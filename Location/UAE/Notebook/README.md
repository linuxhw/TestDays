Linux in UAE - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------

A project to collect tested hardware configurations for Linux in UAE.

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

Total: 199

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Apple         | MacBookAir5,1               | [5c7029f981](https://linux-hardware.org/?probe=5c7029f981) | Dec 23, 2023 |
| Lenovo        | ThinkPad T440p 20AWA02M0... | [c977bbe2c4](https://linux-hardware.org/?probe=c977bbe2c4) | Dec 03, 2023 |
| Acer          | Nitro AN517-55              | [91df918363](https://linux-hardware.org/?probe=91df918363) | Nov 28, 2023 |
| Apple         | MacBookAir6,1               | [e22c72e9d4](https://linux-hardware.org/?probe=e22c72e9d4) | Nov 26, 2023 |
| Apple         | MacBookAir6,1               | [dfa296fd96](https://linux-hardware.org/?probe=dfa296fd96) | Nov 25, 2023 |
| HP            | Laptop 15-dy1xxx            | [9218c25c70](https://linux-hardware.org/?probe=9218c25c70) | Nov 21, 2023 |
| Acer          | Aspire A315-58              | [9c08dba7b5](https://linux-hardware.org/?probe=9c08dba7b5) | Nov 13, 2023 |
| HP            | Laptop 14-dq2xxx            | [e384b513f0](https://linux-hardware.org/?probe=e384b513f0) | Nov 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | [e7f5173a86](https://linux-hardware.org/?probe=e7f5173a86) | Nov 12, 2023 |
| HP            | Laptop 14-dq2xxx            | [0d5d11180c](https://linux-hardware.org/?probe=0d5d11180c) | Nov 07, 2023 |
| Toshiba       | PORTEGE Z10t-A              | [600445b726](https://linux-hardware.org/?probe=600445b726) | Nov 05, 2023 |
| HP            | HPPavilionLaptop15-eh0xx... | [436064bfba](https://linux-hardware.org/?probe=436064bfba) | Nov 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | [92ed6d25c3](https://linux-hardware.org/?probe=92ed6d25c3) | Nov 05, 2023 |
| Toshiba       | Satellite L750              | [f4cbcd5ba1](https://linux-hardware.org/?probe=f4cbcd5ba1) | Nov 05, 2023 |
| Toshiba       | Satellite L750              | [34a347877f](https://linux-hardware.org/?probe=34a347877f) | Nov 05, 2023 |
| Gigabyte      | A5 X1                       | [981be88a61](https://linux-hardware.org/?probe=981be88a61) | Oct 30, 2023 |
| Lenovo        | ThinkPad E490 20N80006UE    | [4bb8e497d3](https://linux-hardware.org/?probe=4bb8e497d3) | Oct 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | [8678e7aace](https://linux-hardware.org/?probe=8678e7aace) | Oct 08, 2023 |
| I-Life Dig... | ZED AIR PRO                 | [7cb30879f6](https://linux-hardware.org/?probe=7cb30879f6) | Sep 28, 2023 |
| Lenovo        | ThinkPad P51 20HHCTO1WW     | [64a85b8eb3](https://linux-hardware.org/?probe=64a85b8eb3) | Sep 28, 2023 |
| Google        | Lick                        | [11aec9d97c](https://linux-hardware.org/?probe=11aec9d97c) | Sep 03, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [0585143fdc](https://linux-hardware.org/?probe=0585143fdc) | Aug 19, 2023 |
| HP            | ProBook 450 G2              | [de0ce7c424](https://linux-hardware.org/?probe=de0ce7c424) | Aug 06, 2023 |
| Dell          | Latitude 3420               | [cdecb64c4a](https://linux-hardware.org/?probe=cdecb64c4a) | Aug 04, 2023 |
| Lenovo        | Z50-70 20354                | [c741db51a0](https://linux-hardware.org/?probe=c741db51a0) | Aug 03, 2023 |
| HP            | ProBook 450 G2              | [18eceddda0](https://linux-hardware.org/?probe=18eceddda0) | Jul 26, 2023 |
| HP            | ProBook 450 G2              | [3466d6ab26](https://linux-hardware.org/?probe=3466d6ab26) | Jul 23, 2023 |
| HP            | ProBook 450 G2              | [94df828438](https://linux-hardware.org/?probe=94df828438) | Jul 22, 2023 |
| Dell          | G15 Special Edition 5521    | [42890cd134](https://linux-hardware.org/?probe=42890cd134) | Jul 04, 2023 |
| Dell          | G15 Special Edition 5521    | [8a3a0f9375](https://linux-hardware.org/?probe=8a3a0f9375) | Jul 04, 2023 |
| ASUSTek       | GL553VD                     | [884a5ecd03](https://linux-hardware.org/?probe=884a5ecd03) | Jun 28, 2023 |
| HP            | Laptop 15-dw2xxx            | [7f41e23d3a](https://linux-hardware.org/?probe=7f41e23d3a) | Jun 23, 2023 |
| HP            | Laptop 15-dw2xxx            | [79ec1a7b3f](https://linux-hardware.org/?probe=79ec1a7b3f) | Jun 23, 2023 |
| Razer         | Blade 15 Advanced Model ... | [7dd15a9fa4](https://linux-hardware.org/?probe=7dd15a9fa4) | Jun 19, 2023 |
| HUAWEI        | KLVD-WXX9                   | [75eeeb7917](https://linux-hardware.org/?probe=75eeeb7917) | Jun 16, 2023 |
| Lenovo        | Yoga Creator 7 15IMH05 8... | [3bcc239452](https://linux-hardware.org/?probe=3bcc239452) | Jun 04, 2023 |
| Valve         | Jupiter                     | [0c81d929ca](https://linux-hardware.org/?probe=0c81d929ca) | Jun 04, 2023 |
| HP            | Laptop 14-dq2xxx            | [589112cb44](https://linux-hardware.org/?probe=589112cb44) | May 25, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [2ae74516a9](https://linux-hardware.org/?probe=2ae74516a9) | May 24, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [cbd7b1dcc7](https://linux-hardware.org/?probe=cbd7b1dcc7) | May 24, 2023 |
| Lenovo        | ThinkPad T490 20N2004JAD    | [c765eed46d](https://linux-hardware.org/?probe=c765eed46d) | May 16, 2023 |
| Toshiba       | Satellite L850-B434         | [54e6cd2fc6](https://linux-hardware.org/?probe=54e6cd2fc6) | May 13, 2023 |
| HUAWEI        | BOHB-WAX9                   | [89747b6213](https://linux-hardware.org/?probe=89747b6213) | May 12, 2023 |
| HP            | Laptop 14-dq2xxx            | [0a639ba55d](https://linux-hardware.org/?probe=0a639ba55d) | May 08, 2023 |
| Acer          | Aspire F5-573G              | [aabb19e388](https://linux-hardware.org/?probe=aabb19e388) | May 06, 2023 |
| HP            | Laptop 14-dq2xxx            | [856494ea85](https://linux-hardware.org/?probe=856494ea85) | May 04, 2023 |
| Valve         | Jupiter                     | [c6e5e310b9](https://linux-hardware.org/?probe=c6e5e310b9) | May 02, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [1704454cdb](https://linux-hardware.org/?probe=1704454cdb) | May 02, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | [d2f8737b9d](https://linux-hardware.org/?probe=d2f8737b9d) | May 02, 2023 |
| Valve         | Jupiter                     | [78a3abdc19](https://linux-hardware.org/?probe=78a3abdc19) | Apr 25, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [59c225df6e](https://linux-hardware.org/?probe=59c225df6e) | Apr 24, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [6e2da1e766](https://linux-hardware.org/?probe=6e2da1e766) | Apr 21, 2023 |
| HP            | ZBook 15 G2                 | [00ed2824f0](https://linux-hardware.org/?probe=00ed2824f0) | Apr 20, 2023 |
| HP            | ZBook 15 G2                 | [7a4242a973](https://linux-hardware.org/?probe=7a4242a973) | Apr 19, 2023 |
| HP            | Laptop 15-dw3xxx            | [a0cf4fd00d](https://linux-hardware.org/?probe=a0cf4fd00d) | Apr 19, 2023 |
| HP            | Laptop 15-dw3xxx            | [7ce26d7fd9](https://linux-hardware.org/?probe=7ce26d7fd9) | Apr 19, 2023 |
| HP            | Pavilion 15                 | [d0c3e2bb4e](https://linux-hardware.org/?probe=d0c3e2bb4e) | Apr 19, 2023 |
| HP            | 15-dc1018ur                 | [7df35a90ad](https://linux-hardware.org/?probe=7df35a90ad) | Apr 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | [a7b2caaba8](https://linux-hardware.org/?probe=a7b2caaba8) | Apr 16, 2023 |
| HP            | Pavilion 15                 | [199f3bb771](https://linux-hardware.org/?probe=199f3bb771) | Apr 14, 2023 |
| Notebook      | NV4XMB,ME,MZ                | [125884d17a](https://linux-hardware.org/?probe=125884d17a) | Apr 05, 2023 |
| Lenovo        | ThinkPad T460s 20FAS1U20... | [99ea485cee](https://linux-hardware.org/?probe=99ea485cee) | Mar 27, 2023 |
| ASUSTek       | Q551LN                      | [3385f39150](https://linux-hardware.org/?probe=3385f39150) | Mar 26, 2023 |
| HP            | Laptop 14-dq2xxx            | [1a46276700](https://linux-hardware.org/?probe=1a46276700) | Mar 05, 2023 |
| Dell          | XPS 13 7390                 | [2a8830034a](https://linux-hardware.org/?probe=2a8830034a) | Feb 26, 2023 |
| Dell          | XPS 13 9370                 | [452bd46c01](https://linux-hardware.org/?probe=452bd46c01) | Feb 22, 2023 |
| Dell          | XPS 13 9370                 | [fe78ef8424](https://linux-hardware.org/?probe=fe78ef8424) | Feb 22, 2023 |
| HP            | Laptop 14-dq2xxx            | [83bef528a7](https://linux-hardware.org/?probe=83bef528a7) | Feb 19, 2023 |
| Lenovo        | G50-80 80E5                 | [64c385ee36](https://linux-hardware.org/?probe=64c385ee36) | Feb 16, 2023 |
| HP            | Laptop 14-dq2xxx            | [54f7f241bf](https://linux-hardware.org/?probe=54f7f241bf) | Feb 15, 2023 |
| HP            | Laptop 14-dq2xxx            | [8fc284c3b5](https://linux-hardware.org/?probe=8fc284c3b5) | Feb 15, 2023 |
| Notebook      | PD5x_7xPNP_PNN_PNT          | [a64ae29757](https://linux-hardware.org/?probe=a64ae29757) | Jan 31, 2023 |
| HP            | Laptop 14-dq2xxx            | [f308688189](https://linux-hardware.org/?probe=f308688189) | Jan 25, 2023 |
| Valve         | Jupiter                     | [83d050bdbe](https://linux-hardware.org/?probe=83d050bdbe) | Jan 25, 2023 |
| HP            | Laptop 14-dq2xxx            | [9a930173a0](https://linux-hardware.org/?probe=9a930173a0) | Jan 24, 2023 |
| Dell          | G5 5587                     | [96ca22c550](https://linux-hardware.org/?probe=96ca22c550) | Jan 21, 2023 |
| Dell          | G5 5587                     | [a070a8ba69](https://linux-hardware.org/?probe=a070a8ba69) | Jan 21, 2023 |
| Acer          | Aspire E5-471P              | [c50e807e64](https://linux-hardware.org/?probe=c50e807e64) | Jan 12, 2023 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | [6d3966411f](https://linux-hardware.org/?probe=6d3966411f) | Jan 09, 2023 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | [1405e2a7c8](https://linux-hardware.org/?probe=1405e2a7c8) | Jan 09, 2023 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | [6206409322](https://linux-hardware.org/?probe=6206409322) | Jan 08, 2023 |
| HP            | EliteBook 2560p             | [89c0ffe36d](https://linux-hardware.org/?probe=89c0ffe36d) | Dec 29, 2022 |
| Lenovo        | Legion Y7000P 81LD          | [d27a1b703b](https://linux-hardware.org/?probe=d27a1b703b) | Dec 26, 2022 |
| Valve         | Jupiter                     | [fae62b5114](https://linux-hardware.org/?probe=fae62b5114) | Dec 11, 2022 |
| MSI           | Modern 14 B5M               | [8277ece293](https://linux-hardware.org/?probe=8277ece293) | Nov 30, 2022 |
| HP            | EliteBook 840 G1            | [7d3eac2c7d](https://linux-hardware.org/?probe=7d3eac2c7d) | Nov 05, 2022 |
| Lenovo        | ThinkPad P1 Gen 5 21DC00... | [910b452558](https://linux-hardware.org/?probe=910b452558) | Oct 30, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [7406489511](https://linux-hardware.org/?probe=7406489511) | Oct 21, 2022 |
| HP            | 250 G5 Notebook PC          | [e8e0acd06e](https://linux-hardware.org/?probe=e8e0acd06e) | Oct 17, 2022 |
| Dell          | XPS 15 7590                 | [fdab72c478](https://linux-hardware.org/?probe=fdab72c478) | Oct 07, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [b1590cf8fa](https://linux-hardware.org/?probe=b1590cf8fa) | Oct 03, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [df5fcf14f9](https://linux-hardware.org/?probe=df5fcf14f9) | Sep 26, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZW... | [472668e67b](https://linux-hardware.org/?probe=472668e67b) | Sep 12, 2022 |
| Lenovo        | ThinkPad T61 76653JG        | [0fae1da16b](https://linux-hardware.org/?probe=0fae1da16b) | Aug 02, 2022 |
| Lenovo        | 81FV                        | [aa9e5c9f73](https://linux-hardware.org/?probe=aa9e5c9f73) | Jul 22, 2022 |
| Lenovo        | ThinkPad T480s 20L7001PA... | [de71ab8780](https://linux-hardware.org/?probe=de71ab8780) | Jul 21, 2022 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [ad2442631e](https://linux-hardware.org/?probe=ad2442631e) | May 28, 2022 |
| HP            | Pavilion Laptop 13-bb0xx... | [ae7d5dbb0c](https://linux-hardware.org/?probe=ae7d5dbb0c) | May 01, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS4... | [28c774c6de](https://linux-hardware.org/?probe=28c774c6de) | Apr 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [718b671125](https://linux-hardware.org/?probe=718b671125) | Apr 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [5e0763131c](https://linux-hardware.org/?probe=5e0763131c) | Mar 28, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [8dda7f6478](https://linux-hardware.org/?probe=8dda7f6478) | Mar 06, 2022 |
| Google        | Terra                       | [54163369b2](https://linux-hardware.org/?probe=54163369b2) | Feb 23, 2022 |
| Dell          | Latitude E6230              | [a8aeb155b0](https://linux-hardware.org/?probe=a8aeb155b0) | Feb 10, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [8aafebe07c](https://linux-hardware.org/?probe=8aafebe07c) | Feb 03, 2022 |
| Dell          | Latitude E5440              | [ebbb8ee138](https://linux-hardware.org/?probe=ebbb8ee138) | Jan 22, 2022 |
| Lenovo        | ThinkPad T480s 20L8S3FV0... | [78080db667](https://linux-hardware.org/?probe=78080db667) | Jan 13, 2022 |
| HP            | EliteBook 840 G6            | [c36553e3a3](https://linux-hardware.org/?probe=c36553e3a3) | Dec 27, 2021 |
| Google        | Akemi                       | [aaf0a3e10e](https://linux-hardware.org/?probe=aaf0a3e10e) | Dec 20, 2021 |
| Dell          | Inspiron 5570               | [927497310e](https://linux-hardware.org/?probe=927497310e) | Nov 16, 2021 |
| win elemen... | MoreFine S500+              | [ace08cf199](https://linux-hardware.org/?probe=ace08cf199) | Nov 11, 2021 |
| win elemen... | MoreFine S500+              | [0e31d4b6fa](https://linux-hardware.org/?probe=0e31d4b6fa) | Nov 11, 2021 |
| MSI           | PS63 Modern 8RD             | [519048dea2](https://linux-hardware.org/?probe=519048dea2) | Nov 01, 2021 |
| MSI           | PS63 Modern 8RD             | [6d3cd2f117](https://linux-hardware.org/?probe=6d3cd2f117) | Nov 01, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [41ff21e8e8](https://linux-hardware.org/?probe=41ff21e8e8) | Oct 06, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [6654adaf99](https://linux-hardware.org/?probe=6654adaf99) | Oct 04, 2021 |
| HP            | ProBook 6475b               | [9d60bf5397](https://linux-hardware.org/?probe=9d60bf5397) | Oct 02, 2021 |
| Apple         | MacBook9,1                  | [888ca9b5de](https://linux-hardware.org/?probe=888ca9b5de) | Sep 04, 2021 |
| Apple         | MacBook9,1                  | [69119d1952](https://linux-hardware.org/?probe=69119d1952) | Sep 04, 2021 |
| Sony          | VGN-NS10J_S                 | [31d1e0e91d](https://linux-hardware.org/?probe=31d1e0e91d) | Aug 12, 2021 |
| LG Electro... | C500-G.AEF5BE1              | [b78f4cd34d](https://linux-hardware.org/?probe=b78f4cd34d) | Jun 14, 2021 |
| Toshiba       | Satellite C850-A966         | [391d22d993](https://linux-hardware.org/?probe=391d22d993) | Jun 02, 2021 |
| Sony          | SVE14A25CAB                 | [78ddb916b5](https://linux-hardware.org/?probe=78ddb916b5) | May 30, 2021 |
| Sony          | SVE14A25CAB                 | [0a2c5cf1cd](https://linux-hardware.org/?probe=0a2c5cf1cd) | May 30, 2021 |
| HP            | Laptop 15s-eq2xxx           | [5707e7ae37](https://linux-hardware.org/?probe=5707e7ae37) | May 28, 2021 |
| HP            | Laptop 15s-eq2xxx           | [66cc8bd4a5](https://linux-hardware.org/?probe=66cc8bd4a5) | May 19, 2021 |
| Dell          | G5 5587                     | [2d2cf67a2d](https://linux-hardware.org/?probe=2d2cf67a2d) | May 08, 2021 |
| Dell          | Latitude E6510              | [06d38294ab](https://linux-hardware.org/?probe=06d38294ab) | May 03, 2021 |
| Lenovo        | Legion Y7000P 81LD          | [e3b22a36fb](https://linux-hardware.org/?probe=e3b22a36fb) | Apr 22, 2021 |
| Lenovo        | Legion Y7000P 81LD          | [f5715022b7](https://linux-hardware.org/?probe=f5715022b7) | Apr 22, 2021 |
| Acer          | Aspire 5755G                | [6b82d5c050](https://linux-hardware.org/?probe=6b82d5c050) | Mar 07, 2021 |
| Acer          | Aspire 5755G                | [227244211b](https://linux-hardware.org/?probe=227244211b) | Mar 07, 2021 |
| HP            | Pavilion Notebook           | [3c9d39abce](https://linux-hardware.org/?probe=3c9d39abce) | Mar 06, 2021 |
| Lenovo        | ThinkPad X230 2325DV8       | [11d5145d10](https://linux-hardware.org/?probe=11d5145d10) | Feb 12, 2021 |
| HP            | Pavilion dv6                | [317b81878c](https://linux-hardware.org/?probe=317b81878c) | Jan 27, 2021 |
| ASUSTek       | Strix GL703GM_GL703GM       | [3d8ea2b061](https://linux-hardware.org/?probe=3d8ea2b061) | Jan 27, 2021 |
| HP            | Laptop 15-da1xxx            | [a3c15a6f74](https://linux-hardware.org/?probe=a3c15a6f74) | Jan 18, 2021 |
| HP            | Laptop 15-da1xxx            | [58bf01b1e7](https://linux-hardware.org/?probe=58bf01b1e7) | Jan 18, 2021 |
| Dell          | Inspiron 3521               | [2e84869a9a](https://linux-hardware.org/?probe=2e84869a9a) | Jan 11, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JM... | [6a02570e23](https://linux-hardware.org/?probe=6a02570e23) | Jan 03, 2021 |
| HP            | Pavilion Sleekbook 15 PC    | [092666f171](https://linux-hardware.org/?probe=092666f171) | Dec 31, 2020 |
| HP            | EliteBook 8460p             | [d24a3c768e](https://linux-hardware.org/?probe=d24a3c768e) | Dec 24, 2020 |
| Dell          | Latitude E6410              | [a2a46d21e9](https://linux-hardware.org/?probe=a2a46d21e9) | Dec 15, 2020 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [e2816ed19c](https://linux-hardware.org/?probe=e2816ed19c) | Nov 27, 2020 |
| HP            | Laptop 15-dw1xxx            | [91e0e6c6bc](https://linux-hardware.org/?probe=91e0e6c6bc) | Nov 04, 2020 |
| HP            | Pavilion Power Laptop 15... | [b1cd303933](https://linux-hardware.org/?probe=b1cd303933) | Oct 08, 2020 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [f9f212a509](https://linux-hardware.org/?probe=f9f212a509) | Oct 01, 2020 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [ab392f30cb](https://linux-hardware.org/?probe=ab392f30cb) | Sep 30, 2020 |
| Acer          | ChiefRiver Platform         | [23e2162b8e](https://linux-hardware.org/?probe=23e2162b8e) | Sep 20, 2020 |
| Dell          | Inspiron 5537               | [4ddf924081](https://linux-hardware.org/?probe=4ddf924081) | Sep 05, 2020 |
| Dell          | Inspiron 5537               | [23a0e05047](https://linux-hardware.org/?probe=23a0e05047) | Sep 05, 2020 |
| Dell          | Latitude E6540              | [9abf14d168](https://linux-hardware.org/?probe=9abf14d168) | Aug 31, 2020 |
| Dell          | Precision 5540              | [76f1cfa736](https://linux-hardware.org/?probe=76f1cfa736) | Aug 23, 2020 |
| I-Life Dig... | ZED AIR                     | [b40d7e9c7c](https://linux-hardware.org/?probe=b40d7e9c7c) | Aug 10, 2020 |
| I-Life Dig... | ZED AIR                     | [5662aa186c](https://linux-hardware.org/?probe=5662aa186c) | Aug 10, 2020 |
| Lenovo        | ThinkPad L480 20LS0012AD    | [81d46e4c4a](https://linux-hardware.org/?probe=81d46e4c4a) | Aug 02, 2020 |
| Toshiba       | Satellite C660              | [670cc8a66c](https://linux-hardware.org/?probe=670cc8a66c) | Jul 26, 2020 |
| Lenovo        | IdeaPadFlex 14 20308        | [aea3470496](https://linux-hardware.org/?probe=aea3470496) | Jul 21, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X420... | [b3dbd3f2af](https://linux-hardware.org/?probe=b3dbd3f2af) | Jul 14, 2020 |
| Toshiba       | TECRA A50-C                 | [adf7a73571](https://linux-hardware.org/?probe=adf7a73571) | Jul 03, 2020 |
| ASUSTek       | FX503VD                     | [d6c0a21749](https://linux-hardware.org/?probe=d6c0a21749) | Jul 02, 2020 |
| HP            | Pavilion 15                 | [499f0c72ee](https://linux-hardware.org/?probe=499f0c72ee) | Jun 29, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X420... | [dd5c9e8d9f](https://linux-hardware.org/?probe=dd5c9e8d9f) | Jun 23, 2020 |
| Dell          | Latitude E6410              | [06055ff260](https://linux-hardware.org/?probe=06055ff260) | Jun 19, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X420... | [b53cc32ed0](https://linux-hardware.org/?probe=b53cc32ed0) | Jun 19, 2020 |
| Lenovo        | G500 20236                  | [fdc9496e84](https://linux-hardware.org/?probe=fdc9496e84) | Jun 19, 2020 |
| Dell          | Latitude E6410              | [1b73d74e65](https://linux-hardware.org/?probe=1b73d74e65) | Jun 09, 2020 |
| Lenovo        | ThinkPad L480 20LS0012AD    | [e9b38b78d7](https://linux-hardware.org/?probe=e9b38b78d7) | May 30, 2020 |
| HP            | Presario C300 (RH208UA#A... | [50e95ff237](https://linux-hardware.org/?probe=50e95ff237) | May 14, 2020 |
| HP            | Presario C300 (RH208UA#A... | [6b4a8eab4c](https://linux-hardware.org/?probe=6b4a8eab4c) | May 14, 2020 |
| Toshiba       | TECRA X40-D                 | [3255796d07](https://linux-hardware.org/?probe=3255796d07) | May 10, 2020 |
| YJKC          | vBOOK Plus RVP7             | [49363e9553](https://linux-hardware.org/?probe=49363e9553) | May 07, 2020 |
| HP            | ProBook 450 G2              | [887a19760b](https://linux-hardware.org/?probe=887a19760b) | May 01, 2020 |
| Lenovo        | ThinkPad X240 20AMS6GB00    | [3fa804be21](https://linux-hardware.org/?probe=3fa804be21) | May 01, 2020 |
| YJKC          | vBOOK Plus RVP7             | [d2328783da](https://linux-hardware.org/?probe=d2328783da) | Apr 24, 2020 |
| Dell          | Vostro 14-5480              | [1bba68101c](https://linux-hardware.org/?probe=1bba68101c) | Apr 20, 2020 |
| HP            | ProBook 450 G2              | [1ef49ff7a3](https://linux-hardware.org/?probe=1ef49ff7a3) | Apr 17, 2020 |
| HP            | Notebook                    | [4f154f82b0](https://linux-hardware.org/?probe=4f154f82b0) | Apr 01, 2020 |
| HP            | Pavilion Notebook           | [5cd86dffe9](https://linux-hardware.org/?probe=5cd86dffe9) | Mar 16, 2020 |
| HP            | ENVY Laptop 13-aq0xxx       | [7f0b4db18a](https://linux-hardware.org/?probe=7f0b4db18a) | Mar 12, 2020 |
| HP            | Pavilion Notebook           | [87df29714d](https://linux-hardware.org/?probe=87df29714d) | Mar 11, 2020 |
| HP            | ENVY Laptop 13-aq0xxx       | [04da794ff5](https://linux-hardware.org/?probe=04da794ff5) | Feb 25, 2020 |
| HP            | EliteBook 2760p             | [40333472c7](https://linux-hardware.org/?probe=40333472c7) | Feb 21, 2020 |
| HP            | ENVY Laptop 13-aq0xxx       | [b12186f161](https://linux-hardware.org/?probe=b12186f161) | Feb 13, 2020 |
| HP            | Notebook                    | [a25a67e533](https://linux-hardware.org/?probe=a25a67e533) | Feb 02, 2020 |
| Lenovo        | ThinkPad T460 20FMS1A200    | [c2a7159d3a](https://linux-hardware.org/?probe=c2a7159d3a) | Jan 04, 2020 |
| Lenovo        | ThinkPad T460 20FMS1A200    | [028d728043](https://linux-hardware.org/?probe=028d728043) | Jan 04, 2020 |
| Lenovo        | Yoga S730-13IWL 81J0        | [d1ca80edff](https://linux-hardware.org/?probe=d1ca80edff) | Dec 24, 2019 |
| Toshiba       | Satellite A300              | [420c738977](https://linux-hardware.org/?probe=420c738977) | Oct 15, 2019 |
| Toshiba       | Satellite A300              | [036dc7e829](https://linux-hardware.org/?probe=036dc7e829) | Oct 15, 2019 |
| Lenovo        | Yoga 2 Pro 20266            | [ab1c14d729](https://linux-hardware.org/?probe=ab1c14d729) | Oct 12, 2019 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [558c01fdce](https://linux-hardware.org/?probe=558c01fdce) | Oct 07, 2019 |
| Notebook      | P95_96_97Ex,Rx              | [d4ad7906b5](https://linux-hardware.org/?probe=d4ad7906b5) | Sep 11, 2019 |
| I-Life Dig... | ZED AIR                     | [514c494f7f](https://linux-hardware.org/?probe=514c494f7f) | Jul 23, 2019 |
| I-Life Dig... | ZED AIR                     | [a9fe92aa3c](https://linux-hardware.org/?probe=a9fe92aa3c) | Jul 23, 2019 |
| HP            | EliteBook 8440p             | [1f8a20b199](https://linux-hardware.org/?probe=1f8a20b199) | May 25, 2019 |
| HP            | EliteBook 8440p             | [60d0e8dd5d](https://linux-hardware.org/?probe=60d0e8dd5d) | May 25, 2019 |
| HP            | ProBook 4540s               | [271be85705](https://linux-hardware.org/?probe=271be85705) | May 15, 2019 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | [ab25f83cd0](https://linux-hardware.org/?probe=ab25f83cd0) | Mar 27, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 24        | 16.33%  |
| Ubuntu 22.04       | 14        | 9.52%   |
| Ubuntu 18.04       | 10        | 6.8%    |
| Pop!_OS 22.04      | 5         | 3.4%    |
| Arch               | 5         | 3.4%    |
| Fedora 38          | 4         | 2.72%   |
| Debian 12          | 4         | 2.72%   |
| Zorin 15           | 3         | 2.04%   |
| Ubuntu 20.10       | 3         | 2.04%   |
| Ubuntu 19.10       | 3         | 2.04%   |
| Kubuntu 22.04      | 3         | 2.04%   |
| Fedora 37          | 3         | 2.04%   |
| Fedora 36          | 3         | 2.04%   |
| Debian 11          | 3         | 2.04%   |
| ArcoLinux Rolling  | 3         | 2.04%   |
| Ubuntu 23.04       | 2         | 1.36%   |
| Ubuntu 22.10       | 2         | 1.36%   |
| Ubuntu 21.10       | 2         | 1.36%   |
| Ubuntu 16.04       | 2         | 1.36%   |
| SteamOS 3.4.6      | 2         | 1.36%   |
| Parrot 6.0         | 2         | 1.36%   |
| Lubuntu 22.04      | 2         | 1.36%   |
| Linux Mint 20.3    | 2         | 1.36%   |
| KDE neon 20.04     | 2         | 1.36%   |
| Kali 2023.1        | 2         | 1.36%   |
| BlackPanther 18.1  | 2         | 1.36%   |
| Arch Rolling       | 2         | 1.36%   |
| Xubuntu 20.04      | 1         | 0.68%   |
| Ubuntu Unity 18.04 | 1         | 0.68%   |
| Ubuntu 23.10       | 1         | 0.68%   |
| Ubuntu 19.04       | 1         | 0.68%   |
| SteamOS 3.4.8      | 1         | 0.68%   |
| SteamOS 3.4.4      | 1         | 0.68%   |
| SteamOS 3.3.2      | 1         | 0.68%   |
| ROSA 12.2          | 1         | 0.68%   |
| Rocky Linux 9.1    | 1         | 0.68%   |
| Pop!_OS 21.10      | 1         | 0.68%   |
| Pop!_OS 20.10      | 1         | 0.68%   |
| Pop!_OS 20.04      | 1         | 0.68%   |
| Parrot 5.3         | 1         | 0.68%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 62        | 42.76%  |
| Fedora       | 11        | 7.59%   |
| Pop!_OS      | 8         | 5.52%   |
| Debian       | 7         | 4.83%   |
| Arch         | 7         | 4.83%   |
| Linux Mint   | 6         | 4.14%   |
| SteamOS      | 5         | 3.45%   |
| OpenMandriva | 5         | 3.45%   |
| Zorin        | 3         | 2.07%   |
| Parrot       | 3         | 2.07%   |
| Manjaro      | 3         | 2.07%   |
| Kubuntu      | 3         | 2.07%   |
| KDE neon     | 3         | 2.07%   |
| ArcoLinux    | 3         | 2.07%   |
| Lubuntu      | 2         | 1.38%   |
| Kali         | 2         | 1.38%   |
| BlackPanther | 2         | 1.38%   |
| Xubuntu      | 1         | 0.69%   |
| Ubuntu Unity | 1         | 0.69%   |
| ROSA         | 1         | 0.69%   |
| Rocky Linux  | 1         | 0.69%   |
| GNOME OS     | 1         | 0.69%   |
| Feren OS     | 1         | 0.69%   |
| Endless      | 1         | 0.69%   |
| Elementary   | 1         | 0.69%   |
| CachyOS      | 1         | 0.69%   |
| Alpine       | 1         | 0.69%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Notebooks | Percent |
|-----------------------------|-----------|---------|
| 5.4.0-42-generic            | 5         | 3.25%   |
| 5.4.0-58-generic            | 4         | 2.6%    |
| 5.13.0-valve36-1-neptune    | 4         | 2.6%    |
| 5.4.0-26-generic            | 3         | 1.95%   |
| 6.4.7-200.fc38.x86_64       | 2         | 1.3%    |
| 6.2.0-33-generic            | 2         | 1.3%    |
| 6.2.0-26-generic            | 2         | 1.3%    |
| 6.1.0-13-amd64              | 2         | 1.3%    |
| 5.4.0-33-generic            | 2         | 1.3%    |
| 5.4.0-29-generic            | 2         | 1.3%    |
| 5.3.0-40-generic            | 2         | 1.3%    |
| 5.3.0-29-generic            | 2         | 1.3%    |
| 5.19.0-42-generic           | 2         | 1.3%    |
| 5.19.0-40-generic           | 2         | 1.3%    |
| 4.15.0-50-generic           | 2         | 1.3%    |
| 6.6.1-zen1-1-zen            | 1         | 0.65%   |
| 6.5.9-zen2-1-zen            | 1         | 0.65%   |
| 6.5.6-76060506-generic      | 1         | 0.65%   |
| 6.5.5-200.fc38.x86_64       | 1         | 0.65%   |
| 6.5.0-3parrot1-amd64        | 1         | 0.65%   |
| 6.5.0-13parrot1-amd64       | 1         | 0.65%   |
| 6.5.0-10-generic            | 1         | 0.65%   |
| 6.4.8-desktop-2omv2390      | 1         | 0.65%   |
| 6.4.8-arch1-1               | 1         | 0.65%   |
| 6.4.0-0.deb12.2-amd64       | 1         | 0.65%   |
| 6.3.8-200.fc38.x86_64       | 1         | 0.65%   |
| 6.3.1-4-cachyos             | 1         | 0.65%   |
| 6.2.7-060207-generic        | 1         | 0.65%   |
| 6.2.6-76060206-generic      | 1         | 0.65%   |
| 6.2.10-200.fc37.x86_64      | 1         | 0.65%   |
| 6.2.0-37-generic            | 1         | 0.65%   |
| 6.2.0-36-generic            | 1         | 0.65%   |
| 6.2.0-20-generic            | 1         | 0.65%   |
| 6.1.8-603.inttf.fc37.x86_64 | 1         | 0.65%   |
| 6.1.6-200.fc37.x86_64       | 1         | 0.65%   |
| 6.1.12-060112-generic       | 1         | 0.65%   |
| 6.1.11-76060111-generic     | 1         | 0.65%   |
| 6.1.1-desktop-1omv2290      | 1         | 0.65%   |
| 6.1.0-kali7-amd64           | 1         | 0.65%   |
| 6.1.0-kali5-amd64           | 1         | 0.65%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 27        | 18%     |
| 5.19.0  | 11        | 7.33%   |
| 4.15.0  | 9         | 6%      |
| 5.15.0  | 8         | 5.33%   |
| 6.2.0   | 7         | 4.67%   |
| 5.8.0   | 7         | 4.67%   |
| 5.13.0  | 7         | 4.67%   |
| 6.1.0   | 5         | 3.33%   |
| 5.3.0   | 5         | 3.33%   |
| 5.11.0  | 5         | 3.33%   |
| 5.10.0  | 4         | 2.67%   |
| 6.5.0   | 3         | 2%      |
| 6.4.8   | 2         | 1.33%   |
| 6.4.7   | 2         | 1.33%   |
| 5.14.0  | 2         | 1.33%   |
| 5.0.0   | 2         | 1.33%   |
| 6.6.1   | 1         | 0.67%   |
| 6.5.9   | 1         | 0.67%   |
| 6.5.6   | 1         | 0.67%   |
| 6.5.5   | 1         | 0.67%   |
| 6.4.0   | 1         | 0.67%   |
| 6.3.8   | 1         | 0.67%   |
| 6.3.1   | 1         | 0.67%   |
| 6.2.7   | 1         | 0.67%   |
| 6.2.6   | 1         | 0.67%   |
| 6.2.10  | 1         | 0.67%   |
| 6.1.8   | 1         | 0.67%   |
| 6.1.6   | 1         | 0.67%   |
| 6.1.12  | 1         | 0.67%   |
| 6.1.11  | 1         | 0.67%   |
| 6.1.1   | 1         | 0.67%   |
| 6.0.6   | 1         | 0.67%   |
| 6.0.12  | 1         | 0.67%   |
| 5.9.3   | 1         | 0.67%   |
| 5.8.5   | 1         | 0.67%   |
| 5.7.6   | 1         | 0.67%   |
| 5.7.14  | 1         | 0.67%   |
| 5.6.16  | 1         | 0.67%   |
| 5.6.14  | 1         | 0.67%   |
| 5.4.68  | 1         | 0.67%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 29        | 19.46%  |
| 5.19    | 13        | 8.72%   |
| 5.15    | 11        | 7.38%   |
| 6.2     | 10        | 6.71%   |
| 6.1     | 10        | 6.71%   |
| 4.15    | 9         | 6.04%   |
| 5.8     | 8         | 5.37%   |
| 5.13    | 7         | 4.7%    |
| 6.5     | 6         | 4.03%   |
| 5.10    | 6         | 4.03%   |
| 6.4     | 5         | 3.36%   |
| 5.3     | 5         | 3.36%   |
| 5.11    | 5         | 3.36%   |
| 5.16    | 4         | 2.68%   |
| 6.3     | 2         | 1.34%   |
| 6.0     | 2         | 1.34%   |
| 5.7     | 2         | 1.34%   |
| 5.6     | 2         | 1.34%   |
| 5.18    | 2         | 1.34%   |
| 5.14    | 2         | 1.34%   |
| 5.0     | 2         | 1.34%   |
| 4.18    | 2         | 1.34%   |
| 6.6     | 1         | 0.67%   |
| 5.9     | 1         | 0.67%   |
| 5.17    | 1         | 0.67%   |
| 4.4     | 1         | 0.67%   |
| 4.19    | 1         | 0.67%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 142       | 99.3%   |
| i686   | 1         | 0.7%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 83        | 56.46%  |
| KDE5       | 27        | 18.37%  |
| Unknown    | 13        | 8.84%   |
| X-Cinnamon | 5         | 3.4%    |
| MATE       | 5         | 3.4%    |
| XFCE       | 4         | 2.72%   |
| KDE        | 4         | 2.72%   |
| LXQt       | 2         | 1.36%   |
| Unity      | 1         | 0.68%   |
| Pantheon   | 1         | 0.68%   |
| DWM        | 1         | 0.68%   |
| awesome    | 1         | 0.68%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 100       | 68.97%  |
| Wayland | 37        | 25.52%  |
| Unknown | 8         | 5.52%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 72        | 49.66%  |
| GDM3    | 23        | 15.86%  |
| SDDM    | 19        | 13.1%   |
| GDM     | 19        | 13.1%   |
| LightDM | 10        | 6.9%    |
| TDM     | 2         | 1.38%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 113       | 77.93%  |
| Unknown | 13        | 8.97%   |
| en_GB   | 7         | 4.83%   |
| ru_RU   | 3         | 2.07%   |
| en_AU   | 2         | 1.38%   |
| C       | 2         | 1.38%   |
| pl_PL   | 1         | 0.69%   |
| hu_HU   | 1         | 0.69%   |
| en_IN   | 1         | 0.69%   |
| el_GR   | 1         | 0.69%   |
| de_DE   | 1         | 0.69%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 83        | 56.85%  |
| BIOS | 63        | 43.15%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 108       | 75.52%  |
| Btrfs   | 19        | 13.29%  |
| Tmpfs   | 6         | 4.2%    |
| Overlay | 6         | 4.2%    |
| Xfs     | 4         | 2.8%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 72        | 49.66%  |
| GPT     | 67        | 46.21%  |
| MBR     | 6         | 4.14%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 133       | 93.01%  |
| Yes       | 10        | 6.99%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 88        | 61.54%  |
| Yes       | 55        | 38.46%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Lenovo                      | 38        | 26.57%  |
| Hewlett-Packard             | 35        | 24.48%  |
| Dell                        | 17        | 11.89%  |
| ASUSTek Computer            | 11        | 7.69%   |
| Toshiba                     | 8         | 5.59%   |
| Acer                        | 6         | 4.2%    |
| Valve                       | 5         | 3.5%    |
| Notebook                    | 3         | 2.1%    |
| Google                      | 3         | 2.1%    |
| Apple                       | 3         | 2.1%    |
| Sony                        | 2         | 1.4%    |
| MSI                         | 2         | 1.4%    |
| I-Life Digital Technologies | 2         | 1.4%    |
| HUAWEI                      | 2         | 1.4%    |
| YJKC                        | 1         | 0.7%    |
| win element                 | 1         | 0.7%    |
| Razer                       | 1         | 0.7%    |
| LG Electronics              | 1         | 0.7%    |
| Gigabyte Technology         | 1         | 0.7%    |
| A-DATA Technology           | 1         | 0.7%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Valve Jupiter                                         | 5         | 3.5%    |
| ASUS VivoBook_ASUSLaptop X1404VA_X1404VA              | 3         | 2.1%    |
| HP ProBook 450 G2                                     | 2         | 1.4%    |
| HP Pavilion Notebook                                  | 2         | 1.4%    |
| HP Pavilion 15                                        | 2         | 1.4%    |
| HP ENVY Laptop 13-aq0xxx                              | 2         | 1.4%    |
| Dell G5 5587                                          | 2         | 1.4%    |
| YJKC vBOOK Plus                                       | 1         | 0.7%    |
| win element MoreFine S500+                            | 1         | 0.7%    |
| Toshiba TECRA X40-D                                   | 1         | 0.7%    |
| Toshiba TECRA A50-C                                   | 1         | 0.7%    |
| Toshiba Satellite L850-B434                           | 1         | 0.7%    |
| Toshiba Satellite L750                                | 1         | 0.7%    |
| Toshiba Satellite C850-A966                           | 1         | 0.7%    |
| Toshiba Satellite C660                                | 1         | 0.7%    |
| Toshiba Satellite A300                                | 1         | 0.7%    |
| Toshiba PORTEGE Z10t-A                                | 1         | 0.7%    |
| Sony VGN-NS10J_S                                      | 1         | 0.7%    |
| Sony SVE14A25CAB                                      | 1         | 0.7%    |
| Razer Blade 15 Advanced Model (Early 2020) - RZ09-033 | 1         | 0.7%    |
| Notebook PD5x_7xPNP_PNN_PNT                           | 1         | 0.7%    |
| Notebook P95_96_97Ex,Rx                               | 1         | 0.7%    |
| Notebook NV4XMB,ME,MZ                                 | 1         | 0.7%    |
| MSI PS63 Modern 8RD                                   | 1         | 0.7%    |
| MSI Modern 14 B5M                                     | 1         | 0.7%    |
| LG C500-G.AEF5BE1                                     | 1         | 0.7%    |
| Lenovo Z50-70 20354                                   | 1         | 0.7%    |
| Lenovo Yoga S730-13IWL 81J0                           | 1         | 0.7%    |
| Lenovo Yoga Creator 7 15IMH05 82DS                    | 1         | 0.7%    |
| Lenovo Yoga 2 Pro 20266                               | 1         | 0.7%    |
| Lenovo ThinkPad X240 20AMS6GB00                       | 1         | 0.7%    |
| Lenovo ThinkPad X230 2325DV8                          | 1         | 0.7%    |
| Lenovo ThinkPad X1 Extreme Gen 3 20TK001HUS           | 1         | 0.7%    |
| Lenovo ThinkPad X1 Carbon Gen 9 20XW00A9US            | 1         | 0.7%    |
| Lenovo ThinkPad T61 76653JG                           | 1         | 0.7%    |
| Lenovo ThinkPad T490 20N2004JAD                       | 1         | 0.7%    |
| Lenovo ThinkPad T480s 20L8S3FV00                      | 1         | 0.7%    |
| Lenovo ThinkPad T480s 20L7001PAD                      | 1         | 0.7%    |
| Lenovo ThinkPad T470 W10DG 20JMS0Q300                 | 1         | 0.7%    |
| Lenovo ThinkPad T460s 20FAS1U207                      | 1         | 0.7%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 19        | 13.29%  |
| Lenovo IdeaPad       | 9         | 6.29%   |
| HP Pavilion          | 9         | 6.29%   |
| HP Laptop            | 7         | 4.9%    |
| HP EliteBook         | 7         | 4.9%    |
| Dell Latitude        | 6         | 4.2%    |
| ASUS VivoBook        | 6         | 4.2%    |
| Valve Jupiter        | 5         | 3.5%    |
| Toshiba Satellite    | 5         | 3.5%    |
| HP ProBook           | 4         | 2.8%    |
| Acer Aspire          | 4         | 2.8%    |
| Lenovo Yoga          | 3         | 2.1%    |
| Dell XPS             | 3         | 2.1%    |
| Dell Inspiron        | 3         | 2.1%    |
| Toshiba TECRA        | 2         | 1.4%    |
| I-Life Digital ZED   | 2         | 1.4%    |
| HP ENVY              | 2         | 1.4%    |
| Dell G5              | 2         | 1.4%    |
| YJKC vBOOK           | 1         | 0.7%    |
| win element MoreFine | 1         | 0.7%    |
| Toshiba PORTEGE      | 1         | 0.7%    |
| Sony VGN-NS10J       | 1         | 0.7%    |
| Sony SVE14A25CAB     | 1         | 0.7%    |
| Razer Blade          | 1         | 0.7%    |
| Notebook PD5x        | 1         | 0.7%    |
| Notebook P95         | 1         | 0.7%    |
| Notebook NV4XMB      | 1         | 0.7%    |
| MSI PS63             | 1         | 0.7%    |
| MSI Modern           | 1         | 0.7%    |
| LG C500-G.AEF5BE1    | 1         | 0.7%    |
| Lenovo Z50-70        | 1         | 0.7%    |
| Lenovo ThinkBook     | 1         | 0.7%    |
| Lenovo Legion        | 1         | 0.7%    |
| Lenovo IdeaPadFlex   | 1         | 0.7%    |
| Lenovo G500          | 1         | 0.7%    |
| Lenovo G50-80        | 1         | 0.7%    |
| Lenovo 81FV          | 1         | 0.7%    |
| HUAWEI KLVD-WXX9     | 1         | 0.7%    |
| HUAWEI BOHB-WAX9     | 1         | 0.7%    |
| HP ZBook             | 1         | 0.7%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 19        | 13.29%  |
| 2020 | 15        | 10.49%  |
| 2013 | 15        | 10.49%  |
| 2019 | 14        | 9.79%   |
| 2018 | 14        | 9.79%   |
| 2022 | 11        | 7.69%   |
| 2017 | 8         | 5.59%   |
| 2016 | 8         | 5.59%   |
| 2012 | 8         | 5.59%   |
| 2014 | 7         | 4.9%    |
| 2015 | 5         | 3.5%    |
| 2011 | 5         | 3.5%    |
| 2010 | 5         | 3.5%    |
| 2023 | 4         | 2.8%    |
| 2008 | 3         | 2.1%    |
| 2007 | 2         | 1.4%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 143       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 125       | 87.41%  |
| Enabled  | 18        | 12.59%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 140       | 97.9%   |
| Yes  | 3         | 2.1%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 33        | 23.08%  |
| 8.01-16.0   | 33        | 23.08%  |
| 16.01-24.0  | 27        | 18.88%  |
| 3.01-4.0    | 22        | 15.38%  |
| 32.01-64.0  | 15        | 10.49%  |
| 64.01-256.0 | 5         | 3.5%    |
| 1.01-2.0    | 3         | 2.1%    |
| 24.01-32.0  | 2         | 1.4%    |
| 2.01-3.0    | 2         | 1.4%    |
| 0.51-1.0    | 1         | 0.7%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 44        | 28.76%  |
| 2.01-3.0  | 40        | 26.14%  |
| 4.01-8.0  | 35        | 22.88%  |
| 3.01-4.0  | 23        | 15.03%  |
| 8.01-16.0 | 5         | 3.27%   |
| 0.51-1.0  | 5         | 3.27%   |
| 0.01-0.5  | 1         | 0.65%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 109       | 76.22%  |
| 2      | 26        | 18.18%  |
| 3      | 4         | 2.8%    |
| 4      | 2         | 1.4%    |
| 0      | 2         | 1.4%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 103       | 72.03%  |
| Yes       | 40        | 27.97%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 98        | 68.53%  |
| No        | 45        | 31.47%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 140       | 97.9%   |
| No        | 3         | 2.1%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 121       | 84.62%  |
| No        | 22        | 15.38%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| UAE     | 143       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Dubai            | 75        | 51.02%  |
| Abu Dhabi        | 34        | 23.13%  |
| Sharjah          | 20        | 13.61%  |
| Al Ain City      | 7         | 4.76%   |
| Ajman            | 7         | 4.76%   |
| Al Fujairah City | 2         | 1.36%   |
| Ras al-Khaimah   | 1         | 0.68%   |
| Al Halah         | 1         | 0.68%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 27        | 27     | 15.43%  |
| WDC                         | 23        | 24     | 13.14%  |
| Seagate                     | 15        | 17     | 8.57%   |
| Toshiba                     | 14        | 14     | 8%      |
| Unknown                     | 11        | 16     | 6.29%   |
| Micron Technology           | 9         | 9      | 5.14%   |
| HGST                        | 9         | 11     | 5.14%   |
| Crucial                     | 9         | 9      | 5.14%   |
| Intel                       | 8         | 9      | 4.57%   |
| Sandisk                     | 7         | 7      | 4%      |
| SK hynix                    | 4         | 5      | 2.29%   |
| Kingston Technology Company | 4         | 4      | 2.29%   |
| Kingston                    | 4         | 4      | 2.29%   |
| Silicon Motion              | 3         | 3      | 1.71%   |
| Hitachi                     | 3         | 3      | 1.71%   |
| Apple                       | 3         | 4      | 1.71%   |
| Realtek Semiconductor       | 2         | 2      | 1.14%   |
| Phison Electronics          | 2         | 2      | 1.14%   |
| Micron/Crucial Technology   | 2         | 2      | 1.14%   |
| ADATA Technology            | 2         | 2      | 1.14%   |
| Team                        | 1         | 1      | 0.57%   |
| Phison                      | 1         | 1      | 0.57%   |
| Patriot                     | 1         | 1      | 0.57%   |
| O2 Micro                    | 1         | 1      | 0.57%   |
| Lite-On                     | 1         | 1      | 0.57%   |
| LaCie                       | 1         | 1      | 0.57%   |
| KIOXIA                      | 1         | 5      | 0.57%   |
| KingSpec                    | 1         | 2      | 0.57%   |
| JMicron Technology          | 1         | 1      | 0.57%   |
| Fujitsu                     | 1         | 1      | 0.57%   |
| External                    | 1         | 1      | 0.57%   |
| China                       | 1         | 1      | 0.57%   |
| ASMT                        | 1         | 2      | 0.57%   |
| A-DATA Technology           | 1         | 1      | 0.57%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| HGST HTS721010A9E630 1TB                              | 5         | 2.76%   |
| WDC WD10SPZX-08Z10 1TB                                | 3         | 1.66%   |
| WDC WD10JPCX-24UE4T0 1TB                              | 3         | 1.66%   |
| Toshiba MQ01ABD075 752GB                              | 3         | 1.66%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB   | 3         | 1.66%   |
| Micron 2400_MTFDKBA512QFM 512GB                       | 3         | 1.66%   |
| Intel NVMe SSD Drive 512GB                            | 3         | 1.66%   |
| HGST HTS725050A7E630 500GB                            | 3         | 1.66%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB                    | 2         | 1.1%    |
| Unknown MMC Card  64GB                                | 2         | 1.1%    |
| Unknown MMC Card  32GB                                | 2         | 1.1%    |
| Unknown MMC Card  16GB                                | 2         | 1.1%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 2         | 1.1%    |
| Seagate ST500LT012-9WS142 500GB                       | 2         | 1.1%    |
| Seagate ST500LT012-1DG142 500GB                       | 2         | 1.1%    |
| Seagate ST2000LM003 HN-M201RAD 2TB                    | 2         | 1.1%    |
| Seagate ST1000LM035-1RK172 1TB                        | 2         | 1.1%    |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB      | 2         | 1.1%    |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB                | 2         | 1.1%    |
| Samsung MZVLQ512HALU-000H1 512GB                      | 2         | 1.1%    |
| Kingston Company OM3PDP3 NVMe SSD 256GB               | 2         | 1.1%    |
| WDC WDS500G2B0A-00SM50 500GB SSD                      | 1         | 0.55%   |
| WDC WDS250G2B0A 250GB SSD                             | 1         | 0.55%   |
| WDC WDS120G1G0A-00SS50 120GB SSD                      | 1         | 0.55%   |
| WDC WDS100T3X0C-00SJG0 1TB                            | 1         | 0.55%   |
| WDC WD5000LPVX-60V0TT0 500GB                          | 1         | 0.55%   |
| WDC WD5000LPCX-22VHAT1 500GB                          | 1         | 0.55%   |
| WDC WD5000BPVT-00A1YT0 500GB                          | 1         | 0.55%   |
| WDC WD2500BEVS-26UST0 250GB                           | 1         | 0.55%   |
| WDC WD1200BEVS-08UST0 120GB                           | 1         | 0.55%   |
| WDC WD10SPZX-24Z10T0 1TB                              | 1         | 0.55%   |
| WDC WD10SPZX-24Z10 1TB                                | 1         | 0.55%   |
| WDC WD10JPVX-60JC3T1 1TB                              | 1         | 0.55%   |
| WDC WD Blue SA510 2.5 500GB                           | 1         | 0.55%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB                  | 1         | 0.55%   |
| WDC PC SN730 SDBPNTY-512G-1101 512GB                  | 1         | 0.55%   |
| Unknown SR64G  64GB                                   | 1         | 0.55%   |
| Unknown SM32G  32GB                                   | 1         | 0.55%   |
| Unknown SL16G  16GB                                   | 1         | 0.55%   |
| Unknown NCard  32GB                                   | 1         | 0.55%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 15        | 17     | 26.79%  |
| WDC      | 14        | 15     | 25%     |
| Toshiba  | 11        | 11     | 19.64%  |
| HGST     | 9         | 11     | 16.07%  |
| Hitachi  | 3         | 3      | 5.36%   |
| Fujitsu  | 1         | 1      | 1.79%   |
| External | 1         | 1      | 1.79%   |
| ASMT     | 1         | 2      | 1.79%   |
| Apple    | 1         | 1      | 1.79%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 6         | 6      | 21.43%  |
| Samsung Electronics | 5         | 5      | 17.86%  |
| WDC                 | 4         | 4      | 14.29%  |
| SanDisk             | 3         | 3      | 10.71%  |
| Toshiba             | 1         | 1      | 3.57%   |
| SK hynix            | 1         | 1      | 3.57%   |
| Patriot             | 1         | 1      | 3.57%   |
| LaCie               | 1         | 1      | 3.57%   |
| Kingston            | 1         | 1      | 3.57%   |
| KingSpec            | 1         | 2      | 3.57%   |
| JMicron Technology  | 1         | 1      | 3.57%   |
| Intel               | 1         | 1      | 3.57%   |
| China               | 1         | 1      | 3.57%   |
| Apple               | 1         | 1      | 3.57%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 73        | 87     | 44.24%  |
| HDD  | 56        | 62     | 33.94%  |
| SSD  | 25        | 29     | 15.15%  |
| MMC  | 11        | 16     | 6.67%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 73        | 87     | 45.34%  |
| SATA | 73        | 86     | 45.34%  |
| MMC  | 11        | 16     | 6.83%   |
| SAS  | 4         | 5      | 2.48%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 44        | 50     | 55.7%   |
| 0.51-1.0   | 33        | 39     | 41.77%  |
| 1.01-2.0   | 2         | 2      | 2.53%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 47        | 32.41%  |
| 101-250        | 34        | 23.45%  |
| 21-50          | 14        | 9.66%   |
| 501-1000       | 14        | 9.66%   |
| 51-100         | 14        | 9.66%   |
| 1001-2000      | 9         | 6.21%   |
| 1-20           | 6         | 4.14%   |
| Unknown        | 4         | 2.76%   |
| 2001-3000      | 2         | 1.38%   |
| More than 3000 | 1         | 0.69%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 65        | 43.33%  |
| 21-50     | 35        | 23.33%  |
| 101-250   | 17        | 11.33%  |
| 51-100    | 14        | 9.33%   |
| 251-500   | 7         | 4.67%   |
| 501-1000  | 5         | 3.33%   |
| Unknown   | 4         | 2.67%   |
| 1001-2000 | 3         | 2%      |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                     | Notebooks | Drives | Percent |
|-----------------------------------------------------------|-----------|--------|---------|
| WDC WD10JPVX-60JC3T1 1TB                                  | 1         | 1      | 20%     |
| WDC WD Blue SA510 2.5 500GB                               | 1         | 1      | 20%     |
| SanDisk SD9SN8W-128G-1006 128GB SSD                       | 1         | 1      | 20%     |
| Samsung Electronics MZVLQ256HBJD-00BH1 256GB              | 1         | 1      | 20%     |
| Realtek Semiconductor RTS5763DL NVMe SSD Controller 512GB | 1         | 1      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Notebooks | Drives | Percent |
|-----------------------|-----------|--------|---------|
| WDC                   | 2         | 2      | 40%     |
| SanDisk               | 1         | 1      | 20%     |
| Samsung Electronics   | 1         | 1      | 20%     |
| Realtek Semiconductor | 1         | 1      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 2         | 2      | 40%     |
| SSD  | 2         | 2      | 40%     |
| HDD  | 1         | 1      | 20%     |

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
| Detected | 90        | 124    | 60%     |
| Works    | 55        | 65     | 36.67%  |
| Malfunc  | 5         | 5      | 3.33%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 98        | 57.31%  |
| Samsung Electronics          | 22        | 12.87%  |
| Micron Technology            | 9         | 5.26%   |
| SanDisk                      | 8         | 4.68%   |
| Kingston Technology Company  | 7         | 4.09%   |
| Silicon Motion               | 4         | 2.34%   |
| Micron/Crucial Technology    | 4         | 2.34%   |
| SK hynix                     | 3         | 1.75%   |
| Phison Electronics           | 3         | 1.75%   |
| Toshiba America Info Systems | 2         | 1.17%   |
| Realtek Semiconductor        | 2         | 1.17%   |
| AMD                          | 2         | 1.17%   |
| ADATA Technology             | 2         | 1.17%   |
| O2 Micro                     | 1         | 0.58%   |
| Marvell Technology Group     | 1         | 0.58%   |
| Lite-On Technology           | 1         | 0.58%   |
| KIOXIA                       | 1         | 0.58%   |
| Apple                        | 1         | 0.58%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 15        | 8.29%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 11        | 6.08%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 11        | 6.08%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 10        | 5.52%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 9         | 4.97%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 8         | 4.42%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 8         | 4.42%   |
| Intel Volume Management Device NVMe RAID Controller                            | 7         | 3.87%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 7         | 3.87%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 6         | 3.31%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 5         | 2.76%   |
| Intel SSD 660P Series                                                          | 5         | 2.76%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 1.66%   |
| Micron 2400 NVMe SSD (DRAM-less)                                               | 3         | 1.66%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 3         | 1.66%   |
| Intel Tiger Lake-LP SATA Controller                                            | 3         | 1.66%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 1.66%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 2         | 1.1%    |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 2         | 1.1%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 1.1%    |
| Phison E12 NVMe Controller                                                     | 2         | 1.1%    |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                           | 2         | 1.1%    |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 2         | 1.1%    |
| Micron 3400 NVMe SSD [Hendrix]                                                 | 2         | 1.1%    |
| Micron 2210 NVMe SSD [Cobain]                                                  | 2         | 1.1%    |
| Kingston Company OM3PDP3 NVMe SSD                                              | 2         | 1.1%    |
| Kingston Company NV2 NVMe SSD SM2267XT                                         | 2         | 1.1%    |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 2         | 1.1%    |
| Intel Comet Lake SATA AHCI Controller                                          | 2         | 1.1%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 1.1%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 1.1%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 1.1%    |
| AMD FCH SATA Controller [AHCI mode]                                            | 2         | 1.1%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 0.55%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)            | 1         | 0.55%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 1         | 0.55%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 1         | 0.55%   |
| Silicon Motion Non-Volatile memory controller                                  | 1         | 0.55%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                          | 1         | 0.55%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                    | 1         | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 75        | 42.61%  |
| NVMe | 73        | 41.48%  |
| RAID | 25        | 14.2%   |
| IDE  | 3         | 1.7%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 127       | 88.81%  |
| AMD    | 16        | 11.19%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz       | 5         | 3.5%    |
| Intel Core i5-4200U CPU @ 1.60GHz       | 5         | 3.5%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 5         | 3.5%    |
| AMD Custom APU 0405                     | 5         | 3.5%    |
| Intel Core i7-8750H CPU @ 2.20GHz       | 4         | 2.8%    |
| Intel Core i7-8550U CPU @ 1.80GHz       | 4         | 2.8%    |
| Intel Core i5-8265U CPU @ 1.60GHz       | 4         | 2.8%    |
| Intel 12th Gen Core i7-12700H           | 4         | 2.8%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 3         | 2.1%    |
| Intel Core i7-7500U CPU @ 2.70GHz       | 3         | 2.1%    |
| Intel Core i7-5500U CPU @ 2.40GHz       | 3         | 2.1%    |
| Intel Core i5-10210U CPU @ 1.60GHz      | 3         | 2.1%    |
| Intel 13th Gen Core i7-1355U            | 3         | 2.1%    |
| AMD Ryzen 9 5900HX with Radeon Graphics | 3         | 2.1%    |
| Intel Core i9-10885H CPU @ 2.40GHz      | 2         | 1.4%    |
| Intel Core i7-6500U CPU @ 2.50GHz       | 2         | 1.4%    |
| Intel Core i7-3632QM CPU @ 2.20GHz      | 2         | 1.4%    |
| Intel Core i7-10750H CPU @ 2.60GHz      | 2         | 1.4%    |
| Intel Core i5-6300U CPU @ 2.40GHz       | 2         | 1.4%    |
| Intel Core i5-4210U CPU @ 1.70GHz       | 2         | 1.4%    |
| Intel Core i5-3317U CPU @ 1.70GHz       | 2         | 1.4%    |
| Intel Core i5-2450M CPU @ 2.50GHz       | 2         | 1.4%    |
| Intel Core i5-2410M CPU @ 2.30GHz       | 2         | 1.4%    |
| Intel Core i3-4005U CPU @ 1.70GHz       | 2         | 1.4%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 2         | 1.4%    |
| AMD Ryzen 5 5500U with Radeon Graphics  | 2         | 1.4%    |
| Intel Core m5-6Y54 CPU @ 1.10GHz        | 1         | 0.7%    |
| Intel Core i9-9980HK CPU @ 2.40GHz      | 1         | 0.7%    |
| Intel Core i9-8950HK CPU @ 2.90GHz      | 1         | 0.7%    |
| Intel Core i7-9850H CPU @ 2.60GHz       | 1         | 0.7%    |
| Intel Core i7-9750H CPU @ 2.60GHz       | 1         | 0.7%    |
| Intel Core i7-8650U CPU @ 1.90GHz       | 1         | 0.7%    |
| Intel Core i7-7820HQ CPU @ 2.90GHz      | 1         | 0.7%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 1         | 0.7%    |
| Intel Core i7-6600U CPU @ 2.60GHz       | 1         | 0.7%    |
| Intel Core i7-4910MQ CPU @ 2.90GHz      | 1         | 0.7%    |
| Intel Core i7-4600M CPU @ 2.90GHz       | 1         | 0.7%    |
| Intel Core i7-4510U CPU @ 2.00GHz       | 1         | 0.7%    |
| Intel Core i7-3630QM CPU @ 2.40GHz      | 1         | 0.7%    |
| Intel Core i7-2640M CPU @ 2.80GHz       | 1         | 0.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i7    | 42        | 29.37%  |
| Intel Core i5    | 41        | 28.67%  |
| Other            | 25        | 17.48%  |
| Intel Core i3    | 8         | 5.59%   |
| Intel Celeron    | 5         | 3.5%    |
| Intel Core i9    | 4         | 2.8%    |
| AMD Ryzen 5      | 4         | 2.8%    |
| Intel Core 2 Duo | 3         | 2.1%    |
| AMD Ryzen 9      | 3         | 2.1%    |
| Intel Atom       | 2         | 1.4%    |
| AMD Ryzen 7      | 2         | 1.4%    |
| Intel Core m5    | 1         | 0.7%    |
| Intel Celeron M  | 1         | 0.7%    |
| AMD Ryzen 7 PRO  | 1         | 0.7%    |
| AMD A6           | 1         | 0.7%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 61        | 42.66%  |
| 4      | 47        | 32.87%  |
| 6      | 13        | 9.09%   |
| 8      | 11        | 7.69%   |
| 14     | 5         | 3.5%    |
| 10     | 3         | 2.1%    |
| 1      | 2         | 1.4%    |
| 12     | 1         | 0.7%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 143       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 128       | 89.51%  |
| 1      | 15        | 10.49%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 142       | 99.3%   |
| 32-bit         | 1         | 0.7%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 49        | 34.03%  |
| 0x806c1    | 8         | 5.56%   |
| 0x406e3    | 7         | 4.86%   |
| 0x40651    | 7         | 4.86%   |
| 0x306a9    | 7         | 4.86%   |
| 0x206a7    | 7         | 4.86%   |
| 0x906ea    | 6         | 4.17%   |
| 0x806ec    | 5         | 3.47%   |
| 0x806ea    | 5         | 3.47%   |
| 0x906a3    | 4         | 2.78%   |
| 0x806e9    | 4         | 2.78%   |
| 0xa0652    | 3         | 2.08%   |
| 0x906e9    | 3         | 2.08%   |
| 0x20655    | 3         | 2.08%   |
| 0x0a50000c | 3         | 2.08%   |
| 0x906ed    | 2         | 1.39%   |
| 0x806eb    | 2         | 1.39%   |
| 0x6fd      | 2         | 1.39%   |
| 0x306d4    | 2         | 1.39%   |
| 0xb06a3    | 1         | 0.69%   |
| 0x806d1    | 1         | 0.69%   |
| 0x706a1    | 1         | 0.69%   |
| 0x6fb      | 1         | 0.69%   |
| 0x6e8      | 1         | 0.69%   |
| 0x506e3    | 1         | 0.69%   |
| 0x406c4    | 1         | 0.69%   |
| 0x406c3    | 1         | 0.69%   |
| 0x306c3    | 1         | 0.69%   |
| 0x20652    | 1         | 0.69%   |
| 0x08608103 | 1         | 0.69%   |
| 0x08608102 | 1         | 0.69%   |
| 0x08600106 | 1         | 0.69%   |
| 0x08108109 | 1         | 0.69%   |
| 0x06001119 | 1         | 0.69%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 37        | 25.87%  |
| Haswell          | 16        | 11.19%  |
| TigerLake        | 10        | 6.99%   |
| SandyBridge      | 10        | 6.99%   |
| IvyBridge        | 10        | 6.99%   |
| Unknown          | 9         | 6.29%   |
| Skylake          | 8         | 5.59%   |
| Alderlake Hybrid | 7         | 4.9%    |
| CometLake        | 6         | 4.2%    |
| Zen 3            | 5         | 3.5%    |
| Broadwell        | 5         | 3.5%    |
| Westmere         | 4         | 2.8%    |
| Silvermont       | 3         | 2.1%    |
| IceLake          | 3         | 2.1%    |
| Core             | 3         | 2.1%    |
| Zen 2            | 2         | 1.4%    |
| Goldmont plus    | 2         | 1.4%    |
| Zen+             | 1         | 0.7%    |
| Piledriver       | 1         | 0.7%    |
| P6               | 1         | 0.7%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 118       | 58.42%  |
| Nvidia | 54        | 26.73%  |
| AMD    | 30        | 14.85%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 13        | 6.4%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 9         | 4.43%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 9         | 4.43%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 8         | 3.94%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 8         | 3.94%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 7         | 3.45%   |
| Intel UHD Graphics 620                                                                   | 6         | 2.96%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 6         | 2.96%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 6         | 2.96%   |
| Intel HD Graphics 620                                                                    | 5         | 2.46%   |
| Intel HD Graphics 5500                                                                   | 5         | 2.46%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 5         | 2.46%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 5         | 2.46%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 5         | 2.46%   |
| Intel HD Graphics 630                                                                    | 4         | 1.97%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 1.97%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 1.48%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 3         | 1.48%   |
| Nvidia GM108M [GeForce MX130]                                                            | 3         | 1.48%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 3         | 1.48%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 3         | 1.48%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 1.48%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.48%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 3         | 1.48%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 3         | 1.48%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 0.99%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 0.99%   |
| Nvidia GP108BM [GeForce MX250]                                                           | 2         | 0.99%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.99%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 2         | 0.99%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 0.99%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 2         | 0.99%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 2         | 0.99%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 0.99%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 0.99%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 0.99%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 2         | 0.99%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 2         | 0.99%   |
| AMD Lucienne                                                                             | 2         | 0.99%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.49%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 62        | 43.36%  |
| Intel + Nvidia | 44        | 30.77%  |
| 1 x AMD        | 15        | 10.49%  |
| Intel + AMD    | 12        | 8.39%   |
| 1 x Nvidia     | 7         | 4.9%    |
| AMD + Nvidia   | 3         | 2.1%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 116       | 81.12%  |
| Proprietary | 25        | 17.48%  |
| Unknown     | 2         | 1.4%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 93        | 65.03%  |
| 1.01-2.0   | 21        | 14.69%  |
| 3.01-4.0   | 13        | 9.09%   |
| 0.01-0.5   | 8         | 5.59%   |
| 0.51-1.0   | 5         | 3.5%    |
| 5.01-6.0   | 3         | 2.1%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 28        | 17.95%  |
| AU Optronics            | 28        | 17.95%  |
| Chimei Innolux          | 22        | 14.1%   |
| LG Display              | 21        | 13.46%  |
| Samsung Electronics     | 15        | 9.62%   |
| Valve                   | 4         | 2.56%   |
| Goldstar                | 4         | 2.56%   |
| CSO                     | 4         | 2.56%   |
| Sharp                   | 3         | 1.92%   |
| InfoVision              | 3         | 1.92%   |
| Dell                    | 3         | 1.92%   |
| BenQ                    | 3         | 1.92%   |
| Apple                   | 3         | 1.92%   |
| LGD                     | 2         | 1.28%   |
| LG Philips              | 2         | 1.28%   |
| Hewlett-Packard         | 2         | 1.28%   |
| Chi Mei Optoelectronics | 2         | 1.28%   |
| ASUSTek Computer        | 2         | 1.28%   |
| Seiko/Epson             | 1         | 0.64%   |
| Lenovo                  | 1         | 0.64%   |
| CMN                     | 1         | 0.64%   |
| Ancor Communications    | 1         | 0.64%   |
| Analogix                | 1         | 0.64%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch        | 5         | 3.18%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                     | 4         | 2.55%   |
| LGD LCD Monitor 1366x768                                                | 2         | 1.27%   |
| LG Display LCD Monitor LGD0575 1920x1080 309x174mm 14.0-inch            | 2         | 1.27%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch             | 2         | 1.27%   |
| CSO LCD Monitor CSO1603 2560x1600 344x215mm 16.0-inch                   | 2         | 1.27%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch        | 2         | 1.27%   |
| BOE LCD Monitor BOE06B3 1366x768 309x173mm 13.9-inch                    | 2         | 1.27%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                   | 2         | 1.27%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                    | 2         | 1.27%   |
| AU Optronics LCD Monitor AUO272B 3840x2160 293x165mm 13.2-inch          | 2         | 1.27%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch          | 2         | 1.27%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch          | 2         | 1.27%   |
| ASUSTek Computer PG32UQ AUS32E1 3840x2160 708x399mm 32.0-inch           | 2         | 1.27%   |
| Apple Color LCD APP9CF2 1366x768 256x144mm 11.6-inch                    | 2         | 1.27%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                 | 1         | 0.64%   |
| Sharp LCD Monitor SHP14B9 3840x2160 344x194mm 15.5-inch                 | 1         | 0.64%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch                 | 1         | 0.64%   |
| Seiko/Epson LCD Monitor 1280x800                                        | 1         | 0.64%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch       | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SEC5741 1280x800 261x163mm 12.1-inch    | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch    | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch    | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch    | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch    | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch   | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SDC4341 1366x768 344x194mm 15.5-inch    | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SDC424A 3200x1800 293x165mm 13.2-inch   | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SDC416D 2880x1800 312x195mm 14.5-inch   | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SDC4157 3840x2160 344x194mm 15.5-inch   | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SAM0FEF 3840x2160 1872x1053mm 84.6-inch | 1         | 0.64%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch       | 1         | 0.64%   |
| Samsung Electronics C27R50x SAM0F9D 1920x1080 598x336mm 27.0-inch       | 1         | 0.64%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 1         | 0.64%   |
| LG Philips LP154WX4-TLC8 LPL0120 1280x800 331x207mm 15.4-inch           | 1         | 0.64%   |
| LG Philips LCD Monitor LPL2A00 1280x800 330x210mm 15.4-inch             | 1         | 0.64%   |
| LG Display LCD Monitor LGD065B 1920x1080 382x215mm 17.3-inch            | 1         | 0.64%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch            | 1         | 0.64%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch            | 1         | 0.64%   |
| LG Display LCD Monitor LGD05D0 1920x1080 344x194mm 15.5-inch            | 1         | 0.64%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 68        | 45.03%  |
| 1366x768 (WXGA)   | 46        | 30.46%  |
| 3840x2160 (4K)    | 9         | 5.96%   |
| 800x1280          | 5         | 3.31%   |
| 1280x800 (WXGA)   | 4         | 2.65%   |
| 2560x1600         | 3         | 1.99%   |
| 2560x1440 (QHD)   | 3         | 1.99%   |
| 1920x1200 (WUXGA) | 3         | 1.99%   |
| 2880x1800         | 2         | 1.32%   |
| 1600x900 (HD+)    | 2         | 1.32%   |
| 3200x1800 (QHD+)  | 1         | 0.66%   |
| 2880x1920         | 1         | 0.66%   |
| 2560x1080         | 1         | 0.66%   |
| 2304x1440         | 1         | 0.66%   |
| 2160x1440         | 1         | 0.66%   |
| 1440x900 (WXGA+)  | 1         | 0.66%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 56        | 35.67%  |
| 14      | 26        | 16.56%  |
| 13      | 26        | 16.56%  |
| 12      | 6         | 3.82%   |
| 11      | 6         | 3.82%   |
| 27      | 5         | 3.18%   |
| 16      | 5         | 3.18%   |
| 21      | 4         | 2.55%   |
| 7       | 4         | 2.55%   |
| Unknown | 4         | 2.55%   |
| 23      | 3         | 1.91%   |
| 17      | 3         | 1.91%   |
| 32      | 2         | 1.27%   |
| 24      | 2         | 1.27%   |
| 84      | 1         | 0.64%   |
| 40      | 1         | 0.64%   |
| 34      | 1         | 0.64%   |
| 31      | 1         | 0.64%   |
| 3       | 1         | 0.64%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 100       | 63.69%  |
| 201-300     | 23        | 14.65%  |
| 501-600     | 10        | 6.37%   |
| 351-400     | 5         | 3.18%   |
| 1-100       | 5         | 3.18%   |
| 401-500     | 4         | 2.55%   |
| Unknown     | 4         | 2.55%   |
| 701-800     | 3         | 1.91%   |
| 801-900     | 1         | 0.64%   |
| 601-700     | 1         | 0.64%   |
| 1501-2000   | 1         | 0.64%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 119       | 83.22%  |
| 16/10   | 13        | 9.09%   |
| 0.67    | 4         | 2.8%    |
| Unknown | 4         | 2.8%    |
| 6/5     | 1         | 0.7%    |
| 3/2     | 1         | 0.7%    |
| 21/9    | 1         | 0.7%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 56        | 35.67%  |
| 81-90          | 41        | 26.11%  |
| 71-80          | 10        | 6.37%   |
| 201-250        | 8         | 5.1%    |
| 61-70          | 6         | 3.82%   |
| 51-60          | 6         | 3.82%   |
| 1-40           | 5         | 3.18%   |
| 301-350        | 5         | 3.18%   |
| 111-120        | 5         | 3.18%   |
| 351-500        | 4         | 2.55%   |
| Unknown        | 4         | 2.55%   |
| 121-130        | 3         | 1.91%   |
| More than 1000 | 1         | 0.64%   |
| 251-300        | 1         | 0.64%   |
| 501-1000       | 1         | 0.64%   |
| 91-100         | 1         | 0.64%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 69        | 44.52%  |
| 101-120       | 39        | 25.16%  |
| 161-240       | 18        | 11.61%  |
| 51-100        | 16        | 10.32%  |
| More than 240 | 9         | 5.81%   |
| Unknown       | 4         | 2.58%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 118       | 82.52%  |
| 2     | 20        | 13.99%  |
| 0     | 4         | 2.8%    |
| 3     | 1         | 0.7%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 88        | 41.71%  |
| Realtek Semiconductor    | 72        | 34.12%  |
| Qualcomm Atheros         | 20        | 9.48%   |
| Broadcom                 | 8         | 3.79%   |
| Ralink                   | 5         | 2.37%   |
| MediaTek                 | 5         | 2.37%   |
| Xiaomi                   | 3         | 1.42%   |
| TP-Link                  | 3         | 1.42%   |
| Broadcom Limited         | 2         | 0.95%   |
| Sierra Wireless          | 1         | 0.47%   |
| Ralink Technology        | 1         | 0.47%   |
| Marvell Technology Group | 1         | 0.47%   |
| Lenovo                   | 1         | 0.47%   |
| ASIX Electronics         | 1         | 0.47%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 38        | 15.26%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 15        | 6.02%   |
| Intel Wi-Fi 6 AX201                                               | 9         | 3.61%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 8         | 3.21%   |
| Intel Wireless 7260                                               | 7         | 2.81%   |
| Intel Wireless 8265 / 8275                                        | 6         | 2.41%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 6         | 2.41%   |
| Intel Wi-Fi 6 AX200                                               | 5         | 2.01%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 5         | 2.01%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 5         | 2.01%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 5         | 2.01%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 2.01%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.61%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 1.61%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 4         | 1.61%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 1.61%   |
| Intel Wireless 7265                                               | 4         | 1.61%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 3         | 1.2%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 1.2%    |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 1.2%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 1.2%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3         | 1.2%    |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                 | 3         | 1.2%    |
| Intel Wireless 8260                                               | 3         | 1.2%    |
| Intel Wireless 3165                                               | 3         | 1.2%    |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.2%    |
| Intel Ethernet Connection I218-LM                                 | 3         | 1.2%    |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.2%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 1.2%    |
| Intel Centrino Advanced-N 6235                                    | 3         | 1.2%    |
| Intel 82577LM Gigabit Network Connection                          | 3         | 1.2%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 2         | 0.8%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 2         | 0.8%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 0.8%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 0.8%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.8%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.8%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 0.8%    |
| Intel Wireless-AC 9260                                            | 2         | 0.8%    |
| Intel Wireless 3160                                               | 2         | 0.8%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 84        | 56.76%  |
| Realtek Semiconductor | 24        | 16.22%  |
| Qualcomm Atheros      | 16        | 10.81%  |
| Broadcom              | 7         | 4.73%   |
| Ralink                | 5         | 3.38%   |
| MediaTek              | 5         | 3.38%   |
| TP-Link               | 3         | 2.03%   |
| Broadcom Limited      | 2         | 1.35%   |
| Sierra Wireless       | 1         | 0.68%   |
| Ralink Technology     | 1         | 0.68%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                            | 9         | 6.08%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 8         | 5.41%   |
| Intel Wireless 7260                                            | 7         | 4.73%   |
| Intel Wireless 8265 / 8275                                     | 6         | 4.05%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 6         | 4.05%   |
| Intel Wi-Fi 6 AX200                                            | 5         | 3.38%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 5         | 3.38%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 5         | 3.38%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 5         | 3.38%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 4         | 2.7%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 4         | 2.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 4         | 2.7%    |
| Intel Wireless 7265                                            | 4         | 2.7%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 3         | 2.03%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 3         | 2.03%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 3         | 2.03%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter              | 3         | 2.03%   |
| Intel Wireless 8260                                            | 3         | 2.03%   |
| Intel Wireless 3165                                            | 3         | 2.03%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 3         | 2.03%   |
| Intel Centrino Advanced-N 6235                                 | 3         | 2.03%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 2         | 1.35%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 2         | 1.35%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2         | 1.35%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 1.35%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 1.35%   |
| Intel Wireless-AC 9260                                         | 2         | 1.35%   |
| Intel Wireless 3160                                            | 2         | 1.35%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 2         | 1.35%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 2         | 1.35%   |
| Intel Centrino Ultimate-N 6300                                 | 2         | 1.35%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 2         | 1.35%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 2         | 1.35%   |
| TP-Link 802.11ac WLAN Adapter                                  | 1         | 0.68%   |
| Sierra Wireless EM7455                                         | 1         | 0.68%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.68%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 1         | 0.68%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 1         | 0.68%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 0.68%   |
| Realtek 802.11n WLAN Adapter                                   | 1         | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 61        | 61.62%  |
| Intel                    | 26        | 26.26%  |
| Qualcomm Atheros         | 5         | 5.05%   |
| Xiaomi                   | 3         | 3.03%   |
| Marvell Technology Group | 1         | 1.01%   |
| Lenovo                   | 1         | 1.01%   |
| Broadcom                 | 1         | 1.01%   |
| ASIX Electronics         | 1         | 1.01%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 38        | 37.62%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 15        | 14.85%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 4.95%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 3.96%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 3         | 2.97%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 2.97%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 2.97%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 2.97%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 2.97%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 2.97%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 1.98%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 1.98%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.98%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 1.98%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.99%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.99%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.99%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.99%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.99%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 0.99%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.99%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.99%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 0.99%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.99%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 0.99%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 0.99%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 0.99%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 140       | 59.07%  |
| Ethernet | 97        | 40.93%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 120       | 85.71%  |
| Ethernet | 20        | 14.29%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 91        | 63.64%  |
| 1     | 50        | 34.97%  |
| 0     | 2         | 1.4%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 103       | 71.53%  |
| Yes  | 41        | 28.47%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 68        | 56.2%   |
| Realtek Semiconductor           | 12        | 9.92%   |
| Qualcomm Atheros Communications | 9         | 7.44%   |
| IMC Networks                    | 8         | 6.61%   |
| Toshiba                         | 4         | 3.31%   |
| Ralink                          | 4         | 3.31%   |
| Foxconn / Hon Hai               | 4         | 3.31%   |
| Broadcom                        | 4         | 3.31%   |
| Hewlett-Packard                 | 2         | 1.65%   |
| Dell                            | 2         | 1.65%   |
| Apple                           | 2         | 1.65%   |
| MediaTek                        | 1         | 0.83%   |
| Lite-On Technology              | 1         | 0.83%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface               | 20        | 16.53%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)   | 18        | 14.88%  |
| Intel AX201 Bluetooth                            | 15        | 12.4%   |
| Realtek Bluetooth Radio                          | 7         | 5.79%   |
| Intel AX200 Bluetooth                            | 5         | 4.13%   |
| IMC Networks Bluetooth Radio                     | 5         | 4.13%   |
| Ralink RT3290 Bluetooth                          | 4         | 3.31%   |
| Realtek 802.11ac WLAN Adapter                    | 3         | 2.48%   |
| Qualcomm Atheros  Bluetooth Device               | 3         | 2.48%   |
| Intel Centrino Bluetooth Wireless Transceiver    | 3         | 2.48%   |
| Intel Bluetooth Device                           | 3         | 2.48%   |
| IMC Networks Wireless_Device                     | 3         | 2.48%   |
| Toshiba Bluetooth USB Host Controller            | 2         | 1.65%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter          | 2         | 1.65%   |
| Qualcomm Atheros AR3011 Bluetooth                | 2         | 1.65%   |
| Intel Wireless-AC 9260 Bluetooth Adapter         | 2         | 1.65%   |
| Intel AX210 Bluetooth                            | 2         | 1.65%   |
| HP Broadcom 2070 Bluetooth Combo                 | 2         | 1.65%   |
| Foxconn / Hon Hai Bluetooth Device               | 2         | 1.65%   |
| Toshiba RT Bluetooth Radio                       | 1         | 0.83%   |
| Toshiba Integrated Bluetooth HCI                 | 1         | 0.83%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0           | 1         | 0.83%   |
| Qualcomm Atheros Bluetooth USB Host Controller   | 1         | 0.83%   |
| Qualcomm Atheros AR9462 Bluetooth                | 1         | 0.83%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0            | 1         | 0.83%   |
| MediaTek Wireless_Device                         | 1         | 0.83%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth       | 1         | 0.83%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter     | 1         | 0.83%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller  | 1         | 0.83%   |
| Dell DW375 Bluetooth Module                      | 1         | 0.83%   |
| Dell BCM20702A0 Bluetooth Module                 | 1         | 0.83%   |
| Broadcom HP Portable SoftSailing                 | 1         | 0.83%   |
| Broadcom BCM43142A0 Bluetooth 4.0                | 1         | 0.83%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]       | 1         | 0.83%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller] | 1         | 0.83%   |
| Apple Built-in Bluetooth 2.0+EDR HCI             | 1         | 0.83%   |
| Apple Bluetooth USB Host Controller              | 1         | 0.83%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 126       | 70%     |
| Nvidia                | 29        | 16.11%  |
| AMD                   | 17        | 9.44%   |
| Lenovo                | 2         | 1.11%   |
| JMTek                 | 2         | 1.11%   |
| SteelSeries ApS       | 1         | 0.56%   |
| Samsung Electronics   | 1         | 0.56%   |
| Realtek Semiconductor | 1         | 0.56%   |
| Logitech              | 1         | 0.56%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 18        | 8.57%   |
| Intel Haswell-ULT HD Audio Controller                                      | 13        | 6.19%   |
| Intel 8 Series HD Audio Controller                                         | 13        | 6.19%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 13        | 6.19%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 10        | 4.76%   |
| AMD Family 17h/19h HD Audio Controller                                     | 10        | 4.76%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 9         | 4.29%   |
| Intel Cannon Lake PCH cAVS                                                 | 9         | 4.29%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 8         | 3.81%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 7         | 3.33%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 6         | 2.86%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 5         | 2.38%   |
| Intel Comet Lake PCH-LP cAVS                                               | 5         | 2.38%   |
| Intel Comet Lake PCH cAVS                                                  | 5         | 2.38%   |
| Intel Broadwell-U Audio Controller                                         | 5         | 2.38%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 5         | 2.38%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4         | 1.9%    |
| Intel CM238 HD Audio Controller                                            | 4         | 1.9%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 1.9%    |
| Nvidia GP107GL High Definition Audio Controller                            | 3         | 1.43%   |
| Nvidia GP106 High Definition Audio Controller                              | 3         | 1.43%   |
| Nvidia GA106 High Definition Audio Controller                              | 3         | 1.43%   |
| Nvidia Audio device                                                        | 3         | 1.43%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 3         | 1.43%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3         | 1.43%   |
| Nvidia TU104 HD Audio Controller                                           | 2         | 0.95%   |
| Nvidia High Definition Audio Controller                                    | 2         | 0.95%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 0.95%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 0.95%   |
| Nvidia GA104 High Definition Audio Controller                              | 2         | 0.95%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 0.95%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 0.95%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 0.95%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 0.95%   |
| SteelSeries ApS Arctis 7+                                                  | 1         | 0.48%   |
| Samsung Electronics USBC Headset                                           | 1         | 0.48%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.48%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.48%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 0.48%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.48%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 29        | 33.33%  |
| SK hynix            | 17        | 19.54%  |
| Micron Technology   | 16        | 18.39%  |
| Crucial             | 7         | 8.05%   |
| Kingston            | 6         | 6.9%    |
| Ramaxel Technology  | 4         | 4.6%    |
| Unknown             | 3         | 3.45%   |
| Wilk                | 1         | 1.15%   |
| Timetec             | 1         | 1.15%   |
| Nanya Technology    | 1         | 1.15%   |
| Gold Key            | 1         | 1.15%   |
| 4ea5                | 1         | 1.15%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s        | 4         | 4.35%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s         | 3         | 3.26%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 2.17%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s       | 2         | 2.17%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s        | 2         | 2.17%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s       | 2         | 2.17%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s     | 2         | 2.17%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s    | 2         | 2.17%   |
| Micron RAM MTC8C1084S1SC48BA1 16GB SODIMM DDR5 4800MT/s      | 2         | 2.17%   |
| Crucial RAM CT16G4SFRA32A.M16FR 16GB SODIMM DDR4 3200MT/s    | 2         | 2.17%   |
| Wilk RAM W-HK32S32O 32GB SODIMM DDR4 3200MT/s                | 1         | 1.09%   |
| Unknown RAM Module 4GB Chip DDR4 2133MT/s                    | 1         | 1.09%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2667MT/s               | 1         | 1.09%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                   | 1         | 1.09%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                   | 1         | 1.09%   |
| Timetec RAM SD3-1600 8GB SODIMM DDR3 1600MT/s                | 1         | 1.09%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                 | 1         | 1.09%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                 | 1         | 1.09%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 1.09%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s       | 1         | 1.09%   |
| SK hynix RAM HMT125S6TFR8C-G7 2GB SODIMM DDR3 1067MT/s       | 1         | 1.09%   |
| SK hynix RAM HMAA51S6AMR6N-UH 8GB SODIMM DDR4 2400MT/s       | 1         | 1.09%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s      | 1         | 1.09%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s       | 1         | 1.09%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s       | 1         | 1.09%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s      | 1         | 1.09%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s      | 1         | 1.09%   |
| SK hynix RAM HMA82GS6DJR8N-VK 16GB SODIMM DDR4 2667MT/s      | 1         | 1.09%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 1.09%   |
| SK hynix RAM H5ANAG6NCMR-XNC 8GB Row Of Chips DDR4 3200MT/s  | 1         | 1.09%   |
| Samsung RAM Module 32GB SODIMM DDR4 3200MT/s                 | 1         | 1.09%   |
| Samsung RAM M471B5673EH1-CH9 2048MB SODIMM DDR3 1334MT/s     | 1         | 1.09%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s        | 1         | 1.09%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 1.09%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s     | 1         | 1.09%   |
| Samsung RAM M471A5244BB0-CPB 4GB SODIMM DDR4 2400MT/s        | 1         | 1.09%   |
| Samsung RAM M471A5143DB0-CPB 4GB SODIMM DDR4 2133MT/s        | 1         | 1.09%   |
| Samsung RAM M471A2G44AM0-CWE 16GB Row Of Chips DDR4 3200MT/s | 1         | 1.09%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s       | 1         | 1.09%   |
| Samsung RAM M471A1K44BM0-CRC 8GB SODIMM DDR4 2400MT/s        | 1         | 1.09%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 49        | 71.01%  |
| DDR3   | 13        | 18.84%  |
| LPDDR4 | 2         | 2.9%    |
| LPDDR3 | 2         | 2.9%    |
| DDR5   | 2         | 2.9%    |
| DDR2   | 1         | 1.45%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 63        | 87.5%   |
| Row Of Chips | 7         | 9.72%   |
| Chip         | 1         | 1.39%   |
| Unknown      | 1         | 1.39%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 34        | 43.04%  |
| 16384 | 19        | 24.05%  |
| 4096  | 14        | 17.72%  |
| 2048  | 7         | 8.86%   |
| 32768 | 4         | 5.06%   |
| 1024  | 1         | 1.27%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 25        | 32.89%  |
| 2667  | 22        | 28.95%  |
| 1600  | 9         | 11.84%  |
| 2400  | 6         | 7.89%   |
| 2133  | 4         | 5.26%   |
| 4800  | 2         | 2.63%   |
| 1334  | 2         | 2.63%   |
| 4267  | 1         | 1.32%   |
| 3733  | 1         | 1.32%   |
| 1867  | 1         | 1.32%   |
| 1333  | 1         | 1.32%   |
| 1067  | 1         | 1.32%   |
| 667   | 1         | 1.32%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                  | Notebooks | Percent |
|------------------------|-----------|---------|
| HP DeskJet 2300 series | 1         | 100%    |

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
| Chicony Electronics                    | 36        | 27.48%  |
| IMC Networks                           | 18        | 13.74%  |
| Bison Electronics                      | 10        | 7.63%   |
| Realtek Semiconductor                  | 8         | 6.11%   |
| Microdia                               | 8         | 6.11%   |
| Luxvisions Innotech Limited            | 8         | 6.11%   |
| Cheng Uei Precision Industry (Foxlink) | 8         | 6.11%   |
| Sunplus Innovation Technology          | 6         | 4.58%   |
| Quanta                                 | 5         | 3.82%   |
| Syntek                                 | 4         | 3.05%   |
| Ricoh                                  | 3         | 2.29%   |
| Alcor Micro                            | 3         | 2.29%   |
| Suyin                                  | 2         | 1.53%   |
| Lite-On Technology                     | 2         | 1.53%   |
| Apple                                  | 2         | 1.53%   |
| Acer                                   | 2         | 1.53%   |
| Samsung Electronics                    | 1         | 0.76%   |
| Ruision                                | 1         | 0.76%   |
| Microsoft                              | 1         | 0.76%   |
| Logitech                               | 1         | 0.76%   |
| Lenovo                                 | 1         | 0.76%   |
| Google                                 | 1         | 0.76%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 11        | 8.33%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 9         | 6.82%   |
| Microdia Integrated_Webcam_HD                                   | 4         | 3.03%   |
| IMC Networks Integrated Camera                                  | 4         | 3.03%   |
| Chicony Integrated Camera (1280x720@30)                         | 4         | 3.03%   |
| Syntek Integrated Camera                                        | 3         | 2.27%   |
| Realtek Integrated_Webcam_HD                                    | 3         | 2.27%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera             | 3         | 2.27%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 3         | 2.27%   |
| Alcor Micro USB 2.0 Camera                                      | 3         | 2.27%   |
| Sunplus Integrated_Webcam_HD                                    | 2         | 1.52%   |
| Sunplus HP HD Webcam [Fixed]                                    | 2         | 1.52%   |
| Ricoh HD Webcam                                                 | 2         | 1.52%   |
| Realtek HP Truevision HD                                        | 2         | 1.52%   |
| Quanta HP TrueVision HD Camera                                  | 2         | 1.52%   |
| Microdia Laptop_Integrated_Webcam_HD                            | 2         | 1.52%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera            | 2         | 1.52%   |
| Chicony TOSHIBA Web Camera - HD                                 | 2         | 1.52%   |
| Chicony TOSHIBA Web Camera - FHD                                | 2         | 1.52%   |
| Chicony Lenovo EasyCamera                                       | 2         | 1.52%   |
| Chicony HP Truevision HD                                        | 2         | 1.52%   |
| Chicony HP HD Webcam [Fixed]                                    | 2         | 1.52%   |
| Chicony HP HD Webcam                                            | 2         | 1.52%   |
| Chicony HD WebCam                                               | 2         | 1.52%   |
| Chicony EasyCamera                                              | 2         | 1.52%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam             | 2         | 1.52%   |
| Bison Lenovo EasyCamera                                         | 2         | 1.52%   |
| Bison Integrated Camera                                         | 2         | 1.52%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                              | 2         | 1.52%   |
| Acer BisonCam,NB Pro                                            | 2         | 1.52%   |
| Syntek EasyCamera                                               | 1         | 0.76%   |
| Suyin HP TrueVision HD                                          | 1         | 0.76%   |
| Suyin 1.3M HD WebCam                                            | 1         | 0.76%   |
| Sunplus Integrated_Webcam_FHD                                   | 1         | 0.76%   |
| Sunplus Integrated Webcam                                       | 1         | 0.76%   |
| Samsung Galaxy series, misc. (MTP mode)                         | 1         | 0.76%   |
| Ruision UVC Camera                                              | 1         | 0.76%   |
| Ricoh Sony Vaio Integrated Webcam                               | 1         | 0.76%   |
| Realtek USB2.0 HD UVC WebCam                                    | 1         | 0.76%   |
| Realtek Lenovo EasyCamera                                       | 1         | 0.76%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 15        | 39.47%  |
| Validity Sensors                   | 14        | 36.84%  |
| Elan Microelectronics              | 5         | 13.16%  |
| Shenzhen Goodix Technology         | 2         | 5.26%   |
| STMicroelectronics                 | 1         | 2.63%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 2.63%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Elan ELAN:ARM-M4                                                | 5         | 13.16%  |
| Validity Sensors VFS471 Fingerprint Reader                      | 3         | 7.89%   |
| Validity Sensors Synaptics WBDI                                 | 3         | 7.89%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 3         | 7.89%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 3         | 7.89%   |
| Validity Sensors VFS495 Fingerprint Reader                      | 2         | 5.26%   |
| Validity Sensors VFS491                                         | 2         | 5.26%   |
| Synaptics UWP WBDI Device                                       | 2         | 5.26%   |
| Synaptics UWP WBDI                                              | 2         | 5.26%   |
| Validity Sensors VFS5011 Fingerprint Reader                     | 1         | 2.63%   |
| Validity Sensors VFS Fingerprint sensor                         | 1         | 2.63%   |
| Validity Sensors VFS 5011 fingerprint sensor                    | 1         | 2.63%   |
| Validity Sensors Fingerprint scanner                            | 1         | 2.63%   |
| Synaptics WBDI Fingerprint Reader USB 086                       | 1         | 2.63%   |
| Synaptics TouchPad                                              | 1         | 2.63%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint       | 1         | 2.63%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                | 1         | 2.63%   |
| Synaptics Fingerprint reader [HP G6]                            | 1         | 2.63%   |
| STMicroelectronics Fingerprint Reader                           | 1         | 2.63%   |
| Shenzhen Goodix  Fingerprint Device                             | 1         | 2.63%   |
| Shenzhen Goodix Fingerprint Reader                              | 1         | 2.63%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 1         | 2.63%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 3         | 37.5%   |
| Alcor Micro | 3         | 37.5%   |
| Upek        | 1         | 12.5%   |
| Aktiv       | 1         | 12.5%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
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


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 71        | 49.31%  |
| 1     | 54        | 37.5%   |
| 2     | 16        | 11.11%  |
| 3     | 3         | 2.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 38        | 41.76%  |
| Graphics card            | 16        | 17.58%  |
| Net/wireless             | 9         | 9.89%   |
| Chipcard                 | 7         | 7.69%   |
| Camera                   | 7         | 7.69%   |
| Multimedia controller    | 4         | 4.4%    |
| Bluetooth                | 4         | 4.4%    |
| Wireless                 | 2         | 2.2%    |
| Sound                    | 2         | 2.2%    |
| Communication controller | 2         | 2.2%    |

