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

Total: 66

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek  | PRIME B450M-A II            | [95bc101c80](https://linux-hardware.org/?probe=95bc101c80) | Jun 09, 2023 |
| Dell     | 00V62H A01                  | [89d6a4edd2](https://linux-hardware.org/?probe=89d6a4edd2) | May 13, 2023 |
| Unknown  | Intel X79                   | [6b1ddbd923](https://linux-hardware.org/?probe=6b1ddbd923) | May 03, 2023 |
| Biostar  | H110MHV3                    | [95b25ba480](https://linux-hardware.org/?probe=95b25ba480) | Apr 29, 2023 |
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
| Xero Rolling | 43       | 89.58%  |
| Xero         | 5        | 10.42%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| Xero | 48       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Desktops | Percent |
|-------------------------|----------|---------|
| 6.1.12-arch1-1          | 4        | 7.41%   |
| 6.2.12-arch1-1          | 2        | 3.7%    |
| 5.18.16-arch1-1         | 2        | 3.7%    |
| 5.16.15-arch1-1         | 2        | 3.7%    |
| 5.16.12-arch1-1         | 2        | 3.7%    |
| 6.3.6-arch1-1           | 1        | 1.85%   |
| 6.2.8-arch1-1           | 1        | 1.85%   |
| 6.2.6-arch1-1           | 1        | 1.85%   |
| 6.2.13-arch1-1          | 1        | 1.85%   |
| 6.2.1-x64v1-xanmod1-1   | 1        | 1.85%   |
| 6.1.6-arch1-3           | 1        | 1.85%   |
| 6.0.6-zen1-1-zen        | 1        | 1.85%   |
| 6.0.2-zen1-1-zen        | 1        | 1.85%   |
| 6.0.1-arch2-1           | 1        | 1.85%   |
| 5.19.9-arch1-1          | 1        | 1.85%   |
| 5.19.2-zen1-1-zen       | 1        | 1.85%   |
| 5.19.13-zen1-1-zen      | 1        | 1.85%   |
| 5.19.13-arch1-1         | 1        | 1.85%   |
| 5.19.10-arch1-1         | 1        | 1.85%   |
| 5.18.9-arch1-1          | 1        | 1.85%   |
| 5.18.6-arch1-1          | 1        | 1.85%   |
| 5.18.3-arch1-1          | 1        | 1.85%   |
| 5.18.0-arch1-1          | 1        | 1.85%   |
| 5.17.5-arch1-1          | 1        | 1.85%   |
| 5.17.1-arch1-1          | 1        | 1.85%   |
| 5.16.16-zen1-1-zen      | 1        | 1.85%   |
| 5.16.16-arch1-1         | 1        | 1.85%   |
| 5.16.13-arch1-1         | 1        | 1.85%   |
| 5.16.1-arch1-1          | 1        | 1.85%   |
| 5.15.4-arch1-1          | 1        | 1.85%   |
| 5.15.33-1-lts           | 1        | 1.85%   |
| 5.15.3-zen1-1-zen       | 1        | 1.85%   |
| 5.15.24-1-lts           | 1        | 1.85%   |
| 5.15.13-AMD             | 1        | 1.85%   |
| 5.15.12-zen1-1-zen      | 1        | 1.85%   |
| 5.15.12-arch1-1-surface | 1        | 1.85%   |
| 5.15.12-arch1-1         | 1        | 1.85%   |
| 5.15.11-arch2-1-surface | 1        | 1.85%   |
| 5.15.10-arch1-1         | 1        | 1.85%   |
| 5.14.9-zen2-1-zen       | 1        | 1.85%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.1.12  | 4        | 7.41%   |
| 5.15.12 | 3        | 5.56%   |
| 6.2.12  | 2        | 3.7%    |
| 5.19.13 | 2        | 3.7%    |
| 5.18.16 | 2        | 3.7%    |
| 5.16.16 | 2        | 3.7%    |
| 5.16.15 | 2        | 3.7%    |
| 5.16.12 | 2        | 3.7%    |
| 6.3.6   | 1        | 1.85%   |
| 6.2.8   | 1        | 1.85%   |
| 6.2.6   | 1        | 1.85%   |
| 6.2.13  | 1        | 1.85%   |
| 6.2.1   | 1        | 1.85%   |
| 6.1.6   | 1        | 1.85%   |
| 6.0.6   | 1        | 1.85%   |
| 6.0.2   | 1        | 1.85%   |
| 6.0.1   | 1        | 1.85%   |
| 5.19.9  | 1        | 1.85%   |
| 5.19.2  | 1        | 1.85%   |
| 5.19.10 | 1        | 1.85%   |
| 5.18.9  | 1        | 1.85%   |
| 5.18.6  | 1        | 1.85%   |
| 5.18.3  | 1        | 1.85%   |
| 5.18.0  | 1        | 1.85%   |
| 5.17.5  | 1        | 1.85%   |
| 5.17.1  | 1        | 1.85%   |
| 5.16.13 | 1        | 1.85%   |
| 5.16.1  | 1        | 1.85%   |
| 5.15.4  | 1        | 1.85%   |
| 5.15.33 | 1        | 1.85%   |
| 5.15.3  | 1        | 1.85%   |
| 5.15.24 | 1        | 1.85%   |
| 5.15.13 | 1        | 1.85%   |
| 5.15.11 | 1        | 1.85%   |
| 5.15.10 | 1        | 1.85%   |
| 5.14.9  | 1        | 1.85%   |
| 5.14.8  | 1        | 1.85%   |
| 5.14.15 | 1        | 1.85%   |
| 5.14.14 | 1        | 1.85%   |
| 5.13.4  | 1        | 1.85%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 9        | 16.98%  |
| 5.16    | 8        | 15.09%  |
| 6.2     | 6        | 11.32%  |
| 5.18    | 6        | 11.32%  |
| 6.1     | 5        | 9.43%   |
| 5.19    | 5        | 9.43%   |
| 5.14    | 4        | 7.55%   |
| 6.0     | 3        | 5.66%   |
| 5.17    | 2        | 3.77%   |
| 5.13    | 2        | 3.77%   |
| 6.3     | 1        | 1.89%   |
| 5.12    | 1        | 1.89%   |
| 5.11    | 1        | 1.89%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 48       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| KDE5  | 46       | 93.88%  |
| XFCE  | 2        | 4.08%   |
| GNOME | 1        | 2.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 44       | 91.67%  |
| Wayland | 2        | 4.17%   |
| Tty     | 2        | 4.17%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 32       | 65.31%  |
| Unknown | 11       | 22.45%  |
| LightDM | 4        | 8.16%   |
| TDM     | 1        | 2.04%   |
| GDM     | 1        | 2.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 25       | 52.08%  |
| en_GB | 5        | 10.42%  |
| de_DE | 4        | 8.33%   |
| C     | 2        | 4.17%   |
| tr_TR | 1        | 2.08%   |
| sv_SE | 1        | 2.08%   |
| ru_RU | 1        | 2.08%   |
| pl_PL | 1        | 2.08%   |
| hu_HU | 1        | 2.08%   |
| es_MX | 1        | 2.08%   |
| en_ZA | 1        | 2.08%   |
| en_IN | 1        | 2.08%   |
| en_CA | 1        | 2.08%   |
| en_AU | 1        | 2.08%   |
| de_AT | 1        | 2.08%   |
| ba_RU | 1        | 2.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 26       | 54.17%  |
| BIOS | 22       | 45.83%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Btrfs   | 25       | 51.02%  |
| Ext4    | 11       | 22.45%  |
| Xfs     | 10       | 20.41%  |
| Overlay | 3        | 6.12%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 31       | 64.58%  |
| Unknown | 11       | 22.92%  |
| MBR     | 6        | 12.5%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 33       | 66%     |
| Yes       | 17       | 34%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 30       | 62.5%   |
| Yes       | 18       | 37.5%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 18       | 37.5%   |
| Hewlett-Packard     | 6        | 12.5%   |
| MSI                 | 4        | 8.33%   |
| Gigabyte Technology | 4        | 8.33%   |
| Dell                | 4        | 8.33%   |
| ASRock              | 3        | 6.25%   |
| Acer                | 3        | 6.25%   |
| Pegatron            | 2        | 4.17%   |
| Unknown             | 2        | 4.17%   |
| JINGSHA             | 1        | 2.08%   |
| Biostar             | 1        | 2.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| Unknown                           | 3        | 6.25%   |
| MSI MS-7971                       | 2        | 4.17%   |
| ASUS TUF Gaming X570-PLUS         | 2        | 4.17%   |
| Pegatron p6-2026                  | 1        | 2.08%   |
| Pegatron 20-b010                  | 1        | 2.08%   |
| MSI MS-7C91                       | 1        | 2.08%   |
| MSI MS-7B61                       | 1        | 2.08%   |
| HP Z230 SFF Workstation           | 1        | 2.08%   |
| HP ProOne 400 G1 AiO              | 1        | 2.08%   |
| HP Pavilion Power Desktop 580-1xx | 1        | 2.08%   |
| HP Pavilion Desktop 590-p0xxx     | 1        | 2.08%   |
| HP Compaq Elite 8300 CMT          | 1        | 2.08%   |
| HP 750-424                        | 1        | 2.08%   |
| Gigabyte Z170X-UD3                | 1        | 2.08%   |
| Gigabyte X570 AORUS MASTER        | 1        | 2.08%   |
| Gigabyte B460MDS3HV2              | 1        | 2.08%   |
| Gigabyte A320M-S2H                | 1        | 2.08%   |
| Dell Studio XPS 8100              | 1        | 2.08%   |
| Dell Precision T1500              | 1        | 2.08%   |
| Dell OptiPlex 9020                | 1        | 2.08%   |
| Dell OptiPlex 7010                | 1        | 2.08%   |
| Biostar H110MHV3                  | 1        | 2.08%   |
| ASUS TUF Z390-PLUS GAMING         | 1        | 2.08%   |
| ASUS TUF Gaming B550M-PLUS        | 1        | 2.08%   |
| ASUS TUF B360M-PLUS GAMING/BR     | 1        | 2.08%   |
| ASUS ROG STRIX Z370-F GAMING      | 1        | 2.08%   |
| ASUS ROG STRIX X570-F GAMING      | 1        | 2.08%   |
| ASUS ROG STRIX B450-F GAMING      | 1        | 2.08%   |
| ASUS ROG Maximus X HERO           | 1        | 2.08%   |
| ASUS ROG CROSSHAIR VIII HERO      | 1        | 2.08%   |
| ASUS ROG CROSSHAIR VIII DARK HERO | 1        | 2.08%   |
| ASUS PRIME B450M-A II             | 1        | 2.08%   |
| ASUS PRIME B250-PLUS              | 1        | 2.08%   |
| ASUS PRIME A320M-K                | 1        | 2.08%   |
| ASUS P7P55 LX                     | 1        | 2.08%   |
| ASUS P5Q PRO TURBO                | 1        | 2.08%   |
| ASUS Maximus IX HERO              | 1        | 2.08%   |
| ASUS A68HM-PLUS                   | 1        | 2.08%   |
| ASRock X570 Taichi                | 1        | 2.08%   |
| ASRock B450M Pro4                 | 1        | 2.08%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| ASUS ROG             | 6        | 12.5%   |
| ASUS TUF             | 5        | 10.42%  |
| ASUS PRIME           | 3        | 6.25%   |
| Acer Aspire          | 3        | 6.25%   |
| Unknown              | 3        | 6.25%   |
| MSI MS-7971          | 2        | 4.17%   |
| HP Pavilion          | 2        | 4.17%   |
| Dell OptiPlex        | 2        | 4.17%   |
| Pegatron p6-2026     | 1        | 2.08%   |
| Pegatron 20-b010     | 1        | 2.08%   |
| MSI MS-7C91          | 1        | 2.08%   |
| MSI MS-7B61          | 1        | 2.08%   |
| HP Z230              | 1        | 2.08%   |
| HP ProOne            | 1        | 2.08%   |
| HP Compaq            | 1        | 2.08%   |
| HP 750-424           | 1        | 2.08%   |
| Gigabyte Z170X-UD3   | 1        | 2.08%   |
| Gigabyte X570        | 1        | 2.08%   |
| Gigabyte B460MDS3HV2 | 1        | 2.08%   |
| Gigabyte A320M-S2H   | 1        | 2.08%   |
| Dell Studio          | 1        | 2.08%   |
| Dell Precision       | 1        | 2.08%   |
| Biostar H110MHV3     | 1        | 2.08%   |
| ASUS P7P55           | 1        | 2.08%   |
| ASUS P5Q             | 1        | 2.08%   |
| ASUS Maximus         | 1        | 2.08%   |
| ASUS A68HM-PLUS      | 1        | 2.08%   |
| ASRock X570          | 1        | 2.08%   |
| ASRock B450M         | 1        | 2.08%   |
| ASRock AB350         | 1        | 2.08%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 9        | 18.75%  |
| 2018 | 7        | 14.58%  |
| 2020 | 6        | 12.5%   |
| 2017 | 6        | 12.5%   |
| 2015 | 4        | 8.33%   |
| 2014 | 3        | 6.25%   |
| 2010 | 3        | 6.25%   |
| 2013 | 2        | 4.17%   |
| 2012 | 2        | 4.17%   |
| 2009 | 2        | 4.17%   |
| 2022 | 1        | 2.08%   |
| 2021 | 1        | 2.08%   |
| 2016 | 1        | 2.08%   |
| 2011 | 1        | 2.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 48       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 48       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 48       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 18       | 37.5%   |
| 32.01-64.0  | 12       | 25%     |
| 8.01-16.0   | 9        | 18.75%  |
| 4.01-8.0    | 6        | 12.5%   |
| 3.01-4.0    | 1        | 2.08%   |
| 24.01-32.0  | 1        | 2.08%   |
| 64.01-256.0 | 1        | 2.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 14       | 25.93%  |
| 2.01-3.0   | 13       | 24.07%  |
| 1.01-2.0   | 8        | 14.81%  |
| 3.01-4.0   | 7        | 12.96%  |
| 8.01-16.0  | 6        | 11.11%  |
| 16.01-24.0 | 3        | 5.56%   |
| 0.01-0.5   | 2        | 3.7%    |
| 0.51-1.0   | 1        | 1.85%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 14       | 29.17%  |
| 3      | 12       | 25%     |
| 2      | 9        | 18.75%  |
| 4      | 6        | 12.5%   |
| 5      | 4        | 8.33%   |
| 6      | 2        | 4.17%   |
| 7      | 1        | 2.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 34       | 70.83%  |
| Yes       | 14       | 29.17%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 48       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 26       | 54.17%  |
| No        | 22       | 45.83%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 25       | 51.02%  |
| Yes       | 24       | 48.98%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country        | Desktops | Percent |
|----------------|----------|---------|
| USA            | 12       | 25%     |
| Germany        | 4        | 8.33%   |
| UK             | 3        | 6.25%   |
| Spain          | 2        | 4.17%   |
| Russia         | 2        | 4.17%   |
| Poland         | 2        | 4.17%   |
| Mexico         | 2        | 4.17%   |
| Canada         | 2        | 4.17%   |
| Turkey         | 1        | 2.08%   |
| Sweden         | 1        | 2.08%   |
| South Africa   | 1        | 2.08%   |
| Portugal       | 1        | 2.08%   |
| Netherlands    | 1        | 2.08%   |
| Lebanon        | 1        | 2.08%   |
| Italy          | 1        | 2.08%   |
| India          | 1        | 2.08%   |
| Hungary        | 1        | 2.08%   |
| Greece         | 1        | 2.08%   |
| Czechia        | 1        | 2.08%   |
| Cyprus         | 1        | 2.08%   |
| Colombia       | 1        | 2.08%   |
| Brazil         | 1        | 2.08%   |
| Bahrain        | 1        | 2.08%   |
| Austria        | 1        | 2.08%   |
| Australia      | 1        | 2.08%   |
| Argentina      | 1        | 2.08%   |
| Åland Islands | 1        | 2.08%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Zell am See           | 1        | 2.08%   |
| Wroclaw               | 1        | 2.08%   |
| Wrexham               | 1        | 2.08%   |
| Wells                 | 1        | 2.08%   |
| Warsaw                | 1        | 2.08%   |
| Vredenburg            | 1        | 2.08%   |
| Stow                  | 1        | 2.08%   |
| Springfield           | 1        | 2.08%   |
| Sonora                | 1        | 2.08%   |
| Shadrinsk             | 1        | 2.08%   |
| Sant Boi de Llobregat | 1        | 2.08%   |
| Salt Lake City        | 1        | 2.08%   |
| Portland              | 1        | 2.08%   |
| Phoenix               | 1        | 2.08%   |
| Passos                | 1        | 2.08%   |
| Oberursel             | 1        | 2.08%   |
| Nicosia               | 1        | 2.08%   |
| New Haven             | 1        | 2.08%   |
| Nagykanizsa           | 1        | 2.08%   |
| Moscow                | 1        | 2.08%   |
| Monterrey             | 1        | 2.08%   |
| Milton Keynes         | 1        | 2.08%   |
| Mexico City           | 1        | 2.08%   |
| Mariehamn             | 1        | 2.08%   |
| Margate               | 1        | 2.08%   |
| Manama                | 1        | 2.08%   |
| Longview              | 1        | 2.08%   |
| Lisbon                | 1        | 2.08%   |
| Laval                 | 1        | 2.08%   |
| Krizanov              | 1        | 2.08%   |
| Kista                 | 1        | 2.08%   |
| Hamburg               | 1        | 2.08%   |
| Ernakulam             | 1        | 2.08%   |
| Chicago               | 1        | 2.08%   |
| Canovelles            | 1        | 2.08%   |
| Candiac               | 1        | 2.08%   |
| Buenos Aires          | 1        | 2.08%   |
| Bristol               | 1        | 2.08%   |
| Brisbane              | 1        | 2.08%   |
| Brindisi              | 1        | 2.08%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 20       | 29     | 17.7%   |
| Seagate                   | 19       | 30     | 16.81%  |
| Samsung Electronics       | 18       | 29     | 15.93%  |
| Kingston                  | 8        | 11     | 7.08%   |
| Toshiba                   | 7        | 9      | 6.19%   |
| SanDisk                   | 6        | 8      | 5.31%   |
| Unknown                   | 5        | 6      | 4.42%   |
| Crucial                   | 4        | 6      | 3.54%   |
| China                     | 3        | 3      | 2.65%   |
| Phison                    | 2        | 2      | 1.77%   |
| Intel                     | 2        | 3      | 1.77%   |
| Hitachi                   | 2        | 2      | 1.77%   |
| HGST                      | 2        | 2      | 1.77%   |
| A-DATA Technology         | 2        | 2      | 1.77%   |
| XPG                       | 1        | 1      | 0.88%   |
| Transcend                 | 1        | 1      | 0.88%   |
| SPCC                      | 1        | 1      | 0.88%   |
| SK hynix                  | 1        | 1      | 0.88%   |
| Silicon Motion            | 1        | 1      | 0.88%   |
| Realtek Semiconductor     | 1        | 1      | 0.88%   |
| PNY                       | 1        | 1      | 0.88%   |
| Micron/Crucial Technology | 1        | 1      | 0.88%   |
| Micron Technology         | 1        | 2      | 0.88%   |
| Leven                     | 1        | 1      | 0.88%   |
| KIOXIA                    | 1        | 1      | 0.88%   |
| Intenso                   | 1        | 1      | 0.88%   |
| 2-Power                   | 1        | 1      | 0.88%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Unknown SD/MMC/MS PRO 64GB       | 3        | 2.21%   |
| Kingston SA400S37240G 240GB SSD  | 3        | 2.21%   |
| Crucial CT500MX500SSD1 500GB     | 3        | 2.21%   |
| WDC WD10EZEX-60WN4A0 1TB         | 2        | 1.47%   |
| Toshiba DT01ACA300 3TB           | 2        | 1.47%   |
| Seagate ST2000DM006-2DM164 2TB   | 2        | 1.47%   |
| Seagate ST1000DM010-2EP102 1TB   | 2        | 1.47%   |
| Seagate ST1000DM003-1SB102 1TB   | 2        | 1.47%   |
| SanDisk NVMe SSD Drive 500GB     | 2        | 1.47%   |
| Samsung SSD 970 EVO 1TB          | 2        | 1.47%   |
| XPG GAMMIX S50 1TB               | 1        | 0.74%   |
| WDC WDS512G1X0C-00ENX0 512GB     | 1        | 0.74%   |
| WDC WDS500G3XHC-00SJG0 500GB     | 1        | 0.74%   |
| WDC WDS500G3X0C-00SJG0 500GB     | 1        | 0.74%   |
| WDC WDS500G2B0B-00YS70 500GB SSD | 1        | 0.74%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 1        | 0.74%   |
| WDC WDS120G2G0A-00JH30 120GB SSD | 1        | 0.74%   |
| WDC WD800JD-00MSA1 80GB          | 1        | 0.74%   |
| WDC WD7500BPKT-75PK4T0 752GB     | 1        | 0.74%   |
| WDC WD6400AAKS-22A7B2 640GB      | 1        | 0.74%   |
| WDC WD5000AAVS-00ZTB0 500GB      | 1        | 0.74%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 1        | 0.74%   |
| WDC WD40EZRZ-22GXCB0 4TB         | 1        | 0.74%   |
| WDC WD2500BEVT-60ZCT1 250GB      | 1        | 0.74%   |
| WDC WD20EZRZ-60Z5HB0 2TB         | 1        | 0.74%   |
| WDC WD20EZBX-00AYRA0 2TB         | 1        | 0.74%   |
| WDC WD2003FZEX-00SRLA0 2TB       | 1        | 0.74%   |
| WDC WD15EADS-11R6B1 1TB          | 1        | 0.74%   |
| WDC WD10EZEX-22MFCA0 1TB         | 1        | 0.74%   |
| WDC WD10EZEX-21WN4A0 1TB         | 1        | 0.74%   |
| WDC WD10EZEX-08WN4A0 1TB         | 1        | 0.74%   |
| WDC WD10EZEX-00KUWA0 1TB         | 1        | 0.74%   |
| WDC WD10EAVS-00D7B1 1TB          | 1        | 0.74%   |
| WDC WD10EADS-00M2B0 1TB          | 1        | 0.74%   |
| WDC WD1002FAEX-00Z3A0 1TB        | 1        | 0.74%   |
| Unknown MMC Card  64GB           | 1        | 0.74%   |
| Unknown MMC Card  4GB            | 1        | 0.74%   |
| Unknown MMC Card  128GB          | 1        | 0.74%   |
| Transcend TS120GSSD220S 120GB    | 1        | 0.74%   |
| Toshiba MQ04ABF100 1TB           | 1        | 0.74%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 19       | 30     | 35.19%  |
| WDC                 | 17       | 23     | 31.48%  |
| Toshiba             | 7        | 9      | 12.96%  |
| Unknown             | 3        | 3      | 5.56%   |
| Samsung Electronics | 3        | 3      | 5.56%   |
| Hitachi             | 2        | 2      | 3.7%    |
| HGST                | 2        | 2      | 3.7%    |
| Intenso             | 1        | 1      | 1.85%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 9        | 12     | 25%     |
| Kingston            | 8        | 11     | 22.22%  |
| Crucial             | 4        | 6      | 11.11%  |
| WDC                 | 3        | 3      | 8.33%   |
| China               | 3        | 3      | 8.33%   |
| SanDisk             | 2        | 2      | 5.56%   |
| Transcend           | 1        | 1      | 2.78%   |
| SPCC                | 1        | 1      | 2.78%   |
| PNY                 | 1        | 1      | 2.78%   |
| Micron Technology   | 1        | 1      | 2.78%   |
| Leven               | 1        | 1      | 2.78%   |
| A-DATA Technology   | 1        | 1      | 2.78%   |
| 2-Power             | 1        | 1      | 2.78%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 38       | 73     | 41.3%   |
| SSD  | 29       | 44     | 31.52%  |
| NVMe | 23       | 36     | 25%     |
| MMC  | 2        | 3      | 2.17%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 44       | 109    | 57.89%  |
| NVMe | 23       | 36     | 30.26%  |
| SAS  | 7        | 8      | 9.21%   |
| MMC  | 2        | 3      | 2.63%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 34       | 56     | 44.16%  |
| 0.51-1.0   | 26       | 37     | 33.77%  |
| 1.01-2.0   | 9        | 13     | 11.69%  |
| 4.01-10.0  | 5        | 8      | 6.49%   |
| 2.01-3.0   | 2        | 2      | 2.6%    |
| 3.01-4.0   | 1        | 1      | 1.3%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 17       | 33.33%  |
| 1001-2000      | 10       | 19.61%  |
| 501-1000       | 6        | 11.76%  |
| 251-500        | 5        | 9.8%    |
| 101-250        | 5        | 9.8%    |
| 21-50          | 2        | 3.92%   |
| 1-20           | 2        | 3.92%   |
| 51-100         | 2        | 3.92%   |
| 2001-3000      | 1        | 1.96%   |
| Unknown        | 1        | 1.96%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 13       | 25.49%  |
| 1-20           | 11       | 21.57%  |
| 51-100         | 6        | 11.76%  |
| 501-1000       | 5        | 9.8%    |
| 251-500        | 4        | 7.84%   |
| More than 3000 | 3        | 5.88%   |
| 21-50          | 3        | 5.88%   |
| 1001-2000      | 3        | 5.88%   |
| 2001-3000      | 2        | 3.92%   |
| Unknown        | 1        | 1.96%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| WDC WD5000AAKX-60U6AA0 500GB     | 1        | 1      | 6.25%   |
| WDC WD10EZEX-08WN4A0 1TB         | 1        | 1      | 6.25%   |
| WDC WD10EADS-00M2B0 1TB          | 1        | 1      | 6.25%   |
| WDC WD1002FAEX-00Z3A0 1TB        | 1        | 2      | 6.25%   |
| Toshiba MQ01ABD100 1TB           | 1        | 1      | 6.25%   |
| Toshiba MK4058GSX 400GB          | 1        | 1      | 6.25%   |
| Seagate ST9500420AS 500GB        | 1        | 1      | 6.25%   |
| Seagate ST500DM009-2F110A 500GB  | 1        | 1      | 6.25%   |
| Seagate ST31000524AS 1TB         | 1        | 1      | 6.25%   |
| Seagate ST2000VX000-1CU164 2TB   | 1        | 1      | 6.25%   |
| Seagate ST2000DM006-2DM164 2TB   | 1        | 1      | 6.25%   |
| Kingston SV300S37A120G 120GB SSD | 1        | 1      | 6.25%   |
| Kingston SUV400S37240G 240GB SSD | 1        | 1      | 6.25%   |
| Hitachi HTS725050A9A364 500GB    | 1        | 1      | 6.25%   |
| Hitachi HCP725050GLA380 500GB    | 1        | 1      | 6.25%   |
| China SATA3 240GB SSD            | 1        | 1      | 6.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Seagate  | 5        | 5      | 33.33%  |
| WDC      | 4        | 5      | 26.67%  |
| Kingston | 2        | 2      | 13.33%  |
| Hitachi  | 2        | 2      | 13.33%  |
| Toshiba  | 1        | 2      | 6.67%   |
| China    | 1        | 1      | 6.67%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 5        | 5      | 41.67%  |
| WDC     | 4        | 5      | 33.33%  |
| Hitachi | 2        | 2      | 16.67%  |
| Toshiba | 1        | 2      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 11       | 14     | 78.57%  |
| SSD  | 3        | 3      | 21.43%  |

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
| Works    | 36       | 93     | 55.38%  |
| Detected | 16       | 46     | 24.62%  |
| Malfunc  | 13       | 17     | 20%     |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 32       | 42.67%  |
| AMD                       | 18       | 24%     |
| SanDisk                   | 7        | 9.33%   |
| Samsung Electronics       | 7        | 9.33%   |
| Realtek Semiconductor     | 2        | 2.67%   |
| Phison Electronics        | 2        | 2.67%   |
| SK hynix                  | 1        | 1.33%   |
| Silicon Motion            | 1        | 1.33%   |
| Micron/Crucial Technology | 1        | 1.33%   |
| Micron Technology         | 1        | 1.33%   |
| KIOXIA                    | 1        | 1.33%   |
| ASMedia Technology        | 1        | 1.33%   |
| ADATA Technology          | 1        | 1.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 15       | 17.65%  |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 7        | 8.24%   |
| Intel SATA Controller [RAID mode]                                              | 5        | 5.88%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 5        | 5.88%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4        | 4.71%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3        | 3.53%   |
| AMD 400 Series Chipset SATA Controller                                         | 3        | 3.53%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 2        | 2.35%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2        | 2.35%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2        | 2.35%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2        | 2.35%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2        | 2.35%   |
| AMD FCH SATA Controller D                                                      | 2        | 2.35%   |
| AMD 500 Series Chipset SATA Controller                                         | 2        | 2.35%   |
| AMD 300 Series Chipset SATA Controller                                         | 2        | 2.35%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1        | 1.18%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 1        | 1.18%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                             | 1        | 1.18%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1        | 1.18%   |
| SanDisk WD Black SN770 NVMe SSD                                                | 1        | 1.18%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1        | 1.18%   |
| SanDisk WD Black NVMe SSD                                                      | 1        | 1.18%   |
| Samsung NVMe SSD Controller 980                                                | 1        | 1.18%   |
| Realtek RTS5763DL NVMe SSD Controller                                          | 1        | 1.18%   |
| Realtek NVMe Controller                                                        | 1        | 1.18%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1        | 1.18%   |
| Phison E12 NVMe Controller                                                     | 1        | 1.18%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                | 1        | 1.18%   |
| Micron NVMe Storage Controller                                                 | 1        | 1.18%   |
| KIOXIA NVMe SSD                                                                | 1        | 1.18%   |
| Intel SSD 660P Series                                                          | 1        | 1.18%   |
| Intel SSD 600P Series                                                          | 1        | 1.18%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1        | 1.18%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 1        | 1.18%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 1        | 1.18%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 1        | 1.18%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1        | 1.18%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 1        | 1.18%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 1        | 1.18%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 1        | 1.18%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 43       | 59.72%  |
| NVMe | 23       | 31.94%  |
| RAID | 5        | 6.94%   |
| IDE  | 1        | 1.39%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 30       | 62.5%   |
| AMD    | 18       | 37.5%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| AMD Ryzen 5 3600X 6-Core Processor            | 3        | 6.12%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 2        | 4.08%   |
| Intel Core i7 CPU 870 @ 2.93GHz               | 2        | 4.08%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 2        | 4.08%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 2        | 4.08%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 2        | 4.08%   |
| AMD Ryzen 5 3600 6-Core Processor             | 2        | 4.08%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 2        | 4.08%   |
| Intel Xeon CPU E5-2689 0 @ 2.60GHz            | 1        | 2.04%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz           | 1        | 2.04%   |
| Intel Genuine CPU 0000 @ 2.10GHz              | 1        | 2.04%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 1        | 2.04%   |
| Intel Core i7-7700K CPU @ 4.20GHz             | 1        | 2.04%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 1        | 2.04%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 1        | 2.04%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 1        | 2.04%   |
| Intel Core i7 CPU 860 @ 2.80GHz               | 1        | 2.04%   |
| Intel Core i5-9600K CPU @ 3.70GHz             | 1        | 2.04%   |
| Intel Core i5-9400F CPU @ 2.90GHz             | 1        | 2.04%   |
| Intel Core i5-9400 CPU @ 2.90GHz              | 1        | 2.04%   |
| Intel Core i5-6600 CPU @ 3.30GHz              | 1        | 2.04%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 1        | 2.04%   |
| Intel Core i5-6400 CPU @ 2.70GHz              | 1        | 2.04%   |
| Intel Core i5-4670 CPU @ 3.40GHz              | 1        | 2.04%   |
| Intel Core i5-4590T CPU @ 2.00GHz             | 1        | 2.04%   |
| Intel Core i5-10400F CPU @ 2.90GHz            | 1        | 2.04%   |
| Intel Core i3-8100 CPU @ 3.60GHz              | 1        | 2.04%   |
| Intel Core i3-6100 CPU @ 3.70GHz              | 1        | 2.04%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 1        | 2.04%   |
| Intel Core i3 CPU 540 @ 3.07GHz               | 1        | 2.04%   |
| Intel Core 2 Quad CPU Q9650 @ 3.00GHz         | 1        | 2.04%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 1        | 2.04%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 1        | 2.04%   |
| AMD Ryzen 7 5800X3D 8-Core Processor          | 1        | 2.04%   |
| AMD Ryzen 7 3800X 8-Core Processor            | 1        | 2.04%   |
| AMD Ryzen 7 2700 Eight-Core Processor         | 1        | 2.04%   |
| AMD E1-1200 APU with Radeon HD Graphics       | 1        | 2.04%   |
| AMD Athlon 200GE with Radeon Vega Graphics    | 1        | 2.04%   |
| AMD A8-9600 RADEON R7, 10 COMPUTE CORES 4C+6G | 1        | 2.04%   |
| AMD A8-6600K APU with Radeon HD Graphics      | 1        | 2.04%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| Intel Core i5     | 11       | 22.45%  |
| Intel Core i7     | 10       | 20.41%  |
| AMD Ryzen 5       | 9        | 18.37%  |
| AMD Ryzen 7       | 5        | 10.2%   |
| Intel Core i3     | 4        | 8.16%   |
| Intel Xeon        | 2        | 4.08%   |
| AMD A8            | 2        | 4.08%   |
| Intel Genuine     | 1        | 2.04%   |
| Intel Core 2 Quad | 1        | 2.04%   |
| Intel Celeron     | 1        | 2.04%   |
| AMD Ryzen 9       | 1        | 2.04%   |
| AMD E1            | 1        | 2.04%   |
| AMD Athlon        | 1        | 2.04%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 17       | 34.69%  |
| 6      | 16       | 32.65%  |
| 8      | 7        | 14.29%  |
| 2      | 7        | 14.29%  |
| 16     | 1        | 2.04%   |
| 12     | 1        | 2.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 47       | 97.92%  |
| 2      | 1        | 2.08%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 33       | 68.75%  |
| 1      | 15       | 31.25%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 48       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 13       | 26.53%  |
| 0x506e3    | 5        | 10.2%   |
| 0x08701021 | 5        | 10.2%   |
| 0x906ea    | 4        | 8.16%   |
| 0x0a201016 | 3        | 6.12%   |
| 0x306c3    | 2        | 4.08%   |
| 0x306a9    | 2        | 4.08%   |
| 0x106e5    | 2        | 4.08%   |
| 0x0a20120a | 2        | 4.08%   |
| 0xa0653    | 1        | 2.04%   |
| 0x906ed    | 1        | 2.04%   |
| 0x906eb    | 1        | 2.04%   |
| 0x906e9    | 1        | 2.04%   |
| 0x306f2    | 1        | 2.04%   |
| 0x20655    | 1        | 2.04%   |
| 0x1067a    | 1        | 2.04%   |
| 0x08701013 | 1        | 2.04%   |
| 0x0810100b | 1        | 2.04%   |
| 0x0600611a | 1        | 2.04%   |
| 0x0500010d | 1        | 2.04%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| KabyLake      | 9        | 18.37%  |
| Zen 2         | 7        | 14.29%  |
| Skylake       | 6        | 12.24%  |
| Zen 3         | 5        | 10.2%   |
| Haswell       | 4        | 8.16%   |
| Nehalem       | 3        | 6.12%   |
| Zen+          | 2        | 4.08%   |
| Zen           | 2        | 4.08%   |
| SandyBridge   | 2        | 4.08%   |
| IvyBridge     | 2        | 4.08%   |
| Westmere      | 1        | 2.04%   |
| Piledriver    | 1        | 2.04%   |
| Penryn        | 1        | 2.04%   |
| Goldmont plus | 1        | 2.04%   |
| Excavator     | 1        | 2.04%   |
| CometLake     | 1        | 2.04%   |
| Bobcat        | 1        | 2.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 25       | 50%     |
| AMD               | 15       | 30%     |
| Intel             | 9        | 18%     |
| ASPEED Technology | 1        | 2%      |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia GP104 [GeForce GTX 1080]                                             | 3        | 5.88%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 3        | 5.88%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 2        | 3.92%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2        | 3.92%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 3.92%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2        | 3.92%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 3.92%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 3.92%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 2        | 3.92%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 1.96%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 1.96%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 1.96%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 1.96%   |
| Nvidia GT200 [GeForce GTX 260]                                              | 1        | 1.96%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 1.96%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 1.96%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 1.96%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 1.96%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 1.96%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 1.96%   |
| Nvidia GK107 [GeForce GT 740]                                               | 1        | 1.96%   |
| Nvidia GF106GL [Quadro 2000]                                                | 1        | 1.96%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 1        | 1.96%   |
| Nvidia GA102 [GeForce RTX 3080 Lite Hash Rate]                              | 1        | 1.96%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 1.96%   |
| Intel HD Graphics 530                                                       | 1        | 1.96%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1        | 1.96%   |
| Intel Core Processor Integrated Graphics Controller                         | 1        | 1.96%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 1        | 1.96%   |
| ASPEED Technology ASPEED Graphics Family                                    | 1        | 1.96%   |
| AMD Wrestler [Radeon HD 7310]                                               | 1        | 1.96%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 1        | 1.96%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 1        | 1.96%   |
| AMD Tonga PRO [Radeon R9 285/380]                                           | 1        | 1.96%   |
| AMD Richland [Radeon HD 8570D]                                              | 1        | 1.96%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 1        | 1.96%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 1        | 1.96%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 1        | 1.96%   |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                            | 1        | 1.96%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 1        | 1.96%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 23       | 47.92%  |
| 1 x AMD         | 15       | 31.25%  |
| 1 x Intel       | 8        | 16.67%  |
| 2 x Nvidia      | 1        | 2.08%   |
| Nvidia + ASPEED | 1        | 2.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 28       | 58.33%  |
| Proprietary | 18       | 37.5%   |
| Unknown     | 2        | 4.17%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 17       | 35.42%  |
| 7.01-8.0   | 9        | 18.75%  |
| 1.01-2.0   | 8        | 16.67%  |
| 5.01-6.0   | 4        | 8.33%   |
| 8.01-16.0  | 4        | 8.33%   |
| 3.01-4.0   | 3        | 6.25%   |
| 0.01-0.5   | 2        | 4.17%   |
| 0.51-1.0   | 1        | 2.08%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 11       | 22.45%  |
| Hewlett-Packard      | 5        | 10.2%   |
| Acer                 | 5        | 10.2%   |
| AOC                  | 4        | 8.16%   |
| Ancor Communications | 4        | 8.16%   |
| Goldstar             | 3        | 6.12%   |
| Lenovo               | 2        | 4.08%   |
| Iiyama               | 2        | 4.08%   |
| Sony                 | 1        | 2.04%   |
| MSI                  | 1        | 2.04%   |
| Konka                | 1        | 2.04%   |
| Kogan                | 1        | 2.04%   |
| KOC                  | 1        | 2.04%   |
| JRY                  | 1        | 2.04%   |
| Idek Iiyama          | 1        | 2.04%   |
| Hitachi              | 1        | 2.04%   |
| Gigabyte Technology  | 1        | 2.04%   |
| FOX                  | 1        | 2.04%   |
| Dell                 | 1        | 2.04%   |
| ASUSTek Computer     | 1        | 2.04%   |
| Unknown              | 1        | 2.04%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch    | 2        | 3.77%   |
| Sony LCD Monitor AVSYSTEM 1280x720                                   | 1        | 1.89%   |
| Samsung Electronics T27B300 SAM0933 1920x1080 598x336mm 27.0-inch    | 1        | 1.89%   |
| Samsung Electronics SyncMaster SAM0524 1920x1080 477x268mm 21.5-inch | 1        | 1.89%   |
| Samsung Electronics SyncMaster SAM02FE 1680x1050 433x271mm 20.1-inch | 1        | 1.89%   |
| Samsung Electronics SMS24A350H SAM07D6 1920x1080 531x299mm 24.0-inch | 1        | 1.89%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch    | 1        | 1.89%   |
| Samsung Electronics LCD Monitor SAM02EB 1920x540                     | 1        | 1.89%   |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch  | 1        | 1.89%   |
| Samsung Electronics LC24RG50 SAM0F91 1920x1080 532x304mm 24.1-inch   | 1        | 1.89%   |
| Samsung Electronics C27R50x SAM0F9E 1920x1080 598x336mm 27.0-inch    | 1        | 1.89%   |
| MSI G24C4 MSI3BA0 1920x1080 521x293mm 23.5-inch                      | 1        | 1.89%   |
| Lenovo LEN T24i-10 LEN61CE 1920x1080 527x296mm 23.8-inch             | 1        | 1.89%   |
| Lenovo G24-20 LEN66CF 1920x1080 530x300mm 24.0-inch                  | 1        | 1.89%   |
| Konka TV MONIOR KOA0030 1920x540 708x398mm 32.0-inch                 | 1        | 1.89%   |
| Kogan HDMI1 KGN3400 3440x1440 796x334mm 34.0-inch                    | 1        | 1.89%   |
| KOC SXGA85_ANALOG KOC0482 1280x1024 365x292mm 18.4-inch              | 1        | 1.89%   |
| JRY VIZTA JRY2700 1920x1080 598x336mm 27.0-inch                      | 1        | 1.89%   |
| Iiyama PL3466WQ IVM761A 3440x1440 797x334mm 34.0-inch                | 1        | 1.89%   |
| Iiyama PL2409HD IVM560C 1920x1080 521x293mm 23.5-inch                | 1        | 1.89%   |
| Idek Iiyama LCD Monitor PL2760Q 2560x1440                            | 1        | 1.89%   |
| Hitachi HISENSE HEC002F 3840x2160 1872x1053mm 84.6-inch              | 1        | 1.89%   |
| Hewlett-Packard V27e HPN36B1 1920x1080 598x336mm 27.0-inch           | 1        | 1.89%   |
| Hewlett-Packard TouchSmart HWP4218 1600x900 443x249mm 20.0-inch      | 1        | 1.89%   |
| Hewlett-Packard M24fe FHD HPN378B 1920x1080 527x296mm 23.8-inch      | 1        | 1.89%   |
| Hewlett-Packard M24f FHD HPN3707 1920x1080 527x296mm 23.8-inch       | 1        | 1.89%   |
| Hewlett-Packard E240c HWP327C 1920x1080 510x290mm 23.1-inch          | 1        | 1.89%   |
| Hewlett-Packard 27w HPN3494 1920x1080 598x336mm 27.0-inch            | 1        | 1.89%   |
| Goldstar ULTRAWIDE GSM76FA 2560x1080 531x298mm 24.0-inch             | 1        | 1.89%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                | 1        | 1.89%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 1        | 1.89%   |
| Goldstar 22EN43 GSM59D8 1920x1080 477x268mm 21.5-inch                | 1        | 1.89%   |
| Gigabyte Technology M27Q GBT270D 2560x1440 596x335mm 26.9-inch       | 1        | 1.89%   |
| FOX FBC TV FOX9C01 1366x768 698x393mm 31.5-inch                      | 1        | 1.89%   |
| Dell U3219Q DELA124 1920x1200 697x392mm 31.5-inch                    | 1        | 1.89%   |
| ASUSTek Computer VG279QM AUS278F 1920x1080 598x336mm 27.0-inch       | 1        | 1.89%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                  | 1        | 1.89%   |
| AOC Q2963 AOC2963 2560x1080 673x284mm 28.8-inch                      | 1        | 1.89%   |
| AOC Q2963 AOC2963 2560x1080 670x280mm 28.6-inch                      | 1        | 1.89%   |
| AOC Q27G2G4 AOC2702 2560x1440 600x340mm 27.2-inch                    | 1        | 1.89%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 22       | 46.81%  |
| 2560x1440 (QHD)    | 6        | 12.77%  |
| 3440x1440          | 5        | 10.64%  |
| 3840x2160 (4K)     | 4        | 8.51%   |
| 2560x1080          | 2        | 4.26%   |
| 3840x1080          | 1        | 2.13%   |
| 1920x540           | 1        | 2.13%   |
| 1680x1050 (WSXGA+) | 1        | 2.13%   |
| 1600x900 (HD+)     | 1        | 2.13%   |
| 1366x768 (WXGA)    | 1        | 2.13%   |
| 1360x768           | 1        | 2.13%   |
| 1280x720 (HD)      | 1        | 2.13%   |
| 1280x1024 (SXGA)   | 1        | 2.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 11       | 22%     |
| 24      | 7        | 14%     |
| 34      | 6        | 12%     |
| 23      | 6        | 12%     |
| 21      | 5        | 10%     |
| Unknown | 4        | 8%      |
| 31      | 3        | 6%      |
| 20      | 2        | 4%      |
| 84      | 1        | 2%      |
| 52      | 1        | 2%      |
| 48      | 1        | 2%      |
| 33      | 1        | 2%      |
| 28      | 1        | 2%      |
| 18      | 1        | 2%      |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 22       | 45.83%  |
| 701-800     | 7        | 14.58%  |
| 401-500     | 7        | 14.58%  |
| 601-700     | 4        | 8.33%   |
| Unknown     | 4        | 8.33%   |
| 1001-1500   | 2        | 4.17%   |
| 351-400     | 1        | 2.08%   |
| 1501-2000   | 1        | 2.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 32       | 71.11%  |
| 21/9    | 7        | 15.56%  |
| Unknown | 3        | 6.67%   |
| 5/4     | 1        | 2.22%   |
| 32/9    | 1        | 2.22%   |
| 16/10   | 1        | 2.22%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 16       | 32.65%  |
| 301-350        | 11       | 22.45%  |
| 351-500        | 10       | 20.41%  |
| Unknown        | 4        | 8.16%   |
| 151-200        | 3        | 6.12%   |
| More than 1000 | 2        | 4.08%   |
| 251-300        | 2        | 4.08%   |
| 501-1000       | 1        | 2.04%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 26       | 59.09%  |
| 101-120 | 10       | 22.73%  |
| Unknown | 4        | 9.09%   |
| 1-50    | 2        | 4.55%   |
| 161-240 | 1        | 2.27%   |
| 121-160 | 1        | 2.27%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 36       | 73.47%  |
| 2     | 11       | 22.45%  |
| 0     | 2        | 4.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 32       | 46.38%  |
| Intel                           | 24       | 34.78%  |
| Broadcom                        | 3        | 4.35%   |
| Ralink Technology               | 2        | 2.9%    |
| Qualcomm Atheros                | 2        | 2.9%    |
| TP-Link                         | 1        | 1.45%   |
| Ralink                          | 1        | 1.45%   |
| Qualcomm Atheros Communications | 1        | 1.45%   |
| Qualcomm                        | 1        | 1.45%   |
| NetGear                         | 1        | 1.45%   |
| Microsoft                       | 1        | 1.45%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller         | 25       | 30.86%  |
| Intel I211 Gigabit Network Connection                                     | 6        | 7.41%   |
| Realtek RTL8125 2.5GbE Controller                                         | 5        | 6.17%   |
| Intel Wi-Fi 6 AX200                                                       | 5        | 6.17%   |
| Intel Ethernet Connection (2) I219-V                                      | 5        | 6.17%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                        | 2        | 2.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                  | 2        | 2.47%   |
| Intel Wireless 7265                                                       | 2        | 2.47%   |
| Intel Ethernet Connection I217-LM                                         | 2        | 2.47%   |
| Intel Ethernet Connection (7) I219-V                                      | 2        | 2.47%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                          | 2        | 2.47%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                     | 2        | 2.47%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                           | 2        | 2.47%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                       | 1        | 1.23%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                           | 1        | 1.23%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                           | 1        | 1.23%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                     | 1        | 1.23%   |
| Ralink RT2501/RT2573 Wireless Adapter                                     | 1        | 1.23%   |
| Ralink MT7601U Wireless Adapter                                           | 1        | 1.23%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                    | 1        | 1.23%   |
| Qualcomm Fairphone 4 5G                                                   | 1        | 1.23%   |
| Qualcomm Atheros AR9271 802.11n                                           | 1        | 1.23%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                          | 1        | 1.23%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)            | 1        | 1.23%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet            | 1        | 1.23%   |
| NetGear Nighthawk A7000 802.11ac Wireless Adapter AC1900 [Realtek 8814AU] | 1        | 1.23%   |
| Microsoft Xbox 360 Wireless Adapter                                       | 1        | 1.23%   |
| Intel Wireless-AC 9260                                                    | 1        | 1.23%   |
| Intel Ethernet Connection (11) I219-V                                     | 1        | 1.23%   |
| Intel Cannon Lake PCH CNVi WiFi                                           | 1        | 1.23%   |
| Broadcom BCM43228 802.11a/b/g/n                                           | 1        | 1.23%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller       | 1        | 1.23%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 11       | 40.74%  |
| Realtek Semiconductor           | 6        | 22.22%  |
| Ralink Technology               | 2        | 7.41%   |
| Qualcomm Atheros                | 2        | 7.41%   |
| Broadcom                        | 2        | 7.41%   |
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
| Realtek RTL88x2bu [AC1200 Techkey]                                        | 2        | 7.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                  | 2        | 7.41%   |
| Intel Wireless 7265                                                       | 2        | 7.41%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                          | 2        | 7.41%   |
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
| Realtek Semiconductor | 30       | 56.6%   |
| Intel                 | 18       | 33.96%  |
| Broadcom              | 2        | 3.77%   |
| TP-Link               | 1        | 1.89%   |
| Qualcomm Atheros      | 1        | 1.89%   |
| Qualcomm              | 1        | 1.89%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 25       | 46.3%   |
| Intel I211 Gigabit Network Connection                             | 6        | 11.11%  |
| Realtek RTL8125 2.5GbE Controller                                 | 5        | 9.26%   |
| Intel Ethernet Connection (2) I219-V                              | 5        | 9.26%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 3.7%    |
| Intel Ethernet Connection (7) I219-V                              | 2        | 3.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 3.7%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2        | 3.7%    |
| TP-Link Archer T2U PLUS [RTL8821AU]                               | 1        | 1.85%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 1.85%   |
| Qualcomm Fairphone 4 5G                                           | 1        | 1.85%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 1.85%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 1.85%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 48       | 64.86%  |
| WiFi     | 26       | 35.14%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 37       | 74%     |
| WiFi     | 13       | 26%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 26       | 54.17%  |
| 2     | 19       | 39.58%  |
| 3     | 3        | 6.25%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 37       | 75.51%  |
| Yes  | 12       | 24.49%  |

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
| Intel                  | 30       | 32.61%  |
| Nvidia                 | 24       | 26.09%  |
| AMD                    | 21       | 22.83%  |
| Corsair                | 3        | 3.26%   |
| C-Media Electronics    | 3        | 3.26%   |
| Razer USA              | 2        | 2.17%   |
| Kingston Technology    | 2        | 2.17%   |
| Tenx Technology        | 1        | 1.09%   |
| Plantronics            | 1        | 1.09%   |
| Logitech               | 1        | 1.09%   |
| Hewlett-Packard        | 1        | 1.09%   |
| Generalplus Technology | 1        | 1.09%   |
| ELMCU                  | 1        | 1.09%   |
| Astro Gaming           | 1        | 1.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 10       | 9.43%   |
| Intel 200 Series PCH HD Audio                                              | 7        | 6.6%    |
| Nvidia GP104 High Definition Audio Controller                              | 5        | 4.72%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5        | 4.72%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4        | 3.77%   |
| Nvidia TU106 High Definition Audio Controller                              | 3        | 2.83%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3        | 2.83%   |
| Intel Cannon Lake PCH cAVS                                                 | 3        | 2.83%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3        | 2.83%   |
| AMD Navi 10 HDMI Audio                                                     | 3        | 2.83%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3        | 2.83%   |
| Nvidia TU116 High Definition Audio Controller                              | 2        | 1.89%   |
| Nvidia GP106 High Definition Audio Controller                              | 2        | 1.89%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2        | 1.89%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2        | 1.89%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 2        | 1.89%   |
| AMD FCH Azalia Controller                                                  | 2        | 1.89%   |
| Tenx Technology USB AUDIO                                                  | 1        | 0.94%   |
| Razer USA RZ04-0318 Gaming Headset [Kraken Ultimate]                       | 1        | 0.94%   |
| Razer USA Razer Kraken X USB                                               | 1        | 0.94%   |
| Plantronics C320-M                                                         | 1        | 0.94%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1        | 0.94%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 0.94%   |
| Nvidia GP102 HDMI Audio Controller                                         | 1        | 0.94%   |
| Nvidia GM206 High Definition Audio Controller                              | 1        | 0.94%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 0.94%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 0.94%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1        | 0.94%   |
| Nvidia GF106 High Definition Audio Controller                              | 1        | 0.94%   |
| Nvidia GA106 High Definition Audio Controller                              | 1        | 0.94%   |
| Nvidia GA102 High Definition Audio Controller                              | 1        | 0.94%   |
| Logitech CONEXANT USB AUDIO                                                | 1        | 0.94%   |
| Kingston Technology HyperX Cloud Flight Wireless                           | 1        | 0.94%   |
| Kingston Technology HyperX 7.1 Audio                                       | 1        | 0.94%   |
| Intel Comet Lake PCH cAVS                                                  | 1        | 0.94%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1        | 0.94%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 1        | 0.94%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 1        | 0.94%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1        | 0.94%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1        | 0.94%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 10       | 21.74%  |
| SK hynix            | 6        | 13.04%  |
| G.Skill             | 6        | 13.04%  |
| Unknown             | 4        | 8.7%    |
| Samsung Electronics | 4        | 8.7%    |
| Crucial             | 4        | 8.7%    |
| Kingston            | 3        | 6.52%   |
| Team                | 2        | 4.35%   |
| Micron Technology   | 2        | 4.35%   |
| Unifosa             | 1        | 2.17%   |
| Transcend           | 1        | 2.17%   |
| Ramaxel Technology  | 1        | 2.17%   |
| PNY                 | 1        | 2.17%   |
| A-DATA Technology   | 1        | 2.17%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s  | 2        | 3.85%   |
| Kingston RAM KHX2133C14/16G 16GB DIMM DDR4 2176MT/s     | 2        | 3.85%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s   | 2        | 3.85%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s               | 1        | 1.92%   |
| Unknown RAM Module 4GB DIMM DDR4 2133MT/s               | 1        | 1.92%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                | 1        | 1.92%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                | 1        | 1.92%   |
| Unifosa RAM GU512303EP0202 2GB DIMM DDR3 1333MT/s       | 1        | 1.92%   |
| Transcend RAM TS1GLK64V6H 8GB DIMM DDR3 1600MT/s        | 1        | 1.92%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s      | 1        | 1.92%   |
| Team RAM TEAMGROUP-UD3-1600 4GB DIMM DDR3 1600MT/s      | 1        | 1.92%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s    | 1        | 1.92%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 1        | 1.92%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s    | 1        | 1.92%   |
| SK hynix RAM HMT351U6BFR8C-H9 4096MB DIMM 1450MT/s      | 1        | 1.92%   |
| SK hynix RAM HMA81GU6MFR8N-UH 8GB DIMM DDR4 2400MT/s    | 1        | 1.92%   |
| SK hynix RAM HMA451R7MFR8N-TFTD 4GB DIMM DDR4 2133MT/s  | 1        | 1.92%   |
| SK hynix RAM HMA451R7MFR8N-TF 4GB DIMM DDR4 2133MT/s    | 1        | 1.92%   |
| Samsung RAM Module 8GB DIMM DDR4 2666MT/s               | 1        | 1.92%   |
| Samsung RAM Module 8GB DIMM DDR4 2133MT/s               | 1        | 1.92%   |
| Samsung RAM M393A5143DB0-CPB 4GB DIMM DDR4 2133MT/s     | 1        | 1.92%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM 1600MT/s          | 1        | 1.92%   |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR3 1867MT/s     | 1        | 1.92%   |
| Ramaxel RAM RMUA5110MB78HAF-2400 8GB DIMM DDR4 2400MT/s | 1        | 1.92%   |
| PNY RAM 8GBF1X08QFHH36-135-K 8GB DIMM DDR4 2933MT/s     | 1        | 1.92%   |
| Micron RAM 8KTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s     | 1        | 1.92%   |
| Micron RAM 16KTF1G64AZ-1G6E1 8GB DIMM DDR3 1600MT/s     | 1        | 1.92%   |
| Kingston RAM KHX3600C18D4/16GX 16GB DIMM DDR4 3600MT/s  | 1        | 1.92%   |
| Kingston RAM KHX3466C19D4/16G 16GB DIMM DDR4 3467MT/s   | 1        | 1.92%   |
| G.Skill RAM F4-3600C17-8GTZR 8GB DIMM DDR4 3600MT/s     | 1        | 1.92%   |
| G.Skill RAM F4-3600C16-8GTZNC 8GB DIMM DDR4 3800MT/s    | 1        | 1.92%   |
| G.Skill RAM F4-3600C16-16GTZRC 16GB DIMM DDR4 4400MT/s  | 1        | 1.92%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s  | 1        | 1.92%   |
| G.Skill RAM F4-3200C16-8GTZKW 8GB DIMM DDR4 3200MT/s    | 1        | 1.92%   |
| G.Skill RAM F4-3200C16-8GTZKO 8GB DIMM DDR4 3200MT/s    | 1        | 1.92%   |
| G.Skill RAM F4-2666C15-4GVR 4GB DIMM DDR4 2933MT/s      | 1        | 1.92%   |
| Crucial RAM CT4G4DFS824A.C8FHP 4GB DIMM DDR4 2400MT/s   | 1        | 1.92%   |
| Crucial RAM CT25664BD160B.C8FN 2GB DIMM DDR3 1333MT/s   | 1        | 1.92%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1800MT/s   | 1        | 1.92%   |
| Crucial RAM BL16G32C16U4R.M16FE 16GB DIMM DDR4 3200MT/s | 1        | 1.92%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Desktops | Percent |
|-------|----------|---------|
| DDR4  | 27       | 67.5%   |
| DDR3  | 10       | 25%     |
| SDRAM | 1        | 2.5%    |
| DDR2  | 1        | 2.5%    |
| DDR   | 1        | 2.5%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 37       | 94.87%  |
| SODIMM | 2        | 5.13%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 18       | 40.91%  |
| 4096  | 12       | 27.27%  |
| 16384 | 11       | 25%     |
| 2048  | 3        | 6.82%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 8        | 17.78%  |
| 1600  | 7        | 15.56%  |
| 3600  | 4        | 8.89%   |
| 2933  | 3        | 6.67%   |
| 2400  | 3        | 6.67%   |
| 1800  | 3        | 6.67%   |
| 3400  | 2        | 4.44%   |
| 2176  | 2        | 4.44%   |
| 2133  | 2        | 4.44%   |
| 1333  | 2        | 4.44%   |
| 4400  | 1        | 2.22%   |
| 4133  | 1        | 2.22%   |
| 3800  | 1        | 2.22%   |
| 3467  | 1        | 2.22%   |
| 2747  | 1        | 2.22%   |
| 2666  | 1        | 2.22%   |
| 1867  | 1        | 2.22%   |
| 1450  | 1        | 2.22%   |
| 800   | 1        | 2.22%   |

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
| Generalplus Technology                 | 2        | 25%     |
| Chicony Electronics                    | 2        | 25%     |
| Panasonic (Matsushita)                 | 1        | 12.5%   |
| Microdia                               | 1        | 12.5%   |
| Logitech                               | 1        | 12.5%   |
| Cheng Uei Precision Industry (Foxlink) | 1        | 12.5%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Chicony HP High Definition 1MP Webcam                                | 2        | 25%     |
| Panasonic (Matsushita) TY-CC20W                                      | 1        | 12.5%   |
| Microdia Webcam Vitade AF                                            | 1        | 12.5%   |
| Logitech Webcam C600                                                 | 1        | 12.5%   |
| Generalplus GENERAL WEBCAM                                           | 1        | 12.5%   |
| Generalplus campark PC04                                             | 1        | 12.5%   |
| Cheng Uei Precision Industry (Foxlink) HP High Definition 1MP Webcam | 1        | 12.5%   |

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
| 0     | 40       | 83.33%  |
| 1     | 8        | 16.67%  |

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

