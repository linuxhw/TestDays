Siduction - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Siduction.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Siduction/Desktop/README.md) and [notebooks](/Dist/Siduction/Notebook/README.md).

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

Total: 105

| Vendor  | Model                       | Form-Factor | Probe                                                      | Date         |
|---------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo  | ThinkPad T14s Gen 1 20T1... | Notebook    | [3936c99d1e](https://linux-hardware.org/?probe=3936c99d1e) | Mar 25, 2024 |
| Lenovo  | ThinkPad T470 W10DG 20JN... | Notebook    | [df52747427](https://linux-hardware.org/?probe=df52747427) | Jan 22, 2024 |
| HP      | 250 G7 Notebook PC          | Notebook    | [3b58774e8d](https://linux-hardware.org/?probe=3b58774e8d) | Jan 15, 2024 |
| Lenovo  | ThinkPad T470 W10DG 20JN... | Notebook    | [d17724d57c](https://linux-hardware.org/?probe=d17724d57c) | Jan 11, 2024 |
| ASUSTek | BU201LA                     | Notebook    | [2985f7a222](https://linux-hardware.org/?probe=2985f7a222) | Dec 22, 2023 |
| Lenovo  | ThinkPad T580 20LAS1GG00    | Notebook    | [c592d82494](https://linux-hardware.org/?probe=c592d82494) | Dec 05, 2023 |
| Lenovo  | ThinkPad L540 20AUS01H00    | Notebook    | [6bdb162853](https://linux-hardware.org/?probe=6bdb162853) | Nov 29, 2023 |
| Lenovo  | ThinkPad T490 20N3SFKX00    | Notebook    | [9d5bc38102](https://linux-hardware.org/?probe=9d5bc38102) | Nov 29, 2023 |
| HP      | 250 G7 Notebook PC          | Notebook    | [64d7d103a5](https://linux-hardware.org/?probe=64d7d103a5) | Oct 24, 2023 |
| HP      | 250 G7 Notebook PC          | Notebook    | [91d0aa5397](https://linux-hardware.org/?probe=91d0aa5397) | Oct 10, 2023 |
| HP      | 250 G7 Notebook PC          | Notebook    | [c2123c4f21](https://linux-hardware.org/?probe=c2123c4f21) | Oct 10, 2023 |
| Dell    | 0KC9NP A01                  | Desktop     | [15e1733eb4](https://linux-hardware.org/?probe=15e1733eb4) | Sep 20, 2023 |
| HP      | 250 G7 Notebook PC          | Notebook    | [428177914f](https://linux-hardware.org/?probe=428177914f) | Sep 17, 2023 |
| HP      | 250 G7 Notebook PC          | Notebook    | [f2b0e180d4](https://linux-hardware.org/?probe=f2b0e180d4) | Aug 27, 2023 |
| Dell    | 0T7D40 A01                  | Desktop     | [19c877cd88](https://linux-hardware.org/?probe=19c877cd88) | Jul 31, 2023 |
| Intel   | NUC7i5DNB J57626-509        | Mini pc     | [fdc2de43bb](https://linux-hardware.org/?probe=fdc2de43bb) | Jul 31, 2023 |
| Dell    | 0T7D40 A01                  | Desktop     | [c1b5a5f99b](https://linux-hardware.org/?probe=c1b5a5f99b) | Jul 08, 2023 |
| Intel   | NUC7i5DNB J57626-509        | Mini pc     | [a8ee980594](https://linux-hardware.org/?probe=a8ee980594) | Jun 28, 2023 |
| HP      | ZBook 15 G6                 | Notebook    | [eb23ebb0b8](https://linux-hardware.org/?probe=eb23ebb0b8) | Jun 10, 2023 |
| Apple   | MacBookPro9,2               | Notebook    | [baf92c8b36](https://linux-hardware.org/?probe=baf92c8b36) | Jun 08, 2023 |
| Dell    | 0T7D40 A01                  | Desktop     | [0c0dc06847](https://linux-hardware.org/?probe=0c0dc06847) | May 31, 2023 |
| HP      | 250 G7 Notebook PC          | Notebook    | [2f0f83bda2](https://linux-hardware.org/?probe=2f0f83bda2) | May 25, 2023 |
| HP      | ProBook 640 G1              | Notebook    | [5dceebaf6c](https://linux-hardware.org/?probe=5dceebaf6c) | May 13, 2023 |
| Dell    | Vostro 15 3510              | Notebook    | [fc82fe9907](https://linux-hardware.org/?probe=fc82fe9907) | May 11, 2023 |
| Dell    | 0JP3NX A00                  | Desktop     | [974cb924d5](https://linux-hardware.org/?probe=974cb924d5) | May 08, 2023 |
| Dell    | 0T7D40 A01                  | Desktop     | [7ce0658b0f](https://linux-hardware.org/?probe=7ce0658b0f) | Apr 29, 2023 |
| Dell    | Latitude 5491               | Notebook    | [ef97e6890a](https://linux-hardware.org/?probe=ef97e6890a) | Apr 13, 2023 |
| Lenovo  | 36F7 SDK0J40700 WIN 3258... | Desktop     | [ea50bc5d28](https://linux-hardware.org/?probe=ea50bc5d28) | Apr 13, 2023 |
| Dell    | Inspiron 7415 2-in-1        | Convertible | [b65f6a101f](https://linux-hardware.org/?probe=b65f6a101f) | Apr 12, 2023 |
| Dell    | 0T7D40 A01                  | Desktop     | [11aee4ed7b](https://linux-hardware.org/?probe=11aee4ed7b) | Apr 08, 2023 |
| ASUSTek | X751LAB                     | Notebook    | [03465bed03](https://linux-hardware.org/?probe=03465bed03) | Apr 06, 2023 |
| HP      | ProBook 640 G1              | Notebook    | [5aa6a42aa2](https://linux-hardware.org/?probe=5aa6a42aa2) | Mar 29, 2023 |
| Acer    | Swift SF314-51              | Notebook    | [5a73818024](https://linux-hardware.org/?probe=5a73818024) | Mar 27, 2023 |
| Dell    | 0T7D40 A01                  | Desktop     | [9320ecf2b2](https://linux-hardware.org/?probe=9320ecf2b2) | Mar 25, 2023 |
| Lenovo  | 3746 WIN SDK0T76463 3422... | All in one  | [ec07bb84cf](https://linux-hardware.org/?probe=ec07bb84cf) | Mar 25, 2023 |
| Lenovo  | ThinkPad X1 Carbon 5th 2... | Notebook    | [0c7e919608](https://linux-hardware.org/?probe=0c7e919608) | Mar 20, 2023 |
| NEWSMAY | Unknown                     | Desktop     | [c4cab7022b](https://linux-hardware.org/?probe=c4cab7022b) | Mar 15, 2023 |
| Acer    | Aspire E5-551G              | Notebook    | [58703e3260](https://linux-hardware.org/?probe=58703e3260) | Mar 15, 2023 |
| ASUSTek | ROG STRIX B550-A GAMING     | Desktop     | [c215f0cf02](https://linux-hardware.org/?probe=c215f0cf02) | Mar 14, 2023 |
| Lenovo  | ThinkPad X1 Tablet Gen 2... | Tablet      | [149c782883](https://linux-hardware.org/?probe=149c782883) | Mar 08, 2023 |
| Intel   | NUC7i5DNB J57626-509        | Mini pc     | [f38b8db522](https://linux-hardware.org/?probe=f38b8db522) | Mar 06, 2023 |
| ASRock  | B550 Steel Legend           | Desktop     | [d533a64cb9](https://linux-hardware.org/?probe=d533a64cb9) | Mar 04, 2023 |
| Lenovo  | ThinkPad X1 Carbon 5th 2... | Notebook    | [5c39a363d8](https://linux-hardware.org/?probe=5c39a363d8) | Feb 28, 2023 |
| ASUSTek | ROG STRIX B550-A GAMING     | Desktop     | [eeafe897ae](https://linux-hardware.org/?probe=eeafe897ae) | Feb 09, 2023 |
| HP      | EliteBook 865 16 inch G9... | Notebook    | [49a4e66cd0](https://linux-hardware.org/?probe=49a4e66cd0) | Feb 05, 2023 |
| Dell    | 0T7D40 A01                  | Desktop     | [74207a9fec](https://linux-hardware.org/?probe=74207a9fec) | Dec 19, 2022 |
| HP      | 212B                        | Desktop     | [55f34c27ec](https://linux-hardware.org/?probe=55f34c27ec) | Oct 08, 2022 |
| ASUSTek | ROG STRIX B550-A GAMING     | Desktop     | [b1514ab047](https://linux-hardware.org/?probe=b1514ab047) | Oct 02, 2022 |
| Acer    | Aspire V5-471               | Notebook    | [fe551b92a5](https://linux-hardware.org/?probe=fe551b92a5) | Oct 02, 2022 |
| ASUSTek | ET2411_W8                   | All in one  | [e0ef691738](https://linux-hardware.org/?probe=e0ef691738) | Oct 02, 2022 |
| Dell    | 0T7D40 A01                  | Desktop     | [9eba047248](https://linux-hardware.org/?probe=9eba047248) | Sep 18, 2022 |
| Dell    | 0T7D40 A01                  | Desktop     | [0968e0629e](https://linux-hardware.org/?probe=0968e0629e) | Aug 31, 2022 |
| Acer    | Aspire A515-55              | Notebook    | [bed4db4cf3](https://linux-hardware.org/?probe=bed4db4cf3) | Jul 16, 2022 |
| Dell    | 0T7D40 A01                  | Desktop     | [42b1694c97](https://linux-hardware.org/?probe=42b1694c97) | Jul 01, 2022 |
| Dell    | Inspiron 7415 2-in-1        | Convertible | [2521a61389](https://linux-hardware.org/?probe=2521a61389) | Jun 11, 2022 |
| ASUSTek | ROG STRIX B450-F GAMING     | Desktop     | [3766ac4bad](https://linux-hardware.org/?probe=3766ac4bad) | May 27, 2022 |
| MSI     | MPG B550 GAMING PLUS        | Desktop     | [5600c7649a](https://linux-hardware.org/?probe=5600c7649a) | Apr 05, 2022 |
| Acer    | Aspire E5-771G              | Notebook    | [a765f92826](https://linux-hardware.org/?probe=a765f92826) | Mar 28, 2022 |
| ASUSTek | B150M-A/M.2                 | Desktop     | [3098c1fdf3](https://linux-hardware.org/?probe=3098c1fdf3) | Feb 09, 2022 |
| HP      | 8703                        | Desktop     | [11bdfccc66](https://linux-hardware.org/?probe=11bdfccc66) | Feb 04, 2022 |
| Lenovo  | ThinkPad T410 253725G       | Notebook    | [3e1c463980](https://linux-hardware.org/?probe=3e1c463980) | Jan 16, 2022 |
| Lenovo  | IdeaPad 3 15IIL05 81WE      | Notebook    | [7fa0610547](https://linux-hardware.org/?probe=7fa0610547) | Jan 02, 2022 |
| ASUSTek | ROG STRIX B550-A GAMING     | Desktop     | [80bb463c02](https://linux-hardware.org/?probe=80bb463c02) | Dec 30, 2021 |
| Dell    | 0T7D40 A01                  | Desktop     | [065636c444](https://linux-hardware.org/?probe=065636c444) | Nov 25, 2021 |
| MSI     | MPG B550 GAMING PLUS        | Desktop     | [e3b8f92aa4](https://linux-hardware.org/?probe=e3b8f92aa4) | Sep 27, 2021 |
| Lenovo  | ThinkPad E590 20NB001AIX    | Notebook    | [436614e885](https://linux-hardware.org/?probe=436614e885) | Sep 26, 2021 |
| ASUSTek | B150M-A/M.2                 | Desktop     | [8c936491c0](https://linux-hardware.org/?probe=8c936491c0) | Sep 23, 2021 |
| ASUSTek | B150M-A/M.2                 | Desktop     | [1c6a203e2f](https://linux-hardware.org/?probe=1c6a203e2f) | Sep 16, 2021 |
| ASUSTek | ROG STRIX Z370-F GAMING     | Desktop     | [cdf90072fd](https://linux-hardware.org/?probe=cdf90072fd) | Aug 21, 2021 |
| Dell    | 0T7D40 A01                  | Desktop     | [0728097100](https://linux-hardware.org/?probe=0728097100) | Aug 06, 2021 |
| Lenovo  | ThinkPad T410 253725G       | Notebook    | [65b842202c](https://linux-hardware.org/?probe=65b842202c) | Aug 06, 2021 |
| ASUSTek | B150M-A/M.2                 | Desktop     | [8b033c463e](https://linux-hardware.org/?probe=8b033c463e) | Aug 06, 2021 |
| ASRock  | B450 Pro4                   | Desktop     | [68f4f90fd0](https://linux-hardware.org/?probe=68f4f90fd0) | Aug 05, 2021 |
| MSI     | MPG B550 GAMING PLUS        | Desktop     | [0ce1757e83](https://linux-hardware.org/?probe=0ce1757e83) | Aug 05, 2021 |
| ASUSTek | ROG STRIX B450-F GAMING     | Desktop     | [78924b9791](https://linux-hardware.org/?probe=78924b9791) | Aug 05, 2021 |
| ASUSTek | ROG STRIX B450-F GAMING     | Desktop     | [cc17fc0f36](https://linux-hardware.org/?probe=cc17fc0f36) | Aug 05, 2021 |
| ASUSTek | ZenBook UX325JA_UX325JA     | Notebook    | [70ddebc8cc](https://linux-hardware.org/?probe=70ddebc8cc) | Jul 25, 2021 |
| ASUSTek | ZenBook UX325JA_UX325JA     | Notebook    | [455c830431](https://linux-hardware.org/?probe=455c830431) | Jul 25, 2021 |
| TUXEDO  | Book BA1510                 | Notebook    | [80b8c9719c](https://linux-hardware.org/?probe=80b8c9719c) | Jul 11, 2021 |
| HP      | ProBook 4520s               | Notebook    | [50b007f51d](https://linux-hardware.org/?probe=50b007f51d) | Jun 26, 2021 |
| MSI     | MPG B550 GAMING PLUS        | Desktop     | [fcd7305b92](https://linux-hardware.org/?probe=fcd7305b92) | Jun 25, 2021 |
| Dell    | 0T7D40 A01                  | Desktop     | [5ee785eb32](https://linux-hardware.org/?probe=5ee785eb32) | Jun 24, 2021 |
| HP      | ProBook 4520s               | Notebook    | [261b02ab53](https://linux-hardware.org/?probe=261b02ab53) | Jun 20, 2021 |
| MSI     | MPG B550 GAMING PLUS        | Desktop     | [681bafbc6a](https://linux-hardware.org/?probe=681bafbc6a) | May 13, 2021 |
| HP      | Laptop 17-ca1xxx            | Notebook    | [99f175055d](https://linux-hardware.org/?probe=99f175055d) | May 05, 2021 |
| ASUSTek | ROG STRIX Z370-F GAMING     | Desktop     | [9fa9842ec9](https://linux-hardware.org/?probe=9fa9842ec9) | May 01, 2021 |
| HP      | Laptop 17-ca1xxx            | Notebook    | [e21ac181a5](https://linux-hardware.org/?probe=e21ac181a5) | Apr 03, 2021 |
| HP      | Laptop 17-ca1xxx            | Notebook    | [a8a82ba1b9](https://linux-hardware.org/?probe=a8a82ba1b9) | Mar 01, 2021 |
| HP      | Laptop 17-ca1xxx            | Notebook    | [a3ea535d80](https://linux-hardware.org/?probe=a3ea535d80) | Feb 04, 2021 |
| HP      | Laptop 17-ca1xxx            | Notebook    | [d88b363f5e](https://linux-hardware.org/?probe=d88b363f5e) | Jan 19, 2021 |
| HP      | Laptop 17-ca1xxx            | Notebook    | [5e6eb88969](https://linux-hardware.org/?probe=5e6eb88969) | Jan 02, 2021 |
| HP      | Laptop 17-ca1xxx            | Notebook    | [09675fa9a5](https://linux-hardware.org/?probe=09675fa9a5) | Dec 09, 2020 |
| HP      | Laptop 17-ca1xxx            | Notebook    | [0779e6ce28](https://linux-hardware.org/?probe=0779e6ce28) | Nov 18, 2020 |
| ASUSTek | PRIME Z270-A                | Desktop     | [894f4ade05](https://linux-hardware.org/?probe=894f4ade05) | Oct 02, 2020 |
| HP      | Laptop 17-ca1xxx            | Notebook    | [386583ebea](https://linux-hardware.org/?probe=386583ebea) | Sep 02, 2020 |
| HP      | 250 G7 Notebook PC          | Notebook    | [52a48bdcb8](https://linux-hardware.org/?probe=52a48bdcb8) | Aug 02, 2020 |
| ASUSTek | ROG STRIX Z370-F GAMING     | Desktop     | [7db0b1474d](https://linux-hardware.org/?probe=7db0b1474d) | Jun 18, 2020 |
| ASUSTek | ROG STRIX B450-F GAMING     | Desktop     | [70ab783420](https://linux-hardware.org/?probe=70ab783420) | Apr 07, 2020 |
| Lenovo  | ThinkPad E590 20NB001AIX    | Notebook    | [bc066bdf30](https://linux-hardware.org/?probe=bc066bdf30) | Feb 11, 2020 |
| HP      | Laptop 15-db0xxx            | Notebook    | [f6d4378d90](https://linux-hardware.org/?probe=f6d4378d90) | Jan 03, 2020 |
| Compal  | NBLBX                       | Notebook    | [865da8f6a9](https://linux-hardware.org/?probe=865da8f6a9) | Dec 05, 2019 |
| Lenovo  | ThinkPad Edge E540 20C60... | Notebook    | [552827c68a](https://linux-hardware.org/?probe=552827c68a) | Nov 20, 2019 |
| Lenovo  | ThinkPad Edge E540 20C60... | Notebook    | [d942b46e5b](https://linux-hardware.org/?probe=d942b46e5b) | Nov 20, 2019 |
| Lenovo  | ThinkPad Edge E540 20C60... | Notebook    | [17f6c8b364](https://linux-hardware.org/?probe=17f6c8b364) | Nov 20, 2019 |
| Acer    | Aspire 5750                 | Notebook    | [62afcd020e](https://linux-hardware.org/?probe=62afcd020e) | Feb 26, 2019 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Siduction 12       | 19        | 32.76%  |
| Siduction 11       | 14        | 24.14%  |
| Siduction Unstable | 11        | 18.97%  |
| Siduction          | 8         | 13.79%  |
| Siduction 10       | 5         | 8.62%   |
| Siduction 21       | 1         | 1.72%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| Siduction | 45        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                       | Computers | Percent |
|-------------------------------|-----------|---------|
| 6.2.6-1-siduction-amd64       | 4         | 4.71%   |
| 6.2.8-1-siduction-amd64       | 3         | 3.53%   |
| 5.13.8-1-siduction-amd64      | 3         | 3.53%   |
| 6.5.3-1-siduction-amd64       | 2         | 2.35%   |
| 6.2.2-6-siduction-amd64       | 2         | 2.35%   |
| 6.2.15-1-siduction-amd64      | 2         | 2.35%   |
| 6.2.13-1-siduction-amd64      | 2         | 2.35%   |
| 6.2.10-1-siduction-amd64      | 2         | 2.35%   |
| 6.1.14-1-siduction-amd64      | 2         | 2.35%   |
| 5.13.6-1-siduction-amd64      | 2         | 2.35%   |
| 5.12.12-1-siduction-amd64     | 2         | 2.35%   |
| 6.7.10-1-siduction-amd64      | 1         | 1.18%   |
| 6.6.8-1-siduction-amd64       | 1         | 1.18%   |
| 6.6.4-1-siduction-amd64       | 1         | 1.18%   |
| 6.6.2-1-siduction-amd64       | 1         | 1.18%   |
| 6.6.10-1-siduction-amd64      | 1         | 1.18%   |
| 6.5.6-1-siduction-amd64       | 1         | 1.18%   |
| 6.5.2-1-siduction-amd64       | 1         | 1.18%   |
| 6.4.12-1-siduction-amd64      | 1         | 1.18%   |
| 6.3.7-1-siduction-amd64       | 1         | 1.18%   |
| 6.3.3-1-siduction-amd64       | 1         | 1.18%   |
| 6.3.10-1-siduction-amd64      | 1         | 1.18%   |
| 6.2.2-3-siduction-amd64       | 1         | 1.18%   |
| 6.2.11-1-siduction-amd64      | 1         | 1.18%   |
| 6.2.0-rc6-siduction-amd64     | 1         | 1.18%   |
| 6.1.10-2-siduction-amd64      | 1         | 1.18%   |
| 6.1.1-4-siduction-amd64       | 1         | 1.18%   |
| 6.0.9-1-siduction-amd64       | 1         | 1.18%   |
| 5.9.8-towo.3-siduction-amd64  | 1         | 1.18%   |
| 5.9.13-towo.1-siduction-amd64 | 1         | 1.18%   |
| 5.8.5-towo.1-siduction-amd64  | 1         | 1.18%   |
| 5.8.12-towo.1-siduction-amd64 | 1         | 1.18%   |
| 5.7.2-towo.1-siduction-amd64  | 1         | 1.18%   |
| 5.7.11-towo.2-siduction-amd64 | 1         | 1.18%   |
| 5.6.2-towo.1-siduction-amd64  | 1         | 1.18%   |
| 5.4.5-towo.2-siduction-amd64  | 1         | 1.18%   |
| 5.4.18-towo.1-siduction-amd64 | 1         | 1.18%   |
| 5.3.12-towo.2-siduction-amd64 | 1         | 1.18%   |
| 5.3.1-towo.2-siduction-amd64  | 1         | 1.18%   |
| 5.19.5-2-siduction-amd64      | 1         | 1.18%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.2.6   | 4         | 4.71%   |
| 6.2.8   | 3         | 3.53%   |
| 6.2.2   | 3         | 3.53%   |
| 5.13.8  | 3         | 3.53%   |
| 6.5.3   | 2         | 2.35%   |
| 6.2.15  | 2         | 2.35%   |
| 6.2.13  | 2         | 2.35%   |
| 6.2.10  | 2         | 2.35%   |
| 6.1.14  | 2         | 2.35%   |
| 5.14.0  | 2         | 2.35%   |
| 5.13.6  | 2         | 2.35%   |
| 5.12.12 | 2         | 2.35%   |
| 6.7.10  | 1         | 1.18%   |
| 6.6.8   | 1         | 1.18%   |
| 6.6.4   | 1         | 1.18%   |
| 6.6.2   | 1         | 1.18%   |
| 6.6.10  | 1         | 1.18%   |
| 6.5.6   | 1         | 1.18%   |
| 6.5.2   | 1         | 1.18%   |
| 6.4.12  | 1         | 1.18%   |
| 6.3.7   | 1         | 1.18%   |
| 6.3.3   | 1         | 1.18%   |
| 6.3.10  | 1         | 1.18%   |
| 6.2.11  | 1         | 1.18%   |
| 6.2.0   | 1         | 1.18%   |
| 6.1.10  | 1         | 1.18%   |
| 6.1.1   | 1         | 1.18%   |
| 6.0.9   | 1         | 1.18%   |
| 5.9.8   | 1         | 1.18%   |
| 5.9.13  | 1         | 1.18%   |
| 5.8.5   | 1         | 1.18%   |
| 5.8.12  | 1         | 1.18%   |
| 5.7.2   | 1         | 1.18%   |
| 5.7.11  | 1         | 1.18%   |
| 5.6.2   | 1         | 1.18%   |
| 5.4.5   | 1         | 1.18%   |
| 5.4.18  | 1         | 1.18%   |
| 5.3.12  | 1         | 1.18%   |
| 5.3.1   | 1         | 1.18%   |
| 5.19.5  | 1         | 1.18%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.2     | 16        | 21.33%  |
| 5.13    | 8         | 10.67%  |
| 6.6     | 4         | 5.33%   |
| 6.1     | 4         | 5.33%   |
| 5.16    | 4         | 5.33%   |
| 5.12    | 4         | 5.33%   |
| 6.5     | 3         | 4%      |
| 6.3     | 3         | 4%      |
| 5.19    | 3         | 4%      |
| 5.18    | 3         | 4%      |
| 5.15    | 3         | 4%      |
| 5.14    | 3         | 4%      |
| 5.8     | 2         | 2.67%   |
| 5.7     | 2         | 2.67%   |
| 5.4     | 2         | 2.67%   |
| 5.3     | 2         | 2.67%   |
| 5.10    | 2         | 2.67%   |
| 6.7     | 1         | 1.33%   |
| 6.4     | 1         | 1.33%   |
| 6.0     | 1         | 1.33%   |
| 5.9     | 1         | 1.33%   |
| 5.6     | 1         | 1.33%   |
| 5.11    | 1         | 1.33%   |
| 4.20    | 1         | 1.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 45        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KDE5            | 33        | 64.71%  |
| XFCE            | 5         | 9.8%    |
| Unknown         | 4         | 7.84%   |
| X-Cinnamon      | 3         | 5.88%   |
| LXQt            | 3         | 5.88%   |
| GNOME Flashback | 1         | 1.96%   |
| Cinnamon        | 1         | 1.96%   |
| Budgie          | 1         | 1.96%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 37        | 77.08%  |
| Wayland | 9         | 18.75%  |
| Tty     | 2         | 4.17%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 34        | 69.39%  |
| Unknown | 10        | 20.41%  |
| LightDM | 2         | 4.08%   |
| TDM     | 1         | 2.04%   |
| GDM3    | 1         | 2.04%   |
| GDM     | 1         | 2.04%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| de_DE   | 20        | 41.67%  |
| en_US   | 13        | 27.08%  |
| Unknown | 4         | 8.33%   |
| en_GB   | 3         | 6.25%   |
| it_IT   | 2         | 4.17%   |
| de_AT   | 2         | 4.17%   |
| fr_FR   | 1         | 2.08%   |
| en_CA   | 1         | 2.08%   |
| de_CH   | 1         | 2.08%   |
| C       | 1         | 2.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 34        | 73.91%  |
| BIOS | 12        | 26.09%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 36        | 76.6%   |
| Btrfs   | 9         | 19.15%  |
| Overlay | 1         | 2.13%   |
| Unknown | 1         | 2.13%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 32        | 69.57%  |
| Unknown | 9         | 19.57%  |
| MBR     | 5         | 10.87%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 42        | 91.3%   |
| Yes       | 4         | 8.7%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 35        | 76.09%  |
| Yes       | 11        | 23.91%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Lenovo           | 12        | 26.67%  |
| Hewlett-Packard  | 9         | 20%     |
| ASUSTek Computer | 7         | 15.56%  |
| Dell             | 6         | 13.33%  |
| Acer             | 4         | 8.89%   |
| ASRock           | 2         | 4.44%   |
| TUXEDO           | 1         | 2.22%   |
| NEWSMAY          | 1         | 2.22%   |
| MSI              | 1         | 2.22%   |
| Intel            | 1         | 2.22%   |
| Compal           | 1         | 2.22%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| TUXEDO Book BA1510                         | 1         | 2.22%   |
| MSI MS-7C56                                | 1         | 2.22%   |
| Lenovo ThinkPad X1 Tablet Gen 2 20JCA016JP | 1         | 2.22%   |
| Lenovo ThinkPad X1 Carbon 5th 20HRCTO1WW   | 1         | 2.22%   |
| Lenovo ThinkPad T580 20LAS1GG00            | 1         | 2.22%   |
| Lenovo ThinkPad T490 20N3SFKX00            | 1         | 2.22%   |
| Lenovo ThinkPad T410 253725G               | 1         | 2.22%   |
| Lenovo ThinkPad T14s Gen 1 20T1S15N00      | 1         | 2.22%   |
| Lenovo ThinkPad L540 20AUS01H00            | 1         | 2.22%   |
| Lenovo ThinkPad Edge E540 20C6003AGE       | 1         | 2.22%   |
| Lenovo ThinkPad E590 20NB001AIX            | 1         | 2.22%   |
| Lenovo IdeaPad 3 15IIL05 81WE              | 1         | 2.22%   |
| Lenovo IdeaCentre AIO 3 27ALC6 F0FY0055GE  | 1         | 2.22%   |
| Lenovo IdeaCentre 310S-08ASR 90G9006DIX    | 1         | 2.22%   |
| Intel NUC7i5DNKE                           | 1         | 2.22%   |
| HP ZBook 15 G6                             | 1         | 2.22%   |
| HP Z440 Workstation                        | 1         | 2.22%   |
| HP ProBook 640 G1                          | 1         | 2.22%   |
| HP ProBook 4520s                           | 1         | 2.22%   |
| HP OMEN 30L Desktop GT13-0xxx              | 1         | 2.22%   |
| HP Laptop 17-ca1xxx                        | 1         | 2.22%   |
| HP Laptop 15-db0xxx                        | 1         | 2.22%   |
| HP EliteBook 865 16 inch G9 Notebook PC    | 1         | 2.22%   |
| HP 250 G7 Notebook PC                      | 1         | 2.22%   |
| Dell Vostro 15 3510                        | 1         | 2.22%   |
| Dell OptiPlex 9020                         | 1         | 2.22%   |
| Dell OptiPlex 5040                         | 1         | 2.22%   |
| Dell OptiPlex 3050                         | 1         | 2.22%   |
| Dell Latitude 5491                         | 1         | 2.22%   |
| Dell Inspiron 7415 2-in-1                  | 1         | 2.22%   |
| Compal NBLBX                               | 1         | 2.22%   |
| ASUS ZenBook UX325JA_UX325JA               | 1         | 2.22%   |
| ASUS ROG STRIX Z370-F GAMING               | 1         | 2.22%   |
| ASUS ROG STRIX B550-A GAMING               | 1         | 2.22%   |
| ASUS PRIME Z270-A                          | 1         | 2.22%   |
| ASUS BU201LA                               | 1         | 2.22%   |
| ASUS B150M-A/M.2                           | 1         | 2.22%   |
| ASUS A0000001                              | 1         | 2.22%   |
| ASRock B550 Steel Legend                   | 1         | 2.22%   |
| ASRock B450 Pro4                           | 1         | 2.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 9         | 20%     |
| Dell OptiPlex     | 3         | 6.67%   |
| Acer Aspire       | 3         | 6.67%   |
| Lenovo IdeaCentre | 2         | 4.44%   |
| HP ProBook        | 2         | 4.44%   |
| HP Laptop         | 2         | 4.44%   |
| ASUS ROG          | 2         | 4.44%   |
| TUXEDO Book       | 1         | 2.22%   |
| MSI MS-7C56       | 1         | 2.22%   |
| Lenovo IdeaPad    | 1         | 2.22%   |
| Intel NUC7i5DNKE  | 1         | 2.22%   |
| HP ZBook          | 1         | 2.22%   |
| HP Z440           | 1         | 2.22%   |
| HP OMEN           | 1         | 2.22%   |
| HP EliteBook      | 1         | 2.22%   |
| HP 250            | 1         | 2.22%   |
| Dell Vostro       | 1         | 2.22%   |
| Dell Latitude     | 1         | 2.22%   |
| Dell Inspiron     | 1         | 2.22%   |
| Compal NBLBX      | 1         | 2.22%   |
| ASUS ZenBook      | 1         | 2.22%   |
| ASUS PRIME        | 1         | 2.22%   |
| ASUS BU201LA      | 1         | 2.22%   |
| ASUS B150M-A      | 1         | 2.22%   |
| ASUS A0000001     | 1         | 2.22%   |
| ASRock B550       | 1         | 2.22%   |
| ASRock B450       | 1         | 2.22%   |
| Acer Swift        | 1         | 2.22%   |
| Unknown           | 1         | 2.22%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 8         | 17.78%  |
| 2019 | 6         | 13.33%  |
| 2018 | 5         | 11.11%  |
| 2021 | 4         | 8.89%   |
| 2017 | 4         | 8.89%   |
| 2014 | 4         | 8.89%   |
| 2016 | 3         | 6.67%   |
| 2013 | 3         | 6.67%   |
| 2022 | 2         | 4.44%   |
| 2015 | 2         | 4.44%   |
| 2010 | 2         | 4.44%   |
| 2011 | 1         | 2.22%   |
| 2009 | 1         | 2.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 26        | 57.78%  |
| Desktop     | 15        | 33.33%  |
| Tablet      | 1         | 2.22%   |
| Convertible | 1         | 2.22%   |
| Mini pc     | 1         | 2.22%   |
| All in one  | 1         | 2.22%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 45        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 45        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 13        | 28.26%  |
| 4.01-8.0    | 11        | 23.91%  |
| 8.01-16.0   | 10        | 21.74%  |
| 32.01-64.0  | 9         | 19.57%  |
| 3.01-4.0    | 1         | 2.17%   |
| 64.01-256.0 | 1         | 2.17%   |
| Unknown     | 1         | 2.17%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 16        | 26.23%  |
| 3.01-4.0   | 14        | 22.95%  |
| 2.01-3.0   | 14        | 22.95%  |
| 1.01-2.0   | 7         | 11.48%  |
| 8.01-16.0  | 4         | 6.56%   |
| 0.51-1.0   | 3         | 4.92%   |
| 16.01-24.0 | 1         | 1.64%   |
| 0.01-0.5   | 1         | 1.64%   |
| Unknown    | 1         | 1.64%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 27        | 57.45%  |
| 2      | 10        | 21.28%  |
| 4      | 5         | 10.64%  |
| 3      | 3         | 6.38%   |
| 6      | 1         | 2.13%   |
| 5      | 1         | 2.13%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 30        | 63.83%  |
| Yes       | 17        | 36.17%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 40        | 88.89%  |
| No        | 5         | 11.11%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 36        | 80%     |
| No        | 9         | 20%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 30        | 62.5%   |
| No        | 18        | 37.5%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Germany     | 20        | 42.55%  |
| USA         | 7         | 14.89%  |
| Austria     | 4         | 8.51%   |
| UK          | 3         | 6.38%   |
| Italy       | 3         | 6.38%   |
| Canada      | 3         | 6.38%   |
| Sweden      | 2         | 4.26%   |
| Switzerland | 1         | 2.13%   |
| Netherlands | 1         | 2.13%   |
| Japan       | 1         | 2.13%   |
| Israel      | 1         | 2.13%   |
| France      | 1         | 2.13%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City            | Computers | Percent |
|-----------------|-----------|---------|
| Munich          | 5         | 7.81%   |
| Vienna          | 3         | 4.69%   |
| Berlin          | 3         | 4.69%   |
| Suisun          | 2         | 3.13%   |
| Stuttgart       | 2         | 3.13%   |
| Stockholm       | 2         | 3.13%   |
| Schrobenhausen  | 2         | 3.13%   |
| Zurich          | 1         | 1.56%   |
| Wiener Neustadt | 1         | 1.56%   |
| Unterbergla     | 1         | 1.56%   |
| Turin           | 1         | 1.56%   |
| Trier           | 1         | 1.56%   |
| Toronto         | 1         | 1.56%   |
| Tokyo           | 1         | 1.56%   |
| Sidney          | 1         | 1.56%   |
| Savannah        | 1         | 1.56%   |
| Sanford         | 1         | 1.56%   |
| San Francisco   | 1         | 1.56%   |
| Salzburg        | 1         | 1.56%   |
| Reading         | 1         | 1.56%   |
| Portland        | 1         | 1.56%   |
| Piea            | 1         | 1.56%   |
| Paris           | 1         | 1.56%   |
| Papenburg       | 1         | 1.56%   |
| Oranienburg     | 1         | 1.56%   |
| Oberboihingen   | 1         | 1.56%   |
| Mittenwald      | 1         | 1.56%   |
| Milan           | 1         | 1.56%   |
| Merseburg       | 1         | 1.56%   |
| Mannheim        | 1         | 1.56%   |
| Malmo           | 1         | 1.56%   |
| Leipzig         | 1         | 1.56%   |
| Langewiesen     | 1         | 1.56%   |
| Landau          | 1         | 1.56%   |
| Kensington      | 1         | 1.56%   |
| Jerusalem       | 1         | 1.56%   |
| Iserlohn        | 1         | 1.56%   |
| Innsbruck       | 1         | 1.56%   |
| Hamburg         | 1         | 1.56%   |
| Guglingen       | 1         | 1.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 15        | 25     | 19.74%  |
| WDC                 | 12        | 29     | 15.79%  |
| Seagate             | 8         | 17     | 10.53%  |
| Toshiba             | 7         | 16     | 9.21%   |
| SanDisk             | 6         | 12     | 7.89%   |
| SK hynix            | 5         | 14     | 6.58%   |
| Kingston            | 5         | 5      | 6.58%   |
| Crucial             | 5         | 17     | 6.58%   |
| Intel               | 3         | 7      | 3.95%   |
| Unknown             | 1         | 1      | 1.32%   |
| SSSTC               | 1         | 1      | 1.32%   |
| Silicon Motion      | 1         | 1      | 1.32%   |
| OCZ                 | 1         | 3      | 1.32%   |
| Mushkin             | 1         | 3      | 1.32%   |
| Micron Technology   | 1         | 1      | 1.32%   |
| Lenovo              | 1         | 1      | 1.32%   |
| HGST                | 1         | 11     | 1.32%   |
| GRITRONIX           | 1         | 1      | 1.32%   |
| Corsair             | 1         | 3      | 1.32%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| WDC WD10JPVX-22JC3T0 1TB                          | 3         | 3.49%   |
| Toshiba MQ04ABF100 1TB                            | 2         | 2.33%   |
| SanDisk NVMe SSD Drive 1TB                        | 2         | 2.33%   |
| Samsung SSD 850 EVO 250GB                         | 2         | 2.33%   |
| Kingston SA400S37240G 240GB SSD                   | 2         | 2.33%   |
| Crucial CT500MX500SSD1 500GB                      | 2         | 2.33%   |
| Crucial CT1000MX500SSD1 1TB                       | 2         | 2.33%   |
| WDC WDS400T2B0A-00SM50 4TB SSD                    | 1         | 1.16%   |
| WDC WDS200T2B0B-00YS70 2TB SSD                    | 1         | 1.16%   |
| WDC WDS100T2B0C-00PXH0 1TB                        | 1         | 1.16%   |
| WDC WD60EZAZ-00SF3B0 6TB                          | 1         | 1.16%   |
| WDC WD40EZAZ-00SF3B0 4TB                          | 1         | 1.16%   |
| WDC WD20EZRZ-00Z5HB0 2TB                          | 1         | 1.16%   |
| WDC WD20EFRX-68EUZN0 2TB                          | 1         | 1.16%   |
| WDC WD10SPZX-60Z10T0 1TB                          | 1         | 1.16%   |
| WDC WD10JPVX-60JC3T1 1TB                          | 1         | 1.16%   |
| WDC WD10EADX-00TDHB0 1TB                          | 1         | 1.16%   |
| WDC WD BLACK SDBPNTY-512G-1106 512GB              | 1         | 1.16%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB              | 1         | 1.16%   |
| Unknown MMC Card  64GB                            | 1         | 1.16%   |
| Toshiba THNSNK256GVN8 256GB SSD                   | 1         | 1.16%   |
| Toshiba THNSF5512GPUK 512GB                       | 1         | 1.16%   |
| Toshiba RD400 256GB                               | 1         | 1.16%   |
| Toshiba MQ01ACF032 320GB                          | 1         | 1.16%   |
| Toshiba KBG30ZMT256G 256GB                        | 1         | 1.16%   |
| SSSTC CL4-3D256-Q11 NVMe 256GB                    | 1         | 1.16%   |
| SK hynix SKHynix_HFS256GD9TNG-L5B0B 256GB         | 1         | 1.16%   |
| SK hynix SC308 SATA 128GB SSD                     | 1         | 1.16%   |
| SK hynix NVMe SSD Drive 512GB                     | 1         | 1.16%   |
| SK hynix BC711 NVMe 1TB                           | 1         | 1.16%   |
| SK hynix BC501 HFM256GDJTNG-8310A 256GB           | 1         | 1.16%   |
| Silicon Motion SM2262/SM2262EN SSD Controller 2TB | 1         | 1.16%   |
| Seagate ST9640320AS 640GB                         | 1         | 1.16%   |
| Seagate ST9500420AS 500GB                         | 1         | 1.16%   |
| Seagate ST6000DM003-2CY186 6TB                    | 1         | 1.16%   |
| Seagate ST500LT012-1DG142 500GB                   | 1         | 1.16%   |
| Seagate ST4000LM016-1N2170 4TB                    | 1         | 1.16%   |
| Seagate ST32000542AS 2TB                          | 1         | 1.16%   |
| Seagate ST31000524AS 1TB                          | 1         | 1.16%   |
| Seagate ST3000VN000-1HJ166 3TB                    | 1         | 1.16%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 9         | 20     | 40.91%  |
| Seagate             | 8         | 17     | 36.36%  |
| Toshiba             | 3         | 11     | 13.64%  |
| Samsung Electronics | 1         | 1      | 4.55%   |
| HGST                | 1         | 11     | 4.55%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 18     | 34.62%  |
| Crucial             | 5         | 16     | 19.23%  |
| Kingston            | 4         | 4      | 15.38%  |
| WDC                 | 2         | 2      | 7.69%   |
| SanDisk             | 2         | 4      | 7.69%   |
| Toshiba             | 1         | 1      | 3.85%   |
| SK hynix            | 1         | 9      | 3.85%   |
| OCZ                 | 1         | 3      | 3.85%   |
| GRITRONIX           | 1         | 1      | 3.85%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 26        | 49     | 39.39%  |
| SSD  | 21        | 58     | 31.82%  |
| HDD  | 18        | 60     | 27.27%  |
| MMC  | 1         | 1      | 1.52%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 31        | 118    | 53.45%  |
| NVMe | 26        | 49     | 44.83%  |
| MMC  | 1         | 1      | 1.72%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 19        | 48     | 45.24%  |
| 0.51-1.0   | 11        | 32     | 26.19%  |
| 1.01-2.0   | 6         | 19     | 14.29%  |
| 3.01-4.0   | 3         | 14     | 7.14%   |
| 4.01-10.0  | 2         | 2      | 4.76%   |
| 2.01-3.0   | 1         | 3      | 2.38%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 12        | 24%     |
| 101-250        | 7         | 14%     |
| 1001-2000      | 7         | 14%     |
| More than 3000 | 6         | 12%     |
| 501-1000       | 6         | 12%     |
| Unknown        | 5         | 10%     |
| 1-20           | 3         | 6%      |
| 2001-3000      | 2         | 4%      |
| 21-50          | 1         | 2%      |
| 51-100         | 1         | 2%      |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 17        | 29.31%  |
| 51-100         | 8         | 13.79%  |
| 101-250        | 7         | 12.07%  |
| 21-50          | 5         | 8.62%   |
| Unknown        | 5         | 8.62%   |
| 251-500        | 4         | 6.9%    |
| 1001-2000      | 4         | 6.9%    |
| 501-1000       | 4         | 6.9%    |
| More than 3000 | 3         | 5.17%   |
| 2001-3000      | 1         | 1.72%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                   | Computers | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| WDC WD20EZRZ-00Z5HB0 2TB                | 1         | 6      | 11.11%  |
| SK hynix SC308 SATA 128GB SSD           | 1         | 9      | 11.11%  |
| SK hynix BC501 HFM256GDJTNG-8310A 256GB | 1         | 1      | 11.11%  |
| Seagate ST32000542AS 2TB                | 1         | 3      | 11.11%  |
| Samsung Electronics SSD 870 EVO 4TB     | 1         | 1      | 11.11%  |
| OCZ VERTEX3 120GB SSD                   | 1         | 3      | 11.11%  |
| Kingston SA400S37240G 240GB SSD         | 1         | 1      | 11.11%  |
| HGST HTS725050A7E630 500GB              | 1         | 11     | 11.11%  |
| Crucial CT500MX500SSD1 500GB            | 1         | 1      | 11.11%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| SK hynix            | 2         | 10     | 22.22%  |
| WDC                 | 1         | 6      | 11.11%  |
| Seagate             | 1         | 3      | 11.11%  |
| Samsung Electronics | 1         | 1      | 11.11%  |
| OCZ                 | 1         | 3      | 11.11%  |
| Kingston            | 1         | 1      | 11.11%  |
| HGST                | 1         | 11     | 11.11%  |
| Crucial             | 1         | 1      | 11.11%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 6      | 33.33%  |
| Seagate | 1         | 3      | 33.33%  |
| HGST    | 1         | 11     | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 5         | 15     | 55.56%  |
| HDD  | 3         | 20     | 33.33%  |
| NVMe | 1         | 1      | 11.11%  |

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
| Works    | 37        | 108    | 67.27%  |
| Detected | 11        | 24     | 20%     |
| Malfunc  | 7         | 36     | 12.73%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 28        | 42.42%  |
| AMD                            | 12        | 18.18%  |
| SanDisk                        | 6         | 9.09%   |
| SK hynix                       | 4         | 6.06%   |
| Samsung Electronics            | 4         | 6.06%   |
| Toshiba America Info Systems   | 3         | 4.55%   |
| Solid State Storage Technology | 1         | 1.52%   |
| Silicon Motion                 | 1         | 1.52%   |
| Phison Electronics             | 1         | 1.52%   |
| OCZ Technology Group           | 1         | 1.52%   |
| Micron/Crucial Technology      | 1         | 1.52%   |
| Micron Technology              | 1         | 1.52%   |
| Lenovo                         | 1         | 1.52%   |
| Kingston Technology Company    | 1         | 1.52%   |
| ASMedia Technology             | 1         | 1.52%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 9         | 12.5%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 5.56%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 3         | 4.17%   |
| AMD 500 Series Chipset SATA Controller                                         | 3         | 4.17%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)            | 2         | 2.78%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 2         | 2.78%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 2         | 2.78%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 2.78%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 2.78%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 2.78%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 2.78%   |
| AMD 400 Series Chipset SATA Controller                                         | 2         | 2.78%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 1         | 1.39%   |
| Solid State Storage CL4-8D512 NVMe SSD M.2 (DRAM-less)                         | 1         | 1.39%   |
| SK hynix PC601 NVMe Solid State Drive                                          | 1         | 1.39%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 1         | 1.39%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 1         | 1.39%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                          | 1         | 1.39%   |
| SanDisk PC SN735 NVMe SSD (DRAM-less)                                          | 1         | 1.39%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                          | 1         | 1.39%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 1         | 1.39%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1         | 1.39%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 1         | 1.39%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                    | 1         | 1.39%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 1.39%   |
| Phison E7 NVMe Controller                                                      | 1         | 1.39%   |
| OCZ Group RD400/400A SSD                                                       | 1         | 1.39%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton]                                      | 1         | 1.39%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 1         | 1.39%   |
| Lenovo LENSE20256GMSP34MEAT2TA                                                 | 1         | 1.39%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                       | 1         | 1.39%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 1.39%   |
| Intel Tiger Lake-LP SATA Controller                                            | 1         | 1.39%   |
| Intel SSD 665p Series [Neptune Harbor Refresh]                                 | 1         | 1.39%   |
| Intel SSD 660P Series                                                          | 1         | 1.39%   |
| Intel SATA Controller [RAID mode]                                              | 1         | 1.39%   |
| Intel Optane NVME SSD H10 with Solid State Storage [Teton Glacier]             | 1         | 1.39%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 1         | 1.39%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 1         | 1.39%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 1.39%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 35        | 54.69%  |
| NVMe | 25        | 39.06%  |
| RAID | 3         | 4.69%   |
| IDE  | 1         | 1.56%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 32        | 71.11%  |
| AMD    | 13        | 28.89%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 4.44%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 4.44%   |
| AMD Ryzen 5 3600 6-Core Processor             | 2         | 4.44%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 4.44%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz           | 1         | 2.22%   |
| Intel Pentium Silver N6005 @ 2.00GHz          | 1         | 2.22%   |
| Intel Pentium CPU G4400T @ 2.90GHz            | 1         | 2.22%   |
| Intel Core i7-9850H CPU @ 2.60GHz             | 1         | 2.22%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 1         | 2.22%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 1         | 2.22%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 2.22%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz            | 1         | 2.22%   |
| Intel Core i7-10700K CPU @ 3.80GHz            | 1         | 2.22%   |
| Intel Core i7-10610U CPU @ 1.80GHz            | 1         | 2.22%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 1         | 2.22%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 1         | 2.22%   |
| Intel Core i5-7Y54 CPU @ 1.20GHz              | 1         | 2.22%   |
| Intel Core i5-7600K CPU @ 3.80GHz             | 1         | 2.22%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 1         | 2.22%   |
| Intel Core i5-6600K CPU @ 3.50GHz             | 1         | 2.22%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 1         | 2.22%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 2.22%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 2.22%   |
| Intel Core i5-4590S CPU @ 3.00GHz             | 1         | 2.22%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 2.22%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 1         | 2.22%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 1         | 2.22%   |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 1         | 2.22%   |
| Intel Core i5 CPU M 430 @ 2.27GHz             | 1         | 2.22%   |
| Intel Core i3-4000M CPU @ 2.40GHz             | 1         | 2.22%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 1         | 2.22%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 1         | 2.22%   |
| AMD Ryzen 9 PRO 6950HS with Radeon Graphics   | 1         | 2.22%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 1         | 2.22%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 1         | 2.22%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 1         | 2.22%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 1         | 2.22%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 1         | 2.22%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 1         | 2.22%   |
| AMD FX-7500 Radeon R7, 10 Compute Cores 4C+6G | 1         | 2.22%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 17        | 37.78%  |
| Intel Core i7        | 9         | 20%     |
| AMD Ryzen 5          | 7         | 15.56%  |
| Other                | 2         | 4.44%   |
| Intel Core i3        | 2         | 4.44%   |
| AMD Ryzen 9          | 2         | 4.44%   |
| AMD Ryzen 7          | 2         | 4.44%   |
| Intel Xeon           | 1         | 2.22%   |
| Intel Pentium Silver | 1         | 2.22%   |
| Intel Pentium        | 1         | 2.22%   |
| AMD FX               | 1         | 2.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 18        | 40%     |
| 2      | 15        | 33.33%  |
| 6      | 7         | 15.56%  |
| 8      | 4         | 8.89%   |
| 12     | 1         | 2.22%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 45        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 38        | 84.44%  |
| 1      | 7         | 15.56%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 44        | 97.78%  |
| Unknown        | 1         | 2.22%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 21        | 40.38%  |
| 0x08701021 | 3         | 5.77%   |
| 0x806ec    | 2         | 3.85%   |
| 0x706e5    | 2         | 3.85%   |
| 0x506e3    | 2         | 3.85%   |
| 0x20655    | 2         | 3.85%   |
| 0x08108102 | 2         | 3.85%   |
| 0x0800820d | 2         | 3.85%   |
| 0xa0655    | 1         | 1.92%   |
| 0x906ea    | 1         | 1.92%   |
| 0x906e9    | 1         | 1.92%   |
| 0x806eb    | 1         | 1.92%   |
| 0x806e9    | 1         | 1.92%   |
| 0x306f2    | 1         | 1.92%   |
| 0x306d4    | 1         | 1.92%   |
| 0x306c3    | 1         | 1.92%   |
| 0x206a7    | 1         | 1.92%   |
| 0x20652    | 1         | 1.92%   |
| 0x0a404102 | 1         | 1.92%   |
| 0x08608103 | 1         | 1.92%   |
| 0x08108109 | 1         | 1.92%   |
| 0x0810100b | 1         | 1.92%   |
| 0x06006705 | 1         | 1.92%   |
| 0x06003106 | 1         | 1.92%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| KabyLake    | 12        | 26.67%  |
| Haswell     | 6         | 13.33%  |
| Zen+        | 4         | 8.89%   |
| Skylake     | 4         | 8.89%   |
| Zen 2       | 3         | 6.67%   |
| Westmere    | 3         | 6.67%   |
| Unknown     | 3         | 6.67%   |
| IceLake     | 2         | 4.44%   |
| Zen         | 1         | 2.22%   |
| Tremont     | 1         | 2.22%   |
| TigerLake   | 1         | 2.22%   |
| Steamroller | 1         | 2.22%   |
| SandyBridge | 1         | 2.22%   |
| Excavator   | 1         | 2.22%   |
| CometLake   | 1         | 2.22%   |
| Broadwell   | 1         | 2.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 25        | 49.02%  |
| AMD    | 17        | 33.33%  |
| Nvidia | 9         | 17.65%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 3         | 5.66%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 3         | 5.66%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 3         | 5.66%   |
| Intel Iris Plus Graphics G7                                                 | 2         | 3.77%   |
| Intel HD Graphics 620                                                       | 2         | 3.77%   |
| Intel Core Processor Integrated Graphics Controller                         | 2         | 3.77%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2         | 3.77%   |
| AMD Lucienne                                                                | 2         | 3.77%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                               | 1         | 1.89%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1         | 1.89%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1         | 1.89%   |
| Nvidia GM108M [GeForce MX130]                                               | 1         | 1.89%   |
| Nvidia GK208M [GeForce GT 740M]                                             | 1         | 1.89%   |
| Nvidia GK104 [GeForce GTX 770]                                              | 1         | 1.89%   |
| Nvidia GF119 [NVS 310]                                                      | 1         | 1.89%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]        | 1         | 1.89%   |
| Nvidia GA106 [Geforce RTX 3050]                                             | 1         | 1.89%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1         | 1.89%   |
| Intel UHD Graphics 620                                                      | 1         | 1.89%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 1         | 1.89%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 1         | 1.89%   |
| Intel JasperLake [UHD Graphics]                                             | 1         | 1.89%   |
| Intel HD Graphics 615                                                       | 1         | 1.89%   |
| Intel HD Graphics 5500                                                      | 1         | 1.89%   |
| Intel HD Graphics 530                                                       | 1         | 1.89%   |
| Intel HD Graphics 510                                                       | 1         | 1.89%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 1         | 1.89%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 1         | 1.89%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 1         | 1.89%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 1         | 1.89%   |
| AMD Vega 20 [Radeon VII]                                                    | 1         | 1.89%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                    | 1         | 1.89%   |
| AMD RV711/M93 [Mobility Radeon HD 4350/4550/530v/540v/545v / FirePro RG220] | 1         | 1.89%   |
| AMD Rembrandt [Radeon 680M]                                                 | 1         | 1.89%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 1         | 1.89%   |
| AMD Opal XT [Radeon R7 M265/M365X/M465]                                     | 1         | 1.89%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 1         | 1.89%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 1         | 1.89%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 1         | 1.89%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                    | 1         | 1.89%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 21        | 44.68%  |
| 1 x AMD        | 15        | 31.91%  |
| 1 x Nvidia     | 6         | 12.77%  |
| Intel + Nvidia | 3         | 6.38%   |
| 2 x AMD        | 1         | 2.13%   |
| Intel + AMD    | 1         | 2.13%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 41        | 87.23%  |
| Proprietary | 6         | 12.77%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 27        | 55.1%   |
| 0.01-0.5   | 7         | 14.29%  |
| 7.01-8.0   | 4         | 8.16%   |
| 1.01-2.0   | 4         | 8.16%   |
| 8.01-16.0  | 2         | 4.08%   |
| 0.51-1.0   | 2         | 4.08%   |
| 5.01-6.0   | 1         | 2.04%   |
| 3.01-4.0   | 1         | 2.04%   |
| 2.01-3.0   | 1         | 2.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Chimei Innolux      | 9         | 15.52%  |
| LG Display          | 7         | 12.07%  |
| AU Optronics        | 6         | 10.34%  |
| Acer                | 6         | 10.34%  |
| Samsung Electronics | 4         | 6.9%    |
| Hewlett-Packard     | 4         | 6.9%    |
| BOE                 | 4         | 6.9%    |
| Lenovo              | 3         | 5.17%   |
| Dell                | 3         | 5.17%   |
| Philips             | 2         | 3.45%   |
| Goldstar            | 2         | 3.45%   |
| AOC                 | 2         | 3.45%   |
| STD                 | 1         | 1.72%   |
| Sony                | 1         | 1.72%   |
| MSI                 | 1         | 1.72%   |
| Eizo                | 1         | 1.72%   |
| BenQ                | 1         | 1.72%   |
| ASUSTek Computer    | 1         | 1.72%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SyncMaster SAM021E 1680x1050 433x271mm 20.1-inch  | 2         | 3.28%   |
| STD HDMI TV STD00C7 1680x1050 698x392mm 31.5-inch                     | 1         | 1.64%   |
| Sony SAMSUNG SNY5203 1920x540                                         | 1         | 1.64%   |
| Samsung Electronics S27E590 SAM0C5D 1920x1080 598x336mm 27.0-inch     | 1         | 1.64%   |
| Samsung Electronics S27E391 SAM0C15 1920x1080 598x336mm 27.0-inch     | 1         | 1.64%   |
| Samsung Electronics LCD Monitor SDC4244 2160x1440 254x169mm 12.0-inch | 1         | 1.64%   |
| Philips PHL 241P6E PHL08F7 1920x1080 530x300mm 24.0-inch              | 1         | 1.64%   |
| Philips 200V4 PHLC0BF 1600x900 432x240mm 19.5-inch                    | 1         | 1.64%   |
| MSI G241 MSI3BA4 1920x1080 527x296mm 23.8-inch                        | 1         | 1.64%   |
| LG Display LCD Monitor LGD06FF 1920x1080 344x194mm 15.5-inch          | 1         | 1.64%   |
| LG Display LCD Monitor LGD059D 1920x1080 309x174mm 14.0-inch          | 1         | 1.64%   |
| LG Display LCD Monitor LGD051D 1920x1080 309x174mm 14.0-inch          | 1         | 1.64%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch           | 1         | 1.64%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch          | 1         | 1.64%   |
| LG Display LCD Monitor LGD03DE 1600x900 382x215mm 17.3-inch           | 1         | 1.64%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch           | 1         | 1.64%   |
| Lenovo LEN-A-A LENF918 1920x1080 596x335mm 26.9-inch                  | 1         | 1.64%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 1         | 1.64%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x190mm 14.1-inch               | 1         | 1.64%   |
| Hewlett-Packard X27i HPN3678 2560x1440 597x336mm 27.0-inch            | 1         | 1.64%   |
| Hewlett-Packard E243i HPN3463 1920x1200 518x324mm 24.1-inch           | 1         | 1.64%   |
| Hewlett-Packard 27f HPN354B 1920x1080 598x336mm 27.0-inch             | 1         | 1.64%   |
| Hewlett-Packard 27f HPN354A 1920x1080 598x336mm 27.0-inch             | 1         | 1.64%   |
| Hewlett-Packard 23xw HWP318C 1920x1080 509x286mm 23.0-inch            | 1         | 1.64%   |
| Hewlett-Packard 23cw HWP3187 1920x1080 509x286mm 23.0-inch            | 1         | 1.64%   |
| Goldstar W1946 GSM4BCD 1360x768 406x229mm 18.4-inch                   | 1         | 1.64%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch               | 1         | 1.64%   |
| Eizo EV3285 ENC2979 3840x2160 698x393mm 31.5-inch                     | 1         | 1.64%   |
| Dell UP3216Q DEL40C2 3840x2160 700x400mm 31.7-inch                    | 1         | 1.64%   |
| Dell U2415 DELA0BC 1920x1200 518x324mm 24.1-inch                      | 1         | 1.64%   |
| Dell U2414H DELA0B2 1920x1080 527x296mm 23.8-inch                     | 1         | 1.64%   |
| Chimei Innolux LCD Monitor CMN175A 1920x1080 381x214mm 17.2-inch      | 1         | 1.64%   |
| Chimei Innolux LCD Monitor CMN1610 1920x1200 344x215mm 16.0-inch      | 1         | 1.64%   |
| Chimei Innolux LCD Monitor CMN15F6 1920x1080 344x193mm 15.5-inch      | 1         | 1.64%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 1         | 1.64%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 1         | 1.64%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch      | 1         | 1.64%   |
| Chimei Innolux LCD Monitor CMN15C0 1920x1080 344x194mm 15.5-inch      | 1         | 1.64%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 1         | 1.64%   |
| Chimei Innolux LCD Monitor CMN1388 1920x1080 293x165mm 13.2-inch      | 1         | 1.64%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 31        | 58.49%  |
| 1366x768 (WXGA)    | 5         | 9.43%   |
| 3840x2160 (4K)     | 4         | 7.55%   |
| 2560x1440 (QHD)    | 2         | 3.77%   |
| 1680x1050 (WSXGA+) | 2         | 3.77%   |
| 1600x900 (HD+)     | 2         | 3.77%   |
| 3840x1080          | 1         | 1.89%   |
| 3440x1440          | 1         | 1.89%   |
| 2160x1440          | 1         | 1.89%   |
| 1920x540           | 1         | 1.89%   |
| 1920x1200 (WUXGA)  | 1         | 1.89%   |
| 1440x900 (WXGA+)   | 1         | 1.89%   |
| 1360x768           | 1         | 1.89%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 14        | 24.56%  |
| 27      | 8         | 14.04%  |
| 14      | 7         | 12.28%  |
| 23      | 4         | 7.02%   |
| 31      | 3         | 5.26%   |
| 24      | 3         | 5.26%   |
| 20      | 2         | 3.51%   |
| 17      | 2         | 3.51%   |
| 13      | 2         | 3.51%   |
| 12      | 2         | 3.51%   |
| 49      | 1         | 1.75%   |
| 40      | 1         | 1.75%   |
| 34      | 1         | 1.75%   |
| 32      | 1         | 1.75%   |
| 26      | 1         | 1.75%   |
| 21      | 1         | 1.75%   |
| 19      | 1         | 1.75%   |
| 18      | 1         | 1.75%   |
| 16      | 1         | 1.75%   |
| Unknown | 1         | 1.75%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 23        | 43.4%   |
| 501-600     | 14        | 26.42%  |
| 601-700     | 3         | 5.66%   |
| 401-500     | 3         | 5.66%   |
| 201-300     | 3         | 5.66%   |
| 701-800     | 2         | 3.77%   |
| 351-400     | 2         | 3.77%   |
| 801-900     | 1         | 1.89%   |
| 1001-1500   | 1         | 1.89%   |
| Unknown     | 1         | 1.89%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 40        | 81.63%  |
| 16/10 | 5         | 10.2%   |
| 32/9  | 2         | 4.08%   |
| 3/2   | 1         | 2.04%   |
| 21/9  | 1         | 2.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 14        | 25.45%  |
| 301-350        | 9         | 16.36%  |
| 81-90          | 8         | 14.55%  |
| 201-250        | 6         | 10.91%  |
| 351-500        | 4         | 7.27%   |
| 151-200        | 3         | 5.45%   |
| 61-70          | 2         | 3.64%   |
| 121-130        | 2         | 3.64%   |
| 501-1000       | 2         | 3.64%   |
| 71-80          | 1         | 1.82%   |
| 251-300        | 1         | 1.82%   |
| 141-150        | 1         | 1.82%   |
| 111-120        | 1         | 1.82%   |
| Unknown        | 1         | 1.82%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 121-160 | 21        | 40.38%  |
| 51-100  | 16        | 30.77%  |
| 101-120 | 9         | 17.31%  |
| 161-240 | 5         | 9.62%   |
| Unknown | 1         | 1.92%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 36        | 75%     |
| 2     | 9         | 18.75%  |
| 3     | 3         | 6.25%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 30        | 47.62%  |
| Realtek Semiconductor | 22        | 34.92%  |
| Qualcomm Atheros      | 5         | 7.94%   |
| Broadcom              | 3         | 4.76%   |
| Sierra Wireless       | 1         | 1.59%   |
| Qualcomm              | 1         | 1.59%   |
| NetGear               | 1         | 1.59%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 19        | 23.46%  |
| Intel Wi-Fi 6 AX200                                                    | 4         | 4.94%   |
| Intel Wireless 8265 / 8275                                             | 3         | 3.7%    |
| Intel Ethernet Connection (2) I219-V                                   | 3         | 3.7%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 2         | 2.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 2         | 2.47%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 2         | 2.47%   |
| Intel Wireless 7260                                                    | 2         | 2.47%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 2         | 2.47%   |
| Intel Ethernet Connection I217-V                                       | 2         | 2.47%   |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 2.47%   |
| Sierra Wireless EM7430 Qualcomm Snapdragon X7 LTE-A                    | 1         | 1.23%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 1         | 1.23%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 1         | 1.23%   |
| Realtek RTL8723DE Wireless Network Adapter                             | 1         | 1.23%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1         | 1.23%   |
| Realtek 802.11ax WLAN Adapter                                          | 1         | 1.23%   |
| Qualcomm QCNFA765 Wireless Network Adapter                             | 1         | 1.23%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 1         | 1.23%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 1         | 1.23%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)         | 1         | 1.23%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 1         | 1.23%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 1         | 1.23%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]            | 1         | 1.23%   |
| Intel Wireless 7265                                                    | 1         | 1.23%   |
| Intel Wireless 3160                                                    | 1         | 1.23%   |
| Intel Wi-Fi 6 AX201                                                    | 1         | 1.23%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 1         | 1.23%   |
| Intel I211 Gigabit Network Connection                                  | 1         | 1.23%   |
| Intel Ethernet Controller I225-V                                       | 1         | 1.23%   |
| Intel Ethernet Connection I219-LM                                      | 1         | 1.23%   |
| Intel Ethernet Connection I218-V                                       | 1         | 1.23%   |
| Intel Ethernet Connection I217-LM                                      | 1         | 1.23%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1         | 1.23%   |
| Intel Ethernet Connection (6) I219-LM                                  | 1         | 1.23%   |
| Intel Ethernet Connection (2) I218-LM                                  | 1         | 1.23%   |
| Intel Ethernet Connection (10) I219-LM                                 | 1         | 1.23%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 1         | 1.23%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 1         | 1.23%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                           | 1         | 1.23%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 23        | 58.97%  |
| Realtek Semiconductor | 6         | 15.38%  |
| Qualcomm Atheros      | 5         | 12.82%  |
| Broadcom              | 2         | 5.13%   |
| Sierra Wireless       | 1         | 2.56%   |
| Qualcomm              | 1         | 2.56%   |
| NetGear               | 1         | 2.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 4         | 9.76%   |
| Intel Wireless 8265 / 8275                                     | 3         | 7.32%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 2         | 4.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 4.88%   |
| Intel Wireless 7260                                            | 2         | 4.88%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 2         | 4.88%   |
| Sierra Wireless EM7430 Qualcomm Snapdragon X7 LTE-A            | 1         | 2.44%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 1         | 2.44%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 2.44%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 2.44%   |
| Realtek 802.11ax WLAN Adapter                                  | 1         | 2.44%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 1         | 2.44%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 2.44%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 2.44%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 2.44%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 2.44%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 2.44%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]    | 1         | 2.44%   |
| Intel Wireless 7265                                            | 1         | 2.44%   |
| Intel Wireless 3160                                            | 1         | 2.44%   |
| Intel Wi-Fi 6 AX201                                            | 1         | 2.44%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 1         | 2.44%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 2.44%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 2.44%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 1         | 2.44%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 2.44%   |
| Intel Centrino Advanced-N 6235                                 | 1         | 2.44%   |
| Intel Centrino Advanced-N 6200                                 | 1         | 2.44%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 2.44%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 1         | 2.44%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 1         | 2.44%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 1         | 2.44%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 22        | 55%     |
| Intel                 | 17        | 42.5%   |
| Broadcom              | 1         | 2.5%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 19        | 47.5%   |
| Intel Ethernet Connection (2) I219-V                                   | 3         | 7.5%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 2         | 5%      |
| Intel Ethernet Connection I217-V                                       | 2         | 5%      |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 5%      |
| Realtek RTL8125 2.5GbE Controller                                      | 1         | 2.5%    |
| Intel I211 Gigabit Network Connection                                  | 1         | 2.5%    |
| Intel Ethernet Controller I225-V                                       | 1         | 2.5%    |
| Intel Ethernet Connection I219-LM                                      | 1         | 2.5%    |
| Intel Ethernet Connection I218-V                                       | 1         | 2.5%    |
| Intel Ethernet Connection I217-LM                                      | 1         | 2.5%    |
| Intel Ethernet Connection (7) I219-LM                                  | 1         | 2.5%    |
| Intel Ethernet Connection (6) I219-LM                                  | 1         | 2.5%    |
| Intel Ethernet Connection (2) I218-LM                                  | 1         | 2.5%    |
| Intel Ethernet Connection (10) I219-LM                                 | 1         | 2.5%    |
| Intel 82577LM Gigabit Network Connection                               | 1         | 2.5%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 1         | 2.5%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 40        | 53.33%  |
| WiFi     | 35        | 46.67%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 30        | 68.18%  |
| Ethernet | 14        | 31.82%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 26        | 57.78%  |
| 1     | 18        | 40%     |
| 3     | 1         | 2.22%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 36        | 73.47%  |
| Yes  | 13        | 26.53%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 19        | 57.58%  |
| Realtek Semiconductor           | 5         | 15.15%  |
| Lite-On Technology              | 2         | 6.06%   |
| Edimax Technology               | 2         | 6.06%   |
| Cambridge Silicon Radio         | 2         | 6.06%   |
| Qualcomm Atheros Communications | 1         | 3.03%   |
| Foxconn / Hon Hai               | 1         | 3.03%   |
| Broadcom                        | 1         | 3.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)          | 4         | 12.12%  |
| Intel AX200 Bluetooth                                   | 4         | 12.12%  |
| Realtek  Bluetooth 4.2 Adapter                          | 3         | 9.09%   |
| Intel Bluetooth wireless interface                      | 3         | 9.09%   |
| Intel Bluetooth Device                                  | 3         | 9.09%   |
| Intel AX201 Bluetooth                                   | 3         | 9.09%   |
| Realtek Bluetooth Radio                                 | 2         | 6.06%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)     | 2         | 6.06%   |
| Qualcomm Atheros AR3011 Bluetooth                       | 1         | 3.03%   |
| Lite-On Bluetooth Device                                | 1         | 3.03%   |
| Lite-On Atheros AR3012 Bluetooth                        | 1         | 3.03%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                | 1         | 3.03%   |
| Intel Centrino Bluetooth Wireless Transceiver           | 1         | 3.03%   |
| Foxconn / Hon Hai Bluetooth Device                      | 1         | 3.03%   |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter | 1         | 3.03%   |
| Edimax Edimax Bluetooth Adapter                         | 1         | 3.03%   |
| Broadcom HP Portable Bumble Bee                         | 1         | 3.03%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 32        | 50.79%  |
| AMD                     | 17        | 26.98%  |
| Nvidia                  | 5         | 7.94%   |
| C-Media Electronics     | 2         | 3.17%   |
| Astro Gaming            | 2         | 3.17%   |
| SAVITECH                | 1         | 1.59%   |
| Realtek Semiconductor   | 1         | 1.59%   |
| Hewlett-Packard         | 1         | 1.59%   |
| GN Netcom               | 1         | 1.59%   |
| Cambridge Silicon Radio | 1         | 1.59%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 6         | 7.23%   |
| Intel Sunrise Point-LP HD Audio                                            | 5         | 6.02%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4         | 4.82%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4         | 4.82%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 3.61%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 3.61%   |
| Intel 200 Series PCH HD Audio                                              | 3         | 3.61%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3         | 3.61%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3         | 3.61%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 3         | 3.61%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 3         | 3.61%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 2.41%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 2.41%   |
| Intel Cannon Lake PCH cAVS                                                 | 2         | 2.41%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 2.41%   |
| Astro Gaming Astro A50                                                     | 2         | 2.41%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2         | 2.41%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 2         | 2.41%   |
| SAVITECH MX3                                                               | 1         | 1.2%    |
| Realtek Semiconductor USB Audio                                            | 1         | 1.2%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 1.2%    |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 1.2%    |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 1.2%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 1.2%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 1.2%    |
| Intel Jasper Lake HD Audio                                                 | 1         | 1.2%    |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 1.2%    |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 1.2%    |
| Intel Comet Lake PCH cAVS                                                  | 1         | 1.2%    |
| Intel C610/X99 series chipset HD Audio Controller                          | 1         | 1.2%    |
| Intel Broadwell-U Audio Controller                                         | 1         | 1.2%    |
| Intel 8 Series HD Audio Controller                                         | 1         | 1.2%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 1.2%    |
| Hewlett-Packard USB Audio                                                  | 1         | 1.2%    |
| GN Netcom Jabra Link 380                                                   | 1         | 1.2%    |
| Cambridge Silicon Radio Avantree DG80                                      | 1         | 1.2%    |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                              | 1         | 1.2%    |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 1         | 1.2%    |
| AMD Vega 20 HDMI Audio [Radeon VII]                                        | 1         | 1.2%    |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 1         | 1.2%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 11        | 22.92%  |
| Samsung Electronics | 10        | 20.83%  |
| Crucial             | 6         | 12.5%   |
| Kingston            | 5         | 10.42%  |
| G.Skill             | 5         | 10.42%  |
| Micron Technology   | 4         | 8.33%   |
| Nanya Technology    | 2         | 4.17%   |
| Corsair             | 2         | 4.17%   |
| Unknown             | 1         | 2.08%   |
| Ramsta              | 1         | 2.08%   |
| Elpida              | 1         | 2.08%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 2         | 4.08%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 4.08%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                        | 1         | 2.04%   |
| SK hynix RAM HMT451U6DFR8A-PB 4GB DIMM DDR3 1600MT/s             | 1         | 2.04%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 2.04%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 2.04%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 2.04%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 1         | 2.04%   |
| SK hynix RAM HMA81GU6CJR8N-VK 8GB DIMM DDR4 2400MT/s             | 1         | 2.04%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 2.04%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 2.04%   |
| SK hynix RAM H9CCNNNCLGALAR-NUD 8GB Row Of Chips LPDDR3 1867MT/s | 1         | 2.04%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 1         | 2.04%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s         | 1         | 2.04%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 1         | 2.04%   |
| Samsung RAM M471A2K43BB1-CRC 16GB SODIMM DDR4 2400MT/s           | 1         | 2.04%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 2.04%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 2.04%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 1         | 2.04%   |
| Samsung RAM K4UBE3D4AA-MGCL 8GB Row Of Chips LPDDR4 4267MT/s     | 1         | 2.04%   |
| Ramsta RAM 3200MHz-16G 16GB SODIMM DDR4 3200MT/s                 | 1         | 2.04%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s             | 1         | 2.04%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s             | 1         | 2.04%   |
| Micron RAM Module 16GB SODIMM DDR4 3200MT/s                      | 1         | 2.04%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 1         | 2.04%   |
| Micron RAM 4ATF25664HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 1         | 2.04%   |
| Micron RAM ...d 4096MB SODIMM DDR3 1067MT/s                      | 1         | 2.04%   |
| Kingston RAM Module 8GB DIMM DDR4 3200MT/s                       | 1         | 2.04%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s             | 1         | 2.04%   |
| Kingston RAM KHX1600C9S3L/8G 8192MB SODIMM DDR3 1600MT/s         | 1         | 2.04%   |
| Kingston RAM ACR16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s           | 1         | 2.04%   |
| Kingston RAM 99U5663-007.A00G 16GB SODIMM DDR4 2667MT/s          | 1         | 2.04%   |
| G.Skill RAM F4-3600C16-8GTZR 8192MB DIMM DDR4 3600MT/s           | 1         | 2.04%   |
| G.Skill RAM F4-3200C16-16GTZN 16GB DIMM DDR4 3200MT/s            | 1         | 2.04%   |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s           | 1         | 2.04%   |
| G.Skill RAM F4-3000C15-8GRBB 8GB DIMM DDR4 3000MT/s              | 1         | 2.04%   |
| G.Skill RAM F4-2400C15-8GNT 8GB DIMM DDR4 2666MT/s               | 1         | 2.04%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                       | 1         | 2.04%   |
| Crucial RAM CT8G4SFS824A.M8FE 8GB SODIMM DDR4 2667MT/s           | 1         | 2.04%   |
| Crucial RAM CT4G3S1067M.C16FKD 4GB SODIMM DDR3 1066MT/s          | 1         | 2.04%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 27        | 67.5%   |
| DDR3   | 9         | 22.5%   |
| SDRAM  | 1         | 2.5%    |
| LPDDR4 | 1         | 2.5%    |
| LPDDR3 | 1         | 2.5%    |
| DDR5   | 1         | 2.5%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 25        | 62.5%   |
| DIMM         | 12        | 30%     |
| Row Of Chips | 3         | 7.5%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 21        | 47.73%  |
| 4096  | 11        | 25%     |
| 16384 | 10        | 22.73%  |
| 32768 | 1         | 2.27%   |
| 2048  | 1         | 2.27%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 10        | 22.73%  |
| 2667  | 10        | 22.73%  |
| 2400  | 6         | 13.64%  |
| 1600  | 6         | 13.64%  |
| 3600  | 2         | 4.55%   |
| 3000  | 2         | 4.55%   |
| 4800  | 1         | 2.27%   |
| 4267  | 1         | 2.27%   |
| 4199  | 1         | 2.27%   |
| 2666  | 1         | 2.27%   |
| 1867  | 1         | 2.27%   |
| 1334  | 1         | 2.27%   |
| 1067  | 1         | 2.27%   |
| 1066  | 1         | 2.27%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 33.33%  |
| Hewlett-Packard     | 1         | 33.33%  |
| Canon               | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Samsung M2070 Series   | 1         | 33.33%  |
| HP DeskJet 3630 series | 1         | 33.33%  |
| Canon TS8000 series    | 1         | 33.33%  |

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
| Chicony Electronics                    | 10        | 31.25%  |
| Realtek Semiconductor                  | 3         | 9.38%   |
| IMC Networks                           | 3         | 9.38%   |
| Bison Electronics                      | 3         | 9.38%   |
| Microdia                               | 2         | 6.25%   |
| Logitech                               | 2         | 6.25%   |
| WaveRider Communications               | 1         | 3.13%   |
| Suyin                                  | 1         | 3.13%   |
| Silicon Motion                         | 1         | 3.13%   |
| Quanta                                 | 1         | 3.13%   |
| Primax Electronics                     | 1         | 3.13%   |
| Microsoft                              | 1         | 3.13%   |
| Lite-On Technology                     | 1         | 3.13%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 3.13%   |
| A4Tech                                 | 1         | 3.13%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony HD WebCam                                              | 4         | 12.12%  |
| Realtek Integrated_Webcam_HD                                   | 2         | 6.06%   |
| Microdia Integrated_Webcam_HD                                  | 2         | 6.06%   |
| Chicony Integrated Camera                                      | 2         | 6.06%   |
| Bison Integrated Camera                                        | 2         | 6.06%   |
| WaveRider USB Live camera                                      | 1         | 3.03%   |
| Suyin 1.3M HD WebCam                                           | 1         | 3.03%   |
| Silicon Motion USB 2.0 PC Cam                                  | 1         | 3.03%   |
| Realtek FULL HD 1080P Webcam                                   | 1         | 3.03%   |
| Quanta HP Webcam                                               | 1         | 3.03%   |
| Primax Villem                                                  | 1         | 3.03%   |
| Microsoft LifeCam Cinema                                       | 1         | 3.03%   |
| Logitech Webcam C270                                           | 1         | 3.03%   |
| Logitech QuickCam Pro 9000                                     | 1         | 3.03%   |
| Lite-On Integrated Camera                                      | 1         | 3.03%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 1         | 3.03%   |
| IMC Networks SunplusIT Integrated Camera                       | 1         | 3.03%   |
| IMC Networks Integrated Camera                                 | 1         | 3.03%   |
| Chicony USB2.0 HD UVC WebCam                                   | 1         | 3.03%   |
| Chicony HP Webcam                                              | 1         | 3.03%   |
| Chicony HP HD Camera                                           | 1         | 3.03%   |
| Chicony HP 5MP Camera                                          | 1         | 3.03%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 3.03%   |
| Bison SunplusIT Integrated Camera                              | 1         | 3.03%   |
| Bison Integrated IR Camera                                     | 1         | 3.03%   |
| A4Tech REDRAGON Live Camera                                    | 1         | 3.03%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 4         | 44.44%  |
| Synaptics             | 4         | 44.44%  |
| LighTuning Technology | 1         | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader              | 1         | 11.11%  |
| Validity Sensors VFS451 Fingerprint Reader               | 1         | 11.11%  |
| Validity Sensors VFS Fingerprint sensor                  | 1         | 11.11%  |
| Validity Sensors Synaptics WBDI                          | 1         | 11.11%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 1         | 11.11%  |
| Synaptics Metallica MOH Touch Fingerprint Reader         | 1         | 11.11%  |
| Synaptics Metallica MIS Touch Fingerprint Reader         | 1         | 11.11%  |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 11.11%  |
| LighTuning EgisTec Touch Fingerprint Sensor              | 1         | 11.11%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 1         | 50%     |
| Alcor Micro | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Broadcom 5880                       | 1         | 50%     |
| Alcor Micro AU9540 Smartcard Reader | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 32        | 69.57%  |
| 1     | 12        | 26.09%  |
| 2     | 2         | 4.35%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 9         | 56.25%  |
| Chipcard                 | 2         | 12.5%   |
| Unassigned class         | 1         | 6.25%   |
| Sound                    | 1         | 6.25%   |
| Net/wireless             | 1         | 6.25%   |
| Graphics card            | 1         | 6.25%   |
| Communication controller | 1         | 6.25%   |

