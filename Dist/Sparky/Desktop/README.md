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

Total: 47

| Vendor   | Model                | Probe                                                      | Date         |
|----------|----------------------|------------------------------------------------------------|--------------|
| ASUSTek  | PRIME H510M-K        | [fc06ed6b10](https://linux-hardware.org/?probe=fc06ed6b10) | Feb 20, 2024 |
| Lenovo   | 315F NOK             | [620272c63f](https://linux-hardware.org/?probe=620272c63f) | Feb 13, 2024 |
| HP       | 212B                 | [cb5e65ba08](https://linux-hardware.org/?probe=cb5e65ba08) | Jan 21, 2024 |
| Acer     | Aspire X3950         | [09dfa7ff4b](https://linux-hardware.org/?probe=09dfa7ff4b) | Jan 04, 2024 |
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
| Sparky 6    | 7        | 19.44%  |
| Sparky 7    | 5        | 13.89%  |
| Sparky 8    | 3        | 8.33%   |
| Sparky 7.1  | 3        | 8.33%   |
| Sparky 5.12 | 3        | 8.33%   |
| Sparky 7.0  | 2        | 5.56%   |
| Sparky 6.7  | 2        | 5.56%   |
| Sparky 6.3  | 2        | 5.56%   |
| Sparky 6.2  | 2        | 5.56%   |
| Sparky 6.1  | 2        | 5.56%   |
| Sparky 7.2  | 1        | 2.78%   |
| Sparky 6.6  | 1        | 2.78%   |
| Sparky 6.5  | 1        | 2.78%   |
| Sparky 6.0  | 1        | 2.78%   |
| Sparky 5.10 | 1        | 2.78%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Sparky | 34       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Desktops | Percent |
|---------------------------|----------|---------|
| 6.1.0-13-amd64            | 3        | 8.11%   |
| 6.6.15-amd64              | 1        | 2.7%    |
| 6.6.13-amd64              | 1        | 2.7%    |
| 6.4.0-1-amd64             | 1        | 2.7%    |
| 6.1.0-9-amd64             | 1        | 2.7%    |
| 6.1.0-7-amd64             | 1        | 2.7%    |
| 6.1.0-3-amd64             | 1        | 2.7%    |
| 6.1.0-17-amd64            | 1        | 2.7%    |
| 6.1.0-11-amd64            | 1        | 2.7%    |
| 6.0.11-x64v2-rt14-xanmod1 | 1        | 2.7%    |
| 6.0.0-5-amd64             | 1        | 2.7%    |
| 5.9.13-sparky-amd64       | 1        | 2.7%    |
| 5.7.2-sparky-amd64        | 1        | 2.7%    |
| 5.6.0-2-amd64             | 1        | 2.7%    |
| 5.18.3-sparky-amd64       | 1        | 2.7%    |
| 5.18.0-4-amd64            | 1        | 2.7%    |
| 5.18.0-2-amd64            | 1        | 2.7%    |
| 5.17.3-sparky-amd64       | 1        | 2.7%    |
| 5.16.5-sparky-amd64       | 1        | 2.7%    |
| 5.10.0-9-amd64            | 1        | 2.7%    |
| 5.10.0-8-amd64            | 1        | 2.7%    |
| 5.10.0-7-amd64            | 1        | 2.7%    |
| 5.10.0-6-amd64            | 1        | 2.7%    |
| 5.10.0-3-amd64            | 1        | 2.7%    |
| 5.10.0-26-amd64           | 1        | 2.7%    |
| 5.10.0-23-amd64           | 1        | 2.7%    |
| 5.10.0-21-amd64           | 1        | 2.7%    |
| 5.10.0-2-amd64            | 1        | 2.7%    |
| 5.10.0-14-amd64           | 1        | 2.7%    |
| 5.10.0-12-amd64           | 1        | 2.7%    |
| 5.10.0-11-686             | 1        | 2.7%    |
| 4.19.0-8-amd64            | 1        | 2.7%    |
| 4.19.0-12-amd64           | 1        | 2.7%    |
| 4.19.0-10-amd64           | 1        | 2.7%    |
| 4.19.0-10-686             | 1        | 2.7%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10.0  | 12       | 32.43%  |
| 6.1.0   | 8        | 21.62%  |
| 4.19.0  | 4        | 10.81%  |
| 5.18.0  | 2        | 5.41%   |
| 6.6.15  | 1        | 2.7%    |
| 6.6.13  | 1        | 2.7%    |
| 6.4.0   | 1        | 2.7%    |
| 6.0.11  | 1        | 2.7%    |
| 6.0.0   | 1        | 2.7%    |
| 5.9.13  | 1        | 2.7%    |
| 5.7.2   | 1        | 2.7%    |
| 5.6.0   | 1        | 2.7%    |
| 5.18.3  | 1        | 2.7%    |
| 5.17.3  | 1        | 2.7%    |
| 5.16.5  | 1        | 2.7%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 12       | 33.33%  |
| 6.1     | 8        | 22.22%  |
| 4.19    | 4        | 11.11%  |
| 5.18    | 3        | 8.33%   |
| 6.6     | 2        | 5.56%   |
| 6.4     | 1        | 2.78%   |
| 6.0     | 1        | 2.78%   |
| 5.9     | 1        | 2.78%   |
| 5.7     | 1        | 2.78%   |
| 5.6     | 1        | 2.78%   |
| 5.17    | 1        | 2.78%   |
| 5.16    | 1        | 2.78%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 32       | 94.12%  |
| i686   | 2        | 5.88%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| XFCE             | 15       | 44.12%  |
| LXQt             | 8        | 23.53%  |
| X-Cinnamon       | 3        | 8.82%   |
| KDE5             | 2        | 5.88%   |
| lightdm-xsession | 1        | 2.94%   |
| ICEWM            | 1        | 2.94%   |
| GNOME Flashback  | 1        | 2.94%   |
| GNOME            | 1        | 2.94%   |
| Budgie           | 1        | 2.94%   |
| Unknown          | 1        | 2.94%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 34       | 97.14%  |
| Tty  | 1        | 2.86%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 12       | 35.29%  |
| SDDM    | 8        | 23.53%  |
| LightDM | 7        | 20.59%  |
| TDM     | 6        | 17.65%  |
| GDM     | 1        | 2.94%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 10       | 29.41%  |
| pt_BR | 5        | 14.71%  |
| en_GB | 4        | 11.76%  |
| fr_FR | 3        | 8.82%   |
| es_ES | 2        | 5.88%   |
| sv_SE | 1        | 2.94%   |
| ru_RU | 1        | 2.94%   |
| it_IT | 1        | 2.94%   |
| es_US | 1        | 2.94%   |
| es_AR | 1        | 2.94%   |
| en_ZA | 1        | 2.94%   |
| en_DK | 1        | 2.94%   |
| en_CA | 1        | 2.94%   |
| de_CH | 1        | 2.94%   |
| cs_CZ | 1        | 2.94%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 24       | 70.59%  |
| EFI  | 10       | 29.41%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Ext4  | 31       | 91.18%  |
| Btrfs | 2        | 5.88%   |
| Zfs   | 1        | 2.94%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| MBR     | 12       | 35.29%  |
| Unknown | 12       | 35.29%  |
| GPT     | 10       | 29.41%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 27       | 79.41%  |
| Yes       | 7        | 20.59%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 22       | 64.71%  |
| Yes       | 12       | 35.29%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 7        | 20.59%  |
| ASUSTek Computer    | 6        | 17.65%  |
| Gigabyte Technology | 5        | 14.71%  |
| Intel               | 4        | 11.76%  |
| MSI                 | 3        | 8.82%   |
| Dell                | 3        | 8.82%   |
| Acer                | 3        | 8.82%   |
| Lenovo              | 1        | 2.94%   |
| Foxconn             | 1        | 2.94%   |
| Unknown             | 1        | 2.94%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| MSI MS-7C09                         | 1        | 2.94%   |
| MSI MS-7B86                         | 1        | 2.94%   |
| MSI MS-7721                         | 1        | 2.94%   |
| Lenovo ThinkCentre M90s 11D2CTO1WW  | 1        | 2.94%   |
| Intel H61                           | 1        | 2.94%   |
| Intel H55                           | 1        | 2.94%   |
| Intel DG43RK AAE78175-402           | 1        | 2.94%   |
| Intel DG41TY AAE47335-300           | 1        | 2.94%   |
| HP Z440 Workstation                 | 1        | 2.94%   |
| HP Z420 Workstation                 | 1        | 2.94%   |
| HP t5740                            | 1        | 2.94%   |
| HP rp5700 Business System           | 1        | 2.94%   |
| HP EliteDesk 800 G2 DM 65W          | 1        | 2.94%   |
| HP EliteDesk 705 G2 MINI            | 1        | 2.94%   |
| HP Compaq dc7700 Ultra-slim Desktop | 1        | 2.94%   |
| Gigabyte X570S AORUS PRO AX         | 1        | 2.94%   |
| Gigabyte M68M-S2P                   | 1        | 2.94%   |
| Gigabyte H97-Gaming 3               | 1        | 2.94%   |
| Gigabyte H410M H                    | 1        | 2.94%   |
| Gigabyte G41M-ES2L                  | 1        | 2.94%   |
| Foxconn p6-2010fr                   | 1        | 2.94%   |
| Dell OptiPlex 7010                  | 1        | 2.94%   |
| Dell OptiPlex 580                   | 1        | 2.94%   |
| Dell Inspiron 620                   | 1        | 2.94%   |
| ASUS PRIME H510M-K                  | 1        | 2.94%   |
| ASUS P7H55-M                        | 1        | 2.94%   |
| ASUS M5A78L-M LX/BR                 | 1        | 2.94%   |
| ASUS M4N68T-M                       | 1        | 2.94%   |
| ASUS G20AJ                          | 1        | 2.94%   |
| ASUS CROSSHAIR VI HERO              | 1        | 2.94%   |
| Acer Aspire X3950                   | 1        | 2.94%   |
| Acer Aspire X3900                   | 1        | 2.94%   |
| Acer Aspire X3470                   | 1        | 2.94%   |
| Unknown                             | 1        | 2.94%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Acer Aspire         | 3        | 8.82%   |
| HP EliteDesk        | 2        | 5.88%   |
| Dell OptiPlex       | 2        | 5.88%   |
| MSI MS-7C09         | 1        | 2.94%   |
| MSI MS-7B86         | 1        | 2.94%   |
| MSI MS-7721         | 1        | 2.94%   |
| Lenovo ThinkCentre  | 1        | 2.94%   |
| Intel H61           | 1        | 2.94%   |
| Intel H55           | 1        | 2.94%   |
| Intel DG43RK        | 1        | 2.94%   |
| Intel DG41TY        | 1        | 2.94%   |
| HP Z440             | 1        | 2.94%   |
| HP Z420             | 1        | 2.94%   |
| HP t5740            | 1        | 2.94%   |
| HP rp5700           | 1        | 2.94%   |
| HP Compaq           | 1        | 2.94%   |
| Gigabyte X570S      | 1        | 2.94%   |
| Gigabyte M68M-S2P   | 1        | 2.94%   |
| Gigabyte H97-Gaming | 1        | 2.94%   |
| Gigabyte H410M      | 1        | 2.94%   |
| Gigabyte G41M-ES2L  | 1        | 2.94%   |
| Foxconn p6-2010fr   | 1        | 2.94%   |
| Dell Inspiron       | 1        | 2.94%   |
| ASUS PRIME          | 1        | 2.94%   |
| ASUS P7H55-M        | 1        | 2.94%   |
| ASUS M5A78L-M       | 1        | 2.94%   |
| ASUS M4N68T-M       | 1        | 2.94%   |
| ASUS G20AJ          | 1        | 2.94%   |
| ASUS CROSSHAIR      | 1        | 2.94%   |
| Unknown             | 1        | 2.94%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2009 | 6        | 17.65%  |
| 2021 | 4        | 11.76%  |
| 2011 | 4        | 11.76%  |
| 2015 | 3        | 8.82%   |
| 2014 | 3        | 8.82%   |
| 2010 | 3        | 8.82%   |
| 2007 | 3        | 8.82%   |
| 2012 | 2        | 5.88%   |
| 2020 | 1        | 2.94%   |
| 2019 | 1        | 2.94%   |
| 2018 | 1        | 2.94%   |
| 2017 | 1        | 2.94%   |
| 2016 | 1        | 2.94%   |
| 2013 | 1        | 2.94%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 34       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 34       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 34       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 3.01-4.0    | 11       | 32.35%  |
| 8.01-16.0   | 7        | 20.59%  |
| 16.01-24.0  | 6        | 17.65%  |
| 4.01-8.0    | 3        | 8.82%   |
| 32.01-64.0  | 2        | 5.88%   |
| 1.01-2.0    | 2        | 5.88%   |
| 24.01-32.0  | 1        | 2.94%   |
| 2.01-3.0    | 1        | 2.94%   |
| 64.01-256.0 | 1        | 2.94%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1.01-2.0 | 21       | 58.33%  |
| 2.01-3.0 | 10       | 27.78%  |
| 4.01-8.0 | 3        | 8.33%   |
| 0.51-1.0 | 2        | 5.56%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 21       | 56.76%  |
| 2      | 8        | 21.62%  |
| 4      | 4        | 10.81%  |
| 6      | 2        | 5.41%   |
| 3      | 2        | 5.41%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 22       | 64.71%  |
| Yes       | 12       | 35.29%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 32       | 94.12%  |
| No        | 2        | 5.88%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 21       | 61.76%  |
| Yes       | 13       | 38.24%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 28       | 82.35%  |
| Yes       | 6        | 17.65%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| France       | 5        | 14.71%  |
| Brazil       | 5        | 14.71%  |
| UK           | 3        | 8.82%   |
| Sweden       | 3        | 8.82%   |
| Indonesia    | 2        | 5.88%   |
| Argentina    | 2        | 5.88%   |
| Venezuela    | 1        | 2.94%   |
| USA          | 1        | 2.94%   |
| Switzerland  | 1        | 2.94%   |
| Spain        | 1        | 2.94%   |
| South Africa | 1        | 2.94%   |
| Russia       | 1        | 2.94%   |
| Netherlands  | 1        | 2.94%   |
| Mexico       | 1        | 2.94%   |
| Lebanon      | 1        | 2.94%   |
| Italy        | 1        | 2.94%   |
| Germany      | 1        | 2.94%   |
| Czechia      | 1        | 2.94%   |
| Canada       | 1        | 2.94%   |
| Belgium      | 1        | 2.94%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Woking              | 1        | 2.78%   |
| West Palm Beach     | 1        | 2.78%   |
| Uppsala             | 1        | 2.78%   |
| Trelaze             | 1        | 2.78%   |
| Surabaya            | 1        | 2.78%   |
| Sin el Fil          | 1        | 2.78%   |
| San Cristóbal      | 1        | 2.78%   |
| Rosario             | 1        | 2.78%   |
| Rio de Janeiro      | 1        | 2.78%   |
| Rio Claro           | 1        | 2.78%   |
| Presidente Prudente | 1        | 2.78%   |
| Posadas             | 1        | 2.78%   |
| Norrköping         | 1        | 2.78%   |
| Moscow              | 1        | 2.78%   |
| Montriond           | 1        | 2.78%   |
| Montreuil           | 1        | 2.78%   |
| Mnisek pod Brdy     | 1        | 2.78%   |
| Kirkcaldy           | 1        | 2.78%   |
| Kage                | 1        | 2.78%   |
| Harlow              | 1        | 2.78%   |
| Guadalajara         | 1        | 2.78%   |
| Grabs               | 1        | 2.78%   |
| Fuveau              | 1        | 2.78%   |
| Frankfurt (Oder)    | 1        | 2.78%   |
| Enfield             | 1        | 2.78%   |
| Duque de Caxias     | 1        | 2.78%   |
| Dartmouth           | 1        | 2.78%   |
| Choisy-le-Roi       | 1        | 2.78%   |
| Carapicuiba         | 1        | 2.78%   |
| Cape Town           | 1        | 2.78%   |
| Campomarino         | 1        | 2.78%   |
| Calanda             | 1        | 2.78%   |
| Brussels            | 1        | 2.78%   |
| Bordeaux            | 1        | 2.78%   |
| Bandung             | 1        | 2.78%   |
| Amsterdam           | 1        | 2.78%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 12       | 12     | 21.82%  |
| Seagate             | 11       | 13     | 20%     |
| Samsung Electronics | 10       | 21     | 18.18%  |
| Kingston            | 4        | 5      | 7.27%   |
| Hitachi             | 3        | 3      | 5.45%   |
| Toshiba             | 2        | 2      | 3.64%   |
| SanDisk             | 2        | 3      | 3.64%   |
| XPG                 | 1        | 1      | 1.82%   |
| SK hynix            | 1        | 1      | 1.82%   |
| PNY                 | 1        | 1      | 1.82%   |
| Patriot             | 1        | 1      | 1.82%   |
| Intel               | 1        | 1      | 1.82%   |
| HGST                | 1        | 1      | 1.82%   |
| Gigabyte Technology | 1        | 1      | 1.82%   |
| China               | 1        | 1      | 1.82%   |
| ASMedia             | 1        | 1      | 1.82%   |
| A-DATA Technology   | 1        | 1      | 1.82%   |
| Unknown             | 1        | 1      | 1.82%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Seagate ST2000DM008-2FR102 2TB                    | 3        | 4.92%   |
| Seagate ST500LT012-1DG142 500GB                   | 2        | 3.28%   |
| Samsung HD161GJ 160GB                             | 2        | 3.28%   |
| Kingston SA400S37120G 120GB SSD                   | 2        | 3.28%   |
| XPG GAMMIX S11 Pro 512GB                          | 1        | 1.64%   |
| WDC WD800JD-08MSA1 80GB                           | 1        | 1.64%   |
| WDC WD6400AAKS-22A7B2 640GB                       | 1        | 1.64%   |
| WDC WD5000AVVS-63ZWB0 500GB                       | 1        | 1.64%   |
| WDC WD5000AAKS-75V0A0 500GB                       | 1        | 1.64%   |
| WDC WD50 00LPLX-08ZNTT0 500GB                     | 1        | 1.64%   |
| WDC WD3200AAKS-75L9A0 320GB                       | 1        | 1.64%   |
| WDC WD2500AAKX-07U6AA0 250GB                      | 1        | 1.64%   |
| WDC WD2500AAJS-00L7A0 250GB                       | 1        | 1.64%   |
| WDC WD1600BEVT-22ZCT0 160GB                       | 1        | 1.64%   |
| WDC WD1600AAJS-08L7A0 160GB                       | 1        | 1.64%   |
| WDC WD10EZEX-60WN4A0 1TB                          | 1        | 1.64%   |
| WDC WD10EADS-00M2B0 1TB                           | 1        | 1.64%   |
| Toshiba DT01ACA100 1TB                            | 1        | 1.64%   |
| Toshiba DT01ACA050 500GB                          | 1        | 1.64%   |
| SK hynix SKHynix_HFS512GDE9X081N 512GB            | 1        | 1.64%   |
| Seagate ST975042 0AS 752GB                        | 1        | 1.64%   |
| Seagate ST9250315AS 250GB                         | 1        | 1.64%   |
| Seagate ST500DM002-1BD142 500GB                   | 1        | 1.64%   |
| Seagate ST3500413AS 500GB                         | 1        | 1.64%   |
| Seagate ST3500312CS 500GB                         | 1        | 1.64%   |
| Seagate ST3320418AS 320GB                         | 1        | 1.64%   |
| Seagate ST2000VM003-1ET164 2TB                    | 1        | 1.64%   |
| Seagate BarraCuda Q5 ZP500CV30001 500GB           | 1        | 1.64%   |
| Sandisk WD Blue SN570 1TB                         | 1        | 1.64%   |
| SanDisk NVMe SSD Drive 500GB                      | 1        | 1.64%   |
| Samsung SSD 870 EVO 1TB                           | 1        | 1.64%   |
| Samsung SSD 850 EVO 500GB                         | 1        | 1.64%   |
| Samsung SSD 850 EVO 250GB                         | 1        | 1.64%   |
| Samsung SSD 840 PRO Series 512GB                  | 1        | 1.64%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 1        | 1.64%   |
| Samsung MZVPV256HDGL-000H1 256GB                  | 1        | 1.64%   |
| Samsung HN-M320MBB 320GB                          | 1        | 1.64%   |
| Samsung HD753LJ 752GB                             | 1        | 1.64%   |
| Samsung HD322GJ 320GB                             | 1        | 1.64%   |
| Samsung HD154UI 1TB                               | 1        | 1.64%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 12       | 12     | 35.29%  |
| Seagate             | 11       | 12     | 32.35%  |
| Samsung Electronics | 5        | 12     | 14.71%  |
| Hitachi             | 3        | 3      | 8.82%   |
| Toshiba             | 2        | 2      | 5.88%   |
| HGST                | 1        | 1      | 2.94%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 4        | 7      | 25%     |
| Kingston            | 4        | 5      | 25%     |
| PNY                 | 1        | 1      | 6.25%   |
| Patriot             | 1        | 1      | 6.25%   |
| Intel               | 1        | 1      | 6.25%   |
| Gigabyte Technology | 1        | 1      | 6.25%   |
| China               | 1        | 1      | 6.25%   |
| ASMedia             | 1        | 1      | 6.25%   |
| A-DATA Technology   | 1        | 1      | 6.25%   |
| Unknown             | 1        | 1      | 6.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 26       | 42     | 57.78%  |
| SSD  | 14       | 20     | 31.11%  |
| NVMe | 5        | 8      | 11.11%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 34       | 58     | 82.93%  |
| NVMe | 5        | 8      | 12.2%   |
| SAS  | 2        | 4      | 4.88%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 28       | 40     | 66.67%  |
| 0.51-1.0   | 9        | 17     | 21.43%  |
| 1.01-2.0   | 4        | 4      | 9.52%   |
| 10.01-20.0 | 1        | 1      | 2.38%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 251-500    | 11       | 31.43%  |
| 101-250    | 7        | 20%     |
| 501-1000   | 6        | 17.14%  |
| 2001-3000  | 5        | 14.29%  |
| 51-100     | 3        | 8.57%   |
| 21-50      | 1        | 2.86%   |
| 1-20       | 1        | 2.86%   |
| Unknown    | 1        | 2.86%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 14       | 40%     |
| 21-50     | 7        | 20%     |
| 251-500   | 3        | 8.57%   |
| 501-1000  | 3        | 8.57%   |
| 101-250   | 2        | 5.71%   |
| 1001-2000 | 2        | 5.71%   |
| 51-100    | 2        | 5.71%   |
| 2001-3000 | 1        | 2.86%   |
| Unknown   | 1        | 2.86%   |

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
| Works    | 20       | 28     | 51.28%  |
| Detected | 12       | 35     | 30.77%  |
| Malfunc  | 7        | 7      | 17.95%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 23       | 53.49%  |
| AMD                       | 8        | 18.6%   |
| SanDisk                   | 2        | 4.65%   |
| Samsung Electronics       | 2        | 4.65%   |
| Nvidia                    | 2        | 4.65%   |
| VIA Technologies          | 1        | 2.33%   |
| SK hynix                  | 1        | 2.33%   |
| Seagate Technology        | 1        | 2.33%   |
| Marvell Technology Group  | 1        | 2.33%   |
| LSI Logic / Symbios Logic | 1        | 2.33%   |
| ADATA Technology          | 1        | 2.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 6        | 10.71%  |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 4        | 7.14%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                                   | 2        | 3.57%   |
| Nvidia MCP61 SATA Controller                                                            | 2        | 3.57%   |
| Nvidia MCP61 IDE                                                                        | 2        | 3.57%   |
| Intel SATA Controller [RAID mode]                                                       | 2        | 3.57%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2        | 3.57%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 2        | 3.57%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2        | 3.57%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2        | 3.57%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 1        | 1.79%   |
| VIA VT8237A SATA 2-Port Controller                                                      | 1        | 1.79%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 1        | 1.79%   |
| Seagate BarraCuda Q5 NVMe SSD (DRAM-less)                                               | 1        | 1.79%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1        | 1.79%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 1        | 1.79%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                               | 1        | 1.79%   |
| LSI Logic / Symbios Logic SAS1064ET PCI-Express Fusion-MPT SAS                          | 1        | 1.79%   |
| Intel sSATA Controller [RAID Mode]                                                      | 1        | 1.79%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1        | 1.79%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1        | 1.79%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 1        | 1.79%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 1        | 1.79%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1        | 1.79%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1        | 1.79%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1        | 1.79%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1        | 1.79%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                    | 1        | 1.79%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1        | 1.79%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1        | 1.79%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 1.79%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 1.79%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 1        | 1.79%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 1        | 1.79%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1        | 1.79%   |
| AMD X370 Series Chipset SATA Controller                                                 | 1        | 1.79%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 1        | 1.79%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1        | 1.79%   |
| AMD 400 Series Chipset SATA Controller                                                  | 1        | 1.79%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 1        | 1.79%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 22       | 48.89%  |
| IDE  | 13       | 28.89%  |
| NVMe | 5        | 11.11%  |
| RAID | 3        | 6.67%   |
| SAS  | 1        | 2.22%   |
| SCSI | 1        | 2.22%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 24       | 70.59%  |
| AMD    | 10       | 29.41%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel Core i5-2500 CPU @ 3.30GHz             | 2        | 5.88%   |
| Intel Xeon CPU E5-2687W 0 @ 3.10GHz          | 1        | 2.94%   |
| Intel Xeon CPU E5-1650 v4 @ 3.60GHz          | 1        | 2.94%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz       | 1        | 2.94%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz  | 1        | 2.94%   |
| Intel Core i7-4790 CPU @ 3.60GHz             | 1        | 2.94%   |
| Intel Core i7-3770 CPU @ 3.40GHz             | 1        | 2.94%   |
| Intel Core i7-10700 CPU @ 2.90GHz            | 1        | 2.94%   |
| Intel Core i7 CPU 860 @ 2.80GHz              | 1        | 2.94%   |
| Intel Core i5-6500 CPU @ 3.20GHz             | 1        | 2.94%   |
| Intel Core i5-4460 CPU @ 3.20GHz             | 1        | 2.94%   |
| Intel Core i5-3570K CPU @ 3.40GHz            | 1        | 2.94%   |
| Intel Core i5-10400 CPU @ 2.90GHz            | 1        | 2.94%   |
| Intel Core i5 CPU 660 @ 3.33GHz              | 1        | 2.94%   |
| Intel Core i3 CPU 540 @ 3.07GHz              | 1        | 2.94%   |
| Intel Core i3 CPU 530 @ 2.93GHz              | 1        | 2.94%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz        | 1        | 2.94%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz         | 1        | 2.94%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz         | 1        | 2.94%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz         | 1        | 2.94%   |
| Intel Core 2 CPU 6300 @ 1.86GHz              | 1        | 2.94%   |
| Intel Atom CPU N280 @ 1.66GHz                | 1        | 2.94%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz       | 1        | 2.94%   |
| AMD Sempron 145 Processor                    | 1        | 2.94%   |
| AMD Ryzen 9 5900X 12-Core Processor          | 1        | 2.94%   |
| AMD Ryzen 7 1800X Eight-Core Processor       | 1        | 2.94%   |
| AMD Ryzen 3 3100 4-Core Processor            | 1        | 2.94%   |
| AMD PRO A8-8600B R6, 10 Compute Cores 4C+6G  | 1        | 2.94%   |
| AMD Phenom II X6 1045T Processor             | 1        | 2.94%   |
| AMD Athlon II X3 440 Processor               | 1        | 2.94%   |
| AMD Athlon II X2 B22 Processor               | 1        | 2.94%   |
| AMD A6-7480 Radeon R5, 8 Compute Cores 2C+6G | 1        | 2.94%   |
| AMD A6-3600 APU with Radeon HD Graphics      | 1        | 2.94%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 7        | 20.59%  |
| Intel Core i7           | 4        | 11.76%  |
| Intel Core 2 Duo        | 3        | 8.82%   |
| Intel Xeon              | 2        | 5.88%   |
| Intel Core i3           | 2        | 5.88%   |
| AMD A6                  | 2        | 5.88%   |
| Other                   | 1        | 2.94%   |
| Intel Pentium Gold      | 1        | 2.94%   |
| Intel Pentium Dual-Core | 1        | 2.94%   |
| Intel Core 2 Quad       | 1        | 2.94%   |
| Intel Core 2            | 1        | 2.94%   |
| Intel Atom              | 1        | 2.94%   |
| AMD Sempron             | 1        | 2.94%   |
| AMD Ryzen 9             | 1        | 2.94%   |
| AMD Ryzen 7             | 1        | 2.94%   |
| AMD Ryzen 3             | 1        | 2.94%   |
| AMD PRO A8              | 1        | 2.94%   |
| AMD Phenom II X6        | 1        | 2.94%   |
| AMD Athlon II X3        | 1        | 2.94%   |
| AMD Athlon II X2        | 1        | 2.94%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 11       | 32.35%  |
| 2      | 11       | 32.35%  |
| 8      | 4        | 11.76%  |
| 6      | 3        | 8.82%   |
| 1      | 3        | 8.82%   |
| 12     | 1        | 2.94%   |
| 3      | 1        | 2.94%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 34       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 17       | 50%     |
| 1      | 17       | 50%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 33       | 97.06%  |
| 32-bit         | 1        | 2.94%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 6        | 17.65%  |
| 0x20652    | 3        | 8.82%   |
| 0x306c3    | 2        | 5.88%   |
| 0x306a9    | 2        | 5.88%   |
| 0x206a7    | 2        | 5.88%   |
| 0x1067a    | 2        | 5.88%   |
| 0x0600611a | 2        | 5.88%   |
| 0xa0653    | 1        | 2.94%   |
| 0x6fd      | 1        | 2.94%   |
| 0x6fb      | 1        | 2.94%   |
| 0x6f2      | 1        | 2.94%   |
| 0x506e3    | 1        | 2.94%   |
| 0x406f1    | 1        | 2.94%   |
| 0x206d7    | 1        | 2.94%   |
| 0x106e5    | 1        | 2.94%   |
| 0x0a201016 | 1        | 2.94%   |
| 0x08701021 | 1        | 2.94%   |
| 0x08001138 | 1        | 2.94%   |
| 0x03000027 | 1        | 2.94%   |
| 0x010000dc | 1        | 2.94%   |
| 0x010000db | 1        | 2.94%   |
| 0x010000c8 | 1        | 2.94%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| K10         | 4        | 11.76%  |
| Westmere    | 3        | 8.82%   |
| SandyBridge | 3        | 8.82%   |
| Penryn      | 3        | 8.82%   |
| Core        | 3        | 8.82%   |
| IvyBridge   | 2        | 5.88%   |
| Haswell     | 2        | 5.88%   |
| Excavator   | 2        | 5.88%   |
| CometLake   | 2        | 5.88%   |
| Zen 3       | 1        | 2.94%   |
| Zen 2       | 1        | 2.94%   |
| Zen         | 1        | 2.94%   |
| Skylake     | 1        | 2.94%   |
| Nehalem     | 1        | 2.94%   |
| KabyLake    | 1        | 2.94%   |
| K10 Llano   | 1        | 2.94%   |
| Broadwell   | 1        | 2.94%   |
| Bonnell     | 1        | 2.94%   |
| Unknown     | 1        | 2.94%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| AMD              | 13       | 35.14%  |
| Intel            | 12       | 32.43%  |
| Nvidia           | 11       | 29.73%  |
| VIA Technologies | 1        | 2.7%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2        | 5.26%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                            | 2        | 5.26%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 5.26%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 2        | 5.26%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                           | 1        | 2.63%   |
| Nvidia GT218 [GeForce 310]                                                  | 1        | 2.63%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 2.63%   |
| Nvidia GT200GL [Quadro FX 3800]                                             | 1        | 2.63%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 2.63%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 2.63%   |
| Nvidia GM107GL [Quadro K1200]                                               | 1        | 2.63%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 2.63%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 1        | 2.63%   |
| Nvidia GA106 [Geforce RTX 3050]                                             | 1        | 2.63%   |
| Nvidia G96CGL [Quadro FX 580]                                               | 1        | 2.63%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 1        | 2.63%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 2.63%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 1        | 2.63%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1        | 2.63%   |
| Intel HD Graphics 530                                                       | 1        | 2.63%   |
| Intel Core Processor Integrated Graphics Controller                         | 1        | 2.63%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                   | 1        | 2.63%   |
| AMD Turks GL [FirePro V4900]                                                | 1        | 2.63%   |
| AMD Sumo [Radeon HD 6530D]                                                  | 1        | 2.63%   |
| AMD RS880 [Radeon HD 4200]                                                  | 1        | 2.63%   |
| AMD Redwood LE [Radeon HD 5550/5570/5630/6390/6490/7570]                    | 1        | 2.63%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]       | 1        | 2.63%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 1        | 2.63%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 1        | 2.63%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 1        | 2.63%   |
| AMD Cypress XT [Radeon HD 5870]                                             | 1        | 2.63%   |
| AMD Caicos XT [Radeon HD 7470/8470 / R5 235/310 OEM]                        | 1        | 2.63%   |
| AMD Barts PRO [Radeon HD 6850]                                              | 1        | 2.63%   |
| AMD Barts LE [Radeon HD 6790]                                               | 1        | 2.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 12       | 35.29%  |
| 1 x Nvidia     | 10       | 29.41%  |
| 1 x Intel      | 9        | 26.47%  |
| 2 x Intel      | 1        | 2.94%   |
| 1 x VIA        | 1        | 2.94%   |
| Intel + Nvidia | 1        | 2.94%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 27       | 79.41%  |
| Unknown     | 4        | 11.76%  |
| Proprietary | 3        | 8.82%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 18       | 51.43%  |
| 0.51-1.0   | 6        | 17.14%  |
| 0.01-0.5   | 5        | 14.29%  |
| 7.01-8.0   | 2        | 5.71%   |
| 3.01-4.0   | 2        | 5.71%   |
| 1.01-2.0   | 2        | 5.71%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 8        | 27.59%  |
| Goldstar             | 5        | 17.24%  |
| Dell                 | 3        | 10.34%  |
| AOC                  | 3        | 10.34%  |
| BenQ                 | 2        | 6.9%    |
| Acer                 | 2        | 6.9%    |
| Unknown              | 1        | 3.45%   |
| Toshiba              | 1        | 3.45%   |
| Philips              | 1        | 3.45%   |
| JCH                  | 1        | 3.45%   |
| Hewlett-Packard      | 1        | 3.45%   |
| Ancor Communications | 1        | 3.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 1        | 3.13%   |
| Toshiba TV TSB0206 1920x1080                                          | 1        | 3.13%   |
| Samsung Electronics SyncMaster SAM0581 1920x1080 477x268mm 21.5-inch  | 1        | 3.13%   |
| Samsung Electronics SyncMaster SAM0116 1024x768 267x200mm 13.1-inch   | 1        | 3.13%   |
| Samsung Electronics SMB1630N SAM0630 1360x768 344x194mm 15.5-inch     | 1        | 3.13%   |
| Samsung Electronics SA300/SA350 SAM078F 1920x1080 477x268mm 21.5-inch | 1        | 3.13%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch     | 1        | 3.13%   |
| Samsung Electronics S22C450 SAM09C5 1920x1080 477x268mm 21.5-inch     | 1        | 3.13%   |
| Samsung Electronics LS27C36x SAM7315 1920x1080 598x336mm 27.0-inch    | 1        | 3.13%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1        | 3.13%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 1        | 3.13%   |
| JCH F24 JCH1919 1920x1080 520x310mm 23.8-inch                         | 1        | 3.13%   |
| Hewlett-Packard w2207 HWP26A8 1680x1050 473x296mm 22.0-inch           | 1        | 3.13%   |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                   | 1        | 3.13%   |
| Goldstar W2042 GSM4E7E 1680x1050 434x270mm 20.1-inch                  | 1        | 3.13%   |
| Goldstar TV GSM9CF6 1360x768 708x398mm 32.0-inch                      | 1        | 3.13%   |
| Goldstar T710SH GSM436B 1280x960 310x230mm 15.2-inch                  | 1        | 3.13%   |
| Goldstar L1953H GSM4B3D 1280x1024 338x270mm 17.0-inch                 | 1        | 3.13%   |
| Goldstar L1953H GSM4B3C 1280x1024 338x270mm 17.0-inch                 | 1        | 3.13%   |
| Goldstar 23MP55 GSM5A23 1920x1080 510x290mm 23.1-inch                 | 1        | 3.13%   |
| Dell LCD Monitor S2715H 3840x1080                                     | 1        | 3.13%   |
| Dell LCD Monitor S2715H                                               | 1        | 3.13%   |
| Dell IN1930 DELF03B 1366x768 410x230mm 18.5-inch                      | 1        | 3.13%   |
| Dell E176FP DELA014 1280x1024 338x270mm 17.0-inch                     | 1        | 3.13%   |
| BenQ FP202WA BNQ76C2 1680x1050 430x270mm 20.0-inch                    | 1        | 3.13%   |
| BenQ E900HD BNQ7910 1366x768 410x230mm 18.5-inch                      | 1        | 3.13%   |
| AOC LM729 AOCA784 1280x1024 340x270mm 17.1-inch                       | 1        | 3.13%   |
| AOC 2475W1 AOC2475 1920x1080 527x296mm 23.8-inch                      | 1        | 3.13%   |
| AOC 2450W AOC2450 1920x1080 521x293mm 23.5-inch                       | 1        | 3.13%   |
| Ancor Communications ASUS VA325 ACI32FA 1920x1080 698x393mm 31.5-inch | 1        | 3.13%   |
| Acer S271HL ACR02CA 1920x1080 598x336mm 27.0-inch                     | 1        | 3.13%   |
| Acer AL1916W ACRAD80 1440x900 410x257mm 19.1-inch                     | 1        | 3.13%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 14       | 45.16%  |
| 1680x1050 (WSXGA+) | 3        | 9.68%   |
| 1366x768 (WXGA)    | 3        | 9.68%   |
| 1280x1024 (SXGA)   | 3        | 9.68%   |
| 3840x1080          | 1        | 3.23%   |
| 2288x1287          | 1        | 3.23%   |
| 1600x900 (HD+)     | 1        | 3.23%   |
| 1440x900 (WXGA+)   | 1        | 3.23%   |
| 1360x768           | 1        | 3.23%   |
| 1280x960           | 1        | 3.23%   |
| 1024x768 (XGA)     | 1        | 3.23%   |
| Unknown            | 1        | 3.23%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 6        | 20%     |
| 21      | 3        | 10%     |
| 20      | 3        | 10%     |
| 17      | 3        | 10%     |
| 27      | 2        | 6.67%   |
| 18      | 2        | 6.67%   |
| 142     | 1        | 3.33%   |
| 74      | 1        | 3.33%   |
| 72      | 1        | 3.33%   |
| 31      | 1        | 3.33%   |
| 24      | 1        | 3.33%   |
| 22      | 1        | 3.33%   |
| 19      | 1        | 3.33%   |
| 16      | 1        | 3.33%   |
| 15      | 1        | 3.33%   |
| 13      | 1        | 3.33%   |
| Unknown | 1        | 3.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 401-500        | 10       | 33.33%  |
| 501-600        | 9        | 30%     |
| 301-350        | 5        | 16.67%  |
| 1501-2000      | 2        | 6.67%   |
| More than 2000 | 1        | 3.33%   |
| 601-700        | 1        | 3.33%   |
| 201-300        | 1        | 3.33%   |
| Unknown        | 1        | 3.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 18       | 60%     |
| 16/10   | 5        | 16.67%  |
| 5/4     | 3        | 10%     |
| 4/3     | 2        | 6.67%   |
| 1.00    | 1        | 3.33%   |
| Unknown | 1        | 3.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 9        | 30%     |
| 151-200        | 6        | 20%     |
| 141-150        | 5        | 16.67%  |
| More than 1000 | 3        | 10%     |
| 301-350        | 2        | 6.67%   |
| 81-90          | 1        | 3.33%   |
| 351-500        | 1        | 3.33%   |
| 121-130        | 1        | 3.33%   |
| 101-110        | 1        | 3.33%   |
| Unknown        | 1        | 3.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 21       | 72.41%  |
| 101-120 | 4        | 13.79%  |
| 1-50    | 3        | 10.34%  |
| Unknown | 1        | 3.45%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 29       | 85.29%  |
| 2     | 3        | 8.82%   |
| 0     | 2        | 5.88%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 15       | 33.33%  |
| Intel                 | 11       | 24.44%  |
| Ralink Technology     | 3        | 6.67%   |
| Qualcomm Atheros      | 3        | 6.67%   |
| Broadcom              | 3        | 6.67%   |
| TP-Link               | 2        | 4.44%   |
| Nvidia                | 2        | 4.44%   |
| Broadcom Limited      | 2        | 4.44%   |
| VIA Technologies      | 1        | 2.22%   |
| NetGear               | 1        | 2.22%   |
| MediaTek              | 1        | 2.22%   |
| D-Link System         | 1        | 2.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                       | Desktops | Percent |
|---------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller                      | 12       | 24.49%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                       | 2        | 4.08%   |
| Nvidia MCP61 Ethernet                                                                       | 2        | 4.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                       | 2        | 4.08%   |
| VIA VT6102/VT6103 [Rhine-II]                                                                | 1        | 2.04%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                 | 1        | 2.04%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                         | 1        | 2.04%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                          | 1        | 2.04%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                    | 1        | 2.04%   |
| Ralink RT5370 Wireless Adapter                                                              | 1        | 2.04%   |
| Ralink RT3072 Wireless Adapter                                                              | 1        | 2.04%   |
| Ralink MT7601U Wireless Adapter                                                             | 1        | 2.04%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                                   | 1        | 2.04%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                            | 1        | 2.04%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]               | 1        | 2.04%   |
| NetGear WNDA4100 802.11abgn 3x3:3 [Ralink RT3573]                                           | 1        | 2.04%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                               | 1        | 2.04%   |
| Intel Wireless 8260                                                                         | 1        | 2.04%   |
| Intel Wi-Fi 6 AX200                                                                         | 1        | 2.04%   |
| Intel I211 Gigabit Network Connection                                                       | 1        | 2.04%   |
| Intel Ethernet Controller I225-V                                                            | 1        | 2.04%   |
| Intel Ethernet Connection (2) I219-LM                                                       | 1        | 2.04%   |
| Intel Ethernet Connection (2) I218-V                                                        | 1        | 2.04%   |
| Intel Ethernet Connection (2) I218-LM                                                       | 1        | 2.04%   |
| Intel Ethernet Connection (11) I219-LM                                                      | 1        | 2.04%   |
| Intel Comet Lake PCH CNVi WiFi                                                              | 1        | 2.04%   |
| Intel 82578DC Gigabit Network Connection                                                    | 1        | 2.04%   |
| Intel 82566DM Gigabit Network Connection                                                    | 1        | 2.04%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                                        | 1        | 2.04%   |
| D-Link System DWA-160 802.11abgn Xtreme N Dual Band Adapter(rev.A2) [Atheros AR9170+AR9104] | 1        | 2.04%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                                            | 1        | 2.04%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                                     | 1        | 2.04%   |
| Broadcom NetXtreme BCM5721 Gigabit Ethernet PCI Express                                     | 1        | 2.04%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe                                    | 1        | 2.04%   |
| Broadcom Limited NetLink BCM57788 Gigabit Ethernet PCIe                                     | 1        | 2.04%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Ralink Technology     | 3        | 20%     |
| Intel                 | 3        | 20%     |
| TP-Link               | 2        | 13.33%  |
| Realtek Semiconductor | 2        | 13.33%  |
| Qualcomm Atheros      | 2        | 13.33%  |
| NetGear               | 1        | 6.67%   |
| MediaTek              | 1        | 6.67%   |
| D-Link System         | 1        | 6.67%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                       | Desktops | Percent |
|---------------------------------------------------------------------------------------------|----------|---------|
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                 | 1        | 6.67%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                         | 1        | 6.67%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                          | 1        | 6.67%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                    | 1        | 6.67%   |
| Ralink RT5370 Wireless Adapter                                                              | 1        | 6.67%   |
| Ralink RT3072 Wireless Adapter                                                              | 1        | 6.67%   |
| Ralink MT7601U Wireless Adapter                                                             | 1        | 6.67%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                            | 1        | 6.67%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]               | 1        | 6.67%   |
| NetGear WNDA4100 802.11abgn 3x3:3 [Ralink RT3573]                                           | 1        | 6.67%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                               | 1        | 6.67%   |
| Intel Wireless 8260                                                                         | 1        | 6.67%   |
| Intel Wi-Fi 6 AX200                                                                         | 1        | 6.67%   |
| Intel Comet Lake PCH CNVi WiFi                                                              | 1        | 6.67%   |
| D-Link System DWA-160 802.11abgn Xtreme N Dual Band Adapter(rev.A2) [Atheros AR9170+AR9104] | 1        | 6.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 14       | 41.18%  |
| Intel                 | 11       | 32.35%  |
| Broadcom              | 3        | 8.82%   |
| Nvidia                | 2        | 5.88%   |
| Broadcom Limited      | 2        | 5.88%   |
| VIA Technologies      | 1        | 2.94%   |
| Qualcomm Atheros      | 1        | 2.94%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 12       | 35.29%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 2        | 5.88%   |
| Nvidia MCP61 Ethernet                                                  | 2        | 5.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2        | 5.88%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 1        | 2.94%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1        | 2.94%   |
| Intel I211 Gigabit Network Connection                                  | 1        | 2.94%   |
| Intel Ethernet Controller I225-V                                       | 1        | 2.94%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1        | 2.94%   |
| Intel Ethernet Connection (2) I218-V                                   | 1        | 2.94%   |
| Intel Ethernet Connection (2) I218-LM                                  | 1        | 2.94%   |
| Intel Ethernet Connection (11) I219-LM                                 | 1        | 2.94%   |
| Intel 82578DC Gigabit Network Connection                               | 1        | 2.94%   |
| Intel 82566DM Gigabit Network Connection                               | 1        | 2.94%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                   | 1        | 2.94%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                       | 1        | 2.94%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                | 1        | 2.94%   |
| Broadcom NetXtreme BCM5721 Gigabit Ethernet PCI Express                | 1        | 2.94%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe               | 1        | 2.94%   |
| Broadcom Limited NetLink BCM57788 Gigabit Ethernet PCIe                | 1        | 2.94%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 32       | 69.57%  |
| WiFi     | 14       | 30.43%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 26       | 68.42%  |
| WiFi     | 12       | 31.58%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 27       | 79.41%  |
| 2     | 7        | 20.59%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 31       | 91.18%  |
| Yes  | 3        | 8.82%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 3        | 50%     |
| Qualcomm Atheros Communications | 1        | 16.67%  |
| IMC Networks                    | 1        | 16.67%  |
| Cambridge Silicon Radio         | 1        | 16.67%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Qualcomm Atheros Bluetooth                          | 1        | 16.67%  |
| Intel Bluetooth Device                              | 1        | 16.67%  |
| Intel AX201 Bluetooth                               | 1        | 16.67%  |
| Intel AX200 Bluetooth                               | 1        | 16.67%  |
| IMC Networks Bluetooth Radio                        | 1        | 16.67%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1        | 16.67%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 22       | 43.14%  |
| AMD                 | 15       | 29.41%  |
| Nvidia              | 10       | 19.61%  |
| VIA Technologies    | 1        | 1.96%   |
| Plantronics         | 1        | 1.96%   |
| Creative Labs       | 1        | 1.96%   |
| C-Media Electronics | 1        | 1.96%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 4        | 6.9%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 3        | 5.17%   |
| Nvidia MCP61 High Definition Audio                                                | 2        | 3.45%   |
| Nvidia High Definition Audio Controller                                           | 2        | 3.45%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 2        | 3.45%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 2        | 3.45%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 2        | 3.45%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 2        | 3.45%   |
| AMD Starship/Matisse HD Audio Controller                                          | 2        | 3.45%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 2        | 3.45%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 2        | 3.45%   |
| AMD Kabini HDMI/DP Audio                                                          | 2        | 3.45%   |
| AMD FCH Azalia Controller                                                         | 2        | 3.45%   |
| AMD Barts HDMI Audio [Radeon HD 6790/6850/6870 / 7720 OEM]                        | 2        | 3.45%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                    | 1        | 1.72%   |
| Plantronics USB DSP v4 Audio Interface                                            | 1        | 1.72%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 1        | 1.72%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 1        | 1.72%   |
| Nvidia GK104 HDMI Audio Controller                                                | 1        | 1.72%   |
| Nvidia GA106 High Definition Audio Controller                                     | 1        | 1.72%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 1        | 1.72%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 1        | 1.72%   |
| Intel Comet Lake PCH-V cAVS                                                       | 1        | 1.72%   |
| Intel Comet Lake PCH cAVS                                                         | 1        | 1.72%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 1        | 1.72%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 1        | 1.72%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 1        | 1.72%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 1        | 1.72%   |
| Intel 200 Series PCH HD Audio                                                     | 1        | 1.72%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 1        | 1.72%   |
| Creative Labs CA0106/CA0111 [SB Live!/Audigy/X-Fi Series]                         | 1        | 1.72%   |
| C-Media Electronics USB Audio Device                                              | 1        | 1.72%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 1        | 1.72%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                    | 1        | 1.72%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 1        | 1.72%   |
| AMD Navi 10 HDMI Audio                                                            | 1        | 1.72%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 1        | 1.72%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                  | 1        | 1.72%   |
| AMD Cypress HDMI Audio [Radeon HD 5830/5850/5870 / 6850/6870 Rebrand]             | 1        | 1.72%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 1        | 1.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 7        | 25.93%  |
| Samsung Electronics | 5        | 18.52%  |
| Kingston            | 4        | 14.81%  |
| G.Skill             | 2        | 7.41%   |
| Corsair             | 2        | 7.41%   |
| Unifosa             | 1        | 3.7%    |
| Toshiba             | 1        | 3.7%    |
| SK hynix            | 1        | 3.7%    |
| Ramaxel Technology  | 1        | 3.7%    |
| Micron Technology   | 1        | 3.7%    |
| Crucial             | 1        | 3.7%    |
| Avant               | 1        | 3.7%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM 800MT/s                | 2        | 6.9%    |
| Unknown RAM Module 4GB DIMM 1333MT/s                  | 1        | 3.45%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s             | 1        | 3.45%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s              | 1        | 3.45%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s           | 1        | 3.45%   |
| Unknown RAM Module 1024MB DIMM SDRAM                  | 1        | 3.45%   |
| Unifosa RAM GU512303EP0202 2GB DIMM DDR3 1333MT/s     | 1        | 3.45%   |
| Toshiba RAM 9905474-012.A00LF 2GB DIMM DDR3 1333MT/s  | 1        | 3.45%   |
| SK hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s  | 1        | 3.45%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s | 1        | 3.45%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s | 1        | 3.45%   |
| Samsung RAM M393A2K40BB1-CRC 16GB DIMM DDR4 2400MT/s  | 1        | 3.45%   |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR3 1867MT/s   | 1        | 3.45%   |
| Samsung RAM M3 78T5663EH3-CF7 2GB DIMM DDR2 800MT/s   | 1        | 3.45%   |
| Samsung RAM M3 78T2863RZS-CE6 1GB DIMM DDR2 667MT/s   | 1        | 3.45%   |
| Samsung RAM M3 78T2863QZS-CE6 1GB DIMM DDR2 1639MT/s  | 1        | 3.45%   |
| Ramaxel RAM RMR5030MM58E8F1600 2GB DIMM DDR3 1600MT/s | 1        | 3.45%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s   | 1        | 3.45%   |
| Kingston RAM Module 8GB DIMM DDR3 1600MT/s            | 1        | 3.45%   |
| Kingston RAM Module 16GB SODIMM DDR4 2133MT/s         | 1        | 3.45%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s   | 1        | 3.45%   |
| Kingston RAM 99U5471-030.A00LF 8GB DIMM DDR3 1333MT/s | 1        | 3.45%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s    | 1        | 3.45%   |
| G.Skill RAM F2-6400CL4-1GBPK 1GB DIMM DDR2 800MT/s    | 1        | 3.45%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1800MT/s | 1        | 3.45%   |
| Corsair RAM CMZ4GX3M1A1600C9 4GB DIMM DDR3 1600MT/s   | 1        | 3.45%   |
| Corsair RAM CMK16GX4M2D3600C18 8GB DIMM DDR4 3600MT/s | 1        | 3.45%   |
| Avant RAM W641GU49J2320N6 8GB DIMM DDR4 2666MT/s      | 1        | 3.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 10       | 41.67%  |
| DDR4    | 4        | 16.67%  |
| DDR2    | 3        | 12.5%   |
| Unknown | 3        | 12.5%   |
| SDRAM   | 2        | 8.33%   |
| DRAM    | 1        | 4.17%   |
| DDR     | 1        | 4.17%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 20       | 86.96%  |
| SODIMM | 3        | 13.04%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 2048  | 9        | 33.33%  |
| 8192  | 8        | 29.63%  |
| 4096  | 5        | 18.52%  |
| 1024  | 3        | 11.11%  |
| 16384 | 2        | 7.41%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1333    | 6        | 22.22%  |
| 1600    | 5        | 18.52%  |
| 800     | 4        | 14.81%  |
| 2400    | 2        | 7.41%   |
| 3666    | 1        | 3.7%    |
| 3200    | 1        | 3.7%    |
| 2666    | 1        | 3.7%    |
| 2133    | 1        | 3.7%    |
| 2048    | 1        | 3.7%    |
| 1867    | 1        | 3.7%    |
| 1800    | 1        | 3.7%    |
| 1639    | 1        | 3.7%    |
| 667     | 1        | 3.7%    |
| Unknown | 1        | 3.7%    |

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
| 0     | 26       | 76.47%  |
| 1     | 7        | 20.59%  |
| 2     | 1        | 2.94%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type             | Desktops | Percent |
|------------------|----------|---------|
| Graphics card    | 5        | 55.56%  |
| Net/wireless     | 2        | 22.22%  |
| Unassigned class | 1        | 11.11%  |
| Camera           | 1        | 11.11%  |

