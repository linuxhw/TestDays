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

Total: 86

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Devuan 4                | 26       | 37.14%  |
| Devuan 5                | 14       | 20%     |
| Devuan 3                | 14       | 20%     |
| Devuan Testing/unstable | 7        | 10%     |
| Devuan 2.1              | 6        | 8.57%   |
| Devuan 6                | 1        | 1.43%   |
| Devuan 1.0.0            | 1        | 1.43%   |
| Devuan                  | 1        | 1.43%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Devuan | 67       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Desktops | Percent |
|-----------------------|----------|---------|
| 5.10.0-9-amd64        | 6        | 8.11%   |
| 5.10.0-21-amd64       | 4        | 5.41%   |
| 4.19.0-14-amd64       | 4        | 5.41%   |
| 6.1.0-13-amd64        | 3        | 4.05%   |
| 5.10.0-19-amd64       | 3        | 4.05%   |
| 4.19.0-16-amd64       | 3        | 4.05%   |
| 5.10.0-8-amd64        | 2        | 2.7%    |
| 5.10.0-6-amd64        | 2        | 2.7%    |
| 5.10.0-23-amd64       | 2        | 2.7%    |
| 4.19.0-9-amd64        | 2        | 2.7%    |
| 4.19.0-13-amd64       | 2        | 2.7%    |
| 4.19.0-10-amd64       | 2        | 2.7%    |
| 6.5.0-0.deb12.1-amd64 | 1        | 1.35%   |
| 6.3.0-2-amd64         | 1        | 1.35%   |
| 6.2.12                | 1        | 1.35%   |
| 6.1.7                 | 1        | 1.35%   |
| 6.1.0-6-amd64         | 1        | 1.35%   |
| 6.1.0-16-amd64        | 1        | 1.35%   |
| 6.1.0-10-amd64        | 1        | 1.35%   |
| 6.1.0-0.deb11.5-amd64 | 1        | 1.35%   |
| 6.0.0-5-amd64         | 1        | 1.35%   |
| 5.9.0-1-amd64         | 1        | 1.35%   |
| 5.8.0-3-amd64         | 1        | 1.35%   |
| 5.7.0-1-amd64         | 1        | 1.35%   |
| 5.7.0-0.bpo.2-amd64   | 1        | 1.35%   |
| 5.18.14-devuan        | 1        | 1.35%   |
| 5.18.11-gnu           | 1        | 1.35%   |
| 5.18.0-1-amd64        | 1        | 1.35%   |
| 5.16.0-1-amd64        | 1        | 1.35%   |
| 5.15.0-2-amd64        | 1        | 1.35%   |
| 5.15.0-0.bpo.2-amd64  | 1        | 1.35%   |
| 5.14.0-kali2-amd64    | 1        | 1.35%   |
| 5.10.0-5-amd64        | 1        | 1.35%   |
| 5.10.0-24-amd64       | 1        | 1.35%   |
| 5.10.0-22-amd64       | 1        | 1.35%   |
| 5.10.0-2-amd64        | 1        | 1.35%   |
| 5.10.0-18-amd64       | 1        | 1.35%   |
| 5.10.0-16-amd64       | 1        | 1.35%   |
| 5.10.0-15-amd64       | 1        | 1.35%   |
| 5.10.0-11-amd64       | 1        | 1.35%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.10.0   | 25       | 36.23%  |
| 4.19.0   | 15       | 21.74%  |
| 6.1.0    | 7        | 10.14%  |
| 4.9.0    | 4        | 5.8%    |
| 5.7.0    | 2        | 2.9%    |
| 5.15.0   | 2        | 2.9%    |
| 6.5.0    | 1        | 1.45%   |
| 6.3.0    | 1        | 1.45%   |
| 6.2.12   | 1        | 1.45%   |
| 6.1.7    | 1        | 1.45%   |
| 6.0.0    | 1        | 1.45%   |
| 5.9.0    | 1        | 1.45%   |
| 5.8.0    | 1        | 1.45%   |
| 5.18.14  | 1        | 1.45%   |
| 5.18.11  | 1        | 1.45%   |
| 5.18.0   | 1        | 1.45%   |
| 5.16.0   | 1        | 1.45%   |
| 5.14.0   | 1        | 1.45%   |
| 4.19.112 | 1        | 1.45%   |
| 4.18.0   | 1        | 1.45%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 25       | 36.23%  |
| 4.19    | 16       | 23.19%  |
| 6.1     | 8        | 11.59%  |
| 4.9     | 4        | 5.8%    |
| 5.18    | 3        | 4.35%   |
| 5.7     | 2        | 2.9%    |
| 5.15    | 2        | 2.9%    |
| 6.5     | 1        | 1.45%   |
| 6.3     | 1        | 1.45%   |
| 6.2     | 1        | 1.45%   |
| 6.0     | 1        | 1.45%   |
| 5.9     | 1        | 1.45%   |
| 5.8     | 1        | 1.45%   |
| 5.16    | 1        | 1.45%   |
| 5.14    | 1        | 1.45%   |
| 4.18    | 1        | 1.45%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 64       | 95.52%  |
| i686   | 3        | 4.48%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| XFCE       | 30       | 42.86%  |
| Unknown    | 13       | 18.57%  |
| MATE       | 8        | 11.43%  |
| KDE5       | 8        | 11.43%  |
| LXDE       | 3        | 4.29%   |
| Cinnamon   | 3        | 4.29%   |
| X-Cinnamon | 1        | 1.43%   |
| LXQt       | 1        | 1.43%   |
| i3         | 1        | 1.43%   |
| GNOME      | 1        | 1.43%   |
| awesome    | 1        | 1.43%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 57       | 83.82%  |
| Tty     | 8        | 11.76%  |
| Unknown | 3        | 4.41%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SLiM    | 29       | 43.28%  |
| Unknown | 16       | 23.88%  |
| LightDM | 12       | 17.91%  |
| SDDM    | 6        | 8.96%   |
| NODM    | 2        | 2.99%   |
| XDM     | 1        | 1.49%   |
| LXDM    | 1        | 1.49%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 22       | 32.35%  |
| fr_FR   | 8        | 11.76%  |
| en_GB   | 7        | 10.29%  |
| Unknown | 5        | 7.35%   |
| ru_RU   | 4        | 5.88%   |
| C       | 4        | 5.88%   |
| sk_SK   | 3        | 4.41%   |
| pt_BR   | 3        | 4.41%   |
| en_AU   | 3        | 4.41%   |
| fr_BE   | 2        | 2.94%   |
| en_NZ   | 2        | 2.94%   |
| de_DE   | 2        | 2.94%   |
| pl_PL   | 1        | 1.47%   |
| it_IT   | 1        | 1.47%   |
| en_CA   | 1        | 1.47%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 39       | 58.21%  |
| EFI  | 28       | 41.79%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 59       | 88.06%  |
| Overlay | 2        | 2.99%   |
| Btrfs   | 2        | 2.99%   |
| Xfs     | 1        | 1.49%   |
| Ext3    | 1        | 1.49%   |
| Ext2    | 1        | 1.49%   |
| Unknown | 1        | 1.49%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 40       | 57.14%  |
| MBR     | 24       | 34.29%  |
| Unknown | 6        | 8.57%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 45       | 65.22%  |
| Yes       | 24       | 34.78%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 48       | 71.64%  |
| Yes       | 19       | 28.36%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 15       | 22.39%  |
| ASUSTek Computer    | 14       | 20.9%   |
| MSI                 | 10       | 14.93%  |
| Dell                | 6        | 8.96%   |
| Hewlett-Packard     | 5        | 7.46%   |
| ASRock              | 5        | 7.46%   |
| Intel               | 3        | 4.48%   |
| Lenovo              | 2        | 2.99%   |
| Supermicro          | 1        | 1.49%   |
| Sun Microsystems    | 1        | 1.49%   |
| Online Labs         | 1        | 1.49%   |
| LORD ELECTRONICS    | 1        | 1.49%   |
| Google              | 1        | 1.49%   |
| AMI                 | 1        | 1.49%   |
| Acer                | 1        | 1.49%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Supermicro SYS-1018GR-T                           | 1        | 1.49%   |
| Sun Microsystems Ultra 24                         | 1        | 1.49%   |
| Online Labs SR                                    | 1        | 1.49%   |
| MSI MS-7B86                                       | 1        | 1.49%   |
| MSI MS-7B84                                       | 1        | 1.49%   |
| MSI MS-7B53                                       | 1        | 1.49%   |
| MSI MS-7A38                                       | 1        | 1.49%   |
| MSI MS-7A36                                       | 1        | 1.49%   |
| MSI MS-7A34                                       | 1        | 1.49%   |
| MSI MS-7885                                       | 1        | 1.49%   |
| MSI MS-7693                                       | 1        | 1.49%   |
| MSI MS-7678                                       | 1        | 1.49%   |
| MSI MS-7673                                       | 1        | 1.49%   |
| LORD ELECTRONICS LORD G4x 775 ICH7 8712 As Design | 1        | 1.49%   |
| Lenovo ThinkStation P330 30C5S1LQ00               | 1        | 1.49%   |
| Lenovo ThinkStation E20 4220CTO                   | 1        | 1.49%   |
| Intel X99                                         | 1        | 1.49%   |
| Intel D815EEA AAA45884-401                        | 1        | 1.49%   |
| Intel AHV                                         | 1        | 1.49%   |
| HP Z640 Workstation                               | 1        | 1.49%   |
| HP Z220 SFF Workstation                           | 1        | 1.49%   |
| HP ProDesk 600 G1 SFF                             | 1        | 1.49%   |
| HP EliteDesk 800 G1 DM                            | 1        | 1.49%   |
| HP Compaq 8200 Elite SFF PC                       | 1        | 1.49%   |
| Google Tricky                                     | 1        | 1.49%   |
| Gigabyte Z390 GAMING SLI                          | 1        | 1.49%   |
| Gigabyte P55A-UD3                                 | 1        | 1.49%   |
| Gigabyte MZGLKBP-00                               | 1        | 1.49%   |
| Gigabyte H81M-S2H                                 | 1        | 1.49%   |
| Gigabyte H310M S2H 2.0                            | 1        | 1.49%   |
| Gigabyte H170-HD3-CF                              | 1        | 1.49%   |
| Gigabyte H170-HD3                                 | 1        | 1.49%   |
| Gigabyte GA-G41M-ES2L                             | 1        | 1.49%   |
| Gigabyte F2A55M-HD2                               | 1        | 1.49%   |
| Gigabyte B75M-D3V                                 | 1        | 1.49%   |
| Gigabyte B650I AORUS ULTRA                        | 1        | 1.49%   |
| Gigabyte B550I AORUS PRO AX                       | 1        | 1.49%   |
| Gigabyte B550 GAMING X V2                         | 1        | 1.49%   |
| Gigabyte B450 AORUS ELITE                         | 1        | 1.49%   |
| Gigabyte 970A-DS3P                                | 1        | 1.49%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| Dell OptiPlex           | 5        | 7.46%   |
| ASUS PRIME              | 4        | 5.97%   |
| Lenovo ThinkStation     | 2        | 2.99%   |
| ASUS ROG                | 2        | 2.99%   |
| Supermicro SYS-1018GR-T | 1        | 1.49%   |
| Sun Microsystems Ultra  | 1        | 1.49%   |
| Online Labs SR          | 1        | 1.49%   |
| MSI MS-7B86             | 1        | 1.49%   |
| MSI MS-7B84             | 1        | 1.49%   |
| MSI MS-7B53             | 1        | 1.49%   |
| MSI MS-7A38             | 1        | 1.49%   |
| MSI MS-7A36             | 1        | 1.49%   |
| MSI MS-7A34             | 1        | 1.49%   |
| MSI MS-7885             | 1        | 1.49%   |
| MSI MS-7693             | 1        | 1.49%   |
| MSI MS-7678             | 1        | 1.49%   |
| MSI MS-7673             | 1        | 1.49%   |
| LORD ELECTRONICS LORD   | 1        | 1.49%   |
| Intel X99               | 1        | 1.49%   |
| Intel D815EEA           | 1        | 1.49%   |
| Intel AHV               | 1        | 1.49%   |
| HP Z640                 | 1        | 1.49%   |
| HP Z220                 | 1        | 1.49%   |
| HP ProDesk              | 1        | 1.49%   |
| HP EliteDesk            | 1        | 1.49%   |
| HP Compaq               | 1        | 1.49%   |
| Google Tricky           | 1        | 1.49%   |
| Gigabyte Z390           | 1        | 1.49%   |
| Gigabyte P55A-UD3       | 1        | 1.49%   |
| Gigabyte MZGLKBP-00     | 1        | 1.49%   |
| Gigabyte H81M-S2H       | 1        | 1.49%   |
| Gigabyte H310M          | 1        | 1.49%   |
| Gigabyte H170-HD3-CF    | 1        | 1.49%   |
| Gigabyte H170-HD3       | 1        | 1.49%   |
| Gigabyte GA-G41M-ES2L   | 1        | 1.49%   |
| Gigabyte F2A55M-HD2     | 1        | 1.49%   |
| Gigabyte B75M-D3V       | 1        | 1.49%   |
| Gigabyte B650I          | 1        | 1.49%   |
| Gigabyte B550I          | 1        | 1.49%   |
| Gigabyte B550           | 1        | 1.49%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 10       | 14.93%  |
| 2019 | 8        | 11.94%  |
| 2013 | 6        | 8.96%   |
| 2012 | 5        | 7.46%   |
| 2011 | 5        | 7.46%   |
| 2020 | 4        | 5.97%   |
| 2017 | 4        | 5.97%   |
| 2014 | 4        | 5.97%   |
| 2016 | 3        | 4.48%   |
| 2015 | 3        | 4.48%   |
| 2010 | 3        | 4.48%   |
| 2022 | 2        | 2.99%   |
| 2009 | 2        | 2.99%   |
| 2008 | 2        | 2.99%   |
| 2007 | 2        | 2.99%   |
| 2023 | 1        | 1.49%   |
| 2021 | 1        | 1.49%   |
| 2006 | 1        | 1.49%   |
| 2000 | 1        | 1.49%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 67       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 66       | 98.51%  |
| Enabled  | 1        | 1.49%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 65       | 97.01%  |
| Yes  | 2        | 2.99%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 20       | 29.85%  |
| 32.01-64.0  | 13       | 19.4%   |
| 8.01-16.0   | 12       | 17.91%  |
| 4.01-8.0    | 8        | 11.94%  |
| 64.01-256.0 | 5        | 7.46%   |
| 3.01-4.0    | 4        | 5.97%   |
| 1.01-2.0    | 4        | 5.97%   |
| 0.01-0.5    | 1        | 1.49%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 23       | 32.39%  |
| 4.01-8.0   | 11       | 15.49%  |
| 2.01-3.0   | 11       | 15.49%  |
| 0.51-1.0   | 10       | 14.08%  |
| 3.01-4.0   | 6        | 8.45%   |
| 8.01-16.0  | 5        | 7.04%   |
| 0.01-0.5   | 3        | 4.23%   |
| 16.01-24.0 | 2        | 2.82%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 26       | 38.81%  |
| 3      | 14       | 20.9%   |
| 2      | 12       | 17.91%  |
| 5      | 5        | 7.46%   |
| 4      | 5        | 7.46%   |
| 6      | 4        | 5.97%   |
| 7      | 1        | 1.49%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 44       | 65.67%  |
| Yes       | 23       | 34.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 66       | 98.51%  |
| No        | 1        | 1.49%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 52       | 76.47%  |
| Yes       | 16       | 23.53%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 57       | 85.07%  |
| Yes       | 10       | 14.93%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| France      | 11       | 16.42%  |
| USA         | 10       | 14.93%  |
| Russia      | 5        | 7.46%   |
| UK          | 4        | 5.97%   |
| Ukraine     | 3        | 4.48%   |
| Slovakia    | 3        | 4.48%   |
| Poland      | 3        | 4.48%   |
| Germany     | 3        | 4.48%   |
| Brazil      | 3        | 4.48%   |
| Australia   | 3        | 4.48%   |
| New Zealand | 2        | 2.99%   |
| Netherlands | 2        | 2.99%   |
| Canada      | 2        | 2.99%   |
| Belgium     | 2        | 2.99%   |
| Argentina   | 2        | 2.99%   |
| Tunisia     | 1        | 1.49%   |
| Spain       | 1        | 1.49%   |
| South Korea | 1        | 1.49%   |
| Puerto Rico | 1        | 1.49%   |
| Italy       | 1        | 1.49%   |
| Israel      | 1        | 1.49%   |
| Georgia     | 1        | 1.49%   |
| China       | 1        | 1.49%   |
| Bulgaria    | 1        | 1.49%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Bratislava       | 3        | 4.48%   |
| Bagnolet         | 3        | 4.48%   |
| Volzhskiy        | 2        | 2.99%   |
| Toronto          | 2        | 2.99%   |
| Sydney           | 2        | 2.99%   |
| Auckland         | 2        | 2.99%   |
| Xiamen           | 1        | 1.49%   |
| Wroclaw          | 1        | 1.49%   |
| Waterford        | 1        | 1.49%   |
| Vladikavkaz      | 1        | 1.49%   |
| Vise             | 1        | 1.49%   |
| Tel Aviv         | 1        | 1.49%   |
| Tbilisi          | 1        | 1.49%   |
| Sofia            | 1        | 1.49%   |
| Seongbuk-gu      | 1        | 1.49%   |
| Sao Paulo        | 1        | 1.49%   |
| Saint-Herblain   | 1        | 1.49%   |
| Rugby            | 1        | 1.49%   |
| Roubaix          | 1        | 1.49%   |
| Rio de Janeiro   | 1        | 1.49%   |
| Renkum           | 1        | 1.49%   |
| Radzionkow       | 1        | 1.49%   |
| Port Richey      | 1        | 1.49%   |
| Poperinge        | 1        | 1.49%   |
| Paris            | 1        | 1.49%   |
| Oleksandriya     | 1        | 1.49%   |
| Okehampton       | 1        | 1.49%   |
| Novopokrovskoye  | 1        | 1.49%   |
| Norman           | 1        | 1.49%   |
| Nérac           | 1        | 1.49%   |
| Monferran-Plaves | 1        | 1.49%   |
| Miedziana Gora   | 1        | 1.49%   |
| Miami            | 1        | 1.49%   |
| Manaus           | 1        | 1.49%   |
| Madrid           | 1        | 1.49%   |
| Loosdrecht       | 1        | 1.49%   |
| Lincoln          | 1        | 1.49%   |
| Leeds            | 1        | 1.49%   |
| Lahr             | 1        | 1.49%   |
| L'Albenc         | 1        | 1.49%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 29       | 51     | 23.2%   |
| Seagate             | 21       | 32     | 16.8%   |
| Kingston            | 11       | 14     | 8.8%    |
| Samsung Electronics | 10       | 21     | 8%      |
| Toshiba             | 8        | 8      | 6.4%    |
| SanDisk             | 6        | 6      | 4.8%    |
| Crucial             | 6        | 8      | 4.8%    |
| Netac               | 2        | 2      | 1.6%    |
| Micron Technology   | 2        | 2      | 1.6%    |
| Maxtor              | 2        | 2      | 1.6%    |
| Intel               | 2        | 4      | 1.6%    |
| Hitachi             | 2        | 2      | 1.6%    |
| HGST                | 2        | 2      | 1.6%    |
| Dogfish             | 2        | 2      | 1.6%    |
| A-DATA Technology   | 2        | 2      | 1.6%    |
| WD MediaMax         | 1        | 3      | 0.8%    |
| Unknown             | 1        | 1      | 0.8%    |
| Transcend           | 1        | 2      | 0.8%    |
| Team                | 1        | 1      | 0.8%    |
| Supermicro          | 1        | 1      | 0.8%    |
| SK hynix            | 1        | 1      | 0.8%    |
| PNY                 | 1        | 1      | 0.8%    |
| Plextor             | 1        | 1      | 0.8%    |
| Lexar               | 1        | 1      | 0.8%    |
| KingDian            | 1        | 1      | 0.8%    |
| Intenso             | 1        | 1      | 0.8%    |
| IBM/Hitachi         | 1        | 1      | 0.8%    |
| HPE                 | 1        | 2      | 0.8%    |
| Hewlett-Packard     | 1        | 2      | 0.8%    |
| GOODRAM             | 1        | 1      | 0.8%    |
| Fujitsu             | 1        | 1      | 0.8%    |
| Corsair             | 1        | 1      | 0.8%    |
| China               | 1        | 1      | 0.8%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Kingston SA400S37120G 120GB SSD  | 3        | 1.99%   |
| Kingston SA2000M8250G 250GB      | 3        | 1.99%   |
| WDC WD10EZEX-08WN4A0 1TB         | 2        | 1.32%   |
| WDC WD10EZEX-00BBHA0 1TB         | 2        | 1.32%   |
| WDC WD10EARX-00N0YB0 1TB         | 2        | 1.32%   |
| Seagate ST3500418AS 500GB        | 2        | 1.32%   |
| Seagate ST2000DX002-2DV164 2TB   | 2        | 1.32%   |
| Seagate ST2000DM008-2FR102 2TB   | 2        | 1.32%   |
| SanDisk SDSSDX240GG25 240GB      | 2        | 1.32%   |
| Samsung SSD 860 EVO 250GB        | 2        | 1.32%   |
| Kingston SA400S37480G 480GB SSD  | 2        | 1.32%   |
| Hitachi HDS721616PLA380 160GB    | 2        | 1.32%   |
| WDC WDS500G3X0C-00SJG0 500GB     | 1        | 0.66%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 1        | 0.66%   |
| WDC WDS480G2G0A-00JH30 480GB SSD | 1        | 0.66%   |
| WDC WDS120G2G0A-00JH30 120GB SSD | 1        | 0.66%   |
| WDC WD800BB-00JHC0 80GB          | 1        | 0.66%   |
| WDC WD7500AALX-009BA0 752GB      | 1        | 0.66%   |
| WDC WD5001AALS-00L3B2 500GB      | 1        | 0.66%   |
| WDC WD5001AALS-00E3A0 500GB      | 1        | 0.66%   |
| WDC WD5000LPVX-00V0TT0 500GB     | 1        | 0.66%   |
| WDC WD5000BPVT-24HXZT3 500GB     | 1        | 0.66%   |
| WDC WD5000AZLX-75K2TA0 500GB     | 1        | 0.66%   |
| WDC WD40EFRX-68WT0N0 4TB         | 1        | 0.66%   |
| WDC WD40EDAZ-11SLVB0 4TB         | 1        | 0.66%   |
| WDC WD20PURZ-85GU6Y0 2TB         | 1        | 0.66%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 1        | 0.66%   |
| WDC WD20EZRX-00DC0B0 2TB         | 1        | 0.66%   |
| WDC WD20EZRX-00D8PB0 2TB         | 1        | 0.66%   |
| WDC WD20EZAZ-00L9GB0 2TB         | 1        | 0.66%   |
| WDC WD20EFRX-68EUZN0 2TB         | 1        | 0.66%   |
| WDC WD2003FZEX-00Z4SA0 2TB       | 1        | 0.66%   |
| WDC WD2003FZEX-00SRLA0 2TB       | 1        | 0.66%   |
| WDC WD1600AAJS-00YZCA0 160GB     | 1        | 0.66%   |
| WDC WD1502FAEX-007BA0 1TB        | 1        | 0.66%   |
| WDC WD1200JS-55NCB1 120GB        | 1        | 0.66%   |
| WDC WD10SPZX-22Z10T1 1TB         | 1        | 0.66%   |
| WDC WD10JFCX-68N6GN0 1TB         | 1        | 0.66%   |
| WDC WD10EZRX-00D8PB0 1TB         | 1        | 0.66%   |
| WDC WD10EZEX-75M2NA0 1TB         | 1        | 0.66%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 26       | 47     | 40.63%  |
| Seagate             | 20       | 31     | 31.25%  |
| Toshiba             | 6        | 6      | 9.38%   |
| Samsung Electronics | 2        | 3      | 3.13%   |
| Maxtor              | 2        | 2      | 3.13%   |
| Hitachi             | 2        | 2      | 3.13%   |
| HGST                | 2        | 2      | 3.13%   |
| IBM/Hitachi         | 1        | 1      | 1.56%   |
| HPE                 | 1        | 2      | 1.56%   |
| Hewlett-Packard     | 1        | 2      | 1.56%   |
| Fujitsu             | 1        | 1      | 1.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 9        | 12     | 19.57%  |
| Kingston            | 8        | 10     | 17.39%  |
| WDC                 | 3        | 3      | 6.52%   |
| SanDisk             | 3        | 3      | 6.52%   |
| Netac               | 2        | 2      | 4.35%   |
| Micron Technology   | 2        | 2      | 4.35%   |
| Dogfish             | 2        | 2      | 4.35%   |
| Crucial             | 2        | 3      | 4.35%   |
| A-DATA Technology   | 2        | 2      | 4.35%   |
| Transcend           | 1        | 2      | 2.17%   |
| Team                | 1        | 1      | 2.17%   |
| Supermicro          | 1        | 1      | 2.17%   |
| SK hynix            | 1        | 1      | 2.17%   |
| PNY                 | 1        | 1      | 2.17%   |
| Plextor             | 1        | 1      | 2.17%   |
| Lexar               | 1        | 1      | 2.17%   |
| KingDian            | 1        | 1      | 2.17%   |
| Intenso             | 1        | 1      | 2.17%   |
| Intel               | 1        | 3      | 2.17%   |
| GOODRAM             | 1        | 1      | 2.17%   |
| Corsair             | 1        | 1      | 2.17%   |
| China               | 1        | 1      | 2.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 47       | 99     | 43.93%  |
| SSD     | 39       | 55     | 36.45%  |
| NVMe    | 18       | 22     | 16.82%  |
| Unknown | 2        | 4      | 1.87%   |
| MMC     | 1        | 1      | 0.93%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 62       | 151    | 72.94%  |
| NVMe | 18       | 22     | 21.18%  |
| SAS  | 4        | 7      | 4.71%   |
| MMC  | 1        | 1      | 1.18%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 45       | 79     | 49.45%  |
| 0.51-1.0   | 25       | 44     | 27.47%  |
| 1.01-2.0   | 14       | 23     | 15.38%  |
| 3.01-4.0   | 5        | 6      | 5.49%   |
| 4.01-10.0  | 2        | 2      | 2.2%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 14       | 20%     |
| 251-500        | 13       | 18.57%  |
| 1001-2000      | 13       | 18.57%  |
| 101-250        | 10       | 14.29%  |
| More than 3000 | 8        | 11.43%  |
| 21-50          | 3        | 4.29%   |
| 51-100         | 3        | 4.29%   |
| 2001-3000      | 2        | 2.86%   |
| 1-20           | 2        | 2.86%   |
| Unknown        | 2        | 2.86%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 16       | 23.19%  |
| 1-20           | 14       | 20.29%  |
| 21-50          | 7        | 10.14%  |
| 251-500        | 6        | 8.7%    |
| 1001-2000      | 6        | 8.7%    |
| 501-1000       | 6        | 8.7%    |
| 51-100         | 6        | 8.7%    |
| More than 3000 | 3        | 4.35%   |
| 2001-3000      | 3        | 4.35%   |
| Unknown        | 2        | 2.9%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Hitachi HDS721616PLA380 160GB         | 2        | 2      | 9.09%   |
| WDC WD5000LPVX-00V0TT0 500GB          | 1        | 1      | 4.55%   |
| WDC WD5000BPVT-24HXZT3 500GB          | 1        | 1      | 4.55%   |
| WDC WD1502FAEX-007BA0 1TB             | 1        | 1      | 4.55%   |
| WDC WD10EARX-00N0YB0 1TB              | 1        | 1      | 4.55%   |
| Toshiba MQ04ABF100 1TB                | 1        | 1      | 4.55%   |
| Toshiba MQ02ABF100 1TB                | 1        | 1      | 4.55%   |
| SK hynix SH920 mSATA 128GB SSD        | 1        | 1      | 4.55%   |
| Seagate ST3500418AS 500GB             | 1        | 1      | 4.55%   |
| Samsung Electronics SSD 970 EVO 500GB | 1        | 1      | 4.55%   |
| Samsung Electronics SP2504C 250GB     | 1        | 1      | 4.55%   |
| Samsung Electronics HD160JJ 160GB     | 1        | 1      | 4.55%   |
| Maxtor 6E040L0 40GB                   | 1        | 1      | 4.55%   |
| Kingston SA400S37120G 120GB SSD       | 1        | 1      | 4.55%   |
| Intel SSDSC2BF120A5 120GB             | 1        | 3      | 4.55%   |
| HPE MB4000GEFNA 4TB                   | 1        | 2      | 4.55%   |
| HGST HTS545050A7E680 500GB            | 1        | 1      | 4.55%   |
| HGST HTE721010A9E630 1TB              | 1        | 1      | 4.55%   |
| Hewlett-Packard VB0250EAVER 250GB     | 1        | 2      | 4.55%   |
| Fujitsu MHV2060BH PL 64GB             | 1        | 1      | 4.55%   |
| China SATA SSD 64GB                   | 1        | 1      | 4.55%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 4        | 4      | 19.05%  |
| Toshiba             | 2        | 2      | 9.52%   |
| Samsung Electronics | 2        | 3      | 9.52%   |
| Hitachi             | 2        | 2      | 9.52%   |
| HGST                | 2        | 2      | 9.52%   |
| SK hynix            | 1        | 1      | 4.76%   |
| Seagate             | 1        | 1      | 4.76%   |
| Maxtor              | 1        | 1      | 4.76%   |
| Kingston            | 1        | 1      | 4.76%   |
| Intel               | 1        | 3      | 4.76%   |
| HPE                 | 1        | 2      | 4.76%   |
| Hewlett-Packard     | 1        | 2      | 4.76%   |
| Fujitsu             | 1        | 1      | 4.76%   |
| China               | 1        | 1      | 4.76%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 4        | 4      | 25%     |
| Toshiba             | 2        | 2      | 12.5%   |
| Hitachi             | 2        | 2      | 12.5%   |
| HGST                | 2        | 2      | 12.5%   |
| Seagate             | 1        | 1      | 6.25%   |
| Samsung Electronics | 1        | 2      | 6.25%   |
| Maxtor              | 1        | 1      | 6.25%   |
| HPE                 | 1        | 2      | 6.25%   |
| Hewlett-Packard     | 1        | 2      | 6.25%   |
| Fujitsu             | 1        | 1      | 6.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 16       | 19     | 76.19%  |
| SSD  | 4        | 6      | 19.05%  |
| NVMe | 1        | 1      | 4.76%   |

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
| Works    | 49       | 123    | 56.98%  |
| Malfunc  | 20       | 26     | 23.26%  |
| Detected | 17       | 32     | 19.77%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 46       | 48.42%  |
| AMD                              | 20       | 21.05%  |
| Samsung Electronics              | 5        | 5.26%   |
| SanDisk                          | 4        | 4.21%   |
| Micron/Crucial Technology        | 4        | 4.21%   |
| Kingston Technology Company      | 4        | 4.21%   |
| Marvell Technology Group         | 3        | 3.16%   |
| Toshiba America Info Systems     | 2        | 2.11%   |
| Silicon Integrated Systems [SiS] | 1        | 1.05%   |
| LSI Logic / Symbios Logic        | 1        | 1.05%   |
| Integrated Technology Express    | 1        | 1.05%   |
| Chelsio Communications           | 1        | 1.05%   |
| Broadcom / LSI                   | 1        | 1.05%   |
| ASMedia Technology               | 1        | 1.05%   |
| Adaptec                          | 1        | 1.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 12       | 9.76%   |
| AMD 400 Series Chipset SATA Controller                                                  | 6        | 4.88%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5        | 4.07%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 5        | 4.07%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5        | 4.07%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5        | 4.07%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                                | 4        | 3.25%   |
| Intel SATA Controller [RAID mode]                                                       | 4        | 3.25%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 4        | 3.25%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 4        | 3.25%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3        | 2.44%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 3        | 2.44%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3        | 2.44%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3        | 2.44%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3        | 2.44%   |
| AMD FCH IDE Controller                                                                  | 3        | 2.44%   |
| AMD 500 Series Chipset SATA Controller                                                  | 3        | 2.44%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 2        | 1.63%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 2        | 1.63%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 1.63%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2        | 1.63%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2        | 1.63%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 2        | 1.63%   |
| AMD FCH SATA Controller D                                                               | 2        | 1.63%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 1        | 0.81%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                                    | 1        | 0.81%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                             | 1        | 0.81%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                    | 1        | 0.81%   |
| Sandisk WD Black SN850X NVMe SSD                                                        | 1        | 0.81%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD                 | 1        | 0.81%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 0.81%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 1        | 0.81%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton2]                                              | 1        | 0.81%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller                                 | 1        | 0.81%   |
| LSI Logic / Symbios Logic MegaRAID SAS 2108 [Liberator]                                 | 1        | 0.81%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1        | 0.81%   |
| Intel Optane SSD 900P Series                                                            | 1        | 0.81%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1        | 0.81%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1        | 0.81%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 1        | 0.81%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 53       | 56.38%  |
| NVMe | 18       | 19.15%  |
| IDE  | 16       | 17.02%  |
| RAID | 5        | 5.32%   |
| SCSI | 2        | 2.13%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 47       | 70.15%  |
| AMD    | 20       | 29.85%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-9400F CPU @ 2.90GHz           | 2        | 2.94%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 2        | 2.94%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 2        | 2.94%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2        | 2.94%   |
| AMD Ryzen 7 5700X 8-Core Processor          | 2        | 2.94%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 2        | 2.94%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 2        | 2.94%   |
| AMD FX-8300 Eight-Core Processor            | 2        | 2.94%   |
| Intel Xeon CPU X3460 @ 2.80GHz              | 1        | 1.47%   |
| Intel Xeon CPU E5-2670 v3 @ 2.30GHz         | 1        | 1.47%   |
| Intel Xeon CPU E5-2643 v3 @ 3.40GHz         | 1        | 1.47%   |
| Intel Xeon CPU E5-2603 v4 @ 1.70GHz         | 1        | 1.47%   |
| Intel Xeon CPU E3-1270 V2 @ 3.50GHz         | 1        | 1.47%   |
| Intel Xeon CPU E3-1226 v3 @ 3.30GHz         | 1        | 1.47%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz    | 1        | 1.47%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz      | 1        | 1.47%   |
| Intel Pentium Dual-Core CPU E6300 @ 2.80GHz | 1        | 1.47%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1        | 1.47%   |
| Intel Pentium D CPU 3.40GHz                 | 1        | 1.47%   |
| Intel Pentium CPU G3240 @ 3.10GHz           | 1        | 1.47%   |
| Intel Pentium 4 CPU 3.00GHz                 | 1        | 1.47%   |
| Intel Core i9-10850K CPU @ 3.60GHz          | 1        | 1.47%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 1        | 1.47%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1        | 1.47%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1        | 1.47%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1        | 1.47%   |
| Intel Core i7-5930K CPU @ 3.50GHz           | 1        | 1.47%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 1        | 1.47%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 1.47%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1        | 1.47%   |
| Intel Core i5-7500T CPU @ 2.70GHz           | 1        | 1.47%   |
| Intel Core i5-4590T CPU @ 2.00GHz           | 1        | 1.47%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 1        | 1.47%   |
| Intel Core i5-4570S CPU @ 2.90GHz           | 1        | 1.47%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1        | 1.47%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 1        | 1.47%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 1        | 1.47%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 1        | 1.47%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 1        | 1.47%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 1        | 1.47%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 15       | 22.06%  |
| Intel Core i7           | 8        | 11.76%  |
| Intel Xeon              | 6        | 8.82%   |
| AMD Ryzen 5             | 5        | 7.35%   |
| AMD Ryzen 7             | 4        | 5.88%   |
| Intel Core 2 Duo        | 3        | 4.41%   |
| Intel Celeron           | 3        | 4.41%   |
| Intel Core i3           | 2        | 2.94%   |
| Intel Core 2 Quad       | 2        | 2.94%   |
| AMD Ryzen 3             | 2        | 2.94%   |
| AMD FX                  | 2        | 2.94%   |
| AMD A10                 | 2        | 2.94%   |
| Intel Pentium Silver    | 1        | 1.47%   |
| Intel Pentium Gold      | 1        | 1.47%   |
| Intel Pentium Dual-Core | 1        | 1.47%   |
| Intel Pentium Dual      | 1        | 1.47%   |
| Intel Pentium D         | 1        | 1.47%   |
| Intel Pentium 4         | 1        | 1.47%   |
| Intel Pentium           | 1        | 1.47%   |
| Intel Core i9           | 1        | 1.47%   |
| Intel Atom              | 1        | 1.47%   |
| AMD Sempron             | 1        | 1.47%   |
| AMD Ryzen Threadripper  | 1        | 1.47%   |
| AMD Ryzen 7 PRO         | 1        | 1.47%   |
| AMD Athlon              | 1        | 1.47%   |
| AMD A4                  | 1        | 1.47%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 24       | 35.82%  |
| 2      | 16       | 23.88%  |
| 6      | 13       | 19.4%   |
| 8      | 7        | 10.45%  |
| 1      | 4        | 5.97%   |
| 24     | 1        | 1.49%   |
| 12     | 1        | 1.49%   |
| 10     | 1        | 1.49%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 66       | 98.51%  |
| 2      | 1        | 1.49%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 35       | 52.24%  |
| 1      | 32       | 47.76%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 66       | 98.51%  |
| 32-bit         | 1        | 1.49%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 14       | 20.59%  |
| 0x306c3    | 5        | 7.35%   |
| 0x206a7    | 5        | 7.35%   |
| 0x906ea    | 4        | 5.88%   |
| 0x1067a    | 4        | 5.88%   |
| 0x306a9    | 3        | 4.41%   |
| 0x0800820d | 3        | 4.41%   |
| 0x906e9    | 2        | 2.94%   |
| 0x106e5    | 2        | 2.94%   |
| 0x0a20120a | 2        | 2.94%   |
| 0x08701021 | 2        | 2.94%   |
| 0xf49      | 1        | 1.47%   |
| 0xa0655    | 1        | 1.47%   |
| 0xa0653    | 1        | 1.47%   |
| 0x906ed    | 1        | 1.47%   |
| 0x706a1    | 1        | 1.47%   |
| 0x6fd      | 1        | 1.47%   |
| 0x686      | 1        | 1.47%   |
| 0x506e3    | 1        | 1.47%   |
| 0x506c9    | 1        | 1.47%   |
| 0x406f1    | 1        | 1.47%   |
| 0x406d8    | 1        | 1.47%   |
| 0x40651    | 1        | 1.47%   |
| 0x306f2    | 1        | 1.47%   |
| 0x10676    | 1        | 1.47%   |
| 0x0a601203 | 1        | 1.47%   |
| 0x08701013 | 1        | 1.47%   |
| 0x0810100b | 1        | 1.47%   |
| 0x08001138 | 1        | 1.47%   |
| 0x08001129 | 1        | 1.47%   |
| 0x06001119 | 1        | 1.47%   |
| 0x06000822 | 1        | 1.47%   |
| 0x03000027 | 1        | 1.47%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Haswell       | 10       | 14.93%  |
| KabyLake      | 8        | 11.94%  |
| SandyBridge   | 5        | 7.46%   |
| Penryn        | 5        | 7.46%   |
| Zen+          | 4        | 5.97%   |
| Zen           | 4        | 5.97%   |
| Piledriver    | 4        | 5.97%   |
| Zen 2         | 3        | 4.48%   |
| Nehalem       | 3        | 4.48%   |
| IvyBridge     | 3        | 4.48%   |
| Zen 3         | 2        | 2.99%   |
| Skylake       | 2        | 2.99%   |
| NetBurst      | 2        | 2.99%   |
| Core          | 2        | 2.99%   |
| CometLake     | 2        | 2.99%   |
| Silvermont    | 1        | 1.49%   |
| P6            | 1        | 1.49%   |
| K8 Hammer     | 1        | 1.49%   |
| K10 Llano     | 1        | 1.49%   |
| Goldmont plus | 1        | 1.49%   |
| Goldmont      | 1        | 1.49%   |
| Broadwell     | 1        | 1.49%   |
| Unknown       | 1        | 1.49%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Nvidia                           | 23       | 33.82%  |
| Intel                            | 22       | 32.35%  |
| AMD                              | 21       | 30.88%  |
| Silicon Integrated Systems [SiS] | 1        | 1.47%   |
| ASPEED Technology                | 1        | 1.47%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 4        | 5.63%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 4        | 5.63%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 3        | 4.23%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 2.82%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 2        | 2.82%   |
| Nvidia G96CGL [Quadro FX 580]                                               | 2        | 2.82%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2        | 2.82%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 2.82%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 2        | 2.82%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 2.82%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 2.82%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2        | 2.82%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter           | 1        | 1.41%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 1.41%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                       | 1        | 1.41%   |
| Nvidia GT218 [GeForce 310]                                                  | 1        | 1.41%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 1.41%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1        | 1.41%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 1.41%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 1.41%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 1.41%   |
| Nvidia GK107 [NVS 510]                                                      | 1        | 1.41%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                           | 1        | 1.41%   |
| Nvidia GF119 [GeForce GT 610]                                               | 1        | 1.41%   |
| Nvidia GF108 [GeForce GT 430]                                               | 1        | 1.41%   |
| Nvidia GA104 [GeForce RTX 3060 Ti]                                          | 1        | 1.41%   |
| Nvidia AD107 [GeForce RTX 4060]                                             | 1        | 1.41%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 1.41%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1        | 1.41%   |
| Intel HD Graphics 630                                                       | 1        | 1.41%   |
| Intel HD Graphics 500                                                       | 1        | 1.41%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 1        | 1.41%   |
| Intel GeminiLake [UHD Graphics 605]                                         | 1        | 1.41%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                   | 1        | 1.41%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 1.41%   |
| ASPEED Technology ASPEED Graphics Family                                    | 1        | 1.41%   |
| AMD Tahiti PRO [Radeon HD 7950/8950 OEM / R9 280]                           | 1        | 1.41%   |
| AMD RV730 PRO [Radeon HD 4650]                                              | 1        | 1.41%   |
| AMD RV350 [Radeon 9550] (Secondary)                                         | 1        | 1.41%   |
| AMD RV350 [Radeon 9550]                                                     | 1        | 1.41%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| 1 x Nvidia  | 23       | 34.33%  |
| 1 x Intel   | 20       | 29.85%  |
| 1 x AMD     | 19       | 28.36%  |
| Other       | 1        | 1.49%   |
| 2 x AMD     | 1        | 1.49%   |
| 1 x SiS     | 1        | 1.49%   |
| Intel + AMD | 1        | 1.49%   |
| 1 x ASPEED  | 1        | 1.49%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 47       | 69.12%  |
| Proprietary | 15       | 22.06%  |
| Unknown     | 6        | 8.82%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 30       | 44.12%  |
| 7.01-8.0   | 9        | 13.24%  |
| 3.01-4.0   | 8        | 11.76%  |
| 0.01-0.5   | 8        | 11.76%  |
| 0.51-1.0   | 5        | 7.35%   |
| 2.01-3.0   | 3        | 4.41%   |
| 1.01-2.0   | 3        | 4.41%   |
| 5.01-6.0   | 2        | 2.94%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 13       | 18.57%  |
| Hewlett-Packard      | 8        | 11.43%  |
| Philips              | 6        | 8.57%   |
| Ancor Communications | 6        | 8.57%   |
| Goldstar             | 5        | 7.14%   |
| Acer                 | 5        | 7.14%   |
| Dell                 | 4        | 5.71%   |
| AOC                  | 4        | 5.71%   |
| Unknown              | 3        | 4.29%   |
| Lenovo               | 3        | 4.29%   |
| Iiyama               | 3        | 4.29%   |
| ___                  | 1        | 1.43%   |
| ViewSonic            | 1        | 1.43%   |
| Toshiba              | 1        | 1.43%   |
| MSI                  | 1        | 1.43%   |
| HJW                  | 1        | 1.43%   |
| eMachines            | 1        | 1.43%   |
| Eizo                 | 1        | 1.43%   |
| CVT                  | 1        | 1.43%   |
| CHI                  | 1        | 1.43%   |
| BenQ                 | 1        | 1.43%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM0091 1600x1200 432x324mm 21.3-inch   | 2        | 2.7%    |
| Philips 17S PHL0877 1280x1024 337x270mm 17.0-inch                      | 2        | 2.7%    |
| Hewlett-Packard 22m HPN3575 1920x1080 476x268mm 21.5-inch              | 2        | 2.7%    |
| Acer AL1716A ACRAD46 1280x1024 338x270mm 17.0-inch                     | 2        | 2.7%    |
| ___ LCDTV16 ___9000 1360x768                                           | 1        | 1.35%   |
| ViewSonic VA2261 Series VSC0F30 1920x1080 477x268mm 21.5-inch          | 1        | 1.35%   |
| Unknown LCD TV 9000 1360x768 1600x900mm 72.3-inch                      | 1        | 1.35%   |
| Unknown LCD Monitor hp L1702 1280x1024                                 | 1        | 1.35%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch              | 1        | 1.35%   |
| Toshiba TV TSB0209 1920x1080 1594x900mm 72.1-inch                      | 1        | 1.35%   |
| Samsung Electronics T24B301 SAM098E 1920x1080 521x293mm 23.5-inch      | 1        | 1.35%   |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                       | 1        | 1.35%   |
| Samsung Electronics SyncMaster SAM0473 2048x1152 510x287mm 23.0-inch   | 1        | 1.35%   |
| Samsung Electronics SyncMaster SAM0226 1440x900 410x257mm 19.1-inch    | 1        | 1.35%   |
| Samsung Electronics SyncMaster SAM0029 2048x1536 312x234mm 15.4-inch   | 1        | 1.35%   |
| Samsung Electronics S24B300 SAM08B3 1920x1080 520x290mm 23.4-inch      | 1        | 1.35%   |
| Samsung Electronics S/T 77/76BDF STN0007 1280x1024 312x234mm 15.4-inch | 1        | 1.35%   |
| Samsung Electronics LCD Monitor SyncMaster 1280x1024                   | 1        | 1.35%   |
| Samsung Electronics LCD Monitor SyncMaster                             | 1        | 1.35%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 700x390mm 31.5-inch  | 1        | 1.35%   |
| Samsung Electronics LCD Monitor SA300/350/360                          | 1        | 1.35%   |
| Samsung Electronics LCD Monitor S24D340                                | 1        | 1.35%   |
| Samsung Electronics LCD Monitor C27F390 5760x1080                      | 1        | 1.35%   |
| Samsung Electronics C27F398 SAM0D45 1920x1080 598x336mm 27.0-inch      | 1        | 1.35%   |
| Philips PHL 243S7 PHL090F 1920x1080 527x296mm 23.8-inch                | 1        | 1.35%   |
| Philips PHL 241P6Q PHL08DB 1920x1080 527x296mm 23.8-inch               | 1        | 1.35%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch                | 1        | 1.35%   |
| Philips 190B PHL086C 1280x1024 376x301mm 19.0-inch                     | 1        | 1.35%   |
| MSI Optix MAG27CQ MSI1462 2560x1440 597x336mm 27.0-inch                | 1        | 1.35%   |
| Lenovo LI2215sD LEN65CC 1920x1080 476x267mm 21.5-inch                  | 1        | 1.35%   |
| Lenovo LCD Monitor LEN40A0 1366x768 309x174mm 14.0-inch                | 1        | 1.35%   |
| Lenovo L24e-30 LEN66BC 1920x1080 527x296mm 23.8-inch                   | 1        | 1.35%   |
| Iiyama PLX2483H IVM6114 1920x1080 530x300mm 24.0-inch                  | 1        | 1.35%   |
| Iiyama PLB2712HDS IVM6602 1920x1080 598x336mm 27.0-inch                | 1        | 1.35%   |
| Iiyama PL2482H IVM610D 1920x1080 521x293mm 23.5-inch                   | 1        | 1.35%   |
| HJW HDMI TO USB HJW0001 1920x1080 700x390mm 31.5-inch                  | 1        | 1.35%   |
| Hewlett-Packard LA2206 HWP2947 1920x1080 477x268mm 21.5-inch           | 1        | 1.35%   |
| Hewlett-Packard LA1951 HWP285A 1280x1024 380x300mm 19.1-inch           | 1        | 1.35%   |
| Hewlett-Packard L2245w HWP26FC 1680x1050 473x296mm 22.0-inch           | 1        | 1.35%   |
| Hewlett-Packard ENVY 34c HWP3204 3440x1440 797x333mm 34.0-inch         | 1        | 1.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 27       | 40.3%   |
| 1280x1024 (SXGA)   | 9        | 13.43%  |
| 1440x900 (WXGA+)   | 5        | 7.46%   |
| 3840x2160 (4K)     | 4        | 5.97%   |
| 1920x1200 (WUXGA)  | 4        | 5.97%   |
| 1366x768 (WXGA)    | 3        | 4.48%   |
| 3440x1440          | 2        | 2.99%   |
| 2560x1440 (QHD)    | 2        | 2.99%   |
| 1600x1200          | 2        | 2.99%   |
| Unknown            | 2        | 2.99%   |
| 5760x1080          | 1        | 1.49%   |
| 2288x1287          | 1        | 1.49%   |
| 2048x1152          | 1        | 1.49%   |
| 1680x1050 (WSXGA+) | 1        | 1.49%   |
| 1600x900 (HD+)     | 1        | 1.49%   |
| 1360x768           | 1        | 1.49%   |
| 1024x768 (XGA)     | 1        | 1.49%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 13       | 19.4%   |
| 24      | 8        | 11.94%  |
| Unknown | 8        | 11.94%  |
| 23      | 7        | 10.45%  |
| 17      | 5        | 7.46%   |
| 27      | 4        | 5.97%   |
| 19      | 4        | 5.97%   |
| 18      | 3        | 4.48%   |
| 72      | 2        | 2.99%   |
| 34      | 2        | 2.99%   |
| 31      | 2        | 2.99%   |
| 15      | 2        | 2.99%   |
| 142     | 1        | 1.49%   |
| 54      | 1        | 1.49%   |
| 40      | 1        | 1.49%   |
| 26      | 1        | 1.49%   |
| 25      | 1        | 1.49%   |
| 22      | 1        | 1.49%   |
| 14      | 1        | 1.49%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 19       | 30.65%  |
| 401-500        | 17       | 27.42%  |
| Unknown        | 8        | 12.9%   |
| 301-350        | 7        | 11.29%  |
| 701-800        | 2        | 3.23%   |
| 601-700        | 2        | 3.23%   |
| 351-400        | 2        | 3.23%   |
| 1501-2000      | 2        | 3.23%   |
| More than 2000 | 1        | 1.61%   |
| 801-900        | 1        | 1.61%   |
| 1001-1500      | 1        | 1.61%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 35       | 55.56%  |
| 16/10   | 8        | 12.7%   |
| 5/4     | 6        | 9.52%   |
| Unknown | 6        | 9.52%   |
| 4/3     | 4        | 6.35%   |
| 21/9    | 2        | 3.17%   |
| 6/5     | 1        | 1.59%   |
| 1.00    | 1        | 1.59%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 22       | 33.85%  |
| Unknown        | 8        | 12.31%  |
| 151-200        | 7        | 10.77%  |
| 141-150        | 7        | 10.77%  |
| 251-300        | 5        | 7.69%   |
| More than 1000 | 4        | 6.15%   |
| 351-500        | 4        | 6.15%   |
| 301-350        | 4        | 6.15%   |
| 111-120        | 2        | 3.08%   |
| 81-90          | 1        | 1.54%   |
| 501-1000       | 1        | 1.54%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 34       | 53.13%  |
| 101-120 | 18       | 28.13%  |
| Unknown | 8        | 12.5%   |
| 1-50    | 4        | 6.25%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 53       | 79.1%   |
| 2     | 8        | 11.94%  |
| 3     | 3        | 4.48%   |
| 0     | 3        | 4.48%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 41       | 47.67%  |
| Intel                            | 27       | 31.4%   |
| Qualcomm Atheros                 | 4        | 4.65%   |
| NetGear                          | 2        | 2.33%   |
| Marvell Technology Group         | 2        | 2.33%   |
| Broadcom                         | 2        | 2.33%   |
| TP-Link                          | 1        | 1.16%   |
| Solarflare Communications        | 1        | 1.16%   |
| Silicon Integrated Systems [SiS] | 1        | 1.16%   |
| Ralink Technology                | 1        | 1.16%   |
| MediaTek                         | 1        | 1.16%   |
| JMicron Technology               | 1        | 1.16%   |
| D-Link System                    | 1        | 1.16%   |
| Chelsio Communications           | 1        | 1.16%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 33       | 35.48%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 3.23%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 3.23%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 3.23%   |
| NetGear WNA3100M(v1) Wireless-N 300 [Realtek RTL8192CU]           | 2        | 2.15%   |
| Intel I210 Gigabit Network Connection                             | 2        | 2.15%   |
| Intel Ethernet Controller I225-V                                  | 2        | 2.15%   |
| Intel Ethernet Connection (7) I219-LM                             | 2        | 2.15%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1        | 1.08%   |
| Solarflare SFC9020 10G Ethernet Controller                        | 1        | 1.08%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1        | 1.08%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1        | 1.08%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 1        | 1.08%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1        | 1.08%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1        | 1.08%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1        | 1.08%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 1.08%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller         | 1        | 1.08%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 1.08%   |
| Ralink MT7601U Wireless Adapter                                   | 1        | 1.08%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 1.08%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1        | 1.08%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1        | 1.08%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter        | 1        | 1.08%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 1        | 1.08%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1        | 1.08%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 1.08%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1        | 1.08%   |
| Intel Wireless 7260                                               | 1        | 1.08%   |
| Intel Wi-Fi 6 AX200                                               | 1        | 1.08%   |
| Intel I350 Gigabit Network Connection                             | 1        | 1.08%   |
| Intel I211 Gigabit Network Connection                             | 1        | 1.08%   |
| Intel Ethernet Connection I354 2.5 GbE Backplane                  | 1        | 1.08%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.08%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 1.08%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 1.08%   |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 1.08%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 1.08%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 1.08%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1        | 1.08%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 6        | 35.29%  |
| Qualcomm Atheros      | 3        | 17.65%  |
| Intel                 | 3        | 17.65%  |
| NetGear               | 2        | 11.76%  |
| TP-Link               | 1        | 5.88%   |
| Ralink Technology     | 1        | 5.88%   |
| MediaTek              | 1        | 5.88%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| NetGear WNA3100M(v1) Wireless-N 300 [Realtek RTL8192CU]       | 2        | 11.76%  |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                  | 1        | 5.88%   |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 1        | 5.88%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter       | 1        | 5.88%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter         | 1        | 5.88%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 1        | 5.88%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                    | 1        | 5.88%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller     | 1        | 5.88%   |
| Ralink MT7601U Wireless Adapter                               | 1        | 5.88%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 1        | 5.88%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter              | 1        | 5.88%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter    | 1        | 5.88%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 1        | 5.88%   |
| Intel Wireless 7260                                           | 1        | 5.88%   |
| Intel Wi-Fi 6 AX200                                           | 1        | 5.88%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 1        | 5.88%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 38       | 52.05%  |
| Intel                            | 25       | 34.25%  |
| Marvell Technology Group         | 2        | 2.74%   |
| Broadcom                         | 2        | 2.74%   |
| Solarflare Communications        | 1        | 1.37%   |
| Silicon Integrated Systems [SiS] | 1        | 1.37%   |
| Qualcomm Atheros                 | 1        | 1.37%   |
| JMicron Technology               | 1        | 1.37%   |
| D-Link System                    | 1        | 1.37%   |
| Chelsio Communications           | 1        | 1.37%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 33       | 43.42%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 3.95%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 3.95%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 3.95%   |
| Intel I210 Gigabit Network Connection                             | 2        | 2.63%   |
| Intel Ethernet Controller I225-V                                  | 2        | 2.63%   |
| Intel Ethernet Connection (7) I219-LM                             | 2        | 2.63%   |
| Solarflare SFC9020 10G Ethernet Controller                        | 1        | 1.32%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1        | 1.32%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 1.32%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 1.32%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 1.32%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1        | 1.32%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 1.32%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1        | 1.32%   |
| Intel I350 Gigabit Network Connection                             | 1        | 1.32%   |
| Intel I211 Gigabit Network Connection                             | 1        | 1.32%   |
| Intel Ethernet Connection I354 2.5 GbE Backplane                  | 1        | 1.32%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.32%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 1.32%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 1.32%   |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 1.32%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 1.32%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 1.32%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 1.32%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 1.32%   |
| Intel 82576 Gigabit Network Connection                            | 1        | 1.32%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 1.32%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)        | 1        | 1.32%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 1.32%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1        | 1.32%   |
| Chelsio T420-SO Unified Wire Ethernet Controller                  | 1        | 1.32%   |
| Chelsio T4 Generic function                                       | 1        | 1.32%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1        | 1.32%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1        | 1.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 66       | 80.49%  |
| WiFi     | 16       | 19.51%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 56       | 84.85%  |
| WiFi     | 10       | 15.15%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 48       | 70.59%  |
| 2     | 13       | 19.12%  |
| 3     | 3        | 4.41%   |
| 7     | 1        | 1.47%   |
| 5     | 1        | 1.47%   |
| 4     | 1        | 1.47%   |
| 0     | 1        | 1.47%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 58       | 86.57%  |
| Yes  | 9        | 13.43%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| ASUSTek Computer                | 4        | 40%     |
| Intel                           | 3        | 30%     |
| Qualcomm Atheros Communications | 2        | 20%     |
| MediaTek                        | 1        | 10%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| ASUS Bluetooth Device              | 2        | 20%     |
| Qualcomm Atheros  Bluetooth Device | 1        | 10%     |
| Qualcomm Atheros AR3011 Bluetooth  | 1        | 10%     |
| MediaTek Wireless_Device           | 1        | 10%     |
| Intel Wireless-AC 3168 Bluetooth   | 1        | 10%     |
| Intel Bluetooth wireless interface | 1        | 10%     |
| Intel AX200 Bluetooth              | 1        | 10%     |
| ASUS Qualcomm Bluetooth 4.1        | 1        | 10%     |
| ASUS Broadcom BCM20702A0 Bluetooth | 1        | 10%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 41       | 37.61%  |
| AMD                              | 24       | 22.02%  |
| Nvidia                           | 21       | 19.27%  |
| Creative Labs                    | 6        | 5.5%    |
| Texas Instruments                | 2        | 1.83%   |
| Plantronics                      | 2        | 1.83%   |
| TEAC                             | 1        | 0.92%   |
| Silicon Integrated Systems [SiS] | 1        | 0.92%   |
| M-Audio                          | 1        | 0.92%   |
| Logitech                         | 1        | 0.92%   |
| KORG                             | 1        | 0.92%   |
| Giga-Byte Technology             | 1        | 0.92%   |
| Generalplus Technology           | 1        | 0.92%   |
| Focusrite-Novation               | 1        | 0.92%   |
| Elite Silicon                    | 1        | 0.92%   |
| DCMT Technology                  | 1        | 0.92%   |
| Cirrus Logic                     | 1        | 0.92%   |
| Avance Logic                     | 1        | 0.92%   |
| ASUSTek Computer                 | 1        | 0.92%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6        | 4.69%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5        | 3.91%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5        | 3.91%   |
| AMD Starship/Matisse HD Audio Controller                                   | 5        | 3.91%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 5        | 3.91%   |
| Nvidia GP106 High Definition Audio Controller                              | 4        | 3.13%   |
| Intel Cannon Lake PCH cAVS                                                 | 4        | 3.13%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4        | 3.13%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4        | 3.13%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 4        | 3.13%   |
| Nvidia GP104 High Definition Audio Controller                              | 3        | 2.34%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 3        | 2.34%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3        | 2.34%   |
| Intel 200 Series PCH HD Audio                                              | 3        | 2.34%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]  | 3        | 2.34%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 3        | 2.34%   |
| AMD FCH Azalia Controller                                                  | 3        | 2.34%   |
| AMD Family 17h/19h HD Audio Controller                                     | 3        | 2.34%   |
| Texas Instruments PCM2902 Audio Codec                                      | 2        | 1.56%   |
| Plantronics HD1                                                            | 2        | 1.56%   |
| Nvidia High Definition Audio Controller                                    | 2        | 1.56%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 1.56%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2        | 1.56%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2        | 1.56%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 2        | 1.56%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2        | 1.56%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2        | 1.56%   |
| TEAC US-1800                                                               | 1        | 0.78%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 1        | 0.78%   |
| Nvidia TU116 High Definition Audio Controller                              | 1        | 0.78%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 0.78%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1        | 0.78%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1        | 0.78%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1        | 0.78%   |
| Nvidia GF108 High Definition Audio Controller                              | 1        | 0.78%   |
| Nvidia GA104 High Definition Audio Controller                              | 1        | 0.78%   |
| Nvidia Audio device                                                        | 1        | 0.78%   |
| M-Audio MIDISPORT 4x4 Anniv                                                | 1        | 0.78%   |
| M-Audio M-Audio 1x1                                                        | 1        | 0.78%   |
| Logitech H390 headset with microphone                                      | 1        | 0.78%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 14       | 19.18%  |
| Corsair             | 14       | 19.18%  |
| Kingston            | 13       | 17.81%  |
| SK hynix            | 6        | 8.22%   |
| Micron Technology   | 5        | 6.85%   |
| G.Skill             | 5        | 6.85%   |
| Samsung Electronics | 4        | 5.48%   |
| Nanya Technology    | 2        | 2.74%   |
| Crucial             | 2        | 2.74%   |
| Unknown (ABCD)      | 1        | 1.37%   |
| Transcend           | 1        | 1.37%   |
| Team                | 1        | 1.37%   |
| Ramaxel Technology  | 1        | 1.37%   |
| GOODRAM             | 1        | 1.37%   |
| Avant               | 1        | 1.37%   |
| A-DATA Technology   | 1        | 1.37%   |
| Unknown             | 1        | 1.37%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s         | 3        | 3.7%    |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s          | 2        | 2.47%   |
| Corsair RAM CMK32GX4M4A2666C16 8GB DIMM DDR4 3000MT/s          | 2        | 2.47%   |
| Unknown RAM SM3S320SD0488CABC 8192MB SODIMM DDR3 1600MT/s      | 1        | 1.23%   |
| Unknown RAM Module 8192MB DIMM DDR3 800MT/s                    | 1        | 1.23%   |
| Unknown RAM Module 64MB DIMM DRAM 100MT/s                      | 1        | 1.23%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 1        | 1.23%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                 | 1        | 1.23%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                   | 1        | 1.23%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                           | 1        | 1.23%   |
| Unknown RAM Module 256MB DIMM DRAM 100MT/s                     | 1        | 1.23%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                  | 1        | 1.23%   |
| Unknown RAM Module 2048MB DIMM SDRAM 667MT/s                   | 1        | 1.23%   |
| Unknown RAM Module 2048MB DIMM SDRAM                           | 1        | 1.23%   |
| Unknown RAM Module 128MB DIMM DRAM 100MT/s                     | 1        | 1.23%   |
| Unknown RAM Module 1024MB DIMM DDR 400MT/s                     | 1        | 1.23%   |
| Unknown RAM Module 1024MB DIMM DDR                             | 1        | 1.23%   |
| Unknown RAM 3600 C17 Series 8GB DIMM DDR4 3200MT/s             | 1        | 1.23%   |
| Unknown RAM 3000 C16 Series 8192MB DIMM DDR4 2133MT/s          | 1        | 1.23%   |
| Unknown RAM 1600 CL9 Series 8192MB DIMM DDR3 1066MT/s          | 1        | 1.23%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 1        | 1.23%   |
| Transcend RAM JM1333KLN-4G 4GB DIMM DDR3 1600MT/s              | 1        | 1.23%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 2933MT/s             | 1        | 1.23%   |
| SK hynix RAM Module 4GB DIMM DDR3 1333MT/s                     | 1        | 1.23%   |
| SK hynix RAM HMT451U7BFR8A-PB 4GB DIMM 1600MT/s                | 1        | 1.23%   |
| SK hynix RAM HMT451U6AFR8A-PB 4GB DIMM DDR3 1600MT/s           | 1        | 1.23%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s           | 1        | 1.23%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s           | 1        | 1.23%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM 1600MT/s                | 1        | 1.23%   |
| SK hynix RAM HMT325U6CFR8C-PB 8GB DIMM DDR3 1866MT/s           | 1        | 1.23%   |
| SK hynix RAM HMA81GU6JJR8N-VK 8GB DIMM DDR4 2667MT/s           | 1        | 1.23%   |
| Samsung RAM Module 2GB DIMM DDR3 1333MT/s                      | 1        | 1.23%   |
| Samsung RAM M393A4K40BB0-CPB 32GB DIMM DDR4 2133MT/s           | 1        | 1.23%   |
| Samsung RAM M378B5273DH0-CH9 4096MB DIMM DDR2 2133MT/s         | 1        | 1.23%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 2133MT/s            | 1        | 1.23%   |
| Ramaxel RAM RMUA5180ME78HBF-2666 16GB DIMM DDR4 2667MT/s       | 1        | 1.23%   |
| Nanya RAM Module 2GB DIMM DDR3 1333MT/s                        | 1        | 1.23%   |
| Nanya RAM M2X4G64CB8HG5N-DG 4GB DIMM DDR3 1867MT/s             | 1        | 1.23%   |
| Micron RAM Module 2GB DIMM DDR3 1333MT/s                       | 1        | 1.23%   |
| Micron RAM DVM64453C DATARAM 8192MB DIMM DDR3 1600MT/s         | 1        | 1.23%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 29       | 47.54%  |
| DDR3    | 21       | 34.43%  |
| SDRAM   | 3        | 4.92%   |
| DDR     | 2        | 3.28%   |
| Unknown | 2        | 3.28%   |
| LPDDR4  | 1        | 1.64%   |
| DRAM    | 1        | 1.64%   |
| DDR5    | 1        | 1.64%   |
| DDR2    | 1        | 1.64%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 55       | 91.67%  |
| SODIMM | 5        | 8.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 23       | 34.33%  |
| 4096  | 17       | 25.37%  |
| 16384 | 13       | 19.4%   |
| 2048  | 5        | 7.46%   |
| 32768 | 4        | 5.97%   |
| 1024  | 2        | 2.99%   |
| 256   | 1        | 1.49%   |
| 128   | 1        | 1.49%   |
| 64    | 1        | 1.49%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 13       | 18.84%  |
| 3600    | 6        | 8.7%    |
| 2667    | 6        | 8.7%    |
| 2400    | 6        | 8.7%    |
| 2133    | 6        | 8.7%    |
| 1333    | 5        | 7.25%   |
| 3400    | 4        | 5.8%    |
| 1800    | 3        | 4.35%   |
| 3200    | 2        | 2.9%    |
| 3000    | 2        | 2.9%    |
| 1867    | 2        | 2.9%    |
| 667     | 2        | 2.9%    |
| Unknown | 2        | 2.9%    |
| 4800    | 1        | 1.45%   |
| 3666    | 1        | 1.45%   |
| 3534    | 1        | 1.45%   |
| 2933    | 1        | 1.45%   |
| 2666    | 1        | 1.45%   |
| 1866    | 1        | 1.45%   |
| 1632    | 1        | 1.45%   |
| 800     | 1        | 1.45%   |
| 400     | 1        | 1.45%   |
| 100     | 1        | 1.45%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Hewlett-Packard        | 2        | 50%     |
| Custom Engineering SPA | 1        | 25%     |
| Brother Industries     | 1        | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| HP ENVY 5000 series             | 1        | 25%     |
| HP DeskJet F4200 series         | 1        | 25%     |
| Custom Engineering SPA KUBE USB | 1        | 25%     |
| Brother HL-L2375DW series       | 1        | 25%     |

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
| Logitech                    | 5        | 31.25%  |
| Cubeternet                  | 2        | 12.5%   |
| Z-Star Microelectronics     | 1        | 6.25%   |
| Softkinetic                 | 1        | 6.25%   |
| Realtek Semiconductor       | 1        | 6.25%   |
| Microsoft                   | 1        | 6.25%   |
| Microdia                    | 1        | 6.25%   |
| MacroSilicon                | 1        | 6.25%   |
| KYE Systems (Mouse Systems) | 1        | 6.25%   |
| Hauppauge                   | 1        | 6.25%   |
| GEMBIRD                     | 1        | 6.25%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                     | Desktops | Percent |
|-------------------------------------------|----------|---------|
| Logitech Webcam C270                      | 3        | 18.75%  |
| Cubeternet GL-UPC822 UVC WebCam           | 2        | 12.5%   |
| Z-Star A4 TECH USB2.0 PC Camera E         | 1        | 6.25%   |
| Softkinetic DepthSense 325                | 1        | 6.25%   |
| Realtek HD 720P Webcam                    | 1        | 6.25%   |
| Microsoft LifeCam Studio                  | 1        | 6.25%   |
| Microdia Camera                           | 1        | 6.25%   |
| MacroSilicon USB3. 0 capture              | 1        | 6.25%   |
| Logitech C920 PRO HD Webcam               | 1        | 6.25%   |
| Logitech BRIO Ultra HD Webcam             | 1        | 6.25%   |
| KYE Systems (Mouse Systems) Genius Webcam | 1        | 6.25%   |
| Hauppauge HD PVR Pro 60                   | 1        | 6.25%   |
| GEMBIRD USB2.0 PC CAMERA                  | 1        | 6.25%   |

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
| 0     | 53       | 77.94%  |
| 1     | 13       | 19.12%  |
| 2     | 2        | 2.94%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 7        | 41.18%  |
| Unassigned class         | 4        | 23.53%  |
| Net/wireless             | 2        | 11.76%  |
| Communication controller | 2        | 11.76%  |
| Net/ethernet             | 1        | 5.88%   |
| Firewire controller      | 1        | 5.88%   |

