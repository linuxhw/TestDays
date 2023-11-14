CentOS 7 - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------

A project to collect tested hardware configurations for CentOS 7.

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

Total: 96

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | ZHAN 66 Pro A 14 G3         | [249f2a954a](https://linux-hardware.org/?probe=249f2a954a) | Nov 02, 2023 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | [6ffee2798a](https://linux-hardware.org/?probe=6ffee2798a) | Sep 08, 2023 |
| HP            | ProBook 650 G1              | [b0f558c0a2](https://linux-hardware.org/?probe=b0f558c0a2) | Aug 31, 2023 |
| HP            | ProBook 450 G3              | [90e7667180](https://linux-hardware.org/?probe=90e7667180) | Aug 02, 2023 |
| Dell          | System XPS L702X            | [21f1d68bc1](https://linux-hardware.org/?probe=21f1d68bc1) | Jul 21, 2023 |
| Acer          | Aspire 7750G                | [f99591fe95](https://linux-hardware.org/?probe=f99591fe95) | Mar 26, 2023 |
| Acer          | Nitro AN515-54              | [56e5f689ab](https://linux-hardware.org/?probe=56e5f689ab) | Feb 06, 2023 |
| HP            | ProBook 650 G1              | [830394a75e](https://linux-hardware.org/?probe=830394a75e) | Jan 29, 2023 |
| LG Electro... | 15UD480-GX50K               | [16be4a033d](https://linux-hardware.org/?probe=16be4a033d) | Dec 19, 2022 |
| Dell          | Precision 7720              | [5e8014cc1b](https://linux-hardware.org/?probe=5e8014cc1b) | Dec 08, 2022 |
| HONOR         | BBR-WAX9                    | [d7d701ca15](https://linux-hardware.org/?probe=d7d701ca15) | Dec 06, 2022 |
| Dell          | XPS 15 9520                 | [b6cf92da13](https://linux-hardware.org/?probe=b6cf92da13) | Dec 02, 2022 |
| Panasonic     | CF-19ADNAXDY                | [51120805b1](https://linux-hardware.org/?probe=51120805b1) | Dec 02, 2022 |
| Panasonic     | CF-19ADNAXDY                | [7a809e9dbd](https://linux-hardware.org/?probe=7a809e9dbd) | Dec 02, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [b79b60e4b3](https://linux-hardware.org/?probe=b79b60e4b3) | Nov 28, 2022 |
| Dell          | Latitude E6230              | [da1e32759d](https://linux-hardware.org/?probe=da1e32759d) | Nov 05, 2022 |
| ASUSTek       | G752VSK                     | [16e086c77f](https://linux-hardware.org/?probe=16e086c77f) | Jun 16, 2022 |
| Dell          | Inspiron 3584               | [27ac9bc8f9](https://linux-hardware.org/?probe=27ac9bc8f9) | Jun 07, 2022 |
| Dell          | Inspiron 3584               | [7fdce576b4](https://linux-hardware.org/?probe=7fdce576b4) | Jun 07, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [4655b6a8ed](https://linux-hardware.org/?probe=4655b6a8ed) | Jun 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [8120719b26](https://linux-hardware.org/?probe=8120719b26) | May 26, 2022 |
| Dell          | Vostro 5581                 | [cdcb310766](https://linux-hardware.org/?probe=cdcb310766) | Apr 30, 2022 |
| Lenovo        | ThinkPad T61 64665WG        | [ac1bec6053](https://linux-hardware.org/?probe=ac1bec6053) | Apr 26, 2022 |
| Lenovo        | ThinkPad X61s 7667DB2       | [34ae68d221](https://linux-hardware.org/?probe=34ae68d221) | Apr 05, 2022 |
| Acer          | Aspire 3820                 | [195bb81f89](https://linux-hardware.org/?probe=195bb81f89) | Dec 28, 2021 |
| Acer          | Aspire 3820                 | [149083ba5f](https://linux-hardware.org/?probe=149083ba5f) | Dec 28, 2021 |
| Dell          | Vostro 14 5410              | [ef6f4cf593](https://linux-hardware.org/?probe=ef6f4cf593) | Dec 05, 2021 |
| Dell          | Vostro 14 5410              | [6ab102bc84](https://linux-hardware.org/?probe=6ab102bc84) | Nov 30, 2021 |
| HP            | EliteBook 8540w             | [a68000e142](https://linux-hardware.org/?probe=a68000e142) | Sep 26, 2021 |
| Dell          | Latitude E6530              | [41d65e59eb](https://linux-hardware.org/?probe=41d65e59eb) | Sep 26, 2021 |
| Apple         | MacBookPro5,5               | [d7ee29aac3](https://linux-hardware.org/?probe=d7ee29aac3) | Sep 15, 2021 |
| HP            | EliteBook 8540w             | [fd6f5273e3](https://linux-hardware.org/?probe=fd6f5273e3) | Sep 02, 2021 |
| HP            | EliteBook 2740p             | [0beccde57d](https://linux-hardware.org/?probe=0beccde57d) | Sep 01, 2021 |
| HP            | EliteBook 8540w             | [6e6d5c8f2c](https://linux-hardware.org/?probe=6e6d5c8f2c) | Aug 20, 2021 |
| HP            | Presario C700               | [fa731abf46](https://linux-hardware.org/?probe=fa731abf46) | Aug 19, 2021 |
| Lenovo        | ThinkPad X61s 7667DB2       | [c0af3fd295](https://linux-hardware.org/?probe=c0af3fd295) | Jul 05, 2021 |
| Lenovo        | ThinkPad X61s 7667DB2       | [32d294ba2a](https://linux-hardware.org/?probe=32d294ba2a) | Jun 23, 2021 |
| ASUSTek       | U35JC                       | [29ea6520a1](https://linux-hardware.org/?probe=29ea6520a1) | May 08, 2021 |
| Lenovo        | ThinkPad X200 7459ZEJ       | [a4f7ad5736](https://linux-hardware.org/?probe=a4f7ad5736) | May 07, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80UH      | [72df2af331](https://linux-hardware.org/?probe=72df2af331) | Mar 16, 2021 |
| Dell          | Latitude E7250              | [551399bf55](https://linux-hardware.org/?probe=551399bf55) | Mar 08, 2021 |
| HP            | ProBook 6560b               | [57004cab16](https://linux-hardware.org/?probe=57004cab16) | Feb 17, 2021 |
| Lenovo        | ThinkPad T520 4243Y1N       | [66b47b2f1e](https://linux-hardware.org/?probe=66b47b2f1e) | Jan 20, 2021 |
| HP            | EliteBook 840 G5            | [71b67a3764](https://linux-hardware.org/?probe=71b67a3764) | Jan 14, 2021 |
| Acer          | Aspire E1-572               | [a06266ed7f](https://linux-hardware.org/?probe=a06266ed7f) | Dec 17, 2020 |
| Toshiba       | Satellite A135              | [310ddb721f](https://linux-hardware.org/?probe=310ddb721f) | Nov 20, 2020 |
| Lenovo        | ThinkPad X200 7459H92       | [242193b8bc](https://linux-hardware.org/?probe=242193b8bc) | Nov 17, 2020 |
| Dell          | Latitude E6440              | [46a2699a96](https://linux-hardware.org/?probe=46a2699a96) | Oct 21, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [97a2b45d12](https://linux-hardware.org/?probe=97a2b45d12) | Oct 21, 2020 |
| Dell          | Latitude E6410              | [926bbbdaf2](https://linux-hardware.org/?probe=926bbbdaf2) | Oct 18, 2020 |
| Lenovo        | G500s 20245                 | [8a975cb577](https://linux-hardware.org/?probe=8a975cb577) | Oct 07, 2020 |
| Dell          | Latitude E6410              | [a36dab9e9b](https://linux-hardware.org/?probe=a36dab9e9b) | Oct 06, 2020 |
| Dell          | Inspiron 3542               | [233a83b315](https://linux-hardware.org/?probe=233a83b315) | Sep 08, 2020 |
| Dell          | Inspiron 3542               | [fcb2182f02](https://linux-hardware.org/?probe=fcb2182f02) | Sep 08, 2020 |
| Unknown       | 34AS1                       | [cc188d0f25](https://linux-hardware.org/?probe=cc188d0f25) | Sep 08, 2020 |
| Unknown       | 34AS1                       | [0ab59553ea](https://linux-hardware.org/?probe=0ab59553ea) | Sep 08, 2020 |
| Dell          | Inspiron 3542               | [751df6a75b](https://linux-hardware.org/?probe=751df6a75b) | Sep 08, 2020 |
| Dell          | Inspiron 3542               | [14680221b6](https://linux-hardware.org/?probe=14680221b6) | Sep 07, 2020 |
| HP            | EliteBook 6930p             | [8fdba744ec](https://linux-hardware.org/?probe=8fdba744ec) | Sep 03, 2020 |
| Dell          | Inspiron 5567               | [d7700d73c4](https://linux-hardware.org/?probe=d7700d73c4) | Sep 03, 2020 |
| Dell          | Inspiron N4050              | [c51c0d5538](https://linux-hardware.org/?probe=c51c0d5538) | Aug 15, 2020 |
| HP            | Falco                       | [26ace050f7](https://linux-hardware.org/?probe=26ace050f7) | Jul 07, 2020 |
| Dell          | Inspiron N4050              | [2a05830be5](https://linux-hardware.org/?probe=2a05830be5) | Jul 05, 2020 |
| HP            | EliteBook 840 G5            | [2605330e8c](https://linux-hardware.org/?probe=2605330e8c) | Jun 04, 2020 |
| HP            | EliteBook 840 G5            | [912c44b0ac](https://linux-hardware.org/?probe=912c44b0ac) | May 15, 2020 |
| Acer          | Aspire 5750G                | [1f49c0d636](https://linux-hardware.org/?probe=1f49c0d636) | May 06, 2020 |
| Dell          | Latitude E6220              | [a4db1d31a5](https://linux-hardware.org/?probe=a4db1d31a5) | May 05, 2020 |
| Dell          | Latitude E6220              | [c0152a3b02](https://linux-hardware.org/?probe=c0152a3b02) | May 05, 2020 |
| Toshiba       | Satellite Radius 12 P20W... | [4f272f1c99](https://linux-hardware.org/?probe=4f272f1c99) | May 03, 2020 |
| Dell          | Inspiron 5437               | [0606d60ddb](https://linux-hardware.org/?probe=0606d60ddb) | Apr 29, 2020 |
| Dell          | Inspiron 5437               | [c4f288077d](https://linux-hardware.org/?probe=c4f288077d) | Apr 29, 2020 |
| Dell          | Precision 7510              | [40e5c33fd8](https://linux-hardware.org/?probe=40e5c33fd8) | Apr 27, 2020 |
| Sony          | VGN-N19VP_B                 | [a2e6c99940](https://linux-hardware.org/?probe=a2e6c99940) | Apr 20, 2020 |
| Lenovo        | ThinkPad P53 20QNS00Y00     | [2918602e15](https://linux-hardware.org/?probe=2918602e15) | Mar 12, 2020 |
| Lenovo        | ThinkPad P53 20QNS00Y00     | [8376f889c2](https://linux-hardware.org/?probe=8376f889c2) | Mar 12, 2020 |
| HP            | Laptop 15-da0xxx            | [d2ab3b608a](https://linux-hardware.org/?probe=d2ab3b608a) | Mar 07, 2020 |
| HP            | ZBook 17                    | [5937f48c97](https://linux-hardware.org/?probe=5937f48c97) | Feb 13, 2020 |
| Sony          | VPCSB19GG                   | [cc8806b4ec](https://linux-hardware.org/?probe=cc8806b4ec) | Feb 04, 2020 |
| HP            | EliteBook x360 1040 G6      | [7d1585f3cd](https://linux-hardware.org/?probe=7d1585f3cd) | Dec 28, 2019 |
| Lenovo        | Y520-15IKBN 80WK            | [e795735d5b](https://linux-hardware.org/?probe=e795735d5b) | Dec 14, 2019 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [1bb0047e0e](https://linux-hardware.org/?probe=1bb0047e0e) | Dec 03, 2019 |
| Dell          | System XPS L702X            | [ba096189bc](https://linux-hardware.org/?probe=ba096189bc) | Dec 03, 2019 |
| MSI           | GL63 8SD                    | [3cef0087aa](https://linux-hardware.org/?probe=3cef0087aa) | Dec 01, 2019 |
| Dell          | Vostro 5568                 | [a0b3e4d70f](https://linux-hardware.org/?probe=a0b3e4d70f) | Oct 16, 2019 |
| HP            | Pavilion 15                 | [7e407e7cd4](https://linux-hardware.org/?probe=7e407e7cd4) | Sep 15, 2019 |
| HP            | Pavilion 15                 | [447f75484c](https://linux-hardware.org/?probe=447f75484c) | Sep 11, 2019 |
| HP            | Pavilion 15                 | [9352d1efae](https://linux-hardware.org/?probe=9352d1efae) | Sep 11, 2019 |
| MSI           | GP62MVR 7RFX                | [5a21834bbd](https://linux-hardware.org/?probe=5a21834bbd) | Sep 01, 2019 |
| Notebook      | WA50SRQ                     | [fd99d2b5e2](https://linux-hardware.org/?probe=fd99d2b5e2) | Aug 09, 2019 |
| Dell          | Precision M4600             | [9b9a3a238d](https://linux-hardware.org/?probe=9b9a3a238d) | Apr 14, 2019 |
| Dell          | Vostro 5470                 | [e106741644](https://linux-hardware.org/?probe=e106741644) | Apr 10, 2019 |
| ASUSTek       | X540SC                      | [f513215ec6](https://linux-hardware.org/?probe=f513215ec6) | Jan 09, 2019 |
| Lenovo        | ThinkPad T440p 20AWS27B0... | [000dae069a](https://linux-hardware.org/?probe=000dae069a) | Oct 31, 2018 |
| Lenovo        | ThinkPad T530 2394AG6       | [6b8015f1e2](https://linux-hardware.org/?probe=6b8015f1e2) | Oct 26, 2018 |
| Lenovo        | ThinkPad T530 2394AG6       | [c834cadf29](https://linux-hardware.org/?probe=c834cadf29) | Oct 26, 2018 |
| HP            | EliteBook 2740p             | [1b72dbb418](https://linux-hardware.org/?probe=1b72dbb418) | Sep 17, 2017 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                 | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| 3.10.0-957.27.2.el7.x86_64              | 3         | 4.05%   |
| 3.10.0-957.10.1.el7.x86_64              | 3         | 4.05%   |
| 3.10.0-1160.80.1.el7.x86_64             | 3         | 4.05%   |
| 3.10.0-1160.66.1.el7.x86_64             | 3         | 4.05%   |
| 3.10.0-1160.15.2.el7.x86_64             | 3         | 4.05%   |
| 3.10.0-1127.19.1.el7.x86_64             | 3         | 4.05%   |
| 3.10.0-957.el7.x86_64                   | 2         | 2.7%    |
| 3.10.0-957.1.3.el7.x86_64               | 2         | 2.7%    |
| 3.10.0-862.14.4.el7.x86_64              | 2         | 2.7%    |
| 3.10.0-1160.45.1.el7.x86_64             | 2         | 2.7%    |
| 3.10.0-1127.el7.x86_64                  | 2         | 2.7%    |
| 3.10.0-1127.18.2.el7.x86_64             | 2         | 2.7%    |
| 3.10.0-1127.18.2.el7.centos.plus.i686   | 2         | 2.7%    |
| 3.10.0-1127.13.1.el7.x86_64             | 2         | 2.7%    |
| 3.10.0-1062.9.1.el7.x86_64              | 2         | 2.7%    |
| 3.10.0-1062.4.3.el7.x86_64              | 2         | 2.7%    |
| 3.10.0-1062.12.1.el7.x86_64             | 2         | 2.7%    |
| 5.8.13-1.el7.elrepo.x86_64              | 1         | 1.35%   |
| 5.6.8-1.el7.elrepo.x86_64               | 1         | 1.35%   |
| 5.4.6-1.el7.elrepo.x86_64               | 1         | 1.35%   |
| 5.4.225-200.el7.x86_64                  | 1         | 1.35%   |
| 5.4.125-200.el7.x86_64                  | 1         | 1.35%   |
| 5.4.121-200.el7.x86_64                  | 1         | 1.35%   |
| 5.18.13-1.el7.elrepo.x86_64             | 1         | 1.35%   |
| 5.11.0-1.el7.elrepo.x86_64              | 1         | 1.35%   |
| 5.10.75-200.el7.x86_64                  | 1         | 1.35%   |
| 4.20.8-1.el7.elrepo.x86_64              | 1         | 1.35%   |
| 4.19.8-1.el7.elrepo.x86_64              | 1         | 1.35%   |
| 3.10.0-957.21.3.el7.x86_64              | 1         | 1.35%   |
| 3.10.0-862.el7.x86_64                   | 1         | 1.35%   |
| 3.10.0-693.2.2.el7.x86_64               | 1         | 1.35%   |
| 3.10.0-1160.el7.x86_64                  | 1         | 1.35%   |
| 3.10.0-1160.95.1.el7.x86_64             | 1         | 1.35%   |
| 3.10.0-1160.92.1.el7.x86_64             | 1         | 1.35%   |
| 3.10.0-1160.90.1.el7.x86_64             | 1         | 1.35%   |
| 3.10.0-1160.88.1.el7.x86_64             | 1         | 1.35%   |
| 3.10.0-1160.83.1.el7.x86_64             | 1         | 1.35%   |
| 3.10.0-1160.76.1.el7.x86_64             | 1         | 1.35%   |
| 3.10.0-1160.76.1.el7.centos.plus.x86_64 | 1         | 1.35%   |
| 3.10.0-1160.62.1.el7.x86_64             | 1         | 1.35%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 3.10.0  | 63        | 85.14%  |
| 5.8.13  | 1         | 1.35%   |
| 5.6.8   | 1         | 1.35%   |
| 5.4.6   | 1         | 1.35%   |
| 5.4.225 | 1         | 1.35%   |
| 5.4.125 | 1         | 1.35%   |
| 5.4.121 | 1         | 1.35%   |
| 5.18.13 | 1         | 1.35%   |
| 5.11.0  | 1         | 1.35%   |
| 5.10.75 | 1         | 1.35%   |
| 4.20.8  | 1         | 1.35%   |
| 4.19.8  | 1         | 1.35%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 3.10    | 63        | 86.3%   |
| 5.4     | 3         | 4.11%   |
| 5.8     | 1         | 1.37%   |
| 5.6     | 1         | 1.37%   |
| 5.18    | 1         | 1.37%   |
| 5.11    | 1         | 1.37%   |
| 5.10    | 1         | 1.37%   |
| 4.20    | 1         | 1.37%   |
| 4.19    | 1         | 1.37%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 69        | 95.83%  |
| i686   | 3         | 4.17%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 24        | 33.33%  |
| KDE4          | 14        | 19.44%  |
| GNOME Classic | 14        | 19.44%  |
| Unknown       | 8         | 11.11%  |
| MATE          | 6         | 8.33%   |
| Cinnamon      | 4         | 5.56%   |
| XFCE          | 2         | 2.78%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 70        | 97.22%  |
| Unknown | 2         | 2.78%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GDM     | 48        | 65.75%  |
| Unknown | 19        | 26.03%  |
| LightDM | 4         | 5.48%   |
| TDM     | 2         | 2.74%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| en_US       | 35        | 47.95%  |
| Unknown     | 13        | 17.81%  |
| en_GB       | 6         | 8.22%   |
| fr_FR       | 4         | 5.48%   |
| ru_RU       | 3         | 4.11%   |
| pt_BR       | 2         | 2.74%   |
| pl_PL       | 2         | 2.74%   |
| zh_CN       | 1         | 1.37%   |
| pt_PT       | 1         | 1.37%   |
| ja_JP       | 1         | 1.37%   |
| es_ES       | 1         | 1.37%   |
| es_AR       | 1         | 1.37%   |
| en_ZA       | 1         | 1.37%   |
| en_US.utf-8 | 1         | 1.37%   |
| de_DE       | 1         | 1.37%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 49        | 67.12%  |
| EFI  | 24        | 32.88%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Xfs     | 42        | 57.53%  |
| Ext4    | 23        | 31.51%  |
| Unknown | 5         | 6.85%   |
| Overlay | 1         | 1.37%   |
| Ext3    | 1         | 1.37%   |
| Ext2    | 1         | 1.37%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 29        | 39.73%  |
| MBR     | 27        | 36.99%  |
| Unknown | 17        | 23.29%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 59        | 81.94%  |
| Yes       | 13        | 18.06%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 56        | 76.71%  |
| Yes       | 17        | 23.29%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Dell                | 22        | 30.56%  |
| Hewlett-Packard     | 15        | 20.83%  |
| Lenovo              | 14        | 19.44%  |
| ASUSTek Computer    | 4         | 5.56%   |
| Acer                | 4         | 5.56%   |
| Toshiba             | 2         | 2.78%   |
| Sony                | 2         | 2.78%   |
| MSI                 | 2         | 2.78%   |
| Samsung Electronics | 1         | 1.39%   |
| Panasonic           | 1         | 1.39%   |
| Notebook            | 1         | 1.39%   |
| LG Electronics      | 1         | 1.39%   |
| HONOR               | 1         | 1.39%   |
| Apple               | 1         | 1.39%   |
| Unknown             | 1         | 1.39%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Dell System XPS L702X                                 | 2         | 2.78%   |
| Dell Inspiron N4050                                   | 2         | 2.78%   |
| Toshiba Satellite Radius 12 P20W-C-106                | 1         | 1.39%   |
| Toshiba Satellite A135                                | 1         | 1.39%   |
| Sony VPCSB19GG                                        | 1         | 1.39%   |
| Sony VGN-N19VP_B                                      | 1         | 1.39%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 1.39%   |
| Panasonic CF-19ADNAXDY                                | 1         | 1.39%   |
| Notebook WA50SRQ                                      | 1         | 1.39%   |
| MSI GP62MVR 7RFX                                      | 1         | 1.39%   |
| MSI GL63 8SD                                          | 1         | 1.39%   |
| LG 15UD480-GX50K                                      | 1         | 1.39%   |
| Lenovo Y520-15IKBN 80WK                               | 1         | 1.39%   |
| Lenovo ThinkPad X61s 7667DB2                          | 1         | 1.39%   |
| Lenovo ThinkPad X200 7459ZEJ                          | 1         | 1.39%   |
| Lenovo ThinkPad X200 7459H92                          | 1         | 1.39%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGSA3T00              | 1         | 1.39%   |
| Lenovo ThinkPad T61 64665WG                           | 1         | 1.39%   |
| Lenovo ThinkPad T530 2394AG6                          | 1         | 1.39%   |
| Lenovo ThinkPad T520 4243Y1N                          | 1         | 1.39%   |
| Lenovo ThinkPad T440p 20AWS27B0X                      | 1         | 1.39%   |
| Lenovo ThinkPad T14 Gen 1 20S0003GUS                  | 1         | 1.39%   |
| Lenovo ThinkPad P53 20QNS00Y00                        | 1         | 1.39%   |
| Lenovo ThinkPad P14s Gen 2i 20VX00MWUS                | 1         | 1.39%   |
| Lenovo IdeaPad 310-15ISK 80UH                         | 1         | 1.39%   |
| Lenovo G500s 20245                                    | 1         | 1.39%   |
| HONOR BBR-WAX9                                        | 1         | 1.39%   |
| HP ZHAN 66 Pro A 14 G3                                | 1         | 1.39%   |
| HP ZBook 17                                           | 1         | 1.39%   |
| HP ProBook 6560b                                      | 1         | 1.39%   |
| HP ProBook 650 G1                                     | 1         | 1.39%   |
| HP ProBook 450 G3                                     | 1         | 1.39%   |
| HP Presario C700                                      | 1         | 1.39%   |
| HP Pavilion Laptop 14-dv0xxx                          | 1         | 1.39%   |
| HP Pavilion 15                                        | 1         | 1.39%   |
| HP Laptop 15-da0xxx                                   | 1         | 1.39%   |
| HP Falco                                              | 1         | 1.39%   |
| HP EliteBook x360 1040 G6                             | 1         | 1.39%   |
| HP EliteBook 8540w                                    | 1         | 1.39%   |
| HP EliteBook 840 G5                                   | 1         | 1.39%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 11        | 15.28%  |
| Dell Latitude          | 6         | 8.33%   |
| Dell Inspiron          | 6         | 8.33%   |
| HP EliteBook           | 5         | 6.94%   |
| Dell Vostro            | 4         | 5.56%   |
| HP ProBook             | 3         | 4.17%   |
| Dell Precision         | 3         | 4.17%   |
| Acer Aspire            | 3         | 4.17%   |
| Toshiba Satellite      | 2         | 2.78%   |
| HP Pavilion            | 2         | 2.78%   |
| Dell System            | 2         | 2.78%   |
| Sony VPCSB19GG         | 1         | 1.39%   |
| Sony VGN-N19VP         | 1         | 1.39%   |
| Samsung 300E5EV        | 1         | 1.39%   |
| Panasonic CF-19ADNAXDY | 1         | 1.39%   |
| Notebook WA50SRQ       | 1         | 1.39%   |
| MSI GP62MVR            | 1         | 1.39%   |
| MSI GL63               | 1         | 1.39%   |
| LG 15UD480-GX50K       | 1         | 1.39%   |
| Lenovo Y520-15IKBN     | 1         | 1.39%   |
| Lenovo IdeaPad         | 1         | 1.39%   |
| Lenovo G500s           | 1         | 1.39%   |
| HONOR BBR-WAX9         | 1         | 1.39%   |
| HP ZHAN                | 1         | 1.39%   |
| HP ZBook               | 1         | 1.39%   |
| HP Presario            | 1         | 1.39%   |
| HP Laptop              | 1         | 1.39%   |
| HP Falco               | 1         | 1.39%   |
| Dell XPS               | 1         | 1.39%   |
| ASUS X540SC            | 1         | 1.39%   |
| ASUS VivoBook          | 1         | 1.39%   |
| ASUS U35JC             | 1         | 1.39%   |
| ASUS G752VSK           | 1         | 1.39%   |
| Apple MacBookPro5      | 1         | 1.39%   |
| Acer Nitro             | 1         | 1.39%   |
| Unknown                | 1         | 1.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2011 | 10        | 13.89%  |
| 2013 | 9         | 12.5%   |
| 2019 | 5         | 6.94%   |
| 2018 | 5         | 6.94%   |
| 2014 | 5         | 6.94%   |
| 2010 | 5         | 6.94%   |
| 2021 | 4         | 5.56%   |
| 2016 | 4         | 5.56%   |
| 2015 | 4         | 5.56%   |
| 2012 | 4         | 5.56%   |
| 2017 | 3         | 4.17%   |
| 2008 | 3         | 4.17%   |
| 2007 | 3         | 4.17%   |
| 2022 | 2         | 2.78%   |
| 2020 | 2         | 2.78%   |
| 2006 | 2         | 2.78%   |
| 2009 | 1         | 1.39%   |
| 2001 | 1         | 1.39%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 72        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 68        | 94.44%  |
| Enabled  | 4         | 5.56%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 71        | 98.61%  |
| Yes  | 1         | 1.39%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 29        | 39.73%  |
| 3.01-4.0    | 12        | 16.44%  |
| 8.01-16.0   | 10        | 13.7%   |
| 16.01-24.0  | 9         | 12.33%  |
| 32.01-64.0  | 6         | 8.22%   |
| 1.01-2.0    | 3         | 4.11%   |
| 24.01-32.0  | 1         | 1.37%   |
| 2.01-3.0    | 1         | 1.37%   |
| 64.01-256.0 | 1         | 1.37%   |
| 0.51-1.0    | 1         | 1.37%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 19        | 24.68%  |
| 1.01-2.0   | 19        | 24.68%  |
| 4.01-8.0   | 14        | 18.18%  |
| 3.01-4.0   | 13        | 16.88%  |
| 0.51-1.0   | 8         | 10.39%  |
| 32.01-64.0 | 1         | 1.3%    |
| 24.01-32.0 | 1         | 1.3%    |
| 8.01-16.0  | 1         | 1.3%    |
| 0.01-0.5   | 1         | 1.3%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 52        | 71.23%  |
| 2      | 16        | 21.92%  |
| 3      | 3         | 4.11%   |
| 0      | 2         | 2.74%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 43        | 59.72%  |
| Yes       | 29        | 40.28%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 65        | 90.28%  |
| No        | 7         | 9.72%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 72        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 53        | 73.61%  |
| No        | 19        | 26.39%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 9         | 12.5%   |
| Russia       | 9         | 12.5%   |
| France       | 5         | 6.94%   |
| UK           | 4         | 5.56%   |
| Poland       | 4         | 5.56%   |
| China        | 4         | 5.56%   |
| Ukraine      | 2         | 2.78%   |
| Spain        | 2         | 2.78%   |
| Malaysia     | 2         | 2.78%   |
| Japan        | 2         | 2.78%   |
| Germany      | 2         | 2.78%   |
| Finland      | 2         | 2.78%   |
| Bulgaria     | 2         | 2.78%   |
| Brazil       | 2         | 2.78%   |
| Australia    | 2         | 2.78%   |
| Taiwan       | 1         | 1.39%   |
| Switzerland  | 1         | 1.39%   |
| Sweden       | 1         | 1.39%   |
| South Korea  | 1         | 1.39%   |
| South Africa | 1         | 1.39%   |
| Romania      | 1         | 1.39%   |
| Portugal     | 1         | 1.39%   |
| Mexico       | 1         | 1.39%   |
| Kazakhstan   | 1         | 1.39%   |
| Israel       | 1         | 1.39%   |
| Ireland      | 1         | 1.39%   |
| Iran         | 1         | 1.39%   |
| India        | 1         | 1.39%   |
| Greece       | 1         | 1.39%   |
| Croatia      | 1         | 1.39%   |
| Chile        | 1         | 1.39%   |
| Canada       | 1         | 1.39%   |
| Argentina    | 1         | 1.39%   |
| Algeria      | 1         | 1.39%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Notebooks | Percent |
|-----------------|-----------|---------|
| Moscow          | 5         | 6.67%   |
| Guangzhou       | 3         | 4%      |
| Sofia           | 2         | 2.67%   |
| Krasnodar       | 2         | 2.67%   |
| Helsinki        | 2         | 2.67%   |
| Grovedale       | 2         | 2.67%   |
| Zagreb          | 1         | 1.33%   |
| Yekaterinburg   | 1         | 1.33%   |
| West Chester    | 1         | 1.33%   |
| Waltham         | 1         | 1.33%   |
| Tygelsjoe       | 1         | 1.33%   |
| Toyama          | 1         | 1.33%   |
| Toronto         | 1         | 1.33%   |
| Tehran          | 1         | 1.33%   |
| Taichung        | 1         | 1.33%   |
| Skikda          | 1         | 1.33%   |
| Satigny         | 1         | 1.33%   |
| Sao Paulo       | 1         | 1.33%   |
| Santiago        | 1         | 1.33%   |
| Rzeszów        | 1         | 1.33%   |
| Roman           | 1         | 1.33%   |
| Poznan          | 1         | 1.33%   |
| Phoenix         | 1         | 1.33%   |
| Petaling Jaya   | 1         | 1.33%   |
| Paris           | 1         | 1.33%   |
| Nur-Sultan      | 1         | 1.33%   |
| Nea Filadelfeia | 1         | 1.33%   |
| Mytishchi       | 1         | 1.33%   |
| Mykolayiv       | 1         | 1.33%   |
| Murcia          | 1         | 1.33%   |
| Milwaukee       | 1         | 1.33%   |
| Mexico City     | 1         | 1.33%   |
| Medford         | 1         | 1.33%   |
| Marseille       | 1         | 1.33%   |
| Manchester      | 1         | 1.33%   |
| Maidenhead      | 1         | 1.33%   |
| Lodz            | 1         | 1.33%   |
| Littlehampton   | 1         | 1.33%   |
| Lisbon          | 1         | 1.33%   |
| La Serena       | 1         | 1.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 17        | 21     | 19.1%   |
| Seagate                      | 12        | 13     | 13.48%  |
| Toshiba                      | 10        | 11     | 11.24%  |
| Kingston                     | 9         | 9      | 10.11%  |
| WDC                          | 8         | 8      | 8.99%   |
| SanDisk                      | 5         | 5      | 5.62%   |
| Intel                        | 4         | 5      | 4.49%   |
| Hitachi                      | 4         | 4      | 4.49%   |
| Unknown                      | 2         | 2      | 2.25%   |
| StoreJet                     | 2         | 2      | 2.25%   |
| SK hynix                     | 2         | 2      | 2.25%   |
| Micron Technology            | 2         | 2      | 2.25%   |
| Toshiba America Info Systems | 1         | 2      | 1.12%   |
| SPCC                         | 1         | 3      | 1.12%   |
| Smartbuy                     | 1         | 1      | 1.12%   |
| OCZ                          | 1         | 2      | 1.12%   |
| LITEONIT                     | 1         | 1      | 1.12%   |
| LITEON                       | 1         | 1      | 1.12%   |
| Kingston Technology Company  | 1         | 1      | 1.12%   |
| HGST                         | 1         | 1      | 1.12%   |
| GOODRAM                      | 1         | 1      | 1.12%   |
| Fujitsu                      | 1         | 1      | 1.12%   |
| Crucial                      | 1         | 1      | 1.12%   |
| A-DATA Technology            | 1         | 1      | 1.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                   | 3         | 3.3%    |
| Toshiba TR200 240GB SSD                           | 2         | 2.2%    |
| StoreJet Transcend 500GB                          | 2         | 2.2%    |
| Seagate BUP Slim 1TB                              | 2         | 2.2%    |
| Samsung NVMe SSD Controller SM981/PM981 2TB       | 2         | 2.2%    |
| WDC WD7500BPVX-00JC3T0 752GB                      | 1         | 1.1%    |
| WDC WD7500BPKX-00HPJT0 752GB                      | 1         | 1.1%    |
| WDC WD5000BEVT-80A0RT0 500GB                      | 1         | 1.1%    |
| WDC WD5000BEVT-22A0RT0 500GB                      | 1         | 1.1%    |
| WDC WD3200BPVT-75JJ5T0 320GB                      | 1         | 1.1%    |
| WDC WD10JPCX-24UE4T0 1TB                          | 1         | 1.1%    |
| WDC PC SN810 NVMe 1024GB                          | 1         | 1.1%    |
| WDC PC SN520 SDAPNUW-256G-1006 256GB              | 1         | 1.1%    |
| Unknown SDC  4GB                                  | 1         | 1.1%    |
| Unknown SD32G  32GB                               | 1         | 1.1%    |
| Toshiba THNSNK256GCS8 SATA 256GB SSD              | 1         | 1.1%    |
| Toshiba THNSNC128GMMJ 128GB SSD                   | 1         | 1.1%    |
| Toshiba MQ04ABF100 1TB                            | 1         | 1.1%    |
| Toshiba MQ01ABF050 500GB                          | 1         | 1.1%    |
| Toshiba MQ01ABD100 1TB                            | 1         | 1.1%    |
| Toshiba MQ01ABD050 500GB                          | 1         | 1.1%    |
| Toshiba MK8032GSX 80GB                            | 1         | 1.1%    |
| Toshiba MK5061GSY 500GB                           | 1         | 1.1%    |
| Toshiba America Info Systems KXG60ZNV1T02 NVM 1TB | 1         | 1.1%    |
| SPCC Solid State Disk 256GB                       | 1         | 1.1%    |
| Smartbuy SSD 120GB                                | 1         | 1.1%    |
| SK hynix SH920 2.5 7MM 256GB SSD                  | 1         | 1.1%    |
| SK hynix SC210 mSATA 256GB SSD                    | 1         | 1.1%    |
| Seagate ST980813ASG 80GB                          | 1         | 1.1%    |
| Seagate ST9320328CS 320GB                         | 1         | 1.1%    |
| Seagate ST9320325AS 320GB                         | 1         | 1.1%    |
| Seagate ST9120823AS 120GB                         | 1         | 1.1%    |
| Seagate ST750LM022 HN-M750MBB 752GB               | 1         | 1.1%    |
| Seagate ST500LT012-1DG142 500GB                   | 1         | 1.1%    |
| Seagate ST1000LM048-2E7172 1TB                    | 1         | 1.1%    |
| Seagate ST1000LM035-1RK172 1TB                    | 1         | 1.1%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 1         | 1.1%    |
| Seagate Expansion 1TB                             | 1         | 1.1%    |
| Sandisk WDC PC SN730 SDB 512GB                    | 1         | 1.1%    |
| Sandisk WD PC SN740 SDDQ 512GB                    | 1         | 1.1%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 13     | 38.71%  |
| WDC                 | 6         | 6      | 19.35%  |
| Toshiba             | 6         | 6      | 19.35%  |
| Hitachi             | 4         | 4      | 12.9%   |
| Samsung Electronics | 1         | 1      | 3.23%   |
| HGST                | 1         | 1      | 3.23%   |
| Fujitsu             | 1         | 1      | 3.23%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 11        | 11     | 26.19%  |
| Kingston            | 8         | 8      | 19.05%  |
| Toshiba             | 4         | 5      | 9.52%   |
| Intel               | 3         | 4      | 7.14%   |
| StoreJet            | 2         | 2      | 4.76%   |
| SK hynix            | 2         | 2      | 4.76%   |
| SanDisk             | 2         | 2      | 4.76%   |
| Micron Technology   | 2         | 2      | 4.76%   |
| SPCC                | 1         | 3      | 2.38%   |
| Smartbuy            | 1         | 1      | 2.38%   |
| OCZ                 | 1         | 2      | 2.38%   |
| LITEONIT            | 1         | 1      | 2.38%   |
| LITEON              | 1         | 1      | 2.38%   |
| GOODRAM             | 1         | 1      | 2.38%   |
| Crucial             | 1         | 1      | 2.38%   |
| A-DATA Technology   | 1         | 1      | 2.38%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 39        | 47     | 45.35%  |
| HDD  | 31        | 32     | 36.05%  |
| NVMe | 14        | 19     | 16.28%  |
| MMC  | 2         | 2      | 2.33%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 58        | 74     | 73.42%  |
| NVMe | 14        | 19     | 17.72%  |
| SAS  | 5         | 5      | 6.33%   |
| MMC  | 2         | 2      | 2.53%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 50        | 61     | 73.53%  |
| 0.51-1.0   | 17        | 17     | 25%     |
| 3.01-4.0   | 1         | 1      | 1.47%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 25        | 33.78%  |
| 251-500        | 16        | 21.62%  |
| 51-100         | 11        | 14.86%  |
| 501-1000       | 9         | 12.16%  |
| 1001-2000      | 6         | 8.11%   |
| More than 3000 | 3         | 4.05%   |
| 21-50          | 3         | 4.05%   |
| 1-20           | 1         | 1.35%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 28        | 38.36%  |
| 101-250        | 12        | 16.44%  |
| 251-500        | 9         | 12.33%  |
| 51-100         | 8         | 10.96%  |
| 21-50          | 7         | 9.59%   |
| 501-1000       | 5         | 6.85%   |
| More than 3000 | 2         | 2.74%   |
| 2001-3000      | 1         | 1.37%   |
| 1001-2000      | 1         | 1.37%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WD10JPCX-24UE4T0 1TB                            | 1         | 1      | 5.56%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD                | 1         | 1      | 5.56%   |
| Toshiba MQ04ABF100 1TB                              | 1         | 1      | 5.56%   |
| Toshiba MK8032GSX 80GB                              | 1         | 1      | 5.56%   |
| Smartbuy SSD 120GB                                  | 1         | 1      | 5.56%   |
| SK hynix SC210 mSATA 256GB SSD                      | 1         | 1      | 5.56%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 1      | 5.56%   |
| SanDisk SD9SN8W256G1009 256GB SSD                   | 1         | 1      | 5.56%   |
| Micron Technology MTFDDAK256MAY-1AH1ZABHA 256GB SSD | 1         | 1      | 5.56%   |
| Micron Technology 1100 SATA 256GB SSD               | 1         | 1      | 5.56%   |
| LITEONIT LSS-16L6G-HP 16GB SSD                      | 1         | 1      | 5.56%   |
| Intel SSDSC2KW240H6 240GB                           | 1         | 1      | 5.56%   |
| Intel SSDSC2KW180H6 180GB                           | 1         | 1      | 5.56%   |
| Intel SSDSC2BW240A4 240GB                           | 1         | 2      | 5.56%   |
| Hitachi HTS727575A9E364 752GB                       | 1         | 1      | 5.56%   |
| Hitachi HTS543232A7A384 320GB                       | 1         | 1      | 5.56%   |
| Hitachi HTS541680J9SA00 80GB                        | 1         | 1      | 5.56%   |
| Crucial CT480M500SSD1 480GB                         | 1         | 1      | 5.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Toshiba           | 3         | 3      | 16.67%  |
| Intel             | 3         | 4      | 16.67%  |
| Hitachi           | 3         | 3      | 16.67%  |
| Micron Technology | 2         | 2      | 11.11%  |
| WDC               | 1         | 1      | 5.56%   |
| Smartbuy          | 1         | 1      | 5.56%   |
| SK hynix          | 1         | 1      | 5.56%   |
| Seagate           | 1         | 1      | 5.56%   |
| SanDisk           | 1         | 1      | 5.56%   |
| LITEONIT          | 1         | 1      | 5.56%   |
| Crucial           | 1         | 1      | 5.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 3         | 3      | 42.86%  |
| Toshiba | 2         | 2      | 28.57%  |
| WDC     | 1         | 1      | 14.29%  |
| Seagate | 1         | 1      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 11        | 12     | 61.11%  |
| HDD  | 7         | 7      | 38.89%  |

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
| Works    | 38        | 51     | 50%     |
| Detected | 21        | 30     | 27.63%  |
| Malfunc  | 17        | 19     | 22.37%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 61        | 77.22%  |
| Samsung Electronics              | 6         | 7.59%   |
| SanDisk                          | 5         | 6.33%   |
| Kingston Technology Company      | 2         | 2.53%   |
| AMD                              | 2         | 2.53%   |
| Toshiba America Info Systems     | 1         | 1.27%   |
| Silicon Integrated Systems [SiS] | 1         | 1.27%   |
| Nvidia                           | 1         | 1.27%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 10        | 11.49%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 7         | 8.05%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 7         | 8.05%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 5         | 5.75%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 4         | 4.6%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 4         | 4.6%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 3         | 3.45%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 3         | 3.45%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 3         | 3.45%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 3         | 3.45%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 3         | 3.45%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 3         | 3.45%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 3         | 3.45%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 2         | 2.3%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 2         | 2.3%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 1         | 1.15%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                   | 1         | 1.15%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                             | 1         | 1.15%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                                  | 1         | 1.15%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD                | 1         | 1.15%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                   | 1         | 1.15%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                            | 1         | 1.15%   |
| Nvidia MCP79 SATA Controller                                                           | 1         | 1.15%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                          | 1         | 1.15%   |
| Kingston Company A1000/U-SNS8154P3 x2 NVMe SSD                                         | 1         | 1.15%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 1         | 1.15%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                                       | 1         | 1.15%   |
| Intel Mobile PM965/GM965 PT IDER Controller                                            | 1         | 1.15%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                       | 1         | 1.15%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 1         | 1.15%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 1         | 1.15%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 1         | 1.15%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 1         | 1.15%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 1         | 1.15%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 1         | 1.15%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 1.15%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 1.15%   |
| AMD IXP SB4x0 Serial ATA Controller                                                    | 1         | 1.15%   |
| AMD IXP SB4x0 IDE Controller                                                           | 1         | 1.15%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 1         | 1.15%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 48        | 58.54%  |
| NVMe | 14        | 17.07%  |
| RAID | 11        | 13.41%  |
| IDE  | 9         | 10.98%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 71        | 98.61%  |
| AMD    | 1         | 1.39%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz    | 4         | 5.56%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz   | 3         | 4.17%   |
| Intel Core i3-2330M CPU @ 2.20GHz    | 3         | 4.17%   |
| Intel Core i7-8550U CPU @ 1.80GHz    | 2         | 2.78%   |
| Intel Core i7-6500U CPU @ 2.50GHz    | 2         | 2.78%   |
| Intel Core i5-8250U CPU @ 1.60GHz    | 2         | 2.78%   |
| Intel Core i5-7200U CPU @ 2.50GHz    | 2         | 2.78%   |
| Intel Core i5 CPU M 560 @ 2.67GHz    | 2         | 2.78%   |
| Intel Core i3-3120M CPU @ 2.50GHz    | 2         | 2.78%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz | 2         | 2.78%   |
| Intel Pentium CPU P6200 @ 2.13GHz    | 1         | 1.39%   |
| Intel Pentium CPU N3700 @ 1.60GHz    | 1         | 1.39%   |
| Intel Pentium 4 CPU 2.00GHz          | 1         | 1.39%   |
| Intel Genuine CPU T2060 @ 1.60GHz    | 1         | 1.39%   |
| Intel Genuine CPU T2050 @ 1.60GHz    | 1         | 1.39%   |
| Intel Core i9-9880H CPU @ 2.30GHz    | 1         | 1.39%   |
| Intel Core i7-9750H CPU @ 2.60GHz    | 1         | 1.39%   |
| Intel Core i7-8750H CPU @ 2.20GHz    | 1         | 1.39%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz   | 1         | 1.39%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz   | 1         | 1.39%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz   | 1         | 1.39%   |
| Intel Core i7-4610M CPU @ 3.00GHz    | 1         | 1.39%   |
| Intel Core i7-3520M CPU @ 2.90GHz    | 1         | 1.39%   |
| Intel Core i7-2670QM CPU @ 2.20GHz   | 1         | 1.39%   |
| Intel Core i7-2620M CPU @ 2.70GHz    | 1         | 1.39%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz   | 1         | 1.39%   |
| Intel Core i7-10510U CPU @ 1.80GHz   | 1         | 1.39%   |
| Intel Core i7 CPU Q 840 @ 1.87GHz    | 1         | 1.39%   |
| Intel Core i5-8365U CPU @ 1.60GHz    | 1         | 1.39%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz   | 1         | 1.39%   |
| Intel Core i5-5300U CPU @ 2.30GHz    | 1         | 1.39%   |
| Intel Core i5-4300M CPU @ 2.60GHz    | 1         | 1.39%   |
| Intel Core i5-4210U CPU @ 1.70GHz    | 1         | 1.39%   |
| Intel Core i5-4200U CPU @ 1.60GHz    | 1         | 1.39%   |
| Intel Core i5-3320M CPU @ 2.60GHz    | 1         | 1.39%   |
| Intel Core i5-3210M CPU @ 2.50GHz    | 1         | 1.39%   |
| Intel Core i5-2430M CPU @ 2.40GHz    | 1         | 1.39%   |
| Intel Core i5-10210U CPU @ 1.60GHz   | 1         | 1.39%   |
| Intel Core i3-8145U CPU @ 2.10GHz    | 1         | 1.39%   |
| Intel Core i3-7020U CPU @ 2.30GHz    | 1         | 1.39%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 20        | 27.78%  |
| Intel Core i7    | 19        | 26.39%  |
| Intel Core i3    | 12        | 16.67%  |
| Intel Core 2 Duo | 7         | 9.72%   |
| Other            | 4         | 5.56%   |
| Intel Celeron    | 3         | 4.17%   |
| Intel Pentium    | 2         | 2.78%   |
| Intel Genuine    | 2         | 2.78%   |
| Intel Pentium 4  | 1         | 1.39%   |
| Intel Core i9    | 1         | 1.39%   |
| AMD Ryzen 7      | 1         | 1.39%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 45        | 62.5%   |
| 4      | 21        | 29.17%  |
| 8      | 2         | 2.78%   |
| 6      | 2         | 2.78%   |
| 14     | 1         | 1.39%   |
| 1      | 1         | 1.39%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 72        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 53        | 73.61%  |
| 1      | 19        | 26.39%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 65        | 90.28%  |
| Unknown        | 4         | 5.56%   |
| 32-bit         | 3         | 4.17%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x206a7    | 11        | 15.07%  |
| 0x306a9    | 6         | 8.22%   |
| 0x40651    | 5         | 6.85%   |
| 0x306c3    | 5         | 6.85%   |
| 0x906e9    | 4         | 5.48%   |
| 0x806ea    | 4         | 5.48%   |
| 0x20655    | 4         | 5.48%   |
| 0x806ec    | 3         | 4.11%   |
| 0x806e9    | 3         | 4.11%   |
| 0x806c1    | 3         | 4.11%   |
| 0x1067a    | 3         | 4.11%   |
| 0x906ea    | 2         | 2.74%   |
| 0x406e3    | 2         | 2.74%   |
| 0x10676    | 2         | 2.74%   |
| Unknown    | 2         | 2.74%   |
| 0xf24      | 1         | 1.37%   |
| 0x906ed    | 1         | 1.37%   |
| 0x906a3    | 1         | 1.37%   |
| 0x806eb    | 1         | 1.37%   |
| 0x706e5    | 1         | 1.37%   |
| 0x6fd      | 1         | 1.37%   |
| 0x6fb      | 1         | 1.37%   |
| 0x6ec      | 1         | 1.37%   |
| 0x6e8      | 1         | 1.37%   |
| 0x506e3    | 1         | 1.37%   |
| 0x406c3    | 1         | 1.37%   |
| 0x306d4    | 1         | 1.37%   |
| 0x106e5    | 1         | 1.37%   |
| 0x08600109 | 1         | 1.37%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 18        | 25%     |
| SandyBridge      | 11        | 15.28%  |
| Haswell          | 10        | 13.89%  |
| IvyBridge        | 6         | 8.33%   |
| Penryn           | 5         | 6.94%   |
| Westmere         | 4         | 5.56%   |
| Skylake          | 4         | 5.56%   |
| TigerLake        | 3         | 4.17%   |
| P6               | 2         | 2.78%   |
| Core             | 2         | 2.78%   |
| Zen 2            | 1         | 1.39%   |
| Silvermont       | 1         | 1.39%   |
| NetBurst         | 1         | 1.39%   |
| Nehalem          | 1         | 1.39%   |
| IceLake          | 1         | 1.39%   |
| Broadwell        | 1         | 1.39%   |
| Alderlake Hybrid | 1         | 1.39%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 62        | 65.26%  |
| Nvidia                           | 20        | 21.05%  |
| AMD                              | 12        | 12.63%  |
| Silicon Integrated Systems [SiS] | 1         | 1.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 9         | 9.09%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 6         | 6.06%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 5         | 5.05%   |
| Intel UHD Graphics 620                                                                | 4         | 4.04%   |
| Intel Core Processor Integrated Graphics Controller                                   | 4         | 4.04%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 3         | 3.03%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 3         | 3.03%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                   | 3         | 3.03%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                     | 3         | 3.03%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 3         | 3.03%   |
| Intel HD Graphics 630                                                                 | 3         | 3.03%   |
| Intel HD Graphics 620                                                                 | 3         | 3.03%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 3         | 3.03%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 3         | 3.03%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 2         | 2.02%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 2         | 2.02%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 2         | 2.02%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                | 2         | 2.02%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 2         | 2.02%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]         | 2         | 2.02%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                            | 2         | 2.02%   |
| Silicon Integrated Systems [SiS] 65x/M650/740 PCI/AGP VGA Display Adapter             | 1         | 1.01%   |
| Nvidia TU117M [GeForce MX450]                                                         | 1         | 1.01%   |
| Nvidia TU117GLM [Quadro T500 Mobile]                                                  | 1         | 1.01%   |
| Nvidia TU104GLM [Quadro RTX 4000 Mobile / Max-Q]                                      | 1         | 1.01%   |
| Nvidia GT218M [GeForce 310M]                                                          | 1         | 1.01%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 1         | 1.01%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                               | 1         | 1.01%   |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                              | 1         | 1.01%   |
| Nvidia GM108M [GeForce MX110]                                                         | 1         | 1.01%   |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                                 | 1         | 1.01%   |
| Nvidia GM107GLM [Quadro M1000M]                                                       | 1         | 1.01%   |
| Nvidia GK208M [GeForce GT 740M]                                                       | 1         | 1.01%   |
| Nvidia GK107M [GeForce GT 750M]                                                       | 1         | 1.01%   |
| Nvidia GK107M [GeForce 810M]                                                          | 1         | 1.01%   |
| Nvidia GK104GLM [Quadro K3100M]                                                       | 1         | 1.01%   |
| Nvidia GF116M [GeForce GT 555M/635M]                                                  | 1         | 1.01%   |
| Nvidia GF106M [GeForce GT 550M]                                                       | 1         | 1.01%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                            | 1         | 1.01%   |
| Nvidia C79 [GeForce 9400M]                                                            | 1         | 1.01%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 39        | 54.17%  |
| Intel + Nvidia | 15        | 20.83%  |
| Intel + AMD    | 8         | 11.11%  |
| 1 x Nvidia     | 5         | 6.94%   |
| 1 x AMD        | 4         | 5.56%   |
| 1 x SiS        | 1         | 1.39%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 56        | 77.78%  |
| Unknown     | 10        | 13.89%  |
| Proprietary | 6         | 8.33%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 48        | 66.67%  |
| 1.01-2.0   | 9         | 12.5%   |
| 0.51-1.0   | 8         | 11.11%  |
| 3.01-4.0   | 3         | 4.17%   |
| 0.01-0.5   | 2         | 2.78%   |
| 5.01-6.0   | 1         | 1.39%   |
| 2.01-3.0   | 1         | 1.39%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| LG Display          | 16        | 20%     |
| AU Optronics        | 12        | 15%     |
| Chimei Innolux      | 10        | 12.5%   |
| Samsung Electronics | 9         | 11.25%  |
| Dell                | 7         | 8.75%   |
| Lenovo              | 5         | 6.25%   |
| BOE                 | 4         | 5%      |
| Acer                | 3         | 3.75%   |
| PANDA               | 2         | 2.5%    |
| InnoLux Display     | 2         | 2.5%    |
| Goldstar            | 2         | 2.5%    |
| Sony                | 1         | 1.25%   |
| Sharp               | 1         | 1.25%   |
| MIT                 | 1         | 1.25%   |
| LG Philips          | 1         | 1.25%   |
| Hewlett-Packard     | 1         | 1.25%   |
| ASUSTek Computer    | 1         | 1.25%   |
| Apple               | 1         | 1.25%   |
| ALP                 | 1         | 1.25%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch           | 2         | 2.47%   |
| InnoLux Display LCD Monitor INL0014 1366x768 309x174mm 14.0-inch      | 2         | 2.47%   |
| Sony TV *02 SNY9403 1920x1080 1218x685mm 55.0-inch                    | 1         | 1.23%   |
| Sharp LCD Monitor SHP144D 3840x2160 276x156mm 12.5-inch               | 1         | 1.23%   |
| Samsung Electronics SMS22A300B SAM078E 1920x1080 477x268mm 21.5-inch  | 1         | 1.23%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch     | 1         | 1.23%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch  | 1         | 1.23%   |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch  | 1         | 1.23%   |
| Samsung Electronics LCD Monitor SEC4C42 1280x800 303x190mm 14.1-inch  | 1         | 1.23%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch  | 1         | 1.23%   |
| Samsung Electronics LCD Monitor SEC3155 1920x1200 367x230mm 17.1-inch | 1         | 1.23%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch  | 1         | 1.23%   |
| Samsung Electronics LCD Monitor SDC414D 3456x2160 336x210mm 15.6-inch | 1         | 1.23%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 1         | 1.23%   |
| PANDA LCD Monitor NCP0033 1920x1080 344x194mm 15.5-inch               | 1         | 1.23%   |
| MIT LCD Monitor MIT2011 3840x2160 1150x650mm 52.0-inch                | 1         | 1.23%   |
| MIT HDMI Matrix MIT2011 1920x1080 708x398mm 32.0-inch                 | 1         | 1.23%   |
| LG Philips LCD Monitor LPLC700 1280x800 331x207mm 15.4-inch           | 1         | 1.23%   |
| LG Display LCD Monitor LGD6616 1366x768 277x156mm 12.5-inch           | 1         | 1.23%   |
| LG Display LCD Monitor LGD05D4 1920x1080 344x194mm 15.5-inch          | 1         | 1.23%   |
| LG Display LCD Monitor LGD0525 1366x768 344x194mm 15.5-inch           | 1         | 1.23%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch           | 1         | 1.23%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 1         | 1.23%   |
| LG Display LCD Monitor LGD0450 1366x768 277x156mm 12.5-inch           | 1         | 1.23%   |
| LG Display LCD Monitor LGD03B7 1366x768 309x174mm 14.0-inch           | 1         | 1.23%   |
| LG Display LCD Monitor LGD036C 1366x768 277x156mm 12.5-inch           | 1         | 1.23%   |
| LG Display LCD Monitor LGD032C 1920x1080 344x194mm 15.5-inch          | 1         | 1.23%   |
| LG Display LCD Monitor LGD02FC 1920x1080 380x210mm 17.1-inch          | 1         | 1.23%   |
| LG Display LCD Monitor LGD02D9 1920x1080 344x194mm 15.5-inch          | 1         | 1.23%   |
| LG Display LCD Monitor LGD02C5 1920x1080 382x215mm 17.3-inch          | 1         | 1.23%   |
| LG Display LCD Monitor LGD0290 1366x768 293x165mm 13.2-inch           | 1         | 1.23%   |
| LG Display LCD Monitor LGD0289 1600x900 382x215mm 17.3-inch           | 1         | 1.23%   |
| Lenovo T24i-10 LEN61A6 1920x1080 527x296mm 23.8-inch                  | 1         | 1.23%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x194mm 15.5-inch               | 1         | 1.23%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch               | 1         | 1.23%   |
| Lenovo LCD Monitor LEN4010 1280x800 261x163mm 12.1-inch               | 1         | 1.23%   |
| Lenovo LCD Monitor LEN4000 1024x768 246x185mm 12.1-inch               | 1         | 1.23%   |
| Hewlett-Packard E232 HWP3279 1920x1080 509x286mm 23.0-inch            | 1         | 1.23%   |
| Goldstar W2252 GSM567E 1680x1050 474x296mm 22.0-inch                  | 1         | 1.23%   |
| Goldstar L192WS GSM4B32 1440x900 410x256mm 19.0-inch                  | 1         | 1.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 26        | 35.62%  |
| 1366x768 (WXGA)    | 23        | 31.51%  |
| 1280x800 (WXGA)    | 7         | 9.59%   |
| 1600x900 (HD+)     | 4         | 5.48%   |
| 3840x2160 (4K)     | 3         | 4.11%   |
| 1280x1024 (SXGA)   | 3         | 4.11%   |
| 1440x900 (WXGA+)   | 2         | 2.74%   |
| 3456x2160          | 1         | 1.37%   |
| 2560x1440 (QHD)    | 1         | 1.37%   |
| 1920x1200 (WUXGA)  | 1         | 1.37%   |
| 1680x1050 (WSXGA+) | 1         | 1.37%   |
| 1600x1200          | 1         | 1.37%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 30        | 37.04%  |
| 17      | 8         | 9.88%   |
| 13      | 8         | 9.88%   |
| 14      | 7         | 8.64%   |
| 12      | 7         | 8.64%   |
| 24      | 4         | 4.94%   |
| 23      | 4         | 4.94%   |
| 19      | 4         | 4.94%   |
| 27      | 3         | 3.7%    |
| 55      | 1         | 1.23%   |
| 52      | 1         | 1.23%   |
| 36      | 1         | 1.23%   |
| 21      | 1         | 1.23%   |
| 20      | 1         | 1.23%   |
| Unknown | 1         | 1.23%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 41        | 51.25%  |
| 501-600     | 10        | 12.5%   |
| 351-400     | 10        | 12.5%   |
| 201-300     | 10        | 12.5%   |
| 401-500     | 5         | 6.25%   |
| 1001-1500   | 2         | 2.5%    |
| 701-800     | 1         | 1.25%   |
| Unknown     | 1         | 1.25%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 50        | 74.63%  |
| 16/10   | 10        | 14.93%  |
| 5/4     | 3         | 4.48%   |
| 3/2     | 2         | 2.99%   |
| 4/3     | 1         | 1.49%   |
| Unknown | 1         | 1.49%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 30        | 37.5%   |
| 81-90          | 13        | 16.25%  |
| 61-70          | 7         | 8.75%   |
| 201-250        | 7         | 8.75%   |
| 121-130        | 6         | 7.5%    |
| 151-200        | 5         | 6.25%   |
| 301-350        | 3         | 3.75%   |
| More than 1000 | 2         | 2.5%    |
| 71-80          | 2         | 2.5%    |
| 251-300        | 1         | 1.25%   |
| 141-150        | 1         | 1.25%   |
| 131-140        | 1         | 1.25%   |
| 501-1000       | 1         | 1.25%   |
| Unknown        | 1         | 1.25%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 30        | 37.97%  |
| 101-120       | 24        | 30.38%  |
| 51-100        | 20        | 25.32%  |
| More than 240 | 3         | 3.8%    |
| 1-50          | 1         | 1.27%   |
| Unknown       | 1         | 1.27%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 47        | 63.51%  |
| 2     | 18        | 24.32%  |
| 0     | 8         | 10.81%  |
| 3     | 1         | 1.35%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 51        | 43.22%  |
| Realtek Semiconductor             | 29        | 24.58%  |
| Qualcomm Atheros                  | 19        | 16.1%   |
| Broadcom                          | 5         | 4.24%   |
| TP-Link                           | 3         | 2.54%   |
| Xilinx                            | 1         | 0.85%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.85%   |
| Ralink Technology                 | 1         | 0.85%   |
| Ralink                            | 1         | 0.85%   |
| Qualcomm Atheros Communications   | 1         | 0.85%   |
| Nvidia                            | 1         | 0.85%   |
| Marvell Technology Group          | 1         | 0.85%   |
| Huawei Technologies               | 1         | 0.85%   |
| Ericsson Business Mobile Networks | 1         | 0.85%   |
| Edimax Technology                 | 1         | 0.85%   |
| ASIX Electronics                  | 1         | 0.85%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 15        | 10.07%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 9         | 6.04%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 7         | 4.7%    |
| Intel Wireless 7260                                                     | 5         | 3.36%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4         | 2.68%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 2.68%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 2.68%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 2.01%   |
| Intel Ethernet Connection I217-LM                                       | 3         | 2.01%   |
| Intel 82577LM Gigabit Network Connection                                | 3         | 2.01%   |
| Intel 82567LM Gigabit Network Connection                                | 3         | 2.01%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 2         | 1.34%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 1.34%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 1.34%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller               | 2         | 1.34%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 1.34%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.34%   |
| Intel Wireless 8265 / 8275                                              | 2         | 1.34%   |
| Intel Wireless 8260                                                     | 2         | 1.34%   |
| Intel Wireless 7265                                                     | 2         | 1.34%   |
| Intel Wireless 3165                                                     | 2         | 1.34%   |
| Intel Wi-Fi 6 AX201                                                     | 2         | 1.34%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 2         | 1.34%   |
| Intel Ethernet Connection (4) I219-V                                    | 2         | 1.34%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 1.34%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 2         | 1.34%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 1.34%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                           | 2         | 1.34%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 1.34%   |
| Intel 82566MM Gigabit Network Connection                                | 2         | 1.34%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 2         | 1.34%   |
| Xilinx Ethernet controller                                              | 1         | 0.67%   |
| TP-Link USB 10/100 LAN                                                  | 1         | 0.67%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]         | 1         | 0.67%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 1         | 0.67%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet               | 1         | 0.67%   |
| Silicon Integrated Systems [SiS] AC'97 Modem Controller                 | 1         | 0.67%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.67%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 0.67%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                         | 1         | 0.67%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 47        | 61.04%  |
| Qualcomm Atheros                | 15        | 19.48%  |
| Realtek Semiconductor           | 6         | 7.79%   |
| Broadcom                        | 4         | 5.19%   |
| TP-Link                         | 1         | 1.3%    |
| Ralink Technology               | 1         | 1.3%    |
| Ralink                          | 1         | 1.3%    |
| Qualcomm Atheros Communications | 1         | 1.3%    |
| Edimax Technology               | 1         | 1.3%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                                           | 5         | 6.49%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 4         | 5.19%   |
| Intel Wi-Fi 6 AX200                                                           | 4         | 5.19%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 4         | 5.19%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 3         | 3.9%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 2         | 2.6%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 2         | 2.6%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 2         | 2.6%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 2         | 2.6%    |
| Intel Wireless 8265 / 8275                                                    | 2         | 2.6%    |
| Intel Wireless 8260                                                           | 2         | 2.6%    |
| Intel Wireless 7265                                                           | 2         | 2.6%    |
| Intel Wireless 3165                                                           | 2         | 2.6%    |
| Intel Wi-Fi 6 AX201                                                           | 2         | 2.6%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                       | 2         | 2.6%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 2         | 2.6%    |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                 | 2         | 2.6%    |
| Intel Centrino Ultimate-N 6300                                                | 2         | 2.6%    |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                                 | 2         | 2.6%    |
| Intel Centrino Advanced-N 6200                                                | 2         | 2.6%    |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                        | 2         | 2.6%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 1         | 1.3%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 1.3%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1         | 1.3%    |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                               | 1         | 1.3%    |
| Realtek RTL8723DE Wireless Network Adapter                                    | 1         | 1.3%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 1         | 1.3%    |
| Realtek RTL8188EE Wireless Network Adapter                                    | 1         | 1.3%    |
| Ralink Conceptronic C300RU v2 802.11bgn Wireless Adapter [Ralink RT2770]      | 1         | 1.3%    |
| Ralink RT2500 Wireless 802.11bg                                               | 1         | 1.3%    |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271] | 1         | 1.3%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1         | 1.3%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 1         | 1.3%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 1         | 1.3%    |
| Intel Ultimate N WiFi Link 5300                                               | 1         | 1.3%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                               | 1         | 1.3%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1         | 1.3%    |
| Intel Centrino Wireless-N 135                                                 | 1         | 1.3%    |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                  | 1         | 1.3%    |
| Intel Centrino Advanced-N 6235                                                | 1         | 1.3%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 27        | 39.13%  |
| Realtek Semiconductor            | 26        | 37.68%  |
| Qualcomm Atheros                 | 7         | 10.14%  |
| TP-Link                          | 2         | 2.9%    |
| Xilinx                           | 1         | 1.45%   |
| Silicon Integrated Systems [SiS] | 1         | 1.45%   |
| Nvidia                           | 1         | 1.45%   |
| Marvell Technology Group         | 1         | 1.45%   |
| Huawei Technologies              | 1         | 1.45%   |
| Broadcom                         | 1         | 1.45%   |
| ASIX Electronics                 | 1         | 1.45%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 15        | 21.43%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 12.86%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 10%     |
| Intel Ethernet Connection I217-LM                                 | 3         | 4.29%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 4.29%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 4.29%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 2.86%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 2.86%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 2.86%   |
| Intel 82566MM Gigabit Network Connection                          | 2         | 2.86%   |
| Xilinx Ethernet controller                                        | 1         | 1.43%   |
| TP-Link USB 10/100 LAN                                            | 1         | 1.43%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 1.43%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet         | 1         | 1.43%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.43%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.43%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.43%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.43%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 1.43%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 1.43%   |
| Nvidia MCP79 Ethernet                                             | 1         | 1.43%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 1.43%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.43%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 1.43%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 1.43%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.43%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.43%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.43%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 1.43%   |
| Huawei ALP-AL00                                                   | 1         | 1.43%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.43%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 1.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 72        | 51.8%   |
| Ethernet | 65        | 46.76%  |
| Modem    | 2         | 1.44%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 54        | 69.23%  |
| Ethernet | 24        | 30.77%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 62        | 86.11%  |
| 1     | 9         | 12.5%   |
| 3     | 1         | 1.39%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 65        | 87.84%  |
| Yes  | 9         | 12.16%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 28        | 51.85%  |
| Qualcomm Atheros Communications | 9         | 16.67%  |
| Realtek Semiconductor           | 4         | 7.41%   |
| Broadcom                        | 4         | 7.41%   |
| Dell                            | 3         | 5.56%   |
| Lite-On Technology              | 1         | 1.85%   |
| IMC Networks                    | 1         | 1.85%   |
| Foxconn / Hon Hai               | 1         | 1.85%   |
| ASUSTek Computer                | 1         | 1.85%   |
| Apple                           | 1         | 1.85%   |
| Alps Electric                   | 1         | 1.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 11        | 20.37%  |
| Intel Bluetooth Device                                                              | 4         | 7.41%   |
| Intel AX200 Bluetooth                                                               | 4         | 7.41%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 3         | 5.56%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 3         | 5.56%   |
| Intel AX201 Bluetooth                                                               | 3         | 5.56%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 2         | 3.7%    |
| Realtek Bluetooth Radio                                                             | 2         | 3.7%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 2         | 3.7%    |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 2         | 3.7%    |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 2         | 3.7%    |
| Dell DW375 Bluetooth Module                                                         | 2         | 3.7%    |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 2         | 3.7%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 1.85%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 1.85%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 1.85%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 1.85%   |
| IMC Networks Bluetooth Device                                                       | 1         | 1.85%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.85%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 1.85%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 1.85%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 1         | 1.85%   |
| ASUS BT-270 Bluetooth Adapter                                                       | 1         | 1.85%   |
| Apple Bluetooth Host Controller                                                     | 1         | 1.85%   |
| Alps Electric UGTZ4 Bluetooth                                                       | 1         | 1.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 68        | 82.93%  |
| Nvidia                           | 6         | 7.32%   |
| AMD                              | 4         | 4.88%   |
| Silicon Integrated Systems [SiS] | 1         | 1.22%   |
| Realtek Semiconductor            | 1         | 1.22%   |
| Lenovo                           | 1         | 1.22%   |
| GN Netcom                        | 1         | 1.22%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 11        | 11.7%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 10        | 10.64%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6         | 6.38%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 5.32%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 5.32%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 5.32%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 5.32%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 4.26%   |
| Intel CM238 HD Audio Controller                                                                   | 4         | 4.26%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 3.19%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 3.19%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 3.19%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 3.19%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 2.13%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 2.13%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller                                   | 1         | 1.06%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 1.06%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 1.06%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 1.06%   |
| Nvidia stereo controller                                                                          | 1         | 1.06%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 1.06%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 1.06%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 1.06%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 1         | 1.06%   |
| Lenovo ThinkPad Dock USB Audio                                                                    | 1         | 1.06%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 1.06%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 1.06%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 1.06%   |
| Intel Broadwell-U Audio Controller                                                                | 1         | 1.06%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.06%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 1         | 1.06%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 1.06%   |
| GN Netcom Jabra SPEAK 510 USB                                                                     | 1         | 1.06%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 1         | 1.06%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 1.06%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 1         | 1.06%   |
| AMD IXP SB4x0 High Definition Audio Controller                                                    | 1         | 1.06%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 1         | 1.06%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 19        | 29.69%  |
| SK hynix            | 15        | 23.44%  |
| Kingston            | 8         | 12.5%   |
| Unknown             | 6         | 9.38%   |
| Micron Technology   | 4         | 6.25%   |
| Crucial             | 3         | 4.69%   |
| A-DATA Technology   | 3         | 4.69%   |
| Wilk                | 1         | 1.56%   |
| Transcend           | 1         | 1.56%   |
| Ramaxel Technology  | 1         | 1.56%   |
| Nanya Technology    | 1         | 1.56%   |
| Elpida              | 1         | 1.56%   |
| Apacer              | 1         | 1.56%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s    | 2         | 2.99%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s    | 2         | 2.99%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 2         | 2.99%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 2         | 2.99%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s        | 2         | 2.99%   |
| Samsung RAM M471A2G44AM0-CWE 16384MB SODIMM DDR4 3200MT/s    | 2         | 2.99%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s        | 2         | 2.99%   |
| Wilk RAM GR3200S464L22/16G 16GB SODIMM DDR4 3200MT/s         | 1         | 1.49%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                  | 1         | 1.49%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s               | 1         | 1.49%   |
| Unknown RAM Module 4096MB SODIMM DDR3                        | 1         | 1.49%   |
| Unknown RAM Module 4096MB SODIMM DDR2 667MT/s                | 1         | 1.49%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                | 1         | 1.49%   |
| Unknown RAM Module 1024MB SODIMM DRAM                        | 1         | 1.49%   |
| Transcend RAM JM2666HSB-16G 16GB SODIMM DDR4 2667MT/s        | 1         | 1.49%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2133MT/s              | 1         | 1.49%   |
| SK hynix RAM HMT451S6CFR6A-PB 4096MB SODIMM DDR3 1600MT/s    | 1         | 1.49%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.49%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s    | 1         | 1.49%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.49%   |
| SK hynix RAM HMT325S6CFR8C-PB 2048MB SODIMM DDR3 1600MT/s    | 1         | 1.49%   |
| SK hynix RAM HMT325S6BFR8C-H9 2048MB SODIMM DDR3 1333MT/s    | 1         | 1.49%   |
| SK hynix RAM HMCG78MEBSA095N 16GB SODIMM DDR5 4800MT/s       | 1         | 1.49%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s       | 1         | 1.49%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s      | 1         | 1.49%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s       | 1         | 1.49%   |
| Samsung RAM Module 4096MB SODIMM DDR4 2667MT/s               | 1         | 1.49%   |
| Samsung RAM Module 2048MB SODIMM DDR2 667MT/s                | 1         | 1.49%   |
| Samsung RAM Module 16384MB SODIMM DDR4 3200MT/s              | 1         | 1.49%   |
| Samsung RAM Module 1024MB SODIMM DDR2 667MT/s                | 1         | 1.49%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s        | 1         | 1.49%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 1.49%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s        | 1         | 1.49%   |
| Samsung RAM M471A5244BB0-CPB 4GB SODIMM DDR4 2400MT/s        | 1         | 1.49%   |
| Samsung RAM M471A2K43BB1-CRC 16GB SODIMM DDR4 2400MT/s       | 1         | 1.49%   |
| Samsung RAM M471A1K44BM0-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 1.49%   |
| Samsung RAM K4E6E304EE-EGCE 4096MB SODIMM LPDDR3 1600MT/s    | 1         | 1.49%   |
| Samsung RAM K4E6E304EB-EGCG 4GB Row Of Chips LPDDR3 2133MT/s | 1         | 1.49%   |
| Ramaxel RAM RMSA3260MB78HAF2400 8GB SODIMM DDR4 2400MT/s     | 1         | 1.49%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s         | 1         | 1.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 25        | 45.45%  |
| DDR4   | 21        | 38.18%  |
| DDR2   | 4         | 7.27%   |
| LPDDR3 | 2         | 3.64%   |
| SDRAM  | 1         | 1.82%   |
| DRAM   | 1         | 1.82%   |
| DDR5   | 1         | 1.82%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 54        | 98.18%  |
| Row Of Chips | 1         | 1.82%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 24        | 39.34%  |
| 8192  | 17        | 27.87%  |
| 16384 | 9         | 14.75%  |
| 2048  | 8         | 13.11%  |
| 1024  | 2         | 3.28%   |
| 32768 | 1         | 1.64%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 15        | 24.19%  |
| 2667    | 13        | 20.97%  |
| 3200    | 7         | 11.29%  |
| 1333    | 7         | 11.29%  |
| 1334    | 4         | 6.45%   |
| 2400    | 3         | 4.84%   |
| 667     | 3         | 4.84%   |
| 3266    | 2         | 3.23%   |
| 2133    | 2         | 3.23%   |
| Unknown | 2         | 3.23%   |
| 4800    | 1         | 1.61%   |
| 4199    | 1         | 1.61%   |
| 1067    | 1         | 1.61%   |
| 800     | 1         | 1.61%   |

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
| Samsung M288x Series | 1         | 100%    |

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
| Chicony Electronics                    | 10        | 17.24%  |
| Sunplus Innovation Technology          | 6         | 10.34%  |
| Microdia                               | 6         | 10.34%  |
| Quanta                                 | 5         | 8.62%   |
| IMC Networks                           | 5         | 8.62%   |
| Realtek Semiconductor                  | 4         | 6.9%    |
| Suyin                                  | 3         | 5.17%   |
| Ricoh                                  | 2         | 3.45%   |
| Logitech                               | 2         | 3.45%   |
| Lite-On Technology                     | 2         | 3.45%   |
| Bison Electronics                      | 2         | 3.45%   |
| Apple                                  | 2         | 3.45%   |
| Acer                                   | 2         | 3.45%   |
| Syntek                                 | 1         | 1.72%   |
| Silicon Motion                         | 1         | 1.72%   |
| Samsung Electronics                    | 1         | 1.72%   |
| Microsoft                              | 1         | 1.72%   |
| Generalplus Technology                 | 1         | 1.72%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.72%   |
| Alcor Micro                            | 1         | 1.72%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD            | 4         | 6.9%    |
| Sunplus Integrated_Webcam_HD             | 3         | 5.17%   |
| IMC Networks Integrated Camera           | 3         | 5.17%   |
| Suyin Integrated Webcam                  | 2         | 3.45%   |
| Quanta Laptop_Integrated_Webcam_2HDM     | 2         | 3.45%   |
| Chicony HP HD Camera                     | 2         | 3.45%   |
| Syntek EasyCamera                        | 1         | 1.72%   |
| Suyin Asus Integrated Webcam [CN031B]    | 1         | 1.72%   |
| Sunplus Laptop_Integrated_Webcam_HD      | 1         | 1.72%   |
| Sunplus Integrated Webcam                | 1         | 1.72%   |
| Sunplus 1.3M HD WebCam                   | 1         | 1.72%   |
| Silicon Motion WebCam SC-10HDD12636N     | 1         | 1.72%   |
| Samsung Galaxy series, misc. (MTP mode)  | 1         | 1.72%   |
| Ricoh Laptop_Integrated_Webcam_FHD       | 1         | 1.72%   |
| Ricoh HD Webcam                          | 1         | 1.72%   |
| Realtek USB2.0 VGA UVC WebCam            | 1         | 1.72%   |
| Realtek USB2.0 HD UVC WebCam             | 1         | 1.72%   |
| Realtek Lenovo EasyCamera                | 1         | 1.72%   |
| Realtek Integrated Webcam HD             | 1         | 1.72%   |
| Quanta USB HD Webcam                     | 1         | 1.72%   |
| Quanta HP Webcam                         | 1         | 1.72%   |
| Quanta HP Full-HD Camera                 | 1         | 1.72%   |
| Microsoft LifeCam NX-6000                | 1         | 1.72%   |
| Microdia Laptop_Integrated_Webcam_HD     | 1         | 1.72%   |
| Microdia Dell Integrated HD Webcam       | 1         | 1.72%   |
| Logitech Webcam C170                     | 1         | 1.72%   |
| Logitech C922 Pro Stream Webcam          | 1         | 1.72%   |
| Lite-On HP HD Webcam                     | 1         | 1.72%   |
| Lite-On HP HD Camera                     | 1         | 1.72%   |
| IMC Networks USB2.0 HD UVC WebCam        | 1         | 1.72%   |
| IMC Networks HD Camera                   | 1         | 1.72%   |
| Generalplus 808 Camera #9 (web-cam mode) | 1         | 1.72%   |
| Chicony USB2.0 Camera                    | 1         | 1.72%   |
| Chicony TOSHIBA Web Camera - HD          | 1         | 1.72%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 1         | 1.72%   |
| Chicony HP Wide Vision HD Camera         | 1         | 1.72%   |
| Chicony HP Webcam [2 MP Macro]           | 1         | 1.72%   |
| Chicony HP Truevision HD                 | 1         | 1.72%   |
| Chicony HD WebCam                        | 1         | 1.72%   |
| Chicony HD User Facing                   | 1         | 1.72%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Validity Sensors   | 6         | 33.33%  |
| Synaptics          | 5         | 27.78%  |
| AuthenTec          | 4         | 22.22%  |
| STMicroelectronics | 2         | 11.11%  |
| Upek               | 1         | 5.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 3         | 16.67%  |
| AuthenTec AES2810                                                          | 3         | 16.67%  |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 11.11%  |
| STMicroelectronics Fingerprint Reader                                      | 2         | 11.11%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 5.56%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 5.56%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 5.56%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 5.56%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 5.56%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 5.56%   |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 5.56%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 5.56%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Broadcom         | 7         | 77.78%  |
| SCM Microsystems | 1         | 11.11%  |
| Lenovo           | 1         | 11.11%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 44.44%  |
| Broadcom 5880                                                                | 2         | 22.22%  |
| SCM Microsystems SCR331 SmartCard Reader                                     | 1         | 11.11%  |
| Lenovo Integrated Smart Card Reader                                          | 1         | 11.11%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 11.11%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 31        | 41.89%  |
| 0     | 27        | 36.49%  |
| 2     | 10        | 13.51%  |
| 4     | 3         | 4.05%   |
| 5     | 2         | 2.7%    |
| 3     | 1         | 1.35%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 19        | 27.94%  |
| Fingerprint reader       | 18        | 26.47%  |
| Communication controller | 9         | 13.24%  |
| Net/wireless             | 7         | 10.29%  |
| Chipcard                 | 6         | 8.82%   |
| Sound                    | 3         | 4.41%   |
| Storage                  | 2         | 2.94%   |
| Net/ethernet             | 2         | 2.94%   |
| Storage/raid             | 1         | 1.47%   |
| Multimedia controller    | 1         | 1.47%   |

