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

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                   | Computers | Percent |
|---------------------------|-----------|---------|
| 5.10.0-8-amd64            | 7         | 9.46%   |
| 4.19.0-9-amd64            | 6         | 8.11%   |
| 4.19.0-14-amd64           | 6         | 8.11%   |
| 5.10.0-9-amd64            | 5         | 6.76%   |
| 4.19.0-16-amd64           | 5         | 6.76%   |
| 5.7.0-2-amd64             | 3         | 4.05%   |
| 4.19.0-12-amd64           | 3         | 4.05%   |
| 5.7.0-0.bpo.2-amd64       | 2         | 2.7%    |
| 4.19.0-17-amd64           | 2         | 2.7%    |
| 4.19.0-10-amd64           | 2         | 2.7%    |
| 5.9.0-4-amd64             | 1         | 1.35%   |
| 5.9.0-1-amd64             | 1         | 1.35%   |
| 5.8.0-3-amd64             | 1         | 1.35%   |
| 5.8.0-1-amd64             | 1         | 1.35%   |
| 5.7.19-server1            | 1         | 1.35%   |
| 5.7.0-1-amd64             | 1         | 1.35%   |
| 5.6.0-2-amd64             | 1         | 1.35%   |
| 5.15.5-xanmod1            | 1         | 1.35%   |
| 5.14.0-4-amd64            | 1         | 1.35%   |
| 5.11.0-6.2-liquorix-amd64 | 1         | 1.35%   |
| 5.10.0-7-amd64            | 1         | 1.35%   |
| 5.10.0-6-amd64            | 1         | 1.35%   |
| 5.10.0-5-amd64            | 1         | 1.35%   |
| 5.10.0-4-amd64            | 1         | 1.35%   |
| 5.10.0-2-amd64            | 1         | 1.35%   |
| 5.10.0-1-amd64            | 1         | 1.35%   |
| 5.1.21                    | 1         | 1.35%   |
| 5.0.7                     | 1         | 1.35%   |
| 4.9.0-15-amd64            | 1         | 1.35%   |
| 4.9.0-14-amd64            | 1         | 1.35%   |
| 4.9.0-14-686-pae          | 1         | 1.35%   |
| 4.9.0-14-686              | 1         | 1.35%   |
| 4.9.0-11-amd64            | 1         | 1.35%   |
| 4.9.0-11-686-pae          | 1         | 1.35%   |
| 4.9.0-11-686              | 1         | 1.35%   |
| 4.9.0-0.bpo.4-686-pae     | 1         | 1.35%   |
| 4.4.195-antix.1-amd64-smp | 1         | 1.35%   |
| 4.19.112                  | 1         | 1.35%   |
| 4.19.0-17-686-pae         | 1         | 1.35%   |
| 4.19.0-13-amd64           | 1         | 1.35%   |
| 4.19.0-1-amd64            | 1         | 1.35%   |
| 4.19.0-0.bpo.6-amd64      | 1         | 1.35%   |
| 4.18.0-0.bpo.1-amd64      | 1         | 1.35%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 4.19.0   | 27        | 36.99%  |
| 5.10.0   | 18        | 24.66%  |
| 4.9.0    | 8         | 10.96%  |
| 5.7.0    | 6         | 8.22%   |
| 5.9.0    | 2         | 2.74%   |
| 5.8.0    | 2         | 2.74%   |
| 5.7.19   | 1         | 1.37%   |
| 5.6.0    | 1         | 1.37%   |
| 5.15.5   | 1         | 1.37%   |
| 5.14.0   | 1         | 1.37%   |
| 5.11.0   | 1         | 1.37%   |
| 5.1.21   | 1         | 1.37%   |
| 5.0.7    | 1         | 1.37%   |
| 4.4.195  | 1         | 1.37%   |
| 4.19.112 | 1         | 1.37%   |
| 4.18.0   | 1         | 1.37%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.19    | 28        | 38.36%  |
| 5.10    | 18        | 24.66%  |
| 4.9     | 8         | 10.96%  |
| 5.7     | 7         | 9.59%   |
| 5.9     | 2         | 2.74%   |
| 5.8     | 2         | 2.74%   |
| 5.6     | 1         | 1.37%   |
| 5.15    | 1         | 1.37%   |
| 5.14    | 1         | 1.37%   |
| 5.11    | 1         | 1.37%   |
| 5.1     | 1         | 1.37%   |
| 5.0     | 1         | 1.37%   |
| 4.4     | 1         | 1.37%   |
| 4.18    | 1         | 1.37%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 61        | 89.71%  |
| i686   | 6         | 8.82%   |
| armv7l | 1         | 1.47%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| XFCE     | 29        | 41.43%  |
| KDE5     | 10        | 14.29%  |
| MATE     | 9         | 12.86%  |
| Unknown  | 9         | 12.86%  |
| i3       | 4         | 5.71%   |
| LXDE     | 3         | 4.29%   |
| LXQt     | 2         | 2.86%   |
| Openbox  | 1         | 1.43%   |
| GNOME    | 1         | 1.43%   |
| Cinnamon | 1         | 1.43%   |
| awesome  | 1         | 1.43%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 64        | 94.12%  |
| Tty     | 3         | 4.41%   |
| Unknown | 1         | 1.47%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SLiM    | 26        | 37.14%  |
| LightDM | 19        | 27.14%  |
| Unknown | 17        | 24.29%  |
| SDDM    | 4         | 5.71%   |
| XDM     | 2         | 2.86%   |
| NODM    | 1         | 1.43%   |
| GDM3    | 1         | 1.43%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 21        | 30.43%  |
| en_GB       | 13        | 18.84%  |
| ru_RU       | 6         | 8.7%    |
| Unknown     | 5         | 7.25%   |
| C           | 4         | 5.8%    |
| sk_SK       | 3         | 4.35%   |
| pt_BR       | 3         | 4.35%   |
| fr_FR       | 3         | 4.35%   |
| en_AU       | 2         | 2.9%    |
| pl_PL       | 1         | 1.45%   |
| it_IT       | 1         | 1.45%   |
| fr_BE       | 1         | 1.45%   |
| es_SV       | 1         | 1.45%   |
| es_ES       | 1         | 1.45%   |
| en_US.utf-8 | 1         | 1.45%   |
| en_NZ       | 1         | 1.45%   |
| en_CA       | 1         | 1.45%   |
| de_AT       | 1         | 1.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 45        | 66.18%  |
| EFI  | 23        | 33.82%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 55        | 80.88%  |
| Unknown | 5         | 7.35%   |
| Btrfs   | 4         | 5.88%   |
| Overlay | 2         | 2.94%   |
| OveXlay | 1         | 1.47%   |
| Ext3    | 1         | 1.47%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| MBR     | 32        | 45.07%  |
| GPT     | 31        | 43.66%  |
| Unknown | 8         | 11.27%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 53        | 76.81%  |
| Yes       | 16        | 23.19%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 51        | 73.91%  |
| Yes       | 18        | 26.09%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 12        | 17.65%  |
| ASUSTek Computer    | 9         | 13.24%  |
| Gigabyte Technology | 8         | 11.76%  |
| Hewlett-Packard     | 6         | 8.82%   |
| Dell                | 5         | 7.35%   |
| Acer                | 4         | 5.88%   |
| MSI                 | 3         | 4.41%   |
| ASRock              | 3         | 4.41%   |
| Toshiba             | 2         | 2.94%   |
| Intel               | 2         | 2.94%   |
| Fujitsu Siemens     | 2         | 2.94%   |
| Teclast             | 1         | 1.47%   |
| Sun Microsystems    | 1         | 1.47%   |
| Samsung Electronics | 1         | 1.47%   |
| Nokia               | 1         | 1.47%   |
| MTC                 | 1         | 1.47%   |
| Microsoft           | 1         | 1.47%   |
| IBM                 | 1         | 1.47%   |
| Google              | 1         | 1.47%   |
| Fujitsu             | 1         | 1.47%   |
| Chuwi               | 1         | 1.47%   |
| Apple               | 1         | 1.47%   |
| AMI                 | 1         | 1.47%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                                                                     | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Toshiba Satellite M40X                                                                   | 1         | 1.47%   |
| Toshiba Satellite L655                                                                   | 1         | 1.47%   |
| Teclast F6 Plus                                                                          | 1         | 1.47%   |
| Sun Microsystems Ultra 24                                                                | 1         | 1.47%   |
| Samsung 355V4C/355V4X/355V5C/355V5X/356V4C/356V4X/356V5C/356V5X/3445VC/3445VX/3545VC/354 | 1         | 1.47%   |
| Nokia N900                                                                               | 1         | 1.47%   |
| MTC Montara-GML                                                                          | 1         | 1.47%   |
| MSI MS-7B53                                                                              | 1         | 1.47%   |
| MSI MS-7A34                                                                              | 1         | 1.47%   |
| MSI MS-1688                                                                              | 1         | 1.47%   |
| Microsoft Surface Pro 4                                                                  | 1         | 1.47%   |
| Lenovo Yoga C640-13IML 81UE                                                              | 1         | 1.47%   |
| Lenovo ThinkStation E20 4220CTO                                                          | 1         | 1.47%   |
| Lenovo ThinkPad X60 1707YF8                                                              | 1         | 1.47%   |
| Lenovo ThinkPad X250 20CLS7WY04                                                          | 1         | 1.47%   |
| Lenovo ThinkPad X230 2325DE0                                                             | 1         | 1.47%   |
| Lenovo ThinkPad X230 23247S0                                                             | 1         | 1.47%   |
| Lenovo ThinkPad X220 429053G                                                             | 1         | 1.47%   |
| Lenovo ThinkPad X200 74585FU                                                             | 1         | 1.47%   |
| Lenovo ThinkPad X1 Carbon 7th 20QD00L1PB                                                 | 1         | 1.47%   |
| Lenovo ThinkPad T550 20CJS1VD01                                                          | 1         | 1.47%   |
| Lenovo IdeaPad Z370                                                                      | 1         | 1.47%   |
| Lenovo IdeaPad 130-15AST 81H5                                                            | 1         | 1.47%   |
| Intel D815EEA AAA45884-401                                                               | 1         | 1.47%   |
| Intel AHV                                                                                | 1         | 1.47%   |
| IBM ThinkPad T41p 2373GHG                                                                | 1         | 1.47%   |
| HP Z220 SFF Workstation                                                                  | 1         | 1.47%   |
| HP ProBook 6475b                                                                         | 1         | 1.47%   |
| HP Pavilion x360 Convertible 14-dh1xxx                                                   | 1         | 1.47%   |
| HP Pavilion 11 x360 PC                                                                   | 1         | 1.47%   |
| HP EliteDesk 800 G1 DM                                                                   | 1         | 1.47%   |
| HP Compaq 8200 Elite SFF PC                                                              | 1         | 1.47%   |
| Google Panther                                                                           | 1         | 1.47%   |
| Gigabyte Z390 GAMING SLI                                                                 | 1         | 1.47%   |
| Gigabyte MZGLKBP-00                                                                      | 1         | 1.47%   |
| Gigabyte H170-HD3-CF                                                                     | 1         | 1.47%   |
| Gigabyte H170-HD3                                                                        | 1         | 1.47%   |
| Gigabyte GA-G41M-ES2L                                                                    | 1         | 1.47%   |
| Gigabyte B75M-D3V                                                                        | 1         | 1.47%   |
| Gigabyte B450 AORUS ELITE                                                                | 1         | 1.47%   |
| Gigabyte 970A-DS3P                                                                       | 1         | 1.47%   |
| Fujitsu Siemens ESPRIMO Mobile V6535                                                     | 1         | 1.47%   |
| Fujitsu Siemens AMILO Xi 1546                                                            | 1         | 1.47%   |
| Fujitsu LIFEBOOK U7510                                                                   | 1         | 1.47%   |
| Dell Precision 7530                                                                      | 1         | 1.47%   |
| Dell OptiPlex 7010                                                                       | 1         | 1.47%   |
| Dell Latitude E7250                                                                      | 1         | 1.47%   |
| Dell Latitude 5501                                                                       | 1         | 1.47%   |
| Dell Inspiron 1564                                                                       | 1         | 1.47%   |
| Chuwi Hi10 pro tablet                                                                    | 1         | 1.47%   |
| ASUS PRIME Z490M-PLUS                                                                    | 1         | 1.47%   |
| ASUS P5PE-VM                                                                             | 1         | 1.47%   |
| ASUS P5G41T-M LX2/BR                                                                     | 1         | 1.47%   |
| ASUS Maximus V GENE                                                                      | 1         | 1.47%   |
| ASUS K55VJ                                                                               | 1         | 1.47%   |
| ASUS K52F                                                                                | 1         | 1.47%   |
| ASUS F1A55-M LX                                                                          | 1         | 1.47%   |
| ASUS EX-A320M-GAMING                                                                     | 1         | 1.47%   |
| ASUS All Series                                                                          | 1         | 1.47%   |
| ASRock K8A780LM                                                                          | 1         | 1.47%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 8         | 11.76%  |
| Acer Aspire             | 3         | 4.41%   |
| Toshiba Satellite       | 2         | 2.94%   |
| Lenovo IdeaPad          | 2         | 2.94%   |
| HP Pavilion             | 2         | 2.94%   |
| Dell Latitude           | 2         | 2.94%   |
| Teclast F6              | 1         | 1.47%   |
| Sun Microsystems Ultra  | 1         | 1.47%   |
| Samsung 355V4C          | 1         | 1.47%   |
| Nokia N900              | 1         | 1.47%   |
| MTC Montara-GML         | 1         | 1.47%   |
| MSI MS-7B53             | 1         | 1.47%   |
| MSI MS-7A34             | 1         | 1.47%   |
| MSI MS-1688             | 1         | 1.47%   |
| Microsoft Surface       | 1         | 1.47%   |
| Lenovo Yoga             | 1         | 1.47%   |
| Lenovo ThinkStation     | 1         | 1.47%   |
| Intel D815EEA           | 1         | 1.47%   |
| Intel AHV               | 1         | 1.47%   |
| IBM ThinkPad            | 1         | 1.47%   |
| HP Z220                 | 1         | 1.47%   |
| HP ProBook              | 1         | 1.47%   |
| HP EliteDesk            | 1         | 1.47%   |
| HP Compaq               | 1         | 1.47%   |
| Google Panther          | 1         | 1.47%   |
| Gigabyte Z390           | 1         | 1.47%   |
| Gigabyte MZGLKBP-00     | 1         | 1.47%   |
| Gigabyte H170-HD3-CF    | 1         | 1.47%   |
| Gigabyte H170-HD3       | 1         | 1.47%   |
| Gigabyte GA-G41M-ES2L   | 1         | 1.47%   |
| Gigabyte B75M-D3V       | 1         | 1.47%   |
| Gigabyte B450           | 1         | 1.47%   |
| Gigabyte 970A-DS3P      | 1         | 1.47%   |
| Fujitsu Siemens ESPRIMO | 1         | 1.47%   |
| Fujitsu Siemens AMILO   | 1         | 1.47%   |
| Fujitsu LIFEBOOK        | 1         | 1.47%   |
| Dell Precision          | 1         | 1.47%   |
| Dell OptiPlex           | 1         | 1.47%   |
| Dell Inspiron           | 1         | 1.47%   |
| Chuwi Hi10              | 1         | 1.47%   |
| ASUS PRIME              | 1         | 1.47%   |
| ASUS P5PE-VM            | 1         | 1.47%   |
| ASUS P5G41T-M           | 1         | 1.47%   |
| ASUS Maximus            | 1         | 1.47%   |
| ASUS K55VJ              | 1         | 1.47%   |
| ASUS K52F               | 1         | 1.47%   |
| ASUS F1A55-M            | 1         | 1.47%   |
| ASUS EX-A320M-GAMING    | 1         | 1.47%   |
| ASUS All                | 1         | 1.47%   |
| ASRock K8A780LM         | 1         | 1.47%   |
| ASRock H81M-ITX         | 1         | 1.47%   |
| ASRock G31M-VS2         | 1         | 1.47%   |
| Apple Macmini3          | 1         | 1.47%   |
| AMI Aptio               | 1         | 1.47%   |
| Acer Extensa            | 1         | 1.47%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 10        | 14.71%  |
| 2011    | 9         | 13.24%  |
| 2018    | 8         | 11.76%  |
| 2015    | 6         | 8.82%   |
| 2020    | 5         | 7.35%   |
| 2013    | 4         | 5.88%   |
| 2012    | 4         | 5.88%   |
| 2009    | 4         | 5.88%   |
| 2016    | 3         | 4.41%   |
| 2014    | 3         | 4.41%   |
| 2007    | 3         | 4.41%   |
| 2021    | 2         | 2.94%   |
| 2005    | 2         | 2.94%   |
| 2017    | 1         | 1.47%   |
| 2010    | 1         | 1.47%   |
| 2006    | 1         | 1.47%   |
| 2000    | 1         | 1.47%   |
| Unknown | 1         | 1.47%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 33        | 48.53%  |
| Desktop     | 29        | 42.65%  |
| Tablet      | 2         | 2.94%   |
| Convertible | 2         | 2.94%   |
| Mini pc     | 2         | 2.94%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 68        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 65        | 95.59%  |
| Yes  | 3         | 4.41%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 13        | 19.12%  |
| 3.01-4.0    | 13        | 19.12%  |
| 8.01-16.0   | 13        | 19.12%  |
| 16.01-24.0  | 11        | 16.18%  |
| 32.01-64.0  | 6         | 8.82%   |
| 1.01-2.0    | 6         | 8.82%   |
| 0.01-0.5    | 3         | 4.41%   |
| 2.01-3.0    | 2         | 2.94%   |
| 64.01-256.0 | 1         | 1.47%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 24        | 33.33%  |
| 4.01-8.0   | 14        | 19.44%  |
| 2.01-3.0   | 12        | 16.67%  |
| 0.51-1.0   | 11        | 15.28%  |
| 0.01-0.5   | 4         | 5.56%   |
| 3.01-4.0   | 3         | 4.17%   |
| 8.01-16.0  | 3         | 4.17%   |
| 32.01-64.0 | 1         | 1.39%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 40        | 58.82%  |
| 2      | 14        | 20.59%  |
| 3      | 6         | 8.82%   |
| 4      | 5         | 7.35%   |
| 5      | 3         | 4.41%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 45        | 65.22%  |
| Yes       | 24        | 34.78%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 62        | 91.18%  |
| No        | 6         | 8.82%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 41        | 59.42%  |
| No        | 28        | 40.58%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 46        | 67.65%  |
| Yes       | 22        | 32.35%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Russia      | 8         | 11.76%  |
| Ukraine     | 6         | 8.82%   |
| France      | 6         | 8.82%   |
| USA         | 4         | 5.88%   |
| Grenada     | 4         | 5.88%   |
| Brazil      | 4         | 5.88%   |
| Slovakia    | 3         | 4.41%   |
| Poland      | 3         | 4.41%   |
| Netherlands | 3         | 4.41%   |
| Germany     | 3         | 4.41%   |
| Israel      | 2         | 2.94%   |
| Hungary     | 2         | 2.94%   |
| Australia   | 2         | 2.94%   |
| UK          | 1         | 1.47%   |
| Switzerland | 1         | 1.47%   |
| Spain       | 1         | 1.47%   |
| South Korea | 1         | 1.47%   |
| Portugal    | 1         | 1.47%   |
| Norway      | 1         | 1.47%   |
| New Zealand | 1         | 1.47%   |
| Mexico      | 1         | 1.47%   |
| Italy       | 1         | 1.47%   |
| Indonesia   | 1         | 1.47%   |
| India       | 1         | 1.47%   |
| Greece      | 1         | 1.47%   |
| Finland     | 1         | 1.47%   |
| El Salvador | 1         | 1.47%   |
| Canada      | 1         | 1.47%   |
| Belgium     | 1         | 1.47%   |
| Austria     | 1         | 1.47%   |
| Argentina   | 1         | 1.47%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Kyiv                 | 3         | 4.35%   |
| Gouyave              | 3         | 4.35%   |
| Bratislava           | 3         | 4.35%   |
| Bagnolet             | 3         | 4.35%   |
| Wroclaw              | 2         | 2.9%    |
| Volzhskiy            | 2         | 2.9%    |
| Tel Aviv             | 2         | 2.9%    |
| São Paulo           | 2         | 2.9%    |
| Ryde                 | 2         | 2.9%    |
| Rio de Janeiro       | 2         | 2.9%    |
| Hillsborough         | 2         | 2.9%    |
| Budapest             | 2         | 2.9%    |
| Zeist                | 1         | 1.45%   |
| Wageningen           | 1         | 1.45%   |
| Vologda              | 1         | 1.45%   |
| Toronto              | 1         | 1.45%   |
| Thrissur             | 1         | 1.45%   |
| Thessaloniki         | 1         | 1.45%   |
| Talavera de la Reina | 1         | 1.45%   |
| Syeverodonets'k      | 1         | 1.45%   |
| St Petersburg        | 1         | 1.45%   |
| Seongbuk-gu          | 1         | 1.45%   |
| San Salvador         | 1         | 1.45%   |
| Saint-Herblain       | 1         | 1.45%   |
| Poperinge            | 1         | 1.45%   |
| Oslo                 | 1         | 1.45%   |
| Oleksandriya         | 1         | 1.45%   |
| Nérac               | 1         | 1.45%   |
| Mozdok               | 1         | 1.45%   |
| Moscow               | 1         | 1.45%   |
| Milan                | 1         | 1.45%   |
| Miedziana Gora       | 1         | 1.45%   |
| Miami                | 1         | 1.45%   |
| Mglin                | 1         | 1.45%   |
| Lisbon               | 1         | 1.45%   |
| Leonding             | 1         | 1.45%   |
| Kirov                | 1         | 1.45%   |
| Jyväskylä          | 1         | 1.45%   |
| Hochheim am Main     | 1         | 1.45%   |
| Hermosillo           | 1         | 1.45%   |
| Hayden               | 1         | 1.45%   |
| Haiger               | 1         | 1.45%   |
| Forest Grove         | 1         | 1.45%   |
| Donetsk              | 1         | 1.45%   |
| Depok                | 1         | 1.45%   |
| Cologne              | 1         | 1.45%   |
| Coghlan              | 1         | 1.45%   |
| Château-Thierry     | 1         | 1.45%   |
| Bradford             | 1         | 1.45%   |
| Auckland             | 1         | 1.45%   |
| Atlanta              | 1         | 1.45%   |
| Amsterdam            | 1         | 1.45%   |
| Aarburg              | 1         | 1.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 20        | 28     | 19.61%  |
| Seagate             | 13        | 20     | 12.75%  |
| Samsung Electronics | 9         | 15     | 8.82%   |
| Kingston            | 8         | 9      | 7.84%   |
| Unknown             | 6         | 8      | 5.88%   |
| Toshiba             | 5         | 5      | 4.9%    |
| Hitachi             | 4         | 4      | 3.92%   |
| Crucial             | 4         | 5      | 3.92%   |
| PNY                 | 3         | 3      | 2.94%   |
| Fujitsu             | 3         | 3      | 2.94%   |
| SK Hynix            | 2         | 2      | 1.96%   |
| Netac               | 2         | 2      | 1.96%   |
| Dogfish             | 2         | 2      | 1.96%   |
| A-DATA Technology   | 2         | 2      | 1.96%   |
| Union Memory        | 1         | 2      | 0.98%   |
| Transcend           | 1         | 2      | 0.98%   |
| Teclast             | 1         | 1      | 0.98%   |
| Team                | 1         | 1      | 0.98%   |
| SMART               | 1         | 1      | 0.98%   |
| SanDisk             | 1         | 1      | 0.98%   |
| SABRENT             | 1         | 2      | 0.98%   |
| Patriot             | 1         | 1      | 0.98%   |
| Micron Technology   | 1         | 1      | 0.98%   |
| MAXTOR              | 1         | 1      | 0.98%   |
| LITEON              | 1         | 2      | 0.98%   |
| Kston               | 1         | 1      | 0.98%   |
| KIOXIA              | 1         | 1      | 0.98%   |
| KingDian            | 1         | 1      | 0.98%   |
| Intel               | 1         | 1      | 0.98%   |
| IBM/Hitachi         | 1         | 1      | 0.98%   |
| HGST                | 1         | 1      | 0.98%   |
| Hewlett-Packard     | 1         | 2      | 0.98%   |
| GOODRAM             | 1         | 1      | 0.98%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| PNY CS900 240GB SSD                     | 3         | 2.61%   |
| WDC WD5000BPVT-24HXZT3 500GB            | 2         | 1.74%   |
| WDC WD10EARX-00N0YB0 1TB                | 2         | 1.74%   |
| Seagate ST2000DX002-2DV164 2TB          | 2         | 1.74%   |
| Samsung SSD 860 EVO 250GB               | 2         | 1.74%   |
| Kingston SA400S37120G 120GB SSD         | 2         | 1.74%   |
| Kingston SA2000M8250G 250GB             | 2         | 1.74%   |
| WDC WDS480G2G0A-00JH30 480GB SSD        | 1         | 0.87%   |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 1         | 0.87%   |
| WDC WDS120G2G0A-00JH30 120GB SSD        | 1         | 0.87%   |
| WDC WD800BB-00JHC0 80GB                 | 1         | 0.87%   |
| WDC WD5001AALS-00L3B2 500GB             | 1         | 0.87%   |
| WDC WD5000LPVX-00V0TT0 500GB            | 1         | 0.87%   |
| WDC WD40EFRX-68WT0N0 4TB                | 1         | 0.87%   |
| WDC WD3200BPVT-22JJ5T0 320GB            | 1         | 0.87%   |
| WDC WD3200BEVT-22A23T0 320GB            | 1         | 0.87%   |
| WDC WD3200BEVE-00A0HT0 320GB            | 1         | 0.87%   |
| WDC WD2500BEKT-00A25T0 250GB            | 1         | 0.87%   |
| WDC WD20PURZ-85GU6Y0 2TB                | 1         | 0.87%   |
| WDC WD20EZRX-00D8PB0 2TB                | 1         | 0.87%   |
| WDC WD20EFRX-68EUZN0 2TB                | 1         | 0.87%   |
| WDC WD1200JS-55NCB1 120GB               | 1         | 0.87%   |
| WDC WD10SPZX-21Z10T0 1TB                | 1         | 0.87%   |
| WDC WD10EZRX-00D8PB0 1TB                | 1         | 0.87%   |
| WDC WD10EZEX-75M2NA0 1TB                | 1         | 0.87%   |
| WDC WD10EZEX-22MFCA0 1TB                | 1         | 0.87%   |
| WDC WD10EZEX-22BN5A0 1TB                | 1         | 0.87%   |
| WDC WD10EZEX-08WN4A0 1TB                | 1         | 0.87%   |
| Unknown SD64G  64GB                     | 1         | 0.87%   |
| Unknown SD04G  4GB                      | 1         | 0.87%   |
| Unknown SD  8GB                         | 1         | 0.87%   |
| Unknown S0J9F8  64GB                    | 1         | 0.87%   |
| Unknown MMC32G  32GB                    | 1         | 0.87%   |
| Unknown MMC Card  32GB                  | 1         | 0.87%   |
| Unknown MMC Card  16GB                  | 1         | 0.87%   |
| Unknown MMC Card  128GB                 | 1         | 0.87%   |
| Union Memory RTOTJ128VGD2EYX 128GB SSD  | 1         | 0.87%   |
| Transcend TS128GSSD370S 128GB           | 1         | 0.87%   |
| Toshiba MQ04ABF100 1TB                  | 1         | 0.87%   |
| Toshiba MQ02ABF100 1TB                  | 1         | 0.87%   |
| Toshiba MK1252GSX 120GB                 | 1         | 0.87%   |
| Toshiba HDWD110 1TB                     | 1         | 0.87%   |
| Toshiba DT01ACA100 1TB                  | 1         | 0.87%   |
| Teclast 256GB NS550-2242 SSD            | 1         | 0.87%   |
| Team T253X1120G 120GB SSD               | 1         | 0.87%   |
| SMART SSD SZ9MSE mSATA 256GB            | 1         | 0.87%   |
| SK Hynix PC611 NVMe 1TB                 | 1         | 0.87%   |
| SK Hynix BC511 HFM256GDJTNI-82A0A 256GB | 1         | 0.87%   |
| Seagate ST9250410AS 250GB               | 1         | 0.87%   |
| Seagate ST750LX003-1AC154 752GB         | 1         | 0.87%   |
| Seagate ST500DM002-1BD142 500GB         | 1         | 0.87%   |
| Seagate ST4000VN008-2DR166 4TB          | 1         | 0.87%   |
| Seagate ST350063 0NS 500GB              | 1         | 0.87%   |
| Seagate ST3500418AS 500GB               | 1         | 0.87%   |
| Seagate ST340014A 40GB                  | 1         | 0.87%   |
| Seagate ST3300555SS 304GB               | 1         | 0.87%   |
| Seagate ST320LM001 HN-M320MBB 320GB     | 1         | 0.87%   |
| Seagate ST3160815A 160GB                | 1         | 0.87%   |
| Seagate ST3160813AS 160GB               | 1         | 0.87%   |
| Seagate ST2000DM006-2DM164 2TB          | 1         | 0.87%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor          | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| WDC             | 17        | 24     | 36.17%  |
| Seagate         | 13        | 20     | 27.66%  |
| Toshiba         | 5         | 5      | 10.64%  |
| Hitachi         | 4         | 4      | 8.51%   |
| Fujitsu         | 3         | 3      | 6.38%   |
| SABRENT         | 1         | 2      | 2.13%   |
| MAXTOR          | 1         | 1      | 2.13%   |
| IBM/Hitachi     | 1         | 1      | 2.13%   |
| HGST            | 1         | 1      | 2.13%   |
| Hewlett-Packard | 1         | 2      | 2.13%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 7      | 15.79%  |
| Kingston            | 6         | 6      | 15.79%  |
| WDC                 | 3         | 4      | 7.89%   |
| PNY                 | 3         | 3      | 7.89%   |
| Netac               | 2         | 2      | 5.26%   |
| DOGFISH             | 2         | 2      | 5.26%   |
| Crucial             | 2         | 2      | 5.26%   |
| A-DATA Technology   | 2         | 2      | 5.26%   |
| Union Memory        | 1         | 2      | 2.63%   |
| Transcend           | 1         | 2      | 2.63%   |
| Teclast             | 1         | 1      | 2.63%   |
| Team                | 1         | 1      | 2.63%   |
| SMART               | 1         | 1      | 2.63%   |
| SanDisk             | 1         | 1      | 2.63%   |
| Patriot             | 1         | 1      | 2.63%   |
| Micron Technology   | 1         | 1      | 2.63%   |
| LITEON              | 1         | 2      | 2.63%   |
| Kston               | 1         | 1      | 2.63%   |
| KingDian            | 1         | 1      | 2.63%   |
| GOODRAM             | 1         | 1      | 2.63%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 40        | 63     | 43.48%  |
| SSD  | 35        | 43     | 38.04%  |
| NVMe | 11        | 18     | 11.96%  |
| MMC  | 6         | 8      | 6.52%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 59        | 98     | 73.75%  |
| NVMe | 11        | 18     | 13.75%  |
| MMC  | 6         | 8      | 7.5%    |
| SAS  | 4         | 8      | 5%      |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 48        | 71     | 67.61%  |
| 0.51-1.0   | 15        | 22     | 21.13%  |
| 1.01-2.0   | 6         | 11     | 8.45%   |
| 3.01-4.0   | 2         | 2      | 2.82%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 16        | 22.22%  |
| 101-250        | 14        | 19.44%  |
| 1001-2000      | 11        | 15.28%  |
| 21-50          | 8         | 11.11%  |
| 501-1000       | 6         | 8.33%   |
| 51-100         | 5         | 6.94%   |
| Unknown        | 5         | 6.94%   |
| 1-20           | 3         | 4.17%   |
| More than 3000 | 2         | 2.78%   |
| 2001-3000      | 2         | 2.78%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 101-250   | 19        | 26.39%  |
| 1-20      | 18        | 25%     |
| 21-50     | 8         | 11.11%  |
| 51-100    | 7         | 9.72%   |
| 1001-2000 | 6         | 8.33%   |
| 501-1000  | 6         | 8.33%   |
| Unknown   | 5         | 6.94%   |
| 251-500   | 3         | 4.17%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD5000BPVT-24HXZT3 500GB      | 2         | 2      | 14.29%  |
| WDC WD5000LPVX-00V0TT0 500GB      | 1         | 1      | 7.14%   |
| WDC WD3200BEVT-22A23T0 320GB      | 1         | 1      | 7.14%   |
| WDC WD10EARX-00N0YB0 1TB          | 1         | 1      | 7.14%   |
| Toshiba MQ04ABF100 1TB            | 1         | 1      | 7.14%   |
| Toshiba MQ02ABF100 1TB            | 1         | 1      | 7.14%   |
| MAXTOR 6E040L0 41GB               | 1         | 1      | 7.14%   |
| Kingston SA400S37120G 120GB SSD   | 1         | 1      | 7.14%   |
| Hitachi HTS727575A9E364 752GB     | 1         | 1      | 7.14%   |
| Hitachi HTS726060M9AT00 56GB      | 1         | 1      | 7.14%   |
| Hitachi HDS721616PLA380 160GB     | 1         | 1      | 7.14%   |
| Hewlett-Packard VB0250EAVER 250GB | 1         | 2      | 7.14%   |
| Fujitsu MHV2060BH PL 64GB         | 1         | 1      | 7.14%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor          | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| WDC             | 5         | 5      | 35.71%  |
| Hitachi         | 3         | 3      | 21.43%  |
| Toshiba         | 2         | 2      | 14.29%  |
| MAXTOR          | 1         | 1      | 7.14%   |
| Kingston        | 1         | 1      | 7.14%   |
| Hewlett-Packard | 1         | 2      | 7.14%   |
| Fujitsu         | 1         | 1      | 7.14%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor          | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| WDC             | 5         | 5      | 38.46%  |
| Hitachi         | 3         | 3      | 23.08%  |
| Toshiba         | 2         | 2      | 15.38%  |
| MAXTOR          | 1         | 1      | 7.69%   |
| Hewlett-Packard | 1         | 2      | 7.69%   |
| Fujitsu         | 1         | 1      | 7.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 13        | 14     | 92.86%  |
| SSD  | 1         | 1      | 7.14%   |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 48        | 87     | 59.26%  |
| Detected | 20        | 30     | 24.69%  |
| Malfunc  | 13        | 15     | 16.05%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 51        | 64.56%  |
| AMD                              | 10        | 12.66%  |
| Samsung Electronics              | 3         | 3.8%    |
| Kingston Technology Company      | 3         | 3.8%    |
| SK Hynix                         | 2         | 2.53%   |
| Micron/Crucial Technology        | 2         | 2.53%   |
| VIA Technologies                 | 1         | 1.27%   |
| Silicon Integrated Systems [SiS] | 1         | 1.27%   |
| Nvidia                           | 1         | 1.27%   |
| Marvell Technology Group         | 1         | 1.27%   |
| KIOXIA                           | 1         | 1.27%   |
| Broadcom / LSI                   | 1         | 1.27%   |
| ASMedia Technology               | 1         | 1.27%   |
| Adaptec                          | 1         | 1.27%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                  | Computers | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 6         | 6.52%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 5         | 5.43%   |
| Kingston Company A2000 NVMe SSD                                                        | 3         | 3.26%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 3         | 3.26%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                      | 3         | 3.26%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 3         | 3.26%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 3         | 3.26%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]           | 3         | 3.26%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 3         | 3.26%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 3         | 3.26%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 3         | 3.26%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                        | 2         | 2.17%   |
| Intel SATA Controller [RAID mode]                                                      | 2         | 2.17%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 2         | 2.17%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                             | 2         | 2.17%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 2         | 2.17%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 2         | 2.17%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                                 | 2         | 2.17%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 2         | 2.17%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 2         | 2.17%   |
| VIA VT6421 IDE/SATA Controller                                                         | 1         | 1.09%   |
| SK Hynix Non-Volatile memory controller                                                | 1         | 1.09%   |
| SK Hynix BC511                                                                         | 1         | 1.09%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                            | 1         | 1.09%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                   | 1         | 1.09%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 1         | 1.09%   |
| Samsung NVMe SSD Controller SM951/PM951                                                | 1         | 1.09%   |
| Samsung NVMe SSD Controller 980                                                        | 1         | 1.09%   |
| Nvidia MCP79 SATA Controller                                                           | 1         | 1.09%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                       | 1         | 1.09%   |
| KIOXIA Non-Volatile memory controller                                                  | 1         | 1.09%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                | 1         | 1.09%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 1         | 1.09%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 1         | 1.09%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                   | 1         | 1.09%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 1         | 1.09%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 1         | 1.09%   |
| Intel 82801FBM (ICH6M) SATA Controller                                                 | 1         | 1.09%   |
| Intel 82801EB/ER (ICH5/ICH5R) IDE Controller                                           | 1         | 1.09%   |
| Intel 82801BA IDE U100 Controller                                                      | 1         | 1.09%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 1         | 1.09%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 1.09%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 1.09%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller          | 1         | 1.09%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 1         | 1.09%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                          | 1         | 1.09%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                          | 1         | 1.09%   |
| Broadcom / LSI SAS1068E PCI-Express Fusion-MPT SAS                                     | 1         | 1.09%   |
| ASMedia ASM1062 Serial ATA Controller                                                  | 1         | 1.09%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                   | 1         | 1.09%   |
| AMD FCH SATA Controller [IDE mode]                                                     | 1         | 1.09%   |
| AMD FCH SATA Controller D                                                              | 1         | 1.09%   |
| AMD FCH IDE Controller                                                                 | 1         | 1.09%   |
| AMD 400 Series Chipset SATA Controller                                                 | 1         | 1.09%   |
| AMD 300 Series Chipset SATA Controller                                                 | 1         | 1.09%   |
| Adaptec AIC-7870P/7881U [AHA-2940U/UW/D/S76]                                           | 1         | 1.09%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 45        | 57.69%  |
| IDE  | 16        | 20.51%  |
| NVMe | 11        | 14.1%   |
| RAID | 5         | 6.41%   |
| SCSI | 1         | 1.28%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 57        | 83.82%  |
| AMD    | 10        | 14.71%  |
| ARM    | 1         | 1.47%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel Core i5-5300U CPU @ 2.30GHz            | 3         | 4.35%   |
| Intel Core i5-9400F CPU @ 2.90GHz            | 2         | 2.9%    |
| Intel Core i5-6400 CPU @ 2.70GHz             | 2         | 2.9%    |
| Intel Core i5-6300U CPU @ 2.40GHz            | 2         | 2.9%    |
| Intel Core i5-3320M CPU @ 2.60GHz            | 2         | 2.9%    |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz         | 2         | 2.9%    |
| AMD Ryzen 5 1600 Six-Core Processor          | 2         | 2.9%    |
| Intel Xeon CPU X3460 @ 2.80GHz               | 1         | 1.45%   |
| Intel Xeon CPU E3-1270 V2 @ 3.50GHz          | 1         | 1.45%   |
| Intel Xeon CPU E3-1226 v3 @ 3.30GHz          | 1         | 1.45%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz     | 1         | 1.45%   |
| Intel Pentium M processor 1700MHz            | 1         | 1.45%   |
| Intel Pentium M processor 1.60GHz            | 1         | 1.45%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz  | 1         | 1.45%   |
| Intel Pentium Dual-Core CPU E6300 @ 2.80GHz  | 1         | 1.45%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz       | 1         | 1.45%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz       | 1         | 1.45%   |
| Intel Pentium CPU P6100 @ 2.00GHz            | 1         | 1.45%   |
| Intel Pentium CPU G3240 @ 3.10GHz            | 1         | 1.45%   |
| Intel Pentium 4 CPU 3.00GHz                  | 1         | 1.45%   |
| Intel Core i9-8950HK CPU @ 2.90GHz           | 1         | 1.45%   |
| Intel Core i9-10850K CPU @ 3.60GHz           | 1         | 1.45%   |
| Intel Core i7-9850H CPU @ 2.60GHz            | 1         | 1.45%   |
| Intel Core i7-8565U CPU @ 1.80GHz            | 1         | 1.45%   |
| Intel Core i7-4600U CPU @ 2.10GHz            | 1         | 1.45%   |
| Intel Core i7-3770 CPU @ 3.40GHz             | 1         | 1.45%   |
| Intel Core i7-3610QM CPU @ 2.30GHz           | 1         | 1.45%   |
| Intel Core i7-2640M CPU @ 2.80GHz            | 1         | 1.45%   |
| Intel Core i7-10510U CPU @ 1.80GHz           | 1         | 1.45%   |
| Intel Core i5-4590T CPU @ 2.00GHz            | 1         | 1.45%   |
| Intel Core i5-3470 CPU @ 3.20GHz             | 1         | 1.45%   |
| Intel Core i5-2500K CPU @ 3.30GHz            | 1         | 1.45%   |
| Intel Core i5-2500 CPU @ 3.30GHz             | 1         | 1.45%   |
| Intel Core i5-2410M CPU @ 2.30GHz            | 1         | 1.45%   |
| Intel Core i5-10310U CPU @ 1.70GHz           | 1         | 1.45%   |
| Intel Core i3-2350M CPU @ 2.30GHz            | 1         | 1.45%   |
| Intel Core i3-10110U CPU @ 2.10GHz           | 1         | 1.45%   |
| Intel Core i3 CPU M 380 @ 2.53GHz            | 1         | 1.45%   |
| Intel Core i3 CPU M 370 @ 2.40GHz            | 1         | 1.45%   |
| Intel Core i3 CPU M 330 @ 2.13GHz            | 1         | 1.45%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz        | 1         | 1.45%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz         | 1         | 1.45%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz         | 1         | 1.45%   |
| Intel Core 2 CPU T7200 @ 2.00GHz             | 1         | 1.45%   |
| Intel Core 2 CPU T5600 @ 1.83GHz             | 1         | 1.45%   |
| Intel Core 2 CPU P8600 @ 2.40GHz             | 1         | 1.45%   |
| Intel Celeron N4100 CPU @ 1.10GHz            | 1         | 1.45%   |
| Intel Celeron M processor 1.40GHz            | 1         | 1.45%   |
| Intel Celeron CPU N2830 @ 2.16GHz            | 1         | 1.45%   |
| Intel Celeron CPU J1900 @ 1.99GHz            | 1         | 1.45%   |
| Intel Celeron (Coppermine)                   | 1         | 1.45%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz            | 1         | 1.45%   |
| ARM Nokia RX-51 board Processor              | 1         | 1.45%   |
| AMD Sempron Processor 2800+                  | 1         | 1.45%   |
| AMD Ryzen 5 3600 6-Core Processor            | 1         | 1.45%   |
| AMD FX-8300 Eight-Core Processor             | 1         | 1.45%   |
| AMD E2-1800 APU with Radeon HD Graphics      | 1         | 1.45%   |
| AMD E-300 APU with Radeon HD Graphics        | 1         | 1.45%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G | 1         | 1.45%   |
| AMD A6-4400M APU with Radeon HD Graphics     | 1         | 1.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 17        | 24.64%  |
| Intel Core i7           | 7         | 10.14%  |
| Intel Core i3           | 5         | 7.25%   |
| Intel Core 2 Duo        | 4         | 5.8%    |
| Intel Celeron           | 4         | 5.8%    |
| Intel Xeon              | 3         | 4.35%   |
| Intel Core 2            | 3         | 4.35%   |
| AMD Ryzen 5             | 3         | 4.35%   |
| Other                   | 2         | 2.9%    |
| Intel Pentium M         | 2         | 2.9%    |
| Intel Pentium Dual-Core | 2         | 2.9%    |
| Intel Pentium Dual      | 2         | 2.9%    |
| Intel Pentium           | 2         | 2.9%    |
| Intel Core i9           | 2         | 2.9%    |
| Intel Pentium Silver    | 1         | 1.45%   |
| Intel Pentium 4         | 1         | 1.45%   |
| Intel Core 2 Quad       | 1         | 1.45%   |
| Intel Celeron M         | 1         | 1.45%   |
| Intel Atom              | 1         | 1.45%   |
| AMD Sempron             | 1         | 1.45%   |
| AMD FX                  | 1         | 1.45%   |
| AMD E2                  | 1         | 1.45%   |
| AMD E                   | 1         | 1.45%   |
| AMD A6                  | 1         | 1.45%   |
| AMD A4                  | 1         | 1.45%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 32        | 47.06%  |
| 4      | 20        | 29.41%  |
| 1      | 8         | 11.76%  |
| 6      | 7         | 10.29%  |
| 10     | 1         | 1.47%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 68        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 38        | 55.88%  |
| 2      | 30        | 44.12%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 61        | 89.71%  |
| 32-bit         | 4         | 5.88%   |
| Unknown        | 3         | 4.41%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 16        | 22.86%  |
| 0x206a7    | 5         | 7.14%   |
| 0x1067a    | 5         | 7.14%   |
| 0x806ec    | 4         | 5.71%   |
| 0x306a9    | 4         | 5.71%   |
| 0x906ea    | 3         | 4.29%   |
| 0x306d4    | 3         | 4.29%   |
| 0x706a1    | 2         | 2.86%   |
| 0x6f6      | 2         | 2.86%   |
| 0x406e3    | 2         | 2.86%   |
| 0x306c3    | 2         | 2.86%   |
| 0x20655    | 2         | 2.86%   |
| 0xf49      | 1         | 1.43%   |
| 0xa0655    | 1         | 1.43%   |
| 0x906ed    | 1         | 1.43%   |
| 0x6fd      | 1         | 1.43%   |
| 0x6d8      | 1         | 1.43%   |
| 0x695      | 1         | 1.43%   |
| 0x686      | 1         | 1.43%   |
| 0x506e3    | 1         | 1.43%   |
| 0x406c4    | 1         | 1.43%   |
| 0x40651    | 1         | 1.43%   |
| 0x30678    | 1         | 1.43%   |
| 0x20652    | 1         | 1.43%   |
| 0x106e5    | 1         | 1.43%   |
| 0x10676    | 1         | 1.43%   |
| 0x08701013 | 1         | 1.43%   |
| 0x08001138 | 1         | 1.43%   |
| 0x08001129 | 1         | 1.43%   |
| 0x05000119 | 1         | 1.43%   |
| 0x05000101 | 1         | 1.43%   |
| 0x03000027 | 1         | 1.43%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 8         | 11.76%  |
| Penryn        | 7         | 10.29%  |
| IvyBridge     | 6         | 8.82%   |
| SandyBridge   | 5         | 7.35%   |
| Westmere      | 4         | 5.88%   |
| Skylake       | 4         | 5.88%   |
| P6            | 4         | 5.88%   |
| Haswell       | 4         | 5.88%   |
| Core          | 4         | 5.88%   |
| Silvermont    | 3         | 4.41%   |
| Broadwell     | 3         | 4.41%   |
| Zen           | 2         | 2.94%   |
| Piledriver    | 2         | 2.94%   |
| Goldmont plus | 2         | 2.94%   |
| Bobcat        | 2         | 2.94%   |
| Zen 2         | 1         | 1.47%   |
| NetBurst      | 1         | 1.47%   |
| Nehalem       | 1         | 1.47%   |
| K8 Hammer     | 1         | 1.47%   |
| K10 Llano     | 1         | 1.47%   |
| Excavator     | 1         | 1.47%   |
| CometLake     | 1         | 1.47%   |
| Unknown       | 1         | 1.47%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 39        | 54.93%  |
| AMD                              | 16        | 22.54%  |
| Nvidia                           | 15        | 21.13%  |
| Silicon Integrated Systems [SiS] | 1         | 1.41%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 5.33%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 4         | 5.33%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 3         | 4%      |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 4%      |
| Intel HD Graphics 5500                                                                   | 3         | 4%      |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 4%      |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 4%      |
| Nvidia G96CGL [Quadro FX 580]                                                            | 2         | 2.67%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 2.67%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 2.67%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 2.67%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1         | 1.33%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 1         | 1.33%   |
| Nvidia GP107M [GeForce MX150]                                                            | 1         | 1.33%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 1.33%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 1.33%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 1         | 1.33%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1         | 1.33%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                                        | 1         | 1.33%   |
| Nvidia GF108M [GeForce GT 635M]                                                          | 1         | 1.33%   |
| Nvidia GA104 [GeForce RTX 3060 Ti]                                                       | 1         | 1.33%   |
| Nvidia C79 [GeForce 9400]                                                                | 1         | 1.33%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1         | 1.33%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 1.33%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 1.33%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 1.33%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1         | 1.33%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 1.33%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 1         | 1.33%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 1.33%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1         | 1.33%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.33%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.33%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1         | 1.33%   |
| Intel 82852/855GM Integrated Graphics Device                                             | 1         | 1.33%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 1         | 1.33%   |
| AMD Wrestler [Radeon HD 7340]                                                            | 1         | 1.33%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 1         | 1.33%   |
| AMD Trinity 2 [Radeon HD 7520G]                                                          | 1         | 1.33%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1         | 1.33%   |
| AMD RV380/M24 [Mobility Radeon X600]                                                     | 1         | 1.33%   |
| AMD RV350/M10 GL [Mobility FireGL T2]                                                    | 1         | 1.33%   |
| AMD RV350 [Radeon 9550] (Secondary)                                                      | 1         | 1.33%   |
| AMD RV350 [Radeon 9550]                                                                  | 1         | 1.33%   |
| AMD RV100 [Radeon 7000 / Radeon VE]                                                      | 1         | 1.33%   |
| AMD RS780L [Radeon 3000]                                                                 | 1         | 1.33%   |
| AMD R520/M58 [Mobility Radeon X1800]                                                     | 1         | 1.33%   |
| AMD R350 [Radeon 9800 Series]                                                            | 1         | 1.33%   |
| AMD R350 [Radeon 9800 PRO] (Secondary)                                                   | 1         | 1.33%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 1         | 1.33%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 1         | 1.33%   |
| AMD Curacao XT / Trinidad XT [Radeon R7 370 / R9 270X/370X]                              | 1         | 1.33%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 1         | 1.33%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 1         | 1.33%   |
| AMD Baffin [Radeon Pro WX 4130/4150]                                                     | 1         | 1.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 33        | 48.53%  |
| 1 x AMD        | 14        | 20.59%  |
| 1 x Nvidia     | 13        | 19.12%  |
| Other          | 2         | 2.94%   |
| Intel + Nvidia | 2         | 2.94%   |
| 2 x Intel      | 1         | 1.47%   |
| 2 x AMD        | 1         | 1.47%   |
| 1 x SiS        | 1         | 1.47%   |
| Intel + AMD    | 1         | 1.47%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 58        | 84.06%  |
| Proprietary | 9         | 13.04%  |
| Unknown     | 2         | 2.9%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 40        | 57.97%  |
| 0.01-0.5   | 12        | 17.39%  |
| 3.01-4.0   | 4         | 5.8%    |
| 0.51-1.0   | 4         | 5.8%    |
| 2.01-3.0   | 3         | 4.35%   |
| 1.01-2.0   | 3         | 4.35%   |
| 7.01-8.0   | 2         | 2.9%    |
| 5.01-6.0   | 1         | 1.45%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 14        | 19.44%  |
| LG Display              | 10        | 13.89%  |
| AU Optronics            | 6         | 8.33%   |
| Goldstar                | 5         | 6.94%   |
| Lenovo                  | 4         | 5.56%   |
| Hewlett-Packard         | 4         | 5.56%   |
| Philips                 | 3         | 4.17%   |
| AOC                     | 3         | 4.17%   |
| PANDA                   | 2         | 2.78%   |
| Iiyama                  | 2         | 2.78%   |
| Dell                    | 2         | 2.78%   |
| Chimei Innolux          | 2         | 2.78%   |
| Chi Mei Optoelectronics | 2         | 2.78%   |
| BOE                     | 2         | 2.78%   |
| Acer                    | 2         | 2.78%   |
| ViewSonic               | 1         | 1.39%   |
| Toshiba                 | 1         | 1.39%   |
| STD                     | 1         | 1.39%   |
| InnoLux Display         | 1         | 1.39%   |
| HJW                     | 1         | 1.39%   |
| Hisense                 | 1         | 1.39%   |
| Eizo                    | 1         | 1.39%   |
| CVT                     | 1         | 1.39%   |
| Ancor Communications    | 1         | 1.39%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SyncMaster SAM0091 1600x1200 432x324mm 21.3-inch     | 2         | 2.63%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 2         | 2.63%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 2         | 2.63%   |
| ViewSonic VA2261 VSC0F30 1920x1080 477x268mm 21.5-inch                   | 1         | 1.32%   |
| Toshiba TV TSB0209 1920x1080 1594x900mm 72.1-inch                        | 1         | 1.32%   |
| STD STD HDMI TV STD00C7 1920x1080 698x392mm 31.5-inch                    | 1         | 1.32%   |
| Samsung Electronics T24B301 SAM098E 1920x1080 521x293mm 23.5-inch        | 1         | 1.32%   |
| Samsung Electronics SyncMaster SAM0029 1280x1024 312x234mm 15.4-inch     | 1         | 1.32%   |
| Samsung Electronics S24D340 SAM0BBB 1920x1080 531x299mm 24.0-inch        | 1         | 1.32%   |
| Samsung Electronics S/T 77/76BDF STN0007 1280x1024 312x234mm 15.4-inch   | 1         | 1.32%   |
| Samsung Electronics LCD Monitor SyncMaster 1280x1024                     | 1         | 1.32%   |
| Samsung Electronics LCD Monitor SyncMaster                               | 1         | 1.32%   |
| Samsung Electronics LCD Monitor SEC4545 1280x800 331x207mm 15.4-inch     | 1         | 1.32%   |
| Samsung Electronics LCD Monitor SEC4151 1366x768 344x194mm 15.5-inch     | 1         | 1.32%   |
| Samsung Electronics LCD Monitor SDC4851 1366x768 344x194mm 15.5-inch     | 1         | 1.32%   |
| Samsung Electronics LCD Monitor SDC3853 2736x1824 260x173mm 12.3-inch    | 1         | 1.32%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 1020x570mm 46.0-inch   | 1         | 1.32%   |
| Samsung Electronics LCD Monitor SA300/350/360                            | 1         | 1.32%   |
| Samsung Electronics LCD Monitor S24D340                                  | 1         | 1.32%   |
| Samsung Electronics LCD Monitor C27F390 5760x1080                        | 1         | 1.32%   |
| Samsung Electronics C27F398 SAM0D45 1920x1080 600x340mm 27.2-inch        | 1         | 1.32%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch                  | 1         | 1.32%   |
| Philips 190B PHL086C 1280x1024 376x301mm 19.0-inch                       | 1         | 1.32%   |
| Philips 17S PHL0877 1280x1024 337x270mm 17.0-inch                        | 1         | 1.32%   |
| PANDA LM133LF5L01 NCP0020 1920x1080 294x165mm 13.3-inch                  | 1         | 1.32%   |
| PANDA LCD Monitor NCP002E 1920x1080 344x194mm 15.5-inch                  | 1         | 1.32%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch            | 1         | 1.32%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch             | 1         | 1.32%   |
| LG Display LCD Monitor LGD0540 1920x1080 344x194mm 15.5-inch             | 1         | 1.32%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 1         | 1.32%   |
| LG Display LCD Monitor LGD0450 1366x768 277x156mm 12.5-inch              | 1         | 1.32%   |
| LG Display LCD Monitor LGD03A3 1366x768 277x156mm 12.5-inch              | 1         | 1.32%   |
| LG Display LCD Monitor LGD0386 1366x768 309x174mm 14.0-inch              | 1         | 1.32%   |
| LG Display LCD Monitor LGD02C0 1366x768 293x165mm 13.2-inch              | 1         | 1.32%   |
| Lenovo LI2215sD LEN65CC 1920x1080 476x267mm 21.5-inch                    | 1         | 1.32%   |
| Lenovo LCD Monitor LEN40A0 1366x768 309x174mm 14.0-inch                  | 1         | 1.32%   |
| Lenovo LCD Monitor LEN4010 1280x800 261x163mm 12.1-inch                  | 1         | 1.32%   |
| Lenovo LCD Monitor LEN4000 1024x768 246x185mm 12.1-inch                  | 1         | 1.32%   |
| InnoLux Display LCD Monitor INL000A 1366x768 344x194mm 15.5-inch         | 1         | 1.32%   |
| Iiyama PLX2483H IVM6114 1920x1080 531x299mm 24.0-inch                    | 1         | 1.32%   |
| Iiyama PLB2712HDS IVM6602 1920x1080 598x336mm 27.0-inch                  | 1         | 1.32%   |
| HJW HDMI TO USB HJW0001 1920x1080 700x390mm 31.5-inch                    | 1         | 1.32%   |
| Hisense Hisense HSE4000 1920x1080 591x355mm 27.1-inch                    | 1         | 1.32%   |
| Hewlett-Packard LA2206 HWP2947 1920x1080 476x268mm 21.5-inch             | 1         | 1.32%   |
| Hewlett-Packard L2245w HWP26FC 1680x1050 470x300mm 22.0-inch             | 1         | 1.32%   |
| Hewlett-Packard Compaq S2321a HWP2915 1920x1080 509x286mm 23.0-inch      | 1         | 1.32%   |
| Hewlett-Packard 24y HPN3504 1920x1080 528x297mm 23.9-inch                | 1         | 1.32%   |
| Hewlett-Packard 22cwa HWP3183 1920x1080 476x268mm 21.5-inch              | 1         | 1.32%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                  | 1         | 1.32%   |
| Goldstar L1730S GSM438D 1280x1024 338x270mm 17.0-inch                    | 1         | 1.32%   |
| Goldstar E2260 GSM57E0 1920x1080 477x268mm 21.5-inch                     | 1         | 1.32%   |
| Eizo EV2456 ENC2798 1920x1200 520x330mm 24.2-inch                        | 1         | 1.32%   |
| Dell P2415Q DELA0BE 2048x1280 530x300mm 24.0-inch                        | 1         | 1.32%   |
| Dell LCD Monitor P1914S 1280x1024                                        | 1         | 1.32%   |
| CVT LCD Monitor CVT4668 1440x900 360x290mm 18.2-inch                     | 1         | 1.32%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 1         | 1.32%   |
| Chimei Innolux LCD Monitor CMN1118 1366x768 256x144mm 11.6-inch          | 1         | 1.32%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch | 1         | 1.32%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 1         | 1.32%   |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                    | 1         | 1.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 28        | 38.89%  |
| 1366x768 (WXGA)    | 21        | 29.17%  |
| 3840x2160 (4K)     | 6         | 8.33%   |
| 1280x1024 (SXGA)   | 5         | 6.94%   |
| 1600x1200          | 2         | 2.78%   |
| 1440x900 (WXGA+)   | 2         | 2.78%   |
| 1280x800 (WXGA)    | 2         | 2.78%   |
| Unknown            | 2         | 2.78%   |
| 5760x1080          | 1         | 1.39%   |
| 2736x1824          | 1         | 1.39%   |
| 1920x1200 (WUXGA)  | 1         | 1.39%   |
| 1680x1050 (WSXGA+) | 1         | 1.39%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 17        | 23.94%  |
| 21      | 12        | 16.9%   |
| 12      | 7         | 9.86%   |
| 24      | 5         | 7.04%   |
| 27      | 4         | 5.63%   |
| 14      | 4         | 5.63%   |
| 31      | 3         | 4.23%   |
| 23      | 3         | 4.23%   |
| 18      | 3         | 4.23%   |
| 17      | 3         | 4.23%   |
| 13      | 3         | 4.23%   |
| Unknown | 2         | 2.82%   |
| 72      | 1         | 1.41%   |
| 54      | 1         | 1.41%   |
| 22      | 1         | 1.41%   |
| 19      | 1         | 1.41%   |
| 11      | 1         | 1.41%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 22        | 32.35%  |
| 401-500     | 13        | 19.12%  |
| 501-600     | 12        | 17.65%  |
| 201-300     | 11        | 16.18%  |
| 601-700     | 3         | 4.41%   |
| 351-400     | 3         | 4.41%   |
| Unknown     | 2         | 2.94%   |
| 1501-2000   | 1         | 1.47%   |
| 1001-1500   | 1         | 1.47%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 47        | 74.6%   |
| 16/10   | 5         | 7.94%   |
| 4/3     | 4         | 6.35%   |
| 5/4     | 3         | 4.76%   |
| Unknown | 2         | 3.17%   |
| 6/5     | 1         | 1.59%   |
| 3/2     | 1         | 1.59%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 15        | 21.43%  |
| 101-110        | 15        | 21.43%  |
| 61-70          | 7         | 10%     |
| 151-200        | 6         | 8.57%   |
| 81-90          | 4         | 5.71%   |
| 301-350        | 4         | 5.71%   |
| 141-150        | 4         | 5.71%   |
| 71-80          | 3         | 4.29%   |
| 351-500        | 3         | 4.29%   |
| More than 1000 | 2         | 2.86%   |
| 111-120        | 2         | 2.86%   |
| Unknown        | 2         | 2.86%   |
| 51-60          | 1         | 1.43%   |
| 251-300        | 1         | 1.43%   |
| 131-140        | 1         | 1.43%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 24        | 34.78%  |
| 51-100        | 23        | 33.33%  |
| 121-160       | 13        | 18.84%  |
| 161-240       | 4         | 5.8%    |
| 1-50          | 2         | 2.9%    |
| Unknown       | 2         | 2.9%    |
| More than 240 | 1         | 1.45%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 56        | 81.16%  |
| 2     | 9         | 13.04%  |
| 3     | 3         | 4.35%   |
| 0     | 1         | 1.45%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 33        | 33.67%  |
| Intel                            | 28        | 28.57%  |
| Qualcomm Atheros                 | 17        | 17.35%  |
| Ralink Technology                | 3         | 3.06%   |
| Marvell Technology Group         | 3         | 3.06%   |
| TP-Link                          | 2         | 2.04%   |
| NetGear                          | 2         | 2.04%   |
| JMicron Technology               | 2         | 2.04%   |
| Broadcom Limited                 | 2         | 2.04%   |
| VIA Technologies                 | 1         | 1.02%   |
| Silicon Integrated Systems [SiS] | 1         | 1.02%   |
| Samsung Electronics              | 1         | 1.02%   |
| Ralink                           | 1         | 1.02%   |
| Nvidia                           | 1         | 1.02%   |
| Broadcom                         | 1         | 1.02%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 23        | 20.35%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 6         | 5.31%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 4         | 3.54%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 3         | 2.65%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 2.65%   |
| Intel Wireless 7265                                                     | 3         | 2.65%   |
| Intel Ethernet Connection (3) I218-LM                                   | 3         | 2.65%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.77%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 2         | 1.77%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 2         | 1.77%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.77%   |
| NetGear WG111v3 54 Mbps Wireless [realtek RTL8187B]                     | 2         | 1.77%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 2         | 1.77%   |
| Intel Wireless 7260                                                     | 2         | 1.77%   |
| Intel Ethernet Connection (7) I219-LM                                   | 2         | 1.77%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 1.77%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 1.77%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller       | 2         | 1.77%   |
| VIA VT6105/VT6106S [Rhine-III]                                          | 1         | 0.88%   |
| TP-Link USB 10/100/1000 LAN                                             | 1         | 0.88%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 0.88%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 1         | 0.88%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 1         | 0.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.88%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                         | 1         | 0.88%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 1         | 0.88%   |
| Ralink RT5372 Wireless Adapter                                          | 1         | 0.88%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 0.88%   |
| Ralink MT7601U Wireless Adapter                                         | 1         | 0.88%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.88%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 0.88%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 1         | 0.88%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.88%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.88%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 0.88%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 1         | 0.88%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                              | 1         | 0.88%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 1         | 0.88%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter              | 1         | 0.88%   |
| Nvidia MCP79 Ethernet                                                   | 1         | 0.88%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                       | 1         | 0.88%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                 | 1         | 0.88%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                       | 1         | 0.88%   |
| Intel Wireless 8260                                                     | 1         | 0.88%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 0.88%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 1         | 0.88%   |
| Intel Ethernet Connection I217-LM                                       | 1         | 0.88%   |
| Intel Ethernet Connection (7) I219-V                                    | 1         | 0.88%   |
| Intel Ethernet Connection (6) I219-V                                    | 1         | 0.88%   |
| Intel Ethernet Connection (11) I219-V                                   | 1         | 0.88%   |
| Intel Ethernet Connection (10) I219-LM                                  | 1         | 0.88%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 0.88%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 0.88%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller        | 1         | 0.88%   |
| Intel 82579V Gigabit Network Connection                                 | 1         | 0.88%   |
| Intel 82578DM Gigabit Network Connection                                | 1         | 0.88%   |
| Intel 82573L Gigabit Ethernet Controller                                | 1         | 0.88%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)              | 1         | 0.88%   |
| Intel 82567LM Gigabit Network Connection                                | 1         | 0.88%   |
| Intel 82566DM-2 Gigabit Network Connection                              | 1         | 0.88%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Qualcomm Atheros         | 15        | 34.88%  |
| Intel                    | 14        | 32.56%  |
| Realtek Semiconductor    | 3         | 6.98%   |
| Ralink Technology        | 3         | 6.98%   |
| NetGear                  | 2         | 4.65%   |
| Broadcom Limited         | 2         | 4.65%   |
| TP-Link                  | 1         | 2.33%   |
| Ralink                   | 1         | 2.33%   |
| Marvell Technology Group | 1         | 2.33%   |
| Broadcom                 | 1         | 2.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 3         | 6.98%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 6.98%   |
| Intel Wireless 7265                                                     | 3         | 6.98%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 4.65%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 2         | 4.65%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 4.65%   |
| NetGear WG111v3 54 Mbps Wireless [realtek RTL8187B]                     | 2         | 4.65%   |
| Intel Wireless 7260                                                     | 2         | 4.65%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 4.65%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 4.65%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 2.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 2.33%   |
| Ralink RT5372 Wireless Adapter                                          | 1         | 2.33%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 2.33%   |
| Ralink MT7601U Wireless Adapter                                         | 1         | 2.33%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 2.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 2.33%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 2.33%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 2.33%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 2.33%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter              | 1         | 2.33%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                       | 1         | 2.33%   |
| Intel Wireless 8260                                                     | 1         | 2.33%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 2.33%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 1         | 2.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 2.33%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 2.33%   |
| Broadcom Limited BCM4321 802.11a/b/g/n                                  | 1         | 2.33%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 1         | 2.33%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 1         | 2.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 31        | 46.97%  |
| Intel                            | 22        | 33.33%  |
| Qualcomm Atheros                 | 4         | 6.06%   |
| Marvell Technology Group         | 2         | 3.03%   |
| JMicron Technology               | 2         | 3.03%   |
| VIA Technologies                 | 1         | 1.52%   |
| TP-Link                          | 1         | 1.52%   |
| Silicon Integrated Systems [SiS] | 1         | 1.52%   |
| Samsung Electronics              | 1         | 1.52%   |
| Nvidia                           | 1         | 1.52%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 23        | 34.33%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 8.96%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 5.97%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 4.48%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 2.99%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 2         | 2.99%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 2.99%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1         | 1.49%   |
| TP-Link USB 10/100/1000 LAN                                       | 1         | 1.49%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 1.49%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.49%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 1.49%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.49%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.49%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.49%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 1.49%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.49%   |
| Nvidia MCP79 Ethernet                                             | 1         | 1.49%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 1.49%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1         | 1.49%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.49%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.49%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.49%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 1.49%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 1.49%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 1.49%   |
| Intel 82578DM Gigabit Network Connection                          | 1         | 1.49%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 1.49%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)        | 1         | 1.49%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.49%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1         | 1.49%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                | 1         | 1.49%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 62        | 58.49%  |
| WiFi     | 41        | 38.68%  |
| Modem    | 3         | 2.83%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 43        | 57.33%  |
| WiFi     | 32        | 42.67%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 37        | 53.62%  |
| 1     | 27        | 39.13%  |
| 0     | 4         | 5.8%    |
| 5     | 1         | 1.45%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 65        | 95.59%  |
| Yes  | 3         | 4.41%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 9         | 39.13%  |
| Qualcomm Atheros Communications | 4         | 17.39%  |
| Cambridge Silicon Radio         | 2         | 8.7%    |
| Broadcom                        | 2         | 8.7%    |
| Realtek Semiconductor           | 1         | 4.35%   |
| Ralink                          | 1         | 4.35%   |
| Marvell Semiconductor           | 1         | 4.35%   |
| Lite-On Technology              | 1         | 4.35%   |
| IMC Networks                    | 1         | 4.35%   |
| Apple                           | 1         | 4.35%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 5         | 21.74%  |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 8.7%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 8.7%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 8.7%    |
| Realtek Bluetooth Radio                             | 1         | 4.35%   |
| Ralink RT3290 Bluetooth                             | 1         | 4.35%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 4.35%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 4.35%   |
| Marvell Bluetooth and Wireless LAN Composite        | 1         | 4.35%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 4.35%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 4.35%   |
| Intel AX201 Bluetooth                               | 1         | 4.35%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 4.35%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 4.35%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 4.35%   |
| Apple Bluetooth USB Host Controller                 | 1         | 4.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 52        | 57.14%  |
| AMD                              | 13        | 14.29%  |
| Nvidia                           | 12        | 13.19%  |
| Plantronics                      | 2         | 2.2%    |
| Creative Labs                    | 2         | 2.2%    |
| Texas Instruments                | 1         | 1.1%    |
| Silicon Integrated Systems [SiS] | 1         | 1.1%    |
| Realtek Semiconductor            | 1         | 1.1%    |
| M-Audio                          | 1         | 1.1%    |
| Logitech                         | 1         | 1.1%    |
| KORG                             | 1         | 1.1%    |
| GYROCOM C&C                      | 1         | 1.1%    |
| Cirrus Logic                     | 1         | 1.1%    |
| C-Media Electronics              | 1         | 1.1%    |
| Blue Microphones                 | 1         | 1.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7         | 6.73%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5         | 4.81%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5         | 4.81%   |
| Nvidia GP106 High Definition Audio Controller                              | 4         | 3.85%   |
| Intel Cannon Lake PCH cAVS                                                 | 4         | 3.85%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 3.85%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 3.85%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 2.88%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 2.88%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 2.88%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3         | 2.88%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 3         | 2.88%   |
| AMD FCH Azalia Controller                                                  | 3         | 2.88%   |
| Plantronics HD1                                                            | 2         | 1.92%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 1.92%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 1.92%   |
| Intel Sunrise Point-LP HD Audio                                            | 2         | 1.92%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.92%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 1.92%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 2         | 1.92%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]  | 2         | 1.92%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 2         | 1.92%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2         | 1.92%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2         | 1.92%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1         | 0.96%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 1         | 0.96%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.96%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 0.96%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.96%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.96%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1         | 0.96%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 0.96%   |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 0.96%   |
| M-Audio MIDISPORT 4x4 Anniv                                                | 1         | 0.96%   |
| M-Audio M-Audio 1x1                                                        | 1         | 0.96%   |
| Logitech H390 headset with microphone                                      | 1         | 0.96%   |
| KORG nanoKONTROL studio controller                                         | 1         | 0.96%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 0.96%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 0.96%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 0.96%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller           | 1         | 0.96%   |
| Intel 82801BA/BAM AC'97 Audio Controller                                   | 1         | 0.96%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 0.96%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 0.96%   |
| GYROCOM C&C Fiio E10                                                       | 1         | 0.96%   |
| Cirrus Logic Crystal CS4281 PCI Audio                                      | 1         | 0.96%   |
| C-Media Electronics CM106 Like Sound Device                                | 1         | 0.96%   |
| Blue Microphones Yeti Stereo Microphone                                    | 1         | 0.96%   |
| AMD Wrestler HDMI Audio                                                    | 1         | 0.96%   |
| AMD Trinity HDMI Audio Controller                                          | 1         | 0.96%   |
| AMD Starship/Matisse HD Audio Controller                                   | 1         | 0.96%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1         | 0.96%   |
| AMD High Definition Audio Controller                                       | 1         | 0.96%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1         | 0.96%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 1         | 0.96%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 17        | 23.94%  |
| Samsung Electronics | 13        | 18.31%  |
| Kingston            | 11        | 15.49%  |
| SK Hynix            | 7         | 9.86%   |
| G.Skill             | 4         | 5.63%   |
| Nanya Technology    | 3         | 4.23%   |
| Micron Technology   | 3         | 4.23%   |
| Crucial             | 3         | 4.23%   |
| Corsair             | 3         | 4.23%   |
| A-DATA Technology   | 3         | 4.23%   |
| Unknown (ABCD)      | 1         | 1.41%   |
| GOODRAM             | 1         | 1.41%   |
| Avant               | 1         | 1.41%   |
| Apacer              | 1         | 1.41%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB SODIMM DDR2                            | 2         | 2.5%    |
| Unknown RAM Module 1024MB SODIMM DDR                             | 2         | 2.5%    |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 2.5%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 2.5%    |
| Kingston RAM 99U5471-054.A00LF 8192MB DIMM DDR3 1600MT/s         | 2         | 2.5%    |
| Unknown RAM SM3S320SD0488CABC 8192MB SODIMM DDR3 1600MT/s        | 1         | 1.25%   |
| Unknown RAM Module 8192MB DIMM DDR3 800MT/s                      | 1         | 1.25%   |
| Unknown RAM Module 64MB DIMM DRAM 100MT/s                        | 1         | 1.25%   |
| Unknown RAM Module 512MB SODIMM DDR                              | 1         | 1.25%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 1         | 1.25%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                     | 1         | 1.25%   |
| Unknown RAM Module 256MB DIMM DRAM 100MT/s                       | 1         | 1.25%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 1.25%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                         | 1         | 1.25%   |
| Unknown RAM Module 2048MB DIMM SDRAM 667MT/s                     | 1         | 1.25%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 1         | 1.25%   |
| Unknown RAM Module 128MB DIMM DRAM 100MT/s                       | 1         | 1.25%   |
| Unknown RAM Module 1024MB SODIMM DDR2                            | 1         | 1.25%   |
| Unknown RAM Module 1024MB DIMM DDR 400MT/s                       | 1         | 1.25%   |
| Unknown RAM Module 1024MB DIMM DDR                               | 1         | 1.25%   |
| Unknown RAM BRAN51288G16C1600L 8GB DIMM DDR3 1600MT/s            | 1         | 1.25%   |
| Unknown RAM 3000 C16 Series 8192MB DIMM DDR4 2133MT/s            | 1         | 1.25%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 1.25%   |
| SK Hynix RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s          | 1         | 1.25%   |
| SK Hynix RAM Module 4GB DIMM DDR3 1333MT/s                       | 1         | 1.25%   |
| SK Hynix RAM Module 4096MB DIMM DDR3 1066MT/s                    | 1         | 1.25%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s             | 1         | 1.25%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.25%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4096MB SODIMM DDR3 1333MT/s        | 1         | 1.25%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4096MB SODIMM DDR4 2667MT/s        | 1         | 1.25%   |
| Samsung RAM Module 2GB DIMM DDR3 1333MT/s                        | 1         | 1.25%   |
| Samsung RAM Module 2048MB Row Of Chips LPDDR3 1867MT/s           | 1         | 1.25%   |
| Samsung RAM M471B5773DH0-CH9 2048MB SODIMM DDR3 1600MT/s         | 1         | 1.25%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 1         | 1.25%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s            | 1         | 1.25%   |
| Samsung RAM M471B5273EB0-CK0 4096MB SODIMM DDR3 4199MT/s         | 1         | 1.25%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.25%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 1         | 1.25%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.25%   |
| Samsung RAM M378B5273DH0-CH9 4096MB DIMM DDR3 2133MT/s           | 1         | 1.25%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s             | 1         | 1.25%   |
| Nanya RAM Module 2GB DIMM DDR3 1333MT/s                          | 1         | 1.25%   |
| Nanya RAM M2X4G64CB8HG5N-DG 4GB DIMM DDR3 1867MT/s               | 1         | 1.25%   |
| Micron RAM Module 2GB SODIMM DDR3 1067MT/s                       | 1         | 1.25%   |
| Micron RAM Module 2GB DIMM DDR3 1333MT/s                         | 1         | 1.25%   |
| Micron RAM 4ATF51264HZ-2G6E1 4096MB SODIMM DDR4 2667MT/s         | 1         | 1.25%   |
| Kingston RAM TSB1600D3S1ELD/4GE 4096MB SODIMM DDR3 1067MT/s      | 1         | 1.25%   |
| Kingston RAM KHYXPX-MIE 8GB SODIMM DDR4 2667MT/s                 | 1         | 1.25%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s           | 1         | 1.25%   |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 2667MT/s              | 1         | 1.25%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2400MT/s                | 1         | 1.25%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s              | 1         | 1.25%   |
| Kingston RAM ACR16D3LS1NGG/2G 2GB SODIMM DDR3 1333MT/s           | 1         | 1.25%   |
| Kingston RAM 99U5704-001.A00G 4GB SODIMM DDR4 2400MT/s           | 1         | 1.25%   |
| Kingston RAM 99U5471-066.A00LF 8GB DIMM DDR3 1600MT/s            | 1         | 1.25%   |
| Kingston RAM 9905711-015.A00G 4GB SODIMM DDR4 2400MT/s           | 1         | 1.25%   |
| Kingston RAM 9905625-066.A00G 16GB DIMM DDR4 2667MT/s            | 1         | 1.25%   |
| Kingston RAM 9905471-084.A00LF 8GB DIMM DDR3 1600MT/s            | 1         | 1.25%   |
| Kingston RAM 9905428-426.A00LF 8192MB SODIMM DDR3 1600MT/s       | 1         | 1.25%   |
| GOODRAM RAM GR1333D364L9/4G 4GB DIMM DDR3 1600MT/s               | 1         | 1.25%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 27        | 45.76%  |
| DDR4    | 16        | 27.12%  |
| SDRAM   | 4         | 6.78%   |
| DDR     | 4         | 6.78%   |
| DDR2    | 3         | 5.08%   |
| LPDDR3  | 2         | 3.39%   |
| LPDDR4  | 1         | 1.69%   |
| DRAM    | 1         | 1.69%   |
| Unknown | 1         | 1.69%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 31        | 53.45%  |
| DIMM         | 25        | 43.1%   |
| Row Of Chips | 2         | 3.45%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 20        | 28.99%  |
| 4096  | 16        | 23.19%  |
| 2048  | 16        | 23.19%  |
| 16384 | 6         | 8.7%    |
| 1024  | 5         | 7.25%   |
| 32768 | 2         | 2.9%    |
| 512   | 1         | 1.45%   |
| 256   | 1         | 1.45%   |
| 128   | 1         | 1.45%   |
| 64    | 1         | 1.45%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 12        | 19.05%  |
| 2667    | 10        | 15.87%  |
| 1333    | 7         | 11.11%  |
| Unknown | 6         | 9.52%   |
| 2400    | 4         | 6.35%   |
| 1067    | 4         | 6.35%   |
| 3600    | 3         | 4.76%   |
| 2133    | 3         | 4.76%   |
| 4199    | 2         | 3.17%   |
| 1867    | 2         | 3.17%   |
| 800     | 2         | 3.17%   |
| 667     | 2         | 3.17%   |
| 3200    | 1         | 1.59%   |
| 1800    | 1         | 1.59%   |
| 1334    | 1         | 1.59%   |
| 1066    | 1         | 1.59%   |
| 400     | 1         | 1.59%   |
| 100     | 1         | 1.59%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 1         | 33.33%  |
| Custom Engineering SPA | 1         | 33.33%  |
| Brother Industries     | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                           | Computers | Percent |
|---------------------------------|-----------|---------|
| HP Deskjet 1050 J410            | 1         | 33.33%  |
| Custom Engineering SPA KUBE USB | 1         | 33.33%  |
| Brother HL-L2375DW series       | 1         | 33.33%  |

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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 10        | 32.26%  |
| Sunplus Innovation Technology          | 3         | 9.68%   |
| Acer                                   | 3         | 9.68%   |
| Microdia                               | 2         | 6.45%   |
| Logitech                               | 2         | 6.45%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 6.45%   |
| Z-Star Microelectronics                | 1         | 3.23%   |
| Suyin                                  | 1         | 3.23%   |
| Softkinetic                            | 1         | 3.23%   |
| Samsung Electronics                    | 1         | 3.23%   |
| Mustek Systems                         | 1         | 3.23%   |
| MacroSilicon                           | 1         | 3.23%   |
| Lite-On Technology                     | 1         | 3.23%   |
| IMC Networks                           | 1         | 3.23%   |
| GEMBIRD                                | 1         | 3.23%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 4         | 12.9%   |
| Sunplus Integrated_Webcam_HD                     | 2         | 6.45%   |
| Acer Integrated Camera                           | 2         | 6.45%   |
| Z-Star Vimicro USB2.0 Camera                     | 1         | 3.23%   |
| Suyin Acer/HP Integrated Webcam [CN0314]         | 1         | 3.23%   |
| Sunplus Asus Webcam                              | 1         | 3.23%   |
| Softkinetic DepthSense 325                       | 1         | 3.23%   |
| Samsung Galaxy A5 (MTP)                          | 1         | 3.23%   |
| Mustek Systems USB 2.0 PC Camera                 | 1         | 3.23%   |
| Microdia WebCam SC-13HDL12639P                   | 1         | 3.23%   |
| Microdia 1.3 MPixel Integrated Webcam            | 1         | 3.23%   |
| MacroSilicon USB Video                           | 1         | 3.23%   |
| Logitech Webcam C270                             | 1         | 3.23%   |
| Logitech HD Pro Webcam C920                      | 1         | 3.23%   |
| Lite-On HP Wide Vision HD Camera                 | 1         | 3.23%   |
| IMC Networks Integrated Webcam                   | 1         | 3.23%   |
| GEMBIRD USB2.0 PC CAMERA                         | 1         | 3.23%   |
| Chicony WebCam                                   | 1         | 3.23%   |
| Chicony VGA WebCam                               | 1         | 3.23%   |
| Chicony Lenovo Integrated Camera (0.3MP)         | 1         | 3.23%   |
| Chicony Lenovo EasyCamera                        | 1         | 3.23%   |
| Chicony EasyCamera                               | 1         | 3.23%   |
| Chicony CNF9055 Toshiba Webcam                   | 1         | 3.23%   |
| Cheng Uei Precision Industry (Foxlink) Webcam    | 1         | 3.23%   |
| Cheng Uei Precision Industry (Foxlink) FM13FF-82 | 1         | 3.23%   |
| Acer BisonCam, NB Pro                            | 1         | 3.23%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Upek               | 1         | 33.33%  |
| Synaptics          | 1         | 33.33%  |
| STMicroelectronics | 1         | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 33.33%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 33.33%  |
| STMicroelectronics Fingerprint Reader                  | 1         | 33.33%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 3         | 75%     |
| Alcor Micro | 1         | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 1         | 25%     |
| Broadcom 5880                                  | 1         | 25%     |
| Broadcom 58200                                 | 1         | 25%     |
| Alcor Micro AU9540 Smartcard Reader            | 1         | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 57        | 82.61%  |
| 1     | 8         | 11.59%  |
| 3     | 2         | 2.9%    |
| 2     | 2         | 2.9%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 3         | 21.43%  |
| Graphics card            | 2         | 14.29%  |
| Communication controller | 2         | 14.29%  |
| Chipcard                 | 2         | 14.29%  |
| Net/wireless             | 1         | 7.14%   |
| Multimedia controller    | 1         | 7.14%   |
| Firewire controller      | 1         | 7.14%   |
| Camera                   | 1         | 7.14%   |
| Bluetooth                | 1         | 7.14%   |

