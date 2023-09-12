Archcraft - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Archcraft.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Archcraft/Desktop/README.md) and [notebooks](/Dist/Archcraft/Notebook/README.md).

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

Total: 77

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | 0KP561                      | Desktop     | [90055b146d](https://linux-hardware.org/?probe=90055b146d) | Sep 06, 2023 |
| Dell          | Vostro 3401                 | Notebook    | [792ea03809](https://linux-hardware.org/?probe=792ea03809) | Aug 19, 2023 |
| Packard Be... | EasyNote TK85               | Notebook    | [da059008eb](https://linux-hardware.org/?probe=da059008eb) | Aug 14, 2023 |
| AXDIA Inte... | WINPAD V10                  | Notebook    | [4dc8c20191](https://linux-hardware.org/?probe=4dc8c20191) | Aug 13, 2023 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [41831db130](https://linux-hardware.org/?probe=41831db130) | Aug 13, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [bbe4e49261](https://linux-hardware.org/?probe=bbe4e49261) | Aug 01, 2023 |
| AXDIA Inte... | WINPAD V10                  | Notebook    | [0e7e712860](https://linux-hardware.org/?probe=0e7e712860) | Jul 24, 2023 |
| ASUSTek       | K30BF_M32BF_A_F_K31BF_6     | Desktop     | [08d5b71848](https://linux-hardware.org/?probe=08d5b71848) | Jul 22, 2023 |
| Dell          | Latitude E5420              | Notebook    | [be15c1e3d1](https://linux-hardware.org/?probe=be15c1e3d1) | Jul 20, 2023 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [2bdf7534ad](https://linux-hardware.org/?probe=2bdf7534ad) | Jul 13, 2023 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [e3ad1f49b1](https://linux-hardware.org/?probe=e3ad1f49b1) | Jul 13, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | Desktop     | [e59862f167](https://linux-hardware.org/?probe=e59862f167) | Jul 05, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [2499e68e07](https://linux-hardware.org/?probe=2499e68e07) | Jul 01, 2023 |
| Lenovo        | Win8 Pro DPK TPG            | Desktop     | [0efc49ca3a](https://linux-hardware.org/?probe=0efc49ca3a) | Jun 28, 2023 |
| Lenovo        | Win8 Pro DPK TPG            | Desktop     | [72514911c8](https://linux-hardware.org/?probe=72514911c8) | Jun 28, 2023 |
| Infinix       | INBook X1 Pro               | Notebook    | [a03717af50](https://linux-hardware.org/?probe=a03717af50) | Jun 26, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [09b5be9c77](https://linux-hardware.org/?probe=09b5be9c77) | Jun 24, 2023 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [558c031517](https://linux-hardware.org/?probe=558c031517) | Jun 16, 2023 |
| HP            | Notebook                    | Notebook    | [1ce7986145](https://linux-hardware.org/?probe=1ce7986145) | Jun 11, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [61c1703e67](https://linux-hardware.org/?probe=61c1703e67) | Jun 10, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [321ad38786](https://linux-hardware.org/?probe=321ad38786) | Jun 10, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [8529d01687](https://linux-hardware.org/?probe=8529d01687) | May 27, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [8301ca5155](https://linux-hardware.org/?probe=8301ca5155) | May 27, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [08eb3979f4](https://linux-hardware.org/?probe=08eb3979f4) | May 19, 2023 |
| Dell          | Latitude 5490               | Notebook    | [2ce70b7a2c](https://linux-hardware.org/?probe=2ce70b7a2c) | May 04, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [eeef579322](https://linux-hardware.org/?probe=eeef579322) | Apr 28, 2023 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [c7f5eaf3f1](https://linux-hardware.org/?probe=c7f5eaf3f1) | Mar 28, 2023 |
| eMachines     | eME730                      | Notebook    | [0e1683ee34](https://linux-hardware.org/?probe=0e1683ee34) | Mar 08, 2023 |
| eMachines     | eME730                      | Notebook    | [db15f88805](https://linux-hardware.org/?probe=db15f88805) | Mar 08, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [f9df27503f](https://linux-hardware.org/?probe=f9df27503f) | Feb 03, 2023 |
| MSI           | Katana GF66 11UE            | Notebook    | [aead8d4d18](https://linux-hardware.org/?probe=aead8d4d18) | Jan 26, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [6f3b4fc131](https://linux-hardware.org/?probe=6f3b4fc131) | Jan 16, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [b33bedc4c2](https://linux-hardware.org/?probe=b33bedc4c2) | Jan 15, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [806da9b386](https://linux-hardware.org/?probe=806da9b386) | Jan 12, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [29e6fcfd32](https://linux-hardware.org/?probe=29e6fcfd32) | Jan 12, 2023 |
| Dell          | Inspiron 7559               | Notebook    | [52cf8ddc0f](https://linux-hardware.org/?probe=52cf8ddc0f) | Dec 22, 2022 |
| ASUSTek       | H110M-E/M.2                 | Desktop     | [82584d7e83](https://linux-hardware.org/?probe=82584d7e83) | Dec 20, 2022 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [d2c04dd7cd](https://linux-hardware.org/?probe=d2c04dd7cd) | Dec 01, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [315d8b6ff7](https://linux-hardware.org/?probe=315d8b6ff7) | Nov 08, 2022 |
| MSI           | GF63 Thin 10SC              | Notebook    | [2b22722ce8](https://linux-hardware.org/?probe=2b22722ce8) | Oct 27, 2022 |
| ASUSTek       | H110M-E/M.2                 | Desktop     | [fb73fb5efc](https://linux-hardware.org/?probe=fb73fb5efc) | Oct 18, 2022 |
| ASUSTek       | H110M-E/M.2                 | Desktop     | [77fd87ca91](https://linux-hardware.org/?probe=77fd87ca91) | Oct 18, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [704da5b600](https://linux-hardware.org/?probe=704da5b600) | Oct 07, 2022 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [98e8df2d3d](https://linux-hardware.org/?probe=98e8df2d3d) | Sep 21, 2022 |
| Dell          | Latitude E6420              | Notebook    | [3ea84baba3](https://linux-hardware.org/?probe=3ea84baba3) | Sep 09, 2022 |
| Dell          | Latitude E6420              | Notebook    | [78fd24b713](https://linux-hardware.org/?probe=78fd24b713) | Sep 09, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [500d050ad6](https://linux-hardware.org/?probe=500d050ad6) | Sep 06, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [01b8531ddf](https://linux-hardware.org/?probe=01b8531ddf) | Sep 04, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [9e4c1bc292](https://linux-hardware.org/?probe=9e4c1bc292) | Sep 04, 2022 |
| HP            | Notebook                    | Notebook    | [b0b97c0ea3](https://linux-hardware.org/?probe=b0b97c0ea3) | Aug 30, 2022 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [8bb62c2062](https://linux-hardware.org/?probe=8bb62c2062) | Aug 24, 2022 |
| ASUSTek       | X441SA                      | Notebook    | [cb26c73037](https://linux-hardware.org/?probe=cb26c73037) | Aug 16, 2022 |
| Acer          | Swift SF113-31              | Notebook    | [1c4298ff33](https://linux-hardware.org/?probe=1c4298ff33) | Aug 08, 2022 |
| Acer          | Swift SF113-31              | Notebook    | [0f1ad8ccf7](https://linux-hardware.org/?probe=0f1ad8ccf7) | Aug 08, 2022 |
| Lenovo        | 3111 SDK0J40705 WIN 3425... | Desktop     | [543fe6b6a7](https://linux-hardware.org/?probe=543fe6b6a7) | Aug 07, 2022 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [9ac134681b](https://linux-hardware.org/?probe=9ac134681b) | Aug 06, 2022 |
| Dell          | Latitude E7250              | Notebook    | [2dd83a16c7](https://linux-hardware.org/?probe=2dd83a16c7) | Aug 01, 2022 |
| Medion        | E3223                       | Convertible | [8d78a4424e](https://linux-hardware.org/?probe=8d78a4424e) | Jul 06, 2022 |
| Acer          | Aspire E5-573               | Notebook    | [01f3150f60](https://linux-hardware.org/?probe=01f3150f60) | Jul 01, 2022 |
| Positivo      | CHT14B                      | Notebook    | [95566d3625](https://linux-hardware.org/?probe=95566d3625) | Jun 05, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [bede15789b](https://linux-hardware.org/?probe=bede15789b) | Jun 02, 2022 |
| Framework     | Laptop                      | Notebook    | [f8790adbf2](https://linux-hardware.org/?probe=f8790adbf2) | May 25, 2022 |
| Standard      | Unknown                     | Notebook    | [74971ae227](https://linux-hardware.org/?probe=74971ae227) | May 04, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [c8c2ede566](https://linux-hardware.org/?probe=c8c2ede566) | Feb 11, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [f3f3b08d89](https://linux-hardware.org/?probe=f3f3b08d89) | Feb 09, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [e975782c15](https://linux-hardware.org/?probe=e975782c15) | Jan 31, 2022 |
| ECS           | G31T-M                      | Desktop     | [3820396d91](https://linux-hardware.org/?probe=3820396d91) | Jan 29, 2022 |
| Lenovo        | ThinkPad T430 2351AK9       | Notebook    | [19f50b09d5](https://linux-hardware.org/?probe=19f50b09d5) | Jan 21, 2022 |
| ASRock        | H97M Pro4                   | Desktop     | [232f2dad91](https://linux-hardware.org/?probe=232f2dad91) | Dec 15, 2021 |
| Apple         | MacBookAir4,1               | Notebook    | [ecc4515014](https://linux-hardware.org/?probe=ecc4515014) | Nov 01, 2021 |
| ASUSTek       | ROG DOMINUS EXTREME         | Desktop     | [0adc8fc04d](https://linux-hardware.org/?probe=0adc8fc04d) | Oct 12, 2021 |
| ASUSTek       | ROG DOMINUS EXTREME         | Desktop     | [b977489e9c](https://linux-hardware.org/?probe=b977489e9c) | Oct 12, 2021 |
| Google        | Kindred                     | Notebook    | [c2631a9488](https://linux-hardware.org/?probe=c2631a9488) | Jul 29, 2021 |
| HP            | Laptop 15q-bu1xx            | Notebook    | [af9f2a95ec](https://linux-hardware.org/?probe=af9f2a95ec) | Jun 28, 2021 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [5e0e7e2b80](https://linux-hardware.org/?probe=5e0e7e2b80) | Jun 25, 2021 |
| HP            | Pavilion g4                 | Notebook    | [6a3471480a](https://linux-hardware.org/?probe=6a3471480a) | May 29, 2021 |
| MSI           | GL65 Leopard 10SFK          | Notebook    | [a9e5bb7556](https://linux-hardware.org/?probe=a9e5bb7556) | May 28, 2021 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Archcraft Rolling | 47        | 82.46%  |
| Archcraft         | 10        | 17.54%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| Archcraft | 57        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.18.16-arch1-1        | 4         | 6.56%   |
| 6.3.9-arch1-1          | 3         | 4.92%   |
| 6.4.4-zen1-1-zen       | 2         | 3.28%   |
| 6.4.1-arch2-1          | 2         | 3.28%   |
| 6.2.13-arch1-1         | 2         | 3.28%   |
| 5.19.13-arch1-1        | 2         | 3.28%   |
| 5.12.7-arch1-1         | 2         | 3.28%   |
| 6.4.7-arch1-1          | 1         | 1.64%   |
| 6.4.4-arch1-1          | 1         | 1.64%   |
| 6.4.3-arch1-1          | 1         | 1.64%   |
| 6.4.12-arch1-1         | 1         | 1.64%   |
| 6.4.10-zen2-1-zen      | 1         | 1.64%   |
| 6.4.10-arch1-1         | 1         | 1.64%   |
| 6.3.8-arch1-1          | 1         | 1.64%   |
| 6.3.6-arch1-1          | 1         | 1.64%   |
| 6.3.4-arch1-1          | 1         | 1.64%   |
| 6.3.10-1-clear         | 1         | 1.64%   |
| 6.2.8-zen1-1-zen       | 1         | 1.64%   |
| 6.2.2-arch1-1          | 1         | 1.64%   |
| 6.2.12-arch1-1         | 1         | 1.64%   |
| 6.1.9-x64v1-xanmod1-1  | 1         | 1.64%   |
| 6.1.7-arch1-1          | 1         | 1.64%   |
| 6.1.4-x64v1-xanmod1-1  | 1         | 1.64%   |
| 6.1.1-arch1-1          | 1         | 1.64%   |
| 6.0.7-arch1-1          | 1         | 1.64%   |
| 6.0.2-arch1-1          | 1         | 1.64%   |
| 6.0.12-arch1-1         | 1         | 1.64%   |
| 6.0.10-x64v1-xanmod1-1 | 1         | 1.64%   |
| 5.19.9-arch1-1         | 1         | 1.64%   |
| 5.19.7-arch1-1         | 1         | 1.64%   |
| 5.19.6-arch1-1         | 1         | 1.64%   |
| 5.19.3-arch1-1         | 1         | 1.64%   |
| 5.18.9-zen1-1-zen      | 1         | 1.64%   |
| 5.18.6-arch1-1         | 1         | 1.64%   |
| 5.18.14-zen1-1-zen     | 1         | 1.64%   |
| 5.18.0-arch1-1         | 1         | 1.64%   |
| 5.17.9-arch1-1         | 1         | 1.64%   |
| 5.17.6-arch1-1         | 1         | 1.64%   |
| 5.17.5-arch1-1         | 1         | 1.64%   |
| 5.16.8-arch1-1         | 1         | 1.64%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.18.16 | 4         | 6.56%   |
| 6.4.4   | 3         | 4.92%   |
| 6.3.9   | 3         | 4.92%   |
| 6.4.10  | 2         | 3.28%   |
| 6.4.1   | 2         | 3.28%   |
| 6.2.13  | 2         | 3.28%   |
| 5.19.13 | 2         | 3.28%   |
| 5.12.7  | 2         | 3.28%   |
| 6.4.7   | 1         | 1.64%   |
| 6.4.3   | 1         | 1.64%   |
| 6.4.12  | 1         | 1.64%   |
| 6.3.8   | 1         | 1.64%   |
| 6.3.6   | 1         | 1.64%   |
| 6.3.4   | 1         | 1.64%   |
| 6.3.10  | 1         | 1.64%   |
| 6.2.8   | 1         | 1.64%   |
| 6.2.2   | 1         | 1.64%   |
| 6.2.12  | 1         | 1.64%   |
| 6.1.9   | 1         | 1.64%   |
| 6.1.7   | 1         | 1.64%   |
| 6.1.4   | 1         | 1.64%   |
| 6.1.1   | 1         | 1.64%   |
| 6.0.7   | 1         | 1.64%   |
| 6.0.2   | 1         | 1.64%   |
| 6.0.12  | 1         | 1.64%   |
| 6.0.10  | 1         | 1.64%   |
| 5.19.9  | 1         | 1.64%   |
| 5.19.7  | 1         | 1.64%   |
| 5.19.6  | 1         | 1.64%   |
| 5.19.3  | 1         | 1.64%   |
| 5.18.9  | 1         | 1.64%   |
| 5.18.6  | 1         | 1.64%   |
| 5.18.14 | 1         | 1.64%   |
| 5.18.0  | 1         | 1.64%   |
| 5.17.9  | 1         | 1.64%   |
| 5.17.6  | 1         | 1.64%   |
| 5.17.5  | 1         | 1.64%   |
| 5.16.8  | 1         | 1.64%   |
| 5.16.7  | 1         | 1.64%   |
| 5.16.4  | 1         | 1.64%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.4     | 9         | 15.25%  |
| 5.18    | 8         | 13.56%  |
| 6.3     | 7         | 11.86%  |
| 5.19    | 6         | 10.17%  |
| 6.2     | 5         | 8.47%   |
| 6.1     | 4         | 6.78%   |
| 6.0     | 4         | 6.78%   |
| 5.16    | 4         | 6.78%   |
| 5.12    | 4         | 6.78%   |
| 5.17    | 3         | 5.08%   |
| 5.15    | 2         | 3.39%   |
| 5.14    | 2         | 3.39%   |
| 5.10    | 1         | 1.69%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 57        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| openbox  | 22        | 38.6%   |
| XFCE     | 14        | 24.56%  |
| bspwm    | 7         | 12.28%  |
| sway     | 2         | 3.51%   |
| KDE5     | 2         | 3.51%   |
| GNOME    | 2         | 3.51%   |
| Unknown  | 2         | 3.51%   |
| qtile    | 1         | 1.75%   |
| LXDE     | 1         | 1.75%   |
| i3       | 1         | 1.75%   |
| Hyprland | 1         | 1.75%   |
| dwm      | 1         | 1.75%   |
| awesome  | 1         | 1.75%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 52        | 91.23%  |
| Wayland | 4         | 7.02%   |
| Unknown | 1         | 1.75%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 39        | 67.24%  |
| Unknown | 10        | 17.24%  |
| LXDM    | 5         | 8.62%   |
| LightDM | 3         | 5.17%   |
| Ly      | 1         | 1.72%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 28        | 49.12%  |
| es_MX | 6         | 10.53%  |
| en_IN | 4         | 7.02%   |
| en_GB | 4         | 7.02%   |
| es_ES | 3         | 5.26%   |
| en_ZA | 2         | 3.51%   |
| en_SG | 2         | 3.51%   |
| tr_TR | 1         | 1.75%   |
| pt_BR | 1         | 1.75%   |
| pl_PL | 1         | 1.75%   |
| it_IT | 1         | 1.75%   |
| fr_FR | 1         | 1.75%   |
| en_PH | 1         | 1.75%   |
| de_DE | 1         | 1.75%   |
| de_AT | 1         | 1.75%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 40        | 70.18%  |
| BIOS | 17        | 29.82%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Ext4  | 43        | 75.44%  |
| Btrfs | 12        | 21.05%  |
| Xfs   | 2         | 3.51%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 43        | 75.44%  |
| Unknown | 9         | 15.79%  |
| MBR     | 5         | 8.77%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 48        | 84.21%  |
| Yes       | 9         | 15.79%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 38        | 66.67%  |
| Yes       | 19        | 33.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 9         | 15.79%  |
| Dell                | 9         | 15.79%  |
| ASUSTek Computer    | 7         | 12.28%  |
| MSI                 | 6         | 10.53%  |
| Lenovo              | 4         | 7.02%   |
| HUAWEI              | 3         | 5.26%   |
| Gigabyte Technology | 3         | 5.26%   |
| ASRock              | 2         | 3.51%   |
| Apple               | 2         | 3.51%   |
| Acer                | 2         | 3.51%   |
| Standard            | 1         | 1.75%   |
| Positivo            | 1         | 1.75%   |
| Medion              | 1         | 1.75%   |
| Infinix             | 1         | 1.75%   |
| Google              | 1         | 1.75%   |
| Framework           | 1         | 1.75%   |
| eMachines           | 1         | 1.75%   |
| ECS                 | 1         | 1.75%   |
| Chuwi               | 1         | 1.75%   |
| AXDIA International | 1         | 1.75%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Positivo CHT14B                      | 1         | 1.75%   |
| MSI MS-7C91                          | 1         | 1.75%   |
| MSI MS-7C51                          | 1         | 1.75%   |
| MSI Katana GF66 11UE                 | 1         | 1.75%   |
| MSI GL65 Leopard 10SFK               | 1         | 1.75%   |
| MSI GF63 Thin 10SC                   | 1         | 1.75%   |
| MSI Alpha 15 B5EEK                   | 1         | 1.75%   |
| Medion E3223                         | 1         | 1.75%   |
| Lenovo ThinkPad T430 2351AK9         | 1         | 1.75%   |
| Lenovo ThinkCentre M710q 10MR0047US  | 1         | 1.75%   |
| Lenovo ThinkCentre Edge72 3484HPU    | 1         | 1.75%   |
| Lenovo MIIX 310-10ICR 80SG           | 1         | 1.75%   |
| Infinix INBook X1 Pro                | 1         | 1.75%   |
| HUAWEI NBD-WXX9                      | 1         | 1.75%   |
| HUAWEI HLYL-WXX9                     | 1         | 1.75%   |
| HUAWEI BOHB-WAX9                     | 1         | 1.75%   |
| HP Stream Laptop 11-ak0xxx           | 1         | 1.75%   |
| HP Spectre x360 Convertible 15-ch0xx | 1         | 1.75%   |
| HP Pavilion Laptop 15-eh0xxx         | 1         | 1.75%   |
| HP Pavilion Laptop 15-cc1xx          | 1         | 1.75%   |
| HP Pavilion g4                       | 1         | 1.75%   |
| HP Notebook                          | 1         | 1.75%   |
| HP Laptop 15q-bu1xx                  | 1         | 1.75%   |
| HP Laptop 15-dy2xxx                  | 1         | 1.75%   |
| HP Laptop 15-dw0xxx                  | 1         | 1.75%   |
| Google Kindred                       | 1         | 1.75%   |
| Gigabyte F2A68HM-DS2                 | 1         | 1.75%   |
| Gigabyte B650 AORUS ELITE AX         | 1         | 1.75%   |
| Gigabyte B550I AORUS PRO AX          | 1         | 1.75%   |
| Framework Laptop                     | 1         | 1.75%   |
| eMachines eME730                     | 1         | 1.75%   |
| ECS G31T-M                           | 1         | 1.75%   |
| Dell XPS 13 9310 2-in-1              | 1         | 1.75%   |
| Dell Vostro 3401                     | 1         | 1.75%   |
| Dell OptiPlex 330                    | 1         | 1.75%   |
| Dell Latitude E7250                  | 1         | 1.75%   |
| Dell Latitude E6420                  | 1         | 1.75%   |
| Dell Latitude E5420                  | 1         | 1.75%   |
| Dell Latitude 5490                   | 1         | 1.75%   |
| Dell Inspiron 7559                   | 1         | 1.75%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Dell Latitude              | 4         | 7.02%   |
| HP Pavilion                | 3         | 5.26%   |
| HP Laptop                  | 3         | 5.26%   |
| Lenovo ThinkCentre         | 2         | 3.51%   |
| Dell Inspiron              | 2         | 3.51%   |
| ASUS ROG                   | 2         | 3.51%   |
| Positivo CHT14B            | 1         | 1.75%   |
| MSI MS-7C91                | 1         | 1.75%   |
| MSI MS-7C51                | 1         | 1.75%   |
| MSI Katana                 | 1         | 1.75%   |
| MSI GL65                   | 1         | 1.75%   |
| MSI GF63                   | 1         | 1.75%   |
| MSI Alpha                  | 1         | 1.75%   |
| Medion E3223               | 1         | 1.75%   |
| Lenovo ThinkPad            | 1         | 1.75%   |
| Lenovo MIIX                | 1         | 1.75%   |
| Infinix INBook             | 1         | 1.75%   |
| HUAWEI NBD-WXX9            | 1         | 1.75%   |
| HUAWEI HLYL-WXX9           | 1         | 1.75%   |
| HUAWEI BOHB-WAX9           | 1         | 1.75%   |
| HP Stream                  | 1         | 1.75%   |
| HP Spectre                 | 1         | 1.75%   |
| HP Notebook                | 1         | 1.75%   |
| Google Kindred             | 1         | 1.75%   |
| Gigabyte F2A68HM-DS2       | 1         | 1.75%   |
| Gigabyte B650              | 1         | 1.75%   |
| Gigabyte B550I             | 1         | 1.75%   |
| Framework Laptop           | 1         | 1.75%   |
| eMachines eME730           | 1         | 1.75%   |
| ECS G31T-M                 | 1         | 1.75%   |
| Dell XPS                   | 1         | 1.75%   |
| Dell Vostro                | 1         | 1.75%   |
| Dell OptiPlex              | 1         | 1.75%   |
| Chuwi GemiBook             | 1         | 1.75%   |
| AXDIA International WINPAD | 1         | 1.75%   |
| ASUS X441SA                | 1         | 1.75%   |
| ASUS PRIME                 | 1         | 1.75%   |
| ASUS P8H61-M               | 1         | 1.75%   |
| ASUS K30BF                 | 1         | 1.75%   |
| ASUS H110M-E               | 1         | 1.75%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 11        | 19.3%   |
| 2020 | 9         | 15.79%  |
| 2014 | 5         | 8.77%   |
| 2018 | 4         | 7.02%   |
| 2017 | 4         | 7.02%   |
| 2016 | 4         | 7.02%   |
| 2012 | 4         | 7.02%   |
| 2011 | 4         | 7.02%   |
| 2019 | 3         | 5.26%   |
| 2015 | 3         | 5.26%   |
| 2022 | 2         | 3.51%   |
| 2007 | 2         | 3.51%   |
| 2010 | 1         | 1.75%   |
| 2008 | 1         | 1.75%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 37        | 64.91%  |
| Desktop     | 16        | 28.07%  |
| Convertible | 3         | 5.26%   |
| Tablet      | 1         | 1.75%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 57        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 56        | 98.25%  |
| Yes  | 1         | 1.75%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 15        | 26.32%  |
| 3.01-4.0    | 10        | 17.54%  |
| 8.01-16.0   | 10        | 17.54%  |
| 32.01-64.0  | 8         | 14.04%  |
| 16.01-24.0  | 7         | 12.28%  |
| 1.01-2.0    | 4         | 7.02%   |
| 24.01-32.0  | 1         | 1.75%   |
| 2.01-3.0    | 1         | 1.75%   |
| 64.01-256.0 | 1         | 1.75%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 18        | 30.51%  |
| 2.01-3.0  | 17        | 28.81%  |
| 3.01-4.0  | 9         | 15.25%  |
| 4.01-8.0  | 8         | 13.56%  |
| 0.51-1.0  | 5         | 8.47%   |
| 8.01-16.0 | 2         | 3.39%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 31        | 54.39%  |
| 2      | 18        | 31.58%  |
| 3      | 3         | 5.26%   |
| 5      | 2         | 3.51%   |
| 4      | 2         | 3.51%   |
| 7      | 1         | 1.75%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 47        | 82.46%  |
| Yes       | 10        | 17.54%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 41        | 71.93%  |
| No        | 16        | 28.07%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 47        | 81.03%  |
| No        | 11        | 18.97%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 39        | 68.42%  |
| No        | 18        | 31.58%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Computers | Percent |
|--------------------|-----------|---------|
| USA                | 10        | 17.54%  |
| Mexico             | 6         | 10.53%  |
| India              | 6         | 10.53%  |
| UK                 | 4         | 7.02%   |
| Spain              | 3         | 5.26%   |
| Brazil             | 3         | 5.26%   |
| Uruguay            | 2         | 3.51%   |
| South Africa       | 2         | 3.51%   |
| Malaysia           | 2         | 3.51%   |
| Germany            | 2         | 3.51%   |
| Vietnam            | 1         | 1.75%   |
| Turkey             | 1         | 1.75%   |
| Thailand           | 1         | 1.75%   |
| Slovakia           | 1         | 1.75%   |
| Russia             | 1         | 1.75%   |
| Poland             | 1         | 1.75%   |
| Philippines        | 1         | 1.75%   |
| Italy              | 1         | 1.75%   |
| Indonesia          | 1         | 1.75%   |
| Hungary            | 1         | 1.75%   |
| France             | 1         | 1.75%   |
| Finland            | 1         | 1.75%   |
| Dominican Republic | 1         | 1.75%   |
| Czechia            | 1         | 1.75%   |
| Belarus            | 1         | 1.75%   |
| Austria            | 1         | 1.75%   |
| Argentina          | 1         | 1.75%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Seremban           | 2         | 3.45%   |
| New Delhi          | 2         | 3.45%   |
| Montevideo         | 2         | 3.45%   |
| Madrid             | 2         | 3.45%   |
| Cape Town          | 2         | 3.45%   |
| Welwyn Garden City | 1         | 1.72%   |
| Vienna             | 1         | 1.72%   |
| Valencia           | 1         | 1.72%   |
| Ulm                | 1         | 1.72%   |
| Torreón           | 1         | 1.72%   |
| Tirunelveli        | 1         | 1.72%   |
| Tábor             | 1         | 1.72%   |
| Stevens Point      | 1         | 1.72%   |
| Sao Paulo          | 1         | 1.72%   |
| Santo Domingo Este | 1         | 1.72%   |
| Santa Rosa         | 1         | 1.72%   |
| Rocca di Papa      | 1         | 1.72%   |
| Paulista           | 1         | 1.72%   |
| Osasco             | 1         | 1.72%   |
| Monterrey          | 1         | 1.72%   |
| Milton Keynes      | 1         | 1.72%   |
| Mazatlán          | 1         | 1.72%   |
| Mar del Plata      | 1         | 1.72%   |
| Mangalore          | 1         | 1.72%   |
| Manchester         | 1         | 1.72%   |
| Malang             | 1         | 1.72%   |
| Loskutova          | 1         | 1.72%   |
| Lorain             | 1         | 1.72%   |
| London             | 1         | 1.72%   |
| Lannion            | 1         | 1.72%   |
| Jorge Negrete      | 1         | 1.72%   |
| Istanbul           | 1         | 1.72%   |
| Ibbenbueren        | 1         | 1.72%   |
| Helsinki           | 1         | 1.72%   |
| Hanoi              | 1         | 1.72%   |
| Guadalajara        | 1         | 1.72%   |
| Gebze              | 1         | 1.72%   |
| Gdansk             | 1         | 1.72%   |
| Frisco             | 1         | 1.72%   |
| Dallas             | 1         | 1.72%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 11        | 13     | 12.64%  |
| Seagate                     | 9         | 14     | 10.34%  |
| Unknown                     | 7         | 14     | 8.05%   |
| Samsung Electronics         | 7         | 7      | 8.05%   |
| Sandisk                     | 5         | 5      | 5.75%   |
| Phison Electronics          | 5         | 5      | 5.75%   |
| Hitachi                     | 5         | 5      | 5.75%   |
| Toshiba                     | 4         | 4      | 4.6%    |
| KIOXIA                      | 3         | 3      | 3.45%   |
| Kingston                    | 3         | 3      | 3.45%   |
| Intel                       | 3         | 6      | 3.45%   |
| Unknown                     | 3         | 3      | 3.45%   |
| SK hynix                    | 2         | 2      | 2.3%    |
| Phison                      | 2         | 2      | 2.3%    |
| Micron/Crucial Technology   | 2         | 2      | 2.3%    |
| Crucial                     | 2         | 2      | 2.3%    |
| Yangtze Memory Technologies | 1         | 1      | 1.15%   |
| ROG                         | 1         | 1      | 1.15%   |
| Patriot                     | 1         | 1      | 1.15%   |
| Netac                       | 1         | 1      | 1.15%   |
| Mushkin                     | 1         | 2      | 1.15%   |
| Kingston Technology Company | 1         | 2      | 1.15%   |
| KingFast                    | 1         | 2      | 1.15%   |
| Initio                      | 1         | 1      | 1.15%   |
| HGST                        | 1         | 1      | 1.15%   |
| Gigabyte Technology         | 1         | 2      | 1.15%   |
| China                       | 1         | 2      | 1.15%   |
| Apple                       | 1         | 1      | 1.15%   |
| Apacer                      | 1         | 1      | 1.15%   |
| A-DATA Technology           | 1         | 2      | 1.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                              | 3         | 3.09%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 3         | 3.09%   |
| Unknown                                             | 3         | 3.09%   |
| Unknown MMC Card  64GB                              | 2         | 2.06%   |
| Seagate ST500LM030-2E717D 500GB                     | 2         | 2.06%   |
| Phison PS5013 E13 NVMe Controller 512GB             | 2         | 2.06%   |
| Phison E16 PCIe4 NVMe Controller 1TB                | 2         | 2.06%   |
| Yangtze Memory YMTC PC005 256GB                     | 1         | 1.03%   |
| WDC WDS500G2B0C-00PXH0 500GB                        | 1         | 1.03%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 1         | 1.03%   |
| WDC WD5000AAKX-75U6AA0 500GB                        | 1         | 1.03%   |
| WDC WD5000AAKX-60U6AA0 500GB                        | 1         | 1.03%   |
| WDC WD5000AAKX-08U6AA0 500GB                        | 1         | 1.03%   |
| WDC WD3200BPVT-22JJ5T0 320GB                        | 1         | 1.03%   |
| WDC WD20 EARX-00PASB0 2TB                           | 1         | 1.03%   |
| WDC WD10SPZX-75Z10T3 1TB                            | 1         | 1.03%   |
| WDC WD10SPZX-24Z10T0 1TB                            | 1         | 1.03%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 1         | 1.03%   |
| WDC WD10EZEX-22RKKA0 1TB                            | 1         | 1.03%   |
| WDC WD10EZEX-21M2NA0 1TB                            | 1         | 1.03%   |
| WDC WD10EARS-00MVWB0 1TB                            | 1         | 1.03%   |
| Unknown SD/MMC/MS PRO 1GB                           | 1         | 1.03%   |
| Unknown SC128  128GB                                | 1         | 1.03%   |
| Unknown MMC Card  16GB                              | 1         | 1.03%   |
| Unknown MMC Card  128GB                             | 1         | 1.03%   |
| Unknown Essentiel B 1TB                             | 1         | 1.03%   |
| Toshiba MQ01ABF050 500GB                            | 1         | 1.03%   |
| Toshiba MQ01ABD100 1TB                              | 1         | 1.03%   |
| Toshiba DT01ACA200 2TB                              | 1         | 1.03%   |
| Toshiba DT01ACA100 1TB                              | 1         | 1.03%   |
| SK hynix NVMe SSD Drive 128GB                       | 1         | 1.03%   |
| SK hynix HFS128G39TND-N210A 128GB SSD               | 1         | 1.03%   |
| Seagate ST6000DM003-2CY186 6TB                      | 1         | 1.03%   |
| Seagate ST3500410AS 500GB                           | 1         | 1.03%   |
| Seagate ST320LM001 HN-M320MBB 320GB                 | 1         | 1.03%   |
| Seagate ST3160815AS 160GB                           | 1         | 1.03%   |
| Seagate ST31500341AS 1TB                            | 1         | 1.03%   |
| Seagate ST2000DM 008-2FR102 2TB                     | 1         | 1.03%   |
| Seagate ST1000LM048-2E7172 1TB                      | 1         | 1.03%   |
| Seagate ST1000DM010-2EP102 1TB                      | 1         | 1.03%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 9         | 11     | 29.03%  |
| Seagate | 9         | 14     | 29.03%  |
| Hitachi | 5         | 5      | 16.13%  |
| Toshiba | 4         | 4      | 12.9%   |
| Unknown | 2         | 3      | 6.45%   |
| Initio  | 1         | 1      | 3.23%   |
| HGST    | 1         | 1      | 3.23%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Unknown             | 3         | 3      | 14.29%  |
| Samsung Electronics | 2         | 2      | 9.52%   |
| Kingston            | 2         | 2      | 9.52%   |
| Intel               | 2         | 2      | 9.52%   |
| WDC                 | 1         | 1      | 4.76%   |
| SK hynix            | 1         | 1      | 4.76%   |
| SanDisk             | 1         | 1      | 4.76%   |
| Phison              | 1         | 1      | 4.76%   |
| Patriot             | 1         | 1      | 4.76%   |
| Netac               | 1         | 1      | 4.76%   |
| Gigabyte Technology | 1         | 2      | 4.76%   |
| Crucial             | 1         | 1      | 4.76%   |
| China               | 1         | 2      | 4.76%   |
| Apple               | 1         | 1      | 4.76%   |
| Apacer              | 1         | 1      | 4.76%   |
| A-DATA Technology   | 1         | 2      | 4.76%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 25        | 33     | 33.33%  |
| HDD     | 23        | 39     | 30.67%  |
| SSD     | 19        | 24     | 25.33%  |
| MMC     | 6         | 11     | 8%      |
| Unknown | 2         | 3      | 2.67%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 35        | 57     | 48.61%  |
| NVMe | 25        | 33     | 34.72%  |
| SAS  | 6         | 9      | 8.33%   |
| MMC  | 6         | 11     | 8.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 27        | 37     | 58.7%   |
| 0.51-1.0   | 15        | 20     | 32.61%  |
| 1.01-2.0   | 3         | 5      | 6.52%   |
| 4.01-10.0  | 1         | 1      | 2.17%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 15        | 26.32%  |
| 251-500        | 13        | 22.81%  |
| 1001-2000      | 8         | 14.04%  |
| 501-1000       | 8         | 14.04%  |
| More than 3000 | 4         | 7.02%   |
| 51-100         | 4         | 7.02%   |
| Unknown        | 3         | 5.26%   |
| 21-50          | 1         | 1.75%   |
| 2001-3000      | 1         | 1.75%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 21-50          | 15        | 25.86%  |
| 1-20           | 13        | 22.41%  |
| 51-100         | 9         | 15.52%  |
| 251-500        | 6         | 10.34%  |
| 101-250        | 6         | 10.34%  |
| 501-1000       | 4         | 6.9%    |
| Unknown        | 3         | 5.17%   |
| More than 3000 | 1         | 1.72%   |
| 1001-2000      | 1         | 1.72%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                          | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC WD5000AAKX-75U6AA0 500GB   | 1         | 1      | 14.29%  |
| WDC WD5000AAKX-60U6AA0 500GB   | 1         | 1      | 14.29%  |
| WDC WD10EARS-00MVWB0 1TB       | 1         | 1      | 14.29%  |
| Seagate ST1000LM048-2E7172 1TB | 1         | 1      | 14.29%  |
| Hitachi HTS547550A9E384 500GB  | 1         | 1      | 14.29%  |
| Hitachi HTS545032A7E380 320GB  | 1         | 1      | 14.29%  |
| HGST HTS545050A7E680 500GB     | 1         | 1      | 14.29%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 3         | 3      | 42.86%  |
| Hitachi | 2         | 2      | 28.57%  |
| Seagate | 1         | 1      | 14.29%  |
| HGST    | 1         | 1      | 14.29%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 3         | 3      | 42.86%  |
| Hitachi | 2         | 2      | 28.57%  |
| Seagate | 1         | 1      | 14.29%  |
| HGST    | 1         | 1      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 6         | 7      | 100%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST3500410AS 500GB | 1         | 2      | 50%     |
| Seagate ST31500341AS 1TB  | 1         | 2      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 4      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 40        | 66     | 61.54%  |
| Detected | 18        | 33     | 27.69%  |
| Malfunc  | 6         | 7      | 9.23%   |
| Failed   | 1         | 4      | 1.54%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 36        | 50%     |
| AMD                         | 9         | 12.5%   |
| SanDisk                     | 5         | 6.94%   |
| Samsung Electronics         | 5         | 6.94%   |
| Phison Electronics          | 5         | 6.94%   |
| Micron/Crucial Technology   | 3         | 4.17%   |
| KIOXIA                      | 3         | 4.17%   |
| Kingston Technology Company | 2         | 2.78%   |
| Yangtze Memory Technologies | 1         | 1.39%   |
| SK hynix                    | 1         | 1.39%   |
| Silicon Motion              | 1         | 1.39%   |
| ASMedia Technology          | 1         | 1.39%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 5         | 6.17%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 4         | 4.94%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 4         | 4.94%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)          | 3         | 3.7%    |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                    | 3         | 3.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller  | 3         | 3.7%    |
| AMD 500 Series Chipset SATA Controller                                        | 3         | 3.7%    |
| Phison PS5013 E13 NVMe Controller                                             | 2         | 2.47%   |
| Phison E16 PCIe4 NVMe Controller                                              | 2         | 2.47%   |
| Intel Volume Management Device NVMe RAID Controller                           | 2         | 2.47%   |
| Intel Tiger Lake SATA AHCI Controller                                         | 2         | 2.47%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 2         | 2.47%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                         | 2         | 2.47%   |
| Intel Comet Lake SATA AHCI Controller                                         | 2         | 2.47%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                        | 2         | 2.47%   |
| Intel 82801G (ICH7 Family) IDE Controller                                     | 2         | 2.47%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 2         | 2.47%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller | 2         | 2.47%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                          | 2         | 2.47%   |
| Yangtze Memory PC005 NVMe SSD                                                 | 1         | 1.23%   |
| SK hynix BC501 NVMe Solid State Drive                                         | 1         | 1.23%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                 | 1         | 1.23%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                            | 1         | 1.23%   |
| SanDisk WD Blue SN550 NVMe SSD                                                | 1         | 1.23%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                     | 1         | 1.23%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD       | 1         | 1.23%   |
| SanDisk PC SN735 NVMe SSD (DRAM-less)                                         | 1         | 1.23%   |
| Samsung NVMe SSD Controller 980                                               | 1         | 1.23%   |
| Phison E18 PCIe4 NVMe Controller                                              | 1         | 1.23%   |
| Phison E12 NVMe Controller                                                    | 1         | 1.23%   |
| Kingston Company Company Non-Volatile memory controller                       | 1         | 1.23%   |
| Kingston Company OM3PDP3 NVMe SSD                                             | 1         | 1.23%   |
| Kingston Company KC3000/Renegade NVMe SSD                                     | 1         | 1.23%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                            | 1         | 1.23%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 1         | 1.23%   |
| Intel Optane SSD 900P Series                                                  | 1         | 1.23%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                             | 1         | 1.23%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                            | 1         | 1.23%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller      | 1         | 1.23%   |
| Intel C620 Series Chipset Family IDE Redirection                              | 1         | 1.23%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 39        | 52.7%   |
| NVMe | 25        | 33.78%  |
| RAID | 6         | 8.11%   |
| IDE  | 4         | 5.41%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 44        | 77.19%  |
| AMD    | 13        | 22.81%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz              | 2         | 3.51%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz              | 2         | 3.51%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz        | 2         | 3.51%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz        | 2         | 3.51%   |
| AMD A10-7800 Radeon R7, 12 Compute Cores 4C+8G | 2         | 3.51%   |
| Intel Xeon W-3175X CPU @ 3.10GHz               | 1         | 1.75%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz       | 1         | 1.75%   |
| Intel Pentium CPU N4200 @ 1.10GHz              | 1         | 1.75%   |
| Intel Core i7-8705G CPU @ 3.10GHz              | 1         | 1.75%   |
| Intel Core i7-8565U CPU @ 1.80GHz              | 1         | 1.75%   |
| Intel Core i7-8550U CPU @ 1.80GHz              | 1         | 1.75%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz             | 1         | 1.75%   |
| Intel Core i7-4510U CPU @ 2.00GHz              | 1         | 1.75%   |
| Intel Core i7-2600K CPU @ 3.40GHz              | 1         | 1.75%   |
| Intel Core i7-10750H CPU @ 2.60GHz             | 1         | 1.75%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz             | 1         | 1.75%   |
| Intel Core i5-7400 CPU @ 3.00GHz               | 1         | 1.75%   |
| Intel Core i5-6500T CPU @ 2.50GHz              | 1         | 1.75%   |
| Intel Core i5-5300U CPU @ 2.30GHz              | 1         | 1.75%   |
| Intel Core i5-4690K CPU @ 3.50GHz              | 1         | 1.75%   |
| Intel Core i5-3320M CPU @ 2.60GHz              | 1         | 1.75%   |
| Intel Core i5-2540M CPU @ 2.60GHz              | 1         | 1.75%   |
| Intel Core i5-2467M CPU @ 1.60GHz              | 1         | 1.75%   |
| Intel Core i5-10300H CPU @ 2.50GHz             | 1         | 1.75%   |
| Intel Core i5-10210U CPU @ 1.60GHz             | 1         | 1.75%   |
| Intel Core i3-5005U CPU @ 2.00GHz              | 1         | 1.75%   |
| Intel Core i3-3220 CPU @ 3.30GHz               | 1         | 1.75%   |
| Intel Core i3-2310M CPU @ 2.10GHz              | 1         | 1.75%   |
| Intel Core i3-10110U CPU @ 2.10GHz             | 1         | 1.75%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz             | 1         | 1.75%   |
| Intel Core i3 CPU M 350 @ 2.27GHz              | 1         | 1.75%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz           | 1         | 1.75%   |
| Intel Core 2 Duo CPU E4600 @ 2.40GHz           | 1         | 1.75%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz           | 1         | 1.75%   |
| Intel Celeron N4020 CPU @ 1.10GHz              | 1         | 1.75%   |
| Intel Celeron J4125 CPU @ 2.00GHz              | 1         | 1.75%   |
| Intel Celeron CPU N3060 @ 1.60GHz              | 1         | 1.75%   |
| Intel Celeron 2957U @ 1.40GHz                  | 1         | 1.75%   |
| Intel Atom CPU Z3735F @ 1.33GHz                | 1         | 1.75%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz        | 1         | 1.75%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 11        | 19.3%   |
| Intel Core i7        | 8         | 14.04%  |
| Other                | 6         | 10.53%  |
| Intel Core i3        | 6         | 10.53%  |
| AMD Ryzen 5          | 5         | 8.77%   |
| Intel Celeron        | 4         | 7.02%   |
| AMD Ryzen 7          | 4         | 7.02%   |
| Intel Core 2 Duo     | 3         | 5.26%   |
| Intel Atom           | 3         | 5.26%   |
| AMD A10              | 2         | 3.51%   |
| Intel Xeon           | 1         | 1.75%   |
| Intel Pentium Silver | 1         | 1.75%   |
| Intel Pentium        | 1         | 1.75%   |
| AMD Ryzen 9          | 1         | 1.75%   |
| AMD A4               | 1         | 1.75%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 22        | 38.6%   |
| 2      | 21        | 36.84%  |
| 8      | 6         | 10.53%  |
| 6      | 6         | 10.53%  |
| 28     | 1         | 1.75%   |
| 12     | 1         | 1.75%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 57        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 40        | 70.18%  |
| 1      | 17        | 29.82%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 57        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 26        | 45.61%  |
| 0xa0652    | 2         | 3.51%   |
| 0x806d1    | 2         | 3.51%   |
| 0x706a8    | 2         | 3.51%   |
| 0x506e3    | 2         | 3.51%   |
| 0x206a7    | 2         | 3.51%   |
| 0x906e9    | 1         | 1.75%   |
| 0x806ec    | 1         | 1.75%   |
| 0x806ea    | 1         | 1.75%   |
| 0x806c1    | 1         | 1.75%   |
| 0x6fd      | 1         | 1.75%   |
| 0x506c9    | 1         | 1.75%   |
| 0x50654    | 1         | 1.75%   |
| 0x406c4    | 1         | 1.75%   |
| 0x40651    | 1         | 1.75%   |
| 0x306d4    | 1         | 1.75%   |
| 0x306c3    | 1         | 1.75%   |
| 0x306a9    | 1         | 1.75%   |
| 0x0a601203 | 1         | 1.75%   |
| 0x0a404102 | 1         | 1.75%   |
| 0x0a201016 | 1         | 1.75%   |
| 0x0a201009 | 1         | 1.75%   |
| 0x08701021 | 1         | 1.75%   |
| 0x08600106 | 1         | 1.75%   |
| 0x08600104 | 1         | 1.75%   |
| 0x06003106 | 1         | 1.75%   |
| 0x03000027 | 1         | 1.75%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 8         | 14.04%  |
| Zen 2         | 4         | 7.02%   |
| TigerLake     | 4         | 7.02%   |
| Silvermont    | 4         | 7.02%   |
| SandyBridge   | 4         | 7.02%   |
| IceLake       | 4         | 7.02%   |
| Zen 3         | 3         | 5.26%   |
| Skylake       | 3         | 5.26%   |
| Haswell       | 3         | 5.26%   |
| Goldmont plus | 3         | 5.26%   |
| Steamroller   | 2         | 3.51%   |
| IvyBridge     | 2         | 3.51%   |
| Core          | 2         | 3.51%   |
| CometLake     | 2         | 3.51%   |
| Broadwell     | 2         | 3.51%   |
| Unknown       | 2         | 3.51%   |
| Zen+          | 1         | 1.75%   |
| Westmere      | 1         | 1.75%   |
| Penryn        | 1         | 1.75%   |
| K10 Llano     | 1         | 1.75%   |
| Goldmont      | 1         | 1.75%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 40        | 56.34%  |
| AMD    | 16        | 22.54%  |
| Nvidia | 15        | 21.13%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 3         | 3.95%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 3.95%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 3.95%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3         | 3.95%   |
| AMD Renoir                                                                               | 3         | 3.95%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 3         | 3.95%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 2.63%   |
| Nvidia GM108M [GeForce MX130]                                                            | 2         | 2.63%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 2.63%   |
| Intel HD Graphics 630                                                                    | 2         | 2.63%   |
| Intel HD Graphics 5500                                                                   | 2         | 2.63%   |
| Intel HD Graphics 530                                                                    | 2         | 2.63%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 2.63%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 2.63%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 2.63%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 2.63%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 2         | 2.63%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 2         | 2.63%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 1         | 1.32%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                                    | 1         | 1.32%   |
| Nvidia TU102 [TITAN RTX]                                                                 | 1         | 1.32%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 1.32%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 1.32%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 1.32%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 1.32%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 1         | 1.32%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 1.32%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                                           | 1         | 1.32%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 1         | 1.32%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1         | 1.32%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 1.32%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 1         | 1.32%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.32%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.32%   |
| Intel Iris Plus Graphics G7                                                              | 1         | 1.32%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 1         | 1.32%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 1         | 1.32%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.32%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 1.32%   |
| Intel Apollo Lake [HD Graphics 505]                                                      | 1         | 1.32%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 27        | 47.37%  |
| Intel + Nvidia | 9         | 15.79%  |
| 1 x AMD        | 7         | 12.28%  |
| 2 x AMD        | 4         | 7.02%   |
| 1 x Nvidia     | 4         | 7.02%   |
| Intel + AMD    | 3         | 5.26%   |
| AMD + Nvidia   | 2         | 3.51%   |
| 2 x Intel      | 1         | 1.75%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 45        | 77.59%  |
| Proprietary | 13        | 22.41%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 40        | 68.97%  |
| 7.01-8.0   | 4         | 6.9%    |
| 0.01-0.5   | 4         | 6.9%    |
| 5.01-6.0   | 2         | 3.45%   |
| 3.01-4.0   | 2         | 3.45%   |
| 16.01-24.0 | 2         | 3.45%   |
| 0.51-1.0   | 2         | 3.45%   |
| 1.01-2.0   | 1         | 1.72%   |
| 8.01-16.0  | 1         | 1.72%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Chimei Innolux       | 10        | 15.87%  |
| BOE                  | 8         | 12.7%   |
| LG Display           | 6         | 9.52%   |
| AU Optronics         | 6         | 9.52%   |
| Samsung Electronics  | 5         | 7.94%   |
| Dell                 | 5         | 7.94%   |
| PANDA                | 3         | 4.76%   |
| Goldstar             | 3         | 4.76%   |
| Ancor Communications | 3         | 4.76%   |
| Lenovo               | 2         | 3.17%   |
| ASUSTek Computer     | 2         | 3.17%   |
| Apple                | 2         | 3.17%   |
| Toshiba              | 1         | 1.59%   |
| Sharp                | 1         | 1.59%   |
| HJC                  | 1         | 1.59%   |
| Hewlett-Packard      | 1         | 1.59%   |
| BenQ                 | 1         | 1.59%   |
| AGO                  | 1         | 1.59%   |
| Acer                 | 1         | 1.59%   |
| Unknown              | 1         | 1.59%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| PANDA LM133LF5L01 NCP0020 1920x1080 294x165mm 13.3-inch              | 2         | 3.08%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch          | 2         | 3.08%   |
| LG Display LCD Monitor LGD02EB 1366x768 309x174mm 14.0-inch          | 2         | 3.08%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                | 2         | 3.08%   |
| Toshiba TV TSB0206 1920x1080                                         | 1         | 1.54%   |
| Sharp LCD Monitor SHP14F8 3840x2400 288x180mm 13.4-inch              | 1         | 1.54%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch    | 1         | 1.54%   |
| Samsung Electronics LCD Monitor SEC335A 1366x768 309x174mm 14.0-inch | 1         | 1.54%   |
| Samsung Electronics LCD Monitor SEC3046 1366x768 344x193mm 15.5-inch | 1         | 1.54%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch   | 1         | 1.54%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 1         | 1.54%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 1         | 1.54%   |
| LG Display LCD Monitor LGD04B9 1920x1080 344x194mm 15.5-inch         | 1         | 1.54%   |
| LG Display LCD Monitor LGD04B1 1366x768 310x174mm 14.0-inch          | 1         | 1.54%   |
| Lenovo P24h-10 LEN61AE 2560x1440 527x296mm 23.8-inch                 | 1         | 1.54%   |
| Lenovo LEN T2054pC LEN60D9 1440x900 419x262mm 19.5-inch              | 1         | 1.54%   |
| HJC LCD Monitor HJC003D 1920x1080 309x174mm 14.0-inch                | 1         | 1.54%   |
| Hewlett-Packard V320 HPN3363 1920x1080 698x393mm 31.5-inch           | 1         | 1.54%   |
| Goldstar L1742 GSM449C 1280x1024 338x270mm 17.0-inch                 | 1         | 1.54%   |
| Goldstar HDR WFHD GSM5BB9 2560x1080 798x334mm 34.1-inch              | 1         | 1.54%   |
| Goldstar FULL HD GSM5BFB 1920x1080 480x270mm 21.7-inch               | 1         | 1.54%   |
| Dell SE2417HG DELD08E 1920x1080 521x293mm 23.5-inch                  | 1         | 1.54%   |
| Dell SE2417HG DELD08D 1920x1080 521x293mm 23.5-inch                  | 1         | 1.54%   |
| Dell S2421NX DEL41FB 1920x1080 527x296mm 23.8-inch                   | 1         | 1.54%   |
| Dell S2240T DELA094 1920x1080 477x268mm 21.5-inch                    | 1         | 1.54%   |
| Dell E198WFP DELF005 1440x900 408x255mm 18.9-inch                    | 1         | 1.54%   |
| Dell AW2518HF DELA101 1920x1080 540x300mm 24.3-inch                  | 1         | 1.54%   |
| Chimei Innolux LCD Monitor CMN1604 1920x1080 355x199mm 16.0-inch     | 1         | 1.54%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 1         | 1.54%   |
| Chimei Innolux LCD Monitor CMN15E3 1920x1080 344x193mm 15.5-inch     | 1         | 1.54%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch      | 1         | 1.54%   |
| Chimei Innolux LCD Monitor CMN1541 1366x768 344x193mm 15.5-inch      | 1         | 1.54%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 1         | 1.54%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 1         | 1.54%   |
| Chimei Innolux LCD Monitor CMN1404 1920x1080 309x173mm 13.9-inch     | 1         | 1.54%   |
| Chimei Innolux LCD Monitor CMN1147 1366x768 256x144mm 11.6-inch      | 1         | 1.54%   |
| Chimei Innolux HJ140BB-02A CMN8C03 2160x1440 296x197mm 14.0-inch     | 1         | 1.54%   |
| BOE LCD Monitor BOE0974 2560x1440 344x194mm 15.5-inch                | 1         | 1.54%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                | 1         | 1.54%   |
| BOE LCD Monitor BOE07FF 1920x1080 344x194mm 15.5-inch                | 1         | 1.54%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Computers | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 27        | 43.55%  |
| 1366x768 (WXGA)  | 14        | 22.58%  |
| 2560x1440 (QHD)  | 4         | 6.45%   |
| 3840x2160 (4K)   | 3         | 4.84%   |
| 2256x1504        | 2         | 3.23%   |
| 1440x900 (WXGA+) | 2         | 3.23%   |
| 3840x2400        | 1         | 1.61%   |
| 3840x1080        | 1         | 1.61%   |
| 3440x1440        | 1         | 1.61%   |
| 3200x1080        | 1         | 1.61%   |
| 2560x1080        | 1         | 1.61%   |
| 2160x1440        | 1         | 1.61%   |
| 1600x900 (HD+)   | 1         | 1.61%   |
| 1280x800 (WXGA)  | 1         | 1.61%   |
| 1280x1024 (SXGA) | 1         | 1.61%   |
| Unknown          | 1         | 1.61%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 18        | 28.13%  |
| 13      | 10        | 15.63%  |
| 14      | 8         | 12.5%   |
| 24      | 5         | 7.81%   |
| 21      | 3         | 4.69%   |
| 34      | 2         | 3.13%   |
| 27      | 2         | 3.13%   |
| 23      | 2         | 3.13%   |
| 19      | 2         | 3.13%   |
| 12      | 2         | 3.13%   |
| 11      | 2         | 3.13%   |
| 74      | 1         | 1.56%   |
| 64      | 1         | 1.56%   |
| 48      | 1         | 1.56%   |
| 32      | 1         | 1.56%   |
| 31      | 1         | 1.56%   |
| 17      | 1         | 1.56%   |
| 16      | 1         | 1.56%   |
| Unknown | 1         | 1.56%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 29        | 46.03%  |
| 201-300     | 11        | 17.46%  |
| 501-600     | 8         | 12.7%   |
| 401-500     | 5         | 7.94%   |
| 701-800     | 3         | 4.76%   |
| 601-700     | 2         | 3.17%   |
| 1001-1500   | 2         | 3.17%   |
| 351-400     | 1         | 1.59%   |
| 1501-2000   | 1         | 1.59%   |
| Unknown     | 1         | 1.59%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 45        | 76.27%  |
| 16/10   | 5         | 8.47%   |
| 3/2     | 3         | 5.08%   |
| 21/9    | 2         | 3.39%   |
| 5/4     | 1         | 1.69%   |
| 4/3     | 1         | 1.69%   |
| 32/9    | 1         | 1.69%   |
| Unknown | 1         | 1.69%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 20        | 31.25%  |
| 81-90          | 14        | 21.88%  |
| 201-250        | 7         | 10.94%  |
| 71-80          | 4         | 6.25%   |
| 351-500        | 4         | 6.25%   |
| 151-200        | 3         | 4.69%   |
| More than 1000 | 2         | 3.13%   |
| 51-60          | 2         | 3.13%   |
| 301-350        | 2         | 3.13%   |
| 251-300        | 2         | 3.13%   |
| 61-70          | 1         | 1.56%   |
| 141-150        | 1         | 1.56%   |
| 501-1000       | 1         | 1.56%   |
| Unknown        | 1         | 1.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 22        | 34.92%  |
| 101-120       | 16        | 25.4%   |
| 51-100        | 14        | 22.22%  |
| 161-240       | 7         | 11.11%  |
| More than 240 | 2         | 3.17%   |
| 1-50          | 1         | 1.59%   |
| Unknown       | 1         | 1.59%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 47        | 82.46%  |
| 2     | 9         | 15.79%  |
| 3     | 1         | 1.75%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 34        | 42.5%   |
| Intel                    | 25        | 31.25%  |
| Qualcomm Atheros         | 5         | 6.25%   |
| Ralink Technology        | 4         | 5%      |
| MediaTek                 | 3         | 3.75%   |
| Broadcom                 | 3         | 3.75%   |
| Broadcom Limited         | 2         | 2.5%    |
| TP-Link                  | 1         | 1.25%   |
| OPPO Electronics         | 1         | 1.25%   |
| Marvell Technology Group | 1         | 1.25%   |
| Aquantia                 | 1         | 1.25%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 18        | 18.95%  |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 5.26%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 5.26%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 4.21%   |
| Ralink MT7601U Wireless Adapter                                   | 3         | 3.16%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 2.11%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2         | 2.11%   |
| Realtek 802.11ac NIC                                              | 2         | 2.11%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 2.11%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 2.11%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 2         | 2.11%   |
| Intel Wireless 8265 / 8275                                        | 2         | 2.11%   |
| Intel Wireless 7265                                               | 2         | 2.11%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 2.11%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 2.11%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 2.11%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 2.11%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 2.11%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 2.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 2.11%   |
| TP-Link 802.11ac WLAN Adapter                                     | 1         | 1.05%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 1.05%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 1         | 1.05%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 1.05%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 1.05%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.05%   |
| Ralink RT5572 Wireless Adapter                                    | 1         | 1.05%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 1.05%   |
| OPPO SM8350-MTP _SN:E34C72C4                                      | 1         | 1.05%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 1         | 1.05%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 1.05%   |
| Intel Wireless-AC 9260                                            | 1         | 1.05%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1         | 1.05%   |
| Intel Wi-Fi 6 AX200                                               | 1         | 1.05%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 1         | 1.05%   |
| Intel I211 Gigabit Network Connection                             | 1         | 1.05%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 1         | 1.05%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.05%   |
| Intel Ethernet Connection (3) I219-LM                             | 1         | 1.05%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.05%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 22        | 44%     |
| Realtek Semiconductor | 12        | 24%     |
| Qualcomm Atheros      | 5         | 10%     |
| Ralink Technology     | 4         | 8%      |
| MediaTek              | 3         | 6%      |
| Broadcom              | 3         | 6%      |
| TP-Link               | 1         | 2%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 4         | 7.84%   |
| Ralink MT7601U Wireless Adapter                               | 3         | 5.88%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 2         | 3.92%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter      | 2         | 3.92%   |
| Realtek 802.11ac NIC                                          | 2         | 3.92%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 2         | 3.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 2         | 3.92%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 2         | 3.92%   |
| Intel Wireless 8265 / 8275                                    | 2         | 3.92%   |
| Intel Wireless 7265                                           | 2         | 3.92%   |
| Intel Wi-Fi 6 AX201                                           | 2         | 3.92%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 2         | 3.92%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 2         | 3.92%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 2         | 3.92%   |
| Intel Comet Lake PCH CNVi WiFi                                | 2         | 3.92%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 2         | 3.92%   |
| TP-Link 802.11ac WLAN Adapter                                 | 1         | 1.96%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 1         | 1.96%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                    | 1         | 1.96%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 1         | 1.96%   |
| Ralink RT5572 Wireless Adapter                                | 1         | 1.96%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 1         | 1.96%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 1         | 1.96%   |
| Intel Wireless-AC 9260                                        | 1         | 1.96%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 1         | 1.96%   |
| Intel Wi-Fi 6 AX200                                           | 1         | 1.96%   |
| Intel Ice Lake-LP PCH CNVi WiFi                               | 1         | 1.96%   |
| Intel Gemini Lake PCH CNVi WiFi                               | 1         | 1.96%   |
| Intel Centrino Ultimate-N 6300                                | 1         | 1.96%   |
| Broadcom BCM43225 802.11b/g/n                                 | 1         | 1.96%   |
| Broadcom BCM43224 802.11a/b/g/n                               | 1         | 1.96%   |
| Broadcom BCM4321 802.11a/b/g/n                                | 1         | 1.96%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 27        | 65.85%  |
| Intel                    | 8         | 19.51%  |
| Broadcom Limited         | 2         | 4.88%   |
| OPPO Electronics         | 1         | 2.44%   |
| Marvell Technology Group | 1         | 2.44%   |
| Broadcom                 | 1         | 2.44%   |
| Aquantia                 | 1         | 2.44%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 18        | 40.91%  |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 11.36%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 11.36%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 4.55%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 2.27%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 2.27%   |
| OPPO SM8350-MTP _SN:E34C72C4                                      | 1         | 2.27%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 2.27%   |
| Intel I211 Gigabit Network Connection                             | 1         | 2.27%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 2.27%   |
| Intel Ethernet Connection (3) I219-LM                             | 1         | 2.27%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 2.27%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 2.27%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 2.27%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 2.27%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1         | 2.27%   |
| Broadcom Limited NetLink BCM5787 Gigabit Ethernet PCI Express     | 1         | 2.27%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1         | 2.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 47        | 54.02%  |
| Ethernet | 40        | 45.98%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 38        | 66.67%  |
| Ethernet | 19        | 33.33%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 28        | 49.12%  |
| 1     | 25        | 43.86%  |
| 0     | 3         | 5.26%   |
| 3     | 1         | 1.75%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 36        | 63.16%  |
| Yes  | 21        | 36.84%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 19        | 48.72%  |
| Realtek Semiconductor           | 5         | 12.82%  |
| Qualcomm Atheros Communications | 3         | 7.69%   |
| MediaTek                        | 2         | 5.13%   |
| IMC Networks                    | 2         | 5.13%   |
| Cambridge Silicon Radio         | 2         | 5.13%   |
| Apple                           | 2         | 5.13%   |
| Realtek                         | 1         | 2.56%   |
| Lite-On Technology              | 1         | 2.56%   |
| Foxconn / Hon Hai               | 1         | 2.56%   |
| Broadcom                        | 1         | 2.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 8         | 20.51%  |
| Realtek Bluetooth Radio                             | 4         | 10.26%  |
| Intel Bluetooth wireless interface                  | 4         | 10.26%  |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 5.13%   |
| MediaTek Wireless_Device                            | 2         | 5.13%   |
| Intel Bluetooth Device                              | 2         | 5.13%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 5.13%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 5.13%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 2.56%   |
| Realtek 802.11ac WLAN Adapter                       | 1         | 2.56%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 2.56%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 2.56%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 2.56%   |
| Intel AX210 Bluetooth                               | 1         | 2.56%   |
| Intel AX200 Bluetooth                               | 1         | 2.56%   |
| IMC Networks Bluetooth Radio                        | 1         | 2.56%   |
| IMC Networks Bluetooth Device                       | 1         | 2.56%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 2.56%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 2.56%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 2.56%   |
| Apple Bluetooth HCI                                 | 1         | 2.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 41        | 53.95%  |
| AMD                 | 16        | 21.05%  |
| Nvidia              | 10        | 13.16%  |
| Logitech            | 3         | 3.95%   |
| C-Media Electronics | 2         | 2.63%   |
| Texas Instruments   | 1         | 1.32%   |
| Oculus VR           | 1         | 1.32%   |
| Kingston Technology | 1         | 1.32%   |
| JMTek               | 1         | 1.32%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 6         | 6.52%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 5         | 5.43%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 4         | 4.35%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 4.35%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 3         | 3.26%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 3.26%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 3         | 3.26%   |
| AMD FCH Azalia Controller                                                                         | 3         | 3.26%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 3         | 3.26%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 2.17%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 2.17%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 2         | 2.17%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 2.17%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 2.17%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 2.17%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 2.17%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 2.17%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 2.17%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 2.17%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 2.17%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 2.17%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 2.17%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 2         | 2.17%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 2         | 2.17%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 1.09%   |
| Oculus VR Rift CV1 Audio                                                                          | 1         | 1.09%   |
| Nvidia TU102 High Definition Audio Controller                                                     | 1         | 1.09%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 1.09%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 1.09%   |
| Nvidia Audio device                                                                               | 1         | 1.09%   |
| Logitech Logitech USB Microphone                                                                  | 1         | 1.09%   |
| Logitech H390 headset with microphone                                                             | 1         | 1.09%   |
| Logitech G432 Gaming Headset                                                                      | 1         | 1.09%   |
| Kingston Technology HyperX QuadCast                                                               | 1         | 1.09%   |
| JMTek USB PnP Audio Device                                                                        | 1         | 1.09%   |
| Intel Lewisburg MROM 0                                                                            | 1         | 1.09%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 1.09%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 1.09%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 1.09%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.09%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 12        | 21.05%  |
| SK hynix            | 9         | 15.79%  |
| Kingston            | 8         | 14.04%  |
| Micron Technology   | 7         | 12.28%  |
| Unknown             | 5         | 8.77%   |
| Crucial             | 5         | 8.77%   |
| Unknown (ABCD)      | 2         | 3.51%   |
| Corsair             | 2         | 3.51%   |
| A-DATA Technology   | 2         | 3.51%   |
| Team                | 1         | 1.75%   |
| Nanya Technology    | 1         | 1.75%   |
| G.Skill             | 1         | 1.75%   |
| ChangXin Memory     | 1         | 1.75%   |
| Unknown             | 1         | 1.75%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 2         | 3.23%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 3.23%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 3.23%   |
| Kingston RAM KF2933C17S4/16G 16GB SODIMM DDR4 2933MT/s           | 2         | 3.23%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                        | 1         | 1.61%   |
| Unknown RAM Module 4GB Row Of Chips LPDDR4 4267MT/s              | 1         | 1.61%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 1         | 1.61%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 1.61%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 1         | 1.61%   |
| Unknown RAM Module 1GB DIMM SDRAM                                | 1         | 1.61%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s               | 1         | 1.61%   |
| SK hynix RAM HYMP512U64CP8-S6 1GB DIMM DDR2 800MT/s              | 1         | 1.61%   |
| SK hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s            | 1         | 1.61%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.61%   |
| SK hynix RAM HMT451S6CFR6A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 1.61%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.61%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 1         | 1.61%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.61%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB Row Of Chips DDR4 2667MT/s     | 1         | 1.61%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.61%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.61%   |
| Samsung RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 1.61%   |
| Samsung RAM M474A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 1         | 1.61%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 1         | 1.61%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 1.61%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.61%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.61%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.61%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.61%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.61%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 1         | 1.61%   |
| Samsung RAM K4A8G165WC-BCTD 4GB Row Of Chips DDR4 2667MT/s       | 1         | 1.61%   |
| Nanya RAM Module 1GB SODIMM DDR2 667MT/s                         | 1         | 1.61%   |
| Micron RAM MTC4C10163S1SC48BA1 8GB SODIMM DDR5 4800MT/s          | 1         | 1.61%   |
| Micron RAM Module 2GB SODIMM DDR3 1866MT/s                       | 1         | 1.61%   |
| Micron RAM K4A8G165WB-BCRC 8GB Row Of Chips LPDDR4 3333MT/s      | 1         | 1.61%   |
| Micron RAM F6451U64F9333G 4GB DIMM DDR3 1333MT/s                 | 1         | 1.61%   |
| Micron RAM 8KTF25664HZ-1G6M1 2GB SODIMM DDR3 1600MT/s            | 1         | 1.61%   |
| Micron RAM 4ATF51264HZ-3G2R1 4GB SODIMM DDR4 3200MT/s            | 1         | 1.61%   |
| Micron RAM 16ATF2G64HZ-2G3E1 16384MB SODIMM DDR4 2667MT/s        | 1         | 1.61%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 23        | 46%     |
| DDR3   | 17        | 34%     |
| LPDDR4 | 5         | 10%     |
| DDR5   | 2         | 4%      |
| DDR2   | 2         | 4%      |
| SDRAM  | 1         | 2%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 31        | 63.27%  |
| DIMM         | 13        | 26.53%  |
| Row Of Chips | 5         | 10.2%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 22        | 40%     |
| 4096  | 12        | 21.82%  |
| 16384 | 8         | 14.55%  |
| 2048  | 8         | 14.55%  |
| 1024  | 4         | 7.27%   |
| 32768 | 1         | 1.82%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 12        | 21.43%  |
| 2667    | 10        | 17.86%  |
| 3200    | 7         | 12.5%   |
| 1333    | 5         | 8.93%   |
| 2133    | 3         | 5.36%   |
| 4800    | 2         | 3.57%   |
| 3733    | 2         | 3.57%   |
| 2933    | 2         | 3.57%   |
| 2400    | 2         | 3.57%   |
| 49926   | 1         | 1.79%   |
| 4267    | 1         | 1.79%   |
| 3800    | 1         | 1.79%   |
| 3600    | 1         | 1.79%   |
| 3333    | 1         | 1.79%   |
| 1866    | 1         | 1.79%   |
| 1334    | 1         | 1.79%   |
| 1067    | 1         | 1.79%   |
| 800     | 1         | 1.79%   |
| 667     | 1         | 1.79%   |
| Unknown | 1         | 1.79%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| HP DeskJet 4720 series | 1         | 100%    |

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
| Chicony Electronics                    | 7         | 20.59%  |
| Microdia                               | 5         | 14.71%  |
| Cheng Uei Precision Industry (Foxlink) | 3         | 8.82%   |
| Bison Electronics                      | 3         | 8.82%   |
| Realtek Semiconductor                  | 2         | 5.88%   |
| Quanta                                 | 2         | 5.88%   |
| IMC Networks                           | 2         | 5.88%   |
| Apple                                  | 2         | 5.88%   |
| Alcor Micro                            | 2         | 5.88%   |
| Suyin                                  | 1         | 2.94%   |
| Sunplus Innovation Technology          | 1         | 2.94%   |
| Ricoh                                  | 1         | 2.94%   |
| Luxvisions Innotech Limited            | 1         | 2.94%   |
| Logitech                               | 1         | 2.94%   |
| Generalplus Technology                 | 1         | 2.94%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                    | 4         | 11.76%  |
| Quanta ov9734_techfront_camera                                   | 2         | 5.88%   |
| Bison HD Webcam                                                  | 2         | 5.88%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)      | 1         | 2.94%   |
| Sunplus Integrated_Webcam_HD                                     | 1         | 2.94%   |
| Ricoh Laptop_Integrated_Webcam_FHD                               | 1         | 2.94%   |
| Realtek HP Webcam                                                | 1         | 2.94%   |
| Realtek HD Webcam - Realtek                                      | 1         | 2.94%   |
| Microdia Webcam Vitade AF                                        | 1         | 2.94%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera              | 1         | 2.94%   |
| Logitech HD Pro Webcam C920                                      | 1         | 2.94%   |
| IMC Networks HP TrueVision HD Camera                             | 1         | 2.94%   |
| IMC Networks HD Camera                                           | 1         | 2.94%   |
| Generalplus WEB CAM                                              | 1         | 2.94%   |
| Chicony USB2.0 VGA UVC WebCam                                    | 1         | 2.94%   |
| Chicony Integrated IR Camera                                     | 1         | 2.94%   |
| Chicony Integrated HD WebCam                                     | 1         | 2.94%   |
| Chicony HP Wide Vision HD Camera                                 | 1         | 2.94%   |
| Chicony HP Truevision HD                                         | 1         | 2.94%   |
| Chicony HD Webcam                                                | 1         | 2.94%   |
| Chicony HD User Facing                                           | 1         | 2.94%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera  | 1         | 2.94%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision FHD Camera | 1         | 2.94%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera   | 1         | 2.94%   |
| Bison Integrated Camera                                          | 1         | 2.94%   |
| Apple FaceTime Camera                                            | 1         | 2.94%   |
| Apple Built-in iSight [Micron]                                   | 1         | 2.94%   |
| Alcor Micro USB 2.0 PC cam                                       | 1         | 2.94%   |
| Alcor Micro USB 2.0 Camera                                       | 1         | 2.94%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 2         | 40%     |
| Elan Microelectronics      | 2         | 40%     |
| LighTuning Technology      | 1         | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Elan ELAN:ARM-M4                            | 2         | 40%     |
| Shenzhen Goodix  Fingerprint Device         | 1         | 20%     |
| Shenzhen Goodix Fingerprint Reader          | 1         | 20%     |
| LighTuning EgisTec Touch Fingerprint Sensor | 1         | 20%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 43        | 75.44%  |
| 1     | 11        | 19.3%   |
| 2     | 3         | 5.26%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 5         | 31.25%  |
| Graphics card         | 4         | 25%     |
| Storage               | 2         | 12.5%   |
| Net/wireless          | 2         | 12.5%   |
| Unassigned class      | 1         | 6.25%   |
| Multimedia controller | 1         | 6.25%   |
| Chipcard              | 1         | 6.25%   |

