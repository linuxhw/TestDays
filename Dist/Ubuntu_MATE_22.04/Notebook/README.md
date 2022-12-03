Ubuntu MATE 22.04 - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu MATE 22.04.

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

Total: 103

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | ProBook 450 G6              | [c9e94d483e](https://linux-hardware.org/?probe=c9e94d483e) | Nov 30, 2022 |
| Notebook      | NJx0MU                      | [d53007b0b3](https://linux-hardware.org/?probe=d53007b0b3) | Nov 30, 2022 |
| Acer          | TravelMate P614-51T-G2      | [37e14fc1c1](https://linux-hardware.org/?probe=37e14fc1c1) | Nov 30, 2022 |
| ASUSTek       | X555LAB                     | [d62cc93587](https://linux-hardware.org/?probe=d62cc93587) | Nov 28, 2022 |
| ASUSTek       | X555LAB                     | [8d8fc0d4d4](https://linux-hardware.org/?probe=8d8fc0d4d4) | Nov 28, 2022 |
| Acer          | Aspire A515-45              | [4cec4d0e04](https://linux-hardware.org/?probe=4cec4d0e04) | Nov 27, 2022 |
| Notebook      | NJx0MU                      | [05d0bf9d8d](https://linux-hardware.org/?probe=05d0bf9d8d) | Nov 25, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [9e22e08aa1](https://linux-hardware.org/?probe=9e22e08aa1) | Nov 25, 2022 |
| HP            | ProBook 640 G8 Notebook ... | [ce586530e4](https://linux-hardware.org/?probe=ce586530e4) | Nov 24, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [cf30d2df93](https://linux-hardware.org/?probe=cf30d2df93) | Nov 24, 2022 |
| Notebook      | NJx0MU                      | [bc690a128e](https://linux-hardware.org/?probe=bc690a128e) | Nov 23, 2022 |
| Toshiba       | Satellite P50-B-10Z         | [c5413ac393](https://linux-hardware.org/?probe=c5413ac393) | Nov 19, 2022 |
| Acer          | Swift SF114-34              | [96d82e20c4](https://linux-hardware.org/?probe=96d82e20c4) | Nov 19, 2022 |
| Acer          | Swift SF114-34              | [f5fd517d69](https://linux-hardware.org/?probe=f5fd517d69) | Nov 19, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [d4b8ffffe1](https://linux-hardware.org/?probe=d4b8ffffe1) | Nov 19, 2022 |
| Notebook      | NJx0MU                      | [f2e60e58dc](https://linux-hardware.org/?probe=f2e60e58dc) | Nov 17, 2022 |
| Notebook      | NJx0MU                      | [fe43edb930](https://linux-hardware.org/?probe=fe43edb930) | Nov 16, 2022 |
| Dell          | Latitude D630               | [3a15603bd6](https://linux-hardware.org/?probe=3a15603bd6) | Nov 13, 2022 |
| Dell          | Latitude D630               | [3e964fdd59](https://linux-hardware.org/?probe=3e964fdd59) | Nov 12, 2022 |
| ASUSTek       | K93SV                       | [8511ee86ad](https://linux-hardware.org/?probe=8511ee86ad) | Nov 12, 2022 |
| Notebook      | NJx0MU                      | [2dc75b76f4](https://linux-hardware.org/?probe=2dc75b76f4) | Nov 12, 2022 |
| Notebook      | NJx0MU                      | [01a339fb27](https://linux-hardware.org/?probe=01a339fb27) | Nov 11, 2022 |
| Lenovo        | ThinkPad T420 4238LY7       | [c5cf611a37](https://linux-hardware.org/?probe=c5cf611a37) | Nov 07, 2022 |
| Lenovo        | G50-45 80E3                 | [7818a033c6](https://linux-hardware.org/?probe=7818a033c6) | Nov 06, 2022 |
| HP            | Laptop 15s-eq1xxx           | [b59f9dcf48](https://linux-hardware.org/?probe=b59f9dcf48) | Nov 05, 2022 |
| Notebook      | NJx0MU                      | [e56aa65a39](https://linux-hardware.org/?probe=e56aa65a39) | Nov 05, 2022 |
| HP            | Laptop 15s-eq1xxx           | [8fdaec6b5a](https://linux-hardware.org/?probe=8fdaec6b5a) | Nov 04, 2022 |
| HP            | Laptop 15s-eq1xxx           | [4f5b04e8d9](https://linux-hardware.org/?probe=4f5b04e8d9) | Nov 03, 2022 |
| Notebook      | NJx0MU                      | [5c0b61dfb6](https://linux-hardware.org/?probe=5c0b61dfb6) | Nov 03, 2022 |
| HP            | 15 Notebook PC              | [d17e8e8e36](https://linux-hardware.org/?probe=d17e8e8e36) | Nov 03, 2022 |
| Notebook      | NJx0MU                      | [342c7609c9](https://linux-hardware.org/?probe=342c7609c9) | Nov 02, 2022 |
| Notebook      | NJx0MU                      | [5b45883fef](https://linux-hardware.org/?probe=5b45883fef) | Nov 02, 2022 |
| Notebook      | NJx0MU                      | [6b2b490208](https://linux-hardware.org/?probe=6b2b490208) | Nov 01, 2022 |
| Notebook      | NJx0MU                      | [1b626eed02](https://linux-hardware.org/?probe=1b626eed02) | Oct 31, 2022 |
| Notebook      | NJx0MU                      | [1b03bb8445](https://linux-hardware.org/?probe=1b03bb8445) | Oct 30, 2022 |
| Notebook      | NJx0MU                      | [f27aa95917](https://linux-hardware.org/?probe=f27aa95917) | Oct 29, 2022 |
| Dell          | Precision 7760              | [b8fce270db](https://linux-hardware.org/?probe=b8fce270db) | Oct 27, 2022 |
| Notebook      | NJx0MU                      | [2474ff9baf](https://linux-hardware.org/?probe=2474ff9baf) | Oct 27, 2022 |
| Toshiba       | Satellite C50D-A-133        | [c1ba737ccc](https://linux-hardware.org/?probe=c1ba737ccc) | Oct 25, 2022 |
| Apple         | MacBookAir6,1               | [4785b7f6f6](https://linux-hardware.org/?probe=4785b7f6f6) | Oct 25, 2022 |
| HP            | ENVY Sleekbook 6            | [a197375e26](https://linux-hardware.org/?probe=a197375e26) | Oct 19, 2022 |
| Acer          | Aspire 7750G                | [e0c71d09bb](https://linux-hardware.org/?probe=e0c71d09bb) | Oct 11, 2022 |
| Chuwi         | GemiBook Pro                | [02170aab85](https://linux-hardware.org/?probe=02170aab85) | Oct 09, 2022 |
| Chuwi         | GemiBook Pro                | [1a165faedb](https://linux-hardware.org/?probe=1a165faedb) | Oct 08, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [bc1f7e7d02](https://linux-hardware.org/?probe=bc1f7e7d02) | Oct 06, 2022 |
| Lenovo        | ThinkPad T460p 20FW002CP... | [b7cd76d0b6](https://linux-hardware.org/?probe=b7cd76d0b6) | Oct 05, 2022 |
| ASUSTek       | UX32VD                      | [0bea9d8673](https://linux-hardware.org/?probe=0bea9d8673) | Oct 05, 2022 |
| Lenovo        | ThinkPad X230 2325Y5L       | [7c5c62cc90](https://linux-hardware.org/?probe=7c5c62cc90) | Oct 03, 2022 |
| Dell          | Latitude 7300               | [d9acb6ec9c](https://linux-hardware.org/?probe=d9acb6ec9c) | Oct 03, 2022 |
| Sony          | VGN-SZ3XP_C                 | [6e9671dd1a](https://linux-hardware.org/?probe=6e9671dd1a) | Oct 02, 2022 |
| Acer          | Aspire 7750G                | [ccf9b69093](https://linux-hardware.org/?probe=ccf9b69093) | Oct 02, 2022 |
| Acer          | Aspire 7750G                | [7b89b5d0cf](https://linux-hardware.org/?probe=7b89b5d0cf) | Oct 02, 2022 |
| HP            | ZBook 14 G2                 | [ac14cbda52](https://linux-hardware.org/?probe=ac14cbda52) | Oct 02, 2022 |
| Intel         | H81U                        | [9e4458528b](https://linux-hardware.org/?probe=9e4458528b) | Sep 25, 2022 |
| Dell          | Precision 7760              | [f6600a1244](https://linux-hardware.org/?probe=f6600a1244) | Sep 22, 2022 |
| Intel         | Kabylake Platform           | [8b1c5eb5bf](https://linux-hardware.org/?probe=8b1c5eb5bf) | Sep 21, 2022 |
| Acer          | Aspire 5050                 | [1961d1c468](https://linux-hardware.org/?probe=1961d1c468) | Sep 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [64b8914cb2](https://linux-hardware.org/?probe=64b8914cb2) | Sep 12, 2022 |
| LG Electro... | 17Z990-R.AAS8U1             | [2df5aeabed](https://linux-hardware.org/?probe=2df5aeabed) | Sep 08, 2022 |
| Dell          | Precision 7760              | [e920197599](https://linux-hardware.org/?probe=e920197599) | Sep 05, 2022 |
| HP            | Pavilion 15                 | [194bb33f3d](https://linux-hardware.org/?probe=194bb33f3d) | Sep 04, 2022 |
| Dell          | Inspiron 7720               | [0749c352d0](https://linux-hardware.org/?probe=0749c352d0) | Sep 03, 2022 |
| HP            | Notebook                    | [573d359faf](https://linux-hardware.org/?probe=573d359faf) | Aug 31, 2022 |
| HP            | 15 Notebook PC              | [1109650747](https://linux-hardware.org/?probe=1109650747) | Aug 31, 2022 |
| LincPlus      | LINNCPLUS P1                | [516427e0e9](https://linux-hardware.org/?probe=516427e0e9) | Aug 23, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [5028378988](https://linux-hardware.org/?probe=5028378988) | Aug 23, 2022 |
| Notebook      | NJx0MU                      | [7a86bdf14e](https://linux-hardware.org/?probe=7a86bdf14e) | Aug 22, 2022 |
| Dell          | Latitude 7420               | [d599ef65fd](https://linux-hardware.org/?probe=d599ef65fd) | Aug 20, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [4efd818377](https://linux-hardware.org/?probe=4efd818377) | Aug 19, 2022 |
| HP            | EliteBook 745 G5            | [7e8d33a07f](https://linux-hardware.org/?probe=7e8d33a07f) | Aug 16, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [644fbe551a](https://linux-hardware.org/?probe=644fbe551a) | Aug 13, 2022 |
| Dell          | Latitude E7470              | [61d0b104e9](https://linux-hardware.org/?probe=61d0b104e9) | Aug 13, 2022 |
| HP            | 15 Notebook PC              | [46aa83aeb4](https://linux-hardware.org/?probe=46aa83aeb4) | Aug 07, 2022 |
| HONOR         | BOHK-WAX9X                  | [3d426cb1de](https://linux-hardware.org/?probe=3d426cb1de) | Aug 04, 2022 |
| Lenovo        | Legion R9000P2021H 82JQ     | [4f2ba69c49](https://linux-hardware.org/?probe=4f2ba69c49) | Jul 27, 2022 |
| Dell          | Latitude E4200              | [6cc0415a8a](https://linux-hardware.org/?probe=6cc0415a8a) | Jul 21, 2022 |
| Compaq        | Presario CQ-23              | [589a41e629](https://linux-hardware.org/?probe=589a41e629) | Jul 14, 2022 |
| MicroByte     | ezbook                      | [91b1fc169b](https://linux-hardware.org/?probe=91b1fc169b) | Jun 28, 2022 |
| Dell          | XPS 17 9710                 | [6e16eed17c](https://linux-hardware.org/?probe=6e16eed17c) | Jun 26, 2022 |
| ASUSTek       | S550CM                      | [c7262ada04](https://linux-hardware.org/?probe=c7262ada04) | Jun 25, 2022 |
| HUAWEI        | KLVD-WXX9                   | [a8c98b76b4](https://linux-hardware.org/?probe=a8c98b76b4) | Jun 24, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [10de805cb0](https://linux-hardware.org/?probe=10de805cb0) | Jun 24, 2022 |
| Google        | Kled                        | [5f47e6d3e3](https://linux-hardware.org/?probe=5f47e6d3e3) | Jun 16, 2022 |
| Google        | Kled                        | [6a566134c4](https://linux-hardware.org/?probe=6a566134c4) | Jun 16, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [f7abc9fae0](https://linux-hardware.org/?probe=f7abc9fae0) | Jun 14, 2022 |
| Lenovo        | V15 G2 ITL 82KB             | [e956f6b0b8](https://linux-hardware.org/?probe=e956f6b0b8) | Jun 09, 2022 |
| HP            | EliteBook 8560p             | [9bfdb902ce](https://linux-hardware.org/?probe=9bfdb902ce) | Jun 08, 2022 |
| Intel         | Kabylake Platform           | [074fd90c6a](https://linux-hardware.org/?probe=074fd90c6a) | Jun 06, 2022 |
| TrekStor      | Surfbook A13B               | [a42b3de31a](https://linux-hardware.org/?probe=a42b3de31a) | Jun 05, 2022 |
| Dell          | Precision M6500             | [1b68d2ca74](https://linux-hardware.org/?probe=1b68d2ca74) | Jun 01, 2022 |
| Apple         | MacBook5,1                  | [74e6dbe9af](https://linux-hardware.org/?probe=74e6dbe9af) | May 23, 2022 |
| Apple         | MacBook5,1                  | [a53d746d08](https://linux-hardware.org/?probe=a53d746d08) | May 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [5107890ffd](https://linux-hardware.org/?probe=5107890ffd) | May 15, 2022 |
| Sony          | VPCEA36FG                   | [0161a27629](https://linux-hardware.org/?probe=0161a27629) | May 13, 2022 |
| HONOR         | BOHK-WAX9X                  | [e6c4aaa3d8](https://linux-hardware.org/?probe=e6c4aaa3d8) | May 12, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [e99cdba363](https://linux-hardware.org/?probe=e99cdba363) | May 07, 2022 |
| HP            | EliteBook 840 G5            | [a53b09a7f3](https://linux-hardware.org/?probe=a53b09a7f3) | May 07, 2022 |
| HYPERPC       | PLAY                        | [408e86d04f](https://linux-hardware.org/?probe=408e86d04f) | May 06, 2022 |
| Apple         | MacBookPro6,2               | [ebaaf4a69b](https://linux-hardware.org/?probe=ebaaf4a69b) | May 01, 2022 |
| Apple         | MacBookPro9,1               | [35b3b3ae30](https://linux-hardware.org/?probe=35b3b3ae30) | Apr 26, 2022 |
| Apple         | MacBookPro9,1               | [faf447a067](https://linux-hardware.org/?probe=faf447a067) | Apr 24, 2022 |
| IPASON        | MaxBook P1                  | [d66d062f54](https://linux-hardware.org/?probe=d66d062f54) | Apr 05, 2022 |
| Lenovo        | ThinkPad SL500 27463ZG      | [b746a25ff1](https://linux-hardware.org/?probe=b746a25ff1) | Jan 28, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Notebooks | Percent |
|-----------------------|-----------|---------|
| 5.15.0-52-generic     | 7         | 10.29%  |
| 5.15.0-53-generic     | 6         | 8.82%   |
| 5.15.0-47-generic     | 6         | 8.82%   |
| 5.15.0-46-generic     | 6         | 8.82%   |
| 5.15.0-25-generic     | 6         | 8.82%   |
| 5.15.0-48-generic     | 5         | 7.35%   |
| 5.15.0-43-generic     | 5         | 7.35%   |
| 5.15.0-40-generic     | 4         | 5.88%   |
| 5.15.0-41-generic     | 3         | 4.41%   |
| 5.15.0-30-generic     | 3         | 4.41%   |
| 5.15.0-27-generic     | 3         | 4.41%   |
| 5.15.0-52-lowlatency  | 2         | 2.94%   |
| 6.0.8-x64v1-xanmod1   | 1         | 1.47%   |
| 5.18.0-051800-generic | 1         | 1.47%   |
| 5.17.1-051701-generic | 1         | 1.47%   |
| 5.17.0-1003-oem       | 1         | 1.47%   |
| 5.15.0-50-generic     | 1         | 1.47%   |
| 5.15.0-46-lowlatency  | 1         | 1.47%   |
| 5.15.0-39-generic     | 1         | 1.47%   |
| 5.15.0-37-generic     | 1         | 1.47%   |
| 5.15.0-35-generic     | 1         | 1.47%   |
| 5.15.0-33-generic     | 1         | 1.47%   |
| 5.15.0-18-generic     | 1         | 1.47%   |
| 5.14.0-1054-oem       | 1         | 1.47%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 58        | 92.06%  |
| 6.0.8   | 1         | 1.59%   |
| 5.18.0  | 1         | 1.59%   |
| 5.17.1  | 1         | 1.59%   |
| 5.17.0  | 1         | 1.59%   |
| 5.14.0  | 1         | 1.59%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 58        | 92.06%  |
| 5.17    | 2         | 3.17%   |
| 6.0     | 1         | 1.59%   |
| 5.18    | 1         | 1.59%   |
| 5.14    | 1         | 1.59%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 63        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| MATE | 63        | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 62        | 98.41%  |
| Wayland | 1         | 1.59%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 53        | 82.81%  |
| Unknown | 8         | 12.5%   |
| GDM3    | 3         | 4.69%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 26        | 41.27%  |
| de_DE | 8         | 12.7%   |
| fr_FR | 7         | 11.11%  |
| it_IT | 5         | 7.94%   |
| ru_RU | 4         | 6.35%   |
| pt_BR | 2         | 3.17%   |
| fi_FI | 2         | 3.17%   |
| es_ES | 2         | 3.17%   |
| en_GB | 2         | 3.17%   |
| zh_CN | 1         | 1.59%   |
| pl_PL | 1         | 1.59%   |
| en_AU | 1         | 1.59%   |
| de_CH | 1         | 1.59%   |
| C     | 1         | 1.59%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 38        | 56.72%  |
| BIOS | 29        | 43.28%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 54        | 85.71%  |
| Overlay | 4         | 6.35%   |
| Zfs     | 3         | 4.76%   |
| Jfs     | 1         | 1.59%   |
| Btrfs   | 1         | 1.59%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 46        | 70.77%  |
| Unknown | 15        | 23.08%  |
| MBR     | 4         | 6.15%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 53        | 84.13%  |
| Yes       | 10        | 15.87%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 40        | 62.5%   |
| Yes       | 24        | 37.5%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 12        | 19.05%  |
| Hewlett-Packard  | 12        | 19.05%  |
| Dell             | 7         | 11.11%  |
| ASUSTek Computer | 7         | 11.11%  |
| Apple            | 4         | 6.35%   |
| Acer             | 4         | 6.35%   |
| Toshiba          | 2         | 3.17%   |
| Intel            | 2         | 3.17%   |
| TrekStor         | 1         | 1.59%   |
| Sony             | 1         | 1.59%   |
| Notebook         | 1         | 1.59%   |
| MicroByte        | 1         | 1.59%   |
| LincPlus         | 1         | 1.59%   |
| LG Electronics   | 1         | 1.59%   |
| IPASON           | 1         | 1.59%   |
| HYPERPC          | 1         | 1.59%   |
| HUAWEI           | 1         | 1.59%   |
| HONOR            | 1         | 1.59%   |
| Google           | 1         | 1.59%   |
| Compaq           | 1         | 1.59%   |
| Chuwi            | 1         | 1.59%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| TrekStor Surfbook A13B               | 1         | 1.59%   |
| Toshiba Satellite P50-B-10Z          | 1         | 1.59%   |
| Toshiba Satellite C50D-A-133         | 1         | 1.59%   |
| Sony VPCEA36FG                       | 1         | 1.59%   |
| Notebook NJx0MU                      | 1         | 1.59%   |
| MicroByte ezbook                     | 1         | 1.59%   |
| LincPlus LINNCPLUS P1                | 1         | 1.59%   |
| LG 17Z990-R.AAS8U1                   | 1         | 1.59%   |
| Lenovo V15 G2 ITL 82KB               | 1         | 1.59%   |
| Lenovo ThinkPad X230 2325Y5L         | 1         | 1.59%   |
| Lenovo ThinkPad T460p 20FW002CPB     | 1         | 1.59%   |
| Lenovo ThinkPad T420 4238LY7         | 1         | 1.59%   |
| Lenovo ThinkPad SL500 27463ZG        | 1         | 1.59%   |
| Lenovo ThinkPad E15 Gen 2 20TDS0T500 | 1         | 1.59%   |
| Lenovo ThinkBook 16p Gen 2 20YM      | 1         | 1.59%   |
| Lenovo ThinkBook 14 G2 ITL 20VD      | 1         | 1.59%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY | 1         | 1.59%   |
| Lenovo IdeaPad 3 15IIL05 81WE        | 1         | 1.59%   |
| Lenovo IdeaPad 3 15ALC6 82KU         | 1         | 1.59%   |
| Lenovo IdeaPad 130-15AST 81H5        | 1         | 1.59%   |
| IPASON MaxBook P1                    | 1         | 1.59%   |
| Intel Kabylake Platform              | 1         | 1.59%   |
| Intel H81U                           | 1         | 1.59%   |
| HYPERPC PLAY                         | 1         | 1.59%   |
| HUAWEI KLVD-WXX9                     | 1         | 1.59%   |
| HONOR BOHK-WAX9X                     | 1         | 1.59%   |
| HP ZBook 14 G2                       | 1         | 1.59%   |
| HP ProBook 640 G8 Notebook PC        | 1         | 1.59%   |
| HP ProBook 450 G6                    | 1         | 1.59%   |
| HP Pavilion Laptop 15-eh1xxx         | 1         | 1.59%   |
| HP Pavilion 15                       | 1         | 1.59%   |
| HP Notebook                          | 1         | 1.59%   |
| HP Laptop 15s-eq1xxx                 | 1         | 1.59%   |
| HP ENVY Sleekbook 6                  | 1         | 1.59%   |
| HP EliteBook 8560p                   | 1         | 1.59%   |
| HP EliteBook 840 G5                  | 1         | 1.59%   |
| HP EliteBook 745 G5                  | 1         | 1.59%   |
| HP 15 Notebook PC                    | 1         | 1.59%   |
| Google Kled                          | 1         | 1.59%   |
| Dell XPS 17 9710                     | 1         | 1.59%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 5         | 7.94%   |
| Lenovo IdeaPad     | 4         | 6.35%   |
| HP EliteBook       | 3         | 4.76%   |
| Dell Latitude      | 3         | 4.76%   |
| Toshiba Satellite  | 2         | 3.17%   |
| Lenovo ThinkBook   | 2         | 3.17%   |
| HP ProBook         | 2         | 3.17%   |
| HP Pavilion        | 2         | 3.17%   |
| Dell Precision     | 2         | 3.17%   |
| ASUS VivoBook      | 2         | 3.17%   |
| Acer Aspire        | 2         | 3.17%   |
| TrekStor Surfbook  | 1         | 1.59%   |
| Sony VPCEA36FG     | 1         | 1.59%   |
| Notebook NJx0MU    | 1         | 1.59%   |
| MicroByte ezbook   | 1         | 1.59%   |
| LincPlus LINNCPLUS | 1         | 1.59%   |
| LG 17Z990-R.AAS8U1 | 1         | 1.59%   |
| Lenovo V15         | 1         | 1.59%   |
| IPASON MaxBook     | 1         | 1.59%   |
| Intel Kabylake     | 1         | 1.59%   |
| Intel H81U         | 1         | 1.59%   |
| HYPERPC PLAY       | 1         | 1.59%   |
| HUAWEI KLVD-WXX9   | 1         | 1.59%   |
| HONOR BOHK-WAX9X   | 1         | 1.59%   |
| HP ZBook           | 1         | 1.59%   |
| HP Notebook        | 1         | 1.59%   |
| HP Laptop          | 1         | 1.59%   |
| HP ENVY            | 1         | 1.59%   |
| HP 15              | 1         | 1.59%   |
| Google Kled        | 1         | 1.59%   |
| Dell XPS           | 1         | 1.59%   |
| Dell Inspiron      | 1         | 1.59%   |
| Compaq Presario    | 1         | 1.59%   |
| Chuwi GemiBook     | 1         | 1.59%   |
| ASUS X555LAB       | 1         | 1.59%   |
| ASUS UX32VD        | 1         | 1.59%   |
| ASUS S550CM        | 1         | 1.59%   |
| ASUS K93SV         | 1         | 1.59%   |
| ASUS ASUS          | 1         | 1.59%   |
| Apple MacBookPro9  | 1         | 1.59%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 18        | 28.57%  |
| 2020 | 7         | 11.11%  |
| 2012 | 6         | 9.52%   |
| 2018 | 5         | 7.94%   |
| 2019 | 4         | 6.35%   |
| 2014 | 3         | 4.76%   |
| 2011 | 3         | 4.76%   |
| 2010 | 3         | 4.76%   |
| 2022 | 2         | 3.17%   |
| 2016 | 2         | 3.17%   |
| 2015 | 2         | 3.17%   |
| 2013 | 2         | 3.17%   |
| 2009 | 2         | 3.17%   |
| 2017 | 1         | 1.59%   |
| 2008 | 1         | 1.59%   |
| 2007 | 1         | 1.59%   |
| 2006 | 1         | 1.59%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 63        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 59        | 89.39%  |
| Enabled  | 7         | 10.61%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 62        | 98.41%  |
| Yes  | 1         | 1.59%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 21        | 33.33%  |
| 3.01-4.0    | 12        | 19.05%  |
| 16.01-24.0  | 12        | 19.05%  |
| 8.01-16.0   | 12        | 19.05%  |
| 32.01-64.0  | 4         | 6.35%   |
| 64.01-256.0 | 2         | 3.17%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 22        | 32.84%  |
| 1.01-2.0  | 16        | 23.88%  |
| 4.01-8.0  | 12        | 17.91%  |
| 3.01-4.0  | 12        | 17.91%  |
| 8.01-16.0 | 4         | 5.97%   |
| 0.51-1.0  | 1         | 1.49%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 49        | 77.78%  |
| 2      | 11        | 17.46%  |
| 3      | 3         | 4.76%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 44        | 69.84%  |
| Yes       | 19        | 30.16%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 46        | 73.02%  |
| No        | 17        | 26.98%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 63        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 56        | 87.5%   |
| No        | 8         | 12.5%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Germany     | 8         | 12.7%   |
| Italy       | 7         | 11.11%  |
| USA         | 6         | 9.52%   |
| France      | 6         | 9.52%   |
| Spain       | 5         | 7.94%   |
| Russia      | 4         | 6.35%   |
| Brazil      | 4         | 6.35%   |
| UK          | 3         | 4.76%   |
| Turkey      | 2         | 3.17%   |
| Serbia      | 2         | 3.17%   |
| Finland     | 2         | 3.17%   |
| Estonia     | 2         | 3.17%   |
| Switzerland | 1         | 1.59%   |
| Romania     | 1         | 1.59%   |
| Poland      | 1         | 1.59%   |
| Paraguay    | 1         | 1.59%   |
| Netherlands | 1         | 1.59%   |
| India       | 1         | 1.59%   |
| Hungary     | 1         | 1.59%   |
| Greece      | 1         | 1.59%   |
| Georgia     | 1         | 1.59%   |
| Colombia    | 1         | 1.59%   |
| China       | 1         | 1.59%   |
| Bulgaria    | 1         | 1.59%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Mannheim          | 2         | 3.13%   |
| Belgrade          | 2         | 3.13%   |
| Xining            | 1         | 1.56%   |
| Warsaw            | 1         | 1.56%   |
| Villeurbanne      | 1         | 1.56%   |
| Varna             | 1         | 1.56%   |
| Valenciennes      | 1         | 1.56%   |
| Turku             | 1         | 1.56%   |
| Tula              | 1         | 1.56%   |
| Thane             | 1         | 1.56%   |
| Tartu             | 1         | 1.56%   |
| Seville           | 1         | 1.56%   |
| Settimo Torinese  | 1         | 1.56%   |
| Sarospatak        | 1         | 1.56%   |
| Sao Paulo         | 1         | 1.56%   |
| Rostov-on-Don     | 1         | 1.56%   |
| Rennes            | 1         | 1.56%   |
| Porto Alegre      | 1         | 1.56%   |
| Pärnu            | 1         | 1.56%   |
| Paris             | 1         | 1.56%   |
| Ortuella          | 1         | 1.56%   |
| Norwich           | 1         | 1.56%   |
| North Wilkesboro  | 1         | 1.56%   |
| Newport News      | 1         | 1.56%   |
| Naaldwijk         | 1         | 1.56%   |
| Moscow            | 1         | 1.56%   |
| Moosseedorf       | 1         | 1.56%   |
| Milan             | 1         | 1.56%   |
| Memphis           | 1         | 1.56%   |
| Medellín         | 1         | 1.56%   |
| Marseille         | 1         | 1.56%   |
| Magdeburg         | 1         | 1.56%   |
| Limbiate          | 1         | 1.56%   |
| Laubach           | 1         | 1.56%   |
| La Rochelle       | 1         | 1.56%   |
| la Nucia          | 1         | 1.56%   |
| K'alak'i T'bilisi | 1         | 1.56%   |
| Jundiaí          | 1         | 1.56%   |
| Izmir             | 1         | 1.56%   |
| Iesi              | 1         | 1.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 16        | 22     | 20.51%  |
| Toshiba             | 7         | 9      | 8.97%   |
| Crucial             | 7         | 7      | 8.97%   |
| SanDisk             | 6         | 8      | 7.69%   |
| Unknown             | 3         | 3      | 3.85%   |
| Seagate             | 3         | 3      | 3.85%   |
| Kingston            | 3         | 3      | 3.85%   |
| WDC                 | 2         | 2      | 2.56%   |
| SK hynix            | 2         | 2      | 2.56%   |
| Phison              | 2         | 2      | 2.56%   |
| Micron Technology   | 2         | 2      | 2.56%   |
| KingSpec            | 2         | 2      | 2.56%   |
| Intel               | 2         | 2      | 2.56%   |
| HGST                | 2         | 2      | 2.56%   |
| China               | 2         | 2      | 2.56%   |
| A-DATA Technology   | 2         | 2      | 2.56%   |
| UMIS                | 1         | 1      | 1.28%   |
| SPCC                | 1         | 1      | 1.28%   |
| Netac               | 1         | 1      | 1.28%   |
| LITEONIT            | 1         | 1      | 1.28%   |
| Lenovo              | 1         | 1      | 1.28%   |
| Kston               | 1         | 1      | 1.28%   |
| KIOXIA              | 1         | 1      | 1.28%   |
| JMicron Technology  | 1         | 1      | 1.28%   |
| Intenso             | 1         | 1      | 1.28%   |
| Hjwdz               | 1         | 1      | 1.28%   |
| Hitachi             | 1         | 1      | 1.28%   |
| Gigabyte Technology | 1         | 1      | 1.28%   |
| faspeed             | 1         | 1      | 1.28%   |
| Apple               | 1         | 1      | 1.28%   |
| ADATA Technology    | 1         | 1      | 1.28%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB                             | 2         | 2.47%   |
| Samsung MZVLQ512HBLU-00BH1 512GB                     | 2         | 2.47%   |
| Crucial CT240BX500SSD1 240GB                         | 2         | 2.47%   |
| Crucial CT1000BX500SSD1 1TB                          | 2         | 2.47%   |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB                   | 1         | 1.23%   |
| WDC PC SN520 SDAPNUW-512G-1014 512GB                 | 1         | 1.23%   |
| Unknown SLD64G  64GB                                 | 1         | 1.23%   |
| Unknown MMC Card  7GB                                | 1         | 1.23%   |
| Unknown Biwin  64GB                                  | 1         | 1.23%   |
| UMIS RPJTJ256MEE1OWX 256GB                           | 1         | 1.23%   |
| Toshiba THNSNK256GVN8 256GB SSD                      | 1         | 1.23%   |
| Toshiba MQ04ABF100 1TB                               | 1         | 1.23%   |
| Toshiba MK3259GSXP 320GB                             | 1         | 1.23%   |
| Toshiba KBG40ZNT256G MEMORY 256GB                    | 1         | 1.23%   |
| Toshiba KBG30ZMV256G 256GB                           | 1         | 1.23%   |
| SPCC Solid State Disk 1024GB                         | 1         | 1.23%   |
| SK hynix SC311 SATA 256GB SSD                        | 1         | 1.23%   |
| SK hynix HFM128GDJTNG-8310A 128GB                    | 1         | 1.23%   |
| Seagate ST9500420AS 500GB                            | 1         | 1.23%   |
| Seagate ST2000LM015-2E8174 2TB                       | 1         | 1.23%   |
| Seagate ST1000LM035-1RK172 1TB                       | 1         | 1.23%   |
| SanDisk SSD U100 24GB                                | 1         | 1.23%   |
| SanDisk SSD i100 24GB                                | 1         | 1.23%   |
| SanDisk SD7TB3Q-256G-1006 256GB SSD                  | 1         | 1.23%   |
| SanDisk SD6SB1M-128G-1006 128GB SSD                  | 1         | 1.23%   |
| SanDisk SD6PP4M-256G-1006 256GB SSD                  | 1         | 1.23%   |
| SanDisk NVMe SSD Drive 512GB                         | 1         | 1.23%   |
| SanDisk Extreme 55AE 500GB SSD                       | 1         | 1.23%   |
| Samsung SSD PM830 mSATA 32GB                         | 1         | 1.23%   |
| Samsung SSD PM800 TM 128GB                           | 1         | 1.23%   |
| Samsung SSD 980 PRO 1TB                              | 1         | 1.23%   |
| Samsung SSD 860 EVO 250GB                            | 1         | 1.23%   |
| Samsung SSD 850 EVO 250GB                            | 1         | 1.23%   |
| Samsung SSD 830 Series 512GB                         | 1         | 1.23%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB               | 1         | 1.23%   |
| Samsung PM9A1 NVMe 512GB                             | 1         | 1.23%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 250GB | 1         | 1.23%   |
| Samsung MZVLQ256HBJD-00BH1 256GB                     | 1         | 1.23%   |
| Samsung MZVL2512HCJQ-00B00 512GB                     | 1         | 1.23%   |
| Samsung MZNLN512HAJQ-00000 512GB SSD                 | 1         | 1.23%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 4         | 5      | 40%     |
| Seagate | 3         | 3      | 30%     |
| HGST    | 2         | 2      | 20%     |
| Hitachi | 1         | 1      | 10%     |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 7         | 7      | 18.92%  |
| Samsung Electronics | 6         | 7      | 16.22%  |
| SanDisk             | 5         | 6      | 13.51%  |
| Kingston            | 2         | 2      | 5.41%   |
| KingSpec            | 2         | 2      | 5.41%   |
| China               | 2         | 2      | 5.41%   |
| A-DATA Technology   | 2         | 2      | 5.41%   |
| Toshiba             | 1         | 2      | 2.7%    |
| SPCC                | 1         | 1      | 2.7%    |
| SK hynix            | 1         | 1      | 2.7%    |
| Netac               | 1         | 1      | 2.7%    |
| Micron Technology   | 1         | 1      | 2.7%    |
| LITEONIT            | 1         | 1      | 2.7%    |
| Kston               | 1         | 1      | 2.7%    |
| JMicron Technology  | 1         | 1      | 2.7%    |
| Intenso             | 1         | 1      | 2.7%    |
| Intel               | 1         | 1      | 2.7%    |
| Apple               | 1         | 1      | 2.7%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 29        | 40     | 42.03%  |
| NVMe    | 26        | 32     | 37.68%  |
| HDD     | 9         | 11     | 13.04%  |
| MMC     | 3         | 3      | 4.35%   |
| Unknown | 2         | 2      | 2.9%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 37        | 50     | 53.62%  |
| NVMe | 26        | 32     | 37.68%  |
| SAS  | 3         | 3      | 4.35%   |
| MMC  | 3         | 3      | 4.35%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 28        | 36     | 66.67%  |
| 0.51-1.0   | 12        | 12     | 28.57%  |
| 1.01-2.0   | 2         | 3      | 4.76%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 22        | 34.38%  |
| 251-500        | 16        | 25%     |
| 1001-2000      | 6         | 9.38%   |
| 1-20           | 6         | 9.38%   |
| 501-1000       | 4         | 6.25%   |
| 21-50          | 3         | 4.69%   |
| 51-100         | 3         | 4.69%   |
| 2001-3000      | 2         | 3.13%   |
| More than 3000 | 1         | 1.56%   |
| Unknown        | 1         | 1.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 18        | 27.69%  |
| 21-50     | 12        | 18.46%  |
| 101-250   | 12        | 18.46%  |
| 51-100    | 10        | 15.38%  |
| 1001-2000 | 4         | 6.15%   |
| 501-1000  | 4         | 6.15%   |
| 251-500   | 3         | 4.62%   |
| 2001-3000 | 1         | 1.54%   |
| Unknown   | 1         | 1.54%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Seagate ST9500420AS 500GB                    | 1         | 1      | 25%     |
| Samsung Electronics MZVLQ512HBLU-00BH1 512GB | 1         | 1      | 25%     |
| Netac SSD 256GB                              | 1         | 1      | 25%     |
| Intel SSDSC2KW512G8 512GB                    | 1         | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1         | 1      | 25%     |
| Samsung Electronics | 1         | 1      | 25%     |
| Netac               | 1         | 1      | 25%     |
| Intel               | 1         | 1      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 2         | 2      | 50%     |
| NVMe | 1         | 1      | 25%     |
| HDD  | 1         | 1      | 25%     |

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
| Works    | 41        | 51     | 58.57%  |
| Detected | 25        | 33     | 35.71%  |
| Malfunc  | 4         | 4      | 5.71%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 41        | 51.9%   |
| Samsung Electronics          | 10        | 12.66%  |
| AMD                          | 10        | 12.66%  |
| SanDisk                      | 3         | 3.8%    |
| Phison Electronics           | 3         | 3.8%    |
| Toshiba America Info Systems | 2         | 2.53%   |
| KIOXIA                       | 2         | 2.53%   |
| Union Memory (Shenzhen)      | 1         | 1.27%   |
| SK hynix                     | 1         | 1.27%   |
| Nvidia                       | 1         | 1.27%   |
| Micron Technology            | 1         | 1.27%   |
| Marvell Technology Group     | 1         | 1.27%   |
| Lenovo                       | 1         | 1.27%   |
| Kingston Technology Company  | 1         | 1.27%   |
| ADATA Technology             | 1         | 1.27%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 9         | 10.47%  |
| Samsung NVMe SSD Controller 980                                                        | 7         | 8.14%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 6         | 6.98%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 5         | 5.81%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 4         | 4.65%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 3         | 3.49%   |
| Intel Tiger Lake-LP SATA Controller                                                    | 3         | 3.49%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 2         | 2.33%   |
| Phison E16 PCIe4 NVMe Controller                                                       | 2         | 2.33%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 2         | 2.33%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 2         | 2.33%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 2         | 2.33%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 2         | 2.33%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 2         | 2.33%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 2         | 2.33%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 2         | 2.33%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 2         | 2.33%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                                 | 1         | 1.16%   |
| Toshiba America Info Systems Toshiba America Info SATA controller                      | 1         | 1.16%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                   | 1         | 1.16%   |
| SK hynix BC501 NVMe Solid State Drive                                                  | 1         | 1.16%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                              | 1         | 1.16%   |
| Phison PS5013 E13 NVMe Controller                                                      | 1         | 1.16%   |
| Nvidia MCP79 AHCI Controller                                                           | 1         | 1.16%   |
| Micron Non-Volatile memory controller                                                  | 1         | 1.16%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                             | 1         | 1.16%   |
| Lenovo Non-Volatile memory controller                                                  | 1         | 1.16%   |
| KIOXIA NVMe SSD Controller BG4                                                         | 1         | 1.16%   |
| KIOXIA Non-Volatile memory controller                                                  | 1         | 1.16%   |
| Kingston Company Company Non-Volatile memory controller                                | 1         | 1.16%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 1         | 1.16%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 1         | 1.16%   |
| Intel SSD 660P Series                                                                  | 1         | 1.16%   |
| Intel Jasper Lake SATA AHCI Controller                                                 | 1         | 1.16%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 1         | 1.16%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 1         | 1.16%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 1         | 1.16%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 1         | 1.16%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 1         | 1.16%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 1         | 1.16%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 43        | 52.44%  |
| NVMe | 26        | 31.71%  |
| RAID | 9         | 10.98%  |
| IDE  | 4         | 4.88%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 49        | 77.78%  |
| AMD    | 14        | 22.22%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Intel Core i7-3517U CPU @ 1.90GHz        | 3         | 4.76%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz  | 3         | 4.76%   |
| Intel Core i7-8565U CPU @ 1.80GHz        | 2         | 3.17%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz  | 2         | 3.17%   |
| AMD Ryzen 5 4600H with Radeon Graphics   | 2         | 3.17%   |
| Intel Pentium Silver N6000 @ 1.10GHz     | 1         | 1.59%   |
| Intel Pentium CPU N4200 @ 1.10GHz        | 1         | 1.59%   |
| Intel Pentium CPU N3540 @ 2.16GHz        | 1         | 1.59%   |
| Intel Core i7-7500U CPU @ 2.70GHz        | 1         | 1.59%   |
| Intel Core i7-5500U CPU @ 2.40GHz        | 1         | 1.59%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz       | 1         | 1.59%   |
| Intel Core i7-3720QM CPU @ 2.60GHz       | 1         | 1.59%   |
| Intel Core i7-3630QM CPU @ 2.40GHz       | 1         | 1.59%   |
| Intel Core i7-2670QM CPU @ 2.20GHz       | 1         | 1.59%   |
| Intel Core i7-10510U CPU @ 1.80GHz       | 1         | 1.59%   |
| Intel Core i7 CPU X 920 @ 2.00GHz        | 1         | 1.59%   |
| Intel Core i5-8250U CPU @ 1.60GHz        | 1         | 1.59%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz       | 1         | 1.59%   |
| Intel Core i5-4300Y CPU @ 1.60GHz        | 1         | 1.59%   |
| Intel Core i5-4250U CPU @ 1.30GHz        | 1         | 1.59%   |
| Intel Core i5-3380M CPU @ 2.90GHz        | 1         | 1.59%   |
| Intel Core i5-2540M CPU @ 2.60GHz        | 1         | 1.59%   |
| Intel Core i5-2520M CPU @ 2.50GHz        | 1         | 1.59%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz       | 1         | 1.59%   |
| Intel Core i5 CPU M 560 @ 2.67GHz        | 1         | 1.59%   |
| Intel Core i5 CPU M 520 @ 2.40GHz        | 1         | 1.59%   |
| Intel Core i3-4005U CPU @ 1.70GHz        | 1         | 1.59%   |
| Intel Core i3-3110M CPU @ 2.40GHz        | 1         | 1.59%   |
| Intel Core i3-10110U CPU @ 2.10GHz       | 1         | 1.59%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz       | 1         | 1.59%   |
| Intel Core 2 Duo CPU U9600 @ 1.60GHz     | 1         | 1.59%   |
| Intel Core 2 Duo CPU T9550 @ 2.66GHz     | 1         | 1.59%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz     | 1         | 1.59%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz     | 1         | 1.59%   |
| Intel Celeron N5100 @ 1.10GHz            | 1         | 1.59%   |
| Intel Celeron N4020 CPU @ 1.10GHz        | 1         | 1.59%   |
| Intel Celeron J4125 CPU @ 2.00GHz        | 1         | 1.59%   |
| Intel Celeron CPU N3450 @ 1.10GHz        | 1         | 1.59%   |
| Intel Celeron CPU N2830 @ 2.16GHz        | 1         | 1.59%   |
| Intel 11th Gen Core i9-11980HK @ 2.60GHz | 1         | 1.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i7        | 13        | 20.63%  |
| Other                | 10        | 15.87%  |
| Intel Core i5        | 10        | 15.87%  |
| Intel Celeron        | 5         | 7.94%   |
| Intel Core i3        | 4         | 6.35%   |
| Intel Core 2 Duo     | 4         | 6.35%   |
| AMD Ryzen 5          | 3         | 4.76%   |
| Intel Pentium        | 2         | 3.17%   |
| AMD Ryzen 7          | 2         | 3.17%   |
| AMD Ryzen 3          | 2         | 3.17%   |
| Intel Pentium Silver | 1         | 1.59%   |
| AMD Turion 64 Mobile | 1         | 1.59%   |
| AMD Ryzen 9          | 1         | 1.59%   |
| AMD Ryzen 7 PRO      | 1         | 1.59%   |
| AMD E1               | 1         | 1.59%   |
| AMD A8               | 1         | 1.59%   |
| AMD A6               | 1         | 1.59%   |
| AMD A4               | 1         | 1.59%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 28        | 44.44%  |
| 2      | 26        | 41.27%  |
| 8      | 5         | 7.94%   |
| 6      | 3         | 4.76%   |
| 1      | 1         | 1.59%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 63        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 44        | 69.84%  |
| 1      | 19        | 30.16%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 63        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 25        | 36.76%  |
| 0x806c1    | 6         | 8.82%   |
| 0x306a9    | 4         | 5.88%   |
| 0x806d1    | 3         | 4.41%   |
| 0x806ec    | 2         | 2.94%   |
| 0x706e5    | 2         | 2.94%   |
| 0x706a8    | 2         | 2.94%   |
| 0x506c9    | 2         | 2.94%   |
| 0x40651    | 2         | 2.94%   |
| 0x206a7    | 2         | 2.94%   |
| 0x1067a    | 2         | 2.94%   |
| 0x08608103 | 2         | 2.94%   |
| 0x906c0    | 1         | 1.47%   |
| 0x806eb    | 1         | 1.47%   |
| 0x806ea    | 1         | 1.47%   |
| 0x806e9    | 1         | 1.47%   |
| 0x6fb      | 1         | 1.47%   |
| 0x506e3    | 1         | 1.47%   |
| 0x30678    | 1         | 1.47%   |
| 0x20655    | 1         | 1.47%   |
| 0x0a50000c | 1         | 1.47%   |
| 0x08608102 | 1         | 1.47%   |
| 0x08108109 | 1         | 1.47%   |
| 0x08101016 | 1         | 1.47%   |
| 0x07030105 | 1         | 1.47%   |
| 0x0700010f | 1         | 1.47%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| TigerLake     | 7         | 10.94%  |
| IvyBridge     | 7         | 10.94%  |
| KabyLake      | 6         | 9.38%   |
| Unknown       | 6         | 9.38%   |
| Icelake       | 5         | 7.81%   |
| Haswell       | 4         | 6.25%   |
| Zen 2         | 3         | 4.69%   |
| SandyBridge   | 3         | 4.69%   |
| Penryn        | 3         | 4.69%   |
| Westmere      | 2         | 3.13%   |
| Silvermont    | 2         | 3.13%   |
| Goldmont plus | 2         | 3.13%   |
| Goldmont      | 2         | 3.13%   |
| Excavator     | 2         | 3.13%   |
| Zen+          | 1         | 1.56%   |
| Zen 3         | 1         | 1.56%   |
| Zen           | 1         | 1.56%   |
| Skylake       | 1         | 1.56%   |
| Puma          | 1         | 1.56%   |
| Nehalem       | 1         | 1.56%   |
| K8 Hammer     | 1         | 1.56%   |
| Jaguar        | 1         | 1.56%   |
| Core          | 1         | 1.56%   |
| Broadwell     | 1         | 1.56%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 44        | 57.14%  |
| AMD    | 18        | 23.38%  |
| Nvidia | 15        | 19.48%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 6         | 7.69%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 6         | 7.69%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 3         | 3.85%   |
| AMD Renoir                                                                | 3         | 3.85%   |
| AMD Lucienne                                                              | 3         | 3.85%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 2         | 2.56%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 2         | 2.56%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 2         | 2.56%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 2         | 2.56%   |
| Intel JasperLake [UHD Graphics]                                           | 2         | 2.56%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 2         | 2.56%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 2         | 2.56%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 2         | 2.56%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 2         | 2.56%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 2         | 2.56%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                  | 2         | 2.56%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 1         | 1.28%   |
| Nvidia TU117M                                                             | 1         | 1.28%   |
| Nvidia GT216M [GeForce GT 330M]                                           | 1         | 1.28%   |
| Nvidia GM108M [GeForce MX130]                                             | 1         | 1.28%   |
| Nvidia GK107M [GeForce GT 650M]                                           | 1         | 1.28%   |
| Nvidia GK107M [GeForce GT 650M Mac Edition]                               | 1         | 1.28%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]      | 1         | 1.28%   |
| Nvidia GF108M [GeForce GT 635M]                                           | 1         | 1.28%   |
| Nvidia GF108M [GeForce GT 540M]                                           | 1         | 1.28%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                  | 1         | 1.28%   |
| Nvidia GA104GLM [RTX A3000 Mobile]                                        | 1         | 1.28%   |
| Nvidia G92GLM [Quadro FX 2800M]                                           | 1         | 1.28%   |
| Nvidia C79 [GeForce 9400M]                                                | 1         | 1.28%   |
| Intel UHD Graphics 620                                                    | 1         | 1.28%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                 | 1         | 1.28%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 1         | 1.28%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 1         | 1.28%   |
| Intel HD Graphics 620                                                     | 1         | 1.28%   |
| Intel HD Graphics 5500                                                    | 1         | 1.28%   |
| Intel HD Graphics 530                                                     | 1         | 1.28%   |
| Intel HD Graphics 500                                                     | 1         | 1.28%   |
| Intel Haswell-ULT High Definition Audio Controller [HD Graphics]          | 1         | 1.28%   |
| Intel Core Processor Integrated Graphics Controller                       | 1         | 1.28%   |
| Intel Apollo Lake [HD Graphics 505]                                       | 1         | 1.28%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 33        | 52.38%  |
| 1 x AMD        | 12        | 19.05%  |
| Intel + Nvidia | 8         | 12.7%   |
| 1 x Nvidia     | 4         | 6.35%   |
| Intel + AMD    | 3         | 4.76%   |
| AMD + Nvidia   | 3         | 4.76%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 55        | 87.3%   |
| Proprietary | 7         | 11.11%  |
| Unknown     | 1         | 1.59%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 50        | 78.13%  |
| 0.01-0.5   | 6         | 9.38%   |
| 0.51-1.0   | 4         | 6.25%   |
| 1.01-2.0   | 3         | 4.69%   |
| 5.01-6.0   | 1         | 1.56%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 12        | 16.67%  |
| Chimei Innolux          | 11        | 15.28%  |
| LG Display              | 9         | 12.5%   |
| Samsung Electronics     | 8         | 11.11%  |
| AU Optronics            | 7         | 9.72%   |
| Apple                   | 4         | 5.56%   |
| Chi Mei Optoelectronics | 3         | 4.17%   |
| PANDA                   | 2         | 2.78%   |
| AOC                     | 2         | 2.78%   |
| ViewSonic               | 1         | 1.39%   |
| Unknown                 | 1         | 1.39%   |
| Toshiba                 | 1         | 1.39%   |
| Sony                    | 1         | 1.39%   |
| Sharp                   | 1         | 1.39%   |
| Sceptre Tech            | 1         | 1.39%   |
| Philips                 | 1         | 1.39%   |
| Lenovo                  | 1         | 1.39%   |
| Iiyama                  | 1         | 1.39%   |
| Hitachi                 | 1         | 1.39%   |
| HannStar                | 1         | 1.39%   |
| Dell                    | 1         | 1.39%   |
| CS_                     | 1         | 1.39%   |
| BenQ                    | 1         | 1.39%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                 | 2         | 2.78%   |
| Apple LCD Monitor APP9CA3 1440x900 330x210mm 15.4-inch                | 2         | 2.78%   |
| ViewSonic VP2765 SERIES VSC9F28 1920x1080 598x336mm 27.0-inch         | 1         | 1.39%   |
| Unknown SMART TV 0563 1920x1080 1209x680mm 54.6-inch                  | 1         | 1.39%   |
| Toshiba LCD Monitor LCD2109 1280x800 261x163mm 12.1-inch              | 1         | 1.39%   |
| Sony LCD Monitor SNY05FA 1366x768 340x190mm 15.3-inch                 | 1         | 1.39%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch               | 1         | 1.39%   |
| Sceptre Tech Sceptre E24 SPT099D 1920x1080 521x293mm 23.5-inch        | 1         | 1.39%   |
| Samsung Electronics SMT27A300 SAM087A 1920x1080 598x336mm 27.0-inch   | 1         | 1.39%   |
| Samsung Electronics SMB2220N SAM06A2 1920x1080 480x270mm 21.7-inch    | 1         | 1.39%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch     | 1         | 1.39%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 367x230mm 17.1-inch  | 1         | 1.39%   |
| Samsung Electronics LCD Monitor SEC5044 1920x1080 382x215mm 17.3-inch | 1         | 1.39%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 344x194mm 15.5-inch  | 1         | 1.39%   |
| Samsung Electronics LCD Monitor SEC3157 1280x800 303x190mm 14.1-inch  | 1         | 1.39%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch  | 1         | 1.39%   |
| Philips 247EL PHLC084 1920x1080 521x293mm 23.5-inch                   | 1         | 1.39%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch               | 1         | 1.39%   |
| PANDA LC133LF2L03 NCP0015 1920x1080 294x165mm 13.3-inch               | 1         | 1.39%   |
| LG Display LCD Monitor LGD40A0 1366x768 310x174mm 14.0-inch           | 1         | 1.39%   |
| LG Display LCD Monitor LGD0724 1920x1080 309x174mm 14.0-inch          | 1         | 1.39%   |
| LG Display LCD Monitor LGD069A 1920x1080 344x194mm 15.5-inch          | 1         | 1.39%   |
| LG Display LCD Monitor LGD05F8 2560x1600 366x229mm 17.0-inch          | 1         | 1.39%   |
| LG Display LCD Monitor LGD05F1 1920x1080 309x174mm 14.0-inch          | 1         | 1.39%   |
| LG Display LCD Monitor LGD0493 1366x768 344x194mm 15.5-inch           | 1         | 1.39%   |
| LG Display LCD Monitor LGD045C 1366x768 344x194mm 15.5-inch           | 1         | 1.39%   |
| LG Display LCD Monitor LGD03A3 1366x768 277x156mm 12.5-inch           | 1         | 1.39%   |
| LG Display LCD Monitor LGD034D 1366x768 344x194mm 15.5-inch           | 1         | 1.39%   |
| Lenovo LCD Monitor LEN4050 1280x800 331x207mm 15.4-inch               | 1         | 1.39%   |
| Iiyama PL2773H IVM660A 1920x1080 600x340mm 27.2-inch                  | 1         | 1.39%   |
| Hitachi HISENSE HEC0030 3840x2160 1872x1053mm 84.6-inch               | 1         | 1.39%   |
| HannStar Hanns.G Hi221 HSD2469 1680x1050 474x297mm 22.0-inch          | 1         | 1.39%   |
| Dell S2421HGF DELA16C 1920x1080 527x296mm 23.8-inch                   | 1         | 1.39%   |
| CS_ LCD Monitor CS_5211 1366x768 518x333mm 24.2-inch                  | 1         | 1.39%   |
| Chimei Innolux LCD Monitor CMN174A 1920x1080 381x214mm 17.2-inch      | 1         | 1.39%   |
| Chimei Innolux LCD Monitor CMN1745 1600x900 382x214mm 17.2-inch       | 1         | 1.39%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 1         | 1.39%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch       | 1         | 1.39%   |
| Chimei Innolux LCD Monitor CMN15B6 1366x768 344x193mm 15.5-inch       | 1         | 1.39%   |
| Chimei Innolux LCD Monitor CMN1526 1920x1080 344x193mm 15.5-inch      | 1         | 1.39%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 34        | 50%     |
| 1366x768 (WXGA)    | 15        | 22.06%  |
| 1440x900 (WXGA+)   | 4         | 5.88%   |
| 1280x800 (WXGA)    | 4         | 5.88%   |
| 3840x2160 (4K)     | 2         | 2.94%   |
| 2560x1600          | 2         | 2.94%   |
| 2560x1440 (QHD)    | 2         | 2.94%   |
| 2160x1440          | 2         | 2.94%   |
| 3840x2400          | 1         | 1.47%   |
| 1680x1050 (WSXGA+) | 1         | 1.47%   |
| 1600x900 (HD+)     | 1         | 1.47%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 26        | 36.11%  |
| 14     | 10        | 13.89%  |
| 17     | 8         | 11.11%  |
| 13     | 8         | 11.11%  |
| 27     | 4         | 5.56%   |
| 24     | 3         | 4.17%   |
| 23     | 2         | 2.78%   |
| 21     | 2         | 2.78%   |
| 12     | 2         | 2.78%   |
| 84     | 1         | 1.39%   |
| 54     | 1         | 1.39%   |
| 25     | 1         | 1.39%   |
| 22     | 1         | 1.39%   |
| 18     | 1         | 1.39%   |
| 16     | 1         | 1.39%   |
| 11     | 1         | 1.39%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 40        | 55.56%  |
| 501-600     | 10        | 13.89%  |
| 351-400     | 8         | 11.11%  |
| 201-300     | 8         | 11.11%  |
| 401-500     | 4         | 5.56%   |
| 1501-2000   | 1         | 1.39%   |
| 1001-1500   | 1         | 1.39%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 49        | 76.56%  |
| 16/10 | 13        | 20.31%  |
| 3/2   | 2         | 3.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 25        | 35.21%  |
| 81-90          | 15        | 21.13%  |
| 121-130        | 7         | 9.86%   |
| 201-250        | 6         | 8.45%   |
| 301-350        | 4         | 5.63%   |
| 71-80          | 3         | 4.23%   |
| More than 1000 | 2         | 2.82%   |
| 61-70          | 2         | 2.82%   |
| 251-300        | 2         | 2.82%   |
| 51-60          | 1         | 1.41%   |
| 141-150        | 1         | 1.41%   |
| 131-140        | 1         | 1.41%   |
| 111-120        | 1         | 1.41%   |
| 91-100         | 1         | 1.41%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 27        | 38.57%  |
| 101-120       | 21        | 30%     |
| 51-100        | 13        | 18.57%  |
| 161-240       | 7         | 10%     |
| More than 240 | 1         | 1.43%   |
| 1-50          | 1         | 1.43%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 51        | 80.95%  |
| 2     | 10        | 15.87%  |
| 3     | 1         | 1.59%   |
| 0     | 1         | 1.59%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 39        | 42.39%  |
| Realtek Semiconductor             | 32        | 34.78%  |
| Qualcomm Atheros                  | 5         | 5.43%   |
| Broadcom                          | 4         | 4.35%   |
| Ericsson Business Mobile Networks | 2         | 2.17%   |
| Broadcom Limited                  | 2         | 2.17%   |
| ASIX Electronics                  | 2         | 2.17%   |
| TP-Link                           | 1         | 1.09%   |
| Quectel Wireless Solutions        | 1         | 1.09%   |
| Qualcomm Atheros Communications   | 1         | 1.09%   |
| Nvidia                            | 1         | 1.09%   |
| Microchip Technology              | 1         | 1.09%   |
| Marvell Technology Group          | 1         | 1.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 17        | 14.53%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 5         | 4.27%   |
| Intel Wi-Fi 6 AX201                                                            | 5         | 4.27%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 4         | 3.42%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 4         | 3.42%   |
| Realtek RTL8188EE Wireless Network Adapter                                     | 3         | 2.56%   |
| Intel Wi-Fi 6 AX200                                                            | 3         | 2.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 3         | 2.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 2         | 1.71%   |
| Realtek 802.11ac NIC                                                           | 2         | 1.71%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 2         | 1.71%   |
| Intel Wireless 8265 / 8275                                                     | 2         | 1.71%   |
| Intel Wireless 7260                                                            | 2         | 1.71%   |
| Intel Wireless 3165                                                            | 2         | 1.71%   |
| Intel Wireless 3160                                                            | 2         | 1.71%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                         | 2         | 1.71%   |
| Intel Wi-Fi 6 AX201 160MHz                                                     | 2         | 1.71%   |
| Intel Tiger Lake PCH CNVi WiFi                                                 | 2         | 1.71%   |
| Intel Ethernet Connection (13) I219-V                                          | 2         | 1.71%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                              | 2         | 1.71%   |
| Intel Centrino Wireless-N 2230                                                 | 2         | 1.71%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 2         | 1.71%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 2         | 1.71%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 2         | 1.71%   |
| TP-Link 802.11ac NIC                                                           | 1         | 0.85%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                       | 1         | 0.85%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                        | 1         | 0.85%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 1         | 0.85%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 0.85%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 0.85%   |
| Quectel Wireless Solutions EM12G-ACER                                          | 1         | 0.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 1         | 0.85%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 1         | 0.85%   |
| Qualcomm Atheros AR9271 802.11n                                                | 1         | 0.85%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)        | 1         | 0.85%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 0.85%   |
| Microchip LAN7500 Ethernet 10/100/1000 Adapter                                 | 1         | 0.85%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.85%   |
| Intel Wireless 8260                                                            | 1         | 0.85%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 39        | 57.35%  |
| Realtek Semiconductor           | 16        | 23.53%  |
| Qualcomm Atheros                | 5         | 7.35%   |
| Broadcom                        | 3         | 4.41%   |
| Broadcom Limited                | 2         | 2.94%   |
| TP-Link                         | 1         | 1.47%   |
| Quectel Wireless Solutions      | 1         | 1.47%   |
| Qualcomm Atheros Communications | 1         | 1.47%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                                     | 5         | 7.35%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 5.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 5.88%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 4.41%   |
| Intel Wi-Fi 6 AX200                                                     | 3         | 4.41%   |
| Realtek 802.11ac NIC                                                    | 2         | 2.94%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2         | 2.94%   |
| Intel Wireless 8265 / 8275                                              | 2         | 2.94%   |
| Intel Wireless 7260                                                     | 2         | 2.94%   |
| Intel Wireless 3165                                                     | 2         | 2.94%   |
| Intel Wireless 3160                                                     | 2         | 2.94%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 2.94%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 2         | 2.94%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 2.94%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 2.94%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 2.94%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 2.94%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 2.94%   |
| TP-Link 802.11ac NIC                                                    | 1         | 1.47%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 1.47%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 1         | 1.47%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.47%   |
| Quectel Wireless Solutions EM12G-ACER                                   | 1         | 1.47%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 1.47%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 1.47%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 1.47%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.47%   |
| Intel Wireless 8260                                                     | 1         | 1.47%   |
| Intel Wireless 7265                                                     | 1         | 1.47%   |
| Intel WiFi Link 5100                                                    | 1         | 1.47%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 1         | 1.47%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 1         | 1.47%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 1.47%   |
| Intel Centrino Wireless-N 2200                                          | 1         | 1.47%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 1         | 1.47%   |
| Intel Centrino Advanced-N 6235                                          | 1         | 1.47%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 1         | 1.47%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 1         | 1.47%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 1         | 1.47%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 1         | 1.47%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 25        | 54.35%  |
| Intel                    | 12        | 26.09%  |
| Broadcom                 | 3         | 6.52%   |
| ASIX Electronics         | 2         | 4.35%   |
| Qualcomm Atheros         | 1         | 2.17%   |
| Nvidia                   | 1         | 2.17%   |
| Microchip Technology     | 1         | 2.17%   |
| Marvell Technology Group | 1         | 2.17%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 17        | 36.17%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 5         | 10.64%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 3         | 6.38%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 2         | 4.26%   |
| Intel Ethernet Connection (13) I219-V                                          | 2         | 4.26%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 2         | 4.26%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 2.13%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 2.13%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 2.13%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 2.13%   |
| Microchip LAN7500 Ethernet 10/100/1000 Adapter                                 | 1         | 2.13%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 2.13%   |
| Intel I210 Gigabit Network Connection                                          | 1         | 2.13%   |
| Intel Ethernet Connection (6) I219-LM                                          | 1         | 2.13%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 2.13%   |
| Intel Ethernet Connection (3) I218-LM                                          | 1         | 2.13%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1         | 2.13%   |
| Intel Ethernet Connection (14) I219-LM                                         | 1         | 2.13%   |
| Intel 82567LM Gigabit Network Connection                                       | 1         | 2.13%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 1         | 2.13%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 1         | 2.13%   |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                              | 1         | 2.13%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 63        | 56.76%  |
| Ethernet | 46        | 41.44%  |
| Modem    | 2         | 1.8%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 55        | 77.46%  |
| Ethernet | 16        | 22.54%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 42        | 66.67%  |
| 1     | 20        | 31.75%  |
| 0     | 1         | 1.59%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 40        | 63.49%  |
| Yes  | 23        | 36.51%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 30        | 52.63%  |
| Realtek Semiconductor           | 9         | 15.79%  |
| IMC Networks                    | 4         | 7.02%   |
| Apple                           | 4         | 7.02%   |
| Cambridge Silicon Radio         | 3         | 5.26%   |
| Broadcom                        | 3         | 5.26%   |
| Toshiba                         | 1         | 1.75%   |
| Qualcomm Atheros Communications | 1         | 1.75%   |
| Hewlett-Packard                 | 1         | 1.75%   |
| Foxconn / Hon Hai               | 1         | 1.75%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                                                               | 11        | 19.3%   |
| Realtek Bluetooth Radio                                                             | 9         | 15.79%  |
| Intel Bluetooth wireless interface                                                  | 7         | 12.28%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 4         | 7.02%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 3         | 5.26%   |
| Intel AX200 Bluetooth                                                               | 3         | 5.26%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 3         | 5.26%   |
| Intel AX210 Bluetooth                                                               | 2         | 3.51%   |
| IMC Networks Bluetooth Radio                                                        | 2         | 3.51%   |
| IMC Networks Bluetooth Device                                                       | 2         | 3.51%   |
| Apple Bluetooth USB Host Controller                                                 | 2         | 3.51%   |
| Apple Bluetooth Host Controller                                                     | 2         | 3.51%   |
| Toshiba Bluetooth Device                                                            | 1         | 1.75%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 1.75%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 1.75%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.75%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter                                    | 1         | 1.75%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 1         | 1.75%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 1         | 1.75%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 48        | 60%     |
| AMD                    | 15        | 18.75%  |
| Nvidia                 | 12        | 15%     |
| C-Media Electronics    | 2         | 2.5%    |
| Meizu                  | 1         | 1.25%   |
| Generalplus Technology | 1         | 1.25%   |
| DSEA A/S               | 1         | 1.25%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 9         | 9.28%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 7         | 7.22%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7         | 7.22%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 5         | 5.15%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3         | 3.09%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 3.09%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 3.09%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 3.09%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 3.09%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 2.06%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2         | 2.06%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 2.06%   |
| Nvidia GA106 High Definition Audio Controller                              | 2         | 2.06%   |
| Nvidia GA104 High Definition Audio Controller                              | 2         | 2.06%   |
| Intel Sunrise Point-LP HD Audio                                            | 2         | 2.06%   |
| Intel Jasper Lake HD Audio                                                 | 2         | 2.06%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 2.06%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 2.06%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 2.06%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 2         | 2.06%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 2.06%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 2.06%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 2.06%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 2.06%   |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 2.06%   |
| AMD High Definition Audio Controller                                       | 2         | 2.06%   |
| AMD FCH Azalia Controller                                                  | 2         | 2.06%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2         | 2.06%   |
| Nvidia stereo controller                                                   | 1         | 1.03%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 1.03%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 1.03%   |
| Meizu HiFi DAC Headphone Amplifier                                         | 1         | 1.03%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 1.03%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 1.03%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 1.03%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 1.03%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 1.03%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 1.03%   |
| Generalplus Technology USB Audio Device                                    | 1         | 1.03%   |
| DSEA A/S EPOS GSA 70                                                       | 1         | 1.03%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 15        | 26.79%  |
| Samsung Electronics | 14        | 25%     |
| Micron Technology   | 8         | 14.29%  |
| Kingston            | 5         | 8.93%   |
| Unknown (ABCD)      | 4         | 7.14%   |
| Unknown             | 4         | 7.14%   |
| Crucial             | 3         | 5.36%   |
| G.Skill             | 2         | 3.57%   |
| Nanya Technology    | 1         | 1.79%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 4         | 6.56%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s         | 3         | 4.92%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 3.28%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 3.28%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                      | 1         | 1.64%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 1.64%   |
| Unknown RAM Module 4096MB SODIMM DDR2                            | 1         | 1.64%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 1.64%   |
| Unknown RAM MEM-DOWN 8192MB SODIMM DDR4 2400MT/s                 | 1         | 1.64%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s                     | 1         | 1.64%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2400MT/s                    | 1         | 1.64%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.64%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.64%   |
| SK hynix RAM HMT351S6BFR8C-G7 4GB SODIMM DDR3 1067MT/s           | 1         | 1.64%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 1.64%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.64%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB Row Of Chips DDR4 2667MT/s     | 1         | 1.64%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.64%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 1.64%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 1.64%   |
| SK hynix RAM HMA851S6DJR6N-XN 4096MB Row Of Chips DDR4 3200MT/s  | 1         | 1.64%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.64%   |
| Samsung RAM Module 1GB SODIMM DDR3 1066MT/s                      | 1         | 1.64%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                     | 1         | 1.64%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 1.64%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.64%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.64%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.64%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.64%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.64%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 1         | 1.64%   |
| Samsung RAM M471A2G44AM0-CWE 16GB Row Of Chips DDR4 3200MT/s     | 1         | 1.64%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.64%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.64%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.64%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s             | 1         | 1.64%   |
| Micron RAM Module 8GB SODIMM DDR4 2400MT/s                       | 1         | 1.64%   |
| Micron RAM 8KTF51264HZ-1G6N1 4GB SODIMM DDR3 1600MT/s            | 1         | 1.64%   |
| Micron RAM 8ATF2G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 1         | 1.64%   |
| Micron RAM 8ATF1G64HZ-2G3B1 8192MB SODIMM DDR4 2400MT/s          | 1         | 1.64%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 25        | 53.19%  |
| DDR3   | 15        | 31.91%  |
| LPDDR4 | 6         | 12.77%  |
| DDR2   | 1         | 2.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 42        | 82.35%  |
| Row Of Chips | 8         | 15.69%  |
| Chip         | 1         | 1.96%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 24        | 45.28%  |
| 4096  | 19        | 35.85%  |
| 16384 | 5         | 9.43%   |
| 32768 | 2         | 3.77%   |
| 2048  | 2         | 3.77%   |
| 1024  | 1         | 1.89%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 17        | 33.33%  |
| 1600    | 10        | 19.61%  |
| 2400    | 9         | 17.65%  |
| 2667    | 6         | 11.76%  |
| 1334    | 2         | 3.92%   |
| Unknown | 2         | 3.92%   |
| 4267    | 1         | 1.96%   |
| 2133    | 1         | 1.96%   |
| 1867    | 1         | 1.96%   |
| 1067    | 1         | 1.96%   |
| 1066    | 1         | 1.96%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Samsung M2070 Series | 1         | 100%    |

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
| Chicony Electronics                    | 19        | 33.33%  |
| Realtek Semiconductor                  | 6         | 10.53%  |
| Quanta                                 | 4         | 7.02%   |
| IMC Networks                           | 4         | 7.02%   |
| Syntek                                 | 3         | 5.26%   |
| Microdia                               | 3         | 5.26%   |
| Apple                                  | 3         | 5.26%   |
| Sunplus Innovation Technology          | 2         | 3.51%   |
| Luxvisions Innotech Limited            | 2         | 3.51%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 3.51%   |
| Acer                                   | 2         | 3.51%   |
| U0AS01A-0                              | 1         | 1.75%   |
| Suyin                                  | 1         | 1.75%   |
| Ricoh                                  | 1         | 1.75%   |
| Lite-On Technology                     | 1         | 1.75%   |
| Lenovo                                 | 1         | 1.75%   |
| ARC International                      | 1         | 1.75%   |
| Alcor Micro                            | 1         | 1.75%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Realtek USB Camera                                              | 4         | 7.02%   |
| Syntek Integrated Camera                                        | 3         | 5.26%   |
| Chicony HP HD Camera                                            | 3         | 5.26%   |
| Quanta HD User Facing                                           | 2         | 3.51%   |
| Microdia Webcam Vitade AF                                       | 2         | 3.51%   |
| Luxvisions Innotech Limited Integrated Camera                   | 2         | 3.51%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 2         | 3.51%   |
| Chicony integrated camera                                       | 2         | 3.51%   |
| Chicony HD User Facing                                          | 2         | 3.51%   |
| Apple Built-in iSight                                           | 2         | 3.51%   |
| U0AS01A-0 U0AS01A-0                                             | 1         | 1.75%   |
| Suyin USB 2.0 Camera                                            | 1         | 1.75%   |
| Sunplus Integrated_Webcam_FHD                                   | 1         | 1.75%   |
| Sunplus HP Truevision HD                                        | 1         | 1.75%   |
| Ricoh Dell Laptop Integrated Webcam                             | 1         | 1.75%   |
| Realtek Laptop_Integrated_Webcam_HD                             | 1         | 1.75%   |
| Realtek Integrated_Webcam_HD                                    | 1         | 1.75%   |
| Quanta ov9734_techfront_camera                                  | 1         | 1.75%   |
| Quanta HP TrueVision HD Camera                                  | 1         | 1.75%   |
| Microdia Integrated_Webcam_2M                                   | 1         | 1.75%   |
| Lite-On HP HD Webcam                                            | 1         | 1.75%   |
| Lenovo CNF7237&CNF7238                                          | 1         | 1.75%   |
| IMC Networks TOSHIBA Web Camera - HD                            | 1         | 1.75%   |
| IMC Networks Integrated Camera                                  | 1         | 1.75%   |
| Chicony USB2.0 VGA UVC WebCam                                   | 1         | 1.75%   |
| Chicony USB2.0 Camera                                           | 1         | 1.75%   |
| Chicony USB 2.0 Camera                                          | 1         | 1.75%   |
| Chicony TOSHIBA Web Camera - HD                                 | 1         | 1.75%   |
| Chicony LG Camera                                               | 1         | 1.75%   |
| Chicony Integrated HP HD Webcam                                 | 1         | 1.75%   |
| Chicony Integrated Camera [ThinkPad]                            | 1         | 1.75%   |
| Chicony HP Webcam                                               | 1         | 1.75%   |
| Chicony HP Truevision HD                                        | 1         | 1.75%   |
| Chicony HD Webcam                                               | 1         | 1.75%   |
| Chicony EasyCamera                                              | 1         | 1.75%   |
| Chicony CNFA078                                                 | 1         | 1.75%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 1         | 1.75%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD         | 1         | 1.75%   |
| ARC International Camera                                        | 1         | 1.75%   |
| Apple FaceTime HD Camera                                        | 1         | 1.75%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 4         | 40%     |
| Validity Sensors           | 3         | 30%     |
| Upek                       | 1         | 10%     |
| Synaptics                  | 1         | 10%     |
| Elan Microelectronics      | 1         | 10%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                        | 4         | 40%     |
| Validity Sensors VFS7500 Touch Fingerprint Sensor          | 1         | 10%     |
| Validity Sensors VFS495 Fingerprint Reader                 | 1         | 10%     |
| Validity Sensors VFS471 Fingerprint Reader                 | 1         | 10%     |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 1         | 10%     |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 10%     |
| Elan ELAN:ARM-M4                                           | 1         | 10%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 4         | 44.44%  |
| Alcor Micro           | 2         | 22.22%  |
| SCM Microsystems      | 1         | 11.11%  |
| O2 Micro              | 1         | 11.11%  |
| Advanced Card Systems | 1         | 11.11%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 22.22%  |
| Broadcom 58200                                                               | 2         | 22.22%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 22.22%  |
| SCM Microsystems SCR3500 A Contact Reader                                    | 1         | 11.11%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 11.11%  |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 11.11%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 40        | 62.5%   |
| 1     | 18        | 28.13%  |
| 2     | 5         | 7.81%   |
| 3     | 1         | 1.56%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 10        | 35.71%  |
| Chipcard              | 9         | 32.14%  |
| Net/wireless          | 2         | 7.14%   |
| Graphics card         | 2         | 7.14%   |
| Camera                | 2         | 7.14%   |
| Multimedia controller | 1         | 3.57%   |
| Flash memory          | 1         | 3.57%   |
| Bluetooth             | 1         | 3.57%   |

