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

Total: 54

| Vendor        | Model                    | Probe                                                      | Date         |
|---------------|--------------------------|------------------------------------------------------------|--------------|
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
| Devuan 4                | 14       | 33.33%  |
| Devuan 3                | 13       | 30.95%  |
| Devuan Testing/unstable | 7        | 16.67%  |
| Devuan 2.1              | 6        | 14.29%  |
| Devuan 5                | 1        | 2.38%   |
| Devuan 1.0.0            | 1        | 2.38%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Devuan | 39       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Desktops | Percent |
|----------------------|----------|---------|
| 5.10.0-9-amd64       | 6        | 13.95%  |
| 4.19.0-14-amd64      | 4        | 9.3%    |
| 4.19.0-16-amd64      | 3        | 6.98%   |
| 5.10.0-8-amd64       | 2        | 4.65%   |
| 5.10.0-6-amd64       | 2        | 4.65%   |
| 4.19.0-9-amd64       | 2        | 4.65%   |
| 4.19.0-13-amd64      | 2        | 4.65%   |
| 5.9.0-1-amd64        | 1        | 2.33%   |
| 5.8.0-3-amd64        | 1        | 2.33%   |
| 5.7.0-1-amd64        | 1        | 2.33%   |
| 5.7.0-0.bpo.2-amd64  | 1        | 2.33%   |
| 5.16.0-1-amd64       | 1        | 2.33%   |
| 5.15.0-2-amd64       | 1        | 2.33%   |
| 5.15.0-0.bpo.2-amd64 | 1        | 2.33%   |
| 5.14.0-kali2-amd64   | 1        | 2.33%   |
| 5.10.0-5-amd64       | 1        | 2.33%   |
| 5.10.0-2-amd64       | 1        | 2.33%   |
| 5.10.0-11-amd64      | 1        | 2.33%   |
| 5.10.0-10-amd64      | 1        | 2.33%   |
| 4.9.0-15-amd64       | 1        | 2.33%   |
| 4.9.0-14-686-pae     | 1        | 2.33%   |
| 4.9.0-14-686         | 1        | 2.33%   |
| 4.9.0-11-686-pae     | 1        | 2.33%   |
| 4.19.112             | 1        | 2.33%   |
| 4.19.0-12-amd64      | 1        | 2.33%   |
| 4.19.0-10-amd64      | 1        | 2.33%   |
| 4.19.0-1-amd64       | 1        | 2.33%   |
| 4.19.0-0.bpo.6-amd64 | 1        | 2.33%   |
| 4.18.0-0.bpo.1-amd64 | 1        | 2.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.10.0   | 14       | 34.15%  |
| 4.19.0   | 13       | 31.71%  |
| 4.9.0    | 4        | 9.76%   |
| 5.7.0    | 2        | 4.88%   |
| 5.15.0   | 2        | 4.88%   |
| 5.9.0    | 1        | 2.44%   |
| 5.8.0    | 1        | 2.44%   |
| 5.16.0   | 1        | 2.44%   |
| 5.14.0   | 1        | 2.44%   |
| 4.19.112 | 1        | 2.44%   |
| 4.18.0   | 1        | 2.44%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 14       | 34.15%  |
| 4.19    | 14       | 34.15%  |
| 4.9     | 4        | 9.76%   |
| 5.7     | 2        | 4.88%   |
| 5.15    | 2        | 4.88%   |
| 5.9     | 1        | 2.44%   |
| 5.8     | 1        | 2.44%   |
| 5.16    | 1        | 2.44%   |
| 5.14    | 1        | 2.44%   |
| 4.18    | 1        | 2.44%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 36       | 92.31%  |
| i686   | 3        | 7.69%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| XFCE       | 21       | 50%     |
| Unknown    | 7        | 16.67%  |
| MATE       | 6        | 14.29%  |
| KDE5       | 3        | 7.14%   |
| LXDE       | 2        | 4.76%   |
| X-Cinnamon | 1        | 2.38%   |
| i3         | 1        | 2.38%   |
| awesome    | 1        | 2.38%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 33       | 82.5%   |
| Tty     | 6        | 15%     |
| Unknown | 1        | 2.5%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SLiM    | 20       | 51.28%  |
| Unknown | 9        | 23.08%  |
| LightDM | 8        | 20.51%  |
| XDM     | 1        | 2.56%   |
| NODM    | 1        | 2.56%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 11       | 27.5%   |
| fr_FR   | 4        | 10%     |
| en_GB   | 4        | 10%     |
| Unknown | 4        | 10%     |
| sk_SK   | 3        | 7.5%    |
| en_AU   | 3        | 7.5%    |
| C       | 3        | 7.5%    |
| ru_RU   | 2        | 5%      |
| pt_BR   | 2        | 5%      |
| pl_PL   | 1        | 2.5%    |
| fr_BE   | 1        | 2.5%    |
| en_NZ   | 1        | 2.5%    |
| en_CA   | 1        | 2.5%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 27       | 69.23%  |
| EFI  | 12       | 30.77%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 35       | 89.74%  |
| Overlay | 2        | 5.13%   |
| Ext3    | 1        | 2.56%   |
| Unknown | 1        | 2.56%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 21       | 50%     |
| MBR     | 18       | 42.86%  |
| Unknown | 3        | 7.14%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 26       | 63.41%  |
| Yes       | 15       | 36.59%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 29       | 74.36%  |
| Yes       | 10       | 25.64%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 10       | 25.64%  |
| ASUSTek Computer    | 8        | 20.51%  |
| Dell                | 4        | 10.26%  |
| ASRock              | 4        | 10.26%  |
| MSI                 | 3        | 7.69%   |
| Hewlett-Packard     | 3        | 7.69%   |
| Intel               | 2        | 5.13%   |
| Sun Microsystems    | 1        | 2.56%   |
| Online Labs         | 1        | 2.56%   |
| Lenovo              | 1        | 2.56%   |
| Google              | 1        | 2.56%   |
| Acer                | 1        | 2.56%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| Sun Microsystems Ultra 24       | 1        | 2.56%   |
| Online Labs SR                  | 1        | 2.56%   |
| MSI MS-7B84                     | 1        | 2.56%   |
| MSI MS-7B53                     | 1        | 2.56%   |
| MSI MS-7A34                     | 1        | 2.56%   |
| Lenovo ThinkStation E20 4220CTO | 1        | 2.56%   |
| Intel D815EEA AAA45884-401      | 1        | 2.56%   |
| Intel AHV                       | 1        | 2.56%   |
| HP Z220 SFF Workstation         | 1        | 2.56%   |
| HP EliteDesk 800 G1 DM          | 1        | 2.56%   |
| HP Compaq 8200 Elite SFF PC     | 1        | 2.56%   |
| Google Panther                  | 1        | 2.56%   |
| Gigabyte Z390 GAMING SLI        | 1        | 2.56%   |
| Gigabyte P55A-UD3               | 1        | 2.56%   |
| Gigabyte MZGLKBP-00             | 1        | 2.56%   |
| Gigabyte H310M S2H 2.0          | 1        | 2.56%   |
| Gigabyte H170-HD3-CF            | 1        | 2.56%   |
| Gigabyte H170-HD3               | 1        | 2.56%   |
| Gigabyte GA-G41M-ES2L           | 1        | 2.56%   |
| Gigabyte B75M-D3V               | 1        | 2.56%   |
| Gigabyte B450 AORUS ELITE       | 1        | 2.56%   |
| Gigabyte 970A-DS3P              | 1        | 2.56%   |
| Dell OptiPlex 9020              | 1        | 2.56%   |
| Dell OptiPlex 7060              | 1        | 2.56%   |
| Dell OptiPlex 7050              | 1        | 2.56%   |
| Dell OptiPlex 7010              | 1        | 2.56%   |
| ASUS PRIME Z490M-PLUS           | 1        | 2.56%   |
| ASUS PRIME H510M-A              | 1        | 2.56%   |
| ASUS P5PE-VM                    | 1        | 2.56%   |
| ASUS P5G41T-M LX2/BR            | 1        | 2.56%   |
| ASUS Maximus V GENE             | 1        | 2.56%   |
| ASUS F1A55-M LX                 | 1        | 2.56%   |
| ASUS EX-A320M-GAMING            | 1        | 2.56%   |
| ASUS All Series                 | 1        | 2.56%   |
| ASRock K8A780LM                 | 1        | 2.56%   |
| ASRock H81M-ITX                 | 1        | 2.56%   |
| ASRock G31M-VS2                 | 1        | 2.56%   |
| ASRock B450M-HDV R4.0           | 1        | 2.56%   |
| Acer Aspire M1610               | 1        | 2.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 4        | 10.26%  |
| ASUS PRIME             | 2        | 5.13%   |
| Sun Microsystems Ultra | 1        | 2.56%   |
| Online Labs SR         | 1        | 2.56%   |
| MSI MS-7B84            | 1        | 2.56%   |
| MSI MS-7B53            | 1        | 2.56%   |
| MSI MS-7A34            | 1        | 2.56%   |
| Lenovo ThinkStation    | 1        | 2.56%   |
| Intel D815EEA          | 1        | 2.56%   |
| Intel AHV              | 1        | 2.56%   |
| HP Z220                | 1        | 2.56%   |
| HP EliteDesk           | 1        | 2.56%   |
| HP Compaq              | 1        | 2.56%   |
| Google Panther         | 1        | 2.56%   |
| Gigabyte Z390          | 1        | 2.56%   |
| Gigabyte P55A-UD3      | 1        | 2.56%   |
| Gigabyte MZGLKBP-00    | 1        | 2.56%   |
| Gigabyte H310M         | 1        | 2.56%   |
| Gigabyte H170-HD3-CF   | 1        | 2.56%   |
| Gigabyte H170-HD3      | 1        | 2.56%   |
| Gigabyte GA-G41M-ES2L  | 1        | 2.56%   |
| Gigabyte B75M-D3V      | 1        | 2.56%   |
| Gigabyte B450          | 1        | 2.56%   |
| Gigabyte 970A-DS3P     | 1        | 2.56%   |
| ASUS P5PE-VM           | 1        | 2.56%   |
| ASUS P5G41T-M          | 1        | 2.56%   |
| ASUS Maximus           | 1        | 2.56%   |
| ASUS F1A55-M           | 1        | 2.56%   |
| ASUS EX-A320M-GAMING   | 1        | 2.56%   |
| ASUS All               | 1        | 2.56%   |
| ASRock K8A780LM        | 1        | 2.56%   |
| ASRock H81M-ITX        | 1        | 2.56%   |
| ASRock G31M-VS2        | 1        | 2.56%   |
| ASRock B450M-HDV       | 1        | 2.56%   |
| Acer Aspire            | 1        | 2.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 8        | 20.51%  |
| 2014 | 4        | 10.26%  |
| 2012 | 4        | 10.26%  |
| 2017 | 3        | 7.69%   |
| 2013 | 3        | 7.69%   |
| 2011 | 3        | 7.69%   |
| 2019 | 2        | 5.13%   |
| 2010 | 2        | 5.13%   |
| 2009 | 2        | 5.13%   |
| 2021 | 1        | 2.56%   |
| 2020 | 1        | 2.56%   |
| 2016 | 1        | 2.56%   |
| 2015 | 1        | 2.56%   |
| 2008 | 1        | 2.56%   |
| 2007 | 1        | 2.56%   |
| 2006 | 1        | 2.56%   |
| 2000 | 1        | 2.56%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 39       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 39       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 37       | 94.87%  |
| Yes  | 2        | 5.13%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 16.01-24.0 | 11       | 28.21%  |
| 8.01-16.0  | 10       | 25.64%  |
| 4.01-8.0   | 6        | 15.38%  |
| 32.01-64.0 | 6        | 15.38%  |
| 1.01-2.0   | 3        | 7.69%   |
| 3.01-4.0   | 2        | 5.13%   |
| 0.01-0.5   | 1        | 2.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 12       | 29.27%  |
| 4.01-8.0  | 8        | 19.51%  |
| 2.01-3.0  | 7        | 17.07%  |
| 0.51-1.0  | 7        | 17.07%  |
| 3.01-4.0  | 4        | 9.76%   |
| 8.01-16.0 | 2        | 4.88%   |
| 0.01-0.5  | 1        | 2.44%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 18       | 46.15%  |
| 3      | 7        | 17.95%  |
| 2      | 6        | 15.38%  |
| 4      | 5        | 12.82%  |
| 5      | 3        | 7.69%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 28       | 71.79%  |
| Yes       | 11       | 28.21%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 38       | 97.44%  |
| No        | 1        | 2.56%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 32       | 80%     |
| Yes       | 8        | 20%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 35       | 89.74%  |
| Yes       | 4        | 10.26%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| France      | 6        | 15.38%  |
| Russia      | 4        | 10.26%  |
| USA         | 3        | 7.69%   |
| Ukraine     | 3        | 7.69%   |
| Slovakia    | 3        | 7.69%   |
| Australia   | 3        | 7.69%   |
| UK          | 2        | 5.13%   |
| Poland      | 2        | 5.13%   |
| Netherlands | 2        | 5.13%   |
| Brazil      | 2        | 5.13%   |
| Argentina   | 2        | 5.13%   |
| South Korea | 1        | 2.56%   |
| Puerto Rico | 1        | 2.56%   |
| New Zealand | 1        | 2.56%   |
| Israel      | 1        | 2.56%   |
| Germany     | 1        | 2.56%   |
| Canada      | 1        | 2.56%   |
| Belgium     | 1        | 2.56%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Bratislava     | 3        | 7.69%   |
| Bagnolet       | 3        | 7.69%   |
| Volzhskiy      | 2        | 5.13%   |
| Sydney         | 2        | 5.13%   |
| Wroclaw        | 1        | 2.56%   |
| Vladikavkaz    | 1        | 2.56%   |
| Toronto        | 1        | 2.56%   |
| Tel Aviv       | 1        | 2.56%   |
| Seongbuk-gu    | 1        | 2.56%   |
| Sao Paulo      | 1        | 2.56%   |
| Saint-Herblain | 1        | 2.56%   |
| Rio de Janeiro | 1        | 2.56%   |
| Renkum         | 1        | 2.56%   |
| Poperinge      | 1        | 2.56%   |
| Paris          | 1        | 2.56%   |
| Oleksandriya   | 1        | 2.56%   |
| Nérac         | 1        | 2.56%   |
| Miedziana Gora | 1        | 2.56%   |
| Miami          | 1        | 2.56%   |
| Loosdrecht     | 1        | 2.56%   |
| Leeds          | 1        | 2.56%   |
| Kirov          | 1        | 2.56%   |
| Karlsruhe      | 1        | 2.56%   |
| Hollywood      | 1        | 2.56%   |
| Great Bend     | 1        | 2.56%   |
| Donetsk        | 1        | 2.56%   |
| Dnipro         | 1        | 2.56%   |
| Cipolletti     | 1        | 2.56%   |
| Carlisle       | 1        | 2.56%   |
| Caguas         | 1        | 2.56%   |
| Buenos Aires   | 1        | 2.56%   |
| Brisbane       | 1        | 2.56%   |
| Auckland       | 1        | 2.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 16       | 28     | 23.19%  |
| Seagate             | 14       | 22     | 20.29%  |
| Kingston            | 8        | 10     | 11.59%  |
| Toshiba             | 5        | 5      | 7.25%   |
| Samsung Electronics | 4        | 5      | 5.8%    |
| Crucial             | 3        | 4      | 4.35%   |
| Netac               | 2        | 2      | 2.9%    |
| Micron Technology   | 2        | 2      | 2.9%    |
| Dogfish             | 2        | 2      | 2.9%    |
| A-DATA Technology   | 2        | 2      | 2.9%    |
| WD MediaMax         | 1        | 3      | 1.45%   |
| Transcend           | 1        | 2      | 1.45%   |
| SK Hynix            | 1        | 1      | 1.45%   |
| MAXTOR              | 1        | 1      | 1.45%   |
| KingDian            | 1        | 1      | 1.45%   |
| IBM/Hitachi         | 1        | 1      | 1.45%   |
| Hitachi             | 1        | 1      | 1.45%   |
| HGST                | 1        | 1      | 1.45%   |
| Hewlett-Packard     | 1        | 2      | 1.45%   |
| GOODRAM             | 1        | 1      | 1.45%   |
| Fujitsu             | 1        | 1      | 1.45%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Kingston SA2000M8250G 250GB         | 3        | 3.75%   |
| WDC WD10EARX-00N0YB0 1TB            | 2        | 2.5%    |
| Seagate ST2000DX002-2DV164 2TB      | 2        | 2.5%    |
| Samsung SSD 860 EVO 250GB           | 2        | 2.5%    |
| Kingston SA400S37120G 120GB SSD     | 2        | 2.5%    |
| WDC WDS480G2G0A-00JH30 480GB SSD    | 1        | 1.25%   |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 1        | 1.25%   |
| WDC WD800BB-00JHC0 80GB             | 1        | 1.25%   |
| WDC WD5001AALS-00L3B2 500GB         | 1        | 1.25%   |
| WDC WD5001AALS-00E3A0 500GB         | 1        | 1.25%   |
| WDC WD5000LPVX-00V0TT0 500GB        | 1        | 1.25%   |
| WDC WD5000BPVT-24HXZT3 500GB        | 1        | 1.25%   |
| WDC WD40EFRX-68WT0N0 4TB            | 1        | 1.25%   |
| WDC WD20PURZ-85GU6Y0 2TB            | 1        | 1.25%   |
| WDC WD20EZRX-00D8PB0 2TB            | 1        | 1.25%   |
| WDC WD20EFRX-68EUZN0 2TB            | 1        | 1.25%   |
| WDC WD1200JS-55NCB1 120GB           | 1        | 1.25%   |
| WDC WD10SPZX-22Z10T1 1TB            | 1        | 1.25%   |
| WDC WD10EZRX-00D8PB0 1TB            | 1        | 1.25%   |
| WDC WD10EZEX-75M2NA0 1TB            | 1        | 1.25%   |
| WDC WD10EZEX-22MFCA0 1TB            | 1        | 1.25%   |
| WDC WD10EZEX-22BN5A0 1TB            | 1        | 1.25%   |
| WDC WD10EZEX-08WN4A0 1TB            | 1        | 1.25%   |
| WDC WD10EURX-63FH1Y0 1TB            | 1        | 1.25%   |
| WD MediaMax WL500GSA3272 500GB      | 1        | 1.25%   |
| Transcend TS128GSSD370S 128GB       | 1        | 1.25%   |
| Toshiba MQ04ABF100 1TB              | 1        | 1.25%   |
| Toshiba MQ02ABF100 1TB              | 1        | 1.25%   |
| Toshiba KXG60ZNV512G NVMe 512GB     | 1        | 1.25%   |
| Toshiba HDWD110 1TB                 | 1        | 1.25%   |
| Toshiba DT01ACA100 1TB              | 1        | 1.25%   |
| SK Hynix SH920 mSATA 128GB SSD      | 1        | 1.25%   |
| Seagate ST8000DM004-2CX188 8TB      | 1        | 1.25%   |
| Seagate ST750LX003-1AC154 752GB     | 1        | 1.25%   |
| Seagate ST500DM002-1BD142 500GB     | 1        | 1.25%   |
| Seagate ST4000VN008-2DR166 4TB      | 1        | 1.25%   |
| Seagate ST4000DM005-2DP166 4TB      | 1        | 1.25%   |
| Seagate ST350063 0NS 500GB          | 1        | 1.25%   |
| Seagate ST3500418AS 500GB           | 1        | 1.25%   |
| Seagate ST340014A 40GB              | 1        | 1.25%   |
| Seagate ST3300555SS 304GB           | 1        | 1.25%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 1        | 1.25%   |
| Seagate ST3160815A 160GB            | 1        | 1.25%   |
| Seagate ST3160813AS 160GB           | 1        | 1.25%   |
| Seagate ST2000DM008-2FR102 2TB      | 1        | 1.25%   |
| Seagate ST2000DM006-2DM164 2TB      | 1        | 1.25%   |
| Seagate ST1000LM035-1RK172 1TB      | 1        | 1.25%   |
| Seagate ST1000DM003-1SB102 1TB      | 1        | 1.25%   |
| Seagate BUP Ultra Touch 2TB         | 1        | 1.25%   |
| Samsung SSD 860 EVO 500G            | 1        | 1.25%   |
| Samsung SSD 850 EVO 250GB           | 1        | 1.25%   |
| Netac SSD 720GB                     | 1        | 1.25%   |
| Netac SSD 512GB                     | 1        | 1.25%   |
| Micron 1100_MTFDDAK2T0TBN 2TB SSD   | 1        | 1.25%   |
| Micron 1100 SATA 256GB SSD          | 1        | 1.25%   |
| MAXTOR 6E040L0 41GB                 | 1        | 1.25%   |
| Kingston SV300S37A120G 120GB SSD    | 1        | 1.25%   |
| Kingston SA400S37960G 960GB SSD     | 1        | 1.25%   |
| Kingston SA400S37480G 480GB SSD     | 1        | 1.25%   |
| Kingston SA2000M8500G 500GB         | 1        | 1.25%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor          | Desktops | Drives | Percent |
|-----------------|----------|--------|---------|
| WDC             | 14       | 26     | 36.84%  |
| Seagate         | 14       | 22     | 36.84%  |
| Toshiba         | 4        | 4      | 10.53%  |
| MAXTOR          | 1        | 1      | 2.63%   |
| IBM/Hitachi     | 1        | 1      | 2.63%   |
| Hitachi         | 1        | 1      | 2.63%   |
| HGST            | 1        | 1      | 2.63%   |
| Hewlett-Packard | 1        | 2      | 2.63%   |
| Fujitsu         | 1        | 1      | 2.63%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 5        | 6      | 20.83%  |
| Samsung Electronics | 4        | 5      | 16.67%  |
| WDC                 | 2        | 2      | 8.33%   |
| Netac               | 2        | 2      | 8.33%   |
| Micron Technology   | 2        | 2      | 8.33%   |
| DOGFISH             | 2        | 2      | 8.33%   |
| A-DATA Technology   | 2        | 2      | 8.33%   |
| Transcend           | 1        | 2      | 4.17%   |
| SK Hynix            | 1        | 1      | 4.17%   |
| KingDian            | 1        | 1      | 4.17%   |
| GOODRAM             | 1        | 1      | 4.17%   |
| Crucial             | 1        | 1      | 4.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 31       | 59     | 52.54%  |
| SSD     | 21       | 27     | 35.59%  |
| NVMe    | 6        | 8      | 10.17%  |
| Unknown | 1        | 3      | 1.69%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 38       | 83     | 80.85%  |
| NVMe | 6        | 8      | 12.77%  |
| SAS  | 3        | 6      | 6.38%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 27       | 45     | 52.94%  |
| 0.51-1.0   | 14       | 26     | 27.45%  |
| 1.01-2.0   | 6        | 11     | 11.76%  |
| 3.01-4.0   | 3        | 3      | 5.88%   |
| 4.01-10.0  | 1        | 1      | 1.96%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1001-2000      | 10       | 23.81%  |
| 251-500        | 9        | 21.43%  |
| 101-250        | 6        | 14.29%  |
| 501-1000       | 5        | 11.9%   |
| More than 3000 | 4        | 9.52%   |
| 21-50          | 3        | 7.14%   |
| 51-100         | 2        | 4.76%   |
| Unknown        | 2        | 4.76%   |
| 1-20           | 1        | 2.38%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 15       | 36.59%  |
| 1-20           | 8        | 19.51%  |
| 21-50          | 5        | 12.2%   |
| 1001-2000      | 4        | 9.76%   |
| 501-1000       | 4        | 9.76%   |
| More than 3000 | 2        | 4.88%   |
| Unknown        | 2        | 4.88%   |
| 51-100         | 1        | 2.44%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD5000LPVX-00V0TT0 500GB      | 1        | 1      | 8.33%   |
| WDC WD5000BPVT-24HXZT3 500GB      | 1        | 1      | 8.33%   |
| WDC WD10EARX-00N0YB0 1TB          | 1        | 1      | 8.33%   |
| Toshiba MQ04ABF100 1TB            | 1        | 1      | 8.33%   |
| Toshiba MQ02ABF100 1TB            | 1        | 1      | 8.33%   |
| SK Hynix SH920 mSATA 128GB SSD    | 1        | 1      | 8.33%   |
| MAXTOR 6E040L0 41GB               | 1        | 1      | 8.33%   |
| Kingston SA400S37120G 120GB SSD   | 1        | 1      | 8.33%   |
| Hitachi HDS721616PLA380 164GB     | 1        | 1      | 8.33%   |
| HGST HTE721010A9E630 1TB          | 1        | 1      | 8.33%   |
| Hewlett-Packard VB0250EAVER 250GB | 1        | 2      | 8.33%   |
| Fujitsu MHV2060BH PL 64GB         | 1        | 1      | 8.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor          | Desktops | Drives | Percent |
|-----------------|----------|--------|---------|
| WDC             | 3        | 3      | 25%     |
| Toshiba         | 2        | 2      | 16.67%  |
| SK Hynix        | 1        | 1      | 8.33%   |
| MAXTOR          | 1        | 1      | 8.33%   |
| Kingston        | 1        | 1      | 8.33%   |
| Hitachi         | 1        | 1      | 8.33%   |
| HGST            | 1        | 1      | 8.33%   |
| Hewlett-Packard | 1        | 2      | 8.33%   |
| Fujitsu         | 1        | 1      | 8.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor          | Desktops | Drives | Percent |
|-----------------|----------|--------|---------|
| WDC             | 3        | 3      | 30%     |
| Toshiba         | 2        | 2      | 20%     |
| MAXTOR          | 1        | 1      | 10%     |
| Hitachi         | 1        | 1      | 10%     |
| HGST            | 1        | 1      | 10%     |
| Hewlett-Packard | 1        | 2      | 10%     |
| Fujitsu         | 1        | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 10       | 11     | 83.33%  |
| SSD  | 2        | 2      | 16.67%  |

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
| Works    | 27       | 60     | 56.25%  |
| Malfunc  | 11       | 13     | 22.92%  |
| Detected | 10       | 24     | 20.83%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 30       | 57.69%  |
| AMD                              | 8        | 15.38%  |
| Kingston Technology Company      | 4        | 7.69%   |
| Micron/Crucial Technology        | 2        | 3.85%   |
| Marvell Technology Group         | 2        | 3.85%   |
| Toshiba America Info Systems     | 1        | 1.92%   |
| Silicon Integrated Systems [SiS] | 1        | 1.92%   |
| Integrated Technology Express    | 1        | 1.92%   |
| Broadcom / LSI                   | 1        | 1.92%   |
| ASMedia Technology               | 1        | 1.92%   |
| Adaptec                          | 1        | 1.92%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 5        | 7.94%   |
| Kingston Company A2000 NVMe SSD                                                | 4        | 6.35%   |
| Intel SATA Controller [RAID mode]                                              | 4        | 6.35%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 3        | 4.76%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 3        | 4.76%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 3        | 4.76%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3        | 4.76%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 3        | 4.76%   |
| AMD 400 Series Chipset SATA Controller                                         | 3        | 4.76%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 2        | 3.17%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 2        | 3.17%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2        | 3.17%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1        | 1.59%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 1        | 1.59%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 1        | 1.59%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller               | 1        | 1.59%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller                        | 1        | 1.59%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1        | 1.59%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1        | 1.59%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1        | 1.59%   |
| Intel Atom processor C2000 AHCI SATA3 Controller                               | 1        | 1.59%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]           | 1        | 1.59%   |
| Intel 82801EB/ER (ICH5/ICH5R) IDE Controller                                   | 1        | 1.59%   |
| Intel 82801BA IDE U100 Controller                                              | 1        | 1.59%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 1        | 1.59%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1        | 1.59%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 1        | 1.59%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 1        | 1.59%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 1        | 1.59%   |
| Integrated Express IT8213 IDE Controller                                       | 1        | 1.59%   |
| Broadcom / LSI SAS1068E PCI-Express Fusion-MPT SAS                             | 1        | 1.59%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 1        | 1.59%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 1        | 1.59%   |
| AMD FCH SATA Controller [IDE mode]                                             | 1        | 1.59%   |
| AMD FCH SATA Controller D                                                      | 1        | 1.59%   |
| AMD FCH IDE Controller                                                         | 1        | 1.59%   |
| AMD 300 Series Chipset SATA Controller                                         | 1        | 1.59%   |
| Adaptec AIC-7870P/7881U [AHA-2940U/UW/D/S76]                                   | 1        | 1.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 29       | 59.18%  |
| IDE  | 9        | 18.37%  |
| NVMe | 6        | 12.24%  |
| RAID | 4        | 8.16%   |
| SCSI | 1        | 2.04%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 31       | 79.49%  |
| AMD    | 8        | 20.51%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-9400F CPU @ 2.90GHz           | 2        | 5%      |
| Intel Core i5-6400 CPU @ 2.70GHz            | 2        | 5%      |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2        | 5%      |
| AMD Ryzen 5 1600 Six-Core Processor         | 2        | 5%      |
| Intel Xeon CPU X3460 @ 2.80GHz              | 1        | 2.5%    |
| Intel Xeon CPU E3-1270 V2 @ 3.50GHz         | 1        | 2.5%    |
| Intel Xeon CPU E3-1226 v3 @ 3.30GHz         | 1        | 2.5%    |
| Intel Pentium Silver J5005 CPU @ 1.50GHz    | 1        | 2.5%    |
| Intel Pentium Gold G5420 CPU @ 3.80GHz      | 1        | 2.5%    |
| Intel Pentium Dual-Core CPU E6300 @ 2.80GHz | 1        | 2.5%    |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1        | 2.5%    |
| Intel Pentium CPU G3240 @ 3.10GHz           | 1        | 2.5%    |
| Intel Pentium 4 CPU 3.00GHz                 | 1        | 2.5%    |
| Intel Core i9-10850K CPU @ 3.60GHz          | 1        | 2.5%    |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1        | 2.5%    |
| Intel Core i7-4600U CPU @ 2.10GHz           | 1        | 2.5%    |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 2.5%    |
| Intel Core i5-7500T CPU @ 2.70GHz           | 1        | 2.5%    |
| Intel Core i5-4590T CPU @ 2.00GHz           | 1        | 2.5%    |
| Intel Core i5-4570S CPU @ 2.90GHz           | 1        | 2.5%    |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1        | 2.5%    |
| Intel Core i5-2500K CPU @ 3.30GHz           | 1        | 2.5%    |
| Intel Core i5-2500 CPU @ 3.30GHz            | 1        | 2.5%    |
| Intel Core i5-2410M CPU @ 2.30GHz           | 1        | 2.5%    |
| Intel Core i5-10400 CPU @ 2.90GHz           | 1        | 2.5%    |
| Intel Core i5 CPU 750 @ 2.67GHz             | 1        | 2.5%    |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 1        | 2.5%    |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 1        | 2.5%    |
| Intel Celeron (Coppermine)                  | 1        | 2.5%    |
| Intel Atom CPU C2750 @ 2.40GHz              | 1        | 2.5%    |
| AMD Sempron Processor 2800+                 | 1        | 2.5%    |
| AMD Ryzen 5 3600 6-Core Processor           | 1        | 2.5%    |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 1        | 2.5%    |
| AMD Ryzen 3 3100 4-Core Processor           | 1        | 2.5%    |
| AMD FX-8300 Eight-Core Processor            | 1        | 2.5%    |
| AMD A4-3300 APU with Radeon HD Graphics     | 1        | 2.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 13       | 32.5%   |
| Intel Xeon              | 3        | 7.5%    |
| Intel Core i7           | 3        | 7.5%    |
| Intel Core 2 Duo        | 3        | 7.5%    |
| AMD Ryzen 5             | 3        | 7.5%    |
| AMD Ryzen 3             | 2        | 5%      |
| Intel Pentium Silver    | 1        | 2.5%    |
| Intel Pentium Gold      | 1        | 2.5%    |
| Intel Pentium Dual-Core | 1        | 2.5%    |
| Intel Pentium Dual      | 1        | 2.5%    |
| Intel Pentium 4         | 1        | 2.5%    |
| Intel Pentium           | 1        | 2.5%    |
| Intel Core i9           | 1        | 2.5%    |
| Intel Core 2 Quad       | 1        | 2.5%    |
| Intel Celeron           | 1        | 2.5%    |
| Intel Atom              | 1        | 2.5%    |
| AMD Sempron             | 1        | 2.5%    |
| AMD FX                  | 1        | 2.5%    |
| AMD A4                  | 1        | 2.5%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 18       | 46.15%  |
| 2      | 9        | 23.08%  |
| 6      | 7        | 17.95%  |
| 1      | 3        | 7.69%   |
| 10     | 1        | 2.56%   |
| 8      | 1        | 2.56%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 39       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 24       | 61.54%  |
| 2      | 15       | 38.46%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 38       | 97.44%  |
| 32-bit         | 1        | 2.56%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 8        | 20%     |
| 0x906ea    | 3        | 7.5%    |
| 0x306c3    | 3        | 7.5%    |
| 0x306a9    | 3        | 7.5%    |
| 0x206a7    | 3        | 7.5%    |
| 0x1067a    | 3        | 7.5%    |
| 0xf49      | 1        | 2.5%    |
| 0xa0655    | 1        | 2.5%    |
| 0xa0653    | 1        | 2.5%    |
| 0x906e9    | 1        | 2.5%    |
| 0x706a1    | 1        | 2.5%    |
| 0x6fd      | 1        | 2.5%    |
| 0x686      | 1        | 2.5%    |
| 0x506e3    | 1        | 2.5%    |
| 0x406d8    | 1        | 2.5%    |
| 0x40651    | 1        | 2.5%    |
| 0x106e5    | 1        | 2.5%    |
| 0x10676    | 1        | 2.5%    |
| 0x08701021 | 1        | 2.5%    |
| 0x08701013 | 1        | 2.5%    |
| 0x08001138 | 1        | 2.5%    |
| 0x08001129 | 1        | 2.5%    |
| 0x03000027 | 1        | 2.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| KabyLake      | 5        | 12.82%  |
| Haswell       | 5        | 12.82%  |
| Penryn        | 4        | 10.26%  |
| SandyBridge   | 3        | 7.69%   |
| IvyBridge     | 3        | 7.69%   |
| Zen 2         | 2        | 5.13%   |
| Zen           | 2        | 5.13%   |
| Skylake       | 2        | 5.13%   |
| Nehalem       | 2        | 5.13%   |
| CometLake     | 2        | 5.13%   |
| Zen+          | 1        | 2.56%   |
| Silvermont    | 1        | 2.56%   |
| Piledriver    | 1        | 2.56%   |
| P6            | 1        | 2.56%   |
| NetBurst      | 1        | 2.56%   |
| K8 Hammer     | 1        | 2.56%   |
| K10 Llano     | 1        | 2.56%   |
| Goldmont plus | 1        | 2.56%   |
| Core          | 1        | 2.56%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 16       | 40%     |
| Nvidia                           | 12       | 30%     |
| AMD                              | 11       | 27.5%   |
| Silicon Integrated Systems [SiS] | 1        | 2.5%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 3        | 6.98%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3        | 6.98%   |
| Nvidia G96CGL [Quadro FX 580]                                               | 2        | 4.65%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2        | 4.65%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 4.65%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2        | 4.65%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter           | 1        | 2.33%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                       | 1        | 2.33%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 2.33%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 2.33%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 2.33%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 2.33%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                           | 1        | 2.33%   |
| Nvidia GA104 [GeForce RTX 3060 Ti]                                          | 1        | 2.33%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 2.33%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1        | 2.33%   |
| Intel HD Graphics 630                                                       | 1        | 2.33%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 1        | 2.33%   |
| Intel GeminiLake [UHD Graphics 605]                                         | 1        | 2.33%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 2.33%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                   | 1        | 2.33%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 1        | 2.33%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1        | 2.33%   |
| AMD RV350 [Radeon 9550] (Secondary)                                         | 1        | 2.33%   |
| AMD RV350 [Radeon 9550]                                                     | 1        | 2.33%   |
| AMD RV100 [Radeon 7000 / Radeon VE]                                         | 1        | 2.33%   |
| AMD RS780L [Radeon 3000]                                                    | 1        | 2.33%   |
| AMD R350 [Radeon 9800 Series]                                               | 1        | 2.33%   |
| AMD R350 [Radeon 9800 PRO] (Secondary)                                      | 1        | 2.33%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 1        | 2.33%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 1        | 2.33%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 1        | 2.33%   |
| AMD Curacao XT / Trinidad XT [Radeon R7 370 / R9 270X/370X]                 | 1        | 2.33%   |
| AMD Cedar [Radeon HD 7350/8350 / R5 220]                                    | 1        | 2.33%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 1        | 2.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| 1 x Intel   | 14       | 35.9%   |
| 1 x Nvidia  | 12       | 30.77%  |
| 1 x AMD     | 9        | 23.08%  |
| Other       | 1        | 2.56%   |
| 2 x AMD     | 1        | 2.56%   |
| 1 x SiS     | 1        | 2.56%   |
| Intel + AMD | 1        | 2.56%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 28       | 70%     |
| Proprietary | 8        | 20%     |
| Unknown     | 4        | 10%     |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 17       | 43.59%  |
| 0.01-0.5   | 7        | 17.95%  |
| 3.01-4.0   | 4        | 10.26%  |
| 0.51-1.0   | 4        | 10.26%  |
| 2.01-3.0   | 3        | 7.69%   |
| 7.01-8.0   | 2        | 5.13%   |
| 5.01-6.0   | 1        | 2.56%   |
| 1.01-2.0   | 1        | 2.56%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 10       | 25%     |
| Hewlett-Packard      | 5        | 12.5%   |
| Goldstar             | 4        | 10%     |
| Philips              | 3        | 7.5%    |
| AOC                  | 3        | 7.5%    |
| Lenovo               | 2        | 5%      |
| Iiyama               | 2        | 5%      |
| Dell                 | 2        | 5%      |
| Acer                 | 2        | 5%      |
| ViewSonic            | 1        | 2.5%    |
| Toshiba              | 1        | 2.5%    |
| HJW                  | 1        | 2.5%    |
| eMachines            | 1        | 2.5%    |
| Eizo                 | 1        | 2.5%    |
| CVT                  | 1        | 2.5%    |
| Ancor Communications | 1        | 2.5%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM0091 1600x1200 432x324mm 21.3-inch   | 2        | 4.55%   |
| Hewlett-Packard 22m HPN3575 1920x1080 476x268mm 21.5-inch              | 2        | 4.55%   |
| ViewSonic VA2261 Series VSC0F30 1920x1080 477x268mm 21.5-inch          | 1        | 2.27%   |
| Toshiba TV TSB0209 1920x1080 1594x900mm 72.1-inch                      | 1        | 2.27%   |
| Samsung Electronics T24B301 SAM098E 1920x1080 520x290mm 23.4-inch      | 1        | 2.27%   |
| Samsung Electronics SyncMaster SAM0226 1440x900 410x260mm 19.1-inch    | 1        | 2.27%   |
| Samsung Electronics SyncMaster SAM0029 1280x1024 312x234mm 15.4-inch   | 1        | 2.27%   |
| Samsung Electronics S/T 77/76BDF STN0007 1280x1024 312x234mm 15.4-inch | 1        | 2.27%   |
| Samsung Electronics LCD Monitor SyncMaster 1280x1024                   | 1        | 2.27%   |
| Samsung Electronics LCD Monitor SyncMaster                             | 1        | 2.27%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 700x390mm 31.5-inch  | 1        | 2.27%   |
| Samsung Electronics LCD Monitor SA300/350/360                          | 1        | 2.27%   |
| Samsung Electronics LCD Monitor S24D340                                | 1        | 2.27%   |
| Samsung Electronics LCD Monitor C27F390 5760x1080                      | 1        | 2.27%   |
| Samsung Electronics C27F398 SAM0D45 1920x1080 598x336mm 27.0-inch      | 1        | 2.27%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch                | 1        | 2.27%   |
| Philips 190B PHL086C 1280x1024 376x301mm 19.0-inch                     | 1        | 2.27%   |
| Philips 17S PHL0877 1280x1024 337x270mm 17.0-inch                      | 1        | 2.27%   |
| Lenovo LI2215sD LEN65CC 1920x1080 476x267mm 21.5-inch                  | 1        | 2.27%   |
| Lenovo LCD Monitor LEN40A0 1366x768 309x174mm 14.0-inch                | 1        | 2.27%   |
| Iiyama PLX2483H IVM6114 1920x1080 531x299mm 24.0-inch                  | 1        | 2.27%   |
| Iiyama PLB2712HDS IVM6602 1920x1080 598x336mm 27.0-inch                | 1        | 2.27%   |
| HJW HDMI TO USB HJW0001 1920x1080 700x390mm 31.5-inch                  | 1        | 2.27%   |
| Hewlett-Packard LA2206 HWP2947 1920x1080 476x268mm 21.5-inch           | 1        | 2.27%   |
| Hewlett-Packard L2245w HWP26FC 1680x1050 473x296mm 22.0-inch           | 1        | 2.27%   |
| Hewlett-Packard Compaq S2321a HWP2915 1920x1080 509x286mm 23.0-inch    | 1        | 2.27%   |
| Hewlett-Packard 22cw HWP3183 1920x1080 476x268mm 21.5-inch             | 1        | 2.27%   |
| Goldstar W2243 GSM56FF 1920x1080 477x269mm 21.6-inch                   | 1        | 2.27%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                | 1        | 2.27%   |
| Goldstar L1730S GSM438D 1280x1024 338x270mm 17.0-inch                  | 1        | 2.27%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 1        | 2.27%   |
| eMachines E19T6W EMA0783 1440x900 410x260mm 19.1-inch                  | 1        | 2.27%   |
| Eizo EV2456 ENC2798 1920x1200 520x330mm 24.2-inch                      | 1        | 2.27%   |
| Dell P2719H DEL4184 1920x1080 598x336mm 27.0-inch                      | 1        | 2.27%   |
| Dell LCD Monitor P1914S 1280x1024                                      | 1        | 2.27%   |
| CVT LCD Monitor CVT4668 1440x900 360x290mm 18.2-inch                   | 1        | 2.27%   |
| AOC U2790B AOC2790 3840x2160 600x340mm 27.2-inch                       | 1        | 2.27%   |
| AOC Q32G1WG4 AOC3201 2560x1440 697x393mm 31.5-inch                     | 1        | 2.27%   |
| AOC 1950w AOC1950 1366x768 410x230mm 18.5-inch                         | 1        | 2.27%   |
| Ancor Communications ASUS VW190 ACI19E9 1366x768 410x230mm 18.5-inch   | 1        | 2.27%   |
| Acer VG220Q ACR06D8 1920x1080 476x268mm 21.5-inch                      | 1        | 2.27%   |
| Acer V206HQL ACR0334 1366x768 434x236mm 19.4-inch                      | 1        | 2.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 17       | 42.5%   |
| 1280x1024 (SXGA)   | 5        | 12.5%   |
| 3840x2160 (4K)     | 4        | 10%     |
| 1440x900 (WXGA+)   | 3        | 7.5%    |
| 1366x768 (WXGA)    | 3        | 7.5%    |
| 1600x1200          | 2        | 5%      |
| Unknown            | 2        | 5%      |
| 5760x1080          | 1        | 2.5%    |
| 1920x1200 (WUXGA)  | 1        | 2.5%    |
| 1680x1050 (WSXGA+) | 1        | 2.5%    |
| 1600x900 (HD+)     | 1        | 2.5%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 12       | 31.58%  |
| 27      | 4        | 10.53%  |
| 19      | 3        | 7.89%   |
| 18      | 3        | 7.89%   |
| 31      | 2        | 5.26%   |
| 24      | 2        | 5.26%   |
| 23      | 2        | 5.26%   |
| 17      | 2        | 5.26%   |
| 15      | 2        | 5.26%   |
| Unknown | 2        | 5.26%   |
| 72      | 1        | 2.63%   |
| 54      | 1        | 2.63%   |
| 22      | 1        | 2.63%   |
| 14      | 1        | 2.63%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 15       | 42.86%  |
| 501-600     | 8        | 22.86%  |
| 301-350     | 4        | 11.43%  |
| 601-700     | 2        | 5.71%   |
| 351-400     | 2        | 5.71%   |
| Unknown     | 2        | 5.71%   |
| 1501-2000   | 1        | 2.86%   |
| 1001-1500   | 1        | 2.86%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 22       | 59.46%  |
| 16/10   | 5        | 13.51%  |
| 4/3     | 4        | 10.81%  |
| 5/4     | 3        | 8.11%   |
| Unknown | 2        | 5.41%   |
| 6/5     | 1        | 2.7%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 11       | 29.73%  |
| 151-200        | 8        | 21.62%  |
| 301-350        | 4        | 10.81%  |
| 141-150        | 4        | 10.81%  |
| More than 1000 | 2        | 5.41%   |
| 351-500        | 2        | 5.41%   |
| 111-120        | 2        | 5.41%   |
| Unknown        | 2        | 5.41%   |
| 81-90          | 1        | 2.7%    |
| 251-300        | 1        | 2.7%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 19       | 51.35%  |
| 101-120 | 14       | 37.84%  |
| 1-50    | 2        | 5.41%   |
| Unknown | 2        | 5.41%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 30       | 76.92%  |
| 3     | 3        | 7.69%   |
| 2     | 3        | 7.69%   |
| 0     | 3        | 7.69%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 23       | 46.94%  |
| Intel                            | 17       | 34.69%  |
| Qualcomm Atheros                 | 3        | 6.12%   |
| Marvell Technology Group         | 2        | 4.08%   |
| TP-Link                          | 1        | 2.04%   |
| Silicon Integrated Systems [SiS] | 1        | 2.04%   |
| Ralink Technology                | 1        | 2.04%   |
| JMicron Technology               | 1        | 2.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 20       | 39.22%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 5.88%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 3.92%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1        | 1.96%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1        | 1.96%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 1        | 1.96%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1        | 1.96%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 1.96%   |
| Ralink MT7601U Wireless Adapter                                   | 1        | 1.96%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 1.96%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1        | 1.96%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter        | 1        | 1.96%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1        | 1.96%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 1.96%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1        | 1.96%   |
| Intel Wireless 7260                                               | 1        | 1.96%   |
| Intel Ethernet Connection I354 2.5 GbE Backplane                  | 1        | 1.96%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.96%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 1.96%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 1.96%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 1.96%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 1.96%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1        | 1.96%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 1.96%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 1.96%   |
| Intel 82576 Gigabit Network Connection                            | 1        | 1.96%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 1.96%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)        | 1        | 1.96%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 1.96%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 2        | 25%     |
| Qualcomm Atheros      | 2        | 25%     |
| Intel                 | 2        | 25%     |
| TP-Link               | 1        | 12.5%   |
| Ralink Technology     | 1        | 12.5%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]               | 1        | 12.5%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter    | 1        | 12.5%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                 | 1        | 12.5%   |
| Ralink MT7601U Wireless Adapter                            | 1        | 12.5%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter           | 1        | 12.5%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter | 1        | 12.5%   |
| Intel Wireless 7260                                        | 1        | 12.5%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 1        | 12.5%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 21       | 50%     |
| Intel                            | 16       | 38.1%   |
| Marvell Technology Group         | 2        | 4.76%   |
| Silicon Integrated Systems [SiS] | 1        | 2.38%   |
| Qualcomm Atheros                 | 1        | 2.38%   |
| JMicron Technology               | 1        | 2.38%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 20       | 46.51%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 6.98%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 4.65%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1        | 2.33%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 2.33%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 2.33%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1        | 2.33%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 2.33%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1        | 2.33%   |
| Intel Ethernet Connection I354 2.5 GbE Backplane                  | 1        | 2.33%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 2.33%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 2.33%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 2.33%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 2.33%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 2.33%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 2.33%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 2.33%   |
| Intel 82576 Gigabit Network Connection                            | 1        | 2.33%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 2.33%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)        | 1        | 2.33%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 2.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 38       | 82.61%  |
| WiFi     | 8        | 17.39%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 33       | 84.62%  |
| WiFi     | 6        | 15.38%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 27       | 67.5%   |
| 2     | 10       | 25%     |
| 5     | 1        | 2.5%    |
| 3     | 1        | 2.5%    |
| 0     | 1        | 2.5%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 38       | 97.44%  |
| Yes  | 1        | 2.56%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Qualcomm Atheros Communications | 2        | 50%     |
| Intel                           | 2        | 50%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Qualcomm Atheros  Bluetooth Device | 1        | 25%     |
| Qualcomm Atheros AR3011 Bluetooth  | 1        | 25%     |
| Intel Wireless-AC 3168 Bluetooth   | 1        | 25%     |
| Intel Bluetooth wireless interface | 1        | 25%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 27       | 45.76%  |
| Nvidia                           | 10       | 16.95%  |
| AMD                              | 10       | 16.95%  |
| Plantronics                      | 2        | 3.39%   |
| Creative Labs                    | 2        | 3.39%   |
| Texas Instruments                | 1        | 1.69%   |
| TEAC                             | 1        | 1.69%   |
| Silicon Integrated Systems [SiS] | 1        | 1.69%   |
| M-Audio                          | 1        | 1.69%   |
| Logitech                         | 1        | 1.69%   |
| KORG                             | 1        | 1.69%   |
| Elite Silicon                    | 1        | 1.69%   |
| Cirrus Logic                     | 1        | 1.69%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Nvidia GP106 High Definition Audio Controller                              | 4        | 5.8%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4        | 5.8%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4        | 5.8%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3        | 4.35%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3        | 4.35%   |
| Intel Cannon Lake PCH cAVS                                                 | 3        | 4.35%   |
| Plantronics HD1                                                            | 2        | 2.9%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2        | 2.9%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2        | 2.9%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2        | 2.9%    |
| Intel 200 Series PCH HD Audio                                              | 2        | 2.9%    |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]  | 2        | 2.9%    |
| AMD Starship/Matisse HD Audio Controller                                   | 2        | 2.9%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 2        | 2.9%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 2        | 2.9%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2        | 2.9%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2        | 2.9%    |
| Texas Instruments PCM2902 Audio Codec                                      | 1        | 1.45%   |
| TEAC US-1800                                                               | 1        | 1.45%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 1        | 1.45%   |
| Nvidia High Definition Audio Controller                                    | 1        | 1.45%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 1.45%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1        | 1.45%   |
| Nvidia GA104 High Definition Audio Controller                              | 1        | 1.45%   |
| M-Audio MIDISPORT 4x4 Anniv                                                | 1        | 1.45%   |
| M-Audio M-Audio 1x1                                                        | 1        | 1.45%   |
| Logitech H390 headset with microphone                                      | 1        | 1.45%   |
| KORG nanoKONTROL studio controller                                         | 1        | 1.45%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1        | 1.45%   |
| Intel Comet Lake PCH cAVS                                                  | 1        | 1.45%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1        | 1.45%   |
| Intel Audio device                                                         | 1        | 1.45%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1        | 1.45%   |
| Intel 82801BA/BAM AC'97 Audio Controller                                   | 1        | 1.45%   |
| Intel 8 Series HD Audio Controller                                         | 1        | 1.45%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1        | 1.45%   |
| Elite Silicon USB Audio Device                                             | 1        | 1.45%   |
| Cirrus Logic Crystal CS4281 PCI Audio                                      | 1        | 1.45%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1        | 1.45%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1        | 1.45%   |
| AMD FCH Azalia Controller                                                  | 1        | 1.45%   |
| AMD Family 17h/19h HD Audio Controller                                     | 1        | 1.45%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 1        | 1.45%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 12       | 27.91%  |
| Kingston            | 9        | 20.93%  |
| Corsair             | 5        | 11.63%  |
| Micron Technology   | 4        | 9.3%    |
| SK Hynix            | 3        | 6.98%   |
| Samsung Electronics | 2        | 4.65%   |
| Nanya Technology    | 2        | 4.65%   |
| G.Skill             | 2        | 4.65%   |
| GOODRAM             | 1        | 2.33%   |
| Crucial             | 1        | 2.33%   |
| Avant               | 1        | 2.33%   |
| A-DATA Technology   | 1        | 2.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s     | 2        | 4.08%   |
| Corsair RAM CMK32GX4M4A2666C16 8GB DIMM DDR4 2667MT/s     | 2        | 4.08%   |
| Unknown RAM SM3S320SD0488CABC 8192MB SODIMM DDR3 1600MT/s | 1        | 2.04%   |
| Unknown RAM Module 8192MB DIMM DDR3 800MT/s               | 1        | 2.04%   |
| Unknown RAM Module 64MB DIMM DRAM 100MT/s                 | 1        | 2.04%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                      | 1        | 2.04%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s            | 1        | 2.04%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s              | 1        | 2.04%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                      | 1        | 2.04%   |
| Unknown RAM Module 256MB DIMM DRAM 100MT/s                | 1        | 2.04%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s             | 1        | 2.04%   |
| Unknown RAM Module 2048MB DIMM SDRAM 667MT/s              | 1        | 2.04%   |
| Unknown RAM Module 2048MB DIMM SDRAM                      | 1        | 2.04%   |
| Unknown RAM Module 128MB DIMM DRAM 100MT/s                | 1        | 2.04%   |
| Unknown RAM Module 1024MB DIMM DDR 400MT/s                | 1        | 2.04%   |
| Unknown RAM Module 1024MB DIMM DDR                        | 1        | 2.04%   |
| Unknown RAM 3000 C16 Series 8192MB DIMM DDR4 2133MT/s     | 1        | 2.04%   |
| SK Hynix RAM Module 4GB DIMM DDR3 1333MT/s                | 1        | 2.04%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s   | 1        | 2.04%   |
| SK Hynix RAM HMA81GU6JJR8N-VK 8GB DIMM DDR4 2666MT/s      | 1        | 2.04%   |
| Samsung RAM Module 2GB DIMM DDR3 1333MT/s                 | 1        | 2.04%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s       | 1        | 2.04%   |
| Nanya RAM Module 2GB DIMM DDR3 1333MT/s                   | 1        | 2.04%   |
| Nanya RAM M2X4G64CB8HG5N-DG 4096MB DIMM DDR3 1867MT/s     | 1        | 2.04%   |
| Micron RAM Module 2GB DIMM DDR3 1333MT/s                  | 1        | 2.04%   |
| Micron RAM DVM64453C DATARAM 8GB DIMM DDR3 1600MT/s       | 1        | 2.04%   |
| Micron RAM 8JTF51264AZ-1G6E1 4096MB DIMM DDR3 1600MT/s    | 1        | 2.04%   |
| Micron RAM 4ATF51264HZ-2G3E1 4GB SODIMM DDR4 2667MT/s     | 1        | 2.04%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s    | 1        | 2.04%   |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 2667MT/s       | 1        | 2.04%   |
| Kingston RAM KHX2133C14/8G 8192MB DIMM DDR4 2400MT/s      | 1        | 2.04%   |
| Kingston RAM KHX1600C9D3/4GX 4096MB DIMM DDR3 2400MT/s    | 1        | 2.04%   |
| Kingston RAM 99U5704-001.A00G 4GB SODIMM DDR4 2400MT/s    | 1        | 2.04%   |
| Kingston RAM 99U5702-094.A00G 8192MB DIMM DDR4 2400MT/s   | 1        | 2.04%   |
| Kingston RAM 99U5471-066.A00LF 8GB DIMM DDR3 1600MT/s     | 1        | 2.04%   |
| Kingston RAM 9905711-015.A00G 4GB SODIMM DDR4 2400MT/s    | 1        | 2.04%   |
| Kingston RAM 9905625-066.A00G 16GB DIMM DDR4 2667MT/s     | 1        | 2.04%   |
| Kingston RAM 9905471-084.A00LF 8192MB DIMM DDR3 1600MT/s  | 1        | 2.04%   |
| GOODRAM RAM GR1333D364L9/4G 4GB DIMM DDR3 1600MT/s        | 1        | 2.04%   |
| G.Skill RAM F4-3200C16-16GIS 16384MB DIMM DDR4 3600MT/s   | 1        | 2.04%   |
| G.Skill RAM F4-2133C15-16GIS 16384MB DIMM DDR4 2133MT/s   | 1        | 2.04%   |
| Crucial RAM CT51264BA160BJ.C8 4GB DIMM DDR3 1600MT/s      | 1        | 2.04%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s     | 1        | 2.04%   |
| Corsair RAM CMD8GX3M2B2133C9 4096MB DIMM DDR3 1333MT/s    | 1        | 2.04%   |
| Corsair RAM CM4X16GE2400C16K4 16GB DIMM DDR4 2400MT/s     | 1        | 2.04%   |
| Avant RAM F6451U67F9333G 4096MB DIMM DDR3 1333MT/s        | 1        | 2.04%   |
| A-DATA RAM DDR4 2666 2OZ 4GB DIMM DDR4 2667MT/s           | 1        | 2.04%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 14       | 40%     |
| DDR3    | 14       | 40%     |
| SDRAM   | 2        | 5.71%   |
| DDR     | 2        | 5.71%   |
| DRAM    | 1        | 2.86%   |
| DDR2    | 1        | 2.86%   |
| Unknown | 1        | 2.86%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 30       | 85.71%  |
| SODIMM | 5        | 14.29%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 12       | 29.27%  |
| 4096  | 12       | 29.27%  |
| 16384 | 6        | 14.63%  |
| 2048  | 5        | 12.2%   |
| 1024  | 2        | 4.88%   |
| 32768 | 1        | 2.44%   |
| 256   | 1        | 2.44%   |
| 128   | 1        | 2.44%   |
| 64    | 1        | 2.44%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 7        | 18.42%  |
| 2667    | 5        | 13.16%  |
| 2400    | 5        | 13.16%  |
| 1333    | 5        | 13.16%  |
| 3600    | 3        | 7.89%   |
| 2133    | 2        | 5.26%   |
| 667     | 2        | 5.26%   |
| Unknown | 2        | 5.26%   |
| 3200    | 1        | 2.63%   |
| 2666    | 1        | 2.63%   |
| 1867    | 1        | 2.63%   |
| 1800    | 1        | 2.63%   |
| 800     | 1        | 2.63%   |
| 400     | 1        | 2.63%   |
| 100     | 1        | 2.63%   |

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


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Z-Star Microelectronics | 1        | 12.5%   |
| Softkinetic             | 1        | 12.5%   |
| Microsoft               | 1        | 12.5%   |
| Microdia                | 1        | 12.5%   |
| MacroSilicon            | 1        | 12.5%   |
| Logitech                | 1        | 12.5%   |
| GEMBIRD                 | 1        | 12.5%   |
| Cubeternet              | 1        | 12.5%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Z-Star Vimicro USB Camera (Altair) | 1        | 12.5%   |
| Softkinetic DepthSense 325         | 1        | 12.5%   |
| Microsoft LifeCam Studio           | 1        | 12.5%   |
| Microdia Camera                    | 1        | 12.5%   |
| MacroSilicon USB Video             | 1        | 12.5%   |
| Logitech Webcam C270               | 1        | 12.5%   |
| GEMBIRD USB2.0 PC CAMERA           | 1        | 12.5%   |
| Cubeternet GL-UPC822 UVC WebCam    | 1        | 12.5%   |

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
| 0     | 34       | 87.18%  |
| 1     | 4        | 10.26%  |
| 2     | 1        | 2.56%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 4        | 66.67%  |
| Firewire controller      | 1        | 16.67%  |
| Communication controller | 1        | 16.67%  |

