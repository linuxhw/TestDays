Devuan - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for Devuan.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Devuan/Desktop/README.md) and [notebooks](/Dist/Devuan/Notebook/README.md).

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

Total: 106

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Chuwi         | Hi10 X                      | Tablet      | [1aa66a62c4](https://linux-hardware.org/?probe=1aa66a62c4) | Mar 26, 2022 |
| Dell          | Latitude E5540              | Notebook    | [0948114af7](https://linux-hardware.org/?probe=0948114af7) | Mar 03, 2022 |
| HP            | 1825                        | Desktop     | [a7ce5b6b11](https://linux-hardware.org/?probe=a7ce5b6b11) | Mar 03, 2022 |
| Lenovo        | ThinkPad T550 20CJS1VD01    | Notebook    | [a3aed9d375](https://linux-hardware.org/?probe=a3aed9d375) | Mar 03, 2022 |
| Lenovo        | ThinkPad X1 Tablet Gen 3... | Tablet      | [f92ae76fed](https://linux-hardware.org/?probe=f92ae76fed) | Feb 24, 2022 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [3f99c8072a](https://linux-hardware.org/?probe=3f99c8072a) | Feb 23, 2022 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [7ab68e0043](https://linux-hardware.org/?probe=7ab68e0043) | Feb 17, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [f2a65b8a5f](https://linux-hardware.org/?probe=f2a65b8a5f) | Feb 14, 2022 |
| Gigabyte      | P55A-UD3                    | Desktop     | [824dbdd8ad](https://linux-hardware.org/?probe=824dbdd8ad) | Jan 22, 2022 |
| Online Lab... | SR 42                       | Desktop     | [e3037eb087](https://linux-hardware.org/?probe=e3037eb087) | Jan 22, 2022 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [9e14e04f7f](https://linux-hardware.org/?probe=9e14e04f7f) | Jan 22, 2022 |
| ASUSTek       | K55VJ                       | Notebook    | [562262b9eb](https://linux-hardware.org/?probe=562262b9eb) | Jan 22, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [8e7267692b](https://linux-hardware.org/?probe=8e7267692b) | Jan 21, 2022 |
| ASUSTek       | X555LJ                      | Notebook    | [9fbdf4dfc2](https://linux-hardware.org/?probe=9fbdf4dfc2) | Jan 17, 2022 |
| Lenovo        | ThinkPad T420 4180AG3       | Notebook    | [2c3cd27ad2](https://linux-hardware.org/?probe=2c3cd27ad2) | Jan 16, 2022 |
| Notebook      | W230ST                      | Notebook    | [3dacf0aea8](https://linux-hardware.org/?probe=3dacf0aea8) | Jan 15, 2022 |
| Gigabyte      | MZGLKBP-00                  | Desktop     | [202ccac61c](https://linux-hardware.org/?probe=202ccac61c) | Dec 30, 2021 |
| Gigabyte      | B75M-D3V                    | Desktop     | [1c15b6b3c7](https://linux-hardware.org/?probe=1c15b6b3c7) | Dec 26, 2021 |
| Lenovo        | IdeaPad 130-15AST 81H5      | Notebook    | [899cb98778](https://linux-hardware.org/?probe=899cb98778) | Dec 06, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | Notebook    | [d860ff9858](https://linux-hardware.org/?probe=d860ff9858) | Nov 30, 2021 |
| Fujitsu       | LIFEBOOK U7510              | Notebook    | [d43a6a6bb8](https://linux-hardware.org/?probe=d43a6a6bb8) | Nov 29, 2021 |
| HP            | 1495                        | Desktop     | [28835849f0](https://linux-hardware.org/?probe=28835849f0) | Oct 29, 2021 |
| Lenovo        | ThinkPad T550 20CJS1VD01    | Notebook    | [55689e67b3](https://linux-hardware.org/?probe=55689e67b3) | Oct 27, 2021 |
| Lenovo        | ThinkPad X230 2325DE0       | Notebook    | [991007e92a](https://linux-hardware.org/?probe=991007e92a) | Oct 13, 2021 |
| Lenovo        | IdeaPad 130-15AST 81H5      | Notebook    | [7f1b3371a9](https://linux-hardware.org/?probe=7f1b3371a9) | Oct 03, 2021 |
| ASUSTek       | PRIME Z490M-PLUS            | Desktop     | [5a7e6805d3](https://linux-hardware.org/?probe=5a7e6805d3) | Oct 02, 2021 |
| MSI           | B360M PRO-VD                | Desktop     | [06e625d98f](https://linux-hardware.org/?probe=06e625d98f) | Oct 02, 2021 |
| Toshiba       | Satellite M40X              | Notebook    | [61fea93e97](https://linux-hardware.org/?probe=61fea93e97) | Oct 01, 2021 |
| Acer          | Aspire 5250                 | Notebook    | [ae41600fd9](https://linux-hardware.org/?probe=ae41600fd9) | Sep 24, 2021 |
| IBM           | ThinkPad T41p 2373GHG       | Notebook    | [04747e3df4](https://linux-hardware.org/?probe=04747e3df4) | Sep 19, 2021 |
| IBM           | ThinkPad T41p 2373GHG       | Notebook    | [134b90f474](https://linux-hardware.org/?probe=134b90f474) | Sep 18, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [ffd8fa11af](https://linux-hardware.org/?probe=ffd8fa11af) | Sep 16, 2021 |
| Apple         | Mac-F22C86C8                | Mini pc     | [d65f9a48fd](https://linux-hardware.org/?probe=d65f9a48fd) | Sep 04, 2021 |
| Lenovo        | ThinkPad X200 74585FU       | Notebook    | [04256a6e0a](https://linux-hardware.org/?probe=04256a6e0a) | Aug 25, 2021 |
| Lenovo        | ThinkPad X200 74585FU       | Notebook    | [dffbcc492c](https://linux-hardware.org/?probe=dffbcc492c) | Aug 25, 2021 |
| ASUSTek       | K52F                        | Notebook    | [643e3cc4b3](https://linux-hardware.org/?probe=643e3cc4b3) | Aug 13, 2021 |
| MSI           | MS-1688                     | Notebook    | [0ae772d66b](https://linux-hardware.org/?probe=0ae772d66b) | Jul 30, 2021 |
| Lenovo        | ThinkPad X220 429053G       | Notebook    | [5f553465bf](https://linux-hardware.org/?probe=5f553465bf) | Jul 29, 2021 |
| Acer          | Extensa 215-51K             | Notebook    | [1c49c2f4d0](https://linux-hardware.org/?probe=1c49c2f4d0) | Jul 26, 2021 |
| Lenovo        | ThinkPad X250 20CLS7WY04    | Notebook    | [fc77801294](https://linux-hardware.org/?probe=fc77801294) | Jun 07, 2021 |
| HP            | 1825                        | Desktop     | [ff75be1ea3](https://linux-hardware.org/?probe=ff75be1ea3) | Jun 06, 2021 |
| Lenovo        | ThinkPad T550 20CJS1VD01    | Notebook    | [aef4e323e2](https://linux-hardware.org/?probe=aef4e323e2) | Jun 06, 2021 |
| ASUSTek       | P5G41T-M LX2/BR             | Desktop     | [8702580cb4](https://linux-hardware.org/?probe=8702580cb4) | May 26, 2021 |
| ASUSTek       | P5G41T-M LX2/BR             | Desktop     | [05f1d12390](https://linux-hardware.org/?probe=05f1d12390) | May 26, 2021 |
| Gigabyte      | H170-HD3-CF                 | Desktop     | [2ffdc89c2a](https://linux-hardware.org/?probe=2ffdc89c2a) | Apr 28, 2021 |
| Gigabyte      | Z390 GAMING SLI-CF          | Desktop     | [50f8ddb45c](https://linux-hardware.org/?probe=50f8ddb45c) | Apr 28, 2021 |
| ASUSTek       | K55VJ                       | Notebook    | [6fa86f9d25](https://linux-hardware.org/?probe=6fa86f9d25) | Apr 27, 2021 |
| Google        | Panther                     | Desktop     | [666794d603](https://linux-hardware.org/?probe=666794d603) | Apr 26, 2021 |
| ASUSTek       | K55VJ                       | Notebook    | [aef1b6c71f](https://linux-hardware.org/?probe=aef1b6c71f) | Apr 17, 2021 |
| ASUSTek       | F1A55-M LX                  | Desktop     | [630bbb748a](https://linux-hardware.org/?probe=630bbb748a) | Apr 17, 2021 |
| Gigabyte      | H170-HD3-CF                 | Desktop     | [f103eefd66](https://linux-hardware.org/?probe=f103eefd66) | Apr 17, 2021 |
| Gigabyte      | Z390 GAMING SLI-CF          | Desktop     | [e802fc9ff5](https://linux-hardware.org/?probe=e802fc9ff5) | Apr 17, 2021 |
| HP            | ProBook 6475b               | Notebook    | [74b0fa77b5](https://linux-hardware.org/?probe=74b0fa77b5) | Apr 14, 2021 |
| Sun Micros... | Ultra 24 50                 | Desktop     | [e4b76f9137](https://linux-hardware.org/?probe=e4b76f9137) | Apr 10, 2021 |
| Sun Micros... | Ultra 24 50                 | Desktop     | [15691fbc42](https://linux-hardware.org/?probe=15691fbc42) | Apr 10, 2021 |
| Fujitsu Si... | AMILO Xi 1546               | Notebook    | [22a53eeb74](https://linux-hardware.org/?probe=22a53eeb74) | Apr 03, 2021 |
| Chuwi         | Hi10 pro tablet             | Tablet      | [ee6bb68e8c](https://linux-hardware.org/?probe=ee6bb68e8c) | Mar 29, 2021 |
| ASUSTek       | A8R-MVP                     | Desktop     | [6daa2a372c](https://linux-hardware.org/?probe=6daa2a372c) | Mar 27, 2021 |
| ASRock        | K8A780LM                    | Desktop     | [b8f4c7c2cb](https://linux-hardware.org/?probe=b8f4c7c2cb) | Mar 22, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [eeebc66137](https://linux-hardware.org/?probe=eeebc66137) | Mar 17, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [fdf4e6d366](https://linux-hardware.org/?probe=fdf4e6d366) | Mar 17, 2021 |
| ASRock        | K8A780LM                    | Desktop     | [d95a56d80f](https://linux-hardware.org/?probe=d95a56d80f) | Mar 15, 2021 |
| ASRock        | H81M-ITX                    | Desktop     | [0f5f41e1ca](https://linux-hardware.org/?probe=0f5f41e1ca) | Mar 08, 2021 |
| ASRock        | H81M-ITX                    | Desktop     | [8599b883d6](https://linux-hardware.org/?probe=8599b883d6) | Mar 08, 2021 |
| Intel         | D815EEA AAA45884-401        | Desktop     | [248565d49c](https://linux-hardware.org/?probe=248565d49c) | Feb 20, 2021 |
| Intel         | D815EEA AAA45884-401        | Desktop     | [3acc2f0b1e](https://linux-hardware.org/?probe=3acc2f0b1e) | Feb 20, 2021 |
| Gigabyte      | GA-G41M-ES2L                | Desktop     | [592c995804](https://linux-hardware.org/?probe=592c995804) | Jan 30, 2021 |
| Acer          | F672CR R01-A4               | Desktop     | [8d41694165](https://linux-hardware.org/?probe=8d41694165) | Jan 25, 2021 |
| Teclast       | F6 Plus                     | Notebook    | [26ac25681a](https://linux-hardware.org/?probe=26ac25681a) | Jan 08, 2021 |
| Lenovo        | Board                       | Desktop     | [f963a2e7f9](https://linux-hardware.org/?probe=f963a2e7f9) | Jan 06, 2021 |
| Lenovo        | Board                       | Desktop     | [3ab2cd64a6](https://linux-hardware.org/?probe=3ab2cd64a6) | Jan 04, 2021 |
| Dell          | 0GXM1W A04                  | Desktop     | [989f983b51](https://linux-hardware.org/?probe=989f983b51) | Dec 28, 2020 |
| Lenovo        | Board                       | Desktop     | [aac28ba905](https://linux-hardware.org/?probe=aac28ba905) | Dec 19, 2020 |
| Dell          | Precision 7530              | Notebook    | [8e0ee186a3](https://linux-hardware.org/?probe=8e0ee186a3) | Dec 04, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [b708be8d9e](https://linux-hardware.org/?probe=b708be8d9e) | Nov 10, 2020 |
| Lenovo        | ThinkPad X60 1707YF8        | Notebook    | [bcdd451de1](https://linux-hardware.org/?probe=bcdd451de1) | Oct 31, 2020 |
| Intel         | HURONRIVER                  | Desktop     | [49bdd1a99d](https://linux-hardware.org/?probe=49bdd1a99d) | Oct 29, 2020 |
| ASUSTek       | Maximus V GENE              | Desktop     | [253b5aba98](https://linux-hardware.org/?probe=253b5aba98) | Oct 29, 2020 |
| Nokia         | N900                        | Notebook    | [7960cb48cc](https://linux-hardware.org/?probe=7960cb48cc) | Oct 05, 2020 |
| ASUSTek       | H81M-C                      | Desktop     | [cd136e059e](https://linux-hardware.org/?probe=cd136e059e) | Oct 05, 2020 |
| Lenovo        | ThinkPad X230 23247S0       | Notebook    | [f313b0bf1b](https://linux-hardware.org/?probe=f313b0bf1b) | Oct 01, 2020 |
| Dell          | Precision 7530              | Notebook    | [e6c6dd2734](https://linux-hardware.org/?probe=e6c6dd2734) | Sep 26, 2020 |
| Dell          | Precision 7530              | Notebook    | [81e9306141](https://linux-hardware.org/?probe=81e9306141) | Sep 26, 2020 |
| HP            | 1791                        | Desktop     | [f41fcdc019](https://linux-hardware.org/?probe=f41fcdc019) | Sep 26, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [3d241c321f](https://linux-hardware.org/?probe=3d241c321f) | Sep 20, 2020 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [32b487459e](https://linux-hardware.org/?probe=32b487459e) | Sep 16, 2020 |
| ASUSTek       | K52F                        | Notebook    | [cef5147eeb](https://linux-hardware.org/?probe=cef5147eeb) | Aug 30, 2020 |
| Acer          | Aspire 5732Z                | Notebook    | [c4cb936b69](https://linux-hardware.org/?probe=c4cb936b69) | Aug 30, 2020 |
| Toshiba       | Satellite L655              | Notebook    | [6251a9111f](https://linux-hardware.org/?probe=6251a9111f) | Aug 30, 2020 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [0c85729a27](https://linux-hardware.org/?probe=0c85729a27) | Aug 30, 2020 |
| ASUSTek       | EX-A320M-GAMING             | Desktop     | [4eb75f039b](https://linux-hardware.org/?probe=4eb75f039b) | Aug 17, 2020 |
| HP            | 1791                        | Desktop     | [5a21e91155](https://linux-hardware.org/?probe=5a21e91155) | Aug 15, 2020 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [ff5143e508](https://linux-hardware.org/?probe=ff5143e508) | Aug 02, 2020 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [358be6b820](https://linux-hardware.org/?probe=358be6b820) | Jul 28, 2020 |
| Lenovo        | IdeaPad Z370                | Notebook    | [51e3108708](https://linux-hardware.org/?probe=51e3108708) | Jun 28, 2020 |
| Dell          | Latitude 5501               | Notebook    | [94ec8d2a1d](https://linux-hardware.org/?probe=94ec8d2a1d) | Jun 28, 2020 |
| Lenovo        | IdeaPad Z370                | Notebook    | [76c985ed75](https://linux-hardware.org/?probe=76c985ed75) | Jun 27, 2020 |
| Dell          | Latitude E7250              | Notebook    | [c2ca61e7bf](https://linux-hardware.org/?probe=c2ca61e7bf) | Jun 23, 2020 |
| ASUSTek       | P5PE-VM                     | Desktop     | [298c1239dd](https://linux-hardware.org/?probe=298c1239dd) | May 20, 2020 |
| MSI           | B350 PC MATE                | Desktop     | [ff3852f02d](https://linux-hardware.org/?probe=ff3852f02d) | Mar 23, 2020 |
| Dell          | Inspiron 1564               | Notebook    | [b80e556643](https://linux-hardware.org/?probe=b80e556643) | Feb 02, 2020 |
| MTC           | Montara-GML                 | Notebook    | [227bf1ba1d](https://linux-hardware.org/?probe=227bf1ba1d) | Dec 07, 2019 |
| ASRock        | G31M-VS2                    | Desktop     | [b64547f948](https://linux-hardware.org/?probe=b64547f948) | Dec 06, 2019 |
| Gigabyte      | H170-HD3-CF                 | Desktop     | [338994bd66](https://linux-hardware.org/?probe=338994bd66) | Dec 02, 2019 |
| ASUSTek       | P5PE-VM                     | Desktop     | [6a89046dfb](https://linux-hardware.org/?probe=6a89046dfb) | Dec 02, 2019 |
| Microsoft     | Surface Pro 4               | Tablet      | [59ca47d9e7](https://linux-hardware.org/?probe=59ca47d9e7) | Apr 12, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Devuan 3                | 30        | 34.88%  |
| Devuan 4                | 26        | 30.23%  |
| Devuan Testing/unstable | 15        | 17.44%  |
| Devuan 2.1              | 7         | 8.14%   |
| Devuan 5                | 3         | 3.49%   |
| Devuan                  | 2         | 2.33%   |
| Devuan 3.0              | 1         | 1.16%   |
| Devuan 2.0              | 1         | 1.16%   |
| Devuan 1.0.0            | 1         | 1.16%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Devuan | 79        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Computers | Percent |
|---------------------------|-----------|---------|
| 5.10.0-9-amd64            | 7         | 7.95%   |
| 5.10.0-8-amd64            | 7         | 7.95%   |
| 4.19.0-9-amd64            | 6         | 6.82%   |
| 4.19.0-14-amd64           | 6         | 6.82%   |
| 4.19.0-16-amd64           | 5         | 5.68%   |
| 5.10.0-11-amd64           | 4         | 4.55%   |
| 5.7.0-2-amd64             | 3         | 3.41%   |
| 5.10.0-10-amd64           | 3         | 3.41%   |
| 4.19.0-12-amd64           | 3         | 3.41%   |
| 5.7.0-0.bpo.2-amd64       | 2         | 2.27%   |
| 5.15.0-2-amd64            | 2         | 2.27%   |
| 5.10.0-6-amd64            | 2         | 2.27%   |
| 4.19.0-17-amd64           | 2         | 2.27%   |
| 4.19.0-10-amd64           | 2         | 2.27%   |
| 5.9.0-4-amd64             | 1         | 1.14%   |
| 5.9.0-1-amd64             | 1         | 1.14%   |
| 5.8.0-3-amd64             | 1         | 1.14%   |
| 5.8.0-1-amd64             | 1         | 1.14%   |
| 5.7.19-server1            | 1         | 1.14%   |
| 5.7.0-1-amd64             | 1         | 1.14%   |
| 5.6.0-2-amd64             | 1         | 1.14%   |
| 5.16.0-1-amd64            | 1         | 1.14%   |
| 5.15.5-xanmod1            | 1         | 1.14%   |
| 5.15.0-0.bpo.2-amd64      | 1         | 1.14%   |
| 5.14.0-4-amd64            | 1         | 1.14%   |
| 5.11.0-6.2-liquorix-amd64 | 1         | 1.14%   |
| 5.10.0-7-amd64            | 1         | 1.14%   |
| 5.10.0-5-amd64            | 1         | 1.14%   |
| 5.10.0-4-amd64            | 1         | 1.14%   |
| 5.10.0-2-amd64            | 1         | 1.14%   |
| 5.10.0-1-amd64            | 1         | 1.14%   |
| 5.1.21                    | 1         | 1.14%   |
| 5.0.7                     | 1         | 1.14%   |
| 4.9.0-15-amd64            | 1         | 1.14%   |
| 4.9.0-14-amd64            | 1         | 1.14%   |
| 4.9.0-14-686-pae          | 1         | 1.14%   |
| 4.9.0-14-686              | 1         | 1.14%   |
| 4.9.0-11-amd64            | 1         | 1.14%   |
| 4.9.0-11-686-pae          | 1         | 1.14%   |
| 4.9.0-11-686              | 1         | 1.14%   |
| 4.9.0-0.bpo.4-686-pae     | 1         | 1.14%   |
| 4.4.195-antix.1-amd64-smp | 1         | 1.14%   |
| 4.19.112                  | 1         | 1.14%   |
| 4.19.0-17-686-pae         | 1         | 1.14%   |
| 4.19.0-13-amd64           | 1         | 1.14%   |
| 4.19.0-1-amd64            | 1         | 1.14%   |
| 4.19.0-0.bpo.6-amd64      | 1         | 1.14%   |
| 4.18.0-0.bpo.1-amd64      | 1         | 1.14%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.10.0   | 27        | 31.4%   |
| 4.19.0   | 27        | 31.4%   |
| 4.9.0    | 8         | 9.3%    |
| 5.7.0    | 6         | 6.98%   |
| 5.15.0   | 3         | 3.49%   |
| 5.9.0    | 2         | 2.33%   |
| 5.8.0    | 2         | 2.33%   |
| 5.7.19   | 1         | 1.16%   |
| 5.6.0    | 1         | 1.16%   |
| 5.16.0   | 1         | 1.16%   |
| 5.15.5   | 1         | 1.16%   |
| 5.14.0   | 1         | 1.16%   |
| 5.11.0   | 1         | 1.16%   |
| 5.1.21   | 1         | 1.16%   |
| 5.0.7    | 1         | 1.16%   |
| 4.4.195  | 1         | 1.16%   |
| 4.19.112 | 1         | 1.16%   |
| 4.18.0   | 1         | 1.16%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.19    | 28        | 32.56%  |
| 5.10    | 27        | 31.4%   |
| 4.9     | 8         | 9.3%    |
| 5.7     | 7         | 8.14%   |
| 5.15    | 4         | 4.65%   |
| 5.9     | 2         | 2.33%   |
| 5.8     | 2         | 2.33%   |
| 5.6     | 1         | 1.16%   |
| 5.16    | 1         | 1.16%   |
| 5.14    | 1         | 1.16%   |
| 5.11    | 1         | 1.16%   |
| 5.1     | 1         | 1.16%   |
| 5.0     | 1         | 1.16%   |
| 4.4     | 1         | 1.16%   |
| 4.18    | 1         | 1.16%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 72        | 91.14%  |
| i686   | 6         | 7.59%   |
| armv7l | 1         | 1.27%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| XFCE       | 32        | 38.1%   |
| Unknown    | 13        | 15.48%  |
| KDE5       | 12        | 14.29%  |
| MATE       | 11        | 13.1%   |
| LXDE       | 4         | 4.76%   |
| i3         | 4         | 4.76%   |
| LXQt       | 2         | 2.38%   |
| Cinnamon   | 2         | 2.38%   |
| X-Cinnamon | 1         | 1.19%   |
| Openbox    | 1         | 1.19%   |
| GNOME      | 1         | 1.19%   |
| awesome    | 1         | 1.19%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 71        | 87.65%  |
| Tty     | 7         | 8.64%   |
| Unknown | 3         | 3.7%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SLiM    | 29        | 35.37%  |
| Unknown | 23        | 28.05%  |
| LightDM | 22        | 26.83%  |
| SDDM    | 4         | 4.88%   |
| XDM     | 2         | 2.44%   |
| NODM    | 1         | 1.22%   |
| GDM3    | 1         | 1.22%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 24        | 29.63%  |
| en_GB       | 15        | 18.52%  |
| ru_RU       | 7         | 8.64%   |
| Unknown     | 7         | 8.64%   |
| C           | 5         | 6.17%   |
| fr_FR       | 4         | 4.94%   |
| sk_SK       | 3         | 3.7%    |
| pt_BR       | 3         | 3.7%    |
| fr_BE       | 2         | 2.47%   |
| en_AU       | 2         | 2.47%   |
| pl_PL       | 1         | 1.23%   |
| it_IT       | 1         | 1.23%   |
| es_SV       | 1         | 1.23%   |
| es_ES       | 1         | 1.23%   |
| en_US.utf-8 | 1         | 1.23%   |
| en_SG       | 1         | 1.23%   |
| en_NZ       | 1         | 1.23%   |
| en_CA       | 1         | 1.23%   |
| de_AT       | 1         | 1.23%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 52        | 65%     |
| EFI  | 28        | 35%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 65        | 82.28%  |
| Unknown | 5         | 6.33%   |
| Btrfs   | 4         | 5.06%   |
| Overlay | 2         | 2.53%   |
| OveXlay | 1         | 1.27%   |
| Ext3    | 1         | 1.27%   |
| Ext2    | 1         | 1.27%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 38        | 45.24%  |
| MBR     | 36        | 42.86%  |
| Unknown | 10        | 11.9%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 61        | 76.25%  |
| Yes       | 19        | 23.75%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 59        | 73.75%  |
| Yes       | 21        | 26.25%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 14        | 17.72%  |
| ASUSTek Computer    | 11        | 13.92%  |
| Gigabyte Technology | 10        | 12.66%  |
| Hewlett-Packard     | 6         | 7.59%   |
| Dell                | 6         | 7.59%   |
| MSI                 | 4         | 5.06%   |
| ASRock              | 4         | 5.06%   |
| Acer                | 4         | 5.06%   |
| Toshiba             | 2         | 2.53%   |
| Intel               | 2         | 2.53%   |
| Fujitsu Siemens     | 2         | 2.53%   |
| Teclast             | 1         | 1.27%   |
| Sun Microsystems    | 1         | 1.27%   |
| Samsung Electronics | 1         | 1.27%   |
| Online Labs         | 1         | 1.27%   |
| Notebook            | 1         | 1.27%   |
| Nokia               | 1         | 1.27%   |
| MTC                 | 1         | 1.27%   |
| Microsoft           | 1         | 1.27%   |
| IBM                 | 1         | 1.27%   |
| Google              | 1         | 1.27%   |
| Fujitsu             | 1         | 1.27%   |
| Chuwi               | 1         | 1.27%   |
| Apple               | 1         | 1.27%   |
| AMI                 | 1         | 1.27%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                                                     | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Toshiba Satellite M40X                                                                   | 1         | 1.27%   |
| Toshiba Satellite L655                                                                   | 1         | 1.27%   |
| Teclast F6 Plus                                                                          | 1         | 1.27%   |
| Sun Microsystems Ultra 24                                                                | 1         | 1.27%   |
| Samsung 355V4C/355V4X/355V5C/355V5X/356V4C/356V4X/356V5C/356V5X/3445VC/3445VX/3545VC/354 | 1         | 1.27%   |
| Online Labs SR                                                                           | 1         | 1.27%   |
| Notebook W230ST                                                                          | 1         | 1.27%   |
| Nokia N900                                                                               | 1         | 1.27%   |
| MTC Montara-GML                                                                          | 1         | 1.27%   |
| MSI MS-7B84                                                                              | 1         | 1.27%   |
| MSI MS-7B53                                                                              | 1         | 1.27%   |
| MSI MS-7A34                                                                              | 1         | 1.27%   |
| MSI MS-1688                                                                              | 1         | 1.27%   |
| Microsoft Surface Pro 4                                                                  | 1         | 1.27%   |
| Lenovo Yoga C640-13IML 81UE                                                              | 1         | 1.27%   |
| Lenovo ThinkStation E20 4220CTO                                                          | 1         | 1.27%   |
| Lenovo ThinkPad X60 1707YF8                                                              | 1         | 1.27%   |
| Lenovo ThinkPad X250 20CLS7WY04                                                          | 1         | 1.27%   |
| Lenovo ThinkPad X230 2325DE0                                                             | 1         | 1.27%   |
| Lenovo ThinkPad X230 23247S0                                                             | 1         | 1.27%   |
| Lenovo ThinkPad X220 429053G                                                             | 1         | 1.27%   |
| Lenovo ThinkPad X200 74585FU                                                             | 1         | 1.27%   |
| Lenovo ThinkPad X1 Tablet Gen 3 20KJCTO1WW                                               | 1         | 1.27%   |
| Lenovo ThinkPad X1 Carbon 7th 20QD00L1PB                                                 | 1         | 1.27%   |
| Lenovo ThinkPad T550 20CJS1VD01                                                          | 1         | 1.27%   |
| Lenovo ThinkPad T420 4180AG3                                                             | 1         | 1.27%   |
| Lenovo IdeaPad Z370                                                                      | 1         | 1.27%   |
| Lenovo IdeaPad 130-15AST 81H5                                                            | 1         | 1.27%   |
| Intel D815EEA AAA45884-401                                                               | 1         | 1.27%   |
| Intel AHV                                                                                | 1         | 1.27%   |
| IBM ThinkPad T41p 2373GHG                                                                | 1         | 1.27%   |
| HP Z220 SFF Workstation                                                                  | 1         | 1.27%   |
| HP ProBook 6475b                                                                         | 1         | 1.27%   |
| HP Pavilion x360 Convertible 14-dh1xxx                                                   | 1         | 1.27%   |
| HP Pavilion 11 x360 PC                                                                   | 1         | 1.27%   |
| HP EliteDesk 800 G1 DM                                                                   | 1         | 1.27%   |
| HP Compaq 8200 Elite SFF PC                                                              | 1         | 1.27%   |
| Google Panther                                                                           | 1         | 1.27%   |
| Gigabyte Z390 GAMING SLI                                                                 | 1         | 1.27%   |
| Gigabyte P55A-UD3                                                                        | 1         | 1.27%   |
| Gigabyte MZGLKBP-00                                                                      | 1         | 1.27%   |
| Gigabyte H310M S2H 2.0                                                                   | 1         | 1.27%   |
| Gigabyte H170-HD3-CF                                                                     | 1         | 1.27%   |
| Gigabyte H170-HD3                                                                        | 1         | 1.27%   |
| Gigabyte GA-G41M-ES2L                                                                    | 1         | 1.27%   |
| Gigabyte B75M-D3V                                                                        | 1         | 1.27%   |
| Gigabyte B450 AORUS ELITE                                                                | 1         | 1.27%   |
| Gigabyte 970A-DS3P                                                                       | 1         | 1.27%   |
| Fujitsu Siemens ESPRIMO Mobile V6535                                                     | 1         | 1.27%   |
| Fujitsu Siemens AMILO Xi 1546                                                            | 1         | 1.27%   |
| Fujitsu LIFEBOOK U7510                                                                   | 1         | 1.27%   |
| Dell Precision 7530                                                                      | 1         | 1.27%   |
| Dell OptiPlex 7010                                                                       | 1         | 1.27%   |
| Dell Latitude E7250                                                                      | 1         | 1.27%   |
| Dell Latitude E5540                                                                      | 1         | 1.27%   |
| Dell Latitude 5501                                                                       | 1         | 1.27%   |
| Dell Inspiron 1564                                                                       | 1         | 1.27%   |
| Chuwi Hi10 pro tablet                                                                    | 1         | 1.27%   |
| ASUS X555LJ                                                                              | 1         | 1.27%   |
| ASUS PRIME Z490M-PLUS                                                                    | 1         | 1.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 10        | 12.66%  |
| Dell Latitude           | 3         | 3.8%    |
| Acer Aspire             | 3         | 3.8%    |
| Toshiba Satellite       | 2         | 2.53%   |
| Lenovo IdeaPad          | 2         | 2.53%   |
| HP Pavilion             | 2         | 2.53%   |
| ASUS PRIME              | 2         | 2.53%   |
| Teclast F6              | 1         | 1.27%   |
| Sun Microsystems Ultra  | 1         | 1.27%   |
| Samsung 355V4C          | 1         | 1.27%   |
| Online Labs SR          | 1         | 1.27%   |
| Notebook W230ST         | 1         | 1.27%   |
| Nokia N900              | 1         | 1.27%   |
| MTC Montara-GML         | 1         | 1.27%   |
| MSI MS-7B84             | 1         | 1.27%   |
| MSI MS-7B53             | 1         | 1.27%   |
| MSI MS-7A34             | 1         | 1.27%   |
| MSI MS-1688             | 1         | 1.27%   |
| Microsoft Surface       | 1         | 1.27%   |
| Lenovo Yoga             | 1         | 1.27%   |
| Lenovo ThinkStation     | 1         | 1.27%   |
| Intel D815EEA           | 1         | 1.27%   |
| Intel AHV               | 1         | 1.27%   |
| IBM ThinkPad            | 1         | 1.27%   |
| HP Z220                 | 1         | 1.27%   |
| HP ProBook              | 1         | 1.27%   |
| HP EliteDesk            | 1         | 1.27%   |
| HP Compaq               | 1         | 1.27%   |
| Google Panther          | 1         | 1.27%   |
| Gigabyte Z390           | 1         | 1.27%   |
| Gigabyte P55A-UD3       | 1         | 1.27%   |
| Gigabyte MZGLKBP-00     | 1         | 1.27%   |
| Gigabyte H310M          | 1         | 1.27%   |
| Gigabyte H170-HD3-CF    | 1         | 1.27%   |
| Gigabyte H170-HD3       | 1         | 1.27%   |
| Gigabyte GA-G41M-ES2L   | 1         | 1.27%   |
| Gigabyte B75M-D3V       | 1         | 1.27%   |
| Gigabyte B450           | 1         | 1.27%   |
| Gigabyte 970A-DS3P      | 1         | 1.27%   |
| Fujitsu Siemens ESPRIMO | 1         | 1.27%   |
| Fujitsu Siemens AMILO   | 1         | 1.27%   |
| Fujitsu LIFEBOOK        | 1         | 1.27%   |
| Dell Precision          | 1         | 1.27%   |
| Dell OptiPlex           | 1         | 1.27%   |
| Dell Inspiron           | 1         | 1.27%   |
| Chuwi Hi10              | 1         | 1.27%   |
| ASUS X555LJ             | 1         | 1.27%   |
| ASUS P5PE-VM            | 1         | 1.27%   |
| ASUS P5G41T-M           | 1         | 1.27%   |
| ASUS Maximus            | 1         | 1.27%   |
| ASUS K55VJ              | 1         | 1.27%   |
| ASUS K52F               | 1         | 1.27%   |
| ASUS F1A55-M            | 1         | 1.27%   |
| ASUS EX-A320M-GAMING    | 1         | 1.27%   |
| ASUS All                | 1         | 1.27%   |
| ASRock K8A780LM         | 1         | 1.27%   |
| ASRock H81M-ITX         | 1         | 1.27%   |
| ASRock G31M-VS2         | 1         | 1.27%   |
| ASRock B450M-HDV        | 1         | 1.27%   |
| Apple Macmini3          | 1         | 1.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 11        | 13.92%  |
| 2012    | 9         | 11.39%  |
| 2019    | 7         | 8.86%   |
| 2014    | 7         | 8.86%   |
| 2011    | 7         | 8.86%   |
| 2015    | 5         | 6.33%   |
| 2009    | 5         | 6.33%   |
| 2013    | 4         | 5.06%   |
| 2008    | 4         | 5.06%   |
| 2016    | 3         | 3.8%    |
| 2010    | 3         | 3.8%    |
| 2006    | 3         | 3.8%    |
| 2020    | 2         | 2.53%   |
| 2017    | 2         | 2.53%   |
| 2007    | 2         | 2.53%   |
| 2005    | 2         | 2.53%   |
| 2021    | 1         | 1.27%   |
| 2000    | 1         | 1.27%   |
| Unknown | 1         | 1.27%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Desktop     | 36        | 45.57%  |
| Notebook    | 36        | 45.57%  |
| Tablet      | 3         | 3.8%    |
| Convertible | 2         | 2.53%   |
| Mini pc     | 2         | 2.53%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 79        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 76        | 96.2%   |
| Yes  | 3         | 3.8%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 16        | 20.25%  |
| 8.01-16.0   | 16        | 20.25%  |
| 3.01-4.0    | 14        | 17.72%  |
| 16.01-24.0  | 14        | 17.72%  |
| 32.01-64.0  | 7         | 8.86%   |
| 1.01-2.0    | 6         | 7.59%   |
| 0.01-0.5    | 3         | 3.8%    |
| 2.01-3.0    | 2         | 2.53%   |
| 64.01-256.0 | 1         | 1.27%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 27        | 31.4%   |
| 4.01-8.0   | 17        | 19.77%  |
| 2.01-3.0   | 15        | 17.44%  |
| 0.51-1.0   | 13        | 15.12%  |
| 3.01-4.0   | 6         | 6.98%   |
| 0.01-0.5   | 4         | 4.65%   |
| 8.01-16.0  | 3         | 3.49%   |
| 32.01-64.0 | 1         | 1.16%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 48        | 60.76%  |
| 2      | 14        | 17.72%  |
| 3      | 9         | 11.39%  |
| 4      | 5         | 6.33%   |
| 5      | 3         | 3.8%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 51        | 63.75%  |
| Yes       | 29        | 36.25%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 71        | 89.87%  |
| No        | 8         | 10.13%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 47        | 58.75%  |
| No        | 33        | 41.25%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 53        | 67.09%  |
| Yes       | 26        | 32.91%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Russia      | 9         | 11.39%  |
| France      | 8         | 10.13%  |
| Ukraine     | 6         | 7.59%   |
| USA         | 5         | 6.33%   |
| Brazil      | 5         | 6.33%   |
| Grenada     | 4         | 5.06%   |
| Germany     | 4         | 5.06%   |
| Slovakia    | 3         | 3.8%    |
| Poland      | 3         | 3.8%    |
| Netherlands | 3         | 3.8%    |
| UK          | 2         | 2.53%   |
| Israel      | 2         | 2.53%   |
| Hungary     | 2         | 2.53%   |
| Australia   | 2         | 2.53%   |
| Argentina   | 2         | 2.53%   |
| Vietnam     | 1         | 1.27%   |
| Switzerland | 1         | 1.27%   |
| Spain       | 1         | 1.27%   |
| South Korea | 1         | 1.27%   |
| Singapore   | 1         | 1.27%   |
| Puerto Rico | 1         | 1.27%   |
| Portugal    | 1         | 1.27%   |
| Norway      | 1         | 1.27%   |
| New Zealand | 1         | 1.27%   |
| Mexico      | 1         | 1.27%   |
| Italy       | 1         | 1.27%   |
| Indonesia   | 1         | 1.27%   |
| India       | 1         | 1.27%   |
| Greece      | 1         | 1.27%   |
| Finland     | 1         | 1.27%   |
| El Salvador | 1         | 1.27%   |
| Canada      | 1         | 1.27%   |
| Belgium     | 1         | 1.27%   |
| Austria     | 1         | 1.27%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Bagnolet             | 4         | 4.94%   |
| Kyiv                 | 3         | 3.7%    |
| Gouyave              | 3         | 3.7%    |
| Bratislava           | 3         | 3.7%    |
| Wroclaw              | 2         | 2.47%   |
| Volzhskiy            | 2         | 2.47%   |
| Tel Aviv             | 2         | 2.47%   |
| Sao Paulo            | 2         | 2.47%   |
| Ryde                 | 2         | 2.47%   |
| Rio de Janeiro       | 2         | 2.47%   |
| Hillsborough         | 2         | 2.47%   |
| Budapest             | 2         | 2.47%   |
| Zeist                | 1         | 1.23%   |
| Yakutsk              | 1         | 1.23%   |
| Wageningen           | 1         | 1.23%   |
| Vologda              | 1         | 1.23%   |
| Toronto              | 1         | 1.23%   |
| Thrissur             | 1         | 1.23%   |
| Thessaloniki         | 1         | 1.23%   |
| Talavera de la Reina | 1         | 1.23%   |
| Syeverodonets'k      | 1         | 1.23%   |
| St Petersburg        | 1         | 1.23%   |
| Singapore            | 1         | 1.23%   |
| Seongbuk-gu          | 1         | 1.23%   |
| Sao Vicente          | 1         | 1.23%   |
| San Salvador         | 1         | 1.23%   |
| Saint-Herblain       | 1         | 1.23%   |
| Poperinge            | 1         | 1.23%   |
| Paris                | 1         | 1.23%   |
| Oslo                 | 1         | 1.23%   |
| Oleksandriya         | 1         | 1.23%   |
| NГ©rac             | 1         | 1.23%   |
| Nadudvar             | 1         | 1.23%   |
| Mozdok               | 1         | 1.23%   |
| Moscow               | 1         | 1.23%   |
| Milan                | 1         | 1.23%   |
| Miedziana Gora       | 1         | 1.23%   |
| Miami                | 1         | 1.23%   |
| Mglin                | 1         | 1.23%   |
| Lisbon               | 1         | 1.23%   |
| Leonding             | 1         | 1.23%   |
| Leipzig              | 1         | 1.23%   |
| Kirov                | 1         | 1.23%   |
| JyvГ¤skylГ¤      | 1         | 1.23%   |
| Hochheim am Main     | 1         | 1.23%   |
| Hermosillo           | 1         | 1.23%   |
| Hayden               | 1         | 1.23%   |
| Hanoi                | 1         | 1.23%   |
| Haiger               | 1         | 1.23%   |
| Great Bend           | 1         | 1.23%   |
| Forest Grove         | 1         | 1.23%   |
| Donetsk              | 1         | 1.23%   |
| Depok                | 1         | 1.23%   |
| Cologne              | 1         | 1.23%   |
| Coghlan              | 1         | 1.23%   |
| Cipolletti           | 1         | 1.23%   |
| ChГўteau-Thierry   | 1         | 1.23%   |
| Carlisle             | 1         | 1.23%   |
| Caguas               | 1         | 1.23%   |
| Bradford             | 1         | 1.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 23        | 34     | 19.66%  |
| Seagate             | 16        | 24     | 13.68%  |
| Kingston            | 10        | 12     | 8.55%   |
| Samsung Electronics | 9         | 15     | 7.69%   |
| Unknown             | 6         | 8      | 5.13%   |
| Toshiba             | 5         | 5      | 4.27%   |
| Crucial             | 5         | 6      | 4.27%   |
| Hitachi             | 4         | 4      | 3.42%   |
| PNY                 | 3         | 3      | 2.56%   |
| Fujitsu             | 3         | 3      | 2.56%   |
| SK Hynix            | 2         | 2      | 1.71%   |
| Netac               | 2         | 2      | 1.71%   |
| HGST                | 2         | 2      | 1.71%   |
| Hewlett-Packard     | 2         | 3      | 1.71%   |
| DOGFISH             | 2         | 2      | 1.71%   |
| A-DATA Technology   | 2         | 2      | 1.71%   |
| WD MediaMax         | 1         | 2      | 0.85%   |
| Union Memory        | 1         | 2      | 0.85%   |
| Transcend           | 1         | 2      | 0.85%   |
| Teclast             | 1         | 1      | 0.85%   |
| Team                | 1         | 1      | 0.85%   |
| SMART               | 1         | 1      | 0.85%   |
| SanDisk             | 1         | 1      | 0.85%   |
| SABRENT             | 1         | 2      | 0.85%   |
| Patriot             | 1         | 1      | 0.85%   |
| Micron Technology   | 1         | 1      | 0.85%   |
| MAXTOR              | 1         | 1      | 0.85%   |
| LITEON              | 1         | 3      | 0.85%   |
| Lenovo              | 1         | 1      | 0.85%   |
| Kston               | 1         | 1      | 0.85%   |
| KIOXIA              | 1         | 1      | 0.85%   |
| KingFast            | 1         | 1      | 0.85%   |
| KingDian            | 1         | 1      | 0.85%   |
| Intel               | 1         | 1      | 0.85%   |
| IBM/Hitachi         | 1         | 1      | 0.85%   |
| HXY                 | 1         | 1      | 0.85%   |
| GOODRAM             | 1         | 1      | 0.85%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| PNY CS900 240GB SSD                     | 3         | 2.29%   |
| Kingston SA2000M8250G 250GB             | 3         | 2.29%   |
| WDC WD5000BPVT-24HXZT3 500GB            | 2         | 1.53%   |
| WDC WD10EARX-00N0YB0 1TB                | 2         | 1.53%   |
| Seagate ST2000DX002-2DV164 2TB          | 2         | 1.53%   |
| Samsung SSD 860 EVO 250GB               | 2         | 1.53%   |
| Kingston SA400S37480G 480GB SSD         | 2         | 1.53%   |
| Kingston SA400S37120G 120GB SSD         | 2         | 1.53%   |
| WDC WDS480G2G0A-00JH30 480GB SSD        | 1         | 0.76%   |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 1         | 0.76%   |
| WDC WDS120G2G0A-00JH30 120GB SSD        | 1         | 0.76%   |
| WDC WD800BB-00JHC0 80GB                 | 1         | 0.76%   |
| WDC WD7500BPKX-00HPJT0 752GB            | 1         | 0.76%   |
| WDC WD5001AALS-00L3B2 500GB             | 1         | 0.76%   |
| WDC WD5001AALS-00E3A0 500GB             | 1         | 0.76%   |
| WDC WD5000LPVX-00V0TT0 500GB            | 1         | 0.76%   |
| WDC WD40EFRX-68WT0N0 4TB                | 1         | 0.76%   |
| WDC WD3200BPVT-22JJ5T0 320GB            | 1         | 0.76%   |
| WDC WD3200BEVT-22A23T0 320GB            | 1         | 0.76%   |
| WDC WD3200BEVE-00A0HT0 320GB            | 1         | 0.76%   |
| WDC WD2500BEKT-00A25T0 250GB            | 1         | 0.76%   |
| WDC WD20PURZ-85GU6Y0 2TB                | 1         | 0.76%   |
| WDC WD20EZRX-00D8PB0 2TB                | 1         | 0.76%   |
| WDC WD20EFRX-68EUZN0 2TB                | 1         | 0.76%   |
| WDC WD1200JS-55NCB1 120GB               | 1         | 0.76%   |
| WDC WD10SPZX-21Z10T0 1TB                | 1         | 0.76%   |
| WDC WD10EZRX-00D8PB0 1TB                | 1         | 0.76%   |
| WDC WD10EZEX-75M2NA0 1TB                | 1         | 0.76%   |
| WDC WD10EZEX-22MFCA0 1TB                | 1         | 0.76%   |
| WDC WD10EZEX-22BN5A0 1TB                | 1         | 0.76%   |
| WDC WD10EZEX-08WN4A0 1TB                | 1         | 0.76%   |
| WDC WD10EURX-63FH1Y0 1TB                | 1         | 0.76%   |
| WD MediaMax WL500GSA3272 500GB          | 1         | 0.76%   |
| Unknown SD64G  64GB                     | 1         | 0.76%   |
| Unknown SD04G  4GB                      | 1         | 0.76%   |
| Unknown SD  8GB                         | 1         | 0.76%   |
| Unknown S0J9F8  64GB                    | 1         | 0.76%   |
| Unknown MMC32G  32GB                    | 1         | 0.76%   |
| Unknown MMC Card  32GB                  | 1         | 0.76%   |
| Unknown MMC Card  16GB                  | 1         | 0.76%   |
| Unknown MMC Card  128GB                 | 1         | 0.76%   |
| Union Memory RTOTJ128VGD2EYX 128GB SSD  | 1         | 0.76%   |
| Transcend TS128GSSD370S 128GB           | 1         | 0.76%   |
| Toshiba MQ04ABF100 1TB                  | 1         | 0.76%   |
| Toshiba MQ02ABF100 1TB                  | 1         | 0.76%   |
| Toshiba MK1252GSX 120GB                 | 1         | 0.76%   |
| Toshiba HDWD110 1TB                     | 1         | 0.76%   |
| Toshiba DT01ACA100 1TB                  | 1         | 0.76%   |
| Teclast 256GB NS550-2242 SSD            | 1         | 0.76%   |
| Team T253X1120G 120GB SSD               | 1         | 0.76%   |
| SMART SSD SZ9MSE mSATA 256GB            | 1         | 0.76%   |
| SK Hynix PC611 NVMe 1TB                 | 1         | 0.76%   |
| SK Hynix BC511 HFM256GDJTNI-82A0A 256GB | 1         | 0.76%   |
| Seagate ST9250410AS 250GB               | 1         | 0.76%   |
| Seagate ST8000DM004-2CX188 8TB          | 1         | 0.76%   |
| Seagate ST750LX003-1AC154 752GB         | 1         | 0.76%   |
| Seagate ST500LT012-1DG142 500GB         | 1         | 0.76%   |
| Seagate ST500DM002-1BD142 500GB         | 1         | 0.76%   |
| Seagate ST4000VN008-2DR166 4TB          | 1         | 0.76%   |
| Seagate ST4000DM005-2DP166 4TB          | 1         | 0.76%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor          | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| WDC             | 20        | 30     | 37.04%  |
| Seagate         | 16        | 24     | 29.63%  |
| Toshiba         | 5         | 5      | 9.26%   |
| Hitachi         | 4         | 4      | 7.41%   |
| Fujitsu         | 3         | 3      | 5.56%   |
| HGST            | 2         | 2      | 3.7%    |
| SABRENT         | 1         | 2      | 1.85%   |
| MAXTOR          | 1         | 1      | 1.85%   |
| IBM/Hitachi     | 1         | 1      | 1.85%   |
| Hewlett-Packard | 1         | 2      | 1.85%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 7         | 8      | 16.67%  |
| Samsung Electronics | 6         | 7      | 14.29%  |
| WDC                 | 3         | 4      | 7.14%   |
| PNY                 | 3         | 3      | 7.14%   |
| Crucial             | 3         | 3      | 7.14%   |
| Netac               | 2         | 2      | 4.76%   |
| DOGFISH             | 2         | 2      | 4.76%   |
| A-DATA Technology   | 2         | 2      | 4.76%   |
| Union Memory        | 1         | 2      | 2.38%   |
| Transcend           | 1         | 2      | 2.38%   |
| Teclast             | 1         | 1      | 2.38%   |
| Team                | 1         | 1      | 2.38%   |
| SMART               | 1         | 1      | 2.38%   |
| SanDisk             | 1         | 1      | 2.38%   |
| Patriot             | 1         | 1      | 2.38%   |
| Micron Technology   | 1         | 1      | 2.38%   |
| LITEON              | 1         | 3      | 2.38%   |
| Kston               | 1         | 1      | 2.38%   |
| KingDian            | 1         | 1      | 2.38%   |
| HXY                 | 1         | 1      | 2.38%   |
| Hewlett-Packard     | 1         | 1      | 2.38%   |
| GOODRAM             | 1         | 1      | 2.38%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 47        | 74     | 43.93%  |
| SSD     | 39        | 49     | 36.45%  |
| NVMe    | 13        | 20     | 12.15%  |
| MMC     | 6         | 8      | 5.61%   |
| Unknown | 2         | 3      | 1.87%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 69        | 118    | 75%     |
| NVMe | 13        | 20     | 14.13%  |
| MMC  | 6         | 8      | 6.52%   |
| SAS  | 4         | 8      | 4.35%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 53        | 74     | 63.86%  |
| 0.51-1.0   | 19        | 33     | 22.89%  |
| 1.01-2.0   | 7         | 12     | 8.43%   |
| 3.01-4.0   | 3         | 3      | 3.61%   |
| 4.01-10.0  | 1         | 1      | 1.2%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 19        | 22.35%  |
| 101-250        | 16        | 18.82%  |
| 1001-2000      | 14        | 16.47%  |
| 21-50          | 8         | 9.41%   |
| 501-1000       | 8         | 9.41%   |
| 51-100         | 6         | 7.06%   |
| Unknown        | 6         | 7.06%   |
| More than 3000 | 3         | 3.53%   |
| 1-20           | 3         | 3.53%   |
| 2001-3000      | 2         | 2.35%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 23        | 27.38%  |
| 1-20           | 22        | 26.19%  |
| 21-50          | 9         | 10.71%  |
| 501-1000       | 7         | 8.33%   |
| 51-100         | 7         | 8.33%   |
| 1001-2000      | 6         | 7.14%   |
| Unknown        | 6         | 7.14%   |
| 251-500        | 3         | 3.57%   |
| More than 3000 | 1         | 1.19%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD5000BPVT-24HXZT3 500GB      | 2         | 2      | 13.33%  |
| WDC WD5000LPVX-00V0TT0 500GB      | 1         | 1      | 6.67%   |
| WDC WD3200BEVT-22A23T0 320GB      | 1         | 1      | 6.67%   |
| WDC WD10EARX-00N0YB0 1TB          | 1         | 1      | 6.67%   |
| Toshiba MQ04ABF100 1TB            | 1         | 1      | 6.67%   |
| Toshiba MQ02ABF100 1TB            | 1         | 1      | 6.67%   |
| MAXTOR 6E040L0 41GB               | 1         | 1      | 6.67%   |
| Kingston SA400S37120G 120GB SSD   | 1         | 1      | 6.67%   |
| Hitachi HTS727575A9E364 752GB     | 1         | 1      | 6.67%   |
| Hitachi HTS726060M9AT00 56GB      | 1         | 1      | 6.67%   |
| Hitachi HDS721616PLA380 164GB     | 1         | 1      | 6.67%   |
| HGST HTE721010A9E630 1TB          | 1         | 1      | 6.67%   |
| Hewlett-Packard VB0250EAVER 250GB | 1         | 2      | 6.67%   |
| Fujitsu MHV2060BH PL 64GB         | 1         | 1      | 6.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor          | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| WDC             | 5         | 5      | 33.33%  |
| Hitachi         | 3         | 3      | 20%     |
| Toshiba         | 2         | 2      | 13.33%  |
| MAXTOR          | 1         | 1      | 6.67%   |
| Kingston        | 1         | 1      | 6.67%   |
| HGST            | 1         | 1      | 6.67%   |
| Hewlett-Packard | 1         | 2      | 6.67%   |
| Fujitsu         | 1         | 1      | 6.67%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor          | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| WDC             | 5         | 5      | 35.71%  |
| Hitachi         | 3         | 3      | 21.43%  |
| Toshiba         | 2         | 2      | 14.29%  |
| MAXTOR          | 1         | 1      | 7.14%   |
| HGST            | 1         | 1      | 7.14%   |
| Hewlett-Packard | 1         | 2      | 7.14%   |
| Fujitsu         | 1         | 1      | 7.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 14        | 15     | 93.33%  |
| SSD  | 1         | 1      | 6.67%   |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 57        | 100    | 61.29%  |
| Detected | 22        | 38     | 23.66%  |
| Malfunc  | 14        | 16     | 15.05%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 59        | 63.44%  |
| AMD                              | 12        | 12.9%   |
| Kingston Technology Company      | 4         | 4.3%    |
| Samsung Electronics              | 3         | 3.23%   |
| SK Hynix                         | 2         | 2.15%   |
| Micron/Crucial Technology        | 2         | 2.15%   |
| Marvell Technology Group         | 2         | 2.15%   |
| VIA Technologies                 | 1         | 1.08%   |
| Silicon Integrated Systems [SiS] | 1         | 1.08%   |
| Nvidia                           | 1         | 1.08%   |
| Lenovo                           | 1         | 1.08%   |
| KIOXIA                           | 1         | 1.08%   |
| Integrated Technology Express    | 1         | 1.08%   |
| Broadcom / LSI                   | 1         | 1.08%   |
| ASMedia Technology               | 1         | 1.08%   |
| Adaptec                          | 1         | 1.08%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Computers | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 8         | 7.41%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 5         | 4.63%   |
| Kingston Company A2000 NVMe SSD                                                        | 4         | 3.7%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 4         | 3.7%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 4         | 3.7%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                      | 3         | 2.78%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 3         | 2.78%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]           | 3         | 2.78%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 3         | 2.78%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 3         | 2.78%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 3         | 2.78%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 3         | 2.78%   |
| AMD 400 Series Chipset SATA Controller                                                 | 3         | 2.78%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                        | 2         | 1.85%   |
| Intel SATA Controller [RAID mode]                                                      | 2         | 1.85%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 2         | 1.85%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                             | 2         | 1.85%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 2         | 1.85%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 2         | 1.85%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                                 | 2         | 1.85%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 2         | 1.85%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 2         | 1.85%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 2         | 1.85%   |
| VIA VT6421 IDE/SATA Controller                                                         | 1         | 0.93%   |
| SK Hynix Non-Volatile memory controller                                                | 1         | 0.93%   |
| SK Hynix BC511                                                                         | 1         | 0.93%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                            | 1         | 0.93%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                   | 1         | 0.93%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 1         | 0.93%   |
| Samsung NVMe SSD Controller SM951/PM951                                                | 1         | 0.93%   |
| Samsung NVMe SSD Controller 980                                                        | 1         | 0.93%   |
| Nvidia MCP79 SATA Controller                                                           | 1         | 0.93%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                       | 1         | 0.93%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller                                | 1         | 0.93%   |
| Lenovo Non-Volatile memory controller                                                  | 1         | 0.93%   |
| KIOXIA Non-Volatile memory controller                                                  | 1         | 0.93%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                | 1         | 0.93%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 1         | 0.93%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 1         | 0.93%   |
| Intel Atom processor C2000 AHCI SATA3 Controller                                       | 1         | 0.93%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                   | 1         | 0.93%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 1         | 0.93%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 1         | 0.93%   |
| Intel 82801FBM (ICH6M) SATA Controller                                                 | 1         | 0.93%   |
| Intel 82801EB/ER (ICH5/ICH5R) IDE Controller                                           | 1         | 0.93%   |
| Intel 82801BA IDE U100 Controller                                                      | 1         | 0.93%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 0.93%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 0.93%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller          | 1         | 0.93%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                   | 1         | 0.93%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                          | 1         | 0.93%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                          | 1         | 0.93%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                       | 1         | 0.93%   |
| Integrated Express IT8213 IDE Controller                                               | 1         | 0.93%   |
| Broadcom / LSI SAS1068E PCI-Express Fusion-MPT SAS                                     | 1         | 0.93%   |
| ASMedia ASM1062 Serial ATA Controller                                                  | 1         | 0.93%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                   | 1         | 0.93%   |
| AMD FCH SATA Controller [IDE mode]                                                     | 1         | 0.93%   |
| AMD FCH SATA Controller D                                                              | 1         | 0.93%   |
| AMD FCH IDE Controller                                                                 | 1         | 0.93%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 55        | 60.44%  |
| IDE  | 17        | 18.68%  |
| NVMe | 13        | 14.29%  |
| RAID | 5         | 5.49%   |
| SCSI | 1         | 1.1%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 66        | 83.54%  |
| AMD    | 12        | 15.19%  |
| ARM    | 1         | 1.27%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-5300U CPU @ 2.30GHz           | 3         | 3.75%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 2         | 2.5%    |
| Intel Core i5-6400 CPU @ 2.70GHz            | 2         | 2.5%    |
| Intel Core i5-6300U CPU @ 2.40GHz           | 2         | 2.5%    |
| Intel Core i5-3320M CPU @ 2.60GHz           | 2         | 2.5%    |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2         | 2.5%    |
| AMD Ryzen 5 1600 Six-Core Processor         | 2         | 2.5%    |
| Intel Xeon CPU X3460 @ 2.80GHz              | 1         | 1.25%   |
| Intel Xeon CPU E3-1270 V2 @ 3.50GHz         | 1         | 1.25%   |
| Intel Xeon CPU E3-1226 v3 @ 3.30GHz         | 1         | 1.25%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz    | 1         | 1.25%   |
| Intel Pentium M processor 1700MHz           | 1         | 1.25%   |
| Intel Pentium M processor 1.60GHz           | 1         | 1.25%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz      | 1         | 1.25%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 1.25%   |
| Intel Pentium Dual-Core CPU E6300 @ 2.80GHz | 1         | 1.25%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz      | 1         | 1.25%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1         | 1.25%   |
| Intel Pentium CPU P6100 @ 2.00GHz           | 1         | 1.25%   |
| Intel Pentium CPU G3240 @ 3.10GHz           | 1         | 1.25%   |
| Intel Pentium 4 CPU 3.00GHz                 | 1         | 1.25%   |
| Intel Core i9-8950HK CPU @ 2.90GHz          | 1         | 1.25%   |
| Intel Core i9-10850K CPU @ 3.60GHz          | 1         | 1.25%   |
| Intel Core i7-9850H CPU @ 2.60GHz           | 1         | 1.25%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 1.25%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 1.25%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 1         | 1.25%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 1         | 1.25%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1         | 1.25%   |
| Intel Core i7-3610QM CPU @ 2.30GHz          | 1         | 1.25%   |
| Intel Core i7-2640M CPU @ 2.80GHz           | 1         | 1.25%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 1         | 1.25%   |
| Intel Core i5-4590T CPU @ 2.00GHz           | 1         | 1.25%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1         | 1.25%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 1         | 1.25%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 1         | 1.25%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 1         | 1.25%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 1         | 1.25%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 1         | 1.25%   |
| Intel Core i5-10310U CPU @ 1.70GHz          | 1         | 1.25%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 1         | 1.25%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 1         | 1.25%   |
| Intel Core i3-4010U CPU @ 1.70GHz           | 1         | 1.25%   |
| Intel Core i3-2350M CPU @ 2.30GHz           | 1         | 1.25%   |
| Intel Core i3-10110U CPU @ 2.10GHz          | 1         | 1.25%   |
| Intel Core i3 CPU M 380 @ 2.53GHz           | 1         | 1.25%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 1         | 1.25%   |
| Intel Core i3 CPU M 330 @ 2.13GHz           | 1         | 1.25%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 1         | 1.25%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz        | 1         | 1.25%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 1         | 1.25%   |
| Intel Core 2 CPU T7200 @ 2.00GHz            | 1         | 1.25%   |
| Intel Core 2 CPU T5600 @ 1.83GHz            | 1         | 1.25%   |
| Intel Core 2 CPU P8600 @ 2.40GHz            | 1         | 1.25%   |
| Intel Celeron N4100 CPU @ 1.10GHz           | 1         | 1.25%   |
| Intel Celeron M processor 1.40GHz           | 1         | 1.25%   |
| Intel Celeron CPU N2830 @ 2.16GHz           | 1         | 1.25%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 1         | 1.25%   |
| Intel Celeron (Coppermine)                  | 1         | 1.25%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 1         | 1.25%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 20        | 25%     |
| Intel Core i7           | 9         | 11.25%  |
| Intel Core i3           | 7         | 8.75%   |
| Intel Core 2 Duo        | 4         | 5%      |
| Intel Celeron           | 4         | 5%      |
| Intel Xeon              | 3         | 3.75%   |
| Intel Core 2            | 3         | 3.75%   |
| AMD Ryzen 5             | 3         | 3.75%   |
| Other                   | 2         | 2.5%    |
| Intel Pentium M         | 2         | 2.5%    |
| Intel Pentium Dual-Core | 2         | 2.5%    |
| Intel Pentium Dual      | 2         | 2.5%    |
| Intel Pentium           | 2         | 2.5%    |
| Intel Core i9           | 2         | 2.5%    |
| Intel Atom              | 2         | 2.5%    |
| AMD Ryzen 3             | 2         | 2.5%    |
| Intel Pentium Silver    | 1         | 1.25%   |
| Intel Pentium Gold      | 1         | 1.25%   |
| Intel Pentium 4         | 1         | 1.25%   |
| Intel Core 2 Quad       | 1         | 1.25%   |
| Intel Celeron M         | 1         | 1.25%   |
| AMD Sempron             | 1         | 1.25%   |
| AMD FX                  | 1         | 1.25%   |
| AMD E2                  | 1         | 1.25%   |
| AMD E                   | 1         | 1.25%   |
| AMD A6                  | 1         | 1.25%   |
| AMD A4                  | 1         | 1.25%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 36        | 45.57%  |
| 4      | 25        | 31.65%  |
| 6      | 8         | 10.13%  |
| 1      | 8         | 10.13%  |
| 10     | 1         | 1.27%   |
| 8      | 1         | 1.27%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 79        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 41        | 51.9%   |
| 2      | 38        | 48.1%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 72        | 91.14%  |
| 32-bit         | 4         | 5.06%   |
| Unknown        | 3         | 3.8%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 20        | 24.69%  |
| 0x206a7    | 6         | 7.41%   |
| 0x1067a    | 5         | 6.17%   |
| 0x806ec    | 4         | 4.94%   |
| 0x306a9    | 4         | 4.94%   |
| 0x906ea    | 3         | 3.7%    |
| 0x306d4    | 3         | 3.7%    |
| 0x306c3    | 3         | 3.7%    |
| 0x706a1    | 2         | 2.47%   |
| 0x6f6      | 2         | 2.47%   |
| 0x406e3    | 2         | 2.47%   |
| 0x40651    | 2         | 2.47%   |
| 0x20655    | 2         | 2.47%   |
| 0xf49      | 1         | 1.23%   |
| 0xa0655    | 1         | 1.23%   |
| 0xa0653    | 1         | 1.23%   |
| 0x906ed    | 1         | 1.23%   |
| 0x806ea    | 1         | 1.23%   |
| 0x6fd      | 1         | 1.23%   |
| 0x6d8      | 1         | 1.23%   |
| 0x695      | 1         | 1.23%   |
| 0x686      | 1         | 1.23%   |
| 0x506e3    | 1         | 1.23%   |
| 0x406d8    | 1         | 1.23%   |
| 0x406c4    | 1         | 1.23%   |
| 0x30678    | 1         | 1.23%   |
| 0x20652    | 1         | 1.23%   |
| 0x106e5    | 1         | 1.23%   |
| 0x10676    | 1         | 1.23%   |
| 0x08701021 | 1         | 1.23%   |
| 0x08701013 | 1         | 1.23%   |
| 0x08001138 | 1         | 1.23%   |
| 0x08001129 | 1         | 1.23%   |
| 0x05000119 | 1         | 1.23%   |
| 0x05000101 | 1         | 1.23%   |
| 0x03000027 | 1         | 1.23%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 10        | 12.66%  |
| Penryn        | 7         | 8.86%   |
| SandyBridge   | 6         | 7.59%   |
| IvyBridge     | 6         | 7.59%   |
| Haswell       | 6         | 7.59%   |
| Westmere      | 4         | 5.06%   |
| Skylake       | 4         | 5.06%   |
| Silvermont    | 4         | 5.06%   |
| P6            | 4         | 5.06%   |
| Core          | 4         | 5.06%   |
| Broadwell     | 4         | 5.06%   |
| Zen 2         | 2         | 2.53%   |
| Zen           | 2         | 2.53%   |
| Piledriver    | 2         | 2.53%   |
| Nehalem       | 2         | 2.53%   |
| Goldmont plus | 2         | 2.53%   |
| CometLake     | 2         | 2.53%   |
| Bobcat        | 2         | 2.53%   |
| Zen+          | 1         | 1.27%   |
| NetBurst      | 1         | 1.27%   |
| K8 Hammer     | 1         | 1.27%   |
| K10 Llano     | 1         | 1.27%   |
| Excavator     | 1         | 1.27%   |
| Unknown       | 1         | 1.27%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 46        | 55.42%  |
| AMD                              | 19        | 22.89%  |
| Nvidia                           | 17        | 20.48%  |
| Silicon Integrated Systems [SiS] | 1         | 1.2%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 5         | 5.75%   |
| Intel HD Graphics 5500                                                                   | 4         | 4.6%    |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 4.6%    |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 3         | 3.45%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 3.45%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 3.45%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 3.45%   |
| Nvidia G96CGL [Quadro FX 580]                                                            | 2         | 2.3%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 2.3%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 2.3%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 2.3%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2         | 2.3%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 2.3%    |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 2         | 2.3%    |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1         | 1.15%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 1         | 1.15%   |
| Nvidia GP107M [GeForce MX150]                                                            | 1         | 1.15%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 1.15%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 1.15%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 1.15%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 1         | 1.15%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1         | 1.15%   |
| Nvidia GK106M [GeForce GTX 765M]                                                         | 1         | 1.15%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                                        | 1         | 1.15%   |
| Nvidia GF108M [GeForce GT 635M]                                                          | 1         | 1.15%   |
| Nvidia GA104 [GeForce RTX 3060 Ti]                                                       | 1         | 1.15%   |
| Nvidia C79 [GeForce 9400]                                                                | 1         | 1.15%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1         | 1.15%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 1.15%   |
| Intel UHD Graphics 620                                                                   | 1         | 1.15%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 1.15%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 1.15%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1         | 1.15%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 1         | 1.15%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 1.15%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                                | 1         | 1.15%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.15%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.15%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1         | 1.15%   |
| Intel 82852/855GM Integrated Graphics Device                                             | 1         | 1.15%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 1.15%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 1         | 1.15%   |
| AMD Wrestler [Radeon HD 7340]                                                            | 1         | 1.15%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 1         | 1.15%   |
| AMD Trinity 2 [Radeon HD 7520G]                                                          | 1         | 1.15%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1         | 1.15%   |
| AMD RV380/M24 [Mobility Radeon X600]                                                     | 1         | 1.15%   |
| AMD RV350/M10 GL [Mobility FireGL T2]                                                    | 1         | 1.15%   |
| AMD RV350 [Radeon 9550] (Secondary)                                                      | 1         | 1.15%   |
| AMD RV350 [Radeon 9550]                                                                  | 1         | 1.15%   |
| AMD RV100 [Radeon 7000 / Radeon VE]                                                      | 1         | 1.15%   |
| AMD RS780L [Radeon 3000]                                                                 | 1         | 1.15%   |
| AMD R520/M58 [Mobility Radeon X1800]                                                     | 1         | 1.15%   |
| AMD R350 [Radeon 9800 Series]                                                            | 1         | 1.15%   |
| AMD R350 [Radeon 9800 PRO] (Secondary)                                                   | 1         | 1.15%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1         | 1.15%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 1         | 1.15%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 1         | 1.15%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 1         | 1.15%   |
| AMD Curacao XT / Trinidad XT [Radeon R7 370 / R9 270X/370X]                              | 1         | 1.15%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 38        | 48.1%   |
| 1 x AMD        | 17        | 21.52%  |
| 1 x Nvidia     | 13        | 16.46%  |
| Intel + Nvidia | 4         | 5.06%   |
| Other          | 3         | 3.8%    |
| 2 x Intel      | 1         | 1.27%   |
| 2 x AMD        | 1         | 1.27%   |
| 1 x SiS        | 1         | 1.27%   |
| Intel + AMD    | 1         | 1.27%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 66        | 82.5%   |
| Proprietary | 9         | 11.25%  |
| Unknown     | 5         | 6.25%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 48        | 60%     |
| 0.01-0.5   | 12        | 15%     |
| 3.01-4.0   | 5         | 6.25%   |
| 0.51-1.0   | 5         | 6.25%   |
| 1.01-2.0   | 4         | 5%      |
| 2.01-3.0   | 3         | 3.75%   |
| 7.01-8.0   | 2         | 2.5%    |
| 5.01-6.0   | 1         | 1.25%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 15        | 18.07%  |
| LG Display              | 12        | 14.46%  |
| AU Optronics            | 7         | 8.43%   |
| Goldstar                | 6         | 7.23%   |
| Lenovo                  | 4         | 4.82%   |
| Hewlett-Packard         | 4         | 4.82%   |
| Chimei Innolux          | 4         | 4.82%   |
| AOC                     | 4         | 4.82%   |
| Philips                 | 3         | 3.61%   |
| Acer                    | 3         | 3.61%   |
| PANDA                   | 2         | 2.41%   |
| Iiyama                  | 2         | 2.41%   |
| Dell                    | 2         | 2.41%   |
| Chi Mei Optoelectronics | 2         | 2.41%   |
| BOE                     | 2         | 2.41%   |
| ViewSonic               | 1         | 1.2%    |
| Toshiba                 | 1         | 1.2%    |
| STD                     | 1         | 1.2%    |
| MStar                   | 1         | 1.2%    |
| InnoLux Display         | 1         | 1.2%    |
| HJW                     | 1         | 1.2%    |
| Hisense                 | 1         | 1.2%    |
| eMachines               | 1         | 1.2%    |
| Eizo                    | 1         | 1.2%    |
| CVT                     | 1         | 1.2%    |
| Ancor Communications    | 1         | 1.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SyncMaster SAM0091 1600x1200 432x324mm 21.3-inch   | 2         | 2.3%    |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch            | 2         | 2.3%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 2         | 2.3%    |
| ViewSonic VA2261 Series VSC0F30 1920x1080 477x268mm 21.5-inch          | 1         | 1.15%   |
| Toshiba TV TSB0209 1920x1080 1594x900mm 72.1-inch                      | 1         | 1.15%   |
| STD HDMI TV STD00C7 1920x1080 698x392mm 31.5-inch                      | 1         | 1.15%   |
| Samsung Electronics T24B301 SAM098E 1920x1080 520x290mm 23.4-inch      | 1         | 1.15%   |
| Samsung Electronics SyncMaster SAM0226 1440x900 410x257mm 19.1-inch    | 1         | 1.15%   |
| Samsung Electronics SyncMaster SAM0029 1280x1024 312x234mm 15.4-inch   | 1         | 1.15%   |
| Samsung Electronics S24D340 SAM0BBB 1920x1080 530x300mm 24.0-inch      | 1         | 1.15%   |
| Samsung Electronics S/T 77/76BDF STN0007 1280x1024 312x234mm 15.4-inch | 1         | 1.15%   |
| Samsung Electronics LCD Monitor SyncMaster 1280x1024                   | 1         | 1.15%   |
| Samsung Electronics LCD Monitor SyncMaster                             | 1         | 1.15%   |
| Samsung Electronics LCD Monitor SEC4545 1280x800 331x207mm 15.4-inch   | 1         | 1.15%   |
| Samsung Electronics LCD Monitor SEC4151 1366x768 344x194mm 15.5-inch   | 1         | 1.15%   |
| Samsung Electronics LCD Monitor SDC4851 1366x768 344x194mm 15.5-inch   | 1         | 1.15%   |
| Samsung Electronics LCD Monitor SDC3853 2736x1824 260x173mm 12.3-inch  | 1         | 1.15%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 890x500mm 40.2-inch  | 1         | 1.15%   |
| Samsung Electronics LCD Monitor SA300/350/360                          | 1         | 1.15%   |
| Samsung Electronics LCD Monitor S24D340                                | 1         | 1.15%   |
| Samsung Electronics LCD Monitor C27F390 5760x1080                      | 1         | 1.15%   |
| Samsung Electronics C27F398 SAM0D45 1920x1080 598x336mm 27.0-inch      | 1         | 1.15%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                | 1         | 1.15%   |
| Philips 190B PHL086C 1280x1024 376x301mm 19.0-inch                     | 1         | 1.15%   |
| Philips 17S PHL0877 1280x1024 337x270mm 17.0-inch                      | 1         | 1.15%   |
| PANDA LM133LF5L01 NCP0020 1920x1080 294x165mm 13.3-inch                | 1         | 1.15%   |
| PANDA LCD Monitor NCP002E 1920x1080 344x194mm 15.5-inch                | 1         | 1.15%   |
| MStar Demo MST0030 1920x540 1150x650mm 52.0-inch                       | 1         | 1.15%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch          | 1         | 1.15%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch           | 1         | 1.15%   |
| LG Display LCD Monitor LGD0582 3000x2000 275x183mm 13.0-inch           | 1         | 1.15%   |
| LG Display LCD Monitor LGD0540 1920x1080 344x194mm 15.5-inch           | 1         | 1.15%   |
| LG Display LCD Monitor LGD047B 1366x768 344x194mm 15.5-inch            | 1         | 1.15%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch           | 1         | 1.15%   |
| LG Display LCD Monitor LGD0450 1366x768 277x156mm 12.5-inch            | 1         | 1.15%   |
| LG Display LCD Monitor LGD03A3 1366x768 277x156mm 12.5-inch            | 1         | 1.15%   |
| LG Display LCD Monitor LGD0386 1366x768 309x174mm 14.0-inch            | 1         | 1.15%   |
| LG Display LCD Monitor LGD02C0 1366x768 293x165mm 13.2-inch            | 1         | 1.15%   |
| Lenovo LI2215sD LEN65CC 1920x1080 476x267mm 21.5-inch                  | 1         | 1.15%   |
| Lenovo LCD Monitor LEN40A0 1366x768 309x174mm 14.0-inch                | 1         | 1.15%   |
| Lenovo LCD Monitor LEN4010 1280x800 261x163mm 12.1-inch                | 1         | 1.15%   |
| Lenovo LCD Monitor LEN4000 1024x768 246x185mm 12.1-inch                | 1         | 1.15%   |
| InnoLux Display LCD Monitor INL000A 1366x768 344x194mm 15.5-inch       | 1         | 1.15%   |
| Iiyama PLX2483H IVM6114 1920x1080 531x299mm 24.0-inch                  | 1         | 1.15%   |
| Iiyama PLB2712HDS IVM6602 1920x1080 598x336mm 27.0-inch                | 1         | 1.15%   |
| HJW HDMI TO USB HJW0001 1920x1080 700x390mm 31.5-inch                  | 1         | 1.15%   |
| Hisense Hisense HSE4000 1920x1080 591x355mm 27.1-inch                  | 1         | 1.15%   |
| Hewlett-Packard LA2206 HWP2947 1920x1080 476x268mm 21.5-inch           | 1         | 1.15%   |
| Hewlett-Packard L2245w HWP26FC 1680x1050 470x300mm 22.0-inch           | 1         | 1.15%   |
| Hewlett-Packard Compaq S2321a HWP2915 1920x1080 509x286mm 23.0-inch    | 1         | 1.15%   |
| Hewlett-Packard 24y HPN3504 1920x1080 528x297mm 23.9-inch              | 1         | 1.15%   |
| Hewlett-Packard 22cwa HWP3183 1920x1080 476x268mm 21.5-inch            | 1         | 1.15%   |
| Goldstar W2243 GSM56FF 1920x1080 477x268mm 21.5-inch                   | 1         | 1.15%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                | 1         | 1.15%   |
| Goldstar L1730S GSM438D 1280x1024 338x270mm 17.0-inch                  | 1         | 1.15%   |
| Goldstar E2260 GSM57E0 1920x1080 477x268mm 21.5-inch                   | 1         | 1.15%   |
| eMachines E19T6W EMA0783 1440x900 410x260mm 19.1-inch                  | 1         | 1.15%   |
| Eizo EV2456 ENC2798 1920x1200 520x330mm 24.2-inch                      | 1         | 1.15%   |
| Dell P2415Q DELA0BE 3840x2160 527x296mm 23.8-inch                      | 1         | 1.15%   |
| Dell LCD Monitor P1914S 1280x1024                                      | 1         | 1.15%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 30        | 36.59%  |
| 1366x768 (WXGA)    | 23        | 28.05%  |
| 3840x2160 (4K)     | 7         | 8.54%   |
| 1280x1024 (SXGA)   | 5         | 6.1%    |
| 1440x900 (WXGA+)   | 4         | 4.88%   |
| 1600x900 (HD+)     | 2         | 2.44%   |
| 1600x1200          | 2         | 2.44%   |
| 1280x800 (WXGA)    | 2         | 2.44%   |
| Unknown            | 2         | 2.44%   |
| 5760x1080          | 1         | 1.22%   |
| 3000x2000          | 1         | 1.22%   |
| 2736x1824          | 1         | 1.22%   |
| 1920x1200 (WUXGA)  | 1         | 1.22%   |
| 1680x1050 (WSXGA+) | 1         | 1.22%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 19        | 23.46%  |
| 21      | 13        | 16.05%  |
| 12      | 7         | 8.64%   |
| 24      | 5         | 6.17%   |
| 14      | 5         | 6.17%   |
| 13      | 5         | 6.17%   |
| 27      | 4         | 4.94%   |
| 23      | 4         | 4.94%   |
| 31      | 3         | 3.7%    |
| 19      | 3         | 3.7%    |
| 18      | 3         | 3.7%    |
| 17      | 3         | 3.7%    |
| Unknown | 2         | 2.47%   |
| 72      | 1         | 1.23%   |
| 54      | 1         | 1.23%   |
| 52      | 1         | 1.23%   |
| 22      | 1         | 1.23%   |
| 11      | 1         | 1.23%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 25        | 32.05%  |
| 401-500     | 16        | 20.51%  |
| 501-600     | 13        | 16.67%  |
| 201-300     | 13        | 16.67%  |
| 601-700     | 3         | 3.85%   |
| 351-400     | 3         | 3.85%   |
| 1001-1500   | 2         | 2.56%   |
| Unknown     | 2         | 2.56%   |
| 1501-2000   | 1         | 1.28%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 52        | 72.22%  |
| 16/10   | 8         | 11.11%  |
| 4/3     | 4         | 5.56%   |
| 5/4     | 3         | 4.17%   |
| 3/2     | 2         | 2.78%   |
| Unknown | 2         | 2.78%   |
| 6/5     | 1         | 1.39%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 18        | 22.5%   |
| 101-110        | 17        | 21.25%  |
| 61-70          | 7         | 8.75%   |
| 151-200        | 7         | 8.75%   |
| 81-90          | 5         | 6.25%   |
| 71-80          | 5         | 6.25%   |
| 301-350        | 4         | 5%      |
| 141-150        | 4         | 5%      |
| More than 1000 | 3         | 3.75%   |
| 351-500        | 3         | 3.75%   |
| 111-120        | 2         | 2.5%    |
| Unknown        | 2         | 2.5%    |
| 51-60          | 1         | 1.25%   |
| 251-300        | 1         | 1.25%   |
| 131-140        | 1         | 1.25%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 27        | 34.18%  |
| 51-100        | 27        | 34.18%  |
| 121-160       | 14        | 17.72%  |
| 161-240       | 4         | 5.06%   |
| 1-50          | 3         | 3.8%    |
| More than 240 | 2         | 2.53%   |
| Unknown       | 2         | 2.53%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 62        | 76.54%  |
| 2     | 11        | 13.58%  |
| 3     | 4         | 4.94%   |
| 0     | 4         | 4.94%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 39        | 33.62%  |
| Intel                            | 35        | 30.17%  |
| Qualcomm Atheros                 | 18        | 15.52%  |
| Ralink Technology                | 3         | 2.59%   |
| Marvell Technology Group         | 3         | 2.59%   |
| TP-Link                          | 2         | 1.72%   |
| Sierra Wireless                  | 2         | 1.72%   |
| NetGear                          | 2         | 1.72%   |
| JMicron Technology               | 2         | 1.72%   |
| Broadcom Limited                 | 2         | 1.72%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.86%   |
| VIA Technologies                 | 1         | 0.86%   |
| Silicon Integrated Systems [SiS] | 1         | 0.86%   |
| Samsung Electronics              | 1         | 0.86%   |
| Ralink                           | 1         | 0.86%   |
| Nvidia                           | 1         | 0.86%   |
| MEDIATEK                         | 1         | 0.86%   |
| Broadcom                         | 1         | 0.86%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 29        | 21.97%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 7         | 5.3%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 4         | 3.03%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 3.03%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 2.27%   |
| Intel Wireless 7265                                                     | 3         | 2.27%   |
| Intel Wireless 7260                                                     | 3         | 2.27%   |
| Intel Ethernet Connection (3) I218-LM                                   | 3         | 2.27%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 2.27%   |
| Sierra Wireless EM7455                                                  | 2         | 1.52%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.52%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 2         | 1.52%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 2         | 1.52%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.52%   |
| NetGear WG111v3 54 Mbps Wireless [realtek RTL8187B]                     | 2         | 1.52%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 2         | 1.52%   |
| Intel Ethernet Connection (7) I219-LM                                   | 2         | 1.52%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 1.52%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller       | 2         | 1.52%   |
| ZTE WCDMA MSM ZTE Mobile Broadband Station                              | 1         | 0.76%   |
| VIA VT6105/VT6106S [Rhine-III]                                          | 1         | 0.76%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]         | 1         | 0.76%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 0.76%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 1         | 0.76%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 1         | 0.76%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.76%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                         | 1         | 0.76%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 1         | 0.76%   |
| Ralink RT5372 Wireless Adapter                                          | 1         | 0.76%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 0.76%   |
| Ralink MT7601U Wireless Adapter                                         | 1         | 0.76%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.76%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 0.76%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 1         | 0.76%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.76%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.76%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 0.76%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 1         | 0.76%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                              | 1         | 0.76%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 1         | 0.76%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter              | 1         | 0.76%   |
| Nvidia MCP79 Ethernet                                                   | 1         | 0.76%   |
| MEDIATEK MT7630e 802.11bgn Wireless Network Adapter                     | 1         | 0.76%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                       | 1         | 0.76%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                 | 1         | 0.76%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                       | 1         | 0.76%   |
| Intel Wireless 8265 / 8275                                              | 1         | 0.76%   |
| Intel Wireless 8260                                                     | 1         | 0.76%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 0.76%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 1         | 0.76%   |
| Intel Ethernet Connection I354 2.5 GbE Backplane                        | 1         | 0.76%   |
| Intel Ethernet Connection I217-LM                                       | 1         | 0.76%   |
| Intel Ethernet Connection (7) I219-V                                    | 1         | 0.76%   |
| Intel Ethernet Connection (6) I219-V                                    | 1         | 0.76%   |
| Intel Ethernet Connection (14) I219-V                                   | 1         | 0.76%   |
| Intel Ethernet Connection (11) I219-V                                   | 1         | 0.76%   |
| Intel Ethernet Connection (10) I219-LM                                  | 1         | 0.76%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 0.76%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 0.76%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller        | 1         | 0.76%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 17        | 34%     |
| Qualcomm Atheros         | 16        | 32%     |
| Realtek Semiconductor    | 3         | 6%      |
| Ralink Technology        | 3         | 6%      |
| Sierra Wireless          | 2         | 4%      |
| NetGear                  | 2         | 4%      |
| Broadcom Limited         | 2         | 4%      |
| TP-Link                  | 1         | 2%      |
| Ralink                   | 1         | 2%      |
| MEDIATEK                 | 1         | 2%      |
| Marvell Technology Group | 1         | 2%      |
| Broadcom                 | 1         | 2%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 8%      |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 6%      |
| Intel Wireless 7265                                                     | 3         | 6%      |
| Intel Wireless 7260                                                     | 3         | 6%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 6%      |
| Sierra Wireless EM7455                                                  | 2         | 4%      |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 4%      |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 2         | 4%      |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 4%      |
| NetGear WG111v3 54 Mbps Wireless [realtek RTL8187B]                     | 2         | 4%      |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 4%      |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 2%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 2%      |
| Ralink RT5372 Wireless Adapter                                          | 1         | 2%      |
| Ralink RT5370 Wireless Adapter                                          | 1         | 2%      |
| Ralink MT7601U Wireless Adapter                                         | 1         | 2%      |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 2%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 2%      |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 2%      |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 2%      |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 2%      |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter              | 1         | 2%      |
| MEDIATEK MT7630e 802.11bgn Wireless Network Adapter                     | 1         | 2%      |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                       | 1         | 2%      |
| Intel Wireless 8265 / 8275                                              | 1         | 2%      |
| Intel Wireless 8260                                                     | 1         | 2%      |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 2%      |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 1         | 2%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 2%      |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 2%      |
| Broadcom Limited BCM4321 802.11a/b/g/n                                  | 1         | 2%      |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 1         | 2%      |
| Broadcom BCM43228 802.11a/b/g/n                                         | 1         | 2%      |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 37        | 48.05%  |
| Intel                            | 27        | 35.06%  |
| Qualcomm Atheros                 | 4         | 5.19%   |
| Marvell Technology Group         | 2         | 2.6%    |
| JMicron Technology               | 2         | 2.6%    |
| VIA Technologies                 | 1         | 1.3%    |
| TP-Link                          | 1         | 1.3%    |
| Silicon Integrated Systems [SiS] | 1         | 1.3%    |
| Samsung Electronics              | 1         | 1.3%    |
| Nvidia                           | 1         | 1.3%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 29        | 37.18%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 8.97%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 5.13%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 3.85%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 2.56%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 2         | 2.56%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 2.56%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1         | 1.28%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 1.28%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 1.28%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.28%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 1.28%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.28%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.28%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.28%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 1.28%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.28%   |
| Nvidia MCP79 Ethernet                                             | 1         | 1.28%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 1.28%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1         | 1.28%   |
| Intel Ethernet Connection I354 2.5 GbE Backplane                  | 1         | 1.28%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.28%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.28%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.28%   |
| Intel Ethernet Connection (14) I219-V                             | 1         | 1.28%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 1.28%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 1.28%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 1.28%   |
| Intel 82578DM Gigabit Network Connection                          | 1         | 1.28%   |
| Intel 82576 Gigabit Network Connection                            | 1         | 1.28%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 1.28%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 1.28%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)        | 1         | 1.28%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.28%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1         | 1.28%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                | 1         | 1.28%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 71        | 58.2%   |
| WiFi     | 47        | 38.52%  |
| Modem    | 4         | 3.28%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 50        | 58.14%  |
| WiFi     | 35        | 40.7%   |
| Modem    | 1         | 1.16%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 42        | 52.5%   |
| 1     | 32        | 40%     |
| 0     | 4         | 5%      |
| 5     | 1         | 1.25%   |
| 3     | 1         | 1.25%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 74        | 93.67%  |
| Yes  | 5         | 6.33%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 11        | 40.74%  |
| Qualcomm Atheros Communications | 4         | 14.81%  |
| Broadcom                        | 3         | 11.11%  |
| Cambridge Silicon Radio         | 2         | 7.41%   |
| Realtek Semiconductor           | 1         | 3.7%    |
| Ralink                          | 1         | 3.7%    |
| Marvell Semiconductor           | 1         | 3.7%    |
| Lite-On Technology              | 1         | 3.7%    |
| IMC Networks                    | 1         | 3.7%    |
| Foxconn / Hon Hai               | 1         | 3.7%    |
| Apple                           | 1         | 3.7%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 7         | 25.93%  |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 7.41%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 7.41%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 7.41%   |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 7.41%   |
| Realtek Bluetooth Radio                             | 1         | 3.7%    |
| Ralink RT3290 Bluetooth                             | 1         | 3.7%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 3.7%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 3.7%    |
| Marvell Bluetooth and Wireless LAN Composite        | 1         | 3.7%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 3.7%    |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 3.7%    |
| Intel AX201 Bluetooth                               | 1         | 3.7%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 3.7%    |
| Foxconn / Hon Hai BT                                | 1         | 3.7%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 3.7%    |
| Apple Bluetooth USB Host Controller                 | 1         | 3.7%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 60        | 57.14%  |
| AMD                              | 16        | 15.24%  |
| Nvidia                           | 13        | 12.38%  |
| Plantronics                      | 2         | 1.9%    |
| Creative Labs                    | 2         | 1.9%    |
| Texas Instruments                | 1         | 0.95%   |
| TEAC                             | 1         | 0.95%   |
| Silicon Integrated Systems [SiS] | 1         | 0.95%   |
| Realtek Semiconductor            | 1         | 0.95%   |
| M-Audio                          | 1         | 0.95%   |
| Logitech                         | 1         | 0.95%   |
| KORG                             | 1         | 0.95%   |
| GYROCOM C&C                      | 1         | 0.95%   |
| Elite Silicon                    | 1         | 0.95%   |
| Cirrus Logic                     | 1         | 0.95%   |
| C-Media Electronics              | 1         | 0.95%   |
| Blue Microphones                 | 1         | 0.95%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7         | 5.69%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6         | 4.88%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5         | 4.07%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5         | 4.07%   |
| Nvidia GP106 High Definition Audio Controller                              | 4         | 3.25%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 3.25%   |
| Intel Cannon Lake PCH cAVS                                                 | 4         | 3.25%   |
| Intel Broadwell-U Audio Controller                                         | 4         | 3.25%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 3.25%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4         | 3.25%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3         | 2.44%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 2.44%   |
| Intel Sunrise Point-LP HD Audio                                            | 3         | 2.44%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 2.44%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 3         | 2.44%   |
| AMD FCH Azalia Controller                                                  | 3         | 2.44%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 3         | 2.44%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 3         | 2.44%   |
| Plantronics HD1                                                            | 2         | 1.63%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 1.63%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.63%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 1.63%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 2         | 1.63%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 1.63%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]  | 2         | 1.63%   |
| AMD Starship/Matisse HD Audio Controller                                   | 2         | 1.63%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 2         | 1.63%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1         | 0.81%   |
| TEAC US-1800                                                               | 1         | 0.81%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 1         | 0.81%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.81%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 0.81%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.81%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.81%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1         | 0.81%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 0.81%   |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 0.81%   |
| M-Audio MIDISPORT 4x4 Anniv                                                | 1         | 0.81%   |
| M-Audio M-Audio 1x1                                                        | 1         | 0.81%   |
| Logitech USB Headset                                                       | 1         | 0.81%   |
| KORG nanoKONTROL studio controller                                         | 1         | 0.81%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 0.81%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 0.81%   |
| Intel Audio device                                                         | 1         | 0.81%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller           | 1         | 0.81%   |
| Intel 82801BA/BAM AC'97 Audio Controller                                   | 1         | 0.81%   |
| Intel 200 Series PCH HD Audio                                              | 1         | 0.81%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 0.81%   |
| GYROCOM C&C Fiio E10                                                       | 1         | 0.81%   |
| Elite Silicon USB Audio Device                                             | 1         | 0.81%   |
| Cirrus Logic Crystal CS4281 PCI Audio                                      | 1         | 0.81%   |
| C-Media Electronics CM106 Like Sound Device                                | 1         | 0.81%   |
| Blue Microphones Yeti Stereo Microphone                                    | 1         | 0.81%   |
| AMD Wrestler HDMI Audio                                                    | 1         | 0.81%   |
| AMD Trinity HDMI Audio Controller                                          | 1         | 0.81%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 0.81%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1         | 0.81%   |
| AMD High Definition Audio Controller                                       | 1         | 0.81%   |
| AMD Family 17h/19h HD Audio Controller                                     | 1         | 0.81%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1         | 0.81%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 18        | 22.5%   |
| Samsung Electronics | 15        | 18.75%  |
| Kingston            | 12        | 15%     |
| SK Hynix            | 7         | 8.75%   |
| Corsair             | 5         | 6.25%   |
| Micron Technology   | 4         | 5%      |
| G.Skill             | 4         | 5%      |
| Crucial             | 4         | 5%      |
| Nanya Technology    | 3         | 3.75%   |
| A-DATA Technology   | 3         | 3.75%   |
| Unknown (ABCD)      | 1         | 1.25%   |
| Smart               | 1         | 1.25%   |
| GOODRAM             | 1         | 1.25%   |
| Avant               | 1         | 1.25%   |
| Apacer              | 1         | 1.25%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB SODIMM DDR2                               | 2         | 2.2%    |
| Unknown RAM Module 1024MB SODIMM DDR                                | 2         | 2.2%    |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 2         | 2.2%    |
| Samsung RAM M471A1K43DB1-CTD 8192MB SODIMM DDR4 2667MT/s            | 2         | 2.2%    |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s               | 2         | 2.2%    |
| Corsair RAM CMK32GX4M4A2666C16 8192MB DIMM 2667MT/s                 | 2         | 2.2%    |
| Unknown RAM SM3S320SD0488CABC 8192MB SODIMM DDR3 1600MT/s           | 1         | 1.1%    |
| Unknown RAM Module 8192MB DIMM DDR3 800MT/s                         | 1         | 1.1%    |
| Unknown RAM Module 64MB DIMM DRAM 100MT/s                           | 1         | 1.1%    |
| Unknown RAM Module 512MB SODIMM DDR                                 | 1         | 1.1%    |
| Unknown RAM Module 4GB DIMM 1333MT/s                                | 1         | 1.1%    |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                      | 1         | 1.1%    |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                        | 1         | 1.1%    |
| Unknown RAM Module 2GB DIMM 1333MT/s                                | 1         | 1.1%    |
| Unknown RAM Module 256MB DIMM DRAM 100MT/s                          | 1         | 1.1%    |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                       | 1         | 1.1%    |
| Unknown RAM Module 2048MB SODIMM 800MT/s                            | 1         | 1.1%    |
| Unknown RAM Module 2048MB DIMM SDRAM 667MT/s                        | 1         | 1.1%    |
| Unknown RAM Module 2048MB DIMM SDRAM                                | 1         | 1.1%    |
| Unknown RAM Module 128MB DIMM DRAM 100MT/s                          | 1         | 1.1%    |
| Unknown RAM Module 1024MB SODIMM DDR2                               | 1         | 1.1%    |
| Unknown RAM Module 1024MB DIMM DDR 400MT/s                          | 1         | 1.1%    |
| Unknown RAM Module 1024MB DIMM DDR                                  | 1         | 1.1%    |
| Unknown RAM BRAN51288G16C1600L 8GB DIMM DDR3 1600MT/s               | 1         | 1.1%    |
| Unknown RAM 3000 C16 Series 8192MB DIMM DDR4 2133MT/s               | 1         | 1.1%    |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 1         | 1.1%    |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s               | 1         | 1.1%    |
| Smart RAM SF564128CJ8NWMNSEG 4GB SODIMM DDR3 1600MT/s               | 1         | 1.1%    |
| SK Hynix RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s             | 1         | 1.1%    |
| SK Hynix RAM Module 4GB DIMM DDR3 1333MT/s                          | 1         | 1.1%    |
| SK Hynix RAM Module 4096MB DIMM DDR3 1066MT/s                       | 1         | 1.1%    |
| SK Hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s             | 1         | 1.1%    |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.1%    |
| SK Hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s              | 1         | 1.1%    |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 1         | 1.1%    |
| Samsung RAM Module 2GB DIMM DDR3 1333MT/s                           | 1         | 1.1%    |
| Samsung RAM Module 2048MB Row Of Chips LPDDR3 1867MT/s              | 1         | 1.1%    |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s               | 1         | 1.1%    |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s               | 1         | 1.1%    |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s               | 1         | 1.1%    |
| Samsung RAM M471B5273EB0-CK0 4096MB SODIMM DDR3 4199MT/s            | 1         | 1.1%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 1.1%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 1.1%    |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s              | 1         | 1.1%    |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s               | 1         | 1.1%    |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s                 | 1         | 1.1%    |
| Samsung RAM K4EBE304EB-EGCG 8192MB Row Of Chips LPDDR3 2133MT/s     | 1         | 1.1%    |
| Nanya RAM NT2GC64B88B0NS-CG 2048MB SODIMM DDR3 1334MT/s             | 1         | 1.1%    |
| Nanya RAM Module 2GB DIMM DDR3 1333MT/s                             | 1         | 1.1%    |
| Nanya RAM M2X4G64CB8HG5N-DG 4GB DIMM DDR3 1867MT/s                  | 1         | 1.1%    |
| Micron RAM Module 2GB SODIMM DDR3 1067MT/s                          | 1         | 1.1%    |
| Micron RAM Module 2GB DIMM DDR3 1333MT/s                            | 1         | 1.1%    |
| Micron RAM DVM64453C DATARAM 8GB DIMM DDR3 1600MT/s                 | 1         | 1.1%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 1         | 1.1%    |
| Kingston RAM TSB1600D3S1ELD/4GE 4096MB SODIMM DDR3 1067MT/s         | 1         | 1.1%    |
| Kingston RAM KHYXPX-MIE 8GB SODIMM DDR4 2667MT/s                    | 1         | 1.1%    |
| Kingston RAM KHX3200C16D4/16GX 16384MB DIMM DDR4 3600MT/s           | 1         | 1.1%    |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 2667MT/s                 | 1         | 1.1%    |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2400MT/s                   | 1         | 1.1%    |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s                 | 1         | 1.1%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 31        | 45.59%  |
| DDR4    | 19        | 27.94%  |
| SDRAM   | 4         | 5.88%   |
| DDR     | 4         | 5.88%   |
| LPDDR3  | 3         | 4.41%   |
| DDR2    | 3         | 4.41%   |
| Unknown | 2         | 2.94%   |
| LPDDR4  | 1         | 1.47%   |
| DRAM    | 1         | 1.47%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 34        | 50.75%  |
| DIMM         | 30        | 44.78%  |
| Row Of Chips | 3         | 4.48%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 25        | 31.25%  |
| 4096  | 20        | 25%     |
| 2048  | 17        | 21.25%  |
| 16384 | 7         | 8.75%   |
| 1024  | 5         | 6.25%   |
| 32768 | 2         | 2.5%    |
| 512   | 1         | 1.25%   |
| 256   | 1         | 1.25%   |
| 128   | 1         | 1.25%   |
| 64    | 1         | 1.25%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 16        | 22.22%  |
| 2667    | 11        | 15.28%  |
| 1333    | 8         | 11.11%  |
| 2400    | 6         | 8.33%   |
| Unknown | 6         | 8.33%   |
| 2133    | 4         | 5.56%   |
| 1067    | 4         | 5.56%   |
| 3600    | 3         | 4.17%   |
| 4199    | 2         | 2.78%   |
| 1867    | 2         | 2.78%   |
| 800     | 2         | 2.78%   |
| 667     | 2         | 2.78%   |
| 3200    | 1         | 1.39%   |
| 1800    | 1         | 1.39%   |
| 1334    | 1         | 1.39%   |
| 1066    | 1         | 1.39%   |
| 400     | 1         | 1.39%   |
| 100     | 1         | 1.39%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 2         | 50%     |
| Custom Engineering SPA | 1         | 25%     |
| Brother Industries     | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Computers | Percent |
|---------------------------------|-----------|---------|
| HP ENVY 5000 series             | 1         | 25%     |
| HP Deskjet 1050 J410            | 1         | 25%     |
| Custom Engineering SPA KUBE USB | 1         | 25%     |
| Brother HL-L2375DW series       | 1         | 25%     |

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 11        | 30.56%  |
| Acer                                   | 4         | 11.11%  |
| Sunplus Innovation Technology          | 3         | 8.33%   |
| Microdia                               | 3         | 8.33%   |
| Suyin                                  | 2         | 5.56%   |
| Logitech                               | 2         | 5.56%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 5.56%   |
| Z-Star Microelectronics                | 1         | 2.78%   |
| Softkinetic                            | 1         | 2.78%   |
| Samsung Electronics                    | 1         | 2.78%   |
| Mustek Systems                         | 1         | 2.78%   |
| MacroSilicon                           | 1         | 2.78%   |
| Lite-On Technology                     | 1         | 2.78%   |
| IMC Networks                           | 1         | 2.78%   |
| GEMBIRD                                | 1         | 2.78%   |
| Cubeternet                             | 1         | 2.78%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 5         | 13.89%  |
| Sunplus Integrated_Webcam_HD                     | 2         | 5.56%   |
| Acer BisonCam, NB Pro                            | 2         | 5.56%   |
| Z-Star Vimicro USB2.0 Camera                     | 1         | 2.78%   |
| Suyin Acer/Lenovo Webcam [CN0316]                | 1         | 2.78%   |
| Suyin Acer/HP Integrated Webcam [CN0314]         | 1         | 2.78%   |
| Sunplus Asus Webcam                              | 1         | 2.78%   |
| Softkinetic DepthSense 325                       | 1         | 2.78%   |
| Samsung Galaxy series, misc. (MTP mode)          | 1         | 2.78%   |
| Mustek Systems USB 2.0 PC Camera                 | 1         | 2.78%   |
| Microdia WebCam SC-13HDL12639P                   | 1         | 2.78%   |
| Microdia Camera                                  | 1         | 2.78%   |
| Microdia 1.3 MPixel Integrated Webcam            | 1         | 2.78%   |
| MacroSilicon MiraBox Capture                     | 1         | 2.78%   |
| Logitech Webcam C270                             | 1         | 2.78%   |
| Logitech HD Pro Webcam C920                      | 1         | 2.78%   |
| Lite-On HP Wide Vision HD Camera                 | 1         | 2.78%   |
| IMC Networks Integrated Webcam                   | 1         | 2.78%   |
| GEMBIRD USB2.0 PC CAMERA                         | 1         | 2.78%   |
| Cubeternet GL-UPC822 UVC WebCam                  | 1         | 2.78%   |
| Chicony WebCam                                   | 1         | 2.78%   |
| Chicony VGA WebCam                               | 1         | 2.78%   |
| Chicony Lenovo Integrated Camera (0.3MP)         | 1         | 2.78%   |
| Chicony Lenovo EasyCamera                        | 1         | 2.78%   |
| Chicony EasyCamera                               | 1         | 2.78%   |
| Chicony CNF9055 Toshiba Webcam                   | 1         | 2.78%   |
| Cheng Uei Precision Industry (Foxlink) Webcam    | 1         | 2.78%   |
| Cheng Uei Precision Industry (Foxlink) FM13FF-82 | 1         | 2.78%   |
| Acer ThinkPad Integrated Camera                  | 1         | 2.78%   |
| Acer Integrated Camera                           | 1         | 2.78%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Upek               | 1         | 33.33%  |
| Synaptics          | 1         | 33.33%  |
| STMicroelectronics | 1         | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 33.33%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 33.33%  |
| STMicroelectronics Fingerprint Reader                  | 1         | 33.33%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 3         | 60%     |
| Lenovo      | 1         | 20%     |
| Alcor Micro | 1         | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Lenovo Integrated Smart Card Reader            | 1         | 20%     |
| Broadcom BCM5880 Secure Applications Processor | 1         | 20%     |
| Broadcom 5880                                  | 1         | 20%     |
| Broadcom 58200                                 | 1         | 20%     |
| Alcor Micro AU9540 Smartcard Reader            | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 63        | 77.78%  |
| 1     | 11        | 13.58%  |
| 2     | 5         | 6.17%   |
| 3     | 2         | 2.47%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 4         | 19.05%  |
| Fingerprint reader       | 3         | 14.29%  |
| Communication controller | 3         | 14.29%  |
| Chipcard                 | 3         | 14.29%  |
| Net/wireless             | 2         | 9.52%   |
| Multimedia controller    | 2         | 9.52%   |
| Bluetooth                | 2         | 9.52%   |
| Firewire controller      | 1         | 4.76%   |
| Camera                   | 1         | 4.76%   |

