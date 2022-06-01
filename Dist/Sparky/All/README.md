Sparky - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for Sparky.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Sparky/Desktop/README.md) and [notebooks](/Dist/Sparky/Notebook/README.md).

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

| Vendor    | Model                       | Form-Factor | Probe                                                      | Date         |
|-----------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP        | EliteBook 745 G3            | Notebook    | [fac15b2640](https://linux-hardware.org/?probe=fac15b2640) | May 18, 2022 |
| ASUSTek   | CROSSHAIR VI HERO           | Desktop     | [803d13c6ca](https://linux-hardware.org/?probe=803d13c6ca) | May 15, 2022 |
| HP        | EliteBook 8770w             | Notebook    | [4fa8e91f6d](https://linux-hardware.org/?probe=4fa8e91f6d) | Apr 26, 2022 |
| Lenovo    | G50-30 80G0                 | Notebook    | [c7ea70f7ba](https://linux-hardware.org/?probe=c7ea70f7ba) | Apr 25, 2022 |
| HP        | 3641h                       | Desktop     | [d50fc13ff0](https://linux-hardware.org/?probe=d50fc13ff0) | Mar 30, 2022 |
| HP        | Pavilion dv5                | Notebook    | [22ae3dae3d](https://linux-hardware.org/?probe=22ae3dae3d) | Mar 22, 2022 |
| Intel     | H55                         | Desktop     | [baff4758b7](https://linux-hardware.org/?probe=baff4758b7) | Mar 21, 2022 |
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
| HP        | Pavilion dv9000 (GA359UA... | Notebook    | [6f024c0dd0](https://linux-hardware.org/?probe=6f024c0dd0) | Sep 03, 2019 |
| ASRock    | H61M-VG4                    | Desktop     | [93ae8e7a8c](https://linux-hardware.org/?probe=93ae8e7a8c) | Aug 18, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Sparky 6    | 16        | 36.36%  |
| Sparky 6.1  | 6         | 13.64%  |
| Sparky 5.12 | 5         | 11.36%  |
| Sparky 7    | 3         | 6.82%   |
| Sparky 6.0  | 3         | 6.82%   |
| Sparky 5.14 | 3         | 6.82%   |
| Sparky 5.10 | 3         | 6.82%   |
| Sparky 6.2  | 2         | 4.55%   |
| Sparky 5.13 | 2         | 4.55%   |
| Sparky 6.3  | 1         | 2.27%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Sparky | 41        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Computers | Percent |
|---------------------|-----------|---------|
| 5.10.0-9-amd64      | 3         | 6.52%   |
| 5.10.0-8-amd64      | 3         | 6.52%   |
| 5.10.0-6-amd64      | 3         | 6.52%   |
| 5.10.0-11-686       | 3         | 6.52%   |
| 4.19.0-8-amd64      | 3         | 6.52%   |
| 4.19.0-12-amd64     | 3         | 6.52%   |
| 5.17.0-1-amd64      | 2         | 4.35%   |
| 5.10.0-3-amd64      | 2         | 4.35%   |
| 4.19.0-13-686       | 2         | 4.35%   |
| 4.19.0-10-686       | 2         | 4.35%   |
| 5.9.13-sparky-amd64 | 1         | 2.17%   |
| 5.9.0-4-amd64       | 1         | 2.17%   |
| 5.8.13-sparky-amd64 | 1         | 2.17%   |
| 5.8.0-2-amd64       | 1         | 2.17%   |
| 5.7.2-sparky-amd64  | 1         | 2.17%   |
| 5.6.0-2-amd64       | 1         | 2.17%   |
| 5.5.0-2-amd64       | 1         | 2.17%   |
| 5.4.7-sparky-amd64  | 1         | 2.17%   |
| 5.2.0-2-amd64       | 1         | 2.17%   |
| 5.17.3-sparky-amd64 | 1         | 2.17%   |
| 5.16.5-sparky-amd64 | 1         | 2.17%   |
| 5.16.0-5-amd64      | 1         | 2.17%   |
| 5.15.0-3-amd64      | 1         | 2.17%   |
| 5.14.0-4-amd64      | 1         | 2.17%   |
| 5.10.4-sparky-amd64 | 1         | 2.17%   |
| 5.10.0-7-amd64      | 1         | 2.17%   |
| 5.10.0-2-amd64      | 1         | 2.17%   |
| 5.10.0-12-amd64     | 1         | 2.17%   |
| 4.19.0-14-686       | 1         | 2.17%   |
| 4.19.0-10-amd64     | 1         | 2.17%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 17        | 38.64%  |
| 4.19.0  | 10        | 22.73%  |
| 5.17.0  | 2         | 4.55%   |
| 5.9.13  | 1         | 2.27%   |
| 5.9.0   | 1         | 2.27%   |
| 5.8.13  | 1         | 2.27%   |
| 5.8.0   | 1         | 2.27%   |
| 5.7.2   | 1         | 2.27%   |
| 5.6.0   | 1         | 2.27%   |
| 5.5.0   | 1         | 2.27%   |
| 5.4.7   | 1         | 2.27%   |
| 5.2.0   | 1         | 2.27%   |
| 5.17.3  | 1         | 2.27%   |
| 5.16.5  | 1         | 2.27%   |
| 5.16.0  | 1         | 2.27%   |
| 5.15.0  | 1         | 2.27%   |
| 5.14.0  | 1         | 2.27%   |
| 5.10.4  | 1         | 2.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 18        | 40.91%  |
| 4.19    | 10        | 22.73%  |
| 5.17    | 3         | 6.82%   |
| 5.9     | 2         | 4.55%   |
| 5.8     | 2         | 4.55%   |
| 5.16    | 2         | 4.55%   |
| 5.7     | 1         | 2.27%   |
| 5.6     | 1         | 2.27%   |
| 5.5     | 1         | 2.27%   |
| 5.4     | 1         | 2.27%   |
| 5.2     | 1         | 2.27%   |
| 5.15    | 1         | 2.27%   |
| 5.14    | 1         | 2.27%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 35        | 85.37%  |
| i686   | 6         | 14.63%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| XFCE             | 14        | 33.33%  |
| LXQt             | 12        | 28.57%  |
| Unknown          | 7         | 16.67%  |
| KDE5             | 2         | 4.76%   |
| GNOME            | 2         | 4.76%   |
| X-Cinnamon       | 1         | 2.38%   |
| openbox          | 1         | 2.38%   |
| MATE             | 1         | 2.38%   |
| lightdm-xsession | 1         | 2.38%   |
| ICEWM            | 1         | 2.38%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 39        | 92.86%  |
| Tty  | 3         | 7.14%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| TDM     | 13        | 31.71%  |
| Unknown | 12        | 29.27%  |
| SDDM    | 8         | 19.51%  |
| LightDM | 6         | 14.63%  |
| XDM     | 1         | 2.44%   |
| GDM     | 1         | 2.44%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 12        | 29.27%  |
| en_GB   | 4         | 9.76%   |
| pl_PL   | 3         | 7.32%   |
| pt_BR   | 2         | 4.88%   |
| fr_FR   | 2         | 4.88%   |
| es_ES   | 2         | 4.88%   |
| de_DE   | 2         | 4.88%   |
| Unknown | 2         | 4.88%   |
| sv_SE   | 1         | 2.44%   |
| ja_JP   | 1         | 2.44%   |
| es_US   | 1         | 2.44%   |
| es_CL   | 1         | 2.44%   |
| es_AR   | 1         | 2.44%   |
| en_ZA   | 1         | 2.44%   |
| en_PH   | 1         | 2.44%   |
| en_IN   | 1         | 2.44%   |
| en_DK   | 1         | 2.44%   |
| en_CA   | 1         | 2.44%   |
| de_CH   | 1         | 2.44%   |
| cs_CZ   | 1         | 2.44%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 28        | 68.29%  |
| EFI  | 13        | 31.71%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 37        | 90.24%  |
| Overlay | 2         | 4.88%   |
| Zfs     | 1         | 2.44%   |
| Btrfs   | 1         | 2.44%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| MBR     | 14        | 34.15%  |
| GPT     | 14        | 34.15%  |
| Unknown | 13        | 31.71%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 35        | 85.37%  |
| Yes       | 6         | 14.63%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 26        | 63.41%  |
| Yes       | 15        | 36.59%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 10        | 24.39%  |
| Lenovo              | 5         | 12.2%   |
| Dell                | 5         | 12.2%   |
| Intel               | 4         | 9.76%   |
| Gigabyte Technology | 4         | 9.76%   |
| MSI                 | 3         | 7.32%   |
| ASUSTek Computer    | 3         | 7.32%   |
| Samsung Electronics | 1         | 2.44%   |
| Google              | 1         | 2.44%   |
| eMachines           | 1         | 2.44%   |
| Beelink             | 1         | 2.44%   |
| Apple               | 1         | 2.44%   |
| Acer                | 1         | 2.44%   |
| Unknown             | 1         | 2.44%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| Samsung NC10                     | 1         | 2.44%   |
| MSI MS-7C09                      | 1         | 2.44%   |
| MSI MS-7B86                      | 1         | 2.44%   |
| MSI MS-7721                      | 1         | 2.44%   |
| Lenovo ThinkPad T61 7659AB7      | 1         | 2.44%   |
| Lenovo ThinkPad T60 2007FUG      | 1         | 2.44%   |
| Lenovo ThinkPad E15 20RES0GF00   | 1         | 2.44%   |
| Lenovo IdeaPad S206 20154        | 1         | 2.44%   |
| Lenovo G50-30 80G0               | 1         | 2.44%   |
| Intel NUC5CPYB H61145-408        | 1         | 2.44%   |
| Intel H55                        | 1         | 2.44%   |
| Intel DG43RK AAE78175-402        | 1         | 2.44%   |
| Intel DG41TY AAE47335-300        | 1         | 2.44%   |
| HP t5740                         | 1         | 2.44%   |
| HP Pavilion g7                   | 1         | 2.44%   |
| HP Pavilion dv9000 (GA359UA#ABA) | 1         | 2.44%   |
| HP Pavilion dv5                  | 1         | 2.44%   |
| HP Laptop 17z-ca100              | 1         | 2.44%   |
| HP EliteDesk 800 G2 DM 65W       | 1         | 2.44%   |
| HP EliteDesk 705 G2 MINI         | 1         | 2.44%   |
| HP EliteBook Folio 9480m         | 1         | 2.44%   |
| HP EliteBook 8770w               | 1         | 2.44%   |
| HP EliteBook 745 G3              | 1         | 2.44%   |
| Google Banon                     | 1         | 2.44%   |
| Gigabyte M68M-S2P                | 1         | 2.44%   |
| Gigabyte H97-Gaming 3            | 1         | 2.44%   |
| Gigabyte H410M H                 | 1         | 2.44%   |
| Gigabyte G41M-ES2L               | 1         | 2.44%   |
| eMachines E525                   | 1         | 2.44%   |
| Dell OptiPlex 580                | 1         | 2.44%   |
| Dell Latitude XT3                | 1         | 2.44%   |
| Dell Inspiron N5010              | 1         | 2.44%   |
| Dell Inspiron 5770               | 1         | 2.44%   |
| Dell Inspiron 5720               | 1         | 2.44%   |
| Beelink BT3 PRO                  | 1         | 2.44%   |
| ASUS S101                        | 1         | 2.44%   |
| ASUS CROSSHAIR VI HERO           | 1         | 2.44%   |
| ASUS 1000HE                      | 1         | 2.44%   |
| Apple MacBook1,1                 | 1         | 2.44%   |
| Acer Aspire 5742G                | 1         | 2.44%   |
| Unknown                          | 1         | 2.44%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 3         | 7.32%   |
| HP Pavilion         | 3         | 7.32%   |
| HP EliteBook        | 3         | 7.32%   |
| Dell Inspiron       | 3         | 7.32%   |
| HP EliteDesk        | 2         | 4.88%   |
| Samsung NC10        | 1         | 2.44%   |
| MSI MS-7C09         | 1         | 2.44%   |
| MSI MS-7B86         | 1         | 2.44%   |
| MSI MS-7721         | 1         | 2.44%   |
| Lenovo IdeaPad      | 1         | 2.44%   |
| Lenovo G50-30       | 1         | 2.44%   |
| Intel NUC5CPYB      | 1         | 2.44%   |
| Intel H55           | 1         | 2.44%   |
| Intel DG43RK        | 1         | 2.44%   |
| Intel DG41TY        | 1         | 2.44%   |
| HP t5740            | 1         | 2.44%   |
| HP Laptop           | 1         | 2.44%   |
| Google Banon        | 1         | 2.44%   |
| Gigabyte M68M-S2P   | 1         | 2.44%   |
| Gigabyte H97-Gaming | 1         | 2.44%   |
| Gigabyte H410M      | 1         | 2.44%   |
| Gigabyte G41M-ES2L  | 1         | 2.44%   |
| eMachines E525      | 1         | 2.44%   |
| Dell OptiPlex       | 1         | 2.44%   |
| Dell Latitude       | 1         | 2.44%   |
| Beelink BT3         | 1         | 2.44%   |
| ASUS S101           | 1         | 2.44%   |
| ASUS CROSSHAIR      | 1         | 2.44%   |
| ASUS 1000HE         | 1         | 2.44%   |
| Apple MacBook1      | 1         | 2.44%   |
| Acer Aspire         | 1         | 2.44%   |
| Unknown             | 1         | 2.44%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2009 | 7         | 17.07%  |
| 2014 | 4         | 9.76%   |
| 2012 | 4         | 9.76%   |
| 2018 | 3         | 7.32%   |
| 2010 | 3         | 7.32%   |
| 2008 | 3         | 7.32%   |
| 2021 | 2         | 4.88%   |
| 2020 | 2         | 4.88%   |
| 2019 | 2         | 4.88%   |
| 2016 | 2         | 4.88%   |
| 2015 | 2         | 4.88%   |
| 2011 | 2         | 4.88%   |
| 2007 | 2         | 4.88%   |
| 2006 | 2         | 4.88%   |
| 2017 | 1         | 2.44%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Notebook | 24        | 58.54%  |
| Desktop  | 16        | 39.02%  |
| Mini pc  | 1         | 2.44%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 41        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 40        | 97.56%  |
| Yes  | 1         | 2.44%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 13        | 31.71%  |
| 4.01-8.0   | 8         | 19.51%  |
| 2.01-3.0   | 5         | 12.2%   |
| 16.01-24.0 | 5         | 12.2%   |
| 1.01-2.0   | 4         | 9.76%   |
| 24.01-32.0 | 2         | 4.88%   |
| 8.01-16.0  | 2         | 4.88%   |
| 32.01-64.0 | 1         | 2.44%   |
| 0.51-1.0   | 1         | 2.44%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 18        | 40.91%  |
| 0.51-1.0 | 10        | 22.73%  |
| 2.01-3.0 | 7         | 15.91%  |
| 4.01-8.0 | 5         | 11.36%  |
| 3.01-4.0 | 2         | 4.55%   |
| 0.01-0.5 | 2         | 4.55%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 30        | 71.43%  |
| 2      | 7         | 16.67%  |
| 4      | 3         | 7.14%   |
| 5      | 1         | 2.38%   |
| 3      | 1         | 2.38%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 25        | 60.98%  |
| Yes       | 16        | 39.02%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 38        | 92.68%  |
| No        | 3         | 7.32%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 29        | 70.73%  |
| No        | 12        | 29.27%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 23        | 56.1%   |
| Yes       | 18        | 43.9%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 8         | 19.51%  |
| UK           | 4         | 9.76%   |
| Germany      | 4         | 9.76%   |
| Poland       | 3         | 7.32%   |
| France       | 3         | 7.32%   |
| Indonesia    | 2         | 4.88%   |
| Canada       | 2         | 4.88%   |
| Brazil       | 2         | 4.88%   |
| Argentina    | 2         | 4.88%   |
| Venezuela    | 1         | 2.44%   |
| Switzerland  | 1         | 2.44%   |
| Sweden       | 1         | 2.44%   |
| Spain        | 1         | 2.44%   |
| South Africa | 1         | 2.44%   |
| Philippines  | 1         | 2.44%   |
| Lebanon      | 1         | 2.44%   |
| Japan        | 1         | 2.44%   |
| India        | 1         | 2.44%   |
| Czechia      | 1         | 2.44%   |
| Chile        | 1         | 2.44%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Woking           | 1         | 2.27%   |
| Wenatchee        | 1         | 2.27%   |
| Tucson           | 1         | 2.27%   |
| Takahama         | 1         | 2.27%   |
| Surabaya         | 1         | 2.27%   |
| Spokane          | 1         | 2.27%   |
| Sin el Fil       | 1         | 2.27%   |
| San Cristóbal   | 1         | 2.27%   |
| San Antonio      | 1         | 2.27%   |
| Sainte-Julie     | 1         | 2.27%   |
| Rosario          | 1         | 2.27%   |
| Rio Claro        | 1         | 2.27%   |
| Quezon City      | 1         | 2.27%   |
| Pujaudran        | 1         | 2.27%   |
| Puente Alto      | 1         | 2.27%   |
| Posadas          | 1         | 2.27%   |
| Pompano Beach    | 1         | 2.27%   |
| Montreuil        | 1         | 2.27%   |
| Montreal         | 1         | 2.27%   |
| Mnisek pod Brdy  | 1         | 2.27%   |
| Miekoszyn        | 1         | 2.27%   |
| Mannheim         | 1         | 2.27%   |
| Liverpool        | 1         | 2.27%   |
| Lienen           | 1         | 2.27%   |
| Leipzig          | 1         | 2.27%   |
| Koło            | 1         | 2.27%   |
| Kage             | 1         | 2.27%   |
| Houston          | 1         | 2.27%   |
| Grabs            | 1         | 2.27%   |
| Gmina Bolków    | 1         | 2.27%   |
| Glasgow          | 1         | 2.27%   |
| Fuveau           | 1         | 2.27%   |
| Frankfurt (Oder) | 1         | 2.27%   |
| East Wenatchee   | 1         | 2.27%   |
| Duque de Caxias  | 1         | 2.27%   |
| Dunoon           | 1         | 2.27%   |
| Dobrzen Wielki   | 1         | 2.27%   |
| Dehradun         | 1         | 2.27%   |
| Chicago          | 1         | 2.27%   |
| Cape Town        | 1         | 2.27%   |
| Calanda          | 1         | 2.27%   |
| Birmingham       | 1         | 2.27%   |
| Barnsley         | 1         | 2.27%   |
| Bandung          | 1         | 2.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 15     | 18.18%  |
| WDC                 | 9         | 11     | 16.36%  |
| Samsung Electronics | 9         | 15     | 16.36%  |
| Hitachi             | 5         | 6      | 9.09%   |
| Kingston            | 3         | 3      | 5.45%   |
| Unknown             | 2         | 2      | 3.64%   |
| Intel               | 2         | 2      | 3.64%   |
| GOODRAM             | 2         | 4      | 3.64%   |
| XPG                 | 1         | 1      | 1.82%   |
| SPCC                | 1         | 2      | 1.82%   |
| SanDisk             | 1         | 1      | 1.82%   |
| ORICO               | 1         | 1      | 1.82%   |
| Netac               | 1         | 1      | 1.82%   |
| Micron Technology   | 1         | 1      | 1.82%   |
| HGST                | 1         | 1      | 1.82%   |
| Gigabyte Technology | 1         | 1      | 1.82%   |
| Fujitsu             | 1         | 2      | 1.82%   |
| Crucial             | 1         | 1      | 1.82%   |
| ASUS-JM             | 1         | 1      | 1.82%   |
| asmedia             | 1         | 1      | 1.82%   |
| A-DATA Technology   | 1         | 1      | 1.82%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| WDC WD1600BEVT-22ZCT0 160GB              | 2         | 3.28%   |
| Samsung HD161GJ 160GB                    | 2         | 3.28%   |
| Hitachi HTS545025B9A300 250GB            | 2         | 3.28%   |
| XPG GAMMIX S11 Pro 256GB                 | 1         | 1.64%   |
| WDC WD800JD-08MSA1 80GB                  | 1         | 1.64%   |
| WDC WD5000BEVT-22ZAT0 500GB              | 1         | 1.64%   |
| WDC WD5000AVVS-63ZWB0 500GB              | 1         | 1.64%   |
| WDC WD3200BPVT-75ZEST0 320GB             | 1         | 1.64%   |
| WDC WD2500AAKX-07U6AA0 250GB             | 1         | 1.64%   |
| WDC WD1600AAJS-08L7A0 160GB              | 1         | 1.64%   |
| WDC WD10EZEX-60WN4A0 1TB                 | 1         | 1.64%   |
| Unknown MMC Card  64GB                   | 1         | 1.64%   |
| Unknown HBG4a2  32GB                     | 1         | 1.64%   |
| SPCC Solid State Disk 256GB              | 1         | 1.64%   |
| Seagate ST9500325AS 500GB                | 1         | 1.64%   |
| Seagate ST9250315AS 250GB                | 1         | 1.64%   |
| Seagate ST9160310AS 160GB                | 1         | 1.64%   |
| Seagate ST500LT012-1DG142 500GB          | 1         | 1.64%   |
| Seagate ST3500312CS 500GB                | 1         | 1.64%   |
| Seagate ST3320418AS 320GB                | 1         | 1.64%   |
| Seagate ST2000VM003-1ET164 2TB           | 1         | 1.64%   |
| Seagate ST1000LM048-2E7172 1TB           | 1         | 1.64%   |
| Seagate ST1000LM035-1RK172 1TB           | 1         | 1.64%   |
| Seagate ST1000LM024 HN-M101MBB 1TB       | 1         | 1.64%   |
| Seagate Backup+ Hub BK 8TB               | 1         | 1.64%   |
| Seagate Backup+ Desk 5TB                 | 1         | 1.64%   |
| SanDisk SSD PLUS 480GB                   | 1         | 1.64%   |
| Samsung SSD 850 EVO 500GB                | 1         | 1.64%   |
| Samsung SSD 850 EVO 250GB                | 1         | 1.64%   |
| Samsung SSD 840 Series 120GB             | 1         | 1.64%   |
| Samsung NVMe SSD Drive 256GB             | 1         | 1.64%   |
| Samsung MZVPV256HDGL-000H1 256GB         | 1         | 1.64%   |
| Samsung MZALQ512HALU-000L1 512GB         | 1         | 1.64%   |
| Samsung MZ7TD128HAFV-000L1 128GB SSD     | 1         | 1.64%   |
| Samsung HN-M320MBB 320GB                 | 1         | 1.64%   |
| Samsung HD753LJ 752GB                    | 1         | 1.64%   |
| Samsung HD154UI 1TB                      | 1         | 1.64%   |
| ORICO M200 1TB                           | 1         | 1.64%   |
| Netac SSD 256GB                          | 1         | 1.64%   |
| Micron MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 1.64%   |
| Kingston SV300S37A480G 480GB SSD         | 1         | 1.64%   |
| Kingston SA400S37120G 120GB SSD          | 1         | 1.64%   |
| Kingston SA400M8240G 240GB SSD           | 1         | 1.64%   |
| Intel SSDSA2BW120G3H 120GB               | 1         | 1.64%   |
| Intel SSDMAEXC024G3H 24GB                | 1         | 1.64%   |
| Hitachi HTS545025B9SA02 250GB            | 1         | 1.64%   |
| Hitachi HTS543232A7A384 320GB            | 1         | 1.64%   |
| Hitachi HTS541080G9SA00 80GB             | 1         | 1.64%   |
| HGST HTS545050A7E380 500GB               | 1         | 1.64%   |
| GOODRAM SSDPR-CX400-256-G2 256GB         | 1         | 1.64%   |
| GOODRAM SSDPR-CL100-240-G3 240GB         | 1         | 1.64%   |
| GOODRAM IR-SSDPR-S25A-120 120GB          | 1         | 1.64%   |
| Gigabyte GP-GSTFS31120GNTD 120GB         | 1         | 1.64%   |
| Fujitsu MHW2120BH 120GB                  | 1         | 1.64%   |
| Crucial CT250MX500SSD1 250GB             | 1         | 1.64%   |
| ASUS-JM S41 SSD 16GB                     | 1         | 1.64%   |
| asmedia ASMT1153e 1TB                    | 1         | 1.64%   |
| A-DATA SX8200NP 480GB                    | 1         | 1.64%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 14     | 33.33%  |
| WDC                 | 9         | 11     | 30%     |
| Hitachi             | 5         | 6      | 16.67%  |
| Samsung Electronics | 3         | 7      | 10%     |
| HGST                | 1         | 1      | 3.33%   |
| Fujitsu             | 1         | 2      | 3.33%   |
| asmedia             | 1         | 1      | 3.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 5      | 22.22%  |
| Kingston            | 3         | 3      | 16.67%  |
| Intel               | 2         | 2      | 11.11%  |
| GOODRAM             | 2         | 4      | 11.11%  |
| SPCC                | 1         | 2      | 5.56%   |
| SanDisk             | 1         | 1      | 5.56%   |
| Netac               | 1         | 1      | 5.56%   |
| Micron Technology   | 1         | 1      | 5.56%   |
| Gigabyte Technology | 1         | 1      | 5.56%   |
| Crucial             | 1         | 1      | 5.56%   |
| ASUS-JM             | 1         | 1      | 5.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 27        | 42     | 51.92%  |
| SSD     | 16        | 22     | 30.77%  |
| NVMe    | 5         | 5      | 9.62%   |
| MMC     | 2         | 2      | 3.85%   |
| Unknown | 2         | 2      | 3.85%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 38        | 61     | 80.85%  |
| NVMe | 5         | 5      | 10.64%  |
| SAS  | 2         | 5      | 4.26%   |
| MMC  | 2         | 2      | 4.26%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 34        | 50     | 82.93%  |
| 0.51-1.0   | 5         | 10     | 12.2%   |
| 1.01-2.0   | 1         | 1      | 2.44%   |
| 4.01-10.0  | 1         | 3      | 2.44%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 14        | 33.33%  |
| 501-1000       | 7         | 16.67%  |
| 251-500        | 6         | 14.29%  |
| 1-20           | 4         | 9.52%   |
| 51-100         | 3         | 7.14%   |
| 21-50          | 2         | 4.76%   |
| 2001-3000      | 2         | 4.76%   |
| Unknown        | 2         | 4.76%   |
| More than 3000 | 1         | 2.38%   |
| 1001-2000      | 1         | 2.38%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 19        | 43.18%  |
| 21-50          | 6         | 13.64%  |
| 51-100         | 6         | 13.64%  |
| 101-250        | 3         | 6.82%   |
| 501-1000       | 3         | 6.82%   |
| 251-500        | 2         | 4.55%   |
| 1001-2000      | 2         | 4.55%   |
| Unknown        | 2         | 4.55%   |
| More than 3000 | 1         | 2.27%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-22ZAT0 500GB                         | 1         | 1      | 12.5%   |
| WDC WD5000AVVS-63ZWB0 500GB                         | 1         | 1      | 12.5%   |
| WDC WD3200BPVT-75ZEST0 320GB                        | 1         | 1      | 12.5%   |
| WDC WD1600AAJS-08L7A0 160GB                         | 1         | 1      | 12.5%   |
| Seagate ST9500325AS 500GB                           | 1         | 1      | 12.5%   |
| Seagate ST9250315AS 250GB                           | 1         | 1      | 12.5%   |
| Micron Technology MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 1      | 12.5%   |
| asmedia ASMT1153e 1TB                               | 1         | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| WDC               | 4         | 4      | 50%     |
| Seagate           | 2         | 2      | 25%     |
| Micron Technology | 1         | 1      | 12.5%   |
| asmedia           | 1         | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 4         | 4      | 57.14%  |
| Seagate | 2         | 2      | 28.57%  |
| asmedia | 1         | 1      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 7         | 7      | 87.5%   |
| SSD  | 1         | 1      | 12.5%   |

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
| Works    | 23        | 37     | 50%     |
| Detected | 15        | 28     | 32.61%  |
| Malfunc  | 8         | 8      | 17.39%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 28        | 62.22%  |
| AMD                      | 7         | 15.56%  |
| Samsung Electronics      | 3         | 6.67%   |
| Nvidia                   | 2         | 4.44%   |
| VIA Technologies         | 1         | 2.22%   |
| Silicon Motion           | 1         | 2.22%   |
| Marvell Technology Group | 1         | 2.22%   |
| JMicron Technology       | 1         | 2.22%   |
| ADATA Technology         | 1         | 2.22%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 5         | 8.93%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 3         | 5.36%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 3         | 5.36%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 3.57%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 2         | 3.57%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 3.57%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 2         | 3.57%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 2         | 3.57%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 2         | 3.57%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 3.57%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 3.57%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                      | 1         | 1.79%   |
| VIA VT8237A SATA 2-Port Controller                                               | 1         | 1.79%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 1         | 1.79%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 1         | 1.79%   |
| Nvidia MCP61 SATA Controller                                                     | 1         | 1.79%   |
| Nvidia MCP61 IDE                                                                 | 1         | 1.79%   |
| Nvidia MCP51 Serial ATA Controller                                               | 1         | 1.79%   |
| Nvidia MCP51 IDE                                                                 | 1         | 1.79%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                        | 1         | 1.79%   |
| JMicron JMB360 AHCI Controller                                                   | 1         | 1.79%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 1         | 1.79%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 1.79%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 1.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 1.79%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 1.79%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 1         | 1.79%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 1         | 1.79%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 1         | 1.79%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 1         | 1.79%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 1.79%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 1.79%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1         | 1.79%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 1         | 1.79%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 1         | 1.79%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 1         | 1.79%   |
| AMD X370 Series Chipset SATA Controller                                          | 1         | 1.79%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 1         | 1.79%   |
| AMD 400 Series Chipset SATA Controller                                           | 1         | 1.79%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 1         | 1.79%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 28        | 58.33%  |
| IDE  | 14        | 29.17%  |
| NVMe | 5         | 10.42%  |
| RAID | 1         | 2.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 31        | 75.61%  |
| AMD    | 10        | 24.39%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Atom CPU N280 @ 1.66GHz                 | 2         | 4.88%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 2         | 4.88%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz        | 1         | 2.44%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz   | 1         | 2.44%   |
| Intel Pentium CPU B950 @ 2.10GHz              | 1         | 2.44%   |
| Intel Genuine CPU T2400 @ 1.83GHz             | 1         | 2.44%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 1         | 2.44%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 1         | 2.44%   |
| Intel Core i7-3612QM CPU @ 2.10GHz            | 1         | 2.44%   |
| Intel Core i7 CPU 860 @ 2.80GHz               | 1         | 2.44%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 2.44%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 1         | 2.44%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 1         | 2.44%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 2.44%   |
| Intel Core i5-10400 CPU @ 2.90GHz             | 1         | 2.44%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 2.44%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 1         | 2.44%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 1         | 2.44%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 1         | 2.44%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 1         | 2.44%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 1         | 2.44%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 1         | 2.44%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz          | 1         | 2.44%   |
| Intel Core 2 CPU T5600 @ 1.83GHz              | 1         | 2.44%   |
| Intel Celeron CPU N3160 @ 1.60GHz             | 1         | 2.44%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 1         | 2.44%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 1         | 2.44%   |
| Intel Celeron CPU 900 @ 2.20GHz               | 1         | 2.44%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 1         | 2.44%   |
| AMD Turion 64 X2 Mobile Technology TL-64      | 1         | 2.44%   |
| AMD Sempron 145 Processor                     | 1         | 2.44%   |
| AMD Ryzen 7 1800X Eight-Core Processor        | 1         | 2.44%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 2.44%   |
| AMD Ryzen 3 3100 4-Core Processor             | 1         | 2.44%   |
| AMD PRO A8-8600B R6, 10 Compute Cores 4C+6G   | 1         | 2.44%   |
| AMD PRO A10-8700B R6, 10 Compute Cores 4C+6G  | 1         | 2.44%   |
| AMD C-50 Processor                            | 1         | 2.44%   |
| AMD Athlon II X2 B22 Processor                | 1         | 2.44%   |
| AMD A6-7480 Radeon R5, 8 Compute Cores 2C+6G  | 1         | 2.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 7         | 17.07%  |
| Intel Atom              | 5         | 12.2%   |
| Intel Core i7           | 4         | 9.76%   |
| Intel Core 2 Duo        | 4         | 9.76%   |
| Intel Celeron           | 4         | 9.76%   |
| Intel Pentium Gold      | 1         | 2.44%   |
| Intel Pentium Dual-Core | 1         | 2.44%   |
| Intel Pentium           | 1         | 2.44%   |
| Intel Genuine           | 1         | 2.44%   |
| Intel Core i3           | 1         | 2.44%   |
| Intel Core 2 Quad       | 1         | 2.44%   |
| Intel Core 2            | 1         | 2.44%   |
| AMD Turion 64 X2 Mobile | 1         | 2.44%   |
| AMD Sempron             | 1         | 2.44%   |
| AMD Ryzen 7             | 1         | 2.44%   |
| AMD Ryzen 5             | 1         | 2.44%   |
| AMD Ryzen 3             | 1         | 2.44%   |
| AMD PRO A8              | 1         | 2.44%   |
| AMD PRO A10             | 1         | 2.44%   |
| AMD C-50                | 1         | 2.44%   |
| AMD Athlon II X2        | 1         | 2.44%   |
| AMD A6                  | 1         | 2.44%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 20        | 48.78%  |
| 4      | 12        | 29.27%  |
| 1      | 7         | 17.07%  |
| 8      | 1         | 2.44%   |
| 6      | 1         | 2.44%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 41        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 21        | 51.22%  |
| 2      | 20        | 48.78%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 36        | 87.8%   |
| 32-bit         | 5         | 12.2%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 8         | 19.51%  |
| 0x0600611a | 3         | 7.32%   |
| 0x406c4    | 2         | 4.88%   |
| 0x306a9    | 2         | 4.88%   |
| 0x206a7    | 2         | 4.88%   |
| 0x20655    | 2         | 4.88%   |
| 0x106c2    | 2         | 4.88%   |
| 0x1067a    | 2         | 4.88%   |
| 0xa0653    | 1         | 2.44%   |
| 0x806ec    | 1         | 2.44%   |
| 0x806ea    | 1         | 2.44%   |
| 0x6fd      | 1         | 2.44%   |
| 0x6fb      | 1         | 2.44%   |
| 0x6f2      | 1         | 2.44%   |
| 0x506e3    | 1         | 2.44%   |
| 0x406c3    | 1         | 2.44%   |
| 0x40651    | 1         | 2.44%   |
| 0x306c3    | 1         | 2.44%   |
| 0x30678    | 1         | 2.44%   |
| 0x106e5    | 1         | 2.44%   |
| 0x10676    | 1         | 2.44%   |
| 0x08701021 | 1         | 2.44%   |
| 0x08108109 | 1         | 2.44%   |
| 0x08001138 | 1         | 2.44%   |
| 0x05000029 | 1         | 2.44%   |
| 0x010000c8 | 1         | 2.44%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Silvermont  | 4         | 9.76%   |
| Penryn      | 4         | 9.76%   |
| Core        | 4         | 9.76%   |
| Bonnell     | 4         | 9.76%   |
| KabyLake    | 3         | 7.32%   |
| Excavator   | 3         | 7.32%   |
| Westmere    | 2         | 4.88%   |
| SandyBridge | 2         | 4.88%   |
| K10         | 2         | 4.88%   |
| IvyBridge   | 2         | 4.88%   |
| Haswell     | 2         | 4.88%   |
| Zen+        | 1         | 2.44%   |
| Zen 2       | 1         | 2.44%   |
| Zen         | 1         | 2.44%   |
| Skylake     | 1         | 2.44%   |
| P6          | 1         | 2.44%   |
| Nehalem     | 1         | 2.44%   |
| K8 Hammer   | 1         | 2.44%   |
| CometLake   | 1         | 2.44%   |
| Bobcat      | 1         | 2.44%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Intel            | 24        | 55.81%  |
| AMD              | 11        | 25.58%  |
| Nvidia           | 7         | 16.28%  |
| VIA Technologies | 1         | 2.33%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 4         | 8.33%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 3         | 6.25%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 6.25%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 3         | 6.25%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 4.17%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 4.17%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 4.17%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 1         | 2.08%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 2.08%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1         | 2.08%   |
| Nvidia GK104GLM [Quadro K3000M]                                                          | 1         | 2.08%   |
| Nvidia GF108M [GeForce GT 420M]                                                          | 1         | 2.08%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 2.08%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 1         | 2.08%   |
| Nvidia C51 [GeForce Go 6150]                                                             | 1         | 2.08%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1         | 2.08%   |
| Intel UHD Graphics 620                                                                   | 1         | 2.08%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 2.08%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 2.08%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 2.08%   |
| Intel HD Graphics 530                                                                    | 1         | 2.08%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 2.08%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 2.08%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 2.08%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1         | 2.08%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                                | 1         | 2.08%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 2.08%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1         | 2.08%   |
| AMD Wrestler [Radeon HD 6250]                                                            | 1         | 2.08%   |
| AMD RV515/M54 [Mobility Radeon X1400]                                                    | 1         | 2.08%   |
| AMD RS880 [Radeon HD 4200]                                                               | 1         | 2.08%   |
| AMD Redwood LE [Radeon HD 5550/5570/5630/6390/6490/7570]                                 | 1         | 2.08%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1         | 2.08%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 1         | 2.08%   |
| AMD Barts PRO [Radeon HD 6850]                                                           | 1         | 2.08%   |
| AMD Barts LE [Radeon HD 6790]                                                            | 1         | 2.08%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 23        | 56.1%   |
| 1 x AMD        | 10        | 24.39%  |
| 1 x Nvidia     | 6         | 14.63%  |
| 1 x VIA        | 1         | 2.44%   |
| Intel + Nvidia | 1         | 2.44%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 37        | 90.24%  |
| Proprietary | 2         | 4.88%   |
| Unknown     | 2         | 4.88%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 28        | 68.29%  |
| 0.01-0.5   | 6         | 14.63%  |
| 1.01-2.0   | 3         | 7.32%   |
| 0.51-1.0   | 2         | 4.88%   |
| 7.01-8.0   | 1         | 2.44%   |
| 3.01-4.0   | 1         | 2.44%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 6         | 14.63%  |
| LG Display          | 6         | 14.63%  |
| Goldstar            | 3         | 7.32%   |
| Dell                | 3         | 7.32%   |
| Chimei Innolux      | 3         | 7.32%   |
| AU Optronics        | 3         | 7.32%   |
| Lenovo              | 2         | 4.88%   |
| CPT                 | 2         | 4.88%   |
| BenQ                | 2         | 4.88%   |
| AOC                 | 2         | 4.88%   |
| Unknown             | 1         | 2.44%   |
| LG Philips          | 1         | 2.44%   |
| JCH                 | 1         | 2.44%   |
| Insignia            | 1         | 2.44%   |
| Hitachi             | 1         | 2.44%   |
| HannStar            | 1         | 2.44%   |
| BOE                 | 1         | 2.44%   |
| Apple               | 1         | 2.44%   |
| Acer                | 1         | 2.44%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch            | 1         | 2.27%   |
| Samsung Electronics SyncMaster SAM0581 1920x1080 477x268mm 21.5-inch | 1         | 2.27%   |
| Samsung Electronics SyncMaster SAM0116 1024x768 267x200mm 13.1-inch  | 1         | 2.27%   |
| Samsung Electronics S24D330 SAM0D93 1920x1080 531x299mm 24.0-inch    | 1         | 2.27%   |
| Samsung Electronics S22C450 SAM09C5 1920x1080 477x268mm 21.5-inch    | 1         | 2.27%   |
| Samsung Electronics LCD Monitor SEC4F45 1280x800 331x207mm 15.4-inch | 1         | 2.27%   |
| Samsung Electronics LCD Monitor SEC4141 1366x768 344x193mm 15.5-inch | 1         | 2.27%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 1         | 2.27%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch          | 1         | 2.27%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch        | 1         | 2.27%   |
| LG Display LCD Monitor LGD059E 1920x1080 382x215mm 17.3-inch         | 1         | 2.27%   |
| LG Display LCD Monitor LGD04E1 1366x768 344x194mm 15.5-inch          | 1         | 2.27%   |
| LG Display LCD Monitor LGD02E1 1600x900 382x215mm 17.3-inch          | 1         | 2.27%   |
| LG Display LCD Monitor LGD0266 1366x768 344x194mm 15.5-inch          | 1         | 2.27%   |
| LG Display LCD Monitor LGD01C5 1366x768 293x165mm 13.2-inch          | 1         | 2.27%   |
| Lenovo LCD Monitor LEN4033 1440x900 303x190mm 14.1-inch              | 1         | 2.27%   |
| Lenovo LCD Monitor LEN4022 1400x1050 287x215mm 14.1-inch             | 1         | 2.27%   |
| JCH F24 JCH1919 1920x1080 520x310mm 23.8-inch                        | 1         | 2.27%   |
| Insignia DX-32D20SNA14 BBY0032 1360x768 544x326mm 25.0-inch          | 1         | 2.27%   |
| Hitachi HDMI HEC0088 1920x540                                        | 1         | 2.27%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch            | 1         | 2.27%   |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                  | 1         | 2.27%   |
| Goldstar T710SH GSM436B 1280x960 310x230mm 15.2-inch                 | 1         | 2.27%   |
| Goldstar L1953H GSM4B3D 1280x1024 338x270mm 17.0-inch                | 1         | 2.27%   |
| Goldstar 23MP55 GSM5A23 1920x1080 510x290mm 23.1-inch                | 1         | 2.27%   |
| Dell LCD Monitor S2715H 3840x1080                                    | 1         | 2.27%   |
| Dell LCD Monitor S2715H                                              | 1         | 2.27%   |
| Dell IN1930 DELF03B 1366x768 410x230mm 18.5-inch                     | 1         | 2.27%   |
| Dell E176FP DELA014 1280x1024 338x270mm 17.0-inch                    | 1         | 2.27%   |
| CPT LCD Monitor CPT04CE 1024x600 222x130mm 10.1-inch                 | 1         | 2.27%   |
| CPT LCD Monitor CPT04C4 1024x600 222x130mm 10.1-inch                 | 1         | 2.27%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch     | 1         | 2.27%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 308x173mm 13.9-inch     | 1         | 2.27%   |
| Chimei Innolux LCD Monitor CMN1484 1600x900 310x174mm 14.0-inch      | 1         | 2.27%   |
| BOE LCD Monitor BOE085E 1920x1080 344x194mm 15.5-inch                | 1         | 2.27%   |
| BenQ FP202WA BNQ76C2 1680x1050 430x270mm 20.0-inch                   | 1         | 2.27%   |
| BenQ E900HD BNQ7910 1366x768 410x230mm 18.5-inch                     | 1         | 2.27%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch       | 1         | 2.27%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch        | 1         | 2.27%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch       | 1         | 2.27%   |
| Apple Color LCD APP9C5E 1280x800 286x178mm 13.3-inch                 | 1         | 2.27%   |
| AOC LM729 AOCA784 1280x1024 340x270mm 17.1-inch                      | 1         | 2.27%   |
| AOC 2450W AOC2450 1920x1080 521x293mm 23.5-inch                      | 1         | 2.27%   |
| Acer S232HL ACR0203 1920x1080 510x287mm 23.0-inch                    | 1         | 2.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 14        | 31.82%  |
| 1366x768 (WXGA)    | 7         | 15.91%  |
| 1600x900 (HD+)     | 4         | 9.09%   |
| 1280x1024 (SXGA)   | 3         | 6.82%   |
| 1024x600           | 3         | 6.82%   |
| 1920x540           | 2         | 4.55%   |
| 1440x900 (WXGA+)   | 2         | 4.55%   |
| 1280x800 (WXGA)    | 2         | 4.55%   |
| 3840x1080          | 1         | 2.27%   |
| 2288x1287          | 1         | 2.27%   |
| 1680x1050 (WSXGA+) | 1         | 2.27%   |
| 1400x1050          | 1         | 2.27%   |
| 1280x960           | 1         | 2.27%   |
| 1024x768 (XGA)     | 1         | 2.27%   |
| Unknown            | 1         | 2.27%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 17      | 9         | 20.93%  |
| 15      | 7         | 16.28%  |
| 23      | 5         | 11.63%  |
| 13      | 4         | 9.3%    |
| 14      | 3         | 6.98%   |
| 10      | 3         | 6.98%   |
| 48      | 2         | 4.65%   |
| 21      | 2         | 4.65%   |
| 20      | 2         | 4.65%   |
| 18      | 2         | 4.65%   |
| 142     | 1         | 2.33%   |
| 24      | 1         | 2.33%   |
| 16      | 1         | 2.33%   |
| Unknown | 1         | 2.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 14        | 32.56%  |
| 201-300        | 7         | 16.28%  |
| 501-600        | 6         | 13.95%  |
| 401-500        | 6         | 13.95%  |
| 351-400        | 6         | 13.95%  |
| 1001-1500      | 2         | 4.65%   |
| More than 2000 | 1         | 2.33%   |
| Unknown        | 1         | 2.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 28        | 65.12%  |
| 16/10   | 5         | 11.63%  |
| 5/4     | 3         | 6.98%   |
| 4/3     | 3         | 6.98%   |
| 1.96    | 2         | 4.65%   |
| 1.00    | 1         | 2.33%   |
| Unknown | 1         | 2.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 7         | 16.28%  |
| 201-250        | 6         | 13.95%  |
| 121-130        | 6         | 13.95%  |
| 141-150        | 5         | 11.63%  |
| 81-90          | 4         | 9.3%    |
| 151-200        | 4         | 9.3%    |
| 41-50          | 3         | 6.98%   |
| 71-80          | 2         | 4.65%   |
| 501-1000       | 2         | 4.65%   |
| More than 1000 | 1         | 2.33%   |
| 131-140        | 1         | 2.33%   |
| 91-100         | 1         | 2.33%   |
| Unknown        | 1         | 2.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 15        | 36.59%  |
| 101-120 | 13        | 31.71%  |
| 121-160 | 9         | 21.95%  |
| 1-50    | 3         | 7.32%   |
| Unknown | 1         | 2.44%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 37        | 90.24%  |
| 2     | 4         | 9.76%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 17        | 28.33%  |
| Intel                    | 15        | 25%     |
| Qualcomm Atheros         | 10        | 16.67%  |
| Broadcom Limited         | 4         | 6.67%   |
| Broadcom                 | 3         | 5%      |
| TP-Link                  | 2         | 3.33%   |
| Ralink Technology        | 2         | 3.33%   |
| Nvidia                   | 2         | 3.33%   |
| Marvell Technology Group | 2         | 3.33%   |
| VIA Technologies         | 1         | 1.67%   |
| Ralink                   | 1         | 1.67%   |
| D-Link System            | 1         | 1.67%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                       | Computers | Percent |
|---------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                           | 12        | 17.14%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                       | 5         | 7.14%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                              | 2         | 2.86%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                              | 2         | 2.86%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                     | 2         | 2.86%   |
| Intel Wireless 7265                                                                         | 2         | 2.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                       | 2         | 2.86%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                                            | 2         | 2.86%   |
| VIA VT6102/VT6103 [Rhine-II]                                                                | 1         | 1.43%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                                                       | 1         | 1.43%   |
| TP-Link 802.11ac WLAN Adapter                                                               | 1         | 1.43%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                    | 1         | 1.43%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                             | 1         | 1.43%   |
| Ralink RT5370 Wireless Adapter                                                              | 1         | 1.43%   |
| Ralink RT3072 Wireless Adapter                                                              | 1         | 1.43%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                   | 1         | 1.43%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                  | 1         | 1.43%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                                   | 1         | 1.43%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                            | 1         | 1.43%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                              | 1         | 1.43%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                                       | 1         | 1.43%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]               | 1         | 1.43%   |
| Nvidia MCP61 Ethernet                                                                       | 1         | 1.43%   |
| Nvidia MCP51 Ethernet Controller                                                            | 1         | 1.43%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                                     | 1         | 1.43%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                                        | 1         | 1.43%   |
| Intel Wireless 8260                                                                         | 1         | 1.43%   |
| Intel Wireless 7260                                                                         | 1         | 1.43%   |
| Intel Wireless 3165                                                                         | 1         | 1.43%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                                     | 1         | 1.43%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                               | 1         | 1.43%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                       | 1         | 1.43%   |
| Intel I211 Gigabit Network Connection                                                       | 1         | 1.43%   |
| Intel Ethernet Connection I218-LM                                                           | 1         | 1.43%   |
| Intel Ethernet Connection (2) I219-LM                                                       | 1         | 1.43%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                           | 1         | 1.43%   |
| Intel Centrino Wireless-N 2230                                                              | 1         | 1.43%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                                | 1         | 1.43%   |
| Intel Centrino Ultimate-N 6300                                                              | 1         | 1.43%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                | 1         | 1.43%   |
| Intel 82573L Gigabit Ethernet Controller                                                    | 1         | 1.43%   |
| Intel 82566MM Gigabit Network Connection                                                    | 1         | 1.43%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                                        | 1         | 1.43%   |
| D-Link System DWA-160 802.11abgn Xtreme N Dual Band Adapter(rev.A2) [Atheros AR9170+AR9104] | 1         | 1.43%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                             | 1         | 1.43%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe                                    | 1         | 1.43%   |
| Broadcom Limited NetLink BCM57788 Gigabit Ethernet PCIe                                     | 1         | 1.43%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter                                 | 1         | 1.43%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                                   | 1         | 1.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 13        | 41.94%  |
| Qualcomm Atheros      | 8         | 25.81%  |
| TP-Link               | 2         | 6.45%   |
| Realtek Semiconductor | 2         | 6.45%   |
| Ralink Technology     | 2         | 6.45%   |
| Broadcom Limited      | 2         | 6.45%   |
| Ralink                | 1         | 3.23%   |
| D-Link System         | 1         | 3.23%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                       | Computers | Percent |
|---------------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                              | 2         | 6.45%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                     | 2         | 6.45%   |
| Intel Wireless 7265                                                                         | 2         | 6.45%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                                                       | 1         | 3.23%   |
| TP-Link 802.11ac WLAN Adapter                                                               | 1         | 3.23%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                    | 1         | 3.23%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                             | 1         | 3.23%   |
| Ralink RT5370 Wireless Adapter                                                              | 1         | 3.23%   |
| Ralink RT3072 Wireless Adapter                                                              | 1         | 3.23%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                   | 1         | 3.23%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                  | 1         | 3.23%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                            | 1         | 3.23%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                              | 1         | 3.23%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]               | 1         | 3.23%   |
| Intel Wireless 8260                                                                         | 1         | 3.23%   |
| Intel Wireless 7260                                                                         | 1         | 3.23%   |
| Intel Wireless 3165                                                                         | 1         | 3.23%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                                     | 1         | 3.23%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                               | 1         | 3.23%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                       | 1         | 3.23%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                           | 1         | 3.23%   |
| Intel Centrino Wireless-N 2230                                                              | 1         | 3.23%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                                | 1         | 3.23%   |
| Intel Centrino Ultimate-N 6300                                                              | 1         | 3.23%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                | 1         | 3.23%   |
| D-Link System DWA-160 802.11abgn Xtreme N Dual Band Adapter(rev.A2) [Atheros AR9170+AR9104] | 1         | 3.23%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter                                 | 1         | 3.23%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                                   | 1         | 3.23%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 17        | 43.59%  |
| Intel                    | 8         | 20.51%  |
| Qualcomm Atheros         | 4         | 10.26%  |
| Broadcom                 | 3         | 7.69%   |
| Nvidia                   | 2         | 5.13%   |
| Marvell Technology Group | 2         | 5.13%   |
| Broadcom Limited         | 2         | 5.13%   |
| VIA Technologies         | 1         | 2.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 12        | 30.77%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 12.82%  |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 5.13%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 5.13%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 2         | 5.13%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 2.56%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 2.56%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 2.56%   |
| Nvidia MCP61 Ethernet                                             | 1         | 2.56%   |
| Nvidia MCP51 Ethernet Controller                                  | 1         | 2.56%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 2.56%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 2.56%   |
| Intel I211 Gigabit Network Connection                             | 1         | 2.56%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 2.56%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 2.56%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 2.56%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 2.56%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 1         | 2.56%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 2.56%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1         | 2.56%   |
| Broadcom Limited NetLink BCM57788 Gigabit Ethernet PCIe           | 1         | 2.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 38        | 55.88%  |
| WiFi     | 30        | 44.12%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 25        | 56.82%  |
| Ethernet | 19        | 43.18%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 24        | 58.54%  |
| 1     | 17        | 41.46%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 37        | 86.05%  |
| Yes  | 6         | 13.95%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 7         | 38.89%  |
| Broadcom                        | 3         | 16.67%  |
| Realtek Semiconductor           | 2         | 11.11%  |
| Qualcomm Atheros Communications | 2         | 11.11%  |
| Dell                            | 1         | 5.56%   |
| Cambridge Silicon Radio         | 1         | 5.56%   |
| ASUSTek Computer                | 1         | 5.56%   |
| Apple                           | 1         | 5.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 5         | 27.78%  |
| Realtek RTL8723B Bluetooth                          | 1         | 5.56%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 5.56%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 5.56%   |
| Qualcomm Atheros Bluetooth                          | 1         | 5.56%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 5.56%   |
| Intel AX201 Bluetooth                               | 1         | 5.56%   |
| Dell Wireless 365 Bluetooth                         | 1         | 5.56%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 5.56%   |
| Broadcom HP Portable SoftSailing                    | 1         | 5.56%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 1         | 5.56%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 5.56%   |
| ASUS Broadcom Bluetooth 2.1                         | 1         | 5.56%   |
| Apple Bluetooth HCI                                 | 1         | 5.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 29        | 58%     |
| AMD                 | 10        | 20%     |
| Nvidia              | 6         | 12%     |
| VIA Technologies    | 1         | 2%      |
| Plantronics         | 1         | 2%      |
| Native Instruments  | 1         | 2%      |
| Focusrite-Novation  | 1         | 2%      |
| C-Media Electronics | 1         | 2%      |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7         | 11.86%  |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 5.08%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 5.08%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 5.08%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 3.39%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 2         | 3.39%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 3.39%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 3.39%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 3.39%   |
| AMD Barts HDMI Audio [Radeon HD 6790/6850/6870 / 7720 OEM]                                        | 2         | 3.39%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1         | 1.69%   |
| Plantronics USB DSP v4 Audio Interface                                                            | 1         | 1.69%   |
| Nvidia MCP61 High Definition Audio                                                                | 1         | 1.69%   |
| Nvidia MCP51 High Definition Audio                                                                | 1         | 1.69%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 1.69%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 1.69%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 1.69%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 1.69%   |
| Native Instruments KOMPLETE KONTROL M32                                                           | 1         | 1.69%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 1.69%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 1         | 1.69%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 1.69%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 1         | 1.69%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 1.69%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 1.69%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 1         | 1.69%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 1         | 1.69%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 1.69%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 1.69%   |
| Intel 200 Series PCH HD Audio                                                                     | 1         | 1.69%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 1.69%   |
| Focusrite-Novation Focusrite Scarlett 2i2 2nd Gen                                                 | 1         | 1.69%   |
| C-Media Electronics SADES Luna                                                                    | 1         | 1.69%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 1.69%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 1         | 1.69%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 1         | 1.69%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 1.69%   |
| AMD Navi 10 HDMI Audio                                                                            | 1         | 1.69%   |
| AMD FCH Azalia Controller                                                                         | 1         | 1.69%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 1         | 1.69%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 1         | 1.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 7         | 21.88%  |
| Samsung Electronics | 7         | 21.88%  |
| SK Hynix            | 3         | 9.38%   |
| Kingston            | 3         | 9.38%   |
| Nanya Technology    | 2         | 6.25%   |
| Micron Technology   | 2         | 6.25%   |
| G.Skill             | 2         | 6.25%   |
| Corsair             | 2         | 6.25%   |
| GOODRAM             | 1         | 3.13%   |
| Elpida              | 1         | 3.13%   |
| Crucial             | 1         | 3.13%   |
| Avant               | 1         | 3.13%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB DIMM 800MT/s                   | 2         | 5.88%   |
| Unknown RAM Module 2GB SODIMM SDRAM                      | 1         | 2.94%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                 | 1         | 2.94%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s              | 1         | 2.94%   |
| Unknown RAM Module 1024MB SODIMM DDR2                    | 1         | 2.94%   |
| Unknown RAM Module 1024MB SODIMM 800MT/s                 | 1         | 2.94%   |
| Unknown RAM Module 1024MB DIMM SDRAM                     | 1         | 2.94%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1066MT/s             | 1         | 2.94%   |
| SK Hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s  | 1         | 2.94%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s   | 1         | 2.94%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s              | 1         | 2.94%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s    | 1         | 2.94%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s    | 1         | 2.94%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s    | 1         | 2.94%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s    | 1         | 2.94%   |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1334MT/s    | 1         | 2.94%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s | 1         | 2.94%   |
| Samsung RAM K4E8E324EB-EGCF 2GB LPDDR3 1867MT/s          | 1         | 2.94%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s     | 1         | 2.94%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s     | 1         | 2.94%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8192MB SODIMM DDR3 1600MT/s | 1         | 2.94%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s   | 1         | 2.94%   |
| Kingston RAM Module 16GB SODIMM DDR4 2133MT/s            | 1         | 2.94%   |
| Kingston RAM KHX1600C9D3/4GX 4096MB DIMM DDR3 2400MT/s   | 1         | 2.94%   |
| Kingston RAM ACR128X64D3S1333C9 1GB SODIMM DDR3 1333MT/s | 1         | 2.94%   |
| GOODRAM RAM GR1600S3V64L11/8G 8GB SODIMM DDR3 1600MT/s   | 1         | 2.94%   |
| G.Skill RAM F4-3200C16-8GIS 8192MB DIMM DDR4 3200MT/s    | 1         | 2.94%   |
| G.Skill RAM F4-2400C16-16GRS 16GB SODIMM DDR4 2667MT/s   | 1         | 2.94%   |
| Elpida RAM EBJ81UG8BAS0-DJ-F 8GB SODIMM DDR3 1333MT/s    | 1         | 2.94%   |
| Crucial RAM BLS8G3D1609DS1S00. 8192MB DIMM DDR3 1600MT/s | 1         | 2.94%   |
| Corsair RAM CMZ4GX3M1A1600C9 4096MB DIMM DDR3 1600MT/s   | 1         | 2.94%   |
| Corsair RAM CMSA4GX3M1A1333C9 4GB SODIMM DDR3 1333MT/s   | 1         | 2.94%   |
| Avant RAM W641GU49J2320N6 8GB DIMM DDR4 2666MT/s         | 1         | 2.94%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 16        | 53.33%  |
| DDR4    | 5         | 16.67%  |
| SDRAM   | 3         | 10%     |
| Unknown | 3         | 10%     |
| DDR2    | 2         | 6.67%   |
| LPDDR3  | 1         | 3.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SODIMM  | 19        | 65.52%  |
| DIMM    | 9         | 31.03%  |
| Unknown | 1         | 3.45%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 9         | 27.27%  |
| 2048  | 9         | 27.27%  |
| 8192  | 8         | 24.24%  |
| 1024  | 4         | 12.12%  |
| 16384 | 3         | 9.09%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 10        | 32.26%  |
| 800     | 4         | 12.9%   |
| 1333    | 3         | 9.68%   |
| Unknown | 3         | 9.68%   |
| 2667    | 2         | 6.45%   |
| 1334    | 2         | 6.45%   |
| 4199    | 1         | 3.23%   |
| 3200    | 1         | 3.23%   |
| 2666    | 1         | 3.23%   |
| 2400    | 1         | 3.23%   |
| 2133    | 1         | 3.23%   |
| 1867    | 1         | 3.23%   |
| 1066    | 1         | 3.23%   |

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 7         | 31.82%  |
| Microdia                               | 4         | 18.18%  |
| Sunplus Innovation Technology          | 2         | 9.09%   |
| Logitech                               | 2         | 9.09%   |
| Acer                                   | 2         | 9.09%   |
| Z-Star Microelectronics                | 1         | 4.55%   |
| Suyin                                  | 1         | 4.55%   |
| Samsung Electronics                    | 1         | 4.55%   |
| Microsoft                              | 1         | 4.55%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 4.55%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Z-Star Namuga 1.3M Webcam                                   | 1         | 4.55%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 4.55%   |
| Sunplus Integrated Webcam                                   | 1         | 4.55%   |
| Sunplus HP HD Webcam [Fixed]                                | 1         | 4.55%   |
| Samsung Galaxy A5 (MTP)                                     | 1         | 4.55%   |
| Microsoft LifeCam Cinema                                    | 1         | 4.55%   |
| Microdia Sonix USB 2.0 Camera                               | 1         | 4.55%   |
| Microdia Lenovo EasyCamera                                  | 1         | 4.55%   |
| Microdia Laptop_Integrated_Webcam_HD                        | 1         | 4.55%   |
| Microdia Laptop_Integrated_Webcam_1.3M                      | 1         | 4.55%   |
| Logitech Webcam C270                                        | 1         | 4.55%   |
| Logitech QuickCam Notebook Pro                              | 1         | 4.55%   |
| Chicony Integrated Camera (1280x720@30)                     | 1         | 4.55%   |
| Chicony HP TrueVision HD Camera                             | 1         | 4.55%   |
| Chicony HP Integrated Webcam                                | 1         | 4.55%   |
| Chicony HP HD Webcam                                        | 1         | 4.55%   |
| Chicony HD WebCam                                           | 1         | 4.55%   |
| Chicony Asus Integrated 0.3M UVC Webcam                     | 1         | 4.55%   |
| Chicony 2.0M UVC Webcam / CNF7129                           | 1         | 4.55%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera         | 1         | 4.55%   |
| Acer Lenovo EasyCamera                                      | 1         | 4.55%   |
| Acer HP Webcam                                              | 1         | 4.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Validity Sensors   | 3         | 75%     |
| STMicroelectronics | 1         | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader | 1         | 25%     |
| Validity Sensors VFS491                    | 1         | 25%     |
| Validity Sensors VFS101 Fingerprint Reader | 1         | 25%     |
| STMicroelectronics Fingerprint Reader      | 1         | 25%     |

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
| 0     | 29        | 70.73%  |
| 1     | 9         | 21.95%  |
| 2     | 3         | 7.32%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 4         | 26.67%  |
| Fingerprint reader    | 4         | 26.67%  |
| Net/wireless          | 3         | 20%     |
| Multimedia controller | 2         | 13.33%  |
| Chipcard              | 1         | 6.67%   |
| Camera                | 1         | 6.67%   |

