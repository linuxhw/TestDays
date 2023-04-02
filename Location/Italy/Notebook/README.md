Linux in Italy - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------

A project to collect tested hardware configurations for Linux in Italy.

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

Total: 5741

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | V110-15ISK 80TL             | [db058df07b](https://linux-hardware.org/?probe=db058df07b) | Apr 01, 2023 |
| Lenovo        | V110-15ISK 80TL             | [3691be13e8](https://linux-hardware.org/?probe=3691be13e8) | Apr 01, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [70fb59cd4f](https://linux-hardware.org/?probe=70fb59cd4f) | Apr 01, 2023 |
| Unknown       | Unknown                     | [702a241ca6](https://linux-hardware.org/?probe=702a241ca6) | Apr 01, 2023 |
| Lenovo        | G50-45 80E3                 | [f75af97954](https://linux-hardware.org/?probe=f75af97954) | Apr 01, 2023 |
| HP            | Notebook                    | [7cb279c8e0](https://linux-hardware.org/?probe=7cb279c8e0) | Apr 01, 2023 |
| HP            | Pavilion x2 Detachable      | [363d925d25](https://linux-hardware.org/?probe=363d925d25) | Apr 01, 2023 |
| ASUSTek       | X556UAK                     | [24f79c68f6](https://linux-hardware.org/?probe=24f79c68f6) | Mar 31, 2023 |
| Notebook      | W54_55SU1,SUW               | [74313ae73b](https://linux-hardware.org/?probe=74313ae73b) | Mar 31, 2023 |
| Microtech     | ebookPro                    | [ffe1da27cc](https://linux-hardware.org/?probe=ffe1da27cc) | Mar 31, 2023 |
| Acer          | Extensa 215-31              | [b1601e6747](https://linux-hardware.org/?probe=b1601e6747) | Mar 31, 2023 |
| Dell          | Latitude E7440              | [fdd9fda693](https://linux-hardware.org/?probe=fdd9fda693) | Mar 31, 2023 |
| HP            | Pavilion 15                 | [4dc2c9dfc1](https://linux-hardware.org/?probe=4dc2c9dfc1) | Mar 31, 2023 |
| Lenovo        | ThinkPad E14 20RA0016IX     | [685f18f5b3](https://linux-hardware.org/?probe=685f18f5b3) | Mar 31, 2023 |
| Lenovo        | Yoga 3 11 80J8              | [fce7483fa0](https://linux-hardware.org/?probe=fce7483fa0) | Mar 31, 2023 |
| Olivetti      | Spring Peak                 | [9678c685d7](https://linux-hardware.org/?probe=9678c685d7) | Mar 31, 2023 |
| Olivetti      | Spring Peak                 | [7878f53f36](https://linux-hardware.org/?probe=7878f53f36) | Mar 31, 2023 |
| Valve         | Jupiter                     | [34766581f3](https://linux-hardware.org/?probe=34766581f3) | Mar 31, 2023 |
| Toshiba       | Satellite Pro S500          | [b2e60d9170](https://linux-hardware.org/?probe=b2e60d9170) | Mar 31, 2023 |
| ASUSTek       | N552VX                      | [cacf95c277](https://linux-hardware.org/?probe=cacf95c277) | Mar 30, 2023 |
| Acer          | Aspire ES1-523              | [a800dab0ab](https://linux-hardware.org/?probe=a800dab0ab) | Mar 30, 2023 |
| Sony          | SVE1713X1EB                 | [8953aa2e04](https://linux-hardware.org/?probe=8953aa2e04) | Mar 30, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [45f39402f0](https://linux-hardware.org/?probe=45f39402f0) | Mar 30, 2023 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | [976d8a1a13](https://linux-hardware.org/?probe=976d8a1a13) | Mar 30, 2023 |
| Dell          | Precision 3560              | [f6ef5c1a2c](https://linux-hardware.org/?probe=f6ef5c1a2c) | Mar 30, 2023 |
| Lenovo        | G505 20240                  | [25c5c7ee2e](https://linux-hardware.org/?probe=25c5c7ee2e) | Mar 30, 2023 |
| Toshiba       | Satellite L655              | [2e6ea8bf5c](https://linux-hardware.org/?probe=2e6ea8bf5c) | Mar 30, 2023 |
| Dell          | Latitude 5580               | [84157deda8](https://linux-hardware.org/?probe=84157deda8) | Mar 29, 2023 |
| Fujitsu       | LIFEBOOK A555               | [6f28f9e6ec](https://linux-hardware.org/?probe=6f28f9e6ec) | Mar 29, 2023 |
| MSI           | Prestige 14Evo A11M         | [fc06b01f31](https://linux-hardware.org/?probe=fc06b01f31) | Mar 29, 2023 |
| MSI           | Prestige 14Evo A11M         | [5ac693dbd4](https://linux-hardware.org/?probe=5ac693dbd4) | Mar 29, 2023 |
| Lenovo        | ThinkPad T440 20B7A0CYMH    | [428491a9d5](https://linux-hardware.org/?probe=428491a9d5) | Mar 29, 2023 |
| HP            | Laptop 15-dw0xxx            | [53bc341050](https://linux-hardware.org/?probe=53bc341050) | Mar 29, 2023 |
| Valve         | Jupiter                     | [889e4e5eef](https://linux-hardware.org/?probe=889e4e5eef) | Mar 29, 2023 |
| HP            | ProBook 640 G1              | [c9ac2eb353](https://linux-hardware.org/?probe=c9ac2eb353) | Mar 28, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [5520b0fc5f](https://linux-hardware.org/?probe=5520b0fc5f) | Mar 28, 2023 |
| HP            | OMEN Laptop 15-ek0xxx       | [f44d26ed76](https://linux-hardware.org/?probe=f44d26ed76) | Mar 28, 2023 |
| Acer          | Swift SF314-511             | [ccef379a7f](https://linux-hardware.org/?probe=ccef379a7f) | Mar 28, 2023 |
| HP            | ProBook 450 G7              | [8b27d78a17](https://linux-hardware.org/?probe=8b27d78a17) | Mar 28, 2023 |
| Dell          | Inspiron 16 5630            | [5838554410](https://linux-hardware.org/?probe=5838554410) | Mar 28, 2023 |
| ASUSTek       | N53SV                       | [77aa77b2a3](https://linux-hardware.org/?probe=77aa77b2a3) | Mar 28, 2023 |
| Unknown       | Unknown                     | [26d819f9fc](https://linux-hardware.org/?probe=26d819f9fc) | Mar 27, 2023 |
| HP            | 250 G1                      | [75cf798dde](https://linux-hardware.org/?probe=75cf798dde) | Mar 27, 2023 |
| Sony          | SVE1713X1EB                 | [fa77641b57](https://linux-hardware.org/?probe=fa77641b57) | Mar 27, 2023 |
| Dell          | XPS 13 9305                 | [2f96abf16a](https://linux-hardware.org/?probe=2f96abf16a) | Mar 27, 2023 |
| Dell          | XPS 13 9305                 | [07caea9176](https://linux-hardware.org/?probe=07caea9176) | Mar 27, 2023 |
| Acer          | Mammoth                     | [d43ab9891b](https://linux-hardware.org/?probe=d43ab9891b) | Mar 27, 2023 |
| Sony          | VPCEH1S1E                   | [081294b14c](https://linux-hardware.org/?probe=081294b14c) | Mar 27, 2023 |
| Lenovo        | G50-45 80E3                 | [279d3659a9](https://linux-hardware.org/?probe=279d3659a9) | Mar 26, 2023 |
| ASUSTek       | X550LD                      | [6ac498fa82](https://linux-hardware.org/?probe=6ac498fa82) | Mar 26, 2023 |
| ASUSTek       | N552VW                      | [322426698a](https://linux-hardware.org/?probe=322426698a) | Mar 26, 2023 |
| Apple         | MacBookPro11,5              | [0c2be4a34c](https://linux-hardware.org/?probe=0c2be4a34c) | Mar 26, 2023 |
| Dell          | XPS 13 9305                 | [5b29fbd6ac](https://linux-hardware.org/?probe=5b29fbd6ac) | Mar 26, 2023 |
| Sony          | SVE1713X1EB                 | [cf11e69c46](https://linux-hardware.org/?probe=cf11e69c46) | Mar 26, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [55c29cec29](https://linux-hardware.org/?probe=55c29cec29) | Mar 26, 2023 |
| HP            | Compaq 6730s                | [ca30390612](https://linux-hardware.org/?probe=ca30390612) | Mar 25, 2023 |
| HP            | Laptop 15-dw3xxx            | [3b8cd70b69](https://linux-hardware.org/?probe=3b8cd70b69) | Mar 25, 2023 |
| MSI           | Katana GF66 12UG            | [9e03ac14c0](https://linux-hardware.org/?probe=9e03ac14c0) | Mar 25, 2023 |
| Lenovo        | V130-15IKB 81HN             | [0bfaf1252f](https://linux-hardware.org/?probe=0bfaf1252f) | Mar 25, 2023 |
| Dell          | Latitude E6230              | [1a248bdc33](https://linux-hardware.org/?probe=1a248bdc33) | Mar 25, 2023 |
| Acer          | Aspire A517-52G             | [ce3133a010](https://linux-hardware.org/?probe=ce3133a010) | Mar 25, 2023 |
| ASUSTek       | GL503VS                     | [8e066fcf6e](https://linux-hardware.org/?probe=8e066fcf6e) | Mar 25, 2023 |
| Lenovo        | Z50-75 80EC                 | [d6783c57a6](https://linux-hardware.org/?probe=d6783c57a6) | Mar 24, 2023 |
| Lenovo        | Z50-75 80EC                 | [353666c217](https://linux-hardware.org/?probe=353666c217) | Mar 24, 2023 |
| Dell          | XPS 13 9305                 | [c7e354ffe3](https://linux-hardware.org/?probe=c7e354ffe3) | Mar 24, 2023 |
| Apple         | MacBookPro11,5              | [9fd6508caf](https://linux-hardware.org/?probe=9fd6508caf) | Mar 24, 2023 |
| Dell          | Latitude 5580               | [d4ad4c55a6](https://linux-hardware.org/?probe=d4ad4c55a6) | Mar 24, 2023 |
| ASUSTek       | K53SJ                       | [175f99ccdd](https://linux-hardware.org/?probe=175f99ccdd) | Mar 23, 2023 |
| Acer          | Aspire E3-112               | [721e804a03](https://linux-hardware.org/?probe=721e804a03) | Mar 23, 2023 |
| HUAWEI        | BOD-WXX9                    | [088494906d](https://linux-hardware.org/?probe=088494906d) | Mar 23, 2023 |
| HP            | ProBook 440 G8 Notebook ... | [aba9609828](https://linux-hardware.org/?probe=aba9609828) | Mar 23, 2023 |
| Dell          | Inspiron 1750               | [007a0b3bb7](https://linux-hardware.org/?probe=007a0b3bb7) | Mar 22, 2023 |
| Dell          | XPS 9315                    | [b082aa6edf](https://linux-hardware.org/?probe=b082aa6edf) | Mar 22, 2023 |
| Dell          | XPS 9315                    | [9a14590477](https://linux-hardware.org/?probe=9a14590477) | Mar 22, 2023 |
| TrekStor      | Notebook Slim S130          | [6c3a6e7e53](https://linux-hardware.org/?probe=6c3a6e7e53) | Mar 22, 2023 |
| Toshiba       | Satellite Pro S500          | [2bb2519c2c](https://linux-hardware.org/?probe=2bb2519c2c) | Mar 21, 2023 |
| Toshiba       | Satellite Pro S500          | [a45c7086e5](https://linux-hardware.org/?probe=a45c7086e5) | Mar 21, 2023 |
| Dell          | XPS 15 9570                 | [6fc76628d3](https://linux-hardware.org/?probe=6fc76628d3) | Mar 21, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [b4d5442d02](https://linux-hardware.org/?probe=b4d5442d02) | Mar 21, 2023 |
| MSI           | Prestige 14Evo A11M         | [cac8d6b991](https://linux-hardware.org/?probe=cac8d6b991) | Mar 21, 2023 |
| HP            | Pavilion Laptop 15-cs2xx... | [6d96576431](https://linux-hardware.org/?probe=6d96576431) | Mar 21, 2023 |
| Dell          | Inspiron 5570               | [e311e9a53a](https://linux-hardware.org/?probe=e311e9a53a) | Mar 21, 2023 |
| Acer          | Extensa 5235                | [270cd6ed83](https://linux-hardware.org/?probe=270cd6ed83) | Mar 20, 2023 |
| Lenovo        | ThinkPad T480s 20L8002WM... | [762762da77](https://linux-hardware.org/?probe=762762da77) | Mar 20, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [0a71696d3b](https://linux-hardware.org/?probe=0a71696d3b) | Mar 20, 2023 |
| HP            | Laptop 15s-eq3xxx           | [83fbe3a3d6](https://linux-hardware.org/?probe=83fbe3a3d6) | Mar 20, 2023 |
| Notebook      | P15SM                       | [00d7786f9f](https://linux-hardware.org/?probe=00d7786f9f) | Mar 19, 2023 |
| Microtech     | CoreBook                    | [d50c0297a6](https://linux-hardware.org/?probe=d50c0297a6) | Mar 19, 2023 |
| HP            | G62                         | [2cb4092da0](https://linux-hardware.org/?probe=2cb4092da0) | Mar 19, 2023 |
| HP            | G62                         | [76d7e36f21](https://linux-hardware.org/?probe=76d7e36f21) | Mar 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [cbad8c5f1e](https://linux-hardware.org/?probe=cbad8c5f1e) | Mar 18, 2023 |
| Lenovo        | ThinkPad T460s 20FAS6PN0... | [bb86a34180](https://linux-hardware.org/?probe=bb86a34180) | Mar 18, 2023 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [a3339e152a](https://linux-hardware.org/?probe=a3339e152a) | Mar 18, 2023 |
| HP            | Laptop 15-dw1xxx            | [63ecda6230](https://linux-hardware.org/?probe=63ecda6230) | Mar 18, 2023 |
| HP            | ProBook 6570b               | [f5c9cd8419](https://linux-hardware.org/?probe=f5c9cd8419) | Mar 17, 2023 |
| HP            | 255 G3                      | [3e5f860704](https://linux-hardware.org/?probe=3e5f860704) | Mar 17, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [2530e262d2](https://linux-hardware.org/?probe=2530e262d2) | Mar 17, 2023 |
| ASUSTek       | K61IC                       | [045474725b](https://linux-hardware.org/?probe=045474725b) | Mar 17, 2023 |
| Lenovo        | ThinkPad T480s 20L8S88M0... | [2ad89b7995](https://linux-hardware.org/?probe=2ad89b7995) | Mar 16, 2023 |
| HP            | Pavilion Laptop 15-ck0xx    | [6a1e908693](https://linux-hardware.org/?probe=6a1e908693) | Mar 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [2cb5e6ce4f](https://linux-hardware.org/?probe=2cb5e6ce4f) | Mar 16, 2023 |
| Dell          | Latitude E5470              | [cc4f08349d](https://linux-hardware.org/?probe=cc4f08349d) | Mar 16, 2023 |
| MSI           | Modern 14 B11MOL            | [33bbc272c0](https://linux-hardware.org/?probe=33bbc272c0) | Mar 15, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [c454542aaa](https://linux-hardware.org/?probe=c454542aaa) | Mar 15, 2023 |
| Valve         | Jupiter                     | [fc387a787e](https://linux-hardware.org/?probe=fc387a787e) | Mar 15, 2023 |
| Toshiba       | Satellite Pro S500          | [0065669867](https://linux-hardware.org/?probe=0065669867) | Mar 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [b0b311216d](https://linux-hardware.org/?probe=b0b311216d) | Mar 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [0f6370d7f7](https://linux-hardware.org/?probe=0f6370d7f7) | Mar 14, 2023 |
| ASUSTek       | U36SD                       | [74e2dfbbc6](https://linux-hardware.org/?probe=74e2dfbbc6) | Mar 14, 2023 |
| HP            | Pavilion Laptop 15-ck0xx    | [d9f9e09a41](https://linux-hardware.org/?probe=d9f9e09a41) | Mar 14, 2023 |
| HP            | Pavilion Laptop 15-ck0xx    | [be16fd4aab](https://linux-hardware.org/?probe=be16fd4aab) | Mar 13, 2023 |
| ASUSTek       | GL753VE                     | [8100c63113](https://linux-hardware.org/?probe=8100c63113) | Mar 13, 2023 |
| HP            | Pavilion dv6500             | [03097b6049](https://linux-hardware.org/?probe=03097b6049) | Mar 13, 2023 |
| Dell          | XPS 15 9570                 | [456057e6af](https://linux-hardware.org/?probe=456057e6af) | Mar 13, 2023 |
| Dell          | XPS 15 9570                 | [7ee93079fb](https://linux-hardware.org/?probe=7ee93079fb) | Mar 13, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [ee01825196](https://linux-hardware.org/?probe=ee01825196) | Mar 13, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [a7d30f68b1](https://linux-hardware.org/?probe=a7d30f68b1) | Mar 12, 2023 |
| Acer          | aspire5740                  | [d5e64f31d4](https://linux-hardware.org/?probe=d5e64f31d4) | Mar 12, 2023 |
| HP            | Laptop 15s-fq5xxx           | [5bf763c288](https://linux-hardware.org/?probe=5bf763c288) | Mar 11, 2023 |
| Dell          | Latitude E6440              | [e5ba284442](https://linux-hardware.org/?probe=e5ba284442) | Mar 11, 2023 |
| HP            | G61                         | [2f5e9f6f43](https://linux-hardware.org/?probe=2f5e9f6f43) | Mar 11, 2023 |
| Sony          | SVE1713X1EB                 | [2a7d9091ff](https://linux-hardware.org/?probe=2a7d9091ff) | Mar 11, 2023 |
| ASUSTek       | X556UQK                     | [e5c898a856](https://linux-hardware.org/?probe=e5c898a856) | Mar 11, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [d7ed4aaf2c](https://linux-hardware.org/?probe=d7ed4aaf2c) | Mar 11, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [4664479644](https://linux-hardware.org/?probe=4664479644) | Mar 11, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [6e97141469](https://linux-hardware.org/?probe=6e97141469) | Mar 10, 2023 |
| HP            | EliteBook 840 G1            | [1315898b67](https://linux-hardware.org/?probe=1315898b67) | Mar 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [ffcc55bb14](https://linux-hardware.org/?probe=ffcc55bb14) | Mar 10, 2023 |
| Lenovo        | ThinkPad T460 20LPS3K002    | [c375b36f4a](https://linux-hardware.org/?probe=c375b36f4a) | Mar 10, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [420b463f4d](https://linux-hardware.org/?probe=420b463f4d) | Mar 10, 2023 |
| ASUSTek       | X540LA                      | [de3c24e686](https://linux-hardware.org/?probe=de3c24e686) | Mar 10, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [041ebfc8c6](https://linux-hardware.org/?probe=041ebfc8c6) | Mar 09, 2023 |
| Lenovo        | ThinkPad T440p 20AWS0XX0... | [780937bb9f](https://linux-hardware.org/?probe=780937bb9f) | Mar 09, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [ffbffb33ae](https://linux-hardware.org/?probe=ffbffb33ae) | Mar 09, 2023 |
| Fujitsu       | LIFEBOOK U7312              | [74bbf2c865](https://linux-hardware.org/?probe=74bbf2c865) | Mar 09, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [796b1ad7cb](https://linux-hardware.org/?probe=796b1ad7cb) | Mar 09, 2023 |
| HP            | Compaq Presario CQ60        | [4167bec602](https://linux-hardware.org/?probe=4167bec602) | Mar 09, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [8faa1d14ca](https://linux-hardware.org/?probe=8faa1d14ca) | Mar 08, 2023 |
| Lenovo        | ThinkPad E490 20N9S21H00    | [0bb64aee2c](https://linux-hardware.org/?probe=0bb64aee2c) | Mar 08, 2023 |
| HP            | Pavilion x2 Detachable      | [04ef76ee4a](https://linux-hardware.org/?probe=04ef76ee4a) | Mar 07, 2023 |
| Timi          | TM1701                      | [3a94d06b73](https://linux-hardware.org/?probe=3a94d06b73) | Mar 07, 2023 |
| HP            | Pavilion dv6                | [a1631eb10b](https://linux-hardware.org/?probe=a1631eb10b) | Mar 07, 2023 |
| Unknown       | Unknown                     | [fdc4f4d3c6](https://linux-hardware.org/?probe=fdc4f4d3c6) | Mar 07, 2023 |
| Dell          | Latitude 5330               | [c99cbe9970](https://linux-hardware.org/?probe=c99cbe9970) | Mar 07, 2023 |
| HP            | EliteBook 840 G1            | [f56dc75b4e](https://linux-hardware.org/?probe=f56dc75b4e) | Mar 07, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [16c33be9a3](https://linux-hardware.org/?probe=16c33be9a3) | Mar 07, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [be24c7e178](https://linux-hardware.org/?probe=be24c7e178) | Mar 07, 2023 |
| Acer          | Aspire E5-575G              | [fd8c378fda](https://linux-hardware.org/?probe=fd8c378fda) | Mar 07, 2023 |
| ASUSTek       | X556UAK                     | [51f2084195](https://linux-hardware.org/?probe=51f2084195) | Mar 06, 2023 |
| Lenovo        | IdeaPad S540-14IWL 81ND     | [745898b5de](https://linux-hardware.org/?probe=745898b5de) | Mar 06, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [8a70478523](https://linux-hardware.org/?probe=8a70478523) | Mar 06, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [6e08a2dcf9](https://linux-hardware.org/?probe=6e08a2dcf9) | Mar 06, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [20fbc926fd](https://linux-hardware.org/?probe=20fbc926fd) | Mar 06, 2023 |
| Lenovo        | G50-45 80E3                 | [02dfdb807e](https://linux-hardware.org/?probe=02dfdb807e) | Mar 06, 2023 |
| HP            | G72                         | [64009d0874](https://linux-hardware.org/?probe=64009d0874) | Mar 06, 2023 |
| HP            | ProBook 430 G5              | [aaebada0ca](https://linux-hardware.org/?probe=aaebada0ca) | Mar 06, 2023 |
| YJKC          | vBOOK Plus RVP7             | [acdf0dca1d](https://linux-hardware.org/?probe=acdf0dca1d) | Mar 06, 2023 |
| Microtech     | ebookPro                    | [cac30f03b1](https://linux-hardware.org/?probe=cac30f03b1) | Mar 06, 2023 |
| Dell          | Inspiron 17-7779            | [24b5bddf1d](https://linux-hardware.org/?probe=24b5bddf1d) | Mar 05, 2023 |
| SANTECH       | NHx0DB,DE                   | [9ebc94ec48](https://linux-hardware.org/?probe=9ebc94ec48) | Mar 04, 2023 |
| Apple         | MacBookPro10,1              | [7b7aa513b8](https://linux-hardware.org/?probe=7b7aa513b8) | Mar 04, 2023 |
| Toshiba       | NB550D                      | [8ba5171640](https://linux-hardware.org/?probe=8ba5171640) | Mar 04, 2023 |
| HP            | G72                         | [a094ef43f1](https://linux-hardware.org/?probe=a094ef43f1) | Mar 04, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [4816618219](https://linux-hardware.org/?probe=4816618219) | Mar 04, 2023 |
| Dell          | Inspiron 16 7610            | [1121d93a65](https://linux-hardware.org/?probe=1121d93a65) | Mar 04, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [71f2f93645](https://linux-hardware.org/?probe=71f2f93645) | Mar 04, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [13fc723c9e](https://linux-hardware.org/?probe=13fc723c9e) | Mar 04, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | [1a0011a745](https://linux-hardware.org/?probe=1a0011a745) | Mar 03, 2023 |
| HP            | 255 G8 Notebook PC          | [7dc484b236](https://linux-hardware.org/?probe=7dc484b236) | Mar 03, 2023 |
| HP            | 255 G8 Notebook PC          | [b7e4822b00](https://linux-hardware.org/?probe=b7e4822b00) | Mar 03, 2023 |
| HUAWEI        | CREF-XX                     | [bef62e57b0](https://linux-hardware.org/?probe=bef62e57b0) | Mar 03, 2023 |
| HUAWEI        | CREF-XX                     | [b42f1c3f6b](https://linux-hardware.org/?probe=b42f1c3f6b) | Mar 03, 2023 |
| HP            | ENVY 15                     | [9ceefd9a22](https://linux-hardware.org/?probe=9ceefd9a22) | Mar 03, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [17f1328add](https://linux-hardware.org/?probe=17f1328add) | Mar 03, 2023 |
| HP            | ENVY dv6                    | [357b5b3506](https://linux-hardware.org/?probe=357b5b3506) | Mar 03, 2023 |
| Apple         | MacBookAir6,2               | [f791caa732](https://linux-hardware.org/?probe=f791caa732) | Mar 03, 2023 |
| Acer          | Aspire 5732Z                | [bff68efdba](https://linux-hardware.org/?probe=bff68efdba) | Mar 03, 2023 |
| HP            | EliteBook 830 G5            | [cd6c75d08e](https://linux-hardware.org/?probe=cd6c75d08e) | Mar 03, 2023 |
| Toshiba       | Satellite L50-B             | [8abe852ff0](https://linux-hardware.org/?probe=8abe852ff0) | Mar 03, 2023 |
| Apple         | MacBookAir6,2               | [0b39498d52](https://linux-hardware.org/?probe=0b39498d52) | Mar 03, 2023 |
| GMK           | NucBox2                     | [84af5a7d53](https://linux-hardware.org/?probe=84af5a7d53) | Mar 02, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [c34c6d8786](https://linux-hardware.org/?probe=c34c6d8786) | Mar 02, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [2a1515aaa3](https://linux-hardware.org/?probe=2a1515aaa3) | Mar 02, 2023 |
| Acer          | TravelMate P253             | [aa56b7749c](https://linux-hardware.org/?probe=aa56b7749c) | Mar 02, 2023 |
| MSI           | Creator 15M A9SD            | [b19d8d936c](https://linux-hardware.org/?probe=b19d8d936c) | Mar 02, 2023 |
| Acer          | Aspire 5755G                | [c1594b1f9d](https://linux-hardware.org/?probe=c1594b1f9d) | Mar 02, 2023 |
| PC Special... | 14 Fusion IV                | [e465178d82](https://linux-hardware.org/?probe=e465178d82) | Mar 02, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [98e86d41d1](https://linux-hardware.org/?probe=98e86d41d1) | Mar 01, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [61fe88e268](https://linux-hardware.org/?probe=61fe88e268) | Mar 01, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [6a99428156](https://linux-hardware.org/?probe=6a99428156) | Mar 01, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [52ecc1a9fb](https://linux-hardware.org/?probe=52ecc1a9fb) | Mar 01, 2023 |
| HP            | Pavilion 15                 | [78f570552a](https://linux-hardware.org/?probe=78f570552a) | Mar 01, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [456504fe92](https://linux-hardware.org/?probe=456504fe92) | Feb 28, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [1165717061](https://linux-hardware.org/?probe=1165717061) | Feb 28, 2023 |
| HP            | ENVY Laptop 17-ch1xxx       | [b518eb9925](https://linux-hardware.org/?probe=b518eb9925) | Feb 28, 2023 |
| HUAWEI        | MRC-WX0                     | [e2776f99bf](https://linux-hardware.org/?probe=e2776f99bf) | Feb 28, 2023 |
| Acer          | Aspire 5750G                | [34b5806bcf](https://linux-hardware.org/?probe=34b5806bcf) | Feb 28, 2023 |
| Dell          | Latitude 5530               | [f892221e4c](https://linux-hardware.org/?probe=f892221e4c) | Feb 27, 2023 |
| Acer          | Aspire E1-531               | [a52b94c2d5](https://linux-hardware.org/?probe=a52b94c2d5) | Feb 27, 2023 |
| Getac         | V200-X                      | [f3a5da3eae](https://linux-hardware.org/?probe=f3a5da3eae) | Feb 27, 2023 |
| Acer          | TravelMate B113             | [31691f9681](https://linux-hardware.org/?probe=31691f9681) | Feb 27, 2023 |
| Razer         | Blade 15 Base Model (Ear... | [425567e8f3](https://linux-hardware.org/?probe=425567e8f3) | Feb 27, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [2cea6ee649](https://linux-hardware.org/?probe=2cea6ee649) | Feb 26, 2023 |
| ASUSTek       | X540NA                      | [8bca0d4eb5](https://linux-hardware.org/?probe=8bca0d4eb5) | Feb 26, 2023 |
| Timi          | TM1612                      | [eb4a3f330e](https://linux-hardware.org/?probe=eb4a3f330e) | Feb 26, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [67b8b5ad09](https://linux-hardware.org/?probe=67b8b5ad09) | Feb 26, 2023 |
| Lenovo        | Y50-70 20378                | [005749f4ef](https://linux-hardware.org/?probe=005749f4ef) | Feb 26, 2023 |
| ASUSTek       | T100HAN                     | [bde9736ffd](https://linux-hardware.org/?probe=bde9736ffd) | Feb 26, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [84750f9d96](https://linux-hardware.org/?probe=84750f9d96) | Feb 25, 2023 |
| Acer          | Aspire A515-51G             | [432235c684](https://linux-hardware.org/?probe=432235c684) | Feb 25, 2023 |
| Acer          | Aspire ES1-521              | [e5f0a23afd](https://linux-hardware.org/?probe=e5f0a23afd) | Feb 25, 2023 |
| ASUSTek       | X551CA                      | [c8ead0e580](https://linux-hardware.org/?probe=c8ead0e580) | Feb 25, 2023 |
| HP            | 250 G3                      | [6a3d2238ba](https://linux-hardware.org/?probe=6a3d2238ba) | Feb 25, 2023 |
| ASUSTek       | T100HAN                     | [fd75fdb59f](https://linux-hardware.org/?probe=fd75fdb59f) | Feb 25, 2023 |
| ASUSTek       | X556URK                     | [fc80e01794](https://linux-hardware.org/?probe=fc80e01794) | Feb 25, 2023 |
| HP            | EliteBook 820 G3            | [75a0fcca48](https://linux-hardware.org/?probe=75a0fcca48) | Feb 25, 2023 |
| BESSTAR Te... | X400                        | [e1c05e0782](https://linux-hardware.org/?probe=e1c05e0782) | Feb 25, 2023 |
| HP            | ENVY 17                     | [08db7a8be2](https://linux-hardware.org/?probe=08db7a8be2) | Feb 25, 2023 |
| HP            | ENVY 17                     | [0ad15a7e01](https://linux-hardware.org/?probe=0ad15a7e01) | Feb 25, 2023 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [e3578290d2](https://linux-hardware.org/?probe=e3578290d2) | Feb 25, 2023 |
| HONOR         | HYM-WXX                     | [c6f84d1224](https://linux-hardware.org/?probe=c6f84d1224) | Feb 24, 2023 |
| HP            | EliteBook 840 Aero G8 No... | [f24e6a55c4](https://linux-hardware.org/?probe=f24e6a55c4) | Feb 24, 2023 |
| Dell          | Latitude 5530               | [8ad26dd8a0](https://linux-hardware.org/?probe=8ad26dd8a0) | Feb 24, 2023 |
| Fujitsu       | LIFEBOOK U749               | [ba7cdc6018](https://linux-hardware.org/?probe=ba7cdc6018) | Feb 24, 2023 |
| ASUSTek       | X555LA                      | [502020fe52](https://linux-hardware.org/?probe=502020fe52) | Feb 24, 2023 |
| ASUSTek       | X551CA                      | [62b46afbb8](https://linux-hardware.org/?probe=62b46afbb8) | Feb 24, 2023 |
| ASUSTek       | X510UQR                     | [075081e4ad](https://linux-hardware.org/?probe=075081e4ad) | Feb 24, 2023 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | [ac2d78d240](https://linux-hardware.org/?probe=ac2d78d240) | Feb 24, 2023 |
| Acer          | Aspire E1-531               | [4526585d29](https://linux-hardware.org/?probe=4526585d29) | Feb 24, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | [a8fbcbec0e](https://linux-hardware.org/?probe=a8fbcbec0e) | Feb 23, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [cddc383ff9](https://linux-hardware.org/?probe=cddc383ff9) | Feb 23, 2023 |
| Acer          | Aspire SW3-013              | [771b90caaa](https://linux-hardware.org/?probe=771b90caaa) | Feb 23, 2023 |
| Dell          | Latitude 5530               | [dbbcb7502c](https://linux-hardware.org/?probe=dbbcb7502c) | Feb 23, 2023 |
| Dell          | Latitude 5530               | [d620cdcce0](https://linux-hardware.org/?probe=d620cdcce0) | Feb 23, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [0f5352f94f](https://linux-hardware.org/?probe=0f5352f94f) | Feb 23, 2023 |
| HP            | Laptop 15s-eq2xxx           | [8a638dd3a7](https://linux-hardware.org/?probe=8a638dd3a7) | Feb 23, 2023 |
| Dell          | Latitude 7300               | [c4bb27e884](https://linux-hardware.org/?probe=c4bb27e884) | Feb 23, 2023 |
| Acer          | TravelMate P253             | [b99414b6de](https://linux-hardware.org/?probe=b99414b6de) | Feb 23, 2023 |
| HP            | Pavilion g6                 | [c76844f9a1](https://linux-hardware.org/?probe=c76844f9a1) | Feb 22, 2023 |
| HP            | ProBook 445 G8 Notebook ... | [7d3442e2a7](https://linux-hardware.org/?probe=7d3442e2a7) | Feb 22, 2023 |
| ASUSTek       | X555DG                      | [5e7abe271f](https://linux-hardware.org/?probe=5e7abe271f) | Feb 22, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [99d4f0df73](https://linux-hardware.org/?probe=99d4f0df73) | Feb 22, 2023 |
| ASUSTek       | X555LA                      | [e62c134a68](https://linux-hardware.org/?probe=e62c134a68) | Feb 22, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [71928c5a75](https://linux-hardware.org/?probe=71928c5a75) | Feb 22, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [57e007d035](https://linux-hardware.org/?probe=57e007d035) | Feb 22, 2023 |
| HP            | ENVY 17                     | [f705060f1e](https://linux-hardware.org/?probe=f705060f1e) | Feb 22, 2023 |
| HP            | ENVY 17                     | [bf86e7904b](https://linux-hardware.org/?probe=bf86e7904b) | Feb 22, 2023 |
| HUAWEI        | BOD-WXX9                    | [05f20bac2d](https://linux-hardware.org/?probe=05f20bac2d) | Feb 21, 2023 |
| HP            | Pavilion dv6                | [526430f218](https://linux-hardware.org/?probe=526430f218) | Feb 21, 2023 |
| Acer          | Aspire SW3-013              | [f0111df214](https://linux-hardware.org/?probe=f0111df214) | Feb 21, 2023 |
| BESSTAR Te... | X400                        | [f7f9004058](https://linux-hardware.org/?probe=f7f9004058) | Feb 21, 2023 |
| Teclast       | F7                          | [3f5fdc3aa9](https://linux-hardware.org/?probe=3f5fdc3aa9) | Feb 21, 2023 |
| Unknown       | Unknown                     | [46d473b3e5](https://linux-hardware.org/?probe=46d473b3e5) | Feb 21, 2023 |
| Lenovo        | ThinkPad S430 336457G       | [3a525ce932](https://linux-hardware.org/?probe=3a525ce932) | Feb 21, 2023 |
| Lenovo        | ThinkPad S430 336457G       | [f845d181ec](https://linux-hardware.org/?probe=f845d181ec) | Feb 20, 2023 |
| ASUSTek       | X555LPB                     | [29eb95639c](https://linux-hardware.org/?probe=29eb95639c) | Feb 20, 2023 |
| Lenovo        | ThinkPad E590 20NB001AMX    | [ec529ac1bd](https://linux-hardware.org/?probe=ec529ac1bd) | Feb 20, 2023 |
| Acer          | Aspire V5-573G              | [376b35f5b6](https://linux-hardware.org/?probe=376b35f5b6) | Feb 20, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | [6f9ef751cd](https://linux-hardware.org/?probe=6f9ef751cd) | Feb 20, 2023 |
| Lenovo        | ThinkPad T470s 20HGS0BY0... | [56c81f1044](https://linux-hardware.org/?probe=56c81f1044) | Feb 20, 2023 |
| HP            | EliteBook 8570w             | [a6fd2ffc5b](https://linux-hardware.org/?probe=a6fd2ffc5b) | Feb 20, 2023 |
| HP            | ProBook 650 G1              | [4e6687829e](https://linux-hardware.org/?probe=4e6687829e) | Feb 19, 2023 |
| ASUSTek       | X555LA                      | [51d702d217](https://linux-hardware.org/?probe=51d702d217) | Feb 19, 2023 |
| Dell          | XPS 15 7590                 | [297b06716d](https://linux-hardware.org/?probe=297b06716d) | Feb 19, 2023 |
| Dell          | Inspiron 7520               | [1489b9779a](https://linux-hardware.org/?probe=1489b9779a) | Feb 19, 2023 |
| ASUSTek       | S551LN                      | [ff5df2cf03](https://linux-hardware.org/?probe=ff5df2cf03) | Feb 19, 2023 |
| ASUSTek       | S551LN                      | [84e519800c](https://linux-hardware.org/?probe=84e519800c) | Feb 19, 2023 |
| ASUSTek       | X555LA                      | [2ffc7c4a96](https://linux-hardware.org/?probe=2ffc7c4a96) | Feb 19, 2023 |
| Packard Be... | EasyNote TJ65               | [2c98b99901](https://linux-hardware.org/?probe=2c98b99901) | Feb 19, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [1104c148d1](https://linux-hardware.org/?probe=1104c148d1) | Feb 19, 2023 |
| Dell          | Latitude 5480               | [e288a18f9d](https://linux-hardware.org/?probe=e288a18f9d) | Feb 18, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | [eb9f3822a0](https://linux-hardware.org/?probe=eb9f3822a0) | Feb 18, 2023 |
| HP            | 255 G8 Notebook PC          | [ecf73f400b](https://linux-hardware.org/?probe=ecf73f400b) | Feb 18, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [eb64c99981](https://linux-hardware.org/?probe=eb64c99981) | Feb 18, 2023 |
| HP            | OMEN by Laptop 15-dh0xxx    | [cadd20aaff](https://linux-hardware.org/?probe=cadd20aaff) | Feb 18, 2023 |
| Samsung       | RF511/RF411/RF711           | [355838f8b2](https://linux-hardware.org/?probe=355838f8b2) | Feb 18, 2023 |
| MSI           | Summit E13FlipEvo A11MT     | [df01e5357c](https://linux-hardware.org/?probe=df01e5357c) | Feb 18, 2023 |
| HP            | 240 G6 Notebook PC          | [fc39dde214](https://linux-hardware.org/?probe=fc39dde214) | Feb 18, 2023 |
| Acer          | Aspire A515-45              | [01a17523fa](https://linux-hardware.org/?probe=01a17523fa) | Feb 18, 2023 |
| Acer          | Aspire A515-45              | [6b59c75dec](https://linux-hardware.org/?probe=6b59c75dec) | Feb 18, 2023 |
| Jumper        | EZbook                      | [35f7c6a28a](https://linux-hardware.org/?probe=35f7c6a28a) | Feb 18, 2023 |
| HP            | ENVY 15                     | [bcdc62a706](https://linux-hardware.org/?probe=bcdc62a706) | Feb 18, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [7360e6e667](https://linux-hardware.org/?probe=7360e6e667) | Feb 17, 2023 |
| Dell          | Latitude E6440              | [96e9e43a2e](https://linux-hardware.org/?probe=96e9e43a2e) | Feb 17, 2023 |
| Getac         | V200-X                      | [754a4bd022](https://linux-hardware.org/?probe=754a4bd022) | Feb 17, 2023 |
| Getac         | V200-X                      | [6794c7246f](https://linux-hardware.org/?probe=6794c7246f) | Feb 17, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [e4483255db](https://linux-hardware.org/?probe=e4483255db) | Feb 17, 2023 |
| MSI           | Summit E13FlipEvo A11MT     | [b29933336d](https://linux-hardware.org/?probe=b29933336d) | Feb 17, 2023 |
| MSI           | Summit E13FlipEvo A11MT     | [d97ee3d7d1](https://linux-hardware.org/?probe=d97ee3d7d1) | Feb 17, 2023 |
| Acer          | Aspire E5-571G              | [7a47fab9f3](https://linux-hardware.org/?probe=7a47fab9f3) | Feb 17, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [e84edd71e7](https://linux-hardware.org/?probe=e84edd71e7) | Feb 17, 2023 |
| HP            | Pavilion 15                 | [a48098f6fc](https://linux-hardware.org/?probe=a48098f6fc) | Feb 17, 2023 |
| HP            | EliteBook 840 G3            | [f8b182d99b](https://linux-hardware.org/?probe=f8b182d99b) | Feb 17, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [85fd62f731](https://linux-hardware.org/?probe=85fd62f731) | Feb 17, 2023 |
| Jumper        | EZbook                      | [82ba62c4b0](https://linux-hardware.org/?probe=82ba62c4b0) | Feb 16, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [7d6dcd9cd1](https://linux-hardware.org/?probe=7d6dcd9cd1) | Feb 16, 2023 |
| Lenovo        | ThinkPad T430 2349IF8       | [4b6268364f](https://linux-hardware.org/?probe=4b6268364f) | Feb 16, 2023 |
| Jumper        | EZbook                      | [1009011b57](https://linux-hardware.org/?probe=1009011b57) | Feb 16, 2023 |
| Acer          | Swift SF314-59              | [fcf01071e5](https://linux-hardware.org/?probe=fcf01071e5) | Feb 15, 2023 |
| HP            | Notebook                    | [21442c303e](https://linux-hardware.org/?probe=21442c303e) | Feb 15, 2023 |
| Lenovo        | ThinkPad SL 2746AHG         | [c141867fa3](https://linux-hardware.org/?probe=c141867fa3) | Feb 15, 2023 |
| Google        | Grunt                       | [89c633c2c1](https://linux-hardware.org/?probe=89c633c2c1) | Feb 15, 2023 |
| ASUSTek       | X553MA                      | [56ee76d678](https://linux-hardware.org/?probe=56ee76d678) | Feb 15, 2023 |
| ASUSTek       | X553MA                      | [1f8387dde4](https://linux-hardware.org/?probe=1f8387dde4) | Feb 15, 2023 |
| ASUSTek       | F6A                         | [3660446fe5](https://linux-hardware.org/?probe=3660446fe5) | Feb 15, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [28ac8fee12](https://linux-hardware.org/?probe=28ac8fee12) | Feb 14, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [dddbb2d135](https://linux-hardware.org/?probe=dddbb2d135) | Feb 14, 2023 |
| Acer          | Aspire 7250G                | [5f5cec8261](https://linux-hardware.org/?probe=5f5cec8261) | Feb 14, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [a3eb6fde29](https://linux-hardware.org/?probe=a3eb6fde29) | Feb 14, 2023 |
| HP            | ENVY 17                     | [d07a7a99de](https://linux-hardware.org/?probe=d07a7a99de) | Feb 14, 2023 |
| Dell          | XPS 9320                    | [10eb3017b5](https://linux-hardware.org/?probe=10eb3017b5) | Feb 13, 2023 |
| HP            | Laptop 15s-fq4xxx           | [9d1c8bca14](https://linux-hardware.org/?probe=9d1c8bca14) | Feb 13, 2023 |
| Acer          | Swift SF114-33              | [14cd72be0e](https://linux-hardware.org/?probe=14cd72be0e) | Feb 13, 2023 |
| MSI           | Prestige 14Evo A11M         | [abeebd4312](https://linux-hardware.org/?probe=abeebd4312) | Feb 13, 2023 |
| Unknown       | Unknown                     | [23a611650b](https://linux-hardware.org/?probe=23a611650b) | Feb 13, 2023 |
| MSI           | GF63 Thin 11UC              | [6eb24e6e38](https://linux-hardware.org/?probe=6eb24e6e38) | Feb 13, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [23eec2d2bc](https://linux-hardware.org/?probe=23eec2d2bc) | Feb 13, 2023 |
| HP            | ProBook 455 G8 Notebook ... | [3cccebc1ef](https://linux-hardware.org/?probe=3cccebc1ef) | Feb 12, 2023 |
| HP            | ENVY 15                     | [efc0c8427a](https://linux-hardware.org/?probe=efc0c8427a) | Feb 12, 2023 |
| Lenovo        | ThinkPad L460 20FVS25H01    | [37383d8798](https://linux-hardware.org/?probe=37383d8798) | Feb 12, 2023 |
| MSI           | GF63 Thin 11UC              | [f12982699d](https://linux-hardware.org/?probe=f12982699d) | Feb 12, 2023 |
| HP            | 255 G8 Notebook PC          | [3542104e07](https://linux-hardware.org/?probe=3542104e07) | Feb 12, 2023 |
| HUAWEI        | BOM-WXX9                    | [c798855263](https://linux-hardware.org/?probe=c798855263) | Feb 12, 2023 |
| HP            | Compaq 6720s                | [4b8e0e10e0](https://linux-hardware.org/?probe=4b8e0e10e0) | Feb 12, 2023 |
| HP            | Compaq 6720s                | [a23186bb63](https://linux-hardware.org/?probe=a23186bb63) | Feb 11, 2023 |
| Lenovo        | ThinkPad T440p 20AWS0XX0... | [404cac8b60](https://linux-hardware.org/?probe=404cac8b60) | Feb 11, 2023 |
| Dell          | Vostro 15 3510              | [8291db193a](https://linux-hardware.org/?probe=8291db193a) | Feb 11, 2023 |
| HP            | Notebook                    | [94c42af775](https://linux-hardware.org/?probe=94c42af775) | Feb 11, 2023 |
| HP            | ZBook 17 G3                 | [f0dff8ed53](https://linux-hardware.org/?probe=f0dff8ed53) | Feb 11, 2023 |
| HP            | Notebook                    | [e19e0407ec](https://linux-hardware.org/?probe=e19e0407ec) | Feb 11, 2023 |
| Dell          | XPS 15 9500                 | [11222774d3](https://linux-hardware.org/?probe=11222774d3) | Feb 10, 2023 |
| MSI           | Prestige 15 A11SCX          | [a82372e461](https://linux-hardware.org/?probe=a82372e461) | Feb 10, 2023 |
| HP            | Notebook                    | [4daf49165c](https://linux-hardware.org/?probe=4daf49165c) | Feb 10, 2023 |
| HP            | ZBook 17 G3                 | [bd09c6036f](https://linux-hardware.org/?probe=bd09c6036f) | Feb 10, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [fd8d478a5b](https://linux-hardware.org/?probe=fd8d478a5b) | Feb 10, 2023 |
| Lenovo        | Yoga Slim 7 13ITL5 82CU     | [7f4c6d1757](https://linux-hardware.org/?probe=7f4c6d1757) | Feb 10, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [9de542dff7](https://linux-hardware.org/?probe=9de542dff7) | Feb 09, 2023 |
| HP            | 255 G4                      | [00870a3da9](https://linux-hardware.org/?probe=00870a3da9) | Feb 09, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [08f3d3b7d8](https://linux-hardware.org/?probe=08f3d3b7d8) | Feb 09, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [0cb6963914](https://linux-hardware.org/?probe=0cb6963914) | Feb 09, 2023 |
| Acer          | Extensa 5635ZG              | [dd22b216a9](https://linux-hardware.org/?probe=dd22b216a9) | Feb 08, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [96d63ff41b](https://linux-hardware.org/?probe=96d63ff41b) | Feb 08, 2023 |
| Acer          | Aspire A515-52G             | [e521c55b1a](https://linux-hardware.org/?probe=e521c55b1a) | Feb 08, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [5ce86509b6](https://linux-hardware.org/?probe=5ce86509b6) | Feb 08, 2023 |
| Dell          | XPS 17 9720                 | [3d1b70c4af](https://linux-hardware.org/?probe=3d1b70c4af) | Feb 08, 2023 |
| Google        | Grunt                       | [84ecb8aaf1](https://linux-hardware.org/?probe=84ecb8aaf1) | Feb 08, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [3089398556](https://linux-hardware.org/?probe=3089398556) | Feb 08, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [07d8f7c1da](https://linux-hardware.org/?probe=07d8f7c1da) | Feb 08, 2023 |
| HP            | ENVY 15                     | [641ce1347d](https://linux-hardware.org/?probe=641ce1347d) | Feb 08, 2023 |
| Acer          | Aspire E5-553               | [5e951ad06d](https://linux-hardware.org/?probe=5e951ad06d) | Feb 07, 2023 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | [0713732442](https://linux-hardware.org/?probe=0713732442) | Feb 07, 2023 |
| Google        | Grunt                       | [1bbc4ae776](https://linux-hardware.org/?probe=1bbc4ae776) | Feb 07, 2023 |
| Lenovo        | ThinkPad T430 2347G7G       | [925017105d](https://linux-hardware.org/?probe=925017105d) | Feb 07, 2023 |
| HUAWEI        | MACH-WX9                    | [263101d492](https://linux-hardware.org/?probe=263101d492) | Feb 07, 2023 |
| HP            | ENVY Laptop 17-cr0xxx       | [b7ab00ddb1](https://linux-hardware.org/?probe=b7ab00ddb1) | Feb 07, 2023 |
| MSI           | U90/U100                    | [f7dc915782](https://linux-hardware.org/?probe=f7dc915782) | Feb 06, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [50af8c9fe6](https://linux-hardware.org/?probe=50af8c9fe6) | Feb 06, 2023 |
| ASUSTek       | X550JF                      | [c8f1b71cfd](https://linux-hardware.org/?probe=c8f1b71cfd) | Feb 06, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [0edeee4ba6](https://linux-hardware.org/?probe=0edeee4ba6) | Feb 06, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [66201d26d7](https://linux-hardware.org/?probe=66201d26d7) | Feb 06, 2023 |
| Acer          | Extensa 5635                | [8f8f4d24f9](https://linux-hardware.org/?probe=8f8f4d24f9) | Feb 06, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [762c097b3e](https://linux-hardware.org/?probe=762c097b3e) | Feb 06, 2023 |
| Intel         | Unknown                     | [a1044e362f](https://linux-hardware.org/?probe=a1044e362f) | Feb 06, 2023 |
| Lenovo        | Flex 2-14D 20376            | [16f0d33c85](https://linux-hardware.org/?probe=16f0d33c85) | Feb 06, 2023 |
| Lenovo        | ThinkPad T470 20HES3X300    | [6a77ec4c4f](https://linux-hardware.org/?probe=6a77ec4c4f) | Feb 06, 2023 |
| Valve         | Jupiter                     | [8a1998f130](https://linux-hardware.org/?probe=8a1998f130) | Feb 05, 2023 |
| Dell          | Latitude 7380               | [7b9d4ef8b4](https://linux-hardware.org/?probe=7b9d4ef8b4) | Feb 05, 2023 |
| ASUSTek       | N55SF                       | [5b81cbed5f](https://linux-hardware.org/?probe=5b81cbed5f) | Feb 05, 2023 |
| Acer          | One S1002                   | [2d98ceddca](https://linux-hardware.org/?probe=2d98ceddca) | Feb 05, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [30676c5e14](https://linux-hardware.org/?probe=30676c5e14) | Feb 05, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [08bf9ddbcf](https://linux-hardware.org/?probe=08bf9ddbcf) | Feb 05, 2023 |
| ASUSTek       | K52Jc                       | [464b35f82b](https://linux-hardware.org/?probe=464b35f82b) | Feb 05, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | [2ac999e9b0](https://linux-hardware.org/?probe=2ac999e9b0) | Feb 05, 2023 |
| HP            | 255 G3                      | [dfa2e96880](https://linux-hardware.org/?probe=dfa2e96880) | Feb 05, 2023 |
| Acer          | Aspire E5-573G              | [b7760210a8](https://linux-hardware.org/?probe=b7760210a8) | Feb 05, 2023 |
| Notebook      | W25CSW                      | [b63184cd07](https://linux-hardware.org/?probe=b63184cd07) | Feb 05, 2023 |
| Notebook      | W65_67SJ                    | [870af12011](https://linux-hardware.org/?probe=870af12011) | Feb 05, 2023 |
| Lenovo        | G50-45 80E3                 | [229050fbe5](https://linux-hardware.org/?probe=229050fbe5) | Feb 05, 2023 |
| Acer          | TravelMate P253             | [b2cad8970a](https://linux-hardware.org/?probe=b2cad8970a) | Feb 04, 2023 |
| Lenovo        | G50-45 80E3                 | [885ad2ae95](https://linux-hardware.org/?probe=885ad2ae95) | Feb 04, 2023 |
| SiComputer    | Nauta 01C                   | [1579a837f7](https://linux-hardware.org/?probe=1579a837f7) | Feb 04, 2023 |
| Microtech     | CoreBook                    | [2ee0649a6e](https://linux-hardware.org/?probe=2ee0649a6e) | Feb 03, 2023 |
| Toshiba       | Satellite Pro S500          | [9274080d89](https://linux-hardware.org/?probe=9274080d89) | Feb 03, 2023 |
| HP            | ProBook 440 G7              | [f9a4f80656](https://linux-hardware.org/?probe=f9a4f80656) | Feb 03, 2023 |
| Intel         | Unknown                     | [ba5bda9424](https://linux-hardware.org/?probe=ba5bda9424) | Feb 02, 2023 |
| Acer          | Aspire F5-573G              | [ba43497e32](https://linux-hardware.org/?probe=ba43497e32) | Feb 02, 2023 |
| HP            | 250 G6 Notebook PC          | [a0b5d1c73c](https://linux-hardware.org/?probe=a0b5d1c73c) | Feb 02, 2023 |
| ASUSTek       | K54L                        | [8568b17267](https://linux-hardware.org/?probe=8568b17267) | Feb 02, 2023 |
| Dell          | XPS 13 7390                 | [f86eaa6db8](https://linux-hardware.org/?probe=f86eaa6db8) | Feb 02, 2023 |
| Timi          | Mi Laptop Pro 15            | [9deaff7467](https://linux-hardware.org/?probe=9deaff7467) | Feb 02, 2023 |
| Toshiba       | Satellite Pro S500          | [19a2c05804](https://linux-hardware.org/?probe=19a2c05804) | Feb 02, 2023 |
| HP            | Pavilion 15                 | [946fec8f7d](https://linux-hardware.org/?probe=946fec8f7d) | Feb 01, 2023 |
| Acer          | Aspire 5750G                | [a8a3f37ad8](https://linux-hardware.org/?probe=a8a3f37ad8) | Feb 01, 2023 |
| HP            | Laptop 15s-fq5xxx           | [bd22f26ad1](https://linux-hardware.org/?probe=bd22f26ad1) | Jan 31, 2023 |
| HP            | Laptop 15s-fq5xxx           | [28ea3cafe8](https://linux-hardware.org/?probe=28ea3cafe8) | Jan 31, 2023 |
| HP            | ENVY 15                     | [c688eb85bb](https://linux-hardware.org/?probe=c688eb85bb) | Jan 31, 2023 |
| HP            | Notebook                    | [f352309997](https://linux-hardware.org/?probe=f352309997) | Jan 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [78bd5ea99c](https://linux-hardware.org/?probe=78bd5ea99c) | Jan 31, 2023 |
| Acer          | Swift SF114-32              | [8e8ae85d60](https://linux-hardware.org/?probe=8e8ae85d60) | Jan 31, 2023 |
| Dell          | XPS 15 9570                 | [ee60c1c921](https://linux-hardware.org/?probe=ee60c1c921) | Jan 31, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [5e5231a159](https://linux-hardware.org/?probe=5e5231a159) | Jan 31, 2023 |
| Acer          | Aspire ES1-512              | [0d254e85dd](https://linux-hardware.org/?probe=0d254e85dd) | Jan 30, 2023 |
| Acer          | Aspire E1-522               | [88de348bef](https://linux-hardware.org/?probe=88de348bef) | Jan 30, 2023 |
| Dell          | Precision 3560              | [3d5432deef](https://linux-hardware.org/?probe=3d5432deef) | Jan 30, 2023 |
| Dell          | Precision 3560              | [c250c935bd](https://linux-hardware.org/?probe=c250c935bd) | Jan 30, 2023 |
| Dell          | Precision 3571              | [55f371f4ef](https://linux-hardware.org/?probe=55f371f4ef) | Jan 30, 2023 |
| Acer          | Aspire 5552                 | [f1168775a7](https://linux-hardware.org/?probe=f1168775a7) | Jan 30, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [519a211655](https://linux-hardware.org/?probe=519a211655) | Jan 30, 2023 |
| HP            | Laptop 15s-eq1xxx           | [9f093d7cff](https://linux-hardware.org/?probe=9f093d7cff) | Jan 30, 2023 |
| Acer          | Aspire E5-553               | [8200b57a5b](https://linux-hardware.org/?probe=8200b57a5b) | Jan 29, 2023 |
| Acer          | Aspire E5-553               | [3ac195a476](https://linux-hardware.org/?probe=3ac195a476) | Jan 29, 2023 |
| Acer          | Aspire A315-41              | [f8ef554d85](https://linux-hardware.org/?probe=f8ef554d85) | Jan 29, 2023 |
| Lenovo        | ThinkPad X220 42915CG       | [d058eeaad5](https://linux-hardware.org/?probe=d058eeaad5) | Jan 29, 2023 |
| Apple         | MacBookPro7,1               | [615e9f22e4](https://linux-hardware.org/?probe=615e9f22e4) | Jan 29, 2023 |
| Valve         | Jupiter                     | [5ea763da5f](https://linux-hardware.org/?probe=5ea763da5f) | Jan 28, 2023 |
| Dell          | Inspiron 5570               | [17a8246044](https://linux-hardware.org/?probe=17a8246044) | Jan 28, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [edd571ba94](https://linux-hardware.org/?probe=edd571ba94) | Jan 28, 2023 |
| Acer          | Aspire A315-41              | [bbe5b30c42](https://linux-hardware.org/?probe=bbe5b30c42) | Jan 28, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [844e4e4b2a](https://linux-hardware.org/?probe=844e4e4b2a) | Jan 28, 2023 |
| Acer          | Swift SF314-511             | [eeaf26e835](https://linux-hardware.org/?probe=eeaf26e835) | Jan 28, 2023 |
| Sony          | SVE1711C5E                  | [73977968f5](https://linux-hardware.org/?probe=73977968f5) | Jan 27, 2023 |
| Sony          | SVE1711C5E                  | [d526ae42aa](https://linux-hardware.org/?probe=d526ae42aa) | Jan 27, 2023 |
| HP            | 255 G8 Notebook PC          | [23a84c76b8](https://linux-hardware.org/?probe=23a84c76b8) | Jan 27, 2023 |
| Apple         | MacBook4,1                  | [e00443a9cc](https://linux-hardware.org/?probe=e00443a9cc) | Jan 27, 2023 |
| HUAWEI        | VLT-WX0                     | [270e8da18d](https://linux-hardware.org/?probe=270e8da18d) | Jan 27, 2023 |
| Lenovo        | ThinkPad E590 20NB001AMX    | [4bf7b18ab1](https://linux-hardware.org/?probe=4bf7b18ab1) | Jan 27, 2023 |
| HUAWEI        | KLVC-WXX9                   | [8fa82c8684](https://linux-hardware.org/?probe=8fa82c8684) | Jan 26, 2023 |
| Toshiba       | Satellite Pro C50-A-1FD     | [7f7198cdcb](https://linux-hardware.org/?probe=7f7198cdcb) | Jan 26, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | [8725d530e5](https://linux-hardware.org/?probe=8725d530e5) | Jan 26, 2023 |
| Dell          | XPS 17 9700                 | [759ae65214](https://linux-hardware.org/?probe=759ae65214) | Jan 26, 2023 |
| Chuwi         | GemiBook Pro                | [bea1d8a9ce](https://linux-hardware.org/?probe=bea1d8a9ce) | Jan 25, 2023 |
| HUAWEI        | KLVL-WXX9                   | [f04915614f](https://linux-hardware.org/?probe=f04915614f) | Jan 25, 2023 |
| Sony          | SVE1513C5E                  | [48ee443aef](https://linux-hardware.org/?probe=48ee443aef) | Jan 25, 2023 |
| ASUSTek       | N551JW                      | [9694a30eff](https://linux-hardware.org/?probe=9694a30eff) | Jan 25, 2023 |
| HP            | EliteBook 820 G2            | [7b93d7477b](https://linux-hardware.org/?probe=7b93d7477b) | Jan 25, 2023 |
| HP            | ProBook 6440b               | [25c4dbbe9c](https://linux-hardware.org/?probe=25c4dbbe9c) | Jan 24, 2023 |
| HP            | Laptop 15s-eq2xxx           | [cb29f724a0](https://linux-hardware.org/?probe=cb29f724a0) | Jan 24, 2023 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [cfd65f9e9e](https://linux-hardware.org/?probe=cfd65f9e9e) | Jan 24, 2023 |
| TUXEDO        | Aura 15 Gen1                | [51d8d1eb34](https://linux-hardware.org/?probe=51d8d1eb34) | Jan 24, 2023 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [5df97c3eb1](https://linux-hardware.org/?probe=5df97c3eb1) | Jan 24, 2023 |
| Toshiba       | Satellite Pro S500          | [d529b5d578](https://linux-hardware.org/?probe=d529b5d578) | Jan 24, 2023 |
| Dell          | XPS 9320                    | [e6a308392c](https://linux-hardware.org/?probe=e6a308392c) | Jan 23, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | [cbd812094c](https://linux-hardware.org/?probe=cbd812094c) | Jan 23, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [a05bb7e519](https://linux-hardware.org/?probe=a05bb7e519) | Jan 23, 2023 |
| Toshiba       | Satellite Pro S500          | [118cda5e06](https://linux-hardware.org/?probe=118cda5e06) | Jan 23, 2023 |
| ASUSTek       | G75VW                       | [917f63e659](https://linux-hardware.org/?probe=917f63e659) | Jan 23, 2023 |
| Fujitsu       | LIFEBOOK A544               | [972194ff6e](https://linux-hardware.org/?probe=972194ff6e) | Jan 23, 2023 |
| HUAWEI        | KLVL-WXX9                   | [5cd697d63d](https://linux-hardware.org/?probe=5cd697d63d) | Jan 23, 2023 |
| Fujitsu       | LIFEBOOK U9311A             | [6bdcfeae43](https://linux-hardware.org/?probe=6bdcfeae43) | Jan 23, 2023 |
| Sony          | SVE1513C5E                  | [bff960bae2](https://linux-hardware.org/?probe=bff960bae2) | Jan 23, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | [adcd91409c](https://linux-hardware.org/?probe=adcd91409c) | Jan 23, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | [e2fd85407d](https://linux-hardware.org/?probe=e2fd85407d) | Jan 23, 2023 |
| HP            | Laptop 15-dw0xxx            | [8460e3552a](https://linux-hardware.org/?probe=8460e3552a) | Jan 22, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [8941c8857e](https://linux-hardware.org/?probe=8941c8857e) | Jan 22, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [89c37ebdfa](https://linux-hardware.org/?probe=89c37ebdfa) | Jan 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X435... | [b1ced07f7b](https://linux-hardware.org/?probe=b1ced07f7b) | Jan 22, 2023 |
| HP            | ProBook 450 G3              | [a3ce3d4a23](https://linux-hardware.org/?probe=a3ce3d4a23) | Jan 22, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | [09650cf189](https://linux-hardware.org/?probe=09650cf189) | Jan 22, 2023 |
| Dell          | Vostro 15 3515              | [51234f64dd](https://linux-hardware.org/?probe=51234f64dd) | Jan 21, 2023 |
| HP            | ProBook 4520s               | [ab9f74eb2c](https://linux-hardware.org/?probe=ab9f74eb2c) | Jan 21, 2023 |
| Acer          | Aspire F5-573G              | [68847eb1e6](https://linux-hardware.org/?probe=68847eb1e6) | Jan 21, 2023 |
| Toshiba       | Satellite Pro C850-10L      | [c1de4d0e2b](https://linux-hardware.org/?probe=c1de4d0e2b) | Jan 21, 2023 |
| Acer          | Aspire E5-575G              | [d020dd93e4](https://linux-hardware.org/?probe=d020dd93e4) | Jan 21, 2023 |
| MSI           | Prestige 15 A12SC           | [b368e80a36](https://linux-hardware.org/?probe=b368e80a36) | Jan 21, 2023 |
| Acer          | Aspire 7745G                | [98d6ab791c](https://linux-hardware.org/?probe=98d6ab791c) | Jan 21, 2023 |
| Acer          | Aspire A315-55G             | [b8660798ec](https://linux-hardware.org/?probe=b8660798ec) | Jan 20, 2023 |
| Toshiba       | Satellite Pro S500          | [f1e995c40b](https://linux-hardware.org/?probe=f1e995c40b) | Jan 20, 2023 |
| Toshiba       | Satellite Pro S500          | [16708a6471](https://linux-hardware.org/?probe=16708a6471) | Jan 20, 2023 |
| Acer          | Aspire E5-573G              | [c87740267f](https://linux-hardware.org/?probe=c87740267f) | Jan 20, 2023 |
| HP            | Pavilion dv7                | [0a4700fc75](https://linux-hardware.org/?probe=0a4700fc75) | Jan 20, 2023 |
| HUAWEI        | BOM-WXX9                    | [77ac7a6fc3](https://linux-hardware.org/?probe=77ac7a6fc3) | Jan 20, 2023 |
| Toshiba       | Satellite Pro S500          | [194f5676bd](https://linux-hardware.org/?probe=194f5676bd) | Jan 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [76ab21d17b](https://linux-hardware.org/?probe=76ab21d17b) | Jan 20, 2023 |
| Acer          | TravelMate 5735Z            | [712fdb1fa7](https://linux-hardware.org/?probe=712fdb1fa7) | Jan 20, 2023 |
| Acer          | TravelMate 5735Z            | [5b1b812b6e](https://linux-hardware.org/?probe=5b1b812b6e) | Jan 20, 2023 |
| Lenovo        | V15-IIL 82C5                | [8fc05186e7](https://linux-hardware.org/?probe=8fc05186e7) | Jan 20, 2023 |
| Dell          | XPS 13 9305                 | [5175eeeff4](https://linux-hardware.org/?probe=5175eeeff4) | Jan 20, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [c1169d55de](https://linux-hardware.org/?probe=c1169d55de) | Jan 19, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [2f712e8614](https://linux-hardware.org/?probe=2f712e8614) | Jan 19, 2023 |
| HP            | Laptop 15s-eq2xxx           | [bbc2c32eee](https://linux-hardware.org/?probe=bbc2c32eee) | Jan 19, 2023 |
| HP            | Pavilion x2 Detachable      | [8a13d31503](https://linux-hardware.org/?probe=8a13d31503) | Jan 19, 2023 |
| Apple         | MacBookPro11,1              | [67e4dd8f10](https://linux-hardware.org/?probe=67e4dd8f10) | Jan 19, 2023 |
| Insyde        | Braswell                    | [18526fdbe2](https://linux-hardware.org/?probe=18526fdbe2) | Jan 19, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [79ad95dada](https://linux-hardware.org/?probe=79ad95dada) | Jan 18, 2023 |
| HP            | Pavilion g6                 | [d1d3fadd60](https://linux-hardware.org/?probe=d1d3fadd60) | Jan 18, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [5a1bee99ee](https://linux-hardware.org/?probe=5a1bee99ee) | Jan 18, 2023 |
| ASUSTek       | TP301UJ                     | [4ee30e82ab](https://linux-hardware.org/?probe=4ee30e82ab) | Jan 18, 2023 |
| ASUSTek       | E200HA                      | [f17b69afa1](https://linux-hardware.org/?probe=f17b69afa1) | Jan 18, 2023 |
| ASUSTek       | X505BP                      | [ec4d653e2f](https://linux-hardware.org/?probe=ec4d653e2f) | Jan 17, 2023 |
| HP            | Laptop 15s-fq2xxx           | [133972f199](https://linux-hardware.org/?probe=133972f199) | Jan 17, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [44bf2e2ced](https://linux-hardware.org/?probe=44bf2e2ced) | Jan 17, 2023 |
| Acer          | Aspire E5-573G              | [9dba648ced](https://linux-hardware.org/?probe=9dba648ced) | Jan 17, 2023 |
| HUAWEI        | BOHB-WAX9                   | [b39c4fc9b7](https://linux-hardware.org/?probe=b39c4fc9b7) | Jan 16, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | [1c81e8c322](https://linux-hardware.org/?probe=1c81e8c322) | Jan 16, 2023 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | [5b56cf615b](https://linux-hardware.org/?probe=5b56cf615b) | Jan 16, 2023 |
| HP            | 15                          | [ae082994e2](https://linux-hardware.org/?probe=ae082994e2) | Jan 16, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [3891575263](https://linux-hardware.org/?probe=3891575263) | Jan 16, 2023 |
| Sony          | SVT1312M1ES                 | [9244e6ad96](https://linux-hardware.org/?probe=9244e6ad96) | Jan 16, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [b36eb94e80](https://linux-hardware.org/?probe=b36eb94e80) | Jan 16, 2023 |
| HP            | Pavilion Laptop 15-ck0xx    | [360173820c](https://linux-hardware.org/?probe=360173820c) | Jan 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [8fb168e741](https://linux-hardware.org/?probe=8fb168e741) | Jan 16, 2023 |
| Acer          | TravelMate P253             | [8f2246679e](https://linux-hardware.org/?probe=8f2246679e) | Jan 15, 2023 |
| HP            | Pavilion x2 Detachable      | [aa28cfacc3](https://linux-hardware.org/?probe=aa28cfacc3) | Jan 15, 2023 |
| HP            | Notebook                    | [be5a441ca6](https://linux-hardware.org/?probe=be5a441ca6) | Jan 15, 2023 |
| HP            | Pavilion x2 Detachable      | [5f9aaa4add](https://linux-hardware.org/?probe=5f9aaa4add) | Jan 15, 2023 |
| HP            | 15                          | [3faa6c9265](https://linux-hardware.org/?probe=3faa6c9265) | Jan 15, 2023 |
| HP            | Pavilion dv7                | [b3cbaccd13](https://linux-hardware.org/?probe=b3cbaccd13) | Jan 15, 2023 |
| HP            | Pavilion dv7                | [08bbff061e](https://linux-hardware.org/?probe=08bbff061e) | Jan 15, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [57d99b139f](https://linux-hardware.org/?probe=57d99b139f) | Jan 15, 2023 |
| Apple         | MacBook5,1                  | [51581940b0](https://linux-hardware.org/?probe=51581940b0) | Jan 15, 2023 |
| Acer          | TravelMate P253             | [15c26878b5](https://linux-hardware.org/?probe=15c26878b5) | Jan 15, 2023 |
| Dell          | Vostro 15 3515              | [fdf3113afb](https://linux-hardware.org/?probe=fdf3113afb) | Jan 15, 2023 |
| Kiano         | SlimNote 14,2               | [7596dc87b3](https://linux-hardware.org/?probe=7596dc87b3) | Jan 14, 2023 |
| ASUSTek       | N501VW                      | [5f9c2eebd4](https://linux-hardware.org/?probe=5f9c2eebd4) | Jan 14, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | [e5c76bef74](https://linux-hardware.org/?probe=e5c76bef74) | Jan 14, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | [2a08ec8e9e](https://linux-hardware.org/?probe=2a08ec8e9e) | Jan 14, 2023 |
| Olivetti      | Olibook P55-431W850-8G50... | [fe5c9c2425](https://linux-hardware.org/?probe=fe5c9c2425) | Jan 14, 2023 |
| Olivetti      | Olibook P55-431W850-8G50... | [649546bc61](https://linux-hardware.org/?probe=649546bc61) | Jan 14, 2023 |
| HP            | Notebook                    | [4c9b4e3b67](https://linux-hardware.org/?probe=4c9b4e3b67) | Jan 14, 2023 |
| HP            | Stream Notebook PC 13       | [b31d60976b](https://linux-hardware.org/?probe=b31d60976b) | Jan 14, 2023 |
| Toshiba       | Satellite Pro C850-1HD      | [d9ecac6816](https://linux-hardware.org/?probe=d9ecac6816) | Jan 14, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [86fff559f5](https://linux-hardware.org/?probe=86fff559f5) | Jan 14, 2023 |
| MSI           | PS63 Modern 8RC             | [e55e0d9d0a](https://linux-hardware.org/?probe=e55e0d9d0a) | Jan 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [1b50127412](https://linux-hardware.org/?probe=1b50127412) | Jan 14, 2023 |
| HUAWEI        | KPL-W0X                     | [d1175d8dba](https://linux-hardware.org/?probe=d1175d8dba) | Jan 14, 2023 |
| HP            | 250 G4 Notebook PC          | [dda4a9ae38](https://linux-hardware.org/?probe=dda4a9ae38) | Jan 14, 2023 |
| ASUSTek       | X550LD                      | [60b21ee22f](https://linux-hardware.org/?probe=60b21ee22f) | Jan 14, 2023 |
| Acer          | Swift SF314-511             | [8a4bbb603e](https://linux-hardware.org/?probe=8a4bbb603e) | Jan 14, 2023 |
| Acer          | Aspire E1-572G              | [360a177e77](https://linux-hardware.org/?probe=360a177e77) | Jan 14, 2023 |
| Dell          | XPS 9320                    | [b8de11c93d](https://linux-hardware.org/?probe=b8de11c93d) | Jan 13, 2023 |
| Acer          | Swift SF314-511             | [baa87ed4e0](https://linux-hardware.org/?probe=baa87ed4e0) | Jan 13, 2023 |
| Acer          | Swift SF314-511             | [cb94045e18](https://linux-hardware.org/?probe=cb94045e18) | Jan 13, 2023 |
| HP            | Pavilion Laptop 15-cs2xx... | [e7bab74a13](https://linux-hardware.org/?probe=e7bab74a13) | Jan 13, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | [b3fed0d61d](https://linux-hardware.org/?probe=b3fed0d61d) | Jan 13, 2023 |
| Unknown       | Unknown                     | [d0391da5d8](https://linux-hardware.org/?probe=d0391da5d8) | Jan 13, 2023 |
| Dell          | Precision 3551              | [66d483ea58](https://linux-hardware.org/?probe=66d483ea58) | Jan 13, 2023 |
| Acer          | Swift SF514-52T             | [feb261f5f5](https://linux-hardware.org/?probe=feb261f5f5) | Jan 13, 2023 |
| ASUSTek       | G56JR                       | [3665659d26](https://linux-hardware.org/?probe=3665659d26) | Jan 13, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [033a92981f](https://linux-hardware.org/?probe=033a92981f) | Jan 13, 2023 |
| HP            | EliteBook 840 G6            | [0559975d13](https://linux-hardware.org/?probe=0559975d13) | Jan 13, 2023 |
| ASUSTek       | N501VW                      | [176a3488df](https://linux-hardware.org/?probe=176a3488df) | Jan 12, 2023 |
| Google        | Sasuke                      | [7241244512](https://linux-hardware.org/?probe=7241244512) | Jan 12, 2023 |
| Lenovo        | IdeaPad Slim 9 14ITL5 82... | [a8d6ad51af](https://linux-hardware.org/?probe=a8d6ad51af) | Jan 12, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [fb5857252b](https://linux-hardware.org/?probe=fb5857252b) | Jan 12, 2023 |
| Acer          | Aspire V5-561G              | [1551c2b90c](https://linux-hardware.org/?probe=1551c2b90c) | Jan 12, 2023 |
| HP            | Pavilion dv6                | [43e7923f04](https://linux-hardware.org/?probe=43e7923f04) | Jan 11, 2023 |
| ASUSTek       | E200HA                      | [828a42310a](https://linux-hardware.org/?probe=828a42310a) | Jan 11, 2023 |
| HP            | ProBook 430 G5              | [6403930d67](https://linux-hardware.org/?probe=6403930d67) | Jan 11, 2023 |
| Google        | Sasuke                      | [99ba2827e0](https://linux-hardware.org/?probe=99ba2827e0) | Jan 10, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [c82f19c656](https://linux-hardware.org/?probe=c82f19c656) | Jan 10, 2023 |
| Toshiba       | Satellite Pro S500          | [2549187c34](https://linux-hardware.org/?probe=2549187c34) | Jan 10, 2023 |
| ASUSTek       | N501VW                      | [07d13b3b0b](https://linux-hardware.org/?probe=07d13b3b0b) | Jan 10, 2023 |
| ASUSTek       | X555YI                      | [4968e51e0b](https://linux-hardware.org/?probe=4968e51e0b) | Jan 10, 2023 |
| MSI           | Modern 15 A11M              | [5b55647c95](https://linux-hardware.org/?probe=5b55647c95) | Jan 10, 2023 |
| HP            | 15                          | [f6b287dae1](https://linux-hardware.org/?probe=f6b287dae1) | Jan 10, 2023 |
| HP            | Pavilion dv6                | [8f65765701](https://linux-hardware.org/?probe=8f65765701) | Jan 09, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [d6cac381fd](https://linux-hardware.org/?probe=d6cac381fd) | Jan 09, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [9f1f002f51](https://linux-hardware.org/?probe=9f1f002f51) | Jan 09, 2023 |
| Dell          | Precision 7540              | [77b35e556c](https://linux-hardware.org/?probe=77b35e556c) | Jan 09, 2023 |
| ASUSTek       | K50IJ                       | [9d476dfade](https://linux-hardware.org/?probe=9d476dfade) | Jan 09, 2023 |
| HP            | Pavilion Power Laptop 15... | [4d7677f391](https://linux-hardware.org/?probe=4d7677f391) | Jan 09, 2023 |
| HP            | Pavilion dv7                | [d3177dc8b3](https://linux-hardware.org/?probe=d3177dc8b3) | Jan 09, 2023 |
| HP            | Pavilion dv7                | [77590fdff4](https://linux-hardware.org/?probe=77590fdff4) | Jan 09, 2023 |
| Dell          | XPS 9320                    | [a58b8a72b7](https://linux-hardware.org/?probe=a58b8a72b7) | Jan 09, 2023 |
| HP            | Notebook                    | [c4cc7fb9f6](https://linux-hardware.org/?probe=c4cc7fb9f6) | Jan 09, 2023 |
| Apple         | MacBookPro8,2               | [0a7899316d](https://linux-hardware.org/?probe=0a7899316d) | Jan 08, 2023 |
| Dell          | Latitude E6440              | [faeb2d5372](https://linux-hardware.org/?probe=faeb2d5372) | Jan 08, 2023 |
| Dell          | Latitude 3450               | [e4e8bee1cb](https://linux-hardware.org/?probe=e4e8bee1cb) | Jan 08, 2023 |
| Notebook      | PCX0DX                      | [7e17526b20](https://linux-hardware.org/?probe=7e17526b20) | Jan 08, 2023 |
| Notebook      | PCX0DX                      | [698649c9ae](https://linux-hardware.org/?probe=698649c9ae) | Jan 08, 2023 |
| HP            | Notebook                    | [1174de12fc](https://linux-hardware.org/?probe=1174de12fc) | Jan 08, 2023 |
| Toshiba       | Satellite Pro S500          | [da62202546](https://linux-hardware.org/?probe=da62202546) | Jan 08, 2023 |
| Notebook      | NL40_50CU                   | [953d771250](https://linux-hardware.org/?probe=953d771250) | Jan 08, 2023 |
| ASUSTek       | S500CA                      | [d742870a51](https://linux-hardware.org/?probe=d742870a51) | Jan 07, 2023 |
| Timi          | TM1701                      | [c011ef538e](https://linux-hardware.org/?probe=c011ef538e) | Jan 07, 2023 |
| HP            | Pavilion dv6                | [7e1ac76fc9](https://linux-hardware.org/?probe=7e1ac76fc9) | Jan 07, 2023 |
| HP            | Compaq CQ58                 | [fae1531801](https://linux-hardware.org/?probe=fae1531801) | Jan 07, 2023 |
| Dell          | Latitude E6230              | [7a7cd04af0](https://linux-hardware.org/?probe=7a7cd04af0) | Jan 07, 2023 |
| HP            | Stream Notebook PC 13       | [d39ec5e414](https://linux-hardware.org/?probe=d39ec5e414) | Jan 07, 2023 |
| HP            | 250 G3                      | [227b44bf7c](https://linux-hardware.org/?probe=227b44bf7c) | Jan 06, 2023 |
| Dell          | Latitude 7520               | [f4f253a52b](https://linux-hardware.org/?probe=f4f253a52b) | Jan 06, 2023 |
| Lenovo        | ThinkPad T430 2349KB4       | [4546ecbe85](https://linux-hardware.org/?probe=4546ecbe85) | Jan 06, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [2227400f4c](https://linux-hardware.org/?probe=2227400f4c) | Jan 05, 2023 |
| HP            | 350 G1                      | [09f234d211](https://linux-hardware.org/?probe=09f234d211) | Jan 05, 2023 |
| Valve         | Jupiter                     | [3ce1a1d086](https://linux-hardware.org/?probe=3ce1a1d086) | Jan 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [4900ec9966](https://linux-hardware.org/?probe=4900ec9966) | Jan 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [e4a7ff414a](https://linux-hardware.org/?probe=e4a7ff414a) | Jan 05, 2023 |
| Timi          | RedmiBook 16                | [dca6d06bf4](https://linux-hardware.org/?probe=dca6d06bf4) | Jan 05, 2023 |
| HUAWEI        | KPL-W0X                     | [591d1b0ea9](https://linux-hardware.org/?probe=591d1b0ea9) | Jan 04, 2023 |
| Dell          | XPS 9320                    | [8684c6d86b](https://linux-hardware.org/?probe=8684c6d86b) | Jan 04, 2023 |
| ASUSTek       | 1005P                       | [7ccbcf9b28](https://linux-hardware.org/?probe=7ccbcf9b28) | Jan 04, 2023 |
| HP            | 15                          | [d0aae7c4b7](https://linux-hardware.org/?probe=d0aae7c4b7) | Jan 04, 2023 |
| MSI           | Prestige 15 A11SCX          | [86850a5925](https://linux-hardware.org/?probe=86850a5925) | Jan 04, 2023 |
| Dell          | XPS 15 9550                 | [72f8edfe5b](https://linux-hardware.org/?probe=72f8edfe5b) | Jan 04, 2023 |
| Acer          | Aspire E5-573               | [bd9e90dca3](https://linux-hardware.org/?probe=bd9e90dca3) | Jan 04, 2023 |
| Notebook      | NP5x_NP6x_NP7xPNK_PNH_PN... | [ace1cd7d4d](https://linux-hardware.org/?probe=ace1cd7d4d) | Jan 04, 2023 |
| Unknown       | Unknown                     | [b363093f89](https://linux-hardware.org/?probe=b363093f89) | Jan 04, 2023 |
| HP            | ProBook 650 G1              | [9aadf12194](https://linux-hardware.org/?probe=9aadf12194) | Jan 04, 2023 |
| Lenovo        | ThinkPad W541 20EFCTO1WW    | [a10abfb25a](https://linux-hardware.org/?probe=a10abfb25a) | Jan 03, 2023 |
| Lenovo        | ThinkPad W541 20EGS24J00    | [fa19ac7348](https://linux-hardware.org/?probe=fa19ac7348) | Jan 03, 2023 |
| HP            | 255 G8 Notebook PC          | [b876c5797a](https://linux-hardware.org/?probe=b876c5797a) | Jan 03, 2023 |
| HP            | 350 G1                      | [0929eec44b](https://linux-hardware.org/?probe=0929eec44b) | Jan 03, 2023 |
| HP            | 250 G8 Notebook PC          | [42e877ed10](https://linux-hardware.org/?probe=42e877ed10) | Jan 02, 2023 |
| Lenovo        | G510 20238                  | [90c0016c38](https://linux-hardware.org/?probe=90c0016c38) | Jan 02, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [287840d797](https://linux-hardware.org/?probe=287840d797) | Jan 02, 2023 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [0fb41a5066](https://linux-hardware.org/?probe=0fb41a5066) | Jan 02, 2023 |
| Dell          | Latitude 7410               | [acb8ce902e](https://linux-hardware.org/?probe=acb8ce902e) | Jan 01, 2023 |
| HP            | EliteBook 850 G3            | [64c803c589](https://linux-hardware.org/?probe=64c803c589) | Jan 01, 2023 |
| Acer          | TravelMate P253             | [a90b917fbe](https://linux-hardware.org/?probe=a90b917fbe) | Jan 01, 2023 |
| Acer          | TravelMate 5735Z            | [9fa5978af4](https://linux-hardware.org/?probe=9fa5978af4) | Jan 01, 2023 |
| Dell          | XPS 9320                    | [08626b8d57](https://linux-hardware.org/?probe=08626b8d57) | Jan 01, 2023 |
| Google        | Blooglet                    | [711ca24e79](https://linux-hardware.org/?probe=711ca24e79) | Jan 01, 2023 |
| HP            | Laptop 15s-fq5xxx           | [a8ce1c44a8](https://linux-hardware.org/?probe=a8ce1c44a8) | Jan 01, 2023 |
| Acer          | Aspire E5-573G              | [527a92f562](https://linux-hardware.org/?probe=527a92f562) | Dec 31, 2022 |
| HP            | Notebook                    | [d25df9daf4](https://linux-hardware.org/?probe=d25df9daf4) | Dec 31, 2022 |
| ASUSTek       | ProArt StudioBook H5600Q... | [07ca2ed63d](https://linux-hardware.org/?probe=07ca2ed63d) | Dec 31, 2022 |
| Dell          | XPS 9320                    | [c98fd80f29](https://linux-hardware.org/?probe=c98fd80f29) | Dec 31, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [60989ad0c4](https://linux-hardware.org/?probe=60989ad0c4) | Dec 31, 2022 |
| HP            | Compaq 6710b (KE207ES#AB... | [d7d0be3872](https://linux-hardware.org/?probe=d7d0be3872) | Dec 30, 2022 |
| Chuwi         | HeroBook                    | [1664994b07](https://linux-hardware.org/?probe=1664994b07) | Dec 30, 2022 |
| ASUSTek       | K55VD                       | [e4c90250df](https://linux-hardware.org/?probe=e4c90250df) | Dec 30, 2022 |
| MSI           | GP72MVR 7RFX                | [cefedef93c](https://linux-hardware.org/?probe=cefedef93c) | Dec 30, 2022 |
| Lenovo        | ThinkPad W541 20EF0011IX    | [a2f6a6831a](https://linux-hardware.org/?probe=a2f6a6831a) | Dec 30, 2022 |
| Lenovo        | ThinkPad W541 20EF0011IX    | [3f5a2c6ea1](https://linux-hardware.org/?probe=3f5a2c6ea1) | Dec 30, 2022 |
| ASUSTek       | X556UQK                     | [42a9dc760d](https://linux-hardware.org/?probe=42a9dc760d) | Dec 30, 2022 |
| Dell          | Inspiron 5593               | [bf0f36d69a](https://linux-hardware.org/?probe=bf0f36d69a) | Dec 30, 2022 |
| HP            | 255 G3                      | [89d6bd459c](https://linux-hardware.org/?probe=89d6bd459c) | Dec 30, 2022 |
| Dell          | Latitude E6410              | [0ee655e2cc](https://linux-hardware.org/?probe=0ee655e2cc) | Dec 29, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [2d653884d9](https://linux-hardware.org/?probe=2d653884d9) | Dec 29, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | [587aa5f819](https://linux-hardware.org/?probe=587aa5f819) | Dec 29, 2022 |
| Lenovo        | ThinkPad E580 20KS001RIX    | [4ca01731b4](https://linux-hardware.org/?probe=4ca01731b4) | Dec 29, 2022 |
| HP            | Compaq 6730s                | [9294bf57da](https://linux-hardware.org/?probe=9294bf57da) | Dec 28, 2022 |
| Lenovo        | ThinkPad E480 20KQS13M00    | [fb7e2874d3](https://linux-hardware.org/?probe=fb7e2874d3) | Dec 28, 2022 |
| Apple         | MacBookPro8,1               | [7b03f438db](https://linux-hardware.org/?probe=7b03f438db) | Dec 28, 2022 |
| Fujitsu       | LIFEBOOK A544               | [efdc6bb5cb](https://linux-hardware.org/?probe=efdc6bb5cb) | Dec 28, 2022 |
| Acer          | Aspire A315-55G             | [92155ba882](https://linux-hardware.org/?probe=92155ba882) | Dec 28, 2022 |
| HP            | ProBook 440 G6              | [6240bc3677](https://linux-hardware.org/?probe=6240bc3677) | Dec 28, 2022 |
| HP            | ProBook 440 G6              | [f5689c6edc](https://linux-hardware.org/?probe=f5689c6edc) | Dec 28, 2022 |
| HP            | EliteBook 850 G3            | [0dede5b37a](https://linux-hardware.org/?probe=0dede5b37a) | Dec 28, 2022 |
| System76      | Darter Pro                  | [a46000c111](https://linux-hardware.org/?probe=a46000c111) | Dec 28, 2022 |
| HP            | 250 G8 Notebook PC          | [7d79eadc7d](https://linux-hardware.org/?probe=7d79eadc7d) | Dec 28, 2022 |
| Teclast       | F15Plus 2                   | [71564a5900](https://linux-hardware.org/?probe=71564a5900) | Dec 27, 2022 |
| Teclast       | F15Plus 2                   | [4d10c4922e](https://linux-hardware.org/?probe=4d10c4922e) | Dec 27, 2022 |
| Packard Be... | EasyNote TJ65               | [57bfe7c99d](https://linux-hardware.org/?probe=57bfe7c99d) | Dec 27, 2022 |
| ASUSTek       | X550VXK                     | [301db79821](https://linux-hardware.org/?probe=301db79821) | Dec 27, 2022 |
| ASUSTek       | X550VXK                     | [039600625a](https://linux-hardware.org/?probe=039600625a) | Dec 27, 2022 |
| Dell          | XPS 9320                    | [7a2537eba2](https://linux-hardware.org/?probe=7a2537eba2) | Dec 27, 2022 |
| Dell          | Inspiron 15 3525            | [64a70af984](https://linux-hardware.org/?probe=64a70af984) | Dec 27, 2022 |
| System76      | Darter Pro                  | [c5aebaaece](https://linux-hardware.org/?probe=c5aebaaece) | Dec 27, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [d75dbe1e39](https://linux-hardware.org/?probe=d75dbe1e39) | Dec 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [1cf2ac2b8b](https://linux-hardware.org/?probe=1cf2ac2b8b) | Dec 27, 2022 |
| HP            | Pavilion 15                 | [9843ba5174](https://linux-hardware.org/?probe=9843ba5174) | Dec 26, 2022 |
| Notebook      | NP5x_NP6x_NP7xPNK_PNH_PN... | [792a203576](https://linux-hardware.org/?probe=792a203576) | Dec 26, 2022 |
| MSI           | GS76 Stealth 11UG           | [10e22b317f](https://linux-hardware.org/?probe=10e22b317f) | Dec 26, 2022 |
| Lenovo        | ThinkPad E590 20NB001AMX    | [047944fa9f](https://linux-hardware.org/?probe=047944fa9f) | Dec 26, 2022 |
| HP            | Laptop 15-da0xxx            | [96a4f739b8](https://linux-hardware.org/?probe=96a4f739b8) | Dec 26, 2022 |
| HP            | Laptop 15-da0xxx            | [19af161114](https://linux-hardware.org/?probe=19af161114) | Dec 26, 2022 |
| HP            | EliteBook 840 G4            | [1c5b59d2e4](https://linux-hardware.org/?probe=1c5b59d2e4) | Dec 26, 2022 |
| HP            | EliteBook 840 G4            | [730469b496](https://linux-hardware.org/?probe=730469b496) | Dec 26, 2022 |
| HP            | EliteBook 820 G1            | [6a2c20cb74](https://linux-hardware.org/?probe=6a2c20cb74) | Dec 26, 2022 |
| HP            | 255 G8 Notebook PC          | [2df8b7768a](https://linux-hardware.org/?probe=2df8b7768a) | Dec 26, 2022 |
| HP            | Compaq 6730s                | [ac1ae104e8](https://linux-hardware.org/?probe=ac1ae104e8) | Dec 26, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [38a87e716e](https://linux-hardware.org/?probe=38a87e716e) | Dec 26, 2022 |
| HP            | Compaq 6730s                | [0cc88159aa](https://linux-hardware.org/?probe=0cc88159aa) | Dec 26, 2022 |
| Lenovo        | ThinkPad X1 Carbon 34604... | [dfb555f802](https://linux-hardware.org/?probe=dfb555f802) | Dec 26, 2022 |
| Samsung       | RV420/RV520/RV720/E3530/... | [4665d79293](https://linux-hardware.org/?probe=4665d79293) | Dec 25, 2022 |
| SANTECH       | NHx0DB,DE                   | [a0996d42bd](https://linux-hardware.org/?probe=a0996d42bd) | Dec 25, 2022 |
| Toshiba       | Satellite Pro S500          | [cd547b04a1](https://linux-hardware.org/?probe=cd547b04a1) | Dec 25, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [ff90a6a029](https://linux-hardware.org/?probe=ff90a6a029) | Dec 25, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [faba7b00c6](https://linux-hardware.org/?probe=faba7b00c6) | Dec 25, 2022 |
| WYSE          | XM CLASS                    | [948bfb388d](https://linux-hardware.org/?probe=948bfb388d) | Dec 25, 2022 |
| HP            | EliteBook 8440p             | [571afe8b70](https://linux-hardware.org/?probe=571afe8b70) | Dec 24, 2022 |
| Dell          | XPS 9320                    | [f55956cac2](https://linux-hardware.org/?probe=f55956cac2) | Dec 24, 2022 |
| Dell          | Latitude 5590               | [f7011844b5](https://linux-hardware.org/?probe=f7011844b5) | Dec 24, 2022 |
| Dell          | Latitude 5590               | [3f1acac04f](https://linux-hardware.org/?probe=3f1acac04f) | Dec 24, 2022 |
| HP            | 255 G8 Notebook PC          | [3f72d88324](https://linux-hardware.org/?probe=3f72d88324) | Dec 24, 2022 |
| Dell          | Latitude 5590               | [e439eb94d4](https://linux-hardware.org/?probe=e439eb94d4) | Dec 24, 2022 |
| Dell          | Latitude 5590               | [816056e28e](https://linux-hardware.org/?probe=816056e28e) | Dec 24, 2022 |
| HUAWEI        | KPR-WX9                     | [e2b01c4a0f](https://linux-hardware.org/?probe=e2b01c4a0f) | Dec 23, 2022 |
| Dell          | Inspiron 15 5510            | [d53469cd41](https://linux-hardware.org/?probe=d53469cd41) | Dec 23, 2022 |
| Dell          | Inspiron 15 5510            | [9ddf91aa1b](https://linux-hardware.org/?probe=9ddf91aa1b) | Dec 23, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [f114731a78](https://linux-hardware.org/?probe=f114731a78) | Dec 23, 2022 |
| Acer          | Aspire A515-52G             | [586dd36eed](https://linux-hardware.org/?probe=586dd36eed) | Dec 23, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [214b2a3235](https://linux-hardware.org/?probe=214b2a3235) | Dec 23, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B3302CEA... | [756390ae0c](https://linux-hardware.org/?probe=756390ae0c) | Dec 23, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B3302CEA... | [c2dd56664a](https://linux-hardware.org/?probe=c2dd56664a) | Dec 23, 2022 |
| Timi          | TM1701                      | [2f28d7e2dc](https://linux-hardware.org/?probe=2f28d7e2dc) | Dec 23, 2022 |
| Timi          | TM1701                      | [dfb4f8774f](https://linux-hardware.org/?probe=dfb4f8774f) | Dec 23, 2022 |
| Dell          | XPS 9320                    | [7bb7ba7202](https://linux-hardware.org/?probe=7bb7ba7202) | Dec 23, 2022 |
| Medion        | X6816                       | [bafbf1ea90](https://linux-hardware.org/?probe=bafbf1ea90) | Dec 23, 2022 |
| Medion        | X6816                       | [ac9627e5d4](https://linux-hardware.org/?probe=ac9627e5d4) | Dec 23, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [db7dc4fa25](https://linux-hardware.org/?probe=db7dc4fa25) | Dec 22, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [e8ac233c29](https://linux-hardware.org/?probe=e8ac233c29) | Dec 22, 2022 |
| HP            | Compaq 6730b (GW687AV)      | [8c936284b0](https://linux-hardware.org/?probe=8c936284b0) | Dec 22, 2022 |
| Monster       | TULPAR T5 V20.1             | [23cb6e06f8](https://linux-hardware.org/?probe=23cb6e06f8) | Dec 22, 2022 |
| HP            | Pavilion dv9000 (RR329EA... | [6fc7281f2f](https://linux-hardware.org/?probe=6fc7281f2f) | Dec 22, 2022 |
| HP            | Pavilion Laptop 15-cs3xx... | [a62d8c781d](https://linux-hardware.org/?probe=a62d8c781d) | Dec 22, 2022 |
| HUAWEI        | VLT-WX0                     | [6f2d542a6e](https://linux-hardware.org/?probe=6f2d542a6e) | Dec 22, 2022 |
| Packard Be... | DOT S                       | [c26f1d77e6](https://linux-hardware.org/?probe=c26f1d77e6) | Dec 22, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [54273f1267](https://linux-hardware.org/?probe=54273f1267) | Dec 22, 2022 |
| ASUSTek       | 1215P                       | [a39ca1c22f](https://linux-hardware.org/?probe=a39ca1c22f) | Dec 21, 2022 |
| ASUSTek       | 1215P                       | [ed3dc80f1b](https://linux-hardware.org/?probe=ed3dc80f1b) | Dec 21, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BT      | [543b6fc9db](https://linux-hardware.org/?probe=543b6fc9db) | Dec 21, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | [5ea57fb331](https://linux-hardware.org/?probe=5ea57fb331) | Dec 21, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | [c4f6f99d36](https://linux-hardware.org/?probe=c4f6f99d36) | Dec 21, 2022 |
| Dell          | Latitude E7470              | [e171eea812](https://linux-hardware.org/?probe=e171eea812) | Dec 21, 2022 |
| ASUSTek       | S551LB                      | [5e48f71064](https://linux-hardware.org/?probe=5e48f71064) | Dec 20, 2022 |
| HP            | Sona                        | [85c88dea70](https://linux-hardware.org/?probe=85c88dea70) | Dec 20, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | [a4549398af](https://linux-hardware.org/?probe=a4549398af) | Dec 20, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [2b8c2f06eb](https://linux-hardware.org/?probe=2b8c2f06eb) | Dec 20, 2022 |
| Notebook      | PCX0DX                      | [83c28a3013](https://linux-hardware.org/?probe=83c28a3013) | Dec 20, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [9f5a91c628](https://linux-hardware.org/?probe=9f5a91c628) | Dec 19, 2022 |
| Sony          | VGN-FW11E                   | [2d57afaa38](https://linux-hardware.org/?probe=2d57afaa38) | Dec 19, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [686a93a02a](https://linux-hardware.org/?probe=686a93a02a) | Dec 19, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [8e10fc1464](https://linux-hardware.org/?probe=8e10fc1464) | Dec 18, 2022 |
| ASUSTek       | 900SD                       | [43d2c88062](https://linux-hardware.org/?probe=43d2c88062) | Dec 18, 2022 |
| Lenovo        | ThinkPad R61 77324TG        | [90c300a51c](https://linux-hardware.org/?probe=90c300a51c) | Dec 18, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [7dc7a80819](https://linux-hardware.org/?probe=7dc7a80819) | Dec 18, 2022 |
| Acer          | TravelMate P253             | [97d650e93f](https://linux-hardware.org/?probe=97d650e93f) | Dec 18, 2022 |
| Dell          | Latitude E7470              | [262849f0f6](https://linux-hardware.org/?probe=262849f0f6) | Dec 18, 2022 |
| HP            | Laptop 15s-fq2xxx           | [ab6fd91b71](https://linux-hardware.org/?probe=ab6fd91b71) | Dec 17, 2022 |
| HP            | Laptop 15s-fq2xxx           | [1a23b502b9](https://linux-hardware.org/?probe=1a23b502b9) | Dec 17, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | [75126bccca](https://linux-hardware.org/?probe=75126bccca) | Dec 17, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [a54756ab6f](https://linux-hardware.org/?probe=a54756ab6f) | Dec 17, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [fc473cc90f](https://linux-hardware.org/?probe=fc473cc90f) | Dec 17, 2022 |
| WYSE          | XM CLASS                    | [8aac2f31cb](https://linux-hardware.org/?probe=8aac2f31cb) | Dec 17, 2022 |
| HP            | EliteBook 820 G3            | [5e5909e93f](https://linux-hardware.org/?probe=5e5909e93f) | Dec 17, 2022 |
| ASUSTek       | ROG Strix G513RC_G513RC     | [feb5e321dc](https://linux-hardware.org/?probe=feb5e321dc) | Dec 16, 2022 |
| Acer          | TravelMate P253             | [80188fd5bf](https://linux-hardware.org/?probe=80188fd5bf) | Dec 16, 2022 |
| Toshiba       | Satellite M70               | [9415a97254](https://linux-hardware.org/?probe=9415a97254) | Dec 16, 2022 |
| Dell          | XPS 15 9520                 | [dcf616e068](https://linux-hardware.org/?probe=dcf616e068) | Dec 16, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | [665bd04471](https://linux-hardware.org/?probe=665bd04471) | Dec 16, 2022 |
| Alienware     | 15                          | [6da8e1748a](https://linux-hardware.org/?probe=6da8e1748a) | Dec 16, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [30fda215a5](https://linux-hardware.org/?probe=30fda215a5) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [d5cf351351](https://linux-hardware.org/?probe=d5cf351351) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [e2056deb8a](https://linux-hardware.org/?probe=e2056deb8a) | Dec 16, 2022 |
| HUAWEI        | BOM-WXX9                    | [dd664077fe](https://linux-hardware.org/?probe=dd664077fe) | Dec 16, 2022 |
| HP            | Laptop 15s-fq2xxx           | [d9c3d0a5cd](https://linux-hardware.org/?probe=d9c3d0a5cd) | Dec 16, 2022 |
| HP            | Laptop 15-da0xxx            | [d871acfe36](https://linux-hardware.org/?probe=d871acfe36) | Dec 16, 2022 |
| Toshiba       | Satellite M70               | [79506873c1](https://linux-hardware.org/?probe=79506873c1) | Dec 15, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [18d67ba2ab](https://linux-hardware.org/?probe=18d67ba2ab) | Dec 15, 2022 |
| Packard Be... | EasyNote TJ71               | [f722162e15](https://linux-hardware.org/?probe=f722162e15) | Dec 15, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [5e8318b8b8](https://linux-hardware.org/?probe=5e8318b8b8) | Dec 15, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [57ecebdc0f](https://linux-hardware.org/?probe=57ecebdc0f) | Dec 15, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [d5c9abda1e](https://linux-hardware.org/?probe=d5c9abda1e) | Dec 15, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | [1d57f3ab30](https://linux-hardware.org/?probe=1d57f3ab30) | Dec 15, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | [a1d6879fab](https://linux-hardware.org/?probe=a1d6879fab) | Dec 15, 2022 |
| HP            | Compaq 6735s                | [72d29aa11f](https://linux-hardware.org/?probe=72d29aa11f) | Dec 14, 2022 |
| Samsung       | 750XDA                      | [0120054e9f](https://linux-hardware.org/?probe=0120054e9f) | Dec 14, 2022 |
| ASUSTek       | X302LA                      | [8404a0b0c6](https://linux-hardware.org/?probe=8404a0b0c6) | Dec 14, 2022 |
| PC Special... | Elimina Iv 17               | [66a5d6dd6a](https://linux-hardware.org/?probe=66a5d6dd6a) | Dec 13, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [6fc042d213](https://linux-hardware.org/?probe=6fc042d213) | Dec 13, 2022 |
| HP            | EliteBook 820 G3            | [ff5b82cee3](https://linux-hardware.org/?probe=ff5b82cee3) | Dec 13, 2022 |
| Lenovo        | G505 20240                  | [e6777c2fbc](https://linux-hardware.org/?probe=e6777c2fbc) | Dec 13, 2022 |
| Lenovo        | ThinkPad T480s 20L8002WM... | [d742af8997](https://linux-hardware.org/?probe=d742af8997) | Dec 13, 2022 |
| MSI           | GS65 Stealth Thin 8RF       | [074195107c](https://linux-hardware.org/?probe=074195107c) | Dec 12, 2022 |
| Packard Be... | EasyNote TJ71               | [45630329df](https://linux-hardware.org/?probe=45630329df) | Dec 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [a9505fa3e4](https://linux-hardware.org/?probe=a9505fa3e4) | Dec 12, 2022 |
| HP            | EliteBook 820 G3            | [1e0eec72b2](https://linux-hardware.org/?probe=1e0eec72b2) | Dec 12, 2022 |
| Apple         | MacBookPro14,3              | [7cefe54b56](https://linux-hardware.org/?probe=7cefe54b56) | Dec 12, 2022 |
| HP            | EliteBook 8570w             | [367579550b](https://linux-hardware.org/?probe=367579550b) | Dec 11, 2022 |
| SGIN          | laptop                      | [8f650d00dd](https://linux-hardware.org/?probe=8f650d00dd) | Dec 11, 2022 |
| Toshiba       | Satellite L455              | [e92985332e](https://linux-hardware.org/?probe=e92985332e) | Dec 11, 2022 |
| Lenovo        | G50-45 80E3                 | [754e028997](https://linux-hardware.org/?probe=754e028997) | Dec 11, 2022 |
| Lenovo        | G50-45 80E3                 | [fb2f97325d](https://linux-hardware.org/?probe=fb2f97325d) | Dec 11, 2022 |
| HP            | Laptop 15s-fq2xxx           | [129c077e02](https://linux-hardware.org/?probe=129c077e02) | Dec 11, 2022 |
| ASUSTek       | K50C                        | [6cf2037e0f](https://linux-hardware.org/?probe=6cf2037e0f) | Dec 11, 2022 |
| ASUSTek       | S551LN                      | [9aabc2d159](https://linux-hardware.org/?probe=9aabc2d159) | Dec 11, 2022 |
| Google        | Blooglet                    | [a9d65d2144](https://linux-hardware.org/?probe=a9d65d2144) | Dec 11, 2022 |
| Valve         | Jupiter                     | [26c1e67dff](https://linux-hardware.org/?probe=26c1e67dff) | Dec 11, 2022 |
| Valve         | Jupiter                     | [e143b181a1](https://linux-hardware.org/?probe=e143b181a1) | Dec 11, 2022 |
| HP            | Pavilion dv6000 (RY649EA... | [9deecc89f5](https://linux-hardware.org/?probe=9deecc89f5) | Dec 10, 2022 |
| Acer          | TravelMate 4070             | [8f9e4c0e26](https://linux-hardware.org/?probe=8f9e4c0e26) | Dec 10, 2022 |
| HUAWEI        | CREM-WXX9                   | [1b6dee1e4a](https://linux-hardware.org/?probe=1b6dee1e4a) | Dec 10, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [61b2bab886](https://linux-hardware.org/?probe=61b2bab886) | Dec 10, 2022 |
| ASUSTek       | VivoBook S15 X510UF         | [5f72ad2758](https://linux-hardware.org/?probe=5f72ad2758) | Dec 10, 2022 |
| HUAWEI        | CREM-WXX9                   | [fdda7ba30e](https://linux-hardware.org/?probe=fdda7ba30e) | Dec 10, 2022 |
| Acer          | Aspire ES1-512              | [c9313e3820](https://linux-hardware.org/?probe=c9313e3820) | Dec 10, 2022 |
| SANTECH       | NHx0DB,DE                   | [89e8d0f23e](https://linux-hardware.org/?probe=89e8d0f23e) | Dec 10, 2022 |
| Dell          | Inspiron 5570               | [4d78d14f00](https://linux-hardware.org/?probe=4d78d14f00) | Dec 10, 2022 |
| Toshiba       | Satellite C70-C-11L         | [8de407e526](https://linux-hardware.org/?probe=8de407e526) | Dec 09, 2022 |
| HP            | 250 G3                      | [7e7b65bb5f](https://linux-hardware.org/?probe=7e7b65bb5f) | Dec 09, 2022 |
| HP            | 250 G3                      | [170a8b35c6](https://linux-hardware.org/?probe=170a8b35c6) | Dec 09, 2022 |
| Packard Be... | EasyNote TJ71               | [4c0af21017](https://linux-hardware.org/?probe=4c0af21017) | Dec 09, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [d28d2da00b](https://linux-hardware.org/?probe=d28d2da00b) | Dec 09, 2022 |
| Google        | Blooglet                    | [241c0f4331](https://linux-hardware.org/?probe=241c0f4331) | Dec 09, 2022 |
| HP            | EliteBook 830 G8 Noteboo... | [5d96a0484a](https://linux-hardware.org/?probe=5d96a0484a) | Dec 08, 2022 |
| HP            | EliteBook 840 G5            | [946807e266](https://linux-hardware.org/?probe=946807e266) | Dec 08, 2022 |
| HP            | Pavilion Laptop 15-eg1xx... | [970f8e990b](https://linux-hardware.org/?probe=970f8e990b) | Dec 08, 2022 |
| HP            | Pavilion Laptop 15-eg1xx... | [0e7da55713](https://linux-hardware.org/?probe=0e7da55713) | Dec 08, 2022 |
| Toshiba       | Satellite C850-1LJ          | [4af2ab112f](https://linux-hardware.org/?probe=4af2ab112f) | Dec 08, 2022 |
| Lenovo        | ThinkPad P52 20M9001KIX     | [f470667df1](https://linux-hardware.org/?probe=f470667df1) | Dec 08, 2022 |
| Lenovo        | ThinkPad P52 20M9001KIX     | [2562e31e5a](https://linux-hardware.org/?probe=2562e31e5a) | Dec 08, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | [182678a056](https://linux-hardware.org/?probe=182678a056) | Dec 08, 2022 |
| Packard Be... | EasyNote TJ71               | [f4bf9ede5b](https://linux-hardware.org/?probe=f4bf9ede5b) | Dec 08, 2022 |
| HP            | ProBook 640 G1              | [c3bf44d032](https://linux-hardware.org/?probe=c3bf44d032) | Dec 08, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | [c66f0c0c8d](https://linux-hardware.org/?probe=c66f0c0c8d) | Dec 08, 2022 |
| Lenovo        | V15 G2 ITL 82KB             | [ca25d43c56](https://linux-hardware.org/?probe=ca25d43c56) | Dec 08, 2022 |
| Lenovo        | V15 G2 ITL 82KB             | [104e0e02d1](https://linux-hardware.org/?probe=104e0e02d1) | Dec 08, 2022 |
| Acer          | TravelMate 4070             | [ec589662a2](https://linux-hardware.org/?probe=ec589662a2) | Dec 08, 2022 |
| Toshiba       | Satellite Pro S500          | [bcf1460e47](https://linux-hardware.org/?probe=bcf1460e47) | Dec 08, 2022 |
| HP            | EliteBook 840 G5            | [bb11ec4f3f](https://linux-hardware.org/?probe=bb11ec4f3f) | Dec 08, 2022 |
| Google        | Sasuke                      | [527f49b0ae](https://linux-hardware.org/?probe=527f49b0ae) | Dec 07, 2022 |
| Dell          | Inspiron 5505               | [183c4593a7](https://linux-hardware.org/?probe=183c4593a7) | Dec 07, 2022 |
| Google        | Sasuke                      | [5bd0b833cb](https://linux-hardware.org/?probe=5bd0b833cb) | Dec 07, 2022 |
| Acer          | Aspire 5935                 | [01da97dae6](https://linux-hardware.org/?probe=01da97dae6) | Dec 07, 2022 |
| Dell          | Studio 1558                 | [ce0c8ffe20](https://linux-hardware.org/?probe=ce0c8ffe20) | Dec 06, 2022 |
| ASUSTek       | ZenBook UX533FD_UX533FD     | [799ba39d5e](https://linux-hardware.org/?probe=799ba39d5e) | Dec 06, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [10fea00e5a](https://linux-hardware.org/?probe=10fea00e5a) | Dec 06, 2022 |
| Teclast       | F7 Plus                     | [5e155a318e](https://linux-hardware.org/?probe=5e155a318e) | Dec 06, 2022 |
| Acer          | Aspire 5935                 | [44895b82f9](https://linux-hardware.org/?probe=44895b82f9) | Dec 05, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [dd7a026e5e](https://linux-hardware.org/?probe=dd7a026e5e) | Dec 05, 2022 |
| MSI           | Creator 15M A9SD            | [f8e6206ba6](https://linux-hardware.org/?probe=f8e6206ba6) | Dec 05, 2022 |
| Toshiba       | Satellite L50-B             | [6d92129c25](https://linux-hardware.org/?probe=6d92129c25) | Dec 05, 2022 |
| ASUSTek       | K53SC                       | [57e7bb2427](https://linux-hardware.org/?probe=57e7bb2427) | Dec 05, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [fd9114a304](https://linux-hardware.org/?probe=fd9114a304) | Dec 04, 2022 |
| ASUSTek       | X750JN                      | [af27460f17](https://linux-hardware.org/?probe=af27460f17) | Dec 04, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [888ec24e9d](https://linux-hardware.org/?probe=888ec24e9d) | Dec 04, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [ac92442dbc](https://linux-hardware.org/?probe=ac92442dbc) | Dec 04, 2022 |
| Schenker      | XMG APEX (Mid 2021)         | [41824c584f](https://linux-hardware.org/?probe=41824c584f) | Dec 03, 2022 |
| Acer          | Aspire A315-23              | [8c3beba1e1](https://linux-hardware.org/?probe=8c3beba1e1) | Dec 03, 2022 |
| Acer          | Aspire A315-21              | [91eb1913d7](https://linux-hardware.org/?probe=91eb1913d7) | Dec 03, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [f34caf87d5](https://linux-hardware.org/?probe=f34caf87d5) | Dec 03, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [c00aab388c](https://linux-hardware.org/?probe=c00aab388c) | Dec 03, 2022 |
| Lenovo        | XiaoXinPro 16ACH 2021 82... | [2085f260e1](https://linux-hardware.org/?probe=2085f260e1) | Dec 03, 2022 |
| HP            | Pavilion 15                 | [87de142ecd](https://linux-hardware.org/?probe=87de142ecd) | Dec 03, 2022 |
| Google        | Blooglet                    | [045f75ab43](https://linux-hardware.org/?probe=045f75ab43) | Dec 03, 2022 |
| HUAWEI        | MACHC-WAX9                  | [958e17ffc9](https://linux-hardware.org/?probe=958e17ffc9) | Dec 03, 2022 |
| Lenovo        | G580 2189                   | [80fe3f7171](https://linux-hardware.org/?probe=80fe3f7171) | Dec 03, 2022 |
| Samsung       | 530U3C/530U4C/532U3C        | [91edd3827d](https://linux-hardware.org/?probe=91edd3827d) | Dec 02, 2022 |
| Dell          | XPS 15 9570                 | [867e3d70f0](https://linux-hardware.org/?probe=867e3d70f0) | Dec 02, 2022 |
| HP            | Unknown                     | [741029c3af](https://linux-hardware.org/?probe=741029c3af) | Dec 02, 2022 |
| HP            | Notebook                    | [4184c8fa06](https://linux-hardware.org/?probe=4184c8fa06) | Dec 02, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [9d27bb4f90](https://linux-hardware.org/?probe=9d27bb4f90) | Dec 01, 2022 |
| Mediacom      | SmartBook 14 FullHD - SB... | [1df1f552ff](https://linux-hardware.org/?probe=1df1f552ff) | Dec 01, 2022 |
| Acer          | Aspire 5750G                | [a8236e24a5](https://linux-hardware.org/?probe=a8236e24a5) | Dec 01, 2022 |
| HP            | ProBook 440 G7              | [a54a325001](https://linux-hardware.org/?probe=a54a325001) | Dec 01, 2022 |
| Acer          | Aspire 5750G                | [198d7f2534](https://linux-hardware.org/?probe=198d7f2534) | Dec 01, 2022 |
| ASUSTek       | K52F                        | [63c08600c3](https://linux-hardware.org/?probe=63c08600c3) | Dec 01, 2022 |
| ASUSTek       | K52F                        | [4276cc2cb9](https://linux-hardware.org/?probe=4276cc2cb9) | Dec 01, 2022 |
| Dell          | Studio 1558                 | [cf40788ef8](https://linux-hardware.org/?probe=cf40788ef8) | Nov 30, 2022 |
| ASUSTek       | K53SC                       | [6d21dd6cea](https://linux-hardware.org/?probe=6d21dd6cea) | Nov 30, 2022 |
| HP            | Pavilion g6                 | [c552ca011c](https://linux-hardware.org/?probe=c552ca011c) | Nov 30, 2022 |
| Apple         | MacBook4,1                  | [0866a64897](https://linux-hardware.org/?probe=0866a64897) | Nov 30, 2022 |
| Apple         | MacBookAir8,1               | [7581ef0e85](https://linux-hardware.org/?probe=7581ef0e85) | Nov 29, 2022 |
| HUAWEI        | BOD-WXX9                    | [a2b8deb4e3](https://linux-hardware.org/?probe=a2b8deb4e3) | Nov 29, 2022 |
| Lenovo        | IdeaPad 110-15AST 80TR      | [cbb0c1dca7](https://linux-hardware.org/?probe=cbb0c1dca7) | Nov 29, 2022 |
| HP            | Compaq nc6320 (GB940ES#A... | [bb417133ee](https://linux-hardware.org/?probe=bb417133ee) | Nov 29, 2022 |
| HP            | Compaq nc6320 (GB940ES#A... | [ddb2f42bcc](https://linux-hardware.org/?probe=ddb2f42bcc) | Nov 29, 2022 |
| Acer          | Aspire 5738                 | [a9697f1e7a](https://linux-hardware.org/?probe=a9697f1e7a) | Nov 28, 2022 |
| MSI           | Prestige 15 A12SC           | [af2a404105](https://linux-hardware.org/?probe=af2a404105) | Nov 28, 2022 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [ab9b95babe](https://linux-hardware.org/?probe=ab9b95babe) | Nov 28, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [1620a1a2cb](https://linux-hardware.org/?probe=1620a1a2cb) | Nov 28, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | [0d99651537](https://linux-hardware.org/?probe=0d99651537) | Nov 28, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | [3f660318ea](https://linux-hardware.org/?probe=3f660318ea) | Nov 28, 2022 |
| Unknown       | Unknown                     | [4f73de3788](https://linux-hardware.org/?probe=4f73de3788) | Nov 27, 2022 |
| Dell          | XPS 13 9305                 | [c306dcfa4f](https://linux-hardware.org/?probe=c306dcfa4f) | Nov 27, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [44a305db4d](https://linux-hardware.org/?probe=44a305db4d) | Nov 27, 2022 |
| ASUSTek       | VivoBook S15 X510UF         | [7bd68a8bb1](https://linux-hardware.org/?probe=7bd68a8bb1) | Nov 27, 2022 |
| Lenovo        | S20-30 Touch 20434          | [63d2134051](https://linux-hardware.org/?probe=63d2134051) | Nov 27, 2022 |
| Lenovo        | B50-30 80ES                 | [ced4c1f563](https://linux-hardware.org/?probe=ced4c1f563) | Nov 27, 2022 |
| Dell          | G5 5587                     | [689db41249](https://linux-hardware.org/?probe=689db41249) | Nov 27, 2022 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [f397d89e9b](https://linux-hardware.org/?probe=f397d89e9b) | Nov 27, 2022 |
| Lenovo        | ThinkPad X280 20KES2DD0D    | [394b24459c](https://linux-hardware.org/?probe=394b24459c) | Nov 27, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0XX0... | [f91c391079](https://linux-hardware.org/?probe=f91c391079) | Nov 26, 2022 |
| MSI           | Creator 15M A9SD            | [8b47bbf475](https://linux-hardware.org/?probe=8b47bbf475) | Nov 26, 2022 |
| Lenovo        | Y50-70 20378                | [57e4892065](https://linux-hardware.org/?probe=57e4892065) | Nov 26, 2022 |
| HUAWEI        | KLVL-WXX9                   | [ce7815f106](https://linux-hardware.org/?probe=ce7815f106) | Nov 26, 2022 |
| Lenovo        | ThinkPad T495 20NJS0L100    | [1e9e7f34df](https://linux-hardware.org/?probe=1e9e7f34df) | Nov 26, 2022 |
| Sony          | SVP1121X9EB                 | [78df785a47](https://linux-hardware.org/?probe=78df785a47) | Nov 26, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [123efdf4df](https://linux-hardware.org/?probe=123efdf4df) | Nov 26, 2022 |
| ASUSTek       | X202E                       | [24a8811d77](https://linux-hardware.org/?probe=24a8811d77) | Nov 25, 2022 |
| ASUSTek       | X202E                       | [69a3fa54c1](https://linux-hardware.org/?probe=69a3fa54c1) | Nov 25, 2022 |
| Lenovo        | ThinkPad T430 2349IF8       | [4d8bd1760a](https://linux-hardware.org/?probe=4d8bd1760a) | Nov 25, 2022 |
| MSI           | Creator 15M A9SD            | [a15ef33296](https://linux-hardware.org/?probe=a15ef33296) | Nov 25, 2022 |
| Acer          | Nitro AN515-45              | [10186425ec](https://linux-hardware.org/?probe=10186425ec) | Nov 25, 2022 |
| HP            | ProBook 450 G6              | [d044aabfec](https://linux-hardware.org/?probe=d044aabfec) | Nov 25, 2022 |
| Acer          | Nitro AN515-45              | [5a7b57dae6](https://linux-hardware.org/?probe=5a7b57dae6) | Nov 25, 2022 |
| Dell          | Latitude 3450               | [d7af694917](https://linux-hardware.org/?probe=d7af694917) | Nov 25, 2022 |
| ASUSTek       | X551CAP                     | [f40e3110d0](https://linux-hardware.org/?probe=f40e3110d0) | Nov 24, 2022 |
| Alienware     | 15                          | [3423725ae2](https://linux-hardware.org/?probe=3423725ae2) | Nov 24, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [2d1c8c7ea5](https://linux-hardware.org/?probe=2d1c8c7ea5) | Nov 24, 2022 |
| ASUSTek       | X510UQ                      | [5972ededc2](https://linux-hardware.org/?probe=5972ededc2) | Nov 24, 2022 |
| HP            | Pavilion 15                 | [b0d1e2e0ba](https://linux-hardware.org/?probe=b0d1e2e0ba) | Nov 24, 2022 |
| HP            | Laptop 15-dw0xxx            | [894c4e9ebf](https://linux-hardware.org/?probe=894c4e9ebf) | Nov 24, 2022 |
| Acer          | Aspire V3-772G              | [7ce85c6de5](https://linux-hardware.org/?probe=7ce85c6de5) | Nov 23, 2022 |
| Lenovo        | G500 20236                  | [2bfa796e90](https://linux-hardware.org/?probe=2bfa796e90) | Nov 23, 2022 |
| Lenovo        | G500 20236                  | [afcb386e71](https://linux-hardware.org/?probe=afcb386e71) | Nov 23, 2022 |
| Unknown       | Unknown                     | [f40545f0d5](https://linux-hardware.org/?probe=f40545f0d5) | Nov 23, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [fd8121fecd](https://linux-hardware.org/?probe=fd8121fecd) | Nov 22, 2022 |
| HP            | 250 G7 Notebook PC          | [242d685287](https://linux-hardware.org/?probe=242d685287) | Nov 22, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [923ccf8b76](https://linux-hardware.org/?probe=923ccf8b76) | Nov 22, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [e9ba2ff234](https://linux-hardware.org/?probe=e9ba2ff234) | Nov 22, 2022 |
| Toshiba       | Satellite Pro S500          | [a9d392c0c3](https://linux-hardware.org/?probe=a9d392c0c3) | Nov 22, 2022 |
| ASUSTek       | GL503VS                     | [18fa411a6d](https://linux-hardware.org/?probe=18fa411a6d) | Nov 22, 2022 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [bdf1794487](https://linux-hardware.org/?probe=bdf1794487) | Nov 22, 2022 |
| HUAWEI        | BOHB-WAX9                   | [b0d3226df4](https://linux-hardware.org/?probe=b0d3226df4) | Nov 21, 2022 |
| Acer          | Aspire A515-45              | [b0b972f8ef](https://linux-hardware.org/?probe=b0b972f8ef) | Nov 21, 2022 |
| Dell          | Latitude 9420               | [ddf8c8749c](https://linux-hardware.org/?probe=ddf8c8749c) | Nov 21, 2022 |
| MSI           | Creator 15M A9SD            | [e6d5440b09](https://linux-hardware.org/?probe=e6d5440b09) | Nov 21, 2022 |
| HP            | Laptop 14s-fq0xxx           | [a94bd1fd5a](https://linux-hardware.org/?probe=a94bd1fd5a) | Nov 21, 2022 |
| HP            | Laptop 14s-fq0xxx           | [cc9c76c85c](https://linux-hardware.org/?probe=cc9c76c85c) | Nov 21, 2022 |
| HP            | Laptop 15-db0xxx            | [f634446cde](https://linux-hardware.org/?probe=f634446cde) | Nov 21, 2022 |
| Google        | Sasuke                      | [35330e59ad](https://linux-hardware.org/?probe=35330e59ad) | Nov 20, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [aaa2d66240](https://linux-hardware.org/?probe=aaa2d66240) | Nov 20, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [3ecbc7acb4](https://linux-hardware.org/?probe=3ecbc7acb4) | Nov 20, 2022 |
| HP            | Pavilion Laptop 14-ce2xx... | [cd2b457ffb](https://linux-hardware.org/?probe=cd2b457ffb) | Nov 20, 2022 |
| HP            | Notebook                    | [1278403b39](https://linux-hardware.org/?probe=1278403b39) | Nov 20, 2022 |
| Lenovo        | ThinkPad L380 20M6S4E000    | [4f65299a92](https://linux-hardware.org/?probe=4f65299a92) | Nov 20, 2022 |
| Sony          | VPCEB2M1E                   | [eeefed51e4](https://linux-hardware.org/?probe=eeefed51e4) | Nov 20, 2022 |
| Acer          | Nitro AN515-54              | [b9d2b8c218](https://linux-hardware.org/?probe=b9d2b8c218) | Nov 20, 2022 |
| Dell          | XPS 13 7390                 | [9f6c38b4ee](https://linux-hardware.org/?probe=9f6c38b4ee) | Nov 20, 2022 |
| Acer          | aspire5740                  | [6cdc4f5cfc](https://linux-hardware.org/?probe=6cdc4f5cfc) | Nov 20, 2022 |
| Acer          | Aspire ES1-521              | [6af4249f1a](https://linux-hardware.org/?probe=6af4249f1a) | Nov 20, 2022 |
| Apple         | MacBookPro5,1               | [4f04b7d627](https://linux-hardware.org/?probe=4f04b7d627) | Nov 19, 2022 |
| Acer          | Aspire ES1-111M             | [3b15bcfd88](https://linux-hardware.org/?probe=3b15bcfd88) | Nov 19, 2022 |
| HUAWEI        | BOHB-WAX9                   | [8ffb460b9e](https://linux-hardware.org/?probe=8ffb460b9e) | Nov 19, 2022 |
| Olidata       | T7700                       | [d8220596fc](https://linux-hardware.org/?probe=d8220596fc) | Nov 19, 2022 |
| Apple         | MacBook4,1                  | [c2d79be90d](https://linux-hardware.org/?probe=c2d79be90d) | Nov 19, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [36bc4b545f](https://linux-hardware.org/?probe=36bc4b545f) | Nov 19, 2022 |
| HP            | Presario CQ58               | [fc1d1892ef](https://linux-hardware.org/?probe=fc1d1892ef) | Nov 19, 2022 |
| Apple         | MacBookAir4,2               | [c11ad764af](https://linux-hardware.org/?probe=c11ad764af) | Nov 19, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [0b0d1f6427](https://linux-hardware.org/?probe=0b0d1f6427) | Nov 19, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [865fa07274](https://linux-hardware.org/?probe=865fa07274) | Nov 19, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [68d651f36b](https://linux-hardware.org/?probe=68d651f36b) | Nov 19, 2022 |
| Sony          | VPCYA1C5E                   | [416067b991](https://linux-hardware.org/?probe=416067b991) | Nov 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [6e0f255eeb](https://linux-hardware.org/?probe=6e0f255eeb) | Nov 18, 2022 |
| Fujitsu       | LIFEBOOK U759               | [945910eb8a](https://linux-hardware.org/?probe=945910eb8a) | Nov 18, 2022 |
| Acer          | Aspire V5-573G              | [f58db71272](https://linux-hardware.org/?probe=f58db71272) | Nov 18, 2022 |
| HP            | Laptop 17-cp0xxx            | [e18aef24ac](https://linux-hardware.org/?probe=e18aef24ac) | Nov 17, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21E3C... | [dee1a4e29e](https://linux-hardware.org/?probe=dee1a4e29e) | Nov 17, 2022 |
| Dell          | XPS 13 7390                 | [19d18ac52c](https://linux-hardware.org/?probe=19d18ac52c) | Nov 17, 2022 |
| Mediacom      | FlexBook_edge13-M-FBE13     | [aa7f8583b6](https://linux-hardware.org/?probe=aa7f8583b6) | Nov 17, 2022 |
| Mediacom      | FlexBook_edge13-M-FBE13     | [c15d4ee015](https://linux-hardware.org/?probe=c15d4ee015) | Nov 17, 2022 |
| Mediacom      | FlexBook_edge13-M-FBE13     | [b5106cb728](https://linux-hardware.org/?probe=b5106cb728) | Nov 17, 2022 |
| ASUSTek       | X541UV                      | [74aca760f1](https://linux-hardware.org/?probe=74aca760f1) | Nov 17, 2022 |
| HP            | Laptop 15-dw0xxx            | [b81771eed0](https://linux-hardware.org/?probe=b81771eed0) | Nov 17, 2022 |
| MSI           | Creator 15M A9SD            | [f1fdc384f9](https://linux-hardware.org/?probe=f1fdc384f9) | Nov 17, 2022 |
| HP            | Laptop 15-db0xxx            | [5aa50e7f6c](https://linux-hardware.org/?probe=5aa50e7f6c) | Nov 17, 2022 |
| HP            | OMEN by Laptop 15-dh0xxx    | [523e8a1c6b](https://linux-hardware.org/?probe=523e8a1c6b) | Nov 17, 2022 |
| HP            | 250 G4                      | [3f2660a101](https://linux-hardware.org/?probe=3f2660a101) | Nov 16, 2022 |
| HP            | 250 G4                      | [cc4a368fd3](https://linux-hardware.org/?probe=cc4a368fd3) | Nov 16, 2022 |
| ASUSTek       | N53Jf                       | [61f5cf6214](https://linux-hardware.org/?probe=61f5cf6214) | Nov 16, 2022 |
| HP            | Laptop 15-db0xxx            | [f6202bb6fa](https://linux-hardware.org/?probe=f6202bb6fa) | Nov 16, 2022 |
| MSI           | Prestige 14Evo A11M         | [78601d078c](https://linux-hardware.org/?probe=78601d078c) | Nov 16, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [922ce95539](https://linux-hardware.org/?probe=922ce95539) | Nov 16, 2022 |
| Dell          | XPS 15 9570                 | [d62ee2298d](https://linux-hardware.org/?probe=d62ee2298d) | Nov 16, 2022 |
| Toshiba       | Satellite Pro S500          | [f528238460](https://linux-hardware.org/?probe=f528238460) | Nov 16, 2022 |
| Toshiba       | Satellite Pro S500          | [97ccc55f03](https://linux-hardware.org/?probe=97ccc55f03) | Nov 16, 2022 |
| Fujitsu       | LIFEBOOK E554               | [df8344d098](https://linux-hardware.org/?probe=df8344d098) | Nov 16, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [809e86d562](https://linux-hardware.org/?probe=809e86d562) | Nov 15, 2022 |
| HP            | ProBook 450 G7              | [612006bada](https://linux-hardware.org/?probe=612006bada) | Nov 15, 2022 |
| HP            | ProBook 450 G7              | [2e122b28c4](https://linux-hardware.org/?probe=2e122b28c4) | Nov 15, 2022 |
| Fujitsu       | LIFEBOOK E557               | [a57972523b](https://linux-hardware.org/?probe=a57972523b) | Nov 15, 2022 |
| MSI           | PS63 Modern 8RC             | [699ea2cc17](https://linux-hardware.org/?probe=699ea2cc17) | Nov 15, 2022 |
| System76      | Oryx Pro                    | [3ea0d459e1](https://linux-hardware.org/?probe=3ea0d459e1) | Nov 15, 2022 |
| Acer          | Aspire A715-42G             | [403bc1b6b5](https://linux-hardware.org/?probe=403bc1b6b5) | Nov 14, 2022 |
| Acer          | Aspire A715-42G             | [6209796b42](https://linux-hardware.org/?probe=6209796b42) | Nov 14, 2022 |
| Lenovo        | ThinkPad T430 2349IF8       | [b6e353af2b](https://linux-hardware.org/?probe=b6e353af2b) | Nov 14, 2022 |
| Lenovo        | ThinkPad T430 2349IF8       | [c642a76e3e](https://linux-hardware.org/?probe=c642a76e3e) | Nov 14, 2022 |
| ASUSTek       | N751JX                      | [cea52af467](https://linux-hardware.org/?probe=cea52af467) | Nov 14, 2022 |
| Olidata       | T7700                       | [488f74cf4b](https://linux-hardware.org/?probe=488f74cf4b) | Nov 14, 2022 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | [d28a778811](https://linux-hardware.org/?probe=d28a778811) | Nov 14, 2022 |
| Microtech     | ebookLite                   | [471a1a6ac7](https://linux-hardware.org/?probe=471a1a6ac7) | Nov 14, 2022 |
| MSI           | Prestige 15 A12SC           | [211fdda09b](https://linux-hardware.org/?probe=211fdda09b) | Nov 14, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [0d39dde901](https://linux-hardware.org/?probe=0d39dde901) | Nov 14, 2022 |
| Acer          | Aspire 5600                 | [9fe2a7d245](https://linux-hardware.org/?probe=9fe2a7d245) | Nov 14, 2022 |
| Acer          | TravelMate P259-G2-MG       | [27d3da0f8a](https://linux-hardware.org/?probe=27d3da0f8a) | Nov 14, 2022 |
| Sony          | VGN-NS21M_W                 | [b3f4aef7a4](https://linux-hardware.org/?probe=b3f4aef7a4) | Nov 14, 2022 |
| Packard Be... | DOT S                       | [4e6d343f5c](https://linux-hardware.org/?probe=4e6d343f5c) | Nov 14, 2022 |
| Lenovo        | G510 20238                  | [99c1eee67d](https://linux-hardware.org/?probe=99c1eee67d) | Nov 14, 2022 |
| HP            | Laptop 15s-eq2xxx           | [36df61fb32](https://linux-hardware.org/?probe=36df61fb32) | Nov 13, 2022 |
| HUAWEI        | CREM-WXX9                   | [b33f7744b5](https://linux-hardware.org/?probe=b33f7744b5) | Nov 13, 2022 |
| HUAWEI        | CREM-WXX9                   | [9d7853c05b](https://linux-hardware.org/?probe=9d7853c05b) | Nov 13, 2022 |
| Lenovo        | ThinkPad L450 20DSS1GD00    | [b0ea02b16c](https://linux-hardware.org/?probe=b0ea02b16c) | Nov 13, 2022 |
| Lenovo        | ThinkPad T430 2349P25       | [ba76ce6af6](https://linux-hardware.org/?probe=ba76ce6af6) | Nov 13, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [48e0868598](https://linux-hardware.org/?probe=48e0868598) | Nov 13, 2022 |
| HP            | 250 G4                      | [58f7b77f39](https://linux-hardware.org/?probe=58f7b77f39) | Nov 12, 2022 |
| HP            | 250 G4                      | [f700001da4](https://linux-hardware.org/?probe=f700001da4) | Nov 12, 2022 |
| Acer          | aspire5740                  | [5218638790](https://linux-hardware.org/?probe=5218638790) | Nov 12, 2022 |
| Microtech     | ebookLite                   | [9c3039fa75](https://linux-hardware.org/?probe=9c3039fa75) | Nov 12, 2022 |
| Unknown       | Unknown                     | [0dff6ba2e2](https://linux-hardware.org/?probe=0dff6ba2e2) | Nov 12, 2022 |
| Acer          | aspire5740                  | [ba3ea314f0](https://linux-hardware.org/?probe=ba3ea314f0) | Nov 12, 2022 |
| HP            | 15                          | [bebef9206b](https://linux-hardware.org/?probe=bebef9206b) | Nov 12, 2022 |
| Dell          | Inspiron 15 3511            | [361f37b08d](https://linux-hardware.org/?probe=361f37b08d) | Nov 11, 2022 |
| Dell          | Latitude E6440              | [7d35b21aae](https://linux-hardware.org/?probe=7d35b21aae) | Nov 11, 2022 |
| ASUSTek       | X550JD                      | [9c88cc6c32](https://linux-hardware.org/?probe=9c88cc6c32) | Nov 11, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | [969fa6c183](https://linux-hardware.org/?probe=969fa6c183) | Nov 11, 2022 |
| Dell          | Latitude 12 Rugged Extre... | [d5b955a7b3](https://linux-hardware.org/?probe=d5b955a7b3) | Nov 11, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | [08963a61fb](https://linux-hardware.org/?probe=08963a61fb) | Nov 10, 2022 |
| Dell          | Venue 11 Pro 7140           | [78a6cdf739](https://linux-hardware.org/?probe=78a6cdf739) | Nov 10, 2022 |
| ASUSTek       | N550JK                      | [befb8455f0](https://linux-hardware.org/?probe=befb8455f0) | Nov 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [fc22f217b3](https://linux-hardware.org/?probe=fc22f217b3) | Nov 10, 2022 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | [89839b84cb](https://linux-hardware.org/?probe=89839b84cb) | Nov 10, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [31e940a232](https://linux-hardware.org/?probe=31e940a232) | Nov 10, 2022 |
| Microtech     | ebookLite                   | [63f80f900a](https://linux-hardware.org/?probe=63f80f900a) | Nov 10, 2022 |
| Timi          | TM1701                      | [917ec43bd1](https://linux-hardware.org/?probe=917ec43bd1) | Nov 09, 2022 |
| HP            | Pavilion Notebook           | [150409691d](https://linux-hardware.org/?probe=150409691d) | Nov 09, 2022 |
| HP            | 15                          | [c301aa00eb](https://linux-hardware.org/?probe=c301aa00eb) | Nov 09, 2022 |
| MSI           | GL63 8RD                    | [e10069a2f8](https://linux-hardware.org/?probe=e10069a2f8) | Nov 09, 2022 |
| Lenovo        | ThinkPad X250 20CLS3AJ00    | [ec16a4b3c5](https://linux-hardware.org/?probe=ec16a4b3c5) | Nov 09, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Italy/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 472       | 11.34%  |
| Ubuntu 18.04                 | 289       | 6.95%   |
| Ubuntu 22.04                 | 229       | 5.5%    |
| Arch Rolling                 | 122       | 2.93%   |
| OpenMandriva 4.2             | 106       | 2.55%   |
| OpenMandriva 4.3             | 98        | 2.36%   |
| Debian 11                    | 96        | 2.31%   |
| Fedora 36                    | 89        | 2.14%   |
| Arch                         | 75        | 1.8%    |
| Xubuntu 18.04                | 69        | 1.66%   |
| Ubuntu 19.10                 | 68        | 1.63%   |
| Ubuntu 22.10                 | 66        | 1.59%   |
| Pop!_OS 22.04                | 64        | 1.54%   |
| Linux Mint 21.1              | 64        | 1.54%   |
| Ubuntu 20.10                 | 61        | 1.47%   |
| Fedora 37                    | 61        | 1.47%   |
| Xubuntu 20.04                | 60        | 1.44%   |
| Ubuntu 21.10                 | 58        | 1.39%   |
| Linux Mint 20.3              | 58        | 1.39%   |
| Ubuntu 19.04                 | 56        | 1.35%   |
| Zorin 16                     | 55        | 1.32%   |
| KDE neon 20.04               | 54        | 1.3%    |
| Zorin 15                     | 49        | 1.18%   |
| Linux Mint 21                | 49        | 1.18%   |
| Debian 10                    | 46        | 1.11%   |
| EndeavourOS Rolling          | 45        | 1.08%   |
| Fedora 35                    | 42        | 1.01%   |
| Ubuntu 18.10                 | 40        | 0.96%   |
| Ubuntu 21.04                 | 39        | 0.94%   |
| OpenMandriva 23.01           | 36        | 0.87%   |
| Linux Mint 20.1              | 36        | 0.87%   |
| Kubuntu 22.04                | 36        | 0.87%   |
| Pop!_OS 20.10                | 35        | 0.84%   |
| Linux Mint 19.3              | 35        | 0.84%   |
| Kubuntu 20.04                | 35        | 0.84%   |
| Fedora 33                    | 35        | 0.84%   |
| Linux Mint 20.2              | 34        | 0.82%   |
| Linux Mint 20                | 34        | 0.82%   |
| ROSA R10                     | 29        | 0.7%    |
| openSUSE Tumbleweed-XXXXXXXX | 28        | 0.67%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1326      | 33.69%  |
| Linux Mint    | 306       | 7.77%   |
| Fedora        | 283       | 7.19%   |
| OpenMandriva  | 267       | 6.78%   |
| Arch          | 192       | 4.88%   |
| Xubuntu       | 176       | 4.47%   |
| Debian        | 173       | 4.4%    |
| Pop!_OS       | 156       | 3.96%   |
| Manjaro       | 118       | 3%      |
| Kubuntu       | 113       | 2.87%   |
| Zorin         | 110       | 2.79%   |
| ROSA          | 86        | 2.18%   |
| KDE neon      | 70        | 1.78%   |
| Lubuntu       | 60        | 1.52%   |
| EndeavourOS   | 47        | 1.19%   |
| openSUSE      | 45        | 1.14%   |
| Elementary    | 40        | 1.02%   |
| Endless       | 38        | 0.97%   |
| Ubuntu MATE   | 37        | 0.94%   |
| ArcoLinux     | 22        | 0.56%   |
| Gentoo        | 20        | 0.51%   |
| BlackPanther  | 20        | 0.51%   |
| Ubuntu Unity  | 19        | 0.48%   |
| MX            | 19        | 0.48%   |
| LMDE          | 19        | 0.48%   |
| Clear Linux   | 16        | 0.41%   |
| Ubuntu Budgie | 15        | 0.38%   |
| Kali          | 15        | 0.38%   |
| SteamOS       | 11        | 0.28%   |
| Peppermint    | 11        | 0.28%   |
| Garuda Linux  | 11        | 0.28%   |
| Parrot        | 7         | 0.18%   |
| LinuxFX       | 7         | 0.18%   |
| Nobara        | 6         | 0.15%   |
| Chrome OS     | 5         | 0.13%   |
| Xero          | 4         | 0.1%    |
| Slackware     | 4         | 0.1%    |
| Linux Lite    | 4         | 0.1%    |
| CentOS        | 4         | 0.1%    |
| BunsenLabs    | 4         | 0.1%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 101       | 2.21%   |
| 5.15.0-52-generic        | 96        | 2.1%    |
| 5.16.7-desktop-1omv4003  | 94        | 2.06%   |
| 5.4.0-42-generic         | 68        | 1.49%   |
| 5.15.0-56-generic        | 63        | 1.38%   |
| 5.15.0-58-generic        | 43        | 0.94%   |
| 5.4.0-26-generic         | 41        | 0.9%    |
| 5.15.0-46-generic        | 41        | 0.9%    |
| 5.3.0-46-generic         | 40        | 0.88%   |
| 5.4.0-52-generic         | 36        | 0.79%   |
| 5.4.0-29-generic         | 36        | 0.79%   |
| 5.15.0-47-generic        | 35        | 0.77%   |
| 5.4.0-58-generic         | 33        | 0.72%   |
| 5.15.0-43-generic        | 33        | 0.72%   |
| 5.3.0-40-generic         | 32        | 0.7%    |
| 5.3.0-42-generic         | 31        | 0.68%   |
| 6.1.1-desktop-1omv2290   | 30        | 0.66%   |
| 5.4.0-48-generic         | 30        | 0.66%   |
| 6.0.2-arch1-1            | 28        | 0.61%   |
| 5.15.0-53-generic        | 27        | 0.59%   |
| 5.15.0-41-generic        | 27        | 0.59%   |
| 5.13.0-28-generic        | 27        | 0.59%   |
| 5.0.0-37-generic         | 27        | 0.59%   |
| 5.15.0-48-generic        | 25        | 0.55%   |
| 5.10.0-19-amd64          | 24        | 0.53%   |
| 5.3.0-51-generic         | 23        | 0.5%    |
| 5.19.0-23-generic        | 23        | 0.5%    |
| 5.19.0-21-generic        | 23        | 0.5%    |
| 5.15.0-60-generic        | 23        | 0.5%    |
| 5.4.0-54-generic         | 22        | 0.48%   |
| 5.4.0-47-generic         | 22        | 0.48%   |
| 5.4.0-28-generic         | 22        | 0.48%   |
| 5.15.0-50-generic        | 21        | 0.46%   |
| 4.18.0-15-generic        | 21        | 0.46%   |
| 5.4.0-33-generic         | 20        | 0.44%   |
| 5.10.0-21-amd64          | 20        | 0.44%   |
| 5.4.0-37-generic         | 19        | 0.42%   |
| 5.19.16-200.fc36.x86_64  | 19        | 0.42%   |
| 5.19.0-76051900-generic  | 19        | 0.42%   |
| 5.19.0-35-generic        | 19        | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 683       | 15.96%  |
| 5.15.0  | 470       | 10.98%  |
| 4.15.0  | 237       | 5.54%   |
| 5.3.0   | 223       | 5.21%   |
| 5.8.0   | 201       | 4.7%    |
| 5.13.0  | 195       | 4.56%   |
| 5.11.0  | 167       | 3.9%    |
| 5.19.0  | 153       | 3.57%   |
| 5.10.0  | 129       | 3.01%   |
| 5.0.0   | 113       | 2.64%   |
| 5.10.14 | 101       | 2.36%   |
| 5.16.7  | 96        | 2.24%   |
| 4.18.0  | 87        | 2.03%   |
| 6.0.2   | 53        | 1.24%   |
| 4.19.0  | 45        | 1.05%   |
| 6.1.1   | 37        | 0.86%   |
| 5.19.16 | 29        | 0.68%   |
| 6.0.0   | 26        | 0.61%   |
| 6.0.12  | 22        | 0.51%   |
| 5.17.5  | 20        | 0.47%   |
| 4.18.16 | 19        | 0.44%   |
| 6.0.6   | 18        | 0.42%   |
| 4.9.60  | 18        | 0.42%   |
| 4.9.20  | 17        | 0.4%    |
| 6.2.6   | 16        | 0.37%   |
| 6.0.7   | 16        | 0.37%   |
| 4.4.0   | 16        | 0.37%   |
| 5.17.1  | 14        | 0.33%   |
| 6.0.5   | 13        | 0.3%    |
| 6.0.9   | 12        | 0.28%   |
| 5.18.0  | 12        | 0.28%   |
| 6.1.8   | 11        | 0.26%   |
| 6.0.10  | 11        | 0.26%   |
| 5.19.12 | 11        | 0.26%   |
| 5.14.0  | 11        | 0.26%   |
| 6.0.11  | 10        | 0.23%   |
| 5.19.6  | 10        | 0.23%   |
| 5.17.0  | 10        | 0.23%   |
| 5.16.11 | 10        | 0.23%   |
| 5.14.14 | 10        | 0.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 729       | 17.23%  |
| 5.15    | 558       | 13.19%  |
| 5.10    | 286       | 6.76%   |
| 5.19    | 257       | 6.07%   |
| 5.3     | 248       | 5.86%   |
| 5.8     | 241       | 5.7%    |
| 4.15    | 238       | 5.63%   |
| 5.13    | 216       | 5.11%   |
| 5.11    | 204       | 4.82%   |
| 6.0     | 203       | 4.8%    |
| 5.16    | 147       | 3.47%   |
| 6.1     | 116       | 2.74%   |
| 5.0     | 116       | 2.74%   |
| 4.18    | 109       | 2.58%   |
| 5.17    | 65        | 1.54%   |
| 4.9     | 61        | 1.44%   |
| 4.19    | 58        | 1.37%   |
| 5.14    | 55        | 1.3%    |
| 5.18    | 54        | 1.28%   |
| 5.9     | 46        | 1.09%   |
| 6.2     | 38        | 0.9%    |
| 5.12    | 37        | 0.87%   |
| 5.6     | 34        | 0.8%    |
| 5.5     | 34        | 0.8%    |
| 5.7     | 23        | 0.54%   |
| 4.4     | 17        | 0.4%    |
| 5.2     | 9         | 0.21%   |
| 4.13    | 6         | 0.14%   |
| 4.1     | 6         | 0.14%   |
| 5.1     | 4         | 0.09%   |
| 4.12    | 4         | 0.09%   |
| 4.20    | 3         | 0.07%   |
| 4.17    | 3         | 0.07%   |
| 4.16    | 2         | 0.05%   |
| 3.10    | 2         | 0.05%   |
| 4.14    | 1         | 0.02%   |
| 4.10    | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 3589      | 94.55%  |
| i686   | 206       | 5.43%   |
| armv7l | 1         | 0.03%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| GNOME             | 1739      | 43.8%   |
| KDE5              | 731       | 18.41%  |
| Unknown           | 402       | 10.13%  |
| XFCE              | 355       | 8.94%   |
| X-Cinnamon        | 243       | 6.12%   |
| MATE              | 106       | 2.67%   |
| KDE               | 69        | 1.74%   |
| LXQt              | 63        | 1.59%   |
| KDE4              | 50        | 1.26%   |
| Pantheon          | 40        | 1.01%   |
| Cinnamon          | 27        | 0.68%   |
| LXDE              | 26        | 0.65%   |
| Unity             | 21        | 0.53%   |
| Budgie            | 21        | 0.53%   |
| i3                | 15        | 0.38%   |
| GNOME Flashback   | 15        | 0.38%   |
| Deepin            | 6         | 0.15%   |
| sway              | 5         | 0.13%   |
| GNOME Classic     | 5         | 0.13%   |
| bspwm             | 5         | 0.13%   |
| Hyprland          | 4         | 0.1%    |
| DWM               | 4         | 0.1%    |
| xubuntu           | 2         | 0.05%   |
| qtile             | 2         | 0.05%   |
| openbox           | 2         | 0.05%   |
| enlightenment     | 2         | 0.05%   |
| ubuntu:pika:GNOME | 1         | 0.03%   |
| ubuntu            | 1         | 0.03%   |
| Trinity           | 1         | 0.03%   |
| none+i3           | 1         | 0.03%   |
| none+bspwm        | 1         | 0.03%   |
| lightdm-xsession  | 1         | 0.03%   |
| icewm             | 1         | 0.03%   |
| gamescope         | 1         | 0.03%   |
| Cutefish          | 1         | 0.03%   |
| awesome           | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 2977      | 75.94%  |
| Wayland | 699       | 17.83%  |
| Unknown | 207       | 5.28%   |
| Tty     | 37        | 0.94%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1755      | 44.4%   |
| SDDM    | 685       | 17.33%  |
| GDM     | 479       | 12.12%  |
| GDM3    | 475       | 12.02%  |
| LightDM | 393       | 9.94%   |
| TDM     | 95        | 2.4%    |
| KDM     | 51        | 1.29%   |
| XDM     | 6         | 0.15%   |
| SLiM    | 6         | 0.15%   |
| LXDM    | 3         | 0.08%   |
| WDM     | 1         | 0.03%   |
| SLIMSKI | 1         | 0.03%   |
| MDM     | 1         | 0.03%   |
| Ly      | 1         | 0.03%   |
| GREETD  | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang         | Notebooks | Percent |
|--------------|-----------|---------|
| it_IT        | 2403      | 61.5%   |
| en_US        | 849       | 21.73%  |
| Unknown      | 432       | 11.06%  |
| en_GB        | 86        | 2.2%    |
| C            | 66        | 1.69%   |
| de_DE        | 12        | 0.31%   |
| fr_FR        | 9         | 0.23%   |
| es_ES        | 8         | 0.2%    |
| de_IT        | 7         | 0.18%   |
| ru_RU        | 5         | 0.13%   |
| POSIX        | 4         | 0.1%    |
| en_AU        | 3         | 0.08%   |
| it_IT@euro   | 2         | 0.05%   |
| en_US.UTF8   | 2         | 0.05%   |
| en_IE        | 2         | 0.05%   |
| en_AG        | 2         | 0.05%   |
| ro_RO        | 1         | 0.03%   |
| pt_BR        | 1         | 0.03%   |
| pl_PL        | 1         | 0.03%   |
| it_IT.UTF -8 | 1         | 0.03%   |
| it_CH        | 1         | 0.03%   |
| fur_IT       | 1         | 0.03%   |
| fr_BE        | 1         | 0.03%   |
| es_US        | 1         | 0.03%   |
| en_US@euro   | 1         | 0.03%   |
| en_US.utf-8  | 1         | 0.03%   |
| en_IN        | 1         | 0.03%   |
| de_CH        | 1         | 0.03%   |
| de_AT        | 1         | 0.03%   |
| C.UTF8       | 1         | 0.03%   |
| bg_BG        | 1         | 0.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 2055      | 53.17%  |
| BIOS | 1810      | 46.83%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 2996      | 77.26%  |
| Overlay  | 362       | 9.33%   |
| Btrfs    | 332       | 8.56%   |
| Unknown  | 103       | 2.66%   |
| Xfs      | 29        | 0.75%   |
| Zfs      | 25        | 0.64%   |
| Ext2     | 11        | 0.28%   |
| F2fs     | 7         | 0.18%   |
| Ext3     | 5         | 0.13%   |
| Tmpfs    | 4         | 0.1%    |
| XXX4     | 2         | 0.05%   |
| Reiserfs | 1         | 0.03%   |
| Jfs      | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1924      | 49.54%  |
| GPT     | 1564      | 40.27%  |
| MBR     | 396       | 10.2%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3385      | 87.79%  |
| Yes       | 471       | 12.21%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2569      | 66.4%   |
| Yes       | 1300      | 33.6%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 866       | 22.84%  |
| Lenovo              | 616       | 16.24%  |
| ASUSTek Computer    | 602       | 15.88%  |
| Acer                | 429       | 11.31%  |
| Dell                | 390       | 10.28%  |
| Toshiba             | 100       | 2.64%   |
| HUAWEI              | 91        | 2.4%    |
| Apple               | 90        | 2.37%   |
| Sony                | 86        | 2.27%   |
| MSI                 | 73        | 1.93%   |
| Samsung Electronics | 66        | 1.74%   |
| Fujitsu             | 40        | 1.05%   |
| Unknown             | 30        | 0.79%   |
| Packard Bell        | 29        | 0.76%   |
| Mediacom            | 25        | 0.66%   |
| Notebook            | 21        | 0.55%   |
| Chuwi               | 21        | 0.55%   |
| Teclast             | 20        | 0.53%   |
| Timi                | 18        | 0.47%   |
| Fujitsu Siemens     | 18        | 0.47%   |
| Microtech           | 15        | 0.4%    |
| TUXEDO              | 12        | 0.32%   |
| PC Specialist       | 11        | 0.29%   |
| Valve               | 9         | 0.24%   |
| SANTECH             | 8         | 0.21%   |
| TrekStor            | 7         | 0.18%   |
| Jumper              | 7         | 0.18%   |
| eMachines           | 7         | 0.18%   |
| Google              | 6         | 0.16%   |
| Olivetti            | 5         | 0.13%   |
| LG Electronics      | 5         | 0.13%   |
| Alienware           | 5         | 0.13%   |
| YASHI               | 3         | 0.08%   |
| System76            | 3         | 0.08%   |
| SiComputer          | 3         | 0.08%   |
| Razer               | 3         | 0.08%   |
| Intel               | 3         | 0.08%   |
| YJKC                | 2         | 0.05%   |
| TELECOMITALIA       | 2         | 0.05%   |
| Schenker            | 2         | 0.05%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| HP Pavilion dv6                        | 52        | 1.37%   |
| Unknown                                | 44        | 1.16%   |
| HP Notebook                            | 38        | 1%      |
| HP Pavilion 15                         | 26        | 0.69%   |
| HP Pavilion g6                         | 22        | 0.58%   |
| HP 255 G8 Notebook PC                  | 18        | 0.47%   |
| HUAWEI NBLK-WAX9X                      | 17        | 0.45%   |
| HP 15                                  | 15        | 0.4%    |
| Dell XPS 15 7590                       | 13        | 0.34%   |
| Mediacom SmartBook 14 FullHD - SB14UC  | 12        | 0.32%   |
| HP G62                                 | 12        | 0.32%   |
| HP 255 G7 Notebook PC                  | 12        | 0.32%   |
| Apple MacBook4,1                       | 12        | 0.32%   |
| Lenovo IdeaPad 3 15ADA05 81W1          | 11        | 0.29%   |
| HUAWEI KLVL-WXX9                       | 11        | 0.29%   |
| HP Pavilion x2 Detachable              | 11        | 0.29%   |
| HP 255 G6 Notebook PC                  | 11        | 0.29%   |
| HP 250 G6 Notebook PC                  | 11        | 0.29%   |
| HP ENVY 15                             | 10        | 0.26%   |
| Valve Jupiter                          | 9         | 0.24%   |
| Lenovo IdeaPad 330S-15IKB 81F5         | 9         | 0.24%   |
| HP Laptop 15s-eq2xxx                   | 9         | 0.24%   |
| HP Compaq 6730s                        | 9         | 0.24%   |
| Dell XPS 15 9570                       | 9         | 0.24%   |
| Dell XPS 15 9560                       | 9         | 0.24%   |
| Lenovo V145-15AST 81MT                 | 8         | 0.21%   |
| HP ProBook 450 G5                      | 8         | 0.21%   |
| HP Pavilion dv7                        | 8         | 0.21%   |
| HP 250 G3                              | 8         | 0.21%   |
| Dell Latitude E7440                    | 8         | 0.21%   |
| Dell Inspiron 5570                     | 8         | 0.21%   |
| ASUS VivoBook_ASUSLaptop X580GD_N580GD | 8         | 0.21%   |
| ASUS N53SV                             | 8         | 0.21%   |
| ASUS K53SC                             | 8         | 0.21%   |
| Acer Aspire E5-575G                    | 8         | 0.21%   |
| Acer Aspire E5-573G                    | 8         | 0.21%   |
| Acer Aspire E5-571G                    | 8         | 0.21%   |
| Acer Aspire E1-522                     | 8         | 0.21%   |
| Acer Aspire A515-51G                   | 8         | 0.21%   |
| Acer Aspire A515-45                    | 8         | 0.21%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 297       | 7.83%   |
| Acer Aspire           | 282       | 7.44%   |
| HP Pavilion           | 233       | 6.14%   |
| Lenovo IdeaPad        | 154       | 4.06%   |
| Dell Latitude         | 146       | 3.85%   |
| HP EliteBook          | 100       | 2.64%   |
| ASUS VivoBook         | 91        | 2.4%    |
| Toshiba Satellite     | 87        | 2.29%   |
| Dell XPS              | 87        | 2.29%   |
| HP Laptop             | 83        | 2.19%   |
| HP ProBook            | 81        | 2.14%   |
| Dell Inspiron         | 76        | 2%      |
| HP Compaq             | 64        | 1.69%   |
| HP 255                | 56        | 1.48%   |
| HP 250                | 49        | 1.29%   |
| Unknown               | 44        | 1.16%   |
| HP Notebook           | 38        | 1%      |
| Fujitsu LIFEBOOK      | 38        | 1%      |
| Acer TravelMate       | 33        | 0.87%   |
| Acer Swift            | 33        | 0.87%   |
| Acer Extensa          | 33        | 0.87%   |
| Dell Precision        | 31        | 0.82%   |
| Dell Vostro           | 30        | 0.79%   |
| Lenovo ThinkBook      | 29        | 0.76%   |
| Packard Bell EasyNote | 22        | 0.58%   |
| HP ENVY               | 21        | 0.55%   |
| ASUS ROG              | 18        | 0.47%   |
| Apple MacBookPro11    | 18        | 0.47%   |
| HUAWEI NBLK-WAX9X     | 17        | 0.45%   |
| HP 15                 | 15        | 0.4%    |
| Mediacom SmartBook    | 14        | 0.37%   |
| HP ZBook              | 14        | 0.37%   |
| HP Presario           | 14        | 0.37%   |
| ASUS Zenbook          | 14        | 0.37%   |
| Acer Nitro            | 13        | 0.34%   |
| MSI Modern            | 12        | 0.32%   |
| HP OMEN               | 12        | 0.32%   |
| HP G62                | 12        | 0.32%   |
| Apple MacBook4        | 12        | 0.32%   |
| MSI Prestige          | 11        | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 332       | 8.76%   |
| 2019    | 329       | 8.68%   |
| 2018    | 302       | 7.96%   |
| 2021    | 286       | 7.54%   |
| 2013    | 267       | 7.04%   |
| 2017    | 257       | 6.78%   |
| 2016    | 226       | 5.96%   |
| 2010    | 225       | 5.93%   |
| 2011    | 223       | 5.88%   |
| 2008    | 223       | 5.88%   |
| 2015    | 222       | 5.85%   |
| 2012    | 222       | 5.85%   |
| 2014    | 210       | 5.54%   |
| 2009    | 175       | 4.61%   |
| 2007    | 115       | 3.03%   |
| 2022    | 84        | 2.22%   |
| 2006    | 61        | 1.61%   |
| 2005    | 23        | 0.61%   |
| Unknown | 5         | 0.13%   |
| 2004    | 3         | 0.08%   |
| 2023    | 1         | 0.03%   |
| 2003    | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 3792      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 3447      | 89.93%  |
| Enabled  | 386       | 10.07%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3778      | 99.63%  |
| Yes  | 14        | 0.37%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1060      | 27.6%   |
| 3.01-4.0    | 960       | 25%     |
| 16.01-24.0  | 623       | 16.22%  |
| 8.01-16.0   | 594       | 15.47%  |
| 1.01-2.0    | 254       | 6.61%   |
| 32.01-64.0  | 172       | 4.48%   |
| 2.01-3.0    | 85        | 2.21%   |
| 0.51-1.0    | 44        | 1.15%   |
| 24.01-32.0  | 26        | 0.68%   |
| 64.01-256.0 | 19        | 0.49%   |
| 0.01-0.5    | 3         | 0.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1615      | 38.42%  |
| 2.01-3.0   | 1021      | 24.29%  |
| 4.01-8.0   | 525       | 12.49%  |
| 3.01-4.0   | 499       | 11.87%  |
| 0.51-1.0   | 357       | 8.49%   |
| 8.01-16.0  | 130       | 3.09%   |
| 0.01-0.5   | 45        | 1.07%   |
| 16.01-24.0 | 8         | 0.19%   |
| 24.01-32.0 | 2         | 0.05%   |
| Unknown    | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2894      | 75.01%  |
| 2      | 836       | 21.67%  |
| 3      | 85        | 2.2%    |
| 0      | 28        | 0.73%   |
| 4      | 11        | 0.29%   |
| 6      | 2         | 0.05%   |
| 5      | 2         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2160      | 56.69%  |
| Yes       | 1650      | 43.31%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3035      | 79.66%  |
| No        | 775       | 20.34%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3716      | 97.89%  |
| No        | 80        | 2.11%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2779      | 72.33%  |
| No        | 1063      | 27.67%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Italy   | 3792      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| Milan               | 580       | 13.53%  |
| Rome                | 439       | 10.24%  |
| Turin               | 142       | 3.31%   |
| Naples              | 82        | 1.91%   |
| Bologna             | 76        | 1.77%   |
| Florence            | 74        | 1.73%   |
| Rho                 | 68        | 1.59%   |
| Genoa               | 59        | 1.38%   |
| Padova              | 52        | 1.21%   |
| Palermo             | 48        | 1.12%   |
| Verona              | 45        | 1.05%   |
| Bari                | 39        | 0.91%   |
| Catania             | 34        | 0.79%   |
| Brescia             | 34        | 0.79%   |
| Milano              | 32        | 0.75%   |
| Trieste             | 28        | 0.65%   |
| Bergamo             | 28        | 0.65%   |
| Parma               | 26        | 0.61%   |
| Venice              | 22        | 0.51%   |
| Pisa                | 22        | 0.51%   |
| Bolzano             | 22        | 0.51%   |
| Trento              | 20        | 0.47%   |
| Modena              | 20        | 0.47%   |
| Casalecchio di Reno | 20        | 0.47%   |
| Sesto San Giovanni  | 18        | 0.42%   |
| Perugia             | 17        | 0.4%    |
| Cagliari            | 17        | 0.4%    |
| Seregno             | 16        | 0.37%   |
| Reggio Emilia       | 15        | 0.35%   |
| Monza               | 15        | 0.35%   |
| Udine               | 14        | 0.33%   |
| Salerno             | 14        | 0.33%   |
| Taranto             | 13        | 0.3%    |
| Pescara             | 13        | 0.3%    |
| Reggio Calabria     | 12        | 0.28%   |
| Novara              | 12        | 0.28%   |
| Mestre              | 12        | 0.28%   |
| Legnano             | 12        | 0.28%   |
| Forlì              | 12        | 0.28%   |
| Vicenza             | 11        | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 832       | 1096   | 17.9%   |
| WDC                         | 460       | 574    | 9.9%    |
| Seagate                     | 439       | 532    | 9.44%   |
| Toshiba                     | 322       | 408    | 6.93%   |
| SanDisk                     | 290       | 386    | 6.24%   |
| Unknown                     | 285       | 385    | 6.13%   |
| Kingston                    | 276       | 318    | 5.94%   |
| Crucial                     | 265       | 307    | 5.7%    |
| Hitachi                     | 210       | 255    | 4.52%   |
| SK hynix                    | 178       | 215    | 3.83%   |
| HGST                        | 168       | 217    | 3.61%   |
| Micron Technology           | 122       | 148    | 2.62%   |
| Intel                       | 108       | 135    | 2.32%   |
| KIOXIA                      | 54        | 65     | 1.16%   |
| Fujitsu                     | 44        | 52     | 0.95%   |
| Phison                      | 37        | 45     | 0.8%    |
| China                       | 36        | 41     | 0.77%   |
| Apple                       | 31        | 33     | 0.67%   |
| LITEON                      | 25        | 32     | 0.54%   |
| SPCC                        | 24        | 30     | 0.52%   |
| Transcend                   | 23        | 29     | 0.49%   |
| Intenso                     | 22        | 22     | 0.47%   |
| JMicron Technology          | 20        | 23     | 0.43%   |
| Netac                       | 17        | 18     | 0.37%   |
| A-DATA Technology           | 16        | 19     | 0.34%   |
| Teclast                     | 15        | 20     | 0.32%   |
| Phison Electronics          | 15        | 17     | 0.32%   |
| Unknown                     | 15        | 20     | 0.32%   |
| KingDian                    | 14        | 19     | 0.3%    |
| Silicon Motion              | 11        | 14     | 0.24%   |
| SABRENT                     | 11        | 11     | 0.24%   |
| PNY                         | 11        | 13     | 0.24%   |
| Drevo                       | 11        | 12     | 0.24%   |
| Kingston Technology Company | 10        | 12     | 0.22%   |
| Patriot                     | 9         | 12     | 0.19%   |
| LITEONIT                    | 9         | 19     | 0.19%   |
| Lenovo                      | 8         | 8      | 0.17%   |
| Corsair                     | 8         | 9      | 0.17%   |
| TCSUNBOW                    | 7         | 9      | 0.15%   |
| SSSTC                       | 7         | 7      | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                     | 77        | 1.6%    |
| Crucial CT500MX500SSD1 500GB                        | 65        | 1.35%   |
| Unknown MMC Card  32GB                              | 64        | 1.33%   |
| Toshiba MQ01ABF050 500GB                            | 59        | 1.23%   |
| Samsung SSD 860 EVO 500GB                           | 58        | 1.2%    |
| Seagate ST500LT012-1DG142 500GB                     | 48        | 1%      |
| Samsung SSD 850 EVO 250GB                           | 48        | 1%      |
| HGST HTS545050A7E680 500GB                          | 48        | 1%      |
| Seagate ST1000LM035-1RK172 1TB                      | 44        | 0.91%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 43        | 0.89%   |
| HGST HTS721010A9E630 1TB                            | 43        | 0.89%   |
| Samsung SSD 850 EVO 500GB                           | 41        | 0.85%   |
| Unknown MMC Card  64GB                              | 34        | 0.71%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 34        | 0.71%   |
| Crucial CT240BX500SSD1 240GB                        | 34        | 0.71%   |
| Kingston SA400S37480G 480GB SSD                     | 33        | 0.69%   |
| Samsung NVMe SSD Drive 512GB                        | 32        | 0.66%   |
| Toshiba MQ01ABD100 1TB                              | 30        | 0.62%   |
| SanDisk NVMe SSD Drive 512GB                        | 28        | 0.58%   |
| Seagate ST9500325AS 500GB                           | 27        | 0.56%   |
| Toshiba MQ04ABF100 1TB                              | 26        | 0.54%   |
| SanDisk SSD PLUS 240GB                              | 25        | 0.52%   |
| Samsung SSD 860 EVO 250GB                           | 24        | 0.5%    |
| Crucial CT480BX500SSD1 480GB                        | 24        | 0.5%    |
| Samsung SSD 860 EVO 1TB                             | 22        | 0.46%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB              | 22        | 0.46%   |
| SanDisk NVMe SSD Drive 256GB                        | 20        | 0.42%   |
| Hitachi HTS545050A7E380 500GB                       | 20        | 0.42%   |
| Crucial CT1000MX500SSD1 1TB                         | 20        | 0.42%   |
| SK hynix NVMe SSD Drive 512GB                       | 19        | 0.39%   |
| Kingston SV300S37A120G 120GB SSD                    | 19        | 0.39%   |
| Kingston SA400S37120G 120GB SSD                     | 19        | 0.39%   |
| WDC WD5000LPVX-22V0TT0 500GB                        | 18        | 0.37%   |
| Seagate M3 Portable 2TB                             | 18        | 0.37%   |
| Samsung SSD 840 EVO 250GB                           | 18        | 0.37%   |
| Unknown MMC Card  16GB                              | 17        | 0.35%   |
| Unknown MMC Card  128GB                             | 17        | 0.35%   |
| Samsung MZVLQ512HALU-000H1 512GB                    | 17        | 0.35%   |
| HGST HTS541010A9E680 1TB                            | 17        | 0.35%   |
| Micron 1100_MTFDDAV512TBN 512GB SSD                 | 16        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 419       | 502    | 28.45%  |
| WDC                 | 323       | 405    | 21.93%  |
| Toshiba             | 225       | 268    | 15.27%  |
| Hitachi             | 210       | 255    | 14.26%  |
| HGST                | 168       | 217    | 11.41%  |
| Fujitsu             | 44        | 52     | 2.99%   |
| Samsung Electronics | 40        | 51     | 2.72%   |
| Unknown             | 17        | 18     | 1.15%   |
| SABRENT             | 11        | 11     | 0.75%   |
| ASMT                | 5         | 6      | 0.34%   |
| IBM/Hitachi         | 2         | 3      | 0.14%   |
| HGST HTS            | 2         | 2      | 0.14%   |
| USB3.0              | 1         | 1      | 0.07%   |
| StoreJet            | 1         | 1      | 0.07%   |
| Intenso             | 1         | 1      | 0.07%   |
| Generic-            | 1         | 1      | 0.07%   |
| DAS                 | 1         | 4      | 0.07%   |
| ASMedia             | 1         | 1      | 0.07%   |
| Apple               | 1         | 1      | 0.07%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 428       | 551    | 26.5%   |
| Crucial             | 247       | 289    | 15.29%  |
| Kingston            | 212       | 241    | 13.13%  |
| SanDisk             | 165       | 208    | 10.22%  |
| Micron Technology   | 53        | 68     | 3.28%   |
| WDC                 | 47        | 59     | 2.91%   |
| SK hynix            | 45        | 50     | 2.79%   |
| China               | 35        | 40     | 2.17%   |
| Toshiba             | 26        | 41     | 1.61%   |
| Transcend           | 23        | 29     | 1.42%   |
| Apple               | 23        | 24     | 1.42%   |
| Intel               | 22        | 27     | 1.36%   |
| LITEON              | 21        | 24     | 1.3%    |
| SPCC                | 20        | 25     | 1.24%   |
| Intenso             | 18        | 18     | 1.11%   |
| Netac               | 16        | 17     | 0.99%   |
| Teclast             | 15        | 20     | 0.93%   |
| KingDian            | 14        | 19     | 0.87%   |
| A-DATA Technology   | 12        | 13     | 0.74%   |
| PNY                 | 10        | 11     | 0.62%   |
| JMicron Technology  | 10        | 11     | 0.62%   |
| Drevo               | 10        | 11     | 0.62%   |
| Patriot             | 9         | 12     | 0.56%   |
| LITEONIT            | 9         | 19     | 0.56%   |
| Unknown             | 9         | 14     | 0.56%   |
| Corsair             | 8         | 9      | 0.5%    |
| Microtech           | 7         | 17     | 0.43%   |
| GOODRAM             | 7         | 8      | 0.43%   |
| Dogfish             | 7         | 8      | 0.43%   |
| Verbatim            | 5         | 10     | 0.31%   |
| TCSUNBOW            | 5         | 5      | 0.31%   |
| FORESEE             | 5         | 5      | 0.31%   |
| KingSpec            | 4         | 5      | 0.25%   |
| Hewlett-Packard     | 4         | 5      | 0.25%   |
| BAITITON            | 4         | 6      | 0.25%   |
| TO Exter            | 3         | 3      | 0.19%   |
| Team                | 3         | 3      | 0.19%   |
| Phison              | 3         | 4      | 0.19%   |
| OCZ                 | 3         | 3      | 0.19%   |
| Leven               | 3         | 3      | 0.19%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 1522      | 1982   | 34.29%  |
| HDD     | 1427      | 1800   | 32.15%  |
| NVMe    | 1134      | 1550   | 25.55%  |
| MMC     | 284       | 395    | 6.4%    |
| Unknown | 72        | 87     | 1.62%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2663      | 3676   | 62.7%   |
| NVMe | 1131      | 1541   | 26.63%  |
| MMC  | 284       | 395    | 6.69%   |
| SAS  | 169       | 202    | 3.98%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2202      | 2911   | 76.17%  |
| 0.51-1.0   | 624       | 795    | 21.58%  |
| 1.01-2.0   | 58        | 69     | 2.01%   |
| 4.01-10.0  | 4         | 4      | 0.14%   |
| 3.01-4.0   | 2         | 2      | 0.07%   |
| 2.01-3.0   | 1         | 1      | 0.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 1204      | 30.1%   |
| 251-500        | 1034      | 25.85%  |
| 501-1000       | 444       | 11.1%   |
| 1-20           | 399       | 9.98%   |
| 51-100         | 331       | 8.28%   |
| 21-50          | 210       | 5.25%   |
| 1001-2000      | 183       | 4.58%   |
| Unknown        | 86        | 2.15%   |
| 2001-3000      | 57        | 1.43%   |
| More than 3000 | 52        | 1.3%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1812      | 43.57%  |
| 21-50          | 672       | 16.16%  |
| 101-250        | 561       | 13.49%  |
| 51-100         | 512       | 12.31%  |
| 251-500        | 293       | 7.04%   |
| 501-1000       | 148       | 3.56%   |
| Unknown        | 86        | 2.07%   |
| 1001-2000      | 44        | 1.06%   |
| 2001-3000      | 16        | 0.38%   |
| More than 3000 | 15        | 0.36%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| HGST HTS545050A7E680 500GB                     | 14        | 15     | 5.81%   |
| Seagate ST9500325AS 500GB                      | 7         | 7      | 2.9%    |
| Seagate ST1000LM035-1RK172 1TB                 | 6         | 8      | 2.49%   |
| WDC WD3200BEVT-60A23T0 320GB                   | 5         | 5      | 2.07%   |
| Toshiba MQ01ABF050 500GB                       | 5         | 5      | 2.07%   |
| Seagate ST500LT012-1DG142 500GB                | 5         | 5      | 2.07%   |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 5         | 5      | 2.07%   |
| Hitachi HTS725050A9A364 500GB                  | 5         | 5      | 2.07%   |
| Hitachi HTS545050A7E380 500GB                  | 4         | 4      | 1.66%   |
| HGST HTS725050A7E630 500GB                     | 4         | 5      | 1.66%   |
| Toshiba MQ01ABD100 1TB                         | 3         | 4      | 1.24%   |
| Toshiba MK5065GSX 500GB                        | 3         | 3      | 1.24%   |
| SK hynix HFS512G39TND-N210A 512GB SSD          | 3         | 3      | 1.24%   |
| Seagate ST500LT012-9WS142 500GB                | 3         | 3      | 1.24%   |
| Micron Technology 1100_MTFDDAV512TBN 512GB SSD | 3         | 3      | 1.24%   |
| Hitachi HTS547550A9E384 500GB                  | 3         | 3      | 1.24%   |
| HGST HTS721010A9E630 1TB                       | 3         | 3      | 1.24%   |
| HGST HTS541075A9E680 752GB                     | 3         | 6      | 1.24%   |
| WDC WD5000LPCX-24C6HT0 500GB                   | 2         | 2      | 0.83%   |
| WDC WD5000BEVT-22ZAT0 500GB                    | 2         | 2      | 0.83%   |
| WDC WD10JPVX-22JC3T0 1TB                       | 2         | 3      | 0.83%   |
| SK hynix HFS128G39TND-N210A 128GB SSD          | 2         | 2      | 0.83%   |
| Seagate ST9320423AS 320GB                      | 2         | 2      | 0.83%   |
| Seagate ST9320325AS 320GB                      | 2         | 2      | 0.83%   |
| Seagate ST9250315AS 250GB                      | 2         | 2      | 0.83%   |
| Seagate ST9160310AS 160GB                      | 2         | 3      | 0.83%   |
| Seagate ST500LM021-1KJ152 500GB                | 2         | 2      | 0.83%   |
| Seagate ST500LM012 HN-M500MBB 500GB            | 2         | 2      | 0.83%   |
| Seagate ST320LT020-9YG142 320GB                | 2         | 2      | 0.83%   |
| Seagate ST1000LM014-1EJ164 1TB                 | 2         | 2      | 0.83%   |
| Kingston SA400S37240G 240GB SSD                | 2         | 2      | 0.83%   |
| Hitachi HTS547575A9E384 752GB                  | 2         | 2      | 0.83%   |
| Hitachi HTS543232A7A384 320GB                  | 2         | 3      | 0.83%   |
| Hitachi HTS543225L9A300 250GB                  | 2         | 2      | 0.83%   |
| Hitachi HTS542516K9SA00 160GB                  | 2         | 2      | 0.83%   |
| HGST HTS541010A9E680 1TB                       | 2         | 2      | 0.83%   |
| Crucial CT525MX300SSD1 528GB                   | 2         | 2      | 0.83%   |
| Yangtze Memory Technologies YMTC PC005 256GB   | 1         | 1      | 0.41%   |
| WINTEC 240GB SATA3 SF2281 SSD                  | 1         | 1      | 0.41%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD               | 1         | 1      | 0.41%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 51        | 54     | 21.16%  |
| Hitachi                     | 39        | 40     | 16.18%  |
| Toshiba                     | 30        | 31     | 12.45%  |
| WDC                         | 28        | 33     | 11.62%  |
| HGST                        | 28        | 33     | 11.62%  |
| SK hynix                    | 9         | 10     | 3.73%   |
| Samsung Electronics         | 9         | 9      | 3.73%   |
| Crucial                     | 8         | 8      | 3.32%   |
| Micron Technology           | 7         | 7      | 2.9%    |
| Kingston                    | 5         | 5      | 2.07%   |
| Intel                       | 4         | 6      | 1.66%   |
| Fujitsu                     | 4         | 4      | 1.66%   |
| SanDisk                     | 3         | 3      | 1.24%   |
| Drevo                       | 2         | 2      | 0.83%   |
| Yangtze Memory Technologies | 1         | 1      | 0.41%   |
| WINTEC                      | 1         | 1      | 0.41%   |
| WDC WDS2                    | 1         | 1      | 0.41%   |
| Unknown                     | 1         | 1      | 0.41%   |
| Transcend                   | 1         | 2      | 0.41%   |
| Teclast                     | 1         | 1      | 0.41%   |
| TCSUNBOW                    | 1         | 1      | 0.41%   |
| SSSTC                       | 1         | 1      | 0.41%   |
| NGFF                        | 1         | 1      | 0.41%   |
| LITEON                      | 1         | 1      | 0.41%   |
| KingSpec                    | 1         | 1      | 0.41%   |
| KingDian                    | 1         | 1      | 0.41%   |
| BAITITON                    | 1         | 3      | 0.41%   |
| A-DATA Technology           | 1         | 1      | 0.41%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 51        | 54     | 28.18%  |
| Hitachi             | 39        | 40     | 21.55%  |
| Toshiba             | 28        | 29     | 15.47%  |
| HGST                | 28        | 33     | 15.47%  |
| WDC                 | 27        | 32     | 14.92%  |
| Fujitsu             | 4         | 4      | 2.21%   |
| Samsung Electronics | 3         | 3      | 1.66%   |
| Unknown             | 1         | 1      | 0.55%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 180       | 196    | 75%     |
| SSD  | 54        | 57     | 22.5%   |
| NVMe | 6         | 9      | 2.5%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-26A0RT0 500GB                     | 1         | 1      | 11.11%  |
| WDC WD5000BEVT-22A0RT0 500GB                     | 1         | 1      | 11.11%  |
| WDC WD10JPVX-60JC3T0 1TB                         | 1         | 1      | 11.11%  |
| WDC PC SN520 SDAPNUW-256G-1102 256GB             | 1         | 1      | 11.11%  |
| Toshiba MK3265GSX 320GB                          | 1         | 1      | 11.11%  |
| Seagate ST9500420AS 500GB                        | 1         | 3      | 11.11%  |
| Seagate ST2000LX001-1RG174 2TB                   | 1         | 1      | 11.11%  |
| Samsung Electronics MZNTY128HDHP-00000 128GB SSD | 1         | 1      | 11.11%  |
| Hitachi HTS545050A7E380 500GB                    | 1         | 1      | 11.11%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 4      | 44.44%  |
| Seagate             | 2         | 4      | 22.22%  |
| Toshiba             | 1         | 1      | 11.11%  |
| Samsung Electronics | 1         | 1      | 11.11%  |
| Hitachi             | 1         | 1      | 11.11%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2249      | 3451   | 55.85%  |
| Works    | 1529      | 2090   | 37.97%  |
| Malfunc  | 240       | 262    | 5.96%   |
| Failed   | 9         | 11     | 0.22%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2690      | 61.88%  |
| AMD                              | 435       | 10.01%  |
| Samsung Electronics              | 401       | 9.22%   |
| SanDisk                          | 191       | 4.39%   |
| SK hynix                         | 123       | 2.83%   |
| Kingston Technology Company      | 73        | 1.68%   |
| Toshiba America Info Systems     | 71        | 1.63%   |
| Micron Technology                | 71        | 1.63%   |
| KIOXIA                           | 59        | 1.36%   |
| Phison Electronics               | 50        | 1.15%   |
| Nvidia                           | 46        | 1.06%   |
| Silicon Integrated Systems [SiS] | 24        | 0.55%   |
| Micron/Crucial Technology        | 23        | 0.53%   |
| Silicon Motion                   | 12        | 0.28%   |
| Union Memory (Shenzhen)          | 11        | 0.25%   |
| Solid State Storage Technology   | 11        | 0.25%   |
| VIA Technologies                 | 7         | 0.16%   |
| Lite-On Technology               | 7         | 0.16%   |
| Lenovo                           | 7         | 0.16%   |
| Apple                            | 7         | 0.16%   |
| ADATA Technology                 | 7         | 0.16%   |
| Yangtze Memory Technologies      | 3         | 0.07%   |
| Silicon Image                    | 3         | 0.07%   |
| Seagate Technology               | 3         | 0.07%   |
| ASMedia Technology               | 3         | 0.07%   |
| Shenzhen Longsys Electronics     | 2         | 0.05%   |
| MAXIO Technology (Hangzhou)      | 2         | 0.05%   |
| JMicron Technology               | 2         | 0.05%   |
| Realtek Semiconductor            | 1         | 0.02%   |
| O2 Micro                         | 1         | 0.02%   |
| Marvell Technology Group         | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 354       | 7.53%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 321       | 6.83%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 252       | 5.36%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 224       | 4.76%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 205       | 4.36%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 203       | 4.32%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 182       | 3.87%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 153       | 3.25%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 119       | 2.53%   |
| Samsung NVMe SSD Controller 980                                                  | 110       | 2.34%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 107       | 2.28%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 104       | 2.21%   |
| Intel Volume Management Device NVMe RAID Controller                              | 102       | 2.17%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 102       | 2.17%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 92        | 1.96%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 85        | 1.81%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 77        | 1.64%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 73        | 1.55%   |
| Micron NVMe Storage Controller                                                   | 70        | 1.49%   |
| Intel Comet Lake SATA AHCI Controller                                            | 56        | 1.19%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 53        | 1.13%   |
| Intel SSD 660P Series                                                            | 51        | 1.08%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 51        | 1.08%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 47        | 1%      |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 47        | 1%      |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 44        | 0.94%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 44        | 0.94%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 44        | 0.94%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 40        | 0.85%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 39        | 0.83%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 38        | 0.81%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 38        | 0.81%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 38        | 0.81%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 37        | 0.79%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 35        | 0.74%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 35        | 0.74%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 34        | 0.72%   |
| Intel Tiger Lake-LP SATA Controller                                              | 33        | 0.7%    |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 32        | 0.68%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 29        | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 2683      | 59.19%  |
| NVMe | 1139      | 25.13%  |
| IDE  | 377       | 8.32%   |
| RAID | 334       | 7.37%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 3138      | 82.75%  |
| AMD          | 650       | 17.14%  |
| CentaurHauls | 2         | 0.05%   |
| ARM          | 1         | 0.03%   |
| Unknown      | 1         | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 83        | 2.19%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 64        | 1.69%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 64        | 1.69%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 58        | 1.53%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 52        | 1.37%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 50        | 1.32%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 48        | 1.27%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 46        | 1.21%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 44        | 1.16%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 44        | 1.16%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 43        | 1.13%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 41        | 1.08%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 40        | 1.05%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 39        | 1.03%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 37        | 0.98%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 35        | 0.92%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 34        | 0.9%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 33        | 0.87%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 33        | 0.87%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 33        | 0.87%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 30        | 0.79%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 27        | 0.71%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 27        | 0.71%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 27        | 0.71%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 27        | 0.71%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 26        | 0.69%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 26        | 0.69%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 25        | 0.66%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 23        | 0.61%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 23        | 0.61%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 23        | 0.61%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 23        | 0.61%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 23        | 0.61%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 22        | 0.58%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 22        | 0.58%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 22        | 0.58%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 22        | 0.58%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 22        | 0.58%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 21        | 0.55%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 21        | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 953       | 25.13%  |
| Intel Core i5           | 732       | 19.3%   |
| Intel Core i3           | 270       | 7.12%   |
| Intel Core 2 Duo        | 269       | 7.09%   |
| Other                   | 259       | 6.83%   |
| Intel Celeron           | 233       | 6.14%   |
| Intel Atom              | 161       | 4.24%   |
| AMD Ryzen 5             | 132       | 3.48%   |
| AMD Ryzen 7             | 130       | 3.43%   |
| Intel Pentium           | 50        | 1.32%   |
| AMD E1                  | 45        | 1.19%   |
| Intel Pentium Dual-Core | 41        | 1.08%   |
| Intel Pentium Dual      | 36        | 0.95%   |
| Intel Genuine           | 35        | 0.92%   |
| AMD A4                  | 32        | 0.84%   |
| Intel Core 2            | 31        | 0.82%   |
| AMD A8                  | 30        | 0.79%   |
| AMD A10                 | 29        | 0.76%   |
| AMD A6                  | 27        | 0.71%   |
| AMD Ryzen 3             | 24        | 0.63%   |
| AMD E2                  | 22        | 0.58%   |
| AMD Ryzen 9             | 20        | 0.53%   |
| Intel Core i9           | 19        | 0.5%    |
| Intel Pentium M         | 16        | 0.42%   |
| AMD Turion 64 X2 Mobile | 15        | 0.4%    |
| Intel Pentium Silver    | 14        | 0.37%   |
| AMD Ryzen 7 PRO         | 14        | 0.37%   |
| Intel Celeron M         | 13        | 0.34%   |
| AMD Sempron             | 12        | 0.32%   |
| AMD Ryzen 5 PRO         | 11        | 0.29%   |
| AMD Mobile Sempron      | 9         | 0.24%   |
| AMD E                   | 9         | 0.24%   |
| Intel Core m3           | 8         | 0.21%   |
| Intel Celeron Dual-Core | 8         | 0.21%   |
| AMD Athlon II           | 7         | 0.18%   |
| Intel Core M            | 6         | 0.16%   |
| AMD A12                 | 6         | 0.16%   |
| AMD Turion 64 Mobile    | 4         | 0.11%   |
| AMD Athlon X2           | 4         | 0.11%   |
| AMD Athlon              | 4         | 0.11%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 1936      | 51.01%  |
| 4       | 1259      | 33.18%  |
| 6       | 200       | 5.27%   |
| 8       | 183       | 4.82%   |
| 1       | 165       | 4.35%   |
| 14      | 28        | 0.74%   |
| 10      | 14        | 0.37%   |
| 12      | 8         | 0.21%   |
| 5       | 1         | 0.03%   |
| Unknown | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 3792      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 2632      | 69.3%   |
| 1       | 1164      | 30.65%  |
| 4       | 1         | 0.03%   |
| Unknown | 1         | 0.03%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3670      | 96.66%  |
| 32-bit         | 98        | 2.58%   |
| Unknown        | 29        | 0.76%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 772       | 19.68%  |
| 0x306a9    | 207       | 5.28%   |
| 0x206a7    | 202       | 5.15%   |
| 0x40651    | 140       | 3.57%   |
| 0x806ea    | 138       | 3.52%   |
| 0x1067a    | 138       | 3.52%   |
| 0x806ec    | 129       | 3.29%   |
| 0x806c1    | 122       | 3.11%   |
| 0x406e3    | 119       | 3.03%   |
| 0x806e9    | 102       | 2.6%    |
| 0x6fd      | 95        | 2.42%   |
| 0x20655    | 90        | 2.29%   |
| 0x906ea    | 86        | 2.19%   |
| 0x306c3    | 86        | 2.19%   |
| 0x306d4    | 81        | 2.07%   |
| 0x10676    | 70        | 1.78%   |
| 0x08108109 | 64        | 1.63%   |
| 0x706e5    | 56        | 1.43%   |
| 0x406c3    | 51        | 1.3%    |
| 0x806eb    | 49        | 1.25%   |
| 0x30678    | 47        | 1.2%    |
| 0x906e9    | 46        | 1.17%   |
| 0x20652    | 44        | 1.12%   |
| 0xa0652    | 42        | 1.07%   |
| 0x08608103 | 42        | 1.07%   |
| 0x06006705 | 42        | 1.07%   |
| 0x406c4    | 39        | 0.99%   |
| 0x106ca    | 39        | 0.99%   |
| 0x706a8    | 38        | 0.97%   |
| 0x0a50000c | 38        | 0.97%   |
| 0x706a1    | 36        | 0.92%   |
| 0x506e3    | 32        | 0.82%   |
| 0x506c9    | 32        | 0.82%   |
| 0x08600106 | 29        | 0.74%   |
| 0x07030105 | 29        | 0.74%   |
| 0x906a3    | 26        | 0.66%   |
| 0x106c2    | 26        | 0.66%   |
| 0x08108102 | 26        | 0.66%   |
| 0x08600104 | 24        | 0.61%   |
| 0x6e8      | 23        | 0.59%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 675       | 17.79%  |
| Haswell          | 293       | 7.72%   |
| IvyBridge        | 254       | 6.69%   |
| Penryn           | 243       | 6.4%    |
| SandyBridge      | 238       | 6.27%   |
| Skylake          | 191       | 5.03%   |
| Core             | 183       | 4.82%   |
| Silvermont       | 165       | 4.35%   |
| TigerLake        | 156       | 4.11%   |
| Westmere         | 155       | 4.08%   |
| Unknown          | 113       | 2.98%   |
| Zen+             | 105       | 2.77%   |
| Broadwell        | 99        | 2.61%   |
| Excavator        | 89        | 2.35%   |
| Goldmont plus    | 88        | 2.32%   |
| IceLake          | 81        | 2.13%   |
| Bonnell          | 80        | 2.11%   |
| Zen 2            | 75        | 1.98%   |
| CometLake        | 59        | 1.55%   |
| Zen 3            | 58        | 1.53%   |
| P6               | 57        | 1.5%    |
| Puma             | 41        | 1.08%   |
| Jaguar           | 39        | 1.03%   |
| Goldmont         | 39        | 1.03%   |
| K8 Hammer        | 38        | 1%      |
| Alderlake Hybrid | 35        | 0.92%   |
| Bobcat           | 28        | 0.74%   |
| Zen              | 22        | 0.58%   |
| K10              | 21        | 0.55%   |
| Nehalem          | 19        | 0.5%    |
| K8 & K10 hybrid  | 16        | 0.42%   |
| K10 Llano        | 14        | 0.37%   |
| Steamroller      | 11        | 0.29%   |
| Piledriver       | 9         | 0.24%   |
| Tremont          | 3         | 0.08%   |
| NetBurst         | 3         | 0.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2756      | 56.9%   |
| Nvidia                           | 1118      | 23.08%  |
| AMD                              | 950       | 19.61%  |
| Silicon Integrated Systems [SiS] | 14        | 0.29%   |
| VIA Technologies                 | 5         | 0.1%    |
| S3 Graphics                      | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 238       | 4.69%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 209       | 4.12%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 170       | 3.35%   |
| Intel UHD Graphics 620                                                                   | 165       | 3.25%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 147       | 2.9%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 137       | 2.7%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 133       | 2.62%   |
| Intel HD Graphics 620                                                                    | 116       | 2.29%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 111       | 2.19%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 106       | 2.09%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 105       | 2.07%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 104       | 2.05%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 103       | 2.03%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 101       | 1.99%   |
| Intel Core Processor Integrated Graphics Controller                                      | 91        | 1.79%   |
| Intel HD Graphics 5500                                                                   | 85        | 1.68%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 74        | 1.46%   |
| AMD Renoir                                                                               | 73        | 1.44%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 72        | 1.42%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 72        | 1.42%   |
| AMD Lucienne                                                                             | 66        | 1.3%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 64        | 1.26%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 62        | 1.22%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 60        | 1.18%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 58        | 1.14%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 55        | 1.08%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 52        | 1.03%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 51        | 1.01%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 48        | 0.95%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 48        | 0.95%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 42        | 0.83%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 42        | 0.83%   |
| Nvidia GP108M [GeForce MX150]                                                            | 41        | 0.81%   |
| Intel HD Graphics 630                                                                    | 41        | 0.81%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 41        | 0.81%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 39        | 0.77%   |
| Intel HD Graphics 530                                                                    | 38        | 0.75%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 36        | 0.71%   |
| Nvidia GM108M [GeForce MX130]                                                            | 34        | 0.67%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 34        | 0.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 1747      | 45.99%  |
| Intel + Nvidia  | 833       | 21.93%  |
| 1 x AMD         | 646       | 17%     |
| 1 x Nvidia      | 232       | 6.11%   |
| Intel + AMD     | 168       | 4.42%   |
| 2 x AMD         | 88        | 2.32%   |
| AMD + Nvidia    | 51        | 1.34%   |
| 1 x SiS         | 14        | 0.37%   |
| Other           | 5         | 0.13%   |
| 2 x Intel       | 5         | 0.13%   |
| 1 x VIA         | 5         | 0.13%   |
| 2 x Nvidia      | 4         | 0.11%   |
| 1 x S3 Graphics | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 3234      | 84.28%  |
| Proprietary | 502       | 13.08%  |
| Unknown     | 101       | 2.63%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2341      | 60.2%   |
| 0.01-0.5   | 544       | 13.99%  |
| 1.01-2.0   | 518       | 13.32%  |
| 0.51-1.0   | 260       | 6.69%   |
| 3.01-4.0   | 162       | 4.17%   |
| 5.01-6.0   | 36        | 0.93%   |
| 7.01-8.0   | 18        | 0.46%   |
| 2.01-3.0   | 9         | 0.23%   |
| 8.01-16.0  | 1         | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 786       | 19.08%  |
| Chimei Innolux          | 602       | 14.61%  |
| LG Display              | 549       | 13.33%  |
| BOE                     | 528       | 12.82%  |
| Samsung Electronics     | 478       | 11.6%   |
| Chi Mei Optoelectronics | 128       | 3.11%   |
| Sharp                   | 103       | 2.5%    |
| Apple                   | 88        | 2.14%   |
| Goldstar                | 75        | 1.82%   |
| Philips                 | 67        | 1.63%   |
| Hewlett-Packard         | 65        | 1.58%   |
| LG Philips              | 60        | 1.46%   |
| PANDA                   | 55        | 1.33%   |
| Lenovo                  | 51        | 1.24%   |
| Ancor Communications    | 47        | 1.14%   |
| Dell                    | 45        | 1.09%   |
| Acer                    | 35        | 0.85%   |
| HannStar                | 33        | 0.8%    |
| InfoVision              | 31        | 0.75%   |
| BenQ                    | 29        | 0.7%    |
| Sony                    | 25        | 0.61%   |
| AOC                     | 22        | 0.53%   |
| CPT                     | 21        | 0.51%   |
| CSO                     | 19        | 0.46%   |
| Toshiba                 | 14        | 0.34%   |
| Quanta Display          | 13        | 0.32%   |
| LGD                     | 13        | 0.32%   |
| ASUSTek Computer        | 9         | 0.22%   |
| Seiko/Epson             | 8         | 0.19%   |
| MSI                     | 8         | 0.19%   |
| TMX                     | 7         | 0.17%   |
| Valve                   | 6         | 0.15%   |
| InnoLux Display         | 6         | 0.15%   |
| Vestel Elektronik       | 5         | 0.12%   |
| Eizo                    | 5         | 0.12%   |
| Nvidia                  | 4         | 0.1%    |
| Iiyama                  | 4         | 0.1%    |
| Unknown                 | 3         | 0.07%   |
| Tianma XM               | 3         | 0.07%   |
| Panasonic               | 3         | 0.07%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 62        | 1.49%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 34        | 0.82%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 32        | 0.77%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 31        | 0.75%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 29        | 0.7%    |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 29        | 0.7%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 29        | 0.7%    |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch          | 28        | 0.67%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 28        | 0.67%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 26        | 0.63%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 25        | 0.6%    |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 24        | 0.58%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 22        | 0.53%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 22        | 0.53%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 21        | 0.5%    |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 20        | 0.48%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 20        | 0.48%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 18        | 0.43%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 18        | 0.43%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 18        | 0.43%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 17        | 0.41%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 17        | 0.41%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 16        | 0.38%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 16        | 0.38%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 15        | 0.36%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 15        | 0.36%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch              | 14        | 0.34%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch     | 13        | 0.31%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 13        | 0.31%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 13        | 0.31%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 13        | 0.31%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 13        | 0.31%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 13        | 0.31%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 12        | 0.29%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch     | 12        | 0.29%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 12        | 0.29%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch          | 12        | 0.29%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 12        | 0.29%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch             | 11        | 0.26%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 11        | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1530      | 39.09%  |
| 1366x768 (WXGA)    | 1329      | 33.96%  |
| 1280x800 (WXGA)    | 275       | 7.03%   |
| 1600x900 (HD+)     | 135       | 3.45%   |
| 3840x2160 (4K)     | 125       | 3.19%   |
| 2560x1440 (QHD)    | 65        | 1.66%   |
| 1440x900 (WXGA+)   | 64        | 1.64%   |
| 1920x1200 (WUXGA)  | 58        | 1.48%   |
| 1024x600           | 58        | 1.48%   |
| 1680x1050 (WSXGA+) | 34        | 0.87%   |
| 2560x1600          | 30        | 0.77%   |
| 2160x1440          | 30        | 0.77%   |
| 2880x1800          | 23        | 0.59%   |
| 1280x1024 (SXGA)   | 23        | 0.59%   |
| 3840x2400          | 14        | 0.36%   |
| 1360x768           | 14        | 0.36%   |
| 2560x1080          | 13        | 0.33%   |
| 800x1280           | 7         | 0.18%   |
| 3440x1440          | 7         | 0.18%   |
| 3200x1800 (QHD+)   | 7         | 0.18%   |
| 3000x2000          | 7         | 0.18%   |
| 1024x768 (XGA)     | 7         | 0.18%   |
| 3072x1920          | 5         | 0.13%   |
| 2520x1680          | 4         | 0.1%    |
| 1920x540           | 4         | 0.1%    |
| 1920x1280          | 4         | 0.1%    |
| Unknown            | 4         | 0.1%    |
| 3840x1080          | 3         | 0.08%   |
| 2240x1400          | 3         | 0.08%   |
| 1600x1200          | 3         | 0.08%   |
| 1400x1050          | 3         | 0.08%   |
| 3840x1600          | 2         | 0.05%   |
| 3456x2160          | 2         | 0.05%   |
| 2880x1920          | 2         | 0.05%   |
| 2880x1620          | 2         | 0.05%   |
| 2288x1287          | 2         | 0.05%   |
| 1680x945           | 2         | 0.05%   |
| 1280x960           | 2         | 0.05%   |
| 1280x720 (HD)      | 2         | 0.05%   |
| 3840x1200          | 1         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 2108      | 51.21%  |
| 13      | 504       | 12.24%  |
| 14      | 356       | 8.65%   |
| 17      | 192       | 4.66%   |
| 24      | 124       | 3.01%   |
| 27      | 113       | 2.75%   |
| 12      | 106       | 2.58%   |
| 23      | 98        | 2.38%   |
| 21      | 77        | 1.87%   |
| 10      | 65        | 1.58%   |
| 11      | 63        | 1.53%   |
| Unknown | 61        | 1.48%   |
| 16      | 42        | 1.02%   |
| 19      | 26        | 0.63%   |
| 18      | 26        | 0.63%   |
| 22      | 17        | 0.41%   |
| 34      | 14        | 0.34%   |
| 31      | 14        | 0.34%   |
| 40      | 13        | 0.32%   |
| 20      | 13        | 0.32%   |
| 84      | 11        | 0.27%   |
| 54      | 9         | 0.22%   |
| 32      | 7         | 0.17%   |
| 25      | 7         | 0.17%   |
| 8       | 6         | 0.15%   |
| 7       | 6         | 0.15%   |
| 72      | 5         | 0.12%   |
| 65      | 4         | 0.1%    |
| 52      | 3         | 0.07%   |
| 48      | 3         | 0.07%   |
| 35      | 3         | 0.07%   |
| 26      | 3         | 0.07%   |
| 142     | 2         | 0.05%   |
| 58      | 2         | 0.05%   |
| 47      | 2         | 0.05%   |
| 46      | 2         | 0.05%   |
| 37      | 2         | 0.05%   |
| 49      | 1         | 0.02%   |
| 42      | 1         | 0.02%   |
| 39      | 1         | 0.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 2686      | 65.66%  |
| 201-300        | 507       | 12.39%  |
| 501-600        | 316       | 7.72%   |
| 351-400        | 250       | 6.11%   |
| 401-500        | 144       | 3.52%   |
| Unknown        | 61        | 1.49%   |
| 601-700        | 29        | 0.71%   |
| 1001-1500      | 25        | 0.61%   |
| 701-800        | 22        | 0.54%   |
| 801-900        | 19        | 0.46%   |
| 1501-2000      | 16        | 0.39%   |
| 101-200        | 7         | 0.17%   |
| 1-100          | 6         | 0.15%   |
| More than 2000 | 2         | 0.05%   |
| 901-1000       | 1         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 3042      | 81.88%  |
| 16/10   | 495       | 13.32%  |
| 3/2     | 54        | 1.45%   |
| Unknown | 46        | 1.24%   |
| 5/4     | 24        | 0.65%   |
| 21/9    | 21        | 0.57%   |
| 4/3     | 17        | 0.46%   |
| 0.67    | 6         | 0.16%   |
| 32/9    | 4         | 0.11%   |
| 6/5     | 2         | 0.05%   |
| 1.00    | 2         | 0.05%   |
| 2.21    | 1         | 0.03%   |
| 0.62    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 2109      | 51.36%  |
| 81-90          | 653       | 15.9%   |
| 201-250        | 266       | 6.48%   |
| 71-80          | 205       | 4.99%   |
| 121-130        | 151       | 3.68%   |
| 301-350        | 116       | 2.83%   |
| 61-70          | 102       | 2.48%   |
| 41-50          | 66        | 1.61%   |
| 51-60          | 63        | 1.53%   |
| Unknown        | 61        | 1.49%   |
| 151-200        | 52        | 1.27%   |
| 251-300        | 41        | 1%      |
| 351-500        | 38        | 0.93%   |
| More than 1000 | 36        | 0.88%   |
| 141-150        | 36        | 0.88%   |
| 111-120        | 31        | 0.75%   |
| 131-140        | 29        | 0.71%   |
| 501-1000       | 25        | 0.61%   |
| 91-100         | 14        | 0.34%   |
| 1-40           | 12        | 0.29%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1474      | 36.47%  |
| 101-120       | 1330      | 32.9%   |
| 51-100        | 798       | 19.74%  |
| 161-240       | 257       | 6.36%   |
| More than 240 | 94        | 2.33%   |
| Unknown       | 61        | 1.51%   |
| 1-50          | 28        | 0.69%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 3191      | 82.16%  |
| 2     | 536       | 13.8%   |
| 0     | 113       | 2.91%   |
| 3     | 41        | 1.06%   |
| 4     | 3         | 0.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2040      | 33.52%  |
| Intel                             | 1793      | 29.46%  |
| Qualcomm Atheros                  | 958       | 15.74%  |
| Broadcom                          | 456       | 7.49%   |
| Marvell Technology Group          | 118       | 1.94%   |
| Broadcom Limited                  | 101       | 1.66%   |
| Ralink                            | 68        | 1.12%   |
| MediaTek                          | 67        | 1.1%    |
| TP-Link                           | 51        | 0.84%   |
| Ralink Technology                 | 42        | 0.69%   |
| Nvidia                            | 31        | 0.51%   |
| ASIX Electronics                  | 30        | 0.49%   |
| Dell                              | 27        | 0.44%   |
| Huawei Technologies               | 23        | 0.38%   |
| Samsung Electronics               | 18        | 0.3%    |
| Ericsson Business Mobile Networks | 18        | 0.3%    |
| Silicon Integrated Systems [SiS]  | 17        | 0.28%   |
| Xiaomi                            | 16        | 0.26%   |
| Sierra Wireless                   | 16        | 0.26%   |
| JMicron Technology                | 16        | 0.26%   |
| Attansic Technology               | 16        | 0.26%   |
| Qualcomm Atheros Communications   | 13        | 0.21%   |
| Qualcomm                          | 11        | 0.18%   |
| Hewlett-Packard                   | 11        | 0.18%   |
| Sitecom Europe                    | 8         | 0.13%   |
| Lenovo                            | 8         | 0.13%   |
| Apple                             | 7         | 0.12%   |
| ZTE WCDMA Technologies MSM        | 6         | 0.1%    |
| OnePlus Technology (Shenzhen)     | 6         | 0.1%    |
| DisplayLink                       | 6         | 0.1%    |
| D-Link System                     | 6         | 0.1%    |
| AMD                               | 6         | 0.1%    |
| T & A Mobile Phones               | 5         | 0.08%   |
| NetGear                           | 5         | 0.08%   |
| ICS Advent                        | 5         | 0.08%   |
| Fibocom                           | 5         | 0.08%   |
| Belkin Components                 | 5         | 0.08%   |
| D-Link                            | 4         | 0.07%   |
| ZyDAS                             | 3         | 0.05%   |
| VIA Technologies                  | 3         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 1226      | 17.13%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 388       | 5.42%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 171       | 2.39%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 168       | 2.35%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 168       | 2.35%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 147       | 2.05%   |
| Intel Wireless 8265 / 8275                                              | 146       | 2.04%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 134       | 1.87%   |
| Intel Wi-Fi 6 AX200                                                     | 132       | 1.84%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 123       | 1.72%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 123       | 1.72%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 114       | 1.59%   |
| Intel Wireless 7265                                                     | 109       | 1.52%   |
| Intel Wi-Fi 6 AX201                                                     | 107       | 1.49%   |
| Intel Wireless 3165                                                     | 106       | 1.48%   |
| Intel Wireless 7260                                                     | 90        | 1.26%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 82        | 1.15%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 79        | 1.1%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 79        | 1.1%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 76        | 1.06%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 74        | 1.03%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 69        | 0.96%   |
| Intel Wireless 8260                                                     | 65        | 0.91%   |
| Intel WiFi Link 5100                                                    | 65        | 0.91%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 64        | 0.89%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 63        | 0.88%   |
| Broadcom BCM43142 802.11b/g/n                                           | 59        | 0.82%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 54        | 0.75%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 50        | 0.7%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 43        | 0.6%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 42        | 0.59%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 41        | 0.57%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 40        | 0.56%   |
| Intel Ethernet Connection (4) I219-LM                                   | 38        | 0.53%   |
| Intel Ethernet Connection I218-LM                                       | 36        | 0.5%    |
| Intel Centrino Advanced-N 6200                                          | 35        | 0.49%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 35        | 0.49%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 35        | 0.49%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 34        | 0.47%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 34        | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1724      | 44.11%  |
| Qualcomm Atheros                      | 871       | 22.29%  |
| Realtek Semiconductor                 | 601       | 15.38%  |
| Broadcom                              | 328       | 8.39%   |
| Broadcom Limited                      | 69        | 1.77%   |
| Ralink                                | 68        | 1.74%   |
| MediaTek                              | 65        | 1.66%   |
| TP-Link                               | 42        | 1.07%   |
| Ralink Technology                     | 42        | 1.07%   |
| Sierra Wireless                       | 16        | 0.41%   |
| Dell                                  | 16        | 0.41%   |
| Qualcomm Atheros Communications       | 13        | 0.33%   |
| Sitecom Europe                        | 7         | 0.18%   |
| D-Link System                         | 6         | 0.15%   |
| Qualcomm                              | 5         | 0.13%   |
| NetGear                               | 5         | 0.13%   |
| FIBOCOM                               | 5         | 0.13%   |
| Belkin Components                     | 5         | 0.13%   |
| ZyDAS                                 | 3         | 0.08%   |
| D-Link                                | 3         | 0.08%   |
| ASUSTek Computer                      | 3         | 0.08%   |
| U.S. Robotics                         | 2         | 0.05%   |
| Qcom                                  | 2         | 0.05%   |
| Microsoft                             | 2         | 0.05%   |
| Hewlett-Packard                       | 2         | 0.05%   |
| ZyXEL Communications                  | 1         | 0.03%   |
| AVM                                   | 1         | 0.03%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 171       | 4.36%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 168       | 4.28%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 168       | 4.28%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 147       | 3.75%   |
| Intel Wireless 8265 / 8275                                              | 146       | 3.72%   |
| Intel Wi-Fi 6 AX200                                                     | 132       | 3.36%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 123       | 3.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 123       | 3.13%   |
| Intel Wireless 7265                                                     | 109       | 2.78%   |
| Intel Wi-Fi 6 AX201                                                     | 107       | 2.73%   |
| Intel Wireless 3165                                                     | 106       | 2.7%    |
| Intel Wireless 7260                                                     | 90        | 2.29%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 82        | 2.09%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 79        | 2.01%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 79        | 2.01%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 76        | 1.94%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 74        | 1.89%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 69        | 1.76%   |
| Intel Wireless 8260                                                     | 65        | 1.66%   |
| Intel WiFi Link 5100                                                    | 65        | 1.66%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 64        | 1.63%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 63        | 1.61%   |
| Broadcom BCM43142 802.11b/g/n                                           | 59        | 1.5%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 54        | 1.38%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 50        | 1.27%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 43        | 1.1%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 42        | 1.07%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 41        | 1.04%   |
| Intel Centrino Advanced-N 6200                                          | 35        | 0.89%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 35        | 0.89%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 34        | 0.87%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 34        | 0.87%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 33        | 0.84%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 32        | 0.82%   |
| Intel Centrino Wireless-N 2230                                          | 31        | 0.79%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 29        | 0.74%   |
| Intel Wireless-AC 9260                                                  | 29        | 0.74%   |
| Intel Wireless 3160                                                     | 29        | 0.74%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 29        | 0.74%   |
| Intel Centrino Ultimate-N 6300                                          | 29        | 0.74%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1815      | 57.91%  |
| Intel                            | 546       | 17.42%  |
| Qualcomm Atheros                 | 196       | 6.25%   |
| Broadcom                         | 183       | 5.84%   |
| Marvell Technology Group         | 118       | 3.77%   |
| Broadcom Limited                 | 33        | 1.05%   |
| Nvidia                           | 30        | 0.96%   |
| ASIX Electronics                 | 30        | 0.96%   |
| Huawei Technologies              | 18        | 0.57%   |
| Samsung Electronics              | 17        | 0.54%   |
| Xiaomi                           | 16        | 0.51%   |
| JMicron Technology               | 16        | 0.51%   |
| Attansic Technology              | 16        | 0.51%   |
| Silicon Integrated Systems [SiS] | 15        | 0.48%   |
| TP-Link                          | 9         | 0.29%   |
| Lenovo                           | 8         | 0.26%   |
| Apple                            | 7         | 0.22%   |
| ZTE WCDMA Technologies MSM       | 6         | 0.19%   |
| Qualcomm                         | 6         | 0.19%   |
| OnePlus Technology (Shenzhen)    | 6         | 0.19%   |
| DisplayLink                      | 6         | 0.19%   |
| ICS Advent                       | 5         | 0.16%   |
| T & A Mobile Phones              | 4         | 0.13%   |
| VIA Technologies                 | 3         | 0.1%    |
| OPPO Electronics                 | 3         | 0.1%    |
| Motorola PCS                     | 3         | 0.1%    |
| HMD Global                       | 3         | 0.1%    |
| Spreadtrum Communications        | 2         | 0.06%   |
| MediaTek                         | 2         | 0.06%   |
| LG Electronics                   | 2         | 0.06%   |
| Hewlett-Packard                  | 2         | 0.06%   |
| Google                           | 2         | 0.06%   |
| Sitecom Europe                   | 1         | 0.03%   |
| MosChip Semiconductor            | 1         | 0.03%   |
| Microchip Technology             | 1         | 0.03%   |
| D-Link                           | 1         | 0.03%   |
| ADMtek                           | 1         | 0.03%   |
| Accton Technology                | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 1226      | 38.82%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 388       | 12.29%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 134       | 4.24%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 114       | 3.61%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 40        | 1.27%   |
| Intel Ethernet Connection (4) I219-LM                                          | 38        | 1.2%    |
| Intel Ethernet Connection I218-LM                                              | 36        | 1.14%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 35        | 1.11%   |
| Intel 82577LM Gigabit Network Connection                                       | 33        | 1.04%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 32        | 1.01%   |
| Intel 82567LM Gigabit Network Connection                                       | 30        | 0.95%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 30        | 0.95%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 28        | 0.89%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 28        | 0.89%   |
| Intel Ethernet Connection I219-LM                                              | 27        | 0.85%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 26        | 0.82%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 23        | 0.73%   |
| Intel Ethernet Connection I217-LM                                              | 23        | 0.73%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 21        | 0.66%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 21        | 0.66%   |
| Intel Ethernet Connection (3) I218-LM                                          | 21        | 0.66%   |
| Intel Ethernet Connection I219-V                                               | 19        | 0.6%    |
| Intel Ethernet Connection (4) I219-V                                           | 19        | 0.6%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 18        | 0.57%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 18        | 0.57%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 17        | 0.54%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 17        | 0.54%   |
| Nvidia MCP79 Ethernet                                                          | 16        | 0.51%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 16        | 0.51%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 16        | 0.51%   |
| Attansic AR8152 v2.0 Fast Ethernet                                             | 16        | 0.51%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 15        | 0.47%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 15        | 0.47%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 15        | 0.47%   |
| Intel Ethernet Connection (6) I219-V                                           | 15        | 0.47%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 15        | 0.47%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 15        | 0.47%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 14        | 0.44%   |
| Intel Ethernet Connection (10) I219-V                                          | 14        | 0.44%   |
| Intel 82573L Gigabit Ethernet Controller                                       | 14        | 0.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3716      | 54.52%  |
| Ethernet | 3025      | 44.38%  |
| Modem    | 69        | 1.01%   |
| Unknown  | 6         | 0.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3126      | 79.44%  |
| Ethernet | 806       | 20.48%  |
| Unknown  | 2         | 0.05%   |
| Modem    | 1         | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 2773      | 73.01%  |
| 1     | 918       | 24.17%  |
| 0     | 85        | 2.24%   |
| 3     | 22        | 0.58%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3585      | 93.68%  |
| Yes  | 242       | 6.32%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1255      | 44.73%  |
| Realtek Semiconductor           | 345       | 12.3%   |
| Qualcomm Atheros Communications | 200       | 7.13%   |
| IMC Networks                    | 165       | 5.88%   |
| Lite-On Technology              | 160       | 5.7%    |
| Broadcom                        | 154       | 5.49%   |
| Foxconn / Hon Hai               | 128       | 4.56%   |
| Apple                           | 79        | 2.82%   |
| Hewlett-Packard                 | 61        | 2.17%   |
| Realtek                         | 52        | 1.85%   |
| Dell                            | 39        | 1.39%   |
| Cambridge Silicon Radio         | 38        | 1.35%   |
| Ralink                          | 34        | 1.21%   |
| Toshiba                         | 32        | 1.14%   |
| ASUSTek Computer                | 18        | 0.64%   |
| Alps Electric                   | 14        | 0.5%    |
| Ralink Technology               | 7         | 0.25%   |
| Foxconn International           | 5         | 0.18%   |
| MediaTek                        | 4         | 0.14%   |
| Chicony Electronics             | 4         | 0.14%   |
| Askey Computer                  | 4         | 0.14%   |
| Taiyo Yuden                     | 2         | 0.07%   |
| Integrated System Solution      | 2         | 0.07%   |
| Unknown                         | 1         | 0.04%   |
| Sitecom Europe                  | 1         | 0.04%   |
| Opticis                         | 1         | 0.04%   |
| Conwise Technology              | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 544       | 19.39%  |
| Realtek Bluetooth Radio                                                             | 226       | 8.05%   |
| Intel AX201 Bluetooth                                                               | 213       | 7.59%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 189       | 6.74%   |
| Intel AX200 Bluetooth                                                               | 127       | 4.53%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 91        | 3.24%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 79        | 2.82%   |
| IMC Networks Bluetooth Device                                                       | 71        | 2.53%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 53        | 1.89%   |
| Realtek Bluetooth Radio                                                             | 52        | 1.85%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 48        | 1.71%   |
| Apple Bluetooth Host Controller                                                     | 43        | 1.53%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 42        | 1.5%    |
| Intel Wireless-AC 3168 Bluetooth                                                    | 42        | 1.5%    |
| IMC Networks Bluetooth Radio                                                        | 42        | 1.5%    |
| Foxconn / Hon Hai Bluetooth Device                                                  | 41        | 1.46%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 39        | 1.39%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 38        | 1.35%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 37        | 1.32%   |
| Lite-On Bluetooth Device                                                            | 37        | 1.32%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 36        | 1.28%   |
| Ralink RT3290 Bluetooth                                                             | 34        | 1.21%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 29        | 1.03%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 29        | 1.03%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 28        | 1%      |
| Intel Bluetooth Device                                                              | 28        | 1%      |
| Broadcom BCM2045 Bluetooth                                                          | 24        | 0.86%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 22        | 0.78%   |
| IMC Networks Wireless_Device                                                        | 21        | 0.75%   |
| Intel AX210 Bluetooth                                                               | 19        | 0.68%   |
| Apple Bluetooth HCI                                                                 | 18        | 0.64%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 17        | 0.61%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 17        | 0.61%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 16        | 0.57%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 16        | 0.57%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 16        | 0.57%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 15        | 0.53%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 15        | 0.53%   |
| Realtek RTL8723B Bluetooth                                                          | 14        | 0.5%    |
| Broadcom HP Portable SoftSailing                                                    | 14        | 0.5%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3001      | 67.65%  |
| AMD                              | 767       | 17.29%  |
| Nvidia                           | 432       | 9.74%   |
| C-Media Electronics              | 27        | 0.61%   |
| Silicon Integrated Systems [SiS] | 24        | 0.54%   |
| Logitech                         | 18        | 0.41%   |
| GN Netcom                        | 16        | 0.36%   |
| JMTek                            | 14        | 0.32%   |
| Realtek Semiconductor            | 12        | 0.27%   |
| Generalplus Technology           | 12        | 0.27%   |
| VIA Technologies                 | 7         | 0.16%   |
| Lenovo                           | 7         | 0.16%   |
| Texas Instruments                | 6         | 0.14%   |
| CMX Systems                      | 6         | 0.14%   |
| Plantronics                      | 5         | 0.11%   |
| Hewlett-Packard                  | 5         | 0.11%   |
| Apple                            | 5         | 0.11%   |
| Huawei Technologies              | 4         | 0.09%   |
| Fujitsu                          | 4         | 0.09%   |
| Creative Technology              | 4         | 0.09%   |
| BEHRINGER International          | 4         | 0.09%   |
| Sony                             | 3         | 0.07%   |
| Samson Technologies              | 3         | 0.07%   |
| M-Audio                          | 3         | 0.07%   |
| Syntek                           | 2         | 0.05%   |
| Razer USA                        | 2         | 0.05%   |
| Medeli Electronics               | 2         | 0.05%   |
| Focusrite-Novation               | 2         | 0.05%   |
| Dell                             | 2         | 0.05%   |
| Cambridge Silicon Radio          | 2         | 0.05%   |
| ASUSTek Computer                 | 2         | 0.05%   |
| XMOS                             | 1         | 0.02%   |
| TEAC                             | 1         | 0.02%   |
| SmartlinkTechnology              | 1         | 0.02%   |
| Schiit Audio                     | 1         | 0.02%   |
| RODE Microphones                 | 1         | 0.02%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.02%   |
| Numark                           | 1         | 0.02%   |
| MosArt Semiconductor             | 1         | 0.02%   |
| Microsoft                        | 1         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 437       | 8.12%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 324       | 6.02%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 283       | 5.26%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 218       | 4.05%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 209       | 3.88%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 175       | 3.25%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 174       | 3.23%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 172       | 3.2%    |
| Intel 8 Series HD Audio Controller                                                                | 172       | 3.2%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 156       | 2.9%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 137       | 2.55%   |
| AMD FCH Azalia Controller                                                                         | 128       | 2.38%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 123       | 2.29%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 122       | 2.27%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 119       | 2.21%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 113       | 2.1%    |
| Intel Cannon Lake PCH cAVS                                                                        | 112       | 2.08%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 109       | 2.03%   |
| AMD Kabini HDMI/DP Audio                                                                          | 107       | 1.99%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 103       | 1.91%   |
| Intel Broadwell-U Audio Controller                                                                | 99        | 1.84%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 95        | 1.77%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 88        | 1.64%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 87        | 1.62%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 64        | 1.19%   |
| AMD High Definition Audio Controller                                                              | 62        | 1.15%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 57        | 1.06%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 56        | 1.04%   |
| Intel Comet Lake PCH cAVS                                                                         | 54        | 1%      |
| Intel CM238 HD Audio Controller                                                                   | 53        | 0.99%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 47        | 0.87%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 45        | 0.84%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 43        | 0.8%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 42        | 0.78%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 39        | 0.72%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 38        | 0.71%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 31        | 0.58%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 31        | 0.58%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 30        | 0.56%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 29        | 0.54%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 737       | 29.81%  |
| SK hynix                     | 542       | 21.93%  |
| Micron Technology            | 316       | 12.78%  |
| Unknown                      | 215       | 8.7%    |
| Kingston                     | 212       | 8.58%   |
| Crucial                      | 107       | 4.33%   |
| Ramaxel Technology           | 63        | 2.55%   |
| Elpida                       | 55        | 2.22%   |
| Unknown (ABCD)               | 51        | 2.06%   |
| A-DATA Technology            | 39        | 1.58%   |
| Corsair                      | 32        | 1.29%   |
| Nanya Technology             | 30        | 1.21%   |
| Unknown                      | 11        | 0.44%   |
| Team                         | 9         | 0.36%   |
| Transcend                    | 8         | 0.32%   |
| ASint Technology             | 6         | 0.24%   |
| Toshiba                      | 5         | 0.2%    |
| G.Skill                      | 5         | 0.2%    |
| Qimonda                      | 4         | 0.16%   |
| 48spaces                     | 4         | 0.16%   |
| Timetec                      | 3         | 0.12%   |
| Patriot                      | 2         | 0.08%   |
| Unknown (8A5D)               | 1         | 0.04%   |
| Unknown (8A02)               | 1         | 0.04%   |
| Unknown (7F7F7F7F7F7F6B00)   | 1         | 0.04%   |
| Unknown (0x08A4FFFFFFFFFFFF) | 1         | 0.04%   |
| Unigen                       | 1         | 0.04%   |
| Unifosa                      | 1         | 0.04%   |
| Smart Brazil                 | 1         | 0.04%   |
| SHARETRONIC                  | 1         | 0.04%   |
| Sesame                       | 1         | 0.04%   |
| Neo Forza                    | 1         | 0.04%   |
| Infineon                     | 1         | 0.04%   |
| Goldkey                      | 1         | 0.04%   |
| Essencore Limited            | 1         | 0.04%   |
| ChangXin Memory              | 1         | 0.04%   |
| Avant                        | 1         | 0.04%   |
| Apacer                       | 1         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 47        | 1.78%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 38        | 1.44%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 34        | 1.29%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 33        | 1.25%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 30        | 1.14%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 28        | 1.06%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 27        | 1.03%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 27        | 1.03%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 25        | 0.95%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 25        | 0.95%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 24        | 0.91%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 23        | 0.87%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 20        | 0.76%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 20        | 0.76%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 20        | 0.76%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 20        | 0.76%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 19        | 0.72%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 19        | 0.72%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 19        | 0.72%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 18        | 0.68%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 18        | 0.68%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 17        | 0.65%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 17        | 0.65%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 16        | 0.61%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 16        | 0.61%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 15        | 0.57%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 15        | 0.57%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 14        | 0.53%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 14        | 0.53%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 14        | 0.53%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 14        | 0.53%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 14        | 0.53%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 14        | 0.53%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 13        | 0.49%   |
| Micron RAM 8ATF1G64HZ-2G3B1 8GB SODIMM DDR4 2400MT/s             | 13        | 0.49%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 13        | 0.49%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 13        | 0.49%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 12        | 0.46%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 12        | 0.46%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 12        | 0.46%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 982       | 46.21%  |
| DDR3    | 732       | 34.45%  |
| LPDDR4  | 131       | 6.16%   |
| DDR2    | 117       | 5.51%   |
| LPDDR3  | 61        | 2.87%   |
| SDRAM   | 45        | 2.12%   |
| Unknown | 16        | 0.75%   |
| DDR5    | 15        | 0.71%   |
| DRAM    | 10        | 0.47%   |
| LPDDR5  | 8         | 0.38%   |
| DDR     | 8         | 0.38%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1902      | 88.75%  |
| Row Of Chips | 219       | 10.22%  |
| DIMM         | 10        | 0.47%   |
| Chip         | 10        | 0.47%   |
| Unknown      | 2         | 0.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 847       | 36.86%  |
| 4096  | 754       | 32.81%  |
| 2048  | 315       | 13.71%  |
| 16384 | 274       | 11.92%  |
| 1024  | 64        | 2.79%   |
| 32768 | 28        | 1.22%   |
| 512   | 15        | 0.65%   |
| 256   | 1         | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 470       | 20.48%  |
| 2667    | 468       | 20.39%  |
| 3200    | 365       | 15.9%   |
| 2400    | 203       | 8.85%   |
| 1334    | 129       | 5.62%   |
| 2133    | 114       | 4.97%   |
| 1333    | 83        | 3.62%   |
| Unknown | 74        | 3.22%   |
| 667     | 68        | 2.96%   |
| 4267    | 46        | 2%      |
| 3266    | 38        | 1.66%   |
| 1066    | 35        | 1.53%   |
| 800     | 28        | 1.22%   |
| 1867    | 23        | 1%      |
| 1067    | 23        | 1%      |
| 4199    | 19        | 0.83%   |
| 8400    | 16        | 0.7%    |
| 4800    | 16        | 0.7%    |
| 533     | 14        | 0.61%   |
| 2048    | 12        | 0.52%   |
| 975     | 9         | 0.39%   |
| 6400    | 8         | 0.35%   |
| 4266    | 7         | 0.31%   |
| 2933    | 6         | 0.26%   |
| 3733    | 3         | 0.13%   |
| 3400    | 2         | 0.09%   |
| 1866    | 2         | 0.09%   |
| 1639    | 2         | 0.09%   |
| 1200    | 2         | 0.09%   |
| 400     | 2         | 0.09%   |
| 333     | 2         | 0.09%   |
| 2800    | 1         | 0.04%   |
| 2267    | 1         | 0.04%   |
| 2134    | 1         | 0.04%   |
| 2000    | 1         | 0.04%   |
| 1776    | 1         | 0.04%   |
| 933     | 1         | 0.04%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 21        | 35%     |
| Samsung Electronics | 15        | 25%     |
| Canon               | 10        | 16.67%  |
| Brother Industries  | 5         | 8.33%   |
| Seiko Epson         | 3         | 5%      |
| Pantum              | 2         | 3.33%   |
| Xerox               | 1         | 1.67%   |
| Sagem               | 1         | 1.67%   |
| ICS Advent          | 1         | 1.67%   |
| Apple               | 1         | 1.67%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Samsung ML-216x Series Laser Printer | 2         | 3.28%   |
| Samsung M267x 287x Series            | 2         | 3.28%   |
| Samsung M2070 Series                 | 2         | 3.28%   |
| HP OfficeJet 3830 series             | 2         | 3.28%   |
| HP Officejet 2620 series             | 2         | 3.28%   |
| Xerox B215                           | 1         | 1.64%   |
| Seiko Epson WF-2510 Series           | 1         | 1.64%   |
| Seiko Epson Printer                  | 1         | 1.64%   |
| Seiko Epson L355 Series              | 1         | 1.64%   |
| Samsung SCX-483x 5x3x Series         | 1         | 1.64%   |
| Samsung SCX-4623 Series              | 1         | 1.64%   |
| Samsung SCX-4300 Series              | 1         | 1.64%   |
| Samsung ML-331x Series Laser Printer | 1         | 1.64%   |
| Samsung ML-2010P Mono Laser Printer  | 1         | 1.64%   |
| Samsung ML-1865W Series              | 1         | 1.64%   |
| Samsung ML-1640 Series Laser Printer | 1         | 1.64%   |
| Samsung CLP-325 Color Laser Printer  | 1         | 1.64%   |
| Samsung C3060 Series                 | 1         | 1.64%   |
| Sagem Laser Pro LL                   | 1         | 1.64%   |
| Pantum P2500W series                 | 1         | 1.64%   |
| Pantum M6500W series                 | 1         | 1.64%   |
| ICS Advent Parallel Adapter          | 1         | 1.64%   |
| HP Officejet Pro 6230                | 1         | 1.64%   |
| HP OfficeJet 6950                    | 1         | 1.64%   |
| HP OfficeJet 5600 (USBHUB)           | 1         | 1.64%   |
| HP LaserJet P3005                    | 1         | 1.64%   |
| HP LaserJet P2055 series             | 1         | 1.64%   |
| HP LaserJet P1102                    | 1         | 1.64%   |
| HP LaserJet 1200                     | 1         | 1.64%   |
| HP LaserJet 1020                     | 1         | 1.64%   |
| HP LaserJet 1015                     | 1         | 1.64%   |
| HP LaserJet 1010                     | 1         | 1.64%   |
| HP ENVY 5000 series                  | 1         | 1.64%   |
| HP ENVY 4520 series                  | 1         | 1.64%   |
| HP DeskJet 940c                      | 1         | 1.64%   |
| HP DeskJet 840c                      | 1         | 1.64%   |
| HP Deskjet 3520 series               | 1         | 1.64%   |
| HP DeskJet 2700 series               | 1         | 1.64%   |
| HP Deskjet 2050 J510                 | 1         | 1.64%   |
| HP Deskjet 1510                      | 1         | 1.64%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 6         | 46.15%  |
| Seiko Epson     | 5         | 38.46%  |
| Hewlett-Packard | 2         | 15.38%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]        | 2         | 14.29%  |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1         | 7.14%   |
| Seiko Epson ES-D400 [GT-S80]                             | 1         | 7.14%   |
| Seiko Epson CC-570L [Stylus CX3100/CX3200]               | 1         | 7.14%   |
| HP Scanjet G2710                                         | 1         | 7.14%   |
| HP ScanJet 3570c                                         | 1         | 7.14%   |
| Canon CanoScan LIDE 25                                   | 1         | 7.14%   |
| Canon CanoScan LiDE 220                                  | 1         | 7.14%   |
| Canon CanoScan LiDE 120                                  | 1         | 7.14%   |
| Canon CanoScan LiDE 110                                  | 1         | 7.14%   |
| Canon CanoScan LiDE 100                                  | 1         | 7.14%   |
| Canon CanoScan 4400F                                     | 1         | 7.14%   |
| Canon CanoScan 1220U                                     | 1         | 7.14%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 903       | 26.71%  |
| IMC Networks                           | 420       | 12.42%  |
| Realtek Semiconductor                  | 253       | 7.48%   |
| Microdia                               | 240       | 7.1%    |
| Acer                                   | 230       | 6.8%    |
| Quanta                                 | 175       | 5.18%   |
| Suyin                                  | 172       | 5.09%   |
| Cheng Uei Precision Industry (Foxlink) | 145       | 4.29%   |
| Sunplus Innovation Technology          | 139       | 4.11%   |
| Alcor Micro                            | 90        | 2.66%   |
| Lite-On Technology                     | 82        | 2.43%   |
| Syntek                                 | 81        | 2.4%    |
| Apple                                  | 73        | 2.16%   |
| Luxvisions Innotech Limited            | 62        | 1.83%   |
| Ricoh                                  | 43        | 1.27%   |
| Silicon Motion                         | 41        | 1.21%   |
| Bison Electronics                      | 40        | 1.18%   |
| Logitech                               | 24        | 0.71%   |
| Z-Star Microelectronics                | 18        | 0.53%   |
| ALi                                    | 16        | 0.47%   |
| Primax Electronics                     | 15        | 0.44%   |
| Samsung Electronics                    | 11        | 0.33%   |
| USB Camera                             | 10        | 0.3%    |
| Lenovo                                 | 8         | 0.24%   |
| Sonix Technology                       | 7         | 0.21%   |
| Importek                               | 7         | 0.21%   |
| Sunplus Technology                     | 6         | 0.18%   |
| DigiTech                               | 6         | 0.18%   |
| ARC International                      | 6         | 0.18%   |
| SunplusIT                              | 5         | 0.15%   |
| Genesys Logic                          | 5         | 0.15%   |
| GEMBIRD                                | 4         | 0.12%   |
| Microsoft                              | 3         | 0.09%   |
| Generalplus Technology                 | 3         | 0.09%   |
| WaveRider Communications               | 2         | 0.06%   |
| USB Camera CS                          | 2         | 0.06%   |
| Pixart Imaging                         | 2         | 0.06%   |
| OmniVision Technologies                | 2         | 0.06%   |
| Nebraska Furniture Mart                | 2         | 0.06%   |
| Mustek Systems                         | 2         | 0.06%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 141       | 4.15%   |
| Microdia Integrated_Webcam_HD                           | 100       | 2.94%   |
| Chicony HD WebCam                                       | 86        | 2.53%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 75        | 2.21%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 70        | 2.06%   |
| IMC Networks Integrated Camera                          | 67        | 1.97%   |
| Realtek Integrated_Webcam_HD                            | 54        | 1.59%   |
| Chicony USB2.0 VGA UVC WebCam                           | 43        | 1.27%   |
| Realtek USB Camera                                      | 42        | 1.24%   |
| Alcor Micro USB 2.0 Camera                              | 42        | 1.24%   |
| Acer Integrated Camera                                  | 42        | 1.24%   |
| Syntek Integrated Camera                                | 41        | 1.21%   |
| Chicony USB2.0 HD UVC WebCam                            | 41        | 1.21%   |
| Chicony HP TrueVision HD                                | 38        | 1.12%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera     | 37        | 1.09%   |
| Sunplus Integrated_Webcam_HD                            | 36        | 1.06%   |
| Quanta HP TrueVision HD Camera                          | 34        | 1%      |
| Acer Lenovo EasyCamera                                  | 32        | 0.94%   |
| IMC Networks HD Camera                                  | 30        | 0.88%   |
| Chicony FJ Camera                                       | 30        | 0.88%   |
| Chicony HP Webcam                                       | 28        | 0.82%   |
| Chicony HP TrueVision HD Camera                         | 28        | 0.82%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                         | 27        | 0.8%    |
| Sunplus HD WebCam                                       | 26        | 0.77%   |
| Quanta HP Webcam                                        | 26        | 0.77%   |
| Chicony HP HD Camera                                    | 26        | 0.77%   |
| Acer HD Webcam                                          | 26        | 0.77%   |
| Realtek USB2.0 VGA UVC WebCam                           | 24        | 0.71%   |
| Suyin HP Truevision HD                                  | 23        | 0.68%   |
| Chicony HP Wide Vision HD Camera                        | 23        | 0.68%   |
| Alcor Micro Asus Integrated Webcam                      | 23        | 0.68%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 22        | 0.65%   |
| Lite-On HP HD Camera                                    | 22        | 0.65%   |
| Acer SunplusIT Integrated Camera                        | 22        | 0.65%   |
| Quanta HD User Facing                                   | 21        | 0.62%   |
| Microdia Integrated Webcam                              | 21        | 0.62%   |
| IMC Networks UVC VGA Webcam                             | 21        | 0.62%   |
| Chicony USB2.0 Camera                                   | 21        | 0.62%   |
| Cheng Uei Precision Industry (Foxlink) Webcam           | 21        | 0.62%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 21        | 0.62%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 193       | 30.16%  |
| Synaptics                          | 141       | 22.03%  |
| Shenzhen Goodix Technology         | 111       | 17.34%  |
| Elan Microelectronics              | 75        | 11.72%  |
| Upek                               | 37        | 5.78%   |
| AuthenTec                          | 36        | 5.63%   |
| LighTuning Technology              | 35        | 5.47%   |
| STMicroelectronics                 | 5         | 0.78%   |
| Focal-systems.Corp                 | 4         | 0.63%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.31%   |
| Microsoft                          | 1         | 0.16%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 85        | 13.28%  |
| Elan ELAN:ARM-M4                                                           | 50        | 7.81%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 42        | 6.56%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 38        | 5.94%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 32        | 5%      |
| Elan ELAN:Fingerprint                                                      | 25        | 3.91%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 24        | 3.75%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 23        | 3.59%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 20        | 3.13%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 19        | 2.97%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 18        | 2.81%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 18        | 2.81%   |
| Validity Sensors Fingerprint scanner                                       | 16        | 2.5%    |
| Shenzhen Goodix Fingerprint Reader                                         | 15        | 2.34%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 14        | 2.19%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 13        | 2.03%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 13        | 2.03%   |
| Validity Sensors VFS491                                                    | 11        | 1.72%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 11        | 1.72%   |
| Shenzhen Goodix FingerPrint                                                | 11        | 1.72%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 10        | 1.56%   |
| Synaptics  WBDI                                                            | 9         | 1.41%   |
| Unknown                                                                    | 9         | 1.41%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 8         | 1.25%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 8         | 1.25%   |
| Validity Sensors VFS Fingerprint sensor                                    | 7         | 1.09%   |
| AuthenTec Fingerprint Sensor                                               | 7         | 1.09%   |
| AuthenTec AES1600                                                          | 7         | 1.09%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 6         | 0.94%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 6         | 0.94%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 6         | 0.94%   |
| Validity Sensors Synaptics WBDI                                            | 5         | 0.78%   |
| Upek TCS5B Fingerprint sensor                                              | 5         | 0.78%   |
| Synaptics UWP WBDI Device                                                  | 5         | 0.78%   |
| Synaptics UWP WBDI                                                         | 5         | 0.78%   |
| STMicroelectronics Fingerprint Reader                                      | 5         | 0.78%   |
| LighTuning Fingerprint Reader                                              | 5         | 0.78%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 4         | 0.63%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 4         | 0.63%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 0.47%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Broadcom                 | 101       | 39.45%  |
| Alcor Micro              | 84        | 32.81%  |
| O2 Micro                 | 27        | 10.55%  |
| Lenovo                   | 16        | 6.25%   |
| Upek                     | 11        | 4.3%    |
| Gemalto (was Gemplus)    | 4         | 1.56%   |
| Advanced Card Systems    | 4         | 1.56%   |
| BIT4ID                   | 3         | 1.17%   |
| Realtek Semiconductor    | 2         | 0.78%   |
| SCM Microsystems         | 1         | 0.39%   |
| Reiner SCT Kartensysteme | 1         | 0.39%   |
| OmniKey                  | 1         | 0.39%   |
| In Focus Systems         | 1         | 0.39%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 81        | 31.64%  |
| Broadcom BCM5880 Secure Applications Processor                               | 31        | 12.11%  |
| Broadcom 58200                                                               | 28        | 10.94%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 23        | 8.98%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 20        | 7.81%   |
| Broadcom 5880                                                                | 20        | 7.81%   |
| Lenovo Integrated Smart Card Reader                                          | 16        | 6.25%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 11        | 4.3%    |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 1.56%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 1.17%   |
| BIT4ID miniLector EVO                                                        | 3         | 1.17%   |
| Alcor Micro Watchdata W 1981                                                 | 3         | 1.17%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 3         | 1.17%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 0.78%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.78%   |
| SCM Microsystems uTrust 3700 F CL Reader                                     | 1         | 0.39%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.39%   |
| OmniKey CardMan Smart@Link                                                   | 1         | 0.39%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.39%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.39%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.39%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 2403      | 61.69%  |
| 1     | 1170      | 30.04%  |
| 2     | 285       | 7.32%   |
| 3     | 24        | 0.62%   |
| 4     | 10        | 0.26%   |
| 5     | 2         | 0.05%   |
| 6     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 632       | 35.11%  |
| Graphics card            | 426       | 23.67%  |
| Chipcard                 | 223       | 12.39%  |
| Net/wireless             | 167       | 9.28%   |
| Multimedia controller    | 85        | 4.72%   |
| Camera                   | 65        | 3.61%   |
| Bluetooth                | 59        | 3.28%   |
| Storage                  | 28        | 1.56%   |
| Communication controller | 26        | 1.44%   |
| Flash memory             | 18        | 1%      |
| Sound                    | 17        | 0.94%   |
| Modem                    | 17        | 0.94%   |
| Net/ethernet             | 13        | 0.72%   |
| Card reader              | 13        | 0.72%   |
| Network                  | 5         | 0.28%   |
| Dvb card                 | 2         | 0.11%   |
| Wireless                 | 1         | 0.06%   |
| Storage/raid             | 1         | 0.06%   |
| Storage/nvme             | 1         | 0.06%   |
| Storage/ide              | 1         | 0.06%   |

