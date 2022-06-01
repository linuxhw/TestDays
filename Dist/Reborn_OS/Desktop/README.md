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

Total: 83

| Vendor   | Model                    | Probe                                                      | Date         |
|----------|--------------------------|------------------------------------------------------------|--------------|
| Gigabyte | H110M-S2PT-CF            | [506afdf9c7](https://linux-hardware.org/?probe=506afdf9c7) | Mar 09, 2022 |
| Shuttle  | FZ270                    | [ed3e018227](https://linux-hardware.org/?probe=ed3e018227) | Mar 09, 2022 |
| ASUSTek  | ROG STRIX X570-I GAMING  | [bc31f5f2bd](https://linux-hardware.org/?probe=bc31f5f2bd) | Jan 17, 2022 |
| ASUSTek  | PRIME H310M-K R2.0       | [7dba1540ad](https://linux-hardware.org/?probe=7dba1540ad) | Dec 06, 2021 |
| Medion   | Cattle24 1M              | [fd68d44a6a](https://linux-hardware.org/?probe=fd68d44a6a) | Oct 16, 2021 |
| Medion   | Cattle24 1M              | [dd4a0707ba](https://linux-hardware.org/?probe=dd4a0707ba) | May 19, 2021 |
| Dell     | 0200DY A01               | [426fc0381c](https://linux-hardware.org/?probe=426fc0381c) | May 08, 2021 |
| ASUSTek  | PRIME Z270-A             | [58fbf7553b](https://linux-hardware.org/?probe=58fbf7553b) | May 03, 2021 |
| ASUSTek  | PRIME Z270-A             | [27595787eb](https://linux-hardware.org/?probe=27595787eb) | Apr 26, 2021 |
| ASUSTek  | PRIME Z270-A             | [ec119e020d](https://linux-hardware.org/?probe=ec119e020d) | Apr 26, 2021 |
| HP       | 3048h                    | [b61eb90220](https://linux-hardware.org/?probe=b61eb90220) | Mar 20, 2021 |
| Gigabyte | X570 AORUS ELITE         | [0e8f323e0f](https://linux-hardware.org/?probe=0e8f323e0f) | Mar 18, 2021 |
| Gigabyte | X570 AORUS ELITE         | [a949911df6](https://linux-hardware.org/?probe=a949911df6) | Mar 18, 2021 |
| Gigabyte | B450 AORUS M             | [4a76fb93d3](https://linux-hardware.org/?probe=4a76fb93d3) | Mar 16, 2021 |
| Gigabyte | F2A85X-UP4               | [926ae13f69](https://linux-hardware.org/?probe=926ae13f69) | Mar 09, 2021 |
| ASUSTek  | ROG STRIX X570-I GAMING  | [6c98f8666d](https://linux-hardware.org/?probe=6c98f8666d) | Feb 24, 2021 |
| ASRock   | X570 Taichi              | [e6476ce804](https://linux-hardware.org/?probe=e6476ce804) | Feb 05, 2021 |
| ASUSTek  | PRIME B450M-A            | [6042185966](https://linux-hardware.org/?probe=6042185966) | Feb 05, 2021 |
| ASUSTek  | PRIME B450M-A            | [8c4549fed4](https://linux-hardware.org/?probe=8c4549fed4) | Feb 05, 2021 |
| ASUSTek  | ROG STRIX B350-F GAMING  | [0bb6c600d0](https://linux-hardware.org/?probe=0bb6c600d0) | Jan 25, 2021 |
| ASUSTek  | Q87M-E                   | [e95dad9e90](https://linux-hardware.org/?probe=e95dad9e90) | Jan 14, 2021 |
| MSI      | MEG X570 ACE             | [5b061048ce](https://linux-hardware.org/?probe=5b061048ce) | Jan 11, 2021 |
| Dell     | 02YYK5 A01               | [f50fd232e1](https://linux-hardware.org/?probe=f50fd232e1) | Jan 06, 2021 |
| MSI      | A320M PRO-VD/S V2        | [5d05e8d607](https://linux-hardware.org/?probe=5d05e8d607) | Jan 04, 2021 |
| ASUSTek  | PRIME H310M-K R2.0       | [ed3e1cc88a](https://linux-hardware.org/?probe=ed3e1cc88a) | Jan 04, 2021 |
| ASUSTek  | PRIME H310M-K R2.0       | [fb77017d74](https://linux-hardware.org/?probe=fb77017d74) | Jan 04, 2021 |
| ASUSTek  | P8B75-V                  | [a8ba58ce8d](https://linux-hardware.org/?probe=a8ba58ce8d) | Jan 03, 2021 |
| ASUSTek  | ROG STRIX B450-F GAMING  | [60d4c9b8f1](https://linux-hardware.org/?probe=60d4c9b8f1) | Jan 02, 2021 |
| ASUSTek  | ROG STRIX B450-F GAMING  | [bab82e261e](https://linux-hardware.org/?probe=bab82e261e) | Jan 02, 2021 |
| ASUSTek  | P7H55-M PRO              | [253b9e5126](https://linux-hardware.org/?probe=253b9e5126) | Jan 01, 2021 |
| ASUSTek  | P7H55-M PRO              | [016282f72d](https://linux-hardware.org/?probe=016282f72d) | Jan 01, 2021 |
| Dell     | 084J0R A00               | [45b5f0850b](https://linux-hardware.org/?probe=45b5f0850b) | Dec 30, 2020 |
| MSI      | FM2-A75MA-E35            | [c537d4854e](https://linux-hardware.org/?probe=c537d4854e) | Dec 14, 2020 |
| MSI      | FM2-A75MA-E35            | [f1f14b545e](https://linux-hardware.org/?probe=f1f14b545e) | Dec 13, 2020 |
| Dell     | 096JG8 A01               | [d0fc564ec7](https://linux-hardware.org/?probe=d0fc564ec7) | Dec 11, 2020 |
| Dell     | 096JG8 A01               | [2385d54def](https://linux-hardware.org/?probe=2385d54def) | Dec 09, 2020 |
| OEM      | G41 775 ICH7 8712        | [a135ed4b82](https://linux-hardware.org/?probe=a135ed4b82) | Nov 08, 2020 |
| OEM      | G41 775 ICH7 8712        | [151ca5d99e](https://linux-hardware.org/?probe=151ca5d99e) | Nov 08, 2020 |
| ASRock   | 960GM-VGS3 FX            | [5c51163253](https://linux-hardware.org/?probe=5c51163253) | Nov 05, 2020 |
| Gigabyte | EP43-UD3L                | [d6fd55eee0](https://linux-hardware.org/?probe=d6fd55eee0) | Nov 01, 2020 |
| Lenovo   | ThinkCentre M58 6258WCY  | [a1896b3549](https://linux-hardware.org/?probe=a1896b3549) | Oct 26, 2020 |
| ASUSTek  | PRIME H110M-P            | [5f4ab6b326](https://linux-hardware.org/?probe=5f4ab6b326) | Oct 18, 2020 |
| Foxconn  | H61S                     | [0fd947c658](https://linux-hardware.org/?probe=0fd947c658) | Oct 12, 2020 |
| Dell     | 096JG8 A01               | [337abf3073](https://linux-hardware.org/?probe=337abf3073) | Sep 30, 2020 |
| Huanan   | X79-8D VAA31             | [e0551a0a1c](https://linux-hardware.org/?probe=e0551a0a1c) | Sep 10, 2020 |
| Huanan   | X79-8D VAA31             | [66006c461d](https://linux-hardware.org/?probe=66006c461d) | Sep 06, 2020 |
| ASUSTek  | PRIME X370-PRO           | [524f57a765](https://linux-hardware.org/?probe=524f57a765) | Sep 06, 2020 |
| ASUSTek  | Z87-PLUS                 | [3fe15728ad](https://linux-hardware.org/?probe=3fe15728ad) | Sep 06, 2020 |
| ASUSTek  | Z87-PLUS                 | [e3f12cdd9b](https://linux-hardware.org/?probe=e3f12cdd9b) | Sep 05, 2020 |
| Dell     | 0Y2MRG A00               | [8af1b0565b](https://linux-hardware.org/?probe=8af1b0565b) | Sep 03, 2020 |
| Acer     | Aspire TC-885 V:1.1      | [c90b90e1a8](https://linux-hardware.org/?probe=c90b90e1a8) | Aug 21, 2020 |
| ASRock   | B450M Pro4               | [49170a6643](https://linux-hardware.org/?probe=49170a6643) | Aug 12, 2020 |
| ASUSTek  | M5A99X EVO               | [6aae8e8b65](https://linux-hardware.org/?probe=6aae8e8b65) | Aug 12, 2020 |
| MSI      | IONA                     | [0510d0f8ef](https://linux-hardware.org/?probe=0510d0f8ef) | Aug 06, 2020 |
| MSI      | IONA                     | [446e406f22](https://linux-hardware.org/?probe=446e406f22) | Aug 06, 2020 |
| ASUSTek  | P5KPL-AM SE              | [9c79ef0e1c](https://linux-hardware.org/?probe=9c79ef0e1c) | Jul 31, 2020 |
| ASUSTek  | P5KPL-AM SE              | [242b101828](https://linux-hardware.org/?probe=242b101828) | Jul 31, 2020 |
| ASUSTek  | STRIX H270F GAMING       | [52b8fcb9b0](https://linux-hardware.org/?probe=52b8fcb9b0) | Jul 26, 2020 |
| Gigabyte | Z87-HD3                  | [3eff281cc0](https://linux-hardware.org/?probe=3eff281cc0) | Jun 27, 2020 |
| Gigabyte | F2A75-D3H                | [59a8d5230f](https://linux-hardware.org/?probe=59a8d5230f) | Apr 09, 2020 |
| Pegatron | 2A99                     | [f01c0c56e7](https://linux-hardware.org/?probe=f01c0c56e7) | Apr 08, 2020 |
| ASRock   | X570 Phantom Gaming 4    | [97ffeec17e](https://linux-hardware.org/?probe=97ffeec17e) | Mar 23, 2020 |
| Lenovo   | MAHOBAY NOK              | [aaac6f9d4d](https://linux-hardware.org/?probe=aaac6f9d4d) | Mar 17, 2020 |
| ASRock   | X570 Phantom Gaming 4    | [63b8db155d](https://linux-hardware.org/?probe=63b8db155d) | Mar 02, 2020 |
| ASRock   | X570 Phantom Gaming 4    | [ed0b979970](https://linux-hardware.org/?probe=ed0b979970) | Mar 01, 2020 |
| ASRock   | X570 Phantom Gaming 4    | [85c6480266](https://linux-hardware.org/?probe=85c6480266) | Mar 01, 2020 |
| ASRock   | H81M-HDS                 | [0f180375d6](https://linux-hardware.org/?probe=0f180375d6) | Feb 25, 2020 |
| ASRock   | H81M-HDS                 | [55c569be56](https://linux-hardware.org/?probe=55c569be56) | Feb 23, 2020 |
| ASRock   | H81M-HDS                 | [98ae2a8227](https://linux-hardware.org/?probe=98ae2a8227) | Feb 22, 2020 |
| Gigabyte | GA-880GM-UD2H            | [b189e00138](https://linux-hardware.org/?probe=b189e00138) | Jan 16, 2020 |
| Gigabyte | GA-880GM-UD2H            | [ecb6ade802](https://linux-hardware.org/?probe=ecb6ade802) | Jan 16, 2020 |
| Intel    | DH55HC AAE70933-501      | [64266b67a2](https://linux-hardware.org/?probe=64266b67a2) | Dec 26, 2019 |
| HP       | 82F2 A01                 | [0b8306e086](https://linux-hardware.org/?probe=0b8306e086) | Nov 18, 2019 |
| Dell     | 0773VG A00               | [adf2d5daca](https://linux-hardware.org/?probe=adf2d5daca) | Oct 31, 2019 |
| Dell     | 0773VG A00               | [2f3044da6d](https://linux-hardware.org/?probe=2f3044da6d) | Oct 31, 2019 |
| MSI      | C236A WORKSTATION        | [fcc16b2804](https://linux-hardware.org/?probe=fcc16b2804) | Oct 11, 2019 |
| MSI      | C236A WORKSTATION        | [f68bc503a9](https://linux-hardware.org/?probe=f68bc503a9) | Oct 11, 2019 |
| Gigabyte | H61M-DS2                 | [2560a1cb4e](https://linux-hardware.org/?probe=2560a1cb4e) | Aug 28, 2019 |
| Gigabyte | H61M-DS2                 | [b013eab87a](https://linux-hardware.org/?probe=b013eab87a) | Aug 27, 2019 |
| ASUSTek  | Z8NA-D6                  | [81c929f40d](https://linux-hardware.org/?probe=81c929f40d) | Jan 23, 2019 |
| ASUSTek  | P8Z77-V DELUXE           | [2180eb318a](https://linux-hardware.org/?probe=2180eb318a) | Dec 30, 2018 |
| ASRock   | H97M Pro4                | [2e4984a12a](https://linux-hardware.org/?probe=2e4984a12a) | Nov 27, 2018 |
| Lenovo   | ThinkCentre M91p 0266RZ1 | [812afde3d9](https://linux-hardware.org/?probe=812afde3d9) | Nov 21, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| Reborn OS         | 50       | 86.21%  |
| Reborn OS Rolling | 8        | 13.79%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| Reborn OS | 58       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Desktops | Percent |
|----------------------|----------|---------|
| 5.10.3-arch1-1       | 4        | 6.35%   |
| 5.9.14-arch1-1       | 3        | 4.76%   |
| 5.7.12-arch1-1       | 3        | 4.76%   |
| 5.9.1-arch1-1        | 2        | 3.17%   |
| 5.8.7-arch1-1        | 2        | 3.17%   |
| 5.16.12-arch1-1      | 2        | 3.17%   |
| 5.11.7-arch1-1       | 2        | 3.17%   |
| 5.10.4-arch2-1       | 2        | 3.17%   |
| 5.10.13-arch1-1      | 2        | 3.17%   |
| 5.9.6-arch1-1        | 1        | 1.59%   |
| 5.9.3-arch1-1        | 1        | 1.59%   |
| 5.9.2-arch1-1        | 1        | 1.59%   |
| 5.9.13-arch1-1       | 1        | 1.59%   |
| 5.9.12-arch1-1       | 1        | 1.59%   |
| 5.9.11-arch2-1       | 1        | 1.59%   |
| 5.8.6-arch1-1        | 1        | 1.59%   |
| 5.8.5-arch1-1        | 1        | 1.59%   |
| 5.8.14-arch1-1       | 1        | 1.59%   |
| 5.8.12-arch1-1       | 1        | 1.59%   |
| 5.8.1-arch1-1        | 1        | 1.59%   |
| 5.7.6-arch1-1-custom | 1        | 1.59%   |
| 5.7.11-arch1-1       | 1        | 1.59%   |
| 5.7.10-arch1-1       | 1        | 1.59%   |
| 5.6.3-arch1-1        | 1        | 1.59%   |
| 5.6.2-arch1-2        | 1        | 1.59%   |
| 5.5.9-arch1-2        | 1        | 1.59%   |
| 5.5.5-arch1-1        | 1        | 1.59%   |
| 5.5.2-arch1-1        | 1        | 1.59%   |
| 5.5.11-arch1-1       | 1        | 1.59%   |
| 5.4.6-arch3-1        | 1        | 1.59%   |
| 5.4.10-arch1-1       | 1        | 1.59%   |
| 5.3.7-arch1-2-ARCH   | 1        | 1.59%   |
| 5.3.5-arch1-1-ARCH   | 1        | 1.59%   |
| 5.3.11-arch1-1       | 1        | 1.59%   |
| 5.2.9-arch1-1-ARCH   | 1        | 1.59%   |
| 5.16.0-zen1-1-zen    | 1        | 1.59%   |
| 5.14.7-arch1-1       | 1        | 1.59%   |
| 5.12.4-arch1-2       | 1        | 1.59%   |
| 5.12.1-arch1-1       | 1        | 1.59%   |
| 5.11.6-arch1-1       | 1        | 1.59%   |
| 5.11.4-arch1-1       | 1        | 1.59%   |
| 5.11.16-arch1-1      | 1        | 1.59%   |
| 5.11.16-149-tkg-bmq  | 1        | 1.59%   |
| 5.11.1-arch1-1       | 1        | 1.59%   |
| 5.10.83-1-lts        | 1        | 1.59%   |
| 5.10.6-arch1-1       | 1        | 1.59%   |
| 4.20.3-arch1-1-ARCH  | 1        | 1.59%   |
| 4.19.2-arch1-1-ARCH  | 1        | 1.59%   |
| 4.19.12-arch1-1-ARCH | 1        | 1.59%   |
| 4.18.10-arch1-1-ARCH | 1        | 1.59%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10.3  | 4        | 6.45%   |
| 5.9.14  | 3        | 4.84%   |
| 5.7.12  | 3        | 4.84%   |
| 5.9.1   | 2        | 3.23%   |
| 5.8.7   | 2        | 3.23%   |
| 5.16.12 | 2        | 3.23%   |
| 5.11.7  | 2        | 3.23%   |
| 5.10.4  | 2        | 3.23%   |
| 5.10.13 | 2        | 3.23%   |
| 5.9.6   | 1        | 1.61%   |
| 5.9.3   | 1        | 1.61%   |
| 5.9.2   | 1        | 1.61%   |
| 5.9.13  | 1        | 1.61%   |
| 5.9.12  | 1        | 1.61%   |
| 5.9.11  | 1        | 1.61%   |
| 5.8.6   | 1        | 1.61%   |
| 5.8.5   | 1        | 1.61%   |
| 5.8.14  | 1        | 1.61%   |
| 5.8.12  | 1        | 1.61%   |
| 5.8.1   | 1        | 1.61%   |
| 5.7.6   | 1        | 1.61%   |
| 5.7.11  | 1        | 1.61%   |
| 5.7.10  | 1        | 1.61%   |
| 5.6.3   | 1        | 1.61%   |
| 5.6.2   | 1        | 1.61%   |
| 5.5.9   | 1        | 1.61%   |
| 5.5.5   | 1        | 1.61%   |
| 5.5.2   | 1        | 1.61%   |
| 5.5.11  | 1        | 1.61%   |
| 5.4.6   | 1        | 1.61%   |
| 5.4.10  | 1        | 1.61%   |
| 5.3.7   | 1        | 1.61%   |
| 5.3.5   | 1        | 1.61%   |
| 5.3.11  | 1        | 1.61%   |
| 5.2.9   | 1        | 1.61%   |
| 5.16.0  | 1        | 1.61%   |
| 5.14.7  | 1        | 1.61%   |
| 5.12.4  | 1        | 1.61%   |
| 5.12.1  | 1        | 1.61%   |
| 5.11.6  | 1        | 1.61%   |
| 5.11.4  | 1        | 1.61%   |
| 5.11.16 | 1        | 1.61%   |
| 5.11.1  | 1        | 1.61%   |
| 5.10.83 | 1        | 1.61%   |
| 5.10.6  | 1        | 1.61%   |
| 4.20.3  | 1        | 1.61%   |
| 4.19.2  | 1        | 1.61%   |
| 4.19.12 | 1        | 1.61%   |
| 4.18.10 | 1        | 1.61%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.9     | 11       | 18.03%  |
| 5.10    | 9        | 14.75%  |
| 5.8     | 7        | 11.48%  |
| 5.7     | 6        | 9.84%   |
| 5.11    | 6        | 9.84%   |
| 5.5     | 4        | 6.56%   |
| 5.3     | 3        | 4.92%   |
| 5.16    | 3        | 4.92%   |
| 5.6     | 2        | 3.28%   |
| 5.4     | 2        | 3.28%   |
| 5.12    | 2        | 3.28%   |
| 4.19    | 2        | 3.28%   |
| 5.2     | 1        | 1.64%   |
| 5.14    | 1        | 1.64%   |
| 4.20    | 1        | 1.64%   |
| 4.18    | 1        | 1.64%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 58       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 11       | 18.97%  |
| X-Cinnamon | 9        | 15.52%  |
| KDE        | 8        | 13.79%  |
| Deepin     | 7        | 12.07%  |
| Unknown    | 7        | 12.07%  |
| XFCE       | 6        | 10.34%  |
| Budgie     | 3        | 5.17%   |
| LXQt       | 2        | 3.45%   |
| KDE5       | 2        | 3.45%   |
| MATE       | 1        | 1.72%   |
| i3         | 1        | 1.72%   |
| Cinnamon   | 1        | 1.72%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 51       | 87.93%  |
| Wayland | 7        | 12.07%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 50       | 84.75%  |
| TDM     | 4        | 6.78%   |
| GDM     | 3        | 5.08%   |
| SDDM    | 1        | 1.69%   |
| LightDM | 1        | 1.69%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 22       | 37.93%  |
| Unknown | 8        | 13.79%  |
| es_ES   | 5        | 8.62%   |
| en_GB   | 5        | 8.62%   |
| de_DE   | 5        | 8.62%   |
| es_AR   | 2        | 3.45%   |
| en_AU   | 2        | 3.45%   |
| ru_UA   | 1        | 1.72%   |
| ru_RU   | 1        | 1.72%   |
| pt_BR   | 1        | 1.72%   |
| fr_FR   | 1        | 1.72%   |
| es_PA   | 1        | 1.72%   |
| en_PH   | 1        | 1.72%   |
| en_CA   | 1        | 1.72%   |
| el_GR   | 1        | 1.72%   |
| de_AT   | 1        | 1.72%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 41       | 70.69%  |
| EFI  | 17       | 29.31%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 43       | 74.14%  |
| Unknown | 8        | 13.79%  |
| Tmpfs   | 4        | 6.9%    |
| Xfs     | 3        | 5.17%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 49       | 84.48%  |
| GPT     | 8        | 13.79%  |
| MBR     | 1        | 1.72%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 54       | 93.1%   |
| Yes       | 4        | 6.9%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 53       | 89.83%  |
| Yes       | 6        | 10.17%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 17       | 29.31%  |
| Gigabyte Technology | 9        | 15.52%  |
| ASRock              | 7        | 12.07%  |
| MSI                 | 6        | 10.34%  |
| Dell                | 6        | 10.34%  |
| Lenovo              | 3        | 5.17%   |
| Hewlett-Packard     | 2        | 3.45%   |
| Shuttle             | 1        | 1.72%   |
| Pegatron            | 1        | 1.72%   |
| OEM                 | 1        | 1.72%   |
| Medion              | 1        | 1.72%   |
| Intel               | 1        | 1.72%   |
| Huanan              | 1        | 1.72%   |
| Foxconn             | 1        | 1.72%   |
| Acer                | 1        | 1.72%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| MSI MS-7721                     | 2        | 3.45%   |
| ASRock X570 Phantom Gaming 4    | 2        | 3.45%   |
| Shuttle SZ270                   | 1        | 1.72%   |
| Pegatron CQ3476L                | 1        | 1.72%   |
| OEM G41 775 ICH7 8712           | 1        | 1.72%   |
| MSI WK711AA-ACB HPE-110ru       | 1        | 1.72%   |
| MSI MS-7C35                     | 1        | 1.72%   |
| MSI MS-7A36                     | 1        | 1.72%   |
| MSI MS-7998                     | 1        | 1.72%   |
| Medion P961x                    | 1        | 1.72%   |
| Lenovo ThinkCentre M92 32071F5  | 1        | 1.72%   |
| Lenovo ThinkCentre M91p 0266RZ1 | 1        | 1.72%   |
| Lenovo ThinkCentre M58 6258WCY  | 1        | 1.72%   |
| Intel DH55HC AAE70933-501       | 1        | 1.72%   |
| Huanan X79-8D VAA31             | 1        | 1.72%   |
| HP Pavilion Desktop PC 570-p0XX | 1        | 1.72%   |
| HP Compaq 6000 Pro MT PC        | 1        | 1.72%   |
| Gigabyte Z87-HD3                | 1        | 1.72%   |
| Gigabyte X570 AORUS ELITE       | 1        | 1.72%   |
| Gigabyte H61M-DS2               | 1        | 1.72%   |
| Gigabyte H110M-S2PT-CF          | 1        | 1.72%   |
| Gigabyte GA-880GM-UD2H          | 1        | 1.72%   |
| Gigabyte F2A85X-UP4             | 1        | 1.72%   |
| Gigabyte F2A75-D3H              | 1        | 1.72%   |
| Gigabyte EP43-UD3L              | 1        | 1.72%   |
| Gigabyte B450 AORUS M           | 1        | 1.72%   |
| Foxconn H61S                    | 1        | 1.72%   |
| Dell XPS 8300                   | 1        | 1.72%   |
| Dell OptiPlex 780               | 1        | 1.72%   |
| Dell OptiPlex 7040              | 1        | 1.72%   |
| Dell OptiPlex 7020              | 1        | 1.72%   |
| Dell OptiPlex 7010              | 1        | 1.72%   |
| Dell Inspiron 660               | 1        | 1.72%   |
| ASUS Z8NA-D6                    | 1        | 1.72%   |
| ASUS STRIX H270F GAMING         | 1        | 1.72%   |
| ASUS ROG STRIX X570-I GAMING    | 1        | 1.72%   |
| ASUS ROG STRIX B450-F GAMING    | 1        | 1.72%   |
| ASUS ROG STRIX B350-F GAMING    | 1        | 1.72%   |
| ASUS Q87M-XA                    | 1        | 1.72%   |
| ASUS PRIME Z270-A               | 1        | 1.72%   |
| ASUS PRIME X370-PRO             | 1        | 1.72%   |
| ASUS PRIME H310M-K R2.0         | 1        | 1.72%   |
| ASUS PRIME H110M-P              | 1        | 1.72%   |
| ASUS PRIME B450M-A              | 1        | 1.72%   |
| ASUS P8Z77-V DELUXE             | 1        | 1.72%   |
| ASUS P8B75-V                    | 1        | 1.72%   |
| ASUS P7H55-M PRO                | 1        | 1.72%   |
| ASUS P5KPL-AM SE                | 1        | 1.72%   |
| ASUS M5A99X EVO                 | 1        | 1.72%   |
| ASUS All Series                 | 1        | 1.72%   |
| ASRock X570 Taichi              | 1        | 1.72%   |
| ASRock H97M Pro4                | 1        | 1.72%   |
| ASRock H81M-HDS                 | 1        | 1.72%   |
| ASRock B450M Pro4               | 1        | 1.72%   |
| ASRock 960GM-VGS3 FX            | 1        | 1.72%   |
| Acer Aspire TC-885              | 1        | 1.72%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 5        | 8.62%   |
| Dell OptiPlex          | 4        | 6.9%    |
| Lenovo ThinkCentre     | 3        | 5.17%   |
| ASUS ROG               | 3        | 5.17%   |
| ASRock X570            | 3        | 5.17%   |
| MSI MS-7721            | 2        | 3.45%   |
| Shuttle SZ270          | 1        | 1.72%   |
| Pegatron CQ3476L       | 1        | 1.72%   |
| OEM G41                | 1        | 1.72%   |
| MSI WK711AA-ACB        | 1        | 1.72%   |
| MSI MS-7C35            | 1        | 1.72%   |
| MSI MS-7A36            | 1        | 1.72%   |
| MSI MS-7998            | 1        | 1.72%   |
| Medion P961x           | 1        | 1.72%   |
| Intel DH55HC           | 1        | 1.72%   |
| Huanan X79-8D          | 1        | 1.72%   |
| HP Pavilion            | 1        | 1.72%   |
| HP Compaq              | 1        | 1.72%   |
| Gigabyte Z87-HD3       | 1        | 1.72%   |
| Gigabyte X570          | 1        | 1.72%   |
| Gigabyte H61M-DS2      | 1        | 1.72%   |
| Gigabyte H110M-S2PT-CF | 1        | 1.72%   |
| Gigabyte GA-880GM-UD2H | 1        | 1.72%   |
| Gigabyte F2A85X-UP4    | 1        | 1.72%   |
| Gigabyte F2A75-D3H     | 1        | 1.72%   |
| Gigabyte EP43-UD3L     | 1        | 1.72%   |
| Gigabyte B450          | 1        | 1.72%   |
| Foxconn H61S           | 1        | 1.72%   |
| Dell XPS               | 1        | 1.72%   |
| Dell Inspiron          | 1        | 1.72%   |
| ASUS Z8NA-D6           | 1        | 1.72%   |
| ASUS STRIX             | 1        | 1.72%   |
| ASUS Q87M-XA           | 1        | 1.72%   |
| ASUS P8Z77-V           | 1        | 1.72%   |
| ASUS P8B75-V           | 1        | 1.72%   |
| ASUS P7H55-M           | 1        | 1.72%   |
| ASUS P5KPL-AM          | 1        | 1.72%   |
| ASUS M5A99X            | 1        | 1.72%   |
| ASUS All               | 1        | 1.72%   |
| ASRock H97M            | 1        | 1.72%   |
| ASRock H81M-HDS        | 1        | 1.72%   |
| ASRock B450M           | 1        | 1.72%   |
| ASRock 960GM-VGS3      | 1        | 1.72%   |
| Acer Aspire            | 1        | 1.72%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 9        | 15.52%  |
| 2012 | 8        | 13.79%  |
| 2013 | 7        | 12.07%  |
| 2018 | 6        | 10.34%  |
| 2016 | 5        | 8.62%   |
| 2010 | 5        | 8.62%   |
| 2009 | 5        | 8.62%   |
| 2017 | 4        | 6.9%    |
| 2011 | 3        | 5.17%   |
| 2014 | 2        | 3.45%   |
| 2008 | 2        | 3.45%   |
| 2020 | 1        | 1.72%   |
| 2015 | 1        | 1.72%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 58       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 58       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 58       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 17       | 28.33%  |
| 8.01-16.0   | 15       | 25%     |
| 4.01-8.0    | 12       | 20%     |
| 32.01-64.0  | 9        | 15%     |
| 3.01-4.0    | 5        | 8.33%   |
| 64.01-256.0 | 1        | 1.67%   |
| 1.01-2.0    | 1        | 1.67%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 24       | 39.34%  |
| 2.01-3.0  | 18       | 29.51%  |
| 4.01-8.0  | 8        | 13.11%  |
| 3.01-4.0  | 7        | 11.48%  |
| 8.01-16.0 | 2        | 3.28%   |
| 0.51-1.0  | 2        | 3.28%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 20       | 33.9%   |
| 2      | 18       | 30.51%  |
| 4      | 8        | 13.56%  |
| 3      | 8        | 13.56%  |
| 0      | 2        | 3.39%   |
| 7      | 1        | 1.69%   |
| 6      | 1        | 1.69%   |
| 5      | 1        | 1.69%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 30       | 50.85%  |
| No        | 29       | 49.15%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 54       | 93.1%   |
| No        | 4        | 6.9%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 30       | 51.72%  |
| No        | 28       | 48.28%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 38       | 65.52%  |
| Yes       | 20       | 34.48%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 15       | 25.86%  |
| Germany     | 6        | 10.34%  |
| UK          | 5        | 8.62%   |
| Spain       | 5        | 8.62%   |
| Canada      | 4        | 6.9%    |
| Netherlands | 3        | 5.17%   |
| Thailand    | 2        | 3.45%   |
| Panama      | 2        | 3.45%   |
| India       | 2        | 3.45%   |
| Greece      | 2        | 3.45%   |
| Argentina   | 2        | 3.45%   |
| Ukraine     | 1        | 1.72%   |
| Russia      | 1        | 1.72%   |
| Philippines | 1        | 1.72%   |
| Hungary     | 1        | 1.72%   |
| Egypt       | 1        | 1.72%   |
| Colombia    | 1        | 1.72%   |
| Brazil      | 1        | 1.72%   |
| Azerbaijan  | 1        | 1.72%   |
| Austria     | 1        | 1.72%   |
| Australia   | 1        | 1.72%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Desktops | Percent |
|--------------------|----------|---------|
| Miami              | 2        | 3.33%   |
| Lelystad           | 2        | 3.33%   |
| Cologne            | 2        | 3.33%   |
| Athens             | 2        | 3.33%   |
| Zutphen            | 1        | 1.67%   |
| Wuppertal          | 1        | 1.67%   |
| Winsted            | 1        | 1.67%   |
| Watford            | 1        | 1.67%   |
| Verwood            | 1        | 1.67%   |
| Tres Cantos        | 1        | 1.67%   |
| Toledo             | 1        | 1.67%   |
| Szekszárd         | 1        | 1.67%   |
| Sydney             | 1        | 1.67%   |
| Surrey             | 1        | 1.67%   |
| Stuttgart          | 1        | 1.67%   |
| Streatham          | 1        | 1.67%   |
| Spremberg          | 1        | 1.67%   |
| Southampton        | 1        | 1.67%   |
| Smithfield         | 1        | 1.67%   |
| Si Racha           | 1        | 1.67%   |
| Seville            | 1        | 1.67%   |
| Sao Paulo          | 1        | 1.67%   |
| Santa Clara        | 1        | 1.67%   |
| Salt Lake City     | 1        | 1.67%   |
| Reno               | 1        | 1.67%   |
| Quezon City        | 1        | 1.67%   |
| Queens             | 1        | 1.67%   |
| Purdon             | 1        | 1.67%   |
| Pont-y-clun        | 1        | 1.67%   |
| Phoenix            | 1        | 1.67%   |
| Novosibirsk        | 1        | 1.67%   |
| Newcastle          | 1        | 1.67%   |
| New Delhi          | 1        | 1.67%   |
| Mascouche          | 1        | 1.67%   |
| Lehigh Acres       | 1        | 1.67%   |
| Kyiv               | 1        | 1.67%   |
| Kochi              | 1        | 1.67%   |
| Kentville          | 1        | 1.67%   |
| Ibiza Town         | 1        | 1.67%   |
| Helwan             | 1        | 1.67%   |
| Graz               | 1        | 1.67%   |
| Düsseldorf        | 1        | 1.67%   |
| Dortmund           | 1        | 1.67%   |
| Derby              | 1        | 1.67%   |
| David              | 1        | 1.67%   |
| Cervera            | 1        | 1.67%   |
| Bugaba             | 1        | 1.67%   |
| Buffalo            | 1        | 1.67%   |
| Bowling Green      | 1        | 1.67%   |
| Bogotá            | 1        | 1.67%   |
| Boca de la Zanja   | 1        | 1.67%   |
| Bluefield          | 1        | 1.67%   |
| Bastrop            | 1        | 1.67%   |
| Bang Lamung        | 1        | 1.67%   |
| Banda del Rio Sali | 1        | 1.67%   |
| Baku               | 1        | 1.67%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 27       | 33     | 23.89%  |
| Seagate             | 16       | 22     | 14.16%  |
| Samsung Electronics | 15       | 17     | 13.27%  |
| Toshiba             | 8        | 9      | 7.08%   |
| Phison              | 6        | 7      | 5.31%   |
| Hitachi             | 6        | 6      | 5.31%   |
| Kingston            | 4        | 4      | 3.54%   |
| Crucial             | 4        | 5      | 3.54%   |
| SanDisk             | 3        | 4      | 2.65%   |
| ZOTAC               | 2        | 2      | 1.77%   |
| Unknown             | 2        | 2      | 1.77%   |
| PNY                 | 2        | 2      | 1.77%   |
| Intel               | 2        | 2      | 1.77%   |
| SPCC                | 1        | 1      | 0.88%   |
| Phison Electronics  | 1        | 2      | 0.88%   |
| Patriot             | 1        | 1      | 0.88%   |
| OCZ                 | 1        | 2      | 0.88%   |
| KingSpec            | 1        | 1      | 0.88%   |
| JMicron             | 1        | 1      | 0.88%   |
| HGST                | 1        | 1      | 0.88%   |
| Hewlett-Packard     | 1        | 2      | 0.88%   |
| Gigabyte Technology | 1        | 2      | 0.88%   |
| Emtec               | 1        | 1      | 0.88%   |
| DREVO               | 1        | 1      | 0.88%   |
| Dell                | 1        | 1      | 0.88%   |
| ASMT                | 1        | 1      | 0.88%   |
| AMD                 | 1        | 1      | 0.88%   |
| addlink             | 1        | 1      | 0.88%   |
| A-DATA Technology   | 1        | 1      | 0.88%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Samsung SSD 860 EVO 500GB          | 3        | 2.38%   |
| WDC WD10EZEX-08WN4A0 1TB           | 2        | 1.59%   |
| WDC WD1002FAEX-00Z3A0 1TB          | 2        | 1.59%   |
| WDC WD1001FALS-403AA0 1TB          | 2        | 1.59%   |
| Toshiba DT01ACA100 1TB             | 2        | 1.59%   |
| Seagate ST3500312CS 500GB          | 2        | 1.59%   |
| Seagate ST2000DM006-2DM164 2TB     | 2        | 1.59%   |
| Seagate ST1000DM003-1CH162 1TB     | 2        | 1.59%   |
| Samsung SSD 850 EVO 500GB          | 2        | 1.59%   |
| PNY CS900 120GB SSD                | 2        | 1.59%   |
| Phison NVMe SSD Drive 960GB        | 2        | 1.59%   |
| Phison NVMe SSD Drive 240GB        | 2        | 1.59%   |
| Phison NVMe SSD Drive 1TB          | 2        | 1.59%   |
| ZOTAC ZTSSD-S11-120G-P 120GB       | 1        | 0.79%   |
| ZOTAC ZTSSD-A4P-120G               | 1        | 0.79%   |
| WDC WDS500G2X0C-00L350 500GB       | 1        | 0.79%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 1        | 0.79%   |
| WDC WDS100T3X0C-00SJG0 1TB         | 1        | 0.79%   |
| WDC WD6400AAKS-22A7B0 640GB        | 1        | 0.79%   |
| WDC WD6400AAKS-00A7B2 640GB        | 1        | 0.79%   |
| WDC WD5000LPVX-00V0TT0 500GB       | 1        | 0.79%   |
| WDC WD5000AZLX-00JKKA0 500GB       | 1        | 0.79%   |
| WDC WD5000AVDS-63U7B1 500GB        | 1        | 0.79%   |
| WDC WD5000AAKX-753CA1 500GB        | 1        | 0.79%   |
| WDC WD5000AADS-00S9B0 500GB        | 1        | 0.79%   |
| WDC WD3200AAKS-00UU3A0 320GB       | 1        | 0.79%   |
| WDC WD30PURX-64P6ZY0 3TB           | 1        | 0.79%   |
| WDC WD2500JS-00MHB0 250GB          | 1        | 0.79%   |
| WDC WD20EZRX-00D8PB0 2TB           | 1        | 0.79%   |
| WDC WD20EURX-63T0FY0 2TB           | 1        | 0.79%   |
| WDC WD2003FZEX-00SRLA0 2TB         | 1        | 0.79%   |
| WDC WD2003FYPS-27Y2B0 2TB          | 1        | 0.79%   |
| WDC WD15EADS-65P8B1 1TB            | 1        | 0.79%   |
| WDC WD10EZRX-00L4HB0 1TB           | 1        | 0.79%   |
| WDC WD10EZEX-21WN4A0 1TB           | 1        | 0.79%   |
| WDC WD10EZEX-00WN4A0 1TB           | 1        | 0.79%   |
| WDC WD10EZEX-00BN5A0 1TB           | 1        | 0.79%   |
| WDC WD10EARS-00Y5B1 1TB            | 1        | 0.79%   |
| WDC WD10EADS-65M2B1 1TB            | 1        | 0.79%   |
| WDC WD1002FAEX-00Y9A0 1TB          | 1        | 0.79%   |
| Unknown SD/MMC/MS PRO 999GB        | 1        | 0.79%   |
| Unknown NVMe SSD Drive 512GB       | 1        | 0.79%   |
| Toshiba TL100 240GB SSD            | 1        | 0.79%   |
| Toshiba THNSN5512GPUK NVMe 512GB   | 1        | 0.79%   |
| Toshiba NVMe SSD Drive 512GB       | 1        | 0.79%   |
| Toshiba MK5075GSX 500GB            | 1        | 0.79%   |
| Toshiba MK3256GSY 320GB            | 1        | 0.79%   |
| Toshiba HDWD120 2TB                | 1        | 0.79%   |
| SPCC M.2 PCIe SSD 1TB              | 1        | 0.79%   |
| Seagate ST500NM0011 500GB          | 1        | 0.79%   |
| Seagate ST500LM030-2E717D 500GB    | 1        | 0.79%   |
| Seagate ST500DM002-1BD142 500GB    | 1        | 0.79%   |
| Seagate ST4000DM004-2CV104 4TB     | 1        | 0.79%   |
| Seagate ST3500418AS 500GB          | 1        | 0.79%   |
| Seagate ST3250824AS 250GB          | 1        | 0.79%   |
| Seagate ST3160023AS 160GB          | 1        | 0.79%   |
| Seagate ST3000LM024-2AN17R 3TB     | 1        | 0.79%   |
| Seagate ST3000DM001-1ER166 3TB     | 1        | 0.79%   |
| Seagate ST2000DX002-2DV164 2TB     | 1        | 0.79%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1        | 0.79%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 24       | 29     | 42.86%  |
| Seagate             | 16       | 22     | 28.57%  |
| Hitachi             | 6        | 6      | 10.71%  |
| Toshiba             | 5        | 5      | 8.93%   |
| Samsung Electronics | 2        | 2      | 3.57%   |
| Unknown             | 1        | 1      | 1.79%   |
| HGST                | 1        | 1      | 1.79%   |
| ASMT                | 1        | 1      | 1.79%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 12       | 12     | 32.43%  |
| Kingston            | 4        | 4      | 10.81%  |
| Crucial             | 3        | 4      | 8.11%   |
| ZOTAC               | 2        | 2      | 5.41%   |
| SanDisk             | 2        | 3      | 5.41%   |
| PNY                 | 2        | 2      | 5.41%   |
| WDC                 | 1        | 1      | 2.7%    |
| Toshiba             | 1        | 1      | 2.7%    |
| Patriot             | 1        | 1      | 2.7%    |
| OCZ                 | 1        | 2      | 2.7%    |
| KingSpec            | 1        | 1      | 2.7%    |
| JMicron             | 1        | 1      | 2.7%    |
| Hewlett-Packard     | 1        | 2      | 2.7%    |
| Gigabyte Technology | 1        | 2      | 2.7%    |
| Emtec               | 1        | 1      | 2.7%    |
| DREVO               | 1        | 1      | 2.7%    |
| AMD                 | 1        | 1      | 2.7%    |
| A-DATA Technology   | 1        | 1      | 2.7%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 40       | 67     | 45.45%  |
| SSD     | 28       | 42     | 31.82%  |
| NVMe    | 18       | 24     | 20.45%  |
| Unknown | 2        | 2      | 2.27%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 52       | 105    | 69.33%  |
| NVMe | 18       | 24     | 24%     |
| SAS  | 5        | 6      | 6.67%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 40       | 60     | 49.38%  |
| 0.51-1.0   | 29       | 33     | 35.8%   |
| 1.01-2.0   | 7        | 9      | 8.64%   |
| 2.01-3.0   | 3        | 4      | 3.7%    |
| 3.01-4.0   | 1        | 1      | 1.23%   |
| 4.01-10.0  | 1        | 2      | 1.23%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 16       | 27.59%  |
| 251-500        | 10       | 17.24%  |
| 101-250        | 10       | 17.24%  |
| More than 3000 | 6        | 10.34%  |
| 1001-2000      | 4        | 6.9%    |
| 51-100         | 4        | 6.9%    |
| 2001-3000      | 3        | 5.17%   |
| Unknown        | 3        | 5.17%   |
| 21-50          | 2        | 3.45%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 21-50     | 19       | 31.15%  |
| 1-20      | 19       | 31.15%  |
| 501-1000  | 5        | 8.2%    |
| 251-500   | 4        | 6.56%   |
| 51-100    | 4        | 6.56%   |
| 2001-3000 | 3        | 4.92%   |
| 101-250   | 3        | 4.92%   |
| Unknown   | 3        | 4.92%   |
| 1001-2000 | 1        | 1.64%   |

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
| Detected | 49       | 108    | 85.96%  |
| Works    | 8        | 27     | 14.04%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 37       | 46.25%  |
| AMD                          | 19       | 23.75%  |
| Phison Electronics           | 8        | 10%     |
| Samsung Electronics          | 4        | 5%      |
| Sandisk                      | 3        | 3.75%   |
| JMicron Technology           | 3        | 3.75%   |
| Toshiba America Info Systems | 2        | 2.5%    |
| Nvidia                       | 1        | 1.25%   |
| Micron/Crucial Technology    | 1        | 1.25%   |
| ASMedia Technology           | 1        | 1.25%   |
| ADATA Technology             | 1        | 1.25%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 16       | 14.95%  |
| Phison E12 NVMe Controller                                                              | 5        | 4.67%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 5        | 4.67%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4        | 3.74%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4        | 3.74%   |
| AMD 400 Series Chipset SATA Controller                                                  | 4        | 3.74%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3        | 2.8%    |
| Intel SATA Controller [RAID mode]                                                       | 3        | 2.8%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 3        | 2.8%    |
| Intel 4 Series Chipset PT IDER Controller                                               | 3        | 2.8%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3        | 2.8%    |
| Phison E16 PCIe4 NVMe Controller                                                        | 2        | 1.87%   |
| JMicron JMB368 IDE controller                                                           | 2        | 1.87%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2        | 1.87%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 2        | 1.87%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 2        | 1.87%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2        | 1.87%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 2        | 1.87%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]           | 2        | 1.87%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 1.87%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 1.87%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2        | 1.87%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 2        | 1.87%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 2        | 1.87%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2        | 1.87%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                                    | 1        | 0.93%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller        | 1        | 0.93%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 1        | 0.93%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1        | 0.93%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1        | 0.93%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 0.93%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1        | 0.93%   |
| Phison E7 NVMe Controller                                                               | 1        | 0.93%   |
| Nvidia MCP61 SATA Controller                                                            | 1        | 0.93%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 1        | 0.93%   |
| JMicron JMB362 SATA Controller                                                          | 1        | 0.93%   |
| Intel SSD 660P Series                                                                   | 1        | 0.93%   |
| Intel SSD 600P Series                                                                   | 1        | 0.93%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1        | 0.93%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1        | 0.93%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 1        | 0.93%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                    | 1        | 0.93%   |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode]           | 1        | 0.93%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 1        | 0.93%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 1        | 0.93%   |
| Intel 5 Series/3400 Series Chipset PT IDER Controller                                   | 1        | 0.93%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 1        | 0.93%   |
| AMD X370 Series Chipset SATA Controller                                                 | 1        | 0.93%   |
| AMD FCH SATA Controller D                                                               | 1        | 0.93%   |
| AMD 300 Series Chipset SATA Controller                                                  | 1        | 0.93%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 1        | 0.93%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 42       | 51.85%  |
| NVMe | 18       | 22.22%  |
| IDE  | 18       | 22.22%  |
| RAID | 3        | 3.7%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 37       | 63.79%  |
| AMD    | 21       | 36.21%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 4        | 6.78%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 3.39%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 2        | 3.39%   |
| AMD Ryzen 5 3600 6-Core Processor           | 2        | 3.39%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 2        | 3.39%   |
| AMD A4-5300 APU with Radeon HD Graphics     | 2        | 3.39%   |
| AMD A10-5800K APU with Radeon HD Graphics   | 2        | 3.39%   |
| Intel Xeon CPU E5530 @ 2.40GHz              | 1        | 1.69%   |
| Intel Xeon CPU E5-2697 v2 @ 2.70GHz         | 1        | 1.69%   |
| Intel Xeon CPU E3-1270 V2 @ 3.50GHz         | 1        | 1.69%   |
| Intel Xeon CPU E3-1225 v5 @ 3.30GHz         | 1        | 1.69%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 1        | 1.69%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 1        | 1.69%   |
| Intel Pentium CPU G3258 @ 3.20GHz           | 1        | 1.69%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 1.69%   |
| Intel Core i7-6700T CPU @ 2.80GHz           | 1        | 1.69%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1        | 1.69%   |
| Intel Core i7-4770S CPU @ 3.10GHz           | 1        | 1.69%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1        | 1.69%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 1        | 1.69%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 1        | 1.69%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1        | 1.69%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 1        | 1.69%   |
| Intel Core i5-6500T CPU @ 2.50GHz           | 1        | 1.69%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 1        | 1.69%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 1        | 1.69%   |
| Intel Core i5-4570T CPU @ 2.90GHz           | 1        | 1.69%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 1        | 1.69%   |
| Intel Core i5-3340 CPU @ 3.10GHz            | 1        | 1.69%   |
| Intel Core i5-2400S CPU @ 2.50GHz           | 1        | 1.69%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 1        | 1.69%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 1        | 1.69%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 1        | 1.69%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 1        | 1.69%   |
| Intel Core i3 CPU 540 @ 3.07GHz             | 1        | 1.69%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 1        | 1.69%   |
| Intel Core 2 Duo CPU E7200 @ 2.53GHz        | 1        | 1.69%   |
| Intel Core 2 Duo CPU E6750 @ 2.66GHz        | 1        | 1.69%   |
| Intel Celeron CPU G3930 @ 2.90GHz           | 1        | 1.69%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 1        | 1.69%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 1        | 1.69%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 1        | 1.69%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 1        | 1.69%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 1        | 1.69%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 1        | 1.69%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 1        | 1.69%   |
| AMD Phenom II X4 955 Processor              | 1        | 1.69%   |
| AMD FX-9590 Eight-Core Processor            | 1        | 1.69%   |
| AMD FX-6300 Six-Core Processor              | 1        | 1.69%   |
| AMD Athlon II X2 255 Processor              | 1        | 1.69%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 15       | 25.42%  |
| Intel Core 2 Duo        | 7        | 11.86%  |
| Intel Core i7           | 6        | 10.17%  |
| AMD Ryzen 5             | 6        | 10.17%  |
| AMD Ryzen 7             | 5        | 8.47%   |
| Intel Xeon              | 4        | 6.78%   |
| Intel Pentium           | 2        | 3.39%   |
| Intel Core i3           | 2        | 3.39%   |
| AMD FX                  | 2        | 3.39%   |
| AMD A4                  | 2        | 3.39%   |
| AMD A10                 | 2        | 3.39%   |
| Intel Pentium Dual-Core | 1        | 1.69%   |
| Intel Celeron           | 1        | 1.69%   |
| AMD Ryzen 9             | 1        | 1.69%   |
| AMD Ryzen 3             | 1        | 1.69%   |
| AMD Phenom II X4        | 1        | 1.69%   |
| AMD Athlon II X2        | 1        | 1.69%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 22       | 37.93%  |
| 2      | 17       | 29.31%  |
| 6      | 8        | 13.79%  |
| 8      | 6        | 10.34%  |
| 1      | 2        | 3.45%   |
| 24     | 1        | 1.72%   |
| 12     | 1        | 1.72%   |
| 3      | 1        | 1.72%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 56       | 96.55%  |
| 2      | 2        | 3.45%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 31       | 53.45%  |
| 1      | 27       | 46.55%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 51       | 87.93%  |
| Unknown        | 7        | 12.07%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 10       | 16.95%  |
| 0x506e3    | 5        | 8.47%   |
| 0x306c3    | 5        | 8.47%   |
| 0x306a9    | 5        | 8.47%   |
| 0x206a7    | 4        | 6.78%   |
| 0x0800820d | 4        | 6.78%   |
| 0x06001119 | 4        | 6.78%   |
| 0x906e9    | 3        | 5.08%   |
| 0x20652    | 2        | 3.39%   |
| 0x1067a    | 2        | 3.39%   |
| 0x906ea    | 1        | 1.69%   |
| 0x6fb      | 1        | 1.69%   |
| 0x306e4    | 1        | 1.69%   |
| 0x106e5    | 1        | 1.69%   |
| 0x106a5    | 1        | 1.69%   |
| 0x10676    | 1        | 1.69%   |
| 0x0a201016 | 1        | 1.69%   |
| 0x0a201009 | 1        | 1.69%   |
| 0x08701021 | 1        | 1.69%   |
| 0x08108109 | 1        | 1.69%   |
| 0x08001138 | 1        | 1.69%   |
| 0x0600081c | 1        | 1.69%   |
| 0x06000817 | 1        | 1.69%   |
| 0x010000c8 | 1        | 1.69%   |
| 0x010000b6 | 1        | 1.69%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Zen+        | 6        | 10.34%  |
| Piledriver  | 6        | 10.34%  |
| Penryn      | 6        | 10.34%  |
| IvyBridge   | 6        | 10.34%  |
| Haswell     | 6        | 10.34%  |
| Skylake     | 5        | 8.62%   |
| KabyLake    | 5        | 8.62%   |
| Zen 2       | 4        | 6.9%    |
| SandyBridge | 4        | 6.9%    |
| Zen         | 2        | 3.45%   |
| Westmere    | 2        | 3.45%   |
| Nehalem     | 2        | 3.45%   |
| K10         | 2        | 3.45%   |
| Zen 3       | 1        | 1.72%   |
| Core        | 1        | 1.72%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 27       | 43.55%  |
| AMD               | 19       | 30.65%  |
| Intel             | 15       | 24.19%  |
| ASPEED Technology | 1        | 1.61%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia GK208B [GeForce GT 710]                                              | 4        | 6.15%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 4        | 6.15%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3        | 4.62%   |
| Nvidia GF108 [GeForce GT 730]                                               | 3        | 4.62%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 4.62%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 2        | 3.08%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 3.08%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 3.08%   |
| Intel HD Graphics 530                                                       | 2        | 3.08%   |
| AMD Trinity [Radeon HD 7660D]                                               | 2        | 3.08%   |
| AMD Curacao XT / Trinidad XT [Radeon R7 370 / R9 270X/370X]                 | 2        | 3.08%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 1.54%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                      | 1        | 1.54%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 1.54%   |
| Nvidia GT216M [GeForce GT 330M]                                             | 1        | 1.54%   |
| Nvidia GT200GL [Quadro FX 4800]                                             | 1        | 1.54%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 1.54%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 1.54%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 1.54%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 1.54%   |
| Nvidia GM204 [GeForce GTX 980]                                              | 1        | 1.54%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1        | 1.54%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 1.54%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 1        | 1.54%   |
| Nvidia GK104GL [Tesla K10]                                                  | 1        | 1.54%   |
| Nvidia GF119 [NVS 310]                                                      | 1        | 1.54%   |
| Nvidia GF119 [GeForce GT 610]                                               | 1        | 1.54%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 1.54%   |
| Nvidia GF108 [GeForce GT 420]                                               | 1        | 1.54%   |
| Intel HD Graphics P530                                                      | 1        | 1.54%   |
| Intel HD Graphics 630                                                       | 1        | 1.54%   |
| Intel HD Graphics 610                                                       | 1        | 1.54%   |
| Intel Core Processor Integrated Graphics Controller                         | 1        | 1.54%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 1        | 1.54%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1        | 1.54%   |
| ASPEED Technology ASPEED Graphics Family                                    | 1        | 1.54%   |
| AMD Vega 20 [Radeon VII]                                                    | 1        | 1.54%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 1        | 1.54%   |
| AMD Tahiti XT [Radeon HD 7970/8970 OEM / R9 280X]                           | 1        | 1.54%   |
| AMD RV770 [Radeon HD 4850]                                                  | 1        | 1.54%   |
| AMD RV710 [Radeon HD 4350/4550]                                             | 1        | 1.54%   |
| AMD RS780L [Radeon 3000]                                                    | 1        | 1.54%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 1        | 1.54%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 1        | 1.54%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 1        | 1.54%   |
| AMD Ellesmere [Radeon Pro WX 5100]                                          | 1        | 1.54%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 1        | 1.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 25       | 43.1%   |
| 1 x AMD        | 19       | 32.76%  |
| 1 x Intel      | 11       | 18.97%  |
| 3 x Nvidia     | 1        | 1.72%   |
| Intel + Nvidia | 1        | 1.72%   |
| 1 x ASPEED     | 1        | 1.72%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 46       | 77.97%  |
| Proprietary | 12       | 20.34%  |
| Unknown     | 1        | 1.69%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 22       | 37.93%  |
| 1.01-2.0   | 10       | 17.24%  |
| 7.01-8.0   | 7        | 12.07%  |
| 3.01-4.0   | 5        | 8.62%   |
| 0.51-1.0   | 5        | 8.62%   |
| 8.01-16.0  | 3        | 5.17%   |
| 0.01-0.5   | 3        | 5.17%   |
| 2.01-3.0   | 2        | 3.45%   |
| 5.01-6.0   | 1        | 1.72%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 13       | 20.97%  |
| Hewlett-Packard      | 7        | 11.29%  |
| BenQ                 | 6        | 9.68%   |
| Dell                 | 5        | 8.06%   |
| Acer                 | 5        | 8.06%   |
| Philips              | 4        | 6.45%   |
| Goldstar             | 4        | 6.45%   |
| Ancor Communications | 3        | 4.84%   |
| MSI                  | 2        | 3.23%   |
| AOC                  | 2        | 3.23%   |
| Vizio                | 1        | 1.61%   |
| Vestel               | 1        | 1.61%   |
| Unknown              | 1        | 1.61%   |
| Sony                 | 1        | 1.61%   |
| Sceptre Tech         | 1        | 1.61%   |
| Plain Tree Systems   | 1        | 1.61%   |
| Microstep            | 1        | 1.61%   |
| Medion               | 1        | 1.61%   |
| Iiyama               | 1        | 1.61%   |
| GRM                  | 1        | 1.61%   |
| ASUSTek Computer     | 1        | 1.61%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics SA300/SA350 SAM0791 1920x1080 510x287mm 23.0-inch | 2        | 2.86%   |
| MSI Optix MAG27CQ MSI1462 2560x1440 597x336mm 27.0-inch               | 2        | 2.86%   |
| Vizio E500i-A1 VIZ1004 1920x1080 1095x616mm 49.5-inch                 | 1        | 1.43%   |
| Vestel LCD Monitor 32W_LCD_TV                                         | 1        | 1.43%   |
| Unknown LCD Monitor DAC Moniter 5760x1080                             | 1        | 1.43%   |
| Sony TV SNYF301 1920x1080                                             | 1        | 1.43%   |
| Sceptre Tech Sceptre M25 SPT0A05 1920x1080 698x393mm 31.5-inch        | 1        | 1.43%   |
| Samsung Electronics SyncMaster SAM0593 1920x1080 477x268mm 21.5-inch  | 1        | 1.43%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 428x255mm 19.6-inch   | 1        | 1.43%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch     | 1        | 1.43%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 480x270mm 21.7-inch     | 1        | 1.43%   |
| Samsung Electronics S22D300 SAM0B3E 1920x1080 477x268mm 21.5-inch     | 1        | 1.43%   |
| Samsung Electronics LU28R55 SAM1016 3840x2160 632x360mm 28.6-inch     | 1        | 1.43%   |
| Samsung Electronics LCD Monitor SAM0DF7 3840x2160 950x540mm 43.0-inch | 1        | 1.43%   |
| Samsung Electronics LCD Monitor SAM094E 1920x1080 890x500mm 40.2-inch | 1        | 1.43%   |
| Samsung Electronics LCD Monitor SAM07BA 1920x1080 890x500mm 40.2-inch | 1        | 1.43%   |
| Samsung Electronics LCD Monitor S24D300 1920x1080                     | 1        | 1.43%   |
| Samsung Electronics LCD Monitor S22D300 1920x1080                     | 1        | 1.43%   |
| Plain Tree Systems TFT19DXP PTS03A0 1280x1024 376x301mm 19.0-inch     | 1        | 1.43%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch              | 1        | 1.43%   |
| Philips PHL 273V5 PHLC0D2 1920x1080 598x336mm 27.0-inch               | 1        | 1.43%   |
| Philips PHL 246E9Q PHLC17C 1920x1080 527x296mm 23.8-inch              | 1        | 1.43%   |
| Philips LCD Monitor PHL 276E8V 7680x2160                              | 1        | 1.43%   |
| Philips LCD Monitor PHL 276E8V                                        | 1        | 1.43%   |
| MSI Optix G27C2 MSI1462 1920x1080 600x340mm 27.2-inch                 | 1        | 1.43%   |
| MSI MPG341CQR MSI3DA0 3440x1440 797x334mm 34.0-inch                   | 1        | 1.43%   |
| Microstep LCD Monitor Optix MAG24C 3840x1200                          | 1        | 1.43%   |
| Medion LCD Monitor MEDB603 1920x1080 480x270mm 21.7-inch              | 1        | 1.43%   |
| Iiyama PL2493H IVM6148 1920x1080 527x296mm 23.8-inch                  | 1        | 1.43%   |
| Hewlett-Packard x23LED HWP2912 1920x1080 509x286mm 23.0-inch          | 1        | 1.43%   |
| Hewlett-Packard w2228h HWP2810 1680x1050 473x296mm 22.0-inch          | 1        | 1.43%   |
| Hewlett-Packard w2207 HWP26A8 1680x1050 473x296mm 22.0-inch           | 1        | 1.43%   |
| Hewlett-Packard vs19x HWP2658 1280x1024 376x301mm 19.0-inch           | 1        | 1.43%   |
| Hewlett-Packard LCD Monitor x23LED 1920x1080                          | 1        | 1.43%   |
| Hewlett-Packard Compaq S1922 HWP290B 1366x768 413x234mm 18.7-inch     | 1        | 1.43%   |
| Hewlett-Packard 27ea HPN3395 1920x1080 527x296mm 23.8-inch            | 1        | 1.43%   |
| Hewlett-Packard 2159 HWP282A 1920x1080 479x269mm 21.6-inch            | 1        | 1.43%   |
| GRM Q19 cinema GRM2730 1360x768 410x230mm 18.5-inch                   | 1        | 1.43%   |
| Goldstar M228WA GSM563C 1680x1050 434x270mm 20.1-inch                 | 1        | 1.43%   |
| Goldstar L1915S GSM4A90 1280x1024 380x300mm 19.1-inch                 | 1        | 1.43%   |
| Goldstar 32inch FHD GSM76F5 1920x1080 698x392mm 31.5-inch             | 1        | 1.43%   |
| Goldstar 24MP55 GSM5A20 1920x1080 510x290mm 23.1-inch                 | 1        | 1.43%   |
| Dell U2312HM DEL4072 1920x1080 510x287mm 23.0-inch                    | 1        | 1.43%   |
| Dell SE2417HG DELD08C 1920x1080 521x293mm 23.5-inch                   | 1        | 1.43%   |
| Dell LCD Monitor U2713HM 2560x1440                                    | 1        | 1.43%   |
| Dell LCD Monitor 2408WFP                                              | 1        | 1.43%   |
| Dell E2417H DELA0E2 1920x1080 527x296mm 23.8-inch                     | 1        | 1.43%   |
| Dell E2417H DELA0E1 1920x1080 527x296mm 23.8-inch                     | 1        | 1.43%   |
| Dell 2408WFP DELA02C 1920x1200 519x324mm 24.1-inch                    | 1        | 1.43%   |
| BenQ ZOWIE RL LCD BNQ7F4F 1920x1080 530x300mm 24.0-inch               | 1        | 1.43%   |
| BenQ LCD Monitor LCD 7680x2160                                        | 1        | 1.43%   |
| BenQ LCD Monitor LCD                                                  | 1        | 1.43%   |
| BenQ LCD Monitor GC2870 1920x1080                                     | 1        | 1.43%   |
| BenQ LCD Monitor G2220HD                                              | 1        | 1.43%   |
| BenQ LCD BNQ801D 3840x2160 521x293mm 23.5-inch                        | 1        | 1.43%   |
| BenQ GW2470 BNQ78D9 1920x1080 527x296mm 23.8-inch                     | 1        | 1.43%   |
| BenQ GW2280 BNQ78E8 1920x1080 476x268mm 21.5-inch                     | 1        | 1.43%   |
| ASUSTek Computer VP28U AUS28B1 3840x2160 620x340mm 27.8-inch          | 1        | 1.43%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                   | 1        | 1.43%   |
| AOC 2269WM AOC2269 1920x1080 477x268mm 21.5-inch                      | 1        | 1.43%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 31       | 50%     |
| 3840x2160 (4K)     | 4        | 6.45%   |
| 1680x1050 (WSXGA+) | 4        | 6.45%   |
| Unknown            | 4        | 6.45%   |
| 1366x768 (WXGA)    | 3        | 4.84%   |
| 1280x1024 (SXGA)   | 3        | 4.84%   |
| 7680x2160          | 2        | 3.23%   |
| 3440x1440          | 2        | 3.23%   |
| 2560x1440 (QHD)    | 2        | 3.23%   |
| 1440x900 (WXGA+)   | 2        | 3.23%   |
| 5760x1080          | 1        | 1.61%   |
| 3840x1200          | 1        | 1.61%   |
| 1920x1200 (WUXGA)  | 1        | 1.61%   |
| 1600x900 (HD+)     | 1        | 1.61%   |
| 1360x768           | 1        | 1.61%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 11       | 17.46%  |
| Unknown | 9        | 14.29%  |
| 21      | 8        | 12.7%   |
| 24      | 6        | 9.52%   |
| 19      | 5        | 7.94%   |
| 27      | 4        | 6.35%   |
| 18      | 4        | 6.35%   |
| 22      | 3        | 4.76%   |
| 34      | 2        | 3.17%   |
| 31      | 2        | 3.17%   |
| 20      | 2        | 3.17%   |
| 84      | 1        | 1.59%   |
| 72      | 1        | 1.59%   |
| 54      | 1        | 1.59%   |
| 49      | 1        | 1.59%   |
| 46      | 1        | 1.59%   |
| 33      | 1        | 1.59%   |
| 28      | 1        | 1.59%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 19       | 31.15%  |
| 501-600     | 18       | 29.51%  |
| Unknown     | 9        | 14.75%  |
| 601-700     | 4        | 6.56%   |
| 701-800     | 3        | 4.92%   |
| 351-400     | 3        | 4.92%   |
| 1001-1500   | 3        | 4.92%   |
| 1501-2000   | 2        | 3.28%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 38       | 65.52%  |
| Unknown | 9        | 15.52%  |
| 16/10   | 6        | 10.34%  |
| 5/4     | 3        | 5.17%   |
| 21/9    | 2        | 3.45%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 23       | 38.33%  |
| 151-200        | 9        | 15%     |
| Unknown        | 9        | 15%     |
| 351-500        | 5        | 8.33%   |
| More than 1000 | 4        | 6.67%   |
| 301-350        | 4        | 6.67%   |
| 141-150        | 4        | 6.67%   |
| 251-300        | 1        | 1.67%   |
| 501-1000       | 1        | 1.67%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 35       | 57.38%  |
| 101-120 | 10       | 16.39%  |
| Unknown | 9        | 14.75%  |
| 1-50    | 4        | 6.56%   |
| 121-160 | 2        | 3.28%   |
| 161-240 | 1        | 1.64%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 49       | 83.05%  |
| 2     | 7        | 11.86%  |
| 0     | 2        | 3.39%   |
| 3     | 1        | 1.69%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 34       | 41.46%  |
| Intel                           | 29       | 35.37%  |
| Qualcomm Atheros                | 4        | 4.88%   |
| Ralink Technology               | 3        | 3.66%   |
| TP-Link                         | 2        | 2.44%   |
| Microsoft                       | 2        | 2.44%   |
| Broadcom                        | 2        | 2.44%   |
| Xiaomi                          | 1        | 1.22%   |
| Ralink                          | 1        | 1.22%   |
| Qualcomm Atheros Communications | 1        | 1.22%   |
| Nvidia                          | 1        | 1.22%   |
| NetXen Incorporated             | 1        | 1.22%   |
| Belkin Components               | 1        | 1.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 25       | 27.17%  |
| Intel I211 Gigabit Network Connection                                   | 10       | 10.87%  |
| Intel Wi-Fi 6 AX200                                                     | 5        | 5.43%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 3        | 3.26%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 3        | 3.26%   |
| Intel 82567LM-3 Gigabit Network Connection                              | 3        | 3.26%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 2        | 2.17%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 2        | 2.17%   |
| Ralink RT5572 Wireless Adapter                                          | 2        | 2.17%   |
| Intel Wireless-AC 9260                                                  | 2        | 2.17%   |
| Intel Ethernet Connection I217-LM                                       | 2        | 2.17%   |
| Intel Ethernet Connection (2) I219-V                                    | 2        | 2.17%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1        | 1.09%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                   | 1        | 1.09%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                               | 1        | 1.09%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                              | 1        | 1.09%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1        | 1.09%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1        | 1.09%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 1        | 1.09%   |
| Realtek RTL8125 2.5GbE Controller                                       | 1        | 1.09%   |
| Ralink MT7601U Wireless Adapter                                         | 1        | 1.09%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                    | 1        | 1.09%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1        | 1.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1        | 1.09%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1        | 1.09%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 1        | 1.09%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1        | 1.09%   |
| Nvidia MCP61 Ethernet                                                   | 1        | 1.09%   |
| NetXen Incorporated NX3031 Multifunction 1/10-Gigabit Server Adapter    | 1        | 1.09%   |
| Microsoft XBOX ACC                                                      | 1        | 1.09%   |
| Microsoft Xbox 360 Wireless Adapter                                     | 1        | 1.09%   |
| Intel Wireless 8265 / 8275                                              | 1        | 1.09%   |
| Intel Ethernet Connection I217-V                                        | 1        | 1.09%   |
| Intel Ethernet Connection (2) I219-LM                                   | 1        | 1.09%   |
| Intel Ethernet Connection (2) I218-V                                    | 1        | 1.09%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1        | 1.09%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 1        | 1.09%   |
| Intel 82579V Gigabit Network Connection                                 | 1        | 1.09%   |
| Intel 82578DC Gigabit Network Connection                                | 1        | 1.09%   |
| Intel 82574L Gigabit Network Connection                                 | 1        | 1.09%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                         | 1        | 1.09%   |
| Broadcom BCM43217 802.11b/g/n                                           | 1        | 1.09%   |
| Belkin Components F5D8053 N Wireless USB Adapter v3000 [Ralink RT2870]  | 1        | 1.09%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 10       | 31.25%  |
| Realtek Semiconductor           | 8        | 25%     |
| Ralink Technology               | 3        | 9.38%   |
| Qualcomm Atheros                | 3        | 9.38%   |
| TP-Link                         | 2        | 6.25%   |
| Microsoft                       | 2        | 6.25%   |
| Ralink                          | 1        | 3.13%   |
| Qualcomm Atheros Communications | 1        | 3.13%   |
| Broadcom                        | 1        | 3.13%   |
| Belkin Components               | 1        | 3.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 5        | 15.63%  |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 3        | 9.38%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 2        | 6.25%   |
| Ralink RT5572 Wireless Adapter                                          | 2        | 6.25%   |
| Intel Wireless-AC 9260                                                  | 2        | 6.25%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                   | 1        | 3.13%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                               | 1        | 3.13%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                              | 1        | 3.13%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1        | 3.13%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1        | 3.13%   |
| Ralink MT7601U Wireless Adapter                                         | 1        | 3.13%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                    | 1        | 3.13%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1        | 3.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1        | 3.13%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1        | 3.13%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1        | 3.13%   |
| Microsoft XBOX ACC                                                      | 1        | 3.13%   |
| Microsoft Xbox 360 Wireless Adapter                                     | 1        | 3.13%   |
| Intel Wireless 8265 / 8275                                              | 1        | 3.13%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1        | 3.13%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 1        | 3.13%   |
| Broadcom BCM43217 802.11b/g/n                                           | 1        | 3.13%   |
| Belkin Components F5D8053 N Wireless USB Adapter v3000 [Ralink RT2870]  | 1        | 3.13%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 29       | 48.33%  |
| Intel                 | 26       | 43.33%  |
| Xiaomi                | 1        | 1.67%   |
| Qualcomm Atheros      | 1        | 1.67%   |
| Nvidia                | 1        | 1.67%   |
| NetXen Incorporated   | 1        | 1.67%   |
| Broadcom              | 1        | 1.67%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 25       | 41.67%  |
| Intel I211 Gigabit Network Connection                                | 10       | 16.67%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 3        | 5%      |
| Intel 82567LM-3 Gigabit Network Connection                           | 3        | 5%      |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 2        | 3.33%   |
| Intel Ethernet Connection I217-LM                                    | 2        | 3.33%   |
| Intel Ethernet Connection (2) I219-V                                 | 2        | 3.33%   |
| Xiaomi Mi/Redmi series (RNDIS)                                       | 1        | 1.67%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                             | 1        | 1.67%   |
| Realtek RTL8125 2.5GbE Controller                                    | 1        | 1.67%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                        | 1        | 1.67%   |
| Nvidia MCP61 Ethernet                                                | 1        | 1.67%   |
| NetXen Incorporated NX3031 Multifunction 1/10-Gigabit Server Adapter | 1        | 1.67%   |
| Intel Ethernet Connection I217-V                                     | 1        | 1.67%   |
| Intel Ethernet Connection (2) I219-LM                                | 1        | 1.67%   |
| Intel Ethernet Connection (2) I218-V                                 | 1        | 1.67%   |
| Intel 82579V Gigabit Network Connection                              | 1        | 1.67%   |
| Intel 82578DC Gigabit Network Connection                             | 1        | 1.67%   |
| Intel 82574L Gigabit Network Connection                              | 1        | 1.67%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                      | 1        | 1.67%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 54       | 64.29%  |
| WiFi     | 30       | 35.71%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 44       | 74.58%  |
| WiFi     | 15       | 25.42%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 36       | 62.07%  |
| 2     | 16       | 27.59%  |
| 3     | 3        | 5.17%   |
| 0     | 2        | 3.45%   |
| 6     | 1        | 1.72%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 56       | 94.92%  |
| Yes  | 3        | 5.08%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 10       | 50%     |
| Cambridge Silicon Radio | 7        | 35%     |
| ASUSTek Computer        | 2        | 10%     |
| IMC Networks            | 1        | 5%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 7        | 35%     |
| Intel AX200 Bluetooth                               | 5        | 25%     |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2        | 10%     |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 5%      |
| Intel Bluetooth wireless interface                  | 1        | 5%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 5%      |
| IMC Networks Bluetooth Module                       | 1        | 5%      |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 5%      |
| ASUS BCM20702A0                                     | 1        | 5%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 36       | 34.95%  |
| Nvidia                 | 28       | 27.18%  |
| AMD                    | 27       | 26.21%  |
| C-Media Electronics    | 4        | 3.88%   |
| Plantronics            | 1        | 0.97%   |
| Logitech               | 1        | 0.97%   |
| JMTek                  | 1        | 0.97%   |
| Generalplus Technology | 1        | 0.97%   |
| Focusrite-Novation     | 1        | 0.97%   |
| Creative Labs          | 1        | 0.97%   |
| Blue Microphones       | 1        | 0.97%   |
| Alesis                 | 1        | 0.97%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 7        | 5.93%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5        | 4.24%   |
| Intel 200 Series PCH HD Audio                                              | 5        | 4.24%   |
| AMD Starship/Matisse HD Audio Controller                                   | 5        | 4.24%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 5        | 4.24%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 4        | 3.39%   |
| Nvidia GF108 High Definition Audio Controller                              | 4        | 3.39%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4        | 3.39%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4        | 3.39%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4        | 3.39%   |
| AMD FCH Azalia Controller                                                  | 4        | 3.39%   |
| Nvidia GP108 High Definition Audio Controller                              | 3        | 2.54%   |
| Nvidia GP104 High Definition Audio Controller                              | 3        | 2.54%   |
| Nvidia GF119 HDMI Audio Controller                                         | 3        | 2.54%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 3        | 2.54%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3        | 2.54%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 3        | 2.54%   |
| Nvidia GM204 High Definition Audio Controller                              | 2        | 1.69%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2        | 1.69%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2        | 1.69%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 1.69%   |
| AMD Trinity HDMI Audio Controller                                          | 2        | 1.69%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2        | 1.69%   |
| Plantronics RIG 800HD                                                      | 1        | 0.85%   |
| Nvidia TU116 High Definition Audio Controller                              | 1        | 0.85%   |
| Nvidia TU106 High Definition Audio Controller                              | 1        | 0.85%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 0.85%   |
| Nvidia High Definition Audio Controller                                    | 1        | 0.85%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1        | 0.85%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 0.85%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 0.85%   |
| Nvidia GP102 HDMI Audio Controller                                         | 1        | 0.85%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 0.85%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1        | 0.85%   |
| Logitech H600 [Wireless Headset]                                           | 1        | 0.85%   |
| JMTek USB PnP Audio Device                                                 | 1        | 0.85%   |
| Intel Cannon Lake PCH cAVS                                                 | 1        | 0.85%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 1        | 0.85%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 1        | 0.85%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1        | 0.85%   |
| Generalplus Technology Usb Audio Device                                    | 1        | 0.85%   |
| Focusrite-Novation Scarlett Solo (3rd Gen.)                                | 1        | 0.85%   |
| Creative Labs EMU20k2 [Sound Blaster X-Fi Titanium Series]                 | 1        | 0.85%   |
| C-Media Electronics SADES Luna                                             | 1        | 0.85%   |
| C-Media Electronics CM108 Audio Controller                                 | 1        | 0.85%   |
| C-Media Electronics CM106 Like Sound Device                                | 1        | 0.85%   |
| C-Media Electronics Audio Device                                           | 1        | 0.85%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 1        | 0.85%   |
| Blue Microphones Yeti Stereo Microphone                                    | 1        | 0.85%   |
| AMD Vega 20 HDMI Audio [Radeon VII]                                        | 1        | 0.85%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 1        | 0.85%   |
| AMD Tahiti HDMI Audio [Radeon HD 7870 XT / 7950/7970]                      | 1        | 0.85%   |
| AMD RV770 HDMI Audio [Radeon HD 4850/4870]                                 | 1        | 0.85%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 1        | 0.85%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1        | 0.85%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 1        | 0.85%   |
| AMD Navi 10 HDMI Audio                                                     | 1        | 0.85%   |
| AMD Family 17h/19h HD Audio Controller                                     | 1        | 0.85%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 1        | 0.85%   |
| Alesis Q25                                                                 | 1        | 0.85%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 3        | 23.08%  |
| Samsung Electronics | 2        | 15.38%  |
| Crucial             | 2        | 15.38%  |
| Unknown             | 1        | 7.69%   |
| Team                | 1        | 7.69%   |
| SK Hynix            | 1        | 7.69%   |
| Micron Technology   | 1        | 7.69%   |
| G.Skill             | 1        | 7.69%   |
| Corsair             | 1        | 7.69%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s             | 1        | 6.67%   |
| Team RAM TEAMGROUP-SD4-2666 16384MB SODIMM DDR4 2667MT/s | 1        | 6.67%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s   | 1        | 6.67%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM SDRAM 1867MT/s     | 1        | 6.67%   |
| Samsung RAM M378A1K43CB2-CRC 8192MB DIMM DDR4 3500MT/s   | 1        | 6.67%   |
| Micron RAM 16ATF1G64AZ-2G1A2 8192MB DIMM DDR4 2400MT/s   | 1        | 6.67%   |
| Kingston RAM KHX2133C14/8G 8192MB DIMM DDR4 2400MT/s     | 1        | 6.67%   |
| Kingston RAM 99P5471-002.A00LF 2GB DIMM DDR3 1600MT/s    | 1        | 6.67%   |
| Kingston RAM 99P5471-001.A01LF 2GB DIMM DDR3 1333MT/s    | 1        | 6.67%   |
| Kingston RAM 99P5471-001.A00LF 2GB DIMM DDR3 1333MT/s    | 1        | 6.67%   |
| Kingston RAM 9905584-023.A00LF 4GB DIMM DDR3 1600MT/s    | 1        | 6.67%   |
| G.Skill RAM F4-3600C16-8GVKC 8192MB DIMM DDR4 3600MT/s   | 1        | 6.67%   |
| Crucial RAM BLT4G3D1869DT 4096MB DIMM DDR3 1333MT/s      | 1        | 6.67%   |
| Crucial RAM BL16G36C16U4W.M16FE1 16GB DIMM DDR4 3733MT/s | 1        | 6.67%   |
| Corsair RAM CMK64GX4M2D3000C16 32GB DIMM DDR4 3000MT/s   | 1        | 6.67%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Desktops | Percent |
|--------|----------|---------|
| DDR4   | 6        | 50%     |
| DDR3   | 4        | 33.33%  |
| SDRAM  | 1        | 8.33%   |
| LPDDR4 | 1        | 8.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 9        | 90%     |
| SODIMM | 1        | 10%     |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 4        | 33.33%  |
| 4096  | 4        | 33.33%  |
| 32768 | 2        | 16.67%  |
| 16384 | 1        | 8.33%   |
| 2048  | 1        | 8.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 3        | 23.08%  |
| 2400  | 2        | 15.38%  |
| 1333  | 2        | 15.38%  |
| 3733  | 1        | 7.69%   |
| 3600  | 1        | 7.69%   |
| 3500  | 1        | 7.69%   |
| 3000  | 1        | 7.69%   |
| 2667  | 1        | 7.69%   |
| 1867  | 1        | 7.69%   |

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
| Logitech                    | 3        | 33.33%  |
| Samsung Electronics         | 1        | 11.11%  |
| KYE Systems (Mouse Systems) | 1        | 11.11%  |
| IMC Networks                | 1        | 11.11%  |
| Generalplus Technology      | 1        | 11.11%  |
| GEMBIRD                     | 1        | 11.11%  |
| Alcor Micro                 | 1        | 11.11%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920             | 2        | 22.22%  |
| Samsung Galaxy A5 (MTP)                 | 1        | 11.11%  |
| Logitech C922 Pro Stream Webcam         | 1        | 11.11%  |
| KYE Systems (Mouse Systems) Slim 1322AF | 1        | 11.11%  |
| IMC Networks XHC Camera                 | 1        | 11.11%  |
| Generalplus 808 Camera                  | 1        | 11.11%  |
| GEMBIRD USB2.0 PC CAMERA                | 1        | 11.11%  |
| Alcor Micro USB 2.0 PC Camera           | 1        | 11.11%  |

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
| 0     | 50       | 86.21%  |
| 1     | 6        | 10.34%  |
| 2     | 2        | 3.45%   |

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

