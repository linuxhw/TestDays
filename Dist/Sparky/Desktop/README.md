Sparky - Tested Hardware & Statistics (Desktops)
------------------------------------------------

A project to collect tested hardware configurations for Sparky.

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

Total: 40

| Vendor   | Model                | Probe                                                      | Date         |
|----------|----------------------|------------------------------------------------------------|--------------|
| Dell     | 0YXT71 A01           | [aa6781c002](https://linux-hardware.org/?probe=aa6781c002) | Aug 18, 2023 |
| ASUSTek  | M5A78L-M LX/BR       | [90c03881ae](https://linux-hardware.org/?probe=90c03881ae) | Jul 29, 2023 |
| Dell     | 0GDG8Y A00           | [f0fdd509f7](https://linux-hardware.org/?probe=f0fdd509f7) | Jun 29, 2023 |
| ASUSTek  | M4N68T-M             | [f0b58c9f4e](https://linux-hardware.org/?probe=f0b58c9f4e) | Jun 12, 2023 |
| ASRock   | FM2A58M-VG3+ R2.0    | [3e4b7afb1e](https://linux-hardware.org/?probe=3e4b7afb1e) | Jun 10, 2023 |
| HP       | 1589                 | [af8e129ecd](https://linux-hardware.org/?probe=af8e129ecd) | May 04, 2023 |
| HP       | 1589                 | [632f486421](https://linux-hardware.org/?probe=632f486421) | Apr 27, 2023 |
| HP       | 0A5Ch                | [636d94a346](https://linux-hardware.org/?probe=636d94a346) | Apr 15, 2023 |
| Acer     | Aspire X3470         | [659a1f31bd](https://linux-hardware.org/?probe=659a1f31bd) | Feb 22, 2023 |
| Foxconn  | 2ABF                 | [90af9a1be5](https://linux-hardware.org/?probe=90af9a1be5) | Dec 06, 2022 |
| Foxconn  | 2ABF                 | [09a9309a2a](https://linux-hardware.org/?probe=09a9309a2a) | Nov 30, 2022 |
| Foxconn  | 2ABF                 | [b585d891a8](https://linux-hardware.org/?probe=b585d891a8) | Nov 30, 2022 |
| ASUSTek  | G20AJ                | [7e1557713a](https://linux-hardware.org/?probe=7e1557713a) | Sep 06, 2022 |
| Gigabyte | X570S AORUS PRO AX   | [4fb948980f](https://linux-hardware.org/?probe=4fb948980f) | Aug 25, 2022 |
| ASUSTek  | CROSSHAIR VI HERO    | [f5e7afea43](https://linux-hardware.org/?probe=f5e7afea43) | Jul 05, 2022 |
| Intel    | H61                  | [bf862f44d2](https://linux-hardware.org/?probe=bf862f44d2) | Jun 11, 2022 |
| ASUSTek  | CROSSHAIR VI HERO    | [803d13c6ca](https://linux-hardware.org/?probe=803d13c6ca) | May 15, 2022 |
| HP       | 3641h                | [d50fc13ff0](https://linux-hardware.org/?probe=d50fc13ff0) | Mar 30, 2022 |
| Intel    | H55                  | [baff4758b7](https://linux-hardware.org/?probe=baff4758b7) | Mar 21, 2022 |
| ASUSTek  | CROSSHAIR VI HERO    | [39dcd3854f](https://linux-hardware.org/?probe=39dcd3854f) | Feb 03, 2022 |
| MSI      | B450 GAMING PLUS MAX | [47eae3d6b2](https://linux-hardware.org/?probe=47eae3d6b2) | Jan 19, 2022 |
| MSI      | H310M PRO-VDH PLUS   | [079af91b8f](https://linux-hardware.org/?probe=079af91b8f) | Aug 22, 2021 |
| MSI      | H310M PRO-VDH PLUS   | [c6fe94a0ba](https://linux-hardware.org/?probe=c6fe94a0ba) | Aug 22, 2021 |
| HP       | 805B                 | [d6c2730444](https://linux-hardware.org/?probe=d6c2730444) | Jul 12, 2021 |
| Gigabyte | H97-Gaming 3         | [d8b0632698](https://linux-hardware.org/?probe=d8b0632698) | May 23, 2021 |
| MSI      | A68HM-E33 V2         | [82a06b4bea](https://linux-hardware.org/?probe=82a06b4bea) | Feb 21, 2021 |
| Gigabyte | H410M H              | [ee13368ccf](https://linux-hardware.org/?probe=ee13368ccf) | Feb 18, 2021 |
| Pegatron | 2AC2A                | [8a5448bc07](https://linux-hardware.org/?probe=8a5448bc07) | Jan 17, 2021 |
| Pegatron | 2AC2A                | [c76bbefc71](https://linux-hardware.org/?probe=c76bbefc71) | Jan 09, 2021 |
| Pegatron | 2AC2A                | [95ead72109](https://linux-hardware.org/?probe=95ead72109) | Dec 17, 2020 |
| HP       | 8056                 | [79fd2c8837](https://linux-hardware.org/?probe=79fd2c8837) | Dec 12, 2020 |
| Intel    | DG41TY AAE47335-300  | [e3457f83fa](https://linux-hardware.org/?probe=e3457f83fa) | Oct 22, 2020 |
| Gigabyte | M68M-S2P             | [0e4bab3503](https://linux-hardware.org/?probe=0e4bab3503) | Oct 05, 2020 |
| Unknown  | 4CoreDX90-VSTA       | [31dbedff45](https://linux-hardware.org/?probe=31dbedff45) | Sep 10, 2020 |
| Gigabyte | G41M-ES2L            | [87c93c4148](https://linux-hardware.org/?probe=87c93c4148) | Jun 21, 2020 |
| Gigabyte | G41M-ES2L            | [01beb1ea00](https://linux-hardware.org/?probe=01beb1ea00) | Jun 21, 2020 |
| Dell     | 039VR8 A00           | [d386006ad9](https://linux-hardware.org/?probe=d386006ad9) | Jun 15, 2020 |
| Vorke    | V1 Plus              | [e371a7cf42](https://linux-hardware.org/?probe=e371a7cf42) | Mar 29, 2020 |
| Intel    | DG43RK AAE78175-402  | [262ba9568a](https://linux-hardware.org/?probe=262ba9568a) | Mar 22, 2020 |
| ASRock   | H61M-VG4             | [93ae8e7a8c](https://linux-hardware.org/?probe=93ae8e7a8c) | Aug 18, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Sparky 6    | 7        | 24.14%  |
| Sparky 7    | 5        | 17.24%  |
| Sparky 5.12 | 3        | 10.34%  |
| Sparky 7.0  | 2        | 6.9%    |
| Sparky 6.3  | 2        | 6.9%    |
| Sparky 6.2  | 2        | 6.9%    |
| Sparky 6.1  | 2        | 6.9%    |
| Sparky 8    | 1        | 3.45%   |
| Sparky 6.7  | 1        | 3.45%   |
| Sparky 6.6  | 1        | 3.45%   |
| Sparky 6.5  | 1        | 3.45%   |
| Sparky 6.0  | 1        | 3.45%   |
| Sparky 5.10 | 1        | 3.45%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Sparky | 27       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Desktops | Percent |
|---------------------------|----------|---------|
| 6.4.0-1-amd64             | 1        | 3.33%   |
| 6.1.0-9-amd64             | 1        | 3.33%   |
| 6.1.0-7-amd64             | 1        | 3.33%   |
| 6.1.0-3-amd64             | 1        | 3.33%   |
| 6.1.0-11-amd64            | 1        | 3.33%   |
| 6.0.11-x64v2-rt14-xanmod1 | 1        | 3.33%   |
| 6.0.0-5-amd64             | 1        | 3.33%   |
| 5.9.13-sparky-amd64       | 1        | 3.33%   |
| 5.7.2-sparky-amd64        | 1        | 3.33%   |
| 5.6.0-2-amd64             | 1        | 3.33%   |
| 5.18.3-sparky-amd64       | 1        | 3.33%   |
| 5.18.0-4-amd64            | 1        | 3.33%   |
| 5.18.0-2-amd64            | 1        | 3.33%   |
| 5.17.3-sparky-amd64       | 1        | 3.33%   |
| 5.16.5-sparky-amd64       | 1        | 3.33%   |
| 5.10.0-9-amd64            | 1        | 3.33%   |
| 5.10.0-8-amd64            | 1        | 3.33%   |
| 5.10.0-7-amd64            | 1        | 3.33%   |
| 5.10.0-6-amd64            | 1        | 3.33%   |
| 5.10.0-3-amd64            | 1        | 3.33%   |
| 5.10.0-23-amd64           | 1        | 3.33%   |
| 5.10.0-21-amd64           | 1        | 3.33%   |
| 5.10.0-2-amd64            | 1        | 3.33%   |
| 5.10.0-14-amd64           | 1        | 3.33%   |
| 5.10.0-12-amd64           | 1        | 3.33%   |
| 5.10.0-11-686             | 1        | 3.33%   |
| 4.19.0-8-amd64            | 1        | 3.33%   |
| 4.19.0-12-amd64           | 1        | 3.33%   |
| 4.19.0-10-amd64           | 1        | 3.33%   |
| 4.19.0-10-686             | 1        | 3.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10.0  | 11       | 36.67%  |
| 6.1.0   | 4        | 13.33%  |
| 4.19.0  | 4        | 13.33%  |
| 5.18.0  | 2        | 6.67%   |
| 6.4.0   | 1        | 3.33%   |
| 6.0.11  | 1        | 3.33%   |
| 6.0.0   | 1        | 3.33%   |
| 5.9.13  | 1        | 3.33%   |
| 5.7.2   | 1        | 3.33%   |
| 5.6.0   | 1        | 3.33%   |
| 5.18.3  | 1        | 3.33%   |
| 5.17.3  | 1        | 3.33%   |
| 5.16.5  | 1        | 3.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 11       | 37.93%  |
| 6.1     | 4        | 13.79%  |
| 4.19    | 4        | 13.79%  |
| 5.18    | 3        | 10.34%  |
| 6.4     | 1        | 3.45%   |
| 6.0     | 1        | 3.45%   |
| 5.9     | 1        | 3.45%   |
| 5.7     | 1        | 3.45%   |
| 5.6     | 1        | 3.45%   |
| 5.17    | 1        | 3.45%   |
| 5.16    | 1        | 3.45%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 25       | 92.59%  |
| i686   | 2        | 7.41%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| XFCE             | 12       | 44.44%  |
| LXQt             | 7        | 25.93%  |
| X-Cinnamon       | 2        | 7.41%   |
| KDE5             | 2        | 7.41%   |
| lightdm-xsession | 1        | 3.7%    |
| ICEWM            | 1        | 3.7%    |
| GNOME            | 1        | 3.7%    |
| Unknown          | 1        | 3.7%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 27       | 96.43%  |
| Tty  | 1        | 3.57%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 10       | 37.04%  |
| SDDM    | 7        | 25.93%  |
| TDM     | 6        | 22.22%  |
| LightDM | 4        | 14.81%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 6        | 22.22%  |
| pt_BR | 5        | 18.52%  |
| en_GB | 4        | 14.81%  |
| fr_FR | 2        | 7.41%   |
| es_ES | 2        | 7.41%   |
| sv_SE | 1        | 3.7%    |
| es_US | 1        | 3.7%    |
| es_AR | 1        | 3.7%    |
| en_ZA | 1        | 3.7%    |
| en_DK | 1        | 3.7%    |
| en_CA | 1        | 3.7%    |
| de_CH | 1        | 3.7%    |
| cs_CZ | 1        | 3.7%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 18       | 66.67%  |
| EFI  | 9        | 33.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Ext4  | 25       | 92.59%  |
| Zfs   | 1        | 3.7%    |
| Btrfs | 1        | 3.7%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 10       | 37.04%  |
| MBR     | 9        | 33.33%  |
| GPT     | 8        | 29.63%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 21       | 77.78%  |
| Yes       | 6        | 22.22%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 19       | 70.37%  |
| Yes       | 8        | 29.63%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 5        | 18.52%  |
| Gigabyte Technology | 5        | 18.52%  |
| Intel               | 4        | 14.81%  |
| ASUSTek Computer    | 4        | 14.81%  |
| MSI                 | 3        | 11.11%  |
| Dell                | 3        | 11.11%  |
| Foxconn             | 1        | 3.7%    |
| Acer                | 1        | 3.7%    |
| Unknown             | 1        | 3.7%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| MSI MS-7C09                         | 1        | 3.7%    |
| MSI MS-7B86                         | 1        | 3.7%    |
| MSI MS-7721                         | 1        | 3.7%    |
| Intel H61                           | 1        | 3.7%    |
| Intel H55                           | 1        | 3.7%    |
| Intel DG43RK AAE78175-402           | 1        | 3.7%    |
| Intel DG41TY AAE47335-300           | 1        | 3.7%    |
| HP Z420 Workstation                 | 1        | 3.7%    |
| HP t5740                            | 1        | 3.7%    |
| HP EliteDesk 800 G2 DM 65W          | 1        | 3.7%    |
| HP EliteDesk 705 G2 MINI            | 1        | 3.7%    |
| HP Compaq dc7700 Ultra-slim Desktop | 1        | 3.7%    |
| Gigabyte X570S AORUS PRO AX         | 1        | 3.7%    |
| Gigabyte M68M-S2P                   | 1        | 3.7%    |
| Gigabyte H97-Gaming 3               | 1        | 3.7%    |
| Gigabyte H410M H                    | 1        | 3.7%    |
| Gigabyte G41M-ES2L                  | 1        | 3.7%    |
| Foxconn p6-2010fr                   | 1        | 3.7%    |
| Dell OptiPlex 7010                  | 1        | 3.7%    |
| Dell OptiPlex 580                   | 1        | 3.7%    |
| Dell Inspiron 620                   | 1        | 3.7%    |
| ASUS M5A78L-M LX/BR                 | 1        | 3.7%    |
| ASUS M4N68T-M                       | 1        | 3.7%    |
| ASUS G20AJ                          | 1        | 3.7%    |
| ASUS CROSSHAIR VI HERO              | 1        | 3.7%    |
| Acer Aspire X3470                   | 1        | 3.7%    |
| Unknown                             | 1        | 3.7%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| HP EliteDesk        | 2        | 7.41%   |
| Dell OptiPlex       | 2        | 7.41%   |
| MSI MS-7C09         | 1        | 3.7%    |
| MSI MS-7B86         | 1        | 3.7%    |
| MSI MS-7721         | 1        | 3.7%    |
| Intel H61           | 1        | 3.7%    |
| Intel H55           | 1        | 3.7%    |
| Intel DG43RK        | 1        | 3.7%    |
| Intel DG41TY        | 1        | 3.7%    |
| HP Z420             | 1        | 3.7%    |
| HP t5740            | 1        | 3.7%    |
| HP Compaq           | 1        | 3.7%    |
| Gigabyte X570S      | 1        | 3.7%    |
| Gigabyte M68M-S2P   | 1        | 3.7%    |
| Gigabyte H97-Gaming | 1        | 3.7%    |
| Gigabyte H410M      | 1        | 3.7%    |
| Gigabyte G41M-ES2L  | 1        | 3.7%    |
| Foxconn p6-2010fr   | 1        | 3.7%    |
| Dell Inspiron       | 1        | 3.7%    |
| ASUS M5A78L-M       | 1        | 3.7%    |
| ASUS M4N68T-M       | 1        | 3.7%    |
| ASUS G20AJ          | 1        | 3.7%    |
| ASUS CROSSHAIR      | 1        | 3.7%    |
| Acer Aspire         | 1        | 3.7%    |
| Unknown             | 1        | 3.7%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2009 | 5        | 18.52%  |
| 2011 | 4        | 14.81%  |
| 2014 | 3        | 11.11%  |
| 2021 | 2        | 7.41%   |
| 2018 | 2        | 7.41%   |
| 2015 | 2        | 7.41%   |
| 2012 | 2        | 7.41%   |
| 2007 | 2        | 7.41%   |
| 2020 | 1        | 3.7%    |
| 2019 | 1        | 3.7%    |
| 2017 | 1        | 3.7%    |
| 2013 | 1        | 3.7%    |
| 2010 | 1        | 3.7%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 27       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 27       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 27       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 3.01-4.0   | 8        | 29.63%  |
| 16.01-24.0 | 6        | 22.22%  |
| 8.01-16.0  | 6        | 22.22%  |
| 4.01-8.0   | 3        | 11.11%  |
| 1.01-2.0   | 2        | 7.41%   |
| 24.01-32.0 | 1        | 3.7%    |
| 2.01-3.0   | 1        | 3.7%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1.01-2.0 | 18       | 62.07%  |
| 2.01-3.0 | 5        | 17.24%  |
| 4.01-8.0 | 3        | 10.34%  |
| 0.51-1.0 | 2        | 6.9%    |
| 3.01-4.0 | 1        | 3.45%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 17       | 56.67%  |
| 2      | 7        | 23.33%  |
| 4      | 3        | 10%     |
| 6      | 2        | 6.67%   |
| 3      | 1        | 3.33%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 19       | 70.37%  |
| Yes       | 8        | 29.63%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 26       | 96.3%   |
| No        | 1        | 3.7%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 18       | 66.67%  |
| Yes       | 9        | 33.33%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 22       | 81.48%  |
| Yes       | 5        | 18.52%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Brazil       | 5        | 18.52%  |
| UK           | 3        | 11.11%  |
| France       | 3        | 11.11%  |
| Sweden       | 2        | 7.41%   |
| Indonesia    | 2        | 7.41%   |
| Argentina    | 2        | 7.41%   |
| Venezuela    | 1        | 3.7%    |
| USA          | 1        | 3.7%    |
| Switzerland  | 1        | 3.7%    |
| Spain        | 1        | 3.7%    |
| South Africa | 1        | 3.7%    |
| Lebanon      | 1        | 3.7%    |
| Germany      | 1        | 3.7%    |
| Czechia      | 1        | 3.7%    |
| Canada       | 1        | 3.7%    |
| Belgium      | 1        | 3.7%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Woking              | 1        | 3.45%   |
| West Palm Beach     | 1        | 3.45%   |
| Trelaze             | 1        | 3.45%   |
| Surabaya            | 1        | 3.45%   |
| Sin el Fil          | 1        | 3.45%   |
| San Cristóbal      | 1        | 3.45%   |
| Rosario             | 1        | 3.45%   |
| Rio de Janeiro      | 1        | 3.45%   |
| Rio Claro           | 1        | 3.45%   |
| Presidente Prudente | 1        | 3.45%   |
| Posadas             | 1        | 3.45%   |
| Norrköping         | 1        | 3.45%   |
| Montreuil           | 1        | 3.45%   |
| Mnisek pod Brdy     | 1        | 3.45%   |
| Kirkcaldy           | 1        | 3.45%   |
| Kage                | 1        | 3.45%   |
| Harlow              | 1        | 3.45%   |
| Grabs               | 1        | 3.45%   |
| Fuveau              | 1        | 3.45%   |
| Frankfurt (Oder)    | 1        | 3.45%   |
| Enfield             | 1        | 3.45%   |
| Duque de Caxias     | 1        | 3.45%   |
| Dartmouth           | 1        | 3.45%   |
| Carapicuiba         | 1        | 3.45%   |
| Cape Town           | 1        | 3.45%   |
| Calanda             | 1        | 3.45%   |
| Brussels            | 1        | 3.45%   |
| Bordeaux            | 1        | 3.45%   |
| Bandung             | 1        | 3.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 11       | 11     | 25.58%  |
| Seagate             | 9        | 11     | 20.93%  |
| Samsung Electronics | 8        | 19     | 18.6%   |
| Kingston            | 3        | 3      | 6.98%   |
| Toshiba             | 2        | 2      | 4.65%   |
| Hitachi             | 2        | 2      | 4.65%   |
| XPG                 | 1        | 1      | 2.33%   |
| SanDisk             | 1        | 2      | 2.33%   |
| Intel               | 1        | 1      | 2.33%   |
| HGST                | 1        | 1      | 2.33%   |
| Gigabyte Technology | 1        | 1      | 2.33%   |
| ASMedia             | 1        | 1      | 2.33%   |
| A-DATA Technology   | 1        | 1      | 2.33%   |
| Unknown             | 1        | 1      | 2.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Seagate ST500LT012-1DG142 500GB         | 2        | 4.17%   |
| Samsung HD161GJ 160GB                   | 2        | 4.17%   |
| XPG GAMMIX S11 Pro 1TB                  | 1        | 2.08%   |
| WDC WD800JD-08MSA1 80GB                 | 1        | 2.08%   |
| WDC WD5000AVVS-63ZWB0 500GB             | 1        | 2.08%   |
| WDC WD5000AAKS-75V0A0 500GB             | 1        | 2.08%   |
| WDC WD50 00LPLX-08ZNTT0 500GB           | 1        | 2.08%   |
| WDC WD3200AAKS-75L9A0 320GB             | 1        | 2.08%   |
| WDC WD2500AAKX-07U6AA0 250GB            | 1        | 2.08%   |
| WDC WD2500AAJS-00L7A0 250GB             | 1        | 2.08%   |
| WDC WD1600BEVT-22ZCT0 160GB             | 1        | 2.08%   |
| WDC WD1600AAJS-08L7A0 160GB             | 1        | 2.08%   |
| WDC WD10EZEX-60WN4A0 1TB                | 1        | 2.08%   |
| WDC WD10EADS-00M2B0 1TB                 | 1        | 2.08%   |
| Toshiba DT01ACA100 1TB                  | 1        | 2.08%   |
| Toshiba DT01ACA050 500GB                | 1        | 2.08%   |
| Seagate ST975042 0AS 752GB              | 1        | 2.08%   |
| Seagate ST9250315AS 250GB               | 1        | 2.08%   |
| Seagate ST500DM002-1BD142 500GB         | 1        | 2.08%   |
| Seagate ST3500413AS 500GB               | 1        | 2.08%   |
| Seagate ST3500312CS 500GB               | 1        | 2.08%   |
| Seagate ST3320418AS 320GB               | 1        | 2.08%   |
| Seagate ST2000VM003-1ET164 2TB          | 1        | 2.08%   |
| Seagate ST2000DM008-2FR102 2TB          | 1        | 2.08%   |
| Seagate BarraCuda Q5 ZP500CV30001 500GB | 1        | 2.08%   |
| SanDisk NVMe SSD Drive 500GB            | 1        | 2.08%   |
| Samsung SSD 850 EVO 500GB               | 1        | 2.08%   |
| Samsung SSD 850 EVO 250GB               | 1        | 2.08%   |
| Samsung SSD 840 PRO Series 512GB        | 1        | 2.08%   |
| Samsung MZVPV256HDGL-000H1 256GB        | 1        | 2.08%   |
| Samsung HN-M320MBB 320GB                | 1        | 2.08%   |
| Samsung HD753LJ 752GB                   | 1        | 2.08%   |
| Samsung HD322GJ 320GB                   | 1        | 2.08%   |
| Samsung HD154UI 1TB                     | 1        | 2.08%   |
| Samsung HD103SJ 1TB                     | 1        | 2.08%   |
| Kingston SV300S37A480G 480GB SSD        | 1        | 2.08%   |
| Kingston SA400S37120G 120GB SSD         | 1        | 2.08%   |
| Kingston SA400M8240G 240GB SSD          | 1        | 2.08%   |
| Intel SSDSA2BW120G3H 120GB              | 1        | 2.08%   |
| Hitachi HTS723232A7A364 320GB           | 1        | 2.08%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 11       | 11     | 36.67%  |
| Seagate             | 9        | 10     | 30%     |
| Samsung Electronics | 5        | 12     | 16.67%  |
| Toshiba             | 2        | 2      | 6.67%   |
| Hitachi             | 2        | 2      | 6.67%   |
| HGST                | 1        | 1      | 3.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 3        | 6      | 27.27%  |
| Kingston            | 3        | 3      | 27.27%  |
| Intel               | 1        | 1      | 9.09%   |
| Gigabyte Technology | 1        | 1      | 9.09%   |
| ASMedia             | 1        | 1      | 9.09%   |
| A-DATA Technology   | 1        | 1      | 9.09%   |
| Unknown             | 1        | 1      | 9.09%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 22       | 38     | 62.86%  |
| SSD  | 10       | 14     | 28.57%  |
| NVMe | 3        | 5      | 8.57%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 27       | 49     | 87.1%   |
| NVMe | 3        | 5      | 9.68%   |
| SAS  | 1        | 3      | 3.23%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 24       | 36     | 75%     |
| 0.51-1.0   | 6        | 14     | 18.75%  |
| 1.01-2.0   | 2        | 2      | 6.25%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 251-500    | 8        | 28.57%  |
| 101-250    | 6        | 21.43%  |
| 2001-3000  | 4        | 14.29%  |
| 501-1000   | 4        | 14.29%  |
| 51-100     | 3        | 10.71%  |
| 21-50      | 1        | 3.57%   |
| 1-20       | 1        | 3.57%   |
| Unknown    | 1        | 3.57%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 12       | 42.86%  |
| 21-50     | 5        | 17.86%  |
| 251-500   | 3        | 10.71%  |
| 1001-2000 | 2        | 7.14%   |
| 51-100    | 2        | 7.14%   |
| 2001-3000 | 1        | 3.57%   |
| 101-250   | 1        | 3.57%   |
| 501-1000  | 1        | 3.57%   |
| Unknown   | 1        | 3.57%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                       | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC WD5000AVVS-63ZWB0 500GB | 1        | 1      | 16.67%  |
| WDC WD1600AAJS-08L7A0 160GB | 1        | 1      | 16.67%  |
| WDC WD10EADS-00M2B0 1TB     | 1        | 1      | 16.67%  |
| Seagate ST9250315AS 250GB   | 1        | 1      | 16.67%  |
| Seagate ST3500413AS 500GB   | 1        | 1      | 16.67%  |
| Unknown                     | 1        | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 3        | 3      | 50%     |
| Seagate | 2        | 2      | 33.33%  |
| Unknown | 1        | 1      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 3        | 3      | 60%     |
| Seagate | 2        | 2      | 40%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 5        | 5      | 83.33%  |
| SSD  | 1        | 1      | 16.67%  |

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
| Works    | 16       | 23     | 50%     |
| Detected | 10       | 28     | 31.25%  |
| Malfunc  | 6        | 6      | 18.75%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 16       | 48.48%  |
| AMD                       | 8        | 24.24%  |
| Nvidia                    | 2        | 6.06%   |
| VIA Technologies          | 1        | 3.03%   |
| Seagate Technology        | 1        | 3.03%   |
| SanDisk                   | 1        | 3.03%   |
| Samsung Electronics       | 1        | 3.03%   |
| Marvell Technology Group  | 1        | 3.03%   |
| LSI Logic / Symbios Logic | 1        | 3.03%   |
| ADATA Technology          | 1        | 3.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 6        | 13.33%  |
| Nvidia MCP61 SATA Controller                                                            | 2        | 4.44%   |
| Nvidia MCP61 IDE                                                                        | 2        | 4.44%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2        | 4.44%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2        | 4.44%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2        | 4.44%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 1        | 2.22%   |
| VIA VT8237A SATA 2-Port Controller                                                      | 1        | 2.22%   |
| Seagate BarraCuda Q5 NVMe SSD (DRAM-less)                                               | 1        | 2.22%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                                      | 1        | 2.22%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 1        | 2.22%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                               | 1        | 2.22%   |
| LSI Logic / Symbios Logic SAS1064ET PCI-Express Fusion-MPT SAS                          | 1        | 2.22%   |
| Intel SATA Controller [RAID mode]                                                       | 1        | 2.22%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1        | 2.22%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 1        | 2.22%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 1        | 2.22%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1        | 2.22%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1        | 2.22%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1        | 2.22%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1        | 2.22%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                    | 1        | 2.22%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 1        | 2.22%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1        | 2.22%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1        | 2.22%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 2.22%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 2.22%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1        | 2.22%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 1        | 2.22%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1        | 2.22%   |
| AMD X370 Series Chipset SATA Controller                                                 | 1        | 2.22%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 1        | 2.22%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1        | 2.22%   |
| AMD 400 Series Chipset SATA Controller                                                  | 1        | 2.22%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 1        | 2.22%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 17       | 47.22%  |
| IDE  | 12       | 33.33%  |
| NVMe | 3        | 8.33%   |
| RAID | 2        | 5.56%   |
| SAS  | 1        | 2.78%   |
| SCSI | 1        | 2.78%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 17       | 62.96%  |
| AMD    | 10       | 37.04%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel Core i5-2500 CPU @ 3.30GHz             | 2        | 7.41%   |
| Intel Xeon CPU E5-2687W 0 @ 3.10GHz          | 1        | 3.7%    |
| Intel Pentium Gold G5400 CPU @ 3.70GHz       | 1        | 3.7%    |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz  | 1        | 3.7%    |
| Intel Core i7-4790 CPU @ 3.60GHz             | 1        | 3.7%    |
| Intel Core i7-3770 CPU @ 3.40GHz             | 1        | 3.7%    |
| Intel Core i7 CPU 860 @ 2.80GHz              | 1        | 3.7%    |
| Intel Core i5-6500 CPU @ 3.20GHz             | 1        | 3.7%    |
| Intel Core i5-4460 CPU @ 3.20GHz             | 1        | 3.7%    |
| Intel Core i5-3570K CPU @ 3.40GHz            | 1        | 3.7%    |
| Intel Core i5-10400 CPU @ 2.90GHz            | 1        | 3.7%    |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz        | 1        | 3.7%    |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz         | 1        | 3.7%    |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz         | 1        | 3.7%    |
| Intel Core 2 CPU 6300 @ 1.86GHz              | 1        | 3.7%    |
| Intel Atom CPU N280 @ 1.66GHz                | 1        | 3.7%    |
| AMD Sempron 145 Processor                    | 1        | 3.7%    |
| AMD Ryzen 9 5900X 12-Core Processor          | 1        | 3.7%    |
| AMD Ryzen 7 1800X Eight-Core Processor       | 1        | 3.7%    |
| AMD Ryzen 3 3100 4-Core Processor            | 1        | 3.7%    |
| AMD PRO A8-8600B R6, 10 Compute Cores 4C+6G  | 1        | 3.7%    |
| AMD Phenom II X6 1045T Processor             | 1        | 3.7%    |
| AMD Athlon II X3 440 Processor               | 1        | 3.7%    |
| AMD Athlon II X2 B22 Processor               | 1        | 3.7%    |
| AMD A6-7480 Radeon R5, 8 Compute Cores 2C+6G | 1        | 3.7%    |
| AMD A6-3600 APU with Radeon HD Graphics      | 1        | 3.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 6        | 22.22%  |
| Intel Core i7           | 3        | 11.11%  |
| Intel Core 2 Duo        | 2        | 7.41%   |
| AMD A6                  | 2        | 7.41%   |
| Intel Xeon              | 1        | 3.7%    |
| Intel Pentium Gold      | 1        | 3.7%    |
| Intel Pentium Dual-Core | 1        | 3.7%    |
| Intel Core 2 Quad       | 1        | 3.7%    |
| Intel Core 2            | 1        | 3.7%    |
| Intel Atom              | 1        | 3.7%    |
| AMD Sempron             | 1        | 3.7%    |
| AMD Ryzen 9             | 1        | 3.7%    |
| AMD Ryzen 7             | 1        | 3.7%    |
| AMD Ryzen 3             | 1        | 3.7%    |
| AMD PRO A8              | 1        | 3.7%    |
| AMD Phenom II X6        | 1        | 3.7%    |
| AMD Athlon II X3        | 1        | 3.7%    |
| AMD Athlon II X2        | 1        | 3.7%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 11       | 40.74%  |
| 2      | 7        | 25.93%  |
| 1      | 3        | 11.11%  |
| 8      | 2        | 7.41%   |
| 6      | 2        | 7.41%   |
| 12     | 1        | 3.7%    |
| 3      | 1        | 3.7%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 27       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 16       | 59.26%  |
| 2      | 11       | 40.74%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 26       | 96.3%   |
| 32-bit         | 1        | 3.7%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 4        | 14.81%  |
| 0x306c3    | 2        | 7.41%   |
| 0x306a9    | 2        | 7.41%   |
| 0x206a7    | 2        | 7.41%   |
| 0x0600611a | 2        | 7.41%   |
| 0xa0653    | 1        | 3.7%    |
| 0x6fd      | 1        | 3.7%    |
| 0x6fb      | 1        | 3.7%    |
| 0x6f2      | 1        | 3.7%    |
| 0x506e3    | 1        | 3.7%    |
| 0x206d7    | 1        | 3.7%    |
| 0x106e5    | 1        | 3.7%    |
| 0x1067a    | 1        | 3.7%    |
| 0x0a201016 | 1        | 3.7%    |
| 0x08701021 | 1        | 3.7%    |
| 0x08001138 | 1        | 3.7%    |
| 0x03000027 | 1        | 3.7%    |
| 0x010000dc | 1        | 3.7%    |
| 0x010000db | 1        | 3.7%    |
| 0x010000c8 | 1        | 3.7%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| K10         | 4        | 14.81%  |
| SandyBridge | 3        | 11.11%  |
| Core        | 3        | 11.11%  |
| Penryn      | 2        | 7.41%   |
| IvyBridge   | 2        | 7.41%   |
| Haswell     | 2        | 7.41%   |
| Excavator   | 2        | 7.41%   |
| Zen 3       | 1        | 3.7%    |
| Zen 2       | 1        | 3.7%    |
| Zen         | 1        | 3.7%    |
| Skylake     | 1        | 3.7%    |
| Nehalem     | 1        | 3.7%    |
| KabyLake    | 1        | 3.7%    |
| K10 Llano   | 1        | 3.7%    |
| CometLake   | 1        | 3.7%    |
| Bonnell     | 1        | 3.7%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| AMD              | 10       | 34.48%  |
| Nvidia           | 9        | 31.03%  |
| Intel            | 9        | 31.03%  |
| VIA Technologies | 1        | 3.45%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 6.67%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 2        | 6.67%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                           | 1        | 3.33%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 3.33%   |
| Nvidia GT200GL [Quadro FX 3800]                                             | 1        | 3.33%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 3.33%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 3.33%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 3.33%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 1        | 3.33%   |
| Nvidia GA106 [Geforce RTX 3050]                                             | 1        | 3.33%   |
| Nvidia G96CGL [Quadro FX 580]                                               | 1        | 3.33%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 1        | 3.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 3.33%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 1        | 3.33%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1        | 3.33%   |
| Intel HD Graphics 530                                                       | 1        | 3.33%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 3.33%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                   | 1        | 3.33%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                            | 1        | 3.33%   |
| AMD Turks GL [FirePro V4900]                                                | 1        | 3.33%   |
| AMD Sumo [Radeon HD 6530D]                                                  | 1        | 3.33%   |
| AMD RS880 [Radeon HD 4200]                                                  | 1        | 3.33%   |
| AMD Redwood LE [Radeon HD 5550/5570/5630/6390/6490/7570]                    | 1        | 3.33%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 1        | 3.33%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 1        | 3.33%   |
| AMD Cypress XT [Radeon HD 5870]                                             | 1        | 3.33%   |
| AMD Barts PRO [Radeon HD 6850]                                              | 1        | 3.33%   |
| AMD Barts LE [Radeon HD 6790]                                               | 1        | 3.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 9        | 33.33%  |
| 1 x Nvidia     | 8        | 29.63%  |
| 1 x Intel      | 8        | 29.63%  |
| 1 x VIA        | 1        | 3.7%    |
| Intel + Nvidia | 1        | 3.7%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 21       | 77.78%  |
| Unknown     | 4        | 14.81%  |
| Proprietary | 2        | 7.41%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 14       | 50%     |
| 0.51-1.0   | 5        | 17.86%  |
| 0.01-0.5   | 4        | 14.29%  |
| 7.01-8.0   | 2        | 7.14%   |
| 1.01-2.0   | 2        | 7.14%   |
| 3.01-4.0   | 1        | 3.57%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 7        | 29.17%  |
| Goldstar            | 5        | 20.83%  |
| Dell                | 3        | 12.5%   |
| BenQ                | 2        | 8.33%   |
| AOC                 | 2        | 8.33%   |
| Unknown             | 1        | 4.17%   |
| Toshiba             | 1        | 4.17%   |
| JCH                 | 1        | 4.17%   |
| Hewlett-Packard     | 1        | 4.17%   |
| Acer                | 1        | 4.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 1        | 3.7%    |
| Toshiba TV TSB0206 1920x1080                                          | 1        | 3.7%    |
| Samsung Electronics SyncMaster SAM0581 1920x1080 477x268mm 21.5-inch  | 1        | 3.7%    |
| Samsung Electronics SyncMaster SAM0116 1024x768 267x200mm 13.1-inch   | 1        | 3.7%    |
| Samsung Electronics SMB1630N SAM0630 1366x768 344x194mm 15.5-inch     | 1        | 3.7%    |
| Samsung Electronics SA300/SA350 SAM078F 1920x1080 477x268mm 21.5-inch | 1        | 3.7%    |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch     | 1        | 3.7%    |
| Samsung Electronics S22C450 SAM09C5 1920x1080 477x268mm 21.5-inch     | 1        | 3.7%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1        | 3.7%    |
| JCH F24 JCH1919 1920x1080 520x310mm 23.8-inch                         | 1        | 3.7%    |
| Hewlett-Packard w2207 HWP26A8 1680x1050 473x296mm 22.0-inch           | 1        | 3.7%    |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                   | 1        | 3.7%    |
| Goldstar W2042 GSM4E7E 1680x1050 434x270mm 20.1-inch                  | 1        | 3.7%    |
| Goldstar TV GSM9CF6 1360x768 708x398mm 32.0-inch                      | 1        | 3.7%    |
| Goldstar T710SH GSM436B 1280x960 310x230mm 15.2-inch                  | 1        | 3.7%    |
| Goldstar L1953H GSM4B3D 1280x1024 338x270mm 17.0-inch                 | 1        | 3.7%    |
| Goldstar L1953H GSM4B3C 1280x1024 338x270mm 17.0-inch                 | 1        | 3.7%    |
| Goldstar 23MP55 GSM5A23 1920x1080 510x290mm 23.1-inch                 | 1        | 3.7%    |
| Dell LCD Monitor S2715H 3840x1080                                     | 1        | 3.7%    |
| Dell LCD Monitor S2715H                                               | 1        | 3.7%    |
| Dell IN1930 DELF03B 1366x768 410x230mm 18.5-inch                      | 1        | 3.7%    |
| Dell E176FP DELA014 1280x1024 338x270mm 17.0-inch                     | 1        | 3.7%    |
| BenQ FP202W BNQ76C2 1680x1050 376x301mm 19.0-inch                     | 1        | 3.7%    |
| BenQ E900HD BNQ7910 1366x768 410x230mm 18.5-inch                      | 1        | 3.7%    |
| AOC LM729 AOCA784 1280x1024 340x270mm 17.1-inch                       | 1        | 3.7%    |
| AOC 2450W AOC2450 1920x1080 521x293mm 23.5-inch                       | 1        | 3.7%    |
| Acer S271HL ACR02CA 1920x1080 598x336mm 27.0-inch                     | 1        | 3.7%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 10       | 38.46%  |
| 1680x1050 (WSXGA+) | 3        | 11.54%  |
| 1366x768 (WXGA)    | 3        | 11.54%  |
| 1280x1024 (SXGA)   | 3        | 11.54%  |
| 3840x1080          | 1        | 3.85%   |
| 2288x1287          | 1        | 3.85%   |
| 1600x900 (HD+)     | 1        | 3.85%   |
| 1360x768           | 1        | 3.85%   |
| 1280x960           | 1        | 3.85%   |
| 1024x768 (XGA)     | 1        | 3.85%   |
| Unknown            | 1        | 3.85%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 4        | 16%     |
| 21      | 3        | 12%     |
| 20      | 3        | 12%     |
| 17      | 3        | 12%     |
| 18      | 2        | 8%      |
| 142     | 1        | 4%      |
| 74      | 1        | 4%      |
| 72      | 1        | 4%      |
| 27      | 1        | 4%      |
| 24      | 1        | 4%      |
| 22      | 1        | 4%      |
| 16      | 1        | 4%      |
| 15      | 1        | 4%      |
| 13      | 1        | 4%      |
| Unknown | 1        | 4%      |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 401-500        | 9        | 36%     |
| 501-600        | 6        | 24%     |
| 301-350        | 5        | 20%     |
| 1501-2000      | 2        | 8%      |
| More than 2000 | 1        | 4%      |
| 201-300        | 1        | 4%      |
| Unknown        | 1        | 4%      |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 14       | 56%     |
| 16/10   | 4        | 16%     |
| 5/4     | 3        | 12%     |
| 4/3     | 2        | 8%      |
| 1.00    | 1        | 4%      |
| Unknown | 1        | 4%      |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 7        | 28%     |
| 151-200        | 5        | 20%     |
| 141-150        | 5        | 20%     |
| More than 1000 | 3        | 12%     |
| 81-90          | 1        | 4%      |
| 301-350        | 1        | 4%      |
| 121-130        | 1        | 4%      |
| 101-110        | 1        | 4%      |
| Unknown        | 1        | 4%      |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 16       | 66.67%  |
| 101-120 | 4        | 16.67%  |
| 1-50    | 3        | 12.5%   |
| Unknown | 1        | 4.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 22       | 81.48%  |
| 2     | 3        | 11.11%  |
| 0     | 2        | 7.41%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 13       | 36.11%  |
| Intel                 | 8        | 22.22%  |
| Ralink Technology     | 3        | 8.33%   |
| Qualcomm Atheros      | 3        | 8.33%   |
| Nvidia                | 2        | 5.56%   |
| Broadcom Limited      | 2        | 5.56%   |
| Broadcom              | 2        | 5.56%   |
| VIA Technologies      | 1        | 2.78%   |
| TP-Link               | 1        | 2.78%   |
| D-Link System         | 1        | 2.78%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                       | Desktops | Percent |
|---------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                           | 10       | 25.64%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                       | 2        | 5.13%   |
| Nvidia MCP61 Ethernet                                                                       | 2        | 5.13%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                       | 2        | 5.13%   |
| VIA VT6102/VT6103 [Rhine-II]                                                                | 1        | 2.56%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                                                       | 1        | 2.56%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                          | 1        | 2.56%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                    | 1        | 2.56%   |
| Ralink RT5370 Wireless Adapter                                                              | 1        | 2.56%   |
| Ralink RT3072 Wireless Adapter                                                              | 1        | 2.56%   |
| Ralink MT7601U Wireless Adapter                                                             | 1        | 2.56%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                                   | 1        | 2.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                            | 1        | 2.56%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]               | 1        | 2.56%   |
| Intel Wireless 8260                                                                         | 1        | 2.56%   |
| Intel Wi-Fi 6 AX200                                                                         | 1        | 2.56%   |
| Intel I211 Gigabit Network Connection                                                       | 1        | 2.56%   |
| Intel Ethernet Controller I225-V                                                            | 1        | 2.56%   |
| Intel Ethernet Connection (2) I219-LM                                                       | 1        | 2.56%   |
| Intel Ethernet Connection (2) I218-V                                                        | 1        | 2.56%   |
| Intel 82566DM Gigabit Network Connection                                                    | 1        | 2.56%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                                        | 1        | 2.56%   |
| D-Link System DWA-160 802.11abgn Xtreme N Dual Band Adapter(rev.A2) [Atheros AR9170+AR9104] | 1        | 2.56%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                                            | 1        | 2.56%   |
| Broadcom NetXtreme BCM5721 Gigabit Ethernet PCI Express                                     | 1        | 2.56%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe                                    | 1        | 2.56%   |
| Broadcom Limited NetLink BCM57788 Gigabit Ethernet PCIe                                     | 1        | 2.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Ralink Technology     | 3        | 27.27%  |
| Realtek Semiconductor | 2        | 18.18%  |
| Qualcomm Atheros      | 2        | 18.18%  |
| Intel                 | 2        | 18.18%  |
| TP-Link               | 1        | 9.09%   |
| D-Link System         | 1        | 9.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                       | Desktops | Percent |
|---------------------------------------------------------------------------------------------|----------|---------|
| TP-Link TL-WN821N Version 5 RTL8192EU                                                       | 1        | 9.09%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                          | 1        | 9.09%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                    | 1        | 9.09%   |
| Ralink RT5370 Wireless Adapter                                                              | 1        | 9.09%   |
| Ralink RT3072 Wireless Adapter                                                              | 1        | 9.09%   |
| Ralink MT7601U Wireless Adapter                                                             | 1        | 9.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                            | 1        | 9.09%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]               | 1        | 9.09%   |
| Intel Wireless 8260                                                                         | 1        | 9.09%   |
| Intel Wi-Fi 6 AX200                                                                         | 1        | 9.09%   |
| D-Link System DWA-160 802.11abgn Xtreme N Dual Band Adapter(rev.A2) [Atheros AR9170+AR9104] | 1        | 9.09%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 12       | 42.86%  |
| Intel                 | 8        | 28.57%  |
| Nvidia                | 2        | 7.14%   |
| Broadcom Limited      | 2        | 7.14%   |
| Broadcom              | 2        | 7.14%   |
| VIA Technologies      | 1        | 3.57%   |
| Qualcomm Atheros      | 1        | 3.57%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 10       | 35.71%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 7.14%   |
| Nvidia MCP61 Ethernet                                             | 2        | 7.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 7.14%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 3.57%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 3.57%   |
| Intel I211 Gigabit Network Connection                             | 1        | 3.57%   |
| Intel Ethernet Controller I225-V                                  | 1        | 3.57%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 3.57%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 3.57%   |
| Intel 82566DM Gigabit Network Connection                          | 1        | 3.57%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 1        | 3.57%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1        | 3.57%   |
| Broadcom NetXtreme BCM5721 Gigabit Ethernet PCI Express           | 1        | 3.57%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1        | 3.57%   |
| Broadcom Limited NetLink BCM57788 Gigabit Ethernet PCIe           | 1        | 3.57%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 26       | 72.22%  |
| WiFi     | 10       | 27.78%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 22       | 73.33%  |
| WiFi     | 8        | 26.67%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 21       | 77.78%  |
| 2     | 6        | 22.22%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 24       | 88.89%  |
| Yes  | 3        | 11.11%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 2        | 40%     |
| Qualcomm Atheros Communications | 1        | 20%     |
| IMC Networks                    | 1        | 20%     |
| Cambridge Silicon Radio         | 1        | 20%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Qualcomm Atheros Bluetooth                          | 1        | 20%     |
| Intel Bluetooth wireless interface                  | 1        | 20%     |
| Intel AX200 Bluetooth                               | 1        | 20%     |
| IMC Networks Bluetooth Radio                        | 1        | 20%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1        | 20%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 15       | 38.46%  |
| AMD                 | 12       | 30.77%  |
| Nvidia              | 8        | 20.51%  |
| VIA Technologies    | 1        | 2.56%   |
| Plantronics         | 1        | 2.56%   |
| Creative Labs       | 1        | 2.56%   |
| C-Media Electronics | 1        | 2.56%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3        | 6.52%   |
| Nvidia MCP61 High Definition Audio                                         | 2        | 4.35%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 4.35%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2        | 4.35%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2        | 4.35%   |
| AMD Starship/Matisse HD Audio Controller                                   | 2        | 4.35%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2        | 4.35%   |
| AMD Kabini HDMI/DP Audio                                                   | 2        | 4.35%   |
| AMD FCH Azalia Controller                                                  | 2        | 4.35%   |
| AMD Barts HDMI Audio [Radeon HD 6790/6850/6870 / 7720 OEM]                 | 2        | 4.35%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller             | 1        | 2.17%   |
| Plantronics USB DSP v4 Audio Interface                                     | 1        | 2.17%   |
| Nvidia High Definition Audio Controller                                    | 1        | 2.17%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 2.17%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1        | 2.17%   |
| Nvidia GA106 High Definition Audio Controller                              | 1        | 2.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1        | 2.17%   |
| Intel Comet Lake PCH-V cAVS                                                | 1        | 2.17%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1        | 2.17%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1        | 2.17%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1        | 2.17%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1        | 2.17%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1        | 2.17%   |
| Intel 200 Series PCH HD Audio                                              | 1        | 2.17%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1        | 2.17%   |
| Creative Labs CA0106/CA0111 [SB Live!/Audigy/X-Fi Series]                  | 1        | 2.17%   |
| C-Media Electronics USB Audio Device                                       | 1        | 2.17%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 1        | 2.17%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 1        | 2.17%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 1        | 2.17%   |
| AMD Navi 10 HDMI Audio                                                     | 1        | 2.17%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1        | 2.17%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1        | 2.17%   |
| AMD Cypress HDMI Audio [Radeon HD 5830/5850/5870 / 6850/6870 Rebrand]      | 1        | 2.17%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]        | 1        | 2.17%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 6        | 28.57%  |
| Kingston            | 4        | 19.05%  |
| Samsung Electronics | 3        | 14.29%  |
| Corsair             | 2        | 9.52%   |
| SK hynix            | 1        | 4.76%   |
| Ramaxel Technology  | 1        | 4.76%   |
| Micron Technology   | 1        | 4.76%   |
| G.Skill             | 1        | 4.76%   |
| Crucial             | 1        | 4.76%   |
| Avant               | 1        | 4.76%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM 800MT/s                | 2        | 8.7%    |
| Unknown RAM Module 4GB DIMM 1333MT/s                  | 1        | 4.35%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s             | 1        | 4.35%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s           | 1        | 4.35%   |
| Unknown RAM Module 1024MB DIMM SDRAM                  | 1        | 4.35%   |
| SK hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s  | 1        | 4.35%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s | 1        | 4.35%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s | 1        | 4.35%   |
| Samsung RAM M3 78T5663EH3-CF7 2GB DIMM DDR2 800MT/s   | 1        | 4.35%   |
| Samsung RAM M3 78T2863RZS-CE6 1GB DIMM DDR2 667MT/s   | 1        | 4.35%   |
| Samsung RAM M3 78T2863QZS-CE6 1GB DIMM DDR2 1639MT/s  | 1        | 4.35%   |
| Ramaxel RAM RMR5030MM58E8F1600 2GB DIMM DDR3 1600MT/s | 1        | 4.35%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s   | 1        | 4.35%   |
| Kingston RAM Module 8GB DIMM DDR3 1600MT/s            | 1        | 4.35%   |
| Kingston RAM Module 16GB SODIMM DDR4 2133MT/s         | 1        | 4.35%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s   | 1        | 4.35%   |
| Kingston RAM 99U5471-030.A00LF 8GB DIMM DDR3 1333MT/s | 1        | 4.35%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s    | 1        | 4.35%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1800MT/s | 1        | 4.35%   |
| Corsair RAM CMZ4GX3M1A1600C9 4GB DIMM DDR3 1600MT/s   | 1        | 4.35%   |
| Corsair RAM CMK16GX4M2D3600C18 8GB DIMM DDR4 3600MT/s | 1        | 4.35%   |
| Avant RAM W641GU49J2320N6 8GB DIMM DDR4 2666MT/s      | 1        | 4.35%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 8        | 42.11%  |
| DDR4    | 4        | 21.05%  |
| Unknown | 3        | 15.79%  |
| SDRAM   | 2        | 10.53%  |
| DDR2    | 2        | 10.53%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 15       | 83.33%  |
| SODIMM | 3        | 16.67%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 8        | 38.1%   |
| 2048  | 6        | 28.57%  |
| 4096  | 4        | 19.05%  |
| 1024  | 2        | 9.52%   |
| 16384 | 1        | 4.76%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 5        | 23.81%  |
| 1333    | 3        | 14.29%  |
| 800     | 3        | 14.29%  |
| 3666    | 1        | 4.76%   |
| 3200    | 1        | 4.76%   |
| 2666    | 1        | 4.76%   |
| 2400    | 1        | 4.76%   |
| 2133    | 1        | 4.76%   |
| 2048    | 1        | 4.76%   |
| 1800    | 1        | 4.76%   |
| 1639    | 1        | 4.76%   |
| 667     | 1        | 4.76%   |
| Unknown | 1        | 4.76%   |

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


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Logitech            | 2        | 33.33%  |
| Samsung Electronics | 1        | 16.67%  |
| JOURIST-DC80        | 1        | 16.67%  |
| Guillemot           | 1        | 16.67%  |
| Alcor Micro         | 1        | 16.67%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Samsung Galaxy series, misc. (MTP mode) | 1        | 16.67%  |
| Logitech Webcam C270                    | 1        | 16.67%  |
| Logitech QuickCam Notebook Pro          | 1        | 16.67%  |
| JOURIST-DC80 JOURIST-DC80               | 1        | 16.67%  |
| Guillemot Hercules Dualpix Exchange     | 1        | 16.67%  |
| Alcor Micro USB 2.0 Camera              | 1        | 16.67%  |

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
| 0     | 21       | 77.78%  |
| 1     | 5        | 18.52%  |
| 2     | 1        | 3.7%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Graphics card | 4        | 57.14%  |
| Net/wireless  | 2        | 28.57%  |
| Camera        | 1        | 14.29%  |

