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

Total: 87

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | 0GDG8Y A00                  | Desktop     | [f0fdd509f7](https://linux-hardware.org/?probe=f0fdd509f7) | Jun 29, 2023 |
| ASUSTek       | M4N68T-M                    | Desktop     | [f0b58c9f4e](https://linux-hardware.org/?probe=f0b58c9f4e) | Jun 12, 2023 |
| ASRock        | FM2A58M-VG3+ R2.0           | Desktop     | [3e4b7afb1e](https://linux-hardware.org/?probe=3e4b7afb1e) | Jun 10, 2023 |
| Panasonic     | CFSZ5-2                     | Notebook    | [d5b1455382](https://linux-hardware.org/?probe=d5b1455382) | May 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [37dab045c7](https://linux-hardware.org/?probe=37dab045c7) | May 21, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | Notebook    | [24aaf9e627](https://linux-hardware.org/?probe=24aaf9e627) | May 13, 2023 |
| HP            | 1589                        | Desktop     | [af8e129ecd](https://linux-hardware.org/?probe=af8e129ecd) | May 04, 2023 |
| HP            | 1589                        | Desktop     | [632f486421](https://linux-hardware.org/?probe=632f486421) | Apr 27, 2023 |
| HP            | 0A5Ch                       | Desktop     | [636d94a346](https://linux-hardware.org/?probe=636d94a346) | Apr 15, 2023 |
| Apple         | MacBook1,1                  | Notebook    | [002929e495](https://linux-hardware.org/?probe=002929e495) | Mar 26, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [097be8dd03](https://linux-hardware.org/?probe=097be8dd03) | Mar 08, 2023 |
| MSI           | Alpha 15 A3DDK              | Notebook    | [c4ef9294ef](https://linux-hardware.org/?probe=c4ef9294ef) | Feb 23, 2023 |
| MSI           | Alpha 15 A3DDK              | Notebook    | [219483f968](https://linux-hardware.org/?probe=219483f968) | Feb 23, 2023 |
| Acer          | Aspire X3470                | Desktop     | [659a1f31bd](https://linux-hardware.org/?probe=659a1f31bd) | Feb 22, 2023 |
| Positivo      | CHT14B                      | Notebook    | [49eff89b98](https://linux-hardware.org/?probe=49eff89b98) | Feb 16, 2023 |
| Fujitsu Si... | STYLISTIC ST5112            | Notebook    | [c343cec0c8](https://linux-hardware.org/?probe=c343cec0c8) | Jan 30, 2023 |
| Acer          | Aspire E1-522               | Notebook    | [8bf37cf82d](https://linux-hardware.org/?probe=8bf37cf82d) | Dec 26, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [54273f1267](https://linux-hardware.org/?probe=54273f1267) | Dec 22, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [90af9a1be5](https://linux-hardware.org/?probe=90af9a1be5) | Dec 06, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [09a9309a2a](https://linux-hardware.org/?probe=09a9309a2a) | Nov 30, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [b585d891a8](https://linux-hardware.org/?probe=b585d891a8) | Nov 30, 2022 |
| Apple         | MacBook1,1                  | Notebook    | [6945006338](https://linux-hardware.org/?probe=6945006338) | Nov 15, 2022 |
| Google        | Swanky                      | Notebook    | [1a0a358398](https://linux-hardware.org/?probe=1a0a358398) | Nov 15, 2022 |
| ASUSTek       | G20AJ                       | Desktop     | [7e1557713a](https://linux-hardware.org/?probe=7e1557713a) | Sep 06, 2022 |
| ASUSTek       | M70Vn                       | Notebook    | [236d8cb74e](https://linux-hardware.org/?probe=236d8cb74e) | Aug 29, 2022 |
| Gigabyte      | X570S AORUS PRO AX          | Desktop     | [4fb948980f](https://linux-hardware.org/?probe=4fb948980f) | Aug 25, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [b4006730ce](https://linux-hardware.org/?probe=b4006730ce) | Jul 17, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [f5e7afea43](https://linux-hardware.org/?probe=f5e7afea43) | Jul 05, 2022 |
| Intel         | H61                         | Desktop     | [bf862f44d2](https://linux-hardware.org/?probe=bf862f44d2) | Jun 11, 2022 |
| HP            | Stream Notebook PC 13       | Notebook    | [47b55dbb68](https://linux-hardware.org/?probe=47b55dbb68) | Jun 06, 2022 |
| HP            | EliteBook 745 G3            | Notebook    | [fac15b2640](https://linux-hardware.org/?probe=fac15b2640) | May 18, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [803d13c6ca](https://linux-hardware.org/?probe=803d13c6ca) | May 15, 2022 |
| HP            | EliteBook 8770w             | Notebook    | [4fa8e91f6d](https://linux-hardware.org/?probe=4fa8e91f6d) | Apr 26, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [c7ea70f7ba](https://linux-hardware.org/?probe=c7ea70f7ba) | Apr 25, 2022 |
| HP            | 3641h                       | Desktop     | [d50fc13ff0](https://linux-hardware.org/?probe=d50fc13ff0) | Mar 30, 2022 |
| HP            | Pavilion dv5                | Notebook    | [22ae3dae3d](https://linux-hardware.org/?probe=22ae3dae3d) | Mar 22, 2022 |
| Intel         | H55                         | Desktop     | [baff4758b7](https://linux-hardware.org/?probe=baff4758b7) | Mar 21, 2022 |
| ASUSTek       | 1000HE                      | Notebook    | [5dd6246e59](https://linux-hardware.org/?probe=5dd6246e59) | Feb 08, 2022 |
| ASUSTek       | S101                        | Notebook    | [a850549e73](https://linux-hardware.org/?probe=a850549e73) | Feb 04, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [39dcd3854f](https://linux-hardware.org/?probe=39dcd3854f) | Feb 03, 2022 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [47eae3d6b2](https://linux-hardware.org/?probe=47eae3d6b2) | Jan 19, 2022 |
| HP            | EliteBook 8770w             | Notebook    | [9a2052fc8c](https://linux-hardware.org/?probe=9a2052fc8c) | Nov 25, 2021 |
| HP            | Pavilion g7                 | Notebook    | [6cebc99fe6](https://linux-hardware.org/?probe=6cebc99fe6) | Nov 22, 2021 |
| Dell          | Inspiron N5010              | Notebook    | [df5e66431b](https://linux-hardware.org/?probe=df5e66431b) | Nov 20, 2021 |
| HP            | EliteBook Folio 9480m       | Notebook    | [dae2e04d45](https://linux-hardware.org/?probe=dae2e04d45) | Oct 04, 2021 |
| Google        | Banon                       | Notebook    | [764debedcd](https://linux-hardware.org/?probe=764debedcd) | Sep 25, 2021 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [079af91b8f](https://linux-hardware.org/?probe=079af91b8f) | Aug 22, 2021 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [c6fe94a0ba](https://linux-hardware.org/?probe=c6fe94a0ba) | Aug 22, 2021 |
| HP            | 805B                        | Desktop     | [d6c2730444](https://linux-hardware.org/?probe=d6c2730444) | Jul 12, 2021 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [d8b0632698](https://linux-hardware.org/?probe=d8b0632698) | May 23, 2021 |
| Lenovo        | ThinkPad E15 20RES0GF00     | Notebook    | [8722c3498e](https://linux-hardware.org/?probe=8722c3498e) | May 14, 2021 |
| Intel         | NUC5CPYB H61145-408         | Mini pc     | [7243895ae4](https://linux-hardware.org/?probe=7243895ae4) | Apr 20, 2021 |
| Apple         | MacBook1,1                  | Notebook    | [cc415ab6c7](https://linux-hardware.org/?probe=cc415ab6c7) | Mar 15, 2021 |
| Samsung       | NC10                        | Notebook    | [b5909af616](https://linux-hardware.org/?probe=b5909af616) | Mar 11, 2021 |
| Samsung       | NC10                        | Notebook    | [3b8de5559e](https://linux-hardware.org/?probe=3b8de5559e) | Feb 27, 2021 |
| MSI           | A68HM-E33 V2                | Desktop     | [82a06b4bea](https://linux-hardware.org/?probe=82a06b4bea) | Feb 21, 2021 |
| Lenovo        | ThinkPad T61 7659AB7        | Notebook    | [43f03346c5](https://linux-hardware.org/?probe=43f03346c5) | Feb 19, 2021 |
| Gigabyte      | H410M H                     | Desktop     | [ee13368ccf](https://linux-hardware.org/?probe=ee13368ccf) | Feb 18, 2021 |
| Pegatron      | 2AC2A                       | Desktop     | [8a5448bc07](https://linux-hardware.org/?probe=8a5448bc07) | Jan 17, 2021 |
| Pegatron      | 2AC2A                       | Desktop     | [c76bbefc71](https://linux-hardware.org/?probe=c76bbefc71) | Jan 09, 2021 |
| Beelink       | BT3 PRO                     | Notebook    | [8dbfa4dacd](https://linux-hardware.org/?probe=8dbfa4dacd) | Jan 06, 2021 |
| Beelink       | BT3 PRO                     | Notebook    | [d85a392e02](https://linux-hardware.org/?probe=d85a392e02) | Jan 06, 2021 |
| Samsung       | NC10                        | Notebook    | [8c878860a7](https://linux-hardware.org/?probe=8c878860a7) | Jan 03, 2021 |
| Pegatron      | 2AC2A                       | Desktop     | [95ead72109](https://linux-hardware.org/?probe=95ead72109) | Dec 17, 2020 |
| HP            | 8056                        | Desktop     | [79fd2c8837](https://linux-hardware.org/?probe=79fd2c8837) | Dec 12, 2020 |
| Dell          | Inspiron 5720               | Notebook    | [d360a61780](https://linux-hardware.org/?probe=d360a61780) | Dec 08, 2020 |
| eMachines     | E525                        | Notebook    | [0c11b6b4dc](https://linux-hardware.org/?probe=0c11b6b4dc) | Nov 25, 2020 |
| Lenovo        | IdeaPad S206 20154          | Notebook    | [393f27acf7](https://linux-hardware.org/?probe=393f27acf7) | Nov 18, 2020 |
| Intel         | DG41TY AAE47335-300         | Desktop     | [e3457f83fa](https://linux-hardware.org/?probe=e3457f83fa) | Oct 22, 2020 |
| Dell          | Inspiron 5720               | Notebook    | [787263a0c6](https://linux-hardware.org/?probe=787263a0c6) | Oct 10, 2020 |
| Gigabyte      | M68M-S2P                    | Desktop     | [0e4bab3503](https://linux-hardware.org/?probe=0e4bab3503) | Oct 05, 2020 |
| HP            | Laptop 17z-ca100            | Notebook    | [2217d0703c](https://linux-hardware.org/?probe=2217d0703c) | Oct 05, 2020 |
| HP            | Laptop 17z-ca100            | Notebook    | [1927ffc179](https://linux-hardware.org/?probe=1927ffc179) | Oct 05, 2020 |
| Unknown       | 4CoreDX90-VSTA              | Desktop     | [31dbedff45](https://linux-hardware.org/?probe=31dbedff45) | Sep 10, 2020 |
| Apple         | MacBook1,1                  | Notebook    | [73b04f9de4](https://linux-hardware.org/?probe=73b04f9de4) | Aug 26, 2020 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [87c93c4148](https://linux-hardware.org/?probe=87c93c4148) | Jun 21, 2020 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [01beb1ea00](https://linux-hardware.org/?probe=01beb1ea00) | Jun 21, 2020 |
| Dell          | 039VR8 A00                  | Desktop     | [d386006ad9](https://linux-hardware.org/?probe=d386006ad9) | Jun 15, 2020 |
| Acer          | Aspire 5742G                | Notebook    | [a90fb35c67](https://linux-hardware.org/?probe=a90fb35c67) | May 01, 2020 |
| Vorke         | V1 Plus                     | Desktop     | [e371a7cf42](https://linux-hardware.org/?probe=e371a7cf42) | Mar 29, 2020 |
| Intel         | DG43RK AAE78175-402         | Desktop     | [262ba9568a](https://linux-hardware.org/?probe=262ba9568a) | Mar 22, 2020 |
| Lenovo        | ThinkPad T60 2007FUG        | Notebook    | [d552e50d7e](https://linux-hardware.org/?probe=d552e50d7e) | Mar 12, 2020 |
| Dell          | Latitude XT3                | Notebook    | [0944e88882](https://linux-hardware.org/?probe=0944e88882) | Mar 09, 2020 |
| Dell          | Inspiron 5770               | Notebook    | [a3dd71465d](https://linux-hardware.org/?probe=a3dd71465d) | Jan 06, 2020 |
| HP            | Pavilion dv9000 (GA359UA... | Notebook    | [db4a924be0](https://linux-hardware.org/?probe=db4a924be0) | Sep 07, 2019 |
| HP            | Pavilion dv9000 (GA359UA... | Notebook    | [6f024c0dd0](https://linux-hardware.org/?probe=6f024c0dd0) | Sep 03, 2019 |
| ASRock        | H61M-VG4                    | Desktop     | [93ae8e7a8c](https://linux-hardware.org/?probe=93ae8e7a8c) | Aug 18, 2019 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Sparky 6    | 16        | 23.53%  |
| Sparky 7    | 12        | 17.65%  |
| Sparky 6.1  | 6         | 8.82%   |
| Sparky 6.5  | 5         | 7.35%   |
| Sparky 5.12 | 5         | 7.35%   |
| Sparky 6.6  | 4         | 5.88%   |
| Sparky 6.7  | 3         | 4.41%   |
| Sparky 6.3  | 3         | 4.41%   |
| Sparky 6.0  | 3         | 4.41%   |
| Sparky 5.14 | 3         | 4.41%   |
| Sparky 5.10 | 3         | 4.41%   |
| Sparky 6.2  | 2         | 2.94%   |
| Sparky 5.13 | 2         | 2.94%   |
| Sparky 7.0  | 1         | 1.47%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Sparky | 62        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                   | Computers | Percent |
|---------------------------|-----------|---------|
| 5.10.0-21-amd64           | 4         | 5.63%   |
| 5.10.0-11-686             | 4         | 5.63%   |
| 5.10.0-9-amd64            | 3         | 4.23%   |
| 5.10.0-8-amd64            | 3         | 4.23%   |
| 5.10.0-6-amd64            | 3         | 4.23%   |
| 4.19.0-8-amd64            | 3         | 4.23%   |
| 4.19.0-12-amd64           | 3         | 4.23%   |
| 5.18.0-4-amd64            | 2         | 2.82%   |
| 5.18.0-2-amd64            | 2         | 2.82%   |
| 5.17.0-1-amd64            | 2         | 2.82%   |
| 5.10.0-3-amd64            | 2         | 2.82%   |
| 5.10.0-14-amd64           | 2         | 2.82%   |
| 4.19.0-13-686             | 2         | 2.82%   |
| 4.19.0-10-686             | 2         | 2.82%   |
| 6.3.3-1-liquorix-amd64    | 1         | 1.41%   |
| 6.2.0-sparky-amd64        | 1         | 1.41%   |
| 6.1.0-9-amd64             | 1         | 1.41%   |
| 6.1.0-7-amd64             | 1         | 1.41%   |
| 6.1.0-3-amd64             | 1         | 1.41%   |
| 6.0.11-x64v2-rt14-xanmod1 | 1         | 1.41%   |
| 6.0.0-5-amd64             | 1         | 1.41%   |
| 5.9.13-sparky-amd64       | 1         | 1.41%   |
| 5.9.0-4-amd64             | 1         | 1.41%   |
| 5.8.13-sparky-amd64       | 1         | 1.41%   |
| 5.8.0-2-amd64             | 1         | 1.41%   |
| 5.7.2-sparky-amd64        | 1         | 1.41%   |
| 5.6.0-2-amd64             | 1         | 1.41%   |
| 5.5.0-2-amd64             | 1         | 1.41%   |
| 5.4.7-sparky-amd64        | 1         | 1.41%   |
| 5.2.0-2-amd64             | 1         | 1.41%   |
| 5.18.3-sparky-amd64       | 1         | 1.41%   |
| 5.17.3-sparky-amd64       | 1         | 1.41%   |
| 5.16.5-sparky-amd64       | 1         | 1.41%   |
| 5.16.0-5-amd64            | 1         | 1.41%   |
| 5.15.0-3-amd64            | 1         | 1.41%   |
| 5.14.0-4-amd64            | 1         | 1.41%   |
| 5.10.4-sparky-amd64       | 1         | 1.41%   |
| 5.10.0-7-amd64            | 1         | 1.41%   |
| 5.10.0-23-amd64           | 1         | 1.41%   |
| 5.10.0-22-amd64           | 1         | 1.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 29        | 42.65%  |
| 4.19.0  | 10        | 14.71%  |
| 5.18.0  | 4         | 5.88%   |
| 6.1.0   | 3         | 4.41%   |
| 5.17.0  | 2         | 2.94%   |
| 6.3.3   | 1         | 1.47%   |
| 6.2.0   | 1         | 1.47%   |
| 6.0.11  | 1         | 1.47%   |
| 6.0.0   | 1         | 1.47%   |
| 5.9.13  | 1         | 1.47%   |
| 5.9.0   | 1         | 1.47%   |
| 5.8.13  | 1         | 1.47%   |
| 5.8.0   | 1         | 1.47%   |
| 5.7.2   | 1         | 1.47%   |
| 5.6.0   | 1         | 1.47%   |
| 5.5.0   | 1         | 1.47%   |
| 5.4.7   | 1         | 1.47%   |
| 5.2.0   | 1         | 1.47%   |
| 5.18.3  | 1         | 1.47%   |
| 5.17.3  | 1         | 1.47%   |
| 5.16.5  | 1         | 1.47%   |
| 5.16.0  | 1         | 1.47%   |
| 5.15.0  | 1         | 1.47%   |
| 5.14.0  | 1         | 1.47%   |
| 5.10.4  | 1         | 1.47%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 30        | 44.78%  |
| 4.19    | 10        | 14.93%  |
| 5.18    | 5         | 7.46%   |
| 6.1     | 3         | 4.48%   |
| 5.17    | 3         | 4.48%   |
| 5.9     | 2         | 2.99%   |
| 5.8     | 2         | 2.99%   |
| 5.16    | 2         | 2.99%   |
| 6.3     | 1         | 1.49%   |
| 6.2     | 1         | 1.49%   |
| 6.0     | 1         | 1.49%   |
| 5.7     | 1         | 1.49%   |
| 5.6     | 1         | 1.49%   |
| 5.5     | 1         | 1.49%   |
| 5.4     | 1         | 1.49%   |
| 5.2     | 1         | 1.49%   |
| 5.15    | 1         | 1.49%   |
| 5.14    | 1         | 1.49%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 56        | 90.32%  |
| i686   | 6         | 9.68%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| XFCE             | 24        | 38.1%   |
| LXQt             | 15        | 23.81%  |
| Unknown          | 8         | 12.7%   |
| KDE5             | 5         | 7.94%   |
| X-Cinnamon       | 2         | 3.17%   |
| openbox          | 2         | 3.17%   |
| MATE             | 2         | 3.17%   |
| GNOME            | 2         | 3.17%   |
| lightdm-xsession | 1         | 1.59%   |
| ICEWM            | 1         | 1.59%   |
| GNOME Classic    | 1         | 1.59%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 59        | 92.19%  |
| Tty  | 5         | 7.81%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 20        | 32.26%  |
| LightDM | 14        | 22.58%  |
| TDM     | 13        | 20.97%  |
| SDDM    | 13        | 20.97%  |
| XDM     | 1         | 1.61%   |
| GDM     | 1         | 1.61%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 18        | 29.03%  |
| en_GB   | 6         | 9.68%   |
| pt_BR   | 5         | 8.06%   |
| de_DE   | 5         | 8.06%   |
| fr_FR   | 4         | 6.45%   |
| es_ES   | 4         | 6.45%   |
| pl_PL   | 3         | 4.84%   |
| en_CA   | 2         | 3.23%   |
| Unknown | 2         | 3.23%   |
| sv_SE   | 1         | 1.61%   |
| ja_JP   | 1         | 1.61%   |
| it_IT   | 1         | 1.61%   |
| es_US   | 1         | 1.61%   |
| es_MX   | 1         | 1.61%   |
| es_CL   | 1         | 1.61%   |
| es_AR   | 1         | 1.61%   |
| en_ZA   | 1         | 1.61%   |
| en_PH   | 1         | 1.61%   |
| en_IN   | 1         | 1.61%   |
| en_DK   | 1         | 1.61%   |
| de_CH   | 1         | 1.61%   |
| cs_CZ   | 1         | 1.61%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 38        | 61.29%  |
| EFI  | 24        | 38.71%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 55        | 88.71%  |
| Overlay | 3         | 4.84%   |
| Btrfs   | 2         | 3.23%   |
| Zfs     | 1         | 1.61%   |
| Ext2    | 1         | 1.61%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 24        | 38.71%  |
| Unknown | 20        | 32.26%  |
| MBR     | 18        | 29.03%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 53        | 85.48%  |
| Yes       | 9         | 14.52%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 40        | 64.52%  |
| Yes       | 22        | 35.48%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 14        | 22.58%  |
| ASUSTek Computer    | 7         | 11.29%  |
| Dell                | 6         | 9.68%   |
| Lenovo              | 5         | 8.06%   |
| Intel               | 5         | 8.06%   |
| Gigabyte Technology | 5         | 8.06%   |
| MSI                 | 4         | 6.45%   |
| Acer                | 3         | 4.84%   |
| Google              | 2         | 3.23%   |
| Samsung Electronics | 1         | 1.61%   |
| Positivo            | 1         | 1.61%   |
| Panasonic           | 1         | 1.61%   |
| Mediacom            | 1         | 1.61%   |
| HUAWEI              | 1         | 1.61%   |
| Fujitsu Siemens     | 1         | 1.61%   |
| Foxconn             | 1         | 1.61%   |
| eMachines           | 1         | 1.61%   |
| Beelink             | 1         | 1.61%   |
| Apple               | 1         | 1.61%   |
| Unknown             | 1         | 1.61%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| Samsung NC10                          | 1         | 1.61%   |
| Positivo CHT14B                       | 1         | 1.61%   |
| Panasonic CFSZ5-2                     | 1         | 1.61%   |
| MSI MS-7C09                           | 1         | 1.61%   |
| MSI MS-7B86                           | 1         | 1.61%   |
| MSI MS-7721                           | 1         | 1.61%   |
| MSI Alpha 15 A3DDK                    | 1         | 1.61%   |
| Mediacom SmartBook 14 FullHD - SB14UC | 1         | 1.61%   |
| Lenovo ThinkPad T61 7659AB7           | 1         | 1.61%   |
| Lenovo ThinkPad T60 2007FUG           | 1         | 1.61%   |
| Lenovo ThinkPad E15 20RES0GF00        | 1         | 1.61%   |
| Lenovo IdeaPad S206 20154             | 1         | 1.61%   |
| Lenovo G50-30 80G0                    | 1         | 1.61%   |
| Intel NUC5CPYB H61145-408             | 1         | 1.61%   |
| Intel H61                             | 1         | 1.61%   |
| Intel H55                             | 1         | 1.61%   |
| Intel DG43RK AAE78175-402             | 1         | 1.61%   |
| Intel DG41TY AAE47335-300             | 1         | 1.61%   |
| HUAWEI HVY-WXX9                       | 1         | 1.61%   |
| HP Z420 Workstation                   | 1         | 1.61%   |
| HP t5740                              | 1         | 1.61%   |
| HP Stream Notebook PC 13              | 1         | 1.61%   |
| HP Pavilion x360 Convertible 14-ba0xx | 1         | 1.61%   |
| HP Pavilion g7                        | 1         | 1.61%   |
| HP Pavilion dv9000 (GA359UA#ABA)      | 1         | 1.61%   |
| HP Pavilion dv5                       | 1         | 1.61%   |
| HP Laptop 17z-ca100                   | 1         | 1.61%   |
| HP EliteDesk 800 G2 DM 65W            | 1         | 1.61%   |
| HP EliteDesk 705 G2 MINI              | 1         | 1.61%   |
| HP EliteBook Folio 9480m              | 1         | 1.61%   |
| HP EliteBook 8770w                    | 1         | 1.61%   |
| HP EliteBook 745 G3                   | 1         | 1.61%   |
| HP Compaq dc7700 Ultra-slim Desktop   | 1         | 1.61%   |
| Google Swanky                         | 1         | 1.61%   |
| Google Banon                          | 1         | 1.61%   |
| Gigabyte X570S AORUS PRO AX           | 1         | 1.61%   |
| Gigabyte M68M-S2P                     | 1         | 1.61%   |
| Gigabyte H97-Gaming 3                 | 1         | 1.61%   |
| Gigabyte H410M H                      | 1         | 1.61%   |
| Gigabyte G41M-ES2L                    | 1         | 1.61%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                      | Computers | Percent |
|---------------------------|-----------|---------|
| HP Pavilion               | 4         | 6.45%   |
| Dell Inspiron             | 4         | 6.45%   |
| Lenovo ThinkPad           | 3         | 4.84%   |
| HP EliteBook              | 3         | 4.84%   |
| Acer Aspire               | 3         | 4.84%   |
| HP EliteDesk              | 2         | 3.23%   |
| Samsung NC10              | 1         | 1.61%   |
| Positivo CHT14B           | 1         | 1.61%   |
| Panasonic CFSZ5-2         | 1         | 1.61%   |
| MSI MS-7C09               | 1         | 1.61%   |
| MSI MS-7B86               | 1         | 1.61%   |
| MSI MS-7721               | 1         | 1.61%   |
| MSI Alpha                 | 1         | 1.61%   |
| Mediacom SmartBook        | 1         | 1.61%   |
| Lenovo IdeaPad            | 1         | 1.61%   |
| Lenovo G50-30             | 1         | 1.61%   |
| Intel NUC5CPYB            | 1         | 1.61%   |
| Intel H61                 | 1         | 1.61%   |
| Intel H55                 | 1         | 1.61%   |
| Intel DG43RK              | 1         | 1.61%   |
| Intel DG41TY              | 1         | 1.61%   |
| HUAWEI HVY-WXX9           | 1         | 1.61%   |
| HP Z420                   | 1         | 1.61%   |
| HP t5740                  | 1         | 1.61%   |
| HP Stream                 | 1         | 1.61%   |
| HP Laptop                 | 1         | 1.61%   |
| HP Compaq                 | 1         | 1.61%   |
| Google Swanky             | 1         | 1.61%   |
| Google Banon              | 1         | 1.61%   |
| Gigabyte X570S            | 1         | 1.61%   |
| Gigabyte M68M-S2P         | 1         | 1.61%   |
| Gigabyte H97-Gaming       | 1         | 1.61%   |
| Gigabyte H410M            | 1         | 1.61%   |
| Gigabyte G41M-ES2L        | 1         | 1.61%   |
| Fujitsu Siemens STYLISTIC | 1         | 1.61%   |
| Foxconn p6-2010fr         | 1         | 1.61%   |
| eMachines E525            | 1         | 1.61%   |
| Dell OptiPlex             | 1         | 1.61%   |
| Dell Latitude             | 1         | 1.61%   |
| Beelink BT3               | 1         | 1.61%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2009 | 8         | 12.9%   |
| 2014 | 6         | 9.68%   |
| 2012 | 5         | 8.06%   |
| 2011 | 5         | 8.06%   |
| 2008 | 5         | 8.06%   |
| 2021 | 4         | 6.45%   |
| 2018 | 4         | 6.45%   |
| 2017 | 4         | 6.45%   |
| 2020 | 3         | 4.84%   |
| 2019 | 3         | 4.84%   |
| 2016 | 3         | 4.84%   |
| 2010 | 3         | 4.84%   |
| 2007 | 3         | 4.84%   |
| 2015 | 2         | 3.23%   |
| 2006 | 2         | 3.23%   |
| 2022 | 1         | 1.61%   |
| 2013 | 1         | 1.61%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 35        | 56.45%  |
| Desktop     | 25        | 40.32%  |
| Convertible | 1         | 1.61%   |
| Mini pc     | 1         | 1.61%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 62        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 60        | 96.77%  |
| Yes  | 2         | 3.23%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 20        | 32.26%  |
| 4.01-8.0   | 10        | 16.13%  |
| 1.01-2.0   | 8         | 12.9%   |
| 8.01-16.0  | 8         | 12.9%   |
| 16.01-24.0 | 7         | 11.29%  |
| 2.01-3.0   | 5         | 8.06%   |
| 24.01-32.0 | 2         | 3.23%   |
| 32.01-64.0 | 1         | 1.61%   |
| 0.51-1.0   | 1         | 1.61%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 30        | 45.45%  |
| 0.51-1.0 | 12        | 18.18%  |
| 2.01-3.0 | 11        | 16.67%  |
| 4.01-8.0 | 6         | 9.09%   |
| 3.01-4.0 | 4         | 6.06%   |
| 0.01-0.5 | 3         | 4.55%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 45        | 69.23%  |
| 2      | 12        | 18.46%  |
| 4      | 4         | 6.15%   |
| 6      | 2         | 3.08%   |
| 5      | 1         | 1.54%   |
| 3      | 1         | 1.54%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 41        | 66.13%  |
| Yes       | 21        | 33.87%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 54        | 87.1%   |
| No        | 8         | 12.9%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 43        | 69.35%  |
| No        | 19        | 30.65%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 32        | 51.61%  |
| Yes       | 30        | 48.39%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 10        | 16.13%  |
| Germany      | 8         | 12.9%   |
| UK           | 6         | 9.68%   |
| France       | 5         | 8.06%   |
| Brazil       | 5         | 8.06%   |
| Spain        | 3         | 4.84%   |
| Poland       | 3         | 4.84%   |
| Indonesia    | 3         | 4.84%   |
| Canada       | 3         | 4.84%   |
| Argentina    | 2         | 3.23%   |
| Venezuela    | 1         | 1.61%   |
| Switzerland  | 1         | 1.61%   |
| Sweden       | 1         | 1.61%   |
| South Africa | 1         | 1.61%   |
| Philippines  | 1         | 1.61%   |
| New Zealand  | 1         | 1.61%   |
| Mexico       | 1         | 1.61%   |
| Lebanon      | 1         | 1.61%   |
| Japan        | 1         | 1.61%   |
| Italy        | 1         | 1.61%   |
| India        | 1         | 1.61%   |
| Czechia      | 1         | 1.61%   |
| Chile        | 1         | 1.61%   |
| Belgium      | 1         | 1.61%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Montreuil           | 2         | 2.99%   |
| Leipzig             | 2         | 2.99%   |
| Woking              | 1         | 1.49%   |
| West Palm Beach     | 1         | 1.49%   |
| Wenatchee           | 1         | 1.49%   |
| Tucson              | 1         | 1.49%   |
| Trelaze             | 1         | 1.49%   |
| Tauranga            | 1         | 1.49%   |
| Takahama            | 1         | 1.49%   |
| Surabaya            | 1         | 1.49%   |
| Spokane             | 1         | 1.49%   |
| Sin el Fil          | 1         | 1.49%   |
| Santo André        | 1         | 1.49%   |
| San Cristóbal      | 1         | 1.49%   |
| San Antonio         | 1         | 1.49%   |
| Salina Cruz         | 1         | 1.49%   |
| Sainte-Julie        | 1         | 1.49%   |
| Rudersberg          | 1         | 1.49%   |
| Rosario             | 1         | 1.49%   |
| Rio de Janeiro      | 1         | 1.49%   |
| Rio Claro           | 1         | 1.49%   |
| Quezon City         | 1         | 1.49%   |
| Pujaudran           | 1         | 1.49%   |
| Puente Alto         | 1         | 1.49%   |
| Presidente Prudente | 1         | 1.49%   |
| Posadas             | 1         | 1.49%   |
| Pompano Beach       | 1         | 1.49%   |
| Munich              | 1         | 1.49%   |
| Montreal            | 1         | 1.49%   |
| Mnisek pod Brdy     | 1         | 1.49%   |
| Milano              | 1         | 1.49%   |
| Miekoszyn           | 1         | 1.49%   |
| Mannheim            | 1         | 1.49%   |
| Madrid              | 1         | 1.49%   |
| Liverpool           | 1         | 1.49%   |
| Lienen              | 1         | 1.49%   |
| Koło               | 1         | 1.49%   |
| Kirkcaldy           | 1         | 1.49%   |
| Kage                | 1         | 1.49%   |
| Jakarta             | 1         | 1.49%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 17        | 19     | 19.54%  |
| Seagate             | 16        | 23     | 18.39%  |
| Samsung Electronics | 13        | 24     | 14.94%  |
| Unknown             | 6         | 6      | 6.9%    |
| Hitachi             | 6         | 9      | 6.9%    |
| SanDisk             | 3         | 4      | 3.45%   |
| Kingston            | 3         | 3      | 3.45%   |
| Intel               | 3         | 3      | 3.45%   |
| Toshiba             | 2         | 2      | 2.3%    |
| HGST                | 2         | 2      | 2.3%    |
| GOODRAM             | 2         | 4      | 2.3%    |
| ASMedia             | 2         | 2      | 2.3%    |
| XPG                 | 1         | 1      | 1.15%   |
| SPCC                | 1         | 2      | 1.15%   |
| Silicon Motion      | 1         | 1      | 1.15%   |
| ORICO               | 1         | 1      | 1.15%   |
| Netac               | 1         | 1      | 1.15%   |
| Micron Technology   | 1         | 1      | 1.15%   |
| Gigabyte Technology | 1         | 1      | 1.15%   |
| Fujitsu             | 1         | 2      | 1.15%   |
| Crucial             | 1         | 1      | 1.15%   |
| ASUS-JM             | 1         | 1      | 1.15%   |
| A-DATA Technology   | 1         | 1      | 1.15%   |
| Unknown             | 1         | 1      | 1.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| WDC WD1600BEVT-22ZCT0 160GB          | 2         | 2.13%   |
| Unknown MMC Card  32GB               | 2         | 2.13%   |
| Seagate ST500LT012-1DG142 500GB      | 2         | 2.13%   |
| Seagate Backup+ Hub BK 6TB           | 2         | 2.13%   |
| Samsung HD161GJ 160GB                | 2         | 2.13%   |
| Hitachi HTS545025B9A300 250GB        | 2         | 2.13%   |
| XPG GAMMIX S11 Pro 512GB             | 1         | 1.06%   |
| WDC WD800JD-08MSA1 80GB              | 1         | 1.06%   |
| WDC WD7500BPVX-22JC3T0 752GB         | 1         | 1.06%   |
| WDC WD5000BEVT-22ZAT0 500GB          | 1         | 1.06%   |
| WDC WD5000AVVS-63ZWB0 500GB          | 1         | 1.06%   |
| WDC WD5000AAKS-75V0A0 500GB          | 1         | 1.06%   |
| WDC WD50 00LPLX-08ZNTT0 500GB        | 1         | 1.06%   |
| WDC WD50 00LPCX-21VHAT0 500GB        | 1         | 1.06%   |
| WDC WD3200BPVT-75ZEST0 320GB         | 1         | 1.06%   |
| WDC WD3200AAKS-75L9A0 320GB          | 1         | 1.06%   |
| WDC WD2500AAKX-07U6AA0 250GB         | 1         | 1.06%   |
| WDC WD2500AAJS-00L7A0 250GB          | 1         | 1.06%   |
| WDC WD1600AAJS-08L7A0 160GB          | 1         | 1.06%   |
| WDC WD10EZEX-60WN4A0 1TB             | 1         | 1.06%   |
| WDC WD10EADS-00M2B0 1TB              | 1         | 1.06%   |
| WDC PC SN730 SDBPNTY-512G-1006 512GB | 1         | 1.06%   |
| Unknown NCard  32GB                  | 1         | 1.06%   |
| Unknown MMC Card  64GB               | 1         | 1.06%   |
| Unknown HBG4a2  32GB                 | 1         | 1.06%   |
| Unknown 016GE2  16GB                 | 1         | 1.06%   |
| Toshiba DT01ACA100 1TB               | 1         | 1.06%   |
| Toshiba DT01ACA050 500GB             | 1         | 1.06%   |
| SPCC Solid State Disk 256GB          | 1         | 1.06%   |
| Silicon Motion PCIe-8 SSD 512GB      | 1         | 1.06%   |
| Seagate ST975042 0AS 752GB           | 1         | 1.06%   |
| Seagate ST9500325AS 500GB            | 1         | 1.06%   |
| Seagate ST9250320AS 250GB            | 1         | 1.06%   |
| Seagate ST9250315AS 250GB            | 1         | 1.06%   |
| Seagate ST9160310AS 160GB            | 1         | 1.06%   |
| Seagate ST500DM002-1BD142 500GB      | 1         | 1.06%   |
| Seagate ST3500312CS 500GB            | 1         | 1.06%   |
| Seagate ST3320418AS 320GB            | 1         | 1.06%   |
| Seagate ST2000VM003-1ET164 2TB       | 1         | 1.06%   |
| Seagate ST2000DM008-2FR102 2TB       | 1         | 1.06%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 16        | 18     | 32%     |
| Seagate             | 16        | 21     | 32%     |
| Hitachi             | 6         | 9      | 12%     |
| Samsung Electronics | 5         | 12     | 10%     |
| Toshiba             | 2         | 2      | 4%      |
| HGST                | 2         | 2      | 4%      |
| ASMedia             | 2         | 2      | 4%      |
| Fujitsu             | 1         | 2      | 2%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 8      | 22.73%  |
| Kingston            | 3         | 3      | 13.64%  |
| Intel               | 3         | 3      | 13.64%  |
| SanDisk             | 2         | 2      | 9.09%   |
| GOODRAM             | 2         | 4      | 9.09%   |
| SPCC                | 1         | 2      | 4.55%   |
| ORICO               | 1         | 1      | 4.55%   |
| Netac               | 1         | 1      | 4.55%   |
| Micron Technology   | 1         | 1      | 4.55%   |
| Gigabyte Technology | 1         | 1      | 4.55%   |
| Crucial             | 1         | 1      | 4.55%   |
| ASUS-JM             | 1         | 1      | 4.55%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 39        | 68     | 51.32%  |
| SSD     | 20        | 28     | 26.32%  |
| NVMe    | 9         | 11     | 11.84%  |
| MMC     | 7         | 7      | 9.21%   |
| Unknown | 1         | 1      | 1.32%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 51        | 87     | 70.83%  |
| NVMe | 9         | 11     | 12.5%   |
| MMC  | 7         | 7      | 9.72%   |
| SAS  | 5         | 10     | 6.94%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 44        | 70     | 73.33%  |
| 0.51-1.0   | 11        | 19     | 18.33%  |
| 1.01-2.0   | 2         | 2      | 3.33%   |
| 4.01-10.0  | 2         | 4      | 3.33%   |
| 2.01-3.0   | 1         | 1      | 1.67%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 16        | 25.4%   |
| 251-500        | 12        | 19.05%  |
| 501-1000       | 10        | 15.87%  |
| 1-20           | 7         | 11.11%  |
| 21-50          | 6         | 9.52%   |
| 2001-3000      | 4         | 6.35%   |
| 51-100         | 3         | 4.76%   |
| More than 3000 | 2         | 3.17%   |
| Unknown        | 2         | 3.17%   |
| 1001-2000      | 1         | 1.59%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 29        | 44.62%  |
| 21-50          | 9         | 13.85%  |
| 251-500        | 6         | 9.23%   |
| 51-100         | 6         | 9.23%   |
| 101-250        | 4         | 6.15%   |
| 501-1000       | 4         | 6.15%   |
| 1001-2000      | 3         | 4.62%   |
| Unknown        | 2         | 3.08%   |
| More than 3000 | 1         | 1.54%   |
| 2001-3000      | 1         | 1.54%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-22ZAT0 500GB                         | 1         | 1      | 10%     |
| WDC WD5000AVVS-63ZWB0 500GB                         | 1         | 1      | 10%     |
| WDC WD3200BPVT-75ZEST0 320GB                        | 1         | 1      | 10%     |
| WDC WD1600AAJS-08L7A0 160GB                         | 1         | 1      | 10%     |
| WDC WD10EADS-00M2B0 1TB                             | 1         | 1      | 10%     |
| Seagate ST9500325AS 500GB                           | 1         | 1      | 10%     |
| Seagate ST9250315AS 250GB                           | 1         | 1      | 10%     |
| Micron Technology MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 1      | 10%     |
| Intel SSDSC2CW060A3 64GB                            | 1         | 1      | 10%     |
| ASMedia ASMT1153E 3TB                               | 1         | 1      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| WDC               | 5         | 5      | 50%     |
| Seagate           | 2         | 2      | 20%     |
| Micron Technology | 1         | 1      | 10%     |
| Intel             | 1         | 1      | 10%     |
| ASMedia           | 1         | 1      | 10%     |

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
| HDD  | 8         | 8      | 80%     |
| SSD  | 2         | 2      | 20%     |

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
| Works    | 33        | 50     | 47.14%  |
| Detected | 27        | 55     | 38.57%  |
| Malfunc  | 10        | 10     | 14.29%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 39        | 60%     |
| AMD                       | 10        | 15.38%  |
| Samsung Electronics       | 4         | 6.15%   |
| Nvidia                    | 3         | 4.62%   |
| Silicon Motion            | 2         | 3.08%   |
| VIA Technologies          | 1         | 1.54%   |
| Seagate Technology        | 1         | 1.54%   |
| SanDisk                   | 1         | 1.54%   |
| Marvell Technology Group  | 1         | 1.54%   |
| LSI Logic / Symbios Logic | 1         | 1.54%   |
| JMicron Technology        | 1         | 1.54%   |
| ADATA Technology          | 1         | 1.54%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 8         | 9.88%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 4         | 4.94%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 3         | 3.7%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 3         | 3.7%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 3         | 3.7%    |
| Samsung NVMe SSD Controller 980                                                  | 2         | 2.47%   |
| Nvidia MCP61 SATA Controller                                                     | 2         | 2.47%   |
| Nvidia MCP61 IDE                                                                 | 2         | 2.47%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 2         | 2.47%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 2.47%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 2         | 2.47%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 2         | 2.47%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 2         | 2.47%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 2         | 2.47%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 2.47%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 2.47%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                      | 1         | 1.23%   |
| VIA VT8237A SATA 2-Port Controller                                               | 1         | 1.23%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 1         | 1.23%   |
| Silicon Motion Non-Volatile memory controller                                    | 1         | 1.23%   |
| Seagate Non-Volatile memory controller                                           | 1         | 1.23%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                               | 1         | 1.23%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 1         | 1.23%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 1         | 1.23%   |
| Nvidia MCP51 Serial ATA Controller                                               | 1         | 1.23%   |
| Nvidia MCP51 IDE                                                                 | 1         | 1.23%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                        | 1         | 1.23%   |
| LSI Logic / Symbios Logic SAS1064ET PCI-Express Fusion-MPT SAS                   | 1         | 1.23%   |
| JMicron JMB360 AHCI Controller                                                   | 1         | 1.23%   |
| Intel SATA Controller [RAID mode]                                                | 1         | 1.23%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 1.23%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 1.23%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 1.23%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                              | 1         | 1.23%   |
| Intel C600/X79 series chipset IDE-r Controller                                   | 1         | 1.23%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 1         | 1.23%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 1.23%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 1.23%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 1         | 1.23%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 1         | 1.23%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 38        | 54.29%  |
| IDE  | 20        | 28.57%  |
| NVMe | 8         | 11.43%  |
| RAID | 2         | 2.86%   |
| SAS  | 1         | 1.43%   |
| SCSI | 1         | 1.43%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 46        | 74.19%  |
| AMD    | 16        | 25.81%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Celeron CPU N2840 @ 2.16GHz           | 3         | 4.84%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 2         | 3.23%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz        | 2         | 3.23%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 2         | 3.23%   |
| Intel Atom CPU N280 @ 1.66GHz               | 2         | 3.23%   |
| Intel Atom CPU N270 @ 1.60GHz               | 2         | 3.23%   |
| Intel Xeon CPU E5-2687W 0 @ 3.10GHz         | 1         | 1.61%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz      | 1         | 1.61%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz | 1         | 1.61%   |
| Intel Pentium CPU B950 @ 2.10GHz            | 1         | 1.61%   |
| Intel Genuine CPU T2400 @ 1.83GHz           | 1         | 1.61%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1         | 1.61%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 1         | 1.61%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1         | 1.61%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 1         | 1.61%   |
| Intel Core i7-3612QM CPU @ 2.10GHz          | 1         | 1.61%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1         | 1.61%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1         | 1.61%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 1         | 1.61%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 1         | 1.61%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 1         | 1.61%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 1         | 1.61%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 1         | 1.61%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 1         | 1.61%   |
| Intel Core i5 CPU M 460 @ 2.53GHz           | 1         | 1.61%   |
| Intel Core i3-7100U CPU @ 2.40GHz           | 1         | 1.61%   |
| Intel Core i3 CPU M 380 @ 2.53GHz           | 1         | 1.61%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 1         | 1.61%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz        | 1         | 1.61%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 1         | 1.61%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz        | 1         | 1.61%   |
| Intel Core 2 CPU U7600 @ 1.20GHz            | 1         | 1.61%   |
| Intel Core 2 CPU T5600 @ 1.83GHz            | 1         | 1.61%   |
| Intel Core 2 CPU 6300 @ 1.86GHz             | 1         | 1.61%   |
| Intel Celeron N4020 CPU @ 1.10GHz           | 1         | 1.61%   |
| Intel Celeron CPU N3160 @ 1.60GHz           | 1         | 1.61%   |
| Intel Celeron CPU N3050 @ 1.60GHz           | 1         | 1.61%   |
| Intel Celeron CPU 900 @ 2.20GHz             | 1         | 1.61%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz           | 1         | 1.61%   |
| AMD Turion 64 X2 Mobile Technology TL-64    | 1         | 1.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 10        | 16.13%  |
| Intel Celeron           | 7         | 11.29%  |
| Intel Atom              | 7         | 11.29%  |
| Intel Core i7           | 6         | 9.68%   |
| Intel Core 2 Duo        | 5         | 8.06%   |
| Intel Core 2            | 3         | 4.84%   |
| Intel Core i3           | 2         | 3.23%   |
| AMD Ryzen 7             | 2         | 3.23%   |
| AMD Ryzen 5             | 2         | 3.23%   |
| AMD A6                  | 2         | 3.23%   |
| Intel Xeon              | 1         | 1.61%   |
| Intel Pentium Gold      | 1         | 1.61%   |
| Intel Pentium Dual-Core | 1         | 1.61%   |
| Intel Pentium           | 1         | 1.61%   |
| Intel Genuine           | 1         | 1.61%   |
| Intel Core 2 Quad       | 1         | 1.61%   |
| AMD Turion 64 X2 Mobile | 1         | 1.61%   |
| AMD Sempron             | 1         | 1.61%   |
| AMD Ryzen 9             | 1         | 1.61%   |
| AMD Ryzen 3             | 1         | 1.61%   |
| AMD PRO A8              | 1         | 1.61%   |
| AMD PRO A10             | 1         | 1.61%   |
| AMD C-50                | 1         | 1.61%   |
| AMD Athlon II X3        | 1         | 1.61%   |
| AMD Athlon II X2        | 1         | 1.61%   |
| AMD A4                  | 1         | 1.61%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 28        | 45.16%  |
| 4      | 21        | 33.87%  |
| 1      | 7         | 11.29%  |
| 8      | 2         | 3.23%   |
| 6      | 2         | 3.23%   |
| 12     | 1         | 1.61%   |
| 3      | 1         | 1.61%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 62        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 34        | 54.84%  |
| 2      | 28        | 45.16%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 57        | 91.94%  |
| 32-bit         | 5         | 8.06%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 9         | 14.52%  |
| 0x206a7    | 4         | 6.45%   |
| 0x6f2      | 3         | 4.84%   |
| 0x406c4    | 3         | 4.84%   |
| 0x306a9    | 3         | 4.84%   |
| 0x30678    | 3         | 4.84%   |
| 0x0600611a | 3         | 4.84%   |
| 0x406c3    | 2         | 3.23%   |
| 0x306c3    | 2         | 3.23%   |
| 0x20655    | 2         | 3.23%   |
| 0x106c2    | 2         | 3.23%   |
| 0x1067a    | 2         | 3.23%   |
| 0x10676    | 2         | 3.23%   |
| 0x08108109 | 2         | 3.23%   |
| 0xa0653    | 1         | 1.61%   |
| 0x806ec    | 1         | 1.61%   |
| 0x806ea    | 1         | 1.61%   |
| 0x806e9    | 1         | 1.61%   |
| 0x706a8    | 1         | 1.61%   |
| 0x6fd      | 1         | 1.61%   |
| 0x6fb      | 1         | 1.61%   |
| 0x506e3    | 1         | 1.61%   |
| 0x40651    | 1         | 1.61%   |
| 0x206d7    | 1         | 1.61%   |
| 0x106e5    | 1         | 1.61%   |
| 0x0a201016 | 1         | 1.61%   |
| 0x08701021 | 1         | 1.61%   |
| 0x08600106 | 1         | 1.61%   |
| 0x08001138 | 1         | 1.61%   |
| 0x0700010f | 1         | 1.61%   |
| 0x05000029 | 1         | 1.61%   |
| 0x03000027 | 1         | 1.61%   |
| 0x010000db | 1         | 1.61%   |
| 0x010000c8 | 1         | 1.61%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Silvermont    | 8         | 12.9%   |
| Core          | 6         | 9.68%   |
| SandyBridge   | 5         | 8.06%   |
| Penryn        | 5         | 8.06%   |
| KabyLake      | 4         | 6.45%   |
| Bonnell       | 4         | 6.45%   |
| K10           | 3         | 4.84%   |
| IvyBridge     | 3         | 4.84%   |
| Haswell       | 3         | 4.84%   |
| Excavator     | 3         | 4.84%   |
| Zen+          | 2         | 3.23%   |
| Zen 2         | 2         | 3.23%   |
| Westmere      | 2         | 3.23%   |
| Skylake       | 2         | 3.23%   |
| Zen 3         | 1         | 1.61%   |
| Zen           | 1         | 1.61%   |
| P6            | 1         | 1.61%   |
| Nehalem       | 1         | 1.61%   |
| K8 Hammer     | 1         | 1.61%   |
| K10 Llano     | 1         | 1.61%   |
| Jaguar        | 1         | 1.61%   |
| Goldmont plus | 1         | 1.61%   |
| CometLake     | 1         | 1.61%   |
| Bobcat        | 1         | 1.61%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Intel            | 33        | 51.56%  |
| AMD              | 17        | 26.56%  |
| Nvidia           | 13        | 20.31%  |
| VIA Technologies | 1         | 1.56%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 5         | 6.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 6.94%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 3         | 4.17%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 4.17%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 3         | 4.17%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 2.78%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 2.78%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 2.78%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 2.78%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 2.78%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 2         | 2.78%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 1         | 1.39%   |
| Nvidia GT200GL [Quadro FX 3800]                                                          | 1         | 1.39%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1         | 1.39%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 1.39%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1         | 1.39%   |
| Nvidia GK104GLM [Quadro K3000M]                                                          | 1         | 1.39%   |
| Nvidia GK104 [GeForce GTX 760]                                                           | 1         | 1.39%   |
| Nvidia GF108M [GeForce GT 420M]                                                          | 1         | 1.39%   |
| Nvidia GA106 [Geforce RTX 3050]                                                          | 1         | 1.39%   |
| Nvidia G96CM [GeForce 9650M GT]                                                          | 1         | 1.39%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 1.39%   |
| Nvidia G96CGL [Quadro FX 580]                                                            | 1         | 1.39%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 1         | 1.39%   |
| Nvidia C51 [GeForce Go 6150]                                                             | 1         | 1.39%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1         | 1.39%   |
| Intel UHD Graphics 620                                                                   | 1         | 1.39%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 1.39%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.39%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.39%   |
| Intel HD Graphics 620                                                                    | 1         | 1.39%   |
| Intel HD Graphics 530                                                                    | 1         | 1.39%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 1.39%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 1.39%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.39%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 1.39%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1         | 1.39%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                                | 1         | 1.39%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                                         | 1         | 1.39%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1         | 1.39%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 32        | 51.61%  |
| 1 x AMD        | 15        | 24.19%  |
| 1 x Nvidia     | 12        | 19.35%  |
| 2 x AMD        | 1         | 1.61%   |
| 1 x VIA        | 1         | 1.61%   |
| Intel + Nvidia | 1         | 1.61%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 55        | 88.71%  |
| Unknown     | 4         | 6.45%   |
| Proprietary | 3         | 4.84%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 40        | 63.49%  |
| 0.01-0.5   | 10        | 15.87%  |
| 1.01-2.0   | 5         | 7.94%   |
| 0.51-1.0   | 5         | 7.94%   |
| 7.01-8.0   | 2         | 3.17%   |
| 3.01-4.0   | 1         | 1.59%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 8         | 13.79%  |
| LG Display          | 7         | 12.07%  |
| AU Optronics        | 6         | 10.34%  |
| Goldstar            | 5         | 8.62%   |
| BOE                 | 5         | 8.62%   |
| Chimei Innolux      | 4         | 6.9%    |
| Dell                | 3         | 5.17%   |
| CPT                 | 3         | 5.17%   |
| Lenovo              | 2         | 3.45%   |
| BenQ                | 2         | 3.45%   |
| AOC                 | 2         | 3.45%   |
| Acer                | 2         | 3.45%   |
| Unknown             | 1         | 1.72%   |
| Toshiba             | 1         | 1.72%   |
| Medion              | 1         | 1.72%   |
| LG Philips          | 1         | 1.72%   |
| JCH                 | 1         | 1.72%   |
| Insignia            | 1         | 1.72%   |
| Hitachi             | 1         | 1.72%   |
| HannStar            | 1         | 1.72%   |
| Apple               | 1         | 1.72%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 1         | 1.61%   |
| Toshiba TV TSB0206 1920x1080 886x498mm 40.0-inch                      | 1         | 1.61%   |
| Samsung Electronics SyncMaster SAM0581 1920x1080 477x268mm 21.5-inch  | 1         | 1.61%   |
| Samsung Electronics SyncMaster SAM0116 1024x768 267x200mm 13.1-inch   | 1         | 1.61%   |
| Samsung Electronics SA300/SA350 SAM078F 1920x1080 477x268mm 21.5-inch | 1         | 1.61%   |
| Samsung Electronics S24D330 SAM0D93 1920x1080 531x299mm 24.0-inch     | 1         | 1.61%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch     | 1         | 1.61%   |
| Samsung Electronics S22C450 SAM09C5 1920x1080 477x268mm 21.5-inch     | 1         | 1.61%   |
| Samsung Electronics LCD Monitor SEC4F45 1280x800 331x207mm 15.4-inch  | 1         | 1.61%   |
| Samsung Electronics LCD Monitor SEC4141 1366x768 344x193mm 15.5-inch  | 1         | 1.61%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1         | 1.61%   |
| Medion MD 20310 MED3645 1920x1080 521x293mm 23.5-inch                 | 1         | 1.61%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch           | 1         | 1.61%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch         | 1         | 1.61%   |
| LG Display LCD Monitor LGD059E 1920x1080 382x215mm 17.3-inch          | 1         | 1.61%   |
| LG Display LCD Monitor LGD04E1 1366x768 344x194mm 15.5-inch           | 1         | 1.61%   |
| LG Display LCD Monitor LGD03F8 1366x768 345x194mm 15.6-inch           | 1         | 1.61%   |
| LG Display LCD Monitor LGD02E1 1600x900 382x215mm 17.3-inch           | 1         | 1.61%   |
| LG Display LCD Monitor LGD0266 1366x768 344x194mm 15.5-inch           | 1         | 1.61%   |
| LG Display LCD Monitor LGD01C5 1366x768 293x165mm 13.2-inch           | 1         | 1.61%   |
| Lenovo LCD Monitor LEN4033 1440x900 304x190mm 14.1-inch               | 1         | 1.61%   |
| Lenovo LCD Monitor LEN4022 1400x1050 286x214mm 14.1-inch              | 1         | 1.61%   |
| JCH F24 JCH1919 1920x1080 520x310mm 23.8-inch                         | 1         | 1.61%   |
| Insignia NS32DD200NA14 BBY0032 1680x1050 700x390mm 31.5-inch          | 1         | 1.61%   |
| Hitachi HDMI HEC0088 1920x540                                         | 1         | 1.61%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch              | 1         | 1.61%   |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                   | 1         | 1.61%   |
| Goldstar W2042 GSM4E7E 1680x1050 434x270mm 20.1-inch                  | 1         | 1.61%   |
| Goldstar TV GSM9CF6 1360x768 708x398mm 32.0-inch                      | 1         | 1.61%   |
| Goldstar T710SH GSM436B 1280x960 310x230mm 15.2-inch                  | 1         | 1.61%   |
| Goldstar L1953H GSM4B3D 1280x1024 338x270mm 17.0-inch                 | 1         | 1.61%   |
| Goldstar L1953H GSM4B3C 1280x1024 338x270mm 17.0-inch                 | 1         | 1.61%   |
| Goldstar 23MP55 GSM5A23 1920x1080 510x290mm 23.1-inch                 | 1         | 1.61%   |
| Dell LCD Monitor S2715H 3840x1080                                     | 1         | 1.61%   |
| Dell LCD Monitor S2715H                                               | 1         | 1.61%   |
| Dell IN1930 DELF03B 1366x768 410x230mm 18.5-inch                      | 1         | 1.61%   |
| Dell E176FP DELA014 1280x1024 340x270mm 17.1-inch                     | 1         | 1.61%   |
| CPT LCD Monitor CPT37D5 1920x1200 260x160mm 12.0-inch                 | 1         | 1.61%   |
| CPT LCD Monitor CPT04CE 1024x600 222x130mm 10.1-inch                  | 1         | 1.61%   |
| CPT LCD Monitor CPT04C4 1024x600 222x130mm 10.1-inch                  | 1         | 1.61%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 23        | 37.7%   |
| 1366x768 (WXGA)    | 12        | 19.67%  |
| 1600x900 (HD+)     | 4         | 6.56%   |
| 1280x1024 (SXGA)   | 3         | 4.92%   |
| 1024x600           | 3         | 4.92%   |
| 1920x540           | 2         | 3.28%   |
| 1680x1050 (WSXGA+) | 2         | 3.28%   |
| 1440x900 (WXGA+)   | 2         | 3.28%   |
| 1280x800 (WXGA)    | 2         | 3.28%   |
| 3840x1080          | 1         | 1.64%   |
| 2288x1287          | 1         | 1.64%   |
| 1920x1200 (WUXGA)  | 1         | 1.64%   |
| 1400x1050          | 1         | 1.64%   |
| 1360x768           | 1         | 1.64%   |
| 1280x960           | 1         | 1.64%   |
| 1024x768 (XGA)     | 1         | 1.64%   |
| Unknown            | 1         | 1.64%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 17      | 9         | 15%     |
| 15      | 9         | 15%     |
| 13      | 9         | 15%     |
| 23      | 6         | 10%     |
| 14      | 4         | 6.67%   |
| 21      | 3         | 5%      |
| 20      | 3         | 5%      |
| 10      | 3         | 5%      |
| 48      | 2         | 3.33%   |
| 24      | 2         | 3.33%   |
| 18      | 2         | 3.33%   |
| 16      | 2         | 3.33%   |
| 142     | 1         | 1.67%   |
| 74      | 1         | 1.67%   |
| 72      | 1         | 1.67%   |
| 27      | 1         | 1.67%   |
| 12      | 1         | 1.67%   |
| Unknown | 1         | 1.67%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 20        | 33.33%  |
| 201-300        | 10        | 16.67%  |
| 501-600        | 9         | 15%     |
| 401-500        | 8         | 13.33%  |
| 351-400        | 7         | 11.67%  |
| 1501-2000      | 2         | 3.33%   |
| 1001-1500      | 2         | 3.33%   |
| More than 2000 | 1         | 1.67%   |
| Unknown        | 1         | 1.67%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 42        | 70%     |
| 16/10   | 8         | 13.33%  |
| 5/4     | 3         | 5%      |
| 4/3     | 3         | 5%      |
| 1.96    | 2         | 3.33%   |
| 1.00    | 1         | 1.67%   |
| Unknown | 1         | 1.67%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 10        | 16.67%  |
| 201-250        | 9         | 15%     |
| 81-90          | 8         | 13.33%  |
| 121-130        | 6         | 10%     |
| 151-200        | 5         | 8.33%   |
| 141-150        | 5         | 8.33%   |
| 71-80          | 4         | 6.67%   |
| More than 1000 | 3         | 5%      |
| 41-50          | 3         | 5%      |
| 501-1000       | 2         | 3.33%   |
| 61-70          | 1         | 1.67%   |
| 301-350        | 1         | 1.67%   |
| 131-140        | 1         | 1.67%   |
| 91-100         | 1         | 1.67%   |
| Unknown        | 1         | 1.67%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 20        | 34.48%  |
| 101-120 | 18        | 31.03%  |
| 121-160 | 13        | 22.41%  |
| 1-50    | 5         | 8.62%   |
| 161-240 | 1         | 1.72%   |
| Unknown | 1         | 1.72%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 55        | 88.71%  |
| 2     | 4         | 6.45%   |
| 0     | 3         | 4.84%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 27        | 30.68%  |
| Intel                    | 24        | 27.27%  |
| Qualcomm Atheros         | 11        | 12.5%   |
| Broadcom                 | 5         | 5.68%   |
| Broadcom Limited         | 4         | 4.55%   |
| Ralink Technology        | 3         | 3.41%   |
| Nvidia                   | 3         | 3.41%   |
| Marvell Technology Group | 3         | 3.41%   |
| TP-Link                  | 2         | 2.27%   |
| VIA Technologies         | 1         | 1.14%   |
| Samsung Electronics      | 1         | 1.14%   |
| Ralink                   | 1         | 1.14%   |
| OPPO Electronics         | 1         | 1.14%   |
| Edimax Technology        | 1         | 1.14%   |
| D-Link System            | 1         | 1.14%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 16        | 15.53%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 6         | 5.83%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 3         | 2.91%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 2         | 1.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 2         | 1.94%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 2         | 1.94%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 2         | 1.94%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 2         | 1.94%   |
| Nvidia MCP61 Ethernet                                                         | 2         | 1.94%   |
| Intel Wireless 8260                                                           | 2         | 1.94%   |
| Intel Wireless 7265                                                           | 2         | 1.94%   |
| Intel Wireless 7260                                                           | 2         | 1.94%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 2         | 1.94%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                              | 2         | 1.94%   |
| VIA VT6102/VT6103 [Rhine-II]                                                  | 1         | 0.97%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                           | 1         | 0.97%   |
| TP-Link 802.11ac WLAN Adapter                                                 | 1         | 0.97%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 1         | 0.97%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 1         | 0.97%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.97%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 1         | 0.97%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 1         | 0.97%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                              | 1         | 0.97%   |
| Ralink RT5370 Wireless Adapter                                                | 1         | 0.97%   |
| Ralink RT3072 Wireless Adapter                                                | 1         | 0.97%   |
| Ralink MT7601U Wireless Adapter                                               | 1         | 0.97%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                     | 1         | 0.97%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 1         | 0.97%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 1         | 0.97%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1         | 0.97%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1         | 0.97%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1         | 0.97%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 1         | 0.97%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                         | 1         | 0.97%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 0.97%   |
| OPPO CPH2411                                                                  | 1         | 0.97%   |
| Nvidia MCP51 Ethernet Controller                                              | 1         | 0.97%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                       | 1         | 0.97%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                       | 1         | 0.97%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                          | 1         | 0.97%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 19        | 40.43%  |
| Qualcomm Atheros      | 9         | 19.15%  |
| Realtek Semiconductor | 8         | 17.02%  |
| Ralink Technology     | 3         | 6.38%   |
| TP-Link               | 2         | 4.26%   |
| Broadcom Limited      | 2         | 4.26%   |
| Ralink                | 1         | 2.13%   |
| Edimax Technology     | 1         | 2.13%   |
| D-Link System         | 1         | 2.13%   |
| Broadcom              | 1         | 2.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                                       | Computers | Percent |
|---------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                    | 2         | 4.26%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                    | 2         | 4.26%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                              | 2         | 4.26%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                     | 2         | 4.26%   |
| Intel Wireless 8260                                                                         | 2         | 4.26%   |
| Intel Wireless 7265                                                                         | 2         | 4.26%   |
| Intel Wireless 7260                                                                         | 2         | 4.26%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                       | 2         | 4.26%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                         | 1         | 2.13%   |
| TP-Link 802.11ac WLAN Adapter                                                               | 1         | 2.13%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                          | 1         | 2.13%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                    | 1         | 2.13%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                             | 1         | 2.13%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                         | 1         | 2.13%   |
| Ralink RT5370 Wireless Adapter                                                              | 1         | 2.13%   |
| Ralink RT3072 Wireless Adapter                                                              | 1         | 2.13%   |
| Ralink MT7601U Wireless Adapter                                                             | 1         | 2.13%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                   | 1         | 2.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                  | 1         | 2.13%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                  | 1         | 2.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                            | 1         | 2.13%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                              | 1         | 2.13%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]               | 1         | 2.13%   |
| Intel Wireless 3165                                                                         | 1         | 2.13%   |
| Intel WiFi Link 5100                                                                        | 1         | 2.13%   |
| Intel Wi-Fi 6 AX200                                                                         | 1         | 2.13%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                                     | 1         | 2.13%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                               | 1         | 2.13%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                            | 1         | 2.13%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                           | 1         | 2.13%   |
| Intel Centrino Wireless-N 2230                                                              | 1         | 2.13%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                                | 1         | 2.13%   |
| Intel Centrino Ultimate-N 6300                                                              | 1         | 2.13%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                | 1         | 2.13%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                              | 1         | 2.13%   |
| D-Link System DWA-160 802.11abgn Xtreme N Dual Band Adapter(rev.A2) [Atheros AR9170+AR9104] | 1         | 2.13%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter                                 | 1         | 2.13%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                                   | 1         | 2.13%   |
| Broadcom BCM43142 802.11b/g/n                                                               | 1         | 2.13%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 23        | 41.07%  |
| Intel                    | 13        | 23.21%  |
| Qualcomm Atheros         | 5         | 8.93%   |
| Broadcom                 | 4         | 7.14%   |
| Nvidia                   | 3         | 5.36%   |
| Marvell Technology Group | 3         | 5.36%   |
| Broadcom Limited         | 2         | 3.57%   |
| VIA Technologies         | 1         | 1.79%   |
| Samsung Electronics      | 1         | 1.79%   |
| OPPO Electronics         | 1         | 1.79%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 16        | 28.57%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 10.71%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 5.36%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 3.57%   |
| Nvidia MCP61 Ethernet                                             | 2         | 3.57%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 2         | 3.57%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 1.79%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.79%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 1.79%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.79%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 1.79%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.79%   |
| OPPO CPH2411                                                      | 1         | 1.79%   |
| Nvidia MCP51 Ethernet Controller                                  | 1         | 1.79%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 1.79%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 1.79%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 1.79%   |
| Intel I211 Gigabit Network Connection                             | 1         | 1.79%   |
| Intel Ethernet Controller I225-V                                  | 1         | 1.79%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.79%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.79%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.79%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 1.79%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 1.79%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 1.79%   |
| Intel 82566DM Gigabit Network Connection                          | 1         | 1.79%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 1         | 1.79%   |
| Broadcom NetXtreme BCM5721 Gigabit Ethernet PCI Express           | 1         | 1.79%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.79%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1         | 1.79%   |
| Broadcom Limited NetLink BCM57788 Gigabit Ethernet PCIe           | 1         | 1.79%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 54        | 55.1%   |
| WiFi     | 44        | 44.9%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 34        | 51.52%  |
| Ethernet | 32        | 48.48%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 31        | 50%     |
| 1     | 28        | 45.16%  |
| 0     | 2         | 3.23%   |
| 3     | 1         | 1.61%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 52        | 81.25%  |
| Yes  | 12        | 18.75%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 11        | 36.67%  |
| Broadcom                        | 4         | 13.33%  |
| IMC Networks                    | 3         | 10%     |
| Realtek Semiconductor           | 2         | 6.67%   |
| Qualcomm Atheros Communications | 2         | 6.67%   |
| Cambridge Silicon Radio         | 2         | 6.67%   |
| Taiyo Yuden                     | 1         | 3.33%   |
| Realtek                         | 1         | 3.33%   |
| Foxconn / Hon Hai               | 1         | 3.33%   |
| Dell                            | 1         | 3.33%   |
| ASUSTek Computer                | 1         | 3.33%   |
| Apple                           | 1         | 3.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 7         | 23.33%  |
| IMC Networks Bluetooth Radio                        | 3         | 10%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 6.67%   |
| Taiyo Yuden Bluetooth Device (V2.0+EDR)             | 1         | 3.33%   |
| Realtek RTL8723B Bluetooth                          | 1         | 3.33%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 3.33%   |
| Realtek Bluetooth Radio                             | 1         | 3.33%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 3.33%   |
| Qualcomm Atheros Bluetooth                          | 1         | 3.33%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 3.33%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 3.33%   |
| Intel AX201 Bluetooth                               | 1         | 3.33%   |
| Intel AX200 Bluetooth                               | 1         | 3.33%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 3.33%   |
| Dell Wireless 365 Bluetooth                         | 1         | 3.33%   |
| Broadcom HP Portable SoftSailing                    | 1         | 3.33%   |
| Broadcom BCM43142A0 Bluetooth Device                | 1         | 3.33%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 1         | 3.33%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 3.33%   |
| ASUS Broadcom Bluetooth 2.1                         | 1         | 3.33%   |
| Apple Bluetooth HCI                                 | 1         | 3.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 41        | 53.95%  |
| AMD                 | 17        | 22.37%  |
| Nvidia              | 10        | 13.16%  |
| C-Media Electronics | 2         | 2.63%   |
| VIA Technologies    | 1         | 1.32%   |
| Plantronics         | 1         | 1.32%   |
| Native Instruments  | 1         | 1.32%   |
| Focusrite-Novation  | 1         | 1.32%   |
| Creative Labs       | 1         | 1.32%   |
| ASUSTek Computer    | 1         | 1.32%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 8         | 8.99%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 5         | 5.62%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 4.49%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 4.49%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 3         | 3.37%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 3.37%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 3.37%   |
| AMD FCH Azalia Controller                                                                         | 3         | 3.37%   |
| Nvidia MCP61 High Definition Audio                                                                | 2         | 2.25%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 2.25%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 2         | 2.25%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 2.25%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 2         | 2.25%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 2.25%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 2         | 2.25%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 2         | 2.25%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 2.25%   |
| AMD Navi 10 HDMI Audio                                                                            | 2         | 2.25%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 2         | 2.25%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 2.25%   |
| AMD Barts HDMI Audio [Radeon HD 6790/6850/6870 / 7720 OEM]                                        | 2         | 2.25%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1         | 1.12%   |
| Plantronics USB DSP v4 Audio Interface                                                            | 1         | 1.12%   |
| Nvidia MCP51 High Definition Audio                                                                | 1         | 1.12%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 1.12%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 1.12%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 1.12%   |
| Native Instruments KOMPLETE KONTROL M32                                                           | 1         | 1.12%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 1.12%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 1.12%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 1         | 1.12%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 1.12%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 1.12%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 1         | 1.12%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 1.12%   |
| Intel 200 Series PCH HD Audio                                                                     | 1         | 1.12%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 1.12%   |
| Focusrite-Novation Focusrite Scarlett 2i2 2nd Gen                                                 | 1         | 1.12%   |
| Creative Labs CA0106/CA0111 [SB Live!/Audigy/X-Fi Series]                                         | 1         | 1.12%   |
| C-Media Electronics USB Audio Device                                                              | 1         | 1.12%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 12        | 25.53%  |
| Unknown             | 11        | 23.4%   |
| Kingston            | 6         | 12.77%  |
| Micron Technology   | 4         | 8.51%   |
| SK hynix            | 3         | 6.38%   |
| Corsair             | 3         | 6.38%   |
| Nanya Technology    | 2         | 4.26%   |
| G.Skill             | 2         | 4.26%   |
| GOODRAM             | 1         | 2.13%   |
| Elpida              | 1         | 2.13%   |
| Crucial             | 1         | 2.13%   |
| Avant               | 1         | 2.13%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                | 2         | 3.85%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                     | 2         | 3.85%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s      | 2         | 3.85%   |
| Unknown RAM Module 2GB SODIMM SDRAM                        | 1         | 1.92%   |
| Unknown RAM Module 2GB SODIMM DDR2 266MT/s                 | 1         | 1.92%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                  | 1         | 1.92%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                   | 1         | 1.92%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                | 1         | 1.92%   |
| Unknown RAM Module 1024MB SODIMM DDR2                      | 1         | 1.92%   |
| Unknown RAM Module 1024MB SODIMM 800MT/s                   | 1         | 1.92%   |
| Unknown RAM Module 1024MB DIMM SDRAM                       | 1         | 1.92%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1066MT/s               | 1         | 1.92%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s    | 1         | 1.92%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s     | 1         | 1.92%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                | 1         | 1.92%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s      | 1         | 1.92%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s      | 1         | 1.92%   |
| Samsung RAM M471B5173EB0-YK0 4096MB SODIMM DDR3 1600MT/s   | 1         | 1.92%   |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1334MT/s      | 1         | 1.92%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s      | 1         | 1.92%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s      | 1         | 1.92%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s      | 1         | 1.92%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s      | 1         | 1.92%   |
| Samsung RAM M3 78T5663EH3-CF7 2GB DIMM DDR2 800MT/s        | 1         | 1.92%   |
| Samsung RAM M3 78T2863RZS-CE6 1GB DIMM DDR2 667MT/s        | 1         | 1.92%   |
| Samsung RAM M3 78T2863QZS-CE6 1GB DIMM DDR2 1639MT/s       | 1         | 1.92%   |
| Samsung RAM K4E8E324EB-EGCF 2GB LPDDR3 1867MT/s            | 1         | 1.92%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s       | 1         | 1.92%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s       | 1         | 1.92%   |
| Micron RAM 8ATF1G64HZ-2G6H1 8GB SODIMM DDR4 2667MT/s       | 1         | 1.92%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s | 1         | 1.92%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s      | 1         | 1.92%   |
| Micron RAM 16JSF51264HZ-1G4D1 4096MB SODIMM DDR3 1334MT/s  | 1         | 1.92%   |
| Kingston RAM Module 8GB DIMM DDR3 1600MT/s                 | 1         | 1.92%   |
| Kingston RAM Module 4GB SODIMM DDR3 800MT/s                | 1         | 1.92%   |
| Kingston RAM Module 16GB SODIMM DDR4 2133MT/s              | 1         | 1.92%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s        | 1         | 1.92%   |
| Kingston RAM ACR16D3LS1KBG/4G 4GB SODIMM DDR3 1600MT/s     | 1         | 1.92%   |
| Kingston RAM ACR128X64D3S1333C9 1GB SODIMM DDR3 1333MT/s   | 1         | 1.92%   |
| Kingston RAM 99U5471-030.A00LF 8GB DIMM DDR3 1333MT/s      | 1         | 1.92%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 23        | 51.11%  |
| DDR4    | 10        | 22.22%  |
| SDRAM   | 4         | 8.89%   |
| DDR2    | 4         | 8.89%   |
| Unknown | 3         | 6.67%   |
| LPDDR3  | 1         | 2.22%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 28        | 65.12%  |
| DIMM         | 13        | 30.23%  |
| Row Of Chips | 1         | 2.33%   |
| Unknown      | 1         | 2.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 15        | 30%     |
| 2048  | 15        | 30%     |
| 4096  | 11        | 22%     |
| 1024  | 5         | 10%     |
| 16384 | 4         | 8%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 13        | 26.53%  |
| 1333    | 5         | 10.2%   |
| 800     | 5         | 10.2%   |
| 2667    | 4         | 8.16%   |
| 3200    | 3         | 6.12%   |
| 1066    | 3         | 6.12%   |
| Unknown | 3         | 6.12%   |
| 1334    | 2         | 4.08%   |
| 4199    | 1         | 2.04%   |
| 3666    | 1         | 2.04%   |
| 2666    | 1         | 2.04%   |
| 2400    | 1         | 2.04%   |
| 2133    | 1         | 2.04%   |
| 2048    | 1         | 2.04%   |
| 1867    | 1         | 2.04%   |
| 1800    | 1         | 2.04%   |
| 1639    | 1         | 2.04%   |
| 667     | 1         | 2.04%   |
| 266     | 1         | 2.04%   |

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
| Chicony Electronics                    | 9         | 25%     |
| Microdia                               | 4         | 11.11%  |
| Suyin                                  | 3         | 8.33%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 8.33%   |
| Alcor Micro                            | 3         | 8.33%   |
| Sunplus Innovation Technology          | 2         | 5.56%   |
| Logitech                               | 2         | 5.56%   |
| Bison Electronics                      | 2         | 5.56%   |
| Acer                                   | 2         | 5.56%   |
| Z-Star Microelectronics                | 1         | 2.78%   |
| Sonix Technology                       | 1         | 2.78%   |
| Samsung Electronics                    | 1         | 2.78%   |
| Microsoft                              | 1         | 2.78%   |
| Guillemot                              | 1         | 2.78%   |
| Unknown                                | 1         | 2.78%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Alcor Micro USB 2.0 Camera                                      | 3         | 8.33%   |
| Chicony HD WebCam                                               | 2         | 5.56%   |
| Z-Star Namuga 1.3M Webcam                                       | 1         | 2.78%   |
| Suyin USB2.0 UVC 1.3M WebCam                                    | 1         | 2.78%   |
| Suyin HP Truevision HD                                          | 1         | 2.78%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)     | 1         | 2.78%   |
| Sunplus Integrated Webcam                                       | 1         | 2.78%   |
| Sunplus HP HD Webcam [Fixed]                                    | 1         | 2.78%   |
| Sonix USB2.0 HD UVC WebCam                                      | 1         | 2.78%   |
| Samsung Galaxy A5 (MTP)                                         | 1         | 2.78%   |
| Microsoft LifeCam Cinema                                        | 1         | 2.78%   |
| Microdia Sonix USB 2.0 Camera                                   | 1         | 2.78%   |
| Microdia Lenovo EasyCamera                                      | 1         | 2.78%   |
| Microdia Laptop_Integrated_Webcam_HD                            | 1         | 2.78%   |
| Microdia Laptop_Integrated_Webcam_1.3M                          | 1         | 2.78%   |
| Logitech Webcam C270                                            | 1         | 2.78%   |
| Logitech QuickCam Notebook Pro                                  | 1         | 2.78%   |
| Guillemot Hercules Dualpix Exchange                             | 1         | 2.78%   |
| Chicony TOSHIBA Web Camera - HD                                 | 1         | 2.78%   |
| Chicony Integrated Camera (1280x720@30)                         | 1         | 2.78%   |
| Chicony HP TrueVision HD Camera                                 | 1         | 2.78%   |
| Chicony HP Integrated Webcam                                    | 1         | 2.78%   |
| Chicony HP HD Webcam                                            | 1         | 2.78%   |
| Chicony Asus Integrated 0.3M UVC Webcam                         | 1         | 2.78%   |
| Chicony 2.0M UVC Webcam / CNF7129                               | 1         | 2.78%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 1         | 2.78%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera             | 1         | 2.78%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera                | 1         | 2.78%   |
| Bison USB HD Webcam                                             | 1         | 2.78%   |
| Bison HP Webcam                                                 | 1         | 2.78%   |
| Acer Lenovo EasyCamera                                          | 1         | 2.78%   |
| Acer HD Webcam                                                  | 1         | 2.78%   |
| Unknown                                                         | 1         | 2.78%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 3         | 42.86%  |
| AuthenTec                  | 2         | 28.57%  |
| STMicroelectronics         | 1         | 14.29%  |
| Shenzhen Goodix Technology | 1         | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader | 1         | 14.29%  |
| Validity Sensors VFS491                    | 1         | 14.29%  |
| Validity Sensors VFS101 Fingerprint Reader | 1         | 14.29%  |
| STMicroelectronics Fingerprint Reader      | 1         | 14.29%  |
| Shenzhen Goodix  Fingerprint Device        | 1         | 14.29%  |
| AuthenTec AES2501 Fingerprint Sensor       | 1         | 14.29%  |
| AuthenTec AES1600                          | 1         | 14.29%  |

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
| 0     | 41        | 66.13%  |
| 1     | 17        | 27.42%  |
| 2     | 4         | 6.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 8         | 29.63%  |
| Fingerprint reader    | 7         | 25.93%  |
| Net/wireless          | 6         | 22.22%  |
| Multimedia controller | 4         | 14.81%  |
| Chipcard              | 1         | 3.7%    |
| Camera                | 1         | 3.7%    |

