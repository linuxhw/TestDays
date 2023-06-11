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

Total: 94

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Devuan 4                | 39        | 50%     |
| Devuan 3                | 14        | 17.95%  |
| Devuan 5                | 12        | 15.38%  |
| Devuan Testing/unstable | 8         | 10.26%  |
| Devuan                  | 3         | 3.85%   |
| Devuan 3.0              | 1         | 1.28%   |
| Devuan 2.1              | 1         | 1.28%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Devuan | 74        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Notebooks | Percent |
|-----------------------|-----------|---------|
| 5.10.0-21-amd64       | 8         | 9.64%   |
| 5.10.0-16-amd64       | 5         | 6.02%   |
| 5.10.0-9-amd64        | 4         | 4.82%   |
| 5.10.0-13-amd64       | 4         | 4.82%   |
| 4.19.0-9-amd64        | 4         | 4.82%   |
| 5.7.0-2-amd64         | 3         | 3.61%   |
| 5.10.0-8-amd64        | 3         | 3.61%   |
| 5.10.0-18-amd64       | 3         | 3.61%   |
| 5.10.0-10-amd64       | 3         | 3.61%   |
| 6.1.0-6-amd64         | 2         | 2.41%   |
| 5.18.0-2-amd64        | 2         | 2.41%   |
| 5.10.0-20-amd64       | 2         | 2.41%   |
| 5.10.0-19-amd64       | 2         | 2.41%   |
| 5.10.0-11-amd64       | 2         | 2.41%   |
| 4.19.0-17-amd64       | 2         | 2.41%   |
| 4.19.0-16-amd64       | 2         | 2.41%   |
| 4.19.0-14-amd64       | 2         | 2.41%   |
| 6.1.25                | 1         | 1.2%    |
| 6.1.0-9-amd64         | 1         | 1.2%    |
| 6.1.0-7-amd64         | 1         | 1.2%    |
| 6.1.0-0.deb11.6-amd64 | 1         | 1.2%    |
| 6.0.0-5-amd64         | 1         | 1.2%    |
| 6.0.0-2-amd64         | 1         | 1.2%    |
| 6.0.0-0.deb11.6-amd64 | 1         | 1.2%    |
| 5.9.0-4-amd64         | 1         | 1.2%    |
| 5.8.0-1-amd64         | 1         | 1.2%    |
| 5.7.0-0.bpo.2-amd64   | 1         | 1.2%    |
| 5.6.0-2-amd64         | 1         | 1.2%    |
| 5.19.0-2-amd64        | 1         | 1.2%    |
| 5.18.0-1-amd64        | 1         | 1.2%    |
| 5.15.5-xanmod1        | 1         | 1.2%    |
| 5.15.0-2-amd64        | 1         | 1.2%    |
| 5.14.0-4-amd64        | 1         | 1.2%    |
| 5.10.0-7-amd64        | 1         | 1.2%    |
| 5.10.0-4-amd64        | 1         | 1.2%    |
| 5.10.0-15-amd64       | 1         | 1.2%    |
| 5.10.0-14-amd64       | 1         | 1.2%    |
| 5.10.0-1-amd64        | 1         | 1.2%    |
| 5.1.21                | 1         | 1.2%    |
| 4.9.0-14-amd64        | 1         | 1.2%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 38        | 47.5%   |
| 4.19.0  | 13        | 16.25%  |
| 6.1.0   | 5         | 6.25%   |
| 5.7.0   | 4         | 5%      |
| 4.9.0   | 4         | 5%      |
| 6.0.0   | 3         | 3.75%   |
| 5.18.0  | 3         | 3.75%   |
| 6.1.25  | 1         | 1.25%   |
| 5.9.0   | 1         | 1.25%   |
| 5.8.0   | 1         | 1.25%   |
| 5.6.0   | 1         | 1.25%   |
| 5.19.0  | 1         | 1.25%   |
| 5.15.5  | 1         | 1.25%   |
| 5.15.0  | 1         | 1.25%   |
| 5.14.0  | 1         | 1.25%   |
| 5.1.21  | 1         | 1.25%   |
| 4.4.195 | 1         | 1.25%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 38        | 47.5%   |
| 4.19    | 13        | 16.25%  |
| 6.1     | 6         | 7.5%    |
| 5.7     | 4         | 5%      |
| 4.9     | 4         | 5%      |
| 6.0     | 3         | 3.75%   |
| 5.18    | 3         | 3.75%   |
| 5.15    | 2         | 2.5%    |
| 5.9     | 1         | 1.25%   |
| 5.8     | 1         | 1.25%   |
| 5.6     | 1         | 1.25%   |
| 5.19    | 1         | 1.25%   |
| 5.14    | 1         | 1.25%   |
| 5.1     | 1         | 1.25%   |
| 4.4     | 1         | 1.25%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 70        | 94.59%  |
| i686   | 3         | 4.05%   |
| armv7l | 1         | 1.35%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| XFCE          | 32        | 41.03%  |
| KDE5          | 13        | 16.67%  |
| MATE          | 10        | 12.82%  |
| Unknown       | 9         | 11.54%  |
| i3            | 4         | 5.13%   |
| LXDE          | 3         | 3.85%   |
| GNOME         | 2         | 2.56%   |
| Enlightenment | 2         | 2.56%   |
| Openbox       | 1         | 1.28%   |
| LXQt          | 1         | 1.28%   |
| Cinnamon      | 1         | 1.28%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 70        | 92.11%  |
| Tty     | 3         | 3.95%   |
| Unknown | 2         | 2.63%   |
| Wayland | 1         | 1.32%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SLiM    | 24        | 31.17%  |
| LightDM | 22        | 28.57%  |
| Unknown | 20        | 25.97%  |
| SDDM    | 7         | 9.09%   |
| XDM     | 1         | 1.3%    |
| Ly      | 1         | 1.3%    |
| LXDM    | 1         | 1.3%    |
| GDM3    | 1         | 1.3%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| en_US       | 34        | 45.33%  |
| en_GB       | 14        | 18.67%  |
| ru_RU       | 7         | 9.33%   |
| pt_BR       | 3         | 4%      |
| it_IT       | 2         | 2.67%   |
| es_ES       | 2         | 2.67%   |
| de_DE       | 2         | 2.67%   |
| de_AT       | 2         | 2.67%   |
| Unknown     | 2         | 2.67%   |
| ru_UA       | 1         | 1.33%   |
| pl_PL       | 1         | 1.33%   |
| fr_BE       | 1         | 1.33%   |
| es_SV       | 1         | 1.33%   |
| en_US.utf-8 | 1         | 1.33%   |
| de_CH       | 1         | 1.33%   |
| C           | 1         | 1.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 39        | 52%     |
| EFI  | 36        | 48%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 61        | 82.43%  |
| Xfs     | 4         | 5.41%   |
| Btrfs   | 4         | 5.41%   |
| Unknown | 3         | 4.05%   |
| OveXlay | 1         | 1.35%   |
| Ext2    | 1         | 1.35%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 38        | 50%     |
| MBR     | 27        | 35.53%  |
| Unknown | 11        | 14.47%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 66        | 89.19%  |
| Yes       | 8         | 10.81%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 60        | 80%     |
| Yes       | 15        | 20%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 22        | 29.73%  |
| Dell                | 14        | 18.92%  |
| Hewlett-Packard     | 8         | 10.81%  |
| Acer                | 5         | 6.76%   |
| ASUSTek Computer    | 4         | 5.41%   |
| Toshiba             | 3         | 4.05%   |
| MSI                 | 3         | 4.05%   |
| Google              | 2         | 2.7%    |
| Fujitsu Siemens     | 2         | 2.7%    |
| Teclast             | 1         | 1.35%   |
| Sony                | 1         | 1.35%   |
| Samsung Electronics | 1         | 1.35%   |
| Notebook            | 1         | 1.35%   |
| Nokia               | 1         | 1.35%   |
| MTC                 | 1         | 1.35%   |
| IBM                 | 1         | 1.35%   |
| HUAWEI              | 1         | 1.35%   |
| Fujitsu             | 1         | 1.35%   |
| CCE                 | 1         | 1.35%   |
| Unknown             | 1         | 1.35%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                                                     | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Toshiba Satellite Pro A50-C                                                              | 1         | 1.35%   |
| Toshiba Satellite M40X                                                                   | 1         | 1.35%   |
| Toshiba Satellite L655                                                                   | 1         | 1.35%   |
| Teclast F6 Plus                                                                          | 1         | 1.35%   |
| Sony VPCEE23FX                                                                           | 1         | 1.35%   |
| Samsung 355V4C/355V4X/355V5C/355V5X/356V4C/356V4X/356V5C/356V5X/3445VC/3445VX/3545VC/354 | 1         | 1.35%   |
| Notebook W230ST                                                                          | 1         | 1.35%   |
| Nokia N900                                                                               | 1         | 1.35%   |
| MTC Montara-GML                                                                          | 1         | 1.35%   |
| MSI MS-1688                                                                              | 1         | 1.35%   |
| MSI Modern 15 A5M                                                                        | 1         | 1.35%   |
| MSI Bravo 15 A4DDR                                                                       | 1         | 1.35%   |
| Lenovo V310-14ISK 80SX                                                                   | 1         | 1.35%   |
| Lenovo ThinkPad X60 1707YF8                                                              | 1         | 1.35%   |
| Lenovo ThinkPad X250 20CLS7WY04                                                          | 1         | 1.35%   |
| Lenovo ThinkPad X230 2325DE0                                                             | 1         | 1.35%   |
| Lenovo ThinkPad X230 23247S0                                                             | 1         | 1.35%   |
| Lenovo ThinkPad X220 429053G                                                             | 1         | 1.35%   |
| Lenovo ThinkPad X200 74585FU                                                             | 1         | 1.35%   |
| Lenovo ThinkPad X1 Carbon 7th 20QD00L1PB                                                 | 1         | 1.35%   |
| Lenovo ThinkPad T560 20FJS1J200                                                          | 1         | 1.35%   |
| Lenovo ThinkPad T550 20CJS1VD01                                                          | 1         | 1.35%   |
| Lenovo ThinkPad T480 20L5CTO1WW                                                          | 1         | 1.35%   |
| Lenovo ThinkPad T470s 20HGS00P00                                                         | 1         | 1.35%   |
| Lenovo ThinkPad T440p                                                                    | 1         | 1.35%   |
| Lenovo ThinkPad T430 2349I46                                                             | 1         | 1.35%   |
| Lenovo ThinkPad T420 4180AG3                                                             | 1         | 1.35%   |
| Lenovo ThinkPad T14 Gen 3 21AHCTO1WW                                                     | 1         | 1.35%   |
| Lenovo S20-30 20421                                                                      | 1         | 1.35%   |
| Lenovo IdeaPad Z370                                                                      | 1         | 1.35%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK                                                    | 1         | 1.35%   |
| Lenovo IdeaPad 530S-14ARR 81H1                                                           | 1         | 1.35%   |
| Lenovo IdeaPad 130-15AST 81H5                                                            | 1         | 1.35%   |
| Lenovo G50-30 80G0                                                                       | 1         | 1.35%   |
| IBM ThinkPad T41p 2373GHG                                                                | 1         | 1.35%   |
| HUAWEI HN-WX9X                                                                           | 1         | 1.35%   |
| HP ProBook 6475b                                                                         | 1         | 1.35%   |
| HP ProBook 640 G1                                                                        | 1         | 1.35%   |
| HP Pavilion 11 x360 PC                                                                   | 1         | 1.35%   |
| HP Notebook                                                                              | 1         | 1.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 15        | 20.27%  |
| Dell Latitude           | 9         | 12.16%  |
| Lenovo IdeaPad          | 4         | 5.41%   |
| Acer Aspire             | 4         | 5.41%   |
| Toshiba Satellite       | 3         | 4.05%   |
| HP Laptop               | 3         | 4.05%   |
| HP ProBook              | 2         | 2.7%    |
| Dell Inspiron           | 2         | 2.7%    |
| Teclast F6              | 1         | 1.35%   |
| Sony VPCEE23FX          | 1         | 1.35%   |
| Samsung 355V4C          | 1         | 1.35%   |
| Notebook W230ST         | 1         | 1.35%   |
| Nokia N900              | 1         | 1.35%   |
| MTC Montara-GML         | 1         | 1.35%   |
| MSI MS-1688             | 1         | 1.35%   |
| MSI Modern              | 1         | 1.35%   |
| MSI Bravo               | 1         | 1.35%   |
| Lenovo V310-14ISK       | 1         | 1.35%   |
| Lenovo S20-30           | 1         | 1.35%   |
| Lenovo G50-30           | 1         | 1.35%   |
| IBM ThinkPad            | 1         | 1.35%   |
| HUAWEI HN-WX9X          | 1         | 1.35%   |
| HP Pavilion             | 1         | 1.35%   |
| HP Notebook             | 1         | 1.35%   |
| HP 250                  | 1         | 1.35%   |
| Google Cyan             | 1         | 1.35%   |
| Google Bluebird         | 1         | 1.35%   |
| Fujitsu Siemens ESPRIMO | 1         | 1.35%   |
| Fujitsu Siemens AMILO   | 1         | 1.35%   |
| Fujitsu LIFEBOOK        | 1         | 1.35%   |
| Dell XPS                | 1         | 1.35%   |
| Dell Precision          | 1         | 1.35%   |
| Dell G5                 | 1         | 1.35%   |
| CCE Capella             | 1         | 1.35%   |
| ASUS X555LJ             | 1         | 1.35%   |
| ASUS K55VJ              | 1         | 1.35%   |
| ASUS K52F               | 1         | 1.35%   |
| ASUS G750JM             | 1         | 1.35%   |
| Acer Extensa            | 1         | 1.35%   |
| Unknown                 | 1         | 1.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2012    | 9         | 12.16%  |
| 2019    | 7         | 9.46%   |
| 2018    | 7         | 9.46%   |
| 2014    | 6         | 8.11%   |
| 2013    | 5         | 6.76%   |
| 2021    | 4         | 5.41%   |
| 2020    | 4         | 5.41%   |
| 2016    | 4         | 5.41%   |
| 2011    | 4         | 5.41%   |
| 2010    | 4         | 5.41%   |
| 2017    | 3         | 4.05%   |
| 2015    | 3         | 4.05%   |
| 2009    | 3         | 4.05%   |
| 2022    | 2         | 2.7%    |
| 2008    | 2         | 2.7%    |
| 2006    | 2         | 2.7%    |
| 2005    | 2         | 2.7%    |
| 2023    | 1         | 1.35%   |
| 2007    | 1         | 1.35%   |
| Unknown | 1         | 1.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 74        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 72        | 97.3%   |
| Enabled  | 2         | 2.7%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 70        | 94.59%  |
| Yes  | 4         | 5.41%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 19        | 25.68%  |
| 8.01-16.0   | 17        | 22.97%  |
| 3.01-4.0    | 14        | 18.92%  |
| 16.01-24.0  | 10        | 13.51%  |
| 1.01-2.0    | 4         | 5.41%   |
| 32.01-64.0  | 3         | 4.05%   |
| 2.01-3.0    | 3         | 4.05%   |
| 0.01-0.5    | 2         | 2.7%    |
| 24.01-32.0  | 1         | 1.35%   |
| 64.01-256.0 | 1         | 1.35%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 31        | 38.27%  |
| 4.01-8.0   | 16        | 19.75%  |
| 3.01-4.0   | 12        | 14.81%  |
| 2.01-3.0   | 9         | 11.11%  |
| 0.51-1.0   | 6         | 7.41%   |
| 8.01-16.0  | 3         | 3.7%    |
| 0.01-0.5   | 3         | 3.7%    |
| 32.01-64.0 | 1         | 1.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 57        | 76%     |
| 2      | 14        | 18.67%  |
| 3      | 4         | 5.33%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 47        | 62.67%  |
| Yes       | 28        | 37.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 65        | 87.84%  |
| No        | 9         | 12.16%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 71        | 95.95%  |
| No        | 3         | 4.05%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 49        | 65.33%  |
| No        | 26        | 34.67%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 12        | 16%     |
| Germany     | 9         | 12%     |
| Russia      | 6         | 8%      |
| Brazil      | 5         | 6.67%   |
| Ukraine     | 4         | 5.33%   |
| Italy       | 3         | 4%      |
| Grenada     | 3         | 4%      |
| France      | 3         | 4%      |
| Spain       | 2         | 2.67%   |
| Portugal    | 2         | 2.67%   |
| Poland      | 2         | 2.67%   |
| Netherlands | 2         | 2.67%   |
| Hungary     | 2         | 2.67%   |
| Finland     | 2         | 2.67%   |
| Austria     | 2         | 2.67%   |
| Vietnam     | 1         | 1.33%   |
| UK          | 1         | 1.33%   |
| Switzerland | 1         | 1.33%   |
| Slovakia    | 1         | 1.33%   |
| Serbia      | 1         | 1.33%   |
| Romania     | 1         | 1.33%   |
| Norway      | 1         | 1.33%   |
| Mexico      | 1         | 1.33%   |
| Lithuania   | 1         | 1.33%   |
| Israel      | 1         | 1.33%   |
| Indonesia   | 1         | 1.33%   |
| Greece      | 1         | 1.33%   |
| Georgia     | 1         | 1.33%   |
| El Salvador | 1         | 1.33%   |
| Belarus     | 1         | 1.33%   |
| Bangladesh  | 1         | 1.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Saint George's     | 3         | 4%      |
| Nadudvar           | 2         | 2.67%   |
| Milan              | 2         | 2.67%   |
| Kyiv               | 2         | 2.67%   |
| Ft. Washington     | 2         | 2.67%   |
| Bagnolet           | 2         | 2.67%   |
| Amsterdam          | 2         | 2.67%   |
| Yakutsk            | 1         | 1.33%   |
| Wroclaw            | 1         | 1.33%   |
| Willich            | 1         | 1.33%   |
| Wildberg           | 1         | 1.33%   |
| Vilnius            | 1         | 1.33%   |
| Trubchëvsk        | 1         | 1.33%   |
| Thessaloniki       | 1         | 1.33%   |
| Tel Aviv           | 1         | 1.33%   |
| Tejgaon            | 1         | 1.33%   |
| Tbilisi            | 1         | 1.33%   |
| Staunton           | 1         | 1.33%   |
| St Petersburg      | 1         | 1.33%   |
| Siena              | 1         | 1.33%   |
| Sao Paulo          | 1         | 1.33%   |
| San Salvador       | 1         | 1.33%   |
| Rio de Janeiro     | 1         | 1.33%   |
| Praia Grande       | 1         | 1.33%   |
| Oslo               | 1         | 1.33%   |
| Novopskov          | 1         | 1.33%   |
| New York           | 1         | 1.33%   |
| Munich             | 1         | 1.33%   |
| Muenster-Sarmsheim | 1         | 1.33%   |
| Mountain View      | 1         | 1.33%   |
| Moscow             | 1         | 1.33%   |
| Maladzyechna       | 1         | 1.33%   |
| Madrid             | 1         | 1.33%   |
| Lisbon             | 1         | 1.33%   |
| Leonding           | 1         | 1.33%   |
| Leipzig            | 1         | 1.33%   |
| Krasnodar          | 1         | 1.33%   |
| Kouvola            | 1         | 1.33%   |
| Kharkiv            | 1         | 1.33%   |
| Katzenbach         | 1         | 1.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 14        | 15     | 14.89%  |
| Samsung Electronics | 13        | 19     | 13.83%  |
| Unknown             | 10        | 11     | 10.64%  |
| Kingston            | 6         | 6      | 6.38%   |
| Seagate             | 5         | 5      | 5.32%   |
| SanDisk             | 5         | 5      | 5.32%   |
| Hitachi             | 4         | 4      | 4.26%   |
| Crucial             | 4         | 4      | 4.26%   |
| Toshiba             | 3         | 3      | 3.19%   |
| SK hynix            | 3         | 3      | 3.19%   |
| PNY                 | 3         | 3      | 3.19%   |
| LITEON              | 3         | 6      | 3.19%   |
| HGST                | 3         | 3      | 3.19%   |
| Team                | 2         | 2      | 2.13%   |
| Intel               | 2         | 2      | 2.13%   |
| Fujitsu             | 2         | 2      | 2.13%   |
| Union Memory        | 1         | 2      | 1.06%   |
| UMIS                | 1         | 1      | 1.06%   |
| Teclast             | 1         | 1      | 1.06%   |
| Smart               | 1         | 1      | 1.06%   |
| SABRENT             | 1         | 2      | 1.06%   |
| Patriot             | 1         | 1      | 1.06%   |
| Mushkin             | 1         | 1      | 1.06%   |
| LITEONIT            | 1         | 1      | 1.06%   |
| KIOXIA              | 1         | 1      | 1.06%   |
| KingFast            | 1         | 1      | 1.06%   |
| HXY                 | 1         | 1      | 1.06%   |
| Hewlett-Packard     | 1         | 1      | 1.06%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Unknown MMC Card  32GB               | 3         | 3.13%   |
| Unknown MMC Card  128GB              | 3         | 3.13%   |
| PNY CS900 240GB SSD                  | 3         | 3.13%   |
| Samsung SSD 850 EVO 500GB            | 2         | 2.08%   |
| Samsung SSD 850 EVO 250GB            | 2         | 2.08%   |
| Kingston SA400S37480G 480GB SSD      | 2         | 2.08%   |
| Kingston SA400S37240G 240GB SSD      | 2         | 2.08%   |
| Crucial CT250MX500SSD1 250GB         | 2         | 2.08%   |
| Crucial CT1000MX500SSD1 1TB          | 2         | 2.08%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 1         | 1.04%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1         | 1.04%   |
| WDC WD7500BPKX-00HPJT0 752GB         | 1         | 1.04%   |
| WDC WD5000BPVT-24HXZT3 500GB         | 1         | 1.04%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 1         | 1.04%   |
| WDC WD3200BEVT-22A23T0 320GB         | 1         | 1.04%   |
| WDC WD3200BEVE-00A0HT0 320GB         | 1         | 1.04%   |
| WDC WD2500BEKT-00A25T0 250GB         | 1         | 1.04%   |
| WDC WD10SPZX-21Z10T0 1TB             | 1         | 1.04%   |
| WDC WD10JPCX-24UE4T0 1TB             | 1         | 1.04%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB | 1         | 1.04%   |
| WDC PC SN540 SDDPNPF-512G-1032 512GB | 1         | 1.04%   |
| WDC PC SN530 NVMe 256GB              | 1         | 1.04%   |
| WDC PC SN520 SDAPMUW-512G-1101 512GB | 1         | 1.04%   |
| Unknown SD04G  4GB                   | 1         | 1.04%   |
| Unknown SD  8GB                      | 1         | 1.04%   |
| Unknown MMC32G  32GB                 | 1         | 1.04%   |
| Unknown MMC Card  8GB                | 1         | 1.04%   |
| Unknown MMC Card  16GB               | 1         | 1.04%   |
| Union Memory RTOTJ128VGD2EYX 128GB   | 1         | 1.04%   |
| UMIS RPFTJ256PDD2MWX 256GB           | 1         | 1.04%   |
| Toshiba MK5065GSX 500GB              | 1         | 1.04%   |
| Toshiba MK1252GSX 120GB              | 1         | 1.04%   |
| Toshiba KBG30ZMV512G 512GB           | 1         | 1.04%   |
| Teclast 256GB NS550-2242 SSD         | 1         | 1.04%   |
| Team T253X1120G 120GB SSD            | 1         | 1.04%   |
| Team T253TD240G 240GB SSD            | 1         | 1.04%   |
| Smart SSD SZ9MSE mSATA 256GB         | 1         | 1.04%   |
| SK hynix SC311 SATA 256GB SSD        | 1         | 1.04%   |
| SK hynix PC611 NVMe 1TB              | 1         | 1.04%   |
| SK hynix PC401 NVMe 512GB            | 1         | 1.04%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 8         | 8      | 33.33%  |
| Seagate | 5         | 5      | 20.83%  |
| Hitachi | 4         | 4      | 16.67%  |
| HGST    | 3         | 3      | 12.5%   |
| Toshiba | 2         | 2      | 8.33%   |
| Fujitsu | 2         | 2      | 8.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 8      | 19.05%  |
| Kingston            | 6         | 6      | 14.29%  |
| SanDisk             | 5         | 5      | 11.9%   |
| Crucial             | 4         | 4      | 9.52%   |
| PNY                 | 3         | 3      | 7.14%   |
| WDC                 | 2         | 3      | 4.76%   |
| Team                | 2         | 2      | 4.76%   |
| LITEON              | 2         | 5      | 4.76%   |
| Union Memory        | 1         | 2      | 2.38%   |
| Teclast             | 1         | 1      | 2.38%   |
| Smart               | 1         | 1      | 2.38%   |
| SK hynix            | 1         | 1      | 2.38%   |
| SABRENT             | 1         | 2      | 2.38%   |
| Patriot             | 1         | 1      | 2.38%   |
| Mushkin             | 1         | 1      | 2.38%   |
| LITEONIT            | 1         | 1      | 2.38%   |
| HXY                 | 1         | 1      | 2.38%   |
| Hewlett-Packard     | 1         | 1      | 2.38%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 37        | 48     | 41.57%  |
| HDD     | 24        | 24     | 26.97%  |
| NVMe    | 17        | 23     | 19.1%   |
| MMC     | 10        | 11     | 11.24%  |
| Unknown | 1         | 1      | 1.12%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 55        | 70     | 65.48%  |
| NVMe | 17        | 23     | 20.24%  |
| MMC  | 10        | 11     | 11.9%   |
| SAS  | 2         | 3      | 2.38%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 46        | 54     | 79.31%  |
| 0.51-1.0   | 8         | 13     | 13.79%  |
| 1.01-2.0   | 2         | 2      | 3.45%   |
| 3.01-4.0   | 1         | 1      | 1.72%   |
| 10.01-20.0 | 1         | 2      | 1.72%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 22        | 28.57%  |
| 101-250        | 18        | 23.38%  |
| 501-1000       | 10        | 12.99%  |
| 51-100         | 8         | 10.39%  |
| 21-50          | 7         | 9.09%   |
| 1001-2000      | 4         | 5.19%   |
| Unknown        | 3         | 3.9%    |
| 2001-3000      | 2         | 2.6%    |
| 1-20           | 2         | 2.6%    |
| More than 3000 | 1         | 1.3%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 24        | 31.17%  |
| 101-250   | 15        | 19.48%  |
| 51-100    | 11        | 14.29%  |
| 251-500   | 9         | 11.69%  |
| 21-50     | 8         | 10.39%  |
| 1001-2000 | 3         | 3.9%    |
| 501-1000  | 3         | 3.9%    |
| Unknown   | 3         | 3.9%    |
| 2001-3000 | 1         | 1.3%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                         | Notebooks | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| WDC WD5000BPVT-24HXZT3 500GB  | 1         | 1      | 20%     |
| WDC WD3200BEVT-22A23T0 320GB  | 1         | 1      | 20%     |
| WDC WD10JPCX-24UE4T0 1TB      | 1         | 1      | 20%     |
| Hitachi HTS727575A9E364 752GB | 1         | 1      | 20%     |
| Hitachi HTS726060M9AT00 56GB  | 1         | 1      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 3         | 3      | 60%     |
| Hitachi | 2         | 2      | 40%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 3         | 3      | 60%     |
| Hitachi | 2         | 2      | 40%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 5         | 5      | 100%    |

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
| Works    | 57        | 76     | 69.51%  |
| Detected | 20        | 26     | 24.39%  |
| Malfunc  | 5         | 5      | 6.1%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 52        | 67.53%  |
| AMD                          | 9         | 11.69%  |
| Samsung Electronics          | 5         | 6.49%   |
| SanDisk                      | 4         | 5.19%   |
| SK hynix                     | 2         | 2.6%    |
| VIA Technologies             | 1         | 1.3%    |
| Union Memory (Shenzhen)      | 1         | 1.3%    |
| Toshiba America Info Systems | 1         | 1.3%    |
| Lite-On Technology           | 1         | 1.3%    |
| KIOXIA                       | 1         | 1.3%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 7         | 8.24%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 7         | 8.24%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 4         | 4.71%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 4         | 4.71%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 4         | 4.71%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 4         | 4.71%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 3         | 3.53%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 3         | 3.53%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 3         | 3.53%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 3         | 3.53%   |
| SanDisk Non-Volatile memory controller                                                 | 2         | 2.35%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 2         | 2.35%   |
| Intel Tiger Lake-LP SATA Controller                                                    | 2         | 2.35%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 2         | 2.35%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 2         | 2.35%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                                 | 2         | 2.35%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 2         | 2.35%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 2         | 2.35%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 2         | 2.35%   |
| VIA VT6421 IDE/SATA Controller                                                         | 1         | 1.18%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                                 | 1         | 1.18%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                   | 1         | 1.18%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                            | 1         | 1.18%   |
| SK hynix Non-Volatile memory controller                                                | 1         | 1.18%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                        | 1         | 1.18%   |
| SanDisk PC SN520 NVMe SSD                                                              | 1         | 1.18%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 1         | 1.18%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 1         | 1.18%   |
| Samsung NVMe SSD Controller 980                                                        | 1         | 1.18%   |
| Lite-On Non-Volatile memory controller                                                 | 1         | 1.18%   |
| KIOXIA NVMe SSD Controller BG4                                                         | 1         | 1.18%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 1         | 1.18%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                | 1         | 1.18%   |
| Intel Non-Volatile memory controller                                                   | 1         | 1.18%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 1         | 1.18%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 1         | 1.18%   |
| Intel 82801FBM (ICH6M) SATA Controller                                                 | 1         | 1.18%   |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode]          | 1         | 1.18%   |
| Intel 8 Series Chipset Family 4-port SATA Controller 1 [IDE mode] - Mobile             | 1         | 1.18%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 1.18%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 50        | 61.73%  |
| NVMe | 17        | 20.99%  |
| IDE  | 9         | 11.11%  |
| RAID | 5         | 6.17%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 60        | 81.08%  |
| AMD    | 13        | 17.57%  |
| ARM    | 1         | 1.35%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-5300U CPU @ 2.30GHz           | 3         | 4.05%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 3         | 4.05%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 2         | 2.7%    |
| Intel Core i5-6300U CPU @ 2.40GHz           | 2         | 2.7%    |
| Intel Core i3 CPU M 330 @ 2.13GHz           | 2         | 2.7%    |
| AMD Ryzen 5 4600H with Radeon Graphics      | 2         | 2.7%    |
| Intel Pentium M processor 1700MHz           | 1         | 1.35%   |
| Intel Pentium M processor 1.60GHz           | 1         | 1.35%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 1.35%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz      | 1         | 1.35%   |
| Intel Pentium CPU P6100 @ 2.00GHz           | 1         | 1.35%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 1         | 1.35%   |
| Intel Core i9-8950HK CPU @ 2.90GHz          | 1         | 1.35%   |
| Intel Core i7-9850H CPU @ 2.60GHz           | 1         | 1.35%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 1.35%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 1.35%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 1         | 1.35%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 1.35%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz          | 1         | 1.35%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 1         | 1.35%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz          | 1         | 1.35%   |
| Intel Core i7-4610M CPU @ 3.00GHz           | 1         | 1.35%   |
| Intel Core i7-4500U CPU @ 1.80GHz           | 1         | 1.35%   |
| Intel Core i7-3610QM CPU @ 2.30GHz          | 1         | 1.35%   |
| Intel Core i7-3540M CPU @ 3.00GHz           | 1         | 1.35%   |
| Intel Core i7-3520M CPU @ 2.90GHz           | 1         | 1.35%   |
| Intel Core i7-2640M CPU @ 2.80GHz           | 1         | 1.35%   |
| Intel Core i5-9300H CPU @ 2.40GHz           | 1         | 1.35%   |
| Intel Core i5-4310U CPU @ 2.00GHz           | 1         | 1.35%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 1         | 1.35%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 1         | 1.35%   |
| Intel Core i5-10310U CPU @ 1.70GHz          | 1         | 1.35%   |
| Intel Core i3-7100U CPU @ 2.40GHz           | 1         | 1.35%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 1         | 1.35%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 1         | 1.35%   |
| Intel Core i3-4010U CPU @ 1.70GHz           | 1         | 1.35%   |
| Intel Core i3-3120M CPU @ 2.50GHz           | 1         | 1.35%   |
| Intel Core i3-2350M CPU @ 2.30GHz           | 1         | 1.35%   |
| Intel Core i3 CPU M 380 @ 2.53GHz           | 1         | 1.35%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 1         | 1.35%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 16        | 21.62%  |
| Intel Core i5           | 13        | 17.57%  |
| Intel Core i3           | 10        | 13.51%  |
| Intel Celeron           | 6         | 8.11%   |
| Other                   | 5         | 6.76%   |
| Intel Core 2            | 3         | 4.05%   |
| AMD Ryzen 7             | 3         | 4.05%   |
| AMD Ryzen 5             | 3         | 4.05%   |
| Intel Pentium M         | 2         | 2.7%    |
| Intel Pentium           | 2         | 2.7%    |
| Intel Pentium Dual-Core | 1         | 1.35%   |
| Intel Pentium Dual      | 1         | 1.35%   |
| Intel Core i9           | 1         | 1.35%   |
| Intel Celeron M         | 1         | 1.35%   |
| Intel Atom              | 1         | 1.35%   |
| AMD E2                  | 1         | 1.35%   |
| AMD E                   | 1         | 1.35%   |
| AMD Athlon II           | 1         | 1.35%   |
| AMD A8                  | 1         | 1.35%   |
| AMD A6                  | 1         | 1.35%   |
| AMD A10                 | 1         | 1.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 44        | 59.46%  |
| 4      | 18        | 24.32%  |
| 6      | 5         | 6.76%   |
| 1      | 5         | 6.76%   |
| 12     | 1         | 1.35%   |
| 8      | 1         | 1.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 74        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 48        | 64.86%  |
| 1      | 26        | 35.14%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 69        | 93.24%  |
| 32-bit         | 3         | 4.05%   |
| Unknown        | 2         | 2.7%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 20        | 26.32%  |
| 0x306c3    | 5         | 6.58%   |
| 0x406e3    | 4         | 5.26%   |
| 0x306a9    | 4         | 5.26%   |
| 0x306d4    | 3         | 3.95%   |
| 0x206a7    | 3         | 3.95%   |
| 0x906ea    | 2         | 2.63%   |
| 0x806ec    | 2         | 2.63%   |
| 0x706a1    | 2         | 2.63%   |
| 0x6f6      | 2         | 2.63%   |
| 0x406c4    | 2         | 2.63%   |
| 0x40651    | 2         | 2.63%   |
| 0x30678    | 2         | 2.63%   |
| 0x20655    | 2         | 2.63%   |
| 0x1067a    | 2         | 2.63%   |
| 0x08608103 | 2         | 2.63%   |
| 0x906ed    | 1         | 1.32%   |
| 0x906a3    | 1         | 1.32%   |
| 0x806ea    | 1         | 1.32%   |
| 0x806c1    | 1         | 1.32%   |
| 0x706a8    | 1         | 1.32%   |
| 0x6d8      | 1         | 1.32%   |
| 0x695      | 1         | 1.32%   |
| 0x20652    | 1         | 1.32%   |
| 0x08600106 | 1         | 1.32%   |
| 0x08600102 | 1         | 1.32%   |
| 0x08108109 | 1         | 1.32%   |
| 0x0810100b | 1         | 1.32%   |
| 0x07030105 | 1         | 1.32%   |
| 0x0600611a | 1         | 1.32%   |
| 0x05000119 | 1         | 1.32%   |
| 0x05000101 | 1         | 1.32%   |
| 0x010000b6 | 1         | 1.32%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 9         | 12%     |
| Haswell          | 8         | 10.67%  |
| IvyBridge        | 7         | 9.33%   |
| Westmere         | 5         | 6.67%   |
| Skylake          | 5         | 6.67%   |
| Silvermont       | 5         | 6.67%   |
| Broadwell        | 4         | 5.33%   |
| Unknown          | 4         | 5.33%   |
| SandyBridge      | 3         | 4%      |
| P6               | 3         | 4%      |
| Goldmont plus    | 3         | 4%      |
| Core             | 3         | 4%      |
| Zen 2            | 2         | 2.67%   |
| TigerLake        | 2         | 2.67%   |
| Penryn           | 2         | 2.67%   |
| Excavator        | 2         | 2.67%   |
| Bobcat           | 2         | 2.67%   |
| Zen+             | 1         | 1.33%   |
| Zen              | 1         | 1.33%   |
| Puma             | 1         | 1.33%   |
| Piledriver       | 1         | 1.33%   |
| K10              | 1         | 1.33%   |
| Alderlake Hybrid | 1         | 1.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 56        | 65.88%  |
| AMD    | 19        | 22.35%  |
| Nvidia | 10        | 11.76%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 7         | 7.78%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 5.56%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 5.56%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 4.44%   |
| Intel HD Graphics 5500                                                                   | 4         | 4.44%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 3.33%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 3.33%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 3.33%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 3.33%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3         | 3.33%   |
| Intel UHD Graphics 620                                                                   | 2         | 2.22%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 2.22%   |
| Intel HD Graphics 620                                                                    | 2         | 2.22%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 2.22%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 2.22%   |
| AMD Renoir                                                                               | 2         | 2.22%   |
| AMD Lucienne                                                                             | 2         | 2.22%   |
| Nvidia GP107M [GeForce MX150]                                                            | 1         | 1.11%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 1.11%   |
| Nvidia GM108M [GeForce 930M]                                                             | 1         | 1.11%   |
| Nvidia GM107M [GeForce GTX 860M]                                                         | 1         | 1.11%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 1.11%   |
| Nvidia GK106M [GeForce GTX 765M]                                                         | 1         | 1.11%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 1.11%   |
| Nvidia GF108M [NVS 5400M]                                                                | 1         | 1.11%   |
| Nvidia GF108M [GeForce GT 635M]                                                          | 1         | 1.11%   |
| Nvidia GF108GLM [NVS 5200M]                                                              | 1         | 1.11%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 1.11%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 1.11%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 1.11%   |
| Intel HD Graphics 520                                                                    | 1         | 1.11%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 1.11%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 1         | 1.11%   |
| Intel 82852/855GM Integrated Graphics Device                                             | 1         | 1.11%   |
| AMD Wrestler [Radeon HD 7340]                                                            | 1         | 1.11%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 1         | 1.11%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 1.11%   |
| AMD Trinity 2 [Radeon HD 7520G]                                                          | 1         | 1.11%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 1         | 1.11%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 1         | 1.11%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 41        | 55.41%  |
| 1 x AMD        | 13        | 17.57%  |
| Intel + Nvidia | 10        | 13.51%  |
| 2 x AMD        | 4         | 5.41%   |
| Other          | 3         | 4.05%   |
| Intel + AMD    | 2         | 2.7%    |
| 2 x Intel      | 1         | 1.35%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 68        | 91.89%  |
| Proprietary | 4         | 5.41%   |
| Unknown     | 2         | 2.7%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 55        | 73.33%  |
| 0.01-0.5   | 9         | 12%     |
| 0.51-1.0   | 5         | 6.67%   |
| 1.01-2.0   | 4         | 5.33%   |
| 5.01-6.0   | 1         | 1.33%   |
| 3.01-4.0   | 1         | 1.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 17        | 20.24%  |
| AU Optronics            | 17        | 20.24%  |
| Chimei Innolux          | 11        | 13.1%   |
| Samsung Electronics     | 7         | 8.33%   |
| BOE                     | 7         | 8.33%   |
| PANDA                   | 4         | 4.76%   |
| Dell                    | 3         | 3.57%   |
| MStar                   | 2         | 2.38%   |
| Lenovo                  | 2         | 2.38%   |
| Goldstar                | 2         | 2.38%   |
| Chi Mei Optoelectronics | 2         | 2.38%   |
| Acer                    | 2         | 2.38%   |
| Unknown                 | 1         | 1.19%   |
| STD                     | 1         | 1.19%   |
| Sharp                   | 1         | 1.19%   |
| InnoLux Display         | 1         | 1.19%   |
| InfoVision              | 1         | 1.19%   |
| Iiyama                  | 1         | 1.19%   |
| Hisense                 | 1         | 1.19%   |
| AOC                     | 1         | 1.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics S24D340 SAM0BBB 1920x1080 531x299mm 24.0-inch     | 2         | 2.38%   |
| MStar TV MST0030 1920x1080 708x398mm 32.0-inch                        | 2         | 2.38%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 2         | 2.38%   |
| Dell P2717H DEL40F7 1920x1080 598x336mm 27.0-inch                     | 2         | 2.38%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 2         | 2.38%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 1         | 1.19%   |
| STD HDMI TV STD00C7 1920x1080 698x392mm 31.5-inch                     | 1         | 1.19%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch               | 1         | 1.19%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch  | 1         | 1.19%   |
| Samsung Electronics LCD Monitor SEC4545 1280x800 331x207mm 15.4-inch  | 1         | 1.19%   |
| Samsung Electronics LCD Monitor SEC4151 1366x768 344x194mm 15.5-inch  | 1         | 1.19%   |
| Samsung Electronics LCD Monitor SDC4852 1920x1080 344x194mm 15.5-inch | 1         | 1.19%   |
| Samsung Electronics LCD Monitor SDC4851 1366x768 344x194mm 15.5-inch  | 1         | 1.19%   |
| PANDA LM133LF5L01 NCP0020 1920x1080 294x165mm 13.3-inch               | 1         | 1.19%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch               | 1         | 1.19%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch               | 1         | 1.19%   |
| PANDA LCD Monitor NCP002E 1920x1080 344x194mm 15.5-inch               | 1         | 1.19%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch         | 1         | 1.19%   |
| LG Display LCD Monitor LGDD901 1366x768 344x194mm 15.5-inch           | 1         | 1.19%   |
| LG Display LCD Monitor LGD0542 1920x1080 276x156mm 12.5-inch          | 1         | 1.19%   |
| LG Display LCD Monitor LGD0540 1920x1080 344x194mm 15.5-inch          | 1         | 1.19%   |
| LG Display LCD Monitor LGD04D5 1920x1080 344x194mm 15.5-inch          | 1         | 1.19%   |
| LG Display LCD Monitor LGD047B 1366x768 344x194mm 15.5-inch           | 1         | 1.19%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 1         | 1.19%   |
| LG Display LCD Monitor LGD0450 1366x768 277x156mm 12.5-inch           | 1         | 1.19%   |
| LG Display LCD Monitor LGD03D3 1600x900 309x174mm 14.0-inch           | 1         | 1.19%   |
| LG Display LCD Monitor LGD03A3 1366x768 277x156mm 12.5-inch           | 1         | 1.19%   |
| LG Display LCD Monitor LGD0386 1366x768 309x174mm 14.0-inch           | 1         | 1.19%   |
| LG Display LCD Monitor LGD036C 1366x768 277x156mm 12.5-inch           | 1         | 1.19%   |
| LG Display LCD Monitor LGD033E 1366x768 309x174mm 14.0-inch           | 1         | 1.19%   |
| LG Display LCD Monitor LGD02C0 1366x768 293x165mm 13.2-inch           | 1         | 1.19%   |
| LG Display LCD Monitor LGD018B 1366x768 310x174mm 14.0-inch           | 1         | 1.19%   |
| Lenovo LCD Monitor LEN4010 1280x800 261x163mm 12.1-inch               | 1         | 1.19%   |
| Lenovo LCD Monitor LEN4000 1024x768 246x184mm 12.1-inch               | 1         | 1.19%   |
| InnoLux Display LCD Monitor INL000A 1366x768 344x194mm 15.5-inch      | 1         | 1.19%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 1         | 1.19%   |
| Iiyama PL2730H IVM663A 1920x1080 598x336mm 27.0-inch                  | 1         | 1.19%   |
| Hisense Hisense HSE4000 1920x1080 591x355mm 27.1-inch                 | 1         | 1.19%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 1         | 1.19%   |
| Goldstar E2260 GSM57E0 1920x1080 477x268mm 21.5-inch                  | 1         | 1.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 34        | 41.46%  |
| 1920x1080 (FHD)   | 31        | 37.8%   |
| 3840x2160 (4K)    | 5         | 6.1%    |
| 1600x900 (HD+)    | 5         | 6.1%    |
| 1280x800 (WXGA)   | 2         | 2.44%   |
| 2560x1440 (QHD)   | 1         | 1.22%   |
| 2288x1287         | 1         | 1.22%   |
| 2160x1440         | 1         | 1.22%   |
| 1920x1200 (WUXGA) | 1         | 1.22%   |
| 1440x900 (WXGA+)  | 1         | 1.22%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 30        | 35.71%  |
| 14     | 11        | 13.1%   |
| 13     | 9         | 10.71%  |
| 12     | 9         | 10.71%  |
| 27     | 4         | 4.76%   |
| 24     | 4         | 4.76%   |
| 17     | 4         | 4.76%   |
| 11     | 4         | 4.76%   |
| 52     | 2         | 2.38%   |
| 23     | 2         | 2.38%   |
| 21     | 2         | 2.38%   |
| 142    | 1         | 1.19%   |
| 31     | 1         | 1.19%   |
| 20     | 1         | 1.19%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 45        | 53.57%  |
| 201-300        | 18        | 21.43%  |
| 501-600        | 10        | 11.9%   |
| 351-400        | 4         | 4.76%   |
| 401-500        | 3         | 3.57%   |
| 1001-1500      | 2         | 2.38%   |
| More than 2000 | 1         | 1.19%   |
| 601-700        | 1         | 1.19%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 65        | 91.55%  |
| 16/10 | 4         | 5.63%   |
| 3/2   | 1         | 1.41%   |
| 1.00  | 1         | 1.41%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 30        | 35.71%  |
| 81-90          | 15        | 17.86%  |
| 61-70          | 9         | 10.71%  |
| 201-250        | 8         | 9.52%   |
| 71-80          | 5         | 5.95%   |
| 51-60          | 4         | 4.76%   |
| 301-350        | 4         | 4.76%   |
| More than 1000 | 3         | 3.57%   |
| 121-130        | 3         | 3.57%   |
| 351-500        | 1         | 1.19%   |
| 151-200        | 1         | 1.19%   |
| 131-140        | 1         | 1.19%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 34        | 40.96%  |
| 101-120 | 25        | 30.12%  |
| 51-100  | 14        | 16.87%  |
| 161-240 | 7         | 8.43%   |
| 1-50    | 3         | 3.61%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 61        | 79.22%  |
| 2     | 13        | 16.88%  |
| 3     | 2         | 2.6%    |
| 0     | 1         | 1.3%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 38        | 32.48%  |
| Realtek Semiconductor      | 33        | 28.21%  |
| Qualcomm Atheros           | 23        | 19.66%  |
| Broadcom                   | 5         | 4.27%   |
| Samsung Electronics        | 2         | 1.71%   |
| Ralink Technology          | 2         | 1.71%   |
| MediaTek                   | 2         | 1.71%   |
| ZTE WCDMA Technologies MSM | 1         | 0.85%   |
| VIA Technologies           | 1         | 0.85%   |
| TP-Link                    | 1         | 0.85%   |
| Sierra Wireless            | 1         | 0.85%   |
| Ralink                     | 1         | 0.85%   |
| NetGear                    | 1         | 0.85%   |
| JMicron Technology         | 1         | 0.85%   |
| Huawei Technologies        | 1         | 0.85%   |
| DisplayLink                | 1         | 0.85%   |
| Dell                       | 1         | 0.85%   |
| Broadcom Limited           | 1         | 0.85%   |
| ASIX Electronics           | 1         | 0.85%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 19        | 12.84%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 8         | 5.41%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 7         | 4.73%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 3.38%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 2.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 2.7%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 2.7%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 2.7%    |
| Intel Wireless 7265                                                     | 4         | 2.7%    |
| Intel Wireless 7260                                                     | 4         | 2.7%    |
| Intel Wireless 8260                                                     | 3         | 2.03%   |
| Intel Wi-Fi 6 AX200                                                     | 3         | 2.03%   |
| Intel Ethernet Connection (3) I218-LM                                   | 3         | 2.03%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 2         | 1.35%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.35%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2         | 1.35%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 1.35%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 2         | 1.35%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.35%   |
| Intel Wireless 8265 / 8275                                              | 2         | 1.35%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 2         | 1.35%   |
| Intel Ethernet Connection I217-LM                                       | 2         | 1.35%   |
| Intel Ethernet Connection (7) I219-LM                                   | 2         | 1.35%   |
| Intel Ethernet Connection (4) I219-LM                                   | 2         | 1.35%   |
| Intel Centrino Advanced-N 6235                                          | 2         | 1.35%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller       | 2         | 1.35%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 1.35%   |
| ZTE WCDMA MSM DEMO Mobile Boardband                                     | 1         | 0.68%   |
| VIA VT6105/VT6106S [Rhine-III]                                          | 1         | 0.68%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]         | 1         | 0.68%   |
| Sierra Wireless EM7455                                                  | 1         | 0.68%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.68%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.68%   |
| Realtek RTL8187SE Wireless LAN Controller                               | 1         | 0.68%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                         | 1         | 0.68%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 1         | 0.68%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 1         | 0.68%   |
| Realtek 802.11ac NIC                                                    | 1         | 0.68%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 0.68%   |
| Ralink MT7601U Wireless Adapter                                         | 1         | 0.68%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 30        | 40.54%  |
| Qualcomm Atheros      | 21        | 28.38%  |
| Realtek Semiconductor | 10        | 13.51%  |
| Broadcom              | 4         | 5.41%   |
| Ralink Technology     | 2         | 2.7%    |
| MediaTek              | 2         | 2.7%    |
| Sierra Wireless       | 1         | 1.35%   |
| Ralink                | 1         | 1.35%   |
| NetGear               | 1         | 1.35%   |
| Dell                  | 1         | 1.35%   |
| Broadcom Limited      | 1         | 1.35%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 6.76%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 5.41%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 5.41%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 5.41%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 5.41%   |
| Intel Wireless 7265                                                     | 4         | 5.41%   |
| Intel Wireless 7260                                                     | 4         | 5.41%   |
| Intel Wireless 8260                                                     | 3         | 4.05%   |
| Intel Wi-Fi 6 AX200                                                     | 3         | 4.05%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 2.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2         | 2.7%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 2.7%    |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 2         | 2.7%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 2.7%    |
| Intel Wireless 8265 / 8275                                              | 2         | 2.7%    |
| Intel Gemini Lake PCH CNVi WiFi                                         | 2         | 2.7%    |
| Intel Centrino Advanced-N 6235                                          | 2         | 2.7%    |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 2.7%    |
| Sierra Wireless EM7455                                                  | 1         | 1.35%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.35%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 1.35%   |
| Realtek RTL8187SE Wireless LAN Controller                               | 1         | 1.35%   |
| Realtek 802.11ac NIC                                                    | 1         | 1.35%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 1.35%   |
| Ralink MT7601U Wireless Adapter                                         | 1         | 1.35%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 1.35%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 1.35%   |
| NetGear WG111v3 54 Mbps Wireless [realtek RTL8187B]                     | 1         | 1.35%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 1         | 1.35%   |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter                     | 1         | 1.35%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 1.35%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 1         | 1.35%   |
| Intel Centrino Advanced-N 6200                                          | 1         | 1.35%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 1.35%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 1         | 1.35%   |
| Dell Hub of E-Port Replicator                                           | 1         | 1.35%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 1         | 1.35%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                      | 1         | 1.35%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 1         | 1.35%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 29        | 40.85%  |
| Intel                      | 28        | 39.44%  |
| Qualcomm Atheros           | 4         | 5.63%   |
| Samsung Electronics        | 2         | 2.82%   |
| ZTE WCDMA Technologies MSM | 1         | 1.41%   |
| VIA Technologies           | 1         | 1.41%   |
| TP-Link                    | 1         | 1.41%   |
| JMicron Technology         | 1         | 1.41%   |
| Huawei Technologies        | 1         | 1.41%   |
| DisplayLink                | 1         | 1.41%   |
| Broadcom                   | 1         | 1.41%   |
| ASIX Electronics           | 1         | 1.41%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 19        | 26.76%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 11.27%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 9.86%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 4.23%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 2.82%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 2.82%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 2.82%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 2.82%   |
| ZTE WCDMA MSM DEMO Mobile Boardband                               | 1         | 1.41%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1         | 1.41%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 1.41%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 1.41%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.41%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.41%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.41%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.41%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 1.41%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.41%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 1.41%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.41%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.41%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.41%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.41%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.41%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.41%   |
| Intel Ethernet Connection (16) I219-V                             | 1         | 1.41%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 1.41%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 1.41%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.41%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                | 1         | 1.41%   |
| Huawei E353/E3131                                                 | 1         | 1.41%   |
| DisplayLink StarTech USB3DOCKHDPC                                 | 1         | 1.41%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.41%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 1.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 71        | 51.08%  |
| Ethernet | 65        | 46.76%  |
| Modem    | 3         | 2.16%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 52        | 66.67%  |
| Ethernet | 26        | 33.33%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 59        | 79.73%  |
| 1     | 13        | 17.57%  |
| 0     | 2         | 2.7%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 64        | 86.49%  |
| Yes  | 10        | 13.51%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 20        | 40%     |
| Realtek Semiconductor           | 6         | 12%     |
| Qualcomm Atheros Communications | 5         | 10%     |
| Broadcom                        | 4         | 8%      |
| Lite-On Technology              | 3         | 6%      |
| IMC Networks                    | 2         | 4%      |
| Foxconn International           | 2         | 4%      |
| Foxconn / Hon Hai               | 2         | 4%      |
| Dell                            | 2         | 4%      |
| Cambridge Silicon Radio         | 2         | 4%      |
| Realtek                         | 1         | 2%      |
| Ralink                          | 1         | 2%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 11        | 22%     |
| Realtek Bluetooth Radio                             | 6         | 12%     |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 8%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 6%      |
| Intel AX200 Bluetooth                               | 3         | 6%      |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 4%      |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 4%      |
| Foxconn International BCM43142A0 Bluetooth module   | 2         | 4%      |
| Dell BCM20702A0 Bluetooth Module                    | 2         | 4%      |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 4%      |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 4%      |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 4%      |
| Realtek Bluetooth Radio                             | 1         | 2%      |
| Ralink RT3290 Bluetooth                             | 1         | 2%      |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 2%      |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 2%      |
| Intel Bluetooth Device                              | 1         | 2%      |
| IMC Networks BCM20702A0                             | 1         | 2%      |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 2%      |
| Foxconn / Hon Hai BT                                | 1         | 2%      |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 2%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 59        | 68.6%   |
| AMD                   | 15        | 17.44%  |
| Nvidia                | 5         | 5.81%   |
| C-Media Electronics   | 4         | 4.65%   |
| Realtek Semiconductor | 1         | 1.16%   |
| GYROCOM C&C           | 1         | 1.16%   |
| Blue Microphones      | 1         | 1.16%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 9         | 8.11%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 7         | 6.31%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 6         | 5.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 4.5%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 4.5%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 4.5%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 3.6%    |
| Intel Broadwell-U Audio Controller                                                                | 4         | 3.6%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 2.7%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 2.7%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 2.7%    |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 2.7%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 2.7%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 2.7%    |
| Intel 8 Series HD Audio Controller                                                                | 3         | 2.7%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 3         | 2.7%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 2.7%    |
| AMD FCH Azalia Controller                                                                         | 3         | 2.7%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 1.8%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 1.8%    |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 2         | 1.8%    |
| C-Media Electronics CM106 Like Sound Device                                                       | 2         | 1.8%    |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 2         | 1.8%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 1.8%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 1.8%    |
| AMD Navi 10 HDMI Audio                                                                            | 2         | 1.8%    |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 1.8%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 1.8%    |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.9%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.9%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.9%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 0.9%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 0.9%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.9%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 1         | 0.9%    |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 1         | 0.9%    |
| GYROCOM C&C Fiio E10                                                                              | 1         | 0.9%    |
| Blue Microphones Yeti Stereo Microphone                                                           | 1         | 0.9%    |
| AMD Wrestler HDMI Audio                                                                           | 1         | 0.9%    |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 0.9%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 23        | 32.86%  |
| SK hynix            | 12        | 17.14%  |
| Unknown             | 7         | 10%     |
| Kingston            | 6         | 8.57%   |
| A-DATA Technology   | 5         | 7.14%   |
| Crucial             | 4         | 5.71%   |
| Micron Technology   | 3         | 4.29%   |
| G.Skill             | 2         | 2.86%   |
| Unknown (ABCD)      | 1         | 1.43%   |
| Smart               | 1         | 1.43%   |
| Ramaxel Technology  | 1         | 1.43%   |
| Nanya Technology    | 1         | 1.43%   |
| Corsair             | 1         | 1.43%   |
| Apacer              | 1         | 1.43%   |
| 4ea5                | 1         | 1.43%   |
| Unknown             | 1         | 1.43%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 3.66%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 2         | 2.44%   |
| Unknown RAM Module 1024MB SODIMM DDR                             | 2         | 2.44%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 2.44%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 2         | 2.44%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 2.44%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 2         | 2.44%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 1.22%   |
| Unknown RAM Module 512MB SODIMM DDR                              | 1         | 1.22%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 1.22%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                         | 1         | 1.22%   |
| Unknown RAM Module 1024MB SODIMM DDR2                            | 1         | 1.22%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 1.22%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 1         | 1.22%   |
| Smart RAM SF564128CJ8NWMNSEG 4GB SODIMM DDR3 1600MT/s            | 1         | 1.22%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1066MT/s                     | 1         | 1.22%   |
| SK hynix RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s          | 1         | 1.22%   |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 1.22%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.22%   |
| SK hynix RAM HMT41GS6DFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.22%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.22%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.22%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.22%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s        | 1         | 1.22%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 1.22%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 1         | 1.22%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.22%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 1.22%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 1         | 1.22%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 1         | 1.22%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s            | 1         | 1.22%   |
| Samsung RAM M471B5273EB0-CK0 4096MB SODIMM DDR3 4199MT/s         | 1         | 1.22%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.22%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.22%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.22%   |
| Samsung RAM M471B5173CB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.22%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.22%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 1         | 1.22%   |
| Samsung RAM M471A2K43BB1-CRC 16GB SODIMM DDR4 2400MT/s           | 1         | 1.22%   |
| Samsung RAM M471A2G44BM0-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.22%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 29        | 47.54%  |
| DDR4    | 21        | 34.43%  |
| SDRAM   | 2         | 3.28%   |
| LPDDR4  | 2         | 3.28%   |
| LPDDR3  | 2         | 3.28%   |
| DDR2    | 2         | 3.28%   |
| DDR     | 2         | 3.28%   |
| Unknown | 1         | 1.64%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 57        | 93.44%  |
| Row Of Chips | 2         | 3.28%   |
| Chip         | 1         | 1.64%   |
| Unknown      | 1         | 1.64%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 28        | 39.44%  |
| 4096  | 19        | 26.76%  |
| 2048  | 11        | 15.49%  |
| 16384 | 8         | 11.27%  |
| 1024  | 3         | 4.23%   |
| 32768 | 1         | 1.41%   |
| 512   | 1         | 1.41%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 21        | 31.34%  |
| 2667    | 12        | 17.91%  |
| 3200    | 7         | 10.45%  |
| 2400    | 5         | 7.46%   |
| Unknown | 5         | 7.46%   |
| 1333    | 4         | 5.97%   |
| 1067    | 3         | 4.48%   |
| 4199    | 2         | 2.99%   |
| 3266    | 2         | 2.99%   |
| 2133    | 2         | 2.99%   |
| 1334    | 1         | 1.49%   |
| 1200    | 1         | 1.49%   |
| 1066    | 1         | 1.49%   |
| 800     | 1         | 1.49%   |

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
| Chicony Electronics                    | 24        | 40.68%  |
| Microdia                               | 7         | 11.86%  |
| Sunplus Innovation Technology          | 5         | 8.47%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 6.78%   |
| Realtek Semiconductor                  | 3         | 5.08%   |
| IMC Networks                           | 3         | 5.08%   |
| Bison Electronics                      | 3         | 5.08%   |
| Acer                                   | 3         | 5.08%   |
| Suyin                                  | 2         | 3.39%   |
| Samsung Electronics                    | 1         | 1.69%   |
| Quanta                                 | 1         | 1.69%   |
| Mustek Systems                         | 1         | 1.69%   |
| Logitech                               | 1         | 1.69%   |
| Lite-On Technology                     | 1         | 1.69%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 7         | 11.86%  |
| Chicony HD WebCam                        | 3         | 5.08%   |
| Chicony HP TrueVision HD Camera          | 2         | 3.39%   |
| Chicony EasyCamera                       | 2         | 3.39%   |
| Acer BisonCam, NB Pro                    | 2         | 3.39%   |
| Suyin Acer/Lenovo Webcam [CN0316]        | 1         | 1.69%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 1         | 1.69%   |
| Sunplus Laptop Integrated Webcam HD      | 1         | 1.69%   |
| Sunplus Integrated_Webcam_HD             | 1         | 1.69%   |
| Sunplus FHD Camera Microphone            | 1         | 1.69%   |
| Sunplus Asus Webcam                      | 1         | 1.69%   |
| Sunplus 720p HD Camera                   | 1         | 1.69%   |
| Samsung Galaxy series, misc. (MTP mode)  | 1         | 1.69%   |
| Realtek Lenovo EasyCamera                | 1         | 1.69%   |
| Realtek Integrated_Webcam_HD             | 1         | 1.69%   |
| Realtek Integrated Webcam_HD             | 1         | 1.69%   |
| Quanta Sony Visual Communication Camera  | 1         | 1.69%   |
| Mustek Systems USB 2.0 PC Camera         | 1         | 1.69%   |
| Microdia Webcam Vitade AF                | 1         | 1.69%   |
| Microdia WebCam SC-13HDL12639P           | 1         | 1.69%   |
| Microdia Sonix USB 2.0 Camera            | 1         | 1.69%   |
| Microdia Integrated_Webcam_HD            | 1         | 1.69%   |
| Microdia Integrated Webcam               | 1         | 1.69%   |
| Microdia Dell Integrated HD Webcam       | 1         | 1.69%   |
| Microdia 1.3 MPixel Integrated Webcam    | 1         | 1.69%   |
| Logitech HD Pro Webcam C920              | 1         | 1.69%   |
| Lite-On HP HD Webcam                     | 1         | 1.69%   |
| IMC Networks Lenovo EasyCamera           | 1         | 1.69%   |
| IMC Networks Integrated Webcam           | 1         | 1.69%   |
| IMC Networks Integrated Camera           | 1         | 1.69%   |
| Chicony WebCam                           | 1         | 1.69%   |
| Chicony VGA WebCam                       | 1         | 1.69%   |
| Chicony USB2.0 HD UVC WebCam             | 1         | 1.69%   |
| Chicony TOSHIBA Web Camera - FHD         | 1         | 1.69%   |
| Chicony Thinkpad T430 camera             | 1         | 1.69%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 1         | 1.69%   |
| Chicony Lenovo EasyCamera                | 1         | 1.69%   |
| Chicony HP TrueVision HD                 | 1         | 1.69%   |
| Chicony HD WebCam (Acer)                 | 1         | 1.69%   |
| Chicony CNF9055 Toshiba Webcam           | 1         | 1.69%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 1         | 20%     |
| Upek                       | 1         | 20%     |
| Synaptics                  | 1         | 20%     |
| STMicroelectronics         | 1         | 20%     |
| Shenzhen Goodix Technology | 1         | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI                        | 1         | 20%     |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 20%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 20%     |
| STMicroelectronics Fingerprint Reader                  | 1         | 20%     |
| Shenzhen Goodix Fingerprint Reader                     | 1         | 20%     |

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
| 0     | 52        | 67.53%  |
| 1     | 17        | 22.08%  |
| 2     | 5         | 6.49%   |
| 3     | 2         | 2.6%    |
| 5     | 1         | 1.3%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Chipcard                 | 9         | 32.14%  |
| Fingerprint reader       | 5         | 17.86%  |
| Net/wireless             | 4         | 14.29%  |
| Graphics card            | 3         | 10.71%  |
| Camera                   | 3         | 10.71%  |
| Communication controller | 2         | 7.14%   |
| Bluetooth                | 2         | 7.14%   |

