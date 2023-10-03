Zorin - Tested Hardware & Statistics (Notebooks)
------------------------------------------------

A project to collect tested hardware configurations for Zorin.

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

Total: 4601

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Toshiba       | Satellite C870-1C2          | [d9750c9040](https://linux-hardware.org/?probe=d9750c9040) | Sep 30, 2023 |
| Apple         | MacBookPro5,3               | [0669d0020d](https://linux-hardware.org/?probe=0669d0020d) | Sep 30, 2023 |
| Apple         | MacBookPro8,2               | [237492c356](https://linux-hardware.org/?probe=237492c356) | Sep 30, 2023 |
| Apple         | MacBookPro5,3               | [d249d5e114](https://linux-hardware.org/?probe=d249d5e114) | Sep 30, 2023 |
| Lenovo        | IdeaPad Slim 3 15IRU8 82... | [e9dd0291e0](https://linux-hardware.org/?probe=e9dd0291e0) | Sep 29, 2023 |
| ASUSTek       | X551MA                      | [8ba160ee59](https://linux-hardware.org/?probe=8ba160ee59) | Sep 29, 2023 |
| Lenovo        | ThinkPad R60 9461DXG        | [4f74530d68](https://linux-hardware.org/?probe=4f74530d68) | Sep 28, 2023 |
| Lenovo        | ThinkPad R60 9461DXG        | [5fb1e549ea](https://linux-hardware.org/?probe=5fb1e549ea) | Sep 28, 2023 |
| Acer          | Aspire 5736Z                | [cfd174dbe0](https://linux-hardware.org/?probe=cfd174dbe0) | Sep 28, 2023 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | [c717c1ab13](https://linux-hardware.org/?probe=c717c1ab13) | Sep 28, 2023 |
| Lenovo        | ThinkPad E14 20RA0050US     | [097539dde8](https://linux-hardware.org/?probe=097539dde8) | Sep 27, 2023 |
| Medion        | E6431 MD60112               | [f1fee9da62](https://linux-hardware.org/?probe=f1fee9da62) | Sep 27, 2023 |
| HP            | Notebook                    | [4690fda15e](https://linux-hardware.org/?probe=4690fda15e) | Sep 27, 2023 |
| Apple         | MacBookPro11,1              | [7463d4f447](https://linux-hardware.org/?probe=7463d4f447) | Sep 26, 2023 |
| Dell          | Vostro 3550                 | [f87aee7d8f](https://linux-hardware.org/?probe=f87aee7d8f) | Sep 26, 2023 |
| Dell          | Vostro 3550                 | [7214093885](https://linux-hardware.org/?probe=7214093885) | Sep 26, 2023 |
| Dell          | Inspiron 5459               | [1095c770f0](https://linux-hardware.org/?probe=1095c770f0) | Sep 26, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | [0c8a57738d](https://linux-hardware.org/?probe=0c8a57738d) | Sep 25, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | [a778013e21](https://linux-hardware.org/?probe=a778013e21) | Sep 25, 2023 |
| Intel         | W7645                       | [8a83c23785](https://linux-hardware.org/?probe=8a83c23785) | Sep 25, 2023 |
| Dell          | Inspiron 14 5410            | [863dfa9b96](https://linux-hardware.org/?probe=863dfa9b96) | Sep 25, 2023 |
| Apple         | MacBookAir6,1               | [1bee981c70](https://linux-hardware.org/?probe=1bee981c70) | Sep 25, 2023 |
| Dell          | Inspiron 3581               | [11796876dd](https://linux-hardware.org/?probe=11796876dd) | Sep 25, 2023 |
| Sony          | SVF14A15CXB                 | [cbce21a887](https://linux-hardware.org/?probe=cbce21a887) | Sep 25, 2023 |
| Alienware     | M17x                        | [5c6b700486](https://linux-hardware.org/?probe=5c6b700486) | Sep 25, 2023 |
| Samsung       | 3570R/370R/470R/450R/510... | [6d75f2f29b](https://linux-hardware.org/?probe=6d75f2f29b) | Sep 24, 2023 |
| HUAWEI        | KLVL-WXXW                   | [f2a543d0dd](https://linux-hardware.org/?probe=f2a543d0dd) | Sep 24, 2023 |
| Dell          | XPS 13 9360                 | [6897fc6f5a](https://linux-hardware.org/?probe=6897fc6f5a) | Sep 23, 2023 |
| ASUSTek       | K50IJ                       | [02a39de387](https://linux-hardware.org/?probe=02a39de387) | Sep 23, 2023 |
| Lenovo        | ThinkPad E575 20H8000HUS    | [8b5a2354c5](https://linux-hardware.org/?probe=8b5a2354c5) | Sep 23, 2023 |
| Acer          | Aspire A514-54              | [c74511d498](https://linux-hardware.org/?probe=c74511d498) | Sep 22, 2023 |
| Toshiba       | Satellite Pro R40-D         | [d33d1b7b77](https://linux-hardware.org/?probe=d33d1b7b77) | Sep 22, 2023 |
| Primux Tec... | Primux_1406F_W10            | [a1911e4e9a](https://linux-hardware.org/?probe=a1911e4e9a) | Sep 22, 2023 |
| Primux Tec... | Primux_1406F_W10            | [c267e8d9a3](https://linux-hardware.org/?probe=c267e8d9a3) | Sep 22, 2023 |
| HP            | 250 G7 Notebook PC          | [cc25c24fa5](https://linux-hardware.org/?probe=cc25c24fa5) | Sep 21, 2023 |
| HP            | 255 G8 Notebook PC          | [d92a4fb2af](https://linux-hardware.org/?probe=d92a4fb2af) | Sep 21, 2023 |
| Dell          | Inspiron 3576               | [a76faead17](https://linux-hardware.org/?probe=a76faead17) | Sep 21, 2023 |
| Acer          | TravelMate P246-MG          | [197b2c18c7](https://linux-hardware.org/?probe=197b2c18c7) | Sep 21, 2023 |
| Acer          | Aspire VN7-572G             | [8936ef0637](https://linux-hardware.org/?probe=8936ef0637) | Sep 21, 2023 |
| Lenovo        | ThinkPad T570 20HAS1PC00    | [218325e9e3](https://linux-hardware.org/?probe=218325e9e3) | Sep 21, 2023 |
| Lenovo        | ThinkPad T560 20FJS2BX00    | [85a0203a02](https://linux-hardware.org/?probe=85a0203a02) | Sep 20, 2023 |
| Lenovo        | ThinkPad T560 20FJS2BX00    | [c96d3bf498](https://linux-hardware.org/?probe=c96d3bf498) | Sep 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [162a680d7d](https://linux-hardware.org/?probe=162a680d7d) | Sep 19, 2023 |
| Acer          | Aspire 5750                 | [9fb8b99e70](https://linux-hardware.org/?probe=9fb8b99e70) | Sep 19, 2023 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [ca70cb035f](https://linux-hardware.org/?probe=ca70cb035f) | Sep 19, 2023 |
| HP            | Pavilion dv7                | [2bbc187582](https://linux-hardware.org/?probe=2bbc187582) | Sep 19, 2023 |
| HP            | Laptop 15-ef1xxx            | [5ec304bdb6](https://linux-hardware.org/?probe=5ec304bdb6) | Sep 19, 2023 |
| HP            | Laptop 15-fc0xxx            | [bb3c1bf2b9](https://linux-hardware.org/?probe=bb3c1bf2b9) | Sep 18, 2023 |
| HP            | EliteBook 745 G5            | [d03b8c1860](https://linux-hardware.org/?probe=d03b8c1860) | Sep 18, 2023 |
| HP            | Laptop 15-fc0xxx            | [4e845095f4](https://linux-hardware.org/?probe=4e845095f4) | Sep 18, 2023 |
| Dell          | XPS 13 9370                 | [002401cab6](https://linux-hardware.org/?probe=002401cab6) | Sep 18, 2023 |
| Hometech      | Ultra Tab 8W                | [065988c338](https://linux-hardware.org/?probe=065988c338) | Sep 17, 2023 |
| Hometech      | Ultra Tab 8W                | [1a9e79b92e](https://linux-hardware.org/?probe=1a9e79b92e) | Sep 17, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | [ef3516c115](https://linux-hardware.org/?probe=ef3516c115) | Sep 17, 2023 |
| Acer          | Aspire 5750                 | [e639402c30](https://linux-hardware.org/?probe=e639402c30) | Sep 17, 2023 |
| Apple         | MacBook4,1                  | [3774dfea8e](https://linux-hardware.org/?probe=3774dfea8e) | Sep 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [87f26cde55](https://linux-hardware.org/?probe=87f26cde55) | Sep 16, 2023 |
| HP            | 250 G7 Notebook PC          | [72503b214c](https://linux-hardware.org/?probe=72503b214c) | Sep 16, 2023 |
| Acer          | Aspire 5755G                | [16c14700d3](https://linux-hardware.org/?probe=16c14700d3) | Sep 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [00fd2287c0](https://linux-hardware.org/?probe=00fd2287c0) | Sep 16, 2023 |
| Apple         | MacBookPro3,1               | [f6be487f38](https://linux-hardware.org/?probe=f6be487f38) | Sep 16, 2023 |
| ASUSTek       | K54C                        | [23a000c4d4](https://linux-hardware.org/?probe=23a000c4d4) | Sep 16, 2023 |
| Itautec       | Infoway                     | [d4a8bc6420](https://linux-hardware.org/?probe=d4a8bc6420) | Sep 14, 2023 |
| Acer          | Aspire 5735                 | [9d3ceb6624](https://linux-hardware.org/?probe=9d3ceb6624) | Sep 14, 2023 |
| HP            | Notebook                    | [29f1834722](https://linux-hardware.org/?probe=29f1834722) | Sep 14, 2023 |
| MSI           | Bravo 15 A4DDR              | [bba9e61120](https://linux-hardware.org/?probe=bba9e61120) | Sep 13, 2023 |
| Acer          | Aspire 5750ZG               | [c9ce4cde54](https://linux-hardware.org/?probe=c9ce4cde54) | Sep 13, 2023 |
| Dell          | Inspiron 5590               | [32b69241bf](https://linux-hardware.org/?probe=32b69241bf) | Sep 13, 2023 |
| Sony          | VPCEB1E1E                   | [cbd095ee01](https://linux-hardware.org/?probe=cbd095ee01) | Sep 12, 2023 |
| Acer          | Aspire 5750ZG               | [9029730ffb](https://linux-hardware.org/?probe=9029730ffb) | Sep 12, 2023 |
| Acer          | Aspire A514-54              | [8ddb560fdc](https://linux-hardware.org/?probe=8ddb560fdc) | Sep 12, 2023 |
| Apple         | MacBookPro8,2               | [5358fa25ef](https://linux-hardware.org/?probe=5358fa25ef) | Sep 12, 2023 |
| Dell          | Inspiron 5748               | [21baf66690](https://linux-hardware.org/?probe=21baf66690) | Sep 11, 2023 |
| HP            | Pavilion dv7                | [e7c7395c7b](https://linux-hardware.org/?probe=e7c7395c7b) | Sep 11, 2023 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | [26fc33cb75](https://linux-hardware.org/?probe=26fc33cb75) | Sep 10, 2023 |
| Dell          | Latitude E5430 non-vPro     | [b211a425b2](https://linux-hardware.org/?probe=b211a425b2) | Sep 10, 2023 |
| ASUSTek       | X541UA                      | [a8184365b8](https://linux-hardware.org/?probe=a8184365b8) | Sep 10, 2023 |
| Lenovo        | V110-14IAP 80TF             | [3ee6c9a460](https://linux-hardware.org/?probe=3ee6c9a460) | Sep 09, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [382cd978ab](https://linux-hardware.org/?probe=382cd978ab) | Sep 08, 2023 |
| Lenovo        | ThinkPad T430 2349H2G       | [1d9d7c7f78](https://linux-hardware.org/?probe=1d9d7c7f78) | Sep 08, 2023 |
| HP            | 240 G8 Notebook PC          | [62735c1cd9](https://linux-hardware.org/?probe=62735c1cd9) | Sep 07, 2023 |
| HP            | Laptop 14-dq1xxx            | [125a7f7c0d](https://linux-hardware.org/?probe=125a7f7c0d) | Sep 07, 2023 |
| Dell          | Inspiron 5559               | [0428af4d14](https://linux-hardware.org/?probe=0428af4d14) | Sep 06, 2023 |
| HP            | ProBook 650 G5              | [5e6e5cd047](https://linux-hardware.org/?probe=5e6e5cd047) | Sep 06, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [0fdeca1313](https://linux-hardware.org/?probe=0fdeca1313) | Sep 06, 2023 |
| Toshiba       | Satellite A210              | [54f5fb9c03](https://linux-hardware.org/?probe=54f5fb9c03) | Sep 06, 2023 |
| Framework     | Laptop                      | [bd2852cd9e](https://linux-hardware.org/?probe=bd2852cd9e) | Sep 05, 2023 |
| Toshiba       | Satellite C70D-A            | [36070747fd](https://linux-hardware.org/?probe=36070747fd) | Sep 04, 2023 |
| Apple         | MacBookPro8,2               | [371c148953](https://linux-hardware.org/?probe=371c148953) | Sep 04, 2023 |
| Dell          | Latitude E6530              | [e1aa22b8b9](https://linux-hardware.org/?probe=e1aa22b8b9) | Sep 04, 2023 |
| Dell          | G15 5511                    | [e6afc56020](https://linux-hardware.org/?probe=e6afc56020) | Sep 03, 2023 |
| Lenovo        | Legion S7 16IAH7 82TF       | [f4c15b0551](https://linux-hardware.org/?probe=f4c15b0551) | Sep 03, 2023 |
| Toshiba       | Satellite L50-A-1DL         | [d46487843e](https://linux-hardware.org/?probe=d46487843e) | Sep 03, 2023 |
| Dell          | Vostro 14-3468              | [2f75949c09](https://linux-hardware.org/?probe=2f75949c09) | Sep 03, 2023 |
| Apple         | MacBookPro16,2              | [9ab1a9731d](https://linux-hardware.org/?probe=9ab1a9731d) | Sep 03, 2023 |
| Apple         | MacBookPro16,2              | [78d7ccad98](https://linux-hardware.org/?probe=78d7ccad98) | Sep 02, 2023 |
| HP            | EliteBook 840 G5            | [b2b0d3e018](https://linux-hardware.org/?probe=b2b0d3e018) | Sep 02, 2023 |
| Gigabyte      | G5 KF                       | [b38cdf7987](https://linux-hardware.org/?probe=b38cdf7987) | Sep 01, 2023 |
| Gigabyte      | G5 KF                       | [3eef6bf0d1](https://linux-hardware.org/?probe=3eef6bf0d1) | Sep 01, 2023 |
| Dell          | Latitude 5400               | [dee2becb07](https://linux-hardware.org/?probe=dee2becb07) | Sep 01, 2023 |
| Lenovo        | ThinkPad S5-S540 20B3006... | [e33b222d6c](https://linux-hardware.org/?probe=e33b222d6c) | Sep 01, 2023 |
| HP            | ProBook 4740s               | [0ab7fe639e](https://linux-hardware.org/?probe=0ab7fe639e) | Sep 01, 2023 |
| HP            | EliteBook 2570p             | [436e4af3ce](https://linux-hardware.org/?probe=436e4af3ce) | Aug 31, 2023 |
| HP            | 15                          | [39567282e3](https://linux-hardware.org/?probe=39567282e3) | Aug 31, 2023 |
| HP            | Pavilion dv4                | [c84d5215be](https://linux-hardware.org/?probe=c84d5215be) | Aug 30, 2023 |
| Sony          | VPCEE23FX                   | [65714e4d48](https://linux-hardware.org/?probe=65714e4d48) | Aug 30, 2023 |
| Apple         | MacBookPro11,5              | [643e8194ea](https://linux-hardware.org/?probe=643e8194ea) | Aug 30, 2023 |
| Dell          | Venue 11 Pro 5130           | [38c58406bc](https://linux-hardware.org/?probe=38c58406bc) | Aug 29, 2023 |
| ASUSTek       | K93SV                       | [01701d7ab0](https://linux-hardware.org/?probe=01701d7ab0) | Aug 29, 2023 |
| ASUSTek       | K93SV                       | [6da5e2d119](https://linux-hardware.org/?probe=6da5e2d119) | Aug 29, 2023 |
| Dell          | Precision 7710              | [9b92626f63](https://linux-hardware.org/?probe=9b92626f63) | Aug 29, 2023 |
| Acer          | Acadia V1.45                | [4bc36b4d27](https://linux-hardware.org/?probe=4bc36b4d27) | Aug 29, 2023 |
| HP            | Laptop 14-dq1xxx            | [8e13da67ed](https://linux-hardware.org/?probe=8e13da67ed) | Aug 28, 2023 |
| Lenovo        | Yoga 3 14 80JH              | [5268d75df2](https://linux-hardware.org/?probe=5268d75df2) | Aug 28, 2023 |
| Lenovo        | ThinkPad P51s W10DG 20JY... | [4c01a3be17](https://linux-hardware.org/?probe=4c01a3be17) | Aug 28, 2023 |
| HP            | Laptop 14-dk1xxx            | [bdd515fe27](https://linux-hardware.org/?probe=bdd515fe27) | Aug 28, 2023 |
| Lenovo        | ThinkPad P51s W10DG 20JY... | [783bbb68e6](https://linux-hardware.org/?probe=783bbb68e6) | Aug 27, 2023 |
| TERRA         | TERRAPC                     | [2031fd343b](https://linux-hardware.org/?probe=2031fd343b) | Aug 27, 2023 |
| Dell          | Latitude E5470              | [b1efa66e79](https://linux-hardware.org/?probe=b1efa66e79) | Aug 27, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [7e9c9debdf](https://linux-hardware.org/?probe=7e9c9debdf) | Aug 26, 2023 |
| Chuwi         | GemiBook Pro                | [06f19f4198](https://linux-hardware.org/?probe=06f19f4198) | Aug 26, 2023 |
| HP            | Pavilion dv7                | [6fbf874054](https://linux-hardware.org/?probe=6fbf874054) | Aug 26, 2023 |
| Acer          | Aspire A315-56              | [e212f5bc28](https://linux-hardware.org/?probe=e212f5bc28) | Aug 25, 2023 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | [7726b35ef6](https://linux-hardware.org/?probe=7726b35ef6) | Aug 25, 2023 |
| Google        | Rammus                      | [28554e7ce5](https://linux-hardware.org/?probe=28554e7ce5) | Aug 25, 2023 |
| HP            | ProBook 640 G4              | [3b75cf22fb](https://linux-hardware.org/?probe=3b75cf22fb) | Aug 25, 2023 |
| TERRA         | TERRAPC                     | [b33c6ce6e8](https://linux-hardware.org/?probe=b33c6ce6e8) | Aug 24, 2023 |
| Lenovo        | ThinkPad Edge 25453BG       | [188af952b0](https://linux-hardware.org/?probe=188af952b0) | Aug 24, 2023 |
| HP            | ProBook 4740s               | [f9e2a275da](https://linux-hardware.org/?probe=f9e2a275da) | Aug 24, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [64859dd75d](https://linux-hardware.org/?probe=64859dd75d) | Aug 24, 2023 |
| ASUSTek       | X756UQ                      | [0ff5520460](https://linux-hardware.org/?probe=0ff5520460) | Aug 22, 2023 |
| Lenovo        | ThinkPad P51 20HJS3MY00     | [010dac0caa](https://linux-hardware.org/?probe=010dac0caa) | Aug 22, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [2a05992a61](https://linux-hardware.org/?probe=2a05992a61) | Aug 21, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | [a440d57d28](https://linux-hardware.org/?probe=a440d57d28) | Aug 21, 2023 |
| Dell          | Precision M4700             | [9ec95d5a4d](https://linux-hardware.org/?probe=9ec95d5a4d) | Aug 21, 2023 |
| HP            | Notebook                    | [5b7ff7f278](https://linux-hardware.org/?probe=5b7ff7f278) | Aug 20, 2023 |
| Apple         | MacBookPro8,1               | [41edd1a16e](https://linux-hardware.org/?probe=41edd1a16e) | Aug 20, 2023 |
| Dell          | Latitude 3350               | [e86ce20d6d](https://linux-hardware.org/?probe=e86ce20d6d) | Aug 20, 2023 |
| Lenovo        | Unknown                     | [fbbadac782](https://linux-hardware.org/?probe=fbbadac782) | Aug 20, 2023 |
| Lenovo        | ThinkPad Edge 0578A66       | [6b3703818a](https://linux-hardware.org/?probe=6b3703818a) | Aug 20, 2023 |
| Alienware     | 17                          | [9e7015d530](https://linux-hardware.org/?probe=9e7015d530) | Aug 20, 2023 |
| Apple         | MacBookPro4,1               | [1c57edc329](https://linux-hardware.org/?probe=1c57edc329) | Aug 19, 2023 |
| Dell          | Latitude E5470              | [ca95c6f5bc](https://linux-hardware.org/?probe=ca95c6f5bc) | Aug 19, 2023 |
| Sony          | VPCF13Z1E                   | [98c9e71be9](https://linux-hardware.org/?probe=98c9e71be9) | Aug 19, 2023 |
| Apple         | MacBookPro5,2               | [2c20d038ca](https://linux-hardware.org/?probe=2c20d038ca) | Aug 19, 2023 |
| Acer          | Swift SF514-52T             | [9cd2857c01](https://linux-hardware.org/?probe=9cd2857c01) | Aug 18, 2023 |
| ASUSTek       | X550ZA                      | [7f23195701](https://linux-hardware.org/?probe=7f23195701) | Aug 18, 2023 |
| Lenovo        | Flex 2-15 20405             | [77942ee5db](https://linux-hardware.org/?probe=77942ee5db) | Aug 18, 2023 |
| Acer          | Aspire 5755G                | [720c3bfa88](https://linux-hardware.org/?probe=720c3bfa88) | Aug 18, 2023 |
| Lenovo        | G40-30 80FY                 | [d14c477dc9](https://linux-hardware.org/?probe=d14c477dc9) | Aug 18, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | [04ebdc3ec0](https://linux-hardware.org/?probe=04ebdc3ec0) | Aug 18, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [7092a32ce5](https://linux-hardware.org/?probe=7092a32ce5) | Aug 17, 2023 |
| Dell          | G3 3579                     | [58866ca1fb](https://linux-hardware.org/?probe=58866ca1fb) | Aug 17, 2023 |
| TAGTech       | TAGITOP-UNI C               | [d7402c2c8d](https://linux-hardware.org/?probe=d7402c2c8d) | Aug 17, 2023 |
| TAGTech       | TAGITOP-UNI C               | [1cccdef7f4](https://linux-hardware.org/?probe=1cccdef7f4) | Aug 17, 2023 |
| Google        | Coral                       | [f8ed9b3bda](https://linux-hardware.org/?probe=f8ed9b3bda) | Aug 17, 2023 |
| Lenovo        | ThinkPad T480 20L5S04F00    | [7eb670d219](https://linux-hardware.org/?probe=7eb670d219) | Aug 17, 2023 |
| Lenovo        | G40-30 80FY                 | [6574b3e96d](https://linux-hardware.org/?probe=6574b3e96d) | Aug 16, 2023 |
| Apple         | MacBookPro5,2               | [86c85e57c2](https://linux-hardware.org/?probe=86c85e57c2) | Aug 16, 2023 |
| HP            | OMEN by Laptop              | [b31bf50c6e](https://linux-hardware.org/?probe=b31bf50c6e) | Aug 16, 2023 |
| Dell          | Latitude D630               | [878b00d959](https://linux-hardware.org/?probe=878b00d959) | Aug 15, 2023 |
| HP            | 15                          | [645730bff3](https://linux-hardware.org/?probe=645730bff3) | Aug 15, 2023 |
| HP            | 15                          | [08fc74cb7b](https://linux-hardware.org/?probe=08fc74cb7b) | Aug 15, 2023 |
| Sony          | VGN-SR19VN                  | [7adc151adb](https://linux-hardware.org/?probe=7adc151adb) | Aug 15, 2023 |
| Lenovo        | ThinkPad T510 43842RG       | [9b2f268192](https://linux-hardware.org/?probe=9b2f268192) | Aug 15, 2023 |
| Medion        | E15301                      | [e42771be29](https://linux-hardware.org/?probe=e42771be29) | Aug 14, 2023 |
| HP            | Laptop 14-dq1xxx            | [102a6b136f](https://linux-hardware.org/?probe=102a6b136f) | Aug 14, 2023 |
| Lenovo        | Legion R9000P2021H 82JQ     | [777c4f7fb8](https://linux-hardware.org/?probe=777c4f7fb8) | Aug 13, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [c692882ce4](https://linux-hardware.org/?probe=c692882ce4) | Aug 13, 2023 |
| AMI           | Unknown                     | [326999bd6b](https://linux-hardware.org/?probe=326999bd6b) | Aug 12, 2023 |
| AMI           | Unknown                     | [614b443c5c](https://linux-hardware.org/?probe=614b443c5c) | Aug 12, 2023 |
| HP            | 350 G2                      | [f0fa8865d3](https://linux-hardware.org/?probe=f0fa8865d3) | Aug 12, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [71f554fd2c](https://linux-hardware.org/?probe=71f554fd2c) | Aug 12, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [edd42a9a6d](https://linux-hardware.org/?probe=edd42a9a6d) | Aug 12, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | [5ba59f878a](https://linux-hardware.org/?probe=5ba59f878a) | Aug 12, 2023 |
| Acer          | One Z1402                   | [9fd6a2d41b](https://linux-hardware.org/?probe=9fd6a2d41b) | Aug 12, 2023 |
| Unknown       | Unknown                     | [b68d99fd89](https://linux-hardware.org/?probe=b68d99fd89) | Aug 11, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [48a0f64b34](https://linux-hardware.org/?probe=48a0f64b34) | Aug 11, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [a708832571](https://linux-hardware.org/?probe=a708832571) | Aug 11, 2023 |
| HP            | 350 G2                      | [dde52cb361](https://linux-hardware.org/?probe=dde52cb361) | Aug 10, 2023 |
| Clevo         | W251EFQ/W270EFQ             | [cde80ecaf6](https://linux-hardware.org/?probe=cde80ecaf6) | Aug 10, 2023 |
| HP            | ProBook 450 G6              | [c205f19d5e](https://linux-hardware.org/?probe=c205f19d5e) | Aug 09, 2023 |
| HP            | 350 G2                      | [3b79bb8a69](https://linux-hardware.org/?probe=3b79bb8a69) | Aug 09, 2023 |
| HP            | Presario CQ56               | [cf373b9083](https://linux-hardware.org/?probe=cf373b9083) | Aug 09, 2023 |
| HP            | Laptop 14-dk1xxx            | [7c59be984f](https://linux-hardware.org/?probe=7c59be984f) | Aug 09, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [03a4763a96](https://linux-hardware.org/?probe=03a4763a96) | Aug 08, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [de86921bce](https://linux-hardware.org/?probe=de86921bce) | Aug 08, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [c90663d505](https://linux-hardware.org/?probe=c90663d505) | Aug 08, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [87ee840e89](https://linux-hardware.org/?probe=87ee840e89) | Aug 07, 2023 |
| LG Electro... | 14Z90N-V.AA78B              | [af79c7f5f5](https://linux-hardware.org/?probe=af79c7f5f5) | Aug 07, 2023 |
| Apple         | MacBookPro14,1              | [72a4a0eed2](https://linux-hardware.org/?probe=72a4a0eed2) | Aug 06, 2023 |
| ASUSTek       | X405UA                      | [97acf73dea](https://linux-hardware.org/?probe=97acf73dea) | Aug 06, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [c40308638c](https://linux-hardware.org/?probe=c40308638c) | Aug 05, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 ARP23 Ver.1... | [8b6db0bfbb](https://linux-hardware.org/?probe=8b6db0bfbb) | Aug 05, 2023 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | [dbbf788e9d](https://linux-hardware.org/?probe=dbbf788e9d) | Aug 05, 2023 |
| HP            | EliteBook 8440p             | [5f0be846f0](https://linux-hardware.org/?probe=5f0be846f0) | Aug 05, 2023 |
| Dell          | Venue 11 Pro 7140           | [7188a418fc](https://linux-hardware.org/?probe=7188a418fc) | Aug 05, 2023 |
| HP            | EliteBook 8460p             | [db336dcf75](https://linux-hardware.org/?probe=db336dcf75) | Aug 05, 2023 |
| Itautec       | Infoway                     | [1708f5baae](https://linux-hardware.org/?probe=1708f5baae) | Aug 04, 2023 |
| GPD           | G1621-02                    | [d7361e9896](https://linux-hardware.org/?probe=d7361e9896) | Aug 04, 2023 |
| Apple         | MacBook8,1                  | [cf6d77d650](https://linux-hardware.org/?probe=cf6d77d650) | Aug 04, 2023 |
| Dell          | Latitude 7490               | [955c961132](https://linux-hardware.org/?probe=955c961132) | Aug 04, 2023 |
| Apple         | MacBookPro8,1               | [61cb65a2e9](https://linux-hardware.org/?probe=61cb65a2e9) | Aug 04, 2023 |
| Dell          | Inspiron 3531               | [f011e5c6cf](https://linux-hardware.org/?probe=f011e5c6cf) | Aug 03, 2023 |
| Notebook      | NJ50_70CU                   | [59cd10f50e](https://linux-hardware.org/?probe=59cd10f50e) | Aug 02, 2023 |
| Acer          | Aspire M3-581G              | [82814fbe1e](https://linux-hardware.org/?probe=82814fbe1e) | Aug 02, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [37fe1d55f8](https://linux-hardware.org/?probe=37fe1d55f8) | Aug 02, 2023 |
| HP            | Pavilion dv7                | [bd9bc8e7a6](https://linux-hardware.org/?probe=bd9bc8e7a6) | Aug 02, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [ee5b34b232](https://linux-hardware.org/?probe=ee5b34b232) | Aug 02, 2023 |
| ASUSTek       | K54C                        | [f4fcf79e7e](https://linux-hardware.org/?probe=f4fcf79e7e) | Aug 02, 2023 |
| Dell          | Inspiron 5577               | [1204832e26](https://linux-hardware.org/?probe=1204832e26) | Aug 01, 2023 |
| Dell          | Inspiron 5577               | [219723a17d](https://linux-hardware.org/?probe=219723a17d) | Aug 01, 2023 |
| Dell          | Latitude E5470              | [3be826cec4](https://linux-hardware.org/?probe=3be826cec4) | Aug 01, 2023 |
| HP            | Stream Laptop 14-cb1XX      | [957e1805d3](https://linux-hardware.org/?probe=957e1805d3) | Aug 01, 2023 |
| HP            | Stream Laptop 14-cb1XX      | [a522e7336c](https://linux-hardware.org/?probe=a522e7336c) | Aug 01, 2023 |
| MSI           | GE72MVR 7RG                 | [d935650def](https://linux-hardware.org/?probe=d935650def) | Jul 31, 2023 |
| Dell          | Inspiron 3421               | [d1651e3e43](https://linux-hardware.org/?probe=d1651e3e43) | Jul 31, 2023 |
| Chuwi         | GemiBook Pro                | [d4efd6692b](https://linux-hardware.org/?probe=d4efd6692b) | Jul 30, 2023 |
| Apple         | MacBookPro4,1               | [eedbe7eb59](https://linux-hardware.org/?probe=eedbe7eb59) | Jul 30, 2023 |
| Apple         | MacBookAir5,2               | [1a77aeef9d](https://linux-hardware.org/?probe=1a77aeef9d) | Jul 30, 2023 |
| Apple         | MacBookAir5,2               | [a6e35103c8](https://linux-hardware.org/?probe=a6e35103c8) | Jul 30, 2023 |
| Sony          | VPCF13Z1E                   | [e52969e6a8](https://linux-hardware.org/?probe=e52969e6a8) | Jul 30, 2023 |
| HP            | 530                         | [3d05ea6c86](https://linux-hardware.org/?probe=3d05ea6c86) | Jul 30, 2023 |
| MSI           | GS73VR 7RF                  | [9df7170f38](https://linux-hardware.org/?probe=9df7170f38) | Jul 29, 2023 |
| HP            | Pavilion dv4                | [47e9cba85c](https://linux-hardware.org/?probe=47e9cba85c) | Jul 29, 2023 |
| Dell          | XPS 13 9350                 | [472c0bf0b0](https://linux-hardware.org/?probe=472c0bf0b0) | Jul 29, 2023 |
| Dell          | XPS 13 9350                 | [2da43364f8](https://linux-hardware.org/?probe=2da43364f8) | Jul 29, 2023 |
| ASUSTek       | K53U                        | [c1b84117db](https://linux-hardware.org/?probe=c1b84117db) | Jul 29, 2023 |
| HP            | Pavilion 15                 | [df29d1164c](https://linux-hardware.org/?probe=df29d1164c) | Jul 29, 2023 |
| HP            | Pavilion 15                 | [804d28484b](https://linux-hardware.org/?probe=804d28484b) | Jul 29, 2023 |
| HP            | ZBook 15 G5                 | [dfe51162d1](https://linux-hardware.org/?probe=dfe51162d1) | Jul 29, 2023 |
| HP            | Pavilion g7                 | [18eb2a894b](https://linux-hardware.org/?probe=18eb2a894b) | Jul 29, 2023 |
| HP            | ZBook 15 G5                 | [8996d2d4fd](https://linux-hardware.org/?probe=8996d2d4fd) | Jul 28, 2023 |
| Google        | Edgar                       | [7e19b1e507](https://linux-hardware.org/?probe=7e19b1e507) | Jul 28, 2023 |
| ASUSTek       | K50IJ                       | [7e30723b3b](https://linux-hardware.org/?probe=7e30723b3b) | Jul 28, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [9e892612ab](https://linux-hardware.org/?probe=9e892612ab) | Jul 28, 2023 |
| HP            | EliteBook 8560p             | [b7ce548e5b](https://linux-hardware.org/?probe=b7ce548e5b) | Jul 27, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [0a1ef2aa5b](https://linux-hardware.org/?probe=0a1ef2aa5b) | Jul 27, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [d4914d5e5d](https://linux-hardware.org/?probe=d4914d5e5d) | Jul 27, 2023 |
| Sony          | VPCF13Z1E                   | [5022f7359c](https://linux-hardware.org/?probe=5022f7359c) | Jul 26, 2023 |
| Apple         | MacBookPro12,1              | [45bc8cd978](https://linux-hardware.org/?probe=45bc8cd978) | Jul 26, 2023 |
| Sony          | VPCF13Z1E                   | [f5290b8791](https://linux-hardware.org/?probe=f5290b8791) | Jul 25, 2023 |
| Sony          | VPCF13Z1E                   | [99aacf2d95](https://linux-hardware.org/?probe=99aacf2d95) | Jul 25, 2023 |
| Dell          | Vostro 1500                 | [c57ac4da0a](https://linux-hardware.org/?probe=c57ac4da0a) | Jul 25, 2023 |
| Acer          | TravelMate B113             | [b6fdce48b3](https://linux-hardware.org/?probe=b6fdce48b3) | Jul 25, 2023 |
| Toshiba       | QOSMIO X770                 | [7eda84257a](https://linux-hardware.org/?probe=7eda84257a) | Jul 25, 2023 |
| Dell          | Inspiron 3721               | [a0874e626b](https://linux-hardware.org/?probe=a0874e626b) | Jul 24, 2023 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [c16c981a88](https://linux-hardware.org/?probe=c16c981a88) | Jul 24, 2023 |
| Lenovo        | ThinkPad E15 20RD0011GE     | [8ca6d932b3](https://linux-hardware.org/?probe=8ca6d932b3) | Jul 24, 2023 |
| OEM           | Unknown                     | [a45e07b803](https://linux-hardware.org/?probe=a45e07b803) | Jul 23, 2023 |
| HP            | Laptop 15s-eq2xxx           | [35d95135f4](https://linux-hardware.org/?probe=35d95135f4) | Jul 23, 2023 |
| HP            | ProBook 640 G1              | [de254aad44](https://linux-hardware.org/?probe=de254aad44) | Jul 23, 2023 |
| Microtech     | ebookPro                    | [4427543f1a](https://linux-hardware.org/?probe=4427543f1a) | Jul 23, 2023 |
| Dell          | Latitude E6400              | [77a598aa4d](https://linux-hardware.org/?probe=77a598aa4d) | Jul 23, 2023 |
| Acer          | AO756                       | [23e3fc369f](https://linux-hardware.org/?probe=23e3fc369f) | Jul 23, 2023 |
| Apple         | MacBookAir7,2               | [c271fa70b8](https://linux-hardware.org/?probe=c271fa70b8) | Jul 23, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [19356a725e](https://linux-hardware.org/?probe=19356a725e) | Jul 22, 2023 |
| HP            | Pavilion dv4                | [4854c4b18c](https://linux-hardware.org/?probe=4854c4b18c) | Jul 22, 2023 |
| HP            | EliteBook 820 G4            | [3051483589](https://linux-hardware.org/?probe=3051483589) | Jul 22, 2023 |
| Medion        | E15301                      | [e20403ff58](https://linux-hardware.org/?probe=e20403ff58) | Jul 22, 2023 |
| Toshiba       | Satellite L50-B             | [5e7da1cf33](https://linux-hardware.org/?probe=5e7da1cf33) | Jul 22, 2023 |
| Acer          | Nitro AN515-44              | [306d51185f](https://linux-hardware.org/?probe=306d51185f) | Jul 21, 2023 |
| HP            | Compaq Presario CQ50        | [1316c533a8](https://linux-hardware.org/?probe=1316c533a8) | Jul 21, 2023 |
| AMI           | Cherry Trail CR             | [42d75ac45a](https://linux-hardware.org/?probe=42d75ac45a) | Jul 21, 2023 |
| HP            | EliteBook 820 G4            | [c85c21d42e](https://linux-hardware.org/?probe=c85c21d42e) | Jul 21, 2023 |
| Dell          | Latitude E6440              | [b60d8ab453](https://linux-hardware.org/?probe=b60d8ab453) | Jul 21, 2023 |
| Dell          | Vostro 1500                 | [0c4f8fe4d2](https://linux-hardware.org/?probe=0c4f8fe4d2) | Jul 20, 2023 |
| Dell          | Latitude 3520               | [7037e164fd](https://linux-hardware.org/?probe=7037e164fd) | Jul 20, 2023 |
| HP            | 15                          | [36b4035b57](https://linux-hardware.org/?probe=36b4035b57) | Jul 20, 2023 |
| Dell          | Inspiron 3501               | [71f9656ab2](https://linux-hardware.org/?probe=71f9656ab2) | Jul 19, 2023 |
| HP            | EliteBook 2570p             | [854bbb5dee](https://linux-hardware.org/?probe=854bbb5dee) | Jul 19, 2023 |
| HP            | 15                          | [0eeb522bec](https://linux-hardware.org/?probe=0eeb522bec) | Jul 19, 2023 |
| HP            | EliteBook 2570p             | [205b94b373](https://linux-hardware.org/?probe=205b94b373) | Jul 19, 2023 |
| Sony          | VPCEE23FX                   | [2cb9bf9d50](https://linux-hardware.org/?probe=2cb9bf9d50) | Jul 18, 2023 |
| Positivo      | Mobile                      | [1a6243fc5d](https://linux-hardware.org/?probe=1a6243fc5d) | Jul 18, 2023 |
| Positivo      | Mobile                      | [0c194a9d1d](https://linux-hardware.org/?probe=0c194a9d1d) | Jul 18, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [9be017a8a3](https://linux-hardware.org/?probe=9be017a8a3) | Jul 16, 2023 |
| Dell          | Inspiron 3421               | [71c4faf60f](https://linux-hardware.org/?probe=71c4faf60f) | Jul 16, 2023 |
| Dell          | Inspiron 5537               | [428df654fb](https://linux-hardware.org/?probe=428df654fb) | Jul 16, 2023 |
| Dell          | Inspiron 3531               | [0e7f83761f](https://linux-hardware.org/?probe=0e7f83761f) | Jul 15, 2023 |
| Dell          | Inspiron 3531               | [d73dcbb938](https://linux-hardware.org/?probe=d73dcbb938) | Jul 15, 2023 |
| Dell          | Latitude E4300              | [a9e8fb7884](https://linux-hardware.org/?probe=a9e8fb7884) | Jul 15, 2023 |
| Unknown       | SLR-0308                    | [8626e36716](https://linux-hardware.org/?probe=8626e36716) | Jul 15, 2023 |
| Alienware     | M11xR3                      | [9397339221](https://linux-hardware.org/?probe=9397339221) | Jul 14, 2023 |
| HUAWEI        | RLEF-XX                     | [23793e7d9c](https://linux-hardware.org/?probe=23793e7d9c) | Jul 14, 2023 |
| HP            | 15                          | [215a87518e](https://linux-hardware.org/?probe=215a87518e) | Jul 13, 2023 |
| Apple         | MacBookPro9,2               | [34fe8ff1ad](https://linux-hardware.org/?probe=34fe8ff1ad) | Jul 13, 2023 |
| Apple         | MacBookPro9,2               | [a3d301a82a](https://linux-hardware.org/?probe=a3d301a82a) | Jul 13, 2023 |
| Lenovo        | IdeaPad Creator 5 15IMH0... | [56093a48aa](https://linux-hardware.org/?probe=56093a48aa) | Jul 13, 2023 |
| HP            | Pavilion dv7                | [b2e0e73adc](https://linux-hardware.org/?probe=b2e0e73adc) | Jul 13, 2023 |
| Apple         | MacBookPro9,2               | [9cab0f6446](https://linux-hardware.org/?probe=9cab0f6446) | Jul 13, 2023 |
| Apple         | MacBookPro9,2               | [c1a6aea2fc](https://linux-hardware.org/?probe=c1a6aea2fc) | Jul 13, 2023 |
| Apple         | MacBookAir7,2               | [81f693b5b0](https://linux-hardware.org/?probe=81f693b5b0) | Jul 12, 2023 |
| Dell          | Inspiron 3421               | [d347a1b82e](https://linux-hardware.org/?probe=d347a1b82e) | Jul 12, 2023 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [bae54aa498](https://linux-hardware.org/?probe=bae54aa498) | Jul 12, 2023 |
| Dell          | Inspiron 3501               | [7190b16550](https://linux-hardware.org/?probe=7190b16550) | Jul 12, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | [052461ef4d](https://linux-hardware.org/?probe=052461ef4d) | Jul 11, 2023 |
| HP            | Compaq 2510p                | [a7cb1d43fb](https://linux-hardware.org/?probe=a7cb1d43fb) | Jul 11, 2023 |
| HP            | Pavilion g4                 | [6e76f09416](https://linux-hardware.org/?probe=6e76f09416) | Jul 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [ecc4006807](https://linux-hardware.org/?probe=ecc4006807) | Jul 11, 2023 |
| HP            | ProBook 450 G6              | [8e5774c497](https://linux-hardware.org/?probe=8e5774c497) | Jul 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [2c690e981a](https://linux-hardware.org/?probe=2c690e981a) | Jul 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [732d09609d](https://linux-hardware.org/?probe=732d09609d) | Jul 10, 2023 |
| HP            | EliteBook 840 G5            | [08770a11c6](https://linux-hardware.org/?probe=08770a11c6) | Jul 10, 2023 |
| HP            | Compaq 2510p                | [98d500c68c](https://linux-hardware.org/?probe=98d500c68c) | Jul 10, 2023 |
| Lenovo        | ThinkPad Yoga 260 20FES3... | [621eaf410c](https://linux-hardware.org/?probe=621eaf410c) | Jul 10, 2023 |
| Lenovo        | ThinkPad Yoga 260 20FES3... | [3631291aa8](https://linux-hardware.org/?probe=3631291aa8) | Jul 10, 2023 |
| HP            | Notebook                    | [7d4bc75f38](https://linux-hardware.org/?probe=7d4bc75f38) | Jul 09, 2023 |
| ASUSTek       | K54C                        | [3f0ca5ad18](https://linux-hardware.org/?probe=3f0ca5ad18) | Jul 09, 2023 |
| HP            | Laptop 15-dy1xxx            | [938e9efd55](https://linux-hardware.org/?probe=938e9efd55) | Jul 09, 2023 |
| Unknown       | SLR-0308                    | [d5b0d30e8d](https://linux-hardware.org/?probe=d5b0d30e8d) | Jul 09, 2023 |
| Apple         | MacBookPro11,2              | [e6693c16ff](https://linux-hardware.org/?probe=e6693c16ff) | Jul 09, 2023 |
| Dell          | Latitude E5470              | [e04195b0f7](https://linux-hardware.org/?probe=e04195b0f7) | Jul 08, 2023 |
| OTVOC         | N1                          | [1b4d619110](https://linux-hardware.org/?probe=1b4d619110) | Jul 07, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [7b62ed78d1](https://linux-hardware.org/?probe=7b62ed78d1) | Jul 07, 2023 |
| Toshiba       | Satellite L670              | [fdc3192779](https://linux-hardware.org/?probe=fdc3192779) | Jul 06, 2023 |
| Lenovo        | Legion Y7000P-1060 81LF     | [203ffa97b4](https://linux-hardware.org/?probe=203ffa97b4) | Jul 06, 2023 |
| Toshiba       | Satellite L670              | [1db76edeb5](https://linux-hardware.org/?probe=1db76edeb5) | Jul 06, 2023 |
| Dell          | XPS 13 9370                 | [854ca6ff4f](https://linux-hardware.org/?probe=854ca6ff4f) | Jul 06, 2023 |
| ASUSTek       | ZenBook UX482EG_UX482EG     | [774ebec1d8](https://linux-hardware.org/?probe=774ebec1d8) | Jul 05, 2023 |
| Dell          | Precision M4700             | [3680e0f79f](https://linux-hardware.org/?probe=3680e0f79f) | Jul 04, 2023 |
| HP            | EliteBook 820 G4            | [58ced183c2](https://linux-hardware.org/?probe=58ced183c2) | Jul 04, 2023 |
| Acer          | Nitro AN515-44              | [d3aeb3e580](https://linux-hardware.org/?probe=d3aeb3e580) | Jul 03, 2023 |
| Digibras      | NH4CU03                     | [c073941827](https://linux-hardware.org/?probe=c073941827) | Jul 03, 2023 |
| OTVOC         | N1                          | [833ed0c86b](https://linux-hardware.org/?probe=833ed0c86b) | Jul 02, 2023 |
| HP            | ENVY m6                     | [748e336af0](https://linux-hardware.org/?probe=748e336af0) | Jul 02, 2023 |
| HP            | Compaq 6910p (GR670ET#UU... | [1ca7da939f](https://linux-hardware.org/?probe=1ca7da939f) | Jul 02, 2023 |
| HP            | Compaq 6830s                | [9a777f4318](https://linux-hardware.org/?probe=9a777f4318) | Jul 01, 2023 |
| ASUSTek       | K50IJ                       | [8262209249](https://linux-hardware.org/?probe=8262209249) | Jun 30, 2023 |
| Dell          | Latitude E6400              | [c8f88ff5b6](https://linux-hardware.org/?probe=c8f88ff5b6) | Jun 30, 2023 |
| Acer          | Aspire 5738                 | [b4fcb0d0c0](https://linux-hardware.org/?probe=b4fcb0d0c0) | Jun 28, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | [9d6748ef56](https://linux-hardware.org/?probe=9d6748ef56) | Jun 28, 2023 |
| HP            | ENVY m6                     | [715d68bfc0](https://linux-hardware.org/?probe=715d68bfc0) | Jun 28, 2023 |
| Dell          | Latitude E6400              | [0f9255924f](https://linux-hardware.org/?probe=0f9255924f) | Jun 28, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | [64433a8783](https://linux-hardware.org/?probe=64433a8783) | Jun 27, 2023 |
| HP            | Laptop 14-ck0xxx            | [663ce69f30](https://linux-hardware.org/?probe=663ce69f30) | Jun 27, 2023 |
| HP            | Laptop 14-ck0xxx            | [73eab89788](https://linux-hardware.org/?probe=73eab89788) | Jun 27, 2023 |
| Lenovo        | V110-15IKB 80TH             | [e6b9f96475](https://linux-hardware.org/?probe=e6b9f96475) | Jun 27, 2023 |
| HP            | Pavilion dv6700             | [182bf6e4a7](https://linux-hardware.org/?probe=182bf6e4a7) | Jun 27, 2023 |
| Lenovo        | ThinkPad Yoga 11e 20DA50... | [b756e54029](https://linux-hardware.org/?probe=b756e54029) | Jun 27, 2023 |
| Dell          | Latitude 3189               | [ad7c98c905](https://linux-hardware.org/?probe=ad7c98c905) | Jun 26, 2023 |
| Dell          | Latitude 3189               | [8547503af5](https://linux-hardware.org/?probe=8547503af5) | Jun 25, 2023 |
| Dell          | Latitude 3189               | [3f44430a36](https://linux-hardware.org/?probe=3f44430a36) | Jun 25, 2023 |
| Lenovo        | ThinkPad E560 20EV000UIX    | [ac6bd9497a](https://linux-hardware.org/?probe=ac6bd9497a) | Jun 25, 2023 |
| Toshiba       | Satellite U400              | [58b2ad81eb](https://linux-hardware.org/?probe=58b2ad81eb) | Jun 25, 2023 |
| Acer          | Aspire M3-581G              | [0c348c2570](https://linux-hardware.org/?probe=0c348c2570) | Jun 25, 2023 |
| Apple         | MacBookPro11,2              | [2d7e4f3505](https://linux-hardware.org/?probe=2d7e4f3505) | Jun 24, 2023 |
| Acer          | Aspire 5738                 | [8112b061f0](https://linux-hardware.org/?probe=8112b061f0) | Jun 24, 2023 |
| Dell          | Latitude E6400              | [74be208929](https://linux-hardware.org/?probe=74be208929) | Jun 24, 2023 |
| Acer          | AOD270                      | [af596f2c11](https://linux-hardware.org/?probe=af596f2c11) | Jun 24, 2023 |
| Acer          | AOD270                      | [d3204f80d5](https://linux-hardware.org/?probe=d3204f80d5) | Jun 24, 2023 |
| Toshiba       | Satellite U400              | [aa6254ebd2](https://linux-hardware.org/?probe=aa6254ebd2) | Jun 24, 2023 |
| HP            | EliteBook 8560p             | [177d2fe509](https://linux-hardware.org/?probe=177d2fe509) | Jun 22, 2023 |
| Google        | Kefka                       | [2580ed90ee](https://linux-hardware.org/?probe=2580ed90ee) | Jun 22, 2023 |
| Apple         | MacBookAir7,2               | [ae8c13c6fd](https://linux-hardware.org/?probe=ae8c13c6fd) | Jun 22, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [3d558ea9aa](https://linux-hardware.org/?probe=3d558ea9aa) | Jun 21, 2023 |
| Dell          | Vostro 5481                 | [b28f58f09e](https://linux-hardware.org/?probe=b28f58f09e) | Jun 20, 2023 |
| HP            | ENVY m6                     | [ea4c3aca13](https://linux-hardware.org/?probe=ea4c3aca13) | Jun 20, 2023 |
| Dell          | Inspiron 5558               | [72ef7ff0aa](https://linux-hardware.org/?probe=72ef7ff0aa) | Jun 20, 2023 |
| Dell          | G7 7588                     | [946a645897](https://linux-hardware.org/?probe=946a645897) | Jun 20, 2023 |
| Sony          | VPCCA15FX                   | [ed7dba1a4c](https://linux-hardware.org/?probe=ed7dba1a4c) | Jun 19, 2023 |
| Dell          | Vostro 1520                 | [bc371b62c9](https://linux-hardware.org/?probe=bc371b62c9) | Jun 19, 2023 |
| Sony          | VPCCA15FX                   | [c5660d0020](https://linux-hardware.org/?probe=c5660d0020) | Jun 19, 2023 |
| Dell          | Vostro 1520                 | [8086cf1231](https://linux-hardware.org/?probe=8086cf1231) | Jun 19, 2023 |
| Lenovo        | ThinkPad T440 20B7S0VA05    | [307c8a76ab](https://linux-hardware.org/?probe=307c8a76ab) | Jun 19, 2023 |
| GPU Compan... | GWNC21524                   | [46bd956cbf](https://linux-hardware.org/?probe=46bd956cbf) | Jun 19, 2023 |
| Toshiba       | TECRA M10                   | [37f232dce0](https://linux-hardware.org/?probe=37f232dce0) | Jun 19, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | [7546cac791](https://linux-hardware.org/?probe=7546cac791) | Jun 19, 2023 |
| HP            | EliteBook 840 G3            | [e1fc794bc5](https://linux-hardware.org/?probe=e1fc794bc5) | Jun 18, 2023 |
| ASUSTek       | VivoBook S13 X330FA_S330... | [b816a11527](https://linux-hardware.org/?probe=b816a11527) | Jun 18, 2023 |
| Acer          | Aspire 5738                 | [8247e349fc](https://linux-hardware.org/?probe=8247e349fc) | Jun 17, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [bb6859a141](https://linux-hardware.org/?probe=bb6859a141) | Jun 17, 2023 |
| HP            | ProBook 650 G5              | [1d158627b0](https://linux-hardware.org/?probe=1d158627b0) | Jun 17, 2023 |
| Dell          | Latitude 7370               | [5c2378adc5](https://linux-hardware.org/?probe=5c2378adc5) | Jun 17, 2023 |
| Dell          | Latitude 7370               | [44dba24aed](https://linux-hardware.org/?probe=44dba24aed) | Jun 17, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [3614dc460e](https://linux-hardware.org/?probe=3614dc460e) | Jun 17, 2023 |
| HP            | Laptop 14-bw0xx             | [f38253d79c](https://linux-hardware.org/?probe=f38253d79c) | Jun 17, 2023 |
| Haier         | Y11B                        | [0c2abeea6e](https://linux-hardware.org/?probe=0c2abeea6e) | Jun 17, 2023 |
| HP            | ProBook 650 G5              | [9c53e4cd72](https://linux-hardware.org/?probe=9c53e4cd72) | Jun 17, 2023 |
| HP            | G62                         | [2e1e964887](https://linux-hardware.org/?probe=2e1e964887) | Jun 16, 2023 |
| Acer          | Aspire V5-571P              | [2adeb26f8a](https://linux-hardware.org/?probe=2adeb26f8a) | Jun 15, 2023 |
| eMachines     | eMD728                      | [85dd880b0d](https://linux-hardware.org/?probe=85dd880b0d) | Jun 15, 2023 |
| ASUSTek       | K52N                        | [eb2ec7cb3d](https://linux-hardware.org/?probe=eb2ec7cb3d) | Jun 15, 2023 |
| Dell          | Venue 11 Pro 5130           | [e1bb6b17b8](https://linux-hardware.org/?probe=e1bb6b17b8) | Jun 14, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [9fe9d9f03f](https://linux-hardware.org/?probe=9fe9d9f03f) | Jun 13, 2023 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [b737ce6557](https://linux-hardware.org/?probe=b737ce6557) | Jun 13, 2023 |
| HP            | ENVY m6                     | [b3c165b329](https://linux-hardware.org/?probe=b3c165b329) | Jun 12, 2023 |
| MSI           | GL62M 7RDX                  | [d1fb646d9a](https://linux-hardware.org/?probe=d1fb646d9a) | Jun 11, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [9cb593e9e1](https://linux-hardware.org/?probe=9cb593e9e1) | Jun 11, 2023 |
| ASUSTek       | U43Jc                       | [1af7e59490](https://linux-hardware.org/?probe=1af7e59490) | Jun 11, 2023 |
| ASUSTek       | U43Jc                       | [15e8e27585](https://linux-hardware.org/?probe=15e8e27585) | Jun 11, 2023 |
| HP            | Pavilion g7                 | [c599527484](https://linux-hardware.org/?probe=c599527484) | Jun 11, 2023 |
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
| Fujitsu Si... | AMILO A1645                 | [d825262368](https://linux-hardware.org/?probe=d825262368) | May 16, 2023 |
| Fujitsu Si... | AMILO A1645                 | [18ca79ef29](https://linux-hardware.org/?probe=18ca79ef29) | May 16, 2023 |
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
| eMachines     | E620                        | [827a81facc](https://linux-hardware.org/?probe=827a81facc) | May 11, 2023 |
| Apple         | MacBookPro10,1              | [381ca3ca78](https://linux-hardware.org/?probe=381ca3ca78) | May 11, 2023 |
| HP            | OMEN by Laptop              | [2c8128a196](https://linux-hardware.org/?probe=2c8128a196) | May 11, 2023 |
| HP            | EliteBook 820 G4            | [a7327f2e2e](https://linux-hardware.org/?probe=a7327f2e2e) | May 11, 2023 |
| HP            | EliteBook 745 G3            | [256ad0c4d8](https://linux-hardware.org/?probe=256ad0c4d8) | May 11, 2023 |
| Acer          | Aspire A315-23              | [2c96614c16](https://linux-hardware.org/?probe=2c96614c16) | May 11, 2023 |
| Toshiba       | TECRA M10                   | [cf43cf62c7](https://linux-hardware.org/?probe=cf43cf62c7) | May 10, 2023 |
| Toshiba       | TECRA M10                   | [d2be66b23b](https://linux-hardware.org/?probe=d2be66b23b) | May 10, 2023 |
| HP            | Pavilion dv7                | [794d198929](https://linux-hardware.org/?probe=794d198929) | May 10, 2023 |
| Toshiba       | Satellite M60               | [91437556e8](https://linux-hardware.org/?probe=91437556e8) | May 09, 2023 |
| Toshiba       | Satellite M60               | [39b2bcd3a5](https://linux-hardware.org/?probe=39b2bcd3a5) | May 09, 2023 |
| ASUSTek       | GL702VI                     | [3598875ef3](https://linux-hardware.org/?probe=3598875ef3) | May 09, 2023 |
| HP            | EliteBook 840 G4            | [372fa59e86](https://linux-hardware.org/?probe=372fa59e86) | May 09, 2023 |
| HP            | EliteBook 840 G4            | [9ac068efc7](https://linux-hardware.org/?probe=9ac068efc7) | May 09, 2023 |
| Dell          | Latitude E6520              | [668b26cd28](https://linux-hardware.org/?probe=668b26cd28) | May 09, 2023 |
| HP            | Laptop 15                   | [20a0a03b80](https://linux-hardware.org/?probe=20a0a03b80) | May 08, 2023 |
| Fujitsu Si... | LIFEBOOK S6420              | [953d03df07](https://linux-hardware.org/?probe=953d03df07) | May 08, 2023 |
| Acer          | Aspire E5-574               | [d48affb6b2](https://linux-hardware.org/?probe=d48affb6b2) | May 08, 2023 |
| Fujitsu Si... | LIFEBOOK S6420              | [ee52ca7ce5](https://linux-hardware.org/?probe=ee52ca7ce5) | May 08, 2023 |
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
| Acer          | Aspire 5732Z                | [f9868f3430](https://linux-hardware.org/?probe=f9868f3430) | May 04, 2023 |
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
| Acer          | AOHAPPY                     | [6f32fad8f0](https://linux-hardware.org/?probe=6f32fad8f0) | Apr 24, 2023 |
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
| Acer          | AOHAPPY                     | [57a7ebf03f](https://linux-hardware.org/?probe=57a7ebf03f) | Apr 21, 2023 |
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
| Lenovo        | G500 20236                  | [22d22e0742](https://linux-hardware.org/?probe=22d22e0742) | Apr 01, 2023 |
| Lenovo        | G500 20236                  | [2994622700](https://linux-hardware.org/?probe=2994622700) | Apr 01, 2023 |
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
| HP            | 255 G5                      | [99e2d83974](https://linux-hardware.org/?probe=99e2d83974) | Mar 24, 2023 |
| Dell          | Inspiron 3721               | [e992b8f3a0](https://linux-hardware.org/?probe=e992b8f3a0) | Mar 23, 2023 |
| HP            | Pavilion 15                 | [32a0c3ec32](https://linux-hardware.org/?probe=32a0c3ec32) | Mar 23, 2023 |
| HP            | Pavilion dv6                | [625fff449a](https://linux-hardware.org/?probe=625fff449a) | Mar 23, 2023 |
| Dell          | Latitude E7240              | [a3e408033c](https://linux-hardware.org/?probe=a3e408033c) | Mar 21, 2023 |
| ASUSTek       | G53SX                       | [a6c90e3ad8](https://linux-hardware.org/?probe=a6c90e3ad8) | Mar 21, 2023 |
| Dell          | Inspiron 5405               | [bb59d0b5e9](https://linux-hardware.org/?probe=bb59d0b5e9) | Mar 20, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [e7344d03c0](https://linux-hardware.org/?probe=e7344d03c0) | Mar 20, 2023 |
| Acer          | TravelMate 2490             | [5a21a61bef](https://linux-hardware.org/?probe=5a21a61bef) | Mar 19, 2023 |
| Dell          | Inspiron 5423               | [70f51cbfcb](https://linux-hardware.org/?probe=70f51cbfcb) | Mar 19, 2023 |
| Google        | Kip                         | [84b79bf446](https://linux-hardware.org/?probe=84b79bf446) | Mar 19, 2023 |
| Google        | Kip                         | [4e63ea7ac8](https://linux-hardware.org/?probe=4e63ea7ac8) | Mar 19, 2023 |
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
| HP            | Compaq nc6120 (PY505EA#A... | [2b864d8f97](https://linux-hardware.org/?probe=2b864d8f97) | Mar 12, 2023 |
| Novatech      | 15.6 nSpire Laptop          | [f5814aa2e6](https://linux-hardware.org/?probe=f5814aa2e6) | Mar 12, 2023 |
| Lenovo        | ThinkPad X270 20HMS1KL0C    | [f27bb76a32](https://linux-hardware.org/?probe=f27bb76a32) | Mar 12, 2023 |
| Acer          | TravelMate B113             | [e5f001172d](https://linux-hardware.org/?probe=e5f001172d) | Mar 12, 2023 |
| Apple         | MacBookPro9,2               | [fd63e92774](https://linux-hardware.org/?probe=fd63e92774) | Mar 12, 2023 |
| Apple         | MacBookPro9,2               | [6a0426cb65](https://linux-hardware.org/?probe=6a0426cb65) | Mar 12, 2023 |
| Dell          | Latitude E5470              | [86adaddcae](https://linux-hardware.org/?probe=86adaddcae) | Mar 12, 2023 |
| Acer          | TravelMate B113             | [ba6dc5dcb5](https://linux-hardware.org/?probe=ba6dc5dcb5) | Mar 11, 2023 |
| HP            | Pavilion dv6                | [fca49aa86c](https://linux-hardware.org/?probe=fca49aa86c) | Mar 11, 2023 |
| Dell          | Latitude E5470              | [e7e23885b7](https://linux-hardware.org/?probe=e7e23885b7) | Mar 11, 2023 |
| Clevo         | W251EFQ/W270EFQ             | [daad1ee8d5](https://linux-hardware.org/?probe=daad1ee8d5) | Mar 11, 2023 |
| HP            | ZBook 17 G2                 | [4b9462a4ff](https://linux-hardware.org/?probe=4b9462a4ff) | Mar 11, 2023 |
| HP            | Compaq nc6120 (PY505EA#A... | [c8d3cf3a4b](https://linux-hardware.org/?probe=c8d3cf3a4b) | Mar 11, 2023 |
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
| ASUSTek       | K50IJ                       | [6b906bab7d](https://linux-hardware.org/?probe=6b906bab7d) | Mar 09, 2023 |
| ASUSTek       | X550CL                      | [9acfcb9b4f](https://linux-hardware.org/?probe=9acfcb9b4f) | Mar 09, 2023 |
| ASUSTek       | X550CL                      | [21f11cf791](https://linux-hardware.org/?probe=21f11cf791) | Mar 09, 2023 |
| Multilaser    | PC130                       | [37212994df](https://linux-hardware.org/?probe=37212994df) | Mar 09, 2023 |
| Lenovo        | ThinkPad 11e 20DAS0T500     | [e6fd8c46b0](https://linux-hardware.org/?probe=e6fd8c46b0) | Mar 08, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [d01b6ad50c](https://linux-hardware.org/?probe=d01b6ad50c) | Mar 08, 2023 |
| ASUSTek       | K50IJ                       | [cc455dcfac](https://linux-hardware.org/?probe=cc455dcfac) | Mar 08, 2023 |
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
| Dell          | Inspiron N5010              | [480ff87a20](https://linux-hardware.org/?probe=480ff87a20) | Feb 28, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [c698fc199a](https://linux-hardware.org/?probe=c698fc199a) | Feb 28, 2023 |
| HP            | ENVY 17                     | [61d1252ef3](https://linux-hardware.org/?probe=61d1252ef3) | Feb 28, 2023 |
| ASUSTek       | T100HAN                     | [4f835a4f35](https://linux-hardware.org/?probe=4f835a4f35) | Feb 28, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [7478549a38](https://linux-hardware.org/?probe=7478549a38) | Feb 28, 2023 |
| Dell          | Latitude E6440              | [80131cd2a4](https://linux-hardware.org/?probe=80131cd2a4) | Feb 28, 2023 |
| Lenovo        | ThinkPad R400 7439W2F       | [2673ce6bd9](https://linux-hardware.org/?probe=2673ce6bd9) | Feb 27, 2023 |
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
| HP            | ENVY 17                     | [ea0b2e63ef](https://linux-hardware.org/?probe=ea0b2e63ef) | Feb 21, 2023 |
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
| Toshiba       | Satellite L50D-B            | [689c37d3b7](https://linux-hardware.org/?probe=689c37d3b7) | Feb 19, 2023 |
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
| HP            | ENVY 17                     | [de8af1b249](https://linux-hardware.org/?probe=de8af1b249) | Feb 18, 2023 |
| Dell          | Inspiron 14 Plus 7420       | [59387e9081](https://linux-hardware.org/?probe=59387e9081) | Feb 18, 2023 |
| Medion        | E7220                       | [289b7dc6aa](https://linux-hardware.org/?probe=289b7dc6aa) | Feb 17, 2023 |
| Acer          | Aspire 5738                 | [48bbbc04c4](https://linux-hardware.org/?probe=48bbbc04c4) | Feb 17, 2023 |
| ASUSTek       | K50IJ                       | [9b35a3205f](https://linux-hardware.org/?probe=9b35a3205f) | Feb 17, 2023 |
| ASUSTek       | X450LD                      | [b4fb1ddc5a](https://linux-hardware.org/?probe=b4fb1ddc5a) | Feb 17, 2023 |
| Google        | Robo                        | [303c72db93](https://linux-hardware.org/?probe=303c72db93) | Feb 17, 2023 |
| HP            | Laptop 15-bs1xx             | [88d9514231](https://linux-hardware.org/?probe=88d9514231) | Feb 17, 2023 |
| Dell          | Inspiron 3793               | [b997f44969](https://linux-hardware.org/?probe=b997f44969) | Feb 16, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [8043264215](https://linux-hardware.org/?probe=8043264215) | Feb 16, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [c08ad0f295](https://linux-hardware.org/?probe=c08ad0f295) | Feb 16, 2023 |
| ASUSTek       | K50IJ                       | [a37ac85ec2](https://linux-hardware.org/?probe=a37ac85ec2) | Feb 16, 2023 |
| HP            | ENVY TS Sleekbook 4         | [1189701feb](https://linux-hardware.org/?probe=1189701feb) | Feb 15, 2023 |
| Acer          | Extensa 5230                | [2716bcf519](https://linux-hardware.org/?probe=2716bcf519) | Feb 15, 2023 |
| Dell          | Latitude 3320               | [fecee449d4](https://linux-hardware.org/?probe=fecee449d4) | Feb 15, 2023 |
| Lenovo        | ThinkPad L480 20LS001AMX    | [6c1c0027b1](https://linux-hardware.org/?probe=6c1c0027b1) | Feb 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [c2d957f650](https://linux-hardware.org/?probe=c2d957f650) | Feb 15, 2023 |
| Dell          | System XPS L502X            | [2ea016be2a](https://linux-hardware.org/?probe=2ea016be2a) | Feb 14, 2023 |
| Apple         | MacBook2,1                  | [915e87767b](https://linux-hardware.org/?probe=915e87767b) | Feb 14, 2023 |
| Dell          | Latitude 5480               | [03123ee601](https://linux-hardware.org/?probe=03123ee601) | Feb 14, 2023 |
| IBM           | ThinkPad T40p 2373CG6       | [a7aa67f64e](https://linux-hardware.org/?probe=a7aa67f64e) | Feb 14, 2023 |
| IBM           | ThinkPad T40p 2373CG6       | [eda645cefe](https://linux-hardware.org/?probe=eda645cefe) | Feb 14, 2023 |
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
| TWC           | Unknown                     | [4ea2803396](https://linux-hardware.org/?probe=4ea2803396) | Feb 06, 2023 |
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
| ASUSTek       | K50IJ                       | [c01f530c1c](https://linux-hardware.org/?probe=c01f530c1c) | Jan 31, 2023 |
| ASUSTek       | K50IJ                       | [51c65b48bc](https://linux-hardware.org/?probe=51c65b48bc) | Jan 31, 2023 |
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
| AXDIA Inte... | WINPAD V10                  | [dc93e9d9f0](https://linux-hardware.org/?probe=dc93e9d9f0) | Jan 24, 2023 |
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
| ASUSTek       | A6U                         | [58c040d67c](https://linux-hardware.org/?probe=58c040d67c) | Jan 19, 2023 |
| ASUSTek       | A6U                         | [9156e1c9cd](https://linux-hardware.org/?probe=9156e1c9cd) | Jan 19, 2023 |
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
| HP            | Pavilion 17                 | [09b186fbf7](https://linux-hardware.org/?probe=09b186fbf7) | Jan 16, 2023 |
| Lenovo        | G560 0679                   | [26e16a5898](https://linux-hardware.org/?probe=26e16a5898) | Jan 15, 2023 |
| Dell          | Inspiron 7437               | [df8d69926f](https://linux-hardware.org/?probe=df8d69926f) | Jan 15, 2023 |
| Dell          | Inspiron 7437               | [0670d91eb0](https://linux-hardware.org/?probe=0670d91eb0) | Jan 15, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Zorin/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Zorin 16 | 1915      | 62.93%  |
| Zorin 15 | 1014      | 33.32%  |
| Zorin 12 | 114       | 3.75%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| Zorin | 3032      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.15.0-56-generic | 133       | 3.84%   |
| 5.11.0-38-generic | 101       | 2.91%   |
| 5.11.0-27-generic | 94        | 2.71%   |
| 5.15.0-52-generic | 93        | 2.68%   |
| 5.15.0-58-generic | 90        | 2.6%    |
| 5.15.0-46-generic | 88        | 2.54%   |
| 5.13.0-30-generic | 74        | 2.13%   |
| 5.3.0-40-generic  | 67        | 1.93%   |
| 5.11.0-37-generic | 67        | 1.93%   |
| 5.11.0-40-generic | 65        | 1.87%   |
| 5.15.0-69-generic | 63        | 1.82%   |
| 5.15.0-67-generic | 63        | 1.82%   |
| 5.11.0-41-generic | 63        | 1.82%   |
| 5.4.0-42-generic  | 61        | 1.76%   |
| 5.13.0-39-generic | 60        | 1.73%   |
| 5.15.0-78-generic | 57        | 1.64%   |
| 5.11.0-34-generic | 57        | 1.64%   |
| 5.15.0-60-generic | 56        | 1.61%   |
| 5.11.0-43-generic | 56        | 1.61%   |
| 5.15.0-76-generic | 55        | 1.59%   |
| 5.3.0-46-generic  | 53        | 1.53%   |
| 5.15.0-71-generic | 52        | 1.5%    |
| 5.15.0-48-generic | 51        | 1.47%   |
| 5.13.0-44-generic | 48        | 1.38%   |
| 5.3.0-51-generic  | 47        | 1.36%   |
| 5.0.0-37-generic  | 47        | 1.36%   |
| 5.13.0-40-generic | 46        | 1.33%   |
| 5.15.0-53-generic | 43        | 1.24%   |
| 5.13.0-35-generic | 40        | 1.15%   |
| 5.4.0-47-generic  | 38        | 1.1%    |
| 5.3.0-53-generic  | 37        | 1.07%   |
| 5.13.0-28-generic | 37        | 1.07%   |
| 5.3.0-42-generic  | 36        | 1.04%   |
| 5.4.0-45-generic  | 35        | 1.01%   |
| 5.15.0-41-generic | 35        | 1.01%   |
| 5.15.0-79-generic | 34        | 0.98%   |
| 5.15.0-73-generic | 34        | 0.98%   |
| 5.4.0-58-generic  | 32        | 0.92%   |
| 5.4.0-48-generic  | 31        | 0.89%   |
| 5.15.0-72-generic | 31        | 0.89%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 986       | 31.2%   |
| 5.4.0   | 592       | 18.73%  |
| 5.11.0  | 550       | 17.41%  |
| 5.13.0  | 406       | 12.85%  |
| 5.3.0   | 312       | 9.87%   |
| 4.15.0  | 110       | 3.48%   |
| 5.0.0   | 89        | 2.82%   |
| 4.18.0  | 45        | 1.42%   |
| 5.8.0   | 23        | 0.73%   |
| 5.14.0  | 8         | 0.25%   |
| 4.4.0   | 4         | 0.13%   |
| 6.3.13  | 2         | 0.06%   |
| 5.6.0   | 2         | 0.06%   |
| 5.18.15 | 2         | 0.06%   |
| 5.16.0  | 2         | 0.06%   |
| 5.10.0  | 2         | 0.06%   |
| 6.3.2   | 1         | 0.03%   |
| 6.3.1   | 1         | 0.03%   |
| 6.2.16  | 1         | 0.03%   |
| 6.2.14  | 1         | 0.03%   |
| 6.0.9   | 1         | 0.03%   |
| 6.0.19  | 1         | 0.03%   |
| 6.0.0   | 1         | 0.03%   |
| 5.9.12  | 1         | 0.03%   |
| 5.9.0   | 1         | 0.03%   |
| 5.7.1   | 1         | 0.03%   |
| 5.4.180 | 1         | 0.03%   |
| 5.4.1   | 1         | 0.03%   |
| 5.19.9  | 1         | 0.03%   |
| 5.19.14 | 1         | 0.03%   |
| 5.19.12 | 1         | 0.03%   |
| 5.19.1  | 1         | 0.03%   |
| 5.19.0  | 1         | 0.03%   |
| 5.18.6  | 1         | 0.03%   |
| 5.16.12 | 1         | 0.03%   |
| 5.15.49 | 1         | 0.03%   |
| 5.15.24 | 1         | 0.03%   |
| 5.13.18 | 1         | 0.03%   |
| 5.10.35 | 1         | 0.03%   |
| 5.10.16 | 1         | 0.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 988       | 31.27%  |
| 5.4     | 594       | 18.8%   |
| 5.11    | 550       | 17.41%  |
| 5.13    | 407       | 12.88%  |
| 5.3     | 312       | 9.87%   |
| 4.15    | 110       | 3.48%   |
| 5.0     | 89        | 2.82%   |
| 4.18    | 45        | 1.42%   |
| 5.8     | 23        | 0.73%   |
| 5.14    | 8         | 0.25%   |
| 5.19    | 5         | 0.16%   |
| 6.3     | 4         | 0.13%   |
| 5.10    | 4         | 0.13%   |
| 4.4     | 4         | 0.13%   |
| 6.0     | 3         | 0.09%   |
| 5.18    | 3         | 0.09%   |
| 5.16    | 3         | 0.09%   |
| 6.2     | 2         | 0.06%   |
| 5.9     | 2         | 0.06%   |
| 5.6     | 2         | 0.06%   |
| 5.7     | 1         | 0.03%   |
| 4.13    | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 2754      | 90.74%  |
| i686   | 281       | 9.26%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 2150      | 70.15%  |
| XFCE       | 721       | 23.52%  |
| Unknown    | 172       | 5.61%   |
| X-Cinnamon | 7         | 0.23%   |
| Unity      | 3         | 0.1%    |
| KDE5       | 3         | 0.1%    |
| KDE        | 3         | 0.1%    |
| i3         | 2         | 0.07%   |
| Budgie     | 2         | 0.07%   |
| LXDE       | 1         | 0.03%   |
| Cinnamon   | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 2897      | 94.64%  |
| Unknown | 107       | 3.5%    |
| Wayland | 56        | 1.83%   |
| Tty     | 1         | 0.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 2393      | 77.77%  |
| GDM3    | 240       | 7.8%    |
| GDM     | 240       | 7.8%    |
| LightDM | 195       | 6.34%   |
| TDM     | 6         | 0.19%   |
| SDDM    | 2         | 0.06%   |
| LXDM    | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 1068      | 34.92%  |
| de_DE   | 231       | 7.55%   |
| pt_BR   | 195       | 6.38%   |
| en_GB   | 179       | 5.85%   |
| Unknown | 127       | 4.15%   |
| it_IT   | 118       | 3.86%   |
| es_ES   | 103       | 3.37%   |
| fr_FR   | 98        | 3.2%    |
| en_IN   | 95        | 3.11%   |
| en_CA   | 88        | 2.88%   |
| pl_PL   | 74        | 2.42%   |
| en_AU   | 47        | 1.54%   |
| es_MX   | 44        | 1.44%   |
| nl_NL   | 43        | 1.41%   |
| pt_PT   | 42        | 1.37%   |
| ru_RU   | 37        | 1.21%   |
| cs_CZ   | 36        | 1.18%   |
| es_AR   | 31        | 1.01%   |
| en_ZA   | 31        | 1.01%   |
| tr_TR   | 24        | 0.78%   |
| sv_SE   | 23        | 0.75%   |
| C       | 20        | 0.65%   |
| es_CL   | 19        | 0.62%   |
| en_NZ   | 18        | 0.59%   |
| de_AT   | 18        | 0.59%   |
| hu_HU   | 16        | 0.52%   |
| de_CH   | 15        | 0.49%   |
| ja_JP   | 13        | 0.43%   |
| fr_BE   | 13        | 0.43%   |
| nl_BE   | 12        | 0.39%   |
| fr_CA   | 12        | 0.39%   |
| el_GR   | 11        | 0.36%   |
| es_CO   | 10        | 0.33%   |
| en_PH   | 9         | 0.29%   |
| da_DK   | 9         | 0.29%   |
| ro_RO   | 8         | 0.26%   |
| ru_UA   | 7         | 0.23%   |
| hr_HR   | 7         | 0.23%   |
| es_PE   | 7         | 0.23%   |
| sk_SK   | 6         | 0.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 1574      | 51.25%  |
| EFI  | 1497      | 48.75%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 2823      | 92.5%   |
| Overlay | 67        | 2.2%    |
| Tmpfs   | 59        | 1.93%   |
| Zfs     | 31        | 1.02%   |
| Btrfs   | 27        | 0.88%   |
| Ext2    | 21        | 0.69%   |
| Unknown | 17        | 0.56%   |
| Xfs     | 4         | 0.13%   |
| Ext3    | 3         | 0.1%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 2620      | 85.45%  |
| GPT     | 337       | 10.99%  |
| MBR     | 109       | 3.56%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2895      | 94.86%  |
| Yes       | 157       | 5.14%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2568      | 84.22%  |
| Yes       | 481       | 15.78%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 685       | 22.59%  |
| Lenovo              | 479       | 15.8%   |
| Dell                | 467       | 15.4%   |
| ASUSTek Computer    | 289       | 9.53%   |
| Acer                | 244       | 8.05%   |
| Toshiba             | 162       | 5.34%   |
| Apple               | 88        | 2.9%    |
| Samsung Electronics | 60        | 1.98%   |
| Sony                | 53        | 1.75%   |
| MSI                 | 45        | 1.48%   |
| Google              | 32        | 1.06%   |
| Unknown             | 30        | 0.99%   |
| Packard Bell        | 29        | 0.96%   |
| Positivo            | 23        | 0.76%   |
| HUAWEI              | 20        | 0.66%   |
| Fujitsu Siemens     | 20        | 0.66%   |
| Fujitsu             | 18        | 0.59%   |
| Medion              | 16        | 0.53%   |
| Notebook            | 12        | 0.4%    |
| Alienware           | 12        | 0.4%    |
| Chuwi               | 10        | 0.33%   |
| Panasonic           | 9         | 0.3%    |
| AMI                 | 9         | 0.3%    |
| Gateway             | 8         | 0.26%   |
| eMachines           | 8         | 0.26%   |
| Multilaser          | 7         | 0.23%   |
| Itautec             | 7         | 0.23%   |
| LG Electronics      | 6         | 0.2%    |
| Insyde              | 6         | 0.2%    |
| GPU Company         | 6         | 0.2%    |
| Digibras            | 6         | 0.2%    |
| Semp Toshiba        | 5         | 0.16%   |
| NEC Computers       | 5         | 0.16%   |
| Intel               | 5         | 0.16%   |
| Ematic              | 5         | 0.16%   |
| Clevo               | 5         | 0.16%   |
| Thomson             | 4         | 0.13%   |
| Razer               | 4         | 0.13%   |
| Quanta              | 4         | 0.13%   |
| Microtech           | 4         | 0.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Unknown                   | 59        | 1.95%   |
| HP Notebook               | 30        | 0.99%   |
| HP Pavilion Notebook      | 17        | 0.56%   |
| HP Pavilion dv6           | 16        | 0.53%   |
| HP 15                     | 16        | 0.53%   |
| HP Pavilion dv7           | 14        | 0.46%   |
| HP Pavilion 15            | 12        | 0.4%    |
| Toshiba Satellite C660    | 10        | 0.33%   |
| Dell Latitude E6400       | 10        | 0.33%   |
| Dell Latitude D630        | 10        | 0.33%   |
| Dell Inspiron 1545        | 10        | 0.33%   |
| HP Pavilion g6            | 9         | 0.3%    |
| Apple MacBookPro8,1       | 9         | 0.3%    |
| HP Pavilion g7            | 8         | 0.26%   |
| HP Laptop 15-bw0xx        | 8         | 0.26%   |
| Dell Latitude E6540       | 8         | 0.26%   |
| Dell Inspiron 15-3567     | 8         | 0.26%   |
| HP Pavilion dv6700        | 7         | 0.23%   |
| HP EliteBook 8460p        | 7         | 0.23%   |
| HP EliteBook 840 G1       | 7         | 0.23%   |
| Dell Latitude E6410       | 7         | 0.23%   |
| Dell Inspiron 3521        | 7         | 0.23%   |
| Dell Inspiron 1525        | 7         | 0.23%   |
| Toshiba Satellite A100    | 6         | 0.2%    |
| HP ProBook 640 G1         | 6         | 0.2%    |
| HP ProBook 4540s          | 6         | 0.2%    |
| HP Pavilion 17            | 6         | 0.2%    |
| HP Laptop 15-db0xxx       | 6         | 0.2%    |
| Dell Latitude E6430       | 6         | 0.2%    |
| Dell Latitude E5470       | 6         | 0.2%    |
| Dell Inspiron 7520        | 6         | 0.2%    |
| Apple MacBookPro12,1      | 6         | 0.2%    |
| Apple MacBookPro11,1      | 6         | 0.2%    |
| Positivo Mobile           | 5         | 0.16%   |
| Itautec Infoway           | 5         | 0.16%   |
| HP Stream Notebook        | 5         | 0.16%   |
| HP Stream Laptop 14-ax0XX | 5         | 0.16%   |
| HP ProBook 4530s          | 5         | 0.16%   |
| HP Pavilion dv5           | 5         | 0.16%   |
| HP EliteBook 2570p        | 5         | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 198       | 6.53%   |
| HP Pavilion           | 174       | 5.74%   |
| Dell Latitude         | 173       | 5.71%   |
| Dell Inspiron         | 173       | 5.71%   |
| Acer Aspire           | 171       | 5.64%   |
| Lenovo IdeaPad        | 149       | 4.91%   |
| Toshiba Satellite     | 138       | 4.55%   |
| HP EliteBook          | 88        | 2.9%    |
| HP ProBook            | 74        | 2.44%   |
| HP Laptop             | 64        | 2.11%   |
| Unknown               | 59        | 1.95%   |
| HP Compaq             | 53        | 1.75%   |
| ASUS VivoBook         | 41        | 1.35%   |
| Dell Vostro           | 35        | 1.15%   |
| HP Notebook           | 30        | 0.99%   |
| Packard Bell EasyNote | 27        | 0.89%   |
| Dell XPS              | 25        | 0.82%   |
| HP Stream             | 23        | 0.76%   |
| HP ENVY               | 23        | 0.76%   |
| Dell Precision        | 21        | 0.69%   |
| HP 15                 | 18        | 0.59%   |
| ASUS ZenBook          | 18        | 0.59%   |
| HP Presario           | 16        | 0.53%   |
| ASUS ROG              | 16        | 0.53%   |
| Lenovo Yoga           | 14        | 0.46%   |
| HP 255                | 14        | 0.46%   |
| Apple MacBookPro8     | 13        | 0.43%   |
| HP ZBook              | 12        | 0.4%    |
| HP OMEN               | 12        | 0.4%    |
| Fujitsu LIFEBOOK      | 12        | 0.4%    |
| Dell Studio           | 12        | 0.4%    |
| Acer TravelMate       | 12        | 0.4%    |
| Lenovo Legion         | 11        | 0.36%   |
| Fujitsu Siemens AMILO | 11        | 0.36%   |
| Apple MacBookPro11    | 11        | 0.36%   |
| Dell System           | 10        | 0.33%   |
| ASUS ASUS             | 10        | 0.33%   |
| Toshiba PORTEGE       | 9         | 0.3%    |
| Apple MacBookPro5     | 9         | 0.3%    |
| Acer Swift            | 9         | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 274       | 9.04%   |
| 2012    | 258       | 8.51%   |
| 2013    | 246       | 8.11%   |
| 2010    | 216       | 7.12%   |
| 2008    | 206       | 6.79%   |
| 2018    | 190       | 6.27%   |
| 2014    | 187       | 6.17%   |
| 2019    | 181       | 5.97%   |
| 2017    | 177       | 5.84%   |
| 2021    | 166       | 5.47%   |
| 2015    | 165       | 5.44%   |
| 2016    | 154       | 5.08%   |
| 2020    | 153       | 5.05%   |
| 2007    | 148       | 4.88%   |
| 2009    | 144       | 4.75%   |
| 2006    | 56        | 1.85%   |
| 2022    | 48        | 1.58%   |
| 2005    | 37        | 1.22%   |
| 2023    | 17        | 0.56%   |
| Unknown | 6         | 0.2%    |
| 2003    | 2         | 0.07%   |
| 2004    | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 3032      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 2679      | 87.78%  |
| Enabled  | 373       | 12.22%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2995      | 98.78%  |
| Yes  | 37        | 1.22%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 894       | 29.24%  |
| 4.01-8.0    | 876       | 28.66%  |
| 8.01-16.0   | 368       | 12.04%  |
| 1.01-2.0    | 327       | 10.7%   |
| 16.01-24.0  | 295       | 9.65%   |
| 2.01-3.0    | 113       | 3.7%    |
| 32.01-64.0  | 85        | 2.78%   |
| 0.51-1.0    | 72        | 2.36%   |
| 64.01-256.0 | 15        | 0.49%   |
| 24.01-32.0  | 12        | 0.39%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1404      | 42.83%  |
| 2.01-3.0   | 923       | 28.16%  |
| 3.01-4.0   | 367       | 11.2%   |
| 0.51-1.0   | 279       | 8.51%   |
| 4.01-8.0   | 245       | 7.47%   |
| 8.01-16.0  | 30        | 0.92%   |
| 0.01-0.5   | 25        | 0.76%   |
| 24.01-32.0 | 3         | 0.09%   |
| 16.01-24.0 | 2         | 0.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2360      | 76.6%   |
| 2      | 633       | 20.55%  |
| 3      | 63        | 2.04%   |
| 0      | 12        | 0.39%   |
| 4      | 8         | 0.26%   |
| 5      | 3         | 0.1%    |
| 8      | 1         | 0.03%   |
| 6      | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1572      | 51.63%  |
| Yes       | 1473      | 48.37%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2490      | 81.93%  |
| No        | 549       | 18.07%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2937      | 96.8%   |
| No        | 97        | 3.2%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1983      | 64.7%   |
| No        | 1082      | 35.3%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 617       | 20.27%  |
| Germany      | 270       | 8.87%   |
| Brazil       | 225       | 7.39%   |
| UK           | 171       | 5.62%   |
| Italy        | 124       | 4.07%   |
| Canada       | 114       | 3.75%   |
| Spain        | 108       | 3.55%   |
| India        | 102       | 3.35%   |
| France       | 97        | 3.19%   |
| Netherlands  | 78        | 2.56%   |
| Poland       | 72        | 2.37%   |
| Mexico       | 67        | 2.2%    |
| Australia    | 53        | 1.74%   |
| Portugal     | 48        | 1.58%   |
| Sweden       | 41        | 1.35%   |
| Czechia      | 41        | 1.35%   |
| Argentina    | 40        | 1.31%   |
| Russia       | 39        | 1.28%   |
| South Africa | 37        | 1.22%   |
| Belgium      | 37        | 1.22%   |
| Austria      | 34        | 1.12%   |
| Turkey       | 33        | 1.08%   |
| Romania      | 33        | 1.08%   |
| Switzerland  | 29        | 0.95%   |
| Indonesia    | 28        | 0.92%   |
| Greece       | 24        | 0.79%   |
| New Zealand  | 21        | 0.69%   |
| Japan        | 21        | 0.69%   |
| Norway       | 19        | 0.62%   |
| Hungary      | 19        | 0.62%   |
| Chile        | 19        | 0.62%   |
| Colombia     | 18        | 0.59%   |
| Egypt        | 16        | 0.53%   |
| Serbia       | 15        | 0.49%   |
| Bulgaria     | 15        | 0.49%   |
| Denmark      | 13        | 0.43%   |
| Ukraine      | 12        | 0.39%   |
| Philippines  | 12        | 0.39%   |
| Ireland      | 12        | 0.39%   |
| Finland      | 11        | 0.36%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Sao Paulo      | 24        | 0.75%   |
| Berlin         | 20        | 0.63%   |
| Vienna         | 19        | 0.6%    |
| Sydney         | 19        | 0.6%    |
| Madrid         | 19        | 0.6%    |
| Munich         | 17        | 0.53%   |
| Rome           | 16        | 0.5%    |
| Johannesburg   | 15        | 0.47%   |
| Milan          | 14        | 0.44%   |
| Athens         | 14        | 0.44%   |
| Paris          | 13        | 0.41%   |
| New York       | 13        | 0.41%   |
| Montreal       | 13        | 0.41%   |
| Mexico City    | 13        | 0.41%   |
| Istanbul       | 13        | 0.41%   |
| Rio de Janeiro | 12        | 0.38%   |
| Hamburg        | 12        | 0.38%   |
| Auckland       | 12        | 0.38%   |
| Prague         | 11        | 0.35%   |
| Moscow         | 11        | 0.35%   |
| Jakarta        | 11        | 0.35%   |
| Dallas         | 11        | 0.35%   |
| Cairo          | 11        | 0.35%   |
| Amsterdam      | 11        | 0.35%   |
| Toronto        | 10        | 0.31%   |
| Stuttgart      | 10        | 0.31%   |
| Stockholm      | 10        | 0.31%   |
| Seattle        | 10        | 0.31%   |
| Buenos Aires   | 10        | 0.31%   |
| Bucharest      | 10        | 0.31%   |
| Bengaluru      | 10        | 0.31%   |
| Warsaw         | 9         | 0.28%   |
| Nairobi        | 9         | 0.28%   |
| Krakow         | 9         | 0.28%   |
| Kolkata        | 9         | 0.28%   |
| Denver         | 9         | 0.28%   |
| Delhi          | 9         | 0.28%   |
| Belgrade       | 9         | 0.28%   |
| Barcelona      | 9         | 0.28%   |
| Valencia       | 8         | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 450       | 551    | 12.7%   |
| WDC                 | 429       | 525    | 12.11%  |
| Samsung Electronics | 399       | 541    | 11.26%  |
| Toshiba             | 361       | 410    | 10.19%  |
| Unknown             | 307       | 419    | 8.67%   |
| SanDisk             | 204       | 243    | 5.76%   |
| Hitachi             | 172       | 200    | 4.86%   |
| Kingston            | 158       | 193    | 4.46%   |
| Crucial             | 117       | 140    | 3.3%    |
| HGST                | 105       | 126    | 2.96%   |
| Intel               | 87        | 109    | 2.46%   |
| SK hynix            | 79        | 92     | 2.23%   |
| Micron Technology   | 59        | 70     | 1.67%   |
| A-DATA Technology   | 45        | 51     | 1.27%   |
| Fujitsu             | 44        | 47     | 1.24%   |
| China               | 43        | 53     | 1.21%   |
| Apple               | 38        | 44     | 1.07%   |
| Intenso             | 27        | 28     | 0.76%   |
| KIOXIA              | 26        | 31     | 0.73%   |
| PNY                 | 21        | 25     | 0.59%   |
| SPCC                | 19        | 25     | 0.54%   |
| Netac               | 17        | 17     | 0.48%   |
| Phison              | 16        | 19     | 0.45%   |
| Patriot             | 16        | 20     | 0.45%   |
| LITEONIT            | 16        | 19     | 0.45%   |
| LITEON              | 16        | 20     | 0.45%   |
| Unknown             | 16        | 18     | 0.45%   |
| Transcend           | 15        | 20     | 0.42%   |
| GOODRAM             | 13        | 14     | 0.37%   |
| Team                | 11        | 12     | 0.31%   |
| JMicron Technology  | 10        | 11     | 0.28%   |
| OCZ                 | 9         | 10     | 0.25%   |
| Silicon Motion      | 8         | 8      | 0.23%   |
| SABRENT             | 8         | 9      | 0.23%   |
| Phison Electronics  | 6         | 6      | 0.17%   |
| Hewlett-Packard     | 6         | 6      | 0.17%   |
| ASMT                | 6         | 6      | 0.17%   |
| Plextor             | 5         | 5      | 0.14%   |
| Lite-On             | 5         | 7      | 0.14%   |
| KingSpec            | 5         | 5      | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                              | 113       | 3.07%   |
| Unknown MMC Card  64GB                              | 77        | 2.09%   |
| Toshiba MQ01ABF050 500GB                            | 49        | 1.33%   |
| Seagate ST1000LM035-1RK172 1TB                      | 49        | 1.33%   |
| Toshiba MQ01ABD100 1TB                              | 41        | 1.12%   |
| Kingston SA400S37240G 240GB SSD                     | 39        | 1.06%   |
| Seagate ST500LT012-1DG142 500GB                     | 38        | 1.03%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 35        | 0.95%   |
| Toshiba MQ04ABF100 1TB                              | 33        | 0.9%    |
| Unknown MMC Card  128GB                             | 32        | 0.87%   |
| Seagate ST9500325AS 500GB                           | 28        | 0.76%   |
| Unknown MMC Card  16GB                              | 27        | 0.73%   |
| Kingston SA400S37480G 480GB SSD                     | 27        | 0.73%   |
| Samsung NVMe SSD Drive 512GB                        | 24        | 0.65%   |
| Kingston SA400S37120G 120GB SSD                     | 22        | 0.6%    |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 21        | 0.57%   |
| Crucial CT240BX500SSD1 240GB                        | 21        | 0.57%   |
| SanDisk NVMe SSD Drive 256GB                        | 20        | 0.54%   |
| HGST HTS725050A7E630 500GB                          | 20        | 0.54%   |
| HGST HTS721010A9E630 1TB                            | 20        | 0.54%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB              | 19        | 0.52%   |
| HGST HTS541010A9E680 1TB                            | 18        | 0.49%   |
| Intel NVMe SSD Drive 512GB                          | 17        | 0.46%   |
| Hitachi HTS545032B9A300 320GB                       | 17        | 0.46%   |
| Crucial CT500MX500SSD1 500GB                        | 17        | 0.46%   |
| Seagate Expansion 1TB                               | 16        | 0.44%   |
| Samsung SSD 850 EVO 500GB                           | 16        | 0.44%   |
| Unknown                                             | 16        | 0.44%   |
| SanDisk NVMe SSD Drive 512GB                        | 15        | 0.41%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 15        | 0.41%   |
| HGST HTS545050A7E680 500GB                          | 15        | 0.41%   |
| Samsung SSD 860 EVO 500GB                           | 14        | 0.38%   |
| Unknown SD/MMC/MS PRO 128GB                         | 13        | 0.35%   |
| Samsung SSD 860 EVO 250GB                           | 13        | 0.35%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 12        | 0.33%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 12        | 0.33%   |
| Samsung HM160HI 160GB                               | 12        | 0.33%   |
| WDC WD10JPVX-60JC3T0 1TB                            | 11        | 0.3%    |
| Toshiba MQ01ABD075 752GB                            | 11        | 0.3%    |
| Seagate ST9320325AS 320GB                           | 11        | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 445       | 542    | 29.26%  |
| WDC                 | 366       | 439    | 24.06%  |
| Toshiba             | 304       | 341    | 19.99%  |
| Hitachi             | 172       | 200    | 11.31%  |
| HGST                | 105       | 126    | 6.9%    |
| Samsung Electronics | 47        | 52     | 3.09%   |
| Fujitsu             | 44        | 47     | 2.89%   |
| Unknown             | 13        | 19     | 0.85%   |
| SABRENT             | 8         | 9      | 0.53%   |
| Apple               | 5         | 5      | 0.33%   |
| IBM/Hitachi         | 4         | 5      | 0.26%   |
| JMicron Technology  | 2         | 2      | 0.13%   |
| USB3.0              | 1         | 1      | 0.07%   |
| SSK                 | 1         | 1      | 0.07%   |
| Pioneer             | 1         | 1      | 0.07%   |
| LaCie               | 1         | 1      | 0.07%   |
| KESU                | 1         | 1      | 0.07%   |
| Intenso             | 1         | 1      | 0.07%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 217       | 303    | 18.79%  |
| Kingston            | 139       | 171    | 12.03%  |
| SanDisk             | 116       | 138    | 10.04%  |
| Crucial             | 115       | 136    | 9.96%   |
| WDC                 | 48        | 63     | 4.16%   |
| China               | 42        | 52     | 3.64%   |
| Intel               | 40        | 46     | 3.46%   |
| A-DATA Technology   | 38        | 44     | 3.29%   |
| Toshiba             | 33        | 37     | 2.86%   |
| SK hynix            | 29        | 33     | 2.51%   |
| Apple               | 28        | 32     | 2.42%   |
| Micron Technology   | 27        | 31     | 2.34%   |
| PNY                 | 21        | 25     | 1.82%   |
| Intenso             | 19        | 19     | 1.65%   |
| SPCC                | 18        | 24     | 1.56%   |
| Netac               | 17        | 17     | 1.47%   |
| Patriot             | 16        | 20     | 1.39%   |
| LITEONIT            | 16        | 19     | 1.39%   |
| LITEON              | 16        | 20     | 1.39%   |
| Transcend           | 15        | 20     | 1.3%    |
| GOODRAM             | 12        | 13     | 1.04%   |
| Team                | 11        | 12     | 0.95%   |
| OCZ                 | 9         | 10     | 0.78%   |
| JMicron Technology  | 6         | 7      | 0.52%   |
| ASMT                | 6         | 6      | 0.52%   |
| Unknown             | 6         | 8      | 0.52%   |
| Plextor             | 5         | 5      | 0.43%   |
| KingSpec            | 5         | 5      | 0.43%   |
| Hewlett-Packard     | 4         | 4      | 0.35%   |
| Apacer              | 4         | 4      | 0.35%   |
| Verbatim            | 3         | 3      | 0.26%   |
| Phison              | 3         | 4      | 0.26%   |
| Mushkin             | 3         | 3      | 0.26%   |
| Lexar               | 3         | 3      | 0.26%   |
| BHT                 | 3         | 4      | 0.26%   |
| Vaseky              | 2         | 3      | 0.17%   |
| TO Exter            | 2         | 3      | 0.17%   |
| Teclast             | 2         | 2      | 0.17%   |
| TCSUNBOW            | 2         | 2      | 0.17%   |
| Leven               | 2         | 2      | 0.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1486      | 1793   | 43.29%  |
| SSD     | 1097      | 1410   | 31.95%  |
| NVMe    | 492       | 642    | 14.33%  |
| MMC     | 307       | 415    | 8.94%   |
| Unknown | 51        | 56     | 1.49%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2419      | 3117   | 72.91%  |
| NVMe | 492       | 642    | 14.83%  |
| MMC  | 307       | 415    | 9.25%   |
| SAS  | 100       | 142    | 3.01%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1909      | 2380   | 74.57%  |
| 0.51-1.0   | 595       | 744    | 23.24%  |
| 1.01-2.0   | 47        | 63     | 1.84%   |
| 4.01-10.0  | 5         | 9      | 0.2%    |
| 3.01-4.0   | 3         | 6      | 0.12%   |
| 2.01-3.0   | 1         | 1      | 0.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 1109      | 35.53%  |
| 251-500        | 801       | 25.66%  |
| 501-1000       | 388       | 12.43%  |
| 51-100         | 341       | 10.93%  |
| 21-50          | 208       | 6.66%   |
| 1001-2000      | 99        | 3.17%   |
| 1-20           | 97        | 3.11%   |
| Unknown        | 29        | 0.93%   |
| More than 3000 | 26        | 0.83%   |
| 2001-3000      | 23        | 0.74%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1605      | 49.49%  |
| 21-50          | 788       | 24.3%   |
| 51-100         | 330       | 10.18%  |
| 101-250        | 284       | 8.76%   |
| 251-500        | 124       | 3.82%   |
| 501-1000       | 52        | 1.6%    |
| Unknown        | 29        | 0.89%   |
| 1001-2000      | 16        | 0.49%   |
| More than 3000 | 11        | 0.34%   |
| 2001-3000      | 4         | 0.12%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                           | 3         | 3      | 4.29%   |
| Seagate ST9500325AS 500GB                        | 3         | 3      | 4.29%   |
| Toshiba MQ02ABD100H 1TB                          | 2         | 2      | 2.86%   |
| SK hynix BC711 HFM512GD3JX013N 512GB             | 2         | 2      | 2.86%   |
| Seagate ST500LT012-9WS142 500GB                  | 2         | 2      | 2.86%   |
| Seagate ST500LT012-1DG142 500GB                  | 2         | 2      | 2.86%   |
| Seagate ST1000LM035-1RK172 1TB                   | 2         | 2      | 2.86%   |
| HGST HTS545050A7E680 500GB                       | 2         | 2      | 2.86%   |
| HGST HTS545050A7E380 500GB                       | 2         | 3      | 2.86%   |
| WDC WD6400BEVT-22A0RT0 640GB                     | 1         | 1      | 1.43%   |
| WDC WD5000LPVX-75V0TT0 500GB                     | 1         | 1      | 1.43%   |
| WDC WD5000BEVT-24A0RT0 500GB                     | 1         | 1      | 1.43%   |
| WDC WD3200BPVT-55ZEST0 320GB                     | 1         | 1      | 1.43%   |
| WDC WD1200BEVS-60UST0 120GB                      | 1         | 1      | 1.43%   |
| WDC WD10SPZX-75Z10T2 1TB                         | 1         | 1      | 1.43%   |
| WDC WD10JPVX-22JC3T0 1TB                         | 1         | 1      | 1.43%   |
| WDC WD10JPVT-55A1YT0 1TB                         | 1         | 1      | 1.43%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD             | 1         | 1      | 1.43%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD         | 1         | 1      | 1.43%   |
| Toshiba MQ01ABF050 500GB                         | 1         | 1      | 1.43%   |
| Toshiba MQ01ABD075 752GB                         | 1         | 1      | 1.43%   |
| Toshiba MK5061GSY 500GB                          | 1         | 1      | 1.43%   |
| Toshiba MK2046GSX 200GB                          | 1         | 1      | 1.43%   |
| Teclast 128GB NS550-2242 SSD                     | 1         | 1      | 1.43%   |
| Seagate ST9500420AS 500GB                        | 1         | 1      | 1.43%   |
| Seagate ST9320325AS 320GB                        | 1         | 1      | 1.43%   |
| Seagate ST9320310AS 320GB                        | 1         | 1      | 1.43%   |
| Seagate ST9250315AS 250GB                        | 1         | 1      | 1.43%   |
| Seagate ST9200420ASG 200GB                       | 1         | 1      | 1.43%   |
| Seagate ST9160411ASG 160GB                       | 1         | 1      | 1.43%   |
| Seagate ST9160314AS 160GB                        | 1         | 1      | 1.43%   |
| Seagate ST9120822AS 120GB                        | 1         | 1      | 1.43%   |
| Seagate ST500LM000-SSHD-8GB                      | 1         | 1      | 1.43%   |
| Seagate ST320LT007-9ZV142 320GB                  | 1         | 1      | 1.43%   |
| Seagate ST1000LX015-1U7172 1TB                   | 1         | 1      | 1.43%   |
| Seagate ST1000LM048-2E7172 1TB                   | 1         | 1      | 1.43%   |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 1         | 1      | 1.43%   |
| Samsung Electronics MZHPV256HDGL-00000 256GB SSD | 1         | 1      | 1.43%   |
| Samsung Electronics MMCRE64G8MPP-0VA 64GB SSD    | 1         | 1      | 1.43%   |
| Samsung Electronics HM160JI 160GB                | 1         | 1      | 1.43%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 22        | 22     | 31.43%  |
| Toshiba             | 11        | 11     | 15.71%  |
| WDC                 | 8         | 8      | 11.43%  |
| HGST                | 7         | 8      | 10%     |
| Hitachi             | 5         | 5      | 7.14%   |
| Samsung Electronics | 4         | 4      | 5.71%   |
| Kingston            | 3         | 3      | 4.29%   |
| SK hynix            | 2         | 2      | 2.86%   |
| Teclast             | 1         | 1      | 1.43%   |
| POLION              | 1         | 1      | 1.43%   |
| Micron Technology   | 1         | 1      | 1.43%   |
| LITEONIT            | 1         | 1      | 1.43%   |
| Intel               | 1         | 1      | 1.43%   |
| Hewlett-Packard     | 1         | 1      | 1.43%   |
| Drevo               | 1         | 1      | 1.43%   |
| Unknown             | 1         | 1      | 1.43%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 22        | 22     | 41.51%  |
| Toshiba             | 9         | 9      | 16.98%  |
| WDC                 | 8         | 8      | 15.09%  |
| HGST                | 7         | 8      | 13.21%  |
| Hitachi             | 5         | 5      | 9.43%   |
| Samsung Electronics | 2         | 2      | 3.77%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 53        | 54     | 75.71%  |
| SSD  | 15        | 15     | 21.43%  |
| NVMe | 2         | 2      | 2.86%   |

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
| Detected | 2741      | 3916   | 88.94%  |
| Works    | 269       | 326    | 8.73%   |
| Malfunc  | 69        | 71     | 2.24%   |
| Failed   | 2         | 2      | 0.06%   |
| Fixed    | 1         | 1      | 0.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2213      | 69.05%  |
| AMD                              | 388       | 12.11%  |
| Samsung Electronics              | 164       | 5.12%   |
| SanDisk                          | 93        | 2.9%    |
| Nvidia                           | 51        | 1.59%   |
| SK hynix                         | 48        | 1.5%    |
| Micron Technology                | 33        | 1.03%   |
| Silicon Integrated Systems [SiS] | 31        | 0.97%   |
| Toshiba America Info Systems     | 26        | 0.81%   |
| KIOXIA                           | 26        | 0.81%   |
| Kingston Technology Company      | 23        | 0.72%   |
| Phison Electronics               | 19        | 0.59%   |
| VIA Technologies                 | 12        | 0.37%   |
| Silicon Motion                   | 11        | 0.34%   |
| ADATA Technology                 | 10        | 0.31%   |
| Micron/Crucial Technology        | 7         | 0.22%   |
| Marvell Technology Group         | 6         | 0.19%   |
| Union Memory (Shenzhen)          | 5         | 0.16%   |
| MAXIO Technology (Hangzhou)      | 5         | 0.16%   |
| Lite-On Technology               | 5         | 0.16%   |
| JMicron Technology               | 5         | 0.16%   |
| Realtek Semiconductor            | 4         | 0.12%   |
| ASMedia Technology               | 4         | 0.12%   |
| Apple                            | 4         | 0.12%   |
| Yangtze Memory Technologies      | 2         | 0.06%   |
| Solid State Storage Technology   | 2         | 0.06%   |
| Silicon Image                    | 2         | 0.06%   |
| Lenovo                           | 2         | 0.06%   |
| Shenzhen Longsys Electronics     | 1         | 0.03%   |
| Seagate Technology               | 1         | 0.03%   |
| INNOGRIT                         | 1         | 0.03%   |
| Biwin Storage Technology         | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 295       | 8.22%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 249       | 6.94%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 212       | 5.91%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 202       | 5.63%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 176       | 4.91%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 160       | 4.46%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 123       | 3.43%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 120       | 3.34%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 102       | 2.84%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 101       | 2.81%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 82        | 2.29%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 67        | 1.87%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 64        | 1.78%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 55        | 1.53%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 54        | 1.51%   |
| Intel Volume Management Device NVMe RAID Controller                              | 53        | 1.48%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 52        | 1.45%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 51        | 1.42%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 49        | 1.37%   |
| Samsung NVMe SSD Controller 980                                                  | 46        | 1.28%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 45        | 1.25%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 41        | 1.14%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 38        | 1.06%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 37        | 1.03%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 37        | 1.03%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 32        | 0.89%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 31        | 0.86%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 30        | 0.84%   |
| Intel Tiger Lake-LP SATA Controller                                              | 29        | 0.81%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 27        | 0.75%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 24        | 0.67%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 24        | 0.67%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 24        | 0.67%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 24        | 0.67%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 23        | 0.64%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 23        | 0.64%   |
| Intel Comet Lake SATA AHCI Controller                                            | 22        | 0.61%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 21        | 0.59%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 19        | 0.53%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                         | 19        | 0.53%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 2208      | 64.94%  |
| NVMe | 493       | 14.5%   |
| IDE  | 460       | 13.53%  |
| RAID | 239       | 7.03%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 2548      | 84.04%  |
| AMD          | 483       | 15.93%  |
| CentaurHauls | 1         | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 38        | 1.25%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 37        | 1.22%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 35        | 1.15%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 35        | 1.15%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 30        | 0.99%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 30        | 0.99%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 29        | 0.96%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 28        | 0.92%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 26        | 0.86%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 26        | 0.86%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 26        | 0.86%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 26        | 0.86%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 26        | 0.86%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 25        | 0.82%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 24        | 0.79%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 24        | 0.79%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 22        | 0.72%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 22        | 0.72%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 22        | 0.72%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 22        | 0.72%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 22        | 0.72%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 20        | 0.66%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 20        | 0.66%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 20        | 0.66%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 19        | 0.63%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 19        | 0.63%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 19        | 0.63%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 19        | 0.63%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 19        | 0.63%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 19        | 0.63%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 19        | 0.63%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 19        | 0.63%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 18        | 0.59%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 18        | 0.59%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 18        | 0.59%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 17        | 0.56%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 17        | 0.56%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 17        | 0.56%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 17        | 0.56%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 16        | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 651       | 21.45%  |
| Intel Core i7           | 452       | 14.89%  |
| Intel Core i3           | 298       | 9.82%   |
| Intel Celeron           | 266       | 8.76%   |
| Intel Core 2 Duo        | 253       | 8.34%   |
| Intel Atom              | 165       | 5.44%   |
| Other                   | 123       | 4.05%   |
| Intel Pentium           | 101       | 3.33%   |
| AMD Ryzen 5             | 74        | 2.44%   |
| AMD Ryzen 7             | 52        | 1.71%   |
| AMD A6                  | 50        | 1.65%   |
| Intel Pentium Dual-Core | 44        | 1.45%   |
| Intel Genuine           | 42        | 1.38%   |
| AMD A4                  | 41        | 1.35%   |
| Intel Pentium Dual      | 32        | 1.05%   |
| Intel Core 2            | 27        | 0.89%   |
| Intel Pentium M         | 26        | 0.86%   |
| AMD A8                  | 25        | 0.82%   |
| AMD A10                 | 25        | 0.82%   |
| Intel Celeron M         | 24        | 0.79%   |
| AMD Ryzen 3             | 24        | 0.79%   |
| AMD E1                  | 21        | 0.69%   |
| AMD E                   | 20        | 0.66%   |
| AMD Turion 64 X2 Mobile | 17        | 0.56%   |
| Intel Core M            | 12        | 0.4%    |
| Intel Pentium Silver    | 10        | 0.33%   |
| Intel Celeron Dual-Core | 9         | 0.3%    |
| AMD Turion 64 Mobile    | 9         | 0.3%    |
| AMD Ryzen 9             | 9         | 0.3%    |
| AMD E2                  | 9         | 0.3%    |
| AMD Athlon II           | 9         | 0.3%    |
| AMD Athlon 64 X2        | 9         | 0.3%    |
| Intel Core Duo          | 8         | 0.26%   |
| AMD Sempron             | 7         | 0.23%   |
| AMD Mobile Sempron      | 7         | 0.23%   |
| AMD Athlon              | 7         | 0.23%   |
| AMD C-50                | 6         | 0.2%    |
| AMD Athlon X2           | 6         | 0.2%    |
| Intel Core m5           | 5         | 0.16%   |
| AMD C-60                | 5         | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1925      | 63.43%  |
| 4      | 745       | 24.55%  |
| 1      | 188       | 6.19%   |
| 6      | 88        | 2.9%    |
| 8      | 71        | 2.34%   |
| 10     | 7         | 0.23%   |
| 14     | 5         | 0.16%   |
| 16     | 2         | 0.07%   |
| 3      | 2         | 0.07%   |
| 24     | 1         | 0.03%   |
| 12     | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 3032      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1783      | 58.81%  |
| 1      | 1249      | 41.19%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2912      | 96.01%  |
| 32-bit         | 119       | 3.92%   |
| Unknown        | 2         | 0.07%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x206a7    | 268       | 8.71%   |
| Unknown    | 254       | 8.26%   |
| 0x306a9    | 224       | 7.28%   |
| 0x1067a    | 164       | 5.33%   |
| 0x40651    | 135       | 4.39%   |
| 0x20655    | 108       | 3.51%   |
| 0x406e3    | 104       | 3.38%   |
| 0x306d4    | 100       | 3.25%   |
| 0x6fd      | 91        | 2.96%   |
| 0x30678    | 83        | 2.7%    |
| 0x306c3    | 81        | 2.63%   |
| 0x806e9    | 78        | 2.54%   |
| 0x806ea    | 71        | 2.31%   |
| 0x806c1    | 67        | 2.18%   |
| 0x406c4    | 66        | 2.15%   |
| 0x806ec    | 58        | 1.89%   |
| 0x10676    | 53        | 1.72%   |
| 0x906ea    | 43        | 1.4%    |
| 0x506c9    | 42        | 1.37%   |
| 0x406c3    | 42        | 1.37%   |
| 0x706e5    | 40        | 1.3%    |
| 0x20652    | 40        | 1.3%    |
| 0x706a8    | 39        | 1.27%   |
| 0x906e9    | 37        | 1.2%    |
| 0x106ca    | 35        | 1.14%   |
| 0x06006705 | 34        | 1.11%   |
| 0x08108109 | 32        | 1.04%   |
| 0x6e8      | 30        | 0.98%   |
| 0x6d8      | 30        | 0.98%   |
| 0x05000119 | 26        | 0.85%   |
| 0x07030105 | 25        | 0.81%   |
| 0x0700010f | 25        | 0.81%   |
| 0x6f6      | 24        | 0.78%   |
| 0x106c2    | 24        | 0.78%   |
| 0x08108102 | 24        | 0.78%   |
| 0x6fb      | 22        | 0.72%   |
| 0x06001119 | 22        | 0.72%   |
| 0x706a1    | 21        | 0.68%   |
| 0x0a50000c | 21        | 0.68%   |
| 0xa0652    | 20        | 0.65%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 332       | 10.95%  |
| SandyBridge      | 274       | 9.04%   |
| IvyBridge        | 235       | 7.75%   |
| Haswell          | 234       | 7.72%   |
| Penryn           | 229       | 7.55%   |
| Silvermont       | 221       | 7.29%   |
| Core             | 184       | 6.07%   |
| Westmere         | 155       | 5.11%   |
| Skylake          | 126       | 4.16%   |
| Broadwell        | 100       | 3.3%    |
| P6               | 84        | 2.77%   |
| TigerLake        | 76        | 2.51%   |
| Bonnell          | 70        | 2.31%   |
| Goldmont plus    | 63        | 2.08%   |
| Excavator        | 63        | 2.08%   |
| Zen+             | 59        | 1.95%   |
| IceLake          | 52        | 1.72%   |
| K8 Hammer        | 48        | 1.58%   |
| Goldmont         | 44        | 1.45%   |
| Puma             | 41        | 1.35%   |
| Bobcat           | 39        | 1.29%   |
| Unknown          | 37        | 1.22%   |
| Zen 2            | 36        | 1.19%   |
| Zen 3            | 33        | 1.09%   |
| Jaguar           | 31        | 1.02%   |
| Piledriver       | 26        | 0.86%   |
| CometLake        | 25        | 0.82%   |
| K10              | 22        | 0.73%   |
| K10 Llano        | 20        | 0.66%   |
| K8 & K10 hybrid  | 17        | 0.56%   |
| Zen              | 14        | 0.46%   |
| Alderlake Hybrid | 14        | 0.46%   |
| Nehalem          | 11        | 0.36%   |
| Tremont          | 7         | 0.23%   |
| Steamroller      | 6         | 0.2%    |
| NetBurst         | 4         | 0.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2223      | 62.39%  |
| AMD                              | 676       | 18.97%  |
| Nvidia                           | 625       | 17.54%  |
| Silicon Integrated Systems [SiS] | 28        | 0.79%   |
| VIA Technologies                 | 11        | 0.31%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 245       | 6.49%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 223       | 5.91%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 140       | 3.71%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 139       | 3.68%   |
| Intel Core Processor Integrated Graphics Controller                                      | 115       | 3.05%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 114       | 3.02%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 107       | 2.83%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 95        | 2.52%   |
| Intel HD Graphics 620                                                                    | 83        | 2.2%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 81        | 2.15%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 81        | 2.15%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 79        | 2.09%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 75        | 1.99%   |
| Intel HD Graphics 5500                                                                   | 71        | 1.88%   |
| Intel UHD Graphics 620                                                                   | 70        | 1.85%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 60        | 1.59%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 60        | 1.59%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 56        | 1.48%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 50        | 1.32%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 49        | 1.3%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 44        | 1.17%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 43        | 1.14%   |
| Intel HD Graphics 500                                                                    | 36        | 0.95%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 36        | 0.95%   |
| AMD Renoir                                                                               | 36        | 0.95%   |
| Intel HD Graphics 630                                                                    | 34        | 0.9%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 31        | 0.82%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 30        | 0.79%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 29        | 0.77%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 28        | 0.74%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 27        | 0.72%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 27        | 0.72%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 26        | 0.69%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 26        | 0.69%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 25        | 0.66%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 24        | 0.64%   |
| AMD Lucienne                                                                             | 22        | 0.58%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 21        | 0.56%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 21        | 0.56%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 20        | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 1724      | 56.77%  |
| 1 x AMD        | 470       | 15.48%  |
| Intel + Nvidia | 371       | 12.22%  |
| 1 x Nvidia     | 211       | 6.95%   |
| Intel + AMD    | 122       | 4.02%   |
| 2 x AMD        | 48        | 1.58%   |
| AMD + Nvidia   | 37        | 1.22%   |
| 1 x SiS        | 28        | 0.92%   |
| 1 x VIA        | 11        | 0.36%   |
| Other          | 8         | 0.26%   |
| 2 x Nvidia     | 7         | 0.23%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 2644      | 86.8%   |
| Proprietary | 300       | 9.85%   |
| Unknown     | 102       | 3.35%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2008      | 65.36%  |
| 0.01-0.5   | 485       | 15.79%  |
| 1.01-2.0   | 258       | 8.4%    |
| 0.51-1.0   | 187       | 6.09%   |
| 3.01-4.0   | 85        | 2.77%   |
| 5.01-6.0   | 20        | 0.65%   |
| 7.01-8.0   | 16        | 0.52%   |
| 2.01-3.0   | 12        | 0.39%   |
| 8.01-16.0  | 1         | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 596       | 19.38%  |
| LG Display              | 438       | 14.24%  |
| Samsung Electronics     | 410       | 13.33%  |
| Chimei Innolux          | 392       | 12.75%  |
| BOE                     | 369       | 12%     |
| Chi Mei Optoelectronics | 119       | 3.87%   |
| Apple                   | 89        | 2.89%   |
| LG Philips              | 77        | 2.5%    |
| Lenovo                  | 54        | 1.76%   |
| Sharp                   | 47        | 1.53%   |
| Goldstar                | 46        | 1.5%    |
| Dell                    | 43        | 1.4%    |
| InfoVision              | 35        | 1.14%   |
| PANDA                   | 31        | 1.01%   |
| CPT                     | 22        | 0.72%   |
| HannStar                | 18        | 0.59%   |
| Toshiba                 | 17        | 0.55%   |
| Hewlett-Packard         | 17        | 0.55%   |
| Sony                    | 15        | 0.49%   |
| Acer                    | 15        | 0.49%   |
| Philips                 | 12        | 0.39%   |
| Quanta Display          | 11        | 0.36%   |
| BenQ                    | 11        | 0.36%   |
| Vizio                   | 10        | 0.33%   |
| LGD                     | 10        | 0.33%   |
| InnoLux Display         | 10        | 0.33%   |
| AOC                     | 10        | 0.33%   |
| Seiko/Epson             | 9         | 0.29%   |
| Panasonic               | 8         | 0.26%   |
| Ancor Communications    | 8         | 0.26%   |
| Eizo                    | 6         | 0.2%    |
| Iiyama                  | 5         | 0.16%   |
| BOE Technology Group    | 5         | 0.16%   |
| ASUSTek Computer        | 5         | 0.16%   |
| Unknown                 | 5         | 0.16%   |
| Unknown                 | 4         | 0.13%   |
| SLD                     | 4         | 0.13%   |
| KDC                     | 4         | 0.13%   |
| IBM                     | 4         | 0.13%   |
| ViewSonic               | 3         | 0.1%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 34        | 1.1%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 25        | 0.81%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 22        | 0.71%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 20        | 0.64%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 18        | 0.58%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 18        | 0.58%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 17        | 0.55%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 17        | 0.55%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 16        | 0.52%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 16        | 0.52%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 15        | 0.48%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 15        | 0.48%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 14        | 0.45%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 14        | 0.45%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 13        | 0.42%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 13        | 0.42%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 13        | 0.42%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 12        | 0.39%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch                  | 12        | 0.39%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 12        | 0.39%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 11        | 0.35%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 11        | 0.35%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 239x134mm 10.8-inch    | 10        | 0.32%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 10        | 0.32%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch          | 10        | 0.32%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 10        | 0.32%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch     | 9         | 0.29%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 9         | 0.29%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 9         | 0.29%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 9         | 0.29%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 9         | 0.29%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 9         | 0.29%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 9         | 0.29%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 9         | 0.29%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 8         | 0.26%   |
| InfoVision LCD Monitor IVO03F4 1366x768 344x193mm 15.5-inch              | 8         | 0.26%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch          | 8         | 0.26%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 8         | 0.26%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 8         | 0.26%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch          | 8         | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 1262      | 42.08%  |
| 1920x1080 (FHD)    | 833       | 27.78%  |
| 1280x800 (WXGA)    | 242       | 8.07%   |
| 1600x900 (HD+)     | 195       | 6.5%    |
| 1440x900 (WXGA+)   | 83        | 2.77%   |
| 3840x2160 (4K)     | 60        | 2%      |
| 1024x600           | 47        | 1.57%   |
| 1920x1200 (WUXGA)  | 33        | 1.1%    |
| 1680x1050 (WSXGA+) | 32        | 1.07%   |
| 2560x1600          | 26        | 0.87%   |
| 2560x1440 (QHD)    | 22        | 0.73%   |
| 1360x768           | 14        | 0.47%   |
| 1280x1024 (SXGA)   | 14        | 0.47%   |
| 2880x1800          | 12        | 0.4%    |
| 2560x1080          | 11        | 0.37%   |
| 2160x1440          | 11        | 0.37%   |
| 3200x1800 (QHD+)   | 10        | 0.33%   |
| 1024x768 (XGA)     | 10        | 0.33%   |
| Unknown            | 9         | 0.3%    |
| 2256x1504          | 8         | 0.27%   |
| 1280x768           | 8         | 0.27%   |
| 1920x540           | 6         | 0.2%    |
| 3840x2400          | 5         | 0.17%   |
| 3440x1440          | 5         | 0.17%   |
| 3840x1080          | 4         | 0.13%   |
| 1680x945           | 4         | 0.13%   |
| 1400x1050          | 4         | 0.13%   |
| 1920x515           | 3         | 0.1%    |
| 1024x576           | 3         | 0.1%    |
| 5760x1080          | 2         | 0.07%   |
| 3600x1080          | 2         | 0.07%   |
| 2880x1920          | 2         | 0.07%   |
| 2304x1440          | 2         | 0.07%   |
| 2288x1287          | 2         | 0.07%   |
| 1280x720 (HD)      | 2         | 0.07%   |
| 5760x2160          | 1         | 0.03%   |
| 4480x1600          | 1         | 0.03%   |
| 3840x1200          | 1         | 0.03%   |
| 3072x1920          | 1         | 0.03%   |
| 3000x2000          | 1         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1351      | 43.99%  |
| 13      | 418       | 13.61%  |
| 14      | 360       | 11.72%  |
| 17      | 251       | 8.17%   |
| 11      | 116       | 3.78%   |
| 12      | 85        | 2.77%   |
| Unknown | 71        | 2.31%   |
| 10      | 58        | 1.89%   |
| 24      | 48        | 1.56%   |
| 27      | 46        | 1.5%    |
| 23      | 32        | 1.04%   |
| 18      | 30        | 0.98%   |
| 21      | 29        | 0.94%   |
| 16      | 22        | 0.72%   |
| 31      | 20        | 0.65%   |
| 34      | 19        | 0.62%   |
| 19      | 14        | 0.46%   |
| 20      | 12        | 0.39%   |
| 22      | 11        | 0.36%   |
| 72      | 9         | 0.29%   |
| 54      | 9         | 0.29%   |
| 40      | 7         | 0.23%   |
| 84      | 6         | 0.2%    |
| 8       | 5         | 0.16%   |
| 32      | 4         | 0.13%   |
| 25      | 4         | 0.13%   |
| 74      | 3         | 0.1%    |
| 52      | 3         | 0.1%    |
| 49      | 3         | 0.1%    |
| 26      | 3         | 0.1%    |
| 58      | 2         | 0.07%   |
| 48      | 2         | 0.07%   |
| 46      | 2         | 0.07%   |
| 37      | 2         | 0.07%   |
| 36      | 2         | 0.07%   |
| 29      | 2         | 0.07%   |
| 86      | 1         | 0.03%   |
| 65      | 1         | 0.03%   |
| 64      | 1         | 0.03%   |
| 59      | 1         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 1913      | 62.5%   |
| 201-300     | 441       | 14.41%  |
| 351-400     | 303       | 9.9%    |
| 501-600     | 124       | 4.05%   |
| 401-500     | 94        | 3.07%   |
| Unknown     | 71        | 2.32%   |
| 601-700     | 27        | 0.88%   |
| 701-800     | 26        | 0.85%   |
| 1001-1500   | 26        | 0.85%   |
| 1501-2000   | 18        | 0.59%   |
| 801-900     | 10        | 0.33%   |
| 101-200     | 5         | 0.16%   |
| 901-1000    | 3         | 0.1%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 2292      | 80.42%  |
| 16/10   | 420       | 14.74%  |
| Unknown | 54        | 1.89%   |
| 3/2     | 26        | 0.91%   |
| 4/3     | 19        | 0.67%   |
| 21/9    | 17        | 0.6%    |
| 5/4     | 13        | 0.46%   |
| 32/9    | 3         | 0.11%   |
| 3.73    | 3         | 0.11%   |
| 0.62    | 2         | 0.07%   |
| 0.56    | 1         | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1349      | 43.98%  |
| 81-90          | 650       | 21.19%  |
| 121-130        | 183       | 5.97%   |
| 71-80          | 122       | 3.98%   |
| 51-60          | 116       | 3.78%   |
| 201-250        | 99        | 3.23%   |
| 61-70          | 83        | 2.71%   |
| Unknown        | 71        | 2.31%   |
| 41-50          | 58        | 1.89%   |
| 131-140        | 58        | 1.89%   |
| 301-350        | 48        | 1.57%   |
| 351-500        | 44        | 1.43%   |
| More than 1000 | 41        | 1.34%   |
| 151-200        | 39        | 1.27%   |
| 141-150        | 38        | 1.24%   |
| 501-1000       | 20        | 0.65%   |
| 111-120        | 17        | 0.55%   |
| 251-300        | 13        | 0.42%   |
| 91-100         | 13        | 0.42%   |
| 1-40           | 5         | 0.16%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 1325      | 43.85%  |
| 121-160       | 892       | 29.52%  |
| 51-100        | 509       | 16.84%  |
| 161-240       | 138       | 4.57%   |
| Unknown       | 71        | 2.35%   |
| 1-50          | 45        | 1.49%   |
| More than 240 | 42        | 1.39%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 2637      | 85.48%  |
| 2     | 319       | 10.34%  |
| 0     | 106       | 3.44%   |
| 3     | 20        | 0.65%   |
| 4     | 2         | 0.06%   |
| 5     | 1         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1521      | 30.91%  |
| Intel                             | 1281      | 26.04%  |
| Qualcomm Atheros                  | 824       | 16.75%  |
| Broadcom                          | 494       | 10.04%  |
| Broadcom Limited                  | 159       | 3.23%   |
| Marvell Technology Group          | 93        | 1.89%   |
| Ralink                            | 61        | 1.24%   |
| Nvidia                            | 45        | 0.91%   |
| TP-Link                           | 34        | 0.69%   |
| MediaTek                          | 31        | 0.63%   |
| Silicon Integrated Systems [SiS]  | 29        | 0.59%   |
| Ralink Technology                 | 27        | 0.55%   |
| Dell                              | 26        | 0.53%   |
| ASIX Electronics                  | 26        | 0.53%   |
| Samsung Electronics               | 25        | 0.51%   |
| JMicron Technology                | 24        | 0.49%   |
| Xiaomi                            | 16        | 0.33%   |
| Sierra Wireless                   | 16        | 0.33%   |
| Hewlett-Packard                   | 15        | 0.3%    |
| DisplayLink                       | 12        | 0.24%   |
| Qualcomm Atheros Communications   | 11        | 0.22%   |
| Huawei Technologies               | 11        | 0.22%   |
| VIA Technologies                  | 10        | 0.2%    |
| Ericsson Business Mobile Networks | 10        | 0.2%    |
| NetGear                           | 9         | 0.18%   |
| ASUSTek Computer                  | 9         | 0.18%   |
| OPPO Electronics                  | 8         | 0.16%   |
| Edimax Technology                 | 8         | 0.16%   |
| AMD                               | 8         | 0.16%   |
| Qualcomm                          | 6         | 0.12%   |
| Motorola PCS                      | 6         | 0.12%   |
| Attansic Technology               | 6         | 0.12%   |
| OnePlus Technology (Shenzhen)     | 4         | 0.08%   |
| Google                            | 4         | 0.08%   |
| D-Link System                     | 4         | 0.08%   |
| D-Link                            | 4         | 0.08%   |
| T & A Mobile Phones               | 3         | 0.06%   |
| Linksys                           | 3         | 0.06%   |
| Belkin Components                 | 3         | 0.06%   |
| ZyDAS                             | 2         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 764       | 13.06%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 419       | 7.16%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 146       | 2.5%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 135       | 2.31%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 123       | 2.1%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 115       | 1.97%   |
| Intel Wireless 7260                                                     | 113       | 1.93%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 110       | 1.88%   |
| Intel Wireless 7265                                                     | 81        | 1.38%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 80        | 1.37%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 79        | 1.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 77        | 1.32%   |
| Intel Wireless 8265 / 8275                                              | 71        | 1.21%   |
| Broadcom BCM43142 802.11b/g/n                                           | 70        | 1.2%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 67        | 1.15%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 64        | 1.09%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 61        | 1.04%   |
| Intel Wireless 8260                                                     | 57        | 0.97%   |
| Intel Wireless 3165                                                     | 57        | 0.97%   |
| Intel Wi-Fi 6 AX200                                                     | 56        | 0.96%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 53        | 0.91%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 52        | 0.89%   |
| Intel WiFi Link 5100                                                    | 51        | 0.87%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 49        | 0.84%   |
| Intel Wi-Fi 6 AX201                                                     | 49        | 0.84%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 44        | 0.75%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 39        | 0.67%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 37        | 0.63%   |
| Intel Wireless 3160                                                     | 36        | 0.62%   |
| Intel Centrino Ultimate-N 6300                                          | 36        | 0.62%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 35        | 0.6%    |
| Intel Ethernet Connection I218-LM                                       | 35        | 0.6%    |
| Intel Ethernet Connection I217-LM                                       | 35        | 0.6%    |
| Broadcom BCM4311 802.11b/g WLAN                                         | 35        | 0.6%    |
| Intel 82567LM Gigabit Network Connection                                | 34        | 0.58%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 34        | 0.58%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 33        | 0.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 33        | 0.56%   |
| Intel 82577LM Gigabit Network Connection                                | 33        | 0.56%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 31        | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1198      | 38.08%  |
| Qualcomm Atheros                | 698       | 22.19%  |
| Realtek Semiconductor           | 524       | 16.66%  |
| Broadcom                        | 379       | 12.05%  |
| Broadcom Limited                | 110       | 3.5%    |
| Ralink                          | 61        | 1.94%   |
| Ralink Technology               | 27        | 0.86%   |
| TP-Link                         | 26        | 0.83%   |
| MediaTek                        | 26        | 0.83%   |
| Sierra Wireless                 | 16        | 0.51%   |
| Dell                            | 12        | 0.38%   |
| Qualcomm Atheros Communications | 11        | 0.35%   |
| NetGear                         | 9         | 0.29%   |
| Edimax Technology               | 8         | 0.25%   |
| ASUSTek Computer                | 8         | 0.25%   |
| D-Link System                   | 4         | 0.13%   |
| D-Link                          | 4         | 0.13%   |
| Linksys                         | 3         | 0.1%    |
| Hewlett-Packard                 | 3         | 0.1%    |
| Belkin Components               | 3         | 0.1%    |
| ZyDAS                           | 2         | 0.06%   |
| Micro Star International        | 2         | 0.06%   |
| ZyXEL Communications            | 1         | 0.03%   |
| Xiaomi                          | 1         | 0.03%   |
| TRENDnet                        | 1         | 0.03%   |
| Tenda                           | 1         | 0.03%   |
| Sitecom Europe                  | 1         | 0.03%   |
| Qualcomm                        | 1         | 0.03%   |
| Qcom                            | 1         | 0.03%   |
| Mercucys                        | 1         | 0.03%   |
| Lite-On Technology              | 1         | 0.03%   |
| IMC Networks                    | 1         | 0.03%   |
| Fibocom                         | 1         | 0.03%   |
| Askey Computer                  | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 146       | 4.6%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 135       | 4.25%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 115       | 3.62%   |
| Intel Wireless 7260                                                     | 113       | 3.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 110       | 3.47%   |
| Intel Wireless 7265                                                     | 81        | 2.55%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 80        | 2.52%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 79        | 2.49%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 77        | 2.43%   |
| Intel Wireless 8265 / 8275                                              | 71        | 2.24%   |
| Broadcom BCM43142 802.11b/g/n                                           | 70        | 2.21%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 67        | 2.11%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 64        | 2.02%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 61        | 1.92%   |
| Intel Wireless 8260                                                     | 57        | 1.8%    |
| Intel Wireless 3165                                                     | 57        | 1.8%    |
| Intel Wi-Fi 6 AX200                                                     | 56        | 1.76%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 53        | 1.67%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 52        | 1.64%   |
| Intel WiFi Link 5100                                                    | 51        | 1.61%   |
| Intel Wi-Fi 6 AX201                                                     | 49        | 1.54%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 44        | 1.39%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 39        | 1.23%   |
| Intel Wireless 3160                                                     | 36        | 1.13%   |
| Intel Centrino Ultimate-N 6300                                          | 36        | 1.13%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 35        | 1.1%    |
| Broadcom BCM4311 802.11b/g WLAN                                         | 35        | 1.1%    |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 34        | 1.07%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 33        | 1.04%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 31        | 0.98%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 30        | 0.95%   |
| Realtek 802.11n WLAN Adapter                                            | 29        | 0.91%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 28        | 0.88%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 28        | 0.88%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 26        | 0.82%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 25        | 0.79%   |
| Intel Centrino Advanced-N 6235                                          | 25        | 0.79%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 24        | 0.76%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 24        | 0.76%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 24        | 0.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1294      | 50.29%  |
| Intel                                  | 489       | 19.01%  |
| Qualcomm Atheros                       | 214       | 8.32%   |
| Broadcom                               | 175       | 6.8%    |
| Marvell Technology Group               | 93        | 3.61%   |
| Broadcom Limited                       | 54        | 2.1%    |
| Nvidia                                 | 45        | 1.75%   |
| Silicon Integrated Systems [SiS]       | 27        | 1.05%   |
| ASIX Electronics                       | 26        | 1.01%   |
| Samsung Electronics                    | 25        | 0.97%   |
| JMicron Technology                     | 24        | 0.93%   |
| Xiaomi                                 | 15        | 0.58%   |
| DisplayLink                            | 12        | 0.47%   |
| VIA Technologies                       | 10        | 0.39%   |
| TP-Link                                | 8         | 0.31%   |
| OPPO Electronics                       | 8         | 0.31%   |
| Huawei Technologies                    | 8         | 0.31%   |
| Attansic Technology                    | 6         | 0.23%   |
| Qualcomm                               | 5         | 0.19%   |
| Motorola PCS                           | 5         | 0.19%   |
| MediaTek                               | 5         | 0.19%   |
| Google                                 | 4         | 0.16%   |
| Hewlett-Packard                        | 3         | 0.12%   |
| T & A Mobile Phones                    | 2         | 0.08%   |
| OnePlus Technology (Shenzhen)          | 2         | 0.08%   |
| Lenovo                                 | 2         | 0.08%   |
| Davicom Semiconductor                  | 2         | 0.08%   |
| ZTE WCDMA Technologies MSM             | 1         | 0.04%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.04%   |
| Novatel Wireless                       | 1         | 0.04%   |
| Motorola BCS                           | 1         | 0.04%   |
| LG Electronics                         | 1         | 0.04%   |
| ICS Advent                             | 1         | 0.04%   |
| HTC (High Tech Computer)               | 1         | 0.04%   |
| HMD Global                             | 1         | 0.04%   |
| GoPro                                  | 1         | 0.04%   |
| ASUSTek Computer                       | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 764       | 29.57%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 419       | 16.22%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 123       | 4.76%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 49        | 1.9%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 37        | 1.43%   |
| Intel Ethernet Connection I218-LM                                 | 35        | 1.35%   |
| Intel Ethernet Connection I217-LM                                 | 35        | 1.35%   |
| Intel 82567LM Gigabit Network Connection                          | 34        | 1.32%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 33        | 1.28%   |
| Intel 82577LM Gigabit Network Connection                          | 33        | 1.28%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 30        | 1.16%   |
| Intel Ethernet Connection I219-LM                                 | 29        | 1.12%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 26        | 1.01%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 25        | 0.97%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 24        | 0.93%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 24        | 0.93%   |
| Intel 82566MM Gigabit Network Connection                          | 21        | 0.81%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 20        | 0.77%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 20        | 0.77%   |
| ASIX AX88179 Gigabit Ethernet                                     | 20        | 0.77%   |
| Intel Ethernet Connection (4) I219-LM                             | 19        | 0.74%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 19        | 0.74%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 17        | 0.66%   |
| Nvidia MCP79 Ethernet                                             | 17        | 0.66%   |
| Intel Ethernet Connection I219-V                                  | 17        | 0.66%   |
| Intel Ethernet Connection (3) I218-LM                             | 17        | 0.66%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 17        | 0.66%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 17        | 0.66%   |
| Intel Ethernet Connection (4) I219-V                              | 16        | 0.62%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 15        | 0.58%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 15        | 0.58%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 14        | 0.54%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 14        | 0.54%   |
| Nvidia MCP67 Ethernet                                             | 14        | 0.54%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 14        | 0.54%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 14        | 0.54%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 14        | 0.54%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 13        | 0.5%    |
| Intel PRO/100 VE Network Connection                               | 13        | 0.5%    |
| Broadcom Limited BCM4401-B0 100Base-TX                            | 12        | 0.46%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2937      | 53.27%  |
| Ethernet | 2483      | 45.04%  |
| Modem    | 87        | 1.58%   |
| Unknown  | 6         | 0.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2468      | 78.55%  |
| Ethernet | 673       | 21.42%  |
| Unknown  | 1         | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 2293      | 75.53%  |
| 1     | 609       | 20.06%  |
| 0     | 120       | 3.95%   |
| 3     | 14        | 0.46%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2387      | 77.58%  |
| Yes  | 690       | 22.42%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 747       | 37.24%  |
| Qualcomm Atheros Communications | 246       | 12.26%  |
| Realtek Semiconductor           | 226       | 11.27%  |
| Broadcom                        | 161       | 8.03%   |
| IMC Networks                    | 88        | 4.39%   |
| Apple                           | 79        | 3.94%   |
| Foxconn / Hon Hai               | 72        | 3.59%   |
| Lite-On Technology              | 71        | 3.54%   |
| Dell                            | 68        | 3.39%   |
| Hewlett-Packard                 | 66        | 3.29%   |
| Toshiba                         | 40        | 1.99%   |
| Cambridge Silicon Radio         | 30        | 1.5%    |
| Ralink                          | 25        | 1.25%   |
| ASUSTek Computer                | 17        | 0.85%   |
| Realtek                         | 14        | 0.7%    |
| Alps Electric                   | 14        | 0.7%    |
| Foxconn International           | 12        | 0.6%    |
| Askey Computer                  | 6         | 0.3%    |
| Ralink Technology               | 5         | 0.25%   |
| Taiyo Yuden                     | 4         | 0.2%    |
| Dynex                           | 3         | 0.15%   |
| Chicony Electronics             | 3         | 0.15%   |
| Qcom                            | 2         | 0.1%    |
| MediaTek                        | 2         | 0.1%    |
| Integrated System Solution      | 2         | 0.1%    |
| TP-Link                         | 1         | 0.05%   |
| Belkin Components               | 1         | 0.05%   |
| Unknown                         | 1         | 0.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 393       | 19.56%  |
| Realtek Bluetooth Radio                             | 141       | 7.02%   |
| Qualcomm Atheros  Bluetooth Device                  | 106       | 5.28%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 95        | 4.73%   |
| Intel AX201 Bluetooth                               | 89        | 4.43%   |
| Realtek  Bluetooth 4.2 Adapter                      | 67        | 3.33%   |
| Intel AX200 Bluetooth                               | 54        | 2.69%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 44        | 2.19%   |
| Apple Bluetooth Host Controller                     | 44        | 2.19%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 39        | 1.94%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 39        | 1.94%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 36        | 1.79%   |
| IMC Networks Bluetooth Device                       | 32        | 1.59%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 30        | 1.49%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 26        | 1.29%   |
| Lite-On Atheros AR3012 Bluetooth                    | 26        | 1.29%   |
| Ralink RT3290 Bluetooth                             | 25        | 1.24%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 24        | 1.19%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 23        | 1.14%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 22        | 1.1%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 22        | 1.1%    |
| IMC Networks Bluetooth Radio                        | 22        | 1.1%    |
| HP Broadcom 2070 Bluetooth Combo                    | 21        | 1.05%   |
| Broadcom BCM2045B (BDC-2.1)                         | 20        | 1%      |
| Dell DW375 Bluetooth Module                         | 19        | 0.95%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 19        | 0.95%   |
| Foxconn / Hon Hai Bluetooth Device                  | 18        | 0.9%    |
| Intel AX210 Bluetooth                               | 17        | 0.85%   |
| Intel Wireless-AC 3168 Bluetooth                    | 15        | 0.75%   |
| Apple Bluetooth USB Host Controller                 | 15        | 0.75%   |
| Realtek Bluetooth Radio                             | 14        | 0.7%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 14        | 0.7%    |
| Toshiba Bluetooth Device                            | 13        | 0.65%   |
| IMC Networks Wireless_Device                        | 13        | 0.65%   |
| Foxconn International BCM43142A0 Bluetooth module   | 12        | 0.6%    |
| Dell Wireless 365 Bluetooth                         | 12        | 0.6%    |
| Apple Bluetooth HCI                                 | 12        | 0.6%    |
| Dell Wireless 370 Bluetooth Mini-card               | 11        | 0.55%   |
| Dell BCM20702A0 Bluetooth Module                    | 11        | 0.55%   |
| Broadcom BCM2045 Bluetooth                          | 11        | 0.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 2392      | 70.08%  |
| AMD                                  | 538       | 15.76%  |
| Nvidia                               | 349       | 10.23%  |
| Silicon Integrated Systems [SiS]     | 31        | 0.91%   |
| VIA Technologies                     | 11        | 0.32%   |
| C-Media Electronics                  | 11        | 0.32%   |
| Generalplus Technology               | 7         | 0.21%   |
| Tenx Technology                      | 6         | 0.18%   |
| Realtek Semiconductor                | 5         | 0.15%   |
| Texas Instruments                    | 4         | 0.12%   |
| Plantronics                          | 4         | 0.12%   |
| Logitech                             | 4         | 0.12%   |
| Lenovo                               | 4         | 0.12%   |
| Creative Technology                  | 4         | 0.12%   |
| SteelSeries ApS                      | 3         | 0.09%   |
| JMTek                                | 3         | 0.09%   |
| GN Netcom                            | 3         | 0.09%   |
| Yamaha                               | 2         | 0.06%   |
| PreSonus Audio Electronics           | 2         | 0.06%   |
| Hewlett-Packard                      | 2         | 0.06%   |
| Focusrite-Novation                   | 2         | 0.06%   |
| DCMT Technology                      | 2         | 0.06%   |
| Corsair                              | 2         | 0.06%   |
| ZOOM                                 | 1         | 0.03%   |
| XMOS                                 | 1         | 0.03%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.03%   |
| Syntek                               | 1         | 0.03%   |
| Sony                                 | 1         | 0.03%   |
| Sennheiser Communications            | 1         | 0.03%   |
| SAVITECH                             | 1         | 0.03%   |
| Roland                               | 1         | 0.03%   |
| Razer USA                            | 1         | 0.03%   |
| OPPO Electronics                     | 1         | 0.03%   |
| Kingston Technology                  | 1         | 0.03%   |
| FiiO Electronics Technology          | 1         | 0.03%   |
| DSEA A/S                             | 1         | 0.03%   |
| Dell                                 | 1         | 0.03%   |
| Conexant Systems                     | 1         | 0.03%   |
| CMX Systems                          | 1         | 0.03%   |
| BEHRINGER International              | 1         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 284       | 6.89%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 275       | 6.67%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 224       | 5.43%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 197       | 4.78%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 166       | 4.03%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 166       | 4.03%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 142       | 3.44%   |
| Intel 8 Series HD Audio Controller                                                                | 141       | 3.42%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 137       | 3.32%   |
| AMD FCH Azalia Controller                                                                         | 135       | 3.27%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 129       | 3.13%   |
| Intel Broadwell-U Audio Controller                                                                | 100       | 2.42%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 99        | 2.4%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 93        | 2.26%   |
| AMD Kabini HDMI/DP Audio                                                                          | 86        | 2.09%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 76        | 1.84%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 76        | 1.84%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 74        | 1.79%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 74        | 1.79%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 72        | 1.75%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 66        | 1.6%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 63        | 1.53%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 61        | 1.48%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 52        | 1.26%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 51        | 1.24%   |
| Intel Cannon Lake PCH cAVS                                                                        | 51        | 1.24%   |
| AMD High Definition Audio Controller                                                              | 49        | 1.19%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 47        | 1.14%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 44        | 1.07%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 40        | 0.97%   |
| Intel CM238 HD Audio Controller                                                                   | 40        | 0.97%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 32        | 0.78%   |
| AMD Wrestler HDMI Audio                                                                           | 32        | 0.78%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 30        | 0.73%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 26        | 0.63%   |
| AMD Trinity HDMI Audio Controller                                                                 | 26        | 0.63%   |
| Nvidia High Definition Audio Controller                                                           | 24        | 0.58%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 24        | 0.58%   |
| Intel Comet Lake PCH cAVS                                                                         | 23        | 0.56%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 22        | 0.53%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Samsung Electronics    | 186       | 25.17%  |
| SK hynix               | 174       | 23.55%  |
| Micron Technology      | 85        | 11.5%   |
| Unknown                | 70        | 9.47%   |
| Kingston               | 53        | 7.17%   |
| Unknown (ABCD)         | 20        | 2.71%   |
| Crucial                | 20        | 2.71%   |
| Elpida                 | 16        | 2.17%   |
| Ramaxel Technology     | 15        | 2.03%   |
| Nanya Technology       | 15        | 2.03%   |
| A-DATA Technology      | 14        | 1.89%   |
| Smart                  | 10        | 1.35%   |
| Qimonda                | 4         | 0.54%   |
| Corsair                | 4         | 0.54%   |
| Timetec                | 3         | 0.41%   |
| Team                   | 3         | 0.41%   |
| Unknown                | 3         | 0.41%   |
| Transcend              | 2         | 0.27%   |
| Teikon                 | 2         | 0.27%   |
| Smart Brazil           | 2         | 0.27%   |
| SHARETRONIC            | 2         | 0.27%   |
| Patriot                | 2         | 0.27%   |
| High Bridge            | 2         | 0.27%   |
| G.Skill                | 2         | 0.27%   |
| ff                     | 2         | 0.27%   |
| fef5                   | 2         | 0.27%   |
| 4ea5                   | 2         | 0.27%   |
| Walton Chaintech       | 1         | 0.14%   |
| Unknown (08B5)         | 1         | 0.14%   |
| Unknown (07F7)         | 1         | 0.14%   |
| Unknown (000080B30080) | 1         | 0.14%   |
| Toshiba                | 1         | 0.14%   |
| Strontium              | 1         | 0.14%   |
| Silicon Power          | 1         | 0.14%   |
| PUSKILL                | 1         | 0.14%   |
| ProMos/Mosel Vitelic   | 1         | 0.14%   |
| pqi                    | 1         | 0.14%   |
| PNY                    | 1         | 0.14%   |
| Netlist                | 1         | 0.14%   |
| Nayna                  | 1         | 0.14%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 18        | 2.29%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 11        | 1.4%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 11        | 1.4%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 9         | 1.14%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 9         | 1.14%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s            | 8         | 1.02%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 8         | 1.02%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s         | 8         | 1.02%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 0.89%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 0.89%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 0.76%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 6         | 0.76%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 0.76%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 0.76%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 6         | 0.76%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.76%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 6         | 0.76%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 5         | 0.64%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 5         | 0.64%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 5         | 0.64%   |
| Samsung RAM M471B5773DH0-CH9 2048MB SODIMM DDR3 1600MT/s         | 5         | 0.64%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 0.64%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 5         | 0.64%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 4         | 0.51%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 4         | 0.51%   |
| SK hynix RAM HYMP112S64CP6-S6 1GB SODIMM DDR2 975MT/s            | 4         | 0.51%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.51%   |
| SK hynix RAM HMA851S6CJR6N-VK 4096MB SODIMM DDR4 2667MT/s        | 4         | 0.51%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 0.51%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.51%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 0.51%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 4         | 0.51%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 4         | 0.51%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.51%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 0.51%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 4         | 0.51%   |
| Samsung RAM M471A1G44BB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 4         | 0.51%   |
| Samsung RAM M4 70T5663EH3-CF7 2GB SODIMM DDR2 975MT/s            | 4         | 0.51%   |
| Micron RAM 8JSF25664HZ-1G4D1 2GB SODIMM DDR3 1334MT/s            | 4         | 0.51%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 4         | 0.51%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 246       | 39.23%  |
| DDR4    | 205       | 32.7%   |
| DDR2    | 70        | 11.16%  |
| LPDDR4  | 40        | 6.38%   |
| SDRAM   | 23        | 3.67%   |
| LPDDR3  | 20        | 3.19%   |
| DRAM    | 6         | 0.96%   |
| Unknown | 6         | 0.96%   |
| DDR     | 5         | 0.8%    |
| LPDDR5  | 4         | 0.64%   |
| DDR5    | 2         | 0.32%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 544       | 87.6%   |
| Row Of Chips | 50        | 8.05%   |
| DIMM         | 12        | 1.93%   |
| Unknown      | 8         | 1.29%   |
| Chip         | 7         | 1.13%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 222       | 31.36%  |
| 4096  | 221       | 31.21%  |
| 2048  | 148       | 20.9%   |
| 1024  | 51        | 7.2%    |
| 16384 | 45        | 6.36%   |
| 512   | 12        | 1.69%   |
| 32768 | 7         | 0.99%   |
| 256   | 2         | 0.28%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 167       | 24.59%  |
| 2667    | 101       | 14.87%  |
| 3200    | 75        | 11.05%  |
| 2400    | 55        | 8.1%    |
| 1334    | 40        | 5.89%   |
| 667     | 38        | 5.6%    |
| Unknown | 27        | 3.98%   |
| 2133    | 26        | 3.83%   |
| 1333    | 26        | 3.83%   |
| 1066    | 15        | 2.21%   |
| 800     | 13        | 1.91%   |
| 4267    | 11        | 1.62%   |
| 975     | 11        | 1.62%   |
| 2048    | 10        | 1.47%   |
| 533     | 10        | 1.47%   |
| 4199    | 9         | 1.33%   |
| 3266    | 9         | 1.33%   |
| 1867    | 8         | 1.18%   |
| 1067    | 7         | 1.03%   |
| 6400    | 5         | 0.74%   |
| 8400    | 3         | 0.44%   |
| 4800    | 3         | 0.44%   |
| 400     | 3         | 0.44%   |
| 3733    | 2         | 0.29%   |
| 4266    | 1         | 0.15%   |
| 2933    | 1         | 0.15%   |
| 1866    | 1         | 0.15%   |
| 1639    | 1         | 0.15%   |
| 666     | 1         | 0.15%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 12        | 40%     |
| Canon                 | 6         | 20%     |
| Seiko Epson           | 5         | 16.67%  |
| Samsung Electronics   | 2         | 6.67%   |
| Brother Industries    | 2         | 6.67%   |
| Zebra                 | 1         | 3.33%   |
| STMicroelectronics    | 1         | 3.33%   |
| Lexmark International | 1         | 3.33%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| HP ENVY Photo 6200 series                                 | 2         | 6.67%   |
| HP DeskJet 1110 series                                    | 2         | 6.67%   |
| Zebra ZP 450 Printer                                      | 1         | 3.33%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 3.33%   |
| Seiko Epson WF-2010 Series                                | 1         | 3.33%   |
| Seiko Epson Printer                                       | 1         | 3.33%   |
| Seiko Epson L3110 Series                                  | 1         | 3.33%   |
| Seiko Epson ET-2810 Series                                | 1         | 3.33%   |
| Seiko Epson AcuLaser C1700                                | 1         | 3.33%   |
| Samsung M2020 Series                                      | 1         | 3.33%   |
| Samsung CLX-3300 Series                                   | 1         | 3.33%   |
| Lexmark International 2400 series                         | 1         | 3.33%   |
| HP Laserjet P1505                                         | 1         | 3.33%   |
| HP LaserJet P1102                                         | 1         | 3.33%   |
| HP LaserJet 1200                                          | 1         | 3.33%   |
| HP LaserJet 1020                                          | 1         | 3.33%   |
| HP LaserJet 1000                                          | 1         | 3.33%   |
| HP DeskJet 2700 series                                    | 1         | 3.33%   |
| HP DeskJet 2300 series                                    | 1         | 3.33%   |
| HP Deskjet 1510                                           | 1         | 3.33%   |
| Canon TS3100 series                                       | 1         | 3.33%   |
| Canon PIXMA MX490 Series                                  | 1         | 3.33%   |
| Canon PIXMA MX340                                         | 1         | 3.33%   |
| Canon PIXMA MG3600 Series                                 | 1         | 3.33%   |
| Canon PIXMA MG3000 series                                 | 1         | 3.33%   |
| Canon MG2100 series                                       | 1         | 3.33%   |
| Brother MFC-L2730DW series                                | 1         | 3.33%   |
| Brother DCP-T300                                          | 1         | 3.33%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Canon       | 3         | 60%     |
| Seiko Epson | 2         | 40%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-X750 [Perfection 4490 Photo] | 2         | 40%     |
| Canon CanoScan LiDE 90                      | 1         | 20%     |
| Canon CanoScan LIDE 25                      | 1         | 20%     |
| Canon CanoScan LiDE 200                     | 1         | 20%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 619       | 25.16%  |
| Microdia                               | 236       | 9.59%   |
| Realtek Semiconductor                  | 203       | 8.25%   |
| IMC Networks                           | 187       | 7.6%    |
| Sunplus Innovation Technology          | 138       | 5.61%   |
| Suyin                                  | 126       | 5.12%   |
| Bison Electronics                      | 126       | 5.12%   |
| Cheng Uei Precision Industry (Foxlink) | 114       | 4.63%   |
| Quanta                                 | 100       | 4.07%   |
| Apple                                  | 71        | 2.89%   |
| Syntek                                 | 65        | 2.64%   |
| Silicon Motion                         | 56        | 2.28%   |
| Acer                                   | 51        | 2.07%   |
| Lite-On Technology                     | 46        | 1.87%   |
| Alcor Micro                            | 46        | 1.87%   |
| Ricoh                                  | 32        | 1.3%    |
| Luxvisions Innotech Limited            | 22        | 0.89%   |
| Logitech                               | 20        | 0.81%   |
| ALi                                    | 19        | 0.77%   |
| Importek                               | 17        | 0.69%   |
| Samsung Electronics                    | 16        | 0.65%   |
| Primax Electronics                     | 14        | 0.57%   |
| icSpring                               | 14        | 0.57%   |
| Z-Star Microelectronics                | 13        | 0.53%   |
| Sonix Technology                       | 11        | 0.45%   |
| Lenovo                                 | 11        | 0.45%   |
| OmniVision Technologies                | 10        | 0.41%   |
| GEMBIRD                                | 9         | 0.37%   |
| SunplusIT                              | 7         | 0.28%   |
| Genesys Logic                          | 6         | 0.24%   |
| Y Media                                | 4         | 0.16%   |
| Sunplus Technology                     | 4         | 0.16%   |
| Intel                                  | 4         | 0.16%   |
| Microsoft                              | 3         | 0.12%   |
| Generalplus Technology                 | 3         | 0.12%   |
| ARC International                      | 3         | 0.12%   |
| Tripath Technology                     | 2         | 0.08%   |
| LG Electronics                         | 2         | 0.08%   |
| KYE Systems (Mouse Systems)            | 2         | 0.08%   |
| Huawei Technologies                    | 2         | 0.08%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 84        | 3.4%    |
| Microdia Integrated_Webcam_HD                    | 49        | 1.99%   |
| IMC Networks USB2.0 HD UVC WebCam                | 45        | 1.82%   |
| Realtek Integrated_Webcam_HD                     | 38        | 1.54%   |
| Chicony HD WebCam                                | 38        | 1.54%   |
| Microdia Integrated Webcam                       | 36        | 1.46%   |
| Chicony HP TrueVision HD                         | 35        | 1.42%   |
| Syntek Integrated Camera                         | 31        | 1.26%   |
| Sunplus Integrated_Webcam_HD                     | 27        | 1.09%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 27        | 1.09%   |
| Bison Integrated Camera                          | 27        | 1.09%   |
| IMC Networks Integrated Camera                   | 26        | 1.05%   |
| Chicony USB 2.0 Camera                           | 25        | 1.01%   |
| Sunplus HD WebCam                                | 23        | 0.93%   |
| Chicony HP TrueVision HD Camera                  | 23        | 0.93%   |
| Bison Lenovo EasyCamera                          | 23        | 0.93%   |
| Realtek Integrated Webcam                        | 22        | 0.89%   |
| Chicony Lenovo EasyCamera                        | 21        | 0.85%   |
| Chicony EasyCamera                               | 21        | 0.85%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 21        | 0.85%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR               | 20        | 0.81%   |
| Chicony TOSHIBA Web Camera - HD                  | 19        | 0.77%   |
| Apple FaceTime HD Camera                         | 19        | 0.77%   |
| Suyin Acer/HP Integrated Webcam [CN0314]         | 18        | 0.73%   |
| Realtek USB Camera                               | 18        | 0.73%   |
| Chicony VGA WebCam                               | 18        | 0.73%   |
| Chicony HP HD Webcam                             | 18        | 0.73%   |
| Alcor Micro USB 2.0 Web Camera                   | 18        | 0.73%   |
| Suyin HP Truevision HD                           | 17        | 0.69%   |
| Lite-On HP HD Camera                             | 17        | 0.69%   |
| Chicony USB2.0 VGA UVC WebCam                    | 17        | 0.69%   |
| Samsung Galaxy series, misc. (MTP mode)          | 16        | 0.65%   |
| Quanta HP TrueVision HD Camera                   | 16        | 0.65%   |
| Chicony HP Webcam                                | 16        | 0.65%   |
| Chicony CNF9055 Toshiba Webcam                   | 16        | 0.65%   |
| Apple Built-in iSight                            | 16        | 0.65%   |
| ALi Gateway Webcam                               | 16        | 0.65%   |
| Realtek HP Truevision HD                         | 15        | 0.61%   |
| Quanta HP Webcam                                 | 15        | 0.61%   |
| Chicony HP HD Camera                             | 15        | 0.61%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 197       | 47.13%  |
| AuthenTec                          | 62        | 14.83%  |
| Shenzhen Goodix Technology         | 41        | 9.81%   |
| Upek                               | 35        | 8.37%   |
| Synaptics                          | 32        | 7.66%   |
| Elan Microelectronics              | 20        | 4.78%   |
| STMicroelectronics                 | 19        | 4.55%   |
| LighTuning Technology              | 8         | 1.91%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.48%   |
| Samsung Electronics                | 1         | 0.24%   |
| Focal-systems.Corp                 | 1         | 0.24%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 42        | 10.05%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 33        | 7.89%   |
| Shenzhen Goodix  Fingerprint Device                                        | 29        | 6.94%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 25        | 5.98%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 21        | 5.02%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 21        | 5.02%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 19        | 4.55%   |
| Validity Sensors VFS491                                                    | 19        | 4.55%   |
| STMicroelectronics Fingerprint Reader                                      | 19        | 4.55%   |
| Validity Sensors Fingerprint scanner                                       | 18        | 4.31%   |
| AuthenTec AES2810                                                          | 18        | 4.31%   |
| Elan ELAN:ARM-M4                                                           | 11        | 2.63%   |
| AuthenTec AES1600                                                          | 10        | 2.39%   |
| Validity Sensors Synaptics WBDI                                            | 9         | 2.15%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 9         | 2.15%   |
| Synaptics Fingerprint reader [HP G6]                                       | 8         | 1.91%   |
| Shenzhen Goodix Fingerprint Reader                                         | 8         | 1.91%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 7         | 1.67%   |
| Elan ELAN:Fingerprint                                                      | 7         | 1.67%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 6         | 1.44%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 6         | 1.44%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 6         | 1.44%   |
| AuthenTec Fingerprint Sensor                                               | 6         | 1.44%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 5         | 1.2%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 5         | 1.2%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 1.2%    |
| Validity Sensors VFS301 Fingerprint Reader                                 | 4         | 0.96%   |
| Shenzhen Goodix FingerPrint                                                | 4         | 0.96%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 4         | 0.96%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 3         | 0.72%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 0.72%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 3         | 0.72%   |
| Upek TCS5B Fingerprint sensor                                              | 2         | 0.48%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 0.48%   |
| Synaptics WBDI                                                             | 2         | 0.48%   |
| Synaptics  WBDI                                                            | 2         | 0.48%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 0.48%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 0.48%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 2         | 0.48%   |
| LighTuning Fingerprint Reader                                              | 2         | 0.48%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 99        | 53.8%   |
| Alcor Micro                       | 32        | 17.39%  |
| O2 Micro                          | 27        | 14.67%  |
| Lenovo                            | 9         | 4.89%   |
| Upek                              | 8         | 4.35%   |
| Yubico.com                        | 2         | 1.09%   |
| SCM Microsystems                  | 2         | 1.09%   |
| Realtek Semiconductor             | 2         | 1.09%   |
| VASCO Data Security International | 1         | 0.54%   |
| OmniKey                           | 1         | 0.54%   |
| Fujitsu Siemens Computers         | 1         | 0.54%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 47        | 25.41%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 31        | 16.76%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 24        | 12.97%  |
| Broadcom 5880                                                                | 23        | 12.43%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 22        | 11.89%  |
| Lenovo Integrated Smart Card Reader                                          | 9         | 4.86%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 8         | 4.32%   |
| O2 Micro Oz776 SmartCard Reader                                              | 5         | 2.7%    |
| Broadcom 58200                                                               | 4         | 2.16%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 1.08%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 1.08%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 1.08%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 1.08%   |
| VASCO Data Security International DIGIPASS 870                               | 1         | 0.54%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.54%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 0.54%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.54%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1970      | 63.96%  |
| 1     | 864       | 28.05%  |
| 2     | 218       | 7.08%   |
| 3     | 25        | 0.81%   |
| 4     | 2         | 0.06%   |
| 7     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 411       | 30.74%  |
| Graphics card            | 293       | 21.91%  |
| Chipcard                 | 175       | 13.09%  |
| Net/wireless             | 162       | 12.12%  |
| Multimedia controller    | 99        | 7.4%    |
| Storage                  | 44        | 3.29%   |
| Modem                    | 38        | 2.84%   |
| Bluetooth                | 33        | 2.47%   |
| Sound                    | 16        | 1.2%    |
| Communication controller | 14        | 1.05%   |
| Flash memory             | 13        | 0.97%   |
| Camera                   | 13        | 0.97%   |
| Net/ethernet             | 8         | 0.6%    |
| Card reader              | 6         | 0.45%   |
| Network                  | 4         | 0.3%    |
| Storage/nvme             | 2         | 0.15%   |
| Storage/ide              | 2         | 0.15%   |
| Dvb card                 | 2         | 0.15%   |
| Unclassified device      | 1         | 0.07%   |
| Storage/ata              | 1         | 0.07%   |

