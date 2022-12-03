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

Total: 61

| Vendor        | Model                    | Probe                                                      | Date         |
|---------------|--------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | ROG STRIX B550-A GAMING  | [de8b7d8220](https://linux-hardware.org/?probe=de8b7d8220) | Nov 19, 2022 |
| ASUSTek       | PRIME X399-A             | [304c12788b](https://linux-hardware.org/?probe=304c12788b) | Oct 06, 2022 |
| HP            | 1825                     | [bceae72004](https://linux-hardware.org/?probe=bceae72004) | Aug 15, 2022 |
| MSI           | X99S MPOWER              | [a3c1523b6b](https://linux-hardware.org/?probe=a3c1523b6b) | Jul 27, 2022 |
| Dell          | 054KM3 A01               | [407b210bfe](https://linux-hardware.org/?probe=407b210bfe) | Jul 05, 2022 |
| HP            | 18E7                     | [2fd690b3b4](https://linux-hardware.org/?probe=2fd690b3b4) | Jun 22, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO   | [a698baa5f6](https://linux-hardware.org/?probe=a698baa5f6) | Jun 18, 2022 |
| Dell          | 0NC2VH A01               | [f05a6e7d31](https://linux-hardware.org/?probe=f05a6e7d31) | May 03, 2022 |
| ASRock        | B450M-HDV R4.0           | [bce1bba9ff](https://linux-hardware.org/?probe=bce1bba9ff) | Apr 29, 2022 |
| Dell          | 0D24M8 A01               | [fe4bb32aa1](https://linux-hardware.org/?probe=fe4bb32aa1) | Apr 14, 2022 |
| Dell          | 014GRG A00               | [1783efe96b](https://linux-hardware.org/?probe=1783efe96b) | Apr 14, 2022 |
| HP            | 1825                     | [a7ce5b6b11](https://linux-hardware.org/?probe=a7ce5b6b11) | Mar 03, 2022 |
| MSI           | B450M PRO-M2 MAX         | [3f99c8072a](https://linux-hardware.org/?probe=3f99c8072a) | Feb 23, 2022 |
| ASUSTek       | PRIME H510M-A            | [7ab68e0043](https://linux-hardware.org/?probe=7ab68e0043) | Feb 17, 2022 |
| ASRock        | B450M-HDV R4.0           | [f2a65b8a5f](https://linux-hardware.org/?probe=f2a65b8a5f) | Feb 14, 2022 |
| Gigabyte      | P55A-UD3                 | [824dbdd8ad](https://linux-hardware.org/?probe=824dbdd8ad) | Jan 22, 2022 |
| Online Lab... | SR 42                    | [e3037eb087](https://linux-hardware.org/?probe=e3037eb087) | Jan 22, 2022 |
| Gigabyte      | H310M S2H x.x            | [9e14e04f7f](https://linux-hardware.org/?probe=9e14e04f7f) | Jan 22, 2022 |
| ASRock        | B450M-HDV R4.0           | [8e7267692b](https://linux-hardware.org/?probe=8e7267692b) | Jan 21, 2022 |
| Gigabyte      | MZGLKBP-00               | [202ccac61c](https://linux-hardware.org/?probe=202ccac61c) | Dec 30, 2021 |
| Gigabyte      | B75M-D3V                 | [1c15b6b3c7](https://linux-hardware.org/?probe=1c15b6b3c7) | Dec 26, 2021 |
| HP            | 1495                     | [28835849f0](https://linux-hardware.org/?probe=28835849f0) | Oct 29, 2021 |
| ASUSTek       | PRIME Z490M-PLUS         | [5a7e6805d3](https://linux-hardware.org/?probe=5a7e6805d3) | Oct 02, 2021 |
| MSI           | B360M PRO-VD             | [06e625d98f](https://linux-hardware.org/?probe=06e625d98f) | Oct 02, 2021 |
| HP            | 1825                     | [ff75be1ea3](https://linux-hardware.org/?probe=ff75be1ea3) | Jun 06, 2021 |
| ASUSTek       | P5G41T-M LX2/BR          | [8702580cb4](https://linux-hardware.org/?probe=8702580cb4) | May 26, 2021 |
| ASUSTek       | P5G41T-M LX2/BR          | [05f1d12390](https://linux-hardware.org/?probe=05f1d12390) | May 26, 2021 |
| Gigabyte      | H170-HD3-CF              | [2ffdc89c2a](https://linux-hardware.org/?probe=2ffdc89c2a) | Apr 28, 2021 |
| Gigabyte      | Z390 GAMING SLI-CF       | [50f8ddb45c](https://linux-hardware.org/?probe=50f8ddb45c) | Apr 28, 2021 |
| Google        | Panther                  | [666794d603](https://linux-hardware.org/?probe=666794d603) | Apr 26, 2021 |
| ASUSTek       | F1A55-M LX               | [630bbb748a](https://linux-hardware.org/?probe=630bbb748a) | Apr 17, 2021 |
| Gigabyte      | H170-HD3-CF              | [f103eefd66](https://linux-hardware.org/?probe=f103eefd66) | Apr 17, 2021 |
| Gigabyte      | Z390 GAMING SLI-CF       | [e802fc9ff5](https://linux-hardware.org/?probe=e802fc9ff5) | Apr 17, 2021 |
| Sun Micros... | Ultra 24 50              | [e4b76f9137](https://linux-hardware.org/?probe=e4b76f9137) | Apr 10, 2021 |
| Sun Micros... | Ultra 24 50              | [15691fbc42](https://linux-hardware.org/?probe=15691fbc42) | Apr 10, 2021 |
| ASUSTek       | A8R-MVP                  | [6daa2a372c](https://linux-hardware.org/?probe=6daa2a372c) | Mar 27, 2021 |
| ASRock        | K8A780LM                 | [b8f4c7c2cb](https://linux-hardware.org/?probe=b8f4c7c2cb) | Mar 22, 2021 |
| Gigabyte      | 970A-DS3P                | [eeebc66137](https://linux-hardware.org/?probe=eeebc66137) | Mar 17, 2021 |
| Gigabyte      | 970A-DS3P                | [fdf4e6d366](https://linux-hardware.org/?probe=fdf4e6d366) | Mar 17, 2021 |
| ASRock        | K8A780LM                 | [d95a56d80f](https://linux-hardware.org/?probe=d95a56d80f) | Mar 15, 2021 |
| ASRock        | H81M-ITX                 | [0f5f41e1ca](https://linux-hardware.org/?probe=0f5f41e1ca) | Mar 08, 2021 |
| ASRock        | H81M-ITX                 | [8599b883d6](https://linux-hardware.org/?probe=8599b883d6) | Mar 08, 2021 |
| Intel         | D815EEA AAA45884-401     | [248565d49c](https://linux-hardware.org/?probe=248565d49c) | Feb 20, 2021 |
| Intel         | D815EEA AAA45884-401     | [3acc2f0b1e](https://linux-hardware.org/?probe=3acc2f0b1e) | Feb 20, 2021 |
| Gigabyte      | GA-G41M-ES2L             | [592c995804](https://linux-hardware.org/?probe=592c995804) | Jan 30, 2021 |
| Acer          | F672CR R01-A4            | [8d41694165](https://linux-hardware.org/?probe=8d41694165) | Jan 25, 2021 |
| Lenovo        | ThinkStation E20 4220CTO | [f963a2e7f9](https://linux-hardware.org/?probe=f963a2e7f9) | Jan 06, 2021 |
| Dell          | 0GXM1W A04               | [989f983b51](https://linux-hardware.org/?probe=989f983b51) | Dec 28, 2020 |
| Lenovo        | ThinkStation E20 4220CTO | [aac28ba905](https://linux-hardware.org/?probe=aac28ba905) | Dec 19, 2020 |
| Intel         | HURONRIVER               | [49bdd1a99d](https://linux-hardware.org/?probe=49bdd1a99d) | Oct 29, 2020 |
| ASUSTek       | Maximus V GENE           | [253b5aba98](https://linux-hardware.org/?probe=253b5aba98) | Oct 29, 2020 |
| ASUSTek       | H81M-C                   | [cd136e059e](https://linux-hardware.org/?probe=cd136e059e) | Oct 05, 2020 |
| HP            | 1791                     | [f41fcdc019](https://linux-hardware.org/?probe=f41fcdc019) | Sep 26, 2020 |
| ASUSTek       | EX-A320M-GAMING          | [4eb75f039b](https://linux-hardware.org/?probe=4eb75f039b) | Aug 17, 2020 |
| HP            | 1791                     | [5a21e91155](https://linux-hardware.org/?probe=5a21e91155) | Aug 15, 2020 |
| Gigabyte      | B450 AORUS ELITE         | [ff5143e508](https://linux-hardware.org/?probe=ff5143e508) | Aug 02, 2020 |
| ASUSTek       | P5PE-VM                  | [298c1239dd](https://linux-hardware.org/?probe=298c1239dd) | May 20, 2020 |
| MSI           | B350 PC MATE             | [ff3852f02d](https://linux-hardware.org/?probe=ff3852f02d) | Mar 23, 2020 |
| ASRock        | G31M-VS2                 | [b64547f948](https://linux-hardware.org/?probe=b64547f948) | Dec 06, 2019 |
| Gigabyte      | H170-HD3-CF              | [338994bd66](https://linux-hardware.org/?probe=338994bd66) | Dec 02, 2019 |
| ASUSTek       | P5PE-VM                  | [6a89046dfb](https://linux-hardware.org/?probe=6a89046dfb) | Dec 02, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| Devuan 4                | 18       | 37.5%   |
| Devuan 3                | 13       | 27.08%  |
| Devuan Testing/unstable | 7        | 14.58%  |
| Devuan 2.1              | 6        | 12.5%   |
| Devuan 5                | 3        | 6.25%   |
| Devuan 1.0.0            | 1        | 2.08%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Devuan | 45       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Desktops | Percent |
|----------------------|----------|---------|
| 5.10.0-9-amd64       | 6        | 12%     |
| 4.19.0-14-amd64      | 4        | 8%      |
| 4.19.0-16-amd64      | 3        | 6%      |
| 5.10.0-8-amd64       | 2        | 4%      |
| 5.10.0-6-amd64       | 2        | 4%      |
| 4.19.0-9-amd64       | 2        | 4%      |
| 4.19.0-13-amd64      | 2        | 4%      |
| 5.9.0-1-amd64        | 1        | 2%      |
| 5.8.0-3-amd64        | 1        | 2%      |
| 5.7.0-1-amd64        | 1        | 2%      |
| 5.7.0-0.bpo.2-amd64  | 1        | 2%      |
| 5.18.14-devuan       | 1        | 2%      |
| 5.18.0-1-amd64       | 1        | 2%      |
| 5.16.0-1-amd64       | 1        | 2%      |
| 5.15.0-2-amd64       | 1        | 2%      |
| 5.15.0-0.bpo.2-amd64 | 1        | 2%      |
| 5.14.0-kali2-amd64   | 1        | 2%      |
| 5.10.0-5-amd64       | 1        | 2%      |
| 5.10.0-2-amd64       | 1        | 2%      |
| 5.10.0-19-amd64      | 1        | 2%      |
| 5.10.0-18-amd64      | 1        | 2%      |
| 5.10.0-16-amd64      | 1        | 2%      |
| 5.10.0-15-amd64      | 1        | 2%      |
| 5.10.0-11-amd64      | 1        | 2%      |
| 5.10.0-10-amd64      | 1        | 2%      |
| 4.9.0-15-amd64       | 1        | 2%      |
| 4.9.0-14-686-pae     | 1        | 2%      |
| 4.9.0-14-686         | 1        | 2%      |
| 4.9.0-11-686-pae     | 1        | 2%      |
| 4.19.112             | 1        | 2%      |
| 4.19.0-20-amd64      | 1        | 2%      |
| 4.19.0-12-amd64      | 1        | 2%      |
| 4.19.0-10-amd64      | 1        | 2%      |
| 4.19.0-1-amd64       | 1        | 2%      |
| 4.19.0-0.bpo.6-amd64 | 1        | 2%      |
| 4.18.0-0.bpo.1-amd64 | 1        | 2%      |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.10.0   | 17       | 36.17%  |
| 4.19.0   | 14       | 29.79%  |
| 4.9.0    | 4        | 8.51%   |
| 5.7.0    | 2        | 4.26%   |
| 5.15.0   | 2        | 4.26%   |
| 5.9.0    | 1        | 2.13%   |
| 5.8.0    | 1        | 2.13%   |
| 5.18.14  | 1        | 2.13%   |
| 5.18.0   | 1        | 2.13%   |
| 5.16.0   | 1        | 2.13%   |
| 5.14.0   | 1        | 2.13%   |
| 4.19.112 | 1        | 2.13%   |
| 4.18.0   | 1        | 2.13%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 17       | 36.17%  |
| 4.19    | 15       | 31.91%  |
| 4.9     | 4        | 8.51%   |
| 5.7     | 2        | 4.26%   |
| 5.18    | 2        | 4.26%   |
| 5.15    | 2        | 4.26%   |
| 5.9     | 1        | 2.13%   |
| 5.8     | 1        | 2.13%   |
| 5.16    | 1        | 2.13%   |
| 5.14    | 1        | 2.13%   |
| 4.18    | 1        | 2.13%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 42       | 93.33%  |
| i686   | 3        | 6.67%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| XFCE       | 22       | 45.83%  |
| Unknown    | 10       | 20.83%  |
| MATE       | 6        | 12.5%   |
| KDE5       | 4        | 8.33%   |
| LXDE       | 2        | 4.17%   |
| X-Cinnamon | 1        | 2.08%   |
| i3         | 1        | 2.08%   |
| Cinnamon   | 1        | 2.08%   |
| awesome    | 1        | 2.08%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 39       | 84.78%  |
| Tty     | 6        | 13.04%  |
| Unknown | 1        | 2.17%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SLiM    | 23       | 51.11%  |
| Unknown | 10       | 22.22%  |
| LightDM | 9        | 20%     |
| XDM     | 1        | 2.22%   |
| SDDM    | 1        | 2.22%   |
| NODM    | 1        | 2.22%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 13       | 28.26%  |
| en_GB   | 5        | 10.87%  |
| fr_FR   | 4        | 8.7%    |
| C       | 4        | 8.7%    |
| Unknown | 4        | 8.7%    |
| sk_SK   | 3        | 6.52%   |
| en_AU   | 3        | 6.52%   |
| ru_RU   | 2        | 4.35%   |
| pt_BR   | 2        | 4.35%   |
| fr_BE   | 2        | 4.35%   |
| en_NZ   | 2        | 4.35%   |
| pl_PL   | 1        | 2.17%   |
| en_CA   | 1        | 2.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 29       | 64.44%  |
| EFI  | 16       | 35.56%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 41       | 91.11%  |
| Overlay | 2        | 4.44%   |
| Ext3    | 1        | 2.22%   |
| Unknown | 1        | 2.22%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 25       | 52.08%  |
| MBR     | 20       | 41.67%  |
| Unknown | 3        | 6.25%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 29       | 61.7%   |
| Yes       | 18       | 38.3%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 34       | 75.56%  |
| Yes       | 11       | 24.44%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 11       | 24.44%  |
| Gigabyte Technology | 10       | 22.22%  |
| Dell                | 5        | 11.11%  |
| MSI                 | 4        | 8.89%   |
| Hewlett-Packard     | 4        | 8.89%   |
| ASRock              | 4        | 8.89%   |
| Intel               | 2        | 4.44%   |
| Sun Microsystems    | 1        | 2.22%   |
| Online Labs         | 1        | 2.22%   |
| Lenovo              | 1        | 2.22%   |
| Google              | 1        | 2.22%   |
| Acer                | 1        | 2.22%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| Sun Microsystems Ultra 24       | 1        | 2.22%   |
| Online Labs SR                  | 1        | 2.22%   |
| MSI MS-7B84                     | 1        | 2.22%   |
| MSI MS-7B53                     | 1        | 2.22%   |
| MSI MS-7A34                     | 1        | 2.22%   |
| MSI MS-7885                     | 1        | 2.22%   |
| Lenovo ThinkStation E20 4220CTO | 1        | 2.22%   |
| Intel D815EEA AAA45884-401      | 1        | 2.22%   |
| Intel AHV                       | 1        | 2.22%   |
| HP Z220 SFF Workstation         | 1        | 2.22%   |
| HP ProDesk 600 G1 SFF           | 1        | 2.22%   |
| HP EliteDesk 800 G1 DM          | 1        | 2.22%   |
| HP Compaq 8200 Elite SFF PC     | 1        | 2.22%   |
| Google Panther                  | 1        | 2.22%   |
| Gigabyte Z390 GAMING SLI        | 1        | 2.22%   |
| Gigabyte P55A-UD3               | 1        | 2.22%   |
| Gigabyte MZGLKBP-00             | 1        | 2.22%   |
| Gigabyte H310M S2H 2.0          | 1        | 2.22%   |
| Gigabyte H170-HD3-CF            | 1        | 2.22%   |
| Gigabyte H170-HD3               | 1        | 2.22%   |
| Gigabyte GA-G41M-ES2L           | 1        | 2.22%   |
| Gigabyte B75M-D3V               | 1        | 2.22%   |
| Gigabyte B450 AORUS ELITE       | 1        | 2.22%   |
| Gigabyte 970A-DS3P              | 1        | 2.22%   |
| Dell Vostro 430                 | 1        | 2.22%   |
| Dell OptiPlex 9020              | 1        | 2.22%   |
| Dell OptiPlex 7060              | 1        | 2.22%   |
| Dell OptiPlex 7050              | 1        | 2.22%   |
| Dell OptiPlex 7010              | 1        | 2.22%   |
| ASUS ROG STRIX B550-A GAMING    | 1        | 2.22%   |
| ASUS ROG CROSSHAIR VII HERO     | 1        | 2.22%   |
| ASUS PRIME Z490M-PLUS           | 1        | 2.22%   |
| ASUS PRIME X399-A               | 1        | 2.22%   |
| ASUS PRIME H510M-A              | 1        | 2.22%   |
| ASUS P5PE-VM                    | 1        | 2.22%   |
| ASUS P5G41T-M LX2/BR            | 1        | 2.22%   |
| ASUS Maximus V GENE             | 1        | 2.22%   |
| ASUS F1A55-M LX                 | 1        | 2.22%   |
| ASUS EX-A320M-GAMING            | 1        | 2.22%   |
| ASUS All Series                 | 1        | 2.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 4        | 8.89%   |
| ASUS PRIME             | 3        | 6.67%   |
| ASUS ROG               | 2        | 4.44%   |
| Sun Microsystems Ultra | 1        | 2.22%   |
| Online Labs SR         | 1        | 2.22%   |
| MSI MS-7B84            | 1        | 2.22%   |
| MSI MS-7B53            | 1        | 2.22%   |
| MSI MS-7A34            | 1        | 2.22%   |
| MSI MS-7885            | 1        | 2.22%   |
| Lenovo ThinkStation    | 1        | 2.22%   |
| Intel D815EEA          | 1        | 2.22%   |
| Intel AHV              | 1        | 2.22%   |
| HP Z220                | 1        | 2.22%   |
| HP ProDesk             | 1        | 2.22%   |
| HP EliteDesk           | 1        | 2.22%   |
| HP Compaq              | 1        | 2.22%   |
| Google Panther         | 1        | 2.22%   |
| Gigabyte Z390          | 1        | 2.22%   |
| Gigabyte P55A-UD3      | 1        | 2.22%   |
| Gigabyte MZGLKBP-00    | 1        | 2.22%   |
| Gigabyte H310M         | 1        | 2.22%   |
| Gigabyte H170-HD3-CF   | 1        | 2.22%   |
| Gigabyte H170-HD3      | 1        | 2.22%   |
| Gigabyte GA-G41M-ES2L  | 1        | 2.22%   |
| Gigabyte B75M-D3V      | 1        | 2.22%   |
| Gigabyte B450          | 1        | 2.22%   |
| Gigabyte 970A-DS3P     | 1        | 2.22%   |
| Dell Vostro            | 1        | 2.22%   |
| ASUS P5PE-VM           | 1        | 2.22%   |
| ASUS P5G41T-M          | 1        | 2.22%   |
| ASUS Maximus           | 1        | 2.22%   |
| ASUS F1A55-M           | 1        | 2.22%   |
| ASUS EX-A320M-GAMING   | 1        | 2.22%   |
| ASUS All               | 1        | 2.22%   |
| ASRock K8A780LM        | 1        | 2.22%   |
| ASRock H81M-ITX        | 1        | 2.22%   |
| ASRock G31M-VS2        | 1        | 2.22%   |
| ASRock B450M-HDV       | 1        | 2.22%   |
| Acer Aspire            | 1        | 2.22%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 9        | 20%     |
| 2013 | 5        | 11.11%  |
| 2017 | 4        | 8.89%   |
| 2012 | 4        | 8.89%   |
| 2019 | 3        | 6.67%   |
| 2014 | 3        | 6.67%   |
| 2011 | 3        | 6.67%   |
| 2010 | 3        | 6.67%   |
| 2020 | 2        | 4.44%   |
| 2009 | 2        | 4.44%   |
| 2021 | 1        | 2.22%   |
| 2016 | 1        | 2.22%   |
| 2015 | 1        | 2.22%   |
| 2008 | 1        | 2.22%   |
| 2007 | 1        | 2.22%   |
| 2006 | 1        | 2.22%   |
| 2000 | 1        | 2.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 45       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 45       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 43       | 95.56%  |
| Yes  | 2        | 4.44%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 11       | 24.44%  |
| 8.01-16.0   | 11       | 24.44%  |
| 32.01-64.0  | 9        | 20%     |
| 4.01-8.0    | 7        | 15.56%  |
| 1.01-2.0    | 3        | 6.67%   |
| 3.01-4.0    | 2        | 4.44%   |
| 64.01-256.0 | 1        | 2.22%   |
| 0.01-0.5    | 1        | 2.22%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 15       | 31.25%  |
| 4.01-8.0  | 9        | 18.75%  |
| 2.01-3.0  | 8        | 16.67%  |
| 0.51-1.0  | 7        | 14.58%  |
| 3.01-4.0  | 4        | 8.33%   |
| 8.01-16.0 | 3        | 6.25%   |
| 0.01-0.5  | 2        | 4.17%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 19       | 42.22%  |
| 3      | 8        | 17.78%  |
| 2      | 7        | 15.56%  |
| 4      | 5        | 11.11%  |
| 5      | 4        | 8.89%   |
| 6      | 2        | 4.44%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 29       | 64.44%  |
| Yes       | 16       | 35.56%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 44       | 97.78%  |
| No        | 1        | 2.22%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 37       | 80.43%  |
| Yes       | 9        | 19.57%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 40       | 88.89%  |
| Yes       | 5        | 11.11%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| France      | 6        | 13.33%  |
| USA         | 5        | 11.11%  |
| Russia      | 4        | 8.89%   |
| Ukraine     | 3        | 6.67%   |
| UK          | 3        | 6.67%   |
| Slovakia    | 3        | 6.67%   |
| Australia   | 3        | 6.67%   |
| Poland      | 2        | 4.44%   |
| New Zealand | 2        | 4.44%   |
| Netherlands | 2        | 4.44%   |
| Brazil      | 2        | 4.44%   |
| Belgium     | 2        | 4.44%   |
| Argentina   | 2        | 4.44%   |
| South Korea | 1        | 2.22%   |
| Puerto Rico | 1        | 2.22%   |
| Israel      | 1        | 2.22%   |
| Germany     | 1        | 2.22%   |
| Canada      | 1        | 2.22%   |
| Bulgaria    | 1        | 2.22%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Bratislava     | 3        | 6.67%   |
| Bagnolet       | 3        | 6.67%   |
| Volzhskiy      | 2        | 4.44%   |
| Sydney         | 2        | 4.44%   |
| Auckland       | 2        | 4.44%   |
| Wroclaw        | 1        | 2.22%   |
| Vladikavkaz    | 1        | 2.22%   |
| Vise           | 1        | 2.22%   |
| Toronto        | 1        | 2.22%   |
| Tel Aviv       | 1        | 2.22%   |
| Sofia          | 1        | 2.22%   |
| Seongbuk-gu    | 1        | 2.22%   |
| Sao Paulo      | 1        | 2.22%   |
| Saint-Herblain | 1        | 2.22%   |
| Rio de Janeiro | 1        | 2.22%   |
| Renkum         | 1        | 2.22%   |
| Poperinge      | 1        | 2.22%   |
| Paris          | 1        | 2.22%   |
| Oleksandriya   | 1        | 2.22%   |
| Okehampton     | 1        | 2.22%   |
| Norman         | 1        | 2.22%   |
| Nérac         | 1        | 2.22%   |
| Miedziana Gora | 1        | 2.22%   |
| Miami          | 1        | 2.22%   |
| Loosdrecht     | 1        | 2.22%   |
| Leeds          | 1        | 2.22%   |
| Kirov          | 1        | 2.22%   |
| Karlsruhe      | 1        | 2.22%   |
| Holt           | 1        | 2.22%   |
| Hollywood      | 1        | 2.22%   |
| Great Bend     | 1        | 2.22%   |
| Donetsk        | 1        | 2.22%   |
| Dnipro         | 1        | 2.22%   |
| Cipolletti     | 1        | 2.22%   |
| Carlisle       | 1        | 2.22%   |
| Caguas         | 1        | 2.22%   |
| Buenos Aires   | 1        | 2.22%   |
| Brisbane       | 1        | 2.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 20       | 37     | 23.81%  |
| Seagate             | 17       | 25     | 20.24%  |
| Kingston            | 9        | 12     | 10.71%  |
| Toshiba             | 6        | 6      | 7.14%   |
| Samsung Electronics | 5        | 8      | 5.95%   |
| Crucial             | 4        | 6      | 4.76%   |
| Netac               | 2        | 2      | 2.38%   |
| Micron Technology   | 2        | 2      | 2.38%   |
| Maxtor              | 2        | 2      | 2.38%   |
| Dogfish             | 2        | 2      | 2.38%   |
| A-DATA Technology   | 2        | 2      | 2.38%   |
| WD MediaMax         | 1        | 3      | 1.19%   |
| Transcend           | 1        | 2      | 1.19%   |
| Team                | 1        | 1      | 1.19%   |
| SK hynix            | 1        | 1      | 1.19%   |
| SanDisk             | 1        | 1      | 1.19%   |
| KingDian            | 1        | 1      | 1.19%   |
| Intenso             | 1        | 1      | 1.19%   |
| IBM/Hitachi         | 1        | 1      | 1.19%   |
| Hitachi             | 1        | 1      | 1.19%   |
| HGST                | 1        | 1      | 1.19%   |
| Hewlett-Packard     | 1        | 2      | 1.19%   |
| GOODRAM             | 1        | 1      | 1.19%   |
| Fujitsu             | 1        | 1      | 1.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Kingston SA400S37120G 120GB SSD  | 3        | 2.97%   |
| Kingston SA2000M8250G 250GB      | 3        | 2.97%   |
| WDC WD10EZEX-08WN4A0 1TB         | 2        | 1.98%   |
| WDC WD10EARX-00N0YB0 1TB         | 2        | 1.98%   |
| Seagate ST3500418AS 500GB        | 2        | 1.98%   |
| Seagate ST2000DX002-2DV164 2TB   | 2        | 1.98%   |
| Samsung SSD 860 EVO 250GB        | 2        | 1.98%   |
| WDC WDS500G3X0C-00SJG0 500GB     | 1        | 0.99%   |
| WDC WDS480G2G0A-00JH30 480GB SSD | 1        | 0.99%   |
| WDC WDS120G2G0A-00JH30 120GB SSD | 1        | 0.99%   |
| WDC WD800BB-00JHC0 80GB          | 1        | 0.99%   |
| WDC WD5001AALS-00L3B2 500GB      | 1        | 0.99%   |
| WDC WD5001AALS-00E3A0 500GB      | 1        | 0.99%   |
| WDC WD5000LPVX-00V0TT0 500GB     | 1        | 0.99%   |
| WDC WD5000BPVT-24HXZT3 500GB     | 1        | 0.99%   |
| WDC WD5000AZLX-75K2TA0 500GB     | 1        | 0.99%   |
| WDC WD40EFRX-68WT0N0 4TB         | 1        | 0.99%   |
| WDC WD40EDAZ-11SLVB0 4TB         | 1        | 0.99%   |
| WDC WD20PURZ-85GU6Y0 2TB         | 1        | 0.99%   |
| WDC WD20EZRX-00DC0B0 2TB         | 1        | 0.99%   |
| WDC WD20EZRX-00D8PB0 2TB         | 1        | 0.99%   |
| WDC WD20EFRX-68EUZN0 2TB         | 1        | 0.99%   |
| WDC WD1200JS-55NCB1 120GB        | 1        | 0.99%   |
| WDC WD10SPZX-22Z10T1 1TB         | 1        | 0.99%   |
| WDC WD10JFCX-68N6GN0 1TB         | 1        | 0.99%   |
| WDC WD10EZRX-00D8PB0 1TB         | 1        | 0.99%   |
| WDC WD10EZEX-75M2NA0 1TB         | 1        | 0.99%   |
| WDC WD10EZEX-22MFCA0 1TB         | 1        | 0.99%   |
| WDC WD10EZEX-22BN5A0 1TB         | 1        | 0.99%   |
| WDC WD10EZEX-00BN5A0 1TB         | 1        | 0.99%   |
| WDC WD10EZEX-00BBHA0 1TB         | 1        | 0.99%   |
| WDC WD10EURX-63FH1Y0 1TB         | 1        | 0.99%   |
| WD MediaMax WL500GSA3272 500GB   | 1        | 0.99%   |
| Transcend TS128GSSD370S 128GB    | 1        | 0.99%   |
| Toshiba MQ04ABF100 1TB           | 1        | 0.99%   |
| Toshiba MQ02ABF100 1TB           | 1        | 0.99%   |
| Toshiba KXG60ZNV512G NVMe 512GB  | 1        | 0.99%   |
| Toshiba KXG50ZNV512G 512GB       | 1        | 0.99%   |
| Toshiba HDWD110 1TB              | 1        | 0.99%   |
| Toshiba DT01ACA100 1TB           | 1        | 0.99%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 18       | 34     | 38.3%   |
| Seagate             | 17       | 25     | 36.17%  |
| Toshiba             | 4        | 4      | 8.51%   |
| Maxtor              | 2        | 2      | 4.26%   |
| Samsung Electronics | 1        | 1      | 2.13%   |
| IBM/Hitachi         | 1        | 1      | 2.13%   |
| Hitachi             | 1        | 1      | 2.13%   |
| HGST                | 1        | 1      | 2.13%   |
| Hewlett-Packard     | 1        | 2      | 2.13%   |
| Fujitsu             | 1        | 1      | 2.13%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 6        | 8      | 20.69%  |
| Samsung Electronics | 5        | 6      | 17.24%  |
| WDC                 | 2        | 2      | 6.9%    |
| Netac               | 2        | 2      | 6.9%    |
| Micron Technology   | 2        | 2      | 6.9%    |
| Dogfish             | 2        | 2      | 6.9%    |
| Crucial             | 2        | 3      | 6.9%    |
| A-DATA Technology   | 2        | 2      | 6.9%    |
| Transcend           | 1        | 2      | 3.45%   |
| Team                | 1        | 1      | 3.45%   |
| SK hynix            | 1        | 1      | 3.45%   |
| KingDian            | 1        | 1      | 3.45%   |
| Intenso             | 1        | 1      | 3.45%   |
| GOODRAM             | 1        | 1      | 3.45%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 35       | 72     | 50%     |
| SSD     | 25       | 34     | 35.71%  |
| NVMe    | 9        | 12     | 12.86%  |
| Unknown | 1        | 3      | 1.43%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 44       | 103    | 78.57%  |
| NVMe | 9        | 12     | 16.07%  |
| SAS  | 3        | 6      | 5.36%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 32       | 53     | 51.61%  |
| 0.51-1.0   | 18       | 36     | 29.03%  |
| 1.01-2.0   | 7        | 12     | 11.29%  |
| 3.01-4.0   | 4        | 4      | 6.45%   |
| 4.01-10.0  | 1        | 1      | 1.61%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1001-2000      | 11       | 22.92%  |
| 251-500        | 9        | 18.75%  |
| 501-1000       | 8        | 16.67%  |
| 101-250        | 6        | 12.5%   |
| More than 3000 | 5        | 10.42%  |
| 21-50          | 3        | 6.25%   |
| 51-100         | 3        | 6.25%   |
| Unknown        | 2        | 4.17%   |
| 1-20           | 1        | 2.08%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 15       | 31.91%  |
| 1-20           | 9        | 19.15%  |
| 21-50          | 6        | 12.77%  |
| 501-1000       | 5        | 10.64%  |
| 1001-2000      | 4        | 8.51%   |
| More than 3000 | 2        | 4.26%   |
| 251-500        | 2        | 4.26%   |
| Unknown        | 2        | 4.26%   |
| 2001-3000      | 1        | 2.13%   |
| 51-100         | 1        | 2.13%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD5000LPVX-00V0TT0 500GB      | 1        | 1      | 7.69%   |
| WDC WD5000BPVT-24HXZT3 500GB      | 1        | 1      | 7.69%   |
| WDC WD10EARX-00N0YB0 1TB          | 1        | 1      | 7.69%   |
| Toshiba MQ04ABF100 1TB            | 1        | 1      | 7.69%   |
| Toshiba MQ02ABF100 1TB            | 1        | 1      | 7.69%   |
| SK hynix SH920 mSATA 128GB SSD    | 1        | 1      | 7.69%   |
| Seagate ST3500418AS 500GB         | 1        | 1      | 7.69%   |
| Maxtor 6E040L0 41GB               | 1        | 1      | 7.69%   |
| Kingston SA400S37120G 120GB SSD   | 1        | 1      | 7.69%   |
| Hitachi HDS721616PLA380 164GB     | 1        | 1      | 7.69%   |
| HGST HTE721010A9E630 1TB          | 1        | 1      | 7.69%   |
| Hewlett-Packard VB0250EAVER 250GB | 1        | 2      | 7.69%   |
| Fujitsu MHV2060BH PL 64GB         | 1        | 1      | 7.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor          | Desktops | Drives | Percent |
|-----------------|----------|--------|---------|
| WDC             | 3        | 3      | 23.08%  |
| Toshiba         | 2        | 2      | 15.38%  |
| SK hynix        | 1        | 1      | 7.69%   |
| Seagate         | 1        | 1      | 7.69%   |
| Maxtor          | 1        | 1      | 7.69%   |
| Kingston        | 1        | 1      | 7.69%   |
| Hitachi         | 1        | 1      | 7.69%   |
| HGST            | 1        | 1      | 7.69%   |
| Hewlett-Packard | 1        | 2      | 7.69%   |
| Fujitsu         | 1        | 1      | 7.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor          | Desktops | Drives | Percent |
|-----------------|----------|--------|---------|
| WDC             | 3        | 3      | 27.27%  |
| Toshiba         | 2        | 2      | 18.18%  |
| Seagate         | 1        | 1      | 9.09%   |
| Maxtor          | 1        | 1      | 9.09%   |
| Hitachi         | 1        | 1      | 9.09%   |
| HGST            | 1        | 1      | 9.09%   |
| Hewlett-Packard | 1        | 2      | 9.09%   |
| Fujitsu         | 1        | 1      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 11       | 12     | 84.62%  |
| SSD  | 2        | 2      | 15.38%  |

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
| Works    | 33       | 82     | 58.93%  |
| Malfunc  | 12       | 14     | 21.43%  |
| Detected | 11       | 25     | 19.64%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 33       | 52.38%  |
| AMD                              | 11       | 17.46%  |
| Kingston Technology Company      | 4        | 6.35%   |
| Toshiba America Info Systems     | 2        | 3.17%   |
| SanDisk                          | 2        | 3.17%   |
| Micron/Crucial Technology        | 2        | 3.17%   |
| Marvell Technology Group         | 2        | 3.17%   |
| Silicon Integrated Systems [SiS] | 1        | 1.59%   |
| Samsung Electronics              | 1        | 1.59%   |
| Integrated Technology Express    | 1        | 1.59%   |
| Chelsio Communications           | 1        | 1.59%   |
| Broadcom / LSI                   | 1        | 1.59%   |
| ASMedia Technology               | 1        | 1.59%   |
| Adaptec                          | 1        | 1.59%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 7        | 9.09%   |
| Kingston Company A2000 NVMe SSD                                                | 4        | 5.19%   |
| Intel SATA Controller [RAID mode]                                              | 4        | 5.19%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4        | 5.19%   |
| AMD 400 Series Chipset SATA Controller                                         | 4        | 5.19%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 3        | 3.9%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 3        | 3.9%    |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 3        | 3.9%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 3        | 3.9%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3        | 3.9%    |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 2        | 2.6%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2        | 2.6%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1        | 1.3%    |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 1        | 1.3%    |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 1        | 1.3%    |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 1        | 1.3%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1        | 1.3%    |
| SanDisk Non-Volatile memory controller                                         | 1        | 1.3%    |
| Samsung NVMe SSD Controller 980                                                | 1        | 1.3%    |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller               | 1        | 1.3%    |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller                        | 1        | 1.3%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1        | 1.3%    |
| Intel Comet Lake SATA AHCI Controller                                          | 1        | 1.3%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1        | 1.3%    |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 1        | 1.3%    |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 1        | 1.3%    |
| Intel Atom processor C2000 AHCI SATA3 Controller                               | 1        | 1.3%    |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]           | 1        | 1.3%    |
| Intel 82801EB/ER (ICH5/ICH5R) IDE Controller                                   | 1        | 1.3%    |
| Intel 82801BA IDE U100 Controller                                              | 1        | 1.3%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 1        | 1.3%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1        | 1.3%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 1        | 1.3%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 1        | 1.3%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 1        | 1.3%    |
| Integrated Express IT8213 IDE Controller                                       | 1        | 1.3%    |
| Chelsio T420-SO Unified Wire Storage Controller                                | 1        | 1.3%    |
| Broadcom / LSI SAS1068E PCI-Express Fusion-MPT SAS                             | 1        | 1.3%    |
| ASMedia ASM1062 Serial ATA Controller                                          | 1        | 1.3%    |
| AMD X399 Series Chipset SATA Controller                                        | 1        | 1.3%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 35       | 59.32%  |
| NVMe | 9        | 15.25%  |
| IDE  | 9        | 15.25%  |
| RAID | 4        | 6.78%   |
| SCSI | 2        | 3.39%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 34       | 75.56%  |
| AMD    | 11       | 24.44%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel Core i5-9400F CPU @ 2.90GHz              | 2        | 4.35%   |
| Intel Core i5-6400 CPU @ 2.70GHz               | 2        | 4.35%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz           | 2        | 4.35%   |
| AMD Ryzen 5 1600 Six-Core Processor            | 2        | 4.35%   |
| Intel Xeon CPU X3460 @ 2.80GHz                 | 1        | 2.17%   |
| Intel Xeon CPU E3-1270 V2 @ 3.50GHz            | 1        | 2.17%   |
| Intel Xeon CPU E3-1226 v3 @ 3.30GHz            | 1        | 2.17%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz       | 1        | 2.17%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz         | 1        | 2.17%   |
| Intel Pentium Dual-Core CPU E6300 @ 2.80GHz    | 1        | 2.17%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz         | 1        | 2.17%   |
| Intel Pentium CPU G3240 @ 3.10GHz              | 1        | 2.17%   |
| Intel Pentium 4 CPU 3.00GHz                    | 1        | 2.17%   |
| Intel Core i9-10850K CPU @ 3.60GHz             | 1        | 2.17%   |
| Intel Core i7-8700 CPU @ 3.20GHz               | 1        | 2.17%   |
| Intel Core i7-5930K CPU @ 3.50GHz              | 1        | 2.17%   |
| Intel Core i7-4600U CPU @ 2.10GHz              | 1        | 2.17%   |
| Intel Core i7-3770 CPU @ 3.40GHz               | 1        | 2.17%   |
| Intel Core i7 CPU 860 @ 2.80GHz                | 1        | 2.17%   |
| Intel Core i5-7500T CPU @ 2.70GHz              | 1        | 2.17%   |
| Intel Core i5-4590T CPU @ 2.00GHz              | 1        | 2.17%   |
| Intel Core i5-4570S CPU @ 2.90GHz              | 1        | 2.17%   |
| Intel Core i5-3470 CPU @ 3.20GHz               | 1        | 2.17%   |
| Intel Core i5-2500K CPU @ 3.30GHz              | 1        | 2.17%   |
| Intel Core i5-2500 CPU @ 3.30GHz               | 1        | 2.17%   |
| Intel Core i5-2410M CPU @ 2.30GHz              | 1        | 2.17%   |
| Intel Core i5-10400 CPU @ 2.90GHz              | 1        | 2.17%   |
| Intel Core i5 CPU 750 @ 2.67GHz                | 1        | 2.17%   |
| Intel Core i3-4130 CPU @ 3.40GHz               | 1        | 2.17%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz          | 1        | 2.17%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz           | 1        | 2.17%   |
| Intel Celeron (Coppermine)                     | 1        | 2.17%   |
| Intel Atom CPU C2750 @ 2.40GHz                 | 1        | 2.17%   |
| AMD Sempron Processor 2800+                    | 1        | 2.17%   |
| AMD Ryzen Threadripper 1920X 12-Core Processor | 1        | 2.17%   |
| AMD Ryzen 7 5700X 8-Core Processor             | 1        | 2.17%   |
| AMD Ryzen 7 2700X Eight-Core Processor         | 1        | 2.17%   |
| AMD Ryzen 5 3600 6-Core Processor              | 1        | 2.17%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics    | 1        | 2.17%   |
| AMD Ryzen 3 3100 4-Core Processor              | 1        | 2.17%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 13       | 28.26%  |
| Intel Core i7           | 5        | 10.87%  |
| Intel Xeon              | 3        | 6.52%   |
| Intel Core 2 Duo        | 3        | 6.52%   |
| AMD Ryzen 5             | 3        | 6.52%   |
| AMD Ryzen 7             | 2        | 4.35%   |
| AMD Ryzen 3             | 2        | 4.35%   |
| Intel Pentium Silver    | 1        | 2.17%   |
| Intel Pentium Gold      | 1        | 2.17%   |
| Intel Pentium Dual-Core | 1        | 2.17%   |
| Intel Pentium Dual      | 1        | 2.17%   |
| Intel Pentium 4         | 1        | 2.17%   |
| Intel Pentium           | 1        | 2.17%   |
| Intel Core i9           | 1        | 2.17%   |
| Intel Core i3           | 1        | 2.17%   |
| Intel Core 2 Quad       | 1        | 2.17%   |
| Intel Celeron           | 1        | 2.17%   |
| Intel Atom              | 1        | 2.17%   |
| AMD Sempron             | 1        | 2.17%   |
| AMD Ryzen Threadripper  | 1        | 2.17%   |
| AMD FX                  | 1        | 2.17%   |
| AMD A4                  | 1        | 2.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 19       | 42.22%  |
| 2      | 10       | 22.22%  |
| 6      | 8        | 17.78%  |
| 8      | 3        | 6.67%   |
| 1      | 3        | 6.67%   |
| 12     | 1        | 2.22%   |
| 10     | 1        | 2.22%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 45       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 24       | 53.33%  |
| 2      | 21       | 46.67%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 44       | 97.78%  |
| 32-bit         | 1        | 2.22%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 9        | 19.57%  |
| 0x306c3    | 4        | 8.7%    |
| 0x906ea    | 3        | 6.52%   |
| 0x306a9    | 3        | 6.52%   |
| 0x206a7    | 3        | 6.52%   |
| 0x1067a    | 3        | 6.52%   |
| 0x106e5    | 2        | 4.35%   |
| 0xf49      | 1        | 2.17%   |
| 0xa0655    | 1        | 2.17%   |
| 0xa0653    | 1        | 2.17%   |
| 0x906e9    | 1        | 2.17%   |
| 0x706a1    | 1        | 2.17%   |
| 0x6fd      | 1        | 2.17%   |
| 0x686      | 1        | 2.17%   |
| 0x506e3    | 1        | 2.17%   |
| 0x406d8    | 1        | 2.17%   |
| 0x40651    | 1        | 2.17%   |
| 0x306f2    | 1        | 2.17%   |
| 0x10676    | 1        | 2.17%   |
| 0x0a20120a | 1        | 2.17%   |
| 0x08701021 | 1        | 2.17%   |
| 0x08701013 | 1        | 2.17%   |
| 0x0800820d | 1        | 2.17%   |
| 0x08001138 | 1        | 2.17%   |
| 0x08001129 | 1        | 2.17%   |
| 0x03000027 | 1        | 2.17%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Haswell       | 7        | 15.56%  |
| KabyLake      | 5        | 11.11%  |
| Penryn        | 4        | 8.89%   |
| Zen           | 3        | 6.67%   |
| SandyBridge   | 3        | 6.67%   |
| Nehalem       | 3        | 6.67%   |
| IvyBridge     | 3        | 6.67%   |
| Zen+          | 2        | 4.44%   |
| Zen 2         | 2        | 4.44%   |
| Skylake       | 2        | 4.44%   |
| CometLake     | 2        | 4.44%   |
| Zen 3         | 1        | 2.22%   |
| Silvermont    | 1        | 2.22%   |
| Piledriver    | 1        | 2.22%   |
| P6            | 1        | 2.22%   |
| NetBurst      | 1        | 2.22%   |
| K8 Hammer     | 1        | 2.22%   |
| K10 Llano     | 1        | 2.22%   |
| Goldmont plus | 1        | 2.22%   |
| Core          | 1        | 2.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 17       | 36.96%  |
| Nvidia                           | 15       | 32.61%  |
| AMD                              | 13       | 28.26%  |
| Silicon Integrated Systems [SiS] | 1        | 2.17%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 3        | 6.12%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3        | 6.12%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 4.08%   |
| Nvidia G96CGL [Quadro FX 580]                                               | 2        | 4.08%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2        | 4.08%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 4.08%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2        | 4.08%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2        | 4.08%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter           | 1        | 2.04%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                       | 1        | 2.04%   |
| Nvidia GT218 [GeForce 310]                                                  | 1        | 2.04%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 2.04%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 2.04%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 2.04%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 2.04%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                           | 1        | 2.04%   |
| Nvidia GA104 [GeForce RTX 3060 Ti]                                          | 1        | 2.04%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 2.04%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1        | 2.04%   |
| Intel HD Graphics 630                                                       | 1        | 2.04%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 1        | 2.04%   |
| Intel GeminiLake [UHD Graphics 605]                                         | 1        | 2.04%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 2.04%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                   | 1        | 2.04%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 1        | 2.04%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 2.04%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1        | 2.04%   |
| AMD RV350 [Radeon 9550] (Secondary)                                         | 1        | 2.04%   |
| AMD RV350 [Radeon 9550]                                                     | 1        | 2.04%   |
| AMD RV100 [Radeon 7000 / Radeon VE]                                         | 1        | 2.04%   |
| AMD RS780L [Radeon 3000]                                                    | 1        | 2.04%   |
| AMD R350 [Radeon 9800 Series]                                               | 1        | 2.04%   |
| AMD R350 [Radeon 9800 PRO] (Secondary)                                      | 1        | 2.04%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 1        | 2.04%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 1        | 2.04%   |
| AMD Curacao XT / Trinidad XT [Radeon R7 370 / R9 270X/370X]                 | 1        | 2.04%   |
| AMD Cedar [Radeon HD 7350/8350 / R5 220]                                    | 1        | 2.04%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                           | 1        | 2.04%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 1        | 2.04%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| 1 x Nvidia  | 15       | 33.33%  |
| 1 x Intel   | 15       | 33.33%  |
| 1 x AMD     | 11       | 24.44%  |
| Other       | 1        | 2.22%   |
| 2 x AMD     | 1        | 2.22%   |
| 1 x SiS     | 1        | 2.22%   |
| Intel + AMD | 1        | 2.22%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 32       | 69.57%  |
| Proprietary | 10       | 21.74%  |
| Unknown     | 4        | 8.7%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 18       | 40%     |
| 0.01-0.5   | 8        | 17.78%  |
| 3.01-4.0   | 6        | 13.33%  |
| 0.51-1.0   | 4        | 8.89%   |
| 7.01-8.0   | 3        | 6.67%   |
| 2.01-3.0   | 3        | 6.67%   |
| 1.01-2.0   | 2        | 4.44%   |
| 5.01-6.0   | 1        | 2.22%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 10       | 20.83%  |
| Hewlett-Packard      | 7        | 14.58%  |
| Philips              | 4        | 8.33%   |
| Goldstar             | 4        | 8.33%   |
| Iiyama               | 3        | 6.25%   |
| AOC                  | 3        | 6.25%   |
| Lenovo               | 2        | 4.17%   |
| Dell                 | 2        | 4.17%   |
| Acer                 | 2        | 4.17%   |
| ___                  | 1        | 2.08%   |
| ViewSonic            | 1        | 2.08%   |
| Unknown              | 1        | 2.08%   |
| Toshiba              | 1        | 2.08%   |
| MSI                  | 1        | 2.08%   |
| HJW                  | 1        | 2.08%   |
| eMachines            | 1        | 2.08%   |
| Eizo                 | 1        | 2.08%   |
| CVT                  | 1        | 2.08%   |
| CHI                  | 1        | 2.08%   |
| Ancor Communications | 1        | 2.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM0091 1600x1200 432x324mm 21.3-inch   | 2        | 3.85%   |
| Hewlett-Packard 22m HPN3575 1920x1080 476x268mm 21.5-inch              | 2        | 3.85%   |
| ___ LCD TV ___9000 1360x768                                            | 1        | 1.92%   |
| ViewSonic VA2261 Series VSC0F30 1920x1080 477x268mm 21.5-inch          | 1        | 1.92%   |
| Unknown LCD TV 9000 1360x768 1600x900mm 72.3-inch                      | 1        | 1.92%   |
| Toshiba TV TSB0209 1920x1080 1594x900mm 72.1-inch                      | 1        | 1.92%   |
| Samsung Electronics T24B301 SAM098E 1920x1080 521x293mm 23.5-inch      | 1        | 1.92%   |
| Samsung Electronics SyncMaster SAM0226 1440x900 410x257mm 19.1-inch    | 1        | 1.92%   |
| Samsung Electronics SyncMaster SAM0029 2048x1536 312x234mm 15.4-inch   | 1        | 1.92%   |
| Samsung Electronics S/T 77/76BDF STN0007 1280x1024 312x234mm 15.4-inch | 1        | 1.92%   |
| Samsung Electronics LCD Monitor SyncMaster 1280x1024                   | 1        | 1.92%   |
| Samsung Electronics LCD Monitor SyncMaster                             | 1        | 1.92%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 480x270mm 21.7-inch  | 1        | 1.92%   |
| Samsung Electronics LCD Monitor SA300/350/360                          | 1        | 1.92%   |
| Samsung Electronics LCD Monitor S24D340                                | 1        | 1.92%   |
| Samsung Electronics LCD Monitor C27F390 5760x1080                      | 1        | 1.92%   |
| Samsung Electronics C27F398 SAM0D45 1920x1080 598x336mm 27.0-inch      | 1        | 1.92%   |
| Philips PHL 241P6Q PHL08DB 1920x1080 527x296mm 23.8-inch               | 1        | 1.92%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                | 1        | 1.92%   |
| Philips 190B PHL086C 1280x1024 376x301mm 19.0-inch                     | 1        | 1.92%   |
| Philips 17S PHL0877 1280x1024 337x270mm 17.0-inch                      | 1        | 1.92%   |
| MSI PRO 22X 10M MSI1462 1920x1080 595x336mm 26.9-inch                  | 1        | 1.92%   |
| Lenovo LI2215sD LEN65CC 1920x1080 476x267mm 21.5-inch                  | 1        | 1.92%   |
| Lenovo LCD Monitor LEN40A0 1366x768 309x174mm 14.0-inch                | 1        | 1.92%   |
| Iiyama PLX2483H IVM6114 1920x1080 531x299mm 24.0-inch                  | 1        | 1.92%   |
| Iiyama PLB2712HDS IVM6602 1920x1080 598x336mm 27.0-inch                | 1        | 1.92%   |
| Iiyama PL2482H IVM610D 1920x1080 521x293mm 23.5-inch                   | 1        | 1.92%   |
| HJW HDMI TO USB HJW0001 1920x1080 700x390mm 31.5-inch                  | 1        | 1.92%   |
| Hewlett-Packard LA2206 HWP2947 1920x1080 477x268mm 21.5-inch           | 1        | 1.92%   |
| Hewlett-Packard L2245w HWP26FC 1680x1050 470x300mm 22.0-inch           | 1        | 1.92%   |
| Hewlett-Packard ENVY 34c HWP3204 3440x1440 800x330mm 34.1-inch         | 1        | 1.92%   |
| Hewlett-Packard E243 HPN3468 1920x1080 530x300mm 24.0-inch             | 1        | 1.92%   |
| Hewlett-Packard Compaq S2321a HWP2915 1920x1080 509x286mm 23.0-inch    | 1        | 1.92%   |
| Hewlett-Packard 22cw HWP3183 1920x1080 476x268mm 21.5-inch             | 1        | 1.92%   |
| Goldstar W2243 GSM56FF 1920x1080 477x268mm 21.5-inch                   | 1        | 1.92%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                | 1        | 1.92%   |
| Goldstar L1730S GSM438D 1280x1024 338x270mm 17.0-inch                  | 1        | 1.92%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 1        | 1.92%   |
| eMachines E19T6W EMA0783 1440x900 410x260mm 19.1-inch                  | 1        | 1.92%   |
| Eizo EV2456 ENC2798 1920x1200 520x330mm 24.2-inch                      | 1        | 1.92%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 19       | 40.43%  |
| 1280x1024 (SXGA)   | 5        | 10.64%  |
| 3840x2160 (4K)     | 4        | 8.51%   |
| 1440x900 (WXGA+)   | 4        | 8.51%   |
| 1366x768 (WXGA)    | 3        | 6.38%   |
| 3440x1440          | 2        | 4.26%   |
| 1600x1200          | 2        | 4.26%   |
| Unknown            | 2        | 4.26%   |
| 5760x1080          | 1        | 2.13%   |
| 1920x1200 (WUXGA)  | 1        | 2.13%   |
| 1680x1050 (WSXGA+) | 1        | 2.13%   |
| 1600x900 (HD+)     | 1        | 2.13%   |
| 1360x768           | 1        | 2.13%   |
| 1024x768 (XGA)     | 1        | 2.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 12       | 26.09%  |
| 27      | 4        | 8.7%    |
| 23      | 4        | 8.7%    |
| Unknown | 4        | 8.7%    |
| 24      | 3        | 6.52%   |
| 19      | 3        | 6.52%   |
| 18      | 3        | 6.52%   |
| 72      | 2        | 4.35%   |
| 34      | 2        | 4.35%   |
| 31      | 2        | 4.35%   |
| 17      | 2        | 4.35%   |
| 15      | 2        | 4.35%   |
| 54      | 1        | 2.17%   |
| 22      | 1        | 2.17%   |
| 14      | 1        | 2.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 15       | 35.71%  |
| 501-600     | 10       | 23.81%  |
| 301-350     | 4        | 9.52%   |
| Unknown     | 4        | 9.52%   |
| 701-800     | 2        | 4.76%   |
| 601-700     | 2        | 4.76%   |
| 351-400     | 2        | 4.76%   |
| 1501-2000   | 2        | 4.76%   |
| 1001-1500   | 1        | 2.38%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 25       | 58.14%  |
| 16/10   | 5        | 11.63%  |
| 4/3     | 4        | 9.3%    |
| 5/4     | 3        | 6.98%   |
| Unknown | 3        | 6.98%   |
| 21/9    | 2        | 4.65%   |
| 6/5     | 1        | 2.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 13       | 29.55%  |
| 151-200        | 8        | 18.18%  |
| 351-500        | 4        | 9.09%   |
| 301-350        | 4        | 9.09%   |
| 141-150        | 4        | 9.09%   |
| Unknown        | 4        | 9.09%   |
| More than 1000 | 3        | 6.82%   |
| 111-120        | 2        | 4.55%   |
| 81-90          | 1        | 2.27%   |
| 251-300        | 1        | 2.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 21       | 47.73%  |
| 101-120 | 16       | 36.36%  |
| Unknown | 4        | 9.09%   |
| 1-50    | 3        | 6.82%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 34       | 75.56%  |
| 2     | 5        | 11.11%  |
| 3     | 3        | 6.67%   |
| 0     | 3        | 6.67%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 24       | 42.86%  |
| Intel                            | 21       | 37.5%   |
| Qualcomm Atheros                 | 3        | 5.36%   |
| Marvell Technology Group         | 2        | 3.57%   |
| TP-Link                          | 1        | 1.79%   |
| Silicon Integrated Systems [SiS] | 1        | 1.79%   |
| Ralink Technology                | 1        | 1.79%   |
| JMicron Technology               | 1        | 1.79%   |
| Chelsio Communications           | 1        | 1.79%   |
| Broadcom                         | 1        | 1.79%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 20       | 33.9%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 5.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 5.08%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1        | 1.69%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1        | 1.69%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 1        | 1.69%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1        | 1.69%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1        | 1.69%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 1.69%   |
| Ralink MT7601U Wireless Adapter                                   | 1        | 1.69%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 1.69%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1        | 1.69%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter        | 1        | 1.69%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1        | 1.69%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 1.69%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1        | 1.69%   |
| Intel Wireless 7260                                               | 1        | 1.69%   |
| Intel I211 Gigabit Network Connection                             | 1        | 1.69%   |
| Intel I210 Gigabit Network Connection                             | 1        | 1.69%   |
| Intel Ethernet Controller I225-V                                  | 1        | 1.69%   |
| Intel Ethernet Connection I354 2.5 GbE Backplane                  | 1        | 1.69%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.69%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 1.69%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 1.69%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 1.69%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 1.69%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1        | 1.69%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 1.69%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 1.69%   |
| Intel 82576 Gigabit Network Connection                            | 1        | 1.69%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 1.69%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)        | 1        | 1.69%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 1.69%   |
| Chelsio T420-SO Unified Wire Ethernet Controller                  | 1        | 1.69%   |
| Chelsio Chelsio Ethernet controller                               | 1        | 1.69%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1        | 1.69%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 3        | 33.33%  |
| Qualcomm Atheros      | 2        | 22.22%  |
| Intel                 | 2        | 22.22%  |
| TP-Link               | 1        | 11.11%  |
| Ralink Technology     | 1        | 11.11%  |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]               | 1        | 11.11%  |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter    | 1        | 11.11%  |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter        | 1        | 11.11%  |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                 | 1        | 11.11%  |
| Ralink MT7601U Wireless Adapter                            | 1        | 11.11%  |
| Qualcomm Atheros AR9462 Wireless Network Adapter           | 1        | 11.11%  |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter | 1        | 11.11%  |
| Intel Wireless 7260                                        | 1        | 11.11%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 1        | 11.11%  |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 21       | 43.75%  |
| Intel                            | 20       | 41.67%  |
| Marvell Technology Group         | 2        | 4.17%   |
| Silicon Integrated Systems [SiS] | 1        | 2.08%   |
| Qualcomm Atheros                 | 1        | 2.08%   |
| JMicron Technology               | 1        | 2.08%   |
| Chelsio Communications           | 1        | 2.08%   |
| Broadcom                         | 1        | 2.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 20       | 40%     |
| Intel Ethernet Connection I217-LM                                 | 3        | 6%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 6%      |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1        | 2%      |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 2%      |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 2%      |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1        | 2%      |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 2%      |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1        | 2%      |
| Intel I211 Gigabit Network Connection                             | 1        | 2%      |
| Intel I210 Gigabit Network Connection                             | 1        | 2%      |
| Intel Ethernet Controller I225-V                                  | 1        | 2%      |
| Intel Ethernet Connection I354 2.5 GbE Backplane                  | 1        | 2%      |
| Intel Ethernet Connection (7) I219-V                              | 1        | 2%      |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 2%      |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 2%      |
| Intel Ethernet Connection (14) I219-V                             | 1        | 2%      |
| Intel Ethernet Connection (11) I219-V                             | 1        | 2%      |
| Intel 82579V Gigabit Network Connection                           | 1        | 2%      |
| Intel 82578DM Gigabit Network Connection                          | 1        | 2%      |
| Intel 82576 Gigabit Network Connection                            | 1        | 2%      |
| Intel 82574L Gigabit Network Connection                           | 1        | 2%      |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)        | 1        | 2%      |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 2%      |
| Chelsio T420-SO Unified Wire Ethernet Controller                  | 1        | 2%      |
| Chelsio Chelsio Ethernet controller                               | 1        | 2%      |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1        | 2%      |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 44       | 83.02%  |
| WiFi     | 9        | 16.98%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 37       | 84.09%  |
| WiFi     | 7        | 15.91%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 32       | 69.57%  |
| 2     | 10       | 21.74%  |
| 7     | 1        | 2.17%   |
| 5     | 1        | 2.17%   |
| 3     | 1        | 2.17%   |
| 0     | 1        | 2.17%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 41       | 91.11%  |
| Yes  | 4        | 8.89%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Qualcomm Atheros Communications | 2        | 40%     |
| Intel                           | 2        | 40%     |
| ASUSTek Computer                | 1        | 20%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Qualcomm Atheros  Bluetooth Device | 1        | 20%     |
| Qualcomm Atheros AR3011 Bluetooth  | 1        | 20%     |
| Intel Wireless-AC 3168 Bluetooth   | 1        | 20%     |
| Intel Bluetooth wireless interface | 1        | 20%     |
| ASUS ASUS USB-BT500                | 1        | 20%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 30       | 42.86%  |
| Nvidia                           | 13       | 18.57%  |
| AMD                              | 12       | 17.14%  |
| Creative Labs                    | 3        | 4.29%   |
| Plantronics                      | 2        | 2.86%   |
| Texas Instruments                | 1        | 1.43%   |
| TEAC                             | 1        | 1.43%   |
| Silicon Integrated Systems [SiS] | 1        | 1.43%   |
| M-Audio                          | 1        | 1.43%   |
| Logitech                         | 1        | 1.43%   |
| KORG                             | 1        | 1.43%   |
| Elite Silicon                    | 1        | 1.43%   |
| DCMT Technology                  | 1        | 1.43%   |
| Cirrus Logic                     | 1        | 1.43%   |
| ASUSTek Computer                 | 1        | 1.43%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5        | 6.02%   |
| Nvidia GP106 High Definition Audio Controller                              | 4        | 4.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4        | 4.82%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4        | 4.82%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3        | 3.61%   |
| Intel Cannon Lake PCH cAVS                                                 | 3        | 3.61%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3        | 3.61%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3        | 3.61%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3        | 3.61%   |
| Plantronics HD1                                                            | 2        | 2.41%   |
| Nvidia High Definition Audio Controller                                    | 2        | 2.41%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 2.41%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2        | 2.41%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2        | 2.41%   |
| Intel 200 Series PCH HD Audio                                              | 2        | 2.41%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]  | 2        | 2.41%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2        | 2.41%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2        | 2.41%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2        | 2.41%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2        | 2.41%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2        | 2.41%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1        | 1.2%    |
| TEAC US-1800                                                               | 1        | 1.2%    |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 1        | 1.2%    |
| Nvidia GP104 High Definition Audio Controller                              | 1        | 1.2%    |
| Nvidia GK106 HDMI Audio Controller                                         | 1        | 1.2%    |
| Nvidia GA104 High Definition Audio Controller                              | 1        | 1.2%    |
| M-Audio MIDISPORT 4x4 Anniv                                                | 1        | 1.2%    |
| M-Audio M-Audio 1x1                                                        | 1        | 1.2%    |
| Logitech H390 headset with microphone                                      | 1        | 1.2%    |
| KORG nanoKONTROL studio controller                                         | 1        | 1.2%    |
| Intel Haswell-ULT HD Audio Controller                                      | 1        | 1.2%    |
| Intel Comet Lake PCH cAVS                                                  | 1        | 1.2%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1        | 1.2%    |
| Intel C610/X99 series chipset HD Audio Controller                          | 1        | 1.2%    |
| Intel Audio device                                                         | 1        | 1.2%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1        | 1.2%    |
| Intel 82801BA/BAM AC'97 Audio Controller                                   | 1        | 1.2%    |
| Intel 8 Series HD Audio Controller                                         | 1        | 1.2%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1        | 1.2%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 12       | 24.49%  |
| Kingston            | 9        | 18.37%  |
| Corsair             | 7        | 14.29%  |
| SK hynix            | 5        | 10.2%   |
| Micron Technology   | 4        | 8.16%   |
| G.Skill             | 3        | 6.12%   |
| Samsung Electronics | 2        | 4.08%   |
| Nanya Technology    | 2        | 4.08%   |
| Team                | 1        | 2.04%   |
| GOODRAM             | 1        | 2.04%   |
| Crucial             | 1        | 2.04%   |
| Avant               | 1        | 2.04%   |
| A-DATA Technology   | 1        | 2.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s     | 2        | 3.51%   |
| Corsair RAM CMK32GX4M4A2666C16 8GB DIMM DDR4 2667MT/s     | 2        | 3.51%   |
| Unknown RAM SM3S320SD0488CABC 8192MB SODIMM DDR3 1600MT/s | 1        | 1.75%   |
| Unknown RAM Module 8192MB DIMM DDR3 800MT/s               | 1        | 1.75%   |
| Unknown RAM Module 64MB DIMM DRAM 100MT/s                 | 1        | 1.75%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                      | 1        | 1.75%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s            | 1        | 1.75%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s              | 1        | 1.75%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                      | 1        | 1.75%   |
| Unknown RAM Module 256MB DIMM DRAM 100MT/s                | 1        | 1.75%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s             | 1        | 1.75%   |
| Unknown RAM Module 2048MB DIMM SDRAM 667MT/s              | 1        | 1.75%   |
| Unknown RAM Module 2048MB DIMM SDRAM                      | 1        | 1.75%   |
| Unknown RAM Module 128MB DIMM DRAM 100MT/s                | 1        | 1.75%   |
| Unknown RAM Module 1024MB DIMM DDR 400MT/s                | 1        | 1.75%   |
| Unknown RAM Module 1024MB DIMM DDR                        | 1        | 1.75%   |
| Unknown RAM 3000 C16 Series 8192MB DIMM DDR4 2133MT/s     | 1        | 1.75%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 2667MT/s        | 1        | 1.75%   |
| SK hynix RAM Module 4GB DIMM DDR3 1333MT/s                | 1        | 1.75%   |
| SK hynix RAM HMT451U7BFR8A-PB 4GB DIMM 1600MT/s           | 1        | 1.75%   |
| SK hynix RAM HMT451U6AFR8A-PB 4GB DIMM DDR3 1600MT/s      | 1        | 1.75%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s      | 1        | 1.75%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM 1600MT/s           | 1        | 1.75%   |
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s   | 1        | 1.75%   |
| SK hynix RAM HMA81GU6JJR8N-VK 8192MB DIMM DDR4 2666MT/s   | 1        | 1.75%   |
| Samsung RAM Module 2GB DIMM DDR3 1333MT/s                 | 1        | 1.75%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s       | 1        | 1.75%   |
| Nanya RAM Module 2GB DIMM DDR3 1333MT/s                   | 1        | 1.75%   |
| Nanya RAM M2X4G64CB8HG5N-DG 4GB DIMM DDR3 1867MT/s        | 1        | 1.75%   |
| Micron RAM Module 2GB DIMM DDR3 1333MT/s                  | 1        | 1.75%   |
| Micron RAM DVM64453C DATARAM 8GB DIMM DDR3 1600MT/s       | 1        | 1.75%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s       | 1        | 1.75%   |
| Micron RAM 4ATF51264HZ-2G3E1 4GB SODIMM DDR4 2667MT/s     | 1        | 1.75%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s    | 1        | 1.75%   |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 2667MT/s       | 1        | 1.75%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2400MT/s         | 1        | 1.75%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s       | 1        | 1.75%   |
| Kingston RAM 99U5704-001.A00G 4GB SODIMM DDR4 2400MT/s    | 1        | 1.75%   |
| Kingston RAM 99U5702-094.A00G 8GB DIMM DDR4 2400MT/s      | 1        | 1.75%   |
| Kingston RAM 99U5471-066.A00LF 8192MB DIMM DDR3 1600MT/s  | 1        | 1.75%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 18       | 42.86%  |
| DDR3    | 16       | 38.1%   |
| SDRAM   | 2        | 4.76%   |
| DDR     | 2        | 4.76%   |
| Unknown | 2        | 4.76%   |
| DRAM    | 1        | 2.38%   |
| DDR2    | 1        | 2.38%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 36       | 87.8%   |
| SODIMM | 5        | 12.2%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 14       | 29.79%  |
| 8192  | 13       | 27.66%  |
| 16384 | 9        | 19.15%  |
| 2048  | 5        | 10.64%  |
| 1024  | 2        | 4.26%   |
| 32768 | 1        | 2.13%   |
| 256   | 1        | 2.13%   |
| 128   | 1        | 2.13%   |
| 64    | 1        | 2.13%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 9        | 20%     |
| 2667    | 6        | 13.33%  |
| 2400    | 5        | 11.11%  |
| 1333    | 5        | 11.11%  |
| 3600    | 3        | 6.67%   |
| 3200    | 3        | 6.67%   |
| 2133    | 2        | 4.44%   |
| 1800    | 2        | 4.44%   |
| 667     | 2        | 4.44%   |
| Unknown | 2        | 4.44%   |
| 3400    | 1        | 2.22%   |
| 2666    | 1        | 2.22%   |
| 1867    | 1        | 2.22%   |
| 800     | 1        | 2.22%   |
| 400     | 1        | 2.22%   |
| 100     | 1        | 2.22%   |

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
| Cubeternet                  | 2        | 18.18%  |
| Z-Star Microelectronics     | 1        | 9.09%   |
| Softkinetic                 | 1        | 9.09%   |
| Realtek Semiconductor       | 1        | 9.09%   |
| Microsoft                   | 1        | 9.09%   |
| Microdia                    | 1        | 9.09%   |
| MacroSilicon                | 1        | 9.09%   |
| Logitech                    | 1        | 9.09%   |
| KYE Systems (Mouse Systems) | 1        | 9.09%   |
| GEMBIRD                     | 1        | 9.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Cubeternet GL-UPC822 UVC WebCam            | 2        | 18.18%  |
| Z-Star Vimicro USB Camera (Altair)         | 1        | 9.09%   |
| Softkinetic DepthSense 325                 | 1        | 9.09%   |
| Realtek HD 720P Webcam                     | 1        | 9.09%   |
| Microsoft LifeCam Studio                   | 1        | 9.09%   |
| Microdia Camera                            | 1        | 9.09%   |
| MacroSilicon USB Video                     | 1        | 9.09%   |
| Logitech Webcam C270                       | 1        | 9.09%   |
| KYE Systems (Mouse Systems) PC-LM1E Camera | 1        | 9.09%   |
| GEMBIRD USB2.0 PC CAMERA                   | 1        | 9.09%   |

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
| 0     | 38       | 84.44%  |
| 1     | 6        | 13.33%  |
| 2     | 1        | 2.22%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 4        | 50%     |
| Unassigned class         | 1        | 12.5%   |
| Net/ethernet             | 1        | 12.5%   |
| Firewire controller      | 1        | 12.5%   |
| Communication controller | 1        | 12.5%   |

