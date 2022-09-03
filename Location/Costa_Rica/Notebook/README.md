Linux in Costa Rica - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Costa Rica.

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

Total: 184

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo   | ThinkPad T470 W10DG 20JM... | [9b23c4b82c](https://linux-hardware.org/?probe=9b23c4b82c) | Aug 30, 2022 |
| Dell     | G3 3579                     | [a3fc82fe9a](https://linux-hardware.org/?probe=a3fc82fe9a) | Aug 30, 2022 |
| Dell     | Inspiron 3543               | [68d1385b7e](https://linux-hardware.org/?probe=68d1385b7e) | Aug 28, 2022 |
| Toshiba  | Satellite C55-C             | [99faef3f00](https://linux-hardware.org/?probe=99faef3f00) | Aug 20, 2022 |
| Toshiba  | Satellite L655              | [5e3e45b5d5](https://linux-hardware.org/?probe=5e3e45b5d5) | Aug 08, 2022 |
| Toshiba  | Satellite C55-C             | [992b4f4910](https://linux-hardware.org/?probe=992b4f4910) | Aug 06, 2022 |
| ASUSTek  | GL552VW                     | [cd24503d2f](https://linux-hardware.org/?probe=cd24503d2f) | Aug 02, 2022 |
| Acer     | Aspire E5-576               | [a31ceb9a36](https://linux-hardware.org/?probe=a31ceb9a36) | Jul 31, 2022 |
| Acer     | Aspire R3-131T              | [f4efe63bf8](https://linux-hardware.org/?probe=f4efe63bf8) | Jul 13, 2022 |
| Acer     | Aspire R3-131T              | [a06c4e1f6b](https://linux-hardware.org/?probe=a06c4e1f6b) | Jul 13, 2022 |
| Deffad   | Unknown                     | [af38c7120e](https://linux-hardware.org/?probe=af38c7120e) | Jul 04, 2022 |
| Dell     | Inspiron 3520               | [b865370f11](https://linux-hardware.org/?probe=b865370f11) | Jun 28, 2022 |
| Lenovo   | ThinkPad P50 20EN001PUS     | [52ef9383a4](https://linux-hardware.org/?probe=52ef9383a4) | Jun 09, 2022 |
| Lenovo   | ThinkPad T440s 20ARS29U0... | [50de8ad2e9](https://linux-hardware.org/?probe=50de8ad2e9) | Jun 01, 2022 |
| Dell     | Latitude 7400               | [caf85903ad](https://linux-hardware.org/?probe=caf85903ad) | May 19, 2022 |
| Dell     | Inspiron 5565               | [d5a8629a31](https://linux-hardware.org/?probe=d5a8629a31) | May 19, 2022 |
| Lenovo   | ThinkPad L420 7829AA4       | [9c1bbe8cf2](https://linux-hardware.org/?probe=9c1bbe8cf2) | May 14, 2022 |
| HP       | Laptop 15-da0xxx            | [6ad1b34a48](https://linux-hardware.org/?probe=6ad1b34a48) | Apr 29, 2022 |
| Lenovo   | ThinkPad E15 Gen 2 20T80... | [637af2dcc6](https://linux-hardware.org/?probe=637af2dcc6) | Apr 29, 2022 |
| Apple    | MacBookPro8,1               | [f74cae630d](https://linux-hardware.org/?probe=f74cae630d) | Apr 16, 2022 |
| HP       | Pavilion Notebook           | [a1130d8070](https://linux-hardware.org/?probe=a1130d8070) | Apr 13, 2022 |
| Acer     | Nitro AN515-43              | [e1386a38c7](https://linux-hardware.org/?probe=e1386a38c7) | Mar 20, 2022 |
| Dell     | Latitude E5500              | [13be4a0a1b](https://linux-hardware.org/?probe=13be4a0a1b) | Mar 16, 2022 |
| Dell     | Latitude E5500              | [d5f8fd7890](https://linux-hardware.org/?probe=d5f8fd7890) | Mar 16, 2022 |
| HP       | Laptop 15-da0xxx            | [a8531f3837](https://linux-hardware.org/?probe=a8531f3837) | Mar 13, 2022 |
| Dell     | Latitude D630               | [b7b428082a](https://linux-hardware.org/?probe=b7b428082a) | Mar 05, 2022 |
| Dell     | XPS 13 9305                 | [8807d99cb4](https://linux-hardware.org/?probe=8807d99cb4) | Mar 01, 2022 |
| ASUSTek  | VivoBook_ASUS Laptop E41... | [c0adf77f3f](https://linux-hardware.org/?probe=c0adf77f3f) | Feb 26, 2022 |
| Sony     | SVD13215PLB                 | [82c4287f85](https://linux-hardware.org/?probe=82c4287f85) | Feb 23, 2022 |
| Lenovo   | ThinkPad L15 Gen 2 20X4S... | [b355ea1ff3](https://linux-hardware.org/?probe=b355ea1ff3) | Feb 20, 2022 |
| Lenovo   | IdeaPad 3 14ADA05 81W0      | [8468cd0da9](https://linux-hardware.org/?probe=8468cd0da9) | Feb 19, 2022 |
| Lenovo   | IdeaPad 3 14ADA05 81W0      | [80e2f3c47e](https://linux-hardware.org/?probe=80e2f3c47e) | Feb 19, 2022 |
| Apple    | MacBookPro8,1               | [b99a5f9b59](https://linux-hardware.org/?probe=b99a5f9b59) | Feb 14, 2022 |
| HP       | Laptop 15-da0xxx            | [ce15566bc3](https://linux-hardware.org/?probe=ce15566bc3) | Feb 12, 2022 |
| HUAWEI   | NBLK-WAX9X                  | [dbc7cbcfe1](https://linux-hardware.org/?probe=dbc7cbcfe1) | Feb 07, 2022 |
| Toshiba  | Satellite L45-B             | [5e026ae9b0](https://linux-hardware.org/?probe=5e026ae9b0) | Jan 14, 2022 |
| ASUSTek  | VivoBook 15_ASUS Laptop ... | [3f953ad7f3](https://linux-hardware.org/?probe=3f953ad7f3) | Jan 14, 2022 |
| ASUSTek  | VivoBook 15_ASUS Laptop ... | [eecedd12b2](https://linux-hardware.org/?probe=eecedd12b2) | Jan 14, 2022 |
| Dell     | Latitude 5490               | [c5c1f555f1](https://linux-hardware.org/?probe=c5c1f555f1) | Nov 03, 2021 |
| HP       | EliteBook 8460p             | [b6ac4539d1](https://linux-hardware.org/?probe=b6ac4539d1) | Oct 28, 2021 |
| HP       | EliteBook 8460p             | [8264430178](https://linux-hardware.org/?probe=8264430178) | Oct 28, 2021 |
| Dell     | Inspiron 3595               | [1df662506b](https://linux-hardware.org/?probe=1df662506b) | Oct 27, 2021 |
| Apple    | MacBookPro8,1               | [e7e870c6cc](https://linux-hardware.org/?probe=e7e870c6cc) | Oct 22, 2021 |
| Lenovo   | IdeaPad Gaming 3 15ARH05... | [a271c08df2](https://linux-hardware.org/?probe=a271c08df2) | Oct 21, 2021 |
| HP       | EliteBook 8460p             | [5bb3c9bc8b](https://linux-hardware.org/?probe=5bb3c9bc8b) | Oct 19, 2021 |
| Apple    | MacBookPro8,1               | [bfadd59ae5](https://linux-hardware.org/?probe=bfadd59ae5) | Oct 18, 2021 |
| Lenovo   | IdeaPad Gaming 3 15ARH05... | [2a9e8d32e2](https://linux-hardware.org/?probe=2a9e8d32e2) | Oct 15, 2021 |
| Acer     | Aspire 5750                 | [ff12aa7481](https://linux-hardware.org/?probe=ff12aa7481) | Oct 15, 2021 |
| Lenovo   | IdeaPad Gaming 3 15ARH05... | [f0a9d13afb](https://linux-hardware.org/?probe=f0a9d13afb) | Oct 14, 2021 |
| Lenovo   | ThinkPad X1 Carbon 2nd 2... | [1dbff2c4f9](https://linux-hardware.org/?probe=1dbff2c4f9) | Oct 09, 2021 |
| HP       | Laptop 15-da0xxx            | [da71bb02c1](https://linux-hardware.org/?probe=da71bb02c1) | Oct 03, 2021 |
| Dell     | Latitude D620               | [1dc8e001f5](https://linux-hardware.org/?probe=1dc8e001f5) | Sep 28, 2021 |
| Apple    | MacBookPro8,1               | [3a8451c3d2](https://linux-hardware.org/?probe=3a8451c3d2) | Sep 25, 2021 |
| Apple    | MacBookPro8,1               | [0a7625c3ec](https://linux-hardware.org/?probe=0a7625c3ec) | Sep 25, 2021 |
| Apple    | MacBookPro8,1               | [2c4c85f574](https://linux-hardware.org/?probe=2c4c85f574) | Sep 20, 2021 |
| Apple    | MacBookPro8,1               | [dcf03222dc](https://linux-hardware.org/?probe=dcf03222dc) | Sep 12, 2021 |
| HP       | EliteBook 820 G1            | [00b3e62e2e](https://linux-hardware.org/?probe=00b3e62e2e) | Sep 10, 2021 |
| MSI      | GF75 Thin 9SD               | [e70d1b33e1](https://linux-hardware.org/?probe=e70d1b33e1) | Sep 09, 2021 |
| HP       | Pavilion Laptop 15-cc1xx    | [a7cc7fb98c](https://linux-hardware.org/?probe=a7cc7fb98c) | Aug 27, 2021 |
| HP       | Pavilion Laptop 15-cc1xx    | [6972dfc45b](https://linux-hardware.org/?probe=6972dfc45b) | Aug 25, 2021 |
| Olivetti | CL133A                      | [59d8296ec4](https://linux-hardware.org/?probe=59d8296ec4) | Jul 31, 2021 |
| HP       | Pavilion g4                 | [3f01790d4e](https://linux-hardware.org/?probe=3f01790d4e) | Jul 21, 2021 |
| AZW      | GT-R                        | [115230aa47](https://linux-hardware.org/?probe=115230aa47) | Jul 19, 2021 |
| Olivetti | CL133A                      | [a73133e4f3](https://linux-hardware.org/?probe=a73133e4f3) | Jul 15, 2021 |
| ASUSTek  | U46E                        | [720dec33c4](https://linux-hardware.org/?probe=720dec33c4) | Jul 14, 2021 |
| HP       | ProBook 6460b               | [b39eb9b256](https://linux-hardware.org/?probe=b39eb9b256) | Jul 13, 2021 |
| Dell     | G3 3590                     | [3781e31377](https://linux-hardware.org/?probe=3781e31377) | Jul 12, 2021 |
| Olivetti | CL133A                      | [ba8eb5f003](https://linux-hardware.org/?probe=ba8eb5f003) | Jul 10, 2021 |
| Olivetti | CL133A                      | [117e8fa0b4](https://linux-hardware.org/?probe=117e8fa0b4) | Jul 06, 2021 |
| HP       | EliteBook 8570p             | [ab19b80507](https://linux-hardware.org/?probe=ab19b80507) | Jun 09, 2021 |
| HUAWEI   | NBLK-WAX9X                  | [9908ba82e9](https://linux-hardware.org/?probe=9908ba82e9) | May 31, 2021 |
| HP       | Pavilion dv6000 (RP297UA... | [5f6d9f025a](https://linux-hardware.org/?probe=5f6d9f025a) | May 29, 2021 |
| Dell     | Inspiron 5584               | [ebffa34fe2](https://linux-hardware.org/?probe=ebffa34fe2) | May 28, 2021 |
| Toshiba  | Satellite C845              | [e3b90e238b](https://linux-hardware.org/?probe=e3b90e238b) | May 24, 2021 |
| HP       | Laptop 14-ck0xxx            | [6f3c2aa3be](https://linux-hardware.org/?probe=6f3c2aa3be) | May 24, 2021 |
| HP       | Laptop 14-ck0xxx            | [8ccda2ce59](https://linux-hardware.org/?probe=8ccda2ce59) | May 24, 2021 |
| Toshiba  | Satellite C845              | [4d346e2691](https://linux-hardware.org/?probe=4d346e2691) | May 24, 2021 |
| Dell     | Inspiron 5584               | [5e2e76f838](https://linux-hardware.org/?probe=5e2e76f838) | May 20, 2021 |
| Acer     | Aspire A515-43              | [0a87ab06c5](https://linux-hardware.org/?probe=0a87ab06c5) | May 19, 2021 |
| Apple    | MacBookPro8,1               | [4a32129550](https://linux-hardware.org/?probe=4a32129550) | May 15, 2021 |
| Lenovo   | IdeaPad S340-15API 81NC     | [93286a0d38](https://linux-hardware.org/?probe=93286a0d38) | May 15, 2021 |
| Lenovo   | IdeaPad S340-15API 81NC     | [796f490bbb](https://linux-hardware.org/?probe=796f490bbb) | May 15, 2021 |
| Dell     | Inspiron 5584               | [1da876ea0b](https://linux-hardware.org/?probe=1da876ea0b) | May 06, 2021 |
| Dell     | Inspiron 5584               | [0216a041d2](https://linux-hardware.org/?probe=0216a041d2) | May 05, 2021 |
| HP       | Laptop 15-da0xxx            | [b91d32b11a](https://linux-hardware.org/?probe=b91d32b11a) | May 03, 2021 |
| Acer     | Aspire A515-43              | [3c87a86111](https://linux-hardware.org/?probe=3c87a86111) | May 02, 2021 |
| HP       | Pavilion dv6                | [a181ae8691](https://linux-hardware.org/?probe=a181ae8691) | Apr 30, 2021 |
| HP       | Pavilion dv6                | [d363966e4c](https://linux-hardware.org/?probe=d363966e4c) | Apr 30, 2021 |
| HP       | Pavilion dv6                | [204cd9c44f](https://linux-hardware.org/?probe=204cd9c44f) | Apr 30, 2021 |
| HP       | Pavilion dv6                | [e20fc33e2b](https://linux-hardware.org/?probe=e20fc33e2b) | Apr 29, 2021 |
| Lenovo   | ThinkPad L14 Gen 1 20U10... | [3cca89aa74](https://linux-hardware.org/?probe=3cca89aa74) | Apr 28, 2021 |
| HP       | Laptop 15-da0xxx            | [fd209ac377](https://linux-hardware.org/?probe=fd209ac377) | Apr 24, 2021 |
| Lenovo   | ThinkPad L14 Gen 1 20U10... | [38c505f6bd](https://linux-hardware.org/?probe=38c505f6bd) | Apr 23, 2021 |
| Apple    | MacBook2,1                  | [a0590a2529](https://linux-hardware.org/?probe=a0590a2529) | Apr 18, 2021 |
| HP       | Laptop 15-da0xxx            | [5afa66a433](https://linux-hardware.org/?probe=5afa66a433) | Apr 17, 2021 |
| Lenovo   | IdeaPad S340-15API 81NC     | [e990abe7f1](https://linux-hardware.org/?probe=e990abe7f1) | Apr 11, 2021 |
| Lenovo   | IdeaPad S340-15API 81NC     | [41c14db0ef](https://linux-hardware.org/?probe=41c14db0ef) | Apr 11, 2021 |
| Dell     | G3 3590                     | [3c952dbc96](https://linux-hardware.org/?probe=3c952dbc96) | Mar 26, 2021 |
| Toshiba  | QOSMIO X775                 | [d8f82a3984](https://linux-hardware.org/?probe=d8f82a3984) | Mar 26, 2021 |
| HP       | OMEN by Laptop              | [127ea1feb8](https://linux-hardware.org/?probe=127ea1feb8) | Mar 13, 2021 |
| HP       | Pavilion g4                 | [1e7372e4f2](https://linux-hardware.org/?probe=1e7372e4f2) | Mar 01, 2021 |
| Toshiba  | Satellite C45-A             | [e00317dc4d](https://linux-hardware.org/?probe=e00317dc4d) | Mar 01, 2021 |
| Unknown  | Unknown                     | [941e941403](https://linux-hardware.org/?probe=941e941403) | Feb 27, 2021 |
| Dell     | Inspiron 5584               | [16fca1f86b](https://linux-hardware.org/?probe=16fca1f86b) | Feb 24, 2021 |
| Google   | Celes                       | [b30c090b2b](https://linux-hardware.org/?probe=b30c090b2b) | Feb 22, 2021 |
| Dell     | Inspiron 3558               | [41ba11dbb4](https://linux-hardware.org/?probe=41ba11dbb4) | Feb 18, 2021 |
| Dell     | Inspiron 5584               | [660afa073b](https://linux-hardware.org/?probe=660afa073b) | Feb 11, 2021 |
| Dell     | Inspiron 5584               | [840e0e2818](https://linux-hardware.org/?probe=840e0e2818) | Feb 04, 2021 |
| Dell     | Inspiron 5584               | [e10690d1d2](https://linux-hardware.org/?probe=e10690d1d2) | Feb 04, 2021 |
| HP       | Laptop 14-dq1xxx            | [84c932e071](https://linux-hardware.org/?probe=84c932e071) | Feb 02, 2021 |
| Dell     | Inspiron 5584               | [473419d486](https://linux-hardware.org/?probe=473419d486) | Jan 24, 2021 |
| Dell     | Inspiron 5584               | [738e03e488](https://linux-hardware.org/?probe=738e03e488) | Jan 23, 2021 |
| Dell     | Precision M4800             | [f24be700aa](https://linux-hardware.org/?probe=f24be700aa) | Jan 21, 2021 |
| Dell     | Precision M4800             | [316c7dd34b](https://linux-hardware.org/?probe=316c7dd34b) | Jan 21, 2021 |
| HP       | Laptop 14-bp0xx             | [4badbab2db](https://linux-hardware.org/?probe=4badbab2db) | Jan 19, 2021 |
| Dell     | Inspiron 5584               | [1a731e13e0](https://linux-hardware.org/?probe=1a731e13e0) | Jan 18, 2021 |
| Lenovo   | IdeaPad 330-15IKB 81DE      | [6a0e9eff49](https://linux-hardware.org/?probe=6a0e9eff49) | Jan 16, 2021 |
| Dell     | Inspiron 5584               | [76fe08b67a](https://linux-hardware.org/?probe=76fe08b67a) | Jan 14, 2021 |
| Dell     | Inspiron 5584               | [8d9be2defd](https://linux-hardware.org/?probe=8d9be2defd) | Jan 13, 2021 |
| Lenovo   | ThinkPad X1 Carbon 3rd 2... | [b30b783683](https://linux-hardware.org/?probe=b30b783683) | Jan 12, 2021 |
| Dell     | Inspiron 5584               | [6917b5bc30](https://linux-hardware.org/?probe=6917b5bc30) | Jan 11, 2021 |
| Dell     | Inspiron 5584               | [cfa1367cf6](https://linux-hardware.org/?probe=cfa1367cf6) | Jan 10, 2021 |
| Dell     | Inspiron 5584               | [60a171b505](https://linux-hardware.org/?probe=60a171b505) | Jan 10, 2021 |
| HP       | Laptop 14-bp0xx             | [a481e8e9c0](https://linux-hardware.org/?probe=a481e8e9c0) | Dec 16, 2020 |
| HP       | Laptop 14-bp0xx             | [266b8d7543](https://linux-hardware.org/?probe=266b8d7543) | Dec 16, 2020 |
| MSI      | GE60 2OC\2OD\2OE            | [a305c14111](https://linux-hardware.org/?probe=a305c14111) | Dec 13, 2020 |
| ASUSTek  | VivoBook_ASUSLaptop X512... | [c110de3643](https://linux-hardware.org/?probe=c110de3643) | Oct 31, 2020 |
| Dell     | Latitude 7480               | [2e569dcaed](https://linux-hardware.org/?probe=2e569dcaed) | Oct 22, 2020 |
| Dell     | Latitude 7480               | [1cc0a03f18](https://linux-hardware.org/?probe=1cc0a03f18) | Oct 22, 2020 |
| Dell     | XPS 15 9560                 | [9f10520397](https://linux-hardware.org/?probe=9f10520397) | Oct 11, 2020 |
| Dell     | G3 3590                     | [4c2ddd8b88](https://linux-hardware.org/?probe=4c2ddd8b88) | Oct 01, 2020 |
| Toshiba  | Satellite C55-B             | [6acb0908ff](https://linux-hardware.org/?probe=6acb0908ff) | Sep 18, 2020 |
| HP       | Unknown                     | [a446c81ca9](https://linux-hardware.org/?probe=a446c81ca9) | Sep 10, 2020 |
| HP       | EliteBook 8570p             | [48e494142e](https://linux-hardware.org/?probe=48e494142e) | Aug 27, 2020 |
| Toshiba  | Satellite X205              | [b0d5e7d0dd](https://linux-hardware.org/?probe=b0d5e7d0dd) | Aug 26, 2020 |
| Toshiba  | Satellite X205              | [45e52f3631](https://linux-hardware.org/?probe=45e52f3631) | Aug 26, 2020 |
| Acer     | Aspire 4739Z                | [44ec59d132](https://linux-hardware.org/?probe=44ec59d132) | Aug 11, 2020 |
| HP       | Pavilion dv2500             | [4bdd603282](https://linux-hardware.org/?probe=4bdd603282) | Aug 06, 2020 |
| HP       | Pavilion dv2500             | [4114f58581](https://linux-hardware.org/?probe=4114f58581) | Aug 06, 2020 |
| Dell     | Latitude E5440              | [9d31b1e38d](https://linux-hardware.org/?probe=9d31b1e38d) | Jul 29, 2020 |
| Dell     | G3 3590                     | [e2fa394ba6](https://linux-hardware.org/?probe=e2fa394ba6) | Jun 28, 2020 |
| Dell     | XPS 15 9560                 | [8119688776](https://linux-hardware.org/?probe=8119688776) | Jun 27, 2020 |
| Dell     | XPS 15 9560                 | [d2a2900148](https://linux-hardware.org/?probe=d2a2900148) | Jun 20, 2020 |
| Dell     | Inspiron 5559               | [4619502a6b](https://linux-hardware.org/?probe=4619502a6b) | May 28, 2020 |
| HP       | ProBook 455 G4              | [6b6fe8e0c1](https://linux-hardware.org/?probe=6b6fe8e0c1) | May 18, 2020 |
| HP       | 245 G4 Notebook PC          | [9311532f56](https://linux-hardware.org/?probe=9311532f56) | Apr 23, 2020 |
| HP       | 245 G4 Notebook PC          | [b662f230b2](https://linux-hardware.org/?probe=b662f230b2) | Apr 23, 2020 |
| HP       | Notebook                    | [5815277bb0](https://linux-hardware.org/?probe=5815277bb0) | Apr 22, 2020 |
| HP       | Laptop 15-da0xxx            | [1dc3e83e11](https://linux-hardware.org/?probe=1dc3e83e11) | Apr 18, 2020 |
| ASUSTek  | Strix 17 GL703GE            | [2f87bcd627](https://linux-hardware.org/?probe=2f87bcd627) | Apr 07, 2020 |
| ASUSTek  | Strix 17 GL703GE            | [16ff51d343](https://linux-hardware.org/?probe=16ff51d343) | Apr 07, 2020 |
| Acer     | Aspire V3-471               | [024d5b0563](https://linux-hardware.org/?probe=024d5b0563) | Apr 06, 2020 |
| Dell     | G3 3590                     | [26a4f7e20b](https://linux-hardware.org/?probe=26a4f7e20b) | Mar 22, 2020 |
| Dell     | G3 3590                     | [96d9b68953](https://linux-hardware.org/?probe=96d9b68953) | Mar 21, 2020 |
| Toshiba  | Satellite C855D             | [9246f32b7e](https://linux-hardware.org/?probe=9246f32b7e) | Mar 01, 2020 |
| HP       | Pavilion Notebook           | [2bbf18e9e5](https://linux-hardware.org/?probe=2bbf18e9e5) | Feb 20, 2020 |
| HP       | Pavilion Notebook           | [68895d1461](https://linux-hardware.org/?probe=68895d1461) | Feb 20, 2020 |
| HP       | ProBook 6460b               | [121b074dd0](https://linux-hardware.org/?probe=121b074dd0) | Feb 19, 2020 |
| Dell     | Latitude 5500               | [3a7f8e19f1](https://linux-hardware.org/?probe=3a7f8e19f1) | Feb 17, 2020 |
| ASUSTek  | K52F                        | [9dde03d12c](https://linux-hardware.org/?probe=9dde03d12c) | Feb 13, 2020 |
| ASUSTek  | Strix 17 GL703GE            | [9eb64d7269](https://linux-hardware.org/?probe=9eb64d7269) | Jan 17, 2020 |
| ASUSTek  | Strix 17 GL703GE            | [8211b13acf](https://linux-hardware.org/?probe=8211b13acf) | Jan 17, 2020 |
| HP       | 240 G6 Notebook PC          | [73da3dccf1](https://linux-hardware.org/?probe=73da3dccf1) | Nov 14, 2019 |
| HP       | 240 G6 Notebook PC          | [efeee7f2fc](https://linux-hardware.org/?probe=efeee7f2fc) | Nov 14, 2019 |
| System76 | Lemur                       | [a9cc263cb4](https://linux-hardware.org/?probe=a9cc263cb4) | Oct 09, 2019 |
| HP       | ProBook 450 G2              | [c7959cccb3](https://linux-hardware.org/?probe=c7959cccb3) | Sep 30, 2019 |
| HP       | Notebook                    | [163fc3e9dd](https://linux-hardware.org/?probe=163fc3e9dd) | Sep 14, 2019 |
| ASUSTek  | Strix 17 GL703GE            | [c34161a66d](https://linux-hardware.org/?probe=c34161a66d) | Sep 02, 2019 |
| System76 | Lemur                       | [01bbf99115](https://linux-hardware.org/?probe=01bbf99115) | Sep 02, 2019 |
| Lenovo   | ThinkPad P53 20QNS00P00     | [47182bd3e3](https://linux-hardware.org/?probe=47182bd3e3) | Sep 01, 2019 |
| Lenovo   | ThinkPad P53 20QNS00P00     | [2105fa4def](https://linux-hardware.org/?probe=2105fa4def) | Sep 01, 2019 |
| HP       | Notebook                    | [b7e9995b67](https://linux-hardware.org/?probe=b7e9995b67) | Aug 18, 2019 |
| HP       | Notebook                    | [273d0bcc2e](https://linux-hardware.org/?probe=273d0bcc2e) | Aug 18, 2019 |
| Dell     | Venue 11 Pro 7130 vPro      | [2e5b92af00](https://linux-hardware.org/?probe=2e5b92af00) | Aug 17, 2019 |
| Dell     | Latitude E5450              | [3336801ccf](https://linux-hardware.org/?probe=3336801ccf) | Aug 10, 2019 |
| Toshiba  | Satellite A305D             | [ebf0a9c89e](https://linux-hardware.org/?probe=ebf0a9c89e) | Aug 08, 2019 |
| Acer     | SW5-017P                    | [fbf9b74a34](https://linux-hardware.org/?probe=fbf9b74a34) | Jul 29, 2019 |
| Dell     | Latitude 5480               | [f488cfd08f](https://linux-hardware.org/?probe=f488cfd08f) | Jun 22, 2019 |
| ASUSTek  | Strix 17 GL703GE            | [328975f3a5](https://linux-hardware.org/?probe=328975f3a5) | May 15, 2019 |
| Dell     | Latitude 5480               | [694ca16d49](https://linux-hardware.org/?probe=694ca16d49) | May 04, 2019 |
| Purism   | Librem 15 v3                | [00259367c8](https://linux-hardware.org/?probe=00259367c8) | Oct 29, 2018 |
| Purism   | Librem 15 v3                | [c5e1ab1520](https://linux-hardware.org/?probe=c5e1ab1520) | Oct 29, 2018 |
| ASUSTek  | X555LAB                     | [243803142a](https://linux-hardware.org/?probe=243803142a) | Aug 01, 2018 |
| Toshiba  | Satellite C645D             | [9d50eb7fdb](https://linux-hardware.org/?probe=9d50eb7fdb) | Nov 24, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 18.04                 | 13        | 10.66%  |
| Ubuntu 20.04                 | 12        | 9.84%   |
| OpenMandriva 4.2             | 7         | 5.74%   |
| Ubuntu 22.04                 | 6         | 4.92%   |
| Ubuntu 19.04                 | 4         | 3.28%   |
| OpenMandriva 4.3             | 4         | 3.28%   |
| Zorin 16                     | 3         | 2.46%   |
| Lubuntu 21.10                | 3         | 2.46%   |
| Lubuntu 21.04                | 3         | 2.46%   |
| Xubuntu 20.04                | 2         | 1.64%   |
| Ubuntu Studio 20.04          | 2         | 1.64%   |
| Ubuntu 21.04                 | 2         | 1.64%   |
| openSUSE Tumbleweed-XXXXXXXX | 2         | 1.64%   |
| Manjaro 20.2.1               | 2         | 1.64%   |
| Lubuntu 22.04                | 2         | 1.64%   |
| Linux Mint 20.3              | 2         | 1.64%   |
| Linux Mint 20.1              | 2         | 1.64%   |
| Linux Mint 20                | 2         | 1.64%   |
| KDE neon 20.04               | 2         | 1.64%   |
| Fedora 36                    | 2         | 1.64%   |
| Debian 11                    | 2         | 1.64%   |
| Debian 10                    | 2         | 1.64%   |
| Zorin 15                     | 1         | 0.82%   |
| Xubuntu 18.04                | 1         | 0.82%   |
| UbuntuDDE 20.04              | 1         | 0.82%   |
| Ubuntu MATE 18.04            | 1         | 0.82%   |
| Ubuntu 21.10                 | 1         | 0.82%   |
| Ubuntu 16.04                 | 1         | 0.82%   |
| ROSA R8                      | 1         | 0.82%   |
| ROSA R10                     | 1         | 0.82%   |
| Reborn OS Rolling            | 1         | 0.82%   |
| PureOS 10.0                  | 1         | 0.82%   |
| Pop!_OS 21.10                | 1         | 0.82%   |
| Pop!_OS 20.10                | 1         | 0.82%   |
| Peppermint 10                | 1         | 0.82%   |
| Parrot 4.10                  | 1         | 0.82%   |
| Manjaro 21.0.1               | 1         | 0.82%   |
| Manjaro 20.2                 | 1         | 0.82%   |
| Manjaro 20.1                 | 1         | 0.82%   |
| Manjaro                      | 1         | 0.82%   |
| Lubuntu 20.10                | 1         | 0.82%   |
| Lubuntu 20.04                | 1         | 0.82%   |
| LMDE 5                       | 1         | 0.82%   |
| Linux Mint 20.2              | 1         | 0.82%   |
| Linux Mint 19.3              | 1         | 0.82%   |
| Kubuntu 22.04                | 1         | 0.82%   |
| Kubuntu 21.10                | 1         | 0.82%   |
| Kubuntu 20.04                | 1         | 0.82%   |
| Kali 2022.2                  | 1         | 0.82%   |
| Kali 2021.1                  | 1         | 0.82%   |
| Fedora 35                    | 1         | 0.82%   |
| Fedora 34                    | 1         | 0.82%   |
| Fedora 33                    | 1         | 0.82%   |
| Fedora 28                    | 1         | 0.82%   |
| Endless 4.0.2                | 1         | 0.82%   |
| Endless 3.7.7                | 1         | 0.82%   |
| Debian Testing               | 1         | 0.82%   |
| Clear Linux 32110            | 1         | 0.82%   |
| Clear Linux 30900            | 1         | 0.82%   |
| Clear Linux 29410            | 1         | 0.82%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 38        | 33.63%  |
| OpenMandriva  | 11        | 9.73%   |
| Linux Mint    | 8         | 7.08%   |
| Manjaro       | 6         | 5.31%   |
| Fedora        | 6         | 5.31%   |
| Lubuntu       | 5         | 4.42%   |
| Debian        | 5         | 4.42%   |
| Zorin         | 4         | 3.54%   |
| Xubuntu       | 3         | 2.65%   |
| Ubuntu Studio | 2         | 1.77%   |
| ROSA          | 2         | 1.77%   |
| Pop!_OS       | 2         | 1.77%   |
| openSUSE      | 2         | 1.77%   |
| Kubuntu       | 2         | 1.77%   |
| KDE neon      | 2         | 1.77%   |
| Kali          | 2         | 1.77%   |
| Endless       | 2         | 1.77%   |
| UbuntuDDE     | 1         | 0.88%   |
| Ubuntu MATE   | 1         | 0.88%   |
| Reborn OS     | 1         | 0.88%   |
| PureOS        | 1         | 0.88%   |
| Peppermint    | 1         | 0.88%   |
| Parrot        | 1         | 0.88%   |
| LMDE          | 1         | 0.88%   |
| Clear Linux   | 1         | 0.88%   |
| ArcoLinux     | 1         | 0.88%   |
| Arch          | 1         | 0.88%   |
| ALT Linux     | 1         | 0.88%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                          | Notebooks | Percent |
|----------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002         | 7         | 5.22%   |
| 5.16.7-desktop-1omv4003          | 4         | 2.99%   |
| 5.0.0-23-generic                 | 4         | 2.99%   |
| 5.4.0-77-generic                 | 3         | 2.24%   |
| 5.4.0-42-generic                 | 3         | 2.24%   |
| 5.13.0-16-generic                | 3         | 2.24%   |
| 5.11.0-27-generic                | 3         | 2.24%   |
| 5.0.0-25-generic                 | 3         | 2.24%   |
| 5.9.16-1-MANJARO                 | 2         | 1.49%   |
| 5.8.0-50-generic                 | 2         | 1.49%   |
| 5.4.0-21-generic                 | 2         | 1.49%   |
| 5.3.0-40-generic                 | 2         | 1.49%   |
| 5.3.0-28-generic                 | 2         | 1.49%   |
| 5.15.0-41-generic                | 2         | 1.49%   |
| 5.13.0-35-generic                | 2         | 1.49%   |
| 5.13.0-20-generic                | 2         | 1.49%   |
| 5.11.0-16-generic                | 2         | 1.49%   |
| 4.15.0-112-generic               | 2         | 1.49%   |
| 5.9.11-3-MANJARO                 | 1         | 0.75%   |
| 5.8.6-1-MANJARO                  | 1         | 0.75%   |
| 5.8.0-7630-generic               | 1         | 0.75%   |
| 5.8.0-55-generic                 | 1         | 0.75%   |
| 5.8.0-53-generic                 | 1         | 0.75%   |
| 5.7.0-2parrot2-amd64             | 1         | 0.75%   |
| 5.4.0-88-lowlatency              | 1         | 0.75%   |
| 5.4.0-72-generic                 | 1         | 0.75%   |
| 5.4.0-70-generic                 | 1         | 0.75%   |
| 5.4.0-65-generic                 | 1         | 0.75%   |
| 5.4.0-64-generic                 | 1         | 0.75%   |
| 5.4.0-58-generic                 | 1         | 0.75%   |
| 5.4.0-52-generic                 | 1         | 0.75%   |
| 5.4.0-48-lowlatency              | 1         | 0.75%   |
| 5.4.0-48-generic                 | 1         | 0.75%   |
| 5.4.0-47-generic                 | 1         | 0.75%   |
| 5.4.0-37-generic                 | 1         | 0.75%   |
| 5.4.0-31-generic                 | 1         | 0.75%   |
| 5.4.0-29-generic                 | 1         | 0.75%   |
| 5.4.0-25-generic                 | 1         | 0.75%   |
| 5.4.0-110-generic                | 1         | 0.75%   |
| 5.4.0-109-generic                | 1         | 0.75%   |
| 5.4.0-100-generic                | 1         | 0.75%   |
| 5.3.0-61-generic                 | 1         | 0.75%   |
| 5.3.0-46-generic                 | 1         | 0.75%   |
| 5.3.0-45-generic                 | 1         | 0.75%   |
| 5.3.0-42-generic                 | 1         | 0.75%   |
| 5.2.11-829.native                | 1         | 0.75%   |
| 5.19.4-250.vanilla.1.fc36.x86_64 | 1         | 0.75%   |
| 5.18.13-200.fc36.x86_64          | 1         | 0.75%   |
| 5.18.13-100.fc35.x86_64          | 1         | 0.75%   |
| 5.18.0-kali2-amd64               | 1         | 0.75%   |
| 5.17.9-051709-generic            | 1         | 0.75%   |
| 5.15.23-76051523-generic         | 1         | 0.75%   |
| 5.15.0-46-generic                | 1         | 0.75%   |
| 5.15.0-43-generic                | 1         | 0.75%   |
| 5.15.0-35-generic                | 1         | 0.75%   |
| 5.15.0-33-generic                | 1         | 0.75%   |
| 5.15.0-27-generic                | 1         | 0.75%   |
| 5.15.0-25-generic                | 1         | 0.75%   |
| 5.15.0-18-generic                | 1         | 0.75%   |
| 5.14.0-15.1-liquorix-amd64       | 1         | 0.75%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 22        | 17.74%  |
| 5.11.0  | 11        | 8.87%   |
| 5.15.0  | 9         | 7.26%   |
| 5.13.0  | 8         | 6.45%   |
| 5.0.0   | 8         | 6.45%   |
| 5.3.0   | 7         | 5.65%   |
| 5.10.14 | 7         | 5.65%   |
| 5.10.0  | 6         | 4.84%   |
| 5.8.0   | 5         | 4.03%   |
| 4.15.0  | 5         | 4.03%   |
| 5.16.7  | 4         | 3.23%   |
| 5.9.16  | 2         | 1.61%   |
| 5.18.13 | 2         | 1.61%   |
| 4.19.0  | 2         | 1.61%   |
| 5.9.11  | 1         | 0.81%   |
| 5.8.6   | 1         | 0.81%   |
| 5.7.0   | 1         | 0.81%   |
| 5.2.11  | 1         | 0.81%   |
| 5.19.4  | 1         | 0.81%   |
| 5.18.0  | 1         | 0.81%   |
| 5.17.9  | 1         | 0.81%   |
| 5.15.23 | 1         | 0.81%   |
| 5.14.0  | 1         | 0.81%   |
| 5.12.6  | 1         | 0.81%   |
| 5.12.15 | 1         | 0.81%   |
| 5.12.0  | 1         | 0.81%   |
| 5.11.5  | 1         | 0.81%   |
| 5.11.12 | 1         | 0.81%   |
| 5.11.1  | 1         | 0.81%   |
| 5.10.9  | 1         | 0.81%   |
| 5.10.7  | 1         | 0.81%   |
| 5.10.35 | 1         | 0.81%   |
| 5.10.26 | 1         | 0.81%   |
| 5.10.2  | 1         | 0.81%   |
| 5.0.15  | 1         | 0.81%   |
| 4.9.111 | 1         | 0.81%   |
| 4.19.96 | 1         | 0.81%   |
| 4.18.11 | 1         | 0.81%   |
| 4.18.0  | 1         | 0.81%   |
| 4.1.34  | 1         | 0.81%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 22        | 17.89%  |
| 5.10    | 17        | 13.82%  |
| 5.11    | 14        | 11.38%  |
| 5.15    | 10        | 8.13%   |
| 5.0     | 9         | 7.32%   |
| 5.13    | 8         | 6.5%    |
| 5.3     | 7         | 5.69%   |
| 5.8     | 6         | 4.88%   |
| 4.15    | 5         | 4.07%   |
| 5.16    | 4         | 3.25%   |
| 5.9     | 3         | 2.44%   |
| 5.18    | 3         | 2.44%   |
| 5.12    | 3         | 2.44%   |
| 4.19    | 3         | 2.44%   |
| 4.18    | 2         | 1.63%   |
| 5.7     | 1         | 0.81%   |
| 5.2     | 1         | 0.81%   |
| 5.19    | 1         | 0.81%   |
| 5.17    | 1         | 0.81%   |
| 5.14    | 1         | 0.81%   |
| 4.9     | 1         | 0.81%   |
| 4.1     | 1         | 0.81%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 106       | 99.07%  |
| i686   | 1         | 0.93%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 45        | 41.28%  |
| KDE5       | 16        | 14.68%  |
| Unknown    | 13        | 11.93%  |
| XFCE       | 12        | 11.01%  |
| LXQt       | 5         | 4.59%   |
| X-Cinnamon | 4         | 3.67%   |
| MATE       | 4         | 3.67%   |
| KDE        | 3         | 2.75%   |
| Unity      | 2         | 1.83%   |
| i3         | 2         | 1.83%   |
| LXDE       | 1         | 0.92%   |
| Deepin     | 1         | 0.92%   |
| Cinnamon   | 1         | 0.92%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 81        | 75.7%   |
| Wayland | 17        | 15.89%  |
| Unknown | 8         | 7.48%   |
| Tty     | 1         | 0.93%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 49        | 44.55%  |
| SDDM    | 23        | 20.91%  |
| LightDM | 12        | 10.91%  |
| GDM3    | 9         | 8.18%   |
| GDM     | 9         | 8.18%   |
| TDM     | 8         | 7.27%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 44        | 40.74%  |
| es_CR   | 41        | 37.96%  |
| Unknown | 14        | 12.96%  |
| es_ES   | 6         | 5.56%   |
| C       | 2         | 1.85%   |
| es_MX   | 1         | 0.93%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 55        | 50%     |
| EFI  | 55        | 50%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 85        | 77.27%  |
| Overlay | 12        | 10.91%  |
| Btrfs   | 8         | 7.27%   |
| Unknown | 4         | 3.64%   |
| Xfs     | 1         | 0.91%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 58        | 53.7%   |
| GPT     | 37        | 34.26%  |
| MBR     | 13        | 12.04%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 99        | 90.83%  |
| Yes       | 10        | 9.17%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 69        | 63.89%  |
| Yes       | 39        | 36.11%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Hewlett-Packard  | 25        | 23.36%  |
| Dell             | 25        | 23.36%  |
| Lenovo           | 14        | 13.08%  |
| Toshiba          | 11        | 10.28%  |
| ASUSTek Computer | 8         | 7.48%   |
| Acer             | 8         | 7.48%   |
| Apple            | 5         | 4.67%   |
| MSI              | 2         | 1.87%   |
| System76         | 1         | 0.93%   |
| Sony             | 1         | 0.93%   |
| Purism           | 1         | 0.93%   |
| Olivetti         | 1         | 0.93%   |
| HUAWEI           | 1         | 0.93%   |
| Google           | 1         | 0.93%   |
| Deffad           | 1         | 0.93%   |
| AZW              | 1         | 0.93%   |
| Unknown          | 1         | 0.93%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Apple MacBookPro8,1                      | 4         | 3.74%   |
| Dell Inspiron 5584                       | 3         | 2.8%    |
| Unknown                                  | 3         | 2.8%    |
| HP ProBook 6460b                         | 2         | 1.87%   |
| HP Pavilion Notebook                     | 2         | 1.87%   |
| HP Notebook                              | 2         | 1.87%   |
| HP Laptop 15-da0xxx                      | 2         | 1.87%   |
| Toshiba Satellite X205                   | 1         | 0.93%   |
| Toshiba Satellite L655                   | 1         | 0.93%   |
| Toshiba Satellite L45-B                  | 1         | 0.93%   |
| Toshiba Satellite C855D                  | 1         | 0.93%   |
| Toshiba Satellite C845                   | 1         | 0.93%   |
| Toshiba Satellite C645D                  | 1         | 0.93%   |
| Toshiba Satellite C55-C                  | 1         | 0.93%   |
| Toshiba Satellite C55-B                  | 1         | 0.93%   |
| Toshiba Satellite C45-A                  | 1         | 0.93%   |
| Toshiba Satellite A305D                  | 1         | 0.93%   |
| Toshiba QOSMIO X775                      | 1         | 0.93%   |
| System76 Lemur                           | 1         | 0.93%   |
| Sony SVD13215PLB                         | 1         | 0.93%   |
| Purism Librem 15 v3                      | 1         | 0.93%   |
| Olivetti CL133A                          | 1         | 0.93%   |
| MSI GF75 Thin 9SD                        | 1         | 0.93%   |
| MSI GE60 2OC\2OD\2OE                     | 1         | 0.93%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BTS1EY00 | 1         | 0.93%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A80035US | 1         | 0.93%   |
| Lenovo ThinkPad T470 W10DG 20JM000CUS    | 1         | 0.93%   |
| Lenovo ThinkPad T440s 20ARS29U00         | 1         | 0.93%   |
| Lenovo ThinkPad P53 20QNS00P00           | 1         | 0.93%   |
| Lenovo ThinkPad P50 20EN001PUS           | 1         | 0.93%   |
| Lenovo ThinkPad L420 7829AA4             | 1         | 0.93%   |
| Lenovo ThinkPad L15 Gen 2 20X4S8YL00     | 1         | 0.93%   |
| Lenovo ThinkPad L14 Gen 1 20U1001TUS     | 1         | 0.93%   |
| Lenovo ThinkPad E15 Gen 2 20T8005BUS     | 1         | 0.93%   |
| Lenovo IdeaPad S340-15API 81NC           | 1         | 0.93%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY     | 1         | 0.93%   |
| Lenovo IdeaPad 330-15IKB 81DE            | 1         | 0.93%   |
| Lenovo IdeaPad 3 14ADA05 81W0            | 1         | 0.93%   |
| HUAWEI NBLK-WAX9X                        | 1         | 0.93%   |
| HP ProBook 455 G4                        | 1         | 0.93%   |
| HP ProBook 450 G2                        | 1         | 0.93%   |
| HP Pavilion Laptop 15-cc1xx              | 1         | 0.93%   |
| HP Pavilion g4                           | 1         | 0.93%   |
| HP Pavilion dv6000 (RP297UA#ABA)         | 1         | 0.93%   |
| HP Pavilion dv6                          | 1         | 0.93%   |
| HP Pavilion dv2500                       | 1         | 0.93%   |
| HP OMEN by Laptop                        | 1         | 0.93%   |
| HP Laptop 14-dq1xxx                      | 1         | 0.93%   |
| HP Laptop 14-ck0xxx                      | 1         | 0.93%   |
| HP Laptop 14-bp0xx                       | 1         | 0.93%   |
| HP EliteBook 8570p                       | 1         | 0.93%   |
| HP EliteBook 8460p                       | 1         | 0.93%   |
| HP EliteBook 820 G1                      | 1         | 0.93%   |
| HP 245 G4 Notebook PC                    | 1         | 0.93%   |
| HP 240 G6 Notebook PC                    | 1         | 0.93%   |
| Google Celes                             | 1         | 0.93%   |
| Dell XPS 15 9560                         | 1         | 0.93%   |
| Dell XPS 13 9305                         | 1         | 0.93%   |
| Dell Venue 11 Pro 7130 vPro              | 1         | 0.93%   |
| Dell Precision M4800                     | 1         | 0.93%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Toshiba Satellite | 10        | 9.35%   |
| Lenovo ThinkPad   | 10        | 9.35%   |
| Dell Latitude     | 10        | 9.35%   |
| Dell Inspiron     | 9         | 8.41%   |
| HP Pavilion       | 7         | 6.54%   |
| Acer Aspire       | 6         | 5.61%   |
| HP Laptop         | 5         | 4.67%   |
| Lenovo IdeaPad    | 4         | 3.74%   |
| HP ProBook        | 4         | 3.74%   |
| Apple MacBookPro8 | 4         | 3.74%   |
| HP EliteBook      | 3         | 2.8%    |
| ASUS VivoBook     | 3         | 2.8%    |
| Unknown           | 3         | 2.8%    |
| HP Notebook       | 2         | 1.87%   |
| Dell XPS          | 2         | 1.87%   |
| Dell G3           | 2         | 1.87%   |
| Toshiba QOSMIO    | 1         | 0.93%   |
| System76 Lemur    | 1         | 0.93%   |
| Sony SVD13215PLB  | 1         | 0.93%   |
| Purism Librem     | 1         | 0.93%   |
| Olivetti CL133A   | 1         | 0.93%   |
| MSI GF75          | 1         | 0.93%   |
| MSI GE60          | 1         | 0.93%   |
| HUAWEI NBLK-WAX9X | 1         | 0.93%   |
| HP OMEN           | 1         | 0.93%   |
| HP 245            | 1         | 0.93%   |
| HP 240            | 1         | 0.93%   |
| Google Celes      | 1         | 0.93%   |
| Dell Venue        | 1         | 0.93%   |
| Dell Precision    | 1         | 0.93%   |
| AZW GT-R          | 1         | 0.93%   |
| ASUS X555LAB      | 1         | 0.93%   |
| ASUS U46E         | 1         | 0.93%   |
| ASUS Strix        | 1         | 0.93%   |
| ASUS K52F         | 1         | 0.93%   |
| ASUS GL552VW      | 1         | 0.93%   |
| Apple MacBook2    | 1         | 0.93%   |
| Acer SW5-017P     | 1         | 0.93%   |
| Acer Nitro        | 1         | 0.93%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 16        | 14.95%  |
| 2018 | 12        | 11.21%  |
| 2011 | 12        | 11.21%  |
| 2017 | 9         | 8.41%   |
| 2020 | 8         | 7.48%   |
| 2015 | 8         | 7.48%   |
| 2014 | 8         | 7.48%   |
| 2013 | 7         | 6.54%   |
| 2016 | 6         | 5.61%   |
| 2012 | 6         | 5.61%   |
| 2008 | 4         | 3.74%   |
| 2007 | 3         | 2.8%    |
| 2021 | 2         | 1.87%   |
| 2010 | 2         | 1.87%   |
| 2009 | 2         | 1.87%   |
| 2006 | 2         | 1.87%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 107       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 99        | 92.52%  |
| Enabled  | 8         | 7.48%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 105       | 98.13%  |
| Yes  | 2         | 1.87%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 31        | 28.7%   |
| 3.01-4.0    | 26        | 24.07%  |
| 8.01-16.0   | 22        | 20.37%  |
| 16.01-24.0  | 14        | 12.96%  |
| 32.01-64.0  | 6         | 5.56%   |
| 2.01-3.0    | 3         | 2.78%   |
| 1.01-2.0    | 3         | 2.78%   |
| 64.01-256.0 | 2         | 1.85%   |
| 24.01-32.0  | 1         | 0.93%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 52        | 44.83%  |
| 2.01-3.0  | 33        | 28.45%  |
| 4.01-8.0  | 13        | 11.21%  |
| 3.01-4.0  | 11        | 9.48%   |
| 0.51-1.0  | 5         | 4.31%   |
| 8.01-16.0 | 2         | 1.72%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 84        | 78.5%   |
| 2      | 21        | 19.63%  |
| 3      | 2         | 1.87%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 58        | 54.21%  |
| Yes       | 49        | 45.79%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 92        | 85.98%  |
| No        | 15        | 14.02%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 104       | 97.2%   |
| No        | 3         | 2.8%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 79        | 73.15%  |
| No        | 29        | 26.85%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Notebooks | Percent |
|------------|-----------|---------|
| Costa Rica | 107       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| San José     | 40        | 33.9%   |
| Heredia       | 24        | 20.34%  |
| Alajuela      | 11        | 9.32%   |
| Quesada       | 4         | 3.39%   |
| Cartago       | 4         | 3.39%   |
| San Ramon     | 3         | 2.54%   |
| Escazu        | 3         | 2.54%   |
| Siquirres     | 2         | 1.69%   |
| Santa Cruz    | 2         | 1.69%   |
| Naranjo       | 2         | 1.69%   |
| Grecia        | 2         | 1.69%   |
| Esparza       | 2         | 1.69%   |
| Zarcero       | 1         | 0.85%   |
| Tres Rios     | 1         | 0.85%   |
| Santo Domingo | 1         | 0.85%   |
| Santiago      | 1         | 0.85%   |
| Santa Fe      | 1         | 0.85%   |
| San Pedro     | 1         | 0.85%   |
| San Pablo     | 1         | 0.85%   |
| San Juan      | 1         | 0.85%   |
| San Francisco | 1         | 0.85%   |
| Quepos        | 1         | 0.85%   |
| Puntarenas    | 1         | 0.85%   |
| Palmares      | 1         | 0.85%   |
| Nosara        | 1         | 0.85%   |
| Liberia       | 1         | 0.85%   |
| Guacima       | 1         | 0.85%   |
| Curridabat    | 1         | 0.85%   |
| Colon         | 1         | 0.85%   |
| Bagaces       | 1         | 0.85%   |
| Alpes         | 1         | 0.85%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 20        | 29     | 15.75%  |
| Toshiba             | 18        | 22     | 14.17%  |
| Seagate             | 12        | 19     | 9.45%   |
| Samsung Electronics | 12        | 18     | 9.45%   |
| Intel               | 11        | 16     | 8.66%   |
| HGST                | 8         | 9      | 6.3%    |
| Kingston            | 7         | 11     | 5.51%   |
| Unknown             | 6         | 10     | 4.72%   |
| A-DATA Technology   | 6         | 6      | 4.72%   |
| SK hynix            | 4         | 9      | 3.15%   |
| SanDisk             | 3         | 3      | 2.36%   |
| Micron Technology   | 3         | 3      | 2.36%   |
| Team                | 2         | 2      | 1.57%   |
| Patriot             | 2         | 2      | 1.57%   |
| Crucial             | 2         | 2      | 1.57%   |
| Zheino              | 1         | 1      | 0.79%   |
| UMIS                | 1         | 1      | 0.79%   |
| Transcend           | 1         | 1      | 0.79%   |
| Silicon Motion      | 1         | 1      | 0.79%   |
| Netac               | 1         | 1      | 0.79%   |
| LITEONIT            | 1         | 1      | 0.79%   |
| JMicron Technology  | 1         | 1      | 0.79%   |
| Hitachi             | 1         | 2      | 0.79%   |
| Fujitsu             | 1         | 1      | 0.79%   |
| Dell                | 1         | 1      | 0.79%   |
| Unknown             | 1         | 1      | 0.79%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB             | 4         | 2.96%   |
| Toshiba MQ01ABD100 1TB               | 4         | 2.96%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 3         | 2.22%   |
| Toshiba KBG30ZMS256G NVMe 256GB      | 3         | 2.22%   |
| Kingston SA400S37240G 240GB SSD      | 3         | 2.22%   |
| Intel SSDSC2BF180A4H 180GB           | 3         | 2.22%   |
| Intel SSDSA2CW300G3 304GB            | 3         | 2.22%   |
| HGST HTS541010A9E680 1TB             | 3         | 2.22%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD  | 2         | 1.48%   |
| SK hynix NVMe SSD Drive 128GB        | 2         | 1.48%   |
| Seagate ST1000LM035-1RK172 1TB       | 2         | 1.48%   |
| Kingston SV300S37A120G 120GB SSD     | 2         | 1.48%   |
| Intel SSDSC2MH250A2 250GB            | 2         | 1.48%   |
| Zheino CHN 25SATAA3 240 240GB        | 1         | 0.74%   |
| WDC WDS250G2B0B-00YS70 250GB SSD     | 1         | 0.74%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1         | 0.74%   |
| WDC WDS120G1G0B-00RC30 120GB SSD     | 1         | 0.74%   |
| WDC WD800BEVT-75ZCT2 80GB            | 1         | 0.74%   |
| WDC WD7500BPVT-22HXZT3 752GB         | 1         | 0.74%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 1         | 0.74%   |
| WDC WD5000LPCX-21VHAT0 500GB         | 1         | 0.74%   |
| WDC WD5000BPKT-60PK4T0 500GB         | 1         | 0.74%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 1         | 0.74%   |
| WDC WD20SPZX-08UA7 2TB               | 1         | 0.74%   |
| WDC WD1600BEVT-75A23T0 160GB         | 1         | 0.74%   |
| WDC WD10SPZX-60Z10T0 1TB             | 1         | 0.74%   |
| WDC WD10SPZX-21Z10T0 1TB             | 1         | 0.74%   |
| WDC WD10JPVX-75JC3T0 1TB             | 1         | 0.74%   |
| WDC WD10JPVX-60JC3T0 1TB             | 1         | 0.74%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 0.74%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB | 1         | 0.74%   |
| WDC PC SN730 SDBPNTY-512G-1027 512GB | 1         | 0.74%   |
| Unknown SP32G  32GB                  | 1         | 0.74%   |
| Unknown SC64G  64GB                  | 1         | 0.74%   |
| Unknown NVMe SSD Drive 256GB         | 1         | 0.74%   |
| Unknown MMC Card  64GB               | 1         | 0.74%   |
| Unknown MMC Card  32GB               | 1         | 0.74%   |
| Unknown MMC Card  128GB              | 1         | 0.74%   |
| Unknown HCG4a2  64GB                 | 1         | 0.74%   |
| Unknown 00000  129GB                 | 1         | 0.74%   |
| UMIS RPJTJ256MEE1OWX 256GB           | 1         | 0.74%   |
| Transcend TS256GSSD340 256GB         | 1         | 0.74%   |
| Toshiba MQ04ABF100 1TB               | 1         | 0.74%   |
| Toshiba MQ01ABD075 752GB             | 1         | 0.74%   |
| Toshiba MK6476GSX 640GB              | 1         | 0.74%   |
| Toshiba MK3265GSXN 320GB             | 1         | 0.74%   |
| Toshiba MK2565GSXV 250GB             | 1         | 0.74%   |
| Toshiba MK2546GSX 250GB              | 1         | 0.74%   |
| Toshiba MK1255GSX H 120GB            | 1         | 0.74%   |
| Team T253X1480G 480GB SSD            | 1         | 0.74%   |
| Team L5 LITE SSD 240GB               | 1         | 0.74%   |
| SK hynix NVMe SSD Drive 512GB        | 1         | 0.74%   |
| SK hynix HBG4e  32GB                 | 1         | 0.74%   |
| Silicon Motion 512GB                 | 1         | 0.74%   |
| Seagate ST980811AS 80GB              | 1         | 0.74%   |
| Seagate ST9750422AS 752GB            | 1         | 0.74%   |
| Seagate ST9500325AS 500GB            | 1         | 0.74%   |
| Seagate ST500LT012-1DG142 500GB      | 1         | 0.74%   |
| Seagate ST500LM021-1KJ152 500GB      | 1         | 0.74%   |
| Seagate ST2000LM007-1R8174 2TB       | 1         | 0.74%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 15        | 15     | 30.61%  |
| WDC     | 13        | 15     | 26.53%  |
| Seagate | 11        | 18     | 22.45%  |
| HGST    | 8         | 9      | 16.33%  |
| Hitachi | 1         | 2      | 2.04%   |
| Fujitsu | 1         | 1      | 2.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Intel               | 8         | 12     | 16.67%  |
| Samsung Electronics | 7         | 12     | 14.58%  |
| WDC                 | 6         | 11     | 12.5%   |
| Kingston            | 6         | 6      | 12.5%   |
| A-DATA Technology   | 5         | 5      | 10.42%  |
| Micron Technology   | 3         | 3      | 6.25%   |
| Team                | 2         | 2      | 4.17%   |
| SanDisk             | 2         | 2      | 4.17%   |
| Patriot             | 2         | 2      | 4.17%   |
| Crucial             | 2         | 2      | 4.17%   |
| Transcend           | 1         | 1      | 2.08%   |
| Seagate             | 1         | 1      | 2.08%   |
| Netac               | 1         | 1      | 2.08%   |
| LITEONIT            | 1         | 1      | 2.08%   |
| JMicron Technology  | 1         | 1      | 2.08%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 49        | 60     | 39.52%  |
| SSD     | 46        | 62     | 37.1%   |
| NVMe    | 20        | 38     | 16.13%  |
| MMC     | 7         | 11     | 5.65%   |
| Unknown | 2         | 2      | 1.61%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 91        | 121    | 75.21%  |
| NVMe | 20        | 38     | 16.53%  |
| MMC  | 7         | 11     | 5.79%   |
| SAS  | 3         | 3      | 2.48%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 60        | 71     | 62.5%   |
| 0.51-1.0   | 30        | 44     | 31.25%  |
| 1.01-2.0   | 6         | 7      | 6.25%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 36        | 31.86%  |
| 251-500        | 22        | 19.47%  |
| 501-1000       | 16        | 14.16%  |
| 1-20           | 10        | 8.85%   |
| 51-100         | 8         | 7.08%   |
| 1001-2000      | 7         | 6.19%   |
| 21-50          | 6         | 5.31%   |
| More than 3000 | 3         | 2.65%   |
| Unknown        | 3         | 2.65%   |
| 2001-3000      | 2         | 1.77%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 54        | 45.38%  |
| 21-50    | 24        | 20.17%  |
| 101-250  | 13        | 10.92%  |
| 51-100   | 13        | 10.92%  |
| 251-500  | 9         | 7.56%   |
| 501-1000 | 3         | 2.52%   |
| Unknown  | 3         | 2.52%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WD5000LPCX-60VHAT0 500GB                        | 1         | 1      | 10%     |
| WDC WD10JPVX-60JC3T0 1TB                            | 1         | 1      | 10%     |
| Toshiba MQ01ABD075 752GB                            | 1         | 1      | 10%     |
| Toshiba MK6476GSX 640GB                             | 1         | 1      | 10%     |
| Toshiba MK2565GSXV 250GB                            | 1         | 1      | 10%     |
| Micron Technology MTFDDAV256TBN-1AR15ABHA 256GB SSD | 1         | 1      | 10%     |
| Intel SSDSC2BF180A4H 180GB                          | 1         | 1      | 10%     |
| Hitachi HTS547550A9E384 500GB                       | 1         | 2      | 10%     |
| HGST HTS721010A9E630 1TB                            | 1         | 1      | 10%     |
| HGST HTS545050A7E380 500GB                          | 1         | 1      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Toshiba           | 3         | 3      | 30%     |
| WDC               | 2         | 2      | 20%     |
| HGST              | 2         | 2      | 20%     |
| Micron Technology | 1         | 1      | 10%     |
| Intel             | 1         | 1      | 10%     |
| Hitachi           | 1         | 2      | 10%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 3         | 3      | 37.5%   |
| WDC     | 2         | 2      | 25%     |
| HGST    | 2         | 2      | 25%     |
| Hitachi | 1         | 2      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 8         | 9      | 80%     |
| SSD  | 2         | 2      | 20%     |

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
| Detected | 61        | 98     | 53.51%  |
| Works    | 43        | 64     | 37.72%  |
| Malfunc  | 10        | 11     | 8.77%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 83        | 69.17%  |
| AMD                          | 15        | 12.5%   |
| Samsung Electronics          | 6         | 5%      |
| Toshiba America Info Systems | 3         | 2.5%    |
| SK hynix                     | 3         | 2.5%    |
| SanDisk                      | 3         | 2.5%    |
| Union Memory (Shenzhen)      | 1         | 0.83%   |
| Silicon Motion               | 1         | 0.83%   |
| Realtek Semiconductor        | 1         | 0.83%   |
| Nvidia                       | 1         | 0.83%   |
| Kingston Technology Company  | 1         | 0.83%   |
| ASMedia Technology           | 1         | 0.83%   |
| ADATA Technology             | 1         | 0.83%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 13        | 9.77%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 11        | 8.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 11        | 8.27%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 9         | 6.77%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 8         | 6.02%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 5         | 3.76%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 5         | 3.76%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 4         | 3.01%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 4         | 3.01%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 4         | 3.01%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                   | 3         | 2.26%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 3         | 2.26%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 3         | 2.26%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 3         | 2.26%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 3         | 2.26%   |
| SK hynix BC501 NVMe Solid State Drive                                                  | 2         | 1.5%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 2         | 1.5%    |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                | 2         | 1.5%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 2         | 1.5%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 2         | 1.5%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 2         | 1.5%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 2         | 1.5%    |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 2         | 1.5%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 2         | 1.5%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 2         | 1.5%    |
| Union Memory (Shenzhen) Non-Volatile memory controller                                 | 1         | 0.75%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                            | 1         | 0.75%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                        | 1         | 0.75%   |
| Samsung NVMe SSD Controller 980                                                        | 1         | 0.75%   |
| Realtek Realtek Non-Volatile memory controller                                         | 1         | 0.75%   |
| Nvidia MCP67 IDE Controller                                                            | 1         | 0.75%   |
| Nvidia MCP67 AHCI Controller                                                           | 1         | 0.75%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                  | 1         | 0.75%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 1         | 0.75%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 1         | 0.75%   |
| Intel Non-Volatile memory controller                                                   | 1         | 0.75%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 1         | 0.75%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 1         | 0.75%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                   | 1         | 0.75%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                           | 1         | 0.75%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 1         | 0.75%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 1         | 0.75%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                        | 1         | 0.75%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                        | 1         | 0.75%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 0.75%   |
| ASMedia ASM1062 Serial ATA Controller                                                  | 1         | 0.75%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                   | 1         | 0.75%   |
| AMD FCH IDE Controller                                                                 | 1         | 0.75%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                            | 1         | 0.75%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 80        | 64%     |
| NVMe | 21        | 16.8%   |
| IDE  | 14        | 11.2%   |
| RAID | 10        | 8%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 89        | 83.18%  |
| AMD    | 18        | 16.82%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz               | 4         | 3.74%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 3         | 2.8%    |
| Intel Core i7-8565U CPU @ 1.80GHz               | 3         | 2.8%    |
| Intel Core i7-2640M CPU @ 2.80GHz               | 3         | 2.8%    |
| Intel Celeron N4000 CPU @ 1.10GHz               | 3         | 2.8%    |
| Intel Celeron CPU N3060 @ 1.60GHz               | 3         | 2.8%    |
| Intel Core i7-9750H CPU @ 2.60GHz               | 2         | 1.87%   |
| Intel Core i7-8665U CPU @ 1.90GHz               | 2         | 1.87%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz              | 2         | 1.87%   |
| Intel Core i7-4600U CPU @ 2.10GHz               | 2         | 1.87%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 2         | 1.87%   |
| Intel Core i5-6200U CPU @ 2.30GHz               | 2         | 1.87%   |
| Intel Core i5-4200U CPU @ 1.60GHz               | 2         | 1.87%   |
| Intel Core i3-8130U CPU @ 2.20GHz               | 2         | 1.87%   |
| Intel Core i3-5005U CPU @ 2.00GHz               | 2         | 1.87%   |
| Intel Core i3 CPU M 380 @ 2.53GHz               | 2         | 1.87%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz               | 2         | 1.87%   |
| AMD A10-9600P RADEON R5, 10 COMPUTE CORES 4C+6G | 2         | 1.87%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz            | 1         | 0.93%   |
| Intel Pentium CPU P6100 @ 2.00GHz               | 1         | 0.93%   |
| Intel Pentium CPU B960 @ 2.20GHz                | 1         | 0.93%   |
| Intel Genuine CPU U4100 @ 1.30GHz               | 1         | 0.93%   |
| Intel Genuine CPU T2060 @ 1.60GHz               | 1         | 0.93%   |
| Intel Core i7-9850H CPU @ 2.60GHz               | 1         | 0.93%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 1         | 0.93%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 1         | 0.93%   |
| Intel Core i7-7600U CPU @ 2.80GHz               | 1         | 0.93%   |
| Intel Core i7-7500U CPU @ 2.70GHz               | 1         | 0.93%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz              | 1         | 0.93%   |
| Intel Core i7-6500U CPU @ 2.50GHz               | 1         | 0.93%   |
| Intel Core i7-5600U CPU @ 2.60GHz               | 1         | 0.93%   |
| Intel Core i7-3520M CPU @ 2.90GHz               | 1         | 0.93%   |
| Intel Core i7-2760QM CPU @ 2.40GHz              | 1         | 0.93%   |
| Intel Core i7-2630QM CPU @ 2.00GHz              | 1         | 0.93%   |
| Intel Core i7-2620M CPU @ 2.70GHz               | 1         | 0.93%   |
| Intel Core i5-8350U CPU @ 1.70GHz               | 1         | 0.93%   |
| Intel Core i5-8265U CPU @ 1.60GHz               | 1         | 0.93%   |
| Intel Core i5-5300U CPU @ 2.30GHz               | 1         | 0.93%   |
| Intel Core i5-5200U CPU @ 2.20GHz               | 1         | 0.93%   |
| Intel Core i5-4300Y CPU @ 1.60GHz               | 1         | 0.93%   |
| Intel Core i5-4300U CPU @ 1.90GHz               | 1         | 0.93%   |
| Intel Core i5-4210U CPU @ 1.70GHz               | 1         | 0.93%   |
| Intel Core i5-3210M CPU @ 2.50GHz               | 1         | 0.93%   |
| Intel Core i5-2435M CPU @ 2.40GHz               | 1         | 0.93%   |
| Intel Core i5-2410M CPU @ 2.30GHz               | 1         | 0.93%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz              | 1         | 0.93%   |
| Intel Core i5-10210U CPU @ 1.60GHz              | 1         | 0.93%   |
| Intel Core i3-7020U CPU @ 2.30GHz               | 1         | 0.93%   |
| Intel Core i3-6100U CPU @ 2.30GHz               | 1         | 0.93%   |
| Intel Core i3-5020U CPU @ 2.20GHz               | 1         | 0.93%   |
| Intel Core i3-4005U CPU @ 1.70GHz               | 1         | 0.93%   |
| Intel Core i3-4000M CPU @ 2.40GHz               | 1         | 0.93%   |
| Intel Core i3-2370M CPU @ 2.40GHz               | 1         | 0.93%   |
| Intel Core i3-2310M CPU @ 2.10GHz               | 1         | 0.93%   |
| Intel Core 2 Duo CPU T7100 @ 1.80GHz            | 1         | 0.93%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz            | 1         | 0.93%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz            | 1         | 0.93%   |
| Intel Core 2 CPU T7200 @ 2.00GHz                | 1         | 0.93%   |
| Intel Core 2 CPU T5600 @ 1.83GHz                | 1         | 0.93%   |
| Intel Celeron N4020 CPU @ 1.10GHz               | 1         | 0.93%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i7                  | 29        | 27.1%   |
| Intel Core i5                  | 22        | 20.56%  |
| Intel Core i3                  | 13        | 12.15%  |
| Intel Celeron                  | 11        | 10.28%  |
| Other                          | 3         | 2.8%    |
| Intel Core 2 Duo               | 3         | 2.8%    |
| AMD Ryzen 7                    | 3         | 2.8%    |
| AMD Ryzen 5                    | 3         | 2.8%    |
| Intel Pentium                  | 2         | 1.87%   |
| Intel Genuine                  | 2         | 1.87%   |
| Intel Core 2                   | 2         | 1.87%   |
| Intel Atom                     | 2         | 1.87%   |
| AMD Ryzen 3                    | 2         | 1.87%   |
| AMD E1                         | 2         | 1.87%   |
| AMD A8                         | 2         | 1.87%   |
| AMD A10                        | 2         | 1.87%   |
| Intel Xeon                     | 1         | 0.93%   |
| AMD V120                       | 1         | 0.93%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.93%   |
| AMD Turion 64 X2               | 1         | 0.93%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 71        | 66.36%  |
| 4      | 27        | 25.23%  |
| 6      | 7         | 6.54%   |
| 8      | 1         | 0.93%   |
| 1      | 1         | 0.93%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 107       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 75        | 70.09%  |
| 1      | 32        | 29.91%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 105       | 97.22%  |
| Unknown        | 2         | 1.85%   |
| 32-bit         | 1         | 0.93%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 18        | 16.51%  |
| 0x206a7    | 12        | 11.01%  |
| 0x40651    | 7         | 6.42%   |
| 0x306d4    | 6         | 5.5%    |
| 0x806e9    | 5         | 4.59%   |
| 0x406c4    | 5         | 4.59%   |
| 0x08108109 | 5         | 4.59%   |
| 0x906ea    | 4         | 3.67%   |
| 0x806ec    | 4         | 3.67%   |
| 0x706a1    | 4         | 3.67%   |
| 0x406e3    | 4         | 3.67%   |
| 0x806eb    | 3         | 2.75%   |
| 0x306c3    | 3         | 2.75%   |
| 0x20655    | 3         | 2.75%   |
| 0x806ea    | 2         | 1.83%   |
| 0x6fd      | 2         | 1.83%   |
| 0x506e3    | 2         | 1.83%   |
| 0x306a9    | 2         | 1.83%   |
| 0x1067a    | 2         | 1.83%   |
| 0x906ed    | 1         | 0.92%   |
| 0x906e9    | 1         | 0.92%   |
| 0x806c1    | 1         | 0.92%   |
| 0x706a8    | 1         | 0.92%   |
| 0x6f6      | 1         | 0.92%   |
| 0x6ec      | 1         | 0.92%   |
| 0x30678    | 1         | 0.92%   |
| 0x08600104 | 1         | 0.92%   |
| 0x08600103 | 1         | 0.92%   |
| 0x07030105 | 1         | 0.92%   |
| 0x07000110 | 1         | 0.92%   |
| 0x06006118 | 1         | 0.92%   |
| 0x05000119 | 1         | 0.92%   |
| 0x03000027 | 1         | 0.92%   |
| 0x02000057 | 1         | 0.92%   |
| 0x010000c8 | 1         | 0.92%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 23        | 21.5%   |
| SandyBridge     | 16        | 14.95%  |
| Haswell         | 11        | 10.28%  |
| Silvermont      | 7         | 6.54%   |
| Zen+            | 6         | 5.61%   |
| Skylake         | 6         | 5.61%   |
| Broadwell       | 6         | 5.61%   |
| Goldmont plus   | 5         | 4.67%   |
| Core            | 4         | 3.74%   |
| Westmere        | 3         | 2.8%    |
| Excavator       | 3         | 2.8%    |
| Zen 2           | 2         | 1.87%   |
| TigerLake       | 2         | 1.87%   |
| Penryn          | 2         | 1.87%   |
| IvyBridge       | 2         | 1.87%   |
| Puma            | 1         | 0.93%   |
| P6              | 1         | 0.93%   |
| K8 Hammer       | 1         | 0.93%   |
| K8 & K10 hybrid | 1         | 0.93%   |
| K10 Llano       | 1         | 0.93%   |
| K10             | 1         | 0.93%   |
| Jaguar          | 1         | 0.93%   |
| IceLake         | 1         | 0.93%   |
| Bobcat          | 1         | 0.93%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 85        | 69.11%  |
| AMD    | 21        | 17.07%  |
| Nvidia | 17        | 13.82%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 14        | 10.77%  |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 5.38%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 6         | 4.62%   |
| Intel HD Graphics 5500                                                                   | 6         | 4.62%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 4.62%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 4.62%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6         | 4.62%   |
| Intel HD Graphics 620                                                                    | 5         | 3.85%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 3.85%   |
| Intel UHD Graphics 620                                                                   | 4         | 3.08%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 3.08%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 2.31%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 3         | 2.31%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 2.31%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 2.31%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 1.54%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 1.54%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 1.54%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 1.54%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.54%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 1.54%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 1.54%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 1.54%   |
| AMD Renoir                                                                               | 2         | 1.54%   |
| Nvidia TU117M                                                                            | 1         | 0.77%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 1         | 0.77%   |
| Nvidia GP108M [GeForce MX230]                                                            | 1         | 0.77%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.77%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.77%   |
| Nvidia GM107GLM [Quadro M2000M]                                                          | 1         | 0.77%   |
| Nvidia GK106M [GeForce GTX 765M]                                                         | 1         | 0.77%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.77%   |
| Nvidia GF116M [GeForce GT 560M]                                                          | 1         | 0.77%   |
| Nvidia G84M [GeForce 8700M GT]                                                           | 1         | 0.77%   |
| Nvidia C67 [GeForce 7150M / nForce 630M]                                                 | 1         | 0.77%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 0.77%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 0.77%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 1         | 0.77%   |
| Intel HD Graphics P530                                                                   | 1         | 0.77%   |
| Intel HD Graphics 630                                                                    | 1         | 0.77%   |
| Intel HD Graphics 530                                                                    | 1         | 0.77%   |
| Intel Haswell-ULT High Definition Audio Controller [HD Graphics]                         | 1         | 0.77%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 0.77%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 0.77%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1         | 0.77%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 1         | 0.77%   |
| AMD Venus XT [Radeon HD 8870M / R9 M270X/M370X]                                          | 1         | 0.77%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 1         | 0.77%   |
| AMD Sumo [Radeon HD 6620G]                                                               | 1         | 0.77%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1         | 0.77%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 1         | 0.77%   |
| AMD RS780MC [Mobility Radeon HD 3100]                                                    | 1         | 0.77%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 1         | 0.77%   |
| AMD Kabini [Radeon HD 8240 / R3 Series]                                                  | 1         | 0.77%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 1         | 0.77%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 70        | 65.42%  |
| 1 x AMD        | 16        | 14.95%  |
| Intel + Nvidia | 14        | 13.08%  |
| 2 x AMD        | 3         | 2.8%    |
| 1 x Nvidia     | 2         | 1.87%   |
| Intel + AMD    | 1         | 0.93%   |
| AMD + Nvidia   | 1         | 0.93%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 97        | 89.81%  |
| Proprietary | 9         | 8.33%   |
| Unknown     | 2         | 1.85%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 82        | 75.93%  |
| 1.01-2.0   | 8         | 7.41%   |
| 0.01-0.5   | 8         | 7.41%   |
| 3.01-4.0   | 5         | 4.63%   |
| 0.51-1.0   | 4         | 3.7%    |
| 5.01-6.0   | 1         | 0.93%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 27        | 21.26%  |
| LG Display              | 20        | 15.75%  |
| Chimei Innolux          | 16        | 12.6%   |
| Samsung Electronics     | 15        | 11.81%  |
| BOE                     | 12        | 9.45%   |
| Apple                   | 5         | 3.94%   |
| AOC                     | 5         | 3.94%   |
| Goldstar                | 3         | 2.36%   |
| Chi Mei Optoelectronics | 3         | 2.36%   |
| Sharp                   | 2         | 1.57%   |
| Hewlett-Packard         | 2         | 1.57%   |
| Dell                    | 2         | 1.57%   |
| CPT                     | 2         | 1.57%   |
| ViewSonic               | 1         | 0.79%   |
| Sony                    | 1         | 0.79%   |
| Panasonic               | 1         | 0.79%   |
| LG Philips              | 1         | 0.79%   |
| KDC                     | 1         | 0.79%   |
| Hitachi                 | 1         | 0.79%   |
| GAOMON                  | 1         | 0.79%   |
| Envision                | 1         | 0.79%   |
| CVT                     | 1         | 0.79%   |
| ASUSTek Computer        | 1         | 0.79%   |
| Ancor Communications    | 1         | 0.79%   |
| AGO                     | 1         | 0.79%   |
| Acer                    | 1         | 0.79%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch                  | 4         | 3.15%   |
| AU Optronics LCD Monitor AUO25ED 1920x1080 340x190mm 15.3-inch          | 3         | 2.36%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch            | 2         | 1.57%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch             | 2         | 1.57%   |
| Hewlett-Packard 22cwa HWP3183 1920x1080 476x268mm 21.5-inch             | 2         | 1.57%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 2         | 1.57%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch        | 2         | 1.57%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch         | 2         | 1.57%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch         | 2         | 1.57%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch         | 2         | 1.57%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch          | 2         | 1.57%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch           | 2         | 1.57%   |
| ViewSonic VA2359 Series VSC6332 1920x1080 509x286mm 23.0-inch           | 1         | 0.79%   |
| Sony TV SNY0902 1360x768                                                | 1         | 0.79%   |
| Sharp LCD Monitor SHP14AD 3840x2160 294x165mm 13.3-inch                 | 1         | 0.79%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                 | 1         | 0.79%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch       | 1         | 0.79%   |
| Samsung Electronics SyncMaster SAM058A 1920x1080 531x298mm 24.0-inch    | 1         | 0.79%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch    | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SEC4E45 1280x800 331x207mm 15.4-inch    | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch    | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SEC4145 1366x768 309x174mm 14.0-inch    | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 367x230mm 17.1-inch    | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SEC345A 1366x768 309x174mm 14.0-inch    | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 331x207mm 15.4-inch    | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch    | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch   | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SDC4141 3840x2160 344x194mm 15.5-inch   | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 1872x1053mm 84.6-inch | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 1872x1053mm 84.6-inch | 1         | 0.79%   |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                      | 1         | 0.79%   |
| LG Philips LP154WX4-TLC8 LPL0120 1280x800 331x207mm 15.4-inch           | 1         | 0.79%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch           | 1         | 0.79%   |
| LG Display LCD Monitor LGD062C 1920x1080 309x174mm 14.0-inch            | 1         | 0.79%   |
| LG Display LCD Monitor LGD05F2 1920x1080 344x194mm 15.5-inch            | 1         | 0.79%   |
| LG Display LCD Monitor LGD05E6 1920x1080 344x194mm 15.5-inch            | 1         | 0.79%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch            | 1         | 0.79%   |
| LG Display LCD Monitor LGD0493 1366x768 344x194mm 15.5-inch             | 1         | 0.79%   |
| LG Display LCD Monitor LGD0484 1366x768 344x194mm 15.5-inch             | 1         | 0.79%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch            | 1         | 0.79%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch             | 1         | 0.79%   |
| LG Display LCD Monitor LGD0454 1366x768 310x174mm 14.0-inch             | 1         | 0.79%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch             | 1         | 0.79%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch             | 1         | 0.79%   |
| LG Display LCD Monitor LGD02EB 1366x768 309x174mm 14.0-inch             | 1         | 0.79%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch             | 1         | 0.79%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch            | 1         | 0.79%   |
| LG Display LCD Monitor LGD01E6 1366x768 309x174mm 14.0-inch             | 1         | 0.79%   |
| KDC LCD Monitor KDC05F1 1366x768 256x144mm 11.6-inch                    | 1         | 0.79%   |
| Hitachi 50A3 HTC011C 1440x900 708x398mm 32.0-inch                       | 1         | 0.79%   |
| Goldstar 2D HD TV GSM59CA 1366x768 509x286mm 23.0-inch                  | 1         | 0.79%   |
| GAOMON PD1560 GAM1560 1920x1080 345x195mm 15.6-inch                     | 1         | 0.79%   |
| Envision EPI2442 EPI2442 1360x768 525x297mm 23.7-inch                   | 1         | 0.79%   |
| Dell P2417H DELA0DC 1920x1080 530x300mm 24.0-inch                       | 1         | 0.79%   |
| Dell E198FP DELA028 1280x1024 376x301mm 19.0-inch                       | 1         | 0.79%   |
| CVT LCD CVT001A 1920x1080 330x210mm 15.4-inch                           | 1         | 0.79%   |
| CPT LCD Monitor CPT1775 1280x800 304x190mm 14.1-inch                    | 1         | 0.79%   |
| CPT LCD Monitor COR0207 1366x768 309x174mm 14.0-inch                    | 1         | 0.79%   |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 381x214mm 17.2-inch        | 1         | 0.79%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1366x768 (WXGA)  | 45        | 38.14%  |
| 1920x1080 (FHD)  | 42        | 35.59%  |
| 1280x800 (WXGA)  | 10        | 8.47%   |
| 3840x2160 (4K)   | 8         | 6.78%   |
| 1600x900 (HD+)   | 7         | 5.93%   |
| 1440x900 (WXGA+) | 3         | 2.54%   |
| 1280x1024 (SXGA) | 2         | 1.69%   |
| 1360x768         | 1         | 0.85%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 50        | 40%     |
| 14     | 21        | 16.8%   |
| 13     | 20        | 16%     |
| 23     | 6         | 4.8%    |
| 17     | 6         | 4.8%    |
| 84     | 3         | 2.4%    |
| 24     | 3         | 2.4%    |
| 21     | 3         | 2.4%    |
| 19     | 3         | 2.4%    |
| 18     | 3         | 2.4%    |
| 12     | 2         | 1.6%    |
| 11     | 2         | 1.6%    |
| 72     | 1         | 0.8%    |
| 32     | 1         | 0.8%    |
| 31     | 1         | 0.8%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 85        | 68%     |
| 201-300     | 11        | 8.8%    |
| 501-600     | 9         | 7.2%    |
| 401-500     | 8         | 6.4%    |
| 351-400     | 6         | 4.8%    |
| 1501-2000   | 4         | 3.2%    |
| 701-800     | 1         | 0.8%    |
| 601-700     | 1         | 0.8%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 90        | 84.11%  |
| 16/10 | 14        | 13.08%  |
| 5/4   | 2         | 1.87%   |
| 4/3   | 1         | 0.93%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 50        | 40.32%  |
| 81-90          | 39        | 31.45%  |
| 201-250        | 11        | 8.87%   |
| More than 1000 | 4         | 3.23%   |
| 151-200        | 4         | 3.23%   |
| 121-130        | 4         | 3.23%   |
| 71-80          | 3         | 2.42%   |
| 141-150        | 3         | 2.42%   |
| 51-60          | 2         | 1.61%   |
| 351-500        | 2         | 1.61%   |
| 61-70          | 1         | 0.81%   |
| 131-140        | 1         | 0.81%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 53        | 43.44%  |
| 121-160       | 44        | 36.07%  |
| 51-100        | 20        | 16.39%  |
| More than 240 | 2         | 1.64%   |
| 1-50          | 2         | 1.64%   |
| 161-240       | 1         | 0.82%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 88        | 77.88%  |
| 2     | 21        | 18.58%  |
| 3     | 2         | 1.77%   |
| 0     | 2         | 1.77%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 60        | 34.68%  |
| Intel                    | 45        | 26.01%  |
| Qualcomm Atheros         | 32        | 18.5%   |
| Broadcom                 | 15        | 8.67%   |
| Broadcom Limited         | 7         | 4.05%   |
| TP-Link                  | 4         | 2.31%   |
| ASIX Electronics         | 2         | 1.16%   |
| Xiaomi                   | 1         | 0.58%   |
| Nvidia                   | 1         | 0.58%   |
| MediaTek                 | 1         | 0.58%   |
| Marvell Technology Group | 1         | 0.58%   |
| JMicron Technology       | 1         | 0.58%   |
| Huawei Technologies      | 1         | 0.58%   |
| DisplayLink              | 1         | 0.58%   |
| Dell                     | 1         | 0.58%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 30        | 13.82%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 20        | 9.22%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 8         | 3.69%   |
| Intel Wireless 7265                                                                   | 7         | 3.23%   |
| Intel Wireless 7260                                                                   | 6         | 2.76%   |
| Realtek RTL8723DE Wireless Network Adapter                                            | 5         | 2.3%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                              | 5         | 2.3%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 5         | 2.3%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 5         | 2.3%    |
| Broadcom BCM43142 802.11b/g/n                                                         | 5         | 2.3%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 4         | 1.84%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 4         | 1.84%   |
| Intel Wi-Fi 6 AX200                                                                   | 4         | 1.84%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 4         | 1.84%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 4         | 1.84%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                                     | 4         | 1.84%   |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 4         | 1.84%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 3         | 1.38%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 3         | 1.38%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 3         | 1.38%   |
| Intel Ethernet Connection I218-LM                                                     | 3         | 1.38%   |
| Intel Ethernet Connection (4) I219-LM                                                 | 3         | 1.38%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 3         | 1.38%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                                             | 2         | 0.92%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 2         | 0.92%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                            | 2         | 0.92%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                            | 2         | 0.92%   |
| Intel Wireless 8265 / 8275                                                            | 2         | 0.92%   |
| Intel Wireless 8260                                                                   | 2         | 0.92%   |
| Intel Wireless 3160                                                                   | 2         | 0.92%   |
| Intel Ethernet Connection (3) I218-LM                                                 | 2         | 0.92%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 2         | 0.92%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                                     | 2         | 0.92%   |
| Broadcom Limited BCM4311 802.11a/b/g                                                  | 2         | 0.92%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                        | 1         | 0.46%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                                 | 1         | 0.46%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                            | 1         | 0.46%   |
| Realtek USB 10/100/1G/2.5G LAN                                                        | 1         | 0.46%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                              | 1         | 0.46%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 1         | 0.46%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 1         | 0.46%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                       | 1         | 0.46%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                                | 1         | 0.46%   |
| Realtek 802.11ac NIC                                                                  | 1         | 0.46%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                             | 1         | 0.46%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 1         | 0.46%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                                 | 1         | 0.46%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                              | 1         | 0.46%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                         | 1         | 0.46%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 0.46%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 1         | 0.46%   |
| Qualcomm Atheros AR2427 802.11bg Wireless Network Adapter (PCI-Express)               | 1         | 0.46%   |
| Nvidia MCP67 Ethernet                                                                 | 1         | 0.46%   |
| MediaTek moto e6s                                                                     | 1         | 0.46%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                               | 1         | 0.46%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                                | 1         | 0.46%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                         | 1         | 0.46%   |
| Intel PRO/100 VE Network Connection                                                   | 1         | 0.46%   |
| Intel Ethernet Connection I219-V                                                      | 1         | 0.46%   |
| Intel Ethernet Connection I218-V                                                      | 1         | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 40        | 36.36%  |
| Qualcomm Atheros      | 27        | 24.55%  |
| Realtek Semiconductor | 19        | 17.27%  |
| Broadcom              | 12        | 10.91%  |
| Broadcom Limited      | 7         | 6.36%   |
| TP-Link               | 4         | 3.64%   |
| Dell                  | 1         | 0.91%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 8         | 7.14%   |
| Intel Wireless 7265                                                                   | 7         | 6.25%   |
| Intel Wireless 7260                                                                   | 6         | 5.36%   |
| Realtek RTL8723DE Wireless Network Adapter                                            | 5         | 4.46%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 5         | 4.46%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 5         | 4.46%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 5         | 4.46%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 4         | 3.57%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 4         | 3.57%   |
| Intel Wi-Fi 6 AX200                                                                   | 4         | 3.57%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 4         | 3.57%   |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 4         | 3.57%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 3         | 2.68%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 3         | 2.68%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 3         | 2.68%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 3         | 2.68%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                                             | 2         | 1.79%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 2         | 1.79%   |
| Intel Wireless 8265 / 8275                                                            | 2         | 1.79%   |
| Intel Wireless 8260                                                                   | 2         | 1.79%   |
| Intel Wireless 3160                                                                   | 2         | 1.79%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 2         | 1.79%   |
| Broadcom Limited BCM4311 802.11a/b/g                                                  | 2         | 1.79%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                                 | 1         | 0.89%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                            | 1         | 0.89%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                              | 1         | 0.89%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 1         | 0.89%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 1         | 0.89%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                       | 1         | 0.89%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                                | 1         | 0.89%   |
| Realtek 802.11ac NIC                                                                  | 1         | 0.89%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 1         | 0.89%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 0.89%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 1         | 0.89%   |
| Qualcomm Atheros AR2427 802.11bg Wireless Network Adapter (PCI-Express)               | 1         | 0.89%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                         | 1         | 0.89%   |
| Intel Centrino Wireless-N 6150                                                        | 1         | 0.89%   |
| Intel Centrino Wireless-N 2230                                                        | 1         | 0.89%   |
| Intel Centrino Wireless-N + WiMAX 6150                                                | 1         | 0.89%   |
| Dell Wireless 5808e Gobiâ¢ 4G LTE Mobile Broadband Card                           | 1         | 0.89%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                            | 1         | 0.89%   |
| Broadcom Limited BCM43225 802.11b/g/n                                                 | 1         | 0.89%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                                               | 1         | 0.89%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                             | 1         | 0.89%   |
| Broadcom Limited BCM4311 802.11b/g WLAN                                               | 1         | 0.89%   |
| Broadcom BCM43227 802.11b/g/n                                                         | 1         | 0.89%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 1         | 0.89%   |
| Broadcom BCM4311 802.11b/g WLAN                                                       | 1         | 0.89%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 54        | 53.47%  |
| Intel                    | 22        | 21.78%  |
| Qualcomm Atheros         | 8         | 7.92%   |
| Broadcom                 | 8         | 7.92%   |
| ASIX Electronics         | 2         | 1.98%   |
| Xiaomi                   | 1         | 0.99%   |
| Nvidia                   | 1         | 0.99%   |
| MediaTek                 | 1         | 0.99%   |
| Marvell Technology Group | 1         | 0.99%   |
| JMicron Technology       | 1         | 0.99%   |
| Huawei Technologies      | 1         | 0.99%   |
| DisplayLink              | 1         | 0.99%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 30        | 28.57%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 20        | 19.05%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 4.76%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 3.81%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 3.81%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 2.86%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 2.86%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 1.9%    |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 2         | 1.9%    |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 1.9%    |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 2         | 1.9%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.95%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1         | 0.95%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.95%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.95%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.95%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.95%   |
| Nvidia MCP67 Ethernet                                             | 1         | 0.95%   |
| MediaTek moto e6s                                                 | 1         | 0.95%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 0.95%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.95%   |
| Intel PRO/100 VE Network Connection                               | 1         | 0.95%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.95%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.95%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.95%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.95%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.95%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.95%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.95%   |
| Intel 82599 10 Gigabit Network Connection                         | 1         | 0.95%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.95%   |
| Huawei E353/E3131                                                 | 1         | 0.95%   |
| DisplayLink Dell Universal Dock D6000                             | 1         | 0.95%   |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                 | 1         | 0.95%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express          | 1         | 0.95%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1         | 0.95%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 0.95%   |
| ASIX AX88772A Fast Ethernet                                       | 1         | 0.95%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 0.95%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 104       | 53.06%  |
| Ethernet | 92        | 46.94%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 85        | 77.27%  |
| Ethernet | 25        | 22.73%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 85        | 79.44%  |
| 1     | 16        | 14.95%  |
| 3     | 4         | 3.74%   |
| 0     | 2         | 1.87%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 106       | 98.15%  |
| Yes  | 2         | 1.85%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 31        | 38.75%  |
| Qualcomm Atheros Communications | 13        | 16.25%  |
| Realtek Semiconductor           | 12        | 15%     |
| Broadcom                        | 6         | 7.5%    |
| Apple                           | 5         | 6.25%   |
| Toshiba                         | 3         | 3.75%   |
| Lite-On Technology              | 2         | 2.5%    |
| IMC Networks                    | 2         | 2.5%    |
| Cambridge Silicon Radio         | 2         | 2.5%    |
| Realtek                         | 1         | 1.25%   |
| Hewlett-Packard                 | 1         | 1.25%   |
| Foxconn / Hon Hai               | 1         | 1.25%   |
| Dell                            | 1         | 1.25%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 17        | 21.25%  |
| Qualcomm Atheros  Bluetooth Device                  | 9         | 11.25%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 7         | 8.75%   |
| Realtek  Bluetooth 4.2 Adapter                      | 6         | 7.5%    |
| Realtek Bluetooth Radio                             | 6         | 7.5%    |
| Intel AX200 Bluetooth                               | 4         | 5%      |
| Apple Bluetooth Host Controller                     | 4         | 5%      |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 3         | 3.75%   |
| Toshiba Bluetooth Device                            | 2         | 2.5%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 2.5%    |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 2.5%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 2.5%    |
| Toshiba BCM43142A0                                  | 1         | 1.25%   |
| Realtek Bluetooth Radio                             | 1         | 1.25%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 1.25%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 1.25%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 1.25%   |
| Lite-On Bluetooth Device                            | 1         | 1.25%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.25%   |
| IMC Networks Bluetooth Radio                        | 1         | 1.25%   |
| IMC Networks Bluetooth                              | 1         | 1.25%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 1.25%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 1.25%   |
| Dell Broadcom BCM20702A0 Bluetooth                  | 1         | 1.25%   |
| Broadcom HP Portable SoftSailing                    | 1         | 1.25%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 1.25%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 1.25%   |
| Apple Bluetooth HCI                                 | 1         | 1.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 88        | 67.69%  |
| AMD                    | 21        | 16.15%  |
| Nvidia                 | 8         | 6.15%   |
| Generalplus Technology | 3         | 2.31%   |
| JMTek                  | 2         | 1.54%   |
| C-Media Electronics    | 2         | 1.54%   |
| Plantronics            | 1         | 0.77%   |
| Logitech               | 1         | 0.77%   |
| Lenovo                 | 1         | 0.77%   |
| GN Netcom              | 1         | 0.77%   |
| CMX Systems            | 1         | 0.77%   |
| Afatech                | 1         | 0.77%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 13        | 8.13%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 13        | 8.13%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 8         | 5%      |
| Intel 8 Series HD Audio Controller                                                                | 8         | 5%      |
| AMD Family 17h/19h HD Audio Controller                                                            | 8         | 5%      |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 3.75%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 6         | 3.75%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 3.75%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 3.75%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 3.75%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 3.13%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 5         | 3.13%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 2.5%    |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 2.5%    |
| AMD FCH Azalia Controller                                                                         | 4         | 2.5%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 1.88%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 1.88%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 1.88%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 1.88%   |
| Generalplus Technology USB Audio Device                                                           | 3         | 1.88%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 1.88%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 1.25%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 1.25%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 1.25%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 1.25%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 1.25%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 1.25%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 1.25%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 1.25%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 2         | 1.25%   |
| Plantronics Blackwire 3225 Series                                                                 | 1         | 0.63%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.63%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 1         | 0.63%   |
| Logitech Headset H390                                                                             | 1         | 0.63%   |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                                                         | 1         | 0.63%   |
| JMTek USB PnP Audio Device                                                                        | 1         | 0.63%   |
| JMTek LCS USB Audio                                                                               | 1         | 0.63%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 0.63%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 0.63%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.63%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series Low Power Engine Audio           | 1         | 0.63%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.63%   |
| GN Netcom Jabra PRO 9460                                                                          | 1         | 0.63%   |
| CMX Systems EarPods_TC01_K9I                                                                      | 1         | 0.63%   |
| C-Media Electronics Q9-1                                                                          | 1         | 0.63%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 1         | 0.63%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 1         | 0.63%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 0.63%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 1         | 0.63%   |
| AMD High Definition Audio Controller                                                              | 1         | 0.63%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 1         | 0.63%   |
| Afatech GAMDIAS USB Audio Device                                                                  | 1         | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 23        | 33.33%  |
| SK hynix            | 11        | 15.94%  |
| Kingston            | 7         | 10.14%  |
| Micron Technology   | 6         | 8.7%    |
| Team                | 4         | 5.8%    |
| Nanya Technology    | 4         | 5.8%    |
| Corsair             | 4         | 5.8%    |
| Unknown             | 3         | 4.35%   |
| Crucial             | 3         | 4.35%   |
| A-DATA Technology   | 3         | 4.35%   |
| Patriot             | 1         | 1.45%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s           | 4         | 4.88%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s       | 3         | 3.66%   |
| Corsair RAM Module 8GB SODIMM DDR3 1333MT/s                    | 3         | 3.66%   |
| Corsair RAM Module 4GB SODIMM DDR3 1333MT/s                    | 3         | 3.66%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 2         | 2.44%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 2         | 2.44%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 2         | 2.44%   |
| Samsung RAM M471B5773DH0-CH9 2048MB SODIMM DDR3 1600MT/s       | 2         | 2.44%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 2         | 2.44%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s          | 2         | 2.44%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s          | 2         | 2.44%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s          | 2         | 2.44%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s           | 2         | 2.44%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s          | 2         | 2.44%   |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s                    | 1         | 1.22%   |
| Unknown RAM Module 8GB SODIMM DDR3                             | 1         | 1.22%   |
| Unknown RAM Module 4GB SODIMM DDR3                             | 1         | 1.22%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                  | 1         | 1.22%   |
| SK hynix RAM HMT425S6CFR6A-PB 2048MB SODIMM DDR3 1600MT/s      | 1         | 1.22%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 1.22%   |
| SK hynix RAM HMA851S6JJR6N-VK 4096MB SODIMM DDR4 2667MT/s      | 1         | 1.22%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s         | 1         | 1.22%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s        | 1         | 1.22%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s        | 1         | 1.22%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s         | 1         | 1.22%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s          | 1         | 1.22%   |
| Samsung RAM M471B5674-H0-YK0--- 4GB Chip DDR3 1600MT/s         | 1         | 1.22%   |
| Samsung RAM M471B5673FH0-CF8 2048MB SODIMM DDR3 1067MT/s       | 1         | 1.22%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s          | 1         | 1.22%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s          | 1         | 1.22%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s       | 1         | 1.22%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s       | 1         | 1.22%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s          | 1         | 1.22%   |
| Samsung RAM M471A5244CB0-CTD 4096MB Row Of Chips DDR4 2667MT/s | 1         | 1.22%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s          | 1         | 1.22%   |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s          | 1         | 1.22%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s         | 1         | 1.22%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s          | 1         | 1.22%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s          | 1         | 1.22%   |
| Patriot RAM PSD48G266681S 8GB SODIMM DDR4 2667MT/s             | 1         | 1.22%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s           | 1         | 1.22%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s           | 1         | 1.22%   |
| Micron RAM M391A1G43BB1-CRCB1 16GB SODIMM DDR4 2667MT/s        | 1         | 1.22%   |
| Micron RAM 8KTF51264HZ-1G6N1 4GB SODIMM DDR3 1600MT/s          | 1         | 1.22%   |
| Micron RAM 8ATF1G64HZ-2G6H1 8GB SODIMM DDR4 2667MT/s           | 1         | 1.22%   |
| Micron RAM 16HTF25664HY-667E1 2048MB SODIMM DDR 667MT/s        | 1         | 1.22%   |
| Kingston RAM TSB16D3LS1MNG/4G 4GB SODIMM DDR3 1600MT/s         | 1         | 1.22%   |
| Kingston RAM MSI16D3LS1KBG/8G 8192MB SODIMM DDR3 1600MT/s      | 1         | 1.22%   |
| Kingston RAM MSI16D3LS1KBG/4G 4GB SODIMM DDR3 1600MT/s         | 1         | 1.22%   |
| Kingston RAM Module 2GB SODIMM DDR2 667MT/s                    | 1         | 1.22%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s           | 1         | 1.22%   |
| Kingston RAM ACR16D3LS1KBGR/4G 4GB SODIMM DDR3 1600MT/s        | 1         | 1.22%   |
| Kingston RAM ACR16D3LFS1KBG/2G 2GB SODIMM DDR3 1600MT/s        | 1         | 1.22%   |
| Kingston RAM 99U5469-015.A00LF 2048MB SODIMM DDR3 1333MT/s     | 1         | 1.22%   |
| Kingston RAM 9905428-045.A00LF 4GB SODIMM DDR3 1333MT/s        | 1         | 1.22%   |
| Crucial RAM CT8G3S1339M.M16FP 8GB SODIMM DDR3 1334MT/s         | 1         | 1.22%   |
| Crucial RAM CT16G4SFRA32A.M16FRS 16GB SODIMM DDR4 3200MT/s     | 1         | 1.22%   |
| Crucial RAM CT16G4SFD8213.C16FBD 16GB SODIMM DDR4 2133MT/s     | 1         | 1.22%   |
| Corsair RAM Module 8192MB SODIMM DDR3 1333MT/s                 | 1         | 1.22%   |
| Corsair RAM Module 4096MB SODIMM DDR3 1333MT/s                 | 1         | 1.22%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 27        | 45.76%  |
| DDR4   | 26        | 44.07%  |
| DDR2   | 3         | 5.08%   |
| SDRAM  | 2         | 3.39%   |
| LPDDR4 | 1         | 1.69%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 55        | 94.83%  |
| Row Of Chips | 2         | 3.45%   |
| Chip         | 1         | 1.72%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 32        | 45.71%  |
| 8192  | 20        | 28.57%  |
| 2048  | 7         | 10%     |
| 16384 | 6         | 8.57%   |
| 32768 | 5         | 7.14%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 19        | 27.94%  |
| 1600    | 18        | 26.47%  |
| 1333    | 7         | 10.29%  |
| 1334    | 5         | 7.35%   |
| 3200    | 4         | 5.88%   |
| 3266    | 3         | 4.41%   |
| 667     | 3         | 4.41%   |
| 4199    | 2         | 2.94%   |
| 2133    | 2         | 2.94%   |
| Unknown | 2         | 2.94%   |
| 8400    | 1         | 1.47%   |
| 2400    | 1         | 1.47%   |
| 1067    | 1         | 1.47%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 2         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Seiko Epson L380 Series | 1         | 50%     |
| Seiko Epson L220 Series | 1         | 50%     |

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
| Chicony Electronics                    | 23        | 23.96%  |
| Microdia                               | 13        | 13.54%  |
| Realtek Semiconductor                  | 11        | 11.46%  |
| IMC Networks                           | 11        | 11.46%  |
| Sunplus Innovation Technology          | 6         | 6.25%   |
| Apple                                  | 5         | 5.21%   |
| Suyin                                  | 3         | 3.13%   |
| Quanta                                 | 3         | 3.13%   |
| Primax Electronics                     | 2         | 2.08%   |
| Luxvisions Innotech Limited            | 2         | 2.08%   |
| Lite-On Technology                     | 2         | 2.08%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 2.08%   |
| Alcor Micro                            | 2         | 2.08%   |
| Acer                                   | 2         | 2.08%   |
| Z-Star Microelectronics                | 1         | 1.04%   |
| Syntek                                 | 1         | 1.04%   |
| Microsoft                              | 1         | 1.04%   |
| Logitech                               | 1         | 1.04%   |
| LG Electronics                         | 1         | 1.04%   |
| Importek                               | 1         | 1.04%   |
| GEMBIRD                                | 1         | 1.04%   |
| Creative Technology                    | 1         | 1.04%   |
| Alpha Imaging Technology               | 1         | 1.04%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                   | 10        | 10.2%   |
| Chicony Integrated Camera                                       | 5         | 5.1%    |
| IMC Networks Integrated Camera                                  | 4         | 4.08%   |
| Apple FaceTime HD Camera                                        | 4         | 4.08%   |
| Sunplus HD WebCam                                               | 3         | 3.06%   |
| Realtek Integrated_Webcam_HD                                    | 3         | 3.06%   |
| Chicony TOSHIBA Web Camera - HD                                 | 3         | 3.06%   |
| Realtek Integrated Webcam HD                                    | 2         | 2.04%   |
| Realtek Integrated Webcam                                       | 2         | 2.04%   |
| Quanta HD WebCam                                                | 2         | 2.04%   |
| Microdia Integrated Webcam                                      | 2         | 2.04%   |
| IMC Networks USB2.0 VGA UVC WebCam                              | 2         | 2.04%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 2         | 2.04%   |
| Chicony USB 2.0 Camera                                          | 2         | 2.04%   |
| Chicony Integrated HP HD Webcam                                 | 2         | 2.04%   |
| Chicony HP Truevision HD                                        | 2         | 2.04%   |
| Z-Star Vega USB2.0 Camera                                       | 1         | 1.02%   |
| Syntek EasyCamera                                               | 1         | 1.02%   |
| Suyin TOSHIBA Web Camera - HD                                   | 1         | 1.02%   |
| Suyin HP TrueVision HD                                          | 1         | 1.02%   |
| Suyin 1.3M HD WebCam                                            | 1         | 1.02%   |
| Sunplus Laptop_Integrated_Webcam_HD                             | 1         | 1.02%   |
| Sunplus Integrated_Webcam_HD                                    | 1         | 1.02%   |
| Sunplus HP HD Webcam [Fixed]                                    | 1         | 1.02%   |
| Realtek USB Camera                                              | 1         | 1.02%   |
| Realtek Rear Camera                                             | 1         | 1.02%   |
| Realtek HP Wide Vision FHD Camera                               | 1         | 1.02%   |
| Realtek HP Truevision HD                                        | 1         | 1.02%   |
| Realtek Front Camera                                            | 1         | 1.02%   |
| Quanta HP Webcam                                                | 1         | 1.02%   |
| Primax webcam                                                   | 1         | 1.02%   |
| Primax HP HD Webcam [Fixed]                                     | 1         | 1.02%   |
| Microsoft LifeCam HD-3000                                       | 1         | 1.02%   |
| Microdia Laptop_Integrated_Webcam_HD                            | 1         | 1.02%   |
| Microdia Integrated Camera                                      | 1         | 1.02%   |
| Luxvisions Innotech Limited Integrated Camera                   | 1         | 1.02%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera             | 1         | 1.02%   |
| Logitech Webcam C925e                                           | 1         | 1.02%   |
| Lite-On Integrated Camera                                       | 1         | 1.02%   |
| Lite-On HP HD Webcam                                            | 1         | 1.02%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode)           | 1         | 1.02%   |
| Importek Laptop Integrated Webcam                               | 1         | 1.02%   |
| IMC Networks TOSHIBA Web Camera - HD                            | 1         | 1.02%   |
| IMC Networks ov9734_azurewave_camera                            | 1         | 1.02%   |
| IMC Networks Integrated Webcam                                  | 1         | 1.02%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311]               | 1         | 1.02%   |
| Creative VF0610 Live! Cam Socialize HD                          | 1         | 1.02%   |
| Chicony VGA 30fps UVC Webcam                                    | 1         | 1.02%   |
| Chicony USB2.0 HD UVC WebCam                                    | 1         | 1.02%   |
| Chicony HP TrueVision HD Camera                                 | 1         | 1.02%   |
| Chicony HP HD Webcam                                            | 1         | 1.02%   |
| Chicony HP HD Camera                                            | 1         | 1.02%   |
| Chicony HD User Facing                                          | 1         | 1.02%   |
| Chicony CNF9055 Toshiba Webcam                                  | 1         | 1.02%   |
| Chicony CKF8136                                                 | 1         | 1.02%   |
| Chicony 720p HD Camera                                          | 1         | 1.02%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 1         | 1.02%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam                | 1         | 1.02%   |
| Apple Built-in iSight [Micron]                                  | 1         | 1.02%   |
| Alpha Imaging Integrated_Webcam_8M                              | 1         | 1.02%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 10        | 52.63%  |
| Synaptics                  | 3         | 15.79%  |
| Shenzhen Goodix Technology | 2         | 10.53%  |
| STMicroelectronics         | 1         | 5.26%   |
| LighTuning Technology      | 1         | 5.26%   |
| Elan Microelectronics      | 1         | 5.26%   |
| AuthenTec                  | 1         | 5.26%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader        | 3         | 15.79%  |
| Validity Sensors VFS 5011 fingerprint sensor      | 2         | 10.53%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 2         | 10.53%  |
| Shenzhen Goodix  Fingerprint Device               | 2         | 10.53%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor | 1         | 5.26%   |
| Validity Sensors VFS491                           | 1         | 5.26%   |
| Validity Sensors VFS471 Fingerprint Reader        | 1         | 5.26%   |
| Validity Sensors Synaptics WBDI                   | 1         | 5.26%   |
| Validity Sensors Fingerprint scanner              | 1         | 5.26%   |
| STMicroelectronics Fingerprint Reader             | 1         | 5.26%   |
| LighTuning EgisTec Touch Fingerprint Sensor       | 1         | 5.26%   |
| Elan ELAN:ARM-M4                                  | 1         | 5.26%   |
| AuthenTec AES1600                                 | 1         | 5.26%   |
| Unknown                                           | 1         | 5.26%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Broadcom                   | 4         | 40%     |
| O2 Micro                   | 3         | 30%     |
| Athena Smartcard Solutions | 2         | 20%     |
| Alcor Micro                | 1         | 10%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 20%     |
| Broadcom 5880                                                                | 2         | 20%     |
| Athena Smartcard Solutions ASEDrive CCID                                     | 2         | 20%     |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 10%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 10%     |
| Broadcom 58200                                                               | 1         | 10%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 10%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 70        | 62.5%   |
| 1     | 36        | 32.14%  |
| 2     | 4         | 3.57%   |
| 3     | 2         | 1.79%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 18        | 36%     |
| Net/wireless          | 10        | 20%     |
| Graphics card         | 8         | 16%     |
| Chipcard              | 8         | 16%     |
| Multimedia controller | 2         | 4%      |
| Sound                 | 1         | 2%      |
| Net/ethernet          | 1         | 2%      |
| Firewire controller   | 1         | 2%      |
| Bluetooth             | 1         | 2%      |

