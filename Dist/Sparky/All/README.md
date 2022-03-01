Sparky - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for Sparky.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Sparky/Desktop/README.md) and [notebooks](/Dist/Sparky/Notebook/README.md).

Full-feature report is available here: https://linux-hardware.org/?view=trends

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

| Vendor    | Model                       | Form-Factor | Probe                                                      | Date         |
|-----------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek   | 1000HE                      | Notebook    | [5dd6246e59](https://linux-hardware.org/?probe=5dd6246e59) | Feb 08, 2022 |
| ASUSTek   | S101                        | Notebook    | [a850549e73](https://linux-hardware.org/?probe=a850549e73) | Feb 04, 2022 |
| ASUSTek   | CROSSHAIR VI HERO           | Desktop     | [39dcd3854f](https://linux-hardware.org/?probe=39dcd3854f) | Feb 03, 2022 |
| MSI       | B450 GAMING PLUS MAX        | Desktop     | [47eae3d6b2](https://linux-hardware.org/?probe=47eae3d6b2) | Jan 19, 2022 |
| HP        | EliteBook 8770w             | Notebook    | [9a2052fc8c](https://linux-hardware.org/?probe=9a2052fc8c) | Nov 25, 2021 |
| HP        | Pavilion g7                 | Notebook    | [6cebc99fe6](https://linux-hardware.org/?probe=6cebc99fe6) | Nov 22, 2021 |
| Dell      | Inspiron N5010              | Notebook    | [df5e66431b](https://linux-hardware.org/?probe=df5e66431b) | Nov 20, 2021 |
| HP        | EliteBook Folio 9480m       | Notebook    | [dae2e04d45](https://linux-hardware.org/?probe=dae2e04d45) | Oct 04, 2021 |
| Google    | Banon                       | Notebook    | [764debedcd](https://linux-hardware.org/?probe=764debedcd) | Sep 25, 2021 |
| MSI       | H310M PRO-VDH PLUS          | Desktop     | [079af91b8f](https://linux-hardware.org/?probe=079af91b8f) | Aug 22, 2021 |
| MSI       | H310M PRO-VDH PLUS          | Desktop     | [c6fe94a0ba](https://linux-hardware.org/?probe=c6fe94a0ba) | Aug 22, 2021 |
| HP        | 805B                        | Desktop     | [d6c2730444](https://linux-hardware.org/?probe=d6c2730444) | Jul 12, 2021 |
| Gigabyte  | H97-Gaming 3                | Desktop     | [d8b0632698](https://linux-hardware.org/?probe=d8b0632698) | May 23, 2021 |
| Lenovo    | ThinkPad E15 20RES0GF00     | Notebook    | [8722c3498e](https://linux-hardware.org/?probe=8722c3498e) | May 14, 2021 |
| Intel     | NUC5CPYB H61145-408         | Mini pc     | [7243895ae4](https://linux-hardware.org/?probe=7243895ae4) | Apr 20, 2021 |
| Apple     | MacBook1,1                  | Notebook    | [cc415ab6c7](https://linux-hardware.org/?probe=cc415ab6c7) | Mar 15, 2021 |
| Samsung   | NC10                        | Notebook    | [b5909af616](https://linux-hardware.org/?probe=b5909af616) | Mar 11, 2021 |
| Samsung   | NC10                        | Notebook    | [3b8de5559e](https://linux-hardware.org/?probe=3b8de5559e) | Feb 27, 2021 |
| MSI       | A68HM-E33 V2                | Desktop     | [82a06b4bea](https://linux-hardware.org/?probe=82a06b4bea) | Feb 21, 2021 |
| Lenovo    | ThinkPad T61 7659AB7        | Notebook    | [43f03346c5](https://linux-hardware.org/?probe=43f03346c5) | Feb 19, 2021 |
| Gigabyte  | H410M H                     | Desktop     | [ee13368ccf](https://linux-hardware.org/?probe=ee13368ccf) | Feb 18, 2021 |
| Pegatron  | 2AC2A                       | Desktop     | [8a5448bc07](https://linux-hardware.org/?probe=8a5448bc07) | Jan 17, 2021 |
| Pegatron  | 2AC2A                       | Desktop     | [c06bb14e30](https://linux-hardware.org/?probe=c06bb14e30) | Jan 16, 2021 |
| Pegatron  | 2AC2A                       | Desktop     | [e6e40ab204](https://linux-hardware.org/?probe=e6e40ab204) | Jan 15, 2021 |
| Pegatron  | 2AC2A                       | Desktop     | [79c06ebf01](https://linux-hardware.org/?probe=79c06ebf01) | Jan 15, 2021 |
| Pegatron  | 2AC2A                       | Desktop     | [c76bbefc71](https://linux-hardware.org/?probe=c76bbefc71) | Jan 09, 2021 |
| Beelink   | BT3 PRO                     | Notebook    | [8dbfa4dacd](https://linux-hardware.org/?probe=8dbfa4dacd) | Jan 06, 2021 |
| Beelink   | BT3 PRO                     | Notebook    | [d85a392e02](https://linux-hardware.org/?probe=d85a392e02) | Jan 06, 2021 |
| Samsung   | NC10                        | Notebook    | [8c878860a7](https://linux-hardware.org/?probe=8c878860a7) | Jan 03, 2021 |
| Pegatron  | 2AC2A                       | Desktop     | [95ead72109](https://linux-hardware.org/?probe=95ead72109) | Dec 17, 2020 |
| HP        | 8056                        | Desktop     | [79fd2c8837](https://linux-hardware.org/?probe=79fd2c8837) | Dec 12, 2020 |
| Dell      | Inspiron 5720               | Notebook    | [d360a61780](https://linux-hardware.org/?probe=d360a61780) | Dec 08, 2020 |
| eMachines | E525                        | Notebook    | [0c11b6b4dc](https://linux-hardware.org/?probe=0c11b6b4dc) | Nov 25, 2020 |
| Lenovo    | IdeaPad S206 20154          | Notebook    | [393f27acf7](https://linux-hardware.org/?probe=393f27acf7) | Nov 18, 2020 |
| Intel     | DG41TY AAE47335-300         | Desktop     | [e3457f83fa](https://linux-hardware.org/?probe=e3457f83fa) | Oct 22, 2020 |
| Dell      | Inspiron 5720               | Notebook    | [787263a0c6](https://linux-hardware.org/?probe=787263a0c6) | Oct 10, 2020 |
| Gigabyte  | M68M-S2P                    | Desktop     | [0e4bab3503](https://linux-hardware.org/?probe=0e4bab3503) | Oct 05, 2020 |
| HP        | Laptop 17z-ca100            | Notebook    | [2217d0703c](https://linux-hardware.org/?probe=2217d0703c) | Oct 05, 2020 |
| HP        | Laptop 17z-ca100            | Notebook    | [1927ffc179](https://linux-hardware.org/?probe=1927ffc179) | Oct 05, 2020 |
| Unknown   | 4CoreDX90-VSTA              | Desktop     | [31dbedff45](https://linux-hardware.org/?probe=31dbedff45) | Sep 10, 2020 |
| Apple     | MacBook1,1                  | Notebook    | [73b04f9de4](https://linux-hardware.org/?probe=73b04f9de4) | Aug 26, 2020 |
| Gigabyte  | G41M-ES2L                   | Desktop     | [87c93c4148](https://linux-hardware.org/?probe=87c93c4148) | Jun 21, 2020 |
| Gigabyte  | G41M-ES2L                   | Desktop     | [01beb1ea00](https://linux-hardware.org/?probe=01beb1ea00) | Jun 21, 2020 |
| Dell      | 039VR8 A00                  | Desktop     | [d386006ad9](https://linux-hardware.org/?probe=d386006ad9) | Jun 15, 2020 |
| Acer      | Aspire 5742G                | Notebook    | [a90fb35c67](https://linux-hardware.org/?probe=a90fb35c67) | May 01, 2020 |
| Vorke     | V1 Plus                     | Desktop     | [e371a7cf42](https://linux-hardware.org/?probe=e371a7cf42) | Mar 29, 2020 |
| Intel     | DG43RK AAE78175-402         | Desktop     | [262ba9568a](https://linux-hardware.org/?probe=262ba9568a) | Mar 22, 2020 |
| Lenovo    | ThinkPad T60 2007FUG        | Notebook    | [d552e50d7e](https://linux-hardware.org/?probe=d552e50d7e) | Mar 12, 2020 |
| Dell      | Latitude XT3                | Notebook    | [0944e88882](https://linux-hardware.org/?probe=0944e88882) | Mar 09, 2020 |
| Dell      | Inspiron 5770               | Notebook    | [a3dd71465d](https://linux-hardware.org/?probe=a3dd71465d) | Jan 06, 2020 |
| HP        | Pavilion dv9000 (GA359UA... | Notebook    | [db4a924be0](https://linux-hardware.org/?probe=db4a924be0) | Sep 07, 2019 |
| HP        | Pavilion dv9000 (GA359UA... | Notebook    | [622123c1e6](https://linux-hardware.org/?probe=622123c1e6) | Sep 07, 2019 |
| HP        | Pavilion dv9000 (GA359UA... | Notebook    | [6f024c0dd0](https://linux-hardware.org/?probe=6f024c0dd0) | Sep 03, 2019 |
| ASRock    | H61M-VG4                    | Desktop     | [93ae8e7a8c](https://linux-hardware.org/?probe=93ae8e7a8c) | Aug 18, 2019 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Computers | Percent |
|---------------------|-----------|---------|
| 5.10.0-9-amd64      | 3         | 7.69%   |
| 5.10.0-8-amd64      | 3         | 7.69%   |
| 5.10.0-6-amd64      | 3         | 7.69%   |
| 4.19.0-8-amd64      | 3         | 7.69%   |
| 4.19.0-12-amd64     | 3         | 7.69%   |
| 5.10.0-3-amd64      | 2         | 5.13%   |
| 5.10.0-11-686       | 2         | 5.13%   |
| 4.19.0-13-686       | 2         | 5.13%   |
| 4.19.0-10-686       | 2         | 5.13%   |
| 5.9.13-sparky-amd64 | 1         | 2.56%   |
| 5.9.0-4-amd64       | 1         | 2.56%   |
| 5.8.13-sparky-amd64 | 1         | 2.56%   |
| 5.8.0-2-amd64       | 1         | 2.56%   |
| 5.7.2-sparky-amd64  | 1         | 2.56%   |
| 5.6.0-2-amd64       | 1         | 2.56%   |
| 5.5.0-2-amd64       | 1         | 2.56%   |
| 5.4.7-sparky-amd64  | 1         | 2.56%   |
| 5.2.0-2-amd64       | 1         | 2.56%   |
| 5.16.5-sparky-amd64 | 1         | 2.56%   |
| 5.14.0-4-amd64      | 1         | 2.56%   |
| 5.10.4-sparky-amd64 | 1         | 2.56%   |
| 5.10.0-7-amd64      | 1         | 2.56%   |
| 5.10.0-2-amd64      | 1         | 2.56%   |
| 4.19.0-14-686       | 1         | 2.56%   |
| 4.19.0-10-amd64     | 1         | 2.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 15        | 40.54%  |
| 4.19.0  | 10        | 27.03%  |
| 5.9.13  | 1         | 2.7%    |
| 5.9.0   | 1         | 2.7%    |
| 5.8.13  | 1         | 2.7%    |
| 5.8.0   | 1         | 2.7%    |
| 5.7.2   | 1         | 2.7%    |
| 5.6.0   | 1         | 2.7%    |
| 5.5.0   | 1         | 2.7%    |
| 5.4.7   | 1         | 2.7%    |
| 5.2.0   | 1         | 2.7%    |
| 5.16.5  | 1         | 2.7%    |
| 5.14.0  | 1         | 2.7%    |
| 5.10.4  | 1         | 2.7%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 16        | 43.24%  |
| 4.19    | 10        | 27.03%  |
| 5.9     | 2         | 5.41%   |
| 5.8     | 2         | 5.41%   |
| 5.7     | 1         | 2.7%    |
| 5.6     | 1         | 2.7%    |
| 5.5     | 1         | 2.7%    |
| 5.4     | 1         | 2.7%    |
| 5.2     | 1         | 2.7%    |
| 5.16    | 1         | 2.7%    |
| 5.14    | 1         | 2.7%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 31        | 86.11%  |
| i686   | 5         | 13.89%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| LXQt             | 12        | 32.43%  |
| XFCE             | 11        | 29.73%  |
| Unknown          | 7         | 18.92%  |
| KDE5             | 2         | 5.41%   |
| GNOME            | 2         | 5.41%   |
| X-Cinnamon       | 1         | 2.7%    |
| MATE             | 1         | 2.7%    |
| lightdm-xsession | 1         | 2.7%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 34        | 91.89%  |
| Tty  | 3         | 8.11%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| TDM     | 13        | 36.11%  |
| Unknown | 9         | 25%     |
| SDDM    | 8         | 22.22%  |
| LightDM | 4         | 11.11%  |
| XDM     | 1         | 2.78%   |
| GDM     | 1         | 2.78%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 10        | 27.78%  |
| en_GB   | 4         | 11.11%  |
| pl_PL   | 3         | 8.33%   |
| pt_BR   | 2         | 5.56%   |
| es_ES   | 2         | 5.56%   |
| de_DE   | 2         | 5.56%   |
| Unknown | 2         | 5.56%   |
| sv_SE   | 1         | 2.78%   |
| ja_JP   | 1         | 2.78%   |
| es_US   | 1         | 2.78%   |
| es_CL   | 1         | 2.78%   |
| es_AR   | 1         | 2.78%   |
| en_ZA   | 1         | 2.78%   |
| en_PH   | 1         | 2.78%   |
| en_DK   | 1         | 2.78%   |
| en_CA   | 1         | 2.78%   |
| de_CH   | 1         | 2.78%   |
| cs_CZ   | 1         | 2.78%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 24        | 66.67%  |
| EFI  | 12        | 33.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 32        | 88.89%  |
| Overlay | 2         | 5.56%   |
| Zfs     | 1         | 2.78%   |
| Btrfs   | 1         | 2.78%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| MBR     | 14        | 38.89%  |
| GPT     | 12        | 33.33%  |
| Unknown | 10        | 27.78%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 30        | 83.33%  |
| Yes       | 6         | 16.67%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 22        | 61.11%  |
| Yes       | 14        | 38.89%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 7         | 19.44%  |
| Dell                | 5         | 13.89%  |
| Lenovo              | 4         | 11.11%  |
| Gigabyte Technology | 4         | 11.11%  |
| MSI                 | 3         | 8.33%   |
| Intel               | 3         | 8.33%   |
| ASUSTek Computer    | 3         | 8.33%   |
| Samsung Electronics | 1         | 2.78%   |
| Google              | 1         | 2.78%   |
| eMachines           | 1         | 2.78%   |
| Beelink             | 1         | 2.78%   |
| Apple               | 1         | 2.78%   |
| Acer                | 1         | 2.78%   |
| Unknown             | 1         | 2.78%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| Samsung NC10                     | 1         | 2.78%   |
| MSI MS-7C09                      | 1         | 2.78%   |
| MSI MS-7B86                      | 1         | 2.78%   |
| MSI MS-7721                      | 1         | 2.78%   |
| Lenovo ThinkPad T61 7659AB7      | 1         | 2.78%   |
| Lenovo ThinkPad T60 2007FUG      | 1         | 2.78%   |
| Lenovo ThinkPad E15 20RES0GF00   | 1         | 2.78%   |
| Lenovo IdeaPad S206 20154        | 1         | 2.78%   |
| Intel NUC5CPYB H61145-408        | 1         | 2.78%   |
| Intel DG43RK AAE78175-402        | 1         | 2.78%   |
| Intel DG41TY AAE47335-300        | 1         | 2.78%   |
| HP Pavilion g7                   | 1         | 2.78%   |
| HP Pavilion dv9000 (GA359UA#ABA) | 1         | 2.78%   |
| HP Laptop 17z-ca100              | 1         | 2.78%   |
| HP EliteDesk 800 G2 DM 65W       | 1         | 2.78%   |
| HP EliteDesk 705 G2 MINI         | 1         | 2.78%   |
| HP EliteBook Folio 9480m         | 1         | 2.78%   |
| HP EliteBook 8770w               | 1         | 2.78%   |
| Google Banon                     | 1         | 2.78%   |
| Gigabyte M68M-S2P                | 1         | 2.78%   |
| Gigabyte H97-Gaming 3            | 1         | 2.78%   |
| Gigabyte H410M H                 | 1         | 2.78%   |
| Gigabyte G41M-ES2L               | 1         | 2.78%   |
| eMachines E525                   | 1         | 2.78%   |
| Dell OptiPlex 580                | 1         | 2.78%   |
| Dell Latitude XT3                | 1         | 2.78%   |
| Dell Inspiron N5010              | 1         | 2.78%   |
| Dell Inspiron 5770               | 1         | 2.78%   |
| Dell Inspiron 5720               | 1         | 2.78%   |
| Beelink BT3 PRO                  | 1         | 2.78%   |
| ASUS S101                        | 1         | 2.78%   |
| ASUS CROSSHAIR VI HERO           | 1         | 2.78%   |
| ASUS 1000HE                      | 1         | 2.78%   |
| Apple MacBook1,1                 | 1         | 2.78%   |
| Acer Aspire 5742G                | 1         | 2.78%   |
| Unknown                          | 1         | 2.78%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 3         | 8.33%   |
| Dell Inspiron       | 3         | 8.33%   |
| HP Pavilion         | 2         | 5.56%   |
| HP EliteDesk        | 2         | 5.56%   |
| HP EliteBook        | 2         | 5.56%   |
| Samsung NC10        | 1         | 2.78%   |
| MSI MS-7C09         | 1         | 2.78%   |
| MSI MS-7B86         | 1         | 2.78%   |
| MSI MS-7721         | 1         | 2.78%   |
| Lenovo IdeaPad      | 1         | 2.78%   |
| Intel NUC5CPYB      | 1         | 2.78%   |
| Intel DG43RK        | 1         | 2.78%   |
| Intel DG41TY        | 1         | 2.78%   |
| HP Laptop           | 1         | 2.78%   |
| Google Banon        | 1         | 2.78%   |
| Gigabyte M68M-S2P   | 1         | 2.78%   |
| Gigabyte H97-Gaming | 1         | 2.78%   |
| Gigabyte H410M      | 1         | 2.78%   |
| Gigabyte G41M-ES2L  | 1         | 2.78%   |
| eMachines E525      | 1         | 2.78%   |
| Dell OptiPlex       | 1         | 2.78%   |
| Dell Latitude       | 1         | 2.78%   |
| Beelink BT3         | 1         | 2.78%   |
| ASUS S101           | 1         | 2.78%   |
| ASUS CROSSHAIR      | 1         | 2.78%   |
| ASUS 1000HE         | 1         | 2.78%   |
| Apple MacBook1      | 1         | 2.78%   |
| Acer Aspire         | 1         | 2.78%   |
| Unknown             | 1         | 2.78%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2009 | 6         | 16.67%  |
| 2012 | 4         | 11.11%  |
| 2018 | 3         | 8.33%   |
| 2010 | 3         | 8.33%   |
| 2021 | 2         | 5.56%   |
| 2020 | 2         | 5.56%   |
| 2019 | 2         | 5.56%   |
| 2015 | 2         | 5.56%   |
| 2014 | 2         | 5.56%   |
| 2011 | 2         | 5.56%   |
| 2008 | 2         | 5.56%   |
| 2007 | 2         | 5.56%   |
| 2006 | 2         | 5.56%   |
| 2017 | 1         | 2.78%   |
| 2016 | 1         | 2.78%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Notebook | 21        | 58.33%  |
| Desktop  | 14        | 38.89%  |
| Mini pc  | 1         | 2.78%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 36        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 35        | 97.22%  |
| Yes  | 1         | 2.78%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 10        | 27.78%  |
| 4.01-8.0   | 7         | 19.44%  |
| 16.01-24.0 | 5         | 13.89%  |
| 2.01-3.0   | 4         | 11.11%  |
| 1.01-2.0   | 4         | 11.11%  |
| 24.01-32.0 | 2         | 5.56%   |
| 8.01-16.0  | 2         | 5.56%   |
| 32.01-64.0 | 1         | 2.78%   |
| 0.51-1.0   | 1         | 2.78%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 17        | 45.95%  |
| 0.51-1.0 | 9         | 24.32%  |
| 2.01-3.0 | 4         | 10.81%  |
| 4.01-8.0 | 3         | 8.11%   |
| 3.01-4.0 | 2         | 5.41%   |
| 0.01-0.5 | 2         | 5.41%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 25        | 69.44%  |
| 2      | 7         | 19.44%  |
| 4      | 2         | 5.56%   |
| 5      | 1         | 2.78%   |
| 3      | 1         | 2.78%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 21        | 58.33%  |
| Yes       | 15        | 41.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 34        | 94.44%  |
| No        | 2         | 5.56%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 25        | 69.44%  |
| No        | 11        | 30.56%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 22        | 61.11%  |
| Yes       | 14        | 38.89%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 8         | 22.22%  |
| UK           | 4         | 11.11%  |
| Germany      | 4         | 11.11%  |
| Poland       | 3         | 8.33%   |
| Canada       | 2         | 5.56%   |
| Brazil       | 2         | 5.56%   |
| Argentina    | 2         | 5.56%   |
| Venezuela    | 1         | 2.78%   |
| Switzerland  | 1         | 2.78%   |
| Sweden       | 1         | 2.78%   |
| Spain        | 1         | 2.78%   |
| South Africa | 1         | 2.78%   |
| Philippines  | 1         | 2.78%   |
| Lebanon      | 1         | 2.78%   |
| Japan        | 1         | 2.78%   |
| France       | 1         | 2.78%   |
| Czechia      | 1         | 2.78%   |
| Chile        | 1         | 2.78%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Wroclaw               | 1         | 2.63%   |
| Wenatchee             | 1         | 2.63%   |
| Tucson                | 1         | 2.63%   |
| Takahama              | 1         | 2.63%   |
| Spokane               | 1         | 2.63%   |
| SkellefteГҐ         | 1         | 2.63%   |
| Santa Barbara         | 1         | 2.63%   |
| San Antonio           | 1         | 2.63%   |
| Saint-Basile-le-Grand | 1         | 2.63%   |
| Rosario               | 1         | 2.63%   |
| Rio Claro             | 1         | 2.63%   |
| Prague                | 1         | 2.63%   |
| Posadas               | 1         | 2.63%   |
| Pompano Beach         | 1         | 2.63%   |
| Pasig                 | 1         | 2.63%   |
| Paisley               | 1         | 2.63%   |
| Nasielsk              | 1         | 2.63%   |
| Montreal              | 1         | 2.63%   |
| Montagu               | 1         | 2.63%   |
| Mannheim              | 1         | 2.63%   |
| Leipzig               | 1         | 2.63%   |
| La Florida            | 1         | 2.63%   |
| Kruft                 | 1         | 2.63%   |
| KoЕ‚o              | 1         | 2.63%   |
| Houston               | 1         | 2.63%   |
| Grabs                 | 1         | 2.63%   |
| Glasgow               | 1         | 2.63%   |
| Givors                | 1         | 2.63%   |
| Frankfurt (Oder)      | 1         | 2.63%   |
| East Wenatchee        | 1         | 2.63%   |
| Dunoon                | 1         | 2.63%   |
| Chicago               | 1         | 2.63%   |
| Birmingham            | 1         | 2.63%   |
| Belford Roxo          | 1         | 2.63%   |
| Beirut                | 1         | 2.63%   |
| Basingstoke           | 1         | 2.63%   |
| Barnsley              | 1         | 2.63%   |
| AlcaÃ±iz            | 1         | 2.63%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 9         | 11     | 18.75%  |
| Samsung Electronics | 9         | 11     | 18.75%  |
| Seagate             | 8         | 12     | 16.67%  |
| Hitachi             | 5         | 6      | 10.42%  |
| Kingston            | 3         | 3      | 6.25%   |
| Unknown             | 2         | 2      | 4.17%   |
| Intel               | 2         | 2      | 4.17%   |
| GOODRAM             | 2         | 3      | 4.17%   |
| XPG                 | 1         | 1      | 2.08%   |
| SPCC                | 1         | 2      | 2.08%   |
| SanDisk             | 1         | 1      | 2.08%   |
| Micron Technology   | 1         | 1      | 2.08%   |
| Gigabyte Technology | 1         | 1      | 2.08%   |
| Fujitsu             | 1         | 2      | 2.08%   |
| ASUS-JM             | 1         | 1      | 2.08%   |
| A-DATA Technology   | 1         | 1      | 2.08%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| WDC WD1600BEVT-22ZCT0 160GB              | 2         | 3.77%   |
| Samsung HD161GJ 160GB                    | 2         | 3.77%   |
| Hitachi HTS545025B9A300 250GB            | 2         | 3.77%   |
| XPG GAMMIX S11 Pro 1TB                   | 1         | 1.89%   |
| WDC WD800JD-08MSA1 80GB                  | 1         | 1.89%   |
| WDC WD5000BEVT-22ZAT0 500GB              | 1         | 1.89%   |
| WDC WD5000AVVS-63ZWB0 500GB              | 1         | 1.89%   |
| WDC WD3200BPVT-75ZEST0 320GB             | 1         | 1.89%   |
| WDC WD2500AAKX-07U6AA0 250GB             | 1         | 1.89%   |
| WDC WD1600AAJS-08L7A0 160GB              | 1         | 1.89%   |
| WDC WD10EZEX-60WN4A0 1TB                 | 1         | 1.89%   |
| Unknown MMC Card  64GB                   | 1         | 1.89%   |
| Unknown HBG4a2  32GB                     | 1         | 1.89%   |
| SPCC Solid State Disk 256GB              | 1         | 1.89%   |
| Seagate ST9500325AS 500GB                | 1         | 1.89%   |
| Seagate ST9250315AS 250GB                | 1         | 1.89%   |
| Seagate ST9160310AS 160GB                | 1         | 1.89%   |
| Seagate ST500LT012-1DG142 500GB          | 1         | 1.89%   |
| Seagate ST3320418AS 320GB                | 1         | 1.89%   |
| Seagate ST2000VM003-1ET164 2TB           | 1         | 1.89%   |
| Seagate ST1000LM048-2E7172 1TB           | 1         | 1.89%   |
| Seagate ST1000LM035-1RK172 1TB           | 1         | 1.89%   |
| Seagate Backup+ Hub BK 8TB               | 1         | 1.89%   |
| Seagate Backup+ Desk 3TB                 | 1         | 1.89%   |
| SanDisk SSD PLUS 480GB                   | 1         | 1.89%   |
| Samsung SSD 850 EVO 500GB                | 1         | 1.89%   |
| Samsung SSD 850 EVO 250GB                | 1         | 1.89%   |
| Samsung SSD 840 Series 120GB             | 1         | 1.89%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB   | 1         | 1.89%   |
| Samsung MZVPV256HDGL-000H1 256GB         | 1         | 1.89%   |
| Samsung MZALQ512HALU-000L1 512GB         | 1         | 1.89%   |
| Samsung MZ7TD128HAFV-000L1 128GB SSD     | 1         | 1.89%   |
| Samsung HD753LJ 752GB                    | 1         | 1.89%   |
| Samsung HD154UI 1TB                      | 1         | 1.89%   |
| Micron MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 1.89%   |
| Kingston SV300S37A480G 480GB SSD         | 1         | 1.89%   |
| Kingston SA400S37120G 120GB SSD          | 1         | 1.89%   |
| Kingston SA400M8240G 240GB SSD           | 1         | 1.89%   |
| Intel SSDSA2BW120G3H 120GB               | 1         | 1.89%   |
| Intel SSDMAEXC024G3H 24GB                | 1         | 1.89%   |
| Hitachi HTS545025B9SA02 250GB            | 1         | 1.89%   |
| Hitachi HTS543232A7A384 320GB            | 1         | 1.89%   |
| Hitachi HTS541080G9SA00 80GB             | 1         | 1.89%   |
| GOODRAM SSDPR-CX400-256-G2 256GB         | 1         | 1.89%   |
| GOODRAM SSDPR-CL100-240-G3 240GB         | 1         | 1.89%   |
| GOODRAM IR-SSDPR-S25A-120 120GB          | 1         | 1.89%   |
| Gigabyte GP-GSTFS31120GNTD 120GB         | 1         | 1.89%   |
| Fujitsu MHW2120BH 120GB                  | 1         | 1.89%   |
| ASUS-JM S41 SSD 16GB                     | 1         | 1.89%   |
| A-DATA SX8200NP 480GB                    | 1         | 1.89%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 9         | 11     | 34.62%  |
| Seagate             | 8         | 11     | 30.77%  |
| Hitachi             | 5         | 6      | 19.23%  |
| Samsung Electronics | 3         | 4      | 11.54%  |
| Fujitsu             | 1         | 2      | 3.85%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 4      | 25%     |
| Kingston            | 3         | 3      | 18.75%  |
| Intel               | 2         | 2      | 12.5%   |
| GOODRAM             | 2         | 3      | 12.5%   |
| SPCC                | 1         | 2      | 6.25%   |
| SanDisk             | 1         | 1      | 6.25%   |
| Micron Technology   | 1         | 1      | 6.25%   |
| Gigabyte Technology | 1         | 1      | 6.25%   |
| ASUS-JM             | 1         | 1      | 6.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 24        | 34     | 51.06%  |
| SSD     | 15        | 18     | 31.91%  |
| NVMe    | 5         | 5      | 10.64%  |
| MMC     | 2         | 2      | 4.26%   |
| Unknown | 1         | 1      | 2.13%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 33        | 49     | 80.49%  |
| NVMe | 5         | 5      | 12.2%   |
| MMC  | 2         | 2      | 4.88%   |
| SAS  | 1         | 4      | 2.44%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 31        | 43     | 83.78%  |
| 0.51-1.0   | 4         | 5      | 10.81%  |
| 1.01-2.0   | 1         | 1      | 2.7%    |
| 4.01-10.0  | 1         | 3      | 2.7%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 13        | 36.11%  |
| 501-1000       | 5         | 13.89%  |
| 251-500        | 4         | 11.11%  |
| 1-20           | 4         | 11.11%  |
| 51-100         | 3         | 8.33%   |
| 21-50          | 2         | 5.56%   |
| Unknown        | 2         | 5.56%   |
| More than 3000 | 1         | 2.78%   |
| 2001-3000      | 1         | 2.78%   |
| 1001-2000      | 1         | 2.78%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 19        | 51.35%  |
| 51-100         | 5         | 13.51%  |
| 21-50          | 4         | 10.81%  |
| 101-250        | 2         | 5.41%   |
| 501-1000       | 2         | 5.41%   |
| Unknown        | 2         | 5.41%   |
| More than 3000 | 1         | 2.7%    |
| 251-500        | 1         | 2.7%    |
| 1001-2000      | 1         | 2.7%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-22ZAT0 500GB                         | 1         | 1      | 14.29%  |
| WDC WD5000AVVS-63ZWB0 500GB                         | 1         | 1      | 14.29%  |
| WDC WD3200BPVT-75ZEST0 320GB                        | 1         | 1      | 14.29%  |
| WDC WD1600AAJS-08L7A0 160GB                         | 1         | 1      | 14.29%  |
| Seagate ST9500325AS 500GB                           | 1         | 1      | 14.29%  |
| Seagate ST9250315AS 250GB                           | 1         | 1      | 14.29%  |
| Micron Technology MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 1      | 14.29%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| WDC               | 4         | 4      | 57.14%  |
| Seagate           | 2         | 2      | 28.57%  |
| Micron Technology | 1         | 1      | 14.29%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 4         | 4      | 66.67%  |
| Seagate | 2         | 2      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 6         | 6      | 85.71%  |
| SSD  | 1         | 1      | 14.29%  |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 21        | 32     | 52.5%   |
| Detected | 12        | 21     | 30%     |
| Malfunc  | 7         | 7      | 17.5%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 24        | 60%     |
| AMD                      | 6         | 15%     |
| Samsung Electronics      | 3         | 7.5%    |
| Nvidia                   | 2         | 5%      |
| VIA Technologies         | 1         | 2.5%    |
| Silicon Motion           | 1         | 2.5%    |
| Marvell Technology Group | 1         | 2.5%    |
| JMicron Technology       | 1         | 2.5%    |
| ADATA Technology         | 1         | 2.5%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 4         | 7.84%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 3         | 5.88%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 3         | 5.88%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 3.92%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 2         | 3.92%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 2         | 3.92%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 2         | 3.92%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 2         | 3.92%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 3.92%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                      | 1         | 1.96%   |
| VIA VT8237A SATA 2-Port Controller                                               | 1         | 1.96%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 1         | 1.96%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 1         | 1.96%   |
| Nvidia MCP61 SATA Controller                                                     | 1         | 1.96%   |
| Nvidia MCP61 IDE                                                                 | 1         | 1.96%   |
| Nvidia MCP51 Serial ATA Controller                                               | 1         | 1.96%   |
| Nvidia MCP51 IDE                                                                 | 1         | 1.96%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                        | 1         | 1.96%   |
| JMicron JMB360 AHCI Controller                                                   | 1         | 1.96%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 1         | 1.96%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 1.96%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 1.96%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 1.96%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 1         | 1.96%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 1         | 1.96%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 1         | 1.96%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 1         | 1.96%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 1.96%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 1.96%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1         | 1.96%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 1         | 1.96%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 1         | 1.96%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 1         | 1.96%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 1         | 1.96%   |
| AMD X370 Series Chipset SATA Controller                                          | 1         | 1.96%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 1         | 1.96%   |
| AMD 400 Series Chipset SATA Controller                                           | 1         | 1.96%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 1         | 1.96%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 24        | 57.14%  |
| IDE  | 13        | 30.95%  |
| NVMe | 5         | 11.9%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 27        | 75%     |
| AMD    | 9         | 25%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Atom CPU N270 @ 1.60GHz                 | 2         | 5.56%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz        | 1         | 2.78%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz   | 1         | 2.78%   |
| Intel Pentium CPU B950 @ 2.10GHz              | 1         | 2.78%   |
| Intel Genuine CPU T2400 @ 1.83GHz             | 1         | 2.78%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 1         | 2.78%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 1         | 2.78%   |
| Intel Core i7-3612QM CPU @ 2.10GHz            | 1         | 2.78%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 2.78%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 1         | 2.78%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 1         | 2.78%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 2.78%   |
| Intel Core i5-10400 CPU @ 2.90GHz             | 1         | 2.78%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 2.78%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 1         | 2.78%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 1         | 2.78%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 1         | 2.78%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 1         | 2.78%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 1         | 2.78%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz          | 1         | 2.78%   |
| Intel Core 2 CPU T5600 @ 1.83GHz              | 1         | 2.78%   |
| Intel Celeron CPU N3160 @ 1.60GHz             | 1         | 2.78%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 1         | 2.78%   |
| Intel Celeron CPU 900 @ 2.20GHz               | 1         | 2.78%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 1         | 2.78%   |
| Intel Atom CPU N280 @ 1.66GHz                 | 1         | 2.78%   |
| AMD Turion 64 X2 Mobile Technology TL-64      | 1         | 2.78%   |
| AMD Sempron 145 Processor                     | 1         | 2.78%   |
| AMD Ryzen 7 1800X Eight-Core Processor        | 1         | 2.78%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 2.78%   |
| AMD Ryzen 3 3100 4-Core Processor             | 1         | 2.78%   |
| AMD PRO A8-8600B R6, 10 Compute Cores 4C+6G   | 1         | 2.78%   |
| AMD C-50 Processor                            | 1         | 2.78%   |
| AMD Athlon II X2 B22 Processor                | 1         | 2.78%   |
| AMD A6-7480 Radeon R5, 8 Compute Cores 2C+6G  | 1         | 2.78%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 7         | 19.44%  |
| Intel Atom              | 4         | 11.11%  |
| Intel Core i7           | 3         | 8.33%   |
| Intel Core 2 Duo        | 3         | 8.33%   |
| Intel Celeron           | 3         | 8.33%   |
| Intel Pentium Gold      | 1         | 2.78%   |
| Intel Pentium Dual-Core | 1         | 2.78%   |
| Intel Pentium           | 1         | 2.78%   |
| Intel Genuine           | 1         | 2.78%   |
| Intel Core i3           | 1         | 2.78%   |
| Intel Core 2 Quad       | 1         | 2.78%   |
| Intel Core 2            | 1         | 2.78%   |
| AMD Turion 64 X2 Mobile | 1         | 2.78%   |
| AMD Sempron             | 1         | 2.78%   |
| AMD Ryzen 7             | 1         | 2.78%   |
| AMD Ryzen 5             | 1         | 2.78%   |
| AMD Ryzen 3             | 1         | 2.78%   |
| AMD PRO A8              | 1         | 2.78%   |
| AMD C-50                | 1         | 2.78%   |
| AMD Athlon II X2        | 1         | 2.78%   |
| AMD A6                  | 1         | 2.78%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 17        | 47.22%  |
| 4      | 11        | 30.56%  |
| 1      | 6         | 16.67%  |
| 8      | 1         | 2.78%   |
| 6      | 1         | 2.78%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 36        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 19        | 52.78%  |
| 2      | 17        | 47.22%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 32        | 88.89%  |
| 32-bit         | 4         | 11.11%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 7         | 19.44%  |
| 0x406c4    | 2         | 5.56%   |
| 0x306a9    | 2         | 5.56%   |
| 0x206a7    | 2         | 5.56%   |
| 0x20655    | 2         | 5.56%   |
| 0x106c2    | 2         | 5.56%   |
| 0x1067a    | 2         | 5.56%   |
| 0x0600611a | 2         | 5.56%   |
| 0xa0653    | 1         | 2.78%   |
| 0x806ec    | 1         | 2.78%   |
| 0x806ea    | 1         | 2.78%   |
| 0x6fd      | 1         | 2.78%   |
| 0x6fb      | 1         | 2.78%   |
| 0x6f2      | 1         | 2.78%   |
| 0x506e3    | 1         | 2.78%   |
| 0x406c3    | 1         | 2.78%   |
| 0x40651    | 1         | 2.78%   |
| 0x306c3    | 1         | 2.78%   |
| 0x08701021 | 1         | 2.78%   |
| 0x08108109 | 1         | 2.78%   |
| 0x08001138 | 1         | 2.78%   |
| 0x05000029 | 1         | 2.78%   |
| 0x010000c8 | 1         | 2.78%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Core        | 4         | 11.11%  |
| Silvermont  | 3         | 8.33%   |
| Penryn      | 3         | 8.33%   |
| KabyLake    | 3         | 8.33%   |
| Bonnell     | 3         | 8.33%   |
| Westmere    | 2         | 5.56%   |
| SandyBridge | 2         | 5.56%   |
| K10         | 2         | 5.56%   |
| IvyBridge   | 2         | 5.56%   |
| Haswell     | 2         | 5.56%   |
| Excavator   | 2         | 5.56%   |
| Zen+        | 1         | 2.78%   |
| Zen 2       | 1         | 2.78%   |
| Zen         | 1         | 2.78%   |
| Skylake     | 1         | 2.78%   |
| P6          | 1         | 2.78%   |
| K8 Hammer   | 1         | 2.78%   |
| CometLake   | 1         | 2.78%   |
| Bobcat      | 1         | 2.78%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Intel            | 22        | 57.89%  |
| AMD              | 10        | 26.32%  |
| Nvidia           | 5         | 13.16%  |
| VIA Technologies | 1         | 2.63%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 4         | 9.3%    |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 3         | 6.98%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 6.98%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 4.65%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 4.65%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 4.65%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 1         | 2.33%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 2.33%   |
| Nvidia GK104GLM [Quadro K3000M]                                                          | 1         | 2.33%   |
| Nvidia GF108M [GeForce GT 420M]                                                          | 1         | 2.33%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 1         | 2.33%   |
| Nvidia C51 [GeForce Go 6150]                                                             | 1         | 2.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1         | 2.33%   |
| Intel UHD Graphics 620                                                                   | 1         | 2.33%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 2.33%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 2.33%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 2.33%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 2.33%   |
| Intel HD Graphics 530                                                                    | 1         | 2.33%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 2.33%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 2.33%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 2.33%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1         | 2.33%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                                | 1         | 2.33%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1         | 2.33%   |
| AMD Wrestler [Radeon HD 6250]                                                            | 1         | 2.33%   |
| AMD RV515/M54 [Mobility Radeon X1400]                                                    | 1         | 2.33%   |
| AMD RS880 [Radeon HD 4200]                                                               | 1         | 2.33%   |
| AMD Redwood LE [Radeon HD 5550/5570/5630/6390/6490/7570]                                 | 1         | 2.33%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1         | 2.33%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 1         | 2.33%   |
| AMD Barts PRO [Radeon HD 6850]                                                           | 1         | 2.33%   |
| AMD Barts LE [Radeon HD 6790]                                                            | 1         | 2.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 21        | 58.33%  |
| 1 x AMD        | 9         | 25%     |
| 1 x Nvidia     | 4         | 11.11%  |
| 1 x VIA        | 1         | 2.78%   |
| Intel + Nvidia | 1         | 2.78%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 32        | 88.89%  |
| Proprietary | 2         | 5.56%   |
| Unknown     | 2         | 5.56%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 26        | 72.22%  |
| 0.01-0.5   | 4         | 11.11%  |
| 1.01-2.0   | 2         | 5.56%   |
| 0.51-1.0   | 2         | 5.56%   |
| 7.01-8.0   | 1         | 2.78%   |
| 3.01-4.0   | 1         | 2.78%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| LG Display          | 5         | 13.89%  |
| Samsung Electronics | 4         | 11.11%  |
| Goldstar            | 3         | 8.33%   |
| AU Optronics        | 3         | 8.33%   |
| Lenovo              | 2         | 5.56%   |
| Dell                | 2         | 5.56%   |
| CPT                 | 2         | 5.56%   |
| Chimei Innolux      | 2         | 5.56%   |
| BenQ                | 2         | 5.56%   |
| AOC                 | 2         | 5.56%   |
| Unknown             | 1         | 2.78%   |
| LG Philips          | 1         | 2.78%   |
| JCH                 | 1         | 2.78%   |
| Insignia            | 1         | 2.78%   |
| Hitachi             | 1         | 2.78%   |
| HannStar            | 1         | 2.78%   |
| BOE                 | 1         | 2.78%   |
| Apple               | 1         | 2.78%   |
| Acer                | 1         | 2.78%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch            | 1         | 2.63%   |
| Samsung Electronics SyncMaster SAM0581 1920x1080 477x268mm 21.5-inch | 1         | 2.63%   |
| Samsung Electronics S22C450 SAM09C5 1920x1080 477x268mm 21.5-inch    | 1         | 2.63%   |
| Samsung Electronics LCD Monitor SEC4141 1366x768 344x193mm 15.5-inch | 1         | 2.63%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 1         | 2.63%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch          | 1         | 2.63%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch        | 1         | 2.63%   |
| LG Display LCD Monitor LGD059E 1920x1080 382x215mm 17.3-inch         | 1         | 2.63%   |
| LG Display LCD Monitor LGD02E1 1600x900 382x215mm 17.3-inch          | 1         | 2.63%   |
| LG Display LCD Monitor LGD0266 1366x768 344x194mm 15.5-inch          | 1         | 2.63%   |
| LG Display LCD Monitor LGD01C5 1366x768 293x165mm 13.2-inch          | 1         | 2.63%   |
| Lenovo LCD Monitor LEN4033 1440x900 303x190mm 14.1-inch              | 1         | 2.63%   |
| Lenovo LCD Monitor LEN4022 1400x1050 287x215mm 14.1-inch             | 1         | 2.63%   |
| JCH F24 JCH1919 1920x1080 520x310mm 23.8-inch                        | 1         | 2.63%   |
| Insignia NS-32D312NA15 BBY0032 1680x1050 640x384mm 29.4-inch         | 1         | 2.63%   |
| Hitachi HDMI    HEC0088 1920x1080 1100x560mm 48.6-inch               | 1         | 2.63%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch             | 1         | 2.63%   |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                  | 1         | 2.63%   |
| Goldstar T710SH GSM436B 1280x960 310x230mm 15.2-inch                 | 1         | 2.63%   |
| Goldstar L1953H GSM4B3D 1280x1024 338x270mm 17.0-inch                | 1         | 2.63%   |
| Goldstar 23MP55 GSM5A23 1920x1080 510x290mm 23.1-inch                | 1         | 2.63%   |
| Dell LCD Monitor S2715H 3840x1080                                    | 1         | 2.63%   |
| Dell LCD Monitor S2715H                                              | 1         | 2.63%   |
| Dell E176FP DELA014 1280x1024 338x270mm 17.0-inch                    | 1         | 2.63%   |
| CPT LCD Monitor CPT04CE 1024x600 222x130mm 10.1-inch                 | 1         | 2.63%   |
| CPT LCD Monitor CPT04C4 1024x600 222x130mm 10.1-inch                 | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch     | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN1484 1600x900 310x174mm 14.0-inch      | 1         | 2.63%   |
| BOE LCD Monitor BOE085E 1920x1080 344x194mm 15.5-inch                | 1         | 2.63%   |
| BenQ FP202W BNQ76C2 1680x1050 376x301mm 19.0-inch                    | 1         | 2.63%   |
| BenQ E900HD BNQ7910 1366x768 410x230mm 18.5-inch                     | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch       | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch        | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch       | 1         | 2.63%   |
| Apple Color LCD APP9C5E 1280x800 286x178mm 13.3-inch                 | 1         | 2.63%   |
| AOC LM729 AOCA784 1280x1024 340x270mm 17.1-inch                      | 1         | 2.63%   |
| AOC 2450W AOC2450 1920x1080 521x293mm 23.5-inch                      | 1         | 2.63%   |
| Acer S232HL ACR0203 1920x1080 510x290mm 23.1-inch                    | 1         | 2.63%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 12        | 31.58%  |
| 1366x768 (WXGA)    | 5         | 13.16%  |
| 1600x900 (HD+)     | 4         | 10.53%  |
| 1280x1024 (SXGA)   | 3         | 7.89%   |
| 1024x600           | 3         | 7.89%   |
| 1920x540           | 2         | 5.26%   |
| 1440x900 (WXGA+)   | 2         | 5.26%   |
| 3840x1080          | 1         | 2.63%   |
| 2288x1287          | 1         | 2.63%   |
| 1680x1050 (WSXGA+) | 1         | 2.63%   |
| 1400x1050          | 1         | 2.63%   |
| 1280x960           | 1         | 2.63%   |
| 1280x800 (WXGA)    | 1         | 2.63%   |
| Unknown            | 1         | 2.63%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 17      | 9         | 24.32%  |
| 23      | 5         | 13.51%  |
| 15      | 5         | 13.51%  |
| 14      | 3         | 8.11%   |
| 10      | 3         | 8.11%   |
| 48      | 2         | 5.41%   |
| 21      | 2         | 5.41%   |
| 13      | 2         | 5.41%   |
| 142     | 1         | 2.7%    |
| 20      | 1         | 2.7%    |
| 19      | 1         | 2.7%    |
| 18      | 1         | 2.7%    |
| 16      | 1         | 2.7%    |
| Unknown | 1         | 2.7%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 11        | 29.73%  |
| 351-400        | 7         | 18.92%  |
| 201-300        | 6         | 16.22%  |
| 501-600        | 5         | 13.51%  |
| 401-500        | 4         | 10.81%  |
| 1001-1500      | 2         | 5.41%   |
| More than 2000 | 1         | 2.7%    |
| Unknown        | 1         | 2.7%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 24        | 64.86%  |
| 5/4     | 4         | 10.81%  |
| 16/10   | 3         | 8.11%   |
| 4/3     | 2         | 5.41%   |
| 1.96    | 2         | 5.41%   |
| 1.00    | 1         | 2.7%    |
| Unknown | 1         | 2.7%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 121-130        | 6         | 16.22%  |
| 201-250        | 5         | 13.51%  |
| 101-110        | 5         | 13.51%  |
| 151-200        | 4         | 10.81%  |
| 141-150        | 4         | 10.81%  |
| 41-50          | 3         | 8.11%   |
| 81-90          | 2         | 5.41%   |
| 71-80          | 2         | 5.41%   |
| 501-1000       | 2         | 5.41%   |
| More than 1000 | 1         | 2.7%    |
| 131-140        | 1         | 2.7%    |
| 91-100         | 1         | 2.7%    |
| Unknown        | 1         | 2.7%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 13        | 36.11%  |
| 51-100  | 11        | 30.56%  |
| 121-160 | 8         | 22.22%  |
| 1-50    | 3         | 8.33%   |
| Unknown | 1         | 2.78%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 33        | 91.67%  |
| 2     | 3         | 8.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 14        | 26.42%  |
| Intel                    | 13        | 24.53%  |
| Qualcomm Atheros         | 9         | 16.98%  |
| Broadcom Limited         | 4         | 7.55%   |
| TP-Link                  | 2         | 3.77%   |
| Ralink Technology        | 2         | 3.77%   |
| Nvidia                   | 2         | 3.77%   |
| Marvell Technology Group | 2         | 3.77%   |
| Broadcom                 | 2         | 3.77%   |
| VIA Technologies         | 1         | 1.89%   |
| Ralink                   | 1         | 1.89%   |
| D-Link System            | 1         | 1.89%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                       | Computers | Percent |
|---------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                           | 10        | 16.13%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                       | 4         | 6.45%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                              | 2         | 3.23%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                              | 2         | 3.23%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                     | 2         | 3.23%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                       | 2         | 3.23%   |
| VIA VT6102/VT6103 [Rhine-II]                                                                | 1         | 1.61%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                         | 1         | 1.61%   |
| TP-Link 802.11ac WLAN Adapter                                                               | 1         | 1.61%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                    | 1         | 1.61%   |
| Ralink RT5370 Wireless Adapter                                                              | 1         | 1.61%   |
| Ralink RT3072 Wireless Adapter                                                              | 1         | 1.61%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                   | 1         | 1.61%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                  | 1         | 1.61%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                                   | 1         | 1.61%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                              | 1         | 1.61%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                                       | 1         | 1.61%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]               | 1         | 1.61%   |
| Nvidia MCP61 Ethernet                                                                       | 1         | 1.61%   |
| Nvidia MCP51 Ethernet Controller                                                            | 1         | 1.61%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                                     | 1         | 1.61%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                                        | 1         | 1.61%   |
| Intel Wireless 8260                                                                         | 1         | 1.61%   |
| Intel Wireless 7265                                                                         | 1         | 1.61%   |
| Intel Wireless 7260                                                                         | 1         | 1.61%   |
| Intel Wireless 3165                                                                         | 1         | 1.61%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                               | 1         | 1.61%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                       | 1         | 1.61%   |
| Intel I211 Gigabit Network Connection                                                       | 1         | 1.61%   |
| Intel Ethernet Connection I218-LM                                                           | 1         | 1.61%   |
| Intel Ethernet Connection (2) I219-LM                                                       | 1         | 1.61%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                           | 1         | 1.61%   |
| Intel Centrino Wireless-N 2230                                                              | 1         | 1.61%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                                | 1         | 1.61%   |
| Intel Centrino Ultimate-N 6300                                                              | 1         | 1.61%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                | 1         | 1.61%   |
| Intel 82573L Gigabit Ethernet Controller                                                    | 1         | 1.61%   |
| Intel 82566MM Gigabit Network Connection                                                    | 1         | 1.61%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                                        | 1         | 1.61%   |
| D-Link System DWA-160 802.11abgn Xtreme N Dual Band Adapter(rev.A2) [Atheros AR9170+AR9104] | 1         | 1.61%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                                            | 1         | 1.61%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                             | 1         | 1.61%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe                                    | 1         | 1.61%   |
| Broadcom Limited NetLink BCM57788 Gigabit Ethernet PCIe                                     | 1         | 1.61%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter                                 | 1         | 1.61%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                                   | 1         | 1.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 11        | 40.74%  |
| Qualcomm Atheros      | 7         | 25.93%  |
| TP-Link               | 2         | 7.41%   |
| Ralink Technology     | 2         | 7.41%   |
| Broadcom Limited      | 2         | 7.41%   |
| Realtek Semiconductor | 1         | 3.7%    |
| Ralink                | 1         | 3.7%    |
| D-Link System         | 1         | 3.7%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                       | Computers | Percent |
|---------------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                              | 2         | 7.41%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                     | 2         | 7.41%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                         | 1         | 3.7%    |
| TP-Link 802.11ac WLAN Adapter                                                               | 1         | 3.7%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                    | 1         | 3.7%    |
| Ralink RT5370 Wireless Adapter                                                              | 1         | 3.7%    |
| Ralink RT3072 Wireless Adapter                                                              | 1         | 3.7%    |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                   | 1         | 3.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                  | 1         | 3.7%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                              | 1         | 3.7%    |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]               | 1         | 3.7%    |
| Intel Wireless 8260                                                                         | 1         | 3.7%    |
| Intel Wireless 7265                                                                         | 1         | 3.7%    |
| Intel Wireless 7260                                                                         | 1         | 3.7%    |
| Intel Wireless 3165                                                                         | 1         | 3.7%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                               | 1         | 3.7%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                       | 1         | 3.7%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                                           | 1         | 3.7%    |
| Intel Centrino Wireless-N 2230                                                              | 1         | 3.7%    |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                                | 1         | 3.7%    |
| Intel Centrino Ultimate-N 6300                                                              | 1         | 3.7%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                | 1         | 3.7%    |
| D-Link System DWA-160 802.11abgn Xtreme N Dual Band Adapter(rev.A2) [Atheros AR9170+AR9104] | 1         | 3.7%    |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter                                 | 1         | 3.7%    |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                                   | 1         | 3.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 14        | 40%     |
| Intel                    | 8         | 22.86%  |
| Qualcomm Atheros         | 4         | 11.43%  |
| Nvidia                   | 2         | 5.71%   |
| Marvell Technology Group | 2         | 5.71%   |
| Broadcom Limited         | 2         | 5.71%   |
| Broadcom                 | 2         | 5.71%   |
| VIA Technologies         | 1         | 2.86%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 10        | 28.57%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 11.43%  |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 5.71%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 5.71%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 2.86%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 2.86%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 2.86%   |
| Nvidia MCP61 Ethernet                                             | 1         | 2.86%   |
| Nvidia MCP51 Ethernet Controller                                  | 1         | 2.86%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 2.86%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 2.86%   |
| Intel I211 Gigabit Network Connection                             | 1         | 2.86%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 2.86%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 2.86%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 2.86%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 2.86%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 1         | 2.86%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1         | 2.86%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 2.86%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1         | 2.86%   |
| Broadcom Limited NetLink BCM57788 Gigabit Ethernet PCIe           | 1         | 2.86%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 34        | 56.67%  |
| WiFi     | 26        | 43.33%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 22        | 51.16%  |
| WiFi     | 21        | 48.84%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 21        | 58.33%  |
| 1     | 15        | 41.67%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 33        | 89.19%  |
| Yes  | 4         | 10.81%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 6         | 42.86%  |
| Broadcom                        | 3         | 21.43%  |
| Realtek Semiconductor           | 1         | 7.14%   |
| Qualcomm Atheros Communications | 1         | 7.14%   |
| Dell                            | 1         | 7.14%   |
| ASUSTek Computer                | 1         | 7.14%   |
| Apple                           | 1         | 7.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface               | 3         | 21.43%  |
| Realtek  Bluetooth 4.2 Adapter                   | 1         | 7.14%   |
| Qualcomm Atheros  Bluetooth Device               | 1         | 7.14%   |
| Intel Centrino Bluetooth Wireless Transceiver    | 1         | 7.14%   |
| Intel Bluetooth Device                           | 1         | 7.14%   |
| Intel AX201 Bluetooth                            | 1         | 7.14%   |
| Dell Wireless 365 Bluetooth                      | 1         | 7.14%   |
| Broadcom HP Portable SoftSailing                 | 1         | 7.14%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller] | 1         | 7.14%   |
| Broadcom BCM2045 Bluetooth                       | 1         | 7.14%   |
| ASUS Broadcom Bluetooth 2.1                      | 1         | 7.14%   |
| Apple Bluetooth HCI                              | 1         | 7.14%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Intel            | 25        | 60.98%  |
| AMD              | 9         | 21.95%  |
| Nvidia           | 5         | 12.2%   |
| VIA Technologies | 1         | 2.44%   |
| Plantronics      | 1         | 2.44%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7         | 14.29%  |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 4.08%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 2         | 4.08%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 4.08%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 4.08%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 4.08%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 4.08%   |
| AMD Barts HDMI Audio [Radeon HD 6790/6850/6870 / 7720 OEM]                                        | 2         | 4.08%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1         | 2.04%   |
| Plantronics USB DSP v4 Audio Interface                                                            | 1         | 2.04%   |
| Nvidia MCP61 High Definition Audio                                                                | 1         | 2.04%   |
| Nvidia MCP51 High Definition Audio                                                                | 1         | 2.04%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 2.04%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 2.04%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 2.04%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 2.04%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 1         | 2.04%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 2.04%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 1         | 2.04%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 2.04%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 1         | 2.04%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 1         | 2.04%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 2.04%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 2.04%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 2.04%   |
| Intel 200 Series PCH HD Audio                                                                     | 1         | 2.04%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 2.04%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 2.04%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 1         | 2.04%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 1         | 2.04%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 2.04%   |
| AMD Navi 10 HDMI Audio                                                                            | 1         | 2.04%   |
| AMD FCH Azalia Controller                                                                         | 1         | 2.04%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 1         | 2.04%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 1         | 2.04%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 2.04%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 7         | 23.33%  |
| Samsung Electronics | 5         | 16.67%  |
| SK Hynix            | 3         | 10%     |
| Kingston            | 3         | 10%     |
| Nanya Technology    | 2         | 6.67%   |
| Micron Technology   | 2         | 6.67%   |
| G.Skill             | 2         | 6.67%   |
| Corsair             | 2         | 6.67%   |
| GOODRAM             | 1         | 3.33%   |
| Elpida              | 1         | 3.33%   |
| Crucial             | 1         | 3.33%   |
| Avant               | 1         | 3.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB DIMM 800MT/s                      | 2         | 6.25%   |
| Unknown RAM Module 2GB SODIMM SDRAM                         | 1         | 3.13%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                    | 1         | 3.13%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                 | 1         | 3.13%   |
| Unknown RAM Module 1024MB SODIMM DDR2                       | 1         | 3.13%   |
| Unknown RAM Module 1024MB SODIMM 800MT/s                    | 1         | 3.13%   |
| Unknown RAM Module 1024MB DIMM SDRAM                        | 1         | 3.13%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1066MT/s                | 1         | 3.13%   |
| SK Hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s     | 1         | 3.13%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s   | 1         | 3.13%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s       | 1         | 3.13%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s       | 1         | 3.13%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s       | 1         | 3.13%   |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1334MT/s       | 1         | 3.13%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s    | 1         | 3.13%   |
| Samsung RAM K4E8E324EB-EGCF 2048MB LPDDR3 1600MT/s          | 1         | 3.13%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s        | 1         | 3.13%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s        | 1         | 3.13%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s       | 1         | 3.13%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s      | 1         | 3.13%   |
| Kingston RAM Module 16GB SODIMM DDR4 2133MT/s               | 1         | 3.13%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s         | 1         | 3.13%   |
| Kingston RAM ACR128X64D3S1333C9 1024MB SODIMM DDR3 1333MT/s | 1         | 3.13%   |
| GOODRAM RAM GR1600S3V64L11/8G 8GB SODIMM DDR3 1600MT/s      | 1         | 3.13%   |
| G.Skill RAM F4-3200C16-8GIS 8192MB DIMM DDR4 3200MT/s       | 1         | 3.13%   |
| G.Skill RAM F4-2400C16-16GRS 16GB SODIMM DDR4 2667MT/s      | 1         | 3.13%   |
| Elpida RAM EBJ81UG8BAS0-DJ-F 8GB SODIMM DDR3 1333MT/s       | 1         | 3.13%   |
| Crucial RAM BLS8G3D1609DS1S00. 8192MB DIMM DDR3 1600MT/s    | 1         | 3.13%   |
| Corsair RAM CMZ4GX3M1A1600C9 4096MB DIMM DDR3 1600MT/s      | 1         | 3.13%   |
| Corsair RAM CMSA4GX3M1A1333C9 4GB SODIMM DDR3 1333MT/s      | 1         | 3.13%   |
| Avant RAM W641GU49J2320N6 8GB DIMM DDR4 2666MT/s            | 1         | 3.13%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 14        | 50%     |
| DDR4    | 5         | 17.86%  |
| SDRAM   | 3         | 10.71%  |
| Unknown | 3         | 10.71%  |
| DDR2    | 2         | 7.14%   |
| LPDDR3  | 1         | 3.57%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SODIMM  | 17        | 62.96%  |
| DIMM    | 9         | 33.33%  |
| Unknown | 1         | 3.7%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 2048  | 9         | 29.03%  |
| 8192  | 8         | 25.81%  |
| 4096  | 7         | 22.58%  |
| 1024  | 4         | 12.9%   |
| 16384 | 3         | 9.68%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 9         | 31.03%  |
| 800     | 4         | 13.79%  |
| 1333    | 3         | 10.34%  |
| Unknown | 3         | 10.34%  |
| 2667    | 2         | 6.9%    |
| 1334    | 2         | 6.9%    |
| 4199    | 1         | 3.45%   |
| 3200    | 1         | 3.45%   |
| 2666    | 1         | 3.45%   |
| 2400    | 1         | 3.45%   |
| 2133    | 1         | 3.45%   |
| 1066    | 1         | 3.45%   |

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


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 7         | 36.84%  |
| Microdia                      | 3         | 15.79%  |
| Sunplus Innovation Technology | 2         | 10.53%  |
| Logitech                      | 2         | 10.53%  |
| Z-Star Microelectronics       | 1         | 5.26%   |
| Suyin                         | 1         | 5.26%   |
| Samsung Electronics           | 1         | 5.26%   |
| Microsoft                     | 1         | 5.26%   |
| Acer                          | 1         | 5.26%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Z-Star Namuga 1.3M Webcam                                   | 1         | 5.26%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 5.26%   |
| Sunplus Integrated Webcam                                   | 1         | 5.26%   |
| Sunplus HP HD Webcam [Fixed]                                | 1         | 5.26%   |
| Samsung Galaxy A5 (MTP)                                     | 1         | 5.26%   |
| Microsoft LifeCam Cinema                                    | 1         | 5.26%   |
| Microdia Sonix USB 2.0 Camera                               | 1         | 5.26%   |
| Microdia Laptop_Integrated_Webcam_HD                        | 1         | 5.26%   |
| Microdia Laptop_Integrated_Webcam_1.3M                      | 1         | 5.26%   |
| Logitech Webcam C270                                        | 1         | 5.26%   |
| Logitech QuickCam Notebook Pro                              | 1         | 5.26%   |
| Chicony Integrated Camera (1280x720@30)                     | 1         | 5.26%   |
| Chicony HP TrueVision HD Camera                             | 1         | 5.26%   |
| Chicony HP Integrated Webcam                                | 1         | 5.26%   |
| Chicony HP HD Webcam                                        | 1         | 5.26%   |
| Chicony HD WebCam                                           | 1         | 5.26%   |
| Chicony Asus Integrated 0.3M UVC Webcam                     | 1         | 5.26%   |
| Chicony 2.0M UVC Webcam / CNF7129                           | 1         | 5.26%   |
| Acer Lenovo EasyCamera                                      | 1         | 5.26%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Validity Sensors   | 1         | 50%     |
| STMicroelectronics | 1         | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Validity Sensors VFS491               | 1         | 50%     |
| STMicroelectronics Fingerprint Reader | 1         | 50%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 27        | 75%     |
| 1     | 6         | 16.67%  |
| 2     | 3         | 8.33%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Net/wireless          | 3         | 25%     |
| Graphics card         | 3         | 25%     |
| Multimedia controller | 2         | 16.67%  |
| Fingerprint reader    | 2         | 16.67%  |
| Chipcard              | 1         | 8.33%   |
| Camera                | 1         | 8.33%   |

