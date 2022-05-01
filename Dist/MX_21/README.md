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

Total: 108

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Intel         | V1.3                        | Desktop     | [a01993f2fa](https://linux-hardware.org/?probe=a01993f2fa) | Apr 30, 2022 |
| Dell          | Latitude 3190               | Notebook    | [b88d7076df](https://linux-hardware.org/?probe=b88d7076df) | Apr 25, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [04b51fe1cf](https://linux-hardware.org/?probe=04b51fe1cf) | Apr 25, 2022 |
| Alienware     | m15 R7                      | Notebook    | [77727a1731](https://linux-hardware.org/?probe=77727a1731) | Apr 24, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [4e8b5f940a](https://linux-hardware.org/?probe=4e8b5f940a) | Apr 23, 2022 |
| ASUSTek       | SABERTOOTH X99              | Desktop     | [51cc264c62](https://linux-hardware.org/?probe=51cc264c62) | Apr 22, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [77a6f92da0](https://linux-hardware.org/?probe=77a6f92da0) | Apr 22, 2022 |
| Gigabyte      | B550M S2H                   | Desktop     | [208972e3b5](https://linux-hardware.org/?probe=208972e3b5) | Apr 19, 2022 |
| ASRock        | N3150M                      | Desktop     | [0ee71f6582](https://linux-hardware.org/?probe=0ee71f6582) | Apr 19, 2022 |
| Dell          | Latitude 3190               | Notebook    | [d1542717be](https://linux-hardware.org/?probe=d1542717be) | Apr 18, 2022 |
| Gigabyte      | B550M S2H                   | Desktop     | [1127f26185](https://linux-hardware.org/?probe=1127f26185) | Apr 17, 2022 |
| Sun Micros... | Sun Ultra 40 M2 Workstat... | Server      | [7cc89d3cba](https://linux-hardware.org/?probe=7cc89d3cba) | Apr 14, 2022 |
| Sun Micros... | Sun Ultra 40 M2 Workstat... | Server      | [5cd6adf199](https://linux-hardware.org/?probe=5cd6adf199) | Apr 14, 2022 |
| Dell          | Latitude 3190               | Notebook    | [5369d059e6](https://linux-hardware.org/?probe=5369d059e6) | Apr 11, 2022 |
| Gigabyte      | G5 KC                       | Notebook    | [fc21d0150f](https://linux-hardware.org/?probe=fc21d0150f) | Apr 10, 2022 |
| Acer          | Aspire A515-56              | Notebook    | [46f9e8b140](https://linux-hardware.org/?probe=46f9e8b140) | Apr 07, 2022 |
| Acer          | Aspire A515-56              | Notebook    | [db6408f394](https://linux-hardware.org/?probe=db6408f394) | Apr 07, 2022 |
| MSI           | GV62 8RD                    | Notebook    | [2e43728adb](https://linux-hardware.org/?probe=2e43728adb) | Apr 06, 2022 |
| Microsoft     | Surface Pro 7               | Tablet      | [084e2350e9](https://linux-hardware.org/?probe=084e2350e9) | Apr 05, 2022 |
| ASUSTek       | 1101HA                      | Notebook    | [c3d2458d59](https://linux-hardware.org/?probe=c3d2458d59) | Apr 04, 2022 |
| ASUSTek       | ROG Strix G712LU_G712LU     | Notebook    | [288629b95d](https://linux-hardware.org/?probe=288629b95d) | Apr 04, 2022 |
| Dell          | Latitude 3190               | Notebook    | [45542e945e](https://linux-hardware.org/?probe=45542e945e) | Apr 04, 2022 |
| Dell          | 0YXT71 A01                  | Desktop     | [5de0fab8f2](https://linux-hardware.org/?probe=5de0fab8f2) | Apr 04, 2022 |
| Lenovo        | ThinkPad T430 23427YU       | Notebook    | [07ada1e358](https://linux-hardware.org/?probe=07ada1e358) | Apr 03, 2022 |
| ASUSTek       | ROG Strix G513QC_G513QC     | Notebook    | [697f820432](https://linux-hardware.org/?probe=697f820432) | Apr 02, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [83dab83528](https://linux-hardware.org/?probe=83dab83528) | Apr 01, 2022 |
| TUXEDO        | N7x0WU                      | Notebook    | [cf4f31fe3c](https://linux-hardware.org/?probe=cf4f31fe3c) | Mar 30, 2022 |
| Lenovo        | ThinkPad T440p 20AW002VB... | Notebook    | [e3ec03ac31](https://linux-hardware.org/?probe=e3ec03ac31) | Mar 29, 2022 |
| Dell          | Latitude 3190               | Notebook    | [ffd3ee8119](https://linux-hardware.org/?probe=ffd3ee8119) | Mar 28, 2022 |
| Framework     | Laptop                      | Notebook    | [a9f49dfe70](https://linux-hardware.org/?probe=a9f49dfe70) | Mar 24, 2022 |
| Dell          | Latitude 3190               | Notebook    | [960989448e](https://linux-hardware.org/?probe=960989448e) | Mar 21, 2022 |
| Lenovo        | 1046 NO DPK                 | Desktop     | [561b1c3324](https://linux-hardware.org/?probe=561b1c3324) | Mar 17, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [d0b555e0ba](https://linux-hardware.org/?probe=d0b555e0ba) | Mar 17, 2022 |
| Apple         | Mac-F2238AC8                | All in one  | [c8c2d7bba3](https://linux-hardware.org/?probe=c8c2d7bba3) | Mar 14, 2022 |
| Dell          | Latitude 3190               | Notebook    | [6d1ab0283d](https://linux-hardware.org/?probe=6d1ab0283d) | Mar 14, 2022 |
| HP            | 3647h                       | Desktop     | [fd6766aabb](https://linux-hardware.org/?probe=fd6766aabb) | Mar 11, 2022 |
| ASUSTek       | P5GC-MX/MEDION/SI           | Desktop     | [772e020316](https://linux-hardware.org/?probe=772e020316) | Mar 09, 2022 |
| MSI           | MS-7091                     | Desktop     | [71aaa6a920](https://linux-hardware.org/?probe=71aaa6a920) | Mar 09, 2022 |
| MSI           | MS-7091                     | Desktop     | [b08ddd1115](https://linux-hardware.org/?probe=b08ddd1115) | Mar 09, 2022 |
| Dell          | Latitude 3190               | Notebook    | [620f4d4f09](https://linux-hardware.org/?probe=620f4d4f09) | Mar 07, 2022 |
| Dell          | Latitude 3190               | Notebook    | [964420352c](https://linux-hardware.org/?probe=964420352c) | Feb 28, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [7147fe2d5c](https://linux-hardware.org/?probe=7147fe2d5c) | Feb 26, 2022 |
| ASUSTek       | 1101HA                      | Notebook    | [b234cc741f](https://linux-hardware.org/?probe=b234cc741f) | Feb 22, 2022 |
| Dell          | Latitude 3190               | Notebook    | [9637b88602](https://linux-hardware.org/?probe=9637b88602) | Feb 21, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [851badde2e](https://linux-hardware.org/?probe=851badde2e) | Feb 20, 2022 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [e58223cc60](https://linux-hardware.org/?probe=e58223cc60) | Feb 18, 2022 |
| Huanan        | X99-F8 V2.0                 | Desktop     | [23c722f6cf](https://linux-hardware.org/?probe=23c722f6cf) | Feb 18, 2022 |
| Huanan        | X99-F8 V2.0                 | Desktop     | [f4fec6a5be](https://linux-hardware.org/?probe=f4fec6a5be) | Feb 17, 2022 |
| Sony          | VPCF119FX                   | Notebook    | [1e8448b824](https://linux-hardware.org/?probe=1e8448b824) | Feb 15, 2022 |
| Dell          | Latitude 3190               | Notebook    | [6340f68567](https://linux-hardware.org/?probe=6340f68567) | Feb 14, 2022 |
| MSI           | Z97 GAMING 5                | Desktop     | [7c66c1b404](https://linux-hardware.org/?probe=7c66c1b404) | Feb 09, 2022 |
| Sony          | SVE1513Q1ESI                | Notebook    | [77e599ef9f](https://linux-hardware.org/?probe=77e599ef9f) | Feb 08, 2022 |
| Dell          | Latitude 3190               | Notebook    | [90df65f573](https://linux-hardware.org/?probe=90df65f573) | Feb 07, 2022 |
| Dell          | Latitude E4310              | Notebook    | [50190cb420](https://linux-hardware.org/?probe=50190cb420) | Feb 06, 2022 |
| efirstview    | v01099                      | Notebook    | [ed22d3c2b6](https://linux-hardware.org/?probe=ed22d3c2b6) | Feb 04, 2022 |
| Dell          | Latitude 3190               | Notebook    | [2e81dc022b](https://linux-hardware.org/?probe=2e81dc022b) | Jan 31, 2022 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [4ffe151e7a](https://linux-hardware.org/?probe=4ffe151e7a) | Jan 29, 2022 |
| Dell          | Latitude 3190               | Notebook    | [9b8e8549fd](https://linux-hardware.org/?probe=9b8e8549fd) | Jan 24, 2022 |
| Lenovo        | ThinkPad W541 20EG0005MS    | Notebook    | [f89a7895fc](https://linux-hardware.org/?probe=f89a7895fc) | Jan 23, 2022 |
| Sony          | VPCEH2N1E                   | Notebook    | [17a4bc1847](https://linux-hardware.org/?probe=17a4bc1847) | Jan 22, 2022 |
| Fujitsu Si... | LIFEBOOK E8010              | Notebook    | [82d1bc5db0](https://linux-hardware.org/?probe=82d1bc5db0) | Jan 22, 2022 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [882906d968](https://linux-hardware.org/?probe=882906d968) | Jan 17, 2022 |
| Alienware     | 13 R2                       | Notebook    | [65c1ae9026](https://linux-hardware.org/?probe=65c1ae9026) | Jan 14, 2022 |
| Dell          | Latitude 3190               | Notebook    | [3bb6a6428f](https://linux-hardware.org/?probe=3bb6a6428f) | Jan 10, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [58cff543b5](https://linux-hardware.org/?probe=58cff543b5) | Jan 06, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [ecaec39529](https://linux-hardware.org/?probe=ecaec39529) | Jan 05, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [d0d2edf745](https://linux-hardware.org/?probe=d0d2edf745) | Jan 04, 2022 |
| Lenovo        | G400s VILG1                 | Notebook    | [1cd4b24f16](https://linux-hardware.org/?probe=1cd4b24f16) | Jan 04, 2022 |
| Dell          | Latitude 3190               | Notebook    | [2c483dc59d](https://linux-hardware.org/?probe=2c483dc59d) | Jan 03, 2022 |
| Gigabyte      | P15FV5                      | Notebook    | [164348e568](https://linux-hardware.org/?probe=164348e568) | Jan 03, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [7cc374183b](https://linux-hardware.org/?probe=7cc374183b) | Dec 30, 2021 |
| Dell          | Latitude 3190               | Notebook    | [67cba6d321](https://linux-hardware.org/?probe=67cba6d321) | Dec 27, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [4fe24b4f44](https://linux-hardware.org/?probe=4fe24b4f44) | Dec 26, 2021 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [9147191a67](https://linux-hardware.org/?probe=9147191a67) | Dec 24, 2021 |
| ASUSTek       | X550CC                      | Notebook    | [b0cde813b9](https://linux-hardware.org/?probe=b0cde813b9) | Dec 23, 2021 |
| Dell          | Latitude 3190               | Notebook    | [1a96380872](https://linux-hardware.org/?probe=1a96380872) | Dec 20, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [78d4e04363](https://linux-hardware.org/?probe=78d4e04363) | Dec 16, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [49692045a2](https://linux-hardware.org/?probe=49692045a2) | Dec 16, 2021 |
| Dell          | Latitude 3190               | Notebook    | [5321909b8c](https://linux-hardware.org/?probe=5321909b8c) | Dec 13, 2021 |
| Dell          | Latitude 3190               | Notebook    | [9c532278f1](https://linux-hardware.org/?probe=9c532278f1) | Dec 06, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [21180cbdad](https://linux-hardware.org/?probe=21180cbdad) | Dec 04, 2021 |
| GALAX         | B550M                       | Desktop     | [a6866c8a45](https://linux-hardware.org/?probe=a6866c8a45) | Dec 04, 2021 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [bc8359d097](https://linux-hardware.org/?probe=bc8359d097) | Dec 01, 2021 |
| Lenovo        | B590 20208                  | Notebook    | [ed08d6bdd9](https://linux-hardware.org/?probe=ed08d6bdd9) | Nov 30, 2021 |
| Dell          | Latitude 3190               | Notebook    | [700dd2459e](https://linux-hardware.org/?probe=700dd2459e) | Nov 29, 2021 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | Notebook    | [649434f9b8](https://linux-hardware.org/?probe=649434f9b8) | Nov 23, 2021 |
| Dell          | Latitude 3190               | Notebook    | [7f020f1d1f](https://linux-hardware.org/?probe=7f020f1d1f) | Nov 22, 2021 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [bb58f4914e](https://linux-hardware.org/?probe=bb58f4914e) | Nov 21, 2021 |
| ASUSTek       | N53SN                       | Notebook    | [67d66feb3e](https://linux-hardware.org/?probe=67d66feb3e) | Nov 20, 2021 |
| Dell          | Latitude 3190               | Notebook    | [f24ac635ba](https://linux-hardware.org/?probe=f24ac635ba) | Nov 15, 2021 |
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

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                    | Computers | Percent |
|----------------------------|-----------|---------|
| 5.10.0-9-amd64             | 18        | 23.38%  |
| 5.10.0-13-amd64            | 13        | 16.88%  |
| 5.14.0-4mx-amd64           | 11        | 14.29%  |
| 5.10.0-11-amd64            | 8         | 10.39%  |
| 5.10.0-10-amd64            | 5         | 6.49%   |
| 5.16.0-4mx-amd64           | 2         | 2.6%    |
| 5.14.0-3mx-amd64           | 2         | 2.6%    |
| 5.10.0-8-amd64             | 2         | 2.6%    |
| 5.10.0-11-686-pae          | 2         | 2.6%    |
| 5.17.0-1-amd64             | 1         | 1.3%    |
| 5.16.0-rc5-hwmon-next+     | 1         | 1.3%    |
| 5.16.0-5mx-amd64           | 1         | 1.3%    |
| 5.16.0-18.1-liquorix-amd64 | 1         | 1.3%    |
| 5.15.0-3mx-amd64           | 1         | 1.3%    |
| 5.15.0-2-amd64             | 1         | 1.3%    |
| 5.15.0-0.bpo.2-amd64       | 1         | 1.3%    |
| 5.14.0-2mx-amd64           | 1         | 1.3%    |
| 5.10.52-antix.1-amd64-smp  | 1         | 1.3%    |
| 5.10.111-tkg-cfs           | 1         | 1.3%    |
| 5.10.0-5mx-amd64           | 1         | 1.3%    |
| 5.10.0-13-686-pae          | 1         | 1.3%    |
| 5.10.0-12-amd64            | 1         | 1.3%    |
| 5.10.0-11-686              | 1         | 1.3%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.10.0   | 48        | 65.75%  |
| 5.14.0   | 14        | 19.18%  |
| 5.16.0   | 5         | 6.85%   |
| 5.15.0   | 3         | 4.11%   |
| 5.17.0   | 1         | 1.37%   |
| 5.10.52  | 1         | 1.37%   |
| 5.10.111 | 1         | 1.37%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 50        | 68.49%  |
| 5.14    | 14        | 19.18%  |
| 5.16    | 5         | 6.85%   |
| 5.15    | 3         | 4.11%   |
| 5.17    | 1         | 1.37%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 70        | 95.89%  |
| i686   | 3         | 4.11%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| XFCE             | 51        | 69.86%  |
| KDE5             | 17        | 23.29%  |
| Unknown          | 2         | 2.74%   |
| lightdm-xsession | 1         | 1.37%   |
| GNOME            | 1         | 1.37%   |
| Budgie           | 1         | 1.37%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 72        | 98.63%  |
| Tty  | 1         | 1.37%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 54        | 73.97%  |
| SDDM    | 17        | 23.29%  |
| SLiM    | 1         | 1.37%   |
| Unknown | 1         | 1.37%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 37        | 50.68%  |
| de_DE   | 12        | 16.44%  |
| it_IT   | 3         | 4.11%   |
| en_GB   | 3         | 4.11%   |
| de_CH   | 3         | 4.11%   |
| Unknown | 3         | 4.11%   |
| ru_RU   | 2         | 2.74%   |
| pt_BR   | 2         | 2.74%   |
| fr_FR   | 2         | 2.74%   |
| tr_TR   | 1         | 1.37%   |
| sv_SE   | 1         | 1.37%   |
| sk_SK   | 1         | 1.37%   |
| fi_FI   | 1         | 1.37%   |
| es_PE   | 1         | 1.37%   |
| es_ES   | 1         | 1.37%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 49        | 67.12%  |
| BIOS | 24        | 32.88%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 61        | 83.56%  |
| Overlay  | 7         | 9.59%   |
| Btrfs    | 3         | 4.11%   |
| Reiserfs | 1         | 1.37%   |
| F2fs     | 1         | 1.37%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 58        | 79.45%  |
| MBR  | 15        | 20.55%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 43        | 58.9%   |
| Yes       | 30        | 41.1%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 37        | 50.68%  |
| Yes       | 36        | 49.32%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 12        | 16.44%  |
| ASUSTek Computer    | 12        | 16.44%  |
| Hewlett-Packard     | 8         | 10.96%  |
| Gigabyte Technology | 6         | 8.22%   |
| Sony                | 4         | 5.48%   |
| Dell                | 4         | 5.48%   |
| Apple               | 4         | 5.48%   |
| MSI                 | 3         | 4.11%   |
| Samsung Electronics | 2         | 2.74%   |
| Fujitsu Siemens     | 2         | 2.74%   |
| ASRock              | 2         | 2.74%   |
| Alienware           | 2         | 2.74%   |
| Acer                | 2         | 2.74%   |
| TUXEDO              | 1         | 1.37%   |
| Sun Microsystems    | 1         | 1.37%   |
| Microsoft           | 1         | 1.37%   |
| Intel               | 1         | 1.37%   |
| Huanan              | 1         | 1.37%   |
| GALAX               | 1         | 1.37%   |
| Fujitsu             | 1         | 1.37%   |
| Framework           | 1         | 1.37%   |
| efirstview          | 1         | 1.37%   |
| Chuwi               | 1         | 1.37%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                         | Computers | Percent |
|----------------------------------------------|-----------|---------|
| ASUS All Series                              | 2         | 2.74%   |
| TUXEDO N7x0WU                                | 1         | 1.37%   |
| Sun Microsystems Sun Ultra 40 M2 Workstation | 1         | 1.37%   |
| Sony VPCF119FX                               | 1         | 1.37%   |
| Sony VPCEH2N1E                               | 1         | 1.37%   |
| Sony VPCEC3S1E                               | 1         | 1.37%   |
| Sony SVE1513Q1ESI                            | 1         | 1.37%   |
| Samsung 350V5C/351V5C/3540VC/3440VC          | 1         | 1.37%   |
| Samsung 340XAA/350XAA/550XAA                 | 1         | 1.37%   |
| MSI MS-7917                                  | 1         | 1.37%   |
| MSI GV62 8RD                                 | 1         | 1.37%   |
| MSI Alpha 15 B5EEK                           | 1         | 1.37%   |
| Microsoft Surface Pro 7                      | 1         | 1.37%   |
| Lenovo Yoga 7 14ITL5 82BH                    | 1         | 1.37%   |
| Lenovo ThinkStation P620 30E0CTO1WW          | 1         | 1.37%   |
| Lenovo ThinkPad W541 20EG0005MS              | 1         | 1.37%   |
| Lenovo ThinkPad T440p 20AW002VBR             | 1         | 1.37%   |
| Lenovo ThinkPad T430 23427YU                 | 1         | 1.37%   |
| Lenovo ThinkPad E15 Gen 3 20YG008CUS         | 1         | 1.37%   |
| Lenovo ThinkBook 13s-IWL 20R9                | 1         | 1.37%   |
| Lenovo Legion 5 15ACH6H 82JU                 | 1         | 1.37%   |
| Lenovo IdeaPad Y700-15ISK 80NV               | 1         | 1.37%   |
| Lenovo G400s VILG1                           | 1         | 1.37%   |
| Lenovo B590 20208                            | 1         | 1.37%   |
| Lenovo 10AAS1QB0B                            | 1         | 1.37%   |
| Intel V1.3                                   | 1         | 1.37%   |
| Huanan X99-F8                                | 1         | 1.37%   |
| HP Z400 Workstation                          | 1         | 1.37%   |
| HP Spectre x360 Convertible 15-df1xxx        | 1         | 1.37%   |
| HP ProBook 450 G4                            | 1         | 1.37%   |
| HP EliteBook 850 G3                          | 1         | 1.37%   |
| HP EliteBook 8440p                           | 1         | 1.37%   |
| HP EliteBook 840 G3                          | 1         | 1.37%   |
| HP Compaq Presario CQ60                      | 1         | 1.37%   |
| HP Compaq 8000 Elite CMT PC                  | 1         | 1.37%   |
| Gigabyte Z390 UD                             | 1         | 1.37%   |
| Gigabyte X570 AORUS PRO                      | 1         | 1.37%   |
| Gigabyte P15FV5                              | 1         | 1.37%   |
| Gigabyte G5 KC                               | 1         | 1.37%   |
| Gigabyte B550M S2H                           | 1         | 1.37%   |
| Gigabyte B550M DS3H                          | 1         | 1.37%   |
| GALAX B550M                                  | 1         | 1.37%   |
| Fujitsu Siemens LIFEBOOK E8010               | 1         | 1.37%   |
| Fujitsu Siemens ESPRIMO Mobile D9500         | 1         | 1.37%   |
| Fujitsu ESPRIMO P720                         | 1         | 1.37%   |
| Framework Laptop                             | 1         | 1.37%   |
| efirstview v01099                            | 1         | 1.37%   |
| Dell XPS 17 9710                             | 1         | 1.37%   |
| Dell OptiPlex 7010                           | 1         | 1.37%   |
| Dell Latitude E4310                          | 1         | 1.37%   |
| Dell Latitude 3190                           | 1         | 1.37%   |
| Chuwi GemiBook Pro                           | 1         | 1.37%   |
| ASUS X550CC                                  | 1         | 1.37%   |
| ASUS TUF Gaming FX505DT_FX505DT              | 1         | 1.37%   |
| ASUS ROG Strix G712LU_G712LU                 | 1         | 1.37%   |
| ASUS ROG Strix G513QC_G513QC                 | 1         | 1.37%   |
| ASUS ROG Maximus XIII HERO                   | 1         | 1.37%   |
| ASUS P5GC-MX/MEDION/SI                       | 1         | 1.37%   |
| ASUS N53SN                                   | 1         | 1.37%   |
| ASUS E402MA                                  | 1         | 1.37%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 4         | 5.48%   |
| HP EliteBook             | 3         | 4.11%   |
| ASUS ROG                 | 3         | 4.11%   |
| HP Compaq                | 2         | 2.74%   |
| Gigabyte B550M           | 2         | 2.74%   |
| Dell Latitude            | 2         | 2.74%   |
| ASUS All                 | 2         | 2.74%   |
| TUXEDO N7x0WU            | 1         | 1.37%   |
| Sun Microsystems Sun     | 1         | 1.37%   |
| Sony VPCF119FX           | 1         | 1.37%   |
| Sony VPCEH2N1E           | 1         | 1.37%   |
| Sony VPCEC3S1E           | 1         | 1.37%   |
| Sony SVE1513Q1ESI        | 1         | 1.37%   |
| Samsung 350V5C           | 1         | 1.37%   |
| Samsung 340XAA           | 1         | 1.37%   |
| MSI MS-7917              | 1         | 1.37%   |
| MSI GV62                 | 1         | 1.37%   |
| MSI Alpha                | 1         | 1.37%   |
| Microsoft Surface        | 1         | 1.37%   |
| Lenovo Yoga              | 1         | 1.37%   |
| Lenovo ThinkStation      | 1         | 1.37%   |
| Lenovo ThinkBook         | 1         | 1.37%   |
| Lenovo Legion            | 1         | 1.37%   |
| Lenovo IdeaPad           | 1         | 1.37%   |
| Lenovo G400s             | 1         | 1.37%   |
| Lenovo B590              | 1         | 1.37%   |
| Lenovo 10AAS1QB0B        | 1         | 1.37%   |
| Intel V1.3               | 1         | 1.37%   |
| Huanan X99-F8            | 1         | 1.37%   |
| HP Z400                  | 1         | 1.37%   |
| HP Spectre               | 1         | 1.37%   |
| HP ProBook               | 1         | 1.37%   |
| Gigabyte Z390            | 1         | 1.37%   |
| Gigabyte X570            | 1         | 1.37%   |
| Gigabyte P15FV5          | 1         | 1.37%   |
| Gigabyte G5              | 1         | 1.37%   |
| GALAX B550M              | 1         | 1.37%   |
| Fujitsu Siemens LIFEBOOK | 1         | 1.37%   |
| Fujitsu Siemens ESPRIMO  | 1         | 1.37%   |
| Fujitsu ESPRIMO          | 1         | 1.37%   |
| Framework Laptop         | 1         | 1.37%   |
| efirstview v01099        | 1         | 1.37%   |
| Dell XPS                 | 1         | 1.37%   |
| Dell OptiPlex            | 1         | 1.37%   |
| Chuwi GemiBook           | 1         | 1.37%   |
| ASUS X550CC              | 1         | 1.37%   |
| ASUS TUF                 | 1         | 1.37%   |
| ASUS P5GC-MX             | 1         | 1.37%   |
| ASUS N53SN               | 1         | 1.37%   |
| ASUS E402MA              | 1         | 1.37%   |
| ASUS ASUS                | 1         | 1.37%   |
| ASUS 1101HA              | 1         | 1.37%   |
| ASRock X570              | 1         | 1.37%   |
| ASRock N3150M            | 1         | 1.37%   |
| Apple Macmini6           | 1         | 1.37%   |
| Apple MacBook3           | 1         | 1.37%   |
| Apple iMac12             | 1         | 1.37%   |
| Apple iMac11             | 1         | 1.37%   |
| Alienware m15            | 1         | 1.37%   |
| Alienware 13             | 1         | 1.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 11        | 15.07%  |
| 2020    | 8         | 10.96%  |
| 2015    | 7         | 9.59%   |
| 2019    | 6         | 8.22%   |
| 2016    | 6         | 8.22%   |
| 2013    | 6         | 8.22%   |
| 2010    | 6         | 8.22%   |
| 2018    | 4         | 5.48%   |
| 2014    | 3         | 4.11%   |
| 2011    | 3         | 4.11%   |
| 2007    | 3         | 4.11%   |
| 2012    | 2         | 2.74%   |
| 2009    | 2         | 2.74%   |
| 2008    | 2         | 2.74%   |
| 2022    | 1         | 1.37%   |
| 2017    | 1         | 1.37%   |
| 2005    | 1         | 1.37%   |
| Unknown | 1         | 1.37%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 46        | 63.01%  |
| Desktop     | 20        | 27.4%   |
| Convertible | 2         | 2.74%   |
| All in one  | 2         | 2.74%   |
| Tablet      | 1         | 1.37%   |
| Mini pc     | 1         | 1.37%   |
| Server      | 1         | 1.37%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 72        | 98.63%  |
| Enabled  | 1         | 1.37%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 73        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 20        | 27.4%   |
| 8.01-16.0   | 16        | 21.92%  |
| 16.01-24.0  | 15        | 20.55%  |
| 32.01-64.0  | 9         | 12.33%  |
| 3.01-4.0    | 5         | 6.85%   |
| 2.01-3.0    | 3         | 4.11%   |
| 64.01-256.0 | 2         | 2.74%   |
| 24.01-32.0  | 1         | 1.37%   |
| 1.01-2.0    | 1         | 1.37%   |
| 0.51-1.0    | 1         | 1.37%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 28        | 37.33%  |
| 2.01-3.0   | 20        | 26.67%  |
| 3.01-4.0   | 10        | 13.33%  |
| 4.01-8.0   | 8         | 10.67%  |
| 0.51-1.0   | 5         | 6.67%   |
| 8.01-16.0  | 3         | 4%      |
| 16.01-24.0 | 1         | 1.33%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 35        | 47.95%  |
| 2      | 18        | 24.66%  |
| 3      | 13        | 17.81%  |
| 4      | 3         | 4.11%   |
| 5      | 2         | 2.74%   |
| 8      | 1         | 1.37%   |
| 0      | 1         | 1.37%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 49        | 67.12%  |
| Yes       | 24        | 32.88%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 64        | 87.67%  |
| No        | 9         | 12.33%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 57        | 78.08%  |
| No        | 16        | 21.92%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 44        | 60.27%  |
| No        | 29        | 39.73%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 21        | 28.77%  |
| Germany     | 10        | 13.7%   |
| Italy       | 5         | 6.85%   |
| Canada      | 5         | 6.85%   |
| Switzerland | 3         | 4.11%   |
| Brazil      | 3         | 4.11%   |
| Spain       | 2         | 2.74%   |
| France      | 2         | 2.74%   |
| Finland     | 2         | 2.74%   |
| Belgium     | 2         | 2.74%   |
| Austria     | 2         | 2.74%   |
| UK          | 1         | 1.37%   |
| Turkey      | 1         | 1.37%   |
| Sweden      | 1         | 1.37%   |
| Slovakia    | 1         | 1.37%   |
| Serbia      | 1         | 1.37%   |
| Russia      | 1         | 1.37%   |
| Poland      | 1         | 1.37%   |
| Peru        | 1         | 1.37%   |
| Netherlands | 1         | 1.37%   |
| Malaysia    | 1         | 1.37%   |
| India       | 1         | 1.37%   |
| Greece      | 1         | 1.37%   |
| Czechia     | 1         | 1.37%   |
| Belarus     | 1         | 1.37%   |
| Azerbaijan  | 1         | 1.37%   |
| Australia   | 1         | 1.37%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Vienna              | 2         | 2.74%   |
| Portland            | 2         | 2.74%   |
| Lausen              | 2         | 2.74%   |
| Zurich              | 1         | 1.37%   |
| Waycross            | 1         | 1.37%   |
| Warsaw              | 1         | 1.37%   |
| Volos               | 1         | 1.37%   |
| Vilhelmina          | 1         | 1.37%   |
| Vancouver           | 1         | 1.37%   |
| Uelzen              | 1         | 1.37%   |
| Udine               | 1         | 1.37%   |
| Tupelo              | 1         | 1.37%   |
| Taggia              | 1         | 1.37%   |
| St Petersburg       | 1         | 1.37%   |
| Seelbach            | 1         | 1.37%   |
| Saskatoon           | 1         | 1.37%   |
| San Diego           | 1         | 1.37%   |
| Saarlouis           | 1         | 1.37%   |
| Rosporden           | 1         | 1.37%   |
| Roseville           | 1         | 1.37%   |
| Rochester           | 1         | 1.37%   |
| Prague              | 1         | 1.37%   |
| Powder Springs      | 1         | 1.37%   |
| Postbauer-Heng      | 1         | 1.37%   |
| Piedmont            | 1         | 1.37%   |
| Ottawa              | 1         | 1.37%   |
| Osasco              | 1         | 1.37%   |
| Normal              | 1         | 1.37%   |
| Mussolente          | 1         | 1.37%   |
| Munster             | 1         | 1.37%   |
| Munich              | 1         | 1.37%   |
| Moses Lake          | 1         | 1.37%   |
| Montreal            | 1         | 1.37%   |
| Minsk               | 1         | 1.37%   |
| Minneapolis         | 1         | 1.37%   |
| Milwaukee           | 1         | 1.37%   |
| Milan               | 1         | 1.37%   |
| London              | 1         | 1.37%   |
| Lima                | 1         | 1.37%   |
| Lannion             | 1         | 1.37%   |
| Lahti               | 1         | 1.37%   |
| Kitchener           | 1         | 1.37%   |
| Kent                | 1         | 1.37%   |
| Istanbul            | 1         | 1.37%   |
| Huercal Overa       | 1         | 1.37%   |
| Houston             | 1         | 1.37%   |
| Helsinki            | 1         | 1.37%   |
| Graniteville        | 1         | 1.37%   |
| Granadilla de Abona | 1         | 1.37%   |
| Göttingen          | 1         | 1.37%   |
| Glendale            | 1         | 1.37%   |
| Gilmer              | 1         | 1.37%   |
| Freital             | 1         | 1.37%   |
| Florence            | 1         | 1.37%   |
| Cyberjaya           | 1         | 1.37%   |
| Colorado Springs    | 1         | 1.37%   |
| Colfontaine         | 1         | 1.37%   |
| Cambui              | 1         | 1.37%   |
| Brussels            | 1         | 1.37%   |
| Brisbane            | 1         | 1.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 21        | 30     | 17.65%  |
| WDC                 | 19        | 23     | 15.97%  |
| Seagate             | 12        | 15     | 10.08%  |
| Kingston            | 11        | 11     | 9.24%   |
| Crucial             | 9         | 15     | 7.56%   |
| SK Hynix            | 5         | 5      | 4.2%    |
| Transcend           | 4         | 4      | 3.36%   |
| SanDisk             | 3         | 3      | 2.52%   |
| PNY                 | 3         | 4      | 2.52%   |
| LITEON              | 3         | 3      | 2.52%   |
| Intel               | 3         | 3      | 2.52%   |
| Dogfish             | 3         | 3      | 2.52%   |
| Unknown             | 2         | 2      | 1.68%   |
| Toshiba             | 2         | 2      | 1.68%   |
| Hitachi             | 2         | 2      | 1.68%   |
| Corsair             | 2         | 2      | 1.68%   |
| SPCC                | 1         | 1      | 0.84%   |
| SABRENT             | 1         | 1      | 0.84%   |
| Phison              | 1         | 1      | 0.84%   |
| OCZ                 | 1         | 1      | 0.84%   |
| Netac               | 1         | 1      | 0.84%   |
| Micron Technology   | 1         | 1      | 0.84%   |
| MAXTOR              | 1         | 1      | 0.84%   |
| GOODRAM             | 1         | 1      | 0.84%   |
| Gigabyte Technology | 1         | 1      | 0.84%   |
| GeIL                | 1         | 1      | 0.84%   |
| Fujitsu             | 1         | 1      | 0.84%   |
| Avant               | 1         | 1      | 0.84%   |
| Apple               | 1         | 2      | 0.84%   |
| A-DATA Technology   | 1         | 1      | 0.84%   |
| Unknown             | 1         | 1      | 0.84%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Kingston SA400S37480G 480GB SSD      | 4         | 2.96%   |
| Seagate ST2000DM008-2FR102 2TB       | 3         | 2.22%   |
| Samsung SSD 970 EVO Plus 1TB         | 3         | 2.22%   |
| Kingston SA400S37240G 240GB SSD      | 3         | 2.22%   |
| SK Hynix HFM512GDJTNI-82A0A 512GB    | 2         | 1.48%   |
| Samsung SSD 980 PRO 1TB              | 2         | 1.48%   |
| Samsung SSD 860 EVO 500GB            | 2         | 1.48%   |
| Samsung SSD 850 EVO 1TB              | 2         | 1.48%   |
| Dogfish SSD 128GB                    | 2         | 1.48%   |
| Crucial CT500P2SSD8 500GB            | 2         | 1.48%   |
| Crucial CT240BX500SSD1 240GB         | 2         | 1.48%   |
| Crucial CT120BX500SSD1 120GB         | 2         | 1.48%   |
| Corsair MP400 2TB                    | 2         | 1.48%   |
| WDC WDS500G2B0C-00PXH0 500GB         | 1         | 0.74%   |
| WDC WDS500G2B0B-00YS70 500GB SSD     | 1         | 0.74%   |
| WDC WDS100T2B0A-00SM50 1TB SSD       | 1         | 0.74%   |
| WDC WDS100T1X0E-00AFY0 1TB           | 1         | 0.74%   |
| WDC WD60EZRZ-00RWYB1 6TB             | 1         | 0.74%   |
| WDC WD60EFRX-68L0BN1 6TB             | 1         | 0.74%   |
| WDC WD5002AALX-00J37A0 500GB         | 1         | 0.74%   |
| WDC WD5000LPLX-08ZNTT0 500GB         | 1         | 0.74%   |
| WDC WD5000LPCX-22VHAT0 500GB         | 1         | 0.74%   |
| WDC WD5000AVCS-632DY1 500GB          | 1         | 0.74%   |
| WDC WD5000AAKS-40V6A0 500GB          | 1         | 0.74%   |
| WDC WD40EFRX-68WT0N0 4TB             | 1         | 0.74%   |
| WDC WD30EFRX-68AX9N0 3TB             | 1         | 0.74%   |
| WDC WD1600BEVT-60ZCT1 160GB          | 1         | 0.74%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 0.74%   |
| WDC WD10EZEX-08M2NA0 1TB             | 1         | 0.74%   |
| WDC WD10EVDS-63U8B1 1TB              | 1         | 0.74%   |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB   | 1         | 0.74%   |
| WDC PC SN730 NVMe 1024GB             | 1         | 0.74%   |
| WDC PC SN530 SDBPNPZ-1T00-1032 1TB   | 1         | 0.74%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB | 1         | 0.74%   |
| WDC PC SN530 SDBPMPZ-512G-1001 512GB | 1         | 0.74%   |
| Unknown SDW32G  32GB                 | 1         | 0.74%   |
| Unknown SD32G  32GB                  | 1         | 0.74%   |
| Transcend TS256GSSD370S 256GB        | 1         | 0.74%   |
| Transcend TS1GSDOM22V 1GB SSD        | 1         | 0.74%   |
| Transcend TS128GSSD370S 128GB        | 1         | 0.74%   |
| Transcend TS128GMTS800 128GB SSD     | 1         | 0.74%   |
| Toshiba MQ01ABD075 752GB             | 1         | 0.74%   |
| Toshiba DT01ACA100 1TB               | 1         | 0.74%   |
| SPCC Solid State Disk 256GB          | 1         | 0.74%   |
| SK Hynix HFM512GD3JX013N 512GB       | 1         | 0.74%   |
| SK Hynix HFM256GDJTNG-8310A 256GB    | 1         | 0.74%   |
| SK Hynix HFB1M8MO331C0MR 256GB       | 1         | 0.74%   |
| Seagate ST750LM022 HN-M750MBB 752GB  | 1         | 0.74%   |
| Seagate ST500LM021-1KJ152 500GB      | 1         | 0.74%   |
| Seagate ST500LM000-1EJ162 500GB      | 1         | 0.74%   |
| Seagate ST4000DM004-2CV104 4TB       | 1         | 0.74%   |
| Seagate ST3500413AS 500GB            | 1         | 0.74%   |
| Seagate ST3360320AS 360GB            | 1         | 0.74%   |
| Seagate ST2000LM003 HN-M201RAD 2TB   | 1         | 0.74%   |
| Seagate ST1000LM048-2E7172 1TB       | 1         | 0.74%   |
| Seagate ST1000LM035-1RK172 1TB       | 1         | 0.74%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 1         | 0.74%   |
| SanDisk SDSSDH3 1T00 1TB             | 1         | 0.74%   |
| SanDisk SD8SNAT-256G-1006 256GB SSD  | 1         | 0.74%   |
| SanDisk SD8SN8U-512G-1006 512GB SSD  | 1         | 0.74%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 15     | 36.36%  |
| WDC                 | 10        | 14     | 30.3%   |
| Samsung Electronics | 3         | 3      | 9.09%   |
| Toshiba             | 2         | 2      | 6.06%   |
| Hitachi             | 2         | 2      | 6.06%   |
| SABRENT             | 1         | 1      | 3.03%   |
| MAXTOR              | 1         | 1      | 3.03%   |
| Fujitsu             | 1         | 1      | 3.03%   |
| Apple               | 1         | 1      | 3.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 13        | 16     | 22.81%  |
| Kingston            | 9         | 9      | 15.79%  |
| Crucial             | 7         | 12     | 12.28%  |
| Transcend           | 4         | 4      | 7.02%   |
| SanDisk             | 3         | 3      | 5.26%   |
| LITEON              | 3         | 3      | 5.26%   |
| DOGFISH             | 3         | 3      | 5.26%   |
| WDC                 | 2         | 2      | 3.51%   |
| PNY                 | 2         | 2      | 3.51%   |
| SPCC                | 1         | 1      | 1.75%   |
| OCZ                 | 1         | 1      | 1.75%   |
| Netac               | 1         | 1      | 1.75%   |
| Micron Technology   | 1         | 1      | 1.75%   |
| Intel               | 1         | 1      | 1.75%   |
| GOODRAM             | 1         | 1      | 1.75%   |
| Gigabyte Technology | 1         | 1      | 1.75%   |
| GeIL                | 1         | 1      | 1.75%   |
| Avant               | 1         | 1      | 1.75%   |
| Apple               | 1         | 1      | 1.75%   |
| A-DATA Technology   | 1         | 1      | 1.75%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 45        | 65     | 42.86%  |
| HDD  | 29        | 40     | 27.62%  |
| NVMe | 28        | 35     | 26.67%  |
| MMC  | 3         | 3      | 2.86%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 54        | 102    | 62.07%  |
| NVMe | 28        | 35     | 32.18%  |
| MMC  | 3         | 3      | 3.45%   |
| SAS  | 2         | 3      | 2.3%    |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 44        | 64     | 58.67%  |
| 0.51-1.0   | 22        | 29     | 29.33%  |
| 1.01-2.0   | 5         | 6      | 6.67%   |
| 3.01-4.0   | 2         | 2      | 2.67%   |
| 2.01-3.0   | 1         | 1      | 1.33%   |
| 4.01-10.0  | 1         | 3      | 1.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 17        | 23.29%  |
| 101-250        | 17        | 23.29%  |
| 501-1000       | 13        | 17.81%  |
| More than 3000 | 6         | 8.22%   |
| 21-50          | 5         | 6.85%   |
| 1001-2000      | 5         | 6.85%   |
| 51-100         | 4         | 5.48%   |
| 2001-3000      | 3         | 4.11%   |
| 1-20           | 3         | 4.11%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 24        | 32.88%  |
| 21-50          | 15        | 20.55%  |
| 51-100         | 10        | 13.7%   |
| 101-250        | 9         | 12.33%  |
| 251-500        | 5         | 6.85%   |
| 1001-2000      | 5         | 6.85%   |
| More than 3000 | 2         | 2.74%   |
| 501-1000       | 2         | 2.74%   |
| 2001-3000      | 1         | 1.37%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WDS100T2B0A-00SM50 1TB SSD               | 1         | 1      | 8.33%   |
| WDC WD5000AAKS-40V6A0 500GB                  | 1         | 1      | 8.33%   |
| Seagate ST750LM022 HN-M750MBB 752GB          | 1         | 1      | 8.33%   |
| Seagate ST500LM021-1KJ152 500GB              | 1         | 1      | 8.33%   |
| Seagate ST3500413AS 500GB                    | 1         | 1      | 8.33%   |
| Seagate ST3360320AS 360GB                    | 1         | 1      | 8.33%   |
| Samsung Electronics SSD 850 EVO 500GB        | 1         | 1      | 8.33%   |
| Samsung Electronics SSD 850 EVO 1TB          | 1         | 1      | 8.33%   |
| Samsung Electronics SSD 840 Series 120GB     | 1         | 1      | 8.33%   |
| Samsung Electronics SSD 840 PRO Series 256GB | 1         | 1      | 8.33%   |
| MAXTOR 4K040H2 40GB                          | 1         | 1      | 8.33%   |
| GOODRAM SSDPR-CL100-480-G3 480GB             | 1         | 1      | 8.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 4      | 33.33%  |
| Samsung Electronics | 4         | 4      | 33.33%  |
| WDC                 | 2         | 2      | 16.67%  |
| MAXTOR              | 1         | 1      | 8.33%   |
| GOODRAM             | 1         | 1      | 8.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 66.67%  |
| WDC     | 1         | 1      | 16.67%  |
| MAXTOR  | 1         | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 6         | 6      | 54.55%  |
| HDD  | 5         | 6      | 45.45%  |

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
| Works    | 67        | 125    | 80.72%  |
| Malfunc  | 11        | 12     | 13.25%  |
| Detected | 5         | 6      | 6.02%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 53        | 54.64%  |
| Samsung Electronics         | 10        | 10.31%  |
| Sandisk                     | 7         | 7.22%   |
| AMD                         | 7         | 7.22%   |
| SK Hynix                    | 5         | 5.15%   |
| Phison Electronics          | 4         | 4.12%   |
| ASMedia Technology          | 3         | 3.09%   |
| Nvidia                      | 2         | 2.06%   |
| Micron/Crucial Technology   | 2         | 2.06%   |
| Kingston Technology Company | 2         | 2.06%   |
| Silicon Image               | 1         | 1.03%   |
| Broadcom / LSI              | 1         | 1.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 7         | 6.48%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 5         | 4.63%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 5         | 4.63%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 4         | 3.7%    |
| Phison E12 NVMe Controller                                                       | 4         | 3.7%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 3.7%    |
| AMD FCH SATA Controller [AHCI mode]                                              | 4         | 3.7%    |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 3         | 2.78%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 3         | 2.78%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 2.78%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 3         | 2.78%   |
| AMD 500 Series Chipset SATA Controller                                           | 3         | 2.78%   |
| SK Hynix BC511                                                                   | 2         | 1.85%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 2         | 1.85%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 2         | 1.85%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 2         | 1.85%   |
| Sandisk Non-Volatile memory controller                                           | 2         | 1.85%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 1.85%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 2         | 1.85%   |
| Intel Volume Management Device NVMe RAID Controller                              | 2         | 1.85%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 2         | 1.85%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 2         | 1.85%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 1.85%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 1.85%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 2         | 1.85%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 2         | 1.85%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 2         | 1.85%   |
| SK Hynix Gold P31 SSD                                                            | 1         | 0.93%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                             | 1         | 0.93%   |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                                       | 1         | 0.93%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                     | 1         | 0.93%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                 | 1         | 0.93%   |
| Nvidia MCP55 SATA Controller                                                     | 1         | 0.93%   |
| Nvidia MCP55 IDE                                                                 | 1         | 0.93%   |
| Kingston Company Company Non-Volatile memory controller                          | 1         | 0.93%   |
| Kingston Company KC2000 NVMe SSD                                                 | 1         | 0.93%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                       | 1         | 0.93%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 1         | 0.93%   |
| Intel SSD 660P Series                                                            | 1         | 0.93%   |
| Intel SATA Controller [RAID mode]                                                | 1         | 0.93%   |
| Intel Non-Volatile memory controller                                             | 1         | 0.93%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 1         | 0.93%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 1         | 0.93%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 0.93%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 0.93%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 0.93%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 1         | 0.93%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                             | 1         | 0.93%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1         | 0.93%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                           | 1         | 0.93%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 1         | 0.93%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 1         | 0.93%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 1         | 0.93%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 1         | 0.93%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 1         | 0.93%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 1         | 0.93%   |
| Broadcom / LSI SAS1068E PCI-Express Fusion-MPT SAS                               | 1         | 0.93%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 50        | 53.76%  |
| NVMe | 28        | 30.11%  |
| IDE  | 8         | 8.6%    |
| RAID | 6         | 6.45%   |
| SCSI | 1         | 1.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 59        | 80.82%  |
| AMD    | 14        | 19.18%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 7 5800H with Radeon Graphics        | 3         | 4.11%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 2.74%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 2.74%   |
| Intel Core i7-5820K CPU @ 3.30GHz             | 2         | 2.74%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 2.74%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 2.74%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 2.74%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 2         | 2.74%   |
| Intel Xeon CPU W3565 @ 3.20GHz                | 1         | 1.37%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz           | 1         | 1.37%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 1.37%   |
| Intel Pentium M processor 1.80GHz             | 1         | 1.37%   |
| Intel Core i9-10850K CPU @ 3.60GHz            | 1         | 1.37%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 1.37%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 1.37%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 1.37%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 1         | 1.37%   |
| Intel Core i7-3720QM CPU @ 2.60GHz            | 1         | 1.37%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 1         | 1.37%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 1         | 1.37%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 1         | 1.37%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 1.37%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 1         | 1.37%   |
| Intel Core i7 CPU M 620 @ 2.67GHz             | 1         | 1.37%   |
| Intel Core i5-9600K CPU @ 3.70GHz             | 1         | 1.37%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 1.37%   |
| Intel Core i5-4690K CPU @ 3.50GHz             | 1         | 1.37%   |
| Intel Core i5-4570T CPU @ 2.90GHz             | 1         | 1.37%   |
| Intel Core i5-4300M CPU @ 2.60GHz             | 1         | 1.37%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 1         | 1.37%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 1.37%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 1         | 1.37%   |
| Intel Core i5-2400S CPU @ 2.50GHz             | 1         | 1.37%   |
| Intel Core i5-10500H CPU @ 2.50GHz            | 1         | 1.37%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 1         | 1.37%   |
| Intel Core i3-4130 CPU @ 3.40GHz              | 1         | 1.37%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 1         | 1.37%   |
| Intel Core i3-2328M CPU @ 2.20GHz             | 1         | 1.37%   |
| Intel Core i3 CPU 540 @ 3.07GHz               | 1         | 1.37%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 1         | 1.37%   |
| Intel Core 2 Duo CPU T5250 @ 1.50GHz          | 1         | 1.37%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 1         | 1.37%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz          | 1         | 1.37%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 1         | 1.37%   |
| Intel Celeron CPU N3150 @ 1.60GHz             | 1         | 1.37%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 1         | 1.37%   |
| Intel Atom CPU Z520 @ 1.33GHz                 | 1         | 1.37%   |
| Intel Atom CPU Z3735G @ 1.33GHz               | 1         | 1.37%   |
| Intel 12th Gen Core i7-12700H                 | 1         | 1.37%   |
| Intel 11th Gen Core i9-11980HK @ 2.60GHz      | 1         | 1.37%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 1         | 1.37%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1         | 1.37%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 1         | 1.37%   |
| AMD Sempron SI-42                             | 1         | 1.37%   |
| AMD Ryzen Threadripper PRO 3945WX 12-Cores    | 1         | 1.37%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 1         | 1.37%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 1         | 1.37%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 1         | 1.37%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 1         | 1.37%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 1         | 1.37%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i7          | 19        | 26.03%  |
| Intel Core i5          | 17        | 23.29%  |
| Other                  | 6         | 8.22%   |
| AMD Ryzen 7            | 6         | 8.22%   |
| Intel Core i3          | 4         | 5.48%   |
| Intel Core 2 Duo       | 4         | 5.48%   |
| Intel Celeron          | 3         | 4.11%   |
| Intel Xeon             | 2         | 2.74%   |
| Intel Atom             | 2         | 2.74%   |
| AMD Ryzen 9            | 2         | 2.74%   |
| AMD Ryzen 5            | 2         | 2.74%   |
| Intel Pentium Silver   | 1         | 1.37%   |
| Intel Pentium M        | 1         | 1.37%   |
| Intel Core i9          | 1         | 1.37%   |
| AMD Sempron            | 1         | 1.37%   |
| AMD Ryzen Threadripper | 1         | 1.37%   |
| AMD Ryzen 3            | 1         | 1.37%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 27        | 36.99%  |
| 2      | 23        | 31.51%  |
| 6      | 8         | 10.96%  |
| 8      | 7         | 9.59%   |
| 12     | 3         | 4.11%   |
| 1      | 3         | 4.11%   |
| 14     | 1         | 1.37%   |
| 10     | 1         | 1.37%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 72        | 98.63%  |
| 2      | 1         | 1.37%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 56        | 76.71%  |
| 1      | 17        | 23.29%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 71        | 97.26%  |
| 32-bit         | 2         | 2.74%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306a9    | 7         | 9.59%   |
| Unknown    | 7         | 9.59%   |
| 0x20655    | 4         | 5.48%   |
| 0xa0652    | 3         | 4.11%   |
| 0x806c1    | 3         | 4.11%   |
| 0x406e3    | 3         | 4.11%   |
| 0x306c3    | 3         | 4.11%   |
| 0x206a7    | 3         | 4.11%   |
| 0x0a50000c | 3         | 4.11%   |
| 0x806ea    | 2         | 2.74%   |
| 0x6fd      | 2         | 2.74%   |
| 0x506e3    | 2         | 2.74%   |
| 0x306f2    | 2         | 2.74%   |
| 0x30678    | 2         | 2.74%   |
| 0x08701021 | 2         | 2.74%   |
| 0xa0655    | 1         | 1.37%   |
| 0x906ed    | 1         | 1.37%   |
| 0x906ea    | 1         | 1.37%   |
| 0x906a3    | 1         | 1.37%   |
| 0x806ec    | 1         | 1.37%   |
| 0x806eb    | 1         | 1.37%   |
| 0x806e9    | 1         | 1.37%   |
| 0x806d1    | 1         | 1.37%   |
| 0x706e5    | 1         | 1.37%   |
| 0x706a8    | 1         | 1.37%   |
| 0x706a1    | 1         | 1.37%   |
| 0x6fb      | 1         | 1.37%   |
| 0x6d6      | 1         | 1.37%   |
| 0x406c3    | 1         | 1.37%   |
| 0x106e5    | 1         | 1.37%   |
| 0x106c2    | 1         | 1.37%   |
| 0x1067a    | 1         | 1.37%   |
| 0x0a50000b | 1         | 1.37%   |
| 0x0a201016 | 1         | 1.37%   |
| 0x0a201009 | 1         | 1.37%   |
| 0x08608103 | 1         | 1.37%   |
| 0x08301039 | 1         | 1.37%   |
| 0x08108102 | 1         | 1.37%   |
| 0x0800820d | 1         | 1.37%   |
| 0x02000057 | 1         | 1.37%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Haswell          | 8         | 10.96%  |
| KabyLake         | 7         | 9.59%   |
| IvyBridge        | 7         | 9.59%   |
| Zen 3            | 6         | 8.22%   |
| Westmere         | 5         | 6.85%   |
| Skylake          | 5         | 6.85%   |
| SandyBridge      | 4         | 5.48%   |
| CometLake        | 4         | 5.48%   |
| Zen 2            | 3         | 4.11%   |
| TigerLake        | 3         | 4.11%   |
| Silvermont       | 3         | 4.11%   |
| Core             | 3         | 4.11%   |
| Zen+             | 2         | 2.74%   |
| Nehalem          | 2         | 2.74%   |
| Icelake          | 2         | 2.74%   |
| Goldmont plus    | 2         | 2.74%   |
| Penryn           | 1         | 1.37%   |
| P6               | 1         | 1.37%   |
| K8 Hammer        | 1         | 1.37%   |
| K8 & K10 hybrid  | 1         | 1.37%   |
| Bonnell          | 1         | 1.37%   |
| Alderlake Hybrid | 1         | 1.37%   |
| Unknown          | 1         | 1.37%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 48        | 50.53%  |
| Nvidia | 30        | 31.58%  |
| AMD    | 17        | 17.89%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 6         | 6.12%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 4         | 4.08%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 3         | 3.06%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 3.06%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 3.06%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 3.06%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 3.06%   |
| AMD Cezanne                                                                              | 3         | 3.06%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 2.04%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 2         | 2.04%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 2         | 2.04%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 2.04%   |
| Intel UHD Graphics 620                                                                   | 2         | 2.04%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 2.04%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 2.04%   |
| Intel HD Graphics 530                                                                    | 2         | 2.04%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 2.04%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 2.04%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                                     | 2         | 2.04%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 1.02%   |
| Nvidia TU117M                                                                            | 1         | 1.02%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 1.02%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                    | 1         | 1.02%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 1.02%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 1.02%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 1.02%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1         | 1.02%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 1.02%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 1.02%   |
| Nvidia GK208 [GeForce GT 635]                                                            | 1         | 1.02%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 1         | 1.02%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 1.02%   |
| Nvidia GF108M [GeForce GT 550M]                                                          | 1         | 1.02%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 1         | 1.02%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 1         | 1.02%   |
| Nvidia GA107BM [GeForce RTX 3050 Ti Mobile]                                              | 1         | 1.02%   |
| Nvidia G94GL [Quadro FX 1800]                                                            | 1         | 1.02%   |
| Nvidia G86 [GeForce 8500 GT]                                                             | 1         | 1.02%   |
| Nvidia G71GL [Quadro FX 3500]                                                            | 1         | 1.02%   |
| Nvidia C77 [GeForce 8200M G]                                                             | 1         | 1.02%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1         | 1.02%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 1.02%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                                      | 1         | 1.02%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 1         | 1.02%   |
| Intel Iris Plus Graphics G7                                                              | 1         | 1.02%   |
| Intel HD Graphics 620                                                                    | 1         | 1.02%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 1         | 1.02%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 1.02%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 1.02%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.02%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.02%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 1         | 1.02%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 1         | 1.02%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 1         | 1.02%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 1         | 1.02%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 1         | 1.02%   |
| AMD RV730/M96-XT [Mobility Radeon HD 4670]                                               | 1         | 1.02%   |
| AMD RV350/M10 / RV360/M11 [Mobility Radeon 9600 (PRO) / 9700]                            | 1         | 1.02%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1         | 1.02%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 1         | 1.02%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 29        | 39.73%  |
| Intel + Nvidia | 14        | 19.18%  |
| 1 x Nvidia     | 13        | 17.81%  |
| 1 x AMD        | 11        | 15.07%  |
| AMD + Nvidia   | 3         | 4.11%   |
| Intel + AMD    | 2         | 2.74%   |
| 2 x AMD        | 1         | 1.37%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 52        | 71.23%  |
| Proprietary | 18        | 24.66%  |
| Unknown     | 3         | 4.11%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 48        | 65.75%  |
| 7.01-8.0   | 6         | 8.22%   |
| 3.01-4.0   | 6         | 8.22%   |
| 0.01-0.5   | 6         | 8.22%   |
| 0.51-1.0   | 5         | 6.85%   |
| 8.01-16.0  | 2         | 2.74%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 10        | 12.2%   |
| LG Display              | 8         | 9.76%   |
| AU Optronics            | 8         | 9.76%   |
| Samsung Electronics     | 7         | 8.54%   |
| Dell                    | 4         | 4.88%   |
| BOE                     | 4         | 4.88%   |
| Ancor Communications    | 4         | 4.88%   |
| Sharp                   | 3         | 3.66%   |
| PANDA                   | 3         | 3.66%   |
| Hewlett-Packard         | 3         | 3.66%   |
| Fujitsu Siemens         | 3         | 3.66%   |
| Acer                    | 3         | 3.66%   |
| Sony                    | 2         | 2.44%   |
| Philips                 | 2         | 2.44%   |
| Medion                  | 2         | 2.44%   |
| Chi Mei Optoelectronics | 2         | 2.44%   |
| Apple                   | 2         | 2.44%   |
| AOC                     | 2         | 2.44%   |
| Vizio                   | 1         | 1.22%   |
| SAC                     | 1         | 1.22%   |
| Panasonic               | 1         | 1.22%   |
| NEC Computers           | 1         | 1.22%   |
| Lenovo                  | 1         | 1.22%   |
| Iiyama                  | 1         | 1.22%   |
| Grundig                 | 1         | 1.22%   |
| Goldstar                | 1         | 1.22%   |
| Gigabyte Technology     | 1         | 1.22%   |
| CPT                     | 1         | 1.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 2         | 2.38%   |
| Medion MD22322 MEB8101 2560x1440 699x393mm 31.6-inch                     | 2         | 2.38%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 2         | 2.38%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 2         | 2.38%   |
| Vizio M220MV VIZ0062 1920x1080 480x270mm 21.7-inch                       | 1         | 1.19%   |
| Sony Nvidia Defaul t Flat Panel SNY06FA 1600x900 360x200mm 16.2-inch     | 1         | 1.19%   |
| Sony Nvidia Defaul t Flat Panel MS_0025 1920x1080 360x200mm 16.2-inch    | 1         | 1.19%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch                  | 1         | 1.19%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch                  | 1         | 1.19%   |
| Sharp LCD Monitor SHP1445 3840x2160 350x190mm 15.7-inch                  | 1         | 1.19%   |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                         | 1         | 1.19%   |
| Samsung Electronics S23B300 SAM08AF 1920x1080 510x287mm 23.0-inch        | 1         | 1.19%   |
| Samsung Electronics LCD Monitor SEC4245 1280x800 331x207mm 15.4-inch     | 1         | 1.19%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 344x194mm 15.5-inch     | 1         | 1.19%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 340x190mm 15.3-inch    | 1         | 1.19%   |
| Samsung Electronics C32JG5x SAM0FE0 2560x1440 700x390mm 31.5-inch        | 1         | 1.19%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 1         | 1.19%   |
| SAC DP_FREESYNC SAC2700 2560x1440 597x336mm 27.0-inch                    | 1         | 1.19%   |
| Philips PHL 276E9Q PHLC17B 1920x1080 598x336mm 27.0-inch                 | 1         | 1.19%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                  | 1         | 1.19%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                  | 1         | 1.19%   |
| Panasonic LCD Monitor MEI96A2 2560x1440 309x173mm 13.9-inch              | 1         | 1.19%   |
| NEC Computers EA221WM NEC673D 1680x1050 474x296mm 22.0-inch              | 1         | 1.19%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch            | 1         | 1.19%   |
| LG Display LCD Monitor LGD06E2 1920x1080 344x194mm 15.5-inch             | 1         | 1.19%   |
| LG Display LCD Monitor LGD0570 1920x1080 344x194mm 15.5-inch             | 1         | 1.19%   |
| LG Display LCD Monitor LGD0555 1536x1024 263x175mm 12.4-inch             | 1         | 1.19%   |
| LG Display LCD Monitor LGD03DB 1366x768 345x194mm 15.6-inch              | 1         | 1.19%   |
| LG Display LCD Monitor LGD024D 1366x768 294x166mm 13.3-inch              | 1         | 1.19%   |
| Lenovo LEN T2454pA LEN60C9 1920x1200 518x324mm 24.1-inch                 | 1         | 1.19%   |
| Iiyama PL2776HD IVM6605 1920x1080 598x336mm 27.0-inch                    | 1         | 1.19%   |
| Hewlett-Packard X27q HPN3725 2560x1440 600x340mm 27.2-inch               | 1         | 1.19%   |
| Hewlett-Packard X27q HPN3724 2560x1440 600x340mm 27.2-inch               | 1         | 1.19%   |
| Hewlett-Packard w2207 HWP26A8 1680x1050 473x296mm 22.0-inch              | 1         | 1.19%   |
| Hewlett-Packard LA2306 HWP294B 1920x1080 509x286mm 23.0-inch             | 1         | 1.19%   |
| Grundig UHD GRU4448 3840x2160 1210x680mm 54.6-inch                       | 1         | 1.19%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                  | 1         | 1.19%   |
| Gigabyte Technology G34WQC GBT3400 3440x1440 797x334mm 34.0-inch         | 1         | 1.19%   |
| Fujitsu Siemens L24W-2 FUS077A 1920x1200 520x320mm 24.0-inch             | 1         | 1.19%   |
| Fujitsu Siemens B22W-7 LED FUS0838 1680x1050 474x296mm 22.0-inch         | 1         | 1.19%   |
| Fujitsu Siemens B22W-5 ECO FUS07C3 1680x1050 474x296mm 22.0-inch         | 1         | 1.19%   |
| Dell U2719D DEL415A 2560x1440 597x336mm 27.0-inch                        | 1         | 1.19%   |
| Dell SR2320L DELF03A 1920x1080 510x290mm 23.1-inch                       | 1         | 1.19%   |
| Dell S3422DW DELD103 3440x1440 800x330mm 34.1-inch                       | 1         | 1.19%   |
| Dell E190S DELA04B 1280x1024 376x301mm 19.0-inch                         | 1         | 1.19%   |
| Dell 1908FP DEL4025 1280x1024 376x301mm 19.0-inch                        | 1         | 1.19%   |
| CPT LCD Monitor CPT1C21 1366x768 256x144mm 11.6-inch                     | 1         | 1.19%   |
| Chimei Innolux P140ZKA-BZ1 CMN8C03 2160x1440 296x197mm 14.0-inch         | 1         | 1.19%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 1         | 1.19%   |
| Chimei Innolux LCD Monitor CMN15D6 1920x1080 344x193mm 15.5-inch         | 1         | 1.19%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 1         | 1.19%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch          | 1         | 1.19%   |
| Chimei Innolux LCD Monitor CMN1491 1366x768 309x174mm 14.0-inch          | 1         | 1.19%   |
| Chimei Innolux LCD Monitor CMN1402 1920x1080 309x173mm 13.9-inch         | 1         | 1.19%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 1         | 1.19%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 1         | 1.19%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 1         | 1.19%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                    | 1         | 1.19%   |
| BOE LCD Monitor BOE08BE 1920x1080 382x215mm 17.3-inch                    | 1         | 1.19%   |
| BOE LCD Monitor BOE0714 1920x1080 344x193mm 15.5-inch                    | 1         | 1.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 32        | 41.56%  |
| 1366x768 (WXGA)    | 13        | 16.88%  |
| 3840x2160 (4K)     | 6         | 7.79%   |
| 2560x1440 (QHD)    | 6         | 7.79%   |
| 1680x1050 (WSXGA+) | 3         | 3.9%    |
| 3440x1440          | 2         | 2.6%    |
| 1920x1200 (WUXGA)  | 2         | 2.6%    |
| 1600x900 (HD+)     | 2         | 2.6%    |
| 1280x800 (WXGA)    | 2         | 2.6%    |
| 1280x1024 (SXGA)   | 2         | 2.6%    |
| 3840x2400          | 1         | 1.3%    |
| 2736x1824          | 1         | 1.3%    |
| 2560x1080          | 1         | 1.3%    |
| 2256x1504          | 1         | 1.3%    |
| 2160x1440          | 1         | 1.3%    |
| 1440x900 (WXGA+)   | 1         | 1.3%    |
| 1360x768           | 1         | 1.3%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 26        | 32.5%   |
| 27      | 8         | 10%     |
| 13      | 7         | 8.75%   |
| 24      | 5         | 6.25%   |
| 23      | 5         | 6.25%   |
| 17      | 5         | 6.25%   |
| 31      | 4         | 5%      |
| 14      | 4         | 5%      |
| 34      | 3         | 3.75%   |
| 22      | 3         | 3.75%   |
| 21      | 2         | 2.5%    |
| 19      | 2         | 2.5%    |
| 11      | 2         | 2.5%    |
| 54      | 1         | 1.25%   |
| 26      | 1         | 1.25%   |
| 12      | 1         | 1.25%   |
| Unknown | 1         | 1.25%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 32        | 40.51%  |
| 501-600     | 18        | 22.78%  |
| 201-300     | 8         | 10.13%  |
| 401-500     | 6         | 7.59%   |
| 351-400     | 6         | 7.59%   |
| 601-700     | 4         | 5.06%   |
| 701-800     | 3         | 3.8%    |
| 1001-1500   | 1         | 1.27%   |
| Unknown     | 1         | 1.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 56        | 75.68%  |
| 16/10 | 10        | 13.51%  |
| 3/2   | 3         | 4.05%   |
| 21/9  | 3         | 4.05%   |
| 5/4   | 2         | 2.7%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 26        | 32.5%   |
| 201-250        | 12        | 15%     |
| 81-90          | 9         | 11.25%  |
| 301-350        | 8         | 10%     |
| 351-500        | 7         | 8.75%   |
| 251-300        | 4         | 5%      |
| 121-130        | 4         | 5%      |
| 71-80          | 3         | 3.75%   |
| 51-60          | 2         | 2.5%    |
| 151-200        | 2         | 2.5%    |
| More than 1000 | 1         | 1.25%   |
| 141-150        | 1         | 1.25%   |
| Unknown        | 1         | 1.25%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 28        | 36.36%  |
| 121-160       | 22        | 28.57%  |
| 101-120       | 17        | 22.08%  |
| More than 240 | 4         | 5.19%   |
| 161-240       | 4         | 5.19%   |
| 1-50          | 1         | 1.3%    |
| Unknown       | 1         | 1.3%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 52        | 71.23%  |
| 2     | 15        | 20.55%  |
| 3     | 3         | 4.11%   |
| 0     | 3         | 4.11%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 38        | 33.93%  |
| Realtek Semiconductor    | 32        | 28.57%  |
| Qualcomm Atheros         | 15        | 13.39%  |
| Broadcom                 | 6         | 5.36%   |
| TP-Link                  | 4         | 3.57%   |
| Marvell Technology Group | 4         | 3.57%   |
| MEDIATEK                 | 3         | 2.68%   |
| Ralink Technology        | 2         | 1.79%   |
| Nvidia                   | 2         | 1.79%   |
| Microsoft                | 1         | 0.89%   |
| Edimax Technology        | 1         | 0.89%   |
| Dell                     | 1         | 0.89%   |
| Broadcom Limited         | 1         | 0.89%   |
| ASUSTek Computer         | 1         | 0.89%   |
| Aquantia                 | 1         | 0.89%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 27        | 20.77%  |
| Intel Wireless 8260                                                            | 4         | 3.08%   |
| Intel Wi-Fi 6 AX200                                                            | 4         | 3.08%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 3         | 2.31%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 3         | 2.31%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter                  | 3         | 2.31%   |
| Intel I211 Gigabit Network Connection                                          | 3         | 2.31%   |
| Intel Ethernet Connection I217-LM                                              | 3         | 2.31%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                   | 2         | 1.54%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 2         | 1.54%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 2         | 1.54%   |
| Intel Wireless 8265 / 8275                                                     | 2         | 1.54%   |
| Intel Wireless 7260                                                            | 2         | 1.54%   |
| Intel Ethernet Connection I219-V                                               | 2         | 1.54%   |
| Intel Ethernet Connection (2) I218-V                                           | 2         | 1.54%   |
| Intel Comet Lake PCH CNVi WiFi                                                 | 2         | 1.54%   |
| Intel Centrino Advanced-N 6200                                                 | 2         | 1.54%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 2         | 1.54%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 1.54%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 2         | 1.54%   |
| TP-Link USB 10/100/1000 LAN                                                    | 1         | 0.77%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                         | 1         | 0.77%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                             | 1         | 0.77%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                       | 1         | 0.77%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 1         | 0.77%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                            | 1         | 0.77%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1         | 0.77%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 0.77%   |
| Ralink RT2870/RT3070 Wireless Adapter                                          | 1         | 0.77%   |
| Ralink RT2070 Wireless Adapter                                                 | 1         | 0.77%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 1         | 0.77%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.77%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 1         | 0.77%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.77%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1         | 0.77%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                     | 1         | 0.77%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                               | 1         | 0.77%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                 | 1         | 0.77%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                 | 1         | 0.77%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 0.77%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.77%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)        | 1         | 0.77%   |
| Nvidia MCP77 Ethernet                                                          | 1         | 0.77%   |
| Nvidia MCP55 Ethernet                                                          | 1         | 0.77%   |
| Microsoft RTL8153 GigE [Surface Dock Ethernet]                                 | 1         | 0.77%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.77%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 0.77%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 1         | 0.77%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 0.77%   |
| Intel Wireless 7265                                                            | 1         | 0.77%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                         | 1         | 0.77%   |
| Intel Wi-Fi 6 AX201                                                            | 1         | 0.77%   |
| Intel Tiger Lake PCH CNVi WiFi                                                 | 1         | 0.77%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                          | 1         | 0.77%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                       | 1         | 0.77%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                | 1         | 0.77%   |
| Intel Ethernet Controller I225-V                                               | 1         | 0.77%   |
| Intel Ethernet Connection I217-V                                               | 1         | 0.77%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                              | 1         | 0.77%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                   | 1         | 0.77%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 30        | 49.18%  |
| Qualcomm Atheros      | 11        | 18.03%  |
| Realtek Semiconductor | 6         | 9.84%   |
| TP-Link               | 3         | 4.92%   |
| MEDIATEK              | 3         | 4.92%   |
| Broadcom              | 3         | 4.92%   |
| Ralink Technology     | 2         | 3.28%   |
| Edimax Technology     | 1         | 1.64%   |
| Broadcom Limited      | 1         | 1.64%   |
| ASUSTek Computer      | 1         | 1.64%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8260                                                     | 4         | 6.56%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 6.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 3         | 4.92%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 4.92%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 3.28%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 3.28%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 3.28%   |
| Intel Wireless 8265 / 8275                                              | 2         | 3.28%   |
| Intel Wireless 7260                                                     | 2         | 3.28%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 3.28%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 3.28%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                  | 1         | 1.64%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 1.64%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 1.64%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.64%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                     | 1         | 1.64%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 1.64%   |
| Ralink RT2070 Wireless Adapter                                          | 1         | 1.64%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 1.64%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 1.64%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 1         | 1.64%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 1.64%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 1.64%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.64%   |
| Intel Wireless 7265                                                     | 1         | 1.64%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1         | 1.64%   |
| Intel Wi-Fi 6 AX201                                                     | 1         | 1.64%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 1         | 1.64%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 1.64%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 1         | 1.64%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 1         | 1.64%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1         | 1.64%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 1         | 1.64%   |
| Intel Centrino Advanced-N 6235                                          | 1         | 1.64%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 1.64%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 1.64%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 1         | 1.64%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 1         | 1.64%   |
| Edimax RTL8192S WLAN Adapter                                            | 1         | 1.64%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 1         | 1.64%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 1         | 1.64%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 1         | 1.64%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 1         | 1.64%   |
| ASUS 802.11ac NIC                                                       | 1         | 1.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 31        | 46.97%  |
| Intel                    | 16        | 24.24%  |
| Qualcomm Atheros         | 6         | 9.09%   |
| Marvell Technology Group | 4         | 6.06%   |
| Broadcom                 | 4         | 6.06%   |
| Nvidia                   | 2         | 3.03%   |
| TP-Link                  | 1         | 1.52%   |
| Microsoft                | 1         | 1.52%   |
| Aquantia                 | 1         | 1.52%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 27        | 39.71%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 3         | 4.41%   |
| Intel I211 Gigabit Network Connection                                          | 3         | 4.41%   |
| Intel Ethernet Connection I217-LM                                              | 3         | 4.41%   |
| Intel Ethernet Connection I219-V                                               | 2         | 2.94%   |
| Intel Ethernet Connection (2) I218-V                                           | 2         | 2.94%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 2         | 2.94%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 2.94%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 2         | 2.94%   |
| TP-Link USB 10/100/1000 LAN                                                    | 1         | 1.47%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1         | 1.47%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 1.47%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 1.47%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 1.47%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1         | 1.47%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                     | 1         | 1.47%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 1.47%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 1.47%   |
| Nvidia MCP77 Ethernet                                                          | 1         | 1.47%   |
| Nvidia MCP55 Ethernet                                                          | 1         | 1.47%   |
| Microsoft RTL8153 GigE [Surface Dock Ethernet]                                 | 1         | 1.47%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 1.47%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 1.47%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 1         | 1.47%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 1.47%   |
| Intel Ethernet Controller I225-V                                               | 1         | 1.47%   |
| Intel Ethernet Connection I217-V                                               | 1         | 1.47%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 1         | 1.47%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                              | 1         | 1.47%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 1         | 1.47%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]              | 1         | 1.47%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 64        | 52.46%  |
| WiFi     | 57        | 46.72%  |
| Modem    | 1         | 0.82%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 47        | 59.49%  |
| Ethernet | 31        | 39.24%  |
| Modem    | 1         | 1.27%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 45        | 61.64%  |
| 1     | 26        | 35.62%  |
| 3     | 1         | 1.37%   |
| 0     | 1         | 1.37%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 52        | 71.23%  |
| Yes  | 21        | 28.77%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 20        | 44.44%  |
| Apple                           | 5         | 11.11%  |
| Qualcomm Atheros Communications | 4         | 8.89%   |
| Realtek Semiconductor           | 3         | 6.67%   |
| IMC Networks                    | 3         | 6.67%   |
| Foxconn / Hon Hai               | 3         | 6.67%   |
| Cambridge Silicon Radio         | 2         | 4.44%   |
| ASUSTek Computer                | 2         | 4.44%   |
| Lite-On Technology              | 1         | 2.22%   |
| Hewlett-Packard                 | 1         | 2.22%   |
| Dell                            | 1         | 2.22%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 7         | 15.56%  |
| Intel Bluetooth Device                                                              | 6         | 13.33%  |
| Intel AX200 Bluetooth                                                               | 4         | 8.89%   |
| Realtek Bluetooth Radio                                                             | 3         | 6.67%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 2         | 4.44%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 2         | 4.44%   |
| IMC Networks Wireless_Device                                                        | 2         | 4.44%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 4.44%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 2         | 4.44%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 2         | 4.44%   |
| Apple Bluetooth USB Host Controller                                                 | 2         | 4.44%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 2.22%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 2.22%   |
| Lite-On Wireless_Device                                                             | 1         | 2.22%   |
| Intel AX210 Bluetooth                                                               | 1         | 2.22%   |
| IMC Networks Bluetooth Radio                                                        | 1         | 2.22%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 2.22%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 2.22%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 2.22%   |
| ASUS Broadcom Bluetooth 2.1                                                         | 1         | 2.22%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                               | 1         | 2.22%   |
| Apple Bluetooth HCI                                                                 | 1         | 2.22%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 57        | 51.82%  |
| Nvidia              | 22        | 20%     |
| AMD                 | 18        | 16.36%  |
| ROCCAT              | 2         | 1.82%   |
| Creative Labs       | 2         | 1.82%   |
| C-Media Electronics | 2         | 1.82%   |
| Unknown             | 1         | 0.91%   |
| Texas Instruments   | 1         | 0.91%   |
| Schiit Audio        | 1         | 0.91%   |
| Razer USA           | 1         | 0.91%   |
| Plantronics         | 1         | 0.91%   |
| GN Netcom           | 1         | 0.91%   |
| Unknown             | 1         | 0.91%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 8         | 6.45%   |
| Nvidia Audio device                                                                               | 6         | 4.84%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 6         | 4.84%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 4.84%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 6         | 4.84%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 4.03%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 3.23%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 4         | 3.23%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 3.23%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 3         | 2.42%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 2.42%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 2.42%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 3         | 2.42%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 3         | 2.42%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 3         | 2.42%   |
| ROCCAT Khan AIMO                                                                                  | 2         | 1.61%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 1.61%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 1.61%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 1.61%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 1.61%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 1.61%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 1.61%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                                     | 2         | 1.61%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 2         | 1.61%   |
| Unknown Realtek USB Audio Rear                                                                    | 1         | 0.81%   |
| Unknown Realtek USB Audio Front                                                                   | 1         | 0.81%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                                                 | 1         | 0.81%   |
| Schiit Audio I'm Fulla Schiit                                                                     | 1         | 0.81%   |
| Razer USA Kraken Tournament Edition                                                               | 1         | 0.81%   |
| Plantronics BT600                                                                                 | 1         | 0.81%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.81%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.81%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 1         | 0.81%   |
| Nvidia MCP55 High Definition Audio                                                                | 1         | 0.81%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.81%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.81%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.81%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 1         | 0.81%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.81%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                                   | 1         | 0.81%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 0.81%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 0.81%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 0.81%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 0.81%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 0.81%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.81%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.81%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 1         | 0.81%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 1         | 0.81%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 1         | 0.81%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 1         | 0.81%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 1         | 0.81%   |
| GN Netcom Jabra BIZ 2300                                                                          | 1         | 0.81%   |
| C-Media Electronics USB Advanced Audio Device                                                     | 1         | 0.81%   |
| C-Media Electronics Blue Snowball                                                                 | 1         | 0.81%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 1         | 0.81%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 1         | 0.81%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 1         | 0.81%   |
| AMD Hawaii HDMI Audio [Radeon R9 290/290X / 390/390X]                                             | 1         | 0.81%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 1         | 0.81%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 18        | 21.69%  |
| SK Hynix            | 14        | 16.87%  |
| Unknown             | 13        | 15.66%  |
| Micron Technology   | 7         | 8.43%   |
| Kingston            | 7         | 8.43%   |
| Corsair             | 7         | 8.43%   |
| Crucial             | 5         | 6.02%   |
| G.Skill             | 4         | 4.82%   |
| Smart               | 2         | 2.41%   |
| Unknown             | 2         | 2.41%   |
| Unknown (ABCD)      | 1         | 1.2%    |
| PNY                 | 1         | 1.2%    |
| Elpida              | 1         | 1.2%    |
| Avant               | 1         | 1.2%    |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3                               | 3         | 3.37%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 3         | 3.37%   |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 2.25%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 2         | 2.25%   |
| Samsung RAM Module 2GB SODIMM DDR3 1333MT/s                      | 2         | 2.25%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 2         | 2.25%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 2         | 2.25%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s           | 2         | 2.25%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 2         | 2.25%   |
| Unknown                                                          | 2         | 2.25%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 1.12%   |
| Unknown RAM Module 8GB SODIMM DDR3                               | 1         | 1.12%   |
| Unknown RAM Module 4GB DIMM SDRAM                                | 1         | 1.12%   |
| Unknown RAM Module 2GB SODIMM DRAM 667MT/s                       | 1         | 1.12%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 1.12%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 1.12%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 1.12%   |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s                         | 1         | 1.12%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 1.12%   |
| Unknown RAM Module 1GB SODIMM DDR3 1333MT/s                      | 1         | 1.12%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 1         | 1.12%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 1         | 1.12%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 1         | 1.12%   |
| Smart RAM SF4641G8CK8IEGKSBG 8GB SODIMM DDR4 2400MT/s            | 1         | 1.12%   |
| SK Hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 1         | 1.12%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.12%   |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 1.12%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 1         | 1.12%   |
| SK Hynix RAM HMT351S6EFR8A 4096MB SODIMM DDR3 1600MT/s           | 1         | 1.12%   |
| SK Hynix RAM HMT351S6AFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.12%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2048MB SODIMM DDR3 1333MT/s        | 1         | 1.12%   |
| SK Hynix RAM HMT125S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 1         | 1.12%   |
| SK Hynix RAM HMCG66MEBSA095N 8GB SODIMM 4800MT/s                 | 1         | 1.12%   |
| SK Hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 1.12%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.12%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.12%   |
| SK Hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s           | 1         | 1.12%   |
| SK Hynix RAM H9HCNNNCPNALHR-NEE 8GB Row Of Chips LPDDR4 3733MT/s | 1         | 1.12%   |
| SK Hynix RAM 0000000000-00000 8GB SODIMM DDR4 2400MT/s           | 1         | 1.12%   |
| Samsung RAM Module 4GB SODIMM DDR2 667MT/s                       | 1         | 1.12%   |
| Samsung RAM M471B5773EB0-CK0 2048MB SODIMM DDR3 1600MT/s         | 1         | 1.12%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s            | 1         | 1.12%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.12%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.12%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 1         | 1.12%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s         | 1         | 1.12%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 1         | 1.12%   |
| Samsung RAM M393A4K40DB3-CWE 32GB DIMM DDR4 3200MT/s             | 1         | 1.12%   |
| Samsung RAM M386A4G40DM0-CPB 32GB DIMM DDR4 2133MT/s             | 1         | 1.12%   |
| PNY RAM Module 8GB SODIMM DDR3 1333MT/s                          | 1         | 1.12%   |
| Micron RAM Module 8GB SODIMM DDR3 1600MT/s                       | 1         | 1.12%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s              | 1         | 1.12%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8192MB SODIMM DDR4 3200MT/s          | 1         | 1.12%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 1         | 1.12%   |
| Micron RAM 16KTF51264HZ-1G6M1 4096MB SODIMM DDR3 1600MT/s        | 1         | 1.12%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 1         | 1.12%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s           | 1         | 1.12%   |
| Kingston RAM KHX3200C16D4/4GX 4GB DIMM DDR4 3600MT/s             | 1         | 1.12%   |
| Kingston RAM HP594908-HR1-ELD 2GB SODIMM DDR3 1333MT/s           | 1         | 1.12%   |
| Kingston RAM 99U5471-033.A00LF 4096MB DIMM DDR3                  | 1         | 1.12%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 34        | 47.22%  |
| DDR3    | 26        | 36.11%  |
| DDR2    | 5         | 6.94%   |
| SDRAM   | 2         | 2.78%   |
| LPDDR4  | 2         | 2.78%   |
| DRAM    | 1         | 1.39%   |
| DDR     | 1         | 1.39%   |
| Unknown | 1         | 1.39%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 50        | 70.42%  |
| DIMM         | 19        | 26.76%  |
| Row Of Chips | 2         | 2.82%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 34        | 43.04%  |
| 4096  | 22        | 27.85%  |
| 2048  | 12        | 15.19%  |
| 16384 | 5         | 6.33%   |
| 32768 | 3         | 3.8%    |
| 1024  | 3         | 3.8%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 13        | 17.57%  |
| 1600    | 12        | 16.22%  |
| 1333    | 8         | 10.81%  |
| 2133    | 7         | 9.46%   |
| Unknown | 6         | 8.11%   |
| 2667    | 5         | 6.76%   |
| 3600    | 4         | 5.41%   |
| 2400    | 4         | 5.41%   |
| 667     | 3         | 4.05%   |
| 3400    | 2         | 2.7%    |
| 4800    | 1         | 1.35%   |
| 4199    | 1         | 1.35%   |
| 3733    | 1         | 1.35%   |
| 3466    | 1         | 1.35%   |
| 1639    | 1         | 1.35%   |
| 1400    | 1         | 1.35%   |
| 1334    | 1         | 1.35%   |
| 1067    | 1         | 1.35%   |
| 333     | 1         | 1.35%   |
| 166     | 1         | 1.35%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 50%     |
| Canon           | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                    | Computers | Percent |
|--------------------------|-----------|---------|
| HP LaserJet P2055 series | 1         | 50%     |
| Canon MF641C             | 1         | 50%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Canon CanoScan N1240U/LiDE 30 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 10        | 22.22%  |
| Acer                                   | 5         | 11.11%  |
| Logitech                               | 4         | 8.89%   |
| Realtek Semiconductor                  | 3         | 6.67%   |
| Microdia                               | 3         | 6.67%   |
| IMC Networks                           | 3         | 6.67%   |
| Sunplus Innovation Technology          | 2         | 4.44%   |
| Lite-On Technology                     | 2         | 4.44%   |
| Apple                                  | 2         | 4.44%   |
| Z-Star Microelectronics                | 1         | 2.22%   |
| Suyin                                  | 1         | 2.22%   |
| Silicon Motion                         | 1         | 2.22%   |
| Ricoh                                  | 1         | 2.22%   |
| Quanta                                 | 1         | 2.22%   |
| Primax Electronics                     | 1         | 2.22%   |
| Microsoft                              | 1         | 2.22%   |
| Goodong Industry                       | 1         | 2.22%   |
| Generalplus Technology                 | 1         | 2.22%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.22%   |
| 8SSC20F27145V1SR19P0BEK                | 1         | 2.22%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Sunplus Integrated_Webcam_HD                        | 2         | 4.44%   |
| Logitech Webcam C930e                               | 2         | 4.44%   |
| Acer BisonCam, NB Pro                               | 2         | 4.44%   |
| Z-Star Venus USB2.0 Camera                          | 1         | 2.22%   |
| Suyin Sony Visual Communication Camera              | 1         | 2.22%   |
| Silicon Motion Web Camera                           | 1         | 2.22%   |
| Ricoh USB2.0 Camera                                 | 1         | 2.22%   |
| Realtek USB Camera                                  | 1         | 2.22%   |
| Realtek Lenovo EasyCamera                           | 1         | 2.22%   |
| Realtek Integrated Webcam                           | 1         | 2.22%   |
| Quanta HD User Facing                               | 1         | 2.22%   |
| Primax Dell Laptop Integrated Webcam 2Mpix          | 1         | 2.22%   |
| Microsoft LifeCam HD-3000                           | 1         | 2.22%   |
| Microdia Webcam Vitade AF                           | 1         | 2.22%   |
| Microdia WebCam SC-13HDL12639P                      | 1         | 2.22%   |
| Microdia Webcam                                     | 1         | 2.22%   |
| Logitech Webcam C270                                | 1         | 2.22%   |
| Logitech StreamCam                                  | 1         | 2.22%   |
| Lite-On HP HD Webcam                                | 1         | 2.22%   |
| Lite-On HP HD Camera                                | 1         | 2.22%   |
| IMC Networks USB2.0 UVC 1.3M WebCam                 | 1         | 2.22%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 1         | 2.22%   |
| IMC Networks Integrated Camera                      | 1         | 2.22%   |
| Goodong Industry USB2.0 HD UVC WebCam               | 1         | 2.22%   |
| Generalplus GENERAL WEBCAM                          | 1         | 2.22%   |
| Chicony USB2.0 HD UVC WebCam                        | 1         | 2.22%   |
| Chicony USB 2.0 Camera                              | 1         | 2.22%   |
| Chicony thinkpad t430s camera                       | 1         | 2.22%   |
| Chicony Sony Visual Communication Camera            | 1         | 2.22%   |
| Chicony Lenovo EasyCamera                           | 1         | 2.22%   |
| Chicony Integrated Camera                           | 1         | 2.22%   |
| Chicony HP Wide Vision FHD Camera                   | 1         | 2.22%   |
| Chicony HP Webcam [2 MP Macro]                      | 1         | 2.22%   |
| Chicony HD User Facing                              | 1         | 2.22%   |
| Chicony 2.0M UVC WebCam                             | 1         | 2.22%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 1         | 2.22%   |
| Apple FaceTime HD Camera (Built-in)                 | 1         | 2.22%   |
| Apple Built-in iSight                               | 1         | 2.22%   |
| Acer SunplusIT INC. Integrated Camera               | 1         | 2.22%   |
| Acer Integrated Camera                              | 1         | 2.22%   |
| Acer BisonCam,NB Pro                                | 1         | 2.22%   |
| 8SSC20F27145V1SR19P0BEK Integrated Camera           | 1         | 2.22%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 4         | 50%     |
| Shenzhen Goodix Technology | 3         | 37.5%   |
| Synaptics                  | 1         | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader   | 2         | 25%     |
| Validity Sensors VFS 5011 fingerprint sensor | 2         | 25%     |
| Shenzhen Goodix  FingerPrint Device          | 2         | 25%     |
| Shenzhen Goodix Fingerprint Reader           | 1         | 12.5%   |
| Unknown                                      | 1         | 12.5%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 51        | 68.92%  |
| 1     | 19        | 25.68%  |
| 2     | 4         | 5.41%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 11        | 44%     |
| Fingerprint reader       | 8         | 32%     |
| Unassigned class         | 3         | 12%     |
| Multimedia controller    | 1         | 4%      |
| Communication controller | 1         | 4%      |
| Chipcard                 | 1         | 4%      |

