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

Total: 78

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Google        | Panther                     | [666794d603](https://linux-hardware.org/?probe=666794d603) | Apr 26, 2021 |
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
| Devuan 4                | 25       | 40.32%  |
| Devuan 3                | 14       | 22.58%  |
| Devuan 5                | 8        | 12.9%   |
| Devuan Testing/unstable | 7        | 11.29%  |
| Devuan 2.1              | 6        | 9.68%   |
| Devuan 6                | 1        | 1.61%   |
| Devuan 1.0.0            | 1        | 1.61%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Devuan | 59       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Desktops | Percent |
|-----------------------|----------|---------|
| 5.10.0-9-amd64        | 6        | 9.09%   |
| 5.10.0-21-amd64       | 4        | 6.06%   |
| 4.19.0-14-amd64       | 4        | 6.06%   |
| 4.19.0-16-amd64       | 3        | 4.55%   |
| 5.10.0-8-amd64        | 2        | 3.03%   |
| 5.10.0-6-amd64        | 2        | 3.03%   |
| 5.10.0-23-amd64       | 2        | 3.03%   |
| 5.10.0-19-amd64       | 2        | 3.03%   |
| 4.19.0-9-amd64        | 2        | 3.03%   |
| 4.19.0-13-amd64       | 2        | 3.03%   |
| 4.19.0-10-amd64       | 2        | 3.03%   |
| 6.3.0-2-amd64         | 1        | 1.52%   |
| 6.2.12                | 1        | 1.52%   |
| 6.1.7                 | 1        | 1.52%   |
| 6.1.0-6-amd64         | 1        | 1.52%   |
| 6.1.0-0.deb11.5-amd64 | 1        | 1.52%   |
| 6.0.0-5-amd64         | 1        | 1.52%   |
| 5.9.0-1-amd64         | 1        | 1.52%   |
| 5.8.0-3-amd64         | 1        | 1.52%   |
| 5.7.0-1-amd64         | 1        | 1.52%   |
| 5.7.0-0.bpo.2-amd64   | 1        | 1.52%   |
| 5.18.14-devuan        | 1        | 1.52%   |
| 5.18.11-gnu           | 1        | 1.52%   |
| 5.18.0-1-amd64        | 1        | 1.52%   |
| 5.16.0-1-amd64        | 1        | 1.52%   |
| 5.15.0-2-amd64        | 1        | 1.52%   |
| 5.15.0-0.bpo.2-amd64  | 1        | 1.52%   |
| 5.14.0-kali2-amd64    | 1        | 1.52%   |
| 5.10.0-5-amd64        | 1        | 1.52%   |
| 5.10.0-22-amd64       | 1        | 1.52%   |
| 5.10.0-2-amd64        | 1        | 1.52%   |
| 5.10.0-18-amd64       | 1        | 1.52%   |
| 5.10.0-16-amd64       | 1        | 1.52%   |
| 5.10.0-15-amd64       | 1        | 1.52%   |
| 5.10.0-11-amd64       | 1        | 1.52%   |
| 5.10.0-10-amd64       | 1        | 1.52%   |
| 4.9.0-15-amd64        | 1        | 1.52%   |
| 4.9.0-14-686-pae      | 1        | 1.52%   |
| 4.9.0-14-686          | 1        | 1.52%   |
| 4.9.0-11-686-pae      | 1        | 1.52%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.10.0   | 23       | 37.7%   |
| 4.19.0   | 15       | 24.59%  |
| 4.9.0    | 4        | 6.56%   |
| 6.1.0    | 2        | 3.28%   |
| 5.7.0    | 2        | 3.28%   |
| 5.15.0   | 2        | 3.28%   |
| 6.3.0    | 1        | 1.64%   |
| 6.2.12   | 1        | 1.64%   |
| 6.1.7    | 1        | 1.64%   |
| 6.0.0    | 1        | 1.64%   |
| 5.9.0    | 1        | 1.64%   |
| 5.8.0    | 1        | 1.64%   |
| 5.18.14  | 1        | 1.64%   |
| 5.18.11  | 1        | 1.64%   |
| 5.18.0   | 1        | 1.64%   |
| 5.16.0   | 1        | 1.64%   |
| 5.14.0   | 1        | 1.64%   |
| 4.19.112 | 1        | 1.64%   |
| 4.18.0   | 1        | 1.64%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 23       | 37.7%   |
| 4.19    | 16       | 26.23%  |
| 4.9     | 4        | 6.56%   |
| 6.1     | 3        | 4.92%   |
| 5.18    | 3        | 4.92%   |
| 5.7     | 2        | 3.28%   |
| 5.15    | 2        | 3.28%   |
| 6.3     | 1        | 1.64%   |
| 6.2     | 1        | 1.64%   |
| 6.0     | 1        | 1.64%   |
| 5.9     | 1        | 1.64%   |
| 5.8     | 1        | 1.64%   |
| 5.16    | 1        | 1.64%   |
| 5.14    | 1        | 1.64%   |
| 4.18    | 1        | 1.64%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 56       | 94.92%  |
| i686   | 3        | 5.08%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| XFCE       | 26       | 41.94%  |
| Unknown    | 13       | 20.97%  |
| MATE       | 7        | 11.29%  |
| KDE5       | 6        | 9.68%   |
| LXDE       | 3        | 4.84%   |
| Cinnamon   | 3        | 4.84%   |
| X-Cinnamon | 1        | 1.61%   |
| i3         | 1        | 1.61%   |
| GNOME      | 1        | 1.61%   |
| awesome    | 1        | 1.61%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 50       | 83.33%  |
| Tty     | 7        | 11.67%  |
| Unknown | 3        | 5%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SLiM    | 27       | 45.76%  |
| Unknown | 13       | 22.03%  |
| LightDM | 12       | 20.34%  |
| SDDM    | 4        | 6.78%   |
| NODM    | 2        | 3.39%   |
| XDM     | 1        | 1.69%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 20       | 33.33%  |
| en_GB   | 6        | 10%     |
| fr_FR   | 5        | 8.33%   |
| Unknown | 5        | 8.33%   |
| ru_RU   | 4        | 6.67%   |
| C       | 4        | 6.67%   |
| sk_SK   | 3        | 5%      |
| en_AU   | 3        | 5%      |
| pt_BR   | 2        | 3.33%   |
| fr_BE   | 2        | 3.33%   |
| en_NZ   | 2        | 3.33%   |
| de_DE   | 2        | 3.33%   |
| pl_PL   | 1        | 1.67%   |
| en_CA   | 1        | 1.67%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 35       | 59.32%  |
| EFI  | 24       | 40.68%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 52       | 88.14%  |
| Overlay | 2        | 3.39%   |
| Btrfs   | 2        | 3.39%   |
| Xfs     | 1        | 1.69%   |
| Ext3    | 1        | 1.69%   |
| Unknown | 1        | 1.69%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 35       | 56.45%  |
| MBR     | 24       | 38.71%  |
| Unknown | 3        | 4.84%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 39       | 63.93%  |
| Yes       | 22       | 36.07%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 42       | 71.19%  |
| Yes       | 17       | 28.81%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 13       | 22.03%  |
| ASUSTek Computer    | 12       | 20.34%  |
| MSI                 | 9        | 15.25%  |
| Hewlett-Packard     | 5        | 8.47%   |
| Dell                | 5        | 8.47%   |
| ASRock              | 4        | 6.78%   |
| Lenovo              | 2        | 3.39%   |
| Intel               | 2        | 3.39%   |
| Supermicro          | 1        | 1.69%   |
| Sun Microsystems    | 1        | 1.69%   |
| Online Labs         | 1        | 1.69%   |
| LORD ELECTRONICS    | 1        | 1.69%   |
| Google              | 1        | 1.69%   |
| AMI                 | 1        | 1.69%   |
| Acer                | 1        | 1.69%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Supermicro SYS-1018GR-T                           | 1        | 1.69%   |
| Sun Microsystems Ultra 24                         | 1        | 1.69%   |
| Online Labs SR                                    | 1        | 1.69%   |
| MSI MS-7B86                                       | 1        | 1.69%   |
| MSI MS-7B84                                       | 1        | 1.69%   |
| MSI MS-7B53                                       | 1        | 1.69%   |
| MSI MS-7A38                                       | 1        | 1.69%   |
| MSI MS-7A36                                       | 1        | 1.69%   |
| MSI MS-7A34                                       | 1        | 1.69%   |
| MSI MS-7885                                       | 1        | 1.69%   |
| MSI MS-7678                                       | 1        | 1.69%   |
| MSI MS-7673                                       | 1        | 1.69%   |
| LORD ELECTRONICS LORD G4x 775 ICH7 8712 As Design | 1        | 1.69%   |
| Lenovo ThinkStation P330 30C5S1LQ00               | 1        | 1.69%   |
| Lenovo ThinkStation E20 4220CTO                   | 1        | 1.69%   |
| Intel D815EEA AAA45884-401                        | 1        | 1.69%   |
| Intel AHV                                         | 1        | 1.69%   |
| HP Z640 Workstation                               | 1        | 1.69%   |
| HP Z220 SFF Workstation                           | 1        | 1.69%   |
| HP ProDesk 600 G1 SFF                             | 1        | 1.69%   |
| HP EliteDesk 800 G1 DM                            | 1        | 1.69%   |
| HP Compaq 8200 Elite SFF PC                       | 1        | 1.69%   |
| Google Panther                                    | 1        | 1.69%   |
| Gigabyte Z390 GAMING SLI                          | 1        | 1.69%   |
| Gigabyte P55A-UD3                                 | 1        | 1.69%   |
| Gigabyte MZGLKBP-00                               | 1        | 1.69%   |
| Gigabyte H81M-S2H                                 | 1        | 1.69%   |
| Gigabyte H310M S2H 2.0                            | 1        | 1.69%   |
| Gigabyte H170-HD3-CF                              | 1        | 1.69%   |
| Gigabyte H170-HD3                                 | 1        | 1.69%   |
| Gigabyte GA-G41M-ES2L                             | 1        | 1.69%   |
| Gigabyte B75M-D3V                                 | 1        | 1.69%   |
| Gigabyte B650I AORUS ULTRA                        | 1        | 1.69%   |
| Gigabyte B550I AORUS PRO AX                       | 1        | 1.69%   |
| Gigabyte B450 AORUS ELITE                         | 1        | 1.69%   |
| Gigabyte 970A-DS3P                                | 1        | 1.69%   |
| Dell Vostro 430                                   | 1        | 1.69%   |
| Dell OptiPlex 9020                                | 1        | 1.69%   |
| Dell OptiPlex 7060                                | 1        | 1.69%   |
| Dell OptiPlex 7050                                | 1        | 1.69%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| Dell OptiPlex           | 4        | 6.78%   |
| ASUS PRIME              | 4        | 6.78%   |
| Lenovo ThinkStation     | 2        | 3.39%   |
| ASUS ROG                | 2        | 3.39%   |
| Supermicro SYS-1018GR-T | 1        | 1.69%   |
| Sun Microsystems Ultra  | 1        | 1.69%   |
| Online Labs SR          | 1        | 1.69%   |
| MSI MS-7B86             | 1        | 1.69%   |
| MSI MS-7B84             | 1        | 1.69%   |
| MSI MS-7B53             | 1        | 1.69%   |
| MSI MS-7A38             | 1        | 1.69%   |
| MSI MS-7A36             | 1        | 1.69%   |
| MSI MS-7A34             | 1        | 1.69%   |
| MSI MS-7885             | 1        | 1.69%   |
| MSI MS-7678             | 1        | 1.69%   |
| MSI MS-7673             | 1        | 1.69%   |
| LORD ELECTRONICS LORD   | 1        | 1.69%   |
| Intel D815EEA           | 1        | 1.69%   |
| Intel AHV               | 1        | 1.69%   |
| HP Z640                 | 1        | 1.69%   |
| HP Z220                 | 1        | 1.69%   |
| HP ProDesk              | 1        | 1.69%   |
| HP EliteDesk            | 1        | 1.69%   |
| HP Compaq               | 1        | 1.69%   |
| Google Panther          | 1        | 1.69%   |
| Gigabyte Z390           | 1        | 1.69%   |
| Gigabyte P55A-UD3       | 1        | 1.69%   |
| Gigabyte MZGLKBP-00     | 1        | 1.69%   |
| Gigabyte H81M-S2H       | 1        | 1.69%   |
| Gigabyte H310M          | 1        | 1.69%   |
| Gigabyte H170-HD3-CF    | 1        | 1.69%   |
| Gigabyte H170-HD3       | 1        | 1.69%   |
| Gigabyte GA-G41M-ES2L   | 1        | 1.69%   |
| Gigabyte B75M-D3V       | 1        | 1.69%   |
| Gigabyte B650I          | 1        | 1.69%   |
| Gigabyte B550I          | 1        | 1.69%   |
| Gigabyte B450           | 1        | 1.69%   |
| Gigabyte 970A-DS3P      | 1        | 1.69%   |
| Dell Vostro             | 1        | 1.69%   |
| ASUS P5PE-VM            | 1        | 1.69%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 10       | 16.95%  |
| 2019 | 7        | 11.86%  |
| 2013 | 5        | 8.47%   |
| 2011 | 5        | 8.47%   |
| 2017 | 4        | 6.78%   |
| 2014 | 4        | 6.78%   |
| 2012 | 4        | 6.78%   |
| 2020 | 3        | 5.08%   |
| 2010 | 3        | 5.08%   |
| 2022 | 2        | 3.39%   |
| 2016 | 2        | 3.39%   |
| 2015 | 2        | 3.39%   |
| 2009 | 2        | 3.39%   |
| 2023 | 1        | 1.69%   |
| 2021 | 1        | 1.69%   |
| 2008 | 1        | 1.69%   |
| 2007 | 1        | 1.69%   |
| 2006 | 1        | 1.69%   |
| 2000 | 1        | 1.69%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 59       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 58       | 98.31%  |
| Enabled  | 1        | 1.69%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 57       | 96.61%  |
| Yes  | 2        | 3.39%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 17       | 28.81%  |
| 32.01-64.0  | 12       | 20.34%  |
| 8.01-16.0   | 11       | 18.64%  |
| 4.01-8.0    | 8        | 13.56%  |
| 64.01-256.0 | 4        | 6.78%   |
| 3.01-4.0    | 3        | 5.08%   |
| 1.01-2.0    | 3        | 5.08%   |
| 0.01-0.5    | 1        | 1.69%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 20       | 31.75%  |
| 4.01-8.0   | 10       | 15.87%  |
| 0.51-1.0   | 9        | 14.29%  |
| 2.01-3.0   | 8        | 12.7%   |
| 3.01-4.0   | 6        | 9.52%   |
| 8.01-16.0  | 5        | 7.94%   |
| 0.01-0.5   | 3        | 4.76%   |
| 16.01-24.0 | 2        | 3.17%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 23       | 38.98%  |
| 3      | 12       | 20.34%  |
| 2      | 11       | 18.64%  |
| 4      | 5        | 8.47%   |
| 5      | 4        | 6.78%   |
| 6      | 3        | 5.08%   |
| 7      | 1        | 1.69%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 41       | 69.49%  |
| Yes       | 18       | 30.51%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 58       | 98.31%  |
| No        | 1        | 1.69%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 48       | 80%     |
| Yes       | 12       | 20%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 51       | 86.44%  |
| Yes       | 8        | 13.56%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 8        | 13.56%  |
| France      | 8        | 13.56%  |
| Russia      | 5        | 8.47%   |
| Ukraine     | 3        | 5.08%   |
| UK          | 3        | 5.08%   |
| Slovakia    | 3        | 5.08%   |
| Poland      | 3        | 5.08%   |
| Germany     | 3        | 5.08%   |
| Australia   | 3        | 5.08%   |
| New Zealand | 2        | 3.39%   |
| Netherlands | 2        | 3.39%   |
| Canada      | 2        | 3.39%   |
| Brazil      | 2        | 3.39%   |
| Belgium     | 2        | 3.39%   |
| Argentina   | 2        | 3.39%   |
| Tunisia     | 1        | 1.69%   |
| Spain       | 1        | 1.69%   |
| South Korea | 1        | 1.69%   |
| Puerto Rico | 1        | 1.69%   |
| Israel      | 1        | 1.69%   |
| Georgia     | 1        | 1.69%   |
| China       | 1        | 1.69%   |
| Bulgaria    | 1        | 1.69%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Desktops | Percent |
|-----------------|----------|---------|
| Bratislava      | 3        | 5.08%   |
| Bagnolet        | 3        | 5.08%   |
| Volzhskiy       | 2        | 3.39%   |
| Toronto         | 2        | 3.39%   |
| Sydney          | 2        | 3.39%   |
| Auckland        | 2        | 3.39%   |
| Xiamen          | 1        | 1.69%   |
| Wroclaw         | 1        | 1.69%   |
| Waterford       | 1        | 1.69%   |
| Vladikavkaz     | 1        | 1.69%   |
| Vise            | 1        | 1.69%   |
| Tel Aviv        | 1        | 1.69%   |
| Tbilisi         | 1        | 1.69%   |
| Sofia           | 1        | 1.69%   |
| Seongbuk-gu     | 1        | 1.69%   |
| Sao Paulo       | 1        | 1.69%   |
| Saint-Herblain  | 1        | 1.69%   |
| Roubaix         | 1        | 1.69%   |
| Rio de Janeiro  | 1        | 1.69%   |
| Renkum          | 1        | 1.69%   |
| Radzionkow      | 1        | 1.69%   |
| Port Richey     | 1        | 1.69%   |
| Poperinge       | 1        | 1.69%   |
| Paris           | 1        | 1.69%   |
| Oleksandriya    | 1        | 1.69%   |
| Okehampton      | 1        | 1.69%   |
| Novopokrovskoye | 1        | 1.69%   |
| Norman          | 1        | 1.69%   |
| Nérac          | 1        | 1.69%   |
| Miedziana Gora  | 1        | 1.69%   |
| Miami           | 1        | 1.69%   |
| Madrid          | 1        | 1.69%   |
| Loosdrecht      | 1        | 1.69%   |
| Leeds           | 1        | 1.69%   |
| Lahr            | 1        | 1.69%   |
| L'Albenc        | 1        | 1.69%   |
| Kirov           | 1        | 1.69%   |
| Karlsruhe       | 1        | 1.69%   |
| Holt            | 1        | 1.69%   |
| Hollywood       | 1        | 1.69%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 26       | 45     | 23.21%  |
| Seagate             | 21       | 32     | 18.75%  |
| Kingston            | 10       | 13     | 8.93%   |
| Samsung Electronics | 8        | 15     | 7.14%   |
| Toshiba             | 7        | 7      | 6.25%   |
| Crucial             | 5        | 7      | 4.46%   |
| Sandisk             | 4        | 4      | 3.57%   |
| Netac               | 2        | 2      | 1.79%   |
| Micron Technology   | 2        | 2      | 1.79%   |
| Maxtor              | 2        | 2      | 1.79%   |
| Hitachi             | 2        | 2      | 1.79%   |
| Dogfish             | 2        | 2      | 1.79%   |
| A-DATA Technology   | 2        | 2      | 1.79%   |
| WD MediaMax         | 1        | 3      | 0.89%   |
| Unknown             | 1        | 1      | 0.89%   |
| Transcend           | 1        | 2      | 0.89%   |
| Team                | 1        | 1      | 0.89%   |
| Supermicro          | 1        | 1      | 0.89%   |
| SK hynix            | 1        | 1      | 0.89%   |
| PNY                 | 1        | 1      | 0.89%   |
| Plextor             | 1        | 1      | 0.89%   |
| Lexar               | 1        | 1      | 0.89%   |
| KingDian            | 1        | 1      | 0.89%   |
| Intenso             | 1        | 1      | 0.89%   |
| Intel               | 1        | 1      | 0.89%   |
| IBM/Hitachi         | 1        | 1      | 0.89%   |
| HPE                 | 1        | 2      | 0.89%   |
| HGST                | 1        | 1      | 0.89%   |
| Hewlett-Packard     | 1        | 2      | 0.89%   |
| GOODRAM             | 1        | 1      | 0.89%   |
| Fujitsu             | 1        | 1      | 0.89%   |
| China               | 1        | 1      | 0.89%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Kingston SA400S37120G 120GB SSD  | 3        | 2.24%   |
| Kingston SA2000M8250G 250GB      | 3        | 2.24%   |
| WDC WD10EZEX-08WN4A0 1TB         | 2        | 1.49%   |
| WDC WD10EZEX-00BBHA0 1TB         | 2        | 1.49%   |
| WDC WD10EARX-00N0YB0 1TB         | 2        | 1.49%   |
| Seagate ST3500418AS 500GB        | 2        | 1.49%   |
| Seagate ST2000DX002-2DV164 2TB   | 2        | 1.49%   |
| Seagate ST2000DM008-2FR102 2TB   | 2        | 1.49%   |
| Samsung SSD 860 EVO 250GB        | 2        | 1.49%   |
| Hitachi HDS721616PLA380 160GB    | 2        | 1.49%   |
| WDC WDS500G3X0C-00SJG0 500GB     | 1        | 0.75%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 1        | 0.75%   |
| WDC WDS480G2G0A-00JH30 480GB SSD | 1        | 0.75%   |
| WDC WDS120G2G0A-00JH30 120GB SSD | 1        | 0.75%   |
| WDC WD800BB-00JHC0 80GB          | 1        | 0.75%   |
| WDC WD7500AALX-009BA0 752GB      | 1        | 0.75%   |
| WDC WD5001AALS-00L3B2 500GB      | 1        | 0.75%   |
| WDC WD5001AALS-00E3A0 500GB      | 1        | 0.75%   |
| WDC WD5000LPVX-00V0TT0 500GB     | 1        | 0.75%   |
| WDC WD5000BPVT-24HXZT3 500GB     | 1        | 0.75%   |
| WDC WD5000AZLX-75K2TA0 500GB     | 1        | 0.75%   |
| WDC WD40EFRX-68WT0N0 4TB         | 1        | 0.75%   |
| WDC WD40EDAZ-11SLVB0 4TB         | 1        | 0.75%   |
| WDC WD20PURZ-85GU6Y0 2TB         | 1        | 0.75%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 1        | 0.75%   |
| WDC WD20EZRX-00DC0B0 2TB         | 1        | 0.75%   |
| WDC WD20EZRX-00D8PB0 2TB         | 1        | 0.75%   |
| WDC WD20EZAZ-00L9GB0 2TB         | 1        | 0.75%   |
| WDC WD20EFRX-68EUZN0 2TB         | 1        | 0.75%   |
| WDC WD1600AAJS-00YZCA0 160GB     | 1        | 0.75%   |
| WDC WD1200JS-55NCB1 120GB        | 1        | 0.75%   |
| WDC WD10SPZX-22Z10T1 1TB         | 1        | 0.75%   |
| WDC WD10JFCX-68N6GN0 1TB         | 1        | 0.75%   |
| WDC WD10EZRX-00D8PB0 1TB         | 1        | 0.75%   |
| WDC WD10EZEX-75M2NA0 1TB         | 1        | 0.75%   |
| WDC WD10EZEX-22MFCA0 1TB         | 1        | 0.75%   |
| WDC WD10EZEX-22BN5A0 1TB         | 1        | 0.75%   |
| WDC WD10EZEX-08M2NA0 1TB         | 1        | 0.75%   |
| WDC WD10EZEX-00BN5A0 1TB         | 1        | 0.75%   |
| WDC WD10EURX-63FH1Y0 1TB         | 1        | 0.75%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 23       | 41     | 39.66%  |
| Seagate             | 20       | 31     | 34.48%  |
| Toshiba             | 5        | 5      | 8.62%   |
| Maxtor              | 2        | 2      | 3.45%   |
| Hitachi             | 2        | 2      | 3.45%   |
| Samsung Electronics | 1        | 1      | 1.72%   |
| IBM/Hitachi         | 1        | 1      | 1.72%   |
| HPE                 | 1        | 2      | 1.72%   |
| HGST                | 1        | 1      | 1.72%   |
| Hewlett-Packard     | 1        | 2      | 1.72%   |
| Fujitsu             | 1        | 1      | 1.72%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 7        | 9      | 17.95%  |
| Kingston            | 7        | 9      | 17.95%  |
| WDC                 | 3        | 3      | 7.69%   |
| Netac               | 2        | 2      | 5.13%   |
| Micron Technology   | 2        | 2      | 5.13%   |
| Dogfish             | 2        | 2      | 5.13%   |
| Crucial             | 2        | 3      | 5.13%   |
| A-DATA Technology   | 2        | 2      | 5.13%   |
| Transcend           | 1        | 2      | 2.56%   |
| Team                | 1        | 1      | 2.56%   |
| Supermicro          | 1        | 1      | 2.56%   |
| SK hynix            | 1        | 1      | 2.56%   |
| SanDisk             | 1        | 1      | 2.56%   |
| PNY                 | 1        | 1      | 2.56%   |
| Plextor             | 1        | 1      | 2.56%   |
| Lexar               | 1        | 1      | 2.56%   |
| KingDian            | 1        | 1      | 2.56%   |
| Intenso             | 1        | 1      | 2.56%   |
| GOODRAM             | 1        | 1      | 2.56%   |
| China               | 1        | 1      | 2.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 43       | 89     | 45.26%  |
| SSD     | 33       | 45     | 34.74%  |
| NVMe    | 16       | 20     | 16.84%  |
| Unknown | 2        | 4      | 2.11%   |
| MMC     | 1        | 1      | 1.05%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 55       | 131    | 72.37%  |
| NVMe | 16       | 20     | 21.05%  |
| SAS  | 4        | 7      | 5.26%   |
| MMC  | 1        | 1      | 1.32%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 39       | 65     | 48.15%  |
| 0.51-1.0   | 23       | 42     | 28.4%   |
| 1.01-2.0   | 12       | 19     | 14.81%  |
| 3.01-4.0   | 5        | 6      | 6.17%   |
| 4.01-10.0  | 2        | 2      | 2.47%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1001-2000      | 13       | 20.97%  |
| 501-1000       | 12       | 19.35%  |
| 251-500        | 11       | 17.74%  |
| More than 3000 | 8        | 12.9%   |
| 101-250        | 7        | 11.29%  |
| 21-50          | 3        | 4.84%   |
| 51-100         | 3        | 4.84%   |
| 1-20           | 2        | 3.23%   |
| Unknown        | 2        | 3.23%   |
| 2001-3000      | 1        | 1.61%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 16       | 26.23%  |
| 1-20           | 13       | 21.31%  |
| 21-50          | 6        | 9.84%   |
| 501-1000       | 6        | 9.84%   |
| 251-500        | 5        | 8.2%    |
| 1001-2000      | 5        | 8.2%    |
| More than 3000 | 3        | 4.92%   |
| 2001-3000      | 3        | 4.92%   |
| 51-100         | 2        | 3.28%   |
| Unknown        | 2        | 3.28%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Hitachi HDS721616PLA380 160GB         | 2        | 2      | 11.76%  |
| WDC WD5000LPVX-00V0TT0 500GB          | 1        | 1      | 5.88%   |
| WDC WD5000BPVT-24HXZT3 500GB          | 1        | 1      | 5.88%   |
| WDC WD10EARX-00N0YB0 1TB              | 1        | 1      | 5.88%   |
| Toshiba MQ04ABF100 1TB                | 1        | 1      | 5.88%   |
| Toshiba MQ02ABF100 1TB                | 1        | 1      | 5.88%   |
| SK hynix SH920 mSATA 128GB SSD        | 1        | 1      | 5.88%   |
| Seagate ST3500418AS 500GB             | 1        | 1      | 5.88%   |
| Samsung Electronics SSD 970 EVO 500GB | 1        | 1      | 5.88%   |
| Maxtor 6E040L0 41GB                   | 1        | 1      | 5.88%   |
| Kingston SA400S37120G 120GB SSD       | 1        | 1      | 5.88%   |
| HPE MB4000GEFNA 4TB                   | 1        | 2      | 5.88%   |
| HGST HTE721010A9E630 1TB              | 1        | 1      | 5.88%   |
| Hewlett-Packard VB0250EAVER 250GB     | 1        | 2      | 5.88%   |
| Fujitsu MHV2060BH PL 64GB             | 1        | 1      | 5.88%   |
| China SATA SSD 64GB                   | 1        | 1      | 5.88%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 3        | 3      | 17.65%  |
| Toshiba             | 2        | 2      | 11.76%  |
| Hitachi             | 2        | 2      | 11.76%  |
| SK hynix            | 1        | 1      | 5.88%   |
| Seagate             | 1        | 1      | 5.88%   |
| Samsung Electronics | 1        | 1      | 5.88%   |
| Maxtor              | 1        | 1      | 5.88%   |
| Kingston            | 1        | 1      | 5.88%   |
| HPE                 | 1        | 2      | 5.88%   |
| HGST                | 1        | 1      | 5.88%   |
| Hewlett-Packard     | 1        | 2      | 5.88%   |
| Fujitsu             | 1        | 1      | 5.88%   |
| China               | 1        | 1      | 5.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor          | Desktops | Drives | Percent |
|-----------------|----------|--------|---------|
| WDC             | 3        | 3      | 23.08%  |
| Toshiba         | 2        | 2      | 15.38%  |
| Hitachi         | 2        | 2      | 15.38%  |
| Seagate         | 1        | 1      | 7.69%   |
| Maxtor          | 1        | 1      | 7.69%   |
| HPE             | 1        | 2      | 7.69%   |
| HGST            | 1        | 1      | 7.69%   |
| Hewlett-Packard | 1        | 2      | 7.69%   |
| Fujitsu         | 1        | 1      | 7.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 13       | 15     | 76.47%  |
| SSD  | 3        | 3      | 17.65%  |
| NVMe | 1        | 1      | 5.88%   |

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
| Works    | 45       | 112    | 60%     |
| Malfunc  | 16       | 19     | 21.33%  |
| Detected | 14       | 28     | 18.67%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 42       | 50%     |
| AMD                              | 16       | 19.05%  |
| Sandisk                          | 4        | 4.76%   |
| Samsung Electronics              | 4        | 4.76%   |
| Kingston Technology Company      | 4        | 4.76%   |
| Micron/Crucial Technology        | 3        | 3.57%   |
| Toshiba America Info Systems     | 2        | 2.38%   |
| Marvell Technology Group         | 2        | 2.38%   |
| Silicon Integrated Systems [SiS] | 1        | 1.19%   |
| LSI Logic / Symbios Logic        | 1        | 1.19%   |
| Integrated Technology Express    | 1        | 1.19%   |
| Chelsio Communications           | 1        | 1.19%   |
| Broadcom / LSI                   | 1        | 1.19%   |
| ASMedia Technology               | 1        | 1.19%   |
| Adaptec                          | 1        | 1.19%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 11       | 10.28%  |
| AMD 400 Series Chipset SATA Controller                                                  | 6        | 5.61%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 5        | 4.67%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5        | 4.67%   |
| Kingston Company A2000 NVMe SSD                                                         | 4        | 3.74%   |
| Intel SATA Controller [RAID mode]                                                       | 4        | 3.74%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 4        | 3.74%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4        | 3.74%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3        | 2.8%    |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 3        | 2.8%    |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 3        | 2.8%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3        | 2.8%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3        | 2.8%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2        | 1.87%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 2        | 1.87%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 1.87%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2        | 1.87%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2        | 1.87%   |
| AMD FCH SATA Controller D                                                               | 2        | 1.87%   |
| AMD 500 Series Chipset SATA Controller                                                  | 2        | 1.87%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 1        | 0.93%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                                    | 1        | 0.93%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                             | 1        | 0.93%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                    | 1        | 0.93%   |
| Sandisk Western Digital WD Black SN850X NVMe SSD                                        | 1        | 0.93%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD                 | 1        | 0.93%   |
| Samsung NVMe SSD Controller 980                                                         | 1        | 0.93%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton2]                                              | 1        | 0.93%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 1        | 0.93%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller                                 | 1        | 0.93%   |
| LSI Logic / Symbios Logic MegaRAID SAS 2108 [Liberator]                                 | 1        | 0.93%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1        | 0.93%   |
| Intel Optane SSD 900P Series                                                            | 1        | 0.93%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1        | 0.93%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1        | 0.93%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 1        | 0.93%   |
| Intel Atom processor C2000 AHCI SATA3 Controller                                        | 1        | 0.93%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 1        | 0.93%   |
| Intel 82801EB/ER (ICH5/ICH5R) IDE Controller                                            | 1        | 0.93%   |
| Intel 82801BA IDE U100 Controller                                                       | 1        | 0.93%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 47       | 57.32%  |
| NVMe | 16       | 19.51%  |
| IDE  | 12       | 14.63%  |
| RAID | 5        | 6.1%    |
| SCSI | 2        | 2.44%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 43       | 72.88%  |
| AMD    | 16       | 27.12%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-9400F CPU @ 2.90GHz           | 2        | 3.33%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 2        | 3.33%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 2        | 3.33%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2        | 3.33%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 2        | 3.33%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 2        | 3.33%   |
| Intel Xeon CPU X3460 @ 2.80GHz              | 1        | 1.67%   |
| Intel Xeon CPU E5-2643 v3 @ 3.40GHz         | 1        | 1.67%   |
| Intel Xeon CPU E5-2603 v4 @ 1.70GHz         | 1        | 1.67%   |
| Intel Xeon CPU E3-1270 V2 @ 3.50GHz         | 1        | 1.67%   |
| Intel Xeon CPU E3-1226 v3 @ 3.30GHz         | 1        | 1.67%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz    | 1        | 1.67%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz      | 1        | 1.67%   |
| Intel Pentium Dual-Core CPU E6300 @ 2.80GHz | 1        | 1.67%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1        | 1.67%   |
| Intel Pentium CPU G3240 @ 3.10GHz           | 1        | 1.67%   |
| Intel Pentium 4 CPU 3.00GHz                 | 1        | 1.67%   |
| Intel Core i9-10850K CPU @ 3.60GHz          | 1        | 1.67%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 1        | 1.67%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1        | 1.67%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1        | 1.67%   |
| Intel Core i7-5930K CPU @ 3.50GHz           | 1        | 1.67%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 1        | 1.67%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 1.67%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1        | 1.67%   |
| Intel Core i5-7500T CPU @ 2.70GHz           | 1        | 1.67%   |
| Intel Core i5-4590T CPU @ 2.00GHz           | 1        | 1.67%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 1        | 1.67%   |
| Intel Core i5-4570S CPU @ 2.90GHz           | 1        | 1.67%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1        | 1.67%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 1        | 1.67%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 1        | 1.67%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 1        | 1.67%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 1        | 1.67%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 1        | 1.67%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 1        | 1.67%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 1        | 1.67%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 1        | 1.67%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 1        | 1.67%   |
| Intel Celeron CPU N3350 @ 1.10GHz           | 1        | 1.67%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 15       | 25%     |
| Intel Core i7           | 7        | 11.67%  |
| Intel Xeon              | 5        | 8.33%   |
| AMD Ryzen 5             | 5        | 8.33%   |
| Intel Core 2 Duo        | 3        | 5%      |
| AMD Ryzen 7             | 3        | 5%      |
| Intel Core i3           | 2        | 3.33%   |
| Intel Core 2 Quad       | 2        | 3.33%   |
| Intel Celeron           | 2        | 3.33%   |
| AMD Ryzen 3             | 2        | 3.33%   |
| Intel Pentium Silver    | 1        | 1.67%   |
| Intel Pentium Gold      | 1        | 1.67%   |
| Intel Pentium Dual-Core | 1        | 1.67%   |
| Intel Pentium Dual      | 1        | 1.67%   |
| Intel Pentium 4         | 1        | 1.67%   |
| Intel Pentium           | 1        | 1.67%   |
| Intel Core i9           | 1        | 1.67%   |
| Intel Atom              | 1        | 1.67%   |
| AMD Sempron             | 1        | 1.67%   |
| AMD Ryzen Threadripper  | 1        | 1.67%   |
| AMD Ryzen 7 PRO         | 1        | 1.67%   |
| AMD FX                  | 1        | 1.67%   |
| AMD Athlon              | 1        | 1.67%   |
| AMD A4                  | 1        | 1.67%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 22       | 37.29%  |
| 6      | 13       | 22.03%  |
| 2      | 13       | 22.03%  |
| 8      | 6        | 10.17%  |
| 1      | 3        | 5.08%   |
| 12     | 1        | 1.69%   |
| 10     | 1        | 1.69%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 59       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 30       | 50.85%  |
| 2      | 29       | 49.15%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 58       | 98.31%  |
| 32-bit         | 1        | 1.69%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 10       | 16.67%  |
| 0x306c3    | 5        | 8.33%   |
| 0x206a7    | 5        | 8.33%   |
| 0x906ea    | 4        | 6.67%   |
| 0x1067a    | 4        | 6.67%   |
| 0x306a9    | 3        | 5%      |
| 0x0800820d | 3        | 5%      |
| 0x106e5    | 2        | 3.33%   |
| 0x08701021 | 2        | 3.33%   |
| 0xf49      | 1        | 1.67%   |
| 0xa0655    | 1        | 1.67%   |
| 0xa0653    | 1        | 1.67%   |
| 0x906ed    | 1        | 1.67%   |
| 0x906e9    | 1        | 1.67%   |
| 0x706a1    | 1        | 1.67%   |
| 0x6fd      | 1        | 1.67%   |
| 0x686      | 1        | 1.67%   |
| 0x506e3    | 1        | 1.67%   |
| 0x506c9    | 1        | 1.67%   |
| 0x406f1    | 1        | 1.67%   |
| 0x406d8    | 1        | 1.67%   |
| 0x40651    | 1        | 1.67%   |
| 0x306f2    | 1        | 1.67%   |
| 0x10676    | 1        | 1.67%   |
| 0x0a601203 | 1        | 1.67%   |
| 0x0a20120a | 1        | 1.67%   |
| 0x08701013 | 1        | 1.67%   |
| 0x0810100b | 1        | 1.67%   |
| 0x08001138 | 1        | 1.67%   |
| 0x08001129 | 1        | 1.67%   |
| 0x03000027 | 1        | 1.67%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Haswell       | 9        | 15.25%  |
| KabyLake      | 7        | 11.86%  |
| SandyBridge   | 5        | 8.47%   |
| Penryn        | 5        | 8.47%   |
| Zen+          | 4        | 6.78%   |
| Zen           | 4        | 6.78%   |
| Zen 2         | 3        | 5.08%   |
| Nehalem       | 3        | 5.08%   |
| IvyBridge     | 3        | 5.08%   |
| Skylake       | 2        | 3.39%   |
| CometLake     | 2        | 3.39%   |
| Zen 3         | 1        | 1.69%   |
| Silvermont    | 1        | 1.69%   |
| Piledriver    | 1        | 1.69%   |
| P6            | 1        | 1.69%   |
| NetBurst      | 1        | 1.69%   |
| K8 Hammer     | 1        | 1.69%   |
| K10 Llano     | 1        | 1.69%   |
| Goldmont plus | 1        | 1.69%   |
| Goldmont      | 1        | 1.69%   |
| Core          | 1        | 1.69%   |
| Broadwell     | 1        | 1.69%   |
| Unknown       | 1        | 1.69%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 21       | 35%     |
| Nvidia                           | 20       | 33.33%  |
| AMD                              | 17       | 28.33%  |
| Silicon Integrated Systems [SiS] | 1        | 1.67%   |
| ASPEED Technology                | 1        | 1.67%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 4        | 6.35%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 4        | 6.35%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 3        | 4.76%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 3.17%   |
| Nvidia G96CGL [Quadro FX 580]                                               | 2        | 3.17%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2        | 3.17%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 3.17%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 3.17%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 3.17%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2        | 3.17%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter           | 1        | 1.59%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 1.59%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                       | 1        | 1.59%   |
| Nvidia GT218 [GeForce 310]                                                  | 1        | 1.59%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 1.59%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 1.59%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1        | 1.59%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 1.59%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 1.59%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 1.59%   |
| Nvidia GK107 [NVS 510]                                                      | 1        | 1.59%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                           | 1        | 1.59%   |
| Nvidia GF108 [GeForce GT 430]                                               | 1        | 1.59%   |
| Nvidia GA104 [GeForce RTX 3060 Ti]                                          | 1        | 1.59%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 1.59%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1        | 1.59%   |
| Intel HD Graphics 630                                                       | 1        | 1.59%   |
| Intel HD Graphics 500                                                       | 1        | 1.59%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 1        | 1.59%   |
| Intel GeminiLake [UHD Graphics 605]                                         | 1        | 1.59%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                   | 1        | 1.59%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 1        | 1.59%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 1.59%   |
| ASPEED Technology ASPEED Graphics Family                                    | 1        | 1.59%   |
| AMD Tahiti PRO [Radeon HD 7950/8950 OEM / R9 280]                           | 1        | 1.59%   |
| AMD RV350 [Radeon 9550] (Secondary)                                         | 1        | 1.59%   |
| AMD RV350 [Radeon 9550]                                                     | 1        | 1.59%   |
| AMD RV100 [Radeon 7000 / Radeon VE]                                         | 1        | 1.59%   |
| AMD RS780L [Radeon 3000]                                                    | 1        | 1.59%   |
| AMD R350 [Radeon 9800 Series]                                               | 1        | 1.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| 1 x Nvidia  | 20       | 33.9%   |
| 1 x Intel   | 19       | 32.2%   |
| 1 x AMD     | 15       | 25.42%  |
| Other       | 1        | 1.69%   |
| 2 x AMD     | 1        | 1.69%   |
| 1 x SiS     | 1        | 1.69%   |
| Intel + AMD | 1        | 1.69%   |
| 1 x ASPEED  | 1        | 1.69%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 42       | 70%     |
| Proprietary | 13       | 21.67%  |
| Unknown     | 5        | 8.33%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 26       | 43.33%  |
| 3.01-4.0   | 8        | 13.33%  |
| 0.01-0.5   | 8        | 13.33%  |
| 7.01-8.0   | 5        | 8.33%   |
| 0.51-1.0   | 5        | 8.33%   |
| 2.01-3.0   | 3        | 5%      |
| 1.01-2.0   | 3        | 5%      |
| 5.01-6.0   | 2        | 3.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 12       | 19.35%  |
| Hewlett-Packard      | 7        | 11.29%  |
| Philips              | 6        | 9.68%   |
| Goldstar             | 4        | 6.45%   |
| Dell                 | 4        | 6.45%   |
| AOC                  | 4        | 6.45%   |
| Unknown              | 3        | 4.84%   |
| Lenovo               | 3        | 4.84%   |
| Iiyama               | 3        | 4.84%   |
| Ancor Communications | 3        | 4.84%   |
| Acer                 | 3        | 4.84%   |
| ___                  | 1        | 1.61%   |
| ViewSonic            | 1        | 1.61%   |
| Toshiba              | 1        | 1.61%   |
| MSI                  | 1        | 1.61%   |
| HJW                  | 1        | 1.61%   |
| eMachines            | 1        | 1.61%   |
| Eizo                 | 1        | 1.61%   |
| CVT                  | 1        | 1.61%   |
| CHI                  | 1        | 1.61%   |
| BenQ                 | 1        | 1.61%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM0091 1600x1200 432x324mm 21.3-inch   | 2        | 3.03%   |
| Philips 17S PHL0877 1280x1024 337x270mm 17.0-inch                      | 2        | 3.03%   |
| Hewlett-Packard 22m HPN3575 1920x1080 476x268mm 21.5-inch              | 2        | 3.03%   |
| ___ LCDTV16 ___9000 1360x768                                           | 1        | 1.52%   |
| ViewSonic VA2261 Series VSC0F30 1920x1080 477x268mm 21.5-inch          | 1        | 1.52%   |
| Unknown LCD TV 9000 1360x768 1600x900mm 72.3-inch                      | 1        | 1.52%   |
| Unknown LCD Monitor hp L1702 1280x1024                                 | 1        | 1.52%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch              | 1        | 1.52%   |
| Toshiba TV TSB0209 1920x1080 1594x900mm 72.1-inch                      | 1        | 1.52%   |
| Samsung Electronics T24B301 SAM098E 1920x1080 521x293mm 23.5-inch      | 1        | 1.52%   |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                       | 1        | 1.52%   |
| Samsung Electronics SyncMaster SAM0473 2048x1152 510x287mm 23.0-inch   | 1        | 1.52%   |
| Samsung Electronics SyncMaster SAM0226 1440x900 410x257mm 19.1-inch    | 1        | 1.52%   |
| Samsung Electronics SyncMaster SAM0029 2048x1536 312x234mm 15.4-inch   | 1        | 1.52%   |
| Samsung Electronics S/T 77/76BDF STN0007 1280x1024 312x234mm 15.4-inch | 1        | 1.52%   |
| Samsung Electronics LCD Monitor SyncMaster 1280x1024                   | 1        | 1.52%   |
| Samsung Electronics LCD Monitor SyncMaster                             | 1        | 1.52%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 700x390mm 31.5-inch  | 1        | 1.52%   |
| Samsung Electronics LCD Monitor SA300/350/360                          | 1        | 1.52%   |
| Samsung Electronics LCD Monitor S24D340                                | 1        | 1.52%   |
| Samsung Electronics LCD Monitor C27F390 5760x1080                      | 1        | 1.52%   |
| Samsung Electronics C27F398 SAM0D45 1920x1080 598x336mm 27.0-inch      | 1        | 1.52%   |
| Philips PHL 243S7 PHL090F 1920x1080 527x296mm 23.8-inch                | 1        | 1.52%   |
| Philips PHL 241P6Q PHL08DB 1920x1080 527x296mm 23.8-inch               | 1        | 1.52%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                | 1        | 1.52%   |
| Philips 190B PHL086C 1280x1024 376x301mm 19.0-inch                     | 1        | 1.52%   |
| MSI Optix G241VC MSI1462 1920x1080 521x294mm 23.6-inch                 | 1        | 1.52%   |
| Lenovo LI2215sD LEN65CC 1920x1080 476x267mm 21.5-inch                  | 1        | 1.52%   |
| Lenovo LCD Monitor LEN40A0 1366x768 309x174mm 14.0-inch                | 1        | 1.52%   |
| Lenovo L24e-30 LEN66BC 1920x1080 527x296mm 23.8-inch                   | 1        | 1.52%   |
| Iiyama PLX2483H IVM6114 1920x1080 531x299mm 24.0-inch                  | 1        | 1.52%   |
| Iiyama PLB2712HDS IVM6602 1920x1080 598x336mm 27.0-inch                | 1        | 1.52%   |
| Iiyama PL2482H IVM610D 1920x1080 521x293mm 23.5-inch                   | 1        | 1.52%   |
| HJW HDMI TO USB HJW0001 1920x1080 700x390mm 31.5-inch                  | 1        | 1.52%   |
| Hewlett-Packard LA2206 HWP2947 1920x1080 477x268mm 21.5-inch           | 1        | 1.52%   |
| Hewlett-Packard L2245w HWP26FC 1680x1050 473x296mm 22.0-inch           | 1        | 1.52%   |
| Hewlett-Packard ENVY 34c HWP3204 3440x1440 800x330mm 34.1-inch         | 1        | 1.52%   |
| Hewlett-Packard E243 HPN3468 1920x1080 527x296mm 23.8-inch             | 1        | 1.52%   |
| Hewlett-Packard Compaq S2321a HWP2915 1920x1080 509x286mm 23.0-inch    | 1        | 1.52%   |
| Hewlett-Packard 22cwa HWP3183 1920x1080 480x270mm 21.7-inch            | 1        | 1.52%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 24       | 40%     |
| 1280x1024 (SXGA)   | 7        | 11.67%  |
| 1440x900 (WXGA+)   | 5        | 8.33%   |
| 3840x2160 (4K)     | 4        | 6.67%   |
| 1920x1200 (WUXGA)  | 3        | 5%      |
| 1366x768 (WXGA)    | 3        | 5%      |
| 3440x1440          | 2        | 3.33%   |
| 1600x1200          | 2        | 3.33%   |
| Unknown            | 2        | 3.33%   |
| 5760x1080          | 1        | 1.67%   |
| 2560x1440 (QHD)    | 1        | 1.67%   |
| 2288x1287          | 1        | 1.67%   |
| 2048x1152          | 1        | 1.67%   |
| 1680x1050 (WSXGA+) | 1        | 1.67%   |
| 1600x900 (HD+)     | 1        | 1.67%   |
| 1360x768           | 1        | 1.67%   |
| 1024x768 (XGA)     | 1        | 1.67%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 12       | 20.34%  |
| Unknown | 8        | 13.56%  |
| 24      | 7        | 11.86%  |
| 23      | 6        | 10.17%  |
| 27      | 4        | 6.78%   |
| 19      | 4        | 6.78%   |
| 18      | 3        | 5.08%   |
| 17      | 3        | 5.08%   |
| 72      | 2        | 3.39%   |
| 34      | 2        | 3.39%   |
| 31      | 2        | 3.39%   |
| 15      | 2        | 3.39%   |
| 142     | 1        | 1.69%   |
| 54      | 1        | 1.69%   |
| 22      | 1        | 1.69%   |
| 14      | 1        | 1.69%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 16       | 29.09%  |
| 401-500        | 16       | 29.09%  |
| Unknown        | 8        | 14.55%  |
| 301-350        | 5        | 9.09%   |
| 701-800        | 2        | 3.64%   |
| 601-700        | 2        | 3.64%   |
| 351-400        | 2        | 3.64%   |
| 1501-2000      | 2        | 3.64%   |
| More than 2000 | 1        | 1.82%   |
| 1001-1500      | 1        | 1.82%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 31       | 55.36%  |
| 16/10   | 7        | 12.5%   |
| Unknown | 6        | 10.71%  |
| 5/4     | 4        | 7.14%   |
| 4/3     | 4        | 7.14%   |
| 21/9    | 2        | 3.57%   |
| 6/5     | 1        | 1.79%   |
| 1.00    | 1        | 1.79%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 21       | 36.21%  |
| Unknown        | 8        | 13.79%  |
| 151-200        | 6        | 10.34%  |
| 141-150        | 5        | 8.62%   |
| More than 1000 | 4        | 6.9%    |
| 351-500        | 4        | 6.9%    |
| 301-350        | 4        | 6.9%    |
| 251-300        | 3        | 5.17%   |
| 111-120        | 2        | 3.45%   |
| 81-90          | 1        | 1.72%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 28       | 49.12%  |
| 101-120 | 17       | 29.82%  |
| Unknown | 8        | 14.04%  |
| 1-50    | 4        | 7.02%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 46       | 77.97%  |
| 2     | 7        | 11.86%  |
| 3     | 3        | 5.08%   |
| 0     | 3        | 5.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 35       | 47.3%   |
| Intel                            | 26       | 35.14%  |
| Qualcomm Atheros                 | 3        | 4.05%   |
| Marvell Technology Group         | 2        | 2.7%    |
| TP-Link                          | 1        | 1.35%   |
| Solarflare Communications        | 1        | 1.35%   |
| Silicon Integrated Systems [SiS] | 1        | 1.35%   |
| Ralink Technology                | 1        | 1.35%   |
| MediaTek                         | 1        | 1.35%   |
| JMicron Technology               | 1        | 1.35%   |
| Chelsio Communications           | 1        | 1.35%   |
| Broadcom                         | 1        | 1.35%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 29       | 36.71%  |
| Intel Ethernet Connection I217-LM                                 | 3        | 3.8%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 3.8%    |
| Intel I210 Gigabit Network Connection                             | 2        | 2.53%   |
| Intel Ethernet Controller I225-V                                  | 2        | 2.53%   |
| Intel Ethernet Connection (7) I219-LM                             | 2        | 2.53%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1        | 1.27%   |
| Solarflare SFC9020 10G Ethernet Controller                        | 1        | 1.27%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1        | 1.27%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 1        | 1.27%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1        | 1.27%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1        | 1.27%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1        | 1.27%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 1.27%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 1.27%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 1.27%   |
| Ralink MT7601U Wireless Adapter                                   | 1        | 1.27%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 1.27%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1        | 1.27%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter        | 1        | 1.27%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 1        | 1.27%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1        | 1.27%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 1.27%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1        | 1.27%   |
| Intel Wireless 7260                                               | 1        | 1.27%   |
| Intel Wi-Fi 6 AX200                                               | 1        | 1.27%   |
| Intel I350 Gigabit Network Connection                             | 1        | 1.27%   |
| Intel I211 Gigabit Network Connection                             | 1        | 1.27%   |
| Intel Ethernet Connection I354 2.5 GbE Backplane                  | 1        | 1.27%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.27%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 1.27%   |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 1.27%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 1.27%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 1.27%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1        | 1.27%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 1.27%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 1.27%   |
| Intel 82576 Gigabit Network Connection                            | 1        | 1.27%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 1.27%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)        | 1        | 1.27%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 4        | 33.33%  |
| Intel                 | 3        | 25%     |
| Qualcomm Atheros      | 2        | 16.67%  |
| TP-Link               | 1        | 8.33%   |
| Ralink Technology     | 1        | 8.33%   |
| MediaTek              | 1        | 8.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                  | 1        | 8.33%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter       | 1        | 8.33%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter         | 1        | 8.33%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 1        | 8.33%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                    | 1        | 8.33%   |
| Ralink MT7601U Wireless Adapter                               | 1        | 8.33%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter              | 1        | 8.33%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter    | 1        | 8.33%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 1        | 8.33%   |
| Intel Wireless 7260                                           | 1        | 8.33%   |
| Intel Wi-Fi 6 AX200                                           | 1        | 8.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 1        | 8.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 32       | 50%     |
| Intel                            | 24       | 37.5%   |
| Marvell Technology Group         | 2        | 3.13%   |
| Solarflare Communications        | 1        | 1.56%   |
| Silicon Integrated Systems [SiS] | 1        | 1.56%   |
| Qualcomm Atheros                 | 1        | 1.56%   |
| JMicron Technology               | 1        | 1.56%   |
| Chelsio Communications           | 1        | 1.56%   |
| Broadcom                         | 1        | 1.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 29       | 43.28%  |
| Intel Ethernet Connection I217-LM                                 | 3        | 4.48%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 4.48%   |
| Intel I210 Gigabit Network Connection                             | 2        | 2.99%   |
| Intel Ethernet Controller I225-V                                  | 2        | 2.99%   |
| Intel Ethernet Connection (7) I219-LM                             | 2        | 2.99%   |
| Solarflare SFC9020 10G Ethernet Controller                        | 1        | 1.49%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1        | 1.49%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 1.49%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 1.49%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 1.49%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 1.49%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1        | 1.49%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 1.49%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1        | 1.49%   |
| Intel I350 Gigabit Network Connection                             | 1        | 1.49%   |
| Intel I211 Gigabit Network Connection                             | 1        | 1.49%   |
| Intel Ethernet Connection I354 2.5 GbE Backplane                  | 1        | 1.49%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.49%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 1.49%   |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 1.49%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 1.49%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 1.49%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 1.49%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 1.49%   |
| Intel 82576 Gigabit Network Connection                            | 1        | 1.49%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 1.49%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)        | 1        | 1.49%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 1.49%   |
| Chelsio T420-SO Unified Wire Ethernet Controller                  | 1        | 1.49%   |
| Chelsio T4 Generic function                                       | 1        | 1.49%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1        | 1.49%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 58       | 82.86%  |
| WiFi     | 12       | 17.14%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 50       | 86.21%  |
| WiFi     | 8        | 13.79%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 42       | 70%     |
| 2     | 12       | 20%     |
| 3     | 2        | 3.33%   |
| 7     | 1        | 1.67%   |
| 5     | 1        | 1.67%   |
| 4     | 1        | 1.67%   |
| 0     | 1        | 1.67%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 54       | 91.53%  |
| Yes  | 5        | 8.47%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 3        | 37.5%   |
| Qualcomm Atheros Communications | 2        | 25%     |
| ASUSTek Computer                | 2        | 25%     |
| MediaTek                        | 1        | 12.5%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| ASUS ASUS USB-BT500                | 2        | 25%     |
| Qualcomm Atheros  Bluetooth Device | 1        | 12.5%   |
| Qualcomm Atheros AR3011 Bluetooth  | 1        | 12.5%   |
| MediaTek Wireless_Device           | 1        | 12.5%   |
| Intel Wireless-AC 3168 Bluetooth   | 1        | 12.5%   |
| Intel Bluetooth wireless interface | 1        | 12.5%   |
| Intel AX200 Bluetooth              | 1        | 12.5%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 37       | 39.36%  |
| AMD                              | 19       | 20.21%  |
| Nvidia                           | 18       | 19.15%  |
| Creative Labs                    | 4        | 4.26%   |
| Plantronics                      | 2        | 2.13%   |
| Texas Instruments                | 1        | 1.06%   |
| TEAC                             | 1        | 1.06%   |
| Silicon Integrated Systems [SiS] | 1        | 1.06%   |
| M-Audio                          | 1        | 1.06%   |
| Logitech                         | 1        | 1.06%   |
| KORG                             | 1        | 1.06%   |
| Giga-Byte Technology             | 1        | 1.06%   |
| Generalplus Technology           | 1        | 1.06%   |
| FUXIN                            | 1        | 1.06%   |
| Focusrite-Novation               | 1        | 1.06%   |
| Elite Silicon                    | 1        | 1.06%   |
| Cirrus Logic                     | 1        | 1.06%   |
| Avance Logic                     | 1        | 1.06%   |
| ASUSTek Computer                 | 1        | 1.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6        | 5.45%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5        | 4.55%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 5        | 4.55%   |
| Nvidia GP106 High Definition Audio Controller                              | 4        | 3.64%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 4        | 3.64%   |
| Intel Cannon Lake PCH cAVS                                                 | 4        | 3.64%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4        | 3.64%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4        | 3.64%   |
| AMD Starship/Matisse HD Audio Controller                                   | 4        | 3.64%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 4        | 3.64%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3        | 2.73%   |
| AMD Family 17h/19h HD Audio Controller                                     | 3        | 2.73%   |
| Plantronics HD1                                                            | 2        | 1.82%   |
| Nvidia High Definition Audio Controller                                    | 2        | 1.82%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 1.82%   |
| Nvidia GP104 High Definition Audio Controller                              | 2        | 1.82%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2        | 1.82%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 2        | 1.82%   |
| Intel 200 Series PCH HD Audio                                              | 2        | 1.82%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]  | 2        | 1.82%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2        | 1.82%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2        | 1.82%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2        | 1.82%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2        | 1.82%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1        | 0.91%   |
| TEAC US-1800                                                               | 1        | 0.91%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 1        | 0.91%   |
| Nvidia TU116 High Definition Audio Controller                              | 1        | 0.91%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 0.91%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1        | 0.91%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1        | 0.91%   |
| Nvidia GF108 High Definition Audio Controller                              | 1        | 0.91%   |
| Nvidia GA104 High Definition Audio Controller                              | 1        | 0.91%   |
| M-Audio MIDISPORT 4x4 Anniv                                                | 1        | 0.91%   |
| M-Audio M-Audio 1x1                                                        | 1        | 0.91%   |
| Logitech H390 headset with microphone                                      | 1        | 0.91%   |
| KORG nanoKONTROL studio controller                                         | 1        | 0.91%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 1        | 0.91%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1        | 0.91%   |
| Intel Comet Lake PCH cAVS                                                  | 1        | 0.91%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 13       | 19.7%   |
| Corsair             | 13       | 19.7%   |
| Kingston            | 11       | 16.67%  |
| SK hynix            | 5        | 7.58%   |
| Micron Technology   | 5        | 7.58%   |
| G.Skill             | 5        | 7.58%   |
| Samsung Electronics | 2        | 3.03%   |
| Nanya Technology    | 2        | 3.03%   |
| Crucial             | 2        | 3.03%   |
| Unknown (ABCD)      | 1        | 1.52%   |
| Transcend           | 1        | 1.52%   |
| Team                | 1        | 1.52%   |
| Ramaxel Technology  | 1        | 1.52%   |
| GOODRAM             | 1        | 1.52%   |
| Avant               | 1        | 1.52%   |
| A-DATA Technology   | 1        | 1.52%   |
| Unknown             | 1        | 1.52%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Corsair RAM CMK32GX4M2B3200C16 16384MB DIMM DDR4 3400MT/s         | 3        | 4.05%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s             | 2        | 2.7%    |
| Corsair RAM CMK32GX4M4A2666C16 8GB DIMM DDR4 2667MT/s             | 2        | 2.7%    |
| Unknown RAM SM3S320SD0488CABC 8192MB SODIMM DDR3 1600MT/s         | 1        | 1.35%   |
| Unknown RAM Module 8192MB DIMM DDR3 800MT/s                       | 1        | 1.35%   |
| Unknown RAM Module 64MB DIMM DRAM 100MT/s                         | 1        | 1.35%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                              | 1        | 1.35%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                    | 1        | 1.35%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                      | 1        | 1.35%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                              | 1        | 1.35%   |
| Unknown RAM Module 256MB DIMM DRAM 100MT/s                        | 1        | 1.35%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                     | 1        | 1.35%   |
| Unknown RAM Module 2048MB DIMM SDRAM 667MT/s                      | 1        | 1.35%   |
| Unknown RAM Module 2048MB DIMM SDRAM                              | 1        | 1.35%   |
| Unknown RAM Module 128MB DIMM DRAM 100MT/s                        | 1        | 1.35%   |
| Unknown RAM Module 1024MB DIMM DDR 400MT/s                        | 1        | 1.35%   |
| Unknown RAM Module 1024MB DIMM DDR                                | 1        | 1.35%   |
| Unknown RAM 3600 C17 Series 8GB DIMM DDR4 3200MT/s                | 1        | 1.35%   |
| Unknown RAM 3000 C16 Series 8192MB DIMM DDR4 2133MT/s             | 1        | 1.35%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR4 2400MT/s | 1        | 1.35%   |
| Transcend RAM JM1333KLN-4G 4096MB DIMM SDRAM 1600MT/s             | 1        | 1.35%   |
| Team RAM TEAMGROUP-UD4-2666 16GB DIMM DDR4 2933MT/s               | 1        | 1.35%   |
| SK hynix RAM Module 4GB DIMM DDR3 1333MT/s                        | 1        | 1.35%   |
| SK hynix RAM HMT451U7BFR8A-PB 4GB DIMM 1600MT/s                   | 1        | 1.35%   |
| SK hynix RAM HMT451U6AFR8A-PB 4096MB DIMM DDR3 1600MT/s           | 1        | 1.35%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s              | 1        | 1.35%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s              | 1        | 1.35%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM 1600MT/s                   | 1        | 1.35%   |
| SK hynix RAM HMA81GU6JJR8N-VK 8GB DIMM DDR4 2667MT/s              | 1        | 1.35%   |
| Samsung RAM Module 2GB DIMM DDR3 1333MT/s                         | 1        | 1.35%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s               | 1        | 1.35%   |
| Ramaxel RAM RMUA5180ME78HBF-2666 16GB DIMM DDR4 2667MT/s          | 1        | 1.35%   |
| Nanya RAM Module 2GB DIMM DDR3 1333MT/s                           | 1        | 1.35%   |
| Nanya RAM M2X4G64CB8HG5N-DG 4GB DIMM DDR3 1867MT/s                | 1        | 1.35%   |
| Micron RAM Module 2GB DIMM DDR3 1333MT/s                          | 1        | 1.35%   |
| Micron RAM DVM64453C DATARAM 8GB DIMM DDR3 1600MT/s               | 1        | 1.35%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s               | 1        | 1.35%   |
| Micron RAM 4ATF51264HZ-2G3E1 4GB SODIMM DDR4 2667MT/s             | 1        | 1.35%   |
| Micron RAM 18ASF1G72PDZ-2G1A1 8GB DIMM DDR4 2133MT/s              | 1        | 1.35%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s            | 1        | 1.35%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 26       | 46.43%  |
| DDR3    | 19       | 33.93%  |
| SDRAM   | 3        | 5.36%   |
| DDR     | 2        | 3.57%   |
| Unknown | 2        | 3.57%   |
| LPDDR4  | 1        | 1.79%   |
| DRAM    | 1        | 1.79%   |
| DDR5    | 1        | 1.79%   |
| DDR2    | 1        | 1.79%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 50       | 90.91%  |
| SODIMM | 5        | 9.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 19       | 30.65%  |
| 4096  | 17       | 27.42%  |
| 16384 | 14       | 22.58%  |
| 2048  | 5        | 8.06%   |
| 32768 | 2        | 3.23%   |
| 1024  | 2        | 3.23%   |
| 256   | 1        | 1.61%   |
| 128   | 1        | 1.61%   |
| 64    | 1        | 1.61%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 13       | 20.97%  |
| 2667    | 7        | 11.29%  |
| 2400    | 7        | 11.29%  |
| 1333    | 5        | 8.06%   |
| 3600    | 4        | 6.45%   |
| 3400    | 4        | 6.45%   |
| 2133    | 4        | 6.45%   |
| 1800    | 3        | 4.84%   |
| 3200    | 2        | 3.23%   |
| 1867    | 2        | 3.23%   |
| 667     | 2        | 3.23%   |
| Unknown | 2        | 3.23%   |
| 4800    | 1        | 1.61%   |
| 3666    | 1        | 1.61%   |
| 3534    | 1        | 1.61%   |
| 2933    | 1        | 1.61%   |
| 800     | 1        | 1.61%   |
| 400     | 1        | 1.61%   |
| 100     | 1        | 1.61%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Hewlett-Packard        | 1        | 33.33%  |
| Custom Engineering SPA | 1        | 33.33%  |
| Brother Industries     | 1        | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| HP ENVY 5000 series             | 1        | 33.33%  |
| Custom Engineering SPA KUBE USB | 1        | 33.33%  |
| Brother HL-L2375DW series       | 1        | 33.33%  |

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
| Logitech                    | 4        | 26.67%  |
| Cubeternet                  | 2        | 13.33%  |
| Z-Star Microelectronics     | 1        | 6.67%   |
| Softkinetic                 | 1        | 6.67%   |
| Realtek Semiconductor       | 1        | 6.67%   |
| Microsoft                   | 1        | 6.67%   |
| Microdia                    | 1        | 6.67%   |
| MacroSilicon                | 1        | 6.67%   |
| KYE Systems (Mouse Systems) | 1        | 6.67%   |
| Hauppauge                   | 1        | 6.67%   |
| GEMBIRD                     | 1        | 6.67%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Logitech Webcam C270                       | 2        | 13.33%  |
| Cubeternet GL-UPC822 UVC WebCam            | 2        | 13.33%  |
| Z-Star Vimicro USB Camera (Altair)         | 1        | 6.67%   |
| Softkinetic DepthSense 325                 | 1        | 6.67%   |
| Realtek HD 720P Webcam                     | 1        | 6.67%   |
| Microsoft LifeCam Studio                   | 1        | 6.67%   |
| Microdia Camera                            | 1        | 6.67%   |
| MacroSilicon USB Video                     | 1        | 6.67%   |
| Logitech C920 PRO HD Webcam                | 1        | 6.67%   |
| Logitech BRIO Ultra HD Webcam              | 1        | 6.67%   |
| KYE Systems (Mouse Systems) PC-LM1E Camera | 1        | 6.67%   |
| Hauppauge HD PVR Pro 60                    | 1        | 6.67%   |
| GEMBIRD USB2.0 PC CAMERA                   | 1        | 6.67%   |

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
| 0     | 48       | 81.36%  |
| 1     | 9        | 15.25%  |
| 2     | 2        | 3.39%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 5        | 38.46%  |
| Unassigned class         | 3        | 23.08%  |
| Communication controller | 2        | 15.38%  |
| Net/wireless             | 1        | 7.69%   |
| Net/ethernet             | 1        | 7.69%   |
| Firewire controller      | 1        | 7.69%   |

