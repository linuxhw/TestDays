MX 21 - Tested Hardware & Statistics (Desktops)
-----------------------------------------------

A project to collect tested hardware configurations for MX 21.

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

Total: 97

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | 3029h                       | [153b913406](https://linux-hardware.org/?probe=153b913406) | Mar 27, 2023 |
| Unknown       | GB01                        | [ad0e76307c](https://linux-hardware.org/?probe=ad0e76307c) | Mar 24, 2023 |
| MSI           | B360M PRO-VH                | [2706ed39b7](https://linux-hardware.org/?probe=2706ed39b7) | Mar 23, 2023 |
| HP            | 3048h                       | [cd326ce9fa](https://linux-hardware.org/?probe=cd326ce9fa) | Mar 22, 2023 |
| ASRock        | AB350 Pro4                  | [4a452568eb](https://linux-hardware.org/?probe=4a452568eb) | Mar 16, 2023 |
| Shenzhen M... | F6BFC                       | [46cb84be25](https://linux-hardware.org/?probe=46cb84be25) | Mar 14, 2023 |
| MSI           | CSM-H87M-G43                | [9df13e200e](https://linux-hardware.org/?probe=9df13e200e) | Mar 14, 2023 |
| Lenovo        | ThinkCentre M58 7638CB8     | [d303f78e26](https://linux-hardware.org/?probe=d303f78e26) | Mar 14, 2023 |
| Gigabyte      | PH67A-D3-B3                 | [145a0a3b7d](https://linux-hardware.org/?probe=145a0a3b7d) | Mar 05, 2023 |
| HP            | 8184 X4                     | [b42f6862c7](https://linux-hardware.org/?probe=b42f6862c7) | Mar 04, 2023 |
| Unknown       | 1.0                         | [bab30a1ac1](https://linux-hardware.org/?probe=bab30a1ac1) | Feb 24, 2023 |
| Dell          | 0D441T A03                  | [351a527308](https://linux-hardware.org/?probe=351a527308) | Feb 18, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [482c922bbc](https://linux-hardware.org/?probe=482c922bbc) | Feb 14, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [13492935fd](https://linux-hardware.org/?probe=13492935fd) | Feb 09, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | [11f3874a6f](https://linux-hardware.org/?probe=11f3874a6f) | Feb 07, 2023 |
| ASUSTek       | Z97M-PLUS                   | [99a4bb9e50](https://linux-hardware.org/?probe=99a4bb9e50) | Feb 05, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | [42e242e6bf](https://linux-hardware.org/?probe=42e242e6bf) | Feb 04, 2023 |
| Unknown       | Unknown                     | [793f52c99a](https://linux-hardware.org/?probe=793f52c99a) | Feb 03, 2023 |
| ECS           | P4M800PRO-M                 | [f446d61863](https://linux-hardware.org/?probe=f446d61863) | Feb 02, 2023 |
| Intel         | D34010WYK H14771-303        | [31485ae6ec](https://linux-hardware.org/?probe=31485ae6ec) | Feb 01, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | [dd017ac78a](https://linux-hardware.org/?probe=dd017ac78a) | Jan 31, 2023 |
| ASUSTek       | ROG Maximus XIII HERO       | [a32a9ba13a](https://linux-hardware.org/?probe=a32a9ba13a) | Jan 30, 2023 |
| Gigabyte      | GA-MA770-UD3                | [554aa8592c](https://linux-hardware.org/?probe=554aa8592c) | Jan 28, 2023 |
| BESSTAR Te... | UM340                       | [77efbbb270](https://linux-hardware.org/?probe=77efbbb270) | Jan 27, 2023 |
| MSI           | Z390-A PRO                  | [28c31b639b](https://linux-hardware.org/?probe=28c31b639b) | Jan 25, 2023 |
| Gigabyte      | Z77X-D3H                    | [e81c0bcfc4](https://linux-hardware.org/?probe=e81c0bcfc4) | Jan 22, 2023 |
| Dell          | 0PC5F7 A02                  | [7671c99c3c](https://linux-hardware.org/?probe=7671c99c3c) | Jan 19, 2023 |
| HP            | 3396                        | [2085b91098](https://linux-hardware.org/?probe=2085b91098) | Jan 15, 2023 |
| Pegatron      | 2AD5                        | [d41fde4498](https://linux-hardware.org/?probe=d41fde4498) | Jan 15, 2023 |
| ASRock        | X370 Taichi                 | [9c3ea14006](https://linux-hardware.org/?probe=9c3ea14006) | Jan 09, 2023 |
| ASUSTek       | H81M-E                      | [165bb4a9ab](https://linux-hardware.org/?probe=165bb4a9ab) | Jan 06, 2023 |
| Dell          | 0D881F A06                  | [21e5ad204d](https://linux-hardware.org/?probe=21e5ad204d) | Jan 04, 2023 |
| Dell          | 0D881F A06                  | [00dddfca31](https://linux-hardware.org/?probe=00dddfca31) | Jan 03, 2023 |
| Gigabyte      | B550M DS3H                  | [677feeeca9](https://linux-hardware.org/?probe=677feeeca9) | Jan 03, 2023 |
| ZOTAC         | Unknown                     | [c3d5155637](https://linux-hardware.org/?probe=c3d5155637) | Jan 01, 2023 |
| MSI           | Z390-A PRO                  | [3a3375e173](https://linux-hardware.org/?probe=3a3375e173) | Dec 29, 2022 |
| MSI           | Z270 GAMING PRO CARBON      | [f422489705](https://linux-hardware.org/?probe=f422489705) | Dec 27, 2022 |
| Dell          | 0HY9JP A02                  | [c195f58592](https://linux-hardware.org/?probe=c195f58592) | Dec 24, 2022 |
| Lenovo        | 3741 SDK0T76461 WIN 3422... | [70e125f0d0](https://linux-hardware.org/?probe=70e125f0d0) | Dec 23, 2022 |
| Fujitsu       | D3498-A1 S26361-D3498-A1    | [03cd265cef](https://linux-hardware.org/?probe=03cd265cef) | Dec 05, 2022 |
| ASUSTek       | PRIME A320M-K               | [6487bbd7b7](https://linux-hardware.org/?probe=6487bbd7b7) | Dec 05, 2022 |
| SIRAGON       | AIO-5150                    | [90476603fa](https://linux-hardware.org/?probe=90476603fa) | Dec 04, 2022 |
| HP            | 304Ah                       | [15db22accc](https://linux-hardware.org/?probe=15db22accc) | Nov 30, 2022 |
| ASRock        | B365M Pro4                  | [0f0d4f70b0](https://linux-hardware.org/?probe=0f0d4f70b0) | Nov 20, 2022 |
| Foxconn       | 2ABF                        | [aa4bde7d79](https://linux-hardware.org/?probe=aa4bde7d79) | Nov 20, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [1a0674de42](https://linux-hardware.org/?probe=1a0674de42) | Nov 14, 2022 |
| ASRock        | B365M Pro4                  | [f5305c9730](https://linux-hardware.org/?probe=f5305c9730) | Nov 04, 2022 |
| MSI           | X570-A PRO                  | [c60d9aa72d](https://linux-hardware.org/?probe=c60d9aa72d) | Oct 31, 2022 |
| Biostar       | H61MH                       | [f505de310c](https://linux-hardware.org/?probe=f505de310c) | Oct 27, 2022 |
| Lenovo        | 318E NOK                    | [6b190bfb4f](https://linux-hardware.org/?probe=6b190bfb4f) | Oct 25, 2022 |
| Pegatron      | NARRA3                      | [1588e60c57](https://linux-hardware.org/?probe=1588e60c57) | Oct 12, 2022 |
| ASUSTek       | Z170-P                      | [2f3c79dd55](https://linux-hardware.org/?probe=2f3c79dd55) | Sep 29, 2022 |
| ASUSTek       | P5GC-MX/CKD/SI              | [72bb90ea71](https://linux-hardware.org/?probe=72bb90ea71) | Sep 28, 2022 |
| ASUSTek       | P5G41T-M LX                 | [8e429edcd6](https://linux-hardware.org/?probe=8e429edcd6) | Sep 25, 2022 |
| ASUSTek       | PRIME B450M-A               | [bdb353fd2c](https://linux-hardware.org/?probe=bdb353fd2c) | Sep 20, 2022 |
| HP            | 1632                        | [8309a8acf0](https://linux-hardware.org/?probe=8309a8acf0) | Sep 10, 2022 |
| Medion        | H110H4-EM                   | [1b22e5560d](https://linux-hardware.org/?probe=1b22e5560d) | Sep 07, 2022 |
| Gigabyte      | B560M DS3H V2               | [c430bf0275](https://linux-hardware.org/?probe=c430bf0275) | Sep 03, 2022 |
| Biostar       | A780L3B                     | [62782d600f](https://linux-hardware.org/?probe=62782d600f) | Aug 14, 2022 |
| Intel         | DH55TC AAE70932-303         | [f275229d83](https://linux-hardware.org/?probe=f275229d83) | Jul 31, 2022 |
| MP            | MS-7848                     | [f7696965e0](https://linux-hardware.org/?probe=f7696965e0) | Jul 22, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [85782181c7](https://linux-hardware.org/?probe=85782181c7) | Jul 21, 2022 |
| ASUSTek       | P8H61/USB3 R2.0             | [1076f6d59a](https://linux-hardware.org/?probe=1076f6d59a) | Jul 19, 2022 |
| AOpen         | D1009 A1A4                  | [d8edf66887](https://linux-hardware.org/?probe=d8edf66887) | Jul 13, 2022 |
| Dell          | 0DR845                      | [4c4a530cc5](https://linux-hardware.org/?probe=4c4a530cc5) | Jul 06, 2022 |
| MSI           | B350 TOMAHAWK               | [5a66940742](https://linux-hardware.org/?probe=5a66940742) | Jun 23, 2022 |
| MSI           | Z77A-G41                    | [d0f55f3c0b](https://linux-hardware.org/?probe=d0f55f3c0b) | Jun 22, 2022 |
| Dell          | 0200DY A01                  | [bc8030c1d5](https://linux-hardware.org/?probe=bc8030c1d5) | Jun 22, 2022 |
| Dell          | 0DR845                      | [56b4af8d26](https://linux-hardware.org/?probe=56b4af8d26) | Jun 20, 2022 |
| Gigabyte      | H410M S2H V3                | [b57b3a635c](https://linux-hardware.org/?probe=b57b3a635c) | Jun 02, 2022 |
| ASUSTek       | SABERTOOTH X99              | [b627953ad4](https://linux-hardware.org/?probe=b627953ad4) | May 11, 2022 |
| Intel         | V1.3                        | [a01993f2fa](https://linux-hardware.org/?probe=a01993f2fa) | Apr 30, 2022 |
| ASUSTek       | SABERTOOTH X99              | [51cc264c62](https://linux-hardware.org/?probe=51cc264c62) | Apr 22, 2022 |
| Gigabyte      | B550M S2H                   | [208972e3b5](https://linux-hardware.org/?probe=208972e3b5) | Apr 19, 2022 |
| ASRock        | N3150M                      | [0ee71f6582](https://linux-hardware.org/?probe=0ee71f6582) | Apr 19, 2022 |
| Gigabyte      | B550M S2H                   | [1127f26185](https://linux-hardware.org/?probe=1127f26185) | Apr 17, 2022 |
| Dell          | 0YXT71 A01                  | [5de0fab8f2](https://linux-hardware.org/?probe=5de0fab8f2) | Apr 04, 2022 |
| Lenovo        | 1046 NO DPK                 | [561b1c3324](https://linux-hardware.org/?probe=561b1c3324) | Mar 17, 2022 |
| Gigabyte      | Z390 UD                     | [d0b555e0ba](https://linux-hardware.org/?probe=d0b555e0ba) | Mar 17, 2022 |
| HP            | 3647h                       | [fd6766aabb](https://linux-hardware.org/?probe=fd6766aabb) | Mar 11, 2022 |
| ASUSTek       | P5GC-MX/MEDION/SI           | [772e020316](https://linux-hardware.org/?probe=772e020316) | Mar 09, 2022 |
| MSI           | MS-7091                     | [71aaa6a920](https://linux-hardware.org/?probe=71aaa6a920) | Mar 09, 2022 |
| MSI           | MS-7091                     | [b08ddd1115](https://linux-hardware.org/?probe=b08ddd1115) | Mar 09, 2022 |
| ASUSTek       | ROG Maximus XIII HERO       | [e58223cc60](https://linux-hardware.org/?probe=e58223cc60) | Feb 18, 2022 |
| Huanan        | X99-F8 V2.0                 | [23c722f6cf](https://linux-hardware.org/?probe=23c722f6cf) | Feb 18, 2022 |
| Huanan        | X99-F8 V2.0                 | [f4fec6a5be](https://linux-hardware.org/?probe=f4fec6a5be) | Feb 17, 2022 |
| MSI           | Z97 GAMING 5                | [7c66c1b404](https://linux-hardware.org/?probe=7c66c1b404) | Feb 09, 2022 |
| ASUSTek       | X99-DELUXE                  | [4ffe151e7a](https://linux-hardware.org/?probe=4ffe151e7a) | Jan 29, 2022 |
| HP            | 0B4Ch D                     | [ecaec39529](https://linux-hardware.org/?probe=ecaec39529) | Jan 05, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [78d4e04363](https://linux-hardware.org/?probe=78d4e04363) | Dec 16, 2021 |
| GALAX         | B550M                       | [a6866c8a45](https://linux-hardware.org/?probe=a6866c8a45) | Dec 04, 2021 |
| Lenovo        | SHARKBAY NO DPK             | [fd5f409df8](https://linux-hardware.org/?probe=fd5f409df8) | Nov 14, 2021 |
| Lenovo        | SHARKBAY NO DPK             | [a85cc99f78](https://linux-hardware.org/?probe=a85cc99f78) | Nov 14, 2021 |
| ASRock        | X570 Steel Legend           | [18391015f7](https://linux-hardware.org/?probe=18391015f7) | Nov 11, 2021 |
| Gigabyte      | X570 AORUS PRO              | [fbd2076eee](https://linux-hardware.org/?probe=fbd2076eee) | Oct 28, 2021 |
| Gigabyte      | B550M DS3H                  | [ee6a141211](https://linux-hardware.org/?probe=ee6a141211) | Oct 19, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | [5d136cb09b](https://linux-hardware.org/?probe=5d136cb09b) | Aug 13, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Desktops | Percent |
|------------------------------|----------|---------|
| 5.10.0-20-amd64              | 10       | 12.05%  |
| 5.10.0-21-amd64              | 8        | 9.64%   |
| 5.14.0-4mx-amd64             | 6        | 7.23%   |
| 5.10.0-19-amd64              | 6        | 7.23%   |
| 5.10.0-18-amd64              | 5        | 6.02%   |
| 5.10.0-13-amd64              | 5        | 6.02%   |
| 5.10.0-16-amd64              | 4        | 4.82%   |
| 5.10.0-15-amd64              | 4        | 4.82%   |
| 6.0.0-6mx-amd64              | 3        | 3.61%   |
| 5.16.0-5mx-amd64             | 3        | 3.61%   |
| 6.0.0-10.1-liquorix-amd64    | 2        | 2.41%   |
| 5.14.0-3mx-amd64             | 2        | 2.41%   |
| 5.10.0-9-amd64               | 2        | 2.41%   |
| 5.10.0-11-amd64              | 2        | 2.41%   |
| 6.1.0-2mx-amd64              | 1        | 1.2%    |
| 6.0.5-x64v1-xanmod1          | 1        | 1.2%    |
| 6.0.0-4mx-rt-amd64           | 1        | 1.2%    |
| 6.0.0-13.3-liquorix-amd64    | 1        | 1.2%    |
| 5.19.0-4.2-liquorix-amd64    | 1        | 1.2%    |
| 5.19.0-17.2-liquorix-amd64   | 1        | 1.2%    |
| 5.19.0-14.1-liquorix-amd64   | 1        | 1.2%    |
| 5.18.0-4mx-amd64             | 1        | 1.2%    |
| 5.17.0-3mx-amd64             | 1        | 1.2%    |
| 5.16.0-rc5-hwmon-next+       | 1        | 1.2%    |
| 5.16.0-6mx-amd64             | 1        | 1.2%    |
| 5.15.0-2-amd64               | 1        | 1.2%    |
| 5.15.0-0.bpo.2-amd64         | 1        | 1.2%    |
| 5.14.0-2mx-amd64             | 1        | 1.2%    |
| 5.10.52-antix.1-amd64-smp    | 1        | 1.2%    |
| 5.10.113-lkdtm-i386pae       | 1        | 1.2%    |
| 5.10.111-tkg-cfs             | 1        | 1.2%    |
| 5.10.0-18-686-pae            | 1        | 1.2%    |
| 5.10.0-17-amd64              | 1        | 1.2%    |
| 5.10.0-10-amd64              | 1        | 1.2%    |
| 4.19.0-256-antix.1-amd64-smp | 1        | 1.2%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.10.0   | 49       | 59.04%  |
| 5.14.0   | 9        | 10.84%  |
| 6.0.0    | 7        | 8.43%   |
| 5.16.0   | 5        | 6.02%   |
| 5.19.0   | 3        | 3.61%   |
| 5.15.0   | 2        | 2.41%   |
| 6.1.0    | 1        | 1.2%    |
| 6.0.5    | 1        | 1.2%    |
| 5.18.0   | 1        | 1.2%    |
| 5.17.0   | 1        | 1.2%    |
| 5.10.52  | 1        | 1.2%    |
| 5.10.113 | 1        | 1.2%    |
| 5.10.111 | 1        | 1.2%    |
| 4.19.0   | 1        | 1.2%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 52       | 62.65%  |
| 5.14    | 9        | 10.84%  |
| 6.0     | 8        | 9.64%   |
| 5.16    | 5        | 6.02%   |
| 5.19    | 3        | 3.61%   |
| 5.15    | 2        | 2.41%   |
| 6.1     | 1        | 1.2%    |
| 5.18    | 1        | 1.2%    |
| 5.17    | 1        | 1.2%    |
| 4.19    | 1        | 1.2%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 81       | 97.59%  |
| i686   | 2        | 2.41%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| XFCE             | 61       | 73.49%  |
| KDE5             | 19       | 22.89%  |
| lightdm-xsession | 2        | 2.41%   |
| Unknown          | 1        | 1.2%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 83       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 61       | 73.49%  |
| SDDM    | 18       | 21.69%  |
| SLiM    | 3        | 3.61%   |
| GDM     | 1        | 1.2%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 37       | 44.58%  |
| de_DE | 13       | 15.66%  |
| it_IT | 7        | 8.43%   |
| pl_PL | 4        | 4.82%   |
| en_GB | 4        | 4.82%   |
| ru_RU | 3        | 3.61%   |
| sv_SE | 2        | 2.41%   |
| es_MX | 2        | 2.41%   |
| de_CH | 2        | 2.41%   |
| pt_BR | 1        | 1.2%    |
| hu_HU | 1        | 1.2%    |
| fr_FR | 1        | 1.2%    |
| fi_FI | 1        | 1.2%    |
| es_VE | 1        | 1.2%    |
| es_ES | 1        | 1.2%    |
| es_CO | 1        | 1.2%    |
| es_AR | 1        | 1.2%    |
| en_NZ | 1        | 1.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 49       | 59.04%  |
| EFI  | 34       | 40.96%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 71       | 85.54%  |
| Overlay  | 8        | 9.64%   |
| Xfs      | 1        | 1.2%    |
| Reiserfs | 1        | 1.2%    |
| Ext3     | 1        | 1.2%    |
| Btrfs    | 1        | 1.2%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 48       | 57.83%  |
| MBR  | 35       | 42.17%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 51       | 61.45%  |
| Yes       | 32       | 38.55%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 46       | 55.42%  |
| No        | 37       | 44.58%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 15       | 18.07%  |
| Gigabyte Technology                  | 11       | 13.25%  |
| MSI                                  | 10       | 12.05%  |
| Dell                                 | 8        | 9.64%   |
| Hewlett-Packard                      | 6        | 7.23%   |
| Lenovo                               | 5        | 6.02%   |
| ASRock                               | 5        | 6.02%   |
| Intel                                | 3        | 3.61%   |
| Unknown                              | 3        | 3.61%   |
| Pegatron                             | 2        | 2.41%   |
| Fujitsu                              | 2        | 2.41%   |
| Biostar                              | 2        | 2.41%   |
| ZOTAC                                | 1        | 1.2%    |
| SIRAGON                              | 1        | 1.2%    |
| Shenzhen Meigao Electronic Equipment | 1        | 1.2%    |
| MP                                   | 1        | 1.2%    |
| Medion                               | 1        | 1.2%    |
| Huanan                               | 1        | 1.2%    |
| GALAX                                | 1        | 1.2%    |
| Foxconn                              | 1        | 1.2%    |
| ECS                                  | 1        | 1.2%    |
| BESSTAR Tech                         | 1        | 1.2%    |
| AOpen                                | 1        | 1.2%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Desktops | Percent |
|---------------------------------------------|----------|---------|
| ASUS All Series                             | 4        | 4.82%   |
| Unknown                                     | 4        | 4.82%   |
| MSI MS-7C91                                 | 2        | 2.41%   |
| Gigabyte GA-MA785GM-US2H                    | 2        | 2.41%   |
| Dell OptiPlex 755                           | 2        | 2.41%   |
| ASUS ROG Maximus XIII HERO                  | 2        | 2.41%   |
| SIRAGON AIO-5150                            | 1        | 1.2%    |
| Shenzhen Meigao Electronic Equipment UM450  | 1        | 1.2%    |
| Pegatron FQ425AA-ABA a6655f                 | 1        | 1.2%    |
| Pegatron 2AD5                               | 1        | 1.2%    |
| MSI MS-7C37                                 | 1        | 1.2%    |
| MSI MS-7B98                                 | 1        | 1.2%    |
| MSI MS-7B53                                 | 1        | 1.2%    |
| MSI MS-7A63                                 | 1        | 1.2%    |
| MSI MS-7A34                                 | 1        | 1.2%    |
| MSI MS-7917                                 | 1        | 1.2%    |
| MSI MS-7823                                 | 1        | 1.2%    |
| MSI MS-7758                                 | 1        | 1.2%    |
| MP MS-7848                                  | 1        | 1.2%    |
| Medion Akoya P5330 E MD8876/2458            | 1        | 1.2%    |
| Lenovo ThinkStation P620 30E0CTO1WW         | 1        | 1.2%    |
| Lenovo ThinkCentre M75s Gen 2 11JAS0CJ00    | 1        | 1.2%    |
| Lenovo ThinkCentre M58 7638CB8              | 1        | 1.2%    |
| Lenovo IdeaCentre Gaming5 17IAB7 90T00007US | 1        | 1.2%    |
| Lenovo 10AAS1QB0B                           | 1        | 1.2%    |
| Intel V1.3                                  | 1        | 1.2%    |
| Intel DH55TC AAE70932-303                   | 1        | 1.2%    |
| Intel D34010WYK H14771-303                  | 1        | 1.2%    |
| Huanan X99-F8                               | 1        | 1.2%    |
| HP Z400 Workstation                         | 1        | 1.2%    |
| HP Compaq Elite 8300 CMT                    | 1        | 1.2%    |
| HP Compaq dc5850 Microtower                 | 1        | 1.2%    |
| HP Compaq 8100 Elite SFF PC                 | 1        | 1.2%    |
| HP Compaq 8000 Elite CMT PC                 | 1        | 1.2%    |
| HP 260 G2 DM                                | 1        | 1.2%    |
| Gigabyte Z77X-D3H                           | 1        | 1.2%    |
| Gigabyte Z390 UD                            | 1        | 1.2%    |
| Gigabyte X570 AORUS PRO                     | 1        | 1.2%    |
| Gigabyte PH67A-D3-B3                        | 1        | 1.2%    |
| Gigabyte H410M S2H V3                       | 1        | 1.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Dell OptiPlex                              | 7        | 8.43%   |
| HP Compaq                                  | 4        | 4.82%   |
| ASUS All                                   | 4        | 4.82%   |
| Unknown                                    | 4        | 4.82%   |
| MSI MS-7C91                                | 2        | 2.41%   |
| Lenovo ThinkCentre                         | 2        | 2.41%   |
| Gigabyte GA-MA785GM-US2H                   | 2        | 2.41%   |
| Gigabyte B550M                             | 2        | 2.41%   |
| ASUS TUF                                   | 2        | 2.41%   |
| ASUS ROG                                   | 2        | 2.41%   |
| ASUS P5GC-MX                               | 2        | 2.41%   |
| SIRAGON AIO-5150                           | 1        | 1.2%    |
| Shenzhen Meigao Electronic Equipment UM450 | 1        | 1.2%    |
| Pegatron FQ425AA-ABA                       | 1        | 1.2%    |
| Pegatron 2AD5                              | 1        | 1.2%    |
| MSI MS-7C37                                | 1        | 1.2%    |
| MSI MS-7B98                                | 1        | 1.2%    |
| MSI MS-7B53                                | 1        | 1.2%    |
| MSI MS-7A63                                | 1        | 1.2%    |
| MSI MS-7A34                                | 1        | 1.2%    |
| MSI MS-7917                                | 1        | 1.2%    |
| MSI MS-7823                                | 1        | 1.2%    |
| MSI MS-7758                                | 1        | 1.2%    |
| MP MS-7848                                 | 1        | 1.2%    |
| Medion Akoya                               | 1        | 1.2%    |
| Lenovo ThinkStation                        | 1        | 1.2%    |
| Lenovo IdeaCentre                          | 1        | 1.2%    |
| Lenovo 10AAS1QB0B                          | 1        | 1.2%    |
| Intel V1.3                                 | 1        | 1.2%    |
| Intel DH55TC                               | 1        | 1.2%    |
| Intel D34010WYK                            | 1        | 1.2%    |
| Huanan X99-F8                              | 1        | 1.2%    |
| HP Z400                                    | 1        | 1.2%    |
| HP 260                                     | 1        | 1.2%    |
| Gigabyte Z77X-D3H                          | 1        | 1.2%    |
| Gigabyte Z390                              | 1        | 1.2%    |
| Gigabyte X570                              | 1        | 1.2%    |
| Gigabyte PH67A-D3-B3                       | 1        | 1.2%    |
| Gigabyte H410M                             | 1        | 1.2%    |
| Gigabyte GA-MA770-UD3                      | 1        | 1.2%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 8        | 9.64%   |
| 2022 | 7        | 8.43%   |
| 2018 | 7        | 8.43%   |
| 2021 | 6        | 7.23%   |
| 2014 | 6        | 7.23%   |
| 2013 | 6        | 7.23%   |
| 2012 | 6        | 7.23%   |
| 2009 | 6        | 7.23%   |
| 2019 | 5        | 6.02%   |
| 2016 | 5        | 6.02%   |
| 2007 | 5        | 6.02%   |
| 2011 | 4        | 4.82%   |
| 2010 | 4        | 4.82%   |
| 2008 | 4        | 4.82%   |
| 2017 | 2        | 2.41%   |
| 2015 | 2        | 2.41%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 83       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 83       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 83       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 22       | 26.51%  |
| 4.01-8.0    | 18       | 21.69%  |
| 32.01-64.0  | 17       | 20.48%  |
| 16.01-24.0  | 10       | 12.05%  |
| 3.01-4.0    | 9        | 10.84%  |
| 64.01-256.0 | 3        | 3.61%   |
| 24.01-32.0  | 2        | 2.41%   |
| 2.01-3.0    | 2        | 2.41%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 32       | 38.1%   |
| 2.01-3.0   | 22       | 26.19%  |
| 3.01-4.0   | 13       | 15.48%  |
| 4.01-8.0   | 11       | 13.1%   |
| 8.01-16.0  | 3        | 3.57%   |
| 0.51-1.0   | 2        | 2.38%   |
| 16.01-24.0 | 1        | 1.19%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 29       | 34.94%  |
| 2      | 20       | 24.1%   |
| 3      | 19       | 22.89%  |
| 4      | 8        | 9.64%   |
| 5      | 4        | 4.82%   |
| 8      | 2        | 2.41%   |
| 7      | 1        | 1.2%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 42       | 50.6%   |
| No        | 41       | 49.4%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 82       | 98.8%   |
| No        | 1        | 1.2%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 42       | 50.6%   |
| Yes       | 41       | 49.4%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 62       | 74.7%   |
| Yes       | 21       | 25.3%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 23       | 27.71%  |
| Germany     | 13       | 15.66%  |
| Italy       | 7        | 8.43%   |
| Poland      | 5        | 6.02%   |
| Russia      | 3        | 3.61%   |
| Finland     | 3        | 3.61%   |
| Venezuela   | 2        | 2.41%   |
| UK          | 2        | 2.41%   |
| Switzerland | 2        | 2.41%   |
| Sweden      | 2        | 2.41%   |
| Mexico      | 2        | 2.41%   |
| India       | 2        | 2.41%   |
| France      | 2        | 2.41%   |
| Canada      | 2        | 2.41%   |
| Spain       | 1        | 1.2%    |
| Singapore   | 1        | 1.2%    |
| Romania     | 1        | 1.2%    |
| New Zealand | 1        | 1.2%    |
| Netherlands | 1        | 1.2%    |
| Indonesia   | 1        | 1.2%    |
| Hungary     | 1        | 1.2%    |
| Greece      | 1        | 1.2%    |
| Estonia     | 1        | 1.2%    |
| Colombia    | 1        | 1.2%    |
| Brazil      | 1        | 1.2%    |
| Australia   | 1        | 1.2%    |
| Argentina   | 1        | 1.2%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Desktops | Percent |
|---------------|----------|---------|
| Mesquite      | 2        | 2.41%   |
| Krakow        | 2        | 2.41%   |
| Houston       | 2        | 2.41%   |
| Ettingen      | 2        | 2.41%   |
| Berlin        | 2        | 2.41%   |
| Volos         | 1        | 1.2%    |
| Voghera       | 1        | 1.2%    |
| Vilhelmina    | 1        | 1.2%    |
| Vasco da Gama | 1        | 1.2%    |
| Vaidasoo      | 1        | 1.2%    |
| Tuglie        | 1        | 1.2%    |
| Toronto       | 1        | 1.2%    |
| Tampere       | 1        | 1.2%    |
| Stevens Point | 1        | 1.2%    |
| Stafford      | 1        | 1.2%    |
| St Petersburg | 1        | 1.2%    |
| Sollentuna    | 1        | 1.2%    |
| Singapore     | 1        | 1.2%    |
| Seelbach      | 1        | 1.2%    |
| San Diego     | 1        | 1.2%    |
| Rzeszów      | 1        | 1.2%    |
| Rosporden     | 1        | 1.2%    |
| Reno          | 1        | 1.2%    |
| Rathenow      | 1        | 1.2%    |
| Puebla City   | 1        | 1.2%    |
| Portland      | 1        | 1.2%    |
| Pompano Beach | 1        | 1.2%    |
| Pila          | 1        | 1.2%    |
| Piedmont      | 1        | 1.2%    |
| Pachuca       | 1        | 1.2%    |
| Otwock        | 1        | 1.2%    |
| Osnabrück    | 1        | 1.2%    |
| Ocala         | 1        | 1.2%    |
| Normal        | 1        | 1.2%    |
| Narbonne      | 1        | 1.2%    |
| Moscow        | 1        | 1.2%    |
| Milwaukee     | 1        | 1.2%    |
| Merzig        | 1        | 1.2%    |
| Maringá      | 1        | 1.2%    |
| Lodi          | 1        | 1.2%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Samsung Electronics       | 29       | 49     | 18.24%  |
| Seagate                   | 28       | 36     | 17.61%  |
| WDC                       | 21       | 28     | 13.21%  |
| Kingston                  | 17       | 18     | 10.69%  |
| Toshiba                   | 8        | 9      | 5.03%   |
| China                     | 7        | 8      | 4.4%    |
| SanDisk                   | 6        | 7      | 3.77%   |
| Hitachi                   | 5        | 6      | 3.14%   |
| Crucial                   | 4        | 4      | 2.52%   |
| Unknown                   | 3        | 5      | 1.89%   |
| PNY                       | 3        | 4      | 1.89%   |
| Corsair                   | 3        | 3      | 1.89%   |
| Transcend                 | 2        | 2      | 1.26%   |
| GOODRAM                   | 2        | 2      | 1.26%   |
| Apacer                    | 2        | 2      | 1.26%   |
| A-DATA Technology         | 2        | 2      | 1.26%   |
| Team                      | 1        | 1      | 0.63%   |
| SPCC                      | 1        | 1      | 0.63%   |
| Silicon Motion            | 1        | 1      | 0.63%   |
| Phison Electronics        | 1        | 1      | 0.63%   |
| Phison                    | 1        | 1      | 0.63%   |
| OCZ                       | 1        | 1      | 0.63%   |
| Mushkin                   | 1        | 1      | 0.63%   |
| Micron/Crucial Technology | 1        | 1      | 0.63%   |
| Micron Technology         | 1        | 1      | 0.63%   |
| Maxtor                    | 1        | 1      | 0.63%   |
| JMicron Technology        | 1        | 1      | 0.63%   |
| Intel                     | 1        | 1      | 0.63%   |
| HGST                      | 1        | 1      | 0.63%   |
| External                  | 1        | 1      | 0.63%   |
| CT1000P3                  | 1        | 1      | 0.63%   |
| Avant                     | 1        | 1      | 0.63%   |
| Acer                      | 1        | 1      | 0.63%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Kingston SA400S37480G 480GB SSD  | 5        | 2.63%   |
| Seagate ST2000DM008-2FR102 2TB   | 3        | 1.58%   |
| SanDisk SDSSDA240G 240GB         | 3        | 1.58%   |
| Samsung SSD 850 EVO 250GB        | 3        | 1.58%   |
| Samsung SSD 840 Series 120GB     | 3        | 1.58%   |
| Kingston SV300S37A240G 240GB SSD | 3        | 1.58%   |
| Unknown SD/MMC 2GB               | 2        | 1.05%   |
| Unknown M.S./M.S.Pro/HG 16GB     | 2        | 1.05%   |
| Toshiba HDWD110 1TB              | 2        | 1.05%   |
| Toshiba DT01ACA100 1TB           | 2        | 1.05%   |
| Seagate ST500LM021-1KJ152 500GB  | 2        | 1.05%   |
| Seagate ST3500413AS 500GB        | 2        | 1.05%   |
| Seagate ST2000DM001-1ER164 2TB   | 2        | 1.05%   |
| Samsung SSD 980 PRO 1TB          | 2        | 1.05%   |
| Samsung SSD 970 PRO 512GB        | 2        | 1.05%   |
| Samsung SSD 970 EVO Plus 500GB   | 2        | 1.05%   |
| Samsung SSD 970 EVO Plus 1TB     | 2        | 1.05%   |
| Samsung SSD 870 EVO 500GB        | 2        | 1.05%   |
| Samsung SSD 860 EVO 500GB        | 2        | 1.05%   |
| Samsung SSD 850 EVO 500GB        | 2        | 1.05%   |
| Samsung SSD 850 EVO 1TB          | 2        | 1.05%   |
| Kingston SA400S37120G 120GB SSD  | 2        | 1.05%   |
| Corsair MP400 2TB                | 2        | 1.05%   |
| China SATA SSD 512GB             | 2        | 1.05%   |
| WDC WDS500G2B0C-00PXH0 500GB     | 1        | 0.53%   |
| WDC WDS100T2B0A-00SM50 1TB SSD   | 1        | 0.53%   |
| WDC WD800AAJS-60M0A0 80GB        | 1        | 0.53%   |
| WDC WD60EZRZ-00RWYB1 6TB         | 1        | 0.53%   |
| WDC WD60EFRX-68L0BN1 6TB         | 1        | 0.53%   |
| WDC WD5002AALX-00J37A0 500GB     | 1        | 0.53%   |
| WDC WD5000AVCS-632DY1 500GB      | 1        | 0.53%   |
| WDC WD5000AAKS-00E4A0 500GB      | 1        | 0.53%   |
| WDC WD40EFRX-68WT0N0 4TB         | 1        | 0.53%   |
| WDC WD3200AAKS-75L9A0 320GB      | 1        | 0.53%   |
| WDC WD3200AAKS-00UU3A0 320GB     | 1        | 0.53%   |
| WDC WD30EFRX-68AX9N0 3TB         | 1        | 0.53%   |
| WDC WD2500JS-08NCB1 250GB        | 1        | 0.53%   |
| WDC WD2500AAJS-00B4A0 250GB      | 1        | 0.53%   |
| WDC WD20EZRX-22D8PB0 2TB         | 1        | 0.53%   |
| WDC WD20EZAZ-00GGJB0 2TB         | 1        | 0.53%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 28       | 36     | 41.79%  |
| WDC                 | 19       | 26     | 28.36%  |
| Toshiba             | 8        | 9      | 11.94%  |
| Hitachi             | 5        | 6      | 7.46%   |
| Samsung Electronics | 3        | 3      | 4.48%   |
| Unknown             | 1        | 1      | 1.49%   |
| Maxtor              | 1        | 1      | 1.49%   |
| HGST                | 1        | 1      | 1.49%   |
| External            | 1        | 1      | 1.49%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 21       | 27     | 30.88%  |
| Kingston            | 14       | 15     | 20.59%  |
| China               | 7        | 8      | 10.29%  |
| SanDisk             | 5        | 6      | 7.35%   |
| Crucial             | 3        | 3      | 4.41%   |
| Transcend           | 2        | 2      | 2.94%   |
| PNY                 | 2        | 2      | 2.94%   |
| GOODRAM             | 2        | 2      | 2.94%   |
| A-DATA Technology   | 2        | 2      | 2.94%   |
| WDC                 | 1        | 1      | 1.47%   |
| Team                | 1        | 1      | 1.47%   |
| SPCC                | 1        | 1      | 1.47%   |
| OCZ                 | 1        | 1      | 1.47%   |
| Mushkin             | 1        | 1      | 1.47%   |
| Micron Technology   | 1        | 1      | 1.47%   |
| CT1000P3            | 1        | 1      | 1.47%   |
| Avant               | 1        | 1      | 1.47%   |
| Apacer              | 1        | 1      | 1.47%   |
| Acer                | 1        | 1      | 1.47%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 56       | 77     | 39.16%  |
| HDD     | 56       | 84     | 39.16%  |
| NVMe    | 27       | 35     | 18.88%  |
| Unknown | 3        | 5      | 2.1%    |
| MMC     | 1        | 1      | 0.7%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 75       | 154    | 67.57%  |
| NVMe | 27       | 35     | 24.32%  |
| SAS  | 8        | 12     | 7.21%   |
| MMC  | 1        | 1      | 0.9%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 58       | 93     | 50.88%  |
| 0.51-1.0   | 33       | 38     | 28.95%  |
| 1.01-2.0   | 13       | 18     | 11.4%   |
| 3.01-4.0   | 4        | 4      | 3.51%   |
| 2.01-3.0   | 3        | 3      | 2.63%   |
| 4.01-10.0  | 2        | 4      | 1.75%   |
| 10.01-20.0 | 1        | 1      | 0.88%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 21       | 25.3%   |
| 251-500        | 17       | 20.48%  |
| 1001-2000      | 12       | 14.46%  |
| 501-1000       | 9        | 10.84%  |
| More than 3000 | 6        | 7.23%   |
| 2001-3000      | 6        | 7.23%   |
| 51-100         | 6        | 7.23%   |
| 1-20           | 4        | 4.82%   |
| 21-50          | 2        | 2.41%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 20       | 23.81%  |
| 21-50          | 16       | 19.05%  |
| 101-250        | 16       | 19.05%  |
| 51-100         | 9        | 10.71%  |
| 1001-2000      | 7        | 8.33%   |
| 251-500        | 6        | 7.14%   |
| 501-1000       | 6        | 7.14%   |
| More than 3000 | 2        | 2.38%   |
| 2001-3000      | 2        | 2.38%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Desktops | Drives | Percent |
|------------------------------------------|----------|--------|---------|
| WDC WDS100T2B0A-00SM50 1TB SSD           | 1        | 1      | 3.85%   |
| WDC WD3200AAKS-00UU3A0 320GB             | 1        | 1      | 3.85%   |
| WDC WD2500AAJS-00B4A0 250GB              | 1        | 1      | 3.85%   |
| WDC WD10EADS-98M2B0 1TB                  | 1        | 1      | 3.85%   |
| WDC WD10EADS-00M2B0 1TB                  | 1        | 1      | 3.85%   |
| Toshiba MQ01ABF050 500GB                 | 1        | 1      | 3.85%   |
| Seagate ST500LT012-9WS142 500GB          | 1        | 1      | 3.85%   |
| Seagate ST500LM021-1KJ152 500GB          | 1        | 1      | 3.85%   |
| Seagate ST380815AS 80GB                  | 1        | 1      | 3.85%   |
| Seagate ST3500413AS 500GB                | 1        | 1      | 3.85%   |
| Seagate ST3360320AS 360GB                | 1        | 1      | 3.85%   |
| Seagate ST320LT020-9YG142 320GB          | 1        | 1      | 3.85%   |
| Seagate ST320LT012-1DG14C 320GB          | 1        | 2      | 3.85%   |
| Seagate ST250DM000-1BD141 250GB          | 1        | 1      | 3.85%   |
| Seagate ST2000DM001-1ER164 2TB           | 1        | 1      | 3.85%   |
| Seagate ST1000VM002-1CT162 1TB           | 1        | 1      | 3.85%   |
| Samsung Electronics SSD 870 EVO 500GB    | 1        | 1      | 3.85%   |
| Samsung Electronics SSD 850 EVO 500GB    | 1        | 1      | 3.85%   |
| Samsung Electronics SSD 850 EVO 1TB      | 1        | 2      | 3.85%   |
| Samsung Electronics SSD 840 Series 120GB | 1        | 1      | 3.85%   |
| Maxtor 4K040H2 40GB                      | 1        | 1      | 3.85%   |
| Hitachi HTS545050A7E380 500GB            | 1        | 1      | 3.85%   |
| Hitachi HDS721050CLA362 500GB            | 1        | 1      | 3.85%   |
| HGST HTS545050A7E380 500GB               | 1        | 1      | 3.85%   |
| GOODRAM SSDPR-CL100-480-G3 480GB         | 1        | 1      | 3.85%   |
| China SSD 512GB                          | 1        | 1      | 3.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 10       | 11     | 40%     |
| WDC                 | 5        | 5      | 20%     |
| Samsung Electronics | 4        | 5      | 16%     |
| Toshiba             | 1        | 1      | 4%      |
| Maxtor              | 1        | 1      | 4%      |
| Hitachi             | 1        | 2      | 4%      |
| HGST                | 1        | 1      | 4%      |
| GOODRAM             | 1        | 1      | 4%      |
| China               | 1        | 1      | 4%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 10       | 11     | 55.56%  |
| WDC     | 4        | 4      | 22.22%  |
| Toshiba | 1        | 1      | 5.56%   |
| Maxtor  | 1        | 1      | 5.56%   |
| Hitachi | 1        | 2      | 5.56%   |
| HGST    | 1        | 1      | 5.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 17       | 20     | 70.83%  |
| SSD  | 7        | 8      | 29.17%  |

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


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 75       | 160    | 68.81%  |
| Malfunc  | 24       | 28     | 22.02%  |
| Detected | 10       | 14     | 9.17%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 57       | 47.9%   |
| AMD                         | 24       | 20.17%  |
| Samsung Electronics         | 12       | 10.08%  |
| Phison Electronics          | 7        | 5.88%   |
| ASMedia Technology          | 6        | 5.04%   |
| Kingston Technology Company | 3        | 2.52%   |
| SanDisk                     | 2        | 1.68%   |
| Micron/Crucial Technology   | 2        | 1.68%   |
| VIA Technologies            | 1        | 0.84%   |
| ULi Electronics             | 1        | 0.84%   |
| Silicon Motion              | 1        | 0.84%   |
| Nvidia                      | 1        | 0.84%   |
| Marvell Technology Group    | 1        | 0.84%   |
| LSI Logic / Symbios Logic   | 1        | 0.84%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 9        | 6.12%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 7        | 4.76%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 6        | 4.08%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 6        | 4.08%   |
| AMD 500 Series Chipset SATA Controller                                                  | 6        | 4.08%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5        | 3.4%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 4        | 2.72%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4        | 2.72%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 3        | 2.04%   |
| Phison E12 NVMe Controller                                                              | 3        | 2.04%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3        | 2.04%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3        | 2.04%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 3        | 2.04%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 3        | 2.04%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 3        | 2.04%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 3        | 2.04%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3        | 2.04%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3        | 2.04%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2        | 1.36%   |
| Samsung NVMe SSD Controller 980                                                         | 2        | 1.36%   |
| Phison PS5013 E13 NVMe Controller                                                       | 2        | 1.36%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 2        | 1.36%   |
| Intel SATA Controller [RAID mode]                                                       | 2        | 1.36%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2        | 1.36%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2        | 1.36%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 2        | 1.36%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2        | 1.36%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 2        | 1.36%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 1.36%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 1.36%   |
| Intel 5 Series/3400 Series Chipset PT IDER Controller                                   | 2        | 1.36%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2        | 1.36%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 2        | 1.36%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 2        | 1.36%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 2        | 1.36%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2        | 1.36%   |
| AMD 400 Series Chipset SATA Controller                                                  | 2        | 1.36%   |
| AMD 300 Series Chipset SATA Controller                                                  | 2        | 1.36%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 1        | 0.68%   |
| VIA VIA VT6420 SATA RAID Controller                                                     | 1        | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 72       | 59.5%   |
| NVMe | 27       | 22.31%  |
| IDE  | 18       | 14.88%  |
| RAID | 3        | 2.48%   |
| SCSI | 1        | 0.83%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 58       | 69.88%  |
| AMD    | 25       | 30.12%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i7-3770 CPU @ 3.40GHz            | 3        | 3.61%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 3        | 3.61%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 3        | 3.61%   |
| Intel Core i7-5820K CPU @ 3.30GHz           | 2        | 2.41%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 2        | 2.41%   |
| Intel Core i5-3350P CPU @ 3.10GHz           | 2        | 2.41%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 2        | 2.41%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 2        | 2.41%   |
| AMD Athlon II X4 630 Processor              | 2        | 2.41%   |
| Intel Xeon W-2123 CPU @ 3.60GHz             | 1        | 1.2%    |
| Intel Xeon CPU W3565 @ 3.20GHz              | 1        | 1.2%    |
| Intel Xeon CPU E5520 @ 2.27GHz              | 1        | 1.2%    |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz         | 1        | 1.2%    |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 1        | 1.2%    |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 1        | 1.2%    |
| Intel Pentium CPU 2030M @ 2.50GHz           | 1        | 1.2%    |
| Intel Pentium 4 CPU 3.00GHz                 | 1        | 1.2%    |
| Intel Core M-5Y10c CPU @ 0.80GHz            | 1        | 1.2%    |
| Intel Core i9-9900K CPU @ 3.60GHz           | 1        | 1.2%    |
| Intel Core i9-10850K CPU @ 3.60GHz          | 1        | 1.2%    |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1        | 1.2%    |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1        | 1.2%    |
| Intel Core i7-2600K CPU @ 3.40GHz           | 1        | 1.2%    |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1        | 1.2%    |
| Intel Core i7 CPU 870 @ 2.93GHz             | 1        | 1.2%    |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1        | 1.2%    |
| Intel Core i5-8400 CPU @ 2.80GHz            | 1        | 1.2%    |
| Intel Core i5-6600K CPU @ 3.50GHz           | 1        | 1.2%    |
| Intel Core i5-6402P CPU @ 2.80GHz           | 1        | 1.2%    |
| Intel Core i5-6200U CPU @ 2.30GHz           | 1        | 1.2%    |
| Intel Core i5-4690K CPU @ 3.50GHz           | 1        | 1.2%    |
| Intel Core i5-4570T CPU @ 2.90GHz           | 1        | 1.2%    |
| Intel Core i5-4460 CPU @ 3.20GHz            | 1        | 1.2%    |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1        | 1.2%    |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 1        | 1.2%    |
| Intel Core i3-4130 CPU @ 3.40GHz            | 1        | 1.2%    |
| Intel Core i3-4010U CPU @ 1.70GHz           | 1        | 1.2%    |
| Intel Core i3-2350M CPU @ 2.30GHz           | 1        | 1.2%    |
| Intel Core i3-2120 CPU @ 3.30GHz            | 1        | 1.2%    |
| Intel Core i3-2100 CPU @ 3.10GHz            | 1        | 1.2%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 13       | 15.66%  |
| Intel Core i7           | 11       | 13.25%  |
| Intel Core i3           | 10       | 12.05%  |
| AMD Ryzen 5             | 8        | 9.64%   |
| Intel Core 2 Duo        | 6        | 7.23%   |
| AMD Ryzen 7             | 5        | 6.02%   |
| Other                   | 4        | 4.82%   |
| Intel Xeon              | 4        | 4.82%   |
| Intel Celeron           | 3        | 3.61%   |
| AMD Athlon II X4        | 3        | 3.61%   |
| Intel Core i9           | 2        | 2.41%   |
| AMD Ryzen 3             | 2        | 2.41%   |
| AMD Phenom              | 2        | 2.41%   |
| Intel Pentium Dual-Core | 1        | 1.2%    |
| Intel Pentium Dual      | 1        | 1.2%    |
| Intel Pentium 4         | 1        | 1.2%    |
| Intel Pentium           | 1        | 1.2%    |
| Intel Core M            | 1        | 1.2%    |
| AMD Ryzen Threadripper  | 1        | 1.2%    |
| AMD Ryzen 9             | 1        | 1.2%    |
| AMD Ryzen 5 PRO         | 1        | 1.2%    |
| AMD Phenom II X4        | 1        | 1.2%    |
| AMD Athlon              | 1        | 1.2%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 31       | 37.35%  |
| 2      | 24       | 28.92%  |
| 6      | 12       | 14.46%  |
| 8      | 9        | 10.84%  |
| 12     | 4        | 4.82%   |
| 10     | 2        | 2.41%   |
| 1      | 1        | 1.2%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 82       | 98.8%   |
| 2      | 1        | 1.2%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 48       | 57.83%  |
| 1      | 35       | 42.17%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 83       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 9        | 10.84%  |
| 0x306a9    | 7        | 8.43%   |
| 0x306c3    | 6        | 7.23%   |
| 0x206a7    | 5        | 6.02%   |
| 0x1067a    | 4        | 4.82%   |
| 0x906ed    | 3        | 3.61%   |
| 0x08701021 | 3        | 3.61%   |
| 0x08108109 | 3        | 3.61%   |
| 0x0800820d | 3        | 3.61%   |
| 0x010000db | 3        | 3.61%   |
| 0x6fd      | 2        | 2.41%   |
| 0x506e3    | 2        | 2.41%   |
| 0x306f2    | 2        | 2.41%   |
| 0x20655    | 2        | 2.41%   |
| 0x106e5    | 2        | 2.41%   |
| 0x01000083 | 2        | 2.41%   |
| 0xf49      | 1        | 1.2%    |
| 0xa0671    | 1        | 1.2%    |
| 0xa0655    | 1        | 1.2%    |
| 0xa0653    | 1        | 1.2%    |
| 0x906ea    | 1        | 1.2%    |
| 0x906e9    | 1        | 1.2%    |
| 0x906a4    | 1        | 1.2%    |
| 0x90672    | 1        | 1.2%    |
| 0x706a1    | 1        | 1.2%    |
| 0x506c9    | 1        | 1.2%    |
| 0x50654    | 1        | 1.2%    |
| 0x406c3    | 1        | 1.2%    |
| 0x40651    | 1        | 1.2%    |
| 0x306d4    | 1        | 1.2%    |
| 0x106a5    | 1        | 1.2%    |
| 0x10676    | 1        | 1.2%    |
| 0x0a50000d | 1        | 1.2%    |
| 0x0a20120a | 1        | 1.2%    |
| 0x0a201016 | 1        | 1.2%    |
| 0x0a201009 | 1        | 1.2%    |
| 0x08600106 | 1        | 1.2%    |
| 0x08301039 | 1        | 1.2%    |
| 0x08101016 | 1        | 1.2%    |
| 0x08001138 | 1        | 1.2%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Haswell       | 12       | 14.46%  |
| IvyBridge     | 7        | 8.43%   |
| Zen+          | 6        | 7.23%   |
| Penryn        | 6        | 7.23%   |
| K10           | 6        | 7.23%   |
| Zen 3         | 5        | 6.02%   |
| Zen 2         | 5        | 6.02%   |
| SandyBridge   | 5        | 6.02%   |
| KabyLake      | 5        | 6.02%   |
| Skylake       | 4        | 4.82%   |
| Nehalem       | 4        | 4.82%   |
| Zen           | 3        | 3.61%   |
| Unknown       | 3        | 3.61%   |
| Westmere      | 2        | 2.41%   |
| Core          | 2        | 2.41%   |
| CometLake     | 2        | 2.41%   |
| Silvermont    | 1        | 1.2%    |
| NetBurst      | 1        | 1.2%    |
| Icelake       | 1        | 1.2%    |
| Goldmont plus | 1        | 1.2%    |
| Goldmont      | 1        | 1.2%    |
| Broadwell     | 1        | 1.2%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 33       | 35.87%  |
| Nvidia | 31       | 33.7%   |
| AMD    | 28       | 30.43%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 4        | 4.3%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 3.23%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 3        | 3.23%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3        | 3.23%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3        | 3.23%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 3        | 3.23%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 3.23%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3        | 3.23%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 3        | 3.23%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 2        | 2.15%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 2        | 2.15%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 2.15%   |
| Intel Core Processor Integrated Graphics Controller                         | 2        | 2.15%   |
| AMD RS880 [Radeon HD 4200]                                                  | 2        | 2.15%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 2        | 2.15%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2        | 2.15%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 1.08%   |
| Nvidia NV44A [GeForce 6200]                                                 | 1        | 1.08%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 1.08%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 1.08%   |
| Nvidia GP107GL [Quadro P1000]                                               | 1        | 1.08%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 1.08%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 1.08%   |
| Nvidia GM107GL [Quadro K620]                                                | 1        | 1.08%   |
| Nvidia GK208 [GeForce GT 635]                                               | 1        | 1.08%   |
| Nvidia GK107GL [Quadro K600]                                                | 1        | 1.08%   |
| Nvidia GF116 [GeForce GT 640 OEM]                                           | 1        | 1.08%   |
| Nvidia GF114 [GeForce GTX 560 Ti]                                           | 1        | 1.08%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 1.08%   |
| Nvidia GF106 [GeForce GTS 450]                                              | 1        | 1.08%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 1        | 1.08%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 1        | 1.08%   |
| Nvidia G94GL [Quadro FX 1800]                                               | 1        | 1.08%   |
| Nvidia G92 [GeForce 9800 GT]                                                | 1        | 1.08%   |
| Nvidia G86 [GeForce 8500 GT]                                                | 1        | 1.08%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 1        | 1.08%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 1.08%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 1        | 1.08%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 1        | 1.08%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1        | 1.08%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x Nvidia   | 30       | 36.14%  |
| 1 x Intel    | 25       | 30.12%  |
| 1 x AMD      | 25       | 30.12%  |
| Intel + AMD  | 2        | 2.41%   |
| AMD + Nvidia | 1        | 1.2%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 59       | 71.08%  |
| Proprietary | 19       | 22.89%  |
| Unknown     | 5        | 6.02%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 31       | 36.9%   |
| 1.01-2.0   | 12       | 14.29%  |
| 3.01-4.0   | 11       | 13.1%   |
| 0.51-1.0   | 10       | 11.9%   |
| 7.01-8.0   | 9        | 10.71%  |
| 0.01-0.5   | 7        | 8.33%   |
| 8.01-16.0  | 3        | 3.57%   |
| 2.01-3.0   | 1        | 1.19%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 15       | 17.05%  |
| Dell                 | 10       | 11.36%  |
| Hewlett-Packard      | 8        | 9.09%   |
| Acer                 | 6        | 6.82%   |
| Goldstar             | 5        | 5.68%   |
| Sony                 | 4        | 4.55%   |
| Fujitsu Siemens      | 4        | 4.55%   |
| Philips              | 3        | 3.41%   |
| Lenovo               | 3        | 3.41%   |
| Iiyama               | 3        | 3.41%   |
| Eizo                 | 3        | 3.41%   |
| AOC                  | 3        | 3.41%   |
| Ancor Communications | 3        | 3.41%   |
| Medion               | 2        | 2.27%   |
| BenQ                 | 2        | 2.27%   |
| Xiaomi               | 1        | 1.14%   |
| Vizio                | 1        | 1.14%   |
| Vestel Elektronik    | 1        | 1.14%   |
| SAC                  | 1        | 1.14%   |
| RTK                  | 1        | 1.14%   |
| Panasonic            | 1        | 1.14%   |
| NEC Computers        | 1        | 1.14%   |
| MSI                  | 1        | 1.14%   |
| MiTAC                | 1        | 1.14%   |
| LG Electronics       | 1        | 1.14%   |
| Grundig              | 1        | 1.14%   |
| Gigabyte Technology  | 1        | 1.14%   |
| CTV                  | 1        | 1.14%   |
| ASUSTek Computer     | 1        | 1.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Sony SDM-M81 SNY0480 1280x1024 359x287mm 18.1-inch                     | 2        | 2.13%   |
| Samsung Electronics C32JG5x SAM0FE0 2560x1440 697x392mm 31.5-inch      | 2        | 2.13%   |
| Medion MD22322 MEB8101 2560x1440 699x393mm 31.6-inch                   | 2        | 2.13%   |
| Fujitsu Siemens B22W-7 LED FUS0838 1680x1050 474x296mm 22.0-inch       | 2        | 2.13%   |
| Xiaomi Mi TV XMD004A 1360x768 708x398mm 32.0-inch                      | 1        | 1.06%   |
| Vizio M220MV VIZ0062 1920x1080 509x286mm 23.0-inch                     | 1        | 1.06%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 1        | 1.06%   |
| Sony SDM-HS74P SNY3170 1280x1024 338x270mm 17.0-inch                   | 1        | 1.06%   |
| Sony SDM-HS53 SNY2250 1024x768 304x228mm 15.0-inch                     | 1        | 1.06%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch      | 1        | 1.06%   |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                       | 1        | 1.06%   |
| Samsung Electronics SyncMaster SAM0594 1680x1050 459x296mm 21.5-inch   | 1        | 1.06%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch   | 1        | 1.06%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch    | 1        | 1.06%   |
| Samsung Electronics SyncMaster SAM0286 1280x720 372x209mm 16.8-inch    | 1        | 1.06%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch   | 1        | 1.06%   |
| Samsung Electronics SMB2030 SAM063C 1600x900 443x249mm 20.0-inch       | 1        | 1.06%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 1        | 1.06%   |
| Samsung Electronics S23B550 SAM0919 1920x1080 510x287mm 23.0-inch      | 1        | 1.06%   |
| Samsung Electronics LCD Monitor SMT24A550                              | 1        | 1.06%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch  | 1        | 1.06%   |
| Samsung Electronics LCD Monitor C32R50x 3840x1080                      | 1        | 1.06%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 1        | 1.06%   |
| SAC DP_FREESYNC SAC2700 2560x1440 597x336mm 27.0-inch                  | 1        | 1.06%   |
| RTK FHD HDR RTKBC32 1920x1080 332x186mm 15.0-inch                      | 1        | 1.06%   |
| Philips PHL 276E9Q PHLC17B 1920x1080 598x336mm 27.0-inch               | 1        | 1.06%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch               | 1        | 1.06%   |
| Philips 170C PHL0848 1280x1024 338x270mm 17.0-inch                     | 1        | 1.06%   |
| Panasonic TV MEIA09B 1280x720 698x392mm 31.5-inch                      | 1        | 1.06%   |
| NEC Computers EA221WM NEC673D 1680x1050 474x296mm 22.0-inch            | 1        | 1.06%   |
| MSI G27C6 MSI5CA9 1920x1080 600x340mm 27.2-inch                        | 1        | 1.06%   |
| MSI G27C6 MSI5CA9 1920x1080 598x336mm 27.0-inch                        | 1        | 1.06%   |
| MiTAC KOGAN TV MTC6306 1366x768 700x400mm 31.7-inch                    | 1        | 1.06%   |
| LG Electronics LCD Monitor E2211                                       | 1        | 1.06%   |
| Lenovo T22v-10 LEN61BB 1920x1080 476x267mm 21.5-inch                   | 1        | 1.06%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1200 518x324mm 24.1-inch             | 1        | 1.06%   |
| Lenovo E24-20 LEN62A5 1920x1080 527x296mm 23.8-inch                    | 1        | 1.06%   |
| Iiyama PLE430 IVM46B4 1280x1024 340x270mm 17.1-inch                    | 1        | 1.06%   |
| Iiyama PL2776HD IVM6605 1920x1080 598x336mm 27.0-inch                  | 1        | 1.06%   |
| Iiyama PL2440HS IVM615E 1920x1080 527x296mm 23.8-inch                  | 1        | 1.06%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 31       | 35.63%  |
| 2560x1440 (QHD)    | 10       | 11.49%  |
| 1680x1050 (WSXGA+) | 10       | 11.49%  |
| 1280x1024 (SXGA)   | 9        | 10.34%  |
| 3840x2160 (4K)     | 7        | 8.05%   |
| 1366x768 (WXGA)    | 4        | 4.6%    |
| 3440x1440          | 2        | 2.3%    |
| 1920x1200 (WUXGA)  | 2        | 2.3%    |
| 1440x900 (WXGA+)   | 2        | 2.3%    |
| 1280x720 (HD)      | 2        | 2.3%    |
| Unknown            | 2        | 2.3%    |
| 3840x1080          | 1        | 1.15%   |
| 2560x1600          | 1        | 1.15%   |
| 2560x1080          | 1        | 1.15%   |
| 1600x900 (HD+)     | 1        | 1.15%   |
| 1360x768           | 1        | 1.15%   |
| 1024x768 (XGA)     | 1        | 1.15%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 14       | 16.47%  |
| 23      | 14       | 16.47%  |
| 22      | 9        | 10.59%  |
| 31      | 8        | 9.41%   |
| 24      | 7        | 8.24%   |
| 21      | 5        | 5.88%   |
| 18      | 4        | 4.71%   |
| 17      | 4        | 4.71%   |
| 34      | 3        | 3.53%   |
| 19      | 3        | 3.53%   |
| Unknown | 3        | 3.53%   |
| 15      | 2        | 2.35%   |
| 84      | 1        | 1.18%   |
| 65      | 1        | 1.18%   |
| 61      | 1        | 1.18%   |
| 54      | 1        | 1.18%   |
| 47      | 1        | 1.18%   |
| 40      | 1        | 1.18%   |
| 26      | 1        | 1.18%   |
| 20      | 1        | 1.18%   |
| 16      | 1        | 1.18%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 33       | 39.76%  |
| 401-500     | 18       | 21.69%  |
| 601-700     | 8        | 9.64%   |
| 351-400     | 6        | 7.23%   |
| 301-350     | 6        | 7.23%   |
| 1001-1500   | 4        | 4.82%   |
| 701-800     | 3        | 3.61%   |
| Unknown     | 3        | 3.61%   |
| 801-900     | 1        | 1.2%    |
| 1501-2000   | 1        | 1.2%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 53       | 63.86%  |
| 16/10   | 14       | 16.87%  |
| 5/4     | 9        | 10.84%  |
| 21/9    | 3        | 3.61%   |
| Unknown | 2        | 2.41%   |
| 4/3     | 1        | 1.2%    |
| 3/2     | 1        | 1.2%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 29       | 34.52%  |
| 301-350        | 14       | 16.67%  |
| 351-500        | 11       | 13.1%   |
| 151-200        | 9        | 10.71%  |
| 141-150        | 5        | 5.95%   |
| More than 1000 | 4        | 4.76%   |
| 251-300        | 4        | 4.76%   |
| Unknown        | 3        | 3.57%   |
| 501-1000       | 2        | 2.38%   |
| 121-130        | 1        | 1.19%   |
| 101-110        | 1        | 1.19%   |
| 91-100         | 1        | 1.19%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 58       | 70.73%  |
| 101-120 | 13       | 15.85%  |
| 1-50    | 6        | 7.32%   |
| Unknown | 3        | 3.66%   |
| 161-240 | 1        | 1.22%   |
| 121-160 | 1        | 1.22%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 64       | 77.11%  |
| 2     | 14       | 16.87%  |
| 0     | 3        | 3.61%   |
| 3     | 2        | 2.41%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 47       | 38.52%  |
| Intel                 | 37       | 30.33%  |
| Qualcomm Atheros      | 9        | 7.38%   |
| Ralink Technology     | 5        | 4.1%    |
| TP-Link               | 4        | 3.28%   |
| Broadcom              | 3        | 2.46%   |
| Ralink                | 2        | 1.64%   |
| MediaTek              | 2        | 1.64%   |
| Broadcom Limited      | 2        | 1.64%   |
| Xiaomi                | 1        | 0.82%   |
| VIA Technologies      | 1        | 0.82%   |
| OPPO Electronics      | 1        | 0.82%   |
| Nvidia                | 1        | 0.82%   |
| Microsoft             | 1        | 0.82%   |
| Mercucys              | 1        | 0.82%   |
| Linksys               | 1        | 0.82%   |
| JMicron Technology    | 1        | 0.82%   |
| Edimax Technology     | 1        | 0.82%   |
| AVM                   | 1        | 0.82%   |
| Aquantia              | 1        | 0.82%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 35       | 25.74%  |
| Intel Ethernet Controller I225-V                                  | 7        | 5.15%   |
| Ralink MT7601U Wireless Adapter                                   | 4        | 2.94%   |
| Intel I211 Gigabit Network Connection                             | 4        | 2.94%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4        | 2.94%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 2.21%   |
| Intel Ethernet Connection (2) I218-V                              | 3        | 2.21%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 3        | 2.21%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 2        | 1.47%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 2        | 1.47%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 2        | 1.47%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2        | 1.47%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 1.47%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 2        | 1.47%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2        | 1.47%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2        | 1.47%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 1.47%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 1.47%   |
| Intel 82578DM Gigabit Network Connection                          | 2        | 1.47%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 1.47%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.74%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.74%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                             | 1        | 0.74%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 1        | 0.74%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.74%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter               | 1        | 0.74%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                   | 1        | 0.74%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1        | 0.74%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1        | 0.74%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1        | 0.74%   |
| Realtek B1610311068                                               | 1        | 0.74%   |
| Realtek 802.11ac NIC                                              | 1        | 0.74%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1        | 0.74%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                         | 1        | 0.74%   |
| Ralink RT2561/RT61 802.11g PCI                                    | 1        | 0.74%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 0.74%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 1        | 0.74%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.74%   |
| OPPO RMX3263                                                      | 1        | 0.74%   |
| Nvidia MCP61 Ethernet                                             | 1        | 0.74%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 14       | 30.43%  |
| Intel                 | 9        | 19.57%  |
| Ralink Technology     | 5        | 10.87%  |
| TP-Link               | 4        | 8.7%    |
| Qualcomm Atheros      | 3        | 6.52%   |
| Ralink                | 2        | 4.35%   |
| MediaTek              | 2        | 4.35%   |
| Microsoft             | 1        | 2.17%   |
| Mercucys              | 1        | 2.17%   |
| Linksys               | 1        | 2.17%   |
| Edimax Technology     | 1        | 2.17%   |
| Broadcom Limited      | 1        | 2.17%   |
| Broadcom              | 1        | 2.17%   |
| AVM                   | 1        | 2.17%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Ralink MT7601U Wireless Adapter                            | 4        | 8.7%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]               | 2        | 4.35%   |
| Realtek RTL88x2bu [AC1200 Techkey]                         | 2        | 4.35%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter            | 2        | 4.35%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter        | 2        | 4.35%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter           | 2        | 4.35%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                      | 1        | 2.17%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                     | 1        | 2.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 1        | 2.17%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter        | 1        | 2.17%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter            | 1        | 2.17%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter            | 1        | 2.17%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter      | 1        | 2.17%   |
| Realtek RTL8188EE Wireless Network Adapter                 | 1        | 2.17%   |
| Realtek B1610311068                                        | 1        | 2.17%   |
| Realtek 802.11ac NIC                                       | 1        | 2.17%   |
| Ralink RT2870/RT3070 Wireless Adapter                      | 1        | 2.17%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                  | 1        | 2.17%   |
| Ralink RT2561/RT61 802.11g PCI                             | 1        | 2.17%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter           | 1        | 2.17%   |
| Microsoft XBOX ACC                                         | 1        | 2.17%   |
| Mercucys MW300UM RTL8192EU wifi                            | 1        | 2.17%   |
| MediaTek WiFi                                              | 1        | 2.17%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                    | 1        | 2.17%   |
| Linksys WUSB6300 V2                                        | 1        | 2.17%   |
| Intel Wireless-AC 9260                                     | 1        | 2.17%   |
| Intel Wireless 8260                                        | 1        | 2.17%   |
| Intel Wireless 7265                                        | 1        | 2.17%   |
| Intel Wireless 7260                                        | 1        | 2.17%   |
| Intel Wireless 3160                                        | 1        | 2.17%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                     | 1        | 2.17%   |
| Intel Gemini Lake PCH CNVi WiFi                            | 1        | 2.17%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 1        | 2.17%   |
| Intel Alder Lake-S PCH CNVi WiFi                           | 1        | 2.17%   |
| Edimax RTL8192S WLAN Adapter                               | 1        | 2.17%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter | 1        | 2.17%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter         | 1        | 2.17%   |
| AVM FRITZ!WLAN AC 860                                      | 1        | 2.17%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 38       | 43.68%  |
| Intel                 | 34       | 39.08%  |
| Qualcomm Atheros      | 6        | 6.9%    |
| Broadcom              | 2        | 2.3%    |
| Xiaomi                | 1        | 1.15%   |
| VIA Technologies      | 1        | 1.15%   |
| OPPO Electronics      | 1        | 1.15%   |
| Nvidia                | 1        | 1.15%   |
| JMicron Technology    | 1        | 1.15%   |
| Broadcom Limited      | 1        | 1.15%   |
| Aquantia              | 1        | 1.15%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 35       | 38.89%  |
| Intel Ethernet Controller I225-V                                  | 7        | 7.78%   |
| Intel I211 Gigabit Network Connection                             | 4        | 4.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4        | 4.44%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 3.33%   |
| Intel Ethernet Connection (2) I218-V                              | 3        | 3.33%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 3        | 3.33%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 2.22%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 2        | 2.22%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2        | 2.22%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 2.22%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 2.22%   |
| Intel 82578DM Gigabit Network Connection                          | 2        | 2.22%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 2.22%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 1.11%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 1.11%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 1.11%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 1.11%   |
| OPPO RMX3263                                                      | 1        | 1.11%   |
| Nvidia MCP61 Ethernet                                             | 1        | 1.11%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1        | 1.11%   |
| Intel Ethernet Connection I218-V                                  | 1        | 1.11%   |
| Intel Ethernet Connection I217-V                                  | 1        | 1.11%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.11%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 1.11%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 1.11%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 1.11%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 1.11%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 1.11%   |
| Broadcom Limited NetXtreme BCM5754 Gigabit Ethernet PCI Express   | 1        | 1.11%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 1.11%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 82       | 66.67%  |
| WiFi     | 41       | 33.33%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 57       | 67.06%  |
| WiFi     | 28       | 32.94%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 56       | 67.47%  |
| 2     | 23       | 27.71%  |
| 3     | 4        | 4.82%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 58       | 69.88%  |
| Yes  | 25       | 30.12%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 6        | 28.57%  |
| Cambridge Silicon Radio | 5        | 23.81%  |
| Realtek Semiconductor   | 2        | 9.52%   |
| Foxconn / Hon Hai       | 2        | 9.52%   |
| ASUSTek Computer        | 2        | 9.52%   |
| TP-Link                 | 1        | 4.76%   |
| MediaTek                | 1        | 4.76%   |
| Broadcom                | 1        | 4.76%   |
| Apple                   | 1        | 4.76%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 5        | 23.81%  |
| Intel Bluetooth wireless interface                    | 3        | 14.29%  |
| Realtek Bluetooth Radio                               | 2        | 9.52%   |
| Foxconn / Hon Hai Bluetooth Device                    | 2        | 9.52%   |
| TP-Link UB500 Adapter                                 | 1        | 4.76%   |
| MediaTek Wireless_Device                              | 1        | 4.76%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 1        | 4.76%   |
| Intel Bluetooth Device                                | 1        | 4.76%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 1        | 4.76%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 1        | 4.76%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 1        | 4.76%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 4.76%   |
| Apple Bluetooth Host Controller                       | 1        | 4.76%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 55       | 39.01%  |
| AMD                     | 34       | 24.11%  |
| Nvidia                  | 26       | 18.44%  |
| C-Media Electronics     | 6        | 4.26%   |
| Creative Labs           | 5        | 3.55%   |
| VIA Technologies        | 2        | 1.42%   |
| ROCCAT                  | 2        | 1.42%   |
| Texas Instruments       | 1        | 0.71%   |
| TerraTec Electronic     | 1        | 0.71%   |
| Setek Elektronik        | 1        | 0.71%   |
| Schiit Audio            | 1        | 0.71%   |
| Razer USA               | 1        | 0.71%   |
| JMTek                   | 1        | 0.71%   |
| GYROCOM C&C             | 1        | 0.71%   |
| GN Netcom               | 1        | 0.71%   |
| Generalplus Technology  | 1        | 0.71%   |
| Ensoniq                 | 1        | 0.71%   |
| BEHRINGER International | 1        | 0.71%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                           | Desktops | Percent |
|-------------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                | 7        | 4.24%   |
| AMD Family 17h/19h HD Audio Controller                                                          | 7        | 4.24%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                             | 6        | 3.64%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                      | 6        | 3.64%   |
| AMD Starship/Matisse HD Audio Controller                                                        | 6        | 3.64%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                             | 5        | 3.03%   |
| AMD SBx00 Azalia (Intel HDA)                                                                    | 5        | 3.03%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                             | 5        | 3.03%   |
| Nvidia GP107GL High Definition Audio Controller                                                 | 4        | 2.42%   |
| Nvidia GP104 High Definition Audio Controller                                                   | 4        | 2.42%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                        | 4        | 2.42%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                             | 4        | 2.42%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                         | 4        | 2.42%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                   | 3        | 1.82%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                           | 3        | 1.82%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                         | 3        | 1.82%   |
| Intel Cannon Lake PCH cAVS                                                                      | 3        | 1.82%   |
| Intel C610/X99 series chipset HD Audio Controller                                               | 3        | 1.82%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                             | 3        | 1.82%   |
| Intel 200 Series PCH HD Audio                                                                   | 3        | 1.82%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus] | 3        | 1.82%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                               | 3        | 1.82%   |
| AMD Renoir Radeon High Definition Audio Controller                                              | 3        | 1.82%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                      | 3        | 1.82%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                    | 3        | 1.82%   |
| ROCCAT Khan AIMO                                                                                | 2        | 1.21%   |
| Nvidia TU104 HD Audio Controller                                                                | 2        | 1.21%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                | 2        | 1.21%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                  | 2        | 1.21%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                 | 2        | 1.21%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                    | 2        | 1.21%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                         | 2        | 1.21%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                          | 2        | 1.21%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                                       | 1        | 0.61%   |
| VIA Technologies ICE1712 [Envy24] PCI Multi-Channel I/O Controller                              | 1        | 0.61%   |
| Texas Instruments PCM2902 Audio Codec                                                           | 1        | 0.61%   |
| TerraTec Electronic Aureon Dual USB                                                             | 1        | 0.61%   |
| Setek Elektronik Realtek USB Audio Rear                                                         | 1        | 0.61%   |
| Setek Elektronik Realtek USB Audio Front                                                        | 1        | 0.61%   |
| Schiit Audio I'm Fulla Schiit                                                                   | 1        | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 14       | 14.89%  |
| Kingston            | 14       | 14.89%  |
| Samsung Electronics | 11       | 11.7%   |
| Corsair             | 11       | 11.7%   |
| G.Skill             | 7        | 7.45%   |
| A-DATA Technology   | 6        | 6.38%   |
| Ramaxel Technology  | 5        | 5.32%   |
| SK hynix            | 4        | 4.26%   |
| Crucial             | 4        | 4.26%   |
| Nanya Technology    | 3        | 3.19%   |
| Micron Technology   | 3        | 3.19%   |
| Unknown (ABCD)      | 2        | 2.13%   |
| Transcend           | 2        | 2.13%   |
| Unknown             | 2        | 2.13%   |
| Unknown (AB)        | 1        | 1.06%   |
| Patriot             | 1        | 1.06%   |
| Golden Empire       | 1        | 1.06%   |
| Elpida              | 1        | 1.06%   |
| Avant               | 1        | 1.06%   |
| Apacer              | 1        | 1.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s        | 4        | 4%      |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s                     | 2        | 2%      |
| Unknown RAM Module 2GB DIMM 667MT/s                          | 2        | 2%      |
| Unknown (ABCD) RAM 123456789012345678 1GB DIMM DDR3 2400MT/s | 2        | 2%      |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s          | 2        | 2%      |
| G.Skill RAM F4-4000C18-16GTZR 16GB DIMM DDR4 2133MT/s        | 2        | 2%      |
| Crucial RAM BLS8G4D32AESBK.M8FE1 8GB DIMM DDR4 3600MT/s      | 2        | 2%      |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s       | 2        | 2%      |
| Unknown                                                      | 2        | 2%      |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                    | 1        | 1%      |
| Unknown RAM Module 4GB DIMM SDRAM                            | 1        | 1%      |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                    | 1        | 1%      |
| Unknown RAM Module 4GB DIMM 667MT/s                          | 1        | 1%      |
| Unknown RAM Module 4GB DIMM                                  | 1        | 1%      |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                    | 1        | 1%      |
| Unknown RAM Module 2GB DIMM DDR2 1067MT/s                    | 1        | 1%      |
| Unknown RAM Module 2GB DIMM 800MT/s                          | 1        | 1%      |
| Unknown RAM Module 2GB DIMM 1333MT/s                         | 1        | 1%      |
| Unknown RAM Module 1GB DIMM SDRAM                            | 1        | 1%      |
| Unknown (AB) RAM Module 2GB DIMM LPDDR3 1333MT/s             | 1        | 1%      |
| Transcend RAM JM800QLU-2G 2048MB DIMM DDR 2048MT/s           | 1        | 1%      |
| Transcend RAM JM1333KLN-8GK 4GB DIMM DDR3 1333MT/s           | 1        | 1%      |
| SK hynix RAM HMT451U6AFR8A-PB 4GB DIMM DDR3 1600MT/s         | 1        | 1%      |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1        | 1%      |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s         | 1        | 1%      |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s         | 1        | 1%      |
| SK hynix RAM HMT125U6DFR8C-H9 2048MB DIMM DDR3 1333MT/s      | 1        | 1%      |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 1        | 1%      |
| Samsung RAM M393B5170DZ1-CF8 4GB DIMM DDR3 1066MT/s          | 1        | 1%      |
| Samsung RAM M393A4K40DB3-CWE 32GB DIMM DDR4 3200MT/s         | 1        | 1%      |
| Samsung RAM M393A2K43CB2-CTD 16GB DIMM DDR4 2666MT/s         | 1        | 1%      |
| Samsung RAM M386A4G40DM0-CPB 32GB DIMM DDR4 2133MT/s         | 1        | 1%      |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s          | 1        | 1%      |
| Samsung RAM M378B5273CH0-CK0 4GB DIMM DDR3 2000MT/s          | 1        | 1%      |
| Samsung RAM M378A1K43EB2-CWE 8GB DIMM DDR4 3200MT/s          | 1        | 1%      |
| Samsung RAM M378A1G43DB0-CPB 8GB DIMM DDR4 2133MT/s          | 1        | 1%      |
| Samsung RAM DDR3 1600 8G 8GB DIMM DDR3 1333MT/s              | 1        | 1%      |
| Ramaxel RAM RMUA5200ME78HAF-3200 8GB DIMM DDR4 3200MT/s      | 1        | 1%      |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s      | 1        | 1%      |
| Ramaxel RAM RMR5040ED58E9W1600 4GB DIMM 1600MT/s             | 1        | 1%      |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 37       | 43.53%  |
| DDR3    | 28       | 32.94%  |
| DDR2    | 6        | 7.06%   |
| Unknown | 6        | 7.06%   |
| SDRAM   | 5        | 5.88%   |
| LPDDR4  | 2        | 2.35%   |
| LPDDR3  | 1        | 1.18%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 74       | 90.24%  |
| SODIMM | 8        | 9.76%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 24       | 26.67%  |
| 8192  | 22       | 24.44%  |
| 2048  | 18       | 20%     |
| 16384 | 15       | 16.67%  |
| 32768 | 6        | 6.67%   |
| 1024  | 5        | 5.56%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 13       | 14.77%  |
| 1333    | 13       | 14.77%  |
| 3600    | 9        | 10.23%  |
| 3200    | 8        | 9.09%   |
| 2667    | 5        | 5.68%   |
| 2133    | 5        | 5.68%   |
| 800     | 4        | 4.55%   |
| 667     | 4        | 4.55%   |
| 3400    | 3        | 3.41%   |
| 2666    | 3        | 3.41%   |
| 2400    | 3        | 3.41%   |
| Unknown | 3        | 3.41%   |
| 2048    | 2        | 2.27%   |
| 1066    | 2        | 2.27%   |
| 333     | 2        | 2.27%   |
| 3866    | 1        | 1.14%   |
| 3466    | 1        | 1.14%   |
| 3266    | 1        | 1.14%   |
| 3000    | 1        | 1.14%   |
| 2933    | 1        | 1.14%   |
| 2000    | 1        | 1.14%   |
| 1866    | 1        | 1.14%   |
| 1800    | 1        | 1.14%   |
| 1067    | 1        | 1.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Canon              | 3        | 75%     |
| Brother Industries | 1        | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model               | Desktops | Percent |
|---------------------|----------|---------|
| Canon MF641C        | 2        | 50%     |
| Canon MG5700 series | 1        | 25%     |
| Brother MFC-7340    | 1        | 25%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Canon CanoScan LiDE 210 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 6        | 37.5%   |
| Sunplus Innovation Technology | 2        | 12.5%   |
| Microsoft                     | 2        | 12.5%   |
| Chicony Electronics           | 2        | 12.5%   |
| Sonix Technology              | 1        | 6.25%   |
| Hewlett-Packard               | 1        | 6.25%   |
| Generalplus Technology        | 1        | 6.25%   |
| Arkmicro Technologies         | 1        | 6.25%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Sunplus HD 720P webcam            | 2        | 12.5%   |
| Microsoft LifeCam HD-3000         | 2        | 12.5%   |
| Logitech Webcam C930e             | 2        | 12.5%   |
| Logitech Webcam C270              | 2        | 12.5%   |
| Sonix USB Camera                  | 1        | 6.25%   |
| Logitech Webcam C110              | 1        | 6.25%   |
| Logitech HD Webcam C615           | 1        | 6.25%   |
| HP Webcam HD 2300                 | 1        | 6.25%   |
| Generalplus GENERAL WEBCAM        | 1        | 6.25%   |
| Chicony HP Prem AF Webcam KQ245AA | 1        | 6.25%   |
| Chicony HD Webcam                 | 1        | 6.25%   |
| Arkmicro USB2.0 PC CAMERA         | 1        | 6.25%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor    | Desktops | Percent |
|-----------|----------|---------|
| Microsoft | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                        | Desktops | Percent |
|------------------------------|----------|---------|
| Microsoft Fingerprint Reader | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

Zero info for selected period =(

Chipcard Model
--------------

Chipcard module models

Zero info for selected period =(

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 69       | 83.13%  |
| 1     | 11       | 13.25%  |
| 2     | 2        | 2.41%   |
| 3     | 1        | 1.2%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 6        | 35.29%  |
| Net/wireless             | 4        | 23.53%  |
| Unassigned class         | 3        | 17.65%  |
| Communication controller | 2        | 11.76%  |
| Fingerprint reader       | 1        | 5.88%   |
| Dvb card                 | 1        | 5.88%   |

