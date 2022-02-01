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

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| Intel         | HURONRIVER                  | Notebook    | [49bdd1a99d](https://linux-hardware.org/?probe=49bdd1a99d) | Oct 29, 2020 |
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

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Computers | Percent |
|---------------------------|-----------|---------|
| 5.10.0-9-amd64            | 7         | 8.54%   |
| 5.10.0-8-amd64            | 7         | 8.54%   |
| 4.19.0-9-amd64            | 6         | 7.32%   |
| 4.19.0-14-amd64           | 6         | 7.32%   |
| 4.19.0-16-amd64           | 5         | 6.1%    |
| 5.7.0-2-amd64             | 3         | 3.66%   |
| 5.10.0-10-amd64           | 3         | 3.66%   |
| 4.19.0-12-amd64           | 3         | 3.66%   |
| 5.7.0-0.bpo.2-amd64       | 2         | 2.44%   |
| 5.15.0-2-amd64            | 2         | 2.44%   |
| 5.10.0-6-amd64            | 2         | 2.44%   |
| 4.19.0-17-amd64           | 2         | 2.44%   |
| 4.19.0-10-amd64           | 2         | 2.44%   |
| 5.9.0-4-amd64             | 1         | 1.22%   |
| 5.9.0-1-amd64             | 1         | 1.22%   |
| 5.8.0-3-amd64             | 1         | 1.22%   |
| 5.8.0-1-amd64             | 1         | 1.22%   |
| 5.7.19-server1            | 1         | 1.22%   |
| 5.7.0-1-amd64             | 1         | 1.22%   |
| 5.6.0-2-amd64             | 1         | 1.22%   |
| 5.15.5-xanmod1            | 1         | 1.22%   |
| 5.14.0-4-amd64            | 1         | 1.22%   |
| 5.11.0-6.2-liquorix-amd64 | 1         | 1.22%   |
| 5.10.0-7-amd64            | 1         | 1.22%   |
| 5.10.0-5-amd64            | 1         | 1.22%   |
| 5.10.0-4-amd64            | 1         | 1.22%   |
| 5.10.0-2-amd64            | 1         | 1.22%   |
| 5.10.0-1-amd64            | 1         | 1.22%   |
| 5.1.21                    | 1         | 1.22%   |
| 5.0.7                     | 1         | 1.22%   |
| 4.9.0-15-amd64            | 1         | 1.22%   |
| 4.9.0-14-amd64            | 1         | 1.22%   |
| 4.9.0-14-686-pae          | 1         | 1.22%   |
| 4.9.0-14-686              | 1         | 1.22%   |
| 4.9.0-11-amd64            | 1         | 1.22%   |
| 4.9.0-11-686-pae          | 1         | 1.22%   |
| 4.9.0-11-686              | 1         | 1.22%   |
| 4.9.0-0.bpo.4-686-pae     | 1         | 1.22%   |
| 4.4.195-antix.1-amd64-smp | 1         | 1.22%   |
| 4.19.112                  | 1         | 1.22%   |
| 4.19.0-17-686-pae         | 1         | 1.22%   |
| 4.19.0-13-amd64           | 1         | 1.22%   |
| 4.19.0-1-amd64            | 1         | 1.22%   |
| 4.19.0-0.bpo.6-amd64      | 1         | 1.22%   |
| 4.18.0-0.bpo.1-amd64      | 1         | 1.22%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 4.19.0   | 27        | 33.33%  |
| 5.10.0   | 24        | 29.63%  |
| 4.9.0    | 8         | 9.88%   |
| 5.7.0    | 6         | 7.41%   |
| 5.9.0    | 2         | 2.47%   |
| 5.8.0    | 2         | 2.47%   |
| 5.15.0   | 2         | 2.47%   |
| 5.7.19   | 1         | 1.23%   |
| 5.6.0    | 1         | 1.23%   |
| 5.15.5   | 1         | 1.23%   |
| 5.14.0   | 1         | 1.23%   |
| 5.11.0   | 1         | 1.23%   |
| 5.1.21   | 1         | 1.23%   |
| 5.0.7    | 1         | 1.23%   |
| 4.4.195  | 1         | 1.23%   |
| 4.19.112 | 1         | 1.23%   |
| 4.18.0   | 1         | 1.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.19    | 28        | 34.57%  |
| 5.10    | 24        | 29.63%  |
| 4.9     | 8         | 9.88%   |
| 5.7     | 7         | 8.64%   |
| 5.15    | 3         | 3.7%    |
| 5.9     | 2         | 2.47%   |
| 5.8     | 2         | 2.47%   |
| 5.6     | 1         | 1.23%   |
| 5.14    | 1         | 1.23%   |
| 5.11    | 1         | 1.23%   |
| 5.1     | 1         | 1.23%   |
| 5.0     | 1         | 1.23%   |
| 4.4     | 1         | 1.23%   |
| 4.18    | 1         | 1.23%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 68        | 90.67%  |
| i686   | 6         | 8%      |
| armv7l | 1         | 1.33%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| XFCE     | 31        | 39.74%  |
| KDE5     | 12        | 15.38%  |
| Unknown  | 12        | 15.38%  |
| MATE     | 9         | 11.54%  |
| LXDE     | 4         | 5.13%   |
| i3       | 4         | 5.13%   |
| LXQt     | 2         | 2.56%   |
| Openbox  | 1         | 1.28%   |
| GNOME    | 1         | 1.28%   |
| Cinnamon | 1         | 1.28%   |
| awesome  | 1         | 1.28%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 68        | 89.47%  |
| Tty     | 5         | 6.58%   |
| Unknown | 3         | 3.95%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SLiM    | 28        | 36.36%  |
| Unknown | 22        | 28.57%  |
| LightDM | 19        | 24.68%  |
| SDDM    | 4         | 5.19%   |
| XDM     | 2         | 2.6%    |
| NODM    | 1         | 1.3%    |
| GDM3    | 1         | 1.3%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 22        | 28.95%  |
| en_GB       | 14        | 18.42%  |
| ru_RU       | 7         | 9.21%   |
| Unknown     | 7         | 9.21%   |
| C           | 5         | 6.58%   |
| fr_FR       | 4         | 5.26%   |
| sk_SK       | 3         | 3.95%   |
| pt_BR       | 3         | 3.95%   |
| en_AU       | 2         | 2.63%   |
| pl_PL       | 1         | 1.32%   |
| it_IT       | 1         | 1.32%   |
| fr_BE       | 1         | 1.32%   |
| es_SV       | 1         | 1.32%   |
| es_ES       | 1         | 1.32%   |
| en_US.utf-8 | 1         | 1.32%   |
| en_NZ       | 1         | 1.32%   |
| en_CA       | 1         | 1.32%   |
| de_AT       | 1         | 1.32%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 52        | 68.42%  |
| EFI  | 24        | 31.58%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 61        | 81.33%  |
| Unknown | 5         | 6.67%   |
| Btrfs   | 4         | 5.33%   |
| Overlay | 2         | 2.67%   |
| OveXlay | 1         | 1.33%   |
| Ext3    | 1         | 1.33%   |
| Ext2    | 1         | 1.33%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| MBR     | 36        | 45.57%  |
| GPT     | 33        | 41.77%  |
| Unknown | 10        | 12.66%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 57        | 75%     |
| Yes       | 19        | 25%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 56        | 73.68%  |
| Yes       | 20        | 26.32%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 13        | 17.33%  |
| Gigabyte Technology | 10        | 13.33%  |
| ASUSTek Computer    | 10        | 13.33%  |
| Hewlett-Packard     | 6         | 8%      |
| Dell                | 5         | 6.67%   |
| ASRock              | 4         | 5.33%   |
| Acer                | 4         | 5.33%   |
| MSI                 | 3         | 4%      |
| Toshiba             | 2         | 2.67%   |
| Intel               | 2         | 2.67%   |
| Fujitsu Siemens     | 2         | 2.67%   |
| Teclast             | 1         | 1.33%   |
| Sun Microsystems    | 1         | 1.33%   |
| Samsung Electronics | 1         | 1.33%   |
| Online Labs         | 1         | 1.33%   |
| Notebook            | 1         | 1.33%   |
| Nokia               | 1         | 1.33%   |
| MTC                 | 1         | 1.33%   |
| Microsoft           | 1         | 1.33%   |
| IBM                 | 1         | 1.33%   |
| Google              | 1         | 1.33%   |
| Fujitsu             | 1         | 1.33%   |
| Chuwi               | 1         | 1.33%   |
| Apple               | 1         | 1.33%   |
| AMI                 | 1         | 1.33%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                                                     | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Toshiba Satellite M40X                                                                   | 1         | 1.33%   |
| Toshiba Satellite L655                                                                   | 1         | 1.33%   |
| Teclast F6 Plus                                                                          | 1         | 1.33%   |
| Sun Microsystems Ultra 24                                                                | 1         | 1.33%   |
| Samsung 355V4C/355V4X/355V5C/355V5X/356V4C/356V4X/356V5C/356V5X/3445VC/3445VX/3545VC/354 | 1         | 1.33%   |
| Online Labs SR                                                                           | 1         | 1.33%   |
| Notebook W230ST                                                                          | 1         | 1.33%   |
| Nokia N900                                                                               | 1         | 1.33%   |
| MTC Montara-GML                                                                          | 1         | 1.33%   |
| MSI MS-7B53                                                                              | 1         | 1.33%   |
| MSI MS-7A34                                                                              | 1         | 1.33%   |
| MSI MS-1688                                                                              | 1         | 1.33%   |
| Microsoft Surface Pro 4                                                                  | 1         | 1.33%   |
| Lenovo Yoga C640-13IML 81UE                                                              | 1         | 1.33%   |
| Lenovo ThinkStation E20 4220CTO                                                          | 1         | 1.33%   |
| Lenovo ThinkPad X60 1707YF8                                                              | 1         | 1.33%   |
| Lenovo ThinkPad X250 20CLS7WY04                                                          | 1         | 1.33%   |
| Lenovo ThinkPad X230 2325DE0                                                             | 1         | 1.33%   |
| Lenovo ThinkPad X230 23247S0                                                             | 1         | 1.33%   |
| Lenovo ThinkPad X220 429053G                                                             | 1         | 1.33%   |
| Lenovo ThinkPad X200 74585FU                                                             | 1         | 1.33%   |
| Lenovo ThinkPad X1 Carbon 7th 20QD00L1PB                                                 | 1         | 1.33%   |
| Lenovo ThinkPad T550 20CJS1VD01                                                          | 1         | 1.33%   |
| Lenovo ThinkPad T420 4180AG3                                                             | 1         | 1.33%   |
| Lenovo IdeaPad Z370                                                                      | 1         | 1.33%   |
| Lenovo IdeaPad 130-15AST 81H5                                                            | 1         | 1.33%   |
| Intel D815EEA AAA45884-401                                                               | 1         | 1.33%   |
| Intel AHV                                                                                | 1         | 1.33%   |
| IBM ThinkPad T41p 2373GHG                                                                | 1         | 1.33%   |
| HP Z220 SFF Workstation                                                                  | 1         | 1.33%   |
| HP ProBook 6475b                                                                         | 1         | 1.33%   |
| HP Pavilion x360 Convertible 14-dh1xxx                                                   | 1         | 1.33%   |
| HP Pavilion 11 x360 PC                                                                   | 1         | 1.33%   |
| HP EliteDesk 800 G1 DM                                                                   | 1         | 1.33%   |
| HP Compaq 8200 Elite SFF PC                                                              | 1         | 1.33%   |
| Google Panther                                                                           | 1         | 1.33%   |
| Gigabyte Z390 GAMING SLI                                                                 | 1         | 1.33%   |
| Gigabyte P55A-UD3                                                                        | 1         | 1.33%   |
| Gigabyte MZGLKBP-00                                                                      | 1         | 1.33%   |
| Gigabyte H310M S2H 2.0                                                                   | 1         | 1.33%   |
| Gigabyte H170-HD3-CF                                                                     | 1         | 1.33%   |
| Gigabyte H170-HD3                                                                        | 1         | 1.33%   |
| Gigabyte GA-G41M-ES2L                                                                    | 1         | 1.33%   |
| Gigabyte B75M-D3V                                                                        | 1         | 1.33%   |
| Gigabyte B450 AORUS ELITE                                                                | 1         | 1.33%   |
| Gigabyte 970A-DS3P                                                                       | 1         | 1.33%   |
| Fujitsu Siemens ESPRIMO Mobile V6535                                                     | 1         | 1.33%   |
| Fujitsu Siemens AMILO Xi 1546                                                            | 1         | 1.33%   |
| Fujitsu LIFEBOOK U7510                                                                   | 1         | 1.33%   |
| Dell Precision 7530                                                                      | 1         | 1.33%   |
| Dell OptiPlex 7010                                                                       | 1         | 1.33%   |
| Dell Latitude E7250                                                                      | 1         | 1.33%   |
| Dell Latitude 5501                                                                       | 1         | 1.33%   |
| Dell Inspiron 1564                                                                       | 1         | 1.33%   |
| Chuwi Hi10 pro tablet                                                                    | 1         | 1.33%   |
| ASUS X555LJ                                                                              | 1         | 1.33%   |
| ASUS PRIME Z490M-PLUS                                                                    | 1         | 1.33%   |
| ASUS P5PE-VM                                                                             | 1         | 1.33%   |
| ASUS P5G41T-M LX2/BR                                                                     | 1         | 1.33%   |
| ASUS Maximus V GENE                                                                      | 1         | 1.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 9         | 12%     |
| Acer Aspire             | 3         | 4%      |
| Toshiba Satellite       | 2         | 2.67%   |
| Lenovo IdeaPad          | 2         | 2.67%   |
| HP Pavilion             | 2         | 2.67%   |
| Dell Latitude           | 2         | 2.67%   |
| Teclast F6              | 1         | 1.33%   |
| Sun Microsystems Ultra  | 1         | 1.33%   |
| Samsung 355V4C          | 1         | 1.33%   |
| Online Labs SR          | 1         | 1.33%   |
| Notebook W230ST         | 1         | 1.33%   |
| Nokia N900              | 1         | 1.33%   |
| MTC Montara-GML         | 1         | 1.33%   |
| MSI MS-7B53             | 1         | 1.33%   |
| MSI MS-7A34             | 1         | 1.33%   |
| MSI MS-1688             | 1         | 1.33%   |
| Microsoft Surface       | 1         | 1.33%   |
| Lenovo Yoga             | 1         | 1.33%   |
| Lenovo ThinkStation     | 1         | 1.33%   |
| Intel D815EEA           | 1         | 1.33%   |
| Intel AHV               | 1         | 1.33%   |
| IBM ThinkPad            | 1         | 1.33%   |
| HP Z220                 | 1         | 1.33%   |
| HP ProBook              | 1         | 1.33%   |
| HP EliteDesk            | 1         | 1.33%   |
| HP Compaq               | 1         | 1.33%   |
| Google Panther          | 1         | 1.33%   |
| Gigabyte Z390           | 1         | 1.33%   |
| Gigabyte P55A-UD3       | 1         | 1.33%   |
| Gigabyte MZGLKBP-00     | 1         | 1.33%   |
| Gigabyte H310M          | 1         | 1.33%   |
| Gigabyte H170-HD3-CF    | 1         | 1.33%   |
| Gigabyte H170-HD3       | 1         | 1.33%   |
| Gigabyte GA-G41M-ES2L   | 1         | 1.33%   |
| Gigabyte B75M-D3V       | 1         | 1.33%   |
| Gigabyte B450           | 1         | 1.33%   |
| Gigabyte 970A-DS3P      | 1         | 1.33%   |
| Fujitsu Siemens ESPRIMO | 1         | 1.33%   |
| Fujitsu Siemens AMILO   | 1         | 1.33%   |
| Fujitsu LIFEBOOK        | 1         | 1.33%   |
| Dell Precision          | 1         | 1.33%   |
| Dell OptiPlex           | 1         | 1.33%   |
| Dell Inspiron           | 1         | 1.33%   |
| Chuwi Hi10              | 1         | 1.33%   |
| ASUS X555LJ             | 1         | 1.33%   |
| ASUS PRIME              | 1         | 1.33%   |
| ASUS P5PE-VM            | 1         | 1.33%   |
| ASUS P5G41T-M           | 1         | 1.33%   |
| ASUS Maximus            | 1         | 1.33%   |
| ASUS K55VJ              | 1         | 1.33%   |
| ASUS K52F               | 1         | 1.33%   |
| ASUS F1A55-M            | 1         | 1.33%   |
| ASUS EX-A320M-GAMING    | 1         | 1.33%   |
| ASUS All                | 1         | 1.33%   |
| ASRock K8A780LM         | 1         | 1.33%   |
| ASRock H81M-ITX         | 1         | 1.33%   |
| ASRock G31M-VS2         | 1         | 1.33%   |
| ASRock B450M-HDV        | 1         | 1.33%   |
| Apple Macmini3          | 1         | 1.33%   |
| AMI Aptio               | 1         | 1.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 11        | 14.67%  |
| 2012    | 8         | 10.67%  |
| 2019    | 7         | 9.33%   |
| 2011    | 7         | 9.33%   |
| 2015    | 6         | 8%      |
| 2014    | 5         | 6.67%   |
| 2009    | 5         | 6.67%   |
| 2013    | 4         | 5.33%   |
| 2008    | 4         | 5.33%   |
| 2010    | 3         | 4%      |
| 2006    | 3         | 4%      |
| 2020    | 2         | 2.67%   |
| 2017    | 2         | 2.67%   |
| 2016    | 2         | 2.67%   |
| 2007    | 2         | 2.67%   |
| 2005    | 2         | 2.67%   |
| 2000    | 1         | 1.33%   |
| Unknown | 1         | 1.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 36        | 48%     |
| Desktop     | 33        | 44%     |
| Tablet      | 2         | 2.67%   |
| Convertible | 2         | 2.67%   |
| Mini pc     | 2         | 2.67%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 75        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 72        | 96%     |
| Yes  | 3         | 4%      |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 16        | 21.33%  |
| 8.01-16.0   | 16        | 21.33%  |
| 3.01-4.0    | 13        | 17.33%  |
| 16.01-24.0  | 12        | 16%     |
| 32.01-64.0  | 6         | 8%      |
| 1.01-2.0    | 6         | 8%      |
| 0.01-0.5    | 3         | 4%      |
| 2.01-3.0    | 2         | 2.67%   |
| 64.01-256.0 | 1         | 1.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 25        | 31.25%  |
| 4.01-8.0   | 15        | 18.75%  |
| 2.01-3.0   | 14        | 17.5%   |
| 0.51-1.0   | 12        | 15%     |
| 3.01-4.0   | 6         | 7.5%    |
| 0.01-0.5   | 4         | 5%      |
| 8.01-16.0  | 3         | 3.75%   |
| 32.01-64.0 | 1         | 1.25%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 44        | 58.67%  |
| 2      | 14        | 18.67%  |
| 3      | 9         | 12%     |
| 4      | 5         | 6.67%   |
| 5      | 3         | 4%      |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 46        | 61.33%  |
| Yes       | 29        | 38.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 69        | 92%     |
| No        | 6         | 8%      |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 44        | 57.89%  |
| No        | 32        | 42.11%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 50        | 66.67%  |
| Yes       | 25        | 33.33%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Russia      | 9         | 12%     |
| France      | 8         | 10.67%  |
| Ukraine     | 6         | 8%      |
| USA         | 5         | 6.67%   |
| Brazil      | 5         | 6.67%   |
| Grenada     | 4         | 5.33%   |
| Germany     | 4         | 5.33%   |
| Slovakia    | 3         | 4%      |
| Poland      | 3         | 4%      |
| Netherlands | 3         | 4%      |
| Israel      | 2         | 2.67%   |
| Hungary     | 2         | 2.67%   |
| Australia   | 2         | 2.67%   |
| UK          | 1         | 1.33%   |
| Switzerland | 1         | 1.33%   |
| Spain       | 1         | 1.33%   |
| South Korea | 1         | 1.33%   |
| Puerto Rico | 1         | 1.33%   |
| Portugal    | 1         | 1.33%   |
| Norway      | 1         | 1.33%   |
| New Zealand | 1         | 1.33%   |
| Mexico      | 1         | 1.33%   |
| Italy       | 1         | 1.33%   |
| Indonesia   | 1         | 1.33%   |
| India       | 1         | 1.33%   |
| Greece      | 1         | 1.33%   |
| Finland     | 1         | 1.33%   |
| El Salvador | 1         | 1.33%   |
| Canada      | 1         | 1.33%   |
| Belgium     | 1         | 1.33%   |
| Austria     | 1         | 1.33%   |
| Argentina   | 1         | 1.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Bagnolet             | 4         | 5.26%   |
| Kyiv                 | 3         | 3.95%   |
| Gouyave              | 3         | 3.95%   |
| Bratislava           | 3         | 3.95%   |
| Wroclaw              | 2         | 2.63%   |
| Volzhskiy            | 2         | 2.63%   |
| Tel Aviv             | 2         | 2.63%   |
| São Paulo           | 2         | 2.63%   |
| Ryde                 | 2         | 2.63%   |
| Rio de Janeiro       | 2         | 2.63%   |
| Hillsborough         | 2         | 2.63%   |
| Budapest             | 2         | 2.63%   |
| Zeist                | 1         | 1.32%   |
| Yakutsk              | 1         | 1.32%   |
| Wageningen           | 1         | 1.32%   |
| Vologda              | 1         | 1.32%   |
| Toronto              | 1         | 1.32%   |
| Thrissur             | 1         | 1.32%   |
| Thessaloniki         | 1         | 1.32%   |
| Talavera de la Reina | 1         | 1.32%   |
| Syeverodonets'k      | 1         | 1.32%   |
| St Petersburg        | 1         | 1.32%   |
| Seongbuk-gu          | 1         | 1.32%   |
| Sao Vicente          | 1         | 1.32%   |
| San Salvador         | 1         | 1.32%   |
| Saint-Herblain       | 1         | 1.32%   |
| Poperinge            | 1         | 1.32%   |
| Paris                | 1         | 1.32%   |
| Oslo                 | 1         | 1.32%   |
| Oleksandriya         | 1         | 1.32%   |
| Nérac               | 1         | 1.32%   |
| Mozdok               | 1         | 1.32%   |
| Moscow               | 1         | 1.32%   |
| Milan                | 1         | 1.32%   |
| Miedziana Gora       | 1         | 1.32%   |
| Miami                | 1         | 1.32%   |
| Mglin                | 1         | 1.32%   |
| Lisbon               | 1         | 1.32%   |
| Leonding             | 1         | 1.32%   |
| Leipzig              | 1         | 1.32%   |
| Kirov                | 1         | 1.32%   |
| Jyväskylä          | 1         | 1.32%   |
| Hochheim am Main     | 1         | 1.32%   |
| Hermosillo           | 1         | 1.32%   |
| Hayden               | 1         | 1.32%   |
| Haiger               | 1         | 1.32%   |
| Great Bend           | 1         | 1.32%   |
| Forest Grove         | 1         | 1.32%   |
| Donetsk              | 1         | 1.32%   |
| Depok                | 1         | 1.32%   |
| Cologne              | 1         | 1.32%   |
| Coghlan              | 1         | 1.32%   |
| Château-Thierry     | 1         | 1.32%   |
| Caguas               | 1         | 1.32%   |
| Bradford             | 1         | 1.32%   |
| Auckland             | 1         | 1.32%   |
| Atlanta              | 1         | 1.32%   |
| Amsterdam            | 1         | 1.32%   |
| Aarburg              | 1         | 1.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 23        | 32     | 20.35%  |
| Seagate             | 15        | 23     | 13.27%  |
| Samsung Electronics | 9         | 15     | 7.96%   |
| Kingston            | 9         | 10     | 7.96%   |
| Unknown             | 6         | 8      | 5.31%   |
| Toshiba             | 5         | 5      | 4.42%   |
| Crucial             | 5         | 6      | 4.42%   |
| Hitachi             | 4         | 4      | 3.54%   |
| PNY                 | 3         | 3      | 2.65%   |
| Fujitsu             | 3         | 3      | 2.65%   |
| SK Hynix            | 2         | 2      | 1.77%   |
| Netac               | 2         | 2      | 1.77%   |
| HGST                | 2         | 2      | 1.77%   |
| Hewlett-Packard     | 2         | 3      | 1.77%   |
| DOGFISH             | 2         | 2      | 1.77%   |
| A-DATA Technology   | 2         | 2      | 1.77%   |
| WD MediaMax         | 1         | 1      | 0.88%   |
| Union Memory        | 1         | 2      | 0.88%   |
| Transcend           | 1         | 2      | 0.88%   |
| Teclast             | 1         | 1      | 0.88%   |
| Team                | 1         | 1      | 0.88%   |
| SMART               | 1         | 1      | 0.88%   |
| SanDisk             | 1         | 1      | 0.88%   |
| SABRENT             | 1         | 2      | 0.88%   |
| Patriot             | 1         | 1      | 0.88%   |
| Micron Technology   | 1         | 1      | 0.88%   |
| MAXTOR              | 1         | 1      | 0.88%   |
| LITEON              | 1         | 2      | 0.88%   |
| Kston               | 1         | 1      | 0.88%   |
| KIOXIA              | 1         | 1      | 0.88%   |
| KingFast            | 1         | 1      | 0.88%   |
| KingDian            | 1         | 1      | 0.88%   |
| Intel               | 1         | 1      | 0.88%   |
| IBM/Hitachi         | 1         | 1      | 0.88%   |
| GOODRAM             | 1         | 1      | 0.88%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| PNY CS900 240GB SSD                     | 3         | 2.36%   |
| Kingston SA2000M8250G 250GB             | 3         | 2.36%   |
| WDC WD5000BPVT-24HXZT3 500GB            | 2         | 1.57%   |
| WDC WD10EARX-00N0YB0 1TB                | 2         | 1.57%   |
| Seagate ST2000DX002-2DV164 2TB          | 2         | 1.57%   |
| Samsung SSD 860 EVO 250GB               | 2         | 1.57%   |
| Kingston SA400S37120G 120GB SSD         | 2         | 1.57%   |
| WDC WDS480G2G0A-00JH30 480GB SSD        | 1         | 0.79%   |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 1         | 0.79%   |
| WDC WDS120G2G0A-00JH30 120GB SSD        | 1         | 0.79%   |
| WDC WD800BB-00JHC0 80GB                 | 1         | 0.79%   |
| WDC WD7500BPKX-00HPJT0 752GB            | 1         | 0.79%   |
| WDC WD5001AALS-00L3B2 500GB             | 1         | 0.79%   |
| WDC WD5001AALS-00E3A0 500GB             | 1         | 0.79%   |
| WDC WD5000LPVX-00V0TT0 500GB            | 1         | 0.79%   |
| WDC WD40EFRX-68WT0N0 4TB                | 1         | 0.79%   |
| WDC WD3200BPVT-22JJ5T0 320GB            | 1         | 0.79%   |
| WDC WD3200BEVT-22A23T0 320GB            | 1         | 0.79%   |
| WDC WD3200BEVE-00A0HT0 320GB            | 1         | 0.79%   |
| WDC WD2500BEKT-00A25T0 250GB            | 1         | 0.79%   |
| WDC WD20PURZ-85GU6Y0 2TB                | 1         | 0.79%   |
| WDC WD20EZRX-00D8PB0 2TB                | 1         | 0.79%   |
| WDC WD20EFRX-68EUZN0 2TB                | 1         | 0.79%   |
| WDC WD1200JS-55NCB1 120GB               | 1         | 0.79%   |
| WDC WD10SPZX-21Z10T0 1TB                | 1         | 0.79%   |
| WDC WD10EZRX-00D8PB0 1TB                | 1         | 0.79%   |
| WDC WD10EZEX-75M2NA0 1TB                | 1         | 0.79%   |
| WDC WD10EZEX-22MFCA0 1TB                | 1         | 0.79%   |
| WDC WD10EZEX-22BN5A0 1TB                | 1         | 0.79%   |
| WDC WD10EZEX-08WN4A0 1TB                | 1         | 0.79%   |
| WDC WD10EURX-63FH1Y0 1TB                | 1         | 0.79%   |
| WD MediaMax WL500GSA3272 500GB          | 1         | 0.79%   |
| Unknown SD64G  64GB                     | 1         | 0.79%   |
| Unknown SD04G  4GB                      | 1         | 0.79%   |
| Unknown SD  8GB                         | 1         | 0.79%   |
| Unknown S0J9F8  64GB                    | 1         | 0.79%   |
| Unknown MMC32G  32GB                    | 1         | 0.79%   |
| Unknown MMC Card  32GB                  | 1         | 0.79%   |
| Unknown MMC Card  16GB                  | 1         | 0.79%   |
| Unknown MMC Card  128GB                 | 1         | 0.79%   |
| Union Memory RTOTJ128VGD2EYX 128GB SSD  | 1         | 0.79%   |
| Transcend TS128GSSD370S 128GB           | 1         | 0.79%   |
| Toshiba MQ04ABF100 1TB                  | 1         | 0.79%   |
| Toshiba MQ02ABF100 1TB                  | 1         | 0.79%   |
| Toshiba MK1252GSX 120GB                 | 1         | 0.79%   |
| Toshiba HDWD110 1TB                     | 1         | 0.79%   |
| Toshiba DT01ACA100 1TB                  | 1         | 0.79%   |
| Teclast 256GB NS550-2242 SSD            | 1         | 0.79%   |
| Team T253X1120G 120GB SSD               | 1         | 0.79%   |
| SMART SSD SZ9MSE mSATA 256GB            | 1         | 0.79%   |
| SK Hynix PC611 NVMe 1TB                 | 1         | 0.79%   |
| SK Hynix BC511 HFM256GDJTNI-82A0A 256GB | 1         | 0.79%   |
| Seagate ST9250410AS 250GB               | 1         | 0.79%   |
| Seagate ST8000DM004-2CX188 8TB          | 1         | 0.79%   |
| Seagate ST750LX003-1AC154 752GB         | 1         | 0.79%   |
| Seagate ST500LT012-1DG142 500GB         | 1         | 0.79%   |
| Seagate ST500DM002-1BD142 500GB         | 1         | 0.79%   |
| Seagate ST4000VN008-2DR166 4TB          | 1         | 0.79%   |
| Seagate ST4000DM005-2DP166 4TB          | 1         | 0.79%   |
| Seagate ST350063 0NS 500GB              | 1         | 0.79%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor          | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| WDC             | 20        | 28     | 38.46%  |
| Seagate         | 15        | 23     | 28.85%  |
| Toshiba         | 5         | 5      | 9.62%   |
| Hitachi         | 4         | 4      | 7.69%   |
| Fujitsu         | 3         | 3      | 5.77%   |
| HGST            | 2         | 2      | 3.85%   |
| MAXTOR          | 1         | 1      | 1.92%   |
| IBM/Hitachi     | 1         | 1      | 1.92%   |
| Hewlett-Packard | 1         | 2      | 1.92%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 7      | 14.63%  |
| Kingston            | 6         | 6      | 14.63%  |
| WDC                 | 3         | 4      | 7.32%   |
| PNY                 | 3         | 3      | 7.32%   |
| Crucial             | 3         | 3      | 7.32%   |
| Netac               | 2         | 2      | 4.88%   |
| Dogfish             | 2         | 2      | 4.88%   |
| A-DATA Technology   | 2         | 2      | 4.88%   |
| Union Memory        | 1         | 2      | 2.44%   |
| Transcend           | 1         | 2      | 2.44%   |
| Teclast             | 1         | 1      | 2.44%   |
| Team                | 1         | 1      | 2.44%   |
| SMART               | 1         | 1      | 2.44%   |
| SanDisk             | 1         | 1      | 2.44%   |
| SABRENT             | 1         | 2      | 2.44%   |
| Patriot             | 1         | 1      | 2.44%   |
| Micron Technology   | 1         | 1      | 2.44%   |
| LITEON              | 1         | 2      | 2.44%   |
| Kston               | 1         | 1      | 2.44%   |
| KingDian            | 1         | 1      | 2.44%   |
| Hewlett-Packard     | 1         | 1      | 2.44%   |
| GOODRAM             | 1         | 1      | 2.44%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 45        | 69     | 44.12%  |
| SSD     | 37        | 47     | 36.27%  |
| NVMe    | 12        | 19     | 11.76%  |
| MMC     | 6         | 8      | 5.88%   |
| Unknown | 2         | 2      | 1.96%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 66        | 110    | 75%     |
| NVMe | 12        | 19     | 13.64%  |
| MMC  | 6         | 8      | 6.82%   |
| SAS  | 4         | 8      | 4.55%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 51        | 72     | 63.75%  |
| 0.51-1.0   | 19        | 29     | 23.75%  |
| 1.01-2.0   | 6         | 11     | 7.5%    |
| 3.01-4.0   | 3         | 3      | 3.75%   |
| 4.01-10.0  | 1         | 1      | 1.25%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 18        | 22.78%  |
| 101-250        | 15        | 18.99%  |
| 1001-2000      | 11        | 13.92%  |
| 21-50          | 8         | 10.13%  |
| 501-1000       | 8         | 10.13%  |
| Unknown        | 6         | 7.59%   |
| 51-100         | 5         | 6.33%   |
| More than 3000 | 3         | 3.8%    |
| 1-20           | 3         | 3.8%    |
| 2001-3000      | 2         | 2.53%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 22        | 27.85%  |
| 1-20           | 19        | 24.05%  |
| 21-50          | 9         | 11.39%  |
| 51-100         | 7         | 8.86%   |
| 1001-2000      | 6         | 7.59%   |
| 501-1000       | 6         | 7.59%   |
| Unknown        | 6         | 7.59%   |
| 251-500        | 3         | 3.8%    |
| More than 3000 | 1         | 1.27%   |

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
| Works    | 53        | 94     | 59.55%  |
| Detected | 22        | 35     | 24.72%  |
| Malfunc  | 14        | 16     | 15.73%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 57        | 64.04%  |
| AMD                              | 11        | 12.36%  |
| Kingston Technology Company      | 4         | 4.49%   |
| Samsung Electronics              | 3         | 3.37%   |
| SK Hynix                         | 2         | 2.25%   |
| Micron/Crucial Technology        | 2         | 2.25%   |
| Marvell Technology Group         | 2         | 2.25%   |
| VIA Technologies                 | 1         | 1.12%   |
| Silicon Integrated Systems [SiS] | 1         | 1.12%   |
| Nvidia                           | 1         | 1.12%   |
| KIOXIA                           | 1         | 1.12%   |
| Integrated Technology Express    | 1         | 1.12%   |
| Broadcom / LSI                   | 1         | 1.12%   |
| ASMedia Technology               | 1         | 1.12%   |
| Adaptec                          | 1         | 1.12%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Computers | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 7         | 6.8%    |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 5         | 4.85%   |
| Kingston Company A2000 NVMe SSD                                                        | 4         | 3.88%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 4         | 3.88%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 4         | 3.88%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                      | 3         | 2.91%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 3         | 2.91%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]           | 3         | 2.91%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 3         | 2.91%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 3         | 2.91%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 3         | 2.91%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 3         | 2.91%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                        | 2         | 1.94%   |
| Intel SATA Controller [RAID mode]                                                      | 2         | 1.94%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 2         | 1.94%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                             | 2         | 1.94%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 2         | 1.94%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 2         | 1.94%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                                 | 2         | 1.94%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 2         | 1.94%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 2         | 1.94%   |
| AMD 400 Series Chipset SATA Controller                                                 | 2         | 1.94%   |
| VIA VT6421 IDE/SATA Controller                                                         | 1         | 0.97%   |
| SK Hynix Non-Volatile memory controller                                                | 1         | 0.97%   |
| SK Hynix BC511                                                                         | 1         | 0.97%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                            | 1         | 0.97%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                   | 1         | 0.97%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 1         | 0.97%   |
| Samsung NVMe SSD Controller SM951/PM951                                                | 1         | 0.97%   |
| Samsung NVMe SSD Controller 980                                                        | 1         | 0.97%   |
| Nvidia MCP79 SATA Controller                                                           | 1         | 0.97%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                       | 1         | 0.97%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller                                | 1         | 0.97%   |
| KIOXIA Non-Volatile memory controller                                                  | 1         | 0.97%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                | 1         | 0.97%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 1         | 0.97%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 1         | 0.97%   |
| Intel Atom processor C2000 AHCI SATA3 Controller                                       | 1         | 0.97%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                   | 1         | 0.97%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 1         | 0.97%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 1         | 0.97%   |
| Intel 82801FBM (ICH6M) SATA Controller                                                 | 1         | 0.97%   |
| Intel 82801EB/ER (ICH5/ICH5R) IDE Controller                                           | 1         | 0.97%   |
| Intel 82801BA IDE U100 Controller                                                      | 1         | 0.97%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 1         | 0.97%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 0.97%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 0.97%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller          | 1         | 0.97%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                          | 1         | 0.97%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                          | 1         | 0.97%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                       | 1         | 0.97%   |
| Integrated Express IT8213 IDE Controller                                               | 1         | 0.97%   |
| Broadcom / LSI SAS1068E PCI-Express Fusion-MPT SAS                                     | 1         | 0.97%   |
| ASMedia ASM1062 Serial ATA Controller                                                  | 1         | 0.97%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                   | 1         | 0.97%   |
| AMD FCH SATA Controller [IDE mode]                                                     | 1         | 0.97%   |
| AMD FCH SATA Controller D                                                              | 1         | 0.97%   |
| AMD FCH IDE Controller                                                                 | 1         | 0.97%   |
| AMD 300 Series Chipset SATA Controller                                                 | 1         | 0.97%   |
| Adaptec AIC-7870P/7881U [AHA-2940U/UW/D/S76]                                           | 1         | 0.97%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 52        | 59.77%  |
| IDE  | 17        | 19.54%  |
| NVMe | 12        | 13.79%  |
| RAID | 5         | 5.75%   |
| SCSI | 1         | 1.15%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 63        | 84%     |
| AMD    | 11        | 14.67%  |
| ARM    | 1         | 1.33%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-5300U CPU @ 2.30GHz           | 3         | 3.95%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 2         | 2.63%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 2         | 2.63%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 2         | 2.63%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 2         | 2.63%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2         | 2.63%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 2         | 2.63%   |
| Intel Xeon CPU X3460 @ 2.80GHz              | 1         | 1.32%   |
| Intel Xeon CPU E3-1270 V2 @ 3.50GHz         | 1         | 1.32%   |
| Intel Xeon CPU E3-1226 v3 @ 3.30GHz         | 1         | 1.32%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz    | 1         | 1.32%   |
| Intel Pentium M processor 1700MHz           | 1         | 1.32%   |
| Intel Pentium M processor 1.60GHz           | 1         | 1.32%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz      | 1         | 1.32%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 1.32%   |
| Intel Pentium Dual-Core CPU E6300 @ 2.80GHz | 1         | 1.32%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz      | 1         | 1.32%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1         | 1.32%   |
| Intel Pentium CPU P6100 @ 2.00GHz           | 1         | 1.32%   |
| Intel Pentium CPU G3240 @ 3.10GHz           | 1         | 1.32%   |
| Intel Pentium 4 CPU 3.00GHz                 | 1         | 1.32%   |
| Intel Core i9-8950HK CPU @ 2.90GHz          | 1         | 1.32%   |
| Intel Core i9-10850K CPU @ 3.60GHz          | 1         | 1.32%   |
| Intel Core i7-9850H CPU @ 2.60GHz           | 1         | 1.32%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 1.32%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 1         | 1.32%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 1         | 1.32%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1         | 1.32%   |
| Intel Core i7-3610QM CPU @ 2.30GHz          | 1         | 1.32%   |
| Intel Core i7-2640M CPU @ 2.80GHz           | 1         | 1.32%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 1         | 1.32%   |
| Intel Core i5-4590T CPU @ 2.00GHz           | 1         | 1.32%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1         | 1.32%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 1         | 1.32%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 1         | 1.32%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 1         | 1.32%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 1         | 1.32%   |
| Intel Core i5-10310U CPU @ 1.70GHz          | 1         | 1.32%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 1         | 1.32%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 1         | 1.32%   |
| Intel Core i3-2350M CPU @ 2.30GHz           | 1         | 1.32%   |
| Intel Core i3-10110U CPU @ 2.10GHz          | 1         | 1.32%   |
| Intel Core i3 CPU M 380 @ 2.53GHz           | 1         | 1.32%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 1         | 1.32%   |
| Intel Core i3 CPU M 330 @ 2.13GHz           | 1         | 1.32%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 1         | 1.32%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz        | 1         | 1.32%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 1         | 1.32%   |
| Intel Core 2 CPU T7200 @ 2.00GHz            | 1         | 1.32%   |
| Intel Core 2 CPU T5600 @ 1.83GHz            | 1         | 1.32%   |
| Intel Core 2 CPU P8600 @ 2.40GHz            | 1         | 1.32%   |
| Intel Celeron N4100 CPU @ 1.10GHz           | 1         | 1.32%   |
| Intel Celeron M processor 1.40GHz           | 1         | 1.32%   |
| Intel Celeron CPU N2830 @ 2.16GHz           | 1         | 1.32%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 1         | 1.32%   |
| Intel Celeron (Coppermine)                  | 1         | 1.32%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 1         | 1.32%   |
| Intel Atom CPU C2750 @ 2.40GHz              | 1         | 1.32%   |
| ARM Nokia RX-51 board Processor             | 1         | 1.32%   |
| AMD Sempron Processor 2800+                 | 1         | 1.32%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 19        | 25%     |
| Intel Core i7           | 8         | 10.53%  |
| Intel Core i3           | 6         | 7.89%   |
| Intel Core 2 Duo        | 4         | 5.26%   |
| Intel Celeron           | 4         | 5.26%   |
| Intel Xeon              | 3         | 3.95%   |
| Intel Core 2            | 3         | 3.95%   |
| AMD Ryzen 5             | 3         | 3.95%   |
| Other                   | 2         | 2.63%   |
| Intel Pentium M         | 2         | 2.63%   |
| Intel Pentium Dual-Core | 2         | 2.63%   |
| Intel Pentium Dual      | 2         | 2.63%   |
| Intel Pentium           | 2         | 2.63%   |
| Intel Core i9           | 2         | 2.63%   |
| Intel Atom              | 2         | 2.63%   |
| Intel Pentium Silver    | 1         | 1.32%   |
| Intel Pentium Gold      | 1         | 1.32%   |
| Intel Pentium 4         | 1         | 1.32%   |
| Intel Core 2 Quad       | 1         | 1.32%   |
| Intel Celeron M         | 1         | 1.32%   |
| AMD Sempron             | 1         | 1.32%   |
| AMD Ryzen 3             | 1         | 1.32%   |
| AMD FX                  | 1         | 1.32%   |
| AMD E2                  | 1         | 1.32%   |
| AMD E                   | 1         | 1.32%   |
| AMD A6                  | 1         | 1.32%   |
| AMD A4                  | 1         | 1.32%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 35        | 46.67%  |
| 4      | 23        | 30.67%  |
| 1      | 8         | 10.67%  |
| 6      | 7         | 9.33%   |
| 10     | 1         | 1.33%   |
| 8      | 1         | 1.33%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 75        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 41        | 54.67%  |
| 2      | 34        | 45.33%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 68        | 90.67%  |
| 32-bit         | 4         | 5.33%   |
| Unknown        | 3         | 4%      |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 20        | 25.97%  |
| 0x206a7    | 6         | 7.79%   |
| 0x1067a    | 5         | 6.49%   |
| 0x806ec    | 4         | 5.19%   |
| 0x306a9    | 4         | 5.19%   |
| 0x906ea    | 3         | 3.9%    |
| 0x306d4    | 3         | 3.9%    |
| 0x306c3    | 3         | 3.9%    |
| 0x706a1    | 2         | 2.6%    |
| 0x6f6      | 2         | 2.6%    |
| 0x406e3    | 2         | 2.6%    |
| 0x20655    | 2         | 2.6%    |
| 0xf49      | 1         | 1.3%    |
| 0xa0655    | 1         | 1.3%    |
| 0x906ed    | 1         | 1.3%    |
| 0x6fd      | 1         | 1.3%    |
| 0x6d8      | 1         | 1.3%    |
| 0x695      | 1         | 1.3%    |
| 0x686      | 1         | 1.3%    |
| 0x506e3    | 1         | 1.3%    |
| 0x406d8    | 1         | 1.3%    |
| 0x406c4    | 1         | 1.3%    |
| 0x40651    | 1         | 1.3%    |
| 0x30678    | 1         | 1.3%    |
| 0x20652    | 1         | 1.3%    |
| 0x106e5    | 1         | 1.3%    |
| 0x10676    | 1         | 1.3%    |
| 0x08701013 | 1         | 1.3%    |
| 0x08001138 | 1         | 1.3%    |
| 0x08001129 | 1         | 1.3%    |
| 0x05000119 | 1         | 1.3%    |
| 0x05000101 | 1         | 1.3%    |
| 0x03000027 | 1         | 1.3%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 9         | 12%     |
| Penryn        | 7         | 9.33%   |
| SandyBridge   | 6         | 8%      |
| IvyBridge     | 6         | 8%      |
| Haswell       | 5         | 6.67%   |
| Westmere      | 4         | 5.33%   |
| Skylake       | 4         | 5.33%   |
| Silvermont    | 4         | 5.33%   |
| P6            | 4         | 5.33%   |
| Core          | 4         | 5.33%   |
| Broadwell     | 4         | 5.33%   |
| Zen           | 2         | 2.67%   |
| Piledriver    | 2         | 2.67%   |
| Nehalem       | 2         | 2.67%   |
| Goldmont plus | 2         | 2.67%   |
| Bobcat        | 2         | 2.67%   |
| Zen+          | 1         | 1.33%   |
| Zen 2         | 1         | 1.33%   |
| NetBurst      | 1         | 1.33%   |
| K8 Hammer     | 1         | 1.33%   |
| K10 Llano     | 1         | 1.33%   |
| Excavator     | 1         | 1.33%   |
| CometLake     | 1         | 1.33%   |
| Unknown       | 1         | 1.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 43        | 54.43%  |
| AMD                              | 18        | 22.78%  |
| Nvidia                           | 17        | 21.52%  |
| Silicon Integrated Systems [SiS] | 1         | 1.27%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 5         | 6.02%   |
| Intel HD Graphics 5500                                                                   | 4         | 4.82%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 4.82%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 3         | 3.61%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 3.61%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 3.61%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 3.61%   |
| Nvidia G96CGL [Quadro FX 580]                                                            | 2         | 2.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 2.41%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 2.41%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 2.41%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 2         | 2.41%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1         | 1.2%    |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 1         | 1.2%    |
| Nvidia GP107M [GeForce MX150]                                                            | 1         | 1.2%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 1.2%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 1.2%    |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 1.2%    |
| Nvidia GK208B [GeForce GT 730]                                                           | 1         | 1.2%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 1         | 1.2%    |
| Nvidia GK106M [GeForce GTX 765M]                                                         | 1         | 1.2%    |
| Nvidia GK106 [GeForce GTX 650 Ti]                                                        | 1         | 1.2%    |
| Nvidia GF108M [GeForce GT 635M]                                                          | 1         | 1.2%    |
| Nvidia GA104 [GeForce RTX 3060 Ti]                                                       | 1         | 1.2%    |
| Nvidia C79 [GeForce 9400]                                                                | 1         | 1.2%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1         | 1.2%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 1.2%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 1.2%    |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 1.2%    |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1         | 1.2%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 1.2%    |
| Intel GeminiLake [UHD Graphics 605]                                                      | 1         | 1.2%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 1.2%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1         | 1.2%    |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                                | 1         | 1.2%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.2%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.2%    |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1         | 1.2%    |
| Intel 82852/855GM Integrated Graphics Device                                             | 1         | 1.2%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 1.2%    |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 1         | 1.2%    |
| AMD Wrestler [Radeon HD 7340]                                                            | 1         | 1.2%    |
| AMD Wrestler [Radeon HD 6310]                                                            | 1         | 1.2%    |
| AMD Trinity 2 [Radeon HD 7520G]                                                          | 1         | 1.2%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1         | 1.2%    |
| AMD RV380/M24 [Mobility Radeon X600]                                                     | 1         | 1.2%    |
| AMD RV350/M10 GL [Mobility FireGL T2]                                                    | 1         | 1.2%    |
| AMD RV350 [Radeon 9550] (Secondary)                                                      | 1         | 1.2%    |
| AMD RV350 [Radeon 9550]                                                                  | 1         | 1.2%    |
| AMD RV100 [Radeon 7000 / Radeon VE]                                                      | 1         | 1.2%    |
| AMD RS780L [Radeon 3000]                                                                 | 1         | 1.2%    |
| AMD R520/M58 [Mobility Radeon X1800]                                                     | 1         | 1.2%    |
| AMD R350 [Radeon 9800 Series]                                                            | 1         | 1.2%    |
| AMD R350 [Radeon 9800 PRO] (Secondary)                                                   | 1         | 1.2%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1         | 1.2%    |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 1         | 1.2%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 1         | 1.2%    |
| AMD Curacao XT / Trinidad XT [Radeon R7 370 / R9 270X/370X]                              | 1         | 1.2%    |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 1         | 1.2%    |
| AMD Baffin [Radeon Pro WX 4130/4150]                                                     | 1         | 1.2%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 35        | 46.67%  |
| 1 x AMD        | 16        | 21.33%  |
| 1 x Nvidia     | 13        | 17.33%  |
| Intel + Nvidia | 4         | 5.33%   |
| Other          | 3         | 4%      |
| 2 x Intel      | 1         | 1.33%   |
| 2 x AMD        | 1         | 1.33%   |
| 1 x SiS        | 1         | 1.33%   |
| Intel + AMD    | 1         | 1.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 63        | 82.89%  |
| Proprietary | 9         | 11.84%  |
| Unknown     | 4         | 5.26%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 45        | 59.21%  |
| 0.01-0.5   | 12        | 15.79%  |
| 0.51-1.0   | 5         | 6.58%   |
| 3.01-4.0   | 4         | 5.26%   |
| 1.01-2.0   | 4         | 5.26%   |
| 2.01-3.0   | 3         | 3.95%   |
| 7.01-8.0   | 2         | 2.63%   |
| 5.01-6.0   | 1         | 1.32%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 15        | 18.75%  |
| LG Display              | 10        | 12.5%   |
| AU Optronics            | 7         | 8.75%   |
| Goldstar                | 5         | 6.25%   |
| Lenovo                  | 4         | 5%      |
| Hewlett-Packard         | 4         | 5%      |
| Chimei Innolux          | 4         | 5%      |
| AOC                     | 4         | 5%      |
| Philips                 | 3         | 3.75%   |
| Acer                    | 3         | 3.75%   |
| PANDA                   | 2         | 2.5%    |
| Iiyama                  | 2         | 2.5%    |
| Dell                    | 2         | 2.5%    |
| Chi Mei Optoelectronics | 2         | 2.5%    |
| BOE                     | 2         | 2.5%    |
| ViewSonic               | 1         | 1.25%   |
| Toshiba                 | 1         | 1.25%   |
| STD                     | 1         | 1.25%   |
| MStar                   | 1         | 1.25%   |
| InnoLux Display         | 1         | 1.25%   |
| HJW                     | 1         | 1.25%   |
| Hisense                 | 1         | 1.25%   |
| eMachines               | 1         | 1.25%   |
| Eizo                    | 1         | 1.25%   |
| CVT                     | 1         | 1.25%   |
| Ancor Communications    | 1         | 1.25%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SyncMaster SAM0091 1600x1200 432x324mm 21.3-inch   | 2         | 2.38%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch            | 2         | 2.38%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch              | 2         | 2.38%   |
| ViewSonic VA2261 VSC0F30 1920x1080 477x268mm 21.5-inch                 | 1         | 1.19%   |
| Toshiba TV TSB0209 1920x1080 1594x900mm 72.1-inch                      | 1         | 1.19%   |
| STD STD HDMI TV STD00C7 1920x1080 698x392mm 31.5-inch                  | 1         | 1.19%   |
| Samsung Electronics T24B301 SAM098E 1920x1080 521x293mm 23.5-inch      | 1         | 1.19%   |
| Samsung Electronics SyncMaster SAM0226 1440x900 410x257mm 19.1-inch    | 1         | 1.19%   |
| Samsung Electronics SyncMaster SAM0029 1280x1024 312x234mm 15.4-inch   | 1         | 1.19%   |
| Samsung Electronics S24D340 SAM0BBB 1920x1080 530x300mm 24.0-inch      | 1         | 1.19%   |
| Samsung Electronics S/T 77/76BDF STN0007 1280x1024 312x234mm 15.4-inch | 1         | 1.19%   |
| Samsung Electronics LCD Monitor SyncMaster 1280x1024                   | 1         | 1.19%   |
| Samsung Electronics LCD Monitor SyncMaster                             | 1         | 1.19%   |
| Samsung Electronics LCD Monitor SEC4545 1280x800 331x207mm 15.4-inch   | 1         | 1.19%   |
| Samsung Electronics LCD Monitor SEC4151 1366x768 344x194mm 15.5-inch   | 1         | 1.19%   |
| Samsung Electronics LCD Monitor SDC4851 1366x768 344x194mm 15.5-inch   | 1         | 1.19%   |
| Samsung Electronics LCD Monitor SDC3853 2736x1824 260x173mm 12.3-inch  | 1         | 1.19%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 890x500mm 40.2-inch  | 1         | 1.19%   |
| Samsung Electronics LCD Monitor SA300/350/360                          | 1         | 1.19%   |
| Samsung Electronics LCD Monitor S24D340                                | 1         | 1.19%   |
| Samsung Electronics LCD Monitor C27F390 5760x1080                      | 1         | 1.19%   |
| Samsung Electronics C27F398 SAM0D45 1920x1080 598x336mm 27.0-inch      | 1         | 1.19%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                | 1         | 1.19%   |
| Philips 190B PHL086C 1280x1024 376x301mm 19.0-inch                     | 1         | 1.19%   |
| Philips 17S PHL0877 1280x1024 337x270mm 17.0-inch                      | 1         | 1.19%   |
| PANDA LM133LF5L01 NCP0020 1920x1080 294x165mm 13.3-inch                | 1         | 1.19%   |
| PANDA LCD Monitor NCP002E 1920x1080 344x194mm 15.5-inch                | 1         | 1.19%   |
| MStar Demo MST0030 1920x540 1150x650mm 52.0-inch                       | 1         | 1.19%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch          | 1         | 1.19%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch           | 1         | 1.19%   |
| LG Display LCD Monitor LGD0540 1920x1080 344x194mm 15.5-inch           | 1         | 1.19%   |
| LG Display LCD Monitor LGD046F 1920x1080 340x190mm 15.3-inch           | 1         | 1.19%   |
| LG Display LCD Monitor LGD0450 1366x768 277x156mm 12.5-inch            | 1         | 1.19%   |
| LG Display LCD Monitor LGD03A3 1366x768 277x156mm 12.5-inch            | 1         | 1.19%   |
| LG Display LCD Monitor LGD0386 1366x768 309x174mm 14.0-inch            | 1         | 1.19%   |
| LG Display LCD Monitor LGD02C0 1366x768 293x165mm 13.2-inch            | 1         | 1.19%   |
| Lenovo LI2215sD LEN65CC 1920x1080 476x267mm 21.5-inch                  | 1         | 1.19%   |
| Lenovo LCD Monitor LEN40A0 1366x768 309x174mm 14.0-inch                | 1         | 1.19%   |
| Lenovo LCD Monitor LEN4010 1280x800 261x163mm 12.1-inch                | 1         | 1.19%   |
| Lenovo LCD Monitor LEN4000 1024x768 246x184mm 12.1-inch                | 1         | 1.19%   |
| InnoLux Display LCD Monitor INL000A 1366x768 344x194mm 15.5-inch       | 1         | 1.19%   |
| Iiyama PLX2483H IVM6114 1920x1080 531x299mm 24.0-inch                  | 1         | 1.19%   |
| Iiyama PLB2712HDS IVM6602 1920x1080 598x336mm 27.0-inch                | 1         | 1.19%   |
| HJW HDMI TO USB HJW0001 1920x1080 700x390mm 31.5-inch                  | 1         | 1.19%   |
| Hisense Hisense HSE4000 1920x1080 591x355mm 27.1-inch                  | 1         | 1.19%   |
| Hewlett-Packard LA2206 HWP2947 1920x1080 476x268mm 21.5-inch           | 1         | 1.19%   |
| Hewlett-Packard L2245w HWP26FC 1680x1050 470x300mm 22.0-inch           | 1         | 1.19%   |
| Hewlett-Packard Compaq S2321a HWP2915 1920x1080 509x286mm 23.0-inch    | 1         | 1.19%   |
| Hewlett-Packard 24y HPN3504 1920x1080 528x297mm 23.9-inch              | 1         | 1.19%   |
| Hewlett-Packard 22cwa HWP3183 1920x1080 476x268mm 21.5-inch            | 1         | 1.19%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                | 1         | 1.19%   |
| Goldstar L1730S GSM438D 1280x1024 338x270mm 17.0-inch                  | 1         | 1.19%   |
| Goldstar E2260 GSM57E0 1920x1080 477x268mm 21.5-inch                   | 1         | 1.19%   |
| eMachines E19T6W EMA0783 1440x900 410x260mm 19.1-inch                  | 1         | 1.19%   |
| Eizo EV2456 ENC2798 1920x1200 520x330mm 24.2-inch                      | 1         | 1.19%   |
| Dell P2415Q DELA0BE 3840x2160 527x296mm 23.8-inch                      | 1         | 1.19%   |
| Dell LCD Monitor P1914S 1280x1024                                      | 1         | 1.19%   |
| CVT LCD Monitor CVT4668 1440x900 360x290mm 18.2-inch                   | 1         | 1.19%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch        | 1         | 1.19%   |
| Chimei Innolux LCD Monitor CMN15B8 1366x768 344x194mm 15.5-inch        | 1         | 1.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 29        | 36.71%  |
| 1366x768 (WXGA)    | 22        | 27.85%  |
| 3840x2160 (4K)     | 7         | 8.86%   |
| 1280x1024 (SXGA)   | 5         | 6.33%   |
| 1440x900 (WXGA+)   | 4         | 5.06%   |
| 1600x900 (HD+)     | 2         | 2.53%   |
| 1600x1200          | 2         | 2.53%   |
| 1280x800 (WXGA)    | 2         | 2.53%   |
| Unknown            | 2         | 2.53%   |
| 5760x1080          | 1         | 1.27%   |
| 2736x1824          | 1         | 1.27%   |
| 1920x1200 (WUXGA)  | 1         | 1.27%   |
| 1680x1050 (WSXGA+) | 1         | 1.27%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 18        | 23.08%  |
| 21      | 12        | 15.38%  |
| 12      | 7         | 8.97%   |
| 24      | 5         | 6.41%   |
| 14      | 5         | 6.41%   |
| 27      | 4         | 5.13%   |
| 23      | 4         | 5.13%   |
| 13      | 4         | 5.13%   |
| 31      | 3         | 3.85%   |
| 19      | 3         | 3.85%   |
| 18      | 3         | 3.85%   |
| 17      | 3         | 3.85%   |
| Unknown | 2         | 2.56%   |
| 72      | 1         | 1.28%   |
| 54      | 1         | 1.28%   |
| 52      | 1         | 1.28%   |
| 22      | 1         | 1.28%   |
| 11      | 1         | 1.28%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 24        | 32%     |
| 401-500     | 15        | 20%     |
| 501-600     | 13        | 17.33%  |
| 201-300     | 12        | 16%     |
| 601-700     | 3         | 4%      |
| 351-400     | 3         | 4%      |
| 1001-1500   | 2         | 2.67%   |
| Unknown     | 2         | 2.67%   |
| 1501-2000   | 1         | 1.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 51        | 73.91%  |
| 16/10   | 7         | 10.14%  |
| 4/3     | 4         | 5.8%    |
| 5/4     | 3         | 4.35%   |
| Unknown | 2         | 2.9%    |
| 6/5     | 1         | 1.45%   |
| 3/2     | 1         | 1.45%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 16        | 20.78%  |
| 101-110        | 16        | 20.78%  |
| 151-200        | 8         | 10.39%  |
| 61-70          | 7         | 9.09%   |
| 81-90          | 5         | 6.49%   |
| 71-80          | 4         | 5.19%   |
| 301-350        | 4         | 5.19%   |
| 141-150        | 4         | 5.19%   |
| More than 1000 | 3         | 3.9%    |
| 351-500        | 3         | 3.9%    |
| 111-120        | 2         | 2.6%    |
| Unknown        | 2         | 2.6%    |
| 51-60          | 1         | 1.3%    |
| 251-300        | 1         | 1.3%    |
| 131-140        | 1         | 1.3%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 26        | 34.21%  |
| 101-120       | 25        | 32.89%  |
| 121-160       | 14        | 18.42%  |
| 161-240       | 5         | 6.58%   |
| 1-50          | 3         | 3.95%   |
| Unknown       | 2         | 2.63%   |
| More than 240 | 1         | 1.32%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 59        | 76.62%  |
| 2     | 11        | 14.29%  |
| 3     | 4         | 5.19%   |
| 0     | 3         | 3.9%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 38        | 34.55%  |
| Intel                            | 33        | 30%     |
| Qualcomm Atheros                 | 17        | 15.45%  |
| Ralink Technology                | 3         | 2.73%   |
| Marvell Technology Group         | 3         | 2.73%   |
| TP-Link                          | 2         | 1.82%   |
| NetGear                          | 2         | 1.82%   |
| JMicron Technology               | 2         | 1.82%   |
| Broadcom Limited                 | 2         | 1.82%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.91%   |
| VIA Technologies                 | 1         | 0.91%   |
| Silicon Integrated Systems [SiS] | 1         | 0.91%   |
| Samsung Electronics              | 1         | 0.91%   |
| Ralink                           | 1         | 0.91%   |
| Nvidia                           | 1         | 0.91%   |
| MEDIATEK                         | 1         | 0.91%   |
| Broadcom                         | 1         | 0.91%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 28        | 22.22%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 7         | 5.56%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 4         | 3.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 3         | 2.38%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 2.38%   |
| Intel Wireless 7265                                                     | 3         | 2.38%   |
| Intel Wireless 7260                                                     | 3         | 2.38%   |
| Intel Ethernet Connection (3) I218-LM                                   | 3         | 2.38%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 2.38%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.59%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 2         | 1.59%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 2         | 1.59%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.59%   |
| NetGear WG111v3 54 Mbps Wireless [realtek RTL8187B]                     | 2         | 1.59%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 2         | 1.59%   |
| Intel Ethernet Connection (7) I219-LM                                   | 2         | 1.59%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 1.59%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller       | 2         | 1.59%   |
| ZTE WCDMA MSM DEMO Mobile Boardband                                     | 1         | 0.79%   |
| VIA VT6105/VT6106S [Rhine-III]                                          | 1         | 0.79%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]         | 1         | 0.79%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 0.79%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 1         | 0.79%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 1         | 0.79%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.79%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                         | 1         | 0.79%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 1         | 0.79%   |
| Ralink RT5372 Wireless Adapter                                          | 1         | 0.79%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 0.79%   |
| Ralink MT7601U Wireless Adapter                                         | 1         | 0.79%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.79%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 0.79%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 1         | 0.79%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.79%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.79%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 0.79%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 1         | 0.79%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                              | 1         | 0.79%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 1         | 0.79%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter              | 1         | 0.79%   |
| Nvidia MCP79 Ethernet                                                   | 1         | 0.79%   |
| MEDIATEK MT7630e 802.11bgn Wireless Network Adapter                     | 1         | 0.79%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                       | 1         | 0.79%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                 | 1         | 0.79%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                       | 1         | 0.79%   |
| Intel Wireless 8260                                                     | 1         | 0.79%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 0.79%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 1         | 0.79%   |
| Intel Ethernet Connection I354 2.5 GbE Backplane                        | 1         | 0.79%   |
| Intel Ethernet Connection I217-LM                                       | 1         | 0.79%   |
| Intel Ethernet Connection (7) I219-V                                    | 1         | 0.79%   |
| Intel Ethernet Connection (6) I219-V                                    | 1         | 0.79%   |
| Intel Ethernet Connection (11) I219-V                                   | 1         | 0.79%   |
| Intel Ethernet Connection (10) I219-LM                                  | 1         | 0.79%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 0.79%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 0.79%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller        | 1         | 0.79%   |
| Intel 82579V Gigabit Network Connection                                 | 1         | 0.79%   |
| Intel 82578DM Gigabit Network Connection                                | 1         | 0.79%   |
| Intel 82576 Gigabit Network Connection                                  | 1         | 0.79%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 16        | 34.78%  |
| Qualcomm Atheros         | 15        | 32.61%  |
| Realtek Semiconductor    | 3         | 6.52%   |
| Ralink Technology        | 3         | 6.52%   |
| NetGear                  | 2         | 4.35%   |
| Broadcom Limited         | 2         | 4.35%   |
| TP-Link                  | 1         | 2.17%   |
| Ralink                   | 1         | 2.17%   |
| MEDIATEK                 | 1         | 2.17%   |
| Marvell Technology Group | 1         | 2.17%   |
| Broadcom                 | 1         | 2.17%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 3         | 6.52%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 6.52%   |
| Intel Wireless 7265                                                     | 3         | 6.52%   |
| Intel Wireless 7260                                                     | 3         | 6.52%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 6.52%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 4.35%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 2         | 4.35%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 4.35%   |
| NetGear WG111v3 54 Mbps Wireless [realtek RTL8187B]                     | 2         | 4.35%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 4.35%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 2.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 2.17%   |
| Ralink RT5372 Wireless Adapter                                          | 1         | 2.17%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 2.17%   |
| Ralink MT7601U Wireless Adapter                                         | 1         | 2.17%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 2.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 2.17%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 2.17%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 2.17%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 2.17%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter              | 1         | 2.17%   |
| MEDIATEK MT7630e 802.11bgn Wireless Network Adapter                     | 1         | 2.17%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                       | 1         | 2.17%   |
| Intel Wireless 8260                                                     | 1         | 2.17%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 2.17%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 1         | 2.17%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 2.17%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 2.17%   |
| Broadcom Limited BCM4321 802.11a/b/g/n                                  | 1         | 2.17%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 1         | 2.17%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 1         | 2.17%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 36        | 47.37%  |
| Intel                            | 26        | 34.21%  |
| Qualcomm Atheros                 | 4         | 5.26%   |
| Marvell Technology Group         | 2         | 2.63%   |
| JMicron Technology               | 2         | 2.63%   |
| ZTE WCDMA Technologies MSM       | 1         | 1.32%   |
| VIA Technologies                 | 1         | 1.32%   |
| TP-Link                          | 1         | 1.32%   |
| Silicon Integrated Systems [SiS] | 1         | 1.32%   |
| Samsung Electronics              | 1         | 1.32%   |
| Nvidia                           | 1         | 1.32%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 28        | 36.36%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 9.09%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 5.19%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 3.9%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 2.6%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 2         | 2.6%    |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 2.6%    |
| ZTE WCDMA MSM DEMO Mobile Boardband                               | 1         | 1.3%    |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1         | 1.3%    |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 1.3%    |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 1.3%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.3%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 1.3%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.3%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.3%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.3%    |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 1.3%    |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.3%    |
| Nvidia MCP79 Ethernet                                             | 1         | 1.3%    |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 1.3%    |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1         | 1.3%    |
| Intel Ethernet Connection I354 2.5 GbE Backplane                  | 1         | 1.3%    |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.3%    |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.3%    |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.3%    |
| Intel Ethernet Connection (11) I219-V                             | 1         | 1.3%    |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 1.3%    |
| Intel 82579V Gigabit Network Connection                           | 1         | 1.3%    |
| Intel 82578DM Gigabit Network Connection                          | 1         | 1.3%    |
| Intel 82576 Gigabit Network Connection                            | 1         | 1.3%    |
| Intel 82574L Gigabit Network Connection                           | 1         | 1.3%    |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 1.3%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)        | 1         | 1.3%    |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.3%    |
| Intel 82566DM-2 Gigabit Network Connection                        | 1         | 1.3%    |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                | 1         | 1.3%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 69        | 59.48%  |
| WiFi     | 44        | 37.93%  |
| Modem    | 3         | 2.59%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 48        | 59.26%  |
| WiFi     | 33        | 40.74%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 42        | 55.26%  |
| 1     | 28        | 36.84%  |
| 0     | 4         | 5.26%   |
| 5     | 1         | 1.32%   |
| 3     | 1         | 1.32%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 70        | 93.33%  |
| Yes  | 5         | 6.67%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 10        | 38.46%  |
| Qualcomm Atheros Communications | 4         | 15.38%  |
| Broadcom                        | 3         | 11.54%  |
| Cambridge Silicon Radio         | 2         | 7.69%   |
| Realtek Semiconductor           | 1         | 3.85%   |
| Ralink                          | 1         | 3.85%   |
| Marvell Semiconductor           | 1         | 3.85%   |
| Lite-On Technology              | 1         | 3.85%   |
| IMC Networks                    | 1         | 3.85%   |
| Foxconn / Hon Hai               | 1         | 3.85%   |
| Apple                           | 1         | 3.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                              | 7         | 26.92%  |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 7.69%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 7.69%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 7.69%   |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 7.69%   |
| Realtek Bluetooth Radio                             | 1         | 3.85%   |
| Ralink RT3290 Bluetooth                             | 1         | 3.85%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 3.85%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 3.85%   |
| Marvell Bluetooth and Wireless LAN Composite Device | 1         | 3.85%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 3.85%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 3.85%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 3.85%   |
| Foxconn / Hon Hai BT                                | 1         | 3.85%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 3.85%   |
| Apple Bluetooth USB Host Controller                 | 1         | 3.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 57        | 57.58%  |
| AMD                              | 15        | 15.15%  |
| Nvidia                           | 13        | 13.13%  |
| Plantronics                      | 2         | 2.02%   |
| Creative Labs                    | 2         | 2.02%   |
| Texas Instruments                | 1         | 1.01%   |
| Silicon Integrated Systems [SiS] | 1         | 1.01%   |
| Realtek Semiconductor            | 1         | 1.01%   |
| M-Audio                          | 1         | 1.01%   |
| Logitech                         | 1         | 1.01%   |
| KORG                             | 1         | 1.01%   |
| GYROCOM C&C                      | 1         | 1.01%   |
| Cirrus Logic                     | 1         | 1.01%   |
| C-Media Electronics              | 1         | 1.01%   |
| Blue Microphones                 | 1         | 1.01%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7         | 6.09%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6         | 5.22%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5         | 4.35%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5         | 4.35%   |
| Nvidia GP106 High Definition Audio Controller                              | 4         | 3.48%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 3.48%   |
| Intel Cannon Lake PCH cAVS                                                 | 4         | 3.48%   |
| Intel Broadwell-U Audio Controller                                         | 4         | 3.48%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 3.48%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4         | 3.48%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3         | 2.61%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 2.61%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 2.61%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 3         | 2.61%   |
| AMD FCH Azalia Controller                                                  | 3         | 2.61%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 3         | 2.61%   |
| Plantronics HD1                                                            | 2         | 1.74%   |
| Intel Sunrise Point-LP HD Audio                                            | 2         | 1.74%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.74%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 1.74%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 2         | 1.74%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]  | 2         | 1.74%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 2         | 1.74%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2         | 1.74%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1         | 0.87%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 1         | 0.87%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.87%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 0.87%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.87%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.87%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1         | 0.87%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 0.87%   |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 0.87%   |
| M-Audio MIDISPORT 4x4 Anniv                                                | 1         | 0.87%   |
| M-Audio M-Audio 1x1                                                        | 1         | 0.87%   |
| Logitech H390 headset with microphone                                      | 1         | 0.87%   |
| KORG nanoKONTROL studio controller                                         | 1         | 0.87%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 0.87%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 0.87%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 0.87%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller           | 1         | 0.87%   |
| Intel 82801BA/BAM AC'97 Audio Controller                                   | 1         | 0.87%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 0.87%   |
| Intel 200 Series PCH HD Audio                                              | 1         | 0.87%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 0.87%   |
| GYROCOM C&C Fiio E10                                                       | 1         | 0.87%   |
| Cirrus Logic Crystal CS4281 PCI Audio                                      | 1         | 0.87%   |
| C-Media Electronics CM106 Like Sound Device                                | 1         | 0.87%   |
| Blue Microphones Yeti Stereo Microphone                                    | 1         | 0.87%   |
| AMD Wrestler HDMI Audio                                                    | 1         | 0.87%   |
| AMD Trinity HDMI Audio Controller                                          | 1         | 0.87%   |
| AMD Starship/Matisse HD Audio Controller                                   | 1         | 0.87%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 0.87%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1         | 0.87%   |
| AMD High Definition Audio Controller                                       | 1         | 0.87%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 1         | 0.87%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1         | 0.87%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 1         | 0.87%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 18        | 23.68%  |
| Samsung Electronics | 13        | 17.11%  |
| Kingston            | 11        | 14.47%  |
| SK Hynix            | 7         | 9.21%   |
| Micron Technology   | 4         | 5.26%   |
| G.Skill             | 4         | 5.26%   |
| Crucial             | 4         | 5.26%   |
| Corsair             | 4         | 5.26%   |
| Nanya Technology    | 3         | 3.95%   |
| A-DATA Technology   | 3         | 3.95%   |
| Unknown (ABCD)      | 1         | 1.32%   |
| Smart               | 1         | 1.32%   |
| GOODRAM             | 1         | 1.32%   |
| Avant               | 1         | 1.32%   |
| Apacer              | 1         | 1.32%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB SODIMM DDR2                            | 2         | 2.3%    |
| Unknown RAM Module 1024MB SODIMM DDR                             | 2         | 2.3%    |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 2         | 2.3%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 2.3%    |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s            | 2         | 2.3%    |
| Corsair RAM CMK32GX4M4A2666C16 8GB DIMM DDR4 2667MT/s            | 2         | 2.3%    |
| Unknown RAM SM3S320SD0488CABC 8192MB SODIMM DDR3 1600MT/s        | 1         | 1.15%   |
| Unknown RAM Module 8192MB DIMM DDR3 800MT/s                      | 1         | 1.15%   |
| Unknown RAM Module 64MB DIMM DRAM 100MT/s                        | 1         | 1.15%   |
| Unknown RAM Module 512MB SODIMM DDR                              | 1         | 1.15%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 1         | 1.15%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 1         | 1.15%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                     | 1         | 1.15%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 1         | 1.15%   |
| Unknown RAM Module 256MB DIMM DRAM 100MT/s                       | 1         | 1.15%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 1.15%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                         | 1         | 1.15%   |
| Unknown RAM Module 2048MB DIMM SDRAM 667MT/s                     | 1         | 1.15%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 1         | 1.15%   |
| Unknown RAM Module 128MB DIMM DRAM 100MT/s                       | 1         | 1.15%   |
| Unknown RAM Module 1024MB SODIMM DDR2                            | 1         | 1.15%   |
| Unknown RAM Module 1024MB DIMM DDR 400MT/s                       | 1         | 1.15%   |
| Unknown RAM Module 1024MB DIMM DDR                               | 1         | 1.15%   |
| Unknown RAM BRAN51288G16C1600L 8GB DIMM DDR3 1600MT/s            | 1         | 1.15%   |
| Unknown RAM 3000 C16 Series 8192MB DIMM DDR4 2133MT/s            | 1         | 1.15%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR3 2400MT/s | 1         | 1.15%   |
| Smart RAM SH564128FJ8NWRNSQG 4096MB SODIMM DDR3 1600MT/s         | 1         | 1.15%   |
| Smart RAM SF564128CJ8NWMNSEG 4GB SODIMM DDR3 1600MT/s            | 1         | 1.15%   |
| SK Hynix RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s          | 1         | 1.15%   |
| SK Hynix RAM Module 4GB DIMM DDR3 1333MT/s                       | 1         | 1.15%   |
| SK Hynix RAM Module 4096MB DIMM DDR3 1066MT/s                    | 1         | 1.15%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s             | 1         | 1.15%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.15%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4096MB SODIMM DDR3 1333MT/s        | 1         | 1.15%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 1.15%   |
| Samsung RAM Module 2GB DIMM DDR3 1333MT/s                        | 1         | 1.15%   |
| Samsung RAM Module 2048MB Row Of Chips LPDDR3 1867MT/s           | 1         | 1.15%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 1         | 1.15%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 1         | 1.15%   |
| Samsung RAM M471B5673FH0-CF8 2048MB SODIMM 1067MT/s              | 1         | 1.15%   |
| Samsung RAM M471B5273EB0-CK0 4096MB SODIMM DDR3 4199MT/s         | 1         | 1.15%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.15%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 1         | 1.15%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.15%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s              | 1         | 1.15%   |
| Nanya RAM NT2GC64B88B0NS-CG 2048MB SODIMM DDR3 1334MT/s          | 1         | 1.15%   |
| Nanya RAM Module 2GB DIMM DDR3 1333MT/s                          | 1         | 1.15%   |
| Nanya RAM M2X4G64CB8HG5N-DG 4GB DIMM DDR3 1867MT/s               | 1         | 1.15%   |
| Micron RAM Module 2GB SODIMM DDR3 1067MT/s                       | 1         | 1.15%   |
| Micron RAM Module 2GB DIMM DDR3 1333MT/s                         | 1         | 1.15%   |
| Micron RAM DVM64453C DATARAM 8GB DIMM DDR3 1600MT/s              | 1         | 1.15%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 1         | 1.15%   |
| Kingston RAM TSB1600D3S1ELD/4GE 4096MB SODIMM DDR3 1067MT/s      | 1         | 1.15%   |
| Kingston RAM KHYXPX-MIE 8GB SODIMM DDR4 2667MT/s                 | 1         | 1.15%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s           | 1         | 1.15%   |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 2667MT/s              | 1         | 1.15%   |
| Kingston RAM KHX2133C14/8G 8192MB DIMM DDR4 2400MT/s             | 1         | 1.15%   |
| Kingston RAM KHX1600C9D3/4GX 4096MB DIMM DDR3 2400MT/s           | 1         | 1.15%   |
| Kingston RAM ACR16D3LS1NGG/2G 2GB SODIMM DDR3 1333MT/s           | 1         | 1.15%   |
| Kingston RAM 99U5704-001.A00G 4GB SODIMM DDR4 2400MT/s           | 1         | 1.15%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 30        | 46.88%  |
| DDR4    | 17        | 26.56%  |
| SDRAM   | 4         | 6.25%   |
| DDR     | 4         | 6.25%   |
| DDR2    | 3         | 4.69%   |
| LPDDR3  | 2         | 3.13%   |
| Unknown | 2         | 3.13%   |
| LPDDR4  | 1         | 1.56%   |
| DRAM    | 1         | 1.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 33        | 52.38%  |
| DIMM         | 28        | 44.44%  |
| Row Of Chips | 2         | 3.17%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 22        | 29.33%  |
| 4096  | 19        | 25.33%  |
| 2048  | 17        | 22.67%  |
| 16384 | 6         | 8%      |
| 1024  | 5         | 6.67%   |
| 32768 | 2         | 2.67%   |
| 512   | 1         | 1.33%   |
| 256   | 1         | 1.33%   |
| 128   | 1         | 1.33%   |
| 64    | 1         | 1.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 15        | 22.06%  |
| 2667    | 11        | 16.18%  |
| 1333    | 8         | 11.76%  |
| Unknown | 6         | 8.82%   |
| 2400    | 4         | 5.88%   |
| 1067    | 4         | 5.88%   |
| 3600    | 3         | 4.41%   |
| 2133    | 3         | 4.41%   |
| 4199    | 2         | 2.94%   |
| 1867    | 2         | 2.94%   |
| 800     | 2         | 2.94%   |
| 667     | 2         | 2.94%   |
| 3200    | 1         | 1.47%   |
| 1800    | 1         | 1.47%   |
| 1334    | 1         | 1.47%   |
| 1066    | 1         | 1.47%   |
| 400     | 1         | 1.47%   |
| 100     | 1         | 1.47%   |

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
| Chicony Electronics                    | 11        | 31.43%  |
| Acer                                   | 4         | 11.43%  |
| Sunplus Innovation Technology          | 3         | 8.57%   |
| Microdia                               | 3         | 8.57%   |
| Logitech                               | 2         | 5.71%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 5.71%   |
| Z-Star Microelectronics                | 1         | 2.86%   |
| Suyin                                  | 1         | 2.86%   |
| Softkinetic                            | 1         | 2.86%   |
| Samsung Electronics                    | 1         | 2.86%   |
| Mustek Systems                         | 1         | 2.86%   |
| MacroSilicon                           | 1         | 2.86%   |
| Lite-On Technology                     | 1         | 2.86%   |
| IMC Networks                           | 1         | 2.86%   |
| GEMBIRD                                | 1         | 2.86%   |
| Cubeternet                             | 1         | 2.86%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony integrated camera                        | 5         | 14.29%  |
| Acer BisonCam, NB Pro                            | 2         | 5.71%   |
| Z-Star Vimicro USB Camera (Altair)               | 1         | 2.86%   |
| Suyin Acer/HP Integrated Webcam [CN0314]         | 1         | 2.86%   |
| Sunplus Integrated_Webcam_HD                     | 1         | 2.86%   |
| Sunplus FHD Camera Microphone                    | 1         | 2.86%   |
| Sunplus Asus Webcam                              | 1         | 2.86%   |
| Softkinetic DepthSense 325                       | 1         | 2.86%   |
| Samsung Galaxy A5 (MTP)                          | 1         | 2.86%   |
| Mustek Systems USB 2.0 PC Camera                 | 1         | 2.86%   |
| Microdia WebCam SC-13HDL12639P                   | 1         | 2.86%   |
| Microdia Camera                                  | 1         | 2.86%   |
| Microdia 1.3 MPixel Integrated Webcam            | 1         | 2.86%   |
| MacroSilicon MiraBox Capture                     | 1         | 2.86%   |
| Logitech Webcam C270                             | 1         | 2.86%   |
| Logitech HD Pro Webcam C920                      | 1         | 2.86%   |
| Lite-On HP Wide Vision HD Camera                 | 1         | 2.86%   |
| IMC Networks Integrated Webcam                   | 1         | 2.86%   |
| GEMBIRD USB2.0 PC CAMERA                         | 1         | 2.86%   |
| Cubeternet GL-UPC822 UVC WebCam                  | 1         | 2.86%   |
| Chicony WebCam                                   | 1         | 2.86%   |
| Chicony VGA WebCam                               | 1         | 2.86%   |
| Chicony Lenovo Integrated Camera (0.3MP)         | 1         | 2.86%   |
| Chicony Lenovo EasyCamera                        | 1         | 2.86%   |
| Chicony EasyCamera                               | 1         | 2.86%   |
| Chicony CNF9055 Toshiba Webcam                   | 1         | 2.86%   |
| Cheng Uei Precision Industry (Foxlink) Webcam    | 1         | 2.86%   |
| Cheng Uei Precision Industry (Foxlink) FM13FF-82 | 1         | 2.86%   |
| Acer ThinkPad Integrated Camera                  | 1         | 2.86%   |
| Acer Integrated Camera                           | 1         | 2.86%   |

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
| 0     | 61        | 79.22%  |
| 1     | 10        | 12.99%  |
| 2     | 4         | 5.19%   |
| 3     | 2         | 2.6%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 3         | 15.79%  |
| Fingerprint reader       | 3         | 15.79%  |
| Communication controller | 3         | 15.79%  |
| Chipcard                 | 3         | 15.79%  |
| Net/wireless             | 2         | 10.53%  |
| Bluetooth                | 2         | 10.53%  |
| Multimedia controller    | 1         | 5.26%   |
| Firewire controller      | 1         | 5.26%   |
| Camera                   | 1         | 5.26%   |

