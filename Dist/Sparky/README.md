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

Total: 71

| Vendor    | Model                       | Form-Factor | Probe                                                      | Date         |
|-----------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Acer      | Aspire E1-522               | Notebook    | [8bf37cf82d](https://linux-hardware.org/?probe=8bf37cf82d) | Dec 26, 2022 |
| HP        | Victus by Laptop 16-e0xx... | Notebook    | [54273f1267](https://linux-hardware.org/?probe=54273f1267) | Dec 22, 2022 |
| Foxconn   | 2ABF                        | Desktop     | [90af9a1be5](https://linux-hardware.org/?probe=90af9a1be5) | Dec 06, 2022 |
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

![OS](./All/images/pie_chart/os_name.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Sparky 6    | 16        | 29.09%  |
| Sparky 7    | 8         | 14.55%  |
| Sparky 6.1  | 6         | 10.91%  |
| Sparky 5.12 | 5         | 9.09%   |
| Sparky 6.5  | 4         | 7.27%   |
| Sparky 6.3  | 3         | 5.45%   |
| Sparky 6.0  | 3         | 5.45%   |
| Sparky 5.14 | 3         | 5.45%   |
| Sparky 5.10 | 3         | 5.45%   |
| Sparky 6.2  | 2         | 3.64%   |
| Sparky 5.13 | 2         | 3.64%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Sparky | 50        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                   | Computers | Percent |
|---------------------------|-----------|---------|
| 5.10.0-11-686             | 4         | 6.9%    |
| 5.10.0-9-amd64            | 3         | 5.17%   |
| 5.10.0-8-amd64            | 3         | 5.17%   |
| 5.10.0-6-amd64            | 3         | 5.17%   |
| 4.19.0-8-amd64            | 3         | 5.17%   |
| 4.19.0-12-amd64           | 3         | 5.17%   |
| 5.18.0-4-amd64            | 2         | 3.45%   |
| 5.18.0-2-amd64            | 2         | 3.45%   |
| 5.17.0-1-amd64            | 2         | 3.45%   |
| 5.10.0-3-amd64            | 2         | 3.45%   |
| 5.10.0-14-amd64           | 2         | 3.45%   |
| 4.19.0-13-686             | 2         | 3.45%   |
| 4.19.0-10-686             | 2         | 3.45%   |
| 6.0.11-x64v2-rt14-xanmod1 | 1         | 1.72%   |
| 6.0.0-5-amd64             | 1         | 1.72%   |
| 5.9.13-sparky-amd64       | 1         | 1.72%   |
| 5.9.0-4-amd64             | 1         | 1.72%   |
| 5.8.13-sparky-amd64       | 1         | 1.72%   |
| 5.8.0-2-amd64             | 1         | 1.72%   |
| 5.7.2-sparky-amd64        | 1         | 1.72%   |
| 5.6.0-2-amd64             | 1         | 1.72%   |
| 5.5.0-2-amd64             | 1         | 1.72%   |
| 5.4.7-sparky-amd64        | 1         | 1.72%   |
| 5.2.0-2-amd64             | 1         | 1.72%   |
| 5.18.3-sparky-amd64       | 1         | 1.72%   |
| 5.17.3-sparky-amd64       | 1         | 1.72%   |
| 5.16.5-sparky-amd64       | 1         | 1.72%   |
| 5.16.0-5-amd64            | 1         | 1.72%   |
| 5.15.0-3-amd64            | 1         | 1.72%   |
| 5.14.0-4-amd64            | 1         | 1.72%   |
| 5.10.4-sparky-amd64       | 1         | 1.72%   |
| 5.10.0-7-amd64            | 1         | 1.72%   |
| 5.10.0-20-amd64           | 1         | 1.72%   |
| 5.10.0-2-amd64            | 1         | 1.72%   |
| 5.10.0-19-amd64           | 1         | 1.72%   |
| 5.10.0-12-amd64           | 1         | 1.72%   |
| 4.19.0-14-686             | 1         | 1.72%   |
| 4.19.0-10-amd64           | 1         | 1.72%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 22        | 39.29%  |
| 4.19.0  | 10        | 17.86%  |
| 5.18.0  | 4         | 7.14%   |
| 5.17.0  | 2         | 3.57%   |
| 6.0.11  | 1         | 1.79%   |
| 6.0.0   | 1         | 1.79%   |
| 5.9.13  | 1         | 1.79%   |
| 5.9.0   | 1         | 1.79%   |
| 5.8.13  | 1         | 1.79%   |
| 5.8.0   | 1         | 1.79%   |
| 5.7.2   | 1         | 1.79%   |
| 5.6.0   | 1         | 1.79%   |
| 5.5.0   | 1         | 1.79%   |
| 5.4.7   | 1         | 1.79%   |
| 5.2.0   | 1         | 1.79%   |
| 5.18.3  | 1         | 1.79%   |
| 5.17.3  | 1         | 1.79%   |
| 5.16.5  | 1         | 1.79%   |
| 5.16.0  | 1         | 1.79%   |
| 5.15.0  | 1         | 1.79%   |
| 5.14.0  | 1         | 1.79%   |
| 5.10.4  | 1         | 1.79%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 23        | 41.82%  |
| 4.19    | 10        | 18.18%  |
| 5.18    | 5         | 9.09%   |
| 5.17    | 3         | 5.45%   |
| 5.9     | 2         | 3.64%   |
| 5.8     | 2         | 3.64%   |
| 5.16    | 2         | 3.64%   |
| 6.0     | 1         | 1.82%   |
| 5.7     | 1         | 1.82%   |
| 5.6     | 1         | 1.82%   |
| 5.5     | 1         | 1.82%   |
| 5.4     | 1         | 1.82%   |
| 5.2     | 1         | 1.82%   |
| 5.15    | 1         | 1.82%   |
| 5.14    | 1         | 1.82%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 44        | 88%     |
| i686   | 6         | 12%     |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| XFCE             | 18        | 35.29%  |
| LXQt             | 13        | 25.49%  |
| Unknown          | 8         | 15.69%  |
| KDE5             | 3         | 5.88%   |
| MATE             | 2         | 3.92%   |
| GNOME            | 2         | 3.92%   |
| X-Cinnamon       | 1         | 1.96%   |
| openbox          | 1         | 1.96%   |
| lightdm-xsession | 1         | 1.96%   |
| ICEWM            | 1         | 1.96%   |
| GNOME Classic    | 1         | 1.96%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 47        | 92.16%  |
| Tty  | 4         | 7.84%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 16        | 32%     |
| TDM     | 13        | 26%     |
| LightDM | 11        | 22%     |
| SDDM    | 8         | 16%     |
| XDM     | 1         | 2%      |
| GDM     | 1         | 2%      |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 14        | 28%     |
| en_GB   | 5         | 10%     |
| fr_FR   | 4         | 8%      |
| pt_BR   | 3         | 6%      |
| pl_PL   | 3         | 6%      |
| es_ES   | 3         | 6%      |
| de_DE   | 3         | 6%      |
| Unknown | 2         | 4%      |
| sv_SE   | 1         | 2%      |
| ja_JP   | 1         | 2%      |
| es_US   | 1         | 2%      |
| es_MX   | 1         | 2%      |
| es_CL   | 1         | 2%      |
| es_AR   | 1         | 2%      |
| en_ZA   | 1         | 2%      |
| en_PH   | 1         | 2%      |
| en_IN   | 1         | 2%      |
| en_DK   | 1         | 2%      |
| en_CA   | 1         | 2%      |
| de_CH   | 1         | 2%      |
| cs_CZ   | 1         | 2%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 32        | 64%     |
| EFI  | 18        | 36%     |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 45        | 90%     |
| Overlay | 2         | 4%      |
| Zfs     | 1         | 2%      |
| Ext2    | 1         | 2%      |
| Btrfs   | 1         | 2%      |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 18        | 36%     |
| MBR     | 16        | 32%     |
| Unknown | 16        | 32%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 42        | 84%     |
| Yes       | 8         | 16%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 33        | 66%     |
| Yes       | 17        | 34%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 11        | 22%     |
| Lenovo              | 5         | 10%     |
| Intel               | 5         | 10%     |
| Gigabyte Technology | 5         | 10%     |
| Dell                | 5         | 10%     |
| ASUSTek Computer    | 5         | 10%     |
| MSI                 | 3         | 6%      |
| Google              | 2         | 4%      |
| Acer                | 2         | 4%      |
| Samsung Electronics | 1         | 2%      |
| HUAWEI              | 1         | 2%      |
| Foxconn             | 1         | 2%      |
| eMachines           | 1         | 2%      |
| Beelink             | 1         | 2%      |
| Apple               | 1         | 2%      |
| Unknown             | 1         | 2%      |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| Samsung NC10                     | 1         | 2%      |
| MSI MS-7C09                      | 1         | 2%      |
| MSI MS-7B86                      | 1         | 2%      |
| MSI MS-7721                      | 1         | 2%      |
| Lenovo ThinkPad T61 7659AB7      | 1         | 2%      |
| Lenovo ThinkPad T60 2007FUG      | 1         | 2%      |
| Lenovo ThinkPad E15 20RES0GF00   | 1         | 2%      |
| Lenovo IdeaPad S206 20154        | 1         | 2%      |
| Lenovo G50-30 80G0               | 1         | 2%      |
| Intel NUC5CPYB H61145-408        | 1         | 2%      |
| Intel H61                        | 1         | 2%      |
| Intel H55                        | 1         | 2%      |
| Intel DG43RK AAE78175-402        | 1         | 2%      |
| Intel DG41TY AAE47335-300        | 1         | 2%      |
| HUAWEI HVY-WXX9                  | 1         | 2%      |
| HP t5740                         | 1         | 2%      |
| HP Stream Notebook PC 13         | 1         | 2%      |
| HP Pavilion g7                   | 1         | 2%      |
| HP Pavilion dv9000 (GA359UA#ABA) | 1         | 2%      |
| HP Pavilion dv5                  | 1         | 2%      |
| HP Laptop 17z-ca100              | 1         | 2%      |
| HP EliteDesk 800 G2 DM 65W       | 1         | 2%      |
| HP EliteDesk 705 G2 MINI         | 1         | 2%      |
| HP EliteBook Folio 9480m         | 1         | 2%      |
| HP EliteBook 8770w               | 1         | 2%      |
| HP EliteBook 745 G3              | 1         | 2%      |
| Google Swanky                    | 1         | 2%      |
| Google Banon                     | 1         | 2%      |
| Gigabyte X570S AORUS PRO AX      | 1         | 2%      |
| Gigabyte M68M-S2P                | 1         | 2%      |
| Gigabyte H97-Gaming 3            | 1         | 2%      |
| Gigabyte H410M H                 | 1         | 2%      |
| Gigabyte G41M-ES2L               | 1         | 2%      |
| Foxconn p6-2010fr                | 1         | 2%      |
| eMachines E525                   | 1         | 2%      |
| Dell OptiPlex 580                | 1         | 2%      |
| Dell Latitude XT3                | 1         | 2%      |
| Dell Inspiron N5010              | 1         | 2%      |
| Dell Inspiron 5770               | 1         | 2%      |
| Dell Inspiron 5720               | 1         | 2%      |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 3         | 6%      |
| HP Pavilion         | 3         | 6%      |
| HP EliteBook        | 3         | 6%      |
| Dell Inspiron       | 3         | 6%      |
| HP EliteDesk        | 2         | 4%      |
| Acer Aspire         | 2         | 4%      |
| Samsung NC10        | 1         | 2%      |
| MSI MS-7C09         | 1         | 2%      |
| MSI MS-7B86         | 1         | 2%      |
| MSI MS-7721         | 1         | 2%      |
| Lenovo IdeaPad      | 1         | 2%      |
| Lenovo G50-30       | 1         | 2%      |
| Intel NUC5CPYB      | 1         | 2%      |
| Intel H61           | 1         | 2%      |
| Intel H55           | 1         | 2%      |
| Intel DG43RK        | 1         | 2%      |
| Intel DG41TY        | 1         | 2%      |
| HUAWEI HVY-WXX9     | 1         | 2%      |
| HP t5740            | 1         | 2%      |
| HP Stream           | 1         | 2%      |
| HP Laptop           | 1         | 2%      |
| Google Swanky       | 1         | 2%      |
| Google Banon        | 1         | 2%      |
| Gigabyte X570S      | 1         | 2%      |
| Gigabyte M68M-S2P   | 1         | 2%      |
| Gigabyte H97-Gaming | 1         | 2%      |
| Gigabyte H410M      | 1         | 2%      |
| Gigabyte G41M-ES2L  | 1         | 2%      |
| Foxconn p6-2010fr   | 1         | 2%      |
| eMachines E525      | 1         | 2%      |
| Dell OptiPlex       | 1         | 2%      |
| Dell Latitude       | 1         | 2%      |
| Beelink BT3         | 1         | 2%      |
| ASUS S101           | 1         | 2%      |
| ASUS M70Vn          | 1         | 2%      |
| ASUS G20AJ          | 1         | 2%      |
| ASUS CROSSHAIR      | 1         | 2%      |
| ASUS 1000HE         | 1         | 2%      |
| Apple MacBook1      | 1         | 2%      |
| Unknown             | 1         | 2%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2009 | 7         | 14%     |
| 2014 | 6         | 12%     |
| 2012 | 4         | 8%      |
| 2008 | 4         | 8%      |
| 2021 | 3         | 6%      |
| 2020 | 3         | 6%      |
| 2018 | 3         | 6%      |
| 2011 | 3         | 6%      |
| 2010 | 3         | 6%      |
| 2019 | 2         | 4%      |
| 2017 | 2         | 4%      |
| 2016 | 2         | 4%      |
| 2015 | 2         | 4%      |
| 2007 | 2         | 4%      |
| 2006 | 2         | 4%      |
| 2022 | 1         | 2%      |
| 2013 | 1         | 2%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Notebook | 29        | 58%     |
| Desktop  | 20        | 40%     |
| Mini pc  | 1         | 2%      |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 50        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 48        | 96%     |
| Yes  | 2         | 4%      |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 14        | 28%     |
| 4.01-8.0   | 9         | 18%     |
| 16.01-24.0 | 7         | 14%     |
| 1.01-2.0   | 6         | 12%     |
| 2.01-3.0   | 5         | 10%     |
| 8.01-16.0  | 5         | 10%     |
| 24.01-32.0 | 2         | 4%      |
| 32.01-64.0 | 1         | 2%      |
| 0.51-1.0   | 1         | 2%      |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 23        | 42.59%  |
| 0.51-1.0 | 11        | 20.37%  |
| 2.01-3.0 | 8         | 14.81%  |
| 4.01-8.0 | 5         | 9.26%   |
| 3.01-4.0 | 4         | 7.41%   |
| 0.01-0.5 | 3         | 5.56%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 37        | 69.81%  |
| 2      | 8         | 15.09%  |
| 4      | 4         | 7.55%   |
| 6      | 2         | 3.77%   |
| 5      | 1         | 1.89%   |
| 3      | 1         | 1.89%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 31        | 62%     |
| Yes       | 19        | 38%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 45        | 90%     |
| No        | 5         | 10%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 37        | 74%     |
| No        | 13        | 26%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 25        | 50%     |
| No        | 25        | 50%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 8         | 16%     |
| Germany      | 6         | 12%     |
| UK           | 5         | 10%     |
| France       | 5         | 10%     |
| Poland       | 3         | 6%      |
| Brazil       | 3         | 6%      |
| Spain        | 2         | 4%      |
| Indonesia    | 2         | 4%      |
| Canada       | 2         | 4%      |
| Argentina    | 2         | 4%      |
| Venezuela    | 1         | 2%      |
| Switzerland  | 1         | 2%      |
| Sweden       | 1         | 2%      |
| South Africa | 1         | 2%      |
| Philippines  | 1         | 2%      |
| New Zealand  | 1         | 2%      |
| Mexico       | 1         | 2%      |
| Lebanon      | 1         | 2%      |
| Japan        | 1         | 2%      |
| India        | 1         | 2%      |
| Czechia      | 1         | 2%      |
| Chile        | 1         | 2%      |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Montreuil        | 2         | 3.7%    |
| Leipzig          | 2         | 3.7%    |
| Woking           | 1         | 1.85%   |
| Wenatchee        | 1         | 1.85%   |
| Tucson           | 1         | 1.85%   |
| Trelaze          | 1         | 1.85%   |
| Tauranga         | 1         | 1.85%   |
| Takahama         | 1         | 1.85%   |
| Surabaya         | 1         | 1.85%   |
| Spokane          | 1         | 1.85%   |
| Sin el Fil       | 1         | 1.85%   |
| San Cristóbal   | 1         | 1.85%   |
| San Antonio      | 1         | 1.85%   |
| Salina Cruz      | 1         | 1.85%   |
| Sainte-Julie     | 1         | 1.85%   |
| Rosario          | 1         | 1.85%   |
| Rio de Janeiro   | 1         | 1.85%   |
| Rio Claro        | 1         | 1.85%   |
| Quezon City      | 1         | 1.85%   |
| Pujaudran        | 1         | 1.85%   |
| Puente Alto      | 1         | 1.85%   |
| Posadas          | 1         | 1.85%   |
| Pompano Beach    | 1         | 1.85%   |
| Montreal         | 1         | 1.85%   |
| Mnisek pod Brdy  | 1         | 1.85%   |
| Miekoszyn        | 1         | 1.85%   |
| Mannheim         | 1         | 1.85%   |
| Madrid           | 1         | 1.85%   |
| Liverpool        | 1         | 1.85%   |
| Lienen           | 1         | 1.85%   |
| Koło            | 1         | 1.85%   |
| Kirkcaldy        | 1         | 1.85%   |
| Kage             | 1         | 1.85%   |
| Houston          | 1         | 1.85%   |
| Hamburg          | 1         | 1.85%   |
| Grabs            | 1         | 1.85%   |
| Gmina Bolków    | 1         | 1.85%   |
| Glasgow          | 1         | 1.85%   |
| Fuveau           | 1         | 1.85%   |
| Frankfurt (Oder) | 1         | 1.85%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 14        | 16     | 19.18%  |
| Seagate             | 14        | 21     | 19.18%  |
| Samsung Electronics | 10        | 21     | 13.7%   |
| Hitachi             | 6         | 8      | 8.22%   |
| Unknown             | 4         | 4      | 5.48%   |
| Kingston            | 3         | 3      | 4.11%   |
| Toshiba             | 2         | 2      | 2.74%   |
| SanDisk             | 2         | 3      | 2.74%   |
| Intel               | 2         | 2      | 2.74%   |
| GOODRAM             | 2         | 4      | 2.74%   |
| ASMedia             | 2         | 2      | 2.74%   |
| XPG                 | 1         | 1      | 1.37%   |
| SPCC                | 1         | 2      | 1.37%   |
| Silicon Motion      | 1         | 1      | 1.37%   |
| ORICO               | 1         | 1      | 1.37%   |
| Netac               | 1         | 1      | 1.37%   |
| Micron Technology   | 1         | 1      | 1.37%   |
| HGST                | 1         | 1      | 1.37%   |
| Gigabyte Technology | 1         | 1      | 1.37%   |
| Fujitsu             | 1         | 2      | 1.37%   |
| Crucial             | 1         | 1      | 1.37%   |
| ASUS-JM             | 1         | 1      | 1.37%   |
| A-DATA Technology   | 1         | 1      | 1.37%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| WDC WD1600BEVT-22ZCT0 160GB             | 2         | 2.5%    |
| Seagate ST500LT012-1DG142 500GB         | 2         | 2.5%    |
| Samsung HD161GJ 160GB                   | 2         | 2.5%    |
| Hitachi HTS545025B9A300 250GB           | 2         | 2.5%    |
| XPG GAMMIX S11 Pro 512GB                | 1         | 1.25%   |
| WDC WD800JD-08MSA1 80GB                 | 1         | 1.25%   |
| WDC WD7500BPVX-22JC3T0 752GB            | 1         | 1.25%   |
| WDC WD5000BEVT-22ZAT0 500GB             | 1         | 1.25%   |
| WDC WD5000AVVS-63ZWB0 500GB             | 1         | 1.25%   |
| WDC WD5000AAKS-75V0A0 500GB             | 1         | 1.25%   |
| WDC WD50 00LPLX-08ZNTT0 500GB           | 1         | 1.25%   |
| WDC WD3200BPVT-75ZEST0 320GB            | 1         | 1.25%   |
| WDC WD2500AAKX-07U6AA0 250GB            | 1         | 1.25%   |
| WDC WD1600AAJS-08L7A0 160GB             | 1         | 1.25%   |
| WDC WD10EZEX-60WN4A0 1TB                | 1         | 1.25%   |
| WDC WD10EADS-00M2B0 1TB                 | 1         | 1.25%   |
| WDC PC SN730 SDBPNTY-512G-1006 512GB    | 1         | 1.25%   |
| Unknown MMC Card  64GB                  | 1         | 1.25%   |
| Unknown MMC Card  32GB                  | 1         | 1.25%   |
| Unknown HBG4a2  32GB                    | 1         | 1.25%   |
| Unknown 016GE2  16GB                    | 1         | 1.25%   |
| Toshiba DT01ACA100 1TB                  | 1         | 1.25%   |
| Toshiba DT01ACA050 500GB                | 1         | 1.25%   |
| SPCC Solid State Disk 256GB             | 1         | 1.25%   |
| Silicon Motion PCIe-8 SSD 512GB         | 1         | 1.25%   |
| Seagate ST975042 0AS 752GB              | 1         | 1.25%   |
| Seagate ST9500325AS 500GB               | 1         | 1.25%   |
| Seagate ST9250320AS 250GB               | 1         | 1.25%   |
| Seagate ST9250315AS 250GB               | 1         | 1.25%   |
| Seagate ST9160310AS 160GB               | 1         | 1.25%   |
| Seagate ST500DM002-1BD142 500GB         | 1         | 1.25%   |
| Seagate ST3500312CS 500GB               | 1         | 1.25%   |
| Seagate ST3320418AS 320GB               | 1         | 1.25%   |
| Seagate ST2000VM003-1ET164 2TB          | 1         | 1.25%   |
| Seagate ST1000LM048-2E7172 1TB          | 1         | 1.25%   |
| Seagate ST1000LM035-1RK172 1TB          | 1         | 1.25%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 1         | 1.25%   |
| Seagate BarraCuda Q5 ZP500CV30001 500GB | 1         | 1.25%   |
| Seagate Backup+ Hub BK 8TB              | 1         | 1.25%   |
| Seagate Backup+ Desk 4TB                | 1         | 1.25%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 19     | 34.15%  |
| WDC                 | 13        | 15     | 31.71%  |
| Hitachi             | 6         | 8      | 14.63%  |
| Samsung Electronics | 3         | 10     | 7.32%   |
| Toshiba             | 2         | 2      | 4.88%   |
| HGST                | 1         | 1      | 2.44%   |
| Fujitsu             | 1         | 2      | 2.44%   |
| ASMedia             | 1         | 1      | 2.44%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 8      | 23.81%  |
| Kingston            | 3         | 3      | 14.29%  |
| Intel               | 2         | 2      | 9.52%   |
| GOODRAM             | 2         | 4      | 9.52%   |
| SPCC                | 1         | 2      | 4.76%   |
| SanDisk             | 1         | 1      | 4.76%   |
| ORICO               | 1         | 1      | 4.76%   |
| Netac               | 1         | 1      | 4.76%   |
| Micron Technology   | 1         | 1      | 4.76%   |
| Gigabyte Technology | 1         | 1      | 4.76%   |
| Crucial             | 1         | 1      | 4.76%   |
| ASUS-JM             | 1         | 1      | 4.76%   |
| ASMedia             | 1         | 1      | 4.76%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 33        | 58     | 51.56%  |
| SSD     | 18        | 27     | 28.13%  |
| NVMe    | 8         | 10     | 12.5%   |
| MMC     | 4         | 4      | 6.25%   |
| Unknown | 1         | 1      | 1.56%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 44        | 78     | 74.58%  |
| NVMe | 8         | 10     | 13.56%  |
| MMC  | 4         | 4      | 6.78%   |
| SAS  | 3         | 8      | 5.08%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 38        | 62     | 76%     |
| 0.51-1.0   | 10        | 19     | 20%     |
| 1.01-2.0   | 1         | 1      | 2%      |
| 4.01-10.0  | 1         | 3      | 2%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 15        | 29.41%  |
| 251-500        | 9         | 17.65%  |
| 501-1000       | 9         | 17.65%  |
| 1-20           | 5         | 9.8%    |
| 21-50          | 4         | 7.84%   |
| 51-100         | 3         | 5.88%   |
| 2001-3000      | 2         | 3.92%   |
| Unknown        | 2         | 3.92%   |
| More than 3000 | 1         | 1.96%   |
| 1001-2000      | 1         | 1.96%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 25        | 47.17%  |
| 21-50          | 7         | 13.21%  |
| 51-100         | 6         | 11.32%  |
| 251-500        | 4         | 7.55%   |
| 101-250        | 3         | 5.66%   |
| 501-1000       | 3         | 5.66%   |
| 1001-2000      | 2         | 3.77%   |
| Unknown        | 2         | 3.77%   |
| More than 3000 | 1         | 1.89%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


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

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| WDC               | 5         | 5      | 55.56%  |
| Seagate           | 2         | 2      | 22.22%  |
| Micron Technology | 1         | 1      | 11.11%  |
| ASMedia           | 1         | 1      | 11.11%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 5         | 5      | 62.5%   |
| Seagate | 2         | 2      | 25%     |
| ASMedia | 1         | 1      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 29        | 45     | 50%     |
| Detected | 20        | 46     | 34.48%  |
| Malfunc  | 9         | 9      | 15.52%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 32        | 59.26%  |
| AMD                      | 9         | 16.67%  |
| Samsung Electronics      | 3         | 5.56%   |
| Silicon Motion           | 2         | 3.7%    |
| Nvidia                   | 2         | 3.7%    |
| VIA Technologies         | 1         | 1.85%   |
| Seagate Technology       | 1         | 1.85%   |
| SanDisk                  | 1         | 1.85%   |
| Marvell Technology Group | 1         | 1.85%   |
| JMicron Technology       | 1         | 1.85%   |
| ADATA Technology         | 1         | 1.85%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 7         | 10.77%  |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 3         | 4.62%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 3         | 4.62%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 3.08%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 2         | 3.08%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 3.08%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 2         | 3.08%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 2         | 3.08%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 2         | 3.08%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 2         | 3.08%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 2         | 3.08%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 3.08%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 3.08%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                      | 1         | 1.54%   |
| VIA VT8237A SATA 2-Port Controller                                               | 1         | 1.54%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 1         | 1.54%   |
| Silicon Motion Non-Volatile memory controller                                    | 1         | 1.54%   |
| Seagate Non-Volatile memory controller                                           | 1         | 1.54%   |
| SanDisk WD Blue SN570 NVMe SSD                                                   | 1         | 1.54%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 1         | 1.54%   |
| Nvidia MCP61 SATA Controller                                                     | 1         | 1.54%   |
| Nvidia MCP61 IDE                                                                 | 1         | 1.54%   |
| Nvidia MCP51 Serial ATA Controller                                               | 1         | 1.54%   |
| Nvidia MCP51 IDE                                                                 | 1         | 1.54%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                        | 1         | 1.54%   |
| JMicron JMB360 AHCI Controller                                                   | 1         | 1.54%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 1         | 1.54%   |
| Intel SATA Controller [RAID mode]                                                | 1         | 1.54%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 1.54%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 1.54%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 1.54%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 1.54%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 1         | 1.54%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 1         | 1.54%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 1         | 1.54%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 1.54%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 1.54%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1         | 1.54%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 1         | 1.54%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 1         | 1.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 32        | 58.18%  |
| IDE  | 15        | 27.27%  |
| NVMe | 7         | 12.73%  |
| RAID | 1         | 1.82%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 37        | 74%     |
| AMD    | 13        | 26%     |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron CPU N2840 @ 2.16GHz             | 3         | 6%      |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 2         | 4%      |
| Intel Atom CPU N280 @ 1.66GHz                 | 2         | 4%      |
| Intel Atom CPU N270 @ 1.60GHz                 | 2         | 4%      |
| Intel Pentium Gold G5400 CPU @ 3.70GHz        | 1         | 2%      |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz   | 1         | 2%      |
| Intel Pentium CPU B950 @ 2.10GHz              | 1         | 2%      |
| Intel Genuine CPU T2400 @ 1.83GHz             | 1         | 2%      |
| Intel Core i7-4790 CPU @ 3.60GHz              | 1         | 2%      |
| Intel Core i7-4600U CPU @ 2.10GHz             | 1         | 2%      |
| Intel Core i7-3770 CPU @ 3.40GHz              | 1         | 2%      |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 1         | 2%      |
| Intel Core i7-3612QM CPU @ 2.10GHz            | 1         | 2%      |
| Intel Core i7 CPU 860 @ 2.80GHz               | 1         | 2%      |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 2%      |
| Intel Core i5-6500 CPU @ 3.20GHz              | 1         | 2%      |
| Intel Core i5-4460 CPU @ 3.20GHz              | 1         | 2%      |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 2%      |
| Intel Core i5-2500 CPU @ 3.30GHz              | 1         | 2%      |
| Intel Core i5-10400 CPU @ 2.90GHz             | 1         | 2%      |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 2%      |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 1         | 2%      |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 1         | 2%      |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 1         | 2%      |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 1         | 2%      |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 1         | 2%      |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz          | 1         | 2%      |
| Intel Core 2 CPU T5600 @ 1.83GHz              | 1         | 2%      |
| Intel Celeron CPU N3160 @ 1.60GHz             | 1         | 2%      |
| Intel Celeron CPU N3050 @ 1.60GHz             | 1         | 2%      |
| Intel Celeron CPU 900 @ 2.20GHz               | 1         | 2%      |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 1         | 2%      |
| AMD Turion 64 X2 Mobile Technology TL-64      | 1         | 2%      |
| AMD Sempron 145 Processor                     | 1         | 2%      |
| AMD Ryzen 9 5900X 12-Core Processor           | 1         | 2%      |
| AMD Ryzen 7 1800X Eight-Core Processor        | 1         | 2%      |
| AMD Ryzen 5 4600H with Radeon Graphics        | 1         | 2%      |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 2%      |
| AMD Ryzen 3 3100 4-Core Processor             | 1         | 2%      |
| AMD PRO A8-8600B R6, 10 Compute Cores 4C+6G   | 1         | 2%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 8         | 16%     |
| Intel Core i7           | 6         | 12%     |
| Intel Celeron           | 6         | 12%     |
| Intel Core 2 Duo        | 5         | 10%     |
| Intel Atom              | 5         | 10%     |
| AMD Ryzen 5             | 2         | 4%      |
| Intel Pentium Gold      | 1         | 2%      |
| Intel Pentium Dual-Core | 1         | 2%      |
| Intel Pentium           | 1         | 2%      |
| Intel Genuine           | 1         | 2%      |
| Intel Core i3           | 1         | 2%      |
| Intel Core 2 Quad       | 1         | 2%      |
| Intel Core 2            | 1         | 2%      |
| AMD Turion 64 X2 Mobile | 1         | 2%      |
| AMD Sempron             | 1         | 2%      |
| AMD Ryzen 9             | 1         | 2%      |
| AMD Ryzen 7             | 1         | 2%      |
| AMD Ryzen 3             | 1         | 2%      |
| AMD PRO A8              | 1         | 2%      |
| AMD PRO A10             | 1         | 2%      |
| AMD C-50                | 1         | 2%      |
| AMD Athlon II X2        | 1         | 2%      |
| AMD A6                  | 1         | 2%      |
| AMD A4                  | 1         | 2%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 23        | 46%     |
| 4      | 16        | 32%     |
| 1      | 7         | 14%     |
| 6      | 2         | 4%      |
| 12     | 1         | 2%      |
| 8      | 1         | 2%      |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 50        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 26        | 52%     |
| 2      | 24        | 48%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 45        | 90%     |
| 32-bit         | 5         | 10%     |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 8         | 16%     |
| 0x306a9    | 3         | 6%      |
| 0x30678    | 3         | 6%      |
| 0x206a7    | 3         | 6%      |
| 0x0600611a | 3         | 6%      |
| 0x406c4    | 2         | 4%      |
| 0x306c3    | 2         | 4%      |
| 0x20655    | 2         | 4%      |
| 0x106c2    | 2         | 4%      |
| 0x1067a    | 2         | 4%      |
| 0x10676    | 2         | 4%      |
| 0xa0653    | 1         | 2%      |
| 0x806ec    | 1         | 2%      |
| 0x806ea    | 1         | 2%      |
| 0x6fd      | 1         | 2%      |
| 0x6fb      | 1         | 2%      |
| 0x6f2      | 1         | 2%      |
| 0x506e3    | 1         | 2%      |
| 0x406c3    | 1         | 2%      |
| 0x40651    | 1         | 2%      |
| 0x106e5    | 1         | 2%      |
| 0x0a201016 | 1         | 2%      |
| 0x08701021 | 1         | 2%      |
| 0x08600106 | 1         | 2%      |
| 0x08108109 | 1         | 2%      |
| 0x08001138 | 1         | 2%      |
| 0x0700010f | 1         | 2%      |
| 0x05000029 | 1         | 2%      |
| 0x010000c8 | 1         | 2%      |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Silvermont  | 6         | 12%     |
| Penryn      | 5         | 10%     |
| Core        | 4         | 8%      |
| Bonnell     | 4         | 8%      |
| SandyBridge | 3         | 6%      |
| KabyLake    | 3         | 6%      |
| IvyBridge   | 3         | 6%      |
| Haswell     | 3         | 6%      |
| Excavator   | 3         | 6%      |
| Zen 2       | 2         | 4%      |
| Westmere    | 2         | 4%      |
| K10         | 2         | 4%      |
| Zen+        | 1         | 2%      |
| Zen 3       | 1         | 2%      |
| Zen         | 1         | 2%      |
| Skylake     | 1         | 2%      |
| P6          | 1         | 2%      |
| Nehalem     | 1         | 2%      |
| K8 Hammer   | 1         | 2%      |
| Jaguar      | 1         | 2%      |
| CometLake   | 1         | 2%      |
| Bobcat      | 1         | 2%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Intel            | 26        | 50%     |
| AMD              | 15        | 28.85%  |
| Nvidia           | 10        | 19.23%  |
| VIA Technologies | 1         | 1.92%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 4         | 6.9%    |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 3         | 5.17%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 5.17%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 5.17%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 3         | 5.17%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 3.45%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 3.45%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 3.45%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 1         | 1.72%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 1.72%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1         | 1.72%   |
| Nvidia GK104GLM [Quadro K3000M]                                                          | 1         | 1.72%   |
| Nvidia GK104 [GeForce GTX 760]                                                           | 1         | 1.72%   |
| Nvidia GF108M [GeForce GT 420M]                                                          | 1         | 1.72%   |
| Nvidia GA106 [Geforce RTX 3050]                                                          | 1         | 1.72%   |
| Nvidia G96CM [GeForce 9650M GT]                                                          | 1         | 1.72%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 1.72%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 1         | 1.72%   |
| Nvidia C51 [GeForce Go 6150]                                                             | 1         | 1.72%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1         | 1.72%   |
| Intel UHD Graphics 620                                                                   | 1         | 1.72%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.72%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.72%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 1.72%   |
| Intel HD Graphics 530                                                                    | 1         | 1.72%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 1.72%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.72%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 1.72%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1         | 1.72%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                                | 1         | 1.72%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1         | 1.72%   |
| AMD Wrestler [Radeon HD 6250]                                                            | 1         | 1.72%   |
| AMD Turks GL [FirePro V4900]                                                             | 1         | 1.72%   |
| AMD RV515/M54 [Mobility Radeon X1400]                                                    | 1         | 1.72%   |
| AMD RS880 [Radeon HD 4200]                                                               | 1         | 1.72%   |
| AMD Renoir                                                                               | 1         | 1.72%   |
| AMD Redwood LE [Radeon HD 5550/5570/5630/6390/6490/7570]                                 | 1         | 1.72%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1         | 1.72%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 1         | 1.72%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 1         | 1.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 25        | 50%     |
| 1 x AMD        | 14        | 28%     |
| 1 x Nvidia     | 9         | 18%     |
| 1 x VIA        | 1         | 2%      |
| Intel + Nvidia | 1         | 2%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 44        | 88%     |
| Unknown     | 4         | 8%      |
| Proprietary | 2         | 4%      |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 33        | 64.71%  |
| 0.01-0.5   | 8         | 15.69%  |
| 0.51-1.0   | 4         | 7.84%   |
| 1.01-2.0   | 3         | 5.88%   |
| 7.01-8.0   | 2         | 3.92%   |
| 3.01-4.0   | 1         | 1.96%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 7         | 14.89%  |
| LG Display          | 7         | 14.89%  |
| AU Optronics        | 5         | 10.64%  |
| Goldstar            | 4         | 8.51%   |
| Dell                | 3         | 6.38%   |
| Chimei Innolux      | 3         | 6.38%   |
| Lenovo              | 2         | 4.26%   |
| CPT                 | 2         | 4.26%   |
| BOE                 | 2         | 4.26%   |
| BenQ                | 2         | 4.26%   |
| AOC                 | 2         | 4.26%   |
| Unknown             | 1         | 2.13%   |
| LG Philips          | 1         | 2.13%   |
| JCH                 | 1         | 2.13%   |
| Insignia            | 1         | 2.13%   |
| Hitachi             | 1         | 2.13%   |
| HannStar            | 1         | 2.13%   |
| Apple               | 1         | 2.13%   |
| Acer                | 1         | 2.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch            | 1         | 1.96%   |
| Samsung Electronics SyncMaster SAM0581 1920x1080 477x268mm 21.5-inch | 1         | 1.96%   |
| Samsung Electronics SyncMaster SAM0116 1024x768 267x200mm 13.1-inch  | 1         | 1.96%   |
| Samsung Electronics S24D330 SAM0D93 1920x1080 530x300mm 24.0-inch    | 1         | 1.96%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch    | 1         | 1.96%   |
| Samsung Electronics S22C450 SAM09C5 1920x1080 477x268mm 21.5-inch    | 1         | 1.96%   |
| Samsung Electronics LCD Monitor SEC4F45 1280x800 331x207mm 15.4-inch | 1         | 1.96%   |
| Samsung Electronics LCD Monitor SEC4141 1366x768 344x193mm 15.5-inch | 1         | 1.96%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 1         | 1.96%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch          | 1         | 1.96%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch        | 1         | 1.96%   |
| LG Display LCD Monitor LGD059E 1920x1080 382x215mm 17.3-inch         | 1         | 1.96%   |
| LG Display LCD Monitor LGD04E1 1366x768 344x194mm 15.5-inch          | 1         | 1.96%   |
| LG Display LCD Monitor LGD03F8 1366x768 345x194mm 15.6-inch          | 1         | 1.96%   |
| LG Display LCD Monitor LGD02E1 1600x900 382x215mm 17.3-inch          | 1         | 1.96%   |
| LG Display LCD Monitor LGD0266 1366x768 344x194mm 15.5-inch          | 1         | 1.96%   |
| LG Display LCD Monitor LGD01C5 1366x768 293x165mm 13.2-inch          | 1         | 1.96%   |
| Lenovo LCD Monitor LEN4033 1440x900 303x190mm 14.1-inch              | 1         | 1.96%   |
| Lenovo LCD Monitor LEN4022 1400x1050 286x214mm 14.1-inch             | 1         | 1.96%   |
| JCH F24 JCH1919 1920x1080 520x310mm 23.8-inch                        | 1         | 1.96%   |
| Insignia NS-19E320A13 BBY0032 1680x1050 640x384mm 29.4-inch          | 1         | 1.96%   |
| Hitachi HDMI HEC0088 1920x540                                        | 1         | 1.96%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch             | 1         | 1.96%   |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                  | 1         | 1.96%   |
| Goldstar TV GSM9CF6 1360x768 708x398mm 32.0-inch                     | 1         | 1.96%   |
| Goldstar T710SH GSM436B 1280x960 310x230mm 15.2-inch                 | 1         | 1.96%   |
| Goldstar L1953H GSM4B3D 1280x1024 338x270mm 17.0-inch                | 1         | 1.96%   |
| Goldstar L1953H GSM4B3C 1280x1024 338x270mm 17.0-inch                | 1         | 1.96%   |
| Goldstar 23MP55 GSM5A23 1920x1080 510x290mm 23.1-inch                | 1         | 1.96%   |
| Dell LCD Monitor S2715H 3840x1080                                    | 1         | 1.96%   |
| Dell LCD Monitor S2715H                                              | 1         | 1.96%   |
| Dell IN1930 DELF03B 1366x768 410x230mm 18.5-inch                     | 1         | 1.96%   |
| Dell E176FP DELA014 1280x1024 338x270mm 17.0-inch                    | 1         | 1.96%   |
| CPT LCD Monitor CPT04CE 1024x600 222x130mm 10.1-inch                 | 1         | 1.96%   |
| CPT LCD Monitor CPT04C4 1024x600 222x130mm 10.1-inch                 | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch     | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 308x173mm 13.9-inch     | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN1484 1600x900 310x174mm 14.0-inch      | 1         | 1.96%   |
| BOE LCD Monitor BOE0878 1920x1080 355x200mm 16.0-inch                | 1         | 1.96%   |
| BOE LCD Monitor BOE085E 1920x1080 344x194mm 15.5-inch                | 1         | 1.96%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 16        | 32%     |
| 1366x768 (WXGA)    | 10        | 20%     |
| 1600x900 (HD+)     | 4         | 8%      |
| 1280x1024 (SXGA)   | 3         | 6%      |
| 1024x600           | 3         | 6%      |
| 1920x540           | 2         | 4%      |
| 1440x900 (WXGA+)   | 2         | 4%      |
| 1280x800 (WXGA)    | 2         | 4%      |
| 3840x1080          | 1         | 2%      |
| 2288x1287          | 1         | 2%      |
| 1680x1050 (WSXGA+) | 1         | 2%      |
| 1400x1050          | 1         | 2%      |
| 1360x768           | 1         | 2%      |
| 1280x960           | 1         | 2%      |
| 1024x768 (XGA)     | 1         | 2%      |
| Unknown            | 1         | 2%      |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 17      | 9         | 18.37%  |
| 15      | 8         | 16.33%  |
| 13      | 6         | 12.24%  |
| 23      | 5         | 10.2%   |
| 14      | 3         | 6.12%   |
| 10      | 3         | 6.12%   |
| 48      | 2         | 4.08%   |
| 24      | 2         | 4.08%   |
| 21      | 2         | 4.08%   |
| 20      | 2         | 4.08%   |
| 18      | 2         | 4.08%   |
| 16      | 2         | 4.08%   |
| 142     | 1         | 2.04%   |
| 72      | 1         | 2.04%   |
| Unknown | 1         | 2.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 15        | 30.61%  |
| 201-300        | 9         | 18.37%  |
| 501-600        | 7         | 14.29%  |
| 351-400        | 7         | 14.29%  |
| 401-500        | 6         | 12.24%  |
| 1001-1500      | 2         | 4.08%   |
| More than 2000 | 1         | 2.04%   |
| 1501-2000      | 1         | 2.04%   |
| Unknown        | 1         | 2.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 34        | 69.39%  |
| 16/10   | 5         | 10.2%   |
| 5/4     | 3         | 6.12%   |
| 4/3     | 3         | 6.12%   |
| 1.96    | 2         | 4.08%   |
| 1.00    | 1         | 2.04%   |
| Unknown | 1         | 2.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 9         | 18.37%  |
| 201-250        | 7         | 14.29%  |
| 121-130        | 6         | 12.24%  |
| 141-150        | 5         | 10.2%   |
| 81-90          | 4         | 8.16%   |
| 71-80          | 4         | 8.16%   |
| 151-200        | 4         | 8.16%   |
| 41-50          | 3         | 6.12%   |
| More than 1000 | 2         | 4.08%   |
| 501-1000       | 2         | 4.08%   |
| 131-140        | 1         | 2.04%   |
| 91-100         | 1         | 2.04%   |
| Unknown        | 1         | 2.04%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 17        | 36.17%  |
| 101-120 | 15        | 31.91%  |
| 121-160 | 10        | 21.28%  |
| 1-50    | 4         | 8.51%   |
| Unknown | 1         | 2.13%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 43        | 86%     |
| 2     | 4         | 8%      |
| 0     | 3         | 6%      |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 22        | 30.14%  |
| Intel                    | 19        | 26.03%  |
| Qualcomm Atheros         | 11        | 15.07%  |
| Broadcom Limited         | 4         | 5.48%   |
| Broadcom                 | 4         | 5.48%   |
| Ralink Technology        | 3         | 4.11%   |
| TP-Link                  | 2         | 2.74%   |
| Nvidia                   | 2         | 2.74%   |
| Marvell Technology Group | 2         | 2.74%   |
| VIA Technologies         | 1         | 1.37%   |
| Samsung Electronics      | 1         | 1.37%   |
| Ralink                   | 1         | 1.37%   |
| D-Link System            | 1         | 1.37%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 14        | 16.28%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 6         | 6.98%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 2         | 2.33%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 2         | 2.33%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 2         | 2.33%   |
| Intel Wireless 7265                                                           | 2         | 2.33%   |
| Intel Wireless 7260                                                           | 2         | 2.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2         | 2.33%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                              | 2         | 2.33%   |
| VIA VT6102/VT6103 [Rhine-II]                                                  | 1         | 1.16%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                           | 1         | 1.16%   |
| TP-Link 802.11ac WLAN Adapter                                                 | 1         | 1.16%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 1         | 1.16%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 1         | 1.16%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 1.16%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 1.16%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 1         | 1.16%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 1         | 1.16%   |
| Ralink RT5370 Wireless Adapter                                                | 1         | 1.16%   |
| Ralink RT3072 Wireless Adapter                                                | 1         | 1.16%   |
| Ralink MT7601U Wireless Adapter                                               | 1         | 1.16%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                     | 1         | 1.16%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 1         | 1.16%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 1         | 1.16%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1         | 1.16%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1         | 1.16%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1         | 1.16%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 1         | 1.16%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                         | 1         | 1.16%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 1.16%   |
| Nvidia MCP61 Ethernet                                                         | 1         | 1.16%   |
| Nvidia MCP51 Ethernet Controller                                              | 1         | 1.16%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                       | 1         | 1.16%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                          | 1         | 1.16%   |
| Intel Wireless 8260                                                           | 1         | 1.16%   |
| Intel Wireless 3165                                                           | 1         | 1.16%   |
| Intel WiFi Link 5100                                                          | 1         | 1.16%   |
| Intel Wi-Fi 6 AX200                                                           | 1         | 1.16%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                       | 1         | 1.16%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                 | 1         | 1.16%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 16        | 40%     |
| Qualcomm Atheros      | 9         | 22.5%   |
| Realtek Semiconductor | 5         | 12.5%   |
| Ralink Technology     | 3         | 7.5%    |
| TP-Link               | 2         | 5%      |
| Broadcom Limited      | 2         | 5%      |
| Ralink                | 1         | 2.5%    |
| D-Link System         | 1         | 2.5%    |
| Broadcom              | 1         | 2.5%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                                       | Computers | Percent |
|---------------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                              | 2         | 5%      |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                     | 2         | 5%      |
| Intel Wireless 7265                                                                         | 2         | 5%      |
| Intel Wireless 7260                                                                         | 2         | 5%      |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                         | 1         | 2.5%    |
| TP-Link 802.11ac WLAN Adapter                                                               | 1         | 2.5%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                                          | 1         | 2.5%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                    | 1         | 2.5%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                    | 1         | 2.5%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                    | 1         | 2.5%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                             | 1         | 2.5%    |
| Ralink RT5370 Wireless Adapter                                                              | 1         | 2.5%    |
| Ralink RT3072 Wireless Adapter                                                              | 1         | 2.5%    |
| Ralink MT7601U Wireless Adapter                                                             | 1         | 2.5%    |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                   | 1         | 2.5%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                  | 1         | 2.5%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                  | 1         | 2.5%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                            | 1         | 2.5%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                              | 1         | 2.5%    |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]               | 1         | 2.5%    |
| Intel Wireless 8260                                                                         | 1         | 2.5%    |
| Intel Wireless 3165                                                                         | 1         | 2.5%    |
| Intel WiFi Link 5100                                                                        | 1         | 2.5%    |
| Intel Wi-Fi 6 AX200                                                                         | 1         | 2.5%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                                     | 1         | 2.5%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                               | 1         | 2.5%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                       | 1         | 2.5%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                                           | 1         | 2.5%    |
| Intel Centrino Wireless-N 2230                                                              | 1         | 2.5%    |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                                | 1         | 2.5%    |
| Intel Centrino Ultimate-N 6300                                                              | 1         | 2.5%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                | 1         | 2.5%    |
| D-Link System DWA-160 802.11abgn Xtreme N Dual Band Adapter(rev.A2) [Atheros AR9170+AR9104] | 1         | 2.5%    |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter                                 | 1         | 2.5%    |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                                   | 1         | 2.5%    |
| Broadcom BCM43142 802.11b/g/n                                                               | 1         | 2.5%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 20        | 43.48%  |
| Intel                    | 10        | 21.74%  |
| Qualcomm Atheros         | 5         | 10.87%  |
| Broadcom                 | 3         | 6.52%   |
| Nvidia                   | 2         | 4.35%   |
| Marvell Technology Group | 2         | 4.35%   |
| Broadcom Limited         | 2         | 4.35%   |
| VIA Technologies         | 1         | 2.17%   |
| Samsung Electronics      | 1         | 2.17%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 14        | 30.43%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 13.04%  |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 4.35%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 4.35%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 2         | 4.35%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 2.17%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 2.17%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 2.17%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 2.17%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 2.17%   |
| Nvidia MCP61 Ethernet                                             | 1         | 2.17%   |
| Nvidia MCP51 Ethernet Controller                                  | 1         | 2.17%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 2.17%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 2.17%   |
| Intel I211 Gigabit Network Connection                             | 1         | 2.17%   |
| Intel Ethernet Controller I225-V                                  | 1         | 2.17%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 2.17%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 2.17%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 2.17%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 2.17%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 2.17%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 1         | 2.17%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 2.17%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1         | 2.17%   |
| Broadcom Limited NetLink BCM57788 Gigabit Ethernet PCIe           | 1         | 2.17%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 45        | 54.22%  |
| WiFi     | 38        | 45.78%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 30        | 54.55%  |
| Ethernet | 25        | 45.45%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 28        | 56%     |
| 1     | 22        | 44%     |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 43        | 82.69%  |
| Yes  | 9         | 17.31%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 9         | 36%     |
| Broadcom                        | 4         | 16%     |
| Realtek Semiconductor           | 2         | 8%      |
| Qualcomm Atheros Communications | 2         | 8%      |
| Cambridge Silicon Radio         | 2         | 8%      |
| Realtek                         | 1         | 4%      |
| IMC Networks                    | 1         | 4%      |
| Foxconn / Hon Hai               | 1         | 4%      |
| Dell                            | 1         | 4%      |
| ASUSTek Computer                | 1         | 4%      |
| Apple                           | 1         | 4%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 6         | 24%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 8%      |
| Realtek RTL8723B Bluetooth                          | 1         | 4%      |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 4%      |
| Realtek Bluetooth Radio                             | 1         | 4%      |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 4%      |
| Qualcomm Atheros Bluetooth                          | 1         | 4%      |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 4%      |
| Intel AX201 Bluetooth                               | 1         | 4%      |
| Intel AX200 Bluetooth                               | 1         | 4%      |
| IMC Networks Bluetooth Radio                        | 1         | 4%      |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 4%      |
| Dell Wireless 365 Bluetooth                         | 1         | 4%      |
| Broadcom HP Portable SoftSailing                    | 1         | 4%      |
| Broadcom BCM43142A0 Bluetooth Device                | 1         | 4%      |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 1         | 4%      |
| Broadcom BCM2045 Bluetooth                          | 1         | 4%      |
| ASUS Broadcom Bluetooth 2.1                         | 1         | 4%      |
| Apple Bluetooth HCI                                 | 1         | 4%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 35        | 55.56%  |
| AMD                 | 15        | 23.81%  |
| Nvidia              | 8         | 12.7%   |
| VIA Technologies    | 1         | 1.59%   |
| Plantronics         | 1         | 1.59%   |
| Native Instruments  | 1         | 1.59%   |
| Focusrite-Novation  | 1         | 1.59%   |
| C-Media Electronics | 1         | 1.59%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7         | 9.46%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 5.41%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 5.41%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 5.41%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 4.05%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 4.05%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 2         | 2.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 2.7%    |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 2         | 2.7%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 2         | 2.7%    |
| AMD Starship/Matisse HD Audio Controller                                                          | 2         | 2.7%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 2.7%    |
| AMD FCH Azalia Controller                                                                         | 2         | 2.7%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 2.7%    |
| AMD Barts HDMI Audio [Radeon HD 6790/6850/6870 / 7720 OEM]                                        | 2         | 2.7%    |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1         | 1.35%   |
| Plantronics USB DSP v4 Audio Interface                                                            | 1         | 1.35%   |
| Nvidia MCP61 High Definition Audio                                                                | 1         | 1.35%   |
| Nvidia MCP51 High Definition Audio                                                                | 1         | 1.35%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 1.35%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 1.35%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 1.35%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 1.35%   |
| Native Instruments KOMPLETE KONTROL M32                                                           | 1         | 1.35%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 1.35%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 1         | 1.35%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 1.35%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 1         | 1.35%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 1.35%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 1         | 1.35%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 1.35%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 1.35%   |
| Intel 200 Series PCH HD Audio                                                                     | 1         | 1.35%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 1.35%   |
| Focusrite-Novation Focusrite Scarlett 2i2 2nd Gen                                                 | 1         | 1.35%   |
| C-Media Electronics USB Audio Device                                                              | 1         | 1.35%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 1.35%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 1         | 1.35%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 1.35%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 1         | 1.35%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 9         | 23.68%  |
| Unknown             | 7         | 18.42%  |
| Kingston            | 5         | 13.16%  |
| SK hynix            | 3         | 7.89%   |
| Micron Technology   | 3         | 7.89%   |
| Corsair             | 3         | 7.89%   |
| Nanya Technology    | 2         | 5.26%   |
| G.Skill             | 2         | 5.26%   |
| GOODRAM             | 1         | 2.63%   |
| Elpida              | 1         | 2.63%   |
| Crucial             | 1         | 2.63%   |
| Avant               | 1         | 2.63%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB DIMM 800MT/s                     | 2         | 4.88%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s      | 2         | 4.88%   |
| Unknown RAM Module 2GB SODIMM SDRAM                        | 1         | 2.44%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                   | 1         | 2.44%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                | 1         | 2.44%   |
| Unknown RAM Module 1024MB SODIMM DDR2                      | 1         | 2.44%   |
| Unknown RAM Module 1024MB SODIMM 800MT/s                   | 1         | 2.44%   |
| Unknown RAM Module 1024MB DIMM SDRAM                       | 1         | 2.44%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1066MT/s               | 1         | 2.44%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s    | 1         | 2.44%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s     | 1         | 2.44%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                | 1         | 2.44%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s      | 1         | 2.44%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s      | 1         | 2.44%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s      | 1         | 2.44%   |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1334MT/s      | 1         | 2.44%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s      | 1         | 2.44%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s      | 1         | 2.44%   |
| Samsung RAM K4E8E324EB-EGCF 2GB LPDDR3 1867MT/s            | 1         | 2.44%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s       | 1         | 2.44%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s       | 1         | 2.44%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s | 1         | 2.44%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s      | 1         | 2.44%   |
| Micron RAM 16JSF51264HZ-1G4D1 4096MB SODIMM DDR3 1334MT/s  | 1         | 2.44%   |
| Kingston RAM Module 4GB SODIMM DDR3 800MT/s                | 1         | 2.44%   |
| Kingston RAM Module 16GB SODIMM DDR4 2133MT/s              | 1         | 2.44%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s        | 1         | 2.44%   |
| Kingston RAM ACR16D3LS1KBG/4G 4GB SODIMM DDR3 1600MT/s     | 1         | 2.44%   |
| Kingston RAM ACR128X64D3S1333C9 1GB SODIMM DDR3 1333MT/s   | 1         | 2.44%   |
| Kingston RAM 99U5471-030.A00LF 8192MB DIMM DDR3 1333MT/s   | 1         | 2.44%   |
| GOODRAM RAM GR1600S3V64L11/8G 8GB SODIMM DDR3 1600MT/s     | 1         | 2.44%   |
| G.Skill RAM F4-3200C16-8GIS 8192MB DIMM DDR4 3200MT/s      | 1         | 2.44%   |
| G.Skill RAM F4-2400C16-16GRS 16GB SODIMM DDR4 2667MT/s     | 1         | 2.44%   |
| Elpida RAM EBJ81UG8BAS0-DJ-F 8GB SODIMM DDR3 1333MT/s      | 1         | 2.44%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1600MT/s      | 1         | 2.44%   |
| Corsair RAM CMZ4GX3M1A1600C9 4GB DIMM DDR3 1600MT/s        | 1         | 2.44%   |
| Corsair RAM CMSA4GX3M1A1333C9 4GB SODIMM DDR3 1333MT/s     | 1         | 2.44%   |
| Corsair RAM CMK16GX4M2D3600C18 8GB DIMM DDR4 3600MT/s      | 1         | 2.44%   |
| Avant RAM W641GU49J2320N6 8GB DIMM DDR4 2666MT/s           | 1         | 2.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 20        | 55.56%  |
| DDR4    | 7         | 19.44%  |
| SDRAM   | 3         | 8.33%   |
| Unknown | 3         | 8.33%   |
| DDR2    | 2         | 5.56%   |
| LPDDR3  | 1         | 2.78%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 22        | 62.86%  |
| DIMM         | 11        | 31.43%  |
| Row Of Chips | 1         | 2.86%   |
| Unknown      | 1         | 2.86%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 12        | 30%     |
| 4096  | 11        | 27.5%   |
| 2048  | 10        | 25%     |
| 1024  | 4         | 10%     |
| 16384 | 3         | 7.5%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 13        | 34.21%  |
| 800     | 5         | 13.16%  |
| 1333    | 4         | 10.53%  |
| Unknown | 3         | 7.89%   |
| 3200    | 2         | 5.26%   |
| 2667    | 2         | 5.26%   |
| 1334    | 2         | 5.26%   |
| 4199    | 1         | 2.63%   |
| 3600    | 1         | 2.63%   |
| 2666    | 1         | 2.63%   |
| 2400    | 1         | 2.63%   |
| 2133    | 1         | 2.63%   |
| 1867    | 1         | 2.63%   |
| 1066    | 1         | 2.63%   |

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 9         | 31.03%  |
| Microdia                               | 4         | 13.79%  |
| Suyin                                  | 3         | 10.34%  |
| Sunplus Innovation Technology          | 2         | 6.9%    |
| Logitech                               | 2         | 6.9%    |
| Cheng Uei Precision Industry (Foxlink) | 2         | 6.9%    |
| Acer                                   | 2         | 6.9%    |
| Z-Star Microelectronics                | 1         | 3.45%   |
| Samsung Electronics                    | 1         | 3.45%   |
| Microsoft                              | 1         | 3.45%   |
| Guillemot                              | 1         | 3.45%   |
| Unknown                                | 1         | 3.45%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony HD WebCam                                           | 2         | 6.9%    |
| Z-Star Namuga 1.3M Webcam                                   | 1         | 3.45%   |
| Suyin USB2.0 UVC 1.3M WebCam                                | 1         | 3.45%   |
| Suyin HP Truevision HD                                      | 1         | 3.45%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 3.45%   |
| Sunplus Integrated Webcam                                   | 1         | 3.45%   |
| Sunplus HP HD Webcam [Fixed]                                | 1         | 3.45%   |
| Samsung Galaxy A5 (MTP)                                     | 1         | 3.45%   |
| Microsoft LifeCam Cinema                                    | 1         | 3.45%   |
| Microdia Sonix USB 2.0 Camera                               | 1         | 3.45%   |
| Microdia Lenovo EasyCamera                                  | 1         | 3.45%   |
| Microdia Laptop_Integrated_Webcam_HD                        | 1         | 3.45%   |
| Microdia Laptop_Integrated_Webcam_1.3M                      | 1         | 3.45%   |
| Logitech Webcam C270                                        | 1         | 3.45%   |
| Logitech QuickCam Notebook Pro                              | 1         | 3.45%   |
| Guillemot Hercules Dualpix Exchange                         | 1         | 3.45%   |
| Chicony TOSHIBA Web Camera - HD                             | 1         | 3.45%   |
| Chicony Integrated Camera (1280x720@30)                     | 1         | 3.45%   |
| Chicony HP TrueVision HD Camera                             | 1         | 3.45%   |
| Chicony HP Integrated Webcam                                | 1         | 3.45%   |
| Chicony HP HD Webcam                                        | 1         | 3.45%   |
| Chicony Asus Integrated 0.3M UVC Webcam                     | 1         | 3.45%   |
| Chicony 2.0M UVC Webcam / CNF7129                           | 1         | 3.45%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera         | 1         | 3.45%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera            | 1         | 3.45%   |
| Acer Lenovo EasyCamera                                      | 1         | 3.45%   |
| Acer HP Webcam                                              | 1         | 3.45%   |
| Unknown                                                     | 1         | 3.45%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 3         | 50%     |
| STMicroelectronics         | 1         | 16.67%  |
| Shenzhen Goodix Technology | 1         | 16.67%  |
| AuthenTec                  | 1         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


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
| 0     | 33        | 66%     |
| 1     | 13        | 26%     |
| 2     | 4         | 8%      |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Net/wireless          | 6         | 26.09%  |
| Graphics card         | 6         | 26.09%  |
| Fingerprint reader    | 6         | 26.09%  |
| Multimedia controller | 3         | 13.04%  |
| Chipcard              | 1         | 4.35%   |
| Camera                | 1         | 4.35%   |

