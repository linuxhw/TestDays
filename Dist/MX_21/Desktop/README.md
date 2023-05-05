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

Total: 107

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | Z97-P                       | [8d94344086](https://linux-hardware.org/?probe=8d94344086) | Apr 26, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [4939e609de](https://linux-hardware.org/?probe=4939e609de) | Apr 24, 2023 |
| HP            | 090Ch                       | [01d609bbab](https://linux-hardware.org/?probe=01d609bbab) | Apr 23, 2023 |
| ASRock        | Z690 Pro RS                 | [acb9cde3d7](https://linux-hardware.org/?probe=acb9cde3d7) | Apr 23, 2023 |
| Gateway       | DX4860                      | [5583641f1b](https://linux-hardware.org/?probe=5583641f1b) | Apr 22, 2023 |
| ASUSTek       | GRYPHON Z87                 | [045a79a6e4](https://linux-hardware.org/?probe=045a79a6e4) | Apr 18, 2023 |
| HP            | 3646h                       | [c36653d824](https://linux-hardware.org/?probe=c36653d824) | Apr 12, 2023 |
| HP            | 18E5                        | [441d2678ff](https://linux-hardware.org/?probe=441d2678ff) | Apr 07, 2023 |
| ASUSTek       | P8P67 LE                    | [aea33c89a1](https://linux-hardware.org/?probe=aea33c89a1) | Apr 05, 2023 |
| ASUSTek       | Z97-P                       | [86d8d7f80f](https://linux-hardware.org/?probe=86d8d7f80f) | Apr 05, 2023 |
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
| 5.10.0-21-amd64              | 13       | 13.98%  |
| 5.10.0-20-amd64              | 11       | 11.83%  |
| 5.14.0-4mx-amd64             | 6        | 6.45%   |
| 5.10.0-19-amd64              | 6        | 6.45%   |
| 5.10.0-18-amd64              | 6        | 6.45%   |
| 5.10.0-13-amd64              | 5        | 5.38%   |
| 6.0.0-6mx-amd64              | 4        | 4.3%    |
| 5.10.0-16-amd64              | 4        | 4.3%    |
| 5.10.0-15-amd64              | 4        | 4.3%    |
| 5.16.0-5mx-amd64             | 3        | 3.23%   |
| 6.0.0-10.1-liquorix-amd64    | 2        | 2.15%   |
| 5.14.0-3mx-amd64             | 2        | 2.15%   |
| 5.10.0-9-amd64               | 2        | 2.15%   |
| 5.10.0-11-amd64              | 2        | 2.15%   |
| 6.1.15-2-liquorix-amd64      | 1        | 1.08%   |
| 6.1.0-2mx-amd64              | 1        | 1.08%   |
| 6.0.5-x64v1-xanmod1          | 1        | 1.08%   |
| 6.0.0-4mx-rt-amd64           | 1        | 1.08%   |
| 6.0.0-13.3-liquorix-amd64    | 1        | 1.08%   |
| 5.19.0-4.2-liquorix-amd64    | 1        | 1.08%   |
| 5.19.0-17.2-liquorix-amd64   | 1        | 1.08%   |
| 5.19.0-14.1-liquorix-amd64   | 1        | 1.08%   |
| 5.18.0-4mx-amd64             | 1        | 1.08%   |
| 5.17.0-3mx-amd64             | 1        | 1.08%   |
| 5.16.0-rc5-hwmon-next+       | 1        | 1.08%   |
| 5.16.0-6mx-amd64             | 1        | 1.08%   |
| 5.15.0-2-amd64               | 1        | 1.08%   |
| 5.15.0-0.bpo.2-amd64         | 1        | 1.08%   |
| 5.14.0-2mx-amd64             | 1        | 1.08%   |
| 5.10.52-antix.1-amd64-smp    | 1        | 1.08%   |
| 5.10.113-lkdtm-i386pae       | 1        | 1.08%   |
| 5.10.111-tkg-cfs             | 1        | 1.08%   |
| 5.10.0-20-686-pae            | 1        | 1.08%   |
| 5.10.0-18-686-pae            | 1        | 1.08%   |
| 5.10.0-17-amd64              | 1        | 1.08%   |
| 5.10.0-10-amd64              | 1        | 1.08%   |
| 4.19.0-256-antix.1-amd64-smp | 1        | 1.08%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.10.0   | 57       | 61.29%  |
| 5.14.0   | 9        | 9.68%   |
| 6.0.0    | 8        | 8.6%    |
| 5.16.0   | 5        | 5.38%   |
| 5.19.0   | 3        | 3.23%   |
| 5.15.0   | 2        | 2.15%   |
| 6.1.15   | 1        | 1.08%   |
| 6.1.0    | 1        | 1.08%   |
| 6.0.5    | 1        | 1.08%   |
| 5.18.0   | 1        | 1.08%   |
| 5.17.0   | 1        | 1.08%   |
| 5.10.52  | 1        | 1.08%   |
| 5.10.113 | 1        | 1.08%   |
| 5.10.111 | 1        | 1.08%   |
| 4.19.0   | 1        | 1.08%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 60       | 64.52%  |
| 6.0     | 9        | 9.68%   |
| 5.14    | 9        | 9.68%   |
| 5.16    | 5        | 5.38%   |
| 5.19    | 3        | 3.23%   |
| 6.1     | 2        | 2.15%   |
| 5.15    | 2        | 2.15%   |
| 5.18    | 1        | 1.08%   |
| 5.17    | 1        | 1.08%   |
| 4.19    | 1        | 1.08%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 90       | 96.77%  |
| i686   | 3        | 3.23%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| XFCE             | 69       | 74.19%  |
| KDE5             | 21       | 22.58%  |
| lightdm-xsession | 2        | 2.15%   |
| Unknown          | 1        | 1.08%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 93       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 69       | 74.19%  |
| SDDM    | 20       | 21.51%  |
| SLiM    | 3        | 3.23%   |
| GDM     | 1        | 1.08%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 42       | 45.16%  |
| de_DE | 14       | 15.05%  |
| it_IT | 7        | 7.53%   |
| ru_RU | 4        | 4.3%    |
| pl_PL | 4        | 4.3%    |
| en_GB | 4        | 4.3%    |
| sv_SE | 2        | 2.15%   |
| fr_FR | 2        | 2.15%   |
| es_MX | 2        | 2.15%   |
| es_AR | 2        | 2.15%   |
| de_CH | 2        | 2.15%   |
| pt_BR | 1        | 1.08%   |
| hu_HU | 1        | 1.08%   |
| hr_HR | 1        | 1.08%   |
| fi_FI | 1        | 1.08%   |
| es_VE | 1        | 1.08%   |
| es_ES | 1        | 1.08%   |
| es_CO | 1        | 1.08%   |
| en_NZ | 1        | 1.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 56       | 60.22%  |
| EFI  | 37       | 39.78%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 81       | 87.1%   |
| Overlay  | 8        | 8.6%    |
| Xfs      | 1        | 1.08%   |
| Reiserfs | 1        | 1.08%   |
| Ext3     | 1        | 1.08%   |
| Btrfs    | 1        | 1.08%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 52       | 55.91%  |
| MBR  | 41       | 44.09%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 57       | 61.29%  |
| Yes       | 36       | 38.71%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 50       | 53.76%  |
| No        | 43       | 46.24%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 20       | 21.51%  |
| Gigabyte Technology                  | 11       | 11.83%  |
| MSI                                  | 10       | 10.75%  |
| Hewlett-Packard                      | 9        | 9.68%   |
| Dell                                 | 8        | 8.6%    |
| ASRock                               | 6        | 6.45%   |
| Lenovo                               | 5        | 5.38%   |
| Intel                                | 3        | 3.23%   |
| Unknown                              | 3        | 3.23%   |
| Pegatron                             | 2        | 2.15%   |
| Fujitsu                              | 2        | 2.15%   |
| Biostar                              | 2        | 2.15%   |
| ZOTAC                                | 1        | 1.08%   |
| SIRAGON                              | 1        | 1.08%   |
| Shenzhen Meigao Electronic Equipment | 1        | 1.08%   |
| MP                                   | 1        | 1.08%   |
| Medion                               | 1        | 1.08%   |
| Huanan                               | 1        | 1.08%   |
| Gateway                              | 1        | 1.08%   |
| GALAX                                | 1        | 1.08%   |
| Foxconn                              | 1        | 1.08%   |
| ECS                                  | 1        | 1.08%   |
| BESSTAR Tech                         | 1        | 1.08%   |
| AOpen                                | 1        | 1.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Desktops | Percent |
|---------------------------------------------|----------|---------|
| ASUS All Series                             | 7        | 7.53%   |
| Unknown                                     | 4        | 4.3%    |
| MSI MS-7C91                                 | 2        | 2.15%   |
| Gigabyte GA-MA785GM-US2H                    | 2        | 2.15%   |
| Dell OptiPlex 755                           | 2        | 2.15%   |
| ASUS ROG Maximus XIII HERO                  | 2        | 2.15%   |
| SIRAGON AIO-5150                            | 1        | 1.08%   |
| Shenzhen Meigao Electronic Equipment UM450  | 1        | 1.08%   |
| Pegatron FQ425AA-ABA a6655f                 | 1        | 1.08%   |
| Pegatron 2AD5                               | 1        | 1.08%   |
| MSI MS-7C37                                 | 1        | 1.08%   |
| MSI MS-7B98                                 | 1        | 1.08%   |
| MSI MS-7B53                                 | 1        | 1.08%   |
| MSI MS-7A63                                 | 1        | 1.08%   |
| MSI MS-7A34                                 | 1        | 1.08%   |
| MSI MS-7917                                 | 1        | 1.08%   |
| MSI MS-7823                                 | 1        | 1.08%   |
| MSI MS-7758                                 | 1        | 1.08%   |
| MP MS-7848                                  | 1        | 1.08%   |
| Medion Akoya P5330 E MD8876/2458            | 1        | 1.08%   |
| Lenovo ThinkStation P620 30E0CTO1WW         | 1        | 1.08%   |
| Lenovo ThinkCentre M75s Gen 2 11JAS0CJ00    | 1        | 1.08%   |
| Lenovo ThinkCentre M58 7638CB8              | 1        | 1.08%   |
| Lenovo IdeaCentre Gaming5 17IAB7 90T00007US | 1        | 1.08%   |
| Lenovo 10AAS1QB0B                           | 1        | 1.08%   |
| Intel V1.3                                  | 1        | 1.08%   |
| Intel DH55TC AAE70932-303                   | 1        | 1.08%   |
| Intel D34010WYK H14771-303                  | 1        | 1.08%   |
| Huanan X99-F8                               | 1        | 1.08%   |
| HP Z400 Workstation                         | 1        | 1.08%   |
| HP EliteDesk 800 G1 USDT                    | 1        | 1.08%   |
| HP dc5000 uT(PB647A)                        | 1        | 1.08%   |
| HP Compaq Elite 8300 CMT                    | 1        | 1.08%   |
| HP Compaq dc5850 Microtower                 | 1        | 1.08%   |
| HP Compaq 8100 Elite SFF PC                 | 1        | 1.08%   |
| HP Compaq 8000 Elite CMT PC                 | 1        | 1.08%   |
| HP 3646h                                    | 1        | 1.08%   |
| HP 260 G2 DM                                | 1        | 1.08%   |
| Gigabyte Z77X-D3H                           | 1        | 1.08%   |
| Gigabyte Z390 UD                            | 1        | 1.08%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Dell OptiPlex                              | 7        | 7.53%   |
| ASUS All                                   | 7        | 7.53%   |
| HP Compaq                                  | 4        | 4.3%    |
| Unknown                                    | 4        | 4.3%    |
| ASUS ROG                                   | 3        | 3.23%   |
| MSI MS-7C91                                | 2        | 2.15%   |
| Lenovo ThinkCentre                         | 2        | 2.15%   |
| Gigabyte GA-MA785GM-US2H                   | 2        | 2.15%   |
| Gigabyte B550M                             | 2        | 2.15%   |
| ASUS TUF                                   | 2        | 2.15%   |
| ASUS P5GC-MX                               | 2        | 2.15%   |
| SIRAGON AIO-5150                           | 1        | 1.08%   |
| Shenzhen Meigao Electronic Equipment UM450 | 1        | 1.08%   |
| Pegatron FQ425AA-ABA                       | 1        | 1.08%   |
| Pegatron 2AD5                              | 1        | 1.08%   |
| MSI MS-7C37                                | 1        | 1.08%   |
| MSI MS-7B98                                | 1        | 1.08%   |
| MSI MS-7B53                                | 1        | 1.08%   |
| MSI MS-7A63                                | 1        | 1.08%   |
| MSI MS-7A34                                | 1        | 1.08%   |
| MSI MS-7917                                | 1        | 1.08%   |
| MSI MS-7823                                | 1        | 1.08%   |
| MSI MS-7758                                | 1        | 1.08%   |
| MP MS-7848                                 | 1        | 1.08%   |
| Medion Akoya                               | 1        | 1.08%   |
| Lenovo ThinkStation                        | 1        | 1.08%   |
| Lenovo IdeaCentre                          | 1        | 1.08%   |
| Lenovo 10AAS1QB0B                          | 1        | 1.08%   |
| Intel V1.3                                 | 1        | 1.08%   |
| Intel DH55TC                               | 1        | 1.08%   |
| Intel D34010WYK                            | 1        | 1.08%   |
| Huanan X99-F8                              | 1        | 1.08%   |
| HP Z400                                    | 1        | 1.08%   |
| HP EliteDesk                               | 1        | 1.08%   |
| HP dc5000                                  | 1        | 1.08%   |
| HP 3646h                                   | 1        | 1.08%   |
| HP 260                                     | 1        | 1.08%   |
| Gigabyte Z77X-D3H                          | 1        | 1.08%   |
| Gigabyte Z390                              | 1        | 1.08%   |
| Gigabyte X570                              | 1        | 1.08%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2021 | 8        | 8.6%    |
| 2020 | 8        | 8.6%    |
| 2014 | 8        | 8.6%    |
| 2013 | 8        | 8.6%    |
| 2022 | 7        | 7.53%   |
| 2018 | 7        | 7.53%   |
| 2011 | 7        | 7.53%   |
| 2012 | 6        | 6.45%   |
| 2009 | 6        | 6.45%   |
| 2019 | 5        | 5.38%   |
| 2016 | 5        | 5.38%   |
| 2007 | 5        | 5.38%   |
| 2010 | 4        | 4.3%    |
| 2008 | 4        | 4.3%    |
| 2017 | 2        | 2.15%   |
| 2015 | 2        | 2.15%   |
| 2004 | 1        | 1.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 93       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 93       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 93       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 25       | 26.88%  |
| 4.01-8.0    | 19       | 20.43%  |
| 32.01-64.0  | 18       | 19.35%  |
| 16.01-24.0  | 13       | 13.98%  |
| 3.01-4.0    | 10       | 10.75%  |
| 64.01-256.0 | 3        | 3.23%   |
| 24.01-32.0  | 2        | 2.15%   |
| 2.01-3.0    | 2        | 2.15%   |
| 0.51-1.0    | 1        | 1.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 35       | 37.23%  |
| 2.01-3.0   | 26       | 27.66%  |
| 3.01-4.0   | 14       | 14.89%  |
| 4.01-8.0   | 11       | 11.7%   |
| 8.01-16.0  | 4        | 4.26%   |
| 0.51-1.0   | 3        | 3.19%   |
| 16.01-24.0 | 1        | 1.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 34       | 36.56%  |
| 2      | 21       | 22.58%  |
| 3      | 20       | 21.51%  |
| 4      | 10       | 10.75%  |
| 5      | 5        | 5.38%   |
| 8      | 2        | 2.15%   |
| 7      | 1        | 1.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 48       | 51.61%  |
| Yes       | 45       | 48.39%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 92       | 98.92%  |
| No        | 1        | 1.08%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 48       | 51.61%  |
| Yes       | 45       | 48.39%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 70       | 75.27%  |
| Yes       | 23       | 24.73%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Desktops | Percent |
|------------------------|----------|---------|
| USA                    | 25       | 26.88%  |
| Germany                | 14       | 15.05%  |
| Italy                  | 7        | 7.53%   |
| Poland                 | 5        | 5.38%   |
| Russia                 | 4        | 4.3%    |
| France                 | 3        | 3.23%   |
| Finland                | 3        | 3.23%   |
| Canada                 | 3        | 3.23%   |
| Venezuela              | 2        | 2.15%   |
| UK                     | 2        | 2.15%   |
| Switzerland            | 2        | 2.15%   |
| Sweden                 | 2        | 2.15%   |
| Mexico                 | 2        | 2.15%   |
| India                  | 2        | 2.15%   |
| Australia              | 2        | 2.15%   |
| Argentina              | 2        | 2.15%   |
| Spain                  | 1        | 1.08%   |
| Singapore              | 1        | 1.08%   |
| Romania                | 1        | 1.08%   |
| New Zealand            | 1        | 1.08%   |
| Netherlands            | 1        | 1.08%   |
| Indonesia              | 1        | 1.08%   |
| Hungary                | 1        | 1.08%   |
| Greece                 | 1        | 1.08%   |
| Estonia                | 1        | 1.08%   |
| Croatia                | 1        | 1.08%   |
| Colombia               | 1        | 1.08%   |
| Brazil                 | 1        | 1.08%   |
| Bosnia and Herzegovina | 1        | 1.08%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Desktops | Percent |
|---------------|----------|---------|
| Moscow        | 2        | 2.15%   |
| Mesquite      | 2        | 2.15%   |
| Krakow        | 2        | 2.15%   |
| Houston       | 2        | 2.15%   |
| Ettingen      | 2        | 2.15%   |
| Berlin        | 2        | 2.15%   |
| Alma          | 2        | 2.15%   |
| Zagreb        | 1        | 1.08%   |
| Volos         | 1        | 1.08%   |
| Voghera       | 1        | 1.08%   |
| Vilhelmina    | 1        | 1.08%   |
| Vasco da Gama | 1        | 1.08%   |
| Vaidasoo      | 1        | 1.08%   |
| Tuglie        | 1        | 1.08%   |
| Toronto       | 1        | 1.08%   |
| Tampere       | 1        | 1.08%   |
| Sydney        | 1        | 1.08%   |
| Stevens Point | 1        | 1.08%   |
| Stafford      | 1        | 1.08%   |
| St Petersburg | 1        | 1.08%   |
| Sollentuna    | 1        | 1.08%   |
| Singapore     | 1        | 1.08%   |
| Seelbach      | 1        | 1.08%   |
| Sanski Most   | 1        | 1.08%   |
| San Diego     | 1        | 1.08%   |
| Rzeszów      | 1        | 1.08%   |
| Rosporden     | 1        | 1.08%   |
| Reno          | 1        | 1.08%   |
| Rathenow      | 1        | 1.08%   |
| Pullman       | 1        | 1.08%   |
| Puebla City   | 1        | 1.08%   |
| Portland      | 1        | 1.08%   |
| Pompano Beach | 1        | 1.08%   |
| Pila          | 1        | 1.08%   |
| Piedmont      | 1        | 1.08%   |
| Pachuca       | 1        | 1.08%   |
| Otwock        | 1        | 1.08%   |
| Osnabrück    | 1        | 1.08%   |
| Ocala         | 1        | 1.08%   |
| Normal        | 1        | 1.08%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Samsung Electronics       | 32       | 54     | 17.98%  |
| Seagate                   | 31       | 40     | 17.42%  |
| WDC                       | 28       | 35     | 15.73%  |
| Kingston                  | 19       | 20     | 10.67%  |
| Toshiba                   | 10       | 11     | 5.62%   |
| SanDisk                   | 7        | 9      | 3.93%   |
| China                     | 7        | 8      | 3.93%   |
| Hitachi                   | 5        | 6      | 2.81%   |
| Crucial                   | 5        | 5      | 2.81%   |
| Unknown                   | 3        | 5      | 1.69%   |
| PNY                       | 3        | 4      | 1.69%   |
| Corsair                   | 3        | 3      | 1.69%   |
| Transcend                 | 2        | 2      | 1.12%   |
| GOODRAM                   | 2        | 2      | 1.12%   |
| Apacer                    | 2        | 2      | 1.12%   |
| A-DATA Technology         | 2        | 2      | 1.12%   |
| Team                      | 1        | 1      | 0.56%   |
| SPCC                      | 1        | 1      | 0.56%   |
| Silicon Motion            | 1        | 1      | 0.56%   |
| Phison Electronics        | 1        | 1      | 0.56%   |
| Phison                    | 1        | 1      | 0.56%   |
| OCZ                       | 1        | 1      | 0.56%   |
| Mushkin                   | 1        | 1      | 0.56%   |
| Micron/Crucial Technology | 1        | 1      | 0.56%   |
| Micron Technology         | 1        | 1      | 0.56%   |
| Maxtor                    | 1        | 1      | 0.56%   |
| JMicron Technology        | 1        | 1      | 0.56%   |
| Intel                     | 1        | 1      | 0.56%   |
| HGST                      | 1        | 1      | 0.56%   |
| External                  | 1        | 1      | 0.56%   |
| CT1000P3                  | 1        | 1      | 0.56%   |
| Avant                     | 1        | 1      | 0.56%   |
| Acer                      | 1        | 1      | 0.56%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Kingston SA400S37480G 480GB SSD  | 6        | 2.83%   |
| Kingston SV300S37A240G 240GB SSD | 4        | 1.89%   |
| Seagate ST3500413AS 500GB        | 3        | 1.42%   |
| Seagate ST2000DM008-2FR102 2TB   | 3        | 1.42%   |
| SanDisk SDSSDA240G 240GB         | 3        | 1.42%   |
| Samsung SSD 980 PRO 1TB          | 3        | 1.42%   |
| Samsung SSD 970 EVO Plus 1TB     | 3        | 1.42%   |
| Samsung SSD 850 EVO 250GB        | 3        | 1.42%   |
| Samsung SSD 850 EVO 1TB          | 3        | 1.42%   |
| Samsung SSD 840 Series 120GB     | 3        | 1.42%   |
| Unknown SD/MMC 2GB               | 2        | 0.94%   |
| Unknown M.S./M.S.Pro/HG 16GB     | 2        | 0.94%   |
| Toshiba HDWD110 1TB              | 2        | 0.94%   |
| Toshiba DT01ACA100 1TB           | 2        | 0.94%   |
| Seagate ST500LM021-1KJ152 500GB  | 2        | 0.94%   |
| Seagate ST250DM000-1BD141 250GB  | 2        | 0.94%   |
| Seagate ST2000DM001-1ER164 2TB   | 2        | 0.94%   |
| SanDisk NVMe SSD Drive 1TB       | 2        | 0.94%   |
| Samsung SSD 980 500GB            | 2        | 0.94%   |
| Samsung SSD 970 PRO 512GB        | 2        | 0.94%   |
| Samsung SSD 970 EVO Plus 500GB   | 2        | 0.94%   |
| Samsung SSD 870 EVO 500GB        | 2        | 0.94%   |
| Samsung SSD 860 EVO 500GB        | 2        | 0.94%   |
| Samsung SSD 860 EVO 250GB        | 2        | 0.94%   |
| Samsung SSD 850 EVO 500GB        | 2        | 0.94%   |
| Kingston SA400S37120G 120GB SSD  | 2        | 0.94%   |
| Corsair MP400 2TB                | 2        | 0.94%   |
| China SATA SSD 512GB             | 2        | 0.94%   |
| WDC WDS500G2B0C-00PXH0 500GB     | 1        | 0.47%   |
| WDC WDS250G2B0A-00SM50 250GB SSD | 1        | 0.47%   |
| WDC WDS100T2B0A-00SM50 1TB SSD   | 1        | 0.47%   |
| WDC WD800AAJS-60M0A0 80GB        | 1        | 0.47%   |
| WDC WD60EZRZ-00RWYB1 6TB         | 1        | 0.47%   |
| WDC WD60EFRX-68L0BN1 6TB         | 1        | 0.47%   |
| WDC WD5002AALX-00J37A0 500GB     | 1        | 0.47%   |
| WDC WD5000AVCS-632DY1 500GB      | 1        | 0.47%   |
| WDC WD5000AAKS-00E4A0 500GB      | 1        | 0.47%   |
| WDC WD40EFRX-68WT0N0 4TB         | 1        | 0.47%   |
| WDC WD3200AAKS-75L9A0 320GB      | 1        | 0.47%   |
| WDC WD3200AAKS-75B3A0 320GB      | 1        | 0.47%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 31       | 40     | 39.74%  |
| WDC                 | 25       | 32     | 32.05%  |
| Toshiba             | 10       | 11     | 12.82%  |
| Hitachi             | 5        | 6      | 6.41%   |
| Samsung Electronics | 3        | 3      | 3.85%   |
| Unknown             | 1        | 1      | 1.28%   |
| Maxtor              | 1        | 1      | 1.28%   |
| HGST                | 1        | 1      | 1.28%   |
| External            | 1        | 1      | 1.28%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 23       | 29     | 31.08%  |
| Kingston            | 16       | 17     | 21.62%  |
| China               | 7        | 8      | 9.46%   |
| SanDisk             | 5        | 6      | 6.76%   |
| Crucial             | 4        | 4      | 5.41%   |
| WDC                 | 2        | 2      | 2.7%    |
| Transcend           | 2        | 2      | 2.7%    |
| PNY                 | 2        | 2      | 2.7%    |
| GOODRAM             | 2        | 2      | 2.7%    |
| A-DATA Technology   | 2        | 2      | 2.7%    |
| Team                | 1        | 1      | 1.35%   |
| SPCC                | 1        | 1      | 1.35%   |
| OCZ                 | 1        | 1      | 1.35%   |
| Mushkin             | 1        | 1      | 1.35%   |
| Micron Technology   | 1        | 1      | 1.35%   |
| CT1000P3            | 1        | 1      | 1.35%   |
| Avant               | 1        | 1      | 1.35%   |
| Apacer              | 1        | 1      | 1.35%   |
| Acer                | 1        | 1      | 1.35%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 63       | 96     | 39.62%  |
| SSD     | 62       | 83     | 38.99%  |
| NVMe    | 30       | 40     | 18.87%  |
| Unknown | 3        | 5      | 1.89%   |
| MMC     | 1        | 1      | 0.63%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 85       | 172    | 68.55%  |
| NVMe | 30       | 40     | 24.19%  |
| SAS  | 8        | 12     | 6.45%   |
| MMC  | 1        | 1      | 0.81%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 66       | 103    | 51.16%  |
| 0.51-1.0   | 37       | 43     | 28.68%  |
| 1.01-2.0   | 14       | 19     | 10.85%  |
| 3.01-4.0   | 5        | 5      | 3.88%   |
| 2.01-3.0   | 4        | 4      | 3.1%    |
| 4.01-10.0  | 2        | 4      | 1.55%   |
| 10.01-20.0 | 1        | 1      | 0.78%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 23       | 24.73%  |
| 251-500        | 20       | 21.51%  |
| 1001-2000      | 12       | 12.9%   |
| 501-1000       | 11       | 11.83%  |
| 2001-3000      | 9        | 9.68%   |
| More than 3000 | 6        | 6.45%   |
| 51-100         | 6        | 6.45%   |
| 1-20           | 4        | 4.3%    |
| 21-50          | 2        | 2.15%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 23       | 24.47%  |
| 21-50          | 17       | 18.09%  |
| 101-250        | 17       | 18.09%  |
| 51-100         | 10       | 10.64%  |
| 251-500        | 8        | 8.51%   |
| 1001-2000      | 8        | 8.51%   |
| 501-1000       | 7        | 7.45%   |
| More than 3000 | 2        | 2.13%   |
| 2001-3000      | 2        | 2.13%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Desktops | Drives | Percent |
|------------------------------------------|----------|--------|---------|
| WDC WDS100T2B0A-00SM50 1TB SSD           | 1        | 1      | 3.33%   |
| WDC WD3200AAKS-00UU3A0 320GB             | 1        | 1      | 3.33%   |
| WDC WD3200AAJS-00B4A0 320GB              | 1        | 1      | 3.33%   |
| WDC WD2500AAJS-00B4A0 250GB              | 1        | 1      | 3.33%   |
| WDC WD10EZRZ-00HTKB0 1TB                 | 1        | 1      | 3.33%   |
| WDC WD10EADS-98M2B0 1TB                  | 1        | 1      | 3.33%   |
| WDC WD10EADS-00M2B0 1TB                  | 1        | 1      | 3.33%   |
| Toshiba MQ01ABF050 500GB                 | 1        | 1      | 3.33%   |
| Seagate ST500LT012-9WS142 500GB          | 1        | 1      | 3.33%   |
| Seagate ST500LM021-1KJ152 500GB          | 1        | 1      | 3.33%   |
| Seagate ST380815AS 80GB                  | 1        | 1      | 3.33%   |
| Seagate ST3500413AS 500GB                | 1        | 1      | 3.33%   |
| Seagate ST3360320AS 360GB                | 1        | 1      | 3.33%   |
| Seagate ST320LT020-9YG142 320GB          | 1        | 1      | 3.33%   |
| Seagate ST320LT012-1DG14C 320GB          | 1        | 2      | 3.33%   |
| Seagate ST250DM000-1BD141 250GB          | 1        | 1      | 3.33%   |
| Seagate ST2000DM001-1ER164 2TB           | 1        | 1      | 3.33%   |
| Seagate ST1000VM002-1CT162 1TB           | 1        | 1      | 3.33%   |
| Seagate ST1000DM003-9YN162 1TB           | 1        | 1      | 3.33%   |
| Samsung Electronics SSD 870 EVO 500GB    | 1        | 1      | 3.33%   |
| Samsung Electronics SSD 850 EVO 500GB    | 1        | 1      | 3.33%   |
| Samsung Electronics SSD 850 EVO 1TB      | 1        | 2      | 3.33%   |
| Samsung Electronics SSD 840 Series 120GB | 1        | 1      | 3.33%   |
| Maxtor 4K040H2 40GB                      | 1        | 1      | 3.33%   |
| Kingston SA400S37480G 480GB SSD          | 1        | 1      | 3.33%   |
| Hitachi HTS545050A7E380 500GB            | 1        | 1      | 3.33%   |
| Hitachi HDS721050CLA362 500GB            | 1        | 1      | 3.33%   |
| HGST HTS545050A7E380 500GB               | 1        | 1      | 3.33%   |
| GOODRAM SSDPR-CL100-480-G3 480GB         | 1        | 1      | 3.33%   |
| China SSD 512GB                          | 1        | 1      | 3.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 11       | 12     | 37.93%  |
| WDC                 | 7        | 7      | 24.14%  |
| Samsung Electronics | 4        | 5      | 13.79%  |
| Toshiba             | 1        | 1      | 3.45%   |
| Maxtor              | 1        | 1      | 3.45%   |
| Kingston            | 1        | 1      | 3.45%   |
| Hitachi             | 1        | 2      | 3.45%   |
| HGST                | 1        | 1      | 3.45%   |
| GOODRAM             | 1        | 1      | 3.45%   |
| China               | 1        | 1      | 3.45%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 11       | 12     | 52.38%  |
| WDC     | 6        | 6      | 28.57%  |
| Toshiba | 1        | 1      | 4.76%   |
| Maxtor  | 1        | 1      | 4.76%   |
| Hitachi | 1        | 2      | 4.76%   |
| HGST    | 1        | 1      | 4.76%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 20       | 23     | 71.43%  |
| SSD  | 8        | 9      | 28.57%  |

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
| Works    | 83       | 177    | 68.03%  |
| Malfunc  | 28       | 32     | 22.95%  |
| Detected | 11       | 16     | 9.02%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 66       | 49.25%  |
| AMD                         | 25       | 18.66%  |
| Samsung Electronics         | 14       | 10.45%  |
| Phison Electronics          | 7        | 5.22%   |
| ASMedia Technology          | 6        | 4.48%   |
| SanDisk                     | 3        | 2.24%   |
| Kingston Technology Company | 3        | 2.24%   |
| Micron/Crucial Technology   | 2        | 1.49%   |
| Marvell Technology Group    | 2        | 1.49%   |
| VIA Technologies            | 1        | 0.75%   |
| ULi Electronics             | 1        | 0.75%   |
| Silicon Motion              | 1        | 0.75%   |
| Silicon Image               | 1        | 0.75%   |
| Nvidia                      | 1        | 0.75%   |
| LSI Logic / Symbios Logic   | 1        | 0.75%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 9        | 5.42%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 8        | 4.82%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 8        | 4.82%   |
| AMD 500 Series Chipset SATA Controller                                                  | 7        | 4.22%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 6        | 3.61%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5        | 3.01%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 4        | 2.41%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 4        | 2.41%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4        | 2.41%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 4        | 2.41%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4        | 2.41%   |
| Samsung NVMe SSD Controller 980                                                         | 3        | 1.81%   |
| Phison E12 NVMe Controller                                                              | 3        | 1.81%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3        | 1.81%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3        | 1.81%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 3        | 1.81%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 3        | 1.81%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 3        | 1.81%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 3        | 1.81%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3        | 1.81%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3        | 1.81%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3        | 1.81%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3        | 1.81%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                                      | 2        | 1.2%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2        | 1.2%    |
| Phison PS5013 E13 NVMe Controller                                                       | 2        | 1.2%    |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 2        | 1.2%    |
| Intel SATA Controller [RAID mode]                                                       | 2        | 1.2%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2        | 1.2%    |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 2        | 1.2%    |
| Intel 82Q35 Express PT IDER Controller                                                  | 2        | 1.2%    |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 2        | 1.2%    |
| Intel 5 Series/3400 Series Chipset PT IDER Controller                                   | 2        | 1.2%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2        | 1.2%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 2        | 1.2%    |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 2        | 1.2%    |
| Intel 4 Series Chipset PT IDER Controller                                               | 2        | 1.2%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2        | 1.2%    |
| AMD 400 Series Chipset SATA Controller                                                  | 2        | 1.2%    |
| AMD 300 Series Chipset SATA Controller                                                  | 2        | 1.2%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 80       | 58.82%  |
| NVMe | 30       | 22.06%  |
| IDE  | 20       | 14.71%  |
| RAID | 5        | 3.68%   |
| SCSI | 1        | 0.74%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 67       | 72.04%  |
| AMD    | 26       | 27.96%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 4        | 4.3%    |
| Intel Core i7-3770 CPU @ 3.40GHz            | 3        | 3.23%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 3        | 3.23%   |
| Intel Core i7-5820K CPU @ 3.30GHz           | 2        | 2.15%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 2        | 2.15%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 2        | 2.15%   |
| Intel Core i5-4690K CPU @ 3.50GHz           | 2        | 2.15%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 2        | 2.15%   |
| Intel Core i5-3350P CPU @ 3.10GHz           | 2        | 2.15%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 2        | 2.15%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 2        | 2.15%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 2        | 2.15%   |
| AMD Athlon II X4 630 Processor              | 2        | 2.15%   |
| Intel Xeon W-2123 CPU @ 3.60GHz             | 1        | 1.08%   |
| Intel Xeon CPU W3565 @ 3.20GHz              | 1        | 1.08%   |
| Intel Xeon CPU E5520 @ 2.27GHz              | 1        | 1.08%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz         | 1        | 1.08%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 1        | 1.08%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 1        | 1.08%   |
| Intel Pentium CPU 2030M @ 2.50GHz           | 1        | 1.08%   |
| Intel Pentium 4 CPU 3.00GHz                 | 1        | 1.08%   |
| Intel Pentium 4 CPU 2.80GHz                 | 1        | 1.08%   |
| Intel Core M-5Y10c CPU @ 0.80GHz            | 1        | 1.08%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 1        | 1.08%   |
| Intel Core i9-10850K CPU @ 3.60GHz          | 1        | 1.08%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1        | 1.08%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1        | 1.08%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 1        | 1.08%   |
| Intel Core i7 CPU 870 @ 2.93GHz             | 1        | 1.08%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1        | 1.08%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 1        | 1.08%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 1        | 1.08%   |
| Intel Core i5-6402P CPU @ 2.80GHz           | 1        | 1.08%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 1        | 1.08%   |
| Intel Core i5-4670K CPU @ 3.40GHz           | 1        | 1.08%   |
| Intel Core i5-4570T CPU @ 2.90GHz           | 1        | 1.08%   |
| Intel Core i5-4570S CPU @ 2.90GHz           | 1        | 1.08%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1        | 1.08%   |
| Intel Core i5-2300 CPU @ 2.80GHz            | 1        | 1.08%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 1        | 1.08%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 18       | 19.35%  |
| Intel Core i7           | 12       | 12.9%   |
| Intel Core i3           | 10       | 10.75%  |
| AMD Ryzen 5             | 8        | 8.6%    |
| Intel Core 2 Duo        | 7        | 7.53%   |
| AMD Ryzen 7             | 6        | 6.45%   |
| Other                   | 5        | 5.38%   |
| Intel Xeon              | 4        | 4.3%    |
| Intel Celeron           | 3        | 3.23%   |
| AMD Athlon II X4        | 3        | 3.23%   |
| Intel Pentium 4         | 2        | 2.15%   |
| Intel Core i9           | 2        | 2.15%   |
| AMD Ryzen 3             | 2        | 2.15%   |
| AMD Phenom              | 2        | 2.15%   |
| Intel Pentium Dual-Core | 1        | 1.08%   |
| Intel Pentium Dual      | 1        | 1.08%   |
| Intel Pentium           | 1        | 1.08%   |
| Intel Core M            | 1        | 1.08%   |
| AMD Ryzen Threadripper  | 1        | 1.08%   |
| AMD Ryzen 9             | 1        | 1.08%   |
| AMD Ryzen 5 PRO         | 1        | 1.08%   |
| AMD Phenom II X4        | 1        | 1.08%   |
| AMD Athlon              | 1        | 1.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 37       | 39.78%  |
| 2      | 25       | 26.88%  |
| 6      | 12       | 12.9%   |
| 8      | 10       | 10.75%  |
| 12     | 4        | 4.3%    |
| 10     | 2        | 2.15%   |
| 1      | 2        | 2.15%   |
| 16     | 1        | 1.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 92       | 98.92%  |
| 2      | 1        | 1.08%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 51       | 54.84%  |
| 1      | 42       | 45.16%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 92       | 98.92%  |
| 32-bit         | 1        | 1.08%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 10       | 10.75%  |
| Unknown    | 10       | 10.75%  |
| 0x306a9    | 7        | 7.53%   |
| 0x206a7    | 6        | 6.45%   |
| 0x1067a    | 5        | 5.38%   |
| 0x906ed    | 3        | 3.23%   |
| 0x08701021 | 3        | 3.23%   |
| 0x08108109 | 3        | 3.23%   |
| 0x0800820d | 3        | 3.23%   |
| 0x010000db | 3        | 3.23%   |
| 0x6fd      | 2        | 2.15%   |
| 0x506e3    | 2        | 2.15%   |
| 0x306f2    | 2        | 2.15%   |
| 0x20655    | 2        | 2.15%   |
| 0x106e5    | 2        | 2.15%   |
| 0x0a20120a | 2        | 2.15%   |
| 0x01000083 | 2        | 2.15%   |
| 0xf49      | 1        | 1.08%   |
| 0xf34      | 1        | 1.08%   |
| 0xb0671    | 1        | 1.08%   |
| 0xa0671    | 1        | 1.08%   |
| 0xa0655    | 1        | 1.08%   |
| 0xa0653    | 1        | 1.08%   |
| 0x906ea    | 1        | 1.08%   |
| 0x906e9    | 1        | 1.08%   |
| 0x906a4    | 1        | 1.08%   |
| 0x90672    | 1        | 1.08%   |
| 0x706a1    | 1        | 1.08%   |
| 0x506c9    | 1        | 1.08%   |
| 0x50654    | 1        | 1.08%   |
| 0x406c3    | 1        | 1.08%   |
| 0x40651    | 1        | 1.08%   |
| 0x306d4    | 1        | 1.08%   |
| 0x106a5    | 1        | 1.08%   |
| 0x10676    | 1        | 1.08%   |
| 0x0a50000d | 1        | 1.08%   |
| 0x0a201016 | 1        | 1.08%   |
| 0x0a201009 | 1        | 1.08%   |
| 0x08600106 | 1        | 1.08%   |
| 0x08301039 | 1        | 1.08%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 16       | 17.2%   |
| SandyBridge      | 7        | 7.53%   |
| Penryn           | 7        | 7.53%   |
| IvyBridge        | 7        | 7.53%   |
| Zen+             | 6        | 6.45%   |
| Zen 3            | 6        | 6.45%   |
| K10              | 6        | 6.45%   |
| Zen 2            | 5        | 5.38%   |
| KabyLake         | 5        | 5.38%   |
| Skylake          | 4        | 4.3%    |
| Nehalem          | 4        | 4.3%    |
| Zen              | 3        | 3.23%   |
| Unknown          | 3        | 3.23%   |
| Westmere         | 2        | 2.15%   |
| NetBurst         | 2        | 2.15%   |
| Core             | 2        | 2.15%   |
| CometLake        | 2        | 2.15%   |
| Silvermont       | 1        | 1.08%   |
| Icelake          | 1        | 1.08%   |
| Goldmont plus    | 1        | 1.08%   |
| Goldmont         | 1        | 1.08%   |
| Broadwell        | 1        | 1.08%   |
| Alderlake Hybrid | 1        | 1.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 36       | 35.29%  |
| Nvidia | 35       | 34.31%  |
| AMD    | 31       | 30.39%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 5        | 4.85%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 4        | 3.88%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 4        | 3.88%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 4        | 3.88%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 3        | 2.91%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3        | 2.91%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3        | 2.91%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 2.91%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3        | 2.91%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 3        | 2.91%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 2        | 1.94%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 2        | 1.94%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 2        | 1.94%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 1.94%   |
| Intel Core Processor Integrated Graphics Controller                         | 2        | 1.94%   |
| AMD RS880 [Radeon HD 4200]                                                  | 2        | 1.94%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2        | 1.94%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2        | 1.94%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 0.97%   |
| Nvidia NV44A [GeForce 6200]                                                 | 1        | 0.97%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 0.97%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 0.97%   |
| Nvidia GP107GL [Quadro P1000]                                               | 1        | 0.97%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 0.97%   |
| Nvidia GM107GL [Quadro K620]                                                | 1        | 0.97%   |
| Nvidia GK208 [GeForce GT 635]                                               | 1        | 0.97%   |
| Nvidia GK110 [GeForce GTX 780]                                              | 1        | 0.97%   |
| Nvidia GK107GL [Quadro K600]                                                | 1        | 0.97%   |
| Nvidia GF116 [GeForce GT 640 OEM]                                           | 1        | 0.97%   |
| Nvidia GF114 [GeForce GTX 560 Ti]                                           | 1        | 0.97%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 0.97%   |
| Nvidia GF106 [GeForce GTS 450]                                              | 1        | 0.97%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 1        | 0.97%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 1        | 0.97%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 1        | 0.97%   |
| Nvidia G94GL [Quadro FX 1800]                                               | 1        | 0.97%   |
| Nvidia G92 [GeForce 9800 GT]                                                | 1        | 0.97%   |
| Nvidia G86 [GeForce 8500 GT]                                                | 1        | 0.97%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 1        | 0.97%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 0.97%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x Nvidia   | 34       | 36.56%  |
| 1 x Intel    | 28       | 30.11%  |
| 1 x AMD      | 28       | 30.11%  |
| Intel + AMD  | 2        | 2.15%   |
| AMD + Nvidia | 1        | 1.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 66       | 70.97%  |
| Proprietary | 22       | 23.66%  |
| Unknown     | 5        | 5.38%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 35       | 37.23%  |
| 1.01-2.0   | 13       | 13.83%  |
| 3.01-4.0   | 12       | 12.77%  |
| 7.01-8.0   | 10       | 10.64%  |
| 0.51-1.0   | 10       | 10.64%  |
| 0.01-0.5   | 7        | 7.45%   |
| 8.01-16.0  | 5        | 5.32%   |
| 2.01-3.0   | 2        | 2.13%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 16       | 16.33%  |
| Dell                 | 12       | 12.24%  |
| Acer                 | 9        | 9.18%   |
| Hewlett-Packard      | 8        | 8.16%   |
| Goldstar             | 5        | 5.1%    |
| Sony                 | 4        | 4.08%   |
| Fujitsu Siemens      | 4        | 4.08%   |
| AOC                  | 4        | 4.08%   |
| Ancor Communications | 4        | 4.08%   |
| Philips              | 3        | 3.06%   |
| Lenovo               | 3        | 3.06%   |
| Iiyama               | 3        | 3.06%   |
| Eizo                 | 3        | 3.06%   |
| MSI                  | 2        | 2.04%   |
| Medion               | 2        | 2.04%   |
| BenQ                 | 2        | 2.04%   |
| Xiaomi               | 1        | 1.02%   |
| Vizio                | 1        | 1.02%   |
| ViewSonic            | 1        | 1.02%   |
| Vestel Elektronik    | 1        | 1.02%   |
| SAC                  | 1        | 1.02%   |
| RTK                  | 1        | 1.02%   |
| Panasonic            | 1        | 1.02%   |
| NEC Computers        | 1        | 1.02%   |
| MiTAC                | 1        | 1.02%   |
| LG Electronics       | 1        | 1.02%   |
| Grundig              | 1        | 1.02%   |
| Gigabyte Technology  | 1        | 1.02%   |
| CTV                  | 1        | 1.02%   |
| ASUSTek Computer     | 1        | 1.02%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Sony SDM-M81 SNY0480 1280x1024 359x287mm 18.1-inch                     | 2        | 1.92%   |
| Samsung Electronics C32JG5x SAM0FE0 2560x1440 697x392mm 31.5-inch      | 2        | 1.92%   |
| MSI G27C6 MSI5CA9 1920x1080 598x336mm 27.0-inch                        | 2        | 1.92%   |
| Medion MD22322 MEB8101 2560x1440 699x393mm 31.6-inch                   | 2        | 1.92%   |
| Fujitsu Siemens B22W-7 LED FUS0838 1680x1050 474x296mm 22.0-inch       | 2        | 1.92%   |
| Xiaomi Mi TV XMD004A 1920x1080 708x398mm 32.0-inch                     | 1        | 0.96%   |
| Vizio E260MV VIZ0062 1920x1080 509x286mm 23.0-inch                     | 1        | 0.96%   |
| ViewSonic VX1935wm-3 VSCB81E 1440x900 410x256mm 19.0-inch              | 1        | 0.96%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 1        | 0.96%   |
| Sony SDM-HS74P SNY3170 1280x1024 338x270mm 17.0-inch                   | 1        | 0.96%   |
| Sony SDM-HS53 SNY2250 1024x768 304x228mm 15.0-inch                     | 1        | 0.96%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch      | 1        | 0.96%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch      | 1        | 0.96%   |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                       | 1        | 0.96%   |
| Samsung Electronics SyncMaster SAM0594 1680x1050 459x296mm 21.5-inch   | 1        | 0.96%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch   | 1        | 0.96%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch    | 1        | 0.96%   |
| Samsung Electronics SyncMaster SAM0286 1280x720 372x209mm 16.8-inch    | 1        | 0.96%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch   | 1        | 0.96%   |
| Samsung Electronics SMB2030 SAM063C 1600x900 443x249mm 20.0-inch       | 1        | 0.96%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 1        | 0.96%   |
| Samsung Electronics S23B550 SAM0919 1920x1080 510x287mm 23.0-inch      | 1        | 0.96%   |
| Samsung Electronics LCD Monitor SMT24A550                              | 1        | 0.96%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch  | 1        | 0.96%   |
| Samsung Electronics LCD Monitor C32R50x 3840x1080                      | 1        | 0.96%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 1        | 0.96%   |
| SAC DP_FREESYNC SAC2700 2560x1440 597x336mm 27.0-inch                  | 1        | 0.96%   |
| RTK FHD HDR RTKBC32 1920x1080 597x336mm 27.0-inch                      | 1        | 0.96%   |
| Philips PHL 276E9Q PHLC17B 1920x1080 598x336mm 27.0-inch               | 1        | 0.96%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch               | 1        | 0.96%   |
| Philips 170C PHL0848 1280x1024 338x270mm 17.0-inch                     | 1        | 0.96%   |
| Panasonic TV MEIA09B 1280x720 698x392mm 31.5-inch                      | 1        | 0.96%   |
| NEC Computers EA221WM NEC673D 1680x1050 474x296mm 22.0-inch            | 1        | 0.96%   |
| MSI G27C6 MSI5CA9 1920x1080 600x340mm 27.2-inch                        | 1        | 0.96%   |
| MiTAC KOGAN TV MTC6306 1366x768 700x400mm 31.7-inch                    | 1        | 0.96%   |
| LG Electronics LCD Monitor E2211                                       | 1        | 0.96%   |
| Lenovo T22v-10 LEN61BB 1920x1080 476x267mm 21.5-inch                   | 1        | 0.96%   |
| Lenovo LCD Monitor LEN1144 1920x1080 518x324mm 24.1-inch               | 1        | 0.96%   |
| Lenovo E24-20 LEN62A5 1920x1080 527x296mm 23.8-inch                    | 1        | 0.96%   |
| Iiyama PLE430 IVM46B4 1280x1024 340x270mm 17.1-inch                    | 1        | 0.96%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 38       | 39.18%  |
| 2560x1440 (QHD)    | 11       | 11.34%  |
| 1680x1050 (WSXGA+) | 10       | 10.31%  |
| 1280x1024 (SXGA)   | 9        | 9.28%   |
| 3840x2160 (4K)     | 8        | 8.25%   |
| 1366x768 (WXGA)    | 4        | 4.12%   |
| 1440x900 (WXGA+)   | 3        | 3.09%   |
| 3440x1440          | 2        | 2.06%   |
| 1920x1200 (WUXGA)  | 2        | 2.06%   |
| 1280x720 (HD)      | 2        | 2.06%   |
| Unknown            | 2        | 2.06%   |
| 3840x1080          | 1        | 1.03%   |
| 2560x1600          | 1        | 1.03%   |
| 2560x1080          | 1        | 1.03%   |
| 1600x900 (HD+)     | 1        | 1.03%   |
| 1360x768           | 1        | 1.03%   |
| 1024x768 (XGA)     | 1        | 1.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 16       | 16.84%  |
| 23      | 16       | 16.84%  |
| 22      | 9        | 9.47%   |
| 31      | 8        | 8.42%   |
| 24      | 8        | 8.42%   |
| 21      | 6        | 6.32%   |
| Unknown | 6        | 6.32%   |
| 19      | 4        | 4.21%   |
| 18      | 4        | 4.21%   |
| 17      | 4        | 4.21%   |
| 34      | 3        | 3.16%   |
| 15      | 2        | 2.11%   |
| 84      | 1        | 1.05%   |
| 65      | 1        | 1.05%   |
| 61      | 1        | 1.05%   |
| 54      | 1        | 1.05%   |
| 47      | 1        | 1.05%   |
| 40      | 1        | 1.05%   |
| 26      | 1        | 1.05%   |
| 20      | 1        | 1.05%   |
| 16      | 1        | 1.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 37       | 39.78%  |
| 401-500     | 20       | 21.51%  |
| 601-700     | 9        | 9.68%   |
| 351-400     | 6        | 6.45%   |
| 301-350     | 6        | 6.45%   |
| Unknown     | 6        | 6.45%   |
| 1001-1500   | 4        | 4.3%    |
| 701-800     | 3        | 3.23%   |
| 801-900     | 1        | 1.08%   |
| 1501-2000   | 1        | 1.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 59       | 63.44%  |
| 16/10   | 15       | 16.13%  |
| 5/4     | 9        | 9.68%   |
| Unknown | 5        | 5.38%   |
| 21/9    | 3        | 3.23%   |
| 4/3     | 1        | 1.08%   |
| 3/2     | 1        | 1.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 32       | 34.04%  |
| 301-350        | 16       | 17.02%  |
| 351-500        | 11       | 11.7%   |
| 151-200        | 11       | 11.7%   |
| Unknown        | 6        | 6.38%   |
| 141-150        | 5        | 5.32%   |
| More than 1000 | 4        | 4.26%   |
| 251-300        | 4        | 4.26%   |
| 501-1000       | 2        | 2.13%   |
| 121-130        | 1        | 1.06%   |
| 101-110        | 1        | 1.06%   |
| 91-100         | 1        | 1.06%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 63       | 68.48%  |
| 101-120 | 14       | 15.22%  |
| 1-50    | 6        | 6.52%   |
| Unknown | 6        | 6.52%   |
| 121-160 | 2        | 2.17%   |
| 161-240 | 1        | 1.09%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 74       | 79.57%  |
| 2     | 14       | 15.05%  |
| 0     | 3        | 3.23%   |
| 3     | 2        | 2.15%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 54       | 39.42%  |
| Intel                           | 41       | 29.93%  |
| Qualcomm Atheros                | 9        | 6.57%   |
| Ralink Technology               | 5        | 3.65%   |
| TP-Link                         | 4        | 2.92%   |
| MediaTek                        | 3        | 2.19%   |
| Broadcom Limited                | 3        | 2.19%   |
| Broadcom                        | 3        | 2.19%   |
| Ralink                          | 2        | 1.46%   |
| Xiaomi                          | 1        | 0.73%   |
| VIA Technologies                | 1        | 0.73%   |
| Samsung Electronics             | 1        | 0.73%   |
| Qualcomm Atheros Communications | 1        | 0.73%   |
| OPPO Electronics                | 1        | 0.73%   |
| Nvidia                          | 1        | 0.73%   |
| Microsoft                       | 1        | 0.73%   |
| Mercucys                        | 1        | 0.73%   |
| Linksys                         | 1        | 0.73%   |
| JMicron Technology              | 1        | 0.73%   |
| Edimax Technology               | 1        | 0.73%   |
| AVM                             | 1        | 0.73%   |
| Aquantia                        | 1        | 0.73%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 39       | 25.83%  |
| Intel Ethernet Controller I225-V                                  | 8        | 5.3%    |
| Realtek RTL8125 2.5GbE Controller                                 | 4        | 2.65%   |
| Ralink MT7601U Wireless Adapter                                   | 4        | 2.65%   |
| Intel I211 Gigabit Network Connection                             | 4        | 2.65%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4        | 2.65%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 4        | 2.65%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 3        | 1.99%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 1.99%   |
| Intel Ethernet Connection (2) I218-V                              | 3        | 1.99%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 2        | 1.32%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 2        | 1.32%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2        | 1.32%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 1.32%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 2        | 1.32%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2        | 1.32%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2        | 1.32%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 2        | 1.32%   |
| Intel Ethernet Connection I217-V                                  | 2        | 1.32%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 1.32%   |
| Intel 82578DM Gigabit Network Connection                          | 2        | 1.32%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 1.32%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.66%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.66%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                             | 1        | 0.66%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 1        | 0.66%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 0.66%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.66%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter               | 1        | 0.66%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                   | 1        | 0.66%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1        | 0.66%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1        | 0.66%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1        | 0.66%   |
| Realtek B1610311068                                               | 1        | 0.66%   |
| Realtek 8821CE PCIe 802.11ac Wireless Network Controller          | 1        | 0.66%   |
| Realtek 802.11ac NIC                                              | 1        | 0.66%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1        | 0.66%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                         | 1        | 0.66%   |
| Ralink RT2561/RT61 802.11g PCI                                    | 1        | 0.66%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 0.66%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 16       | 32%     |
| Intel                           | 9        | 18%     |
| Ralink Technology               | 5        | 10%     |
| TP-Link                         | 4        | 8%      |
| Qualcomm Atheros                | 3        | 6%      |
| MediaTek                        | 3        | 6%      |
| Ralink                          | 2        | 4%      |
| Qualcomm Atheros Communications | 1        | 2%      |
| Microsoft                       | 1        | 2%      |
| Mercucys                        | 1        | 2%      |
| Linksys                         | 1        | 2%      |
| Edimax Technology               | 1        | 2%      |
| Broadcom Limited                | 1        | 2%      |
| Broadcom                        | 1        | 2%      |
| AVM                             | 1        | 2%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Ralink MT7601U Wireless Adapter                            | 4        | 8%      |
| Realtek RTL88x2bu [AC1200 Techkey]                         | 3        | 6%      |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]               | 2        | 4%      |
| Realtek RTL8192EE PCIe Wireless Network Adapter            | 2        | 4%      |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter        | 2        | 4%      |
| Qualcomm Atheros AR9462 Wireless Network Adapter           | 2        | 4%      |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                    | 2        | 4%      |
| TP-Link RTL8812AU Archer T4U 802.11ac                      | 1        | 2%      |
| TP-Link Archer T3U [Realtek RTL8812BU]                     | 1        | 2%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 1        | 2%      |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter        | 1        | 2%      |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter            | 1        | 2%      |
| Realtek RTL8723BE PCIe Wireless Network Adapter            | 1        | 2%      |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter      | 1        | 2%      |
| Realtek RTL8188EE Wireless Network Adapter                 | 1        | 2%      |
| Realtek B1610311068                                        | 1        | 2%      |
| Realtek 8821CE PCIe 802.11ac Wireless Network Controller   | 1        | 2%      |
| Realtek 802.11ac NIC                                       | 1        | 2%      |
| Ralink RT2870/RT3070 Wireless Adapter                      | 1        | 2%      |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                  | 1        | 2%      |
| Ralink RT2561/RT61 802.11g PCI                             | 1        | 2%      |
| Qualcomm Atheros AR9271 802.11n                            | 1        | 2%      |
| Qualcomm Atheros AR93xx Wireless Network Adapter           | 1        | 2%      |
| Microsoft Xbox Wireless Adapter for Windows                | 1        | 2%      |
| Mercucys MW300UM RTL8192EU wifi                            | 1        | 2%      |
| MediaTek WiFi                                              | 1        | 2%      |
| Linksys WUSB6300 V2                                        | 1        | 2%      |
| Intel Wireless-AC 9260                                     | 1        | 2%      |
| Intel Wireless 8260                                        | 1        | 2%      |
| Intel Wireless 7265                                        | 1        | 2%      |
| Intel Wireless 7260                                        | 1        | 2%      |
| Intel Wireless 3160                                        | 1        | 2%      |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                     | 1        | 2%      |
| Intel Gemini Lake PCH CNVi WiFi                            | 1        | 2%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 1        | 2%      |
| Intel Alder Lake-S PCH CNVi WiFi                           | 1        | 2%      |
| Edimax RTL8192S WLAN Adapter                               | 1        | 2%      |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter | 1        | 2%      |
| Broadcom BCM4360 802.11ac Wireless Network Adapter         | 1        | 2%      |
| AVM FRITZ!WLAN AC 860                                      | 1        | 2%      |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 43       | 44.33%  |
| Intel                 | 38       | 39.18%  |
| Qualcomm Atheros      | 6        | 6.19%   |
| Broadcom Limited      | 2        | 2.06%   |
| Broadcom              | 2        | 2.06%   |
| Xiaomi                | 1        | 1.03%   |
| VIA Technologies      | 1        | 1.03%   |
| OPPO Electronics      | 1        | 1.03%   |
| Nvidia                | 1        | 1.03%   |
| JMicron Technology    | 1        | 1.03%   |
| Aquantia              | 1        | 1.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 39       | 39%     |
| Intel Ethernet Controller I225-V                                  | 8        | 8%      |
| Realtek RTL8125 2.5GbE Controller                                 | 4        | 4%      |
| Intel I211 Gigabit Network Connection                             | 4        | 4%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4        | 4%      |
| Intel 82567LM-3 Gigabit Network Connection                        | 4        | 4%      |
| Intel Ethernet Connection I217-LM                                 | 3        | 3%      |
| Intel Ethernet Connection (2) I218-V                              | 3        | 3%      |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 2%      |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 2        | 2%      |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2        | 2%      |
| Intel Ethernet Connection I217-V                                  | 2        | 2%      |
| Intel Ethernet Connection (2) I219-V                              | 2        | 2%      |
| Intel 82578DM Gigabit Network Connection                          | 2        | 2%      |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 2%      |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 1%      |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 1%      |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 1%      |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 1%      |
| OPPO KALAMA-MTP_CID:0437_SN:AEEEF597                              | 1        | 1%      |
| Nvidia MCP61 Ethernet                                             | 1        | 1%      |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1        | 1%      |
| Intel Ethernet Connection I218-V                                  | 1        | 1%      |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1%      |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 1%      |
| Intel Ethernet Connection (14) I219-V                             | 1        | 1%      |
| Intel 82578DC Gigabit Network Connection                          | 1        | 1%      |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 1%      |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 1%      |
| Broadcom Limited NetXtreme BCM5782 Gigabit Ethernet               | 1        | 1%      |
| Broadcom Limited NetXtreme BCM5754 Gigabit Ethernet PCI Express   | 1        | 1%      |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 1%      |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 92       | 66.67%  |
| WiFi     | 45       | 32.61%  |
| Modem    | 1        | 0.72%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 64       | 68.09%  |
| WiFi     | 30       | 31.91%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 64       | 68.82%  |
| 2     | 25       | 26.88%  |
| 3     | 4        | 4.3%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 65       | 69.89%  |
| Yes  | 28       | 30.11%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 6        | 26.09%  |
| Cambridge Silicon Radio | 5        | 21.74%  |
| Realtek Semiconductor   | 2        | 8.7%    |
| MediaTek                | 2        | 8.7%    |
| Foxconn / Hon Hai       | 2        | 8.7%    |
| Broadcom                | 2        | 8.7%    |
| ASUSTek Computer        | 2        | 8.7%    |
| TP-Link                 | 1        | 4.35%   |
| Apple                   | 1        | 4.35%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 5        | 21.74%  |
| Intel Bluetooth wireless interface                    | 3        | 13.04%  |
| Realtek Bluetooth Radio                               | 2        | 8.7%    |
| MediaTek Wireless_Device                              | 2        | 8.7%    |
| Foxconn / Hon Hai Bluetooth Device                    | 2        | 8.7%    |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 2        | 8.7%    |
| TP-Link UB500 Adapter                                 | 1        | 4.35%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 1        | 4.35%   |
| Intel Bluetooth Device                                | 1        | 4.35%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 1        | 4.35%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 1        | 4.35%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 4.35%   |
| Apple Bluetooth Host Controller                       | 1        | 4.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 64       | 40%     |
| AMD                     | 38       | 23.75%  |
| Nvidia                  | 30       | 18.75%  |
| C-Media Electronics     | 6        | 3.75%   |
| Creative Labs           | 5        | 3.13%   |
| VIA Technologies        | 2        | 1.25%   |
| Texas Instruments       | 2        | 1.25%   |
| ROCCAT                  | 2        | 1.25%   |
| TerraTec Electronic     | 1        | 0.63%   |
| Setek Elektronik        | 1        | 0.63%   |
| Schiit Audio            | 1        | 0.63%   |
| Razer USA               | 1        | 0.63%   |
| JMTek                   | 1        | 0.63%   |
| GYROCOM C&C             | 1        | 0.63%   |
| GN Netcom               | 1        | 0.63%   |
| Generalplus Technology  | 1        | 0.63%   |
| Ensoniq                 | 1        | 0.63%   |
| Digidesign              | 1        | 0.63%   |
| BEHRINGER International | 1        | 0.63%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                           | Desktops | Percent |
|-------------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                | 8        | 4.32%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                      | 8        | 4.32%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                             | 7        | 3.78%   |
| AMD Starship/Matisse HD Audio Controller                                                        | 7        | 3.78%   |
| AMD Family 17h/19h HD Audio Controller                                                          | 7        | 3.78%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                             | 6        | 3.24%   |
| Nvidia GP107GL High Definition Audio Controller                                                 | 5        | 2.7%    |
| AMD SBx00 Azalia (Intel HDA)                                                                    | 5        | 2.7%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                             | 5        | 2.7%    |
| Nvidia GP104 High Definition Audio Controller                                                   | 4        | 2.16%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                             | 4        | 2.16%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                        | 4        | 2.16%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                             | 4        | 2.16%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                         | 4        | 2.16%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                      | 4        | 2.16%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                   | 3        | 1.62%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                           | 3        | 1.62%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                         | 3        | 1.62%   |
| Intel Cannon Lake PCH cAVS                                                                      | 3        | 1.62%   |
| Intel C610/X99 series chipset HD Audio Controller                                               | 3        | 1.62%   |
| Intel 9 Series Chipset Family HD Audio Controller                                               | 3        | 1.62%   |
| Intel 200 Series PCH HD Audio                                                                   | 3        | 1.62%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus] | 3        | 1.62%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                               | 3        | 1.62%   |
| AMD Renoir Radeon High Definition Audio Controller                                              | 3        | 1.62%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                         | 3        | 1.62%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                          | 3        | 1.62%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                    | 3        | 1.62%   |
| Texas Instruments PCM2902 Audio Codec                                                           | 2        | 1.08%   |
| ROCCAT Khan AIMO                                                                                | 2        | 1.08%   |
| Nvidia TU104 HD Audio Controller                                                                | 2        | 1.08%   |
| Nvidia GM206 High Definition Audio Controller                                                   | 2        | 1.08%   |
| Intel Alder Lake-S HD Audio Controller                                                          | 2        | 1.08%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                | 2        | 1.08%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                  | 2        | 1.08%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                 | 2        | 1.08%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                    | 2        | 1.08%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                                       | 1        | 0.54%   |
| VIA Technologies ICE1712 [Envy24] PCI Multi-Channel I/O Controller                              | 1        | 0.54%   |
| TerraTec Electronic Aureon Dual USB                                                             | 1        | 0.54%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 16       | 15.38%  |
| Unknown             | 14       | 13.46%  |
| Samsung Electronics | 14       | 13.46%  |
| Corsair             | 12       | 11.54%  |
| G.Skill             | 9        | 8.65%   |
| A-DATA Technology   | 6        | 5.77%   |
| SK hynix            | 5        | 4.81%   |
| Ramaxel Technology  | 5        | 4.81%   |
| Crucial             | 4        | 3.85%   |
| Nanya Technology    | 3        | 2.88%   |
| Micron Technology   | 3        | 2.88%   |
| Unknown (ABCD)      | 2        | 1.92%   |
| Transcend           | 2        | 1.92%   |
| Unknown             | 2        | 1.92%   |
| Unknown (AB)        | 1        | 0.96%   |
| Unifosa             | 1        | 0.96%   |
| Patriot             | 1        | 0.96%   |
| Golden Empire       | 1        | 0.96%   |
| Elpida              | 1        | 0.96%   |
| Avant               | 1        | 0.96%   |
| Apacer              | 1        | 0.96%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s          | 4        | 3.54%   |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s                       | 2        | 1.77%   |
| Unknown RAM Module 2GB DIMM 667MT/s                            | 2        | 1.77%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 2        | 1.77%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s           | 2        | 1.77%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s            | 2        | 1.77%   |
| G.Skill RAM F4-4000C18-16GTZR 16GB DIMM DDR4 2133MT/s          | 2        | 1.77%   |
| Crucial RAM BLS8G4D32AESBK.M8FE1 8GB DIMM DDR4 3600MT/s        | 2        | 1.77%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s         | 2        | 1.77%   |
| Unknown                                                        | 2        | 1.77%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                      | 1        | 0.88%   |
| Unknown RAM Module 4GB DIMM SDRAM                              | 1        | 0.88%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                      | 1        | 0.88%   |
| Unknown RAM Module 4GB DIMM 667MT/s                            | 1        | 0.88%   |
| Unknown RAM Module 4GB DIMM                                    | 1        | 0.88%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                      | 1        | 0.88%   |
| Unknown RAM Module 2GB DIMM DDR2 1067MT/s                      | 1        | 0.88%   |
| Unknown RAM Module 2GB DIMM 800MT/s                            | 1        | 0.88%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                           | 1        | 0.88%   |
| Unknown RAM Module 1GB DIMM SDRAM                              | 1        | 0.88%   |
| Unknown (AB) RAM Module 2GB DIMM LPDDR3 1333MT/s               | 1        | 0.88%   |
| Unifosa RAM Module 2GB DIMM DDR3 1333MT/s                      | 1        | 0.88%   |
| Transcend RAM JM800QLU-2G 1GB DIMM DDR2 2048MT/s               | 1        | 0.88%   |
| Transcend RAM JM1333KLN-8GK 4GB DIMM DDR3 1333MT/s             | 1        | 0.88%   |
| SK hynix RAM HMT451U6AFR8A-PB 4GB DIMM DDR3 1600MT/s           | 1        | 0.88%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 1        | 0.88%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s           | 1        | 0.88%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s           | 1        | 0.88%   |
| SK hynix RAM HMT125U6DFR8C-H9 2048MB DIMM DDR3 1333MT/s        | 1        | 0.88%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s          | 1        | 0.88%   |
| Samsung RAM M393B5170DZ1-CF8 4GB DIMM DDR3 1066MT/s            | 1        | 0.88%   |
| Samsung RAM M393A4K40DB3-CWE 32GB DIMM DDR4 3200MT/s           | 1        | 0.88%   |
| Samsung RAM M393A2K43CB2-CTD 16GB DIMM DDR4 2666MT/s           | 1        | 0.88%   |
| Samsung RAM M386A4G40DM0-CPB 32GB DIMM DDR4 2133MT/s           | 1        | 0.88%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s            | 1        | 0.88%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s            | 1        | 0.88%   |
| Samsung RAM M378B5273CH0-CK0 4GB DIMM DDR3 2000MT/s            | 1        | 0.88%   |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR3 1867MT/s            | 1        | 0.88%   |
| Samsung RAM M378A1K43EB2-CWE 8192MB DIMM DDR4 3200MT/s         | 1        | 0.88%   |
| Samsung RAM M378A1G43DB0-CPB 8GB DIMM DDR4 2133MT/s            | 1        | 0.88%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 39       | 41.49%  |
| DDR3    | 34       | 36.17%  |
| DDR2    | 6        | 6.38%   |
| Unknown | 6        | 6.38%   |
| SDRAM   | 5        | 5.32%   |
| LPDDR4  | 2        | 2.13%   |
| LPDDR3  | 1        | 1.06%   |
| DDR     | 1        | 1.06%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 83       | 91.21%  |
| SODIMM | 8        | 8.79%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 29       | 29%     |
| 8192  | 23       | 23%     |
| 2048  | 20       | 20%     |
| 16384 | 16       | 16%     |
| 32768 | 6        | 6%      |
| 1024  | 5        | 5%      |
| 256   | 1        | 1%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 16       | 16.16%  |
| 1333    | 15       | 15.15%  |
| 3600    | 11       | 11.11%  |
| 3200    | 8        | 8.08%   |
| 2667    | 5        | 5.05%   |
| 2133    | 5        | 5.05%   |
| 2400    | 4        | 4.04%   |
| 800     | 4        | 4.04%   |
| 667     | 4        | 4.04%   |
| 2666    | 3        | 3.03%   |
| Unknown | 3        | 3.03%   |
| 3400    | 2        | 2.02%   |
| 2048    | 2        | 2.02%   |
| 1066    | 2        | 2.02%   |
| 333     | 2        | 2.02%   |
| 4133    | 1        | 1.01%   |
| 3866    | 1        | 1.01%   |
| 3466    | 1        | 1.01%   |
| 3266    | 1        | 1.01%   |
| 3000    | 1        | 1.01%   |
| 2933    | 1        | 1.01%   |
| 2200    | 1        | 1.01%   |
| 2000    | 1        | 1.01%   |
| 1867    | 1        | 1.01%   |
| 1866    | 1        | 1.01%   |
| 1800    | 1        | 1.01%   |
| 1067    | 1        | 1.01%   |
| 400     | 1        | 1.01%   |

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
| 0     | 78       | 83.87%  |
| 1     | 12       | 12.9%   |
| 2     | 2        | 2.15%   |
| 3     | 1        | 1.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 7        | 38.89%  |
| Net/wireless             | 4        | 22.22%  |
| Unassigned class         | 3        | 16.67%  |
| Communication controller | 2        | 11.11%  |
| Fingerprint reader       | 1        | 5.56%   |
| Dvb card                 | 1        | 5.56%   |

