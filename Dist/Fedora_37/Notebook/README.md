Fedora 37 - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for Fedora 37.

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

Total: 104

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | Legion 5 15IAH7H 82RB       | [aa6c06f2bb](https://linux-hardware.org/?probe=aa6c06f2bb) | Nov 02, 2022 |
| Lenovo        | Legion 5 15IAH7H 82RB       | [584db1dcb2](https://linux-hardware.org/?probe=584db1dcb2) | Nov 02, 2022 |
| GPD           | G1619-04                    | [898bbfb591](https://linux-hardware.org/?probe=898bbfb591) | Nov 01, 2022 |
| HUAWEI        | CREM-WXX9                   | [1d24aac4ce](https://linux-hardware.org/?probe=1d24aac4ce) | Nov 01, 2022 |
| HUAWEI        | CREM-WXX9                   | [2eb32b1bb3](https://linux-hardware.org/?probe=2eb32b1bb3) | Nov 01, 2022 |
| HP            | ZBook 15 G2                 | [7254a9a2fc](https://linux-hardware.org/?probe=7254a9a2fc) | Nov 01, 2022 |
| Samsung       | RV410/RV510/S3510/E3510     | [566d83485b](https://linux-hardware.org/?probe=566d83485b) | Oct 31, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [e993af2670](https://linux-hardware.org/?probe=e993af2670) | Oct 31, 2022 |
| HP            | ENVY 17                     | [5b845d9ee3](https://linux-hardware.org/?probe=5b845d9ee3) | Oct 31, 2022 |
| Samsung       | RV410/RV510/S3510/E3510     | [073ba962ff](https://linux-hardware.org/?probe=073ba962ff) | Oct 31, 2022 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | [221710c9ea](https://linux-hardware.org/?probe=221710c9ea) | Oct 31, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [a4eebe6485](https://linux-hardware.org/?probe=a4eebe6485) | Oct 30, 2022 |
| Dell          | Latitude 7490               | [95d0006efb](https://linux-hardware.org/?probe=95d0006efb) | Oct 30, 2022 |
| Dell          | XPS 13 9300                 | [cc62dbe2f6](https://linux-hardware.org/?probe=cc62dbe2f6) | Oct 29, 2022 |
| Dell          | XPS 13 9300                 | [301aab9126](https://linux-hardware.org/?probe=301aab9126) | Oct 29, 2022 |
| HP            | ZBook 15 G3                 | [c60b429baa](https://linux-hardware.org/?probe=c60b429baa) | Oct 28, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YR... | [0c6a68368c](https://linux-hardware.org/?probe=0c6a68368c) | Oct 27, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [670823778e](https://linux-hardware.org/?probe=670823778e) | Oct 27, 2022 |
| Dell          | Latitude E7270              | [7f2c8b9e9c](https://linux-hardware.org/?probe=7f2c8b9e9c) | Oct 25, 2022 |
| Dell          | Latitude E7450              | [45e65cd626](https://linux-hardware.org/?probe=45e65cd626) | Oct 25, 2022 |
| HP            | 340S G7 Notebook PC         | [dc8eab937b](https://linux-hardware.org/?probe=dc8eab937b) | Oct 24, 2022 |
| HP            | 340S G7 Notebook PC         | [406538a0de](https://linux-hardware.org/?probe=406538a0de) | Oct 23, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [14830504a7](https://linux-hardware.org/?probe=14830504a7) | Oct 22, 2022 |
| Lenovo        | ThinkPad X260 20F5S5Q200    | [c2e041fd54](https://linux-hardware.org/?probe=c2e041fd54) | Oct 21, 2022 |
| Timi          | Xiaomi Book Pro 16 2022     | [41bade1339](https://linux-hardware.org/?probe=41bade1339) | Oct 21, 2022 |
| LG Electro... | 16Z90P-G.AP75D              | [1e1526e9d8](https://linux-hardware.org/?probe=1e1526e9d8) | Oct 21, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [63751816bc](https://linux-hardware.org/?probe=63751816bc) | Oct 21, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YR... | [e03569f758](https://linux-hardware.org/?probe=e03569f758) | Oct 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [06328b7f7c](https://linux-hardware.org/?probe=06328b7f7c) | Oct 20, 2022 |
| Dell          | Latitude 7420               | [332d2cd420](https://linux-hardware.org/?probe=332d2cd420) | Oct 19, 2022 |
| System76      | Kudu                        | [49c0e1c400](https://linux-hardware.org/?probe=49c0e1c400) | Oct 19, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | [f91daeac73](https://linux-hardware.org/?probe=f91daeac73) | Oct 19, 2022 |
| Dell          | Precision 5510              | [d56d0aceaf](https://linux-hardware.org/?probe=d56d0aceaf) | Oct 18, 2022 |
| Acer          | Aspire A717-71G             | [969c0ac771](https://linux-hardware.org/?probe=969c0ac771) | Oct 17, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [7b5da7d635](https://linux-hardware.org/?probe=7b5da7d635) | Oct 17, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [678415db20](https://linux-hardware.org/?probe=678415db20) | Oct 17, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [c1bad579af](https://linux-hardware.org/?probe=c1bad579af) | Oct 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [2a36feb313](https://linux-hardware.org/?probe=2a36feb313) | Oct 16, 2022 |
| Timi          | TM1701                      | [c2b709ff0c](https://linux-hardware.org/?probe=c2b709ff0c) | Oct 15, 2022 |
| Lenovo        | ThinkPad T480s 20L8S1R50... | [478b58f9b6](https://linux-hardware.org/?probe=478b58f9b6) | Oct 15, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [dbd2328d0f](https://linux-hardware.org/?probe=dbd2328d0f) | Oct 14, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [3a8bdfb3f5](https://linux-hardware.org/?probe=3a8bdfb3f5) | Oct 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [9b0a923899](https://linux-hardware.org/?probe=9b0a923899) | Oct 13, 2022 |
| Acer          | Aspire A715-71G             | [2b0752150c](https://linux-hardware.org/?probe=2b0752150c) | Oct 12, 2022 |
| HP            | EliteBook 840 G6            | [29f63f8a32](https://linux-hardware.org/?probe=29f63f8a32) | Oct 10, 2022 |
| HP            | ENVY Laptop 13-ad0xx        | [52658eb393](https://linux-hardware.org/?probe=52658eb393) | Oct 09, 2022 |
| ASUSTek       | K55VM                       | [d17d1273de](https://linux-hardware.org/?probe=d17d1273de) | Oct 09, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [c0c2e0ca69](https://linux-hardware.org/?probe=c0c2e0ca69) | Oct 08, 2022 |
| HP            | Pavilion Laptop 14-ec1xx... | [615578d390](https://linux-hardware.org/?probe=615578d390) | Oct 08, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [5dbeb45ba5](https://linux-hardware.org/?probe=5dbeb45ba5) | Oct 06, 2022 |
| Acer          | Aspire E5-475G              | [a545cecc64](https://linux-hardware.org/?probe=a545cecc64) | Oct 05, 2022 |
| Acer          | Aspire E5-475G              | [06fa787cb1](https://linux-hardware.org/?probe=06fa787cb1) | Oct 05, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | [f6fc1950ac](https://linux-hardware.org/?probe=f6fc1950ac) | Oct 05, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [d0d3494971](https://linux-hardware.org/?probe=d0d3494971) | Oct 05, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | [ddb0e3fb81](https://linux-hardware.org/?probe=ddb0e3fb81) | Oct 05, 2022 |
| HP            | Laptop 15s-eq3xxx           | [2bd986670e](https://linux-hardware.org/?probe=2bd986670e) | Oct 04, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | [4ba3e28201](https://linux-hardware.org/?probe=4ba3e28201) | Oct 04, 2022 |
| Timi          | A35S                        | [fe7ad0ac13](https://linux-hardware.org/?probe=fe7ad0ac13) | Oct 03, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | [80a2948ff1](https://linux-hardware.org/?probe=80a2948ff1) | Oct 02, 2022 |
| Lenovo        | ThinkPad T470s 20HGS09L0... | [7c384e5578](https://linux-hardware.org/?probe=7c384e5578) | Sep 30, 2022 |
| A-DATA Tec... | XENIA 14                    | [251f390772](https://linux-hardware.org/?probe=251f390772) | Sep 30, 2022 |
| Dell          | Latitude 7430               | [2151370437](https://linux-hardware.org/?probe=2151370437) | Sep 29, 2022 |
| A-DATA Tec... | XENIA 14                    | [e819e5dc14](https://linux-hardware.org/?probe=e819e5dc14) | Sep 29, 2022 |
| HP            | ZBook 15 G3                 | [1d612b997a](https://linux-hardware.org/?probe=1d612b997a) | Sep 29, 2022 |
| ASUSTek       | X550CL                      | [ded047597e](https://linux-hardware.org/?probe=ded047597e) | Sep 28, 2022 |
| Timi          | A35S                        | [bdb2ba4eab](https://linux-hardware.org/?probe=bdb2ba4eab) | Sep 27, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [7c62f5131f](https://linux-hardware.org/?probe=7c62f5131f) | Sep 27, 2022 |
| Lenovo        | IdeaPad 310-14ISK 80UG      | [d8b270de2b](https://linux-hardware.org/?probe=d8b270de2b) | Sep 25, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [9f37c7c4fa](https://linux-hardware.org/?probe=9f37c7c4fa) | Sep 25, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [0d790a94fa](https://linux-hardware.org/?probe=0d790a94fa) | Sep 25, 2022 |
| Dell          | XPS 15 9520                 | [fab5b34402](https://linux-hardware.org/?probe=fab5b34402) | Sep 25, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [2e96ddfdd1](https://linux-hardware.org/?probe=2e96ddfdd1) | Sep 25, 2022 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | [96f4499ec5](https://linux-hardware.org/?probe=96f4499ec5) | Sep 25, 2022 |
| Lenovo        | ThinkPad E495 20NE001RTX    | [91bd22b430](https://linux-hardware.org/?probe=91bd22b430) | Sep 25, 2022 |
| Dell          | XPS 13 9380                 | [332540a4c8](https://linux-hardware.org/?probe=332540a4c8) | Sep 24, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [24b2810c64](https://linux-hardware.org/?probe=24b2810c64) | Sep 24, 2022 |
| Lenovo        | ThinkPad T440s 20ARA0YL0... | [93eedc638b](https://linux-hardware.org/?probe=93eedc638b) | Sep 24, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | [b7f6ab8ad0](https://linux-hardware.org/?probe=b7f6ab8ad0) | Sep 23, 2022 |
| Timi          | A35S                        | [d0f195a77a](https://linux-hardware.org/?probe=d0f195a77a) | Sep 23, 2022 |
| Dell          | XPS 9320                    | [959d1406dd](https://linux-hardware.org/?probe=959d1406dd) | Sep 23, 2022 |
| Acer          | Nitro AN517-51              | [7bd22a5e38](https://linux-hardware.org/?probe=7bd22a5e38) | Sep 20, 2022 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [1da95a964b](https://linux-hardware.org/?probe=1da95a964b) | Sep 20, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [be279328b1](https://linux-hardware.org/?probe=be279328b1) | Sep 19, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | [3615e82cb6](https://linux-hardware.org/?probe=3615e82cb6) | Sep 17, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [9c23c7bb58](https://linux-hardware.org/?probe=9c23c7bb58) | Sep 17, 2022 |
| Irbis         | NB264                       | [e9361bf1c8](https://linux-hardware.org/?probe=e9361bf1c8) | Sep 17, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [9497f1e17f](https://linux-hardware.org/?probe=9497f1e17f) | Sep 16, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZX... | [099e5d3523](https://linux-hardware.org/?probe=099e5d3523) | Sep 16, 2022 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [26cdf51338](https://linux-hardware.org/?probe=26cdf51338) | Sep 15, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [ec8f0a9ebf](https://linux-hardware.org/?probe=ec8f0a9ebf) | Sep 14, 2022 |
| HUAWEI        | HVY-WXX9                    | [8fab790c57](https://linux-hardware.org/?probe=8fab790c57) | Sep 14, 2022 |
| System76      | Lemur Pro                   | [d6682a260a](https://linux-hardware.org/?probe=d6682a260a) | Sep 14, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [4aa3e2b6c2](https://linux-hardware.org/?probe=4aa3e2b6c2) | Sep 14, 2022 |
| HP            | Laptop 17-cp0xxx            | [c05d80959b](https://linux-hardware.org/?probe=c05d80959b) | Sep 14, 2022 |
| HUAWEI        | HVY-WXX9                    | [d574f5da9b](https://linux-hardware.org/?probe=d574f5da9b) | Sep 13, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [7326474aae](https://linux-hardware.org/?probe=7326474aae) | Sep 13, 2022 |
| AXDIA Inte... | WINPAD V10                  | [b3e5abaf4b](https://linux-hardware.org/?probe=b3e5abaf4b) | Sep 09, 2022 |
| TUXEDO        | InfinityBook S 15/17 Gen... | [e1a78657ba](https://linux-hardware.org/?probe=e1a78657ba) | Sep 07, 2022 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | [681486095a](https://linux-hardware.org/?probe=681486095a) | Aug 27, 2022 |
| Lenovo        | ThinkPad W510 4391F66       | [a92e3ba61f](https://linux-hardware.org/?probe=a92e3ba61f) | Aug 19, 2022 |
| HP            | EliteBook 820 G1            | [1bdfc2f218](https://linux-hardware.org/?probe=1bdfc2f218) | Aug 09, 2022 |
| Samsung       | 270E5G/270E5U               | [d1f2245fb4](https://linux-hardware.org/?probe=d1f2245fb4) | Jul 18, 2022 |
| HUAWEI        | HVY-WXX9                    | [43098a1f34](https://linux-hardware.org/?probe=43098a1f34) | Apr 23, 2022 |
| HP            | Laptop 14-dq2xxx            | [2477951c04](https://linux-hardware.org/?probe=2477951c04) | Apr 15, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                                      | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| 5.19.8-300.fc37.x86_64                                       | 10        | 11.24%  |
| 5.19.16-301.fc37.x86_64                                      | 10        | 11.24%  |
| 5.19.13-300.fc37.x86_64                                      | 9         | 10.11%  |
| 5.19.7-300.fc37.x86_64                                       | 7         | 7.87%   |
| 5.19.14-300.fc37.x86_64                                      | 7         | 7.87%   |
| 5.19.11-300.fc37.x86_64                                      | 6         | 6.74%   |
| 5.19.10-300.fc37.x86_64                                      | 6         | 6.74%   |
| 5.19.9-300.fc37.x86_64                                       | 5         | 5.62%   |
| 5.19.15-301.fc37.x86_64                                      | 5         | 5.62%   |
| 5.19.12-300.fc37.x86_64                                      | 4         | 4.49%   |
| 6.0.5-300.fc37.x86_64                                        | 3         | 3.37%   |
| 5.19.16-300.fc37.x86_64                                      | 3         | 3.37%   |
| 5.19.15-300.fc37.x86_64                                      | 2         | 2.25%   |
| 5.18.0-0.rc2.23.fc37.x86_64                                  | 2         | 2.25%   |
| 6.1.0-0.rc0.20221012git49da07006239.10.vanilla.1.fc37.x86_64 | 1         | 1.12%   |
| 6.0.2-xm1.0.fc37.x86_64                                      | 1         | 1.12%   |
| 6.0.0-0.rc6.41.fc38.x86_64                                   | 1         | 1.12%   |
| 5.19.4-300.fc37.x86_64                                       | 1         | 1.12%   |
| 5.19.12-xm1.0.fc37.x86_64                                    | 1         | 1.12%   |
| 5.19.12-302.rog.fc37.x86_64                                  | 1         | 1.12%   |
| 5.19.10-602.inttf.fc37.x86_64                                | 1         | 1.12%   |
| 5.19.0-xm2.0.fc37.x86_64                                     | 1         | 1.12%   |
| 5.19.0-65.fc37.x86_64                                        | 1         | 1.12%   |
| 5.19.0-0.rc6.20220714git4a57a8400075.49.fc37.x86_64          | 1         | 1.12%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.19.16 | 13        | 14.61%  |
| 5.19.8  | 10        | 11.24%  |
| 5.19.13 | 9         | 10.11%  |
| 5.19.7  | 7         | 7.87%   |
| 5.19.15 | 7         | 7.87%   |
| 5.19.14 | 7         | 7.87%   |
| 5.19.10 | 7         | 7.87%   |
| 5.19.12 | 6         | 6.74%   |
| 5.19.11 | 6         | 6.74%   |
| 5.19.9  | 5         | 5.62%   |
| 6.0.5   | 3         | 3.37%   |
| 5.19.0  | 3         | 3.37%   |
| 5.18.0  | 2         | 2.25%   |
| 6.1.0   | 1         | 1.12%   |
| 6.0.2   | 1         | 1.12%   |
| 6.0.0   | 1         | 1.12%   |
| 5.19.4  | 1         | 1.12%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.19    | 78        | 90.7%   |
| 6.0     | 5         | 5.81%   |
| 5.18    | 2         | 2.33%   |
| 6.1     | 1         | 1.16%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 86        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GNOME   | 71        | 82.56%  |
| KDE5    | 12        | 13.95%  |
| XFCE    | 1         | 1.16%   |
| LXDE    | 1         | 1.16%   |
| Unknown | 1         | 1.16%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 72        | 83.72%  |
| X11     | 12        | 13.95%  |
| Tty     | 1         | 1.16%   |
| Unknown | 1         | 1.16%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 45        | 52.33%  |
| GDM     | 30        | 34.88%  |
| SDDM    | 6         | 6.98%   |
| LightDM | 4         | 4.65%   |
| LXDM    | 1         | 1.16%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 50        | 58.14%  |
| ru_RU | 6         | 6.98%   |
| pt_BR | 4         | 4.65%   |
| en_GB | 4         | 4.65%   |
| it_IT | 3         | 3.49%   |
| fr_FR | 3         | 3.49%   |
| de_DE | 2         | 2.33%   |
| uk_UA | 1         | 1.16%   |
| ro_RO | 1         | 1.16%   |
| hu_HU | 1         | 1.16%   |
| es_GT | 1         | 1.16%   |
| es_ES | 1         | 1.16%   |
| es_AR | 1         | 1.16%   |
| en_ZA | 1         | 1.16%   |
| en_PH | 1         | 1.16%   |
| en_IN | 1         | 1.16%   |
| en_IE | 1         | 1.16%   |
| en_CA | 1         | 1.16%   |
| en_AU | 1         | 1.16%   |
| en_AT | 1         | 1.16%   |
| C     | 1         | 1.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 75        | 87.21%  |
| BIOS | 11        | 12.79%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Btrfs   | 74        | 86.05%  |
| Ext4    | 8         | 9.3%    |
| Xfs     | 2         | 2.33%   |
| Overlay | 2         | 2.33%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 44        | 51.16%  |
| GPT     | 39        | 45.35%  |
| MBR     | 3         | 3.49%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 77        | 89.53%  |
| Yes       | 9         | 10.47%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 69        | 80.23%  |
| Yes       | 17        | 19.77%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 30        | 34.88%  |
| Hewlett-Packard     | 12        | 13.95%  |
| ASUSTek Computer    | 12        | 13.95%  |
| Dell                | 10        | 11.63%  |
| HUAWEI              | 5         | 5.81%   |
| Acer                | 4         | 4.65%   |
| Timi                | 3         | 3.49%   |
| System76            | 2         | 2.33%   |
| Samsung Electronics | 2         | 2.33%   |
| TUXEDO              | 1         | 1.16%   |
| Schenker            | 1         | 1.16%   |
| LG Electronics      | 1         | 1.16%   |
| Irbis               | 1         | 1.16%   |
| GPD                 | 1         | 1.16%   |
| A-DATA Technology   | 1         | 1.16%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| HUAWEI HVY-WXX9                            | 2         | 2.33%   |
| TUXEDO InfinityBook S 15/17 Gen7           | 1         | 1.16%   |
| Timi Xiaomi Book Pro 16 2022               | 1         | 1.16%   |
| Timi TM1701                                | 1         | 1.16%   |
| Timi A35S                                  | 1         | 1.16%   |
| System76 Lemur Pro                         | 1         | 1.16%   |
| System76 Kudu                              | 1         | 1.16%   |
| Schenker XMG FUSION 15 (XFU15L19)          | 1         | 1.16%   |
| Samsung RV410/RV510/S3510/E3510            | 1         | 1.16%   |
| Samsung 270E5G/270E5U                      | 1         | 1.16%   |
| LG 16Z90P-G.AP75D                          | 1         | 1.16%   |
| Lenovo ThinkPad X260 20F5S5Q200            | 1         | 1.16%   |
| Lenovo ThinkPad X220 4291WSH               | 1         | 1.16%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XWCTO1WW | 1         | 1.16%   |
| Lenovo ThinkPad X1 Carbon Gen 8 20UAS0X800 | 1         | 1.16%   |
| Lenovo ThinkPad X1 Carbon 7th 20QD0000US   | 1         | 1.16%   |
| Lenovo ThinkPad W510 4391F66               | 1         | 1.16%   |
| Lenovo ThinkPad T480s 20L8S1R50U           | 1         | 1.16%   |
| Lenovo ThinkPad T470s 20HGS09L0K           | 1         | 1.16%   |
| Lenovo ThinkPad T440s 20ARA0YL00           | 1         | 1.16%   |
| Lenovo ThinkPad T14 Gen 2a 20XK000YSP      | 1         | 1.16%   |
| Lenovo ThinkPad T14 Gen 1 20UES08Q15       | 1         | 1.16%   |
| Lenovo ThinkPad P15 Gen 2i 20YRS73601      | 1         | 1.16%   |
| Lenovo ThinkPad P15 Gen 2i 20YRS1YE01      | 1         | 1.16%   |
| Lenovo ThinkPad Edge E540 20C600AKZA       | 1         | 1.16%   |
| Lenovo ThinkPad E495 20NE001RTX            | 1         | 1.16%   |
| Lenovo ThinkPad E14 Gen 2 20TAS08F00       | 1         | 1.16%   |
| Lenovo ThinkBook 15 G2 ITL 20VE            | 1         | 1.16%   |
| Lenovo ThinkBook 14-IIL 20SL               | 1         | 1.16%   |
| Lenovo ThinkBook 13s G3 ACN 20YA           | 1         | 1.16%   |
| Lenovo Legion Y540-15IRH 81SX              | 1         | 1.16%   |
| Lenovo Legion 5 Pro 16ITH6H 82JD           | 1         | 1.16%   |
| Lenovo Legion 5 15IAH7H 82RB               | 1         | 1.16%   |
| Lenovo IdeaPad S145-15IWL 81S9             | 1         | 1.16%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK      | 1         | 1.16%   |
| Lenovo IdeaPad 5 Pro 14ARH7 82SJ           | 1         | 1.16%   |
| Lenovo IdeaPad 5 15ALC05 82LN              | 1         | 1.16%   |
| Lenovo IdeaPad 5 14ITL05 82FE              | 1         | 1.16%   |
| Lenovo IdeaPad 330-15IKB 81DE              | 1         | 1.16%   |
| Lenovo IdeaPad 320-15IAP 80XR              | 1         | 1.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 16        | 18.6%   |
| Lenovo IdeaPad      | 8         | 9.3%    |
| Dell XPS            | 4         | 4.65%   |
| Dell Latitude       | 4         | 4.65%   |
| ASUS ROG            | 4         | 4.65%   |
| Lenovo ThinkBook    | 3         | 3.49%   |
| Lenovo Legion       | 3         | 3.49%   |
| HP Laptop           | 3         | 3.49%   |
| Acer Aspire         | 3         | 3.49%   |
| HUAWEI HVY-WXX9     | 2         | 2.33%   |
| HP ZBook            | 2         | 2.33%   |
| HP Pavilion         | 2         | 2.33%   |
| HP ENVY             | 2         | 2.33%   |
| HP EliteBook        | 2         | 2.33%   |
| ASUS ZenBook        | 2         | 2.33%   |
| ASUS VivoBook       | 2         | 2.33%   |
| ASUS ASUS           | 2         | 2.33%   |
| TUXEDO InfinityBook | 1         | 1.16%   |
| Timi Xiaomi         | 1         | 1.16%   |
| Timi TM1701         | 1         | 1.16%   |
| Timi A35S           | 1         | 1.16%   |
| System76 Lemur      | 1         | 1.16%   |
| System76 Kudu       | 1         | 1.16%   |
| Schenker XMG        | 1         | 1.16%   |
| Samsung RV410       | 1         | 1.16%   |
| Samsung 270E5G      | 1         | 1.16%   |
| LG 16Z90P-G.AP75D   | 1         | 1.16%   |
| Irbis NB264         | 1         | 1.16%   |
| HUAWEI NBLB-WAX9N   | 1         | 1.16%   |
| HUAWEI CREM-WXX9    | 1         | 1.16%   |
| HUAWEI BOHK-WAX9X   | 1         | 1.16%   |
| HP 340S             | 1         | 1.16%   |
| GPD G1619-04        | 1         | 1.16%   |
| Dell Precision      | 1         | 1.16%   |
| Dell Inspiron       | 1         | 1.16%   |
| ASUS X550CL         | 1         | 1.16%   |
| ASUS K55VM          | 1         | 1.16%   |
| Acer Nitro          | 1         | 1.16%   |
| A-DATA XENIA        | 1         | 1.16%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 19        | 22.09%  |
| 2020 | 16        | 18.6%   |
| 2022 | 12        | 13.95%  |
| 2019 | 10        | 11.63%  |
| 2017 | 7         | 8.14%   |
| 2016 | 6         | 6.98%   |
| 2018 | 5         | 5.81%   |
| 2013 | 5         | 5.81%   |
| 2010 | 3         | 3.49%   |
| 2015 | 1         | 1.16%   |
| 2012 | 1         | 1.16%   |
| 2011 | 1         | 1.16%   |

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
| Disabled | 64        | 74.42%  |
| Enabled  | 22        | 25.58%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 85        | 98.84%  |
| Yes  | 1         | 1.16%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 26        | 30.23%  |
| 8.01-16.0  | 21        | 24.42%  |
| 16.01-24.0 | 18        | 20.93%  |
| 32.01-64.0 | 14        | 16.28%  |
| 3.01-4.0   | 3         | 3.49%   |
| 24.01-32.0 | 3         | 3.49%   |
| 2.01-3.0   | 1         | 1.16%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 4.01-8.0  | 28        | 31.82%  |
| 3.01-4.0  | 24        | 27.27%  |
| 2.01-3.0  | 23        | 26.14%  |
| 8.01-16.0 | 7         | 7.95%   |
| 1.01-2.0  | 5         | 5.68%   |
| 0.51-1.0  | 1         | 1.14%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 67        | 77.91%  |
| 2      | 18        | 20.93%  |
| 3      | 1         | 1.16%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 78        | 90.7%   |
| Yes       | 8         | 9.3%    |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 52        | 60.47%  |
| No        | 34        | 39.53%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 86        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 75        | 87.21%  |
| No        | 11        | 12.79%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country             | Notebooks | Percent |
|---------------------|-----------|---------|
| USA                 | 11        | 12.79%  |
| Germany             | 7         | 8.14%   |
| Russia              | 6         | 6.98%   |
| Italy               | 6         | 6.98%   |
| France              | 6         | 6.98%   |
| India               | 5         | 5.81%   |
| Brazil              | 5         | 5.81%   |
| Spain               | 4         | 4.65%   |
| Poland              | 3         | 3.49%   |
| Austria             | 3         | 3.49%   |
| UK                  | 2         | 2.33%   |
| Turkey              | 2         | 2.33%   |
| Thailand            | 2         | 2.33%   |
| Switzerland         | 2         | 2.33%   |
| Norway              | 2         | 2.33%   |
| Japan               | 2         | 2.33%   |
| Trinidad and Tobago | 1         | 1.16%   |
| South Africa        | 1         | 1.16%   |
| Slovakia            | 1         | 1.16%   |
| Puerto Rico         | 1         | 1.16%   |
| Philippines         | 1         | 1.16%   |
| Netherlands         | 1         | 1.16%   |
| Moldova             | 1         | 1.16%   |
| Mexico              | 1         | 1.16%   |
| Latvia              | 1         | 1.16%   |
| Kazakhstan          | 1         | 1.16%   |
| Ireland             | 1         | 1.16%   |
| Indonesia           | 1         | 1.16%   |
| Hungary             | 1         | 1.16%   |
| Ecuador             | 1         | 1.16%   |
| Czechia             | 1         | 1.16%   |
| Canada              | 1         | 1.16%   |
| Australia           | 1         | 1.16%   |
| Argentina           | 1         | 1.16%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Warsaw             | 3         | 3.49%   |
| Vienna             | 2         | 2.33%   |
| Sao Paulo          | 2         | 2.33%   |
| Oslo               | 2         | 2.33%   |
| Moscow             | 2         | 2.33%   |
| Bangkok            | 2         | 2.33%   |
| Zurich             | 1         | 1.16%   |
| Wytheville         | 1         | 1.16%   |
| Wellington         | 1         | 1.16%   |
| Wallisellen        | 1         | 1.16%   |
| Vignola            | 1         | 1.16%   |
| Udaipur            | 1         | 1.16%   |
| Uberlândia        | 1         | 1.16%   |
| Trieste            | 1         | 1.16%   |
| Tokyo              | 1         | 1.16%   |
| Surabaya           | 1         | 1.16%   |
| Shymkent           | 1         | 1.16%   |
| Shinagawa          | 1         | 1.16%   |
| Scarborough        | 1         | 1.16%   |
| Saratov            | 1         | 1.16%   |
| Sao Jose           | 1         | 1.16%   |
| San Miguel         | 1         | 1.16%   |
| San Andres Cholula | 1         | 1.16%   |
| Rosario            | 1         | 1.16%   |
| Riga               | 1         | 1.16%   |
| Redmond            | 1         | 1.16%   |
| Queens             | 1         | 1.16%   |
| Ponce              | 1         | 1.16%   |
| Plancher-les-Mines | 1         | 1.16%   |
| Paris              | 1         | 1.16%   |
| Palaiseau          | 1         | 1.16%   |
| Orekhovo-Zuyevo    | 1         | 1.16%   |
| Nizhniy Novgorod   | 1         | 1.16%   |
| New York           | 1         | 1.16%   |
| Navi Mumbai        | 1         | 1.16%   |
| Munich             | 1         | 1.16%   |
| Matzendorf         | 1         | 1.16%   |
| Marseille          | 1         | 1.16%   |
| Manchester         | 1         | 1.16%   |
| Málaga            | 1         | 1.16%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 28        | 31     | 26.42%  |
| WDC                         | 10        | 11     | 9.43%   |
| Sandisk                     | 9         | 9      | 8.49%   |
| SK hynix                    | 8         | 8      | 7.55%   |
| Micron Technology           | 6         | 6      | 5.66%   |
| Intel                       | 6         | 6      | 5.66%   |
| Seagate                     | 5         | 5      | 4.72%   |
| Kingston                    | 5         | 5      | 4.72%   |
| Toshiba                     | 4         | 4      | 3.77%   |
| Unknown                     | 3         | 4      | 2.83%   |
| KIOXIA                      | 3         | 4      | 2.83%   |
| HGST                        | 3         | 3      | 2.83%   |
| Micron/Crucial Technology   | 2         | 2      | 1.89%   |
| Crucial                     | 2         | 2      | 1.89%   |
| YMTC                        | 1         | 1      | 0.94%   |
| Yangtze Memory Technologies | 1         | 1      | 0.94%   |
| XPG                         | 1         | 1      | 0.94%   |
| UMIS                        | 1         | 1      | 0.94%   |
| Team                        | 1         | 2      | 0.94%   |
| LITEON                      | 1         | 1      | 0.94%   |
| Lexar                       | 1         | 1      | 0.94%   |
| Kingston Technology Company | 1         | 1      | 0.94%   |
| Hitachi                     | 1         | 1      | 0.94%   |
| GOODRAM                     | 1         | 1      | 0.94%   |
| ADATA Technology            | 1         | 1      | 0.94%   |
| A-DATA Technology           | 1         | 1      | 0.94%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB  | 5         | 4.63%   |
| SK hynix BC501 NVMe Solid State Drive 512GB          | 3         | 2.78%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 250GB | 3         | 2.78%   |
| Intel SSD 600P Series 256GB                          | 3         | 2.78%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                     | 2         | 1.85%   |
| Seagate ST1000LM035-1RK172 1TB                       | 2         | 1.85%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                   | 2         | 1.85%   |
| Samsung NVMe SSD Drive 1TB                           | 2         | 1.85%   |
| Samsung MZVLQ512HBLU-00BH1 512GB                     | 2         | 1.85%   |
| Samsung MZALQ512HBLU-00BL2 512GB                     | 2         | 1.85%   |
| Micron MTFDKBA512TFH 512GB                           | 2         | 1.85%   |
| Kingston OM8PCP3512F-AB 512GB                        | 2         | 1.85%   |
| YMTC PC005 512GB                                     | 1         | 0.93%   |
| Yangtze Memory NVMe SSD Drive 512GB                  | 1         | 0.93%   |
| XPG GAMMIX S50 Lite 1TB                              | 1         | 0.93%   |
| WDC WD5000LPCX-24VHAT0 500GB                         | 1         | 0.93%   |
| WDC WD10SPZX-80Z10T2 1TB                             | 1         | 0.93%   |
| WDC WD10SPZX-24Z10 1TB                               | 1         | 0.93%   |
| WDC WD10SPZX-21Z10T0 1TB                             | 1         | 0.93%   |
| WDC WD10SPZX-08Z10 1TB                               | 1         | 0.93%   |
| WDC PC SN730 SDBPNTY-512G-1027 512GB                 | 1         | 0.93%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB                 | 1         | 0.93%   |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB                 | 1         | 0.93%   |
| WDC PC SN520 SDAPMUW-128G-1001 128GB                 | 1         | 0.93%   |
| Unknown SL64G  64GB                                  | 1         | 0.93%   |
| Unknown SD256  249GB                                 | 1         | 0.93%   |
| Unknown MMC Card  128GB                              | 1         | 0.93%   |
| Unknown 032GE4  32GB                                 | 1         | 0.93%   |
| UMIS RPFTJ128PDD2EWX 128GB                           | 1         | 0.93%   |
| Toshiba NVMe SSD Drive 256GB                         | 1         | 0.93%   |
| Toshiba MQ04ABF100 1TB                               | 1         | 0.93%   |
| Toshiba MQ02ABD100H 1TB                              | 1         | 0.93%   |
| Toshiba MK3265GSX 320GB                              | 1         | 0.93%   |
| Team TM8PS7128G 128GB SSD                            | 1         | 0.93%   |
| SK hynix SKHynix_HFS001TEJ9X115N 1024GB              | 1         | 0.93%   |
| SK hynix SHGP31-1000GM-2 1TB                         | 1         | 0.93%   |
| SK hynix SHGP31-1000GM 1TB                           | 1         | 0.93%   |
| SK hynix PC801 NVMe 1TB                              | 1         | 0.93%   |
| SK hynix BC501 NVMe 256GB                            | 1         | 0.93%   |
| Seagate ST750LX003-1AC154 752GB                      | 1         | 0.93%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 5         | 5      | 29.41%  |
| Seagate | 5         | 5      | 29.41%  |
| Toshiba | 3         | 3      | 17.65%  |
| HGST    | 3         | 3      | 17.65%  |
| Hitachi | 1         | 1      | 5.88%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 3      | 16.67%  |
| Kingston            | 3         | 3      | 16.67%  |
| WDC                 | 2         | 2      | 11.11%  |
| Intel               | 2         | 2      | 11.11%  |
| Crucial             | 2         | 2      | 11.11%  |
| Team                | 1         | 2      | 5.56%   |
| Micron Technology   | 1         | 1      | 5.56%   |
| LITEON              | 1         | 1      | 5.56%   |
| Lexar               | 1         | 1      | 5.56%   |
| GOODRAM             | 1         | 1      | 5.56%   |
| A-DATA Technology   | 1         | 1      | 5.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 63        | 73     | 62.38%  |
| SSD  | 18        | 19     | 17.82%  |
| HDD  | 17        | 17     | 16.83%  |
| MMC  | 3         | 4      | 2.97%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 63        | 73     | 66.32%  |
| SATA | 29        | 36     | 30.53%  |
| MMC  | 3         | 4      | 3.16%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 20        | 22     | 58.82%  |
| 0.51-1.0   | 13        | 13     | 38.24%  |
| 1.01-2.0   | 1         | 1      | 2.94%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 16        | 18.39%  |
| 1-20           | 16        | 18.39%  |
| 1001-2000      | 15        | 17.24%  |
| 501-1000       | 15        | 17.24%  |
| 101-250        | 9         | 10.34%  |
| Unknown        | 7         | 8.05%   |
| 21-50          | 5         | 5.75%   |
| 51-100         | 2         | 2.3%    |
| More than 3000 | 1         | 1.15%   |
| 2001-3000      | 1         | 1.15%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 30        | 34.48%  |
| 101-250  | 15        | 17.24%  |
| 21-50    | 13        | 14.94%  |
| 51-100   | 8         | 9.2%    |
| 251-500  | 7         | 8.05%   |
| 501-1000 | 7         | 8.05%   |
| Unknown  | 7         | 8.05%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WDS240G2G0B-00EPW0 240GB SSD                    | 1         | 1      | 20%     |
| Toshiba MK3265GSX 320GB                             | 1         | 1      | 20%     |
| Micron Technology MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 1      | 20%     |
| HGST HTS721075A9E630 752GB                          | 1         | 1      | 20%     |
| HGST HTS721010A9E630 1TB                            | 1         | 1      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| HGST              | 2         | 2      | 40%     |
| WDC               | 1         | 1      | 20%     |
| Toshiba           | 1         | 1      | 20%     |
| Micron Technology | 1         | 1      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HGST    | 2         | 2      | 66.67%  |
| Toshiba | 1         | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 3         | 3      | 60%     |
| SSD  | 2         | 2      | 40%     |

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
| Detected | 48        | 64     | 52.75%  |
| Works    | 38        | 44     | 41.76%  |
| Malfunc  | 5         | 5      | 5.49%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 44        | 36.97%  |
| Samsung Electronics          | 25        | 21.01%  |
| SanDisk                      | 13        | 10.92%  |
| AMD                          | 10        | 8.4%    |
| SK hynix                     | 8         | 6.72%   |
| Micron Technology            | 5         | 4.2%    |
| Kingston Technology Company  | 3         | 2.52%   |
| Yangtze Memory Technologies  | 2         | 1.68%   |
| Toshiba America Info Systems | 2         | 1.68%   |
| Micron/Crucial Technology    | 2         | 1.68%   |
| KIOXIA                       | 2         | 1.68%   |
| Union Memory (Shenzhen)      | 1         | 0.84%   |
| Lite-On Technology           | 1         | 0.84%   |
| ADATA Technology             | 1         | 0.84%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 10        | 8.13%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 9         | 7.32%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 8         | 6.5%    |
| Samsung NVMe SSD Controller 980                                                | 7         | 5.69%   |
| Intel Volume Management Device NVMe RAID Controller                            | 6         | 4.88%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 6         | 4.88%   |
| Micron Non-Volatile memory controller                                          | 5         | 4.07%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 5         | 4.07%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 4         | 3.25%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 3.25%   |
| SanDisk Non-Volatile memory controller                                         | 3         | 2.44%   |
| Intel SSD 600P Series                                                          | 3         | 2.44%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 2.44%   |
| Yangtze Memory Non-Volatile memory controller                                  | 2         | 1.63%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 1.63%   |
| SK hynix Non-Volatile memory controller                                        | 2         | 1.63%   |
| SK hynix Gold P31 SSD                                                          | 2         | 1.63%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 2         | 1.63%   |
| SanDisk WD Blue SN570 NVMe SSD                                                 | 2         | 1.63%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 2         | 1.63%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 2         | 1.63%   |
| Micron/Crucial Non-Volatile memory controller                                  | 2         | 1.63%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 2         | 1.63%   |
| Kingston Company Company Non-Volatile memory controller                        | 2         | 1.63%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 1.63%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 1.63%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 1.63%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 1.63%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2         | 1.63%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 1         | 0.81%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 1         | 0.81%   |
| SanDisk PC SN520 NVMe SSD                                                      | 1         | 0.81%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 0.81%   |
| Lite-On SATA controller                                                        | 1         | 0.81%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 1         | 0.81%   |
| Intel Tiger Lake-LP SATA Controller                                            | 1         | 0.81%   |
| Intel SSD 660P Series                                                          | 1         | 0.81%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 1         | 0.81%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 0.81%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 0.81%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 63        | 53.85%  |
| SATA | 46        | 39.32%  |
| RAID | 8         | 6.84%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 64        | 74.42%  |
| AMD    | 22        | 25.58%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 4.65%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 3.49%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 3.49%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 3.49%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 2.33%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 2.33%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 2.33%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 2         | 2.33%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 2.33%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 2.33%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 2.33%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 2         | 2.33%   |
| Intel 12th Gen Core i9-12900H                 | 2         | 2.33%   |
| Intel 12th Gen Core i7-12700H                 | 2         | 2.33%   |
| Intel 12th Gen Core i5-1240P                  | 2         | 2.33%   |
| Intel 11th Gen Core i7-11850H @ 2.50GHz       | 2         | 2.33%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 2.33%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 2         | 2.33%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 2.33%   |
| AMD Ryzen 5 5625U with Radeon Graphics        | 2         | 2.33%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 2         | 2.33%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 2         | 2.33%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 1.16%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 1.16%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 1.16%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 1         | 1.16%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 1         | 1.16%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 1         | 1.16%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 1         | 1.16%   |
| Intel Core i5-9300HF CPU @ 2.40GHz            | 1         | 1.16%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 1         | 1.16%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 1         | 1.16%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 1         | 1.16%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 1.16%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 1         | 1.16%   |
| Intel Core i5-4310U CPU @ 2.00GHz             | 1         | 1.16%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 1.16%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 1         | 1.16%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 1.16%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 1.16%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 23        | 26.74%  |
| Other                   | 19        | 22.09%  |
| Intel Core i7           | 17        | 19.77%  |
| AMD Ryzen 5             | 11        | 12.79%  |
| AMD Ryzen 7             | 7         | 8.14%   |
| Intel Core i3           | 2         | 2.33%   |
| Intel Celeron           | 2         | 2.33%   |
| AMD Ryzen 9             | 2         | 2.33%   |
| Intel Pentium Dual-Core | 1         | 1.16%   |
| AMD Ryzen 7 PRO         | 1         | 1.16%   |
| AMD Ryzen 5 PRO         | 1         | 1.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 38        | 44.19%  |
| 2      | 16        | 18.6%   |
| 8      | 13        | 15.12%  |
| 6      | 11        | 12.79%  |
| 14     | 4         | 4.65%   |
| 12     | 3         | 3.49%   |
| 10     | 1         | 1.16%   |

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
| 2      | 80        | 93.02%  |
| 1      | 6         | 6.98%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 86        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x906a3    | 7         | 8.14%   |
| 0x806ec    | 7         | 8.14%   |
| 0x806c1    | 7         | 8.14%   |
| 0x0a50000c | 6         | 6.98%   |
| Unknown    | 5         | 5.81%   |
| 0x906ea    | 4         | 4.65%   |
| 0x806ea    | 4         | 4.65%   |
| 0x306a9    | 4         | 4.65%   |
| 0x08600106 | 4         | 4.65%   |
| 0x906e9    | 3         | 3.49%   |
| 0x806e9    | 3         | 3.49%   |
| 0x806d1    | 3         | 3.49%   |
| 0xa0652    | 2         | 2.33%   |
| 0x706e5    | 2         | 2.33%   |
| 0x506e3    | 2         | 2.33%   |
| 0x406e3    | 2         | 2.33%   |
| 0x40651    | 2         | 2.33%   |
| 0x306c3    | 2         | 2.33%   |
| 0x0a404102 | 2         | 2.33%   |
| 0x08608103 | 2         | 2.33%   |
| 0x08600104 | 2         | 2.33%   |
| 0x08108109 | 2         | 2.33%   |
| 0x906ed    | 1         | 1.16%   |
| 0x906a4    | 1         | 1.16%   |
| 0x706a8    | 1         | 1.16%   |
| 0x506c9    | 1         | 1.16%   |
| 0x206a7    | 1         | 1.16%   |
| 0x1067a    | 1         | 1.16%   |
| 0x0a50000d | 1         | 1.16%   |
| 0x08608102 | 1         | 1.16%   |
| 0x08108102 | 1         | 1.16%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 22        | 25.58%  |
| Zen 3            | 8         | 9.3%    |
| TigerLake        | 8         | 9.3%    |
| Alderlake Hybrid | 8         | 9.3%    |
| Zen 2            | 6         | 6.98%   |
| IceLake          | 6         | 6.98%   |
| Skylake          | 5         | 5.81%   |
| Unknown          | 5         | 5.81%   |
| IvyBridge        | 4         | 4.65%   |
| Haswell          | 4         | 4.65%   |
| Zen+             | 3         | 3.49%   |
| CometLake        | 2         | 2.33%   |
| SandyBridge      | 1         | 1.16%   |
| Penryn           | 1         | 1.16%   |
| Nehalem          | 1         | 1.16%   |
| Goldmont plus    | 1         | 1.16%   |
| Goldmont         | 1         | 1.16%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 60        | 52.63%  |
| Nvidia | 30        | 26.32%  |
| AMD    | 24        | 21.05%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                            | 7         | 6.09%   |
| Intel Alder Lake-P Integrated Graphics Controller                    | 7         | 6.09%   |
| AMD Renoir                                                           | 6         | 5.22%   |
| AMD Cezanne                                                          | 6         | 5.22%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                           | 4         | 3.48%   |
| Intel UHD Graphics 620                                               | 4         | 3.48%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                            | 4         | 3.48%   |
| Intel 3rd Gen Core processor Graphics Controller                     | 4         | 3.48%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                           | 3         | 2.61%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                      | 3         | 2.61%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                 | 3         | 2.61%   |
| Intel Skylake GT2 [HD Graphics 520]                                  | 3         | 2.61%   |
| Intel HD Graphics 630                                                | 3         | 2.61%   |
| Intel HD Graphics 620                                                | 3         | 2.61%   |
| Intel CometLake-U GT2 [UHD Graphics]                                 | 3         | 2.61%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series] | 3         | 2.61%   |
| AMD Lucienne                                                         | 3         | 2.61%   |
| Nvidia GP108M [GeForce MX150]                                        | 2         | 1.74%   |
| Nvidia GM107GLM [Quadro M1000M]                                      | 2         | 1.74%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M] | 2         | 1.74%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                               | 2         | 1.74%   |
| Intel Haswell-ULT Integrated Graphics Controller                     | 2         | 1.74%   |
| Intel CometLake-H GT2 [UHD Graphics]                                 | 2         | 1.74%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller          | 2         | 1.74%   |
| AMD Rembrandt [Radeon 680M]                                          | 2         | 1.74%   |
| AMD Barcelo                                                          | 2         | 1.74%   |
| Nvidia TU117M [GeForce MX450]                                        | 1         | 0.87%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                           | 1         | 0.87%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                      | 1         | 0.87%   |
| Nvidia TU117M                                                        | 1         | 0.87%   |
| Nvidia TU117GLM [T1200 Laptop GPU]                                   | 1         | 0.87%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                              | 1         | 0.87%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                              | 1         | 0.87%   |
| Nvidia GT216GLM [Quadro FX 880M]                                     | 1         | 0.87%   |
| Nvidia GP108M [GeForce MX250]                                        | 1         | 0.87%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                              | 1         | 0.87%   |
| Nvidia GM108M [GeForce MX110]                                        | 1         | 0.87%   |
| Nvidia GM108M [GeForce 940MX]                                        | 1         | 0.87%   |
| Nvidia GK106GLM [Quadro K2100M]                                      | 1         | 0.87%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                    | 1         | 0.87%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 33        | 38.37%  |
| Intel + Nvidia | 24        | 27.91%  |
| 1 x AMD        | 21        | 24.42%  |
| 1 x Nvidia     | 5         | 5.81%   |
| 2 x AMD        | 1         | 1.16%   |
| Intel + AMD    | 1         | 1.16%   |
| AMD + Nvidia   | 1         | 1.16%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 69        | 80.23%  |
| Proprietary | 16        | 18.6%   |
| Unknown     | 1         | 1.16%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 47        | 54.65%  |
| 0.01-0.5   | 14        | 16.28%  |
| 1.01-2.0   | 10        | 11.63%  |
| 3.01-4.0   | 7         | 8.14%   |
| 0.51-1.0   | 4         | 4.65%   |
| 5.01-6.0   | 3         | 3.49%   |
| 8.01-16.0  | 1         | 1.16%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 22        | 21.15%  |
| AU Optronics            | 20        | 19.23%  |
| Chimei Innolux          | 13        | 12.5%   |
| LG Display              | 9         | 8.65%   |
| Samsung Electronics     | 5         | 4.81%   |
| Sharp                   | 4         | 3.85%   |
| PANDA                   | 4         | 3.85%   |
| Goldstar                | 4         | 3.85%   |
| CSO                     | 4         | 3.85%   |
| Hewlett-Packard         | 3         | 2.88%   |
| Dell                    | 3         | 2.88%   |
| Lenovo                  | 2         | 1.92%   |
| InfoVision              | 2         | 1.92%   |
| Chi Mei Optoelectronics | 2         | 1.92%   |
| BenQ                    | 2         | 1.92%   |
| ViewSonic               | 1         | 0.96%   |
| Vestel Elektronik       | 1         | 0.96%   |
| TMX                     | 1         | 0.96%   |
| JDI                     | 1         | 0.96%   |
| Arnos Instruments       | 1         | 0.96%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14FF 1920x1080 309x173mm 13.9-inch       | 4         | 3.77%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch           | 2         | 1.89%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch       | 2         | 1.89%   |
| BOE LCD Monitor BOE0878 1920x1080 355x200mm 16.0-inch                  | 2         | 1.89%   |
| BOE LCD Monitor BOE084D 1920x1080 344x193mm 15.5-inch                  | 2         | 1.89%   |
| ViewSonic VX2410 SERIES VSCEF2D 1920x1080 521x293mm 23.5-inch          | 1         | 0.94%   |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 1         | 0.94%   |
| TMX TL156VDXP0101 TMX1561 1920x1080 344x194mm 15.5-inch                | 1         | 0.94%   |
| Sharp LCD Monitor SHP1547 1920x1200 288x180mm 13.4-inch                | 1         | 0.94%   |
| Sharp LCD Monitor SHP1516 3840x2400 336x210mm 15.6-inch                | 1         | 0.94%   |
| Sharp LCD Monitor SHP14CB 1920x1200 288x180mm 13.4-inch                | 1         | 0.94%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                | 1         | 0.94%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch   | 1         | 0.94%   |
| Samsung Electronics LCD Monitor SDC4173 3840x2400 344x215mm 16.0-inch  | 1         | 0.94%   |
| Samsung Electronics LCD Monitor SDC4150 3456x2160 336x210mm 15.6-inch  | 1         | 0.94%   |
| Samsung Electronics LC32G7xT SAM705A 2560x1440 698x393mm 31.5-inch     | 1         | 0.94%   |
| Samsung Electronics LC27G5xT SAM7079 2560x1440 597x336mm 27.0-inch     | 1         | 0.94%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                | 1         | 0.94%   |
| PANDA LCD Monitor NCP004B 1920x1080 344x194mm 15.5-inch                | 1         | 0.94%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                | 1         | 0.94%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch                | 1         | 0.94%   |
| LG Display LCD Monitor LGD06D6 1920x1080 309x174mm 14.0-inch           | 1         | 0.94%   |
| LG Display LCD Monitor LGD0694 2560x1600 344x215mm 16.0-inch           | 1         | 0.94%   |
| LG Display LCD Monitor LGD068D 1920x1080 309x174mm 14.0-inch           | 1         | 0.94%   |
| LG Display LCD Monitor LGD056D 1920x1080 382x215mm 17.3-inch           | 1         | 0.94%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch           | 1         | 0.94%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch           | 1         | 0.94%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch            | 1         | 0.94%   |
| Lenovo LEN P24h-20 LEN61F4 2560x1440 527x296mm 23.8-inch               | 1         | 0.94%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch                | 1         | 0.94%   |
| JDI GPD1001H JDI0031 2560x1600 890x500mm 40.2-inch                     | 1         | 0.94%   |
| InfoVision LCD Monitor IVO854A 1920x1200 286x179mm 13.3-inch           | 1         | 0.94%   |
| InfoVision LCD Monitor IVO03F4 1920x1080 309x173mm 13.9-inch           | 1         | 0.94%   |
| Hewlett-Packard OMEN by HP 32 HPN3378 2560x1440 708x399mm 32.0-inch    | 1         | 0.94%   |
| Hewlett-Packard OMEN by HP 27 HPN3422 2560x1440 598x336mm 27.0-inch    | 1         | 0.94%   |
| Hewlett-Packard E271i HWP3106 1920x1080 600x340mm 27.2-inch            | 1         | 0.94%   |
| Goldstar W2252 GSM567D 1680x1050 490x320mm 23.0-inch                   | 1         | 0.94%   |
| Goldstar M198WDP GSM4B88 1440x900 408x229mm 18.4-inch                  | 1         | 0.94%   |
| Goldstar LG HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch               | 1         | 0.94%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                | 1         | 0.94%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 56        | 55.45%  |
| 1366x768 (WXGA)    | 11        | 10.89%  |
| 1920x1200 (WUXGA)  | 8         | 7.92%   |
| 2560x1440 (QHD)    | 6         | 5.94%   |
| 3840x2160 (4K)     | 4         | 3.96%   |
| 2560x1600          | 4         | 3.96%   |
| 3840x2400          | 2         | 1.98%   |
| 1600x900 (HD+)     | 2         | 1.98%   |
| 3456x2160          | 1         | 0.99%   |
| 3440x1440          | 1         | 0.99%   |
| 2880x1800          | 1         | 0.99%   |
| 2560x1080          | 1         | 0.99%   |
| 2520x1680          | 1         | 0.99%   |
| 1680x1050 (WSXGA+) | 1         | 0.99%   |
| 1440x900 (WXGA+)   | 1         | 0.99%   |
| 1280x1024 (SXGA)   | 1         | 0.99%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 38        | 36.19%  |
| 13     | 20        | 19.05%  |
| 14     | 12        | 11.43%  |
| 16     | 7         | 6.67%   |
| 27     | 5         | 4.76%   |
| 17     | 4         | 3.81%   |
| 12     | 4         | 3.81%   |
| 24     | 3         | 2.86%   |
| 23     | 3         | 2.86%   |
| 34     | 2         | 1.9%    |
| 31     | 2         | 1.9%    |
| 18     | 2         | 1.9%    |
| 84     | 1         | 0.95%   |
| 40     | 1         | 0.95%   |
| 32     | 1         | 0.95%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 69        | 66.99%  |
| 501-600     | 9         | 8.74%   |
| 201-300     | 9         | 8.74%   |
| 351-400     | 7         | 6.8%    |
| 701-800     | 3         | 2.91%   |
| 601-700     | 2         | 1.94%   |
| 401-500     | 2         | 1.94%   |
| 801-900     | 1         | 0.97%   |
| 1501-2000   | 1         | 0.97%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 74        | 79.57%  |
| 16/10 | 14        | 15.05%  |
| 3/2   | 2         | 2.15%   |
| 21/9  | 2         | 2.15%   |
| 5/4   | 1         | 1.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 39        | 37.14%  |
| 81-90          | 27        | 25.71%  |
| 111-120        | 6         | 5.71%   |
| 71-80          | 5         | 4.76%   |
| 351-500        | 5         | 4.76%   |
| 301-350        | 5         | 4.76%   |
| 61-70          | 4         | 3.81%   |
| 201-250        | 4         | 3.81%   |
| 121-130        | 4         | 3.81%   |
| 251-300        | 2         | 1.9%    |
| More than 1000 | 1         | 0.95%   |
| 151-200        | 1         | 0.95%   |
| 141-150        | 1         | 0.95%   |
| 501-1000       | 1         | 0.95%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 53        | 53%     |
| 51-100        | 16        | 16%     |
| 161-240       | 15        | 15%     |
| 101-120       | 10        | 10%     |
| More than 240 | 6         | 6%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 68        | 77.27%  |
| 2     | 16        | 18.18%  |
| 3     | 3         | 3.41%   |
| 0     | 1         | 1.14%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 60        | 48.39%  |
| Realtek Semiconductor    | 41        | 33.06%  |
| Qualcomm Atheros         | 12        | 9.68%   |
| MediaTek                 | 3         | 2.42%   |
| Sierra Wireless          | 2         | 1.61%   |
| Ralink                   | 1         | 0.81%   |
| Marvell Technology Group | 1         | 0.81%   |
| Lenovo                   | 1         | 0.81%   |
| Hewlett-Packard          | 1         | 0.81%   |
| Google                   | 1         | 0.81%   |
| Dell                     | 1         | 0.81%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 26        | 18.06%  |
| Intel Wi-Fi 6 AX200                                               | 13        | 9.03%   |
| Intel Wi-Fi 6 AX201                                               | 7         | 4.86%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 7         | 4.86%   |
| Intel Wireless 8265 / 8275                                        | 5         | 3.47%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 2.78%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 4         | 2.78%   |
| Intel Wireless 8260                                               | 4         | 2.78%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 4         | 2.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 2.08%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 2.08%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 2.08%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 3         | 2.08%   |
| Intel Wireless 7260                                               | 3         | 2.08%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 3         | 2.08%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 2.08%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 2.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.39%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 1.39%   |
| Realtek Realtek Network controller                                | 2         | 1.39%   |
| Intel Ethernet Controller I225-LM                                 | 2         | 1.39%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.39%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 1.39%   |
| Intel Centrino Ultimate-N 6300                                    | 2         | 1.39%   |
| Sierra Wireless EM7455 Qualcomm Snapdragon X7 LTE-A               | 1         | 0.69%   |
| Sierra Wireless EM7345 4G LTE                                     | 1         | 0.69%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1         | 0.69%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 0.69%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.69%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 1         | 0.69%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 0.69%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 0.69%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 0.69%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 0.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.69%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.69%   |
| Lenovo USB-C Dock Ethernet                                        | 1         | 0.69%   |
| Intel Wireless-AC 9260                                            | 1         | 0.69%   |
| Intel Wireless 7265                                               | 1         | 0.69%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 60        | 65.93%  |
| Realtek Semiconductor | 12        | 13.19%  |
| Qualcomm Atheros      | 11        | 12.09%  |
| MediaTek              | 3         | 3.3%    |
| Sierra Wireless       | 2         | 2.2%    |
| Ralink                | 1         | 1.1%    |
| Hewlett-Packard       | 1         | 1.1%    |
| Dell                  | 1         | 1.1%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 13        | 14.29%  |
| Intel Wi-Fi 6 AX201                                            | 7         | 7.69%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 7         | 7.69%   |
| Intel Wireless 8265 / 8275                                     | 5         | 5.49%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 4         | 4.4%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 4         | 4.4%    |
| Intel Wireless 8260                                            | 4         | 4.4%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 4         | 4.4%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 3         | 3.3%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 3         | 3.3%    |
| Intel Wireless 7260                                            | 3         | 3.3%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 3         | 3.3%    |
| Intel Cannon Lake PCH CNVi WiFi                                | 3         | 3.3%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 2.2%    |
| Realtek Realtek Network controller                             | 2         | 2.2%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 2.2%    |
| Intel Centrino Ultimate-N 6300                                 | 2         | 2.2%    |
| Sierra Wireless EM7455 Qualcomm Snapdragon X7 LTE-A            | 1         | 1.1%    |
| Sierra Wireless EM7345 4G LTE                                  | 1         | 1.1%    |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1         | 1.1%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 1.1%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.1%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 1         | 1.1%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 1         | 1.1%    |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 1         | 1.1%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 1.1%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 1.1%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 1.1%    |
| Intel Wireless-AC 9260                                         | 1         | 1.1%    |
| Intel Wireless 7265                                            | 1         | 1.1%    |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1         | 1.1%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 1.1%    |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 1.1%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 1         | 1.1%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 1.1%    |
| HP lt4112 Gobi 4G Module Network Device                        | 1         | 1.1%    |
| Dell DW5811e Snapdragonâ¢ X7 LTE                           | 1         | 1.1%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 33        | 63.46%  |
| Intel                    | 15        | 28.85%  |
| Qualcomm Atheros         | 1         | 1.92%   |
| Marvell Technology Group | 1         | 1.92%   |
| Lenovo                   | 1         | 1.92%   |
| Google                   | 1         | 1.92%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 26        | 49.06%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 5.66%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 5.66%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 5.66%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 3.77%   |
| Intel Ethernet Controller I225-LM                                 | 2         | 3.77%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 3.77%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.89%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 1.89%   |
| Lenovo USB-C Dock Ethernet                                        | 1         | 1.89%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.89%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.89%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.89%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.89%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.89%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.89%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 1.89%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.89%   |
| Google Pixel 6 Pro                                                | 1         | 1.89%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 86        | 62.32%  |
| Ethernet | 52        | 37.68%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 78        | 85.71%  |
| Ethernet | 13        | 14.29%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 46        | 53.49%  |
| 1     | 37        | 43.02%  |
| 3     | 2         | 2.33%   |
| 0     | 1         | 1.16%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 64        | 74.42%  |
| Yes  | 22        | 25.58%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 54        | 72.97%  |
| Realtek Semiconductor           | 7         | 9.46%   |
| Qualcomm Atheros Communications | 5         | 6.76%   |
| Lite-On Technology              | 3         | 4.05%   |
| IMC Networks                    | 2         | 2.7%    |
| Foxconn / Hon Hai               | 2         | 2.7%    |
| Realtek                         | 1         | 1.35%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface             | 12        | 16.22%  |
| Intel AX201 Bluetooth                          | 12        | 16.22%  |
| Intel AX200 Bluetooth                          | 12        | 16.22%  |
| Intel Bluetooth Device                         | 7         | 9.46%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 6         | 8.11%   |
| Realtek Bluetooth Radio                        | 5         | 6.76%   |
| Qualcomm Atheros  Bluetooth Device             | 4         | 5.41%   |
| Intel AX210 Bluetooth                          | 4         | 5.41%   |
| Lite-On Bluetooth Device                       | 2         | 2.7%    |
| Realtek RTL8821A Bluetooth                     | 1         | 1.35%   |
| Realtek RTL8723B Bluetooth                     | 1         | 1.35%   |
| Realtek Bluetooth Radio                        | 1         | 1.35%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0          | 1         | 1.35%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth     | 1         | 1.35%   |
| Intel Wireless-AC 9260 Bluetooth Adapter       | 1         | 1.35%   |
| IMC Networks Wireless_Device                   | 1         | 1.35%   |
| IMC Networks Bluetooth Radio                   | 1         | 1.35%   |
| Foxconn / Hon Hai Wireless_Device              | 1         | 1.35%   |
| Foxconn / Hon Hai Bluetooth Device             | 1         | 1.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 64        | 55.65%  |
| AMD                                  | 22        | 19.13%  |
| Nvidia                               | 20        | 17.39%  |
| Lenovo                               | 2         | 1.74%   |
| C-Media Electronics                  | 2         | 1.74%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.87%   |
| Samsung Electronics                  | 1         | 0.87%   |
| Razer USA                            | 1         | 0.87%   |
| Microchip Technology                 | 1         | 0.87%   |
| JMTek                                | 1         | 0.87%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                              | 20        | 14.39%  |
| AMD Renoir Radeon High Definition Audio Controller                  | 17        | 12.23%  |
| Intel Sunrise Point-LP HD Audio                                     | 10        | 7.19%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller         | 8         | 5.76%   |
| Intel Alder Lake PCH-P High Definition Audio Controller             | 8         | 5.76%   |
| Intel Cannon Lake PCH cAVS                                          | 5         | 3.6%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller      | 4         | 2.88%   |
| Nvidia GP107GL High Definition Audio Controller                     | 4         | 2.88%   |
| Intel Cannon Point-LP High Definition Audio Controller              | 4         | 2.88%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 4         | 2.88%   |
| Nvidia GA106 High Definition Audio Controller                       | 3         | 2.16%   |
| Intel Tiger Lake-H HD Audio Controller                              | 3         | 2.16%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller           | 3         | 2.16%   |
| Intel Comet Lake PCH-LP cAVS                                        | 3         | 2.16%   |
| Intel CM238 HD Audio Controller                                     | 3         | 2.16%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                 | 3         | 2.16%   |
| Nvidia TU106 High Definition Audio Controller                       | 2         | 1.44%   |
| Nvidia Audio device                                                 | 2         | 1.44%   |
| Intel Haswell-ULT HD Audio Controller                               | 2         | 1.44%   |
| Intel Comet Lake PCH cAVS                                           | 2         | 1.44%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 2         | 1.44%   |
| Intel 8 Series HD Audio Controller                                  | 2         | 1.44%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller     | 2         | 1.44%   |
| AMD Rembrandt Radeon High Definition Audio Controller               | 2         | 1.44%   |
| Thesycon Systemsoftware & Consulting D10s                           | 1         | 0.72%   |
| Samsung Electronics USB C Earphone                                  | 1         | 0.72%   |
| Razer USA Kraken 7.1 V2                                             | 1         | 0.72%   |
| Nvidia GT216 HDMI Audio Controller                                  | 1         | 0.72%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]       | 1         | 0.72%   |
| Nvidia GK106 HDMI Audio Controller                                  | 1         | 0.72%   |
| Nvidia GF108 High Definition Audio Controller                       | 1         | 0.72%   |
| Nvidia GA104 High Definition Audio Controller                       | 1         | 0.72%   |
| Microchip Technology HP Wireless Audio Adapter                      | 1         | 0.72%   |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                           | 1         | 0.72%   |
| Lenovo ThinkPad Dock USB Audio                                      | 1         | 0.72%   |
| JMTek audio controller                                              | 1         | 0.72%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller    | 1         | 0.72%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio        | 1         | 0.72%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster   | 1         | 0.72%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                      | 1         | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 19        | 33.93%  |
| Samsung Electronics | 18        | 32.14%  |
| Micron Technology   | 6         | 10.71%  |
| Kingston            | 3         | 5.36%   |
| Unknown             | 2         | 3.57%   |
| A-DATA Technology   | 2         | 3.57%   |
| Unknown             | 2         | 3.57%   |
| Smart Brazil        | 1         | 1.79%   |
| Goldkey             | 1         | 1.79%   |
| G.Skill             | 1         | 1.79%   |
| Crucial             | 1         | 1.79%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s             | 2         | 3.28%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 3.28%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 2         | 3.28%   |
| Samsung RAM M425R2GA3BB0-CQKOL 16GB SODIMM DDR5 4800MT/s         | 2         | 3.28%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 2         | 3.28%   |
| Unknown                                                          | 2         | 3.28%   |
| Unknown RAM Module 8GB Row Of Chips LPDDR4 4267MT/s              | 1         | 1.64%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                       | 1         | 1.64%   |
| Unknown RAM Module 1GB SODIMM DDR2 800MT/s                       | 1         | 1.64%   |
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s     | 1         | 1.64%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2133MT/s                    | 1         | 1.64%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.64%   |
| SK hynix RAM HMAB2GS6CMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 1.64%   |
| SK hynix RAM HMAA4GS6CJR8N-XN 32GB SODIMM DDR4 3200MT/s          | 1         | 1.64%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s        | 1         | 1.64%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 1.64%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 1.64%   |
| SK hynix RAM HMA82GS6MFR8N-TF 16GB SODIMM DDR4 2133MT/s          | 1         | 1.64%   |
| SK hynix RAM HMA81GS6MFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 1         | 1.64%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.64%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 1         | 1.64%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.64%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 1.64%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s           | 1         | 1.64%   |
| SK hynix RAM HMA425S6BJR6N-UH 2GB SODIMM DDR4 2667MT/s           | 1         | 1.64%   |
| SK hynix RAM HCNNNFAMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s   | 1         | 1.64%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 4GB Row Of Chips LPDDR5 6400MT/s | 1         | 1.64%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips LPDDR5 6400MT/s | 1         | 1.64%   |
| SK hynix RAM H5AN8G6NCJR-VKC 4GB SODIMM DDR4 2667MT/s            | 1         | 1.64%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.64%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.64%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.64%   |
| Samsung RAM M471B1G73DM0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.64%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 1         | 1.64%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 1.64%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 1.64%   |
| Samsung RAM M471A5244BB0-CPB 4GB SODIMM DDR4 2400MT/s            | 1         | 1.64%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 1         | 1.64%   |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 1         | 1.64%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.64%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 27        | 61.36%  |
| LPDDR4 | 5         | 11.36%  |
| LPDDR5 | 4         | 9.09%   |
| DDR3   | 3         | 6.82%   |
| LPDDR3 | 2         | 4.55%   |
| DDR5   | 2         | 4.55%   |
| DDR2   | 1         | 2.27%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 31        | 70.45%  |
| Row Of Chips | 12        | 27.27%  |
| DIMM         | 1         | 2.27%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 26        | 50.98%  |
| 4096  | 12        | 23.53%  |
| 16384 | 7         | 13.73%  |
| 2048  | 3         | 5.88%   |
| 32768 | 2         | 3.92%   |
| 1024  | 1         | 1.96%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 14        | 28%     |
| 2667  | 11        | 22%     |
| 2133  | 6         | 12%     |
| 6400  | 4         | 8%      |
| 2400  | 4         | 8%      |
| 4267  | 3         | 6%      |
| 1600  | 3         | 6%      |
| 4800  | 2         | 4%      |
| 4266  | 1         | 2%      |
| 3266  | 1         | 2%      |
| 800   | 1         | 2%      |

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
| Chicony Electronics                    | 22        | 28.21%  |
| IMC Networks                           | 13        | 16.67%  |
| Quanta                                 | 7         | 8.97%   |
| Acer                                   | 7         | 8.97%   |
| Sunplus Innovation Technology          | 5         | 6.41%   |
| Lite-On Technology                     | 5         | 6.41%   |
| Microdia                               | 4         | 5.13%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 3.85%   |
| Syntek                                 | 2         | 2.56%   |
| Silicon Motion                         | 2         | 2.56%   |
| USB Camera CS                          | 1         | 1.28%   |
| Tripath Technology                     | 1         | 1.28%   |
| Realtek Semiconductor                  | 1         | 1.28%   |
| Luxvisions Innotech Limited            | 1         | 1.28%   |
| Logitech                               | 1         | 1.28%   |
| Lenovo                                 | 1         | 1.28%   |
| Importek                               | 1         | 1.28%   |
| Goodong Industry                       | 1         | 1.28%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 9         | 11.54%  |
| Acer Integrated Camera                                          | 5         | 6.41%   |
| Quanta HD Webcam                                                | 4         | 5.13%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 4         | 5.13%   |
| Microdia Integrated_Webcam_HD                                   | 3         | 3.85%   |
| Lite-On Integrated Camera                                       | 3         | 3.85%   |
| Chicony USB2.0 Camera                                           | 3         | 3.85%   |
| Syntek EasyCamera                                               | 2         | 2.56%   |
| Sunplus Integrated_Webcam_HD                                    | 2         | 2.56%   |
| IMC Networks ov9734_azurewave_camera                            | 2         | 2.56%   |
| IMC Networks Integrated Camera                                  | 2         | 2.56%   |
| IMC Networks HD Camera                                          | 2         | 2.56%   |
| Chicony HD Webcam                                               | 2         | 2.56%   |
| Cheng Uei Precision Industry (Foxlink) HP True Vision HD Camera | 2         | 2.56%   |
| USB Camera CS USB Camera CS                                     | 1         | 1.28%   |
| Tripath USB Camera                                              | 1         | 1.28%   |
| Sunplus XiaoMi WebCam                                           | 1         | 1.28%   |
| Sunplus Integrated_Webcam_FHD                                   | 1         | 1.28%   |
| Sunplus Integrated Webcam                                       | 1         | 1.28%   |
| Silicon Motion WebCam SCB-0355N                                 | 1         | 1.28%   |
| Silicon Motion WebCam SC-10HDD12636N                            | 1         | 1.28%   |
| Realtek Integrated_Webcam_HD                                    | 1         | 1.28%   |
| Quanta USB2.0 VGA UVC WebCam                                    | 1         | 1.28%   |
| Quanta HP Wide Vision HD Camera                                 | 1         | 1.28%   |
| Quanta HP TrueVision HD Camera                                  | 1         | 1.28%   |
| Microdia Integrated_Webcam_FHD                                  | 1         | 1.28%   |
| Luxvisions Innotech Limited Integrated RGB Camera               | 1         | 1.28%   |
| Logitech Webcam C310                                            | 1         | 1.28%   |
| Lite-On HP Wide Vision HD Camera                                | 1         | 1.28%   |
| Lite-On HP HD Camera                                            | 1         | 1.28%   |
| Lenovo Integrated Webcam [R5U877]                               | 1         | 1.28%   |
| Importek HP TrueVision HD                                       | 1         | 1.28%   |
| IMC Networks XiaoMi Webcam                                      | 1         | 1.28%   |
| IMC Networks UVC VGA Webcam                                     | 1         | 1.28%   |
| IMC Networks HP TrueVision HD Camera                            | 1         | 1.28%   |
| Goodong Industry USB2.0 HD UVC WebCam                           | 1         | 1.28%   |
| Chicony XiaoMi USB 2.0 Webcam                                   | 1         | 1.28%   |
| Chicony USB2.0 HD UVC WebCam                                    | 1         | 1.28%   |
| Chicony LG Camera                                               | 1         | 1.28%   |
| Chicony Lenovo Integrated Camera (0.3MP)                        | 1         | 1.28%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Elan Microelectronics      | 8         | 29.63%  |
| Synaptics                  | 7         | 25.93%  |
| Shenzhen Goodix Technology | 7         | 25.93%  |
| Validity Sensors           | 4         | 14.81%  |
| Upek                       | 1         | 3.7%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 6         | 22.22%  |
| Shenzhen Goodix  Fingerprint Device                    | 6         | 22.22%  |
| Elan ELAN:Fingerprint                                  | 4         | 14.81%  |
| Elan ELAN:ARM-M4                                       | 4         | 14.81%  |
| Validity Sensors VFS495 Fingerprint Reader             | 2         | 7.41%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 3.7%    |
| Validity Sensors Synaptics WBDI                        | 1         | 3.7%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 3.7%    |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 3.7%    |
| Shenzhen Goodix FingerPrint                            | 1         | 3.7%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 4         | 57.14%  |
| Lenovo                | 1         | 14.29%  |
| Gemalto (was Gemplus) | 1         | 14.29%  |
| Alcor Micro           | 1         | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Broadcom 5880                                          | 2         | 28.57%  |
| Broadcom 58200                                         | 2         | 28.57%  |
| Lenovo Integrated Smart Card Reader                    | 1         | 14.29%  |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer | 1         | 14.29%  |
| Alcor Micro AU9540 Smartcard Reader                    | 1         | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 43        | 49.43%  |
| 1     | 37        | 42.53%  |
| 2     | 4         | 4.6%    |
| 3     | 2         | 2.3%    |
| 5     | 1         | 1.15%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 26        | 47.27%  |
| Graphics card            | 10        | 18.18%  |
| Camera                   | 5         | 9.09%   |
| Multimedia controller    | 4         | 7.27%   |
| Net/wireless             | 3         | 5.45%   |
| Chipcard                 | 2         | 3.64%   |
| Card reader              | 2         | 3.64%   |
| Sound                    | 1         | 1.82%   |
| Communication controller | 1         | 1.82%   |
| Bluetooth                | 1         | 1.82%   |

