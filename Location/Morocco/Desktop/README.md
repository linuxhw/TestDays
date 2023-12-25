Linux in Morocco - Tested Hardware & Statistics (Desktops)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Morocco.

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

Total: 97

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Foxconn       | 2ABF                        | [3441aa81e6](https://linux-hardware.org/?probe=3441aa81e6) | Dec 23, 2023 |
| HP            | 18E7                        | [dad5884f78](https://linux-hardware.org/?probe=dad5884f78) | Dec 10, 2023 |
| HP            | 3031h                       | [06a9e0c346](https://linux-hardware.org/?probe=06a9e0c346) | Dec 04, 2023 |
| Dell          | OptiPlex 745                | [1abbad3f94](https://linux-hardware.org/?probe=1abbad3f94) | Nov 23, 2023 |
| Dell          | 0XPDFK A01                  | [8b3abafe9b](https://linux-hardware.org/?probe=8b3abafe9b) | Nov 19, 2023 |
| HP            | 1998                        | [d37c482ca8](https://linux-hardware.org/?probe=d37c482ca8) | Oct 19, 2023 |
| HP            | 18E4                        | [6707337e0c](https://linux-hardware.org/?probe=6707337e0c) | Oct 03, 2023 |
| Dell          | 077RRV A00                  | [5ebc4171ff](https://linux-hardware.org/?probe=5ebc4171ff) | Sep 08, 2023 |
| Lenovo        | 1030 SDK0J40697 WIN 3305... | [e180d8d91b](https://linux-hardware.org/?probe=e180d8d91b) | Aug 31, 2023 |
| HP            | 3031h                       | [4ce70764b2](https://linux-hardware.org/?probe=4ce70764b2) | Aug 16, 2023 |
| ASUSTek       | PRIME B550M-A               | [74a73b0208](https://linux-hardware.org/?probe=74a73b0208) | Aug 13, 2023 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | [5dc4c594ea](https://linux-hardware.org/?probe=5dc4c594ea) | Aug 05, 2023 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | [e8249dc6d6](https://linux-hardware.org/?probe=e8249dc6d6) | Jul 21, 2023 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | [37132be6bd](https://linux-hardware.org/?probe=37132be6bd) | Jul 21, 2023 |
| HP            | 158A                        | [4d915b56e7](https://linux-hardware.org/?probe=4d915b56e7) | Jul 08, 2023 |
| HP            | 0AECh D                     | [bd8035963a](https://linux-hardware.org/?probe=bd8035963a) | Jul 03, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | [6c1829f43d](https://linux-hardware.org/?probe=6c1829f43d) | Jul 01, 2023 |
| HP            | 21F5 0A                     | [dd990a6e99](https://linux-hardware.org/?probe=dd990a6e99) | Jun 26, 2023 |
| HP            | 1589                        | [be15d33d32](https://linux-hardware.org/?probe=be15d33d32) | May 07, 2023 |
| ASUSTek       | PRIME B450M-K               | [3592ce514a](https://linux-hardware.org/?probe=3592ce514a) | Apr 29, 2023 |
| HP            | 0AECh D                     | [f6c67d337e](https://linux-hardware.org/?probe=f6c67d337e) | Apr 17, 2023 |
| HP            | 1494                        | [9c5dc1a221](https://linux-hardware.org/?probe=9c5dc1a221) | Apr 13, 2023 |
| HP            | 89B4 A                      | [cb8136a176](https://linux-hardware.org/?probe=cb8136a176) | Mar 28, 2023 |
| Foxconn       | 2ABF                        | [41f9974254](https://linux-hardware.org/?probe=41f9974254) | Feb 16, 2023 |
| HP            | 18E7                        | [db4ef3e5f4](https://linux-hardware.org/?probe=db4ef3e5f4) | Jan 30, 2023 |
| Dell          | 0MN1TX A02                  | [e0099da561](https://linux-hardware.org/?probe=e0099da561) | Jan 11, 2023 |
| HP            | 2AA2                        | [36f40353c8](https://linux-hardware.org/?probe=36f40353c8) | Oct 25, 2022 |
| HP            | 1497                        | [17a2f79f3f](https://linux-hardware.org/?probe=17a2f79f3f) | Oct 04, 2022 |
| HP            | 1497                        | [fab365512a](https://linux-hardware.org/?probe=fab365512a) | Oct 04, 2022 |
| HP            | 1497                        | [86ab60b437](https://linux-hardware.org/?probe=86ab60b437) | Sep 30, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | [805d4161a8](https://linux-hardware.org/?probe=805d4161a8) | Sep 15, 2022 |
| Lenovo        | SHARKBAY 0C48431 WIN        | [4598920e84](https://linux-hardware.org/?probe=4598920e84) | Sep 13, 2022 |
| HP            | 18E4                        | [2c113164fd](https://linux-hardware.org/?probe=2c113164fd) | Sep 05, 2022 |
| ASRock        | A320M-HDV R4.0              | [3cca56dc74](https://linux-hardware.org/?probe=3cca56dc74) | Aug 22, 2022 |
| HP            | 198E                        | [4327be921d](https://linux-hardware.org/?probe=4327be921d) | Aug 06, 2022 |
| HP            | 198E                        | [284e29b3ea](https://linux-hardware.org/?probe=284e29b3ea) | Aug 06, 2022 |
| ASUSTek       | WS X299 SAGE                | [acb31e0818](https://linux-hardware.org/?probe=acb31e0818) | Jul 18, 2022 |
| Dell          | 0KJCC5 A00                  | [334e57a8b2](https://linux-hardware.org/?probe=334e57a8b2) | Jun 14, 2022 |
| ECS           | Nettle2                     | [4939d60e6d](https://linux-hardware.org/?probe=4939d60e6d) | Mar 27, 2022 |
| HP            | 18E4                        | [e7d597600e](https://linux-hardware.org/?probe=e7d597600e) | Feb 25, 2022 |
| HP            | 3396                        | [e9486b13b8](https://linux-hardware.org/?probe=e9486b13b8) | Jan 20, 2022 |
| HP            | 1589                        | [402f1722ab](https://linux-hardware.org/?probe=402f1722ab) | Jan 09, 2022 |
| HP            | 8054                        | [13d18f87fe](https://linux-hardware.org/?probe=13d18f87fe) | Dec 30, 2021 |
| HP            | 8054                        | [fcf6deb221](https://linux-hardware.org/?probe=fcf6deb221) | Dec 30, 2021 |
| HP            | 1998                        | [f8e644ed15](https://linux-hardware.org/?probe=f8e644ed15) | Dec 23, 2021 |
| HP            | 090Ch                       | [bf92e3c728](https://linux-hardware.org/?probe=bf92e3c728) | Dec 22, 2021 |
| HP            | 1998                        | [ffa6c0b239](https://linux-hardware.org/?probe=ffa6c0b239) | Dec 01, 2021 |
| Dell          | 0MWYPT A01                  | [63385716b2](https://linux-hardware.org/?probe=63385716b2) | Nov 19, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [f8670ddd99](https://linux-hardware.org/?probe=f8670ddd99) | Nov 18, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [b4fb9ffc24](https://linux-hardware.org/?probe=b4fb9ffc24) | Nov 18, 2021 |
| ASUSTek       | Acacia                      | [acb0ed7655](https://linux-hardware.org/?probe=acb0ed7655) | Nov 16, 2021 |
| HP            | 1589                        | [789cbfc3fa](https://linux-hardware.org/?probe=789cbfc3fa) | Nov 10, 2021 |
| Pegatron      | 2AD5                        | [70ae8e4cdf](https://linux-hardware.org/?probe=70ae8e4cdf) | Oct 30, 2021 |
| HP            | 18E7                        | [94c750ba4b](https://linux-hardware.org/?probe=94c750ba4b) | Oct 23, 2021 |
| American M... | K7S41GX                     | [b5f8d33cc4](https://linux-hardware.org/?probe=b5f8d33cc4) | Oct 20, 2021 |
| American M... | K7S41GX                     | [920a47f107](https://linux-hardware.org/?probe=920a47f107) | Oct 20, 2021 |
| HP            | 3032h                       | [6914386d3d](https://linux-hardware.org/?probe=6914386d3d) | Oct 19, 2021 |
| HP            | 1589                        | [bb8d8d60cf](https://linux-hardware.org/?probe=bb8d8d60cf) | Oct 10, 2021 |
| Dell          | 0J3C2F A00                  | [565fbea977](https://linux-hardware.org/?probe=565fbea977) | Oct 10, 2021 |
| Foxconn       | 2ABF                        | [92bc4bf86c](https://linux-hardware.org/?probe=92bc4bf86c) | Oct 04, 2021 |
| HP            | 18E7                        | [e1aa6d3e49](https://linux-hardware.org/?probe=e1aa6d3e49) | Sep 19, 2021 |
| HP            | 0AACh                       | [588b35da24](https://linux-hardware.org/?probe=588b35da24) | Aug 21, 2021 |
| Lenovo        | SHARKBAY NOK                | [f0faf00d2f](https://linux-hardware.org/?probe=f0faf00d2f) | Aug 09, 2021 |
| Dell          | 0NX0PH A01                  | [8416267437](https://linux-hardware.org/?probe=8416267437) | Aug 09, 2021 |
| HP            | 339A                        | [7ea04a15cb](https://linux-hardware.org/?probe=7ea04a15cb) | Jul 18, 2021 |
| HP            | 339A                        | [31018180f8](https://linux-hardware.org/?probe=31018180f8) | Jul 16, 2021 |
| Foxconn       | 2ABF                        | [77e63e8902](https://linux-hardware.org/?probe=77e63e8902) | Jul 06, 2021 |
| HP            | 3396                        | [28e2f6399c](https://linux-hardware.org/?probe=28e2f6399c) | Jul 05, 2021 |
| Dell          | 0KC9NP A01                  | [513f79e441](https://linux-hardware.org/?probe=513f79e441) | May 26, 2021 |
| HP            | 0AACh                       | [92920ff59a](https://linux-hardware.org/?probe=92920ff59a) | May 26, 2021 |
| MSI           | 2A9C                        | [db1be00449](https://linux-hardware.org/?probe=db1be00449) | May 02, 2021 |
| Foxconn       | 2ACA                        | [04556ec49b](https://linux-hardware.org/?probe=04556ec49b) | Mar 26, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [7a6947637a](https://linux-hardware.org/?probe=7a6947637a) | Mar 16, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [635fc4a0a2](https://linux-hardware.org/?probe=635fc4a0a2) | Mar 16, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [6bccb5f740](https://linux-hardware.org/?probe=6bccb5f740) | Mar 15, 2021 |
| Dell          | 0MWYPT A01                  | [1c76380527](https://linux-hardware.org/?probe=1c76380527) | Mar 06, 2021 |
| HP            | 1495                        | [ca9664aff0](https://linux-hardware.org/?probe=ca9664aff0) | Mar 05, 2021 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | [ab67b7aab9](https://linux-hardware.org/?probe=ab67b7aab9) | Feb 22, 2021 |
| Dell          | 0M863N A01                  | [c10de13cf0](https://linux-hardware.org/?probe=c10de13cf0) | Feb 05, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [7861f8622e](https://linux-hardware.org/?probe=7861f8622e) | Feb 01, 2021 |
| ASUSTek       | Crosshair IV Formula        | [3475dcd9b6](https://linux-hardware.org/?probe=3475dcd9b6) | Jan 17, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [8d7a3472b3](https://linux-hardware.org/?probe=8d7a3472b3) | Jan 16, 2021 |
| HP            | 158A                        | [afd1e7439b](https://linux-hardware.org/?probe=afd1e7439b) | Dec 28, 2020 |
| ASUSTek       | Crosshair IV Formula        | [4a4ce9f5d2](https://linux-hardware.org/?probe=4a4ce9f5d2) | Dec 25, 2020 |
| HP            | 304Ah                       | [d5f7af2482](https://linux-hardware.org/?probe=d5f7af2482) | Nov 23, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [193c57b056](https://linux-hardware.org/?probe=193c57b056) | Nov 10, 2020 |
| Dell          | 0MWYPT A01                  | [3134def56f](https://linux-hardware.org/?probe=3134def56f) | Oct 11, 2020 |
| HP            | 3398                        | [6b7ea8d306](https://linux-hardware.org/?probe=6b7ea8d306) | Aug 27, 2020 |
| HP            | 3397                        | [de9945e027](https://linux-hardware.org/?probe=de9945e027) | Jun 30, 2020 |
| HP            | 0A04h                       | [c0b180275b](https://linux-hardware.org/?probe=c0b180275b) | May 05, 2020 |
| HP            | 0A04h                       | [bb34c7e807](https://linux-hardware.org/?probe=bb34c7e807) | May 05, 2020 |
| HP            | 3397                        | [37ddb2349c](https://linux-hardware.org/?probe=37ddb2349c) | Mar 20, 2020 |
| HP            | 1494                        | [af749848e8](https://linux-hardware.org/?probe=af749848e8) | Nov 23, 2019 |
| Dell          | 0D28YY A03                  | [0be7a39100](https://linux-hardware.org/?probe=0be7a39100) | Jul 14, 2019 |
| Lenovo        | MAHOBAY NO DPK              | [730a048dd9](https://linux-hardware.org/?probe=730a048dd9) | Dec 20, 2018 |
| Lenovo        | MAHOBAY NO DPK              | [36a6a5ce8c](https://linux-hardware.org/?probe=36a6a5ce8c) | Dec 20, 2018 |
| Dell          | 0DR845                      | [3e45e16507](https://linux-hardware.org/?probe=3e45e16507) | Sep 23, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Ubuntu 20.04       | 8        | 9.88%   |
| Ubuntu 22.04       | 7        | 8.64%   |
| OpenMandriva 4.50  | 5        | 6.17%   |
| OpenMandriva 4.2   | 5        | 6.17%   |
| Debian 11          | 5        | 6.17%   |
| Ubuntu 18.04       | 4        | 4.94%   |
| Fedora 33          | 4        | 4.94%   |
| OpenMandriva 23.90 | 2        | 2.47%   |
| Linux Mint 21      | 2        | 2.47%   |
| Fedora 38          | 2        | 2.47%   |
| Debian 12          | 2        | 2.47%   |
| BlackPanther 18.1  | 2        | 2.47%   |
| Zorin 16           | 1        | 1.23%   |
| Zorin 15           | 1        | 1.23%   |
| Xubuntu 18.04      | 1        | 1.23%   |
| Ubuntu Unity 16.04 | 1        | 1.23%   |
| Ubuntu MATE 22.04  | 1        | 1.23%   |
| Ubuntu 20.10       | 1        | 1.23%   |
| Ubuntu 16.04       | 1        | 1.23%   |
| ROSA R8.1          | 1        | 1.23%   |
| Pop!_OS 21.04      | 1        | 1.23%   |
| Pop!_OS 20.10      | 1        | 1.23%   |
| Pear OS 21.04      | 1        | 1.23%   |
| Parrot 5.0         | 1        | 1.23%   |
| OpenMandriva 5.0   | 1        | 1.23%   |
| OpenMandriva 4.3   | 1        | 1.23%   |
| OpenMandriva 23.10 | 1        | 1.23%   |
| OpenMandriva 23.08 | 1        | 1.23%   |
| OpenMandriva 23.01 | 1        | 1.23%   |
| Manjaro 21.0.7     | 1        | 1.23%   |
| Lubuntu 18.04      | 1        | 1.23%   |
| Linux Mint 20.3    | 1        | 1.23%   |
| Linux Mint 20.2    | 1        | 1.23%   |
| Linux Mint 19.3    | 1        | 1.23%   |
| KDE neon 20.04     | 1        | 1.23%   |
| Kali 2023.3        | 1        | 1.23%   |
| Kali 2023.2        | 1        | 1.23%   |
| Kali 2021.4        | 1        | 1.23%   |
| Fedora 39          | 1        | 1.23%   |
| Elementary 7.1     | 1        | 1.23%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 21       | 28%     |
| OpenMandriva | 15       | 20%     |
| Fedora       | 7        | 9.33%   |
| Debian       | 6        | 8%      |
| Linux Mint   | 5        | 6.67%   |
| Kali         | 3        | 4%      |
| Zorin        | 2        | 2.67%   |
| Pop!_OS      | 2        | 2.67%   |
| BlackPanther | 2        | 2.67%   |
| Xubuntu      | 1        | 1.33%   |
| Ubuntu Unity | 1        | 1.33%   |
| Ubuntu MATE  | 1        | 1.33%   |
| ROSA         | 1        | 1.33%   |
| Pear OS      | 1        | 1.33%   |
| Parrot       | 1        | 1.33%   |
| Manjaro      | 1        | 1.33%   |
| Lubuntu      | 1        | 1.33%   |
| KDE neon     | 1        | 1.33%   |
| Elementary   | 1        | 1.33%   |
| ArcoLinux    | 1        | 1.33%   |
| Arch         | 1        | 1.33%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.10.14-desktop-1omv4002 | 5        | 5.81%   |
| 5.12.4-desktop-1omv4050  | 4        | 4.65%   |
| 6.4.11-desktop-1omv2390  | 2        | 2.33%   |
| 5.16.7-desktop-1omv4003  | 2        | 2.33%   |
| 5.15.0-41-generic        | 2        | 2.33%   |
| 6.6.4-200.fc39.x86_64    | 1        | 1.16%   |
| 6.6.1-desktop-1omv2390   | 1        | 1.16%   |
| 6.5.5-desktop-1omv2390   | 1        | 1.16%   |
| 6.5.0-kali2-amd64        | 1        | 1.16%   |
| 6.4.6-200.fc38.x86_64    | 1        | 1.16%   |
| 6.4.10-arch1-1           | 1        | 1.16%   |
| 6.3.12-200.fc38.x86_64   | 1        | 1.16%   |
| 6.2.9-300.fc38.x86_64    | 1        | 1.16%   |
| 6.2.0-33-generic         | 1        | 1.16%   |
| 6.2.0-32-generic         | 1        | 1.16%   |
| 6.1.1-desktop-1omv2290   | 1        | 1.16%   |
| 6.1.0-9-amd64            | 1        | 1.16%   |
| 6.1.0-8-amd64            | 1        | 1.16%   |
| 6.1.0-7-amd64            | 1        | 1.16%   |
| 6.0.0-kali3-amd64        | 1        | 1.16%   |
| 5.8.18-300.fc33.x86_64   | 1        | 1.16%   |
| 5.8.0-7642-generic       | 1        | 1.16%   |
| 5.8.0-59-generic         | 1        | 1.16%   |
| 5.8.0-38-generic         | 1        | 1.16%   |
| 5.8.0-29-generic         | 1        | 1.16%   |
| 5.6.14-desktop-2bP       | 1        | 1.16%   |
| 5.4.0-90-generic         | 1        | 1.16%   |
| 5.4.0-74-generic         | 1        | 1.16%   |
| 5.4.0-70-generic         | 1        | 1.16%   |
| 5.4.0-60-generic         | 1        | 1.16%   |
| 5.4.0-59-generic         | 1        | 1.16%   |
| 5.4.0-58-generic         | 1        | 1.16%   |
| 5.4.0-48-generic         | 1        | 1.16%   |
| 5.4.0-42-generic         | 1        | 1.16%   |
| 5.4.0-39-generic         | 1        | 1.16%   |
| 5.3.0-46-generic         | 1        | 1.16%   |
| 5.3.0-42-generic         | 1        | 1.16%   |
| 5.19.5-desktop-1omv4090  | 1        | 1.16%   |
| 5.19.0-41-generic        | 1        | 1.16%   |
| 5.19.0-38-generic        | 1        | 1.16%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 12       | 14.29%  |
| 5.4.0   | 7        | 8.33%   |
| 5.10.14 | 5        | 5.95%   |
| 5.10.0  | 5        | 5.95%   |
| 4.15.0  | 5        | 5.95%   |
| 5.8.0   | 4        | 4.76%   |
| 5.12.4  | 4        | 4.76%   |
| 6.1.0   | 3        | 3.57%   |
| 5.11.0  | 3        | 3.57%   |
| 6.4.11  | 2        | 2.38%   |
| 6.2.0   | 2        | 2.38%   |
| 5.3.0   | 2        | 2.38%   |
| 5.19.0  | 2        | 2.38%   |
| 5.16.7  | 2        | 2.38%   |
| 5.14.0  | 2        | 2.38%   |
| 6.6.4   | 1        | 1.19%   |
| 6.6.1   | 1        | 1.19%   |
| 6.5.5   | 1        | 1.19%   |
| 6.5.0   | 1        | 1.19%   |
| 6.4.6   | 1        | 1.19%   |
| 6.4.10  | 1        | 1.19%   |
| 6.3.12  | 1        | 1.19%   |
| 6.2.9   | 1        | 1.19%   |
| 6.1.1   | 1        | 1.19%   |
| 6.0.0   | 1        | 1.19%   |
| 5.8.18  | 1        | 1.19%   |
| 5.6.14  | 1        | 1.19%   |
| 5.19.5  | 1        | 1.19%   |
| 5.13.0  | 1        | 1.19%   |
| 5.11.8  | 1        | 1.19%   |
| 5.10.88 | 1        | 1.19%   |
| 5.10.7  | 1        | 1.19%   |
| 5.10.42 | 1        | 1.19%   |
| 5.10.15 | 1        | 1.19%   |
| 5.10.11 | 1        | 1.19%   |
| 4.9.41  | 1        | 1.19%   |
| 4.19.0  | 1        | 1.19%   |
| 4.18.16 | 1        | 1.19%   |
| 4.18.0  | 1        | 1.19%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 14       | 16.87%  |
| 5.15    | 12       | 14.46%  |
| 5.4     | 7        | 8.43%   |
| 5.8     | 5        | 6.02%   |
| 4.15    | 5        | 6.02%   |
| 6.4     | 4        | 4.82%   |
| 6.1     | 4        | 4.82%   |
| 5.12    | 4        | 4.82%   |
| 5.11    | 4        | 4.82%   |
| 6.2     | 3        | 3.61%   |
| 5.19    | 3        | 3.61%   |
| 6.6     | 2        | 2.41%   |
| 6.5     | 2        | 2.41%   |
| 5.3     | 2        | 2.41%   |
| 5.16    | 2        | 2.41%   |
| 5.14    | 2        | 2.41%   |
| 4.18    | 2        | 2.41%   |
| 6.3     | 1        | 1.2%    |
| 6.0     | 1        | 1.2%    |
| 5.6     | 1        | 1.2%    |
| 5.13    | 1        | 1.2%    |
| 4.9     | 1        | 1.2%    |
| 4.19    | 1        | 1.2%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 72       | 96%     |
| i686   | 3        | 4%      |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 35       | 44.87%  |
| KDE5       | 20       | 25.64%  |
| XFCE       | 4        | 5.13%   |
| Unknown    | 4        | 5.13%   |
| X-Cinnamon | 3        | 3.85%   |
| MATE       | 3        | 3.85%   |
| LXDE       | 2        | 2.56%   |
| KDE        | 2        | 2.56%   |
| Unity      | 1        | 1.28%   |
| qtile      | 1        | 1.28%   |
| Pantheon   | 1        | 1.28%   |
| KDE4       | 1        | 1.28%   |
| Cinnamon   | 1        | 1.28%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 57       | 74.03%  |
| Wayland | 16       | 20.78%  |
| Tty     | 2        | 2.6%    |
| Unknown | 2        | 2.6%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 27       | 34.62%  |
| SDDM    | 20       | 25.64%  |
| GDM3    | 12       | 15.38%  |
| LightDM | 10       | 12.82%  |
| GDM     | 7        | 8.97%   |
| TDM     | 1        | 1.28%   |
| KDM     | 1        | 1.28%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 36       | 46.75%  |
| fr_FR   | 25       | 32.47%  |
| Unknown | 6        | 7.79%   |
| en_GB   | 5        | 6.49%   |
| C       | 2        | 2.6%    |
| fr_CH   | 1        | 1.3%    |
| ar_MA   | 1        | 1.3%    |
| ar_DZ   | 1        | 1.3%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 46       | 61.33%  |
| EFI  | 29       | 38.67%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 46       | 61.33%  |
| Overlay | 15       | 20%     |
| Btrfs   | 8        | 10.67%  |
| Tmpfs   | 3        | 4%      |
| Unknown | 2        | 2.67%   |
| Xfs     | 1        | 1.33%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 32       | 42.67%  |
| GPT     | 30       | 40%     |
| MBR     | 13       | 17.33%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 58       | 77.33%  |
| Yes       | 17       | 22.67%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 40       | 52.63%  |
| No        | 36       | 47.37%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 36       | 48.65%  |
| Dell                | 12       | 16.22%  |
| ASUSTek Computer    | 9        | 12.16%  |
| Lenovo              | 6        | 8.11%   |
| Foxconn             | 4        | 5.41%   |
| Pegatron            | 1        | 1.35%   |
| MSI                 | 1        | 1.35%   |
| Gigabyte Technology | 1        | 1.35%   |
| Fujitsu             | 1        | 1.35%   |
| ECS                 | 1        | 1.35%   |
| ASRock              | 1        | 1.35%   |
| American Megatrends | 1        | 1.35%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| HP ProDesk 600 G1 TWR                  | 3        | 4.05%   |
| HP EliteDesk 800 G1 SFF                | 3        | 4.05%   |
| HP Z620 Workstation                    | 2        | 2.7%    |
| HP EliteDesk 800 G1 TWR                | 2        | 2.7%    |
| HP Compaq Elite 8300 SFF               | 2        | 2.7%    |
| HP Compaq Elite 8300 CMT               | 2        | 2.7%    |
| HP Compaq dc7900 Small Form Factor     | 2        | 2.7%    |
| HP Compaq dc7800 Convertible Minitower | 2        | 2.7%    |
| HP Compaq 8200 Elite CMT PC            | 2        | 2.7%    |
| Dell OptiPlex 790                      | 2        | 2.7%    |
| Pegatron h8-1507ef                     | 1        | 1.35%   |
| MSI PPPPP-CCC#MMMMMMMM                 | 1        | 1.35%   |
| Lenovo ThinkStation P700 30A8S26000    | 1        | 1.35%   |
| Lenovo ThinkStation P300 30AGS0FY06    | 1        | 1.35%   |
| Lenovo ThinkCentre M93p 10AAS0R301     | 1        | 1.35%   |
| Lenovo ThinkCentre M910t 10MNS04E4X    | 1        | 1.35%   |
| Lenovo ThinkCentre M72e 3261A85        | 1        | 1.35%   |
| Lenovo SHARKBAY 0C48431 WIN            | 1        | 1.35%   |
| HP Z800 Workstation                    | 1        | 1.35%   |
| HP Z420 Workstation                    | 1        | 1.35%   |
| HP xw6400 Workstation                  | 1        | 1.35%   |
| HP ProDesk 600 G1 SFF                  | 1        | 1.35%   |
| HP ProDesk 490 G2 MT                   | 1        | 1.35%   |
| HP ProDesk 400 G2 MT                   | 1        | 1.35%   |
| HP Pro Tower 290 G9 Desktop PC         | 1        | 1.35%   |
| HP EliteDesk 800 G2 SFF                | 1        | 1.35%   |
| HP dc5000 SFF(PP682US)                 | 1        | 1.35%   |
| HP Compaq Pro 6300 SFF                 | 1        | 1.35%   |
| HP Compaq Elite 8300 USDT              | 1        | 1.35%   |
| HP Compaq dc7900 Convertible Minitower | 1        | 1.35%   |
| HP Compaq 8200 Elite SFF PC            | 1        | 1.35%   |
| HP Compaq 8100 Elite SFF PC            | 1        | 1.35%   |
| HP Compaq 6200 Pro MT PC               | 1        | 1.35%   |
| HP 200-5111es                          | 1        | 1.35%   |
| Gigabyte X570 AORUS MASTER             | 1        | 1.35%   |
| Fujitsu ESPRIMO D556/2                 | 1        | 1.35%   |
| Foxconn Pro3500 Series                 | 1        | 1.35%   |
| Foxconn Pro 3500 Series                | 1        | 1.35%   |
| Foxconn p6-2002es                      | 1        | 1.35%   |
| Foxconn CQ1140FRm                      | 1        | 1.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                        | Desktops | Percent |
|-----------------------------|----------|---------|
| HP Compaq                   | 16       | 21.62%  |
| Dell OptiPlex               | 8        | 10.81%  |
| HP ProDesk                  | 6        | 8.11%   |
| HP EliteDesk                | 6        | 8.11%   |
| Lenovo ThinkCentre          | 3        | 4.05%   |
| Dell Precision              | 3        | 4.05%   |
| ASUS ROG                    | 3        | 4.05%   |
| Lenovo ThinkStation         | 2        | 2.7%    |
| HP Z620                     | 2        | 2.7%    |
| ASUS PRIME                  | 2        | 2.7%    |
| Pegatron h8-1507ef          | 1        | 1.35%   |
| MSI PPPPP-CCC#MMMMMMMM      | 1        | 1.35%   |
| Lenovo SHARKBAY             | 1        | 1.35%   |
| HP Z800                     | 1        | 1.35%   |
| HP Z420                     | 1        | 1.35%   |
| HP xw6400                   | 1        | 1.35%   |
| HP Pro                      | 1        | 1.35%   |
| HP dc5000                   | 1        | 1.35%   |
| HP 200-5111es               | 1        | 1.35%   |
| Gigabyte X570               | 1        | 1.35%   |
| Fujitsu ESPRIMO             | 1        | 1.35%   |
| Foxconn Pro3500             | 1        | 1.35%   |
| Foxconn Pro                 | 1        | 1.35%   |
| Foxconn p6-2002es           | 1        | 1.35%   |
| Foxconn CQ1140FRm           | 1        | 1.35%   |
| ECS GV460AA-ABA             | 1        | 1.35%   |
| Dell Vostro                 | 1        | 1.35%   |
| ASUS Z170                   | 1        | 1.35%   |
| ASUS WS                     | 1        | 1.35%   |
| ASUS GV454AA-ABU            | 1        | 1.35%   |
| ASUS Crosshair              | 1        | 1.35%   |
| ASRock A320M-HDV            | 1        | 1.35%   |
| American Megatrends K7S41GX | 1        | 1.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 13       | 17.57%  |
| 2012 | 11       | 14.86%  |
| 2011 | 8        | 10.81%  |
| 2007 | 6        | 8.11%   |
| 2018 | 5        | 6.76%   |
| 2021 | 4        | 5.41%   |
| 2014 | 4        | 5.41%   |
| 2017 | 3        | 4.05%   |
| 2015 | 3        | 4.05%   |
| 2010 | 3        | 4.05%   |
| 2009 | 3        | 4.05%   |
| 2008 | 3        | 4.05%   |
| 2016 | 2        | 2.7%    |
| 2004 | 2        | 2.7%    |
| 2022 | 1        | 1.35%   |
| 2020 | 1        | 1.35%   |
| 2019 | 1        | 1.35%   |
| 2006 | 1        | 1.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 74       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 72       | 96%     |
| Enabled  | 3        | 4%      |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 74       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 18       | 24%     |
| 3.01-4.0    | 15       | 20%     |
| 16.01-24.0  | 13       | 17.33%  |
| 8.01-16.0   | 9        | 12%     |
| 64.01-256.0 | 5        | 6.67%   |
| 1.01-2.0    | 5        | 6.67%   |
| 32.01-64.0  | 4        | 5.33%   |
| 24.01-32.0  | 4        | 5.33%   |
| 2.01-3.0    | 2        | 2.67%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 32       | 38.55%  |
| 2.01-3.0  | 21       | 25.3%   |
| 4.01-8.0  | 10       | 12.05%  |
| 3.01-4.0  | 10       | 12.05%  |
| 0.51-1.0  | 8        | 9.64%   |
| 8.01-16.0 | 1        | 1.2%    |
| 0.01-0.5  | 1        | 1.2%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 36       | 47.37%  |
| 2      | 26       | 34.21%  |
| 3      | 11       | 14.47%  |
| 4      | 3        | 3.95%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 43       | 58.11%  |
| No        | 31       | 41.89%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 74       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 43       | 58.11%  |
| No        | 31       | 41.89%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 56       | 75.68%  |
| Yes       | 18       | 24.32%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Morocco | 74       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Desktops | Percent |
|---------------|----------|---------|
| Casablanca    | 28       | 35.44%  |
| Agadir        | 7        | 8.86%   |
| Tangier       | 6        | 7.59%   |
| Salé         | 6        | 7.59%   |
| Fes           | 6        | 7.59%   |
| Marrakesh     | 5        | 6.33%   |
| Meknes        | 2        | 2.53%   |
| Youssoufia    | 1        | 1.27%   |
| Tiznit        | 1        | 1.27%   |
| Tétouan      | 1        | 1.27%   |
| Temara        | 1        | 1.27%   |
| Taza          | 1        | 1.27%   |
| Taounate      | 1        | 1.27%   |
| Skhirate      | 1        | 1.27%   |
| Sidi Lmokhtar | 1        | 1.27%   |
| Safi          | 1        | 1.27%   |
| Rabat         | 1        | 1.27%   |
| Oujda         | 1        | 1.27%   |
| Ouirgane      | 1        | 1.27%   |
| Mohammedia    | 1        | 1.27%   |
| El Jadida     | 1        | 1.27%   |
| Douar Kalaa   | 1        | 1.27%   |
| Dar Bouazza   | 1        | 1.27%   |
| Chefchaouen   | 1        | 1.27%   |
| Berrechid     | 1        | 1.27%   |
| Berkane       | 1        | 1.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| WDC                   | 23       | 31     | 20.18%  |
| Seagate               | 23       | 32     | 20.18%  |
| Samsung Electronics   | 16       | 22     | 14.04%  |
| Hitachi               | 12       | 16     | 10.53%  |
| Toshiba               | 5        | 10     | 4.39%   |
| HGST                  | 5        | 6      | 4.39%   |
| Intel                 | 3        | 3      | 2.63%   |
| Micron Technology     | 2        | 3      | 1.75%   |
| KingFast              | 2        | 2      | 1.75%   |
| Fujitsu               | 2        | 2      | 1.75%   |
| Crucial               | 2        | 3      | 1.75%   |
| China                 | 2        | 2      | 1.75%   |
| TwinMOS               | 1        | 1      | 0.88%   |
| Supersonic            | 1        | 2      | 0.88%   |
| SPCC                  | 1        | 2      | 0.88%   |
| SanDisk               | 1        | 1      | 0.88%   |
| Realtek Semiconductor | 1        | 1      | 0.88%   |
| PNY                   | 1        | 1      | 0.88%   |
| Phison                | 1        | 2      | 0.88%   |
| Mushkin               | 1        | 1      | 0.88%   |
| Magnetic Data         | 1        | 1      | 0.88%   |
| LITEON                | 1        | 1      | 0.88%   |
| Lexar                 | 1        | 1      | 0.88%   |
| Kingston              | 1        | 2      | 0.88%   |
| HS-SSD-E100           | 1        | 1      | 0.88%   |
| HPE                   | 1        | 2      | 0.88%   |
| AFOX                  | 1        | 1      | 0.88%   |
| ADATA Technology      | 1        | 1      | 0.88%   |
| Unknown               | 1        | 1      | 0.88%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB      | 4        | 3.2%    |
| WDC WD5000AAKX-60U6AA0 500GB         | 3        | 2.4%    |
| Seagate ST3250312AS 250GB            | 3        | 2.4%    |
| Hitachi HUA723020ALA641 2TB          | 3        | 2.4%    |
| WDC WD800JD-00LSA0 80GB              | 2        | 1.6%    |
| Seagate ST250DM000-1BD141 250GB      | 2        | 1.6%    |
| Samsung MZ7LN128HCHP-000H1 128GB SSD | 2        | 1.6%    |
| Samsung HD161GJ 160GB                | 2        | 1.6%    |
| Intel SSDSC2BF180A4H 180GB           | 2        | 1.6%    |
| Hitachi HUS724030ALE641 3TB          | 2        | 1.6%    |
| Hitachi HDS721680PLA380 80GB         | 2        | 1.6%    |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 1        | 0.8%    |
| WDC WD800JD-75MSA3 80GB              | 1        | 0.8%    |
| WDC WD800AAJS-60WAA0 80GB            | 1        | 0.8%    |
| WDC WD5000BEKT-75KA9T0 500GB         | 1        | 0.8%    |
| WDC WD5000AZLX-60K2TA0 500GB         | 1        | 0.8%    |
| WDC WD5000AAKX-08U6AA0 500GB         | 1        | 0.8%    |
| WDC WD5000AAKS-65V0A0 500GB          | 1        | 0.8%    |
| WDC WD400BB-60DGA0 40GB              | 1        | 0.8%    |
| WDC WD3200BEKT-60F3T1 320GB          | 1        | 0.8%    |
| WDC WD3200AAJS-65RYA0 320GB          | 1        | 0.8%    |
| WDC WD2500AAKX-603CA0 250GB          | 1        | 0.8%    |
| WDC WD2500AAJS-60Z0A0 250GB          | 1        | 0.8%    |
| WDC WD20EARX-00PASB0 2TB             | 1        | 0.8%    |
| WDC WD2002FYPS-02W3B0 2TB            | 1        | 0.8%    |
| WDC WD1600JS-55NCB1 160GB            | 1        | 0.8%    |
| WDC WD1600BEVT-80A23T0 160GB         | 1        | 0.8%    |
| WDC WD1600AAJS-75M0A0 160GB          | 1        | 0.8%    |
| WDC WD1600AAJS-60M0A0 160GB          | 1        | 0.8%    |
| WDC WD1200BEVS-60UST0 120GB          | 1        | 0.8%    |
| WDC WD10EZEX-21WN4A0 1TB             | 1        | 0.8%    |
| WDC WD10EZEX-00BN5A0 1TB             | 1        | 0.8%    |
| TwinMOS SSD 256GB                    | 1        | 0.8%    |
| Toshiba MQ02ABF050H 500GB            | 1        | 0.8%    |
| Toshiba MQ01ABD050V -63 500GB        | 1        | 0.8%    |
| Toshiba DT01ACA200 2TB               | 1        | 0.8%    |
| Toshiba DT01ACA100 LENOVO 1TB        | 1        | 0.8%    |
| Toshiba DT01ACA100 1TB               | 1        | 0.8%    |
| Supersonic SUPERSONIC256 256GB SSD   | 1        | 0.8%    |
| SPCC Solid State Disk 1024GB         | 1        | 0.8%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 23       | 32     | 30.26%  |
| WDC                 | 22       | 30     | 28.95%  |
| Hitachi             | 12       | 16     | 15.79%  |
| Toshiba             | 5        | 10     | 6.58%   |
| Samsung Electronics | 5        | 8      | 6.58%   |
| HGST                | 5        | 6      | 6.58%   |
| Fujitsu             | 2        | 2      | 2.63%   |
| Magnetic Data       | 1        | 1      | 1.32%   |
| HPE                 | 1        | 2      | 1.32%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 6        | 8      | 20.69%  |
| Intel               | 3        | 3      | 10.34%  |
| Micron Technology   | 2        | 3      | 6.9%    |
| KingFast            | 2        | 2      | 6.9%    |
| Crucial             | 2        | 3      | 6.9%    |
| China               | 2        | 2      | 6.9%    |
| WDC                 | 1        | 1      | 3.45%   |
| TwinMOS             | 1        | 1      | 3.45%   |
| Supersonic          | 1        | 2      | 3.45%   |
| SPCC                | 1        | 2      | 3.45%   |
| PNY                 | 1        | 1      | 3.45%   |
| Mushkin             | 1        | 1      | 3.45%   |
| LITEON              | 1        | 1      | 3.45%   |
| Lexar               | 1        | 1      | 3.45%   |
| Kingston            | 1        | 2      | 3.45%   |
| HS-SSD-E100         | 1        | 1      | 3.45%   |
| AFOX                | 1        | 1      | 3.45%   |
| Unknown             | 1        | 1      | 3.45%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 62       | 107    | 64.58%  |
| SSD  | 25       | 36     | 26.04%  |
| NVMe | 9        | 11     | 9.38%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 72       | 141    | 87.8%   |
| NVMe | 9        | 11     | 10.98%  |
| SAS  | 1        | 2      | 1.22%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 58       | 95     | 66.67%  |
| 0.51-1.0   | 17       | 30     | 19.54%  |
| 1.01-2.0   | 8        | 13     | 9.2%    |
| 2.01-3.0   | 2        | 3      | 2.3%    |
| 3.01-4.0   | 1        | 1      | 1.15%   |
| 4.01-10.0  | 1        | 1      | 1.15%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 23       | 29.87%  |
| 251-500        | 15       | 19.48%  |
| 1-20           | 12       | 15.58%  |
| 51-100         | 6        | 7.79%   |
| 501-1000       | 5        | 6.49%   |
| More than 3000 | 4        | 5.19%   |
| 21-50          | 4        | 5.19%   |
| 1001-2000      | 4        | 5.19%   |
| Unknown        | 3        | 3.9%    |
| 2001-3000      | 1        | 1.3%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 36       | 45%     |
| 21-50          | 11       | 13.75%  |
| 51-100         | 10       | 12.5%   |
| 251-500        | 6        | 7.5%    |
| 101-250        | 6        | 7.5%    |
| 1001-2000      | 3        | 3.75%   |
| Unknown        | 3        | 3.75%   |
| More than 3000 | 2        | 2.5%    |
| 501-1000       | 2        | 2.5%    |
| 2001-3000      | 1        | 1.25%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB  | 3        | 3      | 16.67%  |
| Hitachi HDS721680PLA380 80GB     | 2        | 3      | 11.11%  |
| WDC WD800AAJS-60WAA0 80GB        | 1        | 1      | 5.56%   |
| WDC WD2500AAJS-60Z0A0 250GB      | 1        | 1      | 5.56%   |
| WDC WD1200BEVS-60UST0 120GB      | 1        | 1      | 5.56%   |
| Seagate ST500LM021-1KJ152 500GB  | 1        | 1      | 5.56%   |
| Seagate ST340016A 40GB           | 1        | 1      | 5.56%   |
| Seagate ST340014AS 40GB          | 1        | 1      | 5.56%   |
| Seagate ST3250312AS 250GB        | 1        | 1      | 5.56%   |
| Seagate ST3160318AS 160GB        | 1        | 1      | 5.56%   |
| Samsung Electronics HD080HJ 80GB | 1        | 1      | 5.56%   |
| Kingston SA400S37480G 480GB SSD  | 1        | 2      | 5.56%   |
| HPE MM1000GBKAL 1TB              | 1        | 2      | 5.56%   |
| HGST HTS545032A7E660 320GB       | 1        | 1      | 5.56%   |
| Fujitsu MHX2300BT 304GB          | 1        | 1      | 5.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 8        | 8      | 44.44%  |
| WDC                 | 3        | 3      | 16.67%  |
| Hitachi             | 2        | 3      | 11.11%  |
| Samsung Electronics | 1        | 1      | 5.56%   |
| Kingston            | 1        | 2      | 5.56%   |
| HPE                 | 1        | 2      | 5.56%   |
| HGST                | 1        | 1      | 5.56%   |
| Fujitsu             | 1        | 1      | 5.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 8        | 8      | 47.06%  |
| WDC                 | 3        | 3      | 17.65%  |
| Hitachi             | 2        | 3      | 11.76%  |
| Samsung Electronics | 1        | 1      | 5.88%   |
| HPE                 | 1        | 2      | 5.88%   |
| HGST                | 1        | 1      | 5.88%   |
| Fujitsu             | 1        | 1      | 5.88%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 16       | 19     | 94.12%  |
| SSD  | 1        | 2      | 5.88%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                   | Desktops | Drives | Percent |
|-------------------------|----------|--------|---------|
| WDC WD800JD-00LSA0 80GB | 2        | 3      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Desktops | Drives | Percent |
|--------|----------|--------|---------|
| WDC    | 2        | 3      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 38       | 76     | 44.19%  |
| Works    | 29       | 54     | 33.72%  |
| Malfunc  | 17       | 21     | 19.77%  |
| Failed   | 2        | 3      | 2.33%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 62       | 72.09%  |
| AMD                              | 9        | 10.47%  |
| Samsung Electronics              | 5        | 5.81%   |
| Nvidia                           | 2        | 2.33%   |
| Silicon Integrated Systems [SiS] | 1        | 1.16%   |
| SanDisk                          | 1        | 1.16%   |
| Realtek Semiconductor            | 1        | 1.16%   |
| Phison Electronics               | 1        | 1.16%   |
| LSI Logic / Symbios Logic        | 1        | 1.16%   |
| JMicron Technology               | 1        | 1.16%   |
| Broadcom / LSI                   | 1        | 1.16%   |
| ADATA Technology                 | 1        | 1.16%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 12       | 10.08%  |
| Intel SATA Controller [RAID mode]                                                       | 7        | 5.88%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 7        | 5.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 6        | 5.04%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4        | 3.36%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4        | 3.36%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4        | 3.36%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4        | 3.36%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 4        | 3.36%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 4        | 3.36%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 3        | 2.52%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 3        | 2.52%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 3        | 2.52%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 3        | 2.52%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2        | 1.68%   |
| Nvidia MCP61 SATA Controller                                                            | 2        | 1.68%   |
| Nvidia MCP61 IDE                                                                        | 2        | 1.68%   |
| Intel C610/X99 series chipset IDE-r Controller                                          | 2        | 1.68%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 2        | 1.68%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 2        | 1.68%   |
| AMD 400 Series Chipset SATA Controller                                                  | 2        | 1.68%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                    | 1        | 0.84%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                                   | 1        | 0.84%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 1        | 0.84%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                                       | 1        | 0.84%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 0.84%   |
| LSI Logic / Symbios Logic SAS1068E PCI-Express Fusion-MPT SAS                           | 1        | 0.84%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 1        | 0.84%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 1        | 0.84%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 1        | 0.84%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1        | 0.84%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 1        | 0.84%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1        | 0.84%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 1        | 0.84%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1        | 0.84%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1        | 0.84%   |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                              | 1        | 0.84%   |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                              | 1        | 0.84%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 1        | 0.84%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 1        | 0.84%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 49       | 50%     |
| IDE  | 26       | 26.53%  |
| RAID | 10       | 10.2%   |
| NVMe | 9        | 9.18%   |
| SAS  | 3        | 3.06%   |
| SCSI | 1        | 1.02%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 62       | 83.78%  |
| AMD    | 12       | 16.22%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz            | 6        | 8.11%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 4        | 5.41%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 3        | 4.05%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz         | 2        | 2.7%    |
| Intel Xeon CPU E5-2620 0 @ 2.00GHz          | 2        | 2.7%    |
| Intel Core i7-7700 CPU @ 3.60GHz            | 2        | 2.7%    |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2        | 2.7%    |
| Intel Core i5-4570 CPU @ 3.20GHz            | 2        | 2.7%    |
| Intel Core i5-3570 CPU @ 3.40GHz            | 2        | 2.7%    |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2        | 2.7%    |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2        | 2.7%    |
| AMD Ryzen 5 3600 6-Core Processor           | 2        | 2.7%    |
| Intel Xeon CPU W3540 @ 2.93GHz              | 1        | 1.35%   |
| Intel Xeon CPU E5640 @ 2.67GHz              | 1        | 1.35%   |
| Intel Xeon CPU E5-1620 0 @ 3.60GHz          | 1        | 1.35%   |
| Intel Xeon CPU E3-1240 v6 @ 3.70GHz         | 1        | 1.35%   |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz         | 1        | 1.35%   |
| Intel Xeon CPU 5140 @ 2.33GHz               | 1        | 1.35%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1        | 1.35%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1        | 1.35%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1        | 1.35%   |
| Intel Pentium CPU G3220T @ 2.60GHz          | 1        | 1.35%   |
| Intel Pentium 4 CPU 2.80GHz                 | 1        | 1.35%   |
| Intel Core i9-9920X CPU @ 3.50GHz           | 1        | 1.35%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1        | 1.35%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1        | 1.35%   |
| Intel Core i7-4771 CPU @ 3.50GHz            | 1        | 1.35%   |
| Intel Core i5-4670 CPU @ 3.40GHz            | 1        | 1.35%   |
| Intel Core i5-4590S CPU @ 3.00GHz           | 1        | 1.35%   |
| Intel Core i5-3470S CPU @ 2.90GHz           | 1        | 1.35%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 1        | 1.35%   |
| Intel Core i5-2400S CPU @ 2.50GHz           | 1        | 1.35%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 1        | 1.35%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 1        | 1.35%   |
| Intel Core i3-6100T CPU @ 3.20GHz           | 1        | 1.35%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 1        | 1.35%   |
| Intel Core i3-4150 CPU @ 3.50GHz            | 1        | 1.35%   |
| Intel Core i3-4130T CPU @ 2.90GHz           | 1        | 1.35%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 1        | 1.35%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 1        | 1.35%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 24       | 32.43%  |
| Intel Xeon              | 10       | 13.51%  |
| Intel Core i3           | 8        | 10.81%  |
| Intel Core i7           | 7        | 9.46%   |
| Intel Core 2 Duo        | 4        | 5.41%   |
| AMD Ryzen 5             | 3        | 4.05%   |
| Intel Pentium Dual-Core | 2        | 2.7%    |
| AMD Ryzen 9             | 2        | 2.7%    |
| AMD Athlon 64 X2        | 2        | 2.7%    |
| Other                   | 1        | 1.35%   |
| Intel Pentium Dual      | 1        | 1.35%   |
| Intel Pentium 4         | 1        | 1.35%   |
| Intel Pentium           | 1        | 1.35%   |
| Intel Core i9           | 1        | 1.35%   |
| Intel Core 2 Quad       | 1        | 1.35%   |
| Intel Core 2            | 1        | 1.35%   |
| AMD Ryzen 7             | 1        | 1.35%   |
| AMD Ryzen 3             | 1        | 1.35%   |
| AMD Phenom II X6        | 1        | 1.35%   |
| AMD E                   | 1        | 1.35%   |
| AMD Athlon XP           | 1        | 1.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 36       | 48.65%  |
| 2      | 22       | 29.73%  |
| 6      | 5        | 6.76%   |
| 12     | 4        | 5.41%   |
| 16     | 3        | 4.05%   |
| 8      | 2        | 2.7%    |
| 1      | 2        | 2.7%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 69       | 93.24%  |
| 2      | 5        | 6.76%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 43       | 58.11%  |
| 2      | 31       | 41.89%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 72       | 97.3%   |
| 32-bit         | 2        | 2.7%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 20       | 26.67%  |
| 0x306c3    | 10       | 13.33%  |
| 0x306a9    | 8        | 10.67%  |
| 0x206a7    | 8        | 10.67%  |
| 0x6fb      | 3        | 4%      |
| 0x506e3    | 3        | 4%      |
| 0x206d7    | 3        | 4%      |
| 0x1067a    | 3        | 4%      |
| 0x08701021 | 3        | 4%      |
| 0x906e9    | 2        | 2.67%   |
| 0xf29      | 1        | 1.33%   |
| 0x90675    | 1        | 1.33%   |
| 0x6fd      | 1        | 1.33%   |
| 0x50654    | 1        | 1.33%   |
| 0x306f2    | 1        | 1.33%   |
| 0x106e5    | 1        | 1.33%   |
| 0x10676    | 1        | 1.33%   |
| 0x0a201016 | 1        | 1.33%   |
| 0x08701030 | 1        | 1.33%   |
| 0x08108102 | 1        | 1.33%   |
| 0x05000119 | 1        | 1.33%   |
| 0x010000dc | 1        | 1.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 17       | 22.97%  |
| SandyBridge      | 11       | 14.86%  |
| IvyBridge        | 10       | 13.51%  |
| Skylake          | 5        | 6.76%   |
| Penryn           | 5        | 6.76%   |
| Core             | 5        | 6.76%   |
| Zen 2            | 4        | 5.41%   |
| KabyLake         | 3        | 4.05%   |
| Zen 3            | 2        | 2.7%    |
| Westmere         | 2        | 2.7%    |
| Nehalem          | 2        | 2.7%    |
| K8 Hammer        | 2        | 2.7%    |
| Zen+             | 1        | 1.35%   |
| NetBurst         | 1        | 1.35%   |
| K6               | 1        | 1.35%   |
| K10              | 1        | 1.35%   |
| Bobcat           | 1        | 1.35%   |
| Alderlake Hybrid | 1        | 1.35%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 42       | 55.26%  |
| Nvidia                           | 22       | 28.95%  |
| AMD                              | 11       | 14.47%  |
| Silicon Integrated Systems [SiS] | 1        | 1.32%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                      | Desktops | Percent |
|--------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller                | 12       | 15.38%  |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                  | 7        | 8.97%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                           | 5        | 6.41%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                      | 5        | 6.41%   |
| Intel HD Graphics 530                                                                      | 4        | 5.13%   |
| Nvidia GT218 [GeForce 210]                                                                 | 3        | 3.85%   |
| Nvidia GM107GL [Quadro K2200]                                                              | 3        | 3.85%   |
| Nvidia GK208B [GeForce GT 710]                                                             | 3        | 3.85%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                      | 2        | 2.56%   |
| Nvidia GM204GL [Quadro M4000]                                                              | 2        | 2.56%   |
| Nvidia GF119 [GeForce GT 610]                                                              | 2        | 2.56%   |
| Intel HD Graphics 630                                                                      | 2        | 2.56%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                  | 2        | 2.56%   |
| Silicon Integrated Systems [SiS] 661/741/760 PCI/AGP or 662/761Gx PCIE VGA Display Adapter | 1        | 1.28%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                         | 1        | 1.28%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                        | 1        | 1.28%   |
| Nvidia GK107GL [Quadro K420]                                                               | 1        | 1.28%   |
| Nvidia GK107GL [Quadro K2000]                                                              | 1        | 1.28%   |
| Nvidia GF119 [NVS 310]                                                                     | 1        | 1.28%   |
| Nvidia GA104 [GeForce RTX 3070 Lite Hash Rate]                                             | 1        | 1.28%   |
| Nvidia G72 [GeForce 7500 LE]                                                               | 1        | 1.28%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                     | 1        | 1.28%   |
| Intel Core Processor Integrated Graphics Controller                                        | 1        | 1.28%   |
| Intel Alder Lake-S GT1 [UHD Graphics 770]                                                  | 1        | 1.28%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                                           | 1        | 1.28%   |
| Intel 82Q35 Express Integrated Graphics Controller                                         | 1        | 1.28%   |
| Intel 82865G Integrated Graphics Controller                                                | 1        | 1.28%   |
| AMD Wrestler [Radeon HD 6320]                                                              | 1        | 1.28%   |
| AMD RV610 [Radeon HD 2400 PRO]                                                             | 1        | 1.28%   |
| AMD RV610 [Radeon HD 2350]                                                                 | 1        | 1.28%   |
| AMD RV380 [Radeon X300/X550/X1050 Series] (Secondary)                                      | 1        | 1.28%   |
| AMD RV370 [Radeon X600/X600 SE]                                                            | 1        | 1.28%   |
| AMD Redwood PRO [Radeon HD 5550/5570/5630/6510/6610/7570]                                  | 1        | 1.28%   |
| AMD Redwood PRO GL [FirePro V3800]                                                         | 1        | 1.28%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                       | 1        | 1.28%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                      | 1        | 1.28%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                    | 1        | 1.28%   |
| AMD Hawaii XT / Grenada XT [Radeon R9 290X/390X]                                           | 1        | 1.28%   |
| AMD Barts XT [Radeon HD 6870]                                                              | 1        | 1.28%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Intel  | 39       | 52.7%   |
| 1 x Nvidia | 21       | 28.38%  |
| 1 x AMD    | 10       | 13.51%  |
| 2 x Nvidia | 1        | 1.35%   |
| 2 x Intel  | 1        | 1.35%   |
| 2 x AMD    | 1        | 1.35%   |
| 1 x SiS    | 1        | 1.35%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 63       | 85.14%  |
| Proprietary | 10       | 13.51%  |
| Unknown     | 1        | 1.35%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 42       | 55.26%  |
| 1.01-2.0   | 9        | 11.84%  |
| 0.01-0.5   | 9        | 11.84%  |
| 0.51-1.0   | 7        | 9.21%   |
| 3.01-4.0   | 6        | 7.89%   |
| 7.01-8.0   | 3        | 3.95%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 13       | 20%     |
| Dell                 | 13       | 20%     |
| Hewlett-Packard      | 12       | 18.46%  |
| Goldstar             | 5        | 7.69%   |
| Iiyama               | 3        | 4.62%   |
| BenQ                 | 3        | 4.62%   |
| Acer                 | 3        | 4.62%   |
| Philips              | 2        | 3.08%   |
| Fujitsu Siemens      | 2        | 3.08%   |
| Ancor Communications | 2        | 3.08%   |
| RTK                  | 1        | 1.54%   |
| NEC Computers        | 1        | 1.54%   |
| MSI                  | 1        | 1.54%   |
| MiTAC                | 1        | 1.54%   |
| Medion               | 1        | 1.54%   |
| Lenovo               | 1        | 1.54%   |
| Unknown              | 1        | 1.54%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Dell E2414H DEL4090 1920x1080 531x299mm 24.0-inch                       | 3        | 4.55%   |
| Hewlett-Packard 25x HPN357E 1920x1080 544x303mm 24.5-inch               | 2        | 3.03%   |
| Dell E198FP DELA028 1280x1024 380x305mm 19.2-inch                       | 2        | 3.03%   |
| Samsung Electronics SyncMaster SAM0372 1680x1050 459x296mm 21.5-inch    | 1        | 1.52%   |
| Samsung Electronics SyncMaster SAM027E 1680x1050 474x296mm 22.0-inch    | 1        | 1.52%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 340x270mm 17.1-inch    | 1        | 1.52%   |
| Samsung Electronics SyncMaster SAM0161 1280x1024 338x270mm 17.0-inch    | 1        | 1.52%   |
| Samsung Electronics SMBX2440 SAM068A 1920x1080 531x299mm 24.0-inch      | 1        | 1.52%   |
| Samsung Electronics SMBX2250 SAM071B 1920x1080 477x268mm 21.5-inch      | 1        | 1.52%   |
| Samsung Electronics S24C350 SAM0A3A 1920x1080 531x299mm 24.0-inch       | 1        | 1.52%   |
| Samsung Electronics S23B550 SAM0919 1920x1080 510x290mm 23.1-inch       | 1        | 1.52%   |
| Samsung Electronics S22F350 SAM0D1B 1920x1080 477x268mm 21.5-inch       | 1        | 1.52%   |
| Samsung Electronics LCD Monitor SAM71B5 3840x2160 1872x1053mm 84.6-inch | 1        | 1.52%   |
| Samsung Electronics LCD Monitor SAM0F39 1920x1080 1210x680mm 54.6-inch  | 1        | 1.52%   |
| Samsung Electronics LCD Monitor SAM0B7C 1920x1080 886x498mm 40.0-inch   | 1        | 1.52%   |
| Samsung Electronics LCD Monitor SAM0B2A 1280x720 949x543mm 43.0-inch    | 1        | 1.52%   |
| RTK Verbatim M14 RTK0001 1920x1080 300x190mm 14.0-inch                  | 1        | 1.52%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                 | 1        | 1.52%   |
| Philips 170S PHL081E 1280x1024 338x270mm 17.0-inch                      | 1        | 1.52%   |
| NEC Computers LCD224WM NEC6733 1680x1050 474x296mm 22.0-inch            | 1        | 1.52%   |
| MSI G24C4 MSI3BA0 1920x1080 521x293mm 23.5-inch                         | 1        | 1.52%   |
| MiTAC TV MTC9527 1366x768 1150x650mm 52.0-inch                          | 1        | 1.52%   |
| Medion MD 20172 MED3628 1680x1050 474x296mm 22.0-inch                   | 1        | 1.52%   |
| Lenovo T24i-10 LEN61A6 1920x1080 527x296mm 23.8-inch                    | 1        | 1.52%   |
| Iiyama PLE2483H IVM6113 1920x1080 531x299mm 24.0-inch                   | 1        | 1.52%   |
| Iiyama PLB2712HDS IVM6602 1920x1080 598x336mm 27.0-inch                 | 1        | 1.52%   |
| Iiyama PL2280W IVM561F 1680x1050 474x296mm 22.0-inch                    | 1        | 1.52%   |
| Hewlett-Packard ZR22w HWP2867 1920x1080 475x267mm 21.5-inch             | 1        | 1.52%   |
| Hewlett-Packard W2072a HWP3000 1600x900 443x249mm 20.0-inch             | 1        | 1.52%   |
| Hewlett-Packard w1907 HWP26A2 1440x900 408x255mm 18.9-inch              | 1        | 1.52%   |
| Hewlett-Packard V213a HPN335B 1920x1080 458x258mm 20.7-inch             | 1        | 1.52%   |
| Hewlett-Packard LE1901w HWP2842 1440x900 410x256mm 19.0-inch            | 1        | 1.52%   |
| Hewlett-Packard LCD Monitor HWP4101 1920x1080 470x270mm 21.3-inch       | 1        | 1.52%   |
| Hewlett-Packard LCD Monitor E232 1920x1080                              | 1        | 1.52%   |
| Hewlett-Packard LA2006 HWP2943 1600x900 443x249mm 20.0-inch             | 1        | 1.52%   |
| Hewlett-Packard LA1956x HWP3022 1280x1024 376x301mm 19.0-inch           | 1        | 1.52%   |
| Hewlett-Packard E242 HWP326E 1920x1200 518x324mm 24.1-inch              | 1        | 1.52%   |
| Goldstar W1942 GSM4B70 1440x900 408x255mm 18.9-inch                     | 1        | 1.52%   |
| Goldstar W1934 GSM4B7A 1440x900 410x256mm 19.0-inch                     | 1        | 1.52%   |
| Goldstar M2394D GSM56C4 1920x1080 509x286mm 23.0-inch                   | 1        | 1.52%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 29       | 45.31%  |
| 1280x1024 (SXGA)   | 8        | 12.5%   |
| 1680x1050 (WSXGA+) | 7        | 10.94%  |
| 3840x2160 (4K)     | 6        | 9.38%   |
| 1440x900 (WXGA+)   | 6        | 9.38%   |
| 1600x900 (HD+)     | 3        | 4.69%   |
| 2560x1440 (QHD)    | 1        | 1.56%   |
| 1920x1200 (WUXGA)  | 1        | 1.56%   |
| 1366x768 (WXGA)    | 1        | 1.56%   |
| 1280x720 (HD)      | 1        | 1.56%   |
| 1152x864           | 1        | 1.56%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 15       | 22.73%  |
| 19      | 9        | 13.64%  |
| 27      | 6        | 9.09%   |
| 22      | 6        | 9.09%   |
| 23      | 5        | 7.58%   |
| 21      | 5        | 7.58%   |
| 17      | 5        | 7.58%   |
| 20      | 3        | 4.55%   |
| Unknown | 3        | 4.55%   |
| 84      | 1        | 1.52%   |
| 72      | 1        | 1.52%   |
| 58      | 1        | 1.52%   |
| 54      | 1        | 1.52%   |
| 52      | 1        | 1.52%   |
| 43      | 1        | 1.52%   |
| 18      | 1        | 1.52%   |
| 15      | 1        | 1.52%   |
| 14      | 1        | 1.52%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 23       | 35.38%  |
| 401-500     | 21       | 32.31%  |
| 301-350     | 6        | 9.23%   |
| 351-400     | 3        | 4.62%   |
| 1001-1500   | 3        | 4.62%   |
| Unknown     | 3        | 4.62%   |
| 601-700     | 2        | 3.08%   |
| 1501-2000   | 2        | 3.08%   |
| 201-300     | 1        | 1.54%   |
| 901-1000    | 1        | 1.54%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 37       | 57.81%  |
| 16/10   | 15       | 23.44%  |
| 5/4     | 8        | 12.5%   |
| Unknown | 3        | 4.69%   |
| 4/3     | 1        | 1.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 25       | 38.46%  |
| 151-200        | 14       | 21.54%  |
| 301-350        | 6        | 9.23%   |
| More than 1000 | 5        | 7.69%   |
| 141-150        | 5        | 7.69%   |
| 251-300        | 4        | 6.15%   |
| Unknown        | 3        | 4.62%   |
| 101-110        | 2        | 3.08%   |
| 501-1000       | 1        | 1.54%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 46       | 71.88%  |
| 101-120 | 6        | 9.38%   |
| 1-50    | 5        | 7.81%   |
| 161-240 | 3        | 4.69%   |
| Unknown | 3        | 4.69%   |
| 121-160 | 1        | 1.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 69       | 92%     |
| 2     | 3        | 4%      |
| 0     | 3        | 4%      |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 50       | 42.37%  |
| Realtek Semiconductor            | 24       | 20.34%  |
| Ralink Technology                | 14       | 11.86%  |
| Ralink                           | 6        | 5.08%   |
| Broadcom                         | 5        | 4.24%   |
| TP-Link                          | 4        | 3.39%   |
| Qualcomm Atheros                 | 4        | 3.39%   |
| Nvidia                           | 2        | 1.69%   |
| D-Link System                    | 2        | 1.69%   |
| Silicon Integrated Systems [SiS] | 1        | 0.85%   |
| Qualcomm Atheros Communications  | 1        | 0.85%   |
| Marvell Technology Group         | 1        | 0.85%   |
| Huawei Technologies              | 1        | 0.85%   |
| Gemtek                           | 1        | 0.85%   |
| Broadcom Limited                 | 1        | 0.85%   |
| Aquantia                         | 1        | 0.85%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 16       | 12.21%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 14       | 10.69%  |
| Intel Ethernet Connection I217-LM                                              | 13       | 9.92%   |
| Ralink RT5370 Wireless Adapter                                                 | 8        | 6.11%   |
| Ralink MT7601U Wireless Adapter                                                | 5        | 3.82%   |
| Intel Ethernet Connection (2) I219-LM                                          | 5        | 3.82%   |
| Intel Wi-Fi 6 AX200                                                            | 4        | 3.05%   |
| Intel I211 Gigabit Network Connection                                          | 4        | 3.05%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 4        | 3.05%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                   | 3        | 2.29%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                      | 3        | 2.29%   |
| Intel 82574L Gigabit Network Connection                                        | 3        | 2.29%   |
| Intel 82566DM-2 Gigabit Network Connection                                     | 3        | 2.29%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                     | 2        | 1.53%   |
| Ralink RT2870/RT3070 Wireless Adapter                                          | 2        | 1.53%   |
| Nvidia MCP61 Ethernet                                                          | 2        | 1.53%   |
| Intel I210 Gigabit Network Connection                                          | 2        | 1.53%   |
| TP-Link Archer T4U ver.3                                                       | 1        | 0.76%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet                      | 1        | 0.76%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                             | 1        | 0.76%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 1        | 0.76%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                            | 1        | 0.76%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                         | 1        | 0.76%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                          | 1        | 0.76%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 1        | 0.76%   |
| Realtek RTL8187 Wireless Adapter                                               | 1        | 0.76%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1        | 0.76%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 1        | 0.76%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1        | 0.76%   |
| Realtek 802.11ac NIC                                                           | 1        | 0.76%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                         | 1        | 0.76%   |
| Ralink RT5360 Wireless 802.11n 1T/1R                                           | 1        | 0.76%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                           | 1        | 0.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 1        | 0.76%   |
| Qualcomm Atheros AR9271 802.11n                                                | 1        | 0.76%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 1        | 0.76%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                               | 1        | 0.76%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1        | 0.76%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1        | 0.76%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                         | 1        | 0.76%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Ralink Technology               | 14       | 31.11%  |
| Realtek Semiconductor           | 9        | 20%     |
| Ralink                          | 6        | 13.33%  |
| Intel                           | 5        | 11.11%  |
| TP-Link                         | 4        | 8.89%   |
| Qualcomm Atheros                | 3        | 6.67%   |
| Qualcomm Atheros Communications | 1        | 2.22%   |
| Gemtek                          | 1        | 2.22%   |
| D-Link System                   | 1        | 2.22%   |
| Broadcom                        | 1        | 2.22%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Ralink RT5370 Wireless Adapter                                       | 8        | 17.02%  |
| Ralink MT7601U Wireless Adapter                                      | 5        | 10.64%  |
| Intel Wi-Fi 6 AX200                                                  | 4        | 8.51%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 3        | 6.38%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                            | 3        | 6.38%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                           | 2        | 4.26%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 2        | 4.26%   |
| TP-Link Archer T4U ver.3                                             | 1        | 2.13%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 1        | 2.13%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 1        | 2.13%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                  | 1        | 2.13%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                               | 1        | 2.13%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 1        | 2.13%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 1        | 2.13%   |
| Realtek RTL8187 Wireless Adapter                                     | 1        | 2.13%   |
| Realtek 802.11ac NIC                                                 | 1        | 2.13%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter               | 1        | 2.13%   |
| Ralink RT5360 Wireless 802.11n 1T/1R                                 | 1        | 2.13%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                 | 1        | 2.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 1        | 2.13%   |
| Qualcomm Atheros AR9271 802.11n                                      | 1        | 2.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 1        | 2.13%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 1        | 2.13%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 1        | 2.13%   |
| Gemtek WUBR-177G [Ralink RT2571W]                                    | 1        | 2.13%   |
| D-Link System DWA-140 RangeBooster N Adapter(rev.B1) [Ralink RT2870] | 1        | 2.13%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 1        | 2.13%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 49       | 62.03%  |
| Realtek Semiconductor            | 17       | 21.52%  |
| Broadcom                         | 4        | 5.06%   |
| Nvidia                           | 2        | 2.53%   |
| Silicon Integrated Systems [SiS] | 1        | 1.27%   |
| Qualcomm Atheros                 | 1        | 1.27%   |
| Marvell Technology Group         | 1        | 1.27%   |
| Huawei Technologies              | 1        | 1.27%   |
| D-Link System                    | 1        | 1.27%   |
| Broadcom Limited                 | 1        | 1.27%   |
| Aquantia                         | 1        | 1.27%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 16       | 19.05%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 14       | 16.67%  |
| Intel Ethernet Connection I217-LM                                              | 13       | 15.48%  |
| Intel Ethernet Connection (2) I219-LM                                          | 5        | 5.95%   |
| Intel I211 Gigabit Network Connection                                          | 4        | 4.76%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 4        | 4.76%   |
| Intel 82574L Gigabit Network Connection                                        | 3        | 3.57%   |
| Intel 82566DM-2 Gigabit Network Connection                                     | 3        | 3.57%   |
| Nvidia MCP61 Ethernet                                                          | 2        | 2.38%   |
| Intel I210 Gigabit Network Connection                                          | 2        | 2.38%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet                      | 1        | 1.19%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1        | 1.19%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 1        | 1.19%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1        | 1.19%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1        | 1.19%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1        | 1.19%   |
| Intel Ethernet Connection I217-V                                               | 1        | 1.19%   |
| Intel Ethernet Connection (2) I219-V                                           | 1        | 1.19%   |
| Intel Ethernet Connection (2) I218-LM                                          | 1        | 1.19%   |
| Intel 82578DM Gigabit Network Connection                                       | 1        | 1.19%   |
| Huawei MAR-LX1M                                                                | 1        | 1.19%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                                | 1        | 1.19%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 1        | 1.19%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 1        | 1.19%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                        | 1        | 1.19%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                        | 1        | 1.19%   |
| Broadcom Limited NetXtreme BCM5782 Gigabit Ethernet                            | 1        | 1.19%   |
| Aquantia AQC111 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]              | 1        | 1.19%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 74       | 63.25%  |
| WiFi     | 43       | 36.75%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 49       | 62.82%  |
| WiFi     | 29       | 37.18%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 53       | 71.62%  |
| 2     | 16       | 21.62%  |
| 3     | 5        | 6.76%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 74       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 5        | 27.78%  |
| Intel                           | 4        | 22.22%  |
| Broadcom                        | 3        | 16.67%  |
| Realtek Semiconductor           | 2        | 11.11%  |
| Qualcomm Atheros Communications | 2        | 11.11%  |
| Toshiba                         | 1        | 5.56%   |
| ASUSTek Computer                | 1        | 5.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 5        | 27.78%  |
| Intel AX200 Bluetooth                               | 4        | 22.22%  |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2        | 11.11%  |
| Toshiba Atheros AR3012 Bluetooth                    | 1        | 5.56%   |
| Realtek Bluetooth Radio                             | 1        | 5.56%   |
| Realtek 802.11ac WLAN Adapter                       | 1        | 5.56%   |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 5.56%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1        | 5.56%   |
| Broadcom HP Portable Valentine                      | 1        | 5.56%   |
| ASUS 2045 Bluetooth 2.0 Device with trace filter    | 1        | 5.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 62       | 59.05%  |
| Nvidia                           | 22       | 20.95%  |
| AMD                              | 13       | 12.38%  |
| Silicon Integrated Systems [SiS] | 1        | 0.95%   |
| Medeli Electronics               | 1        | 0.95%   |
| Kingston Technology              | 1        | 0.95%   |
| Hewlett-Packard                  | 1        | 0.95%   |
| GN Netcom                        | 1        | 0.95%   |
| GEMBIRD                          | 1        | 0.95%   |
| EDFIER                           | 1        | 0.95%   |
| C-Media Electronics              | 1        | 0.95%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 14       | 11.29%  |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 13       | 10.48%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 10       | 8.06%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8        | 6.45%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 6        | 4.84%   |
| AMD Starship/Matisse HD Audio Controller                                   | 5        | 4.03%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 4        | 3.23%   |
| Nvidia High Definition Audio Controller                                    | 3        | 2.42%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3        | 2.42%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3        | 2.42%   |
| Nvidia GF119 HDMI Audio Controller                                         | 3        | 2.42%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 3        | 2.42%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 3        | 2.42%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3        | 2.42%   |
| Nvidia TU116 High Definition Audio Controller                              | 2        | 1.61%   |
| Nvidia MCP61 High Definition Audio                                         | 2        | 1.61%   |
| Nvidia GM204 High Definition Audio Controller                              | 2        | 1.61%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2        | 1.61%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 2        | 1.61%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2        | 1.61%   |
| Intel 200 Series PCH HD Audio                                              | 2        | 1.61%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2        | 1.61%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 2        | 1.61%   |
| AMD Family 17h/19h HD Audio Controller                                     | 2        | 1.61%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller            | 1        | 0.81%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 0.81%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 0.81%   |
| Nvidia GA104 High Definition Audio Controller                              | 1        | 0.81%   |
| Medeli Electronics USB Audio Device                                        | 1        | 0.81%   |
| Kingston Technology HyperX 7.1 Audio                                       | 1        | 0.81%   |
| Intel Alder Lake-S HD Audio Controller                                     | 1        | 0.81%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 1        | 0.81%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1        | 0.81%   |
| Intel 82801EB/ER (ICH5/ICH5R) AC'97 Audio Controller                       | 1        | 0.81%   |
| Intel 631xESB/632xESB High Definition Audio Controller                     | 1        | 0.81%   |
| Hewlett-Packard Digital Stereo Headset                                     | 1        | 0.81%   |
| GN Netcom Jabra EVOLVE 20 SE MS                                            | 1        | 0.81%   |
| GEMBIRD USB SkypePhone                                                     | 1        | 0.81%   |
| EDFIER EDIFIER W820NB                                                      | 1        | 0.81%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                              | 1        | 0.81%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 21       | 29.17%  |
| SK hynix            | 20       | 27.78%  |
| Micron Technology   | 9        | 12.5%   |
| Corsair             | 4        | 5.56%   |
| Nanya Technology    | 3        | 4.17%   |
| Kingston            | 3        | 4.17%   |
| Unknown             | 2        | 2.78%   |
| Wilk                | 1        | 1.39%   |
| Unknown             | 1        | 1.39%   |
| TakeMS              | 1        | 1.39%   |
| Sesame              | 1        | 1.39%   |
| Qimonda             | 1        | 1.39%   |
| G.Skill             | 1        | 1.39%   |
| Elpida              | 1        | 1.39%   |
| Crucial             | 1        | 1.39%   |
| Avant               | 1        | 1.39%   |
| Apacer              | 1        | 1.39%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s   | 4        | 5%      |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s    | 3        | 3.75%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s    | 3        | 3.75%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s   | 2        | 2.5%    |
| Samsung RAM Module 4GB DIMM DDR3 1333MT/s              | 2        | 2.5%    |
| Unknown                                                | 2        | 2.5%    |
| Wilk RAM Module 16GB DIMM DDR4 2667MT/s                | 1        | 1.25%   |
| Unknown RAM Module 2GB DIMM                            | 1        | 1.25%   |
| TakeMS RAM TMS2GB264C081-665U 2048MB DIMM DDR2 667MT/s | 1        | 1.25%   |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s             | 1        | 1.25%   |
| SK hynix RAM HYMP512U64CP8-Y5 1GB DIMM                 | 1        | 1.25%   |
| SK hynix RAM HYMP164U64CP6-Y5 512MB DIMM DDR2 667MT/s  | 1        | 1.25%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s   | 1        | 1.25%   |
| SK hynix RAM HMT451U6AFR8A-PB 4GB DIMM DDR3 1600MT/s   | 1        | 1.25%   |
| SK hynix RAM HMT425U6AFR6C-PB 2GB DIMM DDR3 1600MT/s   | 1        | 1.25%   |
| SK hynix RAM HMT41GU7MFR8A-H9 8GB DIMM DDR3 1333MT/s   | 1        | 1.25%   |
| SK hynix RAM HMT41GU7AFR8A-PB 8GB DIMM DDR3 1600MT/s   | 1        | 1.25%   |
| SK hynix RAM HMT41GU6MFR8C-PB 8GB DIMM DDR3 1600MT/s   | 1        | 1.25%   |
| SK hynix RAM HMT41GR7BFR4A-PB 8GB DIMM DDR3 1600MT/s   | 1        | 1.25%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s   | 1        | 1.25%   |
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1333MT/s   | 1        | 1.25%   |
| SK hynix RAM HMT31GR7CFR4C-PB 8GB DIMM DDR3 1600MT/s   | 1        | 1.25%   |
| SK hynix RAM HMT125U6BFR8C-G7 2GB DIMM DDR3 1067MT/s   | 1        | 1.25%   |
| SK hynix RAM HMT112U6TFR8C-H9 1GB DIMM DDR3 1333MT/s   | 1        | 1.25%   |
| SK hynix RAM HMA851U6AFR6N-UH 4GB DIMM DDR4 2400MT/s   | 1        | 1.25%   |
| SK hynix RAM HMA42GR7AFR4N-TF 16GB DIMM DDR4 2133MT/s  | 1        | 1.25%   |
| Sesame RAM S949A4UUH-ITR 16GB DIMM DDR4 2400MT/s       | 1        | 1.25%   |
| Samsung RAM Module 8192MB DIMM DDR4 2133MT/s           | 1        | 1.25%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s  | 1        | 1.25%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s  | 1        | 1.25%   |
| Samsung RAM M393B1K73DH0-YF8 8GB DIMM DDR3 1066MT/s    | 1        | 1.25%   |
| Samsung RAM M393B1K70DH0-CK0 8192MB DIMM DDR3 1600MT/s | 1        | 1.25%   |
| Samsung RAM M393B1K70CH0-YH9 8GB DIMM 1333MT/s         | 1        | 1.25%   |
| Samsung RAM M393A4K40BB1-CRC 32GB RIMM DDR4 2400MT/s   | 1        | 1.25%   |
| Samsung RAM M393A1G40DB1-CRC 8GB DIMM DDR4 2400MT/s    | 1        | 1.25%   |
| Samsung RAM M391B1G73QH0-YK0 8GB DIMM DDR3 1600MT/s    | 1        | 1.25%   |
| Samsung RAM M378B5773DH0-CK0 2GB DIMM DDR3 1600MT/s    | 1        | 1.25%   |
| Samsung RAM M378B5773CH0-CH9 2048MB DIMM DDR3 1867MT/s | 1        | 1.25%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s    | 1        | 1.25%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s    | 1        | 1.25%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 21       | 42.86%  |
| DDR4    | 14       | 28.57%  |
| SDRAM   | 7        | 14.29%  |
| DDR2    | 5        | 10.2%   |
| DDR     | 1        | 2.04%   |
| Unknown | 1        | 2.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 38       | 90.48%  |
| SODIMM | 3        | 7.14%   |
| RIMM   | 1        | 2.38%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 18       | 33.33%  |
| 8192  | 11       | 20.37%  |
| 2048  | 7        | 12.96%  |
| 1024  | 7        | 12.96%  |
| 16384 | 5        | 9.26%   |
| 32768 | 2        | 3.7%    |
| 512   | 2        | 3.7%    |
| 256   | 1        | 1.85%   |
| 128   | 1        | 1.85%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 16       | 25.81%  |
| 1333    | 8        | 12.9%   |
| 2400    | 4        | 6.45%   |
| 1648    | 4        | 6.45%   |
| 667     | 4        | 6.45%   |
| 3600    | 3        | 4.84%   |
| 2133    | 3        | 4.84%   |
| 2667    | 2        | 3.23%   |
| 800     | 2        | 3.23%   |
| 4000    | 1        | 1.61%   |
| 3400    | 1        | 1.61%   |
| 3266    | 1        | 1.61%   |
| 2666    | 1        | 1.61%   |
| 1867    | 1        | 1.61%   |
| 1866    | 1        | 1.61%   |
| 1800    | 1        | 1.61%   |
| 1639    | 1        | 1.61%   |
| 1334    | 1        | 1.61%   |
| 1331    | 1        | 1.61%   |
| 1067    | 1        | 1.61%   |
| 1066    | 1        | 1.61%   |
| 400     | 1        | 1.61%   |
| 333     | 1        | 1.61%   |
| 266     | 1        | 1.61%   |
| Unknown | 1        | 1.61%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 1        | 50%     |
| Canon           | 1        | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| HP Deskjet 3510 series | 1        | 50%     |
| Canon MB2000 series    | 1        | 50%     |

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


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Logitech            | 2        | 40%     |
| Lite-On Technology  | 1        | 20%     |
| Jieli Technology    | 1        | 20%     |
| Chicony Electronics | 1        | 20%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Logitech Webcam C270            | 1        | 20%     |
| Logitech BRIO 4K Stream Edition | 1        | 20%     |
| Lite-On EasyCamera 5M           | 1        | 20%     |
| Jieli USB PHY 2.0               | 1        | 20%     |
| Chicony HP Webcam               | 1        | 20%     |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

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
| 0     | 63       | 84%     |
| 1     | 11       | 14.67%  |
| 2     | 1        | 1.33%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 5        | 41.67%  |
| Net/wireless             | 4        | 33.33%  |
| Unassigned class         | 2        | 16.67%  |
| Communication controller | 1        | 8.33%   |

