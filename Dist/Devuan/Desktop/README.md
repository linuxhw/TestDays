Devuan - Tested Hardware & Statistics (Desktops)
------------------------------------------------

A project to collect tested hardware configurations for Devuan.

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

Total: 100

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [fec7c15063](https://linux-hardware.org/?probe=fec7c15063) | Apr 03, 2024 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [7756c3e23b](https://linux-hardware.org/?probe=7756c3e23b) | Apr 01, 2024 |
| Gigabyte      | Z370 AORUS Gaming 7         | [63429edd54](https://linux-hardware.org/?probe=63429edd54) | Apr 01, 2024 |
| Foxconn       | 2ABF                        | [0348bd12f8](https://linux-hardware.org/?probe=0348bd12f8) | Mar 15, 2024 |
| ASUSTek       | TUF B450-PRO GAMING         | [fbd2947969](https://linux-hardware.org/?probe=fbd2947969) | Mar 13, 2024 |
| ASUSTek       | TUF B450-PRO GAMING         | [3b35cebff6](https://linux-hardware.org/?probe=3b35cebff6) | Mar 12, 2024 |
| Gigabyte      | B360M HD3                   | [63a3f8ce29](https://linux-hardware.org/?probe=63a3f8ce29) | Mar 11, 2024 |
| Gigabyte      | B360M HD3                   | [aa06991c8c](https://linux-hardware.org/?probe=aa06991c8c) | Mar 11, 2024 |
| Gigabyte      | B360M HD3                   | [724f7885d0](https://linux-hardware.org/?probe=724f7885d0) | Mar 10, 2024 |
| Gigabyte      | B760 GAMING X AX            | [bdd341c11c](https://linux-hardware.org/?probe=bdd341c11c) | Mar 02, 2024 |
| Dell          | 0NW6H5 A00                  | [5b29c953c3](https://linux-hardware.org/?probe=5b29c953c3) | Feb 17, 2024 |
| ASUSTek       | TUF B450-PRO GAMING         | [348dffed6d](https://linux-hardware.org/?probe=348dffed6d) | Feb 09, 2024 |
| Dell          | OptiPlex 780                | [3c444c1e27](https://linux-hardware.org/?probe=3c444c1e27) | Jan 24, 2024 |
| ASUSTek       | Z170-P                      | [fc85634fb3](https://linux-hardware.org/?probe=fc85634fb3) | Jan 10, 2024 |
| Gigabyte      | B550 GAMING X V2            | [ce4bc6f455](https://linux-hardware.org/?probe=ce4bc6f455) | Dec 21, 2023 |
| ASRock        | G31M-S                      | [01866950a6](https://linux-hardware.org/?probe=01866950a6) | Nov 25, 2023 |
| ASUSTek       | M11BB                       | [21e7b53022](https://linux-hardware.org/?probe=21e7b53022) | Nov 02, 2023 |
| Intel         | X99                         | [8f60418655](https://linux-hardware.org/?probe=8f60418655) | Oct 30, 2023 |
| MSI           | 970A SLI Krait Edition      | [a54528c1ef](https://linux-hardware.org/?probe=a54528c1ef) | Oct 29, 2023 |
| ASUSTek       | STRIX Z270E GAMING          | [baacbfa91a](https://linux-hardware.org/?probe=baacbfa91a) | Oct 19, 2023 |
| Dell          | 0GX297                      | [0fa81b620e](https://linux-hardware.org/?probe=0fa81b620e) | Aug 14, 2023 |
| Gigabyte      | F2A55M-HD2                  | [bed2e58bf4](https://linux-hardware.org/?probe=bed2e58bf4) | Aug 14, 2023 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | [3e63b3dec0](https://linux-hardware.org/?probe=3e63b3dec0) | Aug 09, 2023 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | [a036ddad16](https://linux-hardware.org/?probe=a036ddad16) | Aug 09, 2023 |
| Supermicro    | X10SRG-F                    | [3bdaa7bfef](https://linux-hardware.org/?probe=3bdaa7bfef) | Aug 08, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [606780c010](https://linux-hardware.org/?probe=606780c010) | Jul 24, 2023 |
| Gigabyte      | H81M-S2H                    | [7a3f7dcd73](https://linux-hardware.org/?probe=7a3f7dcd73) | Jun 17, 2023 |
| Lenovo        | 3138 SDK0J40697 WIN 3305... | [36022cb1ac](https://linux-hardware.org/?probe=36022cb1ac) | May 11, 2023 |
| MSI           | B450M PRO-VDH PLUS          | [5e6b796278](https://linux-hardware.org/?probe=5e6b796278) | Apr 24, 2023 |
| HP            | 212A                        | [178f3b9c05](https://linux-hardware.org/?probe=178f3b9c05) | Apr 17, 2023 |
| Lenovo        | 3138 SDK0J40697 WIN 3305... | [491da3c2c2](https://linux-hardware.org/?probe=491da3c2c2) | Apr 10, 2023 |
| MSI           | PH67A-C43                   | [8e7c8a3d67](https://linux-hardware.org/?probe=8e7c8a3d67) | Apr 03, 2023 |
| ASUSTek       | PRIME B360-PLUS             | [ec45a753a5](https://linux-hardware.org/?probe=ec45a753a5) | Apr 02, 2023 |
| Gigabyte      | B650I AORUS ULTRA           | [a33a768662](https://linux-hardware.org/?probe=a33a768662) | Mar 29, 2023 |
| AMI           | Intel                       | [c2c28fa7e4](https://linux-hardware.org/?probe=c2c28fa7e4) | Mar 15, 2023 |
| Gigabyte      | P55A-UD3                    | [60cd9db1c5](https://linux-hardware.org/?probe=60cd9db1c5) | Feb 25, 2023 |
| MSI           | A320M PRO-E                 | [3e441c86f1](https://linux-hardware.org/?probe=3e441c86f1) | Feb 20, 2023 |
| MSI           | H67MS-E43                   | [47a6655b3b](https://linux-hardware.org/?probe=47a6655b3b) | Feb 07, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [beeeff23a5](https://linux-hardware.org/?probe=beeeff23a5) | Dec 25, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [de8b7d8220](https://linux-hardware.org/?probe=de8b7d8220) | Nov 19, 2022 |
| ASUSTek       | PRIME X399-A                | [304c12788b](https://linux-hardware.org/?probe=304c12788b) | Oct 06, 2022 |
| HP            | 1825                        | [bceae72004](https://linux-hardware.org/?probe=bceae72004) | Aug 15, 2022 |
| MSI           | X99S MPOWER                 | [a3c1523b6b](https://linux-hardware.org/?probe=a3c1523b6b) | Jul 27, 2022 |
| Dell          | 054KM3 A01                  | [407b210bfe](https://linux-hardware.org/?probe=407b210bfe) | Jul 05, 2022 |
| HP            | 18E7                        | [2fd690b3b4](https://linux-hardware.org/?probe=2fd690b3b4) | Jun 22, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [a698baa5f6](https://linux-hardware.org/?probe=a698baa5f6) | Jun 18, 2022 |
| Dell          | 0NC2VH A01                  | [f05a6e7d31](https://linux-hardware.org/?probe=f05a6e7d31) | May 03, 2022 |
| ASRock        | B450M-HDV R4.0              | [bce1bba9ff](https://linux-hardware.org/?probe=bce1bba9ff) | Apr 29, 2022 |
| Dell          | 0D24M8 A01                  | [fe4bb32aa1](https://linux-hardware.org/?probe=fe4bb32aa1) | Apr 14, 2022 |
| Dell          | 014GRG A00                  | [1783efe96b](https://linux-hardware.org/?probe=1783efe96b) | Apr 14, 2022 |
| HP            | 1825                        | [a7ce5b6b11](https://linux-hardware.org/?probe=a7ce5b6b11) | Mar 03, 2022 |
| MSI           | B450M PRO-M2 MAX            | [3f99c8072a](https://linux-hardware.org/?probe=3f99c8072a) | Feb 23, 2022 |
| ASUSTek       | PRIME H510M-A               | [7ab68e0043](https://linux-hardware.org/?probe=7ab68e0043) | Feb 17, 2022 |
| ASRock        | B450M-HDV R4.0              | [f2a65b8a5f](https://linux-hardware.org/?probe=f2a65b8a5f) | Feb 14, 2022 |
| Gigabyte      | P55A-UD3                    | [824dbdd8ad](https://linux-hardware.org/?probe=824dbdd8ad) | Jan 22, 2022 |
| Online Lab... | SR 42                       | [e3037eb087](https://linux-hardware.org/?probe=e3037eb087) | Jan 22, 2022 |
| Gigabyte      | H310M S2H x.x               | [9e14e04f7f](https://linux-hardware.org/?probe=9e14e04f7f) | Jan 22, 2022 |
| ASRock        | B450M-HDV R4.0              | [8e7267692b](https://linux-hardware.org/?probe=8e7267692b) | Jan 21, 2022 |
| Gigabyte      | MZGLKBP-00                  | [202ccac61c](https://linux-hardware.org/?probe=202ccac61c) | Dec 30, 2021 |
| Gigabyte      | B75M-D3V                    | [1c15b6b3c7](https://linux-hardware.org/?probe=1c15b6b3c7) | Dec 26, 2021 |
| HP            | 1495                        | [28835849f0](https://linux-hardware.org/?probe=28835849f0) | Oct 29, 2021 |
| ASUSTek       | PRIME Z490M-PLUS            | [5a7e6805d3](https://linux-hardware.org/?probe=5a7e6805d3) | Oct 02, 2021 |
| MSI           | B360M PRO-VD                | [06e625d98f](https://linux-hardware.org/?probe=06e625d98f) | Oct 02, 2021 |
| HP            | 1825                        | [ff75be1ea3](https://linux-hardware.org/?probe=ff75be1ea3) | Jun 06, 2021 |
| ASUSTek       | P5G41T-M LX2/BR             | [8702580cb4](https://linux-hardware.org/?probe=8702580cb4) | May 26, 2021 |
| ASUSTek       | P5G41T-M LX2/BR             | [05f1d12390](https://linux-hardware.org/?probe=05f1d12390) | May 26, 2021 |
| Gigabyte      | H170-HD3-CF                 | [2ffdc89c2a](https://linux-hardware.org/?probe=2ffdc89c2a) | Apr 28, 2021 |
| Gigabyte      | Z390 GAMING SLI-CF          | [50f8ddb45c](https://linux-hardware.org/?probe=50f8ddb45c) | Apr 28, 2021 |
| Google        | Tricky                      | [666794d603](https://linux-hardware.org/?probe=666794d603) | Apr 26, 2021 |
| ASUSTek       | F1A55-M LX                  | [630bbb748a](https://linux-hardware.org/?probe=630bbb748a) | Apr 17, 2021 |
| Gigabyte      | H170-HD3-CF                 | [f103eefd66](https://linux-hardware.org/?probe=f103eefd66) | Apr 17, 2021 |
| Gigabyte      | Z390 GAMING SLI-CF          | [e802fc9ff5](https://linux-hardware.org/?probe=e802fc9ff5) | Apr 17, 2021 |
| Sun Micros... | Ultra 24 50                 | [e4b76f9137](https://linux-hardware.org/?probe=e4b76f9137) | Apr 10, 2021 |
| Sun Micros... | Ultra 24 50                 | [15691fbc42](https://linux-hardware.org/?probe=15691fbc42) | Apr 10, 2021 |
| ASUSTek       | A8R-MVP                     | [6daa2a372c](https://linux-hardware.org/?probe=6daa2a372c) | Mar 27, 2021 |
| ASRock        | K8A780LM                    | [b8f4c7c2cb](https://linux-hardware.org/?probe=b8f4c7c2cb) | Mar 22, 2021 |
| Gigabyte      | 970A-DS3P                   | [eeebc66137](https://linux-hardware.org/?probe=eeebc66137) | Mar 17, 2021 |
| Gigabyte      | 970A-DS3P                   | [fdf4e6d366](https://linux-hardware.org/?probe=fdf4e6d366) | Mar 17, 2021 |
| ASRock        | K8A780LM                    | [d95a56d80f](https://linux-hardware.org/?probe=d95a56d80f) | Mar 15, 2021 |
| ASRock        | H81M-ITX                    | [0f5f41e1ca](https://linux-hardware.org/?probe=0f5f41e1ca) | Mar 08, 2021 |
| ASRock        | H81M-ITX                    | [8599b883d6](https://linux-hardware.org/?probe=8599b883d6) | Mar 08, 2021 |
| Intel         | D815EEA AAA45884-401        | [248565d49c](https://linux-hardware.org/?probe=248565d49c) | Feb 20, 2021 |
| Intel         | D815EEA AAA45884-401        | [3acc2f0b1e](https://linux-hardware.org/?probe=3acc2f0b1e) | Feb 20, 2021 |
| Gigabyte      | GA-G41M-ES2L                | [592c995804](https://linux-hardware.org/?probe=592c995804) | Jan 30, 2021 |
| Acer          | F672CR R01-A4               | [8d41694165](https://linux-hardware.org/?probe=8d41694165) | Jan 25, 2021 |
| Lenovo        | ThinkStation E20 4220CTO    | [f963a2e7f9](https://linux-hardware.org/?probe=f963a2e7f9) | Jan 06, 2021 |
| Dell          | 0GXM1W A04                  | [989f983b51](https://linux-hardware.org/?probe=989f983b51) | Dec 28, 2020 |
| Lenovo        | ThinkStation E20 4220CTO    | [aac28ba905](https://linux-hardware.org/?probe=aac28ba905) | Dec 19, 2020 |
| Intel         | HURONRIVER                  | [49bdd1a99d](https://linux-hardware.org/?probe=49bdd1a99d) | Oct 29, 2020 |
| ASUSTek       | Maximus V GENE              | [253b5aba98](https://linux-hardware.org/?probe=253b5aba98) | Oct 29, 2020 |
| ASUSTek       | H81M-C                      | [cd136e059e](https://linux-hardware.org/?probe=cd136e059e) | Oct 05, 2020 |
| HP            | 1791                        | [f41fcdc019](https://linux-hardware.org/?probe=f41fcdc019) | Sep 26, 2020 |
| ASUSTek       | EX-A320M-GAMING             | [4eb75f039b](https://linux-hardware.org/?probe=4eb75f039b) | Aug 17, 2020 |
| HP            | 1791                        | [5a21e91155](https://linux-hardware.org/?probe=5a21e91155) | Aug 15, 2020 |
| Gigabyte      | B450 AORUS ELITE            | [ff5143e508](https://linux-hardware.org/?probe=ff5143e508) | Aug 02, 2020 |
| ASUSTek       | P5PE-VM                     | [298c1239dd](https://linux-hardware.org/?probe=298c1239dd) | May 20, 2020 |
| MSI           | B350 PC MATE                | [ff3852f02d](https://linux-hardware.org/?probe=ff3852f02d) | Mar 23, 2020 |
| ASRock        | G31M-VS2                    | [b64547f948](https://linux-hardware.org/?probe=b64547f948) | Dec 06, 2019 |
| Gigabyte      | H170-HD3-CF                 | [338994bd66](https://linux-hardware.org/?probe=338994bd66) | Dec 02, 2019 |
| ASUSTek       | P5PE-VM                     | [6a89046dfb](https://linux-hardware.org/?probe=6a89046dfb) | Dec 02, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| Devuan 4                | 27       | 33.75%  |
| Devuan 5                | 18       | 22.5%   |
| Devuan 3                | 14       | 17.5%   |
| Devuan Testing/unstable | 7        | 8.75%   |
| Devuan 2.1              | 6        | 7.5%    |
| Devuan 6                | 4        | 5%      |
| Devuan                  | 3        | 3.75%   |
| Devuan 1.0.0            | 1        | 1.25%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Devuan | 77       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Desktops | Percent |
|-----------------------|----------|---------|
| 5.10.0-9-amd64        | 6        | 7.14%   |
| 6.1.0-18-amd64        | 4        | 4.76%   |
| 5.10.0-21-amd64       | 4        | 4.76%   |
| 4.19.0-14-amd64       | 4        | 4.76%   |
| 6.1.0-13-amd64        | 3        | 3.57%   |
| 5.10.0-19-amd64       | 3        | 3.57%   |
| 4.19.0-16-amd64       | 3        | 3.57%   |
| 6.1.0-17-amd64        | 2        | 2.38%   |
| 5.10.0-8-amd64        | 2        | 2.38%   |
| 5.10.0-6-amd64        | 2        | 2.38%   |
| 5.10.0-23-amd64       | 2        | 2.38%   |
| 4.19.0-9-amd64        | 2        | 2.38%   |
| 4.19.0-13-amd64       | 2        | 2.38%   |
| 4.19.0-10-amd64       | 2        | 2.38%   |
| 6.6.15-amd64          | 1        | 1.19%   |
| 6.5.0-0.deb12.1-amd64 | 1        | 1.19%   |
| 6.3.0-2-amd64         | 1        | 1.19%   |
| 6.3.0-1-amd64         | 1        | 1.19%   |
| 6.2.12                | 1        | 1.19%   |
| 6.1.71-gnu            | 1        | 1.19%   |
| 6.1.7                 | 1        | 1.19%   |
| 6.1.0-6-amd64         | 1        | 1.19%   |
| 6.1.0-16-amd64        | 1        | 1.19%   |
| 6.1.0-10-amd64        | 1        | 1.19%   |
| 6.1.0-0.deb11.5-amd64 | 1        | 1.19%   |
| 6.0.0-5-amd64         | 1        | 1.19%   |
| 5.9.0-1-amd64         | 1        | 1.19%   |
| 5.8.0-3-amd64         | 1        | 1.19%   |
| 5.7.0-1-amd64         | 1        | 1.19%   |
| 5.7.0-0.bpo.2-amd64   | 1        | 1.19%   |
| 5.18.14-devuan        | 1        | 1.19%   |
| 5.18.11-gnu           | 1        | 1.19%   |
| 5.18.0-1-amd64        | 1        | 1.19%   |
| 5.16.0-1-amd64        | 1        | 1.19%   |
| 5.15.0-2-amd64        | 1        | 1.19%   |
| 5.15.0-0.bpo.2-amd64  | 1        | 1.19%   |
| 5.14.0-kali2-amd64    | 1        | 1.19%   |
| 5.10.0-5-amd64        | 1        | 1.19%   |
| 5.10.0-28-amd64       | 1        | 1.19%   |
| 5.10.0-24-amd64       | 1        | 1.19%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.10.0   | 26       | 32.91%  |
| 4.19.0   | 15       | 18.99%  |
| 6.1.0    | 13       | 16.46%  |
| 4.9.0    | 4        | 5.06%   |
| 6.3.0    | 2        | 2.53%   |
| 5.7.0    | 2        | 2.53%   |
| 5.15.0   | 2        | 2.53%   |
| 6.6.15   | 1        | 1.27%   |
| 6.5.0    | 1        | 1.27%   |
| 6.2.12   | 1        | 1.27%   |
| 6.1.71   | 1        | 1.27%   |
| 6.1.7    | 1        | 1.27%   |
| 6.0.0    | 1        | 1.27%   |
| 5.9.0    | 1        | 1.27%   |
| 5.8.0    | 1        | 1.27%   |
| 5.18.14  | 1        | 1.27%   |
| 5.18.11  | 1        | 1.27%   |
| 5.18.0   | 1        | 1.27%   |
| 5.16.0   | 1        | 1.27%   |
| 5.14.0   | 1        | 1.27%   |
| 4.19.112 | 1        | 1.27%   |
| 4.18.0   | 1        | 1.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 26       | 32.91%  |
| 4.19    | 16       | 20.25%  |
| 6.1     | 15       | 18.99%  |
| 4.9     | 4        | 5.06%   |
| 5.18    | 3        | 3.8%    |
| 6.3     | 2        | 2.53%   |
| 5.7     | 2        | 2.53%   |
| 5.15    | 2        | 2.53%   |
| 6.6     | 1        | 1.27%   |
| 6.5     | 1        | 1.27%   |
| 6.2     | 1        | 1.27%   |
| 6.0     | 1        | 1.27%   |
| 5.9     | 1        | 1.27%   |
| 5.8     | 1        | 1.27%   |
| 5.16    | 1        | 1.27%   |
| 5.14    | 1        | 1.27%   |
| 4.18    | 1        | 1.27%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 74       | 96.1%   |
| i686   | 3        | 3.9%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| XFCE       | 36       | 45%     |
| Unknown    | 14       | 17.5%   |
| MATE       | 8        | 10%     |
| KDE5       | 8        | 10%     |
| LXDE       | 5        | 6.25%   |
| Cinnamon   | 3        | 3.75%   |
| awesome    | 2        | 2.5%    |
| X-Cinnamon | 1        | 1.25%   |
| LXQt       | 1        | 1.25%   |
| i3         | 1        | 1.25%   |
| GNOME      | 1        | 1.25%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 66       | 84.62%  |
| Tty     | 9        | 11.54%  |
| Unknown | 3        | 3.85%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SLiM    | 31       | 40.26%  |
| Unknown | 21       | 27.27%  |
| LightDM | 15       | 19.48%  |
| SDDM    | 6        | 7.79%   |
| NODM    | 2        | 2.6%    |
| XDM     | 1        | 1.3%    |
| LXDM    | 1        | 1.3%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 24       | 30.77%  |
| fr_FR   | 11       | 14.1%   |
| en_GB   | 7        | 8.97%   |
| ru_RU   | 6        | 7.69%   |
| Unknown | 5        | 6.41%   |
| C       | 4        | 5.13%   |
| sk_SK   | 3        | 3.85%   |
| pt_BR   | 3        | 3.85%   |
| en_AU   | 3        | 3.85%   |
| it_IT   | 2        | 2.56%   |
| fr_BE   | 2        | 2.56%   |
| en_NZ   | 2        | 2.56%   |
| de_DE   | 2        | 2.56%   |
| pl_PL   | 1        | 1.28%   |
| es_MX   | 1        | 1.28%   |
| es_ES   | 1        | 1.28%   |
| en_CA   | 1        | 1.28%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 46       | 59.74%  |
| EFI  | 31       | 40.26%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 67       | 87.01%  |
| Btrfs   | 3        | 3.9%    |
| Xfs     | 2        | 2.6%    |
| Overlay | 2        | 2.6%    |
| Ext3    | 1        | 1.3%    |
| Ext2    | 1        | 1.3%    |
| Unknown | 1        | 1.3%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 44       | 55%     |
| MBR     | 26       | 32.5%   |
| Unknown | 10       | 12.5%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 54       | 68.35%  |
| Yes       | 25       | 31.65%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 58       | 75.32%  |
| Yes       | 19       | 24.68%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 18       | 23.38%  |
| ASUSTek Computer    | 17       | 22.08%  |
| MSI                 | 10       | 12.99%  |
| Dell                | 8        | 10.39%  |
| Hewlett-Packard     | 5        | 6.49%   |
| ASRock              | 5        | 6.49%   |
| Intel               | 3        | 3.9%    |
| Lenovo              | 2        | 2.6%    |
| Supermicro          | 1        | 1.3%    |
| Sun Microsystems    | 1        | 1.3%    |
| Online Labs         | 1        | 1.3%    |
| LORD ELECTRONICS    | 1        | 1.3%    |
| Google              | 1        | 1.3%    |
| Fujitsu             | 1        | 1.3%    |
| Foxconn             | 1        | 1.3%    |
| AMI                 | 1        | 1.3%    |
| Acer                | 1        | 1.3%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Dell OptiPlex 7050                                | 2        | 2.6%    |
| ASUS TUF B450-PRO GAMING                          | 2        | 2.6%    |
| Supermicro SYS-1018GR-T                           | 1        | 1.3%    |
| Sun Microsystems Ultra 24                         | 1        | 1.3%    |
| Online Labs SR                                    | 1        | 1.3%    |
| MSI MS-7B86                                       | 1        | 1.3%    |
| MSI MS-7B84                                       | 1        | 1.3%    |
| MSI MS-7B53                                       | 1        | 1.3%    |
| MSI MS-7A38                                       | 1        | 1.3%    |
| MSI MS-7A36                                       | 1        | 1.3%    |
| MSI MS-7A34                                       | 1        | 1.3%    |
| MSI MS-7885                                       | 1        | 1.3%    |
| MSI MS-7693                                       | 1        | 1.3%    |
| MSI MS-7678                                       | 1        | 1.3%    |
| MSI MS-7673                                       | 1        | 1.3%    |
| LORD ELECTRONICS LORD G4x 775 ICH7 8712 As Design | 1        | 1.3%    |
| Lenovo ThinkStation P330 30C5S1LQ00               | 1        | 1.3%    |
| Lenovo ThinkStation E20 4220CTO                   | 1        | 1.3%    |
| Intel X99                                         | 1        | 1.3%    |
| Intel D815EEA AAA45884-401                        | 1        | 1.3%    |
| Intel AHV                                         | 1        | 1.3%    |
| HP Z640 Workstation                               | 1        | 1.3%    |
| HP Z220 SFF Workstation                           | 1        | 1.3%    |
| HP ProDesk 600 G1 SFF                             | 1        | 1.3%    |
| HP EliteDesk 800 G1 DM                            | 1        | 1.3%    |
| HP Compaq 8200 Elite SFF PC                       | 1        | 1.3%    |
| Google Tricky                                     | 1        | 1.3%    |
| Gigabyte Z390 GAMING SLI                          | 1        | 1.3%    |
| Gigabyte Z370 AORUS Gaming 7                      | 1        | 1.3%    |
| Gigabyte P55A-UD3                                 | 1        | 1.3%    |
| Gigabyte MZGLKBP-00                               | 1        | 1.3%    |
| Gigabyte H81M-S2H                                 | 1        | 1.3%    |
| Gigabyte H310M S2H 2.0                            | 1        | 1.3%    |
| Gigabyte H170-HD3-CF                              | 1        | 1.3%    |
| Gigabyte H170-HD3                                 | 1        | 1.3%    |
| Gigabyte GA-G41M-ES2L                             | 1        | 1.3%    |
| Gigabyte F2A55M-HD2                               | 1        | 1.3%    |
| Gigabyte B760 GAMING X AX                         | 1        | 1.3%    |
| Gigabyte B75M-D3V                                 | 1        | 1.3%    |
| Gigabyte B650I AORUS ULTRA                        | 1        | 1.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| Dell OptiPlex           | 7        | 9.09%   |
| ASUS PRIME              | 4        | 5.19%   |
| Lenovo ThinkStation     | 2        | 2.6%    |
| ASUS TUF                | 2        | 2.6%    |
| ASUS ROG                | 2        | 2.6%    |
| Supermicro SYS-1018GR-T | 1        | 1.3%    |
| Sun Microsystems Ultra  | 1        | 1.3%    |
| Online Labs SR          | 1        | 1.3%    |
| MSI MS-7B86             | 1        | 1.3%    |
| MSI MS-7B84             | 1        | 1.3%    |
| MSI MS-7B53             | 1        | 1.3%    |
| MSI MS-7A38             | 1        | 1.3%    |
| MSI MS-7A36             | 1        | 1.3%    |
| MSI MS-7A34             | 1        | 1.3%    |
| MSI MS-7885             | 1        | 1.3%    |
| MSI MS-7693             | 1        | 1.3%    |
| MSI MS-7678             | 1        | 1.3%    |
| MSI MS-7673             | 1        | 1.3%    |
| LORD ELECTRONICS LORD   | 1        | 1.3%    |
| Intel X99               | 1        | 1.3%    |
| Intel D815EEA           | 1        | 1.3%    |
| Intel AHV               | 1        | 1.3%    |
| HP Z640                 | 1        | 1.3%    |
| HP Z220                 | 1        | 1.3%    |
| HP ProDesk              | 1        | 1.3%    |
| HP EliteDesk            | 1        | 1.3%    |
| HP Compaq               | 1        | 1.3%    |
| Google Tricky           | 1        | 1.3%    |
| Gigabyte Z390           | 1        | 1.3%    |
| Gigabyte Z370           | 1        | 1.3%    |
| Gigabyte P55A-UD3       | 1        | 1.3%    |
| Gigabyte MZGLKBP-00     | 1        | 1.3%    |
| Gigabyte H81M-S2H       | 1        | 1.3%    |
| Gigabyte H310M          | 1        | 1.3%    |
| Gigabyte H170-HD3-CF    | 1        | 1.3%    |
| Gigabyte H170-HD3       | 1        | 1.3%    |
| Gigabyte GA-G41M-ES2L   | 1        | 1.3%    |
| Gigabyte F2A55M-HD2     | 1        | 1.3%    |
| Gigabyte B760           | 1        | 1.3%    |
| Gigabyte B75M-D3V       | 1        | 1.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 13       | 16.88%  |
| 2013 | 8        | 10.39%  |
| 2019 | 7        | 9.09%   |
| 2017 | 7        | 9.09%   |
| 2012 | 5        | 6.49%   |
| 2011 | 5        | 6.49%   |
| 2020 | 4        | 5.19%   |
| 2015 | 4        | 5.19%   |
| 2014 | 4        | 5.19%   |
| 2010 | 4        | 5.19%   |
| 2016 | 3        | 3.9%    |
| 2023 | 2        | 2.6%    |
| 2022 | 2        | 2.6%    |
| 2009 | 2        | 2.6%    |
| 2008 | 2        | 2.6%    |
| 2007 | 2        | 2.6%    |
| 2021 | 1        | 1.3%    |
| 2006 | 1        | 1.3%    |
| 2000 | 1        | 1.3%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 77       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 76       | 98.7%   |
| Enabled  | 1        | 1.3%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 75       | 97.4%   |
| Yes  | 2        | 2.6%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 23       | 29.87%  |
| 32.01-64.0  | 15       | 19.48%  |
| 8.01-16.0   | 12       | 15.58%  |
| 4.01-8.0    | 10       | 12.99%  |
| 64.01-256.0 | 7        | 9.09%   |
| 3.01-4.0    | 5        | 6.49%   |
| 1.01-2.0    | 4        | 5.19%   |
| 0.01-0.5    | 1        | 1.3%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 25       | 30.86%  |
| 4.01-8.0   | 13       | 16.05%  |
| 2.01-3.0   | 12       | 14.81%  |
| 0.51-1.0   | 11       | 13.58%  |
| 3.01-4.0   | 9        | 11.11%  |
| 8.01-16.0  | 6        | 7.41%   |
| 0.01-0.5   | 3        | 3.7%    |
| 16.01-24.0 | 2        | 2.47%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 29       | 37.66%  |
| 3      | 15       | 19.48%  |
| 2      | 15       | 19.48%  |
| 4      | 7        | 9.09%   |
| 5      | 5        | 6.49%   |
| 6      | 4        | 5.19%   |
| 7      | 2        | 2.6%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 52       | 67.53%  |
| Yes       | 25       | 32.47%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 76       | 98.7%   |
| No        | 1        | 1.3%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 60       | 76.92%  |
| Yes       | 18       | 23.08%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 65       | 84.42%  |
| Yes       | 12       | 15.58%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| France      | 14       | 18.18%  |
| USA         | 10       | 12.99%  |
| Russia      | 8        | 10.39%  |
| UK          | 4        | 5.19%   |
| Ukraine     | 3        | 3.9%    |
| Slovakia    | 3        | 3.9%    |
| Poland      | 3        | 3.9%    |
| Germany     | 3        | 3.9%    |
| Brazil      | 3        | 3.9%    |
| Australia   | 3        | 3.9%    |
| Spain       | 2        | 2.6%    |
| New Zealand | 2        | 2.6%    |
| Netherlands | 2        | 2.6%    |
| Canada      | 2        | 2.6%    |
| Belgium     | 2        | 2.6%    |
| Argentina   | 2        | 2.6%    |
| Tunisia     | 1        | 1.3%    |
| South Korea | 1        | 1.3%    |
| Puerto Rico | 1        | 1.3%    |
| Mexico      | 1        | 1.3%    |
| Italy       | 1        | 1.3%    |
| Israel      | 1        | 1.3%    |
| Iceland     | 1        | 1.3%    |
| Georgia     | 1        | 1.3%    |
| Denmark     | 1        | 1.3%    |
| China       | 1        | 1.3%    |
| Bulgaria    | 1        | 1.3%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Paris            | 3        | 3.9%    |
| Bratislava       | 3        | 3.9%    |
| Bagnolet         | 3        | 3.9%    |
| Volzhskiy        | 2        | 2.6%    |
| Toronto          | 2        | 2.6%    |
| Sydney           | 2        | 2.6%    |
| Moscow           | 2        | 2.6%    |
| Auckland         | 2        | 2.6%    |
| Xiamen           | 1        | 1.3%    |
| Wroclaw          | 1        | 1.3%    |
| Waterford        | 1        | 1.3%    |
| Vladikavkaz      | 1        | 1.3%    |
| Vise             | 1        | 1.3%    |
| Valencia         | 1        | 1.3%    |
| Tel Aviv         | 1        | 1.3%    |
| Tbilisi          | 1        | 1.3%    |
| Sofia            | 1        | 1.3%    |
| Shelekhov        | 1        | 1.3%    |
| Seongbuk-gu      | 1        | 1.3%    |
| Sao Paulo        | 1        | 1.3%    |
| Saint-Herblain   | 1        | 1.3%    |
| Rugby            | 1        | 1.3%    |
| Roubaix          | 1        | 1.3%    |
| Rio de Janeiro   | 1        | 1.3%    |
| Reykjavik        | 1        | 1.3%    |
| Renkum           | 1        | 1.3%    |
| Randers          | 1        | 1.3%    |
| Radzionkow       | 1        | 1.3%    |
| Port Richey      | 1        | 1.3%    |
| Poperinge        | 1        | 1.3%    |
| Oleksandriya     | 1        | 1.3%    |
| Okehampton       | 1        | 1.3%    |
| Novopokrovskoye  | 1        | 1.3%    |
| Norman           | 1        | 1.3%    |
| Nérac           | 1        | 1.3%    |
| Monferran-Plaves | 1        | 1.3%    |
| Molsheim         | 1        | 1.3%    |
| Miedziana Gora   | 1        | 1.3%    |
| Miami            | 1        | 1.3%    |
| Mexico City      | 1        | 1.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 33       | 57     | 22.6%   |
| Seagate                     | 25       | 38     | 17.12%  |
| Kingston                    | 13       | 17     | 8.9%    |
| Samsung Electronics         | 12       | 23     | 8.22%   |
| Toshiba                     | 8        | 8      | 5.48%   |
| SanDisk                     | 7        | 7      | 4.79%   |
| Crucial                     | 7        | 9      | 4.79%   |
| Intel                       | 3        | 5      | 2.05%   |
| Patriot                     | 2        | 2      | 1.37%   |
| Netac                       | 2        | 2      | 1.37%   |
| Micron Technology           | 2        | 2      | 1.37%   |
| Maxtor                      | 2        | 2      | 1.37%   |
| Hitachi                     | 2        | 2      | 1.37%   |
| HGST                        | 2        | 2      | 1.37%   |
| Dogfish                     | 2        | 2      | 1.37%   |
| A-DATA Technology           | 2        | 2      | 1.37%   |
| WD MediaMax                 | 1        | 3      | 0.68%   |
| Verbatim                    | 1        | 1      | 0.68%   |
| Unknown                     | 1        | 1      | 0.68%   |
| Transcend                   | 1        | 2      | 0.68%   |
| Team                        | 1        | 1      | 0.68%   |
| Supermicro                  | 1        | 1      | 0.68%   |
| SK hynix                    | 1        | 1      | 0.68%   |
| PNY                         | 1        | 1      | 0.68%   |
| Plextor                     | 1        | 1      | 0.68%   |
| MAXIO Technology (Hangzhou) | 1        | 1      | 0.68%   |
| Lexar                       | 1        | 1      | 0.68%   |
| KingDian                    | 1        | 1      | 0.68%   |
| Intenso                     | 1        | 1      | 0.68%   |
| IBM/Hitachi                 | 1        | 1      | 0.68%   |
| HPE                         | 1        | 2      | 0.68%   |
| Hewlett-Packard             | 1        | 2      | 0.68%   |
| GOODRAM                     | 1        | 1      | 0.68%   |
| Fujitsu                     | 1        | 1      | 0.68%   |
| Corsair                     | 1        | 1      | 0.68%   |
| China                       | 1        | 1      | 0.68%   |
| Apacer                      | 1        | 1      | 0.68%   |
| ADATA Technology            | 1        | 1      | 0.68%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Kingston SA400S37480G 480GB SSD  | 3        | 1.72%   |
| Kingston SA400S37120G 120GB SSD  | 3        | 1.72%   |
| Kingston SA2000M8250G 250GB      | 3        | 1.72%   |
| WDC WD10EZEX-08WN4A0 1TB         | 2        | 1.15%   |
| WDC WD10EZEX-00BBHA0 1TB         | 2        | 1.15%   |
| WDC WD10EARX-00N0YB0 1TB         | 2        | 1.15%   |
| Seagate ST3500418AS 500GB        | 2        | 1.15%   |
| Seagate ST2000DX002-2DV164 2TB   | 2        | 1.15%   |
| Seagate ST2000DM008-2FR102 2TB   | 2        | 1.15%   |
| SanDisk SDSSDX240GG25 240GB      | 2        | 1.15%   |
| Samsung SSD 860 EVO 250GB        | 2        | 1.15%   |
| Patriot Burst 120GB SSD          | 2        | 1.15%   |
| Hitachi HDS721616PLA380 160GB    | 2        | 1.15%   |
| WDC WDS500G3X0C-00SJG0 500GB     | 1        | 0.57%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 1        | 0.57%   |
| WDC WDS480G2G0A-00JH30 480GB SSD | 1        | 0.57%   |
| WDC WDS120G2G0A-00JH30 120GB SSD | 1        | 0.57%   |
| WDC WD800BB-00JHC0 80GB          | 1        | 0.57%   |
| WDC WD7500AALX-009BA0 752GB      | 1        | 0.57%   |
| WDC WD5001AALS-00L3B2 500GB      | 1        | 0.57%   |
| WDC WD5001AALS-00E3A0 500GB      | 1        | 0.57%   |
| WDC WD5000LPVX-00V0TT0 500GB     | 1        | 0.57%   |
| WDC WD5000BPVT-24HXZT3 500GB     | 1        | 0.57%   |
| WDC WD5000AZLX-75K2TA0 500GB     | 1        | 0.57%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 1        | 0.57%   |
| WDC WD40PURZ-85TTDY0 4TB         | 1        | 0.57%   |
| WDC WD40EFRX-68WT0N0 4TB         | 1        | 0.57%   |
| WDC WD40EDAZ-11SLVB0 4TB         | 1        | 0.57%   |
| WDC WD22PURZ-85B4ZY0 2TB         | 1        | 0.57%   |
| WDC WD20PURZ-85GU6Y0 2TB         | 1        | 0.57%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 1        | 0.57%   |
| WDC WD20EZRX-00DC0B0 2TB         | 1        | 0.57%   |
| WDC WD20EZRX-00D8PB0 2TB         | 1        | 0.57%   |
| WDC WD20EZAZ-00L9GB0 2TB         | 1        | 0.57%   |
| WDC WD20EFRX-68EUZN0 2TB         | 1        | 0.57%   |
| WDC WD2003FZEX-00Z4SA0 2TB       | 1        | 0.57%   |
| WDC WD2003FZEX-00SRLA0 2TB       | 1        | 0.57%   |
| WDC WD1600AAJS-00YZCA0 160GB     | 1        | 0.57%   |
| WDC WD1502FAEX-007BA0 1TB        | 1        | 0.57%   |
| WDC WD1200JS-55NCB1 120GB        | 1        | 0.57%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 30       | 53     | 41.1%   |
| Seagate             | 24       | 37     | 32.88%  |
| Toshiba             | 6        | 6      | 8.22%   |
| Samsung Electronics | 3        | 4      | 4.11%   |
| Maxtor              | 2        | 2      | 2.74%   |
| Hitachi             | 2        | 2      | 2.74%   |
| HGST                | 2        | 2      | 2.74%   |
| IBM/Hitachi         | 1        | 1      | 1.37%   |
| HPE                 | 1        | 2      | 1.37%   |
| Hewlett-Packard     | 1        | 2      | 1.37%   |
| Fujitsu             | 1        | 1      | 1.37%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 10       | 13     | 18.52%  |
| Kingston            | 9        | 11     | 16.67%  |
| WDC                 | 3        | 3      | 5.56%   |
| SanDisk             | 3        | 3      | 5.56%   |
| Crucial             | 3        | 4      | 5.56%   |
| Patriot             | 2        | 2      | 3.7%    |
| Netac               | 2        | 2      | 3.7%    |
| Micron Technology   | 2        | 2      | 3.7%    |
| Intel               | 2        | 4      | 3.7%    |
| Dogfish             | 2        | 2      | 3.7%    |
| A-DATA Technology   | 2        | 2      | 3.7%    |
| Verbatim            | 1        | 1      | 1.85%   |
| Transcend           | 1        | 2      | 1.85%   |
| Team                | 1        | 1      | 1.85%   |
| Supermicro          | 1        | 1      | 1.85%   |
| SK hynix            | 1        | 1      | 1.85%   |
| PNY                 | 1        | 1      | 1.85%   |
| Plextor             | 1        | 1      | 1.85%   |
| Lexar               | 1        | 1      | 1.85%   |
| KingDian            | 1        | 1      | 1.85%   |
| Intenso             | 1        | 1      | 1.85%   |
| GOODRAM             | 1        | 1      | 1.85%   |
| Corsair             | 1        | 1      | 1.85%   |
| China               | 1        | 1      | 1.85%   |
| Apacer              | 1        | 1      | 1.85%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 54       | 112    | 42.86%  |
| SSD     | 47       | 63     | 37.3%   |
| NVMe    | 22       | 27     | 17.46%  |
| Unknown | 2        | 4      | 1.59%   |
| MMC     | 1        | 1      | 0.79%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 71       | 172    | 72.45%  |
| NVMe | 22       | 27     | 22.45%  |
| SAS  | 4        | 7      | 4.08%   |
| MMC  | 1        | 1      | 1.02%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 53       | 90     | 50%     |
| 0.51-1.0   | 28       | 50     | 26.42%  |
| 1.01-2.0   | 16       | 24     | 15.09%  |
| 3.01-4.0   | 7        | 9      | 6.6%    |
| 4.01-10.0  | 2        | 2      | 1.89%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 18       | 22.5%   |
| 251-500        | 15       | 18.75%  |
| 1001-2000      | 13       | 16.25%  |
| 101-250        | 11       | 13.75%  |
| More than 3000 | 9        | 11.25%  |
| 51-100         | 4        | 5%      |
| 21-50          | 3        | 3.75%   |
| 2001-3000      | 3        | 3.75%   |
| 1-20           | 2        | 2.5%    |
| Unknown        | 2        | 2.5%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 19       | 24.05%  |
| 1-20           | 17       | 21.52%  |
| 21-50          | 8        | 10.13%  |
| 251-500        | 7        | 8.86%   |
| 1001-2000      | 7        | 8.86%   |
| 51-100         | 7        | 8.86%   |
| 501-1000       | 6        | 7.59%   |
| More than 3000 | 3        | 3.8%    |
| 2001-3000      | 3        | 3.8%    |
| Unknown        | 2        | 2.53%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Hitachi HDS721616PLA380 160GB         | 2        | 2      | 8.7%    |
| WDC WD5000LPVX-00V0TT0 500GB          | 1        | 1      | 4.35%   |
| WDC WD5000BPVT-24HXZT3 500GB          | 1        | 1      | 4.35%   |
| WDC WD5000AAKX-60U6AA0 500GB          | 1        | 1      | 4.35%   |
| WDC WD1502FAEX-007BA0 1TB             | 1        | 1      | 4.35%   |
| WDC WD10EARX-00N0YB0 1TB              | 1        | 1      | 4.35%   |
| Toshiba MQ04ABF100 1TB                | 1        | 1      | 4.35%   |
| Toshiba MQ02ABF100 1TB                | 1        | 1      | 4.35%   |
| SK hynix SH920 mSATA 128GB SSD        | 1        | 1      | 4.35%   |
| Seagate ST3500418AS 500GB             | 1        | 1      | 4.35%   |
| Samsung Electronics SSD 970 EVO 500GB | 1        | 1      | 4.35%   |
| Samsung Electronics SP2504C 250GB     | 1        | 1      | 4.35%   |
| Samsung Electronics HD160JJ 160GB     | 1        | 1      | 4.35%   |
| Maxtor 6E040L0 41GB                   | 1        | 1      | 4.35%   |
| Kingston SA400S37120G 120GB SSD       | 1        | 1      | 4.35%   |
| Intel SSDSC2BF120A5 120GB             | 1        | 3      | 4.35%   |
| HPE MB4000GEFNA 4TB                   | 1        | 2      | 4.35%   |
| HGST HTS545050A7E680 500GB            | 1        | 1      | 4.35%   |
| HGST HTE721010A9E630 1TB              | 1        | 1      | 4.35%   |
| Hewlett-Packard VB0250EAVER 250GB     | 1        | 2      | 4.35%   |
| Fujitsu MHV2060BH PL 64GB             | 1        | 1      | 4.35%   |
| China SATA SSD 64GB                   | 1        | 1      | 4.35%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 5        | 5      | 22.73%  |
| Toshiba             | 2        | 2      | 9.09%   |
| Samsung Electronics | 2        | 3      | 9.09%   |
| Hitachi             | 2        | 2      | 9.09%   |
| HGST                | 2        | 2      | 9.09%   |
| SK hynix            | 1        | 1      | 4.55%   |
| Seagate             | 1        | 1      | 4.55%   |
| Maxtor              | 1        | 1      | 4.55%   |
| Kingston            | 1        | 1      | 4.55%   |
| Intel               | 1        | 3      | 4.55%   |
| HPE                 | 1        | 2      | 4.55%   |
| Hewlett-Packard     | 1        | 2      | 4.55%   |
| Fujitsu             | 1        | 1      | 4.55%   |
| China               | 1        | 1      | 4.55%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 5        | 5      | 29.41%  |
| Toshiba             | 2        | 2      | 11.76%  |
| Hitachi             | 2        | 2      | 11.76%  |
| HGST                | 2        | 2      | 11.76%  |
| Seagate             | 1        | 1      | 5.88%   |
| Samsung Electronics | 1        | 2      | 5.88%   |
| Maxtor              | 1        | 1      | 5.88%   |
| HPE                 | 1        | 2      | 5.88%   |
| Hewlett-Packard     | 1        | 2      | 5.88%   |
| Fujitsu             | 1        | 1      | 5.88%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 17       | 20     | 77.27%  |
| SSD  | 4        | 6      | 18.18%  |
| NVMe | 1        | 1      | 4.55%   |

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
| Works    | 55       | 136    | 56.12%  |
| Detected | 22       | 44     | 22.45%  |
| Malfunc  | 21       | 27     | 21.43%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 54       | 49.54%  |
| AMD                              | 22       | 20.18%  |
| Sandisk                          | 5        | 4.59%   |
| Samsung Electronics              | 5        | 4.59%   |
| Kingston Technology Company      | 5        | 4.59%   |
| Micron/Crucial Technology        | 4        | 3.67%   |
| Marvell Technology Group         | 3        | 2.75%   |
| Toshiba America Info Systems     | 2        | 1.83%   |
| Silicon Integrated Systems [SiS] | 1        | 0.92%   |
| MAXIO Technology (Hangzhou)      | 1        | 0.92%   |
| LSI Logic / Symbios Logic        | 1        | 0.92%   |
| Integrated Technology Express    | 1        | 0.92%   |
| Chelsio Communications           | 1        | 0.92%   |
| Broadcom / LSI                   | 1        | 0.92%   |
| ASMedia Technology               | 1        | 0.92%   |
| ADATA Technology                 | 1        | 0.92%   |
| Adaptec                          | 1        | 0.92%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 12       | 8.57%   |
| AMD 400 Series Chipset SATA Controller                                                  | 8        | 5.71%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 6        | 4.29%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 6        | 4.29%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5        | 3.57%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5        | 3.57%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                                | 4        | 2.86%   |
| Intel SATA Controller [RAID mode]                                                       | 4        | 2.86%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 4        | 2.86%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 4        | 2.86%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 4        | 2.86%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3        | 2.14%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 3        | 2.14%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3        | 2.14%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 3        | 2.14%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3        | 2.14%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3        | 2.14%   |
| AMD FCH IDE Controller                                                                  | 3        | 2.14%   |
| AMD 500 Series Chipset SATA Controller                                                  | 3        | 2.14%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 2        | 1.43%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 2        | 1.43%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2        | 1.43%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 1.43%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 2        | 1.43%   |
| AMD FCH SATA Controller D                                                               | 2        | 1.43%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 1        | 0.71%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                                    | 1        | 0.71%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                             | 1        | 0.71%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                    | 1        | 0.71%   |
| SanDisk WD PC SN540 / Green SN350 NVMe SSD 1 TB (DRAM-less)                             | 1        | 0.71%   |
| Sandisk WD Black SN850X NVMe SSD                                                        | 1        | 0.71%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD                 | 1        | 0.71%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 0.71%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 1        | 0.71%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton2]                                              | 1        | 0.71%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                                | 1        | 0.71%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller                                 | 1        | 0.71%   |
| LSI Logic / Symbios Logic MegaRAID SAS 2108 [Liberator]                                 | 1        | 0.71%   |
| Kingston Company NV2 NVMe SSD TC2200 (DRAM-less)                                        | 1        | 0.71%   |
| Intel Raptor Lake SATA AHCI Controller                                                  | 1        | 0.71%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 61       | 56.48%  |
| NVMe | 22       | 20.37%  |
| IDE  | 18       | 16.67%  |
| RAID | 5        | 4.63%   |
| SCSI | 2        | 1.85%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 55       | 71.43%  |
| AMD    | 22       | 28.57%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i7-8700 CPU @ 3.20GHz            | 2        | 2.56%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 2        | 2.56%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 2        | 2.56%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 2.56%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 2        | 2.56%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2        | 2.56%   |
| AMD Ryzen 7 5700X 8-Core Processor          | 2        | 2.56%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 2        | 2.56%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 2        | 2.56%   |
| AMD FX-8300 Eight-Core Processor            | 2        | 2.56%   |
| Intel Xeon CPU X3460 @ 2.80GHz              | 1        | 1.28%   |
| Intel Xeon CPU E5-2670 v3 @ 2.30GHz         | 1        | 1.28%   |
| Intel Xeon CPU E5-2643 v3 @ 3.40GHz         | 1        | 1.28%   |
| Intel Xeon CPU E5-2603 v4 @ 1.70GHz         | 1        | 1.28%   |
| Intel Xeon CPU E3-1270 V2 @ 3.50GHz         | 1        | 1.28%   |
| Intel Xeon CPU E3-1226 v3 @ 3.30GHz         | 1        | 1.28%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz    | 1        | 1.28%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz      | 1        | 1.28%   |
| Intel Pentium Dual-Core CPU E6300 @ 2.80GHz | 1        | 1.28%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1        | 1.28%   |
| Intel Pentium D CPU 3.40GHz                 | 1        | 1.28%   |
| Intel Pentium CPU G3240 @ 3.10GHz           | 1        | 1.28%   |
| Intel Pentium 4 CPU 3.00GHz                 | 1        | 1.28%   |
| Intel Core i9-10850K CPU @ 3.60GHz          | 1        | 1.28%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 1        | 1.28%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1        | 1.28%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1        | 1.28%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1        | 1.28%   |
| Intel Core i7-5930K CPU @ 3.50GHz           | 1        | 1.28%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 1        | 1.28%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 1.28%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1        | 1.28%   |
| Intel Core i5-8500 CPU @ 3.00GHz            | 1        | 1.28%   |
| Intel Core i5-7500T CPU @ 2.70GHz           | 1        | 1.28%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 1        | 1.28%   |
| Intel Core i5-4590T CPU @ 2.00GHz           | 1        | 1.28%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 1        | 1.28%   |
| Intel Core i5-4570S CPU @ 2.90GHz           | 1        | 1.28%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 1        | 1.28%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 1        | 1.28%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 19       | 24.36%  |
| Intel Core i7           | 10       | 12.82%  |
| Intel Xeon              | 6        | 7.69%   |
| AMD Ryzen 5             | 6        | 7.69%   |
| AMD Ryzen 7             | 5        | 6.41%   |
| Intel Celeron           | 4        | 5.13%   |
| Intel Core 2 Quad       | 3        | 3.85%   |
| Intel Core 2 Duo        | 3        | 3.85%   |
| Intel Core i3           | 2        | 2.56%   |
| AMD Ryzen 3             | 2        | 2.56%   |
| AMD FX                  | 2        | 2.56%   |
| AMD A10                 | 2        | 2.56%   |
| Intel Pentium Silver    | 1        | 1.28%   |
| Intel Pentium Gold      | 1        | 1.28%   |
| Intel Pentium Dual-Core | 1        | 1.28%   |
| Intel Pentium Dual      | 1        | 1.28%   |
| Intel Pentium D         | 1        | 1.28%   |
| Intel Pentium 4         | 1        | 1.28%   |
| Intel Pentium           | 1        | 1.28%   |
| Intel Core i9           | 1        | 1.28%   |
| Intel Atom              | 1        | 1.28%   |
| AMD Sempron             | 1        | 1.28%   |
| AMD Ryzen Threadripper  | 1        | 1.28%   |
| AMD Ryzen 7 PRO         | 1        | 1.28%   |
| AMD Athlon              | 1        | 1.28%   |
| AMD A4                  | 1        | 1.28%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 28       | 36.36%  |
| 6      | 16       | 20.78%  |
| 2      | 16       | 20.78%  |
| 8      | 8        | 10.39%  |
| 1      | 5        | 6.49%   |
| 10     | 2        | 2.6%    |
| 24     | 1        | 1.3%    |
| 12     | 1        | 1.3%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 76       | 98.7%   |
| 2      | 1        | 1.3%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 39       | 50.65%  |
| 1      | 38       | 49.35%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 76       | 98.7%   |
| 32-bit         | 1        | 1.3%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 21       | 26.92%  |
| 0x306c3    | 5        | 6.41%   |
| 0x206a7    | 5        | 6.41%   |
| 0x906ea    | 4        | 5.13%   |
| 0x306a9    | 4        | 5.13%   |
| 0x1067a    | 4        | 5.13%   |
| 0x08701021 | 3        | 3.85%   |
| 0x0800820d | 3        | 3.85%   |
| 0x906e9    | 2        | 2.56%   |
| 0x506e3    | 2        | 2.56%   |
| 0x106e5    | 2        | 2.56%   |
| 0x0a20120a | 2        | 2.56%   |
| 0xf49      | 1        | 1.28%   |
| 0xa0655    | 1        | 1.28%   |
| 0xa0653    | 1        | 1.28%   |
| 0x906ed    | 1        | 1.28%   |
| 0x706a1    | 1        | 1.28%   |
| 0x6fd      | 1        | 1.28%   |
| 0x686      | 1        | 1.28%   |
| 0x506c9    | 1        | 1.28%   |
| 0x406f1    | 1        | 1.28%   |
| 0x406d8    | 1        | 1.28%   |
| 0x40651    | 1        | 1.28%   |
| 0x306f2    | 1        | 1.28%   |
| 0x10676    | 1        | 1.28%   |
| 0x0a601203 | 1        | 1.28%   |
| 0x08701013 | 1        | 1.28%   |
| 0x0810100b | 1        | 1.28%   |
| 0x08001138 | 1        | 1.28%   |
| 0x08001129 | 1        | 1.28%   |
| 0x06001119 | 1        | 1.28%   |
| 0x06000822 | 1        | 1.28%   |
| 0x03000027 | 1        | 1.28%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| KabyLake      | 11       | 14.29%  |
| Haswell       | 10       | 12.99%  |
| Penryn        | 6        | 7.79%   |
| Zen+          | 5        | 6.49%   |
| SandyBridge   | 5        | 6.49%   |
| Zen 2         | 4        | 5.19%   |
| Zen           | 4        | 5.19%   |
| Piledriver    | 4        | 5.19%   |
| IvyBridge     | 4        | 5.19%   |
| Skylake       | 3        | 3.9%    |
| Nehalem       | 3        | 3.9%    |
| Core          | 3        | 3.9%    |
| Zen 3         | 2        | 2.6%    |
| NetBurst      | 2        | 2.6%    |
| CometLake     | 2        | 2.6%    |
| Unknown       | 2        | 2.6%    |
| Silvermont    | 1        | 1.3%    |
| P6            | 1        | 1.3%    |
| K8 Hammer     | 1        | 1.3%    |
| K10 Llano     | 1        | 1.3%    |
| Goldmont plus | 1        | 1.3%    |
| Goldmont      | 1        | 1.3%    |
| Broadwell     | 1        | 1.3%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Nvidia                           | 28       | 35.9%   |
| Intel                            | 26       | 33.33%  |
| AMD                              | 22       | 28.21%  |
| Silicon Integrated Systems [SiS] | 1        | 1.28%   |
| ASPEED Technology                | 1        | 1.28%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 4        | 4.94%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 4        | 4.94%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 3        | 3.7%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3        | 3.7%    |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 3        | 3.7%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 2.47%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 2.47%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 2        | 2.47%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 2.47%   |
| Nvidia GA104 [GeForce RTX 3060 Ti]                                          | 2        | 2.47%   |
| Nvidia G96CGL [Quadro FX 580]                                               | 2        | 2.47%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 2.47%   |
| Intel HD Graphics 630                                                       | 2        | 2.47%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2        | 2.47%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 2        | 2.47%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 2.47%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2        | 2.47%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter           | 1        | 1.23%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 1.23%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                       | 1        | 1.23%   |
| Nvidia GT218 [GeForce 310]                                                  | 1        | 1.23%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 1.23%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 1.23%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1        | 1.23%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 1.23%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 1.23%   |
| Nvidia GK107 [NVS 510]                                                      | 1        | 1.23%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                           | 1        | 1.23%   |
| Nvidia GF119 [GeForce GT 610]                                               | 1        | 1.23%   |
| Nvidia GF108 [GeForce GT 430]                                               | 1        | 1.23%   |
| Nvidia AD107 [GeForce RTX 4060]                                             | 1        | 1.23%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1        | 1.23%   |
| Intel HD Graphics 500                                                       | 1        | 1.23%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 1        | 1.23%   |
| Intel GeminiLake [UHD Graphics 605]                                         | 1        | 1.23%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                   | 1        | 1.23%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 1.23%   |
| ASPEED Technology ASPEED Graphics Family                                    | 1        | 1.23%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 1        | 1.23%   |
| AMD Tahiti PRO [Radeon HD 7950/8950 OEM / R9 280]                           | 1        | 1.23%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| 1 x Nvidia  | 28       | 36.36%  |
| 1 x Intel   | 24       | 31.17%  |
| 1 x AMD     | 20       | 25.97%  |
| Other       | 1        | 1.3%    |
| 2 x AMD     | 1        | 1.3%    |
| 1 x SiS     | 1        | 1.3%    |
| Intel + AMD | 1        | 1.3%    |
| 1 x ASPEED  | 1        | 1.3%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 54       | 69.23%  |
| Proprietary | 18       | 23.08%  |
| Unknown     | 6        | 7.69%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 35       | 44.87%  |
| 7.01-8.0   | 12       | 15.38%  |
| 3.01-4.0   | 8        | 10.26%  |
| 0.01-0.5   | 8        | 10.26%  |
| 0.51-1.0   | 6        | 7.69%   |
| 5.01-6.0   | 3        | 3.85%   |
| 2.01-3.0   | 3        | 3.85%   |
| 1.01-2.0   | 3        | 3.85%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 14       | 17.07%  |
| Philips              | 9        | 10.98%  |
| Hewlett-Packard      | 9        | 10.98%  |
| Goldstar             | 6        | 7.32%   |
| Ancor Communications | 6        | 7.32%   |
| Acer                 | 6        | 7.32%   |
| Dell                 | 5        | 6.1%    |
| Lenovo               | 4        | 4.88%   |
| AOC                  | 4        | 4.88%   |
| Unknown              | 3        | 3.66%   |
| Iiyama               | 3        | 3.66%   |
| BenQ                 | 2        | 2.44%   |
| ___                  | 1        | 1.22%   |
| ViewSonic            | 1        | 1.22%   |
| Toshiba              | 1        | 1.22%   |
| Packard Bell         | 1        | 1.22%   |
| MSI                  | 1        | 1.22%   |
| HJW                  | 1        | 1.22%   |
| EXP                  | 1        | 1.22%   |
| eMachines            | 1        | 1.22%   |
| Eizo                 | 1        | 1.22%   |
| CVT                  | 1        | 1.22%   |
| CHI                  | 1        | 1.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM0091 1600x1200 432x324mm 21.3-inch   | 2        | 2.3%    |
| Philips 17S PHL0877 1280x1024 337x270mm 17.0-inch                      | 2        | 2.3%    |
| Hewlett-Packard 22m HPN3575 1920x1080 476x268mm 21.5-inch              | 2        | 2.3%    |
| Acer AL1716 ACRAD46 1280x1024 338x270mm 17.0-inch                      | 2        | 2.3%    |
| ___ LCDTV16 ___9000 1360x768                                           | 1        | 1.15%   |
| ViewSonic VA2261 VSC0F30 1920x1080 480x270mm 21.7-inch                 | 1        | 1.15%   |
| Unknown LCD TV 9000 1360x768 1600x900mm 72.3-inch                      | 1        | 1.15%   |
| Unknown LCD Monitor hp L1702 1280x1024                                 | 1        | 1.15%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch              | 1        | 1.15%   |
| Toshiba TV TSB0209 1920x1080 1594x900mm 72.1-inch                      | 1        | 1.15%   |
| Samsung Electronics T24B301 SAM098E 1920x1080 521x293mm 23.5-inch      | 1        | 1.15%   |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                       | 1        | 1.15%   |
| Samsung Electronics SyncMaster SAM0473 2048x1152 510x287mm 23.0-inch   | 1        | 1.15%   |
| Samsung Electronics SyncMaster SAM0226 1440x900 410x257mm 19.1-inch    | 1        | 1.15%   |
| Samsung Electronics SyncMaster SAM0029 2048x1536 312x234mm 15.4-inch   | 1        | 1.15%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch      | 1        | 1.15%   |
| Samsung Electronics S24B300 SAM08B3 1920x1080 521x293mm 23.5-inch      | 1        | 1.15%   |
| Samsung Electronics S/T 77/76BDF STN0007 1280x1024 312x234mm 15.4-inch | 1        | 1.15%   |
| Samsung Electronics LCD Monitor SyncMaster 1280x1024                   | 1        | 1.15%   |
| Samsung Electronics LCD Monitor SyncMaster                             | 1        | 1.15%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 890x500mm 40.2-inch  | 1        | 1.15%   |
| Samsung Electronics LCD Monitor SA300/350/360                          | 1        | 1.15%   |
| Samsung Electronics LCD Monitor S24D340                                | 1        | 1.15%   |
| Samsung Electronics LCD Monitor C27F390 5760x1080                      | 1        | 1.15%   |
| Samsung Electronics C27F398 SAM0D45 1920x1080 598x336mm 27.0-inch      | 1        | 1.15%   |
| Philips PHL 243S7 PHL090F 1920x1080 527x296mm 23.8-inch                | 1        | 1.15%   |
| Philips PHL 241P6Q PHL08DB 1920x1080 527x296mm 23.8-inch               | 1        | 1.15%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                | 1        | 1.15%   |
| Philips LCD Monitor PHL 234E5 4480x1440                                | 1        | 1.15%   |
| Philips 32M1C5500V PHLC29C 2560x1440 700x390mm 31.5-inch               | 1        | 1.15%   |
| Philips 247EL PHLC084 1920x1080 521x293mm 23.5-inch                    | 1        | 1.15%   |
| Philips 190B PHL086C 1280x1024 376x301mm 19.0-inch                     | 1        | 1.15%   |
| Packard Bell Viseo223DX PKB0385 1920x1080 477x268mm 21.5-inch          | 1        | 1.15%   |
| MSI Optix MAG24C MSI1462 1920x1080 521x293mm 23.5-inch                 | 1        | 1.15%   |
| Lenovo LI2215sD LEN65CC 1920x1080 476x267mm 21.5-inch                  | 1        | 1.15%   |
| Lenovo LEN D221 Wide LEN19DE 1680x1050 473x296mm 22.0-inch             | 1        | 1.15%   |
| Lenovo LCD Monitor LEN40A0 1366x768 309x174mm 14.0-inch                | 1        | 1.15%   |
| Lenovo L24e-30 LEN66BC 1920x1080 527x296mm 23.8-inch                   | 1        | 1.15%   |
| Iiyama PLX2483H IVM6114 1920x1080 531x299mm 24.0-inch                  | 1        | 1.15%   |
| Iiyama PLB2712HDS IVM6602 1920x1080 598x336mm 27.0-inch                | 1        | 1.15%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 30       | 38.46%  |
| 1280x1024 (SXGA)   | 9        | 11.54%  |
| 2560x1440 (QHD)    | 5        | 6.41%   |
| 1440x900 (WXGA+)   | 5        | 6.41%   |
| 3840x2160 (4K)     | 4        | 5.13%   |
| 1920x1200 (WUXGA)  | 4        | 5.13%   |
| 1366x768 (WXGA)    | 4        | 5.13%   |
| 1680x1050 (WSXGA+) | 3        | 3.85%   |
| Unknown            | 3        | 3.85%   |
| 3440x1440          | 2        | 2.56%   |
| 1600x1200          | 2        | 2.56%   |
| 5760x1080          | 1        | 1.28%   |
| 4480x1440          | 1        | 1.28%   |
| 2288x1287          | 1        | 1.28%   |
| 2048x1152          | 1        | 1.28%   |
| 1600x900 (HD+)     | 1        | 1.28%   |
| 1360x768           | 1        | 1.28%   |
| 1024x768 (XGA)     | 1        | 1.28%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 14       | 17.95%  |
| 24      | 10       | 12.82%  |
| Unknown | 9        | 11.54%  |
| 23      | 8        | 10.26%  |
| 27      | 5        | 6.41%   |
| 17      | 5        | 6.41%   |
| 19      | 4        | 5.13%   |
| 18      | 4        | 5.13%   |
| 31      | 3        | 3.85%   |
| 22      | 3        | 3.85%   |
| 72      | 2        | 2.56%   |
| 34      | 2        | 2.56%   |
| 15      | 2        | 2.56%   |
| 142     | 1        | 1.28%   |
| 54      | 1        | 1.28%   |
| 52      | 1        | 1.28%   |
| 40      | 1        | 1.28%   |
| 26      | 1        | 1.28%   |
| 25      | 1        | 1.28%   |
| 14      | 1        | 1.28%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 23       | 31.94%  |
| 401-500        | 20       | 27.78%  |
| Unknown        | 9        | 12.5%   |
| 301-350        | 7        | 9.72%   |
| 601-700        | 3        | 4.17%   |
| 701-800        | 2        | 2.78%   |
| 351-400        | 2        | 2.78%   |
| 1501-2000      | 2        | 2.78%   |
| 1001-1500      | 2        | 2.78%   |
| More than 2000 | 1        | 1.39%   |
| 801-900        | 1        | 1.39%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 42       | 57.53%  |
| 16/10   | 10       | 13.7%   |
| Unknown | 7        | 9.59%   |
| 5/4     | 6        | 8.22%   |
| 4/3     | 4        | 5.48%   |
| 21/9    | 2        | 2.74%   |
| 6/5     | 1        | 1.37%   |
| 1.00    | 1        | 1.37%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 26       | 35.14%  |
| Unknown        | 9        | 12.16%  |
| 141-150        | 8        | 10.81%  |
| 151-200        | 7        | 9.46%   |
| More than 1000 | 5        | 6.76%   |
| 351-500        | 5        | 6.76%   |
| 301-350        | 5        | 6.76%   |
| 251-300        | 5        | 6.76%   |
| 111-120        | 2        | 2.7%    |
| 81-90          | 1        | 1.35%   |
| 501-1000       | 1        | 1.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 39       | 52.7%   |
| 101-120 | 20       | 27.03%  |
| Unknown | 9        | 12.16%  |
| 1-50    | 5        | 6.76%   |
| 121-160 | 1        | 1.35%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 61       | 79.22%  |
| 2     | 9        | 11.69%  |
| 3     | 4        | 5.19%   |
| 0     | 3        | 3.9%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 48       | 48.48%  |
| Intel                            | 30       | 30.3%   |
| Qualcomm Atheros                 | 5        | 5.05%   |
| TP-Link                          | 2        | 2.02%   |
| NetGear                          | 2        | 2.02%   |
| Marvell Technology Group         | 2        | 2.02%   |
| Broadcom                         | 2        | 2.02%   |
| Solarflare Communications        | 1        | 1.01%   |
| Silicon Integrated Systems [SiS] | 1        | 1.01%   |
| Samsung Electronics              | 1        | 1.01%   |
| Ralink Technology                | 1        | 1.01%   |
| MediaTek                         | 1        | 1.01%   |
| JMicron Technology               | 1        | 1.01%   |
| D-Link System                    | 1        | 1.01%   |
| Chelsio Communications           | 1        | 1.01%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 40       | 37.04%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 3        | 2.78%   |
| Intel Ethernet Connection I217-LM                                      | 3        | 2.78%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3        | 2.78%   |
| Realtek RTL8125 2.5GbE Controller                                      | 2        | 1.85%   |
| NetGear WNA3100M(v1) Wireless-N 300 [Realtek RTL8192CU]                | 2        | 1.85%   |
| Intel I210 Gigabit Network Connection                                  | 2        | 1.85%   |
| Intel Ethernet Controller I225-V                                       | 2        | 1.85%   |
| Intel Ethernet Connection (7) I219-LM                                  | 2        | 1.85%   |
| Intel Ethernet Connection (5) I219-LM                                  | 2        | 1.85%   |
| Intel Ethernet Connection (2) I219-V                                   | 2        | 1.85%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                    | 1        | 0.93%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 1        | 0.93%   |
| Solarflare SFC9020 10G Ethernet Controller                             | 1        | 0.93%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 1        | 0.93%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1        | 0.93%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 1        | 0.93%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller            | 1        | 0.93%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                | 1        | 0.93%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 1        | 0.93%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 1        | 0.93%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 1        | 0.93%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller              | 1        | 0.93%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1        | 0.93%   |
| Ralink MT7601U Wireless Adapter                                        | 1        | 0.93%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1        | 0.93%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 1        | 0.93%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1        | 0.93%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 1        | 0.93%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter             | 1        | 0.93%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 1        | 0.93%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                | 1        | 0.93%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                      | 1        | 0.93%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 1        | 0.93%   |
| Intel Wireless 7260                                                    | 1        | 0.93%   |
| Intel Wi-Fi 6 AX200                                                    | 1        | 0.93%   |
| Intel I350 Gigabit Network Connection                                  | 1        | 0.93%   |
| Intel I211 Gigabit Network Connection                                  | 1        | 0.93%   |
| Intel Ethernet Connection I354 2.5 GbE Backplane                       | 1        | 0.93%   |
| Intel Ethernet Connection (7) I219-V                                   | 1        | 0.93%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 7        | 36.84%  |
| Qualcomm Atheros      | 3        | 15.79%  |
| Intel                 | 3        | 15.79%  |
| TP-Link               | 2        | 10.53%  |
| NetGear               | 2        | 10.53%  |
| Ralink Technology     | 1        | 5.26%   |
| MediaTek              | 1        | 5.26%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| NetGear WNA3100M(v1) Wireless-N 300 [Realtek RTL8192CU]       | 2        | 10.53%  |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                           | 1        | 5.26%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                  | 1        | 5.26%   |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 1        | 5.26%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller   | 1        | 5.26%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter       | 1        | 5.26%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter         | 1        | 5.26%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 1        | 5.26%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                    | 1        | 5.26%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller     | 1        | 5.26%   |
| Ralink MT7601U Wireless Adapter                               | 1        | 5.26%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 1        | 5.26%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter              | 1        | 5.26%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter    | 1        | 5.26%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 1        | 5.26%   |
| Intel Wireless 7260                                           | 1        | 5.26%   |
| Intel Wi-Fi 6 AX200                                           | 1        | 5.26%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 1        | 5.26%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 45       | 52.94%  |
| Intel                            | 28       | 32.94%  |
| Qualcomm Atheros                 | 2        | 2.35%   |
| Marvell Technology Group         | 2        | 2.35%   |
| Broadcom                         | 2        | 2.35%   |
| Solarflare Communications        | 1        | 1.18%   |
| Silicon Integrated Systems [SiS] | 1        | 1.18%   |
| Samsung Electronics              | 1        | 1.18%   |
| JMicron Technology               | 1        | 1.18%   |
| D-Link System                    | 1        | 1.18%   |
| Chelsio Communications           | 1        | 1.18%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 40       | 44.94%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 3        | 3.37%   |
| Intel Ethernet Connection I217-LM                                      | 3        | 3.37%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3        | 3.37%   |
| Realtek RTL8125 2.5GbE Controller                                      | 2        | 2.25%   |
| Intel I210 Gigabit Network Connection                                  | 2        | 2.25%   |
| Intel Ethernet Controller I225-V                                       | 2        | 2.25%   |
| Intel Ethernet Connection (7) I219-LM                                  | 2        | 2.25%   |
| Intel Ethernet Connection (5) I219-LM                                  | 2        | 2.25%   |
| Intel Ethernet Connection (2) I219-V                                   | 2        | 2.25%   |
| Solarflare SFC9020 10G Ethernet Controller                             | 1        | 1.12%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 1        | 1.12%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1        | 1.12%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1        | 1.12%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1        | 1.12%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1        | 1.12%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                | 1        | 1.12%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                      | 1        | 1.12%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 1        | 1.12%   |
| Intel I350 Gigabit Network Connection                                  | 1        | 1.12%   |
| Intel I211 Gigabit Network Connection                                  | 1        | 1.12%   |
| Intel Ethernet Connection I354 2.5 GbE Backplane                       | 1        | 1.12%   |
| Intel Ethernet Connection (7) I219-V                                   | 1        | 1.12%   |
| Intel Ethernet Connection (2) I218-LM                                  | 1        | 1.12%   |
| Intel Ethernet Connection (14) I219-V                                  | 1        | 1.12%   |
| Intel Ethernet Connection (11) I219-V                                  | 1        | 1.12%   |
| Intel 82579V Gigabit Network Connection                                | 1        | 1.12%   |
| Intel 82578DM Gigabit Network Connection                               | 1        | 1.12%   |
| Intel 82576 Gigabit Network Connection                                 | 1        | 1.12%   |
| Intel 82574L Gigabit Network Connection                                | 1        | 1.12%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)             | 1        | 1.12%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 1        | 1.12%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 1        | 1.12%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                        | 1        | 1.12%   |
| Chelsio T420-SO Unified Wire Ethernet Controller                       | 1        | 1.12%   |
| Chelsio T4 Generic function                                            | 1        | 1.12%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                | 1        | 1.12%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 1        | 1.12%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 76       | 80.85%  |
| WiFi     | 18       | 19.15%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 66       | 86.84%  |
| WiFi     | 10       | 13.16%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 56       | 71.79%  |
| 2     | 14       | 17.95%  |
| 3     | 4        | 5.13%   |
| 7     | 1        | 1.28%   |
| 5     | 1        | 1.28%   |
| 4     | 1        | 1.28%   |
| 0     | 1        | 1.28%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 67       | 87.01%  |
| Yes  | 10       | 12.99%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| ASUSTek Computer                | 4        | 33.33%  |
| Intel                           | 3        | 25%     |
| Qualcomm Atheros Communications | 2        | 16.67%  |
| Realtek Semiconductor           | 1        | 8.33%   |
| MediaTek                        | 1        | 8.33%   |
| Cambridge Silicon Radio         | 1        | 8.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| ASUS ASUS USB-BT500                                 | 2        | 16.67%  |
| Realtek Bluetooth Radio                             | 1        | 8.33%   |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 8.33%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1        | 8.33%   |
| MediaTek Wireless_Device                            | 1        | 8.33%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 8.33%   |
| Intel Bluetooth wireless interface                  | 1        | 8.33%   |
| Intel AX200 Bluetooth                               | 1        | 8.33%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1        | 8.33%   |
| ASUS Qualcomm Bluetooth 4.1                         | 1        | 8.33%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 8.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 49       | 38.58%  |
| Nvidia                           | 26       | 20.47%  |
| AMD                              | 26       | 20.47%  |
| Creative Labs                    | 6        | 4.72%   |
| Plantronics                      | 3        | 2.36%   |
| Texas Instruments                | 2        | 1.57%   |
| TEAC                             | 1        | 0.79%   |
| Silicon Integrated Systems [SiS] | 1        | 0.79%   |
| Medeli Electronics               | 1        | 0.79%   |
| M-Audio                          | 1        | 0.79%   |
| Logitech                         | 1        | 0.79%   |
| KORG                             | 1        | 0.79%   |
| Giga-Byte Technology             | 1        | 0.79%   |
| Generalplus Technology           | 1        | 0.79%   |
| Focusrite-Novation               | 1        | 0.79%   |
| FIFINE Microphones               | 1        | 0.79%   |
| Elite Silicon                    | 1        | 0.79%   |
| DCMT Technology                  | 1        | 0.79%   |
| Cirrus Logic                     | 1        | 0.79%   |
| Avance Logic                     | 1        | 0.79%   |
| ASUSTek Computer                 | 1        | 0.79%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 6        | 4.08%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6        | 4.08%   |
| AMD Starship/Matisse HD Audio Controller                                   | 6        | 4.08%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 6        | 4.08%   |
| Nvidia GP106 High Definition Audio Controller                              | 5        | 3.4%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5        | 3.4%    |
| Intel Cannon Lake PCH cAVS                                                 | 5        | 3.4%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5        | 3.4%    |
| Intel 200 Series PCH HD Audio                                              | 5        | 3.4%    |
| Nvidia GP104 High Definition Audio Controller                              | 4        | 2.72%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4        | 2.72%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 4        | 2.72%   |
| Plantronics HD1                                                            | 3        | 2.04%   |
| Nvidia High Definition Audio Controller                                    | 3        | 2.04%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3        | 2.04%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 3        | 2.04%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3        | 2.04%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]  | 3        | 2.04%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 3        | 2.04%   |
| AMD FCH Azalia Controller                                                  | 3        | 2.04%   |
| AMD Family 17h/19h HD Audio Controller                                     | 3        | 2.04%   |
| Texas Instruments PCM2902 Audio Codec                                      | 2        | 1.36%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 1.36%   |
| Nvidia GA104 High Definition Audio Controller                              | 2        | 1.36%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2        | 1.36%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2        | 1.36%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 2        | 1.36%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2        | 1.36%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2        | 1.36%   |
| TEAC US-1800                                                               | 1        | 0.68%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 1        | 0.68%   |
| Nvidia TU116 High Definition Audio Controller                              | 1        | 0.68%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 0.68%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1        | 0.68%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1        | 0.68%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1        | 0.68%   |
| Nvidia GF108 High Definition Audio Controller                              | 1        | 0.68%   |
| Nvidia Audio device                                                        | 1        | 0.68%   |
| Medeli Electronics USB Audio Device                                        | 1        | 0.68%   |
| M-Audio MIDISPORT 4x4 Anniv                                                | 1        | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 15       | 18.75%  |
| Corsair             | 15       | 18.75%  |
| Unknown             | 14       | 17.5%   |
| SK hynix            | 7        | 8.75%   |
| Micron Technology   | 5        | 6.25%   |
| G.Skill             | 5        | 6.25%   |
| Samsung Electronics | 4        | 5%      |
| Crucial             | 3        | 3.75%   |
| Nanya Technology    | 2        | 2.5%    |
| Unknown (ABCD)      | 1        | 1.25%   |
| Transcend           | 1        | 1.25%   |
| Team                | 1        | 1.25%   |
| Silicon Power       | 1        | 1.25%   |
| Ramaxel Technology  | 1        | 1.25%   |
| Patriot             | 1        | 1.25%   |
| GOODRAM             | 1        | 1.25%   |
| Avant               | 1        | 1.25%   |
| A-DATA Technology   | 1        | 1.25%   |
| Unknown             | 1        | 1.25%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3800MT/s       | 3        | 3.41%   |
| SK hynix RAM HMT451U6AFR8A-PB 4GB DIMM DDR3 1600MT/s         | 2        | 2.27%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s        | 2        | 2.27%   |
| Corsair RAM CMK32GX4M4A2666C16 8GB DIMM DDR4 3000MT/s        | 2        | 2.27%   |
| Unknown RAM SM3S320SD0488CABC 8192MB SODIMM DDR3 1600MT/s    | 1        | 1.14%   |
| Unknown RAM Module 8192MB DIMM DDR3 800MT/s                  | 1        | 1.14%   |
| Unknown RAM Module 64MB DIMM DRAM 100MT/s                    | 1        | 1.14%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                         | 1        | 1.14%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s               | 1        | 1.14%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                 | 1        | 1.14%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                         | 1        | 1.14%   |
| Unknown RAM Module 256MB DIMM DRAM 100MT/s                   | 1        | 1.14%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                | 1        | 1.14%   |
| Unknown RAM Module 2048MB DIMM SDRAM 667MT/s                 | 1        | 1.14%   |
| Unknown RAM Module 2048MB DIMM SDRAM                         | 1        | 1.14%   |
| Unknown RAM Module 128MB DIMM DRAM 100MT/s                   | 1        | 1.14%   |
| Unknown RAM Module 1024MB DIMM DDR 400MT/s                   | 1        | 1.14%   |
| Unknown RAM Module 1024MB DIMM DDR                           | 1        | 1.14%   |
| Unknown RAM 3600 C17 Series 8GB DIMM DDR4 3200MT/s           | 1        | 1.14%   |
| Unknown RAM 3000 C16 Series 8192MB DIMM DDR4 2133MT/s        | 1        | 1.14%   |
| Unknown RAM 1600 CL9 Series 8192MB DIMM DDR3 1066MT/s        | 1        | 1.14%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s | 1        | 1.14%   |
| Transcend RAM JM1333KLN-4G 4GB DIMM DDR3 1600MT/s            | 1        | 1.14%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 3200MT/s           | 1        | 1.14%   |
| SK hynix RAM Module 4GB DIMM DDR3 1333MT/s                   | 1        | 1.14%   |
| SK hynix RAM HMT451U7BFR8A-PB 4GB DIMM 1600MT/s              | 1        | 1.14%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s         | 1        | 1.14%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s         | 1        | 1.14%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM 1600MT/s              | 1        | 1.14%   |
| SK hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1866MT/s         | 1        | 1.14%   |
| SK hynix RAM HMA81GU6JJR8N-VK 8GB DIMM DDR4 2667MT/s         | 1        | 1.14%   |
| Silicon Power RAM Module 4GB DIMM DDR3 1600MT/s              | 1        | 1.14%   |
| Samsung RAM Module 2GB DIMM DDR3 1333MT/s                    | 1        | 1.14%   |
| Samsung RAM M393A4K40BB0-CPB 32GB DIMM DDR4 2133MT/s         | 1        | 1.14%   |
| Samsung RAM M378B5273DH0-CH9 4096MB DIMM DDR3 2133MT/s       | 1        | 1.14%   |
| Samsung RAM M378B1G73DB0-CK0 8192MB DIMM DDR3 2133MT/s       | 1        | 1.14%   |
| Ramaxel RAM RMUA5180ME78HBF-2666 16GB DIMM DDR4 2667MT/s     | 1        | 1.14%   |
| Patriot RAM 3600 C20 Series 16GB DIMM DDR4 3600MT/s          | 1        | 1.14%   |
| Nanya RAM Module 2GB DIMM DDR3 1333MT/s                      | 1        | 1.14%   |
| Nanya RAM M2X4G64CB8HG5N-DG 4GB DIMM DDR3 1867MT/s           | 1        | 1.14%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 33       | 49.25%  |
| DDR3    | 22       | 32.84%  |
| SDRAM   | 3        | 4.48%   |
| DDR5    | 2        | 2.99%   |
| DDR     | 2        | 2.99%   |
| Unknown | 2        | 2.99%   |
| LPDDR4  | 1        | 1.49%   |
| DRAM    | 1        | 1.49%   |
| DDR2    | 1        | 1.49%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 61       | 92.42%  |
| SODIMM | 5        | 7.58%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 25       | 34.25%  |
| 4096  | 18       | 24.66%  |
| 16384 | 15       | 20.55%  |
| 32768 | 5        | 6.85%   |
| 2048  | 5        | 6.85%   |
| 1024  | 2        | 2.74%   |
| 256   | 1        | 1.37%   |
| 128   | 1        | 1.37%   |
| 64    | 1        | 1.37%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 14       | 18.67%  |
| 3600    | 7        | 9.33%   |
| 2667    | 6        | 8%      |
| 2400    | 6        | 8%      |
| 2133    | 6        | 8%      |
| 1333    | 5        | 6.67%   |
| 3800    | 4        | 5.33%   |
| 3200    | 3        | 4%      |
| 1800    | 3        | 4%      |
| 3000    | 2        | 2.67%   |
| 1867    | 2        | 2.67%   |
| 667     | 2        | 2.67%   |
| Unknown | 2        | 2.67%   |
| 5600    | 1        | 1.33%   |
| 4800    | 1        | 1.33%   |
| 3666    | 1        | 1.33%   |
| 3534    | 1        | 1.33%   |
| 3400    | 1        | 1.33%   |
| 3066    | 1        | 1.33%   |
| 2666    | 1        | 1.33%   |
| 2176    | 1        | 1.33%   |
| 1866    | 1        | 1.33%   |
| 1632    | 1        | 1.33%   |
| 800     | 1        | 1.33%   |
| 400     | 1        | 1.33%   |
| 100     | 1        | 1.33%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Hewlett-Packard        | 3        | 50%     |
| Brother Industries     | 2        | 33.33%  |
| Custom Engineering SPA | 1        | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| HP ENVY 5000 series             | 1        | 16.67%  |
| HP DeskJet F4200 series         | 1        | 16.67%  |
| HP Deskjet 1510                 | 1        | 16.67%  |
| Custom Engineering SPA KUBE USB | 1        | 16.67%  |
| Brother MFC-J460DW              | 1        | 16.67%  |
| Brother HL-L2375DW series       | 1        | 16.67%  |

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
| Logitech                    | 6        | 35.29%  |
| Cubeternet                  | 2        | 11.76%  |
| Z-Star Microelectronics     | 1        | 5.88%   |
| Softkinetic                 | 1        | 5.88%   |
| Realtek Semiconductor       | 1        | 5.88%   |
| Microsoft                   | 1        | 5.88%   |
| Microdia                    | 1        | 5.88%   |
| MacroSilicon                | 1        | 5.88%   |
| KYE Systems (Mouse Systems) | 1        | 5.88%   |
| Hauppauge                   | 1        | 5.88%   |
| GEMBIRD                     | 1        | 5.88%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                     | Desktops | Percent |
|-------------------------------------------|----------|---------|
| Logitech Webcam C270                      | 3        | 17.65%  |
| Cubeternet GL-UPC822 UVC WebCam           | 2        | 11.76%  |
| Z-Star Vimicro USB Camera (Altair)        | 1        | 5.88%   |
| Softkinetic DepthSense 325                | 1        | 5.88%   |
| Realtek HD 720P Webcam                    | 1        | 5.88%   |
| Microsoft LifeCam Studio                  | 1        | 5.88%   |
| Microdia Camera                           | 1        | 5.88%   |
| MacroSilicon MiraBox Capture              | 1        | 5.88%   |
| Logitech Webcam C170                      | 1        | 5.88%   |
| Logitech C920 PRO HD Webcam               | 1        | 5.88%   |
| Logitech BRIO Ultra HD Webcam             | 1        | 5.88%   |
| KYE Systems (Mouse Systems) Genius Webcam | 1        | 5.88%   |
| Hauppauge HD PVR Pro 60                   | 1        | 5.88%   |
| GEMBIRD USB2.0 PC CAMERA                  | 1        | 5.88%   |

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
| 0     | 62       | 79.49%  |
| 1     | 14       | 17.95%  |
| 2     | 2        | 2.56%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 7        | 38.89%  |
| Unassigned class         | 4        | 22.22%  |
| Net/wireless             | 3        | 16.67%  |
| Communication controller | 2        | 11.11%  |
| Net/ethernet             | 1        | 5.56%   |
| Firewire controller      | 1        | 5.56%   |

