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

Total: 91

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [90c03881ae](https://linux-hardware.org/?probe=90c03881ae) | Jul 29, 2023 |
| Acer          | Aspire A315-58              | Notebook    | [d7383d2980](https://linux-hardware.org/?probe=d7383d2980) | Jul 20, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [f7a66609af](https://linux-hardware.org/?probe=f7a66609af) | Jul 13, 2023 |
| ASUSTek       | ET2411_W8                   | All in one  | [27d0310272](https://linux-hardware.org/?probe=27d0310272) | Jul 13, 2023 |
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

![OS](./images/pie_chart/os_name.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Sparky 6    | 16        | 22.22%  |
| Sparky 7    | 12        | 16.67%  |
| Sparky 6.1  | 6         | 8.33%   |
| Sparky 6.5  | 5         | 6.94%   |
| Sparky 5.12 | 5         | 6.94%   |
| Sparky 6.6  | 4         | 5.56%   |
| Sparky 6.3  | 4         | 5.56%   |
| Sparky 6.7  | 3         | 4.17%   |
| Sparky 6.0  | 3         | 4.17%   |
| Sparky 5.14 | 3         | 4.17%   |
| Sparky 5.10 | 3         | 4.17%   |
| Sparky 8    | 2         | 2.78%   |
| Sparky 7.0  | 2         | 2.78%   |
| Sparky 6.2  | 2         | 2.78%   |
| Sparky 5.13 | 2         | 2.78%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Sparky | 66        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Computers | Percent |
|---------------------------|-----------|---------|
| 5.10.0-21-amd64           | 4         | 5.33%   |
| 5.10.0-11-686             | 4         | 5.33%   |
| 5.10.0-9-amd64            | 3         | 4%      |
| 5.10.0-8-amd64            | 3         | 4%      |
| 5.10.0-6-amd64            | 3         | 4%      |
| 4.19.0-8-amd64            | 3         | 4%      |
| 4.19.0-12-amd64           | 3         | 4%      |
| 5.18.0-4-amd64            | 2         | 2.67%   |
| 5.18.0-2-amd64            | 2         | 2.67%   |
| 5.17.0-1-amd64            | 2         | 2.67%   |
| 5.10.0-3-amd64            | 2         | 2.67%   |
| 5.10.0-23-amd64           | 2         | 2.67%   |
| 5.10.0-14-amd64           | 2         | 2.67%   |
| 4.19.0-13-686             | 2         | 2.67%   |
| 4.19.0-10-686             | 2         | 2.67%   |
| 6.4.4-sparky8-amd64       | 1         | 1.33%   |
| 6.4.0-1-amd64             | 1         | 1.33%   |
| 6.3.3-1-liquorix-amd64    | 1         | 1.33%   |
| 6.3.0-1-amd64             | 1         | 1.33%   |
| 6.2.0-sparky-amd64        | 1         | 1.33%   |
| 6.1.0-9-amd64             | 1         | 1.33%   |
| 6.1.0-7-amd64             | 1         | 1.33%   |
| 6.1.0-3-amd64             | 1         | 1.33%   |
| 6.0.11-x64v2-rt14-xanmod1 | 1         | 1.33%   |
| 6.0.0-5-amd64             | 1         | 1.33%   |
| 5.9.13-sparky-amd64       | 1         | 1.33%   |
| 5.9.0-4-amd64             | 1         | 1.33%   |
| 5.8.13-sparky-amd64       | 1         | 1.33%   |
| 5.8.0-2-amd64             | 1         | 1.33%   |
| 5.7.2-sparky-amd64        | 1         | 1.33%   |
| 5.6.0-2-amd64             | 1         | 1.33%   |
| 5.5.0-2-amd64             | 1         | 1.33%   |
| 5.4.7-sparky-amd64        | 1         | 1.33%   |
| 5.2.0-2-amd64             | 1         | 1.33%   |
| 5.18.3-sparky-amd64       | 1         | 1.33%   |
| 5.17.3-sparky-amd64       | 1         | 1.33%   |
| 5.16.5-sparky-amd64       | 1         | 1.33%   |
| 5.16.0-5-amd64            | 1         | 1.33%   |
| 5.15.0-3-amd64            | 1         | 1.33%   |
| 5.14.0-4-amd64            | 1         | 1.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 30        | 41.67%  |
| 4.19.0  | 10        | 13.89%  |
| 5.18.0  | 4         | 5.56%   |
| 6.1.0   | 3         | 4.17%   |
| 5.17.0  | 2         | 2.78%   |
| 6.4.4   | 1         | 1.39%   |
| 6.4.0   | 1         | 1.39%   |
| 6.3.3   | 1         | 1.39%   |
| 6.3.0   | 1         | 1.39%   |
| 6.2.0   | 1         | 1.39%   |
| 6.0.11  | 1         | 1.39%   |
| 6.0.0   | 1         | 1.39%   |
| 5.9.13  | 1         | 1.39%   |
| 5.9.0   | 1         | 1.39%   |
| 5.8.13  | 1         | 1.39%   |
| 5.8.0   | 1         | 1.39%   |
| 5.7.2   | 1         | 1.39%   |
| 5.6.0   | 1         | 1.39%   |
| 5.5.0   | 1         | 1.39%   |
| 5.4.7   | 1         | 1.39%   |
| 5.2.0   | 1         | 1.39%   |
| 5.18.3  | 1         | 1.39%   |
| 5.17.3  | 1         | 1.39%   |
| 5.16.5  | 1         | 1.39%   |
| 5.16.0  | 1         | 1.39%   |
| 5.15.0  | 1         | 1.39%   |
| 5.14.0  | 1         | 1.39%   |
| 5.10.4  | 1         | 1.39%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 31        | 43.66%  |
| 4.19    | 10        | 14.08%  |
| 5.18    | 5         | 7.04%   |
| 6.1     | 3         | 4.23%   |
| 5.17    | 3         | 4.23%   |
| 6.4     | 2         | 2.82%   |
| 6.3     | 2         | 2.82%   |
| 5.9     | 2         | 2.82%   |
| 5.8     | 2         | 2.82%   |
| 5.16    | 2         | 2.82%   |
| 6.2     | 1         | 1.41%   |
| 6.0     | 1         | 1.41%   |
| 5.7     | 1         | 1.41%   |
| 5.6     | 1         | 1.41%   |
| 5.5     | 1         | 1.41%   |
| 5.4     | 1         | 1.41%   |
| 5.2     | 1         | 1.41%   |
| 5.15    | 1         | 1.41%   |
| 5.14    | 1         | 1.41%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 60        | 90.91%  |
| i686   | 6         | 9.09%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| XFCE             | 26        | 38.81%  |
| LXQt             | 15        | 22.39%  |
| Unknown          | 8         | 11.94%  |
| KDE5             | 6         | 8.96%   |
| openbox          | 3         | 4.48%   |
| X-Cinnamon       | 2         | 2.99%   |
| MATE             | 2         | 2.99%   |
| GNOME            | 2         | 2.99%   |
| lightdm-xsession | 1         | 1.49%   |
| ICEWM            | 1         | 1.49%   |
| GNOME Classic    | 1         | 1.49%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 63        | 92.65%  |
| Tty  | 5         | 7.35%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 20        | 30.3%   |
| LightDM | 16        | 24.24%  |
| SDDM    | 15        | 22.73%  |
| TDM     | 13        | 19.7%   |
| XDM     | 1         | 1.52%   |
| GDM     | 1         | 1.52%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 19        | 28.79%  |
| pt_BR   | 7         | 10.61%  |
| en_GB   | 6         | 9.09%   |
| de_DE   | 5         | 7.58%   |
| fr_FR   | 4         | 6.06%   |
| es_ES   | 4         | 6.06%   |
| pl_PL   | 3         | 4.55%   |
| en_CA   | 2         | 3.03%   |
| Unknown | 2         | 3.03%   |
| sv_SE   | 1         | 1.52%   |
| ru_RU   | 1         | 1.52%   |
| ja_JP   | 1         | 1.52%   |
| it_IT   | 1         | 1.52%   |
| es_US   | 1         | 1.52%   |
| es_MX   | 1         | 1.52%   |
| es_CL   | 1         | 1.52%   |
| es_AR   | 1         | 1.52%   |
| en_ZA   | 1         | 1.52%   |
| en_PH   | 1         | 1.52%   |
| en_IN   | 1         | 1.52%   |
| en_DK   | 1         | 1.52%   |
| de_CH   | 1         | 1.52%   |
| cs_CZ   | 1         | 1.52%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 41        | 62.12%  |
| EFI  | 25        | 37.88%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 58        | 87.88%  |
| Overlay | 3         | 4.55%   |
| Btrfs   | 3         | 4.55%   |
| Zfs     | 1         | 1.52%   |
| Ext2    | 1         | 1.52%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 25        | 37.88%  |
| MBR     | 21        | 31.82%  |
| Unknown | 20        | 30.3%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 57        | 86.36%  |
| Yes       | 9         | 13.64%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 43        | 65.15%  |
| Yes       | 23        | 34.85%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 15        | 22.73%  |
| ASUSTek Computer    | 9         | 13.64%  |
| Dell                | 6         | 9.09%   |
| Lenovo              | 5         | 7.58%   |
| Intel               | 5         | 7.58%   |
| Gigabyte Technology | 5         | 7.58%   |
| MSI                 | 4         | 6.06%   |
| Acer                | 4         | 6.06%   |
| Google              | 2         | 3.03%   |
| Samsung Electronics | 1         | 1.52%   |
| Positivo            | 1         | 1.52%   |
| Panasonic           | 1         | 1.52%   |
| Mediacom            | 1         | 1.52%   |
| HUAWEI              | 1         | 1.52%   |
| Fujitsu Siemens     | 1         | 1.52%   |
| Foxconn             | 1         | 1.52%   |
| eMachines           | 1         | 1.52%   |
| Beelink             | 1         | 1.52%   |
| Apple               | 1         | 1.52%   |
| Unknown             | 1         | 1.52%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| Samsung NC10                          | 1         | 1.52%   |
| Positivo CHT14B                       | 1         | 1.52%   |
| Panasonic CFSZ5-2                     | 1         | 1.52%   |
| MSI MS-7C09                           | 1         | 1.52%   |
| MSI MS-7B86                           | 1         | 1.52%   |
| MSI MS-7721                           | 1         | 1.52%   |
| MSI Alpha 15 A3DDK                    | 1         | 1.52%   |
| Mediacom SmartBook 14 FullHD - SB14UC | 1         | 1.52%   |
| Lenovo ThinkPad T61 7659AB7           | 1         | 1.52%   |
| Lenovo ThinkPad T60 2007FUG           | 1         | 1.52%   |
| Lenovo ThinkPad E15 20RES0GF00        | 1         | 1.52%   |
| Lenovo IdeaPad S206 20154             | 1         | 1.52%   |
| Lenovo G50-30 80G0                    | 1         | 1.52%   |
| Intel NUC5CPYB H61145-408             | 1         | 1.52%   |
| Intel H61                             | 1         | 1.52%   |
| Intel H55                             | 1         | 1.52%   |
| Intel DG43RK AAE78175-402             | 1         | 1.52%   |
| Intel DG41TY AAE47335-300             | 1         | 1.52%   |
| HUAWEI HVY-WXX9                       | 1         | 1.52%   |
| HP Z420 Workstation                   | 1         | 1.52%   |
| HP t5740                              | 1         | 1.52%   |
| HP Stream Notebook PC 13              | 1         | 1.52%   |
| HP Pavilion x360 Convertible 14-ba0xx | 1         | 1.52%   |
| HP Pavilion g7                        | 1         | 1.52%   |
| HP Pavilion dv9000 (GA359UA#ABA)      | 1         | 1.52%   |
| HP Pavilion dv5                       | 1         | 1.52%   |
| HP Laptop 17z-ca100                   | 1         | 1.52%   |
| HP EliteDesk 800 G2 DM 65W            | 1         | 1.52%   |
| HP EliteDesk 705 G2 MINI              | 1         | 1.52%   |
| HP EliteBook Folio 9480m              | 1         | 1.52%   |
| HP EliteBook 8770w                    | 1         | 1.52%   |
| HP EliteBook 8440p                    | 1         | 1.52%   |
| HP EliteBook 745 G3                   | 1         | 1.52%   |
| HP Compaq dc7700 Ultra-slim Desktop   | 1         | 1.52%   |
| Google Swanky                         | 1         | 1.52%   |
| Google Banon                          | 1         | 1.52%   |
| Gigabyte X570S AORUS PRO AX           | 1         | 1.52%   |
| Gigabyte M68M-S2P                     | 1         | 1.52%   |
| Gigabyte H97-Gaming 3                 | 1         | 1.52%   |
| Gigabyte H410M H                      | 1         | 1.52%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                      | Computers | Percent |
|---------------------------|-----------|---------|
| HP Pavilion               | 4         | 6.06%   |
| HP EliteBook              | 4         | 6.06%   |
| Dell Inspiron             | 4         | 6.06%   |
| Acer Aspire               | 4         | 6.06%   |
| Lenovo ThinkPad           | 3         | 4.55%   |
| HP EliteDesk              | 2         | 3.03%   |
| Samsung NC10              | 1         | 1.52%   |
| Positivo CHT14B           | 1         | 1.52%   |
| Panasonic CFSZ5-2         | 1         | 1.52%   |
| MSI MS-7C09               | 1         | 1.52%   |
| MSI MS-7B86               | 1         | 1.52%   |
| MSI MS-7721               | 1         | 1.52%   |
| MSI Alpha                 | 1         | 1.52%   |
| Mediacom SmartBook        | 1         | 1.52%   |
| Lenovo IdeaPad            | 1         | 1.52%   |
| Lenovo G50-30             | 1         | 1.52%   |
| Intel NUC5CPYB            | 1         | 1.52%   |
| Intel H61                 | 1         | 1.52%   |
| Intel H55                 | 1         | 1.52%   |
| Intel DG43RK              | 1         | 1.52%   |
| Intel DG41TY              | 1         | 1.52%   |
| HUAWEI HVY-WXX9           | 1         | 1.52%   |
| HP Z420                   | 1         | 1.52%   |
| HP t5740                  | 1         | 1.52%   |
| HP Stream                 | 1         | 1.52%   |
| HP Laptop                 | 1         | 1.52%   |
| HP Compaq                 | 1         | 1.52%   |
| Google Swanky             | 1         | 1.52%   |
| Google Banon              | 1         | 1.52%   |
| Gigabyte X570S            | 1         | 1.52%   |
| Gigabyte M68M-S2P         | 1         | 1.52%   |
| Gigabyte H97-Gaming       | 1         | 1.52%   |
| Gigabyte H410M            | 1         | 1.52%   |
| Gigabyte G41M-ES2L        | 1         | 1.52%   |
| Fujitsu Siemens STYLISTIC | 1         | 1.52%   |
| Foxconn p6-2010fr         | 1         | 1.52%   |
| eMachines E525            | 1         | 1.52%   |
| Dell OptiPlex             | 1         | 1.52%   |
| Dell Latitude             | 1         | 1.52%   |
| Beelink BT3               | 1         | 1.52%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2009 | 8         | 12.12%  |
| 2014 | 6         | 9.09%   |
| 2012 | 6         | 9.09%   |
| 2011 | 6         | 9.09%   |
| 2021 | 5         | 7.58%   |
| 2008 | 5         | 7.58%   |
| 2018 | 4         | 6.06%   |
| 2017 | 4         | 6.06%   |
| 2010 | 4         | 6.06%   |
| 2020 | 3         | 4.55%   |
| 2019 | 3         | 4.55%   |
| 2016 | 3         | 4.55%   |
| 2007 | 3         | 4.55%   |
| 2015 | 2         | 3.03%   |
| 2006 | 2         | 3.03%   |
| 2022 | 1         | 1.52%   |
| 2013 | 1         | 1.52%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 37        | 56.06%  |
| Desktop     | 26        | 39.39%  |
| Convertible | 1         | 1.52%   |
| Mini pc     | 1         | 1.52%   |
| All in one  | 1         | 1.52%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 66        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 64        | 96.97%  |
| Yes  | 2         | 3.03%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 21        | 31.82%  |
| 4.01-8.0   | 12        | 18.18%  |
| 8.01-16.0  | 9         | 13.64%  |
| 1.01-2.0   | 8         | 12.12%  |
| 16.01-24.0 | 7         | 10.61%  |
| 2.01-3.0   | 5         | 7.58%   |
| 24.01-32.0 | 2         | 3.03%   |
| 32.01-64.0 | 1         | 1.52%   |
| 0.51-1.0   | 1         | 1.52%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 30        | 42.86%  |
| 2.01-3.0 | 15        | 21.43%  |
| 0.51-1.0 | 12        | 17.14%  |
| 4.01-8.0 | 6         | 8.57%   |
| 3.01-4.0 | 4         | 5.71%   |
| 0.01-0.5 | 3         | 4.29%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 47        | 68.12%  |
| 2      | 14        | 20.29%  |
| 4      | 4         | 5.8%    |
| 6      | 2         | 2.9%    |
| 5      | 1         | 1.45%   |
| 3      | 1         | 1.45%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 43        | 65.15%  |
| Yes       | 23        | 34.85%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 58        | 87.88%  |
| No        | 8         | 12.12%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 46        | 69.7%   |
| No        | 20        | 30.3%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 33        | 50%     |
| No        | 33        | 50%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 11        | 16.67%  |
| Germany      | 8         | 12.12%  |
| Brazil       | 7         | 10.61%  |
| UK           | 6         | 9.09%   |
| France       | 5         | 7.58%   |
| Spain        | 3         | 4.55%   |
| Poland       | 3         | 4.55%   |
| Indonesia    | 3         | 4.55%   |
| Canada       | 3         | 4.55%   |
| Argentina    | 2         | 3.03%   |
| Venezuela    | 1         | 1.52%   |
| Uzbekistan   | 1         | 1.52%   |
| Switzerland  | 1         | 1.52%   |
| Sweden       | 1         | 1.52%   |
| South Africa | 1         | 1.52%   |
| Philippines  | 1         | 1.52%   |
| New Zealand  | 1         | 1.52%   |
| Mexico       | 1         | 1.52%   |
| Lebanon      | 1         | 1.52%   |
| Japan        | 1         | 1.52%   |
| Italy        | 1         | 1.52%   |
| India        | 1         | 1.52%   |
| Czechia      | 1         | 1.52%   |
| Chile        | 1         | 1.52%   |
| Belgium      | 1         | 1.52%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Rio de Janeiro      | 2         | 2.82%   |
| Montreuil           | 2         | 2.82%   |
| Leipzig             | 2         | 2.82%   |
| Woking              | 1         | 1.41%   |
| West Palm Beach     | 1         | 1.41%   |
| Wenatchee           | 1         | 1.41%   |
| Tucson              | 1         | 1.41%   |
| Trelaze             | 1         | 1.41%   |
| Tauranga            | 1         | 1.41%   |
| Takahama            | 1         | 1.41%   |
| Surabaya            | 1         | 1.41%   |
| Spokane             | 1         | 1.41%   |
| Sin el Fil          | 1         | 1.41%   |
| Santo André        | 1         | 1.41%   |
| San Cristóbal      | 1         | 1.41%   |
| San Antonio         | 1         | 1.41%   |
| Salina Cruz         | 1         | 1.41%   |
| Sainte-Julie        | 1         | 1.41%   |
| Rudersberg          | 1         | 1.41%   |
| Rosario             | 1         | 1.41%   |
| Rio Claro           | 1         | 1.41%   |
| Quezon City         | 1         | 1.41%   |
| Pujaudran           | 1         | 1.41%   |
| Puente Alto         | 1         | 1.41%   |
| Presidente Prudente | 1         | 1.41%   |
| Posadas             | 1         | 1.41%   |
| Pompano Beach       | 1         | 1.41%   |
| Munich              | 1         | 1.41%   |
| Montreal            | 1         | 1.41%   |
| Mnisek pod Brdy     | 1         | 1.41%   |
| Milano              | 1         | 1.41%   |
| Miekoszyn           | 1         | 1.41%   |
| Mannheim            | 1         | 1.41%   |
| Madrid              | 1         | 1.41%   |
| Liverpool           | 1         | 1.41%   |
| Little Rock         | 1         | 1.41%   |
| Lienen              | 1         | 1.41%   |
| Koło               | 1         | 1.41%   |
| Kirkcaldy           | 1         | 1.41%   |
| Kage                | 1         | 1.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 18        | 25     | 19.35%  |
| WDC                 | 17        | 19     | 18.28%  |
| Samsung Electronics | 13        | 24     | 13.98%  |
| Unknown             | 7         | 7      | 7.53%   |
| Hitachi             | 6         | 9      | 6.45%   |
| Toshiba             | 3         | 3      | 3.23%   |
| SanDisk             | 3         | 4      | 3.23%   |
| Kingston            | 3         | 3      | 3.23%   |
| Intel               | 3         | 3      | 3.23%   |
| HGST                | 2         | 2      | 2.15%   |
| Goodram             | 2         | 4      | 2.15%   |
| ASMedia             | 2         | 2      | 2.15%   |
| Unknown             | 2         | 2      | 2.15%   |
| XPG                 | 1         | 1      | 1.08%   |
| SPCC                | 1         | 2      | 1.08%   |
| SK hynix            | 1         | 1      | 1.08%   |
| Silicon Motion      | 1         | 1      | 1.08%   |
| ORICO               | 1         | 1      | 1.08%   |
| Netac               | 1         | 1      | 1.08%   |
| Micron Technology   | 1         | 1      | 1.08%   |
| Gigabyte Technology | 1         | 1      | 1.08%   |
| Fujitsu             | 1         | 2      | 1.08%   |
| Crucial             | 1         | 1      | 1.08%   |
| ASUS-JM             | 1         | 1      | 1.08%   |
| A-DATA Technology   | 1         | 1      | 1.08%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| WDC WD1600BEVT-22ZCT0 160GB          | 2         | 2%      |
| Unknown MMC Card  32GB               | 2         | 2%      |
| Seagate ST500LT012-1DG142 500GB      | 2         | 2%      |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 2         | 2%      |
| Seagate Backup+ Hub BK 8TB           | 2         | 2%      |
| Samsung HD161GJ 160GB                | 2         | 2%      |
| Hitachi HTS545025B9A300 250GB        | 2         | 2%      |
| Unknown                              | 2         | 2%      |
| XPG GAMMIX S11 Pro 1TB               | 1         | 1%      |
| WDC WD800JD-08MSA1 80GB              | 1         | 1%      |
| WDC WD7500BPVX-22JC3T0 752GB         | 1         | 1%      |
| WDC WD5000BEVT-22ZAT0 500GB          | 1         | 1%      |
| WDC WD5000AVVS-63ZWB0 500GB          | 1         | 1%      |
| WDC WD5000AAKS-75V0A0 500GB          | 1         | 1%      |
| WDC WD50 00LPLX-08ZNTT0 500GB        | 1         | 1%      |
| WDC WD50 00LPCX-21VHAT0 500GB        | 1         | 1%      |
| WDC WD3200BPVT-75ZEST0 320GB         | 1         | 1%      |
| WDC WD3200AAKS-75L9A0 320GB          | 1         | 1%      |
| WDC WD2500AAKX-07U6AA0 250GB         | 1         | 1%      |
| WDC WD2500AAJS-00L7A0 250GB          | 1         | 1%      |
| WDC WD1600AAJS-08L7A0 160GB          | 1         | 1%      |
| WDC WD10EZEX-60WN4A0 1TB             | 1         | 1%      |
| WDC WD10EADS-00M2B0 1TB              | 1         | 1%      |
| WDC PC SN730 SDBPNTY-512G-1006 512GB | 1         | 1%      |
| Unknown SDC  8GB                     | 1         | 1%      |
| Unknown NCard  32GB                  | 1         | 1%      |
| Unknown MMC Card  64GB               | 1         | 1%      |
| Unknown HBG4a2  32GB                 | 1         | 1%      |
| Unknown 016GE2  16GB                 | 1         | 1%      |
| Toshiba MQ04ABF100 1TB               | 1         | 1%      |
| Toshiba DT01ACA100 1TB               | 1         | 1%      |
| Toshiba DT01ACA050 500GB             | 1         | 1%      |
| SPCC Solid State Disk 256GB          | 1         | 1%      |
| SK hynix BC711 HFM256GD3JX013N 256GB | 1         | 1%      |
| Silicon Motion PCIe-8 SSD 512GB      | 1         | 1%      |
| Seagate ST975042 0AS 752GB           | 1         | 1%      |
| Seagate ST9500325AS 500GB            | 1         | 1%      |
| Seagate ST9250320AS 250GB            | 1         | 1%      |
| Seagate ST9250315AS 250GB            | 1         | 1%      |
| Seagate ST9160310AS 160GB            | 1         | 1%      |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 18        | 23     | 33.96%  |
| WDC                 | 16        | 18     | 30.19%  |
| Hitachi             | 6         | 9      | 11.32%  |
| Samsung Electronics | 5         | 12     | 9.43%   |
| Toshiba             | 3         | 3      | 5.66%   |
| HGST                | 2         | 2      | 3.77%   |
| ASMedia             | 2         | 2      | 3.77%   |
| Fujitsu             | 1         | 2      | 1.89%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 8      | 21.74%  |
| Kingston            | 3         | 3      | 13.04%  |
| Intel               | 3         | 3      | 13.04%  |
| SanDisk             | 2         | 2      | 8.7%    |
| Goodram             | 2         | 4      | 8.7%    |
| SPCC                | 1         | 2      | 4.35%   |
| ORICO               | 1         | 1      | 4.35%   |
| Netac               | 1         | 1      | 4.35%   |
| Micron Technology   | 1         | 1      | 4.35%   |
| Gigabyte Technology | 1         | 1      | 4.35%   |
| Crucial             | 1         | 1      | 4.35%   |
| ASUS-JM             | 1         | 1      | 4.35%   |
| Unknown             | 1         | 1      | 4.35%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 42        | 71     | 51.22%  |
| SSD     | 21        | 29     | 25.61%  |
| NVMe    | 10        | 12     | 12.2%   |
| MMC     | 8         | 8      | 9.76%   |
| Unknown | 1         | 1      | 1.22%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 55        | 91     | 70.51%  |
| NVMe | 10        | 12     | 12.82%  |
| MMC  | 8         | 8      | 10.26%  |
| SAS  | 5         | 10     | 6.41%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 45        | 71     | 70.31%  |
| 0.51-1.0   | 14        | 22     | 21.88%  |
| 1.01-2.0   | 2         | 2      | 3.13%   |
| 4.01-10.0  | 2         | 4      | 3.13%   |
| 2.01-3.0   | 1         | 1      | 1.56%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 17        | 25.37%  |
| 501-1000       | 13        | 19.4%   |
| 251-500        | 12        | 17.91%  |
| 1-20           | 7         | 10.45%  |
| 21-50          | 6         | 8.96%   |
| 2001-3000      | 4         | 5.97%   |
| 51-100         | 3         | 4.48%   |
| More than 3000 | 2         | 2.99%   |
| Unknown        | 2         | 2.99%   |
| 1001-2000      | 1         | 1.49%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 31        | 44.93%  |
| 21-50          | 11        | 15.94%  |
| 251-500        | 6         | 8.7%    |
| 51-100         | 6         | 8.7%    |
| 101-250        | 4         | 5.8%    |
| 501-1000       | 4         | 5.8%    |
| 1001-2000      | 3         | 4.35%   |
| Unknown        | 2         | 2.9%    |
| More than 3000 | 1         | 1.45%   |
| 2001-3000      | 1         | 1.45%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-22ZAT0 500GB                         | 1         | 1      | 7.69%   |
| WDC WD5000AVVS-63ZWB0 500GB                         | 1         | 1      | 7.69%   |
| WDC WD3200BPVT-75ZEST0 320GB                        | 1         | 1      | 7.69%   |
| WDC WD1600AAJS-08L7A0 160GB                         | 1         | 1      | 7.69%   |
| WDC WD10EADS-00M2B0 1TB                             | 1         | 1      | 7.69%   |
| Seagate ST9500325AS 500GB                           | 1         | 1      | 7.69%   |
| Seagate ST9250315AS 250GB                           | 1         | 1      | 7.69%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 1      | 7.69%   |
| Seagate ST1000DM003-9YN162 1TB                      | 1         | 1      | 7.69%   |
| Micron Technology MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 1      | 7.69%   |
| Intel SSDSC2CW060A3 64GB                            | 1         | 1      | 7.69%   |
| ASMedia ASMT1153E 3TB                               | 1         | 1      | 7.69%   |
| Unknown                                             | 1         | 1      | 7.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| WDC               | 5         | 5      | 38.46%  |
| Seagate           | 4         | 4      | 30.77%  |
| Micron Technology | 1         | 1      | 7.69%   |
| Intel             | 1         | 1      | 7.69%   |
| ASMedia           | 1         | 1      | 7.69%   |
| Unknown           | 1         | 1      | 7.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 5         | 5      | 50%     |
| Seagate | 4         | 4      | 40%     |
| ASMedia | 1         | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 10        | 10     | 76.92%  |
| SSD  | 3         | 3      | 23.08%  |

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
| Works    | 34        | 52     | 45.33%  |
| Detected | 28        | 56     | 37.33%  |
| Malfunc  | 13        | 13     | 17.33%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 42        | 60%     |
| AMD                       | 11        | 15.71%  |
| Samsung Electronics       | 4         | 5.71%   |
| Nvidia                    | 3         | 4.29%   |
| Silicon Motion            | 2         | 2.86%   |
| VIA Technologies          | 1         | 1.43%   |
| SK hynix                  | 1         | 1.43%   |
| Seagate Technology        | 1         | 1.43%   |
| SanDisk                   | 1         | 1.43%   |
| Marvell Technology Group  | 1         | 1.43%   |
| LSI Logic / Symbios Logic | 1         | 1.43%   |
| JMicron Technology        | 1         | 1.43%   |
| ADATA Technology          | 1         | 1.43%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 8         | 9.2%    |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 4         | 4.6%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 3         | 3.45%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 3         | 3.45%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 3         | 3.45%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 3         | 3.45%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 3.45%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 2.3%    |
| Nvidia MCP61 SATA Controller                                                     | 2         | 2.3%    |
| Nvidia MCP61 IDE                                                                 | 2         | 2.3%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 2         | 2.3%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 2.3%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 2         | 2.3%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 2         | 2.3%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 2         | 2.3%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 2.3%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 2         | 2.3%    |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                      | 1         | 1.15%   |
| VIA VT8237A SATA 2-Port Controller                                               | 1         | 1.15%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 1         | 1.15%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 1         | 1.15%   |
| Silicon Motion Non-Volatile memory controller                                    | 1         | 1.15%   |
| Seagate BarraCuda Q5 NVMe SSD (DRAM-less)                                        | 1         | 1.15%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                               | 1         | 1.15%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 1         | 1.15%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 1         | 1.15%   |
| Nvidia MCP51 Serial ATA Controller                                               | 1         | 1.15%   |
| Nvidia MCP51 IDE                                                                 | 1         | 1.15%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                        | 1         | 1.15%   |
| LSI Logic / Symbios Logic SAS1064ET PCI-Express Fusion-MPT SAS                   | 1         | 1.15%   |
| JMicron JMB360 AHCI Controller                                                   | 1         | 1.15%   |
| Intel Tiger Lake-LP SATA Controller                                              | 1         | 1.15%   |
| Intel SATA Controller [RAID mode]                                                | 1         | 1.15%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 1.15%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 1.15%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 1.15%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                              | 1         | 1.15%   |
| Intel C600/X79 series chipset IDE-r Controller                                   | 1         | 1.15%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 1         | 1.15%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 1.15%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 42        | 55.26%  |
| IDE  | 21        | 27.63%  |
| NVMe | 9         | 11.84%  |
| RAID | 2         | 2.63%   |
| SAS  | 1         | 1.32%   |
| SCSI | 1         | 1.32%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 49        | 74.24%  |
| AMD    | 17        | 25.76%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Celeron CPU N2840 @ 2.16GHz           | 3         | 4.55%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 2         | 3.03%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz        | 2         | 3.03%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 2         | 3.03%   |
| Intel Atom CPU N280 @ 1.66GHz               | 2         | 3.03%   |
| Intel Atom CPU N270 @ 1.60GHz               | 2         | 3.03%   |
| Intel Xeon CPU E5-2687W 0 @ 3.10GHz         | 1         | 1.52%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz      | 1         | 1.52%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz | 1         | 1.52%   |
| Intel Pentium CPU B950 @ 2.10GHz            | 1         | 1.52%   |
| Intel Genuine CPU T2400 @ 1.83GHz           | 1         | 1.52%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1         | 1.52%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 1         | 1.52%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1         | 1.52%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 1         | 1.52%   |
| Intel Core i7-3612QM CPU @ 2.10GHz          | 1         | 1.52%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1         | 1.52%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1         | 1.52%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 1         | 1.52%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 1         | 1.52%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 1         | 1.52%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 1         | 1.52%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 1         | 1.52%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 1         | 1.52%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 1         | 1.52%   |
| Intel Core i5 CPU M 460 @ 2.53GHz           | 1         | 1.52%   |
| Intel Core i3-7100U CPU @ 2.40GHz           | 1         | 1.52%   |
| Intel Core i3-2130 CPU @ 3.40GHz            | 1         | 1.52%   |
| Intel Core i3 CPU M 380 @ 2.53GHz           | 1         | 1.52%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 1         | 1.52%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz        | 1         | 1.52%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 1         | 1.52%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz        | 1         | 1.52%   |
| Intel Core 2 CPU U7600 @ 1.20GHz            | 1         | 1.52%   |
| Intel Core 2 CPU T5600 @ 1.83GHz            | 1         | 1.52%   |
| Intel Core 2 CPU 6300 @ 1.86GHz             | 1         | 1.52%   |
| Intel Celeron N4020 CPU @ 1.10GHz           | 1         | 1.52%   |
| Intel Celeron CPU N3160 @ 1.60GHz           | 1         | 1.52%   |
| Intel Celeron CPU N3050 @ 1.60GHz           | 1         | 1.52%   |
| Intel Celeron CPU 900 @ 2.20GHz             | 1         | 1.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 11        | 16.67%  |
| Intel Celeron           | 7         | 10.61%  |
| Intel Atom              | 7         | 10.61%  |
| Intel Core i7           | 6         | 9.09%   |
| Intel Core 2 Duo        | 5         | 7.58%   |
| Intel Core i3           | 3         | 4.55%   |
| Intel Core 2            | 3         | 4.55%   |
| AMD Ryzen 7             | 2         | 3.03%   |
| AMD Ryzen 5             | 2         | 3.03%   |
| AMD A6                  | 2         | 3.03%   |
| Other                   | 1         | 1.52%   |
| Intel Xeon              | 1         | 1.52%   |
| Intel Pentium Gold      | 1         | 1.52%   |
| Intel Pentium Dual-Core | 1         | 1.52%   |
| Intel Pentium           | 1         | 1.52%   |
| Intel Genuine           | 1         | 1.52%   |
| Intel Core 2 Quad       | 1         | 1.52%   |
| AMD Turion 64 X2 Mobile | 1         | 1.52%   |
| AMD Sempron             | 1         | 1.52%   |
| AMD Ryzen 9             | 1         | 1.52%   |
| AMD Ryzen 3             | 1         | 1.52%   |
| AMD PRO A8              | 1         | 1.52%   |
| AMD PRO A10             | 1         | 1.52%   |
| AMD Phenom II X6        | 1         | 1.52%   |
| AMD C-50                | 1         | 1.52%   |
| AMD Athlon II X3        | 1         | 1.52%   |
| AMD Athlon II X2        | 1         | 1.52%   |
| AMD A4                  | 1         | 1.52%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 31        | 46.97%  |
| 4      | 21        | 31.82%  |
| 1      | 7         | 10.61%  |
| 6      | 3         | 4.55%   |
| 8      | 2         | 3.03%   |
| 12     | 1         | 1.52%   |
| 3      | 1         | 1.52%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 66        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 35        | 53.03%  |
| 2      | 31        | 46.97%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 61        | 92.42%  |
| 32-bit         | 5         | 7.58%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 11        | 16.67%  |
| 0x206a7    | 4         | 6.06%   |
| 0x6f2      | 3         | 4.55%   |
| 0x406c4    | 3         | 4.55%   |
| 0x306a9    | 3         | 4.55%   |
| 0x30678    | 3         | 4.55%   |
| 0x20655    | 3         | 4.55%   |
| 0x0600611a | 3         | 4.55%   |
| 0x406c3    | 2         | 3.03%   |
| 0x306c3    | 2         | 3.03%   |
| 0x106c2    | 2         | 3.03%   |
| 0x1067a    | 2         | 3.03%   |
| 0x10676    | 2         | 3.03%   |
| 0x08108109 | 2         | 3.03%   |
| 0xa0653    | 1         | 1.52%   |
| 0x806ec    | 1         | 1.52%   |
| 0x806ea    | 1         | 1.52%   |
| 0x806e9    | 1         | 1.52%   |
| 0x706a8    | 1         | 1.52%   |
| 0x6fd      | 1         | 1.52%   |
| 0x6fb      | 1         | 1.52%   |
| 0x506e3    | 1         | 1.52%   |
| 0x40651    | 1         | 1.52%   |
| 0x206d7    | 1         | 1.52%   |
| 0x106e5    | 1         | 1.52%   |
| 0x0a201016 | 1         | 1.52%   |
| 0x08701021 | 1         | 1.52%   |
| 0x08600106 | 1         | 1.52%   |
| 0x08001138 | 1         | 1.52%   |
| 0x0700010f | 1         | 1.52%   |
| 0x05000029 | 1         | 1.52%   |
| 0x03000027 | 1         | 1.52%   |
| 0x010000dc | 1         | 1.52%   |
| 0x010000db | 1         | 1.52%   |
| 0x010000c8 | 1         | 1.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Silvermont    | 8         | 12.12%  |
| SandyBridge   | 6         | 9.09%   |
| Core          | 6         | 9.09%   |
| Penryn        | 5         | 7.58%   |
| KabyLake      | 4         | 6.06%   |
| K10           | 4         | 6.06%   |
| Bonnell       | 4         | 6.06%   |
| Westmere      | 3         | 4.55%   |
| IvyBridge     | 3         | 4.55%   |
| Haswell       | 3         | 4.55%   |
| Excavator     | 3         | 4.55%   |
| Zen+          | 2         | 3.03%   |
| Zen 2         | 2         | 3.03%   |
| Skylake       | 2         | 3.03%   |
| Zen 3         | 1         | 1.52%   |
| Zen           | 1         | 1.52%   |
| TigerLake     | 1         | 1.52%   |
| P6            | 1         | 1.52%   |
| Nehalem       | 1         | 1.52%   |
| K8 Hammer     | 1         | 1.52%   |
| K10 Llano     | 1         | 1.52%   |
| Jaguar        | 1         | 1.52%   |
| Goldmont plus | 1         | 1.52%   |
| CometLake     | 1         | 1.52%   |
| Bobcat        | 1         | 1.52%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Intel            | 36        | 52.94%  |
| AMD              | 17        | 25%     |
| Nvidia           | 14        | 20.59%  |
| VIA Technologies | 1         | 1.47%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 5         | 6.58%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 6.58%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 3         | 3.95%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 3.95%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3         | 3.95%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 3         | 3.95%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 2.63%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 2.63%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 2.63%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 2.63%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 2.63%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 2         | 2.63%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 1         | 1.32%   |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 1.32%   |
| Nvidia GT200GL [Quadro FX 3800]                                                          | 1         | 1.32%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1         | 1.32%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 1.32%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1         | 1.32%   |
| Nvidia GK104GLM [Quadro K3000M]                                                          | 1         | 1.32%   |
| Nvidia GK104 [GeForce GTX 760]                                                           | 1         | 1.32%   |
| Nvidia GF108M [GeForce GT 420M]                                                          | 1         | 1.32%   |
| Nvidia GA106 [Geforce RTX 3050]                                                          | 1         | 1.32%   |
| Nvidia G96CM [GeForce 9650M GT]                                                          | 1         | 1.32%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 1.32%   |
| Nvidia G96CGL [Quadro FX 580]                                                            | 1         | 1.32%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 1         | 1.32%   |
| Nvidia C51 [GeForce Go 6150]                                                             | 1         | 1.32%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1         | 1.32%   |
| Intel UHD Graphics 620                                                                   | 1         | 1.32%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 1         | 1.32%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 1.32%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.32%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.32%   |
| Intel HD Graphics 620                                                                    | 1         | 1.32%   |
| Intel HD Graphics 530                                                                    | 1         | 1.32%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 1.32%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 1.32%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 1.32%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1         | 1.32%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                                | 1         | 1.32%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 35        | 53.03%  |
| 1 x AMD        | 15        | 22.73%  |
| 1 x Nvidia     | 13        | 19.7%   |
| 2 x AMD        | 1         | 1.52%   |
| 1 x VIA        | 1         | 1.52%   |
| Intel + Nvidia | 1         | 1.52%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 59        | 89.39%  |
| Unknown     | 4         | 6.06%   |
| Proprietary | 3         | 4.55%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 43        | 64.18%  |
| 0.01-0.5   | 10        | 14.93%  |
| 0.51-1.0   | 6         | 8.96%   |
| 1.01-2.0   | 5         | 7.46%   |
| 7.01-8.0   | 2         | 2.99%   |
| 3.01-4.0   | 1         | 1.49%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 9         | 14.29%  |
| LG Display          | 8         | 12.7%   |
| AU Optronics        | 6         | 9.52%   |
| Goldstar            | 5         | 7.94%   |
| BOE                 | 5         | 7.94%   |
| Chimei Innolux      | 4         | 6.35%   |
| Dell                | 3         | 4.76%   |
| CPT                 | 3         | 4.76%   |
| Lenovo              | 2         | 3.17%   |
| BenQ                | 2         | 3.17%   |
| AOC                 | 2         | 3.17%   |
| Acer                | 2         | 3.17%   |
| Unknown             | 1         | 1.59%   |
| Toshiba             | 1         | 1.59%   |
| Sony                | 1         | 1.59%   |
| RTK                 | 1         | 1.59%   |
| PANDA               | 1         | 1.59%   |
| Medion              | 1         | 1.59%   |
| LG Philips          | 1         | 1.59%   |
| JCH                 | 1         | 1.59%   |
| Insignia            | 1         | 1.59%   |
| Hitachi             | 1         | 1.59%   |
| HannStar            | 1         | 1.59%   |
| Apple               | 1         | 1.59%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 1         | 1.49%   |
| Toshiba TV TSB0206 1920x1080 1600x1000mm 74.3-inch                    | 1         | 1.49%   |
| Sony TV SNY2A03 1920x1080                                             | 1         | 1.49%   |
| Samsung Electronics SyncMaster SAM0581 1920x1080 477x268mm 21.5-inch  | 1         | 1.49%   |
| Samsung Electronics SyncMaster SAM0116 1024x768 267x200mm 13.1-inch   | 1         | 1.49%   |
| Samsung Electronics SMB1630N SAM0630 1360x768 344x194mm 15.5-inch     | 1         | 1.49%   |
| Samsung Electronics SA300/SA350 SAM078F 1920x1080 477x268mm 21.5-inch | 1         | 1.49%   |
| Samsung Electronics S24D330 SAM0D93 1920x1080 531x299mm 24.0-inch     | 1         | 1.49%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch     | 1         | 1.49%   |
| Samsung Electronics S22C450 SAM09C5 1920x1080 477x268mm 21.5-inch     | 1         | 1.49%   |
| Samsung Electronics LCD Monitor SEC4F45 1280x800 331x207mm 15.4-inch  | 1         | 1.49%   |
| Samsung Electronics LCD Monitor SEC4141 1366x768 344x193mm 15.5-inch  | 1         | 1.49%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1         | 1.49%   |
| RTK CPL AIO PC RTK2482 1920x1080 509x286mm 23.0-inch                  | 1         | 1.49%   |
| PANDA LCD Monitor NCP0063 1920x1080 344x194mm 15.5-inch               | 1         | 1.49%   |
| Medion MD 20310 MED3645 1920x1080 521x293mm 23.5-inch                 | 1         | 1.49%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch           | 1         | 1.49%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch         | 1         | 1.49%   |
| LG Display LCD Monitor LGD059E 1920x1080 382x215mm 17.3-inch          | 1         | 1.49%   |
| LG Display LCD Monitor LGD04E1 1366x768 344x194mm 15.5-inch           | 1         | 1.49%   |
| LG Display LCD Monitor LGD03F8 1366x768 345x194mm 15.6-inch           | 1         | 1.49%   |
| LG Display LCD Monitor LGD02E1 1600x900 382x215mm 17.3-inch           | 1         | 1.49%   |
| LG Display LCD Monitor LGD0266 1366x768 344x194mm 15.5-inch           | 1         | 1.49%   |
| LG Display LCD Monitor LGD0212 1366x768 309x174mm 14.0-inch           | 1         | 1.49%   |
| LG Display LCD Monitor LGD01C5 1366x768 293x165mm 13.2-inch           | 1         | 1.49%   |
| Lenovo LCD Monitor LEN4033 1440x900 304x190mm 14.1-inch               | 1         | 1.49%   |
| Lenovo LCD Monitor LEN4022 1400x1050 286x214mm 14.1-inch              | 1         | 1.49%   |
| JCH F24 JCH1919 1920x1080 520x310mm 23.8-inch                         | 1         | 1.49%   |
| Insignia BBY LCD BBY0032 1920x540                                     | 1         | 1.49%   |
| Hitachi HDMI HEC0088 1920x540                                         | 1         | 1.49%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch             | 1         | 1.49%   |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                   | 1         | 1.49%   |
| Goldstar W2042 GSM4E7E 1680x1050 434x270mm 20.1-inch                  | 1         | 1.49%   |
| Goldstar TV GSM9CF6 1360x768 708x398mm 32.0-inch                      | 1         | 1.49%   |
| Goldstar T710SH GSM436B 1280x960 310x230mm 15.2-inch                  | 1         | 1.49%   |
| Goldstar L1953H GSM4B3D 1280x1024 338x270mm 17.0-inch                 | 1         | 1.49%   |
| Goldstar L1953H GSM4B3C 1280x1024 338x270mm 17.0-inch                 | 1         | 1.49%   |
| Goldstar 23MP55 GSM5A23 1920x1080 510x290mm 23.1-inch                 | 1         | 1.49%   |
| Dell LCD Monitor S2715H 3840x1080                                     | 1         | 1.49%   |
| Dell LCD Monitor S2715H                                               | 1         | 1.49%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 26        | 39.39%  |
| 1366x768 (WXGA)    | 14        | 21.21%  |
| 1600x900 (HD+)     | 4         | 6.06%   |
| 1280x1024 (SXGA)   | 3         | 4.55%   |
| 1024x600           | 3         | 4.55%   |
| 1920x540           | 2         | 3.03%   |
| 1680x1050 (WSXGA+) | 2         | 3.03%   |
| 1440x900 (WXGA+)   | 2         | 3.03%   |
| 1280x800 (WXGA)    | 2         | 3.03%   |
| 3840x1080          | 1         | 1.52%   |
| 2288x1287          | 1         | 1.52%   |
| 1920x1200 (WUXGA)  | 1         | 1.52%   |
| 1400x1050          | 1         | 1.52%   |
| 1360x768           | 1         | 1.52%   |
| 1280x960           | 1         | 1.52%   |
| 1024x768 (XGA)     | 1         | 1.52%   |
| Unknown            | 1         | 1.52%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 11        | 16.92%  |
| 17      | 9         | 13.85%  |
| 13      | 9         | 13.85%  |
| 23      | 7         | 10.77%  |
| 14      | 5         | 7.69%   |
| 21      | 3         | 4.62%   |
| 20      | 3         | 4.62%   |
| 10      | 3         | 4.62%   |
| 72      | 2         | 3.08%   |
| 48      | 2         | 3.08%   |
| 24      | 2         | 3.08%   |
| 18      | 2         | 3.08%   |
| 16      | 2         | 3.08%   |
| 142     | 1         | 1.54%   |
| 74      | 1         | 1.54%   |
| 27      | 1         | 1.54%   |
| 12      | 1         | 1.54%   |
| Unknown | 1         | 1.54%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 23        | 35.38%  |
| 501-600        | 10        | 15.38%  |
| 201-300        | 10        | 15.38%  |
| 401-500        | 8         | 12.31%  |
| 351-400        | 7         | 10.77%  |
| 1501-2000      | 3         | 4.62%   |
| 1001-1500      | 2         | 3.08%   |
| More than 2000 | 1         | 1.54%   |
| Unknown        | 1         | 1.54%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 46        | 71.88%  |
| 16/10   | 8         | 12.5%   |
| 5/4     | 3         | 4.69%   |
| 4/3     | 3         | 4.69%   |
| 1.96    | 2         | 3.13%   |
| 1.00    | 1         | 1.56%   |
| Unknown | 1         | 1.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 12        | 18.46%  |
| 201-250        | 10        | 15.38%  |
| 81-90          | 9         | 13.85%  |
| 121-130        | 6         | 9.23%   |
| 151-200        | 5         | 7.69%   |
| 141-150        | 5         | 7.69%   |
| More than 1000 | 4         | 6.15%   |
| 71-80          | 4         | 6.15%   |
| 41-50          | 3         | 4.62%   |
| 501-1000       | 2         | 3.08%   |
| 61-70          | 1         | 1.54%   |
| 301-350        | 1         | 1.54%   |
| 131-140        | 1         | 1.54%   |
| 91-100         | 1         | 1.54%   |
| Unknown        | 1         | 1.54%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 21        | 33.33%  |
| 101-120 | 20        | 31.75%  |
| 121-160 | 14        | 22.22%  |
| 1-50    | 6         | 9.52%   |
| 161-240 | 1         | 1.59%   |
| Unknown | 1         | 1.59%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 58        | 87.88%  |
| 2     | 5         | 7.58%   |
| 0     | 3         | 4.55%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 30        | 31.91%  |
| Intel                    | 26        | 27.66%  |
| Qualcomm Atheros         | 12        | 12.77%  |
| Broadcom                 | 5         | 5.32%   |
| Broadcom Limited         | 4         | 4.26%   |
| Ralink Technology        | 3         | 3.19%   |
| Nvidia                   | 3         | 3.19%   |
| Marvell Technology Group | 3         | 3.19%   |
| TP-Link                  | 2         | 2.13%   |
| VIA Technologies         | 1         | 1.06%   |
| Samsung Electronics      | 1         | 1.06%   |
| Ralink                   | 1         | 1.06%   |
| OPPO Electronics         | 1         | 1.06%   |
| Edimax Technology        | 1         | 1.06%   |
| D-Link System            | 1         | 1.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 19        | 17.27%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 6         | 5.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 3         | 2.73%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 2         | 1.82%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 2         | 1.82%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 2         | 1.82%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 2         | 1.82%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 2         | 1.82%   |
| Nvidia MCP61 Ethernet                                                         | 2         | 1.82%   |
| Intel Wireless 8260                                                           | 2         | 1.82%   |
| Intel Wireless 7265                                                           | 2         | 1.82%   |
| Intel Wireless 7260                                                           | 2         | 1.82%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 2         | 1.82%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                              | 2         | 1.82%   |
| VIA VT6102/VT6103 [Rhine-II]                                                  | 1         | 0.91%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                           | 1         | 0.91%   |
| TP-Link 802.11ac WLAN Adapter                                                 | 1         | 0.91%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 1         | 0.91%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 1         | 0.91%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.91%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 1         | 0.91%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 1         | 0.91%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                              | 1         | 0.91%   |
| Ralink RT5370 Wireless Adapter                                                | 1         | 0.91%   |
| Ralink RT3072 Wireless Adapter                                                | 1         | 0.91%   |
| Ralink MT7601U Wireless Adapter                                               | 1         | 0.91%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                     | 1         | 0.91%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 1         | 0.91%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 1         | 0.91%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1         | 0.91%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1         | 0.91%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1         | 0.91%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 1         | 0.91%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 1         | 0.91%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                         | 1         | 0.91%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 0.91%   |
| OPPO SM6375-QRD _SN:F4A23F05                                                  | 1         | 0.91%   |
| Nvidia MCP51 Ethernet Controller                                              | 1         | 0.91%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                       | 1         | 0.91%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                       | 1         | 0.91%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 21        | 42%     |
| Qualcomm Atheros      | 10        | 20%     |
| Realtek Semiconductor | 8         | 16%     |
| Ralink Technology     | 3         | 6%      |
| TP-Link               | 2         | 4%      |
| Broadcom Limited      | 2         | 4%      |
| Ralink                | 1         | 2%      |
| Edimax Technology     | 1         | 2%      |
| D-Link System         | 1         | 2%      |
| Broadcom              | 1         | 2%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                       | Computers | Percent |
|---------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                    | 2         | 4%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                    | 2         | 4%      |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                              | 2         | 4%      |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                     | 2         | 4%      |
| Intel Wireless 8260                                                                         | 2         | 4%      |
| Intel Wireless 7265                                                                         | 2         | 4%      |
| Intel Wireless 7260                                                                         | 2         | 4%      |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                       | 2         | 4%      |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                         | 1         | 2%      |
| TP-Link 802.11ac WLAN Adapter                                                               | 1         | 2%      |
| Realtek RTL88x2bu [AC1200 Techkey]                                                          | 1         | 2%      |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                    | 1         | 2%      |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                             | 1         | 2%      |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                         | 1         | 2%      |
| Ralink RT5370 Wireless Adapter                                                              | 1         | 2%      |
| Ralink RT3072 Wireless Adapter                                                              | 1         | 2%      |
| Ralink MT7601U Wireless Adapter                                                             | 1         | 2%      |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                   | 1         | 2%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                  | 1         | 2%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                  | 1         | 2%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                            | 1         | 2%      |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                              | 1         | 2%      |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                              | 1         | 2%      |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]               | 1         | 2%      |
| Intel Wireless 3165                                                                         | 1         | 2%      |
| Intel WiFi Link 5100                                                                        | 1         | 2%      |
| Intel Wi-Fi 6 AX201                                                                         | 1         | 2%      |
| Intel Wi-Fi 6 AX200                                                                         | 1         | 2%      |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                                     | 1         | 2%      |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                               | 1         | 2%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                            | 1         | 2%      |
| Intel Comet Lake PCH-LP CNVi WiFi                                                           | 1         | 2%      |
| Intel Centrino Wireless-N 2230                                                              | 1         | 2%      |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                                | 1         | 2%      |
| Intel Centrino Ultimate-N 6300                                                              | 1         | 2%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                | 1         | 2%      |
| Intel Centrino Advanced-N 6200                                                              | 1         | 2%      |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                              | 1         | 2%      |
| D-Link System DWA-160 802.11abgn Xtreme N Dual Band Adapter(rev.A2) [Atheros AR9170+AR9104] | 1         | 2%      |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter                                 | 1         | 2%      |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 26        | 43.33%  |
| Intel                    | 14        | 23.33%  |
| Qualcomm Atheros         | 5         | 8.33%   |
| Broadcom                 | 4         | 6.67%   |
| Nvidia                   | 3         | 5%      |
| Marvell Technology Group | 3         | 5%      |
| Broadcom Limited         | 2         | 3.33%   |
| VIA Technologies         | 1         | 1.67%   |
| Samsung Electronics      | 1         | 1.67%   |
| OPPO Electronics         | 1         | 1.67%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 19        | 31.67%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 10%     |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 5%      |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 3.33%   |
| Nvidia MCP61 Ethernet                                             | 2         | 3.33%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 2         | 3.33%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 1.67%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.67%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 1.67%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.67%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 1.67%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.67%   |
| OPPO SM6375-QRD _SN:F4A23F05                                      | 1         | 1.67%   |
| Nvidia MCP51 Ethernet Controller                                  | 1         | 1.67%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 1.67%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 1.67%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 1.67%   |
| Intel I211 Gigabit Network Connection                             | 1         | 1.67%   |
| Intel Ethernet Controller I225-V                                  | 1         | 1.67%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.67%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.67%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.67%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 1.67%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.67%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 1.67%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 1.67%   |
| Intel 82566DM Gigabit Network Connection                          | 1         | 1.67%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 1         | 1.67%   |
| Broadcom NetXtreme BCM5721 Gigabit Ethernet PCI Express           | 1         | 1.67%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.67%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1         | 1.67%   |
| Broadcom Limited NetLink BCM57788 Gigabit Ethernet PCIe           | 1         | 1.67%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 58        | 55.24%  |
| WiFi     | 47        | 44.76%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 36        | 50.7%   |
| Ethernet | 35        | 49.3%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 34        | 51.52%  |
| 1     | 29        | 43.94%  |
| 0     | 2         | 3.03%   |
| 3     | 1         | 1.52%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 54        | 79.41%  |
| Yes  | 14        | 20.59%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 12        | 36.36%  |
| Broadcom                        | 4         | 12.12%  |
| IMC Networks                    | 3         | 9.09%   |
| Realtek Semiconductor           | 2         | 6.06%   |
| Qualcomm Atheros Communications | 2         | 6.06%   |
| Cambridge Silicon Radio         | 2         | 6.06%   |
| Taiyo Yuden                     | 1         | 3.03%   |
| Realtek                         | 1         | 3.03%   |
| Hewlett-Packard                 | 1         | 3.03%   |
| Foxconn / Hon Hai               | 1         | 3.03%   |
| Dynex                           | 1         | 3.03%   |
| Dell                            | 1         | 3.03%   |
| ASUSTek Computer                | 1         | 3.03%   |
| Apple                           | 1         | 3.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                       | 7         | 21.21%  |
| IMC Networks Bluetooth Radio                             | 3         | 9.09%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 2         | 6.06%   |
| Taiyo Yuden Bluetooth Device (V2.0+EDR)                  | 1         | 3.03%   |
| Realtek RTL8723B Bluetooth                               | 1         | 3.03%   |
| Realtek  Bluetooth 4.2 Adapter                           | 1         | 3.03%   |
| Realtek 802.11ac WLAN Adapter                            | 1         | 3.03%   |
| Qualcomm Atheros  Bluetooth Device                       | 1         | 3.03%   |
| Qualcomm Atheros Bluetooth                               | 1         | 3.03%   |
| Intel Wireless-AC 3168 Bluetooth                         | 1         | 3.03%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 1         | 3.03%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 1         | 3.03%   |
| Intel AX201 Bluetooth                                    | 1         | 3.03%   |
| Intel AX200 Bluetooth                                    | 1         | 3.03%   |
| HP Broadcom 2070 Bluetooth Combo                         | 1         | 3.03%   |
| Foxconn / Hon Hai Bluetooth Device                       | 1         | 3.03%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 1         | 3.03%   |
| Dell Wireless 365 Bluetooth                              | 1         | 3.03%   |
| Broadcom HP Portable SoftSailing                         | 1         | 3.03%   |
| Broadcom BCM43142A0 Bluetooth Device                     | 1         | 3.03%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]         | 1         | 3.03%   |
| Broadcom BCM2045 Bluetooth                               | 1         | 3.03%   |
| ASUS Broadcom Bluetooth 2.1                              | 1         | 3.03%   |
| Apple Bluetooth HCI                                      | 1         | 3.03%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 44        | 54.32%  |
| AMD                 | 18        | 22.22%  |
| Nvidia              | 11        | 13.58%  |
| C-Media Electronics | 2         | 2.47%   |
| VIA Technologies    | 1         | 1.23%   |
| Plantronics         | 1         | 1.23%   |
| Native Instruments  | 1         | 1.23%   |
| Focusrite-Novation  | 1         | 1.23%   |
| Creative Labs       | 1         | 1.23%   |
| ASUSTek Computer    | 1         | 1.23%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 8         | 8.51%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 6         | 6.38%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 4.26%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 4.26%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 4.26%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 3         | 3.19%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 3.19%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 3.19%   |
| AMD FCH Azalia Controller                                                                         | 3         | 3.19%   |
| Nvidia MCP61 High Definition Audio                                                                | 2         | 2.13%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 2.13%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 2         | 2.13%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 2.13%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 2         | 2.13%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 2.13%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 2         | 2.13%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 2         | 2.13%   |
| AMD Navi 10 HDMI Audio                                                                            | 2         | 2.13%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 2         | 2.13%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 2.13%   |
| AMD Barts HDMI Audio [Radeon HD 6790/6850/6870 / 7720 OEM]                                        | 2         | 2.13%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1         | 1.06%   |
| Plantronics USB DSP v4 Audio Interface                                                            | 1         | 1.06%   |
| Nvidia MCP51 High Definition Audio                                                                | 1         | 1.06%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 1.06%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 1.06%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 1.06%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 1.06%   |
| Native Instruments KOMPLETE KONTROL M32                                                           | 1         | 1.06%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 1.06%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 1.06%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 1.06%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 1         | 1.06%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 1.06%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 1.06%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 1         | 1.06%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 1.06%   |
| Intel 200 Series PCH HD Audio                                                                     | 1         | 1.06%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 1.06%   |
| Focusrite-Novation Focusrite Scarlett 2i2 2nd Gen                                                 | 1         | 1.06%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 13        | 24.53%  |
| Unknown             | 12        | 22.64%  |
| Kingston            | 6         | 11.32%  |
| SK hynix            | 5         | 9.43%   |
| Micron Technology   | 4         | 7.55%   |
| Corsair             | 3         | 5.66%   |
| Nanya Technology    | 2         | 3.77%   |
| G.Skill             | 2         | 3.77%   |
| Crucial             | 2         | 3.77%   |
| High Bridge         | 1         | 1.89%   |
| GOODRAM             | 1         | 1.89%   |
| Elpida              | 1         | 1.89%   |
| Avant               | 1         | 1.89%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                | 2         | 3.39%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                     | 2         | 3.39%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s      | 2         | 3.39%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                       | 1         | 1.69%   |
| Unknown RAM Module 2GB SODIMM SDRAM                        | 1         | 1.69%   |
| Unknown RAM Module 2GB SODIMM DDR2 266MT/s                 | 1         | 1.69%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                  | 1         | 1.69%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                   | 1         | 1.69%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                | 1         | 1.69%   |
| Unknown RAM Module 1024MB SODIMM DDR2                      | 1         | 1.69%   |
| Unknown RAM Module 1024MB SODIMM 800MT/s                   | 1         | 1.69%   |
| Unknown RAM Module 1024MB DIMM SDRAM                       | 1         | 1.69%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1066MT/s               | 1         | 1.69%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s     | 1         | 1.69%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s     | 1         | 1.69%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s     | 1         | 1.69%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s    | 1         | 1.69%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s     | 1         | 1.69%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                | 1         | 1.69%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM 1600MT/s           | 1         | 1.69%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s   | 1         | 1.69%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s      | 1         | 1.69%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s      | 1         | 1.69%   |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1334MT/s      | 1         | 1.69%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s      | 1         | 1.69%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s      | 1         | 1.69%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s      | 1         | 1.69%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s      | 1         | 1.69%   |
| Samsung RAM M3 78T5663EH3-CF7 2GB DIMM DDR2 800MT/s        | 1         | 1.69%   |
| Samsung RAM M3 78T2863RZS-CE6 1GB DIMM DDR2 667MT/s        | 1         | 1.69%   |
| Samsung RAM M3 78T2863QZS-CE6 1GB DIMM DDR2 1639MT/s       | 1         | 1.69%   |
| Samsung RAM K4E8E324EB-EGCF 2GB LPDDR3 1867MT/s            | 1         | 1.69%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s       | 1         | 1.69%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s       | 1         | 1.69%   |
| Micron RAM 8ATF1G64HZ-2G6H1 8GB SODIMM DDR4 2667MT/s       | 1         | 1.69%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s | 1         | 1.69%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s      | 1         | 1.69%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s     | 1         | 1.69%   |
| Kingston RAM Module 8GB DIMM DDR3 1600MT/s                 | 1         | 1.69%   |
| Kingston RAM Module 4GB SODIMM DDR3 800MT/s                | 1         | 1.69%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 25        | 51.02%  |
| DDR4    | 11        | 22.45%  |
| SDRAM   | 4         | 8.16%   |
| DDR2    | 4         | 8.16%   |
| Unknown | 4         | 8.16%   |
| LPDDR3  | 1         | 2.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 31        | 65.96%  |
| DIMM         | 14        | 29.79%  |
| Row Of Chips | 1         | 2.13%   |
| Unknown      | 1         | 2.13%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 2048  | 17        | 30.36%  |
| 8192  | 16        | 28.57%  |
| 4096  | 14        | 25%     |
| 1024  | 5         | 8.93%   |
| 16384 | 4         | 7.14%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 14        | 25.93%  |
| 1333    | 7         | 12.96%  |
| 2667    | 5         | 9.26%   |
| 800     | 5         | 9.26%   |
| 3200    | 3         | 5.56%   |
| 1334    | 3         | 5.56%   |
| 1066    | 3         | 5.56%   |
| Unknown | 3         | 5.56%   |
| 4199    | 1         | 1.85%   |
| 3666    | 1         | 1.85%   |
| 2666    | 1         | 1.85%   |
| 2400    | 1         | 1.85%   |
| 2133    | 1         | 1.85%   |
| 2048    | 1         | 1.85%   |
| 1867    | 1         | 1.85%   |
| 1800    | 1         | 1.85%   |
| 1639    | 1         | 1.85%   |
| 667     | 1         | 1.85%   |
| 266     | 1         | 1.85%   |

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
| Chicony Electronics                    | 10        | 25.64%  |
| Microdia                               | 5         | 12.82%  |
| Suyin                                  | 3         | 7.69%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 7.69%   |
| Bison Electronics                      | 3         | 7.69%   |
| Alcor Micro                            | 3         | 7.69%   |
| Sunplus Innovation Technology          | 2         | 5.13%   |
| Logitech                               | 2         | 5.13%   |
| Z-Star Microelectronics                | 1         | 2.56%   |
| Sonix Technology                       | 1         | 2.56%   |
| Samsung Electronics                    | 1         | 2.56%   |
| Quanta                                 | 1         | 2.56%   |
| Microsoft                              | 1         | 2.56%   |
| Guillemot                              | 1         | 2.56%   |
| Acer                                   | 1         | 2.56%   |
| Unknown                                | 1         | 2.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Alcor Micro USB 2.0 Camera                                      | 3         | 7.69%   |
| Chicony HD WebCam                                               | 2         | 5.13%   |
| Z-Star Namuga 1.3M Webcam                                       | 1         | 2.56%   |
| Suyin USB2.0 UVC 1.3M WebCam                                    | 1         | 2.56%   |
| Suyin HP Truevision HD                                          | 1         | 2.56%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)     | 1         | 2.56%   |
| Sunplus Integrated Webcam                                       | 1         | 2.56%   |
| Sunplus HP HD Webcam [Fixed]                                    | 1         | 2.56%   |
| Sonix USB2.0 HD UVC WebCam                                      | 1         | 2.56%   |
| Samsung Galaxy series, misc. (MTP mode)                         | 1         | 2.56%   |
| Quanta HD User Facing                                           | 1         | 2.56%   |
| Microsoft LifeCam Cinema                                        | 1         | 2.56%   |
| Microdia Sonix USB 2.0 Camera                                   | 1         | 2.56%   |
| Microdia Lenovo EasyCamera                                      | 1         | 2.56%   |
| Microdia Laptop_Integrated_Webcam_HD                            | 1         | 2.56%   |
| Microdia Laptop_Integrated_Webcam_1.3M                          | 1         | 2.56%   |
| Microdia ASUS USB2.0 Camera                                     | 1         | 2.56%   |
| Logitech Webcam C270                                            | 1         | 2.56%   |
| Logitech QuickCam Notebook Pro                                  | 1         | 2.56%   |
| Guillemot Hercules Dualpix Exchange                             | 1         | 2.56%   |
| Chicony TOSHIBA Web Camera - HD                                 | 1         | 2.56%   |
| Chicony Integrated Camera (1280x720@30)                         | 1         | 2.56%   |
| Chicony HP Webcam [2 MP Macro]                                  | 1         | 2.56%   |
| Chicony HP TrueVision HD Camera                                 | 1         | 2.56%   |
| Chicony HP Integrated Webcam                                    | 1         | 2.56%   |
| Chicony HP HD Webcam                                            | 1         | 2.56%   |
| Chicony Asus Integrated 0.3M UVC Webcam                         | 1         | 2.56%   |
| Chicony 2.0M UVC Webcam / CNF7129                               | 1         | 2.56%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 1         | 2.56%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera             | 1         | 2.56%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera                | 1         | 2.56%   |
| Bison USB HD Webcam                                             | 1         | 2.56%   |
| Bison HP Webcam                                                 | 1         | 2.56%   |
| Bison HD Webcam                                                 | 1         | 2.56%   |
| Acer Lenovo EasyCamera                                          | 1         | 2.56%   |
| Unknown                                                         | 1         | 2.56%   |

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
| 0     | 45        | 68.18%  |
| 1     | 17        | 25.76%  |
| 2     | 4         | 6.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 8         | 29.63%  |
| Fingerprint reader    | 7         | 25.93%  |
| Net/wireless          | 6         | 22.22%  |
| Multimedia controller | 4         | 14.81%  |
| Chipcard              | 1         | 3.7%    |
| Camera                | 1         | 3.7%    |

