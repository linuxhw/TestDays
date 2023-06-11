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

Total: 85

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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

![OS](./images/pie_chart/os_name.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Sparky 6    | 16        | 23.88%  |
| Sparky 7    | 12        | 17.91%  |
| Sparky 6.1  | 6         | 8.96%   |
| Sparky 6.5  | 5         | 7.46%   |
| Sparky 5.12 | 5         | 7.46%   |
| Sparky 6.6  | 4         | 5.97%   |
| Sparky 6.7  | 3         | 4.48%   |
| Sparky 6.3  | 3         | 4.48%   |
| Sparky 6.0  | 3         | 4.48%   |
| Sparky 5.14 | 3         | 4.48%   |
| Sparky 5.10 | 3         | 4.48%   |
| Sparky 6.2  | 2         | 2.99%   |
| Sparky 5.13 | 2         | 2.99%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Sparky | 61        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Computers | Percent |
|---------------------------|-----------|---------|
| 5.10.0-21-amd64           | 4         | 5.71%   |
| 5.10.0-11-686             | 4         | 5.71%   |
| 5.10.0-9-amd64            | 3         | 4.29%   |
| 5.10.0-8-amd64            | 3         | 4.29%   |
| 5.10.0-6-amd64            | 3         | 4.29%   |
| 4.19.0-8-amd64            | 3         | 4.29%   |
| 4.19.0-12-amd64           | 3         | 4.29%   |
| 5.18.0-4-amd64            | 2         | 2.86%   |
| 5.18.0-2-amd64            | 2         | 2.86%   |
| 5.17.0-1-amd64            | 2         | 2.86%   |
| 5.10.0-3-amd64            | 2         | 2.86%   |
| 5.10.0-14-amd64           | 2         | 2.86%   |
| 4.19.0-13-686             | 2         | 2.86%   |
| 4.19.0-10-686             | 2         | 2.86%   |
| 6.3.3-1-liquorix-amd64    | 1         | 1.43%   |
| 6.2.0-sparky-amd64        | 1         | 1.43%   |
| 6.1.0-7-amd64             | 1         | 1.43%   |
| 6.1.0-3-amd64             | 1         | 1.43%   |
| 6.0.11-x64v2-rt14-xanmod1 | 1         | 1.43%   |
| 6.0.0-5-amd64             | 1         | 1.43%   |
| 5.9.13-sparky-amd64       | 1         | 1.43%   |
| 5.9.0-4-amd64             | 1         | 1.43%   |
| 5.8.13-sparky-amd64       | 1         | 1.43%   |
| 5.8.0-2-amd64             | 1         | 1.43%   |
| 5.7.2-sparky-amd64        | 1         | 1.43%   |
| 5.6.0-2-amd64             | 1         | 1.43%   |
| 5.5.0-2-amd64             | 1         | 1.43%   |
| 5.4.7-sparky-amd64        | 1         | 1.43%   |
| 5.2.0-2-amd64             | 1         | 1.43%   |
| 5.18.3-sparky-amd64       | 1         | 1.43%   |
| 5.17.3-sparky-amd64       | 1         | 1.43%   |
| 5.16.5-sparky-amd64       | 1         | 1.43%   |
| 5.16.0-5-amd64            | 1         | 1.43%   |
| 5.15.0-3-amd64            | 1         | 1.43%   |
| 5.14.0-4-amd64            | 1         | 1.43%   |
| 5.10.4-sparky-amd64       | 1         | 1.43%   |
| 5.10.0-7-amd64            | 1         | 1.43%   |
| 5.10.0-23-amd64           | 1         | 1.43%   |
| 5.10.0-22-amd64           | 1         | 1.43%   |
| 5.10.0-21-686             | 1         | 1.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 29        | 43.28%  |
| 4.19.0  | 10        | 14.93%  |
| 5.18.0  | 4         | 5.97%   |
| 6.1.0   | 2         | 2.99%   |
| 5.17.0  | 2         | 2.99%   |
| 6.3.3   | 1         | 1.49%   |
| 6.2.0   | 1         | 1.49%   |
| 6.0.11  | 1         | 1.49%   |
| 6.0.0   | 1         | 1.49%   |
| 5.9.13  | 1         | 1.49%   |
| 5.9.0   | 1         | 1.49%   |
| 5.8.13  | 1         | 1.49%   |
| 5.8.0   | 1         | 1.49%   |
| 5.7.2   | 1         | 1.49%   |
| 5.6.0   | 1         | 1.49%   |
| 5.5.0   | 1         | 1.49%   |
| 5.4.7   | 1         | 1.49%   |
| 5.2.0   | 1         | 1.49%   |
| 5.18.3  | 1         | 1.49%   |
| 5.17.3  | 1         | 1.49%   |
| 5.16.5  | 1         | 1.49%   |
| 5.16.0  | 1         | 1.49%   |
| 5.15.0  | 1         | 1.49%   |
| 5.14.0  | 1         | 1.49%   |
| 5.10.4  | 1         | 1.49%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 30        | 45.45%  |
| 4.19    | 10        | 15.15%  |
| 5.18    | 5         | 7.58%   |
| 5.17    | 3         | 4.55%   |
| 6.1     | 2         | 3.03%   |
| 5.9     | 2         | 3.03%   |
| 5.8     | 2         | 3.03%   |
| 5.16    | 2         | 3.03%   |
| 6.3     | 1         | 1.52%   |
| 6.2     | 1         | 1.52%   |
| 6.0     | 1         | 1.52%   |
| 5.7     | 1         | 1.52%   |
| 5.6     | 1         | 1.52%   |
| 5.5     | 1         | 1.52%   |
| 5.4     | 1         | 1.52%   |
| 5.2     | 1         | 1.52%   |
| 5.15    | 1         | 1.52%   |
| 5.14    | 1         | 1.52%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 55        | 90.16%  |
| i686   | 6         | 9.84%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| XFCE             | 23        | 37.1%   |
| LXQt             | 15        | 24.19%  |
| Unknown          | 8         | 12.9%   |
| KDE5             | 6         | 9.68%   |
| openbox          | 2         | 3.23%   |
| MATE             | 2         | 3.23%   |
| GNOME            | 2         | 3.23%   |
| X-Cinnamon       | 1         | 1.61%   |
| lightdm-xsession | 1         | 1.61%   |
| ICEWM            | 1         | 1.61%   |
| GNOME Classic    | 1         | 1.61%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 58        | 92.06%  |
| Tty  | 5         | 7.94%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 19        | 31.15%  |
| LightDM | 14        | 22.95%  |
| TDM     | 13        | 21.31%  |
| SDDM    | 13        | 21.31%  |
| XDM     | 1         | 1.64%   |
| GDM     | 1         | 1.64%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 17        | 27.87%  |
| en_GB   | 6         | 9.84%   |
| de_DE   | 5         | 8.2%    |
| pt_BR   | 4         | 6.56%   |
| fr_FR   | 4         | 6.56%   |
| es_ES   | 4         | 6.56%   |
| pl_PL   | 3         | 4.92%   |
| en_CA   | 2         | 3.28%   |
| Unknown | 2         | 3.28%   |
| sv_SE   | 1         | 1.64%   |
| ja_JP   | 1         | 1.64%   |
| it_IT   | 1         | 1.64%   |
| id_ID   | 1         | 1.64%   |
| es_US   | 1         | 1.64%   |
| es_MX   | 1         | 1.64%   |
| es_CL   | 1         | 1.64%   |
| es_AR   | 1         | 1.64%   |
| en_ZA   | 1         | 1.64%   |
| en_PH   | 1         | 1.64%   |
| en_IN   | 1         | 1.64%   |
| en_DK   | 1         | 1.64%   |
| de_CH   | 1         | 1.64%   |
| cs_CZ   | 1         | 1.64%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 37        | 60.66%  |
| EFI  | 24        | 39.34%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 55        | 90.16%  |
| Overlay | 3         | 4.92%   |
| Zfs     | 1         | 1.64%   |
| Ext2    | 1         | 1.64%   |
| Btrfs   | 1         | 1.64%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 24        | 39.34%  |
| Unknown | 19        | 31.15%  |
| MBR     | 18        | 29.51%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 53        | 86.89%  |
| Yes       | 8         | 13.11%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 40        | 65.57%  |
| Yes       | 21        | 34.43%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 14        | 22.95%  |
| ASUSTek Computer    | 6         | 9.84%   |
| Lenovo              | 5         | 8.2%    |
| Intel               | 5         | 8.2%    |
| Gigabyte Technology | 5         | 8.2%    |
| Dell                | 5         | 8.2%    |
| MSI                 | 4         | 6.56%   |
| Acer                | 3         | 4.92%   |
| Google              | 2         | 3.28%   |
| Samsung Electronics | 1         | 1.64%   |
| Positivo            | 1         | 1.64%   |
| Panasonic           | 1         | 1.64%   |
| Mediacom            | 1         | 1.64%   |
| HUAWEI              | 1         | 1.64%   |
| Fujitsu Siemens     | 1         | 1.64%   |
| Foxconn             | 1         | 1.64%   |
| eMachines           | 1         | 1.64%   |
| Beelink             | 1         | 1.64%   |
| ASRock              | 1         | 1.64%   |
| Apple               | 1         | 1.64%   |
| Unknown             | 1         | 1.64%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| Samsung NC10                          | 1         | 1.64%   |
| Positivo CHT14B                       | 1         | 1.64%   |
| Panasonic CFSZ5-2                     | 1         | 1.64%   |
| MSI MS-7C09                           | 1         | 1.64%   |
| MSI MS-7B86                           | 1         | 1.64%   |
| MSI MS-7721                           | 1         | 1.64%   |
| MSI Alpha 15 A3DDK                    | 1         | 1.64%   |
| Mediacom SmartBook 14 FullHD - SB14UC | 1         | 1.64%   |
| Lenovo ThinkPad T61 7659AB7           | 1         | 1.64%   |
| Lenovo ThinkPad T60 2007FUG           | 1         | 1.64%   |
| Lenovo ThinkPad E15 20RES0GF00        | 1         | 1.64%   |
| Lenovo IdeaPad S206 20154             | 1         | 1.64%   |
| Lenovo G50-30 80G0                    | 1         | 1.64%   |
| Intel NUC5CPYB H61145-408             | 1         | 1.64%   |
| Intel H61                             | 1         | 1.64%   |
| Intel H55                             | 1         | 1.64%   |
| Intel DG43RK AAE78175-402             | 1         | 1.64%   |
| Intel DG41TY AAE47335-300             | 1         | 1.64%   |
| HUAWEI HVY-WXX9                       | 1         | 1.64%   |
| HP Z420 Workstation                   | 1         | 1.64%   |
| HP t5740                              | 1         | 1.64%   |
| HP Stream Notebook PC 13              | 1         | 1.64%   |
| HP Pavilion x360 Convertible 14-ba0xx | 1         | 1.64%   |
| HP Pavilion g7                        | 1         | 1.64%   |
| HP Pavilion dv9000 (GA359UA#ABA)      | 1         | 1.64%   |
| HP Pavilion dv5                       | 1         | 1.64%   |
| HP Laptop 17z-ca100                   | 1         | 1.64%   |
| HP EliteDesk 800 G2 DM 65W            | 1         | 1.64%   |
| HP EliteDesk 705 G2 MINI              | 1         | 1.64%   |
| HP EliteBook Folio 9480m              | 1         | 1.64%   |
| HP EliteBook 8770w                    | 1         | 1.64%   |
| HP EliteBook 745 G3                   | 1         | 1.64%   |
| HP Compaq dc7700 Ultra-slim Desktop   | 1         | 1.64%   |
| Google Swanky                         | 1         | 1.64%   |
| Google Banon                          | 1         | 1.64%   |
| Gigabyte X570S AORUS PRO AX           | 1         | 1.64%   |
| Gigabyte M68M-S2P                     | 1         | 1.64%   |
| Gigabyte H97-Gaming 3                 | 1         | 1.64%   |
| Gigabyte H410M H                      | 1         | 1.64%   |
| Gigabyte G41M-ES2L                    | 1         | 1.64%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                      | Computers | Percent |
|---------------------------|-----------|---------|
| HP Pavilion               | 4         | 6.56%   |
| Lenovo ThinkPad           | 3         | 4.92%   |
| HP EliteBook              | 3         | 4.92%   |
| Dell Inspiron             | 3         | 4.92%   |
| Acer Aspire               | 3         | 4.92%   |
| HP EliteDesk              | 2         | 3.28%   |
| Samsung NC10              | 1         | 1.64%   |
| Positivo CHT14B           | 1         | 1.64%   |
| Panasonic CFSZ5-2         | 1         | 1.64%   |
| MSI MS-7C09               | 1         | 1.64%   |
| MSI MS-7B86               | 1         | 1.64%   |
| MSI MS-7721               | 1         | 1.64%   |
| MSI Alpha                 | 1         | 1.64%   |
| Mediacom SmartBook        | 1         | 1.64%   |
| Lenovo IdeaPad            | 1         | 1.64%   |
| Lenovo G50-30             | 1         | 1.64%   |
| Intel NUC5CPYB            | 1         | 1.64%   |
| Intel H61                 | 1         | 1.64%   |
| Intel H55                 | 1         | 1.64%   |
| Intel DG43RK              | 1         | 1.64%   |
| Intel DG41TY              | 1         | 1.64%   |
| HUAWEI HVY-WXX9           | 1         | 1.64%   |
| HP Z420                   | 1         | 1.64%   |
| HP t5740                  | 1         | 1.64%   |
| HP Stream                 | 1         | 1.64%   |
| HP Laptop                 | 1         | 1.64%   |
| HP Compaq                 | 1         | 1.64%   |
| Google Swanky             | 1         | 1.64%   |
| Google Banon              | 1         | 1.64%   |
| Gigabyte X570S            | 1         | 1.64%   |
| Gigabyte M68M-S2P         | 1         | 1.64%   |
| Gigabyte H97-Gaming       | 1         | 1.64%   |
| Gigabyte H410M            | 1         | 1.64%   |
| Gigabyte G41M-ES2L        | 1         | 1.64%   |
| Fujitsu Siemens STYLISTIC | 1         | 1.64%   |
| Foxconn p6-2010fr         | 1         | 1.64%   |
| eMachines E525            | 1         | 1.64%   |
| Dell OptiPlex             | 1         | 1.64%   |
| Dell Latitude             | 1         | 1.64%   |
| Beelink BT3               | 1         | 1.64%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2009 | 7         | 11.48%  |
| 2014 | 6         | 9.84%   |
| 2012 | 5         | 8.2%    |
| 2008 | 5         | 8.2%    |
| 2021 | 4         | 6.56%   |
| 2018 | 4         | 6.56%   |
| 2017 | 4         | 6.56%   |
| 2016 | 4         | 6.56%   |
| 2011 | 4         | 6.56%   |
| 2020 | 3         | 4.92%   |
| 2019 | 3         | 4.92%   |
| 2010 | 3         | 4.92%   |
| 2007 | 3         | 4.92%   |
| 2015 | 2         | 3.28%   |
| 2006 | 2         | 3.28%   |
| 2022 | 1         | 1.64%   |
| 2013 | 1         | 1.64%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 35        | 57.38%  |
| Desktop     | 24        | 39.34%  |
| Convertible | 1         | 1.64%   |
| Mini pc     | 1         | 1.64%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 61        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 59        | 96.72%  |
| Yes  | 2         | 3.28%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 19        | 31.15%  |
| 4.01-8.0   | 11        | 18.03%  |
| 1.01-2.0   | 8         | 13.11%  |
| 16.01-24.0 | 7         | 11.48%  |
| 8.01-16.0  | 7         | 11.48%  |
| 2.01-3.0   | 5         | 8.2%    |
| 24.01-32.0 | 2         | 3.28%   |
| 32.01-64.0 | 1         | 1.64%   |
| 0.51-1.0   | 1         | 1.64%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 29        | 44.62%  |
| 0.51-1.0 | 13        | 20%     |
| 2.01-3.0 | 11        | 16.92%  |
| 4.01-8.0 | 5         | 7.69%   |
| 3.01-4.0 | 4         | 6.15%   |
| 0.01-0.5 | 3         | 4.62%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 45        | 70.31%  |
| 2      | 11        | 17.19%  |
| 4      | 4         | 6.25%   |
| 6      | 2         | 3.13%   |
| 5      | 1         | 1.56%   |
| 3      | 1         | 1.56%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 40        | 65.57%  |
| Yes       | 21        | 34.43%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 53        | 86.89%  |
| No        | 8         | 13.11%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 43        | 70.49%  |
| No        | 18        | 29.51%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 31        | 50.82%  |
| Yes       | 30        | 49.18%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 9         | 14.75%  |
| Germany      | 8         | 13.11%  |
| UK           | 6         | 9.84%   |
| France       | 5         | 8.2%    |
| Indonesia    | 4         | 6.56%   |
| Brazil       | 4         | 6.56%   |
| Spain        | 3         | 4.92%   |
| Poland       | 3         | 4.92%   |
| Canada       | 3         | 4.92%   |
| Argentina    | 2         | 3.28%   |
| Venezuela    | 1         | 1.64%   |
| Switzerland  | 1         | 1.64%   |
| Sweden       | 1         | 1.64%   |
| South Africa | 1         | 1.64%   |
| Philippines  | 1         | 1.64%   |
| New Zealand  | 1         | 1.64%   |
| Mexico       | 1         | 1.64%   |
| Lebanon      | 1         | 1.64%   |
| Japan        | 1         | 1.64%   |
| Italy        | 1         | 1.64%   |
| India        | 1         | 1.64%   |
| Czechia      | 1         | 1.64%   |
| Chile        | 1         | 1.64%   |
| Belgium      | 1         | 1.64%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Computers | Percent |
|-----------------|-----------|---------|
| Montreuil       | 2         | 3.03%   |
| Leipzig         | 2         | 3.03%   |
| Bandung         | 2         | 3.03%   |
| Woking          | 1         | 1.52%   |
| Wenatchee       | 1         | 1.52%   |
| Tucson          | 1         | 1.52%   |
| Trelaze         | 1         | 1.52%   |
| Tauranga        | 1         | 1.52%   |
| Takahama        | 1         | 1.52%   |
| Surabaya        | 1         | 1.52%   |
| Spokane         | 1         | 1.52%   |
| Sin el Fil      | 1         | 1.52%   |
| Santo André    | 1         | 1.52%   |
| San Cristóbal  | 1         | 1.52%   |
| San Antonio     | 1         | 1.52%   |
| Salina Cruz     | 1         | 1.52%   |
| Sainte-Julie    | 1         | 1.52%   |
| Rudersberg      | 1         | 1.52%   |
| Rosario         | 1         | 1.52%   |
| Rio de Janeiro  | 1         | 1.52%   |
| Rio Claro       | 1         | 1.52%   |
| Quezon City     | 1         | 1.52%   |
| Pujaudran       | 1         | 1.52%   |
| Puente Alto     | 1         | 1.52%   |
| Posadas         | 1         | 1.52%   |
| Pompano Beach   | 1         | 1.52%   |
| Munich          | 1         | 1.52%   |
| Montreal        | 1         | 1.52%   |
| Mnisek pod Brdy | 1         | 1.52%   |
| Milano          | 1         | 1.52%   |
| Miekoszyn       | 1         | 1.52%   |
| Mannheim        | 1         | 1.52%   |
| Madrid          | 1         | 1.52%   |
| Liverpool       | 1         | 1.52%   |
| Lienen          | 1         | 1.52%   |
| Koło           | 1         | 1.52%   |
| Kirkcaldy       | 1         | 1.52%   |
| Kage            | 1         | 1.52%   |
| Jakarta         | 1         | 1.52%   |
| Houston         | 1         | 1.52%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 16        | 18     | 18.82%  |
| Seagate             | 16        | 23     | 18.82%  |
| Samsung Electronics | 12        | 23     | 14.12%  |
| Unknown             | 6         | 6      | 7.06%   |
| Hitachi             | 6         | 9      | 7.06%   |
| SanDisk             | 3         | 4      | 3.53%   |
| Kingston            | 3         | 3      | 3.53%   |
| Intel               | 3         | 3      | 3.53%   |
| Toshiba             | 2         | 2      | 2.35%   |
| HGST                | 2         | 2      | 2.35%   |
| GOODRAM             | 2         | 4      | 2.35%   |
| ASMedia             | 2         | 2      | 2.35%   |
| XPG                 | 1         | 1      | 1.18%   |
| SPCC                | 1         | 2      | 1.18%   |
| Silicon Motion      | 1         | 1      | 1.18%   |
| ORICO               | 1         | 1      | 1.18%   |
| Netac               | 1         | 1      | 1.18%   |
| Micron Technology   | 1         | 1      | 1.18%   |
| Gigabyte Technology | 1         | 1      | 1.18%   |
| Fujitsu             | 1         | 2      | 1.18%   |
| Crucial             | 1         | 1      | 1.18%   |
| ASUS-JM             | 1         | 1      | 1.18%   |
| A-DATA Technology   | 1         | 1      | 1.18%   |
| Unknown             | 1         | 1      | 1.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| WDC WD1600BEVT-22ZCT0 160GB          | 2         | 2.17%   |
| Unknown MMC Card  32GB               | 2         | 2.17%   |
| Seagate ST500LT012-1DG142 500GB      | 2         | 2.17%   |
| Seagate Backup+ Hub BK 6TB           | 2         | 2.17%   |
| Samsung HD161GJ 160GB                | 2         | 2.17%   |
| Hitachi HTS545025B9A300 250GB        | 2         | 2.17%   |
| XPG GAMMIX S11 Pro 512GB             | 1         | 1.09%   |
| WDC WD800JD-08MSA1 80GB              | 1         | 1.09%   |
| WDC WD7500BPVX-22JC3T0 752GB         | 1         | 1.09%   |
| WDC WD5000BEVT-22ZAT0 500GB          | 1         | 1.09%   |
| WDC WD5000AVVS-63ZWB0 500GB          | 1         | 1.09%   |
| WDC WD5000AAKS-75V0A0 500GB          | 1         | 1.09%   |
| WDC WD50 00LPLX-08ZNTT0 500GB        | 1         | 1.09%   |
| WDC WD50 00LPCX-21VHAT0 500GB        | 1         | 1.09%   |
| WDC WD3200BPVT-75ZEST0 320GB         | 1         | 1.09%   |
| WDC WD2500AAKX-07U6AA0 250GB         | 1         | 1.09%   |
| WDC WD2500AAJS-00L7A0 250GB          | 1         | 1.09%   |
| WDC WD1600AAJS-08L7A0 160GB          | 1         | 1.09%   |
| WDC WD10EZEX-60WN4A0 1TB             | 1         | 1.09%   |
| WDC WD10EADS-00M2B0 1TB              | 1         | 1.09%   |
| WDC PC SN730 SDBPNTY-512G-1006 512GB | 1         | 1.09%   |
| Unknown NCard  32GB                  | 1         | 1.09%   |
| Unknown MMC Card  64GB               | 1         | 1.09%   |
| Unknown HBG4a2  32GB                 | 1         | 1.09%   |
| Unknown 016GE2  16GB                 | 1         | 1.09%   |
| Toshiba DT01ACA100 1TB               | 1         | 1.09%   |
| Toshiba DT01ACA050 500GB             | 1         | 1.09%   |
| SPCC Solid State Disk 256GB          | 1         | 1.09%   |
| Silicon Motion PCIe-8 SSD 512GB      | 1         | 1.09%   |
| Seagate ST975042 0AS 752GB           | 1         | 1.09%   |
| Seagate ST9500420AS 500GB            | 1         | 1.09%   |
| Seagate ST9500325AS 500GB            | 1         | 1.09%   |
| Seagate ST9250320AS 250GB            | 1         | 1.09%   |
| Seagate ST9250315AS 250GB            | 1         | 1.09%   |
| Seagate ST9160310AS 160GB            | 1         | 1.09%   |
| Seagate ST500DM002-1BD142 500GB      | 1         | 1.09%   |
| Seagate ST3500312CS 500GB            | 1         | 1.09%   |
| Seagate ST3320418AS 320GB            | 1         | 1.09%   |
| Seagate ST2000VM003-1ET164 2TB       | 1         | 1.09%   |
| Seagate ST1000LM048-2E7172 1TB       | 1         | 1.09%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 16        | 21     | 33.33%  |
| WDC                 | 15        | 17     | 31.25%  |
| Hitachi             | 6         | 9      | 12.5%   |
| Samsung Electronics | 4         | 11     | 8.33%   |
| Toshiba             | 2         | 2      | 4.17%   |
| HGST                | 2         | 2      | 4.17%   |
| ASMedia             | 2         | 2      | 4.17%   |
| Fujitsu             | 1         | 2      | 2.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


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

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 38        | 66     | 50.67%  |
| SSD     | 20        | 28     | 26.67%  |
| NVMe    | 9         | 11     | 12%     |
| MMC     | 7         | 7      | 9.33%   |
| Unknown | 1         | 1      | 1.33%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 50        | 85     | 70.42%  |
| NVMe | 9         | 11     | 12.68%  |
| MMC  | 7         | 7      | 9.86%   |
| SAS  | 5         | 10     | 7.04%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 44        | 70     | 75.86%  |
| 0.51-1.0   | 10        | 18     | 17.24%  |
| 4.01-10.0  | 2         | 4      | 3.45%   |
| 2.01-3.0   | 1         | 1      | 1.72%   |
| 1.01-2.0   | 1         | 1      | 1.72%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 16        | 25.81%  |
| 251-500        | 12        | 19.35%  |
| 501-1000       | 10        | 16.13%  |
| 1-20           | 7         | 11.29%  |
| 21-50          | 6         | 9.68%   |
| 2001-3000      | 3         | 4.84%   |
| 51-100         | 3         | 4.84%   |
| More than 3000 | 2         | 3.23%   |
| Unknown        | 2         | 3.23%   |
| 1001-2000      | 1         | 1.61%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 30        | 46.88%  |
| 21-50          | 8         | 12.5%   |
| 251-500        | 6         | 9.38%   |
| 51-100         | 6         | 9.38%   |
| 101-250        | 4         | 6.25%   |
| 501-1000       | 4         | 6.25%   |
| 1001-2000      | 3         | 4.69%   |
| Unknown        | 2         | 3.13%   |
| More than 3000 | 1         | 1.56%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


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

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


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

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 32        | 48     | 46.38%  |
| Detected | 27        | 55     | 39.13%  |
| Malfunc  | 10        | 10     | 14.49%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 38        | 59.38%  |
| AMD                       | 11        | 17.19%  |
| Samsung Electronics       | 4         | 6.25%   |
| Silicon Motion            | 2         | 3.13%   |
| Nvidia                    | 2         | 3.13%   |
| VIA Technologies          | 1         | 1.56%   |
| Seagate Technology        | 1         | 1.56%   |
| SanDisk                   | 1         | 1.56%   |
| Marvell Technology Group  | 1         | 1.56%   |
| LSI Logic / Symbios Logic | 1         | 1.56%   |
| JMicron Technology        | 1         | 1.56%   |
| ADATA Technology          | 1         | 1.56%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 9         | 11.39%  |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 4         | 5.06%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 3         | 3.8%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 3         | 3.8%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 3         | 3.8%    |
| Samsung NVMe SSD Controller 980                                                  | 2         | 2.53%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 2         | 2.53%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 2.53%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 2         | 2.53%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 2         | 2.53%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 2         | 2.53%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 2         | 2.53%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 2.53%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 2.53%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                      | 1         | 1.27%   |
| VIA VT8237A SATA 2-Port Controller                                               | 1         | 1.27%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 1         | 1.27%   |
| Silicon Motion Non-Volatile memory controller                                    | 1         | 1.27%   |
| Seagate Non-Volatile memory controller                                           | 1         | 1.27%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                               | 1         | 1.27%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 1         | 1.27%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 1         | 1.27%   |
| Nvidia MCP61 SATA Controller                                                     | 1         | 1.27%   |
| Nvidia MCP61 IDE                                                                 | 1         | 1.27%   |
| Nvidia MCP51 Serial ATA Controller                                               | 1         | 1.27%   |
| Nvidia MCP51 IDE                                                                 | 1         | 1.27%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                        | 1         | 1.27%   |
| LSI Logic / Symbios Logic SAS1064ET PCI-Express Fusion-MPT SAS                   | 1         | 1.27%   |
| JMicron JMB360 AHCI Controller                                                   | 1         | 1.27%   |
| Intel SATA Controller [RAID mode]                                                | 1         | 1.27%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 1.27%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 1.27%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 1.27%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                              | 1         | 1.27%   |
| Intel C600/X79 series chipset IDE-r Controller                                   | 1         | 1.27%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 1         | 1.27%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 1.27%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 1.27%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 1         | 1.27%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 1         | 1.27%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 39        | 55.71%  |
| IDE  | 19        | 27.14%  |
| NVMe | 8         | 11.43%  |
| RAID | 2         | 2.86%   |
| SAS  | 1         | 1.43%   |
| SCSI | 1         | 1.43%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 45        | 73.77%  |
| AMD    | 16        | 26.23%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Celeron CPU N2840 @ 2.16GHz           | 3         | 4.92%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz        | 2         | 3.28%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 2         | 3.28%   |
| Intel Atom CPU N280 @ 1.66GHz               | 2         | 3.28%   |
| Intel Atom CPU N270 @ 1.60GHz               | 2         | 3.28%   |
| Intel Xeon CPU E5-2687W 0 @ 3.10GHz         | 1         | 1.64%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz      | 1         | 1.64%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz | 1         | 1.64%   |
| Intel Pentium CPU B950 @ 2.10GHz            | 1         | 1.64%   |
| Intel Genuine CPU T2400 @ 1.83GHz           | 1         | 1.64%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1         | 1.64%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 1         | 1.64%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1         | 1.64%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 1         | 1.64%   |
| Intel Core i7-3612QM CPU @ 2.10GHz          | 1         | 1.64%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1         | 1.64%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1         | 1.64%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 1         | 1.64%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 1         | 1.64%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 1         | 1.64%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 1         | 1.64%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 1         | 1.64%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 1         | 1.64%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 1         | 1.64%   |
| Intel Core i5 CPU M 460 @ 2.53GHz           | 1         | 1.64%   |
| Intel Core i3-7100U CPU @ 2.40GHz           | 1         | 1.64%   |
| Intel Core i3 CPU M 380 @ 2.53GHz           | 1         | 1.64%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 1         | 1.64%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz        | 1         | 1.64%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 1         | 1.64%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz        | 1         | 1.64%   |
| Intel Core 2 CPU U7600 @ 1.20GHz            | 1         | 1.64%   |
| Intel Core 2 CPU T5600 @ 1.83GHz            | 1         | 1.64%   |
| Intel Core 2 CPU 6300 @ 1.86GHz             | 1         | 1.64%   |
| Intel Celeron N4020 CPU @ 1.10GHz           | 1         | 1.64%   |
| Intel Celeron CPU N3160 @ 1.60GHz           | 1         | 1.64%   |
| Intel Celeron CPU N3050 @ 1.60GHz           | 1         | 1.64%   |
| Intel Celeron CPU 900 @ 2.20GHz             | 1         | 1.64%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz           | 1         | 1.64%   |
| AMD Turion 64 X2 Mobile Technology TL-64    | 1         | 1.64%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 9         | 14.75%  |
| Intel Celeron           | 7         | 11.48%  |
| Intel Atom              | 7         | 11.48%  |
| Intel Core i7           | 6         | 9.84%   |
| Intel Core 2 Duo        | 5         | 8.2%    |
| Intel Core 2            | 3         | 4.92%   |
| AMD A6                  | 3         | 4.92%   |
| Intel Core i3           | 2         | 3.28%   |
| AMD Ryzen 7             | 2         | 3.28%   |
| AMD Ryzen 5             | 2         | 3.28%   |
| Intel Xeon              | 1         | 1.64%   |
| Intel Pentium Gold      | 1         | 1.64%   |
| Intel Pentium Dual-Core | 1         | 1.64%   |
| Intel Pentium           | 1         | 1.64%   |
| Intel Genuine           | 1         | 1.64%   |
| Intel Core 2 Quad       | 1         | 1.64%   |
| AMD Turion 64 X2 Mobile | 1         | 1.64%   |
| AMD Sempron             | 1         | 1.64%   |
| AMD Ryzen 9             | 1         | 1.64%   |
| AMD Ryzen 3             | 1         | 1.64%   |
| AMD PRO A8              | 1         | 1.64%   |
| AMD PRO A10             | 1         | 1.64%   |
| AMD C-50                | 1         | 1.64%   |
| AMD Athlon II X2        | 1         | 1.64%   |
| AMD A4                  | 1         | 1.64%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 28        | 45.9%   |
| 4      | 20        | 32.79%  |
| 1      | 8         | 13.11%  |
| 8      | 2         | 3.28%   |
| 6      | 2         | 3.28%   |
| 12     | 1         | 1.64%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 61        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 32        | 52.46%  |
| 2      | 29        | 47.54%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 56        | 91.8%   |
| 32-bit         | 5         | 8.2%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 9         | 14.75%  |
| 0x6f2      | 3         | 4.92%   |
| 0x406c4    | 3         | 4.92%   |
| 0x306a9    | 3         | 4.92%   |
| 0x30678    | 3         | 4.92%   |
| 0x206a7    | 3         | 4.92%   |
| 0x0600611a | 3         | 4.92%   |
| 0x406c3    | 2         | 3.28%   |
| 0x306c3    | 2         | 3.28%   |
| 0x20655    | 2         | 3.28%   |
| 0x106c2    | 2         | 3.28%   |
| 0x1067a    | 2         | 3.28%   |
| 0x10676    | 2         | 3.28%   |
| 0x08108109 | 2         | 3.28%   |
| 0xa0653    | 1         | 1.64%   |
| 0x806ec    | 1         | 1.64%   |
| 0x806ea    | 1         | 1.64%   |
| 0x806e9    | 1         | 1.64%   |
| 0x706a8    | 1         | 1.64%   |
| 0x6fd      | 1         | 1.64%   |
| 0x6fb      | 1         | 1.64%   |
| 0x506e3    | 1         | 1.64%   |
| 0x40651    | 1         | 1.64%   |
| 0x206d7    | 1         | 1.64%   |
| 0x106e5    | 1         | 1.64%   |
| 0x0a201016 | 1         | 1.64%   |
| 0x08701021 | 1         | 1.64%   |
| 0x08600106 | 1         | 1.64%   |
| 0x08001138 | 1         | 1.64%   |
| 0x0700010f | 1         | 1.64%   |
| 0x06001119 | 1         | 1.64%   |
| 0x05000029 | 1         | 1.64%   |
| 0x03000027 | 1         | 1.64%   |
| 0x010000c8 | 1         | 1.64%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Silvermont    | 8         | 13.11%  |
| Core          | 6         | 9.84%   |
| Penryn        | 5         | 8.2%    |
| SandyBridge   | 4         | 6.56%   |
| KabyLake      | 4         | 6.56%   |
| Bonnell       | 4         | 6.56%   |
| IvyBridge     | 3         | 4.92%   |
| Haswell       | 3         | 4.92%   |
| Excavator     | 3         | 4.92%   |
| Zen+          | 2         | 3.28%   |
| Zen 2         | 2         | 3.28%   |
| Westmere      | 2         | 3.28%   |
| Skylake       | 2         | 3.28%   |
| K10           | 2         | 3.28%   |
| Zen 3         | 1         | 1.64%   |
| Zen           | 1         | 1.64%   |
| Piledriver    | 1         | 1.64%   |
| P6            | 1         | 1.64%   |
| Nehalem       | 1         | 1.64%   |
| K8 Hammer     | 1         | 1.64%   |
| K10 Llano     | 1         | 1.64%   |
| Jaguar        | 1         | 1.64%   |
| Goldmont plus | 1         | 1.64%   |
| CometLake     | 1         | 1.64%   |
| Bobcat        | 1         | 1.64%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Intel            | 33        | 52.38%  |
| AMD              | 18        | 28.57%  |
| Nvidia           | 11        | 17.46%  |
| VIA Technologies | 1         | 1.59%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 5         | 7.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 7.04%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 3         | 4.23%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 4.23%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 3         | 4.23%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 2.82%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 2.82%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 2.82%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 2.82%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 2.82%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 2         | 2.82%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 1         | 1.41%   |
| Nvidia GT200GL [Quadro FX 3800]                                                          | 1         | 1.41%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 1.41%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1         | 1.41%   |
| Nvidia GK104GLM [Quadro K3000M]                                                          | 1         | 1.41%   |
| Nvidia GK104 [GeForce GTX 760]                                                           | 1         | 1.41%   |
| Nvidia GF108M [GeForce GT 420M]                                                          | 1         | 1.41%   |
| Nvidia GA106 [Geforce RTX 3050]                                                          | 1         | 1.41%   |
| Nvidia G96CM [GeForce 9650M GT]                                                          | 1         | 1.41%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 1.41%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 1         | 1.41%   |
| Nvidia C51 [GeForce Go 6150]                                                             | 1         | 1.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1         | 1.41%   |
| Intel UHD Graphics 620                                                                   | 1         | 1.41%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 1.41%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.41%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.41%   |
| Intel HD Graphics 620                                                                    | 1         | 1.41%   |
| Intel HD Graphics 530                                                                    | 1         | 1.41%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 1.41%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 1.41%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.41%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 1.41%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1         | 1.41%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                                | 1         | 1.41%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                                         | 1         | 1.41%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1         | 1.41%   |
| AMD Wrestler [Radeon HD 6250]                                                            | 1         | 1.41%   |
| AMD Turks GL [FirePro V4900]                                                             | 1         | 1.41%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 32        | 52.46%  |
| 1 x AMD        | 16        | 26.23%  |
| 1 x Nvidia     | 10        | 16.39%  |
| 2 x AMD        | 1         | 1.64%   |
| 1 x VIA        | 1         | 1.64%   |
| Intel + Nvidia | 1         | 1.64%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 55        | 90.16%  |
| Unknown     | 4         | 6.56%   |
| Proprietary | 2         | 3.28%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 40        | 64.52%  |
| 0.01-0.5   | 9         | 14.52%  |
| 0.51-1.0   | 6         | 9.68%   |
| 1.01-2.0   | 4         | 6.45%   |
| 7.01-8.0   | 2         | 3.23%   |
| 3.01-4.0   | 1         | 1.61%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 7         | 12.28%  |
| LG Display          | 7         | 12.28%  |
| AU Optronics        | 6         | 10.53%  |
| Goldstar            | 5         | 8.77%   |
| BOE                 | 5         | 8.77%   |
| Chimei Innolux      | 4         | 7.02%   |
| Dell                | 3         | 5.26%   |
| CPT                 | 3         | 5.26%   |
| Lenovo              | 2         | 3.51%   |
| BenQ                | 2         | 3.51%   |
| AOC                 | 2         | 3.51%   |
| Unknown             | 1         | 1.75%   |
| Toshiba             | 1         | 1.75%   |
| Medion              | 1         | 1.75%   |
| LG Philips          | 1         | 1.75%   |
| JCH                 | 1         | 1.75%   |
| Insignia            | 1         | 1.75%   |
| HUYINIUDA           | 1         | 1.75%   |
| Hitachi             | 1         | 1.75%   |
| HannStar            | 1         | 1.75%   |
| Apple               | 1         | 1.75%   |
| Acer                | 1         | 1.75%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch            | 1         | 1.64%   |
| Toshiba TV TSB0206 1920x1080 1600x1000mm 74.3-inch                   | 1         | 1.64%   |
| Samsung Electronics SyncMaster SAM0581 1920x1080 477x268mm 21.5-inch | 1         | 1.64%   |
| Samsung Electronics SyncMaster SAM0116 1024x768 267x200mm 13.1-inch  | 1         | 1.64%   |
| Samsung Electronics S24D330 SAM0D93 1920x1080 531x299mm 24.0-inch    | 1         | 1.64%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch    | 1         | 1.64%   |
| Samsung Electronics S22C450 SAM09C5 1920x1080 477x268mm 21.5-inch    | 1         | 1.64%   |
| Samsung Electronics LCD Monitor SEC4F45 1280x800 331x207mm 15.4-inch | 1         | 1.64%   |
| Samsung Electronics LCD Monitor SEC4141 1280x800 261x163mm 12.1-inch | 1         | 1.64%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 1         | 1.64%   |
| Medion MD 20310 MED3645 1920x1080 521x293mm 23.5-inch                | 1         | 1.64%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch          | 1         | 1.64%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch        | 1         | 1.64%   |
| LG Display LCD Monitor LGD059E 1920x1080 382x215mm 17.3-inch         | 1         | 1.64%   |
| LG Display LCD Monitor LGD04E1 1366x768 344x194mm 15.5-inch          | 1         | 1.64%   |
| LG Display LCD Monitor LGD03F8 1366x768 345x194mm 15.6-inch          | 1         | 1.64%   |
| LG Display LCD Monitor LGD02E1 1600x900 382x215mm 17.3-inch          | 1         | 1.64%   |
| LG Display LCD Monitor LGD0266 1366x768 344x194mm 15.5-inch          | 1         | 1.64%   |
| LG Display LCD Monitor LGD01C5 1366x768 293x165mm 13.2-inch          | 1         | 1.64%   |
| Lenovo LCD Monitor LEN4033 1440x900 304x190mm 14.1-inch              | 1         | 1.64%   |
| Lenovo LCD Monitor LEN4022 1400x1050 286x214mm 14.1-inch             | 1         | 1.64%   |
| JCH F24 JCH1919 1920x1080 520x310mm 23.8-inch                        | 1         | 1.64%   |
| Insignia NS-32D20SNA14 BBY0032 1360x768 544x326mm 25.0-inch          | 1         | 1.64%   |
| HUYINIUDA HUYINIUDA HUY1850 1366x768 410x220mm 18.3-inch             | 1         | 1.64%   |
| Hitachi HDMI HEC0088 1920x540                                        | 1         | 1.64%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch             | 1         | 1.64%   |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                  | 1         | 1.64%   |
| Goldstar W2042 GSM4E7E 1680x1050 434x270mm 20.1-inch                 | 1         | 1.64%   |
| Goldstar TV GSM9CF6 1360x768 708x398mm 32.0-inch                     | 1         | 1.64%   |
| Goldstar T710SH GSM436B 1280x960 310x230mm 15.2-inch                 | 1         | 1.64%   |
| Goldstar L1953H GSM4B3D 1280x1024 338x270mm 17.0-inch                | 1         | 1.64%   |
| Goldstar L1953H GSM4B3C 1280x1024 338x270mm 17.0-inch                | 1         | 1.64%   |
| Goldstar 23MP55 GSM5A23 1920x1080 510x290mm 23.1-inch                | 1         | 1.64%   |
| Dell LCD Monitor S2715H 3840x1080                                    | 1         | 1.64%   |
| Dell LCD Monitor S2715H                                              | 1         | 1.64%   |
| Dell IN1930 DELF03B 1366x768 410x230mm 18.5-inch                     | 1         | 1.64%   |
| Dell E176FP DELA014 1280x1024 338x270mm 17.0-inch                    | 1         | 1.64%   |
| CPT LCD Monitor CPT37D5 1920x1200 260x160mm 12.0-inch                | 1         | 1.64%   |
| CPT LCD Monitor CPT04CE 1024x600 222x130mm 10.1-inch                 | 1         | 1.64%   |
| CPT LCD Monitor CPT04C4 1024x600 222x130mm 10.1-inch                 | 1         | 1.64%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 21        | 35%     |
| 1366x768 (WXGA)    | 13        | 21.67%  |
| 1600x900 (HD+)     | 4         | 6.67%   |
| 1280x1024 (SXGA)   | 3         | 5%      |
| 1024x600           | 3         | 5%      |
| 1920x540           | 2         | 3.33%   |
| 1680x1050 (WSXGA+) | 2         | 3.33%   |
| 1440x900 (WXGA+)   | 2         | 3.33%   |
| 1280x800 (WXGA)    | 2         | 3.33%   |
| 3840x1080          | 1         | 1.67%   |
| 2288x1287          | 1         | 1.67%   |
| 1920x1200 (WUXGA)  | 1         | 1.67%   |
| 1400x1050          | 1         | 1.67%   |
| 1360x768           | 1         | 1.67%   |
| 1280x960           | 1         | 1.67%   |
| 1024x768 (XGA)     | 1         | 1.67%   |
| Unknown            | 1         | 1.67%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 17      | 9         | 15.25%  |
| 15      | 9         | 15.25%  |
| 13      | 9         | 15.25%  |
| 23      | 6         | 10.17%  |
| 14      | 4         | 6.78%   |
| 20      | 3         | 5.08%   |
| 18      | 3         | 5.08%   |
| 10      | 3         | 5.08%   |
| 48      | 2         | 3.39%   |
| 24      | 2         | 3.39%   |
| 21      | 2         | 3.39%   |
| 16      | 2         | 3.39%   |
| 142     | 1         | 1.69%   |
| 74      | 1         | 1.69%   |
| 72      | 1         | 1.69%   |
| 12      | 1         | 1.69%   |
| Unknown | 1         | 1.69%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 20        | 33.9%   |
| 201-300        | 10        | 16.95%  |
| 501-600        | 8         | 13.56%  |
| 401-500        | 8         | 13.56%  |
| 351-400        | 7         | 11.86%  |
| 1501-2000      | 2         | 3.39%   |
| 1001-1500      | 2         | 3.39%   |
| More than 2000 | 1         | 1.69%   |
| Unknown        | 1         | 1.69%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 41        | 69.49%  |
| 16/10   | 8         | 13.56%  |
| 5/4     | 3         | 5.08%   |
| 4/3     | 3         | 5.08%   |
| 1.96    | 2         | 3.39%   |
| 1.00    | 1         | 1.69%   |
| Unknown | 1         | 1.69%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 10        | 16.95%  |
| 81-90          | 8         | 13.56%  |
| 201-250        | 8         | 13.56%  |
| 121-130        | 6         | 10.17%  |
| 151-200        | 5         | 8.47%   |
| 141-150        | 5         | 8.47%   |
| 71-80          | 4         | 6.78%   |
| More than 1000 | 3         | 5.08%   |
| 41-50          | 3         | 5.08%   |
| 131-140        | 2         | 3.39%   |
| 501-1000       | 2         | 3.39%   |
| 61-70          | 1         | 1.69%   |
| 91-100         | 1         | 1.69%   |
| Unknown        | 1         | 1.69%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 20        | 35.09%  |
| 101-120 | 17        | 29.82%  |
| 121-160 | 13        | 22.81%  |
| 1-50    | 5         | 8.77%   |
| 161-240 | 1         | 1.75%   |
| Unknown | 1         | 1.75%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 54        | 88.52%  |
| 2     | 4         | 6.56%   |
| 0     | 3         | 4.92%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 27        | 31.03%  |
| Intel                    | 24        | 27.59%  |
| Qualcomm Atheros         | 11        | 12.64%  |
| Broadcom                 | 5         | 5.75%   |
| Broadcom Limited         | 4         | 4.6%    |
| Ralink Technology        | 3         | 3.45%   |
| Marvell Technology Group | 3         | 3.45%   |
| TP-Link                  | 2         | 2.3%    |
| Nvidia                   | 2         | 2.3%    |
| VIA Technologies         | 1         | 1.15%   |
| Samsung Electronics      | 1         | 1.15%   |
| Ralink                   | 1         | 1.15%   |
| OPPO Electronics         | 1         | 1.15%   |
| Edimax Technology        | 1         | 1.15%   |
| D-Link System            | 1         | 1.15%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 16        | 15.69%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 6         | 5.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 3         | 2.94%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 2         | 1.96%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 2         | 1.96%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 2         | 1.96%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 2         | 1.96%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 2         | 1.96%   |
| Intel Wireless 8260                                                           | 2         | 1.96%   |
| Intel Wireless 7265                                                           | 2         | 1.96%   |
| Intel Wireless 7260                                                           | 2         | 1.96%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 2         | 1.96%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                              | 2         | 1.96%   |
| VIA VT6102/VT6103 [Rhine-II]                                                  | 1         | 0.98%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                                         | 1         | 0.98%   |
| TP-Link 802.11ac WLAN Adapter                                                 | 1         | 0.98%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 1         | 0.98%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 1         | 0.98%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.98%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 1         | 0.98%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 1         | 0.98%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                              | 1         | 0.98%   |
| Ralink RT5370 Wireless Adapter                                                | 1         | 0.98%   |
| Ralink RT3072 Wireless Adapter                                                | 1         | 0.98%   |
| Ralink MT7601U Wireless Adapter                                               | 1         | 0.98%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                     | 1         | 0.98%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 1         | 0.98%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 1         | 0.98%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1         | 0.98%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1         | 0.98%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1         | 0.98%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 1         | 0.98%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                         | 1         | 0.98%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 0.98%   |
| OPPO SM8350-MTP _SN:1518BD09                                                  | 1         | 0.98%   |
| Nvidia MCP61 Ethernet                                                         | 1         | 0.98%   |
| Nvidia MCP51 Ethernet Controller                                              | 1         | 0.98%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                       | 1         | 0.98%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                       | 1         | 0.98%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                          | 1         | 0.98%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


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

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


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
| TP-Link TL-WN821N Version 5 RTL8192EU                                                       | 1         | 2.13%   |
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

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 23        | 41.82%  |
| Intel                    | 13        | 23.64%  |
| Qualcomm Atheros         | 5         | 9.09%   |
| Broadcom                 | 4         | 7.27%   |
| Marvell Technology Group | 3         | 5.45%   |
| Nvidia                   | 2         | 3.64%   |
| Broadcom Limited         | 2         | 3.64%   |
| VIA Technologies         | 1         | 1.82%   |
| Samsung Electronics      | 1         | 1.82%   |
| OPPO Electronics         | 1         | 1.82%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 16        | 29.09%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 10.91%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 5.45%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 3.64%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 2         | 3.64%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 1.82%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.82%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 1.82%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.82%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 1.82%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.82%   |
| OPPO SM8350-MTP _SN:1518BD09                                      | 1         | 1.82%   |
| Nvidia MCP61 Ethernet                                             | 1         | 1.82%   |
| Nvidia MCP51 Ethernet Controller                                  | 1         | 1.82%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 1.82%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 1.82%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 1.82%   |
| Intel I211 Gigabit Network Connection                             | 1         | 1.82%   |
| Intel Ethernet Controller I225-V                                  | 1         | 1.82%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.82%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.82%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.82%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 1.82%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 1.82%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 1.82%   |
| Intel 82566DM Gigabit Network Connection                          | 1         | 1.82%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 1         | 1.82%   |
| Broadcom NetXtreme BCM5721 Gigabit Ethernet PCI Express           | 1         | 1.82%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.82%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1         | 1.82%   |
| Broadcom Limited NetLink BCM57788 Gigabit Ethernet PCIe           | 1         | 1.82%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 53        | 54.64%  |
| WiFi     | 44        | 45.36%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 34        | 52.31%  |
| Ethernet | 31        | 47.69%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 31        | 50.82%  |
| 1     | 27        | 44.26%  |
| 0     | 2         | 3.28%   |
| 3     | 1         | 1.64%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 52        | 82.54%  |
| Yes  | 11        | 17.46%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


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

![Bluetooth Model](./images/pie_chart/bt_model.svg)


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

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 40        | 54.05%  |
| AMD                 | 18        | 24.32%  |
| Nvidia              | 8         | 10.81%  |
| C-Media Electronics | 2         | 2.7%    |
| VIA Technologies    | 1         | 1.35%   |
| Plantronics         | 1         | 1.35%   |
| Native Instruments  | 1         | 1.35%   |
| Focusrite-Novation  | 1         | 1.35%   |
| Creative Labs       | 1         | 1.35%   |
| ASUSTek Computer    | 1         | 1.35%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 8         | 9.2%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 4.6%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 4.6%    |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 4.6%    |
| AMD FCH Azalia Controller                                                                         | 4         | 4.6%    |
| Intel Sunrise Point-LP HD Audio                                                                   | 3         | 3.45%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 3.45%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 3.45%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 2         | 2.3%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 2.3%    |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 2         | 2.3%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 2.3%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 2         | 2.3%    |
| AMD Starship/Matisse HD Audio Controller                                                          | 2         | 2.3%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 2.3%    |
| AMD Navi 10 HDMI Audio                                                                            | 2         | 2.3%    |
| AMD Family 17h/19h HD Audio Controller                                                            | 2         | 2.3%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 2.3%    |
| AMD Barts HDMI Audio [Radeon HD 6790/6850/6870 / 7720 OEM]                                        | 2         | 2.3%    |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1         | 1.15%   |
| Plantronics USB DSP v4 Audio Interface                                                            | 1         | 1.15%   |
| Nvidia MCP61 High Definition Audio                                                                | 1         | 1.15%   |
| Nvidia MCP51 High Definition Audio                                                                | 1         | 1.15%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 1.15%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 1.15%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 1.15%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 1.15%   |
| Native Instruments KOMPLETE KONTROL M32                                                           | 1         | 1.15%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 1.15%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 1.15%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 1         | 1.15%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 1.15%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 1.15%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 1         | 1.15%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 1.15%   |
| Intel 200 Series PCH HD Audio                                                                     | 1         | 1.15%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 1.15%   |
| Focusrite-Novation Focusrite Scarlett 2i2 2nd Gen                                                 | 1         | 1.15%   |
| Creative Labs CA0106/CA0111 [SB Live!/Audigy/X-Fi Series]                                         | 1         | 1.15%   |
| C-Media Electronics USB Audio Device                                                              | 1         | 1.15%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 12        | 26.67%  |
| Unknown             | 10        | 22.22%  |
| Kingston            | 5         | 11.11%  |
| Micron Technology   | 4         | 8.89%   |
| SK hynix            | 3         | 6.67%   |
| Corsair             | 3         | 6.67%   |
| Nanya Technology    | 2         | 4.44%   |
| G.Skill             | 2         | 4.44%   |
| GOODRAM             | 1         | 2.22%   |
| Elpida              | 1         | 2.22%   |
| Crucial             | 1         | 2.22%   |
| Avant               | 1         | 2.22%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                | 2         | 4%      |
| Unknown RAM Module 2048MB DIMM 800MT/s                     | 2         | 4%      |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s      | 2         | 4%      |
| Unknown RAM Module 2GB SODIMM SDRAM                        | 1         | 2%      |
| Unknown RAM Module 2GB SODIMM DDR2 266MT/s                 | 1         | 2%      |
| Unknown RAM Module 2048MB SODIMM 800MT/s                   | 1         | 2%      |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                | 1         | 2%      |
| Unknown RAM Module 1024MB SODIMM DDR2                      | 1         | 2%      |
| Unknown RAM Module 1024MB SODIMM 800MT/s                   | 1         | 2%      |
| Unknown RAM Module 1024MB DIMM SDRAM                       | 1         | 2%      |
| SK hynix RAM Module 4GB SODIMM DDR3 1066MT/s               | 1         | 2%      |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s    | 1         | 2%      |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s     | 1         | 2%      |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                | 1         | 2%      |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s      | 1         | 2%      |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s      | 1         | 2%      |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s      | 1         | 2%      |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1334MT/s      | 1         | 2%      |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s      | 1         | 2%      |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s      | 1         | 2%      |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s      | 1         | 2%      |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s      | 1         | 2%      |
| Samsung RAM M3 78T5663EH3-CF7 2GB DIMM DDR2 800MT/s        | 1         | 2%      |
| Samsung RAM M3 78T2863RZS-CE6 1GB DIMM DDR2 667MT/s        | 1         | 2%      |
| Samsung RAM M3 78T2863QZS-CE6 1GB DIMM DDR2 1639MT/s       | 1         | 2%      |
| Samsung RAM K4E8E324EB-EGCF 2GB LPDDR3 1867MT/s            | 1         | 2%      |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s       | 1         | 2%      |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s       | 1         | 2%      |
| Micron RAM 8ATF1G64HZ-2G6H1 8GB SODIMM DDR4 2667MT/s       | 1         | 2%      |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s | 1         | 2%      |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s      | 1         | 2%      |
| Micron RAM 16JSF51264HZ-1G4D1 4096MB SODIMM DDR3 1334MT/s  | 1         | 2%      |
| Kingston RAM Module 4GB SODIMM DDR3 800MT/s                | 1         | 2%      |
| Kingston RAM Module 16GB SODIMM DDR4 2133MT/s              | 1         | 2%      |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s        | 1         | 2%      |
| Kingston RAM ACR16D3LS1KBG/4G 4GB SODIMM DDR3 1600MT/s     | 1         | 2%      |
| Kingston RAM ACR128X64D3S1333C9 1GB SODIMM DDR3 1333MT/s   | 1         | 2%      |
| Kingston RAM 99U5471-030.A00LF 8GB DIMM DDR3 1333MT/s      | 1         | 2%      |
| GOODRAM RAM GR1600S3V64L11/8G 8GB SODIMM DDR3 1600MT/s     | 1         | 2%      |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s         | 1         | 2%      |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 22        | 50%     |
| DDR4    | 10        | 22.73%  |
| SDRAM   | 4         | 9.09%   |
| DDR2    | 4         | 9.09%   |
| Unknown | 3         | 6.82%   |
| LPDDR3  | 1         | 2.27%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 28        | 66.67%  |
| DIMM         | 12        | 28.57%  |
| Row Of Chips | 1         | 2.38%   |
| Unknown      | 1         | 2.38%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 14        | 29.17%  |
| 2048  | 14        | 29.17%  |
| 4096  | 11        | 22.92%  |
| 1024  | 5         | 10.42%  |
| 16384 | 4         | 8.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 12        | 25.53%  |
| 800     | 5         | 10.64%  |
| 2667    | 4         | 8.51%   |
| 1333    | 4         | 8.51%   |
| 3200    | 3         | 6.38%   |
| 1066    | 3         | 6.38%   |
| Unknown | 3         | 6.38%   |
| 1334    | 2         | 4.26%   |
| 4199    | 1         | 2.13%   |
| 3666    | 1         | 2.13%   |
| 2666    | 1         | 2.13%   |
| 2400    | 1         | 2.13%   |
| 2133    | 1         | 2.13%   |
| 2048    | 1         | 2.13%   |
| 1867    | 1         | 2.13%   |
| 1800    | 1         | 2.13%   |
| 1639    | 1         | 2.13%   |
| 667     | 1         | 2.13%   |
| 266     | 1         | 2.13%   |

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

![Camera Model](./images/pie_chart/camera_model.svg)


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
| Samsung Galaxy series, misc. (MTP mode)                         | 1         | 2.78%   |
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

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 3         | 42.86%  |
| AuthenTec                  | 2         | 28.57%  |
| STMicroelectronics         | 1         | 14.29%  |
| Shenzhen Goodix Technology | 1         | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


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
| 0     | 39        | 63.93%  |
| 1     | 18        | 29.51%  |
| 2     | 4         | 6.56%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 9         | 32.14%  |
| Fingerprint reader    | 7         | 25%     |
| Net/wireless          | 6         | 21.43%  |
| Multimedia controller | 4         | 14.29%  |
| Chipcard              | 1         | 3.57%   |
| Camera                | 1         | 3.57%   |

