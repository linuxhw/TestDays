Devuan - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for Devuan.

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

Total: 114

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | XPS M1530                   | [b24e393bbb](https://linux-hardware.org/?probe=b24e393bbb) | Sep 23, 2023 |
| Dell          | Inspiron 3583               | [56cd0e05e8](https://linux-hardware.org/?probe=56cd0e05e8) | Sep 22, 2023 |
| PC Special... | P7xxTM1                     | [2bdbc2f2e7](https://linux-hardware.org/?probe=2bdbc2f2e7) | Sep 12, 2023 |
| Apple         | MacBookPro8,2               | [f23bb97453](https://linux-hardware.org/?probe=f23bb97453) | Sep 11, 2023 |
| Sony          | VGN-FZ140E                  | [361226919e](https://linux-hardware.org/?probe=361226919e) | Sep 11, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | [61906f4e91](https://linux-hardware.org/?probe=61906f4e91) | Sep 07, 2023 |
| Dell          | Inspiron 3585               | [89a0e93fd5](https://linux-hardware.org/?probe=89a0e93fd5) | Sep 05, 2023 |
| Intel         | powered classmate PC        | [f852524db2](https://linux-hardware.org/?probe=f852524db2) | Sep 01, 2023 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [44e328b3a0](https://linux-hardware.org/?probe=44e328b3a0) | Aug 24, 2023 |
| Lenovo        | ThinkPad X390 20Q1A005CD    | [c299d4ad92](https://linux-hardware.org/?probe=c299d4ad92) | Aug 15, 2023 |
| Lenovo        | ThinkPad T560 20FJS1J200    | [f0d90b715d](https://linux-hardware.org/?probe=f0d90b715d) | Aug 15, 2023 |
| ASUSTek       | T200TA                      | [affc999457](https://linux-hardware.org/?probe=affc999457) | Aug 12, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | [67febbf0c0](https://linux-hardware.org/?probe=67febbf0c0) | Jul 27, 2023 |
| Samsung       | 550XDA                      | [c298263c6c](https://linux-hardware.org/?probe=c298263c6c) | Jul 22, 2023 |
| Dell          | Latitude E5500              | [03798c7840](https://linux-hardware.org/?probe=03798c7840) | Jul 10, 2023 |
| Nokia         | N900                        | [7728c85b90](https://linux-hardware.org/?probe=7728c85b90) | Jul 06, 2023 |
| HP            | EliteBook 840 G6            | [d072001450](https://linux-hardware.org/?probe=d072001450) | Jul 04, 2023 |
| Toshiba       | Satellite L300              | [8b04801d40](https://linux-hardware.org/?probe=8b04801d40) | Jun 27, 2023 |
| Lenovo        | ThinkPad T410 2537DA3       | [067b7f26a2](https://linux-hardware.org/?probe=067b7f26a2) | Jun 25, 2023 |
| HP            | EliteBook 840 G6            | [82c9c200bc](https://linux-hardware.org/?probe=82c9c200bc) | Jun 20, 2023 |
| MSI           | Bravo 15 A4DDR              | [0e9ccef97f](https://linux-hardware.org/?probe=0e9ccef97f) | May 27, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | [54f07f7d96](https://linux-hardware.org/?probe=54f07f7d96) | May 12, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [0d2ac684c8](https://linux-hardware.org/?probe=0d2ac684c8) | May 08, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [c67960852a](https://linux-hardware.org/?probe=c67960852a) | May 06, 2023 |
| HUAWEI        | HN-WX9X                     | [d07874c829](https://linux-hardware.org/?probe=d07874c829) | Apr 24, 2023 |
| Lenovo        | S20-30 20421                | [b9846b05e7](https://linux-hardware.org/?probe=b9846b05e7) | Apr 22, 2023 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [96e067f5c8](https://linux-hardware.org/?probe=96e067f5c8) | Apr 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | [549f922cf6](https://linux-hardware.org/?probe=549f922cf6) | Apr 13, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | [a9aa9ab39f](https://linux-hardware.org/?probe=a9aa9ab39f) | Apr 13, 2023 |
| Google        | Cyan                        | [f32e15dfef](https://linux-hardware.org/?probe=f32e15dfef) | Apr 09, 2023 |
| Dell          | G5 5505                     | [2552b456b6](https://linux-hardware.org/?probe=2552b456b6) | Mar 29, 2023 |
| ASUSTek       | G750JM                      | [98ba3a9ce6](https://linux-hardware.org/?probe=98ba3a9ce6) | Mar 25, 2023 |
| Google        | Bluebird                    | [2d18088551](https://linux-hardware.org/?probe=2d18088551) | Mar 15, 2023 |
| Dell          | Latitude E6230              | [49a9844be8](https://linux-hardware.org/?probe=49a9844be8) | Mar 15, 2023 |
| Dell          | Latitude E6440              | [76a537c18e](https://linux-hardware.org/?probe=76a537c18e) | Mar 14, 2023 |
| Unknown       | Unknown                     | [1f89daceb8](https://linux-hardware.org/?probe=1f89daceb8) | Feb 20, 2023 |
| HP            | ProBook 640 G1              | [d0319bdf17](https://linux-hardware.org/?probe=d0319bdf17) | Feb 09, 2023 |
| Lenovo        | ThinkPad T560 20FJS1J200    | [de713cedce](https://linux-hardware.org/?probe=de713cedce) | Jan 21, 2023 |
| Acer          | Aspire E1-572G              | [360a177e77](https://linux-hardware.org/?probe=360a177e77) | Jan 14, 2023 |
| Dell          | Inspiron 15 3511            | [f4349052b8](https://linux-hardware.org/?probe=f4349052b8) | Jan 06, 2023 |
| Dell          | XPS 13 9370                 | [1f72002986](https://linux-hardware.org/?probe=1f72002986) | Dec 29, 2022 |
| HP            | Laptop 14-df0xxx            | [1d9edd6c97](https://linux-hardware.org/?probe=1d9edd6c97) | Dec 25, 2022 |
| HP            | 250 G8 Notebook PC          | [ed3886b135](https://linux-hardware.org/?probe=ed3886b135) | Dec 02, 2022 |
| Dell          | Latitude E6530              | [e40986d2fb](https://linux-hardware.org/?probe=e40986d2fb) | Nov 22, 2022 |
| Dell          | Latitude E6530              | [14debbe3e5](https://linux-hardware.org/?probe=14debbe3e5) | Nov 22, 2022 |
| Lenovo        | G50-30 80G0                 | [be4f638bc7](https://linux-hardware.org/?probe=be4f638bc7) | Nov 21, 2022 |
| HP            | Laptop 15-bs2xx             | [7254534946](https://linux-hardware.org/?probe=7254534946) | Oct 20, 2022 |
| Lenovo        | ThinkPad T550 20CJS1VD01    | [97d1b5e6c5](https://linux-hardware.org/?probe=97d1b5e6c5) | Sep 30, 2022 |
| Lenovo        | ThinkPad T440p              | [270cf10219](https://linux-hardware.org/?probe=270cf10219) | Sep 25, 2022 |
| Lenovo        | ThinkPad T440p              | [bf397424f3](https://linux-hardware.org/?probe=bf397424f3) | Sep 18, 2022 |
| Lenovo        | ThinkPad T550 20CJS1VD01    | [1bcc13e6b4](https://linux-hardware.org/?probe=1bcc13e6b4) | Aug 15, 2022 |
| CCE           | Capella & IbexPeak-M Chi... | [defafd4f0b](https://linux-hardware.org/?probe=defafd4f0b) | Aug 10, 2022 |
| CCE           | Capella & IbexPeak-M Chi... | [389bef188c](https://linux-hardware.org/?probe=389bef188c) | Aug 10, 2022 |
| Sony          | VPCEE23FX                   | [b4108910d3](https://linux-hardware.org/?probe=b4108910d3) | Jul 25, 2022 |
| Toshiba       | Satellite Pro A50-C         | [a94461714d](https://linux-hardware.org/?probe=a94461714d) | Jul 18, 2022 |
| Lenovo        | V310-14ISK 80SX             | [6dcb934555](https://linux-hardware.org/?probe=6dcb934555) | Jul 17, 2022 |
| Dell          | Latitude 7280               | [75ce6d31bc](https://linux-hardware.org/?probe=75ce6d31bc) | Jul 14, 2022 |
| MSI           | Modern 15 A5M               | [40c6c77f2c](https://linux-hardware.org/?probe=40c6c77f2c) | Jul 13, 2022 |
| Dell          | Latitude E7240              | [045554b70c](https://linux-hardware.org/?probe=045554b70c) | Jul 08, 2022 |
| Lenovo        | ThinkPad T430 2349I46       | [3a7df4ea17](https://linux-hardware.org/?probe=3a7df4ea17) | Jun 20, 2022 |
| HP            | Laptop 17-cp0xxx            | [001634b95b](https://linux-hardware.org/?probe=001634b95b) | Jun 17, 2022 |
| Dell          | Latitude E6430              | [95b7617708](https://linux-hardware.org/?probe=95b7617708) | Jun 05, 2022 |
| Acer          | Aspire E5-553G              | [2d4c950e2f](https://linux-hardware.org/?probe=2d4c950e2f) | May 25, 2022 |
| Acer          | Aspire E5-553G              | [73139cdb17](https://linux-hardware.org/?probe=73139cdb17) | May 25, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [2717caa7f5](https://linux-hardware.org/?probe=2717caa7f5) | Apr 25, 2022 |
| HP            | Notebook                    | [966668f0c0](https://linux-hardware.org/?probe=966668f0c0) | Apr 17, 2022 |
| Lenovo        | ThinkPad T470s 20HGS00P0... | [2c9878c68b](https://linux-hardware.org/?probe=2c9878c68b) | Apr 13, 2022 |
| Dell          | Latitude E5540              | [0948114af7](https://linux-hardware.org/?probe=0948114af7) | Mar 03, 2022 |
| Lenovo        | ThinkPad T550 20CJS1VD01    | [a3aed9d375](https://linux-hardware.org/?probe=a3aed9d375) | Mar 03, 2022 |
| ASUSTek       | K55VJ                       | [562262b9eb](https://linux-hardware.org/?probe=562262b9eb) | Jan 22, 2022 |
| ASUSTek       | X555LJ                      | [9fbdf4dfc2](https://linux-hardware.org/?probe=9fbdf4dfc2) | Jan 17, 2022 |
| Lenovo        | ThinkPad T420 4180AG3       | [2c3cd27ad2](https://linux-hardware.org/?probe=2c3cd27ad2) | Jan 16, 2022 |
| Notebook      | W230ST                      | [3dacf0aea8](https://linux-hardware.org/?probe=3dacf0aea8) | Jan 15, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [899cb98778](https://linux-hardware.org/?probe=899cb98778) | Dec 06, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [d860ff9858](https://linux-hardware.org/?probe=d860ff9858) | Nov 30, 2021 |
| Fujitsu       | LIFEBOOK U7510              | [d43a6a6bb8](https://linux-hardware.org/?probe=d43a6a6bb8) | Nov 29, 2021 |
| Lenovo        | ThinkPad T550 20CJS1VD01    | [55689e67b3](https://linux-hardware.org/?probe=55689e67b3) | Oct 27, 2021 |
| Lenovo        | ThinkPad X230 2325DE0       | [991007e92a](https://linux-hardware.org/?probe=991007e92a) | Oct 13, 2021 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [7f1b3371a9](https://linux-hardware.org/?probe=7f1b3371a9) | Oct 03, 2021 |
| Toshiba       | Satellite M40X              | [61fea93e97](https://linux-hardware.org/?probe=61fea93e97) | Oct 01, 2021 |
| Acer          | Aspire 5250                 | [ae41600fd9](https://linux-hardware.org/?probe=ae41600fd9) | Sep 24, 2021 |
| IBM           | ThinkPad T41p 2373GHG       | [04747e3df4](https://linux-hardware.org/?probe=04747e3df4) | Sep 19, 2021 |
| IBM           | ThinkPad T41p 2373GHG       | [134b90f474](https://linux-hardware.org/?probe=134b90f474) | Sep 18, 2021 |
| Lenovo        | ThinkPad X200 74585FU       | [04256a6e0a](https://linux-hardware.org/?probe=04256a6e0a) | Aug 25, 2021 |
| Lenovo        | ThinkPad X200 74585FU       | [dffbcc492c](https://linux-hardware.org/?probe=dffbcc492c) | Aug 25, 2021 |
| ASUSTek       | K52F                        | [643e3cc4b3](https://linux-hardware.org/?probe=643e3cc4b3) | Aug 13, 2021 |
| MSI           | MS-1688                     | [0ae772d66b](https://linux-hardware.org/?probe=0ae772d66b) | Jul 30, 2021 |
| Lenovo        | ThinkPad X220 429053G       | [5f553465bf](https://linux-hardware.org/?probe=5f553465bf) | Jul 29, 2021 |
| Acer          | Extensa 215-51K             | [1c49c2f4d0](https://linux-hardware.org/?probe=1c49c2f4d0) | Jul 26, 2021 |
| Lenovo        | ThinkPad X250 20CLS7WY04    | [fc77801294](https://linux-hardware.org/?probe=fc77801294) | Jun 07, 2021 |
| Lenovo        | ThinkPad T550 20CJS1VD01    | [aef4e323e2](https://linux-hardware.org/?probe=aef4e323e2) | Jun 06, 2021 |
| ASUSTek       | K55VJ                       | [6fa86f9d25](https://linux-hardware.org/?probe=6fa86f9d25) | Apr 27, 2021 |
| ASUSTek       | K55VJ                       | [aef1b6c71f](https://linux-hardware.org/?probe=aef1b6c71f) | Apr 17, 2021 |
| HP            | ProBook 6475b               | [74b0fa77b5](https://linux-hardware.org/?probe=74b0fa77b5) | Apr 14, 2021 |
| Fujitsu Si... | AMILO Xi 1546               | [22a53eeb74](https://linux-hardware.org/?probe=22a53eeb74) | Apr 03, 2021 |
| Teclast       | F6 Plus                     | [26ac25681a](https://linux-hardware.org/?probe=26ac25681a) | Jan 08, 2021 |
| Dell          | Precision 7530              | [8e0ee186a3](https://linux-hardware.org/?probe=8e0ee186a3) | Dec 04, 2020 |
| Lenovo        | ThinkPad X60 1707YF8        | [bcdd451de1](https://linux-hardware.org/?probe=bcdd451de1) | Oct 31, 2020 |
| Nokia         | N900                        | [7960cb48cc](https://linux-hardware.org/?probe=7960cb48cc) | Oct 05, 2020 |
| Lenovo        | ThinkPad X230 23247S0       | [f313b0bf1b](https://linux-hardware.org/?probe=f313b0bf1b) | Oct 01, 2020 |
| Dell          | Precision 7530              | [e6c6dd2734](https://linux-hardware.org/?probe=e6c6dd2734) | Sep 26, 2020 |
| Dell          | Precision 7530              | [81e9306141](https://linux-hardware.org/?probe=81e9306141) | Sep 26, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [3d241c321f](https://linux-hardware.org/?probe=3d241c321f) | Sep 20, 2020 |
| ASUSTek       | K52F                        | [cef5147eeb](https://linux-hardware.org/?probe=cef5147eeb) | Aug 30, 2020 |
| Acer          | Aspire 5732Z                | [c4cb936b69](https://linux-hardware.org/?probe=c4cb936b69) | Aug 30, 2020 |
| Toshiba       | Satellite L655              | [6251a9111f](https://linux-hardware.org/?probe=6251a9111f) | Aug 30, 2020 |
| HP            | Pavilion 11 x360 PC         | [0c85729a27](https://linux-hardware.org/?probe=0c85729a27) | Aug 30, 2020 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [358be6b820](https://linux-hardware.org/?probe=358be6b820) | Jul 28, 2020 |
| Lenovo        | IdeaPad Z370                | [51e3108708](https://linux-hardware.org/?probe=51e3108708) | Jun 28, 2020 |
| Dell          | Latitude 5501               | [94ec8d2a1d](https://linux-hardware.org/?probe=94ec8d2a1d) | Jun 28, 2020 |
| Lenovo        | IdeaPad Z370                | [76c985ed75](https://linux-hardware.org/?probe=76c985ed75) | Jun 27, 2020 |
| Dell          | Latitude E7250              | [c2ca61e7bf](https://linux-hardware.org/?probe=c2ca61e7bf) | Jun 23, 2020 |
| Dell          | Inspiron 1564               | [b80e556643](https://linux-hardware.org/?probe=b80e556643) | Feb 02, 2020 |
| MTC           | Montara-GML                 | [227bf1ba1d](https://linux-hardware.org/?probe=227bf1ba1d) | Dec 07, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Devuan 4                | 47        | 49.47%  |
| Devuan 5                | 20        | 21.05%  |
| Devuan 3                | 14        | 14.74%  |
| Devuan Testing/unstable | 8         | 8.42%   |
| Devuan                  | 4         | 4.21%   |
| Devuan 3.0              | 1         | 1.05%   |
| Devuan 2.1              | 1         | 1.05%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Devuan | 89        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Notebooks | Percent |
|-----------------------|-----------|---------|
| 5.10.0-21-amd64       | 8         | 7.84%   |
| 6.1.0-11-amd64        | 5         | 4.9%    |
| 5.10.0-23-amd64       | 5         | 4.9%    |
| 5.10.0-16-amd64       | 5         | 4.9%    |
| 5.10.0-9-amd64        | 4         | 3.92%   |
| 5.10.0-13-amd64       | 4         | 3.92%   |
| 4.19.0-9-amd64        | 4         | 3.92%   |
| 5.7.0-2-amd64         | 3         | 2.94%   |
| 5.10.0-8-amd64        | 3         | 2.94%   |
| 5.10.0-18-amd64       | 3         | 2.94%   |
| 5.10.0-10-amd64       | 3         | 2.94%   |
| 6.1.0-6-amd64         | 2         | 1.96%   |
| 6.1.0-12-amd64        | 2         | 1.96%   |
| 6.1.0-0.deb11.7-amd64 | 2         | 1.96%   |
| 5.18.0-2-amd64        | 2         | 1.96%   |
| 5.10.0-25-amd64       | 2         | 1.96%   |
| 5.10.0-20-amd64       | 2         | 1.96%   |
| 5.10.0-19-amd64       | 2         | 1.96%   |
| 5.10.0-11-amd64       | 2         | 1.96%   |
| 4.19.0-17-amd64       | 2         | 1.96%   |
| 4.19.0-16-amd64       | 2         | 1.96%   |
| 4.19.0-14-amd64       | 2         | 1.96%   |
| 6.1.9                 | 1         | 0.98%   |
| 6.1.25                | 1         | 0.98%   |
| 6.1.0-9-amd64         | 1         | 0.98%   |
| 6.1.0-7-amd64         | 1         | 0.98%   |
| 6.1.0-10-amd64        | 1         | 0.98%   |
| 6.1.0-0.deb11.6-amd64 | 1         | 0.98%   |
| 6.0.0-5-amd64         | 1         | 0.98%   |
| 6.0.0-2-amd64         | 1         | 0.98%   |
| 6.0.0-0.deb11.6-amd64 | 1         | 0.98%   |
| 5.9.0-4-amd64         | 1         | 0.98%   |
| 5.8.0-1-amd64         | 1         | 0.98%   |
| 5.7.0-0.bpo.2-amd64   | 1         | 0.98%   |
| 5.6.0-2-amd64         | 1         | 0.98%   |
| 5.19.0-2-amd64        | 1         | 0.98%   |
| 5.18.0-1-amd64        | 1         | 0.98%   |
| 5.15.5-xanmod1        | 1         | 0.98%   |
| 5.15.0-2-amd64        | 1         | 0.98%   |
| 5.14.0-4-amd64        | 1         | 0.98%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 46        | 47.42%  |
| 6.1.0   | 13        | 13.4%   |
| 4.19.0  | 13        | 13.4%   |
| 5.7.0   | 4         | 4.12%   |
| 4.9.0   | 4         | 4.12%   |
| 6.0.0   | 3         | 3.09%   |
| 5.18.0  | 3         | 3.09%   |
| 6.1.9   | 1         | 1.03%   |
| 6.1.25  | 1         | 1.03%   |
| 5.9.0   | 1         | 1.03%   |
| 5.8.0   | 1         | 1.03%   |
| 5.6.0   | 1         | 1.03%   |
| 5.19.0  | 1         | 1.03%   |
| 5.15.5  | 1         | 1.03%   |
| 5.15.0  | 1         | 1.03%   |
| 5.14.0  | 1         | 1.03%   |
| 5.1.21  | 1         | 1.03%   |
| 4.4.195 | 1         | 1.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 46        | 47.42%  |
| 6.1     | 15        | 15.46%  |
| 4.19    | 13        | 13.4%   |
| 5.7     | 4         | 4.12%   |
| 4.9     | 4         | 4.12%   |
| 6.0     | 3         | 3.09%   |
| 5.18    | 3         | 3.09%   |
| 5.15    | 2         | 2.06%   |
| 5.9     | 1         | 1.03%   |
| 5.8     | 1         | 1.03%   |
| 5.6     | 1         | 1.03%   |
| 5.19    | 1         | 1.03%   |
| 5.14    | 1         | 1.03%   |
| 5.1     | 1         | 1.03%   |
| 4.4     | 1         | 1.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 84        | 94.38%  |
| i686   | 3         | 3.37%   |
| armv7l | 2         | 2.25%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| XFCE          | 41        | 43.62%  |
| KDE5          | 15        | 15.96%  |
| MATE          | 11        | 11.7%   |
| Unknown       | 11        | 11.7%   |
| i3            | 5         | 5.32%   |
| LXDE          | 4         | 4.26%   |
| GNOME         | 2         | 2.13%   |
| Enlightenment | 2         | 2.13%   |
| Openbox       | 1         | 1.06%   |
| LXQt          | 1         | 1.06%   |
| Cinnamon      | 1         | 1.06%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| X11         | 84        | 91.3%   |
| Tty         | 4         | 4.35%   |
| Unknown     | 2         | 2.17%   |
| Wayland     | 1         | 1.09%   |
| Unspecified | 1         | 1.09%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SLiM    | 31        | 33.7%   |
| LightDM | 26        | 28.26%  |
| Unknown | 24        | 26.09%  |
| SDDM    | 7         | 7.61%   |
| XDM     | 1         | 1.09%   |
| Ly      | 1         | 1.09%   |
| LXDM    | 1         | 1.09%   |
| GDM3    | 1         | 1.09%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| en_US       | 45        | 50%     |
| en_GB       | 15        | 16.67%  |
| ru_RU       | 7         | 7.78%   |
| pt_BR       | 3         | 3.33%   |
| it_IT       | 2         | 2.22%   |
| es_ES       | 2         | 2.22%   |
| de_DE       | 2         | 2.22%   |
| de_AT       | 2         | 2.22%   |
| Unknown     | 2         | 2.22%   |
| ru_UA       | 1         | 1.11%   |
| ru_RU.utf-8 | 1         | 1.11%   |
| pl_PL       | 1         | 1.11%   |
| fr_BE       | 1         | 1.11%   |
| es_SV       | 1         | 1.11%   |
| es_AR       | 1         | 1.11%   |
| en_ZA       | 1         | 1.11%   |
| en_US.utf-8 | 1         | 1.11%   |
| de_CH       | 1         | 1.11%   |
| C           | 1         | 1.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 47        | 52.22%  |
| EFI  | 43        | 47.78%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 74        | 83.15%  |
| Xfs     | 4         | 4.49%   |
| Btrfs   | 4         | 4.49%   |
| Unknown | 3         | 3.37%   |
| OveXlay | 1         | 1.12%   |
| Overlay | 1         | 1.12%   |
| Ext3    | 1         | 1.12%   |
| Ext2    | 1         | 1.12%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 45        | 49.45%  |
| MBR     | 33        | 36.26%  |
| Unknown | 13        | 14.29%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 77        | 86.52%  |
| Yes       | 12        | 13.48%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 72        | 80%     |
| Yes       | 18        | 20%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 24        | 26.97%  |
| Dell                | 18        | 20.22%  |
| Hewlett-Packard     | 9         | 10.11%  |
| ASUSTek Computer    | 5         | 5.62%   |
| Acer                | 5         | 5.62%   |
| Toshiba             | 4         | 4.49%   |
| MSI                 | 3         | 3.37%   |
| Sony                | 2         | 2.25%   |
| Samsung Electronics | 2         | 2.25%   |
| Nokia               | 2         | 2.25%   |
| Google              | 2         | 2.25%   |
| Fujitsu Siemens     | 2         | 2.25%   |
| Teclast             | 1         | 1.12%   |
| PC Specialist       | 1         | 1.12%   |
| Notebook            | 1         | 1.12%   |
| MTC                 | 1         | 1.12%   |
| Intel               | 1         | 1.12%   |
| IBM                 | 1         | 1.12%   |
| HUAWEI              | 1         | 1.12%   |
| Fujitsu             | 1         | 1.12%   |
| CCE                 | 1         | 1.12%   |
| Apple               | 1         | 1.12%   |
| Unknown             | 1         | 1.12%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                                                     | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Nokia N900                                                                               | 2         | 2.25%   |
| Toshiba Satellite Pro A50-C                                                              | 1         | 1.12%   |
| Toshiba Satellite M40X                                                                   | 1         | 1.12%   |
| Toshiba Satellite L655                                                                   | 1         | 1.12%   |
| Toshiba Satellite L300                                                                   | 1         | 1.12%   |
| Teclast F6 Plus                                                                          | 1         | 1.12%   |
| Sony VPCEE23FX                                                                           | 1         | 1.12%   |
| Sony VGN-FZ140E                                                                          | 1         | 1.12%   |
| Samsung 550XDA                                                                           | 1         | 1.12%   |
| Samsung 355V4C/355V4X/355V5C/355V5X/356V4C/356V4X/356V5C/356V5X/3445VC/3445VX/3545VC/354 | 1         | 1.12%   |
| PC Specialist P7xxTM1                                                                    | 1         | 1.12%   |
| Notebook W230ST                                                                          | 1         | 1.12%   |
| MTC Montara-GML                                                                          | 1         | 1.12%   |
| MSI MS-1688                                                                              | 1         | 1.12%   |
| MSI Modern 15 A5M                                                                        | 1         | 1.12%   |
| MSI Bravo 15 A4DDR                                                                       | 1         | 1.12%   |
| Lenovo V310-14ISK 80SX                                                                   | 1         | 1.12%   |
| Lenovo ThinkPad X60 1707YF8                                                              | 1         | 1.12%   |
| Lenovo ThinkPad X390 20Q1A005CD                                                          | 1         | 1.12%   |
| Lenovo ThinkPad X250 20CLS7WY04                                                          | 1         | 1.12%   |
| Lenovo ThinkPad X230 2325DE0                                                             | 1         | 1.12%   |
| Lenovo ThinkPad X230 23247S0                                                             | 1         | 1.12%   |
| Lenovo ThinkPad X220 429053G                                                             | 1         | 1.12%   |
| Lenovo ThinkPad X200 74585FU                                                             | 1         | 1.12%   |
| Lenovo ThinkPad X1 Carbon 7th 20QD00L1PB                                                 | 1         | 1.12%   |
| Lenovo ThinkPad T560 20FJS1J200                                                          | 1         | 1.12%   |
| Lenovo ThinkPad T550 20CJS1VD01                                                          | 1         | 1.12%   |
| Lenovo ThinkPad T480 20L5CTO1WW                                                          | 1         | 1.12%   |
| Lenovo ThinkPad T470s 20HGS00P00                                                         | 1         | 1.12%   |
| Lenovo ThinkPad T440p                                                                    | 1         | 1.12%   |
| Lenovo ThinkPad T430 2349I46                                                             | 1         | 1.12%   |
| Lenovo ThinkPad T420 4180AG3                                                             | 1         | 1.12%   |
| Lenovo ThinkPad T410 2537DA3                                                             | 1         | 1.12%   |
| Lenovo ThinkPad T14 Gen 3 21AHCTO1WW                                                     | 1         | 1.12%   |
| Lenovo S20-30 20421                                                                      | 1         | 1.12%   |
| Lenovo IdeaPad Z370                                                                      | 1         | 1.12%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK                                                    | 1         | 1.12%   |
| Lenovo IdeaPad 530S-14ARR 81H1                                                           | 1         | 1.12%   |
| Lenovo IdeaPad 130-15AST 81H5                                                            | 1         | 1.12%   |
| Lenovo G50-30 80G0                                                                       | 1         | 1.12%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 17        | 19.1%   |
| Dell Latitude           | 10        | 11.24%  |
| Toshiba Satellite       | 4         | 4.49%   |
| Lenovo IdeaPad          | 4         | 4.49%   |
| Dell Inspiron           | 4         | 4.49%   |
| Acer Aspire             | 4         | 4.49%   |
| HP Laptop               | 3         | 3.37%   |
| Nokia N900              | 2         | 2.25%   |
| HP ProBook              | 2         | 2.25%   |
| Dell XPS                | 2         | 2.25%   |
| Teclast F6              | 1         | 1.12%   |
| Sony VPCEE23FX          | 1         | 1.12%   |
| Sony VGN-FZ140E         | 1         | 1.12%   |
| Samsung 550XDA          | 1         | 1.12%   |
| Samsung 355V4C          | 1         | 1.12%   |
| PC Specialist P7xxTM1   | 1         | 1.12%   |
| Notebook W230ST         | 1         | 1.12%   |
| MTC Montara-GML         | 1         | 1.12%   |
| MSI MS-1688             | 1         | 1.12%   |
| MSI Modern              | 1         | 1.12%   |
| MSI Bravo               | 1         | 1.12%   |
| Lenovo V310-14ISK       | 1         | 1.12%   |
| Lenovo S20-30           | 1         | 1.12%   |
| Lenovo G50-30           | 1         | 1.12%   |
| Intel powered           | 1         | 1.12%   |
| IBM ThinkPad            | 1         | 1.12%   |
| HUAWEI HN-WX9X          | 1         | 1.12%   |
| HP Pavilion             | 1         | 1.12%   |
| HP Notebook             | 1         | 1.12%   |
| HP EliteBook            | 1         | 1.12%   |
| HP 250                  | 1         | 1.12%   |
| Google Cyan             | 1         | 1.12%   |
| Google Bluebird         | 1         | 1.12%   |
| Fujitsu Siemens ESPRIMO | 1         | 1.12%   |
| Fujitsu Siemens AMILO   | 1         | 1.12%   |
| Fujitsu LIFEBOOK        | 1         | 1.12%   |
| Dell Precision          | 1         | 1.12%   |
| Dell G5                 | 1         | 1.12%   |
| CCE Capella             | 1         | 1.12%   |
| ASUS X555LJ             | 1         | 1.12%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 10        | 11.24%  |
| 2012    | 10        | 11.24%  |
| 2018    | 9         | 10.11%  |
| 2014    | 6         | 6.74%   |
| 2013    | 6         | 6.74%   |
| 2021    | 5         | 5.62%   |
| 2008    | 5         | 5.62%   |
| 2020    | 4         | 4.49%   |
| 2016    | 4         | 4.49%   |
| 2015    | 4         | 4.49%   |
| 2011    | 4         | 4.49%   |
| 2010    | 4         | 4.49%   |
| 2009    | 4         | 4.49%   |
| 2017    | 3         | 3.37%   |
| 2022    | 2         | 2.25%   |
| 2007    | 2         | 2.25%   |
| 2006    | 2         | 2.25%   |
| 2005    | 2         | 2.25%   |
| Unknown | 2         | 2.25%   |
| 2023    | 1         | 1.12%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 89        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 87        | 96.67%  |
| Enabled  | 3         | 3.33%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 85        | 95.51%  |
| Yes  | 4         | 4.49%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 23        | 25.56%  |
| 8.01-16.0   | 18        | 20%     |
| 3.01-4.0    | 16        | 17.78%  |
| 16.01-24.0  | 11        | 12.22%  |
| 1.01-2.0    | 7         | 7.78%   |
| 32.01-64.0  | 5         | 5.56%   |
| 2.01-3.0    | 5         | 5.56%   |
| 0.01-0.5    | 3         | 3.33%   |
| 24.01-32.0  | 1         | 1.11%   |
| 64.01-256.0 | 1         | 1.11%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 37        | 37%     |
| 4.01-8.0   | 19        | 19%     |
| 3.01-4.0   | 13        | 13%     |
| 2.01-3.0   | 10        | 10%     |
| 0.51-1.0   | 10        | 10%     |
| 8.01-16.0  | 5         | 5%      |
| 0.01-0.5   | 5         | 5%      |
| 32.01-64.0 | 1         | 1%      |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 67        | 74.44%  |
| 2      | 18        | 20%     |
| 3      | 4         | 4.44%   |
| 4      | 1         | 1.11%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 57        | 63.33%  |
| Yes       | 33        | 36.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 79        | 88.76%  |
| No        | 10        | 11.24%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 83        | 93.26%  |
| No        | 6         | 6.74%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 56        | 62.22%  |
| No        | 34        | 37.78%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 14        | 15.56%  |
| Germany      | 10        | 11.11%  |
| Russia       | 9         | 10%     |
| Brazil       | 7         | 7.78%   |
| Ukraine      | 4         | 4.44%   |
| Portugal     | 4         | 4.44%   |
| France       | 4         | 4.44%   |
| Italy        | 3         | 3.33%   |
| Grenada      | 3         | 3.33%   |
| Finland      | 3         | 3.33%   |
| Spain        | 2         | 2.22%   |
| Poland       | 2         | 2.22%   |
| Netherlands  | 2         | 2.22%   |
| Hungary      | 2         | 2.22%   |
| Greece       | 2         | 2.22%   |
| Austria      | 2         | 2.22%   |
| Vietnam      | 1         | 1.11%   |
| UK           | 1         | 1.11%   |
| Switzerland  | 1         | 1.11%   |
| South Africa | 1         | 1.11%   |
| Slovakia     | 1         | 1.11%   |
| Serbia       | 1         | 1.11%   |
| Romania      | 1         | 1.11%   |
| Norway       | 1         | 1.11%   |
| Mexico       | 1         | 1.11%   |
| Lithuania    | 1         | 1.11%   |
| Israel       | 1         | 1.11%   |
| Indonesia    | 1         | 1.11%   |
| Georgia      | 1         | 1.11%   |
| El Salvador  | 1         | 1.11%   |
| Belarus      | 1         | 1.11%   |
| Bangladesh   | 1         | 1.11%   |
| Argentina    | 1         | 1.11%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Saint George's       | 3         | 3.33%   |
| Thessaloniki         | 2         | 2.22%   |
| Palmyra              | 2         | 2.22%   |
| Nadudvar             | 2         | 2.22%   |
| Milan                | 2         | 2.22%   |
| Lisbon               | 2         | 2.22%   |
| Kyiv                 | 2         | 2.22%   |
| Ft. Washington       | 2         | 2.22%   |
| Bagnolet             | 2         | 2.22%   |
| Amsterdam            | 2         | 2.22%   |
| Yoshkar-Ola          | 1         | 1.11%   |
| Yakutsk              | 1         | 1.11%   |
| Wroclaw              | 1         | 1.11%   |
| Willich              | 1         | 1.11%   |
| Wildberg             | 1         | 1.11%   |
| Vilnius              | 1         | 1.11%   |
| Valbonne             | 1         | 1.11%   |
| Trubchëvsk          | 1         | 1.11%   |
| Tel Aviv             | 1         | 1.11%   |
| Tejgaon              | 1         | 1.11%   |
| Tbilisi              | 1         | 1.11%   |
| Syktyvkar            | 1         | 1.11%   |
| Staunton             | 1         | 1.11%   |
| St Petersburg        | 1         | 1.11%   |
| Siena                | 1         | 1.11%   |
| Sao Paulo            | 1         | 1.11%   |
| San Salvador         | 1         | 1.11%   |
| Samara               | 1         | 1.11%   |
| Rio de Janeiro       | 1         | 1.11%   |
| Presidente Venceslau | 1         | 1.11%   |
| Praia Grande         | 1         | 1.11%   |
| Pedro Leopoldo       | 1         | 1.11%   |
| Oslo                 | 1         | 1.11%   |
| Novopskov            | 1         | 1.11%   |
| New York             | 1         | 1.11%   |
| Munich               | 1         | 1.11%   |
| Muenster-Sarmsheim   | 1         | 1.11%   |
| Mountain View        | 1         | 1.11%   |
| Moscow               | 1         | 1.11%   |
| Maladzyechna         | 1         | 1.11%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 16        | 18     | 14.29%  |
| Samsung Electronics | 15        | 24     | 13.39%  |
| Unknown             | 12        | 15     | 10.71%  |
| Seagate             | 10        | 10     | 8.93%   |
| Kingston            | 6         | 6      | 5.36%   |
| Toshiba             | 5         | 5      | 4.46%   |
| SanDisk             | 5         | 5      | 4.46%   |
| Crucial             | 5         | 6      | 4.46%   |
| Hitachi             | 4         | 4      | 3.57%   |
| SK hynix            | 3         | 3      | 2.68%   |
| PNY                 | 3         | 3      | 2.68%   |
| LITEON              | 3         | 6      | 2.68%   |
| Intel               | 3         | 3      | 2.68%   |
| HGST                | 3         | 3      | 2.68%   |
| Team                | 2         | 2      | 1.79%   |
| Fujitsu             | 2         | 2      | 1.79%   |
| Union Memory        | 1         | 2      | 0.89%   |
| UMIS                | 1         | 1      | 0.89%   |
| Teclast             | 1         | 1      | 0.89%   |
| SSSTC               | 1         | 1      | 0.89%   |
| Smart               | 1         | 1      | 0.89%   |
| SABRENT             | 1         | 2      | 0.89%   |
| Patriot             | 1         | 1      | 0.89%   |
| Mushkin             | 1         | 1      | 0.89%   |
| Micron Technology   | 1         | 2      | 0.89%   |
| LITEONIT            | 1         | 1      | 0.89%   |
| KIOXIA              | 1         | 1      | 0.89%   |
| KingFast            | 1         | 1      | 0.89%   |
| HXY                 | 1         | 1      | 0.89%   |
| Hewlett-Packard     | 1         | 1      | 0.89%   |
| Apple               | 1         | 1      | 0.89%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Unknown MMC Card  32GB               | 5         | 4.35%   |
| Unknown MMC Card  128GB              | 3         | 2.61%   |
| PNY CS900 240GB SSD                  | 3         | 2.61%   |
| Samsung SSD 970 EVO Plus 500GB       | 2         | 1.74%   |
| Samsung SSD 850 EVO 500GB            | 2         | 1.74%   |
| Samsung SSD 850 EVO 250GB            | 2         | 1.74%   |
| Kingston SA400S37480G 480GB SSD      | 2         | 1.74%   |
| Kingston SA400S37240G 240GB SSD      | 2         | 1.74%   |
| Crucial CT250MX500SSD1 250GB         | 2         | 1.74%   |
| Crucial CT1000MX500SSD1 1TB          | 2         | 1.74%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 1         | 0.87%   |
| WDC WDS500G1B0A-00H9H0 500GB SSD     | 1         | 0.87%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1         | 0.87%   |
| WDC WD7500BPKX-00HPJT0 752GB         | 1         | 0.87%   |
| WDC WD5000BPVT-24HXZT3 500GB         | 1         | 0.87%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 1         | 0.87%   |
| WDC WD3200BEVT-22A23T0 320GB         | 1         | 0.87%   |
| WDC WD3200BEVE-00A0HT0 320GB         | 1         | 0.87%   |
| WDC WD2500BEKT-00A25T0 250GB         | 1         | 0.87%   |
| WDC WD1600BEVT-75A23T0 160GB         | 1         | 0.87%   |
| WDC WD10SPZX-21Z10T0 1TB             | 1         | 0.87%   |
| WDC WD10JPCX-24UE4T0 1TB             | 1         | 0.87%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB | 1         | 0.87%   |
| WDC PC SN540 SDDPNPF-512G-1032 512GB | 1         | 0.87%   |
| WDC PC SN530 NVMe 256GB              | 1         | 0.87%   |
| WDC PC SN520 SDAPMUW-512G-1101 512GB | 1         | 0.87%   |
| Unknown SD04G  4GB                   | 1         | 0.87%   |
| Unknown SD  8GB                      | 1         | 0.87%   |
| Unknown MMC32G  32GB                 | 1         | 0.87%   |
| Unknown MMC Card  8GB                | 1         | 0.87%   |
| Unknown MMC Card  16GB               | 1         | 0.87%   |
| Union Memory RTOTJ128VGD2EYX 128GB   | 1         | 0.87%   |
| UMIS RPFTJ256PDD2MWX 256GB           | 1         | 0.87%   |
| Toshiba MQ04ABF100 1TB               | 1         | 0.87%   |
| Toshiba MK5065GSX 500GB              | 1         | 0.87%   |
| Toshiba MK2035GSS 200GB              | 1         | 0.87%   |
| Toshiba MK1252GSX 120GB              | 1         | 0.87%   |
| Toshiba KBG30ZMV512G 512GB           | 1         | 0.87%   |
| Teclast 256GB NS550-2242 SSD         | 1         | 0.87%   |
| Team T253X1120G 120GB SSD            | 1         | 0.87%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 10        | 10     | 30.3%   |
| WDC     | 9         | 9      | 27.27%  |
| Toshiba | 4         | 4      | 12.12%  |
| Hitachi | 4         | 4      | 12.12%  |
| HGST    | 3         | 3      | 9.09%   |
| Fujitsu | 2         | 2      | 6.06%   |
| SABRENT | 1         | 2      | 3.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 10        | 10     | 22.22%  |
| Kingston            | 6         | 6      | 13.33%  |
| SanDisk             | 5         | 5      | 11.11%  |
| Crucial             | 4         | 5      | 8.89%   |
| WDC                 | 3         | 4      | 6.67%   |
| PNY                 | 3         | 3      | 6.67%   |
| Team                | 2         | 2      | 4.44%   |
| LITEON              | 2         | 5      | 4.44%   |
| Union Memory        | 1         | 2      | 2.22%   |
| Teclast             | 1         | 1      | 2.22%   |
| Smart               | 1         | 1      | 2.22%   |
| SK hynix            | 1         | 1      | 2.22%   |
| Patriot             | 1         | 1      | 2.22%   |
| Mushkin             | 1         | 1      | 2.22%   |
| LITEONIT            | 1         | 1      | 2.22%   |
| HXY                 | 1         | 1      | 2.22%   |
| Hewlett-Packard     | 1         | 1      | 2.22%   |
| Apple               | 1         | 1      | 2.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 40        | 51     | 37.38%  |
| HDD     | 33        | 34     | 30.84%  |
| NVMe    | 21        | 32     | 19.63%  |
| MMC     | 12        | 15     | 11.21%  |
| Unknown | 1         | 1      | 0.93%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 66        | 83     | 65.35%  |
| NVMe | 21        | 32     | 20.79%  |
| MMC  | 12        | 15     | 11.88%  |
| SAS  | 2         | 3      | 1.98%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 54        | 63     | 77.14%  |
| 0.51-1.0   | 13        | 19     | 18.57%  |
| 1.01-2.0   | 2         | 2      | 2.86%   |
| 4.01-10.0  | 1         | 1      | 1.43%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 23        | 25%     |
| 101-250        | 22        | 23.91%  |
| 51-100         | 12        | 13.04%  |
| 501-1000       | 11        | 11.96%  |
| 21-50          | 9         | 9.78%   |
| 1001-2000      | 5         | 5.43%   |
| 1-20           | 3         | 3.26%   |
| Unknown        | 3         | 3.26%   |
| More than 3000 | 2         | 2.17%   |
| 2001-3000      | 2         | 2.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 30        | 32.26%  |
| 101-250        | 16        | 17.2%   |
| 51-100         | 13        | 13.98%  |
| 21-50          | 12        | 12.9%   |
| 251-500        | 11        | 11.83%  |
| 1001-2000      | 3         | 3.23%   |
| 501-1000       | 3         | 3.23%   |
| Unknown        | 3         | 3.23%   |
| More than 3000 | 1         | 1.08%   |
| 2001-3000      | 1         | 1.08%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD5000BPVT-24HXZT3 500GB    | 1         | 1      | 10%     |
| WDC WD3200BEVT-22A23T0 320GB    | 1         | 1      | 10%     |
| WDC WD1600BEVT-75A23T0 160GB    | 1         | 1      | 10%     |
| WDC WD10JPCX-24UE4T0 1TB        | 1         | 1      | 10%     |
| Seagate ST9200420ASG 200GB      | 1         | 1      | 10%     |
| Seagate ST500LM021-1KJ152 500GB | 1         | 1      | 10%     |
| Seagate ST320LT020-9YG142 320GB | 1         | 1      | 10%     |
| Seagate ST320LT007-9ZV142 320GB | 1         | 1      | 10%     |
| Hitachi HTS727575A9E364 752GB   | 1         | 1      | 10%     |
| Hitachi HTS726060M9AT00 56GB    | 1         | 1      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 4         | 4      | 40%     |
| Seagate | 4         | 4      | 40%     |
| Hitachi | 2         | 2      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 4         | 4      | 40%     |
| Seagate | 4         | 4      | 40%     |
| Hitachi | 2         | 2      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 10        | 10     | 100%    |

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
| Works    | 63        | 91     | 64.95%  |
| Detected | 24        | 32     | 24.74%  |
| Malfunc  | 10        | 10     | 10.31%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 63        | 67.74%  |
| AMD                            | 10        | 10.75%  |
| Samsung Electronics            | 6         | 6.45%   |
| SanDisk                        | 4         | 4.3%    |
| SK hynix                       | 2         | 2.15%   |
| VIA Technologies               | 1         | 1.08%   |
| Union Memory (Shenzhen)        | 1         | 1.08%   |
| Toshiba America Info Systems   | 1         | 1.08%   |
| Solid State Storage Technology | 1         | 1.08%   |
| Micron/Crucial Technology      | 1         | 1.08%   |
| Micron Technology              | 1         | 1.08%   |
| Lite-On Technology             | 1         | 1.08%   |
| KIOXIA                         | 1         | 1.08%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 8         | 7.77%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 7         | 6.8%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 5         | 4.85%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 4         | 3.88%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 4         | 3.88%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 4         | 3.88%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 3.88%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 4         | 3.88%   |
| Intel Tiger Lake-LP SATA Controller                                            | 3         | 2.91%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 2.91%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 3         | 2.91%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 3         | 2.91%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 2         | 1.94%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 1.94%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 2         | 1.94%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 1.94%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 2         | 1.94%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 1.94%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 2         | 1.94%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                         | 2         | 1.94%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 1.94%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 1.94%   |
| VIA VT6421 IDE/SATA Controller                                                 | 1         | 0.97%   |
| Union Memory (Shenzhen) AM610 PCIe 3.0 NVMe SSD 128GB                          | 1         | 0.97%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 1         | 0.97%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                 | 1         | 0.97%   |
| SK hynix PC611 NVMe Solid State Drive                                          | 1         | 0.97%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 1         | 0.97%   |
| SanDisk WD Green SN350 NVMe SSD 1 TB (DRAM-less)                               | 1         | 0.97%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 1         | 0.97%   |
| SanDisk PC SN520 NVMe SSD                                                      | 1         | 0.97%   |
| SanDisk IX SN530 NVMe SSD (DRAM-less)                                          | 1         | 0.97%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 0.97%   |
| Samsung NVMe SSD Controller 980                                                | 1         | 0.97%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 1         | 0.97%   |
| Micron 2200S NVMe SSD [Cassandra]                                              | 1         | 0.97%   |
| Lite-On Non-Volatile memory controller                                         | 1         | 0.97%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 1         | 0.97%   |
| Intel Volume Management Device NVMe RAID Controller                            | 1         | 0.97%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 1         | 0.97%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 60        | 61.22%  |
| NVMe | 21        | 21.43%  |
| IDE  | 11        | 11.22%  |
| RAID | 6         | 6.12%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 73        | 82.02%  |
| AMD    | 14        | 15.73%  |
| ARM    | 2         | 2.25%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-5300U CPU @ 2.30GHz           | 3         | 3.37%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 3         | 3.37%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 2         | 2.25%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 2         | 2.25%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 2         | 2.25%   |
| Intel Core i3 CPU M 330 @ 2.13GHz           | 2         | 2.25%   |
| ARM Nokia RX-51 board Processor             | 2         | 2.25%   |
| AMD Ryzen 5 4600H with Radeon Graphics      | 2         | 2.25%   |
| Intel Pentium M processor 1700MHz           | 1         | 1.12%   |
| Intel Pentium M processor 1.60GHz           | 1         | 1.12%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 1.12%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz      | 1         | 1.12%   |
| Intel Pentium CPU P6100 @ 2.00GHz           | 1         | 1.12%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 1         | 1.12%   |
| Intel Genuine CPU T1600 @ 1.66GHz           | 1         | 1.12%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 1         | 1.12%   |
| Intel Core i9-8950HK CPU @ 2.90GHz          | 1         | 1.12%   |
| Intel Core i7-9850H CPU @ 2.60GHz           | 1         | 1.12%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 1.12%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 1.12%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 1         | 1.12%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 1.12%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz          | 1         | 1.12%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 1         | 1.12%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz          | 1         | 1.12%   |
| Intel Core i7-4610M CPU @ 3.00GHz           | 1         | 1.12%   |
| Intel Core i7-4500U CPU @ 1.80GHz           | 1         | 1.12%   |
| Intel Core i7-3610QM CPU @ 2.30GHz          | 1         | 1.12%   |
| Intel Core i7-3540M CPU @ 3.00GHz           | 1         | 1.12%   |
| Intel Core i7-3520M CPU @ 2.90GHz           | 1         | 1.12%   |
| Intel Core i7-2860QM CPU @ 2.50GHz          | 1         | 1.12%   |
| Intel Core i7-2640M CPU @ 2.80GHz           | 1         | 1.12%   |
| Intel Core i5-9300H CPU @ 2.40GHz           | 1         | 1.12%   |
| Intel Core i5-4310U CPU @ 2.00GHz           | 1         | 1.12%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 1         | 1.12%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 1         | 1.12%   |
| Intel Core i5-10310U CPU @ 1.70GHz          | 1         | 1.12%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 1         | 1.12%   |
| Intel Core i3-8145U CPU @ 2.10GHz           | 1         | 1.12%   |
| Intel Core i3-7100U CPU @ 2.40GHz           | 1         | 1.12%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 17        | 19.1%   |
| Intel Core i5           | 16        | 17.98%  |
| Intel Core i3           | 11        | 12.36%  |
| Other                   | 7         | 7.87%   |
| Intel Celeron           | 6         | 6.74%   |
| AMD Ryzen 5             | 4         | 4.49%   |
| Intel Core 2 Duo        | 3         | 3.37%   |
| Intel Core 2            | 3         | 3.37%   |
| Intel Atom              | 3         | 3.37%   |
| AMD Ryzen 7             | 3         | 3.37%   |
| Intel Pentium M         | 2         | 2.25%   |
| Intel Pentium           | 2         | 2.25%   |
| Intel Core i9           | 2         | 2.25%   |
| Intel Pentium Dual-Core | 1         | 1.12%   |
| Intel Pentium Dual      | 1         | 1.12%   |
| Intel Genuine           | 1         | 1.12%   |
| Intel Celeron M         | 1         | 1.12%   |
| AMD E2                  | 1         | 1.12%   |
| AMD E                   | 1         | 1.12%   |
| AMD Athlon II           | 1         | 1.12%   |
| AMD A8                  | 1         | 1.12%   |
| AMD A6                  | 1         | 1.12%   |
| AMD A10                 | 1         | 1.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 52        | 58.43%  |
| 4      | 23        | 25.84%  |
| 1      | 6         | 6.74%   |
| 6      | 5         | 5.62%   |
| 8      | 2         | 2.25%   |
| 12     | 1         | 1.12%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 89        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 58        | 64.44%  |
| 1      | 32        | 35.56%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 83        | 93.26%  |
| 32-bit         | 3         | 3.37%   |
| Unknown        | 3         | 3.37%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 26        | 27.96%  |
| 0x806ec    | 5         | 5.38%   |
| 0x406e3    | 5         | 5.38%   |
| 0x306c3    | 5         | 5.38%   |
| 0x306a9    | 4         | 4.3%    |
| 0x306d4    | 3         | 3.23%   |
| 0x30678    | 3         | 3.23%   |
| 0x206a7    | 3         | 3.23%   |
| 0x20655    | 3         | 3.23%   |
| 0x1067a    | 3         | 3.23%   |
| 0x906ea    | 2         | 2.15%   |
| 0x806c1    | 2         | 2.15%   |
| 0x706a1    | 2         | 2.15%   |
| 0x6f6      | 2         | 2.15%   |
| 0x406c4    | 2         | 2.15%   |
| 0x40651    | 2         | 2.15%   |
| 0x08608103 | 2         | 2.15%   |
| 0x906ed    | 1         | 1.08%   |
| 0x906a3    | 1         | 1.08%   |
| 0x806ea    | 1         | 1.08%   |
| 0x706a8    | 1         | 1.08%   |
| 0x6fd      | 1         | 1.08%   |
| 0x6d8      | 1         | 1.08%   |
| 0x695      | 1         | 1.08%   |
| 0x30661    | 1         | 1.08%   |
| 0x20652    | 1         | 1.08%   |
| 0x08600106 | 1         | 1.08%   |
| 0x08600102 | 1         | 1.08%   |
| 0x08108109 | 1         | 1.08%   |
| 0x08101016 | 1         | 1.08%   |
| 0x0810100b | 1         | 1.08%   |
| 0x07030105 | 1         | 1.08%   |
| 0x0600611a | 1         | 1.08%   |
| 0x05000119 | 1         | 1.08%   |
| 0x05000101 | 1         | 1.08%   |
| 0x010000b6 | 1         | 1.08%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 13        | 14.44%  |
| Haswell          | 8         | 8.89%   |
| IvyBridge        | 7         | 7.78%   |
| Westmere         | 6         | 6.67%   |
| Silvermont       | 6         | 6.67%   |
| Core             | 6         | 6.67%   |
| Skylake          | 5         | 5.56%   |
| Unknown          | 5         | 5.56%   |
| SandyBridge      | 4         | 4.44%   |
| Broadwell        | 4         | 4.44%   |
| TigerLake        | 3         | 3.33%   |
| Penryn           | 3         | 3.33%   |
| P6               | 3         | 3.33%   |
| Goldmont plus    | 3         | 3.33%   |
| Zen 2            | 2         | 2.22%   |
| Zen              | 2         | 2.22%   |
| Excavator        | 2         | 2.22%   |
| Bobcat           | 2         | 2.22%   |
| Zen+             | 1         | 1.11%   |
| Puma             | 1         | 1.11%   |
| Piledriver       | 1         | 1.11%   |
| K10              | 1         | 1.11%   |
| Bonnell          | 1         | 1.11%   |
| Alderlake Hybrid | 1         | 1.11%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 67        | 67%     |
| AMD    | 21        | 21%     |
| Nvidia | 12        | 12%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 7         | 6.6%    |
| Intel Core Processor Integrated Graphics Controller                                      | 6         | 5.66%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 5         | 4.72%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 4.72%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 3.77%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 3.77%   |
| Intel HD Graphics 5500                                                                   | 4         | 3.77%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 3.77%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 4         | 3.77%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 2.83%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 2.83%   |
| Intel UHD Graphics 620                                                                   | 2         | 1.89%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 1.89%   |
| Intel HD Graphics 620                                                                    | 2         | 1.89%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.89%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.89%   |
| AMD Renoir                                                                               | 2         | 1.89%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 1.89%   |
| AMD Lucienne                                                                             | 2         | 1.89%   |
| Nvidia TU106BM [GeForce RTX 2060 Mobile]                                                 | 1         | 0.94%   |
| Nvidia GP107M [GeForce MX150]                                                            | 1         | 0.94%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.94%   |
| Nvidia GM108M [GeForce 930M]                                                             | 1         | 0.94%   |
| Nvidia GM107M [GeForce GTX 860M]                                                         | 1         | 0.94%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 0.94%   |
| Nvidia GK106M [GeForce GTX 765M]                                                         | 1         | 0.94%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.94%   |
| Nvidia GF108M [NVS 5400M]                                                                | 1         | 0.94%   |
| Nvidia GF108M [GeForce GT 635M]                                                          | 1         | 0.94%   |
| Nvidia GF108GLM [NVS 5200M]                                                              | 1         | 0.94%   |
| Nvidia G84M [GeForce 8600M GT]                                                           | 1         | 0.94%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 1         | 0.94%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 0.94%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 0.94%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 0.94%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 0.94%   |
| Intel HD Graphics 520                                                                    | 1         | 0.94%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 0.94%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 1         | 0.94%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 1         | 0.94%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 51        | 57.3%   |
| 1 x AMD        | 14        | 15.73%  |
| Intel + Nvidia | 10        | 11.24%  |
| Other          | 4         | 4.49%   |
| 2 x AMD        | 4         | 4.49%   |
| Intel + AMD    | 3         | 3.37%   |
| 1 x Nvidia     | 2         | 2.25%   |
| 2 x Intel      | 1         | 1.12%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 81        | 91.01%  |
| Proprietary | 5         | 5.62%   |
| Unknown     | 3         | 3.37%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 67        | 74.44%  |
| 0.01-0.5   | 10        | 11.11%  |
| 0.51-1.0   | 6         | 6.67%   |
| 1.01-2.0   | 4         | 4.44%   |
| 5.01-6.0   | 2         | 2.22%   |
| 3.01-4.0   | 1         | 1.11%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 19        | 18.63%  |
| LG Display              | 17        | 16.67%  |
| BOE                     | 12        | 11.76%  |
| Chimei Innolux          | 11        | 10.78%  |
| Samsung Electronics     | 10        | 9.8%    |
| PANDA                   | 4         | 3.92%   |
| Dell                    | 4         | 3.92%   |
| Lenovo                  | 3         | 2.94%   |
| Chi Mei Optoelectronics | 3         | 2.94%   |
| MStar                   | 2         | 1.96%   |
| Goldstar                | 2         | 1.96%   |
| AOC                     | 2         | 1.96%   |
| Acer                    | 2         | 1.96%   |
| Unknown                 | 1         | 0.98%   |
| STD                     | 1         | 0.98%   |
| Sharp                   | 1         | 0.98%   |
| Lenovo Group Limited    | 1         | 0.98%   |
| InnoLux Display         | 1         | 0.98%   |
| InfoVision              | 1         | 0.98%   |
| Iiyama                  | 1         | 0.98%   |
| Hisense                 | 1         | 0.98%   |
| CPT                     | 1         | 0.98%   |
| Apple                   | 1         | 0.98%   |
| Unknown                 | 1         | 0.98%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics S24D340 SAM0BBB 1920x1080 531x299mm 24.0-inch     | 2         | 1.96%   |
| MStar Demo MST0030 1360x765 1150x650mm 52.0-inch                      | 2         | 1.96%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 2         | 1.96%   |
| Dell P2717H DEL40F7 1920x1080 598x336mm 27.0-inch                     | 2         | 1.96%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch         | 2         | 1.96%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 2         | 1.96%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 1         | 0.98%   |
| STD HDMI TV STD00C7 1680x1050 698x392mm 31.5-inch                     | 1         | 0.98%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch               | 1         | 0.98%   |
| Samsung Electronics SMS24A850 SAM0825 1920x1200 518x324mm 24.1-inch   | 1         | 0.98%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch  | 1         | 0.98%   |
| Samsung Electronics LCD Monitor SEC4545 1280x800 331x207mm 15.4-inch  | 1         | 0.98%   |
| Samsung Electronics LCD Monitor SEC4151 1366x768 344x194mm 15.5-inch  | 1         | 0.98%   |
| Samsung Electronics LCD Monitor SEC3245 1280x800 331x207mm 15.4-inch  | 1         | 0.98%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch  | 1         | 0.98%   |
| Samsung Electronics LCD Monitor SDC4851 1366x768 344x194mm 15.5-inch  | 1         | 0.98%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 700x390mm 31.5-inch | 1         | 0.98%   |
| PANDA LM133LF5L01 NCP0020 1920x1080 294x165mm 13.3-inch               | 1         | 0.98%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch               | 1         | 0.98%   |
| PANDA LCD Monitor NCP0035 1920x1080 344x194mm 15.5-inch               | 1         | 0.98%   |
| PANDA LCD Monitor NCP002E 1920x1080 344x194mm 15.5-inch               | 1         | 0.98%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch         | 1         | 0.98%   |
| LG Display LCD Monitor LGDD901 1366x768 344x194mm 15.5-inch           | 1         | 0.98%   |
| LG Display LCD Monitor LGD0542 1920x1080 276x156mm 12.5-inch          | 1         | 0.98%   |
| LG Display LCD Monitor LGD0540 1920x1080 344x194mm 15.5-inch          | 1         | 0.98%   |
| LG Display LCD Monitor LGD04D5 1920x1080 344x194mm 15.5-inch          | 1         | 0.98%   |
| LG Display LCD Monitor LGD047B 1366x768 344x194mm 15.5-inch           | 1         | 0.98%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 1         | 0.98%   |
| LG Display LCD Monitor LGD0450 1366x768 277x156mm 12.5-inch           | 1         | 0.98%   |
| LG Display LCD Monitor LGD03D3 1600x900 309x174mm 14.0-inch           | 1         | 0.98%   |
| LG Display LCD Monitor LGD03A3 1366x768 277x156mm 12.5-inch           | 1         | 0.98%   |
| LG Display LCD Monitor LGD0386 1366x768 309x174mm 14.0-inch           | 1         | 0.98%   |
| LG Display LCD Monitor LGD036C 1366x768 277x156mm 12.5-inch           | 1         | 0.98%   |
| LG Display LCD Monitor LGD033E 1366x768 309x174mm 14.0-inch           | 1         | 0.98%   |
| LG Display LCD Monitor LGD02C0 1366x768 293x165mm 13.2-inch           | 1         | 0.98%   |
| LG Display LCD Monitor LGD018B 1366x768 309x174mm 14.0-inch           | 1         | 0.98%   |
| Lenovo LCD Monitor LEN4035 1280x800 303x190mm 14.1-inch               | 1         | 0.98%   |
| Lenovo LCD Monitor LEN4010 1280x800 261x163mm 12.1-inch               | 1         | 0.98%   |
| Lenovo LCD Monitor LEN4000 1024x768 246x185mm 12.1-inch               | 1         | 0.98%   |
| Lenovo Group Limited LCD Monitor L24i-30                              | 1         | 0.98%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 37        | 38.14%  |
| 1366x768 (WXGA)    | 36        | 37.11%  |
| 1600x900 (HD+)     | 6         | 6.19%   |
| 3840x2160 (4K)     | 5         | 5.15%   |
| 1280x800 (WXGA)    | 4         | 4.12%   |
| 5760x1080          | 1         | 1.03%   |
| 2560x1440 (QHD)    | 1         | 1.03%   |
| 2288x1287          | 1         | 1.03%   |
| 2160x1440          | 1         | 1.03%   |
| 1920x1200 (WUXGA)  | 1         | 1.03%   |
| 1680x1050 (WSXGA+) | 1         | 1.03%   |
| 1440x900 (WXGA+)   | 1         | 1.03%   |
| 1024x600           | 1         | 1.03%   |
| Unknown            | 1         | 1.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 36        | 36%     |
| 14      | 13        | 13%     |
| 13      | 10        | 10%     |
| 12      | 9         | 9%      |
| 27      | 6         | 6%      |
| 24      | 5         | 5%      |
| 11      | 5         | 5%      |
| 17      | 4         | 4%      |
| 52      | 2         | 2%      |
| 23      | 2         | 2%      |
| 21      | 2         | 2%      |
| 142     | 1         | 1%      |
| 54      | 1         | 1%      |
| 31      | 1         | 1%      |
| 20      | 1         | 1%      |
| 10      | 1         | 1%      |
| Unknown | 1         | 1%      |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 53        | 53.54%  |
| 201-300        | 21        | 21.21%  |
| 501-600        | 12        | 12.12%  |
| 351-400        | 4         | 4.04%   |
| 401-500        | 3         | 3.03%   |
| 1001-1500      | 3         | 3.03%   |
| More than 2000 | 1         | 1.01%   |
| 601-700        | 1         | 1.01%   |
| Unknown        | 1         | 1.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 74        | 88.1%   |
| 16/10   | 7         | 8.33%   |
| 3/2     | 1         | 1.19%   |
| 1.00    | 1         | 1.19%   |
| Unknown | 1         | 1.19%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 36        | 36%     |
| 81-90          | 17        | 17%     |
| 61-70          | 9         | 9%      |
| 201-250        | 8         | 8%      |
| 71-80          | 6         | 6%      |
| 301-350        | 6         | 6%      |
| 51-60          | 5         | 5%      |
| More than 1000 | 4         | 4%      |
| 121-130        | 3         | 3%      |
| 351-500        | 1         | 1%      |
| 41-50          | 1         | 1%      |
| 251-300        | 1         | 1%      |
| 151-200        | 1         | 1%      |
| 131-140        | 1         | 1%      |
| Unknown        | 1         | 1%      |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 39        | 39.8%   |
| 101-120 | 29        | 29.59%  |
| 51-100  | 17        | 17.35%  |
| 161-240 | 8         | 8.16%   |
| 1-50    | 4         | 4.08%   |
| Unknown | 1         | 1.02%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 73        | 78.49%  |
| 2     | 16        | 17.2%   |
| 3     | 3         | 3.23%   |
| 0     | 1         | 1.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 46        | 33.09%  |
| Realtek Semiconductor      | 39        | 28.06%  |
| Qualcomm Atheros           | 26        | 18.71%  |
| Broadcom                   | 7         | 5.04%   |
| MediaTek                   | 3         | 2.16%   |
| Samsung Electronics        | 2         | 1.44%   |
| Ralink Technology          | 2         | 1.44%   |
| Marvell Technology Group   | 2         | 1.44%   |
| ZTE WCDMA Technologies MSM | 1         | 0.72%   |
| VIA Technologies           | 1         | 0.72%   |
| TP-Link                    | 1         | 0.72%   |
| Sierra Wireless            | 1         | 0.72%   |
| Ralink                     | 1         | 0.72%   |
| NetGear                    | 1         | 0.72%   |
| JMicron Technology         | 1         | 0.72%   |
| Huawei Technologies        | 1         | 0.72%   |
| DisplayLink                | 1         | 0.72%   |
| Dell                       | 1         | 0.72%   |
| Broadcom Limited           | 1         | 0.72%   |
| ASIX Electronics           | 1         | 0.72%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 20        | 11.43%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 11        | 6.29%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 8         | 4.57%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 3.43%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 2.86%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 2.29%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 2.29%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 2.29%   |
| Intel Wireless 7265                                                     | 4         | 2.29%   |
| Intel Wireless 7260                                                     | 4         | 2.29%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 2.29%   |
| Intel Wireless 8260                                                     | 3         | 1.71%   |
| Intel Ethernet Connection (6) I219-V                                    | 3         | 1.71%   |
| Intel Ethernet Connection (3) I218-LM                                   | 3         | 1.71%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 2         | 1.14%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.14%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.14%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2         | 1.14%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 1.14%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 2         | 1.14%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.14%   |
| Intel Wireless 8265 / 8275                                              | 2         | 1.14%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 1.14%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 2         | 1.14%   |
| Intel Ethernet Connection I217-LM                                       | 2         | 1.14%   |
| Intel Ethernet Connection (7) I219-LM                                   | 2         | 1.14%   |
| Intel Ethernet Connection (4) I219-LM                                   | 2         | 1.14%   |
| Intel Centrino Advanced-N 6235                                          | 2         | 1.14%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 1.14%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 1.14%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller       | 2         | 1.14%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 1.14%   |
| ZTE WCDMA MSM SCSI CD-ROM 2.31                                          | 1         | 0.57%   |
| VIA VT6105/VT6106S [Rhine-III]                                          | 1         | 0.57%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]         | 1         | 0.57%   |
| Sierra Wireless EM7455                                                  | 1         | 0.57%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.57%   |
| Realtek RTL8187SE Wireless LAN Controller                               | 1         | 0.57%   |
| Realtek RTL8187B Wireless Adapter                                       | 1         | 0.57%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                         | 1         | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 38        | 44.19%  |
| Qualcomm Atheros      | 23        | 26.74%  |
| Realtek Semiconductor | 12        | 13.95%  |
| Broadcom              | 4         | 4.65%   |
| Ralink Technology     | 2         | 2.33%   |
| MediaTek              | 2         | 2.33%   |
| Sierra Wireless       | 1         | 1.16%   |
| Ralink                | 1         | 1.16%   |
| NetGear               | 1         | 1.16%   |
| Dell                  | 1         | 1.16%   |
| Broadcom Limited      | 1         | 1.16%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 6.98%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 5.81%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 4.65%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 4.65%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 4.65%   |
| Intel Wireless 7265                                                     | 4         | 4.65%   |
| Intel Wireless 7260                                                     | 4         | 4.65%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 4.65%   |
| Intel Wireless 8260                                                     | 3         | 3.49%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 2.33%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 2.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2         | 2.33%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 2.33%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 2         | 2.33%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 2.33%   |
| Intel Wireless 8265 / 8275                                              | 2         | 2.33%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 2.33%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 2         | 2.33%   |
| Intel Centrino Advanced-N 6235                                          | 2         | 2.33%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 2.33%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 2.33%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 2.33%   |
| Sierra Wireless EM7455                                                  | 1         | 1.16%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.16%   |
| Realtek RTL8187SE Wireless LAN Controller                               | 1         | 1.16%   |
| Realtek RTL8187B Wireless Adapter                                       | 1         | 1.16%   |
| Realtek 802.11ac NIC                                                    | 1         | 1.16%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 1.16%   |
| Ralink MT7601U Wireless Adapter                                         | 1         | 1.16%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 1.16%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 1.16%   |
| NetGear WG111v3 54 Mbps Wireless [realtek RTL8187B]                     | 1         | 1.16%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 1         | 1.16%   |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter                     | 1         | 1.16%   |
| Intel Wireless-AC 9260                                                  | 1         | 1.16%   |
| Intel WiFi Link 5100                                                    | 1         | 1.16%   |
| Intel Wi-Fi 6 AX201                                                     | 1         | 1.16%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 1.16%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 1         | 1.16%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 1         | 1.16%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 35        | 40.7%   |
| Intel                      | 31        | 36.05%  |
| Qualcomm Atheros           | 5         | 5.81%   |
| Broadcom                   | 3         | 3.49%   |
| Samsung Electronics        | 2         | 2.33%   |
| Marvell Technology Group   | 2         | 2.33%   |
| ZTE WCDMA Technologies MSM | 1         | 1.16%   |
| VIA Technologies           | 1         | 1.16%   |
| TP-Link                    | 1         | 1.16%   |
| MediaTek                   | 1         | 1.16%   |
| JMicron Technology         | 1         | 1.16%   |
| Huawei Technologies        | 1         | 1.16%   |
| DisplayLink                | 1         | 1.16%   |
| ASIX Electronics           | 1         | 1.16%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 20        | 23.26%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11        | 12.79%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 9.3%    |
| Intel Ethernet Connection (6) I219-V                              | 3         | 3.49%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 3.49%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 2.33%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 2.33%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 2.33%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 2.33%   |
| ZTE WCDMA MSM SCSI CD-ROM 2.31                                    | 1         | 1.16%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1         | 1.16%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 1.16%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 1.16%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.16%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.16%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.16%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.16%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.16%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.16%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 1.16%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.16%   |
| MediaTek Infinix HOT 11S NFC                                      | 1         | 1.16%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 1.16%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 1.16%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 1.16%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.16%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.16%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.16%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.16%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.16%   |
| Intel Ethernet Connection (16) I219-V                             | 1         | 1.16%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 1.16%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.16%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 1.16%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.16%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                | 1         | 1.16%   |
| Huawei E353/E3131                                                 | 1         | 1.16%   |
| DisplayLink USB3.0 dock                                           | 1         | 1.16%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.16%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 1.16%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 83        | 50.3%   |
| Ethernet | 79        | 47.88%  |
| Modem    | 3         | 1.82%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 62        | 66.67%  |
| Ethernet | 31        | 33.33%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 70        | 78.65%  |
| 1     | 15        | 16.85%  |
| 0     | 4         | 4.49%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 75        | 84.27%  |
| Yes  | 14        | 15.73%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 24        | 42.11%  |
| Qualcomm Atheros Communications | 7         | 12.28%  |
| Realtek Semiconductor           | 6         | 10.53%  |
| Broadcom                        | 4         | 7.02%   |
| Lite-On Technology              | 3         | 5.26%   |
| IMC Networks                    | 2         | 3.51%   |
| Foxconn International           | 2         | 3.51%   |
| Foxconn / Hon Hai               | 2         | 3.51%   |
| Dell                            | 2         | 3.51%   |
| Cambridge Silicon Radio         | 2         | 3.51%   |
| TP-Link                         | 1         | 1.75%   |
| Realtek                         | 1         | 1.75%   |
| Ralink                          | 1         | 1.75%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 11        | 19.3%   |
| Realtek Bluetooth Radio                             | 6         | 10.53%  |
| Qualcomm Atheros  Bluetooth Device                  | 6         | 10.53%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 5         | 8.77%   |
| Intel AX200 Bluetooth                               | 4         | 7.02%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 3.51%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 3.51%   |
| Foxconn International BCM43142A0 Bluetooth module   | 2         | 3.51%   |
| Dell BCM20702A0 Bluetooth Module                    | 2         | 3.51%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 3.51%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 3.51%   |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 3.51%   |
| TP-Link UB5A Adapter                                | 1         | 1.75%   |
| Realtek Bluetooth Radio                             | 1         | 1.75%   |
| Ralink RT3290 Bluetooth                             | 1         | 1.75%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.75%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 1.75%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.75%   |
| Intel Bluetooth Device                              | 1         | 1.75%   |
| IMC Networks BCM20702A0                             | 1         | 1.75%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 1.75%   |
| Foxconn / Hon Hai BT                                | 1         | 1.75%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 1.75%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 71        | 69.61%  |
| AMD                   | 17        | 16.67%  |
| Nvidia                | 6         | 5.88%   |
| C-Media Electronics   | 4         | 3.92%   |
| Realtek Semiconductor | 1         | 0.98%   |
| GYROCOM C&C           | 1         | 0.98%   |
| GN Netcom             | 1         | 0.98%   |
| Blue Microphones      | 1         | 0.98%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 9         | 7.03%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 7         | 5.47%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 7         | 5.47%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 4.69%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 3.91%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 3.91%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 3.91%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 3.13%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 3.13%   |
| Intel Broadwell-U Audio Controller                                                                | 4         | 3.13%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 3.13%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 2.34%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 2.34%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 2.34%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 2.34%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 2.34%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 2.34%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 2.34%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 2.34%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 2.34%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 2.34%   |
| AMD FCH Azalia Controller                                                                         | 3         | 2.34%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 1.56%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 2         | 1.56%   |
| C-Media Electronics CM106 Like Sound Device                                                       | 2         | 1.56%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 2         | 1.56%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 1.56%   |
| AMD Navi 10 HDMI Audio                                                                            | 2         | 1.56%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 1.56%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 1.56%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.78%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.78%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.78%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.78%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 0.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.78%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 1         | 0.78%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 1         | 0.78%   |
| Intel 200 Series PCH HD Audio                                                                     | 1         | 0.78%   |
| GYROCOM C&C Fiio E10                                                                              | 1         | 0.78%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 25        | 29.41%  |
| SK hynix            | 15        | 17.65%  |
| Unknown             | 8         | 9.41%   |
| Kingston            | 7         | 8.24%   |
| Crucial             | 5         | 5.88%   |
| A-DATA Technology   | 5         | 5.88%   |
| Micron Technology   | 4         | 4.71%   |
| G.Skill             | 3         | 3.53%   |
| Nanya Technology    | 2         | 2.35%   |
| Unknown             | 2         | 2.35%   |
| Unknown (F785)      | 1         | 1.18%   |
| Unknown (ABCD)      | 1         | 1.18%   |
| Smart               | 1         | 1.18%   |
| Ramaxel Technology  | 1         | 1.18%   |
| Goldkey             | 1         | 1.18%   |
| Corsair             | 1         | 1.18%   |
| Apacer              | 1         | 1.18%   |
| A Force             | 1         | 1.18%   |
| 4ea5                | 1         | 1.18%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 3.06%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 3.06%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 2         | 2.04%   |
| Unknown RAM Module 1024MB SODIMM DDR                             | 2         | 2.04%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 2.04%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 2         | 2.04%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 2         | 2.04%   |
| Unknown                                                          | 2         | 2.04%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 1.02%   |
| Unknown RAM Module 512MB SODIMM DDR                              | 1         | 1.02%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 1.02%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                         | 1         | 1.02%   |
| Unknown RAM Module 1GB SODIMM DDR3 1066MT/s                      | 1         | 1.02%   |
| Unknown RAM Module 1024MB SODIMM DDR2                            | 1         | 1.02%   |
| Unknown (F785) RAM Module 16GB SODIMM DDR4 3200MT/s              | 1         | 1.02%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 1         | 1.02%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 1         | 1.02%   |
| Smart RAM SF564128CJ8NWMNSEG 4GB SODIMM DDR3 1600MT/s            | 1         | 1.02%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1066MT/s                     | 1         | 1.02%   |
| SK hynix RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s          | 1         | 1.02%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s            | 1         | 1.02%   |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 1.02%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.02%   |
| SK hynix RAM HMT41GS6DFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.02%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 1         | 1.02%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.02%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.02%   |
| SK hynix RAM HMT325S6BFR8C-G7 2GB SODIMM DDR3 1067MT/s           | 1         | 1.02%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.02%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 1.02%   |
| SK hynix RAM HMA851S6CJR6N-VK 4096MB SODIMM DDR4 2667MT/s        | 1         | 1.02%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 1         | 1.02%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.02%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 1.02%   |
| Samsung RAM M471B5773DH0-CH9 2048MB SODIMM DDR3 1600MT/s         | 1         | 1.02%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 1         | 1.02%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s            | 1         | 1.02%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s            | 1         | 1.02%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.02%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.02%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 32        | 43.24%  |
| DDR4    | 27        | 36.49%  |
| DDR2    | 5         | 6.76%   |
| DDR     | 3         | 4.05%   |
| SDRAM   | 2         | 2.7%    |
| LPDDR4  | 2         | 2.7%    |
| LPDDR3  | 2         | 2.7%    |
| Unknown | 1         | 1.35%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 69        | 94.52%  |
| Row Of Chips | 2         | 2.74%   |
| Chip         | 1         | 1.37%   |
| Unknown      | 1         | 1.37%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 30        | 34.48%  |
| 4096  | 24        | 27.59%  |
| 2048  | 14        | 16.09%  |
| 16384 | 11        | 12.64%  |
| 1024  | 6         | 6.9%    |
| 32768 | 1         | 1.15%   |
| 512   | 1         | 1.15%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 21        | 26.58%  |
| 2667    | 14        | 17.72%  |
| 3200    | 9         | 11.39%  |
| 2400    | 6         | 7.59%   |
| Unknown | 5         | 6.33%   |
| 1333    | 4         | 5.06%   |
| 1067    | 4         | 5.06%   |
| 3266    | 3         | 3.8%    |
| 4199    | 2         | 2.53%   |
| 2133    | 2         | 2.53%   |
| 1066    | 2         | 2.53%   |
| 800     | 2         | 2.53%   |
| 667     | 2         | 2.53%   |
| 1334    | 1         | 1.27%   |
| 1200    | 1         | 1.27%   |
| 975     | 1         | 1.27%   |

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
| Chicony Electronics                    | 25        | 37.31%  |
| Microdia                               | 7         | 10.45%  |
| Sunplus Innovation Technology          | 5         | 7.46%   |
| Realtek Semiconductor                  | 4         | 5.97%   |
| IMC Networks                           | 4         | 5.97%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 5.97%   |
| Bison Electronics                      | 4         | 5.97%   |
| Acer                                   | 3         | 4.48%   |
| Suyin                                  | 2         | 2.99%   |
| Quanta                                 | 2         | 2.99%   |
| Lite-On Technology                     | 2         | 2.99%   |
| Samsung Electronics                    | 1         | 1.49%   |
| OmniVision Technologies                | 1         | 1.49%   |
| Mustek Systems                         | 1         | 1.49%   |
| Logitech                               | 1         | 1.49%   |
| kingcome                               | 1         | 1.49%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 7         | 10.45%  |
| Chicony HD WebCam                        | 3         | 4.48%   |
| Sunplus Integrated_Webcam_HD             | 2         | 2.99%   |
| Realtek Integrated_Webcam_HD             | 2         | 2.99%   |
| IMC Networks Integrated Camera           | 2         | 2.99%   |
| Chicony HP TrueVision HD Camera          | 2         | 2.99%   |
| Chicony EasyCamera                       | 2         | 2.99%   |
| Suyin Acer/Lenovo Webcam [CN0316]        | 1         | 1.49%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 1         | 1.49%   |
| Sunplus Laptop Integrated Webcam HD      | 1         | 1.49%   |
| Sunplus Asus Webcam                      | 1         | 1.49%   |
| Sunplus 720p HD Camera                   | 1         | 1.49%   |
| Samsung Galaxy series, misc. (MTP mode)  | 1         | 1.49%   |
| Realtek Lenovo EasyCamera                | 1         | 1.49%   |
| Realtek Integrated Webcam_HD             | 1         | 1.49%   |
| Quanta Sony Visual Communication Camera  | 1         | 1.49%   |
| Quanta HP HD Camera                      | 1         | 1.49%   |
| OmniVision OV2640 Webcam                 | 1         | 1.49%   |
| Mustek Systems USB 2.0 PC Camera         | 1         | 1.49%   |
| Microdia Webcam Vitade AF                | 1         | 1.49%   |
| Microdia WebCam SC-13HDL12639P           | 1         | 1.49%   |
| Microdia Sonix USB 2.0 Camera            | 1         | 1.49%   |
| Microdia Integrated_Webcam_HD            | 1         | 1.49%   |
| Microdia Integrated Webcam               | 1         | 1.49%   |
| Microdia Dell Integrated HD Webcam       | 1         | 1.49%   |
| Microdia 1.3 MPixel Integrated Webcam    | 1         | 1.49%   |
| Logitech HD Pro Webcam C920              | 1         | 1.49%   |
| Lite-On Integrated Camera                | 1         | 1.49%   |
| Lite-On HP HD Webcam                     | 1         | 1.49%   |
| kingcome 480p VGA Camera                 | 1         | 1.49%   |
| IMC Networks Lenovo EasyCamera           | 1         | 1.49%   |
| IMC Networks Integrated Webcam           | 1         | 1.49%   |
| Chicony WebCam                           | 1         | 1.49%   |
| Chicony VGA WebCam                       | 1         | 1.49%   |
| Chicony USB2.0 HD UVC WebCam             | 1         | 1.49%   |
| Chicony USB 2.0 Camera                   | 1         | 1.49%   |
| Chicony TOSHIBA Web Camera - FHD         | 1         | 1.49%   |
| Chicony Thinkpad T430 camera             | 1         | 1.49%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 1         | 1.49%   |
| Chicony Lenovo EasyCamera                | 1         | 1.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 4         | 44.44%  |
| STMicroelectronics         | 2         | 22.22%  |
| Validity Sensors           | 1         | 11.11%  |
| Upek                       | 1         | 11.11%  |
| Shenzhen Goodix Technology | 1         | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 2         | 22.22%  |
| STMicroelectronics Fingerprint Reader                  | 2         | 22.22%  |
| Validity Sensors Synaptics WBDI                        | 1         | 11.11%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 11.11%  |
| Synaptics WBDI Device                                  | 1         | 11.11%  |
| Synaptics Fingerprint reader [HP G6]                   | 1         | 11.11%  |
| Shenzhen Goodix Fingerprint Reader                     | 1         | 11.11%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 8         | 57.14%  |
| Alcor Micro | 5         | 35.71%  |
| Lenovo      | 1         | 7.14%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 5         | 35.71%  |
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 21.43%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 14.29%  |
| Broadcom 5880                                                                | 2         | 14.29%  |
| Lenovo Integrated Smart Card Reader                                          | 1         | 7.14%   |
| Broadcom 58200                                                               | 1         | 7.14%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 62        | 66.67%  |
| 1     | 23        | 24.73%  |
| 2     | 5         | 5.38%   |
| 3     | 2         | 2.15%   |
| 5     | 1         | 1.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 9         | 26.47%  |
| Chipcard                 | 9         | 26.47%  |
| Graphics card            | 5         | 14.71%  |
| Net/wireless             | 4         | 11.76%  |
| Camera                   | 3         | 8.82%   |
| Communication controller | 2         | 5.88%   |
| Bluetooth                | 2         | 5.88%   |

