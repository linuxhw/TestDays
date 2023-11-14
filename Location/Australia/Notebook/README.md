Linux in Australia - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Australia.

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

Total: 2479

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | Pavilion Gaming Laptop 1... | [231b5b8ef8](https://linux-hardware.org/?probe=231b5b8ef8) | Nov 06, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | [b88b3757af](https://linux-hardware.org/?probe=b88b3757af) | Nov 06, 2023 |
| Lenovo        | ThinkPad T480 20L6S5VP3U    | [ea70f0e597](https://linux-hardware.org/?probe=ea70f0e597) | Nov 05, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [f1d00fbb93](https://linux-hardware.org/?probe=f1d00fbb93) | Nov 05, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [50306c96e2](https://linux-hardware.org/?probe=50306c96e2) | Nov 05, 2023 |
| Sony          | SVE15137CGW                 | [5d2a4746af](https://linux-hardware.org/?probe=5d2a4746af) | Nov 04, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D3S... | [6a2591b5e9](https://linux-hardware.org/?probe=6a2591b5e9) | Nov 03, 2023 |
| HP            | ZBook Power G7 Mobile Wo... | [044aa1f9b5](https://linux-hardware.org/?probe=044aa1f9b5) | Nov 03, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [75a224b797](https://linux-hardware.org/?probe=75a224b797) | Nov 02, 2023 |
| Valve         | Jupiter                     | [b5bd58d350](https://linux-hardware.org/?probe=b5bd58d350) | Oct 31, 2023 |
| MSI           | Creator 15 A11UE            | [e8b0c2a2b5](https://linux-hardware.org/?probe=e8b0c2a2b5) | Oct 31, 2023 |
| HP            | EliteBook 820 G3            | [e131dccf11](https://linux-hardware.org/?probe=e131dccf11) | Oct 31, 2023 |
| Lenovo        | ThinkPad T490 20N2S0QE00    | [9785ae64c0](https://linux-hardware.org/?probe=9785ae64c0) | Oct 31, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D3S... | [8730c3de9d](https://linux-hardware.org/?probe=8730c3de9d) | Oct 30, 2023 |
| Valve         | Jupiter                     | [e73e0881d6](https://linux-hardware.org/?probe=e73e0881d6) | Oct 30, 2023 |
| Dell          | Latitude 5530               | [1731342e23](https://linux-hardware.org/?probe=1731342e23) | Oct 30, 2023 |
| Dell          | XPS 15 9510                 | [ab707308db](https://linux-hardware.org/?probe=ab707308db) | Oct 30, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | [649b911963](https://linux-hardware.org/?probe=649b911963) | Oct 29, 2023 |
| Samsung       | 905S3G/906S3G/915S3G/930... | [bc2ed6322b](https://linux-hardware.org/?probe=bc2ed6322b) | Oct 29, 2023 |
| Google        | Taniks                      | [c864f19e03](https://linux-hardware.org/?probe=c864f19e03) | Oct 28, 2023 |
| Apple         | MacBookAir6,2               | [96b76fc377](https://linux-hardware.org/?probe=96b76fc377) | Oct 28, 2023 |
| Dell          | Latitude 5430               | [af33081c9b](https://linux-hardware.org/?probe=af33081c9b) | Oct 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | [3bc6d6cfda](https://linux-hardware.org/?probe=3bc6d6cfda) | Oct 27, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [755d25d933](https://linux-hardware.org/?probe=755d25d933) | Oct 26, 2023 |
| HP            | EliteBook Folio 9470m       | [765f6f8003](https://linux-hardware.org/?probe=765f6f8003) | Oct 25, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [d69762902a](https://linux-hardware.org/?probe=d69762902a) | Oct 25, 2023 |
| Lenovo        | V110-15IAP 80TG             | [455780b267](https://linux-hardware.org/?probe=455780b267) | Oct 25, 2023 |
| Acer          | Aspire V3-572               | [f873d7efd9](https://linux-hardware.org/?probe=f873d7efd9) | Oct 24, 2023 |
| ASUSTek       | X541UJ                      | [833d4435d4](https://linux-hardware.org/?probe=833d4435d4) | Oct 24, 2023 |
| MSI           | GP62M 7REX                  | [5fbee8e341](https://linux-hardware.org/?probe=5fbee8e341) | Oct 24, 2023 |
| MSI           | GP62M 7REX                  | [a95ab8b563](https://linux-hardware.org/?probe=a95ab8b563) | Oct 24, 2023 |
| Apple         | MacBookAir6,2               | [f15ecd1759](https://linux-hardware.org/?probe=f15ecd1759) | Oct 24, 2023 |
| Acer          | Aspire V3-572               | [974d64f7a8](https://linux-hardware.org/?probe=974d64f7a8) | Oct 23, 2023 |
| Dell          | Latitude 5430               | [8d552380c4](https://linux-hardware.org/?probe=8d552380c4) | Oct 23, 2023 |
| Apple         | MacBookPro9,2               | [dac0aa7f70](https://linux-hardware.org/?probe=dac0aa7f70) | Oct 22, 2023 |
| Acer          | Nitro AN515-45              | [310d794691](https://linux-hardware.org/?probe=310d794691) | Oct 22, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | [92d3be3fff](https://linux-hardware.org/?probe=92d3be3fff) | Oct 22, 2023 |
| HP            | ProBook 4340s               | [8746af78f7](https://linux-hardware.org/?probe=8746af78f7) | Oct 22, 2023 |
| HP            | Pavilion g6                 | [2fc9736b9e](https://linux-hardware.org/?probe=2fc9736b9e) | Oct 22, 2023 |
| HP            | Pavilion g6                 | [7514db3c84](https://linux-hardware.org/?probe=7514db3c84) | Oct 22, 2023 |
| HP            | EliteBook Folio 9470m       | [f342373f65](https://linux-hardware.org/?probe=f342373f65) | Oct 20, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [09ad44bf2e](https://linux-hardware.org/?probe=09ad44bf2e) | Oct 19, 2023 |
| Dell          | XPS 13 9360                 | [dbbedd9f06](https://linux-hardware.org/?probe=dbbedd9f06) | Oct 18, 2023 |
| Apple         | MacBookPro11,1              | [ffeb95bd95](https://linux-hardware.org/?probe=ffeb95bd95) | Oct 17, 2023 |
| Lenovo        | ThinkPad E460 20ETA05KAU    | [cf477f62d0](https://linux-hardware.org/?probe=cf477f62d0) | Oct 15, 2023 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | [feaf25f8e8](https://linux-hardware.org/?probe=feaf25f8e8) | Oct 15, 2023 |
| Acer          | Aspire E1-531               | [4e585c2b99](https://linux-hardware.org/?probe=4e585c2b99) | Oct 15, 2023 |
| HUAWEI        | KLVD-WXX9                   | [9d77b16e0b](https://linux-hardware.org/?probe=9d77b16e0b) | Oct 14, 2023 |
| HP            | Laptop 15s-du4xxx           | [8bec0ea3db](https://linux-hardware.org/?probe=8bec0ea3db) | Oct 14, 2023 |
| Fujitsu       | LIFEBOOK T5010              | [f35263745a](https://linux-hardware.org/?probe=f35263745a) | Oct 14, 2023 |
| HP            | Notebook                    | [221bc048b5](https://linux-hardware.org/?probe=221bc048b5) | Oct 13, 2023 |
| Apple         | MacBookPro11,4              | [107524e9ec](https://linux-hardware.org/?probe=107524e9ec) | Oct 12, 2023 |
| Apple         | MacBookPro11,4              | [f9fee05f72](https://linux-hardware.org/?probe=f9fee05f72) | Oct 12, 2023 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | [e6c5f903ce](https://linux-hardware.org/?probe=e6c5f903ce) | Oct 12, 2023 |
| Lenovo        | ThinkPad T410 2522PT3       | [3d389cfbfa](https://linux-hardware.org/?probe=3d389cfbfa) | Oct 11, 2023 |
| ASUSTek       | K42F                        | [0d099eb4f7](https://linux-hardware.org/?probe=0d099eb4f7) | Oct 10, 2023 |
| Acer          | Aspire A114-33              | [53a1dce896](https://linux-hardware.org/?probe=53a1dce896) | Oct 09, 2023 |
| HP            | EliteBook Folio 9470m       | [9cecfe7ba5](https://linux-hardware.org/?probe=9cecfe7ba5) | Oct 09, 2023 |
| Acer          | Nitro AN515-56              | [6a98464415](https://linux-hardware.org/?probe=6a98464415) | Oct 07, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [d8d241531e](https://linux-hardware.org/?probe=d8d241531e) | Oct 07, 2023 |
| HP            | EliteBook 8460p             | [9b6cb6738d](https://linux-hardware.org/?probe=9b6cb6738d) | Oct 06, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [226b534a32](https://linux-hardware.org/?probe=226b534a32) | Oct 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [dfec5c18d5](https://linux-hardware.org/?probe=dfec5c18d5) | Oct 04, 2023 |
| MSI           | PR600                       | [09fe9eb818](https://linux-hardware.org/?probe=09fe9eb818) | Oct 04, 2023 |
| Dell          | Latitude E7440              | [3cb4fc2857](https://linux-hardware.org/?probe=3cb4fc2857) | Oct 03, 2023 |
| Apple         | MacBookAir7,2               | [efcc70945c](https://linux-hardware.org/?probe=efcc70945c) | Oct 03, 2023 |
| Apple         | MacBookPro16,2              | [66ee93331d](https://linux-hardware.org/?probe=66ee93331d) | Oct 02, 2023 |
| Apple         | MacBook8,1                  | [a7374560fe](https://linux-hardware.org/?probe=a7374560fe) | Oct 02, 2023 |
| Apple         | MacBookPro8,1               | [5488654867](https://linux-hardware.org/?probe=5488654867) | Oct 02, 2023 |
| Apple         | MacBook8,1                  | [2f046de8e8](https://linux-hardware.org/?probe=2f046de8e8) | Oct 02, 2023 |
| Apple         | MacBookPro14,3              | [e26d66c131](https://linux-hardware.org/?probe=e26d66c131) | Oct 01, 2023 |
| Apple         | MacBookPro14,3              | [21f405ccbe](https://linux-hardware.org/?probe=21f405ccbe) | Oct 01, 2023 |
| Toshiba       | Satellite P750              | [6edbfaa1b1](https://linux-hardware.org/?probe=6edbfaa1b1) | Oct 01, 2023 |
| Apple         | MacBookPro14,3              | [ec90ed2076](https://linux-hardware.org/?probe=ec90ed2076) | Oct 01, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [c99f28b27d](https://linux-hardware.org/?probe=c99f28b27d) | Oct 01, 2023 |
| Metabox       | Prime-X X170KM              | [8ab33a8bd3](https://linux-hardware.org/?probe=8ab33a8bd3) | Sep 30, 2023 |
| Apple         | MacBookAir7,2               | [c25eeffab1](https://linux-hardware.org/?probe=c25eeffab1) | Sep 28, 2023 |
| ASUSTek       | X550CC                      | [001231c730](https://linux-hardware.org/?probe=001231c730) | Sep 28, 2023 |
| Apple         | MacBookAir6,2               | [b0c2b630a6](https://linux-hardware.org/?probe=b0c2b630a6) | Sep 28, 2023 |
| Apple         | MacBookPro15,2              | [1331a57778](https://linux-hardware.org/?probe=1331a57778) | Sep 27, 2023 |
| Lenovo        | ThinkPad T410 2522PT3       | [fed9f17a22](https://linux-hardware.org/?probe=fed9f17a22) | Sep 27, 2023 |
| Lenovo        | ThinkPad T410 2522PT3       | [0dd1b47aa0](https://linux-hardware.org/?probe=0dd1b47aa0) | Sep 27, 2023 |
| HP            | EliteBook Folio 9470m       | [78d31814cf](https://linux-hardware.org/?probe=78d31814cf) | Sep 26, 2023 |
| HP            | EliteBook Folio 9470m       | [0d7d5f0613](https://linux-hardware.org/?probe=0d7d5f0613) | Sep 26, 2023 |
| Apple         | MacBookAir5,2               | [55dec782e7](https://linux-hardware.org/?probe=55dec782e7) | Sep 25, 2023 |
| Acer          | Aspire E5-571               | [c834abf6b2](https://linux-hardware.org/?probe=c834abf6b2) | Sep 25, 2023 |
| Acer          | Aspire R3-131T              | [bf8f7a55ae](https://linux-hardware.org/?probe=bf8f7a55ae) | Sep 24, 2023 |
| Acer          | Aspire R3-131T              | [a426f4a94e](https://linux-hardware.org/?probe=a426f4a94e) | Sep 24, 2023 |
| Dell          | Inspiron 14 5420            | [ade3d11822](https://linux-hardware.org/?probe=ade3d11822) | Sep 24, 2023 |
| COM1          | NBINF-X5-9G5                | [919d36ddd8](https://linux-hardware.org/?probe=919d36ddd8) | Sep 24, 2023 |
| HP            | EliteBook Folio 9470m       | [086b0dc21a](https://linux-hardware.org/?probe=086b0dc21a) | Sep 23, 2023 |
| Panasonic     | FZG1-4                      | [bb4677655e](https://linux-hardware.org/?probe=bb4677655e) | Sep 23, 2023 |
| Apple         | MacBookPro14,1              | [8b1188ba33](https://linux-hardware.org/?probe=8b1188ba33) | Sep 22, 2023 |
| Dell          | Precision 5680              | [55deb46665](https://linux-hardware.org/?probe=55deb46665) | Sep 21, 2023 |
| HP            | Pavilion dv7                | [a879a0a88f](https://linux-hardware.org/?probe=a879a0a88f) | Sep 21, 2023 |
| Apple         | MacBookPro8,1               | [c5e9108ee7](https://linux-hardware.org/?probe=c5e9108ee7) | Sep 20, 2023 |
| Dell          | Precision 5560              | [456e9e2c78](https://linux-hardware.org/?probe=456e9e2c78) | Sep 20, 2023 |
| Dell          | Precision 5680              | [a75a75f080](https://linux-hardware.org/?probe=a75a75f080) | Sep 20, 2023 |
| HP            | EliteBook 8460p             | [7a6c8c1d0a](https://linux-hardware.org/?probe=7a6c8c1d0a) | Sep 20, 2023 |
| HP            | EliteBook 8460p             | [6f7974b0f0](https://linux-hardware.org/?probe=6f7974b0f0) | Sep 20, 2023 |
| HP            | EliteBook Folio 9470m       | [5e50efa2c4](https://linux-hardware.org/?probe=5e50efa2c4) | Sep 19, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [eeeb11e211](https://linux-hardware.org/?probe=eeeb11e211) | Sep 19, 2023 |
| Sony          | SVE15137CGW                 | [b454be55a2](https://linux-hardware.org/?probe=b454be55a2) | Sep 19, 2023 |
| Framework     | Laptop                      | [f379873c4b](https://linux-hardware.org/?probe=f379873c4b) | Sep 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [82e9cc2c9a](https://linux-hardware.org/?probe=82e9cc2c9a) | Sep 18, 2023 |
| HP            | EliteBook 745 G2            | [7e5ee5a990](https://linux-hardware.org/?probe=7e5ee5a990) | Sep 18, 2023 |
| Dell          | Latitude 7490               | [91a3ecf449](https://linux-hardware.org/?probe=91a3ecf449) | Sep 18, 2023 |
| Apple         | MacBookPro16,2              | [42bb973998](https://linux-hardware.org/?probe=42bb973998) | Sep 16, 2023 |
| Apple         | MacBookPro16,2              | [d5c797d43b](https://linux-hardware.org/?probe=d5c797d43b) | Sep 16, 2023 |
| Dell          | Inspiron M5010              | [c78ab23cc7](https://linux-hardware.org/?probe=c78ab23cc7) | Sep 16, 2023 |
| COM1          | NBINF-X5-9G5                | [aca0ed1105](https://linux-hardware.org/?probe=aca0ed1105) | Sep 15, 2023 |
| Dell          | XPS L322X                   | [77135f7967](https://linux-hardware.org/?probe=77135f7967) | Sep 11, 2023 |
| Dell          | Inspiron M5010              | [70147b0015](https://linux-hardware.org/?probe=70147b0015) | Sep 11, 2023 |
| Dell          | XPS L322X                   | [fdf4ba47e1](https://linux-hardware.org/?probe=fdf4ba47e1) | Sep 11, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [fac3b5ba62](https://linux-hardware.org/?probe=fac3b5ba62) | Sep 08, 2023 |
| Lenovo        | ThinkPad T410 2522PT3       | [da7303433d](https://linux-hardware.org/?probe=da7303433d) | Sep 07, 2023 |
| Valve         | Jupiter                     | [d4ca58e970](https://linux-hardware.org/?probe=d4ca58e970) | Sep 07, 2023 |
| Apple         | MacBookPro9,2               | [424ab4dc3d](https://linux-hardware.org/?probe=424ab4dc3d) | Sep 05, 2023 |
| Dell          | Latitude 7280               | [3cf6ec76b5](https://linux-hardware.org/?probe=3cf6ec76b5) | Sep 05, 2023 |
| HP            | EliteBook 840 G1            | [318d03cfad](https://linux-hardware.org/?probe=318d03cfad) | Sep 04, 2023 |
| Apple         | MacBookPro16,2              | [ae41ba8b62](https://linux-hardware.org/?probe=ae41ba8b62) | Sep 04, 2023 |
| Apple         | MacBookPro8,1               | [6cbaac077e](https://linux-hardware.org/?probe=6cbaac077e) | Sep 03, 2023 |
| Dell          | Latitude E6520              | [b53cd78958](https://linux-hardware.org/?probe=b53cd78958) | Sep 02, 2023 |
| Dell          | G15 5520                    | [796ae7cf79](https://linux-hardware.org/?probe=796ae7cf79) | Sep 02, 2023 |
| Apple         | MacBookAir6,2               | [da8d60051c](https://linux-hardware.org/?probe=da8d60051c) | Sep 02, 2023 |
| ASUSTek       | K53SD                       | [9a208331c5](https://linux-hardware.org/?probe=9a208331c5) | Sep 01, 2023 |
| Dell          | Latitude E7470              | [0580f1c293](https://linux-hardware.org/?probe=0580f1c293) | Sep 01, 2023 |
| HP            | EliteBook Folio 1040 G1     | [1c496aba4a](https://linux-hardware.org/?probe=1c496aba4a) | Sep 01, 2023 |
| Lenovo        | Legion Slim 7 16IRH8 82Y... | [ab14d9d9bb](https://linux-hardware.org/?probe=ab14d9d9bb) | Aug 31, 2023 |
| Dell          | Latitude 7340               | [d6d1df94f5](https://linux-hardware.org/?probe=d6d1df94f5) | Aug 31, 2023 |
| Apple         | MacBookPro8,1               | [a99931801d](https://linux-hardware.org/?probe=a99931801d) | Aug 31, 2023 |
| HP            | ENVY m6                     | [eea19d891e](https://linux-hardware.org/?probe=eea19d891e) | Aug 31, 2023 |
| Dell          | Latitude 7390               | [3aaefe5b81](https://linux-hardware.org/?probe=3aaefe5b81) | Aug 31, 2023 |
| Apple         | MacBookPro10,1              | [7741e9850b](https://linux-hardware.org/?probe=7741e9850b) | Aug 31, 2023 |
| Apple         | MacBookPro15,2              | [a93751de6d](https://linux-hardware.org/?probe=a93751de6d) | Aug 30, 2023 |
| Apple         | MacBookPro16,2              | [9782f69f43](https://linux-hardware.org/?probe=9782f69f43) | Aug 30, 2023 |
| HP            | 250 G7 Notebook PC          | [1964cb4738](https://linux-hardware.org/?probe=1964cb4738) | Aug 30, 2023 |
| HP            | 250 G7 Notebook PC          | [7176f2933c](https://linux-hardware.org/?probe=7176f2933c) | Aug 30, 2023 |
| Acer          | Aspire E1-572               | [77cdb6f4a4](https://linux-hardware.org/?probe=77cdb6f4a4) | Aug 30, 2023 |
| ASUSTek       | P552LA                      | [6eca0a231c](https://linux-hardware.org/?probe=6eca0a231c) | Aug 30, 2023 |
| Dell          | Latitude 3350               | [4fa556a69f](https://linux-hardware.org/?probe=4fa556a69f) | Aug 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [dc4910965c](https://linux-hardware.org/?probe=dc4910965c) | Aug 29, 2023 |
| Apple         | MacBookPro8,1               | [43db739186](https://linux-hardware.org/?probe=43db739186) | Aug 29, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [4c46f7ae80](https://linux-hardware.org/?probe=4c46f7ae80) | Aug 28, 2023 |
| Dell          | Latitude 14 Rugged (5404... | [c96c172d03](https://linux-hardware.org/?probe=c96c172d03) | Aug 27, 2023 |
| HP            | Compaq 6710b (GE822PA#AB... | [134d0685ff](https://linux-hardware.org/?probe=134d0685ff) | Aug 26, 2023 |
| Acer          | Predator G9-793             | [531f857477](https://linux-hardware.org/?probe=531f857477) | Aug 26, 2023 |
| HP            | ProBook 450 15.6 inch G1... | [973d7867a4](https://linux-hardware.org/?probe=973d7867a4) | Aug 26, 2023 |
| Dell          | XPS 17 9700                 | [93fec269da](https://linux-hardware.org/?probe=93fec269da) | Aug 25, 2023 |
| Dell          | Vostro 2520                 | [96018ae096](https://linux-hardware.org/?probe=96018ae096) | Aug 24, 2023 |
| Lenovo        | ThinkPad R61 7732NDG        | [b0d510a7ad](https://linux-hardware.org/?probe=b0d510a7ad) | Aug 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [5a6247f9b2](https://linux-hardware.org/?probe=5a6247f9b2) | Aug 24, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [68d3bc88e4](https://linux-hardware.org/?probe=68d3bc88e4) | Aug 23, 2023 |
| HP            | Pavilion dv6                | [38fbd02f14](https://linux-hardware.org/?probe=38fbd02f14) | Aug 23, 2023 |
| Fujitsu       | S6420                       | [044d4185b7](https://linux-hardware.org/?probe=044d4185b7) | Aug 22, 2023 |
| Apple         | MacBookPro9,2               | [a8a1e5df49](https://linux-hardware.org/?probe=a8a1e5df49) | Aug 21, 2023 |
| Kogan         | KAL14N360PA                 | [527a0d3cba](https://linux-hardware.org/?probe=527a0d3cba) | Aug 20, 2023 |
| Kogan         | KAL14N360PA                 | [b7cecb1518](https://linux-hardware.org/?probe=b7cecb1518) | Aug 20, 2023 |
| Lenovo        | Yoga Pro 9 14IRP8 83BU      | [b42f885e14](https://linux-hardware.org/?probe=b42f885e14) | Aug 18, 2023 |
| Toshiba       | Satellite L550              | [4c331017e2](https://linux-hardware.org/?probe=4c331017e2) | Aug 18, 2023 |
| Acer          | Aspire 5755G                | [720c3bfa88](https://linux-hardware.org/?probe=720c3bfa88) | Aug 18, 2023 |
| Acer          | Aspire E5-571               | [8a924c30e6](https://linux-hardware.org/?probe=8a924c30e6) | Aug 17, 2023 |
| MSI           | GS60 6QE                    | [3372d46d8c](https://linux-hardware.org/?probe=3372d46d8c) | Aug 16, 2023 |
| Google        | Phaser360                   | [3c248cc2c8](https://linux-hardware.org/?probe=3c248cc2c8) | Aug 16, 2023 |
| Dell          | Precision 5520              | [0516c33229](https://linux-hardware.org/?probe=0516c33229) | Aug 16, 2023 |
| Dell          | Precision 5520              | [b9a35fa791](https://linux-hardware.org/?probe=b9a35fa791) | Aug 16, 2023 |
| Lenovo        | Yoga Pro 9 16IRP8 83BY      | [6242833326](https://linux-hardware.org/?probe=6242833326) | Aug 15, 2023 |
| Lenovo        | Yoga Pro 9 16IRP8 83BY      | [22252eb1d9](https://linux-hardware.org/?probe=22252eb1d9) | Aug 15, 2023 |
| HP            | Notebook                    | [f32b596c87](https://linux-hardware.org/?probe=f32b596c87) | Aug 14, 2023 |
| Apple         | MacBookPro5,5               | [dc696b572c](https://linux-hardware.org/?probe=dc696b572c) | Aug 14, 2023 |
| Apple         | MacBookPro11,1              | [11b8c16b30](https://linux-hardware.org/?probe=11b8c16b30) | Aug 14, 2023 |
| Apple         | MacBookPro5,5               | [5d7e68e3ae](https://linux-hardware.org/?probe=5d7e68e3ae) | Aug 14, 2023 |
| Dell          | Latitude E7470              | [99518b81f7](https://linux-hardware.org/?probe=99518b81f7) | Aug 13, 2023 |
| HP            | ProBook 6450b               | [8862a40143](https://linux-hardware.org/?probe=8862a40143) | Aug 13, 2023 |
| Dell          | Latitude E6410              | [8ed9952374](https://linux-hardware.org/?probe=8ed9952374) | Aug 13, 2023 |
| Dell          | Inspiron M5010              | [dd2538ba1a](https://linux-hardware.org/?probe=dd2538ba1a) | Aug 13, 2023 |
| Panasonic     | CF-19ADNAXDA                | [d96cf2b13c](https://linux-hardware.org/?probe=d96cf2b13c) | Aug 12, 2023 |
| Dell          | G7 7790                     | [b5062f0928](https://linux-hardware.org/?probe=b5062f0928) | Aug 12, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [359d84713c](https://linux-hardware.org/?probe=359d84713c) | Aug 11, 2023 |
| Acer          | TMP255-M                    | [0b1adaea4e](https://linux-hardware.org/?probe=0b1adaea4e) | Aug 11, 2023 |
| Leader        | SC404PRO                    | [6f24ee5e0c](https://linux-hardware.org/?probe=6f24ee5e0c) | Aug 11, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | [2f64f3ee9a](https://linux-hardware.org/?probe=2f64f3ee9a) | Aug 10, 2023 |
| Dell          | Inspiron M5010              | [be4ad618b4](https://linux-hardware.org/?probe=be4ad618b4) | Aug 09, 2023 |
| Apple         | MacBookPro15,2              | [68e26bb5d3](https://linux-hardware.org/?probe=68e26bb5d3) | Aug 09, 2023 |
| Dell          | Vostro 5581                 | [b4495daa07](https://linux-hardware.org/?probe=b4495daa07) | Aug 08, 2023 |
| Apple         | MacBookPro8,1               | [e8524b0045](https://linux-hardware.org/?probe=e8524b0045) | Aug 08, 2023 |
| HP            | Laptop 14-cm0xxx            | [ffd0be48c6](https://linux-hardware.org/?probe=ffd0be48c6) | Aug 08, 2023 |
| Dell          | XPS 13 9350                 | [fb1aaeae43](https://linux-hardware.org/?probe=fb1aaeae43) | Aug 07, 2023 |
| Dell          | Inspiron 5770               | [d6a978f124](https://linux-hardware.org/?probe=d6a978f124) | Aug 07, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [f2d72fe710](https://linux-hardware.org/?probe=f2d72fe710) | Aug 07, 2023 |
| Acer          | Aspire 5750G                | [3b589d53bc](https://linux-hardware.org/?probe=3b589d53bc) | Aug 06, 2023 |
| MSI           | P65 Creator 8RE             | [853567f156](https://linux-hardware.org/?probe=853567f156) | Aug 06, 2023 |
| MSI           | P65 Creator 8RE             | [f26344a920](https://linux-hardware.org/?probe=f26344a920) | Aug 05, 2023 |
| Dell          | Latitude E6220              | [636392b4bf](https://linux-hardware.org/?probe=636392b4bf) | Aug 05, 2023 |
| Acer          | AS E5-523G                  | [b37e833d1e](https://linux-hardware.org/?probe=b37e833d1e) | Aug 05, 2023 |
| Acer          | Aspire 8943G                | [fedb43e298](https://linux-hardware.org/?probe=fedb43e298) | Aug 04, 2023 |
| Lenovo        | ThinkPad T480s 20L8S84H0... | [d64e9809fa](https://linux-hardware.org/?probe=d64e9809fa) | Aug 04, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | [c96666b80d](https://linux-hardware.org/?probe=c96666b80d) | Aug 03, 2023 |
| Apple         | MacBookPro11,3              | [1eb6fd9620](https://linux-hardware.org/?probe=1eb6fd9620) | Aug 02, 2023 |
| Dell          | Inspiron M5010              | [8608f29a0f](https://linux-hardware.org/?probe=8608f29a0f) | Jul 30, 2023 |
| Lenovo        | ThinkBook 13x G2 IAP 21A... | [bc18b4b7ed](https://linux-hardware.org/?probe=bc18b4b7ed) | Jul 29, 2023 |
| Lenovo        | ThinkBook 13x G2 IAP 21A... | [9b4b9b9d59](https://linux-hardware.org/?probe=9b4b9b9d59) | Jul 29, 2023 |
| Toshiba       | PORTEGE X30-E               | [c610464fb5](https://linux-hardware.org/?probe=c610464fb5) | Jul 27, 2023 |
| Acer          | TMP255-M                    | [25d376a674](https://linux-hardware.org/?probe=25d376a674) | Jul 26, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [0059745bdf](https://linux-hardware.org/?probe=0059745bdf) | Jul 25, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [90beff8e65](https://linux-hardware.org/?probe=90beff8e65) | Jul 25, 2023 |
| Acer          | TMP255-M                    | [c4bfc82a98](https://linux-hardware.org/?probe=c4bfc82a98) | Jul 24, 2023 |
| Acer          | TMP255-M                    | [7a57ee89af](https://linux-hardware.org/?probe=7a57ee89af) | Jul 24, 2023 |
| Dell          | Latitude 5410               | [29261ea2bb](https://linux-hardware.org/?probe=29261ea2bb) | Jul 24, 2023 |
| MSI           | Cyborg 15 A13VE             | [edf7b092ec](https://linux-hardware.org/?probe=edf7b092ec) | Jul 23, 2023 |
| HP            | Laptop 15s-eq2xxx           | [35d95135f4](https://linux-hardware.org/?probe=35d95135f4) | Jul 23, 2023 |
| MSI           | Cyborg 15 A13VE             | [421c2ff6b0](https://linux-hardware.org/?probe=421c2ff6b0) | Jul 23, 2023 |
| HP            | EliteBook 835 G8 Noteboo... | [a3350e1d80](https://linux-hardware.org/?probe=a3350e1d80) | Jul 23, 2023 |
| HP            | ZBook Studio G3             | [bcfc5b64f4](https://linux-hardware.org/?probe=bcfc5b64f4) | Jul 23, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [f525252834](https://linux-hardware.org/?probe=f525252834) | Jul 23, 2023 |
| MSI           | MEGA BOOK GX620             | [184ec8dfc2](https://linux-hardware.org/?probe=184ec8dfc2) | Jul 22, 2023 |
| Dell          | Latitude E6430s             | [8e74e2a524](https://linux-hardware.org/?probe=8e74e2a524) | Jul 22, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [fa4def4ece](https://linux-hardware.org/?probe=fa4def4ece) | Jul 21, 2023 |
| Apple         | MacBookPro14,3              | [e24c8a224e](https://linux-hardware.org/?probe=e24c8a224e) | Jul 21, 2023 |
| Toshiba       | Satellite L750              | [662f89dcc3](https://linux-hardware.org/?probe=662f89dcc3) | Jul 20, 2023 |
| HP            | 250 G5 Notebook PC          | [572537c287](https://linux-hardware.org/?probe=572537c287) | Jul 19, 2023 |
| ASRock        | Z77 Performance             | [585aaad9ad](https://linux-hardware.org/?probe=585aaad9ad) | Jul 18, 2023 |
| Toshiba       | Satellite L850              | [afdd53cd2f](https://linux-hardware.org/?probe=afdd53cd2f) | Jul 18, 2023 |
| Toshiba       | Satellite L850              | [23c31a7c87](https://linux-hardware.org/?probe=23c31a7c87) | Jul 17, 2023 |
| Lenovo        | ThinkPad X13s Gen 1 21BY... | [1a0f8c842b](https://linux-hardware.org/?probe=1a0f8c842b) | Jul 16, 2023 |
| Dell          | G5 5505                     | [ba144013b3](https://linux-hardware.org/?probe=ba144013b3) | Jul 15, 2023 |
| MSI           | Stealth 16Studio A13VG      | [ab3683571a](https://linux-hardware.org/?probe=ab3683571a) | Jul 13, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [706f24ffe5](https://linux-hardware.org/?probe=706f24ffe5) | Jul 12, 2023 |
| ASUSTek       | Zephyrus M GM501GM          | [72454f0f8e](https://linux-hardware.org/?probe=72454f0f8e) | Jul 11, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [38f91b870c](https://linux-hardware.org/?probe=38f91b870c) | Jul 11, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [e0c7ec0cbc](https://linux-hardware.org/?probe=e0c7ec0cbc) | Jul 11, 2023 |
| HP            | 250 G2                      | [7fd1832150](https://linux-hardware.org/?probe=7fd1832150) | Jul 11, 2023 |
| HP            | 250 G2                      | [738b04c947](https://linux-hardware.org/?probe=738b04c947) | Jul 11, 2023 |
| ASUSTek       | ZenBook UX431FA             | [09edc8f932](https://linux-hardware.org/?probe=09edc8f932) | Jul 11, 2023 |
| Acer          | ConceptD CN315-71P          | [a211dd78de](https://linux-hardware.org/?probe=a211dd78de) | Jul 09, 2023 |
| Toshiba       | PORTEGE Z30-C               | [f9d1d19d05](https://linux-hardware.org/?probe=f9d1d19d05) | Jul 09, 2023 |
| MSI           | Stealth 16Studio A13VG      | [e16527e244](https://linux-hardware.org/?probe=e16527e244) | Jul 09, 2023 |
| Acer          | Aspire One 753              | [f47888ce55](https://linux-hardware.org/?probe=f47888ce55) | Jul 08, 2023 |
| Acer          | Aspire One 753              | [9f56cc566d](https://linux-hardware.org/?probe=9f56cc566d) | Jul 08, 2023 |
| Toshiba       | PORTEGE X30-E               | [d68e9cd764](https://linux-hardware.org/?probe=d68e9cd764) | Jul 06, 2023 |
| ASUSTek       | G750JZA                     | [fb2477dd61](https://linux-hardware.org/?probe=fb2477dd61) | Jul 06, 2023 |
| HP            | ProBook 4540s               | [cccf56865c](https://linux-hardware.org/?probe=cccf56865c) | Jul 06, 2023 |
| Acer          | TravelMate 8572T            | [67f4a2af7e](https://linux-hardware.org/?probe=67f4a2af7e) | Jul 05, 2023 |
| Lenovo        | ThinkPad P50 20EQS48H00     | [7f64164b64](https://linux-hardware.org/?probe=7f64164b64) | Jul 04, 2023 |
| Apple         | MacBookPro9,2               | [f7a7db0702](https://linux-hardware.org/?probe=f7a7db0702) | Jul 04, 2023 |
| ASUSTek       | G750JZA                     | [72fc73822c](https://linux-hardware.org/?probe=72fc73822c) | Jul 04, 2023 |
| Dell          | Latitude 5420               | [dedd6c842c](https://linux-hardware.org/?probe=dedd6c842c) | Jul 04, 2023 |
| Dell          | Latitude 5420               | [dfe3274d7e](https://linux-hardware.org/?probe=dfe3274d7e) | Jul 03, 2023 |
| Samsung       | 700Z3A/700Z4A/700Z5A/700... | [4586b855ca](https://linux-hardware.org/?probe=4586b855ca) | Jul 02, 2023 |
| Gigabyte      | Q2532N                      | [4560685060](https://linux-hardware.org/?probe=4560685060) | Jul 02, 2023 |
| Acer          | TravelMate 8572T            | [a73fd92e21](https://linux-hardware.org/?probe=a73fd92e21) | Jun 30, 2023 |
| ASRock        | Z77 Performance             | [a678dc9605](https://linux-hardware.org/?probe=a678dc9605) | Jun 29, 2023 |
| Acer          | TravelMate B113             | [04738ce824](https://linux-hardware.org/?probe=04738ce824) | Jun 29, 2023 |
| Acer          | TravelMate B113             | [9cfe4d5036](https://linux-hardware.org/?probe=9cfe4d5036) | Jun 29, 2023 |
| Unknown       | Unknown                     | [d358089f32](https://linux-hardware.org/?probe=d358089f32) | Jun 29, 2023 |
| Acer          | Aspire xxxx                 | [67e8606837](https://linux-hardware.org/?probe=67e8606837) | Jun 29, 2023 |
| HP            | Pavilion dv6                | [7fe9e439c0](https://linux-hardware.org/?probe=7fe9e439c0) | Jun 28, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [ba0db6c3e9](https://linux-hardware.org/?probe=ba0db6c3e9) | Jun 28, 2023 |
| ASUSTek       | ZenBook Pro 15 UX550GEX_... | [56eef68e89](https://linux-hardware.org/?probe=56eef68e89) | Jun 28, 2023 |
| Lenovo        | ThinkPad X230 2325CW1       | [70cbf738e8](https://linux-hardware.org/?probe=70cbf738e8) | Jun 27, 2023 |
| Apple         | MacBookPro11,1              | [06a581d65d](https://linux-hardware.org/?probe=06a581d65d) | Jun 25, 2023 |
| Apple         | MacBookPro11,1              | [a105b6264f](https://linux-hardware.org/?probe=a105b6264f) | Jun 25, 2023 |
| Toshiba       | Satellite L550              | [321ec36f85](https://linux-hardware.org/?probe=321ec36f85) | Jun 25, 2023 |
| ASUSTek       | X550LA                      | [225516996c](https://linux-hardware.org/?probe=225516996c) | Jun 25, 2023 |
| HP            | Laptop 15-db0xxx            | [79979ceac7](https://linux-hardware.org/?probe=79979ceac7) | Jun 25, 2023 |
| Acer          | Aspire A315-22              | [5e2e395efd](https://linux-hardware.org/?probe=5e2e395efd) | Jun 24, 2023 |
| HP            | EliteBook 830 G5            | [2b61a56610](https://linux-hardware.org/?probe=2b61a56610) | Jun 24, 2023 |
| System76      | Oryx Pro                    | [eaa4d8e105](https://linux-hardware.org/?probe=eaa4d8e105) | Jun 24, 2023 |
| ASUSTek       | X550LC                      | [30369c12e1](https://linux-hardware.org/?probe=30369c12e1) | Jun 24, 2023 |
| Lenovo        | ThinkPad T460s 20FAS0NF0... | [f2e368a70d](https://linux-hardware.org/?probe=f2e368a70d) | Jun 23, 2023 |
| HP            | Pavilion dv6                | [fa9045c36f](https://linux-hardware.org/?probe=fa9045c36f) | Jun 22, 2023 |
| ASUSTek       | X550LA                      | [9b58f1abd3](https://linux-hardware.org/?probe=9b58f1abd3) | Jun 20, 2023 |
| COM1          | NBINF-X5-9G5                | [fe2f1cfef6](https://linux-hardware.org/?probe=fe2f1cfef6) | Jun 19, 2023 |
| HP            | EliteBook 8760w             | [ac41230354](https://linux-hardware.org/?probe=ac41230354) | Jun 18, 2023 |
| Dell          | Latitude E7440              | [60d14fe6ab](https://linux-hardware.org/?probe=60d14fe6ab) | Jun 18, 2023 |
| Alienware     | M14xR2                      | [2eb0cc2d0e](https://linux-hardware.org/?probe=2eb0cc2d0e) | Jun 17, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [26b4c05332](https://linux-hardware.org/?probe=26b4c05332) | Jun 17, 2023 |
| Acer          | Aspire A315-510P            | [d1be914db1](https://linux-hardware.org/?probe=d1be914db1) | Jun 17, 2023 |
| Dell          | XPS 13 9360                 | [852d16ee14](https://linux-hardware.org/?probe=852d16ee14) | Jun 16, 2023 |
| Dell          | XPS 15 9550                 | [b7faea4be3](https://linux-hardware.org/?probe=b7faea4be3) | Jun 16, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | [99cc4bf84b](https://linux-hardware.org/?probe=99cc4bf84b) | Jun 16, 2023 |
| HP            | Pavilion dv6                | [55c83ec890](https://linux-hardware.org/?probe=55c83ec890) | Jun 15, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | [f7049b2256](https://linux-hardware.org/?probe=f7049b2256) | Jun 15, 2023 |
| Dell          | Inspiron M5010              | [33541731e3](https://linux-hardware.org/?probe=33541731e3) | Jun 14, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [b2eb89c4fd](https://linux-hardware.org/?probe=b2eb89c4fd) | Jun 13, 2023 |
| Acer          | Aspire A315-510P            | [705ad3c316](https://linux-hardware.org/?probe=705ad3c316) | Jun 12, 2023 |
| NEC Comput... | VERSA P91 series            | [7a4183e095](https://linux-hardware.org/?probe=7a4183e095) | Jun 12, 2023 |
| NEC Comput... | VERSA P91 series            | [2051db7014](https://linux-hardware.org/?probe=2051db7014) | Jun 12, 2023 |
| COM1          | NBINF-X5-9G5                | [755841cee1](https://linux-hardware.org/?probe=755841cee1) | Jun 11, 2023 |
| MSI           | GS60 6QE                    | [e04ff9df40](https://linux-hardware.org/?probe=e04ff9df40) | Jun 10, 2023 |
| Toshiba       | PORTEGE Z10t-A              | [4a0712b322](https://linux-hardware.org/?probe=4a0712b322) | Jun 10, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [5d21e64704](https://linux-hardware.org/?probe=5d21e64704) | Jun 10, 2023 |
| IT Channel... | N8xEJEK                     | [51a7e3f5b4](https://linux-hardware.org/?probe=51a7e3f5b4) | Jun 10, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | [ee9c6252ae](https://linux-hardware.org/?probe=ee9c6252ae) | Jun 07, 2023 |
| Apple         | MacBookPro14,1              | [b0435761df](https://linux-hardware.org/?probe=b0435761df) | Jun 07, 2023 |
| Apple         | MacBookPro14,1              | [a76212cc40](https://linux-hardware.org/?probe=a76212cc40) | Jun 07, 2023 |
| Apple         | MacBookAir4,2               | [afc9f50009](https://linux-hardware.org/?probe=afc9f50009) | Jun 05, 2023 |
| MSI           | GS60 6QE                    | [65ea70f7fa](https://linux-hardware.org/?probe=65ea70f7fa) | Jun 03, 2023 |
| Acer          | TravelMate 8572T            | [46920007ed](https://linux-hardware.org/?probe=46920007ed) | Jun 03, 2023 |
| Toshiba       | Satellite P870              | [559a48c91b](https://linux-hardware.org/?probe=559a48c91b) | Jun 01, 2023 |
| Dell          | XPS 15 9570                 | [6d7803788d](https://linux-hardware.org/?probe=6d7803788d) | Jun 01, 2023 |
| Intel Clie... | LAPRC710                    | [ef0d589f75](https://linux-hardware.org/?probe=ef0d589f75) | May 31, 2023 |
| Acer          | Predator G9-793             | [26ea66d872](https://linux-hardware.org/?probe=26ea66d872) | May 31, 2023 |
| Acer          | E5-551G-871W                | [8034a1ee0b](https://linux-hardware.org/?probe=8034a1ee0b) | May 30, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [c75d4298dc](https://linux-hardware.org/?probe=c75d4298dc) | May 30, 2023 |
| Toshiba       | Satellite C665              | [c6149a6430](https://linux-hardware.org/?probe=c6149a6430) | May 30, 2023 |
| Toshiba       | Satellite P870              | [2b57ca6d62](https://linux-hardware.org/?probe=2b57ca6d62) | May 29, 2023 |
| Valve         | Jupiter                     | [e6e97426e3](https://linux-hardware.org/?probe=e6e97426e3) | May 29, 2023 |
| HP            | EliteBook 840 G1            | [c256cd6942](https://linux-hardware.org/?probe=c256cd6942) | May 28, 2023 |
| Apple         | MacBookPro10,2              | [34d96aa1df](https://linux-hardware.org/?probe=34d96aa1df) | May 28, 2023 |
| Lenovo        | IdeaPad 3 14ABA7 82RM       | [d83ee3fda2](https://linux-hardware.org/?probe=d83ee3fda2) | May 28, 2023 |
| Acer          | Aspire A315-22              | [18a13174aa](https://linux-hardware.org/?probe=18a13174aa) | May 27, 2023 |
| Lenovo        | ThinkPad W541 20EGS1AR00    | [b7f46e7180](https://linux-hardware.org/?probe=b7f46e7180) | May 27, 2023 |
| Dell          | Latitude 5430               | [e8b9199229](https://linux-hardware.org/?probe=e8b9199229) | May 26, 2023 |
| Lenovo        | ThinkPad W541 20EGS1AR00    | [a5301f505d](https://linux-hardware.org/?probe=a5301f505d) | May 25, 2023 |
| Apple         | MacBookPro8,1               | [585b85e476](https://linux-hardware.org/?probe=585b85e476) | May 23, 2023 |
| Dell          | Latitude 7280               | [215bef2144](https://linux-hardware.org/?probe=215bef2144) | May 23, 2023 |
| Apple         | MacBookPro8,1               | [ca5f5ee7bf](https://linux-hardware.org/?probe=ca5f5ee7bf) | May 23, 2023 |
| Acer          | Aspire A515-56              | [dfb369a8d2](https://linux-hardware.org/?probe=dfb369a8d2) | May 22, 2023 |
| COM1          | NBINF-X5-9G5                | [33aa60eaa2](https://linux-hardware.org/?probe=33aa60eaa2) | May 22, 2023 |
| COM1          | NBINF-X5-9G5                | [8d8c13c10c](https://linux-hardware.org/?probe=8d8c13c10c) | May 22, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [b0fac119c2](https://linux-hardware.org/?probe=b0fac119c2) | May 22, 2023 |
| ASUSTek       | K56CA                       | [6ae76c1553](https://linux-hardware.org/?probe=6ae76c1553) | May 21, 2023 |
| MSI           | VR601                       | [7f9381407d](https://linux-hardware.org/?probe=7f9381407d) | May 19, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [4a9869b7a6](https://linux-hardware.org/?probe=4a9869b7a6) | May 19, 2023 |
| Apple         | MacBookAir7,2               | [337509e694](https://linux-hardware.org/?probe=337509e694) | May 19, 2023 |
| ASUSTek       | Zephyrus M GM501GM          | [bf1eed0e60](https://linux-hardware.org/?probe=bf1eed0e60) | May 18, 2023 |
| HP            | Pavilion 15                 | [fd87e57fc3](https://linux-hardware.org/?probe=fd87e57fc3) | May 18, 2023 |
| Dell          | Vostro V131                 | [e20ddd5bca](https://linux-hardware.org/?probe=e20ddd5bca) | May 18, 2023 |
| Dell          | Vostro V131                 | [7714e1784a](https://linux-hardware.org/?probe=7714e1784a) | May 18, 2023 |
| HP            | Notebook                    | [8d3bd6a690](https://linux-hardware.org/?probe=8d3bd6a690) | May 17, 2023 |
| Acer          | Predator G9-793             | [1739ea2f45](https://linux-hardware.org/?probe=1739ea2f45) | May 17, 2023 |
| MSI           | Summit E14FlipEvo A13MT     | [60e19220b9](https://linux-hardware.org/?probe=60e19220b9) | May 15, 2023 |
| ASUSTek       | ZenBook S UX391UA           | [fe36fee27a](https://linux-hardware.org/?probe=fe36fee27a) | May 14, 2023 |
| Acer          | Aspire ES1-531              | [56cdac831f](https://linux-hardware.org/?probe=56cdac831f) | May 13, 2023 |
| Gigabyte      | P34V7                       | [90e6e5d5d9](https://linux-hardware.org/?probe=90e6e5d5d9) | May 13, 2023 |
| Unknown       | Unknown                     | [3fbabd3df0](https://linux-hardware.org/?probe=3fbabd3df0) | May 11, 2023 |
| Acer          | Predator G9-793             | [95595808a8](https://linux-hardware.org/?probe=95595808a8) | May 11, 2023 |
| Toshiba       | Satellite M60               | [91437556e8](https://linux-hardware.org/?probe=91437556e8) | May 09, 2023 |
| Toshiba       | Satellite M60               | [39b2bcd3a5](https://linux-hardware.org/?probe=39b2bcd3a5) | May 09, 2023 |
| Dell          | Inspiron N5010              | [5dd91a589b](https://linux-hardware.org/?probe=5dd91a589b) | May 09, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [503204d798](https://linux-hardware.org/?probe=503204d798) | May 09, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [def28849c6](https://linux-hardware.org/?probe=def28849c6) | May 08, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [f23fb5cca0](https://linux-hardware.org/?probe=f23fb5cca0) | May 08, 2023 |
| Apple         | MacBook4,1                  | [3daf4fbc68](https://linux-hardware.org/?probe=3daf4fbc68) | May 07, 2023 |
| Dell          | Inspiron N5010              | [2a418b4e97](https://linux-hardware.org/?probe=2a418b4e97) | May 07, 2023 |
| Lenovo        | Mixx-700-12ISK 80QL         | [14bc666ec3](https://linux-hardware.org/?probe=14bc666ec3) | May 06, 2023 |
| Toshiba       | PORTEGE Z30t-A              | [18cc14eee0](https://linux-hardware.org/?probe=18cc14eee0) | May 05, 2023 |
| System76      | Oryx Pro                    | [cae9fadc38](https://linux-hardware.org/?probe=cae9fadc38) | May 04, 2023 |
| Acer          | Predator G9-793             | [b3bd1a1031](https://linux-hardware.org/?probe=b3bd1a1031) | May 03, 2023 |
| Intel Clie... | LAPRC510                    | [40c181b615](https://linux-hardware.org/?probe=40c181b615) | May 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [925b5748b9](https://linux-hardware.org/?probe=925b5748b9) | May 01, 2023 |
| Lenovo        | ThinkPad X260 20F5002NAU    | [7fcb72c132](https://linux-hardware.org/?probe=7fcb72c132) | May 01, 2023 |
| ASUSTek       | X501A1                      | [66b02cc148](https://linux-hardware.org/?probe=66b02cc148) | Apr 30, 2023 |
| HP            | Laptop 15s-eq2xxx           | [7a86bdd993](https://linux-hardware.org/?probe=7a86bdd993) | Apr 30, 2023 |
| HP            | Laptop 15s-eq2xxx           | [6206b317f2](https://linux-hardware.org/?probe=6206b317f2) | Apr 30, 2023 |
| Acer          | ConceptD CN315-71P          | [3cc902ff5c](https://linux-hardware.org/?probe=3cc902ff5c) | Apr 28, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | [73141c5006](https://linux-hardware.org/?probe=73141c5006) | Apr 27, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | [0cb164ac2f](https://linux-hardware.org/?probe=0cb164ac2f) | Apr 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [3f44947226](https://linux-hardware.org/?probe=3f44947226) | Apr 27, 2023 |
| HP            | Laptop 15s-eq2xxx           | [198fa6162e](https://linux-hardware.org/?probe=198fa6162e) | Apr 27, 2023 |
| ASUSTek       | X550CA                      | [a63293fe36](https://linux-hardware.org/?probe=a63293fe36) | Apr 26, 2023 |
| Dell          | Inspiron 5548               | [42908a7ab7](https://linux-hardware.org/?probe=42908a7ab7) | Apr 25, 2023 |
| Dell          | System XPS L702X            | [d1aa167e90](https://linux-hardware.org/?probe=d1aa167e90) | Apr 25, 2023 |
| Acer          | E5-551G-871W                | [2730a30d89](https://linux-hardware.org/?probe=2730a30d89) | Apr 25, 2023 |
| MSI           | GE72VR 6RF                  | [89cb17ee72](https://linux-hardware.org/?probe=89cb17ee72) | Apr 25, 2023 |
| Dell          | Precision 5520              | [4d1dd8b673](https://linux-hardware.org/?probe=4d1dd8b673) | Apr 23, 2023 |
| Valve         | Jupiter                     | [b5be7aa6ff](https://linux-hardware.org/?probe=b5be7aa6ff) | Apr 21, 2023 |
| Acer          | Predator G9-793             | [664d6de816](https://linux-hardware.org/?probe=664d6de816) | Apr 20, 2023 |
| Lenovo        | ThinkPad T410 2522PT3       | [8daf9af9b5](https://linux-hardware.org/?probe=8daf9af9b5) | Apr 20, 2023 |
| Acer          | Aspire 5733Z                | [de205c8c62](https://linux-hardware.org/?probe=de205c8c62) | Apr 19, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | [7da02a75b5](https://linux-hardware.org/?probe=7da02a75b5) | Apr 18, 2023 |
| Toshiba       | Satellite E45-B             | [ec0bb6bfc6](https://linux-hardware.org/?probe=ec0bb6bfc6) | Apr 17, 2023 |
| Dell          | Inspiron 13-5378            | [bcb18ae818](https://linux-hardware.org/?probe=bcb18ae818) | Apr 17, 2023 |
| HP            | Pavilion dv6                | [fc41269cf8](https://linux-hardware.org/?probe=fc41269cf8) | Apr 16, 2023 |
| Dell          | Latitude 5420               | [03247dc98c](https://linux-hardware.org/?probe=03247dc98c) | Apr 16, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [71e03c5459](https://linux-hardware.org/?probe=71e03c5459) | Apr 15, 2023 |
| Apple         | MacBookPro7,1               | [3470b35550](https://linux-hardware.org/?probe=3470b35550) | Apr 15, 2023 |
| Toshiba       | QOSMIO F750                 | [590801670a](https://linux-hardware.org/?probe=590801670a) | Apr 15, 2023 |
| Toshiba       | Satellite L850              | [dc9e77bd65](https://linux-hardware.org/?probe=dc9e77bd65) | Apr 14, 2023 |
| Dell          | Latitude E6540              | [61ab891b01](https://linux-hardware.org/?probe=61ab891b01) | Apr 13, 2023 |
| Dell          | Vostro 7590                 | [f759d8ab72](https://linux-hardware.org/?probe=f759d8ab72) | Apr 13, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [8e641b5fd5](https://linux-hardware.org/?probe=8e641b5fd5) | Apr 13, 2023 |
| Acer          | Aspire 5720Z                | [1ac7eb0d0c](https://linux-hardware.org/?probe=1ac7eb0d0c) | Apr 13, 2023 |
| Acer          | TM6495T                     | [435ae018a2](https://linux-hardware.org/?probe=435ae018a2) | Apr 11, 2023 |
| Lenovo        | ThinkPad E460 20ETA05KAU    | [a8090f51bc](https://linux-hardware.org/?probe=a8090f51bc) | Apr 09, 2023 |
| Dell          | Inspiron 1720               | [a2e3b07f6b](https://linux-hardware.org/?probe=a2e3b07f6b) | Apr 09, 2023 |
| Dell          | Latitude E5470              | [3e49e9c541](https://linux-hardware.org/?probe=3e49e9c541) | Apr 08, 2023 |
| Apple         | MacBookAir7,2               | [5aad90904c](https://linux-hardware.org/?probe=5aad90904c) | Apr 07, 2023 |
| Acer          | TravelMate 8572T            | [04f50662d8](https://linux-hardware.org/?probe=04f50662d8) | Apr 07, 2023 |
| Toshiba       | Satellite P70-A             | [6ffb7a79ef](https://linux-hardware.org/?probe=6ffb7a79ef) | Apr 06, 2023 |
| HP            | Pavilion dv6                | [be695e2cd4](https://linux-hardware.org/?probe=be695e2cd4) | Apr 06, 2023 |
| HP            | ZBook 17 G2                 | [258f32d502](https://linux-hardware.org/?probe=258f32d502) | Apr 05, 2023 |
| HUAWEI        | MACHD-WXX9                  | [7e5be74f0b](https://linux-hardware.org/?probe=7e5be74f0b) | Apr 05, 2023 |
| Apple         | MacBookPro10,1              | [473a8c1d7b](https://linux-hardware.org/?probe=473a8c1d7b) | Apr 05, 2023 |
| HP            | Notebook                    | [50c03e608d](https://linux-hardware.org/?probe=50c03e608d) | Apr 05, 2023 |
| Apple         | MacBookPro10,1              | [56079f49e3](https://linux-hardware.org/?probe=56079f49e3) | Apr 04, 2023 |
| Apple         | MacBookPro8,1               | [4ef5210167](https://linux-hardware.org/?probe=4ef5210167) | Apr 04, 2023 |
| HP            | EliteBook Folio 1040 G3     | [9e25dfd6bb](https://linux-hardware.org/?probe=9e25dfd6bb) | Apr 02, 2023 |
| HP            | ProBook 650 G2              | [89622c73d1](https://linux-hardware.org/?probe=89622c73d1) | Apr 02, 2023 |
| Dell          | XPS 15 9570                 | [7beef34820](https://linux-hardware.org/?probe=7beef34820) | Apr 01, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [2a881cc01e](https://linux-hardware.org/?probe=2a881cc01e) | Apr 01, 2023 |
| HP            | ProBook 450 G5              | [89dfecad7e](https://linux-hardware.org/?probe=89dfecad7e) | Mar 30, 2023 |
| Dell          | XPS 15 9570                 | [8d0c93e1a8](https://linux-hardware.org/?probe=8d0c93e1a8) | Mar 30, 2023 |
| Dell          | Precision 5550              | [c7244f1e31](https://linux-hardware.org/?probe=c7244f1e31) | Mar 30, 2023 |
| Dell          | G3 3590                     | [f61ce9bb82](https://linux-hardware.org/?probe=f61ce9bb82) | Mar 28, 2023 |
| MSI           | Delta 15 A5EFK              | [6f4e3ec28b](https://linux-hardware.org/?probe=6f4e3ec28b) | Mar 28, 2023 |
| MSI           | Delta 15 A5EFK              | [9dd1b67b2f](https://linux-hardware.org/?probe=9dd1b67b2f) | Mar 28, 2023 |
| HUAWEI        | NBD-WXX9                    | [8060aec150](https://linux-hardware.org/?probe=8060aec150) | Mar 25, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [9edd5002f0](https://linux-hardware.org/?probe=9edd5002f0) | Mar 24, 2023 |
| HP            | ProBook 470 G5              | [1672158957](https://linux-hardware.org/?probe=1672158957) | Mar 24, 2023 |
| HP            | ProBook 470 G5              | [383b333f72](https://linux-hardware.org/?probe=383b333f72) | Mar 24, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | [fc1c184c05](https://linux-hardware.org/?probe=fc1c184c05) | Mar 23, 2023 |
| Acer          | ConceptD CN315-71P          | [14b71e7a26](https://linux-hardware.org/?probe=14b71e7a26) | Mar 22, 2023 |
| HP            | EliteBook 8470p             | [61025e6e8b](https://linux-hardware.org/?probe=61025e6e8b) | Mar 22, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [80d1a2d67d](https://linux-hardware.org/?probe=80d1a2d67d) | Mar 22, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [eb718edb23](https://linux-hardware.org/?probe=eb718edb23) | Mar 22, 2023 |
| Dell          | Latitude E6520              | [857fdb4095](https://linux-hardware.org/?probe=857fdb4095) | Mar 21, 2023 |
| Dell          | Inspiron 5559               | [6f98b39459](https://linux-hardware.org/?probe=6f98b39459) | Mar 21, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | [786fded1ce](https://linux-hardware.org/?probe=786fded1ce) | Mar 17, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [49bb337156](https://linux-hardware.org/?probe=49bb337156) | Mar 17, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [d762fe2bf3](https://linux-hardware.org/?probe=d762fe2bf3) | Mar 17, 2023 |
| Valve         | Jupiter                     | [8f51ab644e](https://linux-hardware.org/?probe=8f51ab644e) | Mar 17, 2023 |
| Dell          | G3 3590                     | [9ef42643d8](https://linux-hardware.org/?probe=9ef42643d8) | Mar 16, 2023 |
| HP            | ProBook 430 G8 Notebook ... | [ca6ab3c197](https://linux-hardware.org/?probe=ca6ab3c197) | Mar 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [684375b9a0](https://linux-hardware.org/?probe=684375b9a0) | Mar 16, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | [787dfaa7d4](https://linux-hardware.org/?probe=787dfaa7d4) | Mar 15, 2023 |
| Acer          | Swift SFX14-41G             | [59478f318e](https://linux-hardware.org/?probe=59478f318e) | Mar 14, 2023 |
| Dell          | XPS 13 9360                 | [954055245e](https://linux-hardware.org/?probe=954055245e) | Mar 14, 2023 |
| Dell          | Inspiron M5010              | [0a5d0c9169](https://linux-hardware.org/?probe=0a5d0c9169) | Mar 14, 2023 |
| Acer          | Aspire E5-511               | [5343f73c67](https://linux-hardware.org/?probe=5343f73c67) | Mar 13, 2023 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | [b5d8bdc57d](https://linux-hardware.org/?probe=b5d8bdc57d) | Mar 12, 2023 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | [4525fa2931](https://linux-hardware.org/?probe=4525fa2931) | Mar 12, 2023 |
| Lenovo        | ThinkPad E590 20NBA000AU    | [47bfd44610](https://linux-hardware.org/?probe=47bfd44610) | Mar 12, 2023 |
| Maibenben     | P748                        | [a44d1bb8e4](https://linux-hardware.org/?probe=a44d1bb8e4) | Mar 11, 2023 |
| Dell          | XPS 15 9570                 | [9d14bee09f](https://linux-hardware.org/?probe=9d14bee09f) | Mar 10, 2023 |
| HP            | Laptop 15-db0xxx            | [ded87de736](https://linux-hardware.org/?probe=ded87de736) | Mar 09, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | [54ad36532c](https://linux-hardware.org/?probe=54ad36532c) | Mar 07, 2023 |
| HP            | Stream Laptop 11-ah1XX      | [61e3840465](https://linux-hardware.org/?probe=61e3840465) | Mar 07, 2023 |
| HP            | Compaq Presario C700        | [fe1c136403](https://linux-hardware.org/?probe=fe1c136403) | Mar 06, 2023 |
| HP            | Compaq Presario C700        | [0b29805ec8](https://linux-hardware.org/?probe=0b29805ec8) | Mar 06, 2023 |
| HP            | ENVY 17                     | [ce2278a2e4](https://linux-hardware.org/?probe=ce2278a2e4) | Mar 05, 2023 |
| Google        | Ultima                      | [5e42f67839](https://linux-hardware.org/?probe=5e42f67839) | Mar 04, 2023 |
| Valve         | Jupiter                     | [65a9e7ef52](https://linux-hardware.org/?probe=65a9e7ef52) | Mar 04, 2023 |
| HP            | Pavilion Notebook           | [906cb4b50a](https://linux-hardware.org/?probe=906cb4b50a) | Mar 03, 2023 |
| Lenovo        | V14-ADA 82C6                | [f043beec18](https://linux-hardware.org/?probe=f043beec18) | Mar 03, 2023 |
| HP            | Pavilion Notebook           | [2173dea5df](https://linux-hardware.org/?probe=2173dea5df) | Mar 02, 2023 |
| Toshiba       | TECRA Z50-C                 | [c30ead38bd](https://linux-hardware.org/?probe=c30ead38bd) | Mar 02, 2023 |
| Apple         | MacBookPro14,3              | [6f952b4c9b](https://linux-hardware.org/?probe=6f952b4c9b) | Mar 01, 2023 |
| Intel Clie... | LAPRC510                    | [925c24b3db](https://linux-hardware.org/?probe=925c24b3db) | Feb 28, 2023 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [021853dafb](https://linux-hardware.org/?probe=021853dafb) | Feb 28, 2023 |
| Intel Clie... | LAPRC510                    | [6d9a8edb0c](https://linux-hardware.org/?probe=6d9a8edb0c) | Feb 28, 2023 |
| Apple         | MacBookPro10,1              | [816a4eb27e](https://linux-hardware.org/?probe=816a4eb27e) | Feb 26, 2023 |
| HP            | Notebook                    | [4a72575c17](https://linux-hardware.org/?probe=4a72575c17) | Feb 25, 2023 |
| Toshiba       | Satellite C850              | [99d4efbb52](https://linux-hardware.org/?probe=99d4efbb52) | Feb 25, 2023 |
| Apple         | MacBookAir7,2               | [72e11db1c0](https://linux-hardware.org/?probe=72e11db1c0) | Feb 24, 2023 |
| MSI           | Vector GP66 12UEO           | [9b6bf9479e](https://linux-hardware.org/?probe=9b6bf9479e) | Feb 24, 2023 |
| HUAWEI        | NBD-WXX9                    | [ea2663126f](https://linux-hardware.org/?probe=ea2663126f) | Feb 24, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | [fa9427d71f](https://linux-hardware.org/?probe=fa9427d71f) | Feb 22, 2023 |
| Lenovo        | ThinkPad X131e 3367AH5      | [3c1cec4c1c](https://linux-hardware.org/?probe=3c1cec4c1c) | Feb 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [8110c575e9](https://linux-hardware.org/?probe=8110c575e9) | Feb 22, 2023 |
| Acer          | TravelMate 8572T            | [20d7321f8f](https://linux-hardware.org/?probe=20d7321f8f) | Feb 21, 2023 |
| Dell          | Latitude 5430               | [69fd82c453](https://linux-hardware.org/?probe=69fd82c453) | Feb 21, 2023 |
| Dell          | Latitude E6430              | [42750c43b5](https://linux-hardware.org/?probe=42750c43b5) | Feb 20, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [d4663db4e0](https://linux-hardware.org/?probe=d4663db4e0) | Feb 19, 2023 |
| HP            | 250 G5 Notebook PC          | [ca676dc566](https://linux-hardware.org/?probe=ca676dc566) | Feb 19, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [9b0ecbd3c7](https://linux-hardware.org/?probe=9b0ecbd3c7) | Feb 19, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | [cc44156b99](https://linux-hardware.org/?probe=cc44156b99) | Feb 17, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | [bc234d0b32](https://linux-hardware.org/?probe=bc234d0b32) | Feb 17, 2023 |
| Toshiba       | Satellite P750              | [6f5f99b514](https://linux-hardware.org/?probe=6f5f99b514) | Feb 16, 2023 |
| HUAWEI        | NBD-WXX9                    | [8f5697ea3a](https://linux-hardware.org/?probe=8f5697ea3a) | Feb 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [1a20fdd090](https://linux-hardware.org/?probe=1a20fdd090) | Feb 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [3384ced1ca](https://linux-hardware.org/?probe=3384ced1ca) | Feb 14, 2023 |
| MSI           | Vector GP66 12UEO           | [040bddeff8](https://linux-hardware.org/?probe=040bddeff8) | Feb 14, 2023 |
| HP            | Compaq nc6400 (RM741PA#A... | [d556bf453d](https://linux-hardware.org/?probe=d556bf453d) | Feb 13, 2023 |
| ASUSTek       | K45VS                       | [faf4fc0251](https://linux-hardware.org/?probe=faf4fc0251) | Feb 12, 2023 |
| HP            | 250 G5 Notebook PC          | [72b0ba099a](https://linux-hardware.org/?probe=72b0ba099a) | Feb 11, 2023 |
| Acer          | Aspire One 753              | [b3ef912b35](https://linux-hardware.org/?probe=b3ef912b35) | Feb 10, 2023 |
| Dell          | G15 5520                    | [121b06f3cc](https://linux-hardware.org/?probe=121b06f3cc) | Feb 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | [e3ea6ad8da](https://linux-hardware.org/?probe=e3ea6ad8da) | Feb 10, 2023 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [b79b2f3f75](https://linux-hardware.org/?probe=b79b2f3f75) | Feb 09, 2023 |
| Dell          | G15 5520                    | [7f4d36cea1](https://linux-hardware.org/?probe=7f4d36cea1) | Feb 08, 2023 |
| Alienware     | m15 R7                      | [254ab40fcf](https://linux-hardware.org/?probe=254ab40fcf) | Feb 07, 2023 |
| HP            | Laptop 15s-eq2xxx           | [4a647dd6b9](https://linux-hardware.org/?probe=4a647dd6b9) | Feb 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [8b26ec07a6](https://linux-hardware.org/?probe=8b26ec07a6) | Feb 07, 2023 |
| Acer          | Aspire E3-111               | [a7c14e51ff](https://linux-hardware.org/?probe=a7c14e51ff) | Feb 06, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [a0fc4f78ea](https://linux-hardware.org/?probe=a0fc4f78ea) | Feb 05, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [5a7ae4b151](https://linux-hardware.org/?probe=5a7ae4b151) | Feb 05, 2023 |
| HUAWEI        | NBD-WXX9                    | [0eb4367fb4](https://linux-hardware.org/?probe=0eb4367fb4) | Feb 04, 2023 |
| ASUSTek       | X550LC                      | [f22682c35f](https://linux-hardware.org/?probe=f22682c35f) | Feb 04, 2023 |
| Toshiba       | Satellite P500              | [78ebd7c272](https://linux-hardware.org/?probe=78ebd7c272) | Feb 04, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [13bdc2b06c](https://linux-hardware.org/?probe=13bdc2b06c) | Feb 03, 2023 |
| Toshiba       | Satellite C660              | [9cabffbc86](https://linux-hardware.org/?probe=9cabffbc86) | Feb 03, 2023 |
| HUAWEI        | NBD-WXX9                    | [17b77b89e5](https://linux-hardware.org/?probe=17b77b89e5) | Feb 03, 2023 |
| Lenovo        | ThinkPad T420s 4173CTO      | [232ff7a382](https://linux-hardware.org/?probe=232ff7a382) | Feb 02, 2023 |
| HP            | 250 G5 Notebook PC          | [687b1ec2d7](https://linux-hardware.org/?probe=687b1ec2d7) | Feb 02, 2023 |
| Dell          | Latitude E6520              | [548b13cd43](https://linux-hardware.org/?probe=548b13cd43) | Feb 02, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [465114aa14](https://linux-hardware.org/?probe=465114aa14) | Feb 01, 2023 |
| Acer          | Predator PH315-52           | [b1c77eb9c7](https://linux-hardware.org/?probe=b1c77eb9c7) | Jan 31, 2023 |
| ASUSTek       | X550LC                      | [4c50999862](https://linux-hardware.org/?probe=4c50999862) | Jan 30, 2023 |
| ASUSTek       | X550LC                      | [41d606bbe8](https://linux-hardware.org/?probe=41d606bbe8) | Jan 30, 2023 |
| Dell          | Inspiron 5770               | [b5612c2501](https://linux-hardware.org/?probe=b5612c2501) | Jan 29, 2023 |
| Dell          | Latitude 5400               | [80651273e4](https://linux-hardware.org/?probe=80651273e4) | Jan 29, 2023 |
| Dell          | Latitude 5400               | [eb97e73f08](https://linux-hardware.org/?probe=eb97e73f08) | Jan 29, 2023 |
| Apple         | MacBook8,1                  | [02cd28549c](https://linux-hardware.org/?probe=02cd28549c) | Jan 27, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 D... | [d2a46bd14a](https://linux-hardware.org/?probe=d2a46bd14a) | Jan 26, 2023 |
| Apple         | MacBook5,1                  | [b7759508d9](https://linux-hardware.org/?probe=b7759508d9) | Jan 26, 2023 |
| Apple         | MacBook5,1                  | [72f2c3fddc](https://linux-hardware.org/?probe=72f2c3fddc) | Jan 26, 2023 |
| Panasonic     | FZ55-2                      | [dd9ddb12b6](https://linux-hardware.org/?probe=dd9ddb12b6) | Jan 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [26abf66da5](https://linux-hardware.org/?probe=26abf66da5) | Jan 25, 2023 |
| Acer          | Aspire A315-22              | [7c048a8058](https://linux-hardware.org/?probe=7c048a8058) | Jan 24, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [c2226035ce](https://linux-hardware.org/?probe=c2226035ce) | Jan 24, 2023 |
| Alienware     | 15 R4                       | [8833335118](https://linux-hardware.org/?probe=8833335118) | Jan 23, 2023 |
| Dell          | XPS 13 9350                 | [223ab1f016](https://linux-hardware.org/?probe=223ab1f016) | Jan 22, 2023 |
| Lenovo        | ThinkPad X250 20CLS2JV01    | [932148f478](https://linux-hardware.org/?probe=932148f478) | Jan 21, 2023 |
| Dell          | XPS 9315                    | [9dfb19b7c1](https://linux-hardware.org/?probe=9dfb19b7c1) | Jan 21, 2023 |
| Dell          | Latitude 5300               | [e8c4218110](https://linux-hardware.org/?probe=e8c4218110) | Jan 21, 2023 |
| Apple         | MacBookPro11,3              | [28b4d041ad](https://linux-hardware.org/?probe=28b4d041ad) | Jan 20, 2023 |
| Apple         | MacBookAir7,2               | [ead0a07135](https://linux-hardware.org/?probe=ead0a07135) | Jan 20, 2023 |
| Apple         | MacBookAir5,2               | [03e73c44b7](https://linux-hardware.org/?probe=03e73c44b7) | Jan 20, 2023 |
| Apple         | MacBookPro14,3              | [82a49878eb](https://linux-hardware.org/?probe=82a49878eb) | Jan 19, 2023 |
| Dell          | XPS 15 7590                 | [9a7659a260](https://linux-hardware.org/?probe=9a7659a260) | Jan 18, 2023 |
| Dell          | Precision 3561              | [9528d74be6](https://linux-hardware.org/?probe=9528d74be6) | Jan 18, 2023 |
| Dell          | Precision 3561              | [5f23addbde](https://linux-hardware.org/?probe=5f23addbde) | Jan 18, 2023 |
| Lenovo        | ThinkPad X230 2325CW1       | [44a8ae0b56](https://linux-hardware.org/?probe=44a8ae0b56) | Jan 17, 2023 |
| HP            | ProBook 440 G8 Notebook ... | [a80f36a4eb](https://linux-hardware.org/?probe=a80f36a4eb) | Jan 16, 2023 |
| Samsung       | 350V5C/350V5X/350V4C/350... | [f0b2886993](https://linux-hardware.org/?probe=f0b2886993) | Jan 15, 2023 |
| Acer          | Aspire R3-131T              | [268413b274](https://linux-hardware.org/?probe=268413b274) | Jan 15, 2023 |
| Valve         | Jupiter                     | [8830efc64d](https://linux-hardware.org/?probe=8830efc64d) | Jan 15, 2023 |
| HP            | Laptop 14s-dk0xxx           | [6efb68b8da](https://linux-hardware.org/?probe=6efb68b8da) | Jan 14, 2023 |
| Lenovo        | V14-IIL 82C4                | [3837db6f8a](https://linux-hardware.org/?probe=3837db6f8a) | Jan 13, 2023 |
| Intel Clie... | LAPBC510                    | [493f0e9608](https://linux-hardware.org/?probe=493f0e9608) | Jan 13, 2023 |
| Dell          | Latitude 5300               | [148745c883](https://linux-hardware.org/?probe=148745c883) | Jan 13, 2023 |
| Intel Clie... | LAPBC510                    | [ac0b81bf2e](https://linux-hardware.org/?probe=ac0b81bf2e) | Jan 13, 2023 |
| Acer          | Predator PH315-52           | [c6a710b940](https://linux-hardware.org/?probe=c6a710b940) | Jan 13, 2023 |
| Dell          | Inspiron 5770               | [7435d85aca](https://linux-hardware.org/?probe=7435d85aca) | Jan 12, 2023 |
| Dell          | XPS 17 9700                 | [09f6a754d6](https://linux-hardware.org/?probe=09f6a754d6) | Jan 12, 2023 |
| Acer          | Swift SF514-54T             | [98a18475e8](https://linux-hardware.org/?probe=98a18475e8) | Jan 11, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [511306775e](https://linux-hardware.org/?probe=511306775e) | Jan 11, 2023 |
| Dell          | Inspiron 3543               | [c7c7419fd5](https://linux-hardware.org/?probe=c7c7419fd5) | Jan 10, 2023 |
| HP            | ProBook 440 G8 Notebook ... | [17dc10d7bb](https://linux-hardware.org/?probe=17dc10d7bb) | Jan 10, 2023 |
| Lenovo        | ThinkPad T430s 2356AF9      | [eca34fb600](https://linux-hardware.org/?probe=eca34fb600) | Jan 09, 2023 |
| Dell          | XPS 13 9333                 | [f291c4d057](https://linux-hardware.org/?probe=f291c4d057) | Jan 09, 2023 |
| HP            | EliteBook Folio 9470m       | [1c4f7f2f2a](https://linux-hardware.org/?probe=1c4f7f2f2a) | Jan 09, 2023 |
| Dell          | Latitude 7280               | [931dcfb8be](https://linux-hardware.org/?probe=931dcfb8be) | Jan 08, 2023 |
| Dell          | Latitude E7450              | [635ef7be4a](https://linux-hardware.org/?probe=635ef7be4a) | Jan 08, 2023 |
| Lenovo        | ThinkPad W530 2463B87       | [5ac9828d4c](https://linux-hardware.org/?probe=5ac9828d4c) | Jan 08, 2023 |
| Acer          | Predator G9-793             | [5256ec6943](https://linux-hardware.org/?probe=5256ec6943) | Jan 07, 2023 |
| Apple         | MacBookPro12,1              | [67f40c78ec](https://linux-hardware.org/?probe=67f40c78ec) | Jan 06, 2023 |
| Apple         | MacBookPro12,1              | [58f2e834d8](https://linux-hardware.org/?probe=58f2e834d8) | Jan 06, 2023 |
| GPU Compan... | GWTN156-2BK                 | [263354b92e](https://linux-hardware.org/?probe=263354b92e) | Jan 06, 2023 |
| Dell          | Precision M4700             | [414d8c4701](https://linux-hardware.org/?probe=414d8c4701) | Jan 06, 2023 |
| GPU Compan... | GWTN156-2BK                 | [99bf8fff2f](https://linux-hardware.org/?probe=99bf8fff2f) | Jan 06, 2023 |
| GPU Compan... | GWTN156-2BK                 | [d9fa2355b0](https://linux-hardware.org/?probe=d9fa2355b0) | Jan 05, 2023 |
| HP            | Laptop 15s-fq1xxx           | [488e1f656c](https://linux-hardware.org/?probe=488e1f656c) | Jan 03, 2023 |
| HP            | Laptop 15s-fq1xxx           | [d0ac402ed9](https://linux-hardware.org/?probe=d0ac402ed9) | Jan 03, 2023 |
| HP            | Pavilion                    | [466e855af1](https://linux-hardware.org/?probe=466e855af1) | Jan 03, 2023 |
| Lenovo        | ThinkPad X260 20F5005NAU    | [3f68b8438c](https://linux-hardware.org/?probe=3f68b8438c) | Jan 02, 2023 |
| HP            | EliteBook 2760p             | [91741e63eb](https://linux-hardware.org/?probe=91741e63eb) | Jan 01, 2023 |
| HP            | EliteBook 2760p             | [6ac462efda](https://linux-hardware.org/?probe=6ac462efda) | Jan 01, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [cf40d3f30c](https://linux-hardware.org/?probe=cf40d3f30c) | Dec 31, 2022 |
| Apple         | MacBookAir7,2               | [8b84042dc6](https://linux-hardware.org/?probe=8b84042dc6) | Dec 30, 2022 |
| Apple         | MacBookAir7,2               | [dae09ec15f](https://linux-hardware.org/?probe=dae09ec15f) | Dec 30, 2022 |
| Dell          | XPS 15 9570                 | [cc31efb32d](https://linux-hardware.org/?probe=cc31efb32d) | Dec 30, 2022 |
| ASUSTek       | X555UJ                      | [f4ba8643aa](https://linux-hardware.org/?probe=f4ba8643aa) | Dec 30, 2022 |
| AMI           | F3C2                        | [ed7d4a2a13](https://linux-hardware.org/?probe=ed7d4a2a13) | Dec 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [1cf63ef1ad](https://linux-hardware.org/?probe=1cf63ef1ad) | Dec 28, 2022 |
| Acer          | Aspire 5742G                | [f58bb411b8](https://linux-hardware.org/?probe=f58bb411b8) | Dec 28, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | [d1f63174e4](https://linux-hardware.org/?probe=d1f63174e4) | Dec 28, 2022 |
| Lenovo        | ThinkPad X131e 33672K5      | [70d10e91fb](https://linux-hardware.org/?probe=70d10e91fb) | Dec 28, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | [6eaa690ff2](https://linux-hardware.org/?probe=6eaa690ff2) | Dec 28, 2022 |
| Toshiba       | PORTEGE Z30-C               | [03dad182bb](https://linux-hardware.org/?probe=03dad182bb) | Dec 28, 2022 |
| MSI           | Raider GE77HX 12UGS         | [9f7185ccd7](https://linux-hardware.org/?probe=9f7185ccd7) | Dec 27, 2022 |
| MSI           | GP62M 7REX                  | [f49c90b8dc](https://linux-hardware.org/?probe=f49c90b8dc) | Dec 25, 2022 |
| Dell          | Latitude E6520              | [33a51c934d](https://linux-hardware.org/?probe=33a51c934d) | Dec 25, 2022 |
| MSI           | GS60 6QE                    | [aa2f6b0f24](https://linux-hardware.org/?probe=aa2f6b0f24) | Dec 24, 2022 |
| Toshiba       | Satellite C50D-C            | [5f2debe594](https://linux-hardware.org/?probe=5f2debe594) | Dec 23, 2022 |
| Lenovo        | ThinkPad X260 20F5005NAU    | [5f75bb423d](https://linux-hardware.org/?probe=5f75bb423d) | Dec 23, 2022 |
| Lenovo        | ThinkPad X260 20F5005NAU    | [844f589d20](https://linux-hardware.org/?probe=844f589d20) | Dec 22, 2022 |
| Acer          | Nitro AN515-52              | [4732443b9e](https://linux-hardware.org/?probe=4732443b9e) | Dec 22, 2022 |
| Acer          | Nitro AN515-52              | [354b048898](https://linux-hardware.org/?probe=354b048898) | Dec 21, 2022 |
| HP            | Pavilion dv6                | [8b0f82599c](https://linux-hardware.org/?probe=8b0f82599c) | Dec 20, 2022 |
| HUAWEI        | NBD-WXX9                    | [1fec8c22dc](https://linux-hardware.org/?probe=1fec8c22dc) | Dec 20, 2022 |
| HUAWEI        | NBD-WXX9                    | [b0a4a9919c](https://linux-hardware.org/?probe=b0a4a9919c) | Dec 18, 2022 |
| ASUSTek       | X550LD                      | [2960bdb195](https://linux-hardware.org/?probe=2960bdb195) | Dec 16, 2022 |
| Apple         | MacBookPro14,2              | [702a622854](https://linux-hardware.org/?probe=702a622854) | Dec 14, 2022 |
| Apple         | MacBookAir7,2               | [b1386d66d5](https://linux-hardware.org/?probe=b1386d66d5) | Dec 13, 2022 |
| Kogan         | KAL11C250SB                 | [e7ad1c21ad](https://linux-hardware.org/?probe=e7ad1c21ad) | Dec 13, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [265ba7b252](https://linux-hardware.org/?probe=265ba7b252) | Dec 13, 2022 |
| Dell          | XPS L521X                   | [c69c906797](https://linux-hardware.org/?probe=c69c906797) | Dec 12, 2022 |
| ASUSTek       | K56CB                       | [94b056f1f4](https://linux-hardware.org/?probe=94b056f1f4) | Dec 12, 2022 |
| Acer          | Aspire A515-45              | [26f5bfeb45](https://linux-hardware.org/?probe=26f5bfeb45) | Dec 09, 2022 |
| HP            | Laptop 15-db0xxx            | [b0de030271](https://linux-hardware.org/?probe=b0de030271) | Dec 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [b5f311cc8f](https://linux-hardware.org/?probe=b5f311cc8f) | Dec 07, 2022 |
| Dell          | G15 5511                    | [999ed53283](https://linux-hardware.org/?probe=999ed53283) | Dec 05, 2022 |
| Apple         | MacBookPro15,1              | [36732e2602](https://linux-hardware.org/?probe=36732e2602) | Dec 05, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | [c458ba13c3](https://linux-hardware.org/?probe=c458ba13c3) | Dec 05, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | [bd9f0dc967](https://linux-hardware.org/?probe=bd9f0dc967) | Dec 05, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [fb96bd56ad](https://linux-hardware.org/?probe=fb96bd56ad) | Dec 04, 2022 |
| Unknown       | Unknown                     | [54c6593c53](https://linux-hardware.org/?probe=54c6593c53) | Dec 03, 2022 |
| Unknown       | Unknown                     | [7668b4d9a2](https://linux-hardware.org/?probe=7668b4d9a2) | Dec 03, 2022 |
| Apple         | MacBookPro8,1               | [af40c4e286](https://linux-hardware.org/?probe=af40c4e286) | Dec 03, 2022 |
| Acer          | ConceptD CN315-71P          | [370356b4a8](https://linux-hardware.org/?probe=370356b4a8) | Dec 02, 2022 |
| Acer          | ConceptD CN315-71P          | [bbdfc25e56](https://linux-hardware.org/?probe=bbdfc25e56) | Dec 02, 2022 |
| Intel Clie... | LAPBC510                    | [e903f5edea](https://linux-hardware.org/?probe=e903f5edea) | Dec 02, 2022 |
| Lenovo        | ThinkPad T420 4236GY3       | [63dd78fcec](https://linux-hardware.org/?probe=63dd78fcec) | Dec 02, 2022 |
| Dell          | XPS 13 9310                 | [ca1fab4db1](https://linux-hardware.org/?probe=ca1fab4db1) | Dec 02, 2022 |
| Dell          | XPS 13 9310                 | [2adab1a5b2](https://linux-hardware.org/?probe=2adab1a5b2) | Dec 02, 2022 |
| AMI           | Intel                       | [3e2e312c6e](https://linux-hardware.org/?probe=3e2e312c6e) | Nov 29, 2022 |
| Razer         | Blade                       | [de6f0ebcad](https://linux-hardware.org/?probe=de6f0ebcad) | Nov 28, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [3433fd5db6](https://linux-hardware.org/?probe=3433fd5db6) | Nov 28, 2022 |
| Apple         | MacBookAir6,2               | [ed4692d2a7](https://linux-hardware.org/?probe=ed4692d2a7) | Nov 28, 2022 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [ea6f1fc82e](https://linux-hardware.org/?probe=ea6f1fc82e) | Nov 28, 2022 |
| Dell          | XPS 15 9500                 | [f149afb5d1](https://linux-hardware.org/?probe=f149afb5d1) | Nov 28, 2022 |
| Intel Clie... | LAPBC510                    | [f58ff7b6fa](https://linux-hardware.org/?probe=f58ff7b6fa) | Nov 27, 2022 |
| Dell          | Latitude E7440              | [3709af0366](https://linux-hardware.org/?probe=3709af0366) | Nov 27, 2022 |
| Apple         | MacBookPro15,2              | [446ef54cb5](https://linux-hardware.org/?probe=446ef54cb5) | Nov 26, 2022 |
| Apple         | MacBookAir8,1               | [6656b4e315](https://linux-hardware.org/?probe=6656b4e315) | Nov 26, 2022 |
| Kogan         | KAL11C250SB                 | [9ca4f71bb9](https://linux-hardware.org/?probe=9ca4f71bb9) | Nov 26, 2022 |
| Razer         | Blade Pro                   | [dabfd64904](https://linux-hardware.org/?probe=dabfd64904) | Nov 25, 2022 |
| MSI           | GS60 6QE                    | [80d61ee685](https://linux-hardware.org/?probe=80d61ee685) | Nov 25, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [16f086de33](https://linux-hardware.org/?probe=16f086de33) | Nov 25, 2022 |
| Acer          | Aspire R3-131T              | [5395a2556c](https://linux-hardware.org/?probe=5395a2556c) | Nov 24, 2022 |
| Acer          | ConceptD CN315-71P          | [db3ccac179](https://linux-hardware.org/?probe=db3ccac179) | Nov 23, 2022 |
| Apple         | MacBookPro5,1               | [62c77a0e63](https://linux-hardware.org/?probe=62c77a0e63) | Nov 23, 2022 |
| Apple         | MacBookPro5,1               | [06c02ff303](https://linux-hardware.org/?probe=06c02ff303) | Nov 21, 2022 |
| Lenovo        | ThinkPad X240 20AMA0LTAU    | [54ce03d1f1](https://linux-hardware.org/?probe=54ce03d1f1) | Nov 20, 2022 |
| Samsung       | RC410/RC510/RC710           | [06a337fda3](https://linux-hardware.org/?probe=06a337fda3) | Nov 20, 2022 |
| Samsung       | RC410/RC510/RC710           | [965d9d2f5c](https://linux-hardware.org/?probe=965d9d2f5c) | Nov 20, 2022 |
| MSI           | GP62M 7REX                  | [2125546b68](https://linux-hardware.org/?probe=2125546b68) | Nov 19, 2022 |
| MSI           | GP62M 7REX                  | [6ea684de8c](https://linux-hardware.org/?probe=6ea684de8c) | Nov 19, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | [2cb56b8c63](https://linux-hardware.org/?probe=2cb56b8c63) | Nov 17, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [2d0fb1c5d1](https://linux-hardware.org/?probe=2d0fb1c5d1) | Nov 16, 2022 |
| AMI           | Intel                       | [ac36a02403](https://linux-hardware.org/?probe=ac36a02403) | Nov 16, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [66737bb1cc](https://linux-hardware.org/?probe=66737bb1cc) | Nov 15, 2022 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | [ccbda507a9](https://linux-hardware.org/?probe=ccbda507a9) | Nov 14, 2022 |
| ASUSTek       | X550CC                      | [d37b8f7bbd](https://linux-hardware.org/?probe=d37b8f7bbd) | Nov 13, 2022 |
| Acer          | ConceptD CN315-71P          | [2d3a3f4ac8](https://linux-hardware.org/?probe=2d3a3f4ac8) | Nov 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [57368a1129](https://linux-hardware.org/?probe=57368a1129) | Nov 12, 2022 |
| Apple         | MacBook9,1                  | [755a70132f](https://linux-hardware.org/?probe=755a70132f) | Nov 12, 2022 |
| Apple         | MacBook9,1                  | [4371465097](https://linux-hardware.org/?probe=4371465097) | Nov 12, 2022 |
| HP            | Pavilion Notebook           | [1d6ae45d45](https://linux-hardware.org/?probe=1d6ae45d45) | Nov 11, 2022 |
| MSI           | GS60 6QE                    | [a571dc503c](https://linux-hardware.org/?probe=a571dc503c) | Nov 11, 2022 |
| Toshiba       | TECRA A40-D                 | [ab2d9e2712](https://linux-hardware.org/?probe=ab2d9e2712) | Nov 11, 2022 |
| Acer          | Aspire A315-22              | [cde0b24cde](https://linux-hardware.org/?probe=cde0b24cde) | Nov 10, 2022 |
| Lenovo        | ThinkPad T420 4180PEM       | [ad4d7f338d](https://linux-hardware.org/?probe=ad4d7f338d) | Nov 09, 2022 |
| HP            | ProBook 640 G1              | [3189f08179](https://linux-hardware.org/?probe=3189f08179) | Nov 09, 2022 |
| HP            | Pavilion Notebook           | [a7de751ce8](https://linux-hardware.org/?probe=a7de751ce8) | Nov 09, 2022 |
| Dell          | XPS 13 9310                 | [5f358af327](https://linux-hardware.org/?probe=5f358af327) | Nov 08, 2022 |
| MSI           | GS60 6QE                    | [c843b1ff5e](https://linux-hardware.org/?probe=c843b1ff5e) | Nov 08, 2022 |
| ASUSTek       | K53E                        | [07d6d01b99](https://linux-hardware.org/?probe=07d6d01b99) | Nov 06, 2022 |
| Dell          | Latitude E6430              | [fcd82d5966](https://linux-hardware.org/?probe=fcd82d5966) | Nov 06, 2022 |
| Toshiba       | Satellite L500              | [0d6bb9cde0](https://linux-hardware.org/?probe=0d6bb9cde0) | Nov 05, 2022 |
| Toshiba       | Satellite L500              | [3d7692d178](https://linux-hardware.org/?probe=3d7692d178) | Nov 05, 2022 |
| MSI           | Katana GF76 12UC            | [3cb05bdb95](https://linux-hardware.org/?probe=3cb05bdb95) | Nov 04, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [c39a19fa2f](https://linux-hardware.org/?probe=c39a19fa2f) | Nov 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [cc28dc5c8b](https://linux-hardware.org/?probe=cc28dc5c8b) | Nov 04, 2022 |
| HP            | Pavilion Notebook           | [a8f3260004](https://linux-hardware.org/?probe=a8f3260004) | Nov 04, 2022 |
| HP            | Pavilion Notebook           | [e24f2a2f57](https://linux-hardware.org/?probe=e24f2a2f57) | Nov 03, 2022 |
| ASUSTek       | 1005HA                      | [1d386943d6](https://linux-hardware.org/?probe=1d386943d6) | Nov 02, 2022 |
| HP            | Pavilion Notebook           | [9fef9a6a8a](https://linux-hardware.org/?probe=9fef9a6a8a) | Nov 02, 2022 |
| Cube          | i18-BL                      | [725100a829](https://linux-hardware.org/?probe=725100a829) | Nov 02, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | [fefe8e5d04](https://linux-hardware.org/?probe=fefe8e5d04) | Nov 01, 2022 |
| HP            | Notebook                    | [27d097b522](https://linux-hardware.org/?probe=27d097b522) | Nov 01, 2022 |
| Acer          | Aspire 3000                 | [02693e03ca](https://linux-hardware.org/?probe=02693e03ca) | Nov 01, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | [df949b6e10](https://linux-hardware.org/?probe=df949b6e10) | Nov 01, 2022 |
| ASUSTek       | X501A                       | [d5a34df414](https://linux-hardware.org/?probe=d5a34df414) | Nov 01, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [c3ea4065c4](https://linux-hardware.org/?probe=c3ea4065c4) | Oct 29, 2022 |
| ASUSTek       | U50Vg                       | [5f2997ec95](https://linux-hardware.org/?probe=5f2997ec95) | Oct 28, 2022 |
| HP            | ProBook 640 G1              | [b096155d39](https://linux-hardware.org/?probe=b096155d39) | Oct 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [73d5bfb13a](https://linux-hardware.org/?probe=73d5bfb13a) | Oct 27, 2022 |
| Apple         | MacBookAir6,2               | [cca0d420fe](https://linux-hardware.org/?probe=cca0d420fe) | Oct 27, 2022 |
| HP            | G71                         | [3223e2fcc8](https://linux-hardware.org/?probe=3223e2fcc8) | Oct 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [7290786792](https://linux-hardware.org/?probe=7290786792) | Oct 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [4ffd604fea](https://linux-hardware.org/?probe=4ffd604fea) | Oct 25, 2022 |
| Apple         | MacBookAir7,2               | [6f72d6443c](https://linux-hardware.org/?probe=6f72d6443c) | Oct 23, 2022 |
| Apple         | MacBookAir6,2               | [edd13bcc76](https://linux-hardware.org/?probe=edd13bcc76) | Oct 23, 2022 |
| Notebook      | W650EH                      | [6bb1a8b1f1](https://linux-hardware.org/?probe=6bb1a8b1f1) | Oct 23, 2022 |
| Purism        | Librem 13 v2                | [5296ed1e19](https://linux-hardware.org/?probe=5296ed1e19) | Oct 21, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [cb901021a7](https://linux-hardware.org/?probe=cb901021a7) | Oct 21, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [63751816bc](https://linux-hardware.org/?probe=63751816bc) | Oct 21, 2022 |
| HP            | Pavilion Notebook           | [31d7e67080](https://linux-hardware.org/?probe=31d7e67080) | Oct 21, 2022 |
| Acer          | Aspire 5600                 | [202a7e570e](https://linux-hardware.org/?probe=202a7e570e) | Oct 20, 2022 |
| Lenovo        | ThinkPad T410 2522PT3       | [2cd92a7da8](https://linux-hardware.org/?probe=2cd92a7da8) | Oct 19, 2022 |
| HUAWEI        | MACHD-WXX9                  | [5086e64fed](https://linux-hardware.org/?probe=5086e64fed) | Oct 19, 2022 |
| Dell          | Inspiron M5010              | [026a7a8cd3](https://linux-hardware.org/?probe=026a7a8cd3) | Oct 18, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [926d661756](https://linux-hardware.org/?probe=926d661756) | Oct 17, 2022 |
| HP            | G71                         | [46b6033e1e](https://linux-hardware.org/?probe=46b6033e1e) | Oct 17, 2022 |
| HP            | Pavilion Notebook           | [50c44df4fb](https://linux-hardware.org/?probe=50c44df4fb) | Oct 17, 2022 |
| Dell          | Inspiron 1545               | [d9928a4ee9](https://linux-hardware.org/?probe=d9928a4ee9) | Oct 16, 2022 |
| System76      | Galago Pro                  | [ec92c5a918](https://linux-hardware.org/?probe=ec92c5a918) | Oct 14, 2022 |
| HUAWEI        | MACHD-WXX9                  | [5f0c4b3acb](https://linux-hardware.org/?probe=5f0c4b3acb) | Oct 13, 2022 |
| Apple         | MacBookPro15,2              | [705e4f406a](https://linux-hardware.org/?probe=705e4f406a) | Oct 13, 2022 |
| HP            | EliteBook 8540p             | [cd65876f22](https://linux-hardware.org/?probe=cd65876f22) | Oct 12, 2022 |
| Apple         | MacBookPro15,2              | [56fc798c2e](https://linux-hardware.org/?probe=56fc798c2e) | Oct 11, 2022 |
| Acer          | Aspire A315-22              | [07870a3cde](https://linux-hardware.org/?probe=07870a3cde) | Oct 11, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [1ae81569dd](https://linux-hardware.org/?probe=1ae81569dd) | Oct 11, 2022 |
| Dell          | Inspiron 16 5620            | [72151cd0e8](https://linux-hardware.org/?probe=72151cd0e8) | Oct 10, 2022 |
| Gigabyte      | P34V7                       | [c1423fce9e](https://linux-hardware.org/?probe=c1423fce9e) | Oct 10, 2022 |
| System76      | Galago Pro                  | [28e36afa26](https://linux-hardware.org/?probe=28e36afa26) | Oct 10, 2022 |
| HP            | ProBook 470 G5              | [a7b96649da](https://linux-hardware.org/?probe=a7b96649da) | Oct 09, 2022 |
| Panasonic     | CF-19-8                     | [439e2c8122](https://linux-hardware.org/?probe=439e2c8122) | Oct 09, 2022 |
| Panasonic     | CF-19-8                     | [bc5820629b](https://linux-hardware.org/?probe=bc5820629b) | Oct 09, 2022 |
| Dell          | XPS 15 9510                 | [6b62586012](https://linux-hardware.org/?probe=6b62586012) | Oct 09, 2022 |
| Apple         | MacBookAir7,2               | [e26911cff6](https://linux-hardware.org/?probe=e26911cff6) | Oct 08, 2022 |
| HP            | Presario V4000 (EQ608PA#... | [f462d80b2a](https://linux-hardware.org/?probe=f462d80b2a) | Oct 06, 2022 |
| Dell          | XPS 15 9510                 | [99f16967b2](https://linux-hardware.org/?probe=99f16967b2) | Oct 05, 2022 |
| Gigabyte      | AORUS 7 SB                  | [444224d1e0](https://linux-hardware.org/?probe=444224d1e0) | Oct 04, 2022 |
| Acer          | TravelMate 8572T            | [6abaaf4aa6](https://linux-hardware.org/?probe=6abaaf4aa6) | Oct 03, 2022 |
| Dell          | Inspiron 15 7510            | [521636075a](https://linux-hardware.org/?probe=521636075a) | Oct 02, 2022 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | [c555fbbf75](https://linux-hardware.org/?probe=c555fbbf75) | Oct 01, 2022 |
| HP            | ProBook 450 G4              | [9c6340e585](https://linux-hardware.org/?probe=9c6340e585) | Oct 01, 2022 |
| Toshiba       | PORTEGE Z10t-A              | [1aa913c010](https://linux-hardware.org/?probe=1aa913c010) | Oct 01, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [025a55eab7](https://linux-hardware.org/?probe=025a55eab7) | Sep 30, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [875b1df312](https://linux-hardware.org/?probe=875b1df312) | Sep 30, 2022 |
| Acer          | TravelMate 8572T            | [927bf01e34](https://linux-hardware.org/?probe=927bf01e34) | Sep 30, 2022 |
| Gigabyte      | AORUS 17 YE5                | [54b271c3fd](https://linux-hardware.org/?probe=54b271c3fd) | Sep 30, 2022 |
| Acer          | Aspire 5742G                | [354a9c2bc2](https://linux-hardware.org/?probe=354a9c2bc2) | Sep 29, 2022 |
| Dell          | Inspiron 7347               | [ac3079df8c](https://linux-hardware.org/?probe=ac3079df8c) | Sep 29, 2022 |
| Dell          | Inspiron 7347               | [144cad649c](https://linux-hardware.org/?probe=144cad649c) | Sep 29, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [fbc4f29134](https://linux-hardware.org/?probe=fbc4f29134) | Sep 28, 2022 |
| HP            | EliteBook 8770w             | [e5ec559da4](https://linux-hardware.org/?probe=e5ec559da4) | Sep 28, 2022 |
| Dell          | Latitude E7450              | [daeb4afb69](https://linux-hardware.org/?probe=daeb4afb69) | Sep 28, 2022 |
| Gigabyte      | P34V7                       | [27b9651432](https://linux-hardware.org/?probe=27b9651432) | Sep 27, 2022 |
| ASUSTek       | TUF Gaming FX505DV          | [2154b531c9](https://linux-hardware.org/?probe=2154b531c9) | Sep 26, 2022 |
| System76      | Galago Pro                  | [6b2de473b7](https://linux-hardware.org/?probe=6b2de473b7) | Sep 26, 2022 |
| Gigabyte      | AORUS 7 SB                  | [3e8222ad7c](https://linux-hardware.org/?probe=3e8222ad7c) | Sep 26, 2022 |
| ASUSTek       | TUF Gaming FX505DV          | [6b3be4af70](https://linux-hardware.org/?probe=6b3be4af70) | Sep 26, 2022 |
| Dell          | G15 5511                    | [f960f38940](https://linux-hardware.org/?probe=f960f38940) | Sep 26, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | [6c0c9c0037](https://linux-hardware.org/?probe=6c0c9c0037) | Sep 25, 2022 |
| Apple         | MacBookAir7,2               | [93dd525100](https://linux-hardware.org/?probe=93dd525100) | Sep 25, 2022 |
| HP            | Pavilion dv6                | [ae43d0bbce](https://linux-hardware.org/?probe=ae43d0bbce) | Sep 24, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [24b2810c64](https://linux-hardware.org/?probe=24b2810c64) | Sep 24, 2022 |
| Acer          | TMP645-M                    | [83b27c389c](https://linux-hardware.org/?probe=83b27c389c) | Sep 23, 2022 |
| Dell          | Precision 7760              | [f47fe0314b](https://linux-hardware.org/?probe=f47fe0314b) | Sep 23, 2022 |
| Timi          | Redmi Book Pro 15 2022      | [accc831d30](https://linux-hardware.org/?probe=accc831d30) | Sep 23, 2022 |
| Lenovo        | ThinkPad E595 20NFA000AU    | [a01352810a](https://linux-hardware.org/?probe=a01352810a) | Sep 22, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen2... | [87a3d977b1](https://linux-hardware.org/?probe=87a3d977b1) | Sep 22, 2022 |
| Apple         | MacBookPro8,1               | [d97b8fc0ed](https://linux-hardware.org/?probe=d97b8fc0ed) | Sep 21, 2022 |
| Apple         | MacBookPro10,2              | [ecc3b7e71d](https://linux-hardware.org/?probe=ecc3b7e71d) | Sep 19, 2022 |
| ASUSTek       | 1005HA                      | [3b5d6a5b1d](https://linux-hardware.org/?probe=3b5d6a5b1d) | Sep 18, 2022 |
| ASUSTek       | 1005HA                      | [3b1ce0471e](https://linux-hardware.org/?probe=3b1ce0471e) | Sep 18, 2022 |
| Lenovo        | V310-15ISK 80SY             | [fbd66d36f4](https://linux-hardware.org/?probe=fbd66d36f4) | Sep 14, 2022 |
| Apple         | MacBookAir7,2               | [03ba2808d7](https://linux-hardware.org/?probe=03ba2808d7) | Sep 13, 2022 |
| Acer          | Aspire A315-42              | [6121dfd67d](https://linux-hardware.org/?probe=6121dfd67d) | Sep 13, 2022 |
| HP            | ENVY 15                     | [fdb07294df](https://linux-hardware.org/?probe=fdb07294df) | Sep 13, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [d477c1084d](https://linux-hardware.org/?probe=d477c1084d) | Sep 10, 2022 |
| Acer          | Aspire A315-22              | [82058771f7](https://linux-hardware.org/?probe=82058771f7) | Sep 09, 2022 |
| Dell          | Latitude E7470              | [4a2f647549](https://linux-hardware.org/?probe=4a2f647549) | Sep 08, 2022 |
| Acer          | Aspire A315-22              | [49d54ac5c5](https://linux-hardware.org/?probe=49d54ac5c5) | Sep 07, 2022 |
| ASUSTek       | K55VD                       | [c1ca471555](https://linux-hardware.org/?probe=c1ca471555) | Sep 06, 2022 |
| HP            | Pavilion dv6500             | [c37bace401](https://linux-hardware.org/?probe=c37bace401) | Sep 05, 2022 |
| Dell          | XPS 13 9350                 | [dc37712dfc](https://linux-hardware.org/?probe=dc37712dfc) | Sep 02, 2022 |
| Lenovo        | Z50-70 20354                | [8ac8531142](https://linux-hardware.org/?probe=8ac8531142) | Sep 01, 2022 |
| Toshiba       | Satellite C850              | [6cf6d8fca8](https://linux-hardware.org/?probe=6cf6d8fca8) | Sep 01, 2022 |
| ASUSTek       | X550CC                      | [21f3eb8b1d](https://linux-hardware.org/?probe=21f3eb8b1d) | Sep 01, 2022 |
| Lenovo        | Z50-70 20354                | [6e245e4c63](https://linux-hardware.org/?probe=6e245e4c63) | Sep 01, 2022 |
| HP            | Notebook                    | [ee135c3930](https://linux-hardware.org/?probe=ee135c3930) | Aug 31, 2022 |
| Toshiba       | Satellite C850              | [5d7cb36794](https://linux-hardware.org/?probe=5d7cb36794) | Aug 31, 2022 |
| HP            | EliteBook 830 G6            | [897046248f](https://linux-hardware.org/?probe=897046248f) | Aug 30, 2022 |
| Lenovo        | V14-ADA 82C6                | [ce25a77e25](https://linux-hardware.org/?probe=ce25a77e25) | Aug 29, 2022 |
| HP            | EW7-I7D22875GR1             | [307b75624e](https://linux-hardware.org/?probe=307b75624e) | Aug 29, 2022 |
| Toshiba       | Satellite L850              | [fe1480794c](https://linux-hardware.org/?probe=fe1480794c) | Aug 29, 2022 |
| IT Channel... | NH5xAx                      | [66573b4b48](https://linux-hardware.org/?probe=66573b4b48) | Aug 28, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | [f30320f76e](https://linux-hardware.org/?probe=f30320f76e) | Aug 27, 2022 |
| Acer          | Aspire V5-531               | [75b841b0b8](https://linux-hardware.org/?probe=75b841b0b8) | Aug 26, 2022 |
| HP            | Laptop 15-da1xxx            | [51e23209a4](https://linux-hardware.org/?probe=51e23209a4) | Aug 26, 2022 |
| Dell          | Latitude 5300               | [f336b3aeaf](https://linux-hardware.org/?probe=f336b3aeaf) | Aug 26, 2022 |
| Lenovo        | Yoga S940-14IWL 81Q7        | [416e5db831](https://linux-hardware.org/?probe=416e5db831) | Aug 26, 2022 |
| Acer          | Aspire V5-531               | [4ae228e219](https://linux-hardware.org/?probe=4ae228e219) | Aug 25, 2022 |
| Dell          | XPS 13 7390                 | [d609bf3253](https://linux-hardware.org/?probe=d609bf3253) | Aug 24, 2022 |
| Alienware     | 15 R4                       | [f53260e0c2](https://linux-hardware.org/?probe=f53260e0c2) | Aug 23, 2022 |
| Dell          | Inspiron 5770               | [49314a1dfe](https://linux-hardware.org/?probe=49314a1dfe) | Aug 23, 2022 |
| Apple         | MacBook9,1                  | [a6726b8439](https://linux-hardware.org/?probe=a6726b8439) | Aug 22, 2022 |
| Apple         | MacBook9,1                  | [aff9259c2c](https://linux-hardware.org/?probe=aff9259c2c) | Aug 22, 2022 |
| Samsung       | 550P5C/550P7C               | [75f94f8fa5](https://linux-hardware.org/?probe=75f94f8fa5) | Aug 21, 2022 |
| Samsung       | 550P5C/550P7C               | [c369daf6b0](https://linux-hardware.org/?probe=c369daf6b0) | Aug 21, 2022 |
| ASUSTek       | X756UAK                     | [6db3b2a7bc](https://linux-hardware.org/?probe=6db3b2a7bc) | Aug 20, 2022 |
| Dell          | G3 3779                     | [a2b721ca15](https://linux-hardware.org/?probe=a2b721ca15) | Aug 19, 2022 |
| Dell          | XPS 15 9530                 | [9e6a3e80b4](https://linux-hardware.org/?probe=9e6a3e80b4) | Aug 19, 2022 |
| Dell          | Inspiron M5010              | [266f9fc41d](https://linux-hardware.org/?probe=266f9fc41d) | Aug 19, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e500790878](https://linux-hardware.org/?probe=e500790878) | Aug 18, 2022 |
| Lenovo        | ThinkPad T480s 20L70044A... | [f90559618b](https://linux-hardware.org/?probe=f90559618b) | Aug 17, 2022 |
| HP            | EliteBook 8460p             | [26f646cca0](https://linux-hardware.org/?probe=26f646cca0) | Aug 17, 2022 |
| HP            | EliteBook 8460p             | [98b5311ef6](https://linux-hardware.org/?probe=98b5311ef6) | Aug 17, 2022 |
| Lenovo        | ThinkPad X131e 33672K5      | [e32eeecfaa](https://linux-hardware.org/?probe=e32eeecfaa) | Aug 15, 2022 |
| Apple         | MacBookAir6,2               | [2c210a5825](https://linux-hardware.org/?probe=2c210a5825) | Aug 14, 2022 |
| Toshiba       | Satellite L500              | [0d58c17039](https://linux-hardware.org/?probe=0d58c17039) | Aug 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [26c131aca1](https://linux-hardware.org/?probe=26c131aca1) | Aug 13, 2022 |
| HP            | OMEN Laptop 15-ek0xxx       | [662f0801b7](https://linux-hardware.org/?probe=662f0801b7) | Aug 12, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | [166edbd7db](https://linux-hardware.org/?probe=166edbd7db) | Aug 12, 2022 |
| Dell          | Latitude 6430U              | [d21ca8c2e6](https://linux-hardware.org/?probe=d21ca8c2e6) | Aug 11, 2022 |
| HP            | ProBook 430 G5              | [72a09e7b69](https://linux-hardware.org/?probe=72a09e7b69) | Aug 05, 2022 |
| Lenovo        | XiaoXinPro 16 ARH7 82SN     | [abaec227ae](https://linux-hardware.org/?probe=abaec227ae) | Aug 05, 2022 |
| Lenovo        | XiaoXinPro 16 ARH7 82SN     | [a1effa04c3](https://linux-hardware.org/?probe=a1effa04c3) | Aug 05, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [209cd4bc66](https://linux-hardware.org/?probe=209cd4bc66) | Aug 05, 2022 |
| Acer          | Nitro AN515-52              | [8b737740c3](https://linux-hardware.org/?probe=8b737740c3) | Aug 05, 2022 |
| Acer          | Aspire A515-55              | [3ef0714d78](https://linux-hardware.org/?probe=3ef0714d78) | Aug 04, 2022 |
| Toshiba       | Satellite Pro L670          | [302749341d](https://linux-hardware.org/?probe=302749341d) | Aug 03, 2022 |
| Dell          | XPS 9320                    | [9b24b29553](https://linux-hardware.org/?probe=9b24b29553) | Aug 03, 2022 |
| Toshiba       | Satellite Pro L670          | [e6189ba78c](https://linux-hardware.org/?probe=e6189ba78c) | Aug 02, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IHU5 8... | [a67d881d6f](https://linux-hardware.org/?probe=a67d881d6f) | Aug 02, 2022 |
| HP            | EliteBook 2570p             | [b352b7e051](https://linux-hardware.org/?probe=b352b7e051) | Aug 02, 2022 |
| Apple         | MacBook9,1                  | [77687a9bac](https://linux-hardware.org/?probe=77687a9bac) | Aug 02, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [370b872aa5](https://linux-hardware.org/?probe=370b872aa5) | Aug 01, 2022 |
| Acer          | ConceptD CN315-71P          | [c7ed484a1f](https://linux-hardware.org/?probe=c7ed484a1f) | Jul 30, 2022 |
| Dell          | Inspiron M5010              | [bd4cf45b33](https://linux-hardware.org/?probe=bd4cf45b33) | Jul 30, 2022 |
| Acer          | Aspire 5742G                | [e42501aacb](https://linux-hardware.org/?probe=e42501aacb) | Jul 28, 2022 |
| ASUSTek       | X555YA                      | [ddd00fbeea](https://linux-hardware.org/?probe=ddd00fbeea) | Jul 28, 2022 |
| Dell          | Latitude E7250              | [26a8591f1d](https://linux-hardware.org/?probe=26a8591f1d) | Jul 27, 2022 |
| HP            | Laptop 17-cp0xxx            | [761563e485](https://linux-hardware.org/?probe=761563e485) | Jul 27, 2022 |
| Apple         | MacBookAir7,2               | [5e7b9f2b14](https://linux-hardware.org/?probe=5e7b9f2b14) | Jul 26, 2022 |
| Dell          | Latitude 3400               | [3412e8deac](https://linux-hardware.org/?probe=3412e8deac) | Jul 26, 2022 |
| Lenovo        | G570 4334                   | [e4c223e83e](https://linux-hardware.org/?probe=e4c223e83e) | Jul 25, 2022 |
| Apple         | MacBookAir6,1               | [ede7f6cdae](https://linux-hardware.org/?probe=ede7f6cdae) | Jul 23, 2022 |
| Acer          | Nitro AN515-55              | [85f2ffe45a](https://linux-hardware.org/?probe=85f2ffe45a) | Jul 22, 2022 |
| Acer          | ConceptD CN315-71P          | [2723b19c18](https://linux-hardware.org/?probe=2723b19c18) | Jul 22, 2022 |
| Google        | Peppy                       | [3bfdae8e5e](https://linux-hardware.org/?probe=3bfdae8e5e) | Jul 21, 2022 |
| Acer          | Aspire One 753              | [eff74923d7](https://linux-hardware.org/?probe=eff74923d7) | Jul 21, 2022 |
| Dell          | Latitude 5430               | [f02c4072c1](https://linux-hardware.org/?probe=f02c4072c1) | Jul 21, 2022 |
| Acer          | Aspire R3-131T              | [c3722806fe](https://linux-hardware.org/?probe=c3722806fe) | Jul 21, 2022 |
| Apple         | MacBookPro9,2               | [add1e46d7e](https://linux-hardware.org/?probe=add1e46d7e) | Jul 20, 2022 |
| Dell          | Inspiron MM061              | [2360c35ac1](https://linux-hardware.org/?probe=2360c35ac1) | Jul 20, 2022 |
| Dell          | Inspiron MM061              | [5cb9487776](https://linux-hardware.org/?probe=5cb9487776) | Jul 20, 2022 |
| Dell          | Inspiron 1545               | [b0e3b75c3b](https://linux-hardware.org/?probe=b0e3b75c3b) | Jul 19, 2022 |
| Acer          | TravelMate 8572T            | [54e7b50fc7](https://linux-hardware.org/?probe=54e7b50fc7) | Jul 18, 2022 |
| Alienware     | x17 R1                      | [9fc2d6416d](https://linux-hardware.org/?probe=9fc2d6416d) | Jul 16, 2022 |
| Apple         | MacBookAir7,2               | [a1a565d211](https://linux-hardware.org/?probe=a1a565d211) | Jul 16, 2022 |
| HP            | Spectre 13-SMB Pro Ultra... | [5fd8a1dcf4](https://linux-hardware.org/?probe=5fd8a1dcf4) | Jul 15, 2022 |
| Acer          | ConceptD CN315-71P          | [de83d4ef43](https://linux-hardware.org/?probe=de83d4ef43) | Jul 15, 2022 |
| Acer          | ConceptD CN315-71P          | [01e6c30eff](https://linux-hardware.org/?probe=01e6c30eff) | Jul 15, 2022 |
| Dell          | Inspiron 16 Plus 7620       | [73be4f7864](https://linux-hardware.org/?probe=73be4f7864) | Jul 14, 2022 |
| Acer          | Nitro AN515-56              | [2418745195](https://linux-hardware.org/?probe=2418745195) | Jul 14, 2022 |
| Dell          | Inspiron M5010              | [56be64f444](https://linux-hardware.org/?probe=56be64f444) | Jul 14, 2022 |
| ASUSTek       | GL702ZC                     | [755f571a3e](https://linux-hardware.org/?probe=755f571a3e) | Jul 14, 2022 |
| Dell          | XPS 13 9360                 | [ef3bc84295](https://linux-hardware.org/?probe=ef3bc84295) | Jul 13, 2022 |
| Acer          | Aspire R3-131T              | [4126a95603](https://linux-hardware.org/?probe=4126a95603) | Jul 13, 2022 |
| Apple         | MacBook9,1                  | [0ce6078768](https://linux-hardware.org/?probe=0ce6078768) | Jul 12, 2022 |
| Apple         | MacBookPro10,2              | [facbace782](https://linux-hardware.org/?probe=facbace782) | Jul 12, 2022 |
| Acer          | Aspire 1830T                | [d2ff08ade8](https://linux-hardware.org/?probe=d2ff08ade8) | Jul 10, 2022 |
| HP            | EliteBook 8470p             | [c048bb9697](https://linux-hardware.org/?probe=c048bb9697) | Jul 09, 2022 |
| Apple         | MacBookPro9,2               | [663a6c9413](https://linux-hardware.org/?probe=663a6c9413) | Jul 08, 2022 |
| Acer          | Aspire R3-131T              | [749a597089](https://linux-hardware.org/?probe=749a597089) | Jul 08, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3460A... | [e34a9c3166](https://linux-hardware.org/?probe=e34a9c3166) | Jul 08, 2022 |
| HP            | EliteBook 850 G1            | [1a2485b399](https://linux-hardware.org/?probe=1a2485b399) | Jul 06, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [ce6d3ec137](https://linux-hardware.org/?probe=ce6d3ec137) | Jul 06, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [e24a6dd845](https://linux-hardware.org/?probe=e24a6dd845) | Jul 05, 2022 |
| HP            | EliteBook 840 G6            | [d6dccd6ed7](https://linux-hardware.org/?probe=d6dccd6ed7) | Jul 05, 2022 |
| HUAWEI        | KLVD-WXX9                   | [422a12c217](https://linux-hardware.org/?probe=422a12c217) | Jul 05, 2022 |
| HP            | Pavilion g6                 | [0cd693879d](https://linux-hardware.org/?probe=0cd693879d) | Jul 05, 2022 |
| Acer          | ConceptD CN315-71P          | [76d6073818](https://linux-hardware.org/?probe=76d6073818) | Jul 05, 2022 |
| Dell          | Precision M4700             | [48cbbf8dd2](https://linux-hardware.org/?probe=48cbbf8dd2) | Jul 05, 2022 |
| Acer          | Aspire R3-131T              | [748f42be21](https://linux-hardware.org/?probe=748f42be21) | Jul 05, 2022 |
| Apple         | MacBookPro10,2              | [40d0cb89c5](https://linux-hardware.org/?probe=40d0cb89c5) | Jul 04, 2022 |
| HP            | EliteBook 8470p             | [4600681149](https://linux-hardware.org/?probe=4600681149) | Jul 03, 2022 |
| HP            | EliteBook 8470p             | [85c5a62101](https://linux-hardware.org/?probe=85c5a62101) | Jul 03, 2022 |
| Acer          | Aspire A315-21G             | [bcc3835be5](https://linux-hardware.org/?probe=bcc3835be5) | Jul 03, 2022 |
| Acer          | Aspire A315-21G             | [5f3197f581](https://linux-hardware.org/?probe=5f3197f581) | Jul 03, 2022 |
| Acer          | Swift SF114-34              | [dd9610011c](https://linux-hardware.org/?probe=dd9610011c) | Jul 02, 2022 |
| Apple         | MacBookPro9,2               | [4f6364d861](https://linux-hardware.org/?probe=4f6364d861) | Jul 02, 2022 |
| Dell          | Inspiron M5010              | [14b9aa33d2](https://linux-hardware.org/?probe=14b9aa33d2) | Jul 01, 2022 |
| HP            | EliteBook 8470p             | [cd488e4f64](https://linux-hardware.org/?probe=cd488e4f64) | Jun 30, 2022 |
| HP            | EliteBook 8470p             | [52dfa0a4ee](https://linux-hardware.org/?probe=52dfa0a4ee) | Jun 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [3a423eae14](https://linux-hardware.org/?probe=3a423eae14) | Jun 30, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | [1b5babe2aa](https://linux-hardware.org/?probe=1b5babe2aa) | Jun 29, 2022 |
| AMI           | Intel                       | [2b592e2f4a](https://linux-hardware.org/?probe=2b592e2f4a) | Jun 29, 2022 |
| Dell          | Latitude 5430               | [119502eddb](https://linux-hardware.org/?probe=119502eddb) | Jun 29, 2022 |
| Dell          | G3 3500                     | [0df1b9607c](https://linux-hardware.org/?probe=0df1b9607c) | Jun 27, 2022 |
| HUAWEI        | KLVD-WXX9                   | [b947b14fe4](https://linux-hardware.org/?probe=b947b14fe4) | Jun 27, 2022 |
| Alienware     | 14                          | [8846f2e474](https://linux-hardware.org/?probe=8846f2e474) | Jun 24, 2022 |
| Apple         | MacBook9,1                  | [e6f1068c91](https://linux-hardware.org/?probe=e6f1068c91) | Jun 24, 2022 |
| HP            | Presario CQ62               | [2f136051c9](https://linux-hardware.org/?probe=2f136051c9) | Jun 24, 2022 |
| HP            | Presario CQ62               | [9beeb6d3c2](https://linux-hardware.org/?probe=9beeb6d3c2) | Jun 23, 2022 |
| Lenovo        | ThinkPad E490s 20NG0002A... | [4cce05dc1c](https://linux-hardware.org/?probe=4cce05dc1c) | Jun 23, 2022 |
| Apple         | MacBook9,1                  | [3656b8227f](https://linux-hardware.org/?probe=3656b8227f) | Jun 23, 2022 |
| Toshiba       | TECRA A40-D                 | [6307594332](https://linux-hardware.org/?probe=6307594332) | Jun 23, 2022 |
| Acer          | Nitro AN515-55              | [bc159b637c](https://linux-hardware.org/?probe=bc159b637c) | Jun 22, 2022 |
| HP            | 250 G6 Notebook PC          | [30d0a46d81](https://linux-hardware.org/?probe=30d0a46d81) | Jun 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [f013ebb91b](https://linux-hardware.org/?probe=f013ebb91b) | Jun 20, 2022 |
| Acer          | Iconia                      | [2d1f1a2c32](https://linux-hardware.org/?probe=2d1f1a2c32) | Jun 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [b3da04a3af](https://linux-hardware.org/?probe=b3da04a3af) | Jun 20, 2022 |
| Framework     | Laptop                      | [f5ece7ce85](https://linux-hardware.org/?probe=f5ece7ce85) | Jun 19, 2022 |
| Apple         | MacBookPro11,1              | [b88b88ba84](https://linux-hardware.org/?probe=b88b88ba84) | Jun 19, 2022 |
| Apple         | MacBookPro11,1              | [ec132b0ba5](https://linux-hardware.org/?probe=ec132b0ba5) | Jun 19, 2022 |
| Acer          | ConceptD CN315-71P          | [66d09f029f](https://linux-hardware.org/?probe=66d09f029f) | Jun 18, 2022 |
| Dell          | Precision 5540              | [6d3f2c188b](https://linux-hardware.org/?probe=6d3f2c188b) | Jun 17, 2022 |
| Acer          | ConceptD CN315-71P          | [9b162f339b](https://linux-hardware.org/?probe=9b162f339b) | Jun 16, 2022 |
| HUAWEI        | KLVD-WXX9                   | [4c97b8cc3a](https://linux-hardware.org/?probe=4c97b8cc3a) | Jun 16, 2022 |
| Alienware     | m15 R7                      | [9775a12e11](https://linux-hardware.org/?probe=9775a12e11) | Jun 16, 2022 |
| Acer          | Nitro AN515-55              | [bb631825e3](https://linux-hardware.org/?probe=bb631825e3) | Jun 15, 2022 |
| Timi          | Redmi Book Pro 15 2022      | [76fd9cba2e](https://linux-hardware.org/?probe=76fd9cba2e) | Jun 15, 2022 |
| Timi          | Redmi Book Pro 15 2022      | [b3259c0af4](https://linux-hardware.org/?probe=b3259c0af4) | Jun 14, 2022 |
| MSI           | Modern 15 A5M               | [bd16d5829c](https://linux-hardware.org/?probe=bd16d5829c) | Jun 14, 2022 |
| Apple         | MacBookPro11,1              | [57b90afcda](https://linux-hardware.org/?probe=57b90afcda) | Jun 14, 2022 |
| Dell          | Vostro 1500                 | [748a8a831b](https://linux-hardware.org/?probe=748a8a831b) | Jun 12, 2022 |
| HP            | Compaq 6730b                | [dd94c9145b](https://linux-hardware.org/?probe=dd94c9145b) | Jun 11, 2022 |
| ASUSTek       | Unknown                     | [1cc4adfa36](https://linux-hardware.org/?probe=1cc4adfa36) | Jun 09, 2022 |
| Alienware     | x17 R2                      | [78b867a06e](https://linux-hardware.org/?probe=78b867a06e) | Jun 08, 2022 |
| Lenovo        | ThinkPad T410 2522PT3       | [75d6b8489b](https://linux-hardware.org/?probe=75d6b8489b) | Jun 08, 2022 |
| Acer          | Aspire R3-131T              | [1dab354de2](https://linux-hardware.org/?probe=1dab354de2) | Jun 07, 2022 |
| Acer          | Nitro AN515-55              | [4ab9f94abe](https://linux-hardware.org/?probe=4ab9f94abe) | Jun 06, 2022 |
| Lenovo        | ThinkPad Edge E531 6885C... | [d98f987b46](https://linux-hardware.org/?probe=d98f987b46) | Jun 06, 2022 |
| Lenovo        | ThinkPad T470s 20HGS2KW1... | [686fcbebd3](https://linux-hardware.org/?probe=686fcbebd3) | Jun 06, 2022 |
| Lenovo        | Yoga710-14ISK 80TY          | [116abb675e](https://linux-hardware.org/?probe=116abb675e) | Jun 06, 2022 |
| Lenovo        | ThinkPad Edge E531 6885C... | [1b09ad54c8](https://linux-hardware.org/?probe=1b09ad54c8) | Jun 05, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [57e7433cc5](https://linux-hardware.org/?probe=57e7433cc5) | Jun 04, 2022 |
| Lenovo        | IdeaPad L340-17IWL 81M0     | [b5bb3c0725](https://linux-hardware.org/?probe=b5bb3c0725) | Jun 02, 2022 |
| Apple         | MacBookAir4,2               | [86902cb11f](https://linux-hardware.org/?probe=86902cb11f) | Jun 02, 2022 |
| Dell          | G15 5515                    | [24ddbd70dc](https://linux-hardware.org/?probe=24ddbd70dc) | Jun 02, 2022 |
| HP            | 250 G6 Notebook PC          | [878274dbce](https://linux-hardware.org/?probe=878274dbce) | Jun 02, 2022 |
| Acer          | Aspire A315-58              | [b63e54900e](https://linux-hardware.org/?probe=b63e54900e) | Jun 02, 2022 |
| Dell          | Latitude E6540              | [9cbdc3f892](https://linux-hardware.org/?probe=9cbdc3f892) | Jun 02, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [ae39e96b1a](https://linux-hardware.org/?probe=ae39e96b1a) | Jun 01, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 D... | [57f540db26](https://linux-hardware.org/?probe=57f540db26) | Jun 01, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [6378f52a92](https://linux-hardware.org/?probe=6378f52a92) | May 31, 2022 |
| Dell          | Inspiron 5770               | [02b32c935c](https://linux-hardware.org/?probe=02b32c935c) | May 31, 2022 |
| IT Channel... | PA70Hx                      | [091ad22c2d](https://linux-hardware.org/?probe=091ad22c2d) | May 30, 2022 |
| Apple         | MacBookPro9,1               | [6fe2c4a416](https://linux-hardware.org/?probe=6fe2c4a416) | May 29, 2022 |
| HP            | EW7-I7D22875GR1             | [e34608096b](https://linux-hardware.org/?probe=e34608096b) | May 29, 2022 |
| HP            | EW7-I7D22875GR1             | [d21454c335](https://linux-hardware.org/?probe=d21454c335) | May 29, 2022 |
| MSI           | GT70 2OC/2OD                | [43144c3166](https://linux-hardware.org/?probe=43144c3166) | May 28, 2022 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [37d87b9245](https://linux-hardware.org/?probe=37d87b9245) | May 27, 2022 |
| Toshiba       | Satellite P850              | [9ec49310ff](https://linux-hardware.org/?probe=9ec49310ff) | May 25, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [00baf8a2ff](https://linux-hardware.org/?probe=00baf8a2ff) | May 24, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [32f7f3aa4b](https://linux-hardware.org/?probe=32f7f3aa4b) | May 24, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [43a374c1d4](https://linux-hardware.org/?probe=43a374c1d4) | May 23, 2022 |
| Acer          | Nitro AN515-45              | [293712cc51](https://linux-hardware.org/?probe=293712cc51) | May 23, 2022 |
| Apple         | MacBookPro6,1               | [40d33cea3f](https://linux-hardware.org/?probe=40d33cea3f) | May 23, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [1d8684d1f5](https://linux-hardware.org/?probe=1d8684d1f5) | May 23, 2022 |
| Gigabyte      | P34V5                       | [6fa844b91e](https://linux-hardware.org/?probe=6fa844b91e) | May 23, 2022 |
| Gigabyte      | P34V5                       | [3ad8e4b239](https://linux-hardware.org/?probe=3ad8e4b239) | May 23, 2022 |
| Toshiba       | TECRA R850                  | [aa0bfd6c6a](https://linux-hardware.org/?probe=aa0bfd6c6a) | May 22, 2022 |
| Dell          | G3 3500                     | [49f86cc226](https://linux-hardware.org/?probe=49f86cc226) | May 22, 2022 |
| Dell          | Inspiron 1545               | [890010e793](https://linux-hardware.org/?probe=890010e793) | May 21, 2022 |
| Lenovo        | ThinkPad E595 20NFA000AU    | [5d150789cb](https://linux-hardware.org/?probe=5d150789cb) | May 19, 2022 |
| Dell          | Inspiron 7572               | [b7747e3ea4](https://linux-hardware.org/?probe=b7747e3ea4) | May 19, 2022 |
| Dell          | XPS 13 7390                 | [98752f9fb4](https://linux-hardware.org/?probe=98752f9fb4) | May 18, 2022 |
| Acer          | Aspire A515-55              | [c01f14c77f](https://linux-hardware.org/?probe=c01f14c77f) | May 18, 2022 |
| Dell          | Latitude E7450              | [26b07c8dfc](https://linux-hardware.org/?probe=26b07c8dfc) | May 18, 2022 |
| Toshiba       | Satellite C850              | [5927aac0b7](https://linux-hardware.org/?probe=5927aac0b7) | May 17, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [d4f9f894b6](https://linux-hardware.org/?probe=d4f9f894b6) | May 16, 2022 |
| Dell          | Inspiron 5570               | [faf97fa9a0](https://linux-hardware.org/?probe=faf97fa9a0) | May 16, 2022 |
| Gigabyte      | A7 K1                       | [9cd1ec32e4](https://linux-hardware.org/?probe=9cd1ec32e4) | May 16, 2022 |
| Dell          | XPS 15 9560                 | [04f0e074cb](https://linux-hardware.org/?probe=04f0e074cb) | May 14, 2022 |
| Toshiba       | Satellite L50-A             | [30a7bebcd3](https://linux-hardware.org/?probe=30a7bebcd3) | May 14, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [6251446c92](https://linux-hardware.org/?probe=6251446c92) | May 13, 2022 |
| Dell          | Inspiron 15 3515            | [dd8e112250](https://linux-hardware.org/?probe=dd8e112250) | May 12, 2022 |
| HP            | Pavilion g6                 | [5662b515c3](https://linux-hardware.org/?probe=5662b515c3) | May 12, 2022 |
| Acer          | Aspire V5-573G              | [4477112f3a](https://linux-hardware.org/?probe=4477112f3a) | May 11, 2022 |
| Lenovo        | ThinkPad E570 20H5CTO1WW    | [a22c347eaf](https://linux-hardware.org/?probe=a22c347eaf) | May 11, 2022 |
| HP            | 250 G6 Notebook PC          | [f2f010a36d](https://linux-hardware.org/?probe=f2f010a36d) | May 11, 2022 |
| Apple         | MacBookPro12,1              | [0d9616886e](https://linux-hardware.org/?probe=0d9616886e) | May 11, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [ce3addb8a4](https://linux-hardware.org/?probe=ce3addb8a4) | May 10, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [7d146e5dec](https://linux-hardware.org/?probe=7d146e5dec) | May 10, 2022 |
| Apple         | MacBookPro7,1               | [7ff6997105](https://linux-hardware.org/?probe=7ff6997105) | May 08, 2022 |
| Dell          | Studio XPS 1645             | [0d213120b4](https://linux-hardware.org/?probe=0d213120b4) | May 08, 2022 |
| HP            | Compaq Presario CQ60        | [9d27bd494e](https://linux-hardware.org/?probe=9d27bd494e) | May 08, 2022 |
| HP            | Folio 13 - 2000             | [e859aed666](https://linux-hardware.org/?probe=e859aed666) | May 06, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [3d07e8a45e](https://linux-hardware.org/?probe=3d07e8a45e) | May 05, 2022 |
| Dell          | Studio 1555                 | [c02949a388](https://linux-hardware.org/?probe=c02949a388) | May 05, 2022 |
| Acer          | Aspire A315-34              | [3ed5a6d961](https://linux-hardware.org/?probe=3ed5a6d961) | May 04, 2022 |
| Lenovo        | ThinkPad E595 20NFA000AU    | [43dcfa4094](https://linux-hardware.org/?probe=43dcfa4094) | May 03, 2022 |
| Framework     | Laptop                      | [0d35134041](https://linux-hardware.org/?probe=0d35134041) | May 02, 2022 |
| HP            | 250 G5 Notebook PC          | [0e6717d54b](https://linux-hardware.org/?probe=0e6717d54b) | May 02, 2022 |
| HP            | EliteBook 850 G3            | [ab86c0118b](https://linux-hardware.org/?probe=ab86c0118b) | May 02, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [7206b41211](https://linux-hardware.org/?probe=7206b41211) | May 01, 2022 |
| Lenovo        | Legion Y9000X 2020 81TH     | [c335cbb270](https://linux-hardware.org/?probe=c335cbb270) | May 01, 2022 |
| HUAWEI        | BOM-WXX9                    | [faa7213f5c](https://linux-hardware.org/?probe=faa7213f5c) | Apr 30, 2022 |
| Apple         | MacBookPro8,1               | [8826e1d451](https://linux-hardware.org/?probe=8826e1d451) | Apr 30, 2022 |
| HP            | ZBook 15 G6                 | [f948921cba](https://linux-hardware.org/?probe=f948921cba) | Apr 30, 2022 |
| Dell          | Inspiron 3543               | [6165b0554d](https://linux-hardware.org/?probe=6165b0554d) | Apr 28, 2022 |
| Lenovo        | ThinkPad X250 20CLS52P0F    | [a4d291ccda](https://linux-hardware.org/?probe=a4d291ccda) | Apr 27, 2022 |
| Acer          | Aspire 5750G                | [3a96bf8237](https://linux-hardware.org/?probe=3a96bf8237) | Apr 27, 2022 |
| HP            | ProBook 4710s               | [03d5c4c5b2](https://linux-hardware.org/?probe=03d5c4c5b2) | Apr 25, 2022 |
| HP            | Laptop 15s-eq2xxx           | [981d5e03b3](https://linux-hardware.org/?probe=981d5e03b3) | Apr 25, 2022 |
| HP            | Laptop 15s-eq2xxx           | [0b3a1039fb](https://linux-hardware.org/?probe=0b3a1039fb) | Apr 25, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [b1b4ea439d](https://linux-hardware.org/?probe=b1b4ea439d) | Apr 25, 2022 |
| HP            | ProBook 470 G5              | [e0def5bddc](https://linux-hardware.org/?probe=e0def5bddc) | Apr 25, 2022 |
| HUAWEI        | BOM-WXX9                    | [a771d771b2](https://linux-hardware.org/?probe=a771d771b2) | Apr 24, 2022 |
| HUAWEI        | BOM-WXX9                    | [1a195527a4](https://linux-hardware.org/?probe=1a195527a4) | Apr 24, 2022 |
| Dell          | Latitude E5500              | [c954cb4ba4](https://linux-hardware.org/?probe=c954cb4ba4) | Apr 24, 2022 |
| Dell          | Latitude E5500              | [ab88dc2482](https://linux-hardware.org/?probe=ab88dc2482) | Apr 24, 2022 |
| HP            | EliteBook 2530p             | [bfaeba4483](https://linux-hardware.org/?probe=bfaeba4483) | Apr 22, 2022 |
| Dell          | Latitude 7490               | [2b8d24f8ae](https://linux-hardware.org/?probe=2b8d24f8ae) | Apr 22, 2022 |
| HP            | EliteBook 2530p             | [a68c57ea30](https://linux-hardware.org/?probe=a68c57ea30) | Apr 22, 2022 |
| MSI           | GS65 Stealth Thin 8RE       | [cbb3f353a5](https://linux-hardware.org/?probe=cbb3f353a5) | Apr 21, 2022 |
| HP            | Laptop 14s-dk0xxx           | [ec7bef597a](https://linux-hardware.org/?probe=ec7bef597a) | Apr 20, 2022 |
| HP            | Laptop 14s-dk0xxx           | [1edc356b52](https://linux-hardware.org/?probe=1edc356b52) | Apr 20, 2022 |
| Lenovo        | ThinkPad T590 20N5S2NC0V    | [d6bf3c27ef](https://linux-hardware.org/?probe=d6bf3c27ef) | Apr 20, 2022 |
| Dell          | XPS 13 7390                 | [80c38b1425](https://linux-hardware.org/?probe=80c38b1425) | Apr 19, 2022 |
| Timi          | A35S                        | [e7d8adf61f](https://linux-hardware.org/?probe=e7d8adf61f) | Apr 19, 2022 |
| Razer         | Blade 15 Base Model (Ear... | [4c845dc459](https://linux-hardware.org/?probe=4c845dc459) | Apr 19, 2022 |
| HP            | 250 G5 Notebook PC          | [5cb8325ed4](https://linux-hardware.org/?probe=5cb8325ed4) | Apr 18, 2022 |
| Acer          | Aspire R3-131T              | [48f584f713](https://linux-hardware.org/?probe=48f584f713) | Apr 17, 2022 |
| Apple         | MacBookPro5,4               | [918fef81c3](https://linux-hardware.org/?probe=918fef81c3) | Apr 17, 2022 |
| Dell          | Studio XPS 1645             | [6e722019b4](https://linux-hardware.org/?probe=6e722019b4) | Apr 16, 2022 |
| Dell          | Inspiron 1012               | [4659a757bf](https://linux-hardware.org/?probe=4659a757bf) | Apr 15, 2022 |
| Dell          | Inspiron 1012               | [ebfcf670fc](https://linux-hardware.org/?probe=ebfcf670fc) | Apr 15, 2022 |
| Lenovo        | ThinkPad E570 20H5CTO1WW    | [c43bc1fcba](https://linux-hardware.org/?probe=c43bc1fcba) | Apr 15, 2022 |
| Dell          | Latitude E6530              | [d6f985e2ca](https://linux-hardware.org/?probe=d6f985e2ca) | Apr 15, 2022 |
| Dell          | Latitude E6230              | [19e2fe3c97](https://linux-hardware.org/?probe=19e2fe3c97) | Apr 14, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Australia/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 201       | 11.83%  |
| Ubuntu 18.04                 | 82        | 4.83%   |
| Ubuntu 22.04                 | 81        | 4.77%   |
| Pop!_OS 22.04                | 55        | 3.24%   |
| Debian 11                    | 37        | 2.18%   |
| Arch Rolling                 | 34        | 2%      |
| Zorin 16                     | 31        | 1.82%   |
| KDE neon 20.04               | 31        | 1.82%   |
| Linux Mint 20.2              | 29        | 1.71%   |
| Fedora 36                    | 29        | 1.71%   |
| Linux Mint 20.3              | 28        | 1.65%   |
| Pop!_OS 21.04                | 27        | 1.59%   |
| Fedora 38                    | 26        | 1.53%   |
| Pop!_OS 20.04                | 25        | 1.47%   |
| OpenMandriva 4.3             | 25        | 1.47%   |
| Manjaro                      | 24        | 1.41%   |
| Arch                         | 24        | 1.41%   |
| Fedora 37                    | 23        | 1.35%   |
| Linux Mint 20                | 22        | 1.29%   |
| Ubuntu 20.10                 | 21        | 1.24%   |
| OpenMandriva 4.2             | 20        | 1.18%   |
| Linux Mint 21.1              | 20        | 1.18%   |
| Linux Mint 20.1              | 20        | 1.18%   |
| Pop!_OS 20.10                | 19        | 1.12%   |
| ArcoLinux Rolling            | 19        | 1.12%   |
| Ubuntu 21.10                 | 18        | 1.06%   |
| Ubuntu 19.04                 | 18        | 1.06%   |
| Ubuntu 23.04                 | 17        | 1%      |
| Ubuntu 19.10                 | 17        | 1%      |
| Zorin 15                     | 16        | 0.94%   |
| Fedora 33                    | 16        | 0.94%   |
| Ubuntu 21.04                 | 14        | 0.82%   |
| Fedora 35                    | 14        | 0.82%   |
| Xubuntu 18.04                | 13        | 0.77%   |
| Ubuntu 22.10                 | 13        | 0.77%   |
| OpenMandriva 23.03           | 13        | 0.77%   |
| Linux Mint 21                | 13        | 0.77%   |
| KDE neon 22.04               | 13        | 0.77%   |
| Fedora 32                    | 12        | 0.71%   |
| openSUSE Tumbleweed-XXXXXXXX | 11        | 0.65%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 464       | 29.18%  |
| Linux Mint    | 150       | 9.43%   |
| Pop!_OS       | 128       | 8.05%   |
| Fedora        | 120       | 7.55%   |
| OpenMandriva  | 88        | 5.53%   |
| Debian        | 65        | 4.09%   |
| Arch          | 57        | 3.58%   |
| Zorin         | 54        | 3.4%    |
| Manjaro       | 51        | 3.21%   |
| KDE neon      | 47        | 2.96%   |
| Xubuntu       | 36        | 2.26%   |
| Kubuntu       | 35        | 2.2%    |
| Kali          | 26        | 1.64%   |
| Elementary    | 25        | 1.57%   |
| ArcoLinux     | 19        | 1.19%   |
| Gentoo        | 17        | 1.07%   |
| openSUSE      | 15        | 0.94%   |
| Clear Linux   | 13        | 0.82%   |
| Lubuntu       | 12        | 0.75%   |
| Endless       | 12        | 0.75%   |
| Ubuntu Unity  | 11        | 0.69%   |
| SteamOS       | 10        | 0.63%   |
| ROSA          | 10        | 0.63%   |
| LMDE          | 10        | 0.63%   |
| Ubuntu MATE   | 9         | 0.57%   |
| EndeavourOS   | 9         | 0.57%   |
| Parrot        | 8         | 0.5%    |
| MX            | 8         | 0.5%    |
| Ubuntu Budgie | 6         | 0.38%   |
| LinuxFX       | 6         | 0.38%   |
| BlackPanther  | 6         | 0.38%   |
| Xero          | 4         | 0.25%   |
| Reborn OS     | 4         | 0.25%   |
| Nobara        | 4         | 0.25%   |
| TUXEDO OS     | 3         | 0.19%   |
| Solus         | 3         | 0.19%   |
| Oracle Linux  | 3         | 0.19%   |
| Void Linux    | 2         | 0.13%   |
| RHEL          | 2         | 0.13%   |
| PureOS        | 2         | 0.13%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 33        | 1.74%   |
| 5.16.7-desktop-1omv4003  | 24        | 1.26%   |
| 5.10.14-desktop-1omv4002 | 20        | 1.05%   |
| 5.4.0-58-generic         | 18        | 0.95%   |
| 5.4.0-26-generic         | 15        | 0.79%   |
| 5.15.0-56-generic        | 15        | 0.79%   |
| 5.4.0-40-generic         | 14        | 0.74%   |
| 5.11.0-7620-generic      | 14        | 0.74%   |
| 6.2.6-desktop-1omv2390   | 13        | 0.68%   |
| 6.2.6-76060206-generic   | 13        | 0.68%   |
| 5.4.0-29-generic         | 13        | 0.68%   |
| 5.4.0-48-generic         | 12        | 0.63%   |
| 5.15.0-58-generic        | 12        | 0.63%   |
| 5.11.0-38-generic        | 12        | 0.63%   |
| 6.2.0-20-generic         | 11        | 0.58%   |
| 5.17.5-76051705-generic  | 11        | 0.58%   |
| 5.11.0-37-generic        | 11        | 0.58%   |
| 5.11.0-27-generic        | 11        | 0.58%   |
| 6.1.1-desktop-1omv2290   | 10        | 0.53%   |
| 5.4.0-52-generic         | 10        | 0.53%   |
| 5.8.0-63-generic         | 9         | 0.47%   |
| 5.4.0-81-generic         | 9         | 0.47%   |
| 5.4.0-74-generic         | 9         | 0.47%   |
| 5.3.0-40-generic         | 9         | 0.47%   |
| 6.2.0-26-generic         | 8         | 0.42%   |
| 5.8.0-7630-generic       | 8         | 0.42%   |
| 5.8.0-59-generic         | 8         | 0.42%   |
| 5.4.0-7634-generic       | 8         | 0.42%   |
| 5.4.0-65-generic         | 8         | 0.42%   |
| 5.4.0-54-generic         | 8         | 0.42%   |
| 5.3.0-28-generic         | 8         | 0.42%   |
| 5.19.0-46-generic        | 8         | 0.42%   |
| 5.19.0-38-generic        | 8         | 0.42%   |
| 5.15.0-52-generic        | 8         | 0.42%   |
| 5.15.0-46-generic        | 8         | 0.42%   |
| 5.13.0-7620-generic      | 8         | 0.42%   |
| 5.13.0-40-generic        | 8         | 0.42%   |
| 5.11.0-40-generic        | 8         | 0.42%   |
| 5.0.0-13-generic         | 8         | 0.42%   |
| 6.2.0-35-generic         | 7         | 0.37%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 270       | 15.28%  |
| 5.15.0  | 134       | 7.58%   |
| 5.11.0  | 101       | 5.72%   |
| 5.13.0  | 85        | 4.81%   |
| 5.8.0   | 84        | 4.75%   |
| 4.15.0  | 70        | 3.96%   |
| 5.19.0  | 56        | 3.17%   |
| 5.3.0   | 52        | 2.94%   |
| 5.10.0  | 50        | 2.83%   |
| 6.2.0   | 49        | 2.77%   |
| 5.0.0   | 41        | 2.32%   |
| 4.18.0  | 31        | 1.75%   |
| 6.2.6   | 26        | 1.47%   |
| 5.16.7  | 25        | 1.41%   |
| 5.10.14 | 20        | 1.13%   |
| 5.17.5  | 17        | 0.96%   |
| 6.1.0   | 16        | 0.91%   |
| 6.1.1   | 14        | 0.79%   |
| 6.0.0   | 14        | 0.79%   |
| 6.5.0   | 11        | 0.62%   |
| 4.19.0  | 11        | 0.62%   |
| 6.0.12  | 10        | 0.57%   |
| 5.18.0  | 10        | 0.57%   |
| 5.18.10 | 8         | 0.45%   |
| 6.5.5   | 7         | 0.4%    |
| 6.4.6   | 7         | 0.4%    |
| 6.4.11  | 7         | 0.4%    |
| 6.0.9   | 7         | 0.4%    |
| 6.0.7   | 7         | 0.4%    |
| 5.14.0  | 7         | 0.4%    |
| 6.4.10  | 6         | 0.34%   |
| 5.18.12 | 6         | 0.34%   |
| 5.17.15 | 6         | 0.34%   |
| 6.4.0   | 5         | 0.28%   |
| 6.2.9   | 5         | 0.28%   |
| 6.1.11  | 5         | 0.28%   |
| 5.8.16  | 5         | 0.28%   |
| 5.16.11 | 5         | 0.28%   |
| 5.16.0  | 5         | 0.28%   |
| 5.15.72 | 5         | 0.28%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 294       | 16.96%  |
| 5.15    | 173       | 9.98%   |
| 5.11    | 115       | 6.64%   |
| 5.8     | 101       | 5.83%   |
| 5.13    | 99        | 5.71%   |
| 6.2     | 94        | 5.42%   |
| 5.10    | 94        | 5.42%   |
| 5.19    | 72        | 4.15%   |
| 4.15    | 70        | 4.04%   |
| 6.1     | 62        | 3.58%   |
| 5.16    | 58        | 3.35%   |
| 5.3     | 56        | 3.23%   |
| 6.0     | 53        | 3.06%   |
| 5.0     | 45        | 2.6%    |
| 6.4     | 41        | 2.37%   |
| 5.17    | 38        | 2.19%   |
| 5.18    | 37        | 2.14%   |
| 4.18    | 36        | 2.08%   |
| 6.5     | 29        | 1.67%   |
| 6.3     | 24        | 1.38%   |
| 5.6     | 19        | 1.1%    |
| 5.14    | 18        | 1.04%   |
| 5.9     | 17        | 0.98%   |
| 5.12    | 15        | 0.87%   |
| 4.19    | 14        | 0.81%   |
| 5.5     | 12        | 0.69%   |
| 5.7     | 11        | 0.63%   |
| 4.9     | 11        | 0.63%   |
| 5.2     | 5         | 0.29%   |
| 4.4     | 5         | 0.29%   |
| 4.1     | 3         | 0.17%   |
| 5.1     | 2         | 0.12%   |
| 4.20    | 2         | 0.12%   |
| 3.16    | 2         | 0.12%   |
| 3.10    | 2         | 0.12%   |
| 4.8     | 1         | 0.06%   |
| 4.14    | 1         | 0.06%   |
| 4.13    | 1         | 0.06%   |
| 4.11    | 1         | 0.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 1455      | 97.52%  |
| i686    | 32        | 2.14%   |
| aarch64 | 3         | 0.2%    |
| i586    | 2         | 0.13%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 720       | 45.11%  |
| KDE5            | 271       | 16.98%  |
| Unknown         | 150       | 9.4%    |
| X-Cinnamon      | 132       | 8.27%   |
| XFCE            | 118       | 7.39%   |
| MATE            | 35        | 2.19%   |
| KDE             | 32        | 2.01%   |
| Cinnamon        | 24        | 1.5%    |
| Pantheon        | 23        | 1.44%   |
| i3              | 14        | 0.88%   |
| Unity           | 13        | 0.81%   |
| LXQt            | 11        | 0.69%   |
| LXDE            | 9         | 0.56%   |
| Budgie          | 9         | 0.56%   |
| KDE4            | 8         | 0.5%    |
| Deepin          | 6         | 0.38%   |
| BunsenLabs      | 3         | 0.19%   |
| awesome         | 3         | 0.19%   |
| Openbox         | 2         | 0.13%   |
| GNOME Flashback | 2         | 0.13%   |
| GNOME Classic   | 2         | 0.13%   |
| sway            | 1         | 0.06%   |
| qtile           | 1         | 0.06%   |
| LeftWM          | 1         | 0.06%   |
| icewm           | 1         | 0.06%   |
| Hyprland        | 1         | 0.06%   |
| herbstluftwm    | 1         | 0.06%   |
| dwm             | 1         | 0.06%   |
| dusk            | 1         | 0.06%   |
| bspwm           | 1         | 0.06%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 1162      | 74.92%  |
| Wayland | 275       | 17.73%  |
| Unknown | 84        | 5.42%   |
| Tty     | 30        | 1.93%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 797       | 50.8%   |
| SDDM    | 214       | 13.64%  |
| GDM     | 180       | 11.47%  |
| GDM3    | 167       | 10.64%  |
| LightDM | 158       | 10.07%  |
| TDM     | 39        | 2.49%   |
| KDM     | 8         | 0.51%   |
| SLiM    | 2         | 0.13%   |
| LXDM    | 2         | 0.13%   |
| XDM     | 1         | 0.06%   |
| GREETD  | 1         | 0.06%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang         | Notebooks | Percent |
|--------------|-----------|---------|
| en_AU        | 1093      | 70.33%  |
| en_US        | 245       | 15.77%  |
| Unknown      | 135       | 8.69%   |
| C            | 35        | 2.25%   |
| en_GB        | 30        | 1.93%   |
| C.UTF8       | 4         | 0.26%   |
| zh_CN        | 1         | 0.06%   |
| ru_RU        | 1         | 0.06%   |
| POSIX        | 1         | 0.06%   |
| it_IT        | 1         | 0.06%   |
| fr_FR        | 1         | 0.06%   |
| es_ES        | 1         | 0.06%   |
| en_IN        | 1         | 0.06%   |
| en_GB.UTF-12 | 1         | 0.06%   |
| en_DK        | 1         | 0.06%   |
| en_CA        | 1         | 0.06%   |
| en_AU.UFT-8  | 1         | 0.06%   |
| de_DE        | 1         | 0.06%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 783       | 50.98%  |
| BIOS | 753       | 49.02%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 1152      | 74.61%  |
| Btrfs   | 165       | 10.69%  |
| Overlay | 99        | 6.41%   |
| Unknown | 39        | 2.53%   |
| Tmpfs   | 38        | 2.46%   |
| Xfs     | 21        | 1.36%   |
| Zfs     | 18        | 1.17%   |
| Ext2    | 5         | 0.32%   |
| XXXXXXX | 3         | 0.19%   |
| Ext3    | 3         | 0.19%   |
| F2fs    | 1         | 0.06%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 839       | 54.62%  |
| GPT     | 564       | 36.72%  |
| MBR     | 133       | 8.66%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1351      | 89%     |
| Yes       | 167       | 11%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1183      | 77.62%  |
| Yes       | 341       | 22.38%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 268       | 17.99%  |
| Dell                   | 256       | 17.18%  |
| Lenovo                 | 246       | 16.51%  |
| ASUSTek Computer       | 142       | 9.53%   |
| Acer                   | 134       | 8.99%   |
| Apple                  | 114       | 7.65%   |
| Toshiba                | 106       | 7.11%   |
| MSI                    | 38        | 2.55%   |
| Samsung Electronics    | 16        | 1.07%   |
| Alienware              | 16        | 1.07%   |
| Sony                   | 11        | 0.74%   |
| Notebook               | 10        | 0.67%   |
| Gigabyte Technology    | 10        | 0.67%   |
| Panasonic              | 9         | 0.6%    |
| Timi                   | 8         | 0.54%   |
| Valve                  | 7         | 0.47%   |
| Metabox                | 7         | 0.47%   |
| IT Channel Pty         | 7         | 0.47%   |
| HUAWEI                 | 7         | 0.47%   |
| Unknown                | 7         | 0.47%   |
| Razer                  | 6         | 0.4%    |
| Google                 | 6         | 0.4%    |
| System76               | 5         | 0.34%   |
| Intel Client Systems   | 5         | 0.34%   |
| Framework              | 4         | 0.27%   |
| AMI                    | 4         | 0.27%   |
| Medion                 | 3         | 0.2%    |
| LG Electronics         | 3         | 0.2%    |
| Kogan                  | 3         | 0.2%    |
| Fujitsu                | 3         | 0.2%    |
| Purism                 | 2         | 0.13%   |
| Pine Microsystems      | 2         | 0.13%   |
| LEADER                 | 2         | 0.13%   |
| IBM                    | 2         | 0.13%   |
| COM1                   | 2         | 0.13%   |
| Star Labs              | 1         | 0.07%   |
| Pendo Industries       | 1         | 0.07%   |
| ONE-NETBOOK TECHNOLOGY | 1         | 0.07%   |
| One Education          | 1         | 0.07%   |
| OEM                    | 1         | 0.07%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| HP Pavilion dv6                        | 18        | 1.21%   |
| HP Notebook                            | 14        | 0.94%   |
| HP Pavilion g6                         | 12        | 0.81%   |
| Apple MacBookPro9,2                    | 10        | 0.67%   |
| Apple MacBookPro8,1                    | 10        | 0.67%   |
| Apple MacBookAir7,2                    | 10        | 0.67%   |
| Unknown                                | 10        | 0.67%   |
| HP Pavilion 15                         | 9         | 0.6%    |
| Apple MacBookPro10,1                   | 9         | 0.6%    |
| Valve Jupiter                          | 7         | 0.47%   |
| Dell XPS 15 9570                       | 7         | 0.47%   |
| Dell XPS 13 9360                       | 7         | 0.47%   |
| Toshiba Satellite L850                 | 6         | 0.4%    |
| Lenovo ThinkPad T470s W10DG 20JTS0HT00 | 6         | 0.4%    |
| Apple MacBookPro11,1                   | 6         | 0.4%    |
| Acer ConceptD CN315-71P                | 6         | 0.4%    |
| Toshiba Satellite P750                 | 5         | 0.34%   |
| Dell XPS 15 9560                       | 5         | 0.34%   |
| Dell Latitude E7450                    | 5         | 0.34%   |
| Apple MacBookAir6,2                    | 5         | 0.34%   |
| Acer Aspire A315-22                    | 5         | 0.34%   |
| Acer Aspire 5750G                      | 5         | 0.34%   |
| Toshiba Satellite L750                 | 4         | 0.27%   |
| Toshiba Satellite L500                 | 4         | 0.27%   |
| Toshiba Satellite L50-A                | 4         | 0.27%   |
| Toshiba Satellite C660                 | 4         | 0.27%   |
| Lenovo IdeaPad 1 14IGL05 81VU          | 4         | 0.27%   |
| Lenovo G50-45 80E3                     | 4         | 0.27%   |
| HP Pavilion Notebook                   | 4         | 0.27%   |
| HP Pavilion dv7                        | 4         | 0.27%   |
| HP Laptop 15s-eq2xxx                   | 4         | 0.27%   |
| HP Laptop 15-db0xxx                    | 4         | 0.27%   |
| HP ENVY 17                             | 4         | 0.27%   |
| HP EliteBook Folio 9470m               | 4         | 0.27%   |
| HP EliteBook 8460p                     | 4         | 0.27%   |
| Dell XPS 17 9700                       | 4         | 0.27%   |
| Dell XPS 15 9550                       | 4         | 0.27%   |
| Dell XPS 15 9500                       | 4         | 0.27%   |
| Dell XPS 15 7590                       | 4         | 0.27%   |
| Dell XPS 13 9370                       | 4         | 0.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 154       | 10.34%  |
| Acer Aspire        | 94        | 6.31%   |
| Dell Latitude      | 87        | 5.84%   |
| Toshiba Satellite  | 84        | 5.64%   |
| HP Pavilion        | 70        | 4.7%    |
| Dell XPS           | 60        | 4.03%   |
| Dell Inspiron      | 56        | 3.76%   |
| HP EliteBook       | 52        | 3.49%   |
| Lenovo IdeaPad     | 48        | 3.22%   |
| HP ProBook         | 34        | 2.28%   |
| HP Laptop          | 27        | 1.81%   |
| Dell Precision     | 23        | 1.54%   |
| ASUS ZenBook       | 17        | 1.14%   |
| HP Notebook        | 14        | 0.94%   |
| HP ENVY            | 14        | 0.94%   |
| Lenovo Yoga        | 13        | 0.87%   |
| ASUS VivoBook      | 13        | 0.87%   |
| Apple MacBookPro10 | 13        | 0.87%   |
| Toshiba PORTEGE    | 12        | 0.81%   |
| ASUS ROG           | 12        | 0.81%   |
| Apple MacBookPro9  | 11        | 0.74%   |
| Apple MacBookPro11 | 11        | 0.74%   |
| Acer Swift         | 11        | 0.74%   |
| HP 250             | 10        | 0.67%   |
| Apple MacBookPro8  | 10        | 0.67%   |
| Apple MacBookAir7  | 10        | 0.67%   |
| Unknown            | 10        | 0.67%   |
| HP ZBook           | 9         | 0.6%    |
| HP Compaq          | 8         | 0.54%   |
| Dell Vostro        | 8         | 0.54%   |
| ASUS TUF           | 8         | 0.54%   |
| Apple MacBookAir6  | 8         | 0.54%   |
| Acer Nitro         | 8         | 0.54%   |
| Valve Jupiter      | 7         | 0.47%   |
| Toshiba TECRA      | 7         | 0.47%   |
| Lenovo Legion      | 7         | 0.47%   |
| HP OMEN            | 7         | 0.47%   |
| Razer Blade        | 6         | 0.4%    |
| Dell G3            | 6         | 0.4%    |
| Apple MacBookPro16 | 6         | 0.4%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 136       | 9.13%   |
| 2012    | 131       | 8.79%   |
| 2020    | 127       | 8.52%   |
| 2011    | 119       | 7.99%   |
| 2018    | 113       | 7.58%   |
| 2013    | 112       | 7.52%   |
| 2021    | 97        | 6.51%   |
| 2014    | 95        | 6.38%   |
| 2015    | 92        | 6.17%   |
| 2016    | 88        | 5.91%   |
| 2017    | 83        | 5.57%   |
| 2010    | 82        | 5.5%    |
| 2022    | 61        | 4.09%   |
| 2008    | 55        | 3.69%   |
| 2009    | 42        | 2.82%   |
| 2007    | 24        | 1.61%   |
| 2023    | 16        | 1.07%   |
| 2005    | 6         | 0.4%    |
| 2006    | 5         | 0.34%   |
| Unknown | 5         | 0.34%   |
| 2003    | 1         | 0.07%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1490      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 1344      | 89.36%  |
| Enabled  | 160       | 10.64%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1478      | 99.19%  |
| Yes  | 12        | 0.81%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 427       | 28.3%   |
| 16.01-24.0  | 313       | 20.74%  |
| 3.01-4.0    | 305       | 20.21%  |
| 8.01-16.0   | 228       | 15.11%  |
| 32.01-64.0  | 129       | 8.55%   |
| 1.01-2.0    | 55        | 3.64%   |
| 64.01-256.0 | 21        | 1.39%   |
| 24.01-32.0  | 12        | 0.8%    |
| 2.01-3.0    | 12        | 0.8%    |
| 0.51-1.0    | 4         | 0.27%   |
| 0.01-0.5    | 3         | 0.2%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 577       | 33.53%  |
| 2.01-3.0   | 481       | 27.95%  |
| 4.01-8.0   | 240       | 13.95%  |
| 3.01-4.0   | 223       | 12.96%  |
| 0.51-1.0   | 94        | 5.46%   |
| 8.01-16.0  | 79        | 4.59%   |
| 0.01-0.5   | 15        | 0.87%   |
| 16.01-24.0 | 8         | 0.46%   |
| 24.01-32.0 | 2         | 0.12%   |
| 0          | 2         | 0.12%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1095      | 70.69%  |
| 2      | 361       | 23.31%  |
| 3      | 61        | 3.94%   |
| 0      | 17        | 1.1%    |
| 4      | 11        | 0.71%   |
| 5      | 2         | 0.13%   |
| 8      | 1         | 0.06%   |
| 7      | 1         | 0.06%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 967       | 64.38%  |
| Yes       | 535       | 35.62%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1208      | 80.75%  |
| No        | 288       | 19.25%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1460      | 97.86%  |
| No        | 32        | 2.14%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1185      | 78.22%  |
| No        | 330       | 21.78%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| Australia | 1490      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Sydney         | 405       | 25.39%  |
| Melbourne      | 354       | 22.19%  |
| Brisbane       | 253       | 15.86%  |
| Perth          | 124       | 7.77%   |
| Adelaide       | 92        | 5.77%   |
| Canberra       | 29        | 1.82%   |
| Hobart         | 19        | 1.19%   |
| Launceston     | 10        | 0.63%   |
| Gold Coast     | 10        | 0.63%   |
| Richmond       | 7         | 0.44%   |
| Central Coast  | 7         | 0.44%   |
| Woolloongabba  | 6         | 0.38%   |
| Southport      | 6         | 0.38%   |
| Geelong        | 6         | 0.38%   |
| Wollongong     | 5         | 0.31%   |
| Parramatta     | 5         | 0.31%   |
| Newcastle      | 5         | 0.31%   |
| Mitcham        | 5         | 0.31%   |
| Alexandria     | 5         | 0.31%   |
| West End       | 4         | 0.25%   |
| Wahroonga      | 4         | 0.25%   |
| Traralgon      | 4         | 0.25%   |
| Townsville     | 4         | 0.25%   |
| Point Cook     | 4         | 0.25%   |
| Nyngan         | 4         | 0.25%   |
| Mandurah       | 4         | 0.25%   |
| Geraldton      | 4         | 0.25%   |
| Artarmon       | 4         | 0.25%   |
| Surry Hills    | 3         | 0.19%   |
| Spring Field   | 3         | 0.19%   |
| Parkdale       | 3         | 0.19%   |
| Mount Waverley | 3         | 0.19%   |
| Leinster       | 3         | 0.19%   |
| Hawthorn       | 3         | 0.19%   |
| Doncaster      | 3         | 0.19%   |
| Clifton Hill   | 3         | 0.19%   |
| Brighton       | 3         | 0.19%   |
| Ballarat       | 3         | 0.19%   |
| Warragul       | 2         | 0.13%   |
| Sandy Bay      | 2         | 0.13%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 339       | 445    | 18.18%  |
| WDC                         | 195       | 278    | 10.46%  |
| Seagate                     | 193       | 304    | 10.35%  |
| Toshiba                     | 156       | 227    | 8.36%   |
| SanDisk                     | 100       | 131    | 5.36%   |
| Unknown                     | 92        | 120    | 4.93%   |
| Intel                       | 75        | 114    | 4.02%   |
| Crucial                     | 73        | 97     | 3.91%   |
| SK hynix                    | 72        | 93     | 3.86%   |
| Kingston                    | 71        | 89     | 3.81%   |
| Apple                       | 69        | 95     | 3.7%    |
| Hitachi                     | 65        | 79     | 3.49%   |
| Micron Technology           | 53        | 67     | 2.84%   |
| HGST                        | 49        | 67     | 2.63%   |
| KIOXIA                      | 21        | 23     | 1.13%   |
| Fujitsu                     | 16        | 20     | 0.86%   |
| Phison                      | 14        | 20     | 0.75%   |
| A-DATA Technology           | 13        | 19     | 0.7%    |
| Phison Electronics          | 12        | 17     | 0.64%   |
| LITEON                      | 12        | 18     | 0.64%   |
| Micron/Crucial Technology   | 10        | 11     | 0.54%   |
| LITEONIT                    | 10        | 12     | 0.54%   |
| Unknown                     | 9         | 10     | 0.48%   |
| JMicron Technology          | 7         | 11     | 0.38%   |
| Transcend                   | 6         | 8      | 0.32%   |
| SPCC                        | 6         | 8      | 0.32%   |
| OCZ                         | 6         | 8      | 0.32%   |
| Kingston Technology Company | 6         | 8      | 0.32%   |
| KingSpec                    | 5         | 8      | 0.27%   |
| China                       | 5         | 5      | 0.27%   |
| ASMT                        | 5         | 7      | 0.27%   |
| Patriot                     | 4         | 6      | 0.21%   |
| LaCie                       | 4         | 8      | 0.21%   |
| XPG                         | 3         | 3      | 0.16%   |
| Realtek                     | 3         | 3      | 0.16%   |
| OWC                         | 3         | 10     | 0.16%   |
| Lite-On                     | 3         | 3      | 0.16%   |
| Gigabyte Technology         | 3         | 6      | 0.16%   |
| ADATA Technology            | 3         | 8      | 0.16%   |
| USB                         | 2         | 3      | 0.11%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Unknown MMC Card  64GB                             | 21        | 1.08%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 20        | 1.03%   |
| Toshiba MQ01ABD100 1TB                             | 18        | 0.92%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 18        | 0.92%   |
| Seagate Expansion 1TB                              | 16        | 0.82%   |
| Seagate ST500LT012-1DG142 500GB                    | 15        | 0.77%   |
| SanDisk NVMe SSD Drive 512GB                       | 14        | 0.72%   |
| Samsung SSD 860 EVO 500GB                          | 14        | 0.72%   |
| Toshiba MQ01ABF050 500GB                           | 13        | 0.67%   |
| Samsung NVMe SSD Drive 512GB                       | 13        | 0.67%   |
| HGST HTS721010A9E630 1TB                           | 13        | 0.67%   |
| Unknown MMC Card  128GB                            | 12        | 0.62%   |
| Seagate ST1000LM035-1RK172 1TB                     | 12        | 0.62%   |
| Unknown MMC Card  32GB                             | 11        | 0.56%   |
| Samsung SSD 850 EVO 250GB                          | 11        | 0.56%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 11        | 0.56%   |
| Kingston SA400S37240G 240GB SSD                    | 11        | 0.56%   |
| HGST HTS545050A7E680 500GB                         | 11        | 0.56%   |
| Crucial CT500MX500SSD1 500GB                       | 11        | 0.56%   |
| Seagate ST9500325AS 500GB                          | 10        | 0.51%   |
| Samsung SSD 850 EVO 500GB                          | 10        | 0.51%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB             | 10        | 0.51%   |
| Crucial CT1000MX500SSD1 1TB                        | 10        | 0.51%   |
| Crucial CT1000BX500SSD1 1TB                        | 10        | 0.51%   |
| Apple SSD SM0128G 121GB                            | 10        | 0.51%   |
| Toshiba MQ01ABD075 752GB                           | 9         | 0.46%   |
| SK hynix NVMe SSD Drive 256GB                      | 9         | 0.46%   |
| Seagate ST2000LM007-1R8174 2TB                     | 9         | 0.46%   |
| Hitachi HTS547575A9E384 752GB                      | 9         | 0.46%   |
| Unknown                                            | 9         | 0.46%   |
| WDC WD5000LPVX-22V0TT0 500GB                       | 8         | 0.41%   |
| Unknown MMC Card  16GB                             | 8         | 0.41%   |
| Toshiba NVMe SSD Drive 512GB                       | 8         | 0.41%   |
| Toshiba MQ04ABF100 1TB                             | 8         | 0.41%   |
| SanDisk NVMe SSD Drive 256GB                       | 8         | 0.41%   |
| Samsung SSD 870 EVO 500GB                          | 8         | 0.41%   |
| Samsung SSD 860 EVO 1TB                            | 8         | 0.41%   |
| Intel NVMe SSD Drive 512GB                         | 8         | 0.41%   |
| Hitachi HTS545050B9A300 500GB                      | 8         | 0.41%   |
| HGST HTS541010A9E680 1TB                           | 8         | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 188       | 296    | 32.14%  |
| WDC                 | 130       | 186    | 22.22%  |
| Toshiba             | 96        | 147    | 16.41%  |
| Hitachi             | 65        | 79     | 11.11%  |
| HGST                | 49        | 67     | 8.38%   |
| Fujitsu             | 16        | 20     | 2.74%   |
| Samsung Electronics | 12        | 15     | 2.05%   |
| Unknown             | 7         | 7      | 1.2%    |
| Apple               | 5         | 6      | 0.85%   |
| LaCie               | 4         | 7      | 0.68%   |
| ASMT                | 3         | 5      | 0.51%   |
| KESU                | 2         | 2      | 0.34%   |
| HGST HUS            | 2         | 2      | 0.34%   |
| External            | 2         | 2      | 0.34%   |
| USB3.0              | 1         | 1      | 0.17%   |
| USB                 | 1         | 2      | 0.17%   |
| IBM/Hitachi         | 1         | 1      | 0.17%   |
| AAPL                | 1         | 1      | 0.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 170       | 212    | 28.67%  |
| Crucial             | 61        | 83     | 10.29%  |
| SanDisk             | 53        | 64     | 8.94%   |
| Kingston            | 47        | 59     | 7.93%   |
| Apple               | 46        | 54     | 7.76%   |
| WDC                 | 31        | 42     | 5.23%   |
| Toshiba             | 24        | 34     | 4.05%   |
| SK hynix            | 24        | 30     | 4.05%   |
| Intel               | 24        | 45     | 4.05%   |
| Micron Technology   | 18        | 19     | 3.04%   |
| LITEON              | 11        | 17     | 1.85%   |
| LITEONIT            | 10        | 12     | 1.69%   |
| A-DATA Technology   | 7         | 9      | 1.18%   |
| Transcend           | 6         | 8      | 1.01%   |
| SPCC                | 6         | 8      | 1.01%   |
| OCZ                 | 6         | 8      | 1.01%   |
| KingSpec            | 5         | 8      | 0.84%   |
| China               | 5         | 5      | 0.84%   |
| Patriot             | 4         | 6      | 0.67%   |
| Seagate             | 3         | 4      | 0.51%   |
| OWC                 | 3         | 10     | 0.51%   |
| TO Exter            | 2         | 2      | 0.34%   |
| Plextor             | 2         | 6      | 0.34%   |
| Gigabyte Technology | 2         | 2      | 0.34%   |
| FORESEE             | 2         | 2      | 0.34%   |
| WDC WDS2            | 1         | 1      | 0.17%   |
| T-CREATE            | 1         | 1      | 0.17%   |
| SAMSWEET            | 1         | 1      | 0.17%   |
| PNY CS90            | 1         | 1      | 0.17%   |
| PNY                 | 1         | 1      | 0.17%   |
| Mushkin             | 1         | 1      | 0.17%   |
| LT                  | 1         | 1      | 0.17%   |
| Leven               | 1         | 1      | 0.17%   |
| Kston               | 1         | 1      | 0.17%   |
| Kingmax             | 1         | 1      | 0.17%   |
| KingFast            | 1         | 1      | 0.17%   |
| KingDian            | 1         | 1      | 0.17%   |
| INDMEM              | 1         | 1      | 0.17%   |
| Hewlett-Packard     | 1         | 1      | 0.17%   |
| Drevo               | 1         | 1      | 0.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 561       | 771    | 32.02%  |
| HDD     | 549       | 846    | 31.34%  |
| NVMe    | 526       | 787    | 30.02%  |
| MMC     | 91        | 117    | 5.19%   |
| Unknown | 25        | 27     | 1.43%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 982       | 1508   | 57.97%  |
| NVMe | 522       | 773    | 30.81%  |
| SAS  | 99        | 150    | 5.84%   |
| MMC  | 91        | 117    | 5.37%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 726       | 1036   | 65.58%  |
| 0.51-1.0   | 311       | 460    | 28.09%  |
| 1.01-2.0   | 50        | 89     | 4.52%   |
| 3.01-4.0   | 9         | 15     | 0.81%   |
| 2.01-3.0   | 6         | 12     | 0.54%   |
| 4.01-10.0  | 5         | 5      | 0.45%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 425       | 26.36%  |
| 251-500        | 396       | 24.57%  |
| 501-1000       | 263       | 16.32%  |
| 1-20           | 136       | 8.44%   |
| 1001-2000      | 114       | 7.07%   |
| 51-100         | 113       | 7.01%   |
| More than 3000 | 50        | 3.1%    |
| 21-50          | 41        | 2.54%   |
| Unknown        | 41        | 2.54%   |
| 2001-3000      | 33        | 2.05%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 691       | 40.58%  |
| 21-50          | 333       | 19.55%  |
| 51-100         | 195       | 11.45%  |
| 101-250        | 178       | 10.45%  |
| 251-500        | 130       | 7.63%   |
| 501-1000       | 73        | 4.29%   |
| Unknown        | 41        | 2.41%   |
| 1001-2000      | 35        | 2.06%   |
| 2001-3000      | 13        | 0.76%   |
| More than 3000 | 12        | 0.7%    |
| 0              | 2         | 0.12%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                   | Notebooks | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB      | 3         | 4      | 3.45%   |
| HGST HTS545050A7E680 500GB              | 3         | 4      | 3.45%   |
| Toshiba MQ01ABF050 500GB                | 2         | 2      | 2.3%    |
| Seagate ST9500325AS 500GB               | 2         | 2      | 2.3%    |
| Seagate ST500LT012-1DG142 500GB         | 2         | 2      | 2.3%    |
| Seagate ST500LM021-1KJ152 500GB         | 2         | 2      | 2.3%    |
| Micron Technology 1100 SATA 256GB SSD   | 2         | 2      | 2.3%    |
| Kingston RBU-SNS8350DES3128GP 128GB SSD | 2         | 2      | 2.3%    |
| Hitachi HTS547564A9E384 640GB           | 2         | 2      | 2.3%    |
| WDC WD6400BEVT-22A0RT0 640GB            | 1         | 2      | 1.15%   |
| WDC WD5000LPVX-22V0TT0 500GB            | 1         | 2      | 1.15%   |
| WDC WD5000BEVT-60ZAT1 500GB             | 1         | 3      | 1.15%   |
| WDC WD3200BPVT-22ZEST0 320GB            | 1         | 1      | 1.15%   |
| WDC WD3200BEVT-75ZCT0 320GB             | 1         | 1      | 1.15%   |
| WDC WD2500BEVT-35A23T0 250GB            | 1         | 1      | 1.15%   |
| WDC WD20 EARS-00J2GB0 2TB               | 1         | 1      | 1.15%   |
| WDC WD10SPZX-21Z10T0 1TB                | 1         | 2      | 1.15%   |
| WDC WD10JPVX-22JC3T0 1TB                | 1         | 2      | 1.15%   |
| WDC WD Blue SA510 M.2 2280 1000GB SSD   | 1         | 1      | 1.15%   |
| Transcend TS256GSSD230S 256GB           | 1         | 1      | 1.15%   |
| Toshiba THNSNK128GCS8 SATA 128GB SSD    | 1         | 1      | 1.15%   |
| Toshiba MQ01ACF032 320GB                | 1         | 1      | 1.15%   |
| Toshiba MQ01ABD100 1TB                  | 1         | 1      | 1.15%   |
| Toshiba MQ01ABD050 500GB                | 1         | 1      | 1.15%   |
| Toshiba MK5065GSX 500GB                 | 1         | 1      | 1.15%   |
| Toshiba MK5055GSX 500GB                 | 1         | 5      | 1.15%   |
| Toshiba MK3265GSX 320GB                 | 1         | 1      | 1.15%   |
| SK hynix SC308 SATA 256GB SSD           | 1         | 1      | 1.15%   |
| Seagate ST9500423AS 500GB               | 1         | 2      | 1.15%   |
| Seagate ST9500325ASG 500GB              | 1         | 1      | 1.15%   |
| Seagate ST9320423AS 320GB               | 1         | 2      | 1.15%   |
| Seagate ST9250410AS 250GB               | 1         | 1      | 1.15%   |
| Seagate ST9250315AS 250GB               | 1         | 1      | 1.15%   |
| Seagate ST9160821AS 160GB               | 1         | 5      | 1.15%   |
| Seagate ST9160310AS 160GB               | 1         | 1      | 1.15%   |
| Seagate ST500LT012-9WS142 500GB         | 1         | 2      | 1.15%   |
| Seagate ST500LM000-1EJ162 500GB         | 1         | 2      | 1.15%   |
| Seagate ST320LT012-9WS14C 320GB         | 1         | 1      | 1.15%   |
| Seagate ST320LT007-9ZV142 320GB         | 1         | 1      | 1.15%   |
| Seagate ST1000LM049-2GH172 1TB          | 1         | 1      | 1.15%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                   | Notebooks | Drives | Percent |
|--------------------------|-----------|--------|---------|
| Seagate                  | 21        | 30     | 24.14%  |
| Hitachi                  | 11        | 11     | 12.64%  |
| WDC                      | 10        | 16     | 11.49%  |
| Toshiba                  | 9         | 13     | 10.34%  |
| Samsung Electronics      | 6         | 6      | 6.9%    |
| HGST                     | 6         | 7      | 6.9%    |
| Fujitsu                  | 5         | 5      | 5.75%   |
| Micron Technology        | 4         | 4      | 4.6%    |
| SanDisk                  | 3         | 3      | 3.45%   |
| Kingston                 | 3         | 3      | 3.45%   |
| Crucial                  | 2         | 2      | 2.3%    |
| Transcend                | 1         | 1      | 1.15%   |
| SK hynix                 | 1         | 1      | 1.15%   |
| KingSpec                 | 1         | 3      | 1.15%   |
| Intel                    | 1         | 2      | 1.15%   |
| Biwin Storage Technology | 1         | 1      | 1.15%   |
| Apple                    | 1         | 1      | 1.15%   |
| A-DATA Technology        | 1         | 1      | 1.15%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 21        | 30     | 34.43%  |
| Hitachi             | 11        | 11     | 18.03%  |
| WDC                 | 9         | 15     | 14.75%  |
| Toshiba             | 8         | 12     | 13.11%  |
| HGST                | 6         | 7      | 9.84%   |
| Fujitsu             | 5         | 5      | 8.2%    |
| Samsung Electronics | 1         | 1      | 1.64%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 60        | 81     | 69.77%  |
| SSD  | 22        | 25     | 25.58%  |
| NVMe | 4         | 4      | 4.65%   |

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
| Detected | 949       | 1608   | 60.25%  |
| Works    | 541       | 830    | 34.35%  |
| Malfunc  | 85        | 110    | 5.4%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 1036      | 59.34%  |
| Samsung Electronics                     | 188       | 10.77%  |
| AMD                                     | 140       | 8.02%   |
| SanDisk                                 | 81        | 4.64%   |
| SK hynix                                | 48        | 2.75%   |
| Toshiba America Info Systems            | 36        | 2.06%   |
| Micron Technology                       | 35        | 2%      |
| Kingston Technology Company             | 30        | 1.72%   |
| Phison Electronics                      | 27        | 1.55%   |
| Micron/Crucial Technology               | 23        | 1.32%   |
| KIOXIA                                  | 19        | 1.09%   |
| Apple                                   | 17        | 0.97%   |
| Nvidia                                  | 16        | 0.92%   |
| ADATA Technology                        | 11        | 0.63%   |
| Marvell Technology Group                | 9         | 0.52%   |
| Solid State Storage Technology          | 5         | 0.29%   |
| Silicon Motion                          | 4         | 0.23%   |
| Lite-On Technology                      | 4         | 0.23%   |
| Union Memory (Shenzhen)                 | 2         | 0.11%   |
| Silicon Integrated Systems [SiS]        | 2         | 0.11%   |
| Shenzhen Longsys Electronics            | 2         | 0.11%   |
| Realtek Semiconductor                   | 2         | 0.11%   |
| O2 Micro                                | 2         | 0.11%   |
| Lenovo                                  | 2         | 0.11%   |
| ULi Electronics                         | 1         | 0.06%   |
| Shenzhen Unionmemory Information System | 1         | 0.06%   |
| JMicron Technology                      | 1         | 0.06%   |
| Biwin Storage Technology                | 1         | 0.06%   |
| ASMedia Technology                      | 1         | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 127       | 6.83%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 126       | 6.78%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 107       | 5.76%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 105       | 5.65%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 98        | 5.27%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 90        | 4.84%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 57        | 3.07%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 57        | 3.07%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 51        | 2.74%   |
| Intel Volume Management Device NVMe RAID Controller                              | 47        | 2.53%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 44        | 2.37%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 38        | 2.04%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 37        | 1.99%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 32        | 1.72%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 25        | 1.34%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 24        | 1.29%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 23        | 1.24%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 22        | 1.18%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 21        | 1.13%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 19        | 1.02%   |
| Intel SSD 660P Series                                                            | 19        | 1.02%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 18        | 0.97%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 17        | 0.91%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 17        | 0.91%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 16        | 0.86%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                       | 15        | 0.81%   |
| Intel Tiger Lake-LP SATA Controller                                              | 14        | 0.75%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 14        | 0.75%   |
| Phison E12 NVMe Controller                                                       | 13        | 0.7%    |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 12        | 0.65%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 12        | 0.65%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                      | 12        | 0.65%   |
| Intel Comet Lake SATA AHCI Controller                                            | 12        | 0.65%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                             | 11        | 0.59%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                            | 11        | 0.59%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 11        | 0.59%   |
| Apple ANS2 NVMe Controller                                                       | 11        | 0.59%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 11        | 0.59%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 10        | 0.54%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                              | 10        | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1008      | 56.66%  |
| NVMe | 525       | 29.51%  |
| RAID | 160       | 8.99%   |
| IDE  | 86        | 4.83%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 1270      | 85.23%  |
| AMD    | 217       | 14.56%  |
| ARM    | 3         | 0.2%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-9750H CPU @ 2.60GHz       | 35        | 2.35%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 26        | 1.74%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 22        | 1.47%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 21        | 1.41%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 21        | 1.41%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 20        | 1.34%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 20        | 1.34%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 19        | 1.27%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 18        | 1.21%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 18        | 1.21%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 18        | 1.21%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 18        | 1.21%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 17        | 1.14%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 16        | 1.07%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 15        | 1.01%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 15        | 1.01%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 15        | 1.01%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 15        | 1.01%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 14        | 0.94%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 14        | 0.94%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 14        | 0.94%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz      | 14        | 0.94%   |
| Intel Core i7-3610QM CPU @ 2.30GHz      | 14        | 0.94%   |
| Intel Core i7-2670QM CPU @ 2.20GHz      | 12        | 0.8%    |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz    | 12        | 0.8%    |
| Intel Core i7-4510U CPU @ 2.00GHz       | 11        | 0.74%   |
| Intel Core i7-2630QM CPU @ 2.00GHz      | 11        | 0.74%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz       | 11        | 0.74%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 11        | 0.74%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 10        | 0.67%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 10        | 0.67%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 10        | 0.67%   |
| Intel Core i5-2450M CPU @ 2.50GHz       | 10        | 0.67%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 10        | 0.67%   |
| Intel Celeron N4020 CPU @ 1.10GHz       | 10        | 0.67%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 10        | 0.67%   |
| Intel Core i7-3740QM CPU @ 2.70GHz      | 9         | 0.6%    |
| Intel Core i5-5300U CPU @ 2.30GHz       | 9         | 0.6%    |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz    | 9         | 0.6%    |
| Intel 12th Gen Core i7-12700H           | 9         | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i7                  | 490       | 32.86%  |
| Intel Core i5                  | 372       | 24.95%  |
| Other                          | 136       | 9.12%   |
| Intel Core 2 Duo               | 67        | 4.49%   |
| Intel Core i3                  | 62        | 4.16%   |
| Intel Celeron                  | 61        | 4.09%   |
| AMD Ryzen 7                    | 45        | 3.02%   |
| AMD Ryzen 5                    | 35        | 2.35%   |
| Intel Pentium                  | 27        | 1.81%   |
| AMD A6                         | 21        | 1.41%   |
| AMD A4                         | 21        | 1.41%   |
| Intel Atom                     | 15        | 1.01%   |
| AMD Ryzen 7 PRO                | 10        | 0.67%   |
| AMD Ryzen 9                    | 9         | 0.6%    |
| AMD E2                         | 9         | 0.6%    |
| Intel Core i9                  | 8         | 0.54%   |
| AMD A8                         | 8         | 0.54%   |
| AMD A10                        | 8         | 0.54%   |
| Intel Pentium Dual-Core        | 7         | 0.47%   |
| Intel Core 2                   | 7         | 0.47%   |
| AMD E1                         | 7         | 0.47%   |
| Intel Genuine                  | 6         | 0.4%    |
| Intel Core M                   | 6         | 0.4%    |
| Intel Xeon                     | 5         | 0.34%   |
| Intel Core m3                  | 5         | 0.34%   |
| AMD Ryzen 3                    | 5         | 0.34%   |
| Intel Pentium Dual             | 4         | 0.27%   |
| Intel Celeron Dual-Core        | 4         | 0.27%   |
| AMD E                          | 4         | 0.27%   |
| Intel Pentium M                | 3         | 0.2%    |
| Intel Core m7                  | 2         | 0.13%   |
| Intel Core Duo                 | 2         | 0.13%   |
| Intel Celeron M                | 2         | 0.13%   |
| AMD V120                       | 2         | 0.13%   |
| AMD FX                         | 2         | 0.13%   |
| AMD A12                        | 2         | 0.13%   |
| Intel Mobile Pentium 4         | 1         | 0.07%   |
| Intel Core m5                  | 1         | 0.07%   |
| AMD V140                       | 1         | 0.07%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.07%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 721       | 48.32%  |
| 4      | 493       | 33.04%  |
| 6      | 121       | 8.11%   |
| 8      | 81        | 5.43%   |
| 1      | 32        | 2.14%   |
| 10     | 17        | 1.14%   |
| 14     | 15        | 1.01%   |
| 12     | 9         | 0.6%    |
| 16     | 2         | 0.13%   |
| 5      | 1         | 0.07%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1488      | 99.87%  |
| 2      | 2         | 0.13%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1179      | 79.02%  |
| 1      | 310       | 20.78%  |
| 4      | 2         | 0.13%   |
| 8      | 1         | 0.07%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1461      | 97.53%  |
| 32-bit         | 18        | 1.2%    |
| Unknown        | 17        | 1.13%   |
| 64-bit         | 2         | 0.13%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 509       | 32.5%   |
| 0x206a7    | 92        | 5.87%   |
| 0x306a9    | 84        | 5.36%   |
| 0x406e3    | 52        | 3.32%   |
| 0x40651    | 52        | 3.32%   |
| 0x906ea    | 51        | 3.26%   |
| 0x306d4    | 42        | 2.68%   |
| 0x1067a    | 42        | 2.68%   |
| 0x806ec    | 40        | 2.55%   |
| 0x20655    | 38        | 2.43%   |
| 0x806ea    | 37        | 2.36%   |
| 0x806c1    | 35        | 2.23%   |
| 0x306c3    | 35        | 2.23%   |
| 0x806e9    | 32        | 2.04%   |
| 0xa0652    | 21        | 1.34%   |
| 0x906e9    | 21        | 1.34%   |
| 0x20652    | 20        | 1.28%   |
| 0x0a50000c | 18        | 1.15%   |
| 0x06006705 | 18        | 1.15%   |
| 0x806eb    | 16        | 1.02%   |
| 0x07030105 | 15        | 0.96%   |
| 0x30678    | 14        | 0.89%   |
| 0x706e5    | 13        | 0.83%   |
| 0x506e3    | 13        | 0.83%   |
| 0x806d1    | 12        | 0.77%   |
| 0x0700010f | 12        | 0.77%   |
| 0x906a3    | 11        | 0.7%    |
| 0x106e5    | 11        | 0.7%    |
| 0x10676    | 11        | 0.7%    |
| 0x406c3    | 9         | 0.57%   |
| 0x08108109 | 9         | 0.57%   |
| 0x08108102 | 9         | 0.57%   |
| 0x6fd      | 8         | 0.51%   |
| 0x406c4    | 8         | 0.51%   |
| 0x906a4    | 7         | 0.45%   |
| 0x08600106 | 7         | 0.45%   |
| 0x08600103 | 7         | 0.45%   |
| 0x06001119 | 7         | 0.45%   |
| 0x6f6      | 6         | 0.38%   |
| 0x506c9    | 6         | 0.38%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 277       | 18.57%  |
| IvyBridge        | 140       | 9.38%   |
| Haswell          | 130       | 8.71%   |
| SandyBridge      | 127       | 8.51%   |
| Skylake          | 103       | 6.9%    |
| Westmere         | 70        | 4.69%   |
| Penryn           | 69        | 4.62%   |
| Broadwell        | 58        | 3.89%   |
| Unknown          | 53        | 3.55%   |
| TigerLake        | 50        | 3.35%   |
| CometLake        | 40        | 2.68%   |
| IceLake          | 36        | 2.41%   |
| Silvermont       | 35        | 2.35%   |
| Excavator        | 31        | 2.08%   |
| Alderlake Hybrid | 30        | 2.01%   |
| Zen 3            | 28        | 1.88%   |
| Zen 2            | 24        | 1.61%   |
| Core             | 24        | 1.61%   |
| Zen+             | 23        | 1.54%   |
| Puma             | 20        | 1.34%   |
| Goldmont plus    | 16        | 1.07%   |
| Jaguar           | 14        | 0.94%   |
| Nehalem          | 13        | 0.87%   |
| Zen              | 12        | 0.8%    |
| P6               | 12        | 0.8%    |
| Piledriver       | 9         | 0.6%    |
| Goldmont         | 9         | 0.6%    |
| Bonnell          | 8         | 0.54%   |
| K10 Llano        | 7         | 0.47%   |
| K10              | 6         | 0.4%    |
| Steamroller      | 5         | 0.34%   |
| Bobcat           | 5         | 0.34%   |
| Tremont          | 3         | 0.2%    |
| K8 & K10 hybrid  | 2         | 0.13%   |
| NetBurst         | 1         | 0.07%   |
| K8 Hammer        | 1         | 0.07%   |
| Gracemont        | 1         | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1119      | 58.04%  |
| Nvidia                           | 474       | 24.59%  |
| AMD                              | 331       | 17.17%  |
| Silicon Integrated Systems [SiS] | 2         | 0.1%    |
| Neomagic                         | 2         | 0.1%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 122       | 6.11%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 112       | 5.61%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 77        | 3.85%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 73        | 3.65%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 67        | 3.35%   |
| Intel UHD Graphics 620                                                                   | 56        | 2.8%    |
| Intel Core Processor Integrated Graphics Controller                                      | 49        | 2.45%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 47        | 2.35%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 47        | 2.35%   |
| Intel HD Graphics 5500                                                                   | 38        | 1.9%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 37        | 1.85%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 36        | 1.8%    |
| Intel HD Graphics 620                                                                    | 32        | 1.6%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 32        | 1.6%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 30        | 1.5%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 27        | 1.35%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 26        | 1.3%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 26        | 1.3%    |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 23        | 1.15%   |
| Intel HD Graphics 630                                                                    | 22        | 1.1%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 22        | 1.1%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 21        | 1.05%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 19        | 0.95%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 19        | 0.95%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 17        | 0.85%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 16        | 0.8%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 16        | 0.8%    |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 16        | 0.8%    |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 16        | 0.8%    |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 15        | 0.75%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 15        | 0.75%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 15        | 0.75%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 15        | 0.75%   |
| Intel HD Graphics 530                                                                    | 15        | 0.75%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 15        | 0.75%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 14        | 0.7%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 14        | 0.7%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 14        | 0.7%    |
| Intel Iris Plus Graphics G7                                                              | 13        | 0.65%   |
| AMD Lucienne                                                                             | 13        | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 714       | 47.63%  |
| Intel + Nvidia           | 335       | 22.35%  |
| 1 x AMD                  | 192       | 12.81%  |
| 1 x Nvidia               | 103       | 6.87%   |
| Intel + AMD              | 60        | 4%      |
| 2 x AMD                  | 44        | 2.94%   |
| AMD + Nvidia             | 35        | 2.33%   |
| 2 x Intel                | 5         | 0.33%   |
| Other                    | 3         | 0.2%    |
| 1 x SiS                  | 2         | 0.13%   |
| 1 x Neomagic             | 2         | 0.13%   |
| Intel + AMD + 1 x Nvidia | 2         | 0.13%   |
| 2 x Nvidia               | 1         | 0.07%   |
| Intel + 2 x Nvidia       | 1         | 0.07%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1250      | 81.75%  |
| Proprietary | 234       | 15.3%   |
| Unknown     | 45        | 2.94%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 991       | 64.14%  |
| 1.01-2.0   | 162       | 10.49%  |
| 0.01-0.5   | 151       | 9.77%   |
| 3.01-4.0   | 94        | 6.08%   |
| 0.51-1.0   | 86        | 5.57%   |
| 5.01-6.0   | 28        | 1.81%   |
| 7.01-8.0   | 20        | 1.29%   |
| 2.01-3.0   | 8         | 0.52%   |
| 8.01-16.0  | 5         | 0.32%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 350       | 20.17%  |
| LG Display              | 241       | 13.89%  |
| Chimei Innolux          | 180       | 10.37%  |
| Samsung Electronics     | 166       | 9.57%   |
| BOE                     | 157       | 9.05%   |
| Apple                   | 112       | 6.46%   |
| Sharp                   | 73        | 4.21%   |
| Dell                    | 51        | 2.94%   |
| Chi Mei Optoelectronics | 44        | 2.54%   |
| Lenovo                  | 31        | 1.79%   |
| Goldstar                | 26        | 1.5%    |
| Acer                    | 25        | 1.44%   |
| PANDA                   | 24        | 1.38%   |
| Philips                 | 23        | 1.33%   |
| Hewlett-Packard         | 23        | 1.33%   |
| BenQ                    | 21        | 1.21%   |
| AOC                     | 12        | 0.69%   |
| Sony                    | 11        | 0.63%   |
| ViewSonic               | 10        | 0.58%   |
| InfoVision              | 9         | 0.52%   |
| Unknown                 | 8         | 0.46%   |
| CSO                     | 8         | 0.46%   |
| Ancor Communications    | 8         | 0.46%   |
| Valve                   | 7         | 0.4%    |
| Toshiba                 | 6         | 0.35%   |
| Panasonic               | 6         | 0.35%   |
| LG Philips              | 6         | 0.35%   |
| CPT                     | 6         | 0.35%   |
| LGD                     | 5         | 0.29%   |
| Hitachi                 | 5         | 0.29%   |
| SAC                     | 4         | 0.23%   |
| Kogan                   | 4         | 0.23%   |
| HannStar                | 4         | 0.23%   |
| GKK                     | 4         | 0.23%   |
| GDH                     | 4         | 0.23%   |
| eMachines               | 4         | 0.23%   |
| ASUSTek Computer        | 4         | 0.23%   |
| ___                     | 3         | 0.17%   |
| InnoLux Display         | 3         | 0.17%   |
| Unknown (XXX)           | 2         | 0.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 19        | 1.07%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 14        | 0.79%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch     | 11        | 0.62%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 11        | 0.62%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 11        | 0.62%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                  | 10        | 0.56%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                     | 10        | 0.56%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 9         | 0.51%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 9         | 0.51%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                     | 9         | 0.51%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 8         | 0.45%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch          | 8         | 0.45%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 7         | 0.39%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 7         | 0.39%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 7         | 0.39%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 7         | 0.39%   |
| BOE LCD Monitor BOE07CE 1366x768 344x193mm 15.5-inch                     | 7         | 0.39%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 7         | 0.39%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 7         | 0.39%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch           | 7         | 0.39%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                  | 6         | 0.34%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 6         | 0.34%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 6         | 0.34%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch             | 6         | 0.34%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch             | 6         | 0.34%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 6         | 0.34%   |
| Chimei Innolux LCD Monitor CMN1514 1920x1080 344x193mm 15.5-inch         | 6         | 0.34%   |
| Chi Mei Optoelectronics LCD Monitor CMO1100 1366x768 256x144mm 11.6-inch | 6         | 0.34%   |
| BOE LCD Monitor BOE07CB 1920x1080 344x193mm 15.5-inch                    | 6         | 0.34%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 6         | 0.34%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 6         | 0.34%   |
| AU Optronics LCD Monitor AUO323D 1920x1080 309x174mm 14.0-inch           | 6         | 0.34%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                     | 6         | 0.34%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch                  | 5         | 0.28%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                  | 5         | 0.28%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch              | 5         | 0.28%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 5         | 0.28%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 5         | 0.28%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 5         | 0.28%   |
| AU Optronics LCD Monitor AUOD0ED 1920x1080 344x193mm 15.5-inch           | 5         | 0.28%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 618       | 38.01%  |
| 1366x768 (WXGA)    | 488       | 30.01%  |
| 3840x2160 (4K)     | 97        | 5.97%   |
| 1280x800 (WXGA)    | 71        | 4.37%   |
| 1600x900 (HD+)     | 54        | 3.32%   |
| 1440x900 (WXGA+)   | 42        | 2.58%   |
| 1920x1200 (WUXGA)  | 34        | 2.09%   |
| 2560x1440 (QHD)    | 33        | 2.03%   |
| 2560x1600          | 32        | 1.97%   |
| 2880x1800          | 25        | 1.54%   |
| 1680x1050 (WSXGA+) | 14        | 0.86%   |
| 3840x2400          | 13        | 0.8%    |
| 3440x1440          | 12        | 0.74%   |
| 3200x1800 (QHD+)   | 9         | 0.55%   |
| 800x1280           | 7         | 0.43%   |
| 1360x768           | 7         | 0.43%   |
| 1280x1024 (SXGA)   | 7         | 0.43%   |
| 1024x600           | 6         | 0.37%   |
| 3840x1080          | 5         | 0.31%   |
| 3072x1920          | 5         | 0.31%   |
| Unknown            | 5         | 0.31%   |
| 3200x2000          | 4         | 0.25%   |
| 2240x1400          | 4         | 0.25%   |
| 2160x1440          | 4         | 0.25%   |
| 2304x1440          | 3         | 0.18%   |
| 2256x1504          | 3         | 0.18%   |
| 5760x2160          | 2         | 0.12%   |
| 3840x1100          | 2         | 0.12%   |
| 3456x2160          | 2         | 0.12%   |
| 3286x1080          | 2         | 0.12%   |
| 2560x1080          | 2         | 0.12%   |
| 2288x1287          | 2         | 0.12%   |
| 1920x540           | 2         | 0.12%   |
| 1680x945           | 2         | 0.12%   |
| 1280x720 (HD)      | 2         | 0.12%   |
| 1024x768 (XGA)     | 2         | 0.12%   |
| 3840x1600          | 1         | 0.06%   |
| 3000x2000          | 1         | 0.06%   |
| 2726x768           | 1         | 0.06%   |
| 1720x1440          | 1         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 678       | 38.97%  |
| 13      | 262       | 15.06%  |
| 14      | 184       | 10.57%  |
| 17      | 106       | 6.09%   |
| 27      | 69        | 3.97%   |
| 24      | 60        | 3.45%   |
| 12      | 49        | 2.82%   |
| 23      | 44        | 2.53%   |
| 11      | 44        | 2.53%   |
| 21      | 33        | 1.9%    |
| Unknown | 28        | 1.61%   |
| 16      | 25        | 1.44%   |
| 31      | 24        | 1.38%   |
| 18      | 12        | 0.69%   |
| 72      | 11        | 0.63%   |
| 84      | 10        | 0.57%   |
| 34      | 10        | 0.57%   |
| 19      | 10        | 0.57%   |
| 10      | 8         | 0.46%   |
| 40      | 7         | 0.4%    |
| 22      | 7         | 0.4%    |
| 7       | 7         | 0.4%    |
| 52      | 6         | 0.34%   |
| 20      | 6         | 0.34%   |
| 54      | 4         | 0.23%   |
| 48      | 4         | 0.23%   |
| 86      | 3         | 0.17%   |
| 37      | 3         | 0.17%   |
| 35      | 3         | 0.17%   |
| 32      | 3         | 0.17%   |
| 142     | 2         | 0.11%   |
| 49      | 2         | 0.11%   |
| 46      | 2         | 0.11%   |
| 42      | 2         | 0.11%   |
| 25      | 2         | 0.11%   |
| 8       | 2         | 0.11%   |
| 78      | 1         | 0.06%   |
| 63      | 1         | 0.06%   |
| 55      | 1         | 0.06%   |
| 38      | 1         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 957       | 55.57%  |
| 201-300        | 268       | 15.56%  |
| 501-600        | 148       | 8.59%   |
| 351-400        | 135       | 7.84%   |
| 401-500        | 61        | 3.54%   |
| 601-700        | 38        | 2.21%   |
| Unknown        | 28        | 1.63%   |
| 1001-1500      | 23        | 1.34%   |
| 1501-2000      | 22        | 1.28%   |
| 701-800        | 15        | 0.87%   |
| 801-900        | 14        | 0.81%   |
| 1-100          | 7         | 0.41%   |
| More than 2000 | 2         | 0.12%   |
| 101-200        | 2         | 0.12%   |
| 901-1000       | 2         | 0.12%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1191      | 78.72%  |
| 16/10   | 239       | 15.8%   |
| Unknown | 20        | 1.32%   |
| 21/9    | 15        | 0.99%   |
| 3/2     | 14        | 0.93%   |
| 5/4     | 8         | 0.53%   |
| 32/9    | 7         | 0.46%   |
| 0.67    | 7         | 0.46%   |
| 4/3     | 3         | 0.2%    |
| 0.56    | 3         | 0.2%    |
| 3.40    | 2         | 0.13%   |
| 1.00    | 2         | 0.13%   |
| 6/5     | 1         | 0.07%   |
| 0.62    | 1         | 0.07%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 673       | 38.81%  |
| 81-90          | 326       | 18.8%   |
| 71-80          | 121       | 6.98%   |
| 201-250        | 116       | 6.69%   |
| 121-130        | 89        | 5.13%   |
| 301-350        | 69        | 3.98%   |
| 51-60          | 46        | 2.65%   |
| 61-70          | 45        | 2.6%    |
| 351-500        | 41        | 2.36%   |
| More than 1000 | 38        | 2.19%   |
| 151-200        | 28        | 1.61%   |
| 111-120        | 28        | 1.61%   |
| Unknown        | 28        | 1.61%   |
| 501-1000       | 22        | 1.27%   |
| 251-300        | 15        | 0.87%   |
| 131-140        | 15        | 0.87%   |
| 141-150        | 12        | 0.69%   |
| 41-50          | 9         | 0.52%   |
| 1-40           | 9         | 0.52%   |
| 91-100         | 4         | 0.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 602       | 35.68%  |
| 101-120       | 500       | 29.64%  |
| 51-100        | 274       | 16.24%  |
| 161-240       | 157       | 9.31%   |
| More than 240 | 92        | 5.45%   |
| 1-50          | 34        | 2.02%   |
| Unknown       | 28        | 1.66%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1202      | 77.45%  |
| 2     | 262       | 16.88%  |
| 0     | 47        | 3.03%   |
| 3     | 36        | 2.32%   |
| 4     | 5         | 0.32%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 814       | 33.37%  |
| Realtek Semiconductor             | 747       | 30.63%  |
| Qualcomm Atheros                  | 321       | 13.16%  |
| Broadcom                          | 186       | 7.63%   |
| Broadcom Limited                  | 61        | 2.5%    |
| Ralink                            | 28        | 1.15%   |
| MediaTek                          | 27        | 1.11%   |
| Sierra Wireless                   | 26        | 1.07%   |
| Marvell Technology Group          | 18        | 0.74%   |
| DisplayLink                       | 17        | 0.7%    |
| Samsung Electronics               | 15        | 0.62%   |
| Dell                              | 14        | 0.57%   |
| Huawei Technologies               | 12        | 0.49%   |
| Hewlett-Packard                   | 12        | 0.49%   |
| Apple                             | 11        | 0.45%   |
| Nvidia                            | 10        | 0.41%   |
| Lenovo                            | 10        | 0.41%   |
| TP-Link                           | 9         | 0.37%   |
| Ralink Technology                 | 9         | 0.37%   |
| ZTE WCDMA Technologies MSM        | 8         | 0.33%   |
| NetGear                           | 8         | 0.33%   |
| Edimax Technology                 | 7         | 0.29%   |
| ASIX Electronics                  | 7         | 0.29%   |
| Qualcomm                          | 6         | 0.25%   |
| OPPO Electronics                  | 6         | 0.25%   |
| JMicron Technology                | 4         | 0.16%   |
| Google                            | 4         | 0.16%   |
| Ericsson Business Mobile Networks | 4         | 0.16%   |
| ASUSTek Computer                  | 4         | 0.16%   |
| Xiaomi                            | 3         | 0.12%   |
| Motorola PCS                      | 3         | 0.12%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.08%   |
| Qualcomm Atheros Communications   | 2         | 0.08%   |
| Microsoft                         | 2         | 0.08%   |
| ICS Advent                        | 2         | 0.08%   |
| Dresden Elektronik                | 2         | 0.08%   |
| D-Link                            | 2         | 0.08%   |
| Arduino SA                        | 2         | 0.08%   |
| Wilocity                          | 1         | 0.04%   |
| ULi Electronics                   | 1         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 437       | 14.95%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 126       | 4.31%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                             | 88        | 3.01%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 69        | 2.36%   |
| Intel Wi-Fi 6 AX200                                                  | 61        | 2.09%   |
| Intel Wireless 8260                                                  | 60        | 2.05%   |
| Intel Wireless 8265 / 8275                                           | 54        | 1.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 49        | 1.68%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 49        | 1.68%   |
| Intel Wireless 7260                                                  | 49        | 1.68%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 46        | 1.57%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 44        | 1.51%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 40        | 1.37%   |
| Intel Wi-Fi 6 AX201                                                  | 39        | 1.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 38        | 1.3%    |
| Intel Wireless 3165                                                  | 36        | 1.23%   |
| Intel Ethernet Connection I219-LM                                    | 36        | 1.23%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 35        | 1.2%    |
| Intel Centrino Ultimate-N 6300                                       | 35        | 1.2%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 33        | 1.13%   |
| Intel Wireless 7265                                                  | 30        | 1.03%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 30        | 1.03%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 29        | 0.99%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 26        | 0.89%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 25        | 0.86%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 24        | 0.82%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 24        | 0.82%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 23        | 0.79%   |
| Intel Ethernet Connection (4) I219-LM                                | 22        | 0.75%   |
| Intel Wireless-AC 9260                                               | 21        | 0.72%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 21        | 0.72%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                    | 21        | 0.72%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                        | 20        | 0.68%   |
| Intel Wireless 3160                                                  | 20        | 0.68%   |
| Intel 82577LM Gigabit Network Connection                             | 20        | 0.68%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 19        | 0.65%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 18        | 0.62%   |
| Intel Ethernet Connection I218-LM                                    | 17        | 0.58%   |
| Broadcom BCM43224 802.11a/b/g/n                                      | 17        | 0.58%   |
| Intel Centrino Advanced-N 6235                                       | 16        | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 788       | 50.51%  |
| Qualcomm Atheros                | 270       | 17.31%  |
| Realtek Semiconductor           | 165       | 10.58%  |
| Broadcom                        | 148       | 9.49%   |
| Broadcom Limited                | 50        | 3.21%   |
| Ralink                          | 28        | 1.79%   |
| Sierra Wireless                 | 26        | 1.67%   |
| MediaTek                        | 26        | 1.67%   |
| Ralink Technology               | 9         | 0.58%   |
| Dell                            | 9         | 0.58%   |
| TP-Link                         | 8         | 0.51%   |
| NetGear                         | 8         | 0.51%   |
| Edimax Technology               | 7         | 0.45%   |
| Qualcomm                        | 4         | 0.26%   |
| ASUSTek Computer                | 4         | 0.26%   |
| Hewlett-Packard                 | 3         | 0.19%   |
| Qualcomm Atheros Communications | 2         | 0.13%   |
| D-Link                          | 2         | 0.13%   |
| Xiaomi                          | 1         | 0.06%   |
| Wilocity                        | 1         | 0.06%   |
| Belkin Components               | 1         | 0.06%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 61        | 3.89%   |
| Intel Wireless 8260                                                     | 60        | 3.83%   |
| Intel Wireless 8265 / 8275                                              | 54        | 3.44%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 49        | 3.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 49        | 3.13%   |
| Intel Wireless 7260                                                     | 49        | 3.13%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 46        | 2.93%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 44        | 2.81%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 40        | 2.55%   |
| Intel Wi-Fi 6 AX201                                                     | 39        | 2.49%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 38        | 2.42%   |
| Intel Wireless 3165                                                     | 36        | 2.3%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 35        | 2.23%   |
| Intel Centrino Ultimate-N 6300                                          | 35        | 2.23%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 33        | 2.1%    |
| Intel Wireless 7265                                                     | 30        | 1.91%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 30        | 1.91%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 29        | 1.85%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter    | 25        | 1.59%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 24        | 1.53%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 24        | 1.53%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 24        | 1.53%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 23        | 1.47%   |
| Intel Wireless-AC 9260                                                  | 21        | 1.34%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 21        | 1.34%   |
| Intel Wireless 3160                                                     | 20        | 1.28%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 19        | 1.21%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 18        | 1.15%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 17        | 1.08%   |
| Intel Centrino Advanced-N 6235                                          | 16        | 1.02%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 15        | 0.96%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 15        | 0.96%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 14        | 0.89%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 14        | 0.89%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 14        | 0.89%   |
| Intel Centrino Advanced-N 6200                                          | 14        | 0.89%   |
| Intel WiFi Link 5100                                                    | 13        | 0.83%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 12        | 0.77%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 12        | 0.77%   |
| Broadcom BCM43142 802.11b/g/n                                           | 12        | 0.77%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 674       | 52.17%  |
| Intel                            | 293       | 22.68%  |
| Qualcomm Atheros                 | 97        | 7.51%   |
| Broadcom                         | 82        | 6.35%   |
| Marvell Technology Group         | 18        | 1.39%   |
| DisplayLink                      | 17        | 1.32%   |
| Samsung Electronics              | 15        | 1.16%   |
| Broadcom Limited                 | 11        | 0.85%   |
| Apple                            | 11        | 0.85%   |
| Nvidia                           | 10        | 0.77%   |
| Lenovo                           | 10        | 0.77%   |
| Huawei Technologies              | 9         | 0.7%    |
| ZTE WCDMA Technologies MSM       | 8         | 0.62%   |
| ASIX Electronics                 | 7         | 0.54%   |
| OPPO Electronics                 | 6         | 0.46%   |
| JMicron Technology               | 4         | 0.31%   |
| Google                           | 4         | 0.31%   |
| Hewlett-Packard                  | 3         | 0.23%   |
| Xiaomi                           | 2         | 0.15%   |
| Silicon Integrated Systems [SiS] | 2         | 0.15%   |
| Qualcomm                         | 2         | 0.15%   |
| Microsoft                        | 2         | 0.15%   |
| ICS Advent                       | 2         | 0.15%   |
| T & A Mobile Phones              | 1         | 0.08%   |
| Motorola PCS                     | 1         | 0.08%   |
| Attansic Technology              | 1         | 0.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 437       | 33.28%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 126       | 9.6%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 88        | 6.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 69        | 5.26%   |
| Intel Ethernet Connection I219-LM                                 | 36        | 2.74%   |
| Intel Ethernet Connection (4) I219-LM                             | 22        | 1.68%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 21        | 1.6%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 20        | 1.52%   |
| Intel 82577LM Gigabit Network Connection                          | 20        | 1.52%   |
| Intel Ethernet Connection I218-LM                                 | 17        | 1.29%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 16        | 1.22%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 13        | 0.99%   |
| Intel Ethernet Connection (3) I218-LM                             | 12        | 0.91%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 12        | 0.91%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 11        | 0.84%   |
| Intel Ethernet Connection (4) I219-V                              | 11        | 0.84%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 10        | 0.76%   |
| Intel Ethernet Connection I219-V                                  | 10        | 0.76%   |
| Intel 82567LM Gigabit Network Connection                          | 10        | 0.76%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 10        | 0.76%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 9         | 0.69%   |
| Intel Ethernet Connection I217-LM                                 | 9         | 0.69%   |
| Realtek RTL8125 2.5GbE Controller                                 | 8         | 0.61%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 8         | 0.61%   |
| Realtek Killer E3000 2.5GbE Controller                            | 8         | 0.61%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 8         | 0.61%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 8         | 0.61%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 7         | 0.53%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 7         | 0.53%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 7         | 0.53%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 7         | 0.53%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 6         | 0.46%   |
| OPPO RMX2027                                                      | 6         | 0.46%   |
| Nvidia MCP79 Ethernet                                             | 6         | 0.46%   |
| Intel Ethernet Connection (7) I219-LM                             | 6         | 0.46%   |
| Huawei E353/E3131                                                 | 6         | 0.46%   |
| DisplayLink Dell Universal Dock D6000                             | 6         | 0.46%   |
| ASIX AX88179 Gigabit Ethernet                                     | 6         | 0.46%   |
| ZTE WCDMA MSM Unisoc Phone                                        | 5         | 0.38%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 5         | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1460      | 54.03%  |
| Ethernet | 1202      | 44.49%  |
| Modem    | 36        | 1.33%   |
| Unknown  | 4         | 0.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1210      | 77.61%  |
| Ethernet | 349       | 22.39%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1080      | 72.29%  |
| 1     | 391       | 26.17%  |
| 0     | 13        | 0.87%   |
| 3     | 10        | 0.67%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1304      | 86.13%  |
| Yes  | 210       | 13.87%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 596       | 49.67%  |
| Qualcomm Atheros Communications | 98        | 8.17%   |
| Apple                           | 95        | 7.92%   |
| Broadcom                        | 75        | 6.25%   |
| Realtek Semiconductor           | 69        | 5.75%   |
| IMC Networks                    | 47        | 3.92%   |
| Lite-On Technology              | 45        | 3.75%   |
| Foxconn / Hon Hai               | 43        | 3.58%   |
| Toshiba                         | 37        | 3.08%   |
| Hewlett-Packard                 | 21        | 1.75%   |
| Dell                            | 17        | 1.42%   |
| Ralink                          | 15        | 1.25%   |
| Cambridge Silicon Radio         | 10        | 0.83%   |
| Alps Electric                   | 7         | 0.58%   |
| Realtek                         | 6         | 0.5%    |
| ASUSTek Computer                | 6         | 0.5%    |
| Ralink Technology               | 4         | 0.33%   |
| USI                             | 3         | 0.25%   |
| Micro Star International        | 2         | 0.17%   |
| Taiyo Yuden                     | 1         | 0.08%   |
| Opticis                         | 1         | 0.08%   |
| MediaTek                        | 1         | 0.08%   |
| Belkin Components               | 1         | 0.08%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 234       | 19.5%   |
| Intel AX201 Bluetooth                               | 117       | 9.75%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 71        | 5.92%   |
| Intel AX200 Bluetooth                               | 61        | 5.08%   |
| Apple Bluetooth Host Controller                     | 51        | 4.25%   |
| Intel Bluetooth Device                              | 43        | 3.58%   |
| Realtek Bluetooth Radio                             | 39        | 3.25%   |
| Qualcomm Atheros  Bluetooth Device                  | 38        | 3.17%   |
| Apple Bluetooth USB Host Controller                 | 34        | 2.83%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 22        | 1.83%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 22        | 1.83%   |
| Realtek  Bluetooth 4.2 Adapter                      | 21        | 1.75%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 21        | 1.75%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 19        | 1.58%   |
| Intel AX210 Bluetooth                               | 19        | 1.58%   |
| IMC Networks Bluetooth Radio                        | 18        | 1.5%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 16        | 1.33%   |
| Broadcom BCM2045B (BDC-2.1)                         | 16        | 1.33%   |
| Ralink RT3290 Bluetooth                             | 15        | 1.25%   |
| Lite-On Atheros AR3012 Bluetooth                    | 15        | 1.25%   |
| Foxconn / Hon Hai Bluetooth Device                  | 15        | 1.25%   |
| Toshiba Bluetooth Device                            | 13        | 1.08%   |
| HP Broadcom 2070 Bluetooth Combo                    | 12        | 1%      |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 11        | 0.92%   |
| Intel Wireless-AC 3168 Bluetooth                    | 11        | 0.92%   |
| IMC Networks Wireless_Device                        | 10        | 0.83%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 10        | 0.83%   |
| Lite-On Bluetooth Device                            | 9         | 0.75%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 9         | 0.75%   |
| Toshiba Integrated Bluetooth HCI                    | 8         | 0.67%   |
| Foxconn / Hon Hai Wireless_Device                   | 8         | 0.67%   |
| Broadcom HP Portable SoftSailing                    | 8         | 0.67%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 8         | 0.67%   |
| Dell BCM20702A0 Bluetooth Module                    | 7         | 0.58%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 7         | 0.58%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 7         | 0.58%   |
| Realtek Bluetooth Radio                             | 6         | 0.5%    |
| Dell DW375 Bluetooth Module                         | 6         | 0.5%    |
| Broadcom BCM20702A0                                 | 6         | 0.5%    |
| IMC Networks Bluetooth                              | 5         | 0.42%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1238      | 63.68%  |
| Nvidia                                       | 273       | 14.04%  |
| AMD                                          | 272       | 13.99%  |
| Realtek Semiconductor                        | 20        | 1.03%   |
| Apple                                        | 11        | 0.57%   |
| GN Netcom                                    | 10        | 0.51%   |
| Razer USA                                    | 8         | 0.41%   |
| Lenovo                                       | 8         | 0.41%   |
| Logitech                                     | 7         | 0.36%   |
| Generalplus Technology                       | 7         | 0.36%   |
| Kingston Technology                          | 6         | 0.31%   |
| Creative Technology                          | 6         | 0.31%   |
| C-Media Electronics                          | 6         | 0.31%   |
| Hewlett-Packard                              | 5         | 0.26%   |
| Texas Instruments                            | 4         | 0.21%   |
| Plantronics                                  | 4         | 0.21%   |
| JMTek                                        | 4         | 0.21%   |
| OPPO Electronics                             | 3         | 0.15%   |
| Native Instruments                           | 3         | 0.15%   |
| Microsoft                                    | 3         | 0.15%   |
| Thermaltake                                  | 2         | 0.1%    |
| SteelSeries ApS                              | 2         | 0.1%    |
| Silicon Integrated Systems [SiS]             | 2         | 0.1%    |
| Samsung Electronics                          | 2         | 0.1%    |
| Micro Star International                     | 2         | 0.1%    |
| M-Audio                                      | 2         | 0.1%    |
| Dell                                         | 2         | 0.1%    |
| Corsair                                      | 2         | 0.1%    |
| Conexant Systems                             | 2         | 0.1%    |
| Chicony Electronics                          | 2         | 0.1%    |
| Blue Microphones                             | 2         | 0.1%    |
| Antlion Audio                                | 2         | 0.1%    |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.05%   |
| ZOOM                                         | 1         | 0.05%   |
| XMOS                                         | 1         | 0.05%   |
| ULi Electronics                              | 1         | 0.05%   |
| Thesycon Systemsoftware & Consulting         | 1         | 0.05%   |
| Spreadtrum Communications                    | 1         | 0.05%   |
| Sony                                         | 1         | 0.05%   |
| Sennheiser electronic                        | 1         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 180       | 7.77%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 154       | 6.65%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 112       | 4.84%   |
| AMD Family 17h/19h HD Audio Controller                                     | 107       | 4.62%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 83        | 3.58%   |
| Intel 8 Series HD Audio Controller                                         | 76        | 3.28%   |
| Intel Haswell-ULT HD Audio Controller                                      | 75        | 3.24%   |
| Intel Cannon Lake PCH cAVS                                                 | 73        | 3.15%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 58        | 2.5%    |
| Intel Broadwell-U Audio Controller                                         | 58        | 2.5%    |
| AMD FCH Azalia Controller                                                  | 56        | 2.42%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 54        | 2.33%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 53        | 2.29%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 50        | 2.16%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 48        | 2.07%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 44        | 1.9%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 42        | 1.81%   |
| AMD Kabini HDMI/DP Audio                                                   | 39        | 1.68%   |
| Intel Comet Lake PCH cAVS                                                  | 38        | 1.64%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 33        | 1.42%   |
| Intel Comet Lake PCH-LP cAVS                                               | 32        | 1.38%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 31        | 1.34%   |
| Nvidia GF108 High Definition Audio Controller                              | 28        | 1.21%   |
| Intel CM238 HD Audio Controller                                            | 27        | 1.17%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 27        | 1.17%   |
| AMD High Definition Audio Controller                                       | 26        | 1.12%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 25        | 1.08%   |
| Nvidia GK107 HDMI Audio Controller                                         | 23        | 0.99%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 23        | 0.99%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 21        | 0.91%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 21        | 0.91%   |
| Nvidia TU106 High Definition Audio Controller                              | 19        | 0.82%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 19        | 0.82%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 19        | 0.82%   |
| Nvidia TU116 High Definition Audio Controller                              | 18        | 0.78%   |
| Realtek Semiconductor USB Audio                                            | 17        | 0.73%   |
| Nvidia GP107GL High Definition Audio Controller                            | 17        | 0.73%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 17        | 0.73%   |
| Nvidia Audio device                                                        | 16        | 0.69%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 16        | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Samsung Electronics        | 276       | 31.62%  |
| SK hynix                   | 219       | 25.09%  |
| Micron Technology          | 125       | 14.32%  |
| Kingston                   | 74        | 8.48%   |
| Crucial                    | 42        | 4.81%   |
| Unknown                    | 29        | 3.32%   |
| Elpida                     | 23        | 2.63%   |
| Ramaxel Technology         | 12        | 1.37%   |
| Nanya Technology           | 10        | 1.15%   |
| Team                       | 9         | 1.03%   |
| Corsair                    | 9         | 1.03%   |
| A-DATA Technology          | 8         | 0.92%   |
| G.Skill                    | 5         | 0.57%   |
| Apacer                     | 4         | 0.46%   |
| Unknown                    | 4         | 0.46%   |
| Unknown (ABCD)             | 2         | 0.23%   |
| Transcend                  | 2         | 0.23%   |
| Toshiba                    | 2         | 0.23%   |
| Smart                      | 2         | 0.23%   |
| Silicon Power              | 2         | 0.23%   |
| Patriot                    | 2         | 0.23%   |
| Unknown (0x89AD)           | 1         | 0.11%   |
| Unknown (0x873E)           | 1         | 0.11%   |
| Qimonda                    | 1         | 0.11%   |
| pqi                        | 1         | 0.11%   |
| Netlist                    | 1         | 0.11%   |
| Neo Forza                  | 1         | 0.11%   |
| GSkill                     | 1         | 0.11%   |
| ff                         | 1         | 0.11%   |
| Avant                      | 1         | 0.11%   |
| ASint Technology           | 1         | 0.11%   |
| Anucell Technology Holding | 1         | 0.11%   |
| 4ea5                       | 1         | 0.11%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 18        | 1.94%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 13        | 1.4%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 13        | 1.4%    |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 11        | 1.18%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 11        | 1.18%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 11        | 1.18%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 11        | 1.18%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 10        | 1.08%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 9         | 0.97%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 9         | 0.97%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 8         | 0.86%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 0.86%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 7         | 0.75%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 7         | 0.75%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 7         | 0.75%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 7         | 0.75%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 0.75%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 7         | 0.75%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 0.65%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 6         | 0.65%   |
| SK hynix RAM H9HCNNNCPMALHR-NEE 8GB Row Of Chips LPDDR4 4800MT/s | 6         | 0.65%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 6         | 0.65%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s    | 6         | 0.65%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 6         | 0.65%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 6         | 0.65%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 5         | 0.54%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                     | 5         | 0.54%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 5         | 0.54%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 5         | 0.54%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 5         | 0.54%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 5         | 0.54%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 5         | 0.54%   |
| Elpida RAM EBJ21UE8BDS0-DJ-F 2GB SODIMM DDR3 1334MT/s            | 5         | 0.54%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 4         | 0.43%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 4         | 0.43%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 4         | 0.43%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 4         | 0.43%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 4         | 0.43%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 4         | 0.43%   |
| Samsung RAM M471B5773DH0-CH9 2048MB SODIMM DDR3 1600MT/s         | 4         | 0.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 321       | 42.52%  |
| DDR3    | 290       | 38.41%  |
| LPDDR3  | 48        | 6.36%   |
| LPDDR4  | 29        | 3.84%   |
| DDR2    | 25        | 3.31%   |
| LPDDR5  | 14        | 1.85%   |
| DDR5    | 12        | 1.59%   |
| SDRAM   | 10        | 1.32%   |
| Unknown | 3         | 0.4%    |
| DDR     | 2         | 0.26%   |
| DRAM    | 1         | 0.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 657       | 86.9%   |
| Row Of Chips | 86        | 11.38%  |
| Chip         | 9         | 1.19%   |
| Unknown      | 3         | 0.4%    |
| DIMM         | 1         | 0.13%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 317       | 39.38%  |
| 4096  | 222       | 27.58%  |
| 16384 | 134       | 16.65%  |
| 2048  | 88        | 10.93%  |
| 32768 | 27        | 3.35%   |
| 1024  | 12        | 1.49%   |
| 512   | 3         | 0.37%   |
| 1536  | 1         | 0.12%   |
| 256   | 1         | 0.12%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 206       | 25.43%  |
| 2667    | 161       | 19.88%  |
| 3200    | 123       | 15.19%  |
| 1334    | 54        | 6.67%   |
| 2133    | 50        | 6.17%   |
| 2400    | 42        | 5.19%   |
| 1333    | 21        | 2.59%   |
| 1067    | 20        | 2.47%   |
| 1867    | 18        | 2.22%   |
| 4800    | 16        | 1.98%   |
| 6400    | 14        | 1.73%   |
| 667     | 13        | 1.6%    |
| Unknown | 12        | 1.48%   |
| 4267    | 11        | 1.36%   |
| 8400    | 7         | 0.86%   |
| 3266    | 7         | 0.86%   |
| 1066    | 7         | 0.86%   |
| 4266    | 6         | 0.74%   |
| 800     | 6         | 0.74%   |
| 2048    | 4         | 0.49%   |
| 4199    | 3         | 0.37%   |
| 5600    | 2         | 0.25%   |
| 3733    | 2         | 0.25%   |
| 975     | 2         | 0.25%   |
| 533     | 2         | 0.25%   |
| 1639    | 1         | 0.12%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Brother Industries  | 4         | 40%     |
| Hewlett-Packard     | 3         | 30%     |
| Canon               | 2         | 20%     |
| Samsung Electronics | 1         | 10%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                       | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Canon TS3100 series         | 2         | 20%     |
| Brother HL-1110 series      | 2         | 20%     |
| Samsung ML-1865             | 1         | 10%     |
| HP LaserJet Pro M201dw      | 1         | 10%     |
| HP ENVY Inspire 7900 series | 1         | 10%     |
| HP DeskJet 2300 series      | 1         | 10%     |
| Brother MFC-1810            | 1         | 10%     |
| Brother HL-2140 series      | 1         | 10%     |

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
| Canon CanoScan LiDE 220 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 357       | 26.23%  |
| Microdia                               | 126       | 9.26%   |
| IMC Networks                           | 109       | 8.01%   |
| Realtek Semiconductor                  | 108       | 7.94%   |
| Sunplus Innovation Technology          | 101       | 7.42%   |
| Apple                                  | 82        | 6.02%   |
| Bison Electronics                      | 61        | 4.48%   |
| Quanta                                 | 59        | 4.34%   |
| Cheng Uei Precision Industry (Foxlink) | 56        | 4.11%   |
| Suyin                                  | 51        | 3.75%   |
| Logitech                               | 34        | 2.5%    |
| Acer                                   | 29        | 2.13%   |
| Lite-On Technology                     | 23        | 1.69%   |
| Syntek                                 | 20        | 1.47%   |
| Luxvisions Innotech Limited            | 17        | 1.25%   |
| Silicon Motion                         | 13        | 0.96%   |
| Samsung Electronics                    | 13        | 0.96%   |
| Importek                               | 12        | 0.88%   |
| Ricoh                                  | 10        | 0.73%   |
| Alcor Micro                            | 8         | 0.59%   |
| Sonix Technology                       | 7         | 0.51%   |
| Primax Electronics                     | 7         | 0.51%   |
| Lenovo                                 | 7         | 0.51%   |
| Razer USA                              | 4         | 0.29%   |
| OmniVision Technologies                | 4         | 0.29%   |
| Magic Control Technology               | 4         | 0.29%   |
| DigiTech                               | 4         | 0.29%   |
| ALi                                    | 4         | 0.29%   |
| Z-Star Microelectronics                | 3         | 0.22%   |
| LG Electronics                         | 3         | 0.22%   |
| icSpring                               | 3         | 0.22%   |
| SunplusIT                              | 2         | 0.15%   |
| OPPO Electronics                       | 2         | 0.15%   |
| Microsoft                              | 2         | 0.15%   |
| Genesys Logic                          | 2         | 0.15%   |
| GEMBIRD                                | 2         | 0.15%   |
| Tobii Technology AB                    | 1         | 0.07%   |
| Sunplus Technology                     | 1         | 0.07%   |
| Solid Year                             | 1         | 0.07%   |
| Mimaki Engineering                     | 1         | 0.07%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                           | 70        | 5.08%   |
| Chicony Integrated Camera                               | 64        | 4.64%   |
| Chicony HD WebCam                                       | 35        | 2.54%   |
| Realtek Integrated_Webcam_HD                            | 32        | 2.32%   |
| Sunplus Integrated_Webcam_HD                            | 28        | 2.03%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 28        | 2.03%   |
| Chicony TOSHIBA Web Camera - HD                         | 27        | 1.96%   |
| IMC Networks Integrated Camera                          | 24        | 1.74%   |
| Apple FaceTime HD Camera (Built-in)                     | 22        | 1.6%    |
| Apple FaceTime HD Camera                                | 19        | 1.38%   |
| Apple Built-in iSight                                   | 19        | 1.38%   |
| Chicony HP TrueVision HD Camera                         | 18        | 1.31%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                         | 18        | 1.31%   |
| Chicony HP TrueVision HD                                | 17        | 1.23%   |
| Sunplus HD WebCam                                       | 16        | 1.16%   |
| Chicony HD User Facing                                  | 15        | 1.09%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 14        | 1.02%   |
| Syntek Integrated Camera                                | 13        | 0.94%   |
| Samsung Galaxy series, misc. (MTP mode)                 | 13        | 0.94%   |
| Bison Integrated Camera                                 | 13        | 0.94%   |
| Suyin HP TrueVision HD                                  | 12        | 0.87%   |
| Realtek USB Camera                                      | 12        | 0.87%   |
| Chicony HP HD Camera                                    | 12        | 0.87%   |
| Quanta HD User Facing                                   | 11        | 0.8%    |
| Lite-On Integrated Camera                               | 11        | 0.8%    |
| Chicony USB2.0 Camera                                   | 11        | 0.8%    |
| Chicony CNF9055 Toshiba Webcam                          | 11        | 0.8%    |
| Quanta HP TrueVision HD Camera                          | 10        | 0.73%   |
| Microdia Integrated Webcam                              | 10        | 0.73%   |
| Bison HD Webcam                                         | 10        | 0.73%   |
| Acer Integrated Camera                                  | 10        | 0.73%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera     | 9         | 0.65%   |
| Realtek Integrated Webcam HD                            | 8         | 0.58%   |
| Quanta HP Webcam                                        | 8         | 0.58%   |
| Quanta HD Webcam                                        | 8         | 0.58%   |
| Logitech Webcam C270                                    | 8         | 0.58%   |
| Chicony VGA WebCam                                      | 8         | 0.58%   |
| Chicony Integrated Camera (1280x720@30)                 | 8         | 0.58%   |
| Realtek USB2.0-Camera                                   | 7         | 0.51%   |
| Realtek USB2.0 HD UVC WebCam                            | 7         | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 131       | 44.56%  |
| Synaptics                  | 55        | 18.71%  |
| Shenzhen Goodix Technology | 34        | 11.56%  |
| LighTuning Technology      | 21        | 7.14%   |
| AuthenTec                  | 18        | 6.12%   |
| Upek                       | 14        | 4.76%   |
| Elan Microelectronics      | 13        | 4.42%   |
| STMicroelectronics         | 7         | 2.38%   |
| Focal-systems.Corp         | 1         | 0.34%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 27        | 9.18%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 22        | 7.48%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 14        | 4.76%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 13        | 4.42%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 12        | 4.08%   |
| Validity Sensors Fingerprint scanner                                       | 12        | 4.08%   |
| Shenzhen Goodix  Fingerprint Device                                        | 12        | 4.08%   |
| Validity Sensors VFS491                                                    | 11        | 3.74%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 11        | 3.74%   |
| Shenzhen Goodix Fingerprint Reader                                         | 11        | 3.74%   |
| Shenzhen Goodix FingerPrint                                                | 11        | 3.74%   |
| Validity Sensors Synaptics WBDI                                            | 9         | 3.06%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 8         | 2.72%   |
| Validity Sensors VFS Fingerprint sensor                                    | 8         | 2.72%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 8         | 2.72%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 7         | 2.38%   |
| STMicroelectronics Fingerprint Reader                                      | 7         | 2.38%   |
| Elan ELAN:Fingerprint                                                      | 7         | 2.38%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 7         | 2.38%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 6         | 2.04%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 6         | 2.04%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 6         | 2.04%   |
| Elan ELAN:ARM-M4                                                           | 6         | 2.04%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 5         | 1.7%    |
| Synaptics WBDI Device                                                      | 5         | 1.7%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 1.36%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 4         | 1.36%   |
| AuthenTec AES1600                                                          | 4         | 1.36%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 3         | 1.02%   |
| Synaptics  WBDI                                                            | 3         | 1.02%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 1.02%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 1.02%   |
| Synaptics UWP WBDI Device                                                  | 2         | 0.68%   |
| Synaptics UWP WBDI                                                         | 2         | 0.68%   |
| Synaptics TouchPad                                                         | 2         | 0.68%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 2         | 0.68%   |
| LighTuning Fingerprint Reader                                              | 2         | 0.68%   |
| AuthenTec AES2810                                                          | 2         | 0.68%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 2         | 0.68%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.34%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 38        | 62.3%   |
| Alcor Micro           | 13        | 21.31%  |
| Upek                  | 4         | 6.56%   |
| Lenovo                | 3         | 4.92%   |
| O2 Micro              | 2         | 3.28%   |
| Advanced Card Systems | 1         | 1.64%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 17        | 27.87%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 13        | 21.31%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 8         | 13.11%  |
| Broadcom 58200                                                               | 7         | 11.48%  |
| Broadcom 5880                                                                | 6         | 9.84%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 6.56%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 4.92%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 3.28%   |
| Advanced Card Systems ACR122U                                                | 1         | 1.64%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 917       | 58.97%  |
| 1     | 517       | 33.25%  |
| 2     | 98        | 6.3%    |
| 3     | 16        | 1.03%   |
| 4     | 6         | 0.39%   |
| 5     | 1         | 0.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 292       | 39.19%  |
| Graphics card            | 149       | 20%     |
| Net/wireless             | 68        | 9.13%   |
| Multimedia controller    | 56        | 7.52%   |
| Chipcard                 | 55        | 7.38%   |
| Bluetooth                | 26        | 3.49%   |
| Camera                   | 23        | 3.09%   |
| Storage                  | 17        | 2.28%   |
| Net/ethernet             | 14        | 1.88%   |
| Communication controller | 14        | 1.88%   |
| Modem                    | 10        | 1.34%   |
| Sound                    | 8         | 1.07%   |
| Card reader              | 8         | 1.07%   |
| Video                    | 1         | 0.13%   |
| Unassigned class         | 1         | 0.13%   |
| Storage/ide              | 1         | 0.13%   |
| Storage/ata              | 1         | 0.13%   |
| Flash memory             | 1         | 0.13%   |

