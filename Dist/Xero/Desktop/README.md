Xero - Tested Hardware & Statistics (Desktops)
----------------------------------------------

A project to collect tested hardware configurations for Xero.

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

Total: 62

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek  | A68HM-PLUS                  | [520ad2ca86](https://linux-hardware.org/?probe=520ad2ca86) | Mar 31, 2023 |
| HP       | 8437                        | [cdc32d8d8b](https://linux-hardware.org/?probe=cdc32d8d8b) | Mar 25, 2023 |
| HP       | 8437                        | [6fbb459a03](https://linux-hardware.org/?probe=6fbb459a03) | Mar 25, 2023 |
| ASUSTek  | A68HM-PLUS                  | [5d307f2d26](https://linux-hardware.org/?probe=5d307f2d26) | Mar 18, 2023 |
| Acer     | Aspire GX-281               | [d318df6931](https://linux-hardware.org/?probe=d318df6931) | Mar 04, 2023 |
| JINGSHA  | Unknown                     | [c8bd846b63](https://linux-hardware.org/?probe=c8bd846b63) | Feb 26, 2023 |
| Dell     | 0G3HR7 A00                  | [33723c8b80](https://linux-hardware.org/?probe=33723c8b80) | Feb 25, 2023 |
| MSI      | MAG B550 TOMAHAWK           | [503fe663b4](https://linux-hardware.org/?probe=503fe663b4) | Feb 20, 2023 |
| ASUSTek  | ROG STRIX Z370-F GAMING     | [d76b048134](https://linux-hardware.org/?probe=d76b048134) | Feb 17, 2023 |
| HP       | 828A                        | [5f430ba8d1](https://linux-hardware.org/?probe=5f430ba8d1) | Jan 19, 2023 |
| Pegatron | 2AF0                        | [77768feff6](https://linux-hardware.org/?probe=77768feff6) | Jan 01, 2023 |
| ASUSTek  | ROG STRIX X570-F GAMING     | [f074ef2e7c](https://linux-hardware.org/?probe=f074ef2e7c) | Nov 15, 2022 |
| ASUSTek  | ROG STRIX X570-F GAMING     | [711e95b72e](https://linux-hardware.org/?probe=711e95b72e) | Nov 02, 2022 |
| ASUSTek  | ROG STRIX X570-F GAMING     | [ff0c19c661](https://linux-hardware.org/?probe=ff0c19c661) | Nov 02, 2022 |
| Gigabyte | A320M-S2H-CF                | [bcf4fa1baf](https://linux-hardware.org/?probe=bcf4fa1baf) | Oct 18, 2022 |
| Dell     | 0GY6Y8 A02                  | [07b256f333](https://linux-hardware.org/?probe=07b256f333) | Oct 17, 2022 |
| Dell     | 0GY6Y8 A02                  | [fc1ec464bf](https://linux-hardware.org/?probe=fc1ec464bf) | Oct 17, 2022 |
| ASUSTek  | ROG STRIX X570-F GAMING     | [bf0e112f9a](https://linux-hardware.org/?probe=bf0e112f9a) | Oct 16, 2022 |
| ASUSTek  | PRIME B250-PLUS             | [00ab764924](https://linux-hardware.org/?probe=00ab764924) | Oct 15, 2022 |
| ASUSTek  | ROG STRIX X570-F GAMING     | [e037086b30](https://linux-hardware.org/?probe=e037086b30) | Oct 14, 2022 |
| ASUSTek  | ROG CROSSHAIR VIII DARK ... | [9931b35717](https://linux-hardware.org/?probe=9931b35717) | Sep 24, 2022 |
| ASUSTek  | ROG STRIX B450-F GAMING     | [4c95b1bccf](https://linux-hardware.org/?probe=4c95b1bccf) | Aug 22, 2022 |
| Gigabyte | B460M DS3H V2               | [2522ff1530](https://linux-hardware.org/?probe=2522ff1530) | Aug 13, 2022 |
| ASUSTek  | P7P55 LX                    | [8211ccc6cc](https://linux-hardware.org/?probe=8211ccc6cc) | Aug 11, 2022 |
| Unknown  | Unknown                     | [b73e5f9cbf](https://linux-hardware.org/?probe=b73e5f9cbf) | Aug 08, 2022 |
| Unknown  | Unknown                     | [f483092edf](https://linux-hardware.org/?probe=f483092edf) | Aug 07, 2022 |
| ASUSTek  | TUF Gaming X570-PLUS        | [a0507fae02](https://linux-hardware.org/?probe=a0507fae02) | Jul 31, 2022 |
| ASRock   | AB350 Pro4                  | [7049f819f0](https://linux-hardware.org/?probe=7049f819f0) | Jun 30, 2022 |
| HP       | 3396                        | [00782afa06](https://linux-hardware.org/?probe=00782afa06) | Jun 22, 2022 |
| ASUSTek  | ROG STRIX B450-F GAMING     | [8109a04ffa](https://linux-hardware.org/?probe=8109a04ffa) | Jun 12, 2022 |
| ASUSTek  | ROG STRIX B450-F GAMING     | [8a7401e54a](https://linux-hardware.org/?probe=8a7401e54a) | Jun 11, 2022 |
| Acer     | Aspire XC-886 V:2.0         | [2fe8cdaf93](https://linux-hardware.org/?probe=2fe8cdaf93) | May 31, 2022 |
| ASUSTek  | ROG Maximus X HERO          | [3ddad532a9](https://linux-hardware.org/?probe=3ddad532a9) | May 08, 2022 |
| MSI      | Z170-A PRO                  | [db5ab86328](https://linux-hardware.org/?probe=db5ab86328) | Apr 11, 2022 |
| MSI      | Z170-A PRO                  | [3bd5bb8d08](https://linux-hardware.org/?probe=3bd5bb8d08) | Apr 10, 2022 |
| ASUSTek  | TUF Gaming X570-PLUS        | [8d251b1b2a](https://linux-hardware.org/?probe=8d251b1b2a) | Apr 03, 2022 |
| HP       | 843B                        | [a88ff7cf5c](https://linux-hardware.org/?probe=a88ff7cf5c) | Mar 27, 2022 |
| Pegatron | 2AC2                        | [d3c82e973b](https://linux-hardware.org/?probe=d3c82e973b) | Mar 25, 2022 |
| ASUSTek  | Maximus IX HERO             | [745cc1d638](https://linux-hardware.org/?probe=745cc1d638) | Mar 25, 2022 |
| ASUSTek  | Maximus IX HERO             | [8eb98db533](https://linux-hardware.org/?probe=8eb98db533) | Mar 22, 2022 |
| ASUSTek  | ROG CROSSHAIR VIII HERO     | [13cdf54c81](https://linux-hardware.org/?probe=13cdf54c81) | Mar 21, 2022 |
| ASUSTek  | TUF Gaming B550M-PLUS       | [639e7361ef](https://linux-hardware.org/?probe=639e7361ef) | Mar 12, 2022 |
| MSI      | Z170A PC MATE               | [181e014823](https://linux-hardware.org/?probe=181e014823) | Mar 08, 2022 |
| Gigabyte | Z170X-UD3-CF                | [3ec7a7f643](https://linux-hardware.org/?probe=3ec7a7f643) | Mar 06, 2022 |
| ASUSTek  | P5Q PRO TURBO               | [83ca29c9c8](https://linux-hardware.org/?probe=83ca29c9c8) | Jan 28, 2022 |
| ASUSTek  | TUF Gaming B550M-PLUS       | [230373b3ff](https://linux-hardware.org/?probe=230373b3ff) | Jan 09, 2022 |
| HP       | 1906                        | [5f8fe7cb20](https://linux-hardware.org/?probe=5f8fe7cb20) | Jan 06, 2022 |
| ASUSTek  | TUF Gaming X570-PLUS        | [793bfa4f40](https://linux-hardware.org/?probe=793bfa4f40) | Jan 04, 2022 |
| HP       | 2179                        | [79bac7ce1b](https://linux-hardware.org/?probe=79bac7ce1b) | Jan 01, 2022 |
| ASUSTek  | TUF B360M-PLUS GAMING/BR    | [512091cd1c](https://linux-hardware.org/?probe=512091cd1c) | Dec 30, 2021 |
| HP       | 2179                        | [9b6358ce37](https://linux-hardware.org/?probe=9b6358ce37) | Dec 30, 2021 |
| ASRock   | X570 Taichi                 | [5c2c86f287](https://linux-hardware.org/?probe=5c2c86f287) | Dec 23, 2021 |
| ASUSTek  | TUF Gaming X570-PLUS        | [728b23aa46](https://linux-hardware.org/?probe=728b23aa46) | Nov 26, 2021 |
| ASUSTek  | PRIME A320M-K               | [9e9b6fd944](https://linux-hardware.org/?probe=9e9b6fd944) | Nov 21, 2021 |
| ASUSTek  | TUF Z390-PLUS GAMING        | [4877535f8b](https://linux-hardware.org/?probe=4877535f8b) | Nov 03, 2021 |
| MSI      | Z370 GAMING PLUS            | [8dd5924480](https://linux-hardware.org/?probe=8dd5924480) | Oct 31, 2021 |
| Dell     | 0XC7MM A01                  | [390c5408b2](https://linux-hardware.org/?probe=390c5408b2) | Oct 05, 2021 |
| ASRock   | B450M Pro4                  | [a198e8517a](https://linux-hardware.org/?probe=a198e8517a) | Oct 01, 2021 |
| ASRock   | X570 Taichi                 | [50fd919991](https://linux-hardware.org/?probe=50fd919991) | Aug 29, 2021 |
| Gigabyte | X570 AORUS MASTER           | [a3c6fe4037](https://linux-hardware.org/?probe=a3c6fe4037) | Jul 24, 2021 |
| ASRock   | X570 Taichi                 | [57d19e2c3a](https://linux-hardware.org/?probe=57d19e2c3a) | May 19, 2021 |
| Acer     | FIH57                       | [9c3e383ea5](https://linux-hardware.org/?probe=9c3e383ea5) | Apr 30, 2021 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Xero Rolling | 39       | 88.64%  |
| Xero         | 5        | 11.36%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| Xero | 44       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Desktops | Percent |
|-------------------------|----------|---------|
| 6.1.12-arch1-1          | 4        | 8%      |
| 5.18.16-arch1-1         | 2        | 4%      |
| 5.16.15-arch1-1         | 2        | 4%      |
| 5.16.12-arch1-1         | 2        | 4%      |
| 6.2.8-arch1-1           | 1        | 2%      |
| 6.2.6-arch1-1           | 1        | 2%      |
| 6.2.1-x64v1-xanmod1-1   | 1        | 2%      |
| 6.1.6-arch1-3           | 1        | 2%      |
| 6.0.6-zen1-1-zen        | 1        | 2%      |
| 6.0.2-zen1-1-zen        | 1        | 2%      |
| 6.0.1-arch2-1           | 1        | 2%      |
| 5.19.9-arch1-1          | 1        | 2%      |
| 5.19.2-zen1-1-zen       | 1        | 2%      |
| 5.19.13-zen1-1-zen      | 1        | 2%      |
| 5.19.13-arch1-1         | 1        | 2%      |
| 5.19.10-arch1-1         | 1        | 2%      |
| 5.18.9-arch1-1          | 1        | 2%      |
| 5.18.6-arch1-1          | 1        | 2%      |
| 5.18.3-arch1-1          | 1        | 2%      |
| 5.18.0-arch1-1          | 1        | 2%      |
| 5.17.5-arch1-1          | 1        | 2%      |
| 5.17.1-arch1-1          | 1        | 2%      |
| 5.16.16-zen1-1-zen      | 1        | 2%      |
| 5.16.16-arch1-1         | 1        | 2%      |
| 5.16.13-arch1-1         | 1        | 2%      |
| 5.16.1-arch1-1          | 1        | 2%      |
| 5.15.4-arch1-1          | 1        | 2%      |
| 5.15.33-1-lts           | 1        | 2%      |
| 5.15.3-zen1-1-zen       | 1        | 2%      |
| 5.15.24-1-lts           | 1        | 2%      |
| 5.15.13-AMD             | 1        | 2%      |
| 5.15.12-zen1-1-zen      | 1        | 2%      |
| 5.15.12-arch1-1-surface | 1        | 2%      |
| 5.15.12-arch1-1         | 1        | 2%      |
| 5.15.11-arch2-1-surface | 1        | 2%      |
| 5.15.10-arch1-1         | 1        | 2%      |
| 5.14.9-zen2-1-zen       | 1        | 2%      |
| 5.14.8-zen1-1-zen       | 1        | 2%      |
| 5.14.15-zen1-1-zen      | 1        | 2%      |
| 5.14.14-arch1-1         | 1        | 2%      |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.1.12  | 4        | 8%      |
| 5.15.12 | 3        | 6%      |
| 5.19.13 | 2        | 4%      |
| 5.18.16 | 2        | 4%      |
| 5.16.16 | 2        | 4%      |
| 5.16.15 | 2        | 4%      |
| 5.16.12 | 2        | 4%      |
| 6.2.8   | 1        | 2%      |
| 6.2.6   | 1        | 2%      |
| 6.2.1   | 1        | 2%      |
| 6.1.6   | 1        | 2%      |
| 6.0.6   | 1        | 2%      |
| 6.0.2   | 1        | 2%      |
| 6.0.1   | 1        | 2%      |
| 5.19.9  | 1        | 2%      |
| 5.19.2  | 1        | 2%      |
| 5.19.10 | 1        | 2%      |
| 5.18.9  | 1        | 2%      |
| 5.18.6  | 1        | 2%      |
| 5.18.3  | 1        | 2%      |
| 5.18.0  | 1        | 2%      |
| 5.17.5  | 1        | 2%      |
| 5.17.1  | 1        | 2%      |
| 5.16.13 | 1        | 2%      |
| 5.16.1  | 1        | 2%      |
| 5.15.4  | 1        | 2%      |
| 5.15.33 | 1        | 2%      |
| 5.15.3  | 1        | 2%      |
| 5.15.24 | 1        | 2%      |
| 5.15.13 | 1        | 2%      |
| 5.15.11 | 1        | 2%      |
| 5.15.10 | 1        | 2%      |
| 5.14.9  | 1        | 2%      |
| 5.14.8  | 1        | 2%      |
| 5.14.15 | 1        | 2%      |
| 5.14.14 | 1        | 2%      |
| 5.13.4  | 1        | 2%      |
| 5.13.13 | 1        | 2%      |
| 5.12.5  | 1        | 2%      |
| 5.11.16 | 1        | 2%      |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 9        | 18.37%  |
| 5.16    | 8        | 16.33%  |
| 5.18    | 6        | 12.24%  |
| 6.1     | 5        | 10.2%   |
| 5.19    | 5        | 10.2%   |
| 5.14    | 4        | 8.16%   |
| 6.2     | 3        | 6.12%   |
| 6.0     | 3        | 6.12%   |
| 5.17    | 2        | 4.08%   |
| 5.13    | 2        | 4.08%   |
| 5.12    | 1        | 2.04%   |
| 5.11    | 1        | 2.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 44       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| KDE5  | 42       | 93.33%  |
| XFCE  | 2        | 4.44%   |
| GNOME | 1        | 2.22%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 40       | 90.91%  |
| Wayland | 2        | 4.55%   |
| Tty     | 2        | 4.55%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 29       | 64.44%  |
| Unknown | 10       | 22.22%  |
| LightDM | 4        | 8.89%   |
| TDM     | 1        | 2.22%   |
| GDM     | 1        | 2.22%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 23       | 52.27%  |
| en_GB | 5        | 11.36%  |
| de_DE | 4        | 9.09%   |
| C     | 2        | 4.55%   |
| sv_SE | 1        | 2.27%   |
| ru_RU | 1        | 2.27%   |
| pl_PL | 1        | 2.27%   |
| hu_HU | 1        | 2.27%   |
| es_MX | 1        | 2.27%   |
| en_IN | 1        | 2.27%   |
| en_CA | 1        | 2.27%   |
| en_AU | 1        | 2.27%   |
| de_AT | 1        | 2.27%   |
| ba_RU | 1        | 2.27%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 25       | 56.82%  |
| BIOS | 19       | 43.18%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Btrfs   | 24       | 53.33%  |
| Xfs     | 9        | 20%     |
| Ext4    | 9        | 20%     |
| Overlay | 3        | 6.67%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 29       | 65.91%  |
| Unknown | 10       | 22.73%  |
| MBR     | 5        | 11.36%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 29       | 63.04%  |
| Yes       | 17       | 36.96%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 28       | 63.64%  |
| Yes       | 16       | 36.36%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 17       | 38.64%  |
| Hewlett-Packard     | 6        | 13.64%  |
| MSI                 | 4        | 9.09%   |
| Gigabyte Technology | 4        | 9.09%   |
| Dell                | 3        | 6.82%   |
| ASRock              | 3        | 6.82%   |
| Acer                | 3        | 6.82%   |
| Pegatron            | 2        | 4.55%   |
| JINGSHA             | 1        | 2.27%   |
| Unknown             | 1        | 2.27%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| MSI MS-7971                       | 2        | 4.55%   |
| ASUS TUF Gaming X570-PLUS         | 2        | 4.55%   |
| Unknown                           | 2        | 4.55%   |
| Pegatron p6-2026                  | 1        | 2.27%   |
| Pegatron 20-b010                  | 1        | 2.27%   |
| MSI MS-7C91                       | 1        | 2.27%   |
| MSI MS-7B61                       | 1        | 2.27%   |
| HP Z230 SFF Workstation           | 1        | 2.27%   |
| HP ProOne 400 G1 AiO              | 1        | 2.27%   |
| HP Pavilion Power Desktop 580-1xx | 1        | 2.27%   |
| HP Pavilion Desktop 590-p0xxx     | 1        | 2.27%   |
| HP Compaq Elite 8300 CMT          | 1        | 2.27%   |
| HP 750-424                        | 1        | 2.27%   |
| Gigabyte Z170X-UD3                | 1        | 2.27%   |
| Gigabyte X570 AORUS MASTER        | 1        | 2.27%   |
| Gigabyte B460MDS3HV2              | 1        | 2.27%   |
| Gigabyte A320M-S2H                | 1        | 2.27%   |
| Dell Studio XPS 8100              | 1        | 2.27%   |
| Dell Precision T1500              | 1        | 2.27%   |
| Dell OptiPlex 7010                | 1        | 2.27%   |
| ASUS TUF Z390-PLUS GAMING         | 1        | 2.27%   |
| ASUS TUF Gaming B550M-PLUS        | 1        | 2.27%   |
| ASUS TUF B360M-PLUS GAMING/BR     | 1        | 2.27%   |
| ASUS ROG STRIX Z370-F GAMING      | 1        | 2.27%   |
| ASUS ROG STRIX X570-F GAMING      | 1        | 2.27%   |
| ASUS ROG STRIX B450-F GAMING      | 1        | 2.27%   |
| ASUS ROG Maximus X HERO           | 1        | 2.27%   |
| ASUS ROG CROSSHAIR VIII HERO      | 1        | 2.27%   |
| ASUS ROG CROSSHAIR VIII DARK HERO | 1        | 2.27%   |
| ASUS PRIME B250-PLUS              | 1        | 2.27%   |
| ASUS PRIME A320M-K                | 1        | 2.27%   |
| ASUS P7P55 LX                     | 1        | 2.27%   |
| ASUS P5Q PRO TURBO                | 1        | 2.27%   |
| ASUS Maximus IX HERO              | 1        | 2.27%   |
| ASUS A68HM-PLUS                   | 1        | 2.27%   |
| ASRock X570 Taichi                | 1        | 2.27%   |
| ASRock B450M Pro4                 | 1        | 2.27%   |
| ASRock AB350 Pro4                 | 1        | 2.27%   |
| Acer Aspire XC-886                | 1        | 2.27%   |
| Acer Aspire X5950                 | 1        | 2.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| ASUS ROG             | 6        | 13.64%  |
| ASUS TUF             | 5        | 11.36%  |
| Acer Aspire          | 3        | 6.82%   |
| MSI MS-7971          | 2        | 4.55%   |
| HP Pavilion          | 2        | 4.55%   |
| ASUS PRIME           | 2        | 4.55%   |
| Unknown              | 2        | 4.55%   |
| Pegatron p6-2026     | 1        | 2.27%   |
| Pegatron 20-b010     | 1        | 2.27%   |
| MSI MS-7C91          | 1        | 2.27%   |
| MSI MS-7B61          | 1        | 2.27%   |
| HP Z230              | 1        | 2.27%   |
| HP ProOne            | 1        | 2.27%   |
| HP Compaq            | 1        | 2.27%   |
| HP 750-424           | 1        | 2.27%   |
| Gigabyte Z170X-UD3   | 1        | 2.27%   |
| Gigabyte X570        | 1        | 2.27%   |
| Gigabyte B460MDS3HV2 | 1        | 2.27%   |
| Gigabyte A320M-S2H   | 1        | 2.27%   |
| Dell Studio          | 1        | 2.27%   |
| Dell Precision       | 1        | 2.27%   |
| Dell OptiPlex        | 1        | 2.27%   |
| ASUS P7P55           | 1        | 2.27%   |
| ASUS P5Q             | 1        | 2.27%   |
| ASUS Maximus         | 1        | 2.27%   |
| ASUS A68HM-PLUS      | 1        | 2.27%   |
| ASRock X570          | 1        | 2.27%   |
| ASRock B450M         | 1        | 2.27%   |
| ASRock AB350         | 1        | 2.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 8        | 18.18%  |
| 2018 | 7        | 15.91%  |
| 2017 | 6        | 13.64%  |
| 2020 | 5        | 11.36%  |
| 2015 | 3        | 6.82%   |
| 2010 | 3        | 6.82%   |
| 2014 | 2        | 4.55%   |
| 2013 | 2        | 4.55%   |
| 2012 | 2        | 4.55%   |
| 2009 | 2        | 4.55%   |
| 2022 | 1        | 2.27%   |
| 2021 | 1        | 2.27%   |
| 2016 | 1        | 2.27%   |
| 2011 | 1        | 2.27%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 44       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 44       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 44       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 15       | 34.09%  |
| 32.01-64.0  | 12       | 27.27%  |
| 8.01-16.0   | 8        | 18.18%  |
| 4.01-8.0    | 6        | 13.64%  |
| 3.01-4.0    | 1        | 2.27%   |
| 24.01-32.0  | 1        | 2.27%   |
| 64.01-256.0 | 1        | 2.27%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 13       | 26%     |
| 4.01-8.0   | 12       | 24%     |
| 1.01-2.0   | 8        | 16%     |
| 8.01-16.0  | 6        | 12%     |
| 3.01-4.0   | 5        | 10%     |
| 16.01-24.0 | 3        | 6%      |
| 0.01-0.5   | 2        | 4%      |
| 0.51-1.0   | 1        | 2%      |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 12       | 27.27%  |
| 3      | 11       | 25%     |
| 2      | 9        | 20.45%  |
| 4      | 5        | 11.36%  |
| 5      | 4        | 9.09%   |
| 6      | 2        | 4.55%   |
| 7      | 1        | 2.27%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 30       | 66.67%  |
| Yes       | 15       | 33.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 44       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 26       | 59.09%  |
| No        | 18       | 40.91%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 24       | 53.33%  |
| No        | 21       | 46.67%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country        | Desktops | Percent |
|----------------|----------|---------|
| USA            | 11       | 25%     |
| Germany        | 4        | 9.09%   |
| UK             | 3        | 6.82%   |
| Russia         | 2        | 4.55%   |
| Poland         | 2        | 4.55%   |
| Mexico         | 2        | 4.55%   |
| Canada         | 2        | 4.55%   |
| Sweden         | 1        | 2.27%   |
| Spain          | 1        | 2.27%   |
| Portugal       | 1        | 2.27%   |
| Netherlands    | 1        | 2.27%   |
| Lebanon        | 1        | 2.27%   |
| Italy          | 1        | 2.27%   |
| India          | 1        | 2.27%   |
| Hungary        | 1        | 2.27%   |
| Greece         | 1        | 2.27%   |
| Czechia        | 1        | 2.27%   |
| Cyprus         | 1        | 2.27%   |
| Colombia       | 1        | 2.27%   |
| Brazil         | 1        | 2.27%   |
| Bahrain        | 1        | 2.27%   |
| Austria        | 1        | 2.27%   |
| Australia      | 1        | 2.27%   |
| Argentina      | 1        | 2.27%   |
| Åland Islands | 1        | 2.27%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Zell am See    | 1        | 2.27%   |
| Wroclaw        | 1        | 2.27%   |
| Wrexham        | 1        | 2.27%   |
| Wells          | 1        | 2.27%   |
| Warsaw         | 1        | 2.27%   |
| Stow           | 1        | 2.27%   |
| Springfield    | 1        | 2.27%   |
| Sonora         | 1        | 2.27%   |
| Shadrinsk      | 1        | 2.27%   |
| Salt Lake City | 1        | 2.27%   |
| Portland       | 1        | 2.27%   |
| Phoenix        | 1        | 2.27%   |
| Passos         | 1        | 2.27%   |
| Oberursel      | 1        | 2.27%   |
| Nicosia        | 1        | 2.27%   |
| New Haven      | 1        | 2.27%   |
| Moscow         | 1        | 2.27%   |
| Montreal       | 1        | 2.27%   |
| Monterrey      | 1        | 2.27%   |
| Milton Keynes  | 1        | 2.27%   |
| Mexico City    | 1        | 2.27%   |
| Mariehamn      | 1        | 2.27%   |
| Manama         | 1        | 2.27%   |
| Longview       | 1        | 2.27%   |
| Lisbon         | 1        | 2.27%   |
| Krizanov       | 1        | 2.27%   |
| Kista          | 1        | 2.27%   |
| Győr          | 1        | 2.27%   |
| Ernakulam      | 1        | 2.27%   |
| Chicago        | 1        | 2.27%   |
| Canovelles     | 1        | 2.27%   |
| Candiac        | 1        | 2.27%   |
| Buenos Aires   | 1        | 2.27%   |
| Bristol        | 1        | 2.27%   |
| Brisbane       | 1        | 2.27%   |
| Brindisi       | 1        | 2.27%   |
| Bremen         | 1        | 2.27%   |
| Bogotá        | 1        | 2.27%   |
| Bielefeld      | 1        | 2.27%   |
| Beirut         | 1        | 2.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 19       | 27     | 18.1%   |
| Seagate                   | 17       | 28     | 16.19%  |
| Samsung Electronics       | 15       | 26     | 14.29%  |
| Kingston                  | 8        | 11     | 7.62%   |
| Toshiba                   | 6        | 8      | 5.71%   |
| SanDisk                   | 6        | 8      | 5.71%   |
| Unknown                   | 5        | 6      | 4.76%   |
| Crucial                   | 4        | 6      | 3.81%   |
| China                     | 3        | 3      | 2.86%   |
| Phison                    | 2        | 2      | 1.9%    |
| Intel                     | 2        | 3      | 1.9%    |
| Hitachi                   | 2        | 2      | 1.9%    |
| HGST                      | 2        | 2      | 1.9%    |
| A-DATA Technology         | 2        | 2      | 1.9%    |
| XPG                       | 1        | 1      | 0.95%   |
| Transcend                 | 1        | 1      | 0.95%   |
| SPCC                      | 1        | 1      | 0.95%   |
| SK hynix                  | 1        | 1      | 0.95%   |
| Silicon Motion            | 1        | 1      | 0.95%   |
| Realtek Semiconductor     | 1        | 1      | 0.95%   |
| PNY                       | 1        | 1      | 0.95%   |
| Micron/Crucial Technology | 1        | 1      | 0.95%   |
| Micron Technology         | 1        | 2      | 0.95%   |
| Leven                     | 1        | 1      | 0.95%   |
| Intenso                   | 1        | 1      | 0.95%   |
| 2-Power                   | 1        | 1      | 0.95%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Unknown SD/MMC/MS PRO 64GB       | 3        | 2.36%   |
| Kingston SA400S37240G 240GB SSD  | 3        | 2.36%   |
| Crucial CT500MX500SSD1 500GB     | 3        | 2.36%   |
| WDC WD10EZEX-60WN4A0 1TB         | 2        | 1.57%   |
| Toshiba DT01ACA300 3TB           | 2        | 1.57%   |
| Seagate ST2000DM006-2DM164 2TB   | 2        | 1.57%   |
| Seagate ST1000DM010-2EP102 1TB   | 2        | 1.57%   |
| Seagate ST1000DM003-1SB102 1TB   | 2        | 1.57%   |
| SanDisk NVMe SSD Drive 500GB     | 2        | 1.57%   |
| Samsung SSD 970 EVO 1TB          | 2        | 1.57%   |
| XPG GAMMIX S50 1TB               | 1        | 0.79%   |
| WDC WDS512G1X0C-00ENX0 512GB     | 1        | 0.79%   |
| WDC WDS500G3XHC-00SJG0 500GB     | 1        | 0.79%   |
| WDC WDS500G3X0C-00SJG0 500GB     | 1        | 0.79%   |
| WDC WDS500G2B0B-00YS70 500GB SSD | 1        | 0.79%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 1        | 0.79%   |
| WDC WD800JD-00MSA1 80GB          | 1        | 0.79%   |
| WDC WD7500BPKT-75PK4T0 752GB     | 1        | 0.79%   |
| WDC WD6400AAKS-22A7B2 640GB      | 1        | 0.79%   |
| WDC WD5000AAVS-00ZTB0 500GB      | 1        | 0.79%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 1        | 0.79%   |
| WDC WD40EZRZ-22GXCB0 4TB         | 1        | 0.79%   |
| WDC WD2500BEVT-60ZCT1 250GB      | 1        | 0.79%   |
| WDC WD20EZRZ-60Z5HB0 2TB         | 1        | 0.79%   |
| WDC WD20EZBX-00AYRA0 2TB         | 1        | 0.79%   |
| WDC WD2003FZEX-00SRLA0 2TB       | 1        | 0.79%   |
| WDC WD15EADS-11R6B1 1TB          | 1        | 0.79%   |
| WDC WD10EZEX-22MFCA0 1TB         | 1        | 0.79%   |
| WDC WD10EZEX-21WN4A0 1TB         | 1        | 0.79%   |
| WDC WD10EZEX-00KUWA0 1TB         | 1        | 0.79%   |
| WDC WD10EAVS-00D7B1 1TB          | 1        | 0.79%   |
| WDC WD10EADS-00M2B0 1TB          | 1        | 0.79%   |
| WDC WD1002FAEX-00Z3A0 1TB        | 1        | 0.79%   |
| Unknown MMC Card  64GB           | 1        | 0.79%   |
| Unknown MMC Card  4GB            | 1        | 0.79%   |
| Unknown MMC Card  128GB          | 1        | 0.79%   |
| Transcend TS120GSSD220S 120GB    | 1        | 0.79%   |
| Toshiba MQ04ABF100 1TB           | 1        | 0.79%   |
| Toshiba MQ01ABD100 1TB           | 1        | 0.79%   |
| Toshiba MK4058GSX 400GB          | 1        | 0.79%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 17       | 28     | 34.69%  |
| WDC                 | 16       | 22     | 32.65%  |
| Toshiba             | 6        | 8      | 12.24%  |
| Unknown             | 3        | 3      | 6.12%   |
| Samsung Electronics | 2        | 2      | 4.08%   |
| Hitachi             | 2        | 2      | 4.08%   |
| HGST                | 2        | 2      | 4.08%   |
| Intenso             | 1        | 1      | 2.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 8        | 11     | 23.53%  |
| Kingston            | 8        | 11     | 23.53%  |
| Crucial             | 4        | 6      | 11.76%  |
| China               | 3        | 3      | 8.82%   |
| WDC                 | 2        | 2      | 5.88%   |
| SanDisk             | 2        | 2      | 5.88%   |
| Transcend           | 1        | 1      | 2.94%   |
| SPCC                | 1        | 1      | 2.94%   |
| PNY                 | 1        | 1      | 2.94%   |
| Micron Technology   | 1        | 1      | 2.94%   |
| Leven               | 1        | 1      | 2.94%   |
| A-DATA Technology   | 1        | 1      | 2.94%   |
| 2-Power             | 1        | 1      | 2.94%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 36       | 68     | 41.86%  |
| SSD  | 27       | 42     | 31.4%   |
| NVMe | 21       | 34     | 24.42%  |
| MMC  | 2        | 3      | 2.33%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 41       | 102    | 57.75%  |
| NVMe | 21       | 34     | 29.58%  |
| SAS  | 7        | 8      | 9.86%   |
| MMC  | 2        | 3      | 2.82%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 31       | 52     | 41.89%  |
| 0.51-1.0   | 25       | 34     | 33.78%  |
| 1.01-2.0   | 10       | 14     | 13.51%  |
| 4.01-10.0  | 4        | 6      | 5.41%   |
| 2.01-3.0   | 3        | 3      | 4.05%   |
| 3.01-4.0   | 1        | 1      | 1.35%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 16       | 34.04%  |
| 1001-2000      | 9        | 19.15%  |
| 101-250        | 5        | 10.64%  |
| 501-1000       | 5        | 10.64%  |
| 251-500        | 4        | 8.51%   |
| 21-50          | 2        | 4.26%   |
| 1-20           | 2        | 4.26%   |
| 51-100         | 2        | 4.26%   |
| 2001-3000      | 1        | 2.13%   |
| Unknown        | 1        | 2.13%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 13       | 27.66%  |
| 1-20           | 11       | 23.4%   |
| 51-100         | 5        | 10.64%  |
| 501-1000       | 4        | 8.51%   |
| 251-500        | 3        | 6.38%   |
| 21-50          | 3        | 6.38%   |
| 1001-2000      | 3        | 6.38%   |
| More than 3000 | 2        | 4.26%   |
| 2001-3000      | 2        | 4.26%   |
| Unknown        | 1        | 2.13%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| WDC WD5000AAKX-60U6AA0 500GB     | 1        | 1      | 7.14%   |
| WDC WD10EADS-00M2B0 1TB          | 1        | 1      | 7.14%   |
| WDC WD1002FAEX-00Z3A0 1TB        | 1        | 2      | 7.14%   |
| Toshiba MQ01ABD100 1TB           | 1        | 1      | 7.14%   |
| Toshiba MK4058GSX 400GB          | 1        | 1      | 7.14%   |
| Seagate ST9500420AS 500GB        | 1        | 1      | 7.14%   |
| Seagate ST31000524AS 1TB         | 1        | 1      | 7.14%   |
| Seagate ST2000VX000-1CU164 2TB   | 1        | 1      | 7.14%   |
| Seagate ST2000DM006-2DM164 2TB   | 1        | 1      | 7.14%   |
| Kingston SV300S37A120G 120GB SSD | 1        | 1      | 7.14%   |
| Kingston SUV400S37240G 240GB SSD | 1        | 1      | 7.14%   |
| Hitachi HTS725050A9A364 500GB    | 1        | 1      | 7.14%   |
| Hitachi HCP725050GLA380 500GB    | 1        | 1      | 7.14%   |
| China SATA3 240GB SSD            | 1        | 1      | 7.14%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Seagate  | 4        | 4      | 30.77%  |
| WDC      | 3        | 4      | 23.08%  |
| Kingston | 2        | 2      | 15.38%  |
| Hitachi  | 2        | 2      | 15.38%  |
| Toshiba  | 1        | 2      | 7.69%   |
| China    | 1        | 1      | 7.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 4        | 4      | 40%     |
| WDC     | 3        | 4      | 30%     |
| Hitachi | 2        | 2      | 20%     |
| Toshiba | 1        | 2      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 9        | 12     | 75%     |
| SSD  | 3        | 3      | 25%     |

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
| Works    | 33       | 87     | 55.93%  |
| Detected | 15       | 45     | 25.42%  |
| Malfunc  | 11       | 15     | 18.64%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 29       | 42.03%  |
| AMD                       | 17       | 24.64%  |
| SanDisk                   | 7        | 10.14%  |
| Samsung Electronics       | 6        | 8.7%    |
| Realtek Semiconductor     | 2        | 2.9%    |
| Phison Electronics        | 2        | 2.9%    |
| SK hynix                  | 1        | 1.45%   |
| Silicon Motion            | 1        | 1.45%   |
| Micron/Crucial Technology | 1        | 1.45%   |
| Micron Technology         | 1        | 1.45%   |
| ASMedia Technology        | 1        | 1.45%   |
| ADATA Technology          | 1        | 1.45%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 15       | 18.99%  |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 7        | 8.86%   |
| Intel SATA Controller [RAID mode]                                              | 4        | 5.06%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 4        | 5.06%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3        | 3.8%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3        | 3.8%    |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 2        | 2.53%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2        | 2.53%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2        | 2.53%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2        | 2.53%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2        | 2.53%   |
| AMD FCH SATA Controller D                                                      | 2        | 2.53%   |
| AMD 500 Series Chipset SATA Controller                                         | 2        | 2.53%   |
| AMD 400 Series Chipset SATA Controller                                         | 2        | 2.53%   |
| AMD 300 Series Chipset SATA Controller                                         | 2        | 2.53%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1        | 1.27%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 1        | 1.27%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                             | 1        | 1.27%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1        | 1.27%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1        | 1.27%   |
| SanDisk WD Black NVMe SSD                                                      | 1        | 1.27%   |
| SanDisk NVMe Controller                                                        | 1        | 1.27%   |
| Samsung NVMe SSD Controller 980                                                | 1        | 1.27%   |
| Realtek RTS5763DL NVMe SSD Controller                                          | 1        | 1.27%   |
| Realtek NVMe Controller                                                        | 1        | 1.27%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1        | 1.27%   |
| Phison E12 NVMe Controller                                                     | 1        | 1.27%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                | 1        | 1.27%   |
| Micron NVMe Storage Controller                                                 | 1        | 1.27%   |
| Intel SSD 660P Series                                                          | 1        | 1.27%   |
| Intel SSD 600P Series                                                          | 1        | 1.27%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1        | 1.27%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 1        | 1.27%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 1        | 1.27%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1        | 1.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 1        | 1.27%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 1        | 1.27%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 1        | 1.27%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 1        | 1.27%   |
| ADATA XPG GAMMIX S50 NVMe SSD                                                  | 1        | 1.27%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 40       | 60.61%  |
| NVMe | 21       | 31.82%  |
| RAID | 4        | 6.06%   |
| IDE  | 1        | 1.52%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 27       | 61.36%  |
| AMD    | 17       | 38.64%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| AMD Ryzen 5 3600X 6-Core Processor            | 3        | 6.67%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 2        | 4.44%   |
| Intel Core i7 CPU 870 @ 2.93GHz               | 2        | 4.44%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 2        | 4.44%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 2        | 4.44%   |
| AMD Ryzen 5 3600 6-Core Processor             | 2        | 4.44%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 2        | 4.44%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz           | 1        | 2.22%   |
| Intel Genuine CPU 0000 @ 2.10GHz              | 1        | 2.22%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 1        | 2.22%   |
| Intel Core i7-7700K CPU @ 4.20GHz             | 1        | 2.22%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 1        | 2.22%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 1        | 2.22%   |
| Intel Core i7 CPU 860 @ 2.80GHz               | 1        | 2.22%   |
| Intel Core i5-9600K CPU @ 3.70GHz             | 1        | 2.22%   |
| Intel Core i5-9400F CPU @ 2.90GHz             | 1        | 2.22%   |
| Intel Core i5-9400 CPU @ 2.90GHz              | 1        | 2.22%   |
| Intel Core i5-6600 CPU @ 3.30GHz              | 1        | 2.22%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 1        | 2.22%   |
| Intel Core i5-6400 CPU @ 2.70GHz              | 1        | 2.22%   |
| Intel Core i5-4670 CPU @ 3.40GHz              | 1        | 2.22%   |
| Intel Core i5-4590T CPU @ 2.00GHz             | 1        | 2.22%   |
| Intel Core i5-10400F CPU @ 2.90GHz            | 1        | 2.22%   |
| Intel Core i3-8100 CPU @ 3.60GHz              | 1        | 2.22%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 1        | 2.22%   |
| Intel Core i3 CPU 540 @ 3.07GHz               | 1        | 2.22%   |
| Intel Core 2 Quad CPU Q9650 @ 3.00GHz         | 1        | 2.22%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 1        | 2.22%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 1        | 2.22%   |
| AMD Ryzen 7 5800X3D 8-Core Processor          | 1        | 2.22%   |
| AMD Ryzen 7 3800X 8-Core Processor            | 1        | 2.22%   |
| AMD Ryzen 7 2700 Eight-Core Processor         | 1        | 2.22%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 1        | 2.22%   |
| AMD E1-1200 APU with Radeon HD Graphics       | 1        | 2.22%   |
| AMD Athlon 200GE with Radeon Vega Graphics    | 1        | 2.22%   |
| AMD A8-9600 RADEON R7, 10 COMPUTE CORES 4C+6G | 1        | 2.22%   |
| AMD A8-6600K APU with Radeon HD Graphics      | 1        | 2.22%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| Intel Core i5     | 11       | 24.44%  |
| Intel Core i7     | 9        | 20%     |
| AMD Ryzen 5       | 8        | 17.78%  |
| AMD Ryzen 7       | 5        | 11.11%  |
| Intel Core i3     | 3        | 6.67%   |
| AMD A8            | 2        | 4.44%   |
| Intel Xeon        | 1        | 2.22%   |
| Intel Genuine     | 1        | 2.22%   |
| Intel Core 2 Quad | 1        | 2.22%   |
| Intel Celeron     | 1        | 2.22%   |
| AMD Ryzen 9       | 1        | 2.22%   |
| AMD E1            | 1        | 2.22%   |
| AMD Athlon        | 1        | 2.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 16       | 35.56%  |
| 6      | 15       | 33.33%  |
| 8      | 6        | 13.33%  |
| 2      | 6        | 13.33%  |
| 16     | 1        | 2.22%   |
| 12     | 1        | 2.22%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 43       | 97.73%  |
| 2      | 1        | 2.27%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 29       | 65.91%  |
| 1      | 15       | 34.09%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 44       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 10       | 22.22%  |
| 0x506e3    | 5        | 11.11%  |
| 0x08701021 | 5        | 11.11%  |
| 0x906ea    | 4        | 8.89%   |
| 0x0a201016 | 3        | 6.67%   |
| 0x306c3    | 2        | 4.44%   |
| 0x306a9    | 2        | 4.44%   |
| 0x106e5    | 2        | 4.44%   |
| 0xa0653    | 1        | 2.22%   |
| 0x906ed    | 1        | 2.22%   |
| 0x906eb    | 1        | 2.22%   |
| 0x906e9    | 1        | 2.22%   |
| 0x306f2    | 1        | 2.22%   |
| 0x20655    | 1        | 2.22%   |
| 0x1067a    | 1        | 2.22%   |
| 0x0a20120a | 1        | 2.22%   |
| 0x08701013 | 1        | 2.22%   |
| 0x0810100b | 1        | 2.22%   |
| 0x0600611a | 1        | 2.22%   |
| 0x0500010d | 1        | 2.22%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| KabyLake      | 9        | 20%     |
| Zen 2         | 7        | 15.56%  |
| Skylake       | 5        | 11.11%  |
| Zen 3         | 4        | 8.89%   |
| Nehalem       | 3        | 6.67%   |
| Haswell       | 3        | 6.67%   |
| Zen+          | 2        | 4.44%   |
| Zen           | 2        | 4.44%   |
| IvyBridge     | 2        | 4.44%   |
| Westmere      | 1        | 2.22%   |
| SandyBridge   | 1        | 2.22%   |
| Piledriver    | 1        | 2.22%   |
| Penryn        | 1        | 2.22%   |
| Goldmont plus | 1        | 2.22%   |
| Excavator     | 1        | 2.22%   |
| CometLake     | 1        | 2.22%   |
| Bobcat        | 1        | 2.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 22       | 47.83%  |
| AMD               | 15       | 32.61%  |
| Intel             | 8        | 17.39%  |
| ASPEED Technology | 1        | 2.17%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia GP104 [GeForce GTX 1080]                                             | 3        | 6.38%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 3        | 6.38%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 2        | 4.26%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2        | 4.26%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 4.26%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 4.26%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 2        | 4.26%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 2.13%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 2.13%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 2.13%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 2.13%   |
| Nvidia GT200 [GeForce GTX 260]                                              | 1        | 2.13%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 2.13%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 2.13%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 2.13%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 2.13%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 2.13%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 2.13%   |
| Nvidia GK107 [GeForce GT 740]                                               | 1        | 2.13%   |
| Nvidia GF106GL [Quadro 2000]                                                | 1        | 2.13%   |
| Nvidia GA102 [GeForce RTX 3080 Lite Hash Rate]                              | 1        | 2.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 2.13%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 2.13%   |
| Intel HD Graphics 530                                                       | 1        | 2.13%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1        | 2.13%   |
| Intel Core Processor Integrated Graphics Controller                         | 1        | 2.13%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 1        | 2.13%   |
| ASPEED Technology ASPEED Graphics Family                                    | 1        | 2.13%   |
| AMD Wrestler [Radeon HD 7310]                                               | 1        | 2.13%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 1        | 2.13%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 1        | 2.13%   |
| AMD Tonga PRO [Radeon R9 285/380]                                           | 1        | 2.13%   |
| AMD Richland [Radeon HD 8570D]                                              | 1        | 2.13%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 1        | 2.13%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 1        | 2.13%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 1        | 2.13%   |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                            | 1        | 2.13%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 1        | 2.13%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 20       | 45.45%  |
| 1 x AMD         | 15       | 34.09%  |
| 1 x Intel       | 7        | 15.91%  |
| 2 x Nvidia      | 1        | 2.27%   |
| Nvidia + ASPEED | 1        | 2.27%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 27       | 61.36%  |
| Proprietary | 15       | 34.09%  |
| Unknown     | 2        | 4.55%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 16       | 36.36%  |
| 7.01-8.0   | 8        | 18.18%  |
| 1.01-2.0   | 8        | 18.18%  |
| 5.01-6.0   | 4        | 9.09%   |
| 8.01-16.0  | 3        | 6.82%   |
| 3.01-4.0   | 2        | 4.55%   |
| 0.01-0.5   | 2        | 4.55%   |
| 0.51-1.0   | 1        | 2.27%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 11       | 24.44%  |
| Acer                 | 5        | 11.11%  |
| Hewlett-Packard      | 4        | 8.89%   |
| AOC                  | 4        | 8.89%   |
| Ancor Communications | 4        | 8.89%   |
| Goldstar             | 3        | 6.67%   |
| Iiyama               | 2        | 4.44%   |
| MSI                  | 1        | 2.22%   |
| Lenovo               | 1        | 2.22%   |
| Konka                | 1        | 2.22%   |
| Kogan                | 1        | 2.22%   |
| KOC                  | 1        | 2.22%   |
| JRY                  | 1        | 2.22%   |
| Idek Iiyama          | 1        | 2.22%   |
| Hitachi              | 1        | 2.22%   |
| Gigabyte Technology  | 1        | 2.22%   |
| FOX                  | 1        | 2.22%   |
| Dell                 | 1        | 2.22%   |
| ASUSTek Computer     | 1        | 2.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch     | 2        | 4.17%   |
| Samsung Electronics T27B300 SAM0933 1920x1080 598x336mm 27.0-inch     | 1        | 2.08%   |
| Samsung Electronics SyncMaster SAM0524 1920x1080 477x268mm 21.5-inch  | 1        | 2.08%   |
| Samsung Electronics SyncMaster SAM02FE 1680x1050 433x271mm 20.1-inch  | 1        | 2.08%   |
| Samsung Electronics SMS24A350H SAM07D6 1920x1080 531x299mm 24.0-inch  | 1        | 2.08%   |
| Samsung Electronics S24F350 SAM0D22 1920x1080 521x293mm 23.5-inch     | 1        | 2.08%   |
| Samsung Electronics LCD Monitor SAM02EB 1920x540                      | 1        | 2.08%   |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch   | 1        | 2.08%   |
| Samsung Electronics LC24RG50 SAM0F91 1920x1080 532x304mm 24.1-inch    | 1        | 2.08%   |
| Samsung Electronics C27R50x SAM0F9E 1920x1080 598x336mm 27.0-inch     | 1        | 2.08%   |
| MSI G24C4 MSI3BA0 1920x1080 521x293mm 23.5-inch                       | 1        | 2.08%   |
| Lenovo LEN T24i-10 LEN61CE 1920x1080 527x296mm 23.8-inch              | 1        | 2.08%   |
| Konka LCDTV KOA0030 1920x540 708x398mm 32.0-inch                      | 1        | 2.08%   |
| Kogan KAMN34FXQULA KGN3400 3440x1440 797x334mm 34.0-inch              | 1        | 2.08%   |
| KOC SXGA85_ANALOG KOC0482 1280x1024 365x292mm 18.4-inch               | 1        | 2.08%   |
| JRY VIZTA JRY2700 1920x1080 598x336mm 27.0-inch                       | 1        | 2.08%   |
| Iiyama PL3466WQ IVM761A 3440x1440 797x334mm 34.0-inch                 | 1        | 2.08%   |
| Iiyama PL2409HD IVM560C 1920x1080 521x293mm 23.5-inch                 | 1        | 2.08%   |
| Idek Iiyama LCD Monitor PL2760Q 2560x1440                             | 1        | 2.08%   |
| Hitachi HISENSE HEC002F 3840x2160 1872x1053mm 84.6-inch               | 1        | 2.08%   |
| Hewlett-Packard V27e HPN36B1 1920x1080 598x336mm 27.0-inch            | 1        | 2.08%   |
| Hewlett-Packard TouchSmart HWP4218 1600x900 443x249mm 20.0-inch       | 1        | 2.08%   |
| Hewlett-Packard E240c HWP327C 1920x1080 510x290mm 23.1-inch           | 1        | 2.08%   |
| Hewlett-Packard 27w HPN3494 1920x1080 598x336mm 27.0-inch             | 1        | 2.08%   |
| Goldstar ULTRAWIDE GSM76FA 2560x1080 531x298mm 24.0-inch              | 1        | 2.08%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 1        | 2.08%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 1        | 2.08%   |
| Goldstar 22EN43 GSM59D8 1920x1080 477x268mm 21.5-inch                 | 1        | 2.08%   |
| Gigabyte Technology M27Q GBT270D 2560x1440 596x335mm 26.9-inch        | 1        | 2.08%   |
| FOX FBC TV FOX9C01 1366x768 698x393mm 31.5-inch                       | 1        | 2.08%   |
| Dell U3219Q DELA124 3840x2160 697x392mm 31.5-inch                     | 1        | 2.08%   |
| ASUSTek Computer VG279QM AUS278F 1920x1080 598x336mm 27.0-inch        | 1        | 2.08%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                   | 1        | 2.08%   |
| AOC Q2963 AOC2963 2560x1080 673x284mm 28.8-inch                       | 1        | 2.08%   |
| AOC Q2963 AOC2963 2560x1080 670x280mm 28.6-inch                       | 1        | 2.08%   |
| AOC Q27G2G3R3B AOC2702 2560x1440 600x340mm 27.2-inch                  | 1        | 2.08%   |
| AOC 2460G5 AOC246A 1920x1080 530x300mm 24.0-inch                      | 1        | 2.08%   |
| Ancor Communications VW246 ACI24F2 1920x1080 531x299mm 24.0-inch      | 1        | 2.08%   |
| Ancor Communications ROG PG348Q ACI3433 3440x1440 798x335mm 34.1-inch | 1        | 2.08%   |
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch | 1        | 2.08%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 20       | 46.51%  |
| 2560x1440 (QHD)    | 6        | 13.95%  |
| 3440x1440          | 5        | 11.63%  |
| 3840x2160 (4K)     | 4        | 9.3%    |
| 2560x1080          | 2        | 4.65%   |
| 3840x1080          | 1        | 2.33%   |
| 1920x540           | 1        | 2.33%   |
| 1680x1050 (WSXGA+) | 1        | 2.33%   |
| 1600x900 (HD+)     | 1        | 2.33%   |
| 1366x768 (WXGA)    | 1        | 2.33%   |
| 1280x1024 (SXGA)   | 1        | 2.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 11       | 24.44%  |
| 34      | 6        | 13.33%  |
| 24      | 5        | 11.11%  |
| 23      | 5        | 11.11%  |
| 21      | 5        | 11.11%  |
| 31      | 3        | 6.67%   |
| 20      | 2        | 4.44%   |
| Unknown | 2        | 4.44%   |
| 84      | 1        | 2.22%   |
| 52      | 1        | 2.22%   |
| 48      | 1        | 2.22%   |
| 33      | 1        | 2.22%   |
| 28      | 1        | 2.22%   |
| 18      | 1        | 2.22%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 20       | 45.45%  |
| 701-800     | 7        | 15.91%  |
| 401-500     | 7        | 15.91%  |
| 601-700     | 4        | 9.09%   |
| 1001-1500   | 2        | 4.55%   |
| Unknown     | 2        | 4.55%   |
| 351-400     | 1        | 2.27%   |
| 1501-2000   | 1        | 2.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 30       | 73.17%  |
| 21/9    | 7        | 17.07%  |
| 5/4     | 1        | 2.44%   |
| 32/9    | 1        | 2.44%   |
| 16/10   | 1        | 2.44%   |
| Unknown | 1        | 2.44%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 14       | 31.11%  |
| 301-350        | 11       | 24.44%  |
| 351-500        | 10       | 22.22%  |
| 151-200        | 3        | 6.67%   |
| More than 1000 | 2        | 4.44%   |
| 251-300        | 2        | 4.44%   |
| Unknown        | 2        | 4.44%   |
| 501-1000       | 1        | 2.22%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 24       | 60%     |
| 101-120 | 10       | 25%     |
| 1-50    | 2        | 5%      |
| Unknown | 2        | 5%      |
| 161-240 | 1        | 2.5%    |
| 121-160 | 1        | 2.5%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 32       | 71.11%  |
| 2     | 10       | 22.22%  |
| 0     | 3        | 6.67%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 28       | 43.75%  |
| Intel                           | 23       | 35.94%  |
| Broadcom                        | 3        | 4.69%   |
| Ralink Technology               | 2        | 3.13%   |
| Qualcomm Atheros                | 2        | 3.13%   |
| TP-Link                         | 1        | 1.56%   |
| Ralink                          | 1        | 1.56%   |
| Qualcomm Atheros Communications | 1        | 1.56%   |
| Qualcomm                        | 1        | 1.56%   |
| NetGear                         | 1        | 1.56%   |
| Microsoft                       | 1        | 1.56%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller         | 22       | 28.95%  |
| Intel I211 Gigabit Network Connection                                     | 6        | 7.89%   |
| Realtek RTL8125 2.5GbE Controller                                         | 5        | 6.58%   |
| Intel Wi-Fi 6 AX200                                                       | 5        | 6.58%   |
| Intel Ethernet Connection (2) I219-V                                      | 5        | 6.58%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                  | 2        | 2.63%   |
| Intel Wireless 7265                                                       | 2        | 2.63%   |
| Intel Ethernet Connection (7) I219-V                                      | 2        | 2.63%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                          | 2        | 2.63%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                     | 2        | 2.63%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                           | 2        | 2.63%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                       | 1        | 1.32%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                        | 1        | 1.32%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                           | 1        | 1.32%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                           | 1        | 1.32%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                     | 1        | 1.32%   |
| Ralink RT2501/RT2573 Wireless Adapter                                     | 1        | 1.32%   |
| Ralink MT7601U Wireless Adapter                                           | 1        | 1.32%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                    | 1        | 1.32%   |
| Qualcomm Fairphone 4 5G                                                   | 1        | 1.32%   |
| Qualcomm Atheros AR9271 802.11n                                           | 1        | 1.32%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                          | 1        | 1.32%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)            | 1        | 1.32%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet            | 1        | 1.32%   |
| NetGear Nighthawk A7000 802.11ac Wireless Adapter AC1900 [Realtek 8814AU] | 1        | 1.32%   |
| Microsoft Xbox 360 Wireless Adapter                                       | 1        | 1.32%   |
| Intel Wireless-AC 9260                                                    | 1        | 1.32%   |
| Intel Ethernet Connection I217-LM                                         | 1        | 1.32%   |
| Intel Ethernet Connection (11) I219-V                                     | 1        | 1.32%   |
| Intel Cannon Lake PCH CNVi WiFi                                           | 1        | 1.32%   |
| Broadcom BCM43228 802.11a/b/g/n                                           | 1        | 1.32%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller       | 1        | 1.32%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 11       | 40.74%  |
| Realtek Semiconductor           | 5        | 18.52%  |
| Ralink Technology               | 2        | 7.41%   |
| Qualcomm Atheros                | 2        | 7.41%   |
| Broadcom                        | 2        | 7.41%   |
| TP-Link                         | 1        | 3.7%    |
| Ralink                          | 1        | 3.7%    |
| Qualcomm Atheros Communications | 1        | 3.7%    |
| NetGear                         | 1        | 3.7%    |
| Microsoft                       | 1        | 3.7%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                       | 5        | 18.52%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                  | 2        | 7.41%   |
| Intel Wireless 7265                                                       | 2        | 7.41%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                          | 2        | 7.41%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                       | 1        | 3.7%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                        | 1        | 3.7%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                           | 1        | 3.7%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                           | 1        | 3.7%    |
| Ralink RT2501/RT2573 Wireless Adapter                                     | 1        | 3.7%    |
| Ralink MT7601U Wireless Adapter                                           | 1        | 3.7%    |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                    | 1        | 3.7%    |
| Qualcomm Atheros AR9271 802.11n                                           | 1        | 3.7%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                          | 1        | 3.7%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)            | 1        | 3.7%    |
| NetGear Nighthawk A7000 802.11ac Wireless Adapter AC1900 [Realtek 8814AU] | 1        | 3.7%    |
| Microsoft Xbox 360 Wireless Adapter                                       | 1        | 3.7%    |
| Intel Wireless-AC 9260                                                    | 1        | 3.7%    |
| Intel Cannon Lake PCH CNVi WiFi                                           | 1        | 3.7%    |
| Broadcom BCM43228 802.11a/b/g/n                                           | 1        | 3.7%    |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller       | 1        | 3.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 27       | 56.25%  |
| Intel                 | 17       | 35.42%  |
| Broadcom              | 2        | 4.17%   |
| Qualcomm Atheros      | 1        | 2.08%   |
| Qualcomm              | 1        | 2.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 22       | 44.9%   |
| Intel I211 Gigabit Network Connection                             | 6        | 12.24%  |
| Realtek RTL8125 2.5GbE Controller                                 | 5        | 10.2%   |
| Intel Ethernet Connection (2) I219-V                              | 5        | 10.2%   |
| Intel Ethernet Connection (7) I219-V                              | 2        | 4.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 4.08%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2        | 4.08%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 2.04%   |
| Qualcomm Fairphone 4 5G                                           | 1        | 2.04%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 2.04%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 2.04%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 2.04%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 44       | 62.86%  |
| WiFi     | 26       | 37.14%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 33       | 71.74%  |
| WiFi     | 13       | 28.26%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 22       | 50%     |
| 2     | 19       | 43.18%  |
| 3     | 3        | 6.82%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 34       | 75.56%  |
| Yes  | 11       | 24.44%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 11       | 45.83%  |
| Cambridge Silicon Radio | 6        | 25%     |
| Realtek Semiconductor   | 3        | 12.5%   |
| Broadcom                | 2        | 8.33%   |
| ASUSTek Computer        | 2        | 8.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6        | 25%     |
| Intel AX200 Bluetooth                               | 5        | 20.83%  |
| Realtek  Bluetooth 4.2 Adapter                      | 2        | 8.33%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2        | 8.33%   |
| Intel Bluetooth wireless interface                  | 2        | 8.33%   |
| Realtek Bluetooth Radio                             | 1        | 4.17%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 4.17%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 4.17%   |
| Broadcom HP Portable Bumble Bee                     | 1        | 4.17%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 4.17%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 4.17%   |
| ASUS Bluetooth Radio                                | 1        | 4.17%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 27       | 31.76%  |
| Nvidia                 | 21       | 24.71%  |
| AMD                    | 20       | 23.53%  |
| Corsair                | 3        | 3.53%   |
| C-Media Electronics    | 3        | 3.53%   |
| Razer USA              | 2        | 2.35%   |
| Kingston Technology    | 2        | 2.35%   |
| Tenx Technology        | 1        | 1.18%   |
| Plantronics            | 1        | 1.18%   |
| Logitech               | 1        | 1.18%   |
| Hewlett-Packard        | 1        | 1.18%   |
| Generalplus Technology | 1        | 1.18%   |
| ELMCU                  | 1        | 1.18%   |
| Astro Gaming           | 1        | 1.18%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 9        | 9.18%   |
| Intel 200 Series PCH HD Audio                                              | 7        | 7.14%   |
| Nvidia GP104 High Definition Audio Controller                              | 4        | 4.08%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4        | 4.08%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4        | 4.08%   |
| Nvidia TU106 High Definition Audio Controller                              | 3        | 3.06%   |
| Intel Cannon Lake PCH cAVS                                                 | 3        | 3.06%   |
| AMD Navi 10 HDMI Audio                                                     | 3        | 3.06%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3        | 3.06%   |
| Nvidia TU116 High Definition Audio Controller                              | 2        | 2.04%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 2.04%   |
| Nvidia GP106 High Definition Audio Controller                              | 2        | 2.04%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2        | 2.04%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2        | 2.04%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 2        | 2.04%   |
| AMD FCH Azalia Controller                                                  | 2        | 2.04%   |
| Tenx Technology USB AUDIO                                                  | 1        | 1.02%   |
| Razer USA RZ04-0318 Gaming Headset [Kraken Ultimate]                       | 1        | 1.02%   |
| Razer USA Razer Kraken X USB                                               | 1        | 1.02%   |
| Plantronics C320-M                                                         | 1        | 1.02%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1        | 1.02%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 1.02%   |
| Nvidia GP102 HDMI Audio Controller                                         | 1        | 1.02%   |
| Nvidia GM206 High Definition Audio Controller                              | 1        | 1.02%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 1.02%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 1.02%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1        | 1.02%   |
| Nvidia GF106 High Definition Audio Controller                              | 1        | 1.02%   |
| Nvidia GA102 High Definition Audio Controller                              | 1        | 1.02%   |
| Logitech G633 Gaming Headset                                               | 1        | 1.02%   |
| Kingston Technology HyperX Cloud Flight Wireless                           | 1        | 1.02%   |
| Kingston Technology HyperX 7.1 Audio                                       | 1        | 1.02%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1        | 1.02%   |
| Intel Comet Lake PCH cAVS                                                  | 1        | 1.02%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1        | 1.02%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 1        | 1.02%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1        | 1.02%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1        | 1.02%   |
| Hewlett-Packard E240C                                                      | 1        | 1.02%   |
| Generalplus Technology USB Audio Device                                    | 1        | 1.02%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 9        | 21.43%  |
| SK hynix            | 6        | 14.29%  |
| G.Skill             | 6        | 14.29%  |
| Unknown             | 4        | 9.52%   |
| Samsung Electronics | 4        | 9.52%   |
| Kingston            | 3        | 7.14%   |
| Crucial             | 3        | 7.14%   |
| Team                | 2        | 4.76%   |
| Unifosa             | 1        | 2.38%   |
| Ramaxel Technology  | 1        | 2.38%   |
| PNY                 | 1        | 2.38%   |
| Micron Technology   | 1        | 2.38%   |
| A-DATA Technology   | 1        | 2.38%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s  | 2        | 4.17%   |
| Kingston RAM KHX2133C14/16G 16GB DIMM DDR4 2176MT/s     | 2        | 4.17%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s   | 2        | 4.17%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s               | 1        | 2.08%   |
| Unknown RAM Module 4GB DIMM DDR4 2133MT/s               | 1        | 2.08%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                | 1        | 2.08%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                | 1        | 2.08%   |
| Unifosa RAM GU512303EP0202 2GB DIMM DDR3 1333MT/s       | 1        | 2.08%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s      | 1        | 2.08%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1600MT/s      | 1        | 2.08%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s    | 1        | 2.08%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 1        | 2.08%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s    | 1        | 2.08%   |
| SK hynix RAM HMT351U6BFR8C-H9 4096MB DIMM 1450MT/s      | 1        | 2.08%   |
| SK hynix RAM HMA81GU6MFR8N-UH 8GB DIMM DDR4 2400MT/s    | 1        | 2.08%   |
| SK hynix RAM HMA451R7MFR8N-TFTD 4GB DIMM DDR4 2133MT/s  | 1        | 2.08%   |
| SK hynix RAM HMA451R7MFR8N-TF 4GB DIMM DDR4 2133MT/s    | 1        | 2.08%   |
| Samsung RAM Module 8GB DIMM DDR4 2666MT/s               | 1        | 2.08%   |
| Samsung RAM Module 8GB DIMM DDR4 2133MT/s               | 1        | 2.08%   |
| Samsung RAM M393A5143DB0-CPB 4GB DIMM DDR4 2133MT/s     | 1        | 2.08%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s     | 1        | 2.08%   |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR3 1867MT/s     | 1        | 2.08%   |
| Ramaxel RAM RMUA5110MB78HAF-2400 8GB DIMM DDR4 2400MT/s | 1        | 2.08%   |
| PNY RAM 8GBF1X08QFHH36-135-K 8GB DIMM DDR4 2933MT/s     | 1        | 2.08%   |
| Micron RAM 16KTF1G64AZ-1G6E1 8GB DIMM DDR3 1600MT/s     | 1        | 2.08%   |
| Kingston RAM KHX3600C18D4/16GX 16GB DIMM DDR4 3600MT/s  | 1        | 2.08%   |
| Kingston RAM KHX3466C19D4/16G 16GB DIMM DDR4 3467MT/s   | 1        | 2.08%   |
| G.Skill RAM F4-3600C17-8GTZR 8GB DIMM DDR4 3600MT/s     | 1        | 2.08%   |
| G.Skill RAM F4-3600C16-8GTZNC 8GB DIMM DDR4 3800MT/s    | 1        | 2.08%   |
| G.Skill RAM F4-3600C16-16GTZRC 16GB DIMM DDR4 4400MT/s  | 1        | 2.08%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s  | 1        | 2.08%   |
| G.Skill RAM F4-3200C16-8GTZKW 8GB DIMM DDR4 3200MT/s    | 1        | 2.08%   |
| G.Skill RAM F4-3200C16-8GTZKO 8GB DIMM DDR4 3200MT/s    | 1        | 2.08%   |
| G.Skill RAM F4-2666C15-4GVR 4GB DIMM DDR4 2933MT/s      | 1        | 2.08%   |
| Crucial RAM CT4G4DFS824A.C8FHP 4GB DIMM DDR4 2400MT/s   | 1        | 2.08%   |
| Crucial RAM CT25664BD160B.C8FN 2GB DIMM DDR3 1333MT/s   | 1        | 2.08%   |
| Crucial RAM BL16G32C16U4R.M16FE 16GB DIMM DDR4 3200MT/s | 1        | 2.08%   |
| Corsair RAM CMW32GX4M2E3200C16 16GB DIMM DDR4 3200MT/s  | 1        | 2.08%   |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3200MT/s  | 1        | 2.08%   |
| Corsair RAM CMK8GX4M2A2666C16 4GB DIMM DDR4 2747MT/s    | 1        | 2.08%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Desktops | Percent |
|-------|----------|---------|
| DDR4  | 26       | 70.27%  |
| DDR3  | 8        | 21.62%  |
| SDRAM | 1        | 2.7%    |
| DDR2  | 1        | 2.7%    |
| DDR   | 1        | 2.7%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 34       | 94.44%  |
| SODIMM | 2        | 5.56%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 15       | 37.5%   |
| 16384 | 11       | 27.5%   |
| 4096  | 11       | 27.5%   |
| 2048  | 3        | 7.5%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 7        | 17.07%  |
| 1600  | 5        | 12.2%   |
| 3600  | 4        | 9.76%   |
| 2933  | 3        | 7.32%   |
| 2400  | 3        | 7.32%   |
| 3400  | 2        | 4.88%   |
| 2176  | 2        | 4.88%   |
| 2133  | 2        | 4.88%   |
| 1800  | 2        | 4.88%   |
| 1333  | 2        | 4.88%   |
| 4400  | 1        | 2.44%   |
| 4133  | 1        | 2.44%   |
| 3800  | 1        | 2.44%   |
| 3467  | 1        | 2.44%   |
| 2747  | 1        | 2.44%   |
| 2666  | 1        | 2.44%   |
| 1867  | 1        | 2.44%   |
| 1450  | 1        | 2.44%   |
| 800   | 1        | 2.44%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

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


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Generalplus Technology                 | 2        | 28.57%  |
| Chicony Electronics                    | 2        | 28.57%  |
| Microdia                               | 1        | 14.29%  |
| Logitech                               | 1        | 14.29%  |
| Cheng Uei Precision Industry (Foxlink) | 1        | 14.29%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Chicony HP High Definition 1MP Webcam                                | 2        | 28.57%  |
| Microdia Webcam Vitade AF                                            | 1        | 14.29%  |
| Logitech Webcam C600                                                 | 1        | 14.29%  |
| Generalplus GENERAL WEBCAM                                           | 1        | 14.29%  |
| Generalplus campark PC04                                             | 1        | 14.29%  |
| Cheng Uei Precision Industry (Foxlink) HP High Definition 1MP Webcam | 1        | 14.29%  |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Elan Microelectronics | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Elan fingerprint sensor [FeinTech FPS00200] | 1        | 100%    |

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
| 0     | 36       | 81.82%  |
| 1     | 8        | 18.18%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Desktops | Percent |
|--------------------|----------|---------|
| Net/wireless       | 2        | 25%     |
| Graphics card      | 2        | 25%     |
| Bluetooth          | 2        | 25%     |
| Unassigned class   | 1        | 12.5%   |
| Fingerprint reader | 1        | 12.5%   |

