MX 21 - Tested Hardware & Statistics
------------------------------------

A project to collect tested hardware configurations for MX 21.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/MX_21/Desktop/README.md) and [notebooks](/Dist/MX_21/Notebook/README.md).

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

Total: 95

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | Latitude 3190               | Notebook    | [e43c62a67a](https://linux-hardware.org/?probe=e43c62a67a) | May 30, 2022 |
| ASUSTek       | K55A                        | Notebook    | [0eb5e9ea50](https://linux-hardware.org/?probe=0eb5e9ea50) | May 29, 2022 |
| AZW           | SER                         | Mini pc     | [9da3c6ca34](https://linux-hardware.org/?probe=9da3c6ca34) | May 18, 2022 |
| Sony          | VPCSB1V9R                   | Notebook    | [e3b15e462d](https://linux-hardware.org/?probe=e3b15e462d) | May 16, 2022 |
| Sony          | VPCSB1V9R                   | Notebook    | [9dfafea956](https://linux-hardware.org/?probe=9dfafea956) | May 16, 2022 |
| Dell          | Latitude 3190               | Notebook    | [e80556f7d6](https://linux-hardware.org/?probe=e80556f7d6) | May 16, 2022 |
| Medion        | E14304                      | Notebook    | [8d1a922b7b](https://linux-hardware.org/?probe=8d1a922b7b) | May 15, 2022 |
| HP            | Stream Laptop 14-cb0XX      | Notebook    | [3b0408920d](https://linux-hardware.org/?probe=3b0408920d) | May 13, 2022 |
| ASUSTek       | SABERTOOTH X99              | Desktop     | [b627953ad4](https://linux-hardware.org/?probe=b627953ad4) | May 11, 2022 |
| Acer          | Aspire A515-56              | Notebook    | [b728fa5844](https://linux-hardware.org/?probe=b728fa5844) | May 01, 2022 |
| Intel         | V1.3                        | Desktop     | [a01993f2fa](https://linux-hardware.org/?probe=a01993f2fa) | Apr 30, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [04b51fe1cf](https://linux-hardware.org/?probe=04b51fe1cf) | Apr 25, 2022 |
| Alienware     | m15 R7                      | Notebook    | [77727a1731](https://linux-hardware.org/?probe=77727a1731) | Apr 24, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [4e8b5f940a](https://linux-hardware.org/?probe=4e8b5f940a) | Apr 23, 2022 |
| ASUSTek       | SABERTOOTH X99              | Desktop     | [51cc264c62](https://linux-hardware.org/?probe=51cc264c62) | Apr 22, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [77a6f92da0](https://linux-hardware.org/?probe=77a6f92da0) | Apr 22, 2022 |
| Gigabyte      | B550M S2H                   | Desktop     | [208972e3b5](https://linux-hardware.org/?probe=208972e3b5) | Apr 19, 2022 |
| ASRock        | N3150M                      | Desktop     | [0ee71f6582](https://linux-hardware.org/?probe=0ee71f6582) | Apr 19, 2022 |
| Gigabyte      | B550M S2H                   | Desktop     | [1127f26185](https://linux-hardware.org/?probe=1127f26185) | Apr 17, 2022 |
| Sun Micros... | Sun Ultra 40 M2 Workstat... | Server      | [7cc89d3cba](https://linux-hardware.org/?probe=7cc89d3cba) | Apr 14, 2022 |
| Sun Micros... | Sun Ultra 40 M2 Workstat... | Server      | [5cd6adf199](https://linux-hardware.org/?probe=5cd6adf199) | Apr 14, 2022 |
| Gigabyte      | G5 KC                       | Notebook    | [fc21d0150f](https://linux-hardware.org/?probe=fc21d0150f) | Apr 10, 2022 |
| Acer          | Aspire A515-56              | Notebook    | [db6408f394](https://linux-hardware.org/?probe=db6408f394) | Apr 07, 2022 |
| MSI           | GV62 8RD                    | Notebook    | [2e43728adb](https://linux-hardware.org/?probe=2e43728adb) | Apr 06, 2022 |
| Microsoft     | Surface Pro 7               | Tablet      | [084e2350e9](https://linux-hardware.org/?probe=084e2350e9) | Apr 05, 2022 |
| ASUSTek       | 1101HA                      | Notebook    | [c3d2458d59](https://linux-hardware.org/?probe=c3d2458d59) | Apr 04, 2022 |
| ASUSTek       | ROG Strix G712LU_G712LU     | Notebook    | [288629b95d](https://linux-hardware.org/?probe=288629b95d) | Apr 04, 2022 |
| Dell          | 0YXT71 A01                  | Desktop     | [5de0fab8f2](https://linux-hardware.org/?probe=5de0fab8f2) | Apr 04, 2022 |
| Lenovo        | ThinkPad T430 23427YU       | Notebook    | [07ada1e358](https://linux-hardware.org/?probe=07ada1e358) | Apr 03, 2022 |
| ASUSTek       | ROG Strix G513QC_G513QC     | Notebook    | [697f820432](https://linux-hardware.org/?probe=697f820432) | Apr 02, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [83dab83528](https://linux-hardware.org/?probe=83dab83528) | Apr 01, 2022 |
| TUXEDO        | N7x0WU                      | Notebook    | [cf4f31fe3c](https://linux-hardware.org/?probe=cf4f31fe3c) | Mar 30, 2022 |
| Lenovo        | ThinkPad T440p 20AW002VB... | Notebook    | [e3ec03ac31](https://linux-hardware.org/?probe=e3ec03ac31) | Mar 29, 2022 |
| Framework     | Laptop                      | Notebook    | [a9f49dfe70](https://linux-hardware.org/?probe=a9f49dfe70) | Mar 24, 2022 |
| Lenovo        | 1046 NO DPK                 | Desktop     | [561b1c3324](https://linux-hardware.org/?probe=561b1c3324) | Mar 17, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [d0b555e0ba](https://linux-hardware.org/?probe=d0b555e0ba) | Mar 17, 2022 |
| Apple         | Mac-F2238AC8                | All in one  | [c8c2d7bba3](https://linux-hardware.org/?probe=c8c2d7bba3) | Mar 14, 2022 |
| HP            | 3647h                       | Desktop     | [fd6766aabb](https://linux-hardware.org/?probe=fd6766aabb) | Mar 11, 2022 |
| ASUSTek       | P5GC-MX/MEDION/SI           | Desktop     | [772e020316](https://linux-hardware.org/?probe=772e020316) | Mar 09, 2022 |
| MSI           | MS-7091                     | Desktop     | [71aaa6a920](https://linux-hardware.org/?probe=71aaa6a920) | Mar 09, 2022 |
| MSI           | MS-7091                     | Desktop     | [b08ddd1115](https://linux-hardware.org/?probe=b08ddd1115) | Mar 09, 2022 |
| Dell          | Latitude 3190               | Notebook    | [964420352c](https://linux-hardware.org/?probe=964420352c) | Feb 28, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [7147fe2d5c](https://linux-hardware.org/?probe=7147fe2d5c) | Feb 26, 2022 |
| ASUSTek       | 1101HA                      | Notebook    | [b234cc741f](https://linux-hardware.org/?probe=b234cc741f) | Feb 22, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [851badde2e](https://linux-hardware.org/?probe=851badde2e) | Feb 20, 2022 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [e58223cc60](https://linux-hardware.org/?probe=e58223cc60) | Feb 18, 2022 |
| Huanan        | X99-F8 V2.0                 | Desktop     | [23c722f6cf](https://linux-hardware.org/?probe=23c722f6cf) | Feb 18, 2022 |
| Huanan        | X99-F8 V2.0                 | Desktop     | [f4fec6a5be](https://linux-hardware.org/?probe=f4fec6a5be) | Feb 17, 2022 |
| Sony          | VPCF119FX                   | Notebook    | [1e8448b824](https://linux-hardware.org/?probe=1e8448b824) | Feb 15, 2022 |
| MSI           | Z97 GAMING 5                | Desktop     | [7c66c1b404](https://linux-hardware.org/?probe=7c66c1b404) | Feb 09, 2022 |
| Sony          | SVE1513Q1ESI                | Notebook    | [77e599ef9f](https://linux-hardware.org/?probe=77e599ef9f) | Feb 08, 2022 |
| Dell          | Latitude E4310              | Notebook    | [50190cb420](https://linux-hardware.org/?probe=50190cb420) | Feb 06, 2022 |
| efirstview    | v01099                      | Notebook    | [ed22d3c2b6](https://linux-hardware.org/?probe=ed22d3c2b6) | Feb 04, 2022 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [4ffe151e7a](https://linux-hardware.org/?probe=4ffe151e7a) | Jan 29, 2022 |
| Lenovo        | ThinkPad W541 20EG0005MS    | Notebook    | [f89a7895fc](https://linux-hardware.org/?probe=f89a7895fc) | Jan 23, 2022 |
| Sony          | VPCEH2N1E                   | Notebook    | [17a4bc1847](https://linux-hardware.org/?probe=17a4bc1847) | Jan 22, 2022 |
| Fujitsu Si... | LIFEBOOK E8010              | Notebook    | [82d1bc5db0](https://linux-hardware.org/?probe=82d1bc5db0) | Jan 22, 2022 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [882906d968](https://linux-hardware.org/?probe=882906d968) | Jan 17, 2022 |
| Alienware     | 13 R2                       | Notebook    | [65c1ae9026](https://linux-hardware.org/?probe=65c1ae9026) | Jan 14, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [58cff543b5](https://linux-hardware.org/?probe=58cff543b5) | Jan 06, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [ecaec39529](https://linux-hardware.org/?probe=ecaec39529) | Jan 05, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [d0d2edf745](https://linux-hardware.org/?probe=d0d2edf745) | Jan 04, 2022 |
| Lenovo        | G400s VILG1                 | Notebook    | [1cd4b24f16](https://linux-hardware.org/?probe=1cd4b24f16) | Jan 04, 2022 |
| Gigabyte      | P15FV5                      | Notebook    | [164348e568](https://linux-hardware.org/?probe=164348e568) | Jan 03, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [7cc374183b](https://linux-hardware.org/?probe=7cc374183b) | Dec 30, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [4fe24b4f44](https://linux-hardware.org/?probe=4fe24b4f44) | Dec 26, 2021 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [9147191a67](https://linux-hardware.org/?probe=9147191a67) | Dec 24, 2021 |
| ASUSTek       | X550CC                      | Notebook    | [b0cde813b9](https://linux-hardware.org/?probe=b0cde813b9) | Dec 23, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [78d4e04363](https://linux-hardware.org/?probe=78d4e04363) | Dec 16, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [49692045a2](https://linux-hardware.org/?probe=49692045a2) | Dec 16, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [21180cbdad](https://linux-hardware.org/?probe=21180cbdad) | Dec 04, 2021 |
| GALAX         | B550M                       | Desktop     | [a6866c8a45](https://linux-hardware.org/?probe=a6866c8a45) | Dec 04, 2021 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [bc8359d097](https://linux-hardware.org/?probe=bc8359d097) | Dec 01, 2021 |
| Lenovo        | B590 20208                  | Notebook    | [ed08d6bdd9](https://linux-hardware.org/?probe=ed08d6bdd9) | Nov 30, 2021 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | Notebook    | [649434f9b8](https://linux-hardware.org/?probe=649434f9b8) | Nov 23, 2021 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [bb58f4914e](https://linux-hardware.org/?probe=bb58f4914e) | Nov 21, 2021 |
| ASUSTek       | N53SN                       | Notebook    | [67d66feb3e](https://linux-hardware.org/?probe=67d66feb3e) | Nov 20, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [791ae651bb](https://linux-hardware.org/?probe=791ae651bb) | Nov 14, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [b105aaabf5](https://linux-hardware.org/?probe=b105aaabf5) | Nov 14, 2021 |
| Lenovo        | SHARKBAY NO DPK             | Desktop     | [fd5f409df8](https://linux-hardware.org/?probe=fd5f409df8) | Nov 14, 2021 |
| Lenovo        | SHARKBAY NO DPK             | Desktop     | [a85cc99f78](https://linux-hardware.org/?probe=a85cc99f78) | Nov 14, 2021 |
| HP            | Compaq Presario CQ60        | Notebook    | [9d83baca33](https://linux-hardware.org/?probe=9d83baca33) | Nov 12, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [c277967769](https://linux-hardware.org/?probe=c277967769) | Nov 11, 2021 |
| ASRock        | X570 Steel Legend           | Desktop     | [18391015f7](https://linux-hardware.org/?probe=18391015f7) | Nov 11, 2021 |
| Apple         | MacBook3,1                  | Notebook    | [25964b9256](https://linux-hardware.org/?probe=25964b9256) | Nov 08, 2021 |
| HP            | EliteBook 850 G3            | Notebook    | [cd26ab6e8f](https://linux-hardware.org/?probe=cd26ab6e8f) | Nov 05, 2021 |
| Dell          | Latitude 3190               | Notebook    | [592b613273](https://linux-hardware.org/?probe=592b613273) | Nov 01, 2021 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [fbd2076eee](https://linux-hardware.org/?probe=fbd2076eee) | Oct 28, 2021 |
| ASUSTek       | E402MA                      | Notebook    | [4c2453c6a2](https://linux-hardware.org/?probe=4c2453c6a2) | Oct 26, 2021 |
| Sony          | VPCEC3S1E                   | Notebook    | [2af79ba873](https://linux-hardware.org/?probe=2af79ba873) | Oct 25, 2021 |
| Gigabyte      | B550M DS3H                  | Desktop     | [ee6a141211](https://linux-hardware.org/?probe=ee6a141211) | Oct 19, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | Notebook    | [ee6fdf4608](https://linux-hardware.org/?probe=ee6fdf4608) | Oct 18, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [f8735054b4](https://linux-hardware.org/?probe=f8735054b4) | Sep 02, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [5d136cb09b](https://linux-hardware.org/?probe=5d136cb09b) | Aug 13, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [c4ebb4c114](https://linux-hardware.org/?probe=c4ebb4c114) | Jun 04, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Computers | Percent |
|----------------------------|-----------|---------|
| 5.10.0-9-amd64             | 18        | 21.95%  |
| 5.10.0-13-amd64            | 12        | 14.63%  |
| 5.14.0-4mx-amd64           | 11        | 13.41%  |
| 5.10.0-11-amd64            | 8         | 9.76%   |
| 5.10.0-10-amd64            | 4         | 4.88%   |
| 5.16.0-6mx-amd64           | 2         | 2.44%   |
| 5.16.0-5mx-amd64           | 2         | 2.44%   |
| 5.16.0-4mx-amd64           | 2         | 2.44%   |
| 5.14.0-3mx-amd64           | 2         | 2.44%   |
| 5.10.0-8-amd64             | 2         | 2.44%   |
| 5.10.0-14-amd64            | 2         | 2.44%   |
| 5.10.0-11-686-pae          | 2         | 2.44%   |
| 5.17.0-5.2-liquorix-amd64  | 1         | 1.22%   |
| 5.17.0-1mx-amd64           | 1         | 1.22%   |
| 5.17.0-1-amd64             | 1         | 1.22%   |
| 5.16.0-rc5-hwmon-next+     | 1         | 1.22%   |
| 5.16.0-18.1-liquorix-amd64 | 1         | 1.22%   |
| 5.15.0-3mx-amd64           | 1         | 1.22%   |
| 5.15.0-2-amd64             | 1         | 1.22%   |
| 5.15.0-0.bpo.2-amd64       | 1         | 1.22%   |
| 5.14.0-2mx-amd64           | 1         | 1.22%   |
| 5.10.52-antix.1-amd64-smp  | 1         | 1.22%   |
| 5.10.111-tkg-cfs           | 1         | 1.22%   |
| 5.10.0-5mx-amd64           | 1         | 1.22%   |
| 5.10.0-13-686-pae          | 1         | 1.22%   |
| 5.10.0-12-amd64            | 1         | 1.22%   |
| 5.10.0-11-686              | 1         | 1.22%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.10.0   | 50        | 62.5%   |
| 5.14.0   | 14        | 17.5%   |
| 5.16.0   | 8         | 10%     |
| 5.17.0   | 3         | 3.75%   |
| 5.15.0   | 3         | 3.75%   |
| 5.10.52  | 1         | 1.25%   |
| 5.10.111 | 1         | 1.25%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 52        | 65%     |
| 5.14    | 14        | 17.5%   |
| 5.16    | 8         | 10%     |
| 5.17    | 3         | 3.75%   |
| 5.15    | 3         | 3.75%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 75        | 96.15%  |
| i686   | 3         | 3.85%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| XFCE             | 53        | 67.95%  |
| KDE5             | 19        | 24.36%  |
| GNOME            | 2         | 2.56%   |
| Unknown          | 2         | 2.56%   |
| lightdm-xsession | 1         | 1.28%   |
| Budgie           | 1         | 1.28%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 77        | 98.72%  |
| Tty  | 1         | 1.28%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 57        | 73.08%  |
| SDDM    | 19        | 24.36%  |
| SLiM    | 1         | 1.28%   |
| Unknown | 1         | 1.28%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 40        | 51.28%  |
| de_DE   | 13        | 16.67%  |
| ru_RU   | 3         | 3.85%   |
| it_IT   | 3         | 3.85%   |
| en_GB   | 3         | 3.85%   |
| de_CH   | 3         | 3.85%   |
| Unknown | 3         | 3.85%   |
| pt_BR   | 2         | 2.56%   |
| fr_FR   | 2         | 2.56%   |
| tr_TR   | 1         | 1.28%   |
| sv_SE   | 1         | 1.28%   |
| sk_SK   | 1         | 1.28%   |
| fi_FI   | 1         | 1.28%   |
| es_PE   | 1         | 1.28%   |
| es_ES   | 1         | 1.28%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 52        | 66.67%  |
| BIOS | 26        | 33.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 65        | 83.33%  |
| Overlay  | 7         | 8.97%   |
| Btrfs    | 4         | 5.13%   |
| Reiserfs | 1         | 1.28%   |
| F2fs     | 1         | 1.28%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 61        | 78.21%  |
| MBR     | 16        | 20.51%  |
| Unknown | 1         | 1.28%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 45        | 57.69%  |
| Yes       | 33        | 42.31%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 40        | 51.28%  |
| Yes       | 38        | 48.72%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 13        | 16.67%  |
| Lenovo              | 12        | 15.38%  |
| Hewlett-Packard     | 9         | 11.54%  |
| Gigabyte Technology | 6         | 7.69%   |
| Sony                | 5         | 6.41%   |
| Dell                | 4         | 5.13%   |
| Apple               | 4         | 5.13%   |
| MSI                 | 3         | 3.85%   |
| Samsung Electronics | 2         | 2.56%   |
| Fujitsu Siemens     | 2         | 2.56%   |
| ASRock              | 2         | 2.56%   |
| Alienware           | 2         | 2.56%   |
| Acer                | 2         | 2.56%   |
| TUXEDO              | 1         | 1.28%   |
| Sun Microsystems    | 1         | 1.28%   |
| Microsoft           | 1         | 1.28%   |
| Medion              | 1         | 1.28%   |
| Intel               | 1         | 1.28%   |
| Huanan              | 1         | 1.28%   |
| GALAX               | 1         | 1.28%   |
| Fujitsu             | 1         | 1.28%   |
| Framework           | 1         | 1.28%   |
| efirstview          | 1         | 1.28%   |
| Chuwi               | 1         | 1.28%   |
| AZW                 | 1         | 1.28%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                         | Computers | Percent |
|----------------------------------------------|-----------|---------|
| ASUS All Series                              | 2         | 2.56%   |
| TUXEDO N7x0WU                                | 1         | 1.28%   |
| Sun Microsystems Sun Ultra 40 M2 Workstation | 1         | 1.28%   |
| Sony VPCSB1V9R                               | 1         | 1.28%   |
| Sony VPCF119FX                               | 1         | 1.28%   |
| Sony VPCEH2N1E                               | 1         | 1.28%   |
| Sony VPCEC3S1E                               | 1         | 1.28%   |
| Sony SVE1513Q1ESI                            | 1         | 1.28%   |
| Samsung 350V5C/351V5C/3540VC/3440VC          | 1         | 1.28%   |
| Samsung 340XAA/350XAA/550XAA                 | 1         | 1.28%   |
| MSI MS-7917                                  | 1         | 1.28%   |
| MSI GV62 8RD                                 | 1         | 1.28%   |
| MSI Alpha 15 B5EEK                           | 1         | 1.28%   |
| Microsoft Surface Pro 7                      | 1         | 1.28%   |
| Medion E14304                                | 1         | 1.28%   |
| Lenovo Yoga 7 14ITL5 82BH                    | 1         | 1.28%   |
| Lenovo ThinkStation P620 30E0CTO1WW          | 1         | 1.28%   |
| Lenovo ThinkPad W541 20EG0005MS              | 1         | 1.28%   |
| Lenovo ThinkPad T440p 20AW002VBR             | 1         | 1.28%   |
| Lenovo ThinkPad T430 23427YU                 | 1         | 1.28%   |
| Lenovo ThinkPad E15 Gen 3 20YG008CUS         | 1         | 1.28%   |
| Lenovo ThinkBook 13s-IWL 20R9                | 1         | 1.28%   |
| Lenovo Legion 5 15ACH6H 82JU                 | 1         | 1.28%   |
| Lenovo IdeaPad Y700-15ISK 80NV               | 1         | 1.28%   |
| Lenovo G400s VILG1                           | 1         | 1.28%   |
| Lenovo B590 20208                            | 1         | 1.28%   |
| Lenovo 10AAS1QB0B                            | 1         | 1.28%   |
| Intel V1.3                                   | 1         | 1.28%   |
| Huanan X99-F8                                | 1         | 1.28%   |
| HP Z400 Workstation                          | 1         | 1.28%   |
| HP Stream Laptop 14-cb0XX                    | 1         | 1.28%   |
| HP Spectre x360 Convertible 15-df1xxx        | 1         | 1.28%   |
| HP ProBook 450 G4                            | 1         | 1.28%   |
| HP EliteBook 850 G3                          | 1         | 1.28%   |
| HP EliteBook 8440p                           | 1         | 1.28%   |
| HP EliteBook 840 G3                          | 1         | 1.28%   |
| HP Compaq Presario CQ60                      | 1         | 1.28%   |
| HP Compaq 8000 Elite CMT PC                  | 1         | 1.28%   |
| Gigabyte Z390 UD                             | 1         | 1.28%   |
| Gigabyte X570 AORUS PRO                      | 1         | 1.28%   |
| Gigabyte P15FV5                              | 1         | 1.28%   |
| Gigabyte G5 KC                               | 1         | 1.28%   |
| Gigabyte B550M S2H                           | 1         | 1.28%   |
| Gigabyte B550M DS3H                          | 1         | 1.28%   |
| GALAX B550M                                  | 1         | 1.28%   |
| Fujitsu Siemens LIFEBOOK E8010               | 1         | 1.28%   |
| Fujitsu Siemens ESPRIMO Mobile D9500         | 1         | 1.28%   |
| Fujitsu ESPRIMO P720                         | 1         | 1.28%   |
| Framework Laptop                             | 1         | 1.28%   |
| efirstview v01099                            | 1         | 1.28%   |
| Dell XPS 17 9710                             | 1         | 1.28%   |
| Dell OptiPlex 7010                           | 1         | 1.28%   |
| Dell Latitude E4310                          | 1         | 1.28%   |
| Dell Latitude 3190                           | 1         | 1.28%   |
| Chuwi GemiBook Pro                           | 1         | 1.28%   |
| AZW SER                                      | 1         | 1.28%   |
| ASUS X550CC                                  | 1         | 1.28%   |
| ASUS TUF Gaming FX505DT_FX505DT              | 1         | 1.28%   |
| ASUS ROG Strix G712LU_G712LU                 | 1         | 1.28%   |
| ASUS ROG Strix G513QC_G513QC                 | 1         | 1.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 4         | 5.13%   |
| HP EliteBook             | 3         | 3.85%   |
| ASUS ROG                 | 3         | 3.85%   |
| HP Compaq                | 2         | 2.56%   |
| Gigabyte B550M           | 2         | 2.56%   |
| Dell Latitude            | 2         | 2.56%   |
| ASUS All                 | 2         | 2.56%   |
| TUXEDO N7x0WU            | 1         | 1.28%   |
| Sun Microsystems Sun     | 1         | 1.28%   |
| Sony VPCSB1V9R           | 1         | 1.28%   |
| Sony VPCF119FX           | 1         | 1.28%   |
| Sony VPCEH2N1E           | 1         | 1.28%   |
| Sony VPCEC3S1E           | 1         | 1.28%   |
| Sony SVE1513Q1ESI        | 1         | 1.28%   |
| Samsung 350V5C           | 1         | 1.28%   |
| Samsung 340XAA           | 1         | 1.28%   |
| MSI MS-7917              | 1         | 1.28%   |
| MSI GV62                 | 1         | 1.28%   |
| MSI Alpha                | 1         | 1.28%   |
| Microsoft Surface        | 1         | 1.28%   |
| Medion E14304            | 1         | 1.28%   |
| Lenovo Yoga              | 1         | 1.28%   |
| Lenovo ThinkStation      | 1         | 1.28%   |
| Lenovo ThinkBook         | 1         | 1.28%   |
| Lenovo Legion            | 1         | 1.28%   |
| Lenovo IdeaPad           | 1         | 1.28%   |
| Lenovo G400s             | 1         | 1.28%   |
| Lenovo B590              | 1         | 1.28%   |
| Lenovo 10AAS1QB0B        | 1         | 1.28%   |
| Intel V1.3               | 1         | 1.28%   |
| Huanan X99-F8            | 1         | 1.28%   |
| HP Z400                  | 1         | 1.28%   |
| HP Stream                | 1         | 1.28%   |
| HP Spectre               | 1         | 1.28%   |
| HP ProBook               | 1         | 1.28%   |
| Gigabyte Z390            | 1         | 1.28%   |
| Gigabyte X570            | 1         | 1.28%   |
| Gigabyte P15FV5          | 1         | 1.28%   |
| Gigabyte G5              | 1         | 1.28%   |
| GALAX B550M              | 1         | 1.28%   |
| Fujitsu Siemens LIFEBOOK | 1         | 1.28%   |
| Fujitsu Siemens ESPRIMO  | 1         | 1.28%   |
| Fujitsu ESPRIMO          | 1         | 1.28%   |
| Framework Laptop         | 1         | 1.28%   |
| efirstview v01099        | 1         | 1.28%   |
| Dell XPS                 | 1         | 1.28%   |
| Dell OptiPlex            | 1         | 1.28%   |
| Chuwi GemiBook           | 1         | 1.28%   |
| AZW SER                  | 1         | 1.28%   |
| ASUS X550CC              | 1         | 1.28%   |
| ASUS TUF                 | 1         | 1.28%   |
| ASUS P5GC-MX             | 1         | 1.28%   |
| ASUS N53SN               | 1         | 1.28%   |
| ASUS K55A                | 1         | 1.28%   |
| ASUS E402MA              | 1         | 1.28%   |
| ASUS ASUS                | 1         | 1.28%   |
| ASUS 1101HA              | 1         | 1.28%   |
| ASRock X570              | 1         | 1.28%   |
| ASRock N3150M            | 1         | 1.28%   |
| Apple Macmini6           | 1         | 1.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 13        | 16.67%  |
| 2020    | 8         | 10.26%  |
| 2015    | 7         | 8.97%   |
| 2019    | 6         | 7.69%   |
| 2016    | 6         | 7.69%   |
| 2013    | 6         | 7.69%   |
| 2010    | 6         | 7.69%   |
| 2018    | 5         | 6.41%   |
| 2011    | 4         | 5.13%   |
| 2014    | 3         | 3.85%   |
| 2012    | 3         | 3.85%   |
| 2007    | 3         | 3.85%   |
| 2009    | 2         | 2.56%   |
| 2008    | 2         | 2.56%   |
| 2022    | 1         | 1.28%   |
| 2017    | 1         | 1.28%   |
| 2005    | 1         | 1.28%   |
| Unknown | 1         | 1.28%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 50        | 64.1%   |
| Desktop     | 20        | 25.64%  |
| Convertible | 2         | 2.56%   |
| Mini pc     | 2         | 2.56%   |
| All in one  | 2         | 2.56%   |
| Tablet      | 1         | 1.28%   |
| Server      | 1         | 1.28%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 77        | 98.72%  |
| Enabled  | 1         | 1.28%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 78        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 22        | 28.21%  |
| 8.01-16.0   | 18        | 23.08%  |
| 16.01-24.0  | 15        | 19.23%  |
| 32.01-64.0  | 9         | 11.54%  |
| 3.01-4.0    | 6         | 7.69%   |
| 2.01-3.0    | 3         | 3.85%   |
| 64.01-256.0 | 2         | 2.56%   |
| 24.01-32.0  | 1         | 1.28%   |
| 1.01-2.0    | 1         | 1.28%   |
| 0.51-1.0    | 1         | 1.28%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 28        | 34.57%  |
| 2.01-3.0   | 24        | 29.63%  |
| 3.01-4.0   | 11        | 13.58%  |
| 4.01-8.0   | 8         | 9.88%   |
| 0.51-1.0   | 5         | 6.17%   |
| 8.01-16.0  | 4         | 4.94%   |
| 16.01-24.0 | 1         | 1.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 38        | 48.72%  |
| 2      | 20        | 25.64%  |
| 3      | 13        | 16.67%  |
| 4      | 3         | 3.85%   |
| 5      | 2         | 2.56%   |
| 8      | 1         | 1.28%   |
| 0      | 1         | 1.28%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 53        | 67.95%  |
| Yes       | 25        | 32.05%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 67        | 85.9%   |
| No        | 11        | 14.1%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 62        | 79.49%  |
| No        | 16        | 20.51%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 48        | 61.54%  |
| No        | 30        | 38.46%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 24        | 30.77%  |
| Germany     | 11        | 14.1%   |
| Italy       | 5         | 6.41%   |
| Canada      | 5         | 6.41%   |
| Switzerland | 3         | 3.85%   |
| Brazil      | 3         | 3.85%   |
| Spain       | 2         | 2.56%   |
| Russia      | 2         | 2.56%   |
| France      | 2         | 2.56%   |
| Finland     | 2         | 2.56%   |
| Belgium     | 2         | 2.56%   |
| Austria     | 2         | 2.56%   |
| UK          | 1         | 1.28%   |
| Turkey      | 1         | 1.28%   |
| Sweden      | 1         | 1.28%   |
| Slovakia    | 1         | 1.28%   |
| Serbia      | 1         | 1.28%   |
| Poland      | 1         | 1.28%   |
| Peru        | 1         | 1.28%   |
| Netherlands | 1         | 1.28%   |
| Malaysia    | 1         | 1.28%   |
| India       | 1         | 1.28%   |
| Greece      | 1         | 1.28%   |
| Czechia     | 1         | 1.28%   |
| Belarus     | 1         | 1.28%   |
| Azerbaijan  | 1         | 1.28%   |
| Australia   | 1         | 1.28%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Computers | Percent |
|---------------------------|-----------|---------|
| Vienna                    | 2         | 2.53%   |
| Portland                  | 2         | 2.53%   |
| Ettingen                  | 2         | 2.53%   |
| Zurich                    | 1         | 1.27%   |
| Waycross                  | 1         | 1.27%   |
| Warsaw                    | 1         | 1.27%   |
| Volos                     | 1         | 1.27%   |
| Vilhelmina                | 1         | 1.27%   |
| Vancouver                 | 1         | 1.27%   |
| Uelzen                    | 1         | 1.27%   |
| Tupelo                    | 1         | 1.27%   |
| Taggia                    | 1         | 1.27%   |
| Tacoma                    | 1         | 1.27%   |
| Surprise                  | 1         | 1.27%   |
| St Petersburg             | 1         | 1.27%   |
| Seelbach                  | 1         | 1.27%   |
| Schaarbeek                | 1         | 1.27%   |
| Saskatoon                 | 1         | 1.27%   |
| San Diego                 | 1         | 1.27%   |
| Saarlouis                 | 1         | 1.27%   |
| Rosporden                 | 1         | 1.27%   |
| Roseville                 | 1         | 1.27%   |
| Rochester                 | 1         | 1.27%   |
| Reinbek                   | 1         | 1.27%   |
| Prague                    | 1         | 1.27%   |
| Powder Springs            | 1         | 1.27%   |
| Postbauer-Heng            | 1         | 1.27%   |
| Piedmont                  | 1         | 1.27%   |
| Ottawa                    | 1         | 1.27%   |
| Osasco                    | 1         | 1.27%   |
| Obourg                    | 1         | 1.27%   |
| Normal                    | 1         | 1.27%   |
| Neumarkt in der Oberpfalz | 1         | 1.27%   |
| Munich                    | 1         | 1.27%   |
| Moses Lake                | 1         | 1.27%   |
| Moscow                    | 1         | 1.27%   |
| Montreal                  | 1         | 1.27%   |
| Montebelluna              | 1         | 1.27%   |
| Minsk                     | 1         | 1.27%   |
| Minneapolis               | 1         | 1.27%   |
| Milwaukee                 | 1         | 1.27%   |
| Mestre                    | 1         | 1.27%   |
| Lima                      | 1         | 1.27%   |
| Lannion                   | 1         | 1.27%   |
| Lahti                     | 1         | 1.27%   |
| Kitchener                 | 1         | 1.27%   |
| Istanbul                  | 1         | 1.27%   |
| Huercal Overa             | 1         | 1.27%   |
| Houston                   | 1         | 1.27%   |
| Helsinki                  | 1         | 1.27%   |
| Graniteville              | 1         | 1.27%   |
| Granadilla de Abona       | 1         | 1.27%   |
| Göttingen                | 1         | 1.27%   |
| Freital                   | 1         | 1.27%   |
| Florence                  | 1         | 1.27%   |
| Dieburg                   | 1         | 1.27%   |
| Diana                     | 1         | 1.27%   |
| Cyberjaya                 | 1         | 1.27%   |
| Corsico                   | 1         | 1.27%   |
| Concord                   | 1         | 1.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 22        | 33     | 17.46%  |
| WDC                 | 19        | 23     | 15.08%  |
| Seagate             | 13        | 17     | 10.32%  |
| Kingston            | 11        | 11     | 8.73%   |
| Crucial             | 9         | 12     | 7.14%   |
| SK Hynix            | 5         | 6      | 3.97%   |
| Unknown             | 4         | 4      | 3.17%   |
| Transcend           | 4         | 4      | 3.17%   |
| SanDisk             | 4         | 4      | 3.17%   |
| PNY                 | 3         | 4      | 2.38%   |
| LITEON              | 3         | 3      | 2.38%   |
| Intel               | 3         | 3      | 2.38%   |
| Dogfish             | 3         | 3      | 2.38%   |
| Toshiba             | 2         | 2      | 1.59%   |
| OCZ                 | 2         | 2      | 1.59%   |
| Hitachi             | 2         | 2      | 1.59%   |
| Corsair             | 2         | 2      | 1.59%   |
| SPCC                | 1         | 1      | 0.79%   |
| Silicon Motion      | 1         | 1      | 0.79%   |
| SABRENT             | 1         | 1      | 0.79%   |
| Phison              | 1         | 1      | 0.79%   |
| Netac               | 1         | 1      | 0.79%   |
| Micron Technology   | 1         | 1      | 0.79%   |
| MAXTOR              | 1         | 1      | 0.79%   |
| GOODRAM             | 1         | 1      | 0.79%   |
| Gigabyte Technology | 1         | 1      | 0.79%   |
| GeIL                | 1         | 1      | 0.79%   |
| Fujitsu             | 1         | 1      | 0.79%   |
| Avant               | 1         | 1      | 0.79%   |
| Apple               | 1         | 2      | 0.79%   |
| A-DATA Technology   | 1         | 1      | 0.79%   |
| Unknown             | 1         | 1      | 0.79%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Kingston SA400S37480G 480GB SSD      | 4         | 2.82%   |
| Seagate ST2000DM008-2FR102 2TB       | 3         | 2.11%   |
| Samsung SSD 970 EVO Plus 1TB         | 3         | 2.11%   |
| Kingston SA400S37240G 240GB SSD      | 3         | 2.11%   |
| SK Hynix HFM512GDJTNI-82A0A 512GB    | 2         | 1.41%   |
| Samsung SSD 980 PRO 1TB              | 2         | 1.41%   |
| Samsung SSD 860 EVO 500GB            | 2         | 1.41%   |
| Samsung SSD 850 EVO 1TB              | 2         | 1.41%   |
| Dogfish SSD 128GB                    | 2         | 1.41%   |
| Crucial CT500P2SSD8 500GB            | 2         | 1.41%   |
| Crucial CT240BX500SSD1 240GB         | 2         | 1.41%   |
| Crucial CT120BX500SSD1 120GB         | 2         | 1.41%   |
| Corsair MP400 2TB                    | 2         | 1.41%   |
| WDC WDS500G2B0C-00PXH0 500GB         | 1         | 0.7%    |
| WDC WDS500G2B0B-00YS70 500GB SSD     | 1         | 0.7%    |
| WDC WDS100T2B0A-00SM50 1TB SSD       | 1         | 0.7%    |
| WDC WDS100T1X0E-00AFY0 1TB           | 1         | 0.7%    |
| WDC WD60EZRZ-00RWYB1 6TB             | 1         | 0.7%    |
| WDC WD60EFRX-68L0BN1 6TB             | 1         | 0.7%    |
| WDC WD5002AALX-00J37A0 500GB         | 1         | 0.7%    |
| WDC WD5000LPLX-08ZNTT0 500GB         | 1         | 0.7%    |
| WDC WD5000LPCX-22VHAT0 500GB         | 1         | 0.7%    |
| WDC WD5000AVCS-632DY1 500GB          | 1         | 0.7%    |
| WDC WD5000AAKS-40V6A0 500GB          | 1         | 0.7%    |
| WDC WD40EFRX-68WT0N0 4TB             | 1         | 0.7%    |
| WDC WD30EFRX-68AX9N0 3TB             | 1         | 0.7%    |
| WDC WD1600BEVT-60ZCT1 160GB          | 1         | 0.7%    |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 0.7%    |
| WDC WD10EZEX-08M2NA0 1TB             | 1         | 0.7%    |
| WDC WD10EVDS-63U8B1 1TB              | 1         | 0.7%    |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB   | 1         | 0.7%    |
| WDC PC SN730 NVMe 1024GB             | 1         | 0.7%    |
| WDC PC SN530 SDBPNPZ-1T00-1032 1TB   | 1         | 0.7%    |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB | 1         | 0.7%    |
| WDC PC SN530 SDBPMPZ-512G-1001 512GB | 1         | 0.7%    |
| Unknown SDW32G  32GB                 | 1         | 0.7%    |
| Unknown SD32G  32GB                  | 1         | 0.7%    |
| Unknown SD08G  8GB                   | 1         | 0.7%    |
| Unknown BJTD4R  32GB                 | 1         | 0.7%    |
| Transcend TS256GSSD370S 256GB        | 1         | 0.7%    |
| Transcend TS1GSDOM22V 1GB SSD        | 1         | 0.7%    |
| Transcend TS128GSSD370S 128GB        | 1         | 0.7%    |
| Transcend TS128GMTS800 128GB SSD     | 1         | 0.7%    |
| Toshiba MQ01ABD075 752GB             | 1         | 0.7%    |
| Toshiba DT01ACA100 1TB               | 1         | 0.7%    |
| SPCC Solid State Disk 256GB          | 1         | 0.7%    |
| SK Hynix HFM512GD3JX013N 512GB       | 1         | 0.7%    |
| SK Hynix HFM256GDJTNG-8310A 256GB    | 1         | 0.7%    |
| SK Hynix HFB1M8MO331C0MR 256GB       | 1         | 0.7%    |
| Silicon Motion NVMe SSD Drive 256GB  | 1         | 0.7%    |
| Seagate ST9320421AS 320GB            | 1         | 0.7%    |
| Seagate ST750LM022 HN-M750MBB 752GB  | 1         | 0.7%    |
| Seagate ST500LM021-1KJ152 500GB      | 1         | 0.7%    |
| Seagate ST500LM000-1EJ162 500GB      | 1         | 0.7%    |
| Seagate ST4000DM004-2CV104 4TB       | 1         | 0.7%    |
| Seagate ST3500413AS 500GB            | 1         | 0.7%    |
| Seagate ST3360320AS 360GB            | 1         | 0.7%    |
| Seagate ST2000LM003 HN-M201RAD 2TB   | 1         | 0.7%    |
| Seagate ST1000LM048-2E7172 1TB       | 1         | 0.7%    |
| Seagate ST1000LM035-1RK172 1TB       | 1         | 0.7%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 17     | 38.24%  |
| WDC                 | 10        | 14     | 29.41%  |
| Samsung Electronics | 3         | 3      | 8.82%   |
| Toshiba             | 2         | 2      | 5.88%   |
| Hitachi             | 2         | 2      | 5.88%   |
| SABRENT             | 1         | 1      | 2.94%   |
| MAXTOR              | 1         | 1      | 2.94%   |
| Fujitsu             | 1         | 1      | 2.94%   |
| Apple               | 1         | 1      | 2.94%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 13        | 17     | 22.03%  |
| Kingston            | 9         | 9      | 15.25%  |
| Crucial             | 7         | 9      | 11.86%  |
| Transcend           | 4         | 4      | 6.78%   |
| SanDisk             | 4         | 4      | 6.78%   |
| LITEON              | 3         | 3      | 5.08%   |
| Dogfish             | 3         | 3      | 5.08%   |
| WDC                 | 2         | 2      | 3.39%   |
| PNY                 | 2         | 2      | 3.39%   |
| OCZ                 | 2         | 2      | 3.39%   |
| SPCC                | 1         | 1      | 1.69%   |
| Netac               | 1         | 1      | 1.69%   |
| Micron Technology   | 1         | 1      | 1.69%   |
| Intel               | 1         | 1      | 1.69%   |
| GOODRAM             | 1         | 1      | 1.69%   |
| Gigabyte Technology | 1         | 1      | 1.69%   |
| GeIL                | 1         | 1      | 1.69%   |
| Avant               | 1         | 1      | 1.69%   |
| Apple               | 1         | 1      | 1.69%   |
| A-DATA Technology   | 1         | 1      | 1.69%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 47        | 65     | 41.96%  |
| NVMe | 30        | 39     | 26.79%  |
| HDD  | 30        | 42     | 26.79%  |
| MMC  | 5         | 5      | 4.46%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 57        | 104    | 60.64%  |
| NVMe | 30        | 39     | 31.91%  |
| MMC  | 5         | 5      | 5.32%   |
| SAS  | 2         | 3      | 2.13%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 48        | 68     | 61.54%  |
| 0.51-1.0   | 21        | 26     | 26.92%  |
| 1.01-2.0   | 5         | 7      | 6.41%   |
| 3.01-4.0   | 2         | 2      | 2.56%   |
| 2.01-3.0   | 1         | 1      | 1.28%   |
| 4.01-10.0  | 1         | 3      | 1.28%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 18        | 23.08%  |
| 101-250        | 18        | 23.08%  |
| 501-1000       | 14        | 17.95%  |
| More than 3000 | 6         | 7.69%   |
| 21-50          | 6         | 7.69%   |
| 1001-2000      | 5         | 6.41%   |
| 51-100         | 5         | 6.41%   |
| 2001-3000      | 3         | 3.85%   |
| 1-20           | 3         | 3.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 25        | 31.25%  |
| 21-50          | 19        | 23.75%  |
| 101-250        | 10        | 12.5%   |
| 51-100         | 10        | 12.5%   |
| 251-500        | 6         | 7.5%    |
| 1001-2000      | 5         | 6.25%   |
| More than 3000 | 2         | 2.5%    |
| 501-1000       | 2         | 2.5%    |
| 2001-3000      | 1         | 1.25%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WDS100T2B0A-00SM50 1TB SSD               | 1         | 1      | 7.69%   |
| WDC WD5000AAKS-40V6A0 500GB                  | 1         | 1      | 7.69%   |
| Seagate ST9320421AS 320GB                    | 1         | 1      | 7.69%   |
| Seagate ST750LM022 HN-M750MBB 752GB          | 1         | 1      | 7.69%   |
| Seagate ST500LM021-1KJ152 500GB              | 1         | 1      | 7.69%   |
| Seagate ST3500413AS 500GB                    | 1         | 1      | 7.69%   |
| Seagate ST3360320AS 360GB                    | 1         | 1      | 7.69%   |
| Samsung Electronics SSD 850 EVO 500GB        | 1         | 1      | 7.69%   |
| Samsung Electronics SSD 850 EVO 1TB          | 1         | 2      | 7.69%   |
| Samsung Electronics SSD 840 Series 120GB     | 1         | 1      | 7.69%   |
| Samsung Electronics SSD 840 PRO Series 256GB | 1         | 1      | 7.69%   |
| MAXTOR 4K040H2 40GB                          | 1         | 1      | 7.69%   |
| GOODRAM SSDPR-CL100-480-G3 480GB             | 1         | 1      | 7.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 5      | 38.46%  |
| Samsung Electronics | 4         | 5      | 30.77%  |
| WDC                 | 2         | 2      | 15.38%  |
| MAXTOR              | 1         | 1      | 7.69%   |
| GOODRAM             | 1         | 1      | 7.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 5      | 71.43%  |
| WDC     | 1         | 1      | 14.29%  |
| MAXTOR  | 1         | 1      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 6         | 7      | 50%     |
| HDD  | 6         | 7      | 50%     |

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
| Works    | 69        | 127    | 77.53%  |
| Malfunc  | 12        | 14     | 13.48%  |
| Detected | 8         | 10     | 8.99%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 55        | 53.92%  |
| Samsung Electronics         | 11        | 10.78%  |
| AMD                         | 8         | 7.84%   |
| Sandisk                     | 7         | 6.86%   |
| SK Hynix                    | 5         | 4.9%    |
| Phison Electronics          | 4         | 3.92%   |
| ASMedia Technology          | 3         | 2.94%   |
| Nvidia                      | 2         | 1.96%   |
| Micron/Crucial Technology   | 2         | 1.96%   |
| Kingston Technology Company | 2         | 1.96%   |
| Silicon Motion              | 1         | 0.98%   |
| Silicon Image               | 1         | 0.98%   |
| Broadcom / LSI              | 1         | 0.98%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 8         | 7.08%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 5         | 4.42%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 5         | 4.42%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 5         | 4.42%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 4         | 3.54%   |
| Phison E12 NVMe Controller                                                       | 4         | 3.54%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 3.54%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 3         | 2.65%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 3         | 2.65%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 3         | 2.65%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 3         | 2.65%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 2.65%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 3         | 2.65%   |
| AMD 500 Series Chipset SATA Controller                                           | 3         | 2.65%   |
| SK Hynix BC511                                                                   | 2         | 1.77%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 2         | 1.77%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 2         | 1.77%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 2         | 1.77%   |
| Sandisk Non-Volatile memory controller                                           | 2         | 1.77%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 2         | 1.77%   |
| Intel Volume Management Device NVMe RAID Controller                              | 2         | 1.77%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 2         | 1.77%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 2         | 1.77%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 1.77%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 1.77%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 2         | 1.77%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 2         | 1.77%   |
| SK Hynix Gold P31 SSD                                                            | 1         | 0.88%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 0.88%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                             | 1         | 0.88%   |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                                       | 1         | 0.88%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                     | 1         | 0.88%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                 | 1         | 0.88%   |
| Nvidia MCP55 SATA Controller                                                     | 1         | 0.88%   |
| Nvidia MCP55 IDE                                                                 | 1         | 0.88%   |
| Kingston Company Company Non-Volatile memory controller                          | 1         | 0.88%   |
| Kingston Company KC2000 NVMe SSD                                                 | 1         | 0.88%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                       | 1         | 0.88%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 1         | 0.88%   |
| Intel SSD 660P Series                                                            | 1         | 0.88%   |
| Intel SATA Controller [RAID mode]                                                | 1         | 0.88%   |
| Intel Non-Volatile memory controller                                             | 1         | 0.88%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 1         | 0.88%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 1         | 0.88%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 0.88%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 0.88%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 0.88%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 1         | 0.88%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                             | 1         | 0.88%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1         | 0.88%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                           | 1         | 0.88%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 1         | 0.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 1         | 0.88%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 1         | 0.88%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 1         | 0.88%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 1         | 0.88%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 1         | 0.88%   |
| Broadcom / LSI SAS1068E PCI-Express Fusion-MPT SAS                               | 1         | 0.88%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 53        | 54.08%  |
| NVMe | 30        | 30.61%  |
| IDE  | 8         | 8.16%   |
| RAID | 6         | 6.12%   |
| SCSI | 1         | 1.02%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 62        | 79.49%  |
| AMD    | 16        | 20.51%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 7 5800H with Radeon Graphics        | 3         | 3.85%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 2.56%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 2.56%   |
| Intel Core i7-5820K CPU @ 3.30GHz             | 2         | 2.56%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 2.56%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 2.56%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 2.56%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 2         | 2.56%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 2         | 2.56%   |
| Intel Xeon CPU W3565 @ 3.20GHz                | 1         | 1.28%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz           | 1         | 1.28%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 1.28%   |
| Intel Pentium M processor 1.80GHz             | 1         | 1.28%   |
| Intel Core i9-10850K CPU @ 3.60GHz            | 1         | 1.28%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 1.28%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 1.28%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 1.28%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 1         | 1.28%   |
| Intel Core i7-3720QM CPU @ 2.60GHz            | 1         | 1.28%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 1         | 1.28%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 1         | 1.28%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 1         | 1.28%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 1.28%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 1         | 1.28%   |
| Intel Core i7 CPU M 620 @ 2.67GHz             | 1         | 1.28%   |
| Intel Core i5-9600K CPU @ 3.70GHz             | 1         | 1.28%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 1.28%   |
| Intel Core i5-4690K CPU @ 3.50GHz             | 1         | 1.28%   |
| Intel Core i5-4570T CPU @ 2.90GHz             | 1         | 1.28%   |
| Intel Core i5-4300M CPU @ 2.60GHz             | 1         | 1.28%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 1         | 1.28%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 1.28%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 1         | 1.28%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 1         | 1.28%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 1         | 1.28%   |
| Intel Core i5-2400S CPU @ 2.50GHz             | 1         | 1.28%   |
| Intel Core i5-10500H CPU @ 2.50GHz            | 1         | 1.28%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 1         | 1.28%   |
| Intel Core i3-4130 CPU @ 3.40GHz              | 1         | 1.28%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 1         | 1.28%   |
| Intel Core i3-2328M CPU @ 2.20GHz             | 1         | 1.28%   |
| Intel Core i3 CPU 540 @ 3.07GHz               | 1         | 1.28%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 1         | 1.28%   |
| Intel Core 2 Duo CPU T5250 @ 1.50GHz          | 1         | 1.28%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 1         | 1.28%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz          | 1         | 1.28%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 1         | 1.28%   |
| Intel Celeron CPU N3150 @ 1.60GHz             | 1         | 1.28%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 1         | 1.28%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 1         | 1.28%   |
| Intel Atom CPU Z520 @ 1.33GHz                 | 1         | 1.28%   |
| Intel Atom CPU Z3735G @ 1.33GHz               | 1         | 1.28%   |
| Intel 12th Gen Core i7-12700H                 | 1         | 1.28%   |
| Intel 11th Gen Core i9-11980HK @ 2.60GHz      | 1         | 1.28%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 1         | 1.28%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1         | 1.28%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 1         | 1.28%   |
| AMD Sempron SI-42                             | 1         | 1.28%   |
| AMD Ryzen Threadripper PRO 3945WX 12-Cores    | 1         | 1.28%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 1         | 1.28%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i7          | 19        | 24.36%  |
| Intel Core i5          | 19        | 24.36%  |
| AMD Ryzen 7            | 7         | 8.97%   |
| Other                  | 6         | 7.69%   |
| Intel Core i3          | 4         | 5.13%   |
| Intel Core 2 Duo       | 4         | 5.13%   |
| Intel Celeron          | 4         | 5.13%   |
| Intel Xeon             | 2         | 2.56%   |
| Intel Atom             | 2         | 2.56%   |
| AMD Ryzen 9            | 2         | 2.56%   |
| AMD Ryzen 5            | 2         | 2.56%   |
| AMD Ryzen 3            | 2         | 2.56%   |
| Intel Pentium Silver   | 1         | 1.28%   |
| Intel Pentium M        | 1         | 1.28%   |
| Intel Core i9          | 1         | 1.28%   |
| AMD Sempron            | 1         | 1.28%   |
| AMD Ryzen Threadripper | 1         | 1.28%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 28        | 35.9%   |
| 2      | 26        | 33.33%  |
| 8      | 8         | 10.26%  |
| 6      | 8         | 10.26%  |
| 12     | 3         | 3.85%   |
| 1      | 3         | 3.85%   |
| 14     | 1         | 1.28%   |
| 10     | 1         | 1.28%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 77        | 98.72%  |
| 2      | 1         | 1.28%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 58        | 74.36%  |
| 1      | 20        | 25.64%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 76        | 97.44%  |
| 32-bit         | 2         | 2.56%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 8         | 10.26%  |
| 0x306a9    | 7         | 8.97%   |
| 0x206a7    | 5         | 6.41%   |
| 0x20655    | 4         | 5.13%   |
| 0xa0652    | 3         | 3.85%   |
| 0x806c1    | 3         | 3.85%   |
| 0x406e3    | 3         | 3.85%   |
| 0x306c3    | 3         | 3.85%   |
| 0x0a50000c | 3         | 3.85%   |
| 0x806ea    | 2         | 2.56%   |
| 0x6fd      | 2         | 2.56%   |
| 0x506e3    | 2         | 2.56%   |
| 0x306f2    | 2         | 2.56%   |
| 0x30678    | 2         | 2.56%   |
| 0x08701021 | 2         | 2.56%   |
| 0xa0655    | 1         | 1.28%   |
| 0x906ed    | 1         | 1.28%   |
| 0x906ea    | 1         | 1.28%   |
| 0x906a3    | 1         | 1.28%   |
| 0x806ec    | 1         | 1.28%   |
| 0x806eb    | 1         | 1.28%   |
| 0x806e9    | 1         | 1.28%   |
| 0x806d1    | 1         | 1.28%   |
| 0x706e5    | 1         | 1.28%   |
| 0x706a8    | 1         | 1.28%   |
| 0x706a1    | 1         | 1.28%   |
| 0x6fb      | 1         | 1.28%   |
| 0x6d6      | 1         | 1.28%   |
| 0x406c4    | 1         | 1.28%   |
| 0x406c3    | 1         | 1.28%   |
| 0x106e5    | 1         | 1.28%   |
| 0x106c2    | 1         | 1.28%   |
| 0x1067a    | 1         | 1.28%   |
| 0x0a50000b | 1         | 1.28%   |
| 0x0a201016 | 1         | 1.28%   |
| 0x0a201009 | 1         | 1.28%   |
| 0x08608103 | 1         | 1.28%   |
| 0x08600106 | 1         | 1.28%   |
| 0x08301039 | 1         | 1.28%   |
| 0x08108102 | 1         | 1.28%   |
| 0x0800820d | 1         | 1.28%   |
| 0x02000057 | 1         | 1.28%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Haswell          | 8         | 10.26%  |
| KabyLake         | 7         | 8.97%   |
| IvyBridge        | 7         | 8.97%   |
| Zen 3            | 6         | 7.69%   |
| SandyBridge      | 6         | 7.69%   |
| Westmere         | 5         | 6.41%   |
| Skylake          | 5         | 6.41%   |
| Zen 2            | 4         | 5.13%   |
| Silvermont       | 4         | 5.13%   |
| CometLake        | 4         | 5.13%   |
| Zen+             | 3         | 3.85%   |
| TigerLake        | 3         | 3.85%   |
| Core             | 3         | 3.85%   |
| Nehalem          | 2         | 2.56%   |
| Icelake          | 2         | 2.56%   |
| Goldmont plus    | 2         | 2.56%   |
| Penryn           | 1         | 1.28%   |
| P6               | 1         | 1.28%   |
| K8 Hammer        | 1         | 1.28%   |
| K8 & K10 hybrid  | 1         | 1.28%   |
| Bonnell          | 1         | 1.28%   |
| Alderlake Hybrid | 1         | 1.28%   |
| Unknown          | 1         | 1.28%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 51        | 50.5%   |
| Nvidia | 30        | 29.7%   |
| AMD    | 20        | 19.8%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 6         | 5.77%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 6         | 5.77%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 3         | 2.88%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 2.88%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 2.88%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 2.88%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 2.88%   |
| AMD Cezanne                                                                              | 3         | 2.88%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 1.92%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 2         | 1.92%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 2         | 1.92%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 1.92%   |
| Intel UHD Graphics 620                                                                   | 2         | 1.92%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 1.92%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 1.92%   |
| Intel HD Graphics 530                                                                    | 2         | 1.92%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.92%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 1.92%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 1.92%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 1.92%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                                     | 2         | 1.92%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.96%   |
| Nvidia TU117M                                                                            | 1         | 0.96%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.96%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                    | 1         | 0.96%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 0.96%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 0.96%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.96%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1         | 0.96%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 0.96%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 0.96%   |
| Nvidia GK208 [GeForce GT 635]                                                            | 1         | 0.96%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 1         | 0.96%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.96%   |
| Nvidia GF108M [GeForce GT 550M]                                                          | 1         | 0.96%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 1         | 0.96%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 1         | 0.96%   |
| Nvidia GA107BM [GeForce RTX 3050 Ti Mobile]                                              | 1         | 0.96%   |
| Nvidia G94GL [Quadro FX 1800]                                                            | 1         | 0.96%   |
| Nvidia G86 [GeForce 8500 GT]                                                             | 1         | 0.96%   |
| Nvidia G71GL [Quadro FX 3500]                                                            | 1         | 0.96%   |
| Nvidia C77 [GeForce 8200M G]                                                             | 1         | 0.96%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1         | 0.96%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 0.96%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                                      | 1         | 0.96%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 1         | 0.96%   |
| Intel Iris Plus Graphics G7                                                              | 1         | 0.96%   |
| Intel HD Graphics 620                                                                    | 1         | 0.96%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 1         | 0.96%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 0.96%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 0.96%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 0.96%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 1         | 0.96%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 1         | 0.96%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 1         | 0.96%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 1         | 0.96%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 1         | 0.96%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 1         | 0.96%   |
| AMD RV730/M96-XT [Mobility Radeon HD 4670]                                               | 1         | 0.96%   |
| AMD RV350/M10 / RV360/M11 [Mobility Radeon 9600 (PRO) / 9700]                            | 1         | 0.96%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 31        | 39.74%  |
| Intel + Nvidia | 14        | 17.95%  |
| 1 x Nvidia     | 13        | 16.67%  |
| 1 x AMD        | 13        | 16.67%  |
| Intel + AMD    | 3         | 3.85%   |
| AMD + Nvidia   | 3         | 3.85%   |
| 2 x AMD        | 1         | 1.28%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 57        | 73.08%  |
| Proprietary | 18        | 23.08%  |
| Unknown     | 3         | 3.85%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 52        | 66.67%  |
| 0.01-0.5   | 7         | 8.97%   |
| 7.01-8.0   | 6         | 7.69%   |
| 3.01-4.0   | 6         | 7.69%   |
| 0.51-1.0   | 5         | 6.41%   |
| 8.01-16.0  | 2         | 2.56%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 11        | 12.79%  |
| LG Display              | 8         | 9.3%    |
| AU Optronics            | 8         | 9.3%    |
| Samsung Electronics     | 7         | 8.14%   |
| Dell                    | 5         | 5.81%   |
| PANDA                   | 4         | 4.65%   |
| BOE                     | 4         | 4.65%   |
| Ancor Communications    | 4         | 4.65%   |
| Sharp                   | 3         | 3.49%   |
| Hewlett-Packard         | 3         | 3.49%   |
| Fujitsu Siemens         | 3         | 3.49%   |
| Acer                    | 3         | 3.49%   |
| Sony                    | 2         | 2.33%   |
| Philips                 | 2         | 2.33%   |
| Medion                  | 2         | 2.33%   |
| Chi Mei Optoelectronics | 2         | 2.33%   |
| Apple                   | 2         | 2.33%   |
| AOC                     | 2         | 2.33%   |
| Vizio                   | 1         | 1.16%   |
| SAC                     | 1         | 1.16%   |
| Panasonic               | 1         | 1.16%   |
| NEC Computers           | 1         | 1.16%   |
| Lenovo                  | 1         | 1.16%   |
| Iiyama                  | 1         | 1.16%   |
| Hitachi                 | 1         | 1.16%   |
| Grundig                 | 1         | 1.16%   |
| Goldstar                | 1         | 1.16%   |
| Gigabyte Technology     | 1         | 1.16%   |
| CPT                     | 1         | 1.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 2         | 2.27%   |
| Medion MD22322 MEB8101 2560x1440 699x393mm 31.6-inch                     | 2         | 2.27%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 2         | 2.27%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 2         | 2.27%   |
| Vizio M220MV VIZ0062 1920x1080 480x270mm 21.7-inch                       | 1         | 1.14%   |
| Sony Nvidia Defaul t Flat Panel SNY06FA 1600x900 360x200mm 16.2-inch     | 1         | 1.14%   |
| Sony Nvidia Defaul t Flat Panel MS_0025 1920x1080 360x200mm 16.2-inch    | 1         | 1.14%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch                  | 1         | 1.14%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch                  | 1         | 1.14%   |
| Sharp LCD Monitor SHP1445 3840x2160 350x190mm 15.7-inch                  | 1         | 1.14%   |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                         | 1         | 1.14%   |
| Samsung Electronics S23B300 SAM08AF 1920x1080 510x287mm 23.0-inch        | 1         | 1.14%   |
| Samsung Electronics LCD Monitor SEC4245 1280x800 331x207mm 15.4-inch     | 1         | 1.14%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 309x174mm 14.0-inch     | 1         | 1.14%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 340x190mm 15.3-inch    | 1         | 1.14%   |
| Samsung Electronics C32JG5x SAM0FE0 2560x1440 700x390mm 31.5-inch        | 1         | 1.14%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 1         | 1.14%   |
| SAC DP_FREESYNC SAC2700 2560x1440 597x336mm 27.0-inch                    | 1         | 1.14%   |
| Philips PHL 276E9Q PHLC17B 1920x1080 598x336mm 27.0-inch                 | 1         | 1.14%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                  | 1         | 1.14%   |
| PANDA LCD Monitor NCP0052 1920x1080 309x174mm 14.0-inch                  | 1         | 1.14%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                  | 1         | 1.14%   |
| Panasonic VVX16T029D00 MEI96A2 2880x1620 344x193mm 15.5-inch             | 1         | 1.14%   |
| NEC Computers EA221WM NEC673D 1680x1050 474x296mm 22.0-inch              | 1         | 1.14%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch            | 1         | 1.14%   |
| LG Display LCD Monitor LGD06E2 1920x1080 344x194mm 15.5-inch             | 1         | 1.14%   |
| LG Display LCD Monitor LGD0570 1920x1080 344x194mm 15.5-inch             | 1         | 1.14%   |
| LG Display LCD Monitor LGD0555 1536x1024 263x175mm 12.4-inch             | 1         | 1.14%   |
| LG Display LCD Monitor LGD03DB 1366x768 345x194mm 15.6-inch              | 1         | 1.14%   |
| LG Display LCD Monitor LGD024D 1366x768 294x166mm 13.3-inch              | 1         | 1.14%   |
| Lenovo LEN T2454pA LEN60C9 1920x1200 518x324mm 24.1-inch                 | 1         | 1.14%   |
| Iiyama PL2776HD IVM6605 1920x1080 598x336mm 27.0-inch                    | 1         | 1.14%   |
| Hitachi HISENSE HEC002F 3840x2160 1872x1053mm 84.6-inch                  | 1         | 1.14%   |
| Hewlett-Packard X27q HPN3725 2560x1440 600x340mm 27.2-inch               | 1         | 1.14%   |
| Hewlett-Packard X27q HPN3724 2560x1440 600x340mm 27.2-inch               | 1         | 1.14%   |
| Hewlett-Packard w2207 HWP26A8 1680x1050 473x296mm 22.0-inch              | 1         | 1.14%   |
| Hewlett-Packard LA2306 HWP294B 1920x1080 509x286mm 23.0-inch             | 1         | 1.14%   |
| Grundig WXGA GRU4448 1600x1200                                           | 1         | 1.14%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                  | 1         | 1.14%   |
| Gigabyte Technology G34WQC GBT3400 3440x1440 797x334mm 34.0-inch         | 1         | 1.14%   |
| Fujitsu Siemens L24W-2 FUS077A 1920x1200 520x320mm 24.0-inch             | 1         | 1.14%   |
| Fujitsu Siemens B22W-7 LED FUS0838 1680x1050 474x296mm 22.0-inch         | 1         | 1.14%   |
| Fujitsu Siemens B22W-5 ECO FUS07C3 1680x1050 474x296mm 22.0-inch         | 1         | 1.14%   |
| Dell U2719D DEL415A 2560x1440 597x336mm 27.0-inch                        | 1         | 1.14%   |
| Dell SR2320L DELF03A 1920x1080 510x290mm 23.1-inch                       | 1         | 1.14%   |
| Dell S3422DW DELD103 3440x1440 800x330mm 34.1-inch                       | 1         | 1.14%   |
| Dell E190S DELA04B 1280x1024 376x301mm 19.0-inch                         | 1         | 1.14%   |
| Dell 1908FP DEL4025 1280x1024 376x301mm 19.0-inch                        | 1         | 1.14%   |
| Dell 1907FP DEL4014 1280x1024 376x301mm 19.0-inch                        | 1         | 1.14%   |
| CPT LCD Monitor CPT1C21 1366x768 256x144mm 11.6-inch                     | 1         | 1.14%   |
| Chimei Innolux P140ZKA-BZ1 CMN8C03 2160x1440 296x197mm 14.0-inch         | 1         | 1.14%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 1         | 1.14%   |
| Chimei Innolux LCD Monitor CMN15D6 1920x1080 344x193mm 15.5-inch         | 1         | 1.14%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 1         | 1.14%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch          | 1         | 1.14%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch          | 1         | 1.14%   |
| Chimei Innolux LCD Monitor CMN1491 1366x768 309x174mm 14.0-inch          | 1         | 1.14%   |
| Chimei Innolux LCD Monitor CMN1402 1920x1080 309x173mm 13.9-inch         | 1         | 1.14%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 1         | 1.14%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 1         | 1.14%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 33        | 40.74%  |
| 1366x768 (WXGA)    | 14        | 17.28%  |
| 3840x2160 (4K)     | 7         | 8.64%   |
| 2560x1440 (QHD)    | 6         | 7.41%   |
| 1680x1050 (WSXGA+) | 3         | 3.7%    |
| 1280x1024 (SXGA)   | 3         | 3.7%    |
| 3440x1440          | 2         | 2.47%   |
| 1920x1200 (WUXGA)  | 2         | 2.47%   |
| 1600x900 (HD+)     | 2         | 2.47%   |
| 1280x800 (WXGA)    | 2         | 2.47%   |
| 3840x2400          | 1         | 1.23%   |
| 2736x1824          | 1         | 1.23%   |
| 2560x1080          | 1         | 1.23%   |
| 2256x1504          | 1         | 1.23%   |
| 2160x1440          | 1         | 1.23%   |
| 1440x900 (WXGA+)   | 1         | 1.23%   |
| 1360x768           | 1         | 1.23%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 26        | 30.95%  |
| 27      | 8         | 9.52%   |
| 13      | 8         | 9.52%   |
| 24      | 5         | 5.95%   |
| 23      | 5         | 5.95%   |
| 17      | 5         | 5.95%   |
| 14      | 5         | 5.95%   |
| 31      | 4         | 4.76%   |
| 34      | 3         | 3.57%   |
| 22      | 3         | 3.57%   |
| 19      | 3         | 3.57%   |
| 21      | 2         | 2.38%   |
| 11      | 2         | 2.38%   |
| 84      | 1         | 1.19%   |
| 54      | 1         | 1.19%   |
| 26      | 1         | 1.19%   |
| 12      | 1         | 1.19%   |
| Unknown | 1         | 1.19%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 34        | 40.96%  |
| 501-600     | 18        | 21.69%  |
| 201-300     | 8         | 9.64%   |
| 351-400     | 7         | 8.43%   |
| 401-500     | 6         | 7.23%   |
| 601-700     | 4         | 4.82%   |
| 701-800     | 3         | 3.61%   |
| 1501-2000   | 1         | 1.2%    |
| 1001-1500   | 1         | 1.2%    |
| Unknown     | 1         | 1.2%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 59        | 75.64%  |
| 16/10 | 10        | 12.82%  |
| 5/4   | 3         | 3.85%   |
| 3/2   | 3         | 3.85%   |
| 21/9  | 3         | 3.85%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 26        | 30.95%  |
| 201-250        | 12        | 14.29%  |
| 81-90          | 11        | 13.1%   |
| 301-350        | 8         | 9.52%   |
| 351-500        | 7         | 8.33%   |
| 251-300        | 4         | 4.76%   |
| 121-130        | 4         | 4.76%   |
| 71-80          | 3         | 3.57%   |
| 151-200        | 3         | 3.57%   |
| More than 1000 | 2         | 2.38%   |
| 51-60          | 2         | 2.38%   |
| 141-150        | 1         | 1.19%   |
| Unknown        | 1         | 1.19%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 30        | 37.04%  |
| 121-160       | 23        | 28.4%   |
| 101-120       | 18        | 22.22%  |
| More than 240 | 4         | 4.94%   |
| 161-240       | 4         | 4.94%   |
| 1-50          | 1         | 1.23%   |
| Unknown       | 1         | 1.23%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 57        | 73.08%  |
| 2     | 15        | 19.23%  |
| 3     | 3         | 3.85%   |
| 0     | 3         | 3.85%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 41        | 34.17%  |
| Realtek Semiconductor    | 36        | 30%     |
| Qualcomm Atheros         | 16        | 13.33%  |
| Broadcom                 | 6         | 5%      |
| TP-Link                  | 4         | 3.33%   |
| Marvell Technology Group | 4         | 3.33%   |
| MEDIATEK                 | 3         | 2.5%    |
| Ralink Technology        | 2         | 1.67%   |
| Nvidia                   | 2         | 1.67%   |
| Microsoft                | 1         | 0.83%   |
| Edimax Technology        | 1         | 0.83%   |
| Dell                     | 1         | 0.83%   |
| Broadcom Limited         | 1         | 0.83%   |
| ASUSTek Computer         | 1         | 0.83%   |
| Aquantia                 | 1         | 0.83%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 30        | 21.58%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 4         | 2.88%   |
| Intel Wireless 8260                                                            | 4         | 2.88%   |
| Intel Wi-Fi 6 AX200                                                            | 4         | 2.88%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 3         | 2.16%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter                  | 3         | 2.16%   |
| Intel Wireless 7260                                                            | 3         | 2.16%   |
| Intel I211 Gigabit Network Connection                                          | 3         | 2.16%   |
| Intel Ethernet Connection I217-LM                                              | 3         | 2.16%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                   | 2         | 1.44%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 2         | 1.44%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 2         | 1.44%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 2         | 1.44%   |
| Intel Wireless 8265 / 8275                                                     | 2         | 1.44%   |
| Intel Wireless 7265                                                            | 2         | 1.44%   |
| Intel Ethernet Connection I219-V                                               | 2         | 1.44%   |
| Intel Ethernet Connection (2) I218-V                                           | 2         | 1.44%   |
| Intel Comet Lake PCH CNVi WiFi                                                 | 2         | 1.44%   |
| Intel Centrino Advanced-N 6200                                                 | 2         | 1.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 2         | 1.44%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 1.44%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 2         | 1.44%   |
| TP-Link USB 10/100/1000 LAN                                                    | 1         | 0.72%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                         | 1         | 0.72%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                             | 1         | 0.72%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                       | 1         | 0.72%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 1         | 0.72%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                | 1         | 0.72%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                            | 1         | 0.72%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 0.72%   |
| Ralink RT2870/RT3070 Wireless Adapter                                          | 1         | 0.72%   |
| Ralink RT2070 Wireless Adapter                                                 | 1         | 0.72%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 1         | 0.72%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.72%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 1         | 0.72%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.72%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1         | 0.72%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                     | 1         | 0.72%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                               | 1         | 0.72%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                 | 1         | 0.72%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                 | 1         | 0.72%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 0.72%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.72%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)        | 1         | 0.72%   |
| Nvidia MCP77 Ethernet                                                          | 1         | 0.72%   |
| Nvidia MCP55 Ethernet                                                          | 1         | 0.72%   |
| Microsoft RTL8153 GigE [Surface Ethernet Adapter]                              | 1         | 0.72%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.72%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 0.72%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 1         | 0.72%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 0.72%   |
| Intel Wireless 3165                                                            | 1         | 0.72%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                         | 1         | 0.72%   |
| Intel Wi-Fi 6 AX201                                                            | 1         | 0.72%   |
| Intel Tiger Lake PCH CNVi WiFi                                                 | 1         | 0.72%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                          | 1         | 0.72%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                       | 1         | 0.72%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                | 1         | 0.72%   |
| Intel Ethernet Controller I225-V                                               | 1         | 0.72%   |
| Intel Ethernet Connection I217-V                                               | 1         | 0.72%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 33        | 50%     |
| Qualcomm Atheros      | 12        | 18.18%  |
| Realtek Semiconductor | 7         | 10.61%  |
| TP-Link               | 3         | 4.55%   |
| MEDIATEK              | 3         | 4.55%   |
| Broadcom              | 3         | 4.55%   |
| Ralink Technology     | 2         | 3.03%   |
| Edimax Technology     | 1         | 1.52%   |
| Broadcom Limited      | 1         | 1.52%   |
| ASUSTek Computer      | 1         | 1.52%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 6.06%   |
| Intel Wireless 8260                                                     | 4         | 6.06%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 6.06%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 4.55%   |
| Intel Wireless 7260                                                     | 3         | 4.55%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 3.03%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 3.03%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 3.03%   |
| Intel Wireless 8265 / 8275                                              | 2         | 3.03%   |
| Intel Wireless 7265                                                     | 2         | 3.03%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 3.03%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 3.03%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                  | 1         | 1.52%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 1.52%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 1.52%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.52%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 1.52%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                     | 1         | 1.52%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 1.52%   |
| Ralink RT2070 Wireless Adapter                                          | 1         | 1.52%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 1.52%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 1.52%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 1         | 1.52%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 1.52%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 1.52%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.52%   |
| Intel Wireless 3165                                                     | 1         | 1.52%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1         | 1.52%   |
| Intel Wi-Fi 6 AX201                                                     | 1         | 1.52%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 1         | 1.52%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 1.52%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 1         | 1.52%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 1         | 1.52%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1         | 1.52%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 1         | 1.52%   |
| Intel Centrino Advanced-N 6235                                          | 1         | 1.52%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 1.52%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 1.52%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 1         | 1.52%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 1         | 1.52%   |
| Edimax RTL8192S WLAN Adapter                                            | 1         | 1.52%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 1         | 1.52%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 1         | 1.52%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 1         | 1.52%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 1         | 1.52%   |
| ASUS 802.11ac NIC                                                       | 1         | 1.52%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 34        | 49.28%  |
| Intel                    | 16        | 23.19%  |
| Qualcomm Atheros         | 6         | 8.7%    |
| Marvell Technology Group | 4         | 5.8%    |
| Broadcom                 | 4         | 5.8%    |
| Nvidia                   | 2         | 2.9%    |
| TP-Link                  | 1         | 1.45%   |
| Microsoft                | 1         | 1.45%   |
| Aquantia                 | 1         | 1.45%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 30        | 41.67%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 3         | 4.17%   |
| Intel I211 Gigabit Network Connection                                          | 3         | 4.17%   |
| Intel Ethernet Connection I217-LM                                              | 3         | 4.17%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 2         | 2.78%   |
| Intel Ethernet Connection I219-V                                               | 2         | 2.78%   |
| Intel Ethernet Connection (2) I218-V                                           | 2         | 2.78%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 2         | 2.78%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 2.78%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 2         | 2.78%   |
| TP-Link USB 10/100/1000 LAN                                                    | 1         | 1.39%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 1.39%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 1.39%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 1.39%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1         | 1.39%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                     | 1         | 1.39%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 1.39%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 1.39%   |
| Nvidia MCP77 Ethernet                                                          | 1         | 1.39%   |
| Nvidia MCP55 Ethernet                                                          | 1         | 1.39%   |
| Microsoft RTL8153 GigE [Surface Ethernet Adapter]                              | 1         | 1.39%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 1.39%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 1.39%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 1         | 1.39%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 1.39%   |
| Intel Ethernet Controller I225-V                                               | 1         | 1.39%   |
| Intel Ethernet Connection I217-V                                               | 1         | 1.39%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 1         | 1.39%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                              | 1         | 1.39%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 1         | 1.39%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]              | 1         | 1.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 67        | 51.54%  |
| WiFi     | 62        | 47.69%  |
| Modem    | 1         | 0.77%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 51        | 60.71%  |
| Ethernet | 33        | 39.29%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 48        | 61.54%  |
| 1     | 28        | 35.9%   |
| 3     | 1         | 1.28%   |
| 0     | 1         | 1.28%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 57        | 73.08%  |
| Yes  | 21        | 26.92%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 23        | 46.94%  |
| Apple                           | 5         | 10.2%   |
| Realtek Semiconductor           | 4         | 8.16%   |
| Qualcomm Atheros Communications | 4         | 8.16%   |
| IMC Networks                    | 3         | 6.12%   |
| Foxconn / Hon Hai               | 3         | 6.12%   |
| Cambridge Silicon Radio         | 2         | 4.08%   |
| ASUSTek Computer                | 2         | 4.08%   |
| Lite-On Technology              | 1         | 2.04%   |
| Hewlett-Packard                 | 1         | 2.04%   |
| Dell                            | 1         | 2.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 10        | 20.41%  |
| Intel AX201 Bluetooth                                                               | 5         | 10.2%   |
| Intel AX200 Bluetooth                                                               | 4         | 8.16%   |
| Realtek Bluetooth Radio                                                             | 3         | 6.12%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 2         | 4.08%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 2         | 4.08%   |
| IMC Networks Wireless_Device                                                        | 2         | 4.08%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 4.08%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 2         | 4.08%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 2         | 4.08%   |
| Apple Bluetooth USB Host Controller                                                 | 2         | 4.08%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 1         | 2.04%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 2.04%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 2.04%   |
| Lite-On Wireless_Device                                                             | 1         | 2.04%   |
| Intel Bluetooth Device                                                              | 1         | 2.04%   |
| Intel AX210 Bluetooth                                                               | 1         | 2.04%   |
| IMC Networks Bluetooth Radio                                                        | 1         | 2.04%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 2.04%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 2.04%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 2.04%   |
| ASUS Broadcom Bluetooth 2.1                                                         | 1         | 2.04%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                               | 1         | 2.04%   |
| Apple Bluetooth HCI                                                                 | 1         | 2.04%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 60        | 52.17%  |
| Nvidia              | 22        | 19.13%  |
| AMD                 | 20        | 17.39%  |
| ROCCAT              | 2         | 1.74%   |
| Creative Labs       | 2         | 1.74%   |
| C-Media Electronics | 2         | 1.74%   |
| Unknown             | 1         | 0.87%   |
| Texas Instruments   | 1         | 0.87%   |
| Schiit Audio        | 1         | 0.87%   |
| Razer USA           | 1         | 0.87%   |
| Plantronics         | 1         | 0.87%   |
| GN Netcom           | 1         | 0.87%   |
| Unknown             | 1         | 0.87%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 9         | 6.87%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 8         | 6.11%   |
| Nvidia Audio device                                                                               | 6         | 4.58%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 6         | 4.58%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 4.58%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 3.82%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 5         | 3.82%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 3.05%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 3.05%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 4         | 3.05%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 3         | 2.29%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 2.29%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 2.29%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 3         | 2.29%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 3         | 2.29%   |
| ROCCAT Khan AIMO                                                                                  | 2         | 1.53%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 1.53%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 1.53%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 1.53%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 1.53%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.53%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 1.53%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 1.53%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                                     | 2         | 1.53%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 2         | 1.53%   |
| Unknown Realtek USB Audio Rear                                                                    | 1         | 0.76%   |
| Unknown Realtek USB Audio Front                                                                   | 1         | 0.76%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                                                 | 1         | 0.76%   |
| Schiit Audio I'm Fulla Schiit                                                                     | 1         | 0.76%   |
| Razer USA Kraken Tournament Edition                                                               | 1         | 0.76%   |
| Plantronics BT600                                                                                 | 1         | 0.76%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.76%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.76%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 1         | 0.76%   |
| Nvidia MCP55 High Definition Audio                                                                | 1         | 0.76%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.76%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.76%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.76%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 1         | 0.76%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.76%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                                   | 1         | 0.76%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 0.76%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 0.76%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 0.76%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 0.76%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 0.76%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.76%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 1         | 0.76%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 1         | 0.76%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 1         | 0.76%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 1         | 0.76%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 1         | 0.76%   |
| GN Netcom Jabra BIZ 2300                                                                          | 1         | 0.76%   |
| C-Media Electronics USB Advanced Audio Device                                                     | 1         | 0.76%   |
| C-Media Electronics Blue Snowball                                                                 | 1         | 0.76%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 1         | 0.76%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 1         | 0.76%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 1         | 0.76%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 0.76%   |
| AMD Hawaii HDMI Audio [Radeon R9 290/290X / 390/390X]                                             | 1         | 0.76%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 18        | 20.69%  |
| SK Hynix            | 16        | 18.39%  |
| Unknown             | 14        | 16.09%  |
| Kingston            | 8         | 9.2%    |
| Micron Technology   | 7         | 8.05%   |
| Corsair             | 7         | 8.05%   |
| Crucial             | 5         | 5.75%   |
| G.Skill             | 4         | 4.6%    |
| Smart               | 2         | 2.3%    |
| Unknown             | 2         | 2.3%    |
| Unknown (ABCD)      | 1         | 1.15%   |
| PNY                 | 1         | 1.15%   |
| Elpida              | 1         | 1.15%   |
| Avant               | 1         | 1.15%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3                               | 4         | 4.21%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 3.16%   |
| Unknown RAM Module 8GB SODIMM DDR3                               | 2         | 2.11%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 2         | 2.11%   |
| Samsung RAM Module 2GB SODIMM DDR3 1333MT/s                      | 2         | 2.11%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 2.11%   |
| Crucial RAM CT102464BF160B.C16 8192MB SODIMM DDR3 1600MT/s       | 2         | 2.11%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s           | 2         | 2.11%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 2         | 2.11%   |
| Unknown                                                          | 2         | 2.11%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 1.05%   |
| Unknown RAM Module 4GB DIMM SDRAM                                | 1         | 1.05%   |
| Unknown RAM Module 2GB SODIMM DRAM 667MT/s                       | 1         | 1.05%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 1.05%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 1.05%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 1.05%   |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s                         | 1         | 1.05%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 1.05%   |
| Unknown RAM Module 1GB SODIMM DDR3 1333MT/s                      | 1         | 1.05%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 1         | 1.05%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM DDR4 2400MT/s   | 1         | 1.05%   |
| Smart RAM SH564128FJ8NWRNSQG 4096MB SODIMM DDR3 1600MT/s         | 1         | 1.05%   |
| Smart RAM SF4641G8CK8IEGKSBG 8192MB SODIMM DDR4 2400MT/s         | 1         | 1.05%   |
| SK Hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 1         | 1.05%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.05%   |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 1.05%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.05%   |
| SK Hynix RAM HMT351S6EFR8A 4096MB SODIMM DDR3 1600MT/s           | 1         | 1.05%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.05%   |
| SK Hynix RAM HMT351S6AFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.05%   |
| SK Hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 1.05%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2048MB SODIMM DDR3 1333MT/s        | 1         | 1.05%   |
| SK Hynix RAM HMT125S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 1         | 1.05%   |
| SK Hynix RAM HMCG66MEBSA095N 8GB SODIMM 4800MT/s                 | 1         | 1.05%   |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.05%   |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s        | 1         | 1.05%   |
| SK Hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 1.05%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 1.05%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 1         | 1.05%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.05%   |
| SK Hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s           | 1         | 1.05%   |
| SK Hynix RAM H9HCNNNCPNALHR-NEE 8GB Row Of Chips LPDDR4 3733MT/s | 1         | 1.05%   |
| SK Hynix RAM 0000000000-00000 8GB SODIMM DDR4 2400MT/s           | 1         | 1.05%   |
| Samsung RAM Module 4GB SODIMM DDR2 667MT/s                       | 1         | 1.05%   |
| Samsung RAM M471B5773EB0-CK0 2GB SODIMM DDR3 1600MT/s            | 1         | 1.05%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s            | 1         | 1.05%   |
| Samsung RAM M471B5173BH0-CK0 4096MB SODIMM DDR3 1600MT/s         | 1         | 1.05%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.05%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.05%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.05%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 1         | 1.05%   |
| Samsung RAM M393A4K40DB3-CWE 32GB DIMM DDR4 3200MT/s             | 1         | 1.05%   |
| Samsung RAM M386A4G40DM0-CPB 32GB DIMM DDR4 2133MT/s             | 1         | 1.05%   |
| PNY RAM Module 8GB SODIMM DDR3 1333MT/s                          | 1         | 1.05%   |
| Micron RAM Module 8GB SODIMM DDR3 1600MT/s                       | 1         | 1.05%   |
| Micron RAM 8JTF51264AZ-1G6E1 4096MB DIMM DDR3 1600MT/s           | 1         | 1.05%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 1         | 1.05%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 1         | 1.05%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 1         | 1.05%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8192MB SODIMM DDR3 1600MT/s         | 1         | 1.05%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 35        | 46.05%  |
| DDR3    | 29        | 38.16%  |
| DDR2    | 5         | 6.58%   |
| SDRAM   | 2         | 2.63%   |
| LPDDR4  | 2         | 2.63%   |
| DRAM    | 1         | 1.32%   |
| DDR     | 1         | 1.32%   |
| Unknown | 1         | 1.32%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 54        | 72%     |
| DIMM         | 19        | 25.33%  |
| Row Of Chips | 2         | 2.67%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 35        | 41.18%  |
| 4096  | 26        | 30.59%  |
| 2048  | 13        | 15.29%  |
| 16384 | 5         | 5.88%   |
| 32768 | 3         | 3.53%   |
| 1024  | 3         | 3.53%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 14        | 17.95%  |
| 3200    | 13        | 16.67%  |
| 1333    | 8         | 10.26%  |
| 2133    | 7         | 8.97%   |
| Unknown | 7         | 8.97%   |
| 2667    | 6         | 7.69%   |
| 3600    | 4         | 5.13%   |
| 2400    | 4         | 5.13%   |
| 667     | 3         | 3.85%   |
| 3400    | 2         | 2.56%   |
| 4800    | 1         | 1.28%   |
| 4199    | 1         | 1.28%   |
| 3733    | 1         | 1.28%   |
| 3466    | 1         | 1.28%   |
| 1639    | 1         | 1.28%   |
| 1400    | 1         | 1.28%   |
| 1334    | 1         | 1.28%   |
| 1067    | 1         | 1.28%   |
| 333     | 1         | 1.28%   |
| 166     | 1         | 1.28%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 50%     |
| Canon           | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Computers | Percent |
|--------------------------|-----------|---------|
| HP LaserJet P2055 series | 1         | 50%     |
| Canon MF641C             | 1         | 50%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Canon CanoScan N1240U/LiDE 30 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 10        | 20.83%  |
| Acer                                   | 5         | 10.42%  |
| Microdia                               | 4         | 8.33%   |
| Logitech                               | 4         | 8.33%   |
| Realtek Semiconductor                  | 3         | 6.25%   |
| IMC Networks                           | 3         | 6.25%   |
| Sunplus Innovation Technology          | 2         | 4.17%   |
| Lite-On Technology                     | 2         | 4.17%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 4.17%   |
| Apple                                  | 2         | 4.17%   |
| Z-Star Microelectronics                | 1         | 2.08%   |
| Y Media                                | 1         | 2.08%   |
| Suyin                                  | 1         | 2.08%   |
| Silicon Motion                         | 1         | 2.08%   |
| Ricoh                                  | 1         | 2.08%   |
| Quanta                                 | 1         | 2.08%   |
| Primax Electronics                     | 1         | 2.08%   |
| Microsoft                              | 1         | 2.08%   |
| Luxvisions Innotech Limited            | 1         | 2.08%   |
| Goodong Industry                       | 1         | 2.08%   |
| Generalplus Technology                 | 1         | 2.08%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Sunplus Integrated_Webcam_HD                        | 2         | 4.17%   |
| Logitech Webcam C930e                               | 2         | 4.17%   |
| Lite-On HP HD Camera                                | 2         | 4.17%   |
| Acer BisonCam, NB Pro                               | 2         | 4.17%   |
| Z-Star Venus USB2.0 Camera                          | 1         | 2.08%   |
| Y Media USB Camera                                  | 1         | 2.08%   |
| Suyin Sony Visual Communication Camera              | 1         | 2.08%   |
| Silicon Motion Web Camera                           | 1         | 2.08%   |
| Ricoh USB2.0 Camera                                 | 1         | 2.08%   |
| Realtek USB Camera                                  | 1         | 2.08%   |
| Realtek Lenovo EasyCamera                           | 1         | 2.08%   |
| Realtek Integrated Webcam                           | 1         | 2.08%   |
| Quanta HD User Facing                               | 1         | 2.08%   |
| Primax Dell Laptop Integrated Webcam 2Mpix          | 1         | 2.08%   |
| Microsoft LifeCam HD-3000                           | 1         | 2.08%   |
| Microdia Webcam Vitade AF                           | 1         | 2.08%   |
| Microdia WebCam SC-13HDL12639P                      | 1         | 2.08%   |
| Microdia Webcam                                     | 1         | 2.08%   |
| Microdia USB 2.0 Camera                             | 1         | 2.08%   |
| Luxvisions Innotech Limited Integrated Camera       | 1         | 2.08%   |
| Logitech Webcam C270                                | 1         | 2.08%   |
| Logitech StreamCam                                  | 1         | 2.08%   |
| IMC Networks USB2.0 UVC 1.3M WebCam                 | 1         | 2.08%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 1         | 2.08%   |
| IMC Networks Integrated Camera                      | 1         | 2.08%   |
| Goodong Industry USB2.0 HD UVC WebCam               | 1         | 2.08%   |
| Generalplus CAMERA - UVC                            | 1         | 2.08%   |
| Chicony USB2.0 HD UVC WebCam                        | 1         | 2.08%   |
| Chicony USB 2.0 Camera                              | 1         | 2.08%   |
| Chicony thinkpad t430s camera                       | 1         | 2.08%   |
| Chicony Sony Visual Communication Camera            | 1         | 2.08%   |
| Chicony Lenovo EasyCamera                           | 1         | 2.08%   |
| Chicony Integrated Camera                           | 1         | 2.08%   |
| Chicony HP Wide Vision FHD Camera                   | 1         | 2.08%   |
| Chicony HP Webcam [2 MP Macro]                      | 1         | 2.08%   |
| Chicony HD User Facing                              | 1         | 2.08%   |
| Chicony 2.0M UVC WebCam                             | 1         | 2.08%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 1         | 2.08%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 1         | 2.08%   |
| Apple FaceTime HD Camera (Built-in)                 | 1         | 2.08%   |
| Apple Built-in iSight                               | 1         | 2.08%   |
| Acer SunplusIT INC. Integrated Camera               | 1         | 2.08%   |
| Acer Integrated Camera                              | 1         | 2.08%   |
| Acer BisonCam,NB Pro                                | 1         | 2.08%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 4         | 44.44%  |
| Shenzhen Goodix Technology | 3         | 33.33%  |
| Synaptics                  | 1         | 11.11%  |
| AuthenTec                  | 1         | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader   | 2         | 22.22%  |
| Validity Sensors VFS 5011 fingerprint sensor | 2         | 22.22%  |
| Shenzhen Goodix  FingerPrint Device          | 2         | 22.22%  |
| Shenzhen Goodix Fingerprint Reader           | 1         | 11.11%  |
| AuthenTec AES1660 Fingerprint Sensor         | 1         | 11.11%  |
| Unknown                                      | 1         | 11.11%  |

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
| 0     | 55        | 69.62%  |
| 1     | 19        | 24.05%  |
| 2     | 5         | 6.33%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 12        | 44.44%  |
| Fingerprint reader       | 9         | 33.33%  |
| Unassigned class         | 3         | 11.11%  |
| Multimedia controller    | 1         | 3.7%    |
| Communication controller | 1         | 3.7%    |
| Chipcard                 | 1         | 3.7%    |

