Reborn OS - Tested Hardware & Statistics (Desktops)
---------------------------------------------------

A project to collect tested hardware configurations for Reborn OS.

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

Total: 94

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | 18E7                        | [9f4d303ffa](https://linux-hardware.org/?probe=9f4d303ffa) | Mar 18, 2023 |
| HP            | 8460                        | [078e151afc](https://linux-hardware.org/?probe=078e151afc) | Jan 29, 2023 |
| HP            | 8460                        | [2bfad5b267](https://linux-hardware.org/?probe=2bfad5b267) | Jan 24, 2023 |
| Biostar       | A320MH                      | [3fb3a04230](https://linux-hardware.org/?probe=3fb3a04230) | Jan 14, 2023 |
| HP            | 8460                        | [6089c30228](https://linux-hardware.org/?probe=6089c30228) | Dec 07, 2022 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [d9af542480](https://linux-hardware.org/?probe=d9af542480) | Nov 08, 2022 |
| Pegatron      | 2AD5                        | [0b91ee456b](https://linux-hardware.org/?probe=0b91ee456b) | Nov 02, 2022 |
| Pegatron      | 2AD5                        | [5f90d4e478](https://linux-hardware.org/?probe=5f90d4e478) | Nov 02, 2022 |
| HP            | 8460                        | [d74207aa28](https://linux-hardware.org/?probe=d74207aa28) | Sep 08, 2022 |
| BESSTAR Te... | B550                        | [f4a5cc4ace](https://linux-hardware.org/?probe=f4a5cc4ace) | Sep 04, 2022 |
| Biostar       | A320MH                      | [7580882598](https://linux-hardware.org/?probe=7580882598) | Jul 10, 2022 |
| Gigabyte      | H110M-S2PT-CF               | [506afdf9c7](https://linux-hardware.org/?probe=506afdf9c7) | Mar 09, 2022 |
| Shuttle       | FZ270                       | [ed3e018227](https://linux-hardware.org/?probe=ed3e018227) | Mar 09, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [bc31f5f2bd](https://linux-hardware.org/?probe=bc31f5f2bd) | Jan 17, 2022 |
| ASUSTek       | PRIME H310M-K R2.0          | [7dba1540ad](https://linux-hardware.org/?probe=7dba1540ad) | Dec 06, 2021 |
| Medion        | Cattle24 1M                 | [fd68d44a6a](https://linux-hardware.org/?probe=fd68d44a6a) | Oct 16, 2021 |
| Medion        | Cattle24 1M                 | [dd4a0707ba](https://linux-hardware.org/?probe=dd4a0707ba) | May 19, 2021 |
| Dell          | 0200DY A01                  | [426fc0381c](https://linux-hardware.org/?probe=426fc0381c) | May 08, 2021 |
| ASUSTek       | PRIME Z270-A                | [58fbf7553b](https://linux-hardware.org/?probe=58fbf7553b) | May 03, 2021 |
| ASUSTek       | PRIME Z270-A                | [27595787eb](https://linux-hardware.org/?probe=27595787eb) | Apr 26, 2021 |
| ASUSTek       | PRIME Z270-A                | [ec119e020d](https://linux-hardware.org/?probe=ec119e020d) | Apr 26, 2021 |
| HP            | 3048h                       | [b61eb90220](https://linux-hardware.org/?probe=b61eb90220) | Mar 20, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [0e8f323e0f](https://linux-hardware.org/?probe=0e8f323e0f) | Mar 18, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [a949911df6](https://linux-hardware.org/?probe=a949911df6) | Mar 18, 2021 |
| Gigabyte      | B450 AORUS M                | [4a76fb93d3](https://linux-hardware.org/?probe=4a76fb93d3) | Mar 16, 2021 |
| Gigabyte      | F2A85X-UP4                  | [926ae13f69](https://linux-hardware.org/?probe=926ae13f69) | Mar 09, 2021 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [6c98f8666d](https://linux-hardware.org/?probe=6c98f8666d) | Feb 24, 2021 |
| ASRock        | X570 Taichi                 | [e6476ce804](https://linux-hardware.org/?probe=e6476ce804) | Feb 05, 2021 |
| ASUSTek       | PRIME B450M-A               | [6042185966](https://linux-hardware.org/?probe=6042185966) | Feb 05, 2021 |
| ASUSTek       | PRIME B450M-A               | [8c4549fed4](https://linux-hardware.org/?probe=8c4549fed4) | Feb 05, 2021 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [0bb6c600d0](https://linux-hardware.org/?probe=0bb6c600d0) | Jan 25, 2021 |
| ASUSTek       | Q87M-E                      | [e95dad9e90](https://linux-hardware.org/?probe=e95dad9e90) | Jan 14, 2021 |
| MSI           | MEG X570 ACE                | [5b061048ce](https://linux-hardware.org/?probe=5b061048ce) | Jan 11, 2021 |
| Dell          | 02YYK5 A01                  | [f50fd232e1](https://linux-hardware.org/?probe=f50fd232e1) | Jan 06, 2021 |
| MSI           | A320M PRO-VD/S V2           | [5d05e8d607](https://linux-hardware.org/?probe=5d05e8d607) | Jan 04, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | [ed3e1cc88a](https://linux-hardware.org/?probe=ed3e1cc88a) | Jan 04, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | [fb77017d74](https://linux-hardware.org/?probe=fb77017d74) | Jan 04, 2021 |
| ASUSTek       | P8B75-V                     | [a8ba58ce8d](https://linux-hardware.org/?probe=a8ba58ce8d) | Jan 03, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [60d4c9b8f1](https://linux-hardware.org/?probe=60d4c9b8f1) | Jan 02, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [bab82e261e](https://linux-hardware.org/?probe=bab82e261e) | Jan 02, 2021 |
| ASUSTek       | P7H55-M PRO                 | [253b9e5126](https://linux-hardware.org/?probe=253b9e5126) | Jan 01, 2021 |
| ASUSTek       | P7H55-M PRO                 | [016282f72d](https://linux-hardware.org/?probe=016282f72d) | Jan 01, 2021 |
| Dell          | 084J0R A00                  | [45b5f0850b](https://linux-hardware.org/?probe=45b5f0850b) | Dec 30, 2020 |
| MSI           | FM2-A75MA-E35               | [c537d4854e](https://linux-hardware.org/?probe=c537d4854e) | Dec 14, 2020 |
| MSI           | FM2-A75MA-E35               | [f1f14b545e](https://linux-hardware.org/?probe=f1f14b545e) | Dec 13, 2020 |
| Dell          | 096JG8 A01                  | [d0fc564ec7](https://linux-hardware.org/?probe=d0fc564ec7) | Dec 11, 2020 |
| Dell          | 096JG8 A01                  | [2385d54def](https://linux-hardware.org/?probe=2385d54def) | Dec 09, 2020 |
| OEM           | G41 775 ICH7 8712           | [a135ed4b82](https://linux-hardware.org/?probe=a135ed4b82) | Nov 08, 2020 |
| OEM           | G41 775 ICH7 8712           | [151ca5d99e](https://linux-hardware.org/?probe=151ca5d99e) | Nov 08, 2020 |
| ASRock        | 960GM-VGS3 FX               | [5c51163253](https://linux-hardware.org/?probe=5c51163253) | Nov 05, 2020 |
| Gigabyte      | EP43-UD3L                   | [d6fd55eee0](https://linux-hardware.org/?probe=d6fd55eee0) | Nov 01, 2020 |
| Lenovo        | ThinkCentre M58 6258WCY     | [a1896b3549](https://linux-hardware.org/?probe=a1896b3549) | Oct 26, 2020 |
| ASUSTek       | PRIME H110M-P               | [5f4ab6b326](https://linux-hardware.org/?probe=5f4ab6b326) | Oct 18, 2020 |
| Foxconn       | H61S                        | [0fd947c658](https://linux-hardware.org/?probe=0fd947c658) | Oct 12, 2020 |
| Dell          | 096JG8 A01                  | [337abf3073](https://linux-hardware.org/?probe=337abf3073) | Sep 30, 2020 |
| Huanan        | X79-8D VAA31                | [e0551a0a1c](https://linux-hardware.org/?probe=e0551a0a1c) | Sep 10, 2020 |
| Huanan        | X79-8D VAA31                | [66006c461d](https://linux-hardware.org/?probe=66006c461d) | Sep 06, 2020 |
| ASUSTek       | PRIME X370-PRO              | [524f57a765](https://linux-hardware.org/?probe=524f57a765) | Sep 06, 2020 |
| ASUSTek       | Z87-PLUS                    | [3fe15728ad](https://linux-hardware.org/?probe=3fe15728ad) | Sep 06, 2020 |
| ASUSTek       | Z87-PLUS                    | [e3f12cdd9b](https://linux-hardware.org/?probe=e3f12cdd9b) | Sep 05, 2020 |
| Dell          | 0Y2MRG A00                  | [8af1b0565b](https://linux-hardware.org/?probe=8af1b0565b) | Sep 03, 2020 |
| Acer          | Aspire TC-885 V:1.1         | [c90b90e1a8](https://linux-hardware.org/?probe=c90b90e1a8) | Aug 21, 2020 |
| ASRock        | B450M Pro4                  | [49170a6643](https://linux-hardware.org/?probe=49170a6643) | Aug 12, 2020 |
| ASUSTek       | M5A99X EVO                  | [6aae8e8b65](https://linux-hardware.org/?probe=6aae8e8b65) | Aug 12, 2020 |
| MSI           | IONA                        | [0510d0f8ef](https://linux-hardware.org/?probe=0510d0f8ef) | Aug 06, 2020 |
| MSI           | IONA                        | [446e406f22](https://linux-hardware.org/?probe=446e406f22) | Aug 06, 2020 |
| ASUSTek       | P5KPL-AM SE                 | [9c79ef0e1c](https://linux-hardware.org/?probe=9c79ef0e1c) | Jul 31, 2020 |
| ASUSTek       | P5KPL-AM SE                 | [242b101828](https://linux-hardware.org/?probe=242b101828) | Jul 31, 2020 |
| ASUSTek       | STRIX H270F GAMING          | [52b8fcb9b0](https://linux-hardware.org/?probe=52b8fcb9b0) | Jul 26, 2020 |
| Gigabyte      | Z87-HD3                     | [3eff281cc0](https://linux-hardware.org/?probe=3eff281cc0) | Jun 27, 2020 |
| Gigabyte      | F2A75-D3H                   | [59a8d5230f](https://linux-hardware.org/?probe=59a8d5230f) | Apr 09, 2020 |
| Pegatron      | 2A99                        | [f01c0c56e7](https://linux-hardware.org/?probe=f01c0c56e7) | Apr 08, 2020 |
| ASRock        | X570 Phantom Gaming 4       | [97ffeec17e](https://linux-hardware.org/?probe=97ffeec17e) | Mar 23, 2020 |
| Lenovo        | MAHOBAY NOK                 | [aaac6f9d4d](https://linux-hardware.org/?probe=aaac6f9d4d) | Mar 17, 2020 |
| ASRock        | X570 Phantom Gaming 4       | [63b8db155d](https://linux-hardware.org/?probe=63b8db155d) | Mar 02, 2020 |
| ASRock        | X570 Phantom Gaming 4       | [ed0b979970](https://linux-hardware.org/?probe=ed0b979970) | Mar 01, 2020 |
| ASRock        | X570 Phantom Gaming 4       | [85c6480266](https://linux-hardware.org/?probe=85c6480266) | Mar 01, 2020 |
| ASRock        | H81M-HDS                    | [0f180375d6](https://linux-hardware.org/?probe=0f180375d6) | Feb 25, 2020 |
| ASRock        | H81M-HDS                    | [55c569be56](https://linux-hardware.org/?probe=55c569be56) | Feb 23, 2020 |
| ASRock        | H81M-HDS                    | [98ae2a8227](https://linux-hardware.org/?probe=98ae2a8227) | Feb 22, 2020 |
| Gigabyte      | GA-880GM-UD2H               | [b189e00138](https://linux-hardware.org/?probe=b189e00138) | Jan 16, 2020 |
| Gigabyte      | GA-880GM-UD2H               | [ecb6ade802](https://linux-hardware.org/?probe=ecb6ade802) | Jan 16, 2020 |
| Intel         | DH55HC AAE70933-501         | [64266b67a2](https://linux-hardware.org/?probe=64266b67a2) | Dec 26, 2019 |
| HP            | 82F2 A01                    | [0b8306e086](https://linux-hardware.org/?probe=0b8306e086) | Nov 18, 2019 |
| Dell          | 0773VG A00                  | [adf2d5daca](https://linux-hardware.org/?probe=adf2d5daca) | Oct 31, 2019 |
| Dell          | 0773VG A00                  | [2f3044da6d](https://linux-hardware.org/?probe=2f3044da6d) | Oct 31, 2019 |
| MSI           | C236A WORKSTATION           | [fcc16b2804](https://linux-hardware.org/?probe=fcc16b2804) | Oct 11, 2019 |
| MSI           | C236A WORKSTATION           | [f68bc503a9](https://linux-hardware.org/?probe=f68bc503a9) | Oct 11, 2019 |
| Gigabyte      | H61M-DS2                    | [2560a1cb4e](https://linux-hardware.org/?probe=2560a1cb4e) | Aug 28, 2019 |
| Gigabyte      | H61M-DS2                    | [b013eab87a](https://linux-hardware.org/?probe=b013eab87a) | Aug 27, 2019 |
| ASUSTek       | Z8NA-D6                     | [81c929f40d](https://linux-hardware.org/?probe=81c929f40d) | Jan 23, 2019 |
| ASUSTek       | P8Z77-V DELUXE              | [2180eb318a](https://linux-hardware.org/?probe=2180eb318a) | Dec 30, 2018 |
| ASRock        | H97M Pro4                   | [2e4984a12a](https://linux-hardware.org/?probe=2e4984a12a) | Nov 27, 2018 |
| Lenovo        | ThinkCentre M91p 0266RZ1    | [812afde3d9](https://linux-hardware.org/?probe=812afde3d9) | Nov 21, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| Reborn OS         | 53       | 81.54%  |
| Reborn OS Rolling | 12       | 18.46%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| Reborn OS | 64       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Desktops | Percent |
|----------------------|----------|---------|
| 5.10.3-arch1-1       | 4        | 5.63%   |
| 5.9.14-arch1-1       | 3        | 4.23%   |
| 5.7.12-arch1-1       | 3        | 4.23%   |
| 5.9.1-arch1-1        | 2        | 2.82%   |
| 5.8.7-arch1-1        | 2        | 2.82%   |
| 5.16.12-arch1-1      | 2        | 2.82%   |
| 5.11.7-arch1-1       | 2        | 2.82%   |
| 5.10.4-arch2-1       | 2        | 2.82%   |
| 5.10.13-arch1-1      | 2        | 2.82%   |
| 6.2.6-arch1-1        | 1        | 1.41%   |
| 6.1.7-arch1-1        | 1        | 1.41%   |
| 6.0.6-arch1-1        | 1        | 1.41%   |
| 6.0.11-arch1-1       | 1        | 1.41%   |
| 5.9.6-arch1-1        | 1        | 1.41%   |
| 5.9.3-arch1-1        | 1        | 1.41%   |
| 5.9.2-arch1-1        | 1        | 1.41%   |
| 5.9.13-arch1-1       | 1        | 1.41%   |
| 5.9.12-arch1-1       | 1        | 1.41%   |
| 5.9.11-arch2-1       | 1        | 1.41%   |
| 5.8.6-arch1-1        | 1        | 1.41%   |
| 5.8.5-arch1-1        | 1        | 1.41%   |
| 5.8.14-arch1-1       | 1        | 1.41%   |
| 5.8.12-arch1-1       | 1        | 1.41%   |
| 5.8.1-arch1-1        | 1        | 1.41%   |
| 5.7.6-arch1-1-custom | 1        | 1.41%   |
| 5.7.11-arch1-1       | 1        | 1.41%   |
| 5.7.10-arch1-1       | 1        | 1.41%   |
| 5.6.3-arch1-1        | 1        | 1.41%   |
| 5.6.2-arch1-2        | 1        | 1.41%   |
| 5.5.9-arch1-2        | 1        | 1.41%   |
| 5.5.5-arch1-1        | 1        | 1.41%   |
| 5.5.2-arch1-1        | 1        | 1.41%   |
| 5.5.11-arch1-1       | 1        | 1.41%   |
| 5.4.6-arch3-1        | 1        | 1.41%   |
| 5.4.10-arch1-1       | 1        | 1.41%   |
| 5.3.7-arch1-2-ARCH   | 1        | 1.41%   |
| 5.3.5-arch1-1-ARCH   | 1        | 1.41%   |
| 5.3.11-arch1-1       | 1        | 1.41%   |
| 5.2.9-arch1-1-ARCH   | 1        | 1.41%   |
| 5.19.7-arch1-1       | 1        | 1.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10.3  | 4        | 5.71%   |
| 5.9.14  | 3        | 4.29%   |
| 5.7.12  | 3        | 4.29%   |
| 5.9.1   | 2        | 2.86%   |
| 5.8.7   | 2        | 2.86%   |
| 5.16.12 | 2        | 2.86%   |
| 5.11.7  | 2        | 2.86%   |
| 5.10.4  | 2        | 2.86%   |
| 5.10.13 | 2        | 2.86%   |
| 6.2.6   | 1        | 1.43%   |
| 6.1.7   | 1        | 1.43%   |
| 6.0.6   | 1        | 1.43%   |
| 6.0.11  | 1        | 1.43%   |
| 5.9.6   | 1        | 1.43%   |
| 5.9.3   | 1        | 1.43%   |
| 5.9.2   | 1        | 1.43%   |
| 5.9.13  | 1        | 1.43%   |
| 5.9.12  | 1        | 1.43%   |
| 5.9.11  | 1        | 1.43%   |
| 5.8.6   | 1        | 1.43%   |
| 5.8.5   | 1        | 1.43%   |
| 5.8.14  | 1        | 1.43%   |
| 5.8.12  | 1        | 1.43%   |
| 5.8.1   | 1        | 1.43%   |
| 5.7.6   | 1        | 1.43%   |
| 5.7.11  | 1        | 1.43%   |
| 5.7.10  | 1        | 1.43%   |
| 5.6.3   | 1        | 1.43%   |
| 5.6.2   | 1        | 1.43%   |
| 5.5.9   | 1        | 1.43%   |
| 5.5.5   | 1        | 1.43%   |
| 5.5.2   | 1        | 1.43%   |
| 5.5.11  | 1        | 1.43%   |
| 5.4.6   | 1        | 1.43%   |
| 5.4.10  | 1        | 1.43%   |
| 5.3.7   | 1        | 1.43%   |
| 5.3.5   | 1        | 1.43%   |
| 5.3.11  | 1        | 1.43%   |
| 5.2.9   | 1        | 1.43%   |
| 5.19.7  | 1        | 1.43%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.9     | 11       | 15.94%  |
| 5.10    | 9        | 13.04%  |
| 5.8     | 7        | 10.14%  |
| 5.7     | 6        | 8.7%    |
| 5.11    | 6        | 8.7%    |
| 5.5     | 4        | 5.8%    |
| 5.3     | 3        | 4.35%   |
| 5.16    | 3        | 4.35%   |
| 6.0     | 2        | 2.9%    |
| 5.6     | 2        | 2.9%    |
| 5.4     | 2        | 2.9%    |
| 5.19    | 2        | 2.9%    |
| 5.12    | 2        | 2.9%    |
| 4.19    | 2        | 2.9%    |
| 6.2     | 1        | 1.45%   |
| 6.1     | 1        | 1.45%   |
| 5.2     | 1        | 1.45%   |
| 5.18    | 1        | 1.45%   |
| 5.15    | 1        | 1.45%   |
| 5.14    | 1        | 1.45%   |
| 4.20    | 1        | 1.45%   |
| 4.18    | 1        | 1.45%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 64       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 11       | 17.19%  |
| X-Cinnamon | 10       | 15.63%  |
| KDE        | 8        | 12.5%   |
| XFCE       | 7        | 10.94%  |
| Deepin     | 7        | 10.94%  |
| Unknown    | 7        | 10.94%  |
| KDE5       | 5        | 7.81%   |
| Budgie     | 4        | 6.25%   |
| LXQt       | 2        | 3.13%   |
| MATE       | 1        | 1.56%   |
| i3         | 1        | 1.56%   |
| Cinnamon   | 1        | 1.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 56       | 87.5%   |
| Wayland | 8        | 12.5%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 53       | 80.3%   |
| TDM     | 4        | 6.06%   |
| LightDM | 4        | 6.06%   |
| GDM     | 3        | 4.55%   |
| SDDM    | 2        | 3.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 23       | 35.94%  |
| Unknown | 8        | 12.5%   |
| de_DE   | 7        | 10.94%  |
| es_ES   | 5        | 7.81%   |
| en_GB   | 5        | 7.81%   |
| es_AR   | 2        | 3.13%   |
| en_AU   | 2        | 3.13%   |
| en_AG   | 2        | 3.13%   |
| ru_UA   | 1        | 1.56%   |
| ru_RU   | 1        | 1.56%   |
| pt_BR   | 1        | 1.56%   |
| it_IT   | 1        | 1.56%   |
| fr_FR   | 1        | 1.56%   |
| es_PA   | 1        | 1.56%   |
| en_PH   | 1        | 1.56%   |
| en_CA   | 1        | 1.56%   |
| el_GR   | 1        | 1.56%   |
| de_AT   | 1        | 1.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 45       | 69.23%  |
| EFI  | 20       | 30.77%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 48       | 75%     |
| Unknown | 8        | 12.5%   |
| Tmpfs   | 4        | 6.25%   |
| Xfs     | 3        | 4.69%   |
| Btrfs   | 1        | 1.56%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 52       | 80%     |
| GPT     | 12       | 18.46%  |
| MBR     | 1        | 1.54%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 58       | 90.63%  |
| Yes       | 6        | 9.38%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 57       | 87.69%  |
| Yes       | 8        | 12.31%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 18       | 28.13%  |
| Gigabyte Technology | 9        | 14.06%  |
| ASRock              | 7        | 10.94%  |
| MSI                 | 6        | 9.38%   |
| Dell                | 6        | 9.38%   |
| Hewlett-Packard     | 4        | 6.25%   |
| Lenovo              | 3        | 4.69%   |
| Pegatron            | 2        | 3.13%   |
| Shuttle             | 1        | 1.56%   |
| OEM                 | 1        | 1.56%   |
| Medion              | 1        | 1.56%   |
| Intel               | 1        | 1.56%   |
| Huanan              | 1        | 1.56%   |
| Foxconn             | 1        | 1.56%   |
| Biostar             | 1        | 1.56%   |
| BESSTAR Tech        | 1        | 1.56%   |
| Acer                | 1        | 1.56%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| MSI MS-7721                     | 2        | 3.13%   |
| ASRock X570 Phantom Gaming 4    | 2        | 3.13%   |
| Shuttle SZ270                   | 1        | 1.56%   |
| Pegatron Elite 7500 Series MT   | 1        | 1.56%   |
| Pegatron CQ3476L                | 1        | 1.56%   |
| OEM G41 775 ICH7 8712           | 1        | 1.56%   |
| MSI WK711AA-ACB HPE-110ru       | 1        | 1.56%   |
| MSI MS-7C35                     | 1        | 1.56%   |
| MSI MS-7A36                     | 1        | 1.56%   |
| MSI MS-7998                     | 1        | 1.56%   |
| Medion P961x                    | 1        | 1.56%   |
| Lenovo ThinkCentre M92 32071F5  | 1        | 1.56%   |
| Lenovo ThinkCentre M91p 0266RZ1 | 1        | 1.56%   |
| Lenovo ThinkCentre M58 6258WCY  | 1        | 1.56%   |
| Intel DH55HC AAE70933-501       | 1        | 1.56%   |
| Huanan X79-8D VAA31             | 1        | 1.56%   |
| HP ProDesk 600 G1 SFF           | 1        | 1.56%   |
| HP Pavilion Desktop PC 570-p0XX | 1        | 1.56%   |
| HP EliteDesk 705 G4 MT          | 1        | 1.56%   |
| HP Compaq 6000 Pro MT PC        | 1        | 1.56%   |
| Gigabyte Z87-HD3                | 1        | 1.56%   |
| Gigabyte X570 AORUS ELITE       | 1        | 1.56%   |
| Gigabyte H61M-DS2               | 1        | 1.56%   |
| Gigabyte H110M-S2PT-CF          | 1        | 1.56%   |
| Gigabyte GA-880GM-UD2H          | 1        | 1.56%   |
| Gigabyte F2A85X-UP4             | 1        | 1.56%   |
| Gigabyte F2A75-D3H              | 1        | 1.56%   |
| Gigabyte EP43-UD3L              | 1        | 1.56%   |
| Gigabyte B450 AORUS M           | 1        | 1.56%   |
| Foxconn H61S                    | 1        | 1.56%   |
| Dell XPS 8300                   | 1        | 1.56%   |
| Dell OptiPlex 780               | 1        | 1.56%   |
| Dell OptiPlex 7040              | 1        | 1.56%   |
| Dell OptiPlex 7020              | 1        | 1.56%   |
| Dell OptiPlex 7010              | 1        | 1.56%   |
| Dell Inspiron 660               | 1        | 1.56%   |
| Biostar A320MH                  | 1        | 1.56%   |
| BESSTAR Tech B550               | 1        | 1.56%   |
| ASUS Z8NA-D6                    | 1        | 1.56%   |
| ASUS STRIX H270F GAMING         | 1        | 1.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 5        | 7.81%   |
| Dell OptiPlex          | 4        | 6.25%   |
| ASUS ROG               | 4        | 6.25%   |
| Lenovo ThinkCentre     | 3        | 4.69%   |
| ASRock X570            | 3        | 4.69%   |
| MSI MS-7721            | 2        | 3.13%   |
| Shuttle SZ270          | 1        | 1.56%   |
| Pegatron Elite         | 1        | 1.56%   |
| Pegatron CQ3476L       | 1        | 1.56%   |
| OEM G41                | 1        | 1.56%   |
| MSI WK711AA-ACB        | 1        | 1.56%   |
| MSI MS-7C35            | 1        | 1.56%   |
| MSI MS-7A36            | 1        | 1.56%   |
| MSI MS-7998            | 1        | 1.56%   |
| Medion P961x           | 1        | 1.56%   |
| Intel DH55HC           | 1        | 1.56%   |
| Huanan X79-8D          | 1        | 1.56%   |
| HP ProDesk             | 1        | 1.56%   |
| HP Pavilion            | 1        | 1.56%   |
| HP EliteDesk           | 1        | 1.56%   |
| HP Compaq              | 1        | 1.56%   |
| Gigabyte Z87-HD3       | 1        | 1.56%   |
| Gigabyte X570          | 1        | 1.56%   |
| Gigabyte H61M-DS2      | 1        | 1.56%   |
| Gigabyte H110M-S2PT-CF | 1        | 1.56%   |
| Gigabyte GA-880GM-UD2H | 1        | 1.56%   |
| Gigabyte F2A85X-UP4    | 1        | 1.56%   |
| Gigabyte F2A75-D3H     | 1        | 1.56%   |
| Gigabyte EP43-UD3L     | 1        | 1.56%   |
| Gigabyte B450          | 1        | 1.56%   |
| Foxconn H61S           | 1        | 1.56%   |
| Dell XPS               | 1        | 1.56%   |
| Dell Inspiron          | 1        | 1.56%   |
| Biostar A320MH         | 1        | 1.56%   |
| BESSTAR Tech B550      | 1        | 1.56%   |
| ASUS Z8NA-D6           | 1        | 1.56%   |
| ASUS STRIX             | 1        | 1.56%   |
| ASUS Q87M-XA           | 1        | 1.56%   |
| ASUS P8Z77-V           | 1        | 1.56%   |
| ASUS P8B75-V           | 1        | 1.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 10       | 15.63%  |
| 2012 | 9        | 14.06%  |
| 2013 | 8        | 12.5%   |
| 2018 | 7        | 10.94%  |
| 2016 | 5        | 7.81%   |
| 2010 | 5        | 7.81%   |
| 2009 | 5        | 7.81%   |
| 2017 | 4        | 6.25%   |
| 2011 | 3        | 4.69%   |
| 2022 | 2        | 3.13%   |
| 2014 | 2        | 3.13%   |
| 2008 | 2        | 3.13%   |
| 2020 | 1        | 1.56%   |
| 2015 | 1        | 1.56%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 64       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 64       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 64       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 19       | 28.79%  |
| 8.01-16.0   | 16       | 24.24%  |
| 4.01-8.0    | 13       | 19.7%   |
| 32.01-64.0  | 10       | 15.15%  |
| 3.01-4.0    | 5        | 7.58%   |
| 64.01-256.0 | 2        | 3.03%   |
| 1.01-2.0    | 1        | 1.52%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 26       | 37.68%  |
| 2.01-3.0  | 20       | 28.99%  |
| 4.01-8.0  | 10       | 14.49%  |
| 3.01-4.0  | 9        | 13.04%  |
| 8.01-16.0 | 2        | 2.9%    |
| 0.51-1.0  | 2        | 2.9%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 23       | 35.38%  |
| 2      | 20       | 30.77%  |
| 4      | 9        | 13.85%  |
| 3      | 8        | 12.31%  |
| 0      | 2        | 3.08%   |
| 7      | 1        | 1.54%   |
| 6      | 1        | 1.54%   |
| 5      | 1        | 1.54%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 34       | 52.31%  |
| Yes       | 31       | 47.69%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 60       | 93.75%  |
| No        | 4        | 6.25%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 33       | 51.56%  |
| No        | 31       | 48.44%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 40       | 62.5%   |
| Yes       | 24       | 37.5%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 17       | 26.56%  |
| Germany     | 8        | 12.5%   |
| UK          | 5        | 7.81%   |
| Spain       | 5        | 7.81%   |
| Canada      | 4        | 6.25%   |
| Netherlands | 3        | 4.69%   |
| Thailand    | 2        | 3.13%   |
| Panama      | 2        | 3.13%   |
| India       | 2        | 3.13%   |
| Greece      | 2        | 3.13%   |
| Argentina   | 2        | 3.13%   |
| Ukraine     | 1        | 1.56%   |
| UAE         | 1        | 1.56%   |
| Russia      | 1        | 1.56%   |
| Philippines | 1        | 1.56%   |
| Italy       | 1        | 1.56%   |
| Hungary     | 1        | 1.56%   |
| Egypt       | 1        | 1.56%   |
| Colombia    | 1        | 1.56%   |
| Brazil      | 1        | 1.56%   |
| Azerbaijan  | 1        | 1.56%   |
| Austria     | 1        | 1.56%   |
| Australia   | 1        | 1.56%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Miami             | 2        | 2.94%   |
| Lelystad          | 2        | 2.94%   |
| Cologne           | 2        | 2.94%   |
| Athens            | 2        | 2.94%   |
| Zutphen           | 1        | 1.47%   |
| Wuppertal         | 1        | 1.47%   |
| Winsted           | 1        | 1.47%   |
| Weil im Schonbuch | 1        | 1.47%   |
| Watford           | 1        | 1.47%   |
| Verwood           | 1        | 1.47%   |
| Tres Cantos       | 1        | 1.47%   |
| Toledo            | 1        | 1.47%   |
| Szekszárd        | 1        | 1.47%   |
| Sydney            | 1        | 1.47%   |
| Surrey            | 1        | 1.47%   |
| Stuttgart         | 1        | 1.47%   |
| Streatham         | 1        | 1.47%   |
| Spremberg         | 1        | 1.47%   |
| Southampton       | 1        | 1.47%   |
| Smithfield        | 1        | 1.47%   |
| Si Racha          | 1        | 1.47%   |
| Seville           | 1        | 1.47%   |
| Sao Paulo         | 1        | 1.47%   |
| Santa Clara       | 1        | 1.47%   |
| Salt Lake City    | 1        | 1.47%   |
| Reno              | 1        | 1.47%   |
| Redding           | 1        | 1.47%   |
| Quezon City       | 1        | 1.47%   |
| Queens            | 1        | 1.47%   |
| Purdon            | 1        | 1.47%   |
| Pont-y-clun       | 1        | 1.47%   |
| Phoenix           | 1        | 1.47%   |
| Novosibirsk       | 1        | 1.47%   |
| Newcastle         | 1        | 1.47%   |
| New Delhi         | 1        | 1.47%   |
| Mascouche         | 1        | 1.47%   |
| Ludwigsburg       | 1        | 1.47%   |
| Lehigh Acres      | 1        | 1.47%   |
| Kyiv              | 1        | 1.47%   |
| Kochi             | 1        | 1.47%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 28       | 36     | 22.95%  |
| Seagate             | 18       | 24     | 14.75%  |
| Samsung Electronics | 18       | 22     | 14.75%  |
| Toshiba             | 8        | 9      | 6.56%   |
| Phison              | 6        | 7      | 4.92%   |
| Hitachi             | 6        | 6      | 4.92%   |
| Crucial             | 5        | 6      | 4.1%    |
| SanDisk             | 4        | 5      | 3.28%   |
| Kingston            | 4        | 4      | 3.28%   |
| ZOTAC               | 2        | 2      | 1.64%   |
| Unknown             | 2        | 2      | 1.64%   |
| PNY                 | 2        | 2      | 1.64%   |
| Phison Electronics  | 2        | 3      | 1.64%   |
| Intel               | 2        | 2      | 1.64%   |
| SPCC                | 1        | 1      | 0.82%   |
| Patriot             | 1        | 1      | 0.82%   |
| OCZ                 | 1        | 2      | 0.82%   |
| KingSpec            | 1        | 1      | 0.82%   |
| JMicron Technology  | 1        | 1      | 0.82%   |
| HGST                | 1        | 1      | 0.82%   |
| Hewlett-Packard     | 1        | 2      | 0.82%   |
| Gigabyte Technology | 1        | 2      | 0.82%   |
| Emtec               | 1        | 1      | 0.82%   |
| Drevo               | 1        | 1      | 0.82%   |
| Dell                | 1        | 1      | 0.82%   |
| ASMT                | 1        | 1      | 0.82%   |
| AMD                 | 1        | 1      | 0.82%   |
| addlink             | 1        | 1      | 0.82%   |
| A-DATA Technology   | 1        | 1      | 0.82%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Samsung SSD 860 EVO 500GB        | 3        | 2.19%   |
| WDC WD10EZEX-08WN4A0 1TB         | 2        | 1.46%   |
| WDC WD1002FAEX-00Z3A0 1TB        | 2        | 1.46%   |
| WDC WD1001FALS-403AA0 1TB        | 2        | 1.46%   |
| Toshiba DT01ACA100 1TB           | 2        | 1.46%   |
| Seagate ST3500312CS 500GB        | 2        | 1.46%   |
| Seagate ST2000DM006-2DM164 2TB   | 2        | 1.46%   |
| Seagate ST1000DM003-1CH162 1TB   | 2        | 1.46%   |
| Seagate Expansion Desk 8TB       | 2        | 1.46%   |
| Samsung SSD 850 EVO 500GB        | 2        | 1.46%   |
| PNY CS900 120GB SSD              | 2        | 1.46%   |
| Phison NVMe SSD Drive 960GB      | 2        | 1.46%   |
| Phison NVMe SSD Drive 240GB      | 2        | 1.46%   |
| Phison NVMe SSD Drive 1TB        | 2        | 1.46%   |
| Crucial CT1000MX500SSD1 1TB      | 2        | 1.46%   |
| ZOTAC ZTSSD-S11-120G-P 120GB     | 1        | 0.73%   |
| ZOTAC ZTSSD-A4P-120G             | 1        | 0.73%   |
| WDC WDS500G2X0C-00L350 500GB     | 1        | 0.73%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 1        | 0.73%   |
| WDC WDS100T3X0C-00SJG0 1TB       | 1        | 0.73%   |
| WDC WD6400AAKS-22A7B0 640GB      | 1        | 0.73%   |
| WDC WD6400AAKS-00A7B2 640GB      | 1        | 0.73%   |
| WDC WD6400AAKS-00A7B0 640GB      | 1        | 0.73%   |
| WDC WD60EZRZ-00GZ5B1 6TB         | 1        | 0.73%   |
| WDC WD5000LPVX-00V0TT0 500GB     | 1        | 0.73%   |
| WDC WD5000AZLX-00JKKA0 500GB     | 1        | 0.73%   |
| WDC WD5000AVDS-63U7B1 500GB      | 1        | 0.73%   |
| WDC WD5000AAKX-753CA1 500GB      | 1        | 0.73%   |
| WDC WD5000AADS-00S9B0 500GB      | 1        | 0.73%   |
| WDC WD3200AAKS-00UU3A0 320GB     | 1        | 0.73%   |
| WDC WD30PURX-64P6ZY0 3TB         | 1        | 0.73%   |
| WDC WD2500JS-00MHB0 250GB        | 1        | 0.73%   |
| WDC WD20EZRX-00D8PB0 2TB         | 1        | 0.73%   |
| WDC WD20EURX-63T0FY0 2TB         | 1        | 0.73%   |
| WDC WD2003FZEX-00SRLA0 2TB       | 1        | 0.73%   |
| WDC WD2003FYPS-27Y2B0 2TB        | 1        | 0.73%   |
| WDC WD15EADS-65P8B1 1TB          | 1        | 0.73%   |
| WDC WD10EZRX-00L4HB0 1TB         | 1        | 0.73%   |
| WDC WD10EZRX-00A8LB0 1TB         | 1        | 0.73%   |
| WDC WD10EZEX-21WN4A0 1TB         | 1        | 0.73%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 25       | 32     | 42.37%  |
| Seagate             | 18       | 24     | 30.51%  |
| Hitachi             | 6        | 6      | 10.17%  |
| Toshiba             | 5        | 5      | 8.47%   |
| Samsung Electronics | 2        | 2      | 3.39%   |
| Unknown             | 1        | 1      | 1.69%   |
| JMicron Technology  | 1        | 1      | 1.69%   |
| HGST                | 1        | 1      | 1.69%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 13       | 13     | 33.33%  |
| Kingston            | 4        | 4      | 10.26%  |
| Crucial             | 4        | 5      | 10.26%  |
| ZOTAC               | 2        | 2      | 5.13%   |
| SanDisk             | 2        | 3      | 5.13%   |
| PNY                 | 2        | 2      | 5.13%   |
| WDC                 | 1        | 1      | 2.56%   |
| Toshiba             | 1        | 1      | 2.56%   |
| Patriot             | 1        | 1      | 2.56%   |
| OCZ                 | 1        | 2      | 2.56%   |
| KingSpec            | 1        | 1      | 2.56%   |
| Hewlett-Packard     | 1        | 2      | 2.56%   |
| Gigabyte Technology | 1        | 2      | 2.56%   |
| Emtec               | 1        | 1      | 2.56%   |
| Drevo               | 1        | 1      | 2.56%   |
| ASMT                | 1        | 1      | 2.56%   |
| AMD                 | 1        | 1      | 2.56%   |
| A-DATA Technology   | 1        | 1      | 2.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 42       | 72     | 44.21%  |
| SSD     | 30       | 44     | 31.58%  |
| NVMe    | 21       | 30     | 22.11%  |
| Unknown | 2        | 2      | 2.11%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 55       | 111    | 67.07%  |
| NVMe | 21       | 30     | 25.61%  |
| SAS  | 6        | 7      | 7.32%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 41       | 62     | 48.24%  |
| 0.51-1.0   | 29       | 35     | 34.12%  |
| 1.01-2.0   | 7        | 9      | 8.24%   |
| 2.01-3.0   | 4        | 5      | 4.71%   |
| 4.01-10.0  | 3        | 4      | 3.53%   |
| 3.01-4.0   | 1        | 1      | 1.18%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 17       | 26.56%  |
| 101-250        | 11       | 17.19%  |
| 251-500        | 10       | 15.63%  |
| More than 3000 | 8        | 12.5%   |
| 1001-2000      | 6        | 9.38%   |
| 51-100         | 4        | 6.25%   |
| 2001-3000      | 3        | 4.69%   |
| Unknown        | 3        | 4.69%   |
| 21-50          | 2        | 3.13%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 21       | 30.43%  |
| 21-50          | 20       | 28.99%  |
| 251-500        | 6        | 8.7%    |
| 501-1000       | 5        | 7.25%   |
| 51-100         | 5        | 7.25%   |
| 101-250        | 4        | 5.8%    |
| 2001-3000      | 3        | 4.35%   |
| Unknown        | 3        | 4.35%   |
| More than 3000 | 1        | 1.45%   |
| 1001-2000      | 1        | 1.45%   |

Malfunc. Drives
---------------

Drive models with a malfunction

Zero info for selected period =(

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

Zero info for selected period =(

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

Zero info for selected period =(

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
| Detected | 53       | 117    | 82.81%  |
| Works    | 11       | 31     | 17.19%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 39       | 43.33%  |
| AMD                          | 23       | 25.56%  |
| Phison Electronics           | 9        | 10%     |
| Samsung Electronics          | 6        | 6.67%   |
| SanDisk                      | 4        | 4.44%   |
| JMicron Technology           | 3        | 3.33%   |
| Toshiba America Info Systems | 2        | 2.22%   |
| Nvidia                       | 1        | 1.11%   |
| Micron/Crucial Technology    | 1        | 1.11%   |
| ASMedia Technology           | 1        | 1.11%   |
| ADATA Technology             | 1        | 1.11%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 20       | 16.67%  |
| Phison E12 NVMe Controller                                                              | 6        | 5%      |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5        | 4.17%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 5        | 4.17%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4        | 3.33%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4        | 3.33%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 4        | 3.33%   |
| AMD 400 Series Chipset SATA Controller                                                  | 4        | 3.33%   |
| Intel SATA Controller [RAID mode]                                                       | 3        | 2.5%    |
| Intel 4 Series Chipset PT IDER Controller                                               | 3        | 2.5%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3        | 2.5%    |
| Phison E16 PCIe4 NVMe Controller                                                        | 2        | 1.67%   |
| JMicron JMB368 IDE controller                                                           | 2        | 1.67%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2        | 1.67%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 2        | 1.67%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 2        | 1.67%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2        | 1.67%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 2        | 1.67%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]           | 2        | 1.67%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 1.67%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 1.67%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2        | 1.67%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 2        | 1.67%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 2        | 1.67%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2        | 1.67%   |
| AMD FCH SATA Controller D                                                               | 2        | 1.67%   |
| AMD 300 Series Chipset SATA Controller                                                  | 2        | 1.67%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                                    | 1        | 0.83%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                                    | 1        | 0.83%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 1        | 0.83%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1        | 0.83%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1        | 0.83%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1        | 0.83%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 0.83%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 0.83%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1        | 0.83%   |
| Phison E7 NVMe Controller                                                               | 1        | 0.83%   |
| Nvidia MCP61 SATA Controller                                                            | 1        | 0.83%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 1        | 0.83%   |
| JMicron JMB362 SATA Controller                                                          | 1        | 0.83%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 48       | 53.33%  |
| NVMe | 21       | 23.33%  |
| IDE  | 18       | 20%     |
| RAID | 3        | 3.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 39       | 60.94%  |
| AMD    | 25       | 39.06%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 4        | 6.15%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 3.08%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 2        | 3.08%   |
| AMD Ryzen 5 3600 6-Core Processor           | 2        | 3.08%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 2        | 3.08%   |
| AMD A4-5300 APU with Radeon HD Graphics     | 2        | 3.08%   |
| AMD A10-5800K APU with Radeon HD Graphics   | 2        | 3.08%   |
| Intel Xeon CPU E5530 @ 2.40GHz              | 1        | 1.54%   |
| Intel Xeon CPU E5-2697 v2 @ 2.70GHz         | 1        | 1.54%   |
| Intel Xeon CPU E3-1270 V2 @ 3.50GHz         | 1        | 1.54%   |
| Intel Xeon CPU E3-1225 v5 @ 3.30GHz         | 1        | 1.54%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 1        | 1.54%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 1        | 1.54%   |
| Intel Pentium CPU G3258 @ 3.20GHz           | 1        | 1.54%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 1.54%   |
| Intel Core i7-6700T CPU @ 2.80GHz           | 1        | 1.54%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1        | 1.54%   |
| Intel Core i7-4770S CPU @ 3.10GHz           | 1        | 1.54%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1        | 1.54%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 1        | 1.54%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 1        | 1.54%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1        | 1.54%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 1        | 1.54%   |
| Intel Core i5-6500T CPU @ 2.50GHz           | 1        | 1.54%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 1        | 1.54%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 1        | 1.54%   |
| Intel Core i5-4570T CPU @ 2.90GHz           | 1        | 1.54%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 1        | 1.54%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 1        | 1.54%   |
| Intel Core i5-3340 CPU @ 3.10GHz            | 1        | 1.54%   |
| Intel Core i5-2400S CPU @ 2.50GHz           | 1        | 1.54%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 1        | 1.54%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 1        | 1.54%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 1        | 1.54%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 1        | 1.54%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 1        | 1.54%   |
| Intel Core i3 CPU 540 @ 3.07GHz             | 1        | 1.54%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 1        | 1.54%   |
| Intel Core 2 Duo CPU E7200 @ 2.53GHz        | 1        | 1.54%   |
| Intel Core 2 Duo CPU E6750 @ 2.66GHz        | 1        | 1.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 16       | 24.62%  |
| Intel Core 2 Duo        | 7        | 10.77%  |
| AMD Ryzen 5             | 7        | 10.77%  |
| Intel Core i7           | 6        | 9.23%   |
| AMD Ryzen 7             | 5        | 7.69%   |
| Intel Xeon              | 4        | 6.15%   |
| Intel Core i3           | 3        | 4.62%   |
| Intel Pentium           | 2        | 3.08%   |
| AMD Ryzen 9             | 2        | 3.08%   |
| AMD FX                  | 2        | 3.08%   |
| AMD A4                  | 2        | 3.08%   |
| AMD A10                 | 2        | 3.08%   |
| Intel Pentium Dual-Core | 1        | 1.54%   |
| Intel Celeron           | 1        | 1.54%   |
| AMD Ryzen 7 PRO         | 1        | 1.54%   |
| AMD Ryzen 3             | 1        | 1.54%   |
| AMD Phenom II X4        | 1        | 1.54%   |
| AMD Athlon II X2        | 1        | 1.54%   |
| AMD A12                 | 1        | 1.54%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 23       | 35.94%  |
| 2      | 19       | 29.69%  |
| 6      | 9        | 14.06%  |
| 8      | 7        | 10.94%  |
| 1      | 2        | 3.13%   |
| 24     | 1        | 1.56%   |
| 16     | 1        | 1.56%   |
| 12     | 1        | 1.56%   |
| 3      | 1        | 1.56%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 62       | 96.88%  |
| 2      | 2        | 3.13%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 36       | 56.25%  |
| 1      | 28       | 43.75%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 57       | 89.06%  |
| Unknown        | 7        | 10.94%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 14       | 21.21%  |
| 0x506e3    | 5        | 7.58%   |
| 0x306c3    | 5        | 7.58%   |
| 0x306a9    | 5        | 7.58%   |
| 0x0800820d | 5        | 7.58%   |
| 0x206a7    | 4        | 6.06%   |
| 0x06001119 | 4        | 6.06%   |
| 0x906e9    | 3        | 4.55%   |
| 0x20652    | 2        | 3.03%   |
| 0x1067a    | 2        | 3.03%   |
| 0x906ea    | 1        | 1.52%   |
| 0x6fb      | 1        | 1.52%   |
| 0x306e4    | 1        | 1.52%   |
| 0x106e5    | 1        | 1.52%   |
| 0x106a5    | 1        | 1.52%   |
| 0x10676    | 1        | 1.52%   |
| 0x0a601203 | 1        | 1.52%   |
| 0x0a50000d | 1        | 1.52%   |
| 0x0a201016 | 1        | 1.52%   |
| 0x0a201009 | 1        | 1.52%   |
| 0x08701021 | 1        | 1.52%   |
| 0x08108109 | 1        | 1.52%   |
| 0x08001138 | 1        | 1.52%   |
| 0x0600081c | 1        | 1.52%   |
| 0x06000817 | 1        | 1.52%   |
| 0x010000c8 | 1        | 1.52%   |
| 0x010000b6 | 1        | 1.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Zen+        | 7        | 10.94%  |
| IvyBridge   | 7        | 10.94%  |
| Haswell     | 7        | 10.94%  |
| Piledriver  | 6        | 9.38%   |
| Penryn      | 6        | 9.38%   |
| Skylake     | 5        | 7.81%   |
| KabyLake    | 5        | 7.81%   |
| Zen 2       | 4        | 6.25%   |
| SandyBridge | 4        | 6.25%   |
| Zen 3       | 2        | 3.13%   |
| Zen         | 2        | 3.13%   |
| Westmere    | 2        | 3.13%   |
| Nehalem     | 2        | 3.13%   |
| K10         | 2        | 3.13%   |
| Excavator   | 1        | 1.56%   |
| Core        | 1        | 1.56%   |
| Unknown     | 1        | 1.56%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 28       | 40.58%  |
| AMD               | 24       | 34.78%  |
| Intel             | 16       | 23.19%  |
| ASPEED Technology | 1        | 1.45%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia GK208B [GeForce GT 710]                                              | 4        | 5.56%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 4        | 5.56%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3        | 4.17%   |
| Nvidia GF108 [GeForce GT 730]                                               | 3        | 4.17%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 4.17%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 2        | 2.78%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 2.78%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 2.78%   |
| Intel HD Graphics 530                                                       | 2        | 2.78%   |
| AMD Trinity [Radeon HD 7660D]                                               | 2        | 2.78%   |
| AMD Curacao XT / Trinidad XT [Radeon R7 370 / R9 270X/370X]                 | 2        | 2.78%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 1.39%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                      | 1        | 1.39%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 1.39%   |
| Nvidia GT216M [GeForce GT 330M]                                             | 1        | 1.39%   |
| Nvidia GT200GL [Quadro FX 4800]                                             | 1        | 1.39%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 1.39%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 1.39%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 1.39%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 1.39%   |
| Nvidia GM204 [GeForce GTX 980]                                              | 1        | 1.39%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1        | 1.39%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 1.39%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 1        | 1.39%   |
| Nvidia GK104GL [Tesla K10]                                                  | 1        | 1.39%   |
| Nvidia GF119 [NVS 310]                                                      | 1        | 1.39%   |
| Nvidia GF119 [GeForce GT 610]                                               | 1        | 1.39%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 1.39%   |
| Nvidia GF108 [GeForce GT 420]                                               | 1        | 1.39%   |
| Nvidia AD102 [GeForce RTX 4090]                                             | 1        | 1.39%   |
| Intel HD Graphics P530                                                      | 1        | 1.39%   |
| Intel HD Graphics 630                                                       | 1        | 1.39%   |
| Intel HD Graphics 610                                                       | 1        | 1.39%   |
| Intel Core Processor Integrated Graphics Controller                         | 1        | 1.39%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 1        | 1.39%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 1.39%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1        | 1.39%   |
| ASPEED Technology ASPEED Graphics Family                                    | 1        | 1.39%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 1        | 1.39%   |
| AMD Vega 20 [Radeon VII]                                                    | 1        | 1.39%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 25       | 39.06%  |
| 1 x AMD        | 23       | 35.94%  |
| 1 x Intel      | 12       | 18.75%  |
| 3 x Nvidia     | 1        | 1.56%   |
| Intel + Nvidia | 1        | 1.56%   |
| 1 x ASPEED     | 1        | 1.56%   |
| AMD + Nvidia   | 1        | 1.56%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 51       | 78.46%  |
| Proprietary | 13       | 20%     |
| Unknown     | 1        | 1.54%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 26       | 40%     |
| 1.01-2.0   | 10       | 15.38%  |
| 7.01-8.0   | 7        | 10.77%  |
| 3.01-4.0   | 6        | 9.23%   |
| 0.51-1.0   | 5        | 7.69%   |
| 0.01-0.5   | 4        | 6.15%   |
| 8.01-16.0  | 3        | 4.62%   |
| 2.01-3.0   | 2        | 3.08%   |
| 5.01-6.0   | 1        | 1.54%   |
| 16.01-24.0 | 1        | 1.54%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 14       | 20.29%  |
| Hewlett-Packard      | 8        | 11.59%  |
| Dell                 | 6        | 8.7%    |
| BenQ                 | 6        | 8.7%    |
| Acer                 | 6        | 8.7%    |
| Goldstar             | 5        | 7.25%   |
| Philips              | 4        | 5.8%    |
| Ancor Communications | 3        | 4.35%   |
| MSI                  | 2        | 2.9%    |
| AOC                  | 2        | 2.9%    |
| Vizio                | 1        | 1.45%   |
| Vestel               | 1        | 1.45%   |
| Unknown              | 1        | 1.45%   |
| Sony                 | 1        | 1.45%   |
| Sceptre Tech         | 1        | 1.45%   |
| Plain Tree Systems   | 1        | 1.45%   |
| ONN                  | 1        | 1.45%   |
| Microstep            | 1        | 1.45%   |
| Medion               | 1        | 1.45%   |
| Iiyama               | 1        | 1.45%   |
| Hitachi              | 1        | 1.45%   |
| GRM                  | 1        | 1.45%   |
| ASUSTek Computer     | 1        | 1.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics SA300/SA350 SAM0791 1920x1080 510x287mm 23.0-inch | 2        | 2.6%    |
| MSI MAG341CQ MSI1462 3440x1440 797x333mm 34.0-inch                    | 2        | 2.6%    |
| Vizio D43-D2 VIZ1004 1920x1080 477x268mm 21.5-inch                    | 1        | 1.3%    |
| Vestel LCD Monitor 32W_LCD_TV                                         | 1        | 1.3%    |
| Unknown LCD Monitor DAC Moniter 5760x1080                             | 1        | 1.3%    |
| Sony TV SNYF301 1920x1080                                             | 1        | 1.3%    |
| Sceptre Tech Sceptre M25 SPT0A05 1920x1080 597x336mm 27.0-inch        | 1        | 1.3%    |
| Samsung Electronics SyncMaster SAM0593 1920x1080 477x268mm 21.5-inch  | 1        | 1.3%    |
| Samsung Electronics SyncMaster SAM036F 1440x900 428x255mm 19.6-inch   | 1        | 1.3%    |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch     | 1        | 1.3%    |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 1        | 1.3%    |
| Samsung Electronics S22D300 SAM0B3E 1920x1080 477x268mm 21.5-inch     | 1        | 1.3%    |
| Samsung Electronics LU28R55 SAM1016 3840x2160 632x360mm 28.6-inch     | 1        | 1.3%    |
| Samsung Electronics LCD Monitor SAM0DF7 3840x2160 890x500mm 40.2-inch | 1        | 1.3%    |
| Samsung Electronics LCD Monitor SAM094E 1920x1080 700x390mm 31.5-inch | 1        | 1.3%    |
| Samsung Electronics LCD Monitor SAM07BA 1920x1080                     | 1        | 1.3%    |
| Samsung Electronics LCD Monitor SAM0297 1360x768 885x498mm 40.0-inch  | 1        | 1.3%    |
| Samsung Electronics LCD Monitor S24D300 1920x1080                     | 1        | 1.3%    |
| Samsung Electronics LCD Monitor S22D300 1920x1080                     | 1        | 1.3%    |
| Plain Tree Systems TFT19DXP PTS03A0 1280x1024 376x301mm 19.0-inch     | 1        | 1.3%    |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch              | 1        | 1.3%    |
| Philips PHL 273V5 PHLC0D2 1920x1080 598x336mm 27.0-inch               | 1        | 1.3%    |
| Philips PHL 246E9Q PHLC17C 1920x1080 527x296mm 23.8-inch              | 1        | 1.3%    |
| Philips LCD Monitor PHL 276E8V 7680x2160                              | 1        | 1.3%    |
| Philips LCD Monitor PHL 276E8V                                        | 1        | 1.3%    |
| ONN onn. TV ONN007D 3840x2160 800x450mm 36.1-inch                     | 1        | 1.3%    |
| MSI Optix G27C2 MSI1462 1920x1080 600x330mm 27.0-inch                 | 1        | 1.3%    |
| MSI MPG341CQR MSI3DA0 3440x1440 797x334mm 34.0-inch                   | 1        | 1.3%    |
| Microstep LCD Monitor Optix MAG24C 3840x1200                          | 1        | 1.3%    |
| Medion Medion23.6 PC MEDB603 1920x1080 477x268mm 21.5-inch            | 1        | 1.3%    |
| Iiyama PL2493H IVM6148 1920x1080 527x296mm 23.8-inch                  | 1        | 1.3%    |
| Hitachi HISENSE HEC002F 3840x2160 1872x1053mm 84.6-inch               | 1        | 1.3%    |
| Hewlett-Packard x23LED HWP2912 1920x1080 509x286mm 23.0-inch          | 1        | 1.3%    |
| Hewlett-Packard w2228h HWP2810 1680x1050 473x296mm 22.0-inch          | 1        | 1.3%    |
| Hewlett-Packard w2207 HWP26A8 1680x1050 473x296mm 22.0-inch           | 1        | 1.3%    |
| Hewlett-Packard vs19x HWP2658 1280x1024 376x301mm 19.0-inch           | 1        | 1.3%    |
| Hewlett-Packard LCD Monitor x23LED 1920x1080                          | 1        | 1.3%    |
| Hewlett-Packard LA1905 HWP2845 1440x900 408x255mm 18.9-inch           | 1        | 1.3%    |
| Hewlett-Packard Compaq S1922 HWP290B 1366x768 413x234mm 18.7-inch     | 1        | 1.3%    |
| Hewlett-Packard 27ea HPN3395 1920x1080 527x296mm 23.8-inch            | 1        | 1.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 32       | 46.38%  |
| 3840x2160 (4K)     | 7        | 10.14%  |
| 1680x1050 (WSXGA+) | 4        | 5.8%    |
| 1280x1024 (SXGA)   | 4        | 5.8%    |
| Unknown            | 4        | 5.8%    |
| 1440x900 (WXGA+)   | 3        | 4.35%   |
| 1366x768 (WXGA)    | 3        | 4.35%   |
| 7680x2160          | 2        | 2.9%    |
| 3440x1440          | 2        | 2.9%    |
| 2560x1440 (QHD)    | 2        | 2.9%    |
| 1360x768           | 2        | 2.9%    |
| 5760x1080          | 1        | 1.45%   |
| 3840x1200          | 1        | 1.45%   |
| 1920x1200 (WUXGA)  | 1        | 1.45%   |
| 1600x900 (HD+)     | 1        | 1.45%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 10       | 14.29%  |
| Unknown | 9        | 12.86%  |
| 21      | 8        | 11.43%  |
| 24      | 7        | 10%     |
| 27      | 6        | 8.57%   |
| 19      | 6        | 8.57%   |
| 18      | 4        | 5.71%   |
| 22      | 3        | 4.29%   |
| 84      | 2        | 2.86%   |
| 34      | 2        | 2.86%   |
| 31      | 2        | 2.86%   |
| 20      | 2        | 2.86%   |
| 72      | 1        | 1.43%   |
| 54      | 1        | 1.43%   |
| 49      | 1        | 1.43%   |
| 46      | 1        | 1.43%   |
| 40      | 1        | 1.43%   |
| 36      | 1        | 1.43%   |
| 33      | 1        | 1.43%   |
| 28      | 1        | 1.43%   |
| 17      | 1        | 1.43%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 20       | 29.41%  |
| 401-500     | 20       | 29.41%  |
| Unknown     | 9        | 13.24%  |
| 701-800     | 4        | 5.88%   |
| 601-700     | 4        | 5.88%   |
| 351-400     | 3        | 4.41%   |
| 1501-2000   | 3        | 4.41%   |
| 1001-1500   | 3        | 4.41%   |
| 801-900     | 1        | 1.47%   |
| 301-350     | 1        | 1.47%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 43       | 66.15%  |
| Unknown | 9        | 13.85%  |
| 16/10   | 7        | 10.77%  |
| 5/4     | 4        | 6.15%   |
| 21/9    | 2        | 3.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 23       | 34.33%  |
| 151-200        | 10       | 14.93%  |
| Unknown        | 9        | 13.43%  |
| 301-350        | 6        | 8.96%   |
| More than 1000 | 5        | 7.46%   |
| 351-500        | 5        | 7.46%   |
| 141-150        | 5        | 7.46%   |
| 501-1000       | 3        | 4.48%   |
| 251-300        | 1        | 1.49%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 39       | 57.35%  |
| 101-120 | 10       | 14.71%  |
| Unknown | 9        | 13.24%  |
| 1-50    | 5        | 7.35%   |
| 121-160 | 3        | 4.41%   |
| 161-240 | 2        | 2.94%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 54       | 83.08%  |
| 2     | 8        | 12.31%  |
| 0     | 2        | 3.08%   |
| 3     | 1        | 1.54%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 36       | 40.45%  |
| Intel                           | 32       | 35.96%  |
| Qualcomm Atheros                | 5        | 5.62%   |
| Ralink Technology               | 3        | 3.37%   |
| TP-Link                         | 2        | 2.25%   |
| Microsoft                       | 2        | 2.25%   |
| Broadcom                        | 2        | 2.25%   |
| Xiaomi                          | 1        | 1.12%   |
| Ralink                          | 1        | 1.12%   |
| Qualcomm Atheros Communications | 1        | 1.12%   |
| Nvidia                          | 1        | 1.12%   |
| NetXen Incorporated             | 1        | 1.12%   |
| MediaTek                        | 1        | 1.12%   |
| Belkin Components               | 1        | 1.12%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 27       | 26.73%  |
| Intel I211 Gigabit Network Connection                                   | 10       | 9.9%    |
| Intel Wi-Fi 6 AX200                                                     | 5        | 4.95%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 3        | 2.97%   |
| Intel Ethernet Connection I217-LM                                       | 3        | 2.97%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 3        | 2.97%   |
| Intel 82567LM-3 Gigabit Network Connection                              | 3        | 2.97%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 2        | 1.98%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 2        | 1.98%   |
| Ralink RT5572 Wireless Adapter                                          | 2        | 1.98%   |
| Intel Wireless-AC 9260                                                  | 2        | 1.98%   |
| Intel Ethernet Controller I225-V                                        | 2        | 1.98%   |
| Intel Ethernet Connection (2) I219-V                                    | 2        | 1.98%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1        | 0.99%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                   | 1        | 0.99%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                               | 1        | 0.99%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                              | 1        | 0.99%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1        | 0.99%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1        | 0.99%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 1        | 0.99%   |
| Realtek RTL8125 2.5GbE Controller                                       | 1        | 0.99%   |
| Realtek 802.11ac NIC                                                    | 1        | 0.99%   |
| Ralink MT7601U Wireless Adapter                                         | 1        | 0.99%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                    | 1        | 0.99%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1        | 0.99%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1        | 0.99%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1        | 0.99%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 1        | 0.99%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 1        | 0.99%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1        | 0.99%   |
| Nvidia MCP61 Ethernet                                                   | 1        | 0.99%   |
| NetXen Incorporated NX3031 Multifunction 1/10-Gigabit Server Adapter    | 1        | 0.99%   |
| Microsoft Xbox Wireless Adapter for Windows                             | 1        | 0.99%   |
| Microsoft Xbox 360 Wireless Adapter                                     | 1        | 0.99%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 1        | 0.99%   |
| Intel Wireless 8265 / 8275                                              | 1        | 0.99%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1        | 0.99%   |
| Intel Ethernet Connection I217-V                                        | 1        | 0.99%   |
| Intel Ethernet Connection (2) I219-LM                                   | 1        | 0.99%   |
| Intel Ethernet Connection (2) I218-V                                    | 1        | 0.99%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 11       | 31.43%  |
| Realtek Semiconductor           | 9        | 25.71%  |
| Ralink Technology               | 3        | 8.57%   |
| Qualcomm Atheros                | 3        | 8.57%   |
| TP-Link                         | 2        | 5.71%   |
| Microsoft                       | 2        | 5.71%   |
| Ralink                          | 1        | 2.86%   |
| Qualcomm Atheros Communications | 1        | 2.86%   |
| MediaTek                        | 1        | 2.86%   |
| Broadcom                        | 1        | 2.86%   |
| Belkin Components               | 1        | 2.86%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 5        | 14.29%  |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 3        | 8.57%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 2        | 5.71%   |
| Ralink RT5572 Wireless Adapter                                          | 2        | 5.71%   |
| Intel Wireless-AC 9260                                                  | 2        | 5.71%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                   | 1        | 2.86%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                               | 1        | 2.86%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                              | 1        | 2.86%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1        | 2.86%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1        | 2.86%   |
| Realtek 802.11ac NIC                                                    | 1        | 2.86%   |
| Ralink MT7601U Wireless Adapter                                         | 1        | 2.86%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                    | 1        | 2.86%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1        | 2.86%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1        | 2.86%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1        | 2.86%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1        | 2.86%   |
| Microsoft Xbox Wireless Adapter for Windows                             | 1        | 2.86%   |
| Microsoft Xbox 360 Wireless Adapter                                     | 1        | 2.86%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 1        | 2.86%   |
| Intel Wireless 8265 / 8275                                              | 1        | 2.86%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1        | 2.86%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1        | 2.86%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 1        | 2.86%   |
| Broadcom BCM43217 802.11b/g/n                                           | 1        | 2.86%   |
| Belkin Components F5D8053 N Wireless USB Adapter v3000 [Ralink RT2870]  | 1        | 2.86%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 31       | 46.97%  |
| Intel                 | 29       | 43.94%  |
| Qualcomm Atheros      | 2        | 3.03%   |
| Xiaomi                | 1        | 1.52%   |
| Nvidia                | 1        | 1.52%   |
| NetXen Incorporated   | 1        | 1.52%   |
| Broadcom              | 1        | 1.52%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 27       | 40.91%  |
| Intel I211 Gigabit Network Connection                                | 10       | 15.15%  |
| Intel Ethernet Connection I217-LM                                    | 3        | 4.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 3        | 4.55%   |
| Intel 82567LM-3 Gigabit Network Connection                           | 3        | 4.55%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 2        | 3.03%   |
| Intel Ethernet Controller I225-V                                     | 2        | 3.03%   |
| Intel Ethernet Connection (2) I219-V                                 | 2        | 3.03%   |
| Xiaomi Mi/Redmi series (RNDIS)                                       | 1        | 1.52%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                             | 1        | 1.52%   |
| Realtek RTL8125 2.5GbE Controller                                    | 1        | 1.52%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                             | 1        | 1.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                        | 1        | 1.52%   |
| Nvidia MCP61 Ethernet                                                | 1        | 1.52%   |
| NetXen Incorporated NX3031 Multifunction 1/10-Gigabit Server Adapter | 1        | 1.52%   |
| Intel Ethernet Connection I217-V                                     | 1        | 1.52%   |
| Intel Ethernet Connection (2) I219-LM                                | 1        | 1.52%   |
| Intel Ethernet Connection (2) I218-V                                 | 1        | 1.52%   |
| Intel 82579V Gigabit Network Connection                              | 1        | 1.52%   |
| Intel 82578DC Gigabit Network Connection                             | 1        | 1.52%   |
| Intel 82574L Gigabit Network Connection                              | 1        | 1.52%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                      | 1        | 1.52%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 60       | 64.52%  |
| WiFi     | 33       | 35.48%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 49       | 75.38%  |
| WiFi     | 16       | 24.62%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 40       | 62.5%   |
| 2     | 18       | 28.13%  |
| 3     | 3        | 4.69%   |
| 0     | 2        | 3.13%   |
| 6     | 1        | 1.56%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 58       | 89.23%  |
| Yes  | 7        | 10.77%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 11       | 45.83%  |
| Cambridge Silicon Radio | 8        | 33.33%  |
| ASUSTek Computer        | 2        | 8.33%   |
| Realtek Semiconductor   | 1        | 4.17%   |
| MediaTek                | 1        | 4.17%   |
| IMC Networks            | 1        | 4.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 8        | 33.33%  |
| Intel AX200 Bluetooth                               | 5        | 20.83%  |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2        | 8.33%   |
| Realtek Bluetooth Radio                             | 1        | 4.17%   |
| MediaTek Wireless_Device                            | 1        | 4.17%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 4.17%   |
| Intel Bluetooth wireless interface                  | 1        | 4.17%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 4.17%   |
| Intel AX210 Bluetooth                               | 1        | 4.17%   |
| IMC Networks Bluetooth Module                       | 1        | 4.17%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 4.17%   |
| ASUS BCM20702A0                                     | 1        | 4.17%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 38       | 33.33%  |
| AMD                    | 32       | 28.07%  |
| Nvidia                 | 29       | 25.44%  |
| C-Media Electronics    | 5        | 4.39%   |
| Logitech               | 2        | 1.75%   |
| Plantronics            | 1        | 0.88%   |
| JMTek                  | 1        | 0.88%   |
| Generalplus Technology | 1        | 0.88%   |
| Focusrite-Novation     | 1        | 0.88%   |
| Creative Labs          | 1        | 0.88%   |
| Blue Microphones       | 1        | 0.88%   |
| ASUSTek Computer       | 1        | 0.88%   |
| Alesis                 | 1        | 0.88%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 8        | 6.02%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6        | 4.51%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5        | 3.76%   |
| Intel 200 Series PCH HD Audio                                              | 5        | 3.76%   |
| AMD Starship/Matisse HD Audio Controller                                   | 5        | 3.76%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 5        | 3.76%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 4        | 3.01%   |
| Nvidia GF108 High Definition Audio Controller                              | 4        | 3.01%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4        | 3.01%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4        | 3.01%   |
| AMD FCH Azalia Controller                                                  | 4        | 3.01%   |
| Nvidia GP108 High Definition Audio Controller                              | 3        | 2.26%   |
| Nvidia GP104 High Definition Audio Controller                              | 3        | 2.26%   |
| Nvidia GF119 HDMI Audio Controller                                         | 3        | 2.26%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3        | 2.26%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 3        | 2.26%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3        | 2.26%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 3        | 2.26%   |
| Nvidia GM204 High Definition Audio Controller                              | 2        | 1.5%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2        | 1.5%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 1.5%    |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 2        | 1.5%    |
| AMD Trinity HDMI Audio Controller                                          | 2        | 1.5%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2        | 1.5%    |
| AMD Family 17h/19h HD Audio Controller                                     | 2        | 1.5%    |
| Plantronics RIG 800HD                                                      | 1        | 0.75%   |
| Nvidia TU116 High Definition Audio Controller                              | 1        | 0.75%   |
| Nvidia TU106 High Definition Audio Controller                              | 1        | 0.75%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 0.75%   |
| Nvidia High Definition Audio Controller                                    | 1        | 0.75%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1        | 0.75%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 0.75%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 0.75%   |
| Nvidia GP102 HDMI Audio Controller                                         | 1        | 0.75%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 0.75%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1        | 0.75%   |
| Nvidia AD102 High Definition Audio Controller                              | 1        | 0.75%   |
| Logitech PRO X Wireless Gaming Headset                                     | 1        | 0.75%   |
| Logitech H600 [Wireless Headset]                                           | 1        | 0.75%   |
| JMTek USB PnP Audio Device                                                 | 1        | 0.75%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 5        | 27.78%  |
| Unknown             | 2        | 11.11%  |
| Samsung Electronics | 2        | 11.11%  |
| Crucial             | 2        | 11.11%  |
| Corsair             | 2        | 11.11%  |
| Team                | 1        | 5.56%   |
| SK hynix            | 1        | 5.56%   |
| PNY                 | 1        | 5.56%   |
| Micron Technology   | 1        | 5.56%   |
| G.Skill             | 1        | 5.56%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                   | 1        | 5%      |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                | 1        | 5%      |
| Team RAM TEAMGROUP-SD4-2666 16GB SODIMM DDR4 2667MT/s       | 1        | 5%      |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s      | 1        | 5%      |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s         | 1        | 5%      |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s         | 1        | 5%      |
| PNY RAM 8GBU1X08QJLL42-12-K 8GB SODIMM DDR4 3200MT/s        | 1        | 5%      |
| Micron RAM 16ATF1G64AZ-2G1A2 8GB DIMM DDR4 2400MT/s         | 1        | 5%      |
| Kingston RAM Module 8GB DIMM DDR4 2667MT/s                  | 1        | 5%      |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2400MT/s           | 1        | 5%      |
| Kingston RAM HX426C16FB2/8 8GB DIMM DDR4 2667MT/s           | 1        | 5%      |
| Kingston RAM 99P5471-002.A00LF 2GB DIMM DDR3 1600MT/s       | 1        | 5%      |
| Kingston RAM 99P5471-001.A01LF 2GB DIMM DDR3 1333MT/s       | 1        | 5%      |
| Kingston RAM 99P5471-001.A00LF 2GB DIMM DDR3 1333MT/s       | 1        | 5%      |
| Kingston RAM 9905584-023.A00LF 4GB DIMM DDR3 1600MT/s       | 1        | 5%      |
| G.Skill RAM F4-3600C16-8GVKC 8GB DIMM DDR4 3600MT/s         | 1        | 5%      |
| Crucial RAM BLT4G3D1869DT 4096MB DIMM DDR3 1333MT/s         | 1        | 5%      |
| Crucial RAM BL16G36C16U4W.M16FE1 16384MB DIMM DDR4 3733MT/s | 1        | 5%      |
| Corsair RAM CMT32GX5M2X6200C36 16GB DIMM DDR5 6400MT/s      | 1        | 5%      |
| Corsair RAM CMK64GX4M2D3000C16 32GB DIMM DDR4 3000MT/s      | 1        | 5%      |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Desktops | Percent |
|--------|----------|---------|
| DDR4   | 9        | 56.25%  |
| DDR3   | 4        | 25%     |
| SDRAM  | 1        | 6.25%   |
| LPDDR4 | 1        | 6.25%   |
| DDR5   | 1        | 6.25%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 12       | 85.71%  |
| SODIMM | 2        | 14.29%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 8        | 50%     |
| 4096  | 3        | 18.75%  |
| 32768 | 2        | 12.5%   |
| 16384 | 2        | 12.5%   |
| 2048  | 1        | 6.25%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 2667  | 3        | 17.65%  |
| 1600  | 3        | 17.65%  |
| 2400  | 2        | 11.76%  |
| 1333  | 2        | 11.76%  |
| 6400  | 1        | 5.88%   |
| 3733  | 1        | 5.88%   |
| 3600  | 1        | 5.88%   |
| 3500  | 1        | 5.88%   |
| 3200  | 1        | 5.88%   |
| 3000  | 1        | 5.88%   |
| 1867  | 1        | 5.88%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 3        | 60%     |
| Seiko Epson     | 1        | 20%     |
| Canon           | 1        | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Seiko Epson L120 Series            | 1        | 20%     |
| HP LaserJet 1300                   | 1        | 20%     |
| HP DeskJet 3830 series             | 1        | 20%     |
| HP DeskJet 2620 All-in-One Printer | 1        | 20%     |
| Canon PIXMA MG2500 Series          | 1        | 20%     |

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


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Logitech                    | 3        | 30%     |
| Samsung Electronics         | 1        | 10%     |
| Microdia                    | 1        | 10%     |
| KYE Systems (Mouse Systems) | 1        | 10%     |
| IMC Networks                | 1        | 10%     |
| Generalplus Technology      | 1        | 10%     |
| GEMBIRD                     | 1        | 10%     |
| Alcor Micro                 | 1        | 10%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920             | 2        | 20%     |
| Samsung Galaxy series, misc. (MTP mode) | 1        | 10%     |
| Microdia USB 2.0 Camera                 | 1        | 10%     |
| Logitech C922 Pro Stream Webcam         | 1        | 10%     |
| KYE Systems (Mouse Systems) Slim 1322AF | 1        | 10%     |
| IMC Networks XHC Camera                 | 1        | 10%     |
| Generalplus 808 Camera                  | 1        | 10%     |
| GEMBIRD USB2.0 PC CAMERA                | 1        | 10%     |
| Alcor Micro USB 2.0 PC Camera           | 1        | 10%     |

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
| 0     | 54       | 84.38%  |
| 1     | 9        | 14.06%  |
| 2     | 1        | 1.56%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Desktops | Percent |
|-----------------------|----------|---------|
| Net/wireless          | 6        | 60%     |
| Graphics card         | 2        | 20%     |
| Tv card               | 1        | 10%     |
| Multimedia controller | 1        | 10%     |

