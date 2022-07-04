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

Total: 88

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
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
| 5.14.9-gentoo-x86_64                            | 3         | 4.29%   |
| 5.18.4-gentoo                                   | 2         | 2.86%   |
| 5.18.1-gentoo-r2                                | 2         | 2.86%   |
| 5.17.1-gentoo-r1                                | 2         | 2.86%   |
| 5.16.0-gentoo-x86_64                            | 2         | 2.86%   |
| 5.15.41-gentoo-dist                             | 2         | 2.86%   |
| 5.15.10-gentoo-x86_64                           | 2         | 2.86%   |
| 5.18.8-gentoo                                   | 1         | 1.43%   |
| 5.18.5-gentoo                                   | 1         | 1.43%   |
| 5.18.1-gentoo-r1-x86_64                         | 1         | 1.43%   |
| 5.18.1-gentoo-r1                                | 1         | 1.43%   |
| 5.18.0-rc7-x86_64-git-00119-gb015dcd62b86-dirty | 1         | 1.43%   |
| 5.18.0-g95ff72a6c129                            | 1         | 1.43%   |
| 5.17.9-gentoo-x86_64                            | 1         | 1.43%   |
| 5.17.9-gentoo-x86                               | 1         | 1.43%   |
| 5.17.9-gentoo                                   | 1         | 1.43%   |
| 5.17.8-gentoo-x86_64                            | 1         | 1.43%   |
| 5.17.8-gentoo                                   | 1         | 1.43%   |
| 5.17.7-gentoo-groovin                           | 1         | 1.43%   |
| 5.17.6-zen1                                     | 1         | 1.43%   |
| 5.17.5-gentoo-dist                              | 1         | 1.43%   |
| 5.17.3-gentoo                                   | 1         | 1.43%   |
| 5.17.2-gentoo-groovin                           | 1         | 1.43%   |
| 5.17.13-gentoo                                  | 1         | 1.43%   |
| 5.17.12-gentoo-dist                             | 1         | 1.43%   |
| 5.17.0-gentoo-x86_64                            | 1         | 1.43%   |
| 5.16.9-gentoo-dist                              | 1         | 1.43%   |
| 5.16.8-gentoo-gentoo-dist                       | 1         | 1.43%   |
| 5.16.5-gentoo-x86_64                            | 1         | 1.43%   |
| 5.16.2-gentoo-x86_64                            | 1         | 1.43%   |
| 5.16.2-gentoo                                   | 1         | 1.43%   |
| 5.16.14-gentoo-x86_64-lto                       | 1         | 1.43%   |
| 5.16.14-gentoo                                  | 1         | 1.43%   |
| 5.16.11-gentoo-dist                             | 1         | 1.43%   |
| 5.16.10-gentoo--20-feb-2022                     | 1         | 1.43%   |
| 5.16.10-gentoo                                  | 1         | 1.43%   |
| 5.16.1-gentoo-x86_64                            | 1         | 1.43%   |
| 5.16.1-gentoo                                   | 1         | 1.43%   |
| 5.16.0-xanmod1                                  | 1         | 1.43%   |
| 5.16.0-pf5                                      | 1         | 1.43%   |
| 5.16.0-gentoo-gentoo-dist                       | 1         | 1.43%   |
| 5.16.0-gentoo                                   | 1         | 1.43%   |
| 5.15.7-gentoo                                   | 1         | 1.43%   |
| 5.15.6-gentoo                                   | 1         | 1.43%   |
| 5.15.5-gentoo-x86_64                            | 1         | 1.43%   |
| 5.15.5-gentoo-dist                              | 1         | 1.43%   |
| 5.15.5-gentoo                                   | 1         | 1.43%   |
| 5.15.35-adry                                    | 1         | 1.43%   |
| 5.15.33-gentoo-x86_64                           | 1         | 1.43%   |
| 5.15.33-gentoo-113-eee_drivers                  | 1         | 1.43%   |
| 5.15.19-gentoo-112-overlayfs                    | 1         | 1.43%   |
| 5.15.13-gentoo-dist                             | 1         | 1.43%   |
| 5.15.13-gentoo                                  | 1         | 1.43%   |
| 5.15.12-gentoo                                  | 1         | 1.43%   |
| 5.15.1-gentoo-x86_64                            | 1         | 1.43%   |
| 5.14.9-gentoo                                   | 1         | 1.43%   |
| 5.14.7-gentoo-x86_64                            | 1         | 1.43%   |
| 5.14.14-gentoo-x86_64                           | 1         | 1.43%   |
| 5.14.14-gentoo-dist                             | 1         | 1.43%   |
| 5.10.83-gentoo-dist                             | 1         | 1.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.16.0  | 6         | 8.57%   |
| 5.18.1  | 4         | 5.71%   |
| 5.14.9  | 4         | 5.71%   |
| 5.17.9  | 3         | 4.29%   |
| 5.15.5  | 3         | 4.29%   |
| 5.18.4  | 2         | 2.86%   |
| 5.18.0  | 2         | 2.86%   |
| 5.17.8  | 2         | 2.86%   |
| 5.17.1  | 2         | 2.86%   |
| 5.16.2  | 2         | 2.86%   |
| 5.16.14 | 2         | 2.86%   |
| 5.16.10 | 2         | 2.86%   |
| 5.16.1  | 2         | 2.86%   |
| 5.15.41 | 2         | 2.86%   |
| 5.15.33 | 2         | 2.86%   |
| 5.15.13 | 2         | 2.86%   |
| 5.15.10 | 2         | 2.86%   |
| 5.14.14 | 2         | 2.86%   |
| 5.18.8  | 1         | 1.43%   |
| 5.18.5  | 1         | 1.43%   |
| 5.17.7  | 1         | 1.43%   |
| 5.17.6  | 1         | 1.43%   |
| 5.17.5  | 1         | 1.43%   |
| 5.17.3  | 1         | 1.43%   |
| 5.17.2  | 1         | 1.43%   |
| 5.17.13 | 1         | 1.43%   |
| 5.17.12 | 1         | 1.43%   |
| 5.17.0  | 1         | 1.43%   |
| 5.16.9  | 1         | 1.43%   |
| 5.16.8  | 1         | 1.43%   |
| 5.16.5  | 1         | 1.43%   |
| 5.16.11 | 1         | 1.43%   |
| 5.15.7  | 1         | 1.43%   |
| 5.15.6  | 1         | 1.43%   |
| 5.15.35 | 1         | 1.43%   |
| 5.15.19 | 1         | 1.43%   |
| 5.15.12 | 1         | 1.43%   |
| 5.15.1  | 1         | 1.43%   |
| 5.14.7  | 1         | 1.43%   |
| 5.10.83 | 1         | 1.43%   |
| 5.10.76 | 1         | 1.43%   |
| 5.10.70 | 1         | 1.43%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.16    | 17        | 25.37%  |
| 5.15    | 16        | 23.88%  |
| 5.17    | 14        | 20.9%   |
| 5.18    | 10        | 14.93%  |
| 5.14    | 7         | 10.45%  |
| 5.10    | 3         | 4.48%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 58        | 96.67%  |
| i686   | 2         | 3.33%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Unknown  | 23        | 37.7%   |
| KDE5     | 19        | 31.15%  |
| GNOME    | 7         | 11.48%  |
| XFCE     | 4         | 6.56%   |
| sway     | 2         | 3.28%   |
| xmonad   | 1         | 1.64%   |
| MATE     | 1         | 1.64%   |
| LeftWM   | 1         | 1.64%   |
| fvwm     | 1         | 1.64%   |
| DWM      | 1         | 1.64%   |
| Cinnamon | 1         | 1.64%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 28        | 44.44%  |
| Wayland | 16        | 25.4%   |
| Tty     | 10        | 15.87%  |
| Unknown | 9         | 14.29%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 26        | 42.62%  |
| SDDM    | 22        | 36.07%  |
| LightDM | 6         | 9.84%   |
| GDM     | 4         | 6.56%   |
| XDM     | 1         | 1.64%   |
| SLiM    | 1         | 1.64%   |
| GREETD  | 1         | 1.64%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Notebooks | Percent |
|------------|-----------|---------|
| en_US      | 29        | 48.33%  |
| en_GB      | 5         | 8.33%   |
| Unknown    | 5         | 8.33%   |
| C.UTF8     | 4         | 6.67%   |
| ru_RU      | 2         | 3.33%   |
| it_IT      | 2         | 3.33%   |
| es_AR      | 2         | 3.33%   |
| de_DE      | 2         | 3.33%   |
| C          | 2         | 3.33%   |
| tr_TR      | 1         | 1.67%   |
| fr_FR      | 1         | 1.67%   |
| fr_CA      | 1         | 1.67%   |
| en_US.UTF8 | 1         | 1.67%   |
| en_NZ      | 1         | 1.67%   |
| en_AU      | 1         | 1.67%   |
| el_GR      | 1         | 1.67%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 54        | 88.52%  |
| BIOS | 7         | 11.48%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 35        | 58.33%  |
| Btrfs    | 22        | 36.67%  |
| Zfs      | 1         | 1.67%   |
| F2fs     | 1         | 1.67%   |
| Bcachefs | 1         | 1.67%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 54        | 90%     |
| MBR  | 6         | 10%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 46        | 74.19%  |
| Yes       | 16        | 25.81%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 45        | 73.77%  |
| Yes       | 16        | 26.23%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 20        | 33.33%  |
| Dell             | 10        | 16.67%  |
| Hewlett-Packard  | 8         | 13.33%  |
| ASUSTek Computer | 6         | 10%     |
| MSI              | 4         | 6.67%   |
| Acer             | 3         | 5%      |
| Timi             | 2         | 3.33%   |
| Framework        | 2         | 3.33%   |
| Toshiba          | 1         | 1.67%   |
| System76         | 1         | 1.67%   |
| HUAWEI           | 1         | 1.67%   |
| BANGHO           | 1         | 1.67%   |
| AVITA            | 1         | 1.67%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| HP Laptop 15s-eq0xxx                     | 2         | 3.33%   |
| Framework Laptop                         | 2         | 3.33%   |
| ASUS ROG Strix G513QY_G513QY             | 2         | 3.33%   |
| Toshiba Satellite C850D-118              | 1         | 1.67%   |
| Timi RedmiBook 13                        | 1         | 1.67%   |
| Timi Mi Laptop Pro 15                    | 1         | 1.67%   |
| System76 Gazelle                         | 1         | 1.67%   |
| MSI MS-7A34                              | 1         | 1.67%   |
| MSI GS63VR 6RF                           | 1         | 1.67%   |
| MSI GE73 Raider RGB 8RF                  | 1         | 1.67%   |
| MSI GE66 Raider 11UE                     | 1         | 1.67%   |
| Lenovo Yoga Slim 7 14IIL05 82A1          | 1         | 1.67%   |
| Lenovo Yoga S740-14IIL 81RS              | 1         | 1.67%   |
| Lenovo ThinkPad X220 4291QT1             | 1         | 1.67%   |
| Lenovo ThinkPad X1 Carbon 7th 20QD0039RI | 1         | 1.67%   |
| Lenovo ThinkPad T470p 20J7S06Q00         | 1         | 1.67%   |
| Lenovo ThinkPad T460 20FMS421US          | 1         | 1.67%   |
| Lenovo ThinkPad T14 Gen 2a 20XK002SCK    | 1         | 1.67%   |
| Lenovo ThinkPad T14 Gen 1 20S1S35Y00     | 1         | 1.67%   |
| Lenovo ThinkPad P73 20QSS09S00           | 1         | 1.67%   |
| Lenovo ThinkPad P1 Gen 3 20TJS2F437      | 1         | 1.67%   |
| Lenovo ThinkPad E495 20NE000BGE          | 1         | 1.67%   |
| Lenovo ThinkPad E15 Gen 2 20T8001STX     | 1         | 1.67%   |
| Lenovo ThinkPad 20FMCT01WW               | 1         | 1.67%   |
| Lenovo ThinkBook 14 G3 ACL 21A2          | 1         | 1.67%   |
| Lenovo Legion Y7000 2019 PG0 81T0        | 1         | 1.67%   |
| Lenovo Legion Y540-15IRH 81SX            | 1         | 1.67%   |
| Lenovo Legion R7000 2020 82B6            | 1         | 1.67%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ         | 1         | 1.67%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5         | 1         | 1.67%   |
| Lenovo IdeaPad 5 15ITL05 82FG            | 1         | 1.67%   |
| HUAWEI BOHB-WAX9                         | 1         | 1.67%   |
| HP Victus by Laptop 16-e0xxx             | 1         | 1.67%   |
| HP ProBook 6570b                         | 1         | 1.67%   |
| HP Pavilion Notebook                     | 1         | 1.67%   |
| HP Pavilion Gaming Laptop 15-cx0xxx      | 1         | 1.67%   |
| HP OMEN by Laptop 15-dc0xxx              | 1         | 1.67%   |
| HP OMEN by Laptop                        | 1         | 1.67%   |
| Dell XPS 17 9710                         | 1         | 1.67%   |
| Dell XPS 15 9570                         | 1         | 1.67%   |
| Dell XPS 15 9510                         | 1         | 1.67%   |
| Dell Precision 7550                      | 1         | 1.67%   |
| Dell Precision 3561                      | 1         | 1.67%   |
| Dell Latitude D420                       | 1         | 1.67%   |
| Dell Latitude 7490                       | 1         | 1.67%   |
| Dell Inspiron 5415                       | 1         | 1.67%   |
| Dell Inspiron 15 5510                    | 1         | 1.67%   |
| Dell G5 5505                             | 1         | 1.67%   |
| BANGHO MAX G0101                         | 1         | 1.67%   |
| AVITA NS14A6                             | 1         | 1.67%   |
| ASUS X555LJ                              | 1         | 1.67%   |
| ASUS UX430UAR                            | 1         | 1.67%   |
| ASUS ROG Zephyrus G14 GA401QE_GA401QE    | 1         | 1.67%   |
| ASUS 1005HA                              | 1         | 1.67%   |
| Acer Nitro AN515-54                      | 1         | 1.67%   |
| Acer Aspire A715-42G                     | 1         | 1.67%   |
| Acer Aspire A515-55                      | 1         | 1.67%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 11        | 18.33%  |
| Lenovo Legion     | 4         | 6.67%   |
| Dell XPS          | 3         | 5%      |
| ASUS ROG          | 3         | 5%      |
| Lenovo Yoga       | 2         | 3.33%   |
| Lenovo IdeaPad    | 2         | 3.33%   |
| HP Pavilion       | 2         | 3.33%   |
| HP OMEN           | 2         | 3.33%   |
| HP Laptop         | 2         | 3.33%   |
| Framework Laptop  | 2         | 3.33%   |
| Dell Precision    | 2         | 3.33%   |
| Dell Latitude     | 2         | 3.33%   |
| Dell Inspiron     | 2         | 3.33%   |
| Acer Aspire       | 2         | 3.33%   |
| Toshiba Satellite | 1         | 1.67%   |
| Timi RedmiBook    | 1         | 1.67%   |
| Timi Mi           | 1         | 1.67%   |
| System76 Gazelle  | 1         | 1.67%   |
| MSI MS-7A34       | 1         | 1.67%   |
| MSI GS63VR        | 1         | 1.67%   |
| MSI GE73          | 1         | 1.67%   |
| MSI GE66          | 1         | 1.67%   |
| Lenovo ThinkBook  | 1         | 1.67%   |
| HUAWEI BOHB-WAX9  | 1         | 1.67%   |
| HP Victus         | 1         | 1.67%   |
| HP ProBook        | 1         | 1.67%   |
| Dell G5           | 1         | 1.67%   |
| BANGHO MAX        | 1         | 1.67%   |
| AVITA NS14A6      | 1         | 1.67%   |
| ASUS X555LJ       | 1         | 1.67%   |
| ASUS UX430UAR     | 1         | 1.67%   |
| ASUS 1005HA       | 1         | 1.67%   |
| Acer Nitro        | 1         | 1.67%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 19        | 31.67%  |
| 2020 | 12        | 20%     |
| 2019 | 12        | 20%     |
| 2018 | 5         | 8.33%   |
| 2017 | 3         | 5%      |
| 2016 | 2         | 3.33%   |
| 2012 | 2         | 3.33%   |
| 2015 | 1         | 1.67%   |
| 2014 | 1         | 1.67%   |
| 2011 | 1         | 1.67%   |
| 2009 | 1         | 1.67%   |
| 2006 | 1         | 1.67%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 60        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 58        | 95.08%  |
| Enabled  | 3         | 4.92%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 59        | 98.33%  |
| Yes  | 1         | 1.67%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 16        | 26.67%  |
| 8.01-16.0   | 16        | 26.67%  |
| 4.01-8.0    | 11        | 18.33%  |
| 32.01-64.0  | 8         | 13.33%  |
| 64.01-256.0 | 3         | 5%      |
| 3.01-4.0    | 2         | 3.33%   |
| 24.01-32.0  | 1         | 1.67%   |
| 2.01-3.0    | 1         | 1.67%   |
| 1.01-2.0    | 1         | 1.67%   |
| 0.51-1.0    | 1         | 1.67%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 4.01-8.0  | 17        | 25.76%  |
| 1.01-2.0  | 14        | 21.21%  |
| 3.01-4.0  | 11        | 16.67%  |
| 2.01-3.0  | 10        | 15.15%  |
| 8.01-16.0 | 7         | 10.61%  |
| 0.51-1.0  | 5         | 7.58%   |
| 0.01-0.5  | 2         | 3.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 41        | 67.21%  |
| 2      | 17        | 27.87%  |
| 3      | 2         | 3.28%   |
| 4      | 1         | 1.64%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 54        | 90%     |
| Yes       | 6         | 10%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 42        | 70%     |
| No        | 18        | 30%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 60        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 54        | 88.52%  |
| No        | 7         | 11.48%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 13        | 21.31%  |
| UK          | 5         | 8.2%    |
| Germany     | 5         | 8.2%    |
| Russia      | 4         | 6.56%   |
| Belarus     | 3         | 4.92%   |
| Spain       | 2         | 3.28%   |
| Poland      | 2         | 3.28%   |
| Italy       | 2         | 3.28%   |
| India       | 2         | 3.28%   |
| Greece      | 2         | 3.28%   |
| France      | 2         | 3.28%   |
| Czechia     | 2         | 3.28%   |
| China       | 2         | 3.28%   |
| Argentina   | 2         | 3.28%   |
| Uruguay     | 1         | 1.64%   |
| Turkey      | 1         | 1.64%   |
| Sweden      | 1         | 1.64%   |
| Romania     | 1         | 1.64%   |
| Philippines | 1         | 1.64%   |
| Norway      | 1         | 1.64%   |
| New Zealand | 1         | 1.64%   |
| Netherlands | 1         | 1.64%   |
| Hong Kong   | 1         | 1.64%   |
| Finland     | 1         | 1.64%   |
| Canada      | 1         | 1.64%   |
| Belgium     | 1         | 1.64%   |
| Australia   | 1         | 1.64%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Minsk                  | 3         | 4.69%   |
| Sterling               | 2         | 3.13%   |
| Milan                  | 2         | 3.13%   |
| Guangzhou              | 2         | 3.13%   |
| Winston-Salem          | 1         | 1.56%   |
| West Orange            | 1         | 1.56%   |
| Vantaa                 | 1         | 1.56%   |
| Sydney                 | 1         | 1.56%   |
| Storsteinnes           | 1         | 1.56%   |
| Santa Rosa             | 1         | 1.56%   |
| Sacramento             | 1         | 1.56%   |
| Ratingen               | 1         | 1.56%   |
| Québec                | 1         | 1.56%   |
| Punta Gorda            | 1         | 1.56%   |
| Pujaut                 | 1         | 1.56%   |
| Prague                 | 1         | 1.56%   |
| Perm                   | 1         | 1.56%   |
| Paris                  | 1         | 1.56%   |
| Ocala                  | 1         | 1.56%   |
| Nuremberg              | 1         | 1.56%   |
| Novosibirsk            | 1         | 1.56%   |
| Nizhniy Novgorod       | 1         | 1.56%   |
| New York               | 1         | 1.56%   |
| Neath                  | 1         | 1.56%   |
| Motala                 | 1         | 1.56%   |
| Moscow                 | 1         | 1.56%   |
| Milton Keynes          | 1         | 1.56%   |
| London                 | 1         | 1.56%   |
| Lochristi              | 1         | 1.56%   |
| Leidschendam           | 1         | 1.56%   |
| Kulmbach               | 1         | 1.56%   |
| Kallithea              | 1         | 1.56%   |
| Kailua-Kona            | 1         | 1.56%   |
| Hyderabad              | 1         | 1.56%   |
| Houston                | 1         | 1.56%   |
| Gmina Lwówek Śląski | 1         | 1.56%   |
| Foshan                 | 1         | 1.56%   |
| Erskine                | 1         | 1.56%   |
| Córdoba               | 1         | 1.56%   |
| Cieszyn                | 1         | 1.56%   |
| Chicago                | 1         | 1.56%   |
| Chelyabinsk            | 1         | 1.56%   |
| Chattanooga            | 1         | 1.56%   |
| Cerritos               | 1         | 1.56%   |
| Central                | 1         | 1.56%   |
| Burke                  | 1         | 1.56%   |
| Brno                   | 1         | 1.56%   |
| Brasov                 | 1         | 1.56%   |
| Bournemouth            | 1         | 1.56%   |
| Bhavnagar              | 1         | 1.56%   |
| Bertamirans            | 1         | 1.56%   |
| Bernal                 | 1         | 1.56%   |
| Berlin                 | 1         | 1.56%   |
| Barakaldo              | 1         | 1.56%   |
| Bad Zwesten            | 1         | 1.56%   |
| Auckland               | 1         | 1.56%   |
| Athens                 | 1         | 1.56%   |
| Ann Arbor              | 1         | 1.56%   |
| Ankara                 | 1         | 1.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 17        | 20     | 21.52%  |
| Samsung Electronics | 13        | 17     | 16.46%  |
| SK hynix            | 9         | 9      | 11.39%  |
| Intel               | 7         | 9      | 8.86%   |
| Toshiba             | 4         | 5      | 5.06%   |
| Seagate             | 4         | 5      | 5.06%   |
| Micron Technology   | 4         | 4      | 5.06%   |
| SanDisk             | 3         | 4      | 3.8%    |
| Crucial             | 3         | 4      | 3.8%    |
| KIOXIA-EXCERIA      | 2         | 4      | 2.53%   |
| Kingston            | 2         | 2      | 2.53%   |
| HGST                | 2         | 2      | 2.53%   |
| XrayDisk            | 1         | 1      | 1.27%   |
| Unknown             | 1         | 3      | 1.27%   |
| Plextor             | 1         | 1      | 1.27%   |
| Phison              | 1         | 1      | 1.27%   |
| LITEON              | 1         | 1      | 1.27%   |
| KIOXIA              | 1         | 2      | 1.27%   |
| Hoodisk             | 1         | 1      | 1.27%   |
| Hitachi             | 1         | 1      | 1.27%   |
| A-DATA Technology   | 1         | 1      | 1.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel SSDPEKNU512GZ 512GB               | 3         | 3.7%    |
| Toshiba KXG6AZNV512G 512GB              | 2         | 2.47%   |
| SK hynix PC711 NVMe 512GB               | 2         | 2.47%   |
| Samsung MZVLB512HBJQ-000L2 512GB        | 2         | 2.47%   |
| Intel SSDPEKNW010T8 1TB                 | 2         | 2.47%   |
| HGST HTS721010A9E630 1TB                | 2         | 2.47%   |
| XrayDisk SSD 128GB                      | 1         | 1.23%   |
| WDC WDS500G3X0C-00SJG0 500GB            | 1         | 1.23%   |
| WDC WDS500G2B0C-00PXH0 500GB            | 1         | 1.23%   |
| WDC WDS250G2X0C-00L350 250GB            | 1         | 1.23%   |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 1         | 1.23%   |
| WDC WDS100T2B0C-00PXH0 1TB              | 1         | 1.23%   |
| WDC WDS100T2B0A-00SM50 1TB SSD          | 1         | 1.23%   |
| WDC WD3200LPVX-22V0TT0 320GB            | 1         | 1.23%   |
| WDC WD2500BEVS-22UST0 250GB             | 1         | 1.23%   |
| WDC WD10SPSX-08A6W 1TB                  | 1         | 1.23%   |
| WDC WD10EZEX-08M2NA0 1TB                | 1         | 1.23%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB    | 1         | 1.23%   |
| WDC PC SN730 SDBPNTY-512G-1006 512GB    | 1         | 1.23%   |
| WDC PC SN730 SDBPNTY-1T00-1006 1TB      | 1         | 1.23%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB    | 1         | 1.23%   |
| WDC PC SN530 SDBPMPZ-256G-1001 256GB    | 1         | 1.23%   |
| WDC PC SN520 SDAPNUW-512G-1014 512GB    | 1         | 1.23%   |
| WDC PC SN520 SDAPMUW-512G-1101 512GB    | 1         | 1.23%   |
| Unknown USB DISK 3.2 1TB                | 1         | 1.23%   |
| Toshiba MK6008GAH 64GB                  | 1         | 1.23%   |
| Toshiba KSG60ZMV512G M.2 2280 512GB SSD | 1         | 1.23%   |
| SK hynix SKHynix_HFS512GDE9X081N 512GB  | 1         | 1.23%   |
| SK hynix SKHynix_HFS001TDE9X084N 1TB    | 1         | 1.23%   |
| SK hynix PC711 NVMe 1TB                 | 1         | 1.23%   |
| SK hynix PC611 NVMe 512GB               | 1         | 1.23%   |
| SK hynix HFM512GDHTNG-8710B 512GB       | 1         | 1.23%   |
| SK hynix HFM512GD3JX016N 512GB          | 1         | 1.23%   |
| SK hynix BC711 NVMe 512GB               | 1         | 1.23%   |
| Seagate ST1000LM049-2GH172 1TB          | 1         | 1.23%   |
| Seagate ST1000LM035-1RK172 1TB          | 1         | 1.23%   |
| Seagate ST1000LM035-1RK1 1TB            | 1         | 1.23%   |
| Seagate FireCuda 530 ZP4000GM30013 4TB  | 1         | 1.23%   |
| SanDisk SDSSDH3 1T00 1TB                | 1         | 1.23%   |
| SanDisk SD9SN8W256G1002 256GB SSD       | 1         | 1.23%   |
| SanDisk SD8TB8U256G1001 256GB SSD       | 1         | 1.23%   |
| Samsung SSD 980 PRO 2TB                 | 1         | 1.23%   |
| Samsung SSD 970 PRO 1TB                 | 1         | 1.23%   |
| Samsung SSD 970 EVO Plus 1TB            | 1         | 1.23%   |
| Samsung SSD 970 EVO 500GB               | 1         | 1.23%   |
| Samsung SSD 870 EVO 1TB                 | 1         | 1.23%   |
| Samsung SSD 850 EVO 250GB               | 1         | 1.23%   |
| Samsung PSSD T7 500GB                   | 1         | 1.23%   |
| Samsung PSSD T7 1TB                     | 1         | 1.23%   |
| Samsung MZVLW1T0HMLH-000L7 1TB          | 1         | 1.23%   |
| Samsung MZVLB1T0HBLR-000L2 1TB          | 1         | 1.23%   |
| Samsung MZVL21T0HCLR-00B00 1TB          | 1         | 1.23%   |
| Samsung MZNLN512HAJQ-00000 512GB SSD    | 1         | 1.23%   |
| Samsung MZALQ512HALU-000L2 512GB        | 1         | 1.23%   |
| Plextor PX-512M8VC 512GB SSD            | 1         | 1.23%   |
| Phison 311CD0512GB                      | 1         | 1.23%   |
| Micron MTFDHBA512TCK 512GB              | 1         | 1.23%   |
| Micron MTFDHBA256TCK 256GB              | 1         | 1.23%   |
| Micron 2450 NVMe 1024GB                 | 1         | 1.23%   |
| Micron 2200S NVMe 1024GB                | 1         | 1.23%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 4         | 5      | 36.36%  |
| Seagate | 3         | 4      | 27.27%  |
| HGST    | 2         | 2      | 18.18%  |
| Toshiba | 1         | 1      | 9.09%   |
| Hitachi | 1         | 1      | 9.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 6      | 25%     |
| SanDisk             | 3         | 4      | 18.75%  |
| WDC                 | 2         | 3      | 12.5%   |
| Crucial             | 2         | 3      | 12.5%   |
| XrayDisk            | 1         | 1      | 6.25%   |
| Toshiba             | 1         | 1      | 6.25%   |
| Plextor             | 1         | 1      | 6.25%   |
| Hoodisk             | 1         | 1      | 6.25%   |
| A-DATA Technology   | 1         | 1      | 6.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 44        | 60     | 61.11%  |
| SSD     | 16        | 21     | 22.22%  |
| HDD     | 11        | 13     | 15.28%  |
| Unknown | 1         | 3      | 1.39%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 44        | 60     | 62.86%  |
| SATA | 24        | 32     | 34.29%  |
| SAS  | 2         | 5      | 2.86%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.51-1.0   | 14        | 17     | 51.85%  |
| 0.01-0.5   | 12        | 16     | 44.44%  |
| 1.01-2.0   | 1         | 1      | 3.7%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 20        | 32.79%  |
| 501-1000       | 13        | 21.31%  |
| 101-250        | 10        | 16.39%  |
| 1001-2000      | 8         | 13.11%  |
| 1-20           | 3         | 4.92%   |
| More than 3000 | 2         | 3.28%   |
| 21-50          | 2         | 3.28%   |
| 2001-3000      | 2         | 3.28%   |
| 51-100         | 1         | 1.64%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 15        | 23.08%  |
| 101-250   | 13        | 20%     |
| 21-50     | 11        | 16.92%  |
| 251-500   | 10        | 15.38%  |
| 51-100    | 6         | 9.23%   |
| 1001-2000 | 5         | 7.69%   |
| 501-1000  | 5         | 7.69%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD10EZEX-08M2NA0 1TB          | 1         | 2      | 12.5%   |
| Toshiba MK6008GAH 64GB            | 1         | 1      | 12.5%   |
| Seagate ST1000LM049-2GH172 1TB    | 1         | 1      | 12.5%   |
| Seagate ST1000LM035-1RK172 1TB    | 1         | 2      | 12.5%   |
| Intel SSDPEKKF256G8L 256GB        | 1         | 1      | 12.5%   |
| HGST HTS721010A9E630 1TB          | 1         | 1      | 12.5%   |
| Crucial CT1000P1SSD8 1TB          | 1         | 1      | 12.5%   |
| A-DATA Technology SP550 240GB SSD | 1         | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 2         | 3      | 25%     |
| WDC               | 1         | 2      | 12.5%   |
| Toshiba           | 1         | 1      | 12.5%   |
| Intel             | 1         | 1      | 12.5%   |
| HGST              | 1         | 1      | 12.5%   |
| Crucial           | 1         | 1      | 12.5%   |
| A-DATA Technology | 1         | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 3      | 40%     |
| WDC     | 1         | 2      | 20%     |
| Toshiba | 1         | 1      | 20%     |
| HGST    | 1         | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 5         | 7      | 62.5%   |
| NVMe | 2         | 2      | 25%     |
| SSD  | 1         | 1      | 12.5%   |

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
| Works    | 55        | 82     | 84.62%  |
| Malfunc  | 8         | 10     | 12.31%  |
| Detected | 2         | 5      | 3.08%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 34        | 38.2%   |
| SanDisk                      | 11        | 12.36%  |
| Samsung Electronics          | 10        | 11.24%  |
| AMD                          | 10        | 11.24%  |
| SK hynix                     | 9         | 10.11%  |
| Micron Technology            | 4         | 4.49%   |
| Toshiba America Info Systems | 3         | 3.37%   |
| KIOXIA                       | 2         | 2.25%   |
| Kingston Technology Company  | 2         | 2.25%   |
| Seagate Technology           | 1         | 1.12%   |
| Phison Electronics           | 1         | 1.12%   |
| Micron/Crucial Technology    | 1         | 1.12%   |
| Lite-On Technology           | 1         | 1.12%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 10        | 10.99%  |
| SK hynix Gold P31 SSD                                                          | 7         | 7.69%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 6         | 6.59%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 5         | 5.49%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 4         | 4.4%    |
| Micron Non-Volatile memory controller                                          | 4         | 4.4%    |
| Intel Volume Management Device NVMe RAID Controller                            | 3         | 3.3%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 3         | 3.3%    |
| Intel SSD 660P Series                                                          | 3         | 3.3%    |
| Intel Non-Volatile memory controller                                           | 3         | 3.3%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 2.2%    |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 2         | 2.2%    |
| SanDisk Non-Volatile memory controller                                         | 2         | 2.2%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 2.2%    |
| KIOXIA NVMe SSD                                                                | 2         | 2.2%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 2.2%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 2         | 2.2%    |
| Intel Comet Lake SATA AHCI Controller                                          | 2         | 2.2%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 2.2%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 2         | 2.2%    |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 1         | 1.1%    |
| SK hynix Non-Volatile memory controller                                        | 1         | 1.1%    |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 1.1%    |
| Seagate FireCuda 530 SSD                                                       | 1         | 1.1%    |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 1         | 1.1%    |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 1         | 1.1%    |
| SanDisk PC SN520 NVMe SSD                                                      | 1         | 1.1%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 1.1%    |
| Samsung NVMe SSD Controller 980                                                | 1         | 1.1%    |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 1.1%    |
| Micron/Crucial P1 NVMe PCIe SSD                                                | 1         | 1.1%    |
| Lite-On Non-Volatile memory controller                                         | 1         | 1.1%    |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 1         | 1.1%    |
| Kingston Company Company Non-Volatile memory controller                        | 1         | 1.1%    |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                | 1         | 1.1%    |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 1         | 1.1%    |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 1         | 1.1%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 1         | 1.1%    |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 1         | 1.1%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 1.1%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 1         | 1.1%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1         | 1.1%    |
| AMD 300 Series Chipset SATA Controller                                         | 1         | 1.1%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 44        | 53.66%  |
| SATA | 33        | 40.24%  |
| RAID | 4         | 4.88%   |
| IDE  | 1         | 1.22%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 41        | 68.33%  |
| AMD    | 19        | 31.67%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 4         | 6.67%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 5%      |
| Intel Core i7-10850H CPU @ 2.70GHz            | 2         | 3.33%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 3.33%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 2         | 3.33%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 2         | 3.33%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 3.33%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 2         | 3.33%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 3.33%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 2         | 3.33%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 2         | 3.33%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 2         | 3.33%   |
| Intel Core i9-9880H CPU @ 2.30GHz             | 1         | 1.67%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 1.67%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 1.67%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 1.67%   |
| Intel Core i7-7820HK CPU @ 2.90GHz            | 1         | 1.67%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 1.67%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 1.67%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 1.67%   |
| Intel Core i7-10610U CPU @ 1.80GHz            | 1         | 1.67%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 1.67%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 1.67%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 1.67%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 1.67%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 1.67%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 1.67%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 1         | 1.67%   |
| Intel Core i3-4000M CPU @ 2.40GHz             | 1         | 1.67%   |
| Intel Core Duo CPU U2500 @ 1.20GHz            | 1         | 1.67%   |
| Intel Atom CPU N280 @ 1.66GHz                 | 1         | 1.67%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 1         | 1.67%   |
| Intel 11th Gen Core i7-11850H @ 2.50GHz       | 1         | 1.67%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1         | 1.67%   |
| Intel 11th Gen Core i7-11390H @ 3.40GHz       | 1         | 1.67%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 1         | 1.67%   |
| AMD Ryzen 7 PRO 5850U with Radeon Graphics    | 1         | 1.67%   |
| AMD Ryzen 7 5800HS with Radeon Graphics       | 1         | 1.67%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 1         | 1.67%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 1         | 1.67%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 1         | 1.67%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 1         | 1.67%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 1.67%   |
| AMD Ryzen 5 1500X Quad-Core Processor         | 1         | 1.67%   |
| AMD E1-1200 APU with Radeon HD Graphics       | 1         | 1.67%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model           | Notebooks | Percent |
|-----------------|-----------|---------|
| Intel Core i7   | 16        | 26.67%  |
| Intel Core i5   | 12        | 20%     |
| Other           | 9         | 15%     |
| AMD Ryzen 7     | 9         | 15%     |
| AMD Ryzen 5     | 4         | 6.67%   |
| AMD Ryzen 9     | 2         | 3.33%   |
| AMD Ryzen 3     | 2         | 3.33%   |
| Intel Core i9   | 1         | 1.67%   |
| Intel Core i3   | 1         | 1.67%   |
| Intel Core Duo  | 1         | 1.67%   |
| Intel Atom      | 1         | 1.67%   |
| AMD Ryzen 7 PRO | 1         | 1.67%   |
| AMD E1          | 1         | 1.67%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 24        | 40%     |
| 8      | 17        | 28.33%  |
| 2      | 10        | 16.67%  |
| 6      | 8         | 13.33%  |
| 1      | 1         | 1.67%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 60        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 56        | 93.33%  |
| 1      | 4         | 6.67%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 58        | 96.67%  |
| 32-bit         | 2         | 3.33%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x906ea    | 8         | 13.11%  |
| 0x0a50000c | 7         | 11.48%  |
| Unknown    | 6         | 9.84%   |
| 0x806ec    | 5         | 8.2%    |
| 0x806d1    | 5         | 8.2%    |
| 0x08108109 | 3         | 4.92%   |
| 0xa0652    | 2         | 3.28%   |
| 0x806c1    | 2         | 3.28%   |
| 0x706e5    | 2         | 3.28%   |
| 0x306d4    | 2         | 3.28%   |
| 0x08608103 | 2         | 3.28%   |
| 0x08600103 | 2         | 3.28%   |
| 0x906ed    | 1         | 1.64%   |
| 0x906e9    | 1         | 1.64%   |
| 0x806ea    | 1         | 1.64%   |
| 0x806c2    | 1         | 1.64%   |
| 0x6ec      | 1         | 1.64%   |
| 0x506e3    | 1         | 1.64%   |
| 0x406e3    | 1         | 1.64%   |
| 0x306c3    | 1         | 1.64%   |
| 0x306a9    | 1         | 1.64%   |
| 0x206a7    | 1         | 1.64%   |
| 0x08608102 | 1         | 1.64%   |
| 0x08600102 | 1         | 1.64%   |
| 0x08108102 | 1         | 1.64%   |
| 0x08001105 | 1         | 1.64%   |
| 0x05000119 | 1         | 1.64%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 18        | 29.51%  |
| IceLake     | 8         | 13.11%  |
| Zen 3       | 7         | 11.48%  |
| Zen+        | 4         | 6.56%   |
| TigerLake   | 4         | 6.56%   |
| Unknown     | 4         | 6.56%   |
| Zen 2       | 3         | 4.92%   |
| Skylake     | 2         | 3.28%   |
| CometLake   | 2         | 3.28%   |
| Broadwell   | 2         | 3.28%   |
| Zen         | 1         | 1.64%   |
| SandyBridge | 1         | 1.64%   |
| P6          | 1         | 1.64%   |
| IvyBridge   | 1         | 1.64%   |
| Haswell     | 1         | 1.64%   |
| Bonnell     | 1         | 1.64%   |
| Bobcat      | 1         | 1.64%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 38        | 44.71%  |
| Nvidia | 29        | 34.12%  |
| AMD    | 18        | 21.18%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 8         | 8.79%   |
| AMD Cezanne                                                                   | 7         | 7.69%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 5         | 5.49%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 4         | 4.4%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 4         | 4.4%    |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 4         | 4.4%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 4         | 4.4%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 3         | 3.3%    |
| Nvidia GP108M [GeForce MX250]                                                 | 3         | 3.3%    |
| AMD Lucienne                                                                  | 3         | 3.3%    |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                       | 2         | 2.2%    |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                    | 2         | 2.2%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 2         | 2.2%    |
| Intel UHD Graphics 620                                                        | 2         | 2.2%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 2         | 2.2%    |
| Intel Iris Plus Graphics G7                                                   | 2         | 2.2%    |
| Intel HD Graphics 630                                                         | 2         | 2.2%    |
| Intel HD Graphics 5500                                                        | 2         | 2.2%    |
| AMD Renoir                                                                    | 2         | 2.2%    |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                          | 2         | 2.2%    |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                    | 1         | 1.1%    |
| Nvidia TU117GLM [T600 Mobile]                                                 | 1         | 1.1%    |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                 | 1         | 1.1%    |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                       | 1         | 1.1%    |
| Nvidia TU104GLM [Quadro RTX 4000 Mobile / Max-Q]                              | 1         | 1.1%    |
| Nvidia GP108M [GeForce MX330]                                                 | 1         | 1.1%    |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                           | 1         | 1.1%    |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                                       | 1         | 1.1%    |
| Nvidia GM108M [GeForce 940M]                                                  | 1         | 1.1%    |
| Nvidia GM108M [GeForce 940MX]                                                 | 1         | 1.1%    |
| Nvidia GK208BM [GeForce 920M]                                                 | 1         | 1.1%    |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                       | 1         | 1.1%    |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                               | 1         | 1.1%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 1         | 1.1%    |
| Intel Skylake GT2 [HD Graphics 520]                                           | 1         | 1.1%    |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 1         | 1.1%    |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 1         | 1.1%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 1         | 1.1%    |
| Intel HD Graphics 530                                                         | 1         | 1.1%    |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 1         | 1.1%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 1         | 1.1%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 1         | 1.1%    |
| AMD Wrestler [Radeon HD 7310]                                                 | 1         | 1.1%    |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                      | 1         | 1.1%    |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                | 1         | 1.1%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                       | 1         | 1.1%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Intel + Nvidia | 22        | 36.67%  |
| 1 x Intel      | 14        | 23.33%  |
| 1 x AMD        | 11        | 18.33%  |
| 2 x AMD        | 4         | 6.67%   |
| 1 x Nvidia     | 4         | 6.67%   |
| AMD + Nvidia   | 3         | 5%      |
| 2 x Intel      | 2         | 3.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 38        | 63.33%  |
| Proprietary | 21        | 35%     |
| Unknown     | 1         | 1.67%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 32        | 51.61%  |
| 3.01-4.0   | 8         | 12.9%   |
| 1.01-2.0   | 6         | 9.68%   |
| 0.01-0.5   | 5         | 8.06%   |
| 0.51-1.0   | 4         | 6.45%   |
| 5.01-6.0   | 2         | 3.23%   |
| 2.01-3.0   | 2         | 3.23%   |
| 8.01-16.0  | 2         | 3.23%   |
| 7.01-8.0   | 1         | 1.61%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| BOE                 | 18        | 24.32%  |
| AU Optronics        | 12        | 16.22%  |
| Chimei Innolux      | 10        | 13.51%  |
| Samsung Electronics | 6         | 8.11%   |
| LG Display          | 6         | 8.11%   |
| Sharp               | 5         | 6.76%   |
| Goldstar            | 3         | 4.05%   |
| Lenovo              | 2         | 2.7%    |
| Hewlett-Packard     | 2         | 2.7%    |
| BenQ                | 2         | 2.7%    |
| ASUSTek Computer    | 2         | 2.7%    |
| ViewSonic           | 1         | 1.35%   |
| PANDA               | 1         | 1.35%   |
| HannStar            | 1         | 1.35%   |
| Dell                | 1         | 1.35%   |
| CSO                 | 1         | 1.35%   |
| AOC                 | 1         | 1.35%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch        | 2         | 2.7%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch       | 2         | 2.7%    |
| BOE LCD Monitor BOE0973 2560x1440 344x194mm 15.5-inch                  | 2         | 2.7%    |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                  | 2         | 2.7%    |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch         | 2         | 2.7%    |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x193mm 15.5-inch         | 2         | 2.7%    |
| ViewSonic LCD Monitor VSC1B35 1920x1080 530x300mm 24.0-inch            | 1         | 1.35%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                | 1         | 1.35%   |
| Sharp LQ140M1JW49 SHP1523 1920x1080 309x174mm 14.0-inch                | 1         | 1.35%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch                | 1         | 1.35%   |
| Sharp LCD Monitor SHP1515 1920x1200 336x210mm 15.6-inch                | 1         | 1.35%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                | 1         | 1.35%   |
| Samsung Electronics LCD Monitor SEC3157 1280x800 261x163mm 12.1-inch   | 1         | 1.35%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 340x190mm 15.3-inch   | 1         | 1.35%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch   | 1         | 1.35%   |
| Samsung Electronics LCD Monitor SDC415F 3840x2160 344x194mm 15.5-inch  | 1         | 1.35%   |
| Samsung Electronics LCD Monitor SAM07C5 1920x1080 1020x570mm 46.0-inch | 1         | 1.35%   |
| Samsung Electronics C27F591 SAM0D37 1920x1080 598x336mm 27.0-inch      | 1         | 1.35%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch                | 1         | 1.35%   |
| LG Display LCD Monitor LGD05E4 1920x1080 344x194mm 15.5-inch           | 1         | 1.35%   |
| LG Display LCD Monitor LGD05BE 1920x1080 382x215mm 17.3-inch           | 1         | 1.35%   |
| LG Display LCD Monitor LGD0532 1920x1080 344x194mm 15.5-inch           | 1         | 1.35%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch           | 1         | 1.35%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch           | 1         | 1.35%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch            | 1         | 1.35%   |
| Lenovo Q27q-10 LEN65F4 2560x1440 597x336mm 27.0-inch                   | 1         | 1.35%   |
| Lenovo LEN T34w-20 LEN61F3 3440x1440 800x330mm 34.1-inch               | 1         | 1.35%   |
| Hewlett-Packard E273q HPN3473 2560x1440 597x336mm 27.0-inch            | 1         | 1.35%   |
| Hewlett-Packard E232 HWP327A 1920x1080 509x286mm 23.0-inch             | 1         | 1.35%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch              | 1         | 1.35%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                  | 1         | 1.35%   |
| Goldstar E1942 GSM4C09 1366x768 410x230mm 18.5-inch                    | 1         | 1.35%   |
| Goldstar 23EA53 GSM59A9 1920x1080 510x290mm 23.1-inch                  | 1         | 1.35%   |
| Dell E170S DELA04A 1280x1024 338x270mm 17.0-inch                       | 1         | 1.35%   |
| CSO LCD Monitor CSO1609 2560x1600 345x215mm 16.0-inch                  | 1         | 1.35%   |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 381x214mm 17.2-inch       | 1         | 1.35%   |
| Chimei Innolux LCD Monitor CMN152E 1920x1080 344x193mm 15.5-inch       | 1         | 1.35%   |
| Chimei Innolux LCD Monitor CMN14F5 1920x1080 309x173mm 13.9-inch       | 1         | 1.35%   |
| Chimei Innolux LCD Monitor CMN14E7 1920x1080 309x173mm 13.9-inch       | 1         | 1.35%   |
| Chimei Innolux LCD Monitor CMN14D3 1920x1080 309x173mm 13.9-inch       | 1         | 1.35%   |
| Chimei Innolux LCD Monitor CMN140A 1920x1080 309x173mm 13.9-inch       | 1         | 1.35%   |
| BOE LCD Monitor BOE09B6 2560x1600 345x215mm 16.0-inch                  | 1         | 1.35%   |
| BOE LCD Monitor BOE0928 1920x1080 344x194mm 15.5-inch                  | 1         | 1.35%   |
| BOE LCD Monitor BOE0910 1920x1080 344x194mm 15.5-inch                  | 1         | 1.35%   |
| BOE LCD Monitor BOE0900 1920x1080 344x194mm 15.5-inch                  | 1         | 1.35%   |
| BOE LCD Monitor BOE08E2 1920x1080 344x194mm 15.5-inch                  | 1         | 1.35%   |
| BOE LCD Monitor BOE0898 1920x1080 294x165mm 13.3-inch                  | 1         | 1.35%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                  | 1         | 1.35%   |
| BOE LCD Monitor BOE086E 1920x1080 344x194mm 15.5-inch                  | 1         | 1.35%   |
| BOE LCD Monitor BOE084D 1920x1080 344x193mm 15.5-inch                  | 1         | 1.35%   |
| BOE LCD Monitor BOE0821 3840x2160 309x174mm 14.0-inch                  | 1         | 1.35%   |
| BOE LCD Monitor BOE0819 1920x1080 344x194mm 15.5-inch                  | 1         | 1.35%   |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                  | 1         | 1.35%   |
| BOE LCD Monitor BOE0718 1920x1080 309x173mm 13.9-inch                  | 1         | 1.35%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                  | 1         | 1.35%   |
| BenQ PD2500Q BNQ802A 2560x1440 553x311mm 25.0-inch                     | 1         | 1.35%   |
| BenQ EX2780Q BNQ7F76 2560x1440 597x336mm 27.0-inch                     | 1         | 1.35%   |
| AU Optronics LCD Monitor AUODF87 1920x1080 344x193mm 15.5-inch         | 1         | 1.35%   |
| AU Optronics LCD Monitor AUO683D 1920x1080 309x174mm 14.0-inch         | 1         | 1.35%   |
| AU Optronics LCD Monitor AUO32EB 3840x2160 344x193mm 15.5-inch         | 1         | 1.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 39        | 58.21%  |
| 2560x1440 (QHD)   | 6         | 8.96%   |
| 3840x2160 (4K)    | 5         | 7.46%   |
| 1366x768 (WXGA)   | 5         | 7.46%   |
| 3440x1440         | 2         | 2.99%   |
| 2560x1600         | 2         | 2.99%   |
| 2256x1504         | 2         | 2.99%   |
| 3840x2400         | 1         | 1.49%   |
| 1920x1200 (WUXGA) | 1         | 1.49%   |
| 1600x900 (HD+)    | 1         | 1.49%   |
| 1440x900 (WXGA+)  | 1         | 1.49%   |
| 1280x1024 (SXGA)  | 1         | 1.49%   |
| 1024x600          | 1         | 1.49%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 33        | 45.83%  |
| 13     | 10        | 13.89%  |
| 14     | 8         | 11.11%  |
| 27     | 5         | 6.94%   |
| 17     | 4         | 5.56%   |
| 34     | 2         | 2.78%   |
| 23     | 2         | 2.78%   |
| 16     | 2         | 2.78%   |
| 54     | 1         | 1.39%   |
| 25     | 1         | 1.39%   |
| 24     | 1         | 1.39%   |
| 18     | 1         | 1.39%   |
| 12     | 1         | 1.39%   |
| 10     | 1         | 1.39%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 50        | 71.43%  |
| 501-600     | 8         | 11.43%  |
| 201-300     | 5         | 7.14%   |
| 351-400     | 3         | 4.29%   |
| 701-800     | 2         | 2.86%   |
| 401-500     | 1         | 1.43%   |
| 1001-1500   | 1         | 1.43%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 53        | 84.13%  |
| 16/10 | 5         | 7.94%   |
| 3/2   | 2         | 3.17%   |
| 21/9  | 2         | 3.17%   |
| 5/4   | 1         | 1.59%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 32        | 44.44%  |
| 81-90          | 17        | 23.61%  |
| 301-350        | 5         | 6.94%   |
| 201-250        | 3         | 4.17%   |
| 121-130        | 3         | 4.17%   |
| 111-120        | 3         | 4.17%   |
| 351-500        | 2         | 2.78%   |
| 141-150        | 2         | 2.78%   |
| More than 1000 | 1         | 1.39%   |
| 71-80          | 1         | 1.39%   |
| 61-70          | 1         | 1.39%   |
| 41-50          | 1         | 1.39%   |
| 251-300        | 1         | 1.39%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 39        | 54.93%  |
| 101-120       | 10        | 14.08%  |
| 161-240       | 8         | 11.27%  |
| 51-100        | 8         | 11.27%  |
| More than 240 | 5         | 7.04%   |
| 1-50          | 1         | 1.41%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 48        | 78.69%  |
| 2     | 9         | 14.75%  |
| 3     | 3         | 4.92%   |
| 0     | 1         | 1.64%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 46        | 51.11%  |
| Realtek Semiconductor             | 27        | 30%     |
| Qualcomm Atheros                  | 5         | 5.56%   |
| MediaTek                          | 3         | 3.33%   |
| Samsung Electronics               | 2         | 2.22%   |
| ZTE WCDMA Technologies MSM        | 1         | 1.11%   |
| Lenovo                            | 1         | 1.11%   |
| ICS Advent                        | 1         | 1.11%   |
| Ericsson Business Mobile Networks | 1         | 1.11%   |
| D-Link                            | 1         | 1.11%   |
| Broadcom                          | 1         | 1.11%   |
| ASIX Electronics                  | 1         | 1.11%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 21        | 19.44%  |
| Intel Wi-Fi 6 AX200                                               | 9         | 8.33%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 6         | 5.56%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 4         | 3.7%    |
| Intel Tiger Lake PCH CNVi WiFi                                    | 4         | 3.7%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 4         | 3.7%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 3         | 2.78%   |
| Intel Wireless 8265 / 8275                                        | 3         | 2.78%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 3         | 2.78%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 2         | 1.85%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 1.85%   |
| Intel Wireless 8260                                               | 2         | 1.85%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 1.85%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 1.85%   |
| ZTE WCDMA MSM SCSI CD-ROM 2.31                                    | 1         | 0.93%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.93%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.93%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1         | 0.93%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.93%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.93%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.93%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 0.93%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 1         | 0.93%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.93%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.93%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 0.93%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.93%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.93%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 0.93%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 0.93%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.93%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 0.93%   |
| Intel Wireless-AC 9260                                            | 1         | 0.93%   |
| Intel Wireless 7265                                               | 1         | 0.93%   |
| Intel Wireless 3160                                               | 1         | 0.93%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 1         | 0.93%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.93%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.93%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.93%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.93%   |
| Intel Ethernet Connection (5) I219-V                              | 1         | 0.93%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.93%   |
| Intel Ethernet Connection (14) I219-V                             | 1         | 0.93%   |
| Intel Ethernet Connection (14) I219-LM                            | 1         | 0.93%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 0.93%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 0.93%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 1         | 0.93%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 1         | 0.93%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.93%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 0.93%   |
| ICS Advent DM9601 Fast Ethernet Adapter                           | 1         | 0.93%   |
| Ericsson Business Mobile Networks F5521gw                         | 1         | 0.93%   |
| D-Link 802.11 n WLAN                                              | 1         | 0.93%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1         | 0.93%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 0.93%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 45        | 73.77%  |
| Realtek Semiconductor | 9         | 14.75%  |
| Qualcomm Atheros      | 3         | 4.92%   |
| MediaTek              | 3         | 4.92%   |
| D-Link                | 1         | 1.64%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 9         | 14.75%  |
| Intel Cannon Lake PCH CNVi WiFi                                | 6         | 9.84%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 4         | 6.56%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 4         | 6.56%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 4         | 6.56%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 3         | 4.92%   |
| Intel Wireless 8265 / 8275                                     | 3         | 4.92%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 3         | 4.92%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 2         | 3.28%   |
| Intel Wireless 8260                                            | 2         | 3.28%   |
| Intel Wi-Fi 6 AX201                                            | 2         | 3.28%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 2         | 3.28%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1         | 1.64%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.64%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 1.64%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.64%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 1         | 1.64%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 1         | 1.64%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 1.64%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 1.64%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 1.64%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 1.64%   |
| Intel Wireless-AC 9260                                         | 1         | 1.64%   |
| Intel Wireless 7265                                            | 1         | 1.64%   |
| Intel Wireless 3160                                            | 1         | 1.64%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 1         | 1.64%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 1         | 1.64%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 1.64%   |
| D-Link 802.11 n WLAN                                           | 1         | 1.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 24        | 52.17%  |
| Intel                      | 12        | 26.09%  |
| Qualcomm Atheros           | 3         | 6.52%   |
| Samsung Electronics        | 2         | 4.35%   |
| ZTE WCDMA Technologies MSM | 1         | 2.17%   |
| Lenovo                     | 1         | 2.17%   |
| ICS Advent                 | 1         | 2.17%   |
| Broadcom                   | 1         | 2.17%   |
| ASIX Electronics           | 1         | 2.17%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 21        | 45.65%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 4.35%   |
| ZTE WCDMA MSM SCSI CD-ROM 2.31                                    | 1         | 2.17%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 2.17%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 2.17%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 2.17%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 2.17%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 2.17%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 2.17%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 2.17%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 2.17%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 2.17%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 2.17%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 2.17%   |
| Intel Ethernet Connection (5) I219-V                              | 1         | 2.17%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 2.17%   |
| Intel Ethernet Connection (14) I219-V                             | 1         | 2.17%   |
| Intel Ethernet Connection (14) I219-LM                            | 1         | 2.17%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 2.17%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 2.17%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 2.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 2.17%   |
| ICS Advent DM9601 Fast Ethernet Adapter                           | 1         | 2.17%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1         | 2.17%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 2.17%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 60        | 58.25%  |
| Ethernet | 42        | 40.78%  |
| Modem    | 1         | 0.97%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 52        | 82.54%  |
| Ethernet | 11        | 17.46%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 38        | 63.33%  |
| 1     | 21        | 35%     |
| 3     | 1         | 1.67%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 52        | 81.25%  |
| Yes  | 12        | 18.75%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 41        | 75.93%  |
| Realtek Semiconductor | 6         | 11.11%  |
| IMC Networks          | 3         | 5.56%   |
| Toshiba               | 1         | 1.85%   |
| Foxconn / Hon Hai     | 1         | 1.85%   |
| Broadcom              | 1         | 1.85%   |
| ASUSTek Computer      | 1         | 1.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                         | 12        | 22.22%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 9         | 16.67%  |
| Intel AX200 Bluetooth                          | 9         | 16.67%  |
| Intel Bluetooth wireless interface             | 6         | 11.11%  |
| Realtek Bluetooth Radio                        | 4         | 7.41%   |
| Intel AX210 Bluetooth                          | 4         | 7.41%   |
| IMC Networks Wireless_Device                   | 2         | 3.7%    |
| Toshiba RT Bluetooth Radio                     | 1         | 1.85%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter        | 1         | 1.85%   |
| Realtek  Bluetooth 4.2 Adapter                 | 1         | 1.85%   |
| Intel Wireless-AC 9260 Bluetooth Adapter       | 1         | 1.85%   |
| IMC Networks Bluetooth Device                  | 1         | 1.85%   |
| Foxconn / Hon Hai Wireless_Device              | 1         | 1.85%   |
| Broadcom HP Portable SoftSailing               | 1         | 1.85%   |
| ASUS Broadcom Bluetooth 2.1                    | 1         | 1.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 41        | 50%     |
| AMD                 | 20        | 24.39%  |
| Nvidia              | 17        | 20.73%  |
| Razer USA           | 1         | 1.22%   |
| Lenovo              | 1         | 1.22%   |
| Kingston Technology | 1         | 1.22%   |
| ACTIONS             | 1         | 1.22%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 17        | 16.04%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 11        | 10.38%  |
| Intel Cannon Lake PCH cAVS                                                 | 9         | 8.49%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 5         | 4.72%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4         | 3.77%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 4         | 3.77%   |
| Intel Comet Lake PCH-LP cAVS                                               | 4         | 3.77%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 3.77%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3         | 2.83%   |
| Nvidia GP106 High Definition Audio Controller                              | 3         | 2.83%   |
| Nvidia Audio device                                                        | 3         | 2.83%   |
| Intel Sunrise Point-LP HD Audio                                            | 3         | 2.83%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 3         | 2.83%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 1.89%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 1.89%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 1.89%   |
| Intel CM238 HD Audio Controller                                            | 2         | 1.89%   |
| Intel Broadwell-U Audio Controller                                         | 2         | 1.89%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 2         | 1.89%   |
| AMD Navi 10 HDMI Audio                                                     | 2         | 1.89%   |
| Razer USA Razer Kraken X USB                                               | 1         | 0.94%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.94%   |
| Nvidia TU104 HD Audio Controller                                           | 1         | 0.94%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 0.94%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 0.94%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                               | 1         | 0.94%   |
| Kingston Technology HyperX 7.1 Audio                                       | 1         | 0.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 0.94%   |
| Intel USB PnP Sound Device                                                 | 1         | 0.94%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 0.94%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 0.94%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1         | 0.94%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 0.94%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 0.94%   |
| AMD Wrestler HDMI Audio                                                    | 1         | 0.94%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 1         | 0.94%   |
| AMD FCH Azalia Controller                                                  | 1         | 0.94%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1         | 0.94%   |
| ACTIONS EDIFIER M380                                                       | 1         | 0.94%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 28        | 41.18%  |
| SK hynix            | 17        | 25%     |
| Micron Technology   | 7         | 10.29%  |
| Kingston            | 4         | 5.88%   |
| Crucial             | 4         | 5.88%   |
| A-DATA Technology   | 2         | 2.94%   |
| Unknown             | 1         | 1.47%   |
| Patriot             | 1         | 1.47%   |
| Magnum Tech         | 1         | 1.47%   |
| G.Skill             | 1         | 1.47%   |
| Corsair             | 1         | 1.47%   |
| Unknown             | 1         | 1.47%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s        | 3         | 4.35%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 3         | 4.35%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 2.9%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 2.9%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 2.9%    |
| SK hynix RAM H9HCNNNCPMALHR-NEE 8GB Row Of Chips LPDDR4 4800MT/s | 2         | 2.9%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 2.9%    |
| Samsung RAM M471A2G44AM0-CWE 16384MB SODIMM DDR4 3200MT/s        | 2         | 2.9%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 2.9%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 2.9%    |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 2.9%    |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 2.9%    |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 2         | 2.9%    |
| Unknown RAM Module 1GB SODIMM SDRAM                              | 1         | 1.45%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.45%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s          | 1         | 1.45%   |
| SK hynix RAM HMAA2GS6AJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 1.45%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.45%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 1         | 1.45%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.45%   |
| Samsung RAM Module 8GB SODIMM DDR3 1333MT/s                      | 1         | 1.45%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 2133MT/s              | 1         | 1.45%   |
| Samsung RAM M471B5773CHS-CK0 2GB SODIMM DDR3 1600MT/s            | 1         | 1.45%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.45%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.45%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 1         | 1.45%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.45%   |
| Samsung RAM M471A2K43DB1-CTD 16384MB SODIMM DDR4 2667MT/s        | 1         | 1.45%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s           | 1         | 1.45%   |
| Samsung RAM M471A2G43BB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.45%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.45%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 1         | 1.45%   |
| Samsung RAM K4E6E304EB-EGCG 4096MB Row Of Chips LPDDR3 2133MT/s  | 1         | 1.45%   |
| Samsung RAM K4A8G165WC-BCTD 4GB SODIMM DDR4 2667MT/s             | 1         | 1.45%   |
| Patriot RAM PSD416G24002S 16GB SODIMM DDR4 2667MT/s              | 1         | 1.45%   |
| Micron RAM Module 16GB SODIMM DDR4 2667MT/s                      | 1         | 1.45%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8192MB SODIMM DDR4 2667MT/s          | 1         | 1.45%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 1         | 1.45%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 1         | 1.45%   |
| Micron RAM 16ATF2G64HZ-3G2J1 16GB SODIMM DDR4 3200MT/s           | 1         | 1.45%   |
| Magnum Tech RAM MAGNUMTECH 4GB SODIMM DDR3 1600MT/s              | 1         | 1.45%   |
| Kingston RAM KF3200C20S4/32GX 32GB SODIMM DDR4 3200MT/s          | 1         | 1.45%   |
| Kingston RAM HP26D4S9S8HJ-8 8GB SODIMM DDR4 2667MT/s             | 1         | 1.45%   |
| Kingston RAM 99U5624-013.A00G 8GB SODIMM DDR4 2400MT/s           | 1         | 1.45%   |
| Kingston RAM 9905700-053.A00G 8GB SODIMM DDR4 3200MT/s           | 1         | 1.45%   |
| G.Skill RAM F4-3200C 8GB SODIMM DDR4 1067MT/s                    | 1         | 1.45%   |
| Crucial RAM CT8G4SFS8266.M8FE 8GB SODIMM DDR4 2667MT/s           | 1         | 1.45%   |
| Crucial RAM CT8G4SFRA32A.M8FRS 8GB SODIMM DDR4 3200MT/s          | 1         | 1.45%   |
| Crucial RAM CT8G4SFRA32A.C8FR 8GB SODIMM DDR4 3200MT/s           | 1         | 1.45%   |
| Crucial RAM CT32G4SFD832A.C16FE 32GB SODIMM DDR4 3200MT/s        | 1         | 1.45%   |
| Corsair RAM CMSX64GX4M2A2933C19 32GB SODIMM DDR4 2933MT/s        | 1         | 1.45%   |
| A-DATA RAM Module 16GB SODIMM DDR4 2400MT/s                      | 1         | 1.45%   |
| A-DATA RAM DOVF1B163GEG 2GB SODIMM DDR 667MT/s                   | 1         | 1.45%   |
| Unknown                                                          | 1         | 1.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 46        | 77.97%  |
| DDR3   | 7         | 11.86%  |
| LPDDR4 | 2         | 3.39%   |
| LPDDR3 | 2         | 3.39%   |
| SDRAM  | 1         | 1.69%   |
| DDR    | 1         | 1.69%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 53        | 88.33%  |
| Row Of Chips | 6         | 10%     |
| Chip         | 1         | 1.67%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 36        | 58.06%  |
| 16384 | 11        | 17.74%  |
| 4096  | 7         | 11.29%  |
| 32768 | 4         | 6.45%   |
| 2048  | 2         | 3.23%   |
| 1024  | 1         | 1.61%   |
| 512   | 1         | 1.61%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 25        | 40.32%  |
| 2667    | 19        | 30.65%  |
| 1600    | 6         | 9.68%   |
| 4800    | 2         | 3.23%   |
| 2400    | 2         | 3.23%   |
| 2133    | 2         | 3.23%   |
| 2933    | 1         | 1.61%   |
| 1333    | 1         | 1.61%   |
| 1067    | 1         | 1.61%   |
| 667     | 1         | 1.61%   |
| 533     | 1         | 1.61%   |
| Unknown | 1         | 1.61%   |

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


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 11        | 23.4%   |
| IMC Networks                  | 9         | 19.15%  |
| Realtek Semiconductor         | 5         | 10.64%  |
| Acer                          | 5         | 10.64%  |
| Lite-On Technology            | 4         | 8.51%   |
| Sunplus Innovation Technology | 3         | 6.38%   |
| Microdia                      | 3         | 6.38%   |
| Luxvisions Innotech Limited   | 3         | 6.38%   |
| Quanta                        | 2         | 4.26%   |
| Syntek                        | 1         | 2.13%   |
| Alcor Micro                   | 1         | 2.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                       | 7         | 14.89%  |
| Chicony Integrated Camera                            | 5         | 10.64%  |
| Microdia Integrated_Webcam_HD                        | 3         | 6.38%   |
| Acer Integrated Camera                               | 3         | 6.38%   |
| Sunplus Integrated_Webcam_HD                         | 2         | 4.26%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 2         | 4.26%   |
| Lite-On HP Wide Vision HD Camera                     | 2         | 4.26%   |
| Chicony HD User Facing                               | 2         | 4.26%   |
| Syntek Integrated Camera                             | 1         | 2.13%   |
| Sunplus HP Wide Vision HD                            | 1         | 2.13%   |
| Realtek USB Camera                                   | 1         | 2.13%   |
| Realtek Laptop Camera                                | 1         | 2.13%   |
| Realtek Integrated_Webcam_HD                         | 1         | 2.13%   |
| Realtek Integrated Webcam HD                         | 1         | 2.13%   |
| Realtek Integrated Camera                            | 1         | 2.13%   |
| Quanta HD Webcam                                     | 1         | 2.13%   |
| Quanta HD Camera                                     | 1         | 2.13%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 2.13%   |
| Lite-On TOSHIBA Web Camera - HD                      | 1         | 2.13%   |
| Lite-On Integrated Camera                            | 1         | 2.13%   |
| IMC Networks USB2.0 UVC 1.3M WebCam                  | 1         | 2.13%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 1         | 2.13%   |
| Chicony XiaoMi USB 2.0 Webcam                        | 1         | 2.13%   |
| Chicony USB2.0 Camera                                | 1         | 2.13%   |
| Chicony USB 2.0 Camera                               | 1         | 2.13%   |
| Chicony HP Truevision HD                             | 1         | 2.13%   |
| Alcor Micro 720P USB Webcam                          | 1         | 2.13%   |
| Acer NEC HD WebCam                                   | 1         | 2.13%   |
| Acer HD Webcam                                       | 1         | 2.13%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 3         | 33.33%  |
| Elan Microelectronics      | 3         | 33.33%  |
| Validity Sensors           | 2         | 22.22%  |
| Shenzhen Goodix Technology | 1         | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader | 2         | 22.22%  |
| Elan ELAN:Fingerprint                             | 2         | 22.22%  |
| Validity Sensors VFS 5011 fingerprint sensor      | 1         | 11.11%  |
| Validity Sensors Synaptics WBDI                   | 1         | 11.11%  |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 1         | 11.11%  |
| Shenzhen Goodix  FingerPrint Device               | 1         | 11.11%  |
| Elan ELAN:ARM-M4                                  | 1         | 11.11%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 3         | 50%     |
| Alcor Micro | 2         | 33.33%  |
| O2 Micro    | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Broadcom 58200                      | 2         | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader | 2         | 33.33%  |
| O2 Micro Oz776 SmartCard Reader     | 1         | 16.67%  |
| Broadcom 5880                       | 1         | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 29        | 46.77%  |
| 1     | 15        | 24.19%  |
| 2     | 7         | 11.29%  |
| 3     | 6         | 9.68%   |
| 4     | 4         | 6.45%   |
| 6     | 1         | 1.61%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Camera                   | 10        | 15.38%  |
| Fingerprint reader       | 9         | 13.85%  |
| Communication controller | 8         | 12.31%  |
| Bluetooth                | 7         | 10.77%  |
| Chipcard                 | 6         | 9.23%   |
| Graphics card            | 5         | 7.69%   |
| Net/wireless             | 4         | 6.15%   |
| Multimedia controller    | 4         | 6.15%   |
| Network                  | 3         | 4.62%   |
| Sound                    | 2         | 3.08%   |
| Firewire controller      | 2         | 3.08%   |
| Card reader              | 2         | 3.08%   |
| Storage/ata              | 1         | 1.54%   |
| Net/ethernet             | 1         | 1.54%   |
| Modem                    | 1         | 1.54%   |

