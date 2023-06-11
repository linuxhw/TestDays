NixOS - Tested Hardware & Statistics (Desktops)
-----------------------------------------------

A project to collect tested hardware configurations for NixOS.

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

Total: 69

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | Aspire XC600 v1.0           | [754d228b9b](https://linux-hardware.org/?probe=754d228b9b) | Jun 09, 2023 |
| Gigabyte      | X570 AORUS PRO              | [309d09ae8c](https://linux-hardware.org/?probe=309d09ae8c) | Jun 03, 2023 |
| Gigabyte      | B450M DS3H-CF               | [c9c4e5ddb5](https://linux-hardware.org/?probe=c9c4e5ddb5) | May 26, 2023 |
| Gigabyte      | B450M DS3H-CF               | [cc8e36e75a](https://linux-hardware.org/?probe=cc8e36e75a) | May 26, 2023 |
| ASUSTek       | PRIME Z370-P II             | [4d84deed6b](https://linux-hardware.org/?probe=4d84deed6b) | May 09, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [29b2378b4b](https://linux-hardware.org/?probe=29b2378b4b) | May 08, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [62b28b69dc](https://linux-hardware.org/?probe=62b28b69dc) | May 08, 2023 |
| Gigabyte      | B760 GAMING X DDR4          | [6ee65c19d2](https://linux-hardware.org/?probe=6ee65c19d2) | May 02, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [493bc0b894](https://linux-hardware.org/?probe=493bc0b894) | Apr 29, 2023 |
| ASUSTek       | PRIME B350M-A               | [b8b51b29ef](https://linux-hardware.org/?probe=b8b51b29ef) | Apr 25, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [bbbc9206b4](https://linux-hardware.org/?probe=bbbc9206b4) | Apr 17, 2023 |
| MSI           | B550-A PRO                  | [c4f08a9fc3](https://linux-hardware.org/?probe=c4f08a9fc3) | Mar 04, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [c4d51ca1b8](https://linux-hardware.org/?probe=c4d51ca1b8) | Mar 04, 2023 |
| MSI           | Z77A-G43                    | [eb768bf205](https://linux-hardware.org/?probe=eb768bf205) | Feb 03, 2023 |
| Gigabyte      | B450M DS3H V2               | [75a3416ebc](https://linux-hardware.org/?probe=75a3416ebc) | Jan 31, 2023 |
| ASRock        | Z87 Extreme4                | [b795f7c940](https://linux-hardware.org/?probe=b795f7c940) | Jan 19, 2023 |
| ASRock        | B550M Pro4                  | [0e4ba05b0f](https://linux-hardware.org/?probe=0e4ba05b0f) | Jan 15, 2023 |
| Shenzhen M... | F7BFC                       | [6a53c626dd](https://linux-hardware.org/?probe=6a53c626dd) | Jan 02, 2023 |
| ASUSTek       | Z87-C                       | [4929f6a6c9](https://linux-hardware.org/?probe=4929f6a6c9) | Dec 28, 2022 |
| MSI           | B550-A PRO                  | [db7b91ac2f](https://linux-hardware.org/?probe=db7b91ac2f) | Dec 17, 2022 |
| ASUSTek       | PRIME B550M-A               | [3c18fca709](https://linux-hardware.org/?probe=3c18fca709) | Dec 09, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [6ffc032b64](https://linux-hardware.org/?probe=6ffc032b64) | Oct 25, 2022 |
| ASUSTek       | PRIME B550M-A               | [c203d7c388](https://linux-hardware.org/?probe=c203d7c388) | Oct 07, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [b21f5fee1a](https://linux-hardware.org/?probe=b21f5fee1a) | Sep 26, 2022 |
| ASUSTek       | PRIME B550M-A               | [98fd9b974e](https://linux-hardware.org/?probe=98fd9b974e) | Sep 09, 2022 |
| ASRock        | AB350 Pro4                  | [ce872c873e](https://linux-hardware.org/?probe=ce872c873e) | Aug 24, 2022 |
| ASUSTek       | H97I-PLUS                   | [982df0dba9](https://linux-hardware.org/?probe=982df0dba9) | Jun 22, 2022 |
| MSI           | MEG X570 UNIFY              | [6d5fdb800a](https://linux-hardware.org/?probe=6d5fdb800a) | Jun 20, 2022 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [a4621aa4ec](https://linux-hardware.org/?probe=a4621aa4ec) | Jun 19, 2022 |
| MSI           | MEG X570 UNIFY              | [d26f08ea88](https://linux-hardware.org/?probe=d26f08ea88) | Jun 12, 2022 |
| MSI           | MEG X570 UNIFY              | [0123caa2f3](https://linux-hardware.org/?probe=0123caa2f3) | Jun 11, 2022 |
| ASUSTek       | PRIME A520M-K               | [ab13de0478](https://linux-hardware.org/?probe=ab13de0478) | May 27, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [96b24b0640](https://linux-hardware.org/?probe=96b24b0640) | May 20, 2022 |
| ASUSTek       | PRIME X570-P                | [50d2e86de8](https://linux-hardware.org/?probe=50d2e86de8) | Apr 13, 2022 |
| Acer          | Nitro N50-610               | [46b46c842f](https://linux-hardware.org/?probe=46b46c842f) | Apr 13, 2022 |
| ASUSTek       | P8Q77-M                     | [6cd75b6762](https://linux-hardware.org/?probe=6cd75b6762) | Mar 11, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [815cb9ab49](https://linux-hardware.org/?probe=815cb9ab49) | Mar 11, 2022 |
| MSI           | B450M MORTAR MAX            | [1d6563ada3](https://linux-hardware.org/?probe=1d6563ada3) | Mar 11, 2022 |
| ASUSTek       | P8Z77-V LK                  | [5c984c6d9a](https://linux-hardware.org/?probe=5c984c6d9a) | Mar 09, 2022 |
| ASUSTek       | P8Z77-V LK                  | [40d2eced72](https://linux-hardware.org/?probe=40d2eced72) | Mar 09, 2022 |
| EVGA          | X299 FTW K                  | [6f9489b2e6](https://linux-hardware.org/?probe=6f9489b2e6) | Mar 09, 2022 |
| Dell          | 0KJCC5 A00                  | [524b675e7e](https://linux-hardware.org/?probe=524b675e7e) | Mar 09, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [f38279e396](https://linux-hardware.org/?probe=f38279e396) | Mar 09, 2022 |
| MSI           | X399 SLI PLUS               | [a1d172dbc0](https://linux-hardware.org/?probe=a1d172dbc0) | Feb 16, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [c84b603f92](https://linux-hardware.org/?probe=c84b603f92) | Jan 04, 2022 |
| ASUSTek       | Z170-P                      | [d4bac456d1](https://linux-hardware.org/?probe=d4bac456d1) | Dec 16, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [eb5d5f4361](https://linux-hardware.org/?probe=eb5d5f4361) | Dec 12, 2021 |
| ASUSTek       | PRIME Z390-A                | [af887c3f7b](https://linux-hardware.org/?probe=af887c3f7b) | Nov 29, 2021 |
| Gigabyte      | H97M-D3H                    | [349fbeb586](https://linux-hardware.org/?probe=349fbeb586) | Oct 23, 2021 |
| MSI           | X399 SLI PLUS               | [128ae965a7](https://linux-hardware.org/?probe=128ae965a7) | Aug 06, 2021 |
| ASRock        | X570 Taichi                 | [d93a80d973](https://linux-hardware.org/?probe=d93a80d973) | Jul 14, 2021 |
| ASRock        | X570 Taichi                 | [59a699d357](https://linux-hardware.org/?probe=59a699d357) | Jul 14, 2021 |
| ASUSTek       | SABERTOOTH X99              | [60eed45305](https://linux-hardware.org/?probe=60eed45305) | Jun 18, 2021 |
| MSI           | X570-A PRO                  | [0619809b36](https://linux-hardware.org/?probe=0619809b36) | Jun 01, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | [6056eac50c](https://linux-hardware.org/?probe=6056eac50c) | May 31, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | [bd9fb4818b](https://linux-hardware.org/?probe=bd9fb4818b) | May 31, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | [12fa3ffea5](https://linux-hardware.org/?probe=12fa3ffea5) | May 31, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [f03b19461f](https://linux-hardware.org/?probe=f03b19461f) | May 16, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [529e915984](https://linux-hardware.org/?probe=529e915984) | May 16, 2021 |
| ASUSTek       | Pro WS W480-ACE             | [3825190816](https://linux-hardware.org/?probe=3825190816) | Mar 11, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [d55d51a3e2](https://linux-hardware.org/?probe=d55d51a3e2) | Feb 08, 2021 |
| MSI           | MPG X570 GAMING PLUS        | [188755ebc7](https://linux-hardware.org/?probe=188755ebc7) | Oct 25, 2020 |
| Hardkernel    | ODROID-H2                   | [a5d75a24e5](https://linux-hardware.org/?probe=a5d75a24e5) | Oct 13, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | [b85fb81c59](https://linux-hardware.org/?probe=b85fb81c59) | Sep 28, 2020 |
| MSI           | MAG B550M BAZOOKA           | [5f7f2db973](https://linux-hardware.org/?probe=5f7f2db973) | Aug 21, 2020 |
| ASUSTek       | PRIME Z270-K                | [cc8de41afd](https://linux-hardware.org/?probe=cc8de41afd) | Aug 21, 2020 |
| HP            | 8055                        | [1165b457fa](https://linux-hardware.org/?probe=1165b457fa) | Jul 08, 2020 |
| HP            | 8055                        | [a5c65e8d4a](https://linux-hardware.org/?probe=a5c65e8d4a) | Jul 08, 2020 |
| ASRock        | TRX40 Creator               | [2cefd65bfb](https://linux-hardware.org/?probe=2cefd65bfb) | Jun 29, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| NixOS 22.05                      | 13       | 22.41%  |
| NixOS 22.11                      | 11       | 18.97%  |
| NixOS 23.05                      | 7        | 12.07%  |
| NixOS 21.11                      | 7        | 12.07%  |
| NixOS                            | 3        | 5.17%   |
| NixOS 23.11                      | 2        | 3.45%   |
| NixOS 21.05pre-git               | 2        | 3.45%   |
| NixOS 21.11.20210528.540dccb     | 1        | 1.72%   |
| NixOS 21.05.993.93963c27b93      | 1        | 1.72%   |
| NixOS 21.05.2075.ff1ea3a36c1     | 1        | 1.72%   |
| NixOS 21.05.20210929.ee90403     | 1        | 1.72%   |
| NixOS 21.05.20210430.c8dff32     | 1        | 1.72%   |
| NixOS 21.05.20210224.f6b5bfd     | 1        | 1.72%   |
| NixOS 21.05.1471.a7512bb64b1     | 1        | 1.72%   |
| NixOS 21.03pre246062.420f89ceb26 | 1        | 1.72%   |
| NixOS 21.03.git.b4349c13a6d      | 1        | 1.72%   |
| NixOS 21.03.20201007.420f89c     | 1        | 1.72%   |
| NixOS 20.09pre231796.22a81aa5fc1 | 1        | 1.72%   |
| NixOS 20.09pre-git               | 1        | 1.72%   |
| NixOS 20.09.git.4a361b06a93      | 1        | 1.72%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| NixOS | 55       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version      | Desktops | Percent |
|--------------|----------|---------|
| 5.8.1-zen1   | 2        | 3.39%   |
| 5.15.86      | 2        | 3.39%   |
| 5.15.85      | 2        | 3.39%   |
| 5.15.47      | 2        | 3.39%   |
| 5.10.102     | 2        | 3.39%   |
| 6.3.3        | 1        | 1.69%   |
| 6.2.11-lqx3  | 1        | 1.69%   |
| 6.2.11       | 1        | 1.69%   |
| 6.2.10       | 1        | 1.69%   |
| 6.1.31       | 1        | 1.69%   |
| 6.1.27       | 1        | 1.69%   |
| 6.1.24       | 1        | 1.69%   |
| 6.1.14       | 1        | 1.69%   |
| 6.0.12       | 1        | 1.69%   |
| 6.0.11       | 1        | 1.69%   |
| 5.8.10       | 1        | 1.69%   |
| 5.7.19       | 1        | 1.69%   |
| 5.4.94       | 1        | 1.69%   |
| 5.4.72       | 1        | 1.69%   |
| 5.4.69       | 1        | 1.69%   |
| 5.4.50       | 1        | 1.69%   |
| 5.4.47       | 1        | 1.69%   |
| 5.19.14      | 1        | 1.69%   |
| 5.18.19      | 1        | 1.69%   |
| 5.18.14-lqx2 | 1        | 1.69%   |
| 5.17.1       | 1        | 1.69%   |
| 5.16.8-zen1  | 1        | 1.69%   |
| 5.15.95      | 1        | 1.69%   |
| 5.15.90      | 1        | 1.69%   |
| 5.15.83      | 1        | 1.69%   |
| 5.15.74      | 1        | 1.69%   |
| 5.15.7       | 1        | 1.69%   |
| 5.15.50      | 1        | 1.69%   |
| 5.15.43      | 1        | 1.69%   |
| 5.15.39      | 1        | 1.69%   |
| 5.15.34      | 1        | 1.69%   |
| 5.15.26      | 1        | 1.69%   |
| 5.15.25      | 1        | 1.69%   |
| 5.15.18      | 1        | 1.69%   |
| 5.15.110     | 1        | 1.69%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 6.2.11   | 2        | 3.39%   |
| 5.8.1    | 2        | 3.39%   |
| 5.15.86  | 2        | 3.39%   |
| 5.15.85  | 2        | 3.39%   |
| 5.15.47  | 2        | 3.39%   |
| 5.11.16  | 2        | 3.39%   |
| 5.10.102 | 2        | 3.39%   |
| 6.3.3    | 1        | 1.69%   |
| 6.2.10   | 1        | 1.69%   |
| 6.1.31   | 1        | 1.69%   |
| 6.1.27   | 1        | 1.69%   |
| 6.1.24   | 1        | 1.69%   |
| 6.1.14   | 1        | 1.69%   |
| 6.0.12   | 1        | 1.69%   |
| 6.0.11   | 1        | 1.69%   |
| 5.8.10   | 1        | 1.69%   |
| 5.7.19   | 1        | 1.69%   |
| 5.4.94   | 1        | 1.69%   |
| 5.4.72   | 1        | 1.69%   |
| 5.4.69   | 1        | 1.69%   |
| 5.4.50   | 1        | 1.69%   |
| 5.4.47   | 1        | 1.69%   |
| 5.19.14  | 1        | 1.69%   |
| 5.18.19  | 1        | 1.69%   |
| 5.18.14  | 1        | 1.69%   |
| 5.17.1   | 1        | 1.69%   |
| 5.16.8   | 1        | 1.69%   |
| 5.15.95  | 1        | 1.69%   |
| 5.15.90  | 1        | 1.69%   |
| 5.15.83  | 1        | 1.69%   |
| 5.15.74  | 1        | 1.69%   |
| 5.15.7   | 1        | 1.69%   |
| 5.15.50  | 1        | 1.69%   |
| 5.15.43  | 1        | 1.69%   |
| 5.15.39  | 1        | 1.69%   |
| 5.15.34  | 1        | 1.69%   |
| 5.15.26  | 1        | 1.69%   |
| 5.15.25  | 1        | 1.69%   |
| 5.15.18  | 1        | 1.69%   |
| 5.15.110 | 1        | 1.69%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 21       | 35.59%  |
| 5.10    | 9        | 15.25%  |
| 5.4     | 5        | 8.47%   |
| 6.1     | 4        | 6.78%   |
| 6.2     | 3        | 5.08%   |
| 5.8     | 3        | 5.08%   |
| 6.0     | 2        | 3.39%   |
| 5.18    | 2        | 3.39%   |
| 5.11    | 2        | 3.39%   |
| 6.3     | 1        | 1.69%   |
| 5.7     | 1        | 1.69%   |
| 5.19    | 1        | 1.69%   |
| 5.17    | 1        | 1.69%   |
| 5.16    | 1        | 1.69%   |
| 5.14    | 1        | 1.69%   |
| 5.13    | 1        | 1.69%   |
| 5.12    | 1        | 1.69%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 55       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Unknown      | 32       | 58.18%  |
| KDE5         | 5        | 9.09%   |
| GNOME        | 4        | 7.27%   |
| XFCE         | 3        | 5.45%   |
| sway         | 3        | 5.45%   |
| KDE          | 3        | 5.45%   |
| Hyprland     | 2        | 3.64%   |
| none+i3      | 1        | 1.82%   |
| none+awesome | 1        | 1.82%   |
| MATE         | 1        | 1.82%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 30       | 53.57%  |
| X11     | 14       | 25%     |
| Wayland | 8        | 14.29%  |
| Tty     | 4        | 7.14%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 35       | 63.64%  |
| LightDM | 10       | 18.18%  |
| SDDM    | 6        | 10.91%  |
| GDM     | 4        | 7.27%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| en_US      | 21       | 38.18%  |
| Unknown    | 20       | 36.36%  |
| en_GB      | 4        | 7.27%   |
| en_DK      | 2        | 3.64%   |
| en_AU      | 2        | 3.64%   |
| ru_RU      | 1        | 1.82%   |
| pt_BR      | 1        | 1.82%   |
| it_IT      | 1        | 1.82%   |
| en_IE.UTF8 | 1        | 1.82%   |
| de_DE      | 1        | 1.82%   |
| de_CH      | 1        | 1.82%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 47       | 83.93%  |
| BIOS | 9        | 16.07%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 30       | 54.55%  |
| Zfs     | 6        | 10.91%  |
| Btrfs   | 6        | 10.91%  |
| Tmpfs   | 5        | 9.09%   |
| Xfs     | 4        | 7.27%   |
| Unknown | 3        | 5.45%   |
| Ext2    | 1        | 1.82%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 53       | 96.36%  |
| Unknown | 2        | 3.64%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 42       | 75%     |
| Yes       | 14       | 25%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 31       | 56.36%  |
| Yes       | 24       | 43.64%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 21       | 38.18%  |
| MSI                                  | 11       | 20%     |
| Gigabyte Technology                  | 10       | 18.18%  |
| ASRock                               | 6        | 10.91%  |
| Acer                                 | 2        | 3.64%   |
| Shenzhen Meigao Electronic Equipment | 1        | 1.82%   |
| Hewlett-Packard                      | 1        | 1.82%   |
| Hardkernel                           | 1        | 1.82%   |
| EVGA                                 | 1        | 1.82%   |
| Dell                                 | 1        | 1.82%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| MSI MS-7C56                                | 2        | 3.64%   |
| MSI MS-7C37                                | 2        | 3.64%   |
| Gigabyte B550I AORUS PRO AX                | 2        | 3.64%   |
| Gigabyte B450M DS3H                        | 2        | 3.64%   |
| ASUS ROG STRIX B550-F GAMING               | 2        | 3.64%   |
| ASUS All Series                            | 2        | 3.64%   |
| Shenzhen Meigao Electronic Equipment UM690 | 1        | 1.82%   |
| MSI MS-7C95                                | 1        | 1.82%   |
| MSI MS-7C91                                | 1        | 1.82%   |
| MSI MS-7C84                                | 1        | 1.82%   |
| MSI MS-7C35                                | 1        | 1.82%   |
| MSI MS-7B89                                | 1        | 1.82%   |
| MSI MS-7B09                                | 1        | 1.82%   |
| MSI MS-7758                                | 1        | 1.82%   |
| HP EliteDesk 800 G2 DM 35W                 | 1        | 1.82%   |
| Hardkernel ODROID-H2                       | 1        | 1.82%   |
| Gigabyte X570 AORUS PRO                    | 1        | 1.82%   |
| Gigabyte X570 AORUS ELITE                  | 1        | 1.82%   |
| Gigabyte X470 AORUS ULTRA GAMING           | 1        | 1.82%   |
| Gigabyte H97M-D3H                          | 1        | 1.82%   |
| Gigabyte B760 GAMING X DDR4                | 1        | 1.82%   |
| Gigabyte B450M DS3H V2                     | 1        | 1.82%   |
| EVGA X299 FTW K                            | 1        | 1.82%   |
| Dell Precision Tower 7810                  | 1        | 1.82%   |
| ASUS Z170-P                                | 1        | 1.82%   |
| ASUS TUF Gaming X570-PLUS                  | 1        | 1.82%   |
| ASUS SABERTOOTH 990FX R2.0                 | 1        | 1.82%   |
| ASUS ROG STRIX Z390-F GAMING               | 1        | 1.82%   |
| ASUS ROG STRIX B650E-F GAMING WIFI         | 1        | 1.82%   |
| ASUS ROG STRIX B550-I GAMING               | 1        | 1.82%   |
| ASUS PRO602617                             | 1        | 1.82%   |
| ASUS PRO-Q77 IU                            | 1        | 1.82%   |
| ASUS Pro WS W480-ACE                       | 1        | 1.82%   |
| ASUS PRIME Z390-A                          | 1        | 1.82%   |
| ASUS PRIME Z370-P II                       | 1        | 1.82%   |
| ASUS PRIME Z270-K                          | 1        | 1.82%   |
| ASUS PRIME X570-P                          | 1        | 1.82%   |
| ASUS PRIME B550M-A                         | 1        | 1.82%   |
| ASUS PRIME B350M-A                         | 1        | 1.82%   |
| ASUS PRIME A520M-K                         | 1        | 1.82%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| ASUS PRIME                                 | 7        | 12.73%  |
| ASUS ROG                                   | 5        | 9.09%   |
| Gigabyte B450M                             | 3        | 5.45%   |
| MSI MS-7C56                                | 2        | 3.64%   |
| MSI MS-7C37                                | 2        | 3.64%   |
| Gigabyte X570                              | 2        | 3.64%   |
| Gigabyte B550I                             | 2        | 3.64%   |
| ASUS All                                   | 2        | 3.64%   |
| Shenzhen Meigao Electronic Equipment UM690 | 1        | 1.82%   |
| MSI MS-7C95                                | 1        | 1.82%   |
| MSI MS-7C91                                | 1        | 1.82%   |
| MSI MS-7C84                                | 1        | 1.82%   |
| MSI MS-7C35                                | 1        | 1.82%   |
| MSI MS-7B89                                | 1        | 1.82%   |
| MSI MS-7B09                                | 1        | 1.82%   |
| MSI MS-7758                                | 1        | 1.82%   |
| HP EliteDesk                               | 1        | 1.82%   |
| Hardkernel ODROID-H2                       | 1        | 1.82%   |
| Gigabyte X470                              | 1        | 1.82%   |
| Gigabyte H97M-D3H                          | 1        | 1.82%   |
| Gigabyte B760                              | 1        | 1.82%   |
| EVGA X299                                  | 1        | 1.82%   |
| Dell Precision                             | 1        | 1.82%   |
| ASUS Z170-P                                | 1        | 1.82%   |
| ASUS TUF                                   | 1        | 1.82%   |
| ASUS SABERTOOTH                            | 1        | 1.82%   |
| ASUS PRO602617                             | 1        | 1.82%   |
| ASUS PRO-Q77                               | 1        | 1.82%   |
| ASUS Pro                                   | 1        | 1.82%   |
| ASUS P8Z77-V                               | 1        | 1.82%   |
| ASRock Z87                                 | 1        | 1.82%   |
| ASRock X570                                | 1        | 1.82%   |
| ASRock TRX40                               | 1        | 1.82%   |
| ASRock B550M                               | 1        | 1.82%   |
| ASRock B450                                | 1        | 1.82%   |
| ASRock AB350                               | 1        | 1.82%   |
| Acer Nitro                                 | 1        | 1.82%   |
| Acer Aspire                                | 1        | 1.82%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 16       | 29.09%  |
| 2019 | 11       | 20%     |
| 2018 | 8        | 14.55%  |
| 2016 | 4        | 7.27%   |
| 2012 | 4        | 7.27%   |
| 2022 | 3        | 5.45%   |
| 2017 | 3        | 5.45%   |
| 2015 | 2        | 3.64%   |
| 2014 | 2        | 3.64%   |
| 2013 | 2        | 3.64%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 55       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 55       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 55       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 32.01-64.0  | 16       | 29.09%  |
| 64.01-256.0 | 16       | 29.09%  |
| 16.01-24.0  | 12       | 21.82%  |
| 24.01-32.0  | 5        | 9.09%   |
| 4.01-8.0    | 3        | 5.45%   |
| 8.01-16.0   | 3        | 5.45%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 18       | 32.14%  |
| 8.01-16.0  | 12       | 21.43%  |
| 32.01-64.0 | 6        | 10.71%  |
| 3.01-4.0   | 6        | 10.71%  |
| 1.01-2.0   | 6        | 10.71%  |
| 16.01-24.0 | 4        | 7.14%   |
| 2.01-3.0   | 2        | 3.57%   |
| 24.01-32.0 | 1        | 1.79%   |
| 0.51-1.0   | 1        | 1.79%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 19       | 32.76%  |
| 1      | 13       | 22.41%  |
| 3      | 11       | 18.97%  |
| 6      | 4        | 6.9%    |
| 5      | 4        | 6.9%    |
| 4      | 3        | 5.17%   |
| 23     | 1        | 1.72%   |
| 8      | 1        | 1.72%   |
| 7      | 1        | 1.72%   |
| 0      | 1        | 1.72%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 47       | 85.45%  |
| Yes       | 8        | 14.55%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 55       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 35       | 63.64%  |
| Yes       | 20       | 36.36%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 33       | 60%     |
| Yes       | 22       | 40%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 13       | 23.64%  |
| Germany     | 9        | 16.36%  |
| UK          | 5        | 9.09%   |
| Russia      | 3        | 5.45%   |
| Poland      | 3        | 5.45%   |
| Canada      | 3        | 5.45%   |
| Ukraine     | 2        | 3.64%   |
| Italy       | 2        | 3.64%   |
| Denmark     | 2        | 3.64%   |
| Brazil      | 2        | 3.64%   |
| Austria     | 2        | 3.64%   |
| Australia   | 2        | 3.64%   |
| Switzerland | 1        | 1.82%   |
| Serbia      | 1        | 1.82%   |
| New Zealand | 1        | 1.82%   |
| Netherlands | 1        | 1.82%   |
| India       | 1        | 1.82%   |
| Hungary     | 1        | 1.82%   |
| France      | 1        | 1.82%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Vienna            | 2        | 3.57%   |
| Schaafheim        | 2        | 3.57%   |
| Plymouth          | 2        | 3.57%   |
| Marki             | 2        | 3.57%   |
| Kharkiv           | 2        | 3.57%   |
| Darmstadt         | 2        | 3.57%   |
| Austin            | 2        | 3.57%   |
| Wellington        | 1        | 1.79%   |
| Székesfehérvár | 1        | 1.79%   |
| Southampton       | 1        | 1.79%   |
| South Deerfield   | 1        | 1.79%   |
| Sorocaba          | 1        | 1.79%   |
| Sindelfingen      | 1        | 1.79%   |
| San Gabriel       | 1        | 1.79%   |
| Saarbrücken      | 1        | 1.79%   |
| Richardson        | 1        | 1.79%   |
| Redwood City      | 1        | 1.79%   |
| Ramenskoye        | 1        | 1.79%   |
| Pisa              | 1        | 1.79%   |
| Osasco            | 1        | 1.79%   |
| Oakville          | 1        | 1.79%   |
| Norwich           | 1        | 1.79%   |
| North Andover     | 1        | 1.79%   |
| Montreal          | 1        | 1.79%   |
| Melrose           | 1        | 1.79%   |
| Melbourne         | 1        | 1.79%   |
| Landorthe         | 1        | 1.79%   |
| Lamont            | 1        | 1.79%   |
| Kuybyshev         | 1        | 1.79%   |
| Krasnodar         | 1        | 1.79%   |
| Karlsruhe         | 1        | 1.79%   |
| Hobart            | 1        | 1.79%   |
| Heusweiler        | 1        | 1.79%   |
| Hamburg           | 1        | 1.79%   |
| Goleta            | 1        | 1.79%   |
| Gdansk            | 1        | 1.79%   |
| Esbjerg           | 1        | 1.79%   |
| Dietikon          | 1        | 1.79%   |
| Didcot            | 1        | 1.79%   |
| Detroit           | 1        | 1.79%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| Samsung Electronics   | 31       | 60     | 28.97%  |
| Seagate               | 14       | 23     | 13.08%  |
| WDC                   | 12       | 29     | 11.21%  |
| SanDisk               | 10       | 14     | 9.35%   |
| Toshiba               | 8        | 19     | 7.48%   |
| Crucial               | 7        | 8      | 6.54%   |
| Kingston              | 5        | 5      | 4.67%   |
| Intel                 | 4        | 6      | 3.74%   |
| Realtek Semiconductor | 2        | 2      | 1.87%   |
| Phison Electronics    | 2        | 4      | 1.87%   |
| Hitachi               | 2        | 4      | 1.87%   |
| HGST                  | 2        | 4      | 1.87%   |
| SPCC                  | 1        | 1      | 0.93%   |
| Silicon Motion        | 1        | 1      | 0.93%   |
| Plextor               | 1        | 1      | 0.93%   |
| Phison                | 1        | 1      | 0.93%   |
| Lexar                 | 1        | 1      | 0.93%   |
| Corsair               | 1        | 1      | 0.93%   |
| China                 | 1        | 1      | 0.93%   |
| ASMT                  | 1        | 1      | 0.93%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Samsung SSD 860 QVO 1TB                             | 4        | 2.78%   |
| Samsung SSD 860 EVO 1TB                             | 4        | 2.78%   |
| Seagate ST3000DM001-1ER166 3TB                      | 3        | 2.08%   |
| SanDisk SSD PLUS 240GB                              | 3        | 2.08%   |
| Samsung SSD 970 EVO Plus 2TB                        | 3        | 2.08%   |
| Samsung SSD 860 EVO 500GB                           | 3        | 2.08%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 3        | 2.08%   |
| Seagate ST3000DM001-1CH166 3TB                      | 2        | 1.39%   |
| Samsung SSD 980 PRO 1TB                             | 2        | 1.39%   |
| Samsung SSD 970 EVO Plus 1TB                        | 2        | 1.39%   |
| Samsung SSD 970 EVO 500GB                           | 2        | 1.39%   |
| Samsung SSD 970 EVO 1TB                             | 2        | 1.39%   |
| Samsung SSD 860 EVO 2TB                             | 2        | 1.39%   |
| Samsung NVMe SSD Drive 1TB                          | 2        | 1.39%   |
| Crucial CT1000MX500SSD1 1TB                         | 2        | 1.39%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                    | 1        | 0.69%   |
| WDC WD80EMAZ-00WJTA0 8TB                            | 1        | 0.69%   |
| WDC WD80EDAZ-11TA3A0 8TB                            | 1        | 0.69%   |
| WDC WD50EZRX-00MVLB1 5TB                            | 1        | 0.69%   |
| WDC WD40EFRX-68N32N0 4TB                            | 1        | 0.69%   |
| WDC WD3200BPVT-22JJ5T0 320GB                        | 1        | 0.69%   |
| WDC WD20EZRZ-00Z5HB0 2TB                            | 1        | 0.69%   |
| WDC WD20EZRX-00D8PB0 2TB                            | 1        | 0.69%   |
| WDC WD20EARX-008FB0 2TB                             | 1        | 0.69%   |
| WDC WD1600AAJS-62B4A0 160GB                         | 1        | 0.69%   |
| WDC WD10EZEX-60ZF5A0 1TB                            | 1        | 0.69%   |
| WDC WD10EZEX-21WN4A0 1TB                            | 1        | 0.69%   |
| WDC WD10EZEX-00RKKA0 1TB                            | 1        | 0.69%   |
| WDC WD10EZEX-00KUWA0 1TB                            | 1        | 0.69%   |
| WDC WD10EAVS-32D7B1 1TB                             | 1        | 0.69%   |
| WDC WD10EAVS-00D7B0 1TB                             | 1        | 0.69%   |
| WDC WD10EARS-00Y5B1 1TB                             | 1        | 0.69%   |
| WDC WD10EADS-00M2B0 1TB                             | 1        | 0.69%   |
| Toshiba TR150 960GB SSD                             | 1        | 0.69%   |
| Toshiba MG03ACA300 3TB                              | 1        | 0.69%   |
| Toshiba HDWR180 8TB                                 | 1        | 0.69%   |
| Toshiba HDWL120 2TB                                 | 1        | 0.69%   |
| Toshiba HDWG180 8TB                                 | 1        | 0.69%   |
| Toshiba HDWE160 6TB                                 | 1        | 0.69%   |
| Toshiba HDWD130 3TB                                 | 1        | 0.69%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 14       | 23     | 35.9%   |
| WDC                 | 12       | 27     | 30.77%  |
| Toshiba             | 7        | 15     | 17.95%  |
| Samsung Electronics | 2        | 2      | 5.13%   |
| Hitachi             | 2        | 4      | 5.13%   |
| HGST                | 2        | 4      | 5.13%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 16       | 27     | 37.21%  |
| Crucial             | 7        | 8      | 16.28%  |
| SanDisk             | 6        | 9      | 13.95%  |
| Kingston            | 4        | 4      | 9.3%    |
| Intel               | 4        | 6      | 9.3%    |
| WDC                 | 1        | 2      | 2.33%   |
| Toshiba             | 1        | 1      | 2.33%   |
| SPCC                | 1        | 1      | 2.33%   |
| Corsair             | 1        | 1      | 2.33%   |
| China               | 1        | 1      | 2.33%   |
| ASMT                | 1        | 1      | 2.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 36       | 61     | 38.71%  |
| NVMe | 32       | 50     | 34.41%  |
| HDD  | 25       | 75     | 26.88%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 45       | 134    | 56.96%  |
| NVMe | 32       | 50     | 40.51%  |
| SAS  | 2        | 2      | 2.53%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 27       | 41     | 36.99%  |
| 0.51-1.0   | 22       | 43     | 30.14%  |
| 1.01-2.0   | 9        | 14     | 12.33%  |
| 4.01-10.0  | 7        | 22     | 9.59%   |
| 2.01-3.0   | 6        | 12     | 8.22%   |
| 3.01-4.0   | 2        | 4      | 2.74%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 24       | 43.64%  |
| 1-20           | 8        | 14.55%  |
| 501-1000       | 7        | 12.73%  |
| 1001-2000      | 4        | 7.27%   |
| More than 3000 | 3        | 5.45%   |
| 251-500        | 3        | 5.45%   |
| 2001-3000      | 3        | 5.45%   |
| 101-250        | 3        | 5.45%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 24       | 43.64%  |
| 1-20           | 12       | 21.82%  |
| 101-250        | 5        | 9.09%   |
| 1001-2000      | 3        | 5.45%   |
| 501-1000       | 3        | 5.45%   |
| 51-100         | 3        | 5.45%   |
| More than 3000 | 2        | 3.64%   |
| 251-500        | 2        | 3.64%   |
| 2001-3000      | 1        | 1.82%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| WDC WD20EZRZ-00Z5HB0 2TB            | 1        | 1      | 9.09%   |
| WDC WD20EARX-008FB0 2TB             | 1        | 1      | 9.09%   |
| WDC WD10EZEX-60ZF5A0 1TB            | 1        | 1      | 9.09%   |
| Seagate ST3500418AS 500GB           | 1        | 1      | 9.09%   |
| SanDisk SSD PLUS 240GB              | 1        | 1      | 9.09%   |
| Samsung Electronics SSD 970 EVO 1TB | 1        | 1      | 9.09%   |
| Samsung Electronics SSD 870 EVO 1TB | 1        | 1      | 9.09%   |
| Intel SSDSC2BW240A4 240GB           | 1        | 1      | 9.09%   |
| Hitachi HDS722020ALA330 2TB         | 1        | 1      | 9.09%   |
| HGST HTS545050A7E680 500GB          | 1        | 1      | 9.09%   |
| ASMT 2115 160GB                     | 1        | 1      | 9.09%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 3        | 3      | 27.27%  |
| Samsung Electronics | 2        | 2      | 18.18%  |
| Seagate             | 1        | 1      | 9.09%   |
| SanDisk             | 1        | 1      | 9.09%   |
| Intel               | 1        | 1      | 9.09%   |
| Hitachi             | 1        | 1      | 9.09%   |
| HGST                | 1        | 1      | 9.09%   |
| ASMT                | 1        | 1      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 3        | 3      | 50%     |
| Seagate | 1        | 1      | 16.67%  |
| Hitachi | 1        | 1      | 16.67%  |
| HGST    | 1        | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 5        | 6      | 50%     |
| SSD  | 4        | 4      | 40%     |
| NVMe | 1        | 1      | 10%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                  | Desktops | Drives | Percent |
|------------------------|----------|--------|---------|
| Toshiba MG03ACA300 3TB | 1        | 1      | 50%     |
| Toshiba HDWG180 8TB    | 1        | 4      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Toshiba | 2        | 5      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 53       | 159    | 77.94%  |
| Malfunc  | 8        | 11     | 11.76%  |
| Detected | 5        | 11     | 7.35%   |
| Failed   | 2        | 5      | 2.94%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| AMD                          | 33       | 34.02%  |
| Intel                        | 21       | 21.65%  |
| Samsung Electronics          | 20       | 20.62%  |
| ASMedia Technology           | 5        | 5.15%   |
| SanDisk                      | 4        | 4.12%   |
| Phison Electronics           | 3        | 3.09%   |
| Realtek Semiconductor        | 2        | 2.06%   |
| LSI Logic / Symbios Logic    | 2        | 2.06%   |
| Kingston Technology Company  | 2        | 2.06%   |
| Toshiba America Info Systems | 1        | 1.03%   |
| Silicon Motion               | 1        | 1.03%   |
| Shenzhen Longsys Electronics | 1        | 1.03%   |
| Lite-On Technology           | 1        | 1.03%   |
| Broadcom / LSI               | 1        | 1.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 19       | 17.59%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 15       | 13.89%  |
| AMD 500 Series Chipset SATA Controller                                         | 12       | 11.11%  |
| AMD 400 Series Chipset SATA Controller                                         | 6        | 5.56%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 5        | 4.63%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 3        | 2.78%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 3        | 2.78%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2        | 1.85%   |
| Samsung NVMe SSD Controller 980                                                | 2        | 1.85%   |
| Phison E12 NVMe Controller                                                     | 2        | 1.85%   |
| Kingston Company A2000 NVMe SSD                                                | 2        | 1.85%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2        | 1.85%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2        | 1.85%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 2        | 1.85%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2        | 1.85%   |
| AMD 300 Series Chipset SATA Controller                                         | 2        | 1.85%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 1        | 0.93%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1        | 0.93%   |
| Shenzhen Longsys Electronics Non-Volatile memory controller                    | 1        | 0.93%   |
| Sandisk Western Digital WD Black SN850X NVMe SSD                               | 1        | 0.93%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1        | 0.93%   |
| SanDisk WD Black SN770 NVMe SSD                                                | 1        | 0.93%   |
| SanDisk Non-Volatile memory controller                                         | 1        | 0.93%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1        | 0.93%   |
| Samsung Electronics Non-Volatile memory controller                             | 1        | 0.93%   |
| Realtek RTS5763DL NVMe SSD Controller                                          | 1        | 0.93%   |
| Realtek NVMe Controller                                                        | 1        | 0.93%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1        | 0.93%   |
| LSI Logic / Symbios Logic SAS2308 PCI-Express Fusion-MPT SAS-2                 | 1        | 0.93%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]        | 1        | 0.93%   |
| Lite-On Non-Volatile memory controller                                         | 1        | 0.93%   |
| Intel SATA Controller [RAID mode]                                              | 1        | 0.93%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1        | 0.93%   |
| Intel Comet Lake PCH-H RAID                                                    | 1        | 0.93%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1        | 0.93%   |
| Intel C610/X99 series chipset IDE-r Controller                                 | 1        | 0.93%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 1        | 0.93%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 1        | 0.93%   |
| Intel 700 Series Chipset Family SATA AHCI Controller                           | 1        | 0.93%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 1        | 0.93%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 52       | 57.14%  |
| NVMe | 33       | 36.26%  |
| SAS  | 3        | 3.3%    |
| RAID | 2        | 2.2%    |
| IDE  | 1        | 1.1%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 34       | 61.82%  |
| Intel  | 21       | 38.18%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor              | 5        | 9.09%   |
| AMD Ryzen 9 5950X 16-Core Processor            | 3        | 5.45%   |
| AMD Ryzen 7 3800X 8-Core Processor             | 3        | 5.45%   |
| AMD Ryzen 5 5600G with Radeon Graphics         | 3        | 5.45%   |
| Intel Core i7-8700K CPU @ 3.70GHz              | 2        | 3.64%   |
| AMD Ryzen 9 5900X 12-Core Processor            | 2        | 3.64%   |
| AMD Ryzen 5 5600X 6-Core Processor             | 2        | 3.64%   |
| AMD Ryzen 5 3600X 6-Core Processor             | 2        | 3.64%   |
| AMD Ryzen 5 1600 Six-Core Processor            | 2        | 3.64%   |
| Intel Xeon W-1290P CPU @ 3.70GHz               | 1        | 1.82%   |
| Intel Xeon CPU E5-2680 v3 @ 2.50GHz            | 1        | 1.82%   |
| Intel Core i9-9900X CPU @ 3.50GHz              | 1        | 1.82%   |
| Intel Core i7-8700 CPU @ 3.20GHz               | 1        | 1.82%   |
| Intel Core i7-6850K CPU @ 3.60GHz              | 1        | 1.82%   |
| Intel Core i7-4790 CPU @ 3.60GHz               | 1        | 1.82%   |
| Intel Core i7-4770 CPU @ 3.40GHz               | 1        | 1.82%   |
| Intel Core i7-3770 CPU @ 3.40GHz               | 1        | 1.82%   |
| Intel Core i5-7600K CPU @ 3.80GHz              | 1        | 1.82%   |
| Intel Core i5-6500T CPU @ 2.50GHz              | 1        | 1.82%   |
| Intel Core i5-4570S CPU @ 2.90GHz              | 1        | 1.82%   |
| Intel Core i5-4570 CPU @ 3.20GHz               | 1        | 1.82%   |
| Intel Core i5-3570K CPU @ 3.40GHz              | 1        | 1.82%   |
| Intel Core i5-3470T CPU @ 2.90GHz              | 1        | 1.82%   |
| Intel Core i5-3470 CPU @ 3.20GHz               | 1        | 1.82%   |
| Intel Core i5-10400F CPU @ 2.90GHz             | 1        | 1.82%   |
| Intel Core i3-6100 CPU @ 3.70GHz               | 1        | 1.82%   |
| Intel Celeron J4105 CPU @ 1.50GHz              | 1        | 1.82%   |
| Intel 13th Gen Core i5-13600KF                 | 1        | 1.82%   |
| AMD Ryzen Threadripper 3970X 32-Core Processor | 1        | 1.82%   |
| AMD Ryzen Threadripper 1920X 12-Core Processor | 1        | 1.82%   |
| AMD Ryzen 9 6900HX with Radeon Graphics        | 1        | 1.82%   |
| AMD Ryzen 9 3900X 12-Core Processor            | 1        | 1.82%   |
| AMD Ryzen 7 7800X3D 8-Core Processor           | 1        | 1.82%   |
| AMD Ryzen 7 5800X 8-Core Processor             | 1        | 1.82%   |
| AMD Ryzen 7 5700G with Radeon Graphics         | 1        | 1.82%   |
| AMD Ryzen 7 3700X 8-Core Processor             | 1        | 1.82%   |
| AMD Ryzen 7 2700X Eight-Core Processor         | 1        | 1.82%   |
| AMD Ryzen 7 2700 Eight-Core Processor          | 1        | 1.82%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics    | 1        | 1.82%   |
| AMD FX-8320 Eight-Core Processor               | 1        | 1.82%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| AMD Ryzen 5            | 15       | 27.27%  |
| AMD Ryzen 7            | 9        | 16.36%  |
| Intel Core i5          | 8        | 14.55%  |
| Intel Core i7          | 7        | 12.73%  |
| AMD Ryzen 9            | 7        | 12.73%  |
| Intel Xeon             | 2        | 3.64%   |
| AMD Ryzen Threadripper | 2        | 3.64%   |
| Other                  | 1        | 1.82%   |
| Intel Core i9          | 1        | 1.82%   |
| Intel Core i3          | 1        | 1.82%   |
| Intel Celeron          | 1        | 1.82%   |
| AMD FX                 | 1        | 1.82%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 6      | 19       | 34.55%  |
| 4      | 12       | 21.82%  |
| 8      | 10       | 18.18%  |
| 12     | 4        | 7.27%   |
| 16     | 3        | 5.45%   |
| 10     | 2        | 3.64%   |
| 2      | 2        | 3.64%   |
| 32     | 1        | 1.82%   |
| 24     | 1        | 1.82%   |
| 14     | 1        | 1.82%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 54       | 98.18%  |
| 2      | 1        | 1.82%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 48       | 87.27%  |
| 1      | 7        | 12.73%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 55       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x08701021 | 7        | 12.5%   |
| Unknown    | 7        | 12.5%   |
| 0x306c3    | 4        | 7.14%   |
| 0x306a9    | 4        | 7.14%   |
| 0x08701013 | 4        | 7.14%   |
| 0x906ea    | 3        | 5.36%   |
| 0x0a50000d | 3        | 5.36%   |
| 0x506e3    | 2        | 3.57%   |
| 0x0a201204 | 2        | 3.57%   |
| 0x0a201016 | 2        | 3.57%   |
| 0x0a201009 | 2        | 3.57%   |
| 0x08001138 | 2        | 3.57%   |
| 0xa0653    | 1        | 1.79%   |
| 0x906e9    | 1        | 1.79%   |
| 0x406f1    | 1        | 1.79%   |
| 0x306f2    | 1        | 1.79%   |
| 0x0a601203 | 1        | 1.79%   |
| 0x0a50000c | 1        | 1.79%   |
| 0x0a404102 | 1        | 1.79%   |
| 0x0a20120a | 1        | 1.79%   |
| 0x0a201025 | 1        | 1.79%   |
| 0x08301025 | 1        | 1.79%   |
| 0x08108109 | 1        | 1.79%   |
| 0x0800820d | 1        | 1.79%   |
| 0x08001137 | 1        | 1.79%   |
| 0x06000852 | 1        | 1.79%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 2            | 13       | 23.64%  |
| Zen 3            | 12       | 21.82%  |
| Haswell          | 5        | 9.09%   |
| KabyLake         | 4        | 7.27%   |
| IvyBridge        | 4        | 7.27%   |
| Zen+             | 3        | 5.45%   |
| Zen              | 3        | 5.45%   |
| Skylake          | 3        | 5.45%   |
| CometLake        | 2        | 3.64%   |
| Unknown          | 2        | 3.64%   |
| Piledriver       | 1        | 1.82%   |
| Goldmont plus    | 1        | 1.82%   |
| Broadwell        | 1        | 1.82%   |
| Alderlake Hybrid | 1        | 1.82%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 27       | 44.26%  |
| AMD    | 25       | 40.98%  |
| Intel  | 9        | 14.75%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 7        | 11.11%  |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 5        | 7.94%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 3        | 4.76%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 3        | 4.76%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 3        | 4.76%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 3.17%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 2        | 3.17%   |
| Intel HD Graphics 530                                                       | 2        | 3.17%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 2        | 3.17%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 2        | 3.17%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 1.59%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 1.59%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 1.59%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 1.59%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 1.59%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 1.59%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 1.59%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 1.59%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 1.59%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 1.59%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 1.59%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 1.59%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 1        | 1.59%   |
| Nvidia GK107 [NVS 510]                                                      | 1        | 1.59%   |
| Nvidia GK104 [GeForce GTX 660 Ti]                                           | 1        | 1.59%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 1        | 1.59%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 1        | 1.59%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 1.59%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 1.59%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1        | 1.59%   |
| Intel HD Graphics 630                                                       | 1        | 1.59%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1        | 1.59%   |
| Intel Comet Lake-S GT2 [UHD Graphics P630]                                  | 1        | 1.59%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 1.59%   |
| AMD Rembrandt [Radeon 680M]                                                 | 1        | 1.59%   |
| AMD Raphael                                                                 | 1        | 1.59%   |
| AMD Pitcairn XT [Radeon HD 7870 GHz Edition]                                | 1        | 1.59%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX]                                    | 1        | 1.59%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 1        | 1.59%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 1        | 1.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 21       | 38.18%  |
| 1 x AMD        | 19       | 34.55%  |
| 1 x Intel      | 6        | 10.91%  |
| AMD + Nvidia   | 4        | 7.27%   |
| 2 x AMD        | 2        | 3.64%   |
| Intel + Nvidia | 2        | 3.64%   |
| Other          | 1        | 1.82%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 32       | 58.18%  |
| Proprietary | 20       | 36.36%  |
| Unknown     | 3        | 5.45%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 32       | 57.14%  |
| 7.01-8.0   | 13       | 23.21%  |
| 8.01-16.0  | 4        | 7.14%   |
| 3.01-4.0   | 2        | 3.57%   |
| 1.01-2.0   | 2        | 3.57%   |
| 0.01-0.5   | 2        | 3.57%   |
| 16.01-24.0 | 1        | 1.79%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 11       | 22%     |
| Goldstar             | 9        | 18%     |
| Acer                 | 6        | 12%     |
| Samsung Electronics  | 4        | 8%      |
| Ancor Communications | 4        | 8%      |
| Iiyama               | 2        | 4%      |
| Hewlett-Packard      | 2        | 4%      |
| AOC                  | 2        | 4%      |
| Vizio                | 1        | 2%      |
| ViewSonic            | 1        | 2%      |
| Unknown (AAA)        | 1        | 2%      |
| RTK                  | 1        | 2%      |
| NEC Computers        | 1        | 2%      |
| MSI                  | 1        | 2%      |
| MPI                  | 1        | 2%      |
| HVR                  | 1        | 2%      |
| Gigabyte Technology  | 1        | 2%      |
| BenQ                 | 1        | 2%      |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                     | 2        | 3.85%   |
| Dell U2311H DELA060 1920x1080 509x286mm 23.0-inch                    | 2        | 3.85%   |
| Acer CP3271K P ACR0716 3840x2160 597x336mm 27.0-inch                 | 2        | 3.85%   |
| Vizio D50-D1 VIZ1004 1920x1080 1100x620mm 49.7-inch                  | 1        | 1.92%   |
| ViewSonic VX2758-Series VSCA738 2560x1440 598x336mm 27.0-inch        | 1        | 1.92%   |
| Unknown (AAA) Monitor AAA0ABF 1920x1080 480x260mm 21.5-inch          | 1        | 1.92%   |
| Samsung Electronics SyncMaster SAM0248 1280x1024 376x301mm 19.0-inch | 1        | 1.92%   |
| Samsung Electronics LU28R55 SAM1015 3840x2160 632x360mm 28.6-inch    | 1        | 1.92%   |
| Samsung Electronics LC27G5xT SAM707A 2560x1440 600x340mm 27.2-inch   | 1        | 1.92%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 1        | 1.92%   |
| RTK FHD HDR RTKBC32 1920x1080 597x336mm 27.0-inch                    | 1        | 1.92%   |
| NEC Computers 90GX2 NEC6692 1280x1024 376x301mm 19.0-inch            | 1        | 1.92%   |
| MSI G241 MSI3BA4 1920x1080 527x296mm 23.8-inch                       | 1        | 1.92%   |
| MPI MPI7002 MPI7002 1280x1024 255x255mm 14.2-inch                    | 1        | 1.92%   |
| Iiyama PLE2208HDS IVM560A 1920x1080 477x268mm 21.5-inch              | 1        | 1.92%   |
| Iiyama PL2492H IVM612F 1920x1080 530x300mm 24.0-inch                 | 1        | 1.92%   |
| HVR HTC-VIVE HVRAA01 2160x1200                                       | 1        | 1.92%   |
| Hewlett-Packard LA2405 HWP284B 1920x1200 520x320mm 24.0-inch         | 1        | 1.92%   |
| Hewlett-Packard E232 HWP327A 1920x1080 510x290mm 23.1-inch           | 1        | 1.92%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch             | 1        | 1.92%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch              | 1        | 1.92%   |
| Goldstar M228WA GSM563D 1680x1050 434x270mm 20.1-inch                | 1        | 1.92%   |
| Goldstar LG ULTRAWIDE GSM76FE 2560x1080 800x340mm 34.2-inch          | 1        | 1.92%   |
| Goldstar LG ULTRAWIDE GSM59F2 2560x1080 800x340mm 34.2-inch          | 1        | 1.92%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch              | 1        | 1.92%   |
| Goldstar HDR 4K GSM7750 3840x2160 697x392mm 31.5-inch                | 1        | 1.92%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                | 1        | 1.92%   |
| Goldstar FULL HD GSM5BDF 1920x1080 480x270mm 21.7-inch               | 1        | 1.92%   |
| Gigabyte Technology G24F GBT2402 1920x1080 527x296mm 23.8-inch       | 1        | 1.92%   |
| Dell U2718Q DELA0E9 3840x2160 609x349mm 27.6-inch                    | 1        | 1.92%   |
| Dell U2717D DEL40EB 2560x1440 597x336mm 27.0-inch                    | 1        | 1.92%   |
| Dell U2715H DELD067 2560x1440 597x336mm 27.0-inch                    | 1        | 1.92%   |
| Dell U2518D DEL413A 2560x1440 553x311mm 25.0-inch                    | 1        | 1.92%   |
| Dell U2515H DELD070 2560x1440 553x311mm 25.0-inch                    | 1        | 1.92%   |
| Dell U2415 DELA0B9 1920x1200 518x324mm 24.1-inch                     | 1        | 1.92%   |
| Dell U2312HM DEL4072 1920x1080 510x287mm 23.0-inch                   | 1        | 1.92%   |
| Dell P2415Q DELA0BE 3840x2160 527x296mm 23.8-inch                    | 1        | 1.92%   |
| BenQ GL2450 BNQ78A5 1920x1080 530x300mm 24.0-inch                    | 1        | 1.92%   |
| AOC 27P2DG5 AOC2702 1920x1080 598x336mm 27.0-inch                    | 1        | 1.92%   |
| AOC 2450W AOC2450 1920x1080 521x293mm 23.5-inch                      | 1        | 1.92%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 16       | 35.56%  |
| 3840x2160 (4K)     | 9        | 20%     |
| 2560x1440 (QHD)    | 7        | 15.56%  |
| 2560x1080          | 4        | 8.89%   |
| 1280x1024 (SXGA)   | 3        | 6.67%   |
| 2560x1600          | 1        | 2.22%   |
| 2160x1200          | 1        | 2.22%   |
| 1920x1200 (WUXGA)  | 1        | 2.22%   |
| 1680x1050 (WSXGA+) | 1        | 2.22%   |
| 1600x900 (HD+)     | 1        | 2.22%   |
| 1280x720 (HD)      | 1        | 2.22%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 10       | 20.83%  |
| 23      | 9        | 18.75%  |
| 24      | 8        | 16.67%  |
| 34      | 4        | 8.33%   |
| 21      | 3        | 6.25%   |
| 31      | 2        | 4.17%   |
| 25      | 2        | 4.17%   |
| 19      | 2        | 4.17%   |
| 49      | 1        | 2.08%   |
| 38      | 1        | 2.08%   |
| 28      | 1        | 2.08%   |
| 22      | 1        | 2.08%   |
| 20      | 1        | 2.08%   |
| 17      | 1        | 2.08%   |
| 14      | 1        | 2.08%   |
| Unknown | 1        | 2.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 25       | 56.82%  |
| 401-500     | 5        | 11.36%  |
| 701-800     | 4        | 9.09%   |
| 601-700     | 3        | 6.82%   |
| 351-400     | 2        | 4.55%   |
| 801-900     | 1        | 2.27%   |
| 301-350     | 1        | 2.27%   |
| 201-300     | 1        | 2.27%   |
| 1001-1500   | 1        | 2.27%   |
| Unknown     | 1        | 2.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 28       | 68.29%  |
| 16/10 | 5        | 12.2%   |
| 21/9  | 4        | 9.76%   |
| 5/4   | 3        | 7.32%   |
| 1.00  | 1        | 2.44%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 15       | 31.91%  |
| 301-350        | 10       | 21.28%  |
| 351-500        | 7        | 14.89%  |
| 251-300        | 5        | 10.64%  |
| 151-200        | 5        | 10.64%  |
| More than 1000 | 1        | 2.13%   |
| 141-150        | 1        | 2.13%   |
| 101-110        | 1        | 2.13%   |
| 501-1000       | 1        | 2.13%   |
| Unknown        | 1        | 2.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 26       | 59.09%  |
| 101-120 | 10       | 22.73%  |
| 161-240 | 4        | 9.09%   |
| 121-160 | 2        | 4.55%   |
| 1-50    | 1        | 2.27%   |
| Unknown | 1        | 2.27%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 31       | 56.36%  |
| 2     | 11       | 20%     |
| 0     | 11       | 20%     |
| 3     | 2        | 3.64%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 37       | 44.58%  |
| Intel                 | 30       | 36.14%  |
| Aquantia              | 4        | 4.82%   |
| MediaTek              | 3        | 3.61%   |
| TP-Link               | 1        | 1.2%    |
| Texas Instruments     | 1        | 1.2%    |
| Ralink Technology     | 1        | 1.2%    |
| Ralink                | 1        | 1.2%    |
| Qualcomm Atheros      | 1        | 1.2%    |
| Oculus VR             | 1        | 1.2%    |
| Microsoft             | 1        | 1.2%    |
| Google                | 1        | 1.2%    |
| D-Link System         | 1        | 1.2%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 29       | 32.58%  |
| Realtek RTL8125 2.5GbE Controller                                 | 8        | 8.99%   |
| Intel Wi-Fi 6 AX200                                               | 8        | 8.99%   |
| Intel I211 Gigabit Network Connection                             | 6        | 6.74%   |
| Intel Ethernet Controller I225-V                                  | 4        | 4.49%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 2        | 2.25%   |
| Intel Ethernet Connection (7) I219-V                              | 2        | 2.25%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 2.25%   |
| Intel Ethernet Connection (2) I218-V                              | 2        | 2.25%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2        | 2.25%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1        | 1.12%   |
| Texas Instruments CC2538 USB CDC                                  | 1        | 1.12%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 1.12%   |
| Realtek 802.11ac NIC                                              | 1        | 1.12%   |
| Ralink RT5370 Wireless Adapter                                    | 1        | 1.12%   |
| Ralink RT2800 802.11n PCI                                         | 1        | 1.12%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 1.12%   |
| Oculus VR Rift S                                                  | 1        | 1.12%   |
| Microsoft Xbox 360 Wireless Adapter                               | 1        | 1.12%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 1        | 1.12%   |
| Intel Wireless 7265                                               | 1        | 1.12%   |
| Intel Ethernet Controller I225-LM                                 | 1        | 1.12%   |
| Intel Ethernet Connection I217-V                                  | 1        | 1.12%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 1.12%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 1.12%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1        | 1.12%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1        | 1.12%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 1.12%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 1.12%   |
| Intel 82576 Gigabit Network Connection                            | 1        | 1.12%   |
| Google Nexus/Pixel Device (tether)                                | 1        | 1.12%   |
| D-Link System DWA-110 Wireless G Adapter(rev.A1) [Ralink RT2571W] | 1        | 1.12%   |
| Aquantia AQC100 10G Ethernet MAC controller [AQtion]              | 1        | 1.12%   |
| Aquantia 5G USB Ethernet Adapter                                  | 1        | 1.12%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 11       | 55%     |
| MediaTek              | 3        | 15%     |
| TP-Link               | 1        | 5%      |
| Realtek Semiconductor | 1        | 5%      |
| Ralink Technology     | 1        | 5%      |
| Ralink                | 1        | 5%      |
| Microsoft             | 1        | 5%      |
| D-Link System         | 1        | 5%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                               | 8        | 40%     |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 2        | 10%     |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1        | 5%      |
| Realtek 802.11ac NIC                                              | 1        | 5%      |
| Ralink RT5370 Wireless Adapter                                    | 1        | 5%      |
| Ralink RT2800 802.11n PCI                                         | 1        | 5%      |
| Microsoft Xbox 360 Wireless Adapter                               | 1        | 5%      |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 1        | 5%      |
| Intel Wireless 7265                                               | 1        | 5%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1        | 5%      |
| Intel Comet Lake PCH CNVi WiFi                                    | 1        | 5%      |
| D-Link System DWA-110 Wireless G Adapter(rev.A1) [Ralink RT2571W] | 1        | 5%      |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 37       | 56.06%  |
| Intel                 | 23       | 34.85%  |
| Aquantia              | 4        | 6.06%   |
| Qualcomm Atheros      | 1        | 1.52%   |
| Google                | 1        | 1.52%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 29       | 43.28%  |
| Realtek RTL8125 2.5GbE Controller                                 | 8        | 11.94%  |
| Intel I211 Gigabit Network Connection                             | 6        | 8.96%   |
| Intel Ethernet Controller I225-V                                  | 4        | 5.97%   |
| Intel Ethernet Connection (7) I219-V                              | 2        | 2.99%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 2.99%   |
| Intel Ethernet Connection (2) I218-V                              | 2        | 2.99%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2        | 2.99%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 1.49%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 1.49%   |
| Intel Ethernet Controller I225-LM                                 | 1        | 1.49%   |
| Intel Ethernet Connection I217-V                                  | 1        | 1.49%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 1.49%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 1.49%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 1.49%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 1.49%   |
| Intel 82576 Gigabit Network Connection                            | 1        | 1.49%   |
| Google Nexus/Pixel Device (tether)                                | 1        | 1.49%   |
| Aquantia AQC100 10G Ethernet MAC controller [AQtion]              | 1        | 1.49%   |
| Aquantia 5G USB Ethernet Adapter                                  | 1        | 1.49%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 55       | 71.43%  |
| WiFi     | 20       | 25.97%  |
| Modem    | 2        | 2.6%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 46       | 85.19%  |
| WiFi     | 8        | 14.81%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 31       | 56.36%  |
| 2     | 21       | 38.18%  |
| 3     | 2        | 3.64%   |
| 0     | 1        | 1.82%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 36       | 65.45%  |
| Yes  | 19       | 34.55%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 8        | 34.78%  |
| Cambridge Silicon Radio  | 4        | 17.39%  |
| ASUSTek Computer         | 3        | 13.04%  |
| Realtek Semiconductor    | 2        | 8.7%    |
| MediaTek                 | 2        | 8.7%    |
| Broadcom                 | 2        | 8.7%    |
| HTC (High Tech Computer) | 1        | 4.35%   |
| Foxconn / Hon Hai        | 1        | 4.35%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                                | 6        | 26.09%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 4        | 17.39%  |
| Realtek Bluetooth Radio                                              | 2        | 8.7%    |
| MediaTek Wireless_Device                                             | 2        | 8.7%    |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 2        | 8.7%    |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 2        | 8.7%    |
| Intel Wireless-AC 3168 Bluetooth                                     | 1        | 4.35%   |
| Intel AX201 Bluetooth                                                | 1        | 4.35%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 4.35%   |
| Foxconn / Hon Hai Wireless_Device                                    | 1        | 4.35%   |
| ASUS ASUS USB-BT500                                                  | 1        | 4.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| AMD                                  | 38       | 33.33%  |
| Nvidia                               | 27       | 23.68%  |
| Intel                                | 21       | 18.42%  |
| Texas Instruments                    | 3        | 2.63%   |
| C-Media Electronics                  | 3        | 2.63%   |
| Razer USA                            | 2        | 1.75%   |
| Kingston Technology                  | 2        | 1.75%   |
| Focusrite-Novation                   | 2        | 1.75%   |
| Thomann                              | 1        | 0.88%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.88%   |
| Sony                                 | 1        | 0.88%   |
| Shure                                | 1        | 0.88%   |
| Sennheiser Communications            | 1        | 0.88%   |
| Schiit Audio                         | 1        | 0.88%   |
| PreSonus Audio Electronics           | 1        | 0.88%   |
| GYROCOM C&C                          | 1        | 0.88%   |
| Edifier Technology                   | 1        | 0.88%   |
| DSEA A/S                             | 1        | 0.88%   |
| Creative Technology                  | 1        | 0.88%   |
| Creative Labs                        | 1        | 0.88%   |
| ASUSTek Computer                     | 1        | 0.88%   |
| ASRock                               | 1        | 0.88%   |
| Apogee Electronics                   | 1        | 0.88%   |
| Antlion Audio                        | 1        | 0.88%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                            | 20       | 14.71%  |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]          | 7        | 5.15%   |
| AMD Navi 10 HDMI Audio                                              | 5        | 3.68%   |
| AMD Family 17h/19h HD Audio Controller                              | 5        | 3.68%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                 | 5        | 3.68%   |
| Nvidia TU106 High Definition Audio Controller                       | 4        | 2.94%   |
| Nvidia GK104 HDMI Audio Controller                                  | 4        | 2.94%   |
| AMD Renoir Radeon High Definition Audio Controller                  | 4        | 2.94%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                             | 4        | 2.94%   |
| Nvidia TU116 High Definition Audio Controller                       | 3        | 2.21%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 3        | 2.21%   |
| Intel 200 Series PCH HD Audio                                       | 3        | 2.21%   |
| Texas Instruments PCM2902 Audio Codec                               | 2        | 1.47%   |
| Nvidia GP107GL High Definition Audio Controller                     | 2        | 1.47%   |
| Nvidia GP106 High Definition Audio Controller                       | 2        | 1.47%   |
| Nvidia GP104 High Definition Audio Controller                       | 2        | 1.47%   |
| Nvidia GM204 High Definition Audio Controller                       | 2        | 1.47%   |
| Intel Comet Lake PCH cAVS                                           | 2        | 1.47%   |
| Intel Cannon Lake PCH cAVS                                          | 2        | 1.47%   |
| Intel C610/X99 series chipset HD Audio Controller                   | 2        | 1.47%   |
| Intel 9 Series Chipset Family HD Audio Controller                   | 2        | 1.47%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 2        | 1.47%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller     | 2        | 1.47%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                          | 2        | 1.47%   |
| AMD Rembrandt Radeon High Definition Audio Controller               | 2        | 1.47%   |
| Thomann SC450USB                                                    | 1        | 0.74%   |
| Thesycon Systemsoftware & Consulting DX3 Pro+                       | 1        | 0.74%   |
| Texas Instruments PCM2902C Audio CODEC                              | 1        | 0.74%   |
| Sony DualShock 4 [CUH-ZCT2x]                                        | 1        | 0.74%   |
| Shure MV7                                                           | 1        | 0.74%   |
| Sennheiser Communications Sennheiser SC630 for Lync                 | 1        | 0.74%   |
| Schiit Audio Schiit Modi 3+                                         | 1        | 0.74%   |
| Razer USA Razer BlackShark V2 Pro                                   | 1        | 0.74%   |
| Razer USA Kraken 7.1 V2                                             | 1        | 0.74%   |
| PreSonus Audio Electronics AudioBox                                 | 1        | 0.74%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller      | 1        | 0.74%   |
| Nvidia TU104 HD Audio Controller                                    | 1        | 0.74%   |
| Nvidia GP102 HDMI Audio Controller                                  | 1        | 0.74%   |
| Nvidia GM206 High Definition Audio Controller                       | 1        | 0.74%   |
| Nvidia GM200 High Definition Audio                                  | 1        | 0.74%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 17       | 27.42%  |
| Kingston            | 15       | 24.19%  |
| G.Skill             | 12       | 19.35%  |
| Crucial             | 4        | 6.45%   |
| Samsung Electronics | 3        | 4.84%   |
| Micron Technology   | 3        | 4.84%   |
| Team                | 2        | 3.23%   |
| Unknown (ABCD)      | 1        | 1.61%   |
| Unknown             | 1        | 1.61%   |
| Strontium           | 1        | 1.61%   |
| Goodram             | 1        | 1.61%   |
| AMD                 | 1        | 1.61%   |
| A-DATA Technology   | 1        | 1.61%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| G.Skill RAM F4-3200C16-16GVK 16384MB DIMM DDR4 3600MT/s        | 3        | 4.35%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s         | 3        | 4.35%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s         | 2        | 2.9%    |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s            | 2        | 2.9%    |
| Kingston RAM KHX2400C15/16G 16GB DIMM DDR4 3334MT/s            | 2        | 2.9%    |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s         | 2        | 2.9%    |
| Corsair RAM CMK16GX4M1D3000C16 16GB DIMM DDR4 3000MT/s         | 2        | 2.9%    |
| Unknown RAM Module 16384MB DIMM DDR4 2133MT/s                  | 1        | 1.45%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 1        | 1.45%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3733MT/s            | 1        | 1.45%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3000MT/s             | 1        | 1.45%   |
| Team RAM TEAMGROUP-UD4-2666 16384MB DIMM DDR4 2933MT/s         | 1        | 1.45%   |
| Strontium RAM SRT8G86U1-P9H 8GB DIMM DDR3 1600MT/s             | 1        | 1.45%   |
| Samsung RAM Module 4096MB SODIMM DDR4 2133MT/s                 | 1        | 1.45%   |
| Samsung RAM M393A4K40BB0-CPB 32GB RIMM DDR4 2133MT/s           | 1        | 1.45%   |
| Samsung RAM M391A1K43BB1-CRC 8GB DIMM DDR4 2400MT/s            | 1        | 1.45%   |
| Micron RAM 4ATF1G64AZ-3G2E1 8GB DIMM DDR4 3200MT/s             | 1        | 1.45%   |
| Micron RAM 36ASF4G72PZ-2G1A1 32GB RIMM DDR4 2133MT/s           | 1        | 1.45%   |
| Micron RAM 16ATF2G64AZ-3G2J1 16GB DIMM DDR4 3200MT/s           | 1        | 1.45%   |
| Kingston RAM Module 4GB DIMM DDR3 1600MT/s                     | 1        | 1.45%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s           | 1        | 1.45%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s         | 1        | 1.45%   |
| Kingston RAM KHX2400C15D4/8G 8GB DIMM DDR4 2400MT/s            | 1        | 1.45%   |
| Kingston RAM KHX1600C10D3L/8GX 8GB DIMM DDR3 1600MT/s          | 1        | 1.45%   |
| Kingston RAM KF548S38-16 16GB SODIMM DDR5 4800MT/s             | 1        | 1.45%   |
| Kingston RAM KF3600C17D4/8GX 8GB DIMM DDR4 3600MT/s            | 1        | 1.45%   |
| Kingston RAM 99U5474-038.A00LF 4GB DIMM DDR3 1333MT/s          | 1        | 1.45%   |
| Kingston RAM 99U5471-034.A00LF 4GB DIMM DDR3 1600MT/s          | 1        | 1.45%   |
| Kingston RAM 99U5403-123.A00LF 8GB DIMM DDR3 1600MT/s          | 1        | 1.45%   |
| Kingston RAM 99U5403-036.A00LF 4GB DIMM DDR3 1600MT/s          | 1        | 1.45%   |
| Kingston RAM 9965745-021.A00G 32GB DIMM DDR4 2933MT/s          | 1        | 1.45%   |
| Kingston RAM 9965684-028.A00G 8GB DIMM DDR4 3200MT/s           | 1        | 1.45%   |
| Kingston RAM 9965669-008.A03G 16GB DIMM DDR4 2134MT/s          | 1        | 1.45%   |
| Goodram RAM GR1600D364L9/4G 4096MB DIMM DDR3 1333MT/s          | 1        | 1.45%   |
| Goodram RAM GR1600D364L11/4G 4GB DIMM DDR3 1600MT/s            | 1        | 1.45%   |
| G.Skill RAM F4-3600C18-32GVK 32GB DIMM DDR4 3600MT/s           | 1        | 1.45%   |
| G.Skill RAM F4-3600C18-16GVK 16384MB DIMM DDR4 3733MT/s        | 1        | 1.45%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s            | 1        | 1.45%   |
| G.Skill RAM F4-3000C16-16GISB 16GB DIMM DDR4 3200MT/s          | 1        | 1.45%   |
| G.Skill RAM F4-2400C15-8GRK 8GB DIMM DDR4 2400MT/s             | 1        | 1.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Desktops | Percent |
|--------|----------|---------|
| DDR4   | 42       | 77.78%  |
| DDR3   | 9        | 16.67%  |
| DDR5   | 2        | 3.7%    |
| LPDDR4 | 1        | 1.85%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 51       | 94.44%  |
| SODIMM | 2        | 3.7%    |
| RIMM   | 1        | 1.85%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 16384 | 26       | 42.62%  |
| 8192  | 20       | 32.79%  |
| 32768 | 10       | 16.39%  |
| 4096  | 5        | 8.2%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 14       | 21.88%  |
| 3600  | 9        | 14.06%  |
| 1600  | 7        | 10.94%  |
| 3000  | 5        | 7.81%   |
| 2400  | 5        | 7.81%   |
| 3733  | 4        | 6.25%   |
| 2133  | 4        | 6.25%   |
| 3400  | 2        | 3.13%   |
| 3334  | 2        | 3.13%   |
| 2933  | 2        | 3.13%   |
| 1333  | 2        | 3.13%   |
| 6000  | 1        | 1.56%   |
| 4800  | 1        | 1.56%   |
| 3866  | 1        | 1.56%   |
| 3666  | 1        | 1.56%   |
| 3534  | 1        | 1.56%   |
| 2800  | 1        | 1.56%   |
| 2134  | 1        | 1.56%   |
| 2132  | 1        | 1.56%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Xerox  | 1        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Xerox Phaser 6125N | 1        | 100%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Seiko Epson | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Seiko Epson GT-X820 [Perfection V600 Photo] | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Logitech     | 10       | 66.67%  |
| MacroSilicon | 3        | 20%     |
| Microdia     | 1        | 6.67%   |
| Apple        | 1        | 6.67%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| MacroSilicon usb video          | 3        | 20%     |
| Logitech Webcam C270            | 2        | 13.33%  |
| Microdia Camera                 | 1        | 6.67%   |
| Logitech Webcam Pro 9000        | 1        | 6.67%   |
| Logitech Webcam C930e           | 1        | 6.67%   |
| Logitech Webcam C120            | 1        | 6.67%   |
| Logitech StreamCam              | 1        | 6.67%   |
| Logitech HD Webcam C615         | 1        | 6.67%   |
| Logitech HD Pro Webcam C920     | 1        | 6.67%   |
| Logitech C930c                  | 1        | 6.67%   |
| Logitech C922 Pro Stream Webcam | 1        | 6.67%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X | 1        | 6.67%   |

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
| 0     | 43       | 76.79%  |
| 1     | 9        | 16.07%  |
| 2     | 4        | 7.14%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Desktops | Percent |
|-----------------------|----------|---------|
| Net/wireless          | 4        | 26.67%  |
| Unassigned class      | 3        | 20%     |
| Graphics card         | 3        | 20%     |
| Bluetooth             | 2        | 13.33%  |
| Multimedia controller | 1        | 6.67%   |
| Dvb card              | 1        | 6.67%   |
| Camera                | 1        | 6.67%   |

