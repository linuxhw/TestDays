ALT Linux - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for ALT Linux.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

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

Total: 101

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | Unknown                     | [e989736b06](https://linux-hardware.org/?probe=e989736b06) | Mar 30, 2022 |
| HP            | Unknown                     | [672d3c8b62](https://linux-hardware.org/?probe=672d3c8b62) | Mar 29, 2022 |
| HP            | 250 G3                      | [22f691edac](https://linux-hardware.org/?probe=22f691edac) | Mar 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [e4b8a2cc11](https://linux-hardware.org/?probe=e4b8a2cc11) | Mar 23, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [64baae5b88](https://linux-hardware.org/?probe=64baae5b88) | Mar 22, 2022 |
| ICL           | NJ50_70CU                   | [247859eb78](https://linux-hardware.org/?probe=247859eb78) | Mar 22, 2022 |
| ICL           | NJ50_70CU                   | [b9e82b8490](https://linux-hardware.org/?probe=b9e82b8490) | Mar 22, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [58fdf49095](https://linux-hardware.org/?probe=58fdf49095) | Mar 17, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [eaa9fb6aad](https://linux-hardware.org/?probe=eaa9fb6aad) | Mar 14, 2022 |
| 3Logic Gro... | Graviton N15i-K2            | [72eefd2811](https://linux-hardware.org/?probe=72eefd2811) | Mar 14, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [55533901d3](https://linux-hardware.org/?probe=55533901d3) | Mar 11, 2022 |
| Dell          | G5 5590                     | [9b95f2ae1d](https://linux-hardware.org/?probe=9b95f2ae1d) | Mar 06, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [13bc7e73f1](https://linux-hardware.org/?probe=13bc7e73f1) | Mar 02, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [ef592cb1a7](https://linux-hardware.org/?probe=ef592cb1a7) | Feb 26, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [c907453bf5](https://linux-hardware.org/?probe=c907453bf5) | Feb 18, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [3986a62bca](https://linux-hardware.org/?probe=3986a62bca) | Feb 15, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [f0c89a4e5b](https://linux-hardware.org/?probe=f0c89a4e5b) | Feb 15, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [cf41cc6ddb](https://linux-hardware.org/?probe=cf41cc6ddb) | Feb 15, 2022 |
| ASUSTek       | X200MA                      | [b2f1d59884](https://linux-hardware.org/?probe=b2f1d59884) | Feb 12, 2022 |
| Timi          | TM1701                      | [4edeb14964](https://linux-hardware.org/?probe=4edeb14964) | Feb 05, 2022 |
| DEPO Compu... | DPC156                      | [4fb49336e5](https://linux-hardware.org/?probe=4fb49336e5) | Feb 03, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [a08b9de6fa](https://linux-hardware.org/?probe=a08b9de6fa) | Jan 28, 2022 |
| Dell          | Latitude 3590               | [e2a6ef3266](https://linux-hardware.org/?probe=e2a6ef3266) | Jan 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [00f8c9d649](https://linux-hardware.org/?probe=00f8c9d649) | Jan 02, 2022 |
| Samsung       | 750XDA                      | [8fe8612ccb](https://linux-hardware.org/?probe=8fe8612ccb) | Dec 21, 2021 |
| Acer          | Aspire 5750G                | [58cdbcf87e](https://linux-hardware.org/?probe=58cdbcf87e) | Dec 18, 2021 |
| ASUSTek       | N46VZ                       | [aaf9eff6bd](https://linux-hardware.org/?probe=aaf9eff6bd) | Oct 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [2839eb3d12](https://linux-hardware.org/?probe=2839eb3d12) | Oct 09, 2021 |
| HP            | Laptop 15s-fq0xxx           | [516882d907](https://linux-hardware.org/?probe=516882d907) | Sep 23, 2021 |
| Timi          | TM1701                      | [b13b26d7ca](https://linux-hardware.org/?probe=b13b26d7ca) | Sep 16, 2021 |
| ASUSTek       | N46VZ                       | [40c97b439e](https://linux-hardware.org/?probe=40c97b439e) | Sep 12, 2021 |
| Acer          | Aspire A317-32              | [09342414f3](https://linux-hardware.org/?probe=09342414f3) | Sep 09, 2021 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [6648ff785e](https://linux-hardware.org/?probe=6648ff785e) | Sep 08, 2021 |
| ASUSTek       | N46VZ                       | [eb37b7db1e](https://linux-hardware.org/?probe=eb37b7db1e) | Aug 11, 2021 |
| Acer          | Swift SF314-57              | [2872bd6b13](https://linux-hardware.org/?probe=2872bd6b13) | Aug 05, 2021 |
| Durabook      | Z14                         | [7abdb375e2](https://linux-hardware.org/?probe=7abdb375e2) | Jul 27, 2021 |
| Lenovo        | ThinkPad L13 Gen 2 20VH0... | [a85464aae6](https://linux-hardware.org/?probe=a85464aae6) | Jul 06, 2021 |
| Aquarius      | NS585                       | [bc10f2ffbd](https://linux-hardware.org/?probe=bc10f2ffbd) | Jun 27, 2021 |
| Dell          | G3 3779                     | [eaf53820e5](https://linux-hardware.org/?probe=eaf53820e5) | Jun 02, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [9908ba82e9](https://linux-hardware.org/?probe=9908ba82e9) | May 31, 2021 |
| Lenovo        | ThinkPad L13 Gen 2 20VH0... | [9f3a13c865](https://linux-hardware.org/?probe=9f3a13c865) | May 27, 2021 |
| HP            | Laptop 17-by0xxx            | [a3f263e12b](https://linux-hardware.org/?probe=a3f263e12b) | May 26, 2021 |
| Dell          | Inspiron 3542               | [e1a816cc42](https://linux-hardware.org/?probe=e1a816cc42) | May 25, 2021 |
| MSI           | GE72 7RE                    | [a6a5258971](https://linux-hardware.org/?probe=a6a5258971) | May 20, 2021 |
| ASUSTek       | N46VZ                       | [62c6944a06](https://linux-hardware.org/?probe=62c6944a06) | May 19, 2021 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [59740e6ccf](https://linux-hardware.org/?probe=59740e6ccf) | Apr 29, 2021 |
| HP            | EliteBook 8470p             | [632deaf397](https://linux-hardware.org/?probe=632deaf397) | Apr 16, 2021 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [8185306af7](https://linux-hardware.org/?probe=8185306af7) | Apr 16, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [ea2ab7cbc7](https://linux-hardware.org/?probe=ea2ab7cbc7) | Apr 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [3afcb7ca65](https://linux-hardware.org/?probe=3afcb7ca65) | Mar 29, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [66f3887fa2](https://linux-hardware.org/?probe=66f3887fa2) | Mar 20, 2021 |
| HP            | Pavilion Laptop 15-cc5xx    | [2c576fb8a9](https://linux-hardware.org/?probe=2c576fb8a9) | Mar 17, 2021 |
| HP            | Laptop 15s-fq2xxx           | [2d8bd02af5](https://linux-hardware.org/?probe=2d8bd02af5) | Feb 09, 2021 |
| ASUSTek       | N46VZ                       | [af521df7b9](https://linux-hardware.org/?probe=af521df7b9) | Jan 16, 2021 |
| Lenovo        | B50-10 80QR                 | [211bf1a4b4](https://linux-hardware.org/?probe=211bf1a4b4) | Jan 15, 2021 |
| Acer          | NC-ES1-131-C1NL             | [1cae46f14f](https://linux-hardware.org/?probe=1cae46f14f) | Jan 09, 2021 |
| HP            | Laptop 15s-fq0xxx           | [2437a45956](https://linux-hardware.org/?probe=2437a45956) | Jan 07, 2021 |
| HP            | EliteBook 8470p             | [ed90389918](https://linux-hardware.org/?probe=ed90389918) | Dec 22, 2020 |
| Lenovo        | ThinkPad X220 4291M85       | [f2c165b2d8](https://linux-hardware.org/?probe=f2c165b2d8) | Dec 22, 2020 |
| ASUSTek       | X510UNR                     | [53ef89172e](https://linux-hardware.org/?probe=53ef89172e) | Dec 21, 2020 |
| ASUSTek       | N46VZ                       | [d17038f482](https://linux-hardware.org/?probe=d17038f482) | Dec 17, 2020 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [00824d4fae](https://linux-hardware.org/?probe=00824d4fae) | Nov 19, 2020 |
| HP            | Laptop 14s-dq1xxx           | [f6e0ab4b2b](https://linux-hardware.org/?probe=f6e0ab4b2b) | Nov 13, 2020 |
| Toshiba       | Satellite A100              | [f09cd03fff](https://linux-hardware.org/?probe=f09cd03fff) | Nov 09, 2020 |
| MSI           | X300/X340/X400 series       | [1fd45a8e47](https://linux-hardware.org/?probe=1fd45a8e47) | Oct 23, 2020 |
| Lenovo        | B50-10 80QR                 | [ae14993850](https://linux-hardware.org/?probe=ae14993850) | Sep 28, 2020 |
| ASUSTek       | N46VZ                       | [d1ba7fa191](https://linux-hardware.org/?probe=d1ba7fa191) | Sep 23, 2020 |
| ASUSTek       | N46VZ                       | [ee23f7cefc](https://linux-hardware.org/?probe=ee23f7cefc) | Sep 14, 2020 |
| ASUSTek       | N46VZ                       | [52930a9597](https://linux-hardware.org/?probe=52930a9597) | Sep 03, 2020 |
| ASUSTek       | N46VZ                       | [0ac9b22881](https://linux-hardware.org/?probe=0ac9b22881) | Sep 03, 2020 |
| ASUSTek       | N46VZ                       | [0a8a235308](https://linux-hardware.org/?probe=0a8a235308) | Aug 24, 2020 |
| ASUSTek       | N46VZ                       | [c1e8898d0b](https://linux-hardware.org/?probe=c1e8898d0b) | Aug 24, 2020 |
| ASUSTek       | N46VZ                       | [1c45537256](https://linux-hardware.org/?probe=1c45537256) | Aug 14, 2020 |
| ASUSTek       | N46VZ                       | [9998e51d1c](https://linux-hardware.org/?probe=9998e51d1c) | Aug 14, 2020 |
| ASUSTek       | N46VZ                       | [a7c66e41c7](https://linux-hardware.org/?probe=a7c66e41c7) | Aug 14, 2020 |
| Samsung       | R510/P510                   | [e20ff4ae24](https://linux-hardware.org/?probe=e20ff4ae24) | Jul 12, 2020 |
| Lenovo        | B50-10 80QR                 | [a50e0f999e](https://linux-hardware.org/?probe=a50e0f999e) | Jul 07, 2020 |
| HP            | 255 G2                      | [3d4e8b4672](https://linux-hardware.org/?probe=3d4e8b4672) | May 27, 2020 |
| ASUSTek       | N46VZ                       | [fca4008513](https://linux-hardware.org/?probe=fca4008513) | May 23, 2020 |
| Acer          | Aspire E1-571G              | [3290540c34](https://linux-hardware.org/?probe=3290540c34) | Mar 13, 2020 |
| Lenovo        | 3000 G430 4153/200          | [0315e41f8c](https://linux-hardware.org/?probe=0315e41f8c) | Dec 26, 2019 |
| HP            | Pavilion dv6700             | [1031d661db](https://linux-hardware.org/?probe=1031d661db) | Nov 24, 2019 |
| HP            | Pavilion dv6700             | [c2fc59b6de](https://linux-hardware.org/?probe=c2fc59b6de) | Nov 23, 2019 |
| ASUSTek       | N46VZ                       | [00c438c052](https://linux-hardware.org/?probe=00c438c052) | Nov 01, 2019 |
| ASUSTek       | N46VZ                       | [bee323a814](https://linux-hardware.org/?probe=bee323a814) | Oct 29, 2019 |
| eMachines     | eME728                      | [83010f511e](https://linux-hardware.org/?probe=83010f511e) | Oct 25, 2019 |
| ASUSTek       | X200MA                      | [595d1ddd1b](https://linux-hardware.org/?probe=595d1ddd1b) | Oct 25, 2019 |
| ASUSTek       | N46VZ                       | [0974f428e0](https://linux-hardware.org/?probe=0974f428e0) | Sep 28, 2019 |
| MSI           | MEGA BOOK S430              | [6380916978](https://linux-hardware.org/?probe=6380916978) | Sep 15, 2019 |
| Lenovo        | G505s 20255                 | [46308d3b71](https://linux-hardware.org/?probe=46308d3b71) | Aug 30, 2019 |
| Lenovo        | G505s 20255                 | [8fc1a0caf2](https://linux-hardware.org/?probe=8fc1a0caf2) | Aug 30, 2019 |
| Lenovo        | G505s 20255                 | [c840002848](https://linux-hardware.org/?probe=c840002848) | Aug 30, 2019 |
| ASUSTek       | 1101HA                      | [f221bcd7e4](https://linux-hardware.org/?probe=f221bcd7e4) | Aug 16, 2019 |
| ASUSTek       | N46VZ                       | [731932629b](https://linux-hardware.org/?probe=731932629b) | Aug 15, 2019 |
| ASUSTek       | N46VZ                       | [aec6cff1b5](https://linux-hardware.org/?probe=aec6cff1b5) | Aug 15, 2019 |
| Samsung       | RV413/RV513/E3413           | [3e37ab573a](https://linux-hardware.org/?probe=3e37ab573a) | Apr 24, 2019 |
| Samsung       | RV413/RV513/E3413           | [447cdad389](https://linux-hardware.org/?probe=447cdad389) | Apr 23, 2019 |
| Acer          | Aspire ES1-523              | [0f6abd34f2](https://linux-hardware.org/?probe=0f6abd34f2) | Dec 17, 2018 |
| ASUSTek       | 1001PXD                     | [1a4aa87d78](https://linux-hardware.org/?probe=1a4aa87d78) | Oct 29, 2018 |
| Acer          | Aspire ES1-523              | [5e9a049dce](https://linux-hardware.org/?probe=5e9a049dce) | Oct 08, 2018 |
| ASUSTek       | K52JT                       | [7fdee4e7bb](https://linux-hardware.org/?probe=7fdee4e7bb) | Jun 18, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| ALT Linux 9.1      | 20        | 28.99%  |
| ALT Linux 10.0     | 10        | 14.49%  |
| ALT Linux 9.0      | 9         | 13.04%  |
| ALT Linux 9.2      | 8         | 11.59%  |
| ALT Linux 5.0.0    | 4         | 5.8%    |
| ALT Linux P9       | 2         | 2.9%    |
| ALT Linux P8       | 2         | 2.9%    |
| ALT Linux 20191026 | 2         | 2.9%    |
| ALT Linux P10      | 1         | 1.45%   |
| ALT Linux 9        | 1         | 1.45%   |
| ALT Linux 8.990    | 1         | 1.45%   |
| ALT Linux 8.920    | 1         | 1.45%   |
| ALT Linux 8.3      | 1         | 1.45%   |
| ALT Linux 8.2      | 1         | 1.45%   |
| ALT Linux 8.0.0    | 1         | 1.45%   |
| ALT Linux 8        | 1         | 1.45%   |
| ALT Linux 4.0      | 1         | 1.45%   |
| ALT Linux 20201124 | 1         | 1.45%   |
| ALT Linux 20190624 | 1         | 1.45%   |
| ALT Linux          | 1         | 1.45%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| ALT Linux | 63        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Notebooks | Percent |
|-----------------------------|-----------|---------|
| 5.10.88-std-def-alt1        | 5         | 6.17%   |
| 5.4.68-std-def-alt1.1       | 3         | 3.7%    |
| 5.4.28-std-def-alt1         | 3         | 3.7%    |
| 5.4.62-std-def-alt1         | 2         | 2.47%   |
| 5.4.51-std-def-alt1         | 2         | 2.47%   |
| 5.15.25-un-def-alt1         | 2         | 2.47%   |
| 5.10.82-std-def-alt1        | 2         | 2.47%   |
| 5.10.62-un-def-alt1         | 2         | 2.47%   |
| 5.10.37-un-def-alt1         | 2         | 2.47%   |
| 5.10.32-un-def-alt1         | 2         | 2.47%   |
| 5.10.17-un-def-alt1         | 2         | 2.47%   |
| 4.19.79-std-def-alt1        | 2         | 2.47%   |
| 4.19.66-std-def-alt1        | 2         | 2.47%   |
| 4.19.102-std-def-alt1       | 2         | 2.47%   |
| 5.7.19-un-def-alt1          | 1         | 1.23%   |
| 5.7.14-un-def-alt1          | 1         | 1.23%   |
| 5.4.98-std-def-alt1         | 1         | 1.23%   |
| 5.4.87-std-def-alt1         | 1         | 1.23%   |
| 5.4.85-std-def-alt1         | 1         | 1.23%   |
| 5.4.84-std-def-alt1         | 1         | 1.23%   |
| 5.4.81-std-def-alt1         | 1         | 1.23%   |
| 5.4.44-std-def-alt1         | 1         | 1.23%   |
| 5.4.41-std-def-alt1         | 1         | 1.23%   |
| 5.4.40-std-def-alt1         | 1         | 1.23%   |
| 5.4.3-un-def-alt1           | 1         | 1.23%   |
| 5.4.171-std-def-alt1        | 1         | 1.23%   |
| 5.4.144-std-def-alt1        | 1         | 1.23%   |
| 5.4.127-std-def-alt1        | 1         | 1.23%   |
| 5.4.117-std-def-alt1        | 1         | 1.23%   |
| 5.4.115-std-def-alt1        | 1         | 1.23%   |
| 5.4.107-std-def-alt1        | 1         | 1.23%   |
| 5.4.107-std-def-alt0.c9f    | 1         | 1.23%   |
| 5.3.6-un-def-alt1           | 1         | 1.23%   |
| 5.3.5-un-def-alt1           | 1         | 1.23%   |
| 5.2.17-un-def-alt1          | 1         | 1.23%   |
| 5.16.5-un-def-alt1          | 1         | 1.23%   |
| 5.15.23-un-def-alt1         | 1         | 1.23%   |
| 5.15.15-un-def-alt1         | 1         | 1.23%   |
| 5.13.19-un-def-alt1         | 1         | 1.23%   |
| 5.13.15-un-def-alt1         | 1         | 1.23%   |
| 5.10.93-std-def-alt1        | 1         | 1.23%   |
| 5.10.92-std-def-alt1        | 1         | 1.23%   |
| 5.10.69-std-def-alt1        | 1         | 1.23%   |
| 5.10.61-un-def-alt1         | 1         | 1.23%   |
| 5.10.54-std-def-alt2        | 1         | 1.23%   |
| 5.10.52-un-def-alt1         | 1         | 1.23%   |
| 5.10.40-un-def-alt1         | 1         | 1.23%   |
| 5.10.35-std-def-alt1        | 1         | 1.23%   |
| 5.10.29-un-def-alt2         | 1         | 1.23%   |
| 5.10.27-un-def-alt1         | 1         | 1.23%   |
| 5.10.102-std-def-alt1       | 1         | 1.23%   |
| 5.10.10-un-def-alt1         | 1         | 1.23%   |
| 4.9.35-un-def-alt0.M80P.1   | 1         | 1.23%   |
| 4.9.145-std-def-alt0.M80P.1 | 1         | 1.23%   |
| 4.9.133-std-def-alt0.M80P.1 | 1         | 1.23%   |
| 4.9.131-std-def-alt0.M80P.1 | 1         | 1.23%   |
| 4.4.12-std-def-alt0.M80P.1  | 1         | 1.23%   |
| 4.19.95-std-def-alt1        | 1         | 1.23%   |
| 4.19.87-std-def-alt1        | 1         | 1.23%   |
| 4.19.72-std-pae-alt1        | 1         | 1.23%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.10.88  | 5         | 6.17%   |
| 5.4.68   | 3         | 3.7%    |
| 5.4.28   | 3         | 3.7%    |
| 5.4.62   | 2         | 2.47%   |
| 5.4.51   | 2         | 2.47%   |
| 5.4.107  | 2         | 2.47%   |
| 5.15.25  | 2         | 2.47%   |
| 5.10.82  | 2         | 2.47%   |
| 5.10.62  | 2         | 2.47%   |
| 5.10.37  | 2         | 2.47%   |
| 5.10.32  | 2         | 2.47%   |
| 5.10.17  | 2         | 2.47%   |
| 4.19.79  | 2         | 2.47%   |
| 4.19.66  | 2         | 2.47%   |
| 4.19.102 | 2         | 2.47%   |
| 5.7.19   | 1         | 1.23%   |
| 5.7.14   | 1         | 1.23%   |
| 5.4.98   | 1         | 1.23%   |
| 5.4.87   | 1         | 1.23%   |
| 5.4.85   | 1         | 1.23%   |
| 5.4.84   | 1         | 1.23%   |
| 5.4.81   | 1         | 1.23%   |
| 5.4.44   | 1         | 1.23%   |
| 5.4.41   | 1         | 1.23%   |
| 5.4.40   | 1         | 1.23%   |
| 5.4.3    | 1         | 1.23%   |
| 5.4.171  | 1         | 1.23%   |
| 5.4.144  | 1         | 1.23%   |
| 5.4.127  | 1         | 1.23%   |
| 5.4.117  | 1         | 1.23%   |
| 5.4.115  | 1         | 1.23%   |
| 5.3.6    | 1         | 1.23%   |
| 5.3.5    | 1         | 1.23%   |
| 5.2.17   | 1         | 1.23%   |
| 5.16.5   | 1         | 1.23%   |
| 5.15.23  | 1         | 1.23%   |
| 5.15.15  | 1         | 1.23%   |
| 5.13.19  | 1         | 1.23%   |
| 5.13.15  | 1         | 1.23%   |
| 5.10.93  | 1         | 1.23%   |
| 5.10.92  | 1         | 1.23%   |
| 5.10.69  | 1         | 1.23%   |
| 5.10.61  | 1         | 1.23%   |
| 5.10.54  | 1         | 1.23%   |
| 5.10.52  | 1         | 1.23%   |
| 5.10.40  | 1         | 1.23%   |
| 5.10.35  | 1         | 1.23%   |
| 5.10.29  | 1         | 1.23%   |
| 5.10.27  | 1         | 1.23%   |
| 5.10.102 | 1         | 1.23%   |
| 5.10.10  | 1         | 1.23%   |
| 4.9.35   | 1         | 1.23%   |
| 4.9.145  | 1         | 1.23%   |
| 4.9.133  | 1         | 1.23%   |
| 4.9.131  | 1         | 1.23%   |
| 4.4.12   | 1         | 1.23%   |
| 4.19.95  | 1         | 1.23%   |
| 4.19.87  | 1         | 1.23%   |
| 4.19.72  | 1         | 1.23%   |
| 4.19.69  | 1         | 1.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 26        | 35.62%  |
| 5.4     | 20        | 27.4%   |
| 4.19    | 11        | 15.07%  |
| 5.15    | 4         | 5.48%   |
| 4.9     | 3         | 4.11%   |
| 5.7     | 2         | 2.74%   |
| 5.3     | 2         | 2.74%   |
| 5.13    | 2         | 2.74%   |
| 5.2     | 1         | 1.37%   |
| 5.16    | 1         | 1.37%   |
| 4.4     | 1         | 1.37%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 56        | 88.89%  |
| i686   | 7         | 11.11%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KDE5            | 31        | 46.97%  |
| Unknown         | 14        | 21.21%  |
| XFCE            | 11        | 16.67%  |
| LXQt            | 4         | 6.06%   |
| Cinnamon        | 3         | 4.55%   |
| GNOME           | 2         | 3.03%   |
| GNOME Flashback | 1         | 1.52%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 61        | 95.31%  |
| Tty     | 2         | 3.13%   |
| Wayland | 1         | 1.56%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| TDM     | 22        | 32.84%  |
| SDDM    | 22        | 32.84%  |
| LightDM | 18        | 26.87%  |
| Unknown | 3         | 4.48%   |
| XDM     | 1         | 1.49%   |
| GDM     | 1         | 1.49%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| ru_RU   | 37        | 54.41%  |
| Unknown | 26        | 38.24%  |
| en_US   | 4         | 5.88%   |
| POSIX   | 1         | 1.47%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 44        | 67.69%  |
| BIOS | 21        | 32.31%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 50        | 79.37%  |
| Overlay | 9         | 14.29%  |
| Btrfs   | 2         | 3.17%   |
| Unknown | 2         | 3.17%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 44        | 67.69%  |
| MBR     | 17        | 26.15%  |
| Unknown | 4         | 6.15%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 61        | 93.85%  |
| Yes       | 4         | 6.15%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 47        | 73.44%  |
| Yes       | 17        | 26.56%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 14        | 22.22%  |
| Lenovo              | 13        | 20.63%  |
| Hewlett-Packard     | 12        | 19.05%  |
| Acer                | 6         | 9.52%   |
| Samsung Electronics | 3         | 4.76%   |
| MSI                 | 3         | 4.76%   |
| Dell                | 3         | 4.76%   |
| Toshiba             | 1         | 1.59%   |
| Timi                | 1         | 1.59%   |
| ICL                 | 1         | 1.59%   |
| HUAWEI              | 1         | 1.59%   |
| eMachines           | 1         | 1.59%   |
| Durabook            | 1         | 1.59%   |
| DEPO Computers      | 1         | 1.59%   |
| Aquarius            | 1         | 1.59%   |
| 3Logic Group        | 1         | 1.59%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo ThinkPad L13 Gen 2 20VH001WRT       | 2         | 3.17%   |
| Lenovo ThinkBook 15 G2 ITL 20VE            | 2         | 3.17%   |
| HP EliteBook 8470p                         | 2         | 3.17%   |
| ASUS N46VZ                                 | 2         | 3.17%   |
| ASUS ASUS EXPERTBOOK B1500CEAEY_B1500CEAE  | 2         | 3.17%   |
| Toshiba Satellite A100                     | 1         | 1.59%   |
| Timi TM1701                                | 1         | 1.59%   |
| Samsung RV413/RV513/E3413                  | 1         | 1.59%   |
| Samsung R510/P510                          | 1         | 1.59%   |
| Samsung 750XDA                             | 1         | 1.59%   |
| MSI X300/X340/X400 series                  | 1         | 1.59%   |
| MSI MEGA BOOK S430                         | 1         | 1.59%   |
| MSI GE72 7RE                               | 1         | 1.59%   |
| Lenovo ThinkPad X220 4291M85               | 1         | 1.59%   |
| Lenovo ThinkPad 13 2nd Gen 20J1S0EU00      | 1         | 1.59%   |
| Lenovo IdeaPad 5 15IIL05 81YK              | 1         | 1.59%   |
| Lenovo IdeaPad 310-15ISK 80SM              | 1         | 1.59%   |
| Lenovo IdeaPad 3 15IIL05 81WE              | 1         | 1.59%   |
| Lenovo IdeaPad 3 15IGL05 81WQ              | 1         | 1.59%   |
| Lenovo G505s 20255                         | 1         | 1.59%   |
| Lenovo B50-10 80QR                         | 1         | 1.59%   |
| Lenovo 3000 G430 4153/200                  | 1         | 1.59%   |
| ICL NJ50_70CU                              | 1         | 1.59%   |
| HUAWEI NBLK-WAX9X                          | 1         | 1.59%   |
| HP Pavilion Laptop 15-cc5xx                | 1         | 1.59%   |
| HP Pavilion Gaming Laptop 15-ec1xxx        | 1         | 1.59%   |
| HP Pavilion dv6700                         | 1         | 1.59%   |
| HP Laptop 17-by0xxx                        | 1         | 1.59%   |
| HP Laptop 15s-fq2xxx                       | 1         | 1.59%   |
| HP Laptop 15s-fq0xxx                       | 1         | 1.59%   |
| HP Laptop 14s-dq1xxx                       | 1         | 1.59%   |
| HP 255 G2                                  | 1         | 1.59%   |
| HP 250 G3                                  | 1         | 1.59%   |
| eMachines eME728                           | 1         | 1.59%   |
| Durabook Z14                               | 1         | 1.59%   |
| DEPO Computers DPC156                      | 1         | 1.59%   |
| Dell Latitude 3590                         | 1         | 1.59%   |
| Dell Inspiron 3542                         | 1         | 1.59%   |
| Dell G3 3779                               | 1         | 1.59%   |
| ASUS X510UNR                               | 1         | 1.59%   |
| ASUS X200MA                                | 1         | 1.59%   |
| ASUS VivoBook_ASUSLaptop X421IA_M433IA     | 1         | 1.59%   |
| ASUS VivoBook_ASUSLaptop X421DA_M413DA     | 1         | 1.59%   |
| ASUS VivoBook 15_ASUS Laptop X507MA_X507MA | 1         | 1.59%   |
| ASUS K52JT                                 | 1         | 1.59%   |
| ASUS ASUS TUF Gaming A17 FA706IC_FA706IC   | 1         | 1.59%   |
| ASUS ASUS TUF Gaming A15 FA506IV_FX506IV   | 1         | 1.59%   |
| ASUS 1101HA                                | 1         | 1.59%   |
| ASUS 1001PXD                               | 1         | 1.59%   |
| Aquarius NS585                             | 1         | 1.59%   |
| Acer Swift SF314-57                        | 1         | 1.59%   |
| Acer NC-ES1-131-C1NL                       | 1         | 1.59%   |
| Acer Aspire ES1-523                        | 1         | 1.59%   |
| Acer Aspire E1-571G                        | 1         | 1.59%   |
| Acer Aspire A317-32                        | 1         | 1.59%   |
| Acer Aspire 5750G                          | 1         | 1.59%   |
| 3Logic Group Graviton N15i-K2              | 1         | 1.59%   |
| Unknown                                    | 1         | 1.59%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 4         | 6.35%   |
| Lenovo IdeaPad        | 4         | 6.35%   |
| HP Laptop             | 4         | 6.35%   |
| ASUS ASUS             | 4         | 6.35%   |
| Acer Aspire           | 4         | 6.35%   |
| HP Pavilion           | 3         | 4.76%   |
| ASUS VivoBook         | 3         | 4.76%   |
| Lenovo ThinkBook      | 2         | 3.17%   |
| HP EliteBook          | 2         | 3.17%   |
| ASUS N46VZ            | 2         | 3.17%   |
| Toshiba Satellite     | 1         | 1.59%   |
| Timi TM1701           | 1         | 1.59%   |
| Samsung RV413         | 1         | 1.59%   |
| Samsung R510          | 1         | 1.59%   |
| Samsung 750XDA        | 1         | 1.59%   |
| MSI X300              | 1         | 1.59%   |
| MSI MEGA              | 1         | 1.59%   |
| MSI GE72              | 1         | 1.59%   |
| Lenovo G505s          | 1         | 1.59%   |
| Lenovo B50-10         | 1         | 1.59%   |
| Lenovo 3000           | 1         | 1.59%   |
| ICL NJ50              | 1         | 1.59%   |
| HUAWEI NBLK-WAX9X     | 1         | 1.59%   |
| HP 255                | 1         | 1.59%   |
| HP 250                | 1         | 1.59%   |
| eMachines eME728      | 1         | 1.59%   |
| Durabook Z14          | 1         | 1.59%   |
| DEPO Computers DPC156 | 1         | 1.59%   |
| Dell Latitude         | 1         | 1.59%   |
| Dell Inspiron         | 1         | 1.59%   |
| Dell G3               | 1         | 1.59%   |
| ASUS X510UNR          | 1         | 1.59%   |
| ASUS X200MA           | 1         | 1.59%   |
| ASUS K52JT            | 1         | 1.59%   |
| ASUS 1101HA           | 1         | 1.59%   |
| ASUS 1001PXD          | 1         | 1.59%   |
| Aquarius NS585        | 1         | 1.59%   |
| Acer Swift            | 1         | 1.59%   |
| Acer NC-ES1-131-C1NL  | 1         | 1.59%   |
| 3Logic Group Graviton | 1         | 1.59%   |
| Unknown               | 1         | 1.59%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 15        | 23.81%  |
| 2021 | 6         | 9.52%   |
| 2019 | 5         | 7.94%   |
| 2018 | 4         | 6.35%   |
| 2017 | 4         | 6.35%   |
| 2016 | 4         | 6.35%   |
| 2012 | 4         | 6.35%   |
| 2011 | 4         | 6.35%   |
| 2014 | 3         | 4.76%   |
| 2010 | 3         | 4.76%   |
| 2008 | 3         | 4.76%   |
| 2013 | 2         | 3.17%   |
| 2009 | 2         | 3.17%   |
| 2007 | 2         | 3.17%   |
| 2015 | 1         | 1.59%   |
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
| Disabled | 61        | 92.42%  |
| Enabled  | 5         | 7.58%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 63        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 34        | 53.13%  |
| 3.01-4.0   | 14        | 21.88%  |
| 1.01-2.0   | 6         | 9.38%   |
| 16.01-24.0 | 4         | 6.25%   |
| 8.01-16.0  | 4         | 6.25%   |
| 2.01-3.0   | 2         | 3.13%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 29        | 41.43%  |
| 0.51-1.0  | 21        | 30%     |
| 2.01-3.0  | 8         | 11.43%  |
| 4.01-8.0  | 6         | 8.57%   |
| 3.01-4.0  | 3         | 4.29%   |
| 0.01-0.5  | 2         | 2.86%   |
| 8.01-16.0 | 1         | 1.43%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 49        | 74.24%  |
| 2      | 14        | 21.21%  |
| 0      | 2         | 3.03%   |
| 4      | 1         | 1.52%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 49        | 75.38%  |
| Yes       | 16        | 24.62%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 52        | 82.54%  |
| No        | 11        | 17.46%  |

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
| Yes       | 53        | 82.81%  |
| No        | 11        | 17.19%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Notebooks | Percent |
|------------|-----------|---------|
| Russia     | 55        | 87.3%   |
| Greece     | 2         | 3.17%   |
| Uzbekistan | 1         | 1.59%   |
| Ukraine    | 1         | 1.59%   |
| Egypt      | 1         | 1.59%   |
| Czechia    | 1         | 1.59%   |
| Costa Rica | 1         | 1.59%   |
| Belarus    | 1         | 1.59%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| Moscow        | 26        | 37.14%  |
| St Petersburg | 4         | 5.71%   |
| Barnaul       | 4         | 5.71%   |
| Perm          | 2         | 2.86%   |
| Novyy Oskol   | 2         | 2.86%   |
| Novoaltaysk   | 2         | 2.86%   |
| Yekaterinburg | 1         | 1.43%   |
| Vergina       | 1         | 1.43%   |
| Tashkent      | 1         | 1.43%   |
| Surgut        | 1         | 1.43%   |
| Sredneuralsk  | 1         | 1.43%   |
| Sevastopol    | 1         | 1.43%   |
| Saratov       | 1         | 1.43%   |
| San JosГ©   | 1         | 1.43%   |
| Samara        | 1         | 1.43%   |
| Rubtsovsk     | 1         | 1.43%   |
| Prague        | 1         | 1.43%   |
| Omsk          | 1         | 1.43%   |
| Obninsk       | 1         | 1.43%   |
| Novosibirsk   | 1         | 1.43%   |
| Novoburanovo  | 1         | 1.43%   |
| Nizhny Tagil  | 1         | 1.43%   |
| Lesosibirsk   | 1         | 1.43%   |
| Krasnoyarsk   | 1         | 1.43%   |
| Krasnodar     | 1         | 1.43%   |
| Kostroma      | 1         | 1.43%   |
| Korolyov      | 1         | 1.43%   |
| Kirov         | 1         | 1.43%   |
| Khabarovsk    | 1         | 1.43%   |
| Kemerovo      | 1         | 1.43%   |
| KazanвЂ™  | 1         | 1.43%   |
| Irkutsk       | 1         | 1.43%   |
| Hurghada      | 1         | 1.43%   |
| Edessa        | 1         | 1.43%   |
| Cairo         | 1         | 1.43%   |
| Berlezh       | 1         | 1.43%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 17        | 20     | 22.08%  |
| WDC                 | 11        | 15     | 14.29%  |
| Seagate             | 11        | 23     | 14.29%  |
| SK Hynix            | 5         | 5      | 6.49%   |
| Intel               | 5         | 8      | 6.49%   |
| Toshiba             | 4         | 5      | 5.19%   |
| Kingston            | 4         | 4      | 5.19%   |
| Hitachi             | 3         | 3      | 3.9%    |
| Unknown             | 2         | 2      | 2.6%    |
| SanDisk             | 2         | 2      | 2.6%    |
| Fujitsu             | 2         | 2      | 2.6%    |
| Crucial             | 2         | 2      | 2.6%    |
| A-DATA Technology   | 2         | 2      | 2.6%    |
| XPG                 | 1         | 1      | 1.3%    |
| Transcend           | 1         | 1      | 1.3%    |
| PNY                 | 1         | 1      | 1.3%    |
| KingDian            | 1         | 1      | 1.3%    |
| HGST                | 1         | 1      | 1.3%    |
| Gigabyte Technology | 1         | 1      | 1.3%    |
| FOXLINE             | 1         | 1      | 1.3%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Samsung MZALQ256HAJD-000L2 256GB          | 4         | 5%      |
| Seagate ST1000LM024 HN-M101MBB 1TB        | 3         | 3.75%   |
| Seagate ST9250315AS 250GB                 | 2         | 2.5%    |
| Seagate ST1000LM035-1RK172 1TB            | 2         | 2.5%    |
| Samsung SSD 860 EVO 250GB                 | 2         | 2.5%    |
| Intel SSDPEKNW512G8H 512GB                | 2         | 2.5%    |
| Crucial CT120BX500SSD1 120GB              | 2         | 2.5%    |
| XPG NVMe SSD Drive 256GB                  | 1         | 1.25%   |
| WDC WDS500G2B0A-00SM50 500GB SSD          | 1         | 1.25%   |
| WDC WDS120G2G0A-00JH30 120GB SSD          | 1         | 1.25%   |
| WDC WDS100T2B0B-00YS70 1TB SSD            | 1         | 1.25%   |
| WDC WDS100T2B0A-00SM50 1TB SSD            | 1         | 1.25%   |
| WDC WD5000LPVX-80V0TT0 500GB              | 1         | 1.25%   |
| WDC WD5000LPVX-60V0TT0 500GB              | 1         | 1.25%   |
| WDC WD3200BEVT-22A23T0 320GB              | 1         | 1.25%   |
| WDC WD1600BEVS-22RST0 160GB               | 1         | 1.25%   |
| WDC WD1200BEVS-60UST0 120GB               | 1         | 1.25%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB      | 1         | 1.25%   |
| WDC PC SN730 SDBPNTY-512G-1027 512GB      | 1         | 1.25%   |
| WDC PC SN530 SDBPNPZ-512G-1002 512GB      | 1         | 1.25%   |
| Unknown USDU1  32GB                       | 1         | 1.25%   |
| Unknown SDC  8GB                          | 1         | 1.25%   |
| Transcend TS240GSSD220S 240GB             | 1         | 1.25%   |
| Toshiba MQ04ABF100 1TB                    | 1         | 1.25%   |
| Toshiba MQ01ABD100 1TB                    | 1         | 1.25%   |
| Toshiba MQ01ABD050 500GB                  | 1         | 1.25%   |
| Toshiba MK2576GSX 250GB                   | 1         | 1.25%   |
| SK Hynix SKHynix_HFM256GDHTNI-87A0B 256GB | 1         | 1.25%   |
| SK Hynix SC311 SATA 128GB SSD             | 1         | 1.25%   |
| SK Hynix HFS128G39TND-N210A 128GB SSD     | 1         | 1.25%   |
| SK Hynix HFM256GDJTNG-8310A 256GB         | 1         | 1.25%   |
| SK Hynix HBG4e  32GB                      | 1         | 1.25%   |
| Seagate ST9640320AS 640GB                 | 1         | 1.25%   |
| Seagate ST9500325AS 500GB                 | 1         | 1.25%   |
| Seagate ST2000LM007-1R8174 2TB            | 1         | 1.25%   |
| Seagate ST1000LM049-2GH172 1TB            | 1         | 1.25%   |
| SanDisk SD8SN8U128G1002 128GB SSD         | 1         | 1.25%   |
| Sandisk NVMe SSD Drive 512GB              | 1         | 1.25%   |
| Samsung SSD 970 EVO 250GB                 | 1         | 1.25%   |
| Samsung SSD 860 EVO M.2 250GB             | 1         | 1.25%   |
| Samsung NVMe SSD Drive 512GB              | 1         | 1.25%   |
| Samsung NVMe SSD Drive 1TB                | 1         | 1.25%   |
| Samsung MZYTY128HDHP-000L2 128GB SSD      | 1         | 1.25%   |
| Samsung MZVLQ512HBLU-00BTW 512GB          | 1         | 1.25%   |
| Samsung MZVLQ256HBJD-00B 256GB            | 1         | 1.25%   |
| Samsung MZVLQ1T0HALB-00000 1TB            | 1         | 1.25%   |
| Samsung MZVLB512HAJQ-00000 512GB          | 1         | 1.25%   |
| Samsung MZVLB256HBHQ-000L7 256GB          | 1         | 1.25%   |
| Samsung MZVLB256HBHQ-000H1 256GB          | 1         | 1.25%   |
| Samsung MZNLN128HAHQ-000H1 128GB SSD      | 1         | 1.25%   |
| PNY CS900 240GB SSD                       | 1         | 1.25%   |
| Kingston SA400S37480G 480GB SSD           | 1         | 1.25%   |
| Kingston RBUSNS8154P3256GJ1 256GB         | 1         | 1.25%   |
| Kingston RBUSC180S37256GJ 256GB SSD       | 1         | 1.25%   |
| Kingston OM8PCP3512F-AB 512GB             | 1         | 1.25%   |
| KingDian S180 60GB SSD                    | 1         | 1.25%   |
| Intel SSDSC2BX200G4 200GB                 | 1         | 1.25%   |
| Intel SSDPEKKF256G7L 256GB                | 1         | 1.25%   |
| Intel HBRPEKNX0101AHO 16GB                | 1         | 1.25%   |
| Intel HBRPEKNX0101AH 256GB                | 1         | 1.25%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 11        | 23     | 42.31%  |
| WDC     | 5         | 6      | 19.23%  |
| Toshiba | 4         | 5      | 15.38%  |
| Hitachi | 3         | 3      | 11.54%  |
| Fujitsu | 2         | 2      | 7.69%   |
| HGST    | 1         | 1      | 3.85%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 5      | 25%     |
| WDC                 | 3         | 6      | 15%     |
| SK Hynix            | 2         | 2      | 10%     |
| Kingston            | 2         | 2      | 10%     |
| Crucial             | 2         | 2      | 10%     |
| Transcend           | 1         | 1      | 5%      |
| SanDisk             | 1         | 1      | 5%      |
| PNY                 | 1         | 1      | 5%      |
| KingDian            | 1         | 1      | 5%      |
| Intel               | 1         | 1      | 5%      |
| A-DATA Technology   | 1         | 1      | 5%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 26        | 40     | 35.62%  |
| NVMe | 25        | 34     | 34.25%  |
| SSD  | 19        | 23     | 26.03%  |
| MMC  | 3         | 3      | 4.11%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 37        | 62     | 56.06%  |
| NVMe | 25        | 34     | 37.88%  |
| MMC  | 3         | 3      | 4.55%   |
| SAS  | 1         | 1      | 1.52%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 31        | 38     | 73.81%  |
| 0.51-1.0   | 10        | 24     | 23.81%  |
| 1.01-2.0   | 1         | 1      | 2.38%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 33        | 50%     |
| 251-500    | 13        | 19.7%   |
| 21-50      | 6         | 9.09%   |
| 1-20       | 5         | 7.58%   |
| 501-1000   | 5         | 7.58%   |
| 51-100     | 3         | 4.55%   |
| 1001-2000  | 1         | 1.52%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 37        | 52.11%  |
| 21-50    | 11        | 15.49%  |
| 101-250  | 10        | 14.08%  |
| 51-100   | 8         | 11.27%  |
| 251-500  | 4         | 5.63%   |
| 501-1000 | 1         | 1.41%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST9250315AS 250GB             | 2         | 2      | 15.38%  |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 2         | 14     | 15.38%  |
| WDC WD5000LPVX-60V0TT0 500GB          | 1         | 1      | 7.69%   |
| WDC WD1200BEVS-60UST0 120GB           | 1         | 1      | 7.69%   |
| Toshiba MQ01ABD050 500GB              | 1         | 1      | 7.69%   |
| SK Hynix HFS128G39TND-N210A 128GB SSD | 1         | 1      | 7.69%   |
| Seagate ST9640320AS 640GB             | 1         | 1      | 7.69%   |
| Seagate ST9500325AS 500GB             | 1         | 1      | 7.69%   |
| Hitachi HTS542525K9A300 250GB         | 1         | 1      | 7.69%   |
| Hitachi HTS541610J9SA00 100GB         | 1         | 1      | 7.69%   |
| HGST HTS545050A7E680 500GB            | 1         | 1      | 7.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 6         | 18     | 46.15%  |
| WDC      | 2         | 2      | 15.38%  |
| Hitachi  | 2         | 2      | 15.38%  |
| Toshiba  | 1         | 1      | 7.69%   |
| SK Hynix | 1         | 1      | 7.69%   |
| HGST     | 1         | 1      | 7.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 18     | 50%     |
| WDC     | 2         | 2      | 16.67%  |
| Hitachi | 2         | 2      | 16.67%  |
| Toshiba | 1         | 1      | 8.33%   |
| HGST    | 1         | 1      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 12        | 24     | 92.31%  |
| SSD  | 1         | 1      | 7.69%   |

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
| Works    | 49        | 66     | 71.01%  |
| Malfunc  | 13        | 25     | 18.84%  |
| Detected | 7         | 9      | 10.14%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 44        | 56.41%  |
| Samsung Electronics         | 12        | 15.38%  |
| AMD                         | 8         | 10.26%  |
| Sandisk                     | 4         | 5.13%   |
| SK Hynix                    | 2         | 2.56%   |
| Phison Electronics          | 2         | 2.56%   |
| Nvidia                      | 2         | 2.56%   |
| Kingston Technology Company | 2         | 2.56%   |
| VIA Technologies            | 1         | 1.28%   |
| ADATA Technology            | 1         | 1.28%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller 980                                              | 7         | 7.95%   |
| AMD FCH SATA Controller [AHCI mode]                                          | 7         | 7.95%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 5         | 5.68%   |
| Intel Volume Management Device NVMe RAID Controller                          | 5         | 5.68%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 5         | 5.68%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 5         | 5.68%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                              | 4         | 4.55%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 4         | 4.55%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                       | 3         | 3.41%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 3         | 3.41%   |
| Sandisk WD Blue SN550 NVMe SSD                                               | 2         | 2.27%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                   | 2         | 2.27%   |
| Phison PS5013 E13 NVMe Controller                                            | 2         | 2.27%   |
| Intel SSD 660P Series                                                        | 2         | 2.27%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                | 2         | 2.27%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                            | 2         | 2.27%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                       | 2         | 2.27%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 2         | 2.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 2         | 2.27%   |
| VIA VT8237/8251 Serial ATA Controller                                        | 1         | 1.14%   |
| SK Hynix BC511                                                               | 1         | 1.14%   |
| SK Hynix BC501 NVMe Solid State Drive                                        | 1         | 1.14%   |
| Nvidia MCP67 IDE Controller                                                  | 1         | 1.14%   |
| Nvidia MCP67 AHCI Controller                                                 | 1         | 1.14%   |
| Nvidia MCP51 Serial ATA Controller                                           | 1         | 1.14%   |
| Nvidia MCP51 IDE                                                             | 1         | 1.14%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                        | 1         | 1.14%   |
| Kingston Company Company Non-Volatile memory controller                      | 1         | 1.14%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                   | 1         | 1.14%   |
| Intel SSD 600P Series                                                        | 1         | 1.14%   |
| Intel Non-Volatile memory controller                                         | 1         | 1.14%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                           | 1         | 1.14%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                        | 1         | 1.14%   |
| Intel Comet Lake SATA AHCI Controller                                        | 1         | 1.14%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                   | 1         | 1.14%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                            | 1         | 1.14%   |
| Intel Atom Processor E3800 Series SATA IDE Controller                        | 1         | 1.14%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                | 1         | 1.14%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller               | 1         | 1.14%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                            | 1         | 1.14%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                  | 1         | 1.14%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 45        | 53.57%  |
| NVMe | 25        | 29.76%  |
| RAID | 8         | 9.52%   |
| IDE  | 6         | 7.14%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 50        | 79.37%  |
| AMD          | 12        | 19.05%  |
| CentaurHauls | 1         | 1.59%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 5         | 7.94%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 4.76%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 4.76%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 2         | 3.17%   |
| Intel Core i5-8259U CPU @ 2.30GHz             | 2         | 3.17%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 2         | 3.17%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 2         | 3.17%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 3.17%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 2         | 3.17%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 3.17%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 1         | 1.59%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 1.59%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz        | 1         | 1.59%   |
| Intel Pentium Gold 7505 @ 2.00GHz             | 1         | 1.59%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 1.59%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 1.59%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 1.59%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 1.59%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 1         | 1.59%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 1.59%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 1.59%   |
| Intel Core i5-3360M CPU @ 2.80GHz             | 1         | 1.59%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 1.59%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 1         | 1.59%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 1.59%   |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 1         | 1.59%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 1         | 1.59%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 1         | 1.59%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 1.59%   |
| Intel Core i3-3120M CPU @ 2.50GHz             | 1         | 1.59%   |
| Intel Core Duo CPU T2250 @ 1.73GHz            | 1         | 1.59%   |
| Intel Core 2 Solo CPU U3500 @ 1.40GHz         | 1         | 1.59%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 1         | 1.59%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 1         | 1.59%   |
| Intel Celeron Dual-Core CPU T3000 @ 1.80GHz   | 1         | 1.59%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 1         | 1.59%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 1         | 1.59%   |
| Intel Celeron CPU N2830 @ 2.16GHz             | 1         | 1.59%   |
| Intel Atom CPU Z520 @ 1.33GHz                 | 1         | 1.59%   |
| Intel Atom CPU N455 @ 1.66GHz                 | 1         | 1.59%   |
| CentaurHauls VIA C7-M Processor 1600MHz       | 1         | 1.59%   |
| AMD Turion 64 X2 Mobile Technology TL-58      | 1         | 1.59%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 1         | 1.59%   |
| AMD E1-2100 APU with Radeon HD Graphics       | 1         | 1.59%   |
| AMD E-450 APU with Radeon HD Graphics         | 1         | 1.59%   |
| AMD Athlon 64 X2 Dual-Core Processor TK-57    | 1         | 1.59%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 1         | 1.59%   |
| AMD A8-5550M APU with Radeon HD Graphics      | 1         | 1.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 14        | 22.22%  |
| Intel Core i3           | 8         | 12.7%   |
| Other                   | 7         | 11.11%  |
| Intel Core i7           | 6         | 9.52%   |
| Intel Celeron           | 4         | 6.35%   |
| AMD Ryzen 7             | 3         | 4.76%   |
| AMD Ryzen 5             | 3         | 4.76%   |
| Intel Pentium Silver    | 2         | 3.17%   |
| Intel Pentium Gold      | 2         | 3.17%   |
| Intel Atom              | 2         | 3.17%   |
| AMD A8                  | 2         | 3.17%   |
| Intel Pentium Dual-Core | 1         | 1.59%   |
| Intel Core Duo          | 1         | 1.59%   |
| Intel Core 2 Solo       | 1         | 1.59%   |
| Intel Core 2 Duo        | 1         | 1.59%   |
| Intel Celeron Dual-Core | 1         | 1.59%   |
| CentaurHauls VIA C7     | 1         | 1.59%   |
| AMD Turion 64 X2 Mobile | 1         | 1.59%   |
| AMD E1                  | 1         | 1.59%   |
| AMD E                   | 1         | 1.59%   |
| AMD Athlon 64 X2        | 1         | 1.59%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 31        | 49.21%  |
| 4      | 23        | 36.51%  |
| 1      | 4         | 6.35%   |
| 8      | 3         | 4.76%   |
| 6      | 2         | 3.17%   |

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
| 2      | 45        | 71.43%  |
| 1      | 18        | 28.57%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 59        | 93.65%  |
| 32-bit         | 3         | 4.76%   |
| Unknown        | 1         | 1.59%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 11        | 17.19%  |
| 0x806c1    | 7         | 10.94%  |
| 0x306a9    | 5         | 7.81%   |
| 0x706e5    | 4         | 6.25%   |
| 0x806ea    | 3         | 4.69%   |
| 0x806e9    | 3         | 4.69%   |
| 0x1067a    | 3         | 4.69%   |
| 0x08600106 | 3         | 4.69%   |
| 0x906ea    | 2         | 3.13%   |
| 0x706a8    | 2         | 3.13%   |
| 0x40651    | 2         | 3.13%   |
| 0x30678    | 2         | 3.13%   |
| 0x08108109 | 2         | 3.13%   |
| 0xa0660    | 1         | 1.56%   |
| 0x806ec    | 1         | 1.56%   |
| 0x706a1    | 1         | 1.56%   |
| 0x6ec      | 1         | 1.56%   |
| 0x406e3    | 1         | 1.56%   |
| 0x406c3    | 1         | 1.56%   |
| 0x206a7    | 1         | 1.56%   |
| 0x20655    | 1         | 1.56%   |
| 0x106ca    | 1         | 1.56%   |
| 0x106c2    | 1         | 1.56%   |
| 0x10676    | 1         | 1.56%   |
| 0x08600104 | 1         | 1.56%   |
| 0x07030105 | 1         | 1.56%   |
| 0x0700010f | 1         | 1.56%   |
| 0x06001119 | 1         | 1.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 13        | 20.63%  |
| TigerLake     | 8         | 12.7%   |
| IvyBridge     | 5         | 7.94%   |
| Zen 2         | 4         | 6.35%   |
| Penryn        | 4         | 6.35%   |
| IceLake       | 4         | 6.35%   |
| Silvermont    | 3         | 4.76%   |
| Goldmont plus | 3         | 4.76%   |
| Zen+          | 2         | 3.17%   |
| SandyBridge   | 2         | 3.17%   |
| K8 Hammer     | 2         | 3.17%   |
| Haswell       | 2         | 3.17%   |
| Bonnell       | 2         | 3.17%   |
| Westmere      | 1         | 1.59%   |
| Skylake       | 1         | 1.59%   |
| Puma          | 1         | 1.59%   |
| Piledriver    | 1         | 1.59%   |
| P6            | 1         | 1.59%   |
| Jaguar        | 1         | 1.59%   |
| CometLake     | 1         | 1.59%   |
| Bobcat        | 1         | 1.59%   |
| Unknown       | 1         | 1.59%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 47        | 61.04%  |
| Nvidia           | 18        | 23.38%  |
| AMD              | 11        | 14.29%  |
| VIA Technologies | 1         | 1.3%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 5         | 6.33%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 6.33%   |
| Intel UHD Graphics 620                                                                   | 4         | 5.06%   |
| AMD Renoir                                                                               | 4         | 5.06%   |
| Intel Tiger Lake UHD Graphics                                                            | 3         | 3.8%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 3.8%    |
| Intel HD Graphics 620                                                                    | 3         | 3.8%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 2.53%   |
| Nvidia GK107M [GeForce GT 650M]                                                          | 2         | 2.53%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 2.53%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 2.53%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2         | 2.53%   |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                                         | 2         | 2.53%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 2.53%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 2.53%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 2.53%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 1         | 1.27%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 1.27%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 1.27%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 1.27%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 1.27%   |
| Nvidia GP108BM [GeForce MX250]                                                           | 1         | 1.27%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 1.27%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 1.27%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 1.27%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 1         | 1.27%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 1         | 1.27%   |
| Nvidia G98M [GeForce 9300M GS]                                                           | 1         | 1.27%   |
| Nvidia G98M [GeForce 9200M GS]                                                           | 1         | 1.27%   |
| Nvidia C67 [GeForce 7150M / nForce 630M]                                                 | 1         | 1.27%   |
| Nvidia C51 [GeForce Go 6100]                                                             | 1         | 1.27%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 1.27%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                                      | 1         | 1.27%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 1.27%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 1.27%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 1.27%   |
| Intel Iris Plus Graphics G7                                                              | 1         | 1.27%   |
| Intel HD Graphics 630                                                                    | 1         | 1.27%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 1.27%   |
| Intel Comet Lake UHD Graphics                                                            | 1         | 1.27%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                                | 1         | 1.27%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.27%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.27%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1         | 1.27%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 1         | 1.27%   |
| AMD Robson CE [Radeon HD 6370M/7370M]                                                    | 1         | 1.27%   |
| AMD Richland [Radeon HD 8550G]                                                           | 1         | 1.27%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 1         | 1.27%   |
| AMD Kabini [Radeon HD 8210]                                                              | 1         | 1.27%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                             | 1         | 1.27%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 36        | 57.14%  |
| Intel + Nvidia | 11        | 17.46%  |
| 1 x AMD        | 7         | 11.11%  |
| 1 x Nvidia     | 4         | 6.35%   |
| AMD + Nvidia   | 3         | 4.76%   |
| 2 x AMD        | 1         | 1.59%   |
| 1 x VIA        | 1         | 1.59%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 54        | 83.08%  |
| Proprietary | 8         | 12.31%  |
| Unknown     | 3         | 4.62%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 48        | 73.85%  |
| 0.01-0.5   | 8         | 12.31%  |
| 0.51-1.0   | 5         | 7.69%   |
| 1.01-2.0   | 4         | 6.15%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 14        | 20.29%  |
| Chimei Innolux          | 12        | 17.39%  |
| LG Display              | 11        | 15.94%  |
| BOE                     | 10        | 14.49%  |
| Samsung Electronics     | 8         | 11.59%  |
| Chi Mei Optoelectronics | 4         | 5.8%    |
| PANDA                   | 2         | 2.9%    |
| BenQ                    | 2         | 2.9%    |
| AOC                     | 2         | 2.9%    |
| STA                     | 1         | 1.45%   |
| Sharp                   | 1         | 1.45%   |
| KDC                     | 1         | 1.45%   |
| Acer                    | 1         | 1.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 3         | 4.29%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch      | 2         | 2.86%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch              | 2         | 2.86%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 2         | 2.86%   |
| BOE LCD Monitor BOE09CC 1920x1080 344x194mm 15.5-inch                    | 2         | 2.86%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                    | 2         | 2.86%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 2         | 2.86%   |
| AU Optronics LCD Monitor AUO133C 1366x768 309x173mm 13.9-inch            | 2         | 2.86%   |
| STA LCD Monitor STAAFC9 1920x1080 344x194mm 15.5-inch                    | 1         | 1.43%   |
| Sharp LCD Monitor SHP13CA 1280x800 331x207mm 15.4-inch                   | 1         | 1.43%   |
| Samsung Electronics S24D590 SAM0B46 1920x1080 521x293mm 23.5-inch        | 1         | 1.43%   |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch     | 1         | 1.43%   |
| Samsung Electronics LCD Monitor SEC4754 1280x800 261x163mm 12.1-inch     | 1         | 1.43%   |
| Samsung Electronics LCD Monitor SEC364A 1366x768 344x194mm 15.5-inch     | 1         | 1.43%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch     | 1         | 1.43%   |
| Samsung Electronics F27G3xTF SAM710E 1920x1080 600x330mm 27.0-inch       | 1         | 1.43%   |
| Samsung Electronics F27G3xTF SAM710D 1920x1080 600x330mm 27.0-inch       | 1         | 1.43%   |
| PANDA LCD Monitor NCP0064 1920x1080 344x194mm 15.5-inch                  | 1         | 1.43%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 1         | 1.43%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 1         | 1.43%   |
| LG Display LCD Monitor LGD05B5 1920x1080 382x215mm 17.3-inch             | 1         | 1.43%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch             | 1         | 1.43%   |
| LG Display LCD Monitor LGD056D 1920x1080 382x215mm 17.3-inch             | 1         | 1.43%   |
| LG Display LCD Monitor LGD053B 1920x1080 294x165mm 13.3-inch             | 1         | 1.43%   |
| LG Display LCD Monitor LGD046B 1366x768 344x194mm 15.5-inch              | 1         | 1.43%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 1         | 1.43%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 1         | 1.43%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 1         | 1.43%   |
| KDC LCD Monitor KDC0002 1920x1080 309x174mm 14.0-inch                    | 1         | 1.43%   |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 381x214mm 17.2-inch         | 1         | 1.43%   |
| Chimei Innolux LCD Monitor CMN1745 1600x900 382x214mm 17.2-inch          | 1         | 1.43%   |
| Chimei Innolux LCD Monitor CMN15C5 1366x768 344x193mm 15.5-inch          | 1         | 1.43%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 1         | 1.43%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch         | 1         | 1.43%   |
| Chimei Innolux LCD Monitor CMN1515 1920x1080 344x193mm 15.5-inch         | 1         | 1.43%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 1         | 1.43%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 1         | 1.43%   |
| Chimei Innolux LCD Monitor CMN1375 1920x1080 293x165mm 13.2-inch         | 1         | 1.43%   |
| Chimei Innolux LCD Monitor CMN1119 1366x768 256x144mm 11.6-inch          | 1         | 1.43%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 1         | 1.43%   |
| Chi Mei Optoelectronics LCD Monitor CMO1424 1280x800 303x190mm 14.1-inch | 1         | 1.43%   |
| Chi Mei Optoelectronics LCD Monitor CMO1316 1366x768 296x166mm 13.4-inch | 1         | 1.43%   |
| Chi Mei Optoelectronics LCD Monitor CMO1100 1366x768 256x144mm 11.6-inch | 1         | 1.43%   |
| BOE LCD Monitor BOE0900 1920x1080 344x194mm 15.5-inch                    | 1         | 1.43%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                    | 1         | 1.43%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 1         | 1.43%   |
| BOE LCD Monitor BOE0679 1920x1080 344x194mm 15.5-inch                    | 1         | 1.43%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 1         | 1.43%   |
| BOE LCD Monitor BOE0615 1366x768 309x173mm 13.9-inch                     | 1         | 1.43%   |
| BenQ LCD BNQ801B 2560x1440 527x296mm 23.8-inch                           | 1         | 1.43%   |
| BenQ GC2870 BNQ78DD 1920x1080 621x341mm 27.9-inch                        | 1         | 1.43%   |
| AU Optronics LCD Monitor AUO8294 1920x1080 382x215mm 17.3-inch           | 1         | 1.43%   |
| AU Optronics LCD Monitor AUO662D 1920x1080 293x165mm 13.2-inch           | 1         | 1.43%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch           | 1         | 1.43%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 1         | 1.43%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 1         | 1.43%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 1         | 1.43%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 1         | 1.43%   |
| AOC 2490W1 AOC2490 1920x1080 527x296mm 23.8-inch                         | 1         | 1.43%   |
| AOC 2375 AOC2375 1920x1080 509x286mm 23.0-inch                           | 1         | 1.43%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 36        | 55.38%  |
| 1366x768 (WXGA)  | 17        | 26.15%  |
| 1600x900 (HD+)   | 4         | 6.15%   |
| 1280x800 (WXGA)  | 4         | 6.15%   |
| 1440x900 (WXGA+) | 2         | 3.08%   |
| 2560x1440 (QHD)  | 1         | 1.54%   |
| 1280x1024 (SXGA) | 1         | 1.54%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 34        | 49.28%  |
| 13     | 10        | 14.49%  |
| 14     | 7         | 10.14%  |
| 17     | 5         | 7.25%   |
| 23     | 3         | 4.35%   |
| 19     | 3         | 4.35%   |
| 11     | 3         | 4.35%   |
| 27     | 2         | 2.9%    |
| 24     | 1         | 1.45%   |
| 12     | 1         | 1.45%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 47        | 68.12%  |
| 201-300     | 8         | 11.59%  |
| 351-400     | 6         | 8.7%    |
| 501-600     | 5         | 7.25%   |
| 401-500     | 2         | 2.9%    |
| 601-700     | 1         | 1.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 57        | 89.06%  |
| 16/10 | 4         | 6.25%   |
| 3/2   | 2         | 3.13%   |
| 6/5   | 1         | 1.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 34        | 49.28%  |
| 81-90          | 13        | 18.84%  |
| 121-130        | 5         | 7.25%   |
| 71-80          | 4         | 5.8%    |
| 201-250        | 4         | 5.8%    |
| 51-60          | 3         | 4.35%   |
| 151-200        | 3         | 4.35%   |
| 301-350        | 2         | 2.9%    |
| 61-70          | 1         | 1.45%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 38        | 55.88%  |
| 101-120 | 15        | 22.06%  |
| 51-100  | 12        | 17.65%  |
| 161-240 | 3         | 4.41%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 57        | 87.69%  |
| 2     | 6         | 9.23%   |
| 3     | 1         | 1.54%   |
| 0     | 1         | 1.54%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 30        | 30.3%   |
| Intel                           | 29        | 29.29%  |
| Qualcomm Atheros                | 18        | 18.18%  |
| Broadcom                        | 7         | 7.07%   |
| D-Link                          | 5         | 5.05%   |
| Nvidia                          | 2         | 2.02%   |
| Ralink                          | 1         | 1.01%   |
| Qualcomm Atheros Communications | 1         | 1.01%   |
| Micro Star International        | 1         | 1.01%   |
| MEDIATEK                        | 1         | 1.01%   |
| Marvell Technology Group        | 1         | 1.01%   |
| JMicron Technology              | 1         | 1.01%   |
| Broadcom Limited                | 1         | 1.01%   |
| ASUSTek Computer                | 1         | 1.01%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 18        | 14.4%   |
| Intel Wi-Fi 6 AX201                                                     | 7         | 5.6%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 5         | 4%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 4%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 3.2%    |
| Intel Ethernet Connection (13) I219-V                                   | 4         | 3.2%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 2.4%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 3         | 2.4%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 2.4%    |
| Intel Wireless 8265 / 8275                                              | 3         | 2.4%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 2.4%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 3         | 2.4%    |
| D-Link DUB-1312 Gigabit Ethernet Adapter                                | 3         | 2.4%    |
| Broadcom BCM43228 802.11a/b/g/n                                         | 3         | 2.4%    |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 1.6%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 1.6%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 2         | 1.6%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.6%    |
| Intel WiMAX/WiFi Link 5150                                              | 2         | 1.6%    |
| Intel WiMAX Connection 2400m                                            | 2         | 1.6%    |
| Intel Ethernet Connection (6) I219-V                                    | 2         | 1.6%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 1.6%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2         | 1.6%    |
| D-Link DUB-E100 Fast Ethernet Adapter(rev.C1) [ASIX AX88772]            | 2         | 1.6%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 2         | 1.6%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 1         | 0.8%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.8%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 1         | 0.8%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.8%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 1         | 0.8%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.8%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller               | 1         | 0.8%    |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 0.8%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 0.8%    |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 1         | 0.8%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 1         | 0.8%    |
| Nvidia MCP67 Ethernet                                                   | 1         | 0.8%    |
| Nvidia MCP51 Ethernet Controller                                        | 1         | 0.8%    |
| Micro Star International RT2573                                         | 1         | 0.8%    |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 0.8%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                 | 1         | 0.8%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 1         | 0.8%    |
| Intel Wireless-AC 9260                                                  | 1         | 0.8%    |
| Intel Wireless 7265                                                     | 1         | 0.8%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 0.8%    |
| Intel PRO/100 VE Network Connection                                     | 1         | 0.8%    |
| Intel I210 Gigabit Network Connection                                   | 1         | 0.8%    |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 0.8%    |
| Intel Ethernet Connection I219-LM                                       | 1         | 0.8%    |
| Intel Ethernet Connection (4) I219-V                                    | 1         | 0.8%    |
| Intel Ethernet Connection (10) I219-V                                   | 1         | 0.8%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1         | 0.8%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1         | 0.8%    |
| Intel Centrino Wireless-N 105                                           | 1         | 0.8%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 0.8%    |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                     | 1         | 0.8%    |
| Broadcom Limited NetXtreme BCM5788 Gigabit Ethernet                     | 1         | 0.8%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 1         | 0.8%    |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 1         | 0.8%    |
| Broadcom BCM4311 802.11a/b/g                                            | 1         | 0.8%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 27        | 40.3%   |
| Qualcomm Atheros                | 17        | 25.37%  |
| Realtek Semiconductor           | 12        | 17.91%  |
| Broadcom                        | 6         | 8.96%   |
| Ralink                          | 1         | 1.49%   |
| Qualcomm Atheros Communications | 1         | 1.49%   |
| Micro Star International        | 1         | 1.49%   |
| MEDIATEK                        | 1         | 1.49%   |
| ASUSTek Computer                | 1         | 1.49%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                                     | 7         | 10.29%  |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 7.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 5.88%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 4.41%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 3         | 4.41%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 4.41%   |
| Intel Wireless 8265 / 8275                                              | 3         | 4.41%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 4.41%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 3         | 4.41%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 2.94%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 2.94%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 2         | 2.94%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 2.94%   |
| Intel WiMAX/WiFi Link 5150                                              | 2         | 2.94%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 2.94%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2         | 2.94%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 1         | 1.47%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 1.47%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 1.47%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 1.47%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 1.47%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 1.47%   |
| Micro Star International RT2573                                         | 1         | 1.47%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 1.47%   |
| Intel Wireless-AC 9260                                                  | 1         | 1.47%   |
| Intel Wireless 7265                                                     | 1         | 1.47%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 1.47%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 1.47%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1         | 1.47%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1         | 1.47%   |
| Intel Centrino Wireless-N 105                                           | 1         | 1.47%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 1.47%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 1         | 1.47%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 1         | 1.47%   |
| Broadcom BCM4311 802.11a/b/g                                            | 1         | 1.47%   |
| ASUS USB-N13 802.11n Network Adapter (rev. B1) [Realtek RTL8192CU]      | 1         | 1.47%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 23        | 41.82%  |
| Intel                    | 15        | 27.27%  |
| D-Link                   | 5         | 9.09%   |
| Qualcomm Atheros         | 4         | 7.27%   |
| Broadcom                 | 3         | 5.45%   |
| Nvidia                   | 2         | 3.64%   |
| Marvell Technology Group | 1         | 1.82%   |
| JMicron Technology       | 1         | 1.82%   |
| Broadcom Limited         | 1         | 1.82%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 18        | 31.58%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 8.77%   |
| Intel Ethernet Connection (13) I219-V                             | 4         | 7.02%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 5.26%   |
| D-Link DUB-1312 Gigabit Ethernet Adapter                          | 3         | 5.26%   |
| Intel WiMAX Connection 2400m                                      | 2         | 3.51%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 3.51%   |
| D-Link DUB-E100 Fast Ethernet Adapter(rev.C1) [ASIX AX88772]      | 2         | 3.51%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 3.51%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.75%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.75%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.75%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.75%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 1.75%   |
| Nvidia MCP67 Ethernet                                             | 1         | 1.75%   |
| Nvidia MCP51 Ethernet Controller                                  | 1         | 1.75%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 1.75%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 1.75%   |
| Intel PRO/100 VE Network Connection                               | 1         | 1.75%   |
| Intel I210 Gigabit Network Connection                             | 1         | 1.75%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.75%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.75%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.75%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 1.75%   |
| Broadcom Limited NetXtreme BCM5788 Gigabit Ethernet               | 1         | 1.75%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 63        | 54.78%  |
| Ethernet | 52        | 45.22%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 49        | 67.12%  |
| Ethernet | 24        | 32.88%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 46        | 73.02%  |
| 1     | 16        | 25.4%   |
| 3     | 1         | 1.59%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 57        | 90.48%  |
| Yes  | 6         | 9.52%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 22        | 40.74%  |
| Realtek Semiconductor           | 7         | 12.96%  |
| IMC Networks                    | 6         | 11.11%  |
| Lite-On Technology              | 4         | 7.41%   |
| Qualcomm Atheros Communications | 3         | 5.56%   |
| Broadcom                        | 3         | 5.56%   |
| Hewlett-Packard                 | 2         | 3.7%    |
| ASUSTek Computer                | 2         | 3.7%    |
| Toshiba                         | 1         | 1.85%   |
| Realtek                         | 1         | 1.85%   |
| Ralink                          | 1         | 1.85%   |
| Chicony Electronics             | 1         | 1.85%   |
| Cambridge Silicon Radio         | 1         | 1.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 9         | 16.67%  |
| Intel Bluetooth wireless interface                  | 5         | 9.26%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 5         | 9.26%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 7.41%   |
| Realtek Bluetooth Radio                             | 3         | 5.56%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 3.7%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 3.7%    |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 3.7%    |
| IMC Networks Bluetooth Device                       | 2         | 3.7%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 2         | 3.7%    |
| Toshiba Integrated Bluetooth HCI                    | 1         | 1.85%   |
| Realtek Bluetooth Radio                             | 1         | 1.85%   |
| Ralink RT3290 Bluetooth                             | 1         | 1.85%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 1.85%   |
| Lite-On Qualcomm Atheros Bluetooth                  | 1         | 1.85%   |
| Lite-On Bluetooth Radio                             | 1         | 1.85%   |
| Intel Bluetooth Device                              | 1         | 1.85%   |
| IMC Networks Wireless_Device                        | 1         | 1.85%   |
| IMC Networks Bluetooth Radio                        | 1         | 1.85%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 1.85%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 1.85%   |
| Chicony Bluetooth Radio                             | 1         | 1.85%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 1.85%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 1.85%   |
| Broadcom BCM2070 Bluetooth Device                   | 1         | 1.85%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 1.85%   |
| ASUS BT-270 Bluetooth Adapter                       | 1         | 1.85%   |
| ASUS Broadcom Bluetooth 2.1                         | 1         | 1.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 50        | 68.49%  |
| AMD                   | 11        | 15.07%  |
| Nvidia                | 9         | 12.33%  |
| VIA Technologies      | 1         | 1.37%   |
| Realtek Semiconductor | 1         | 1.37%   |
| C-Media Electronics   | 1         | 1.37%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 8         | 9.52%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 8         | 9.52%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 6         | 7.14%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 5         | 5.95%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 4.76%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 4.76%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 3.57%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 3.57%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 3.57%   |
| AMD FCH Azalia Controller                                                                         | 3         | 3.57%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 2.38%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 2.38%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 2.38%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 2.38%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 2.38%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 2.38%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 2.38%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 2.38%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 2.38%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1         | 1.19%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 1.19%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 1.19%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 1.19%   |
| Nvidia MCP67 High Definition Audio                                                                | 1         | 1.19%   |
| Nvidia MCP51 High Definition Audio                                                                | 1         | 1.19%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 1.19%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 1.19%   |
| Nvidia Audio device                                                                               | 1         | 1.19%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                                   | 1         | 1.19%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 1.19%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 1.19%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.19%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 1.19%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 1         | 1.19%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 1.19%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 1.19%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1         | 1.19%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 1         | 1.19%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 19        | 31.67%  |
| SK Hynix            | 13        | 21.67%  |
| Unknown             | 9         | 15%     |
| Kingston            | 5         | 8.33%   |
| Micron Technology   | 4         | 6.67%   |
| A-DATA Technology   | 3         | 5%      |
| Ramaxel Technology  | 2         | 3.33%   |
| Foxline             | 2         | 3.33%   |
| Crucial             | 2         | 3.33%   |
| Elpida              | 1         | 1.67%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s           | 4         | 6.35%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                   | 3         | 4.76%   |
| Unknown RAM Module 2048MB SODIMM DDR2                           | 3         | 4.76%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s          | 3         | 4.76%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s          | 3         | 4.76%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s           | 2         | 3.17%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s     | 2         | 3.17%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s     | 2         | 3.17%   |
| Foxline RAM FL2666D4S19-8G 8GB SODIMM DDR4 2667MT/s             | 2         | 3.17%   |
| Unknown RAM Module 512MB SODIMM DDR2 667MT/s                    | 1         | 1.59%   |
| Unknown RAM Module 4096MB SODIMM 800MT/s                        | 1         | 1.59%   |
| Unknown RAM Module 2GB SODIMM DDR2                              | 1         | 1.59%   |
| Unknown RAM Module 1024MB SODIMM DDR2 333MT/s                   | 1         | 1.59%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 1.59%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1334MT/s       | 1         | 1.59%   |
| SK Hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s          | 1         | 1.59%   |
| SK Hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s          | 1         | 1.59%   |
| SK Hynix RAM HMA851S6CJR6N-XN 4096MB Row Of Chips DDR4 3200MT/s | 1         | 1.59%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s          | 1         | 1.59%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s       | 1         | 1.59%   |
| Samsung RAM U6E3S4AA-MGCR 1GB Row Of Chips LPDDR4 4267MT/s      | 1         | 1.59%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s           | 1         | 1.59%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s        | 1         | 1.59%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s        | 1         | 1.59%   |
| Samsung RAM M471A5644EB0-CRC 2GB SODIMM DDR4 2400MT/s           | 1         | 1.59%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s        | 1         | 1.59%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s        | 1         | 1.59%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s           | 1         | 1.59%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s           | 1         | 1.59%   |
| Samsung RAM K4UBE3D4AA-MGCH 8192MB Row Of Chips LPDDR4 3200MT/s | 1         | 1.59%   |
| Samsung RAM K4A8G165WC-BCTD 4GB SODIMM DDR4 2667MT/s            | 1         | 1.59%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s         | 1         | 1.59%   |
| Ramaxel RAM RMSA3310NA86H9F-2666 4GB SODIMM DDR4 2667MT/s       | 1         | 1.59%   |
| Micron RAM Module 4096MB Row Of Chips DDR4 2400MT/s             | 1         | 1.59%   |
| Micron RAM 4ATF51264HZ-3G2J1 4096MB SODIMM DDR4 3200MT/s        | 1         | 1.59%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s           | 1         | 1.59%   |
| Micron RAM 4ATF51264HZ-2G3AZ 4096MB SODIMM DDR4 2133MT/s        | 1         | 1.59%   |
| Kingston RAM MSI24D4S7S8MB-8 8GB SODIMM DDR4 2400MT/s           | 1         | 1.59%   |
| Kingston RAM CBD24D4S7S8ME-8 8192MB SODIMM DDR4 2400MT/s        | 1         | 1.59%   |
| Kingston RAM 99U5469-078.A00LF 4096MB SODIMM DDR3 1600MT/s      | 1         | 1.59%   |
| Kingston RAM 99U5469-046.A00LF 4096MB SODIMM DDR3 1333MT/s      | 1         | 1.59%   |
| Kingston RAM 99U5469-045.A00LF 4096MB SODIMM DDR3 1600MT/s      | 1         | 1.59%   |
| Elpida RAM EDJ4216EFBG-GNL-F 4GB SODIMM DDR3 1600MT/s           | 1         | 1.59%   |
| Crucial RAM CT51264BF160BJ.M8F 4GB SODIMM DDR3 1600MT/s         | 1         | 1.59%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s         | 1         | 1.59%   |
| A-DATA RAM AO1P26KC4U1-BXOS 4096MB SODIMM DDR4 2667MT/s         | 1         | 1.59%   |
| A-DATA RAM AO1L16BC4R1-BQSS 4096MB SODIMM DDR3 1600MT/s         | 1         | 1.59%   |
| A-DATA RAM AD73I1C1674EV 4096MB SODIMM DDR3 1334MT/s            | 1         | 1.59%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 31        | 54.39%  |
| DDR3    | 15        | 26.32%  |
| DDR2    | 8         | 14.04%  |
| LPDDR4  | 2         | 3.51%   |
| Unknown | 1         | 1.75%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 50        | 86.21%  |
| Row Of Chips | 8         | 13.79%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Notebooks | Percent |
|------|-----------|---------|
| 4096 | 31        | 51.67%  |
| 8192 | 18        | 30%     |
| 2048 | 9         | 15%     |
| 1024 | 1         | 1.67%   |
| 512  | 1         | 1.67%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 15        | 24.59%  |
| 3200    | 13        | 21.31%  |
| 1600    | 13        | 21.31%  |
| 2400    | 4         | 6.56%   |
| Unknown | 4         | 6.56%   |
| 1334    | 3         | 4.92%   |
| 667     | 3         | 4.92%   |
| 4267    | 1         | 1.64%   |
| 3266    | 1         | 1.64%   |
| 2133    | 1         | 1.64%   |
| 1333    | 1         | 1.64%   |
| 800     | 1         | 1.64%   |
| 333     | 1         | 1.64%   |

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
| IMC Networks                           | 15        | 26.32%  |
| Chicony Electronics                    | 14        | 24.56%  |
| Quanta                                 | 6         | 10.53%  |
| Syntek                                 | 3         | 5.26%   |
| Sunplus Innovation Technology          | 3         | 5.26%   |
| Realtek Semiconductor                  | 3         | 5.26%   |
| Acer                                   | 3         | 5.26%   |
| Suyin                                  | 2         | 3.51%   |
| Z-Star Microelectronics                | 1         | 1.75%   |
| Unknown                                | 1         | 1.75%   |
| Sonix Technology                       | 1         | 1.75%   |
| Silicon Motion                         | 1         | 1.75%   |
| Primax Electronics                     | 1         | 1.75%   |
| Microdia                               | 1         | 1.75%   |
| Lite-On Technology                     | 1         | 1.75%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.75%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                | 5         | 8.77%   |
| IMC Networks Integrated Camera                   | 4         | 7.02%   |
| Quanta HP TrueVision HD Camera                   | 3         | 5.26%   |
| Syntek Integrated Camera                         | 2         | 3.51%   |
| Sunplus Asus Webcam                              | 2         | 3.51%   |
| Chicony VGA Webcam                               | 2         | 3.51%   |
| Chicony Integrated Camera                        | 2         | 3.51%   |
| Chicony HD WebCam                                | 2         | 3.51%   |
| Acer BisonCam, NB Pro                            | 2         | 3.51%   |
| Z-Star Vega USB 2.0 Camera                       | 1         | 1.75%   |
| Unknown USB2.0 Webcam                            | 1         | 1.75%   |
| Syntek Lenovo EasyCamera                         | 1         | 1.75%   |
| Suyin HP Truevision HD                           | 1         | 1.75%   |
| Suyin 1.3M HD WebCam                             | 1         | 1.75%   |
| Sunplus Integrated_Webcam_HD                     | 1         | 1.75%   |
| Sonix USB2.0 HD UVC WebCam                       | 1         | 1.75%   |
| Silicon Motion WebCam SC-0311139N                | 1         | 1.75%   |
| Realtek Lenovo EasyCamera                        | 1         | 1.75%   |
| Realtek Integrated_Webcam_HD                     | 1         | 1.75%   |
| Realtek EasyCamera                               | 1         | 1.75%   |
| Quanta VGA WebCam                                | 1         | 1.75%   |
| Quanta HP Wide Vision HD Camera                  | 1         | 1.75%   |
| Quanta HP Webcam                                 | 1         | 1.75%   |
| Primax HP HD Webcam [Fixed]                      | 1         | 1.75%   |
| Microdia Integrated_Webcam_HD                    | 1         | 1.75%   |
| Lite-On HP Webcam                                | 1         | 1.75%   |
| IMC Networks VGA UVC WebCam                      | 1         | 1.75%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 1         | 1.75%   |
| IMC Networks USB 2.0 Camera                      | 1         | 1.75%   |
| IMC Networks ov9734_azurewave_camera             | 1         | 1.75%   |
| IMC Networks HP TrueVision HD Camera             | 1         | 1.75%   |
| IMC Networks HD Camera                           | 1         | 1.75%   |
| Chicony XiaoMi USB 2.0 Webcam                    | 1         | 1.75%   |
| Chicony USB2.0 HD UVC WebCam                     | 1         | 1.75%   |
| Chicony USB camera                               | 1         | 1.75%   |
| Chicony USB 2.0 Webcam Device                    | 1         | 1.75%   |
| Chicony Lenovo Integrated Camera (0.3MP)         | 1         | 1.75%   |
| Chicony Integrated HP HD Webcam                  | 1         | 1.75%   |
| Chicony CNF7070 Webcam                           | 1         | 1.75%   |
| Chicony 1.3M HD WebCam                           | 1         | 1.75%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 1         | 1.75%   |
| Acer BisonCam,NB Pro                             | 1         | 1.75%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 3         | 33.33%  |
| Synaptics                  | 2         | 22.22%  |
| Elan Microelectronics      | 2         | 22.22%  |
| Shenzhen Goodix Technology | 1         | 11.11%  |
| LighTuning Technology      | 1         | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS491                           | 2         | 22.22%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 2         | 22.22%  |
| Validity Sensors VFS5011 Fingerprint Reader       | 1         | 11.11%  |
| Shenzhen Goodix  Fingerprint Device               | 1         | 11.11%  |
| LighTuning EgisTec Touch Fingerprint Sensor       | 1         | 11.11%  |
| Elan ELAN:Fingerprint                             | 1         | 11.11%  |
| Elan ELAN:ARM-M4                                  | 1         | 11.11%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 3         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 3         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 40        | 60.61%  |
| 1     | 18        | 27.27%  |
| 2     | 7         | 10.61%  |
| 3     | 1         | 1.52%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 9         | 29.03%  |
| Graphics card            | 8         | 25.81%  |
| Communication controller | 6         | 19.35%  |
| Chipcard                 | 3         | 9.68%   |
| Net/ethernet             | 2         | 6.45%   |
| Multimedia controller    | 1         | 3.23%   |
| Camera                   | 1         | 3.23%   |
| Bluetooth                | 1         | 3.23%   |

