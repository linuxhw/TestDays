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

Total: 138

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04       | 23        | 22.55%  |
| Ubuntu 18.04       | 9         | 8.82%   |
| Ubuntu 22.04       | 7         | 6.86%   |
| Arch               | 5         | 4.9%    |
| Zorin 15           | 3         | 2.94%   |
| Ubuntu 20.10       | 3         | 2.94%   |
| Ubuntu 19.10       | 3         | 2.94%   |
| Pop!_OS 22.04      | 3         | 2.94%   |
| Fedora 36          | 3         | 2.94%   |
| Ubuntu 21.10       | 2         | 1.96%   |
| Ubuntu 16.04       | 2         | 1.96%   |
| Linux Mint 20.3    | 2         | 1.96%   |
| KDE neon 20.04     | 2         | 1.96%   |
| Fedora 37          | 2         | 1.96%   |
| Debian 11          | 2         | 1.96%   |
| BlackPanther 18.1  | 2         | 1.96%   |
| ArcoLinux Rolling  | 2         | 1.96%   |
| Xubuntu 20.04      | 1         | 0.98%   |
| Ubuntu Unity 18.04 | 1         | 0.98%   |
| Ubuntu 22.10       | 1         | 0.98%   |
| Ubuntu 19.04       | 1         | 0.98%   |
| SteamOS 3.4.4      | 1         | 0.98%   |
| SteamOS 3.3.2      | 1         | 0.98%   |
| ROSA 12.2          | 1         | 0.98%   |
| Rocky Linux 9.1    | 1         | 0.98%   |
| Pop!_OS 21.10      | 1         | 0.98%   |
| Pop!_OS 20.10      | 1         | 0.98%   |
| Pop!_OS 20.04      | 1         | 0.98%   |
| OpenMandriva 4.90  | 1         | 0.98%   |
| OpenMandriva 4.3   | 1         | 0.98%   |
| OpenMandriva 4.2   | 1         | 0.98%   |
| OpenMandriva 23.01 | 1         | 0.98%   |
| Manjaro 21.2.1     | 1         | 0.98%   |
| Manjaro 18.1.4     | 1         | 0.98%   |
| Manjaro            | 1         | 0.98%   |
| Linux Mint 20.1    | 1         | 0.98%   |
| Linux Mint 19.2    | 1         | 0.98%   |
| Kubuntu 22.04      | 1         | 0.98%   |
| Kali 2023.1        | 1         | 0.98%   |
| GNOME OS Nightly   | 1         | 0.98%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 49        | 49%     |
| Pop!_OS      | 6         | 6%      |
| Fedora       | 6         | 6%      |
| Arch         | 5         | 5%      |
| OpenMandriva | 4         | 4%      |
| Linux Mint   | 4         | 4%      |
| Zorin        | 3         | 3%      |
| Manjaro      | 3         | 3%      |
| SteamOS      | 2         | 2%      |
| KDE neon     | 2         | 2%      |
| Debian       | 2         | 2%      |
| BlackPanther | 2         | 2%      |
| ArcoLinux    | 2         | 2%      |
| Xubuntu      | 1         | 1%      |
| Ubuntu Unity | 1         | 1%      |
| ROSA         | 1         | 1%      |
| Rocky Linux  | 1         | 1%      |
| Kubuntu      | 1         | 1%      |
| Kali         | 1         | 1%      |
| GNOME OS     | 1         | 1%      |
| Feren OS     | 1         | 1%      |
| Endless      | 1         | 1%      |
| Elementary   | 1         | 1%      |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Notebooks | Percent |
|-----------------------------|-----------|---------|
| 5.4.0-42-generic            | 5         | 4.63%   |
| 5.4.0-58-generic            | 4         | 3.7%    |
| 5.4.0-26-generic            | 3         | 2.78%   |
| 5.4.0-33-generic            | 2         | 1.85%   |
| 5.4.0-29-generic            | 2         | 1.85%   |
| 5.3.0-40-generic            | 2         | 1.85%   |
| 5.3.0-29-generic            | 2         | 1.85%   |
| 4.15.0-50-generic           | 2         | 1.85%   |
| 6.1.8-603.inttf.fc37.x86_64 | 1         | 0.93%   |
| 6.1.6-200.fc37.x86_64       | 1         | 0.93%   |
| 6.1.12-060112-generic       | 1         | 0.93%   |
| 6.1.11-76060111-generic     | 1         | 0.93%   |
| 6.1.1-desktop-1omv2290      | 1         | 0.93%   |
| 6.1.0-kali5-amd64           | 1         | 0.93%   |
| 6.0.6-76060006-generic      | 1         | 0.93%   |
| 6.0.12-76060006-generic     | 1         | 0.93%   |
| 5.9.3-arch1-1               | 1         | 0.93%   |
| 5.8.5-arch1-1               | 1         | 0.93%   |
| 5.8.0-7642-generic          | 1         | 0.93%   |
| 5.8.0-7630-generic          | 1         | 0.93%   |
| 5.8.0-54-generic            | 1         | 0.93%   |
| 5.8.0-53-generic            | 1         | 0.93%   |
| 5.8.0-50-generic            | 1         | 0.93%   |
| 5.8.0-41-generic            | 1         | 0.93%   |
| 5.8.0-40-generic            | 1         | 0.93%   |
| 5.7.6-arch1-1               | 1         | 0.93%   |
| 5.7.14                      | 1         | 0.93%   |
| 5.6.16-1-MANJARO            | 1         | 0.93%   |
| 5.6.14-desktop-2bP          | 1         | 0.93%   |
| 5.4.68-1-lts                | 1         | 0.93%   |
| 5.4.2-1-MANJARO             | 1         | 0.93%   |
| 5.4.0-81-generic            | 1         | 0.93%   |
| 5.4.0-73-generic            | 1         | 0.93%   |
| 5.4.0-72-generic            | 1         | 0.93%   |
| 5.4.0-65-generic            | 1         | 0.93%   |
| 5.4.0-60-generic            | 1         | 0.93%   |
| 5.4.0-54-generic            | 1         | 0.93%   |
| 5.4.0-48-generic            | 1         | 0.93%   |
| 5.4.0-45-generic            | 1         | 0.93%   |
| 5.4.0-39-generic            | 1         | 0.93%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 26        | 25%     |
| 4.15.0  | 9         | 8.65%   |
| 5.8.0   | 7         | 6.73%   |
| 5.15.0  | 6         | 5.77%   |
| 5.3.0   | 5         | 4.81%   |
| 5.11.0  | 5         | 4.81%   |
| 5.13.0  | 4         | 3.85%   |
| 5.19.0  | 3         | 2.88%   |
| 5.14.0  | 2         | 1.92%   |
| 5.10.0  | 2         | 1.92%   |
| 5.0.0   | 2         | 1.92%   |
| 6.1.8   | 1         | 0.96%   |
| 6.1.6   | 1         | 0.96%   |
| 6.1.12  | 1         | 0.96%   |
| 6.1.11  | 1         | 0.96%   |
| 6.1.1   | 1         | 0.96%   |
| 6.1.0   | 1         | 0.96%   |
| 6.0.6   | 1         | 0.96%   |
| 6.0.12  | 1         | 0.96%   |
| 5.9.3   | 1         | 0.96%   |
| 5.8.5   | 1         | 0.96%   |
| 5.7.6   | 1         | 0.96%   |
| 5.7.14  | 1         | 0.96%   |
| 5.6.16  | 1         | 0.96%   |
| 5.6.14  | 1         | 0.96%   |
| 5.4.68  | 1         | 0.96%   |
| 5.4.2   | 1         | 0.96%   |
| 5.19.8  | 1         | 0.96%   |
| 5.19.13 | 1         | 0.96%   |
| 5.18.12 | 1         | 0.96%   |
| 5.18.11 | 1         | 0.96%   |
| 5.16.7  | 1         | 0.96%   |
| 5.16.5  | 1         | 0.96%   |
| 5.16.18 | 1         | 0.96%   |
| 5.16.16 | 1         | 0.96%   |
| 5.16.12 | 1         | 0.96%   |
| 5.15.5  | 1         | 0.96%   |
| 5.15.12 | 1         | 0.96%   |
| 5.10.74 | 1         | 0.96%   |
| 5.10.14 | 1         | 0.96%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 28        | 27.18%  |
| 4.15    | 9         | 8.74%   |
| 5.8     | 8         | 7.77%   |
| 5.15    | 8         | 7.77%   |
| 6.1     | 6         | 5.83%   |
| 5.3     | 5         | 4.85%   |
| 5.19    | 5         | 4.85%   |
| 5.11    | 5         | 4.85%   |
| 5.16    | 4         | 3.88%   |
| 5.13    | 4         | 3.88%   |
| 5.10    | 4         | 3.88%   |
| 6.0     | 2         | 1.94%   |
| 5.7     | 2         | 1.94%   |
| 5.6     | 2         | 1.94%   |
| 5.18    | 2         | 1.94%   |
| 5.14    | 2         | 1.94%   |
| 5.0     | 2         | 1.94%   |
| 4.18    | 2         | 1.94%   |
| 5.9     | 1         | 0.97%   |
| 4.4     | 1         | 0.97%   |
| 4.19    | 1         | 0.97%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 98        | 98.99%  |
| i686   | 1         | 1.01%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 63        | 61.17%  |
| KDE5       | 13        | 12.62%  |
| Unknown    | 12        | 11.65%  |
| KDE        | 4         | 3.88%   |
| X-Cinnamon | 3         | 2.91%   |
| XFCE       | 2         | 1.94%   |
| MATE       | 2         | 1.94%   |
| Unity      | 1         | 0.97%   |
| Pantheon   | 1         | 0.97%   |
| DWM        | 1         | 0.97%   |
| awesome    | 1         | 0.97%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 71        | 71%     |
| Wayland | 21        | 21%     |
| Unknown | 8         | 8%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 57        | 57%     |
| GDM     | 18        | 18%     |
| SDDM    | 10        | 10%     |
| GDM3    | 10        | 10%     |
| LightDM | 3         | 3%      |
| TDM     | 2         | 2%      |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 77        | 77%     |
| Unknown | 11        | 11%     |
| en_GB   | 4         | 4%      |
| C       | 2         | 2%      |
| ru_RU   | 1         | 1%      |
| pl_PL   | 1         | 1%      |
| hu_HU   | 1         | 1%      |
| en_IN   | 1         | 1%      |
| en_AU   | 1         | 1%      |
| de_DE   | 1         | 1%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 56        | 54.9%   |
| BIOS | 46        | 45.1%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 84        | 84.85%  |
| Btrfs   | 8         | 8.08%   |
| Overlay | 6         | 6.06%   |
| Xfs     | 1         | 1.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 58        | 58%     |
| GPT     | 38        | 38%     |
| MBR     | 4         | 4%      |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 90        | 90.91%  |
| Yes       | 9         | 9.09%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 58        | 58.59%  |
| Yes       | 41        | 41.41%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Lenovo                      | 28        | 28.28%  |
| Hewlett-Packard             | 26        | 26.26%  |
| Dell                        | 15        | 15.15%  |
| ASUSTek Computer            | 6         | 6.06%   |
| Toshiba                     | 5         | 5.05%   |
| Acer                        | 3         | 3.03%   |
| Valve                       | 2         | 2.02%   |
| Sony                        | 2         | 2.02%   |
| Notebook                    | 2         | 2.02%   |
| MSI                         | 2         | 2.02%   |
| Google                      | 2         | 2.02%   |
| YJKC                        | 1         | 1.01%   |
| win element                 | 1         | 1.01%   |
| LG Electronics              | 1         | 1.01%   |
| I-Life Digital Technologies | 1         | 1.01%   |
| Apple                       | 1         | 1.01%   |
| A-DATA Technology           | 1         | 1.01%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Valve Jupiter                               | 2         | 2.02%   |
| HP Pavilion Notebook                        | 2         | 2.02%   |
| HP ENVY Laptop 13-aq0xxx                    | 2         | 2.02%   |
| Dell G5 5587                                | 2         | 2.02%   |
| YJKC vBOOK Plus                             | 1         | 1.01%   |
| win element MoreFine S500+                  | 1         | 1.01%   |
| Toshiba TECRA X40-D                         | 1         | 1.01%   |
| Toshiba TECRA A50-C                         | 1         | 1.01%   |
| Toshiba Satellite C850-A966                 | 1         | 1.01%   |
| Toshiba Satellite C660                      | 1         | 1.01%   |
| Toshiba Satellite A300                      | 1         | 1.01%   |
| Sony VGN-NS10J_S                            | 1         | 1.01%   |
| Sony SVE14A25CAB                            | 1         | 1.01%   |
| Notebook PD5x_7xPNP_PNN_PNT                 | 1         | 1.01%   |
| Notebook P95_96_97Ex,Rx                     | 1         | 1.01%   |
| MSI PS63 Modern 8RD                         | 1         | 1.01%   |
| MSI Modern 14 B5M                           | 1         | 1.01%   |
| LG C500-G.AEF5BE1                           | 1         | 1.01%   |
| Lenovo Yoga S730-13IWL 81J0                 | 1         | 1.01%   |
| Lenovo Yoga 2 Pro 20266                     | 1         | 1.01%   |
| Lenovo ThinkPad X240 20AMS6GB00             | 1         | 1.01%   |
| Lenovo ThinkPad X230 2325DV8                | 1         | 1.01%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TK001HUS | 1         | 1.01%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XW00A9US  | 1         | 1.01%   |
| Lenovo ThinkPad T61 76653JG                 | 1         | 1.01%   |
| Lenovo ThinkPad T480s 20L8S3FV00            | 1         | 1.01%   |
| Lenovo ThinkPad T480s 20L7001PAD            | 1         | 1.01%   |
| Lenovo ThinkPad T470 W10DG 20JMS0Q300       | 1         | 1.01%   |
| Lenovo ThinkPad T460s 20FAS1U207            | 1         | 1.01%   |
| Lenovo ThinkPad T460 20FMS1A200             | 1         | 1.01%   |
| Lenovo ThinkPad P1 Gen 5 21DC000DCK         | 1         | 1.01%   |
| Lenovo ThinkPad P1 Gen 3 20TJS4RX00         | 1         | 1.01%   |
| Lenovo ThinkPad L480 20LS0012AD             | 1         | 1.01%   |
| Lenovo ThinkPad E14 Gen 2 20TA0018AD        | 1         | 1.01%   |
| Lenovo Legion Y7000P 81LD                   | 1         | 1.01%   |
| Lenovo IdeaPadFlex 14 20308                 | 1         | 1.01%   |
| Lenovo IdeaPad Gaming 3 15IMH05 81Y4        | 1         | 1.01%   |
| Lenovo IdeaPad 700-15ISK 80RU               | 1         | 1.01%   |
| Lenovo IdeaPad 320-15IKB 80XL               | 1         | 1.01%   |
| Lenovo IdeaPad 3 14IML05 81WA               | 1         | 1.01%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 14        | 14.14%  |
| Lenovo IdeaPad       | 7         | 7.07%   |
| HP Pavilion          | 7         | 7.07%   |
| HP EliteBook         | 7         | 7.07%   |
| Dell Latitude        | 5         | 5.05%   |
| HP Laptop            | 4         | 4.04%   |
| Toshiba Satellite    | 3         | 3.03%   |
| HP ProBook           | 3         | 3.03%   |
| Dell XPS             | 3         | 3.03%   |
| Dell Inspiron        | 3         | 3.03%   |
| Valve Jupiter        | 2         | 2.02%   |
| Toshiba TECRA        | 2         | 2.02%   |
| Lenovo Yoga          | 2         | 2.02%   |
| HP ENVY              | 2         | 2.02%   |
| Dell G5              | 2         | 2.02%   |
| ASUS VivoBook        | 2         | 2.02%   |
| Acer Aspire          | 2         | 2.02%   |
| YJKC vBOOK           | 1         | 1.01%   |
| win element MoreFine | 1         | 1.01%   |
| Sony VGN-NS10J       | 1         | 1.01%   |
| Sony SVE14A25CAB     | 1         | 1.01%   |
| Notebook PD5x        | 1         | 1.01%   |
| Notebook P95         | 1         | 1.01%   |
| MSI PS63             | 1         | 1.01%   |
| MSI Modern           | 1         | 1.01%   |
| LG C500-G.AEF5BE1    | 1         | 1.01%   |
| Lenovo Legion        | 1         | 1.01%   |
| Lenovo IdeaPadFlex   | 1         | 1.01%   |
| Lenovo G500          | 1         | 1.01%   |
| Lenovo G50-80        | 1         | 1.01%   |
| Lenovo 81FV          | 1         | 1.01%   |
| I-Life Digital ZED   | 1         | 1.01%   |
| HP Presario          | 1         | 1.01%   |
| HP Notebook          | 1         | 1.01%   |
| HP 250               | 1         | 1.01%   |
| Google Terra         | 1         | 1.01%   |
| Google Akemi         | 1         | 1.01%   |
| Dell Vostro          | 1         | 1.01%   |
| Dell Precision       | 1         | 1.01%   |
| ASUS Strix           | 1         | 1.01%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2018 | 13        | 13.13%  |
| 2019 | 12        | 12.12%  |
| 2013 | 11        | 11.11%  |
| 2020 | 10        | 10.1%   |
| 2021 | 9         | 9.09%   |
| 2012 | 7         | 7.07%   |
| 2017 | 6         | 6.06%   |
| 2016 | 5         | 5.05%   |
| 2014 | 5         | 5.05%   |
| 2010 | 5         | 5.05%   |
| 2022 | 4         | 4.04%   |
| 2011 | 4         | 4.04%   |
| 2015 | 3         | 3.03%   |
| 2008 | 3         | 3.03%   |
| 2007 | 2         | 2.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 99        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 87        | 87.88%  |
| Enabled  | 12        | 12.12%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 97        | 97.98%  |
| Yes  | 2         | 2.02%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 25        | 25.25%  |
| 16.01-24.0  | 19        | 19.19%  |
| 8.01-16.0   | 19        | 19.19%  |
| 3.01-4.0    | 17        | 17.17%  |
| 32.01-64.0  | 10        | 10.1%   |
| 64.01-256.0 | 3         | 3.03%   |
| 2.01-3.0    | 2         | 2.02%   |
| 1.01-2.0    | 2         | 2.02%   |
| 24.01-32.0  | 1         | 1.01%   |
| 0.51-1.0    | 1         | 1.01%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 36        | 33.96%  |
| 4.01-8.0  | 22        | 20.75%  |
| 2.01-3.0  | 22        | 20.75%  |
| 3.01-4.0  | 18        | 16.98%  |
| 0.51-1.0  | 4         | 3.77%   |
| 8.01-16.0 | 3         | 2.83%   |
| 0.01-0.5  | 1         | 0.94%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 77        | 77.78%  |
| 2      | 19        | 19.19%  |
| 0      | 2         | 2.02%   |
| 3      | 1         | 1.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 68        | 68.69%  |
| Yes       | 31        | 31.31%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 71        | 71.72%  |
| No        | 28        | 28.28%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 97        | 97.98%  |
| No        | 2         | 2.02%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 80        | 80.81%  |
| No        | 19        | 19.19%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| UAE     | 99        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Dubai            | 46        | 45.1%   |
| Abu Dhabi        | 29        | 28.43%  |
| Sharjah          | 16        | 15.69%  |
| Al Ain City      | 5         | 4.9%    |
| Ajman            | 4         | 3.92%   |
| Al Halah         | 1         | 0.98%   |
| Al Fujairah City | 1         | 0.98%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 18        | 19     | 15.65%  |
| Samsung Electronics         | 18        | 18     | 15.65%  |
| Toshiba                     | 11        | 11     | 9.57%   |
| Seagate                     | 11        | 13     | 9.57%   |
| Unknown                     | 6         | 10     | 5.22%   |
| Intel                       | 6         | 7      | 5.22%   |
| HGST                        | 6         | 7      | 5.22%   |
| Crucial                     | 5         | 5      | 4.35%   |
| SK hynix                    | 4         | 5      | 3.48%   |
| Micron Technology           | 4         | 4      | 3.48%   |
| SanDisk                     | 3         | 3      | 2.61%   |
| Kingston                    | 3         | 3      | 2.61%   |
| Hitachi                     | 3         | 3      | 2.61%   |
| Micron/Crucial Technology   | 2         | 2      | 1.74%   |
| Apple                       | 2         | 3      | 1.74%   |
| Realtek Semiconductor       | 1         | 1      | 0.87%   |
| Phison                      | 1         | 1      | 0.87%   |
| Patriot                     | 1         | 1      | 0.87%   |
| Lite-On                     | 1         | 1      | 0.87%   |
| KIOXIA                      | 1         | 3      | 0.87%   |
| Kingston Technology Company | 1         | 1      | 0.87%   |
| KingSpec                    | 1         | 2      | 0.87%   |
| JMicron Technology          | 1         | 1      | 0.87%   |
| Fujitsu                     | 1         | 1      | 0.87%   |
| External                    | 1         | 1      | 0.87%   |
| China                       | 1         | 1      | 0.87%   |
| ADATA Technology            | 1         | 1      | 0.87%   |
| A-DATA Technology           | 1         | 1      | 0.87%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel NVMe SSD Drive 512GB             | 3         | 2.5%    |
| HGST HTS725050A7E630 500GB             | 3         | 2.5%    |
| WDC WD10SPZX-08Z10 1TB                 | 2         | 1.67%   |
| WDC WD10JPCX-24UE4T0 1TB               | 2         | 1.67%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB     | 2         | 1.67%   |
| Unknown MMC Card  64GB                 | 2         | 1.67%   |
| Unknown MMC Card  16GB                 | 2         | 1.67%   |
| Toshiba MQ01ABD075 752GB               | 2         | 1.67%   |
| Seagate ST500LT012-1DG142 500GB        | 2         | 1.67%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 2         | 1.67%   |
| HGST HTS721010A9E630 1TB               | 2         | 1.67%   |
| WDC WDS500G2B0A-00SM50 500GB SSD       | 1         | 0.83%   |
| WDC WDS120G1G0A-00SS50 120GB SSD       | 1         | 0.83%   |
| WDC WDS100T3X0C-00SJG0 1TB             | 1         | 0.83%   |
| WDC WD5000LPVX-60V0TT0 500GB           | 1         | 0.83%   |
| WDC WD5000LPCX-22VHAT1 500GB           | 1         | 0.83%   |
| WDC WD5000BPVT-00A1YT0 500GB           | 1         | 0.83%   |
| WDC WD2500BEVS-26UST0 250GB            | 1         | 0.83%   |
| WDC WD1200BEVS-08UST0 120GB            | 1         | 0.83%   |
| WDC WD10SPZX-24Z10T0 1TB               | 1         | 0.83%   |
| WDC WD10SPZX-24Z10 1TB                 | 1         | 0.83%   |
| WDC WD10JPVX-60JC3T1 1TB               | 1         | 0.83%   |
| WDC WD Blue SA510 2.5 500GB SSD        | 1         | 0.83%   |
| Unknown SR64G  64GB                    | 1         | 0.83%   |
| Unknown SM32G  32GB                    | 1         | 0.83%   |
| Unknown SL16G  16GB                    | 1         | 0.83%   |
| Unknown NCard  32GB                    | 1         | 0.83%   |
| Unknown MMC64G  64GB                   | 1         | 0.83%   |
| Unknown MMC Card  32GB                 | 1         | 0.83%   |
| Toshiba NVMe SSD Drive 512GB           | 1         | 0.83%   |
| Toshiba MQ02ABF100 1TB                 | 1         | 0.83%   |
| Toshiba MQ01ABF050 500GB               | 1         | 0.83%   |
| Toshiba MQ01ABD100M 1TB                | 1         | 0.83%   |
| Toshiba MQ01ABD050 500GB               | 1         | 0.83%   |
| Toshiba MQ01ABD032 320GB               | 1         | 0.83%   |
| Toshiba MK5075GSX 500GB                | 1         | 0.83%   |
| Toshiba MK2552GSX 250GB                | 1         | 0.83%   |
| Toshiba KBG30ZMV512G 512GB             | 1         | 0.83%   |
| SK hynix SKHynix_HFM256GD3HX015N 256GB | 1         | 0.83%   |
| SK hynix SC311 SATA 256GB SSD          | 1         | 0.83%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 12        | 13     | 27.91%  |
| Seagate | 11        | 13     | 25.58%  |
| Toshiba | 9         | 9      | 20.93%  |
| HGST    | 6         | 7      | 13.95%  |
| Hitachi | 3         | 3      | 6.98%   |
| Fujitsu | 1         | 1      | 2.33%   |
| Apple   | 1         | 1      | 2.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 4      | 23.53%  |
| WDC                 | 3         | 3      | 17.65%  |
| SanDisk             | 2         | 2      | 11.76%  |
| Crucial             | 2         | 2      | 11.76%  |
| SK hynix            | 1         | 1      | 5.88%   |
| Patriot             | 1         | 1      | 5.88%   |
| Kingston            | 1         | 1      | 5.88%   |
| KingSpec            | 1         | 2      | 5.88%   |
| JMicron Technology  | 1         | 1      | 5.88%   |
| China               | 1         | 1      | 5.88%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 45        | 54     | 41.28%  |
| HDD  | 43        | 47     | 39.45%  |
| SSD  | 15        | 18     | 13.76%  |
| MMC  | 6         | 10     | 5.5%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 56        | 64     | 51.85%  |
| NVMe | 44        | 53     | 40.74%  |
| MMC  | 6         | 10     | 5.56%   |
| SAS  | 2         | 2      | 1.85%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 35        | 40     | 61.4%   |
| 0.51-1.0   | 21        | 24     | 36.84%  |
| 1.01-2.0   | 1         | 1      | 1.75%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 33        | 33%     |
| 101-250    | 24        | 24%     |
| 21-50      | 10        | 10%     |
| 501-1000   | 10        | 10%     |
| 51-100     | 7         | 7%      |
| 1-20       | 6         | 6%      |
| 1001-2000  | 5         | 5%      |
| Unknown    | 4         | 4%      |
| 2001-3000  | 1         | 1%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 48        | 46.15%  |
| 21-50     | 24        | 23.08%  |
| 101-250   | 10        | 9.62%   |
| 51-100    | 8         | 7.69%   |
| 251-500   | 6         | 5.77%   |
| Unknown   | 4         | 3.85%   |
| 501-1000  | 3         | 2.88%   |
| 1001-2000 | 1         | 0.96%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD10JPVX-60JC3T1 1TB        | 1         | 1      | 50%     |
| WDC WD Blue SA510 2.5 500GB SSD | 1         | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 2         | 2      | 100%    |

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
| SSD  | 1         | 1      | 50%     |
| HDD  | 1         | 1      | 50%     |

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
| Detected | 64        | 84     | 62.75%  |
| Works    | 36        | 43     | 35.29%  |
| Malfunc  | 2         | 2      | 1.96%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 71        | 63.39%  |
| Samsung Electronics          | 14        | 12.5%   |
| SanDisk                      | 4         | 3.57%   |
| Micron/Crucial Technology    | 4         | 3.57%   |
| Micron Technology            | 4         | 3.57%   |
| SK hynix                     | 3         | 2.68%   |
| Kingston Technology Company  | 3         | 2.68%   |
| Toshiba America Info Systems | 2         | 1.79%   |
| Realtek Semiconductor        | 1         | 0.89%   |
| Phison Electronics           | 1         | 0.89%   |
| Lite-On Technology           | 1         | 0.89%   |
| KIOXIA                       | 1         | 0.89%   |
| Apple                        | 1         | 0.89%   |
| AMD                          | 1         | 0.89%   |
| ADATA Technology             | 1         | 0.89%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 12        | 10.08%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 9         | 7.56%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                            | 8         | 6.72%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 8         | 6.72%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 7         | 5.88%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 6         | 5.04%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 6         | 5.04%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 5         | 4.2%    |
| Samsung NVMe SSD Controller 980                                              | 4         | 3.36%   |
| Micron NVMe Storage Controller                                               | 4         | 3.36%   |
| Intel SSD 660P Series                                                        | 4         | 3.36%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                   | 3         | 2.52%   |
| Intel Volume Management Device NVMe RAID Controller                          | 3         | 2.52%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                               | 2         | 1.68%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                | 2         | 1.68%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                               | 2         | 1.68%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                         | 2         | 1.68%   |
| Micron/Crucial P2 NVMe PCIe SSD                                              | 2         | 1.68%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                      | 2         | 1.68%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                        | 2         | 1.68%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                             | 2         | 1.68%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                         | 1         | 0.84%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                         | 1         | 0.84%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                  | 1         | 0.84%   |
| SanDisk NVMe Controller                                                      | 1         | 0.84%   |
| Realtek NVMe Controller                                                      | 1         | 0.84%   |
| Phison E12 NVMe Controller                                                   | 1         | 0.84%   |
| Lite-On Non-Volatile memory controller                                       | 1         | 0.84%   |
| KIOXIA NVMe SSD Controller BG4                                               | 1         | 0.84%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                        | 1         | 0.84%   |
| Kingston Company OM3PDP3 NVMe SSD                                            | 1         | 0.84%   |
| Kingston Company A2000 NVMe SSD                                              | 1         | 0.84%   |
| Intel Comet Lake SATA AHCI Controller                                        | 1         | 0.84%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                            | 1         | 0.84%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 1         | 0.84%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                 | 1         | 0.84%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                | 1         | 0.84%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]               | 1         | 0.84%   |
| Intel 82801G (ICH7 Family) IDE Controller                                    | 1         | 0.84%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller               | 1         | 0.84%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 54        | 46.55%  |
| NVMe | 44        | 37.93%  |
| RAID | 15        | 12.93%  |
| IDE  | 3         | 2.59%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 91        | 91.92%  |
| AMD    | 8         | 8.08%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-4200U CPU @ 1.60GHz       | 5         | 5.05%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 4         | 4.04%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 4         | 4.04%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 3         | 3.03%   |
| Intel Core i7-5500U CPU @ 2.40GHz       | 3         | 3.03%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 3         | 3.03%   |
| Intel Core i9-10885H CPU @ 2.40GHz      | 2         | 2.02%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 2         | 2.02%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 2         | 2.02%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 2         | 2.02%   |
| Intel Core i5-2410M CPU @ 2.30GHz       | 2         | 2.02%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 2         | 2.02%   |
| Intel Core i3-4005U CPU @ 1.70GHz       | 2         | 2.02%   |
| Intel 12th Gen Core i7-12700H           | 2         | 2.02%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 2         | 2.02%   |
| AMD Ryzen 5 5500U with Radeon Graphics  | 2         | 2.02%   |
| AMD Custom APU 0405                     | 2         | 2.02%   |
| Intel Core m5-6Y54 CPU @ 1.10GHz        | 1         | 1.01%   |
| Intel Core i9-9980HK CPU @ 2.40GHz      | 1         | 1.01%   |
| Intel Core i9-8950HK CPU @ 2.90GHz      | 1         | 1.01%   |
| Intel Core i7-9850H CPU @ 2.60GHz       | 1         | 1.01%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 1         | 1.01%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 1         | 1.01%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 1         | 1.01%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 1         | 1.01%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 1         | 1.01%   |
| Intel Core i7-4600M CPU @ 2.90GHz       | 1         | 1.01%   |
| Intel Core i7-4510U CPU @ 2.00GHz       | 1         | 1.01%   |
| Intel Core i7-3632QM CPU @ 2.20GHz      | 1         | 1.01%   |
| Intel Core i7-2640M CPU @ 2.80GHz       | 1         | 1.01%   |
| Intel Core i7-2630QM CPU @ 2.00GHz      | 1         | 1.01%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 1         | 1.01%   |
| Intel Core i7-10710U CPU @ 1.10GHz      | 1         | 1.01%   |
| Intel Core i5-8300H CPU @ 2.30GHz       | 1         | 1.01%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 1         | 1.01%   |
| Intel Core i5-7300U CPU @ 2.60GHz       | 1         | 1.01%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 1         | 1.01%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 1         | 1.01%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 1         | 1.01%   |
| Intel Core i5-4300U CPU @ 1.90GHz       | 1         | 1.01%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 32        | 32.32%  |
| Intel Core i7    | 31        | 31.31%  |
| Other            | 10        | 10.1%   |
| Intel Core i3    | 7         | 7.07%   |
| Intel Core i9    | 4         | 4.04%   |
| Intel Core 2 Duo | 3         | 3.03%   |
| Intel Celeron    | 3         | 3.03%   |
| AMD Ryzen 5      | 3         | 3.03%   |
| Intel Core m5    | 1         | 1.01%   |
| Intel Celeron M  | 1         | 1.01%   |
| Intel Atom       | 1         | 1.01%   |
| AMD Ryzen 9      | 1         | 1.01%   |
| AMD Ryzen 7 PRO  | 1         | 1.01%   |
| AMD A6           | 1         | 1.01%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 49        | 49.49%  |
| 4      | 30        | 30.3%   |
| 6      | 10        | 10.1%   |
| 8      | 5         | 5.05%   |
| 14     | 3         | 3.03%   |
| 1      | 2         | 2.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 99        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 90        | 90.91%  |
| 1      | 9         | 9.09%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 98        | 98.99%  |
| 32-bit         | 1         | 1.01%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 18        | 18%     |
| 0x40651    | 7         | 7%      |
| 0x206a7    | 7         | 7%      |
| 0x906ea    | 6         | 6%      |
| 0x406e3    | 6         | 6%      |
| 0x306a9    | 6         | 6%      |
| 0x806ea    | 5         | 5%      |
| 0x806c1    | 5         | 5%      |
| 0x806ec    | 4         | 4%      |
| 0x806e9    | 4         | 4%      |
| 0xa0652    | 3         | 3%      |
| 0x20655    | 3         | 3%      |
| 0x906ed    | 2         | 2%      |
| 0x906e9    | 2         | 2%      |
| 0x906a3    | 2         | 2%      |
| 0x806eb    | 2         | 2%      |
| 0x6fd      | 2         | 2%      |
| 0x306d4    | 2         | 2%      |
| 0x706a1    | 1         | 1%      |
| 0x6fb      | 1         | 1%      |
| 0x6e8      | 1         | 1%      |
| 0x506e3    | 1         | 1%      |
| 0x406c4    | 1         | 1%      |
| 0x406c3    | 1         | 1%      |
| 0x306c3    | 1         | 1%      |
| 0x20652    | 1         | 1%      |
| 0x0a50000c | 1         | 1%      |
| 0x08608103 | 1         | 1%      |
| 0x08608102 | 1         | 1%      |
| 0x08600106 | 1         | 1%      |
| 0x08108109 | 1         | 1%      |
| 0x06001119 | 1         | 1%      |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 30        | 30.3%   |
| Haswell          | 11        | 11.11%  |
| SandyBridge      | 8         | 8.08%   |
| Skylake          | 7         | 7.07%   |
| IvyBridge        | 7         | 7.07%   |
| TigerLake        | 5         | 5.05%   |
| Broadwell        | 5         | 5.05%   |
| Unknown          | 5         | 5.05%   |
| Westmere         | 4         | 4.04%   |
| CometLake        | 4         | 4.04%   |
| Core             | 3         | 3.03%   |
| Silvermont       | 2         | 2.02%   |
| Alderlake Hybrid | 2         | 2.02%   |
| Zen+             | 1         | 1.01%   |
| Zen 3            | 1         | 1.01%   |
| Zen 2            | 1         | 1.01%   |
| Piledriver       | 1         | 1.01%   |
| P6               | 1         | 1.01%   |
| Goldmont plus    | 1         | 1.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 86        | 60.56%  |
| Nvidia | 37        | 26.06%  |
| AMD    | 19        | 13.38%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 10        | 6.99%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 7         | 4.9%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 7         | 4.9%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 7         | 4.9%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 7         | 4.9%    |
| Intel UHD Graphics 620                                                                   | 6         | 4.2%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 3.5%    |
| Intel HD Graphics 5500                                                                   | 5         | 3.5%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 2.8%    |
| Intel HD Graphics 620                                                                    | 4         | 2.8%    |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 3         | 2.1%    |
| Nvidia GM108M [GeForce MX130]                                                            | 3         | 2.1%    |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 2.1%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 2.1%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 2.1%    |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 3         | 2.1%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 3         | 2.1%    |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 1.4%    |
| Nvidia GP108BM [GeForce MX250]                                                           | 2         | 1.4%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 1.4%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 1.4%    |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 2         | 1.4%    |
| Intel HD Graphics 630                                                                    | 2         | 1.4%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.4%    |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 2         | 1.4%    |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 2         | 1.4%    |
| AMD Lucienne                                                                             | 2         | 1.4%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.7%    |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 1         | 0.7%    |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 1         | 0.7%    |
| Nvidia TU104M [GeForce RTX 2080 Mobile]                                                  | 1         | 0.7%    |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 0.7%    |
| Nvidia GT218M [GeForce 315M]                                                             | 1         | 0.7%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Max-Q]                                                | 1         | 0.7%    |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 0.7%    |
| Nvidia GM108M [GeForce 940M]                                                             | 1         | 0.7%    |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.7%    |
| Nvidia GM108M [GeForce 930M]                                                             | 1         | 0.7%    |
| Nvidia GM108M [GeForce 920MX]                                                            | 1         | 0.7%    |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 43        | 43.43%  |
| Intel + Nvidia | 33        | 33.33%  |
| Intel + AMD    | 10        | 10.1%   |
| 1 x AMD        | 9         | 9.09%   |
| 1 x Nvidia     | 4         | 4.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 83        | 83.84%  |
| Proprietary | 15        | 15.15%  |
| Unknown     | 1         | 1.01%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 57        | 57.58%  |
| 1.01-2.0   | 18        | 18.18%  |
| 3.01-4.0   | 11        | 11.11%  |
| 0.01-0.5   | 7         | 7.07%   |
| 0.51-1.0   | 4         | 4.04%   |
| 5.01-6.0   | 2         | 2.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 21        | 19.27%  |
| LG Display              | 19        | 17.43%  |
| BOE                     | 18        | 16.51%  |
| Chimei Innolux          | 13        | 11.93%  |
| Samsung Electronics     | 12        | 11.01%  |
| Goldstar                | 4         | 3.67%   |
| Sharp                   | 3         | 2.75%   |
| Dell                    | 3         | 2.75%   |
| LG Philips              | 2         | 1.83%   |
| InfoVision              | 2         | 1.83%   |
| Chi Mei Optoelectronics | 2         | 1.83%   |
| BenQ                    | 2         | 1.83%   |
| Valve                   | 1         | 0.92%   |
| Seiko/Epson             | 1         | 0.92%   |
| LGD                     | 1         | 0.92%   |
| Lenovo                  | 1         | 0.92%   |
| Hewlett-Packard         | 1         | 0.92%   |
| CSO                     | 1         | 0.92%   |
| Apple                   | 1         | 0.92%   |
| Analogix                | 1         | 0.92%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0575 1920x1080 309x174mm 14.0-inch          | 2         | 1.82%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 1.82%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 2         | 1.82%   |
| BOE LCD Monitor BOE06B3 1366x768 309x173mm 13.9-inch                  | 2         | 1.82%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                 | 2         | 1.82%   |
| AU Optronics LCD Monitor AUO272B 3840x2160 293x165mm 13.2-inch        | 2         | 1.82%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch        | 2         | 1.82%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch        | 2         | 1.82%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 1         | 0.91%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 1         | 0.91%   |
| Sharp LCD Monitor SHP14B9 3840x2160 344x194mm 15.5-inch               | 1         | 0.91%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch               | 1         | 0.91%   |
| Seiko/Epson LCD Monitor 1280x800                                      | 1         | 0.91%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 1         | 0.91%   |
| Samsung Electronics LCD Monitor SEC5741 1280x800 261x163mm 12.1-inch  | 1         | 0.91%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 0.91%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch  | 1         | 0.91%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch  | 1         | 0.91%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch  | 1         | 0.91%   |
| Samsung Electronics LCD Monitor SDC4341 1366x768 344x194mm 15.5-inch  | 1         | 0.91%   |
| Samsung Electronics LCD Monitor SDC424A 3200x1800 293x165mm 13.2-inch | 1         | 0.91%   |
| Samsung Electronics LCD Monitor SDC4157 3840x2160 344x194mm 15.5-inch | 1         | 0.91%   |
| Samsung Electronics LCD Monitor SAM0FEF 3840x2160 950x540mm 43.0-inch | 1         | 0.91%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch     | 1         | 0.91%   |
| Samsung Electronics C27R500 SAM0F9D 1920x1080 598x336mm 27.0-inch     | 1         | 0.91%   |
| LGD LCD Monitor 1366x768                                              | 1         | 0.91%   |
| LG Philips LP154WX4-TLC8 LPL0120 1280x800 331x207mm 15.4-inch         | 1         | 0.91%   |
| LG Philips LCD Monitor LPL2A00 1280x800 330x210mm 15.4-inch           | 1         | 0.91%   |
| LG Display LCD Monitor LGD065B 1920x1080 382x215mm 17.3-inch          | 1         | 0.91%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch          | 1         | 0.91%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 1         | 0.91%   |
| LG Display LCD Monitor LGD05D0 1920x1080 344x194mm 15.5-inch          | 1         | 0.91%   |
| LG Display LCD Monitor LGD0504 1366x768 344x194mm 15.5-inch           | 1         | 0.91%   |
| LG Display LCD Monitor LGD04FF 1920x1080 309x174mm 14.0-inch          | 1         | 0.91%   |
| LG Display LCD Monitor LGD04A4 1920x1080 309x174mm 14.0-inch          | 1         | 0.91%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch           | 1         | 0.91%   |
| LG Display LCD Monitor LGD03ED 1366x768 277x156mm 12.5-inch           | 1         | 0.91%   |
| LG Display LCD Monitor LGD03AB 1366x768 344x194mm 15.5-inch           | 1         | 0.91%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch           | 1         | 0.91%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch           | 1         | 0.91%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 47        | 44.34%  |
| 1366x768 (WXGA)   | 34        | 32.08%  |
| 3840x2160 (4K)    | 7         | 6.6%    |
| 1280x800 (WXGA)   | 4         | 3.77%   |
| 800x1280          | 2         | 1.89%   |
| 2560x1440 (QHD)   | 2         | 1.89%   |
| 1920x1200 (WUXGA) | 2         | 1.89%   |
| 1600x900 (HD+)    | 2         | 1.89%   |
| 3200x1800 (QHD+)  | 1         | 0.94%   |
| 2880x1920         | 1         | 0.94%   |
| 2560x1600         | 1         | 0.94%   |
| 2560x1080         | 1         | 0.94%   |
| 2304x1440         | 1         | 0.94%   |
| 1440x900 (WXGA+)  | 1         | 0.94%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 40        | 36.36%  |
| 14      | 23        | 20.91%  |
| 13      | 17        | 15.45%  |
| 27      | 5         | 4.55%   |
| 12      | 5         | 4.55%   |
| 21      | 3         | 2.73%   |
| 16      | 3         | 2.73%   |
| Unknown | 3         | 2.73%   |
| 24      | 2         | 1.82%   |
| 17      | 2         | 1.82%   |
| 11      | 2         | 1.82%   |
| 84      | 1         | 0.91%   |
| 34      | 1         | 0.91%   |
| 31      | 1         | 0.91%   |
| 23      | 1         | 0.91%   |
| 7       | 1         | 0.91%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 72        | 65.45%  |
| 201-300     | 16        | 14.55%  |
| 501-600     | 8         | 7.27%   |
| 351-400     | 4         | 3.64%   |
| 401-500     | 3         | 2.73%   |
| Unknown     | 3         | 2.73%   |
| 701-800     | 1         | 0.91%   |
| 601-700     | 1         | 0.91%   |
| 1501-2000   | 1         | 0.91%   |
| 1-100       | 1         | 0.91%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 88        | 87.13%  |
| 16/10   | 8         | 7.92%   |
| Unknown | 2         | 1.98%   |
| 21/9    | 1         | 0.99%   |
| 0.67    | 1         | 0.99%   |
| 0.62    | 1         | 0.99%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 41        | 37.27%  |
| 81-90          | 31        | 28.18%  |
| 71-80          | 9         | 8.18%   |
| 61-70          | 5         | 4.55%   |
| 301-350        | 5         | 4.55%   |
| 201-250        | 5         | 4.55%   |
| Unknown        | 3         | 2.73%   |
| 51-60          | 2         | 1.82%   |
| 351-500        | 2         | 1.82%   |
| 121-130        | 2         | 1.82%   |
| 111-120        | 2         | 1.82%   |
| More than 1000 | 1         | 0.91%   |
| 1-40           | 1         | 0.91%   |
| 251-300        | 1         | 0.91%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 46        | 42.59%  |
| 101-120       | 31        | 28.7%   |
| 51-100        | 13        | 12.04%  |
| 161-240       | 9         | 8.33%   |
| More than 240 | 6         | 5.56%   |
| Unknown       | 3         | 2.78%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 83        | 83.84%  |
| 2     | 15        | 15.15%  |
| 0     | 1         | 1.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 65        | 45.45%  |
| Realtek Semiconductor    | 47        | 32.87%  |
| Qualcomm Atheros         | 14        | 9.79%   |
| Broadcom                 | 7         | 4.9%    |
| Ralink                   | 4         | 2.8%    |
| TP-Link                  | 1         | 0.7%    |
| Ralink Technology        | 1         | 0.7%    |
| MediaTek                 | 1         | 0.7%    |
| Marvell Technology Group | 1         | 0.7%    |
| Lenovo                   | 1         | 0.7%    |
| Broadcom Limited         | 1         | 0.7%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 25        | 14.53%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 14        | 8.14%   |
| Intel Wireless 7260                                               | 6         | 3.49%   |
| Intel Wireless 8265 / 8275                                        | 5         | 2.91%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 5         | 2.91%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 2.91%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 2.33%   |
| Intel Wi-Fi 6 AX201                                               | 4         | 2.33%   |
| Intel Wi-Fi 6 AX200                                               | 4         | 2.33%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 4         | 2.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3         | 1.74%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 3         | 1.74%   |
| Intel Wireless 8260                                               | 3         | 1.74%   |
| Intel Wireless 7265                                               | 3         | 1.74%   |
| Intel Wireless 3165                                               | 3         | 1.74%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.74%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 1.74%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 3         | 1.74%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 1.74%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 1.16%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 1.16%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 1.16%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 1.16%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 1.16%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 1.16%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 1.16%   |
| Intel Wireless 3160                                               | 2         | 1.16%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 1.16%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 1.16%   |
| Intel Centrino Ultimate-N 6300                                    | 2         | 1.16%   |
| Intel Centrino Advanced-N 6235                                    | 2         | 1.16%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 1.16%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 2         | 1.16%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 2         | 1.16%   |
| TP-Link 802.11ac WLAN Adapter                                     | 1         | 0.58%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.58%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 1         | 0.58%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 0.58%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 0.58%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 62        | 61.39%  |
| Realtek Semiconductor | 15        | 14.85%  |
| Qualcomm Atheros      | 10        | 9.9%    |
| Broadcom              | 6         | 5.94%   |
| Ralink                | 4         | 3.96%   |
| TP-Link               | 1         | 0.99%   |
| Ralink Technology     | 1         | 0.99%   |
| MediaTek              | 1         | 0.99%   |
| Broadcom Limited      | 1         | 0.99%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                            | 6         | 5.94%   |
| Intel Wireless 8265 / 8275                                     | 5         | 4.95%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 5         | 4.95%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 4         | 3.96%   |
| Intel Wi-Fi 6 AX201                                            | 4         | 3.96%   |
| Intel Wi-Fi 6 AX200                                            | 4         | 3.96%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 4         | 3.96%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 3         | 2.97%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 3         | 2.97%   |
| Intel Wireless 8260                                            | 3         | 2.97%   |
| Intel Wireless 7265                                            | 3         | 2.97%   |
| Intel Wireless 3165                                            | 3         | 2.97%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 3         | 2.97%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2         | 1.98%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 2         | 1.98%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 2         | 1.98%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 2         | 1.98%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 1.98%   |
| Intel Wireless 3160                                            | 2         | 1.98%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 1.98%   |
| Intel Centrino Ultimate-N 6300                                 | 2         | 1.98%   |
| Intel Centrino Advanced-N 6235                                 | 2         | 1.98%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 2         | 1.98%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 2         | 1.98%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 2         | 1.98%   |
| TP-Link 802.11ac WLAN Adapter                                  | 1         | 0.99%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.99%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 1         | 0.99%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 0.99%   |
| Realtek 802.11n WLAN Adapter                                   | 1         | 0.99%   |
| Ralink MT7601U Wireless Adapter                                | 1         | 0.99%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.99%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 0.99%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 0.99%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 0.99%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 0.99%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 1         | 0.99%   |
| Intel Wireless-AC 9260                                         | 1         | 0.99%   |
| Intel WiFi Link 5100                                           | 1         | 0.99%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 1         | 0.99%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 42        | 60%     |
| Intel                    | 21        | 30%     |
| Qualcomm Atheros         | 4         | 5.71%   |
| Marvell Technology Group | 1         | 1.43%   |
| Lenovo                   | 1         | 1.43%   |
| Broadcom                 | 1         | 1.43%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 25        | 35.21%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 14        | 19.72%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 7.04%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 4.23%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 4.23%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 4.23%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 2.82%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 2.82%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 2.82%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.41%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.41%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.41%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.41%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 1.41%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 1.41%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.41%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.41%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.41%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 1.41%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 1.41%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 97        | 58.08%  |
| Ethernet | 70        | 41.92%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 86        | 86.87%  |
| Ethernet | 13        | 13.13%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 68        | 68.69%  |
| 1     | 30        | 30.3%   |
| 0     | 1         | 1.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 82        | 82.83%  |
| Yes  | 17        | 17.17%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 47        | 58.75%  |
| Realtek Semiconductor           | 8         | 10%     |
| Qualcomm Atheros Communications | 6         | 7.5%    |
| Broadcom                        | 4         | 5%      |
| Ralink                          | 3         | 3.75%   |
| Foxconn / Hon Hai               | 3         | 3.75%   |
| Toshiba                         | 2         | 2.5%    |
| IMC Networks                    | 2         | 2.5%    |
| Hewlett-Packard                 | 2         | 2.5%    |
| Dell                            | 2         | 2.5%    |
| MediaTek                        | 1         | 1.25%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface               | 17        | 21.25%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)   | 12        | 15%     |
| Intel AX201 Bluetooth                            | 7         | 8.75%   |
| Realtek Bluetooth Radio                          | 5         | 6.25%   |
| Intel AX200 Bluetooth                            | 4         | 5%      |
| Ralink RT3290 Bluetooth                          | 3         | 3.75%   |
| Intel Centrino Bluetooth Wireless Transceiver    | 3         | 3.75%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter          | 2         | 2.5%    |
| Qualcomm Atheros  Bluetooth Device               | 2         | 2.5%    |
| Intel Bluetooth Device                           | 2         | 2.5%    |
| IMC Networks Bluetooth Radio                     | 2         | 2.5%    |
| HP Broadcom 2070 Bluetooth Combo                 | 2         | 2.5%    |
| Foxconn / Hon Hai Bluetooth Device               | 2         | 2.5%    |
| Toshiba RT Bluetooth Radio                       | 1         | 1.25%   |
| Toshiba Integrated Bluetooth HCI                 | 1         | 1.25%   |
| Realtek RTL8821A Bluetooth                       | 1         | 1.25%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0           | 1         | 1.25%   |
| Qualcomm Atheros Bluetooth USB Host Controller   | 1         | 1.25%   |
| Qualcomm Atheros AR9462 Bluetooth                | 1         | 1.25%   |
| Qualcomm Atheros AR3011 Bluetooth                | 1         | 1.25%   |
| MediaTek Wireless_Device                         | 1         | 1.25%   |
| Intel Wireless-AC 9260 Bluetooth Adapter         | 1         | 1.25%   |
| Intel AX210 Bluetooth                            | 1         | 1.25%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller  | 1         | 1.25%   |
| Dell DW375 Bluetooth Module                      | 1         | 1.25%   |
| Dell BCM20702A0 Bluetooth Module                 | 1         | 1.25%   |
| Broadcom HP Portable SoftSailing                 | 1         | 1.25%   |
| Broadcom BCM43142A0 Bluetooth 4.0                | 1         | 1.25%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]       | 1         | 1.25%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller] | 1         | 1.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 91        | 76.47%  |
| Nvidia                | 17        | 14.29%  |
| AMD                   | 8         | 6.72%   |
| Realtek Semiconductor | 1         | 0.84%   |
| Logitech              | 1         | 0.84%   |
| Lenovo                | 1         | 0.84%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 16        | 11.35%  |
| Intel Haswell-ULT HD Audio Controller                                                             | 10        | 7.09%   |
| Intel 8 Series HD Audio Controller                                                                | 10        | 7.09%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 9         | 6.38%   |
| Intel Cannon Lake PCH cAVS                                                                        | 8         | 5.67%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 7         | 4.96%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 6         | 4.26%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 5         | 3.55%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 5         | 3.55%   |
| Intel Broadwell-U Audio Controller                                                                | 5         | 3.55%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 5         | 3.55%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 2.84%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 2.84%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 2.84%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 2.13%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 2.13%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 3         | 2.13%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 2.13%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 3         | 2.13%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 1.42%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 1.42%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 1.42%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 1.42%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 2         | 1.42%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.71%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.71%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.71%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 0.71%   |
| Nvidia Audio device                                                                               | 1         | 0.71%   |
| Logitech H390 headset with microphone                                                             | 1         | 0.71%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                                      | 1         | 0.71%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 0.71%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 0.71%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 0.71%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series Low Power Engine Audio           | 1         | 0.71%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.71%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 0.71%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 0.71%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 0.71%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 0.71%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 17        | 30.91%  |
| SK hynix            | 12        | 21.82%  |
| Micron Technology   | 8         | 14.55%  |
| Crucial             | 6         | 10.91%  |
| Kingston            | 4         | 7.27%   |
| Unknown             | 3         | 5.45%   |
| Ramaxel Technology  | 3         | 5.45%   |
| Wilk                | 1         | 1.82%   |
| Timetec             | 1         | 1.82%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s          | 2         | 3.45%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s           | 2         | 3.45%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s       | 2         | 3.45%   |
| Micron RAM MTC8C1084S1SC48BA1 16GB SODIMM 4800MT/s              | 2         | 3.45%   |
| Crucial RAM CT16G4SFRA32A.M16FR 16GB SODIMM DDR4 3200MT/s       | 2         | 3.45%   |
| Wilk RAM W-HK32S32O 32GB SODIMM DDR4 3200MT/s                   | 1         | 1.72%   |
| Unknown RAM Module 4GB Chip DDR4 2133MT/s                       | 1         | 1.72%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2667MT/s                  | 1         | 1.72%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                      | 1         | 1.72%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                      | 1         | 1.72%   |
| Timetec RAM SD3-1600 8GB SODIMM DDR3 1600MT/s                   | 1         | 1.72%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                    | 1         | 1.72%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 1.72%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s          | 1         | 1.72%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s          | 1         | 1.72%   |
| SK hynix RAM HMT125S6TFR8C-G7 2GB SODIMM DDR3 1067MT/s          | 1         | 1.72%   |
| SK hynix RAM HMAA51S6AMR6N-UH 8GB SODIMM DDR4 2400MT/s          | 1         | 1.72%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s         | 1         | 1.72%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s          | 1         | 1.72%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s         | 1         | 1.72%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s         | 1         | 1.72%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s          | 1         | 1.72%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s          | 1         | 1.72%   |
| SK hynix RAM H5ANAG6NCMR-XNC 8GB Row Of Chips DDR4 3200MT/s     | 1         | 1.72%   |
| Samsung RAM Module 32GB SODIMM DDR4 3200MT/s                    | 1         | 1.72%   |
| Samsung RAM M471B5673EH1-CH9 2048MB SODIMM DDR3 1334MT/s        | 1         | 1.72%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s           | 1         | 1.72%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s           | 1         | 1.72%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s           | 1         | 1.72%   |
| Samsung RAM M471A5143DB0-CPB 4GB SODIMM DDR4 2133MT/s           | 1         | 1.72%   |
| Samsung RAM M471A1K44BM0-CRC 8GB SODIMM DDR4 2400MT/s           | 1         | 1.72%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s           | 1         | 1.72%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s           | 1         | 1.72%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s           | 1         | 1.72%   |
| Samsung RAM M425R2GA3BB0-CQKOD 16GB SODIMM DDR5 4800MT/s        | 1         | 1.72%   |
| Samsung RAM K4EBE304EC-EGCG 8GB Row Of Chips LPDDR3 2133MT/s    | 1         | 1.72%   |
| Samsung RAM K4E6E304EB-EGCF 4GB Row Of Chips LPDDR3 1867MT/s    | 1         | 1.72%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB Row Of Chips DDR4 2400MT/s | 1         | 1.72%   |
| Micron RAM Module 8192MB SODIMM DDR4 3200MT/s                   | 1         | 1.72%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s            | 1         | 1.72%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 31        | 67.39%  |
| DDR3   | 9         | 19.57%  |
| LPDDR3 | 2         | 4.35%   |
| DDR5   | 2         | 4.35%   |
| LPDDR4 | 1         | 2.17%   |
| DDR2   | 1         | 2.17%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 42        | 87.5%   |
| Row Of Chips | 5         | 10.42%  |
| Chip         | 1         | 2.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 20        | 38.46%  |
| 16384 | 13        | 25%     |
| 4096  | 10        | 19.23%  |
| 32768 | 4         | 7.69%   |
| 2048  | 4         | 7.69%   |
| 1024  | 1         | 1.92%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 16        | 32%     |
| 3200  | 12        | 24%     |
| 1600  | 6         | 12%     |
| 2400  | 4         | 8%      |
| 2133  | 4         | 8%      |
| 4800  | 2         | 4%      |
| 1334  | 2         | 4%      |
| 4267  | 1         | 2%      |
| 1867  | 1         | 2%      |
| 1067  | 1         | 2%      |
| 667   | 1         | 2%      |

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
| Chicony Electronics                    | 26        | 28.57%  |
| IMC Networks                           | 10        | 10.99%  |
| Acer                                   | 9         | 9.89%   |
| Microdia                               | 8         | 8.79%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 7.69%   |
| Sunplus Innovation Technology          | 5         | 5.49%   |
| Realtek Semiconductor                  | 5         | 5.49%   |
| Syntek                                 | 3         | 3.3%    |
| Ricoh                                  | 3         | 3.3%    |
| Luxvisions Innotech Limited            | 3         | 3.3%    |
| Suyin                                  | 2         | 2.2%    |
| Quanta                                 | 2         | 2.2%    |
| Apple                                  | 2         | 2.2%    |
| Ruision                                | 1         | 1.1%    |
| Microsoft                              | 1         | 1.1%    |
| Logitech                               | 1         | 1.1%    |
| Lite-On Technology                     | 1         | 1.1%    |
| Lenovo                                 | 1         | 1.1%    |
| Alcor Micro                            | 1         | 1.1%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 9         | 9.89%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 5         | 5.49%   |
| Microdia Integrated_Webcam_HD                                   | 4         | 4.4%    |
| Syntek Integrated Camera                                        | 3         | 3.3%    |
| Chicony Integrated Camera (1280x720@30)                         | 3         | 3.3%    |
| Sunplus HP HD Webcam [Fixed]                                    | 2         | 2.2%    |
| Ricoh HD Webcam                                                 | 2         | 2.2%    |
| Realtek Integrated_Webcam_HD                                    | 2         | 2.2%    |
| Quanta HP TrueVision HD Camera                                  | 2         | 2.2%    |
| Microdia Laptop_Integrated_Webcam_HD                            | 2         | 2.2%    |
| IMC Networks Integrated Camera                                  | 2         | 2.2%    |
| Chicony Lenovo EasyCamera                                       | 2         | 2.2%    |
| Chicony HP Truevision HD                                        | 2         | 2.2%    |
| Chicony HP HD Webcam [Fixed]                                    | 2         | 2.2%    |
| Chicony EasyCamera                                              | 2         | 2.2%    |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 2         | 2.2%    |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam             | 2         | 2.2%    |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                 | 2         | 2.2%    |
| Acer BisonCam,NB Pro                                            | 2         | 2.2%    |
| Suyin HP TrueVision HD                                          | 1         | 1.1%    |
| Suyin 1.3M HD WebCam                                            | 1         | 1.1%    |
| Sunplus Integrated_Webcam_HD                                    | 1         | 1.1%    |
| Sunplus Integrated_Webcam_FHD                                   | 1         | 1.1%    |
| Sunplus Integrated Webcam                                       | 1         | 1.1%    |
| Ruision UVC Camera                                              | 1         | 1.1%    |
| Ricoh Sony Vaio Integrated Webcam                               | 1         | 1.1%    |
| Realtek Lenovo EasyCamera                                       | 1         | 1.1%    |
| Realtek Integrated Webcam                                       | 1         | 1.1%    |
| Realtek HP Truevision HD                                        | 1         | 1.1%    |
| Microsoft LifeCam HD-3000                                       | 1         | 1.1%    |
| Microdia Integrated Webcam                                      | 1         | 1.1%    |
| Microdia Dell Integrated HD Webcam                              | 1         | 1.1%    |
| Luxvisions Innotech Limited HP Wide Vision HD Camera            | 1         | 1.1%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera             | 1         | 1.1%    |
| Luxvisions Innotech Limited HP HD Camera                        | 1         | 1.1%    |
| Logitech Webcam C270                                            | 1         | 1.1%    |
| Lite-On HP HD Camera                                            | 1         | 1.1%    |
| Lenovo Integrated Webcam                                        | 1         | 1.1%    |
| IMC Networks USB2.0 VGA UVC WebCam                              | 1         | 1.1%    |
| IMC Networks USB2.0 UVC HD Webcam                               | 1         | 1.1%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 12        | 42.86%  |
| Synaptics                  | 12        | 42.86%  |
| Elan Microelectronics      | 2         | 7.14%   |
| STMicroelectronics         | 1         | 3.57%   |
| Shenzhen Goodix Technology | 1         | 3.57%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS471 Fingerprint Reader                 | 3         | 10.71%  |
| Synaptics UWP WBDI                                         | 3         | 10.71%  |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 3         | 10.71%  |
| Validity Sensors VFS491                                    | 2         | 7.14%   |
| Validity Sensors Synaptics WBDI                            | 2         | 7.14%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 2         | 7.14%   |
| Elan ELAN:ARM-M4                                           | 2         | 7.14%   |
| Validity Sensors VFS5011 Fingerprint Reader                | 1         | 3.57%   |
| Validity Sensors VFS495 Fingerprint Reader                 | 1         | 3.57%   |
| Validity Sensors VFS Fingerprint sensor                    | 1         | 3.57%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 1         | 3.57%   |
| Validity Sensors Fingerprint scanner                       | 1         | 3.57%   |
| Synaptics WBDI Fingerprint Reader USB 086                  | 1         | 3.57%   |
| Synaptics UWP WBDI Device                                  | 1         | 3.57%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 3.57%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 1         | 3.57%   |
| STMicroelectronics Fingerprint Reader                      | 1         | 3.57%   |
| Shenzhen Goodix Fingerprint Reader                         | 1         | 3.57%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 3         | 42.86%  |
| Alcor Micro | 3         | 42.86%  |
| Upek        | 1         | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
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

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 51        | 51%     |
| 1     | 38        | 38%     |
| 2     | 10        | 10%     |
| 3     | 1         | 1%      |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 28        | 47.46%  |
| Graphics card            | 10        | 16.95%  |
| Chipcard                 | 7         | 11.86%  |
| Net/wireless             | 5         | 8.47%   |
| Camera                   | 3         | 5.08%   |
| Bluetooth                | 3         | 5.08%   |
| Sound                    | 1         | 1.69%   |
| Multimedia controller    | 1         | 1.69%   |
| Communication controller | 1         | 1.69%   |

