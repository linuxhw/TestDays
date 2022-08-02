Gentoo 2.8 - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------

A project to collect tested hardware configurations for Gentoo 2.8.

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

Total: 110

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| TUXEDO    | InfinityBook Pro 14 Gen6    | [de9a854095](https://linux-hardware.org/?probe=de9a854095) | Jul 31, 2022 |
| Razer     | Blade 15 Studio Edition ... | [359f708604](https://linux-hardware.org/?probe=359f708604) | Jul 30, 2022 |
| ASUSTek   | ROG G703GI_G7BI             | [88a326be83](https://linux-hardware.org/?probe=88a326be83) | Jul 28, 2022 |
| Dell      | XPS 15 9570                 | [e7f56631b1](https://linux-hardware.org/?probe=e7f56631b1) | Jul 27, 2022 |
| Dell      | XPS 15 9570                 | [f3972b3a7d](https://linux-hardware.org/?probe=f3972b3a7d) | Jul 26, 2022 |
| Timi      | Mi Laptop Pro 15 2020       | [5455e664e0](https://linux-hardware.org/?probe=5455e664e0) | Jul 26, 2022 |
| HP        | EliteBook 845 G7 Noteboo... | [b15fb90c18](https://linux-hardware.org/?probe=b15fb90c18) | Jul 26, 2022 |
| HP        | OMEN by Laptop 16-c0xxx     | [8f46b7dcca](https://linux-hardware.org/?probe=8f46b7dcca) | Jul 25, 2022 |
| HP        | Laptop 17-ca1xxx            | [64dad58b71](https://linux-hardware.org/?probe=64dad58b71) | Jul 25, 2022 |
| ASUSTek   | ROG Zephyrus G14 GA402RJ... | [6302f1ee8b](https://linux-hardware.org/?probe=6302f1ee8b) | Jul 25, 2022 |
| ASUSTek   | ROG G703GI_G7BI             | [4d636c74d3](https://linux-hardware.org/?probe=4d636c74d3) | Jul 14, 2022 |
| MSI       | GS63VR 6RF                  | [30ad17796f](https://linux-hardware.org/?probe=30ad17796f) | Jul 11, 2022 |
| Lenovo    | IdeaPad 100-15IBD 80QQ      | [94e9d2f65a](https://linux-hardware.org/?probe=94e9d2f65a) | Jul 10, 2022 |
| Lenovo    | G510 20238                  | [f67a64f833](https://linux-hardware.org/?probe=f67a64f833) | Jul 10, 2022 |
| Lenovo    | ThinkPad T14 Gen 2a 20XK... | [8f36480ad7](https://linux-hardware.org/?probe=8f36480ad7) | Jul 10, 2022 |
| Dell      | Latitude D420               | [2e3ded5234](https://linux-hardware.org/?probe=2e3ded5234) | Jul 08, 2022 |
| MSI       | GS63VR 6RF                  | [097cc820d3](https://linux-hardware.org/?probe=097cc820d3) | Jul 08, 2022 |
| Lenovo    | G510 20238                  | [5bdfb575ae](https://linux-hardware.org/?probe=5bdfb575ae) | Jul 07, 2022 |
| ASUSTek   | VivoBook_ASUSLaptop M760... | [850003c6da](https://linux-hardware.org/?probe=850003c6da) | Jul 05, 2022 |
| Lenovo    | IdeaPad 3 15ALC6 82KU       | [1b94ade16a](https://linux-hardware.org/?probe=1b94ade16a) | Jul 05, 2022 |
| HP        | EliteBook 2560p             | [c1e5d91a40](https://linux-hardware.org/?probe=c1e5d91a40) | Jul 02, 2022 |
| Dell      | Latitude D420               | [162b346743](https://linux-hardware.org/?probe=162b346743) | Jul 02, 2022 |
| Timi      | RedmiBook 13                | [fb3b3f37d5](https://linux-hardware.org/?probe=fb3b3f37d5) | Jun 30, 2022 |
| Dell      | Latitude D420               | [c531c131ec](https://linux-hardware.org/?probe=c531c131ec) | Jun 28, 2022 |
| ASUSTek   | X555LJ                      | [0c6dd4c77c](https://linux-hardware.org/?probe=0c6dd4c77c) | Jun 27, 2022 |
| Dell      | Precision 7550              | [4779d18806](https://linux-hardware.org/?probe=4779d18806) | Jun 24, 2022 |
| AVITA     | NS14A6                      | [e3169acbbb](https://linux-hardware.org/?probe=e3169acbbb) | Jun 20, 2022 |
| Lenovo    | ThinkPad T460 20FMS421US    | [b290cf5fe0](https://linux-hardware.org/?probe=b290cf5fe0) | Jun 19, 2022 |
| Lenovo    | ThinkPad T14 Gen 2a 20XK... | [27fd147a80](https://linux-hardware.org/?probe=27fd147a80) | Jun 19, 2022 |
| ASUSTek   | ROG Strix G513QY_G513QY     | [17b77e3069](https://linux-hardware.org/?probe=17b77e3069) | Jun 17, 2022 |
| Dell      | Inspiron 15 5510            | [286f8505c9](https://linux-hardware.org/?probe=286f8505c9) | Jun 17, 2022 |
| HP        | OMEN by Laptop              | [7b531e1607](https://linux-hardware.org/?probe=7b531e1607) | Jun 09, 2022 |
| HP        | OMEN by Laptop 15-dc0xxx    | [f2ca17eb5d](https://linux-hardware.org/?probe=f2ca17eb5d) | Jun 05, 2022 |
| Lenovo    | ThinkPad T14 Gen 1 20S1S... | [0c1909c43b](https://linux-hardware.org/?probe=0c1909c43b) | Jun 03, 2022 |
| Dell      | XPS 17 9710                 | [d17975e27b](https://linux-hardware.org/?probe=d17975e27b) | Jun 02, 2022 |
| HUAWEI    | BOHB-WAX9                   | [0a458659f6](https://linux-hardware.org/?probe=0a458659f6) | Jun 01, 2022 |
| Lenovo    | Legion Y540-15IRH 81SX      | [09fcdacb15](https://linux-hardware.org/?probe=09fcdacb15) | Jun 01, 2022 |
| Dell      | XPS 17 9710                 | [d33b756434](https://linux-hardware.org/?probe=d33b756434) | Jun 01, 2022 |
| Lenovo    | ThinkPad T14 Gen 1 20S1S... | [1be8c71a37](https://linux-hardware.org/?probe=1be8c71a37) | May 30, 2022 |
| Lenovo    | ThinkPad T14 Gen 1 20S1S... | [2669150033](https://linux-hardware.org/?probe=2669150033) | May 29, 2022 |
| Lenovo    | ThinkPad T14 Gen 1 20S1S... | [77989d3d20](https://linux-hardware.org/?probe=77989d3d20) | May 28, 2022 |
| HP        | Pavilion Gaming Laptop 1... | [e879d3c292](https://linux-hardware.org/?probe=e879d3c292) | May 27, 2022 |
| ASUSTek   | 1005HA                      | [0948f30719](https://linux-hardware.org/?probe=0948f30719) | May 26, 2022 |
| ASUSTek   | 1005HA                      | [1d5fe9025a](https://linux-hardware.org/?probe=1d5fe9025a) | May 25, 2022 |
| Lenovo    | ThinkPad T460 20FMS421US    | [47297bafb5](https://linux-hardware.org/?probe=47297bafb5) | May 21, 2022 |
| Lenovo    | ThinkPad T460 20FMS421US    | [7b878500c1](https://linux-hardware.org/?probe=7b878500c1) | May 21, 2022 |
| MSI       | MS-7A34                     | [8956078328](https://linux-hardware.org/?probe=8956078328) | May 21, 2022 |
| MSI       | GE66 Raider 11UE            | [d1a9527039](https://linux-hardware.org/?probe=d1a9527039) | May 16, 2022 |
| MSI       | GE66 Raider 11UE            | [d675d89c8a](https://linux-hardware.org/?probe=d675d89c8a) | May 16, 2022 |
| Lenovo    | ThinkPad P73 20QSS09S00     | [8438c92818](https://linux-hardware.org/?probe=8438c92818) | May 12, 2022 |
| HP        | Laptop 15s-eq0xxx           | [474578814d](https://linux-hardware.org/?probe=474578814d) | May 10, 2022 |
| Dell      | XPS 15 9510                 | [a934bef382](https://linux-hardware.org/?probe=a934bef382) | Apr 24, 2022 |
| Dell      | XPS 15 9510                 | [b61b2af9eb](https://linux-hardware.org/?probe=b61b2af9eb) | Apr 23, 2022 |
| Lenovo    | ThinkPad X220 4291QT1       | [9ffcb6bf7a](https://linux-hardware.org/?probe=9ffcb6bf7a) | Apr 18, 2022 |
| HP        | Pavilion Notebook           | [217905d42a](https://linux-hardware.org/?probe=217905d42a) | Apr 17, 2022 |
| Lenovo    | ThinkPad X220 4291QT1       | [00a23bc10c](https://linux-hardware.org/?probe=00a23bc10c) | Apr 17, 2022 |
| Dell      | G5 5505                     | [ce1fc33387](https://linux-hardware.org/?probe=ce1fc33387) | Apr 13, 2022 |
| MSI       | GE66 Raider 11UE            | [45472dad72](https://linux-hardware.org/?probe=45472dad72) | Apr 12, 2022 |
| HP        | ProBook 6570b               | [63d922ecdd](https://linux-hardware.org/?probe=63d922ecdd) | Apr 12, 2022 |
| HP        | ProBook 6570b               | [87414e70aa](https://linux-hardware.org/?probe=87414e70aa) | Apr 11, 2022 |
| System76  | Gazelle                     | [9edcac1b2c](https://linux-hardware.org/?probe=9edcac1b2c) | Apr 09, 2022 |
| System76  | Gazelle                     | [e22baecee4](https://linux-hardware.org/?probe=e22baecee4) | Apr 07, 2022 |
| Timi      | Mi Laptop Pro 15            | [33f98f8274](https://linux-hardware.org/?probe=33f98f8274) | Mar 23, 2022 |
| BANGHO    | MAX G0101                   | [b40c195d54](https://linux-hardware.org/?probe=b40c195d54) | Mar 20, 2022 |
| MSI       | MS-7A34                     | [27f8a2eb1f](https://linux-hardware.org/?probe=27f8a2eb1f) | Mar 18, 2022 |
| HP        | Victus by Laptop 16-e0xx... | [7c09492e3b](https://linux-hardware.org/?probe=7c09492e3b) | Mar 14, 2022 |
| HP        | Victus by Laptop 16-e0xx... | [f7e85dbf71](https://linux-hardware.org/?probe=f7e85dbf71) | Mar 14, 2022 |
| Framework | Laptop                      | [8902c057fb](https://linux-hardware.org/?probe=8902c057fb) | Mar 10, 2022 |
| Framework | Laptop                      | [e17db20b1c](https://linux-hardware.org/?probe=e17db20b1c) | Mar 08, 2022 |
| Lenovo    | Yoga Slim 7 14IIL05 82A1    | [0022f4a8cc](https://linux-hardware.org/?probe=0022f4a8cc) | Feb 26, 2022 |
| ASUSTek   | UX430UAR                    | [c7cd5ce50d](https://linux-hardware.org/?probe=c7cd5ce50d) | Feb 21, 2022 |
| MSI       | GS63VR 6RF                  | [c20c87027e](https://linux-hardware.org/?probe=c20c87027e) | Feb 10, 2022 |
| HP        | Pavilion Notebook           | [8f79e4d763](https://linux-hardware.org/?probe=8f79e4d763) | Feb 06, 2022 |
| Lenovo    | Legion Y7000 2019 PG0 81... | [f79196e39c](https://linux-hardware.org/?probe=f79196e39c) | Feb 05, 2022 |
| MSI       | GS63VR 6RF                  | [4873365af6](https://linux-hardware.org/?probe=4873365af6) | Jan 30, 2022 |
| Lenovo    | Yoga S740-14IIL 81RS        | [c021622ad4](https://linux-hardware.org/?probe=c021622ad4) | Jan 27, 2022 |
| Timi      | RedmiBook 13                | [e20538f56a](https://linux-hardware.org/?probe=e20538f56a) | Jan 26, 2022 |
| Lenovo    | IdeaPad 5 15ITL05 82FG      | [a4f6a4a38e](https://linux-hardware.org/?probe=a4f6a4a38e) | Jan 24, 2022 |
| Lenovo    | IdeaPad 5 15ITL05 82FG      | [9e4f498056](https://linux-hardware.org/?probe=9e4f498056) | Jan 24, 2022 |
| MSI       | GE73 Raider RGB 8RF         | [a5a825a072](https://linux-hardware.org/?probe=a5a825a072) | Jan 22, 2022 |
| Lenovo    | ThinkPad 20FMCT01WW         | [4bd81196a0](https://linux-hardware.org/?probe=4bd81196a0) | Jan 21, 2022 |
| Timi      | Mi Laptop Pro 15            | [65ce2eb070](https://linux-hardware.org/?probe=65ce2eb070) | Jan 19, 2022 |
| Lenovo    | ThinkPad X1 Carbon 7th 2... | [d786a0b993](https://linux-hardware.org/?probe=d786a0b993) | Jan 17, 2022 |
| Lenovo    | ThinkPad X1 Carbon 7th 2... | [6af6121c33](https://linux-hardware.org/?probe=6af6121c33) | Jan 17, 2022 |
| Dell      | Precision 3561              | [f5417a1852](https://linux-hardware.org/?probe=f5417a1852) | Jan 16, 2022 |
| Lenovo    | Legion 5 Pro 16ACH6H 82J... | [2aa146518a](https://linux-hardware.org/?probe=2aa146518a) | Jan 16, 2022 |
| Lenovo    | Legion R7000 2020 82B6      | [5f92f3376e](https://linux-hardware.org/?probe=5f92f3376e) | Jan 11, 2022 |
| Acer      | Nitro AN515-54              | [d46da820e0](https://linux-hardware.org/?probe=d46da820e0) | Jan 10, 2022 |
| ASUSTek   | ROG Zephyrus G14 GA401QE... | [0cf6f2102c](https://linux-hardware.org/?probe=0cf6f2102c) | Jan 03, 2022 |
| Timi      | RedmiBook 13                | [528d0d32b4](https://linux-hardware.org/?probe=528d0d32b4) | Jan 01, 2022 |
| Dell      | XPS 15 9570                 | [1695a19b52](https://linux-hardware.org/?probe=1695a19b52) | Dec 24, 2021 |
| Framework | Laptop                      | [33bb6590a6](https://linux-hardware.org/?probe=33bb6590a6) | Dec 21, 2021 |
| ASUSTek   | ROG Strix G513QY_G513QY     | [ee63a84605](https://linux-hardware.org/?probe=ee63a84605) | Dec 11, 2021 |
| Toshiba   | Satellite C850D-118         | [b15f2e2c92](https://linux-hardware.org/?probe=b15f2e2c92) | Dec 09, 2021 |
| HP        | Laptop 15s-eq0xxx           | [86f5c0bc34](https://linux-hardware.org/?probe=86f5c0bc34) | Nov 30, 2021 |
| HP        | Laptop 15s-eq0xxx           | [e06c73ada9](https://linux-hardware.org/?probe=e06c73ada9) | Nov 29, 2021 |
| Lenovo    | IdeaPad 5 Pro 16ACH6 82L... | [ad15be0510](https://linux-hardware.org/?probe=ad15be0510) | Nov 29, 2021 |
| Lenovo    | ThinkPad T470p 20J7S06Q0... | [6eca4a1be2](https://linux-hardware.org/?probe=6eca4a1be2) | Nov 22, 2021 |
| Lenovo    | ThinkPad T470p 20J7S06Q0... | [6c92c6ecbb](https://linux-hardware.org/?probe=6c92c6ecbb) | Nov 22, 2021 |
| Acer      | Aspire A715-42G             | [3ea389d8ff](https://linux-hardware.org/?probe=3ea389d8ff) | Nov 21, 2021 |
| Acer      | Aspire A715-42G             | [19f48288ec](https://linux-hardware.org/?probe=19f48288ec) | Nov 20, 2021 |
| Lenovo    | ThinkPad E495 20NE000BGE    | [871e0a8d36](https://linux-hardware.org/?probe=871e0a8d36) | Nov 11, 2021 |
| Dell      | Latitude 7490               | [ea64667f2c](https://linux-hardware.org/?probe=ea64667f2c) | Nov 01, 2021 |
| Lenovo    | ThinkPad P1 Gen 3 20TJS2... | [6105164e23](https://linux-hardware.org/?probe=6105164e23) | Oct 26, 2021 |
| Lenovo    | ThinkPad E15 Gen 2 20T80... | [8a34d739fd](https://linux-hardware.org/?probe=8a34d739fd) | Oct 25, 2021 |
| Acer      | Aspire A515-55              | [437c8fb96b](https://linux-hardware.org/?probe=437c8fb96b) | Oct 12, 2021 |
| Lenovo    | ThinkBook 14 G3 ACL 21A2    | [3ad4e11bac](https://linux-hardware.org/?probe=3ad4e11bac) | Oct 06, 2021 |
| Lenovo    | ThinkBook 14 G3 ACL 21A2    | [18a2385458](https://linux-hardware.org/?probe=18a2385458) | Oct 06, 2021 |
| Timi      | Mi Laptop Pro 15            | [e2057e68dd](https://linux-hardware.org/?probe=e2057e68dd) | Oct 03, 2021 |
| Dell      | Inspiron 5415               | [a265f8ea5c](https://linux-hardware.org/?probe=a265f8ea5c) | Oct 01, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                         | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| 5.14.9-gentoo-x86_64                            | 3         | 3.45%   |
| 5.18.7-gentoo                                   | 2         | 2.3%    |
| 5.18.4-gentoo                                   | 2         | 2.3%    |
| 5.18.1-gentoo-r2                                | 2         | 2.3%    |
| 5.17.1-gentoo-r1                                | 2         | 2.3%    |
| 5.16.0-gentoo-x86_64                            | 2         | 2.3%    |
| 5.15.52-gentoo                                  | 2         | 2.3%    |
| 5.15.41-gentoo-dist                             | 2         | 2.3%    |
| 5.15.10-gentoo-x86_64                           | 2         | 2.3%    |
| 5.19.0-rc2-p+                                   | 1         | 1.15%   |
| 5.18.9-gentoo                                   | 1         | 1.15%   |
| 5.18.8-gentoo-dist                              | 1         | 1.15%   |
| 5.18.8-gentoo                                   | 1         | 1.15%   |
| 5.18.6-gentoo-venus                             | 1         | 1.15%   |
| 5.18.5-gentoo                                   | 1         | 1.15%   |
| 5.18.10-k08                                     | 1         | 1.15%   |
| 5.18.1-gentoo-r1-x86_64                         | 1         | 1.15%   |
| 5.18.1-gentoo-r1                                | 1         | 1.15%   |
| 5.18.0-rc7-x86_64-git-00119-gb015dcd62b86-dirty | 1         | 1.15%   |
| 5.18.0-gbfc780ef1ca0                            | 1         | 1.15%   |
| 5.18.0-g95ff72a6c129                            | 1         | 1.15%   |
| 5.17.9-gentoo-x86_64                            | 1         | 1.15%   |
| 5.17.9-gentoo-x86                               | 1         | 1.15%   |
| 5.17.9-gentoo                                   | 1         | 1.15%   |
| 5.17.8-gentoo-x86_64                            | 1         | 1.15%   |
| 5.17.8-gentoo                                   | 1         | 1.15%   |
| 5.17.7-gentoo-groovin                           | 1         | 1.15%   |
| 5.17.6-zen1                                     | 1         | 1.15%   |
| 5.17.5-gentoo-dist                              | 1         | 1.15%   |
| 5.17.3-gentoo                                   | 1         | 1.15%   |
| 5.17.2-gentoo-groovin                           | 1         | 1.15%   |
| 5.17.13-gentoo                                  | 1         | 1.15%   |
| 5.17.12-gentoo-dist                             | 1         | 1.15%   |
| 5.17.0-gentoo-x86_64                            | 1         | 1.15%   |
| 5.16.9-gentoo-dist                              | 1         | 1.15%   |
| 5.16.8-gentoo-gentoo-dist                       | 1         | 1.15%   |
| 5.16.5-gentoo-x86_64                            | 1         | 1.15%   |
| 5.16.2-gentoo-x86_64                            | 1         | 1.15%   |
| 5.16.2-gentoo                                   | 1         | 1.15%   |
| 5.16.14-gentoo-x86_64-lto                       | 1         | 1.15%   |
| 5.16.14-gentoo                                  | 1         | 1.15%   |
| 5.16.11-gentoo-dist                             | 1         | 1.15%   |
| 5.16.10-gentoo--20-feb-2022                     | 1         | 1.15%   |
| 5.16.10-gentoo                                  | 1         | 1.15%   |
| 5.16.1-gentoo-x86_64                            | 1         | 1.15%   |
| 5.16.1-gentoo                                   | 1         | 1.15%   |
| 5.16.0-xanmod1                                  | 1         | 1.15%   |
| 5.16.0-pf5                                      | 1         | 1.15%   |
| 5.16.0-kali7-amd64                              | 1         | 1.15%   |
| 5.16.0-gentoo-gentoo-dist                       | 1         | 1.15%   |
| 5.16.0-gentoo                                   | 1         | 1.15%   |
| 5.15.7-gentoo                                   | 1         | 1.15%   |
| 5.15.6-gentoo                                   | 1         | 1.15%   |
| 5.15.52-gentoo-XXX                              | 1         | 1.15%   |
| 5.15.52-gentoo-x86_64                           | 1         | 1.15%   |
| 5.15.52-gentoo-dist                             | 1         | 1.15%   |
| 5.15.5-gentoo-x86_64                            | 1         | 1.15%   |
| 5.15.5-gentoo-dist                              | 1         | 1.15%   |
| 5.15.5-gentoo                                   | 1         | 1.15%   |
| 5.15.41-gentoo-x86_64                           | 1         | 1.15%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.16.0  | 7         | 8.14%   |
| 5.15.52 | 5         | 5.81%   |
| 5.18.1  | 4         | 4.65%   |
| 5.15.41 | 4         | 4.65%   |
| 5.14.9  | 4         | 4.65%   |
| 5.17.9  | 3         | 3.49%   |
| 5.15.5  | 3         | 3.49%   |
| 5.18.8  | 2         | 2.33%   |
| 5.18.7  | 2         | 2.33%   |
| 5.18.4  | 2         | 2.33%   |
| 5.18.0  | 2         | 2.33%   |
| 5.17.8  | 2         | 2.33%   |
| 5.17.1  | 2         | 2.33%   |
| 5.16.2  | 2         | 2.33%   |
| 5.16.14 | 2         | 2.33%   |
| 5.16.10 | 2         | 2.33%   |
| 5.16.1  | 2         | 2.33%   |
| 5.15.33 | 2         | 2.33%   |
| 5.15.13 | 2         | 2.33%   |
| 5.15.10 | 2         | 2.33%   |
| 5.14.14 | 2         | 2.33%   |
| 5.19.0  | 1         | 1.16%   |
| 5.18.9  | 1         | 1.16%   |
| 5.18.6  | 1         | 1.16%   |
| 5.18.5  | 1         | 1.16%   |
| 5.18.10 | 1         | 1.16%   |
| 5.17.7  | 1         | 1.16%   |
| 5.17.6  | 1         | 1.16%   |
| 5.17.5  | 1         | 1.16%   |
| 5.17.3  | 1         | 1.16%   |
| 5.17.2  | 1         | 1.16%   |
| 5.17.13 | 1         | 1.16%   |
| 5.17.12 | 1         | 1.16%   |
| 5.17.0  | 1         | 1.16%   |
| 5.16.9  | 1         | 1.16%   |
| 5.16.8  | 1         | 1.16%   |
| 5.16.5  | 1         | 1.16%   |
| 5.16.11 | 1         | 1.16%   |
| 5.15.7  | 1         | 1.16%   |
| 5.15.6  | 1         | 1.16%   |
| 5.15.35 | 1         | 1.16%   |
| 5.15.19 | 1         | 1.16%   |
| 5.15.12 | 1         | 1.16%   |
| 5.15.1  | 1         | 1.16%   |
| 5.14.7  | 1         | 1.16%   |
| 5.10.83 | 1         | 1.16%   |
| 5.10.76 | 1         | 1.16%   |
| 5.10.70 | 1         | 1.16%   |
| 5.10.27 | 1         | 1.16%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 23        | 27.71%  |
| 5.16    | 18        | 21.69%  |
| 5.18    | 16        | 19.28%  |
| 5.17    | 14        | 16.87%  |
| 5.14    | 7         | 8.43%   |
| 5.10    | 4         | 4.82%   |
| 5.19    | 1         | 1.2%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 74        | 97.37%  |
| i686   | 2         | 2.63%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Unknown  | 30        | 38.96%  |
| KDE5     | 23        | 29.87%  |
| GNOME    | 10        | 12.99%  |
| XFCE     | 6         | 7.79%   |
| sway     | 2         | 2.6%    |
| xmonad   | 1         | 1.3%    |
| MATE     | 1         | 1.3%    |
| LeftWM   | 1         | 1.3%    |
| fvwm     | 1         | 1.3%    |
| DWM      | 1         | 1.3%    |
| Cinnamon | 1         | 1.3%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 35        | 44.3%   |
| Wayland | 17        | 21.52%  |
| Unknown | 14        | 17.72%  |
| Tty     | 13        | 16.46%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 33        | 42.86%  |
| SDDM    | 27        | 35.06%  |
| LightDM | 8         | 10.39%  |
| GDM     | 5         | 6.49%   |
| SLiM    | 2         | 2.6%    |
| XDM     | 1         | 1.3%    |
| GREETD  | 1         | 1.3%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Notebooks | Percent |
|------------|-----------|---------|
| en_US      | 38        | 50%     |
| Unknown    | 7         | 9.21%   |
| en_GB      | 6         | 7.89%   |
| C.UTF8     | 6         | 7.89%   |
| ru_RU      | 2         | 2.63%   |
| it_IT      | 2         | 2.63%   |
| es_AR      | 2         | 2.63%   |
| de_DE      | 2         | 2.63%   |
| C          | 2         | 2.63%   |
| zh_CN      | 1         | 1.32%   |
| tr_TR      | 1         | 1.32%   |
| fr_FR      | 1         | 1.32%   |
| fr_CA      | 1         | 1.32%   |
| es_MX      | 1         | 1.32%   |
| en_US.UTF8 | 1         | 1.32%   |
| en_NZ      | 1         | 1.32%   |
| en_AU      | 1         | 1.32%   |
| el_GR      | 1         | 1.32%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 70        | 90.91%  |
| BIOS | 7         | 9.09%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 43        | 56.58%  |
| Btrfs    | 27        | 35.53%  |
| Zfs      | 3         | 3.95%   |
| Overlay  | 1         | 1.32%   |
| F2fs     | 1         | 1.32%   |
| Bcachefs | 1         | 1.32%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 70        | 92.11%  |
| MBR  | 6         | 7.89%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 58        | 73.42%  |
| Yes       | 21        | 26.58%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 59        | 76.62%  |
| Yes       | 18        | 23.38%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 24        | 31.58%  |
| Hewlett-Packard  | 12        | 15.79%  |
| Dell             | 11        | 14.47%  |
| ASUSTek Computer | 9         | 11.84%  |
| MSI              | 5         | 6.58%   |
| Timi             | 3         | 3.95%   |
| Acer             | 3         | 3.95%   |
| Framework        | 2         | 2.63%   |
| TUXEDO           | 1         | 1.32%   |
| Toshiba          | 1         | 1.32%   |
| System76         | 1         | 1.32%   |
| Razer            | 1         | 1.32%   |
| HUAWEI           | 1         | 1.32%   |
| BANGHO           | 1         | 1.32%   |
| AVITA            | 1         | 1.32%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| MSI GS63VR 6RF                            | 2         | 2.63%   |
| HP Laptop 15s-eq0xxx                      | 2         | 2.63%   |
| Framework Laptop                          | 2         | 2.63%   |
| Dell XPS 15 9570                          | 2         | 2.63%   |
| ASUS ROG Strix G513QY_G513QY              | 2         | 2.63%   |
| TUXEDO InfinityBook Pro 14 Gen6           | 1         | 1.32%   |
| Toshiba Satellite C850D-118               | 1         | 1.32%   |
| Timi RedmiBook 13                         | 1         | 1.32%   |
| Timi Mi Laptop Pro 15 2020                | 1         | 1.32%   |
| Timi Mi Laptop Pro 15                     | 1         | 1.32%   |
| System76 Gazelle                          | 1         | 1.32%   |
| Razer Blade 15 Studio Edition - Late 2019 | 1         | 1.32%   |
| MSI MS-7A34                               | 1         | 1.32%   |
| MSI GE73 Raider RGB 8RF                   | 1         | 1.32%   |
| MSI GE66 Raider 11UE                      | 1         | 1.32%   |
| Lenovo Yoga Slim 7 14IIL05 82A1           | 1         | 1.32%   |
| Lenovo Yoga S740-14IIL 81RS               | 1         | 1.32%   |
| Lenovo ThinkPad X220 4291QT1              | 1         | 1.32%   |
| Lenovo ThinkPad X1 Carbon 7th 20QD0039RI  | 1         | 1.32%   |
| Lenovo ThinkPad T470p 20J7S06Q00          | 1         | 1.32%   |
| Lenovo ThinkPad T460 20FMS421US           | 1         | 1.32%   |
| Lenovo ThinkPad T14 Gen 2a 20XK002SCK     | 1         | 1.32%   |
| Lenovo ThinkPad T14 Gen 2a 20XK000YRI     | 1         | 1.32%   |
| Lenovo ThinkPad T14 Gen 1 20S1S35Y00      | 1         | 1.32%   |
| Lenovo ThinkPad P73 20QSS09S00            | 1         | 1.32%   |
| Lenovo ThinkPad P1 Gen 3 20TJS2F437       | 1         | 1.32%   |
| Lenovo ThinkPad E495 20NE000BGE           | 1         | 1.32%   |
| Lenovo ThinkPad E15 Gen 2 20T8001STX      | 1         | 1.32%   |
| Lenovo ThinkPad 20FMCT01WW                | 1         | 1.32%   |
| Lenovo ThinkBook 14 G3 ACL 21A2           | 1         | 1.32%   |
| Lenovo Legion Y7000 2019 PG0 81T0         | 1         | 1.32%   |
| Lenovo Legion Y540-15IRH 81SX             | 1         | 1.32%   |
| Lenovo Legion R7000 2020 82B6             | 1         | 1.32%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ          | 1         | 1.32%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5          | 1         | 1.32%   |
| Lenovo IdeaPad 5 15ITL05 82FG             | 1         | 1.32%   |
| Lenovo IdeaPad 3 15ALC6 82KU              | 1         | 1.32%   |
| Lenovo IdeaPad 100-15IBD 80QQ             | 1         | 1.32%   |
| Lenovo G510 20238                         | 1         | 1.32%   |
| HUAWEI BOHB-WAX9                          | 1         | 1.32%   |
| HP Victus by Laptop 16-e0xxx              | 1         | 1.32%   |
| HP ProBook 6570b                          | 1         | 1.32%   |
| HP Pavilion Notebook                      | 1         | 1.32%   |
| HP Pavilion Gaming Laptop 15-cx0xxx       | 1         | 1.32%   |
| HP OMEN by Laptop 16-c0xxx                | 1         | 1.32%   |
| HP OMEN by Laptop 15-dc0xxx               | 1         | 1.32%   |
| HP OMEN by Laptop                         | 1         | 1.32%   |
| HP Laptop 17-ca1xxx                       | 1         | 1.32%   |
| HP EliteBook 845 G7 Notebook PC           | 1         | 1.32%   |
| HP EliteBook 2560p                        | 1         | 1.32%   |
| Dell XPS 17 9710                          | 1         | 1.32%   |
| Dell XPS 15 9510                          | 1         | 1.32%   |
| Dell Precision 7550                       | 1         | 1.32%   |
| Dell Precision 3561                       | 1         | 1.32%   |
| Dell Latitude D420                        | 1         | 1.32%   |
| Dell Latitude 7490                        | 1         | 1.32%   |
| Dell Inspiron 5415                        | 1         | 1.32%   |
| Dell Inspiron 15 5510                     | 1         | 1.32%   |
| Dell G5 5505                              | 1         | 1.32%   |
| BANGHO MAX G0101                          | 1         | 1.32%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 12        | 15.79%  |
| ASUS ROG            | 5         | 6.58%   |
| Lenovo Legion       | 4         | 5.26%   |
| Lenovo IdeaPad      | 4         | 5.26%   |
| Dell XPS            | 4         | 5.26%   |
| HP OMEN             | 3         | 3.95%   |
| HP Laptop           | 3         | 3.95%   |
| Timi Mi             | 2         | 2.63%   |
| MSI GS63VR          | 2         | 2.63%   |
| Lenovo Yoga         | 2         | 2.63%   |
| HP Pavilion         | 2         | 2.63%   |
| HP EliteBook        | 2         | 2.63%   |
| Framework Laptop    | 2         | 2.63%   |
| Dell Precision      | 2         | 2.63%   |
| Dell Latitude       | 2         | 2.63%   |
| Dell Inspiron       | 2         | 2.63%   |
| Acer Aspire         | 2         | 2.63%   |
| TUXEDO InfinityBook | 1         | 1.32%   |
| Toshiba Satellite   | 1         | 1.32%   |
| Timi RedmiBook      | 1         | 1.32%   |
| System76 Gazelle    | 1         | 1.32%   |
| Razer Blade         | 1         | 1.32%   |
| MSI MS-7A34         | 1         | 1.32%   |
| MSI GE73            | 1         | 1.32%   |
| MSI GE66            | 1         | 1.32%   |
| Lenovo ThinkBook    | 1         | 1.32%   |
| Lenovo G510         | 1         | 1.32%   |
| HUAWEI BOHB-WAX9    | 1         | 1.32%   |
| HP Victus           | 1         | 1.32%   |
| HP ProBook          | 1         | 1.32%   |
| Dell G5             | 1         | 1.32%   |
| BANGHO MAX          | 1         | 1.32%   |
| AVITA NS14A6        | 1         | 1.32%   |
| ASUS X555LJ         | 1         | 1.32%   |
| ASUS VivoBook       | 1         | 1.32%   |
| ASUS UX430UAR       | 1         | 1.32%   |
| ASUS 1005HA         | 1         | 1.32%   |
| Acer Nitro          | 1         | 1.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 25        | 32.89%  |
| 2020 | 14        | 18.42%  |
| 2019 | 14        | 18.42%  |
| 2018 | 6         | 7.89%   |
| 2017 | 3         | 3.95%   |
| 2016 | 3         | 3.95%   |
| 2015 | 2         | 2.63%   |
| 2012 | 2         | 2.63%   |
| 2011 | 2         | 2.63%   |
| 2022 | 1         | 1.32%   |
| 2014 | 1         | 1.32%   |
| 2013 | 1         | 1.32%   |
| 2009 | 1         | 1.32%   |
| 2006 | 1         | 1.32%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 76        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 74        | 96.1%   |
| Enabled  | 3         | 3.9%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 75        | 98.68%  |
| Yes  | 1         | 1.32%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 21        | 27.63%  |
| 16.01-24.0  | 19        | 25%     |
| 32.01-64.0  | 14        | 18.42%  |
| 4.01-8.0    | 12        | 15.79%  |
| 3.01-4.0    | 3         | 3.95%   |
| 64.01-256.0 | 3         | 3.95%   |
| 24.01-32.0  | 1         | 1.32%   |
| 2.01-3.0    | 1         | 1.32%   |
| 1.01-2.0    | 1         | 1.32%   |
| 0.51-1.0    | 1         | 1.32%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 4.01-8.0  | 20        | 24.39%  |
| 1.01-2.0  | 17        | 20.73%  |
| 3.01-4.0  | 14        | 17.07%  |
| 2.01-3.0  | 12        | 14.63%  |
| 8.01-16.0 | 9         | 10.98%  |
| 0.51-1.0  | 8         | 9.76%   |
| 0.01-0.5  | 2         | 2.44%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 53        | 68.83%  |
| 2      | 20        | 25.97%  |
| 3      | 3         | 3.9%    |
| 4      | 1         | 1.3%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 69        | 90.79%  |
| Yes       | 7         | 9.21%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 53        | 69.74%  |
| No        | 23        | 30.26%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 76        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 69        | 89.61%  |
| No        | 8         | 10.39%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 15        | 19.48%  |
| Germany     | 7         | 9.09%   |
| UK          | 6         | 7.79%   |
| Russia      | 5         | 6.49%   |
| China       | 5         | 6.49%   |
| France      | 3         | 3.9%    |
| Belarus     | 3         | 3.9%    |
| Sweden      | 2         | 2.6%    |
| Spain       | 2         | 2.6%    |
| Romania     | 2         | 2.6%    |
| Poland      | 2         | 2.6%    |
| Italy       | 2         | 2.6%    |
| India       | 2         | 2.6%    |
| Greece      | 2         | 2.6%    |
| Czechia     | 2         | 2.6%    |
| Argentina   | 2         | 2.6%    |
| Uruguay     | 1         | 1.3%    |
| Turkey      | 1         | 1.3%    |
| Tunisia     | 1         | 1.3%    |
| Switzerland | 1         | 1.3%    |
| Slovakia    | 1         | 1.3%    |
| Philippines | 1         | 1.3%    |
| Norway      | 1         | 1.3%    |
| New Zealand | 1         | 1.3%    |
| Netherlands | 1         | 1.3%    |
| Mexico      | 1         | 1.3%    |
| Hong Kong   | 1         | 1.3%    |
| Finland     | 1         | 1.3%    |
| Canada      | 1         | 1.3%    |
| Belgium     | 1         | 1.3%    |
| Australia   | 1         | 1.3%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Minsk                  | 3         | 3.75%   |
| Sterling               | 2         | 2.5%    |
| Milan                  | 2         | 2.5%    |
| Guangzhou              | 2         | 2.5%    |
| Foshan                 | 2         | 2.5%    |
| Zacapu                 | 1         | 1.25%   |
| Winston-Salem          | 1         | 1.25%   |
| West Orange            | 1         | 1.25%   |
| Vantaa                 | 1         | 1.25%   |
| Tunis                  | 1         | 1.25%   |
| Trnava                 | 1         | 1.25%   |
| Taby                   | 1         | 1.25%   |
| Sydney                 | 1         | 1.25%   |
| Storsteinnes           | 1         | 1.25%   |
| Shenzhen               | 1         | 1.25%   |
| Santa Rosa             | 1         | 1.25%   |
| Sacramento             | 1         | 1.25%   |
| Ratingen               | 1         | 1.25%   |
| Québec                | 1         | 1.25%   |
| Punta Gorda            | 1         | 1.25%   |
| Pujaut                 | 1         | 1.25%   |
| Prague                 | 1         | 1.25%   |
| Perm                   | 1         | 1.25%   |
| Paris                  | 1         | 1.25%   |
| Orlando                | 1         | 1.25%   |
| Ocala                  | 1         | 1.25%   |
| Nuremberg              | 1         | 1.25%   |
| Novosibirsk            | 1         | 1.25%   |
| Nizhny Tagil           | 1         | 1.25%   |
| Nizhniy Novgorod       | 1         | 1.25%   |
| New York               | 1         | 1.25%   |
| Neath                  | 1         | 1.25%   |
| Motala                 | 1         | 1.25%   |
| Moscow                 | 1         | 1.25%   |
| Minden                 | 1         | 1.25%   |
| Milton Keynes          | 1         | 1.25%   |
| Marcoussis             | 1         | 1.25%   |
| London                 | 1         | 1.25%   |
| Lochristi              | 1         | 1.25%   |
| Lincoln                | 1         | 1.25%   |
| Leidschendam           | 1         | 1.25%   |
| Kulmbach               | 1         | 1.25%   |
| Kallithea              | 1         | 1.25%   |
| Kailua-Kona            | 1         | 1.25%   |
| Hyderabad              | 1         | 1.25%   |
| Huangpu                | 1         | 1.25%   |
| Houston                | 1         | 1.25%   |
| Gmina Lwówek Śląski | 1         | 1.25%   |
| Frick                  | 1         | 1.25%   |
| Erskine                | 1         | 1.25%   |
| Düsseldorf            | 1         | 1.25%   |
| Croydon                | 1         | 1.25%   |
| Córdoba               | 1         | 1.25%   |
| Cluj-Napoca            | 1         | 1.25%   |
| Cieszyn                | 1         | 1.25%   |
| Chicago                | 1         | 1.25%   |
| Chelyabinsk            | 1         | 1.25%   |
| Chattanooga            | 1         | 1.25%   |
| Cerritos               | 1         | 1.25%   |
| Central                | 1         | 1.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 20        | 23     | 20.2%   |
| Samsung Electronics | 19        | 23     | 19.19%  |
| SK hynix            | 12        | 12     | 12.12%  |
| Intel               | 10        | 13     | 10.1%   |
| Seagate             | 7         | 8      | 7.07%   |
| Micron Technology   | 5         | 5      | 5.05%   |
| Toshiba             | 4         | 6      | 4.04%   |
| SanDisk             | 4         | 5      | 4.04%   |
| Crucial             | 3         | 4      | 3.03%   |
| KIOXIA-EXCERIA      | 2         | 4      | 2.02%   |
| Kingston            | 2         | 2      | 2.02%   |
| HGST                | 2         | 2      | 2.02%   |
| XrayDisk            | 1         | 1      | 1.01%   |
| Unknown             | 1         | 3      | 1.01%   |
| Plextor             | 1         | 1      | 1.01%   |
| Phison              | 1         | 1      | 1.01%   |
| LITEON              | 1         | 1      | 1.01%   |
| KIOXIA              | 1         | 2      | 1.01%   |
| Hoodisk             | 1         | 1      | 1.01%   |
| Hitachi             | 1         | 1      | 1.01%   |
| A-DATA Technology   | 1         | 1      | 1.01%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel SSDPEKNW010T8 1TB                 | 3         | 2.97%   |
| Intel SSDPEKNU512GZ 512GB               | 3         | 2.97%   |
| WDC WDS100T2B0A-00SM50 1TB SSD          | 2         | 1.98%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB    | 2         | 1.98%   |
| Toshiba KXG6AZNV512G 512GB              | 2         | 1.98%   |
| SK hynix SKHynix_HFS512GDE9X081N 512GB  | 2         | 1.98%   |
| SK hynix PC711 NVMe 512GB               | 2         | 1.98%   |
| Samsung SSD 970 PRO 1TB                 | 2         | 1.98%   |
| Samsung MZVLB512HBJQ-000L2 512GB        | 2         | 1.98%   |
| HGST HTS721010A9E630 1TB                | 2         | 1.98%   |
| XrayDisk SSD 128GB                      | 1         | 0.99%   |
| WDC WDS500G3X0C-00SJG0 500GB            | 1         | 0.99%   |
| WDC WDS500G2B0C-00PXH0 500GB            | 1         | 0.99%   |
| WDC WDS250G2X0C-00L350 250GB            | 1         | 0.99%   |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 1         | 0.99%   |
| WDC WDS100T2B0C-00PXH0 1TB              | 1         | 0.99%   |
| WDC WD3200LPVX-22V0TT0 320GB            | 1         | 0.99%   |
| WDC WD2500BEVS-22UST0 250GB             | 1         | 0.99%   |
| WDC WD10SPZX-60Z10T0 1TB                | 1         | 0.99%   |
| WDC WD10SPSX-08A6W 1TB                  | 1         | 0.99%   |
| WDC WD10EZEX-08M2NA0 1TB                | 1         | 0.99%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB    | 1         | 0.99%   |
| WDC PC SN730 SDBPNTY-512G-1006 512GB    | 1         | 0.99%   |
| WDC PC SN730 SDBPNTY-1T00-1006 1TB      | 1         | 0.99%   |
| WDC PC SN530 SDBPMPZ-256G-1001 256GB    | 1         | 0.99%   |
| WDC PC SN520 SDAPNUW-512G-1014 512GB    | 1         | 0.99%   |
| WDC PC SN520 SDAPMUW-512G-1101 512GB    | 1         | 0.99%   |
| Unknown USB DISK 3.2 1TB                | 1         | 0.99%   |
| Toshiba MK6008GAH 64GB                  | 1         | 0.99%   |
| Toshiba KSG60ZMV512G M.2 2280 512GB SSD | 1         | 0.99%   |
| SK hynix SKHynix_HFS001TDE9X084N 1TB    | 1         | 0.99%   |
| SK hynix PC711 NVMe 1TB                 | 1         | 0.99%   |
| SK hynix PC611 NVMe 512GB               | 1         | 0.99%   |
| SK hynix HFS128G39MNC-3510A 128GB SSD   | 1         | 0.99%   |
| SK hynix HFM512GDHTNG-8710B 512GB       | 1         | 0.99%   |
| SK hynix HFM512GD3JX016N 512GB          | 1         | 0.99%   |
| SK hynix HFM001TD3JX013N 1TB            | 1         | 0.99%   |
| SK hynix BC711 NVMe 512GB               | 1         | 0.99%   |
| Seagate ST2000LX001-1RG174 2TB          | 1         | 0.99%   |
| Seagate ST1000LM049-2GH172 1TB          | 1         | 0.99%   |
| Seagate ST1000LM048-2E7172 1TB          | 1         | 0.99%   |
| Seagate ST1000LM035-1RK172 1TB          | 1         | 0.99%   |
| Seagate ST1000LM035-1RK1 1TB            | 1         | 0.99%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 1         | 0.99%   |
| Seagate FireCuda 530 ZP4000GM30013 4TB  | 1         | 0.99%   |
| SanDisk SDSSDH3 1T00 1TB                | 1         | 0.99%   |
| SanDisk SD9SN8W256G1002 256GB SSD       | 1         | 0.99%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD     | 1         | 0.99%   |
| SanDisk SD8TB8U256G1001 256GB SSD       | 1         | 0.99%   |
| Samsung SSD 980 PRO 500GB               | 1         | 0.99%   |
| Samsung SSD 980 PRO 2TB                 | 1         | 0.99%   |
| Samsung SSD 970 EVO Plus 1TB            | 1         | 0.99%   |
| Samsung SSD 970 EVO 500GB               | 1         | 0.99%   |
| Samsung SSD 970 EVO 1TB                 | 1         | 0.99%   |
| Samsung SSD 870 EVO 1TB                 | 1         | 0.99%   |
| Samsung SSD 860 EVO 250GB               | 1         | 0.99%   |
| Samsung SSD 850 EVO 250GB               | 1         | 0.99%   |
| Samsung PSSD T7 500GB                   | 1         | 0.99%   |
| Samsung PSSD T7 1TB                     | 1         | 0.99%   |
| Samsung MZVLW1T0HMLH-000L7 1TB          | 1         | 0.99%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 7      | 40%     |
| WDC     | 5         | 6      | 33.33%  |
| HGST    | 2         | 2      | 13.33%  |
| Toshiba | 1         | 2      | 6.67%   |
| Hitachi | 1         | 1      | 6.67%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 7      | 23.81%  |
| SanDisk             | 4         | 5      | 19.05%  |
| WDC                 | 3         | 4      | 14.29%  |
| Crucial             | 2         | 3      | 9.52%   |
| XrayDisk            | 1         | 1      | 4.76%   |
| Toshiba             | 1         | 1      | 4.76%   |
| SK hynix            | 1         | 1      | 4.76%   |
| Plextor             | 1         | 1      | 4.76%   |
| Intel               | 1         | 1      | 4.76%   |
| Hoodisk             | 1         | 1      | 4.76%   |
| A-DATA Technology   | 1         | 1      | 4.76%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 55        | 72     | 60.44%  |
| SSD     | 20        | 26     | 21.98%  |
| HDD     | 15        | 18     | 16.48%  |
| Unknown | 1         | 3      | 1.1%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 55        | 72     | 63.22%  |
| SATA | 30        | 42     | 34.48%  |
| SAS  | 2         | 5      | 2.3%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.51-1.0   | 18        | 21     | 50%     |
| 0.01-0.5   | 16        | 21     | 44.44%  |
| 1.01-2.0   | 2         | 2      | 5.56%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 24        | 31.17%  |
| 501-1000       | 15        | 19.48%  |
| 101-250        | 14        | 18.18%  |
| 1001-2000      | 9         | 11.69%  |
| 1-20           | 4         | 5.19%   |
| 2001-3000      | 3         | 3.9%    |
| Unknown        | 3         | 3.9%    |
| More than 3000 | 2         | 2.6%    |
| 21-50          | 2         | 2.6%    |
| 51-100         | 1         | 1.3%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 21        | 25.93%  |
| 101-250   | 14        | 17.28%  |
| 21-50     | 13        | 16.05%  |
| 251-500   | 11        | 13.58%  |
| 51-100    | 8         | 9.88%   |
| 501-1000  | 6         | 7.41%   |
| 1001-2000 | 5         | 6.17%   |
| Unknown   | 3         | 3.7%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WD10EZEX-08M2NA0 1TB           | 1         | 2      | 11.11%  |
| Toshiba MK6008GAH 64GB             | 1         | 2      | 11.11%  |
| Seagate ST1000LM049-2GH172 1TB     | 1         | 1      | 11.11%  |
| Seagate ST1000LM035-1RK172 1TB     | 1         | 2      | 11.11%  |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 11.11%  |
| Intel SSDPEKKF256G8L 256GB         | 1         | 1      | 11.11%  |
| HGST HTS721010A9E630 1TB           | 1         | 1      | 11.11%  |
| Crucial CT1000P1SSD8 1TB           | 1         | 1      | 11.11%  |
| A-DATA Technology SP550 240GB SSD  | 1         | 1      | 11.11%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 3         | 4      | 33.33%  |
| WDC               | 1         | 2      | 11.11%  |
| Toshiba           | 1         | 2      | 11.11%  |
| Intel             | 1         | 1      | 11.11%  |
| HGST              | 1         | 1      | 11.11%  |
| Crucial           | 1         | 1      | 11.11%  |
| A-DATA Technology | 1         | 1      | 11.11%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 4      | 50%     |
| WDC     | 1         | 2      | 16.67%  |
| Toshiba | 1         | 2      | 16.67%  |
| HGST    | 1         | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 6         | 9      | 66.67%  |
| NVMe | 2         | 2      | 22.22%  |
| SSD  | 1         | 1      | 11.11%  |

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
| Works    | 70        | 102    | 86.42%  |
| Malfunc  | 9         | 12     | 11.11%  |
| Detected | 2         | 5      | 2.47%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 41        | 37.96%  |
| Samsung Electronics          | 15        | 13.89%  |
| AMD                          | 13        | 12.04%  |
| SanDisk                      | 12        | 11.11%  |
| SK hynix                     | 11        | 10.19%  |
| Micron Technology            | 5         | 4.63%   |
| Toshiba America Info Systems | 3         | 2.78%   |
| KIOXIA                       | 2         | 1.85%   |
| Kingston Technology Company  | 2         | 1.85%   |
| Seagate Technology           | 1         | 0.93%   |
| Phison Electronics           | 1         | 0.93%   |
| Micron/Crucial Technology    | 1         | 0.93%   |
| Lite-On Technology           | 1         | 0.93%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 13        | 11.71%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 10        | 9.01%   |
| SK hynix Gold P31 SSD                                                          | 9         | 8.11%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 6         | 5.41%   |
| Micron Non-Volatile memory controller                                          | 5         | 4.5%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 4         | 3.6%    |
| Intel SSD 660P Series                                                          | 4         | 3.6%    |
| SanDisk Non-Volatile memory controller                                         | 3         | 2.7%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 2.7%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 2.7%    |
| Intel Volume Management Device NVMe RAID Controller                            | 3         | 2.7%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 3         | 2.7%    |
| Intel Non-Volatile memory controller                                           | 3         | 2.7%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 2.7%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 2.7%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 1.8%    |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 2         | 1.8%    |
| KIOXIA NVMe SSD                                                                | 2         | 1.8%    |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 2         | 1.8%    |
| Intel Comet Lake SATA AHCI Controller                                          | 2         | 1.8%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 1.8%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 2         | 1.8%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 2         | 1.8%    |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 1         | 0.9%    |
| SK hynix Non-Volatile memory controller                                        | 1         | 0.9%    |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 0.9%    |
| Seagate FireCuda 530 SSD                                                       | 1         | 0.9%    |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 1         | 0.9%    |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 1         | 0.9%    |
| SanDisk PC SN520 NVMe SSD                                                      | 1         | 0.9%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 0.9%    |
| Samsung NVMe SSD Controller 980                                                | 1         | 0.9%    |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 0.9%    |
| Micron/Crucial P1 NVMe PCIe SSD                                                | 1         | 0.9%    |
| Lite-On Non-Volatile memory controller                                         | 1         | 0.9%    |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 1         | 0.9%    |
| Kingston Company Company Non-Volatile memory controller                        | 1         | 0.9%    |
| Intel Tiger Lake-LP SATA Controller                                            | 1         | 0.9%    |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 1         | 0.9%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 1         | 0.9%    |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 1         | 0.9%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 1         | 0.9%    |
| AMD 300 Series Chipset SATA Controller                                         | 1         | 0.9%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 55        | 53.92%  |
| SATA | 41        | 40.2%   |
| RAID | 5         | 4.9%    |
| IDE  | 1         | 0.98%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 50        | 65.79%  |
| AMD    | 26        | 34.21%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8750H CPU @ 2.20GHz             | 4         | 5.26%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 4         | 5.26%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 3         | 3.95%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 3         | 3.95%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 3         | 3.95%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 2.63%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 2.63%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 2         | 2.63%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 2.63%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 2.63%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 2         | 2.63%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 2         | 2.63%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 2.63%   |
| AMD Ryzen 7 PRO 5850U with Radeon Graphics    | 2         | 2.63%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 2         | 2.63%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 2.63%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 2         | 2.63%   |
| Intel Core i9-9880H CPU @ 2.30GHz             | 1         | 1.32%   |
| Intel Core i9-8950HK CPU @ 2.90GHz            | 1         | 1.32%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 1.32%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 1.32%   |
| Intel Core i7-7820HK CPU @ 2.90GHz            | 1         | 1.32%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 1.32%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 1.32%   |
| Intel Core i7-10610U CPU @ 1.80GHz            | 1         | 1.32%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 1.32%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 1.32%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 1.32%   |
| Intel Core i5-4210M CPU @ 2.60GHz             | 1         | 1.32%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 1.32%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 1.32%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 1         | 1.32%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 1         | 1.32%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 1         | 1.32%   |
| Intel Core i3-4000M CPU @ 2.40GHz             | 1         | 1.32%   |
| Intel Core Duo CPU U2500 @ 1.20GHz            | 1         | 1.32%   |
| Intel Atom CPU N280 @ 1.66GHz                 | 1         | 1.32%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 1         | 1.32%   |
| Intel 11th Gen Core i7-11850H @ 2.50GHz       | 1         | 1.32%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1         | 1.32%   |
| Intel 11th Gen Core i7-11390H @ 3.40GHz       | 1         | 1.32%   |
| Intel 11th Gen Core i7-11370H @ 3.30GHz       | 1         | 1.32%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 1         | 1.32%   |
| AMD Ryzen 9 6900HS with Radeon Graphics       | 1         | 1.32%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 1         | 1.32%   |
| AMD Ryzen 7 5800HS with Radeon Graphics       | 1         | 1.32%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 1         | 1.32%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 1         | 1.32%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 1         | 1.32%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 1.32%   |
| AMD Ryzen 5 1500X Quad-Core Processor         | 1         | 1.32%   |
| AMD E1-1200 APU with Radeon HD Graphics       | 1         | 1.32%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model           | Notebooks | Percent |
|-----------------|-----------|---------|
| Intel Core i7   | 20        | 26.32%  |
| Intel Core i5   | 14        | 18.42%  |
| AMD Ryzen 7     | 12        | 15.79%  |
| Other           | 10        | 13.16%  |
| AMD Ryzen 9     | 4         | 5.26%   |
| AMD Ryzen 5     | 4         | 5.26%   |
| AMD Ryzen 7 PRO | 3         | 3.95%   |
| Intel Core i9   | 2         | 2.63%   |
| Intel Core i3   | 2         | 2.63%   |
| AMD Ryzen 3     | 2         | 2.63%   |
| Intel Core Duo  | 1         | 1.32%   |
| Intel Atom      | 1         | 1.32%   |
| AMD E1          | 1         | 1.32%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 28        | 36.84%  |
| 8      | 23        | 30.26%  |
| 2      | 13        | 17.11%  |
| 6      | 11        | 14.47%  |
| 1      | 1         | 1.32%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 76        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 72        | 94.74%  |
| 1      | 4         | 5.26%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 74        | 97.37%  |
| 32-bit         | 2         | 2.63%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x906ea    | 11        | 14.29%  |
| 0x0a50000c | 10        | 12.99%  |
| 0x806ec    | 6         | 7.79%   |
| Unknown    | 6         | 7.79%   |
| 0x806d1    | 5         | 6.49%   |
| 0x08108109 | 4         | 5.19%   |
| 0x806c1    | 3         | 3.9%    |
| 0x306d4    | 3         | 3.9%    |
| 0x08608103 | 3         | 3.9%    |
| 0xa0652    | 2         | 2.6%    |
| 0x706e5    | 2         | 2.6%    |
| 0x506e3    | 2         | 2.6%    |
| 0x306c3    | 2         | 2.6%    |
| 0x206a7    | 2         | 2.6%    |
| 0x08600103 | 2         | 2.6%    |
| 0x906ed    | 1         | 1.3%    |
| 0x906e9    | 1         | 1.3%    |
| 0x806ea    | 1         | 1.3%    |
| 0x806c2    | 1         | 1.3%    |
| 0x6ec      | 1         | 1.3%    |
| 0x406e3    | 1         | 1.3%    |
| 0x306a9    | 1         | 1.3%    |
| 0x0a404101 | 1         | 1.3%    |
| 0x08608102 | 1         | 1.3%    |
| 0x08600106 | 1         | 1.3%    |
| 0x08600102 | 1         | 1.3%    |
| 0x08108102 | 1         | 1.3%    |
| 0x08001105 | 1         | 1.3%    |
| 0x05000119 | 1         | 1.3%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 22        | 28.57%  |
| Zen 3       | 10        | 12.99%  |
| IceLake     | 8         | 10.39%  |
| Unknown     | 6         | 7.79%   |
| Zen+        | 5         | 6.49%   |
| TigerLake   | 5         | 6.49%   |
| Zen 2       | 4         | 5.19%   |
| Skylake     | 3         | 3.9%    |
| Broadwell   | 3         | 3.9%    |
| SandyBridge | 2         | 2.6%    |
| Haswell     | 2         | 2.6%    |
| CometLake   | 2         | 2.6%    |
| Zen         | 1         | 1.3%    |
| P6          | 1         | 1.3%    |
| IvyBridge   | 1         | 1.3%    |
| Bonnell     | 1         | 1.3%    |
| Bobcat      | 1         | 1.3%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 46        | 42.99%  |
| Nvidia | 35        | 32.71%  |
| AMD    | 26        | 24.3%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 10        | 8.7%    |
| AMD Cezanne                                                                   | 10        | 8.7%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 5         | 4.35%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 5         | 4.35%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 5         | 4.35%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 5         | 4.35%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 5         | 4.35%   |
| AMD Lucienne                                                                  | 4         | 3.48%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 3         | 2.61%   |
| Nvidia GP108M [GeForce MX250]                                                 | 3         | 2.61%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                       | 3         | 2.61%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                    | 3         | 2.61%   |
| Intel HD Graphics 5500                                                        | 3         | 2.61%   |
| AMD Renoir                                                                    | 3         | 2.61%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 2         | 1.74%   |
| Intel UHD Graphics 620                                                        | 2         | 1.74%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 2         | 1.74%   |
| Intel Iris Plus Graphics G7                                                   | 2         | 1.74%   |
| Intel HD Graphics 630                                                         | 2         | 1.74%   |
| Intel HD Graphics 530                                                         | 2         | 1.74%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 2         | 1.74%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 2         | 1.74%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                          | 2         | 1.74%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                    | 1         | 0.87%   |
| Nvidia TU117GLM [T600 Mobile]                                                 | 1         | 0.87%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                 | 1         | 0.87%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                       | 1         | 0.87%   |
| Nvidia TU104GLM [Quadro RTX 5000 Mobile / Max-Q]                              | 1         | 0.87%   |
| Nvidia TU104GLM [Quadro RTX 4000 Mobile / Max-Q]                              | 1         | 0.87%   |
| Nvidia GP108M [GeForce MX330]                                                 | 1         | 0.87%   |
| Nvidia GP107M [GeForce MX350]                                                 | 1         | 0.87%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                           | 1         | 0.87%   |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                                       | 1         | 0.87%   |
| Nvidia GP104BM [GeForce GTX 1080 Mobile]                                      | 1         | 0.87%   |
| Nvidia GM108M [GeForce 940M]                                                  | 1         | 0.87%   |
| Nvidia GM108M [GeForce 940MX]                                                 | 1         | 0.87%   |
| Nvidia GK208BM [GeForce 920M]                                                 | 1         | 0.87%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                       | 1         | 0.87%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                               | 1         | 0.87%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 1         | 0.87%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 1         | 0.87%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 1         | 0.87%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 1         | 0.87%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 1         | 0.87%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 1         | 0.87%   |
| AMD Wrestler [Radeon HD 7310]                                                 | 1         | 0.87%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                      | 1         | 0.87%   |
| AMD Rembrandt [Radeon 680M]                                                   | 1         | 0.87%   |
| AMD Navi 23 [Radeon RX 6650 XT]                                               | 1         | 0.87%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                    | 1         | 0.87%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                | 1         | 0.87%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                       | 1         | 0.87%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                  | 1         | 0.87%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Intel + Nvidia | 26        | 34.21%  |
| 1 x Intel      | 17        | 22.37%  |
| 1 x AMD        | 15        | 19.74%  |
| 2 x AMD        | 6         | 7.89%   |
| 1 x Nvidia     | 5         | 6.58%   |
| AMD + Nvidia   | 4         | 5.26%   |
| 2 x Intel      | 2         | 2.63%   |
| Intel + AMD    | 1         | 1.32%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 51        | 67.11%  |
| Proprietary | 24        | 31.58%  |
| Unknown     | 1         | 1.32%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 37        | 47.44%  |
| 1.01-2.0   | 9         | 11.54%  |
| 3.01-4.0   | 8         | 10.26%  |
| 0.01-0.5   | 7         | 8.97%   |
| 0.51-1.0   | 5         | 6.41%   |
| 7.01-8.0   | 4         | 5.13%   |
| 5.01-6.0   | 3         | 3.85%   |
| 8.01-16.0  | 3         | 3.85%   |
| 2.01-3.0   | 2         | 2.56%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| BOE                 | 21        | 22.83%  |
| AU Optronics        | 15        | 16.3%   |
| Chimei Innolux      | 11        | 11.96%  |
| Samsung Electronics | 10        | 10.87%  |
| Sharp               | 7         | 7.61%   |
| LG Display          | 7         | 7.61%   |
| Goldstar            | 3         | 3.26%   |
| Lenovo              | 2         | 2.17%   |
| Hewlett-Packard     | 2         | 2.17%   |
| CSO                 | 2         | 2.17%   |
| BenQ                | 2         | 2.17%   |
| ASUSTek Computer    | 2         | 2.17%   |
| Xiaomi              | 1         | 1.09%   |
| ViewSonic           | 1         | 1.09%   |
| PANDA               | 1         | 1.09%   |
| MSI                 | 1         | 1.09%   |
| InfoVision          | 1         | 1.09%   |
| HannStar            | 1         | 1.09%   |
| Dell                | 1         | 1.09%   |
| AOC                 | 1         | 1.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                | 2         | 2.17%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch           | 2         | 2.17%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch        | 2         | 2.17%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch       | 2         | 2.17%   |
| BOE LCD Monitor BOE0973 2560x1440 344x194mm 15.5-inch                  | 2         | 2.17%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                  | 2         | 2.17%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch         | 2         | 2.17%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch         | 2         | 2.17%   |
| Xiaomi Mi TV XMD0002 1920x1080 708x398mm 32.0-inch                     | 1         | 1.09%   |
| ViewSonic LCD Monitor VSC1B35 1920x1080 530x300mm 24.0-inch            | 1         | 1.09%   |
| Sharp LQ140M1JW49 SHP1523 1920x1080 309x174mm 14.0-inch                | 1         | 1.09%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch                | 1         | 1.09%   |
| Sharp LCD Monitor SHP1515 1920x1200 336x210mm 15.6-inch                | 1         | 1.09%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                | 1         | 1.09%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch   | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SEC3157 1280x800 303x190mm 14.1-inch   | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch   | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch  | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch   | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SDC4752 1366x768 344x194mm 15.5-inch   | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SDC415F 3840x2160 344x194mm 15.5-inch  | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SDC415D 3840x2400 344x215mm 16.0-inch  | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SAM07C5 1920x1080 1020x570mm 46.0-inch | 1         | 1.09%   |
| Samsung Electronics C27F591 SAM0D37 1920x1080 598x336mm 27.0-inch      | 1         | 1.09%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch                | 1         | 1.09%   |
| MSI MAG272QP MSI3CA8 2560x1440 597x336mm 27.0-inch                     | 1         | 1.09%   |
| LG Display LCD Monitor LGD05E4 1920x1080 344x194mm 15.5-inch           | 1         | 1.09%   |
| LG Display LCD Monitor LGD05BE 1920x1080 382x215mm 17.3-inch           | 1         | 1.09%   |
| LG Display LCD Monitor LGD0532 1920x1080 344x194mm 15.5-inch           | 1         | 1.09%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch           | 1         | 1.09%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch            | 1         | 1.09%   |
| Lenovo Q27q-10 LEN65F4 2560x1440 597x336mm 27.0-inch                   | 1         | 1.09%   |
| Lenovo LEN T34w-20 LEN61F3 3440x1440 800x330mm 34.1-inch               | 1         | 1.09%   |
| InfoVision LCD Monitor IVO8C78 1920x1080 309x174mm 14.0-inch           | 1         | 1.09%   |
| Hewlett-Packard E273q HPN3473 2560x1440 597x336mm 27.0-inch            | 1         | 1.09%   |
| Hewlett-Packard E232 HWP327A 1920x1080 509x286mm 23.0-inch             | 1         | 1.09%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch               | 1         | 1.09%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                  | 1         | 1.09%   |
| Goldstar E1942 GSM4C09 1366x768 410x230mm 18.5-inch                    | 1         | 1.09%   |
| Goldstar 23EA53 GSM59A9 1920x1080 510x290mm 23.1-inch                  | 1         | 1.09%   |
| Dell E170S DELA04A 1280x1024 338x270mm 17.0-inch                       | 1         | 1.09%   |
| CSO LCD Monitor CSO1609 2560x1600 345x215mm 16.0-inch                  | 1         | 1.09%   |
| CSO LCD Monitor CSO1402 2880x1800 302x188mm 14.0-inch                  | 1         | 1.09%   |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 381x214mm 17.2-inch       | 1         | 1.09%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch        | 1         | 1.09%   |
| Chimei Innolux LCD Monitor CMN152E 1920x1080 344x193mm 15.5-inch       | 1         | 1.09%   |
| Chimei Innolux LCD Monitor CMN14F5 1920x1080 309x173mm 13.9-inch       | 1         | 1.09%   |
| Chimei Innolux LCD Monitor CMN14E7 1920x1080 309x173mm 13.9-inch       | 1         | 1.09%   |
| Chimei Innolux LCD Monitor CMN14D3 1920x1080 309x173mm 13.9-inch       | 1         | 1.09%   |
| Chimei Innolux LCD Monitor CMN140A 1920x1080 309x173mm 13.9-inch       | 1         | 1.09%   |
| BOE LCD Monitor BOE0A1D 2560x1600 302x189mm 14.0-inch                  | 1         | 1.09%   |
| BOE LCD Monitor BOE09E5 2560x1440 355x200mm 16.0-inch                  | 1         | 1.09%   |
| BOE LCD Monitor BOE09DE 1920x1080 309x174mm 14.0-inch                  | 1         | 1.09%   |
| BOE LCD Monitor BOE09B6 2560x1600 345x215mm 16.0-inch                  | 1         | 1.09%   |
| BOE LCD Monitor BOE0928 1920x1080 344x194mm 15.5-inch                  | 1         | 1.09%   |
| BOE LCD Monitor BOE0910 1920x1080 344x194mm 15.5-inch                  | 1         | 1.09%   |
| BOE LCD Monitor BOE0900 1920x1080 344x194mm 15.5-inch                  | 1         | 1.09%   |
| BOE LCD Monitor BOE08E2 1920x1080 344x194mm 15.5-inch                  | 1         | 1.09%   |
| BOE LCD Monitor BOE0898 1920x1080 294x165mm 13.3-inch                  | 1         | 1.09%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 48        | 56.47%  |
| 2560x1440 (QHD)   | 8         | 9.41%   |
| 1366x768 (WXGA)   | 8         | 9.41%   |
| 3840x2160 (4K)    | 6         | 7.06%   |
| 2560x1600         | 3         | 3.53%   |
| 3840x2400         | 2         | 2.35%   |
| 3440x1440         | 2         | 2.35%   |
| 2256x1504         | 2         | 2.35%   |
| 2880x1800         | 1         | 1.18%   |
| 1920x1200 (WUXGA) | 1         | 1.18%   |
| 1600x900 (HD+)    | 1         | 1.18%   |
| 1440x900 (WXGA+)  | 1         | 1.18%   |
| 1280x1024 (SXGA)  | 1         | 1.18%   |
| 1024x600          | 1         | 1.18%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 40        | 44.44%  |
| 14     | 12        | 13.33%  |
| 13     | 11        | 12.22%  |
| 27     | 6         | 6.67%   |
| 17     | 6         | 6.67%   |
| 16     | 4         | 4.44%   |
| 34     | 2         | 2.22%   |
| 23     | 2         | 2.22%   |
| 65     | 1         | 1.11%   |
| 54     | 1         | 1.11%   |
| 25     | 1         | 1.11%   |
| 24     | 1         | 1.11%   |
| 18     | 1         | 1.11%   |
| 12     | 1         | 1.11%   |
| 10     | 1         | 1.11%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 62        | 70.45%  |
| 501-600     | 9         | 10.23%  |
| 351-400     | 6         | 6.82%   |
| 201-300     | 6         | 6.82%   |
| 701-800     | 2         | 2.27%   |
| 1001-1500   | 2         | 2.27%   |
| 401-500     | 1         | 1.14%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 66        | 83.54%  |
| 16/10 | 8         | 10.13%  |
| 3/2   | 2         | 2.53%   |
| 21/9  | 2         | 2.53%   |
| 5/4   | 1         | 1.27%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 40        | 44.44%  |
| 81-90          | 21        | 23.33%  |
| 301-350        | 6         | 6.67%   |
| 121-130        | 5         | 5.56%   |
| 111-120        | 4         | 4.44%   |
| 201-250        | 3         | 3.33%   |
| More than 1000 | 2         | 2.22%   |
| 71-80          | 2         | 2.22%   |
| 351-500        | 2         | 2.22%   |
| 141-150        | 2         | 2.22%   |
| 61-70          | 1         | 1.11%   |
| 41-50          | 1         | 1.11%   |
| 251-300        | 1         | 1.11%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 47        | 52.81%  |
| 101-120       | 14        | 15.73%  |
| 161-240       | 10        | 11.24%  |
| More than 240 | 8         | 8.99%   |
| 51-100        | 8         | 8.99%   |
| 1-50          | 2         | 2.25%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 62        | 80.52%  |
| 2     | 11        | 14.29%  |
| 3     | 3         | 3.9%    |
| 0     | 1         | 1.3%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 53        | 47.32%  |
| Realtek Semiconductor             | 35        | 31.25%  |
| Qualcomm Atheros                  | 7         | 6.25%   |
| MediaTek                          | 5         | 4.46%   |
| Samsung Electronics               | 2         | 1.79%   |
| Broadcom                          | 2         | 1.79%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.89%   |
| Lenovo                            | 1         | 0.89%   |
| ICS Advent                        | 1         | 0.89%   |
| Ericsson Business Mobile Networks | 1         | 0.89%   |
| D-Link                            | 1         | 0.89%   |
| Broadcom Limited                  | 1         | 0.89%   |
| ASIX Electronics                  | 1         | 0.89%   |
| Aquantia                          | 1         | 0.89%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 25        | 18.52%  |
| Intel Wi-Fi 6 AX200                                               | 11        | 8.15%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 7         | 5.19%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 5         | 3.7%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 4         | 2.96%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 4         | 2.96%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 4         | 2.96%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 4         | 2.96%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 2.22%   |
| Intel Wireless 8265 / 8275                                        | 3         | 2.22%   |
| Intel Wireless 8260                                               | 3         | 2.22%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 2.22%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 3         | 2.22%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.48%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 1.48%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1.48%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 1.48%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 1.48%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 1.48%   |
| ZTE WCDMA MSM ZTE MSM                                             | 1         | 0.74%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.74%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.74%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1         | 0.74%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.74%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.74%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 0.74%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 1         | 0.74%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.74%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.74%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 0.74%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.74%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.74%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 0.74%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 0.74%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.74%   |
| MediaTek WLAN controller                                          | 1         | 0.74%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 0.74%   |
| Intel Wireless-AC 9260                                            | 1         | 0.74%   |
| Intel Wireless 7265                                               | 1         | 0.74%   |
| Intel Wireless 3160                                               | 1         | 0.74%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 1         | 0.74%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.74%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.74%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.74%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.74%   |
| Intel Ethernet Connection (5) I219-V                              | 1         | 0.74%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.74%   |
| Intel Ethernet Connection (14) I219-V                             | 1         | 0.74%   |
| Intel Ethernet Connection (14) I219-LM                            | 1         | 0.74%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 0.74%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 0.74%   |
| Intel Centrino Ultimate-N 6300                                    | 1         | 0.74%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 1         | 0.74%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 1         | 0.74%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.74%   |
| ICS Advent DM9601 Fast Ethernet Adapter                           | 1         | 0.74%   |
| Ericsson Business Mobile Networks F5521gw                         | 1         | 0.74%   |
| D-Link 802.11 n WLAN                                              | 1         | 0.74%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1         | 0.74%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 1         | 0.74%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 52        | 67.53%  |
| Realtek Semiconductor | 14        | 18.18%  |
| MediaTek              | 5         | 6.49%   |
| Qualcomm Atheros      | 3         | 3.9%    |
| D-Link                | 1         | 1.3%    |
| Broadcom Limited      | 1         | 1.3%    |
| Broadcom              | 1         | 1.3%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 11        | 14.29%  |
| Intel Cannon Lake PCH CNVi WiFi                                | 7         | 9.09%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 5         | 6.49%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 4         | 5.19%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 4         | 5.19%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 4         | 5.19%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 4         | 5.19%   |
| Intel Wireless 8265 / 8275                                     | 3         | 3.9%    |
| Intel Wireless 8260                                            | 3         | 3.9%    |
| Intel Wi-Fi 6 AX201                                            | 3         | 3.9%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 3         | 3.9%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2         | 2.6%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 2         | 2.6%    |
| Intel Comet Lake PCH CNVi WiFi                                 | 2         | 2.6%    |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1         | 1.3%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 1.3%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.3%    |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 1.3%    |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 1         | 1.3%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 1.3%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 1.3%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 1.3%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 1.3%    |
| MediaTek WLAN controller                                       | 1         | 1.3%    |
| Intel Wireless-AC 9260                                         | 1         | 1.3%    |
| Intel Wireless 7265                                            | 1         | 1.3%    |
| Intel Wireless 3160                                            | 1         | 1.3%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 1         | 1.3%    |
| Intel Centrino Ultimate-N 6300                                 | 1         | 1.3%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 1         | 1.3%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 1.3%    |
| D-Link 802.11 n WLAN                                           | 1         | 1.3%    |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 1         | 1.3%    |
| Broadcom BCM43142 802.11b/g/n                                  | 1         | 1.3%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 31        | 54.39%  |
| Intel                      | 13        | 22.81%  |
| Qualcomm Atheros           | 5         | 8.77%   |
| Samsung Electronics        | 2         | 3.51%   |
| ZTE WCDMA Technologies MSM | 1         | 1.75%   |
| Lenovo                     | 1         | 1.75%   |
| ICS Advent                 | 1         | 1.75%   |
| Broadcom                   | 1         | 1.75%   |
| ASIX Electronics           | 1         | 1.75%   |
| Aquantia                   | 1         | 1.75%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 25        | 43.86%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 5.26%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 3.51%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 3.51%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 3.51%   |
| ZTE WCDMA MSM ZTE MSM                                             | 1         | 1.75%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 1.75%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.75%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 1.75%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.75%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.75%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.75%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 1.75%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.75%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.75%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 1.75%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.75%   |
| Intel Ethernet Connection (5) I219-V                              | 1         | 1.75%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.75%   |
| Intel Ethernet Connection (14) I219-V                             | 1         | 1.75%   |
| Intel Ethernet Connection (14) I219-LM                            | 1         | 1.75%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 1.75%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 1.75%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 1.75%   |
| ICS Advent DM9601 Fast Ethernet Adapter                           | 1         | 1.75%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1         | 1.75%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 1.75%   |
| Aquantia 5G USB Ethernet Adapter                                  | 1         | 1.75%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 76        | 58.46%  |
| Ethernet | 53        | 40.77%  |
| Modem    | 1         | 0.77%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 63        | 79.75%  |
| Ethernet | 16        | 20.25%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 45        | 59.21%  |
| 1     | 29        | 38.16%  |
| 3     | 2         | 2.63%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 62        | 77.5%   |
| Yes  | 18        | 22.5%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 46        | 66.67%  |
| Realtek Semiconductor | 11        | 15.94%  |
| IMC Networks          | 5         | 7.25%   |
| Toshiba               | 1         | 1.45%   |
| Hewlett-Packard       | 1         | 1.45%   |
| Foxconn International | 1         | 1.45%   |
| Foxconn / Hon Hai     | 1         | 1.45%   |
| Broadcom              | 1         | 1.45%   |
| ASUSTek Computer      | 1         | 1.45%   |
| Apple                 | 1         | 1.45%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                             | 13        | 18.84%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)    | 11        | 15.94%  |
| Intel AX200 Bluetooth                             | 10        | 14.49%  |
| Realtek Bluetooth Radio                           | 7         | 10.14%  |
| Intel Bluetooth wireless interface                | 7         | 10.14%  |
| Intel AX210 Bluetooth                             | 4         | 5.8%    |
| IMC Networks Wireless_Device                      | 4         | 5.8%    |
| Realtek  Bluetooth 4.2 Adapter                    | 2         | 2.9%    |
| Toshiba RT Bluetooth Radio                        | 1         | 1.45%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter           | 1         | 1.45%   |
| Realtek RTL8723B Bluetooth                        | 1         | 1.45%   |
| Intel Bluetooth Device                            | 1         | 1.45%   |
| IMC Networks Bluetooth Device                     | 1         | 1.45%   |
| HP Broadcom 2070 Bluetooth Combo                  | 1         | 1.45%   |
| Foxconn International BCM43142A0 Bluetooth module | 1         | 1.45%   |
| Foxconn / Hon Hai Wireless_Device                 | 1         | 1.45%   |
| Broadcom HP Portable SoftSailing                  | 1         | 1.45%   |
| ASUS Broadcom Bluetooth 2.1                       | 1         | 1.45%   |
| Apple Bluetooth USB Host Controller               | 1         | 1.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 50        | 48.54%  |
| AMD                                  | 27        | 26.21%  |
| Nvidia                               | 20        | 19.42%  |
| Thesycon Systemsoftware & Consulting | 1         | 0.97%   |
| Razer USA                            | 1         | 0.97%   |
| Lenovo                               | 1         | 0.97%   |
| Kingston Technology                  | 1         | 0.97%   |
| Hewlett-Packard                      | 1         | 0.97%   |
| ACTIONS                              | 1         | 0.97%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 24        | 17.39%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 16        | 11.59%  |
| Intel Cannon Lake PCH cAVS                                                 | 12        | 8.7%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 5         | 3.62%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 5         | 3.62%   |
| Intel Comet Lake PCH-LP cAVS                                               | 5         | 3.62%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5         | 3.62%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4         | 2.9%    |
| Nvidia GP106 High Definition Audio Controller                              | 4         | 2.9%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 4         | 2.9%    |
| Nvidia GP107GL High Definition Audio Controller                            | 3         | 2.17%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 2.17%   |
| Intel Sunrise Point-LP HD Audio                                            | 3         | 2.17%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 3         | 2.17%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 2.17%   |
| Nvidia TU104 HD Audio Controller                                           | 2         | 1.45%   |
| Nvidia GP104 High Definition Audio Controller                              | 2         | 1.45%   |
| Nvidia GA106 High Definition Audio Controller                              | 2         | 1.45%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 1.45%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 1.45%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 1.45%   |
| Intel CM238 HD Audio Controller                                            | 2         | 1.45%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2         | 1.45%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 1.45%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 1.45%   |
| AMD Navi 10 HDMI Audio                                                     | 2         | 1.45%   |
| Thesycon Systemsoftware & Consulting DX3 Pro                               | 1         | 0.72%   |
| Razer USA Razer Kraken X USB                                               | 1         | 0.72%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.72%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 0.72%   |
| Nvidia Audio device                                                        | 1         | 0.72%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                               | 1         | 0.72%   |
| Kingston Technology HyperX 7.1 Audio                                       | 1         | 0.72%   |
| Intel USB PnP Sound Device                                                 | 1         | 0.72%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 0.72%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1         | 0.72%   |
| Hewlett-Packard USB Audio                                                  | 1         | 0.72%   |
| AMD Wrestler HDMI Audio                                                    | 1         | 0.72%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 1         | 0.72%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 1         | 0.72%   |
| AMD FCH Azalia Controller                                                  | 1         | 0.72%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1         | 0.72%   |
| ACTIONS EDIFIER M380                                                       | 1         | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 38        | 44.71%  |
| SK hynix            | 17        | 20%     |
| Micron Technology   | 10        | 11.76%  |
| Kingston            | 7         | 8.24%   |
| Crucial             | 4         | 4.71%   |
| A-DATA Technology   | 2         | 2.35%   |
| Unknown             | 1         | 1.18%   |
| Ramaxel Technology  | 1         | 1.18%   |
| Patriot             | 1         | 1.18%   |
| Magnum Tech         | 1         | 1.18%   |
| G.Skill             | 1         | 1.18%   |
| Corsair             | 1         | 1.18%   |
| Unknown             | 1         | 1.18%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 4.55%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 4         | 4.55%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 3         | 3.41%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 3.41%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 3.41%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 2.27%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 2.27%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 2.27%   |
| SK hynix RAM H9HCNNNCPMALHR-NEE 8GB Row Of Chips LPDDR4 4800MT/s | 2         | 2.27%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 2.27%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 2.27%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 2         | 2.27%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 2         | 2.27%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 2.27%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 2.27%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 2         | 2.27%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 2         | 2.27%   |
| Unknown RAM Module 1GB SODIMM SDRAM                              | 1         | 1.14%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.14%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s          | 1         | 1.14%   |
| SK hynix RAM HMAA2GS6AJR8N-XN 16384MB SODIMM DDR4 3200MT/s       | 1         | 1.14%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 1         | 1.14%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.14%   |
| Samsung RAM Module 8GB SODIMM DDR3 1333MT/s                      | 1         | 1.14%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 2133MT/s              | 1         | 1.14%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                     | 1         | 1.14%   |
| Samsung RAM M471B5773CHS-CK0 2GB SODIMM DDR3 1600MT/s            | 1         | 1.14%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.14%   |
| Samsung RAM M471A5244CB0-CWE 4096MB Row Of Chips DDR4 3200MT/s   | 1         | 1.14%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.14%   |
| Samsung RAM M471A2G43BB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.14%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.14%   |
| Samsung RAM M471A1K43EB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 1         | 1.14%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM 4800MT/s               | 1         | 1.14%   |
| Samsung RAM M425R1GB4BB0-CQKOD 8GB SODIMM 4800MT/s               | 1         | 1.14%   |
| Samsung RAM K4E6E304EB-EGCG 4096MB Row Of Chips LPDDR3 2133MT/s  | 1         | 1.14%   |
| Samsung RAM K4A8G165WC-BCTD 4GB SODIMM DDR4 2667MT/s             | 1         | 1.14%   |
| Ramaxel RAM RMT3170MN68F9F1600 4GB SODIMM DDR3 1600MT/s          | 1         | 1.14%   |
| Patriot RAM PSD416G24002S 16GB SODIMM DDR4 2667MT/s              | 1         | 1.14%   |
| Micron RAM Module 16GB SODIMM DDR4 3200MT/s                      | 1         | 1.14%   |
| Micron RAM Module 16GB SODIMM DDR4 2667MT/s                      | 1         | 1.14%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 1         | 1.14%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16384MB SODIMM DDR4 3200MT/s         | 1         | 1.14%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 1         | 1.14%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 1         | 1.14%   |
| Micron RAM 16ATF2G64HZ-3G2J1 16GB SODIMM DDR4 3200MT/s           | 1         | 1.14%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s           | 1         | 1.14%   |
| Magnum Tech RAM MAGNUMTECH 4GB SODIMM DDR3 1600MT/s              | 1         | 1.14%   |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s          | 1         | 1.14%   |
| Kingston RAM KF3200C20S4/32GX 32GB SODIMM DDR4 3200MT/s          | 1         | 1.14%   |
| Kingston RAM HP26D4S9S8ME-8 8GB SODIMM DDR4 2667MT/s             | 1         | 1.14%   |
| Kingston RAM HP26D4S9S8HJ-8 8GB SODIMM DDR4 2667MT/s             | 1         | 1.14%   |
| Kingston RAM 99U5624-013.A00G 8GB SODIMM DDR4 2400MT/s           | 1         | 1.14%   |
| Kingston RAM 99U5428-063.A00LF 8GB SODIMM DDR3 1600MT/s          | 1         | 1.14%   |
| Kingston RAM 9905700-053.A00G 8GB SODIMM DDR4 3200MT/s           | 1         | 1.14%   |
| G.Skill RAM F4-3200C 8GB SODIMM DDR4 1067MT/s                    | 1         | 1.14%   |
| Crucial RAM CT8G4SFS8266.M8FE 8GB SODIMM DDR4 2667MT/s           | 1         | 1.14%   |
| Crucial RAM CT8G4SFRA32A.M8FRS 8GB SODIMM DDR4 3200MT/s          | 1         | 1.14%   |
| Crucial RAM CT8G4SFRA32A.C8FR 8GB SODIMM DDR4 3200MT/s           | 1         | 1.14%   |
| Crucial RAM CT32G4SFD832A.C16FE 32GB SODIMM DDR4 3200MT/s        | 1         | 1.14%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 58        | 77.33%  |
| DDR3    | 10        | 13.33%  |
| LPDDR4  | 2         | 2.67%   |
| LPDDR3  | 2         | 2.67%   |
| SDRAM   | 1         | 1.33%   |
| DDR     | 1         | 1.33%   |
| Unknown | 1         | 1.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 69        | 89.61%  |
| Row Of Chips | 7         | 9.09%   |
| Chip         | 1         | 1.3%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 44        | 56.41%  |
| 16384 | 18        | 23.08%  |
| 4096  | 8         | 10.26%  |
| 32768 | 4         | 5.13%   |
| 2048  | 2         | 2.56%   |
| 1024  | 1         | 1.28%   |
| 512   | 1         | 1.28%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 31        | 39.24%  |
| 2667    | 25        | 31.65%  |
| 1600    | 8         | 10.13%  |
| 4800    | 3         | 3.8%    |
| 8400    | 2         | 2.53%   |
| 2400    | 2         | 2.53%   |
| 2133    | 2         | 2.53%   |
| 2933    | 1         | 1.27%   |
| 1333    | 1         | 1.27%   |
| 1067    | 1         | 1.27%   |
| 667     | 1         | 1.27%   |
| 533     | 1         | 1.27%   |
| Unknown | 1         | 1.27%   |

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
| IMC Networks                           | 14        | 22.58%  |
| Chicony Electronics                    | 13        | 20.97%  |
| Acer                                   | 7         | 11.29%  |
| Realtek Semiconductor                  | 5         | 8.06%   |
| Lite-On Technology                     | 5         | 8.06%   |
| Microdia                               | 4         | 6.45%   |
| Syntek                                 | 3         | 4.84%   |
| Sunplus Innovation Technology          | 3         | 4.84%   |
| Quanta                                 | 3         | 4.84%   |
| Luxvisions Innotech Limited            | 3         | 4.84%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.61%   |
| Alcor Micro                            | 1         | 1.61%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                               | 8         | 12.9%   |
| Chicony Integrated Camera                                    | 5         | 8.06%   |
| Microdia Integrated_Webcam_HD                                | 4         | 6.45%   |
| IMC Networks USB2.0 HD UVC WebCam                            | 4         | 6.45%   |
| Acer Integrated Camera                                       | 4         | 6.45%   |
| Syntek Integrated Camera                                     | 2         | 3.23%   |
| Sunplus Integrated_Webcam_HD                                 | 2         | 3.23%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera          | 2         | 3.23%   |
| Lite-On HP Wide Vision HD Camera                             | 2         | 3.23%   |
| Chicony HD User Facing                                       | 2         | 3.23%   |
| Acer NEC HD WebCam                                           | 2         | 3.23%   |
| Syntek Lenovo EasyCamera                                     | 1         | 1.61%   |
| Sunplus HP Wide Vision HD                                    | 1         | 1.61%   |
| Realtek USB Camera                                           | 1         | 1.61%   |
| Realtek Laptop Camera                                        | 1         | 1.61%   |
| Realtek Integrated_Webcam_HD                                 | 1         | 1.61%   |
| Realtek Integrated Webcam HD                                 | 1         | 1.61%   |
| Realtek Integrated Camera                                    | 1         | 1.61%   |
| Quanta HP Wide Vision HD Camera                              | 1         | 1.61%   |
| Quanta HD Webcam                                             | 1         | 1.61%   |
| Quanta HD Camera                                             | 1         | 1.61%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera         | 1         | 1.61%   |
| Lite-On TOSHIBA Web Camera - HD                              | 1         | 1.61%   |
| Lite-On Integrated Camera                                    | 1         | 1.61%   |
| Lite-On HP Webcam                                            | 1         | 1.61%   |
| IMC Networks USB2.0 UVC 1.3M WebCam                          | 1         | 1.61%   |
| IMC Networks Lenovo EasyCamera                               | 1         | 1.61%   |
| Chicony XiaoMi USB 2.0 Webcam                                | 1         | 1.61%   |
| Chicony USB2.0 Camera                                        | 1         | 1.61%   |
| Chicony USB 2.0 Camera                                       | 1         | 1.61%   |
| Chicony Integrated HP HD Webcam                              | 1         | 1.61%   |
| Chicony HP Truevision HD                                     | 1         | 1.61%   |
| Chicony HP HD Camera                                         | 1         | 1.61%   |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam | 1         | 1.61%   |
| Alcor Micro 720P USB Webcam                                  | 1         | 1.61%   |
| Acer HD Webcam                                               | 1         | 1.61%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Elan Microelectronics      | 4         | 36.36%  |
| Validity Sensors           | 3         | 27.27%  |
| Synaptics                  | 3         | 27.27%  |
| Shenzhen Goodix Technology | 1         | 9.09%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Elan ELAN:Fingerprint                             | 3         | 27.27%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 2         | 18.18%  |
| Validity Sensors VFS471 Fingerprint Reader        | 1         | 9.09%   |
| Validity Sensors VFS 5011 fingerprint sensor      | 1         | 9.09%   |
| Validity Sensors Synaptics WBDI                   | 1         | 9.09%   |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 1         | 9.09%   |
| Shenzhen Goodix  FingerPrint Device               | 1         | 9.09%   |
| Elan ELAN:ARM-M4                                  | 1         | 9.09%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 3         | 42.86%  |
| Alcor Micro | 3         | 42.86%  |
| O2 Micro    | 1         | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 3         | 42.86%  |
| Broadcom 58200                      | 2         | 28.57%  |
| O2 Micro Oz776 SmartCard Reader     | 1         | 14.29%  |
| Broadcom 5880                       | 1         | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 36        | 46.15%  |
| 1     | 21        | 26.92%  |
| 2     | 8         | 10.26%  |
| 3     | 6         | 7.69%   |
| 4     | 5         | 6.41%   |
| 6     | 1         | 1.28%   |
| 5     | 1         | 1.28%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 11        | 13.41%  |
| Camera                   | 11        | 13.41%  |
| Bluetooth                | 10        | 12.2%   |
| Communication controller | 9         | 10.98%  |
| Net/wireless             | 8         | 9.76%   |
| Graphics card            | 7         | 8.54%   |
| Chipcard                 | 6         | 7.32%   |
| Multimedia controller    | 5         | 6.1%    |
| Card reader              | 4         | 4.88%   |
| Network                  | 3         | 3.66%   |
| Sound                    | 2         | 2.44%   |
| Modem                    | 2         | 2.44%   |
| Firewire controller      | 2         | 2.44%   |
| Storage/ata              | 1         | 1.22%   |
| Net/ethernet             | 1         | 1.22%   |

