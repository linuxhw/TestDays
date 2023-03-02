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

Total: 57

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
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
| Xero Rolling | 36       | 87.8%   |
| Xero         | 5        | 12.2%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| Xero | 41       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Desktops | Percent |
|-------------------------|----------|---------|
| 6.1.12-arch1-1          | 4        | 8.51%   |
| 5.18.16-arch1-1         | 2        | 4.26%   |
| 5.16.15-arch1-1         | 2        | 4.26%   |
| 5.16.12-arch1-1         | 2        | 4.26%   |
| 6.1.6-arch1-3           | 1        | 2.13%   |
| 6.0.6-zen1-1-zen        | 1        | 2.13%   |
| 6.0.2-zen1-1-zen        | 1        | 2.13%   |
| 6.0.1-arch2-1           | 1        | 2.13%   |
| 5.19.9-arch1-1          | 1        | 2.13%   |
| 5.19.2-zen1-1-zen       | 1        | 2.13%   |
| 5.19.13-zen1-1-zen      | 1        | 2.13%   |
| 5.19.13-arch1-1         | 1        | 2.13%   |
| 5.19.10-arch1-1         | 1        | 2.13%   |
| 5.18.9-arch1-1          | 1        | 2.13%   |
| 5.18.6-arch1-1          | 1        | 2.13%   |
| 5.18.3-arch1-1          | 1        | 2.13%   |
| 5.18.0-arch1-1          | 1        | 2.13%   |
| 5.17.5-arch1-1          | 1        | 2.13%   |
| 5.17.1-arch1-1          | 1        | 2.13%   |
| 5.16.16-zen1-1-zen      | 1        | 2.13%   |
| 5.16.16-arch1-1         | 1        | 2.13%   |
| 5.16.13-arch1-1         | 1        | 2.13%   |
| 5.16.1-arch1-1          | 1        | 2.13%   |
| 5.15.4-arch1-1          | 1        | 2.13%   |
| 5.15.33-1-lts           | 1        | 2.13%   |
| 5.15.3-zen1-1-zen       | 1        | 2.13%   |
| 5.15.24-1-lts           | 1        | 2.13%   |
| 5.15.13-AMD             | 1        | 2.13%   |
| 5.15.12-zen1-1-zen      | 1        | 2.13%   |
| 5.15.12-arch1-1-surface | 1        | 2.13%   |
| 5.15.12-arch1-1         | 1        | 2.13%   |
| 5.15.11-arch2-1-surface | 1        | 2.13%   |
| 5.15.10-arch1-1         | 1        | 2.13%   |
| 5.14.9-zen2-1-zen       | 1        | 2.13%   |
| 5.14.8-zen1-1-zen       | 1        | 2.13%   |
| 5.14.15-zen1-1-zen      | 1        | 2.13%   |
| 5.14.14-arch1-1         | 1        | 2.13%   |
| 5.13.4-zen1-1-zen       | 1        | 2.13%   |
| 5.13.13-AMD             | 1        | 2.13%   |
| 5.12.5-AMD              | 1        | 2.13%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.1.12  | 4        | 8.51%   |
| 5.15.12 | 3        | 6.38%   |
| 5.19.13 | 2        | 4.26%   |
| 5.18.16 | 2        | 4.26%   |
| 5.16.16 | 2        | 4.26%   |
| 5.16.15 | 2        | 4.26%   |
| 5.16.12 | 2        | 4.26%   |
| 6.1.6   | 1        | 2.13%   |
| 6.0.6   | 1        | 2.13%   |
| 6.0.2   | 1        | 2.13%   |
| 6.0.1   | 1        | 2.13%   |
| 5.19.9  | 1        | 2.13%   |
| 5.19.2  | 1        | 2.13%   |
| 5.19.10 | 1        | 2.13%   |
| 5.18.9  | 1        | 2.13%   |
| 5.18.6  | 1        | 2.13%   |
| 5.18.3  | 1        | 2.13%   |
| 5.18.0  | 1        | 2.13%   |
| 5.17.5  | 1        | 2.13%   |
| 5.17.1  | 1        | 2.13%   |
| 5.16.13 | 1        | 2.13%   |
| 5.16.1  | 1        | 2.13%   |
| 5.15.4  | 1        | 2.13%   |
| 5.15.33 | 1        | 2.13%   |
| 5.15.3  | 1        | 2.13%   |
| 5.15.24 | 1        | 2.13%   |
| 5.15.13 | 1        | 2.13%   |
| 5.15.11 | 1        | 2.13%   |
| 5.15.10 | 1        | 2.13%   |
| 5.14.9  | 1        | 2.13%   |
| 5.14.8  | 1        | 2.13%   |
| 5.14.15 | 1        | 2.13%   |
| 5.14.14 | 1        | 2.13%   |
| 5.13.4  | 1        | 2.13%   |
| 5.13.13 | 1        | 2.13%   |
| 5.12.5  | 1        | 2.13%   |
| 5.11.16 | 1        | 2.13%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 9        | 19.57%  |
| 5.16    | 8        | 17.39%  |
| 5.18    | 6        | 13.04%  |
| 6.1     | 5        | 10.87%  |
| 5.19    | 5        | 10.87%  |
| 5.14    | 4        | 8.7%    |
| 6.0     | 3        | 6.52%   |
| 5.17    | 2        | 4.35%   |
| 5.13    | 2        | 4.35%   |
| 5.12    | 1        | 2.17%   |
| 5.11    | 1        | 2.17%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 41       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| KDE5  | 39       | 92.86%  |
| XFCE  | 2        | 4.76%   |
| GNOME | 1        | 2.38%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 37       | 90.24%  |
| Wayland | 2        | 4.88%   |
| Tty     | 2        | 4.88%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 29       | 69.05%  |
| Unknown | 7        | 16.67%  |
| LightDM | 4        | 9.52%   |
| TDM     | 1        | 2.38%   |
| GDM     | 1        | 2.38%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 23       | 56.1%   |
| en_GB | 5        | 12.2%   |
| de_DE | 3        | 7.32%   |
| C     | 2        | 4.88%   |
| ru_RU | 1        | 2.44%   |
| pl_PL | 1        | 2.44%   |
| es_MX | 1        | 2.44%   |
| en_IN | 1        | 2.44%   |
| en_CA | 1        | 2.44%   |
| en_AU | 1        | 2.44%   |
| de_AT | 1        | 2.44%   |
| ba_RU | 1        | 2.44%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 25       | 60.98%  |
| BIOS | 16       | 39.02%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Btrfs   | 22       | 52.38%  |
| Ext4    | 9        | 21.43%  |
| Xfs     | 8        | 19.05%  |
| Overlay | 3        | 7.14%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 29       | 70.73%  |
| Unknown | 7        | 17.07%  |
| MBR     | 5        | 12.2%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 26       | 60.47%  |
| Yes       | 17       | 39.53%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 25       | 60.98%  |
| Yes       | 16       | 39.02%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 16       | 39.02%  |
| Hewlett-Packard     | 5        | 12.2%   |
| MSI                 | 4        | 9.76%   |
| Gigabyte Technology | 4        | 9.76%   |
| Dell                | 3        | 7.32%   |
| ASRock              | 3        | 7.32%   |
| Pegatron            | 2        | 4.88%   |
| Acer                | 2        | 4.88%   |
| JINGSHA             | 1        | 2.44%   |
| Unknown             | 1        | 2.44%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| MSI MS-7971                       | 2        | 4.88%   |
| ASUS TUF Gaming X570-PLUS         | 2        | 4.88%   |
| Unknown                           | 2        | 4.88%   |
| Pegatron p6-2026                  | 1        | 2.44%   |
| Pegatron 20-b010                  | 1        | 2.44%   |
| MSI MS-7C91                       | 1        | 2.44%   |
| MSI MS-7B61                       | 1        | 2.44%   |
| HP Z230 SFF Workstation           | 1        | 2.44%   |
| HP ProOne 400 G1 AiO              | 1        | 2.44%   |
| HP Pavilion Desktop 590-p0xxx     | 1        | 2.44%   |
| HP Compaq Elite 8300 CMT          | 1        | 2.44%   |
| HP 750-424                        | 1        | 2.44%   |
| Gigabyte Z170X-UD3                | 1        | 2.44%   |
| Gigabyte X570 AORUS MASTER        | 1        | 2.44%   |
| Gigabyte B460MDS3HV2              | 1        | 2.44%   |
| Gigabyte A320M-S2H                | 1        | 2.44%   |
| Dell Studio XPS 8100              | 1        | 2.44%   |
| Dell Precision T1500              | 1        | 2.44%   |
| Dell OptiPlex 7010                | 1        | 2.44%   |
| ASUS TUF Z390-PLUS GAMING         | 1        | 2.44%   |
| ASUS TUF Gaming B550M-PLUS        | 1        | 2.44%   |
| ASUS TUF B360M-PLUS GAMING/BR     | 1        | 2.44%   |
| ASUS ROG STRIX Z370-F GAMING      | 1        | 2.44%   |
| ASUS ROG STRIX X570-F GAMING      | 1        | 2.44%   |
| ASUS ROG STRIX B450-F GAMING      | 1        | 2.44%   |
| ASUS ROG Maximus X HERO           | 1        | 2.44%   |
| ASUS ROG CROSSHAIR VIII HERO      | 1        | 2.44%   |
| ASUS ROG CROSSHAIR VIII DARK HERO | 1        | 2.44%   |
| ASUS PRIME B250-PLUS              | 1        | 2.44%   |
| ASUS PRIME A320M-K                | 1        | 2.44%   |
| ASUS P7P55 LX                     | 1        | 2.44%   |
| ASUS P5Q PRO TURBO                | 1        | 2.44%   |
| ASUS Maximus IX HERO              | 1        | 2.44%   |
| ASRock X570 Taichi                | 1        | 2.44%   |
| ASRock B450M Pro4                 | 1        | 2.44%   |
| ASRock AB350 Pro4                 | 1        | 2.44%   |
| Acer Aspire XC-886                | 1        | 2.44%   |
| Acer Aspire X5950                 | 1        | 2.44%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| ASUS ROG             | 6        | 14.63%  |
| ASUS TUF             | 5        | 12.2%   |
| MSI MS-7971          | 2        | 4.88%   |
| ASUS PRIME           | 2        | 4.88%   |
| Acer Aspire          | 2        | 4.88%   |
| Unknown              | 2        | 4.88%   |
| Pegatron p6-2026     | 1        | 2.44%   |
| Pegatron 20-b010     | 1        | 2.44%   |
| MSI MS-7C91          | 1        | 2.44%   |
| MSI MS-7B61          | 1        | 2.44%   |
| HP Z230              | 1        | 2.44%   |
| HP ProOne            | 1        | 2.44%   |
| HP Pavilion          | 1        | 2.44%   |
| HP Compaq            | 1        | 2.44%   |
| HP 750-424           | 1        | 2.44%   |
| Gigabyte Z170X-UD3   | 1        | 2.44%   |
| Gigabyte X570        | 1        | 2.44%   |
| Gigabyte B460MDS3HV2 | 1        | 2.44%   |
| Gigabyte A320M-S2H   | 1        | 2.44%   |
| Dell Studio          | 1        | 2.44%   |
| Dell Precision       | 1        | 2.44%   |
| Dell OptiPlex        | 1        | 2.44%   |
| ASUS P7P55           | 1        | 2.44%   |
| ASUS P5Q             | 1        | 2.44%   |
| ASUS Maximus         | 1        | 2.44%   |
| ASRock X570          | 1        | 2.44%   |
| ASRock B450M         | 1        | 2.44%   |
| ASRock AB350         | 1        | 2.44%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 7        | 17.07%  |
| 2018 | 6        | 14.63%  |
| 2017 | 6        | 14.63%  |
| 2020 | 5        | 12.2%   |
| 2015 | 3        | 7.32%   |
| 2010 | 3        | 7.32%   |
| 2013 | 2        | 4.88%   |
| 2012 | 2        | 4.88%   |
| 2009 | 2        | 4.88%   |
| 2022 | 1        | 2.44%   |
| 2021 | 1        | 2.44%   |
| 2016 | 1        | 2.44%   |
| 2014 | 1        | 2.44%   |
| 2011 | 1        | 2.44%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 41       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 41       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 41       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 13       | 31.71%  |
| 32.01-64.0  | 12       | 29.27%  |
| 8.01-16.0   | 8        | 19.51%  |
| 4.01-8.0    | 5        | 12.2%   |
| 3.01-4.0    | 1        | 2.44%   |
| 24.01-32.0  | 1        | 2.44%   |
| 64.01-256.0 | 1        | 2.44%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 12       | 25.53%  |
| 2.01-3.0   | 12       | 25.53%  |
| 1.01-2.0   | 8        | 17.02%  |
| 8.01-16.0  | 5        | 10.64%  |
| 3.01-4.0   | 4        | 8.51%   |
| 16.01-24.0 | 3        | 6.38%   |
| 0.01-0.5   | 2        | 4.26%   |
| 0.51-1.0   | 1        | 2.13%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 12       | 29.27%  |
| 3      | 9        | 21.95%  |
| 2      | 9        | 21.95%  |
| 5      | 4        | 9.76%   |
| 4      | 4        | 9.76%   |
| 6      | 2        | 4.88%   |
| 7      | 1        | 2.44%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 29       | 70.73%  |
| Yes       | 12       | 29.27%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 41       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 24       | 58.54%  |
| No        | 17       | 41.46%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 22       | 52.38%  |
| No        | 20       | 47.62%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 11       | 26.83%  |
| UK          | 3        | 7.32%   |
| Germany     | 3        | 7.32%   |
| Russia      | 2        | 4.88%   |
| Poland      | 2        | 4.88%   |
| Mexico      | 2        | 4.88%   |
| Canada      | 2        | 4.88%   |
| Sweden      | 1        | 2.44%   |
| Spain       | 1        | 2.44%   |
| Portugal    | 1        | 2.44%   |
| Netherlands | 1        | 2.44%   |
| Lebanon     | 1        | 2.44%   |
| Italy       | 1        | 2.44%   |
| India       | 1        | 2.44%   |
| Greece      | 1        | 2.44%   |
| Czechia     | 1        | 2.44%   |
| Cyprus      | 1        | 2.44%   |
| Colombia    | 1        | 2.44%   |
| Brazil      | 1        | 2.44%   |
| Bahrain     | 1        | 2.44%   |
| Austria     | 1        | 2.44%   |
| Australia   | 1        | 2.44%   |
| Argentina   | 1        | 2.44%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Zell am See    | 1        | 2.44%   |
| Wroclaw        | 1        | 2.44%   |
| Wrexham        | 1        | 2.44%   |
| Wells          | 1        | 2.44%   |
| Warsaw         | 1        | 2.44%   |
| Stow           | 1        | 2.44%   |
| Springfield    | 1        | 2.44%   |
| Sonora         | 1        | 2.44%   |
| Shadrinsk      | 1        | 2.44%   |
| Salt Lake City | 1        | 2.44%   |
| Portland       | 1        | 2.44%   |
| Phoenix        | 1        | 2.44%   |
| Passos         | 1        | 2.44%   |
| Oberursel      | 1        | 2.44%   |
| Nicosia        | 1        | 2.44%   |
| New Haven      | 1        | 2.44%   |
| Moscow         | 1        | 2.44%   |
| Montreal       | 1        | 2.44%   |
| Monterrey      | 1        | 2.44%   |
| Milton Keynes  | 1        | 2.44%   |
| Mexico City    | 1        | 2.44%   |
| Manama         | 1        | 2.44%   |
| Longview       | 1        | 2.44%   |
| Lisbon         | 1        | 2.44%   |
| Krizanov       | 1        | 2.44%   |
| Kista          | 1        | 2.44%   |
| Ernakulam      | 1        | 2.44%   |
| Chicago        | 1        | 2.44%   |
| Canovelles     | 1        | 2.44%   |
| Candiac        | 1        | 2.44%   |
| Buenos Aires   | 1        | 2.44%   |
| Bristol        | 1        | 2.44%   |
| Brisbane       | 1        | 2.44%   |
| Brindisi       | 1        | 2.44%   |
| Bremen         | 1        | 2.44%   |
| Bogotá        | 1        | 2.44%   |
| Beirut         | 1        | 2.44%   |
| Athens         | 1        | 2.44%   |
| Almere Stad    | 1        | 2.44%   |
| Aiken          | 1        | 2.44%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 18       | 26     | 18.95%  |
| Seagate                   | 16       | 27     | 16.84%  |
| Samsung Electronics       | 14       | 25     | 14.74%  |
| Kingston                  | 7        | 10     | 7.37%   |
| Toshiba                   | 6        | 8      | 6.32%   |
| SanDisk                   | 6        | 8      | 6.32%   |
| Unknown                   | 3        | 4      | 3.16%   |
| Crucial                   | 3        | 5      | 3.16%   |
| China                     | 3        | 3      | 3.16%   |
| Phison                    | 2        | 2      | 2.11%   |
| Hitachi                   | 2        | 2      | 2.11%   |
| HGST                      | 2        | 2      | 2.11%   |
| A-DATA Technology         | 2        | 2      | 2.11%   |
| XPG                       | 1        | 1      | 1.05%   |
| Transcend                 | 1        | 1      | 1.05%   |
| SPCC                      | 1        | 1      | 1.05%   |
| SK hynix                  | 1        | 1      | 1.05%   |
| Silicon Motion            | 1        | 1      | 1.05%   |
| Realtek Semiconductor     | 1        | 1      | 1.05%   |
| PNY                       | 1        | 1      | 1.05%   |
| Micron/Crucial Technology | 1        | 1      | 1.05%   |
| Micron Technology         | 1        | 2      | 1.05%   |
| Intel                     | 1        | 2      | 1.05%   |
| 2-Power                   | 1        | 1      | 1.05%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD  | 3        | 2.56%   |
| WDC WD10EZEX-60WN4A0 1TB         | 2        | 1.71%   |
| Toshiba DT01ACA300 3TB           | 2        | 1.71%   |
| Seagate ST2000DM006-2DM164 2TB   | 2        | 1.71%   |
| Seagate ST1000DM010-2EP102 1TB   | 2        | 1.71%   |
| SanDisk NVMe SSD Drive 500GB     | 2        | 1.71%   |
| Samsung SSD 970 EVO 1TB          | 2        | 1.71%   |
| Crucial CT500MX500SSD1 500GB     | 2        | 1.71%   |
| XPG GAMMIX S50 2TB               | 1        | 0.85%   |
| WDC WDS512G1X0C-00ENX0 512GB     | 1        | 0.85%   |
| WDC WDS500G3XHC-00SJG0 500GB     | 1        | 0.85%   |
| WDC WDS500G3X0C-00SJG0 500GB     | 1        | 0.85%   |
| WDC WDS500G2B0B-00YS70 500GB SSD | 1        | 0.85%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 1        | 0.85%   |
| WDC WD800JD-00MSA1 80GB          | 1        | 0.85%   |
| WDC WD7500BPKT-75PK4T0 752GB     | 1        | 0.85%   |
| WDC WD6400AAKS-22A7B2 640GB      | 1        | 0.85%   |
| WDC WD5000AAVS-00ZTB0 500GB      | 1        | 0.85%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 1        | 0.85%   |
| WDC WD40EZRZ-22GXCB0 4TB         | 1        | 0.85%   |
| WDC WD2500BEVT-60ZCT1 250GB      | 1        | 0.85%   |
| WDC WD20EZRZ-60Z5HB0 2TB         | 1        | 0.85%   |
| WDC WD20EZBX-00AYRA0 2TB         | 1        | 0.85%   |
| WDC WD2003FZEX-00SRLA0 2TB       | 1        | 0.85%   |
| WDC WD15EADS-11R6B1 1TB          | 1        | 0.85%   |
| WDC WD10EZEX-22MFCA0 1TB         | 1        | 0.85%   |
| WDC WD10EZEX-00KUWA0 1TB         | 1        | 0.85%   |
| WDC WD10EAVS-00D7B1 1TB          | 1        | 0.85%   |
| WDC WD10EADS-00M2B0 1TB          | 1        | 0.85%   |
| WDC WD1002FAEX-00Z3A0 1TB        | 1        | 0.85%   |
| Unknown SD/MMC/MS PRO 16GB       | 1        | 0.85%   |
| Unknown MMC Card  64GB           | 1        | 0.85%   |
| Unknown MMC Card  4GB            | 1        | 0.85%   |
| Unknown MMC Card  128GB          | 1        | 0.85%   |
| Transcend TS120GSSD220S 120GB    | 1        | 0.85%   |
| Toshiba MQ04ABF100 1TB           | 1        | 0.85%   |
| Toshiba MQ01ABD100 1TB           | 1        | 0.85%   |
| Toshiba MK4058GSX 400GB          | 1        | 0.85%   |
| Toshiba HDWR160 6TB              | 1        | 0.85%   |
| Toshiba HDWE160 6TB              | 1        | 0.85%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 16       | 27     | 36.36%  |
| WDC                 | 15       | 21     | 34.09%  |
| Toshiba             | 6        | 8      | 13.64%  |
| Samsung Electronics | 2        | 2      | 4.55%   |
| Hitachi             | 2        | 2      | 4.55%   |
| HGST                | 2        | 2      | 4.55%   |
| Unknown             | 1        | 1      | 2.27%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 7        | 10     | 23.33%  |
| Kingston            | 7        | 10     | 23.33%  |
| Crucial             | 3        | 5      | 10%     |
| China               | 3        | 3      | 10%     |
| WDC                 | 2        | 2      | 6.67%   |
| SanDisk             | 2        | 2      | 6.67%   |
| Transcend           | 1        | 1      | 3.33%   |
| SPCC                | 1        | 1      | 3.33%   |
| PNY                 | 1        | 1      | 3.33%   |
| Micron Technology   | 1        | 1      | 3.33%   |
| A-DATA Technology   | 1        | 1      | 3.33%   |
| 2-Power             | 1        | 1      | 3.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 33       | 63     | 41.77%  |
| SSD  | 24       | 38     | 30.38%  |
| NVMe | 20       | 33     | 25.32%  |
| MMC  | 2        | 3      | 2.53%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 38       | 96     | 59.38%  |
| NVMe | 20       | 33     | 31.25%  |
| SAS  | 4        | 5      | 6.25%   |
| MMC  | 2        | 3      | 3.13%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 28       | 46     | 41.18%  |
| 0.51-1.0   | 23       | 32     | 33.82%  |
| 1.01-2.0   | 10       | 14     | 14.71%  |
| 4.01-10.0  | 4        | 6      | 5.88%   |
| 2.01-3.0   | 2        | 2      | 2.94%   |
| 3.01-4.0   | 1        | 1      | 1.47%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 16       | 36.36%  |
| 1001-2000      | 7        | 15.91%  |
| 101-250        | 5        | 11.36%  |
| 501-1000       | 5        | 11.36%  |
| 251-500        | 3        | 6.82%   |
| 21-50          | 2        | 4.55%   |
| 1-20           | 2        | 4.55%   |
| 51-100         | 2        | 4.55%   |
| 2001-3000      | 1        | 2.27%   |
| Unknown        | 1        | 2.27%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 11       | 25%     |
| 1-20           | 11       | 25%     |
| 51-100         | 5        | 11.36%  |
| 251-500        | 3        | 6.82%   |
| 21-50          | 3        | 6.82%   |
| 1001-2000      | 3        | 6.82%   |
| 501-1000       | 3        | 6.82%   |
| More than 3000 | 2        | 4.55%   |
| 2001-3000      | 2        | 4.55%   |
| Unknown        | 1        | 2.27%   |

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
| Works    | 33       | 87     | 58.93%  |
| Detected | 12       | 35     | 21.43%  |
| Malfunc  | 11       | 15     | 19.64%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 27       | 41.54%  |
| AMD                       | 15       | 23.08%  |
| SanDisk                   | 7        | 10.77%  |
| Samsung Electronics       | 6        | 9.23%   |
| Realtek Semiconductor     | 2        | 3.08%   |
| Phison Electronics        | 2        | 3.08%   |
| SK hynix                  | 1        | 1.54%   |
| Silicon Motion            | 1        | 1.54%   |
| Micron/Crucial Technology | 1        | 1.54%   |
| Micron Technology         | 1        | 1.54%   |
| ASMedia Technology        | 1        | 1.54%   |
| ADATA Technology          | 1        | 1.54%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 13       | 17.57%  |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 6        | 8.11%   |
| Intel SATA Controller [RAID mode]                                              | 4        | 5.41%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 4        | 5.41%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3        | 4.05%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3        | 4.05%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 2        | 2.7%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2        | 2.7%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2        | 2.7%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2        | 2.7%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2        | 2.7%    |
| AMD FCH SATA Controller D                                                      | 2        | 2.7%    |
| AMD 500 Series Chipset SATA Controller                                         | 2        | 2.7%    |
| AMD 400 Series Chipset SATA Controller                                         | 2        | 2.7%    |
| SK hynix BC501 NVMe Solid State Drive                                          | 1        | 1.35%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 1        | 1.35%   |
| SanDisk WD Blue SN570 NVMe SSD                                                 | 1        | 1.35%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1        | 1.35%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1        | 1.35%   |
| SanDisk WD Black NVMe SSD                                                      | 1        | 1.35%   |
| SanDisk Non-Volatile memory controller                                         | 1        | 1.35%   |
| Samsung NVMe SSD Controller 980                                                | 1        | 1.35%   |
| Realtek RTS5763DL NVMe SSD Controller                                          | 1        | 1.35%   |
| Realtek Realtek Non-Volatile memory controller                                 | 1        | 1.35%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1        | 1.35%   |
| Phison E12 NVMe Controller                                                     | 1        | 1.35%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                | 1        | 1.35%   |
| Micron Non-Volatile memory controller                                          | 1        | 1.35%   |
| Intel SSD 660P Series                                                          | 1        | 1.35%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1        | 1.35%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 1        | 1.35%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 1        | 1.35%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1        | 1.35%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 1        | 1.35%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 1        | 1.35%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 1        | 1.35%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 1        | 1.35%   |
| AMD 300 Series Chipset SATA Controller                                         | 1        | 1.35%   |
| ADATA XPG GAMMIX S50 NVMe SSD                                                  | 1        | 1.35%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 37       | 59.68%  |
| NVMe | 20       | 32.26%  |
| RAID | 4        | 6.45%   |
| IDE  | 1        | 1.61%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 26       | 63.41%  |
| AMD    | 15       | 36.59%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| AMD Ryzen 5 3600X 6-Core Processor            | 3        | 7.14%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 2        | 4.76%   |
| Intel Core i7 CPU 870 @ 2.93GHz               | 2        | 4.76%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 2        | 4.76%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 2        | 4.76%   |
| AMD Ryzen 5 3600 6-Core Processor             | 2        | 4.76%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz           | 1        | 2.38%   |
| Intel Genuine CPU 0000 @ 2.10GHz              | 1        | 2.38%   |
| Intel Core i7-7700K CPU @ 4.20GHz             | 1        | 2.38%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 1        | 2.38%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 1        | 2.38%   |
| Intel Core i7 CPU 860 @ 2.80GHz               | 1        | 2.38%   |
| Intel Core i5-9600K CPU @ 3.70GHz             | 1        | 2.38%   |
| Intel Core i5-9400F CPU @ 2.90GHz             | 1        | 2.38%   |
| Intel Core i5-9400 CPU @ 2.90GHz              | 1        | 2.38%   |
| Intel Core i5-6600 CPU @ 3.30GHz              | 1        | 2.38%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 1        | 2.38%   |
| Intel Core i5-6400 CPU @ 2.70GHz              | 1        | 2.38%   |
| Intel Core i5-4670 CPU @ 3.40GHz              | 1        | 2.38%   |
| Intel Core i5-4590T CPU @ 2.00GHz             | 1        | 2.38%   |
| Intel Core i5-10400F CPU @ 2.90GHz            | 1        | 2.38%   |
| Intel Core i3-8100 CPU @ 3.60GHz              | 1        | 2.38%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 1        | 2.38%   |
| Intel Core i3 CPU 540 @ 3.07GHz               | 1        | 2.38%   |
| Intel Core 2 Quad CPU Q9650 @ 3.00GHz         | 1        | 2.38%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 1        | 2.38%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 1        | 2.38%   |
| AMD Ryzen 7 5800X3D 8-Core Processor          | 1        | 2.38%   |
| AMD Ryzen 7 3800X 8-Core Processor            | 1        | 2.38%   |
| AMD Ryzen 7 2700 Eight-Core Processor         | 1        | 2.38%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 1        | 2.38%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 1        | 2.38%   |
| AMD E1-1200 APU with Radeon HD Graphics       | 1        | 2.38%   |
| AMD Athlon 200GE with Radeon Vega Graphics    | 1        | 2.38%   |
| AMD A8-9600 RADEON R7, 10 COMPUTE CORES 4C+6G | 1        | 2.38%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| Intel Core i5     | 11       | 26.19%  |
| Intel Core i7     | 8        | 19.05%  |
| AMD Ryzen 5       | 7        | 16.67%  |
| AMD Ryzen 7       | 5        | 11.9%   |
| Intel Core i3     | 3        | 7.14%   |
| Intel Xeon        | 1        | 2.38%   |
| Intel Genuine     | 1        | 2.38%   |
| Intel Core 2 Quad | 1        | 2.38%   |
| Intel Celeron     | 1        | 2.38%   |
| AMD Ryzen 9       | 1        | 2.38%   |
| AMD E1            | 1        | 2.38%   |
| AMD Athlon        | 1        | 2.38%   |
| AMD A8            | 1        | 2.38%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 16       | 38.1%   |
| 6      | 13       | 30.95%  |
| 8      | 6        | 14.29%  |
| 2      | 5        | 11.9%   |
| 16     | 1        | 2.38%   |
| 12     | 1        | 2.38%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 40       | 97.56%  |
| 2      | 1        | 2.44%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 27       | 65.85%  |
| 1      | 14       | 34.15%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 41       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 7        | 16.67%  |
| 0x506e3    | 5        | 11.9%   |
| 0x08701021 | 5        | 11.9%   |
| 0x906ea    | 4        | 9.52%   |
| 0x0a201016 | 3        | 7.14%   |
| 0x306c3    | 2        | 4.76%   |
| 0x306a9    | 2        | 4.76%   |
| 0x106e5    | 2        | 4.76%   |
| 0xa0653    | 1        | 2.38%   |
| 0x906ed    | 1        | 2.38%   |
| 0x906eb    | 1        | 2.38%   |
| 0x906e9    | 1        | 2.38%   |
| 0x306f2    | 1        | 2.38%   |
| 0x20655    | 1        | 2.38%   |
| 0x1067a    | 1        | 2.38%   |
| 0x0a20120a | 1        | 2.38%   |
| 0x08701013 | 1        | 2.38%   |
| 0x0810100b | 1        | 2.38%   |
| 0x0600611a | 1        | 2.38%   |
| 0x0500010d | 1        | 2.38%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| KabyLake      | 8        | 19.05%  |
| Zen 2         | 7        | 16.67%  |
| Skylake       | 5        | 11.9%   |
| Zen 3         | 4        | 9.52%   |
| Nehalem       | 3        | 7.14%   |
| Haswell       | 3        | 7.14%   |
| Zen+          | 2        | 4.76%   |
| IvyBridge     | 2        | 4.76%   |
| Zen           | 1        | 2.38%   |
| Westmere      | 1        | 2.38%   |
| SandyBridge   | 1        | 2.38%   |
| Penryn        | 1        | 2.38%   |
| Goldmont plus | 1        | 2.38%   |
| Excavator     | 1        | 2.38%   |
| CometLake     | 1        | 2.38%   |
| Bobcat        | 1        | 2.38%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 20       | 46.51%  |
| AMD               | 14       | 32.56%  |
| Intel             | 8        | 18.6%   |
| ASPEED Technology | 1        | 2.33%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia GP104 [GeForce GTX 1080]                                             | 3        | 6.82%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 3        | 6.82%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 2        | 4.55%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 4.55%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 4.55%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 2        | 4.55%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 2.27%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 2.27%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 2.27%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 2.27%   |
| Nvidia GT200 [GeForce GTX 260]                                              | 1        | 2.27%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 2.27%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 2.27%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 2.27%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 2.27%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 2.27%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 2.27%   |
| Nvidia GK107 [GeForce GT 740]                                               | 1        | 2.27%   |
| Nvidia GF106GL [Quadro 2000]                                                | 1        | 2.27%   |
| Nvidia GA102 [GeForce RTX 3080 Lite Hash Rate]                              | 1        | 2.27%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 2.27%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 2.27%   |
| Intel HD Graphics 530                                                       | 1        | 2.27%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1        | 2.27%   |
| Intel Core Processor Integrated Graphics Controller                         | 1        | 2.27%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 1        | 2.27%   |
| ASPEED Technology ASPEED Graphics Family                                    | 1        | 2.27%   |
| AMD Wrestler [Radeon HD 7310]                                               | 1        | 2.27%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 1        | 2.27%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 1        | 2.27%   |
| AMD Tonga PRO [Radeon R9 285/380]                                           | 1        | 2.27%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 1        | 2.27%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 1        | 2.27%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 1        | 2.27%   |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                            | 1        | 2.27%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 1        | 2.27%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 18       | 43.9%   |
| 1 x AMD         | 14       | 34.15%  |
| 1 x Intel       | 7        | 17.07%  |
| 2 x Nvidia      | 1        | 2.44%   |
| Nvidia + ASPEED | 1        | 2.44%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 25       | 60.98%  |
| Proprietary | 14       | 34.15%  |
| Unknown     | 2        | 4.88%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 14       | 34.15%  |
| 1.01-2.0   | 8        | 19.51%  |
| 7.01-8.0   | 7        | 17.07%  |
| 5.01-6.0   | 4        | 9.76%   |
| 8.01-16.0  | 3        | 7.32%   |
| 3.01-4.0   | 2        | 4.88%   |
| 0.01-0.5   | 2        | 4.88%   |
| 0.51-1.0   | 1        | 2.44%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 10       | 22.73%  |
| Ancor Communications | 5        | 11.36%  |
| Goldstar             | 4        | 9.09%   |
| AOC                  | 4        | 9.09%   |
| Acer                 | 4        | 9.09%   |
| Hewlett-Packard      | 3        | 6.82%   |
| Iiyama               | 2        | 4.55%   |
| MSI                  | 1        | 2.27%   |
| Lenovo               | 1        | 2.27%   |
| Konka                | 1        | 2.27%   |
| Kogan                | 1        | 2.27%   |
| KOC                  | 1        | 2.27%   |
| JRY                  | 1        | 2.27%   |
| Idek Iiyama          | 1        | 2.27%   |
| Hitachi              | 1        | 2.27%   |
| Gigabyte Technology  | 1        | 2.27%   |
| FOX                  | 1        | 2.27%   |
| Dell                 | 1        | 2.27%   |
| ASUSTek Computer     | 1        | 2.27%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch     | 2        | 4.26%   |
| Samsung Electronics SyncMaster SAM0524 1920x1080 480x270mm 21.7-inch  | 1        | 2.13%   |
| Samsung Electronics SyncMaster SAM02FE 1680x1050 433x271mm 20.1-inch  | 1        | 2.13%   |
| Samsung Electronics SMS24A350H SAM07D6 1920x1080 531x299mm 24.0-inch  | 1        | 2.13%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 600x340mm 27.2-inch     | 1        | 2.13%   |
| Samsung Electronics LCD Monitor SAM0B60 1920x1080 887x500mm 40.1-inch | 1        | 2.13%   |
| Samsung Electronics LCD Monitor SAM02EB 1920x540                      | 1        | 2.13%   |
| Samsung Electronics LC49G95T SAM7053 2560x1440 1193x336mm 48.8-inch   | 1        | 2.13%   |
| Samsung Electronics C27R50x SAM0F9E 1920x1080 598x336mm 27.0-inch     | 1        | 2.13%   |
| MSI G24C4 MSI3BA0 1920x1080 521x293mm 23.5-inch                       | 1        | 2.13%   |
| Lenovo LEN T24i-10 LEN61CE 1920x1080 527x296mm 23.8-inch              | 1        | 2.13%   |
| Konka TV MONIOR KOA0030 1920x540 708x398mm 32.0-inch                  | 1        | 2.13%   |
| Kogan KAMN34FXQULA KGN3400 3440x1440 797x334mm 34.0-inch              | 1        | 2.13%   |
| KOC SXGA85_ANALOG KOC0482 1280x1024 365x292mm 18.4-inch               | 1        | 2.13%   |
| JRY HDMI1 JRY2700 1920x1080 368x207mm 16.6-inch                       | 1        | 2.13%   |
| Iiyama PL3466WQ IVM761A 3440x1440 797x334mm 34.0-inch                 | 1        | 2.13%   |
| Iiyama PL2409HD IVM560C 1920x1080 521x293mm 23.5-inch                 | 1        | 2.13%   |
| Idek Iiyama LCD Monitor PL2760Q 2560x1440                             | 1        | 2.13%   |
| Hitachi HISENSE HEC002F 3840x2160 1095x616mm 49.5-inch                | 1        | 2.13%   |
| Hewlett-Packard Omni / Pro HWP4218 1600x900 443x249mm 20.0-inch       | 1        | 2.13%   |
| Hewlett-Packard E240c HWP327C 1920x1080 510x290mm 23.1-inch           | 1        | 2.13%   |
| Hewlett-Packard 27w HPN3494 1920x1080 598x336mm 27.0-inch             | 1        | 2.13%   |
| Goldstar ULTRAWIDE GSM76FA 2560x1080 531x298mm 24.0-inch              | 1        | 2.13%   |
| Goldstar ULTRAGEAR GSM5B7F 2560x1440 597x336mm 27.0-inch              | 1        | 2.13%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 1        | 2.13%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 1        | 2.13%   |
| Goldstar 22EN43 GSM59D8 1920x1080 477x268mm 21.5-inch                 | 1        | 2.13%   |
| Gigabyte Technology M27Q GBT270D 2560x1440 596x335mm 26.9-inch        | 1        | 2.13%   |
| FOX FBC TV FOX9C01 1366x768 698x393mm 31.5-inch                       | 1        | 2.13%   |
| Dell U3219Q DELA124 3840x2160 697x392mm 31.5-inch                     | 1        | 2.13%   |
| ASUSTek Computer VG279QM AUS278F 1920x1080 598x336mm 27.0-inch        | 1        | 2.13%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                   | 1        | 2.13%   |
| AOC Q2963 AOC2963 2560x1080 673x284mm 28.8-inch                       | 1        | 2.13%   |
| AOC Q2963 AOC2963 2560x1080 670x280mm 28.6-inch                       | 1        | 2.13%   |
| AOC Q27G2G3R3B AOC2702 2560x1440 600x340mm 27.2-inch                  | 1        | 2.13%   |
| AOC 2460G5 AOC246A 1920x1080 530x300mm 24.0-inch                      | 1        | 2.13%   |
| Ancor Communications VW246 ACI24F2 1920x1080 531x299mm 24.0-inch      | 1        | 2.13%   |
| Ancor Communications ROG PG348Q ACI3433 3440x1440 798x335mm 34.1-inch | 1        | 2.13%   |
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch | 1        | 2.13%   |
| Ancor Communications MX279 ACI27C3 1920x1080 598x336mm 27.0-inch      | 1        | 2.13%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 19       | 44.19%  |
| 2560x1440 (QHD)    | 7        | 16.28%  |
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
| 27      | 10       | 22.22%  |
| 34      | 6        | 13.33%  |
| 23      | 6        | 13.33%  |
| 21      | 5        | 11.11%  |
| 24      | 4        | 8.89%   |
| 31      | 3        | 6.67%   |
| 20      | 2        | 4.44%   |
| Unknown | 2        | 4.44%   |
| 84      | 1        | 2.22%   |
| 54      | 1        | 2.22%   |
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
| 501-600     | 19       | 43.18%  |
| 701-800     | 7        | 15.91%  |
| 401-500     | 7        | 15.91%  |
| 601-700     | 4        | 9.09%   |
| 1001-1500   | 3        | 6.82%   |
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
| 201-250        | 14       | 31.82%  |
| 351-500        | 10       | 22.73%  |
| 301-350        | 10       | 22.73%  |
| More than 1000 | 3        | 6.82%   |
| 151-200        | 3        | 6.82%   |
| Unknown        | 2        | 4.55%   |
| 251-300        | 1        | 2.27%   |
| 501-1000       | 1        | 2.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 22       | 55%     |
| 101-120 | 11       | 27.5%   |
| 1-50    | 3        | 7.5%    |
| Unknown | 2        | 5%      |
| 161-240 | 1        | 2.5%    |
| 121-160 | 1        | 2.5%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 30       | 71.43%  |
| 2     | 9        | 21.43%  |
| 0     | 3        | 7.14%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 25       | 41.67%  |
| Intel                           | 22       | 36.67%  |
| Broadcom                        | 3        | 5%      |
| Ralink Technology               | 2        | 3.33%   |
| Qualcomm Atheros                | 2        | 3.33%   |
| TP-Link                         | 1        | 1.67%   |
| Ralink                          | 1        | 1.67%   |
| Qualcomm Atheros Communications | 1        | 1.67%   |
| Qualcomm                        | 1        | 1.67%   |
| NetGear                         | 1        | 1.67%   |
| Microsoft                       | 1        | 1.67%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller         | 19       | 26.76%  |
| Intel I211 Gigabit Network Connection                                     | 6        | 8.45%   |
| Realtek RTL8125 2.5GbE Controller                                         | 5        | 7.04%   |
| Intel Wi-Fi 6 AX200                                                       | 5        | 7.04%   |
| Intel Ethernet Connection (2) I219-V                                      | 5        | 7.04%   |
| Intel Ethernet Connection (7) I219-V                                      | 2        | 2.82%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                          | 2        | 2.82%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                     | 2        | 2.82%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                           | 2        | 2.82%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                       | 1        | 1.41%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                        | 1        | 1.41%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                           | 1        | 1.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                  | 1        | 1.41%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                           | 1        | 1.41%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                     | 1        | 1.41%   |
| Ralink RT2501/RT2573 Wireless Adapter                                     | 1        | 1.41%   |
| Ralink MT7601U Wireless Adapter                                           | 1        | 1.41%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                    | 1        | 1.41%   |
| Qualcomm Redmi 9T                                                         | 1        | 1.41%   |
| Qualcomm Atheros AR9271 802.11n                                           | 1        | 1.41%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                          | 1        | 1.41%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)            | 1        | 1.41%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet            | 1        | 1.41%   |
| NetGear Nighthawk A7000 802.11ac Wireless Adapter AC1900 [Realtek 8814AU] | 1        | 1.41%   |
| Microsoft Xbox 360 Wireless Adapter                                       | 1        | 1.41%   |
| Intel Wireless-AC 9260                                                    | 1        | 1.41%   |
| Intel Wireless 7265                                                       | 1        | 1.41%   |
| Intel Ethernet Connection I217-LM                                         | 1        | 1.41%   |
| Intel Ethernet Connection (11) I219-V                                     | 1        | 1.41%   |
| Intel Cannon Lake PCH CNVi WiFi                                           | 1        | 1.41%   |
| Broadcom BCM43228 802.11a/b/g/n                                           | 1        | 1.41%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller       | 1        | 1.41%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 10       | 40%     |
| Realtek Semiconductor           | 4        | 16%     |
| Ralink Technology               | 2        | 8%      |
| Qualcomm Atheros                | 2        | 8%      |
| Broadcom                        | 2        | 8%      |
| TP-Link                         | 1        | 4%      |
| Ralink                          | 1        | 4%      |
| Qualcomm Atheros Communications | 1        | 4%      |
| NetGear                         | 1        | 4%      |
| Microsoft                       | 1        | 4%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                       | 5        | 20%     |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                          | 2        | 8%      |
| TP-Link Archer T2U PLUS [RTL8821AU]                                       | 1        | 4%      |
| Realtek RTL88x2bu [AC1200 Techkey]                                        | 1        | 4%      |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                           | 1        | 4%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                  | 1        | 4%      |
| Realtek RTL8192EE PCIe Wireless Network Adapter                           | 1        | 4%      |
| Ralink RT2501/RT2573 Wireless Adapter                                     | 1        | 4%      |
| Ralink MT7601U Wireless Adapter                                           | 1        | 4%      |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                    | 1        | 4%      |
| Qualcomm Atheros AR9271 802.11n                                           | 1        | 4%      |
| Qualcomm Atheros AR93xx Wireless Network Adapter                          | 1        | 4%      |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)            | 1        | 4%      |
| NetGear Nighthawk A7000 802.11ac Wireless Adapter AC1900 [Realtek 8814AU] | 1        | 4%      |
| Microsoft Xbox 360 Wireless Adapter                                       | 1        | 4%      |
| Intel Wireless-AC 9260                                                    | 1        | 4%      |
| Intel Wireless 7265                                                       | 1        | 4%      |
| Intel Cannon Lake PCH CNVi WiFi                                           | 1        | 4%      |
| Broadcom BCM43228 802.11a/b/g/n                                           | 1        | 4%      |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller       | 1        | 4%      |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 24       | 53.33%  |
| Intel                 | 17       | 37.78%  |
| Broadcom              | 2        | 4.44%   |
| Qualcomm Atheros      | 1        | 2.22%   |
| Qualcomm              | 1        | 2.22%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 19       | 41.3%   |
| Intel I211 Gigabit Network Connection                             | 6        | 13.04%  |
| Realtek RTL8125 2.5GbE Controller                                 | 5        | 10.87%  |
| Intel Ethernet Connection (2) I219-V                              | 5        | 10.87%  |
| Intel Ethernet Connection (7) I219-V                              | 2        | 4.35%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 4.35%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2        | 4.35%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 2.17%   |
| Qualcomm Redmi 9T                                                 | 1        | 2.17%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 2.17%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 2.17%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 2.17%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 41       | 63.08%  |
| WiFi     | 24       | 36.92%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 31       | 72.09%  |
| WiFi     | 12       | 27.91%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 21       | 51.22%  |
| 2     | 17       | 41.46%  |
| 3     | 3        | 7.32%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 32       | 76.19%  |
| Yes  | 10       | 23.81%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 10       | 45.45%  |
| Cambridge Silicon Radio | 6        | 27.27%  |
| Realtek Semiconductor   | 2        | 9.09%   |
| Broadcom                | 2        | 9.09%   |
| ASUSTek Computer        | 2        | 9.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6        | 27.27%  |
| Intel AX200 Bluetooth                               | 5        | 22.73%  |
| Intel Wireless-AC 3168 Bluetooth                    | 2        | 9.09%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1        | 4.55%   |
| Realtek Bluetooth Radio                             | 1        | 4.55%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 4.55%   |
| Intel Bluetooth wireless interface                  | 1        | 4.55%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 4.55%   |
| Broadcom HP Portable Bumble Bee                     | 1        | 4.55%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 4.55%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 4.55%   |
| ASUS Bluetooth Radio                                | 1        | 4.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 26       | 32.91%  |
| Nvidia                 | 19       | 24.05%  |
| AMD                    | 18       | 22.78%  |
| Corsair                | 3        | 3.8%    |
| C-Media Electronics    | 3        | 3.8%    |
| Razer USA              | 2        | 2.53%   |
| Kingston Technology    | 2        | 2.53%   |
| Tenx Technology        | 1        | 1.27%   |
| Plantronics            | 1        | 1.27%   |
| Logitech               | 1        | 1.27%   |
| Hewlett-Packard        | 1        | 1.27%   |
| Generalplus Technology | 1        | 1.27%   |
| Astro Gaming           | 1        | 1.27%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 9        | 9.89%   |
| Intel 200 Series PCH HD Audio                                              | 6        | 6.59%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4        | 4.4%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4        | 4.4%    |
| Nvidia TU106 High Definition Audio Controller                              | 3        | 3.3%    |
| Nvidia GP104 High Definition Audio Controller                              | 3        | 3.3%    |
| Intel Cannon Lake PCH cAVS                                                 | 3        | 3.3%    |
| AMD Navi 10 HDMI Audio                                                     | 3        | 3.3%    |
| Nvidia TU116 High Definition Audio Controller                              | 2        | 2.2%    |
| Nvidia GP106 High Definition Audio Controller                              | 2        | 2.2%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2        | 2.2%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2        | 2.2%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 2        | 2.2%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 2        | 2.2%    |
| Tenx Technology USB AUDIO                                                  | 1        | 1.1%    |
| Razer USA RZ04-0318 Gaming Headset [Kraken Ultimate]                       | 1        | 1.1%    |
| Razer USA Razer Kraken X USB                                               | 1        | 1.1%    |
| Plantronics C320-M                                                         | 1        | 1.1%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1        | 1.1%    |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 1.1%    |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 1.1%    |
| Nvidia GP102 HDMI Audio Controller                                         | 1        | 1.1%    |
| Nvidia GM206 High Definition Audio Controller                              | 1        | 1.1%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 1.1%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 1.1%    |
| Nvidia GK107 HDMI Audio Controller                                         | 1        | 1.1%    |
| Nvidia GF106 High Definition Audio Controller                              | 1        | 1.1%    |
| Nvidia GA102 High Definition Audio Controller                              | 1        | 1.1%    |
| Logitech G633 Gaming Headset                                               | 1        | 1.1%    |
| Kingston Technology HyperX Cloud Flight Wireless                           | 1        | 1.1%    |
| Kingston Technology HyperX 7.1 Audio                                       | 1        | 1.1%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1        | 1.1%    |
| Intel Comet Lake PCH cAVS                                                  | 1        | 1.1%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1        | 1.1%    |
| Intel C610/X99 series chipset HD Audio Controller                          | 1        | 1.1%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1        | 1.1%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1        | 1.1%    |
| Hewlett-Packard E240C                                                      | 1        | 1.1%    |
| Generalplus Technology USB Audio Device                                    | 1        | 1.1%    |
| Corsair VOID Wireless Gaming Dongle                                        | 1        | 1.1%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 9        | 21.95%  |
| G.Skill             | 6        | 14.63%  |
| SK hynix            | 5        | 12.2%   |
| Unknown             | 4        | 9.76%   |
| Samsung Electronics | 4        | 9.76%   |
| Kingston            | 3        | 7.32%   |
| Crucial             | 3        | 7.32%   |
| Team                | 2        | 4.88%   |
| Unifosa             | 1        | 2.44%   |
| Ramaxel Technology  | 1        | 2.44%   |
| PNY                 | 1        | 2.44%   |
| Micron Technology   | 1        | 2.44%   |
| A-DATA Technology   | 1        | 2.44%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s  | 2        | 4.26%   |
| Kingston RAM KHX2133C14/16G 16GB DIMM DDR4 2176MT/s     | 2        | 4.26%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s   | 2        | 4.26%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s               | 1        | 2.13%   |
| Unknown RAM Module 4GB DIMM DDR4 2133MT/s               | 1        | 2.13%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                | 1        | 2.13%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                | 1        | 2.13%   |
| Unifosa RAM GU512303EP0202 2GB DIMM DDR3 1333MT/s       | 1        | 2.13%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s      | 1        | 2.13%   |
| Team RAM TEAMGROUP-UD3-1600 8192MB DIMM DDR3 1600MT/s   | 1        | 2.13%   |
| SK hynix RAM HMT451U6AFR8C-PB 4096MB DIMM DDR3 1600MT/s | 1        | 2.13%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 1        | 2.13%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s    | 1        | 2.13%   |
| SK hynix RAM HMT351U6BFR8C-H9 4096MB DIMM 1450MT/s      | 1        | 2.13%   |
| SK hynix RAM HMA451R7MFR8N-TFTD 4GB DIMM DDR4 2133MT/s  | 1        | 2.13%   |
| SK hynix RAM HMA451R7MFR8N-TF 4GB DIMM DDR4 2133MT/s    | 1        | 2.13%   |
| Samsung RAM Module 8GB DIMM DDR4 2666MT/s               | 1        | 2.13%   |
| Samsung RAM Module 8GB DIMM DDR4 2133MT/s               | 1        | 2.13%   |
| Samsung RAM M393A5143DB0-CPB 4GB DIMM DDR4 2133MT/s     | 1        | 2.13%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM 1600MT/s          | 1        | 2.13%   |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM 1867MT/s          | 1        | 2.13%   |
| Ramaxel RAM RMUA5110MB78HAF-2400 8GB DIMM DDR4 2400MT/s | 1        | 2.13%   |
| PNY RAM 8GBF1X08QFHH36-135-K 8GB DIMM DDR4 2933MT/s     | 1        | 2.13%   |
| Micron RAM 16KTF1G64AZ-1G6E1 8GB DIMM DDR3 1600MT/s     | 1        | 2.13%   |
| Kingston RAM KHX3600C18D4/16GX 16GB DIMM DDR4 3600MT/s  | 1        | 2.13%   |
| Kingston RAM KHX3466C19D4/16G 16GB DIMM DDR4 3467MT/s   | 1        | 2.13%   |
| G.Skill RAM F4-3600C17-8GTZR 8GB DIMM DDR4 3600MT/s     | 1        | 2.13%   |
| G.Skill RAM F4-3600C16-8GTZNC 8GB DIMM DDR4 3800MT/s    | 1        | 2.13%   |
| G.Skill RAM F4-3600C16-16GTZRC 16GB DIMM DDR4 4400MT/s  | 1        | 2.13%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s  | 1        | 2.13%   |
| G.Skill RAM F4-3200C16-8GTZKW 8GB DIMM DDR4 3200MT/s    | 1        | 2.13%   |
| G.Skill RAM F4-3200C16-8GTZKO 8GB DIMM DDR4 3200MT/s    | 1        | 2.13%   |
| G.Skill RAM F4-2666C15-4GVR 4GB DIMM DDR4 2933MT/s      | 1        | 2.13%   |
| Crucial RAM CT4G4DFS824A.C8FHP 4GB DIMM DDR4 2400MT/s   | 1        | 2.13%   |
| Crucial RAM CT25664BD160B.C8FN 2GB DIMM DDR3 1333MT/s   | 1        | 2.13%   |
| Crucial RAM BL16G32C16U4R.M16FE 16GB DIMM DDR4 3200MT/s | 1        | 2.13%   |
| Corsair RAM CMW32GX4M2E3200C16 16GB DIMM DDR4 3200MT/s  | 1        | 2.13%   |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3200MT/s  | 1        | 2.13%   |
| Corsair RAM CMK8GX4M2A2666C16 4GB DIMM DDR4 2747MT/s    | 1        | 2.13%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s  | 1        | 2.13%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Desktops | Percent |
|-------|----------|---------|
| DDR4  | 25       | 69.44%  |
| DDR3  | 8        | 22.22%  |
| SDRAM | 1        | 2.78%   |
| DDR2  | 1        | 2.78%   |
| DDR   | 1        | 2.78%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 33       | 94.29%  |
| SODIMM | 2        | 5.71%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 14       | 35.9%   |
| 16384 | 11       | 28.21%  |
| 4096  | 11       | 28.21%  |
| 2048  | 3        | 7.69%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 6        | 15%     |
| 1600  | 5        | 12.5%   |
| 3600  | 4        | 10%     |
| 2933  | 3        | 7.5%    |
| 3400  | 2        | 5%      |
| 2400  | 2        | 5%      |
| 2176  | 2        | 5%      |
| 2133  | 2        | 5%      |
| 1800  | 2        | 5%      |
| 1333  | 2        | 5%      |
| 4400  | 1        | 2.5%    |
| 4133  | 1        | 2.5%    |
| 3800  | 1        | 2.5%    |
| 3467  | 1        | 2.5%    |
| 2747  | 1        | 2.5%    |
| 2667  | 1        | 2.5%    |
| 2666  | 1        | 2.5%    |
| 1867  | 1        | 2.5%    |
| 1450  | 1        | 2.5%    |
| 800   | 1        | 2.5%    |

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
| 0     | 33       | 80.49%  |
| 1     | 8        | 19.51%  |

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

