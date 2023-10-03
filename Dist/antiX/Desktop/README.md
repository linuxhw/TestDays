antiX - Tested Hardware & Statistics (Desktops)
-----------------------------------------------

A project to collect tested hardware configurations for antiX.

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

Total: 27

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| Pegatron | Eureka3                     | [e5c7ff0c70](https://linux-hardware.org/?probe=e5c7ff0c70) | Sep 30, 2023 |
| ASRock   | G31M-S                      | [f1325a7f15](https://linux-hardware.org/?probe=f1325a7f15) | Sep 23, 2023 |
| Intel    | DG41TY AAE47335-202         | [cd00ffcda2](https://linux-hardware.org/?probe=cd00ffcda2) | Sep 09, 2023 |
| Intel    | DG41TY AAE47335-202         | [4cdbce3b75](https://linux-hardware.org/?probe=4cdbce3b75) | Sep 09, 2023 |
| MSI      | MPG Z390 GAMING PRO CARB... | [4551c437bf](https://linux-hardware.org/?probe=4551c437bf) | May 18, 2023 |
| Intel    | H61                         | [aa4606c36c](https://linux-hardware.org/?probe=aa4606c36c) | May 02, 2023 |
| Pegatron | NARRA5                      | [4c8bb5eff0](https://linux-hardware.org/?probe=4c8bb5eff0) | Apr 30, 2023 |
| MSI      | B550-A PRO                  | [d8b51c995c](https://linux-hardware.org/?probe=d8b51c995c) | Apr 23, 2023 |
| Gigabyte | Z790 AERO G                 | [f33074a4c8](https://linux-hardware.org/?probe=f33074a4c8) | Apr 03, 2023 |
| Gigabyte | Z790 AERO G                 | [2f380f0d1a](https://linux-hardware.org/?probe=2f380f0d1a) | Apr 03, 2023 |
| VXL      | M6V90AI-VL                  | [935d6b4b24](https://linux-hardware.org/?probe=935d6b4b24) | Feb 21, 2023 |
| Intel    | D525MW AAE93082-401         | [a225baa8a4](https://linux-hardware.org/?probe=a225baa8a4) | Aug 05, 2022 |
| Biostar  | G31-M7 TE                   | [df98c1834c](https://linux-hardware.org/?probe=df98c1834c) | Jul 23, 2022 |
| Dell     | 0F428D A00                  | [fb8a6009f7](https://linux-hardware.org/?probe=fb8a6009f7) | Jul 16, 2022 |
| MSI      | B560M PRO-VDH WIFI [CEC]    | [af73739875](https://linux-hardware.org/?probe=af73739875) | Jul 14, 2022 |
| Unknown  | K8NF3-VSTA                  | [f2ea6e0d83](https://linux-hardware.org/?probe=f2ea6e0d83) | Jun 24, 2022 |
| MSI      | B560M PRO-VDH WIFI [CEC]    | [8654086b85](https://linux-hardware.org/?probe=8654086b85) | Jun 20, 2022 |
| Gigabyte | F2A85XM-D3H                 | [cf20f6e233](https://linux-hardware.org/?probe=cf20f6e233) | Mar 09, 2022 |
| Gigabyte | 945GCMX-S2                  | [54149177a7](https://linux-hardware.org/?probe=54149177a7) | Feb 12, 2022 |
| Unknown  | NF-CK804                    | [dc6287d017](https://linux-hardware.org/?probe=dc6287d017) | Jan 05, 2022 |
| ASUSTek  | A8R-MVP                     | [43a7b44e3f](https://linux-hardware.org/?probe=43a7b44e3f) | Mar 27, 2021 |
| ASUSTek  | M2N-MX SE Plus              | [a8985150bd](https://linux-hardware.org/?probe=a8985150bd) | Feb 08, 2021 |
| ASRock   | H81M-ITX                    | [7b2d6774c8](https://linux-hardware.org/?probe=7b2d6774c8) | Feb 05, 2021 |
| HP       | 3641h                       | [f918637d53](https://linux-hardware.org/?probe=f918637d53) | Jul 29, 2020 |
| Unknown  | Unknown                     | [7653370d96](https://linux-hardware.org/?probe=7653370d96) | Dec 16, 2019 |
| ASUSTek  | P5KPL/1600                  | [8ba4b22f71](https://linux-hardware.org/?probe=8ba4b22f71) | Oct 22, 2019 |
| Lenovo   | ThinkCentre M91p 4480B9U    | [e68917ee9f](https://linux-hardware.org/?probe=e68917ee9f) | Nov 04, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| antiX 21       | 9        | 39.13%  |
| antiX 22       | 5        | 21.74%  |
| antiX 19.2     | 2        | 8.7%    |
| antiX 17.4.1   | 2        | 8.7%    |
| antiX 23       | 1        | 4.35%   |
| antiX 21-runit | 1        | 4.35%   |
| antiX 19.3     | 1        | 4.35%   |
| antiX 17.1     | 1        | 4.35%   |
| antiX 15       | 1        | 4.35%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| antiX | 23       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Desktops | Percent |
|-----------------------------|----------|---------|
| 5.10.57-antix.1-amd64-smp   | 4        | 17.39%  |
| 5.10.142-antix.2-amd64-smp  | 4        | 17.39%  |
| 4.9.0-279-antix.1-amd64-smp | 3        | 13.04%  |
| 4.9.160-antix.2-486-smp     | 2        | 8.7%    |
| 6.2.9-1-liquorix-amd64      | 1        | 4.35%   |
| 6.1.0-0.deb11.9-rt-amd64    | 1        | 4.35%   |
| 5.10.88-antix.1-amd64-smp   | 1        | 4.35%   |
| 5.10.188-antix.1-amd64-smp  | 1        | 4.35%   |
| 4.9.87-antix.1-amd64-smp    | 1        | 4.35%   |
| 4.9.235-antix.1-amd64-smp   | 1        | 4.35%   |
| 4.9.212-antix.1-amd64-smp   | 1        | 4.35%   |
| 4.9.212-antix.1-486-smp     | 1        | 4.35%   |
| 4.9.0-326-antix.1-amd64-smp | 1        | 4.35%   |
| 4.9.0-279-antix.1-486-smp   | 1        | 4.35%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 4.9.0    | 5        | 21.74%  |
| 5.10.57  | 4        | 17.39%  |
| 5.10.142 | 4        | 17.39%  |
| 4.9.212  | 2        | 8.7%    |
| 4.9.160  | 2        | 8.7%    |
| 6.2.9    | 1        | 4.35%   |
| 6.1.0    | 1        | 4.35%   |
| 5.10.88  | 1        | 4.35%   |
| 5.10.188 | 1        | 4.35%   |
| 4.9.87   | 1        | 4.35%   |
| 4.9.235  | 1        | 4.35%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.9     | 11       | 47.83%  |
| 5.10    | 10       | 43.48%  |
| 6.2     | 1        | 4.35%   |
| 6.1     | 1        | 4.35%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 19       | 82.61%  |
| i686   | 4        | 17.39%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| icewm        | 11       | 47.83%  |
| Unknown      | 8        | 34.78%  |
| XFCE         | 2        | 8.7%    |
| jwm          | 1        | 4.35%   |
| herbstluftwm | 1        | 4.35%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 21       | 91.3%   |
| Tty  | 2        | 8.7%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 10       | 43.48%  |
| SLiM    | 6        | 26.09%  |
| SLIMSKI | 5        | 21.74%  |
| LightDM | 2        | 8.7%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 7        | 30.43%  |
| Unknown | 3        | 13.04%  |
| pt_BR   | 2        | 8.7%    |
| pl_PL   | 2        | 8.7%    |
| en_GB   | 2        | 8.7%    |
| tr_TR   | 1        | 4.35%   |
| sk_SK   | 1        | 4.35%   |
| ru_RU   | 1        | 4.35%   |
| it_IT   | 1        | 4.35%   |
| fr_FR   | 1        | 4.35%   |
| es_PE   | 1        | 4.35%   |
| es_AR   | 1        | 4.35%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 17       | 73.91%  |
| EFI  | 6        | 26.09%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 20       | 86.96%  |
| Overlay | 2        | 8.7%    |
| Xfs     | 1        | 4.35%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| MBR     | 15       | 65.22%  |
| GPT     | 7        | 30.43%  |
| Unknown | 1        | 4.35%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 16       | 69.57%  |
| Yes       | 7        | 30.43%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 16       | 69.57%  |
| Yes       | 7        | 30.43%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| MSI                 | 4        | 17.39%  |
| Intel               | 3        | 13.04%  |
| Gigabyte Technology | 3        | 13.04%  |
| Unknown             | 3        | 13.04%  |
| Pegatron            | 2        | 8.7%    |
| ASUSTek Computer    | 2        | 8.7%    |
| VXL                 | 1        | 4.35%   |
| Lenovo              | 1        | 4.35%   |
| Hewlett-Packard     | 1        | 4.35%   |
| Dell                | 1        | 4.35%   |
| Biostar             | 1        | 4.35%   |
| ASRock              | 1        | 4.35%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| Unknown                         | 3        | 13.04%  |
| MSI US Desktop                  | 2        | 8.7%    |
| VXL TC7520d                     | 1        | 4.35%   |
| Pegatron VC902AA-ABF p6136fr    | 1        | 4.35%   |
| Pegatron AU930AA-ACJ p6270in    | 1        | 4.35%   |
| MSI MS-7C56                     | 1        | 4.35%   |
| MSI MS-7B17                     | 1        | 4.35%   |
| Lenovo ThinkCentre M91p 4480B9U | 1        | 4.35%   |
| Intel H61                       | 1        | 4.35%   |
| Intel DG41TY AAE47335-202       | 1        | 4.35%   |
| Intel D525MW AAE93082-401       | 1        | 4.35%   |
| HP t5740                        | 1        | 4.35%   |
| Gigabyte Z790 AERO G            | 1        | 4.35%   |
| Gigabyte F2A85XM-D3H            | 1        | 4.35%   |
| Gigabyte 945GCMX-S2             | 1        | 4.35%   |
| Dell OptiPlex 960               | 1        | 4.35%   |
| Biostar G31-M7 TE               | 1        | 4.35%   |
| ASUS P5KPL/1600                 | 1        | 4.35%   |
| ASUS A8R-MVP                    | 1        | 4.35%   |
| ASRock G31M-S                   | 1        | 4.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| Unknown              | 3        | 13.04%  |
| MSI US               | 2        | 8.7%    |
| VXL TC7520d          | 1        | 4.35%   |
| Pegatron VC902AA-ABF | 1        | 4.35%   |
| Pegatron AU930AA-ACJ | 1        | 4.35%   |
| MSI MS-7C56          | 1        | 4.35%   |
| MSI MS-7B17          | 1        | 4.35%   |
| Lenovo ThinkCentre   | 1        | 4.35%   |
| Intel H61            | 1        | 4.35%   |
| Intel DG41TY         | 1        | 4.35%   |
| Intel D525MW         | 1        | 4.35%   |
| HP t5740             | 1        | 4.35%   |
| Gigabyte Z790        | 1        | 4.35%   |
| Gigabyte F2A85XM-D3H | 1        | 4.35%   |
| Gigabyte 945GCMX-S2  | 1        | 4.35%   |
| Dell OptiPlex        | 1        | 4.35%   |
| Biostar G31-M7       | 1        | 4.35%   |
| ASUS P5KPL           | 1        | 4.35%   |
| ASUS A8R-MVP         | 1        | 4.35%   |
| ASRock G31M-S        | 1        | 4.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2008    | 5        | 21.74%  |
| 2009    | 4        | 17.39%  |
| 2021    | 2        | 8.7%    |
| 2011    | 2        | 8.7%    |
| 2007    | 2        | 8.7%    |
| 2022    | 1        | 4.35%   |
| 2020    | 1        | 4.35%   |
| 2018    | 1        | 4.35%   |
| 2017    | 1        | 4.35%   |
| 2014    | 1        | 4.35%   |
| 2012    | 1        | 4.35%   |
| 2005    | 1        | 4.35%   |
| Unknown | 1        | 4.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 23       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 23       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 23       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 7        | 30.43%  |
| 32.01-64.0  | 3        | 13.04%  |
| 3.01-4.0    | 3        | 13.04%  |
| 4.01-8.0    | 2        | 8.7%    |
| 2.01-3.0    | 2        | 8.7%    |
| 64.01-256.0 | 2        | 8.7%    |
| 16.01-24.0  | 1        | 4.35%   |
| 8.01-16.0   | 1        | 4.35%   |
| 0.51-1.0    | 1        | 4.35%   |
| 0.01-0.5    | 1        | 4.35%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 0.51-1.0   | 8        | 34.78%  |
| 0.01-0.5   | 6        | 26.09%  |
| 1.01-2.0   | 5        | 21.74%  |
| 4.01-8.0   | 2        | 8.7%    |
| 32.01-64.0 | 1        | 4.35%   |
| 2.01-3.0   | 1        | 4.35%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 13       | 56.52%  |
| 4      | 3        | 13.04%  |
| 3      | 3        | 13.04%  |
| 2      | 2        | 8.7%    |
| 5      | 1        | 4.35%   |
| 0      | 1        | 4.35%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 15       | 65.22%  |
| Yes       | 8        | 34.78%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 22       | 95.65%  |
| No        | 1        | 4.35%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 15       | 65.22%  |
| Yes       | 8        | 34.78%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 17       | 73.91%  |
| Yes       | 6        | 26.09%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| USA       | 5        | 21.74%  |
| UK        | 2        | 8.7%    |
| Russia    | 2        | 8.7%    |
| Poland    | 2        | 8.7%    |
| France    | 2        | 8.7%    |
| Brazil    | 2        | 8.7%    |
| Slovakia  | 1        | 4.35%   |
| Peru      | 1        | 4.35%   |
| Japan     | 1        | 4.35%   |
| Italy     | 1        | 4.35%   |
| India     | 1        | 4.35%   |
| Greece    | 1        | 4.35%   |
| Germany   | 1        | 4.35%   |
| Argentina | 1        | 4.35%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Zagnansk          | 1        | 4.35%   |
| Violes            | 1        | 4.35%   |
| Tokyo             | 1        | 4.35%   |
| Romilly-sur-Seine | 1        | 4.35%   |
| Padova            | 1        | 4.35%   |
| Otwock            | 1        | 4.35%   |
| Nova Londrina     | 1        | 4.35%   |
| Miami             | 1        | 4.35%   |
| Mason             | 1        | 4.35%   |
| Maringá          | 1        | 4.35%   |
| Maidstone         | 1        | 4.35%   |
| Lima              | 1        | 4.35%   |
| Kazan’          | 1        | 4.35%   |
| Houston           | 1        | 4.35%   |
| Heraklion         | 1        | 4.35%   |
| Greenwich         | 1        | 4.35%   |
| Frankfurt am Main | 1        | 4.35%   |
| Covington         | 1        | 4.35%   |
| Buenos Aires      | 1        | 4.35%   |
| Bryansk           | 1        | 4.35%   |
| Bratislava        | 1        | 4.35%   |
| Boulder           | 1        | 4.35%   |
| Bengaluru         | 1        | 4.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 8        | 10     | 22.22%  |
| Samsung Electronics       | 6        | 8      | 16.67%  |
| Seagate                   | 5        | 5      | 13.89%  |
| Toshiba                   | 4        | 5      | 11.11%  |
| Micron/Crucial Technology | 2        | 2      | 5.56%   |
| Kingston                  | 2        | 3      | 5.56%   |
| BHT                       | 2        | 2      | 5.56%   |
| Unknown                   | 1        | 1      | 2.78%   |
| SanDisk                   | 1        | 1      | 2.78%   |
| Maxtor                    | 1        | 1      | 2.78%   |
| Intel                     | 1        | 1      | 2.78%   |
| Hitachi                   | 1        | 2      | 2.78%   |
| Crucial                   | 1        | 1      | 2.78%   |
| Apacer                    | 1        | 1      | 2.78%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| WDC WD800AAJS-75M0A0 80GB                          | 2        | 5.13%   |
| WDC WD10SPZX-80Z10T2 1TB                           | 2        | 5.13%   |
| Toshiba MQ01ABD050V -63 500GB                      | 2        | 5.13%   |
| Kingston SA400S37240G 240GB SSD                    | 2        | 5.13%   |
| BHT WR202F0032G 670270F5 32GB SSD                  | 2        | 5.13%   |
| WDC WD800JB-00ETA0 80GB                            | 1        | 2.56%   |
| WDC WD5000AAKX-60U6AA0 500GB                       | 1        | 2.56%   |
| WDC WD205BA 21GB                                   | 1        | 2.56%   |
| WDC WD2003FZEX-00Z4SA0 2TB                         | 1        | 2.56%   |
| WDC WD1600AAJS-00PSA0 160GB                        | 1        | 2.56%   |
| WDC WD10EADS-65M2B0 1TB                            | 1        | 2.56%   |
| Unknown 2GB ATA Flash Disk                         | 1        | 2.56%   |
| Toshiba MQ01ABD100 1TB                             | 1        | 2.56%   |
| Toshiba MG06ACA600E 6TB                            | 1        | 2.56%   |
| Seagate ST500DM002-1BD142 500GB                    | 1        | 2.56%   |
| Seagate ST3500312CS 500GB                          | 1        | 2.56%   |
| Seagate ST3320620AS 320GB                          | 1        | 2.56%   |
| Seagate ST3320413CS 320GB                          | 1        | 2.56%   |
| Seagate ST1000DM010-2EP102 1TB                     | 1        | 2.56%   |
| SanDisk sandisk120 120GB SSD                       | 1        | 2.56%   |
| Samsung SSD 860 EVO 500GB                          | 1        | 2.56%   |
| Samsung SSD 850 EVO 120GB                          | 1        | 2.56%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 1        | 2.56%   |
| Samsung HD250HJ 250GB                              | 1        | 2.56%   |
| Samsung HD162GJ 160GB                              | 1        | 2.56%   |
| Samsung HD160JJ/ 160GB                             | 1        | 2.56%   |
| Samsung HD080HJ 80GB                               | 1        | 2.56%   |
| Micron/Crucial P1 NVMe PCIe SSD 1TB                | 1        | 2.56%   |
| Micron/Crucial CT2000P5PSSD8 2TB                   | 1        | 2.56%   |
| Maxtor Z1 SSD 240GB                                | 1        | 2.56%   |
| Intel SSDPEKNW010T8 1TB                            | 1        | 2.56%   |
| Hitachi HTS723232A7A364 320GB                      | 1        | 2.56%   |
| Crucial CT500MX500SSD1 500GB                       | 1        | 2.56%   |
| Apacer 32GB SATA Flash Drive SSD                   | 1        | 2.56%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 8        | 10     | 36.36%  |
| Seagate             | 5        | 5      | 22.73%  |
| Toshiba             | 4        | 5      | 18.18%  |
| Samsung Electronics | 3        | 4      | 13.64%  |
| Unknown             | 1        | 1      | 4.55%   |
| Hitachi             | 1        | 2      | 4.55%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 2        | 2      | 20%     |
| Kingston            | 2        | 3      | 20%     |
| BHT                 | 2        | 2      | 20%     |
| SanDisk             | 1        | 1      | 10%     |
| Maxtor              | 1        | 1      | 10%     |
| Crucial             | 1        | 1      | 10%     |
| Apacer              | 1        | 1      | 10%     |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 17       | 27     | 56.67%  |
| SSD  | 10       | 11     | 33.33%  |
| NVMe | 3        | 5      | 10%     |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 22       | 38     | 88%     |
| NVMe | 3        | 5      | 12%     |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 20       | 30     | 74.07%  |
| 0.51-1.0   | 5        | 5      | 18.52%  |
| 1.01-2.0   | 1        | 1      | 3.7%    |
| 4.01-10.0  | 1        | 2      | 3.7%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 6        | 26.09%  |
| 251-500        | 4        | 17.39%  |
| 21-50          | 4        | 17.39%  |
| 501-1000       | 3        | 13.04%  |
| 1-20           | 2        | 8.7%    |
| 51-100         | 2        | 8.7%    |
| More than 3000 | 1        | 4.35%   |
| 1001-2000      | 1        | 4.35%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 16       | 69.57%  |
| 101-250        | 3        | 13.04%  |
| More than 3000 | 1        | 4.35%   |
| 21-50          | 1        | 4.35%   |
| 501-1000       | 1        | 4.35%   |
| 51-100         | 1        | 4.35%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                       | Desktops | Drives | Percent |
|---------------------------------------------|----------|--------|---------|
| WDC WD800AAJS-75M0A0 80GB                   | 2        | 2      | 14.29%  |
| WDC WD800JB-00ETA0 80GB                     | 1        | 1      | 7.14%   |
| WDC WD5000AAKX-60U6AA0 500GB                | 1        | 1      | 7.14%   |
| WDC WD205BA 21GB                            | 1        | 1      | 7.14%   |
| WDC WD10EADS-65M2B0 1TB                     | 1        | 1      | 7.14%   |
| Toshiba MQ01ABD100 1TB                      | 1        | 1      | 7.14%   |
| Seagate ST500DM002-1BD142 500GB             | 1        | 1      | 7.14%   |
| Seagate ST3500312CS 500GB                   | 1        | 1      | 7.14%   |
| Seagate ST3320620AS 320GB                   | 1        | 1      | 7.14%   |
| Seagate ST3320413CS 320GB                   | 1        | 1      | 7.14%   |
| SanDisk sandisk120 120GB SSD                | 1        | 1      | 7.14%   |
| Micron/Crucial Technology CT2000P5PSSD8 2TB | 1        | 1      | 7.14%   |
| Apacer 32GB SATA Flash Drive SSD            | 1        | 1      | 7.14%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 6        | 6      | 42.86%  |
| Seagate                   | 4        | 4      | 28.57%  |
| Toshiba                   | 1        | 1      | 7.14%   |
| SanDisk                   | 1        | 1      | 7.14%   |
| Micron/Crucial Technology | 1        | 1      | 7.14%   |
| Apacer                    | 1        | 1      | 7.14%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 6        | 6      | 54.55%  |
| Seagate | 4        | 4      | 36.36%  |
| Toshiba | 1        | 1      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 11       | 11     | 78.57%  |
| SSD  | 2        | 2      | 14.29%  |
| NVMe | 1        | 1      | 7.14%   |

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
| Malfunc  | 14       | 14     | 50%     |
| Works    | 11       | 25     | 39.29%  |
| Detected | 3        | 4      | 10.71%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 16       | 51.61%  |
| ASMedia Technology        | 4        | 12.9%   |
| Nvidia                    | 3        | 9.68%   |
| Micron/Crucial Technology | 2        | 6.45%   |
| AMD                       | 2        | 6.45%   |
| VIA Technologies          | 1        | 3.23%   |
| ULi Electronics           | 1        | 3.23%   |
| Samsung Electronics       | 1        | 3.23%   |
| LSI Logic / Symbios Logic | 1        | 3.23%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                             | 5        | 11.9%   |
| Intel 82801G (ICH7 Family) IDE Controller                                     | 5        | 11.9%   |
| ASMedia ASM1062 Serial ATA Controller                                         | 3        | 7.14%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller | 2        | 4.76%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                          | 2        | 4.76%   |
| AMD FCH SATA Controller [AHCI mode]                                           | 2        | 4.76%   |
| VIA VX900 Series Serial-ATA Controller                                        | 1        | 2.38%   |
| ULi ULi M5288 SATA                                                            | 1        | 2.38%   |
| ULi M5229 IDE                                                                 | 1        | 2.38%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 1        | 2.38%   |
| Nvidia nForce3 Serial ATA Controller                                          | 1        | 2.38%   |
| Nvidia MCP61 SATA Controller                                                  | 1        | 2.38%   |
| Nvidia CK8S Parallel ATA Controller (v2.5)                                    | 1        | 2.38%   |
| Nvidia CK804 Serial ATA Controller                                            | 1        | 2.38%   |
| Nvidia CK804 IDE                                                              | 1        | 2.38%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                          | 1        | 2.38%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton]                                     | 1        | 2.38%   |
| LSI Logic / Symbios Logic SAS3008 PCI-Express Fusion-MPT SAS-3                | 1        | 2.38%   |
| Intel SSD 660P Series                                                         | 1        | 2.38%   |
| Intel SATA Controller [RAID mode]                                             | 1        | 2.38%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                            | 1        | 2.38%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                    | 1        | 2.38%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                    | 1        | 2.38%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]          | 1        | 2.38%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                 | 1        | 2.38%   |
| Intel 700 Series Chipset Family SATA AHCI Controller                          | 1        | 2.38%   |
| Intel 4 Series Chipset PT IDER Controller                                     | 1        | 2.38%   |
| ASMedia ASM1061 SATA IDE Controller                                           | 1        | 2.38%   |
| AMD 500 Series Chipset SATA Controller                                        | 1        | 2.38%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| IDE  | 14       | 48.28%  |
| SATA | 10       | 34.48%  |
| NVMe | 3        | 10.34%  |
| RAID | 1        | 3.45%   |
| SAS  | 1        | 3.45%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 16       | 69.57%  |
| AMD          | 6        | 26.09%  |
| CentaurHauls | 1        | 4.35%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 2        | 8.7%    |
| Intel 11th Gen Core i5-11400F @ 2.60GHz     | 2        | 8.7%    |
| Intel Xeon CPU L5410 @ 2.33GHz              | 1        | 4.35%   |
| Intel Pentium II (Deschutes)                | 1        | 4.35%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 1        | 4.35%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 1        | 4.35%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1        | 4.35%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 1        | 4.35%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 1        | 4.35%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 1        | 4.35%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 1        | 4.35%   |
| Intel Atom CPU N280 @ 1.66GHz               | 1        | 4.35%   |
| Intel Atom CPU D525 @ 1.80GHz               | 1        | 4.35%   |
| Intel 13th Gen Core i9-13900K               | 1        | 4.35%   |
| CentaurHauls VIA Eden X2 U4200 @ 1.0+ GHz   | 1        | 4.35%   |
| AMD Sempron Processor 3000+                 | 1        | 4.35%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 1        | 4.35%   |
| AMD Phenom 9650 Quad-Core Processor         | 1        | 4.35%   |
| AMD Athlon 64 X2 Dual Core Processor 4600+  | 1        | 4.35%   |
| AMD Athlon 64 Processor 3200+               | 1        | 4.35%   |
| AMD A6-5400K APU with Radeon HD Graphics    | 1        | 4.35%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Other                   | 3        | 13.04%  |
| Intel Pentium Dual-Core | 2        | 8.7%    |
| Intel Core 2 Duo        | 2        | 8.7%    |
| Intel Atom              | 2        | 8.7%    |
| Intel Xeon              | 1        | 4.35%   |
| Intel Pentium Dual      | 1        | 4.35%   |
| Intel Pentium           | 1        | 4.35%   |
| Intel Core i9           | 1        | 4.35%   |
| Intel Core i7           | 1        | 4.35%   |
| Intel Core i5           | 1        | 4.35%   |
| Intel Core 2 Quad       | 1        | 4.35%   |
| CentaurHauls VIA Eden   | 1        | 4.35%   |
| AMD Sempron             | 1        | 4.35%   |
| AMD Ryzen 7             | 1        | 4.35%   |
| AMD Phenom              | 1        | 4.35%   |
| AMD Athlon 64 X2        | 1        | 4.35%   |
| AMD Athlon 64           | 1        | 4.35%   |
| AMD A6                  | 1        | 4.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 8        | 34.78%  |
| 4      | 5        | 21.74%  |
| 1      | 5        | 21.74%  |
| 8      | 2        | 8.7%    |
| 6      | 2        | 8.7%    |
| 24     | 1        | 4.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 23       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 14       | 60.87%  |
| 2      | 9        | 39.13%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 21       | 91.3%   |
| 32-bit         | 2        | 8.7%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 6        | 26.09%  |
| 0x1067a    | 5        | 21.74%  |
| 0xa0671    | 2        | 8.7%    |
| 0x206a7    | 2        | 8.7%    |
| 0x906ed    | 1        | 4.35%   |
| 0x6fd      | 1        | 4.35%   |
| 0x652      | 1        | 4.35%   |
| 0x106ca    | 1        | 4.35%   |
| 0x106c2    | 1        | 4.35%   |
| 0x10676    | 1        | 4.35%   |
| 0x06001116 | 1        | 4.35%   |
| 0x01000095 | 1        | 4.35%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Penryn           | 6        | 26.09%  |
| Unknown          | 4        | 17.39%  |
| K8 Hammer        | 3        | 13.04%  |
| SandyBridge      | 2        | 8.7%    |
| Bonnell          | 2        | 8.7%    |
| Zen+             | 1        | 4.35%   |
| Piledriver       | 1        | 4.35%   |
| KabyLake         | 1        | 4.35%   |
| K10              | 1        | 4.35%   |
| Core             | 1        | 4.35%   |
| Alderlake Hybrid | 1        | 4.35%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Nvidia           | 9        | 37.5%   |
| Intel            | 8        | 33.33%  |
| AMD              | 6        | 25%     |
| VIA Technologies | 1        | 4.17%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                     | 2        | 7.41%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                          | 2        | 7.41%   |
| VIA Technologies VX900 Graphics [Chrome9 HD]                              | 1        | 3.7%    |
| Nvidia GT218 [GeForce G210]                                               | 1        | 3.7%    |
| Nvidia GT216 [GeForce GT 220]                                             | 1        | 3.7%    |
| Nvidia GP108 [GeForce GT 1030]                                            | 1        | 3.7%    |
| Nvidia GF119 [GeForce GT 520]                                             | 1        | 3.7%    |
| Nvidia GF108 [GeForce GT 630]                                             | 1        | 3.7%    |
| Nvidia GA102 [GeForce RTX 3090 Ti]                                        | 1        | 3.7%    |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                       | 1        | 3.7%    |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                | 1        | 3.7%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 1        | 3.7%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                 | 1        | 3.7%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller   | 1        | 3.7%    |
| Intel 82G33/G31 Express Integrated Graphics Controller                    | 1        | 3.7%    |
| Intel 82945G/GZ Integrated Graphics Controller                            | 1        | 3.7%    |
| Intel 4 Series Chipset Integrated Graphics Controller                     | 1        | 3.7%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 1        | 3.7%    |
| AMD RV516 [Radeon X1300/X1550 Series] (Secondary)                         | 1        | 3.7%    |
| AMD RV516 [Radeon X1300/X1550 Series]                                     | 1        | 3.7%    |
| AMD RV515 [Radeon X1300/X1550]                                            | 1        | 3.7%    |
| AMD RV515 [Radeon X1300/X1550 Series] (Secondary)                         | 1        | 3.7%    |
| AMD RV280 [Radeon 9200 PRO] (Secondary)                                   | 1        | 3.7%    |
| AMD RV280 [Radeon 9200 PRO / 9250]                                        | 1        | 3.7%    |
| AMD Rage 3 [3D Rage PRO AGP 2X]                                           | 1        | 3.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 8        | 34.78%  |
| 1 x Intel      | 7        | 30.43%  |
| 2 x AMD        | 3        | 13.04%  |
| 1 x AMD        | 3        | 13.04%  |
| 1 x VIA        | 1        | 4.35%   |
| Intel + Nvidia | 1        | 4.35%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 15       | 65.22%  |
| Proprietary | 4        | 17.39%  |
| Unknown     | 4        | 17.39%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 11       | 47.83%  |
| 0.01-0.5   | 6        | 26.09%  |
| 1.01-2.0   | 2        | 8.7%    |
| 0.51-1.0   | 2        | 8.7%    |
| 5.01-6.0   | 1        | 4.35%   |
| 16.01-24.0 | 1        | 4.35%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Acer                 | 4        | 26.67%  |
| Goldstar             | 3        | 20%     |
| Samsung Electronics  | 2        | 13.33%  |
| Vizio                | 1        | 6.67%   |
| LG Electronics       | 1        | 6.67%   |
| Dell                 | 1        | 6.67%   |
| AOC                  | 1        | 6.67%   |
| Ancor Communications | 1        | 6.67%   |
| Unknown              | 1        | 6.67%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Vizio E280i-A1 VIZ1002 1360x768 607x345mm 27.5-inch                   | 1        | 6.67%   |
| Samsung Electronics SyncMaster SAM0091 1600x1200 432x324mm 21.3-inch  | 1        | 6.67%   |
| Samsung Electronics SMT22A300 SAM087B 1920x1080 480x270mm 21.7-inch   | 1        | 6.67%   |
| LG Electronics LCD Monitor LG Ultra HD 4480x3600                      | 1        | 6.67%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 1        | 6.67%   |
| Goldstar TV GSM9CF5 1360x768 700x392mm 31.6-inch                      | 1        | 6.67%   |
| Goldstar M198WA GSM4B36 1440x900 408x255mm 18.9-inch                  | 1        | 6.67%   |
| Dell E1916H DELF064 1366x768 410x230mm 18.5-inch                      | 1        | 6.67%   |
| AOC 2280W AOC2280 1920x1080 477x268mm 21.5-inch                       | 1        | 6.67%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch | 1        | 6.67%   |
| Acer VG220Q ACR06D8 1920x1080 476x268mm 21.5-inch                     | 1        | 6.67%   |
| Acer V243H ACR00A3 1920x1080 531x298mm 24.0-inch                      | 1        | 6.67%   |
| Acer V223HQV ACR025D 1920x1080 510x287mm 23.0-inch                    | 1        | 6.67%   |
| Acer S271HL ACR02CA 1920x1080 598x336mm 27.0-inch                     | 1        | 6.67%   |
| Unknown                                                               | 1        | 6.67%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Desktops | Percent |
|------------------|----------|---------|
| 1920x1080 (FHD)  | 7        | 46.67%  |
| 1366x768 (WXGA)  | 2        | 13.33%  |
| 4480x3600        | 1        | 6.67%   |
| 2560x1080        | 1        | 6.67%   |
| 1600x1200        | 1        | 6.67%   |
| 1440x900 (WXGA+) | 1        | 6.67%   |
| 1360x768         | 1        | 6.67%   |
| Unknown          | 1        | 6.67%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 5        | 35.71%  |
| 38      | 1        | 7.14%   |
| 34      | 1        | 7.14%   |
| 31      | 1        | 7.14%   |
| 27      | 1        | 7.14%   |
| 24      | 1        | 7.14%   |
| 23      | 1        | 7.14%   |
| 19      | 1        | 7.14%   |
| 18      | 1        | 7.14%   |
| Unknown | 1        | 7.14%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 7        | 50%     |
| 501-600     | 3        | 21.43%  |
| 801-900     | 1        | 7.14%   |
| 701-800     | 1        | 7.14%   |
| 601-700     | 1        | 7.14%   |
| Unknown     | 1        | 7.14%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 10       | 71.43%  |
| 4/3     | 1        | 7.14%   |
| 21/9    | 1        | 7.14%   |
| 16/10   | 1        | 7.14%   |
| Unknown | 1        | 7.14%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 6        | 42.86%  |
| 351-500        | 2        | 14.29%  |
| 151-200        | 2        | 14.29%  |
| 301-350        | 1        | 7.14%   |
| 141-150        | 1        | 7.14%   |
| 501-1000       | 1        | 7.14%   |
| Unknown        | 1        | 7.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 7        | 50%     |
| 101-120 | 4        | 28.57%  |
| 1-50    | 2        | 14.29%  |
| Unknown | 1        | 7.14%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 17       | 73.91%  |
| 0     | 5        | 21.74%  |
| 2     | 1        | 4.35%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 15       | 46.88%  |
| Intel                           | 6        | 18.75%  |
| Nvidia                          | 3        | 9.38%   |
| Ralink Technology               | 2        | 6.25%   |
| Samsung Electronics             | 1        | 3.13%   |
| Ralink                          | 1        | 3.13%   |
| Qualcomm Atheros Communications | 1        | 3.13%   |
| Marvell Technology Group        | 1        | 3.13%   |
| LSI                             | 1        | 3.13%   |
| Broadcom                        | 1        | 3.13%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 5        | 13.89%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 3        | 8.33%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 2        | 5.56%   |
| Realtek RTL8125 2.5GbE Controller                                             | 2        | 5.56%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                    | 2        | 5.56%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2        | 5.56%   |
| Ralink RT5370 Wireless Adapter                                                | 2        | 5.56%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 2        | 5.56%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                   | 1        | 2.78%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 2.78%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                     | 1        | 2.78%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1        | 2.78%   |
| Nvidia MCP61 Ethernet                                                         | 1        | 2.78%   |
| Nvidia CK8S Ethernet Controller                                               | 1        | 2.78%   |
| Nvidia CK804 Ethernet Controller                                              | 1        | 2.78%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                             | 1        | 2.78%   |
| LSI 56k WinModem                                                              | 1        | 2.78%   |
| Intel Ethernet Controller I225-V                                              | 1        | 2.78%   |
| Intel Ethernet Connection (7) I219-V                                          | 1        | 2.78%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 1        | 2.78%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 1        | 2.78%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1        | 2.78%   |
| Intel 700 Series Chipset Family Wi-Fi                                         | 1        | 2.78%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                               | 1        | 2.78%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 4        | 40%     |
| Realtek Semiconductor           | 2        | 20%     |
| Ralink Technology               | 2        | 20%     |
| Ralink                          | 1        | 10%     |
| Qualcomm Atheros Communications | 1        | 10%     |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 2        | 20%     |
| Ralink RT5370 Wireless Adapter                                                | 2        | 20%     |
| Intel Tiger Lake PCH CNVi WiFi                                                | 2        | 20%     |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                     | 1        | 10%     |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1        | 10%     |
| Intel Cannon Lake PCH CNVi WiFi                                               | 1        | 10%     |
| Intel 700 Series Chipset Family Wi-Fi                                         | 1        | 10%     |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 15       | 60%     |
| Intel                    | 4        | 16%     |
| Nvidia                   | 3        | 12%     |
| Samsung Electronics      | 1        | 4%      |
| Marvell Technology Group | 1        | 4%      |
| Broadcom                 | 1        | 4%      |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 5        | 20%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 12%     |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 8%      |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 2        | 8%      |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 8%      |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 4%      |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 4%      |
| Nvidia MCP61 Ethernet                                             | 1        | 4%      |
| Nvidia CK8S Ethernet Controller                                   | 1        | 4%      |
| Nvidia CK804 Ethernet Controller                                  | 1        | 4%      |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 4%      |
| Intel Ethernet Controller I225-V                                  | 1        | 4%      |
| Intel Ethernet Connection (7) I219-V                              | 1        | 4%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 4%      |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 4%      |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1        | 4%      |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 22       | 70.97%  |
| WiFi     | 8        | 25.81%  |
| Modem    | 1        | 3.23%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 19       | 79.17%  |
| WiFi     | 5        | 20.83%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 17       | 73.91%  |
| 2     | 6        | 26.09%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 18       | 78.26%  |
| Yes  | 5        | 21.74%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 4        | 66.67%  |
| Cambridge Silicon Radio | 2        | 33.33%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX201 Bluetooth                               | 2        | 33.33%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2        | 33.33%  |
| Intel Bluetooth Device                              | 1        | 16.67%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 16.67%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 14       | 42.42%  |
| Nvidia              | 9        | 27.27%  |
| AMD                 | 3        | 9.09%   |
| Creative Labs       | 2        | 6.06%   |
| C-Media Electronics | 2        | 6.06%   |
| VIA Technologies    | 1        | 3.03%   |
| ULi Electronics     | 1        | 3.03%   |
| Ensoniq             | 1        | 3.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5        | 14.29%  |
| Nvidia TU116 High Definition Audio Controller                              | 2        | 5.71%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2        | 5.71%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2        | 5.71%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2        | 5.71%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller             | 1        | 2.86%   |
| VIA Technologies High Definition Audio Controller                          | 1        | 2.86%   |
| ULi Electronics HD Audio Controller                                        | 1        | 2.86%   |
| Nvidia High Definition Audio Controller                                    | 1        | 2.86%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1        | 2.86%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 2.86%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1        | 2.86%   |
| Nvidia GF108 High Definition Audio Controller                              | 1        | 2.86%   |
| Nvidia GA102 High Definition Audio Controller                              | 1        | 2.86%   |
| Nvidia CK804 AC'97 Audio Controller                                        | 1        | 2.86%   |
| Intel Cannon Lake PCH cAVS                                                 | 1        | 2.86%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1        | 2.86%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 1        | 2.86%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1        | 2.86%   |
| Intel 700 Series Chipset Family Precise Touch and Stylus Port #1           | 1        | 2.86%   |
| Ensoniq ES1371/ES1373 / Creative Labs CT2518                               | 1        | 2.86%   |
| Creative Labs EMU20k1 [Sound Blaster X-Fi Series]                          | 1        | 2.86%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]  | 1        | 2.86%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                              | 1        | 2.86%   |
| C-Media Electronics CM6501                                                 | 1        | 2.86%   |
| AMD FCH Azalia Controller                                                  | 1        | 2.86%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1        | 2.86%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 8        | 32%     |
| SK hynix            | 3        | 12%     |
| Samsung Electronics | 3        | 12%     |
| Kingston            | 3        | 12%     |
| Corsair             | 2        | 8%      |
| Unknown (0x0DA2)    | 1        | 4%      |
| Smart               | 1        | 4%      |
| Ramaxel Technology  | 1        | 4%      |
| Patriot             | 1        | 4%      |
| Kllisre             | 1        | 4%      |
| A-DATA Technology   | 1        | 4%      |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 2GB DIMM SDRAM                        | 2        | 7.41%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s   | 2        | 7.41%   |
| Unknown RAM Module 512MB DIMM DDR 400MT/s                | 1        | 3.7%    |
| Unknown RAM Module 512MB DIMM DDR 333MT/s                | 1        | 3.7%    |
| Unknown RAM Module 512MB DIMM                            | 1        | 3.7%    |
| Unknown RAM Module 2GB DIMM DDR3 800MT/s                 | 1        | 3.7%    |
| Unknown RAM Module 1GB DIMM SDRAM                        | 1        | 3.7%    |
| Unknown RAM Module 1GB DIMM DDR 333MT/s                  | 1        | 3.7%    |
| Unknown RAM Module 1GB DIMM 667MT/s                      | 1        | 3.7%    |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s              | 1        | 3.7%    |
| Unknown (0x0DA2) RAM SB-DR5U-32G 32GB DIMM DDR5 4800MT/s | 1        | 3.7%    |
| Smart RAM SG564568FG8N6KFSQR 2GB DIMM DDR2 800MT/s       | 1        | 3.7%    |
| SK hynix RAM HMT41GU6MFR8C-PB 8GB DIMM DDR3 1600MT/s     | 1        | 3.7%    |
| SK hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s   | 1        | 3.7%    |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM 1333MT/s          | 1        | 3.7%    |
| Samsung RAM M378B5673FH0 2GB DIMM DDR3 1333MT/s          | 1        | 3.7%    |
| Samsung RAM M378A2K43CB1-CTD 16384MB DIMM DDR4 3200MT/s  | 1        | 3.7%    |
| Samsung RAM M3 78T5663EH3-CF7 2GB DIMM DDR2 800MT/s      | 1        | 3.7%    |
| Ramaxel RAM RMUA5180MH78HBF-2666 16GB DIMM DDR4 2400MT/s | 1        | 3.7%    |
| Patriot RAM PSD34G1600L2S 4GB SODIMM DDR3 1600MT/s       | 1        | 3.7%    |
| Kllisre RAM DDR2 2G 2GB DIMM DDR2 800MT/s                | 1        | 3.7%    |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s      | 1        | 3.7%    |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM 1600MT/s         | 1        | 3.7%    |
| Kingston RAM 99U5402-060.A 2GB DIMM DDR3 1333MT/s        | 1        | 3.7%    |
| A-DATA RAM DDR4 2666 2OZ 16GB DIMM DDR4 2667MT/s         | 1        | 3.7%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 6        | 28.57%  |
| SDRAM   | 4        | 19.05%  |
| DDR4    | 4        | 19.05%  |
| DDR2    | 2        | 9.52%   |
| DDR     | 2        | 9.52%   |
| Unknown | 2        | 9.52%   |
| DDR5    | 1        | 4.76%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 19       | 90.48%  |
| SODIMM | 2        | 9.52%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 2048  | 8        | 33.33%  |
| 16384 | 4        | 16.67%  |
| 1024  | 4        | 16.67%  |
| 4096  | 3        | 12.5%   |
| 512   | 3        | 12.5%   |
| 32768 | 1        | 4.17%   |
| 8192  | 1        | 4.17%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 4        | 17.39%  |
| Unknown | 3        | 13.04%  |
| 3534    | 2        | 8.7%    |
| 2400    | 2        | 8.7%    |
| 1333    | 2        | 8.7%    |
| 800     | 2        | 8.7%    |
| 667     | 2        | 8.7%    |
| 4800    | 1        | 4.35%   |
| 3200    | 1        | 4.35%   |
| 2667    | 1        | 4.35%   |
| 2048    | 1        | 4.35%   |
| 400     | 1        | 4.35%   |
| 333     | 1        | 4.35%   |

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


| Vendor         | Desktops | Percent |
|----------------|----------|---------|
| Pixart Imaging | 1        | 100%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Pixart Imaging GE 1.3 MP MiniCam Pro | 1        | 100%    |

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
| 0     | 18       | 78.26%  |
| 2     | 2        | 8.7%    |
| 1     | 2        | 8.7%    |
| 3     | 1        | 4.35%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 5        | 55.56%  |
| Communication controller | 2        | 22.22%  |
| Net/ethernet             | 1        | 11.11%  |
| Modem                    | 1        | 11.11%  |

