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

Total: 68

| Vendor    | Model                       | Form-Factor | Probe                                                      | Date         |
|-----------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Foxconn   | 2ABF                        | Desktop     | [09a9309a2a](https://linux-hardware.org/?probe=09a9309a2a) | Nov 30, 2022 |
| Foxconn   | 2ABF                        | Desktop     | [b585d891a8](https://linux-hardware.org/?probe=b585d891a8) | Nov 30, 2022 |
| Apple     | MacBook1,1                  | Notebook    | [6945006338](https://linux-hardware.org/?probe=6945006338) | Nov 15, 2022 |
| Google    | Swanky                      | Notebook    | [1a0a358398](https://linux-hardware.org/?probe=1a0a358398) | Nov 15, 2022 |
| ASUSTek   | G20AJ                       | Desktop     | [7e1557713a](https://linux-hardware.org/?probe=7e1557713a) | Sep 06, 2022 |
| ASUSTek   | M70Vn                       | Notebook    | [236d8cb74e](https://linux-hardware.org/?probe=236d8cb74e) | Aug 29, 2022 |
| Gigabyte  | X570S AORUS PRO AX          | Desktop     | [4fb948980f](https://linux-hardware.org/?probe=4fb948980f) | Aug 25, 2022 |
| HUAWEI    | HVY-WXX9                    | Notebook    | [b4006730ce](https://linux-hardware.org/?probe=b4006730ce) | Jul 17, 2022 |
| ASUSTek   | CROSSHAIR VI HERO           | Desktop     | [f5e7afea43](https://linux-hardware.org/?probe=f5e7afea43) | Jul 05, 2022 |
| Intel     | H61                         | Desktop     | [bf862f44d2](https://linux-hardware.org/?probe=bf862f44d2) | Jun 11, 2022 |
| HP        | Stream Notebook PC 13       | Notebook    | [47b55dbb68](https://linux-hardware.org/?probe=47b55dbb68) | Jun 06, 2022 |
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
| Sparky 6    | 16        | 29.63%  |
| Sparky 7    | 8         | 14.81%  |
| Sparky 6.1  | 6         | 11.11%  |
| Sparky 5.12 | 5         | 9.26%   |
| Sparky 6.5  | 3         | 5.56%   |
| Sparky 6.3  | 3         | 5.56%   |
| Sparky 6.0  | 3         | 5.56%   |
| Sparky 5.14 | 3         | 5.56%   |
| Sparky 5.10 | 3         | 5.56%   |
| Sparky 6.2  | 2         | 3.7%    |
| Sparky 5.13 | 2         | 3.7%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Sparky | 49        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Computers | Percent |
|---------------------|-----------|---------|
| 5.10.0-11-686       | 4         | 7.14%   |
| 5.10.0-9-amd64      | 3         | 5.36%   |
| 5.10.0-8-amd64      | 3         | 5.36%   |
| 5.10.0-6-amd64      | 3         | 5.36%   |
| 4.19.0-8-amd64      | 3         | 5.36%   |
| 4.19.0-12-amd64     | 3         | 5.36%   |
| 5.18.0-4-amd64      | 2         | 3.57%   |
| 5.18.0-2-amd64      | 2         | 3.57%   |
| 5.17.0-1-amd64      | 2         | 3.57%   |
| 5.10.0-3-amd64      | 2         | 3.57%   |
| 5.10.0-14-amd64     | 2         | 3.57%   |
| 4.19.0-13-686       | 2         | 3.57%   |
| 4.19.0-10-686       | 2         | 3.57%   |
| 6.0.0-5-amd64       | 1         | 1.79%   |
| 5.9.13-sparky-amd64 | 1         | 1.79%   |
| 5.9.0-4-amd64       | 1         | 1.79%   |
| 5.8.13-sparky-amd64 | 1         | 1.79%   |
| 5.8.0-2-amd64       | 1         | 1.79%   |
| 5.7.2-sparky-amd64  | 1         | 1.79%   |
| 5.6.0-2-amd64       | 1         | 1.79%   |
| 5.5.0-2-amd64       | 1         | 1.79%   |
| 5.4.7-sparky-amd64  | 1         | 1.79%   |
| 5.2.0-2-amd64       | 1         | 1.79%   |
| 5.18.3-sparky-amd64 | 1         | 1.79%   |
| 5.17.3-sparky-amd64 | 1         | 1.79%   |
| 5.16.5-sparky-amd64 | 1         | 1.79%   |
| 5.16.0-5-amd64      | 1         | 1.79%   |
| 5.15.0-3-amd64      | 1         | 1.79%   |
| 5.14.0-4-amd64      | 1         | 1.79%   |
| 5.10.4-sparky-amd64 | 1         | 1.79%   |
| 5.10.0-7-amd64      | 1         | 1.79%   |
| 5.10.0-2-amd64      | 1         | 1.79%   |
| 5.10.0-19-amd64     | 1         | 1.79%   |
| 5.10.0-12-amd64     | 1         | 1.79%   |
| 4.19.0-14-686       | 1         | 1.79%   |
| 4.19.0-10-amd64     | 1         | 1.79%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 21        | 38.89%  |
| 4.19.0  | 10        | 18.52%  |
| 5.18.0  | 4         | 7.41%   |
| 5.17.0  | 2         | 3.7%    |
| 6.0.0   | 1         | 1.85%   |
| 5.9.13  | 1         | 1.85%   |
| 5.9.0   | 1         | 1.85%   |
| 5.8.13  | 1         | 1.85%   |
| 5.8.0   | 1         | 1.85%   |
| 5.7.2   | 1         | 1.85%   |
| 5.6.0   | 1         | 1.85%   |
| 5.5.0   | 1         | 1.85%   |
| 5.4.7   | 1         | 1.85%   |
| 5.2.0   | 1         | 1.85%   |
| 5.18.3  | 1         | 1.85%   |
| 5.17.3  | 1         | 1.85%   |
| 5.16.5  | 1         | 1.85%   |
| 5.16.0  | 1         | 1.85%   |
| 5.15.0  | 1         | 1.85%   |
| 5.14.0  | 1         | 1.85%   |
| 5.10.4  | 1         | 1.85%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 22        | 40.74%  |
| 4.19    | 10        | 18.52%  |
| 5.18    | 5         | 9.26%   |
| 5.17    | 3         | 5.56%   |
| 5.9     | 2         | 3.7%    |
| 5.8     | 2         | 3.7%    |
| 5.16    | 2         | 3.7%    |
| 6.0     | 1         | 1.85%   |
| 5.7     | 1         | 1.85%   |
| 5.6     | 1         | 1.85%   |
| 5.5     | 1         | 1.85%   |
| 5.4     | 1         | 1.85%   |
| 5.2     | 1         | 1.85%   |
| 5.15    | 1         | 1.85%   |
| 5.14    | 1         | 1.85%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 43        | 87.76%  |
| i686   | 6         | 12.24%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| XFCE             | 17        | 34%     |
| LXQt             | 13        | 26%     |
| Unknown          | 8         | 16%     |
| KDE5             | 3         | 6%      |
| MATE             | 2         | 4%      |
| GNOME            | 2         | 4%      |
| X-Cinnamon       | 1         | 2%      |
| openbox          | 1         | 2%      |
| lightdm-xsession | 1         | 2%      |
| ICEWM            | 1         | 2%      |
| GNOME Classic    | 1         | 2%      |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 46        | 92%     |
| Tty  | 4         | 8%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 16        | 32.65%  |
| TDM     | 13        | 26.53%  |
| LightDM | 10        | 20.41%  |
| SDDM    | 8         | 16.33%  |
| XDM     | 1         | 2.04%   |
| GDM     | 1         | 2.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 14        | 28.57%  |
| en_GB   | 5         | 10.2%   |
| fr_FR   | 4         | 8.16%   |
| pt_BR   | 3         | 6.12%   |
| pl_PL   | 3         | 6.12%   |
| es_ES   | 3         | 6.12%   |
| de_DE   | 3         | 6.12%   |
| Unknown | 2         | 4.08%   |
| sv_SE   | 1         | 2.04%   |
| ja_JP   | 1         | 2.04%   |
| es_US   | 1         | 2.04%   |
| es_CL   | 1         | 2.04%   |
| es_AR   | 1         | 2.04%   |
| en_ZA   | 1         | 2.04%   |
| en_PH   | 1         | 2.04%   |
| en_IN   | 1         | 2.04%   |
| en_DK   | 1         | 2.04%   |
| en_CA   | 1         | 2.04%   |
| de_CH   | 1         | 2.04%   |
| cs_CZ   | 1         | 2.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 31        | 63.27%  |
| EFI  | 18        | 36.73%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 44        | 89.8%   |
| Overlay | 2         | 4.08%   |
| Zfs     | 1         | 2.04%   |
| Ext2    | 1         | 2.04%   |
| Btrfs   | 1         | 2.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 18        | 36.73%  |
| Unknown | 16        | 32.65%  |
| MBR     | 15        | 30.61%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 41        | 83.67%  |
| Yes       | 8         | 16.33%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 32        | 65.31%  |
| Yes       | 17        | 34.69%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 11        | 22.45%  |
| Lenovo              | 5         | 10.2%   |
| Intel               | 5         | 10.2%   |
| Gigabyte Technology | 5         | 10.2%   |
| Dell                | 5         | 10.2%   |
| ASUSTek Computer    | 5         | 10.2%   |
| MSI                 | 3         | 6.12%   |
| Google              | 2         | 4.08%   |
| Samsung Electronics | 1         | 2.04%   |
| HUAWEI              | 1         | 2.04%   |
| Foxconn             | 1         | 2.04%   |
| eMachines           | 1         | 2.04%   |
| Beelink             | 1         | 2.04%   |
| Apple               | 1         | 2.04%   |
| Acer                | 1         | 2.04%   |
| Unknown             | 1         | 2.04%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| Samsung NC10                     | 1         | 2.04%   |
| MSI MS-7C09                      | 1         | 2.04%   |
| MSI MS-7B86                      | 1         | 2.04%   |
| MSI MS-7721                      | 1         | 2.04%   |
| Lenovo ThinkPad T61 7659AB7      | 1         | 2.04%   |
| Lenovo ThinkPad T60 2007FUG      | 1         | 2.04%   |
| Lenovo ThinkPad E15 20RES0GF00   | 1         | 2.04%   |
| Lenovo IdeaPad S206 20154        | 1         | 2.04%   |
| Lenovo G50-30 80G0               | 1         | 2.04%   |
| Intel NUC5CPYB H61145-408        | 1         | 2.04%   |
| Intel H61                        | 1         | 2.04%   |
| Intel H55                        | 1         | 2.04%   |
| Intel DG43RK AAE78175-402        | 1         | 2.04%   |
| Intel DG41TY AAE47335-300        | 1         | 2.04%   |
| HUAWEI HVY-WXX9                  | 1         | 2.04%   |
| HP t5740                         | 1         | 2.04%   |
| HP Stream Notebook PC 13         | 1         | 2.04%   |
| HP Pavilion g7                   | 1         | 2.04%   |
| HP Pavilion dv9000 (GA359UA#ABA) | 1         | 2.04%   |
| HP Pavilion dv5                  | 1         | 2.04%   |
| HP Laptop 17z-ca100              | 1         | 2.04%   |
| HP EliteDesk 800 G2 DM 65W       | 1         | 2.04%   |
| HP EliteDesk 705 G2 MINI         | 1         | 2.04%   |
| HP EliteBook Folio 9480m         | 1         | 2.04%   |
| HP EliteBook 8770w               | 1         | 2.04%   |
| HP EliteBook 745 G3              | 1         | 2.04%   |
| Google Swanky                    | 1         | 2.04%   |
| Google Banon                     | 1         | 2.04%   |
| Gigabyte X570S AORUS PRO AX      | 1         | 2.04%   |
| Gigabyte M68M-S2P                | 1         | 2.04%   |
| Gigabyte H97-Gaming 3            | 1         | 2.04%   |
| Gigabyte H410M H                 | 1         | 2.04%   |
| Gigabyte G41M-ES2L               | 1         | 2.04%   |
| Foxconn p6-2010fr                | 1         | 2.04%   |
| eMachines E525                   | 1         | 2.04%   |
| Dell OptiPlex 580                | 1         | 2.04%   |
| Dell Latitude XT3                | 1         | 2.04%   |
| Dell Inspiron N5010              | 1         | 2.04%   |
| Dell Inspiron 5770               | 1         | 2.04%   |
| Dell Inspiron 5720               | 1         | 2.04%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 3         | 6.12%   |
| HP Pavilion         | 3         | 6.12%   |
| HP EliteBook        | 3         | 6.12%   |
| Dell Inspiron       | 3         | 6.12%   |
| HP EliteDesk        | 2         | 4.08%   |
| Samsung NC10        | 1         | 2.04%   |
| MSI MS-7C09         | 1         | 2.04%   |
| MSI MS-7B86         | 1         | 2.04%   |
| MSI MS-7721         | 1         | 2.04%   |
| Lenovo IdeaPad      | 1         | 2.04%   |
| Lenovo G50-30       | 1         | 2.04%   |
| Intel NUC5CPYB      | 1         | 2.04%   |
| Intel H61           | 1         | 2.04%   |
| Intel H55           | 1         | 2.04%   |
| Intel DG43RK        | 1         | 2.04%   |
| Intel DG41TY        | 1         | 2.04%   |
| HUAWEI HVY-WXX9     | 1         | 2.04%   |
| HP t5740            | 1         | 2.04%   |
| HP Stream           | 1         | 2.04%   |
| HP Laptop           | 1         | 2.04%   |
| Google Swanky       | 1         | 2.04%   |
| Google Banon        | 1         | 2.04%   |
| Gigabyte X570S      | 1         | 2.04%   |
| Gigabyte M68M-S2P   | 1         | 2.04%   |
| Gigabyte H97-Gaming | 1         | 2.04%   |
| Gigabyte H410M      | 1         | 2.04%   |
| Gigabyte G41M-ES2L  | 1         | 2.04%   |
| Foxconn p6-2010fr   | 1         | 2.04%   |
| eMachines E525      | 1         | 2.04%   |
| Dell OptiPlex       | 1         | 2.04%   |
| Dell Latitude       | 1         | 2.04%   |
| Beelink BT3         | 1         | 2.04%   |
| ASUS S101           | 1         | 2.04%   |
| ASUS M70Vn          | 1         | 2.04%   |
| ASUS G20AJ          | 1         | 2.04%   |
| ASUS CROSSHAIR      | 1         | 2.04%   |
| ASUS 1000HE         | 1         | 2.04%   |
| Apple MacBook1      | 1         | 2.04%   |
| Acer Aspire         | 1         | 2.04%   |
| Unknown             | 1         | 2.04%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2009 | 7         | 14.29%  |
| 2014 | 6         | 12.24%  |
| 2012 | 4         | 8.16%   |
| 2008 | 4         | 8.16%   |
| 2021 | 3         | 6.12%   |
| 2020 | 3         | 6.12%   |
| 2018 | 3         | 6.12%   |
| 2011 | 3         | 6.12%   |
| 2010 | 3         | 6.12%   |
| 2019 | 2         | 4.08%   |
| 2017 | 2         | 4.08%   |
| 2016 | 2         | 4.08%   |
| 2015 | 2         | 4.08%   |
| 2007 | 2         | 4.08%   |
| 2006 | 2         | 4.08%   |
| 2022 | 1         | 2.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Notebook | 28        | 57.14%  |
| Desktop  | 20        | 40.82%  |
| Mini pc  | 1         | 2.04%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 49        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 47        | 95.92%  |
| Yes  | 2         | 4.08%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 14        | 28.57%  |
| 4.01-8.0   | 8         | 16.33%  |
| 16.01-24.0 | 7         | 14.29%  |
| 1.01-2.0   | 6         | 12.24%  |
| 2.01-3.0   | 5         | 10.2%   |
| 8.01-16.0  | 5         | 10.2%   |
| 24.01-32.0 | 2         | 4.08%   |
| 32.01-64.0 | 1         | 2.04%   |
| 0.51-1.0   | 1         | 2.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 22        | 42.31%  |
| 0.51-1.0 | 11        | 21.15%  |
| 2.01-3.0 | 8         | 15.38%  |
| 4.01-8.0 | 5         | 9.62%   |
| 3.01-4.0 | 3         | 5.77%   |
| 0.01-0.5 | 3         | 5.77%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 36        | 70.59%  |
| 2      | 8         | 15.69%  |
| 4      | 3         | 5.88%   |
| 6      | 2         | 3.92%   |
| 5      | 1         | 1.96%   |
| 3      | 1         | 1.96%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 31        | 63.27%  |
| Yes       | 18        | 36.73%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 44        | 89.8%   |
| No        | 5         | 10.2%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 36        | 73.47%  |
| No        | 13        | 26.53%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 25        | 51.02%  |
| Yes       | 24        | 48.98%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 8         | 16.33%  |
| Germany      | 6         | 12.24%  |
| UK           | 5         | 10.2%   |
| France       | 5         | 10.2%   |
| Poland       | 3         | 6.12%   |
| Brazil       | 3         | 6.12%   |
| Spain        | 2         | 4.08%   |
| Indonesia    | 2         | 4.08%   |
| Canada       | 2         | 4.08%   |
| Argentina    | 2         | 4.08%   |
| Venezuela    | 1         | 2.04%   |
| Switzerland  | 1         | 2.04%   |
| Sweden       | 1         | 2.04%   |
| South Africa | 1         | 2.04%   |
| Philippines  | 1         | 2.04%   |
| New Zealand  | 1         | 2.04%   |
| Lebanon      | 1         | 2.04%   |
| Japan        | 1         | 2.04%   |
| India        | 1         | 2.04%   |
| Czechia      | 1         | 2.04%   |
| Chile        | 1         | 2.04%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Montreuil        | 2         | 3.85%   |
| Leipzig          | 2         | 3.85%   |
| Woking           | 1         | 1.92%   |
| Wenatchee        | 1         | 1.92%   |
| Tucson           | 1         | 1.92%   |
| Tauranga         | 1         | 1.92%   |
| Takahama         | 1         | 1.92%   |
| Surabaya         | 1         | 1.92%   |
| Spokane          | 1         | 1.92%   |
| Sin el Fil       | 1         | 1.92%   |
| San Cristóbal   | 1         | 1.92%   |
| San Antonio      | 1         | 1.92%   |
| Sainte-Julie     | 1         | 1.92%   |
| Rosario          | 1         | 1.92%   |
| Rio de Janeiro   | 1         | 1.92%   |
| Rio Claro        | 1         | 1.92%   |
| Quezon City      | 1         | 1.92%   |
| Pujaudran        | 1         | 1.92%   |
| Puente Alto      | 1         | 1.92%   |
| Posadas          | 1         | 1.92%   |
| Pompano Beach    | 1         | 1.92%   |
| Montreal         | 1         | 1.92%   |
| Mnisek pod Brdy  | 1         | 1.92%   |
| Miekoszyn        | 1         | 1.92%   |
| Mannheim         | 1         | 1.92%   |
| Madrid           | 1         | 1.92%   |
| Liverpool        | 1         | 1.92%   |
| Lienen           | 1         | 1.92%   |
| Koło            | 1         | 1.92%   |
| Kirkcaldy        | 1         | 1.92%   |
| Kage             | 1         | 1.92%   |
| Houston          | 1         | 1.92%   |
| Hamburg          | 1         | 1.92%   |
| Grabs            | 1         | 1.92%   |
| Gmina Bolków    | 1         | 1.92%   |
| Glasgow          | 1         | 1.92%   |
| Fuveau           | 1         | 1.92%   |
| Frankfurt (Oder) | 1         | 1.92%   |
| East Wenatchee   | 1         | 1.92%   |
| Duque de Caxias  | 1         | 1.92%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 20     | 19.12%  |
| WDC                 | 11        | 13     | 16.18%  |
| Samsung Electronics | 10        | 20     | 14.71%  |
| Hitachi             | 6         | 8      | 8.82%   |
| Unknown             | 4         | 4      | 5.88%   |
| Kingston            | 3         | 3      | 4.41%   |
| Toshiba             | 2         | 2      | 2.94%   |
| SanDisk             | 2         | 3      | 2.94%   |
| Intel               | 2         | 2      | 2.94%   |
| Goodram             | 2         | 4      | 2.94%   |
| XPG                 | 1         | 1      | 1.47%   |
| SPCC                | 1         | 2      | 1.47%   |
| Silicon Motion      | 1         | 1      | 1.47%   |
| ORICO               | 1         | 1      | 1.47%   |
| Netac               | 1         | 1      | 1.47%   |
| Micron Technology   | 1         | 1      | 1.47%   |
| HGST                | 1         | 1      | 1.47%   |
| Gigabyte Technology | 1         | 1      | 1.47%   |
| Fujitsu             | 1         | 2      | 1.47%   |
| Crucial             | 1         | 1      | 1.47%   |
| ASUS-JM             | 1         | 1      | 1.47%   |
| ASMedia             | 1         | 1      | 1.47%   |
| A-DATA Technology   | 1         | 1      | 1.47%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| WDC WD1600BEVT-22ZCT0 160GB             | 2         | 2.67%   |
| Seagate ST500LT012-1DG142 500GB         | 2         | 2.67%   |
| Samsung HD161GJ 160GB                   | 2         | 2.67%   |
| Hitachi HTS545025B9A300 250GB           | 2         | 2.67%   |
| XPG GAMMIX S11 Pro 1TB                  | 1         | 1.33%   |
| WDC WD800JD-08MSA1 80GB                 | 1         | 1.33%   |
| WDC WD5000BEVT-22ZAT0 500GB             | 1         | 1.33%   |
| WDC WD5000AVVS-63ZWB0 500GB             | 1         | 1.33%   |
| WDC WD5000AAKS-75V0A0 500GB             | 1         | 1.33%   |
| WDC WD3200BPVT-75ZEST0 320GB            | 1         | 1.33%   |
| WDC WD2500AAKX-07U6AA0 250GB            | 1         | 1.33%   |
| WDC WD1600AAJS-08L7A0 160GB             | 1         | 1.33%   |
| WDC WD10EZEX-60WN4A0 1TB                | 1         | 1.33%   |
| WDC WD10EADS-00M2B0 1TB                 | 1         | 1.33%   |
| Unknown MMC Card  64GB                  | 1         | 1.33%   |
| Unknown MMC Card  32GB                  | 1         | 1.33%   |
| Unknown HBG4a2  32GB                    | 1         | 1.33%   |
| Unknown 016GE2  16GB                    | 1         | 1.33%   |
| Toshiba DT01ACA100 1TB                  | 1         | 1.33%   |
| Toshiba DT01ACA050 500GB                | 1         | 1.33%   |
| SPCC Solid State Disk 256GB             | 1         | 1.33%   |
| Silicon Motion PCIe-8 SSD 512GB         | 1         | 1.33%   |
| Seagate ST9500325AS 500GB               | 1         | 1.33%   |
| Seagate ST9250320AS 250GB               | 1         | 1.33%   |
| Seagate ST9250315AS 250GB               | 1         | 1.33%   |
| Seagate ST9160310AS 160GB               | 1         | 1.33%   |
| Seagate ST500DM002-1BD142 500GB         | 1         | 1.33%   |
| Seagate ST3500312CS 500GB               | 1         | 1.33%   |
| Seagate ST3320418AS 320GB               | 1         | 1.33%   |
| Seagate ST2000VM003-1ET164 2TB          | 1         | 1.33%   |
| Seagate ST1000LM048-2E7172 1TB          | 1         | 1.33%   |
| Seagate ST1000LM035-1RK172 1TB          | 1         | 1.33%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 1         | 1.33%   |
| Seagate BarraCuda Q5 ZP500CV30001 500GB | 1         | 1.33%   |
| Seagate Backup+ Hub BK 8TB              | 1         | 1.33%   |
| Seagate Backup+ Desk 5TB                | 1         | 1.33%   |
| SanDisk SSD PLUS 480GB                  | 1         | 1.33%   |
| SanDisk NVMe SSD Drive 500GB            | 1         | 1.33%   |
| Samsung SSD 850 EVO 500GB               | 1         | 1.33%   |
| Samsung SSD 850 EVO 250GB               | 1         | 1.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 18     | 34.21%  |
| WDC                 | 11        | 13     | 28.95%  |
| Hitachi             | 6         | 8      | 15.79%  |
| Samsung Electronics | 3         | 10     | 7.89%   |
| Toshiba             | 2         | 2      | 5.26%   |
| HGST                | 1         | 1      | 2.63%   |
| Fujitsu             | 1         | 2      | 2.63%   |
| ASMedia             | 1         | 1      | 2.63%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 7      | 25%     |
| Kingston            | 3         | 3      | 15%     |
| Intel               | 2         | 2      | 10%     |
| GOODRAM             | 2         | 4      | 10%     |
| SPCC                | 1         | 2      | 5%      |
| SanDisk             | 1         | 1      | 5%      |
| ORICO               | 1         | 1      | 5%      |
| Netac               | 1         | 1      | 5%      |
| Micron Technology   | 1         | 1      | 5%      |
| Gigabyte Technology | 1         | 1      | 5%      |
| Crucial             | 1         | 1      | 5%      |
| ASUS-JM             | 1         | 1      | 5%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 31        | 55     | 50.82%  |
| SSD     | 18        | 25     | 29.51%  |
| NVMe    | 7         | 9      | 11.48%  |
| MMC     | 4         | 4      | 6.56%   |
| Unknown | 1         | 1      | 1.64%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 43        | 76     | 76.79%  |
| NVMe | 7         | 9      | 12.5%   |
| MMC  | 4         | 4      | 7.14%   |
| SAS  | 2         | 5      | 3.57%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 37        | 61     | 77.08%  |
| 0.51-1.0   | 9         | 15     | 18.75%  |
| 1.01-2.0   | 1         | 1      | 2.08%   |
| 4.01-10.0  | 1         | 3      | 2.08%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 15        | 30%     |
| 251-500        | 9         | 18%     |
| 501-1000       | 8         | 16%     |
| 1-20           | 5         | 10%     |
| 21-50          | 4         | 8%      |
| 51-100         | 3         | 6%      |
| 2001-3000      | 2         | 4%      |
| Unknown        | 2         | 4%      |
| More than 3000 | 1         | 2%      |
| 1001-2000      | 1         | 2%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 25        | 48.08%  |
| 21-50          | 7         | 13.46%  |
| 51-100         | 6         | 11.54%  |
| 251-500        | 3         | 5.77%   |
| 101-250        | 3         | 5.77%   |
| 501-1000       | 3         | 5.77%   |
| 1001-2000      | 2         | 3.85%   |
| Unknown        | 2         | 3.85%   |
| More than 3000 | 1         | 1.92%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-22ZAT0 500GB                         | 1         | 1      | 11.11%  |
| WDC WD5000AVVS-63ZWB0 500GB                         | 1         | 1      | 11.11%  |
| WDC WD3200BPVT-75ZEST0 320GB                        | 1         | 1      | 11.11%  |
| WDC WD1600AAJS-08L7A0 160GB                         | 1         | 1      | 11.11%  |
| WDC WD10EADS-00M2B0 1TB                             | 1         | 1      | 11.11%  |
| Seagate ST9500325AS 500GB                           | 1         | 1      | 11.11%  |
| Seagate ST9250315AS 250GB                           | 1         | 1      | 11.11%  |
| Micron Technology MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 1      | 11.11%  |
| ASMedia ASMT1153E 500GB                             | 1         | 1      | 11.11%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| WDC               | 5         | 5      | 55.56%  |
| Seagate           | 2         | 2      | 22.22%  |
| Micron Technology | 1         | 1      | 11.11%  |
| ASMedia           | 1         | 1      | 11.11%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 5         | 5      | 62.5%   |
| Seagate | 2         | 2      | 25%     |
| ASMedia | 1         | 1      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 8         | 8      | 88.89%  |
| SSD  | 1         | 1      | 11.11%  |

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
| Works    | 27        | 43     | 48.21%  |
| Detected | 20        | 42     | 35.71%  |
| Malfunc  | 9         | 9      | 16.07%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 32        | 60.38%  |
| AMD                      | 8         | 15.09%  |
| Samsung Electronics      | 3         | 5.66%   |
| Silicon Motion           | 2         | 3.77%   |
| Nvidia                   | 2         | 3.77%   |
| VIA Technologies         | 1         | 1.89%   |
| Seagate Technology       | 1         | 1.89%   |
| SanDisk                  | 1         | 1.89%   |
| Marvell Technology Group | 1         | 1.89%   |
| JMicron Technology       | 1         | 1.89%   |
| ADATA Technology         | 1         | 1.89%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 6         | 9.38%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 3         | 4.69%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 3         | 4.69%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 3.13%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 2         | 3.13%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 3.13%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 2         | 3.13%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 2         | 3.13%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 2         | 3.13%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 2         | 3.13%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 2         | 3.13%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 3.13%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 3.13%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                      | 1         | 1.56%   |
| VIA VT8237A SATA 2-Port Controller                                               | 1         | 1.56%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 1         | 1.56%   |
| Silicon Motion Non-Volatile memory controller                                    | 1         | 1.56%   |
| Seagate Non-Volatile memory controller                                           | 1         | 1.56%   |
| SanDisk WD Blue SN570 NVMe SSD                                                   | 1         | 1.56%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 1         | 1.56%   |
| Nvidia MCP61 SATA Controller                                                     | 1         | 1.56%   |
| Nvidia MCP61 IDE                                                                 | 1         | 1.56%   |
| Nvidia MCP51 Serial ATA Controller                                               | 1         | 1.56%   |
| Nvidia MCP51 IDE                                                                 | 1         | 1.56%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                        | 1         | 1.56%   |
| JMicron JMB360 AHCI Controller                                                   | 1         | 1.56%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 1         | 1.56%   |
| Intel SATA Controller [RAID mode]                                                | 1         | 1.56%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 1.56%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 1.56%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 1.56%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 1.56%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 1         | 1.56%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 1         | 1.56%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 1         | 1.56%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 1.56%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 1.56%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1         | 1.56%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 1         | 1.56%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 1         | 1.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 31        | 57.41%  |
| IDE  | 15        | 27.78%  |
| NVMe | 7         | 12.96%  |
| RAID | 1         | 1.85%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 37        | 75.51%  |
| AMD    | 12        | 24.49%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron CPU N2840 @ 2.16GHz             | 3         | 6.12%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 2         | 4.08%   |
| Intel Atom CPU N280 @ 1.66GHz                 | 2         | 4.08%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 2         | 4.08%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz        | 1         | 2.04%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz   | 1         | 2.04%   |
| Intel Pentium CPU B950 @ 2.10GHz              | 1         | 2.04%   |
| Intel Genuine CPU T2400 @ 1.83GHz             | 1         | 2.04%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 1         | 2.04%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 1         | 2.04%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 1         | 2.04%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 1         | 2.04%   |
| Intel Core i7-3612QM CPU @ 2.10GHz            | 1         | 2.04%   |
| Intel Core i7 CPU 860 @ 2.80GHz               | 1         | 2.04%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 2.04%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 1         | 2.04%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 1         | 2.04%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 2.04%   |
| Intel Core i5-2500 CPU @ 3.30GHz              | 1         | 2.04%   |
| Intel Core i5-10400 CPU @ 2.90GHz             | 1         | 2.04%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 2.04%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 1         | 2.04%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 1         | 2.04%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 1         | 2.04%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 1         | 2.04%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 1         | 2.04%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz          | 1         | 2.04%   |
| Intel Core 2 CPU T5600 @ 1.83GHz              | 1         | 2.04%   |
| Intel Celeron CPU N3160 @ 1.60GHz             | 1         | 2.04%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 1         | 2.04%   |
| Intel Celeron CPU 900 @ 2.20GHz               | 1         | 2.04%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 1         | 2.04%   |
| AMD Turion 64 X2 Mobile Technology TL-64      | 1         | 2.04%   |
| AMD Sempron 145 Processor                     | 1         | 2.04%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 1         | 2.04%   |
| AMD Ryzen 7 1800X Eight-Core Processor        | 1         | 2.04%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 1         | 2.04%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 2.04%   |
| AMD Ryzen 3 3100 4-Core Processor             | 1         | 2.04%   |
| AMD PRO A8-8600B R6, 10 Compute Cores 4C+6G   | 1         | 2.04%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 8         | 16.33%  |
| Intel Core i7           | 6         | 12.24%  |
| Intel Celeron           | 6         | 12.24%  |
| Intel Core 2 Duo        | 5         | 10.2%   |
| Intel Atom              | 5         | 10.2%   |
| AMD Ryzen 5             | 2         | 4.08%   |
| Intel Pentium Gold      | 1         | 2.04%   |
| Intel Pentium Dual-Core | 1         | 2.04%   |
| Intel Pentium           | 1         | 2.04%   |
| Intel Genuine           | 1         | 2.04%   |
| Intel Core i3           | 1         | 2.04%   |
| Intel Core 2 Quad       | 1         | 2.04%   |
| Intel Core 2            | 1         | 2.04%   |
| AMD Turion 64 X2 Mobile | 1         | 2.04%   |
| AMD Sempron             | 1         | 2.04%   |
| AMD Ryzen 9             | 1         | 2.04%   |
| AMD Ryzen 7             | 1         | 2.04%   |
| AMD Ryzen 3             | 1         | 2.04%   |
| AMD PRO A8              | 1         | 2.04%   |
| AMD PRO A10             | 1         | 2.04%   |
| AMD C-50                | 1         | 2.04%   |
| AMD Athlon II X2        | 1         | 2.04%   |
| AMD A6                  | 1         | 2.04%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 23        | 46.94%  |
| 4      | 15        | 30.61%  |
| 1      | 7         | 14.29%  |
| 6      | 2         | 4.08%   |
| 12     | 1         | 2.04%   |
| 8      | 1         | 2.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 49        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 25        | 51.02%  |
| 2      | 24        | 48.98%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 44        | 89.8%   |
| 32-bit         | 5         | 10.2%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 8         | 16.33%  |
| 0x306a9    | 3         | 6.12%   |
| 0x30678    | 3         | 6.12%   |
| 0x206a7    | 3         | 6.12%   |
| 0x0600611a | 3         | 6.12%   |
| 0x406c4    | 2         | 4.08%   |
| 0x306c3    | 2         | 4.08%   |
| 0x20655    | 2         | 4.08%   |
| 0x106c2    | 2         | 4.08%   |
| 0x1067a    | 2         | 4.08%   |
| 0x10676    | 2         | 4.08%   |
| 0xa0653    | 1         | 2.04%   |
| 0x806ec    | 1         | 2.04%   |
| 0x806ea    | 1         | 2.04%   |
| 0x6fd      | 1         | 2.04%   |
| 0x6fb      | 1         | 2.04%   |
| 0x6f2      | 1         | 2.04%   |
| 0x506e3    | 1         | 2.04%   |
| 0x406c3    | 1         | 2.04%   |
| 0x40651    | 1         | 2.04%   |
| 0x106e5    | 1         | 2.04%   |
| 0x0a201016 | 1         | 2.04%   |
| 0x08701021 | 1         | 2.04%   |
| 0x08600106 | 1         | 2.04%   |
| 0x08108109 | 1         | 2.04%   |
| 0x08001138 | 1         | 2.04%   |
| 0x05000029 | 1         | 2.04%   |
| 0x010000c8 | 1         | 2.04%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Silvermont  | 6         | 12.24%  |
| Penryn      | 5         | 10.2%   |
| Core        | 4         | 8.16%   |
| Bonnell     | 4         | 8.16%   |
| SandyBridge | 3         | 6.12%   |
| KabyLake    | 3         | 6.12%   |
| IvyBridge   | 3         | 6.12%   |
| Haswell     | 3         | 6.12%   |
| Excavator   | 3         | 6.12%   |
| Zen 2       | 2         | 4.08%   |
| Westmere    | 2         | 4.08%   |
| K10         | 2         | 4.08%   |
| Zen+        | 1         | 2.04%   |
| Zen 3       | 1         | 2.04%   |
| Zen         | 1         | 2.04%   |
| Skylake     | 1         | 2.04%   |
| P6          | 1         | 2.04%   |
| Nehalem     | 1         | 2.04%   |
| K8 Hammer   | 1         | 2.04%   |
| CometLake   | 1         | 2.04%   |
| Bobcat      | 1         | 2.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Intel            | 26        | 50.98%  |
| AMD              | 14        | 27.45%  |
| Nvidia           | 10        | 19.61%  |
| VIA Technologies | 1         | 1.96%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 4         | 7.02%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 3         | 5.26%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 5.26%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 5.26%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 3         | 5.26%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 3.51%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 3.51%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 3.51%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 1         | 1.75%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 1.75%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1         | 1.75%   |
| Nvidia GK104GLM [Quadro K3000M]                                                          | 1         | 1.75%   |
| Nvidia GK104 [GeForce GTX 760]                                                           | 1         | 1.75%   |
| Nvidia GF108M [GeForce GT 420M]                                                          | 1         | 1.75%   |
| Nvidia GA106 [Geforce RTX 3050]                                                          | 1         | 1.75%   |
| Nvidia G96CM [GeForce 9650M GT]                                                          | 1         | 1.75%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 1.75%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 1         | 1.75%   |
| Nvidia C51 [GeForce Go 6150]                                                             | 1         | 1.75%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1         | 1.75%   |
| Intel UHD Graphics 620                                                                   | 1         | 1.75%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.75%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.75%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 1.75%   |
| Intel HD Graphics 530                                                                    | 1         | 1.75%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 1.75%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.75%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 1.75%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1         | 1.75%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                                | 1         | 1.75%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1         | 1.75%   |
| AMD Wrestler [Radeon HD 6250]                                                            | 1         | 1.75%   |
| AMD Turks GL [FirePro V4900]                                                             | 1         | 1.75%   |
| AMD RV515/M54 [Mobility Radeon X1400]                                                    | 1         | 1.75%   |
| AMD RS880 [Radeon HD 4200]                                                               | 1         | 1.75%   |
| AMD Renoir                                                                               | 1         | 1.75%   |
| AMD Redwood LE [Radeon HD 5550/5570/5630/6390/6490/7570]                                 | 1         | 1.75%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1         | 1.75%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 1         | 1.75%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 1         | 1.75%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 25        | 51.02%  |
| 1 x AMD        | 13        | 26.53%  |
| 1 x Nvidia     | 9         | 18.37%  |
| 1 x VIA        | 1         | 2.04%   |
| Intel + Nvidia | 1         | 2.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 43        | 87.76%  |
| Unknown     | 4         | 8.16%   |
| Proprietary | 2         | 4.08%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 33        | 66%     |
| 0.01-0.5   | 7         | 14%     |
| 0.51-1.0   | 4         | 8%      |
| 1.01-2.0   | 3         | 6%      |
| 7.01-8.0   | 2         | 4%      |
| 3.01-4.0   | 1         | 2%      |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 7         | 15.22%  |
| LG Display          | 6         | 13.04%  |
| AU Optronics        | 5         | 10.87%  |
| Goldstar            | 4         | 8.7%    |
| Dell                | 3         | 6.52%   |
| Chimei Innolux      | 3         | 6.52%   |
| Lenovo              | 2         | 4.35%   |
| CPT                 | 2         | 4.35%   |
| BOE                 | 2         | 4.35%   |
| BenQ                | 2         | 4.35%   |
| AOC                 | 2         | 4.35%   |
| Unknown             | 1         | 2.17%   |
| LG Philips          | 1         | 2.17%   |
| JCH                 | 1         | 2.17%   |
| Insignia            | 1         | 2.17%   |
| Hitachi             | 1         | 2.17%   |
| HannStar            | 1         | 2.17%   |
| Apple               | 1         | 2.17%   |
| Acer                | 1         | 2.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch            | 1         | 2%      |
| Samsung Electronics SyncMaster SAM0581 1920x1080 477x268mm 21.5-inch | 1         | 2%      |
| Samsung Electronics SyncMaster SAM0116 1024x768 267x200mm 13.1-inch  | 1         | 2%      |
| Samsung Electronics S24D330 SAM0D93 1920x1080 530x300mm 24.0-inch    | 1         | 2%      |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch    | 1         | 2%      |
| Samsung Electronics S22C450 SAM09C5 1920x1080 477x268mm 21.5-inch    | 1         | 2%      |
| Samsung Electronics LCD Monitor SEC4F45 1280x800 331x207mm 15.4-inch | 1         | 2%      |
| Samsung Electronics LCD Monitor SEC4141 1366x768 344x193mm 15.5-inch | 1         | 2%      |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch    | 1         | 2%      |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch          | 1         | 2%      |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch        | 1         | 2%      |
| LG Display LCD Monitor LGD059E 1920x1080 382x215mm 17.3-inch         | 1         | 2%      |
| LG Display LCD Monitor LGD04E1 1366x768 344x194mm 15.5-inch          | 1         | 2%      |
| LG Display LCD Monitor LGD02E1 1600x900 382x215mm 17.3-inch          | 1         | 2%      |
| LG Display LCD Monitor LGD0266 1366x768 344x194mm 15.5-inch          | 1         | 2%      |
| LG Display LCD Monitor LGD01C5 1366x768 293x165mm 13.2-inch          | 1         | 2%      |
| Lenovo LCD Monitor LEN4033 1440x900 303x190mm 14.1-inch              | 1         | 2%      |
| Lenovo LCD Monitor LEN4022 1400x1050 287x215mm 14.1-inch             | 1         | 2%      |
| JCH F24 JCH1919 1920x1080 520x310mm 23.8-inch                        | 1         | 2%      |
| Insignia NS19ED200NA14 BBY0032 1680x1050 640x384mm 29.4-inch         | 1         | 2%      |
| Hitachi HDMI HEC0088 1920x540                                        | 1         | 2%      |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch             | 1         | 2%      |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                  | 1         | 2%      |
| Goldstar TV GSM9CF6 1360x768 708x398mm 32.0-inch                     | 1         | 2%      |
| Goldstar T710SH GSM436B 1280x960 310x230mm 15.2-inch                 | 1         | 2%      |
| Goldstar L1953H GSM4B3D 1280x1024 338x270mm 17.0-inch                | 1         | 2%      |
| Goldstar L1953H GSM4B3C 1280x1024 338x270mm 17.0-inch                | 1         | 2%      |
| Goldstar 23MP55 GSM5A23 1920x1080 510x290mm 23.1-inch                | 1         | 2%      |
| Dell LCD Monitor S2715H 3840x1080                                    | 1         | 2%      |
| Dell LCD Monitor S2715H                                              | 1         | 2%      |
| Dell IN1930 DELF03B 1366x768 410x230mm 18.5-inch                     | 1         | 2%      |
| Dell E176FP DELA014 1280x1024 338x270mm 17.0-inch                    | 1         | 2%      |
| CPT LCD Monitor CPT04CE 1024x600 222x130mm 10.1-inch                 | 1         | 2%      |
| CPT LCD Monitor CPT04C4 1024x600 222x130mm 10.1-inch                 | 1         | 2%      |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch     | 1         | 2%      |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 308x173mm 13.9-inch     | 1         | 2%      |
| Chimei Innolux LCD Monitor CMN1484 1600x900 310x174mm 14.0-inch      | 1         | 2%      |
| BOE LCD Monitor BOE0878 1920x1080 355x200mm 16.0-inch                | 1         | 2%      |
| BOE LCD Monitor BOE085E 1920x1080 344x194mm 15.5-inch                | 1         | 2%      |
| BenQ FP202W BNQ76C2 1680x1050 376x301mm 19.0-inch                    | 1         | 2%      |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 16        | 32.65%  |
| 1366x768 (WXGA)    | 9         | 18.37%  |
| 1600x900 (HD+)     | 4         | 8.16%   |
| 1280x1024 (SXGA)   | 3         | 6.12%   |
| 1024x600           | 3         | 6.12%   |
| 1920x540           | 2         | 4.08%   |
| 1440x900 (WXGA+)   | 2         | 4.08%   |
| 1280x800 (WXGA)    | 2         | 4.08%   |
| 3840x1080          | 1         | 2.04%   |
| 2288x1287          | 1         | 2.04%   |
| 1680x1050 (WSXGA+) | 1         | 2.04%   |
| 1400x1050          | 1         | 2.04%   |
| 1360x768           | 1         | 2.04%   |
| 1280x960           | 1         | 2.04%   |
| 1024x768 (XGA)     | 1         | 2.04%   |
| Unknown            | 1         | 2.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 17      | 9         | 18.75%  |
| 15      | 7         | 14.58%  |
| 13      | 6         | 12.5%   |
| 23      | 5         | 10.42%  |
| 14      | 3         | 6.25%   |
| 10      | 3         | 6.25%   |
| 48      | 2         | 4.17%   |
| 24      | 2         | 4.17%   |
| 21      | 2         | 4.17%   |
| 20      | 2         | 4.17%   |
| 18      | 2         | 4.17%   |
| 16      | 2         | 4.17%   |
| 142     | 1         | 2.08%   |
| 72      | 1         | 2.08%   |
| Unknown | 1         | 2.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 14        | 29.17%  |
| 201-300        | 9         | 18.75%  |
| 501-600        | 7         | 14.58%  |
| 351-400        | 7         | 14.58%  |
| 401-500        | 6         | 12.5%   |
| 1001-1500      | 2         | 4.17%   |
| More than 2000 | 1         | 2.08%   |
| 1501-2000      | 1         | 2.08%   |
| Unknown        | 1         | 2.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 33        | 68.75%  |
| 16/10   | 5         | 10.42%  |
| 5/4     | 3         | 6.25%   |
| 4/3     | 3         | 6.25%   |
| 1.96    | 2         | 4.17%   |
| 1.00    | 1         | 2.08%   |
| Unknown | 1         | 2.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 8         | 16.67%  |
| 201-250        | 7         | 14.58%  |
| 121-130        | 6         | 12.5%   |
| 141-150        | 5         | 10.42%  |
| 81-90          | 4         | 8.33%   |
| 71-80          | 4         | 8.33%   |
| 151-200        | 4         | 8.33%   |
| 41-50          | 3         | 6.25%   |
| More than 1000 | 2         | 4.17%   |
| 501-1000       | 2         | 4.17%   |
| 131-140        | 1         | 2.08%   |
| 91-100         | 1         | 2.08%   |
| Unknown        | 1         | 2.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 16        | 34.78%  |
| 101-120 | 15        | 32.61%  |
| 121-160 | 10        | 21.74%  |
| 1-50    | 4         | 8.7%    |
| Unknown | 1         | 2.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 42        | 85.71%  |
| 2     | 4         | 8.16%   |
| 0     | 3         | 6.12%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 22        | 30.56%  |
| Intel                    | 19        | 26.39%  |
| Qualcomm Atheros         | 10        | 13.89%  |
| Broadcom Limited         | 4         | 5.56%   |
| Broadcom                 | 4         | 5.56%   |
| Ralink Technology        | 3         | 4.17%   |
| TP-Link                  | 2         | 2.78%   |
| Nvidia                   | 2         | 2.78%   |
| Marvell Technology Group | 2         | 2.78%   |
| VIA Technologies         | 1         | 1.39%   |
| Samsung Electronics      | 1         | 1.39%   |
| Ralink                   | 1         | 1.39%   |
| D-Link System            | 1         | 1.39%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 14        | 16.67%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 6         | 7.14%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 2         | 2.38%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 2         | 2.38%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 2         | 2.38%   |
| Intel Wireless 7265                                                           | 2         | 2.38%   |
| Intel Wireless 7260                                                           | 2         | 2.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2         | 2.38%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                              | 2         | 2.38%   |
| VIA VT6102/VT6103 [Rhine-II]                                                  | 1         | 1.19%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                           | 1         | 1.19%   |
| TP-Link 802.11ac WLAN Adapter                                                 | 1         | 1.19%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 1         | 1.19%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 1         | 1.19%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 1.19%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 1.19%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 1         | 1.19%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 1         | 1.19%   |
| Ralink RT5370 Wireless Adapter                                                | 1         | 1.19%   |
| Ralink RT3072 Wireless Adapter                                                | 1         | 1.19%   |
| Ralink MT7601U Wireless Adapter                                               | 1         | 1.19%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                     | 1         | 1.19%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 1         | 1.19%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1         | 1.19%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1         | 1.19%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 1         | 1.19%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                         | 1         | 1.19%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 1.19%   |
| Nvidia MCP61 Ethernet                                                         | 1         | 1.19%   |
| Nvidia MCP51 Ethernet Controller                                              | 1         | 1.19%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                       | 1         | 1.19%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                          | 1         | 1.19%   |
| Intel Wireless 8260                                                           | 1         | 1.19%   |
| Intel Wireless 3165                                                           | 1         | 1.19%   |
| Intel WiFi Link 5100                                                          | 1         | 1.19%   |
| Intel Wi-Fi 6 AX200                                                           | 1         | 1.19%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                       | 1         | 1.19%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                 | 1         | 1.19%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 1         | 1.19%   |
| Intel I211 Gigabit Network Connection                                         | 1         | 1.19%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 16        | 41.03%  |
| Qualcomm Atheros      | 8         | 20.51%  |
| Realtek Semiconductor | 5         | 12.82%  |
| Ralink Technology     | 3         | 7.69%   |
| TP-Link               | 2         | 5.13%   |
| Broadcom Limited      | 2         | 5.13%   |
| Ralink                | 1         | 2.56%   |
| D-Link System         | 1         | 2.56%   |
| Broadcom              | 1         | 2.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                       | Computers | Percent |
|---------------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                              | 2         | 5.13%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                     | 2         | 5.13%   |
| Intel Wireless 7265                                                                         | 2         | 5.13%   |
| Intel Wireless 7260                                                                         | 2         | 5.13%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                         | 1         | 2.56%   |
| TP-Link 802.11ac WLAN Adapter                                                               | 1         | 2.56%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                          | 1         | 2.56%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                    | 1         | 2.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                    | 1         | 2.56%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                    | 1         | 2.56%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                             | 1         | 2.56%   |
| Ralink RT5370 Wireless Adapter                                                              | 1         | 2.56%   |
| Ralink RT3072 Wireless Adapter                                                              | 1         | 2.56%   |
| Ralink MT7601U Wireless Adapter                                                             | 1         | 2.56%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                   | 1         | 2.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                  | 1         | 2.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                            | 1         | 2.56%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                              | 1         | 2.56%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]               | 1         | 2.56%   |
| Intel Wireless 8260                                                                         | 1         | 2.56%   |
| Intel Wireless 3165                                                                         | 1         | 2.56%   |
| Intel WiFi Link 5100                                                                        | 1         | 2.56%   |
| Intel Wi-Fi 6 AX200                                                                         | 1         | 2.56%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                                     | 1         | 2.56%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                               | 1         | 2.56%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                       | 1         | 2.56%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                           | 1         | 2.56%   |
| Intel Centrino Wireless-N 2230                                                              | 1         | 2.56%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                                | 1         | 2.56%   |
| Intel Centrino Ultimate-N 6300                                                              | 1         | 2.56%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                | 1         | 2.56%   |
| D-Link System DWA-160 802.11abgn Xtreme N Dual Band Adapter(rev.A2) [Atheros AR9170+AR9104] | 1         | 2.56%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter                                 | 1         | 2.56%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                                   | 1         | 2.56%   |
| Broadcom BCM43142 802.11b/g/n                                                               | 1         | 2.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 20        | 44.44%  |
| Intel                    | 10        | 22.22%  |
| Qualcomm Atheros         | 4         | 8.89%   |
| Broadcom                 | 3         | 6.67%   |
| Nvidia                   | 2         | 4.44%   |
| Marvell Technology Group | 2         | 4.44%   |
| Broadcom Limited         | 2         | 4.44%   |
| VIA Technologies         | 1         | 2.22%   |
| Samsung Electronics      | 1         | 2.22%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 14        | 31.11%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 13.33%  |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 4.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 4.44%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 2         | 4.44%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 2.22%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 2.22%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 2.22%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 2.22%   |
| Nvidia MCP61 Ethernet                                             | 1         | 2.22%   |
| Nvidia MCP51 Ethernet Controller                                  | 1         | 2.22%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 2.22%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 2.22%   |
| Intel I211 Gigabit Network Connection                             | 1         | 2.22%   |
| Intel Ethernet Controller I225-V                                  | 1         | 2.22%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 2.22%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 2.22%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 2.22%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 2.22%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 2.22%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 1         | 2.22%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 2.22%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1         | 2.22%   |
| Broadcom Limited NetLink BCM57788 Gigabit Ethernet PCIe           | 1         | 2.22%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 44        | 54.32%  |
| WiFi     | 37        | 45.68%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 29        | 53.7%   |
| Ethernet | 25        | 46.3%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 27        | 55.1%   |
| 1     | 22        | 44.9%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 42        | 82.35%  |
| Yes  | 9         | 17.65%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 9         | 37.5%   |
| Broadcom                        | 4         | 16.67%  |
| Realtek Semiconductor           | 2         | 8.33%   |
| Qualcomm Atheros Communications | 2         | 8.33%   |
| Cambridge Silicon Radio         | 2         | 8.33%   |
| Realtek                         | 1         | 4.17%   |
| IMC Networks                    | 1         | 4.17%   |
| Dell                            | 1         | 4.17%   |
| ASUSTek Computer                | 1         | 4.17%   |
| Apple                           | 1         | 4.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 6         | 25%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 8.33%   |
| Realtek RTL8723B Bluetooth                          | 1         | 4.17%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 4.17%   |
| Realtek Bluetooth Radio                             | 1         | 4.17%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 4.17%   |
| Qualcomm Atheros Bluetooth                          | 1         | 4.17%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 4.17%   |
| Intel AX201 Bluetooth                               | 1         | 4.17%   |
| Intel AX200 Bluetooth                               | 1         | 4.17%   |
| IMC Networks Bluetooth Radio                        | 1         | 4.17%   |
| Dell Wireless 365 Bluetooth                         | 1         | 4.17%   |
| Broadcom HP Portable SoftSailing                    | 1         | 4.17%   |
| Broadcom BCM43142A0 Bluetooth Device                | 1         | 4.17%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 1         | 4.17%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 4.17%   |
| ASUS Broadcom Bluetooth 2.1                         | 1         | 4.17%   |
| Apple Bluetooth HCI                                 | 1         | 4.17%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 35        | 56.45%  |
| AMD                 | 14        | 22.58%  |
| Nvidia              | 8         | 12.9%   |
| VIA Technologies    | 1         | 1.61%   |
| Plantronics         | 1         | 1.61%   |
| Native Instruments  | 1         | 1.61%   |
| Focusrite-Novation  | 1         | 1.61%   |
| C-Media Electronics | 1         | 1.61%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7         | 9.72%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 5.56%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 5.56%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 4.17%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 4.17%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 4.17%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 2         | 2.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 2.78%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 2         | 2.78%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 2         | 2.78%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 2         | 2.78%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 2.78%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 2.78%   |
| AMD Barts HDMI Audio [Radeon HD 6790/6850/6870 / 7720 OEM]                                        | 2         | 2.78%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1         | 1.39%   |
| Plantronics USB DSP v4 Audio Interface                                                            | 1         | 1.39%   |
| Nvidia MCP61 High Definition Audio                                                                | 1         | 1.39%   |
| Nvidia MCP51 High Definition Audio                                                                | 1         | 1.39%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 1.39%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 1.39%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 1.39%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 1.39%   |
| Native Instruments KOMPLETE KONTROL M32                                                           | 1         | 1.39%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 1.39%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 1         | 1.39%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 1.39%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 1         | 1.39%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 1.39%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 1         | 1.39%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 1.39%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 1.39%   |
| Intel 200 Series PCH HD Audio                                                                     | 1         | 1.39%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 1.39%   |
| Focusrite-Novation Focusrite Scarlett 2i2 2nd Gen                                                 | 1         | 1.39%   |
| C-Media Electronics USB Audio Device                                                              | 1         | 1.39%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 1.39%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 1         | 1.39%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 1.39%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 1         | 1.39%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 1.39%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 9         | 24.32%  |
| Unknown             | 7         | 18.92%  |
| Kingston            | 4         | 10.81%  |
| SK hynix            | 3         | 8.11%   |
| Micron Technology   | 3         | 8.11%   |
| Corsair             | 3         | 8.11%   |
| Nanya Technology    | 2         | 5.41%   |
| G.Skill             | 2         | 5.41%   |
| GOODRAM             | 1         | 2.7%    |
| Elpida              | 1         | 2.7%    |
| Crucial             | 1         | 2.7%    |
| Avant               | 1         | 2.7%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB DIMM 800MT/s                     | 2         | 5.13%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s      | 2         | 5.13%   |
| Unknown RAM Module 2GB SODIMM SDRAM                        | 1         | 2.56%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                   | 1         | 2.56%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                | 1         | 2.56%   |
| Unknown RAM Module 1024MB SODIMM DDR2                      | 1         | 2.56%   |
| Unknown RAM Module 1024MB SODIMM 800MT/s                   | 1         | 2.56%   |
| Unknown RAM Module 1024MB DIMM SDRAM                       | 1         | 2.56%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1066MT/s               | 1         | 2.56%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s    | 1         | 2.56%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s     | 1         | 2.56%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                | 1         | 2.56%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s      | 1         | 2.56%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s   | 1         | 2.56%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s      | 1         | 2.56%   |
| Samsung RAM M471B2873FHS-CH9 1024MB SODIMM DDR3 1334MT/s   | 1         | 2.56%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s      | 1         | 2.56%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s      | 1         | 2.56%   |
| Samsung RAM K4E8E324EB-EGCF 2GB LPDDR3 1867MT/s            | 1         | 2.56%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s       | 1         | 2.56%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s       | 1         | 2.56%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s | 1         | 2.56%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s      | 1         | 2.56%   |
| Micron RAM 16JSF51264HZ-1G4D1 4096MB SODIMM DDR3 1334MT/s  | 1         | 2.56%   |
| Kingston RAM Module 16GB SODIMM DDR4 2133MT/s              | 1         | 2.56%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s        | 1         | 2.56%   |
| Kingston RAM ACR128X64D3S1333C9 1GB SODIMM DDR3 1333MT/s   | 1         | 2.56%   |
| Kingston RAM 99U5471-030.A00LF 8192MB DIMM DDR3 1333MT/s   | 1         | 2.56%   |
| GOODRAM RAM GR1600S3V64L11/8G 8GB SODIMM DDR3 1600MT/s     | 1         | 2.56%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s         | 1         | 2.56%   |
| G.Skill RAM F4-2400C16-16GRS 16GB SODIMM DDR4 2667MT/s     | 1         | 2.56%   |
| Elpida RAM EBJ81UG8BAS0-DJ-F 8GB SODIMM DDR3 1333MT/s      | 1         | 2.56%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1600MT/s      | 1         | 2.56%   |
| Corsair RAM CMZ4GX3M1A1600C9 4096MB DIMM DDR3 1600MT/s     | 1         | 2.56%   |
| Corsair RAM CMSA4GX3M1A1333C9 4GB SODIMM DDR3 1333MT/s     | 1         | 2.56%   |
| Corsair RAM CMK16GX4M2D3600C18 8GB DIMM DDR4 3600MT/s      | 1         | 2.56%   |
| Avant RAM W641GU49J2320N6 8GB DIMM DDR4 2666MT/s           | 1         | 2.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 19        | 54.29%  |
| DDR4    | 7         | 20%     |
| SDRAM   | 3         | 8.57%   |
| Unknown | 3         | 8.57%   |
| DDR2    | 2         | 5.71%   |
| LPDDR3  | 1         | 2.86%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 21        | 61.76%  |
| DIMM         | 11        | 32.35%  |
| Row Of Chips | 1         | 2.94%   |
| Unknown      | 1         | 2.94%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 12        | 30.77%  |
| 4096  | 10        | 25.64%  |
| 2048  | 10        | 25.64%  |
| 1024  | 4         | 10.26%  |
| 16384 | 3         | 7.69%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 12        | 33.33%  |
| 1333    | 4         | 11.11%  |
| 800     | 4         | 11.11%  |
| Unknown | 3         | 8.33%   |
| 3200    | 2         | 5.56%   |
| 2667    | 2         | 5.56%   |
| 1334    | 2         | 5.56%   |
| 4199    | 1         | 2.78%   |
| 3600    | 1         | 2.78%   |
| 2666    | 1         | 2.78%   |
| 2400    | 1         | 2.78%   |
| 2133    | 1         | 2.78%   |
| 1867    | 1         | 2.78%   |
| 1066    | 1         | 2.78%   |

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
| Chicony Electronics                    | 8         | 28.57%  |
| Microdia                               | 4         | 14.29%  |
| Suyin                                  | 3         | 10.71%  |
| Sunplus Innovation Technology          | 2         | 7.14%   |
| Logitech                               | 2         | 7.14%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 7.14%   |
| Acer                                   | 2         | 7.14%   |
| Z-Star Microelectronics                | 1         | 3.57%   |
| Samsung Electronics                    | 1         | 3.57%   |
| Microsoft                              | 1         | 3.57%   |
| Guillemot                              | 1         | 3.57%   |
| Unknown                                | 1         | 3.57%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Z-Star Namuga 1.3M Webcam                                   | 1         | 3.57%   |
| Suyin USB2.0 UVC 1.3M WebCam                                | 1         | 3.57%   |
| Suyin HP Truevision HD                                      | 1         | 3.57%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 3.57%   |
| Sunplus Integrated Webcam                                   | 1         | 3.57%   |
| Sunplus HP HD Webcam [Fixed]                                | 1         | 3.57%   |
| Samsung Galaxy series, misc. (MTP mode)                     | 1         | 3.57%   |
| Microsoft LifeCam Cinema                                    | 1         | 3.57%   |
| Microdia Sonix USB 2.0 Camera                               | 1         | 3.57%   |
| Microdia Lenovo EasyCamera                                  | 1         | 3.57%   |
| Microdia Laptop_Integrated_Webcam_HD                        | 1         | 3.57%   |
| Microdia Laptop_Integrated_Webcam_1.3M                      | 1         | 3.57%   |
| Logitech Webcam C270                                        | 1         | 3.57%   |
| Logitech QuickCam Notebook Pro                              | 1         | 3.57%   |
| Guillemot Hercules Dualpix Exchange                         | 1         | 3.57%   |
| Chicony TOSHIBA Web Camera - HD                             | 1         | 3.57%   |
| Chicony Integrated Camera (1280x720@30)                     | 1         | 3.57%   |
| Chicony HP TrueVision HD Camera                             | 1         | 3.57%   |
| Chicony HP Integrated Webcam                                | 1         | 3.57%   |
| Chicony HP HD Webcam                                        | 1         | 3.57%   |
| Chicony HD WebCam                                           | 1         | 3.57%   |
| Chicony Asus Integrated 0.3M UVC Webcam                     | 1         | 3.57%   |
| Chicony 2.0M UVC Webcam / CNF7129                           | 1         | 3.57%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera         | 1         | 3.57%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera            | 1         | 3.57%   |
| Acer Lenovo EasyCamera                                      | 1         | 3.57%   |
| Acer HP Webcam                                              | 1         | 3.57%   |
| Unknown                                                     | 1         | 3.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 3         | 50%     |
| STMicroelectronics         | 1         | 16.67%  |
| Shenzhen Goodix Technology | 1         | 16.67%  |
| AuthenTec                  | 1         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader | 1         | 16.67%  |
| Validity Sensors VFS491                    | 1         | 16.67%  |
| Validity Sensors VFS101 Fingerprint Reader | 1         | 16.67%  |
| STMicroelectronics Fingerprint Reader      | 1         | 16.67%  |
| Shenzhen Goodix  Fingerprint Device        | 1         | 16.67%  |
| AuthenTec AES1600                          | 1         | 16.67%  |

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
| 0     | 31        | 63.27%  |
| 1     | 14        | 28.57%  |
| 2     | 4         | 8.16%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 7         | 31.82%  |
| Fingerprint reader    | 6         | 27.27%  |
| Net/wireless          | 5         | 22.73%  |
| Multimedia controller | 2         | 9.09%   |
| Chipcard              | 1         | 4.55%   |
| Camera                | 1         | 4.55%   |

