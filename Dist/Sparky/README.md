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

Total: 59

| Vendor    | Model                       | Form-Factor | Probe                                                      | Date         |
|-----------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Sparky 6    | 16        | 38.1%   |
| Sparky 6.1  | 6         | 14.29%  |
| Sparky 5.12 | 5         | 11.9%   |
| Sparky 6.0  | 3         | 7.14%   |
| Sparky 5.14 | 3         | 7.14%   |
| Sparky 5.10 | 3         | 7.14%   |
| Sparky 7    | 2         | 4.76%   |
| Sparky 6.2  | 2         | 4.76%   |
| Sparky 5.13 | 2         | 4.76%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Sparky | 40        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version             | Computers | Percent |
|---------------------|-----------|---------|
| 5.10.0-9-amd64      | 3         | 6.82%   |
| 5.10.0-8-amd64      | 3         | 6.82%   |
| 5.10.0-6-amd64      | 3         | 6.82%   |
| 5.10.0-11-686       | 3         | 6.82%   |
| 4.19.0-8-amd64      | 3         | 6.82%   |
| 4.19.0-12-amd64     | 3         | 6.82%   |
| 5.10.0-3-amd64      | 2         | 4.55%   |
| 4.19.0-13-686       | 2         | 4.55%   |
| 4.19.0-10-686       | 2         | 4.55%   |
| 5.9.13-sparky-amd64 | 1         | 2.27%   |
| 5.9.0-4-amd64       | 1         | 2.27%   |
| 5.8.13-sparky-amd64 | 1         | 2.27%   |
| 5.8.0-2-amd64       | 1         | 2.27%   |
| 5.7.2-sparky-amd64  | 1         | 2.27%   |
| 5.6.0-2-amd64       | 1         | 2.27%   |
| 5.5.0-2-amd64       | 1         | 2.27%   |
| 5.4.7-sparky-amd64  | 1         | 2.27%   |
| 5.2.0-2-amd64       | 1         | 2.27%   |
| 5.17.0-1-amd64      | 1         | 2.27%   |
| 5.16.5-sparky-amd64 | 1         | 2.27%   |
| 5.16.0-5-amd64      | 1         | 2.27%   |
| 5.15.0-3-amd64      | 1         | 2.27%   |
| 5.14.0-4-amd64      | 1         | 2.27%   |
| 5.10.4-sparky-amd64 | 1         | 2.27%   |
| 5.10.0-7-amd64      | 1         | 2.27%   |
| 5.10.0-2-amd64      | 1         | 2.27%   |
| 5.10.0-12-amd64     | 1         | 2.27%   |
| 4.19.0-14-686       | 1         | 2.27%   |
| 4.19.0-10-amd64     | 1         | 2.27%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 17        | 40.48%  |
| 4.19.0  | 10        | 23.81%  |
| 5.9.13  | 1         | 2.38%   |
| 5.9.0   | 1         | 2.38%   |
| 5.8.13  | 1         | 2.38%   |
| 5.8.0   | 1         | 2.38%   |
| 5.7.2   | 1         | 2.38%   |
| 5.6.0   | 1         | 2.38%   |
| 5.5.0   | 1         | 2.38%   |
| 5.4.7   | 1         | 2.38%   |
| 5.2.0   | 1         | 2.38%   |
| 5.17.0  | 1         | 2.38%   |
| 5.16.5  | 1         | 2.38%   |
| 5.16.0  | 1         | 2.38%   |
| 5.15.0  | 1         | 2.38%   |
| 5.14.0  | 1         | 2.38%   |
| 5.10.4  | 1         | 2.38%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 18        | 42.86%  |
| 4.19    | 10        | 23.81%  |
| 5.9     | 2         | 4.76%   |
| 5.8     | 2         | 4.76%   |
| 5.16    | 2         | 4.76%   |
| 5.7     | 1         | 2.38%   |
| 5.6     | 1         | 2.38%   |
| 5.5     | 1         | 2.38%   |
| 5.4     | 1         | 2.38%   |
| 5.2     | 1         | 2.38%   |
| 5.17    | 1         | 2.38%   |
| 5.15    | 1         | 2.38%   |
| 5.14    | 1         | 2.38%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 34        | 85%     |
| i686   | 6         | 15%     |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| XFCE             | 13        | 31.71%  |
| LXQt             | 12        | 29.27%  |
| Unknown          | 7         | 17.07%  |
| KDE5             | 2         | 4.88%   |
| GNOME            | 2         | 4.88%   |
| X-Cinnamon       | 1         | 2.44%   |
| openbox          | 1         | 2.44%   |
| MATE             | 1         | 2.44%   |
| lightdm-xsession | 1         | 2.44%   |
| ICEWM            | 1         | 2.44%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 38        | 92.68%  |
| Tty  | 3         | 7.32%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| TDM     | 13        | 32.5%   |
| Unknown | 12        | 30%     |
| SDDM    | 8         | 20%     |
| LightDM | 5         | 12.5%   |
| XDM     | 1         | 2.5%    |
| GDM     | 1         | 2.5%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 12        | 30%     |
| en_GB   | 4         | 10%     |
| pl_PL   | 3         | 7.5%    |
| pt_BR   | 2         | 5%      |
| fr_FR   | 2         | 5%      |
| es_ES   | 2         | 5%      |
| de_DE   | 2         | 5%      |
| Unknown | 2         | 5%      |
| sv_SE   | 1         | 2.5%    |
| ja_JP   | 1         | 2.5%    |
| es_US   | 1         | 2.5%    |
| es_CL   | 1         | 2.5%    |
| es_AR   | 1         | 2.5%    |
| en_ZA   | 1         | 2.5%    |
| en_PH   | 1         | 2.5%    |
| en_DK   | 1         | 2.5%    |
| en_CA   | 1         | 2.5%    |
| de_CH   | 1         | 2.5%    |
| cs_CZ   | 1         | 2.5%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 28        | 70%     |
| EFI  | 12        | 30%     |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 36        | 90%     |
| Overlay | 2         | 5%      |
| Zfs     | 1         | 2.5%    |
| Btrfs   | 1         | 2.5%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| MBR     | 14        | 35%     |
| GPT     | 13        | 32.5%   |
| Unknown | 13        | 32.5%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 34        | 85%     |
| Yes       | 6         | 15%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 25        | 62.5%   |
| Yes       | 15        | 37.5%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 9         | 22.5%   |
| Lenovo              | 5         | 12.5%   |
| Dell                | 5         | 12.5%   |
| Intel               | 4         | 10%     |
| Gigabyte Technology | 4         | 10%     |
| MSI                 | 3         | 7.5%    |
| ASUSTek Computer    | 3         | 7.5%    |
| Samsung Electronics | 1         | 2.5%    |
| Google              | 1         | 2.5%    |
| eMachines           | 1         | 2.5%    |
| Beelink             | 1         | 2.5%    |
| Apple               | 1         | 2.5%    |
| Acer                | 1         | 2.5%    |
| Unknown             | 1         | 2.5%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| Samsung NC10                     | 1         | 2.5%    |
| MSI MS-7C09                      | 1         | 2.5%    |
| MSI MS-7B86                      | 1         | 2.5%    |
| MSI MS-7721                      | 1         | 2.5%    |
| Lenovo ThinkPad T61 7659AB7      | 1         | 2.5%    |
| Lenovo ThinkPad T60 2007FUG      | 1         | 2.5%    |
| Lenovo ThinkPad E15 20RES0GF00   | 1         | 2.5%    |
| Lenovo IdeaPad S206 20154        | 1         | 2.5%    |
| Lenovo G50-30 80G0               | 1         | 2.5%    |
| Intel NUC5CPYB H61145-408        | 1         | 2.5%    |
| Intel H55                        | 1         | 2.5%    |
| Intel DG43RK AAE78175-402        | 1         | 2.5%    |
| Intel DG41TY AAE47335-300        | 1         | 2.5%    |
| HP t5740                         | 1         | 2.5%    |
| HP Pavilion g7                   | 1         | 2.5%    |
| HP Pavilion dv9000 (GA359UA#ABA) | 1         | 2.5%    |
| HP Pavilion dv5                  | 1         | 2.5%    |
| HP Laptop 17z-ca100              | 1         | 2.5%    |
| HP EliteDesk 800 G2 DM 65W       | 1         | 2.5%    |
| HP EliteDesk 705 G2 MINI         | 1         | 2.5%    |
| HP EliteBook Folio 9480m         | 1         | 2.5%    |
| HP EliteBook 8770w               | 1         | 2.5%    |
| Google Banon                     | 1         | 2.5%    |
| Gigabyte M68M-S2P                | 1         | 2.5%    |
| Gigabyte H97-Gaming 3            | 1         | 2.5%    |
| Gigabyte H410M H                 | 1         | 2.5%    |
| Gigabyte G41M-ES2L               | 1         | 2.5%    |
| eMachines E525                   | 1         | 2.5%    |
| Dell OptiPlex 580                | 1         | 2.5%    |
| Dell Latitude XT3                | 1         | 2.5%    |
| Dell Inspiron N5010              | 1         | 2.5%    |
| Dell Inspiron 5770               | 1         | 2.5%    |
| Dell Inspiron 5720               | 1         | 2.5%    |
| Beelink BT3 PRO                  | 1         | 2.5%    |
| ASUS S101                        | 1         | 2.5%    |
| ASUS CROSSHAIR VI HERO           | 1         | 2.5%    |
| ASUS 1000HE                      | 1         | 2.5%    |
| Apple MacBook1,1                 | 1         | 2.5%    |
| Acer Aspire 5742G                | 1         | 2.5%    |
| Unknown                          | 1         | 2.5%    |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 3         | 7.5%    |
| HP Pavilion         | 3         | 7.5%    |
| Dell Inspiron       | 3         | 7.5%    |
| HP EliteDesk        | 2         | 5%      |
| HP EliteBook        | 2         | 5%      |
| Samsung NC10        | 1         | 2.5%    |
| MSI MS-7C09         | 1         | 2.5%    |
| MSI MS-7B86         | 1         | 2.5%    |
| MSI MS-7721         | 1         | 2.5%    |
| Lenovo IdeaPad      | 1         | 2.5%    |
| Lenovo G50-30       | 1         | 2.5%    |
| Intel NUC5CPYB      | 1         | 2.5%    |
| Intel H55           | 1         | 2.5%    |
| Intel DG43RK        | 1         | 2.5%    |
| Intel DG41TY        | 1         | 2.5%    |
| HP t5740            | 1         | 2.5%    |
| HP Laptop           | 1         | 2.5%    |
| Google Banon        | 1         | 2.5%    |
| Gigabyte M68M-S2P   | 1         | 2.5%    |
| Gigabyte H97-Gaming | 1         | 2.5%    |
| Gigabyte H410M      | 1         | 2.5%    |
| Gigabyte G41M-ES2L  | 1         | 2.5%    |
| eMachines E525      | 1         | 2.5%    |
| Dell OptiPlex       | 1         | 2.5%    |
| Dell Latitude       | 1         | 2.5%    |
| Beelink BT3         | 1         | 2.5%    |
| ASUS S101           | 1         | 2.5%    |
| ASUS CROSSHAIR      | 1         | 2.5%    |
| ASUS 1000HE         | 1         | 2.5%    |
| Apple MacBook1      | 1         | 2.5%    |
| Acer Aspire         | 1         | 2.5%    |
| Unknown             | 1         | 2.5%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2009 | 7         | 17.5%   |
| 2012 | 4         | 10%     |
| 2018 | 3         | 7.5%    |
| 2015 | 3         | 7.5%    |
| 2014 | 3         | 7.5%    |
| 2010 | 3         | 7.5%    |
| 2008 | 3         | 7.5%    |
| 2021 | 2         | 5%      |
| 2020 | 2         | 5%      |
| 2019 | 2         | 5%      |
| 2011 | 2         | 5%      |
| 2007 | 2         | 5%      |
| 2006 | 2         | 5%      |
| 2017 | 1         | 2.5%    |
| 2016 | 1         | 2.5%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Notebook | 23        | 57.5%   |
| Desktop  | 16        | 40%     |
| Mini pc  | 1         | 2.5%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 40        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 39        | 97.5%   |
| Yes  | 1         | 2.5%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 13        | 32.5%   |
| 4.01-8.0   | 7         | 17.5%   |
| 2.01-3.0   | 5         | 12.5%   |
| 16.01-24.0 | 5         | 12.5%   |
| 1.01-2.0   | 4         | 10%     |
| 24.01-32.0 | 2         | 5%      |
| 8.01-16.0  | 2         | 5%      |
| 32.01-64.0 | 1         | 2.5%    |
| 0.51-1.0   | 1         | 2.5%    |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 18        | 42.86%  |
| 0.51-1.0 | 10        | 23.81%  |
| 2.01-3.0 | 6         | 14.29%  |
| 4.01-8.0 | 4         | 9.52%   |
| 3.01-4.0 | 2         | 4.76%   |
| 0.01-0.5 | 2         | 4.76%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 29        | 72.5%   |
| 2      | 7         | 17.5%   |
| 4      | 2         | 5%      |
| 5      | 1         | 2.5%    |
| 3      | 1         | 2.5%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 24        | 60%     |
| Yes       | 16        | 40%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 37        | 92.5%   |
| No        | 3         | 7.5%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 28        | 70%     |
| No        | 12        | 30%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 23        | 57.5%   |
| Yes       | 17        | 42.5%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 8         | 20%     |
| UK           | 4         | 10%     |
| Germany      | 4         | 10%     |
| Poland       | 3         | 7.5%    |
| France       | 3         | 7.5%    |
| Indonesia    | 2         | 5%      |
| Canada       | 2         | 5%      |
| Brazil       | 2         | 5%      |
| Argentina    | 2         | 5%      |
| Venezuela    | 1         | 2.5%    |
| Switzerland  | 1         | 2.5%    |
| Sweden       | 1         | 2.5%    |
| Spain        | 1         | 2.5%    |
| South Africa | 1         | 2.5%    |
| Philippines  | 1         | 2.5%    |
| Lebanon      | 1         | 2.5%    |
| Japan        | 1         | 2.5%    |
| Czechia      | 1         | 2.5%    |
| Chile        | 1         | 2.5%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Wroclaw               | 1         | 2.33%   |
| Wenatchee             | 1         | 2.33%   |
| Tucson                | 1         | 2.33%   |
| Takahama              | 1         | 2.33%   |
| Surabaya              | 1         | 2.33%   |
| Spokane               | 1         | 2.33%   |
| SkellefteГҐ         | 1         | 2.33%   |
| Santa Barbara         | 1         | 2.33%   |
| San Antonio           | 1         | 2.33%   |
| Saint-Basile-le-Grand | 1         | 2.33%   |
| Rosario               | 1         | 2.33%   |
| Rio Claro             | 1         | 2.33%   |
| Pujaudran             | 1         | 2.33%   |
| Prague                | 1         | 2.33%   |
| Posadas               | 1         | 2.33%   |
| Pompano Beach         | 1         | 2.33%   |
| Pasig                 | 1         | 2.33%   |
| Paisley               | 1         | 2.33%   |
| Nasielsk              | 1         | 2.33%   |
| Montreuil             | 1         | 2.33%   |
| Montreal              | 1         | 2.33%   |
| Montagu               | 1         | 2.33%   |
| Mannheim              | 1         | 2.33%   |
| Leipzig               | 1         | 2.33%   |
| La Florida            | 1         | 2.33%   |
| Kruft                 | 1         | 2.33%   |
| KoЕ‚o              | 1         | 2.33%   |
| Houston               | 1         | 2.33%   |
| Grabs                 | 1         | 2.33%   |
| Glasgow               | 1         | 2.33%   |
| Givors                | 1         | 2.33%   |
| Frankfurt (Oder)      | 1         | 2.33%   |
| East Wenatchee        | 1         | 2.33%   |
| Dunoon                | 1         | 2.33%   |
| Dobrzen Wielki        | 1         | 2.33%   |
| Chicago               | 1         | 2.33%   |
| Birmingham            | 1         | 2.33%   |
| Belford Roxo          | 1         | 2.33%   |
| Beirut                | 1         | 2.33%   |
| Basingstoke           | 1         | 2.33%   |
| Barnsley              | 1         | 2.33%   |
| Bandung               | 1         | 2.33%   |
| AlcaÃ±iz            | 1         | 2.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 15     | 18.52%  |
| WDC                 | 9         | 11     | 16.67%  |
| Samsung Electronics | 9         | 11     | 16.67%  |
| Hitachi             | 5         | 6      | 9.26%   |
| Kingston            | 3         | 3      | 5.56%   |
| Unknown             | 2         | 2      | 3.7%    |
| Intel               | 2         | 2      | 3.7%    |
| GOODRAM             | 2         | 4      | 3.7%    |
| XPG                 | 1         | 1      | 1.85%   |
| SPCC                | 1         | 2      | 1.85%   |
| SanDisk             | 1         | 1      | 1.85%   |
| ORICO               | 1         | 1      | 1.85%   |
| Micron Technology   | 1         | 1      | 1.85%   |
| HGST                | 1         | 1      | 1.85%   |
| Gigabyte Technology | 1         | 1      | 1.85%   |
| Fujitsu             | 1         | 2      | 1.85%   |
| Crucial             | 1         | 1      | 1.85%   |
| ASUS-JM             | 1         | 1      | 1.85%   |
| asmedia             | 1         | 1      | 1.85%   |
| A-DATA Technology   | 1         | 1      | 1.85%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| WDC WD1600BEVT-22ZCT0 160GB              | 2         | 3.39%   |
| Samsung HD161GJ 160GB                    | 2         | 3.39%   |
| Hitachi HTS545025B9A300 250GB            | 2         | 3.39%   |
| XPG GAMMIX S11 Pro 512GB                 | 1         | 1.69%   |
| WDC WD800JD-08MSA1 80GB                  | 1         | 1.69%   |
| WDC WD5000BEVT-22ZAT0 500GB              | 1         | 1.69%   |
| WDC WD5000AVVS-63ZWB0 500GB              | 1         | 1.69%   |
| WDC WD3200BPVT-75ZEST0 320GB             | 1         | 1.69%   |
| WDC WD2500AAKX-07U6AA0 250GB             | 1         | 1.69%   |
| WDC WD1600AAJS-08L7A0 160GB              | 1         | 1.69%   |
| WDC WD10EZEX-60WN4A0 1TB                 | 1         | 1.69%   |
| Unknown MMC Card  64GB                   | 1         | 1.69%   |
| Unknown HBG4a2  32GB                     | 1         | 1.69%   |
| SPCC Solid State Disk 256GB              | 1         | 1.69%   |
| Seagate ST9500325AS 500GB                | 1         | 1.69%   |
| Seagate ST9250315AS 250GB                | 1         | 1.69%   |
| Seagate ST9160310AS 160GB                | 1         | 1.69%   |
| Seagate ST500LT012-1DG142 500GB          | 1         | 1.69%   |
| Seagate ST3500312CS 500GB                | 1         | 1.69%   |
| Seagate ST3320418AS 320GB                | 1         | 1.69%   |
| Seagate ST2000VM003-1ET164 2TB           | 1         | 1.69%   |
| Seagate ST1000LM048-2E7172 1TB           | 1         | 1.69%   |
| Seagate ST1000LM035-1RK172 1TB           | 1         | 1.69%   |
| Seagate ST1000LM024 HN-M101MBB 1TB       | 1         | 1.69%   |
| Seagate Backup+ Hub BK 4TB               | 1         | 1.69%   |
| Seagate Backup+ Desk 5TB                 | 1         | 1.69%   |
| SanDisk SSD PLUS 480GB                   | 1         | 1.69%   |
| Samsung SSD 850 EVO 500GB                | 1         | 1.69%   |
| Samsung SSD 850 EVO 250GB                | 1         | 1.69%   |
| Samsung SSD 840 Series 120GB             | 1         | 1.69%   |
| Samsung NVMe SSD Drive 256GB             | 1         | 1.69%   |
| Samsung MZVPV256HDGL-000H1 256GB         | 1         | 1.69%   |
| Samsung MZALQ512HALU-000L1 512GB         | 1         | 1.69%   |
| Samsung MZ7TD128HAFV-000L1 128GB SSD     | 1         | 1.69%   |
| Samsung HD753LJ 752GB                    | 1         | 1.69%   |
| Samsung HD154UI 1TB                      | 1         | 1.69%   |
| ORICO M200 1TB                           | 1         | 1.69%   |
| Micron MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 1.69%   |
| Kingston SV300S37A480G 480GB SSD         | 1         | 1.69%   |
| Kingston SA400S37120G 120GB SSD          | 1         | 1.69%   |
| Kingston SA400M8240G 240GB SSD           | 1         | 1.69%   |
| Intel SSDSA2BW120G3H 120GB               | 1         | 1.69%   |
| Intel SSDMAEXC024G3H 24GB                | 1         | 1.69%   |
| Hitachi HTS545025B9SA02 250GB            | 1         | 1.69%   |
| Hitachi HTS543232A7A384 320GB            | 1         | 1.69%   |
| Hitachi HTS541080G9SA00 80GB             | 1         | 1.69%   |
| HGST HTS545050A7E380 500GB               | 1         | 1.69%   |
| GOODRAM SSDPR-CX400-256-G2 256GB         | 1         | 1.69%   |
| GOODRAM SSDPR-CL100-240-G3 240GB         | 1         | 1.69%   |
| GOODRAM IR-SSDPR-S25A-120 120GB          | 1         | 1.69%   |
| Gigabyte GP-GSTFS31120GNTD 120GB         | 1         | 1.69%   |
| Fujitsu MHW2120BH 120GB                  | 1         | 1.69%   |
| Crucial CT250MX500SSD1 250GB             | 1         | 1.69%   |
| ASUS-JM S41 SSD 16GB                     | 1         | 1.69%   |
| asmedia ASMT1153e 1TB                    | 1         | 1.69%   |
| A-DATA SX8200NP 480GB                    | 1         | 1.69%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 14     | 33.33%  |
| WDC                 | 9         | 11     | 30%     |
| Hitachi             | 5         | 6      | 16.67%  |
| Samsung Electronics | 3         | 4      | 10%     |
| HGST                | 1         | 1      | 3.33%   |
| Fujitsu             | 1         | 2      | 3.33%   |
| asmedia             | 1         | 1      | 3.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 4      | 23.53%  |
| Kingston            | 3         | 3      | 17.65%  |
| Intel               | 2         | 2      | 11.76%  |
| GOODRAM             | 2         | 4      | 11.76%  |
| SPCC                | 1         | 2      | 5.88%   |
| SanDisk             | 1         | 1      | 5.88%   |
| Micron Technology   | 1         | 1      | 5.88%   |
| Gigabyte Technology | 1         | 1      | 5.88%   |
| Crucial             | 1         | 1      | 5.88%   |
| ASUS-JM             | 1         | 1      | 5.88%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 27        | 39     | 52.94%  |
| SSD     | 15        | 20     | 29.41%  |
| NVMe    | 5         | 5      | 9.8%    |
| MMC     | 2         | 2      | 3.92%   |
| Unknown | 2         | 2      | 3.92%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 37        | 56     | 80.43%  |
| NVMe | 5         | 5      | 10.87%  |
| SAS  | 2         | 5      | 4.35%   |
| MMC  | 2         | 2      | 4.35%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 33        | 47     | 82.5%   |
| 0.51-1.0   | 5         | 8      | 12.5%   |
| 3.01-4.0   | 1         | 3      | 2.5%    |
| 1.01-2.0   | 1         | 1      | 2.5%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 13        | 32.5%   |
| 501-1000       | 7         | 17.5%   |
| 251-500        | 6         | 15%     |
| 1-20           | 4         | 10%     |
| 51-100         | 3         | 7.5%    |
| 21-50          | 2         | 5%      |
| Unknown        | 2         | 5%      |
| More than 3000 | 1         | 2.5%    |
| 2001-3000      | 1         | 2.5%    |
| 1001-2000      | 1         | 2.5%    |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 19        | 45.24%  |
| 51-100         | 6         | 14.29%  |
| 21-50          | 5         | 11.9%   |
| 101-250        | 3         | 7.14%   |
| 501-1000       | 3         | 7.14%   |
| 251-500        | 2         | 4.76%   |
| Unknown        | 2         | 4.76%   |
| More than 3000 | 1         | 2.38%   |
| 1001-2000      | 1         | 2.38%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


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

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| WDC               | 4         | 4      | 50%     |
| Seagate           | 2         | 2      | 25%     |
| Micron Technology | 1         | 1      | 12.5%   |
| asmedia           | 1         | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 4         | 4      | 57.14%  |
| Seagate | 2         | 2      | 28.57%  |
| asmedia | 1         | 1      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 22        | 36     | 48.89%  |
| Detected | 15        | 24     | 33.33%  |
| Malfunc  | 8         | 8      | 17.78%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 28        | 63.64%  |
| AMD                      | 6         | 13.64%  |
| Samsung Electronics      | 3         | 6.82%   |
| Nvidia                   | 2         | 4.55%   |
| VIA Technologies         | 1         | 2.27%   |
| Silicon Motion           | 1         | 2.27%   |
| Marvell Technology Group | 1         | 2.27%   |
| JMicron Technology       | 1         | 2.27%   |
| ADATA Technology         | 1         | 2.27%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 4         | 7.27%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 3         | 5.45%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 3         | 5.45%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 3.64%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 2         | 3.64%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 3.64%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 2         | 3.64%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 2         | 3.64%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 2         | 3.64%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 3.64%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 3.64%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                      | 1         | 1.82%   |
| VIA VT8237A SATA 2-Port Controller                                               | 1         | 1.82%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 1         | 1.82%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 1         | 1.82%   |
| Nvidia MCP61 SATA Controller                                                     | 1         | 1.82%   |
| Nvidia MCP61 IDE                                                                 | 1         | 1.82%   |
| Nvidia MCP51 Serial ATA Controller                                               | 1         | 1.82%   |
| Nvidia MCP51 IDE                                                                 | 1         | 1.82%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                        | 1         | 1.82%   |
| JMicron JMB360 AHCI Controller                                                   | 1         | 1.82%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 1         | 1.82%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 1.82%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 1.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 1.82%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 1.82%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 1         | 1.82%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 1         | 1.82%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 1         | 1.82%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 1         | 1.82%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 1.82%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 1.82%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1         | 1.82%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 1         | 1.82%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 1         | 1.82%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 1         | 1.82%   |
| AMD X370 Series Chipset SATA Controller                                          | 1         | 1.82%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 1         | 1.82%   |
| AMD 400 Series Chipset SATA Controller                                           | 1         | 1.82%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 1         | 1.82%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 27        | 57.45%  |
| IDE  | 14        | 29.79%  |
| NVMe | 5         | 10.64%  |
| RAID | 1         | 2.13%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 31        | 77.5%   |
| AMD    | 9         | 22.5%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Atom CPU N280 @ 1.66GHz                 | 2         | 5%      |
| Intel Atom CPU N270 @ 1.60GHz                 | 2         | 5%      |
| Intel Pentium Gold G5400 CPU @ 3.70GHz        | 1         | 2.5%    |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz   | 1         | 2.5%    |
| Intel Pentium CPU B950 @ 2.10GHz              | 1         | 2.5%    |
| Intel Genuine CPU T2400 @ 1.83GHz             | 1         | 2.5%    |
| Intel Core i7-4600U CPU @ 2.10GHz             | 1         | 2.5%    |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 1         | 2.5%    |
| Intel Core i7-3612QM CPU @ 2.10GHz            | 1         | 2.5%    |
| Intel Core i7 CPU 860 @ 2.80GHz               | 1         | 2.5%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 2.5%    |
| Intel Core i5-6500 CPU @ 3.20GHz              | 1         | 2.5%    |
| Intel Core i5-4460 CPU @ 3.20GHz              | 1         | 2.5%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 2.5%    |
| Intel Core i5-10400 CPU @ 2.90GHz             | 1         | 2.5%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 2.5%    |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 1         | 2.5%    |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 1         | 2.5%    |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 1         | 2.5%    |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 1         | 2.5%    |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 1         | 2.5%    |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 1         | 2.5%    |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz          | 1         | 2.5%    |
| Intel Core 2 CPU T5600 @ 1.83GHz              | 1         | 2.5%    |
| Intel Celeron CPU N3160 @ 1.60GHz             | 1         | 2.5%    |
| Intel Celeron CPU N3050 @ 1.60GHz             | 1         | 2.5%    |
| Intel Celeron CPU N2840 @ 2.16GHz             | 1         | 2.5%    |
| Intel Celeron CPU 900 @ 2.20GHz               | 1         | 2.5%    |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 1         | 2.5%    |
| AMD Turion 64 X2 Mobile Technology TL-64      | 1         | 2.5%    |
| AMD Sempron 145 Processor                     | 1         | 2.5%    |
| AMD Ryzen 7 1800X Eight-Core Processor        | 1         | 2.5%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 2.5%    |
| AMD Ryzen 3 3100 4-Core Processor             | 1         | 2.5%    |
| AMD PRO A8-8600B R6, 10 Compute Cores 4C+6G   | 1         | 2.5%    |
| AMD C-50 Processor                            | 1         | 2.5%    |
| AMD Athlon II X2 B22 Processor                | 1         | 2.5%    |
| AMD A6-7480 Radeon R5, 8 Compute Cores 2C+6G  | 1         | 2.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 7         | 17.5%   |
| Intel Atom              | 5         | 12.5%   |
| Intel Core i7           | 4         | 10%     |
| Intel Core 2 Duo        | 4         | 10%     |
| Intel Celeron           | 4         | 10%     |
| Intel Pentium Gold      | 1         | 2.5%    |
| Intel Pentium Dual-Core | 1         | 2.5%    |
| Intel Pentium           | 1         | 2.5%    |
| Intel Genuine           | 1         | 2.5%    |
| Intel Core i3           | 1         | 2.5%    |
| Intel Core 2 Quad       | 1         | 2.5%    |
| Intel Core 2            | 1         | 2.5%    |
| AMD Turion 64 X2 Mobile | 1         | 2.5%    |
| AMD Sempron             | 1         | 2.5%    |
| AMD Ryzen 7             | 1         | 2.5%    |
| AMD Ryzen 5             | 1         | 2.5%    |
| AMD Ryzen 3             | 1         | 2.5%    |
| AMD PRO A8              | 1         | 2.5%    |
| AMD C-50                | 1         | 2.5%    |
| AMD Athlon II X2        | 1         | 2.5%    |
| AMD A6                  | 1         | 2.5%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 19        | 47.5%   |
| 4      | 12        | 30%     |
| 1      | 7         | 17.5%   |
| 8      | 1         | 2.5%    |
| 6      | 1         | 2.5%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 40        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 21        | 52.5%   |
| 2      | 19        | 47.5%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 35        | 87.5%   |
| 32-bit         | 5         | 12.5%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 8         | 20%     |
| 0x406c4    | 2         | 5%      |
| 0x306a9    | 2         | 5%      |
| 0x206a7    | 2         | 5%      |
| 0x20655    | 2         | 5%      |
| 0x106c2    | 2         | 5%      |
| 0x1067a    | 2         | 5%      |
| 0x0600611a | 2         | 5%      |
| 0xa0653    | 1         | 2.5%    |
| 0x806ec    | 1         | 2.5%    |
| 0x806ea    | 1         | 2.5%    |
| 0x6fd      | 1         | 2.5%    |
| 0x6fb      | 1         | 2.5%    |
| 0x6f2      | 1         | 2.5%    |
| 0x506e3    | 1         | 2.5%    |
| 0x406c3    | 1         | 2.5%    |
| 0x40651    | 1         | 2.5%    |
| 0x306c3    | 1         | 2.5%    |
| 0x30678    | 1         | 2.5%    |
| 0x106e5    | 1         | 2.5%    |
| 0x10676    | 1         | 2.5%    |
| 0x08701021 | 1         | 2.5%    |
| 0x08108109 | 1         | 2.5%    |
| 0x08001138 | 1         | 2.5%    |
| 0x05000029 | 1         | 2.5%    |
| 0x010000c8 | 1         | 2.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Silvermont  | 4         | 10%     |
| Penryn      | 4         | 10%     |
| Core        | 4         | 10%     |
| Bonnell     | 4         | 10%     |
| KabyLake    | 3         | 7.5%    |
| Westmere    | 2         | 5%      |
| SandyBridge | 2         | 5%      |
| K10         | 2         | 5%      |
| IvyBridge   | 2         | 5%      |
| Haswell     | 2         | 5%      |
| Excavator   | 2         | 5%      |
| Zen+        | 1         | 2.5%    |
| Zen 2       | 1         | 2.5%    |
| Zen         | 1         | 2.5%    |
| Skylake     | 1         | 2.5%    |
| P6          | 1         | 2.5%    |
| Nehalem     | 1         | 2.5%    |
| K8 Hammer   | 1         | 2.5%    |
| CometLake   | 1         | 2.5%    |
| Bobcat      | 1         | 2.5%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Intel            | 24        | 57.14%  |
| AMD              | 10        | 23.81%  |
| Nvidia           | 7         | 16.67%  |
| VIA Technologies | 1         | 2.38%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 4         | 8.51%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 3         | 6.38%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 6.38%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 4.26%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 4.26%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 4.26%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 4.26%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 1         | 2.13%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 2.13%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1         | 2.13%   |
| Nvidia GK104GLM [Quadro K3000M]                                                          | 1         | 2.13%   |
| Nvidia GF108M [GeForce GT 420M]                                                          | 1         | 2.13%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 2.13%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 1         | 2.13%   |
| Nvidia C51 [GeForce Go 6150]                                                             | 1         | 2.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1         | 2.13%   |
| Intel UHD Graphics 620                                                                   | 1         | 2.13%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 2.13%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 2.13%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 2.13%   |
| Intel HD Graphics 530                                                                    | 1         | 2.13%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 2.13%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 2.13%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 2.13%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1         | 2.13%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                                | 1         | 2.13%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 2.13%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1         | 2.13%   |
| AMD Wrestler [Radeon HD 6250]                                                            | 1         | 2.13%   |
| AMD RV515/M54 [Mobility Radeon X1400]                                                    | 1         | 2.13%   |
| AMD RS880 [Radeon HD 4200]                                                               | 1         | 2.13%   |
| AMD Redwood LE [Radeon HD 5550/5570/5630/6390/6490/7570]                                 | 1         | 2.13%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1         | 2.13%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 1         | 2.13%   |
| AMD Barts PRO [Radeon HD 6850]                                                           | 1         | 2.13%   |
| AMD Barts LE [Radeon HD 6790]                                                            | 1         | 2.13%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 23        | 57.5%   |
| 1 x AMD        | 9         | 22.5%   |
| 1 x Nvidia     | 6         | 15%     |
| 1 x VIA        | 1         | 2.5%    |
| Intel + Nvidia | 1         | 2.5%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 36        | 90%     |
| Proprietary | 2         | 5%      |
| Unknown     | 2         | 5%      |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 28        | 70%     |
| 0.01-0.5   | 5         | 12.5%   |
| 1.01-2.0   | 3         | 7.5%    |
| 0.51-1.0   | 2         | 5%      |
| 7.01-8.0   | 1         | 2.5%    |
| 3.01-4.0   | 1         | 2.5%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 6         | 15%     |
| LG Display          | 6         | 15%     |
| Goldstar            | 3         | 7.5%    |
| Dell                | 3         | 7.5%    |
| AU Optronics        | 3         | 7.5%    |
| Lenovo              | 2         | 5%      |
| CPT                 | 2         | 5%      |
| Chimei Innolux      | 2         | 5%      |
| BenQ                | 2         | 5%      |
| AOC                 | 2         | 5%      |
| Unknown             | 1         | 2.5%    |
| LG Philips          | 1         | 2.5%    |
| JCH                 | 1         | 2.5%    |
| Insignia            | 1         | 2.5%    |
| Hitachi             | 1         | 2.5%    |
| HannStar            | 1         | 2.5%    |
| BOE                 | 1         | 2.5%    |
| Apple               | 1         | 2.5%    |
| Acer                | 1         | 2.5%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch            | 1         | 2.33%   |
| Samsung Electronics SyncMaster SAM0581 1920x1080 477x268mm 21.5-inch | 1         | 2.33%   |
| Samsung Electronics SyncMaster SAM0116 1024x768 267x200mm 13.1-inch  | 1         | 2.33%   |
| Samsung Electronics S24D330 SAM0D93 1920x1080 531x299mm 24.0-inch    | 1         | 2.33%   |
| Samsung Electronics S22C450 SAM09C5 1920x1080 477x268mm 21.5-inch    | 1         | 2.33%   |
| Samsung Electronics LCD Monitor SEC4F45 1280x800 331x207mm 15.4-inch | 1         | 2.33%   |
| Samsung Electronics LCD Monitor SEC4141 1366x768 344x193mm 15.5-inch | 1         | 2.33%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 1         | 2.33%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch          | 1         | 2.33%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch        | 1         | 2.33%   |
| LG Display LCD Monitor LGD059E 1920x1080 382x215mm 17.3-inch         | 1         | 2.33%   |
| LG Display LCD Monitor LGD04E1 1366x768 344x194mm 15.5-inch          | 1         | 2.33%   |
| LG Display LCD Monitor LGD02E1 1600x900 382x215mm 17.3-inch          | 1         | 2.33%   |
| LG Display LCD Monitor LGD0266 1366x768 344x194mm 15.5-inch          | 1         | 2.33%   |
| LG Display LCD Monitor LGD01C5 1366x768 293x165mm 13.2-inch          | 1         | 2.33%   |
| Lenovo LCD Monitor LEN4033 1440x900 304x190mm 14.1-inch              | 1         | 2.33%   |
| Lenovo LCD Monitor LEN4022 1400x1050 287x215mm 14.1-inch             | 1         | 2.33%   |
| JCH F24 JCH1919 1920x1080 520x310mm 23.8-inch                        | 1         | 2.33%   |
| Insignia NS-32D312NA15 BBY0032 1680x1050 640x384mm 29.4-inch         | 1         | 2.33%   |
| Hitachi HDMI HEC0088 1920x540                                        | 1         | 2.33%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch             | 1         | 2.33%   |
| Goldstar W2043 GSM4E9D 1600x900 450x250mm 20.3-inch                  | 1         | 2.33%   |
| Goldstar T710SH GSM436B 1280x960 310x230mm 15.2-inch                 | 1         | 2.33%   |
| Goldstar L1953H GSM4B3D 1280x1024 338x270mm 17.0-inch                | 1         | 2.33%   |
| Goldstar 23MP55 GSM5A23 1920x1080 510x290mm 23.1-inch                | 1         | 2.33%   |
| Dell LCD Monitor S2715H 3840x1080                                    | 1         | 2.33%   |
| Dell LCD Monitor S2715H                                              | 1         | 2.33%   |
| Dell IN1930 DELF03B 1366x768 410x230mm 18.5-inch                     | 1         | 2.33%   |
| Dell E176FP DELA014 1280x1024 338x270mm 17.0-inch                    | 1         | 2.33%   |
| CPT LCD Monitor CPT04CE 1024x600 222x130mm 10.1-inch                 | 1         | 2.33%   |
| CPT LCD Monitor CPT04C4 1024x600 222x130mm 10.1-inch                 | 1         | 2.33%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch     | 1         | 2.33%   |
| Chimei Innolux LCD Monitor CMN1484 1600x900 310x174mm 14.0-inch      | 1         | 2.33%   |
| BOE LCD Monitor BOE085E 1920x1080 344x194mm 15.5-inch                | 1         | 2.33%   |
| BenQ FP202WA BNQ76C2 1680x1050 430x270mm 20.0-inch                   | 1         | 2.33%   |
| BenQ E900HD BNQ7910 1366x768 410x230mm 18.5-inch                     | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch       | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch        | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch       | 1         | 2.33%   |
| Apple Color LCD APP9C5E 1280x800 286x178mm 13.3-inch                 | 1         | 2.33%   |
| AOC LM729 AOCA784 1280x1024 340x270mm 17.1-inch                      | 1         | 2.33%   |
| AOC 2450W AOC2450 1920x1080 521x293mm 23.5-inch                      | 1         | 2.33%   |
| Acer S232HL ACR0203 1920x1080 510x290mm 23.1-inch                    | 1         | 2.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 13        | 30.23%  |
| 1366x768 (WXGA)    | 7         | 16.28%  |
| 1600x900 (HD+)     | 4         | 9.3%    |
| 1280x1024 (SXGA)   | 3         | 6.98%   |
| 1024x600           | 3         | 6.98%   |
| 1920x540           | 2         | 4.65%   |
| 1440x900 (WXGA+)   | 2         | 4.65%   |
| 1280x800 (WXGA)    | 2         | 4.65%   |
| 3840x1080          | 1         | 2.33%   |
| 2288x1287          | 1         | 2.33%   |
| 1680x1050 (WSXGA+) | 1         | 2.33%   |
| 1400x1050          | 1         | 2.33%   |
| 1280x960           | 1         | 2.33%   |
| 1024x768 (XGA)     | 1         | 2.33%   |
| Unknown            | 1         | 2.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 17      | 9         | 21.43%  |
| 15      | 7         | 16.67%  |
| 23      | 5         | 11.9%   |
| 14      | 3         | 7.14%   |
| 13      | 3         | 7.14%   |
| 10      | 3         | 7.14%   |
| 48      | 2         | 4.76%   |
| 21      | 2         | 4.76%   |
| 20      | 2         | 4.76%   |
| 18      | 2         | 4.76%   |
| 142     | 1         | 2.38%   |
| 24      | 1         | 2.38%   |
| 16      | 1         | 2.38%   |
| Unknown | 1         | 2.38%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 13        | 30.95%  |
| 201-300        | 7         | 16.67%  |
| 501-600        | 6         | 14.29%  |
| 401-500        | 6         | 14.29%  |
| 351-400        | 6         | 14.29%  |
| 1001-1500      | 2         | 4.76%   |
| More than 2000 | 1         | 2.38%   |
| Unknown        | 1         | 2.38%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 27        | 64.29%  |
| 16/10   | 5         | 11.9%   |
| 5/4     | 3         | 7.14%   |
| 4/3     | 3         | 7.14%   |
| 1.96    | 2         | 4.76%   |
| 1.00    | 1         | 2.38%   |
| Unknown | 1         | 2.38%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 7         | 16.67%  |
| 201-250        | 6         | 14.29%  |
| 121-130        | 6         | 14.29%  |
| 141-150        | 5         | 11.9%   |
| 151-200        | 4         | 9.52%   |
| 81-90          | 3         | 7.14%   |
| 41-50          | 3         | 7.14%   |
| 71-80          | 2         | 4.76%   |
| 501-1000       | 2         | 4.76%   |
| More than 1000 | 1         | 2.38%   |
| 131-140        | 1         | 2.38%   |
| 91-100         | 1         | 2.38%   |
| Unknown        | 1         | 2.38%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 15        | 37.5%   |
| 101-120 | 13        | 32.5%   |
| 121-160 | 8         | 20%     |
| 1-50    | 3         | 7.5%    |
| Unknown | 1         | 2.5%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 36        | 90%     |
| 2     | 4         | 10%     |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 17        | 29.31%  |
| Intel                    | 14        | 24.14%  |
| Qualcomm Atheros         | 10        | 17.24%  |
| Broadcom Limited         | 4         | 6.9%    |
| TP-Link                  | 2         | 3.45%   |
| Ralink Technology        | 2         | 3.45%   |
| Nvidia                   | 2         | 3.45%   |
| Marvell Technology Group | 2         | 3.45%   |
| Broadcom                 | 2         | 3.45%   |
| VIA Technologies         | 1         | 1.72%   |
| Ralink                   | 1         | 1.72%   |
| D-Link System            | 1         | 1.72%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                                       | Computers | Percent |
|---------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                           | 12        | 17.65%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                       | 5         | 7.35%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                              | 2         | 2.94%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                              | 2         | 2.94%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                     | 2         | 2.94%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                       | 2         | 2.94%   |
| VIA VT6102/VT6103 [Rhine-II]                                                                | 1         | 1.47%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                         | 1         | 1.47%   |
| TP-Link 802.11ac WLAN Adapter                                                               | 1         | 1.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                    | 1         | 1.47%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                             | 1         | 1.47%   |
| Ralink RT5370 Wireless Adapter                                                              | 1         | 1.47%   |
| Ralink RT3072 Wireless Adapter                                                              | 1         | 1.47%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                   | 1         | 1.47%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                  | 1         | 1.47%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                                   | 1         | 1.47%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                            | 1         | 1.47%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                              | 1         | 1.47%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                                       | 1         | 1.47%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]               | 1         | 1.47%   |
| Nvidia MCP61 Ethernet                                                                       | 1         | 1.47%   |
| Nvidia MCP51 Ethernet Controller                                                            | 1         | 1.47%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                                     | 1         | 1.47%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                                        | 1         | 1.47%   |
| Intel Wireless 8260                                                                         | 1         | 1.47%   |
| Intel Wireless 7265                                                                         | 1         | 1.47%   |
| Intel Wireless 7260                                                                         | 1         | 1.47%   |
| Intel Wireless 3165                                                                         | 1         | 1.47%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                                     | 1         | 1.47%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                               | 1         | 1.47%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                       | 1         | 1.47%   |
| Intel I211 Gigabit Network Connection                                                       | 1         | 1.47%   |
| Intel Ethernet Connection I218-LM                                                           | 1         | 1.47%   |
| Intel Ethernet Connection (2) I219-LM                                                       | 1         | 1.47%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                           | 1         | 1.47%   |
| Intel Centrino Wireless-N 2230                                                              | 1         | 1.47%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                                | 1         | 1.47%   |
| Intel Centrino Ultimate-N 6300                                                              | 1         | 1.47%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                | 1         | 1.47%   |
| Intel 82573L Gigabit Ethernet Controller                                                    | 1         | 1.47%   |
| Intel 82566MM Gigabit Network Connection                                                    | 1         | 1.47%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                                        | 1         | 1.47%   |
| D-Link System DWA-160 802.11abgn Xtreme N Dual Band Adapter(rev.A2) [Atheros AR9170+AR9104] | 1         | 1.47%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                                            | 1         | 1.47%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                             | 1         | 1.47%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe                                    | 1         | 1.47%   |
| Broadcom Limited NetLink BCM57788 Gigabit Ethernet PCIe                                     | 1         | 1.47%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter                                 | 1         | 1.47%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                                   | 1         | 1.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 12        | 40%     |
| Qualcomm Atheros      | 8         | 26.67%  |
| TP-Link               | 2         | 6.67%   |
| Realtek Semiconductor | 2         | 6.67%   |
| Ralink Technology     | 2         | 6.67%   |
| Broadcom Limited      | 2         | 6.67%   |
| Ralink                | 1         | 3.33%   |
| D-Link System         | 1         | 3.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                                       | Computers | Percent |
|---------------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                              | 2         | 6.67%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                     | 2         | 6.67%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                         | 1         | 3.33%   |
| TP-Link 802.11ac WLAN Adapter                                                               | 1         | 3.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                    | 1         | 3.33%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                             | 1         | 3.33%   |
| Ralink RT5370 Wireless Adapter                                                              | 1         | 3.33%   |
| Ralink RT3072 Wireless Adapter                                                              | 1         | 3.33%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                   | 1         | 3.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                  | 1         | 3.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                            | 1         | 3.33%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                              | 1         | 3.33%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]               | 1         | 3.33%   |
| Intel Wireless 8260                                                                         | 1         | 3.33%   |
| Intel Wireless 7265                                                                         | 1         | 3.33%   |
| Intel Wireless 7260                                                                         | 1         | 3.33%   |
| Intel Wireless 3165                                                                         | 1         | 3.33%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                                     | 1         | 3.33%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                               | 1         | 3.33%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                       | 1         | 3.33%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                           | 1         | 3.33%   |
| Intel Centrino Wireless-N 2230                                                              | 1         | 3.33%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                                | 1         | 3.33%   |
| Intel Centrino Ultimate-N 6300                                                              | 1         | 3.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                | 1         | 3.33%   |
| D-Link System DWA-160 802.11abgn Xtreme N Dual Band Adapter(rev.A2) [Atheros AR9170+AR9104] | 1         | 3.33%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter                                 | 1         | 3.33%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                                   | 1         | 3.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 17        | 44.74%  |
| Intel                    | 8         | 21.05%  |
| Qualcomm Atheros         | 4         | 10.53%  |
| Nvidia                   | 2         | 5.26%   |
| Marvell Technology Group | 2         | 5.26%   |
| Broadcom Limited         | 2         | 5.26%   |
| Broadcom                 | 2         | 5.26%   |
| VIA Technologies         | 1         | 2.63%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 12        | 31.58%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 13.16%  |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 5.26%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 5.26%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 2.63%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 2.63%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 2.63%   |
| Nvidia MCP61 Ethernet                                             | 1         | 2.63%   |
| Nvidia MCP51 Ethernet Controller                                  | 1         | 2.63%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 2.63%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 2.63%   |
| Intel I211 Gigabit Network Connection                             | 1         | 2.63%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 2.63%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 2.63%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 2.63%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 2.63%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 1         | 2.63%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1         | 2.63%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 2.63%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1         | 2.63%   |
| Broadcom Limited NetLink BCM57788 Gigabit Ethernet PCIe           | 1         | 2.63%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 37        | 56.06%  |
| WiFi     | 29        | 43.94%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 24        | 50%     |
| Ethernet | 24        | 50%     |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 23        | 57.5%   |
| 1     | 17        | 42.5%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 36        | 85.71%  |
| Yes  | 6         | 14.29%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 6         | 35.29%  |
| Broadcom                        | 3         | 17.65%  |
| Realtek Semiconductor           | 2         | 11.76%  |
| Qualcomm Atheros Communications | 2         | 11.76%  |
| Dell                            | 1         | 5.88%   |
| Cambridge Silicon Radio         | 1         | 5.88%   |
| ASUSTek Computer                | 1         | 5.88%   |
| Apple                           | 1         | 5.88%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 4         | 23.53%  |
| Realtek RTL8723B Bluetooth                          | 1         | 5.88%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 5.88%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 5.88%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 5.88%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 5.88%   |
| Intel Bluetooth Device                              | 1         | 5.88%   |
| Dell Wireless 365 Bluetooth                         | 1         | 5.88%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 5.88%   |
| Broadcom HP Portable SoftSailing                    | 1         | 5.88%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 1         | 5.88%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 5.88%   |
| ASUS Broadcom Bluetooth 2.1                         | 1         | 5.88%   |
| Apple Bluetooth HCI                                 | 1         | 5.88%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Intel              | 29        | 60.42%  |
| AMD                | 9         | 18.75%  |
| Nvidia             | 6         | 12.5%   |
| VIA Technologies   | 1         | 2.08%   |
| Plantronics        | 1         | 2.08%   |
| Native Instruments | 1         | 2.08%   |
| Focusrite-Novation | 1         | 2.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7         | 12.5%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 5.36%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 5.36%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 3.57%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 2         | 3.57%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 3.57%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 3.57%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 3.57%   |
| AMD Barts HDMI Audio [Radeon HD 6790/6850/6870 / 7720 OEM]                                        | 2         | 3.57%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1         | 1.79%   |
| Plantronics USB DSP v4 Audio Interface                                                            | 1         | 1.79%   |
| Nvidia MCP61 High Definition Audio                                                                | 1         | 1.79%   |
| Nvidia MCP51 High Definition Audio                                                                | 1         | 1.79%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 1.79%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 1.79%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 1.79%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 1.79%   |
| Native Instruments KOMPLETE KONTROL M32                                                           | 1         | 1.79%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 1.79%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 1         | 1.79%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 1.79%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 1         | 1.79%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 1.79%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 1.79%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 1         | 1.79%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 1         | 1.79%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 1.79%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 1.79%   |
| Intel 200 Series PCH HD Audio                                                                     | 1         | 1.79%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 1.79%   |
| Focusrite-Novation Focusrite Scarlett 2i2 2nd Gen                                                 | 1         | 1.79%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 1.79%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 1         | 1.79%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 1         | 1.79%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 1.79%   |
| AMD Navi 10 HDMI Audio                                                                            | 1         | 1.79%   |
| AMD FCH Azalia Controller                                                                         | 1         | 1.79%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 1         | 1.79%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 1         | 1.79%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 1.79%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 7         | 22.58%  |
| Samsung Electronics | 6         | 19.35%  |
| SK Hynix            | 3         | 9.68%   |
| Kingston            | 3         | 9.68%   |
| Nanya Technology    | 2         | 6.45%   |
| Micron Technology   | 2         | 6.45%   |
| G.Skill             | 2         | 6.45%   |
| Corsair             | 2         | 6.45%   |
| GOODRAM             | 1         | 3.23%   |
| Elpida              | 1         | 3.23%   |
| Crucial             | 1         | 3.23%   |
| Avant               | 1         | 3.23%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB DIMM 800MT/s                   | 2         | 6.06%   |
| Unknown RAM Module 2GB SODIMM SDRAM                      | 1         | 3.03%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                 | 1         | 3.03%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s              | 1         | 3.03%   |
| Unknown RAM Module 1024MB SODIMM DDR2                    | 1         | 3.03%   |
| Unknown RAM Module 1024MB SODIMM 800MT/s                 | 1         | 3.03%   |
| Unknown RAM Module 1024MB DIMM SDRAM                     | 1         | 3.03%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1066MT/s             | 1         | 3.03%   |
| SK Hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s  | 1         | 3.03%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s   | 1         | 3.03%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s    | 1         | 3.03%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s    | 1         | 3.03%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s    | 1         | 3.03%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s    | 1         | 3.03%   |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1334MT/s    | 1         | 3.03%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s | 1         | 3.03%   |
| Samsung RAM K4E8E324EB-EGCF 2GB LPDDR3 1867MT/s          | 1         | 3.03%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4096MB SODIMM DDR3 1600MT/s  | 1         | 3.03%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s     | 1         | 3.03%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s    | 1         | 3.03%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s   | 1         | 3.03%   |
| Kingston RAM Module 16GB SODIMM DDR4 2133MT/s            | 1         | 3.03%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s      | 1         | 3.03%   |
| Kingston RAM ACR128X64D3S1333C9 1GB SODIMM DDR3 1333MT/s | 1         | 3.03%   |
| GOODRAM RAM GR1600S3V64L11/8G 8GB SODIMM DDR3 1600MT/s   | 1         | 3.03%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s       | 1         | 3.03%   |
| G.Skill RAM F4-2400C16-16GRS 16GB SODIMM DDR4 2667MT/s   | 1         | 3.03%   |
| Elpida RAM EBJ81UG8BAS0-DJ-F 8GB SODIMM DDR3 1333MT/s    | 1         | 3.03%   |
| Crucial RAM BLS8G3D1609DS1S00. 8192MB DIMM DDR3 1600MT/s | 1         | 3.03%   |
| Corsair RAM CMZ4GX3M1A1600C9 4096MB DIMM DDR3 1600MT/s   | 1         | 3.03%   |
| Corsair RAM CMSA4GX3M1A1333C9 4GB SODIMM DDR3 1333MT/s   | 1         | 3.03%   |
| Avant RAM W641GU49J2320N6 8GB DIMM DDR4 2666MT/s         | 1         | 3.03%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 15        | 51.72%  |
| DDR4    | 5         | 17.24%  |
| SDRAM   | 3         | 10.34%  |
| Unknown | 3         | 10.34%  |
| DDR2    | 2         | 6.9%    |
| LPDDR3  | 1         | 3.45%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SODIMM  | 18        | 64.29%  |
| DIMM    | 9         | 32.14%  |
| Unknown | 1         | 3.57%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 2048  | 9         | 28.13%  |
| 8192  | 8         | 25%     |
| 4096  | 8         | 25%     |
| 1024  | 4         | 12.5%   |
| 16384 | 3         | 9.38%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 9         | 30%     |
| 800     | 4         | 13.33%  |
| 1333    | 3         | 10%     |
| Unknown | 3         | 10%     |
| 2667    | 2         | 6.67%   |
| 1334    | 2         | 6.67%   |
| 4199    | 1         | 3.33%   |
| 3200    | 1         | 3.33%   |
| 2666    | 1         | 3.33%   |
| 2400    | 1         | 3.33%   |
| 2133    | 1         | 3.33%   |
| 1867    | 1         | 3.33%   |
| 1066    | 1         | 3.33%   |

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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 7         | 33.33%  |
| Microdia                      | 4         | 19.05%  |
| Sunplus Innovation Technology | 2         | 9.52%   |
| Logitech                      | 2         | 9.52%   |
| Acer                          | 2         | 9.52%   |
| Z-Star Microelectronics       | 1         | 4.76%   |
| Suyin                         | 1         | 4.76%   |
| Samsung Electronics           | 1         | 4.76%   |
| Microsoft                     | 1         | 4.76%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Z-Star Namuga 1.3M Webcam                                   | 1         | 4.76%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 4.76%   |
| Sunplus Integrated Webcam                                   | 1         | 4.76%   |
| Sunplus HP HD Webcam [Fixed]                                | 1         | 4.76%   |
| Samsung Galaxy A5 (MTP)                                     | 1         | 4.76%   |
| Microsoft LifeCam Cinema                                    | 1         | 4.76%   |
| Microdia Sonix USB 2.0 Camera                               | 1         | 4.76%   |
| Microdia Lenovo EasyCamera                                  | 1         | 4.76%   |
| Microdia Laptop_Integrated_Webcam_HD                        | 1         | 4.76%   |
| Microdia Laptop_Integrated_Webcam_1.3M                      | 1         | 4.76%   |
| Logitech Webcam C270                                        | 1         | 4.76%   |
| Logitech QuickCam Notebook Pro                              | 1         | 4.76%   |
| Chicony Integrated Camera (1280x720@30)                     | 1         | 4.76%   |
| Chicony HP TrueVision HD Camera                             | 1         | 4.76%   |
| Chicony HP Integrated Webcam                                | 1         | 4.76%   |
| Chicony HP HD Webcam                                        | 1         | 4.76%   |
| Chicony HD WebCam                                           | 1         | 4.76%   |
| Chicony Asus Integrated 0.3M UVC Webcam                     | 1         | 4.76%   |
| Chicony 2.0M UVC Webcam / CNF7129                           | 1         | 4.76%   |
| Acer Lenovo EasyCamera                                      | 1         | 4.76%   |
| Acer HP Webcam                                              | 1         | 4.76%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Validity Sensors   | 2         | 66.67%  |
| STMicroelectronics | 1         | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Validity Sensors VFS491                    | 1         | 33.33%  |
| Validity Sensors VFS101 Fingerprint Reader | 1         | 33.33%  |
| STMicroelectronics Fingerprint Reader      | 1         | 33.33%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 30        | 75%     |
| 1     | 7         | 17.5%   |
| 2     | 3         | 7.5%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Net/wireless          | 3         | 23.08%  |
| Graphics card         | 3         | 23.08%  |
| Fingerprint reader    | 3         | 23.08%  |
| Multimedia controller | 2         | 15.38%  |
| Chipcard              | 1         | 7.69%   |
| Camera                | 1         | 7.69%   |

