Reborn OS - Tested Hardware & Statistics (Desktops)
---------------------------------------------------

A project to collect tested hardware configurations for Reborn OS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

| Vendor   | Model                   | Probe                                                      | Date         |
|----------|-------------------------|------------------------------------------------------------|--------------|
| ASUSTek  | ROG STRIX X570-I GAMING | [bc31f5f2bd](https://linux-hardware.org/?probe=bc31f5f2bd) | Jan 17, 2022 |
| ASUSTek  | PRIME H310M-K R2.0      | [7dba1540ad](https://linux-hardware.org/?probe=7dba1540ad) | Dec 06, 2021 |
| Medion   | Cattle24 1M             | [fd68d44a6a](https://linux-hardware.org/?probe=fd68d44a6a) | Oct 16, 2021 |
| Medion   | Cattle24 1M             | [dd4a0707ba](https://linux-hardware.org/?probe=dd4a0707ba) | May 19, 2021 |
| Dell     | 0200DY A01              | [426fc0381c](https://linux-hardware.org/?probe=426fc0381c) | May 08, 2021 |
| ASUSTek  | PRIME Z270-A            | [58fbf7553b](https://linux-hardware.org/?probe=58fbf7553b) | May 03, 2021 |
| ASUSTek  | PRIME Z270-A            | [27595787eb](https://linux-hardware.org/?probe=27595787eb) | Apr 26, 2021 |
| ASUSTek  | PRIME Z270-A            | [ec119e020d](https://linux-hardware.org/?probe=ec119e020d) | Apr 26, 2021 |
| HP       | 3048h                   | [b61eb90220](https://linux-hardware.org/?probe=b61eb90220) | Mar 20, 2021 |
| Gigabyte | X570 AORUS ELITE        | [0e8f323e0f](https://linux-hardware.org/?probe=0e8f323e0f) | Mar 18, 2021 |
| Gigabyte | X570 AORUS ELITE        | [a949911df6](https://linux-hardware.org/?probe=a949911df6) | Mar 18, 2021 |
| Gigabyte | B450 AORUS M            | [4a76fb93d3](https://linux-hardware.org/?probe=4a76fb93d3) | Mar 16, 2021 |
| Gigabyte | F2A85X-UP4              | [926ae13f69](https://linux-hardware.org/?probe=926ae13f69) | Mar 09, 2021 |
| ASUSTek  | ROG STRIX X570-I GAMING | [6c98f8666d](https://linux-hardware.org/?probe=6c98f8666d) | Feb 24, 2021 |
| ASRock   | X570 Taichi             | [e6476ce804](https://linux-hardware.org/?probe=e6476ce804) | Feb 05, 2021 |
| ASUSTek  | PRIME B450M-A           | [6042185966](https://linux-hardware.org/?probe=6042185966) | Feb 05, 2021 |
| ASUSTek  | PRIME B450M-A           | [8c4549fed4](https://linux-hardware.org/?probe=8c4549fed4) | Feb 05, 2021 |
| ASUSTek  | ROG STRIX B350-F GAMING | [0bb6c600d0](https://linux-hardware.org/?probe=0bb6c600d0) | Jan 25, 2021 |
| ASUSTek  | Q87M-E                  | [e95dad9e90](https://linux-hardware.org/?probe=e95dad9e90) | Jan 14, 2021 |
| MSI      | MEG X570 ACE            | [5b061048ce](https://linux-hardware.org/?probe=5b061048ce) | Jan 11, 2021 |
| Dell     | 02YYK5 A01              | [f50fd232e1](https://linux-hardware.org/?probe=f50fd232e1) | Jan 06, 2021 |
| MSI      | A320M PRO-VD/S V2       | [5d05e8d607](https://linux-hardware.org/?probe=5d05e8d607) | Jan 04, 2021 |
| ASUSTek  | PRIME H310M-K R2.0      | [ed3e1cc88a](https://linux-hardware.org/?probe=ed3e1cc88a) | Jan 04, 2021 |
| ASUSTek  | PRIME H310M-K R2.0      | [fb77017d74](https://linux-hardware.org/?probe=fb77017d74) | Jan 04, 2021 |
| ASUSTek  | P8B75-V                 | [a8ba58ce8d](https://linux-hardware.org/?probe=a8ba58ce8d) | Jan 03, 2021 |
| ASUSTek  | ROG STRIX B450-F GAMING | [60d4c9b8f1](https://linux-hardware.org/?probe=60d4c9b8f1) | Jan 02, 2021 |
| ASUSTek  | ROG STRIX B450-F GAMING | [bab82e261e](https://linux-hardware.org/?probe=bab82e261e) | Jan 02, 2021 |
| ASUSTek  | P7H55-M PRO             | [253b9e5126](https://linux-hardware.org/?probe=253b9e5126) | Jan 01, 2021 |
| ASUSTek  | P7H55-M PRO             | [016282f72d](https://linux-hardware.org/?probe=016282f72d) | Jan 01, 2021 |
| Dell     | 084J0R A00              | [45b5f0850b](https://linux-hardware.org/?probe=45b5f0850b) | Dec 30, 2020 |
| MSI      | FM2-A75MA-E35           | [c537d4854e](https://linux-hardware.org/?probe=c537d4854e) | Dec 14, 2020 |
| MSI      | FM2-A75MA-E35           | [f1f14b545e](https://linux-hardware.org/?probe=f1f14b545e) | Dec 13, 2020 |
| Dell     | 096JG8 A01              | [d0fc564ec7](https://linux-hardware.org/?probe=d0fc564ec7) | Dec 11, 2020 |
| Dell     | 096JG8 A01              | [2385d54def](https://linux-hardware.org/?probe=2385d54def) | Dec 09, 2020 |
| OEM      | G41 775 ICH7 8712       | [a135ed4b82](https://linux-hardware.org/?probe=a135ed4b82) | Nov 08, 2020 |
| OEM      | G41 775 ICH7 8712       | [151ca5d99e](https://linux-hardware.org/?probe=151ca5d99e) | Nov 08, 2020 |
| ASRock   | 960GM-VGS3 FX           | [5c51163253](https://linux-hardware.org/?probe=5c51163253) | Nov 05, 2020 |
| Gigabyte | EP43-UD3L               | [d6fd55eee0](https://linux-hardware.org/?probe=d6fd55eee0) | Nov 01, 2020 |
| Lenovo   | Board                   | [a1896b3549](https://linux-hardware.org/?probe=a1896b3549) | Oct 26, 2020 |
| ASUSTek  | PRIME H110M-P           | [5f4ab6b326](https://linux-hardware.org/?probe=5f4ab6b326) | Oct 18, 2020 |
| Foxconn  | H61S                    | [0fd947c658](https://linux-hardware.org/?probe=0fd947c658) | Oct 12, 2020 |
| Dell     | 096JG8 A01              | [337abf3073](https://linux-hardware.org/?probe=337abf3073) | Sep 30, 2020 |
| Huanan   | X79-8D VAA31            | [e0551a0a1c](https://linux-hardware.org/?probe=e0551a0a1c) | Sep 10, 2020 |
| Huanan   | X79-8D VAA31            | [66006c461d](https://linux-hardware.org/?probe=66006c461d) | Sep 06, 2020 |
| ASUSTek  | PRIME X370-PRO          | [524f57a765](https://linux-hardware.org/?probe=524f57a765) | Sep 06, 2020 |
| ASUSTek  | Z87-PLUS                | [3fe15728ad](https://linux-hardware.org/?probe=3fe15728ad) | Sep 06, 2020 |
| ASUSTek  | Z87-PLUS                | [e3f12cdd9b](https://linux-hardware.org/?probe=e3f12cdd9b) | Sep 05, 2020 |
| Dell     | 0Y2MRG A00              | [8af1b0565b](https://linux-hardware.org/?probe=8af1b0565b) | Sep 03, 2020 |
| Acer     | Aspire TC-885 V:1.1     | [c90b90e1a8](https://linux-hardware.org/?probe=c90b90e1a8) | Aug 21, 2020 |
| ASRock   | B450M Pro4              | [49170a6643](https://linux-hardware.org/?probe=49170a6643) | Aug 12, 2020 |
| ASUSTek  | M5A99X EVO              | [6aae8e8b65](https://linux-hardware.org/?probe=6aae8e8b65) | Aug 12, 2020 |
| MSI      | IONA                    | [0510d0f8ef](https://linux-hardware.org/?probe=0510d0f8ef) | Aug 06, 2020 |
| MSI      | IONA                    | [446e406f22](https://linux-hardware.org/?probe=446e406f22) | Aug 06, 2020 |
| ASUSTek  | P5KPL-AM SE             | [9c79ef0e1c](https://linux-hardware.org/?probe=9c79ef0e1c) | Jul 31, 2020 |
| ASUSTek  | P5KPL-AM SE             | [242b101828](https://linux-hardware.org/?probe=242b101828) | Jul 31, 2020 |
| ASUSTek  | STRIX H270F GAMING      | [52b8fcb9b0](https://linux-hardware.org/?probe=52b8fcb9b0) | Jul 26, 2020 |
| Gigabyte | Z87-HD3                 | [3eff281cc0](https://linux-hardware.org/?probe=3eff281cc0) | Jun 27, 2020 |
| Gigabyte | F2A75-D3H               | [59a8d5230f](https://linux-hardware.org/?probe=59a8d5230f) | Apr 09, 2020 |
| Pegatron | 2A99                    | [f01c0c56e7](https://linux-hardware.org/?probe=f01c0c56e7) | Apr 08, 2020 |
| ASRock   | X570 Phantom Gaming 4   | [97ffeec17e](https://linux-hardware.org/?probe=97ffeec17e) | Mar 23, 2020 |
| Lenovo   | MAHOBAY NOK             | [aaac6f9d4d](https://linux-hardware.org/?probe=aaac6f9d4d) | Mar 17, 2020 |
| ASRock   | X570 Phantom Gaming 4   | [63b8db155d](https://linux-hardware.org/?probe=63b8db155d) | Mar 02, 2020 |
| ASRock   | X570 Phantom Gaming 4   | [ed0b979970](https://linux-hardware.org/?probe=ed0b979970) | Mar 01, 2020 |
| ASRock   | X570 Phantom Gaming 4   | [cf634b4bfa](https://linux-hardware.org/?probe=cf634b4bfa) | Mar 01, 2020 |
| ASRock   | X570 Phantom Gaming 4   | [85c6480266](https://linux-hardware.org/?probe=85c6480266) | Mar 01, 2020 |
| ASRock   | H81M-HDS                | [0f180375d6](https://linux-hardware.org/?probe=0f180375d6) | Feb 25, 2020 |
| ASRock   | H81M-HDS                | [55c569be56](https://linux-hardware.org/?probe=55c569be56) | Feb 23, 2020 |
| ASRock   | H81M-HDS                | [98ae2a8227](https://linux-hardware.org/?probe=98ae2a8227) | Feb 22, 2020 |
| Gigabyte | GA-880GM-UD2H           | [b189e00138](https://linux-hardware.org/?probe=b189e00138) | Jan 16, 2020 |
| Gigabyte | GA-880GM-UD2H           | [486c4324ce](https://linux-hardware.org/?probe=486c4324ce) | Jan 16, 2020 |
| Gigabyte | GA-880GM-UD2H           | [ecb6ade802](https://linux-hardware.org/?probe=ecb6ade802) | Jan 16, 2020 |
| Intel    | DH55HC AAE70933-501     | [64266b67a2](https://linux-hardware.org/?probe=64266b67a2) | Dec 26, 2019 |
| HP       | 82F2 A01                | [0b8306e086](https://linux-hardware.org/?probe=0b8306e086) | Nov 18, 2019 |
| Dell     | 0773VG A00              | [adf2d5daca](https://linux-hardware.org/?probe=adf2d5daca) | Oct 31, 2019 |
| Dell     | 0773VG A00              | [05df3b6227](https://linux-hardware.org/?probe=05df3b6227) | Oct 31, 2019 |
| Dell     | 0773VG A00              | [2f3044da6d](https://linux-hardware.org/?probe=2f3044da6d) | Oct 31, 2019 |
| MSI      | C236A WORKSTATION       | [fcc16b2804](https://linux-hardware.org/?probe=fcc16b2804) | Oct 11, 2019 |
| MSI      | C236A WORKSTATION       | [f68bc503a9](https://linux-hardware.org/?probe=f68bc503a9) | Oct 11, 2019 |
| Gigabyte | H61M-DS2                | [2560a1cb4e](https://linux-hardware.org/?probe=2560a1cb4e) | Aug 28, 2019 |
| Gigabyte | H61M-DS2                | [b013eab87a](https://linux-hardware.org/?probe=b013eab87a) | Aug 27, 2019 |
| ASUSTek  | Z8NA-D6                 | [81c929f40d](https://linux-hardware.org/?probe=81c929f40d) | Jan 23, 2019 |
| ASUSTek  | P8Z77-V DELUXE          | [2180eb318a](https://linux-hardware.org/?probe=2180eb318a) | Dec 30, 2018 |
| ASRock   | H97M Pro4               | [2e4984a12a](https://linux-hardware.org/?probe=2e4984a12a) | Nov 27, 2018 |
| Lenovo   | Board                   | [812afde3d9](https://linux-hardware.org/?probe=812afde3d9) | Nov 21, 2018 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Desktops | Percent |
|----------------------|----------|---------|
| 5.10.3-arch1-1       | 4        | 6.56%   |
| 5.9.14-arch1-1       | 3        | 4.92%   |
| 5.7.12-arch1-1       | 3        | 4.92%   |
| 5.9.1-arch1-1        | 2        | 3.28%   |
| 5.8.7-arch1-1        | 2        | 3.28%   |
| 5.11.7-arch1-1       | 2        | 3.28%   |
| 5.10.4-arch2-1       | 2        | 3.28%   |
| 5.10.13-arch1-1      | 2        | 3.28%   |
| 5.9.6-arch1-1        | 1        | 1.64%   |
| 5.9.3-arch1-1        | 1        | 1.64%   |
| 5.9.2-arch1-1        | 1        | 1.64%   |
| 5.9.13-arch1-1       | 1        | 1.64%   |
| 5.9.12-arch1-1       | 1        | 1.64%   |
| 5.9.11-arch2-1       | 1        | 1.64%   |
| 5.8.6-arch1-1        | 1        | 1.64%   |
| 5.8.5-arch1-1        | 1        | 1.64%   |
| 5.8.14-arch1-1       | 1        | 1.64%   |
| 5.8.12-arch1-1       | 1        | 1.64%   |
| 5.8.1-arch1-1        | 1        | 1.64%   |
| 5.7.6-arch1-1-custom | 1        | 1.64%   |
| 5.7.11-arch1-1       | 1        | 1.64%   |
| 5.7.10-arch1-1       | 1        | 1.64%   |
| 5.6.3-arch1-1        | 1        | 1.64%   |
| 5.6.2-arch1-2        | 1        | 1.64%   |
| 5.5.9-arch1-2        | 1        | 1.64%   |
| 5.5.5-arch1-1        | 1        | 1.64%   |
| 5.5.2-arch1-1        | 1        | 1.64%   |
| 5.5.11-arch1-1       | 1        | 1.64%   |
| 5.4.6-arch3-1        | 1        | 1.64%   |
| 5.4.10-arch1-1       | 1        | 1.64%   |
| 5.3.7-arch1-2-ARCH   | 1        | 1.64%   |
| 5.3.5-arch1-1-ARCH   | 1        | 1.64%   |
| 5.3.11-arch1-1       | 1        | 1.64%   |
| 5.2.9-arch1-1-ARCH   | 1        | 1.64%   |
| 5.16.0-zen1-1-zen    | 1        | 1.64%   |
| 5.14.7-arch1-1       | 1        | 1.64%   |
| 5.12.4-arch1-2       | 1        | 1.64%   |
| 5.12.1-arch1-1       | 1        | 1.64%   |
| 5.11.6-arch1-1       | 1        | 1.64%   |
| 5.11.4-arch1-1       | 1        | 1.64%   |
| 5.11.16-arch1-1      | 1        | 1.64%   |
| 5.11.16-149-tkg-bmq  | 1        | 1.64%   |
| 5.11.1-arch1-1       | 1        | 1.64%   |
| 5.10.83-1-lts        | 1        | 1.64%   |
| 5.10.6-arch1-1       | 1        | 1.64%   |
| 4.20.3-arch1-1-ARCH  | 1        | 1.64%   |
| 4.19.2-arch1-1-ARCH  | 1        | 1.64%   |
| 4.19.12-arch1-1-ARCH | 1        | 1.64%   |
| 4.18.10-arch1-1-ARCH | 1        | 1.64%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10.3  | 4        | 6.67%   |
| 5.9.14  | 3        | 5%      |
| 5.7.12  | 3        | 5%      |
| 5.9.1   | 2        | 3.33%   |
| 5.8.7   | 2        | 3.33%   |
| 5.11.7  | 2        | 3.33%   |
| 5.10.4  | 2        | 3.33%   |
| 5.10.13 | 2        | 3.33%   |
| 5.9.6   | 1        | 1.67%   |
| 5.9.3   | 1        | 1.67%   |
| 5.9.2   | 1        | 1.67%   |
| 5.9.13  | 1        | 1.67%   |
| 5.9.12  | 1        | 1.67%   |
| 5.9.11  | 1        | 1.67%   |
| 5.8.6   | 1        | 1.67%   |
| 5.8.5   | 1        | 1.67%   |
| 5.8.14  | 1        | 1.67%   |
| 5.8.12  | 1        | 1.67%   |
| 5.8.1   | 1        | 1.67%   |
| 5.7.6   | 1        | 1.67%   |
| 5.7.11  | 1        | 1.67%   |
| 5.7.10  | 1        | 1.67%   |
| 5.6.3   | 1        | 1.67%   |
| 5.6.2   | 1        | 1.67%   |
| 5.5.9   | 1        | 1.67%   |
| 5.5.5   | 1        | 1.67%   |
| 5.5.2   | 1        | 1.67%   |
| 5.5.11  | 1        | 1.67%   |
| 5.4.6   | 1        | 1.67%   |
| 5.4.10  | 1        | 1.67%   |
| 5.3.7   | 1        | 1.67%   |
| 5.3.5   | 1        | 1.67%   |
| 5.3.11  | 1        | 1.67%   |
| 5.2.9   | 1        | 1.67%   |
| 5.16.0  | 1        | 1.67%   |
| 5.14.7  | 1        | 1.67%   |
| 5.12.4  | 1        | 1.67%   |
| 5.12.1  | 1        | 1.67%   |
| 5.11.6  | 1        | 1.67%   |
| 5.11.4  | 1        | 1.67%   |
| 5.11.16 | 1        | 1.67%   |
| 5.11.1  | 1        | 1.67%   |
| 5.10.83 | 1        | 1.67%   |
| 5.10.6  | 1        | 1.67%   |
| 4.20.3  | 1        | 1.67%   |
| 4.19.2  | 1        | 1.67%   |
| 4.19.12 | 1        | 1.67%   |
| 4.18.10 | 1        | 1.67%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.9     | 11       | 18.64%  |
| 5.10    | 9        | 15.25%  |
| 5.8     | 7        | 11.86%  |
| 5.7     | 6        | 10.17%  |
| 5.11    | 6        | 10.17%  |
| 5.5     | 4        | 6.78%   |
| 5.3     | 3        | 5.08%   |
| 5.6     | 2        | 3.39%   |
| 5.4     | 2        | 3.39%   |
| 5.12    | 2        | 3.39%   |
| 4.19    | 2        | 3.39%   |
| 5.2     | 1        | 1.69%   |
| 5.16    | 1        | 1.69%   |
| 5.14    | 1        | 1.69%   |
| 4.20    | 1        | 1.69%   |
| 4.18    | 1        | 1.69%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 56       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 11       | 19.64%  |
| X-Cinnamon | 9        | 16.07%  |
| KDE        | 8        | 14.29%  |
| Deepin     | 7        | 12.5%   |
| Unknown    | 7        | 12.5%   |
| XFCE       | 6        | 10.71%  |
| LXQt       | 2        | 3.57%   |
| Budgie     | 2        | 3.57%   |
| MATE       | 1        | 1.79%   |
| KDE5       | 1        | 1.79%   |
| i3         | 1        | 1.79%   |
| Cinnamon   | 1        | 1.79%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 49       | 87.5%   |
| Wayland | 7        | 12.5%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 50       | 87.72%  |
| TDM     | 4        | 7.02%   |
| GDM     | 2        | 3.51%   |
| SDDM    | 1        | 1.75%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 21       | 37.5%   |
| Unknown | 7        | 12.5%   |
| es_ES   | 5        | 8.93%   |
| en_GB   | 5        | 8.93%   |
| de_DE   | 5        | 8.93%   |
| es_AR   | 2        | 3.57%   |
| en_AU   | 2        | 3.57%   |
| ru_UA   | 1        | 1.79%   |
| ru_RU   | 1        | 1.79%   |
| pt_BR   | 1        | 1.79%   |
| fr_FR   | 1        | 1.79%   |
| es_PA   | 1        | 1.79%   |
| en_PH   | 1        | 1.79%   |
| en_CA   | 1        | 1.79%   |
| el_GR   | 1        | 1.79%   |
| de_AT   | 1        | 1.79%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 41       | 73.21%  |
| EFI  | 15       | 26.79%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 41       | 73.21%  |
| Unknown | 8        | 14.29%  |
| Tmpfs   | 4        | 7.14%   |
| Xfs     | 3        | 5.36%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 49       | 87.5%   |
| GPT     | 6        | 10.71%  |
| MBR     | 1        | 1.79%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 52       | 92.86%  |
| Yes       | 4        | 7.14%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 52       | 91.23%  |
| Yes       | 5        | 8.77%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 17       | 30.36%  |
| Gigabyte Technology | 8        | 14.29%  |
| ASRock              | 7        | 12.5%   |
| MSI                 | 6        | 10.71%  |
| Dell                | 6        | 10.71%  |
| Lenovo              | 3        | 5.36%   |
| Hewlett-Packard     | 2        | 3.57%   |
| Pegatron            | 1        | 1.79%   |
| OEM                 | 1        | 1.79%   |
| Medion              | 1        | 1.79%   |
| Intel               | 1        | 1.79%   |
| Huanan              | 1        | 1.79%   |
| Foxconn             | 1        | 1.79%   |
| Acer                | 1        | 1.79%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| MSI MS-7721                     | 2        | 3.57%   |
| ASRock X570 Phantom Gaming 4    | 2        | 3.57%   |
| Pegatron CQ3476L                | 1        | 1.79%   |
| OEM G41 775 ICH7 8712           | 1        | 1.79%   |
| MSI WK711AA-ACB HPE-110ru       | 1        | 1.79%   |
| MSI MS-7C35                     | 1        | 1.79%   |
| MSI MS-7A36                     | 1        | 1.79%   |
| MSI MS-7998                     | 1        | 1.79%   |
| Medion P961x                    | 1        | 1.79%   |
| Lenovo ThinkCentre M92 32071F5  | 1        | 1.79%   |
| Lenovo ThinkCentre M91p 0266RZ1 | 1        | 1.79%   |
| Lenovo ThinkCentre M58 6258WCY  | 1        | 1.79%   |
| Intel DH55HC AAE70933-501       | 1        | 1.79%   |
| Huanan X79-8D VAA31             | 1        | 1.79%   |
| HP Pavilion Desktop PC 570-p0XX | 1        | 1.79%   |
| HP Compaq 6000 Pro MT PC        | 1        | 1.79%   |
| Gigabyte Z87-HD3                | 1        | 1.79%   |
| Gigabyte X570 AORUS ELITE       | 1        | 1.79%   |
| Gigabyte H61M-DS2               | 1        | 1.79%   |
| Gigabyte GA-880GM-UD2H          | 1        | 1.79%   |
| Gigabyte F2A85X-UP4             | 1        | 1.79%   |
| Gigabyte F2A75-D3H              | 1        | 1.79%   |
| Gigabyte EP43-UD3L              | 1        | 1.79%   |
| Gigabyte B450 AORUS M           | 1        | 1.79%   |
| Foxconn H61S                    | 1        | 1.79%   |
| Dell XPS 8300                   | 1        | 1.79%   |
| Dell OptiPlex 780               | 1        | 1.79%   |
| Dell OptiPlex 7040              | 1        | 1.79%   |
| Dell OptiPlex 7020              | 1        | 1.79%   |
| Dell OptiPlex 7010              | 1        | 1.79%   |
| Dell Inspiron 660               | 1        | 1.79%   |
| ASUS Z8NA-D6                    | 1        | 1.79%   |
| ASUS STRIX H270F GAMING         | 1        | 1.79%   |
| ASUS ROG STRIX X570-I GAMING    | 1        | 1.79%   |
| ASUS ROG STRIX B450-F GAMING    | 1        | 1.79%   |
| ASUS ROG STRIX B350-F GAMING    | 1        | 1.79%   |
| ASUS Q87M-XA                    | 1        | 1.79%   |
| ASUS PRIME Z270-A               | 1        | 1.79%   |
| ASUS PRIME X370-PRO             | 1        | 1.79%   |
| ASUS PRIME H310M-K R2.0         | 1        | 1.79%   |
| ASUS PRIME H110M-P              | 1        | 1.79%   |
| ASUS PRIME B450M-A              | 1        | 1.79%   |
| ASUS P8Z77-V DELUXE             | 1        | 1.79%   |
| ASUS P8B75-V                    | 1        | 1.79%   |
| ASUS P7H55-M PRO                | 1        | 1.79%   |
| ASUS P5KPL-AM SE                | 1        | 1.79%   |
| ASUS M5A99X EVO                 | 1        | 1.79%   |
| ASUS All Series                 | 1        | 1.79%   |
| ASRock X570 Taichi              | 1        | 1.79%   |
| ASRock H97M Pro4                | 1        | 1.79%   |
| ASRock H81M-HDS                 | 1        | 1.79%   |
| ASRock B450M Pro4               | 1        | 1.79%   |
| ASRock 960GM-VGS3 FX            | 1        | 1.79%   |
| Acer Aspire TC-885              | 1        | 1.79%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 5        | 8.93%   |
| Dell OptiPlex          | 4        | 7.14%   |
| Lenovo ThinkCentre     | 3        | 5.36%   |
| ASUS ROG               | 3        | 5.36%   |
| ASRock X570            | 3        | 5.36%   |
| MSI MS-7721            | 2        | 3.57%   |
| Pegatron CQ3476L       | 1        | 1.79%   |
| OEM G41                | 1        | 1.79%   |
| MSI WK711AA-ACB        | 1        | 1.79%   |
| MSI MS-7C35            | 1        | 1.79%   |
| MSI MS-7A36            | 1        | 1.79%   |
| MSI MS-7998            | 1        | 1.79%   |
| Medion P961x           | 1        | 1.79%   |
| Intel DH55HC           | 1        | 1.79%   |
| Huanan X79-8D          | 1        | 1.79%   |
| HP Pavilion            | 1        | 1.79%   |
| HP Compaq              | 1        | 1.79%   |
| Gigabyte Z87-HD3       | 1        | 1.79%   |
| Gigabyte X570          | 1        | 1.79%   |
| Gigabyte H61M-DS2      | 1        | 1.79%   |
| Gigabyte GA-880GM-UD2H | 1        | 1.79%   |
| Gigabyte F2A85X-UP4    | 1        | 1.79%   |
| Gigabyte F2A75-D3H     | 1        | 1.79%   |
| Gigabyte EP43-UD3L     | 1        | 1.79%   |
| Gigabyte B450          | 1        | 1.79%   |
| Foxconn H61S           | 1        | 1.79%   |
| Dell XPS               | 1        | 1.79%   |
| Dell Inspiron          | 1        | 1.79%   |
| ASUS Z8NA-D6           | 1        | 1.79%   |
| ASUS STRIX             | 1        | 1.79%   |
| ASUS Q87M-XA           | 1        | 1.79%   |
| ASUS P8Z77-V           | 1        | 1.79%   |
| ASUS P8B75-V           | 1        | 1.79%   |
| ASUS P7H55-M           | 1        | 1.79%   |
| ASUS P5KPL-AM          | 1        | 1.79%   |
| ASUS M5A99X            | 1        | 1.79%   |
| ASUS All               | 1        | 1.79%   |
| ASRock H97M            | 1        | 1.79%   |
| ASRock H81M-HDS        | 1        | 1.79%   |
| ASRock B450M           | 1        | 1.79%   |
| ASRock 960GM-VGS3      | 1        | 1.79%   |
| Acer Aspire            | 1        | 1.79%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 9        | 16.07%  |
| 2012 | 8        | 14.29%  |
| 2013 | 7        | 12.5%   |
| 2018 | 6        | 10.71%  |
| 2010 | 6        | 10.71%  |
| 2009 | 5        | 8.93%   |
| 2017 | 4        | 7.14%   |
| 2016 | 4        | 7.14%   |
| 2014 | 3        | 5.36%   |
| 2011 | 2        | 3.57%   |
| 2015 | 1        | 1.79%   |
| 2008 | 1        | 1.79%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 56       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 56       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 56       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 15       | 25.86%  |
| 8.01-16.0   | 15       | 25.86%  |
| 4.01-8.0    | 12       | 20.69%  |
| 32.01-64.0  | 9        | 15.52%  |
| 3.01-4.0    | 5        | 8.62%   |
| 64.01-256.0 | 1        | 1.72%   |
| 1.01-2.0    | 1        | 1.72%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 24       | 40.68%  |
| 2.01-3.0  | 18       | 30.51%  |
| 3.01-4.0  | 7        | 11.86%  |
| 4.01-8.0  | 6        | 10.17%  |
| 8.01-16.0 | 2        | 3.39%   |
| 0.51-1.0  | 2        | 3.39%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 19       | 33.33%  |
| 2      | 18       | 31.58%  |
| 3      | 8        | 14.04%  |
| 4      | 7        | 12.28%  |
| 0      | 2        | 3.51%   |
| 7      | 1        | 1.75%   |
| 6      | 1        | 1.75%   |
| 5      | 1        | 1.75%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 29       | 50.88%  |
| No        | 28       | 49.12%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 52       | 92.86%  |
| No        | 4        | 7.14%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 28       | 50%     |
| No        | 28       | 50%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 37       | 66.07%  |
| Yes       | 19       | 33.93%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 14       | 25%     |
| Germany     | 6        | 10.71%  |
| UK          | 5        | 8.93%   |
| Spain       | 5        | 8.93%   |
| Canada      | 4        | 7.14%   |
| Netherlands | 3        | 5.36%   |
| Thailand    | 2        | 3.57%   |
| Panama      | 2        | 3.57%   |
| India       | 2        | 3.57%   |
| Greece      | 2        | 3.57%   |
| Argentina   | 2        | 3.57%   |
| Ukraine     | 1        | 1.79%   |
| Russia      | 1        | 1.79%   |
| Philippines | 1        | 1.79%   |
| Hungary     | 1        | 1.79%   |
| Colombia    | 1        | 1.79%   |
| Brazil      | 1        | 1.79%   |
| Azerbaijan  | 1        | 1.79%   |
| Austria     | 1        | 1.79%   |
| Australia   | 1        | 1.79%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Miami               | 2        | 3.39%   |
| Lelystad            | 2        | 3.39%   |
| Essen               | 2        | 3.39%   |
| David               | 2        | 3.39%   |
| Cologne             | 2        | 3.39%   |
| Athens              | 2        | 3.39%   |
| Zutphen             | 1        | 1.69%   |
| Winsted             | 1        | 1.69%   |
| Watford             | 1        | 1.69%   |
| Villa Martelli      | 1        | 1.69%   |
| Vienna              | 1        | 1.69%   |
| Ullastrell          | 1        | 1.69%   |
| SГЈo Paulo        | 1        | 1.69%   |
| SzekszГЎrd        | 1        | 1.69%   |
| Sydney              | 1        | 1.69%   |
| Surrey              | 1        | 1.69%   |
| Southampton         | 1        | 1.69%   |
| Smithfield          | 1        | 1.69%   |
| Seville             | 1        | 1.69%   |
| Sattahip            | 1        | 1.69%   |
| San Miguel          | 1        | 1.69%   |
| Salt Lake City      | 1        | 1.69%   |
| Reno                | 1        | 1.69%   |
| Queens              | 1        | 1.69%   |
| Phoenix             | 1        | 1.69%   |
| Novosibirsk         | 1        | 1.69%   |
| North Fort Myers    | 1        | 1.69%   |
| Newcastle           | 1        | 1.69%   |
| Nava de la Asuncion | 1        | 1.69%   |
| Mascouche           | 1        | 1.69%   |
| Kyiv                | 1        | 1.69%   |
| Kentville           | 1        | 1.69%   |
| Irun                | 1        | 1.69%   |
| Ibiza Town          | 1        | 1.69%   |
| Hanau               | 1        | 1.69%   |
| Gosport             | 1        | 1.69%   |
| Ernakulam           | 1        | 1.69%   |
| DГјsseldorf       | 1        | 1.69%   |
| Derby               | 1        | 1.69%   |
| Delhi               | 1        | 1.69%   |
| Cottbus             | 1        | 1.69%   |
| Caddo Mills         | 1        | 1.69%   |
| Buffalo             | 1        | 1.69%   |
| Bridgend            | 1        | 1.69%   |
| Bowling Green       | 1        | 1.69%   |
| Bournemouth         | 1        | 1.69%   |
| Boquete             | 1        | 1.69%   |
| BogotГЎ           | 1        | 1.69%   |
| Boca de la Zanja    | 1        | 1.69%   |
| Bluefield           | 1        | 1.69%   |
| Bastrop             | 1        | 1.69%   |
| Ban Ang Sila        | 1        | 1.69%   |
| Baku                | 1        | 1.69%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 25       | 31     | 23.15%  |
| Seagate             | 16       | 22     | 14.81%  |
| Samsung Electronics | 14       | 16     | 12.96%  |
| Toshiba             | 8        | 9      | 7.41%   |
| Phison              | 6        | 7      | 5.56%   |
| Hitachi             | 5        | 5      | 4.63%   |
| Kingston            | 4        | 4      | 3.7%    |
| Crucial             | 4        | 5      | 3.7%    |
| Sandisk             | 3        | 4      | 2.78%   |
| Unknown             | 2        | 2      | 1.85%   |
| PNY                 | 2        | 2      | 1.85%   |
| Intel               | 2        | 2      | 1.85%   |
| ZOTAC               | 1        | 1      | 0.93%   |
| SPCC                | 1        | 1      | 0.93%   |
| Phison Electronics  | 1        | 2      | 0.93%   |
| Patriot             | 1        | 1      | 0.93%   |
| OCZ                 | 1        | 2      | 0.93%   |
| KingSpec            | 1        | 1      | 0.93%   |
| JMicron             | 1        | 1      | 0.93%   |
| HGST                | 1        | 1      | 0.93%   |
| Hewlett-Packard     | 1        | 2      | 0.93%   |
| Gigabyte Technology | 1        | 2      | 0.93%   |
| Emtec               | 1        | 1      | 0.93%   |
| DREVO               | 1        | 1      | 0.93%   |
| Dell                | 1        | 1      | 0.93%   |
| ASMT                | 1        | 1      | 0.93%   |
| AMD                 | 1        | 1      | 0.93%   |
| addlink             | 1        | 1      | 0.93%   |
| A-DATA Technology   | 1        | 1      | 0.93%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Samsung SSD 860 EVO 500GB          | 3        | 2.48%   |
| WDC WD10EZEX-08WN4A0 1TB           | 2        | 1.65%   |
| WDC WD1002FAEX-00Z3A0 1TB          | 2        | 1.65%   |
| WDC WD1001FALS-403AA0 1TB          | 2        | 1.65%   |
| Toshiba DT01ACA100 1TB             | 2        | 1.65%   |
| Seagate ST3500312CS 500GB          | 2        | 1.65%   |
| Seagate ST2000DM006-2DM164 2TB     | 2        | 1.65%   |
| Seagate ST1000DM003-1CH162 1TB     | 2        | 1.65%   |
| Samsung SSD 850 EVO 500GB          | 2        | 1.65%   |
| PNY CS900 120GB SSD                | 2        | 1.65%   |
| Phison NVMe SSD Drive 960GB        | 2        | 1.65%   |
| Phison NVMe SSD Drive 240GB        | 2        | 1.65%   |
| Phison NVMe SSD Drive 1TB          | 2        | 1.65%   |
| ZOTAC ZTSSD-S11-120G-P 120GB       | 1        | 0.83%   |
| WDC WDS500G2X0C-00L350 500GB       | 1        | 0.83%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 1        | 0.83%   |
| WDC WD6400AAKS-22A7B0 640GB        | 1        | 0.83%   |
| WDC WD6400AAKS-00A7B2 640GB        | 1        | 0.83%   |
| WDC WD5000LPVX-00V0TT0 500GB       | 1        | 0.83%   |
| WDC WD5000AZLX-00JKKA0 500GB       | 1        | 0.83%   |
| WDC WD5000AVDS-63U7B1 500GB        | 1        | 0.83%   |
| WDC WD5000AAKX-753CA1 500GB        | 1        | 0.83%   |
| WDC WD5000AADS-00S9B0 500GB        | 1        | 0.83%   |
| WDC WD3200AAKS-00UU3A0 320GB       | 1        | 0.83%   |
| WDC WD30PURX-64P6ZY0 3TB           | 1        | 0.83%   |
| WDC WD2500JS-00MHB0 250GB          | 1        | 0.83%   |
| WDC WD20EZRX-00D8PB0 2TB           | 1        | 0.83%   |
| WDC WD20EURX-63T0FY0 2TB           | 1        | 0.83%   |
| WDC WD2003FZEX-00SRLA0 2TB         | 1        | 0.83%   |
| WDC WD2003FYPS-27Y2B0 2TB          | 1        | 0.83%   |
| WDC WD15EADS-65P8B1 1TB            | 1        | 0.83%   |
| WDC WD10EZRX-00L4HB0 1TB           | 1        | 0.83%   |
| WDC WD10EZEX-21WN4A0 1TB           | 1        | 0.83%   |
| WDC WD10EZEX-00BN5A0 1TB           | 1        | 0.83%   |
| WDC WD10EARS-00Y5B1 1TB            | 1        | 0.83%   |
| WDC WD10EADS-65M2B1 1TB            | 1        | 0.83%   |
| WDC WD1002FAEX-00Y9A0 1TB          | 1        | 0.83%   |
| Unknown SD/MMC/MS PRO 64GB         | 1        | 0.83%   |
| Unknown NVMe SSD Drive 512GB       | 1        | 0.83%   |
| Toshiba TL100 240GB SSD            | 1        | 0.83%   |
| Toshiba THNSN5512GPUK NVMe 512GB   | 1        | 0.83%   |
| Toshiba NVMe SSD Drive 512GB       | 1        | 0.83%   |
| Toshiba MK5075GSX 500GB            | 1        | 0.83%   |
| Toshiba MK3256GSY 320GB            | 1        | 0.83%   |
| Toshiba HDWD120 2TB                | 1        | 0.83%   |
| SPCC M.2 PCIe SSD 1TB              | 1        | 0.83%   |
| Seagate ST500NM0011 500GB          | 1        | 0.83%   |
| Seagate ST500LM030-2E717D 500GB    | 1        | 0.83%   |
| Seagate ST500DM002-1BD142 500GB    | 1        | 0.83%   |
| Seagate ST4000DM004-2CV104 4TB     | 1        | 0.83%   |
| Seagate ST3500418AS 500GB          | 1        | 0.83%   |
| Seagate ST3250824AS 250GB          | 1        | 0.83%   |
| Seagate ST3160023AS 160GB          | 1        | 0.83%   |
| Seagate ST3000LM024-2AN17R 3TB     | 1        | 0.83%   |
| Seagate ST3000DM001-1ER166 3TB     | 1        | 0.83%   |
| Seagate ST2000DX002-2DV164 2TB     | 1        | 0.83%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1        | 0.83%   |
| Seagate ST1000LM014-1EJ164 1TB     | 1        | 0.83%   |
| Seagate ST1000DM010-2EP102 1TB     | 1        | 0.83%   |
| Seagate ST1000DM003-1ER162 1TB     | 1        | 0.83%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 23       | 28     | 41.82%  |
| Seagate             | 16       | 22     | 29.09%  |
| Toshiba             | 5        | 5      | 9.09%   |
| Hitachi             | 5        | 5      | 9.09%   |
| Samsung Electronics | 2        | 2      | 3.64%   |
| Unknown             | 1        | 1      | 1.82%   |
| JMicron             | 1        | 1      | 1.82%   |
| HGST                | 1        | 1      | 1.82%   |
| ASMT                | 1        | 1      | 1.82%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 11       | 11     | 32.35%  |
| Kingston            | 4        | 4      | 11.76%  |
| Crucial             | 3        | 4      | 8.82%   |
| SanDisk             | 2        | 3      | 5.88%   |
| PNY                 | 2        | 2      | 5.88%   |
| ZOTAC               | 1        | 1      | 2.94%   |
| WDC                 | 1        | 1      | 2.94%   |
| Toshiba             | 1        | 1      | 2.94%   |
| Patriot             | 1        | 1      | 2.94%   |
| OCZ                 | 1        | 2      | 2.94%   |
| KingSpec            | 1        | 1      | 2.94%   |
| Hewlett-Packard     | 1        | 2      | 2.94%   |
| Gigabyte Technology | 1        | 2      | 2.94%   |
| Emtec               | 1        | 1      | 2.94%   |
| DREVO               | 1        | 1      | 2.94%   |
| AMD                 | 1        | 1      | 2.94%   |
| A-DATA Technology   | 1        | 1      | 2.94%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 39       | 66     | 45.88%  |
| SSD     | 27       | 39     | 31.76%  |
| NVMe    | 17       | 23     | 20%     |
| Unknown | 2        | 2      | 2.35%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 51       | 101    | 69.86%  |
| NVMe | 17       | 23     | 23.29%  |
| SAS  | 5        | 6      | 6.85%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 39       | 59     | 50.65%  |
| 0.51-1.0   | 27       | 31     | 35.06%  |
| 1.01-2.0   | 6        | 8      | 7.79%   |
| 2.01-3.0   | 3        | 4      | 3.9%    |
| 3.01-4.0   | 1        | 1      | 1.3%    |
| 4.01-10.0  | 1        | 2      | 1.3%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 15       | 26.79%  |
| 251-500        | 10       | 17.86%  |
| 101-250        | 10       | 17.86%  |
| More than 3000 | 6        | 10.71%  |
| 1001-2000      | 4        | 7.14%   |
| 51-100         | 4        | 7.14%   |
| Unknown        | 3        | 5.36%   |
| 21-50          | 2        | 3.57%   |
| 2001-3000      | 2        | 3.57%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 21-50     | 19       | 32.2%   |
| 1-20      | 19       | 32.2%   |
| 251-500   | 4        | 6.78%   |
| 51-100    | 4        | 6.78%   |
| 2001-3000 | 3        | 5.08%   |
| 101-250   | 3        | 5.08%   |
| 501-1000  | 3        | 5.08%   |
| Unknown   | 3        | 5.08%   |
| 1001-2000 | 1        | 1.69%   |

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
| Detected | 49       | 108    | 89.09%  |
| Works    | 6        | 22     | 10.91%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 35       | 45.45%  |
| AMD                          | 19       | 24.68%  |
| Phison Electronics           | 8        | 10.39%  |
| Samsung Electronics          | 4        | 5.19%   |
| JMicron Technology           | 3        | 3.9%    |
| Toshiba America Info Systems | 2        | 2.6%    |
| Sandisk                      | 2        | 2.6%    |
| Nvidia                       | 1        | 1.3%    |
| Micron/Crucial Technology    | 1        | 1.3%    |
| ASMedia Technology           | 1        | 1.3%    |
| ADATA Technology             | 1        | 1.3%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 16       | 15.38%  |
| Phison E12 NVMe Controller                                                              | 5        | 4.81%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4        | 3.85%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 4        | 3.85%   |
| AMD 400 Series Chipset SATA Controller                                                  | 4        | 3.85%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3        | 2.88%   |
| Intel SATA Controller [RAID mode]                                                       | 3        | 2.88%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3        | 2.88%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 3        | 2.88%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 3        | 2.88%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3        | 2.88%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 2        | 1.92%   |
| JMicron JMB368 IDE controller                                                           | 2        | 1.92%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2        | 1.92%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 2        | 1.92%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 2        | 1.92%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2        | 1.92%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 2        | 1.92%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]           | 2        | 1.92%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 1.92%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 1.92%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2        | 1.92%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 2        | 1.92%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 2        | 1.92%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2        | 1.92%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                                    | 1        | 0.96%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller        | 1        | 0.96%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 1        | 0.96%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1        | 0.96%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 0.96%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1        | 0.96%   |
| Phison E7 NVMe Controller                                                               | 1        | 0.96%   |
| Nvidia MCP61 SATA Controller                                                            | 1        | 0.96%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 1        | 0.96%   |
| JMicron JMB362 SATA Controller                                                          | 1        | 0.96%   |
| Intel SSD 660P Series                                                                   | 1        | 0.96%   |
| Intel SSD 600P Series                                                                   | 1        | 0.96%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1        | 0.96%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1        | 0.96%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 1        | 0.96%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                    | 1        | 0.96%   |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode]           | 1        | 0.96%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 1        | 0.96%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 1        | 0.96%   |
| Intel 5 Series/3400 Series Chipset PT IDER Controller                                   | 1        | 0.96%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 1        | 0.96%   |
| AMD X370 Series Chipset SATA Controller                                                 | 1        | 0.96%   |
| AMD FCH SATA Controller D                                                               | 1        | 0.96%   |
| AMD 300 Series Chipset SATA Controller                                                  | 1        | 0.96%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 1        | 0.96%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 40       | 51.28%  |
| IDE  | 18       | 23.08%  |
| NVMe | 17       | 21.79%  |
| RAID | 3        | 3.85%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 35       | 62.5%   |
| AMD    | 21       | 37.5%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 4        | 7.02%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 3.51%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 2        | 3.51%   |
| AMD Ryzen 5 3600 6-Core Processor           | 2        | 3.51%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 2        | 3.51%   |
| AMD A4-5300 APU with Radeon HD Graphics     | 2        | 3.51%   |
| AMD A10-5800K APU with Radeon HD Graphics   | 2        | 3.51%   |
| Intel Xeon CPU E5530 @ 2.40GHz              | 1        | 1.75%   |
| Intel Xeon CPU E5-2697 v2 @ 2.70GHz         | 1        | 1.75%   |
| Intel Xeon CPU E3-1270 V2 @ 3.50GHz         | 1        | 1.75%   |
| Intel Xeon CPU E3-1225 v5 @ 3.30GHz         | 1        | 1.75%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 1        | 1.75%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 1        | 1.75%   |
| Intel Pentium CPU G3258 @ 3.20GHz           | 1        | 1.75%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 1.75%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1        | 1.75%   |
| Intel Core i7-4770S CPU @ 3.10GHz           | 1        | 1.75%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1        | 1.75%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 1        | 1.75%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 1        | 1.75%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1        | 1.75%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 1        | 1.75%   |
| Intel Core i5-6500T CPU @ 2.50GHz           | 1        | 1.75%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 1        | 1.75%   |
| Intel Core i5-4570T CPU @ 2.90GHz           | 1        | 1.75%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 1        | 1.75%   |
| Intel Core i5-3340 CPU @ 3.10GHz            | 1        | 1.75%   |
| Intel Core i5-2400S CPU @ 2.50GHz           | 1        | 1.75%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 1        | 1.75%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 1        | 1.75%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 1        | 1.75%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 1        | 1.75%   |
| Intel Core i3 CPU 540 @ 3.07GHz             | 1        | 1.75%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 1        | 1.75%   |
| Intel Core 2 Duo CPU E7200 @ 2.53GHz        | 1        | 1.75%   |
| Intel Core 2 Duo CPU E6750 @ 2.66GHz        | 1        | 1.75%   |
| Intel Celeron CPU G3930 @ 2.90GHz           | 1        | 1.75%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 1        | 1.75%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 1        | 1.75%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 1        | 1.75%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 1        | 1.75%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 1        | 1.75%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 1        | 1.75%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 1        | 1.75%   |
| AMD Phenom II X4 955 Processor              | 1        | 1.75%   |
| AMD FX-9590 Eight-Core Processor            | 1        | 1.75%   |
| AMD FX-6300 Six-Core Processor              | 1        | 1.75%   |
| AMD Athlon II X2 255 Processor              | 1        | 1.75%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 14       | 24.56%  |
| Intel Core 2 Duo        | 7        | 12.28%  |
| AMD Ryzen 5             | 6        | 10.53%  |
| Intel Core i7           | 5        | 8.77%   |
| AMD Ryzen 7             | 5        | 8.77%   |
| Intel Xeon              | 4        | 7.02%   |
| Intel Pentium           | 2        | 3.51%   |
| Intel Core i3           | 2        | 3.51%   |
| AMD FX                  | 2        | 3.51%   |
| AMD A4                  | 2        | 3.51%   |
| AMD A10                 | 2        | 3.51%   |
| Intel Pentium Dual-Core | 1        | 1.75%   |
| Intel Celeron           | 1        | 1.75%   |
| AMD Ryzen 9             | 1        | 1.75%   |
| AMD Ryzen 3             | 1        | 1.75%   |
| AMD Phenom II X4        | 1        | 1.75%   |
| AMD Athlon II X2        | 1        | 1.75%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 20       | 35.71%  |
| 2      | 17       | 30.36%  |
| 6      | 8        | 14.29%  |
| 8      | 6        | 10.71%  |
| 1      | 2        | 3.57%   |
| 24     | 1        | 1.79%   |
| 12     | 1        | 1.79%   |
| 3      | 1        | 1.79%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 54       | 96.43%  |
| 2      | 2        | 3.57%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 30       | 53.57%  |
| 1      | 26       | 46.43%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 49       | 87.5%   |
| Unknown        | 7        | 12.5%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 10       | 17.54%  |
| 0x306c3    | 5        | 8.77%   |
| 0x306a9    | 5        | 8.77%   |
| 0x206a7    | 4        | 7.02%   |
| 0x0800820d | 4        | 7.02%   |
| 0x06001119 | 4        | 7.02%   |
| 0x906e9    | 3        | 5.26%   |
| 0x506e3    | 3        | 5.26%   |
| 0x20652    | 2        | 3.51%   |
| 0x1067a    | 2        | 3.51%   |
| 0x906ea    | 1        | 1.75%   |
| 0x6fb      | 1        | 1.75%   |
| 0x306e4    | 1        | 1.75%   |
| 0x106e5    | 1        | 1.75%   |
| 0x106a5    | 1        | 1.75%   |
| 0x10676    | 1        | 1.75%   |
| 0x0a201016 | 1        | 1.75%   |
| 0x0a201009 | 1        | 1.75%   |
| 0x08701021 | 1        | 1.75%   |
| 0x08108109 | 1        | 1.75%   |
| 0x08001138 | 1        | 1.75%   |
| 0x0600081c | 1        | 1.75%   |
| 0x06000817 | 1        | 1.75%   |
| 0x010000c8 | 1        | 1.75%   |
| 0x010000b6 | 1        | 1.75%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Zen+        | 6        | 10.71%  |
| Piledriver  | 6        | 10.71%  |
| Penryn      | 6        | 10.71%  |
| IvyBridge   | 6        | 10.71%  |
| Haswell     | 6        | 10.71%  |
| KabyLake    | 5        | 8.93%   |
| Zen 2       | 4        | 7.14%   |
| SandyBridge | 4        | 7.14%   |
| Skylake     | 3        | 5.36%   |
| Zen         | 2        | 3.57%   |
| Westmere    | 2        | 3.57%   |
| Nehalem     | 2        | 3.57%   |
| K10         | 2        | 3.57%   |
| Zen 3       | 1        | 1.79%   |
| Core        | 1        | 1.79%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 25       | 42.37%  |
| AMD               | 19       | 32.2%   |
| Intel             | 14       | 23.73%  |
| ASPEED Technology | 1        | 1.69%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia GK208B [GeForce GT 710]                                              | 4        | 6.45%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 4        | 6.45%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3        | 4.84%   |
| Nvidia GF108 [GeForce GT 730]                                               | 3        | 4.84%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 4.84%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 2        | 3.23%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 3.23%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 3.23%   |
| AMD Trinity [Radeon HD 7660D]                                               | 2        | 3.23%   |
| AMD Curacao XT / Trinidad XT [Radeon R7 370 / R9 270X/370X]                 | 2        | 3.23%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 1.61%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                      | 1        | 1.61%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 1.61%   |
| Nvidia GT216M [GeForce GT 330M]                                             | 1        | 1.61%   |
| Nvidia GT200GL [Quadro FX 4800]                                             | 1        | 1.61%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 1.61%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 1.61%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 1.61%   |
| Nvidia GM204 [GeForce GTX 980]                                              | 1        | 1.61%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 1.61%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 1        | 1.61%   |
| Nvidia GK104GL [Tesla K10]                                                  | 1        | 1.61%   |
| Nvidia GF119 [NVS 310]                                                      | 1        | 1.61%   |
| Nvidia GF119 [GeForce GT 610]                                               | 1        | 1.61%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 1.61%   |
| Nvidia GF108 [GeForce GT 420]                                               | 1        | 1.61%   |
| Intel HD Graphics P530                                                      | 1        | 1.61%   |
| Intel HD Graphics 630                                                       | 1        | 1.61%   |
| Intel HD Graphics 610                                                       | 1        | 1.61%   |
| Intel HD Graphics 530                                                       | 1        | 1.61%   |
| Intel Core Processor Integrated Graphics Controller                         | 1        | 1.61%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 1        | 1.61%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1        | 1.61%   |
| ASPEED Technology ASPEED Graphics Family                                    | 1        | 1.61%   |
| AMD Vega 20 [Radeon VII]                                                    | 1        | 1.61%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 1        | 1.61%   |
| AMD Tahiti XT [Radeon HD 7970/8970 OEM / R9 280X]                           | 1        | 1.61%   |
| AMD RV770 [Radeon HD 4850]                                                  | 1        | 1.61%   |
| AMD RV710 [Radeon HD 4350/4550]                                             | 1        | 1.61%   |
| AMD RS780L [Radeon 3000]                                                    | 1        | 1.61%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 1        | 1.61%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 1        | 1.61%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 1        | 1.61%   |
| AMD Ellesmere [Radeon Pro WX 5100]                                          | 1        | 1.61%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 1        | 1.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Nvidia | 24       | 42.86%  |
| 1 x AMD    | 19       | 33.93%  |
| 1 x Intel  | 11       | 19.64%  |
| 3 x Nvidia | 1        | 1.79%   |
| 1 x ASPEED | 1        | 1.79%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 46       | 80.7%   |
| Proprietary | 10       | 17.54%  |
| Unknown     | 1        | 1.75%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 22       | 39.29%  |
| 1.01-2.0   | 10       | 17.86%  |
| 7.01-8.0   | 6        | 10.71%  |
| 0.51-1.0   | 5        | 8.93%   |
| 3.01-4.0   | 4        | 7.14%   |
| 8.01-16.0  | 3        | 5.36%   |
| 0.01-0.5   | 3        | 5.36%   |
| 2.01-3.0   | 2        | 3.57%   |
| 5.01-6.0   | 1        | 1.79%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 12       | 20%     |
| Hewlett-Packard      | 6        | 10%     |
| BenQ                 | 6        | 10%     |
| Dell                 | 5        | 8.33%   |
| Acer                 | 5        | 8.33%   |
| Philips              | 4        | 6.67%   |
| Goldstar             | 4        | 6.67%   |
| Ancor Communications | 3        | 5%      |
| MSI                  | 2        | 3.33%   |
| AOC                  | 2        | 3.33%   |
| Vizio                | 1        | 1.67%   |
| Vestel               | 1        | 1.67%   |
| Unknown              | 1        | 1.67%   |
| Sony                 | 1        | 1.67%   |
| Sceptre Tech         | 1        | 1.67%   |
| Plain Tree Systems   | 1        | 1.67%   |
| Microstep            | 1        | 1.67%   |
| Medion               | 1        | 1.67%   |
| Iiyama               | 1        | 1.67%   |
| GRM                  | 1        | 1.67%   |
| ASUSTek Computer     | 1        | 1.67%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Samsung Electronics SA300/SA350 SAM0791 1920x1080 510x287mm 23.0-inch  | 2        | 2.94%   |
| MSI Optix G24C MSI1462 1920x1080 521x293mm 23.5-inch                   | 2        | 2.94%   |
| Vizio E390i-A1 VIZ1004 1920x1080 853x480mm 38.5-inch                   | 1        | 1.47%   |
| Vestel LCD Monitor 32W_LCD_TV                                          | 1        | 1.47%   |
| Unknown LCD Monitor DAC Moniter 5760x1080                              | 1        | 1.47%   |
| Sony TV SNYF301 1920x1080 1600x900mm 72.3-inch                         | 1        | 1.47%   |
| Sceptre Tech Sceptre M25 SPT0A05 1920x1080 698x393mm 31.5-inch         | 1        | 1.47%   |
| Samsung Electronics SyncMaster SAM0593 1920x1080 477x268mm 21.5-inch   | 1        | 1.47%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 428x255mm 19.6-inch    | 1        | 1.47%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch      | 1        | 1.47%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch      | 1        | 1.47%   |
| Samsung Electronics S22D300 SAM0B3E 1920x1080 477x268mm 21.5-inch      | 1        | 1.47%   |
| Samsung Electronics LU28R55 SAM1016 3840x2160 632x360mm 28.6-inch      | 1        | 1.47%   |
| Samsung Electronics LCD Monitor SAM0DF7 3840x2160 1210x680mm 54.6-inch | 1        | 1.47%   |
| Samsung Electronics LCD Monitor SAM094E 1920x1080 890x500mm 40.2-inch  | 1        | 1.47%   |
| Samsung Electronics LCD Monitor SAM07BA 1920x1080 480x270mm 21.7-inch  | 1        | 1.47%   |
| Samsung Electronics LCD Monitor S24D300 1920x1080                      | 1        | 1.47%   |
| Plain Tree Systems TFT19DXP PTS03A0 1280x1024 376x301mm 19.0-inch      | 1        | 1.47%   |
| Philips PHL 276E8V PHLC18F 3840x2160 600x340mm 27.2-inch               | 1        | 1.47%   |
| Philips PHL 273V5 PHLC0D2 1920x1080 600x340mm 27.2-inch                | 1        | 1.47%   |
| Philips PHL 246E9Q PHLC17C 1920x1080 527x296mm 23.8-inch               | 1        | 1.47%   |
| Philips LCD Monitor PHL 276E8V 7680x2160                               | 1        | 1.47%   |
| Philips LCD Monitor PHL 276E8V                                         | 1        | 1.47%   |
| MSI MPG341CQR MSI3DA0 3440x1440 797x334mm 34.0-inch                    | 1        | 1.47%   |
| MSI MAG341CQ MSI1462 3440x1440 800x330mm 34.1-inch                     | 1        | 1.47%   |
| Microstep LCD Monitor Optix MAG24C 3840x1200                           | 1        | 1.47%   |
| Medion LCD Monitor MEDB603 1920x1080 480x270mm 21.7-inch               | 1        | 1.47%   |
| Iiyama PL2493H IVM6148 1920x1080 527x296mm 23.8-inch                   | 1        | 1.47%   |
| Hewlett-Packard x23LED HWP2912 1920x1080 509x286mm 23.0-inch           | 1        | 1.47%   |
| Hewlett-Packard w2228h HWP2810 1680x1050 473x296mm 22.0-inch           | 1        | 1.47%   |
| Hewlett-Packard w2207 HWP26A8 1680x1050 473x296mm 22.0-inch            | 1        | 1.47%   |
| Hewlett-Packard vs19x HWP2658 1280x1024 376x301mm 19.0-inch            | 1        | 1.47%   |
| Hewlett-Packard LCD Monitor x23LED 1920x1080                           | 1        | 1.47%   |
| Hewlett-Packard Compaq S1922 HWP290B 1366x768 413x234mm 18.7-inch      | 1        | 1.47%   |
| Hewlett-Packard 2159 HWP282A 1920x1080 477x268mm 21.5-inch             | 1        | 1.47%   |
| GRM Q19 cinema GRM2730 1360x768 410x230mm 18.5-inch                    | 1        | 1.47%   |
| Goldstar M228WA GSM563C 1680x1050 434x270mm 20.1-inch                  | 1        | 1.47%   |
| Goldstar LCD Monitor GSM76F5 1920x1080 700x390mm 31.5-inch             | 1        | 1.47%   |
| Goldstar L1915S GSM4A90 1280x1024 380x300mm 19.1-inch                  | 1        | 1.47%   |
| Goldstar 24MP55 GSM5A20 1920x1080 510x290mm 23.1-inch                  | 1        | 1.47%   |
| Dell U2312HM DEL4072 1920x1080 510x287mm 23.0-inch                     | 1        | 1.47%   |
| Dell SE2417HG DELD08C 1920x1080 521x293mm 23.5-inch                    | 1        | 1.47%   |
| Dell LCD Monitor U2713HM 2560x1440                                     | 1        | 1.47%   |
| Dell LCD Monitor 2408WFP                                               | 1        | 1.47%   |
| Dell E2417H DELA0E2 1920x1080 527x296mm 23.8-inch                      | 1        | 1.47%   |
| Dell E2417H DELA0E1 1920x1080 527x296mm 23.8-inch                      | 1        | 1.47%   |
| Dell 2408WFP DELA02C 1920x1200 519x324mm 24.1-inch                     | 1        | 1.47%   |
| BenQ ZOWIE RL LCD BNQ7F4F 1920x1080 531x299mm 24.0-inch                | 1        | 1.47%   |
| BenQ LCD Monitor LCD 7680x2160                                         | 1        | 1.47%   |
| BenQ LCD Monitor LCD                                                   | 1        | 1.47%   |
| BenQ LCD Monitor GC2870 1920x1080                                      | 1        | 1.47%   |
| BenQ LCD Monitor G2220HD                                               | 1        | 1.47%   |
| BenQ LCD BNQ801D 3840x2160 521x293mm 23.5-inch                         | 1        | 1.47%   |
| BenQ GW2470 BNQ78D9 1920x1080 530x300mm 24.0-inch                      | 1        | 1.47%   |
| BenQ GW2280 BNQ78E8 1920x1080 476x268mm 21.5-inch                      | 1        | 1.47%   |
| ASUSTek Computer VP28U AUS28B1 3840x2160 621x341mm 27.9-inch           | 1        | 1.47%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                    | 1        | 1.47%   |
| AOC 2269W AOC2269 1920x1080 477x268mm 21.5-inch                        | 1        | 1.47%   |
| Ancor Communications MX279 ACI27C3 1920x1080 598x336mm 27.0-inch       | 1        | 1.47%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch  | 1        | 1.47%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 29       | 48.33%  |
| 3840x2160 (4K)     | 4        | 6.67%   |
| 1680x1050 (WSXGA+) | 4        | 6.67%   |
| Unknown            | 4        | 6.67%   |
| 1366x768 (WXGA)    | 3        | 5%      |
| 1280x1024 (SXGA)   | 3        | 5%      |
| 7680x2160          | 2        | 3.33%   |
| 3440x1440          | 2        | 3.33%   |
| 2560x1440 (QHD)    | 2        | 3.33%   |
| 1440x900 (WXGA+)   | 2        | 3.33%   |
| 5760x1080          | 1        | 1.67%   |
| 3840x1200          | 1        | 1.67%   |
| 1920x1200 (WUXGA)  | 1        | 1.67%   |
| 1600x900 (HD+)     | 1        | 1.67%   |
| 1360x768           | 1        | 1.67%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 11       | 18.03%  |
| 21      | 8        | 13.11%  |
| Unknown | 8        | 13.11%  |
| 24      | 5        | 8.2%    |
| 19      | 5        | 8.2%    |
| 27      | 4        | 6.56%   |
| 18      | 4        | 6.56%   |
| 22      | 3        | 4.92%   |
| 34      | 2        | 3.28%   |
| 31      | 2        | 3.28%   |
| 20      | 2        | 3.28%   |
| 84      | 1        | 1.64%   |
| 72      | 1        | 1.64%   |
| 49      | 1        | 1.64%   |
| 46      | 1        | 1.64%   |
| 40      | 1        | 1.64%   |
| 33      | 1        | 1.64%   |
| 28      | 1        | 1.64%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 19       | 32.2%   |
| 501-600     | 17       | 28.81%  |
| Unknown     | 8        | 13.56%  |
| 601-700     | 4        | 6.78%   |
| 701-800     | 3        | 5.08%   |
| 351-400     | 3        | 5.08%   |
| 1501-2000   | 2        | 3.39%   |
| 1001-1500   | 2        | 3.39%   |
| 801-900     | 1        | 1.69%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 37       | 66.07%  |
| Unknown | 8        | 14.29%  |
| 16/10   | 6        | 10.71%  |
| 5/4     | 3        | 5.36%   |
| 21/9    | 2        | 3.57%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 22       | 37.93%  |
| 151-200        | 9        | 15.52%  |
| Unknown        | 8        | 13.79%  |
| 351-500        | 5        | 8.62%   |
| 301-350        | 4        | 6.9%    |
| 141-150        | 4        | 6.9%    |
| More than 1000 | 3        | 5.17%   |
| 501-1000       | 2        | 3.45%   |
| 251-300        | 1        | 1.72%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 35       | 59.32%  |
| 101-120 | 10       | 16.95%  |
| Unknown | 8        | 13.56%  |
| 1-50    | 3        | 5.08%   |
| 121-160 | 2        | 3.39%   |
| 161-240 | 1        | 1.69%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 47       | 82.46%  |
| 2     | 7        | 12.28%  |
| 0     | 2        | 3.51%   |
| 3     | 1        | 1.75%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 33       | 41.77%  |
| Intel                           | 28       | 35.44%  |
| Qualcomm Atheros                | 4        | 5.06%   |
| Ralink Technology               | 3        | 3.8%    |
| TP-Link                         | 2        | 2.53%   |
| Microsoft                       | 2        | 2.53%   |
| Broadcom                        | 2        | 2.53%   |
| Xiaomi                          | 1        | 1.27%   |
| Qualcomm Atheros Communications | 1        | 1.27%   |
| Nvidia                          | 1        | 1.27%   |
| NetXen Incorporated             | 1        | 1.27%   |
| Belkin Components               | 1        | 1.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 24       | 27.27%  |
| Intel I211 Gigabit Network Connection                                   | 9        | 10.23%  |
| Intel Wi-Fi 6 AX200                                                     | 5        | 5.68%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 3        | 3.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 3        | 3.41%   |
| Intel 82567LM-3 Gigabit Network Connection                              | 3        | 3.41%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 2        | 2.27%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 2        | 2.27%   |
| Ralink RT5572 Wireless Adapter                                          | 2        | 2.27%   |
| Intel Wireless-AC 9260                                                  | 2        | 2.27%   |
| Intel Ethernet Connection I217-LM                                       | 2        | 2.27%   |
| Intel Ethernet Connection (2) I219-V                                    | 2        | 2.27%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1        | 1.14%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                   | 1        | 1.14%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                               | 1        | 1.14%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                              | 1        | 1.14%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1        | 1.14%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1        | 1.14%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 1        | 1.14%   |
| Realtek RTL8125 2.5GbE Controller                                       | 1        | 1.14%   |
| Ralink MT7601U Wireless Adapter                                         | 1        | 1.14%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1        | 1.14%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1        | 1.14%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1        | 1.14%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 1        | 1.14%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1        | 1.14%   |
| Nvidia MCP61 Ethernet                                                   | 1        | 1.14%   |
| NetXen Incorporated NX3031 Multifunction 1/10-Gigabit Server Adapter    | 1        | 1.14%   |
| Microsoft XBOX ACC                                                      | 1        | 1.14%   |
| Microsoft Xbox 360 Wireless Adapter                                     | 1        | 1.14%   |
| Intel Ethernet Connection I217-V                                        | 1        | 1.14%   |
| Intel Ethernet Connection (2) I219-LM                                   | 1        | 1.14%   |
| Intel Ethernet Connection (2) I218-V                                    | 1        | 1.14%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1        | 1.14%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 1        | 1.14%   |
| Intel 82579V Gigabit Network Connection                                 | 1        | 1.14%   |
| Intel 82578DC Gigabit Network Connection                                | 1        | 1.14%   |
| Intel 82574L Gigabit Network Connection                                 | 1        | 1.14%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                         | 1        | 1.14%   |
| Broadcom BCM43217 802.11b/g/n                                           | 1        | 1.14%   |
| Belkin Components F5D8053 N Wireless USB Adapter v3000 [Ralink RT2870]  | 1        | 1.14%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 9        | 30%     |
| Realtek Semiconductor           | 8        | 26.67%  |
| Ralink Technology               | 3        | 10%     |
| Qualcomm Atheros                | 3        | 10%     |
| TP-Link                         | 2        | 6.67%   |
| Microsoft                       | 2        | 6.67%   |
| Qualcomm Atheros Communications | 1        | 3.33%   |
| Broadcom                        | 1        | 3.33%   |
| Belkin Components               | 1        | 3.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 5        | 16.67%  |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 3        | 10%     |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 2        | 6.67%   |
| Ralink RT5572 Wireless Adapter                                          | 2        | 6.67%   |
| Intel Wireless-AC 9260                                                  | 2        | 6.67%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                   | 1        | 3.33%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                               | 1        | 3.33%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                              | 1        | 3.33%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1        | 3.33%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1        | 3.33%   |
| Ralink MT7601U Wireless Adapter                                         | 1        | 3.33%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1        | 3.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1        | 3.33%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1        | 3.33%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1        | 3.33%   |
| Microsoft XBOX ACC                                                      | 1        | 3.33%   |
| Microsoft Xbox 360 Wireless Adapter                                     | 1        | 3.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1        | 3.33%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 1        | 3.33%   |
| Broadcom BCM43217 802.11b/g/n                                           | 1        | 3.33%   |
| Belkin Components F5D8053 N Wireless USB Adapter v3000 [Ralink RT2870]  | 1        | 3.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 28       | 48.28%  |
| Intel                 | 25       | 43.1%   |
| Xiaomi                | 1        | 1.72%   |
| Qualcomm Atheros      | 1        | 1.72%   |
| Nvidia                | 1        | 1.72%   |
| NetXen Incorporated   | 1        | 1.72%   |
| Broadcom              | 1        | 1.72%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 24       | 41.38%  |
| Intel I211 Gigabit Network Connection                                | 9        | 15.52%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 3        | 5.17%   |
| Intel 82567LM-3 Gigabit Network Connection                           | 3        | 5.17%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 2        | 3.45%   |
| Intel Ethernet Connection I217-LM                                    | 2        | 3.45%   |
| Intel Ethernet Connection (2) I219-V                                 | 2        | 3.45%   |
| Xiaomi Mi/Redmi series (RNDIS)                                       | 1        | 1.72%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                             | 1        | 1.72%   |
| Realtek RTL8125 2.5GbE Controller                                    | 1        | 1.72%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                        | 1        | 1.72%   |
| Nvidia MCP61 Ethernet                                                | 1        | 1.72%   |
| NetXen Incorporated NX3031 Multifunction 1/10-Gigabit Server Adapter | 1        | 1.72%   |
| Intel Ethernet Connection I217-V                                     | 1        | 1.72%   |
| Intel Ethernet Connection (2) I219-LM                                | 1        | 1.72%   |
| Intel Ethernet Connection (2) I218-V                                 | 1        | 1.72%   |
| Intel 82579V Gigabit Network Connection                              | 1        | 1.72%   |
| Intel 82578DC Gigabit Network Connection                             | 1        | 1.72%   |
| Intel 82574L Gigabit Network Connection                              | 1        | 1.72%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                      | 1        | 1.72%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 52       | 65%     |
| WiFi     | 28       | 35%     |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 49       | 68.06%  |
| WiFi     | 23       | 31.94%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 36       | 64.29%  |
| 2     | 15       | 26.79%  |
| 3     | 2        | 3.57%   |
| 0     | 2        | 3.57%   |
| 6     | 1        | 1.79%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 54       | 94.74%  |
| Yes  | 3        | 5.26%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 9        | 47.37%  |
| Cambridge Silicon Radio | 7        | 36.84%  |
| ASUSTek Computer        | 2        | 10.53%  |
| IMC Networks            | 1        | 5.26%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 7        | 36.84%  |
| Intel AX200 Bluetooth                               | 5        | 26.32%  |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2        | 10.53%  |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 5.26%   |
| Intel Bluetooth Device                              | 1        | 5.26%   |
| IMC Networks Bluetooth Module                       | 1        | 5.26%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 5.26%   |
| ASUS BCM20702A0                                     | 1        | 5.26%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 34       | 34.34%  |
| AMD                    | 27       | 27.27%  |
| Nvidia                 | 26       | 26.26%  |
| C-Media Electronics    | 4        | 4.04%   |
| Plantronics            | 1        | 1.01%   |
| Logitech               | 1        | 1.01%   |
| JMTek                  | 1        | 1.01%   |
| Generalplus Technology | 1        | 1.01%   |
| Focusrite-Novation     | 1        | 1.01%   |
| Creative Labs          | 1        | 1.01%   |
| Blue Microphones       | 1        | 1.01%   |
| Alesis                 | 1        | 1.01%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 7        | 6.14%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5        | 4.39%   |
| AMD Starship/Matisse HD Audio Controller                                   | 5        | 4.39%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 5        | 4.39%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 4        | 3.51%   |
| Nvidia GF108 High Definition Audio Controller                              | 4        | 3.51%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4        | 3.51%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4        | 3.51%   |
| Intel 200 Series PCH HD Audio                                              | 4        | 3.51%   |
| AMD FCH Azalia Controller                                                  | 4        | 3.51%   |
| Nvidia GP108 High Definition Audio Controller                              | 3        | 2.63%   |
| Nvidia GF119 HDMI Audio Controller                                         | 3        | 2.63%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 3        | 2.63%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3        | 2.63%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3        | 2.63%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 3        | 2.63%   |
| Nvidia GP104 High Definition Audio Controller                              | 2        | 1.75%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2        | 1.75%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2        | 1.75%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 1.75%   |
| AMD Trinity HDMI Audio Controller                                          | 2        | 1.75%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2        | 1.75%   |
| Plantronics RIG 800HD                                                      | 1        | 0.88%   |
| Nvidia TU116 High Definition Audio Controller                              | 1        | 0.88%   |
| Nvidia TU106 High Definition Audio Controller                              | 1        | 0.88%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 0.88%   |
| Nvidia High Definition Audio Controller                                    | 1        | 0.88%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1        | 0.88%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 0.88%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 0.88%   |
| Nvidia GP102 HDMI Audio Controller                                         | 1        | 0.88%   |
| Nvidia GM204 High Definition Audio Controller                              | 1        | 0.88%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 0.88%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1        | 0.88%   |
| Logitech H600 [Wireless Headset]                                           | 1        | 0.88%   |
| JMTek USB PnP Audio Device                                                 | 1        | 0.88%   |
| Intel Cannon Lake PCH cAVS                                                 | 1        | 0.88%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 1        | 0.88%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 1        | 0.88%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1        | 0.88%   |
| Generalplus Technology USB Audio Device                                    | 1        | 0.88%   |
| Focusrite-Novation Scarlett Solo (3rd Gen.)                                | 1        | 0.88%   |
| Creative Labs EMU20k2 [Sound Blaster X-Fi Titanium Series]                 | 1        | 0.88%   |
| C-Media Electronics SADES Hammer                                           | 1        | 0.88%   |
| C-Media Electronics CM108 Audio Controller                                 | 1        | 0.88%   |
| C-Media Electronics CM106 Like Sound Device                                | 1        | 0.88%   |
| C-Media Electronics Audio Device                                           | 1        | 0.88%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 1        | 0.88%   |
| Blue Microphones Yeti Stereo Microphone                                    | 1        | 0.88%   |
| AMD Vega 20 HDMI Audio [Radeon VII]                                        | 1        | 0.88%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 1        | 0.88%   |
| AMD Tahiti HDMI Audio [Radeon HD 7870 XT / 7950/7970]                      | 1        | 0.88%   |
| AMD RV770 HDMI Audio [Radeon HD 4850/4870]                                 | 1        | 0.88%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 1        | 0.88%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1        | 0.88%   |
| AMD Navi 21 HDMI Audio [Radeon RX 6800/6800 XT / 6900 XT]                  | 1        | 0.88%   |
| AMD Navi 10 HDMI Audio                                                     | 1        | 0.88%   |
| AMD Family 17h/19h HD Audio Controller                                     | 1        | 0.88%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 1        | 0.88%   |
| Alesis Q25                                                                 | 1        | 0.88%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 2        | 20%     |
| Crucial             | 2        | 20%     |
| Unknown             | 1        | 10%     |
| Team                | 1        | 10%     |
| SK Hynix            | 1        | 10%     |
| Samsung Electronics | 1        | 10%     |
| G.Skill             | 1        | 10%     |
| Corsair             | 1        | 10%     |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s             | 1        | 8.33%   |
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s     | 1        | 8.33%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s   | 1        | 8.33%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s      | 1        | 8.33%   |
| Kingston RAM 99P5471-002.A00LF 2GB DIMM DDR3 1600MT/s    | 1        | 8.33%   |
| Kingston RAM 99P5471-001.A01LF 2GB DIMM DDR3 1333MT/s    | 1        | 8.33%   |
| Kingston RAM 99P5471-001.A00LF 2GB DIMM DDR3 1333MT/s    | 1        | 8.33%   |
| Kingston RAM 9905584-023.A00LF 4GB DIMM DDR3 1600MT/s    | 1        | 8.33%   |
| G.Skill RAM F4-3600C16-8GVKC 8GB DIMM DDR4 3600MT/s      | 1        | 8.33%   |
| Crucial RAM BLT4G3D1869DT 4096MB DIMM DDR3 1333MT/s      | 1        | 8.33%   |
| Crucial RAM BL16G36C16U4W.M16FE1 16GB DIMM DDR4 3733MT/s | 1        | 8.33%   |
| Corsair RAM CMK64GX4M2D3000C16 32GB DIMM DDR4 3000MT/s   | 1        | 8.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Desktops | Percent |
|--------|----------|---------|
| DDR4   | 4        | 44.44%  |
| DDR3   | 4        | 44.44%  |
| LPDDR4 | 1        | 11.11%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 7        | 87.5%   |
| SODIMM | 1        | 12.5%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 4        | 40%     |
| 32768 | 2        | 20%     |
| 8192  | 2        | 20%     |
| 16384 | 1        | 10%     |
| 2048  | 1        | 10%     |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 3        | 30%     |
| 1333  | 2        | 20%     |
| 3733  | 1        | 10%     |
| 3600  | 1        | 10%     |
| 3000  | 1        | 10%     |
| 2667  | 1        | 10%     |
| 1867  | 1        | 10%     |

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
| Logitech                    | 3        | 37.5%   |
| Samsung Electronics         | 1        | 12.5%   |
| KYE Systems (Mouse Systems) | 1        | 12.5%   |
| IMC Networks                | 1        | 12.5%   |
| GEMBIRD                     | 1        | 12.5%   |
| Alcor Micro                 | 1        | 12.5%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920             | 2        | 25%     |
| Samsung Galaxy A5 (MTP)                 | 1        | 12.5%   |
| Logitech C922 Pro Stream Webcam         | 1        | 12.5%   |
| KYE Systems (Mouse Systems) Slim 1322AF | 1        | 12.5%   |
| IMC Networks XHC Camera                 | 1        | 12.5%   |
| GEMBIRD USB2.0 PC CAMERA                | 1        | 12.5%   |
| Alcor Micro USB 2.0 PC Camera           | 1        | 12.5%   |

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
| 0     | 48       | 85.71%  |
| 1     | 6        | 10.71%  |
| 2     | 2        | 3.57%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Desktops | Percent |
|-----------------------|----------|---------|
| Net/wireless          | 5        | 62.5%   |
| Tv card               | 1        | 12.5%   |
| Multimedia controller | 1        | 12.5%   |
| Graphics card         | 1        | 12.5%   |

