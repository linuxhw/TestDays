Zorin 16 - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------

A project to collect tested hardware configurations for Zorin 16.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

Total: 2540

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Samsung       | N150/N210/N220              | [977d645961](https://linux-hardware.org/?probe=977d645961) | Jun 10, 2023 |
| Notebook      | NJ50_70CU                   | [d39b8694fd](https://linux-hardware.org/?probe=d39b8694fd) | Jun 10, 2023 |
| Packard Be... | EasyNote TE11BZ             | [a8f9a31f17](https://linux-hardware.org/?probe=a8f9a31f17) | Jun 10, 2023 |
| Google        | Pirika                      | [67fce0a645](https://linux-hardware.org/?probe=67fce0a645) | Jun 10, 2023 |
| Dell          | Precision 7520              | [c52fb2f851](https://linux-hardware.org/?probe=c52fb2f851) | Jun 10, 2023 |
| HP            | Pavilion Notebook           | [5254a5fe09](https://linux-hardware.org/?probe=5254a5fe09) | Jun 07, 2023 |
| HP            | Pavilion Laptop 14-ec1xx... | [de4c183b01](https://linux-hardware.org/?probe=de4c183b01) | Jun 06, 2023 |
| Samsung       | 300E5M/300E5L               | [e066300eac](https://linux-hardware.org/?probe=e066300eac) | Jun 06, 2023 |
| Acer          | Aspire 5736Z                | [a98deb1f54](https://linux-hardware.org/?probe=a98deb1f54) | Jun 06, 2023 |
| Apple         | MacBookPro8,1               | [8308d5da16](https://linux-hardware.org/?probe=8308d5da16) | Jun 05, 2023 |
| Apple         | MacBookPro8,1               | [2f8dbb707f](https://linux-hardware.org/?probe=2f8dbb707f) | Jun 05, 2023 |
| HP            | OMEN by Laptop              | [e3b8e1a109](https://linux-hardware.org/?probe=e3b8e1a109) | Jun 04, 2023 |
| Dell          | Latitude E5250              | [e85c6a09d1](https://linux-hardware.org/?probe=e85c6a09d1) | Jun 04, 2023 |
| Toshiba       | IS 1412                     | [b1b0369688](https://linux-hardware.org/?probe=b1b0369688) | Jun 04, 2023 |
| Lenovo        | ThinkPad T450 20BUS0LW02    | [27f6e7df80](https://linux-hardware.org/?probe=27f6e7df80) | Jun 04, 2023 |
| HP            | Stream Laptop 14-cb0XX      | [83967c7908](https://linux-hardware.org/?probe=83967c7908) | Jun 04, 2023 |
| HP            | ProBook 450 G2              | [55f28b41b4](https://linux-hardware.org/?probe=55f28b41b4) | Jun 03, 2023 |
| Toshiba       | IS 1412                     | [6ea1bc7e6a](https://linux-hardware.org/?probe=6ea1bc7e6a) | Jun 03, 2023 |
| IPASON        | P3                          | [bd9e0660a4](https://linux-hardware.org/?probe=bd9e0660a4) | Jun 02, 2023 |
| ASUSTek       | K70IJ                       | [5b877dfec5](https://linux-hardware.org/?probe=5b877dfec5) | Jun 02, 2023 |
| Toshiba       | Satellite L650              | [63eb6978fa](https://linux-hardware.org/?probe=63eb6978fa) | Jun 01, 2023 |
| Lenovo        | IdeaPad 3 17ITL6 82H9       | [a7af6cac2c](https://linux-hardware.org/?probe=a7af6cac2c) | Jun 01, 2023 |
| HP            | Pavilion dv6500             | [0198d67a15](https://linux-hardware.org/?probe=0198d67a15) | May 31, 2023 |
| Sony          | SVF14214CXW                 | [51568ce56e](https://linux-hardware.org/?probe=51568ce56e) | May 30, 2023 |
| Dell          | Latitude 3480               | [56d1834385](https://linux-hardware.org/?probe=56d1834385) | May 30, 2023 |
| Sony          | SVF14214CXW                 | [6cf7c2d7f2](https://linux-hardware.org/?probe=6cf7c2d7f2) | May 30, 2023 |
| Dell          | Inspiron 5748               | [08b61d608c](https://linux-hardware.org/?probe=08b61d608c) | May 30, 2023 |
| ASUSTek       | U43Jc                       | [db28d8f731](https://linux-hardware.org/?probe=db28d8f731) | May 28, 2023 |
| ASUSTek       | U43Jc                       | [36bd3a5288](https://linux-hardware.org/?probe=36bd3a5288) | May 28, 2023 |
| Lenovo        | ThinkPad E490 20N8A01YGI    | [c46cf56eb1](https://linux-hardware.org/?probe=c46cf56eb1) | May 27, 2023 |
| Lenovo        | B50-70 80EU                 | [8c51cdf4ef](https://linux-hardware.org/?probe=8c51cdf4ef) | May 27, 2023 |
| HP            | Pavilion dv6                | [9f96328490](https://linux-hardware.org/?probe=9f96328490) | May 27, 2023 |
| Acer          | Aspire ES1-523              | [681fbd4a1f](https://linux-hardware.org/?probe=681fbd4a1f) | May 27, 2023 |
| Toshiba       | TECRA M10                   | [3ce97963e7](https://linux-hardware.org/?probe=3ce97963e7) | May 26, 2023 |
| Toshiba       | TECRA M10                   | [2c574f9677](https://linux-hardware.org/?probe=2c574f9677) | May 26, 2023 |
| HP            | ProBook 4740s               | [457a56d75c](https://linux-hardware.org/?probe=457a56d75c) | May 26, 2023 |
| ASUSTek       | G50VT                       | [6e4a2588b1](https://linux-hardware.org/?probe=6e4a2588b1) | May 26, 2023 |
| Google        | Lars                        | [25cc6549c3](https://linux-hardware.org/?probe=25cc6549c3) | May 25, 2023 |
| HP            | ProBook 6440b               | [5ed14b01a3](https://linux-hardware.org/?probe=5ed14b01a3) | May 25, 2023 |
| Apple         | MacBookAir4,1               | [d25345cb25](https://linux-hardware.org/?probe=d25345cb25) | May 25, 2023 |
| HP            | Pavilion g6                 | [f6fbdf57b5](https://linux-hardware.org/?probe=f6fbdf57b5) | May 24, 2023 |
| HP            | Pavilion Notebook 15-bc5... | [933989a15b](https://linux-hardware.org/?probe=933989a15b) | May 24, 2023 |
| HP            | Stream Notebook             | [74d40533fc](https://linux-hardware.org/?probe=74d40533fc) | May 24, 2023 |
| Lenovo        | V130-15IGM 81HL             | [504a24887e](https://linux-hardware.org/?probe=504a24887e) | May 24, 2023 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [8c7d3913b8](https://linux-hardware.org/?probe=8c7d3913b8) | May 24, 2023 |
| Apple         | MacBookPro7,1               | [e1baf451db](https://linux-hardware.org/?probe=e1baf451db) | May 23, 2023 |
| Apple         | MacBookPro7,1               | [61ef8e4e63](https://linux-hardware.org/?probe=61ef8e4e63) | May 23, 2023 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [08746538f6](https://linux-hardware.org/?probe=08746538f6) | May 23, 2023 |
| Dell          | Latitude E5450              | [642802d511](https://linux-hardware.org/?probe=642802d511) | May 23, 2023 |
| Dell          | Inspiron 1501               | [4703a17f03](https://linux-hardware.org/?probe=4703a17f03) | May 23, 2023 |
| HP            | Pavilion g6                 | [4d0edc38d5](https://linux-hardware.org/?probe=4d0edc38d5) | May 23, 2023 |
| Packard Be... | EasyNote MH35               | [ea7710b373](https://linux-hardware.org/?probe=ea7710b373) | May 22, 2023 |
| Acer          | Aspire A515-56              | [dfb369a8d2](https://linux-hardware.org/?probe=dfb369a8d2) | May 22, 2023 |
| HP            | EliteBook Folio G1          | [81477cd76f](https://linux-hardware.org/?probe=81477cd76f) | May 22, 2023 |
| HP            | EliteBook Folio G1          | [73d4310fa2](https://linux-hardware.org/?probe=73d4310fa2) | May 22, 2023 |
| HP            | Pavilion Sleekbook 14 PC    | [6bef224193](https://linux-hardware.org/?probe=6bef224193) | May 20, 2023 |
| Apple         | MacBookAir7,2               | [d11ecdffaf](https://linux-hardware.org/?probe=d11ecdffaf) | May 20, 2023 |
| Dell          | Latitude E7450              | [b76cb7567c](https://linux-hardware.org/?probe=b76cb7567c) | May 20, 2023 |
| HP            | 255 G8 Notebook PC          | [c1f679b4d4](https://linux-hardware.org/?probe=c1f679b4d4) | May 20, 2023 |
| HP            | 255 G8 Notebook PC          | [0c163f5c69](https://linux-hardware.org/?probe=0c163f5c69) | May 20, 2023 |
| HP            | Stream Laptop 14-ax0XX      | [aae519e65d](https://linux-hardware.org/?probe=aae519e65d) | May 19, 2023 |
| Tactus        | GeoBook 140                 | [534c32884a](https://linux-hardware.org/?probe=534c32884a) | May 19, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [0608bc6ac3](https://linux-hardware.org/?probe=0608bc6ac3) | May 18, 2023 |
| Philco        | PHN14C                      | [4efea72b8f](https://linux-hardware.org/?probe=4efea72b8f) | May 18, 2023 |
| Acer          | Aspire A514-55              | [e096b3a75c](https://linux-hardware.org/?probe=e096b3a75c) | May 18, 2023 |
| Apple         | MacBookAir7,2               | [cadb0eb363](https://linux-hardware.org/?probe=cadb0eb363) | May 17, 2023 |
| Apple         | MacBookAir7,2               | [cd3c24c6a2](https://linux-hardware.org/?probe=cd3c24c6a2) | May 17, 2023 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [e18deba45b](https://linux-hardware.org/?probe=e18deba45b) | May 17, 2023 |
| Framework     | Laptop                      | [b8739c141d](https://linux-hardware.org/?probe=b8739c141d) | May 16, 2023 |
| Dell          | XPS 17 9700                 | [7b95691784](https://linux-hardware.org/?probe=7b95691784) | May 15, 2023 |
| Samsung       | N150/N210/N220              | [3f18889439](https://linux-hardware.org/?probe=3f18889439) | May 15, 2023 |
| ASUSTek       | ROG Strix G512LW_G512LW     | [03c67bbed5](https://linux-hardware.org/?probe=03c67bbed5) | May 15, 2023 |
| HP            | Laptop 15-db0xxx            | [496f6048ec](https://linux-hardware.org/?probe=496f6048ec) | May 15, 2023 |
| Apple         | MacBookPro10,1              | [d27a3510ed](https://linux-hardware.org/?probe=d27a3510ed) | May 14, 2023 |
| HP            | Presario CQ61               | [0967999006](https://linux-hardware.org/?probe=0967999006) | May 14, 2023 |
| Google        | Bluebird                    | [c10880ed1b](https://linux-hardware.org/?probe=c10880ed1b) | May 14, 2023 |
| Acer          | Aspire E5-574               | [89fbcb7903](https://linux-hardware.org/?probe=89fbcb7903) | May 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [83e208da09](https://linux-hardware.org/?probe=83e208da09) | May 14, 2023 |
| Lenovo        | IdeaPad Z470                | [2b11351f94](https://linux-hardware.org/?probe=2b11351f94) | May 14, 2023 |
| Dell          | Latitude 3340               | [59d83d9cef](https://linux-hardware.org/?probe=59d83d9cef) | May 14, 2023 |
| SKIKK         | Niflheim 17 II              | [ce9c27f16f](https://linux-hardware.org/?probe=ce9c27f16f) | May 14, 2023 |
| Chuwi         | GemiBook XPro               | [53b6692944](https://linux-hardware.org/?probe=53b6692944) | May 13, 2023 |
| Chuwi         | GemiBook XPro               | [297921aabf](https://linux-hardware.org/?probe=297921aabf) | May 13, 2023 |
| Acer          | Aspire E1-570               | [135675c3ad](https://linux-hardware.org/?probe=135675c3ad) | May 13, 2023 |
| Google        | Kled                        | [f4e834ff36](https://linux-hardware.org/?probe=f4e834ff36) | May 12, 2023 |
| Dell          | Precision M2800             | [571407d9a3](https://linux-hardware.org/?probe=571407d9a3) | May 12, 2023 |
| Chuwi         | GemiBook XPro               | [e13fe43842](https://linux-hardware.org/?probe=e13fe43842) | May 12, 2023 |
| HP            | ProBook 4535s               | [0d2f9561ce](https://linux-hardware.org/?probe=0d2f9561ce) | May 12, 2023 |
| HP            | EliteBook 820 G4            | [34bd8e2402](https://linux-hardware.org/?probe=34bd8e2402) | May 12, 2023 |
| HP            | OMEN by Laptop              | [5a1484127d](https://linux-hardware.org/?probe=5a1484127d) | May 12, 2023 |
| Apple         | MacBookPro10,1              | [381ca3ca78](https://linux-hardware.org/?probe=381ca3ca78) | May 11, 2023 |
| HP            | OMEN by Laptop              | [2c8128a196](https://linux-hardware.org/?probe=2c8128a196) | May 11, 2023 |
| HP            | EliteBook 820 G4            | [a7327f2e2e](https://linux-hardware.org/?probe=a7327f2e2e) | May 11, 2023 |
| HP            | EliteBook 745 G3            | [256ad0c4d8](https://linux-hardware.org/?probe=256ad0c4d8) | May 11, 2023 |
| Acer          | Aspire A315-23              | [2c96614c16](https://linux-hardware.org/?probe=2c96614c16) | May 11, 2023 |
| Toshiba       | TECRA M10                   | [cf43cf62c7](https://linux-hardware.org/?probe=cf43cf62c7) | May 10, 2023 |
| Toshiba       | TECRA M10                   | [d2be66b23b](https://linux-hardware.org/?probe=d2be66b23b) | May 10, 2023 |
| HP            | Pavilion dv7                | [794d198929](https://linux-hardware.org/?probe=794d198929) | May 10, 2023 |
| ASUSTek       | GL702VI                     | [3598875ef3](https://linux-hardware.org/?probe=3598875ef3) | May 09, 2023 |
| HP            | EliteBook 840 G4            | [372fa59e86](https://linux-hardware.org/?probe=372fa59e86) | May 09, 2023 |
| HP            | EliteBook 840 G4            | [9ac068efc7](https://linux-hardware.org/?probe=9ac068efc7) | May 09, 2023 |
| Dell          | Latitude E6520              | [668b26cd28](https://linux-hardware.org/?probe=668b26cd28) | May 09, 2023 |
| HP            | Laptop 15                   | [20a0a03b80](https://linux-hardware.org/?probe=20a0a03b80) | May 08, 2023 |
| Acer          | Aspire E5-574               | [d48affb6b2](https://linux-hardware.org/?probe=d48affb6b2) | May 08, 2023 |
| HP            | 655                         | [be3dec1f65](https://linux-hardware.org/?probe=be3dec1f65) | May 08, 2023 |
| Positivo      | S14CT01                     | [63a129c031](https://linux-hardware.org/?probe=63a129c031) | May 08, 2023 |
| Dell          | Latitude 5520               | [4d8ef45cbc](https://linux-hardware.org/?probe=4d8ef45cbc) | May 07, 2023 |
| SKIKK         | Niflheim 17 II              | [0304fddec7](https://linux-hardware.org/?probe=0304fddec7) | May 07, 2023 |
| SKIKK         | Niflheim 17 II              | [2a30823af1](https://linux-hardware.org/?probe=2a30823af1) | May 07, 2023 |
| Fujitsu Si... | AMILO PRO V3515             | [a6da9a31d7](https://linux-hardware.org/?probe=a6da9a31d7) | May 06, 2023 |
| Dell          | Inspiron 3501               | [b7bf9f8683](https://linux-hardware.org/?probe=b7bf9f8683) | May 06, 2023 |
| HP            | ProBook 6570b               | [480e352bf8](https://linux-hardware.org/?probe=480e352bf8) | May 05, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [9a0649d500](https://linux-hardware.org/?probe=9a0649d500) | May 05, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [6069763b68](https://linux-hardware.org/?probe=6069763b68) | May 05, 2023 |
| Lenovo        | Legion 7 16ACHg6 82N6       | [d8582f94de](https://linux-hardware.org/?probe=d8582f94de) | May 05, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [4ac4356e10](https://linux-hardware.org/?probe=4ac4356e10) | May 05, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [37fd24fab6](https://linux-hardware.org/?probe=37fd24fab6) | May 05, 2023 |
| Lenovo        | ThinkPad T520 4242A25       | [6290e7f2fb](https://linux-hardware.org/?probe=6290e7f2fb) | May 05, 2023 |
| Unknown       | X133                        | [b38ee0b3cc](https://linux-hardware.org/?probe=b38ee0b3cc) | May 05, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [cf49833602](https://linux-hardware.org/?probe=cf49833602) | May 04, 2023 |
| HP            | EliteBook 8470p             | [9684be9c3a](https://linux-hardware.org/?probe=9684be9c3a) | May 04, 2023 |
| Unknown       | E450                        | [a3261aab47](https://linux-hardware.org/?probe=a3261aab47) | May 04, 2023 |
| Dell          | XPS 15 9560                 | [15160b0649](https://linux-hardware.org/?probe=15160b0649) | May 04, 2023 |
| KUU           | Andes II                    | [b15876e521](https://linux-hardware.org/?probe=b15876e521) | May 04, 2023 |
| Acer          | Aspire E1-570               | [bf515886ac](https://linux-hardware.org/?probe=bf515886ac) | May 03, 2023 |
| Acer          | Aspire V5-531               | [d8c61ad691](https://linux-hardware.org/?probe=d8c61ad691) | May 02, 2023 |
| Dell          | Latitude E6540              | [e6f334c91c](https://linux-hardware.org/?probe=e6f334c91c) | May 01, 2023 |
| Acer          | Aspire A315-21              | [f2c5618e4d](https://linux-hardware.org/?probe=f2c5618e4d) | May 01, 2023 |
| ASUSTek       | K53U                        | [0745a61353](https://linux-hardware.org/?probe=0745a61353) | May 01, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | [cbc75f825e](https://linux-hardware.org/?probe=cbc75f825e) | May 01, 2023 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | [e316615297](https://linux-hardware.org/?probe=e316615297) | May 01, 2023 |
| Acer          | Aspire E5-574               | [bcd38374a3](https://linux-hardware.org/?probe=bcd38374a3) | May 01, 2023 |
| HP            | Pavilion dv7                | [68b51fde68](https://linux-hardware.org/?probe=68b51fde68) | Apr 30, 2023 |
| Positivo      | S14CT01                     | [b11ef938e1](https://linux-hardware.org/?probe=b11ef938e1) | Apr 29, 2023 |
| Toshiba       | Satellite C650D             | [472dedd62a](https://linux-hardware.org/?probe=472dedd62a) | Apr 29, 2023 |
| Sony          | VPCF215FX                   | [49c7606269](https://linux-hardware.org/?probe=49c7606269) | Apr 29, 2023 |
| Apple         | MacBook6,1                  | [58b09d7887](https://linux-hardware.org/?probe=58b09d7887) | Apr 29, 2023 |
| Apple         | MacBook6,1                  | [7d91fe30f7](https://linux-hardware.org/?probe=7d91fe30f7) | Apr 29, 2023 |
| Positivo      | S14CT01                     | [58988f4876](https://linux-hardware.org/?probe=58988f4876) | Apr 29, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [e908fdb73d](https://linux-hardware.org/?probe=e908fdb73d) | Apr 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [a984eefe43](https://linux-hardware.org/?probe=a984eefe43) | Apr 28, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [d9010fa8d0](https://linux-hardware.org/?probe=d9010fa8d0) | Apr 28, 2023 |
| Lenovo        | ThinkPad Edge 25453BG       | [2b5c6e2ded](https://linux-hardware.org/?probe=2b5c6e2ded) | Apr 28, 2023 |
| HP            | Laptop 14-em0xxx            | [8d06549ae0](https://linux-hardware.org/?probe=8d06549ae0) | Apr 28, 2023 |
| Lenovo        | IdeaPad Y470                | [58c809428e](https://linux-hardware.org/?probe=58c809428e) | Apr 28, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | [f1290d4846](https://linux-hardware.org/?probe=f1290d4846) | Apr 28, 2023 |
| Dell          | Vostro 1510                 | [71c860d51c](https://linux-hardware.org/?probe=71c860d51c) | Apr 26, 2023 |
| Medion        | E2215T MD60198              | [390ccbba6f](https://linux-hardware.org/?probe=390ccbba6f) | Apr 26, 2023 |
| Acer          | Aspire A515-57              | [86dad710fa](https://linux-hardware.org/?probe=86dad710fa) | Apr 26, 2023 |
| Lenovo        | 3000 N200 0769A97           | [a293f4f1f7](https://linux-hardware.org/?probe=a293f4f1f7) | Apr 26, 2023 |
| Lenovo        | ThinkPad T430 2347GU8       | [c40de2e155](https://linux-hardware.org/?probe=c40de2e155) | Apr 26, 2023 |
| Lenovo        | ThinkPad T430 2347GU8       | [7abd61de30](https://linux-hardware.org/?probe=7abd61de30) | Apr 25, 2023 |
| HP            | EliteBook 2730p             | [51c0fadfdb](https://linux-hardware.org/?probe=51c0fadfdb) | Apr 25, 2023 |
| Lenovo        | ThinkPad T430 2347GU8       | [927c9a0377](https://linux-hardware.org/?probe=927c9a0377) | Apr 25, 2023 |
| Toshiba       | Satellite C45-A             | [7720195dfe](https://linux-hardware.org/?probe=7720195dfe) | Apr 24, 2023 |
| Dell          | Inspiron 5565               | [6622474d4b](https://linux-hardware.org/?probe=6622474d4b) | Apr 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [60d1d4aec8](https://linux-hardware.org/?probe=60d1d4aec8) | Apr 24, 2023 |
| HP            | Stream Laptop 14-ax0XX      | [c087d6cbae](https://linux-hardware.org/?probe=c087d6cbae) | Apr 24, 2023 |
| Dell          | XPS 15 9530                 | [d9429d7e06](https://linux-hardware.org/?probe=d9429d7e06) | Apr 23, 2023 |
| Lenovo        | ThinkPad T440s 20ARS1BH0... | [b76462c15b](https://linux-hardware.org/?probe=b76462c15b) | Apr 23, 2023 |
| MSI           | GP62 7RD                    | [277bb2d2e3](https://linux-hardware.org/?probe=277bb2d2e3) | Apr 23, 2023 |
| Acer          | AOD270                      | [d7d653d3d6](https://linux-hardware.org/?probe=d7d653d3d6) | Apr 23, 2023 |
| HP            | Laptop 14-em0xxx            | [55ea4ded18](https://linux-hardware.org/?probe=55ea4ded18) | Apr 22, 2023 |
| Lenovo        | B590 62743NG                | [ca0be4b423](https://linux-hardware.org/?probe=ca0be4b423) | Apr 22, 2023 |
| Lenovo        | B590 62743NG                | [74e38a8db9](https://linux-hardware.org/?probe=74e38a8db9) | Apr 22, 2023 |
| AIERXUAN      | XIAOXUAN Pro                | [e472034313](https://linux-hardware.org/?probe=e472034313) | Apr 21, 2023 |
| AIERXUAN      | XIAOXUAN Pro                | [e500ddd5d9](https://linux-hardware.org/?probe=e500ddd5d9) | Apr 21, 2023 |
| Dell          | Inspiron 3531               | [6222a9aa08](https://linux-hardware.org/?probe=6222a9aa08) | Apr 21, 2023 |
| MSI           | GS73VR 7RF                  | [2eb85cc7fe](https://linux-hardware.org/?probe=2eb85cc7fe) | Apr 20, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [7d380bf016](https://linux-hardware.org/?probe=7d380bf016) | Apr 20, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [7029b5ee48](https://linux-hardware.org/?probe=7029b5ee48) | Apr 20, 2023 |
| Lenovo        | Yoga 300-11IBR 80M1         | [9093d27c30](https://linux-hardware.org/?probe=9093d27c30) | Apr 19, 2023 |
| Notebook      | NL40_50CU                   | [069a675d2a](https://linux-hardware.org/?probe=069a675d2a) | Apr 19, 2023 |
| Dell          | XPS 15 9530                 | [bb0be3d9e3](https://linux-hardware.org/?probe=bb0be3d9e3) | Apr 19, 2023 |
| Notebook      | NL40_50CU                   | [e58c3ad9d7](https://linux-hardware.org/?probe=e58c3ad9d7) | Apr 19, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [c36b1a5778](https://linux-hardware.org/?probe=c36b1a5778) | Apr 19, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | [1548cc4309](https://linux-hardware.org/?probe=1548cc4309) | Apr 19, 2023 |
| Notebook      | NL40_50CU                   | [85c7be8d12](https://linux-hardware.org/?probe=85c7be8d12) | Apr 19, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | [7da02a75b5](https://linux-hardware.org/?probe=7da02a75b5) | Apr 18, 2023 |
| Acer          | Aspire E5-574               | [2f60207985](https://linux-hardware.org/?probe=2f60207985) | Apr 17, 2023 |
| Lenovo        | Yoga 2 13 20344             | [895f57e6d5](https://linux-hardware.org/?probe=895f57e6d5) | Apr 17, 2023 |
| Dell          | Vostro 3580                 | [b7d9953b54](https://linux-hardware.org/?probe=b7d9953b54) | Apr 16, 2023 |
| Lenovo        | Y50-70 20378                | [f146ce9da7](https://linux-hardware.org/?probe=f146ce9da7) | Apr 16, 2023 |
| Apple         | MacBookPro5,3               | [ea8d83a743](https://linux-hardware.org/?probe=ea8d83a743) | Apr 16, 2023 |
| Lenovo        | ThinkPad P52s 20LCS1DU01    | [3fc78b3451](https://linux-hardware.org/?probe=3fc78b3451) | Apr 16, 2023 |
| HONOR         | BBR-WAX9                    | [a56688fd70](https://linux-hardware.org/?probe=a56688fd70) | Apr 16, 2023 |
| HONOR         | BBR-WAX9                    | [798405022f](https://linux-hardware.org/?probe=798405022f) | Apr 16, 2023 |
| AZW           | SEi                         | [a382976bf2](https://linux-hardware.org/?probe=a382976bf2) | Apr 15, 2023 |
| AZW           | SEi                         | [980b83cf5e](https://linux-hardware.org/?probe=980b83cf5e) | Apr 15, 2023 |
| Acer          | Aspire V3-772               | [2b6f0394d7](https://linux-hardware.org/?probe=2b6f0394d7) | Apr 15, 2023 |
| Acer          | Aspire ES1-731G             | [1ef0f89c83](https://linux-hardware.org/?probe=1ef0f89c83) | Apr 15, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [ba3d9dd7e7](https://linux-hardware.org/?probe=ba3d9dd7e7) | Apr 15, 2023 |
| HP            | Pavilion Power Laptop 15... | [b66c208e18](https://linux-hardware.org/?probe=b66c208e18) | Apr 15, 2023 |
| Apple         | MacBookPro14,1              | [2ca7c3fccc](https://linux-hardware.org/?probe=2ca7c3fccc) | Apr 15, 2023 |
| Lenovo        | ThinkPad T430s 2352CTO      | [a4c5130b84](https://linux-hardware.org/?probe=a4c5130b84) | Apr 15, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [e122e8dab8](https://linux-hardware.org/?probe=e122e8dab8) | Apr 15, 2023 |
| Positivo      | Q4128C-S                    | [8dc2eb7738](https://linux-hardware.org/?probe=8dc2eb7738) | Apr 14, 2023 |
| HP            | EliteBook 830 G6            | [75ce029800](https://linux-hardware.org/?probe=75ce029800) | Apr 13, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [9e6cfba525](https://linux-hardware.org/?probe=9e6cfba525) | Apr 13, 2023 |
| Acer          | Aspire E5-771G              | [504d600530](https://linux-hardware.org/?probe=504d600530) | Apr 13, 2023 |
| HP            | Compaq Presario F700        | [2ae0d7557b](https://linux-hardware.org/?probe=2ae0d7557b) | Apr 13, 2023 |
| Dell          | Inspiron 1545               | [653a25793d](https://linux-hardware.org/?probe=653a25793d) | Apr 12, 2023 |
| Dell          | Inspiron 1545               | [dccecbecf9](https://linux-hardware.org/?probe=dccecbecf9) | Apr 12, 2023 |
| Acer          | Aspire 5742G                | [878333e620](https://linux-hardware.org/?probe=878333e620) | Apr 12, 2023 |
| Acer          | Aspire A315-56              | [b504683b39](https://linux-hardware.org/?probe=b504683b39) | Apr 12, 2023 |
| Acer          | Aspire A315-56              | [8b8d053221](https://linux-hardware.org/?probe=8b8d053221) | Apr 12, 2023 |
| Toshiba       | Satellite C650D             | [fb8b24d111](https://linux-hardware.org/?probe=fb8b24d111) | Apr 12, 2023 |
| Apple         | MacBookPro14,2              | [1bc09aed8a](https://linux-hardware.org/?probe=1bc09aed8a) | Apr 10, 2023 |
| Dell          | XPS 13 9343                 | [f847287142](https://linux-hardware.org/?probe=f847287142) | Apr 09, 2023 |
| Thomson       | WWNEO14C-4BK32F             | [8b461d224b](https://linux-hardware.org/?probe=8b461d224b) | Apr 06, 2023 |
| HP            | ProBook 4540s               | [02754e47f3](https://linux-hardware.org/?probe=02754e47f3) | Apr 05, 2023 |
| Acer          | Aspire 5742G                | [5363e4031e](https://linux-hardware.org/?probe=5363e4031e) | Apr 05, 2023 |
| HP            | Notebook                    | [4ac4839ccd](https://linux-hardware.org/?probe=4ac4839ccd) | Apr 05, 2023 |
| HP            | EliteBook 8460p             | [5a864191a9](https://linux-hardware.org/?probe=5a864191a9) | Apr 05, 2023 |
| HP            | EliteBook 8460p             | [bb24498044](https://linux-hardware.org/?probe=bb24498044) | Apr 05, 2023 |
| Google        | Cyan                        | [f02aa2a210](https://linux-hardware.org/?probe=f02aa2a210) | Apr 04, 2023 |
| Toshiba       | Satellite C650              | [190547d5cd](https://linux-hardware.org/?probe=190547d5cd) | Apr 03, 2023 |
| Dell          | Latitude E6430              | [5c205ea646](https://linux-hardware.org/?probe=5c205ea646) | Apr 03, 2023 |
| Fujitsu       | LIFEBOOK T935               | [1cc4178b9a](https://linux-hardware.org/?probe=1cc4178b9a) | Apr 02, 2023 |
| Apple         | MacBookPro11,2              | [f78d5a9d04](https://linux-hardware.org/?probe=f78d5a9d04) | Apr 02, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [45086032e1](https://linux-hardware.org/?probe=45086032e1) | Apr 02, 2023 |
| Notebook      | NJ50GU                      | [91e860cd94](https://linux-hardware.org/?probe=91e860cd94) | Apr 02, 2023 |
| Lenovo        | V570 1066EDG                | [8a8a256b79](https://linux-hardware.org/?probe=8a8a256b79) | Apr 02, 2023 |
| Monster       | HUMA H4 V5.2                | [fdd74dbc8c](https://linux-hardware.org/?probe=fdd74dbc8c) | Apr 02, 2023 |
| Dell          | Vostro 1520                 | [2132a3308c](https://linux-hardware.org/?probe=2132a3308c) | Apr 01, 2023 |
| Lenovo        | ThinkPad T410 2518P9G       | [4f74fa6cd2](https://linux-hardware.org/?probe=4f74fa6cd2) | Apr 01, 2023 |
| ASUSTek       | T100TA                      | [1f0b0c32ca](https://linux-hardware.org/?probe=1f0b0c32ca) | Apr 01, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [af258dcd36](https://linux-hardware.org/?probe=af258dcd36) | Mar 31, 2023 |
| ASUSTek       | X450LD                      | [1ca0cdc1e8](https://linux-hardware.org/?probe=1ca0cdc1e8) | Mar 31, 2023 |
| Positivo      | S14SL01                     | [e1c79f71b7](https://linux-hardware.org/?probe=e1c79f71b7) | Mar 30, 2023 |
| HP            | kip                         | [fe84eac39e](https://linux-hardware.org/?probe=fe84eac39e) | Mar 30, 2023 |
| Positivo      | Q232A                       | [2282c5ce96](https://linux-hardware.org/?probe=2282c5ce96) | Mar 30, 2023 |
| Positivo      | Q232A                       | [98e6b249af](https://linux-hardware.org/?probe=98e6b249af) | Mar 29, 2023 |
| Dell          | Precision M4500             | [cf7e033a17](https://linux-hardware.org/?probe=cf7e033a17) | Mar 29, 2023 |
| Dell          | Latitude 7430               | [fdef205301](https://linux-hardware.org/?probe=fdef205301) | Mar 29, 2023 |
| Dell          | Latitude 3590               | [9b5971401c](https://linux-hardware.org/?probe=9b5971401c) | Mar 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [ebf2728d28](https://linux-hardware.org/?probe=ebf2728d28) | Mar 29, 2023 |
| Apple         | MacBookPro11,2              | [422e4056ea](https://linux-hardware.org/?probe=422e4056ea) | Mar 28, 2023 |
| Thomson       | WWNEO14C-4BK32F             | [90fa9585c9](https://linux-hardware.org/?probe=90fa9585c9) | Mar 28, 2023 |
| Acer          | Swift SF314-511             | [ccef379a7f](https://linux-hardware.org/?probe=ccef379a7f) | Mar 28, 2023 |
| Toshiba       | Satellite C55-A-1J8         | [c6ba40cd5c](https://linux-hardware.org/?probe=c6ba40cd5c) | Mar 27, 2023 |
| Packard Be... | EasyNote TE11HC             | [dd242e4ae3](https://linux-hardware.org/?probe=dd242e4ae3) | Mar 27, 2023 |
| Dell          | Inspiron 5555               | [cf226d028d](https://linux-hardware.org/?probe=cf226d028d) | Mar 27, 2023 |
| Lenovo        | ThinkPad Edge E530c 3366... | [b4787579d2](https://linux-hardware.org/?probe=b4787579d2) | Mar 25, 2023 |
| HP            | Compaq 6730s                | [ca30390612](https://linux-hardware.org/?probe=ca30390612) | Mar 25, 2023 |
| WEIPAI        | S15                         | [e6a15d7fa9](https://linux-hardware.org/?probe=e6a15d7fa9) | Mar 25, 2023 |
| HP            | Stream Notebook             | [b1ae4b8667](https://linux-hardware.org/?probe=b1ae4b8667) | Mar 25, 2023 |
| ASUSTek       | G53SX                       | [ab9ed0121f](https://linux-hardware.org/?probe=ab9ed0121f) | Mar 25, 2023 |
| Dell          | Latitude E5510              | [8a9a1eec2c](https://linux-hardware.org/?probe=8a9a1eec2c) | Mar 24, 2023 |
| Framework     | Laptop                      | [4e1bd28ce3](https://linux-hardware.org/?probe=4e1bd28ce3) | Mar 24, 2023 |
| Acer          | Aspire A315-59              | [628d2ea05c](https://linux-hardware.org/?probe=628d2ea05c) | Mar 24, 2023 |
| Dell          | Inspiron 5555               | [efab305a00](https://linux-hardware.org/?probe=efab305a00) | Mar 24, 2023 |
| Dell          | Inspiron 3721               | [e992b8f3a0](https://linux-hardware.org/?probe=e992b8f3a0) | Mar 23, 2023 |
| HP            | Pavilion 15                 | [32a0c3ec32](https://linux-hardware.org/?probe=32a0c3ec32) | Mar 23, 2023 |
| HP            | Pavilion dv6                | [625fff449a](https://linux-hardware.org/?probe=625fff449a) | Mar 23, 2023 |
| Dell          | Latitude E7240              | [a3e408033c](https://linux-hardware.org/?probe=a3e408033c) | Mar 21, 2023 |
| ASUSTek       | G53SX                       | [a6c90e3ad8](https://linux-hardware.org/?probe=a6c90e3ad8) | Mar 21, 2023 |
| Dell          | Inspiron 5405               | [bb59d0b5e9](https://linux-hardware.org/?probe=bb59d0b5e9) | Mar 20, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [e7344d03c0](https://linux-hardware.org/?probe=e7344d03c0) | Mar 20, 2023 |
| Dell          | Inspiron 5423               | [70f51cbfcb](https://linux-hardware.org/?probe=70f51cbfcb) | Mar 19, 2023 |
| Acer          | Aspire M3-581G              | [1434607f7e](https://linux-hardware.org/?probe=1434607f7e) | Mar 19, 2023 |
| Microtech     | CoreBook                    | [d50c0297a6](https://linux-hardware.org/?probe=d50c0297a6) | Mar 19, 2023 |
| Lenovo        | ThinkPad X260 20F600A2MZ    | [5c59b55c2a](https://linux-hardware.org/?probe=5c59b55c2a) | Mar 19, 2023 |
| Lenovo        | ThinkPad T420 4180RK8       | [752373923e](https://linux-hardware.org/?probe=752373923e) | Mar 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [ee8b155a83](https://linux-hardware.org/?probe=ee8b155a83) | Mar 18, 2023 |
| Dell          | Inspiron 3721               | [c7b5ea67bb](https://linux-hardware.org/?probe=c7b5ea67bb) | Mar 18, 2023 |
| ASUSTek       | K52Jc                       | [07dc0a0959](https://linux-hardware.org/?probe=07dc0a0959) | Mar 18, 2023 |
| ASUSTek       | K52Jc                       | [f61ec5ce9f](https://linux-hardware.org/?probe=f61ec5ce9f) | Mar 18, 2023 |
| ASUSTek       | G53SX                       | [901e03fa6e](https://linux-hardware.org/?probe=901e03fa6e) | Mar 17, 2023 |
| ASUSTek       | G53SX                       | [a012da47e9](https://linux-hardware.org/?probe=a012da47e9) | Mar 17, 2023 |
| HP            | Pavilion dm1                | [8707341105](https://linux-hardware.org/?probe=8707341105) | Mar 16, 2023 |
| Alienware     | 15 R3                       | [c1f4b90efb](https://linux-hardware.org/?probe=c1f4b90efb) | Mar 16, 2023 |
| Dell          | Vostro 1520                 | [a029e62352](https://linux-hardware.org/?probe=a029e62352) | Mar 16, 2023 |
| Lenovo        | Yoga 2 13 20344             | [06dd580c2e](https://linux-hardware.org/?probe=06dd580c2e) | Mar 16, 2023 |
| Google        | Babymega                    | [beead110bb](https://linux-hardware.org/?probe=beead110bb) | Mar 16, 2023 |
| Google        | Babymega                    | [0a45acf149](https://linux-hardware.org/?probe=0a45acf149) | Mar 16, 2023 |
| Acer          | Aspire 5736Z                | [d9e1bb3da7](https://linux-hardware.org/?probe=d9e1bb3da7) | Mar 16, 2023 |
| Clevo         | W251EFQ/W270EFQ             | [f5175006b7](https://linux-hardware.org/?probe=f5175006b7) | Mar 15, 2023 |
| Clevo         | W251EFQ/W270EFQ             | [9565625dc4](https://linux-hardware.org/?probe=9565625dc4) | Mar 15, 2023 |
| Lenovo        | ThinkPad T430 23492D1       | [34e2b05336](https://linux-hardware.org/?probe=34e2b05336) | Mar 14, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [f6a3a68640](https://linux-hardware.org/?probe=f6a3a68640) | Mar 14, 2023 |
| HP            | EliteBook 840 G1            | [cbb20e87cb](https://linux-hardware.org/?probe=cbb20e87cb) | Mar 14, 2023 |
| ASUSTek       | U36SD                       | [74e2dfbbc6](https://linux-hardware.org/?probe=74e2dfbbc6) | Mar 14, 2023 |
| Dell          | Inspiron 5423               | [4987f344f2](https://linux-hardware.org/?probe=4987f344f2) | Mar 14, 2023 |
| Google        | Celes                       | [4fd0271747](https://linux-hardware.org/?probe=4fd0271747) | Mar 13, 2023 |
| MSI           | GF63 Thin 11UC              | [77569b52db](https://linux-hardware.org/?probe=77569b52db) | Mar 13, 2023 |
| HP            | Pavilion dv6                | [9d5d0051ea](https://linux-hardware.org/?probe=9d5d0051ea) | Mar 13, 2023 |
| HP            | Pavilion 15                 | [d5eb709e13](https://linux-hardware.org/?probe=d5eb709e13) | Mar 12, 2023 |
| Toshiba       | PORTEGE X30-D               | [9b7e4e10af](https://linux-hardware.org/?probe=9b7e4e10af) | Mar 12, 2023 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | [d777dadd73](https://linux-hardware.org/?probe=d777dadd73) | Mar 12, 2023 |
| Novatech      | 15.6 nSpire Laptop          | [f5814aa2e6](https://linux-hardware.org/?probe=f5814aa2e6) | Mar 12, 2023 |
| Lenovo        | ThinkPad X270 20HMS1KL0C    | [f27bb76a32](https://linux-hardware.org/?probe=f27bb76a32) | Mar 12, 2023 |
| Acer          | TravelMate B113             | [e5f001172d](https://linux-hardware.org/?probe=e5f001172d) | Mar 12, 2023 |
| Apple         | MacBookPro9,2               | [fd63e92774](https://linux-hardware.org/?probe=fd63e92774) | Mar 12, 2023 |
| Apple         | MacBookPro9,2               | [6a0426cb65](https://linux-hardware.org/?probe=6a0426cb65) | Mar 12, 2023 |
| Acer          | TravelMate B113             | [ba6dc5dcb5](https://linux-hardware.org/?probe=ba6dc5dcb5) | Mar 11, 2023 |
| HP            | Pavilion dv6                | [fca49aa86c](https://linux-hardware.org/?probe=fca49aa86c) | Mar 11, 2023 |
| Clevo         | W251EFQ/W270EFQ             | [daad1ee8d5](https://linux-hardware.org/?probe=daad1ee8d5) | Mar 11, 2023 |
| HP            | ZBook 17 G2                 | [4b9462a4ff](https://linux-hardware.org/?probe=4b9462a4ff) | Mar 11, 2023 |
| ASUSTek       | T100TAM                     | [1d647e564b](https://linux-hardware.org/?probe=1d647e564b) | Mar 10, 2023 |
| Medion        | Akoya E1318T                | [8b24b109ec](https://linux-hardware.org/?probe=8b24b109ec) | Mar 10, 2023 |
| Acer          | Aspire V3-772               | [6648af3696](https://linux-hardware.org/?probe=6648af3696) | Mar 10, 2023 |
| Lenovo        | G50-45 80E3                 | [807d1626b4](https://linux-hardware.org/?probe=807d1626b4) | Mar 10, 2023 |
| Toshiba       | Satellite L855              | [3b0a7cfbf0](https://linux-hardware.org/?probe=3b0a7cfbf0) | Mar 10, 2023 |
| Toshiba       | Satellite L855              | [08bfa4188e](https://linux-hardware.org/?probe=08bfa4188e) | Mar 10, 2023 |
| HP            | ProBook 4530s               | [e9c9dd943e](https://linux-hardware.org/?probe=e9c9dd943e) | Mar 10, 2023 |
| Dell          | Precision M6700             | [7a02d78344](https://linux-hardware.org/?probe=7a02d78344) | Mar 10, 2023 |
| HP            | ZBook 17 G2                 | [565c8963d4](https://linux-hardware.org/?probe=565c8963d4) | Mar 10, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | [99d5f17b22](https://linux-hardware.org/?probe=99d5f17b22) | Mar 09, 2023 |
| Acer          | Aspire M3-581G              | [65b41dc560](https://linux-hardware.org/?probe=65b41dc560) | Mar 09, 2023 |
| HP            | Pavilion TS 15              | [5c0b7a773e](https://linux-hardware.org/?probe=5c0b7a773e) | Mar 09, 2023 |
| Dell          | Latitude 3180               | [07a18f8eb1](https://linux-hardware.org/?probe=07a18f8eb1) | Mar 09, 2023 |
| ASUSTek       | X550CL                      | [9acfcb9b4f](https://linux-hardware.org/?probe=9acfcb9b4f) | Mar 09, 2023 |
| ASUSTek       | X550CL                      | [21f11cf791](https://linux-hardware.org/?probe=21f11cf791) | Mar 09, 2023 |
| Multilaser    | PC130                       | [37212994df](https://linux-hardware.org/?probe=37212994df) | Mar 09, 2023 |
| Lenovo        | ThinkPad 11e 20DAS0T500     | [e6fd8c46b0](https://linux-hardware.org/?probe=e6fd8c46b0) | Mar 08, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [d01b6ad50c](https://linux-hardware.org/?probe=d01b6ad50c) | Mar 08, 2023 |
| Dell          | Latitude E4310              | [8dbe3e01fa](https://linux-hardware.org/?probe=8dbe3e01fa) | Mar 08, 2023 |
| ASUSTek       | K54HR                       | [a7c688e9be](https://linux-hardware.org/?probe=a7c688e9be) | Mar 08, 2023 |
| Google        | Candy                       | [e74102ff2c](https://linux-hardware.org/?probe=e74102ff2c) | Mar 07, 2023 |
| Lenovo        | ThinkPad X240 20AMA3PVAR    | [367f53195a](https://linux-hardware.org/?probe=367f53195a) | Mar 07, 2023 |
| Lenovo        | ThinkPad L480 20LS001AMX    | [3f1ebc8271](https://linux-hardware.org/?probe=3f1ebc8271) | Mar 07, 2023 |
| Google        | Lillipup                    | [33350c987b](https://linux-hardware.org/?probe=33350c987b) | Mar 07, 2023 |
| Packard Be... | EasyNote TM82               | [33de288525](https://linux-hardware.org/?probe=33de288525) | Mar 07, 2023 |
| YJKC          | vBOOK Plus RVP7             | [acdf0dca1d](https://linux-hardware.org/?probe=acdf0dca1d) | Mar 06, 2023 |
| Google        | Lillipup                    | [214481f959](https://linux-hardware.org/?probe=214481f959) | Mar 06, 2023 |
| Clevo         | W251EFQ/W270EFQ             | [df192a1871](https://linux-hardware.org/?probe=df192a1871) | Mar 05, 2023 |
| Clevo         | W251EFQ/W270EFQ             | [12c8945329](https://linux-hardware.org/?probe=12c8945329) | Mar 05, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [657175938b](https://linux-hardware.org/?probe=657175938b) | Mar 05, 2023 |
| Timi          | TM1701                      | [4faac58613](https://linux-hardware.org/?probe=4faac58613) | Mar 04, 2023 |
| Lenovo        | ThinkPad X201 3680Z38       | [414dc8dc29](https://linux-hardware.org/?probe=414dc8dc29) | Mar 04, 2023 |
| Lenovo        | ThinkPad X201 3680Z38       | [3e60e33df2](https://linux-hardware.org/?probe=3e60e33df2) | Mar 04, 2023 |
| ASUSTek       | X550CL                      | [c16eae7537](https://linux-hardware.org/?probe=c16eae7537) | Mar 04, 2023 |
| HP            | EliteBook 8570p             | [767045c44e](https://linux-hardware.org/?probe=767045c44e) | Mar 03, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [1237954f03](https://linux-hardware.org/?probe=1237954f03) | Mar 03, 2023 |
| ASUSTek       | UX331UA                     | [310d69ff6f](https://linux-hardware.org/?probe=310d69ff6f) | Mar 03, 2023 |
| Lenovo        | ThinkPad X230 2333BR3       | [a3b6a280c1](https://linux-hardware.org/?probe=a3b6a280c1) | Mar 02, 2023 |
| HP            | Notebook                    | [453811c44a](https://linux-hardware.org/?probe=453811c44a) | Mar 02, 2023 |
| MSI           | GF63 Thin 11UC              | [188ba8d836](https://linux-hardware.org/?probe=188ba8d836) | Mar 02, 2023 |
| MSI           | GF63 Thin 11UC              | [0ad3a8182e](https://linux-hardware.org/?probe=0ad3a8182e) | Mar 02, 2023 |
| ASUSTek       | T100HAN                     | [5729d41d01](https://linux-hardware.org/?probe=5729d41d01) | Mar 02, 2023 |
| Toshiba       | Satellite A100              | [51e1183b15](https://linux-hardware.org/?probe=51e1183b15) | Mar 02, 2023 |
| ASUSTek       | UX331UA                     | [52c7446693](https://linux-hardware.org/?probe=52c7446693) | Mar 02, 2023 |
| Lenovo        | ThinkPad X230 2333BR3       | [7b17e49d0f](https://linux-hardware.org/?probe=7b17e49d0f) | Mar 02, 2023 |
| ASUSTek       | X200MA                      | [95b0a4d944](https://linux-hardware.org/?probe=95b0a4d944) | Mar 02, 2023 |
| ASUSTek       | ROG Strix G713IH_G713IH     | [e9b7ee04ec](https://linux-hardware.org/?probe=e9b7ee04ec) | Mar 01, 2023 |
| Toshiba       | Satellite S55t-B            | [69734289ba](https://linux-hardware.org/?probe=69734289ba) | Mar 01, 2023 |
| MSI           | Raider GE66 12UHS           | [3fcfdd9fba](https://linux-hardware.org/?probe=3fcfdd9fba) | Mar 01, 2023 |
| ASUSTek       | T100HAN                     | [a8b1a02128](https://linux-hardware.org/?probe=a8b1a02128) | Mar 01, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [c698fc199a](https://linux-hardware.org/?probe=c698fc199a) | Feb 28, 2023 |
| ASUSTek       | T100HAN                     | [4f835a4f35](https://linux-hardware.org/?probe=4f835a4f35) | Feb 28, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [7478549a38](https://linux-hardware.org/?probe=7478549a38) | Feb 28, 2023 |
| Dell          | Latitude E6440              | [80131cd2a4](https://linux-hardware.org/?probe=80131cd2a4) | Feb 28, 2023 |
| Dell          | Inspiron 3793               | [d7b51f6048](https://linux-hardware.org/?probe=d7b51f6048) | Feb 27, 2023 |
| HP            | Pavilion dv7                | [d5da5f62b8](https://linux-hardware.org/?probe=d5da5f62b8) | Feb 27, 2023 |
| Acer          | TravelMate B113             | [31691f9681](https://linux-hardware.org/?probe=31691f9681) | Feb 27, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [42acb38635](https://linux-hardware.org/?probe=42acb38635) | Feb 27, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [e8c76a33fe](https://linux-hardware.org/?probe=e8c76a33fe) | Feb 27, 2023 |
| Dell          | Vostro 1540                 | [8f09ea4351](https://linux-hardware.org/?probe=8f09ea4351) | Feb 27, 2023 |
| HP            | ENVY m7 Notebook            | [14374fbcc8](https://linux-hardware.org/?probe=14374fbcc8) | Feb 27, 2023 |
| Lenovo        | V570 1066EDG                | [deb326cc4b](https://linux-hardware.org/?probe=deb326cc4b) | Feb 26, 2023 |
| Lenovo        | V570 1066EDG                | [cc220b6122](https://linux-hardware.org/?probe=cc220b6122) | Feb 26, 2023 |
| HP            | 620                         | [e3bf80caf7](https://linux-hardware.org/?probe=e3bf80caf7) | Feb 25, 2023 |
| Dell          | Latitude E6440              | [a4139e4774](https://linux-hardware.org/?probe=a4139e4774) | Feb 25, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [eca93ca661](https://linux-hardware.org/?probe=eca93ca661) | Feb 25, 2023 |
| HP            | Laptop 15-dy2xxx            | [7f88a11698](https://linux-hardware.org/?probe=7f88a11698) | Feb 25, 2023 |
| Digibras      | NH4CU03                     | [85ea6dded1](https://linux-hardware.org/?probe=85ea6dded1) | Feb 24, 2023 |
| Digibras      | NH4CU03                     | [1fb9cfd7d4](https://linux-hardware.org/?probe=1fb9cfd7d4) | Feb 24, 2023 |
| HP            | Laptop 14-ck0xxx            | [bafb67390c](https://linux-hardware.org/?probe=bafb67390c) | Feb 24, 2023 |
| HP            | Pavilion g6                 | [602cac9f15](https://linux-hardware.org/?probe=602cac9f15) | Feb 24, 2023 |
| Apple         | MacBookPro12,1              | [3b27d3609f](https://linux-hardware.org/?probe=3b27d3609f) | Feb 24, 2023 |
| HP            | ProBook 4545s               | [0f56422e2d](https://linux-hardware.org/?probe=0f56422e2d) | Feb 24, 2023 |
| ASUSTek       | T100TAF                     | [4fce660f2d](https://linux-hardware.org/?probe=4fce660f2d) | Feb 23, 2023 |
| Dell          | Latitude 7480               | [fd80b301db](https://linux-hardware.org/?probe=fd80b301db) | Feb 23, 2023 |
| Lenovo        | G500 20236                  | [294c5c45e6](https://linux-hardware.org/?probe=294c5c45e6) | Feb 23, 2023 |
| DERE          | V14                         | [bb2d40e676](https://linux-hardware.org/?probe=bb2d40e676) | Feb 22, 2023 |
| Teclast       | F7                          | [3f5fdc3aa9](https://linux-hardware.org/?probe=3f5fdc3aa9) | Feb 21, 2023 |
| HP            | Laptop 15-dy2xxx            | [5d32bc7f7c](https://linux-hardware.org/?probe=5d32bc7f7c) | Feb 21, 2023 |
| HP            | Laptop 15-dy2xxx            | [a00e724475](https://linux-hardware.org/?probe=a00e724475) | Feb 21, 2023 |
| Dell          | System XPS L502X            | [7352f47bb0](https://linux-hardware.org/?probe=7352f47bb0) | Feb 20, 2023 |
| Apple         | MacBookAir7,1               | [5002433b97](https://linux-hardware.org/?probe=5002433b97) | Feb 20, 2023 |
| HP            | 620                         | [c3dae62545](https://linux-hardware.org/?probe=c3dae62545) | Feb 20, 2023 |
| Toshiba       | PORTEGE Z30-A               | [882e2c977d](https://linux-hardware.org/?probe=882e2c977d) | Feb 20, 2023 |
| Dell          | Inspiron N4050              | [115fa87a77](https://linux-hardware.org/?probe=115fa87a77) | Feb 20, 2023 |
| Dell          | Latitude E5440              | [10b94a411c](https://linux-hardware.org/?probe=10b94a411c) | Feb 20, 2023 |
| HP            | Laptop 15s-dr0xxx           | [6733a448f9](https://linux-hardware.org/?probe=6733a448f9) | Feb 20, 2023 |
| Packard Be... | EasyNote TS11HR             | [d20a6e81f8](https://linux-hardware.org/?probe=d20a6e81f8) | Feb 19, 2023 |
| Toshiba       | Satellite L50-B             | [3c53a60245](https://linux-hardware.org/?probe=3c53a60245) | Feb 19, 2023 |
| Lenovo        | ThinkPad T460 20FN003LMZ    | [1752223e74](https://linux-hardware.org/?probe=1752223e74) | Feb 19, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [752cdf5b2b](https://linux-hardware.org/?probe=752cdf5b2b) | Feb 19, 2023 |
| Multilaser    | PC130                       | [3526846c1f](https://linux-hardware.org/?probe=3526846c1f) | Feb 19, 2023 |
| Dell          | Inspiron N4050              | [16350a9c3b](https://linux-hardware.org/?probe=16350a9c3b) | Feb 19, 2023 |
| Lenovo        | ThinkPad T570 20H90002MZ    | [6694311da2](https://linux-hardware.org/?probe=6694311da2) | Feb 19, 2023 |
| Lenovo        | ThinkPad T550 20CK003LMZ    | [e3b00dc0f6](https://linux-hardware.org/?probe=e3b00dc0f6) | Feb 18, 2023 |
| HP            | Unknown                     | [3fea6a053b](https://linux-hardware.org/?probe=3fea6a053b) | Feb 18, 2023 |
| Lenovo        | ThinkPad T560 20FJS24T00    | [91a1aa0a0d](https://linux-hardware.org/?probe=91a1aa0a0d) | Feb 18, 2023 |
| Lenovo        | ThinkPad X260 20F600A2MZ    | [bba1f53762](https://linux-hardware.org/?probe=bba1f53762) | Feb 18, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [215ae5796f](https://linux-hardware.org/?probe=215ae5796f) | Feb 18, 2023 |
| Dell          | Inspiron 14 Plus 7420       | [59387e9081](https://linux-hardware.org/?probe=59387e9081) | Feb 18, 2023 |
| Medion        | E7220                       | [289b7dc6aa](https://linux-hardware.org/?probe=289b7dc6aa) | Feb 17, 2023 |
| Acer          | Aspire 5738                 | [48bbbc04c4](https://linux-hardware.org/?probe=48bbbc04c4) | Feb 17, 2023 |
| ASUSTek       | X450LD                      | [b4fb1ddc5a](https://linux-hardware.org/?probe=b4fb1ddc5a) | Feb 17, 2023 |
| Google        | Robo                        | [303c72db93](https://linux-hardware.org/?probe=303c72db93) | Feb 17, 2023 |
| HP            | Laptop 15-bs1xx             | [88d9514231](https://linux-hardware.org/?probe=88d9514231) | Feb 17, 2023 |
| Dell          | Inspiron 3793               | [b997f44969](https://linux-hardware.org/?probe=b997f44969) | Feb 16, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [8043264215](https://linux-hardware.org/?probe=8043264215) | Feb 16, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [c08ad0f295](https://linux-hardware.org/?probe=c08ad0f295) | Feb 16, 2023 |
| HP            | ENVY TS Sleekbook 4         | [1189701feb](https://linux-hardware.org/?probe=1189701feb) | Feb 15, 2023 |
| Acer          | Extensa 5230                | [2716bcf519](https://linux-hardware.org/?probe=2716bcf519) | Feb 15, 2023 |
| Dell          | Latitude 3320               | [fecee449d4](https://linux-hardware.org/?probe=fecee449d4) | Feb 15, 2023 |
| Lenovo        | ThinkPad L480 20LS001AMX    | [6c1c0027b1](https://linux-hardware.org/?probe=6c1c0027b1) | Feb 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [c2d957f650](https://linux-hardware.org/?probe=c2d957f650) | Feb 15, 2023 |
| Dell          | System XPS L502X            | [2ea016be2a](https://linux-hardware.org/?probe=2ea016be2a) | Feb 14, 2023 |
| Apple         | MacBook2,1                  | [915e87767b](https://linux-hardware.org/?probe=915e87767b) | Feb 14, 2023 |
| Dell          | Latitude 5480               | [03123ee601](https://linux-hardware.org/?probe=03123ee601) | Feb 14, 2023 |
| Samsung       | 700T1C                      | [66c15f037d](https://linux-hardware.org/?probe=66c15f037d) | Feb 14, 2023 |
| Samsung       | 700T1C                      | [9e154ea3a4](https://linux-hardware.org/?probe=9e154ea3a4) | Feb 14, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [d1edc30dac](https://linux-hardware.org/?probe=d1edc30dac) | Feb 13, 2023 |
| Lenovo        | IdeaPad U330p 20267         | [de30205f54](https://linux-hardware.org/?probe=de30205f54) | Feb 12, 2023 |
| Lenovo        | IdeaPad U330p 20267         | [19700ab1bd](https://linux-hardware.org/?probe=19700ab1bd) | Feb 12, 2023 |
| HP            | Compaq 6730b (NB034ET#UU... | [baa5f72e80](https://linux-hardware.org/?probe=baa5f72e80) | Feb 12, 2023 |
| HP            | Notebook                    | [a17adfd867](https://linux-hardware.org/?probe=a17adfd867) | Feb 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [6f7c0f381e](https://linux-hardware.org/?probe=6f7c0f381e) | Feb 12, 2023 |
| HP            | Laptop 15-dy2xxx            | [131d5052d1](https://linux-hardware.org/?probe=131d5052d1) | Feb 11, 2023 |
| Dell          | Inspiron 16 5625            | [d4951f7e68](https://linux-hardware.org/?probe=d4951f7e68) | Feb 11, 2023 |
| Dell          | Vostro 1520                 | [698006ab18](https://linux-hardware.org/?probe=698006ab18) | Feb 11, 2023 |
| Lenovo        | ThinkPad L480 20LS001AMX    | [518f413d2f](https://linux-hardware.org/?probe=518f413d2f) | Feb 11, 2023 |
| Lenovo        | ThinkPad L480 20LS001AMX    | [a24d7423c4](https://linux-hardware.org/?probe=a24d7423c4) | Feb 11, 2023 |
| Dell          | Latitude E6400              | [8c489c529a](https://linux-hardware.org/?probe=8c489c529a) | Feb 11, 2023 |
| Acer          | TravelMate P253             | [8947050124](https://linux-hardware.org/?probe=8947050124) | Feb 11, 2023 |
| HONOR         | HLYL-WXX9                   | [9d916e8e03](https://linux-hardware.org/?probe=9d916e8e03) | Feb 10, 2023 |
| Acer          | Aspire 5720                 | [9b71ff828e](https://linux-hardware.org/?probe=9b71ff828e) | Feb 10, 2023 |
| HP            | Pavilion Laptop 14-ce0xx... | [49b463f14c](https://linux-hardware.org/?probe=49b463f14c) | Feb 10, 2023 |
| Acer          | Predator G3-571             | [50fe192ea1](https://linux-hardware.org/?probe=50fe192ea1) | Feb 10, 2023 |
| Lenovo        | Yoga 500-14ACL 80NA         | [3bdbc623a8](https://linux-hardware.org/?probe=3bdbc623a8) | Feb 10, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | [8513e7eb92](https://linux-hardware.org/?probe=8513e7eb92) | Feb 09, 2023 |
| Positivo      | Smash2                      | [1948e9489d](https://linux-hardware.org/?probe=1948e9489d) | Feb 09, 2023 |
| Positivo      | Smash2                      | [47760ee46f](https://linux-hardware.org/?probe=47760ee46f) | Feb 09, 2023 |
| Lenovo        | ThinkPad Edge E430 62715... | [5c9ca6cd47](https://linux-hardware.org/?probe=5c9ca6cd47) | Feb 09, 2023 |
| HP            | Pavilion dv7                | [6b7ba3365e](https://linux-hardware.org/?probe=6b7ba3365e) | Feb 08, 2023 |
| Acer          | Aspire 5755G                | [0d0c6fe86c](https://linux-hardware.org/?probe=0d0c6fe86c) | Feb 08, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | [26f7ad82d9](https://linux-hardware.org/?probe=26f7ad82d9) | Feb 08, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | [d54546bce9](https://linux-hardware.org/?probe=d54546bce9) | Feb 08, 2023 |
| Lenovo        | V570 1066EDG                | [f963048c4c](https://linux-hardware.org/?probe=f963048c4c) | Feb 08, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [e32b918f95](https://linux-hardware.org/?probe=e32b918f95) | Feb 07, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | [c0aab06a5c](https://linux-hardware.org/?probe=c0aab06a5c) | Feb 07, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | [830072137a](https://linux-hardware.org/?probe=830072137a) | Feb 07, 2023 |
| Lenovo        | ThinkPad Edge E430 62715... | [ae78404854](https://linux-hardware.org/?probe=ae78404854) | Feb 07, 2023 |
| Lenovo        | ThinkPad Edge E430 62715... | [b2c3e0fa85](https://linux-hardware.org/?probe=b2c3e0fa85) | Feb 07, 2023 |
| Multilaser    | UB23X LINUX                 | [d630a4eeff](https://linux-hardware.org/?probe=d630a4eeff) | Feb 07, 2023 |
| Lenovo        | V570 1066EDG                | [e3ffc73e43](https://linux-hardware.org/?probe=e3ffc73e43) | Feb 06, 2023 |
| Acer          | Okinawa                     | [eab799e6dc](https://linux-hardware.org/?probe=eab799e6dc) | Feb 06, 2023 |
| Sony          | VGN-Z31XN_B                 | [d7795277f3](https://linux-hardware.org/?probe=d7795277f3) | Feb 06, 2023 |
| Multilaser    | MLSH1H LINUX                | [0e47e3afd8](https://linux-hardware.org/?probe=0e47e3afd8) | Feb 06, 2023 |
| MSI           | GF63 Thin 11UC              | [a57b142e05](https://linux-hardware.org/?probe=a57b142e05) | Feb 06, 2023 |
| Intel         | Unknown                     | [a1044e362f](https://linux-hardware.org/?probe=a1044e362f) | Feb 06, 2023 |
| Sony          | VPCEG36FX                   | [d760d9e79b](https://linux-hardware.org/?probe=d760d9e79b) | Feb 06, 2023 |
| Acer          | TravelMate P253             | [050d7b5d68](https://linux-hardware.org/?probe=050d7b5d68) | Feb 06, 2023 |
| Lenovo        | ThinkPad T420 4236KU9       | [f536be92d0](https://linux-hardware.org/?probe=f536be92d0) | Feb 06, 2023 |
| Lenovo        | V570 1066EDG                | [00714979fe](https://linux-hardware.org/?probe=00714979fe) | Feb 06, 2023 |
| Acer          | One S1002                   | [2d98ceddca](https://linux-hardware.org/?probe=2d98ceddca) | Feb 05, 2023 |
| Insyde        | CherryTrail                 | [b3ad379bdc](https://linux-hardware.org/?probe=b3ad379bdc) | Feb 05, 2023 |
| Lenovo        | V14-IIL 82C4                | [d33be0bc3f](https://linux-hardware.org/?probe=d33be0bc3f) | Feb 05, 2023 |
| Apple         | MacBookPro5,3               | [e8b8e1b8e5](https://linux-hardware.org/?probe=e8b8e1b8e5) | Feb 04, 2023 |
| Apple         | MacBookPro5,3               | [0f57b84fe7](https://linux-hardware.org/?probe=0f57b84fe7) | Feb 04, 2023 |
| Lenovo        | 14w 81MQ00AVCL              | [bd59f68ce8](https://linux-hardware.org/?probe=bd59f68ce8) | Feb 03, 2023 |
| Dell          | Latitude D630               | [aa435d7701](https://linux-hardware.org/?probe=aa435d7701) | Feb 03, 2023 |
| Dell          | Latitude D630               | [b191402036](https://linux-hardware.org/?probe=b191402036) | Feb 03, 2023 |
| Acer          | Aspire A517-51G             | [7555fafa98](https://linux-hardware.org/?probe=7555fafa98) | Feb 03, 2023 |
| Dell          | Inspiron 5537               | [5bfa4ad142](https://linux-hardware.org/?probe=5bfa4ad142) | Feb 02, 2023 |
| Intel         | Unknown                     | [ba5bda9424](https://linux-hardware.org/?probe=ba5bda9424) | Feb 02, 2023 |
| Sony          | VGN-Z31XN_B                 | [324ab7fbd3](https://linux-hardware.org/?probe=324ab7fbd3) | Feb 02, 2023 |
| HUAWEI        | KLVL-WXXW                   | [741a1b90bd](https://linux-hardware.org/?probe=741a1b90bd) | Feb 02, 2023 |
| MSI           | GF63 Thin 11UC              | [b34b3228d3](https://linux-hardware.org/?probe=b34b3228d3) | Feb 01, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [95e019beb2](https://linux-hardware.org/?probe=95e019beb2) | Feb 01, 2023 |
| Dell          | Latitude 7490               | [b2c18d04be](https://linux-hardware.org/?probe=b2c18d04be) | Feb 01, 2023 |
| Dell          | Latitude 7490               | [050126f7f7](https://linux-hardware.org/?probe=050126f7f7) | Feb 01, 2023 |
| MSI           | Raider GE66 12UHS           | [75e83dae8b](https://linux-hardware.org/?probe=75e83dae8b) | Feb 01, 2023 |
| Dell          | Vostro 1520                 | [3fab7107b7](https://linux-hardware.org/?probe=3fab7107b7) | Feb 01, 2023 |
| Acer          | Aspire A315-53              | [d221bc6b8d](https://linux-hardware.org/?probe=d221bc6b8d) | Feb 01, 2023 |
| Dell          | Latitude E6540              | [156a047a82](https://linux-hardware.org/?probe=156a047a82) | Jan 31, 2023 |
| Dell          | Vostro 3700                 | [a663152b7c](https://linux-hardware.org/?probe=a663152b7c) | Jan 31, 2023 |
| Dell          | Vostro 3700                 | [ae3838cc5d](https://linux-hardware.org/?probe=ae3838cc5d) | Jan 31, 2023 |
| HP            | Compaq 6730s                | [1b083e5b64](https://linux-hardware.org/?probe=1b083e5b64) | Jan 31, 2023 |
| HP            | Compaq 6730s                | [ced2899d20](https://linux-hardware.org/?probe=ced2899d20) | Jan 31, 2023 |
| HP            | Pavilion Notebook           | [912213d849](https://linux-hardware.org/?probe=912213d849) | Jan 30, 2023 |
| HP            | Pavilion Notebook           | [456415a23e](https://linux-hardware.org/?probe=456415a23e) | Jan 30, 2023 |
| Dell          | Latitude E6520              | [f042c5966b](https://linux-hardware.org/?probe=f042c5966b) | Jan 30, 2023 |
| HP            | EliteBook 840 G5            | [7b2b210afd](https://linux-hardware.org/?probe=7b2b210afd) | Jan 30, 2023 |
| Lenovo        | ThinkPad T460s 20FAS1F20... | [39b709296b](https://linux-hardware.org/?probe=39b709296b) | Jan 30, 2023 |
| Dell          | Inspiron 5770               | [b5612c2501](https://linux-hardware.org/?probe=b5612c2501) | Jan 29, 2023 |
| Lenovo        | IdeaPad Y560                | [47438e081a](https://linux-hardware.org/?probe=47438e081a) | Jan 29, 2023 |
| ASUSTek       | G750JX                      | [d868c23c4b](https://linux-hardware.org/?probe=d868c23c4b) | Jan 29, 2023 |
| Dell          | Precision 5530              | [92399ea8dc](https://linux-hardware.org/?probe=92399ea8dc) | Jan 29, 2023 |
| Lenovo        | IdeaPad Y560                | [621aca8707](https://linux-hardware.org/?probe=621aca8707) | Jan 29, 2023 |
| Lenovo        | IdeaPad Y560                | [55fe252b4e](https://linux-hardware.org/?probe=55fe252b4e) | Jan 29, 2023 |
| Toshiba       | QOSMIO X770                 | [62b104b3d2](https://linux-hardware.org/?probe=62b104b3d2) | Jan 29, 2023 |
| Toshiba       | QOSMIO X770                 | [b7cf9bee5c](https://linux-hardware.org/?probe=b7cf9bee5c) | Jan 28, 2023 |
| Dell          | Latitude E5430 non-vPro     | [ae644e258a](https://linux-hardware.org/?probe=ae644e258a) | Jan 28, 2023 |
| Acer          | Swift SF314-511             | [eeaf26e835](https://linux-hardware.org/?probe=eeaf26e835) | Jan 28, 2023 |
| Dell          | Precision 5530              | [a9a54c5b7f](https://linux-hardware.org/?probe=a9a54c5b7f) | Jan 28, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [a6f188ab67](https://linux-hardware.org/?probe=a6f188ab67) | Jan 28, 2023 |
| Lenovo        | IdeaPad 3 17ABA7 82RQ       | [57e0449f0f](https://linux-hardware.org/?probe=57e0449f0f) | Jan 28, 2023 |
| Dell          | Vostro 1520                 | [b2eb47268c](https://linux-hardware.org/?probe=b2eb47268c) | Jan 27, 2023 |
| Dell          | Vostro 1520                 | [6a8408404e](https://linux-hardware.org/?probe=6a8408404e) | Jan 27, 2023 |
| I-Life Dig... | ZED AIR 2 SABMS             | [8bd062dd40](https://linux-hardware.org/?probe=8bd062dd40) | Jan 27, 2023 |
| Dell          | Latitude E7470              | [4245585e75](https://linux-hardware.org/?probe=4245585e75) | Jan 27, 2023 |
| Lenovo        | ThinkPad R61 8918DEG        | [5e0dfe2630](https://linux-hardware.org/?probe=5e0dfe2630) | Jan 27, 2023 |
| Apple         | MacBook8,1                  | [02cd28549c](https://linux-hardware.org/?probe=02cd28549c) | Jan 27, 2023 |
| HP            | Notebook                    | [4c632128bf](https://linux-hardware.org/?probe=4c632128bf) | Jan 26, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | [de7bee1cd6](https://linux-hardware.org/?probe=de7bee1cd6) | Jan 26, 2023 |
| Alienware     | M11xR3                      | [634b7f8eb0](https://linux-hardware.org/?probe=634b7f8eb0) | Jan 26, 2023 |
| Lenovo        | ThinkPad R61 8918DEG        | [c29f24d0ca](https://linux-hardware.org/?probe=c29f24d0ca) | Jan 26, 2023 |
| HP            | 625                         | [06c4fa5119](https://linux-hardware.org/?probe=06c4fa5119) | Jan 25, 2023 |
| Google        | Blorb                       | [adae28c837](https://linux-hardware.org/?probe=adae28c837) | Jan 25, 2023 |
| HP            | EliteBook Folio 9470m       | [5dfd026f77](https://linux-hardware.org/?probe=5dfd026f77) | Jan 25, 2023 |
| Lenovo        | Z51-70 80K6                 | [c083024afa](https://linux-hardware.org/?probe=c083024afa) | Jan 25, 2023 |
| Sony          | SVE1513C5E                  | [48ee443aef](https://linux-hardware.org/?probe=48ee443aef) | Jan 25, 2023 |
| Lenovo        | ThinkPad T470 20HES0PF00    | [61d7aa3ef9](https://linux-hardware.org/?probe=61d7aa3ef9) | Jan 25, 2023 |
| Google        | Kip                         | [b450bb3bcf](https://linux-hardware.org/?probe=b450bb3bcf) | Jan 24, 2023 |
| Google        | Kip                         | [bf5c5ab5e6](https://linux-hardware.org/?probe=bf5c5ab5e6) | Jan 24, 2023 |
| I-Life Dig... | ZED AIR 2 SABMS             | [da316254bb](https://linux-hardware.org/?probe=da316254bb) | Jan 24, 2023 |
| HP            | Laptop 15-dy2xxx            | [af9518a90a](https://linux-hardware.org/?probe=af9518a90a) | Jan 24, 2023 |
| Dell          | Latitude E7470              | [db73b82761](https://linux-hardware.org/?probe=db73b82761) | Jan 24, 2023 |
| Dell          | Latitude E7470              | [6fd520f670](https://linux-hardware.org/?probe=6fd520f670) | Jan 23, 2023 |
| Acer          | Aspire SW5-012              | [247455614c](https://linux-hardware.org/?probe=247455614c) | Jan 23, 2023 |
| HP            | ProBook 440 G5              | [788d350490](https://linux-hardware.org/?probe=788d350490) | Jan 23, 2023 |
| Dell          | Latitude E7470              | [525bcdd915](https://linux-hardware.org/?probe=525bcdd915) | Jan 23, 2023 |
| ASUSTek       | T300CHI                     | [bc020f2d3e](https://linux-hardware.org/?probe=bc020f2d3e) | Jan 23, 2023 |
| Acer          | Aspire A315-59              | [20b73bd156](https://linux-hardware.org/?probe=20b73bd156) | Jan 23, 2023 |
| Lenovo        | E51-80 80QB                 | [37073c4323](https://linux-hardware.org/?probe=37073c4323) | Jan 22, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [6d5ca0b2e3](https://linux-hardware.org/?probe=6d5ca0b2e3) | Jan 22, 2023 |
| Packard Be... | EasyNote TE69KB             | [8363dc95c3](https://linux-hardware.org/?probe=8363dc95c3) | Jan 22, 2023 |
| Dell          | Precision M6800             | [a6beff01de](https://linux-hardware.org/?probe=a6beff01de) | Jan 22, 2023 |
| HP            | 625                         | [838d72399b](https://linux-hardware.org/?probe=838d72399b) | Jan 22, 2023 |
| Lenovo        | V110-15IAP 80TG             | [1707a21fed](https://linux-hardware.org/?probe=1707a21fed) | Jan 22, 2023 |
| Itautec       | Infoway w7430               | [b33318e6e0](https://linux-hardware.org/?probe=b33318e6e0) | Jan 22, 2023 |
| HP            | 625                         | [9a8a243973](https://linux-hardware.org/?probe=9a8a243973) | Jan 21, 2023 |
| I-Life Dig... | ZED AIR 2 SABMS             | [aa8fbd29c9](https://linux-hardware.org/?probe=aa8fbd29c9) | Jan 21, 2023 |
| Dell          | Inspiron 1525               | [548d331968](https://linux-hardware.org/?probe=548d331968) | Jan 21, 2023 |
| ASUSTek       | X453MA                      | [94b155d9c2](https://linux-hardware.org/?probe=94b155d9c2) | Jan 21, 2023 |
| Chuwi         | GemiBook Pro                | [f52614c5aa](https://linux-hardware.org/?probe=f52614c5aa) | Jan 21, 2023 |
| Timi          | Mi Notebook Pro             | [1db1382f0b](https://linux-hardware.org/?probe=1db1382f0b) | Jan 21, 2023 |
| Lenovo        | G560 20042                  | [9c78155cfe](https://linux-hardware.org/?probe=9c78155cfe) | Jan 20, 2023 |
| Lenovo        | G560 20042                  | [61e3ee0517](https://linux-hardware.org/?probe=61e3ee0517) | Jan 20, 2023 |
| ASUSTek       | G74Sx                       | [f3af245bf8](https://linux-hardware.org/?probe=f3af245bf8) | Jan 20, 2023 |
| Acer          | Aspire A317-33              | [b7147af4f6](https://linux-hardware.org/?probe=b7147af4f6) | Jan 20, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [d7344938fb](https://linux-hardware.org/?probe=d7344938fb) | Jan 19, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [9b3bbccece](https://linux-hardware.org/?probe=9b3bbccece) | Jan 19, 2023 |
| Lenovo        | Z51-70 80K6                 | [90746298fc](https://linux-hardware.org/?probe=90746298fc) | Jan 19, 2023 |
| HP            | ProBook 4740s               | [3392f975ec](https://linux-hardware.org/?probe=3392f975ec) | Jan 19, 2023 |
| Acer          | Aspire E5-774G              | [f3ab78c392](https://linux-hardware.org/?probe=f3ab78c392) | Jan 19, 2023 |
| Lenovo        | B51-80 80LM                 | [4908236396](https://linux-hardware.org/?probe=4908236396) | Jan 19, 2023 |
| Lenovo        | B51-80 80LM                 | [9e17ffeecc](https://linux-hardware.org/?probe=9e17ffeecc) | Jan 19, 2023 |
| Lenovo        | V110-15IAP 80TG             | [cfe9a9d924](https://linux-hardware.org/?probe=cfe9a9d924) | Jan 18, 2023 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [7be5d0d09b](https://linux-hardware.org/?probe=7be5d0d09b) | Jan 18, 2023 |
| HP            | 15                          | [cebe1b150e](https://linux-hardware.org/?probe=cebe1b150e) | Jan 18, 2023 |
| Packard Be... | EasyNote TM82               | [49ae8de234](https://linux-hardware.org/?probe=49ae8de234) | Jan 18, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [6f91cb09e7](https://linux-hardware.org/?probe=6f91cb09e7) | Jan 18, 2023 |
| Google        | Kip                         | [e74935629a](https://linux-hardware.org/?probe=e74935629a) | Jan 17, 2023 |
| Google        | Kip                         | [558cff5048](https://linux-hardware.org/?probe=558cff5048) | Jan 17, 2023 |
| HP            | Pavilion dv7                | [2efb4b16de](https://linux-hardware.org/?probe=2efb4b16de) | Jan 17, 2023 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [5ebc1885c3](https://linux-hardware.org/?probe=5ebc1885c3) | Jan 17, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DL... | [e9e902c625](https://linux-hardware.org/?probe=e9e902c625) | Jan 17, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DL... | [00ebda8ae9](https://linux-hardware.org/?probe=00ebda8ae9) | Jan 17, 2023 |
| Lenovo        | IdeaPad 310-15ABR 80ST      | [473ae331ec](https://linux-hardware.org/?probe=473ae331ec) | Jan 16, 2023 |
| Wortmann      | Mobile 1524                 | [17fc7e2f75](https://linux-hardware.org/?probe=17fc7e2f75) | Jan 16, 2023 |
| Lenovo        | G560 0679                   | [26e16a5898](https://linux-hardware.org/?probe=26e16a5898) | Jan 15, 2023 |
| Dell          | Inspiron 7437               | [df8d69926f](https://linux-hardware.org/?probe=df8d69926f) | Jan 15, 2023 |
| Dell          | Inspiron 7437               | [0670d91eb0](https://linux-hardware.org/?probe=0670d91eb0) | Jan 15, 2023 |
| Apple         | MacBookPro5,5               | [2f2fec82c8](https://linux-hardware.org/?probe=2f2fec82c8) | Jan 15, 2023 |
| Lenovo        | IdeaPadFlex 15D 20334       | [331b5e3efa](https://linux-hardware.org/?probe=331b5e3efa) | Jan 14, 2023 |
| ASUSTek       | K75VM                       | [6cd0e1793b](https://linux-hardware.org/?probe=6cd0e1793b) | Jan 14, 2023 |
| Lenovo        | IdeaPadFlex 15D 20334       | [19531b68b1](https://linux-hardware.org/?probe=19531b68b1) | Jan 14, 2023 |
| HP            | EliteBook 745 G5            | [941c62872e](https://linux-hardware.org/?probe=941c62872e) | Jan 14, 2023 |
| HP            | ZBook 17 G3                 | [6c53f137fd](https://linux-hardware.org/?probe=6c53f137fd) | Jan 14, 2023 |
| HP            | Presario F500 (GF795EA#A... | [588148e349](https://linux-hardware.org/?probe=588148e349) | Jan 14, 2023 |
| Acer          | Swift SF314-511             | [8a4bbb603e](https://linux-hardware.org/?probe=8a4bbb603e) | Jan 14, 2023 |
| Sony          | SVE1513U1ESI                | [d1c4a0dc83](https://linux-hardware.org/?probe=d1c4a0dc83) | Jan 14, 2023 |
| ASUSTek       | ZenBook UX325SA_UM325SA     | [ddf679df3a](https://linux-hardware.org/?probe=ddf679df3a) | Jan 14, 2023 |
| Acer          | Swift SF314-511             | [baa87ed4e0](https://linux-hardware.org/?probe=baa87ed4e0) | Jan 13, 2023 |
| Acer          | Swift SF314-511             | [cb94045e18](https://linux-hardware.org/?probe=cb94045e18) | Jan 13, 2023 |
| Fujitsu       | FARQ02010                   | [5d3f5fcee2](https://linux-hardware.org/?probe=5d3f5fcee2) | Jan 13, 2023 |
| ASUSTek       | K93SV                       | [250b4a09a0](https://linux-hardware.org/?probe=250b4a09a0) | Jan 13, 2023 |
| Kiano         | Elegance 13.3               | [2e77ce51b9](https://linux-hardware.org/?probe=2e77ce51b9) | Jan 13, 2023 |
| HP            | Laptop 14-bw0xx             | [0092ec8702](https://linux-hardware.org/?probe=0092ec8702) | Jan 12, 2023 |
| Acer          | Aspire 2920                 | [0766ea34c6](https://linux-hardware.org/?probe=0766ea34c6) | Jan 12, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [fb5857252b](https://linux-hardware.org/?probe=fb5857252b) | Jan 12, 2023 |
| Samsung       | R520/R522/R620              | [78eb96d148](https://linux-hardware.org/?probe=78eb96d148) | Jan 11, 2023 |
| Samsung       | R520/R522/R620              | [9dfcb68d9a](https://linux-hardware.org/?probe=9dfcb68d9a) | Jan 11, 2023 |
| HP            | Notebook                    | [8df5d522da](https://linux-hardware.org/?probe=8df5d522da) | Jan 10, 2023 |
| HP            | Notebook                    | [c58dde8021](https://linux-hardware.org/?probe=c58dde8021) | Jan 10, 2023 |
| Dell          | Inspiron 3583               | [cb037b984e](https://linux-hardware.org/?probe=cb037b984e) | Jan 10, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [04a9deb0c1](https://linux-hardware.org/?probe=04a9deb0c1) | Jan 10, 2023 |
| Dell          | Inspiron 15-3567            | [5aaaf24b85](https://linux-hardware.org/?probe=5aaaf24b85) | Jan 09, 2023 |
| HP            | Pavilion dv6                | [852e84ccaa](https://linux-hardware.org/?probe=852e84ccaa) | Jan 09, 2023 |
| Dell          | Latitude E6510              | [28cceb82e3](https://linux-hardware.org/?probe=28cceb82e3) | Jan 09, 2023 |
| Acer          | Aspire A315-53              | [a8f14a8a8e](https://linux-hardware.org/?probe=a8f14a8a8e) | Jan 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [5bd32eb6f6](https://linux-hardware.org/?probe=5bd32eb6f6) | Jan 08, 2023 |
| ASUSTek       | X555LF                      | [0ff44cdd4f](https://linux-hardware.org/?probe=0ff44cdd4f) | Jan 08, 2023 |
| Lenovo        | IdeaPad 3 17IML05 81WC      | [88ba7d805e](https://linux-hardware.org/?probe=88ba7d805e) | Jan 08, 2023 |
| Lenovo        | IdeaPad 3 17IML05 81WC      | [b5b4c3f6ef](https://linux-hardware.org/?probe=b5b4c3f6ef) | Jan 08, 2023 |
| MSI           | CR62 6M                     | [942ca0f3b3](https://linux-hardware.org/?probe=942ca0f3b3) | Jan 07, 2023 |
| Dell          | Inspiron 5559               | [4c680e9948](https://linux-hardware.org/?probe=4c680e9948) | Jan 07, 2023 |
| HP            | Laptop 17-cp1xxx            | [d699356fd1](https://linux-hardware.org/?probe=d699356fd1) | Jan 07, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | [6148bc3313](https://linux-hardware.org/?probe=6148bc3313) | Jan 06, 2023 |
| Multilaser    | PC024                       | [006690ac84](https://linux-hardware.org/?probe=006690ac84) | Jan 06, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20CD003... | [1afcc520de](https://linux-hardware.org/?probe=1afcc520de) | Jan 05, 2023 |
| Lenovo        | V14-IIL 82C4                | [9b828358df](https://linux-hardware.org/?probe=9b828358df) | Jan 05, 2023 |
| Lenovo        | V14-IIL 82C4                | [7cf92f3f43](https://linux-hardware.org/?probe=7cf92f3f43) | Jan 05, 2023 |
| Multilaser    | PC024                       | [8d9a2a1304](https://linux-hardware.org/?probe=8d9a2a1304) | Jan 05, 2023 |
| Dell          | Precision M90               | [b622160555](https://linux-hardware.org/?probe=b622160555) | Jan 05, 2023 |
| HP            | ProBook 4540s               | [6e2638a12e](https://linux-hardware.org/?probe=6e2638a12e) | Jan 04, 2023 |
| Toshiba       | Satellite C50D-B            | [e4bc0d4130](https://linux-hardware.org/?probe=e4bc0d4130) | Jan 04, 2023 |
| Acer          | Aspire V3-772G              | [4ec59dca55](https://linux-hardware.org/?probe=4ec59dca55) | Jan 04, 2023 |
| Sony          | VPCEB3L1E                   | [e8ac8a5d95](https://linux-hardware.org/?probe=e8ac8a5d95) | Jan 04, 2023 |
| Lenovo        | Z51-70 80K6                 | [7fff20462c](https://linux-hardware.org/?probe=7fff20462c) | Jan 03, 2023 |
| HP            | EliteBook Folio 9470m       | [309e449325](https://linux-hardware.org/?probe=309e449325) | Jan 03, 2023 |
| HP            | Pavilion dv7                | [574f62a8ad](https://linux-hardware.org/?probe=574f62a8ad) | Jan 03, 2023 |
| Apple         | MacBookPro12,1              | [ce3dc1998f](https://linux-hardware.org/?probe=ce3dc1998f) | Jan 02, 2023 |
| HP            | EliteBook 2570p             | [fcf5d132a5](https://linux-hardware.org/?probe=fcf5d132a5) | Jan 02, 2023 |
| Acer          | Aspire 4310                 | [e179184ea3](https://linux-hardware.org/?probe=e179184ea3) | Jan 02, 2023 |
| Dell          | Latitude E5440              | [d8b08abf08](https://linux-hardware.org/?probe=d8b08abf08) | Jan 02, 2023 |
| HP            | Pavilion dv6                | [d735200dcf](https://linux-hardware.org/?probe=d735200dcf) | Jan 01, 2023 |
| HP            | EliteBook 850 G3            | [64c803c589](https://linux-hardware.org/?probe=64c803c589) | Jan 01, 2023 |
| Toshiba       | Satellite C50-B             | [b1007671e3](https://linux-hardware.org/?probe=b1007671e3) | Jan 01, 2023 |
| HP            | EliteBook 2760p             | [91741e63eb](https://linux-hardware.org/?probe=91741e63eb) | Jan 01, 2023 |
| HP            | EliteBook 2760p             | [6ac462efda](https://linux-hardware.org/?probe=6ac462efda) | Jan 01, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [0360bb01d0](https://linux-hardware.org/?probe=0360bb01d0) | Jan 01, 2023 |
| Dell          | Latitude E5500              | [f04cd8f466](https://linux-hardware.org/?probe=f04cd8f466) | Dec 31, 2022 |
| Dell          | Latitude E5500              | [24a0ca1b65](https://linux-hardware.org/?probe=24a0ca1b65) | Dec 31, 2022 |
| Lenovo        | Yoga 2 13 20344             | [39c9c8aaea](https://linux-hardware.org/?probe=39c9c8aaea) | Dec 31, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [9220da7abb](https://linux-hardware.org/?probe=9220da7abb) | Dec 31, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | [43f808e1e4](https://linux-hardware.org/?probe=43f808e1e4) | Dec 30, 2022 |
| HP            | EliteBook 2570p             | [b8eccb0fbe](https://linux-hardware.org/?probe=b8eccb0fbe) | Dec 30, 2022 |
| Dell          | Latitude E6540              | [e0e5f33e60](https://linux-hardware.org/?probe=e0e5f33e60) | Dec 30, 2022 |
| ASUSTek       | X540YA                      | [d128cfee28](https://linux-hardware.org/?probe=d128cfee28) | Dec 29, 2022 |
| Toshiba       | Satellite C870-1C2          | [cc1dd99957](https://linux-hardware.org/?probe=cc1dd99957) | Dec 28, 2022 |
| Dell          | Latitude 7490               | [0c49efe5e1](https://linux-hardware.org/?probe=0c49efe5e1) | Dec 28, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [27e072cb3e](https://linux-hardware.org/?probe=27e072cb3e) | Dec 28, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | [75fe6d9325](https://linux-hardware.org/?probe=75fe6d9325) | Dec 28, 2022 |
| Lenovo        | ThinkPad X131e 33672K5      | [70d10e91fb](https://linux-hardware.org/?probe=70d10e91fb) | Dec 28, 2022 |
| Toshiba       | Satellite C50-B             | [31241c1f30](https://linux-hardware.org/?probe=31241c1f30) | Dec 28, 2022 |
| Unknown       | Unknown                     | [6aa557fb75](https://linux-hardware.org/?probe=6aa557fb75) | Dec 27, 2022 |
| MSI           | GF63 Thin 10SC              | [71c1ee486e](https://linux-hardware.org/?probe=71c1ee486e) | Dec 27, 2022 |
| Chuwi         | HeroBook Air                | [2c6e8a0c9f](https://linux-hardware.org/?probe=2c6e8a0c9f) | Dec 27, 2022 |
| Chuwi         | HeroBook Air                | [b3db56361b](https://linux-hardware.org/?probe=b3db56361b) | Dec 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [0763603d12](https://linux-hardware.org/?probe=0763603d12) | Dec 27, 2022 |
| Lenovo        | ThinkPad T470 20HES0PF00    | [052cdcd8bb](https://linux-hardware.org/?probe=052cdcd8bb) | Dec 26, 2022 |
| Lenovo        | ThinkPad T470 20HES0PF00    | [940218d084](https://linux-hardware.org/?probe=940218d084) | Dec 26, 2022 |
| Lenovo        | ThinkPad E590 20NB001AMX    | [047944fa9f](https://linux-hardware.org/?probe=047944fa9f) | Dec 26, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [da3f79863a](https://linux-hardware.org/?probe=da3f79863a) | Dec 26, 2022 |
| Lenovo        | IdeaPad 3 17ABA7 82RQ       | [047823ffbc](https://linux-hardware.org/?probe=047823ffbc) | Dec 26, 2022 |
| ASUSTek       | T100TAS                     | [25894bb300](https://linux-hardware.org/?probe=25894bb300) | Dec 26, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | [1ba51900a6](https://linux-hardware.org/?probe=1ba51900a6) | Dec 25, 2022 |
| Acer          | Aspire M3-581G              | [67071376c6](https://linux-hardware.org/?probe=67071376c6) | Dec 25, 2022 |
| Sony          | VGN-NR32M_S                 | [6ad0da2e88](https://linux-hardware.org/?probe=6ad0da2e88) | Dec 25, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [e968a4fe6d](https://linux-hardware.org/?probe=e968a4fe6d) | Dec 24, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [2415ad5980](https://linux-hardware.org/?probe=2415ad5980) | Dec 24, 2022 |
| HP            | Compaq 6730b (NB034ET#UU... | [304e2ca750](https://linux-hardware.org/?probe=304e2ca750) | Dec 24, 2022 |
| HP            | Pavilion dv7                | [a099e9b6ac](https://linux-hardware.org/?probe=a099e9b6ac) | Dec 24, 2022 |
| HP            | Pavilion g7                 | [ef4cc6fa1a](https://linux-hardware.org/?probe=ef4cc6fa1a) | Dec 24, 2022 |
| Lenovo        | G500 20236                  | [3e8fb581f0](https://linux-hardware.org/?probe=3e8fb581f0) | Dec 23, 2022 |
| ASUSTek       | G75VX                       | [bb9724d53f](https://linux-hardware.org/?probe=bb9724d53f) | Dec 23, 2022 |
| Dell          | Latitude E4310              | [6386845196](https://linux-hardware.org/?probe=6386845196) | Dec 23, 2022 |
| Lenovo        | ThinkPad P52 20MAS25B1X     | [f82f15da88](https://linux-hardware.org/?probe=f82f15da88) | Dec 22, 2022 |
| Lenovo        | G50-30 80G0                 | [f497db99b3](https://linux-hardware.org/?probe=f497db99b3) | Dec 22, 2022 |
| HP            | 15 Notebook PC              | [79aabf81c4](https://linux-hardware.org/?probe=79aabf81c4) | Dec 22, 2022 |
| Lenovo        | G50-30 80G0                 | [c0f831d7a4](https://linux-hardware.org/?probe=c0f831d7a4) | Dec 22, 2022 |
| Toshiba       | Satellite L855              | [3caae1ba3b](https://linux-hardware.org/?probe=3caae1ba3b) | Dec 21, 2022 |
| HUAWEI        | BOHB-WAX9                   | [2e63730e46](https://linux-hardware.org/?probe=2e63730e46) | Dec 21, 2022 |
| Dell          | Inspiron 3583               | [64cd4afc6d](https://linux-hardware.org/?probe=64cd4afc6d) | Dec 21, 2022 |
| Sony          | VJZ13A                      | [748f77bace](https://linux-hardware.org/?probe=748f77bace) | Dec 21, 2022 |
| Dell          | Latitude E4310              | [7b184a032b](https://linux-hardware.org/?probe=7b184a032b) | Dec 21, 2022 |
| Lenovo        | Yoga 300-11IBR 80M1         | [06c3b647be](https://linux-hardware.org/?probe=06c3b647be) | Dec 21, 2022 |
| MSI           | GS73VR 7RF                  | [7f37920146](https://linux-hardware.org/?probe=7f37920146) | Dec 20, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [03e2c64868](https://linux-hardware.org/?probe=03e2c64868) | Dec 20, 2022 |
| Lenovo        | G500 20236                  | [83a3d8e955](https://linux-hardware.org/?probe=83a3d8e955) | Dec 19, 2022 |
| GPD           | G1619-04                    | [f184c297f2](https://linux-hardware.org/?probe=f184c297f2) | Dec 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | [3ec240466e](https://linux-hardware.org/?probe=3ec240466e) | Dec 19, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | [b1bd890ed0](https://linux-hardware.org/?probe=b1bd890ed0) | Dec 19, 2022 |
| HP            | ProBook 640 G1              | [cf1ccbf76a](https://linux-hardware.org/?probe=cf1ccbf76a) | Dec 19, 2022 |
| Dell          | Studio XPS 1645             | [e1c0f5a53b](https://linux-hardware.org/?probe=e1c0f5a53b) | Dec 18, 2022 |
| Dell          | Studio XPS 1645             | [2c26ce45b7](https://linux-hardware.org/?probe=2c26ce45b7) | Dec 18, 2022 |
| Dell          | Inspiron 7537               | [7064963568](https://linux-hardware.org/?probe=7064963568) | Dec 18, 2022 |
| ASUSTek       | S500CA                      | [55cf134a8b](https://linux-hardware.org/?probe=55cf134a8b) | Dec 18, 2022 |
| HP            | Laptop 15s-fq2xxx           | [1a23b502b9](https://linux-hardware.org/?probe=1a23b502b9) | Dec 17, 2022 |
| GPU Compan... | GWTC116-2                   | [e64e0ee27a](https://linux-hardware.org/?probe=e64e0ee27a) | Dec 17, 2022 |
| Fusion5       | C60Bv2-128GB                | [7cc701c4de](https://linux-hardware.org/?probe=7cc701c4de) | Dec 17, 2022 |
| HP            | Compaq 6910p (RM231UT#AB... | [4653b4877b](https://linux-hardware.org/?probe=4653b4877b) | Dec 17, 2022 |
| HP            | 250 G1                      | [07f20cc1ec](https://linux-hardware.org/?probe=07f20cc1ec) | Dec 17, 2022 |
| Jumper        | EZbook                      | [010f6841e5](https://linux-hardware.org/?probe=010f6841e5) | Dec 17, 2022 |
| Sony          | VPCEB2M1E                   | [2505ff8962](https://linux-hardware.org/?probe=2505ff8962) | Dec 17, 2022 |
| Sony          | VPCEB2M1E                   | [72bcddb15e](https://linux-hardware.org/?probe=72bcddb15e) | Dec 17, 2022 |
| Jumper        | EZbook                      | [bbae74f641](https://linux-hardware.org/?probe=bbae74f641) | Dec 17, 2022 |
| WYSE          | XM CLASS                    | [8aac2f31cb](https://linux-hardware.org/?probe=8aac2f31cb) | Dec 17, 2022 |
| Lenovo        | V130-15IGM 81HL             | [255499abee](https://linux-hardware.org/?probe=255499abee) | Dec 17, 2022 |
| Toshiba       | Satellite P500              | [58163fa1d7](https://linux-hardware.org/?probe=58163fa1d7) | Dec 16, 2022 |
| Packard Be... | EasyNote TK85               | [a0a0296ca4](https://linux-hardware.org/?probe=a0a0296ca4) | Dec 16, 2022 |
| Google        | Blorb                       | [4134deb94e](https://linux-hardware.org/?probe=4134deb94e) | Dec 16, 2022 |
| MSI           | GP75 Leopard 10SEK          | [9eda9896f3](https://linux-hardware.org/?probe=9eda9896f3) | Dec 15, 2022 |
| Machcreato... | 14                          | [8b69842953](https://linux-hardware.org/?probe=8b69842953) | Dec 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [06bbbb04a9](https://linux-hardware.org/?probe=06bbbb04a9) | Dec 15, 2022 |
| Lenovo        | ThinkPad T460 20FMS2AN00    | [7db77c4fcd](https://linux-hardware.org/?probe=7db77c4fcd) | Dec 14, 2022 |
| HP            | Pavilion dv7                | [7067714e91](https://linux-hardware.org/?probe=7067714e91) | Dec 14, 2022 |
| HP            | Laptop 17-bs0xx             | [d83f209b7f](https://linux-hardware.org/?probe=d83f209b7f) | Dec 12, 2022 |
| GPU Compan... | GWTC116-2                   | [09b233d518](https://linux-hardware.org/?probe=09b233d518) | Dec 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [4a5f657daf](https://linux-hardware.org/?probe=4a5f657daf) | Dec 12, 2022 |
| Apple         | MacBook4,1                  | [45ad14cbc2](https://linux-hardware.org/?probe=45ad14cbc2) | Dec 12, 2022 |
| Apple         | MacBookPro8,1               | [bc16110ca8](https://linux-hardware.org/?probe=bc16110ca8) | Dec 12, 2022 |
| Toshiba       | Satellite C870-1C2          | [477bcdd546](https://linux-hardware.org/?probe=477bcdd546) | Dec 12, 2022 |
| Alienware     | 18                          | [707124d216](https://linux-hardware.org/?probe=707124d216) | Dec 11, 2022 |
| Acer          | Aspire M3-581G              | [25b27d5b17](https://linux-hardware.org/?probe=25b27d5b17) | Dec 11, 2022 |
| ASUSTek       | X751SA                      | [2da53106a0](https://linux-hardware.org/?probe=2da53106a0) | Dec 11, 2022 |
| Sony          | VGN-NR32M_S                 | [f37234d095](https://linux-hardware.org/?probe=f37234d095) | Dec 10, 2022 |
| ASUSTek       | X751SA                      | [36b3666998](https://linux-hardware.org/?probe=36b3666998) | Dec 10, 2022 |
| Lenovo        | ThinkPad T470 20HES0PF00    | [097b783ae5](https://linux-hardware.org/?probe=097b783ae5) | Dec 10, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | [0f4312c32e](https://linux-hardware.org/?probe=0f4312c32e) | Dec 10, 2022 |
| Dell          | Latitude E7240              | [722c8c8b32](https://linux-hardware.org/?probe=722c8c8b32) | Dec 10, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | [2dffa88142](https://linux-hardware.org/?probe=2dffa88142) | Dec 09, 2022 |
| MSI           | GS73VR 7RF                  | [31aa44b519](https://linux-hardware.org/?probe=31aa44b519) | Dec 09, 2022 |
| HP            | Laptop 14-bw0xx             | [3f3a7f6841](https://linux-hardware.org/?probe=3f3a7f6841) | Dec 09, 2022 |
| Apple         | MacBookAir5,2               | [30bbadcb93](https://linux-hardware.org/?probe=30bbadcb93) | Dec 09, 2022 |
| Dell          | Inspiron 5566               | [3a1ec09d8a](https://linux-hardware.org/?probe=3a1ec09d8a) | Dec 08, 2022 |
| HUAWEI        | BOHB-WAX9                   | [0db55b0eea](https://linux-hardware.org/?probe=0db55b0eea) | Dec 08, 2022 |
| Dell          | Latitude 7490               | [6021de66f0](https://linux-hardware.org/?probe=6021de66f0) | Dec 07, 2022 |
| HP            | ProBook 640 G1              | [1c99985945](https://linux-hardware.org/?probe=1c99985945) | Dec 07, 2022 |
| Dell          | Studio 1558                 | [ce0c8ffe20](https://linux-hardware.org/?probe=ce0c8ffe20) | Dec 06, 2022 |
| Dell          | Latitude 7490               | [2b29482df2](https://linux-hardware.org/?probe=2b29482df2) | Dec 06, 2022 |
| Dell          | Inspiron 5558               | [f8e7b50548](https://linux-hardware.org/?probe=f8e7b50548) | Dec 06, 2022 |
| Apple         | MacBookAir5,2               | [a4029fd324](https://linux-hardware.org/?probe=a4029fd324) | Dec 06, 2022 |
| Toshiba       | Satellite L855              | [a28616ab1b](https://linux-hardware.org/?probe=a28616ab1b) | Dec 06, 2022 |
| Packard Be... | EasyNote TE11BZ             | [b243114de5](https://linux-hardware.org/?probe=b243114de5) | Dec 06, 2022 |
| Dell          | XPS 13 9370                 | [b500d948bf](https://linux-hardware.org/?probe=b500d948bf) | Dec 05, 2022 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [9775fe7147](https://linux-hardware.org/?probe=9775fe7147) | Dec 05, 2022 |
| HP            | Pavilion dv7                | [901e0c59ce](https://linux-hardware.org/?probe=901e0c59ce) | Dec 05, 2022 |
| HP            | Pavilion dv7                | [d02f343be8](https://linux-hardware.org/?probe=d02f343be8) | Dec 05, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [2ee93ad61d](https://linux-hardware.org/?probe=2ee93ad61d) | Dec 05, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | [d5ba349e44](https://linux-hardware.org/?probe=d5ba349e44) | Dec 04, 2022 |
| Dell          | Latitude E6540              | [9a547affad](https://linux-hardware.org/?probe=9a547affad) | Dec 04, 2022 |
| Toshiba       | Satellite C870-1C2          | [0e270ccc80](https://linux-hardware.org/?probe=0e270ccc80) | Dec 04, 2022 |
| ASUSTek       | K53SD                       | [dbaf532969](https://linux-hardware.org/?probe=dbaf532969) | Dec 04, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [888ec24e9d](https://linux-hardware.org/?probe=888ec24e9d) | Dec 04, 2022 |
| HP            | Pavilion dv7                | [c398cf4372](https://linux-hardware.org/?probe=c398cf4372) | Dec 03, 2022 |
| HP            | Pavilion dv7                | [e34ad54f3b](https://linux-hardware.org/?probe=e34ad54f3b) | Dec 03, 2022 |
| Dell          | Latitude 5490               | [e74106a982](https://linux-hardware.org/?probe=e74106a982) | Dec 03, 2022 |
| Dell          | Latitude 5490               | [26e6a987d0](https://linux-hardware.org/?probe=26e6a987d0) | Dec 03, 2022 |
| HP            | Pavilion g4                 | [c6a564dce1](https://linux-hardware.org/?probe=c6a564dce1) | Dec 02, 2022 |
| HP            | EliteBook 830 G5            | [d42891d37b](https://linux-hardware.org/?probe=d42891d37b) | Dec 02, 2022 |
| Lenovo        | ThinkPad T420 4236GY3       | [63dd78fcec](https://linux-hardware.org/?probe=63dd78fcec) | Dec 02, 2022 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [50c8de6edf](https://linux-hardware.org/?probe=50c8de6edf) | Dec 02, 2022 |
| Acer          | Aspire V5-121               | [473cfb46f7](https://linux-hardware.org/?probe=473cfb46f7) | Dec 01, 2022 |
| Sony          | VPCEB1M1E                   | [988c78f70d](https://linux-hardware.org/?probe=988c78f70d) | Dec 01, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [f9020b8dc6](https://linux-hardware.org/?probe=f9020b8dc6) | Dec 01, 2022 |
| Dell          | Latitude E5520              | [92a4c9b5ef](https://linux-hardware.org/?probe=92a4c9b5ef) | Nov 30, 2022 |
| Dell          | Studio 1558                 | [cf40788ef8](https://linux-hardware.org/?probe=cf40788ef8) | Nov 30, 2022 |
| MSI           | GE75 Raider 10SE            | [88245a0df3](https://linux-hardware.org/?probe=88245a0df3) | Nov 30, 2022 |
| Dell          | Latitude E6540              | [48c805974c](https://linux-hardware.org/?probe=48c805974c) | Nov 29, 2022 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [ab9b95babe](https://linux-hardware.org/?probe=ab9b95babe) | Nov 28, 2022 |
| Dell          | System XPS L502X            | [bd45da46bc](https://linux-hardware.org/?probe=bd45da46bc) | Nov 27, 2022 |
| Notebook      | NP5x_NP6x_NP7xPNP           | [3dd83d6d9d](https://linux-hardware.org/?probe=3dd83d6d9d) | Nov 27, 2022 |
| Dell          | XPS 15 9560                 | [47782768eb](https://linux-hardware.org/?probe=47782768eb) | Nov 27, 2022 |
| Dell          | Studio 1558                 | [bc76adb105](https://linux-hardware.org/?probe=bc76adb105) | Nov 27, 2022 |
| HP            | Pavilion g6                 | [17d324d115](https://linux-hardware.org/?probe=17d324d115) | Nov 27, 2022 |
| Lenovo        | B50-30 80ES                 | [ced4c1f563](https://linux-hardware.org/?probe=ced4c1f563) | Nov 27, 2022 |
| Dell          | Studio 1558                 | [43438ab851](https://linux-hardware.org/?probe=43438ab851) | Nov 27, 2022 |
| Dell          | Inspiron 1545               | [07df50a08c](https://linux-hardware.org/?probe=07df50a08c) | Nov 27, 2022 |
| Panasonic     | CF-19AHN3BFF                | [a5989143a8](https://linux-hardware.org/?probe=a5989143a8) | Nov 26, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [c26e52327e](https://linux-hardware.org/?probe=c26e52327e) | Nov 26, 2022 |
| Dell          | Latitude E6540              | [543ca1307c](https://linux-hardware.org/?probe=543ca1307c) | Nov 26, 2022 |
| ASUSTek       | X202E                       | [24a8811d77](https://linux-hardware.org/?probe=24a8811d77) | Nov 25, 2022 |
| ASUSTek       | X202E                       | [69a3fa54c1](https://linux-hardware.org/?probe=69a3fa54c1) | Nov 25, 2022 |
| Toshiba       | Satellite C50D-B            | [92d54fef2b](https://linux-hardware.org/?probe=92d54fef2b) | Nov 25, 2022 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | [1ed724b75e](https://linux-hardware.org/?probe=1ed724b75e) | Nov 25, 2022 |
| HP            | ENVY m6                     | [cb48bbdcc1](https://linux-hardware.org/?probe=cb48bbdcc1) | Nov 25, 2022 |
| Dell          | XPS 15 9510                 | [2c7485441f](https://linux-hardware.org/?probe=2c7485441f) | Nov 25, 2022 |
| Panasonic     | CF-19AHN3BFF                | [bfd184ea5c](https://linux-hardware.org/?probe=bfd184ea5c) | Nov 25, 2022 |
| Samsung       | 600B4B/600B5B               | [6cbdda4e27](https://linux-hardware.org/?probe=6cbdda4e27) | Nov 24, 2022 |
| Thomson       | GEN17V3C8WH256              | [7b1a510e2e](https://linux-hardware.org/?probe=7b1a510e2e) | Nov 24, 2022 |
| Apple         | MacBookPro7,1               | [a1fad8227f](https://linux-hardware.org/?probe=a1fad8227f) | Nov 24, 2022 |
| Apple         | MacBookPro7,1               | [4a3e80efe5](https://linux-hardware.org/?probe=4a3e80efe5) | Nov 24, 2022 |
| Toshiba       | Satellite S55t-B            | [4b01021314](https://linux-hardware.org/?probe=4b01021314) | Nov 24, 2022 |
| HP            | Notebook                    | [d65b0a06fe](https://linux-hardware.org/?probe=d65b0a06fe) | Nov 24, 2022 |
| HP            | Notebook                    | [54b351457e](https://linux-hardware.org/?probe=54b351457e) | Nov 24, 2022 |
| HP            | 15                          | [6ce90bccf9](https://linux-hardware.org/?probe=6ce90bccf9) | Nov 23, 2022 |
| HP            | Laptop 14-bw0xx             | [5d4e847eef](https://linux-hardware.org/?probe=5d4e847eef) | Nov 23, 2022 |
| Lenovo        | IdeaPad U400 09932JU        | [cb5d9871d0](https://linux-hardware.org/?probe=cb5d9871d0) | Nov 22, 2022 |
| Apple         | MacBookPro5,4               | [722165a975](https://linux-hardware.org/?probe=722165a975) | Nov 21, 2022 |
| Apple         | MacBookPro8,1               | [dfb9f9524e](https://linux-hardware.org/?probe=dfb9f9524e) | Nov 20, 2022 |
| Framework     | Laptop                      | [6cc495c0d9](https://linux-hardware.org/?probe=6cc495c0d9) | Nov 20, 2022 |
| Acer          | Aspire ES1-521              | [6af4249f1a](https://linux-hardware.org/?probe=6af4249f1a) | Nov 20, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | [77dcd3bef6](https://linux-hardware.org/?probe=77dcd3bef6) | Nov 19, 2022 |
| GPU Compan... | GWTN156-2BK                 | [a7c034bd91](https://linux-hardware.org/?probe=a7c034bd91) | Nov 19, 2022 |
| Dell          | Latitude E6540              | [4148292f4d](https://linux-hardware.org/?probe=4148292f4d) | Nov 18, 2022 |
| Samsung       | 600B4B/600B5B               | [0185c349b9](https://linux-hardware.org/?probe=0185c349b9) | Nov 18, 2022 |
| HP            | 14                          | [958eb656f2](https://linux-hardware.org/?probe=958eb656f2) | Nov 18, 2022 |
| Samsung       | 600B4B/600B5B               | [6992e11b21](https://linux-hardware.org/?probe=6992e11b21) | Nov 18, 2022 |
| Dell          | Latitude E6540              | [31752fdaa8](https://linux-hardware.org/?probe=31752fdaa8) | Nov 18, 2022 |
| HP            | 14                          | [8e4d001eb6](https://linux-hardware.org/?probe=8e4d001eb6) | Nov 18, 2022 |
| Unknown       | Unknown                     | [ef7af01d47](https://linux-hardware.org/?probe=ef7af01d47) | Nov 18, 2022 |
| Unknown       | Unknown                     | [ceca708c95](https://linux-hardware.org/?probe=ceca708c95) | Nov 18, 2022 |
| HP            | EliteBook 8470p             | [f324f5bc16](https://linux-hardware.org/?probe=f324f5bc16) | Nov 18, 2022 |
| HP            | EliteBook 820 G2            | [1c76975e0e](https://linux-hardware.org/?probe=1c76975e0e) | Nov 17, 2022 |
| ALLDOCUBE     | i1405S                      | [fc1628983b](https://linux-hardware.org/?probe=fc1628983b) | Nov 17, 2022 |
| ALLDOCUBE     | i1405S                      | [0b61421847](https://linux-hardware.org/?probe=0b61421847) | Nov 17, 2022 |
| ASUSTek       | ASUS Gaming FX570UD         | [522c9222c5](https://linux-hardware.org/?probe=522c9222c5) | Nov 17, 2022 |
| HP            | Laptop 15-dw0xxx            | [b81771eed0](https://linux-hardware.org/?probe=b81771eed0) | Nov 17, 2022 |
| Acer          | Aspire 7741                 | [4197d5fccf](https://linux-hardware.org/?probe=4197d5fccf) | Nov 17, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | [23f8c23e8b](https://linux-hardware.org/?probe=23f8c23e8b) | Nov 17, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [545eb5e46c](https://linux-hardware.org/?probe=545eb5e46c) | Nov 16, 2022 |
| Gateway       | NV59C                       | [b3be978b72](https://linux-hardware.org/?probe=b3be978b72) | Nov 16, 2022 |
| Dell          | Inspiron 3543               | [15cc03ec87](https://linux-hardware.org/?probe=15cc03ec87) | Nov 16, 2022 |
| Lenovo        | ThinkPad X201 36809T1       | [aad9f7cbaf](https://linux-hardware.org/?probe=aad9f7cbaf) | Nov 16, 2022 |
| Lenovo        | ThinkPad P15v Gen 3 21D9... | [30c7b06e6f](https://linux-hardware.org/?probe=30c7b06e6f) | Nov 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [733e52cbdb](https://linux-hardware.org/?probe=733e52cbdb) | Nov 15, 2022 |
| Toshiba       | Satellite C55-C             | [b240ae5338](https://linux-hardware.org/?probe=b240ae5338) | Nov 15, 2022 |
| Toshiba       | Satellite C55-C             | [d1049db1fb](https://linux-hardware.org/?probe=d1049db1fb) | Nov 15, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | [73bc7e7428](https://linux-hardware.org/?probe=73bc7e7428) | Nov 14, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | [9d798077df](https://linux-hardware.org/?probe=9d798077df) | Nov 14, 2022 |
| ALURIN        | PR1-M146                    | [124eefce98](https://linux-hardware.org/?probe=124eefce98) | Nov 14, 2022 |
| Microtech     | ebookLite                   | [471a1a6ac7](https://linux-hardware.org/?probe=471a1a6ac7) | Nov 14, 2022 |
| Acer          | Extensa 2530                | [ac83b4e3e9](https://linux-hardware.org/?probe=ac83b4e3e9) | Nov 14, 2022 |
| Toshiba       | PORTEGE Z30-A               | [9e70e7fc3a](https://linux-hardware.org/?probe=9e70e7fc3a) | Nov 13, 2022 |
| Hampoo        | Cherry Trail CR             | [ae8d0b2d8e](https://linux-hardware.org/?probe=ae8d0b2d8e) | Nov 13, 2022 |
| ALURIN        | PR1-M146                    | [8d9345b655](https://linux-hardware.org/?probe=8d9345b655) | Nov 12, 2022 |
| HP            | 250 G4                      | [58f7b77f39](https://linux-hardware.org/?probe=58f7b77f39) | Nov 12, 2022 |
| HP            | 250 G4                      | [f700001da4](https://linux-hardware.org/?probe=f700001da4) | Nov 12, 2022 |
| Microtech     | ebookLite                   | [9c3039fa75](https://linux-hardware.org/?probe=9c3039fa75) | Nov 12, 2022 |
| Fujitsu       | STYLISTIC Q572              | [afd0e0efc4](https://linux-hardware.org/?probe=afd0e0efc4) | Nov 12, 2022 |
| Dell          | XPS 13 9370                 | [2865464ccd](https://linux-hardware.org/?probe=2865464ccd) | Nov 11, 2022 |
| HP            | Pavilion Notebook           | [1d6ae45d45](https://linux-hardware.org/?probe=1d6ae45d45) | Nov 11, 2022 |
| HUAWEI        | BOD-WXX9                    | [2e79d44f43](https://linux-hardware.org/?probe=2e79d44f43) | Nov 11, 2022 |
| Lenovo        | G500 20236                  | [1f9e0a7e16](https://linux-hardware.org/?probe=1f9e0a7e16) | Nov 11, 2022 |
| Lenovo        | G500 20236                  | [d3a6ca47df](https://linux-hardware.org/?probe=d3a6ca47df) | Nov 11, 2022 |
| HP            | 2000                        | [5045f21cc3](https://linux-hardware.org/?probe=5045f21cc3) | Nov 10, 2022 |
| Microtech     | ebookLite                   | [63f80f900a](https://linux-hardware.org/?probe=63f80f900a) | Nov 10, 2022 |
| ASUSTek       | G50VT                       | [57f7e69b18](https://linux-hardware.org/?probe=57f7e69b18) | Nov 10, 2022 |
| HP            | Pavilion Notebook           | [150409691d](https://linux-hardware.org/?probe=150409691d) | Nov 09, 2022 |
| HP            | ProBook 430 G4              | [ef9d0cf774](https://linux-hardware.org/?probe=ef9d0cf774) | Nov 09, 2022 |
| HP            | Pavilion Notebook           | [a7de751ce8](https://linux-hardware.org/?probe=a7de751ce8) | Nov 09, 2022 |
| GPU Compan... | GWTN156-2BK                 | [cf64038190](https://linux-hardware.org/?probe=cf64038190) | Nov 08, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [c17772f8e7](https://linux-hardware.org/?probe=c17772f8e7) | Nov 08, 2022 |
| H-BUSTER      | HBNB1403                    | [9d439a53b2](https://linux-hardware.org/?probe=9d439a53b2) | Nov 08, 2022 |
| HP            | ProBook 430 G4              | [5d6f34affd](https://linux-hardware.org/?probe=5d6f34affd) | Nov 08, 2022 |
| Gateway       | ML6732                      | [7889349228](https://linux-hardware.org/?probe=7889349228) | Nov 08, 2022 |
| Dell          | Latitude E5420              | [c6264f1223](https://linux-hardware.org/?probe=c6264f1223) | Nov 08, 2022 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | [5285abf94f](https://linux-hardware.org/?probe=5285abf94f) | Nov 08, 2022 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | [5cfd9a145a](https://linux-hardware.org/?probe=5cfd9a145a) | Nov 08, 2022 |
| Linx          | LINX1010B                   | [fa6d1ebd57](https://linux-hardware.org/?probe=fa6d1ebd57) | Nov 07, 2022 |
| ASUSTek       | K55VD                       | [d8a78ad824](https://linux-hardware.org/?probe=d8a78ad824) | Nov 07, 2022 |
| ASUSTek       | U36SD                       | [d6b92cbdaa](https://linux-hardware.org/?probe=d6b92cbdaa) | Nov 07, 2022 |
| HP            | 240 G8                      | [cbeff38360](https://linux-hardware.org/?probe=cbeff38360) | Nov 07, 2022 |
| HP            | 240 G8                      | [0fadcc21ac](https://linux-hardware.org/?probe=0fadcc21ac) | Nov 07, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | [e44a807758](https://linux-hardware.org/?probe=e44a807758) | Nov 06, 2022 |
| Packard Be... | EasyNote TS11HR             | [8a62c61d38](https://linux-hardware.org/?probe=8a62c61d38) | Nov 06, 2022 |
| Quanta        | TW8/SW8/DW8                 | [31caaec976](https://linux-hardware.org/?probe=31caaec976) | Nov 05, 2022 |
| ASUSTek       | T200TAC                     | [e14cb334c4](https://linux-hardware.org/?probe=e14cb334c4) | Nov 05, 2022 |
| Dell          | Inspiron N5010              | [ee11f3942f](https://linux-hardware.org/?probe=ee11f3942f) | Nov 05, 2022 |
| Lenovo        | G40-30 80FY                 | [2313029c70](https://linux-hardware.org/?probe=2313029c70) | Nov 04, 2022 |
| Lenovo        | ThinkPad P16 Gen 1 21D7S... | [fc4b865872](https://linux-hardware.org/?probe=fc4b865872) | Nov 04, 2022 |
| HP            | Pavilion Notebook           | [a8f3260004](https://linux-hardware.org/?probe=a8f3260004) | Nov 04, 2022 |
| Dell          | Inspiron 7520               | [60d8b24187](https://linux-hardware.org/?probe=60d8b24187) | Nov 04, 2022 |
| Dell          | Inspiron 7520               | [81c0293410](https://linux-hardware.org/?probe=81c0293410) | Nov 04, 2022 |
| BANGHO        | W240HU/W250HUQ              | [82bafb1ca4](https://linux-hardware.org/?probe=82bafb1ca4) | Nov 04, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [c796c2f9ee](https://linux-hardware.org/?probe=c796c2f9ee) | Nov 03, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [30cd9b0d29](https://linux-hardware.org/?probe=30cd9b0d29) | Nov 03, 2022 |
| Dell          | XPS 15 9510                 | [fea56b5428](https://linux-hardware.org/?probe=fea56b5428) | Nov 03, 2022 |
| Microtech     | CoreBook                    | [1276c24890](https://linux-hardware.org/?probe=1276c24890) | Nov 03, 2022 |
| HP            | Pavilion Notebook           | [e24f2a2f57](https://linux-hardware.org/?probe=e24f2a2f57) | Nov 03, 2022 |
| Dell          | Latitude E6540              | [fe0f06d2d3](https://linux-hardware.org/?probe=fe0f06d2d3) | Nov 02, 2022 |
| Samsung       | 600B4B/600B5B               | [56767f430b](https://linux-hardware.org/?probe=56767f430b) | Nov 02, 2022 |
| Samsung       | 600B4B/600B5B               | [b1ffa94d76](https://linux-hardware.org/?probe=b1ffa94d76) | Nov 02, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [ebe8179d26](https://linux-hardware.org/?probe=ebe8179d26) | Nov 02, 2022 |
| HP            | Pavilion Notebook           | [9fef9a6a8a](https://linux-hardware.org/?probe=9fef9a6a8a) | Nov 02, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | [4968129a1a](https://linux-hardware.org/?probe=4968129a1a) | Nov 02, 2022 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [7c6ddf22b5](https://linux-hardware.org/?probe=7c6ddf22b5) | Nov 02, 2022 |
| GPU Compan... | GWTN156-2BK                 | [a7fb2c2163](https://linux-hardware.org/?probe=a7fb2c2163) | Nov 02, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | [005b25ef06](https://linux-hardware.org/?probe=005b25ef06) | Nov 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [cd0e637d88](https://linux-hardware.org/?probe=cd0e637d88) | Nov 01, 2022 |
| HP            | Pavilion Sleekbook 15 PC    | [9dea1bfedb](https://linux-hardware.org/?probe=9dea1bfedb) | Nov 01, 2022 |
| HP            | ProBook 650 G1              | [85f1aa7b6d](https://linux-hardware.org/?probe=85f1aa7b6d) | Nov 01, 2022 |
| ASUSTek       | K55VD                       | [6e2ff87fad](https://linux-hardware.org/?probe=6e2ff87fad) | Nov 01, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | [9864cd6db6](https://linux-hardware.org/?probe=9864cd6db6) | Nov 01, 2022 |
| GPU Compan... | GWTN156-2BK                 | [99ab599fbc](https://linux-hardware.org/?probe=99ab599fbc) | Nov 01, 2022 |
| Dell          | Latitude E6500              | [b7be8c3204](https://linux-hardware.org/?probe=b7be8c3204) | Oct 31, 2022 |
| Dell          | Latitude E6500              | [cb3b467ba8](https://linux-hardware.org/?probe=cb3b467ba8) | Oct 31, 2022 |
| Lenovo        | ThinkPad Edge 25453BG       | [dc7fa9ac1e](https://linux-hardware.org/?probe=dc7fa9ac1e) | Oct 31, 2022 |
| Lenovo        | ThinkPad Edge 25453BG       | [ba67d47c9c](https://linux-hardware.org/?probe=ba67d47c9c) | Oct 31, 2022 |
| HP            | 2000                        | [ea6e4e2cca](https://linux-hardware.org/?probe=ea6e4e2cca) | Oct 31, 2022 |
| Lenovo        | ThinkPad T420 4180DW1       | [b1e229b9a0](https://linux-hardware.org/?probe=b1e229b9a0) | Oct 31, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [34727cd696](https://linux-hardware.org/?probe=34727cd696) | Oct 31, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [6bf9e760ca](https://linux-hardware.org/?probe=6bf9e760ca) | Oct 30, 2022 |
| Packard Be... | EasyNote TE69KB             | [b83d2dd685](https://linux-hardware.org/?probe=b83d2dd685) | Oct 30, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [1ca9fe180c](https://linux-hardware.org/?probe=1ca9fe180c) | Oct 30, 2022 |
| Lenovo        | ThinkPad T480 20L6S82F0C    | [c06d6a27f5](https://linux-hardware.org/?probe=c06d6a27f5) | Oct 30, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [50170811fd](https://linux-hardware.org/?probe=50170811fd) | Oct 30, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [d8f6faad10](https://linux-hardware.org/?probe=d8f6faad10) | Oct 30, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | [75dcd27c77](https://linux-hardware.org/?probe=75dcd27c77) | Oct 30, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [6c3a410233](https://linux-hardware.org/?probe=6c3a410233) | Oct 30, 2022 |
| Dell          | Inspiron 5537               | [4cd1e12a5d](https://linux-hardware.org/?probe=4cd1e12a5d) | Oct 30, 2022 |
| Dell          | Inspiron N5050              | [f844544154](https://linux-hardware.org/?probe=f844544154) | Oct 30, 2022 |
| MSI           | GL72 6QD                    | [2f7c223f5a](https://linux-hardware.org/?probe=2f7c223f5a) | Oct 29, 2022 |
| Acer          | Extensa 5635ZG              | [8c0a7c0aa1](https://linux-hardware.org/?probe=8c0a7c0aa1) | Oct 29, 2022 |
| Toshiba       | Satellite C660              | [242fa16882](https://linux-hardware.org/?probe=242fa16882) | Oct 29, 2022 |
| Dell          | Latitude E6530              | [cdd3b5ce40](https://linux-hardware.org/?probe=cdd3b5ce40) | Oct 28, 2022 |
| HP            | Presario V6000 (RV053UA#... | [ca121e3727](https://linux-hardware.org/?probe=ca121e3727) | Oct 28, 2022 |
| HP            | OMEN Notebook PC 15         | [fea0167027](https://linux-hardware.org/?probe=fea0167027) | Oct 28, 2022 |
| Packard Be... | EasyNote MH45               | [b9aa4cc6d5](https://linux-hardware.org/?probe=b9aa4cc6d5) | Oct 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [9986b4ff02](https://linux-hardware.org/?probe=9986b4ff02) | Oct 27, 2022 |
| Acer          | Aspire 5720Z                | [fc0b8944bc](https://linux-hardware.org/?probe=fc0b8944bc) | Oct 26, 2022 |
| MSI           | Creator Z16 A11UET          | [58e18764cb](https://linux-hardware.org/?probe=58e18764cb) | Oct 26, 2022 |
| MSI           | Creator Z16 A11UET          | [06274bdff6](https://linux-hardware.org/?probe=06274bdff6) | Oct 26, 2022 |
| Toshiba       | Satellite C660              | [80c2aeb241](https://linux-hardware.org/?probe=80c2aeb241) | Oct 26, 2022 |
| Toshiba       | Satellite C660              | [6b0380ea4c](https://linux-hardware.org/?probe=6b0380ea4c) | Oct 26, 2022 |
| Dell          | Latitude E6510              | [1949f78888](https://linux-hardware.org/?probe=1949f78888) | Oct 26, 2022 |
| ALURIN        | PR1-M146                    | [af492a458f](https://linux-hardware.org/?probe=af492a458f) | Oct 25, 2022 |
| MSI           | GT70 2PE                    | [26d9f8ba04](https://linux-hardware.org/?probe=26d9f8ba04) | Oct 25, 2022 |
| Toshiba       | K201                        | [63a892bae3](https://linux-hardware.org/?probe=63a892bae3) | Oct 25, 2022 |
| MSI           | GE62 7RE                    | [bd5b8943f4](https://linux-hardware.org/?probe=bd5b8943f4) | Oct 24, 2022 |
| Samsung       | 305V4A/305V5A/3415VA        | [d8f70347cf](https://linux-hardware.org/?probe=d8f70347cf) | Oct 24, 2022 |
| HP            | Pavilion Sleekbook 15 PC    | [26e7b206ef](https://linux-hardware.org/?probe=26e7b206ef) | Oct 24, 2022 |
| Lenovo        | G50-45 80MQ                 | [2628815c23](https://linux-hardware.org/?probe=2628815c23) | Oct 24, 2022 |
| Apple         | MacBookPro8,2               | [200f2ac48e](https://linux-hardware.org/?probe=200f2ac48e) | Oct 24, 2022 |
| Toshiba       | Satellite C660              | [646b07cc4c](https://linux-hardware.org/?probe=646b07cc4c) | Oct 24, 2022 |
| Alienware     | 18                          | [11e8831b9d](https://linux-hardware.org/?probe=11e8831b9d) | Oct 24, 2022 |
| Alienware     | 18                          | [86eb347494](https://linux-hardware.org/?probe=86eb347494) | Oct 24, 2022 |
| Chuwi         | HeroBook Air                | [055a6c2be8](https://linux-hardware.org/?probe=055a6c2be8) | Oct 23, 2022 |
| Chuwi         | HeroBook Air                | [cb299f8f1b](https://linux-hardware.org/?probe=cb299f8f1b) | Oct 23, 2022 |
| Dell          | Inspiron 5567               | [42280c6145](https://linux-hardware.org/?probe=42280c6145) | Oct 23, 2022 |
| AMI           | Unknown                     | [337d94fb96](https://linux-hardware.org/?probe=337d94fb96) | Oct 23, 2022 |
| ASUSTek       | X510UQ                      | [6d976f6f96](https://linux-hardware.org/?probe=6d976f6f96) | Oct 23, 2022 |
| Lenovo        | IdeaPad 3 17ABA7 82RQ       | [a8a9cdfabc](https://linux-hardware.org/?probe=a8a9cdfabc) | Oct 22, 2022 |
| Lenovo        | IdeaPad 3 17ABA7 82RQ       | [d82378ea41](https://linux-hardware.org/?probe=d82378ea41) | Oct 22, 2022 |
| Acer          | Aspire E5-411               | [f4fa3fce70](https://linux-hardware.org/?probe=f4fa3fce70) | Oct 22, 2022 |
| HP            | EliteBook 755 G5            | [b1550ee8e1](https://linux-hardware.org/?probe=b1550ee8e1) | Oct 22, 2022 |
| Dell          | Studio 1558                 | [ac449d0411](https://linux-hardware.org/?probe=ac449d0411) | Oct 21, 2022 |
| HP            | Stream Notebook             | [685271f268](https://linux-hardware.org/?probe=685271f268) | Oct 21, 2022 |
| Acer          | Predator PH517-61           | [e30217884a](https://linux-hardware.org/?probe=e30217884a) | Oct 21, 2022 |
| HP            | Pavilion Notebook           | [31d7e67080](https://linux-hardware.org/?probe=31d7e67080) | Oct 21, 2022 |
| Acer          | Aspire A315-33              | [1358385d49](https://linux-hardware.org/?probe=1358385d49) | Oct 20, 2022 |
| ASUSTek       | T200TAC                     | [0aad9d8ecd](https://linux-hardware.org/?probe=0aad9d8ecd) | Oct 20, 2022 |
| HP            | G62                         | [721c09b331](https://linux-hardware.org/?probe=721c09b331) | Oct 19, 2022 |
| Microtech     | CoreBook                    | [0592b30e41](https://linux-hardware.org/?probe=0592b30e41) | Oct 19, 2022 |
| Microtech     | CoreBook                    | [536451ed8a](https://linux-hardware.org/?probe=536451ed8a) | Oct 19, 2022 |
| Dell          | Studio 1458                 | [57b5c85b2a](https://linux-hardware.org/?probe=57b5c85b2a) | Oct 19, 2022 |
| Dell          | Vostro 3500                 | [5d1bb5d8aa](https://linux-hardware.org/?probe=5d1bb5d8aa) | Oct 19, 2022 |
| ASUSTek       | T200TAC                     | [c33c750766](https://linux-hardware.org/?probe=c33c750766) | Oct 18, 2022 |
| HP            | Notebook                    | [01692e8f30](https://linux-hardware.org/?probe=01692e8f30) | Oct 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [ff6d42a3ef](https://linux-hardware.org/?probe=ff6d42a3ef) | Oct 17, 2022 |
| Acer          | Aspire E5-411               | [01979e17ce](https://linux-hardware.org/?probe=01979e17ce) | Oct 17, 2022 |
| HP            | Laptop 15-db0xxx            | [4b0c3a6022](https://linux-hardware.org/?probe=4b0c3a6022) | Oct 17, 2022 |
| HP            | Pavilion Notebook           | [f188526e04](https://linux-hardware.org/?probe=f188526e04) | Oct 17, 2022 |
| HP            | Pavilion Notebook           | [50c44df4fb](https://linux-hardware.org/?probe=50c44df4fb) | Oct 17, 2022 |
| Apple         | MacBookPro5,4               | [bc6696e1d5](https://linux-hardware.org/?probe=bc6696e1d5) | Oct 17, 2022 |
| Toshiba       | Satellite C55-A             | [f93fb31ad5](https://linux-hardware.org/?probe=f93fb31ad5) | Oct 16, 2022 |
| Dell          | Inspiron 14 5401            | [9c955c6521](https://linux-hardware.org/?probe=9c955c6521) | Oct 16, 2022 |
| Dell          | Inspiron 14 5401            | [5fbc33b9bf](https://linux-hardware.org/?probe=5fbc33b9bf) | Oct 16, 2022 |
| Google        | Lars                        | [b607a23c77](https://linux-hardware.org/?probe=b607a23c77) | Oct 14, 2022 |
| HUAWEI        | KLVD-WXX9                   | [bb7d61198e](https://linux-hardware.org/?probe=bb7d61198e) | Oct 14, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | [772645390a](https://linux-hardware.org/?probe=772645390a) | Oct 14, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | [7e770fd62b](https://linux-hardware.org/?probe=7e770fd62b) | Oct 14, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | [e4c404552a](https://linux-hardware.org/?probe=e4c404552a) | Oct 13, 2022 |
| Chuwi         | HeroBook Pro                | [4fe76d84fd](https://linux-hardware.org/?probe=4fe76d84fd) | Oct 13, 2022 |
| Dell          | Vostro 3558                 | [855e0d050c](https://linux-hardware.org/?probe=855e0d050c) | Oct 13, 2022 |
| Dell          | Latitude E6330              | [815d48ffba](https://linux-hardware.org/?probe=815d48ffba) | Oct 12, 2022 |
| Dell          | Latitude E6410              | [9ed4124073](https://linux-hardware.org/?probe=9ed4124073) | Oct 11, 2022 |
| TERRA         | TERRAPC                     | [048f3ad5ef](https://linux-hardware.org/?probe=048f3ad5ef) | Oct 11, 2022 |
| HUAWEI        | MACH-WX9                    | [da36ee9925](https://linux-hardware.org/?probe=da36ee9925) | Oct 11, 2022 |
| Acer          | Aspire A315-33              | [8606cbf7cc](https://linux-hardware.org/?probe=8606cbf7cc) | Oct 10, 2022 |
| Dell          | Inspiron 3521               | [f6e7e1585c](https://linux-hardware.org/?probe=f6e7e1585c) | Oct 10, 2022 |
| Lenovo        | G500 20236                  | [897321f579](https://linux-hardware.org/?probe=897321f579) | Oct 09, 2022 |
| Panasonic     | CF-19-8                     | [439e2c8122](https://linux-hardware.org/?probe=439e2c8122) | Oct 09, 2022 |
| Panasonic     | CF-19-8                     | [bc5820629b](https://linux-hardware.org/?probe=bc5820629b) | Oct 09, 2022 |
| Packard Be... | EasyNote TM82               | [8e3ecfd03d](https://linux-hardware.org/?probe=8e3ecfd03d) | Oct 08, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [d1c01a07a2](https://linux-hardware.org/?probe=d1c01a07a2) | Oct 08, 2022 |
| Dell          | Inspiron 3521               | [0b225367b8](https://linux-hardware.org/?probe=0b225367b8) | Oct 08, 2022 |
| Dell          | Latitude E6410              | [0b617be9dd](https://linux-hardware.org/?probe=0b617be9dd) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [46b44504df](https://linux-hardware.org/?probe=46b44504df) | Oct 08, 2022 |
| AXDIA Inte... | WINBOOK 13                  | [35638411ee](https://linux-hardware.org/?probe=35638411ee) | Oct 08, 2022 |
| Fujitsu       | LIFEBOOK LH531              | [21a68d8c0e](https://linux-hardware.org/?probe=21a68d8c0e) | Oct 08, 2022 |
| HP            | ZBook 17 G5                 | [19db5a4e7c](https://linux-hardware.org/?probe=19db5a4e7c) | Oct 07, 2022 |
| TERRA         | TERRAPC                     | [ec9068f7ea](https://linux-hardware.org/?probe=ec9068f7ea) | Oct 07, 2022 |
| HP            | ZBook 17 G5                 | [005d2d7671](https://linux-hardware.org/?probe=005d2d7671) | Oct 07, 2022 |
| Apple         | MacBookPro9,1               | [d5a346bdd1](https://linux-hardware.org/?probe=d5a346bdd1) | Oct 07, 2022 |
| Dell          | Vostro 2520                 | [da789d3a06](https://linux-hardware.org/?probe=da789d3a06) | Oct 06, 2022 |
| Dell          | Latitude E6500              | [84fa5b35ed](https://linux-hardware.org/?probe=84fa5b35ed) | Oct 06, 2022 |
| Acer          | Aspire E1-522               | [769baa3828](https://linux-hardware.org/?probe=769baa3828) | Oct 05, 2022 |
| HP            | EliteBook 840 G6            | [397e5be75c](https://linux-hardware.org/?probe=397e5be75c) | Oct 05, 2022 |
| Dell          | Inspiron 3521               | [5bb972fab4](https://linux-hardware.org/?probe=5bb972fab4) | Oct 05, 2022 |
| Hampoo        | C3W6_AP108_4GB Reserved     | [9b8dc565f9](https://linux-hardware.org/?probe=9b8dc565f9) | Oct 04, 2022 |
| Gigabyte      | AORUS 7 SB                  | [444224d1e0](https://linux-hardware.org/?probe=444224d1e0) | Oct 04, 2022 |
| HP            | ENVY m6                     | [5c828496a7](https://linux-hardware.org/?probe=5c828496a7) | Oct 04, 2022 |
| Google        | Careena                     | [7ac4802a10](https://linux-hardware.org/?probe=7ac4802a10) | Oct 04, 2022 |
| Acer          | Extensa 2530                | [684b31b41d](https://linux-hardware.org/?probe=684b31b41d) | Oct 03, 2022 |
| HP            | ProBook 455 G6              | [acae78b85a](https://linux-hardware.org/?probe=acae78b85a) | Oct 03, 2022 |
| HP            | ProBook 455 G6              | [3697a412bd](https://linux-hardware.org/?probe=3697a412bd) | Oct 03, 2022 |
| ASUSTek       | X756UQ                      | [e17cbbf886](https://linux-hardware.org/?probe=e17cbbf886) | Oct 03, 2022 |
| ASUSTek       | X756UQ                      | [5767aaf6db](https://linux-hardware.org/?probe=5767aaf6db) | Oct 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [d3bcd51be1](https://linux-hardware.org/?probe=d3bcd51be1) | Oct 03, 2022 |
| Lenovo        | V570 1066EDG                | [8e2439c590](https://linux-hardware.org/?probe=8e2439c590) | Oct 01, 2022 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | [dc7e0ada81](https://linux-hardware.org/?probe=dc7e0ada81) | Oct 01, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Zorin_16/Notebook/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.15.0-56-generic | 126       | 6.54%   |
| 5.11.0-38-generic | 101       | 5.24%   |
| 5.15.0-52-generic | 93        | 4.83%   |
| 5.11.0-27-generic | 93        | 4.83%   |
| 5.15.0-58-generic | 89        | 4.62%   |
| 5.15.0-46-generic | 89        | 4.62%   |
| 5.13.0-30-generic | 74        | 3.84%   |
| 5.11.0-37-generic | 67        | 3.48%   |
| 5.11.0-40-generic | 65        | 3.37%   |
| 5.15.0-69-generic | 63        | 3.27%   |
| 5.11.0-41-generic | 62        | 3.22%   |
| 5.15.0-67-generic | 61        | 3.17%   |
| 5.13.0-39-generic | 60        | 3.12%   |
| 5.11.0-34-generic | 57        | 2.96%   |
| 5.11.0-43-generic | 56        | 2.91%   |
| 5.15.0-60-generic | 54        | 2.8%    |
| 5.15.0-48-generic | 51        | 2.65%   |
| 5.15.0-71-generic | 50        | 2.6%    |
| 5.13.0-44-generic | 48        | 2.49%   |
| 5.13.0-40-generic | 46        | 2.39%   |
| 5.15.0-53-generic | 43        | 2.23%   |
| 5.13.0-35-generic | 40        | 2.08%   |
| 5.13.0-28-generic | 37        | 1.92%   |
| 5.15.0-41-generic | 34        | 1.77%   |
| 5.13.0-52-generic | 31        | 1.61%   |
| 5.15.0-72-generic | 30        | 1.56%   |
| 5.13.0-27-generic | 28        | 1.45%   |
| 5.11.0-46-generic | 26        | 1.35%   |
| 5.13.0-41-generic | 25        | 1.3%    |
| 5.11.0-36-generic | 22        | 1.14%   |
| 5.15.0-43-generic | 21        | 1.09%   |
| 5.13.0-51-generic | 20        | 1.04%   |
| 5.15.0-57-generic | 18        | 0.93%   |
| 5.11.0-44-generic | 18        | 0.93%   |
| 5.15.0-73-generic | 17        | 0.88%   |
| 5.13.0-37-generic | 15        | 0.78%   |
| 5.13.0-48-generic | 13        | 0.67%   |
| 5.15.0-50-generic | 12        | 0.62%   |
| 5.11.0-25-generic | 9         | 0.47%   |
| 5.8.0-53-generic  | 6         | 0.31%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 767       | 43.19%  |
| 5.11.0  | 549       | 30.91%  |
| 5.13.0  | 406       | 22.86%  |
| 5.8.0   | 23        | 1.3%    |
| 5.14.0  | 8         | 0.45%   |
| 5.18.15 | 2         | 0.11%   |
| 5.16.0  | 2         | 0.11%   |
| 5.10.0  | 2         | 0.11%   |
| 6.3.2   | 1         | 0.06%   |
| 6.2.14  | 1         | 0.06%   |
| 6.0.9   | 1         | 0.06%   |
| 6.0.19  | 1         | 0.06%   |
| 6.0.0   | 1         | 0.06%   |
| 5.4.180 | 1         | 0.06%   |
| 5.4.0   | 1         | 0.06%   |
| 5.19.9  | 1         | 0.06%   |
| 5.19.14 | 1         | 0.06%   |
| 5.19.12 | 1         | 0.06%   |
| 5.19.1  | 1         | 0.06%   |
| 5.19.0  | 1         | 0.06%   |
| 5.18.6  | 1         | 0.06%   |
| 5.16.12 | 1         | 0.06%   |
| 5.15.49 | 1         | 0.06%   |
| 5.15.24 | 1         | 0.06%   |
| 5.13.18 | 1         | 0.06%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 769       | 43.3%   |
| 5.11    | 549       | 30.91%  |
| 5.13    | 407       | 22.92%  |
| 5.8     | 23        | 1.3%    |
| 5.14    | 8         | 0.45%   |
| 5.19    | 5         | 0.28%   |
| 6.0     | 3         | 0.17%   |
| 5.18    | 3         | 0.17%   |
| 5.16    | 3         | 0.17%   |
| 5.4     | 2         | 0.11%   |
| 5.10    | 2         | 0.11%   |
| 6.3     | 1         | 0.06%   |
| 6.2     | 1         | 0.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 1697      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 1452      | 84.96%  |
| XFCE       | 234       | 13.69%  |
| Unknown    | 12        | 0.7%    |
| X-Cinnamon | 3         | 0.18%   |
| KDE5       | 2         | 0.12%   |
| Budgie     | 2         | 0.12%   |
| LXDE       | 1         | 0.06%   |
| KDE        | 1         | 0.06%   |
| i3         | 1         | 0.06%   |
| Cinnamon   | 1         | 0.06%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 1668      | 97.72%  |
| Wayland | 34        | 1.99%   |
| Unknown | 4         | 0.23%   |
| Tty     | 1         | 0.06%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1288      | 75.01%  |
| GDM     | 195       | 11.36%  |
| GDM3    | 167       | 9.73%   |
| LightDM | 64        | 3.73%   |
| SDDM    | 2         | 0.12%   |
| LXDM    | 1         | 0.06%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 650       | 38.1%   |
| de_DE | 154       | 9.03%   |
| en_GB | 116       | 6.8%    |
| pt_BR | 97        | 5.69%   |
| fr_FR | 64        | 3.75%   |
| it_IT | 59        | 3.46%   |
| es_ES | 58        | 3.4%    |
| en_IN | 58        | 3.4%    |
| en_CA | 51        | 2.99%   |
| pl_PL | 42        | 2.46%   |
| en_AU | 29        | 1.7%    |
| nl_NL | 28        | 1.64%   |
| es_MX | 27        | 1.58%   |
| ru_RU | 22        | 1.29%   |
| pt_PT | 19        | 1.11%   |
| en_ZA | 19        | 1.11%   |
| cs_CZ | 16        | 0.94%   |
| tr_TR | 12        | 0.7%    |
| sv_SE | 12        | 0.7%    |
| fr_BE | 12        | 0.7%    |
| de_CH | 12        | 0.7%    |
| de_AT | 11        | 0.64%   |
| en_NZ | 10        | 0.59%   |
| es_CL | 9         | 0.53%   |
| hu_HU | 8         | 0.47%   |
| es_AR | 8         | 0.47%   |
| nl_BE | 7         | 0.41%   |
| ja_JP | 6         | 0.35%   |
| hr_HR | 5         | 0.29%   |
| es_CR | 5         | 0.29%   |
| es_CO | 5         | 0.29%   |
| el_GR | 5         | 0.29%   |
| ar_EG | 5         | 0.29%   |
| en_PH | 4         | 0.23%   |
| bg_BG | 4         | 0.23%   |
| sr_RS | 3         | 0.18%   |
| ru_UA | 3         | 0.18%   |
| ro_RO | 3         | 0.18%   |
| nb_NO | 3         | 0.18%   |
| fr_CA | 3         | 0.18%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 1019      | 59.49%  |
| BIOS | 694       | 40.51%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 1611      | 94.6%   |
| Overlay | 31        | 1.82%   |
| Zfs     | 28        | 1.64%   |
| Btrfs   | 16        | 0.94%   |
| Tmpfs   | 10        | 0.59%   |
| Xfs     | 4         | 0.23%   |
| Ext2    | 2         | 0.12%   |
| Ext3    | 1         | 0.06%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1397      | 81.32%  |
| GPT     | 258       | 15.02%  |
| MBR     | 63        | 3.67%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1663      | 97.71%  |
| Yes       | 39        | 2.29%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1547      | 90.79%  |
| Yes       | 157       | 9.21%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 363       | 21.39%  |
| Lenovo              | 295       | 17.38%  |
| Dell                | 264       | 15.56%  |
| ASUSTek Computer    | 181       | 10.67%  |
| Acer                | 132       | 7.78%   |
| Toshiba             | 73        | 4.3%    |
| Apple               | 52        | 3.06%   |
| Samsung Electronics | 30        | 1.77%   |
| MSI                 | 30        | 1.77%   |
| Sony                | 24        | 1.41%   |
| Google              | 24        | 1.41%   |
| Packard Bell        | 17        | 1%      |
| Unknown             | 16        | 0.94%   |
| HUAWEI              | 13        | 0.77%   |
| Positivo            | 12        | 0.71%   |
| Chuwi               | 9         | 0.53%   |
| Notebook            | 8         | 0.47%   |
| Fujitsu             | 8         | 0.47%   |
| Medion              | 7         | 0.41%   |
| Alienware           | 7         | 0.41%   |
| Multilaser          | 6         | 0.35%   |
| GPU Company         | 5         | 0.29%   |
| Fujitsu Siemens     | 5         | 0.29%   |
| Thomson             | 4         | 0.24%   |
| Razer               | 4         | 0.24%   |
| LG Electronics      | 4         | 0.24%   |
| Jumper              | 4         | 0.24%   |
| Framework           | 4         | 0.24%   |
| Microtech           | 3         | 0.18%   |
| Insyde              | 3         | 0.18%   |
| Gateway             | 3         | 0.18%   |
| Digibras            | 3         | 0.18%   |
| AMI                 | 3         | 0.18%   |
| TUXEDO              | 2         | 0.12%   |
| Timi                | 2         | 0.12%   |
| Star Labs           | 2         | 0.12%   |
| Semp Toshiba        | 2         | 0.12%   |
| Panasonic           | 2         | 0.12%   |
| Mediacom            | 2         | 0.12%   |
| Kogan               | 2         | 0.12%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Unknown                        | 25        | 1.47%   |
| HP Notebook                    | 20        | 1.18%   |
| HP Pavilion Notebook           | 14        | 0.82%   |
| HP Pavilion dv6                | 8         | 0.47%   |
| HP 15                          | 8         | 0.47%   |
| Apple MacBookPro8,1            | 8         | 0.47%   |
| HP Pavilion dv7                | 7         | 0.41%   |
| HP Pavilion 15                 | 7         | 0.41%   |
| Dell Latitude E6540            | 6         | 0.35%   |
| HP ProBook 640 G1              | 5         | 0.29%   |
| HP Pavilion g6                 | 5         | 0.29%   |
| Dell Latitude E6520            | 5         | 0.29%   |
| Dell Inspiron 15-3567          | 5         | 0.29%   |
| Toshiba Satellite C660         | 4         | 0.24%   |
| Toshiba Satellite C55-C        | 4         | 0.24%   |
| HP Stream Notebook             | 4         | 0.24%   |
| HP Stream Laptop 14-ax0XX      | 4         | 0.24%   |
| HP Laptop 15-db0xxx            | 4         | 0.24%   |
| HP Laptop 15-bw0xx             | 4         | 0.24%   |
| HP EliteBook 840 G1            | 4         | 0.24%   |
| GPU Company GWTC116-2          | 4         | 0.24%   |
| Framework Laptop               | 4         | 0.24%   |
| Dell Studio 1558               | 4         | 0.24%   |
| Dell Latitude E7440            | 4         | 0.24%   |
| Dell Latitude E6430            | 4         | 0.24%   |
| Dell Latitude E5500            | 4         | 0.24%   |
| Dell Inspiron 3542             | 4         | 0.24%   |
| Dell Inspiron 3521             | 4         | 0.24%   |
| Dell Inspiron 1545             | 4         | 0.24%   |
| Chuwi HeroBook Air             | 4         | 0.24%   |
| Apple MacBookPro12,1           | 4         | 0.24%   |
| Apple MacBookAir7,2            | 4         | 0.24%   |
| Packard Bell EasyNote TS11HR   | 3         | 0.18%   |
| Packard Bell EasyNote TK85     | 3         | 0.18%   |
| Lenovo Yoga 3 Pro-1370 80HE    | 3         | 0.18%   |
| Lenovo Yoga 2 13 20344         | 3         | 0.18%   |
| Lenovo IdeaPad S340-14API 81NB | 3         | 0.18%   |
| Lenovo IdeaPad S145-15API 81V7 | 3         | 0.18%   |
| Lenovo IdeaPad Flex-14API 81SS | 3         | 0.18%   |
| Lenovo IdeaPad 3 17ABA7 82RQ   | 3         | 0.18%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 116       | 6.84%   |
| Dell Latitude         | 103       | 6.07%   |
| Lenovo IdeaPad        | 95        | 5.6%    |
| Acer Aspire           | 95        | 5.6%    |
| Dell Inspiron         | 90        | 5.3%    |
| HP Pavilion           | 89        | 5.24%   |
| Toshiba Satellite     | 58        | 3.42%   |
| HP EliteBook          | 52        | 3.06%   |
| HP ProBook            | 44        | 2.59%   |
| HP Laptop             | 35        | 2.06%   |
| ASUS VivoBook         | 31        | 1.83%   |
| Unknown               | 25        | 1.47%   |
| HP Notebook           | 20        | 1.18%   |
| Dell Vostro           | 20        | 1.18%   |
| HP Stream             | 18        | 1.06%   |
| Dell XPS              | 18        | 1.06%   |
| HP Compaq             | 16        | 0.94%   |
| Packard Bell EasyNote | 15        | 0.88%   |
| Dell Precision        | 15        | 0.88%   |
| HP ENVY               | 14        | 0.82%   |
| Lenovo Yoga           | 11        | 0.65%   |
| HP OMEN               | 11        | 0.65%   |
| ASUS ZenBook          | 11        | 0.65%   |
| ASUS ROG              | 11        | 0.65%   |
| HP 15                 | 10        | 0.59%   |
| ASUS ASUS             | 10        | 0.59%   |
| Apple MacBookPro8     | 10        | 0.59%   |
| Dell Studio           | 8         | 0.47%   |
| Lenovo Legion         | 7         | 0.41%   |
| HP 255                | 7         | 0.41%   |
| Acer Swift            | 7         | 0.41%   |
| Toshiba PORTEGE       | 6         | 0.35%   |
| HP ZBook              | 6         | 0.35%   |
| Fujitsu LIFEBOOK      | 6         | 0.35%   |
| Apple MacBookPro11    | 6         | 0.35%   |
| Toshiba TECRA         | 5         | 0.29%   |
| Lenovo ThinkBook      | 5         | 0.29%   |
| Chuwi HeroBook        | 5         | 0.29%   |
| ASUS TUF              | 5         | 0.29%   |
| Apple MacBookPro5     | 5         | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2012 | 158       | 9.31%   |
| 2011 | 157       | 9.25%   |
| 2021 | 149       | 8.78%   |
| 2013 | 142       | 8.37%   |
| 2020 | 123       | 7.25%   |
| 2019 | 119       | 7.01%   |
| 2014 | 115       | 6.78%   |
| 2017 | 105       | 6.19%   |
| 2018 | 104       | 6.13%   |
| 2010 | 103       | 6.07%   |
| 2015 | 102       | 6.01%   |
| 2016 | 95        | 5.6%    |
| 2008 | 75        | 4.42%   |
| 2009 | 52        | 3.06%   |
| 2022 | 42        | 2.47%   |
| 2007 | 38        | 2.24%   |
| 2023 | 9         | 0.53%   |
| 2006 | 9         | 0.53%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1697      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 1447      | 84.47%  |
| Enabled  | 266       | 15.53%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1669      | 98.35%  |
| Yes  | 28        | 1.65%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 571       | 33.53%  |
| 3.01-4.0    | 476       | 27.95%  |
| 8.01-16.0   | 228       | 13.39%  |
| 16.01-24.0  | 204       | 11.98%  |
| 1.01-2.0    | 107       | 6.28%   |
| 32.01-64.0  | 69        | 4.05%   |
| 2.01-3.0    | 25        | 1.47%   |
| 64.01-256.0 | 11        | 0.65%   |
| 24.01-32.0  | 8         | 0.47%   |
| 0.51-1.0    | 4         | 0.23%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 766       | 41.56%  |
| 2.01-3.0   | 599       | 32.5%   |
| 3.01-4.0   | 248       | 13.46%  |
| 4.01-8.0   | 160       | 8.68%   |
| 0.51-1.0   | 43        | 2.33%   |
| 8.01-16.0  | 24        | 1.3%    |
| 24.01-32.0 | 2         | 0.11%   |
| 16.01-24.0 | 1         | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1309      | 75.88%  |
| 2      | 366       | 21.22%  |
| 3      | 34        | 1.97%   |
| 4      | 7         | 0.41%   |
| 0      | 7         | 0.41%   |
| 8      | 1         | 0.06%   |
| 5      | 1         | 0.06%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 980       | 57.55%  |
| Yes       | 723       | 42.45%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1314      | 77.2%   |
| No        | 388       | 22.8%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1634      | 96.29%  |
| No        | 63        | 3.71%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1221      | 71.28%  |
| No        | 492       | 28.72%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 363       | 21.34%  |
| Germany      | 170       | 9.99%   |
| Brazil       | 111       | 6.53%   |
| UK           | 102       | 6%      |
| Spain        | 65        | 3.82%   |
| Canada       | 64        | 3.76%   |
| India        | 61        | 3.59%   |
| Italy        | 60        | 3.53%   |
| France       | 58        | 3.41%   |
| Netherlands  | 44        | 2.59%   |
| Poland       | 38        | 2.23%   |
| Mexico       | 38        | 2.23%   |
| Australia    | 28        | 1.65%   |
| Russia       | 25        | 1.47%   |
| South Africa | 23        | 1.35%   |
| Portugal     | 23        | 1.35%   |
| Belgium      | 23        | 1.35%   |
| Austria      | 23        | 1.35%   |
| Turkey       | 20        | 1.18%   |
| Switzerland  | 20        | 1.18%   |
| Sweden       | 18        | 1.06%   |
| Czechia      | 18        | 1.06%   |
| Romania      | 17        | 1%      |
| Argentina    | 14        | 0.82%   |
| Norway       | 12        | 0.71%   |
| Greece       | 12        | 0.71%   |
| Japan        | 11        | 0.65%   |
| Hungary      | 11        | 0.65%   |
| New Zealand  | 10        | 0.59%   |
| Chile        | 10        | 0.59%   |
| Indonesia    | 9         | 0.53%   |
| Egypt        | 9         | 0.53%   |
| Colombia     | 9         | 0.53%   |
| Finland      | 8         | 0.47%   |
| Bulgaria     | 8         | 0.47%   |
| Croatia      | 7         | 0.41%   |
| Nigeria      | 6         | 0.35%   |
| Kenya        | 6         | 0.35%   |
| Ireland      | 6         | 0.35%   |
| Costa Rica   | 6         | 0.35%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Berlin            | 14        | 0.79%   |
| Madrid            | 13        | 0.73%   |
| New York          | 12        | 0.68%   |
| Vienna            | 11        | 0.62%   |
| Sao Paulo         | 11        | 0.62%   |
| Munich            | 11        | 0.62%   |
| Sydney            | 10        | 0.56%   |
| Rome              | 10        | 0.56%   |
| Athens            | 10        | 0.56%   |
| Paris             | 8         | 0.45%   |
| Montreal          | 8         | 0.45%   |
| Hamburg           | 8         | 0.45%   |
| Amsterdam         | 8         | 0.45%   |
| Widnau            | 7         | 0.39%   |
| Toronto           | 7         | 0.39%   |
| Moscow            | 7         | 0.39%   |
| London            | 7         | 0.39%   |
| Johannesburg      | 7         | 0.39%   |
| Glasgow           | 7         | 0.39%   |
| Delhi             | 7         | 0.39%   |
| Barcelona         | 7         | 0.39%   |
| Valencia          | 6         | 0.34%   |
| Seattle           | 6         | 0.34%   |
| Rio de Janeiro    | 6         | 0.34%   |
| Krakow            | 6         | 0.34%   |
| Kolkata           | 6         | 0.34%   |
| Istanbul          | 6         | 0.34%   |
| Frankfurt am Main | 6         | 0.34%   |
| Denver            | 6         | 0.34%   |
| Bengaluru         | 6         | 0.34%   |
| Austin            | 6         | 0.34%   |
| Zagreb            | 5         | 0.28%   |
| Stuttgart         | 5         | 0.28%   |
| Stockholm         | 5         | 0.28%   |
| Nairobi           | 5         | 0.28%   |
| Mexico City       | 5         | 0.28%   |
| Melbourne         | 5         | 0.28%   |
| Lagos             | 5         | 0.28%   |
| Jakarta           | 5         | 0.28%   |
| Dallas            | 5         | 0.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 253       | 341    | 12.54%  |
| Seagate                     | 241       | 296    | 11.94%  |
| WDC                         | 213       | 257    | 10.56%  |
| Unknown                     | 187       | 252    | 9.27%   |
| Toshiba                     | 174       | 196    | 8.62%   |
| SanDisk                     | 141       | 163    | 6.99%   |
| Kingston                    | 95        | 114    | 4.71%   |
| Crucial                     | 76        | 91     | 3.77%   |
| Intel                       | 60        | 76     | 2.97%   |
| HGST                        | 56        | 66     | 2.78%   |
| Hitachi                     | 52        | 63     | 2.58%   |
| SK hynix                    | 51        | 59     | 2.53%   |
| Micron Technology           | 46        | 55     | 2.28%   |
| A-DATA Technology           | 31        | 35     | 1.54%   |
| China                       | 25        | 31     | 1.24%   |
| Apple                       | 22        | 25     | 1.09%   |
| KIOXIA                      | 19        | 21     | 0.94%   |
| Intenso                     | 16        | 17     | 0.79%   |
| SPCC                        | 14        | 17     | 0.69%   |
| Netac                       | 14        | 14     | 0.69%   |
| Unknown                     | 14        | 16     | 0.69%   |
| PNY                         | 13        | 14     | 0.64%   |
| LITEONIT                    | 11        | 13     | 0.55%   |
| LITEON                      | 10        | 12     | 0.5%    |
| GOODRAM                     | 10        | 11     | 0.5%    |
| Fujitsu                     | 10        | 11     | 0.5%    |
| Patriot                     | 9         | 10     | 0.45%   |
| Transcend                   | 7         | 9      | 0.35%   |
| Silicon Motion              | 7         | 7      | 0.35%   |
| Phison                      | 7         | 8      | 0.35%   |
| Team                        | 6         | 7      | 0.3%    |
| JMicron Technology          | 6         | 7      | 0.3%    |
| SABRENT                     | 5         | 6      | 0.25%   |
| Phison Electronics          | 5         | 5      | 0.25%   |
| OCZ                         | 5         | 6      | 0.25%   |
| Lite-On                     | 5         | 7      | 0.25%   |
| Lexar                       | 4         | 4      | 0.2%    |
| Kingston Technology Company | 4         | 4      | 0.2%    |
| ASMT                        | 4         | 4      | 0.2%    |
| Mushkin                     | 3         | 3      | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                              | 66        | 3.12%   |
| Unknown MMC Card  64GB                              | 49        | 2.32%   |
| Seagate ST1000LM035-1RK172 1TB                      | 34        | 1.61%   |
| Toshiba MQ01ABD100 1TB                              | 27        | 1.28%   |
| Unknown MMC Card  128GB                             | 24        | 1.14%   |
| Toshiba MQ01ABF050 500GB                            | 24        | 1.14%   |
| Toshiba MQ04ABF100 1TB                              | 21        | 0.99%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 21        | 0.99%   |
| Kingston SA400S37240G 240GB SSD                     | 21        | 0.99%   |
| Seagate ST500LT012-1DG142 500GB                     | 19        | 0.9%    |
| SanDisk NVMe SSD Drive 256GB                        | 19        | 0.9%    |
| Samsung NVMe SSD Drive 512GB                        | 18        | 0.85%   |
| Kingston SA400S37480G 480GB SSD                     | 18        | 0.85%   |
| Unknown MMC Card  16GB                              | 17        | 0.8%    |
| Kingston SA400S37120G 120GB SSD                     | 15        | 0.71%   |
| HGST HTS721010A9E630 1TB                            | 14        | 0.66%   |
| Unknown                                             | 14        | 0.66%   |
| Seagate ST9500325AS 500GB                           | 13        | 0.62%   |
| Crucial CT500MX500SSD1 500GB                        | 13        | 0.62%   |
| Crucial CT240BX500SSD1 240GB                        | 13        | 0.62%   |
| Samsung NVMe SSD Drive 256GB                        | 12        | 0.57%   |
| Intel NVMe SSD Drive 512GB                          | 12        | 0.57%   |
| HGST HTS541010A9E680 1TB                            | 12        | 0.57%   |
| Unknown SD/MMC/MS PRO 64GB                          | 11        | 0.52%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 11        | 0.52%   |
| Seagate Expansion 1TB                               | 11        | 0.52%   |
| SanDisk NVMe SSD Drive 512GB                        | 11        | 0.52%   |
| Samsung SSD 850 EVO 500GB                           | 11        | 0.52%   |
| Samsung SSD 860 EVO 500GB                           | 10        | 0.47%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 10        | 0.47%   |
| SK hynix NVMe SSD Drive 256GB                       | 8         | 0.38%   |
| Samsung SSD 870 EVO 1TB                             | 8         | 0.38%   |
| Samsung SSD 860 EVO 250GB                           | 8         | 0.38%   |
| HGST HTS725050A7E630 500GB                          | 8         | 0.38%   |
| Crucial CT480BX500SSD1 480GB                        | 8         | 0.38%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 7         | 0.33%   |
| Seagate ST9500420AS 500GB                           | 7         | 0.33%   |
| SanDisk X400 M.2 2280 256GB SSD                     | 7         | 0.33%   |
| Micron 2210_MTFDHBA512QFD 512GB                     | 7         | 0.33%   |
| Hitachi HTS545050A7E380 500GB                       | 7         | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 239       | 293    | 34.24%  |
| WDC                 | 170       | 201    | 24.36%  |
| Toshiba             | 138       | 152    | 19.77%  |
| HGST                | 56        | 66     | 8.02%   |
| Hitachi             | 52        | 63     | 7.45%   |
| Samsung Electronics | 13        | 13     | 1.86%   |
| Unknown             | 11        | 13     | 1.58%   |
| Fujitsu             | 10        | 11     | 1.43%   |
| JMicron Technology  | 2         | 2      | 0.29%   |
| Apple               | 2         | 2      | 0.29%   |
| USB3.0              | 1         | 1      | 0.14%   |
| SSK                 | 1         | 1      | 0.14%   |
| SABRENT             | 1         | 1      | 0.14%   |
| KESU                | 1         | 1      | 0.14%   |
| Intenso             | 1         | 1      | 0.14%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 137       | 185    | 19.11%  |
| Kingston            | 82        | 101    | 11.44%  |
| SanDisk             | 75        | 86     | 10.46%  |
| Crucial             | 74        | 87     | 10.32%  |
| WDC                 | 28        | 37     | 3.91%   |
| A-DATA Technology   | 26        | 30     | 3.63%   |
| China               | 24        | 30     | 3.35%   |
| Toshiba             | 22        | 25     | 3.07%   |
| Intel               | 20        | 25     | 2.79%   |
| Micron Technology   | 19        | 22     | 2.65%   |
| Apple               | 17        | 18     | 2.37%   |
| SK hynix            | 14        | 14     | 1.95%   |
| Netac               | 14        | 14     | 1.95%   |
| SPCC                | 13        | 16     | 1.81%   |
| PNY                 | 13        | 14     | 1.81%   |
| LITEONIT            | 11        | 13     | 1.53%   |
| Intenso             | 11        | 11     | 1.53%   |
| LITEON              | 10        | 12     | 1.39%   |
| Patriot             | 9         | 10     | 1.26%   |
| GOODRAM             | 9         | 10     | 1.26%   |
| Transcend           | 7         | 9      | 0.98%   |
| Team                | 6         | 7      | 0.84%   |
| OCZ                 | 5         | 6      | 0.7%    |
| Unknown             | 5         | 7      | 0.7%    |
| SABRENT             | 4         | 5      | 0.56%   |
| ASMT                | 4         | 4      | 0.56%   |
| Mushkin             | 3         | 3      | 0.42%   |
| Lexar               | 3         | 3      | 0.42%   |
| KingSpec            | 3         | 3      | 0.42%   |
| JMicron Technology  | 3         | 4      | 0.42%   |
| Hewlett-Packard     | 3         | 3      | 0.42%   |
| BHT                 | 3         | 4      | 0.42%   |
| Verbatim            | 2         | 2      | 0.28%   |
| Teclast             | 2         | 2      | 0.28%   |
| Plextor             | 2         | 2      | 0.28%   |
| HS-SSD-E100         | 2         | 2      | 0.28%   |
| Gigabyte Technology | 2         | 2      | 0.28%   |
| Apacer              | 2         | 2      | 0.28%   |
| ZOTAC               | 1         | 1      | 0.14%   |
| Vaseky              | 1         | 2      | 0.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 683       | 821    | 35.03%  |
| SSD     | 681       | 862    | 34.92%  |
| NVMe    | 370       | 483    | 18.97%  |
| MMC     | 191       | 253    | 9.79%   |
| Unknown | 25        | 27     | 1.28%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1259      | 1624   | 66.86%  |
| NVMe | 370       | 483    | 19.65%  |
| MMC  | 191       | 253    | 10.14%  |
| SAS  | 63        | 86     | 3.35%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 946       | 1174   | 70.07%  |
| 0.51-1.0   | 360       | 448    | 26.67%  |
| 1.01-2.0   | 31        | 42     | 2.3%    |
| 4.01-10.0  | 5         | 7      | 0.37%   |
| 10.01-20.0 | 4         | 5      | 0.3%    |
| 3.01-4.0   | 3         | 6      | 0.22%   |
| 2.01-3.0   | 1         | 1      | 0.07%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 607       | 34.87%  |
| 251-500        | 456       | 26.19%  |
| 501-1000       | 243       | 13.96%  |
| 51-100         | 167       | 9.59%   |
| 21-50          | 120       | 6.89%   |
| 1001-2000      | 53        | 3.04%   |
| 1-20           | 39        | 2.24%   |
| Unknown        | 21        | 1.21%   |
| More than 3000 | 19        | 1.09%   |
| 2001-3000      | 16        | 0.92%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 772       | 42.58%  |
| 21-50          | 515       | 28.41%  |
| 51-100         | 212       | 11.69%  |
| 101-250        | 172       | 9.49%   |
| 251-500        | 71        | 3.92%   |
| 501-1000       | 33        | 1.82%   |
| Unknown        | 21        | 1.16%   |
| More than 3000 | 7         | 0.39%   |
| 1001-2000      | 7         | 0.39%   |
| 2001-3000      | 3         | 0.17%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Toshiba MQ02ABD100H 1TB                          | 2         | 2      | 4.08%   |
| Toshiba MQ01ABD100 1TB                           | 2         | 2      | 4.08%   |
| SK hynix BC711 HFM512GD3JX013N 512GB             | 2         | 2      | 4.08%   |
| HGST HTS545050A7E380 500GB                       | 2         | 2      | 4.08%   |
| WDC WD6400BEVT-22A0RT0 640GB                     | 1         | 1      | 2.04%   |
| WDC WD5000LPVX-75V0TT0 500GB                     | 1         | 1      | 2.04%   |
| WDC WD5000BEVT-24A0RT0 500GB                     | 1         | 1      | 2.04%   |
| WDC WD1200BEVS-60UST0 120GB                      | 1         | 1      | 2.04%   |
| WDC WD10SPZX-75Z10T2 1TB                         | 1         | 1      | 2.04%   |
| WDC WD10JPVX-22JC3T0 1TB                         | 1         | 1      | 2.04%   |
| WDC WD10JPVT-55A1YT0 1TB                         | 1         | 1      | 2.04%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD             | 1         | 1      | 2.04%   |
| Toshiba MQ01ABF050 500GB                         | 1         | 1      | 2.04%   |
| Toshiba MQ01ABD075 752GB                         | 1         | 1      | 2.04%   |
| Teclast 128GB NS550-2242 SSD                     | 1         | 1      | 2.04%   |
| Seagate ST9500420AS 500GB                        | 1         | 1      | 2.04%   |
| Seagate ST9500325AS 500GB                        | 1         | 1      | 2.04%   |
| Seagate ST9320310AS 320GB                        | 1         | 1      | 2.04%   |
| Seagate ST9250315AS 250GB                        | 1         | 1      | 2.04%   |
| Seagate ST9200420ASG 200GB                       | 1         | 1      | 2.04%   |
| Seagate ST9160411ASG 160GB                       | 1         | 1      | 2.04%   |
| Seagate ST500LT012-9WS142 500GB                  | 1         | 1      | 2.04%   |
| Seagate ST500LT012-1DG142 500GB                  | 1         | 1      | 2.04%   |
| Seagate ST500LM000-SSHD-8GB                      | 1         | 1      | 2.04%   |
| Seagate ST320LT007-9ZV142 320GB                  | 1         | 1      | 2.04%   |
| Seagate ST1000LX015-1U7172 1TB                   | 1         | 1      | 2.04%   |
| Seagate ST1000LM048-2E7172 1TB                   | 1         | 1      | 2.04%   |
| Seagate ST1000LM035-1RK172 1TB                   | 1         | 1      | 2.04%   |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 1         | 1      | 2.04%   |
| Samsung Electronics MZHPV256HDGL-00000 256GB SSD | 1         | 1      | 2.04%   |
| Samsung Electronics MMCRE64G8MPP-0VA 64GB SSD    | 1         | 1      | 2.04%   |
| Samsung Electronics HM160JI 160GB                | 1         | 1      | 2.04%   |
| LITEONIT LCT-256M3S 2.5 7mm 256GB SSD            | 1         | 1      | 2.04%   |
| Kingston SUV400S37240G 240GB SSD                 | 1         | 1      | 2.04%   |
| Kingston SA400S37120G 120GB SSD                  | 1         | 1      | 2.04%   |
| Kingston RBU-SNS8152S3256GG2 256GB SSD           | 1         | 1      | 2.04%   |
| Hitachi HTS725032A9A364 320GB                    | 1         | 1      | 2.04%   |
| Hitachi HTS547575A9E384 752GB                    | 1         | 1      | 2.04%   |
| Hitachi HTS542516K9SA00 160GB                    | 1         | 1      | 2.04%   |
| HGST HTS725050A7E630 500GB                       | 1         | 1      | 2.04%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 14     | 28.57%  |
| WDC                 | 7         | 7      | 14.29%  |
| Toshiba             | 7         | 7      | 14.29%  |
| HGST                | 6         | 6      | 12.24%  |
| Samsung Electronics | 3         | 3      | 6.12%   |
| Kingston            | 3         | 3      | 6.12%   |
| Hitachi             | 3         | 3      | 6.12%   |
| SK hynix            | 2         | 2      | 4.08%   |
| Teclast             | 1         | 1      | 2.04%   |
| LITEONIT            | 1         | 1      | 2.04%   |
| Hewlett-Packard     | 1         | 1      | 2.04%   |
| Drevo               | 1         | 1      | 2.04%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 14     | 37.84%  |
| WDC                 | 7         | 7      | 18.92%  |
| Toshiba             | 6         | 6      | 16.22%  |
| HGST                | 6         | 6      | 16.22%  |
| Hitachi             | 3         | 3      | 8.11%   |
| Samsung Electronics | 1         | 1      | 2.7%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 37        | 37     | 75.51%  |
| SSD  | 10        | 10     | 20.41%  |
| NVMe | 2         | 2      | 4.08%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                          | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Seagate ST2000LX001-1RG174 2TB | 1         | 1      | 50%     |
| SanDisk SSD i100 24GB          | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 50%     |
| SanDisk | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1480      | 2144   | 85.16%  |
| Works    | 208       | 251    | 11.97%  |
| Malfunc  | 48        | 49     | 2.76%   |
| Failed   | 2         | 2      | 0.12%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1220      | 66.49%  |
| AMD                              | 217       | 11.83%  |
| Samsung Electronics              | 125       | 6.81%   |
| SanDisk                          | 70        | 3.81%   |
| SK hynix                         | 36        | 1.96%   |
| Micron Technology                | 28        | 1.53%   |
| KIOXIA                           | 19        | 1.04%   |
| Nvidia                           | 17        | 0.93%   |
| Kingston Technology Company      | 16        | 0.87%   |
| Toshiba America Info Systems     | 15        | 0.82%   |
| Phison Electronics               | 13        | 0.71%   |
| Silicon Motion                   | 9         | 0.49%   |
| ADATA Technology                 | 8         | 0.44%   |
| Micron/Crucial Technology        | 6         | 0.33%   |
| Lite-On Technology               | 5         | 0.27%   |
| Marvell Technology Group         | 4         | 0.22%   |
| ASMedia Technology               | 4         | 0.22%   |
| VIA Technologies                 | 3         | 0.16%   |
| Union Memory (Shenzhen)          | 3         | 0.16%   |
| Silicon Integrated Systems [SiS] | 3         | 0.16%   |
| Realtek Semiconductor            | 3         | 0.16%   |
| Yangtze Memory Technologies      | 2         | 0.11%   |
| MAXIO Technology (Hangzhou)      | 2         | 0.11%   |
| Apple                            | 2         | 0.11%   |
| Solid State Storage Technology   | 1         | 0.05%   |
| Silicon Image                    | 1         | 0.05%   |
| Seagate Technology               | 1         | 0.05%   |
| Lenovo                           | 1         | 0.05%   |
| Biwin Storage Technology         | 1         | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 187       | 9.42%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 162       | 8.16%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 121       | 6.1%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 114       | 5.74%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 108       | 5.44%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 76        | 3.83%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 64        | 3.22%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 64        | 3.22%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 52        | 2.62%   |
| Intel Volume Management Device NVMe RAID Controller                              | 49        | 2.47%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 46        | 2.32%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 44        | 2.22%   |
| Samsung NVMe SSD Controller 980                                                  | 41        | 2.07%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 40        | 2.02%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 37        | 1.86%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 34        | 1.71%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 32        | 1.61%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 30        | 1.51%   |
| Micron NVMe Storage Controller                                                   | 27        | 1.36%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 27        | 1.36%   |
| Intel Tiger Lake-LP SATA Controller                                              | 25        | 1.26%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 25        | 1.26%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 22        | 1.11%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 20        | 1.01%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 19        | 0.96%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 17        | 0.86%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 17        | 0.86%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 17        | 0.86%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 16        | 0.81%   |
| Intel Comet Lake SATA AHCI Controller                                            | 16        | 0.81%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 16        | 0.81%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 14        | 0.71%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 13        | 0.65%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 13        | 0.65%   |
| Intel SSD 660P Series                                                            | 13        | 0.65%   |
| Intel Non-Volatile memory controller                                             | 12        | 0.6%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 10        | 0.5%    |
| Nvidia MCP79 AHCI Controller                                                     | 9         | 0.45%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 9         | 0.45%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 9         | 0.45%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1262      | 65.83%  |
| NVMe | 371       | 19.35%  |
| RAID | 165       | 8.61%   |
| IDE  | 119       | 6.21%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 1423      | 83.85%  |
| AMD    | 274       | 16.15%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 25        | 1.47%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 24        | 1.41%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 23        | 1.36%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 22        | 1.3%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 22        | 1.3%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 20        | 1.18%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 20        | 1.18%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 18        | 1.06%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 18        | 1.06%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 18        | 1.06%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 18        | 1.06%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 17        | 1%      |
| Intel Core i5-5200U CPU @ 2.20GHz             | 17        | 1%      |
| Intel Core i5-4200U CPU @ 1.60GHz             | 17        | 1%      |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 15        | 0.88%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 15        | 0.88%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 14        | 0.82%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 14        | 0.82%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 14        | 0.82%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 14        | 0.82%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 13        | 0.77%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 13        | 0.77%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 13        | 0.77%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 13        | 0.77%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 12        | 0.71%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 12        | 0.71%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 12        | 0.71%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 12        | 0.71%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 11        | 0.65%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 11        | 0.65%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 11        | 0.65%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 11        | 0.65%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 10        | 0.59%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 10        | 0.59%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 10        | 0.59%   |
| Intel Core i5 CPU M 430 @ 2.27GHz             | 10        | 0.59%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 10        | 0.59%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 10        | 0.59%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 10        | 0.59%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 10        | 0.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5                        | 423       | 24.93%  |
| Intel Core i7                        | 278       | 16.38%  |
| Intel Core i3                        | 176       | 10.37%  |
| Intel Celeron                        | 155       | 9.13%   |
| Intel Core 2 Duo                     | 104       | 6.13%   |
| Other                                | 103       | 6.07%   |
| Intel Atom                           | 65        | 3.83%   |
| Intel Pentium                        | 61        | 3.59%   |
| AMD Ryzen 5                          | 55        | 3.24%   |
| AMD Ryzen 7                          | 38        | 2.24%   |
| AMD A6                               | 26        | 1.53%   |
| AMD A4                               | 25        | 1.47%   |
| AMD A8                               | 17        | 1%      |
| AMD A10                              | 17        | 1%      |
| Intel Pentium Dual-Core              | 14        | 0.82%   |
| Intel Pentium Dual                   | 11        | 0.65%   |
| AMD E1                               | 11        | 0.65%   |
| AMD Ryzen 3                          | 10        | 0.59%   |
| Intel Core 2                         | 9         | 0.53%   |
| AMD E                                | 9         | 0.53%   |
| Intel Pentium Silver                 | 8         | 0.47%   |
| AMD Turion 64 X2 Mobile              | 8         | 0.47%   |
| Intel Core M                         | 7         | 0.41%   |
| AMD Ryzen 9                          | 6         | 0.35%   |
| Intel Core m5                        | 5         | 0.29%   |
| AMD E2                               | 5         | 0.29%   |
| AMD Athlon II                        | 5         | 0.29%   |
| Intel Pentium Gold                   | 4         | 0.24%   |
| AMD Ryzen 7 PRO                      | 4         | 0.24%   |
| AMD Athlon                           | 4         | 0.24%   |
| Intel Genuine                        | 3         | 0.18%   |
| Intel Celeron Dual-Core              | 3         | 0.18%   |
| Intel Core i9                        | 2         | 0.12%   |
| Intel Celeron M                      | 2         | 0.12%   |
| AMD Turion X2 Ultra Dual-Core Mobile | 2         | 0.12%   |
| AMD Sempron                          | 2         | 0.12%   |
| AMD FX                               | 2         | 0.12%   |
| AMD Athlon II Neo                    | 2         | 0.12%   |
| Intel Xeon                           | 1         | 0.06%   |
| Intel Core 2 Extreme                 | 1         | 0.06%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1044      | 61.52%  |
| 4      | 500       | 29.46%  |
| 6      | 66        | 3.89%   |
| 8      | 55        | 3.24%   |
| 1      | 19        | 1.12%   |
| 10     | 6         | 0.35%   |
| 14     | 4         | 0.24%   |
| 24     | 1         | 0.06%   |
| 16     | 1         | 0.06%   |
| 3      | 1         | 0.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1697      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1111      | 65.47%  |
| 1      | 586       | 34.53%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1697      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x206a7    | 151       | 8.78%   |
| 0x306a9    | 148       | 8.61%   |
| Unknown    | 112       | 6.52%   |
| 0x40651    | 86        | 5%      |
| 0x1067a    | 69        | 4.01%   |
| 0x20655    | 66        | 3.84%   |
| 0x306d4    | 65        | 3.78%   |
| 0x806c1    | 61        | 3.55%   |
| 0x406e3    | 60        | 3.49%   |
| 0x30678    | 55        | 3.2%    |
| 0x806e9    | 48        | 2.79%   |
| 0x306c3    | 46        | 2.68%   |
| 0x806ea    | 44        | 2.56%   |
| 0x806ec    | 41        | 2.39%   |
| 0x406c4    | 41        | 2.39%   |
| 0x706a8    | 32        | 1.86%   |
| 0x506c9    | 30        | 1.75%   |
| 0x6fd      | 29        | 1.69%   |
| 0x906ea    | 28        | 1.63%   |
| 0x706e5    | 28        | 1.63%   |
| 0x406c3    | 26        | 1.51%   |
| 0x20652    | 25        | 1.45%   |
| 0x906e9    | 23        | 1.34%   |
| 0x10676    | 23        | 1.34%   |
| 0x07030105 | 21        | 1.22%   |
| 0x0a50000c | 20        | 1.16%   |
| 0x08108109 | 19        | 1.11%   |
| 0xa0652    | 18        | 1.05%   |
| 0x06006705 | 17        | 0.99%   |
| 0x08108102 | 16        | 0.93%   |
| 0x0700010f | 13        | 0.76%   |
| 0x506e3    | 12        | 0.7%    |
| 0x08608103 | 12        | 0.7%    |
| 0x08600106 | 12        | 0.7%    |
| 0x05000119 | 12        | 0.7%    |
| 0x706a1    | 11        | 0.64%   |
| 0x6fb      | 11        | 0.64%   |
| 0x06006704 | 11        | 0.64%   |
| 0x806d1    | 10        | 0.58%   |
| 0x010000c8 | 10        | 0.58%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 212       | 12.49%  |
| SandyBridge      | 156       | 9.19%   |
| IvyBridge        | 154       | 9.07%   |
| Haswell          | 142       | 8.37%   |
| Silvermont       | 130       | 7.66%   |
| Westmere         | 93        | 5.48%   |
| Penryn           | 92        | 5.42%   |
| Skylake          | 75        | 4.42%   |
| TigerLake        | 70        | 4.12%   |
| Broadwell        | 65        | 3.83%   |
| Core             | 57        | 3.36%   |
| Goldmont plus    | 46        | 2.71%   |
| Excavator        | 41        | 2.42%   |
| Icelake          | 39        | 2.3%    |
| Zen+             | 38        | 2.24%   |
| Goldmont         | 32        | 1.89%   |
| Puma             | 30        | 1.77%   |
| Zen 3            | 28        | 1.65%   |
| Zen 2            | 27        | 1.59%   |
| Unknown          | 26        | 1.53%   |
| CometLake        | 22        | 1.3%    |
| Jaguar           | 16        | 0.94%   |
| Bobcat           | 15        | 0.88%   |
| Piledriver       | 12        | 0.71%   |
| K10 Llano        | 11        | 0.65%   |
| K10              | 11        | 0.65%   |
| K8 Hammer        | 10        | 0.59%   |
| Nehalem          | 9         | 0.53%   |
| Alderlake Hybrid | 9         | 0.53%   |
| Bonnell          | 8         | 0.47%   |
| Zen              | 7         | 0.41%   |
| Tremont          | 6         | 0.35%   |
| K8 & K10 hybrid  | 5         | 0.29%   |
| Steamroller      | 3         | 0.18%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1283      | 63.02%  |
| AMD                              | 377       | 18.52%  |
| Nvidia                           | 371       | 18.22%  |
| Silicon Integrated Systems [SiS] | 3         | 0.15%   |
| VIA Technologies                 | 2         | 0.1%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 146       | 6.95%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 139       | 6.62%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 88        | 4.19%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 67        | 3.19%   |
| Intel Core Processor Integrated Graphics Controller                                      | 66        | 3.14%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 63        | 3%      |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 55        | 2.62%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 54        | 2.57%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 51        | 2.43%   |
| Intel HD Graphics 620                                                                    | 51        | 2.43%   |
| Intel UHD Graphics 620                                                                   | 44        | 2.1%    |
| Intel HD Graphics 5500                                                                   | 44        | 2.1%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 42        | 2%      |
| Intel GeminiLake [UHD Graphics 600]                                                      | 41        | 1.95%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 39        | 1.86%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 29        | 1.38%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 28        | 1.33%   |
| Intel HD Graphics 500                                                                    | 27        | 1.29%   |
| AMD Renoir                                                                               | 27        | 1.29%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 26        | 1.24%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 26        | 1.24%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 26        | 1.24%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 23        | 1.1%    |
| Intel HD Graphics 630                                                                    | 22        | 1.05%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 22        | 1.05%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 19        | 0.9%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 19        | 0.9%    |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 19        | 0.9%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 18        | 0.86%   |
| AMD Lucienne                                                                             | 17        | 0.81%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 16        | 0.76%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 16        | 0.76%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 16        | 0.76%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 15        | 0.71%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 15        | 0.71%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 14        | 0.67%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 12        | 0.57%   |
| Intel HD Graphics 530                                                                    | 12        | 0.57%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 12        | 0.57%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 11        | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 967       | 56.88%  |
| 1 x AMD        | 258       | 15.18%  |
| Intel + Nvidia | 246       | 14.47%  |
| 1 x Nvidia     | 97        | 5.71%   |
| Intel + AMD    | 66        | 3.88%   |
| 2 x AMD        | 28        | 1.65%   |
| AMD + Nvidia   | 26        | 1.53%   |
| Other          | 5         | 0.29%   |
| 1 x SiS        | 3         | 0.18%   |
| 2 x Nvidia     | 2         | 0.12%   |
| 1 x VIA        | 2         | 0.12%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1488      | 87.32%  |
| Proprietary | 191       | 11.21%  |
| Unknown     | 25        | 1.47%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1152      | 66.98%  |
| 0.01-0.5   | 218       | 12.67%  |
| 1.01-2.0   | 142       | 8.26%   |
| 0.51-1.0   | 117       | 6.8%    |
| 3.01-4.0   | 49        | 2.85%   |
| 5.01-6.0   | 17        | 0.99%   |
| 7.01-8.0   | 14        | 0.81%   |
| 2.01-3.0   | 10        | 0.58%   |
| 8.01-16.0  | 1         | 0.06%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 350       | 19.57%  |
| Chimei Innolux          | 260       | 14.54%  |
| LG Display              | 251       | 14.04%  |
| BOE                     | 245       | 13.7%   |
| Samsung Electronics     | 209       | 11.69%  |
| Chi Mei Optoelectronics | 58        | 3.24%   |
| Apple                   | 51        | 2.85%   |
| Sharp                   | 33        | 1.85%   |
| Dell                    | 32        | 1.79%   |
| Lenovo                  | 30        | 1.68%   |
| Goldstar                | 27        | 1.51%   |
| PANDA                   | 25        | 1.4%    |
| LG Philips              | 24        | 1.34%   |
| InfoVision              | 16        | 0.89%   |
| Hewlett-Packard         | 13        | 0.73%   |
| Acer                    | 11        | 0.62%   |
| CPT                     | 10        | 0.56%   |
| Philips                 | 9         | 0.5%    |
| BenQ                    | 9         | 0.5%    |
| Vizio                   | 8         | 0.45%   |
| Sony                    | 7         | 0.39%   |
| LGD                     | 6         | 0.34%   |
| AOC                     | 6         | 0.34%   |
| InnoLux Display         | 5         | 0.28%   |
| HannStar                | 5         | 0.28%   |
| Ancor Communications    | 5         | 0.28%   |
| Toshiba                 | 4         | 0.22%   |
| SLD                     | 4         | 0.22%   |
| Panasonic               | 4         | 0.22%   |
| KDC                     | 4         | 0.22%   |
| BOE Technology Group    | 4         | 0.22%   |
| ASUSTek Computer        | 4         | 0.22%   |
| TMX                     | 3         | 0.17%   |
| Iiyama                  | 3         | 0.17%   |
| Unknown                 | 3         | 0.17%   |
| SANYO                   | 2         | 0.11%   |
| Quanta Display          | 2         | 0.11%   |
| JDI                     | 2         | 0.11%   |
| ITE                     | 2         | 0.11%   |
| GDH                     | 2         | 0.11%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch     | 20        | 1.11%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 14        | 0.78%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 14        | 0.78%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 14        | 0.78%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 13        | 0.72%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 13        | 0.72%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 12        | 0.67%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 11        | 0.61%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 11        | 0.61%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 10        | 0.56%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 9         | 0.5%    |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 9         | 0.5%    |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 9         | 0.5%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 8         | 0.44%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 8         | 0.44%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 8         | 0.44%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 8         | 0.44%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 7         | 0.39%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                    | 7         | 0.39%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 7         | 0.39%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 7         | 0.39%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 239x134mm 10.8-inch    | 6         | 0.33%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 6         | 0.33%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 6         | 0.33%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch          | 6         | 0.33%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 6         | 0.33%   |
| AU Optronics LCD Monitor AUO405C 1366x768 256x144mm 11.6-inch            | 6         | 0.33%   |
| AU Optronics LCD Monitor AUO159E 1600x900 382x214mm 17.2-inch            | 6         | 0.33%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch           | 6         | 0.33%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch     | 5         | 0.28%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 344x193mm 15.5-inch     | 5         | 0.28%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 5         | 0.28%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 5         | 0.28%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 5         | 0.28%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch                  | 5         | 0.28%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 5         | 0.28%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch          | 5         | 0.28%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 5         | 0.28%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 5         | 0.28%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 5         | 0.28%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 729       | 42.19%  |
| 1920x1080 (FHD)    | 553       | 32%     |
| 1600x900 (HD+)     | 114       | 6.6%    |
| 1280x800 (WXGA)    | 91        | 5.27%   |
| 3840x2160 (4K)     | 39        | 2.26%   |
| 1440x900 (WXGA+)   | 39        | 2.26%   |
| 2560x1600          | 18        | 1.04%   |
| 2560x1440 (QHD)    | 18        | 1.04%   |
| 1920x1200 (WUXGA)  | 14        | 0.81%   |
| 1680x1050 (WSXGA+) | 13        | 0.75%   |
| 1280x1024 (SXGA)   | 10        | 0.58%   |
| 2880x1800          | 8         | 0.46%   |
| 2256x1504          | 8         | 0.46%   |
| 2160x1440          | 8         | 0.46%   |
| 1360x768           | 8         | 0.46%   |
| Unknown            | 7         | 0.41%   |
| 3200x1800 (QHD+)   | 6         | 0.35%   |
| 2560x1080          | 6         | 0.35%   |
| 3840x2400          | 5         | 0.29%   |
| 1920x540           | 5         | 0.29%   |
| 1024x600           | 4         | 0.23%   |
| 3840x1080          | 3         | 0.17%   |
| 3440x1440          | 3         | 0.17%   |
| 5760x1080          | 2         | 0.12%   |
| 2880x1920          | 2         | 0.12%   |
| 1920x515           | 2         | 0.12%   |
| 4480x1600          | 1         | 0.06%   |
| 3840x1200          | 1         | 0.06%   |
| 3600x1080          | 1         | 0.06%   |
| 3072x1920          | 1         | 0.06%   |
| 3000x2000          | 1         | 0.06%   |
| 2304x1440          | 1         | 0.06%   |
| 2288x1287          | 1         | 0.06%   |
| 2240x1400          | 1         | 0.06%   |
| 1920x1280          | 1         | 0.06%   |
| 1680x945           | 1         | 0.06%   |
| 1600x1200          | 1         | 0.06%   |
| 1280x768           | 1         | 0.06%   |
| 1280x720 (HD)      | 1         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 768       | 43.17%  |
| 13      | 261       | 14.67%  |
| 14      | 208       | 11.69%  |
| 17      | 151       | 8.49%   |
| 11      | 76        | 4.27%   |
| 12      | 52        | 2.92%   |
| Unknown | 33        | 1.85%   |
| 27      | 31        | 1.74%   |
| 24      | 30        | 1.69%   |
| 23      | 22        | 1.24%   |
| 18      | 20        | 1.12%   |
| 21      | 16        | 0.9%    |
| 16      | 16        | 0.9%    |
| 34      | 12        | 0.67%   |
| 31      | 12        | 0.67%   |
| 19      | 9         | 0.51%   |
| 10      | 9         | 0.51%   |
| 40      | 6         | 0.34%   |
| 22      | 6         | 0.34%   |
| 20      | 6         | 0.34%   |
| 84      | 3         | 0.17%   |
| 72      | 3         | 0.17%   |
| 54      | 3         | 0.17%   |
| 32      | 3         | 0.17%   |
| 25      | 3         | 0.17%   |
| 52      | 2         | 0.11%   |
| 49      | 2         | 0.11%   |
| 47      | 2         | 0.11%   |
| 37      | 2         | 0.11%   |
| 26      | 2         | 0.11%   |
| 74      | 1         | 0.06%   |
| 65      | 1         | 0.06%   |
| 64      | 1         | 0.06%   |
| 58      | 1         | 0.06%   |
| 48      | 1         | 0.06%   |
| 42      | 1         | 0.06%   |
| 39      | 1         | 0.06%   |
| 36      | 1         | 0.06%   |
| 29      | 1         | 0.06%   |
| 8       | 1         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 1099      | 62.02%  |
| 201-300     | 259       | 14.62%  |
| 351-400     | 181       | 10.21%  |
| 501-600     | 79        | 4.46%   |
| 401-500     | 56        | 3.16%   |
| Unknown     | 33        | 1.86%   |
| 601-700     | 18        | 1.02%   |
| 701-800     | 16        | 0.9%    |
| 1001-1500   | 13        | 0.73%   |
| 801-900     | 9         | 0.51%   |
| 1501-2000   | 7         | 0.4%    |
| 101-200     | 1         | 0.06%   |
| 901-1000    | 1         | 0.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1384      | 84.34%  |
| 16/10   | 181       | 11.03%  |
| Unknown | 24        | 1.46%   |
| 3/2     | 23        | 1.4%    |
| 21/9    | 11        | 0.67%   |
| 5/4     | 8         | 0.49%   |
| 4/3     | 5         | 0.3%    |
| 32/9    | 2         | 0.12%   |
| 3.73    | 2         | 0.12%   |
| 0.62    | 1         | 0.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 767       | 43.14%  |
| 81-90          | 387       | 21.77%  |
| 121-130        | 126       | 7.09%   |
| 71-80          | 82        | 4.61%   |
| 51-60          | 76        | 4.27%   |
| 201-250        | 66        | 3.71%   |
| 61-70          | 50        | 2.81%   |
| Unknown        | 33        | 1.86%   |
| 301-350        | 32        | 1.8%    |
| 351-500        | 27        | 1.52%   |
| 141-150        | 24        | 1.35%   |
| 151-200        | 23        | 1.29%   |
| More than 1000 | 18        | 1.01%   |
| 131-140        | 18        | 1.01%   |
| 111-120        | 14        | 0.79%   |
| 501-1000       | 14        | 0.79%   |
| 41-50          | 9         | 0.51%   |
| 91-100         | 6         | 0.34%   |
| 251-300        | 5         | 0.28%   |
| 1-40           | 1         | 0.06%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 731       | 41.7%   |
| 121-160       | 583       | 33.26%  |
| 51-100        | 250       | 14.26%  |
| 161-240       | 100       | 5.7%    |
| Unknown       | 33        | 1.88%   |
| More than 240 | 32        | 1.83%   |
| 1-50          | 24        | 1.37%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1488      | 86.51%  |
| 2     | 195       | 11.34%  |
| 0     | 22        | 1.28%   |
| 3     | 13        | 0.76%   |
| 5     | 1         | 0.06%   |
| 4     | 1         | 0.06%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 858       | 32.23%  |
| Intel                             | 744       | 27.95%  |
| Qualcomm Atheros                  | 439       | 16.49%  |
| Broadcom                          | 239       | 8.98%   |
| Broadcom Limited                  | 78        | 2.93%   |
| Ralink                            | 33        | 1.24%   |
| Marvell Technology Group          | 31        | 1.16%   |
| MediaTek                          | 23        | 0.86%   |
| TP-Link                           | 20        | 0.75%   |
| ASIX Electronics                  | 17        | 0.64%   |
| Samsung Electronics               | 15        | 0.56%   |
| Nvidia                            | 15        | 0.56%   |
| Dell                              | 15        | 0.56%   |
| Ralink Technology                 | 13        | 0.49%   |
| Hewlett-Packard                   | 10        | 0.38%   |
| Xiaomi                            | 9         | 0.34%   |
| JMicron Technology                | 9         | 0.34%   |
| DisplayLink                       | 9         | 0.34%   |
| Sierra Wireless                   | 7         | 0.26%   |
| Huawei Technologies               | 7         | 0.26%   |
| Qualcomm                          | 6         | 0.23%   |
| OPPO Electronics                  | 5         | 0.19%   |
| NetGear                           | 5         | 0.19%   |
| Ericsson Business Mobile Networks | 5         | 0.19%   |
| OnePlus Technology (Shenzhen)     | 4         | 0.15%   |
| Edimax Technology                 | 4         | 0.15%   |
| Silicon Integrated Systems [SiS]  | 3         | 0.11%   |
| Qualcomm Atheros Communications   | 3         | 0.11%   |
| Google                            | 3         | 0.11%   |
| D-Link System                     | 3         | 0.11%   |
| ASUSTek Computer                  | 3         | 0.11%   |
| VIA Technologies                  | 2         | 0.08%   |
| T & A Mobile Phones               | 2         | 0.08%   |
| Linksys                           | 2         | 0.08%   |
| ZyXEL Communications              | 1         | 0.04%   |
| ZyDAS                             | 1         | 0.04%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.04%   |
| U-Blox                            | 1         | 0.04%   |
| TRENDnet                          | 1         | 0.04%   |
| Shenzhen Goodix Technology        | 1         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 467       | 14.83%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 207       | 6.58%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 95        | 3.02%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 76        | 2.41%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 70        | 2.22%   |
| Intel Wireless 7260                                               | 70        | 2.22%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 65        | 2.06%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 61        | 1.94%   |
| Intel Wireless 7265                                               | 57        | 1.81%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 51        | 1.62%   |
| Broadcom BCM43142 802.11b/g/n                                     | 48        | 1.52%   |
| Intel Wireless 8265 / 8275                                        | 47        | 1.49%   |
| Intel Wi-Fi 6 AX201                                               | 45        | 1.43%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 41        | 1.3%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 41        | 1.3%    |
| Intel Wi-Fi 6 AX200                                               | 40        | 1.27%   |
| Intel Wireless 8260                                               | 37        | 1.18%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 33        | 1.05%   |
| Intel Wireless 3165                                               | 33        | 1.05%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 31        | 0.98%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 29        | 0.92%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 27        | 0.86%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 24        | 0.76%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 23        | 0.73%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 23        | 0.73%   |
| Intel WiFi Link 5100                                              | 22        | 0.7%    |
| Intel Ethernet Connection I218-LM                                 | 22        | 0.7%    |
| Intel Centrino Ultimate-N 6300                                    | 22        | 0.7%    |
| Realtek RTL8188EE Wireless Network Adapter                        | 21        | 0.67%   |
| Intel Ethernet Connection I217-LM                                 | 21        | 0.67%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 20        | 0.64%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 19        | 0.6%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 19        | 0.6%    |
| Intel 82577LM Gigabit Network Connection                          | 19        | 0.6%    |
| Intel Wireless 3160                                               | 18        | 0.57%   |
| Intel Ethernet Connection I219-LM                                 | 16        | 0.51%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                         | 16        | 0.51%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 15        | 0.48%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 15        | 0.48%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 15        | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 714       | 41.34%  |
| Qualcomm Atheros                | 371       | 21.48%  |
| Realtek Semiconductor           | 280       | 16.21%  |
| Broadcom                        | 190       | 11%     |
| Broadcom Limited                | 50        | 2.9%    |
| Ralink                          | 33        | 1.91%   |
| MediaTek                        | 21        | 1.22%   |
| Ralink Technology               | 13        | 0.75%   |
| TP-Link                         | 12        | 0.69%   |
| Sierra Wireless                 | 7         | 0.41%   |
| Dell                            | 7         | 0.41%   |
| NetGear                         | 5         | 0.29%   |
| Edimax Technology               | 4         | 0.23%   |
| Qualcomm Atheros Communications | 3         | 0.17%   |
| D-Link System                   | 3         | 0.17%   |
| Linksys                         | 2         | 0.12%   |
| ASUSTek Computer                | 2         | 0.12%   |
| ZyXEL Communications            | 1         | 0.06%   |
| ZyDAS                           | 1         | 0.06%   |
| TRENDnet                        | 1         | 0.06%   |
| Realtek                         | 1         | 0.06%   |
| Qualcomm                        | 1         | 0.06%   |
| Mercucys                        | 1         | 0.06%   |
| Hewlett-Packard                 | 1         | 0.06%   |
| Fibocom                         | 1         | 0.06%   |
| Belkin Components               | 1         | 0.06%   |
| Askey Computer                  | 1         | 0.06%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 95        | 5.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 70        | 4.01%   |
| Intel Wireless 7260                                                     | 70        | 4.01%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 65        | 3.73%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 61        | 3.5%    |
| Intel Wireless 7265                                                     | 57        | 3.27%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 51        | 2.92%   |
| Broadcom BCM43142 802.11b/g/n                                           | 48        | 2.75%   |
| Intel Wireless 8265 / 8275                                              | 47        | 2.69%   |
| Intel Wi-Fi 6 AX201                                                     | 45        | 2.58%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 41        | 2.35%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 41        | 2.35%   |
| Intel Wi-Fi 6 AX200                                                     | 40        | 2.29%   |
| Intel Wireless 8260                                                     | 37        | 2.12%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 33        | 1.89%   |
| Intel Wireless 3165                                                     | 33        | 1.89%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 29        | 1.66%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 27        | 1.55%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 24        | 1.38%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 23        | 1.32%   |
| Intel WiFi Link 5100                                                    | 22        | 1.26%   |
| Intel Centrino Ultimate-N 6300                                          | 22        | 1.26%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 21        | 1.2%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 19        | 1.09%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 19        | 1.09%   |
| Intel Wireless 3160                                                     | 18        | 1.03%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 16        | 0.92%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 15        | 0.86%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 15        | 0.86%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 15        | 0.86%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 15        | 0.86%   |
| Intel Centrino Advanced-N 6235                                          | 15        | 0.86%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 14        | 0.8%    |
| Realtek 802.11n WLAN Adapter                                            | 14        | 0.8%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 14        | 0.8%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 14        | 0.8%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 14        | 0.8%    |
| Intel Centrino Advanced-N 6200                                          | 14        | 0.8%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 13        | 0.75%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 13        | 0.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 726       | 53.23%  |
| Intel                            | 269       | 19.72%  |
| Qualcomm Atheros                 | 111       | 8.14%   |
| Broadcom                         | 80        | 5.87%   |
| Marvell Technology Group         | 31        | 2.27%   |
| Broadcom Limited                 | 30        | 2.2%    |
| ASIX Electronics                 | 17        | 1.25%   |
| Nvidia                           | 15        | 1.1%    |
| Samsung Electronics              | 10        | 0.73%   |
| Xiaomi                           | 9         | 0.66%   |
| JMicron Technology               | 9         | 0.66%   |
| DisplayLink                      | 9         | 0.66%   |
| TP-Link                          | 8         | 0.59%   |
| Qualcomm                         | 5         | 0.37%   |
| OPPO Electronics                 | 5         | 0.37%   |
| Huawei Technologies              | 5         | 0.37%   |
| Silicon Integrated Systems [SiS] | 3         | 0.22%   |
| Hewlett-Packard                  | 3         | 0.22%   |
| Google                           | 3         | 0.22%   |
| VIA Technologies                 | 2         | 0.15%   |
| OnePlus Technology (Shenzhen)    | 2         | 0.15%   |
| MediaTek                         | 2         | 0.15%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.07%   |
| Novatel Wireless                 | 1         | 0.07%   |
| Motorola PCS                     | 1         | 0.07%   |
| Motorola BCS                     | 1         | 0.07%   |
| LG Electronics                   | 1         | 0.07%   |
| Lenovo                           | 1         | 0.07%   |
| ICS Advent                       | 1         | 0.07%   |
| HMD Global                       | 1         | 0.07%   |
| GoPro                            | 1         | 0.07%   |
| ASUSTek Computer                 | 1         | 0.07%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 467       | 34.09%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 207       | 15.11%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 76        | 5.55%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 31        | 2.26%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 23        | 1.68%   |
| Intel Ethernet Connection I218-LM                                 | 22        | 1.61%   |
| Intel Ethernet Connection I217-LM                                 | 21        | 1.53%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 20        | 1.46%   |
| Intel 82577LM Gigabit Network Connection                          | 19        | 1.39%   |
| Intel Ethernet Connection I219-LM                                 | 16        | 1.17%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 15        | 1.09%   |
| Intel 82567LM Gigabit Network Connection                          | 15        | 1.09%   |
| ASIX AX88179 Gigabit Ethernet                                     | 15        | 1.09%   |
| Intel Ethernet Connection (4) I219-LM                             | 13        | 0.95%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 13        | 0.95%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 12        | 0.88%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 12        | 0.88%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 11        | 0.8%    |
| Intel Ethernet Connection I219-V                                  | 11        | 0.8%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 10        | 0.73%   |
| Intel Ethernet Connection (3) I218-LM                             | 10        | 0.73%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 10        | 0.73%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 10        | 0.73%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 9         | 0.66%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 9         | 0.66%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 9         | 0.66%   |
| Intel Ethernet Connection (4) I219-V                              | 9         | 0.66%   |
| Nvidia MCP79 Ethernet                                             | 8         | 0.58%   |
| Intel 82566MM Gigabit Network Connection                          | 8         | 0.58%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 7         | 0.51%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 7         | 0.51%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 6         | 0.44%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 6         | 0.44%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 6         | 0.44%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 6         | 0.44%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 6         | 0.44%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 5         | 0.36%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 5         | 0.36%   |
| OPPO SM8350-MTP _SN:1518BD09                                      | 5         | 0.36%   |
| Intel Ethernet Connection (2) I219-LM                             | 5         | 0.36%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1633      | 54.85%  |
| Ethernet | 1310      | 44%     |
| Modem    | 29        | 0.97%   |
| Unknown  | 5         | 0.17%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1394      | 79.57%  |
| Ethernet | 357       | 20.38%  |
| Unknown  | 1         | 0.06%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1208      | 71.1%   |
| 1     | 404       | 23.78%  |
| 0     | 80        | 4.71%   |
| 3     | 7         | 0.41%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1192      | 69.26%  |
| Yes  | 529       | 30.74%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 506       | 40.91%  |
| Qualcomm Atheros Communications | 151       | 12.21%  |
| Realtek Semiconductor           | 139       | 11.24%  |
| Broadcom                        | 84        | 6.79%   |
| IMC Networks                    | 67        | 5.42%   |
| Apple                           | 47        | 3.8%    |
| Lite-On Technology              | 45        | 3.64%   |
| Foxconn / Hon Hai               | 44        | 3.56%   |
| Dell                            | 32        | 2.59%   |
| Hewlett-Packard                 | 27        | 2.18%   |
| Toshiba                         | 23        | 1.86%   |
| Cambridge Silicon Radio         | 20        | 1.62%   |
| Ralink                          | 15        | 1.21%   |
| ASUSTek Computer                | 10        | 0.81%   |
| Realtek                         | 6         | 0.49%   |
| Foxconn International           | 6         | 0.49%   |
| Alps Electric                   | 5         | 0.4%    |
| Integrated System Solution      | 2         | 0.16%   |
| Askey Computer                  | 2         | 0.16%   |
| Ralink Technology               | 1         | 0.08%   |
| Qcom                            | 1         | 0.08%   |
| MediaTek                        | 1         | 0.08%   |
| Chicony Electronics             | 1         | 0.08%   |
| Belkin Components               | 1         | 0.08%   |
| Unknown                         | 1         | 0.08%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 251       | 20.27%  |
| Realtek Bluetooth Radio                             | 89        | 7.19%   |
| Intel AX201 Bluetooth                               | 77        | 6.22%   |
| Qualcomm Atheros  Bluetooth Device                  | 66        | 5.33%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 66        | 5.33%   |
| Intel AX200 Bluetooth                               | 38        | 3.07%   |
| Realtek  Bluetooth 4.2 Adapter                      | 35        | 2.83%   |
| Apple Bluetooth Host Controller                     | 31        | 2.5%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 26        | 2.1%    |
| IMC Networks Bluetooth Device                       | 25        | 2.02%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 23        | 1.86%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 21        | 1.7%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 20        | 1.62%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 20        | 1.62%   |
| Intel Bluetooth Device                              | 18        | 1.45%   |
| IMC Networks Bluetooth Radio                        | 17        | 1.37%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 16        | 1.29%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 16        | 1.29%   |
| Lite-On Atheros AR3012 Bluetooth                    | 16        | 1.29%   |
| Ralink RT3290 Bluetooth                             | 15        | 1.21%   |
| Intel AX210 Bluetooth                               | 14        | 1.13%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 14        | 1.13%   |
| Foxconn / Hon Hai Bluetooth Device                  | 14        | 1.13%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 13        | 1.05%   |
| HP Broadcom 2070 Bluetooth Combo                    | 13        | 1.05%   |
| Dell DW375 Bluetooth Module                         | 13        | 1.05%   |
| IMC Networks Wireless_Device                        | 12        | 0.97%   |
| Broadcom BCM2045B (BDC-2.1)                         | 12        | 0.97%   |
| Intel Wireless-AC 3168 Bluetooth                    | 9         | 0.73%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 9         | 0.73%   |
| Toshiba Bluetooth Device                            | 8         | 0.65%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 8         | 0.65%   |
| Realtek RTL8723B Bluetooth                          | 7         | 0.57%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 7         | 0.57%   |
| Dell BCM20702A0 Bluetooth Module                    | 7         | 0.57%   |
| Apple Bluetooth USB Host Controller                 | 7         | 0.57%   |
| Realtek Bluetooth Radio                             | 6         | 0.48%   |
| Lite-On Bluetooth Device                            | 6         | 0.48%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 6         | 0.48%   |
| Foxconn International BCM43142A0 Bluetooth module   | 6         | 0.48%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1352      | 69.26%  |
| AMD                                  | 320       | 16.39%  |
| Nvidia                               | 225       | 11.53%  |
| Generalplus Technology               | 5         | 0.26%   |
| Realtek Semiconductor                | 4         | 0.2%    |
| SteelSeries ApS                      | 3         | 0.15%   |
| Silicon Integrated Systems [SiS]     | 3         | 0.15%   |
| Logitech                             | 3         | 0.15%   |
| Lenovo                               | 3         | 0.15%   |
| JMTek                                | 3         | 0.15%   |
| C-Media Electronics                  | 3         | 0.15%   |
| VIA Technologies                     | 2         | 0.1%    |
| Tenx Technology                      | 2         | 0.1%    |
| Focusrite-Novation                   | 2         | 0.1%    |
| DSEA A/S                             | 2         | 0.1%    |
| DCMT Technology                      | 2         | 0.1%    |
| Corsair                              | 2         | 0.1%    |
| Thesycon Systemsoftware & Consulting | 1         | 0.05%   |
| Texas Instruments                    | 1         | 0.05%   |
| Sony                                 | 1         | 0.05%   |
| SAVITECH                             | 1         | 0.05%   |
| Roland                               | 1         | 0.05%   |
| Razer USA                            | 1         | 0.05%   |
| PreSonus Audio Electronics           | 1         | 0.05%   |
| Plantronics                          | 1         | 0.05%   |
| Kingston Technology                  | 1         | 0.05%   |
| GN Netcom                            | 1         | 0.05%   |
| Dell                                 | 1         | 0.05%   |
| Creative Technology                  | 1         | 0.05%   |
| Conexant Systems                     | 1         | 0.05%   |
| CMX Systems                          | 1         | 0.05%   |
| ASUSTek Computer                     | 1         | 0.05%   |
| Antelope Audio                       | 1         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 184       | 7.71%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 163       | 6.83%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 126       | 5.28%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 117       | 4.9%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 102       | 4.27%   |
| Intel 8 Series HD Audio Controller                                                                | 89        | 3.73%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 85        | 3.56%   |
| AMD FCH Azalia Controller                                                                         | 79        | 3.31%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 78        | 3.27%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 70        | 2.93%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 65        | 2.72%   |
| Intel Broadwell-U Audio Controller                                                                | 65        | 2.72%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 59        | 2.47%   |
| AMD Kabini HDMI/DP Audio                                                                          | 58        | 2.43%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 53        | 2.22%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 46        | 1.93%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 44        | 1.84%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 44        | 1.84%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 40        | 1.68%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 40        | 1.68%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 39        | 1.63%   |
| Intel Cannon Lake PCH cAVS                                                                        | 34        | 1.42%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 33        | 1.38%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 32        | 1.34%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 29        | 1.21%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 29        | 1.21%   |
| AMD High Definition Audio Controller                                                              | 29        | 1.21%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 28        | 1.17%   |
| Intel CM238 HD Audio Controller                                                                   | 26        | 1.09%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 26        | 1.09%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 25        | 1.05%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 25        | 1.05%   |
| Intel Comet Lake PCH cAVS                                                                         | 21        | 0.88%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 18        | 0.75%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 15        | 0.63%   |
| Nvidia High Definition Audio Controller                                                           | 15        | 0.63%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 14        | 0.59%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 14        | 0.59%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 12        | 0.5%    |
| AMD Wrestler HDMI Audio                                                                           | 12        | 0.5%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Samsung Electronics    | 124       | 28.57%  |
| SK hynix               | 96        | 22.12%  |
| Micron Technology      | 54        | 12.44%  |
| Kingston               | 28        | 6.45%   |
| Unknown                | 24        | 5.53%   |
| Unknown (ABCD)         | 17        | 3.92%   |
| Crucial                | 17        | 3.92%   |
| A-DATA Technology      | 11        | 2.53%   |
| Elpida                 | 10        | 2.3%    |
| Ramaxel Technology     | 8         | 1.84%   |
| Smart                  | 4         | 0.92%   |
| Nanya Technology       | 4         | 0.92%   |
| Timetec                | 2         | 0.46%   |
| Teikon                 | 2         | 0.46%   |
| Patriot                | 2         | 0.46%   |
| G.Skill                | 2         | 0.46%   |
| ff                     | 2         | 0.46%   |
| fef5                   | 2         | 0.46%   |
| Corsair                | 2         | 0.46%   |
| 4ea5                   | 2         | 0.46%   |
| Unknown (08B5)         | 1         | 0.23%   |
| Unknown (07F7)         | 1         | 0.23%   |
| Unknown (000080B30080) | 1         | 0.23%   |
| Transcend              | 1         | 0.23%   |
| Team                   | 1         | 0.23%   |
| Strontium              | 1         | 0.23%   |
| SHARETRONIC            | 1         | 0.23%   |
| Qimonda                | 1         | 0.23%   |
| PUSKILL                | 1         | 0.23%   |
| ProMos/Mosel Vitelic   | 1         | 0.23%   |
| PNY                    | 1         | 0.23%   |
| Netlist                | 1         | 0.23%   |
| Kllisre                | 1         | 0.23%   |
| Kingmax                | 1         | 0.23%   |
| GSkill                 | 1         | 0.23%   |
| Essencore              | 1         | 0.23%   |
| CSX                    | 1         | 0.23%   |
| Axiom                  | 1         | 0.23%   |
| Avant                  | 1         | 0.23%   |
| Apacer                 | 1         | 0.23%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 15        | 3.28%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 1.53%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 7         | 1.53%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 7         | 1.53%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 1.31%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 1.31%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 1.31%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 5         | 1.09%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 1.09%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.88%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.88%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.88%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.88%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 4         | 0.88%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.88%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 4         | 0.88%   |
| Samsung RAM M471A1G44BB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 4         | 0.88%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 4         | 0.88%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 3         | 0.66%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 0.66%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.66%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.66%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 3         | 0.66%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 3         | 0.66%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 3         | 0.66%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 0.66%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 3         | 0.66%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 3         | 0.66%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.66%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 0.66%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 0.66%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 3         | 0.66%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 3         | 0.66%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 3         | 0.66%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 3         | 0.66%   |
| Kingston RAM ACR16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s           | 3         | 0.66%   |
| Elpida RAM EBJ21UE8BDS0-DJ-F 2GB SODIMM DDR3 1334MT/s            | 3         | 0.66%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 3         | 0.66%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 2         | 0.44%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 2         | 0.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 149       | 41.05%  |
| DDR3    | 138       | 38.02%  |
| LPDDR4  | 33        | 9.09%   |
| LPDDR3  | 16        | 4.41%   |
| DDR2    | 15        | 4.13%   |
| SDRAM   | 6         | 1.65%   |
| Unknown | 3         | 0.83%   |
| DDR5    | 2         | 0.55%   |
| LPDDR5  | 1         | 0.28%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 310       | 85.16%  |
| Row Of Chips | 37        | 10.16%  |
| Unknown      | 7         | 1.92%   |
| DIMM         | 6         | 1.65%   |
| Chip         | 4         | 1.1%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 147       | 36.3%   |
| 4096  | 137       | 33.83%  |
| 2048  | 65        | 16.05%  |
| 16384 | 37        | 9.14%   |
| 1024  | 13        | 3.21%   |
| 32768 | 5         | 1.23%   |
| 512   | 1         | 0.25%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 92        | 23.41%  |
| 3200    | 67        | 17.05%  |
| 2667    | 65        | 16.54%  |
| 2400    | 43        | 10.94%  |
| 1334    | 24        | 6.11%   |
| 1333    | 14        | 3.56%   |
| 2133    | 13        | 3.31%   |
| 667     | 11        | 2.8%    |
| 4267    | 9         | 2.29%   |
| 3266    | 7         | 1.78%   |
| 1867    | 7         | 1.78%   |
| 1066    | 7         | 1.78%   |
| Unknown | 6         | 1.53%   |
| 800     | 5         | 1.27%   |
| 2048    | 4         | 1.02%   |
| 1067    | 4         | 1.02%   |
| 8400    | 3         | 0.76%   |
| 975     | 3         | 0.76%   |
| 6400    | 2         | 0.51%   |
| 4800    | 2         | 0.51%   |
| 4199    | 2         | 0.51%   |
| 4266    | 1         | 0.25%   |
| 3733    | 1         | 0.25%   |
| 2933    | 1         | 0.25%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 6         | 42.86%  |
| Seiko Epson           | 3         | 21.43%  |
| Canon                 | 2         | 14.29%  |
| Zebra                 | 1         | 7.14%   |
| Samsung Electronics   | 1         | 7.14%   |
| Lexmark International | 1         | 7.14%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                             | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| HP ENVY Photo 6200 series         | 2         | 14.29%  |
| Zebra ZP 450 Printer              | 1         | 7.14%   |
| Seiko Epson L3110 Series          | 1         | 7.14%   |
| Seiko Epson ET-2810 Series        | 1         | 7.14%   |
| Seiko Epson AcuLaser C1700        | 1         | 7.14%   |
| Samsung M2020 Series              | 1         | 7.14%   |
| Lexmark International 2400 series | 1         | 7.14%   |
| HP LaserJet 1200                  | 1         | 7.14%   |
| HP LaserJet 1000                  | 1         | 7.14%   |
| HP DeskJet 2300 series            | 1         | 7.14%   |
| HP DeskJet 1110 series            | 1         | 7.14%   |
| Canon TS3100 series               | 1         | 7.14%   |
| Canon PIXMA MG3000 series         | 1         | 7.14%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 2         | 50%     |
| Canon       | 2         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-X750 [Perfection 4490 Photo] | 2         | 50%     |
| Canon CanoScan LiDE 90                      | 1         | 25%     |
| Canon CanoScan LIDE 25                      | 1         | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 349       | 23.87%  |
| Microdia                               | 141       | 9.64%   |
| Realtek Semiconductor                  | 135       | 9.23%   |
| IMC Networks                           | 125       | 8.55%   |
| Sunplus Innovation Technology          | 87        | 5.95%   |
| Quanta                                 | 71        | 4.86%   |
| Cheng Uei Precision Industry (Foxlink) | 71        | 4.86%   |
| Suyin                                  | 58        | 3.97%   |
| Bison Electronics                      | 58        | 3.97%   |
| Acer                                   | 49        | 3.35%   |
| Syntek                                 | 42        | 2.87%   |
| Apple                                  | 40        | 2.74%   |
| Silicon Motion                         | 29        | 1.98%   |
| Lite-On Technology                     | 25        | 1.71%   |
| Alcor Micro                            | 25        | 1.71%   |
| Ricoh                                  | 17        | 1.16%   |
| Luxvisions Innotech Limited            | 16        | 1.09%   |
| icSpring                               | 13        | 0.89%   |
| Primax Electronics                     | 11        | 0.75%   |
| Logitech                               | 9         | 0.62%   |
| Sonix Technology                       | 8         | 0.55%   |
| ALi                                    | 8         | 0.55%   |
| SunplusIT                              | 7         | 0.48%   |
| Samsung Electronics                    | 7         | 0.48%   |
| Lenovo                                 | 7         | 0.48%   |
| Z-Star Microelectronics                | 5         | 0.34%   |
| Importek                               | 5         | 0.34%   |
| GEMBIRD                                | 5         | 0.34%   |
| Y Media                                | 3         | 0.21%   |
| Sunplus Technology                     | 3         | 0.21%   |
| OmniVision Technologies                | 3         | 0.21%   |
| ARC International                      | 3         | 0.21%   |
| Tripath Technology                     | 2         | 0.14%   |
| Intel                                  | 2         | 0.14%   |
| Genesys Logic                          | 2         | 0.14%   |
| Generalplus Technology                 | 2         | 0.14%   |
| YGTek                                  | 1         | 0.07%   |
| Xiaomi                                 | 1         | 0.07%   |
| vivo                                   | 1         | 0.07%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.07%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 54        | 3.68%   |
| Microdia Integrated_Webcam_HD                    | 36        | 2.45%   |
| IMC Networks USB2.0 HD UVC WebCam                | 33        | 2.25%   |
| Chicony HD WebCam                                | 27        | 1.84%   |
| Microdia Integrated Webcam                       | 26        | 1.77%   |
| Syntek Integrated Camera                         | 25        | 1.7%    |
| Chicony HP Truevision HD                         | 24        | 1.63%   |
| Realtek USB Camera                               | 21        | 1.43%   |
| Realtek Integrated_Webcam_HD                     | 21        | 1.43%   |
| Chicony TOSHIBA Web Camera - HD                  | 20        | 1.36%   |
| IMC Networks Integrated Camera                   | 19        | 1.29%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 18        | 1.23%   |
| Acer Integrated Camera                           | 15        | 1.02%   |
| Sunplus HD WebCam                                | 14        | 0.95%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 14        | 0.95%   |
| Sunplus Integrated_Webcam_HD                     | 13        | 0.89%   |
| Realtek HP Truevision HD                         | 13        | 0.89%   |
| icSpring camera                                  | 13        | 0.89%   |
| Chicony Lenovo EasyCamera                        | 13        | 0.89%   |
| Chicony HP TrueVision HD Camera                  | 13        | 0.89%   |
| Bison Integrated Camera                          | 13        | 0.89%   |
| Apple FaceTime HD Camera                         | 13        | 0.89%   |
| Realtek Integrated Webcam                        | 12        | 0.82%   |
| Quanta VGA WebCam                                | 11        | 0.75%   |
| Quanta HP Wide Vision HD Camera                  | 11        | 0.75%   |
| Lite-On HP HD Camera                             | 11        | 0.75%   |
| Chicony VGA WebCam                               | 11        | 0.75%   |
| Chicony HP HD Webcam                             | 11        | 0.75%   |
| Chicony HP HD Camera                             | 11        | 0.75%   |
| Acer Lenovo EasyCamera                           | 11        | 0.75%   |
| Realtek Lenovo EasyCamera                        | 10        | 0.68%   |
| Quanta HP TrueVision HD Camera                   | 10        | 0.68%   |
| Chicony USB2.0 VGA UVC WebCam                    | 10        | 0.68%   |
| Bison Lenovo EasyCamera                          | 10        | 0.68%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                  | 10        | 0.68%   |
| Alcor Micro USB 2.0 Camera                       | 10        | 0.68%   |
| Syntek Lenovo EasyCamera                         | 9         | 0.61%   |
| Realtek Integrated Webcam HD                     | 9         | 0.61%   |
| Quanta HD User Facing                            | 9         | 0.61%   |
| Microdia Webcam Vitade AF                        | 9         | 0.61%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 106       | 44.73%  |
| Shenzhen Goodix Technology | 31        | 13.08%  |
| AuthenTec                  | 27        | 11.39%  |
| Synaptics                  | 25        | 10.55%  |
| Upek                       | 21        | 8.86%   |
| Elan Microelectronics      | 13        | 5.49%   |
| STMicroelectronics         | 6         | 2.53%   |
| LighTuning Technology      | 6         | 2.53%   |
| Samsung Electronics        | 1         | 0.42%   |
| Focal-systems.Corp         | 1         | 0.42%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 23        | 9.7%    |
| Shenzhen Goodix  FingerPrint Device                                        | 23        | 9.7%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 20        | 8.44%   |
| Validity Sensors VFS491                                                    | 13        | 5.49%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 13        | 5.49%   |
| AuthenTec AES2810                                                          | 11        | 4.64%   |
| Validity Sensors Fingerprint scanner                                       | 10        | 4.22%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 9         | 3.8%    |
| Elan ELAN:ARM-M4                                                           | 9         | 3.8%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 7         | 2.95%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 6         | 2.53%   |
| Validity Sensors Synaptics WBDI                                            | 6         | 2.53%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 6         | 2.53%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 6         | 2.53%   |
| STMicroelectronics Fingerprint Reader                                      | 6         | 2.53%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 5         | 2.11%   |
| Shenzhen Goodix Fingerprint Reader                                         | 5         | 2.11%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 1.69%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 1.69%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 1.69%   |
| Elan ELAN:Fingerprint                                                      | 4         | 1.69%   |
| AuthenTec Fingerprint Sensor                                               | 4         | 1.69%   |
| AuthenTec AES1600                                                          | 4         | 1.69%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 3         | 1.27%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 1.27%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 1.27%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 1.27%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.84%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.84%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 0.84%   |
| Synaptics WBDI                                                             | 2         | 0.84%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 0.84%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 0.84%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.42%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.42%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.42%   |
| Synaptics UWP WBDI Device                                                  | 1         | 0.42%   |
| Synaptics  WBDI                                                            | 1         | 0.42%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 0.42%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.42%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 59        | 56.73%  |
| Alcor Micro                       | 15        | 14.42%  |
| O2 Micro                          | 12        | 11.54%  |
| Lenovo                            | 6         | 5.77%   |
| Upek                              | 5         | 4.81%   |
| Yubico.com                        | 2         | 1.92%   |
| VASCO Data Security International | 1         | 0.96%   |
| SCM Microsystems                  | 1         | 0.96%   |
| Realtek Semiconductor             | 1         | 0.96%   |
| OmniKey                           | 1         | 0.96%   |
| Fujitsu Siemens Computers         | 1         | 0.96%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 25        | 24.04%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 17        | 16.35%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 15        | 14.42%  |
| Broadcom 5880                                                                | 12        | 11.54%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 11        | 10.58%  |
| Lenovo Integrated Smart Card Reader                                          | 6         | 5.77%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 4.81%   |
| Broadcom 58200                                                               | 3         | 2.88%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 1.92%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 1.92%   |
| VASCO Data Security International DIGIPASS 870                               | 1         | 0.96%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.96%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 0.96%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.96%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.96%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 0.96%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1162      | 67.52%  |
| 1     | 435       | 25.28%  |
| 2     | 115       | 6.68%   |
| 3     | 9         | 0.52%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 231       | 34.53%  |
| Graphics card            | 114       | 17.04%  |
| Chipcard                 | 97        | 14.5%   |
| Multimedia controller    | 75        | 11.21%  |
| Net/wireless             | 71        | 10.61%  |
| Storage                  | 23        | 3.44%   |
| Bluetooth                | 19        | 2.84%   |
| Sound                    | 6         | 0.9%    |
| Camera                   | 6         | 0.9%    |
| Net/ethernet             | 5         | 0.75%   |
| Communication controller | 5         | 0.75%   |
| Network                  | 3         | 0.45%   |
| Modem                    | 3         | 0.45%   |
| Card reader              | 3         | 0.45%   |
| Storage/nvme             | 2         | 0.3%    |
| Storage/ide              | 2         | 0.3%    |
| Flash memory             | 2         | 0.3%    |
| Unclassified device      | 1         | 0.15%   |
| Dvb card                 | 1         | 0.15%   |

