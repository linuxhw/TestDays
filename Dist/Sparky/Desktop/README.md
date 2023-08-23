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

Total: 39

| Vendor   | Model                | Probe                                                      | Date         |
|----------|----------------------|------------------------------------------------------------|--------------|
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
| Sparky 6    | 7        | 25%     |
| Sparky 7    | 5        | 17.86%  |
| Sparky 5.12 | 3        | 10.71%  |
| Sparky 6.3  | 2        | 7.14%   |
| Sparky 6.2  | 2        | 7.14%   |
| Sparky 6.1  | 2        | 7.14%   |
| Sparky 8    | 1        | 3.57%   |
| Sparky 7.0  | 1        | 3.57%   |
| Sparky 6.7  | 1        | 3.57%   |
| Sparky 6.6  | 1        | 3.57%   |
| Sparky 6.5  | 1        | 3.57%   |
| Sparky 6.0  | 1        | 3.57%   |
| Sparky 5.10 | 1        | 3.57%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Sparky | 26       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Desktops | Percent |
|---------------------------|----------|---------|
| 6.4.0-1-amd64             | 1        | 3.45%   |
| 6.1.0-9-amd64             | 1        | 3.45%   |
| 6.1.0-7-amd64             | 1        | 3.45%   |
| 6.1.0-3-amd64             | 1        | 3.45%   |
| 6.0.11-x64v2-rt14-xanmod1 | 1        | 3.45%   |
| 6.0.0-5-amd64             | 1        | 3.45%   |
| 5.9.13-sparky-amd64       | 1        | 3.45%   |
| 5.7.2-sparky-amd64        | 1        | 3.45%   |
| 5.6.0-2-amd64             | 1        | 3.45%   |
| 5.18.3-sparky-amd64       | 1        | 3.45%   |
| 5.18.0-4-amd64            | 1        | 3.45%   |
| 5.18.0-2-amd64            | 1        | 3.45%   |
| 5.17.3-sparky-amd64       | 1        | 3.45%   |
| 5.16.5-sparky-amd64       | 1        | 3.45%   |
| 5.10.0-9-amd64            | 1        | 3.45%   |
| 5.10.0-8-amd64            | 1        | 3.45%   |
| 5.10.0-7-amd64            | 1        | 3.45%   |
| 5.10.0-6-amd64            | 1        | 3.45%   |
| 5.10.0-3-amd64            | 1        | 3.45%   |
| 5.10.0-23-amd64           | 1        | 3.45%   |
| 5.10.0-21-amd64           | 1        | 3.45%   |
| 5.10.0-2-amd64            | 1        | 3.45%   |
| 5.10.0-14-amd64           | 1        | 3.45%   |
| 5.10.0-12-amd64           | 1        | 3.45%   |
| 5.10.0-11-686             | 1        | 3.45%   |
| 4.19.0-8-amd64            | 1        | 3.45%   |
| 4.19.0-12-amd64           | 1        | 3.45%   |
| 4.19.0-10-amd64           | 1        | 3.45%   |
| 4.19.0-10-686             | 1        | 3.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10.0  | 11       | 37.93%  |
| 4.19.0  | 4        | 13.79%  |
| 6.1.0   | 3        | 10.34%  |
| 5.18.0  | 2        | 6.9%    |
| 6.4.0   | 1        | 3.45%   |
| 6.0.11  | 1        | 3.45%   |
| 6.0.0   | 1        | 3.45%   |
| 5.9.13  | 1        | 3.45%   |
| 5.7.2   | 1        | 3.45%   |
| 5.6.0   | 1        | 3.45%   |
| 5.18.3  | 1        | 3.45%   |
| 5.17.3  | 1        | 3.45%   |
| 5.16.5  | 1        | 3.45%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 11       | 39.29%  |
| 4.19    | 4        | 14.29%  |
| 6.1     | 3        | 10.71%  |
| 5.18    | 3        | 10.71%  |
| 6.4     | 1        | 3.57%   |
| 6.0     | 1        | 3.57%   |
| 5.9     | 1        | 3.57%   |
| 5.7     | 1        | 3.57%   |
| 5.6     | 1        | 3.57%   |
| 5.17    | 1        | 3.57%   |
| 5.16    | 1        | 3.57%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 24       | 92.31%  |
| i686   | 2        | 7.69%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| XFCE             | 12       | 46.15%  |
| LXQt             | 6        | 23.08%  |
| X-Cinnamon       | 2        | 7.69%   |
| KDE5             | 2        | 7.69%   |
| lightdm-xsession | 1        | 3.85%   |
| ICEWM            | 1        | 3.85%   |
| GNOME            | 1        | 3.85%   |
| Unknown          | 1        | 3.85%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 26       | 96.3%   |
| Tty  | 1        | 3.7%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 10       | 38.46%  |
| TDM     | 6        | 23.08%  |
| SDDM    | 6        | 23.08%  |
| LightDM | 4        | 15.38%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 6        | 23.08%  |
| pt_BR | 5        | 19.23%  |
| en_GB | 3        | 11.54%  |
| fr_FR | 2        | 7.69%   |
| es_ES | 2        | 7.69%   |
| sv_SE | 1        | 3.85%   |
| es_US | 1        | 3.85%   |
| es_AR | 1        | 3.85%   |
| en_ZA | 1        | 3.85%   |
| en_DK | 1        | 3.85%   |
| en_CA | 1        | 3.85%   |
| de_CH | 1        | 3.85%   |
| cs_CZ | 1        | 3.85%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 17       | 65.38%  |
| EFI  | 9        | 34.62%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Ext4  | 24       | 92.31%  |
| Zfs   | 1        | 3.85%   |
| Btrfs | 1        | 3.85%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 10       | 38.46%  |
| MBR     | 8        | 30.77%  |
| GPT     | 8        | 30.77%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 21       | 80.77%  |
| Yes       | 5        | 19.23%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 18       | 69.23%  |
| Yes       | 8        | 30.77%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 5        | 19.23%  |
| Gigabyte Technology | 5        | 19.23%  |
| Intel               | 4        | 15.38%  |
| ASUSTek Computer    | 4        | 15.38%  |
| MSI                 | 3        | 11.54%  |
| Dell                | 2        | 7.69%   |
| Foxconn             | 1        | 3.85%   |
| Acer                | 1        | 3.85%   |
| Unknown             | 1        | 3.85%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| MSI MS-7C09                         | 1        | 3.85%   |
| MSI MS-7B86                         | 1        | 3.85%   |
| MSI MS-7721                         | 1        | 3.85%   |
| Intel H61                           | 1        | 3.85%   |
| Intel H55                           | 1        | 3.85%   |
| Intel DG43RK AAE78175-402           | 1        | 3.85%   |
| Intel DG41TY AAE47335-300           | 1        | 3.85%   |
| HP Z420 Workstation                 | 1        | 3.85%   |
| HP t5740                            | 1        | 3.85%   |
| HP EliteDesk 800 G2 DM 65W          | 1        | 3.85%   |
| HP EliteDesk 705 G2 MINI            | 1        | 3.85%   |
| HP Compaq dc7700 Ultra-slim Desktop | 1        | 3.85%   |
| Gigabyte X570S AORUS PRO AX         | 1        | 3.85%   |
| Gigabyte M68M-S2P                   | 1        | 3.85%   |
| Gigabyte H97-Gaming 3               | 1        | 3.85%   |
| Gigabyte H410M H                    | 1        | 3.85%   |
| Gigabyte G41M-ES2L                  | 1        | 3.85%   |
| Foxconn p6-2010fr                   | 1        | 3.85%   |
| Dell OptiPlex 580                   | 1        | 3.85%   |
| Dell Inspiron 620                   | 1        | 3.85%   |
| ASUS M5A78L-M LX/BR                 | 1        | 3.85%   |
| ASUS M4N68T-M                       | 1        | 3.85%   |
| ASUS G20AJ                          | 1        | 3.85%   |
| ASUS CROSSHAIR VI HERO              | 1        | 3.85%   |
| Acer Aspire X3470                   | 1        | 3.85%   |
| Unknown                             | 1        | 3.85%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| HP EliteDesk        | 2        | 7.69%   |
| MSI MS-7C09         | 1        | 3.85%   |
| MSI MS-7B86         | 1        | 3.85%   |
| MSI MS-7721         | 1        | 3.85%   |
| Intel H61           | 1        | 3.85%   |
| Intel H55           | 1        | 3.85%   |
| Intel DG43RK        | 1        | 3.85%   |
| Intel DG41TY        | 1        | 3.85%   |
| HP Z420             | 1        | 3.85%   |
| HP t5740            | 1        | 3.85%   |
| HP Compaq           | 1        | 3.85%   |
| Gigabyte X570S      | 1        | 3.85%   |
| Gigabyte M68M-S2P   | 1        | 3.85%   |
| Gigabyte H97-Gaming | 1        | 3.85%   |
| Gigabyte H410M      | 1        | 3.85%   |
| Gigabyte G41M-ES2L  | 1        | 3.85%   |
| Foxconn p6-2010fr   | 1        | 3.85%   |
| Dell OptiPlex       | 1        | 3.85%   |
| Dell Inspiron       | 1        | 3.85%   |
| ASUS M5A78L-M       | 1        | 3.85%   |
| ASUS M4N68T-M       | 1        | 3.85%   |
| ASUS G20AJ          | 1        | 3.85%   |
| ASUS CROSSHAIR      | 1        | 3.85%   |
| Acer Aspire         | 1        | 3.85%   |
| Unknown             | 1        | 3.85%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2009 | 5        | 19.23%  |
| 2011 | 4        | 15.38%  |
| 2014 | 3        | 11.54%  |
| 2021 | 2        | 7.69%   |
| 2018 | 2        | 7.69%   |
| 2015 | 2        | 7.69%   |
| 2012 | 2        | 7.69%   |
| 2007 | 2        | 7.69%   |
| 2020 | 1        | 3.85%   |
| 2019 | 1        | 3.85%   |
| 2017 | 1        | 3.85%   |
| 2010 | 1        | 3.85%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 26       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 26       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 26       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 3.01-4.0   | 8        | 30.77%  |
| 16.01-24.0 | 6        | 23.08%  |
| 8.01-16.0  | 5        | 19.23%  |
| 4.01-8.0   | 3        | 11.54%  |
| 1.01-2.0   | 2        | 7.69%   |
| 24.01-32.0 | 1        | 3.85%   |
| 2.01-3.0   | 1        | 3.85%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1.01-2.0 | 18       | 64.29%  |
| 2.01-3.0 | 4        | 14.29%  |
| 4.01-8.0 | 3        | 10.71%  |
| 0.51-1.0 | 2        | 7.14%   |
| 3.01-4.0 | 1        | 3.57%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 17       | 58.62%  |
| 2      | 6        | 20.69%  |
| 4      | 3        | 10.34%  |
| 6      | 2        | 6.9%    |
| 3      | 1        | 3.45%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 18       | 69.23%  |
| Yes       | 8        | 30.77%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 25       | 96.15%  |
| No        | 1        | 3.85%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 17       | 65.38%  |
| Yes       | 9        | 34.62%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 21       | 80.77%  |
| Yes       | 5        | 19.23%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Brazil       | 5        | 19.23%  |
| UK           | 3        | 11.54%  |
| France       | 3        | 11.54%  |
| Indonesia    | 2        | 7.69%   |
| Argentina    | 2        | 7.69%   |
| Venezuela    | 1        | 3.85%   |
| USA          | 1        | 3.85%   |
| Switzerland  | 1        | 3.85%   |
| Sweden       | 1        | 3.85%   |
| Spain        | 1        | 3.85%   |
| South Africa | 1        | 3.85%   |
| Lebanon      | 1        | 3.85%   |
| Germany      | 1        | 3.85%   |
| Czechia      | 1        | 3.85%   |
| Canada       | 1        | 3.85%   |
| Belgium      | 1        | 3.85%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Woking              | 1        | 3.57%   |
| West Palm Beach     | 1        | 3.57%   |
| Trelaze             | 1        | 3.57%   |
| Surabaya            | 1        | 3.57%   |
| Sin el Fil          | 1        | 3.57%   |
| San Cristóbal      | 1        | 3.57%   |
| Rosario             | 1        | 3.57%   |
| Rio de Janeiro      | 1        | 3.57%   |
| Rio Claro           | 1        | 3.57%   |
| Presidente Prudente | 1        | 3.57%   |
| Posadas             | 1        | 3.57%   |
| Montreuil           | 1        | 3.57%   |
| Mnisek pod Brdy     | 1        | 3.57%   |
| Kirkcaldy           | 1        | 3.57%   |
| Kage                | 1        | 3.57%   |
| Harlow              | 1        | 3.57%   |
| Grabs               | 1        | 3.57%   |
| Fuveau              | 1        | 3.57%   |
| Frankfurt (Oder)    | 1        | 3.57%   |
| Enfield             | 1        | 3.57%   |
| Duque de Caxias     | 1        | 3.57%   |
| Dartmouth           | 1        | 3.57%   |
| Carapicuiba         | 1        | 3.57%   |
| Cape Town           | 1        | 3.57%   |
| Calanda             | 1        | 3.57%   |
| Brussels            | 1        | 3.57%   |
| Bordeaux            | 1        | 3.57%   |
| Bandung             | 1        | 3.57%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 11       | 11     | 26.83%  |
| Seagate             | 8        | 10     | 19.51%  |
| Samsung Electronics | 8        | 19     | 19.51%  |
| Kingston            | 3        | 3      | 7.32%   |
| Toshiba             | 2        | 2      | 4.88%   |
| Hitachi             | 2        | 2      | 4.88%   |
| XPG                 | 1        | 1      | 2.44%   |
| SanDisk             | 1        | 2      | 2.44%   |
| Intel               | 1        | 1      | 2.44%   |
| HGST                | 1        | 1      | 2.44%   |
| Gigabyte Technology | 1        | 1      | 2.44%   |
| ASMedia             | 1        | 1      | 2.44%   |
| Unknown             | 1        | 1      | 2.44%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Seagate ST500LT012-1DG142 500GB         | 2        | 4.35%   |
| Samsung HD161GJ 160GB                   | 2        | 4.35%   |
| XPG GAMMIX S11 Pro 1TB                  | 1        | 2.17%   |
| WDC WD800JD-08MSA1 80GB                 | 1        | 2.17%   |
| WDC WD5000AVVS-63ZWB0 500GB             | 1        | 2.17%   |
| WDC WD5000AAKS-75V0A0 500GB             | 1        | 2.17%   |
| WDC WD50 00LPLX-08ZNTT0 500GB           | 1        | 2.17%   |
| WDC WD3200AAKS-75L9A0 320GB             | 1        | 2.17%   |
| WDC WD2500AAKX-07U6AA0 250GB            | 1        | 2.17%   |
| WDC WD2500AAJS-00L7A0 250GB             | 1        | 2.17%   |
| WDC WD1600BEVT-22ZCT0 160GB             | 1        | 2.17%   |
| WDC WD1600AAJS-08L7A0 160GB             | 1        | 2.17%   |
| WDC WD10EZEX-60WN4A0 1TB                | 1        | 2.17%   |
| WDC WD10EADS-00M2B0 1TB                 | 1        | 2.17%   |
| Toshiba DT01ACA100 1TB                  | 1        | 2.17%   |
| Toshiba DT01ACA050 500GB                | 1        | 2.17%   |
| Seagate ST975042 0AS 752GB              | 1        | 2.17%   |
| Seagate ST9250315AS 250GB               | 1        | 2.17%   |
| Seagate ST500DM002-1BD142 500GB         | 1        | 2.17%   |
| Seagate ST3500312CS 500GB               | 1        | 2.17%   |
| Seagate ST3320418AS 320GB               | 1        | 2.17%   |
| Seagate ST2000VM003-1ET164 2TB          | 1        | 2.17%   |
| Seagate ST2000DM008-2FR102 2TB          | 1        | 2.17%   |
| Seagate BarraCuda Q5 ZP500CV30001 500GB | 1        | 2.17%   |
| SanDisk NVMe SSD Drive 500GB            | 1        | 2.17%   |
| Samsung SSD 850 EVO 500GB               | 1        | 2.17%   |
| Samsung SSD 850 EVO 250GB               | 1        | 2.17%   |
| Samsung SSD 840 PRO Series 512GB        | 1        | 2.17%   |
| Samsung MZVPV256HDGL-000H1 256GB        | 1        | 2.17%   |
| Samsung HN-M320MBB 320GB                | 1        | 2.17%   |
| Samsung HD753LJ 752GB                   | 1        | 2.17%   |
| Samsung HD322GJ 320GB                   | 1        | 2.17%   |
| Samsung HD154UI 1TB                     | 1        | 2.17%   |
| Samsung HD103SJ 1TB                     | 1        | 2.17%   |
| Kingston SV300S37A480G 480GB SSD        | 1        | 2.17%   |
| Kingston SA400S37120G 120GB SSD         | 1        | 2.17%   |
| Kingston SA400M8240G 240GB SSD          | 1        | 2.17%   |
| Intel SSDSA2BW120G3H 120GB              | 1        | 2.17%   |
| Hitachi HTS723232A7A364 320GB           | 1        | 2.17%   |
| Hitachi HTS543232A7A384 320GB           | 1        | 2.17%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 11       | 11     | 36.67%  |
| Seagate             | 8        | 9      | 26.67%  |
| Samsung Electronics | 5        | 12     | 16.67%  |
| Toshiba             | 2        | 2      | 6.67%   |
| Hitachi             | 2        | 2      | 6.67%   |
| HGST                | 1        | 1      | 3.33%   |
| ASMedia             | 1        | 1      | 3.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 3        | 6      | 33.33%  |
| Kingston            | 3        | 3      | 33.33%  |
| Intel               | 1        | 1      | 11.11%  |
| Gigabyte Technology | 1        | 1      | 11.11%  |
| Unknown             | 1        | 1      | 11.11%  |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 21       | 38     | 63.64%  |
| SSD  | 9        | 12     | 27.27%  |
| NVMe | 3        | 5      | 9.09%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 26       | 47     | 86.67%  |
| NVMe | 3        | 5      | 10%     |
| SAS  | 1        | 3      | 3.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 23       | 35     | 74.19%  |
| 0.51-1.0   | 6        | 13     | 19.35%  |
| 1.01-2.0   | 2        | 2      | 6.45%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 251-500    | 8        | 29.63%  |
| 101-250    | 6        | 22.22%  |
| 2001-3000  | 4        | 14.81%  |
| 501-1000   | 4        | 14.81%  |
| 51-100     | 3        | 11.11%  |
| 1-20       | 1        | 3.7%    |
| Unknown    | 1        | 3.7%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 12       | 44.44%  |
| 21-50     | 4        | 14.81%  |
| 251-500   | 3        | 11.11%  |
| 1001-2000 | 2        | 7.41%   |
| 51-100    | 2        | 7.41%   |
| 2001-3000 | 1        | 3.7%    |
| 101-250   | 1        | 3.7%    |
| 501-1000  | 1        | 3.7%    |
| Unknown   | 1        | 3.7%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                       | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC WD5000AVVS-63ZWB0 500GB | 1        | 1      | 20%     |
| WDC WD1600AAJS-08L7A0 160GB | 1        | 1      | 20%     |
| WDC WD10EADS-00M2B0 1TB     | 1        | 1      | 20%     |
| Seagate ST9250315AS 250GB   | 1        | 1      | 20%     |
| Unknown                     | 1        | 1      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 3        | 3      | 60%     |
| Seagate | 1        | 1      | 20%     |
| Unknown | 1        | 1      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 3        | 3      | 75%     |
| Seagate | 1        | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 4        | 4      | 80%     |
| SSD  | 1        | 1      | 20%     |

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
| Works    | 15       | 22     | 50%     |
| Detected | 10       | 28     | 33.33%  |
| Malfunc  | 5        | 5      | 16.67%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 15       | 46.88%  |
| AMD                       | 8        | 25%     |
| Nvidia                    | 2        | 6.25%   |
| VIA Technologies          | 1        | 3.13%   |
| Seagate Technology        | 1        | 3.13%   |
| SanDisk                   | 1        | 3.13%   |
| Samsung Electronics       | 1        | 3.13%   |
| Marvell Technology Group  | 1        | 3.13%   |
| LSI Logic / Symbios Logic | 1        | 3.13%   |
| ADATA Technology          | 1        | 3.13%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 6        | 13.64%  |
| Nvidia MCP61 SATA Controller                                                            | 2        | 4.55%   |
| Nvidia MCP61 IDE                                                                        | 2        | 4.55%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2        | 4.55%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2        | 4.55%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2        | 4.55%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 1        | 2.27%   |
| VIA VT8237A SATA 2-Port Controller                                                      | 1        | 2.27%   |
| Seagate BarraCuda Q5 NVMe SSD (DRAM-less)                                               | 1        | 2.27%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                                      | 1        | 2.27%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 1        | 2.27%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                               | 1        | 2.27%   |
| LSI Logic / Symbios Logic SAS1064ET PCI-Express Fusion-MPT SAS                          | 1        | 2.27%   |
| Intel SATA Controller [RAID mode]                                                       | 1        | 2.27%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1        | 2.27%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 1        | 2.27%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 1        | 2.27%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1        | 2.27%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1        | 2.27%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1        | 2.27%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1        | 2.27%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                    | 1        | 2.27%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 1        | 2.27%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1        | 2.27%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 2.27%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 2.27%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1        | 2.27%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 1        | 2.27%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1        | 2.27%   |
| AMD X370 Series Chipset SATA Controller                                                 | 1        | 2.27%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 1        | 2.27%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1        | 2.27%   |
| AMD 400 Series Chipset SATA Controller                                                  | 1        | 2.27%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 1        | 2.27%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 16       | 45.71%  |
| IDE  | 12       | 34.29%  |
| NVMe | 3        | 8.57%   |
| RAID | 2        | 5.71%   |
| SAS  | 1        | 2.86%   |
| SCSI | 1        | 2.86%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 16       | 61.54%  |
| AMD    | 10       | 38.46%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel Core i5-2500 CPU @ 3.30GHz             | 2        | 7.69%   |
| Intel Xeon CPU E5-2687W 0 @ 3.10GHz          | 1        | 3.85%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz       | 1        | 3.85%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz  | 1        | 3.85%   |
| Intel Core i7-4790 CPU @ 3.60GHz             | 1        | 3.85%   |
| Intel Core i7-3770 CPU @ 3.40GHz             | 1        | 3.85%   |
| Intel Core i7 CPU 860 @ 2.80GHz              | 1        | 3.85%   |
| Intel Core i5-6500 CPU @ 3.20GHz             | 1        | 3.85%   |
| Intel Core i5-4460 CPU @ 3.20GHz             | 1        | 3.85%   |
| Intel Core i5-10400 CPU @ 2.90GHz            | 1        | 3.85%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz        | 1        | 3.85%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz         | 1        | 3.85%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz         | 1        | 3.85%   |
| Intel Core 2 CPU 6300 @ 1.86GHz              | 1        | 3.85%   |
| Intel Atom CPU N280 @ 1.66GHz                | 1        | 3.85%   |
| AMD Sempron 145 Processor                    | 1        | 3.85%   |
| AMD Ryzen 9 5900X 12-Core Processor          | 1        | 3.85%   |
| AMD Ryzen 7 1800X Eight-Core Processor       | 1        | 3.85%   |
| AMD Ryzen 3 3100 4-Core Processor            | 1        | 3.85%   |
| AMD PRO A8-8600B R6, 10 Compute Cores 4C+6G  | 1        | 3.85%   |
| AMD Phenom II X6 1045T Processor             | 1        | 3.85%   |
| AMD Athlon II X3 440 Processor               | 1        | 3.85%   |
| AMD Athlon II X2 B22 Processor               | 1        | 3.85%   |
| AMD A6-7480 Radeon R5, 8 Compute Cores 2C+6G | 1        | 3.85%   |
| AMD A6-3600 APU with Radeon HD Graphics      | 1        | 3.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 5        | 19.23%  |
| Intel Core i7           | 3        | 11.54%  |
| Intel Core 2 Duo        | 2        | 7.69%   |
| AMD A6                  | 2        | 7.69%   |
| Intel Xeon              | 1        | 3.85%   |
| Intel Pentium Gold      | 1        | 3.85%   |
| Intel Pentium Dual-Core | 1        | 3.85%   |
| Intel Core 2 Quad       | 1        | 3.85%   |
| Intel Core 2            | 1        | 3.85%   |
| Intel Atom              | 1        | 3.85%   |
| AMD Sempron             | 1        | 3.85%   |
| AMD Ryzen 9             | 1        | 3.85%   |
| AMD Ryzen 7             | 1        | 3.85%   |
| AMD Ryzen 3             | 1        | 3.85%   |
| AMD PRO A8              | 1        | 3.85%   |
| AMD Phenom II X6        | 1        | 3.85%   |
| AMD Athlon II X3        | 1        | 3.85%   |
| AMD Athlon II X2        | 1        | 3.85%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 10       | 38.46%  |
| 2      | 7        | 26.92%  |
| 1      | 3        | 11.54%  |
| 8      | 2        | 7.69%   |
| 6      | 2        | 7.69%   |
| 12     | 1        | 3.85%   |
| 3      | 1        | 3.85%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 26       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 15       | 57.69%  |
| 2      | 11       | 42.31%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 25       | 96.15%  |
| 32-bit         | 1        | 3.85%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 4        | 15.38%  |
| 0x306c3    | 2        | 7.69%   |
| 0x206a7    | 2        | 7.69%   |
| 0x0600611a | 2        | 7.69%   |
| 0xa0653    | 1        | 3.85%   |
| 0x6fd      | 1        | 3.85%   |
| 0x6fb      | 1        | 3.85%   |
| 0x6f2      | 1        | 3.85%   |
| 0x506e3    | 1        | 3.85%   |
| 0x306a9    | 1        | 3.85%   |
| 0x206d7    | 1        | 3.85%   |
| 0x106e5    | 1        | 3.85%   |
| 0x1067a    | 1        | 3.85%   |
| 0x0a201016 | 1        | 3.85%   |
| 0x08701021 | 1        | 3.85%   |
| 0x08001138 | 1        | 3.85%   |
| 0x03000027 | 1        | 3.85%   |
| 0x010000dc | 1        | 3.85%   |
| 0x010000db | 1        | 3.85%   |
| 0x010000c8 | 1        | 3.85%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| K10         | 4        | 15.38%  |
| SandyBridge | 3        | 11.54%  |
| Core        | 3        | 11.54%  |
| Penryn      | 2        | 7.69%   |
| Haswell     | 2        | 7.69%   |
| Excavator   | 2        | 7.69%   |
| Zen 3       | 1        | 3.85%   |
| Zen 2       | 1        | 3.85%   |
| Zen         | 1        | 3.85%   |
| Skylake     | 1        | 3.85%   |
| Nehalem     | 1        | 3.85%   |
| KabyLake    | 1        | 3.85%   |
| K10 Llano   | 1        | 3.85%   |
| IvyBridge   | 1        | 3.85%   |
| CometLake   | 1        | 3.85%   |
| Bonnell     | 1        | 3.85%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| AMD              | 10       | 35.71%  |
| Nvidia           | 9        | 32.14%  |
| Intel            | 8        | 28.57%  |
| VIA Technologies | 1        | 3.57%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 6.9%    |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 2        | 6.9%    |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                           | 1        | 3.45%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 3.45%   |
| Nvidia GT200GL [Quadro FX 3800]                                             | 1        | 3.45%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 3.45%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 3.45%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 3.45%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 1        | 3.45%   |
| Nvidia GA106 [Geforce RTX 3050]                                             | 1        | 3.45%   |
| Nvidia G96CGL [Quadro FX 580]                                               | 1        | 3.45%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 1        | 3.45%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 3.45%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 1        | 3.45%   |
| Intel HD Graphics 530                                                       | 1        | 3.45%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 3.45%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                   | 1        | 3.45%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                            | 1        | 3.45%   |
| AMD Turks GL [FirePro V4900]                                                | 1        | 3.45%   |
| AMD Sumo [Radeon HD 6530D]                                                  | 1        | 3.45%   |
| AMD RS880 [Radeon HD 4200]                                                  | 1        | 3.45%   |
| AMD Redwood LE [Radeon HD 5550/5570/5630/6390/6490/7570]                    | 1        | 3.45%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 1        | 3.45%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 1        | 3.45%   |
| AMD Cypress XT [Radeon HD 5870]                                             | 1        | 3.45%   |
| AMD Barts PRO [Radeon HD 6850]                                              | 1        | 3.45%   |
| AMD Barts LE [Radeon HD 6790]                                               | 1        | 3.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 9        | 34.62%  |
| 1 x Nvidia     | 8        | 30.77%  |
| 1 x Intel      | 7        | 26.92%  |
| 1 x VIA        | 1        | 3.85%   |
| Intel + Nvidia | 1        | 3.85%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 20       | 76.92%  |
| Unknown     | 4        | 15.38%  |
| Proprietary | 2        | 7.69%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 13       | 48.15%  |
| 0.51-1.0   | 5        | 18.52%  |
| 0.01-0.5   | 4        | 14.81%  |
| 7.01-8.0   | 2        | 7.41%   |
| 1.01-2.0   | 2        | 7.41%   |
| 3.01-4.0   | 1        | 3.7%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 7        | 30.43%  |
| Goldstar            | 5        | 21.74%  |
| Dell                | 3        | 13.04%  |
| BenQ                | 2        | 8.7%    |
| AOC                 | 2        | 8.7%    |
| Unknown             | 1        | 4.35%   |
| Toshiba             | 1        | 4.35%   |
| JCH                 | 1        | 4.35%   |
| Acer                | 1        | 4.35%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 1        | 3.85%   |
| Toshiba TV TSB0206 1920x1080 1600x1000mm 74.3-inch                    | 1        | 3.85%   |
| Samsung Electronics SyncMaster SAM0581 1920x1080 477x268mm 21.5-inch  | 1        | 3.85%   |
| Samsung Electronics SyncMaster SAM0116 1024x768 267x200mm 13.1-inch   | 1        | 3.85%   |
| Samsung Electronics SMB1630N SAM0630 1360x768 344x194mm 15.5-inch     | 1        | 3.85%   |
| Samsung Electronics SA300/SA350 SAM078F 1920x1080 477x268mm 21.5-inch | 1        | 3.85%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch     | 1        | 3.85%   |
| Samsung Electronics S22C450 SAM09C5 1920x1080 477x268mm 21.5-inch     | 1        | 3.85%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1        | 3.85%   |
| JCH F24 JCH1919 1920x1080 520x310mm 23.8-inch                         | 1        | 3.85%   |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                   | 1        | 3.85%   |
| Goldstar W2042 GSM4E7E 1680x1050 434x270mm 20.1-inch                  | 1        | 3.85%   |
| Goldstar TV GSM9CF6 1360x768 708x398mm 32.0-inch                      | 1        | 3.85%   |
| Goldstar T710SH GSM436B 1280x960 310x230mm 15.2-inch                  | 1        | 3.85%   |
| Goldstar L1953H GSM4B3D 1280x1024 338x270mm 17.0-inch                 | 1        | 3.85%   |
| Goldstar L1953H GSM4B3C 1280x1024 338x270mm 17.0-inch                 | 1        | 3.85%   |
| Goldstar 23MP55 GSM5A23 1920x1080 510x290mm 23.1-inch                 | 1        | 3.85%   |
| Dell LCD Monitor S2715H 3840x1080                                     | 1        | 3.85%   |
| Dell LCD Monitor S2715H                                               | 1        | 3.85%   |
| Dell IN1930 DELF03B 1366x768 410x230mm 18.5-inch                      | 1        | 3.85%   |
| Dell E176FP DELA014 1280x1024 338x270mm 17.0-inch                     | 1        | 3.85%   |
| BenQ FP202W BNQ76C2 1680x1050 376x301mm 19.0-inch                     | 1        | 3.85%   |
| BenQ E900HD BNQ7910 1366x768 410x230mm 18.5-inch                      | 1        | 3.85%   |
| AOC LM729 AOCA784 1280x1024 340x270mm 17.1-inch                       | 1        | 3.85%   |
| AOC 2450W AOC2450 1920x1080 521x293mm 23.5-inch                       | 1        | 3.85%   |
| Acer S271HL ACR02CA 1920x1080 598x336mm 27.0-inch                     | 1        | 3.85%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 10       | 40%     |
| 1366x768 (WXGA)    | 3        | 12%     |
| 1280x1024 (SXGA)   | 3        | 12%     |
| 1680x1050 (WSXGA+) | 2        | 8%      |
| 3840x1080          | 1        | 4%      |
| 2288x1287          | 1        | 4%      |
| 1600x900 (HD+)     | 1        | 4%      |
| 1360x768           | 1        | 4%      |
| 1280x960           | 1        | 4%      |
| 1024x768 (XGA)     | 1        | 4%      |
| Unknown            | 1        | 4%      |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 4        | 16.67%  |
| 21      | 3        | 12.5%   |
| 20      | 3        | 12.5%   |
| 17      | 3        | 12.5%   |
| 18      | 2        | 8.33%   |
| 142     | 1        | 4.17%   |
| 74      | 1        | 4.17%   |
| 72      | 1        | 4.17%   |
| 27      | 1        | 4.17%   |
| 24      | 1        | 4.17%   |
| 16      | 1        | 4.17%   |
| 15      | 1        | 4.17%   |
| 13      | 1        | 4.17%   |
| Unknown | 1        | 4.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 401-500        | 8        | 33.33%  |
| 501-600        | 6        | 25%     |
| 301-350        | 5        | 20.83%  |
| 1501-2000      | 2        | 8.33%   |
| More than 2000 | 1        | 4.17%   |
| 201-300        | 1        | 4.17%   |
| Unknown        | 1        | 4.17%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 14       | 58.33%  |
| 5/4     | 3        | 12.5%   |
| 16/10   | 3        | 12.5%   |
| 4/3     | 2        | 8.33%   |
| 1.00    | 1        | 4.17%   |
| Unknown | 1        | 4.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 6        | 25%     |
| 151-200        | 5        | 20.83%  |
| 141-150        | 5        | 20.83%  |
| More than 1000 | 3        | 12.5%   |
| 81-90          | 1        | 4.17%   |
| 301-350        | 1        | 4.17%   |
| 121-130        | 1        | 4.17%   |
| 101-110        | 1        | 4.17%   |
| Unknown        | 1        | 4.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 15       | 65.22%  |
| 101-120 | 4        | 17.39%  |
| 1-50    | 3        | 13.04%  |
| Unknown | 1        | 4.35%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 21       | 80.77%  |
| 2     | 3        | 11.54%  |
| 0     | 2        | 7.69%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 13       | 37.14%  |
| Intel                 | 7        | 20%     |
| Ralink Technology     | 3        | 8.57%   |
| Qualcomm Atheros      | 3        | 8.57%   |
| Nvidia                | 2        | 5.71%   |
| Broadcom Limited      | 2        | 5.71%   |
| Broadcom              | 2        | 5.71%   |
| VIA Technologies      | 1        | 2.86%   |
| TP-Link               | 1        | 2.86%   |
| D-Link System         | 1        | 2.86%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                       | Desktops | Percent |
|---------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                           | 10       | 26.32%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                       | 2        | 5.26%   |
| Nvidia MCP61 Ethernet                                                                       | 2        | 5.26%   |
| VIA VT6102/VT6103 [Rhine-II]                                                                | 1        | 2.63%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                         | 1        | 2.63%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                          | 1        | 2.63%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                    | 1        | 2.63%   |
| Ralink RT5370 Wireless Adapter                                                              | 1        | 2.63%   |
| Ralink RT3072 Wireless Adapter                                                              | 1        | 2.63%   |
| Ralink MT7601U Wireless Adapter                                                             | 1        | 2.63%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                                   | 1        | 2.63%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                            | 1        | 2.63%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]               | 1        | 2.63%   |
| Intel Wireless 8260                                                                         | 1        | 2.63%   |
| Intel Wi-Fi 6 AX200                                                                         | 1        | 2.63%   |
| Intel I211 Gigabit Network Connection                                                       | 1        | 2.63%   |
| Intel Ethernet Controller I225-V                                                            | 1        | 2.63%   |
| Intel Ethernet Connection (2) I219-LM                                                       | 1        | 2.63%   |
| Intel Ethernet Connection (2) I218-V                                                        | 1        | 2.63%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                       | 1        | 2.63%   |
| Intel 82566DM Gigabit Network Connection                                                    | 1        | 2.63%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                                        | 1        | 2.63%   |
| D-Link System DWA-160 802.11abgn Xtreme N Dual Band Adapter(rev.A2) [Atheros AR9170+AR9104] | 1        | 2.63%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                                            | 1        | 2.63%   |
| Broadcom NetXtreme BCM5721 Gigabit Ethernet PCI Express                                     | 1        | 2.63%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe                                    | 1        | 2.63%   |
| Broadcom Limited NetLink BCM57788 Gigabit Ethernet PCIe                                     | 1        | 2.63%   |

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
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                         | 1        | 9.09%   |
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
| Realtek Semiconductor | 12       | 44.44%  |
| Intel                 | 7        | 25.93%  |
| Nvidia                | 2        | 7.41%   |
| Broadcom Limited      | 2        | 7.41%   |
| Broadcom              | 2        | 7.41%   |
| VIA Technologies      | 1        | 3.7%    |
| Qualcomm Atheros      | 1        | 3.7%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 10       | 37.04%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 7.41%   |
| Nvidia MCP61 Ethernet                                             | 2        | 7.41%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 3.7%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 3.7%    |
| Intel I211 Gigabit Network Connection                             | 1        | 3.7%    |
| Intel Ethernet Controller I225-V                                  | 1        | 3.7%    |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 3.7%    |
| Intel Ethernet Connection (2) I218-V                              | 1        | 3.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 3.7%    |
| Intel 82566DM Gigabit Network Connection                          | 1        | 3.7%    |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 1        | 3.7%    |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1        | 3.7%    |
| Broadcom NetXtreme BCM5721 Gigabit Ethernet PCI Express           | 1        | 3.7%    |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1        | 3.7%    |
| Broadcom Limited NetLink BCM57788 Gigabit Ethernet PCIe           | 1        | 3.7%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 25       | 71.43%  |
| WiFi     | 10       | 28.57%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 21       | 72.41%  |
| WiFi     | 8        | 27.59%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 20       | 76.92%  |
| 2     | 6        | 23.08%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 23       | 88.46%  |
| Yes  | 3        | 11.54%  |

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
| Intel               | 14       | 36.84%  |
| AMD                 | 12       | 31.58%  |
| Nvidia              | 8        | 21.05%  |
| VIA Technologies    | 1        | 2.63%   |
| Plantronics         | 1        | 2.63%   |
| Creative Labs       | 1        | 2.63%   |
| C-Media Electronics | 1        | 2.63%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3        | 6.67%   |
| Nvidia MCP61 High Definition Audio                                         | 2        | 4.44%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 4.44%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2        | 4.44%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2        | 4.44%   |
| AMD Starship/Matisse HD Audio Controller                                   | 2        | 4.44%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2        | 4.44%   |
| AMD Kabini HDMI/DP Audio                                                   | 2        | 4.44%   |
| AMD FCH Azalia Controller                                                  | 2        | 4.44%   |
| AMD Barts HDMI Audio [Radeon HD 6790/6850/6870 / 7720 OEM]                 | 2        | 4.44%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller             | 1        | 2.22%   |
| Plantronics USB DSP v4 Audio Interface                                     | 1        | 2.22%   |
| Nvidia High Definition Audio Controller                                    | 1        | 2.22%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 2.22%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1        | 2.22%   |
| Nvidia GA106 High Definition Audio Controller                              | 1        | 2.22%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1        | 2.22%   |
| Intel Comet Lake PCH-V cAVS                                                | 1        | 2.22%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1        | 2.22%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1        | 2.22%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1        | 2.22%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1        | 2.22%   |
| Intel 200 Series PCH HD Audio                                              | 1        | 2.22%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1        | 2.22%   |
| Creative Labs CA0106/CA0111 [SB Live!/Audigy/X-Fi Series]                  | 1        | 2.22%   |
| C-Media Electronics USB Audio Device                                       | 1        | 2.22%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 1        | 2.22%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 1        | 2.22%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 1        | 2.22%   |
| AMD Navi 10 HDMI Audio                                                     | 1        | 2.22%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1        | 2.22%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1        | 2.22%   |
| AMD Cypress HDMI Audio [Radeon HD 5830/5850/5870 / 6850/6870 Rebrand]      | 1        | 2.22%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]        | 1        | 2.22%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 6        | 33.33%  |
| Kingston            | 4        | 22.22%  |
| Samsung Electronics | 3        | 16.67%  |
| Corsair             | 2        | 11.11%  |
| G.Skill             | 1        | 5.56%   |
| Crucial             | 1        | 5.56%   |
| Avant               | 1        | 5.56%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM 800MT/s                | 2        | 10%     |
| Unknown RAM Module 4GB DIMM 1333MT/s                  | 1        | 5%      |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s             | 1        | 5%      |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s           | 1        | 5%      |
| Unknown RAM Module 1024MB DIMM SDRAM                  | 1        | 5%      |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s | 1        | 5%      |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s | 1        | 5%      |
| Samsung RAM M3 78T5663EH3-CF7 2GB DIMM DDR2 800MT/s   | 1        | 5%      |
| Samsung RAM M3 78T2863RZS-CE6 1GB DIMM DDR2 667MT/s   | 1        | 5%      |
| Samsung RAM M3 78T2863QZS-CE6 1GB DIMM DDR2 1639MT/s  | 1        | 5%      |
| Kingston RAM Module 8GB DIMM DDR3 1600MT/s            | 1        | 5%      |
| Kingston RAM Module 16GB SODIMM DDR4 2133MT/s         | 1        | 5%      |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s   | 1        | 5%      |
| Kingston RAM 99U5471-030.A00LF 8GB DIMM DDR3 1333MT/s | 1        | 5%      |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s    | 1        | 5%      |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1800MT/s | 1        | 5%      |
| Corsair RAM CMZ4GX3M1A1600C9 4GB DIMM DDR3 1600MT/s   | 1        | 5%      |
| Corsair RAM CMK16GX4M2D3600C18 8GB DIMM DDR4 3600MT/s | 1        | 5%      |
| Avant RAM W641GU49J2320N6 8GB DIMM DDR4 2666MT/s      | 1        | 5%      |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 7        | 38.89%  |
| DDR4    | 4        | 22.22%  |
| Unknown | 3        | 16.67%  |
| SDRAM   | 2        | 11.11%  |
| DDR2    | 2        | 11.11%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 14       | 82.35%  |
| SODIMM | 3        | 17.65%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 8        | 42.11%  |
| 2048  | 5        | 26.32%  |
| 4096  | 3        | 15.79%  |
| 1024  | 2        | 10.53%  |
| 16384 | 1        | 5.26%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 4        | 20%     |
| 1333    | 3        | 15%     |
| 800     | 3        | 15%     |
| 3666    | 1        | 5%      |
| 3200    | 1        | 5%      |
| 2666    | 1        | 5%      |
| 2400    | 1        | 5%      |
| 2133    | 1        | 5%      |
| 2048    | 1        | 5%      |
| 1800    | 1        | 5%      |
| 1639    | 1        | 5%      |
| 667     | 1        | 5%      |
| Unknown | 1        | 5%      |

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
| Guillemot           | 1        | 16.67%  |
| Alcor Micro         | 1        | 16.67%  |
| Unknown             | 1        | 16.67%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Samsung Galaxy series, misc. (MTP mode) | 1        | 16.67%  |
| Logitech Webcam C270                    | 1        | 16.67%  |
| Logitech QuickCam Notebook Pro          | 1        | 16.67%  |
| Guillemot Hercules Dualpix Exchange     | 1        | 16.67%  |
| Alcor Micro USB 2.0 Camera              | 1        | 16.67%  |
| Unknown                                 | 1        | 16.67%  |

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
| 0     | 19       | 73.08%  |
| 1     | 6        | 23.08%  |
| 2     | 1        | 3.85%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Graphics card | 5        | 62.5%   |
| Net/wireless  | 2        | 25%     |
| Camera        | 1        | 12.5%   |

