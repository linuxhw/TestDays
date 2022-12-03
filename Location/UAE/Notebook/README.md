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

Total: 115

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04       | 23        | 26.14%  |
| Ubuntu 18.04       | 9         | 10.23%  |
| Arch               | 5         | 5.68%   |
| Zorin 15           | 3         | 3.41%   |
| Ubuntu 22.04       | 3         | 3.41%   |
| Ubuntu 20.10       | 3         | 3.41%   |
| Ubuntu 19.10       | 3         | 3.41%   |
| Fedora 36          | 3         | 3.41%   |
| Ubuntu 21.10       | 2         | 2.27%   |
| Ubuntu 16.04       | 2         | 2.27%   |
| KDE neon 20.04     | 2         | 2.27%   |
| Debian 11          | 2         | 2.27%   |
| BlackPanther 18.1  | 2         | 2.27%   |
| ArcoLinux Rolling  | 2         | 2.27%   |
| Xubuntu 20.04      | 1         | 1.14%   |
| Ubuntu Unity 18.04 | 1         | 1.14%   |
| Ubuntu 22.10       | 1         | 1.14%   |
| Ubuntu 19.04       | 1         | 1.14%   |
| ROSA 12.2          | 1         | 1.14%   |
| Pop!_OS 22.04      | 1         | 1.14%   |
| Pop!_OS 21.10      | 1         | 1.14%   |
| Pop!_OS 20.10      | 1         | 1.14%   |
| Pop!_OS 20.04      | 1         | 1.14%   |
| OpenMandriva 4.90  | 1         | 1.14%   |
| OpenMandriva 4.3   | 1         | 1.14%   |
| OpenMandriva 4.2   | 1         | 1.14%   |
| Manjaro 21.2.1     | 1         | 1.14%   |
| Manjaro 18.1.4     | 1         | 1.14%   |
| Manjaro            | 1         | 1.14%   |
| Linux Mint 20.3    | 1         | 1.14%   |
| Linux Mint 20.1    | 1         | 1.14%   |
| Linux Mint 19.2    | 1         | 1.14%   |
| Kubuntu 22.04      | 1         | 1.14%   |
| GNOME OS Nightly   | 1         | 1.14%   |
| Feren OS 20.04     | 1         | 1.14%   |
| Fedora 35          | 1         | 1.14%   |
| Endless 4.0.4      | 1         | 1.14%   |
| Elementary 5.1.7   | 1         | 1.14%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 45        | 52.33%  |
| Arch         | 5         | 5.81%   |
| Pop!_OS      | 4         | 4.65%   |
| Fedora       | 4         | 4.65%   |
| Zorin        | 3         | 3.49%   |
| OpenMandriva | 3         | 3.49%   |
| Manjaro      | 3         | 3.49%   |
| Linux Mint   | 3         | 3.49%   |
| KDE neon     | 2         | 2.33%   |
| Debian       | 2         | 2.33%   |
| BlackPanther | 2         | 2.33%   |
| ArcoLinux    | 2         | 2.33%   |
| Xubuntu      | 1         | 1.16%   |
| Ubuntu Unity | 1         | 1.16%   |
| ROSA         | 1         | 1.16%   |
| Kubuntu      | 1         | 1.16%   |
| GNOME OS     | 1         | 1.16%   |
| Feren OS     | 1         | 1.16%   |
| Endless      | 1         | 1.16%   |
| Elementary   | 1         | 1.16%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 5.4.0-42-generic        | 5         | 5.43%   |
| 5.4.0-58-generic        | 4         | 4.35%   |
| 5.4.0-26-generic        | 3         | 3.26%   |
| 5.4.0-33-generic        | 2         | 2.17%   |
| 5.4.0-29-generic        | 2         | 2.17%   |
| 5.3.0-40-generic        | 2         | 2.17%   |
| 5.3.0-29-generic        | 2         | 2.17%   |
| 4.15.0-50-generic       | 2         | 2.17%   |
| 6.0.6-76060006-generic  | 1         | 1.09%   |
| 5.9.3-arch1-1           | 1         | 1.09%   |
| 5.8.5-arch1-1           | 1         | 1.09%   |
| 5.8.0-7642-generic      | 1         | 1.09%   |
| 5.8.0-7630-generic      | 1         | 1.09%   |
| 5.8.0-54-generic        | 1         | 1.09%   |
| 5.8.0-53-generic        | 1         | 1.09%   |
| 5.8.0-50-generic        | 1         | 1.09%   |
| 5.8.0-41-generic        | 1         | 1.09%   |
| 5.8.0-40-generic        | 1         | 1.09%   |
| 5.7.6-arch1-1           | 1         | 1.09%   |
| 5.7.14                  | 1         | 1.09%   |
| 5.6.16-1-MANJARO        | 1         | 1.09%   |
| 5.6.14-desktop-2bP      | 1         | 1.09%   |
| 5.4.68-1-lts            | 1         | 1.09%   |
| 5.4.2-1-MANJARO         | 1         | 1.09%   |
| 5.4.0-81-generic        | 1         | 1.09%   |
| 5.4.0-73-generic        | 1         | 1.09%   |
| 5.4.0-72-generic        | 1         | 1.09%   |
| 5.4.0-65-generic        | 1         | 1.09%   |
| 5.4.0-60-generic        | 1         | 1.09%   |
| 5.4.0-54-generic        | 1         | 1.09%   |
| 5.4.0-48-generic        | 1         | 1.09%   |
| 5.4.0-45-generic        | 1         | 1.09%   |
| 5.4.0-39-generic        | 1         | 1.09%   |
| 5.4.0-37-generic        | 1         | 1.09%   |
| 5.4.0-18-generic        | 1         | 1.09%   |
| 5.4.0-100-generic       | 1         | 1.09%   |
| 5.3.0-46-generic        | 1         | 1.09%   |
| 5.19.8-200.fc36.x86_64  | 1         | 1.09%   |
| 5.19.13-200.fc36.x86_64 | 1         | 1.09%   |
| 5.19.0-21-generic       | 1         | 1.09%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 25        | 28.09%  |
| 4.15.0  | 9         | 10.11%  |
| 5.8.0   | 7         | 7.87%   |
| 5.3.0   | 5         | 5.62%   |
| 5.11.0  | 5         | 5.62%   |
| 5.15.0  | 4         | 4.49%   |
| 5.13.0  | 2         | 2.25%   |
| 5.10.0  | 2         | 2.25%   |
| 5.0.0   | 2         | 2.25%   |
| 6.0.6   | 1         | 1.12%   |
| 5.9.3   | 1         | 1.12%   |
| 5.8.5   | 1         | 1.12%   |
| 5.7.6   | 1         | 1.12%   |
| 5.7.14  | 1         | 1.12%   |
| 5.6.16  | 1         | 1.12%   |
| 5.6.14  | 1         | 1.12%   |
| 5.4.68  | 1         | 1.12%   |
| 5.4.2   | 1         | 1.12%   |
| 5.19.8  | 1         | 1.12%   |
| 5.19.13 | 1         | 1.12%   |
| 5.19.0  | 1         | 1.12%   |
| 5.18.12 | 1         | 1.12%   |
| 5.18.11 | 1         | 1.12%   |
| 5.16.7  | 1         | 1.12%   |
| 5.16.5  | 1         | 1.12%   |
| 5.16.18 | 1         | 1.12%   |
| 5.16.16 | 1         | 1.12%   |
| 5.16.12 | 1         | 1.12%   |
| 5.15.5  | 1         | 1.12%   |
| 5.15.12 | 1         | 1.12%   |
| 5.14.0  | 1         | 1.12%   |
| 5.10.74 | 1         | 1.12%   |
| 5.10.14 | 1         | 1.12%   |
| 4.4.0   | 1         | 1.12%   |
| 4.19.92 | 1         | 1.12%   |
| 4.18.16 | 1         | 1.12%   |
| 4.18.0  | 1         | 1.12%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 27        | 30.68%  |
| 4.15    | 9         | 10.23%  |
| 5.8     | 8         | 9.09%   |
| 5.15    | 6         | 6.82%   |
| 5.3     | 5         | 5.68%   |
| 5.11    | 5         | 5.68%   |
| 5.16    | 4         | 4.55%   |
| 5.10    | 4         | 4.55%   |
| 5.19    | 3         | 3.41%   |
| 5.7     | 2         | 2.27%   |
| 5.6     | 2         | 2.27%   |
| 5.18    | 2         | 2.27%   |
| 5.13    | 2         | 2.27%   |
| 5.0     | 2         | 2.27%   |
| 4.18    | 2         | 2.27%   |
| 6.0     | 1         | 1.14%   |
| 5.9     | 1         | 1.14%   |
| 5.14    | 1         | 1.14%   |
| 4.4     | 1         | 1.14%   |
| 4.19    | 1         | 1.14%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 85        | 98.84%  |
| i686   | 1         | 1.16%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 55        | 61.8%   |
| Unknown    | 12        | 13.48%  |
| KDE5       | 8         | 8.99%   |
| KDE        | 4         | 4.49%   |
| X-Cinnamon | 3         | 3.37%   |
| XFCE       | 2         | 2.25%   |
| Unity      | 1         | 1.12%   |
| Pantheon   | 1         | 1.12%   |
| MATE       | 1         | 1.12%   |
| DWM        | 1         | 1.12%   |
| awesome    | 1         | 1.12%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 64        | 73.56%  |
| Wayland | 15        | 17.24%  |
| Unknown | 8         | 9.2%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 51        | 59.3%   |
| GDM     | 17        | 19.77%  |
| SDDM    | 8         | 9.3%    |
| GDM3    | 6         | 6.98%   |
| TDM     | 2         | 2.33%   |
| LightDM | 2         | 2.33%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 66        | 75.86%  |
| Unknown | 11        | 12.64%  |
| en_GB   | 3         | 3.45%   |
| C       | 2         | 2.3%    |
| ru_RU   | 1         | 1.15%   |
| hu_HU   | 1         | 1.15%   |
| en_IN   | 1         | 1.15%   |
| en_AU   | 1         | 1.15%   |
| de_DE   | 1         | 1.15%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 48        | 55.17%  |
| BIOS | 39        | 44.83%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 76        | 88.37%  |
| Overlay | 5         | 5.81%   |
| Btrfs   | 5         | 5.81%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 52        | 60.47%  |
| GPT     | 30        | 34.88%  |
| MBR     | 4         | 4.65%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 78        | 90.7%   |
| Yes       | 8         | 9.3%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 47        | 54.65%  |
| Yes       | 39        | 45.35%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Lenovo                      | 26        | 30.23%  |
| Hewlett-Packard             | 24        | 27.91%  |
| Dell                        | 12        | 13.95%  |
| Toshiba                     | 5         | 5.81%   |
| ASUSTek Computer            | 5         | 5.81%   |
| Sony                        | 2         | 2.33%   |
| MSI                         | 2         | 2.33%   |
| Google                      | 2         | 2.33%   |
| Acer                        | 2         | 2.33%   |
| YJKC                        | 1         | 1.16%   |
| win element                 | 1         | 1.16%   |
| Notebook                    | 1         | 1.16%   |
| LG Electronics              | 1         | 1.16%   |
| I-Life Digital Technologies | 1         | 1.16%   |
| Apple                       | 1         | 1.16%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| HP Pavilion Notebook                        | 2         | 2.33%   |
| HP ENVY Laptop 13-aq0xxx                    | 2         | 2.33%   |
| YJKC vBOOK Plus                             | 1         | 1.16%   |
| win element MoreFine S500+                  | 1         | 1.16%   |
| Toshiba TECRA X40-D                         | 1         | 1.16%   |
| Toshiba TECRA A50-C                         | 1         | 1.16%   |
| Toshiba Satellite C850-A966                 | 1         | 1.16%   |
| Toshiba Satellite C660                      | 1         | 1.16%   |
| Toshiba Satellite A300                      | 1         | 1.16%   |
| Sony VGN-NS10J_S                            | 1         | 1.16%   |
| Sony SVE14A25CAB                            | 1         | 1.16%   |
| Notebook P95_96_97Ex,Rx                     | 1         | 1.16%   |
| MSI PS63 Modern 8RD                         | 1         | 1.16%   |
| MSI Modern 14 B5M                           | 1         | 1.16%   |
| LG C500-G.AEF5BE1                           | 1         | 1.16%   |
| Lenovo Yoga S730-13IWL 81J0                 | 1         | 1.16%   |
| Lenovo Yoga 2 Pro 20266                     | 1         | 1.16%   |
| Lenovo ThinkPad X240 20AMS6GB00             | 1         | 1.16%   |
| Lenovo ThinkPad X230 2325DV8                | 1         | 1.16%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TK001HUS | 1         | 1.16%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XW00A9US  | 1         | 1.16%   |
| Lenovo ThinkPad T61 76653JG                 | 1         | 1.16%   |
| Lenovo ThinkPad T480s 20L8S3FV00            | 1         | 1.16%   |
| Lenovo ThinkPad T480s 20L7001PAD            | 1         | 1.16%   |
| Lenovo ThinkPad T470 W10DG 20JMS0Q300       | 1         | 1.16%   |
| Lenovo ThinkPad T460 20FMS1A200             | 1         | 1.16%   |
| Lenovo ThinkPad P1 Gen 5 21DC000DCK         | 1         | 1.16%   |
| Lenovo ThinkPad P1 Gen 3 20TJS4RX00         | 1         | 1.16%   |
| Lenovo ThinkPad L480 20LS0012AD             | 1         | 1.16%   |
| Lenovo ThinkPad E14 Gen 2 20TA0018AD        | 1         | 1.16%   |
| Lenovo Legion Y7000P 81LD                   | 1         | 1.16%   |
| Lenovo IdeaPadFlex 14 20308                 | 1         | 1.16%   |
| Lenovo IdeaPad Gaming 3 15IMH05 81Y4        | 1         | 1.16%   |
| Lenovo IdeaPad 700-15ISK 80RU               | 1         | 1.16%   |
| Lenovo IdeaPad 320-15IKB 80XL               | 1         | 1.16%   |
| Lenovo IdeaPad 3 14IML05 81WA               | 1         | 1.16%   |
| Lenovo IdeaPad 3 14ADA05 81W0               | 1         | 1.16%   |
| Lenovo IdeaPad 130-15IKB 81H7               | 1         | 1.16%   |
| Lenovo IdeaPad 110-15ISK 80UD               | 1         | 1.16%   |
| Lenovo G500 20236                           | 1         | 1.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 13        | 15.12%  |
| Lenovo IdeaPad       | 7         | 8.14%   |
| HP Pavilion          | 7         | 8.14%   |
| HP EliteBook         | 6         | 6.98%   |
| Dell Latitude        | 5         | 5.81%   |
| Toshiba Satellite    | 3         | 3.49%   |
| HP ProBook           | 3         | 3.49%   |
| HP Laptop            | 3         | 3.49%   |
| Dell Inspiron        | 3         | 3.49%   |
| Toshiba TECRA        | 2         | 2.33%   |
| Lenovo Yoga          | 2         | 2.33%   |
| HP ENVY              | 2         | 2.33%   |
| ASUS VivoBook        | 2         | 2.33%   |
| YJKC vBOOK           | 1         | 1.16%   |
| win element MoreFine | 1         | 1.16%   |
| Sony VGN-NS10J       | 1         | 1.16%   |
| Sony SVE14A25CAB     | 1         | 1.16%   |
| Notebook P95         | 1         | 1.16%   |
| MSI PS63             | 1         | 1.16%   |
| MSI Modern           | 1         | 1.16%   |
| LG C500-G.AEF5BE1    | 1         | 1.16%   |
| Lenovo Legion        | 1         | 1.16%   |
| Lenovo IdeaPadFlex   | 1         | 1.16%   |
| Lenovo G500          | 1         | 1.16%   |
| Lenovo 81FV          | 1         | 1.16%   |
| I-Life Digital ZED   | 1         | 1.16%   |
| HP Presario          | 1         | 1.16%   |
| HP Notebook          | 1         | 1.16%   |
| HP 250               | 1         | 1.16%   |
| Google Terra         | 1         | 1.16%   |
| Google Akemi         | 1         | 1.16%   |
| Dell XPS             | 1         | 1.16%   |
| Dell Vostro          | 1         | 1.16%   |
| Dell Precision       | 1         | 1.16%   |
| Dell G5              | 1         | 1.16%   |
| ASUS Strix           | 1         | 1.16%   |
| ASUS ROG             | 1         | 1.16%   |
| ASUS FX503VD         | 1         | 1.16%   |
| Apple MacBook9       | 1         | 1.16%   |
| Acer ChiefRiver      | 1         | 1.16%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 11        | 12.79%  |
| 2018 | 11        | 12.79%  |
| 2013 | 11        | 12.79%  |
| 2020 | 9         | 10.47%  |
| 2021 | 8         | 9.3%    |
| 2012 | 7         | 8.14%   |
| 2017 | 6         | 6.98%   |
| 2010 | 5         | 5.81%   |
| 2016 | 4         | 4.65%   |
| 2015 | 3         | 3.49%   |
| 2011 | 3         | 3.49%   |
| 2014 | 2         | 2.33%   |
| 2008 | 2         | 2.33%   |
| 2007 | 2         | 2.33%   |
| 2022 | 1         | 1.16%   |
| 2009 | 1         | 1.16%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 86        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 74        | 86.05%  |
| Enabled  | 12        | 13.95%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 84        | 97.67%  |
| Yes  | 2         | 2.33%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 20        | 23.26%  |
| 16.01-24.0  | 18        | 20.93%  |
| 3.01-4.0    | 17        | 19.77%  |
| 8.01-16.0   | 14        | 16.28%  |
| 32.01-64.0  | 9         | 10.47%  |
| 2.01-3.0    | 2         | 2.33%   |
| 64.01-256.0 | 2         | 2.33%   |
| 1.01-2.0    | 2         | 2.33%   |
| 24.01-32.0  | 1         | 1.16%   |
| 0.51-1.0    | 1         | 1.16%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 32        | 35.16%  |
| 2.01-3.0  | 18        | 19.78%  |
| 3.01-4.0  | 17        | 18.68%  |
| 4.01-8.0  | 16        | 17.58%  |
| 0.51-1.0  | 4         | 4.4%    |
| 8.01-16.0 | 3         | 3.3%    |
| 0.01-0.5  | 1         | 1.1%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 67        | 77.91%  |
| 2      | 16        | 18.6%   |
| 0      | 2         | 2.33%   |
| 3      | 1         | 1.16%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 58        | 67.44%  |
| Yes       | 28        | 32.56%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 63        | 73.26%  |
| No        | 23        | 26.74%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 84        | 97.67%  |
| No        | 2         | 2.33%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 68        | 79.07%  |
| No        | 18        | 20.93%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| UAE     | 86        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Dubai            | 39        | 44.32%  |
| Abu Dhabi        | 25        | 28.41%  |
| Sharjah          | 15        | 17.05%  |
| Al Ain City      | 4         | 4.55%   |
| Ajman            | 3         | 3.41%   |
| Al Halah         | 1         | 1.14%   |
| Al Fujairah City | 1         | 1.14%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Notebooks | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Samsung Electronics   | 16        | 16     | 16.49%  |
| WDC                   | 15        | 16     | 15.46%  |
| Toshiba               | 11        | 11     | 11.34%  |
| Seagate               | 10        | 12     | 10.31%  |
| Intel                 | 6         | 7      | 6.19%   |
| HGST                  | 6         | 7      | 6.19%   |
| Unknown               | 5         | 9      | 5.15%   |
| SK hynix              | 4         | 5      | 4.12%   |
| Micron Technology     | 4         | 4      | 4.12%   |
| Kingston              | 3         | 3      | 3.09%   |
| Hitachi               | 3         | 3      | 3.09%   |
| SanDisk               | 2         | 2      | 2.06%   |
| Crucial               | 2         | 2      | 2.06%   |
| Apple                 | 2         | 3      | 2.06%   |
| Realtek Semiconductor | 1         | 1      | 1.03%   |
| Phison                | 1         | 1      | 1.03%   |
| Patriot               | 1         | 1      | 1.03%   |
| Lite-On               | 1         | 1      | 1.03%   |
| KingSpec              | 1         | 2      | 1.03%   |
| Fujitsu               | 1         | 1      | 1.03%   |
| External              | 1         | 1      | 1.03%   |
| China                 | 1         | 1      | 1.03%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel NVMe SSD Drive 512GB              | 3         | 2.94%   |
| HGST HTS725050A7E630 500GB              | 3         | 2.94%   |
| WDC WD10SPZX-08Z10 1TB                  | 2         | 1.96%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB      | 2         | 1.96%   |
| Unknown MMC Card  16GB                  | 2         | 1.96%   |
| Toshiba MQ01ABD075 752GB                | 2         | 1.96%   |
| Seagate ST500LT012-1DG142 500GB         | 2         | 1.96%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB  | 2         | 1.96%   |
| HGST HTS721010A9E630 1TB                | 2         | 1.96%   |
| WDC WDS500G2B0A-00SM50 500GB SSD        | 1         | 0.98%   |
| WDC WDS120G1G0A-00SS50 120GB SSD        | 1         | 0.98%   |
| WDC WDS100T3X0C-00SJG0 1TB              | 1         | 0.98%   |
| WDC WD5000LPVX-60V0TT0 500GB            | 1         | 0.98%   |
| WDC WD5000LPCX-22VHAT1 500GB            | 1         | 0.98%   |
| WDC WD2500BEVS-26UST0 250GB             | 1         | 0.98%   |
| WDC WD1200BEVS-08UST0 120GB             | 1         | 0.98%   |
| WDC WD10SPZX-24Z10T0 1TB                | 1         | 0.98%   |
| WDC WD10SPZX-24Z10 1TB                  | 1         | 0.98%   |
| WDC WD10JPVX-60JC3T1 1TB                | 1         | 0.98%   |
| WDC WD10JPCX-24UE4T0 1TB                | 1         | 0.98%   |
| Unknown SR64G  64GB                     | 1         | 0.98%   |
| Unknown SM32G  32GB                     | 1         | 0.98%   |
| Unknown SL16G  16GB                     | 1         | 0.98%   |
| Unknown NCard  32GB                     | 1         | 0.98%   |
| Unknown MMC64G  64GB                    | 1         | 0.98%   |
| Unknown MMC Card  64GB                  | 1         | 0.98%   |
| Unknown MMC Card  32GB                  | 1         | 0.98%   |
| Toshiba NVMe SSD Drive 512GB            | 1         | 0.98%   |
| Toshiba MQ02ABF100 1TB                  | 1         | 0.98%   |
| Toshiba MQ01ABF050 500GB                | 1         | 0.98%   |
| Toshiba MQ01ABD100M 1TB                 | 1         | 0.98%   |
| Toshiba MQ01ABD050 500GB                | 1         | 0.98%   |
| Toshiba MQ01ABD032 320GB                | 1         | 0.98%   |
| Toshiba MK5075GSX 500GB                 | 1         | 0.98%   |
| Toshiba MK2552GSX 250GB                 | 1         | 0.98%   |
| Toshiba KBG30ZMV512G 512GB              | 1         | 0.98%   |
| SK hynix SKHynix_HFM256GD3HX015N 256GB  | 1         | 0.98%   |
| SK hynix SC311 SATA 256GB SSD           | 1         | 0.98%   |
| SK hynix PC401 HFS512GD9TNG-62A0A 512GB | 1         | 0.98%   |
| SK hynix NVMe SSD Drive 512GB           | 1         | 0.98%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 10        | 11     | 25%     |
| Seagate | 10        | 12     | 25%     |
| Toshiba | 9         | 9      | 22.5%   |
| HGST    | 6         | 7      | 15%     |
| Hitachi | 3         | 3      | 7.5%    |
| Fujitsu | 1         | 1      | 2.5%    |
| Apple   | 1         | 1      | 2.5%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 4      | 30.77%  |
| WDC                 | 2         | 2      | 15.38%  |
| SK hynix            | 1         | 1      | 7.69%   |
| SanDisk             | 1         | 1      | 7.69%   |
| Patriot             | 1         | 1      | 7.69%   |
| Kingston            | 1         | 1      | 7.69%   |
| KingSpec            | 1         | 2      | 7.69%   |
| Crucial             | 1         | 1      | 7.69%   |
| China               | 1         | 1      | 7.69%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 40        | 44     | 42.55%  |
| NVMe | 37        | 42     | 39.36%  |
| SSD  | 12        | 14     | 12.77%  |
| MMC  | 5         | 9      | 5.32%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 50        | 58     | 54.35%  |
| NVMe | 36        | 41     | 39.13%  |
| MMC  | 5         | 9      | 5.43%   |
| SAS  | 1         | 1      | 1.09%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 31        | 35     | 60.78%  |
| 0.51-1.0   | 19        | 22     | 37.25%  |
| 1.01-2.0   | 1         | 1      | 1.96%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 26        | 30.23%  |
| 101-250    | 21        | 24.42%  |
| 21-50      | 10        | 11.63%  |
| 501-1000   | 8         | 9.3%    |
| 51-100     | 7         | 8.14%   |
| 1-20       | 5         | 5.81%   |
| 1001-2000  | 4         | 4.65%   |
| Unknown    | 4         | 4.65%   |
| 2001-3000  | 1         | 1.16%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 44        | 48.89%  |
| 21-50     | 21        | 23.33%  |
| 51-100    | 7         | 7.78%   |
| 101-250   | 6         | 6.67%   |
| 251-500   | 4         | 4.44%   |
| Unknown   | 4         | 4.44%   |
| 501-1000  | 3         | 3.33%   |
| 1001-2000 | 1         | 1.11%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                    | Notebooks | Drives | Percent |
|--------------------------|-----------|--------|---------|
| WDC WD10JPVX-60JC3T1 1TB | 1         | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

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
| HDD  | 1         | 1      | 100%    |

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
| Detected | 54        | 71     | 63.53%  |
| Works    | 30        | 37     | 35.29%  |
| Malfunc  | 1         | 1      | 1.18%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 64        | 65.98%  |
| Samsung Electronics          | 12        | 12.37%  |
| SanDisk                      | 4         | 4.12%   |
| Micron Technology            | 4         | 4.12%   |
| SK hynix                     | 3         | 3.09%   |
| Toshiba America Info Systems | 2         | 2.06%   |
| Kingston Technology Company  | 2         | 2.06%   |
| Realtek Semiconductor        | 1         | 1.03%   |
| Phison Electronics           | 1         | 1.03%   |
| Micron/Crucial Technology    | 1         | 1.03%   |
| Lite-On Technology           | 1         | 1.03%   |
| Apple                        | 1         | 1.03%   |
| AMD                          | 1         | 1.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 11        | 10.58%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 9         | 8.65%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                            | 7         | 6.73%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 7         | 6.73%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 6         | 5.77%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 6         | 5.77%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 5         | 4.81%   |
| Micron Non-Volatile memory controller                                        | 4         | 3.85%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 4         | 3.85%   |
| Intel SSD 660P Series                                                        | 4         | 3.85%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                   | 3         | 2.88%   |
| Samsung NVMe SSD Controller 980                                              | 3         | 2.88%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                               | 2         | 1.92%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                | 2         | 1.92%   |
| Intel Volume Management Device NVMe RAID Controller                          | 2         | 1.92%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                      | 2         | 1.92%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                        | 2         | 1.92%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                             | 2         | 1.92%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                         | 1         | 0.96%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                         | 1         | 0.96%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                  | 1         | 0.96%   |
| SanDisk Non-Volatile memory controller                                       | 1         | 0.96%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                               | 1         | 0.96%   |
| Realtek Realtek Non-Volatile memory controller                               | 1         | 0.96%   |
| Phison E12 NVMe Controller                                                   | 1         | 0.96%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                         | 1         | 0.96%   |
| Lite-On Non-Volatile memory controller                                       | 1         | 0.96%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                        | 1         | 0.96%   |
| Kingston Company A2000 NVMe SSD                                              | 1         | 0.96%   |
| Intel Comet Lake SATA AHCI Controller                                        | 1         | 0.96%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                            | 1         | 0.96%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 1         | 0.96%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                 | 1         | 0.96%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                | 1         | 0.96%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]               | 1         | 0.96%   |
| Intel 82801G (ICH7 Family) IDE Controller                                    | 1         | 0.96%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller               | 1         | 0.96%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller               | 1         | 0.96%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                         | 1         | 0.96%   |
| Apple S3X NVMe Controller                                                    | 1         | 0.96%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 49        | 48.51%  |
| NVMe | 36        | 35.64%  |
| RAID | 13        | 12.87%  |
| IDE  | 3         | 2.97%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 80        | 93.02%  |
| AMD    | 6         | 6.98%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-4200U CPU @ 1.60GHz       | 5         | 5.81%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 4         | 4.65%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 3         | 3.49%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 3         | 3.49%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 3         | 3.49%   |
| Intel Core i9-10885H CPU @ 2.40GHz      | 2         | 2.33%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 2         | 2.33%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 2         | 2.33%   |
| Intel Core i7-5500U CPU @ 2.40GHz       | 2         | 2.33%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 2         | 2.33%   |
| Intel Core i5-2410M CPU @ 2.30GHz       | 2         | 2.33%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 2         | 2.33%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 2         | 2.33%   |
| AMD Ryzen 5 5500U with Radeon Graphics  | 2         | 2.33%   |
| Intel Core m5-6Y54 CPU @ 1.10GHz        | 1         | 1.16%   |
| Intel Core i9-9980HK CPU @ 2.40GHz      | 1         | 1.16%   |
| Intel Core i7-9850H CPU @ 2.60GHz       | 1         | 1.16%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 1         | 1.16%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 1         | 1.16%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 1         | 1.16%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 1         | 1.16%   |
| Intel Core i7-4600M CPU @ 2.90GHz       | 1         | 1.16%   |
| Intel Core i7-3632QM CPU @ 2.20GHz      | 1         | 1.16%   |
| Intel Core i7-2640M CPU @ 2.80GHz       | 1         | 1.16%   |
| Intel Core i7-2630QM CPU @ 2.00GHz      | 1         | 1.16%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 1         | 1.16%   |
| Intel Core i5-8300H CPU @ 2.30GHz       | 1         | 1.16%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 1         | 1.16%   |
| Intel Core i5-7300U CPU @ 2.60GHz       | 1         | 1.16%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 1         | 1.16%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 1         | 1.16%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 1         | 1.16%   |
| Intel Core i5-4300U CPU @ 1.90GHz       | 1         | 1.16%   |
| Intel Core i5-3360M CPU @ 2.80GHz       | 1         | 1.16%   |
| Intel Core i5-3337U CPU @ 1.80GHz       | 1         | 1.16%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 1         | 1.16%   |
| Intel Core i5-3317U CPU @ 1.70GHz       | 1         | 1.16%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 1         | 1.16%   |
| Intel Core i5-2450M CPU @ 2.50GHz       | 1         | 1.16%   |
| Intel Core i5 CPU M 560 @ 2.67GHz       | 1         | 1.16%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 31        | 36.05%  |
| Intel Core i7    | 26        | 30.23%  |
| Intel Core i3    | 6         | 6.98%   |
| Other            | 5         | 5.81%   |
| Intel Core i9    | 3         | 3.49%   |
| Intel Core 2 Duo | 3         | 3.49%   |
| Intel Celeron    | 3         | 3.49%   |
| AMD Ryzen 5      | 3         | 3.49%   |
| Intel Core m5    | 1         | 1.16%   |
| Intel Celeron M  | 1         | 1.16%   |
| Intel Atom       | 1         | 1.16%   |
| AMD Ryzen 9      | 1         | 1.16%   |
| AMD Ryzen 7 PRO  | 1         | 1.16%   |
| AMD A6           | 1         | 1.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 44        | 51.16%  |
| 4      | 25        | 29.07%  |
| 6      | 8         | 9.3%    |
| 8      | 5         | 5.81%   |
| 14     | 2         | 2.33%   |
| 1      | 2         | 2.33%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 86        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 77        | 89.53%  |
| 1      | 9         | 10.47%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 85        | 98.84%  |
| 32-bit         | 1         | 1.16%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 13        | 15.12%  |
| 0x306a9    | 6         | 6.98%   |
| 0x206a7    | 6         | 6.98%   |
| 0x906ea    | 5         | 5.81%   |
| 0x406e3    | 5         | 5.81%   |
| 0x40651    | 5         | 5.81%   |
| 0x806ec    | 4         | 4.65%   |
| 0x806ea    | 4         | 4.65%   |
| 0x806e9    | 4         | 4.65%   |
| 0xa0652    | 3         | 3.49%   |
| 0x806c1    | 3         | 3.49%   |
| 0x20655    | 3         | 3.49%   |
| 0x906ed    | 2         | 2.33%   |
| 0x906e9    | 2         | 2.33%   |
| 0x806eb    | 2         | 2.33%   |
| 0x6fd      | 2         | 2.33%   |
| 0x306d4    | 2         | 2.33%   |
| 0x906a3    | 1         | 1.16%   |
| 0x706a1    | 1         | 1.16%   |
| 0x6fb      | 1         | 1.16%   |
| 0x6e8      | 1         | 1.16%   |
| 0x506e3    | 1         | 1.16%   |
| 0x406c4    | 1         | 1.16%   |
| 0x406c3    | 1         | 1.16%   |
| 0x306c3    | 1         | 1.16%   |
| 0x20652    | 1         | 1.16%   |
| 0x0a50000c | 1         | 1.16%   |
| 0x08608103 | 1         | 1.16%   |
| 0x08608102 | 1         | 1.16%   |
| 0x08600106 | 1         | 1.16%   |
| 0x08108109 | 1         | 1.16%   |
| 0x06001119 | 1         | 1.16%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 28        | 32.56%  |
| Haswell          | 9         | 10.47%  |
| SandyBridge      | 7         | 8.14%   |
| IvyBridge        | 7         | 8.14%   |
| Skylake          | 6         | 6.98%   |
| Westmere         | 4         | 4.65%   |
| Broadwell        | 4         | 4.65%   |
| TigerLake        | 3         | 3.49%   |
| Core             | 3         | 3.49%   |
| CometLake        | 3         | 3.49%   |
| Unknown          | 3         | 3.49%   |
| Silvermont       | 2         | 2.33%   |
| Zen+             | 1         | 1.16%   |
| Zen 3            | 1         | 1.16%   |
| Zen 2            | 1         | 1.16%   |
| Piledriver       | 1         | 1.16%   |
| P6               | 1         | 1.16%   |
| Goldmont plus    | 1         | 1.16%   |
| Alderlake Hybrid | 1         | 1.16%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 75        | 60%     |
| Nvidia | 34        | 27.2%   |
| AMD    | 16        | 12.8%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 8         | 6.35%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 7         | 5.56%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 7         | 5.56%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 4.76%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 6         | 4.76%   |
| Intel UHD Graphics 620                                                                   | 5         | 3.97%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 3.17%   |
| Intel HD Graphics 620                                                                    | 4         | 3.17%   |
| Intel HD Graphics 5500                                                                   | 4         | 3.17%   |
| Nvidia GM108M [GeForce MX130]                                                            | 3         | 2.38%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 2.38%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 2.38%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 2.38%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 2.38%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 3         | 2.38%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 1.59%   |
| Nvidia GP108BM [GeForce MX250]                                                           | 2         | 1.59%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 1.59%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 1.59%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 2         | 1.59%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 2         | 1.59%   |
| Intel HD Graphics 630                                                                    | 2         | 1.59%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.59%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 2         | 1.59%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 2         | 1.59%   |
| AMD Lucienne                                                                             | 2         | 1.59%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.79%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 1         | 0.79%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 1         | 0.79%   |
| Nvidia TU104M [GeForce RTX 2080 Mobile]                                                  | 1         | 0.79%   |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 0.79%   |
| Nvidia GT218M [GeForce 315M]                                                             | 1         | 0.79%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Max-Q]                                                | 1         | 0.79%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 0.79%   |
| Nvidia GM108M [GeForce 940M]                                                             | 1         | 0.79%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.79%   |
| Nvidia GM108M [GeForce 930M]                                                             | 1         | 0.79%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 1         | 0.79%   |
| Nvidia GM108M [GeForce 830M]                                                             | 1         | 0.79%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 0.79%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 36        | 41.86%  |
| Intel + Nvidia | 30        | 34.88%  |
| Intel + AMD    | 9         | 10.47%  |
| 1 x AMD        | 7         | 8.14%   |
| 1 x Nvidia     | 4         | 4.65%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 72        | 83.72%  |
| Proprietary | 13        | 15.12%  |
| Unknown     | 1         | 1.16%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 45        | 52.33%  |
| 1.01-2.0   | 18        | 20.93%  |
| 3.01-4.0   | 11        | 12.79%  |
| 0.01-0.5   | 7         | 8.14%   |
| 0.51-1.0   | 4         | 4.65%   |
| 5.01-6.0   | 1         | 1.16%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 20        | 21.05%  |
| BOE                     | 16        | 16.84%  |
| LG Display              | 15        | 15.79%  |
| Chimei Innolux          | 12        | 12.63%  |
| Samsung Electronics     | 11        | 11.58%  |
| Goldstar                | 4         | 4.21%   |
| Dell                    | 3         | 3.16%   |
| Sharp                   | 2         | 2.11%   |
| LG Philips              | 2         | 2.11%   |
| InfoVision              | 2         | 2.11%   |
| Chi Mei Optoelectronics | 2         | 2.11%   |
| Seiko/Epson             | 1         | 1.05%   |
| LGD                     | 1         | 1.05%   |
| Lenovo                  | 1         | 1.05%   |
| CSO                     | 1         | 1.05%   |
| BenQ                    | 1         | 1.05%   |
| Apple                   | 1         | 1.05%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0575 1920x1080 309x174mm 14.0-inch            | 2         | 2.08%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch             | 2         | 2.08%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch        | 2         | 2.08%   |
| BOE LCD Monitor BOE06B3 1920x1080 310x170mm 13.9-inch                   | 2         | 2.08%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                   | 2         | 2.08%   |
| AU Optronics LCD Monitor AUO272B 3840x2160 293x165mm 13.2-inch          | 2         | 2.08%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch          | 2         | 2.08%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch          | 2         | 2.08%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                 | 1         | 1.04%   |
| Sharp LCD Monitor SHP14B9 3840x2160 344x194mm 15.5-inch                 | 1         | 1.04%   |
| Seiko/Epson LCD Monitor 1280x800                                        | 1         | 1.04%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch       | 1         | 1.04%   |
| Samsung Electronics LCD Monitor SEC5741 1280x800 261x163mm 12.1-inch    | 1         | 1.04%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch    | 1         | 1.04%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch    | 1         | 1.04%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch    | 1         | 1.04%   |
| Samsung Electronics LCD Monitor SDC4341 1366x768 344x194mm 15.5-inch    | 1         | 1.04%   |
| Samsung Electronics LCD Monitor SDC424A 3200x1800 293x165mm 13.2-inch   | 1         | 1.04%   |
| Samsung Electronics LCD Monitor SDC4157 3840x2160 344x194mm 15.5-inch   | 1         | 1.04%   |
| Samsung Electronics LCD Monitor SAM0FEF 3840x2160 1872x1053mm 84.6-inch | 1         | 1.04%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch       | 1         | 1.04%   |
| Samsung Electronics C27R50x SAM0F9D 1920x1080 598x336mm 27.0-inch       | 1         | 1.04%   |
| LGD LCD Monitor 1366x768                                                | 1         | 1.04%   |
| LG Philips LP154WX4-TLC8 LPL0120 1280x800 331x207mm 15.4-inch           | 1         | 1.04%   |
| LG Philips LCD Monitor LPL2A00 1280x800 330x210mm 15.4-inch             | 1         | 1.04%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch            | 1         | 1.04%   |
| LG Display LCD Monitor LGD0504 1366x768 344x194mm 15.5-inch             | 1         | 1.04%   |
| LG Display LCD Monitor LGD04A4 1920x1080 309x174mm 14.0-inch            | 1         | 1.04%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch             | 1         | 1.04%   |
| LG Display LCD Monitor LGD03ED 1366x768 277x156mm 12.5-inch             | 1         | 1.04%   |
| LG Display LCD Monitor LGD03AB 1366x768 344x194mm 15.5-inch             | 1         | 1.04%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch             | 1         | 1.04%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch             | 1         | 1.04%   |
| LG Display LCD Monitor LGD0386 1366x768 309x174mm 14.0-inch             | 1         | 1.04%   |
| LG Display LCD Monitor LGD036C 1366x768 277x156mm 12.5-inch             | 1         | 1.04%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch             | 1         | 1.04%   |
| LG Display LCD Monitor LGD0212 1366x768 309x174mm 14.0-inch             | 1         | 1.04%   |
| Lenovo LCD Monitor LEN4033 1440x900 303x190mm 14.1-inch                 | 1         | 1.04%   |
| InfoVision LCD Monitor IVO8C78 1920x1080 309x174mm 14.0-inch            | 1         | 1.04%   |
| InfoVision LCD Monitor IVO8C65 1920x1080 309x174mm 14.0-inch            | 1         | 1.04%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 41        | 44.09%  |
| 1366x768 (WXGA)   | 30        | 32.26%  |
| 3840x2160 (4K)    | 6         | 6.45%   |
| 1280x800 (WXGA)   | 4         | 4.3%    |
| 2560x1440 (QHD)   | 2         | 2.15%   |
| 1920x1200 (WUXGA) | 2         | 2.15%   |
| 1600x900 (HD+)    | 2         | 2.15%   |
| 3200x1800 (QHD+)  | 1         | 1.08%   |
| 2880x1920         | 1         | 1.08%   |
| 2560x1600         | 1         | 1.08%   |
| 2560x1080         | 1         | 1.08%   |
| 2304x1440         | 1         | 1.08%   |
| 1440x900 (WXGA+)  | 1         | 1.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 37        | 38.54%  |
| 14      | 21        | 21.88%  |
| 13      | 13        | 13.54%  |
| 12      | 5         | 5.21%   |
| 27      | 4         | 4.17%   |
| 16      | 3         | 3.13%   |
| 24      | 2         | 2.08%   |
| 21      | 2         | 2.08%   |
| 11      | 2         | 2.08%   |
| Unknown | 2         | 2.08%   |
| 84      | 1         | 1.04%   |
| 34      | 1         | 1.04%   |
| 31      | 1         | 1.04%   |
| 23      | 1         | 1.04%   |
| 17      | 1         | 1.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 66        | 68.75%  |
| 201-300     | 13        | 13.54%  |
| 501-600     | 7         | 7.29%   |
| 351-400     | 3         | 3.13%   |
| 401-500     | 2         | 2.08%   |
| Unknown     | 2         | 2.08%   |
| 701-800     | 1         | 1.04%   |
| 601-700     | 1         | 1.04%   |
| 1501-2000   | 1         | 1.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 78        | 87.64%  |
| 16/10   | 8         | 8.99%   |
| Unknown | 2         | 2.25%   |
| 21/9    | 1         | 1.12%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 38        | 39.58%  |
| 81-90          | 28        | 29.17%  |
| 71-80          | 6         | 6.25%   |
| 61-70          | 5         | 5.21%   |
| 301-350        | 4         | 4.17%   |
| 201-250        | 4         | 4.17%   |
| 51-60          | 2         | 2.08%   |
| 351-500        | 2         | 2.08%   |
| 111-120        | 2         | 2.08%   |
| Unknown        | 2         | 2.08%   |
| More than 1000 | 1         | 1.04%   |
| 251-300        | 1         | 1.04%   |
| 121-130        | 1         | 1.04%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 42        | 44.21%  |
| 101-120       | 27        | 28.42%  |
| 51-100        | 12        | 12.63%  |
| 161-240       | 7         | 7.37%   |
| More than 240 | 5         | 5.26%   |
| Unknown       | 2         | 2.11%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 72        | 83.72%  |
| 2     | 13        | 15.12%  |
| 0     | 1         | 1.16%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 57        | 46.34%  |
| Realtek Semiconductor    | 39        | 31.71%  |
| Qualcomm Atheros         | 11        | 8.94%   |
| Broadcom                 | 7         | 5.69%   |
| Ralink                   | 4         | 3.25%   |
| Ralink Technology        | 1         | 0.81%   |
| MediaTek                 | 1         | 0.81%   |
| Marvell Technology Group | 1         | 0.81%   |
| Lenovo                   | 1         | 0.81%   |
| Broadcom Limited         | 1         | 0.81%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 21        | 14%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 14        | 9.33%   |
| Intel Wireless 8265 / 8275                                        | 5         | 3.33%   |
| Intel Wireless 7260                                               | 5         | 3.33%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 5         | 3.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 2.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3         | 2%      |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 3         | 2%      |
| Intel Wireless 7265                                               | 3         | 2%      |
| Intel Wireless 3165                                               | 3         | 2%      |
| Intel Wi-Fi 6 AX201                                               | 3         | 2%      |
| Intel Wi-Fi 6 AX200                                               | 3         | 2%      |
| Intel Ethernet Connection I218-LM                                 | 3         | 2%      |
| Intel Comet Lake PCH CNVi WiFi                                    | 3         | 2%      |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 2%      |
| Intel 82577LM Gigabit Network Connection                          | 3         | 2%      |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 1.33%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 1.33%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 1.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 1.33%   |
| Intel Wireless 8260                                               | 2         | 1.33%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.33%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 1.33%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 1.33%   |
| Intel Centrino Ultimate-N 6300                                    | 2         | 1.33%   |
| Intel Centrino Advanced-N 6235                                    | 2         | 1.33%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 2         | 1.33%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 2         | 1.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.67%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.67%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 1         | 0.67%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 0.67%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.67%   |
| Realtek 802.11n WLAN Adapter                                      | 1         | 0.67%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 0.67%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 0.67%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.67%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 0.67%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.67%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 54        | 62.07%  |
| Realtek Semiconductor | 12        | 13.79%  |
| Qualcomm Atheros      | 8         | 9.2%    |
| Broadcom              | 6         | 6.9%    |
| Ralink                | 4         | 4.6%    |
| Ralink Technology     | 1         | 1.15%   |
| MediaTek              | 1         | 1.15%   |
| Broadcom Limited      | 1         | 1.15%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                     | 5         | 5.75%   |
| Intel Wireless 7260                                            | 5         | 5.75%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 5         | 5.75%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 3         | 3.45%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 3         | 3.45%   |
| Intel Wireless 7265                                            | 3         | 3.45%   |
| Intel Wireless 3165                                            | 3         | 3.45%   |
| Intel Wi-Fi 6 AX201                                            | 3         | 3.45%   |
| Intel Wi-Fi 6 AX200                                            | 3         | 3.45%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 3         | 3.45%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 3         | 3.45%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2         | 2.3%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 2         | 2.3%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 2         | 2.3%    |
| Intel Wireless 8260                                            | 2         | 2.3%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 2.3%    |
| Intel Centrino Ultimate-N 6300                                 | 2         | 2.3%    |
| Intel Centrino Advanced-N 6235                                 | 2         | 2.3%    |
| Intel Alder Lake-P PCH CNVi WiFi                               | 2         | 2.3%    |
| Broadcom BCM43228 802.11a/b/g/n                                | 2         | 2.3%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.15%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.15%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 1         | 1.15%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 1.15%   |
| Realtek 802.11n WLAN Adapter                                   | 1         | 1.15%   |
| Ralink MT7601U Wireless Adapter                                | 1         | 1.15%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 1         | 1.15%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 1.15%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 1.15%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 1.15%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 1.15%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 1.15%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 1.15%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 1         | 1.15%   |
| Intel Wireless-AC 9260                                         | 1         | 1.15%   |
| Intel Wireless 3160                                            | 1         | 1.15%   |
| Intel WiFi Link 5100                                           | 1         | 1.15%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 1         | 1.15%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 1         | 1.15%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 1         | 1.15%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 37        | 59.68%  |
| Intel                    | 19        | 30.65%  |
| Qualcomm Atheros         | 3         | 4.84%   |
| Marvell Technology Group | 1         | 1.61%   |
| Lenovo                   | 1         | 1.61%   |
| Broadcom                 | 1         | 1.61%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 21        | 33.33%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 14        | 22.22%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 6.35%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 4.76%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 4.76%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 3.17%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 3.17%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 3.17%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.59%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.59%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.59%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.59%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 1.59%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 1.59%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.59%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.59%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.59%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 1.59%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 1.59%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.59%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 84        | 57.53%  |
| Ethernet | 62        | 42.47%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 74        | 86.05%  |
| Ethernet | 12        | 13.95%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 61        | 70.93%  |
| 1     | 24        | 27.91%  |
| 0     | 1         | 1.16%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 70        | 81.4%   |
| Yes  | 16        | 18.6%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 41        | 60.29%  |
| Realtek Semiconductor           | 7         | 10.29%  |
| Qualcomm Atheros Communications | 6         | 8.82%   |
| Broadcom                        | 4         | 5.88%   |
| Ralink                          | 3         | 4.41%   |
| Toshiba                         | 2         | 2.94%   |
| Dell                            | 2         | 2.94%   |
| MediaTek                        | 1         | 1.47%   |
| Hewlett-Packard                 | 1         | 1.47%   |
| Foxconn / Hon Hai               | 1         | 1.47%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface               | 15        | 22.06%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)   | 11        | 16.18%  |
| Realtek Bluetooth Radio                          | 6         | 8.82%   |
| Intel AX201 Bluetooth                            | 6         | 8.82%   |
| Ralink RT3290 Bluetooth                          | 3         | 4.41%   |
| Intel Centrino Bluetooth Wireless Transceiver    | 3         | 4.41%   |
| Intel AX200 Bluetooth                            | 3         | 4.41%   |
| Qualcomm Atheros  Bluetooth Device               | 2         | 2.94%   |
| Intel Bluetooth Device                           | 2         | 2.94%   |
| Toshiba RT Bluetooth Radio                       | 1         | 1.47%   |
| Toshiba Integrated Bluetooth HCI                 | 1         | 1.47%   |
| Realtek RTL8821A Bluetooth                       | 1         | 1.47%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0           | 1         | 1.47%   |
| Qualcomm Atheros Bluetooth USB Host Controller   | 1         | 1.47%   |
| Qualcomm Atheros AR9462 Bluetooth                | 1         | 1.47%   |
| Qualcomm Atheros AR3011 Bluetooth                | 1         | 1.47%   |
| MediaTek Wireless_Device                         | 1         | 1.47%   |
| Intel Wireless-AC 9260 Bluetooth Adapter         | 1         | 1.47%   |
| HP Broadcom 2070 Bluetooth Combo                 | 1         | 1.47%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller  | 1         | 1.47%   |
| Dell DW375 Bluetooth Module                      | 1         | 1.47%   |
| Dell BCM20702A0 Bluetooth Module                 | 1         | 1.47%   |
| Broadcom HP Portable SoftSailing                 | 1         | 1.47%   |
| Broadcom BCM43142A0 Bluetooth 4.0                | 1         | 1.47%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]       | 1         | 1.47%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller] | 1         | 1.47%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Intel    | 80        | 77.67%  |
| Nvidia   | 15        | 14.56%  |
| AMD      | 6         | 5.83%   |
| Logitech | 1         | 0.97%   |
| Lenovo   | 1         | 0.97%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 14        | 11.48%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 9         | 7.38%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 8         | 6.56%   |
| Intel 8 Series HD Audio Controller                                                                | 8         | 6.56%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 7         | 5.74%   |
| Intel Cannon Lake PCH cAVS                                                                        | 7         | 5.74%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 5         | 4.1%    |
| AMD Family 17h/19h HD Audio Controller                                                            | 5         | 4.1%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 3.28%   |
| Intel Broadwell-U Audio Controller                                                                | 4         | 3.28%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 3.28%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 3.28%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 2.46%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 2.46%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 2.46%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 2.46%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 2.46%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 1.64%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 1.64%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 1.64%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 1.64%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 1.64%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 1.64%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.82%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 0.82%   |
| Nvidia Audio device                                                                               | 1         | 0.82%   |
| Logitech H390 headset with microphone                                                             | 1         | 0.82%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                                      | 1         | 0.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 0.82%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 0.82%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 0.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series Low Power Engine Audio           | 1         | 0.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.82%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 0.82%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 0.82%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 0.82%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 0.82%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 0.82%   |
| AMD FCH Azalia Controller                                                                         | 1         | 0.82%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 14        | 31.82%  |
| SK hynix            | 10        | 22.73%  |
| Micron Technology   | 7         | 15.91%  |
| Crucial             | 5         | 11.36%  |
| Ramaxel Technology  | 3         | 6.82%   |
| Kingston            | 3         | 6.82%   |
| Unknown             | 2         | 4.55%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s          | 2         | 4.44%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s           | 2         | 4.44%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s       | 2         | 4.44%   |
| Micron RAM MTC8C1084S1SC48BA1 16GB SODIMM DDR5 4800MT/s         | 2         | 4.44%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2667MT/s                  | 1         | 2.22%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                      | 1         | 2.22%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                      | 1         | 2.22%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s          | 1         | 2.22%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s          | 1         | 2.22%   |
| SK hynix RAM HMT125S6TFR8C-G7 2GB SODIMM DDR3 1067MT/s          | 1         | 2.22%   |
| SK hynix RAM HMAA51S6AMR6N-UH 8GB SODIMM DDR4 2400MT/s          | 1         | 2.22%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s         | 1         | 2.22%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s          | 1         | 2.22%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s         | 1         | 2.22%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s         | 1         | 2.22%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s          | 1         | 2.22%   |
| SK hynix RAM H5ANAG6NCMR-XNC 8GB Row Of Chips DDR4 3200MT/s     | 1         | 2.22%   |
| Samsung RAM Module 32GB SODIMM DDR4 3200MT/s                    | 1         | 2.22%   |
| Samsung RAM M471B5673EH1-CH9 2GB SODIMM DDR3 1334MT/s           | 1         | 2.22%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s           | 1         | 2.22%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s           | 1         | 2.22%   |
| Samsung RAM M471A5143DB0-CPB 4GB SODIMM DDR4 2133MT/s           | 1         | 2.22%   |
| Samsung RAM M471A1K44BM0-CRC 8GB SODIMM DDR4 2400MT/s           | 1         | 2.22%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s        | 1         | 2.22%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s           | 1         | 2.22%   |
| Samsung RAM M425R2GA3BB0-CQKOD 16GB SODIMM DDR5 4800MT/s        | 1         | 2.22%   |
| Samsung RAM K4EBE304EC-EGCG 8GB Row Of Chips LPDDR3 2133MT/s    | 1         | 2.22%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB Row Of Chips DDR4 2400MT/s | 1         | 2.22%   |
| Micron RAM Module 8192MB SODIMM DDR4 3200MT/s                   | 1         | 2.22%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s            | 1         | 2.22%   |
| Micron RAM 18ASF2G72HZ-2G3B1 16GB SODIMM DDR4 2400MT/s          | 1         | 2.22%   |
| Micron RAM 16JTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s           | 1         | 2.22%   |
| Micron RAM 16ATF1G64HZ-2G1B1 8GB SODIMM DDR4 2133MT/s           | 1         | 2.22%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s            | 1         | 2.22%   |
| Kingston RAM HP26D4S9S8MHF-8 8GB SODIMM DDR4 2667MT/s           | 1         | 2.22%   |
| Kingston RAM 99U5428-053.A00LF 8GB SODIMM DDR3 1600MT/s         | 1         | 2.22%   |
| Crucial RAM CT8G4SFS8266.C8FD1 8GB SODIMM DDR4 2667MT/s         | 1         | 2.22%   |
| Crucial RAM CT32G48C40S5.M16A1 32GB SODIMM DDR5 4800MT/s        | 1         | 2.22%   |
| Crucial RAM CT16G4SFRA32A.M16FR 16GB SODIMM DDR4 3200MT/s       | 1         | 2.22%   |
| Crucial RAM CT16G4SFRA32A.C8FB 16GB SODIMM DDR4 3200MT/s        | 1         | 2.22%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 26        | 70.27%  |
| DDR3   | 7         | 18.92%  |
| DDR5   | 2         | 5.41%   |
| LPDDR3 | 1         | 2.7%    |
| DDR2   | 1         | 2.7%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 35        | 92.11%  |
| Row Of Chips | 3         | 7.89%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 17        | 40.48%  |
| 16384 | 12        | 28.57%  |
| 4096  | 6         | 14.29%  |
| 32768 | 3         | 7.14%   |
| 2048  | 3         | 7.14%   |
| 1024  | 1         | 2.38%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 14        | 35%     |
| 3200  | 9         | 22.5%   |
| 2400  | 4         | 10%     |
| 1600  | 4         | 10%     |
| 2133  | 3         | 7.5%    |
| 4800  | 2         | 5%      |
| 1334  | 2         | 5%      |
| 1067  | 1         | 2.5%    |
| 667   | 1         | 2.5%    |

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
| Chicony Electronics                    | 23        | 28.4%   |
| IMC Networks                           | 9         | 11.11%  |
| Cheng Uei Precision Industry (Foxlink) | 7         | 8.64%   |
| Acer                                   | 7         | 8.64%   |
| Microdia                               | 6         | 7.41%   |
| Sunplus Innovation Technology          | 5         | 6.17%   |
| Realtek Semiconductor                  | 4         | 4.94%   |
| Syntek                                 | 3         | 3.7%    |
| Ricoh                                  | 3         | 3.7%    |
| Suyin                                  | 2         | 2.47%   |
| Quanta                                 | 2         | 2.47%   |
| Apple                                  | 2         | 2.47%   |
| Ruision                                | 1         | 1.23%   |
| Microsoft                              | 1         | 1.23%   |
| Luxvisions Innotech Limited            | 1         | 1.23%   |
| Logitech                               | 1         | 1.23%   |
| Lite-On Technology                     | 1         | 1.23%   |
| Lenovo                                 | 1         | 1.23%   |
| DJKANA19IDX53W                         | 1         | 1.23%   |
| Alcor Micro                            | 1         | 1.23%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 8         | 9.88%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 5         | 6.17%   |
| Syntek Integrated Camera                                        | 3         | 3.7%    |
| Chicony Integrated Camera (1280x720@30)                         | 3         | 3.7%    |
| Sunplus HP HD Webcam [Fixed]                                    | 2         | 2.47%   |
| Ricoh HD Webcam                                                 | 2         | 2.47%   |
| Quanta HP TrueVision HD Camera                                  | 2         | 2.47%   |
| Microdia Laptop_Integrated_Webcam_HD                            | 2         | 2.47%   |
| Microdia Integrated_Webcam_HD                                   | 2         | 2.47%   |
| IMC Networks Integrated Camera                                  | 2         | 2.47%   |
| Chicony Lenovo EasyCamera                                       | 2         | 2.47%   |
| Chicony HP Truevision HD                                        | 2         | 2.47%   |
| Chicony HP HD Webcam [Fixed]                                    | 2         | 2.47%   |
| Chicony EasyCamera                                              | 2         | 2.47%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 2         | 2.47%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam             | 2         | 2.47%   |
| Apple iPhone 5/5C/5S/6/SE                                       | 2         | 2.47%   |
| Suyin HP TrueVision HD                                          | 1         | 1.23%   |
| Suyin 1.3M HD WebCam                                            | 1         | 1.23%   |
| Sunplus Integrated_Webcam_HD                                    | 1         | 1.23%   |
| Sunplus Integrated_Webcam_FHD                                   | 1         | 1.23%   |
| Sunplus Integrated Webcam                                       | 1         | 1.23%   |
| Ruision UVC Camera                                              | 1         | 1.23%   |
| Ricoh Sony Vaio Integrated Webcam                               | 1         | 1.23%   |
| Realtek Lenovo EasyCamera                                       | 1         | 1.23%   |
| Realtek Integrated_Webcam_HD                                    | 1         | 1.23%   |
| Realtek Integrated Webcam                                       | 1         | 1.23%   |
| Realtek HP Truevision HD                                        | 1         | 1.23%   |
| Microsoft LifeCam HD-3000                                       | 1         | 1.23%   |
| Microdia Integrated Webcam                                      | 1         | 1.23%   |
| Microdia Dell Integrated HD Webcam                              | 1         | 1.23%   |
| Luxvisions Innotech Limited HP HD Camera                        | 1         | 1.23%   |
| Logitech Webcam C270                                            | 1         | 1.23%   |
| Lite-On HP HD Camera                                            | 1         | 1.23%   |
| Lenovo Integrated Webcam                                        | 1         | 1.23%   |
| IMC Networks USB2.0 VGA UVC WebCam                              | 1         | 1.23%   |
| IMC Networks HP TrueVision HD Camera                            | 1         | 1.23%   |
| DJKANA19IDX53W HP Wide Vision HD Camera                         | 1         | 1.23%   |
| Chicony USB 2.0 Camera                                          | 1         | 1.23%   |
| Chicony TOSHIBA Web Camera - HD                                 | 1         | 1.23%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 11        | 45.83%  |
| Validity Sensors           | 10        | 41.67%  |
| STMicroelectronics         | 1         | 4.17%   |
| Shenzhen Goodix Technology | 1         | 4.17%   |
| Elan Microelectronics      | 1         | 4.17%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Unknown                                                    | 4         | 16.67%  |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 3         | 12.5%   |
| Validity Sensors VFS491                                    | 2         | 8.33%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 2         | 8.33%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 2         | 8.33%   |
| Validity Sensors VFS5011 Fingerprint Reader                | 1         | 4.17%   |
| Validity Sensors VFS495 Fingerprint Reader                 | 1         | 4.17%   |
| Validity Sensors VFS Fingerprint sensor                    | 1         | 4.17%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 1         | 4.17%   |
| Validity Sensors Synaptics WBDI                            | 1         | 4.17%   |
| Validity Sensors Fingerprint scanner                       | 1         | 4.17%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 4.17%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 1         | 4.17%   |
| STMicroelectronics Fingerprint Reader                      | 1         | 4.17%   |
| Shenzhen Goodix Fingerprint Reader                         | 1         | 4.17%   |
| Elan ELAN:ARM-M4                                           | 1         | 4.17%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 3         | 50%     |
| Alcor Micro | 2         | 33.33%  |
| Upek        | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 33.33%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 16.67%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 41        | 47.67%  |
| 1     | 36        | 41.86%  |
| 2     | 8         | 9.3%    |
| 3     | 1         | 1.16%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 24        | 44.44%  |
| Graphics card            | 11        | 20.37%  |
| Chipcard                 | 6         | 11.11%  |
| Net/wireless             | 5         | 9.26%   |
| Bluetooth                | 3         | 5.56%   |
| Camera                   | 2         | 3.7%    |
| Sound                    | 1         | 1.85%   |
| Multimedia controller    | 1         | 1.85%   |
| Communication controller | 1         | 1.85%   |

