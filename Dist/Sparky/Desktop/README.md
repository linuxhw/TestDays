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

Total: 43

| Vendor   | Model                | Probe                                                      | Date         |
|----------|----------------------|------------------------------------------------------------|--------------|
| Acer     | FIH57                | [0edb232edf](https://linux-hardware.org/?probe=0edb232edf) | Dec 16, 2023 |
| HP       | 0A80h                | [5e6a479e17](https://linux-hardware.org/?probe=5e6a479e17) | Dec 01, 2023 |
| ASUSTek  | P7H55-M              | [ad3f143871](https://linux-hardware.org/?probe=ad3f143871) | Oct 20, 2023 |
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
| Sparky 6    | 7        | 21.88%  |
| Sparky 7    | 5        | 15.63%  |
| Sparky 5.12 | 3        | 9.38%   |
| Sparky 7.1  | 2        | 6.25%   |
| Sparky 7.0  | 2        | 6.25%   |
| Sparky 6.7  | 2        | 6.25%   |
| Sparky 6.3  | 2        | 6.25%   |
| Sparky 6.2  | 2        | 6.25%   |
| Sparky 6.1  | 2        | 6.25%   |
| Sparky 8    | 1        | 3.13%   |
| Sparky 6.6  | 1        | 3.13%   |
| Sparky 6.5  | 1        | 3.13%   |
| Sparky 6.0  | 1        | 3.13%   |
| Sparky 5.10 | 1        | 3.13%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Sparky | 30       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Desktops | Percent |
|---------------------------|----------|---------|
| 6.1.0-13-amd64            | 2        | 6.06%   |
| 6.4.0-1-amd64             | 1        | 3.03%   |
| 6.1.0-9-amd64             | 1        | 3.03%   |
| 6.1.0-7-amd64             | 1        | 3.03%   |
| 6.1.0-3-amd64             | 1        | 3.03%   |
| 6.1.0-11-amd64            | 1        | 3.03%   |
| 6.0.11-x64v2-rt14-xanmod1 | 1        | 3.03%   |
| 6.0.0-5-amd64             | 1        | 3.03%   |
| 5.9.13-sparky-amd64       | 1        | 3.03%   |
| 5.7.2-sparky-amd64        | 1        | 3.03%   |
| 5.6.0-2-amd64             | 1        | 3.03%   |
| 5.18.3-sparky-amd64       | 1        | 3.03%   |
| 5.18.0-4-amd64            | 1        | 3.03%   |
| 5.18.0-2-amd64            | 1        | 3.03%   |
| 5.17.3-sparky-amd64       | 1        | 3.03%   |
| 5.16.5-sparky-amd64       | 1        | 3.03%   |
| 5.10.0-9-amd64            | 1        | 3.03%   |
| 5.10.0-8-amd64            | 1        | 3.03%   |
| 5.10.0-7-amd64            | 1        | 3.03%   |
| 5.10.0-6-amd64            | 1        | 3.03%   |
| 5.10.0-3-amd64            | 1        | 3.03%   |
| 5.10.0-26-amd64           | 1        | 3.03%   |
| 5.10.0-23-amd64           | 1        | 3.03%   |
| 5.10.0-21-amd64           | 1        | 3.03%   |
| 5.10.0-2-amd64            | 1        | 3.03%   |
| 5.10.0-14-amd64           | 1        | 3.03%   |
| 5.10.0-12-amd64           | 1        | 3.03%   |
| 5.10.0-11-686             | 1        | 3.03%   |
| 4.19.0-8-amd64            | 1        | 3.03%   |
| 4.19.0-12-amd64           | 1        | 3.03%   |
| 4.19.0-10-amd64           | 1        | 3.03%   |
| 4.19.0-10-686             | 1        | 3.03%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10.0  | 12       | 36.36%  |
| 6.1.0   | 6        | 18.18%  |
| 4.19.0  | 4        | 12.12%  |
| 5.18.0  | 2        | 6.06%   |
| 6.4.0   | 1        | 3.03%   |
| 6.0.11  | 1        | 3.03%   |
| 6.0.0   | 1        | 3.03%   |
| 5.9.13  | 1        | 3.03%   |
| 5.7.2   | 1        | 3.03%   |
| 5.6.0   | 1        | 3.03%   |
| 5.18.3  | 1        | 3.03%   |
| 5.17.3  | 1        | 3.03%   |
| 5.16.5  | 1        | 3.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 12       | 37.5%   |
| 6.1     | 6        | 18.75%  |
| 4.19    | 4        | 12.5%   |
| 5.18    | 3        | 9.38%   |
| 6.4     | 1        | 3.13%   |
| 6.0     | 1        | 3.13%   |
| 5.9     | 1        | 3.13%   |
| 5.7     | 1        | 3.13%   |
| 5.6     | 1        | 3.13%   |
| 5.17    | 1        | 3.13%   |
| 5.16    | 1        | 3.13%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 28       | 93.33%  |
| i686   | 2        | 6.67%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| XFCE             | 14       | 46.67%  |
| LXQt             | 7        | 23.33%  |
| X-Cinnamon       | 2        | 6.67%   |
| KDE5             | 2        | 6.67%   |
| lightdm-xsession | 1        | 3.33%   |
| ICEWM            | 1        | 3.33%   |
| GNOME Flashback  | 1        | 3.33%   |
| GNOME            | 1        | 3.33%   |
| Unknown          | 1        | 3.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 30       | 96.77%  |
| Tty  | 1        | 3.23%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 10       | 33.33%  |
| SDDM    | 8        | 26.67%  |
| TDM     | 6        | 20%     |
| LightDM | 5        | 16.67%  |
| GDM     | 1        | 3.33%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 7        | 23.33%  |
| pt_BR | 5        | 16.67%  |
| en_GB | 4        | 13.33%  |
| fr_FR | 2        | 6.67%   |
| es_ES | 2        | 6.67%   |
| sv_SE | 1        | 3.33%   |
| ru_RU | 1        | 3.33%   |
| it_IT | 1        | 3.33%   |
| es_US | 1        | 3.33%   |
| es_AR | 1        | 3.33%   |
| en_ZA | 1        | 3.33%   |
| en_DK | 1        | 3.33%   |
| en_CA | 1        | 3.33%   |
| de_CH | 1        | 3.33%   |
| cs_CZ | 1        | 3.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 21       | 70%     |
| EFI  | 9        | 30%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Ext4  | 28       | 93.33%  |
| Zfs   | 1        | 3.33%   |
| Btrfs | 1        | 3.33%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| MBR     | 11       | 36.67%  |
| Unknown | 10       | 33.33%  |
| GPT     | 9        | 30%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 23       | 76.67%  |
| Yes       | 7        | 23.33%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 19       | 63.33%  |
| Yes       | 11       | 36.67%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 6        | 20%     |
| Gigabyte Technology | 5        | 16.67%  |
| ASUSTek Computer    | 5        | 16.67%  |
| Intel               | 4        | 13.33%  |
| MSI                 | 3        | 10%     |
| Dell                | 3        | 10%     |
| Acer                | 2        | 6.67%   |
| Foxconn             | 1        | 3.33%   |
| Unknown             | 1        | 3.33%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| MSI MS-7C09                         | 1        | 3.33%   |
| MSI MS-7B86                         | 1        | 3.33%   |
| MSI MS-7721                         | 1        | 3.33%   |
| Intel H61                           | 1        | 3.33%   |
| Intel H55                           | 1        | 3.33%   |
| Intel DG43RK AAE78175-402           | 1        | 3.33%   |
| Intel DG41TY AAE47335-300           | 1        | 3.33%   |
| HP Z420 Workstation                 | 1        | 3.33%   |
| HP t5740                            | 1        | 3.33%   |
| HP rp5700 Business System           | 1        | 3.33%   |
| HP EliteDesk 800 G2 DM 65W          | 1        | 3.33%   |
| HP EliteDesk 705 G2 MINI            | 1        | 3.33%   |
| HP Compaq dc7700 Ultra-slim Desktop | 1        | 3.33%   |
| Gigabyte X570S AORUS PRO AX         | 1        | 3.33%   |
| Gigabyte M68M-S2P                   | 1        | 3.33%   |
| Gigabyte H97-Gaming 3               | 1        | 3.33%   |
| Gigabyte H410M H                    | 1        | 3.33%   |
| Gigabyte G41M-ES2L                  | 1        | 3.33%   |
| Foxconn p6-2010fr                   | 1        | 3.33%   |
| Dell OptiPlex 7010                  | 1        | 3.33%   |
| Dell OptiPlex 580                   | 1        | 3.33%   |
| Dell Inspiron 620                   | 1        | 3.33%   |
| ASUS P7H55-M                        | 1        | 3.33%   |
| ASUS M5A78L-M LX/BR                 | 1        | 3.33%   |
| ASUS M4N68T-M                       | 1        | 3.33%   |
| ASUS G20AJ                          | 1        | 3.33%   |
| ASUS CROSSHAIR VI HERO              | 1        | 3.33%   |
| Acer Aspire X3900                   | 1        | 3.33%   |
| Acer Aspire X3470                   | 1        | 3.33%   |
| Unknown                             | 1        | 3.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| HP EliteDesk        | 2        | 6.67%   |
| Dell OptiPlex       | 2        | 6.67%   |
| Acer Aspire         | 2        | 6.67%   |
| MSI MS-7C09         | 1        | 3.33%   |
| MSI MS-7B86         | 1        | 3.33%   |
| MSI MS-7721         | 1        | 3.33%   |
| Intel H61           | 1        | 3.33%   |
| Intel H55           | 1        | 3.33%   |
| Intel DG43RK        | 1        | 3.33%   |
| Intel DG41TY        | 1        | 3.33%   |
| HP Z420             | 1        | 3.33%   |
| HP t5740            | 1        | 3.33%   |
| HP rp5700           | 1        | 3.33%   |
| HP Compaq           | 1        | 3.33%   |
| Gigabyte X570S      | 1        | 3.33%   |
| Gigabyte M68M-S2P   | 1        | 3.33%   |
| Gigabyte H97-Gaming | 1        | 3.33%   |
| Gigabyte H410M      | 1        | 3.33%   |
| Gigabyte G41M-ES2L  | 1        | 3.33%   |
| Foxconn p6-2010fr   | 1        | 3.33%   |
| Dell Inspiron       | 1        | 3.33%   |
| ASUS P7H55-M        | 1        | 3.33%   |
| ASUS M5A78L-M       | 1        | 3.33%   |
| ASUS M4N68T-M       | 1        | 3.33%   |
| ASUS G20AJ          | 1        | 3.33%   |
| ASUS CROSSHAIR      | 1        | 3.33%   |
| Unknown             | 1        | 3.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2009 | 6        | 20%     |
| 2011 | 4        | 13.33%  |
| 2014 | 3        | 10%     |
| 2007 | 3        | 10%     |
| 2021 | 2        | 6.67%   |
| 2018 | 2        | 6.67%   |
| 2015 | 2        | 6.67%   |
| 2012 | 2        | 6.67%   |
| 2010 | 2        | 6.67%   |
| 2020 | 1        | 3.33%   |
| 2019 | 1        | 3.33%   |
| 2017 | 1        | 3.33%   |
| 2013 | 1        | 3.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 30       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 30       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 30       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 3.01-4.0   | 11       | 36.67%  |
| 16.01-24.0 | 6        | 20%     |
| 8.01-16.0  | 6        | 20%     |
| 4.01-8.0   | 3        | 10%     |
| 1.01-2.0   | 2        | 6.67%   |
| 24.01-32.0 | 1        | 3.33%   |
| 2.01-3.0   | 1        | 3.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1.01-2.0 | 20       | 62.5%   |
| 2.01-3.0 | 6        | 18.75%  |
| 4.01-8.0 | 3        | 9.38%   |
| 0.51-1.0 | 2        | 6.25%   |
| 3.01-4.0 | 1        | 3.13%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 20       | 60.61%  |
| 2      | 7        | 21.21%  |
| 4      | 3        | 9.09%   |
| 6      | 2        | 6.06%   |
| 3      | 1        | 3.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 19       | 63.33%  |
| Yes       | 11       | 36.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 29       | 96.67%  |
| No        | 1        | 3.33%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 20       | 66.67%  |
| Yes       | 10       | 33.33%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 25       | 83.33%  |
| Yes       | 5        | 16.67%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Brazil       | 5        | 16.67%  |
| France       | 4        | 13.33%  |
| UK           | 3        | 10%     |
| Sweden       | 2        | 6.67%   |
| Indonesia    | 2        | 6.67%   |
| Argentina    | 2        | 6.67%   |
| Venezuela    | 1        | 3.33%   |
| USA          | 1        | 3.33%   |
| Switzerland  | 1        | 3.33%   |
| Spain        | 1        | 3.33%   |
| South Africa | 1        | 3.33%   |
| Russia       | 1        | 3.33%   |
| Lebanon      | 1        | 3.33%   |
| Italy        | 1        | 3.33%   |
| Germany      | 1        | 3.33%   |
| Czechia      | 1        | 3.33%   |
| Canada       | 1        | 3.33%   |
| Belgium      | 1        | 3.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Woking              | 1        | 3.13%   |
| West Palm Beach     | 1        | 3.13%   |
| Trelaze             | 1        | 3.13%   |
| Surabaya            | 1        | 3.13%   |
| Sin el Fil          | 1        | 3.13%   |
| San Cristóbal      | 1        | 3.13%   |
| Rosario             | 1        | 3.13%   |
| Rio de Janeiro      | 1        | 3.13%   |
| Rio Claro           | 1        | 3.13%   |
| Presidente Prudente | 1        | 3.13%   |
| Posadas             | 1        | 3.13%   |
| Norrköping         | 1        | 3.13%   |
| Moscow              | 1        | 3.13%   |
| Montreuil           | 1        | 3.13%   |
| Mnisek pod Brdy     | 1        | 3.13%   |
| Kirkcaldy           | 1        | 3.13%   |
| Kage                | 1        | 3.13%   |
| Harlow              | 1        | 3.13%   |
| Grabs               | 1        | 3.13%   |
| Fuveau              | 1        | 3.13%   |
| Frankfurt (Oder)    | 1        | 3.13%   |
| Enfield             | 1        | 3.13%   |
| Duque de Caxias     | 1        | 3.13%   |
| Dartmouth           | 1        | 3.13%   |
| Choisy-le-Roi       | 1        | 3.13%   |
| Carapicuiba         | 1        | 3.13%   |
| Cape Town           | 1        | 3.13%   |
| Campomarino         | 1        | 3.13%   |
| Calanda             | 1        | 3.13%   |
| Brussels            | 1        | 3.13%   |
| Bordeaux            | 1        | 3.13%   |
| Bandung             | 1        | 3.13%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 12       | 12     | 26.09%  |
| Seagate             | 10       | 12     | 21.74%  |
| Samsung Electronics | 8        | 19     | 17.39%  |
| Kingston            | 3        | 3      | 6.52%   |
| Toshiba             | 2        | 2      | 4.35%   |
| Hitachi             | 2        | 2      | 4.35%   |
| XPG                 | 1        | 1      | 2.17%   |
| SanDisk             | 1        | 2      | 2.17%   |
| Patriot             | 1        | 1      | 2.17%   |
| Intel               | 1        | 1      | 2.17%   |
| HGST                | 1        | 1      | 2.17%   |
| Gigabyte Technology | 1        | 1      | 2.17%   |
| ASMedia             | 1        | 1      | 2.17%   |
| A-DATA Technology   | 1        | 1      | 2.17%   |
| Unknown             | 1        | 1      | 2.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Seagate ST500LT012-1DG142 500GB         | 2        | 3.92%   |
| Seagate ST2000DM008-2FR102 2TB          | 2        | 3.92%   |
| Samsung HD161GJ 160GB                   | 2        | 3.92%   |
| XPG GAMMIX S11 Pro 256GB                | 1        | 1.96%   |
| WDC WD800JD-08MSA1 80GB                 | 1        | 1.96%   |
| WDC WD6400AAKS-22A7B2 640GB             | 1        | 1.96%   |
| WDC WD5000AVVS-63ZWB0 500GB             | 1        | 1.96%   |
| WDC WD5000AAKS-75V0A0 500GB             | 1        | 1.96%   |
| WDC WD50 00LPLX-08ZNTT0 500GB           | 1        | 1.96%   |
| WDC WD3200AAKS-75L9A0 320GB             | 1        | 1.96%   |
| WDC WD2500AAKX-07U6AA0 250GB            | 1        | 1.96%   |
| WDC WD2500AAJS-00L7A0 250GB             | 1        | 1.96%   |
| WDC WD1600BEVT-22ZCT0 160GB             | 1        | 1.96%   |
| WDC WD1600AAJS-08L7A0 160GB             | 1        | 1.96%   |
| WDC WD10EZEX-60WN4A0 1TB                | 1        | 1.96%   |
| WDC WD10EADS-00M2B0 1TB                 | 1        | 1.96%   |
| Toshiba DT01ACA100 1TB                  | 1        | 1.96%   |
| Toshiba DT01ACA050 500GB                | 1        | 1.96%   |
| Seagate ST975042 0AS 752GB              | 1        | 1.96%   |
| Seagate ST9250315AS 250GB               | 1        | 1.96%   |
| Seagate ST500DM002-1BD142 500GB         | 1        | 1.96%   |
| Seagate ST3500413AS 500GB               | 1        | 1.96%   |
| Seagate ST3500312CS 500GB               | 1        | 1.96%   |
| Seagate ST3320418AS 320GB               | 1        | 1.96%   |
| Seagate ST2000VM003-1ET164 2TB          | 1        | 1.96%   |
| Seagate BarraCuda Q5 ZP500CV30001 500GB | 1        | 1.96%   |
| SanDisk NVMe SSD Drive 500GB            | 1        | 1.96%   |
| Samsung SSD 850 EVO 500GB               | 1        | 1.96%   |
| Samsung SSD 850 EVO 250GB               | 1        | 1.96%   |
| Samsung SSD 840 PRO Series 512GB        | 1        | 1.96%   |
| Samsung MZVPV256HDGL-000H1 256GB        | 1        | 1.96%   |
| Samsung HN-M320MBB 320GB                | 1        | 1.96%   |
| Samsung HD753LJ 752GB                   | 1        | 1.96%   |
| Samsung HD322GJ 320GB                   | 1        | 1.96%   |
| Samsung HD154UI 1TB                     | 1        | 1.96%   |
| Samsung HD103SJ 1TB                     | 1        | 1.96%   |
| Patriot P210 256GB SSD                  | 1        | 1.96%   |
| Kingston SV300S37A480G 480GB SSD        | 1        | 1.96%   |
| Kingston SA400S37120G 120GB SSD         | 1        | 1.96%   |
| Kingston SA400M8240G 240GB SSD          | 1        | 1.96%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 12       | 12     | 37.5%   |
| Seagate             | 10       | 11     | 31.25%  |
| Samsung Electronics | 5        | 12     | 15.63%  |
| Toshiba             | 2        | 2      | 6.25%   |
| Hitachi             | 2        | 2      | 6.25%   |
| HGST                | 1        | 1      | 3.13%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 3        | 6      | 25%     |
| Kingston            | 3        | 3      | 25%     |
| Patriot             | 1        | 1      | 8.33%   |
| Intel               | 1        | 1      | 8.33%   |
| Gigabyte Technology | 1        | 1      | 8.33%   |
| ASMedia             | 1        | 1      | 8.33%   |
| A-DATA Technology   | 1        | 1      | 8.33%   |
| Unknown             | 1        | 1      | 8.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 24       | 40     | 63.16%  |
| SSD  | 11       | 15     | 28.95%  |
| NVMe | 3        | 5      | 7.89%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 30       | 52     | 88.24%  |
| NVMe | 3        | 5      | 8.82%   |
| SAS  | 1        | 3      | 2.94%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 25       | 37     | 69.44%  |
| 0.51-1.0   | 7        | 14     | 19.44%  |
| 1.01-2.0   | 4        | 4      | 11.11%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 251-500    | 9        | 29.03%  |
| 101-250    | 7        | 22.58%  |
| 501-1000   | 5        | 16.13%  |
| 2001-3000  | 4        | 12.9%   |
| 51-100     | 3        | 9.68%   |
| 21-50      | 1        | 3.23%   |
| 1-20       | 1        | 3.23%   |
| Unknown    | 1        | 3.23%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 13       | 41.94%  |
| 21-50     | 6        | 19.35%  |
| 251-500   | 3        | 9.68%   |
| 101-250   | 2        | 6.45%   |
| 1001-2000 | 2        | 6.45%   |
| 51-100    | 2        | 6.45%   |
| 2001-3000 | 1        | 3.23%   |
| 501-1000  | 1        | 3.23%   |
| Unknown   | 1        | 3.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                          | Desktops | Drives | Percent |
|--------------------------------|----------|--------|---------|
| WDC WD5000AVVS-63ZWB0 500GB    | 1        | 1      | 14.29%  |
| WDC WD1600AAJS-08L7A0 160GB    | 1        | 1      | 14.29%  |
| WDC WD10EADS-00M2B0 1TB        | 1        | 1      | 14.29%  |
| Seagate ST9250315AS 250GB      | 1        | 1      | 14.29%  |
| Seagate ST3500413AS 500GB      | 1        | 1      | 14.29%  |
| Seagate ST2000DM008-2FR102 2TB | 1        | 1      | 14.29%  |
| Unknown                        | 1        | 1      | 14.29%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 3        | 3      | 42.86%  |
| Seagate | 3        | 3      | 42.86%  |
| Unknown | 1        | 1      | 14.29%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 3        | 3      | 50%     |
| Seagate | 3        | 3      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 6        | 6      | 85.71%  |
| SSD  | 1        | 1      | 14.29%  |

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
| Works    | 18       | 25     | 51.43%  |
| Detected | 10       | 28     | 28.57%  |
| Malfunc  | 7        | 7      | 20%     |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 19       | 52.78%  |
| AMD                       | 8        | 22.22%  |
| Nvidia                    | 2        | 5.56%   |
| VIA Technologies          | 1        | 2.78%   |
| Seagate Technology        | 1        | 2.78%   |
| SanDisk                   | 1        | 2.78%   |
| Samsung Electronics       | 1        | 2.78%   |
| Marvell Technology Group  | 1        | 2.78%   |
| LSI Logic / Symbios Logic | 1        | 2.78%   |
| ADATA Technology          | 1        | 2.78%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 6        | 12.5%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3        | 6.25%   |
| Nvidia MCP61 SATA Controller                                                            | 2        | 4.17%   |
| Nvidia MCP61 IDE                                                                        | 2        | 4.17%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2        | 4.17%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 2        | 4.17%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2        | 4.17%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2        | 4.17%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 1        | 2.08%   |
| VIA VT8237A SATA 2-Port Controller                                                      | 1        | 2.08%   |
| Seagate BarraCuda Q5 NVMe SSD (DRAM-less)                                               | 1        | 2.08%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                                   | 1        | 2.08%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 1        | 2.08%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                               | 1        | 2.08%   |
| LSI Logic / Symbios Logic SAS1064ET PCI-Express Fusion-MPT SAS                          | 1        | 2.08%   |
| Intel SATA Controller [RAID mode]                                                       | 1        | 2.08%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1        | 2.08%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 1        | 2.08%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 1        | 2.08%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1        | 2.08%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1        | 2.08%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1        | 2.08%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1        | 2.08%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                    | 1        | 2.08%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1        | 2.08%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1        | 2.08%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 2.08%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 2.08%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 1        | 2.08%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1        | 2.08%   |
| AMD X370 Series Chipset SATA Controller                                                 | 1        | 2.08%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 1        | 2.08%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1        | 2.08%   |
| AMD 400 Series Chipset SATA Controller                                                  | 1        | 2.08%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 1        | 2.08%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 19       | 48.72%  |
| IDE  | 13       | 33.33%  |
| NVMe | 3        | 7.69%   |
| RAID | 2        | 5.13%   |
| SAS  | 1        | 2.56%   |
| SCSI | 1        | 2.56%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 20       | 66.67%  |
| AMD    | 10       | 33.33%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel Core i5-2500 CPU @ 3.30GHz             | 2        | 6.67%   |
| Intel Xeon CPU E5-2687W 0 @ 3.10GHz          | 1        | 3.33%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz       | 1        | 3.33%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz  | 1        | 3.33%   |
| Intel Core i7-4790 CPU @ 3.60GHz             | 1        | 3.33%   |
| Intel Core i7-3770 CPU @ 3.40GHz             | 1        | 3.33%   |
| Intel Core i7 CPU 860 @ 2.80GHz              | 1        | 3.33%   |
| Intel Core i5-6500 CPU @ 3.20GHz             | 1        | 3.33%   |
| Intel Core i5-4460 CPU @ 3.20GHz             | 1        | 3.33%   |
| Intel Core i5-3570K CPU @ 3.40GHz            | 1        | 3.33%   |
| Intel Core i5-10400 CPU @ 2.90GHz            | 1        | 3.33%   |
| Intel Core i5 CPU 660 @ 3.33GHz              | 1        | 3.33%   |
| Intel Core i3 CPU 530 @ 2.93GHz              | 1        | 3.33%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz        | 1        | 3.33%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz         | 1        | 3.33%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz         | 1        | 3.33%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz         | 1        | 3.33%   |
| Intel Core 2 CPU 6300 @ 1.86GHz              | 1        | 3.33%   |
| Intel Atom CPU N280 @ 1.66GHz                | 1        | 3.33%   |
| AMD Sempron 145 Processor                    | 1        | 3.33%   |
| AMD Ryzen 9 5900X 12-Core Processor          | 1        | 3.33%   |
| AMD Ryzen 7 1800X Eight-Core Processor       | 1        | 3.33%   |
| AMD Ryzen 3 3100 4-Core Processor            | 1        | 3.33%   |
| AMD PRO A8-8600B R6, 10 Compute Cores 4C+6G  | 1        | 3.33%   |
| AMD Phenom II X6 1045T Processor             | 1        | 3.33%   |
| AMD Athlon II X3 440 Processor               | 1        | 3.33%   |
| AMD Athlon II X2 B22 Processor               | 1        | 3.33%   |
| AMD A6-7480 Radeon R5, 8 Compute Cores 2C+6G | 1        | 3.33%   |
| AMD A6-3600 APU with Radeon HD Graphics      | 1        | 3.33%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 7        | 23.33%  |
| Intel Core i7           | 3        | 10%     |
| Intel Core 2 Duo        | 3        | 10%     |
| AMD A6                  | 2        | 6.67%   |
| Intel Xeon              | 1        | 3.33%   |
| Intel Pentium Gold      | 1        | 3.33%   |
| Intel Pentium Dual-Core | 1        | 3.33%   |
| Intel Core i3           | 1        | 3.33%   |
| Intel Core 2 Quad       | 1        | 3.33%   |
| Intel Core 2            | 1        | 3.33%   |
| Intel Atom              | 1        | 3.33%   |
| AMD Sempron             | 1        | 3.33%   |
| AMD Ryzen 9             | 1        | 3.33%   |
| AMD Ryzen 7             | 1        | 3.33%   |
| AMD Ryzen 3             | 1        | 3.33%   |
| AMD PRO A8              | 1        | 3.33%   |
| AMD Phenom II X6        | 1        | 3.33%   |
| AMD Athlon II X3        | 1        | 3.33%   |
| AMD Athlon II X2        | 1        | 3.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 11       | 36.67%  |
| 2      | 10       | 33.33%  |
| 1      | 3        | 10%     |
| 8      | 2        | 6.67%   |
| 6      | 2        | 6.67%   |
| 12     | 1        | 3.33%   |
| 3      | 1        | 3.33%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 30       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 17       | 56.67%  |
| 2      | 13       | 43.33%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 29       | 96.67%  |
| 32-bit         | 1        | 3.33%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 4        | 13.33%  |
| 0x306c3    | 2        | 6.67%   |
| 0x306a9    | 2        | 6.67%   |
| 0x206a7    | 2        | 6.67%   |
| 0x20652    | 2        | 6.67%   |
| 0x1067a    | 2        | 6.67%   |
| 0x0600611a | 2        | 6.67%   |
| 0xa0653    | 1        | 3.33%   |
| 0x6fd      | 1        | 3.33%   |
| 0x6fb      | 1        | 3.33%   |
| 0x6f2      | 1        | 3.33%   |
| 0x506e3    | 1        | 3.33%   |
| 0x206d7    | 1        | 3.33%   |
| 0x106e5    | 1        | 3.33%   |
| 0x0a201016 | 1        | 3.33%   |
| 0x08701021 | 1        | 3.33%   |
| 0x08001138 | 1        | 3.33%   |
| 0x03000027 | 1        | 3.33%   |
| 0x010000dc | 1        | 3.33%   |
| 0x010000db | 1        | 3.33%   |
| 0x010000c8 | 1        | 3.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| K10         | 4        | 13.33%  |
| SandyBridge | 3        | 10%     |
| Penryn      | 3        | 10%     |
| Core        | 3        | 10%     |
| Westmere    | 2        | 6.67%   |
| IvyBridge   | 2        | 6.67%   |
| Haswell     | 2        | 6.67%   |
| Excavator   | 2        | 6.67%   |
| Zen 3       | 1        | 3.33%   |
| Zen 2       | 1        | 3.33%   |
| Zen         | 1        | 3.33%   |
| Skylake     | 1        | 3.33%   |
| Nehalem     | 1        | 3.33%   |
| KabyLake    | 1        | 3.33%   |
| K10 Llano   | 1        | 3.33%   |
| CometLake   | 1        | 3.33%   |
| Bonnell     | 1        | 3.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Intel            | 11       | 34.38%  |
| Nvidia           | 10       | 31.25%  |
| AMD              | 10       | 31.25%  |
| VIA Technologies | 1        | 3.13%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 82Q963/Q965 Integrated Graphics Controller                            | 2        | 6.06%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 6.06%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 2        | 6.06%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                           | 1        | 3.03%   |
| Nvidia GT218 [GeForce 310]                                                  | 1        | 3.03%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 3.03%   |
| Nvidia GT200GL [Quadro FX 3800]                                             | 1        | 3.03%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 3.03%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 3.03%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 3.03%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 1        | 3.03%   |
| Nvidia GA106 [Geforce RTX 3050]                                             | 1        | 3.03%   |
| Nvidia G96CGL [Quadro FX 580]                                               | 1        | 3.03%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 1        | 3.03%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 3.03%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 1        | 3.03%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1        | 3.03%   |
| Intel HD Graphics 530                                                       | 1        | 3.03%   |
| Intel Core Processor Integrated Graphics Controller                         | 1        | 3.03%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 3.03%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                   | 1        | 3.03%   |
| AMD Turks GL [FirePro V4900]                                                | 1        | 3.03%   |
| AMD Sumo [Radeon HD 6530D]                                                  | 1        | 3.03%   |
| AMD RS880 [Radeon HD 4200]                                                  | 1        | 3.03%   |
| AMD Redwood LE [Radeon HD 5550/5570/5630/6390/6490/7570]                    | 1        | 3.03%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 1        | 3.03%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 1        | 3.03%   |
| AMD Cypress XT [Radeon HD 5870]                                             | 1        | 3.03%   |
| AMD Barts PRO [Radeon HD 6850]                                              | 1        | 3.03%   |
| AMD Barts LE [Radeon HD 6790]                                               | 1        | 3.03%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 9        | 30%     |
| 1 x Intel      | 9        | 30%     |
| 1 x AMD        | 9        | 30%     |
| 2 x Intel      | 1        | 3.33%   |
| 1 x VIA        | 1        | 3.33%   |
| Intel + Nvidia | 1        | 3.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 24       | 80%     |
| Unknown     | 4        | 13.33%  |
| Proprietary | 2        | 6.67%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 16       | 51.61%  |
| 0.51-1.0   | 5        | 16.13%  |
| 0.01-0.5   | 5        | 16.13%  |
| 7.01-8.0   | 2        | 6.45%   |
| 1.01-2.0   | 2        | 6.45%   |
| 3.01-4.0   | 1        | 3.23%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 7        | 28%     |
| Goldstar            | 5        | 20%     |
| Dell                | 3        | 12%     |
| AOC                 | 3        | 12%     |
| BenQ                | 2        | 8%      |
| Unknown             | 1        | 4%      |
| Toshiba             | 1        | 4%      |
| JCH                 | 1        | 4%      |
| Hewlett-Packard     | 1        | 4%      |
| Acer                | 1        | 4%      |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 1        | 3.57%   |
| Toshiba TV TSB0206 1920x1080 890x500mm 40.2-inch                      | 1        | 3.57%   |
| Samsung Electronics SyncMaster SAM0581 1920x1080 477x268mm 21.5-inch  | 1        | 3.57%   |
| Samsung Electronics SyncMaster SAM0116 1024x768 267x200mm 13.1-inch   | 1        | 3.57%   |
| Samsung Electronics SMB1630N SAM0630 1366x768 344x194mm 15.5-inch     | 1        | 3.57%   |
| Samsung Electronics SA300/SA350 SAM078F 1920x1080 477x268mm 21.5-inch | 1        | 3.57%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch     | 1        | 3.57%   |
| Samsung Electronics S22C450 SAM09C5 1920x1080 477x268mm 21.5-inch     | 1        | 3.57%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1        | 3.57%   |
| JCH F24 JCH1919 1920x1080 520x310mm 23.8-inch                         | 1        | 3.57%   |
| Hewlett-Packard w2207 HWP26A8 1680x1050 473x296mm 22.0-inch           | 1        | 3.57%   |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                   | 1        | 3.57%   |
| Goldstar W2042 GSM4E7E 1680x1050 434x270mm 20.1-inch                  | 1        | 3.57%   |
| Goldstar TV GSM9CF6 1360x768 700x392mm 31.6-inch                      | 1        | 3.57%   |
| Goldstar T710SH GSM436B 1280x960 310x230mm 15.2-inch                  | 1        | 3.57%   |
| Goldstar L1953H GSM4B3D 1280x1024 338x270mm 17.0-inch                 | 1        | 3.57%   |
| Goldstar L1953H GSM4B3C 1280x1024 338x270mm 17.0-inch                 | 1        | 3.57%   |
| Goldstar 23MP55 GSM5A23 1920x1080 510x290mm 23.1-inch                 | 1        | 3.57%   |
| Dell LCD Monitor S2715H 3840x1080                                     | 1        | 3.57%   |
| Dell LCD Monitor S2715H                                               | 1        | 3.57%   |
| Dell IN1930 DELF03B 1366x768 410x230mm 18.5-inch                      | 1        | 3.57%   |
| Dell E176FP DELA014 1280x1024 338x270mm 17.0-inch                     | 1        | 3.57%   |
| BenQ FP202WA BNQ76C2 1680x1050 376x301mm 19.0-inch                    | 1        | 3.57%   |
| BenQ E900HD BNQ7910 1366x768 410x230mm 18.5-inch                      | 1        | 3.57%   |
| AOC LM729 AOCA784 1280x1024 340x270mm 17.1-inch                       | 1        | 3.57%   |
| AOC 2475W AOC2475 1920x1080 527x296mm 23.8-inch                       | 1        | 3.57%   |
| AOC 2450W AOC2450 1920x1080 521x293mm 23.5-inch                       | 1        | 3.57%   |
| Acer S271HL ACR02CA 1920x1080 598x336mm 27.0-inch                     | 1        | 3.57%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 11       | 40.74%  |
| 1680x1050 (WSXGA+) | 3        | 11.11%  |
| 1366x768 (WXGA)    | 3        | 11.11%  |
| 1280x1024 (SXGA)   | 3        | 11.11%  |
| 3840x1080          | 1        | 3.7%    |
| 2288x1287          | 1        | 3.7%    |
| 1600x900 (HD+)     | 1        | 3.7%    |
| 1360x768           | 1        | 3.7%    |
| 1280x960           | 1        | 3.7%    |
| 1024x768 (XGA)     | 1        | 3.7%    |
| Unknown            | 1        | 3.7%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 5        | 19.23%  |
| 21      | 3        | 11.54%  |
| 20      | 3        | 11.54%  |
| 17      | 3        | 11.54%  |
| 18      | 2        | 7.69%   |
| 142     | 1        | 3.85%   |
| 74      | 1        | 3.85%   |
| 72      | 1        | 3.85%   |
| 27      | 1        | 3.85%   |
| 24      | 1        | 3.85%   |
| 22      | 1        | 3.85%   |
| 16      | 1        | 3.85%   |
| 15      | 1        | 3.85%   |
| 13      | 1        | 3.85%   |
| Unknown | 1        | 3.85%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 401-500        | 9        | 34.62%  |
| 501-600        | 7        | 26.92%  |
| 301-350        | 5        | 19.23%  |
| 1501-2000      | 2        | 7.69%   |
| More than 2000 | 1        | 3.85%   |
| 201-300        | 1        | 3.85%   |
| Unknown        | 1        | 3.85%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 15       | 57.69%  |
| 16/10   | 4        | 15.38%  |
| 5/4     | 3        | 11.54%  |
| 4/3     | 2        | 7.69%   |
| 1.00    | 1        | 3.85%   |
| Unknown | 1        | 3.85%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 8        | 30.77%  |
| 151-200        | 5        | 19.23%  |
| 141-150        | 5        | 19.23%  |
| More than 1000 | 3        | 11.54%  |
| 81-90          | 1        | 3.85%   |
| 301-350        | 1        | 3.85%   |
| 121-130        | 1        | 3.85%   |
| 101-110        | 1        | 3.85%   |
| Unknown        | 1        | 3.85%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 17       | 68%     |
| 101-120 | 4        | 16%     |
| 1-50    | 3        | 12%     |
| Unknown | 1        | 4%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 25       | 83.33%  |
| 2     | 3        | 10%     |
| 0     | 2        | 6.67%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 14       | 35%     |
| Intel                 | 9        | 22.5%   |
| Ralink Technology     | 3        | 7.5%    |
| Qualcomm Atheros      | 3        | 7.5%    |
| Broadcom              | 3        | 7.5%    |
| Nvidia                | 2        | 5%      |
| Broadcom Limited      | 2        | 5%      |
| VIA Technologies      | 1        | 2.5%    |
| TP-Link               | 1        | 2.5%    |
| NetGear               | 1        | 2.5%    |
| D-Link System         | 1        | 2.5%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                       | Desktops | Percent |
|---------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                           | 11       | 25.58%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                       | 2        | 4.65%   |
| Nvidia MCP61 Ethernet                                                                       | 2        | 4.65%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                       | 2        | 4.65%   |
| VIA VT6102/VT6103 [Rhine-II]                                                                | 1        | 2.33%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                                                       | 1        | 2.33%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                          | 1        | 2.33%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                    | 1        | 2.33%   |
| Ralink RT5370 Wireless Adapter                                                              | 1        | 2.33%   |
| Ralink RT3072 Wireless Adapter                                                              | 1        | 2.33%   |
| Ralink MT7601U Wireless Adapter                                                             | 1        | 2.33%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                                   | 1        | 2.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                            | 1        | 2.33%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]               | 1        | 2.33%   |
| NetGear WNDA4100 802.11abgn 3x3:3 [Ralink RT3573]                                           | 1        | 2.33%   |
| Intel Wireless 8260                                                                         | 1        | 2.33%   |
| Intel Wi-Fi 6 AX200                                                                         | 1        | 2.33%   |
| Intel I211 Gigabit Network Connection                                                       | 1        | 2.33%   |
| Intel Ethernet Controller I225-V                                                            | 1        | 2.33%   |
| Intel Ethernet Connection (2) I219-LM                                                       | 1        | 2.33%   |
| Intel Ethernet Connection (2) I218-V                                                        | 1        | 2.33%   |
| Intel 82578DC Gigabit Network Connection                                                    | 1        | 2.33%   |
| Intel 82566DM Gigabit Network Connection                                                    | 1        | 2.33%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                                        | 1        | 2.33%   |
| D-Link System DWA-160 802.11abgn Xtreme N Dual Band Adapter(rev.A2) [Atheros AR9170+AR9104] | 1        | 2.33%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                                            | 1        | 2.33%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                                     | 1        | 2.33%   |
| Broadcom NetXtreme BCM5721 Gigabit Ethernet PCI Express                                     | 1        | 2.33%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe                                    | 1        | 2.33%   |
| Broadcom Limited NetLink BCM57788 Gigabit Ethernet PCIe                                     | 1        | 2.33%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Ralink Technology     | 3        | 25%     |
| Realtek Semiconductor | 2        | 16.67%  |
| Qualcomm Atheros      | 2        | 16.67%  |
| Intel                 | 2        | 16.67%  |
| TP-Link               | 1        | 8.33%   |
| NetGear               | 1        | 8.33%   |
| D-Link System         | 1        | 8.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                       | Desktops | Percent |
|---------------------------------------------------------------------------------------------|----------|---------|
| TP-Link TL-WN821N Version 5 RTL8192EU                                                       | 1        | 8.33%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                          | 1        | 8.33%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                    | 1        | 8.33%   |
| Ralink RT5370 Wireless Adapter                                                              | 1        | 8.33%   |
| Ralink RT3072 Wireless Adapter                                                              | 1        | 8.33%   |
| Ralink MT7601U Wireless Adapter                                                             | 1        | 8.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                            | 1        | 8.33%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]               | 1        | 8.33%   |
| NetGear WNDA4100 802.11abgn 3x3:3 [Ralink RT3573]                                           | 1        | 8.33%   |
| Intel Wireless 8260                                                                         | 1        | 8.33%   |
| Intel Wi-Fi 6 AX200                                                                         | 1        | 8.33%   |
| D-Link System DWA-160 802.11abgn Xtreme N Dual Band Adapter(rev.A2) [Atheros AR9170+AR9104] | 1        | 8.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 13       | 41.94%  |
| Intel                 | 9        | 29.03%  |
| Broadcom              | 3        | 9.68%   |
| Nvidia                | 2        | 6.45%   |
| Broadcom Limited      | 2        | 6.45%   |
| VIA Technologies      | 1        | 3.23%   |
| Qualcomm Atheros      | 1        | 3.23%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 11       | 35.48%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 6.45%   |
| Nvidia MCP61 Ethernet                                             | 2        | 6.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 6.45%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 3.23%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 3.23%   |
| Intel I211 Gigabit Network Connection                             | 1        | 3.23%   |
| Intel Ethernet Controller I225-V                                  | 1        | 3.23%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 3.23%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 3.23%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 3.23%   |
| Intel 82566DM Gigabit Network Connection                          | 1        | 3.23%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 1        | 3.23%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1        | 3.23%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express           | 1        | 3.23%   |
| Broadcom NetXtreme BCM5721 Gigabit Ethernet PCI Express           | 1        | 3.23%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1        | 3.23%   |
| Broadcom Limited NetLink BCM57788 Gigabit Ethernet PCIe           | 1        | 3.23%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 29       | 72.5%   |
| WiFi     | 11       | 27.5%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 24       | 72.73%  |
| WiFi     | 9        | 27.27%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 24       | 80%     |
| 2     | 6        | 20%     |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 27       | 90%     |
| Yes  | 3        | 10%     |

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
| Intel               | 18       | 41.86%  |
| AMD                 | 12       | 27.91%  |
| Nvidia              | 9        | 20.93%  |
| VIA Technologies    | 1        | 2.33%   |
| Plantronics         | 1        | 2.33%   |
| Creative Labs       | 1        | 2.33%   |
| C-Media Electronics | 1        | 2.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3        | 6%      |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3        | 6%      |
| Nvidia MCP61 High Definition Audio                                         | 2        | 4%      |
| Nvidia High Definition Audio Controller                                    | 2        | 4%      |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 4%      |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2        | 4%      |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2        | 4%      |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2        | 4%      |
| AMD Starship/Matisse HD Audio Controller                                   | 2        | 4%      |
| AMD SBx00 Azalia (Intel HDA)                                               | 2        | 4%      |
| AMD Kabini HDMI/DP Audio                                                   | 2        | 4%      |
| AMD FCH Azalia Controller                                                  | 2        | 4%      |
| AMD Barts HDMI Audio [Radeon HD 6790/6850/6870 / 7720 OEM]                 | 2        | 4%      |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller             | 1        | 2%      |
| Plantronics USB DSP v4 Audio Interface                                     | 1        | 2%      |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 2%      |
| Nvidia GK104 HDMI Audio Controller                                         | 1        | 2%      |
| Nvidia GA106 High Definition Audio Controller                              | 1        | 2%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1        | 2%      |
| Intel Comet Lake PCH-V cAVS                                                | 1        | 2%      |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1        | 2%      |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1        | 2%      |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1        | 2%      |
| Intel 200 Series PCH HD Audio                                              | 1        | 2%      |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1        | 2%      |
| Creative Labs CA0106/CA0111 [SB Live!/Audigy/X-Fi Series]                  | 1        | 2%      |
| C-Media Electronics USB Audio Device                                       | 1        | 2%      |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 1        | 2%      |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 1        | 2%      |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 1        | 2%      |
| AMD Navi 10 HDMI Audio                                                     | 1        | 2%      |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1        | 2%      |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1        | 2%      |
| AMD Cypress HDMI Audio [Radeon HD 5830/5850/5870 / 6850/6870 Rebrand]      | 1        | 2%      |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]        | 1        | 2%      |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 7        | 29.17%  |
| Kingston            | 4        | 16.67%  |
| Samsung Electronics | 3        | 12.5%   |
| G.Skill             | 2        | 8.33%   |
| Corsair             | 2        | 8.33%   |
| Unifosa             | 1        | 4.17%   |
| SK hynix            | 1        | 4.17%   |
| Ramaxel Technology  | 1        | 4.17%   |
| Micron Technology   | 1        | 4.17%   |
| Crucial             | 1        | 4.17%   |
| Avant               | 1        | 4.17%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM 800MT/s                   | 2        | 7.69%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                     | 1        | 3.85%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                | 1        | 3.85%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                 | 1        | 3.85%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s              | 1        | 3.85%   |
| Unknown RAM Module 1024MB DIMM SDRAM                     | 1        | 3.85%   |
| Unifosa RAM GU512303EP0202 2048MB DIMM DDR3 1333MT/s     | 1        | 3.85%   |
| SK hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s     | 1        | 3.85%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s | 1        | 3.85%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s    | 1        | 3.85%   |
| Samsung RAM M3 78T5663EH3-CF7 2GB DIMM DDR2 800MT/s      | 1        | 3.85%   |
| Samsung RAM M3 78T2863RZS-CE6 1GB DIMM DDR2 667MT/s      | 1        | 3.85%   |
| Samsung RAM M3 78T2863QZS-CE6 1GB DIMM DDR2 1639MT/s     | 1        | 3.85%   |
| Ramaxel RAM RMR5030MM58E8F1600 2GB DIMM DDR3 1600MT/s    | 1        | 3.85%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s      | 1        | 3.85%   |
| Kingston RAM Module 8GB DIMM DDR3 1600MT/s               | 1        | 3.85%   |
| Kingston RAM Module 16GB SODIMM DDR4 2133MT/s            | 1        | 3.85%   |
| Kingston RAM KHX1600C9D3/4GX 4096MB DIMM DDR3 1600MT/s   | 1        | 3.85%   |
| Kingston RAM 99U5471-030.A00LF 8GB DIMM DDR3 1333MT/s    | 1        | 3.85%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s       | 1        | 3.85%   |
| G.Skill RAM F2-6400CL4-1GBPK 1GB DIMM DDR2 800MT/s       | 1        | 3.85%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1800MT/s    | 1        | 3.85%   |
| Corsair RAM CMZ4GX3M1A1600C9 4GB DIMM DDR3 1600MT/s      | 1        | 3.85%   |
| Corsair RAM CMK16GX4M2D3600C18 8GB DIMM DDR4 3600MT/s    | 1        | 3.85%   |
| Avant RAM W641GU49J2320N6 8GB DIMM DDR4 2666MT/s         | 1        | 3.85%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 9        | 40.91%  |
| DDR4    | 4        | 18.18%  |
| DDR2    | 3        | 13.64%  |
| Unknown | 3        | 13.64%  |
| SDRAM   | 2        | 9.09%   |
| DDR     | 1        | 4.55%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 18       | 85.71%  |
| SODIMM | 3        | 14.29%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 8        | 33.33%  |
| 2048  | 8        | 33.33%  |
| 4096  | 4        | 16.67%  |
| 1024  | 3        | 12.5%   |
| 16384 | 1        | 4.17%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 5        | 20.83%  |
| 1333    | 5        | 20.83%  |
| 800     | 4        | 16.67%  |
| 3666    | 1        | 4.17%   |
| 3200    | 1        | 4.17%   |
| 2666    | 1        | 4.17%   |
| 2400    | 1        | 4.17%   |
| 2133    | 1        | 4.17%   |
| 2048    | 1        | 4.17%   |
| 1800    | 1        | 4.17%   |
| 1639    | 1        | 4.17%   |
| 667     | 1        | 4.17%   |
| Unknown | 1        | 4.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 1        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Samsung CLP-325 Color Laser Printer | 1        | 100%    |

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
| 0     | 23       | 76.67%  |
| 1     | 6        | 20%     |
| 2     | 1        | 3.33%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Graphics card | 5        | 62.5%   |
| Net/wireless  | 2        | 25%     |
| Camera        | 1        | 12.5%   |

