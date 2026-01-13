Sparky - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for Sparky.

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

Total: 88

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | [17bae1fed1](https://linux-hardware.org/?probe=17bae1fed1) | Jan 03, 2026 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | [fe9e88163a](https://linux-hardware.org/?probe=fe9e88163a) | Jan 03, 2026 |
| HP            | ProBook 6560b               | [182da91655](https://linux-hardware.org/?probe=182da91655) | Jan 03, 2026 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [8ba69eb230](https://linux-hardware.org/?probe=8ba69eb230) | Dec 23, 2025 |
| Lenovo        | ThinkPad T480 20L6S9UJ0Y    | [d2908fddcd](https://linux-hardware.org/?probe=d2908fddcd) | Dec 22, 2025 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [b797292408](https://linux-hardware.org/?probe=b797292408) | Dec 21, 2025 |
| Dell          | Inspiron 5535               | [063482a1f5](https://linux-hardware.org/?probe=063482a1f5) | Nov 19, 2025 |
| Apple         | MacBookPro5,1               | [7443e73d63](https://linux-hardware.org/?probe=7443e73d63) | Nov 14, 2025 |
| ASUSTek       | X450CA                      | [ebf7b86f8b](https://linux-hardware.org/?probe=ebf7b86f8b) | Jul 07, 2025 |
| HP            | Compaq CQ45                 | [22c2ab9efc](https://linux-hardware.org/?probe=22c2ab9efc) | May 28, 2025 |
| Toshiba       | Satellite P755              | [114d7f3084](https://linux-hardware.org/?probe=114d7f3084) | May 13, 2025 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [9f416ad681](https://linux-hardware.org/?probe=9f416ad681) | Mar 27, 2025 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [ee7d28d410](https://linux-hardware.org/?probe=ee7d28d410) | Mar 13, 2025 |
| ASUSTek       | X510UAR                     | [758c2eb717](https://linux-hardware.org/?probe=758c2eb717) | Dec 17, 2024 |
| Shuttle       | NC03U                       | [b21ed9ceef](https://linux-hardware.org/?probe=b21ed9ceef) | Nov 15, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [3595b48d6f](https://linux-hardware.org/?probe=3595b48d6f) | Jun 17, 2024 |
| Toshiba       | Satellite L505D             | [a6d35efbaa](https://linux-hardware.org/?probe=a6d35efbaa) | Jun 11, 2024 |
| Google        | Fleex                       | [281114687b](https://linux-hardware.org/?probe=281114687b) | May 29, 2024 |
| Google        | Setzer                      | [a62ca31dce](https://linux-hardware.org/?probe=a62ca31dce) | May 25, 2024 |
| Google        | Meep                        | [8c7de68350](https://linux-hardware.org/?probe=8c7de68350) | May 13, 2024 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [c03d3e0508](https://linux-hardware.org/?probe=c03d3e0508) | May 03, 2024 |
| Lenovo        | ThinkPad T430 2349FC4       | [1b0129f0b0](https://linux-hardware.org/?probe=1b0129f0b0) | Apr 06, 2024 |
| Sony          | SVE1513Q1ESI                | [9362c14552](https://linux-hardware.org/?probe=9362c14552) | Mar 25, 2024 |
| Samsung       | N150P/N210P/N220P           | [b861f48e1b](https://linux-hardware.org/?probe=b861f48e1b) | Feb 18, 2024 |
| Samsung       | N150/N210/N220              | [cf3126113e](https://linux-hardware.org/?probe=cf3126113e) | Feb 15, 2024 |
| Google        | Kefka                       | [810d5a47f7](https://linux-hardware.org/?probe=810d5a47f7) | Jan 27, 2024 |
| Lenovo        | ThinkPad T430 2349FC4       | [655eb2734a](https://linux-hardware.org/?probe=655eb2734a) | Jan 11, 2024 |
| Lenovo        | ThinkPad T430 2349FC4       | [ea07a49b87](https://linux-hardware.org/?probe=ea07a49b87) | Jan 07, 2024 |
| Lenovo        | ThinkPad T430 2349FC4       | [689d3295aa](https://linux-hardware.org/?probe=689d3295aa) | Dec 30, 2023 |
| Acer          | Aspire SW5-012              | [4efea61fa3](https://linux-hardware.org/?probe=4efea61fa3) | Dec 29, 2023 |
| HP            | Laptop 15-ef2xxx            | [80d1578d90](https://linux-hardware.org/?probe=80d1578d90) | Oct 30, 2023 |
| Medion        | E15415                      | [b9a4ecdc97](https://linux-hardware.org/?probe=b9a4ecdc97) | Oct 14, 2023 |
| HP            | 250 G7 Notebook PC          | [2fc3f16671](https://linux-hardware.org/?probe=2fc3f16671) | Sep 30, 2023 |
| HP            | Pavilion g6                 | [158b6f4df9](https://linux-hardware.org/?probe=158b6f4df9) | Sep 17, 2023 |
| HP            | Laptop 15-ef2xxx            | [b0dbfa8a76](https://linux-hardware.org/?probe=b0dbfa8a76) | Aug 26, 2023 |
| HP            | Laptop 15-ef2xxx            | [da3f894af1](https://linux-hardware.org/?probe=da3f894af1) | Aug 26, 2023 |
| Apple         | MacBookPro9,2               | [4006007a76](https://linux-hardware.org/?probe=4006007a76) | Aug 20, 2023 |
| Acer          | Aspire 5920                 | [31447ef238](https://linux-hardware.org/?probe=31447ef238) | Aug 17, 2023 |
| Acer          | Aspire 5920                 | [8c57c50f82](https://linux-hardware.org/?probe=8c57c50f82) | Aug 17, 2023 |
| Acer          | Aspire A315-58              | [d7383d2980](https://linux-hardware.org/?probe=d7383d2980) | Jul 20, 2023 |
| HP            | EliteBook 8440p             | [f7a66609af](https://linux-hardware.org/?probe=f7a66609af) | Jul 13, 2023 |
| Panasonic     | CFSZ5-2                     | [d5b1455382](https://linux-hardware.org/?probe=d5b1455382) | May 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [37dab045c7](https://linux-hardware.org/?probe=37dab045c7) | May 21, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | [24aaf9e627](https://linux-hardware.org/?probe=24aaf9e627) | May 13, 2023 |
| Apple         | MacBook1,1                  | [002929e495](https://linux-hardware.org/?probe=002929e495) | Mar 26, 2023 |
| MSI           | Alpha 15 A3DDK              | [c4ef9294ef](https://linux-hardware.org/?probe=c4ef9294ef) | Feb 23, 2023 |
| MSI           | Alpha 15 A3DDK              | [219483f968](https://linux-hardware.org/?probe=219483f968) | Feb 23, 2023 |
| Positivo      | CHT14B                      | [49eff89b98](https://linux-hardware.org/?probe=49eff89b98) | Feb 16, 2023 |
| Fujitsu Si... | STYLISTIC ST5112            | [c343cec0c8](https://linux-hardware.org/?probe=c343cec0c8) | Jan 30, 2023 |
| Acer          | Aspire E1-522               | [8bf37cf82d](https://linux-hardware.org/?probe=8bf37cf82d) | Dec 26, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [54273f1267](https://linux-hardware.org/?probe=54273f1267) | Dec 22, 2022 |
| Apple         | MacBook1,1                  | [6945006338](https://linux-hardware.org/?probe=6945006338) | Nov 15, 2022 |
| Google        | Swanky                      | [1a0a358398](https://linux-hardware.org/?probe=1a0a358398) | Nov 15, 2022 |
| ASUSTek       | M70Vn                       | [236d8cb74e](https://linux-hardware.org/?probe=236d8cb74e) | Aug 29, 2022 |
| HUAWEI        | HVY-WXX9                    | [b4006730ce](https://linux-hardware.org/?probe=b4006730ce) | Jul 17, 2022 |
| HP            | Stream Notebook PC 13       | [47b55dbb68](https://linux-hardware.org/?probe=47b55dbb68) | Jun 06, 2022 |
| HP            | EliteBook 745 G3            | [fac15b2640](https://linux-hardware.org/?probe=fac15b2640) | May 18, 2022 |
| HP            | EliteBook 8770w             | [4fa8e91f6d](https://linux-hardware.org/?probe=4fa8e91f6d) | Apr 26, 2022 |
| Lenovo        | G50-30 80G0                 | [c7ea70f7ba](https://linux-hardware.org/?probe=c7ea70f7ba) | Apr 25, 2022 |
| HP            | Pavilion dv5                | [22ae3dae3d](https://linux-hardware.org/?probe=22ae3dae3d) | Mar 22, 2022 |
| ASUSTek       | 1000HE                      | [5dd6246e59](https://linux-hardware.org/?probe=5dd6246e59) | Feb 08, 2022 |
| ASUSTek       | S101                        | [a850549e73](https://linux-hardware.org/?probe=a850549e73) | Feb 04, 2022 |
| HP            | EliteBook 8770w             | [9a2052fc8c](https://linux-hardware.org/?probe=9a2052fc8c) | Nov 25, 2021 |
| HP            | Pavilion g7                 | [6cebc99fe6](https://linux-hardware.org/?probe=6cebc99fe6) | Nov 22, 2021 |
| Dell          | Inspiron N5010              | [df5e66431b](https://linux-hardware.org/?probe=df5e66431b) | Nov 20, 2021 |
| HP            | EliteBook Folio 9480m       | [dae2e04d45](https://linux-hardware.org/?probe=dae2e04d45) | Oct 04, 2021 |
| Google        | Banon                       | [764debedcd](https://linux-hardware.org/?probe=764debedcd) | Sep 25, 2021 |
| Lenovo        | ThinkPad E15 20RES0GF00     | [8722c3498e](https://linux-hardware.org/?probe=8722c3498e) | May 14, 2021 |
| Apple         | MacBook1,1                  | [cc415ab6c7](https://linux-hardware.org/?probe=cc415ab6c7) | Mar 15, 2021 |
| Samsung       | NC10                        | [b5909af616](https://linux-hardware.org/?probe=b5909af616) | Mar 11, 2021 |
| Samsung       | NC10                        | [3b8de5559e](https://linux-hardware.org/?probe=3b8de5559e) | Feb 27, 2021 |
| Lenovo        | ThinkPad T61 7659AB7        | [43f03346c5](https://linux-hardware.org/?probe=43f03346c5) | Feb 19, 2021 |
| Beelink       | BT3 PRO                     | [8dbfa4dacd](https://linux-hardware.org/?probe=8dbfa4dacd) | Jan 06, 2021 |
| Beelink       | BT3 PRO                     | [d85a392e02](https://linux-hardware.org/?probe=d85a392e02) | Jan 06, 2021 |
| Samsung       | NC10                        | [8c878860a7](https://linux-hardware.org/?probe=8c878860a7) | Jan 03, 2021 |
| Dell          | Inspiron 5720               | [d360a61780](https://linux-hardware.org/?probe=d360a61780) | Dec 08, 2020 |
| eMachines     | E525                        | [0c11b6b4dc](https://linux-hardware.org/?probe=0c11b6b4dc) | Nov 25, 2020 |
| Lenovo        | IdeaPad S206 20154          | [393f27acf7](https://linux-hardware.org/?probe=393f27acf7) | Nov 18, 2020 |
| Dell          | Inspiron 5720               | [787263a0c6](https://linux-hardware.org/?probe=787263a0c6) | Oct 10, 2020 |
| HP            | Laptop 17z-ca100            | [2217d0703c](https://linux-hardware.org/?probe=2217d0703c) | Oct 05, 2020 |
| HP            | Laptop 17z-ca100            | [1927ffc179](https://linux-hardware.org/?probe=1927ffc179) | Oct 05, 2020 |
| Apple         | MacBook1,1                  | [73b04f9de4](https://linux-hardware.org/?probe=73b04f9de4) | Aug 26, 2020 |
| Acer          | Aspire 5742G                | [a90fb35c67](https://linux-hardware.org/?probe=a90fb35c67) | May 01, 2020 |
| Lenovo        | ThinkPad T60 2007FUG        | [d552e50d7e](https://linux-hardware.org/?probe=d552e50d7e) | Mar 12, 2020 |
| Dell          | Latitude XT3                | [0944e88882](https://linux-hardware.org/?probe=0944e88882) | Mar 09, 2020 |
| Dell          | Inspiron 5770               | [a3dd71465d](https://linux-hardware.org/?probe=a3dd71465d) | Jan 06, 2020 |
| HP            | Pavilion dv9000 (GA359UA... | [db4a924be0](https://linux-hardware.org/?probe=db4a924be0) | Sep 07, 2019 |
| HP            | Pavilion dv9000 (GA359UA... | [6f024c0dd0](https://linux-hardware.org/?probe=6f024c0dd0) | Sep 03, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| Sparky 8    | 9         | 12.68%  |
| Sparky 6    | 8         | 11.27%  |
| Sparky 7    | 7         | 9.86%   |
| Sparky 7.3  | 4         | 5.63%   |
| Sparky 6.5  | 4         | 5.63%   |
| Sparky 6.1  | 4         | 5.63%   |
| Sparky 7.7  | 3         | 4.23%   |
| Sparky 7.2  | 3         | 4.23%   |
| Sparky 6.7  | 3         | 4.23%   |
| Sparky 5.14 | 3         | 4.23%   |
| Sparky 9    | 2         | 2.82%   |
| Sparky 8.1  | 2         | 2.82%   |
| Sparky 7.4  | 2         | 2.82%   |
| Sparky 7.1  | 2         | 2.82%   |
| Sparky 6.6  | 2         | 2.82%   |
| Sparky 6.3  | 2         | 2.82%   |
| Sparky 6.0  | 2         | 2.82%   |
| Sparky 5.13 | 2         | 2.82%   |
| Sparky 5.12 | 2         | 2.82%   |
| Sparky 5.10 | 2         | 2.82%   |
| Sparky 8.0  | 1         | 1.41%   |
| Sparky 7.5  | 1         | 1.41%   |
| Sparky 7.0  | 1         | 1.41%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Sparky | 66        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Notebooks | Percent |
|------------------------|-----------|---------|
| 6.1.0-18-amd64         | 4         | 5.33%   |
| 6.1.0-21-amd64         | 3         | 4%      |
| 5.10.0-11-686          | 3         | 4%      |
| 6.7.12-amd64           | 2         | 2.67%   |
| 6.12.48+deb13-amd64    | 2         | 2.67%   |
| 6.1.0-37-amd64         | 2         | 2.67%   |
| 6.1.0-17-amd64         | 2         | 2.67%   |
| 6.1.0-12-amd64         | 2         | 2.67%   |
| 5.17.0-1-amd64         | 2         | 2.67%   |
| 5.10.0-9-amd64         | 2         | 2.67%   |
| 5.10.0-8-amd64         | 2         | 2.67%   |
| 5.10.0-21-amd64        | 2         | 2.67%   |
| 4.19.0-8-amd64         | 2         | 2.67%   |
| 4.19.0-13-686          | 2         | 2.67%   |
| 4.19.0-12-amd64        | 2         | 2.67%   |
| 6.5.9-x64v3-xanmod1    | 1         | 1.33%   |
| 6.5.0-5-amd64          | 1         | 1.33%   |
| 6.4.4-sparky8-amd64    | 1         | 1.33%   |
| 6.4.12-x64v3-xanmod1   | 1         | 1.33%   |
| 6.4.0-2-amd64          | 1         | 1.33%   |
| 6.3.3-1-liquorix-amd64 | 1         | 1.33%   |
| 6.3.0-1-amd64          | 1         | 1.33%   |
| 6.2.0-sparky-amd64     | 1         | 1.33%   |
| 6.17.13+deb14-amd64    | 1         | 1.33%   |
| 6.16.12+deb14+1-amd64  | 1         | 1.33%   |
| 6.12.57+deb13-amd64    | 1         | 1.33%   |
| 6.12.17-amd64          | 1         | 1.33%   |
| 6.11.10-amd64          | 1         | 1.33%   |
| 6.1.0-34-amd64         | 1         | 1.33%   |
| 6.1.0-27-amd64         | 1         | 1.33%   |
| 6.1.0-16-amd64         | 1         | 1.33%   |
| 6.1.0-10-amd64         | 1         | 1.33%   |
| 5.9.0-4-amd64          | 1         | 1.33%   |
| 5.8.13-sparky-amd64    | 1         | 1.33%   |
| 5.8.0-2-amd64          | 1         | 1.33%   |
| 5.5.0-2-amd64          | 1         | 1.33%   |
| 5.4.7-sparky-amd64     | 1         | 1.33%   |
| 5.2.0-2-amd64          | 1         | 1.33%   |
| 5.18.0-4-amd64         | 1         | 1.33%   |
| 5.18.0-2-amd64         | 1         | 1.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 18        | 25.71%  |
| 6.1.0   | 15        | 21.43%  |
| 4.19.0  | 6         | 8.57%   |
| 6.7.12  | 2         | 2.86%   |
| 6.12.48 | 2         | 2.86%   |
| 5.18.0  | 2         | 2.86%   |
| 5.17.0  | 2         | 2.86%   |
| 6.5.9   | 1         | 1.43%   |
| 6.5.0   | 1         | 1.43%   |
| 6.4.4   | 1         | 1.43%   |
| 6.4.12  | 1         | 1.43%   |
| 6.4.0   | 1         | 1.43%   |
| 6.3.3   | 1         | 1.43%   |
| 6.3.0   | 1         | 1.43%   |
| 6.2.0   | 1         | 1.43%   |
| 6.17.13 | 1         | 1.43%   |
| 6.16.12 | 1         | 1.43%   |
| 6.12.57 | 1         | 1.43%   |
| 6.12.17 | 1         | 1.43%   |
| 6.11.10 | 1         | 1.43%   |
| 5.9.0   | 1         | 1.43%   |
| 5.8.13  | 1         | 1.43%   |
| 5.8.0   | 1         | 1.43%   |
| 5.5.0   | 1         | 1.43%   |
| 5.4.7   | 1         | 1.43%   |
| 5.2.0   | 1         | 1.43%   |
| 5.16.0  | 1         | 1.43%   |
| 5.15.0  | 1         | 1.43%   |
| 5.14.0  | 1         | 1.43%   |
| 5.10.4  | 1         | 1.43%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 19        | 27.14%  |
| 6.1     | 15        | 21.43%  |
| 4.19    | 6         | 8.57%   |
| 6.12    | 4         | 5.71%   |
| 6.4     | 3         | 4.29%   |
| 6.7     | 2         | 2.86%   |
| 6.5     | 2         | 2.86%   |
| 6.3     | 2         | 2.86%   |
| 5.8     | 2         | 2.86%   |
| 5.18    | 2         | 2.86%   |
| 5.17    | 2         | 2.86%   |
| 6.2     | 1         | 1.43%   |
| 6.17    | 1         | 1.43%   |
| 6.16    | 1         | 1.43%   |
| 6.11    | 1         | 1.43%   |
| 5.9     | 1         | 1.43%   |
| 5.5     | 1         | 1.43%   |
| 5.4     | 1         | 1.43%   |
| 5.2     | 1         | 1.43%   |
| 5.16    | 1         | 1.43%   |
| 5.15    | 1         | 1.43%   |
| 5.14    | 1         | 1.43%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 61        | 92.42%  |
| i686   | 5         | 7.58%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| XFCE             | 20        | 29.85%  |
| LXQt             | 13        | 19.4%   |
| KDE5             | 9         | 13.43%  |
| Unknown          | 8         | 11.94%  |
| openbox          | 3         | 4.48%   |
| MATE             | 3         | 4.48%   |
| X-Cinnamon       | 2         | 2.99%   |
| KDE6             | 2         | 2.99%   |
| lightdm-xsession | 1         | 1.49%   |
| KDE              | 1         | 1.49%   |
| GNOME Classic    | 1         | 1.49%   |
| GNOME            | 1         | 1.49%   |
| Draco            | 1         | 1.49%   |
| Cinnamon         | 1         | 1.49%   |
| Budgie           | 1         | 1.49%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 60        | 89.55%  |
| Tty     | 6         | 8.96%   |
| Wayland | 1         | 1.49%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 24        | 35.82%  |
| Unknown | 21        | 31.34%  |
| SDDM    | 14        | 20.9%   |
| TDM     | 6         | 8.96%   |
| XDM     | 1         | 1.49%   |
| GDM     | 1         | 1.49%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 24        | 36.36%  |
| pl_PL   | 6         | 9.09%   |
| es_ES   | 5         | 7.58%   |
| en_GB   | 4         | 6.06%   |
| de_DE   | 4         | 6.06%   |
| it_IT   | 3         | 4.55%   |
| es_MX   | 3         | 4.55%   |
| ru_RU   | 2         | 3.03%   |
| pt_BR   | 2         | 3.03%   |
| fr_FR   | 2         | 3.03%   |
| Unknown | 2         | 3.03%   |
| ja_JP   | 1         | 1.52%   |
| gl_ES   | 1         | 1.52%   |
| fr_BE   | 1         | 1.52%   |
| es_CO   | 1         | 1.52%   |
| es_CL   | 1         | 1.52%   |
| en_PH   | 1         | 1.52%   |
| en_IN   | 1         | 1.52%   |
| en_CA   | 1         | 1.52%   |
| ar_EG   | 1         | 1.52%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 38        | 56.72%  |
| EFI  | 29        | 43.28%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 56        | 84.85%  |
| Overlay | 4         | 6.06%   |
| Btrfs   | 4         | 6.06%   |
| Tmpfs   | 1         | 1.52%   |
| Ext2    | 1         | 1.52%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 30        | 44.78%  |
| Unknown | 21        | 31.34%  |
| MBR     | 16        | 23.88%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 55        | 83.33%  |
| Yes       | 11        | 16.67%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 48        | 72.73%  |
| Yes       | 18        | 27.27%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 15        | 22.73%  |
| Lenovo              | 10        | 15.15%  |
| Google              | 6         | 9.09%   |
| ASUSTek Computer    | 6         | 9.09%   |
| Dell                | 5         | 7.58%   |
| Acer                | 5         | 7.58%   |
| Samsung Electronics | 3         | 4.55%   |
| Apple               | 3         | 4.55%   |
| Toshiba             | 2         | 3.03%   |
| Sony                | 1         | 1.52%   |
| Shuttle             | 1         | 1.52%   |
| Positivo            | 1         | 1.52%   |
| Panasonic           | 1         | 1.52%   |
| MSI                 | 1         | 1.52%   |
| Medion              | 1         | 1.52%   |
| Mediacom            | 1         | 1.52%   |
| HUAWEI              | 1         | 1.52%   |
| Fujitsu Siemens     | 1         | 1.52%   |
| eMachines           | 1         | 1.52%   |
| Beelink             | 1         | 1.52%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Toshiba Satellite P755                | 1         | 1.52%   |
| Toshiba Satellite L505D               | 1         | 1.52%   |
| Sony SVE1513Q1ESI                     | 1         | 1.52%   |
| Shuttle NC03U                         | 1         | 1.52%   |
| Samsung NC10                          | 1         | 1.52%   |
| Samsung N150P/N210P/N220P             | 1         | 1.52%   |
| Samsung N150/N210/N220                | 1         | 1.52%   |
| Positivo CHT14B                       | 1         | 1.52%   |
| Panasonic CFSZ5-2                     | 1         | 1.52%   |
| MSI Alpha 15 A3DDK                    | 1         | 1.52%   |
| Medion E15415                         | 1         | 1.52%   |
| Mediacom SmartBook 14 FullHD - SB14UC | 1         | 1.52%   |
| Lenovo ThinkPad T61 7659AB7           | 1         | 1.52%   |
| Lenovo ThinkPad T60 2007FUG           | 1         | 1.52%   |
| Lenovo ThinkPad T430 2349FC4          | 1         | 1.52%   |
| Lenovo ThinkPad T14 Gen 2i 20W1S29800 | 1         | 1.52%   |
| Lenovo ThinkPad E15 20RES0GF00        | 1         | 1.52%   |
| Lenovo ThinkPad 13 2nd Gen 20J2S20R00 | 1         | 1.52%   |
| Lenovo IdeaPad S340-15IIL 81VW        | 1         | 1.52%   |
| Lenovo IdeaPad S206 20154             | 1         | 1.52%   |
| Lenovo IdeaPad 3 15IML05 81WB         | 1         | 1.52%   |
| Lenovo G50-30 80G0                    | 1         | 1.52%   |
| HUAWEI HVY-WXX9                       | 1         | 1.52%   |
| HP Stream Notebook PC 13              | 1         | 1.52%   |
| HP ProBook 6560b                      | 1         | 1.52%   |
| HP Pavilion Gaming Laptop 15-cx0xxx   | 1         | 1.52%   |
| HP Pavilion g7                        | 1         | 1.52%   |
| HP Pavilion g6                        | 1         | 1.52%   |
| HP Pavilion dv9000 (GA359UA#ABA)      | 1         | 1.52%   |
| HP Pavilion dv5                       | 1         | 1.52%   |
| HP Laptop 17z-ca100                   | 1         | 1.52%   |
| HP Laptop 15-ef2xxx                   | 1         | 1.52%   |
| HP EliteBook Folio 9480m              | 1         | 1.52%   |
| HP EliteBook 8770w                    | 1         | 1.52%   |
| HP EliteBook 8440p                    | 1         | 1.52%   |
| HP EliteBook 745 G3                   | 1         | 1.52%   |
| HP Compaq CQ45                        | 1         | 1.52%   |
| HP 250 G7 Notebook PC                 | 1         | 1.52%   |
| Google Swanky                         | 1         | 1.52%   |
| Google Setzer                         | 1         | 1.52%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Lenovo ThinkPad           | 6         | 9.09%   |
| HP Pavilion               | 5         | 7.58%   |
| Acer Aspire               | 5         | 7.58%   |
| HP EliteBook              | 4         | 6.06%   |
| Dell Inspiron             | 4         | 6.06%   |
| Lenovo IdeaPad            | 3         | 4.55%   |
| Toshiba Satellite         | 2         | 3.03%   |
| HP Laptop                 | 2         | 3.03%   |
| Sony SVE1513Q1ESI         | 1         | 1.52%   |
| Shuttle NC03U             | 1         | 1.52%   |
| Samsung NC10              | 1         | 1.52%   |
| Samsung N150P             | 1         | 1.52%   |
| Samsung N150              | 1         | 1.52%   |
| Positivo CHT14B           | 1         | 1.52%   |
| Panasonic CFSZ5-2         | 1         | 1.52%   |
| MSI Alpha                 | 1         | 1.52%   |
| Medion E15415             | 1         | 1.52%   |
| Mediacom SmartBook        | 1         | 1.52%   |
| Lenovo G50-30             | 1         | 1.52%   |
| HUAWEI HVY-WXX9           | 1         | 1.52%   |
| HP Stream                 | 1         | 1.52%   |
| HP ProBook                | 1         | 1.52%   |
| HP Compaq                 | 1         | 1.52%   |
| HP 250                    | 1         | 1.52%   |
| Google Swanky             | 1         | 1.52%   |
| Google Setzer             | 1         | 1.52%   |
| Google Meep               | 1         | 1.52%   |
| Google Kefka              | 1         | 1.52%   |
| Google Fleex              | 1         | 1.52%   |
| Google Banon              | 1         | 1.52%   |
| Fujitsu Siemens STYLISTIC | 1         | 1.52%   |
| eMachines E525            | 1         | 1.52%   |
| Dell Latitude             | 1         | 1.52%   |
| Beelink BT3               | 1         | 1.52%   |
| ASUS X510UAR              | 1         | 1.52%   |
| ASUS X450CA               | 1         | 1.52%   |
| ASUS VivoBook             | 1         | 1.52%   |
| ASUS S101                 | 1         | 1.52%   |
| ASUS M70Vn                | 1         | 1.52%   |
| ASUS 1000HE               | 1         | 1.52%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2012 | 9         | 13.64%  |
| 2021 | 5         | 7.58%   |
| 2017 | 5         | 7.58%   |
| 2011 | 5         | 7.58%   |
| 2009 | 5         | 7.58%   |
| 2008 | 5         | 7.58%   |
| 2010 | 4         | 6.06%   |
| 2024 | 3         | 4.55%   |
| 2020 | 3         | 4.55%   |
| 2018 | 3         | 4.55%   |
| 2014 | 3         | 4.55%   |
| 2013 | 3         | 4.55%   |
| 2022 | 2         | 3.03%   |
| 2019 | 2         | 3.03%   |
| 2016 | 2         | 3.03%   |
| 2015 | 2         | 3.03%   |
| 2007 | 2         | 3.03%   |
| 2006 | 2         | 3.03%   |
| 2023 | 1         | 1.52%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 66        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 64        | 96.97%  |
| Enabled  | 2         | 3.03%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 60        | 90.91%  |
| Yes  | 6         | 9.09%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 20        | 30.3%   |
| 4.01-8.0   | 12        | 18.18%  |
| 1.01-2.0   | 10        | 15.15%  |
| 16.01-24.0 | 8         | 12.12%  |
| 2.01-3.0   | 6         | 9.09%   |
| 8.01-16.0  | 5         | 7.58%   |
| 32.01-64.0 | 3         | 4.55%   |
| 24.01-32.0 | 1         | 1.52%   |
| 0.51-1.0   | 1         | 1.52%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 21        | 30.43%  |
| 2.01-3.0  | 19        | 27.54%  |
| 0.51-1.0  | 14        | 20.29%  |
| 3.01-4.0  | 6         | 8.7%    |
| 4.01-8.0  | 5         | 7.25%   |
| 0.01-0.5  | 3         | 4.35%   |
| 8.01-16.0 | 1         | 1.45%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 51        | 77.27%  |
| 2      | 13        | 19.7%   |
| 5      | 1         | 1.52%   |
| 4      | 1         | 1.52%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 42        | 63.64%  |
| Yes       | 24        | 36.36%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 50        | 75.76%  |
| No        | 16        | 24.24%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 62        | 93.94%  |
| No        | 4         | 6.06%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 48        | 72.73%  |
| No        | 18        | 27.27%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 16        | 24.24%  |
| Spain       | 6         | 9.09%   |
| Poland      | 6         | 9.09%   |
| Germany     | 6         | 9.09%   |
| Italy       | 5         | 7.58%   |
| UK          | 4         | 6.06%   |
| Canada      | 3         | 4.55%   |
| Mexico      | 2         | 3.03%   |
| France      | 2         | 3.03%   |
| Chile       | 2         | 3.03%   |
| Brazil      | 2         | 3.03%   |
| Uzbekistan  | 1         | 1.52%   |
| UAE         | 1         | 1.52%   |
| Russia      | 1         | 1.52%   |
| Philippines | 1         | 1.52%   |
| New Zealand | 1         | 1.52%   |
| Malaysia    | 1         | 1.52%   |
| Japan       | 1         | 1.52%   |
| Indonesia   | 1         | 1.52%   |
| India       | 1         | 1.52%   |
| Colombia    | 1         | 1.52%   |
| Bulgaria    | 1         | 1.52%   |
| Belgium     | 1         | 1.52%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Vigo           | 2         | 2.9%    |
| Montreal       | 2         | 2.9%    |
| Leipzig        | 2         | 2.9%    |
| Zephyrhills    | 1         | 1.45%   |
| Wenatchee      | 1         | 1.45%   |
| Tucson         | 1         | 1.45%   |
| Trieste        | 1         | 1.45%   |
| Tauranga       | 1         | 1.45%   |
| Takahama       | 1         | 1.45%   |
| Spokane        | 1         | 1.45%   |
| Sofia          | 1         | 1.45%   |
| Silver Spring  | 1         | 1.45%   |
| Santo André   | 1         | 1.45%   |
| Santiago       | 1         | 1.45%   |
| San Antonio    | 1         | 1.45%   |
| Salina Cruz    | 1         | 1.45%   |
| Sainte-Julie   | 1         | 1.45%   |
| Rio de Janeiro | 1         | 1.45%   |
| Quezon City    | 1         | 1.45%   |
| Pujaudran      | 1         | 1.45%   |
| Puente Alto    | 1         | 1.45%   |
| Pompano Beach  | 1         | 1.45%   |
| Munich         | 1         | 1.45%   |
| Mooresville    | 1         | 1.45%   |
| Montreuil      | 1         | 1.45%   |
| Milicz         | 1         | 1.45%   |
| Milano         | 1         | 1.45%   |
| Milan          | 1         | 1.45%   |
| Miekoszyn      | 1         | 1.45%   |
| Mannheim       | 1         | 1.45%   |
| Madrid         | 1         | 1.45%   |
| Lodz           | 1         | 1.45%   |
| Liverpool      | 1         | 1.45%   |
| Legnano        | 1         | 1.45%   |
| Las Vegas      | 1         | 1.45%   |
| Kuala Lumpur   | 1         | 1.45%   |
| Koło          | 1         | 1.45%   |
| Kazan’       | 1         | 1.45%   |
| Jaslo          | 1         | 1.45%   |
| Jakarta        | 1         | 1.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Unknown                     | 11        | 11     | 13.1%   |
| Seagate                     | 11        | 16     | 13.1%   |
| Samsung Electronics         | 10        | 11     | 11.9%   |
| WDC                         | 8         | 10     | 9.52%   |
| Hitachi                     | 5         | 8      | 5.95%   |
| Crucial                     | 4         | 4      | 4.76%   |
| Toshiba                     | 3         | 3      | 3.57%   |
| SPCC                        | 3         | 4      | 3.57%   |
| HGST                        | 3         | 3      | 3.57%   |
| SK hynix                    | 2         | 2      | 2.38%   |
| Silicon Motion              | 2         | 3      | 2.38%   |
| Intel                       | 2         | 2      | 2.38%   |
| GOODRAM                     | 2         | 4      | 2.38%   |
| ASMedia                     | 2         | 2      | 2.38%   |
| A-DATA Technology           | 2         | 4      | 2.38%   |
| Team                        | 1         | 1      | 1.19%   |
| SanDisk                     | 1         | 1      | 1.19%   |
| Phison Electronics          | 1         | 1      | 1.19%   |
| ORICO                       | 1         | 1      | 1.19%   |
| Netac                       | 1         | 1      | 1.19%   |
| Micron Technology           | 1         | 1      | 1.19%   |
| Kingston Technology Company | 1         | 1      | 1.19%   |
| Kingston                    | 1         | 1      | 1.19%   |
| KingDian                    | 1         | 1      | 1.19%   |
| Intenso                     | 1         | 1      | 1.19%   |
| Fujitsu                     | 1         | 2      | 1.19%   |
| ASUS-JM                     | 1         | 1      | 1.19%   |
| Apple                       | 1         | 1      | 1.19%   |
| Unknown                     | 1         | 1      | 1.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 3         | 3.45%   |
| Unknown MMC Card  32GB                                | 2         | 2.3%    |
| Toshiba MQ04ABF100 1TB                                | 2         | 2.3%    |
| Seagate Backup+ Hub BK 6TB                            | 2         | 2.3%    |
| Hitachi HTS545025B9A300 250GB                         | 2         | 2.3%    |
| WDC WD7500BPVX-22JC3T0 752GB                          | 1         | 1.15%   |
| WDC WD5000BEVT-22ZAT0 500GB                           | 1         | 1.15%   |
| WDC WD50 00LPCX-21VHAT0 500GB                         | 1         | 1.15%   |
| WDC WD3200BPVT-75ZEST0 320GB                          | 1         | 1.15%   |
| WDC WD1600BEVT-22ZCT0 160GB                           | 1         | 1.15%   |
| WDC PC SN730 SDBPNTY-512G-1006 512GB                  | 1         | 1.15%   |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB                  | 1         | 1.15%   |
| WDC PC SA530 SDASN8Y-256G-1006 256GB                  | 1         | 1.15%   |
| Unknown SDC  8GB                                      | 1         | 1.15%   |
| Unknown NVMe SSD Drive 512GB                          | 1         | 1.15%   |
| Unknown NCard  32GB                                   | 1         | 1.15%   |
| Unknown MMC Card  64GB                                | 1         | 1.15%   |
| Unknown HBG4a2  32GB                                  | 1         | 1.15%   |
| Unknown hA8aP  16GB                                   | 1         | 1.15%   |
| Unknown DF4016  16GB                                  | 1         | 1.15%   |
| Unknown DA4032  32GB                                  | 1         | 1.15%   |
| Unknown 016GE2  16GB                                  | 1         | 1.15%   |
| Toshiba MK2555GSX 250GB                               | 1         | 1.15%   |
| Team T2531TB SSD                                      | 1         | 1.15%   |
| SPCC Solid State Disk 512GB                           | 1         | 1.15%   |
| SPCC Solid State Disk 256GB                           | 1         | 1.15%   |
| SPCC M.2 PCIe SSD 512GB                               | 1         | 1.15%   |
| SK hynix HCG8e  64GB                                  | 1         | 1.15%   |
| SK hynix BC711 HFM256GD3JX013N 256GB                  | 1         | 1.15%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 512GB | 1         | 1.15%   |
| Silicon Motion PCIe-8 SSD 512GB                       | 1         | 1.15%   |
| Seagate ST9500325AS 500GB                             | 1         | 1.15%   |
| Seagate ST9250320AS 250GB                             | 1         | 1.15%   |
| Seagate ST9160310AS 160GB                             | 1         | 1.15%   |
| Seagate ST750LM022 HN-M750MBB 752GB                   | 1         | 1.15%   |
| Seagate ST1000LM048-2E7172 1TB                        | 1         | 1.15%   |
| Seagate ST1000LM035-1RK172 1TB                        | 1         | 1.15%   |
| Seagate Backup+ Desk 5TB                              | 1         | 1.15%   |
| SanDisk DF4032  32GB                                  | 1         | 1.15%   |
| Samsung SSD 860 EVO M.2 1TB                           | 1         | 1.15%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 15     | 34.38%  |
| WDC                 | 5         | 7      | 15.63%  |
| Hitachi             | 5         | 8      | 15.63%  |
| Toshiba             | 3         | 3      | 9.38%   |
| HGST                | 3         | 3      | 9.38%   |
| ASMedia             | 2         | 2      | 6.25%   |
| Samsung Electronics | 1         | 1      | 3.13%   |
| Fujitsu             | 1         | 2      | 3.13%   |
| Apple               | 1         | 1      | 3.13%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 4      | 16.67%  |
| Crucial             | 4         | 4      | 16.67%  |
| SPCC                | 2         | 3      | 8.33%   |
| Intel               | 2         | 2      | 8.33%   |
| GOODRAM             | 2         | 4      | 8.33%   |
| WDC                 | 1         | 1      | 4.17%   |
| Team                | 1         | 1      | 4.17%   |
| ORICO               | 1         | 1      | 4.17%   |
| Netac               | 1         | 1      | 4.17%   |
| Micron Technology   | 1         | 1      | 4.17%   |
| Kingston            | 1         | 1      | 4.17%   |
| KingDian            | 1         | 1      | 4.17%   |
| Intenso             | 1         | 1      | 4.17%   |
| ASUS-JM             | 1         | 1      | 4.17%   |
| A-DATA Technology   | 1         | 3      | 4.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 30        | 42     | 37.97%  |
| SSD     | 21        | 29     | 26.58%  |
| NVMe    | 14        | 17     | 17.72%  |
| MMC     | 13        | 13     | 16.46%  |
| Unknown | 1         | 1      | 1.27%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 44        | 64     | 57.89%  |
| NVMe | 14        | 17     | 18.42%  |
| MMC  | 13        | 13     | 17.11%  |
| SAS  | 5         | 8      | 6.58%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 34        | 49     | 68%     |
| 0.51-1.0   | 14        | 18     | 28%     |
| 4.01-10.0  | 2         | 4      | 4%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 23        | 34.85%  |
| 501-1000       | 10        | 15.15%  |
| 1-20           | 9         | 13.64%  |
| 21-50          | 8         | 12.12%  |
| 251-500        | 7         | 10.61%  |
| 1001-2000      | 3         | 4.55%   |
| 51-100         | 3         | 4.55%   |
| More than 3000 | 2         | 3.03%   |
| Unknown        | 1         | 1.52%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 33        | 48.53%  |
| 21-50          | 14        | 20.59%  |
| 501-1000       | 6         | 8.82%   |
| 51-100         | 5         | 7.35%   |
| 251-500        | 4         | 5.88%   |
| 101-250        | 3         | 4.41%   |
| More than 3000 | 1         | 1.47%   |
| 1001-2000      | 1         | 1.47%   |
| Unknown        | 1         | 1.47%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-22ZAT0 500GB                         | 1         | 1      | 12.5%   |
| WDC WD3200BPVT-75ZEST0 320GB                        | 1         | 1      | 12.5%   |
| Seagate ST9500325AS 500GB                           | 1         | 1      | 12.5%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 1      | 12.5%   |
| Samsung Electronics HM160HI 160GB                   | 1         | 1      | 12.5%   |
| Micron Technology MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 1      | 12.5%   |
| Intel SSDSC2CW060A3 64GB                            | 1         | 1      | 12.5%   |
| ASMedia ASMT1153e 64GB                              | 1         | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 2         | 2      | 25%     |
| Seagate             | 2         | 2      | 25%     |
| Samsung Electronics | 1         | 1      | 12.5%   |
| Micron Technology   | 1         | 1      | 12.5%   |
| Intel               | 1         | 1      | 12.5%   |
| ASMedia             | 1         | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 2         | 2      | 33.33%  |
| Seagate             | 2         | 2      | 33.33%  |
| Samsung Electronics | 1         | 1      | 16.67%  |
| ASMedia             | 1         | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 6         | 6      | 75%     |
| SSD  | 2         | 2      | 25%     |

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
| Detected | 36        | 52     | 49.32%  |
| Works    | 29        | 42     | 39.73%  |
| Malfunc  | 8         | 8      | 10.96%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 41        | 65.08%  |
| AMD                             | 6         | 9.52%   |
| Samsung Electronics             | 5         | 7.94%   |
| Silicon Motion                  | 3         | 4.76%   |
| Nvidia                          | 2         | 3.17%   |
| SK hynix                        | 1         | 1.59%   |
| Shenzhen Techwinsemi Technology | 1         | 1.59%   |
| SanDisk                         | 1         | 1.59%   |
| Phison Electronics              | 1         | 1.59%   |
| Kingston Technology Company     | 1         | 1.59%   |
| JMicron Technology              | 1         | 1.59%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 7         | 10%     |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 4         | 5.71%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 4         | 5.71%   |
| AMD FCH SATA Controller [AHCI mode]                                          | 4         | 5.71%   |
| Intel Comet Lake SATA AHCI Controller                                        | 3         | 4.29%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                | 3         | 4.29%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]               | 3         | 4.29%   |
| Intel 82801G (ICH7 Family) IDE Controller                                    | 3         | 4.29%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 2         | 2.86%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                  | 2         | 2.86%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                           | 2         | 2.86%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                       | 2         | 2.86%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 2         | 2.86%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                | 2         | 2.86%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                             | 2         | 2.86%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller               | 2         | 2.86%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                         | 1         | 1.43%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers            | 1         | 1.43%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                | 1         | 1.43%   |
| Silicon Motion Non-Volatile memory controller                                | 1         | 1.43%   |
| Shenzhen Techwinsemi TE3420 series / Patriot P320 M.2 NVMe SSD (DRAM-less)   | 1         | 1.43%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                        | 1         | 1.43%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                | 1         | 1.43%   |
| Phison PS5019-E19 PCIe4 NVMe Controller (DRAM-less)                          | 1         | 1.43%   |
| Nvidia MCP79 AHCI Controller                                                 | 1         | 1.43%   |
| Nvidia MCP51 Serial ATA Controller                                           | 1         | 1.43%   |
| Nvidia MCP51 IDE                                                             | 1         | 1.43%   |
| Kingston Company NV2 NVMe SSD [E21T] (DRAM-less)                             | 1         | 1.43%   |
| JMicron JMB360 AHCI Controller                                               | 1         | 1.43%   |
| Intel Tiger Lake-LP SATA Controller                                          | 1         | 1.43%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                            | 1         | 1.43%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                       | 1         | 1.43%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]         | 1         | 1.43%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 1         | 1.43%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 1         | 1.43%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller               | 1         | 1.43%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                             | 1         | 1.43%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                            | 1         | 1.43%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                         | 1         | 1.43%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 43        | 63.24%  |
| NVMe | 13        | 19.12%  |
| IDE  | 11        | 16.18%  |
| RAID | 1         | 1.47%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 55        | 83.33%  |
| AMD    | 11        | 16.67%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel Celeron CPU N2840 @ 2.16GHz    | 3         | 4.55%   |
| Intel Core i5-8250U CPU @ 1.60GHz    | 2         | 3.03%   |
| Intel Core i5-10210U CPU @ 1.60GHz   | 2         | 3.03%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz | 2         | 3.03%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz | 2         | 3.03%   |
| Intel Celeron N4000 CPU @ 1.10GHz    | 2         | 3.03%   |
| Intel Celeron CPU N3060 @ 1.60GHz    | 2         | 3.03%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz    | 2         | 3.03%   |
| Intel Atom CPU N450 @ 1.66GHz        | 2         | 3.03%   |
| Intel Atom CPU N270 @ 1.60GHz        | 2         | 3.03%   |
| Intel Pentium CPU B950 @ 2.10GHz     | 1         | 1.52%   |
| Intel Pentium CPU 6405U @ 2.40GHz    | 1         | 1.52%   |
| Intel Pentium CPU 2117U @ 1.80GHz    | 1         | 1.52%   |
| Intel Genuine CPU T2400 @ 1.83GHz    | 1         | 1.52%   |
| Intel Core i7-7500U CPU @ 2.70GHz    | 1         | 1.52%   |
| Intel Core i7-4600U CPU @ 2.10GHz    | 1         | 1.52%   |
| Intel Core i7-3630QM CPU @ 2.40GHz   | 1         | 1.52%   |
| Intel Core i7-3612QM CPU @ 2.10GHz   | 1         | 1.52%   |
| Intel Core i5-8300H CPU @ 2.30GHz    | 1         | 1.52%   |
| Intel Core i5-6300U CPU @ 2.40GHz    | 1         | 1.52%   |
| Intel Core i5-3320M CPU @ 2.60GHz    | 1         | 1.52%   |
| Intel Core i5-3230M CPU @ 2.60GHz    | 1         | 1.52%   |
| Intel Core i5-3210M CPU @ 2.50GHz    | 1         | 1.52%   |
| Intel Core i5-2520M CPU @ 2.50GHz    | 1         | 1.52%   |
| Intel Core i5-2450M CPU @ 2.50GHz    | 1         | 1.52%   |
| Intel Core i5-1035G4 CPU @ 1.10GHz   | 1         | 1.52%   |
| Intel Core i5 CPU M 520 @ 2.40GHz    | 1         | 1.52%   |
| Intel Core i5 CPU M 460 @ 2.53GHz    | 1         | 1.52%   |
| Intel Core i3 CPU M 380 @ 2.53GHz    | 1         | 1.52%   |
| Intel Core 2 Duo CPU T9550 @ 2.66GHz | 1         | 1.52%   |
| Intel Core 2 CPU U7600 @ 1.20GHz     | 1         | 1.52%   |
| Intel Core 2 CPU T5600 @ 1.83GHz     | 1         | 1.52%   |
| Intel Celeron N4100 CPU @ 1.10GHz    | 1         | 1.52%   |
| Intel Celeron N4020 CPU @ 1.10GHz    | 1         | 1.52%   |
| Intel Celeron CPU N3160 @ 1.60GHz    | 1         | 1.52%   |
| Intel Celeron CPU B840 @ 1.90GHz     | 1         | 1.52%   |
| Intel Celeron CPU B820 @ 1.70GHz     | 1         | 1.52%   |
| Intel Celeron CPU 900 @ 2.20GHz      | 1         | 1.52%   |
| Intel Celeron CPU 3865U @ 1.80GHz    | 1         | 1.52%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz    | 1         | 1.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 14        | 21.21%  |
| Intel Celeron           | 14        | 21.21%  |
| Intel Atom              | 9         | 13.64%  |
| Intel Core 2 Duo        | 5         | 7.58%   |
| Intel Core i7           | 4         | 6.06%   |
| Intel Pentium           | 3         | 4.55%   |
| Other                   | 2         | 3.03%   |
| Intel Core 2            | 2         | 3.03%   |
| AMD Ryzen 5             | 2         | 3.03%   |
| AMD A8                  | 2         | 3.03%   |
| Intel Genuine           | 1         | 1.52%   |
| Intel Core i3           | 1         | 1.52%   |
| AMD Turion 64 X2 Mobile | 1         | 1.52%   |
| AMD Ryzen 7             | 1         | 1.52%   |
| AMD Ryzen 3             | 1         | 1.52%   |
| AMD PRO A10             | 1         | 1.52%   |
| AMD C-50                | 1         | 1.52%   |
| AMD Athlon X2           | 1         | 1.52%   |
| AMD A4                  | 1         | 1.52%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 39        | 59.09%  |
| 4      | 20        | 30.3%   |
| 1      | 6         | 9.09%   |
| 6      | 1         | 1.52%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 66        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 33        | 50%     |
| 1      | 33        | 50%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 62        | 93.94%  |
| 32-bit         | 4         | 6.06%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 27        | 40.3%   |
| 0x406c4    | 5         | 7.46%   |
| 0x306a9    | 3         | 4.48%   |
| 0x30678    | 3         | 4.48%   |
| 0x20655    | 3         | 4.48%   |
| 0x806ec    | 2         | 2.99%   |
| 0x6f2      | 2         | 2.99%   |
| 0x206a7    | 2         | 2.99%   |
| 0x106ca    | 2         | 2.99%   |
| 0x106c2    | 2         | 2.99%   |
| 0x10676    | 2         | 2.99%   |
| 0x08108109 | 2         | 2.99%   |
| 0x806ea    | 1         | 1.49%   |
| 0x706a8    | 1         | 1.49%   |
| 0x706a1    | 1         | 1.49%   |
| 0x406c3    | 1         | 1.49%   |
| 0x40651    | 1         | 1.49%   |
| 0x1067a    | 1         | 1.49%   |
| 0x08608103 | 1         | 1.49%   |
| 0x08600106 | 1         | 1.49%   |
| 0x0700010f | 1         | 1.49%   |
| 0x0600611a | 1         | 1.49%   |
| 0x06001119 | 1         | 1.49%   |
| 0x05000029 | 1         | 1.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| Silvermont      | 10        | 15.15%  |
| KabyLake        | 8         | 12.12%  |
| IvyBridge       | 6         | 9.09%   |
| SandyBridge     | 5         | 7.58%   |
| Bonnell         | 5         | 7.58%   |
| Penryn          | 4         | 6.06%   |
| Goldmont plus   | 4         | 6.06%   |
| Core            | 4         | 6.06%   |
| Westmere        | 3         | 4.55%   |
| Zen+            | 2         | 3.03%   |
| TigerLake       | 2         | 3.03%   |
| Piledriver      | 2         | 3.03%   |
| Zen 2           | 1         | 1.52%   |
| Skylake         | 1         | 1.52%   |
| P6              | 1         | 1.52%   |
| K8 Hammer       | 1         | 1.52%   |
| K8 & K10 hybrid | 1         | 1.52%   |
| Jaguar          | 1         | 1.52%   |
| IceLake         | 1         | 1.52%   |
| Haswell         | 1         | 1.52%   |
| Excavator       | 1         | 1.52%   |
| Bobcat          | 1         | 1.52%   |
| Unknown         | 1         | 1.52%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 49        | 72.06%  |
| AMD    | 11        | 16.18%  |
| Nvidia | 8         | 11.76%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 7.69%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 5         | 6.41%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 6.41%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 5         | 6.41%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 5.13%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 5.13%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 3         | 3.85%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 2         | 2.56%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 2.56%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 2.56%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 2.56%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 2         | 2.56%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 2.56%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 2.56%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 2.56%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 2.56%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 1.28%   |
| Nvidia GK104GLM [Quadro K3000M]                                                          | 1         | 1.28%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 1         | 1.28%   |
| Nvidia GF108M [GeForce GT 420M]                                                          | 1         | 1.28%   |
| Nvidia G96CM [GeForce 9650M GT]                                                          | 1         | 1.28%   |
| Nvidia C79 [GeForce 9400M]                                                               | 1         | 1.28%   |
| Nvidia C51 [GeForce Go 6150]                                                             | 1         | 1.28%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 1.28%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 1         | 1.28%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 1         | 1.28%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 1.28%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 1         | 1.28%   |
| Intel Kaby Lake-U GT1 [HD Graphics 610]                                                  | 1         | 1.28%   |
| Intel Iris Plus Graphics G4 (Ice Lake)                                                   | 1         | 1.28%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 1.28%   |
| Intel Comet Lake-U GT2 [UHD Graphics 620]                                                | 1         | 1.28%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.28%   |
| AMD Wrestler [Radeon HD 6250]                                                            | 1         | 1.28%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 1.28%   |
| AMD Trinity [Radeon HD 7640G]                                                            | 1         | 1.28%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 1         | 1.28%   |
| AMD RV515/M54 [Mobility Radeon X1400]                                                    | 1         | 1.28%   |
| AMD RS780MC [Mobility Radeon HD 3100]                                                    | 1         | 1.28%   |
| AMD Richland [Radeon HD 8510G]                                                           | 1         | 1.28%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 45        | 68.18%  |
| 1 x AMD        | 9         | 13.64%  |
| 1 x Nvidia     | 5         | 7.58%   |
| 2 x Intel      | 2         | 3.03%   |
| 2 x AMD        | 2         | 3.03%   |
| Intel + Nvidia | 2         | 3.03%   |
| 2 x Nvidia     | 1         | 1.52%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 64        | 96.97%  |
| Proprietary | 1         | 1.52%   |
| Unknown     | 1         | 1.52%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 54        | 80.6%   |
| 0.01-0.5   | 8         | 11.94%  |
| 1.01-2.0   | 3         | 4.48%   |
| 0.51-1.0   | 2         | 2.99%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 13        | 18.57%  |
| AU Optronics            | 13        | 18.57%  |
| Chimei Innolux          | 9         | 12.86%  |
| BOE                     | 7         | 10%     |
| Samsung Electronics     | 6         | 8.57%   |
| Lenovo                  | 3         | 4.29%   |
| CPT                     | 3         | 4.29%   |
| Apple                   | 3         | 4.29%   |
| Chi Mei Optoelectronics | 2         | 2.86%   |
| BenQ                    | 2         | 2.86%   |
| Sony                    | 1         | 1.43%   |
| Sceptre Tech            | 1         | 1.43%   |
| PANDA                   | 1         | 1.43%   |
| Medion                  | 1         | 1.43%   |
| LG Philips              | 1         | 1.43%   |
| Insignia                | 1         | 1.43%   |
| Hitachi                 | 1         | 1.43%   |
| HannStar                | 1         | 1.43%   |
| Acer                    | 1         | 1.43%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Sony TV SNY2A03 1920x1080                                             | 1         | 1.41%   |
| Sceptre Tech Sceptre F27 SPT0ABF 1920x1080 409x230mm 18.5-inch        | 1         | 1.41%   |
| Samsung Electronics S24D330 SAM0D93 1920x1080 531x299mm 24.0-inch     | 1         | 1.41%   |
| Samsung Electronics LCD Monitor SEC4F45 1280x800 331x207mm 15.4-inch  | 1         | 1.41%   |
| Samsung Electronics LCD Monitor SEC4141 1366x768 344x193mm 15.5-inch  | 1         | 1.41%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch  | 1         | 1.41%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 309x174mm 14.0-inch  | 1         | 1.41%   |
| Samsung Electronics LCD Monitor SEC3052 1366x768 256x144mm 11.6-inch  | 1         | 1.41%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch | 1         | 1.41%   |
| PANDA LCD Monitor NCP0063 1920x1080 344x194mm 15.5-inch               | 1         | 1.41%   |
| Medion MD 20310 MED3645 1920x1080 521x293mm 23.5-inch                 | 1         | 1.41%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch           | 1         | 1.41%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch         | 1         | 1.41%   |
| LG Display LCD Monitor LGD059E 1920x1080 382x215mm 17.3-inch          | 1         | 1.41%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch          | 1         | 1.41%   |
| LG Display LCD Monitor LGD053B 1920x1080 294x165mm 13.3-inch          | 1         | 1.41%   |
| LG Display LCD Monitor LGD04E1 1366x768 344x194mm 15.5-inch           | 1         | 1.41%   |
| LG Display LCD Monitor LGD03F8 1366x768 345x194mm 15.6-inch           | 1         | 1.41%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch           | 1         | 1.41%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch           | 1         | 1.41%   |
| LG Display LCD Monitor LGD02E1 1600x900 382x215mm 17.3-inch           | 1         | 1.41%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 1         | 1.41%   |
| LG Display LCD Monitor LGD0266 1366x768 344x194mm 15.5-inch           | 1         | 1.41%   |
| LG Display LCD Monitor LGD0212 1366x768 309x174mm 14.0-inch           | 1         | 1.41%   |
| LG Display LCD Monitor LGD01C5 1366x768 293x165mm 13.2-inch           | 1         | 1.41%   |
| Lenovo LCD Monitor LEN4033 1440x900 304x190mm 14.1-inch               | 1         | 1.41%   |
| Lenovo LCD Monitor LEN4022 1400x1050 287x215mm 14.1-inch              | 1         | 1.41%   |
| Lenovo L29w-30 LEN66E5 2560x1080 673x284mm 28.8-inch                  | 1         | 1.41%   |
| Insignia NS-19E320A13 BBY0032 1680x1050 640x384mm 29.4-inch           | 1         | 1.41%   |
| Hitachi HDMI HEC0088 1920x540                                         | 1         | 1.41%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch             | 1         | 1.41%   |
| CPT LCD Monitor CPT37D5 1920x1200 260x160mm 12.0-inch                 | 1         | 1.41%   |
| CPT LCD Monitor CPT04CE 1024x600 222x130mm 10.1-inch                  | 1         | 1.41%   |
| CPT LCD Monitor CPT04C4 1024x600 222x130mm 10.1-inch                  | 1         | 1.41%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 1         | 1.41%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 1         | 1.41%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch      | 1         | 1.41%   |
| Chimei Innolux LCD Monitor CMN15B6 1366x768 340x190mm 15.3-inch       | 1         | 1.41%   |
| Chimei Innolux LCD Monitor CMN153B 1920x1080 344x193mm 15.5-inch      | 1         | 1.41%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 308x173mm 13.9-inch      | 1         | 1.41%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 26        | 37.68%  |
| 1920x1080 (FHD)   | 21        | 30.43%  |
| 1600x900 (HD+)    | 4         | 5.8%    |
| 1280x800 (WXGA)   | 4         | 5.8%    |
| 1024x600          | 4         | 5.8%    |
| 1440x900 (WXGA+)  | 3         | 4.35%   |
| 1920x540          | 2         | 2.9%    |
| 1920x1200 (WUXGA) | 2         | 2.9%    |
| 3840x2160 (4K)    | 1         | 1.45%   |
| 2560x1080         | 1         | 1.45%   |
| 1400x1050         | 1         | 1.45%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 26        | 36.62%  |
| 13     | 10        | 14.08%  |
| 14     | 8         | 11.27%  |
| 17     | 6         | 8.45%   |
| 11     | 4         | 5.63%   |
| 10     | 4         | 5.63%   |
| 48     | 2         | 2.82%   |
| 24     | 2         | 2.82%   |
| 72     | 1         | 1.41%   |
| 54     | 1         | 1.41%   |
| 32     | 1         | 1.41%   |
| 28     | 1         | 1.41%   |
| 23     | 1         | 1.41%   |
| 21     | 1         | 1.41%   |
| 19     | 1         | 1.41%   |
| 16     | 1         | 1.41%   |
| 12     | 1         | 1.41%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 37        | 52.86%  |
| 201-300     | 16        | 22.86%  |
| 351-400     | 7         | 10%     |
| 501-600     | 3         | 4.29%   |
| 1001-1500   | 3         | 4.29%   |
| 701-800     | 1         | 1.43%   |
| 601-700     | 1         | 1.43%   |
| 401-500     | 1         | 1.43%   |
| 1501-2000   | 1         | 1.43%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 54        | 81.82%  |
| 16/10 | 8         | 12.12%  |
| 1.96  | 2         | 3.03%   |
| 4/3   | 1         | 1.52%   |
| 21/9  | 1         | 1.52%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 27        | 38.03%  |
| 81-90          | 12        | 16.9%   |
| 71-80          | 5         | 7.04%   |
| 121-130        | 5         | 7.04%   |
| 51-60          | 4         | 5.63%   |
| 41-50          | 4         | 5.63%   |
| 201-250        | 4         | 5.63%   |
| More than 1000 | 2         | 2.82%   |
| 501-1000       | 2         | 2.82%   |
| 61-70          | 1         | 1.41%   |
| 351-500        | 1         | 1.41%   |
| 251-300        | 1         | 1.41%   |
| 151-200        | 1         | 1.41%   |
| 131-140        | 1         | 1.41%   |
| 91-100         | 1         | 1.41%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 30        | 43.48%  |
| 121-160 | 24        | 34.78%  |
| 51-100  | 9         | 13.04%  |
| 1-50    | 4         | 5.8%    |
| 161-240 | 2         | 2.9%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 59        | 89.39%  |
| 2     | 6         | 9.09%   |
| 0     | 1         | 1.52%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 32        | 32.65%  |
| Realtek Semiconductor      | 26        | 26.53%  |
| Qualcomm Atheros           | 12        | 12.24%  |
| Broadcom                   | 8         | 8.16%   |
| Marvell Technology Group   | 5         | 5.1%    |
| Ralink                     | 3         | 3.06%   |
| TP-Link                    | 2         | 2.04%   |
| Nvidia                     | 2         | 2.04%   |
| Broadcom Limited           | 2         | 2.04%   |
| Shenzhen Goodix Technology | 1         | 1.02%   |
| Samsung Electronics        | 1         | 1.02%   |
| Qualcomm                   | 1         | 1.02%   |
| OPPO Electronics           | 1         | 1.02%   |
| Edimax Technology          | 1         | 1.02%   |
| D-Link                     | 1         | 1.02%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 12        | 10.17%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 8         | 6.78%   |
| Intel Wireless 7265                                                     | 4         | 3.39%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 2.54%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 3         | 2.54%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 2.54%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 2.54%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 3         | 2.54%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2         | 1.69%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 2         | 1.69%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 1.69%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 2         | 1.69%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.69%   |
| Intel Wireless 8265 / 8275                                              | 2         | 1.69%   |
| Intel Wireless 7260                                                     | 2         | 1.69%   |
| Intel Wi-Fi 6 AX201                                                     | 2         | 1.69%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 2         | 1.69%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 1.69%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 1.69%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 1         | 0.85%   |
| TP-Link 802.11ac WLAN Adapter                                           | 1         | 0.85%   |
| Shenzhen Goodix Fingerprint Reader                                      | 1         | 0.85%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 1         | 0.85%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 0.85%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.85%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.85%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 0.85%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.85%   |
| Realtek RTL8187SE Wireless LAN Controller                               | 1         | 0.85%   |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 1         | 0.85%   |
| Realtek Killer E2600 GbE Controller                                     | 1         | 0.85%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                  | 1         | 0.85%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.85%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.85%   |
| Qualcomm Nokia X30 5G                                                   | 1         | 0.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 0.85%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 1         | 0.85%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 0.85%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 0.85%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 30        | 45.45%  |
| Realtek Semiconductor | 11        | 16.67%  |
| Qualcomm Atheros      | 11        | 16.67%  |
| Broadcom              | 5         | 7.58%   |
| Ralink                | 3         | 4.55%   |
| TP-Link               | 2         | 3.03%   |
| Broadcom Limited      | 2         | 3.03%   |
| Edimax Technology     | 1         | 1.52%   |
| D-Link                | 1         | 1.52%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                                     | 4         | 6.06%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 4.55%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 4.55%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 4.55%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 3.03%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2         | 3.03%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 2         | 3.03%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 3.03%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 3.03%   |
| Intel Wireless 8265 / 8275                                              | 2         | 3.03%   |
| Intel Wireless 7260                                                     | 2         | 3.03%   |
| Intel Wi-Fi 6 AX201                                                     | 2         | 3.03%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 2         | 3.03%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 3.03%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 3.03%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 1         | 1.52%   |
| TP-Link 802.11ac WLAN Adapter                                           | 1         | 1.52%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 1.52%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.52%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 1.52%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 1.52%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 1.52%   |
| Realtek RTL8187SE Wireless LAN Controller                               | 1         | 1.52%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                  | 1         | 1.52%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 1         | 1.52%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 1.52%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 1.52%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 1.52%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 1.52%   |
| Intel Wireless 8260                                                     | 1         | 1.52%   |
| Intel WiFi Link 5100                                                    | 1         | 1.52%   |
| Intel Wi-Fi 6 AX200                                                     | 1         | 1.52%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 1         | 1.52%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 1         | 1.52%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 1         | 1.52%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 1.52%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 1         | 1.52%   |
| Intel Centrino Ultimate-N 6300                                          | 1         | 1.52%   |
| Intel Centrino Advanced-N 6200                                          | 1         | 1.52%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 1         | 1.52%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 22        | 43.14%  |
| Intel                    | 11        | 21.57%  |
| Marvell Technology Group | 5         | 9.8%    |
| Qualcomm Atheros         | 4         | 7.84%   |
| Broadcom                 | 4         | 7.84%   |
| Nvidia                   | 2         | 3.92%   |
| Samsung Electronics      | 1         | 1.96%   |
| Qualcomm                 | 1         | 1.96%   |
| OPPO Electronics         | 1         | 1.96%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 12        | 23.53%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 8         | 15.69%  |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 3         | 5.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3         | 5.88%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 2         | 3.92%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1         | 1.96%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 1         | 1.96%   |
| Realtek Killer E2600 GbE Controller                                    | 1         | 1.96%   |
| Qualcomm Nokia X30 5G                                                  | 1         | 1.96%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 1.96%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 1.96%   |
| OPPO Ace 3V                                                            | 1         | 1.96%   |
| Nvidia MCP79 Ethernet                                                  | 1         | 1.96%   |
| Nvidia MCP51 Ethernet Controller                                       | 1         | 1.96%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 1         | 1.96%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                | 1         | 1.96%   |
| Intel I211 Gigabit Network Connection                                  | 1         | 1.96%   |
| Intel Ethernet Connection I219-LM                                      | 1         | 1.96%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 1.96%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 1.96%   |
| Intel 82579V Gigabit Network Connection                                | 1         | 1.96%   |
| Intel 82577LM Gigabit Network Connection                               | 1         | 1.96%   |
| Intel 82573L Gigabit Ethernet Controller                               | 1         | 1.96%   |
| Intel 82566MM Gigabit Network Connection                               | 1         | 1.96%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 1         | 1.96%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                       | 1         | 1.96%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                 | 1         | 1.96%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 1         | 1.96%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 62        | 54.87%  |
| Ethernet | 50        | 44.25%  |
| Modem    | 1         | 0.88%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 51        | 75%     |
| Ethernet | 17        | 25%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 44        | 66.67%  |
| 1     | 18        | 27.27%  |
| 0     | 3         | 4.55%   |
| 3     | 1         | 1.52%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 52        | 76.47%  |
| Yes  | 16        | 23.53%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 19        | 39.58%  |
| Broadcom                        | 8         | 16.67%  |
| Realtek Semiconductor           | 4         | 8.33%   |
| Apple                           | 3         | 6.25%   |
| Qualcomm Atheros Communications | 2         | 4.17%   |
| IMC Networks                    | 2         | 4.17%   |
| Hewlett-Packard                 | 2         | 4.17%   |
| Foxconn / Hon Hai               | 2         | 4.17%   |
| Taiyo Yuden                     | 1         | 2.08%   |
| Realtek                         | 1         | 2.08%   |
| Ralink                          | 1         | 2.08%   |
| Dell                            | 1         | 2.08%   |
| Cambridge Silicon Radio         | 1         | 2.08%   |
| ASUSTek Computer                | 1         | 2.08%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 9         | 18.75%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 6         | 12.5%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 6.25%   |
| Intel AX201 Bluetooth                               | 2         | 4.17%   |
| IMC Networks Bluetooth Radio                        | 2         | 4.17%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 4.17%   |
| Broadcom BCM2045 Bluetooth                          | 2         | 4.17%   |
| Taiyo Yuden Bluetooth Device (V2.0+EDR)             | 1         | 2.08%   |
| Realtek RTL8723B Bluetooth                          | 1         | 2.08%   |
| Realtek Bluetooth Radio                             | 1         | 2.08%   |
| Ralink RT3290 Bluetooth                             | 1         | 2.08%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 2.08%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 2.08%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 2.08%   |
| Intel AX200 Bluetooth                               | 1         | 2.08%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 2.08%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 2.08%   |
| Dell Wireless 365 Bluetooth                         | 1         | 2.08%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 2.08%   |
| Broadcom HP Portable SoftSailing                    | 1         | 2.08%   |
| Broadcom Bluetooth 2.1 Device                       | 1         | 2.08%   |
| Broadcom BCM43142A0 Bluetooth Device                | 1         | 2.08%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 2.08%   |
| Broadcom BCM2070 Bluetooth Device                   | 1         | 2.08%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 1         | 2.08%   |
| ASUS Broadcom Bluetooth 2.1                         | 1         | 2.08%   |
| Apple Bluetooth USB Host Controller                 | 1         | 2.08%   |
| Apple Bluetooth Host Controller                     | 1         | 2.08%   |
| Apple Bluetooth HCI                                 | 1         | 2.08%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 50        | 71.43%  |
| AMD                 | 10        | 14.29%  |
| Nvidia              | 6         | 8.57%   |
| Native Instruments  | 1         | 1.43%   |
| Focusrite-Novation  | 1         | 1.43%   |
| C-Media Electronics | 1         | 1.43%   |
| ASUSTek Computer    | 1         | 1.43%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 8         | 10.13%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 7         | 8.86%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 5         | 6.33%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 5.06%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 5.06%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 3.8%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 3.8%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 3.8%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 3.8%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 3.8%    |
| AMD Ryzen HD Audio Controller                                                                     | 3         | 3.8%    |
| AMD FCH Azalia Controller                                                                         | 3         | 3.8%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 2.53%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 2.53%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 2.53%   |
| AMD Trinity HDMI Audio Controller                                                                 | 2         | 2.53%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 2.53%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                                       | 2         | 2.53%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 2.53%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 1.27%   |
| Nvidia MCP51 High Definition Audio                                                                | 1         | 1.27%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 1.27%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 1.27%   |
| Native Instruments KOMPLETE KONTROL M32                                                           | 1         | 1.27%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 1.27%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 1.27%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 1.27%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 1.27%   |
| Focusrite-Novation Focusrite Scarlett 2i2 2nd Gen                                                 | 1         | 1.27%   |
| C-Media Electronics CM102-A+/102S+ Audio Controller                                               | 1         | 1.27%   |
| ASUSTek Computer C-Media Audio                                                                    | 1         | 1.27%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 1.27%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 1.27%   |
| AMD Navi 10 HDMI Audio                                                                            | 1         | 1.27%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 1.27%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 17        | 29.31%  |
| SK hynix            | 10        | 17.24%  |
| Unknown             | 9         | 15.52%  |
| Micron Technology   | 4         | 6.9%    |
| Nanya Technology    | 2         | 3.45%   |
| Kingston            | 2         | 3.45%   |
| ff                  | 2         | 3.45%   |
| Crucial             | 2         | 3.45%   |
| 4ea5                | 2         | 3.45%   |
| 48spaces            | 2         | 3.45%   |
| Team                | 1         | 1.72%   |
| High Bridge         | 1         | 1.72%   |
| GOODRAM             | 1         | 1.72%   |
| G.Skill             | 1         | 1.72%   |
| Corsair             | 1         | 1.72%   |
| Unknown             | 1         | 1.72%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                               | 2         | 3.28%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s                    | 2         | 3.28%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 3200MT/s                     | 2         | 3.28%   |
| Samsung RAM K4E8E324EB-EGCF 2GB LPDDR3 1867MT/s                           | 2         | 3.28%   |
| 48spaces RAM 012345678901234567890123456789012345 2GB SODIMM DDR2 667MT/s | 2         | 3.28%   |
| Unknown RAM Module 8GB SODIMM DDR3                                        | 1         | 1.64%   |
| Unknown RAM Module 2GB SODIMM SDRAM                                       | 1         | 1.64%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                               | 1         | 1.64%   |
| Unknown RAM Module 2GB SODIMM DDR2 266MT/s                                | 1         | 1.64%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                                  | 1         | 1.64%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                                | 1         | 1.64%   |
| Unknown RAM Module 1024MB SODIMM DDR2                                     | 1         | 1.64%   |
| Unknown RAM Module 1024MB SODIMM 800MT/s                                  | 1         | 1.64%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s                     | 1         | 1.64%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1066MT/s                              | 1         | 1.64%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 1.64%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 1.64%   |
| SK hynix RAM HMT325S6CFR8A-PB 2GB SODIMM DDR3 1600MT/s                    | 1         | 1.64%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s                   | 1         | 1.64%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s                    | 1         | 1.64%   |
| SK hynix RAM H9HCNNN8KUMLHR 1GB 2400MT/s                                  | 1         | 1.64%   |
| SK hynix RAM H9CCNNN8GTALAR-NUD 2GB LPDDR3 1600MT/s                       | 1         | 1.64%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                               | 1         | 1.64%   |
| Samsung RAM Module 2GB SODIMM DDR3 1067MT/s                               | 1         | 1.64%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s                     | 1         | 1.64%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s                     | 1         | 1.64%   |
| Samsung RAM M471B5673FH0-CH9 2048MB SODIMM DDR3 1600MT/s                  | 1         | 1.64%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                     | 1         | 1.64%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 1         | 1.64%   |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1333MT/s                     | 1         | 1.64%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s                     | 1         | 1.64%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s               | 1         | 1.64%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s                    | 1         | 1.64%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 3200MT/s                     | 1         | 1.64%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 8400MT/s                     | 1         | 1.64%   |
| Samsung RAM K4F8E304HB-MGCJ 1GB LPDDR4 2400MT/s                           | 1         | 1.64%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s                      | 1         | 1.64%   |
| Nanya RAM NT2GC64B88B0NS-CG 2048MB SODIMM DDR3 1334MT/s                   | 1         | 1.64%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s                | 1         | 1.64%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s                     | 1         | 1.64%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 24        | 51.06%  |
| DDR4    | 12        | 25.53%  |
| LPDDR3  | 3         | 6.38%   |
| DDR2    | 3         | 6.38%   |
| SDRAM   | 2         | 4.26%   |
| LPDDR4  | 2         | 4.26%   |
| Unknown | 1         | 2.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 39        | 84.78%  |
| Unknown      | 5         | 10.87%  |
| Row Of Chips | 2         | 4.35%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 2048  | 18        | 32.73%  |
| 4096  | 14        | 25.45%  |
| 8192  | 9         | 16.36%  |
| 1024  | 6         | 10.91%  |
| 16384 | 5         | 9.09%   |
| 32768 | 2         | 3.64%   |
| 256   | 1         | 1.82%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 12        | 24%     |
| 3200    | 8         | 16%     |
| 2667    | 5         | 10%     |
| 1334    | 3         | 6%      |
| 1333    | 3         | 6%      |
| 1066    | 3         | 6%      |
| Unknown | 3         | 6%      |
| 2400    | 2         | 4%      |
| 1867    | 2         | 4%      |
| 800     | 2         | 4%      |
| 667     | 2         | 4%      |
| 8400    | 1         | 2%      |
| 4199    | 1         | 2%      |
| 1067    | 1         | 2%      |
| 533     | 1         | 2%      |
| 266     | 1         | 2%      |

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
| Chicony Electronics                    | 16        | 29.63%  |
| Microdia                               | 5         | 9.26%   |
| Suyin                                  | 4         | 7.41%   |
| Realtek Semiconductor                  | 4         | 7.41%   |
| Bison Electronics                      | 4         | 7.41%   |
| Z-Star Microelectronics                | 3         | 5.56%   |
| Quanta                                 | 3         | 5.56%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 5.56%   |
| Sunplus Innovation Technology          | 2         | 3.7%    |
| IMC Networks                           | 2         | 3.7%    |
| Apple                                  | 2         | 3.7%    |
| Alcor Micro                            | 2         | 3.7%    |
| Syntek                                 | 1         | 1.85%   |
| Sonix Technology                       | 1         | 1.85%   |
| Ricoh                                  | 1         | 1.85%   |
| Microsoft                              | 1         | 1.85%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Z-Star Webcam                                               | 2         | 3.64%   |
| Quanta HP TrueVision HD Camera                              | 2         | 3.64%   |
| Chicony Integrated Camera                                   | 2         | 3.64%   |
| Chicony HP Truevision HD                                    | 2         | 3.64%   |
| Chicony HD WebCam                                           | 2         | 3.64%   |
| Alcor Micro USB 2.0 Camera                                  | 2         | 3.64%   |
| Z-Star Namuga 1.3M Webcam                                   | 1         | 1.82%   |
| Syntek Integrated Camera                                    | 1         | 1.82%   |
| Suyin USB2.0 UVC 1.3M WebCam                                | 1         | 1.82%   |
| Suyin HP Truevision HD                                      | 1         | 1.82%   |
| Suyin Acer CrystalEye Webcam                                | 1         | 1.82%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 1.82%   |
| Sunplus Integrated Webcam                                   | 1         | 1.82%   |
| Sunplus HP HD Webcam [Fixed]                                | 1         | 1.82%   |
| Sonix USB2.0 HD UVC WebCam                                  | 1         | 1.82%   |
| Ricoh USB2.0 Camera                                         | 1         | 1.82%   |
| Realtek USB Camera                                          | 1         | 1.82%   |
| Realtek Integrated Webcam HD                                | 1         | 1.82%   |
| Realtek Integrated Webcam                                   | 1         | 1.82%   |
| Realtek HP Truevision HD                                    | 1         | 1.82%   |
| Quanta HP 5M Camera                                         | 1         | 1.82%   |
| Quanta HD User Facing                                       | 1         | 1.82%   |
| Microsoft LifeCam Cinema                                    | 1         | 1.82%   |
| Microdia Sonix USB 2.0 Camera                               | 1         | 1.82%   |
| Microdia Lenovo EasyCamera                                  | 1         | 1.82%   |
| Microdia Laptop_Integrated_Webcam_HD                        | 1         | 1.82%   |
| Microdia Laptop_Integrated_Webcam_1.3M                      | 1         | 1.82%   |
| Microdia Integrated_Webcam_HD                               | 1         | 1.82%   |
| IMC Networks VGA UVC WebCam                                 | 1         | 1.82%   |
| IMC Networks Integrated Camera                              | 1         | 1.82%   |
| Chicony TOSHIBA Web Camera - HD                             | 1         | 1.82%   |
| Chicony thinkpad t430s camera                               | 1         | 1.82%   |
| Chicony Integrated Camera (1280x720@30)                     | 1         | 1.82%   |
| Chicony HP Wide Vision HD Camera                            | 1         | 1.82%   |
| Chicony HP Webcam [2 MP Macro]                              | 1         | 1.82%   |
| Chicony HP TrueVision HD Camera                             | 1         | 1.82%   |
| Chicony HP Integrated Webcam                                | 1         | 1.82%   |
| Chicony HP HD Webcam                                        | 1         | 1.82%   |
| Chicony Asus Integrated 0.3M UVC Webcam                     | 1         | 1.82%   |
| Chicony 2.0M UVC Webcam / CNF7129                           | 1         | 1.82%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 3         | 37.5%   |
| AuthenTec                  | 2         | 25%     |
| Synaptics                  | 1         | 12.5%   |
| STMicroelectronics         | 1         | 12.5%   |
| Shenzhen Goodix Technology | 1         | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 12.5%   |
| Validity Sensors VFS491                           | 1         | 12.5%   |
| Validity Sensors VFS101 Fingerprint Reader        | 1         | 12.5%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 12.5%   |
| STMicroelectronics Fingerprint Reader             | 1         | 12.5%   |
| Shenzhen Goodix  Fingerprint Device               | 1         | 12.5%   |
| AuthenTec AES2501 Fingerprint Sensor              | 1         | 12.5%   |
| AuthenTec AES1600                                 | 1         | 12.5%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Lenovo   | 1         | 50%     |
| Broadcom | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Lenovo Integrated Smart Card Reader                                          | 1         | 50%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 43        | 65.15%  |
| 1     | 18        | 27.27%  |
| 2     | 4         | 6.06%   |
| 3     | 1         | 1.52%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 8         | 25.81%  |
| Fingerprint reader    | 8         | 25.81%  |
| Net/wireless          | 5         | 16.13%  |
| Multimedia controller | 4         | 12.9%   |
| Chipcard              | 2         | 6.45%   |
| Bluetooth             | 2         | 6.45%   |
| Net/ethernet          | 1         | 3.23%   |
| Card reader           | 1         | 3.23%   |

