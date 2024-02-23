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

Total: 114

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Google        | Kefka                       | Notebook    | [810d5a47f7](https://linux-hardware.org/?probe=810d5a47f7) | Jan 27, 2024 |
| HP            | 212B                        | Desktop     | [cb5e65ba08](https://linux-hardware.org/?probe=cb5e65ba08) | Jan 21, 2024 |
| Lenovo        | ThinkPad T430 2349FC4       | Notebook    | [655eb2734a](https://linux-hardware.org/?probe=655eb2734a) | Jan 11, 2024 |
| Lenovo        | ThinkPad T430 2349FC4       | Notebook    | [ea07a49b87](https://linux-hardware.org/?probe=ea07a49b87) | Jan 07, 2024 |
| Acer          | Aspire X3950                | Desktop     | [09dfa7ff4b](https://linux-hardware.org/?probe=09dfa7ff4b) | Jan 04, 2024 |
| Lenovo        | ThinkPad T430 2349FC4       | Notebook    | [689d3295aa](https://linux-hardware.org/?probe=689d3295aa) | Dec 30, 2023 |
| Acer          | Aspire SW5-012              | Notebook    | [4efea61fa3](https://linux-hardware.org/?probe=4efea61fa3) | Dec 29, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [6e6573e5fe](https://linux-hardware.org/?probe=6e6573e5fe) | Dec 29, 2023 |
| Acer          | FIH57                       | Desktop     | [0edb232edf](https://linux-hardware.org/?probe=0edb232edf) | Dec 16, 2023 |
| HP            | 0A80h                       | Desktop     | [5e6a479e17](https://linux-hardware.org/?probe=5e6a479e17) | Dec 01, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [80d1578d90](https://linux-hardware.org/?probe=80d1578d90) | Oct 30, 2023 |
| ASUSTek       | P7H55-M                     | Desktop     | [ad3f143871](https://linux-hardware.org/?probe=ad3f143871) | Oct 20, 2023 |
| Medion        | E15415                      | Notebook    | [b9a4ecdc97](https://linux-hardware.org/?probe=b9a4ecdc97) | Oct 14, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [2fc3f16671](https://linux-hardware.org/?probe=2fc3f16671) | Sep 30, 2023 |
| HP            | Pavilion g6                 | Notebook    | [158b6f4df9](https://linux-hardware.org/?probe=158b6f4df9) | Sep 17, 2023 |
| Intel         | NUC8BEB J72692-306          | Mini pc     | [6cbfa96139](https://linux-hardware.org/?probe=6cbfa96139) | Sep 07, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [b0dbfa8a76](https://linux-hardware.org/?probe=b0dbfa8a76) | Aug 26, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [da3f894af1](https://linux-hardware.org/?probe=da3f894af1) | Aug 26, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [4006007a76](https://linux-hardware.org/?probe=4006007a76) | Aug 20, 2023 |
| Intel         | NUC8BEB J72692-306          | Mini pc     | [6a155984af](https://linux-hardware.org/?probe=6a155984af) | Aug 19, 2023 |
| Dell          | 0YXT71 A01                  | Desktop     | [aa6781c002](https://linux-hardware.org/?probe=aa6781c002) | Aug 18, 2023 |
| Acer          | Aspire 5920                 | Notebook    | [31447ef238](https://linux-hardware.org/?probe=31447ef238) | Aug 17, 2023 |
| Acer          | Aspire 5920                 | Notebook    | [8c57c50f82](https://linux-hardware.org/?probe=8c57c50f82) | Aug 17, 2023 |
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
| Sparky 6    | 16        | 17.98%  |
| Sparky 7    | 12        | 13.48%  |
| Sparky 8    | 8         | 8.99%   |
| Sparky 6.1  | 6         | 6.74%   |
| Sparky 7.1  | 5         | 5.62%   |
| Sparky 6.5  | 5         | 5.62%   |
| Sparky 5.12 | 5         | 5.62%   |
| Sparky 7.0  | 4         | 4.49%   |
| Sparky 6.7  | 4         | 4.49%   |
| Sparky 6.6  | 4         | 4.49%   |
| Sparky 6.3  | 4         | 4.49%   |
| Sparky 7.2  | 3         | 3.37%   |
| Sparky 6.0  | 3         | 3.37%   |
| Sparky 5.14 | 3         | 3.37%   |
| Sparky 5.10 | 3         | 3.37%   |
| Sparky 6.2  | 2         | 2.25%   |
| Sparky 5.13 | 2         | 2.25%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Sparky | 83        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Computers | Percent |
|---------------------------|-----------|---------|
| 5.10.0-21-amd64           | 4         | 4.21%   |
| 5.10.0-11-686             | 4         | 4.21%   |
| 6.1.0-17-amd64            | 3         | 3.16%   |
| 6.1.0-13-amd64            | 3         | 3.16%   |
| 5.10.0-9-amd64            | 3         | 3.16%   |
| 5.10.0-8-amd64            | 3         | 3.16%   |
| 5.10.0-6-amd64            | 3         | 3.16%   |
| 4.19.0-8-amd64            | 3         | 3.16%   |
| 4.19.0-12-amd64           | 3         | 3.16%   |
| 6.5.0-5-amd64             | 2         | 2.11%   |
| 6.4.0-2-amd64             | 2         | 2.11%   |
| 6.3.0-1-amd64             | 2         | 2.11%   |
| 6.1.0-12-amd64            | 2         | 2.11%   |
| 5.18.0-4-amd64            | 2         | 2.11%   |
| 5.18.0-2-amd64            | 2         | 2.11%   |
| 5.17.0-1-amd64            | 2         | 2.11%   |
| 5.10.0-3-amd64            | 2         | 2.11%   |
| 5.10.0-23-amd64           | 2         | 2.11%   |
| 5.10.0-14-amd64           | 2         | 2.11%   |
| 4.19.0-13-686             | 2         | 2.11%   |
| 4.19.0-10-686             | 2         | 2.11%   |
| 6.5.9-x64v3-xanmod1       | 1         | 1.05%   |
| 6.4.4-sparky8-amd64       | 1         | 1.05%   |
| 6.4.12-x64v3-xanmod1      | 1         | 1.05%   |
| 6.4.0-3-amd64             | 1         | 1.05%   |
| 6.4.0-1-amd64             | 1         | 1.05%   |
| 6.3.3-1-liquorix-amd64    | 1         | 1.05%   |
| 6.2.0-sparky-amd64        | 1         | 1.05%   |
| 6.1.0-9-amd64             | 1         | 1.05%   |
| 6.1.0-7-amd64             | 1         | 1.05%   |
| 6.1.0-3-amd64             | 1         | 1.05%   |
| 6.1.0-16-amd64            | 1         | 1.05%   |
| 6.1.0-11-amd64            | 1         | 1.05%   |
| 6.1.0-10-amd64            | 1         | 1.05%   |
| 6.0.11-x64v2-rt14-xanmod1 | 1         | 1.05%   |
| 6.0.0-5-amd64             | 1         | 1.05%   |
| 5.9.13-sparky-amd64       | 1         | 1.05%   |
| 5.9.0-4-amd64             | 1         | 1.05%   |
| 5.8.13-sparky-amd64       | 1         | 1.05%   |
| 5.8.0-2-amd64             | 1         | 1.05%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 31        | 34.44%  |
| 6.1.0   | 13        | 14.44%  |
| 4.19.0  | 10        | 11.11%  |
| 5.18.0  | 4         | 4.44%   |
| 6.4.0   | 3         | 3.33%   |
| 6.5.0   | 2         | 2.22%   |
| 6.3.0   | 2         | 2.22%   |
| 5.17.0  | 2         | 2.22%   |
| 6.5.9   | 1         | 1.11%   |
| 6.4.4   | 1         | 1.11%   |
| 6.4.12  | 1         | 1.11%   |
| 6.3.3   | 1         | 1.11%   |
| 6.2.0   | 1         | 1.11%   |
| 6.0.11  | 1         | 1.11%   |
| 6.0.0   | 1         | 1.11%   |
| 5.9.13  | 1         | 1.11%   |
| 5.9.0   | 1         | 1.11%   |
| 5.8.13  | 1         | 1.11%   |
| 5.8.0   | 1         | 1.11%   |
| 5.7.2   | 1         | 1.11%   |
| 5.6.0   | 1         | 1.11%   |
| 5.5.0   | 1         | 1.11%   |
| 5.4.7   | 1         | 1.11%   |
| 5.2.0   | 1         | 1.11%   |
| 5.18.3  | 1         | 1.11%   |
| 5.17.3  | 1         | 1.11%   |
| 5.16.5  | 1         | 1.11%   |
| 5.16.0  | 1         | 1.11%   |
| 5.15.0  | 1         | 1.11%   |
| 5.14.0  | 1         | 1.11%   |
| 5.10.4  | 1         | 1.11%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 32        | 35.96%  |
| 6.1     | 13        | 14.61%  |
| 4.19    | 10        | 11.24%  |
| 6.4     | 5         | 5.62%   |
| 5.18    | 5         | 5.62%   |
| 6.5     | 3         | 3.37%   |
| 6.3     | 3         | 3.37%   |
| 5.17    | 3         | 3.37%   |
| 5.9     | 2         | 2.25%   |
| 5.8     | 2         | 2.25%   |
| 5.16    | 2         | 2.25%   |
| 6.2     | 1         | 1.12%   |
| 6.0     | 1         | 1.12%   |
| 5.7     | 1         | 1.12%   |
| 5.6     | 1         | 1.12%   |
| 5.5     | 1         | 1.12%   |
| 5.4     | 1         | 1.12%   |
| 5.2     | 1         | 1.12%   |
| 5.15    | 1         | 1.12%   |
| 5.14    | 1         | 1.12%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 77        | 92.77%  |
| i686   | 6         | 7.23%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| XFCE             | 32        | 37.65%  |
| LXQt             | 19        | 22.35%  |
| KDE5             | 10        | 11.76%  |
| Unknown          | 8         | 9.41%   |
| X-Cinnamon       | 3         | 3.53%   |
| openbox          | 3         | 3.53%   |
| MATE             | 2         | 2.35%   |
| lightdm-xsession | 2         | 2.35%   |
| GNOME            | 2         | 2.35%   |
| ICEWM            | 1         | 1.18%   |
| GNOME Flashback  | 1         | 1.18%   |
| GNOME Classic    | 1         | 1.18%   |
| Cinnamon         | 1         | 1.18%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 79        | 92.94%  |
| Tty  | 6         | 7.06%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 26        | 31.33%  |
| LightDM | 22        | 26.51%  |
| SDDM    | 19        | 22.89%  |
| TDM     | 13        | 15.66%  |
| GDM     | 2         | 2.41%   |
| XDM     | 1         | 1.2%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 24        | 28.92%  |
| pt_BR   | 7         | 8.43%   |
| en_GB   | 7         | 8.43%   |
| es_ES   | 6         | 7.23%   |
| fr_FR   | 5         | 6.02%   |
| de_DE   | 5         | 6.02%   |
| pl_PL   | 4         | 4.82%   |
| ru_RU   | 3         | 3.61%   |
| it_IT   | 2         | 2.41%   |
| en_CA   | 2         | 2.41%   |
| Unknown | 2         | 2.41%   |
| sv_SE   | 1         | 1.2%    |
| ja_JP   | 1         | 1.2%    |
| gl_ES   | 1         | 1.2%    |
| es_US   | 1         | 1.2%    |
| es_MX   | 1         | 1.2%    |
| es_CO   | 1         | 1.2%    |
| es_CL   | 1         | 1.2%    |
| es_AR   | 1         | 1.2%    |
| en_ZA   | 1         | 1.2%    |
| en_PH   | 1         | 1.2%    |
| en_IN   | 1         | 1.2%    |
| en_DK   | 1         | 1.2%    |
| en_AU   | 1         | 1.2%    |
| de_CH   | 1         | 1.2%    |
| cs_CZ   | 1         | 1.2%    |
| ar_EG   | 1         | 1.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 53        | 63.86%  |
| EFI  | 30        | 36.14%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 73        | 87.95%  |
| Overlay | 4         | 4.82%   |
| Btrfs   | 4         | 4.82%   |
| Zfs     | 1         | 1.2%    |
| Ext2    | 1         | 1.2%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 31        | 37.35%  |
| MBR     | 26        | 31.33%  |
| Unknown | 26        | 31.33%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 71        | 85.54%  |
| Yes       | 12        | 14.46%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 55        | 66.27%  |
| Yes       | 28        | 33.73%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 20        | 24.1%   |
| ASUSTek Computer    | 10        | 12.05%  |
| Acer                | 8         | 9.64%   |
| Dell                | 7         | 8.43%   |
| Lenovo              | 6         | 7.23%   |
| Intel               | 6         | 7.23%   |
| Gigabyte Technology | 5         | 6.02%   |
| MSI                 | 4         | 4.82%   |
| Google              | 3         | 3.61%   |
| Apple               | 2         | 2.41%   |
| Samsung Electronics | 1         | 1.2%    |
| Positivo            | 1         | 1.2%    |
| Panasonic           | 1         | 1.2%    |
| Microsoft           | 1         | 1.2%    |
| Medion              | 1         | 1.2%    |
| Mediacom            | 1         | 1.2%    |
| HUAWEI              | 1         | 1.2%    |
| Fujitsu Siemens     | 1         | 1.2%    |
| Foxconn             | 1         | 1.2%    |
| eMachines           | 1         | 1.2%    |
| Beelink             | 1         | 1.2%    |
| Unknown             | 1         | 1.2%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| Samsung NC10                          | 1         | 1.2%    |
| Positivo CHT14B                       | 1         | 1.2%    |
| Panasonic CFSZ5-2                     | 1         | 1.2%    |
| MSI MS-7C09                           | 1         | 1.2%    |
| MSI MS-7B86                           | 1         | 1.2%    |
| MSI MS-7721                           | 1         | 1.2%    |
| MSI Alpha 15 A3DDK                    | 1         | 1.2%    |
| Microsoft Surface Pro 4               | 1         | 1.2%    |
| Medion E15415                         | 1         | 1.2%    |
| Mediacom SmartBook 14 FullHD - SB14UC | 1         | 1.2%    |
| Lenovo ThinkPad T61 7659AB7           | 1         | 1.2%    |
| Lenovo ThinkPad T60 2007FUG           | 1         | 1.2%    |
| Lenovo ThinkPad T430 2349FC4          | 1         | 1.2%    |
| Lenovo ThinkPad E15 20RES0GF00        | 1         | 1.2%    |
| Lenovo IdeaPad S206 20154             | 1         | 1.2%    |
| Lenovo G50-30 80G0                    | 1         | 1.2%    |
| Intel NUC8i5BEH                       | 1         | 1.2%    |
| Intel NUC5CPYB H61145-408             | 1         | 1.2%    |
| Intel H61                             | 1         | 1.2%    |
| Intel H55                             | 1         | 1.2%    |
| Intel DG43RK AAE78175-402             | 1         | 1.2%    |
| Intel DG41TY AAE47335-300             | 1         | 1.2%    |
| HUAWEI HVY-WXX9                       | 1         | 1.2%    |
| HP Z440 Workstation                   | 1         | 1.2%    |
| HP Z420 Workstation                   | 1         | 1.2%    |
| HP t5740                              | 1         | 1.2%    |
| HP Stream Notebook PC 13              | 1         | 1.2%    |
| HP rp5700 Business System             | 1         | 1.2%    |
| HP Pavilion x360 Convertible 14-ba0xx | 1         | 1.2%    |
| HP Pavilion g7                        | 1         | 1.2%    |
| HP Pavilion g6                        | 1         | 1.2%    |
| HP Pavilion dv9000 (GA359UA#ABA)      | 1         | 1.2%    |
| HP Pavilion dv5                       | 1         | 1.2%    |
| HP Laptop 17z-ca100                   | 1         | 1.2%    |
| HP Laptop 15-ef2xxx                   | 1         | 1.2%    |
| HP EliteDesk 800 G2 DM 65W            | 1         | 1.2%    |
| HP EliteDesk 705 G2 MINI              | 1         | 1.2%    |
| HP EliteBook Folio 9480m              | 1         | 1.2%    |
| HP EliteBook 8770w                    | 1         | 1.2%    |
| HP EliteBook 8440p                    | 1         | 1.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Acer Aspire         | 8         | 9.64%   |
| HP Pavilion         | 5         | 6.02%   |
| Lenovo ThinkPad     | 4         | 4.82%   |
| HP EliteBook        | 4         | 4.82%   |
| Dell Inspiron       | 4         | 4.82%   |
| HP Laptop           | 2         | 2.41%   |
| HP EliteDesk        | 2         | 2.41%   |
| Dell OptiPlex       | 2         | 2.41%   |
| Samsung NC10        | 1         | 1.2%    |
| Positivo CHT14B     | 1         | 1.2%    |
| Panasonic CFSZ5-2   | 1         | 1.2%    |
| MSI MS-7C09         | 1         | 1.2%    |
| MSI MS-7B86         | 1         | 1.2%    |
| MSI MS-7721         | 1         | 1.2%    |
| MSI Alpha           | 1         | 1.2%    |
| Microsoft Surface   | 1         | 1.2%    |
| Medion E15415       | 1         | 1.2%    |
| Mediacom SmartBook  | 1         | 1.2%    |
| Lenovo IdeaPad      | 1         | 1.2%    |
| Lenovo G50-30       | 1         | 1.2%    |
| Intel NUC8i5BEH     | 1         | 1.2%    |
| Intel NUC5CPYB      | 1         | 1.2%    |
| Intel H61           | 1         | 1.2%    |
| Intel H55           | 1         | 1.2%    |
| Intel DG43RK        | 1         | 1.2%    |
| Intel DG41TY        | 1         | 1.2%    |
| HUAWEI HVY-WXX9     | 1         | 1.2%    |
| HP Z440             | 1         | 1.2%    |
| HP Z420             | 1         | 1.2%    |
| HP t5740            | 1         | 1.2%    |
| HP Stream           | 1         | 1.2%    |
| HP rp5700           | 1         | 1.2%    |
| HP Compaq           | 1         | 1.2%    |
| HP 250              | 1         | 1.2%    |
| Google Swanky       | 1         | 1.2%    |
| Google Kefka        | 1         | 1.2%    |
| Google Banon        | 1         | 1.2%    |
| Gigabyte X570S      | 1         | 1.2%    |
| Gigabyte M68M-S2P   | 1         | 1.2%    |
| Gigabyte H97-Gaming | 1         | 1.2%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2012 | 10        | 12.05%  |
| 2009 | 9         | 10.84%  |
| 2011 | 7         | 8.43%   |
| 2021 | 6         | 7.23%   |
| 2014 | 6         | 7.23%   |
| 2010 | 6         | 7.23%   |
| 2018 | 5         | 6.02%   |
| 2008 | 5         | 6.02%   |
| 2007 | 5         | 6.02%   |
| 2017 | 4         | 4.82%   |
| 2016 | 4         | 4.82%   |
| 2020 | 3         | 3.61%   |
| 2019 | 3         | 3.61%   |
| 2015 | 3         | 3.61%   |
| 2022 | 2         | 2.41%   |
| 2013 | 2         | 2.41%   |
| 2006 | 2         | 2.41%   |
| 2023 | 1         | 1.2%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 46        | 55.42%  |
| Desktop     | 32        | 38.55%  |
| Mini pc     | 2         | 2.41%   |
| Tablet      | 1         | 1.2%    |
| Convertible | 1         | 1.2%    |
| All in one  | 1         | 1.2%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 82        | 98.8%   |
| Enabled  | 1         | 1.2%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 80        | 96.39%  |
| Yes  | 3         | 3.61%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 25        | 30.12%  |
| 4.01-8.0    | 15        | 18.07%  |
| 8.01-16.0   | 13        | 15.66%  |
| 1.01-2.0    | 10        | 12.05%  |
| 16.01-24.0  | 8         | 9.64%   |
| 2.01-3.0    | 5         | 6.02%   |
| 32.01-64.0  | 3         | 3.61%   |
| 24.01-32.0  | 2         | 2.41%   |
| 64.01-256.0 | 1         | 1.2%    |
| 0.51-1.0    | 1         | 1.2%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 33        | 37.93%  |
| 2.01-3.0 | 24        | 27.59%  |
| 0.51-1.0 | 14        | 16.09%  |
| 4.01-8.0 | 7         | 8.05%   |
| 3.01-4.0 | 6         | 6.9%    |
| 0.01-0.5 | 3         | 3.45%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 60        | 69.77%  |
| 2      | 18        | 20.93%  |
| 4      | 4         | 4.65%   |
| 6      | 2         | 2.33%   |
| 5      | 1         | 1.16%   |
| 3      | 1         | 1.16%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 52        | 62.65%  |
| Yes       | 31        | 37.35%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 70        | 84.34%  |
| No        | 13        | 15.66%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 58        | 69.88%  |
| No        | 25        | 30.12%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 43        | 51.81%  |
| No        | 40        | 48.19%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 13        | 15.66%  |
| Germany      | 8         | 9.64%   |
| France       | 7         | 8.43%   |
| Brazil       | 7         | 8.43%   |
| UK           | 6         | 7.23%   |
| Spain        | 6         | 7.23%   |
| Poland       | 4         | 4.82%   |
| Canada       | 4         | 4.82%   |
| Indonesia    | 3         | 3.61%   |
| Sweden       | 2         | 2.41%   |
| Russia       | 2         | 2.41%   |
| Italy        | 2         | 2.41%   |
| Argentina    | 2         | 2.41%   |
| Venezuela    | 1         | 1.2%    |
| Uzbekistan   | 1         | 1.2%    |
| Switzerland  | 1         | 1.2%    |
| South Africa | 1         | 1.2%    |
| Philippines  | 1         | 1.2%    |
| New Zealand  | 1         | 1.2%    |
| Netherlands  | 1         | 1.2%    |
| Mexico       | 1         | 1.2%    |
| Malaysia     | 1         | 1.2%    |
| Lebanon      | 1         | 1.2%    |
| Japan        | 1         | 1.2%    |
| India        | 1         | 1.2%    |
| Czechia      | 1         | 1.2%    |
| Colombia     | 1         | 1.2%    |
| Chile        | 1         | 1.2%    |
| Belgium      | 1         | 1.2%    |
| Australia    | 1         | 1.2%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Rio de Janeiro      | 2         | 2.27%   |
| Montreuil           | 2         | 2.27%   |
| Montreal            | 2         | 2.27%   |
| Leipzig             | 2         | 2.27%   |
| Woking              | 1         | 1.14%   |
| West Palm Beach     | 1         | 1.14%   |
| Wenatchee           | 1         | 1.14%   |
| Vigo                | 1         | 1.14%   |
| Tucson              | 1         | 1.14%   |
| Trelaze             | 1         | 1.14%   |
| Tauranga            | 1         | 1.14%   |
| Takahama            | 1         | 1.14%   |
| Surabaya            | 1         | 1.14%   |
| Spokane             | 1         | 1.14%   |
| Sin el Fil          | 1         | 1.14%   |
| Santo André        | 1         | 1.14%   |
| San Cristóbal      | 1         | 1.14%   |
| San Antonio         | 1         | 1.14%   |
| Salina Cruz         | 1         | 1.14%   |
| Sainte-Julie        | 1         | 1.14%   |
| Rudersberg          | 1         | 1.14%   |
| Rosario             | 1         | 1.14%   |
| Rio Claro           | 1         | 1.14%   |
| Quezon City         | 1         | 1.14%   |
| Pujaudran           | 1         | 1.14%   |
| Puente Alto         | 1         | 1.14%   |
| Presidente Prudente | 1         | 1.14%   |
| Posadas             | 1         | 1.14%   |
| Pompano Beach       | 1         | 1.14%   |
| Norrköping         | 1         | 1.14%   |
| Munich              | 1         | 1.14%   |
| Moscow              | 1         | 1.14%   |
| Montriond           | 1         | 1.14%   |
| Mnisek pod Brdy     | 1         | 1.14%   |
| Minneapolis         | 1         | 1.14%   |
| Milano              | 1         | 1.14%   |
| Miekoszyn           | 1         | 1.14%   |
| Melbourne           | 1         | 1.14%   |
| Mannheim            | 1         | 1.14%   |
| Madrid              | 1         | 1.14%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| WDC                          | 20        | 23     | 17.39%  |
| Seagate                      | 20        | 27     | 17.39%  |
| Samsung Electronics          | 14        | 25     | 12.17%  |
| Hitachi                      | 8         | 11     | 6.96%   |
| Unknown                      | 7         | 7      | 6.09%   |
| SanDisk                      | 4         | 5      | 3.48%   |
| Toshiba                      | 3         | 3      | 2.61%   |
| SPCC                         | 3         | 4      | 2.61%   |
| Kingston                     | 3         | 3      | 2.61%   |
| Intel                        | 3         | 3      | 2.61%   |
| A-DATA Technology            | 3         | 4      | 2.61%   |
| SK hynix                     | 2         | 2      | 1.74%   |
| Silicon Motion               | 2         | 3      | 1.74%   |
| HGST                         | 2         | 2      | 1.74%   |
| GOODRAM                      | 2         | 4      | 1.74%   |
| Crucial                      | 2         | 2      | 1.74%   |
| ASMedia                      | 2         | 2      | 1.74%   |
| Unknown                      | 2         | 2      | 1.74%   |
| XPG                          | 1         | 1      | 0.87%   |
| Shenzhen Longsys Electronics | 1         | 2      | 0.87%   |
| PNY                          | 1         | 1      | 0.87%   |
| Phison Electronics           | 1         | 1      | 0.87%   |
| Patriot                      | 1         | 1      | 0.87%   |
| ORICO                        | 1         | 1      | 0.87%   |
| Netac                        | 1         | 1      | 0.87%   |
| Micron Technology            | 1         | 1      | 0.87%   |
| Gigabyte Technology          | 1         | 1      | 0.87%   |
| Fujitsu                      | 1         | 2      | 0.87%   |
| China                        | 1         | 1      | 0.87%   |
| ASUS-JM                      | 1         | 1      | 0.87%   |
| Apple                        | 1         | 1      | 0.87%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| WDC WD1600BEVT-22ZCT0 160GB          | 2         | 1.64%   |
| Unknown MMC Card  32GB               | 2         | 1.64%   |
| Seagate ST500LT012-1DG142 500GB      | 2         | 1.64%   |
| Seagate ST2000DM008-2FR102 2TB       | 2         | 1.64%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 2         | 1.64%   |
| Seagate Backup+ Hub BK 8TB           | 2         | 1.64%   |
| Samsung HD161GJ 160GB                | 2         | 1.64%   |
| Hitachi HTS545025B9A300 250GB        | 2         | 1.64%   |
| Unknown                              | 2         | 1.64%   |
| XPG GAMMIX S11 Pro 256GB             | 1         | 0.82%   |
| WDC WD800JD-08MSA1 80GB              | 1         | 0.82%   |
| WDC WD7500BPVX-22JC3T0 752GB         | 1         | 0.82%   |
| WDC WD6400AAKS-22A7B2 640GB          | 1         | 0.82%   |
| WDC WD5000BEVT-22ZAT0 500GB          | 1         | 0.82%   |
| WDC WD5000AVVS-63ZWB0 500GB          | 1         | 0.82%   |
| WDC WD5000AAKS-75V0A0 500GB          | 1         | 0.82%   |
| WDC WD50 00LPLX-08ZNTT0 500GB        | 1         | 0.82%   |
| WDC WD50 00LPCX-21VHAT0 500GB        | 1         | 0.82%   |
| WDC WD3200BPVT-75ZEST0 320GB         | 1         | 0.82%   |
| WDC WD3200AAKS-75L9A0 320GB          | 1         | 0.82%   |
| WDC WD2500AAKX-07U6AA0 250GB         | 1         | 0.82%   |
| WDC WD2500AAJS-00L7A0 250GB          | 1         | 0.82%   |
| WDC WD1600AAJS-08L7A0 160GB          | 1         | 0.82%   |
| WDC WD10SPZX-21Z10T0 1TB             | 1         | 0.82%   |
| WDC WD10EZEX-60WN4A0 1TB             | 1         | 0.82%   |
| WDC WD10EADS-00M2B0 1TB              | 1         | 0.82%   |
| WDC PC SN730 SDBPNTY-512G-1006 512GB | 1         | 0.82%   |
| WDC PC SA530 SDASN8Y-256G-1006 256GB | 1         | 0.82%   |
| Unknown SDC  8GB                     | 1         | 0.82%   |
| Unknown NCard  32GB                  | 1         | 0.82%   |
| Unknown MMC Card  64GB               | 1         | 0.82%   |
| Unknown HBG4a2  32GB                 | 1         | 0.82%   |
| Unknown 016GE2  16GB                 | 1         | 0.82%   |
| Toshiba MQ04ABF100 1TB               | 1         | 0.82%   |
| Toshiba DT01ACA100 1TB               | 1         | 0.82%   |
| Toshiba DT01ACA050 500GB             | 1         | 0.82%   |
| SPCC Solid State Disk 512GB          | 1         | 0.82%   |
| SPCC Solid State Disk 256GB          | 1         | 0.82%   |
| SPCC M.2 PCIe SSD 512GB              | 1         | 0.82%   |
| SK hynix HCG8e  64GB                 | 1         | 0.82%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 20        | 25     | 34.48%  |
| WDC                 | 18        | 21     | 31.03%  |
| Hitachi             | 8         | 11     | 13.79%  |
| Samsung Electronics | 5         | 12     | 8.62%   |
| Toshiba             | 3         | 3      | 5.17%   |
| HGST                | 2         | 2      | 3.45%   |
| Fujitsu             | 1         | 2      | 1.72%   |
| Apple               | 1         | 1      | 1.72%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 8      | 15.15%  |
| Kingston            | 3         | 3      | 9.09%   |
| Intel               | 3         | 3      | 9.09%   |
| SPCC                | 2         | 3      | 6.06%   |
| SanDisk             | 2         | 2      | 6.06%   |
| GOODRAM             | 2         | 4      | 6.06%   |
| Crucial             | 2         | 2      | 6.06%   |
| ASMedia             | 2         | 2      | 6.06%   |
| A-DATA Technology   | 2         | 3      | 6.06%   |
| WDC                 | 1         | 1      | 3.03%   |
| PNY                 | 1         | 1      | 3.03%   |
| Patriot             | 1         | 1      | 3.03%   |
| ORICO               | 1         | 1      | 3.03%   |
| Netac               | 1         | 1      | 3.03%   |
| Micron Technology   | 1         | 1      | 3.03%   |
| Gigabyte Technology | 1         | 1      | 3.03%   |
| China               | 1         | 1      | 3.03%   |
| ASUS-JM             | 1         | 1      | 3.03%   |
| Unknown             | 1         | 1      | 3.03%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 49        | 77     | 47.57%  |
| SSD     | 29        | 40     | 28.16%  |
| NVMe    | 14        | 19     | 13.59%  |
| MMC     | 10        | 10     | 9.71%   |
| Unknown | 1         | 1      | 0.97%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 67        | 108    | 69.79%  |
| NVMe | 14        | 19     | 14.58%  |
| MMC  | 10        | 10     | 10.42%  |
| SAS  | 5         | 10     | 5.21%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 53        | 80     | 67.95%  |
| 0.51-1.0   | 19        | 29     | 24.36%  |
| 1.01-2.0   | 4         | 4      | 5.13%   |
| 4.01-10.0  | 2         | 4      | 2.56%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 22        | 26.19%  |
| 251-500        | 17        | 20.24%  |
| 501-1000       | 16        | 19.05%  |
| 21-50          | 8         | 9.52%   |
| 1-20           | 7         | 8.33%   |
| 2001-3000      | 5         | 5.95%   |
| 51-100         | 4         | 4.76%   |
| More than 3000 | 2         | 2.38%   |
| Unknown        | 2         | 2.38%   |
| 1001-2000      | 1         | 1.19%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 39        | 44.83%  |
| 21-50          | 15        | 17.24%  |
| 251-500        | 8         | 9.2%    |
| 51-100         | 7         | 8.05%   |
| 501-1000       | 6         | 6.9%    |
| 101-250        | 5         | 5.75%   |
| 1001-2000      | 3         | 3.45%   |
| Unknown        | 2         | 2.3%    |
| More than 3000 | 1         | 1.15%   |
| 2001-3000      | 1         | 1.15%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-22ZAT0 500GB                         | 1         | 1      | 6.67%   |
| WDC WD5000AVVS-63ZWB0 500GB                         | 1         | 1      | 6.67%   |
| WDC WD3200BPVT-75ZEST0 320GB                        | 1         | 1      | 6.67%   |
| WDC WD1600AAJS-08L7A0 160GB                         | 1         | 1      | 6.67%   |
| WDC WD10EADS-00M2B0 1TB                             | 1         | 1      | 6.67%   |
| Seagate ST9500325AS 500GB                           | 1         | 1      | 6.67%   |
| Seagate ST9250315AS 250GB                           | 1         | 1      | 6.67%   |
| Seagate ST3500413AS 500GB                           | 1         | 1      | 6.67%   |
| Seagate ST2000DM008-2FR102 2TB                      | 1         | 1      | 6.67%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 1      | 6.67%   |
| Seagate ST1000DM003-9YN162 1TB                      | 1         | 1      | 6.67%   |
| Micron Technology MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 1      | 6.67%   |
| Intel SSDSC2CW060A3 64GB                            | 1         | 1      | 6.67%   |
| ASMedia ASMT1153E 500GB                             | 1         | 1      | 6.67%   |
| Unknown                                             | 1         | 1      | 6.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 6         | 6      | 40%     |
| WDC               | 5         | 5      | 33.33%  |
| Micron Technology | 1         | 1      | 6.67%   |
| Intel             | 1         | 1      | 6.67%   |
| ASMedia           | 1         | 1      | 6.67%   |
| Unknown           | 1         | 1      | 6.67%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 6      | 54.55%  |
| WDC     | 5         | 5      | 45.45%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 11        | 11     | 73.33%  |
| SSD  | 4         | 4      | 26.67%  |

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
| Works    | 43        | 62     | 45.74%  |
| Detected | 36        | 70     | 38.3%   |
| Malfunc  | 15        | 15     | 15.96%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 54        | 62.07%  |
| AMD                          | 12        | 13.79%  |
| Samsung Electronics          | 5         | 5.75%   |
| Silicon Motion               | 3         | 3.45%   |
| Nvidia                       | 3         | 3.45%   |
| VIA Technologies             | 1         | 1.15%   |
| SK hynix                     | 1         | 1.15%   |
| Shenzhen Longsys Electronics | 1         | 1.15%   |
| Seagate Technology           | 1         | 1.15%   |
| SanDisk                      | 1         | 1.15%   |
| Phison Electronics           | 1         | 1.15%   |
| Marvell Technology Group     | 1         | 1.15%   |
| LSI Logic / Symbios Logic    | 1         | 1.15%   |
| JMicron Technology           | 1         | 1.15%   |
| ADATA Technology             | 1         | 1.15%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 9         | 8.49%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                | 6         | 5.66%   |
| Intel 82801G (ICH7 Family) IDE Controller                                     | 4         | 3.77%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 4         | 3.77%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 3         | 2.83%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                 | 3         | 2.83%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                | 3         | 2.83%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller | 3         | 2.83%   |
| Samsung NVMe SSD Controller SM951/PM951                                       | 2         | 1.89%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                   | 2         | 1.89%   |
| Nvidia MCP61 SATA Controller                                                  | 2         | 1.89%   |
| Nvidia MCP61 IDE                                                              | 2         | 1.89%   |
| Intel SATA Controller [RAID Mode]                                             | 2         | 1.89%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                             | 2         | 1.89%   |
| Intel Comet Lake SATA AHCI Controller                                         | 2         | 1.89%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                        | 2         | 1.89%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]         | 2         | 1.89%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]          | 2         | 1.89%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                 | 2         | 1.89%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                              | 2         | 1.89%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                  | 2         | 1.89%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller  | 2         | 1.89%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                             | 2         | 1.89%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                          | 2         | 1.89%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                   | 1         | 0.94%   |
| VIA VT8237A SATA 2-Port Controller                                            | 1         | 0.94%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                          | 1         | 0.94%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers             | 1         | 0.94%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                 | 1         | 0.94%   |
| Silicon Motion Non-Volatile memory controller                                 | 1         | 0.94%   |
| Shenzhen Longsys Lexar NM610 PRO NVME SSD (DRAM-less)                         | 1         | 0.94%   |
| Seagate BarraCuda Q5 NVMe SSD (DRAM-less)                                     | 1         | 0.94%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                         | 1         | 0.94%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 1         | 0.94%   |
| Phison PS5019-E19 PCIe4 NVMe Controller (DRAM-less)                           | 1         | 0.94%   |
| Nvidia MCP51 Serial ATA Controller                                            | 1         | 0.94%   |
| Nvidia MCP51 IDE                                                              | 1         | 0.94%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                     | 1         | 0.94%   |
| LSI Logic / Symbios Logic SAS1064ET PCI-Express Fusion-MPT SAS                | 1         | 0.94%   |
| JMicron JMB360 AHCI Controller                                                | 1         | 0.94%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 53        | 56.38%  |
| IDE  | 23        | 24.47%  |
| NVMe | 13        | 13.83%  |
| RAID | 3         | 3.19%   |
| SAS  | 1         | 1.06%   |
| SCSI | 1         | 1.06%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 64        | 77.11%  |
| AMD    | 19        | 22.89%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Celeron CPU N2840 @ 2.16GHz           | 3         | 3.61%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 2         | 2.41%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 2         | 2.41%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 2         | 2.41%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz        | 2         | 2.41%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz        | 2         | 2.41%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 2         | 2.41%   |
| Intel Atom CPU N280 @ 1.66GHz               | 2         | 2.41%   |
| Intel Atom CPU N270 @ 1.60GHz               | 2         | 2.41%   |
| Intel Xeon CPU E5-2687W 0 @ 3.10GHz         | 1         | 1.2%    |
| Intel Xeon CPU E5-1650 v4 @ 3.60GHz         | 1         | 1.2%    |
| Intel Pentium Gold G5400 CPU @ 3.70GHz      | 1         | 1.2%    |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz | 1         | 1.2%    |
| Intel Pentium CPU B950 @ 2.10GHz            | 1         | 1.2%    |
| Intel Genuine CPU T2400 @ 1.83GHz           | 1         | 1.2%    |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1         | 1.2%    |
| Intel Core i7-4600U CPU @ 2.10GHz           | 1         | 1.2%    |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1         | 1.2%    |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 1         | 1.2%    |
| Intel Core i7-3612QM CPU @ 2.10GHz          | 1         | 1.2%    |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1         | 1.2%    |
| Intel Core i5-8259U CPU @ 2.30GHz           | 1         | 1.2%    |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1         | 1.2%    |
| Intel Core i5-6500 CPU @ 3.20GHz            | 1         | 1.2%    |
| Intel Core i5-4460 CPU @ 3.20GHz            | 1         | 1.2%    |
| Intel Core i5-3570K CPU @ 3.40GHz           | 1         | 1.2%    |
| Intel Core i5-3320M CPU @ 2.60GHz           | 1         | 1.2%    |
| Intel Core i5-3210M CPU @ 2.50GHz           | 1         | 1.2%    |
| Intel Core i5-2520M CPU @ 2.50GHz           | 1         | 1.2%    |
| Intel Core i5-10400 CPU @ 2.90GHz           | 1         | 1.2%    |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 1         | 1.2%    |
| Intel Core i5 CPU M 460 @ 2.53GHz           | 1         | 1.2%    |
| Intel Core i5 CPU 660 @ 3.33GHz             | 1         | 1.2%    |
| Intel Core i3-7100U CPU @ 2.40GHz           | 1         | 1.2%    |
| Intel Core i3-2130 CPU @ 3.40GHz            | 1         | 1.2%    |
| Intel Core i3 CPU M 380 @ 2.53GHz           | 1         | 1.2%    |
| Intel Core i3 CPU 540 @ 3.07GHz             | 1         | 1.2%    |
| Intel Core i3 CPU 530 @ 2.93GHz             | 1         | 1.2%    |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 1         | 1.2%    |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 1         | 1.2%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 18        | 21.69%  |
| Intel Celeron           | 9         | 10.84%  |
| Intel Atom              | 8         | 9.64%   |
| Intel Core 2 Duo        | 7         | 8.43%   |
| Intel Core i7           | 6         | 7.23%   |
| Intel Core i3           | 5         | 6.02%   |
| Intel Core 2            | 3         | 3.61%   |
| Intel Xeon              | 2         | 2.41%   |
| AMD Ryzen 7             | 2         | 2.41%   |
| AMD Ryzen 5             | 2         | 2.41%   |
| AMD Ryzen 3             | 2         | 2.41%   |
| AMD A6                  | 2         | 2.41%   |
| Other                   | 1         | 1.2%    |
| Intel Pentium Gold      | 1         | 1.2%    |
| Intel Pentium Dual-Core | 1         | 1.2%    |
| Intel Pentium           | 1         | 1.2%    |
| Intel Genuine           | 1         | 1.2%    |
| Intel Core 2 Quad       | 1         | 1.2%    |
| AMD Turion 64 X2 Mobile | 1         | 1.2%    |
| AMD Sempron             | 1         | 1.2%    |
| AMD Ryzen 9             | 1         | 1.2%    |
| AMD PRO A8              | 1         | 1.2%    |
| AMD PRO A10             | 1         | 1.2%    |
| AMD Phenom II X6        | 1         | 1.2%    |
| AMD C-50                | 1         | 1.2%    |
| AMD Athlon II X3        | 1         | 1.2%    |
| AMD Athlon II X2        | 1         | 1.2%    |
| AMD A8                  | 1         | 1.2%    |
| AMD A4                  | 1         | 1.2%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 42        | 50.6%   |
| 4      | 26        | 31.33%  |
| 1      | 7         | 8.43%   |
| 6      | 4         | 4.82%   |
| 8      | 2         | 2.41%   |
| 12     | 1         | 1.2%    |
| 3      | 1         | 1.2%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 83        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 42        | 50.6%   |
| 1      | 41        | 49.4%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 78        | 93.98%  |
| 32-bit         | 5         | 6.02%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 19        | 22.62%  |
| 0x406c4    | 4         | 4.76%   |
| 0x306a9    | 4         | 4.76%   |
| 0x206a7    | 4         | 4.76%   |
| 0x6f2      | 3         | 3.57%   |
| 0x30678    | 3         | 3.57%   |
| 0x20655    | 3         | 3.57%   |
| 0x20652    | 3         | 3.57%   |
| 0x1067a    | 3         | 3.57%   |
| 0x0600611a | 3         | 3.57%   |
| 0x806ec    | 2         | 2.38%   |
| 0x406c3    | 2         | 2.38%   |
| 0x306c3    | 2         | 2.38%   |
| 0x106c2    | 2         | 2.38%   |
| 0x10676    | 2         | 2.38%   |
| 0x08108109 | 2         | 2.38%   |
| 0xa0653    | 1         | 1.19%   |
| 0x806ea    | 1         | 1.19%   |
| 0x806e9    | 1         | 1.19%   |
| 0x706a8    | 1         | 1.19%   |
| 0x6fd      | 1         | 1.19%   |
| 0x6fb      | 1         | 1.19%   |
| 0x506e3    | 1         | 1.19%   |
| 0x406f1    | 1         | 1.19%   |
| 0x40651    | 1         | 1.19%   |
| 0x206d7    | 1         | 1.19%   |
| 0x106e5    | 1         | 1.19%   |
| 0x0a201016 | 1         | 1.19%   |
| 0x08701021 | 1         | 1.19%   |
| 0x08608103 | 1         | 1.19%   |
| 0x08600106 | 1         | 1.19%   |
| 0x08001138 | 1         | 1.19%   |
| 0x0700010f | 1         | 1.19%   |
| 0x06001119 | 1         | 1.19%   |
| 0x05000029 | 1         | 1.19%   |
| 0x03000027 | 1         | 1.19%   |
| 0x010000dc | 1         | 1.19%   |
| 0x010000db | 1         | 1.19%   |
| 0x010000c8 | 1         | 1.19%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Silvermont    | 10        | 12.05%  |
| Core          | 7         | 8.43%   |
| Westmere      | 6         | 7.23%   |
| SandyBridge   | 6         | 7.23%   |
| Penryn        | 6         | 7.23%   |
| KabyLake      | 6         | 7.23%   |
| IvyBridge     | 6         | 7.23%   |
| K10           | 4         | 4.82%   |
| Bonnell       | 4         | 4.82%   |
| Skylake       | 3         | 3.61%   |
| Haswell       | 3         | 3.61%   |
| Excavator     | 3         | 3.61%   |
| Zen+          | 2         | 2.41%   |
| Zen 2         | 2         | 2.41%   |
| Goldmont plus | 2         | 2.41%   |
| Zen 3         | 1         | 1.2%    |
| Zen           | 1         | 1.2%    |
| TigerLake     | 1         | 1.2%    |
| Piledriver    | 1         | 1.2%    |
| P6            | 1         | 1.2%    |
| Nehalem       | 1         | 1.2%    |
| K8 Hammer     | 1         | 1.2%    |
| K10 Llano     | 1         | 1.2%    |
| Jaguar        | 1         | 1.2%    |
| CometLake     | 1         | 1.2%    |
| Broadwell     | 1         | 1.2%    |
| Bobcat        | 1         | 1.2%    |
| Unknown       | 1         | 1.2%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Intel            | 48        | 56.47%  |
| AMD              | 20        | 23.53%  |
| Nvidia           | 16        | 18.82%  |
| VIA Technologies | 1         | 1.18%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 6.32%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 5         | 5.26%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 4.21%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 3         | 3.16%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 3.16%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 3.16%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3         | 3.16%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 3         | 3.16%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 2.11%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 2.11%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 2.11%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 2.11%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 2.11%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 2.11%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 2.11%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                                         | 2         | 2.11%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 2.11%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 2.11%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 2         | 2.11%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 1         | 1.05%   |
| Nvidia GT218 [GeForce 310]                                                               | 1         | 1.05%   |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 1.05%   |
| Nvidia GT200GL [Quadro FX 3800]                                                          | 1         | 1.05%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1         | 1.05%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 1.05%   |
| Nvidia GM107GL [Quadro K1200]                                                            | 1         | 1.05%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1         | 1.05%   |
| Nvidia GK104GLM [Quadro K3000M]                                                          | 1         | 1.05%   |
| Nvidia GK104 [GeForce GTX 760]                                                           | 1         | 1.05%   |
| Nvidia GF108M [GeForce GT 420M]                                                          | 1         | 1.05%   |
| Nvidia GA106 [Geforce RTX 3050]                                                          | 1         | 1.05%   |
| Nvidia G96CM [GeForce 9650M GT]                                                          | 1         | 1.05%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 1.05%   |
| Nvidia G96CGL [Quadro FX 580]                                                            | 1         | 1.05%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 1         | 1.05%   |
| Nvidia C51 [GeForce Go 6150]                                                             | 1         | 1.05%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1         | 1.05%   |
| Intel UHD Graphics 620                                                                   | 1         | 1.05%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 1         | 1.05%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1         | 1.05%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 45        | 54.22%  |
| 1 x AMD        | 17        | 20.48%  |
| 1 x Nvidia     | 15        | 18.07%  |
| 2 x Intel      | 2         | 2.41%   |
| 2 x AMD        | 2         | 2.41%   |
| 1 x VIA        | 1         | 1.2%    |
| Intel + Nvidia | 1         | 1.2%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 75        | 90.36%  |
| Proprietary | 4         | 4.82%   |
| Unknown     | 4         | 4.82%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 56        | 66.67%  |
| 0.01-0.5   | 12        | 14.29%  |
| 0.51-1.0   | 7         | 8.33%   |
| 1.01-2.0   | 5         | 5.95%   |
| 7.01-8.0   | 2         | 2.38%   |
| 3.01-4.0   | 2         | 2.38%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 11        | 14.29%  |
| LG Display          | 10        | 12.99%  |
| AU Optronics        | 8         | 10.39%  |
| Chimei Innolux      | 6         | 7.79%   |
| BOE                 | 6         | 7.79%   |
| Goldstar            | 5         | 6.49%   |
| AOC                 | 4         | 5.19%   |
| Dell                | 3         | 3.9%    |
| CPT                 | 3         | 3.9%    |
| Acer                | 3         | 3.9%    |
| Lenovo              | 2         | 2.6%    |
| BenQ                | 2         | 2.6%    |
| Apple               | 2         | 2.6%    |
| Unknown             | 1         | 1.3%    |
| Toshiba             | 1         | 1.3%    |
| Sony                | 1         | 1.3%    |
| RTK                 | 1         | 1.3%    |
| PANDA               | 1         | 1.3%    |
| Medion              | 1         | 1.3%    |
| LG Philips          | 1         | 1.3%    |
| JCH                 | 1         | 1.3%    |
| Insignia            | 1         | 1.3%    |
| Hitachi             | 1         | 1.3%    |
| Hewlett-Packard     | 1         | 1.3%    |
| HannStar            | 1         | 1.3%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 1         | 1.23%   |
| Toshiba TV TSB0206 1920x1080                                          | 1         | 1.23%   |
| Sony TV SNY2A03 1920x1080                                             | 1         | 1.23%   |
| Samsung Electronics SyncMaster SAM0581 1920x1080 477x268mm 21.5-inch  | 1         | 1.23%   |
| Samsung Electronics SyncMaster SAM0116 1024x768 267x200mm 13.1-inch   | 1         | 1.23%   |
| Samsung Electronics SMB1630N SAM0630 1366x768 344x194mm 15.5-inch     | 1         | 1.23%   |
| Samsung Electronics SA300/SA350 SAM078F 1920x1080 477x268mm 21.5-inch | 1         | 1.23%   |
| Samsung Electronics S27C36x SAM7315 1920x1080 600x340mm 27.2-inch     | 1         | 1.23%   |
| Samsung Electronics S24D330 SAM0D93 1920x1080 531x299mm 24.0-inch     | 1         | 1.23%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch     | 1         | 1.23%   |
| Samsung Electronics S22C450 SAM09C5 1920x1080 477x268mm 21.5-inch     | 1         | 1.23%   |
| Samsung Electronics LCD Monitor SEC4F45 1280x800 331x207mm 15.4-inch  | 1         | 1.23%   |
| Samsung Electronics LCD Monitor SEC4141 1366x768 344x193mm 15.5-inch  | 1         | 1.23%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch  | 1         | 1.23%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1         | 1.23%   |
| RTK Lenovo ICA300 RTK2482 1920x1080 477x268mm 21.5-inch               | 1         | 1.23%   |
| PANDA LCD Monitor NCP0063 1920x1080 344x194mm 15.5-inch               | 1         | 1.23%   |
| Medion MD 20310 MED3645 1920x1080 521x293mm 23.5-inch                 | 1         | 1.23%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch           | 1         | 1.23%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch         | 1         | 1.23%   |
| LG Display LCD Monitor LGD059E 1920x1080 382x215mm 17.3-inch          | 1         | 1.23%   |
| LG Display LCD Monitor LGD0555 1536x1024 263x175mm 12.4-inch          | 1         | 1.23%   |
| LG Display LCD Monitor LGD04E1 1366x768 344x194mm 15.5-inch           | 1         | 1.23%   |
| LG Display LCD Monitor LGD03F8 1366x768 345x194mm 15.6-inch           | 1         | 1.23%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch           | 1         | 1.23%   |
| LG Display LCD Monitor LGD02E1 1600x900 382x215mm 17.3-inch           | 1         | 1.23%   |
| LG Display LCD Monitor LGD0266 1366x768 344x194mm 15.5-inch           | 1         | 1.23%   |
| LG Display LCD Monitor LGD0212 1366x768 309x174mm 14.0-inch           | 1         | 1.23%   |
| LG Display LCD Monitor LGD01C5 1366x768 293x165mm 13.2-inch           | 1         | 1.23%   |
| Lenovo LCD Monitor LEN4033 1440x900 304x190mm 14.1-inch               | 1         | 1.23%   |
| Lenovo LCD Monitor LEN4022 1400x1050 287x215mm 14.1-inch              | 1         | 1.23%   |
| JCH F24 JCH1919 1920x1080 520x310mm 23.8-inch                         | 1         | 1.23%   |
| Insignia NS-32D20SNA14 BBY0032 1360x768 544x326mm 25.0-inch           | 1         | 1.23%   |
| Hitachi HDMI    HEC0088 1360x768 1100x560mm 48.6-inch                 | 1         | 1.23%   |
| Hewlett-Packard w2207 HWP26A8 1680x1050 473x296mm 22.0-inch           | 1         | 1.23%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch             | 1         | 1.23%   |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                   | 1         | 1.23%   |
| Goldstar W2042 GSM4E7E 1680x1050 434x270mm 20.1-inch                  | 1         | 1.23%   |
| Goldstar TV GSM9CF6 1360x768 700x392mm 31.6-inch                      | 1         | 1.23%   |
| Goldstar T710SH GSM436B 1280x960 310x230mm 15.2-inch                  | 1         | 1.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 31        | 38.75%  |
| 1366x768 (WXGA)    | 18        | 22.5%   |
| 1600x900 (HD+)     | 4         | 5%      |
| 1280x800 (WXGA)    | 4         | 5%      |
| 1680x1050 (WSXGA+) | 3         | 3.75%   |
| 1440x900 (WXGA+)   | 3         | 3.75%   |
| 1280x1024 (SXGA)   | 3         | 3.75%   |
| 1024x600           | 3         | 3.75%   |
| 1920x540           | 2         | 2.5%    |
| 3840x1080          | 1         | 1.25%   |
| 2736x1824          | 1         | 1.25%   |
| 2288x1287          | 1         | 1.25%   |
| 1920x1200 (WUXGA)  | 1         | 1.25%   |
| 1400x1050          | 1         | 1.25%   |
| 1360x768           | 1         | 1.25%   |
| 1280x960           | 1         | 1.25%   |
| 1024x768 (XGA)     | 1         | 1.25%   |
| Unknown            | 1         | 1.25%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 16        | 20.25%  |
| 13      | 11        | 13.92%  |
| 23      | 9         | 11.39%  |
| 17      | 9         | 11.39%  |
| 14      | 5         | 6.33%   |
| 21      | 3         | 3.8%    |
| 20      | 3         | 3.8%    |
| 10      | 3         | 3.8%    |
| 72      | 2         | 2.53%   |
| 48      | 2         | 2.53%   |
| 27      | 2         | 2.53%   |
| 24      | 2         | 2.53%   |
| 18      | 2         | 2.53%   |
| 16      | 2         | 2.53%   |
| 12      | 2         | 2.53%   |
| 142     | 1         | 1.27%   |
| 74      | 1         | 1.27%   |
| 22      | 1         | 1.27%   |
| 19      | 1         | 1.27%   |
| 11      | 1         | 1.27%   |
| Unknown | 1         | 1.27%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 29        | 36.71%  |
| 501-600        | 13        | 16.46%  |
| 201-300        | 13        | 16.46%  |
| 401-500        | 10        | 12.66%  |
| 351-400        | 7         | 8.86%   |
| 1501-2000      | 3         | 3.8%    |
| 1001-1500      | 2         | 2.53%   |
| More than 2000 | 1         | 1.27%   |
| Unknown        | 1         | 1.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 55        | 70.51%  |
| 16/10   | 12        | 15.38%  |
| 5/4     | 3         | 3.85%   |
| 4/3     | 3         | 3.85%   |
| 1.96    | 2         | 2.56%   |
| 3/2     | 1         | 1.28%   |
| 1.00    | 1         | 1.28%   |
| Unknown | 1         | 1.28%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 17        | 21.52%  |
| 201-250        | 13        | 16.46%  |
| 81-90          | 11        | 13.92%  |
| 151-200        | 6         | 7.59%   |
| 121-130        | 6         | 7.59%   |
| 71-80          | 5         | 6.33%   |
| 141-150        | 5         | 6.33%   |
| More than 1000 | 4         | 5.06%   |
| 41-50          | 3         | 3.8%    |
| 301-350        | 2         | 2.53%   |
| 501-1000       | 2         | 2.53%   |
| 61-70          | 1         | 1.27%   |
| 51-60          | 1         | 1.27%   |
| 131-140        | 1         | 1.27%   |
| 91-100         | 1         | 1.27%   |
| Unknown        | 1         | 1.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 27        | 35.06%  |
| 101-120 | 24        | 31.17%  |
| 121-160 | 18        | 23.38%  |
| 1-50    | 6         | 7.79%   |
| 161-240 | 1         | 1.3%    |
| Unknown | 1         | 1.3%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 75        | 90.36%  |
| 2     | 5         | 6.02%   |
| 0     | 3         | 3.61%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 35        | 30.7%   |
| Realtek Semiconductor    | 34        | 29.82%  |
| Qualcomm Atheros         | 12        | 10.53%  |
| Broadcom                 | 8         | 7.02%   |
| Marvell Technology Group | 4         | 3.51%   |
| Broadcom Limited         | 4         | 3.51%   |
| TP-Link                  | 3         | 2.63%   |
| Ralink Technology        | 3         | 2.63%   |
| Nvidia                   | 3         | 2.63%   |
| Ralink                   | 2         | 1.75%   |
| VIA Technologies         | 1         | 0.88%   |
| Samsung Electronics      | 1         | 0.88%   |
| OPPO Electronics         | 1         | 0.88%   |
| NetGear                  | 1         | 0.88%   |
| Edimax Technology        | 1         | 0.88%   |
| D-Link System            | 1         | 0.88%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 22        | 16.42%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 7         | 5.22%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 5         | 3.73%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 2.24%   |
| Intel Wireless 7265                                                     | 3         | 2.24%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 2.24%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.49%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 1.49%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 2         | 1.49%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.49%   |
| Nvidia MCP61 Ethernet                                                   | 2         | 1.49%   |
| Intel Wireless 8260                                                     | 2         | 1.49%   |
| Intel Wireless 7260                                                     | 2         | 1.49%   |
| Intel Wi-Fi 6 AX200                                                     | 2         | 1.49%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 1.49%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 1.49%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                        | 2         | 1.49%   |
| VIA VT6102/VT6103 [Rhine-II]                                            | 1         | 0.75%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 1         | 0.75%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                     | 1         | 0.75%   |
| TP-Link 802.11ac WLAN Adapter                                           | 1         | 0.75%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 1         | 0.75%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 0.75%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.75%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.75%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.75%   |
| Realtek Killer E2600 GbE Controller                                     | 1         | 0.75%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 0.75%   |
| Ralink RT3072 Wireless Adapter                                          | 1         | 0.75%   |
| Ralink MT7601U Wireless Adapter                                         | 1         | 0.75%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.75%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.75%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 0.75%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 0.75%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 1         | 0.75%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller               | 1         | 0.75%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1         | 0.75%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 0.75%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 0.75%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 1         | 0.75%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 27        | 43.55%  |
| Qualcomm Atheros         | 10        | 16.13%  |
| Realtek Semiconductor    | 9         | 14.52%  |
| TP-Link                  | 3         | 4.84%   |
| Ralink Technology        | 3         | 4.84%   |
| Ralink                   | 2         | 3.23%   |
| Broadcom Limited         | 2         | 3.23%   |
| Broadcom                 | 2         | 3.23%   |
| NetGear                  | 1         | 1.61%   |
| Marvell Technology Group | 1         | 1.61%   |
| Edimax Technology        | 1         | 1.61%   |
| D-Link System            | 1         | 1.61%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 3         | 4.84%   |
| Intel Wireless 7265                                                           | 3         | 4.84%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 3         | 4.84%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 2         | 3.23%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 2         | 3.23%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 2         | 3.23%   |
| Intel Wireless 8260                                                           | 2         | 3.23%   |
| Intel Wireless 7260                                                           | 2         | 3.23%   |
| Intel Wi-Fi 6 AX200                                                           | 2         | 3.23%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 2         | 3.23%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 2         | 3.23%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 1         | 1.61%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                           | 1         | 1.61%   |
| TP-Link 802.11ac WLAN Adapter                                                 | 1         | 1.61%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 1         | 1.61%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 1         | 1.61%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 1         | 1.61%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 1         | 1.61%   |
| Ralink RT5370 Wireless Adapter                                                | 1         | 1.61%   |
| Ralink RT3072 Wireless Adapter                                                | 1         | 1.61%   |
| Ralink MT7601U Wireless Adapter                                               | 1         | 1.61%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                     | 1         | 1.61%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                     | 1         | 1.61%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 1         | 1.61%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 1         | 1.61%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1         | 1.61%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 1         | 1.61%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 1         | 1.61%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 1.61%   |
| NetGear WNDA4100 802.11abgn 3x3:3 [Ralink RT3573]                             | 1         | 1.61%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                             | 1         | 1.61%   |
| Intel Wireless 3165                                                           | 1         | 1.61%   |
| Intel WiFi Link 5100                                                          | 1         | 1.61%   |
| Intel Wi-Fi 6 AX201                                                           | 1         | 1.61%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                       | 1         | 1.61%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                 | 1         | 1.61%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1         | 1.61%   |
| Intel Centrino Wireless-N 2230                                                | 1         | 1.61%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                  | 1         | 1.61%   |
| Intel Centrino Ultimate-N 6300                                                | 1         | 1.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 30        | 41.67%  |
| Intel                    | 19        | 26.39%  |
| Broadcom                 | 7         | 9.72%   |
| Qualcomm Atheros         | 5         | 6.94%   |
| Nvidia                   | 3         | 4.17%   |
| Marvell Technology Group | 3         | 4.17%   |
| Broadcom Limited         | 2         | 2.78%   |
| VIA Technologies         | 1         | 1.39%   |
| Samsung Electronics      | 1         | 1.39%   |
| OPPO Electronics         | 1         | 1.39%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 22        | 30.56%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 7         | 9.72%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 5         | 6.94%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 2         | 2.78%   |
| Nvidia MCP61 Ethernet                                                  | 2         | 2.78%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                       | 2         | 2.78%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 1         | 1.39%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1         | 1.39%   |
| Realtek Killer E2600 GbE Controller                                    | 1         | 1.39%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 1.39%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1         | 1.39%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 1.39%   |
| OPPO SM8350-IDP _SN:361A1B3C                                           | 1         | 1.39%   |
| Nvidia MCP51 Ethernet Controller                                       | 1         | 1.39%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 1         | 1.39%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                | 1         | 1.39%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 1         | 1.39%   |
| Intel I211 Gigabit Network Connection                                  | 1         | 1.39%   |
| Intel Ethernet Controller I225-V                                       | 1         | 1.39%   |
| Intel Ethernet Connection I219-LM                                      | 1         | 1.39%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 1.39%   |
| Intel Ethernet Connection (6) I219-V                                   | 1         | 1.39%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1         | 1.39%   |
| Intel Ethernet Connection (2) I218-V                                   | 1         | 1.39%   |
| Intel Ethernet Connection (2) I218-LM                                  | 1         | 1.39%   |
| Intel 82578DC Gigabit Network Connection                               | 1         | 1.39%   |
| Intel 82577LM Gigabit Network Connection                               | 1         | 1.39%   |
| Intel 82573L Gigabit Ethernet Controller                               | 1         | 1.39%   |
| Intel 82566MM Gigabit Network Connection                               | 1         | 1.39%   |
| Intel 82566DM Gigabit Network Connection                               | 1         | 1.39%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                   | 1         | 1.39%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 1         | 1.39%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                | 1         | 1.39%   |
| Broadcom NetXtreme BCM5721 Gigabit Ethernet PCI Express                | 1         | 1.39%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                 | 1         | 1.39%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 1         | 1.39%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe               | 1         | 1.39%   |
| Broadcom Limited NetLink BCM57788 Gigabit Ethernet PCIe                | 1         | 1.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 70        | 54.26%  |
| WiFi     | 59        | 45.74%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 47        | 54.02%  |
| Ethernet | 40        | 45.98%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 40        | 48.19%  |
| 1     | 39        | 46.99%  |
| 0     | 3         | 3.61%   |
| 3     | 1         | 1.2%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 70        | 82.35%  |
| Yes  | 15        | 17.65%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 16        | 37.21%  |
| Broadcom                        | 6         | 13.95%  |
| Realtek Semiconductor           | 3         | 6.98%   |
| IMC Networks                    | 3         | 6.98%   |
| Qualcomm Atheros Communications | 2         | 4.65%   |
| Cambridge Silicon Radio         | 2         | 4.65%   |
| Apple                           | 2         | 4.65%   |
| Taiyo Yuden                     | 1         | 2.33%   |
| Realtek                         | 1         | 2.33%   |
| Ralink                          | 1         | 2.33%   |
| Marvell Semiconductor           | 1         | 2.33%   |
| Hewlett-Packard                 | 1         | 2.33%   |
| Foxconn / Hon Hai               | 1         | 2.33%   |
| Dynex                           | 1         | 2.33%   |
| Dell                            | 1         | 2.33%   |
| ASUSTek Computer                | 1         | 2.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                       | 8         | 18.6%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 3         | 6.98%   |
| IMC Networks Bluetooth Radio                             | 3         | 6.98%   |
| Realtek  Bluetooth 4.2 Adapter                           | 2         | 4.65%   |
| Intel AX200 Bluetooth                                    | 2         | 4.65%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 2         | 4.65%   |
| Broadcom BCM2045 Bluetooth                               | 2         | 4.65%   |
| Taiyo Yuden Bluetooth Device (V2.0+EDR)                  | 1         | 2.33%   |
| Realtek RTL8723B Bluetooth                               | 1         | 2.33%   |
| Realtek Bluetooth Radio                                  | 1         | 2.33%   |
| Ralink RT3290 Bluetooth                                  | 1         | 2.33%   |
| Qualcomm Atheros  Bluetooth Device                       | 1         | 2.33%   |
| Qualcomm Atheros Bluetooth                               | 1         | 2.33%   |
| Marvell Bluetooth and Wireless LAN Composite             | 1         | 2.33%   |
| Intel Wireless-AC 3168 Bluetooth                         | 1         | 2.33%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 1         | 2.33%   |
| Intel AX201 Bluetooth                                    | 1         | 2.33%   |
| HP Broadcom 2070 Bluetooth Combo                         | 1         | 2.33%   |
| Foxconn / Hon Hai Bluetooth Device                       | 1         | 2.33%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 1         | 2.33%   |
| Dell Wireless 365 Bluetooth                              | 1         | 2.33%   |
| Broadcom HP Portable SoftSailing                         | 1         | 2.33%   |
| Broadcom BCM43142A0 Bluetooth Device                     | 1         | 2.33%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]               | 1         | 2.33%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]         | 1         | 2.33%   |
| ASUS Broadcom Bluetooth 2.1                              | 1         | 2.33%   |
| Apple Bluetooth USB Host Controller                      | 1         | 2.33%   |
| Apple Bluetooth HCI                                      | 1         | 2.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 57        | 57.58%  |
| AMD                 | 21        | 21.21%  |
| Nvidia              | 13        | 13.13%  |
| C-Media Electronics | 2         | 2.02%   |
| VIA Technologies    | 1         | 1.01%   |
| Plantronics         | 1         | 1.01%   |
| Native Instruments  | 1         | 1.01%   |
| Focusrite-Novation  | 1         | 1.01%   |
| Creative Labs       | 1         | 1.01%   |
| ASUSTek Computer    | 1         | 1.01%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 8         | 7.02%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 7         | 6.14%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 6         | 5.26%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 5         | 4.39%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 3.51%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 4         | 3.51%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 3.51%   |
| AMD FCH Azalia Controller                                                                         | 4         | 3.51%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 3         | 2.63%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 2.63%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 2.63%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 2.63%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 3         | 2.63%   |
| Nvidia MCP61 High Definition Audio                                                                | 2         | 1.75%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 1.75%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 1.75%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 2         | 1.75%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1.75%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 1.75%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 2         | 1.75%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 2         | 1.75%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 1.75%   |
| AMD Navi 10 HDMI Audio                                                                            | 2         | 1.75%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 1.75%   |
| AMD Barts HDMI Audio [Radeon HD 6790/6850/6870 / 7720 OEM]                                        | 2         | 1.75%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1         | 0.88%   |
| Plantronics USB DSP v4 Audio Interface                                                            | 1         | 0.88%   |
| Nvidia MCP51 High Definition Audio                                                                | 1         | 0.88%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.88%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.88%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.88%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.88%   |
| Native Instruments KOMPLETE KONTROL M32                                                           | 1         | 0.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 0.88%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 0.88%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 0.88%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 1         | 0.88%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 0.88%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 1         | 0.88%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 1         | 0.88%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 16        | 22.86%  |
| Unknown             | 15        | 21.43%  |
| SK hynix            | 8         | 11.43%  |
| Kingston            | 6         | 8.57%   |
| Micron Technology   | 5         | 7.14%   |
| G.Skill             | 3         | 4.29%   |
| Crucial             | 3         | 4.29%   |
| Corsair             | 3         | 4.29%   |
| Nanya Technology    | 2         | 2.86%   |
| Unifosa             | 1         | 1.43%   |
| Toshiba             | 1         | 1.43%   |
| Team                | 1         | 1.43%   |
| Ramaxel Technology  | 1         | 1.43%   |
| High Bridge         | 1         | 1.43%   |
| GOODRAM             | 1         | 1.43%   |
| Elpida              | 1         | 1.43%   |
| Avant               | 1         | 1.43%   |
| Unknown             | 1         | 1.43%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s              | 2         | 2.63%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                   | 2         | 2.63%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s   | 2         | 2.63%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s   | 2         | 2.63%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 3200MT/s    | 2         | 2.63%   |
| Samsung RAM K4E8E324EB-EGCF 2GB LPDDR3 1867MT/s          | 2         | 2.63%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                     | 1         | 1.32%   |
| Unknown RAM Module 2GB SODIMM SDRAM                      | 1         | 1.32%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s              | 1         | 1.32%   |
| Unknown RAM Module 2GB SODIMM DDR2 266MT/s               | 1         | 1.32%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                | 1         | 1.32%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                 | 1         | 1.32%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                 | 1         | 1.32%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s              | 1         | 1.32%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s               | 1         | 1.32%   |
| Unknown RAM Module 1024MB SODIMM DDR2                    | 1         | 1.32%   |
| Unknown RAM Module 1024MB SODIMM 800MT/s                 | 1         | 1.32%   |
| Unknown RAM Module 1024MB DIMM SDRAM                     | 1         | 1.32%   |
| Unifosa RAM GU512303EP0202 2048MB DIMM DDR3 1333MT/s     | 1         | 1.32%   |
| Toshiba RAM 9905474-012.A00LF 2GB DIMM DDR3 1333MT/s     | 1         | 1.32%   |
| Team RAM TEAMGROUP-SD4-3200 8GB SODIMM DDR4 3200MT/s     | 1         | 1.32%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1066MT/s             | 1         | 1.32%   |
| SK hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s     | 1         | 1.32%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s   | 1         | 1.32%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s  | 1         | 1.32%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s   | 1         | 1.32%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s              | 1         | 1.32%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s    | 1         | 1.32%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s | 1         | 1.32%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s    | 1         | 1.32%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s    | 1         | 1.32%   |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1334MT/s    | 1         | 1.32%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s    | 1         | 1.32%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s    | 1         | 1.32%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s    | 1         | 1.32%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s    | 1         | 1.32%   |
| Samsung RAM M393A2K40BB1-CRC 16GB DIMM DDR4 2400MT/s     | 1         | 1.32%   |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR2 1867MT/s      | 1         | 1.32%   |
| Samsung RAM M3 78T5663EH3-CF7 2GB DIMM DDR2 800MT/s      | 1         | 1.32%   |
| Samsung RAM M3 78T2863RZS-CE6 1GB DIMM DDR2 667MT/s      | 1         | 1.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 30        | 49.18%  |
| DDR4    | 14        | 22.95%  |
| DDR2    | 6         | 9.84%   |
| SDRAM   | 4         | 6.56%   |
| Unknown | 4         | 6.56%   |
| LPDDR3  | 2         | 3.28%   |
| DDR     | 1         | 1.64%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 36        | 61.02%  |
| DIMM         | 20        | 33.9%   |
| Unknown      | 2         | 3.39%   |
| Row Of Chips | 1         | 1.69%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 2048  | 23        | 31.94%  |
| 8192  | 18        | 25%     |
| 4096  | 17        | 23.61%  |
| 1024  | 7         | 9.72%   |
| 16384 | 5         | 6.94%   |
| 32768 | 1         | 1.39%   |
| 256   | 1         | 1.39%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 14        | 20.9%   |
| 1333    | 11        | 16.42%  |
| 3200    | 6         | 8.96%   |
| 2667    | 6         | 8.96%   |
| 800     | 6         | 8.96%   |
| 1867    | 3         | 4.48%   |
| 1334    | 3         | 4.48%   |
| 1066    | 3         | 4.48%   |
| Unknown | 3         | 4.48%   |
| 2400    | 2         | 2.99%   |
| 4199    | 1         | 1.49%   |
| 3666    | 1         | 1.49%   |
| 2666    | 1         | 1.49%   |
| 2133    | 1         | 1.49%   |
| 2048    | 1         | 1.49%   |
| 1800    | 1         | 1.49%   |
| 1639    | 1         | 1.49%   |
| 667     | 1         | 1.49%   |
| 533     | 1         | 1.49%   |
| 266     | 1         | 1.49%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Samsung CLP-325 Color Laser Printer | 1         | 100%    |

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
| Chicony Electronics                    | 12        | 26.09%  |
| Microdia                               | 5         | 10.87%  |
| Suyin                                  | 4         | 8.7%    |
| Cheng Uei Precision Industry (Foxlink) | 4         | 8.7%    |
| Bison Electronics                      | 3         | 6.52%   |
| Alcor Micro                            | 3         | 6.52%   |
| Sunplus Innovation Technology          | 2         | 4.35%   |
| Quanta                                 | 2         | 4.35%   |
| Logitech                               | 2         | 4.35%   |
| Z-Star Microelectronics                | 1         | 2.17%   |
| Sonix Technology                       | 1         | 2.17%   |
| Samsung Electronics                    | 1         | 2.17%   |
| Realtek Semiconductor                  | 1         | 2.17%   |
| Microsoft                              | 1         | 2.17%   |
| JOURIST-DC80                           | 1         | 2.17%   |
| Guillemot                              | 1         | 2.17%   |
| Apple                                  | 1         | 2.17%   |
| Acer                                   | 1         | 2.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Alcor Micro USB 2.0 Camera                                      | 3         | 6.52%   |
| Chicony HD WebCam                                               | 2         | 4.35%   |
| Z-Star Namuga 1.3M Webcam                                       | 1         | 2.17%   |
| Suyin USB2.0 UVC 1.3M WebCam                                    | 1         | 2.17%   |
| Suyin HP Truevision HD                                          | 1         | 2.17%   |
| Suyin Acer CrystalEye Webcam                                    | 1         | 2.17%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)     | 1         | 2.17%   |
| Sunplus Integrated Webcam                                       | 1         | 2.17%   |
| Sunplus HP HD Webcam [Fixed]                                    | 1         | 2.17%   |
| Sonix USB2.0 HD UVC WebCam                                      | 1         | 2.17%   |
| Samsung Galaxy series, misc. (MTP mode)                         | 1         | 2.17%   |
| Realtek Integrated Webcam                                       | 1         | 2.17%   |
| Quanta HP TrueVision HD Camera                                  | 1         | 2.17%   |
| Quanta HD User Facing                                           | 1         | 2.17%   |
| Microsoft LifeCam Cinema                                        | 1         | 2.17%   |
| Microdia Sonix USB 2.0 Camera                                   | 1         | 2.17%   |
| Microdia Lenovo EasyCamera                                      | 1         | 2.17%   |
| Microdia Laptop_Integrated_Webcam_HD                            | 1         | 2.17%   |
| Microdia Laptop_Integrated_Webcam_1.3M                          | 1         | 2.17%   |
| Microdia ASUS USB2.0 Camera                                     | 1         | 2.17%   |
| Logitech Webcam C270                                            | 1         | 2.17%   |
| Logitech QuickCam Notebook Pro                                  | 1         | 2.17%   |
| JOURIST-DC80 JOURIST-DC80                                       | 1         | 2.17%   |
| Guillemot Hercules Dualpix Exchange                             | 1         | 2.17%   |
| Chicony TOSHIBA Web Camera - HD                                 | 1         | 2.17%   |
| Chicony thinkpad t430s camera                                   | 1         | 2.17%   |
| Chicony Integrated Camera (1280x720@30)                         | 1         | 2.17%   |
| Chicony HP Webcam-101                                           | 1         | 2.17%   |
| Chicony HP Webcam [2 MP Macro]                                  | 1         | 2.17%   |
| Chicony HP TrueVision HD Camera                                 | 1         | 2.17%   |
| Chicony HP Truevision HD                                        | 1         | 2.17%   |
| Chicony HP HD Webcam                                            | 1         | 2.17%   |
| Chicony Asus Integrated 0.3M UVC Webcam                         | 1         | 2.17%   |
| Chicony 2.0M UVC Webcam / CNF7129                               | 1         | 2.17%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 1         | 2.17%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam                | 1         | 2.17%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera             | 1         | 2.17%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera                | 1         | 2.17%   |
| Bison USB HD Webcam                                             | 1         | 2.17%   |
| Bison Lenovo EasyCamera                                         | 1         | 2.17%   |

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
| Lenovo   | 1         | 50%     |
| Broadcom | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Lenovo Integrated Smart Card Reader                                          | 1         | 50%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 56        | 67.47%  |
| 1     | 22        | 26.51%  |
| 2     | 5         | 6.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 9         | 27.27%  |
| Fingerprint reader    | 7         | 21.21%  |
| Net/wireless          | 6         | 18.18%  |
| Multimedia controller | 5         | 15.15%  |
| Chipcard              | 2         | 6.06%   |
| Bluetooth             | 2         | 6.06%   |
| Unassigned class      | 1         | 3.03%   |
| Camera                | 1         | 3.03%   |

