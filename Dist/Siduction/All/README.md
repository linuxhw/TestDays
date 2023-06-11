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

Total: 87

| Vendor  | Model                       | Form-Factor | Probe                                                      | Date         |
|---------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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

![OS](./images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Siduction 12       | 19        | 37.25%  |
| Siduction 11       | 14        | 27.45%  |
| Siduction Unstable | 11        | 21.57%  |
| Siduction 10       | 5         | 9.8%    |
| Siduction 21       | 1         | 1.96%   |
| Siduction          | 1         | 1.96%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| Siduction | 39        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                       | Computers | Percent |
|-------------------------------|-----------|---------|
| 6.2.8-1-siduction-amd64       | 3         | 4.05%   |
| 6.2.6-1-siduction-amd64       | 3         | 4.05%   |
| 5.13.8-1-siduction-amd64      | 3         | 4.05%   |
| 6.2.2-6-siduction-amd64       | 2         | 2.7%    |
| 6.2.15-1-siduction-amd64      | 2         | 2.7%    |
| 6.2.13-1-siduction-amd64      | 2         | 2.7%    |
| 6.2.10-1-siduction-amd64      | 2         | 2.7%    |
| 6.1.14-1-siduction-amd64      | 2         | 2.7%    |
| 5.13.6-1-siduction-amd64      | 2         | 2.7%    |
| 5.12.12-1-siduction-amd64     | 2         | 2.7%    |
| 6.3.7-1-siduction-amd64       | 1         | 1.35%   |
| 6.3.5-1-siduction-amd64       | 1         | 1.35%   |
| 6.3.3-1-siduction-amd64       | 1         | 1.35%   |
| 6.2.2-3-siduction-amd64       | 1         | 1.35%   |
| 6.2.11-1-siduction-amd64      | 1         | 1.35%   |
| 6.2.0-rc6-siduction-amd64     | 1         | 1.35%   |
| 6.1.10-2-siduction-amd64      | 1         | 1.35%   |
| 6.1.1-4-siduction-amd64       | 1         | 1.35%   |
| 6.0.9-1-siduction-amd64       | 1         | 1.35%   |
| 5.9.8-towo.3-siduction-amd64  | 1         | 1.35%   |
| 5.9.13-towo.1-siduction-amd64 | 1         | 1.35%   |
| 5.8.5-towo.1-siduction-amd64  | 1         | 1.35%   |
| 5.8.12-towo.1-siduction-amd64 | 1         | 1.35%   |
| 5.7.2-towo.1-siduction-amd64  | 1         | 1.35%   |
| 5.7.11-towo.2-siduction-amd64 | 1         | 1.35%   |
| 5.6.2-towo.1-siduction-amd64  | 1         | 1.35%   |
| 5.4.5-towo.2-siduction-amd64  | 1         | 1.35%   |
| 5.4.18-towo.1-siduction-amd64 | 1         | 1.35%   |
| 5.3.12-towo.2-siduction-amd64 | 1         | 1.35%   |
| 5.3.1-towo.2-siduction-amd64  | 1         | 1.35%   |
| 5.19.5-2-siduction-amd64      | 1         | 1.35%   |
| 5.19.14-1-siduction-amd64     | 1         | 1.35%   |
| 5.19.12-1-siduction-amd64     | 1         | 1.35%   |
| 5.18.8-1-siduction-amd64      | 1         | 1.35%   |
| 5.18.3-1-siduction-amd64      | 1         | 1.35%   |
| 5.18.15-1-siduction-amd64     | 1         | 1.35%   |
| 5.18.0-1-siduction-amd64      | 1         | 1.35%   |
| 5.16.7-1-siduction-amd64      | 1         | 1.35%   |
| 5.16.5-1-siduction-amd64      | 1         | 1.35%   |
| 5.16.18-1-siduction-amd64     | 1         | 1.35%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.2.8   | 3         | 4.05%   |
| 6.2.6   | 3         | 4.05%   |
| 6.2.2   | 3         | 4.05%   |
| 5.13.8  | 3         | 4.05%   |
| 6.2.15  | 2         | 2.7%    |
| 6.2.13  | 2         | 2.7%    |
| 6.2.10  | 2         | 2.7%    |
| 6.1.14  | 2         | 2.7%    |
| 5.14.0  | 2         | 2.7%    |
| 5.13.6  | 2         | 2.7%    |
| 5.12.12 | 2         | 2.7%    |
| 6.3.7   | 1         | 1.35%   |
| 6.3.5   | 1         | 1.35%   |
| 6.3.3   | 1         | 1.35%   |
| 6.2.11  | 1         | 1.35%   |
| 6.2.0   | 1         | 1.35%   |
| 6.1.10  | 1         | 1.35%   |
| 6.1.1   | 1         | 1.35%   |
| 6.0.9   | 1         | 1.35%   |
| 5.9.8   | 1         | 1.35%   |
| 5.9.13  | 1         | 1.35%   |
| 5.8.5   | 1         | 1.35%   |
| 5.8.12  | 1         | 1.35%   |
| 5.7.2   | 1         | 1.35%   |
| 5.7.11  | 1         | 1.35%   |
| 5.6.2   | 1         | 1.35%   |
| 5.4.5   | 1         | 1.35%   |
| 5.4.18  | 1         | 1.35%   |
| 5.3.12  | 1         | 1.35%   |
| 5.3.1   | 1         | 1.35%   |
| 5.19.5  | 1         | 1.35%   |
| 5.19.14 | 1         | 1.35%   |
| 5.19.12 | 1         | 1.35%   |
| 5.18.8  | 1         | 1.35%   |
| 5.18.3  | 1         | 1.35%   |
| 5.18.15 | 1         | 1.35%   |
| 5.18.0  | 1         | 1.35%   |
| 5.16.7  | 1         | 1.35%   |
| 5.16.5  | 1         | 1.35%   |
| 5.16.18 | 1         | 1.35%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.2     | 15        | 23.08%  |
| 5.13    | 8         | 12.31%  |
| 6.1     | 4         | 6.15%   |
| 5.16    | 4         | 6.15%   |
| 5.12    | 4         | 6.15%   |
| 6.3     | 3         | 4.62%   |
| 5.19    | 3         | 4.62%   |
| 5.18    | 3         | 4.62%   |
| 5.15    | 3         | 4.62%   |
| 5.14    | 3         | 4.62%   |
| 5.8     | 2         | 3.08%   |
| 5.7     | 2         | 3.08%   |
| 5.4     | 2         | 3.08%   |
| 5.3     | 2         | 3.08%   |
| 5.10    | 2         | 3.08%   |
| 6.0     | 1         | 1.54%   |
| 5.9     | 1         | 1.54%   |
| 5.6     | 1         | 1.54%   |
| 5.11    | 1         | 1.54%   |
| 4.20    | 1         | 1.54%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 39        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KDE5            | 26        | 61.9%   |
| XFCE            | 5         | 11.9%   |
| X-Cinnamon      | 3         | 7.14%   |
| LXQt            | 3         | 7.14%   |
| Unknown         | 3         | 7.14%   |
| GNOME Flashback | 1         | 2.38%   |
| Cinnamon        | 1         | 2.38%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 33        | 82.5%   |
| Wayland | 5         | 12.5%   |
| Tty     | 2         | 5%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 28        | 66.67%  |
| Unknown | 10        | 23.81%  |
| TDM     | 1         | 2.38%   |
| LightDM | 1         | 2.38%   |
| GDM3    | 1         | 2.38%   |
| GDM     | 1         | 2.38%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| de_DE   | 17        | 41.46%  |
| en_US   | 10        | 24.39%  |
| en_GB   | 3         | 7.32%   |
| Unknown | 3         | 7.32%   |
| it_IT   | 2         | 4.88%   |
| fr_FR   | 1         | 2.44%   |
| es_CO   | 1         | 2.44%   |
| en_CA   | 1         | 2.44%   |
| de_CH   | 1         | 2.44%   |
| de_AT   | 1         | 2.44%   |
| C       | 1         | 2.44%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 27        | 69.23%  |
| BIOS | 12        | 30.77%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 34        | 82.93%  |
| Btrfs   | 6         | 14.63%  |
| Unknown | 1         | 2.44%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 26        | 65%     |
| Unknown | 10        | 25%     |
| MBR     | 4         | 10%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 36        | 90%     |
| Yes       | 4         | 10%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 30        | 75%     |
| Yes       | 10        | 25%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Hewlett-Packard  | 9         | 23.08%  |
| Lenovo           | 8         | 20.51%  |
| ASUSTek Computer | 6         | 15.38%  |
| Dell             | 5         | 12.82%  |
| Acer             | 4         | 10.26%  |
| ASRock           | 2         | 5.13%   |
| TUXEDO           | 1         | 2.56%   |
| NEWSMAY          | 1         | 2.56%   |
| MSI              | 1         | 2.56%   |
| Compal           | 1         | 2.56%   |
| Apple            | 1         | 2.56%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| TUXEDO Book BA1510                         | 1         | 2.56%   |
| MSI MS-7C56                                | 1         | 2.56%   |
| Lenovo ThinkPad X1 Tablet Gen 2 20JCA016JP | 1         | 2.56%   |
| Lenovo ThinkPad X1 Carbon 5th 20HRCTO1WW   | 1         | 2.56%   |
| Lenovo ThinkPad T410 253725G               | 1         | 2.56%   |
| Lenovo ThinkPad Edge E540 20C6003AGE       | 1         | 2.56%   |
| Lenovo ThinkPad E590 20NB001AIX            | 1         | 2.56%   |
| Lenovo IdeaPad 3 15IIL05 81WE              | 1         | 2.56%   |
| Lenovo IdeaCentre AIO 3 27ALC6 F0FY0055GE  | 1         | 2.56%   |
| Lenovo IdeaCentre 310S-08ASR 90G9006DIX    | 1         | 2.56%   |
| HP ZBook 15 G6                             | 1         | 2.56%   |
| HP Z440 Workstation                        | 1         | 2.56%   |
| HP ProBook 640 G1                          | 1         | 2.56%   |
| HP ProBook 4520s                           | 1         | 2.56%   |
| HP OMEN 30L Desktop GT13-0xxx              | 1         | 2.56%   |
| HP Laptop 17-ca1xxx                        | 1         | 2.56%   |
| HP Laptop 15-db0xxx                        | 1         | 2.56%   |
| HP EliteBook 865 16 inch G9 Notebook PC    | 1         | 2.56%   |
| HP 250 G7 Notebook PC                      | 1         | 2.56%   |
| Dell Vostro 15 3510                        | 1         | 2.56%   |
| Dell OptiPlex 5040                         | 1         | 2.56%   |
| Dell OptiPlex 3050                         | 1         | 2.56%   |
| Dell Latitude 5491                         | 1         | 2.56%   |
| Dell Inspiron 7415 2-in-1                  | 1         | 2.56%   |
| Compal NBLBX                               | 1         | 2.56%   |
| ASUS ZenBook UX325JA_UX325JA               | 1         | 2.56%   |
| ASUS ROG STRIX Z370-F GAMING               | 1         | 2.56%   |
| ASUS ROG STRIX B550-A GAMING               | 1         | 2.56%   |
| ASUS PRIME Z270-A                          | 1         | 2.56%   |
| ASUS B150M-A/M.2                           | 1         | 2.56%   |
| ASUS A0000001                              | 1         | 2.56%   |
| ASRock B550 Steel Legend                   | 1         | 2.56%   |
| ASRock B450 Pro4                           | 1         | 2.56%   |
| Apple MacBookPro9,2                        | 1         | 2.56%   |
| Acer Swift SF314-51                        | 1         | 2.56%   |
| Acer Aspire E5-771G                        | 1         | 2.56%   |
| Acer Aspire E5-551G                        | 1         | 2.56%   |
| Acer Aspire 5750                           | 1         | 2.56%   |
| Unknown                                    | 1         | 2.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 5         | 12.82%  |
| Acer Aspire       | 3         | 7.69%   |
| Lenovo IdeaCentre | 2         | 5.13%   |
| HP ProBook        | 2         | 5.13%   |
| HP Laptop         | 2         | 5.13%   |
| Dell OptiPlex     | 2         | 5.13%   |
| ASUS ROG          | 2         | 5.13%   |
| TUXEDO Book       | 1         | 2.56%   |
| MSI MS-7C56       | 1         | 2.56%   |
| Lenovo IdeaPad    | 1         | 2.56%   |
| HP ZBook          | 1         | 2.56%   |
| HP Z440           | 1         | 2.56%   |
| HP OMEN           | 1         | 2.56%   |
| HP EliteBook      | 1         | 2.56%   |
| HP 250            | 1         | 2.56%   |
| Dell Vostro       | 1         | 2.56%   |
| Dell Latitude     | 1         | 2.56%   |
| Dell Inspiron     | 1         | 2.56%   |
| Compal NBLBX      | 1         | 2.56%   |
| ASUS ZenBook      | 1         | 2.56%   |
| ASUS PRIME        | 1         | 2.56%   |
| ASUS B150M-A      | 1         | 2.56%   |
| ASUS A0000001     | 1         | 2.56%   |
| ASRock B550       | 1         | 2.56%   |
| ASRock B450       | 1         | 2.56%   |
| Apple MacBookPro9 | 1         | 2.56%   |
| Acer Swift        | 1         | 2.56%   |
| Unknown           | 1         | 2.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 7         | 17.95%  |
| 2019 | 5         | 12.82%  |
| 2018 | 4         | 10.26%  |
| 2017 | 4         | 10.26%  |
| 2021 | 3         | 7.69%   |
| 2016 | 3         | 7.69%   |
| 2022 | 2         | 5.13%   |
| 2015 | 2         | 5.13%   |
| 2014 | 2         | 5.13%   |
| 2013 | 2         | 5.13%   |
| 2010 | 2         | 5.13%   |
| 2012 | 1         | 2.56%   |
| 2011 | 1         | 2.56%   |
| 2009 | 1         | 2.56%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 22        | 56.41%  |
| Desktop     | 14        | 35.9%   |
| Tablet      | 1         | 2.56%   |
| Convertible | 1         | 2.56%   |
| All in one  | 1         | 2.56%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 39        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 39        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 10        | 25%     |
| 16.01-24.0  | 10        | 25%     |
| 32.01-64.0  | 9         | 22.5%   |
| 8.01-16.0   | 8         | 20%     |
| 3.01-4.0    | 1         | 2.5%    |
| 64.01-256.0 | 1         | 2.5%    |
| Unknown     | 1         | 2.5%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 15        | 27.27%  |
| 2.01-3.0   | 14        | 25.45%  |
| 3.01-4.0   | 10        | 18.18%  |
| 1.01-2.0   | 6         | 10.91%  |
| 8.01-16.0  | 4         | 7.27%   |
| 0.51-1.0   | 3         | 5.45%   |
| 16.01-24.0 | 1         | 1.82%   |
| 0.01-0.5   | 1         | 1.82%   |
| Unknown    | 1         | 1.82%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 21        | 51.22%  |
| 2      | 10        | 24.39%  |
| 4      | 5         | 12.2%   |
| 3      | 3         | 7.32%   |
| 6      | 1         | 2.44%   |
| 5      | 1         | 2.44%   |

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
| Yes       | 34        | 87.18%  |
| No        | 5         | 12.82%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 30        | 76.92%  |
| No        | 9         | 23.08%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 24        | 57.14%  |
| No        | 18        | 42.86%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Germany     | 17        | 41.46%  |
| USA         | 4         | 9.76%   |
| UK          | 3         | 7.32%   |
| Italy       | 3         | 7.32%   |
| Canada      | 3         | 7.32%   |
| Austria     | 3         | 7.32%   |
| Sweden      | 2         | 4.88%   |
| Switzerland | 1         | 2.44%   |
| Netherlands | 1         | 2.44%   |
| Japan       | 1         | 2.44%   |
| Israel      | 1         | 2.44%   |
| France      | 1         | 2.44%   |
| Colombia    | 1         | 2.44%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Munich               | 4         | 7.55%   |
| Vienna               | 3         | 5.66%   |
| Berlin               | 3         | 5.66%   |
| Stockholm            | 2         | 3.77%   |
| Schrobenhausen       | 2         | 3.77%   |
| Zurich               | 1         | 1.89%   |
| Turin                | 1         | 1.89%   |
| Toronto              | 1         | 1.89%   |
| Tokyo                | 1         | 1.89%   |
| Suisun               | 1         | 1.89%   |
| Stuttgart            | 1         | 1.89%   |
| Sidney               | 1         | 1.89%   |
| Savannah             | 1         | 1.89%   |
| Sanford              | 1         | 1.89%   |
| San Francisco        | 1         | 1.89%   |
| Salzburg             | 1         | 1.89%   |
| Reading              | 1         | 1.89%   |
| Piea                 | 1         | 1.89%   |
| Paris                | 1         | 1.89%   |
| Papenburg            | 1         | 1.89%   |
| Oranienburg          | 1         | 1.89%   |
| Mittenwald           | 1         | 1.89%   |
| Milan                | 1         | 1.89%   |
| Merseburg            | 1         | 1.89%   |
| Mannheim             | 1         | 1.89%   |
| Malmo                | 1         | 1.89%   |
| Leipzig              | 1         | 1.89%   |
| Langewiesen          | 1         | 1.89%   |
| Kensington           | 1         | 1.89%   |
| Jerusalem            | 1         | 1.89%   |
| Iserlohn             | 1         | 1.89%   |
| Innsbruck            | 1         | 1.89%   |
| Hamburg              | 1         | 1.89%   |
| Graz                 | 1         | 1.89%   |
| Grafenau             | 1         | 1.89%   |
| Friedrichsthal       | 1         | 1.89%   |
| Freiburg im Breisgau | 1         | 1.89%   |
| Frankfurt am Main    | 1         | 1.89%   |
| Edmonton             | 1         | 1.89%   |
| Düsseldorf          | 1         | 1.89%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 12        | 29     | 17.39%  |
| Samsung Electronics | 12        | 21     | 17.39%  |
| Seagate             | 8         | 17     | 11.59%  |
| Toshiba             | 6         | 15     | 8.7%    |
| SanDisk             | 5         | 7      | 7.25%   |
| Crucial             | 5         | 17     | 7.25%   |
| SK hynix            | 4         | 12     | 5.8%    |
| Kingston            | 3         | 3      | 4.35%   |
| Intel               | 3         | 7      | 4.35%   |
| Unknown             | 1         | 1      | 1.45%   |
| SSSTC               | 1         | 1      | 1.45%   |
| SPCC                | 1         | 1      | 1.45%   |
| Silicon Motion      | 1         | 1      | 1.45%   |
| OCZ                 | 1         | 3      | 1.45%   |
| Mushkin             | 1         | 3      | 1.45%   |
| Micron Technology   | 1         | 1      | 1.45%   |
| Lenovo              | 1         | 1      | 1.45%   |
| HGST                | 1         | 10     | 1.45%   |
| GRITRONIX           | 1         | 1      | 1.45%   |
| Corsair             | 1         | 3      | 1.45%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| WDC WD10JPVX-22JC3T0 1TB                          | 3         | 3.8%    |
| Toshiba MQ04ABF100 1TB                            | 2         | 2.53%   |
| Samsung SSD 850 EVO 250GB                         | 2         | 2.53%   |
| Crucial CT500MX500SSD1 500GB                      | 2         | 2.53%   |
| Crucial CT1000MX500SSD1 1TB                       | 2         | 2.53%   |
| WDC WDS400T2B0A-00SM50 4TB SSD                    | 1         | 1.27%   |
| WDC WDS200T2B0B-00YS70 2TB SSD                    | 1         | 1.27%   |
| WDC WDS100T2B0C-00PXH0 1TB                        | 1         | 1.27%   |
| WDC WD60EZAZ-00SF3B0 6TB                          | 1         | 1.27%   |
| WDC WD40EZAZ-00SF3B0 4TB                          | 1         | 1.27%   |
| WDC WD20EZRZ-00Z5HB0 2TB                          | 1         | 1.27%   |
| WDC WD20EFRX-68EUZN0 2TB                          | 1         | 1.27%   |
| WDC WD10SPZX-60Z10T0 1TB                          | 1         | 1.27%   |
| WDC WD10JPVX-60JC3T1 1TB                          | 1         | 1.27%   |
| WDC WD10EADX-00TDHB0 1TB                          | 1         | 1.27%   |
| WDC WD BLACK SDBPNTY-512G-1106 512GB              | 1         | 1.27%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB              | 1         | 1.27%   |
| Unknown MMC Card  64GB                            | 1         | 1.27%   |
| Toshiba THNSNK256GVN8 256GB SSD                   | 1         | 1.27%   |
| Toshiba RD400 256GB                               | 1         | 1.27%   |
| Toshiba MQ01ACF032 320GB                          | 1         | 1.27%   |
| Toshiba KBG30ZMT256G 256GB                        | 1         | 1.27%   |
| SSSTC CL4-3D256-Q11 NVMe 256GB                    | 1         | 1.27%   |
| SPCC Solid State Disk 512GB                       | 1         | 1.27%   |
| SK hynix SC308 SATA 128GB SSD                     | 1         | 1.27%   |
| SK hynix NVMe SSD Drive 512GB                     | 1         | 1.27%   |
| SK hynix BC711 NVMe 1TB                           | 1         | 1.27%   |
| SK hynix BC501 HFM256GDJTNG-8310A 256GB           | 1         | 1.27%   |
| Silicon Motion SM2262/SM2262EN SSD Controller 1TB | 1         | 1.27%   |
| Seagate ST9640320AS 640GB                         | 1         | 1.27%   |
| Seagate ST9500420AS 500GB                         | 1         | 1.27%   |
| Seagate ST6000DM003-2CY186 6TB                    | 1         | 1.27%   |
| Seagate ST500LT012-1DG142 500GB                   | 1         | 1.27%   |
| Seagate ST4000LM016-1N2170 4TB                    | 1         | 1.27%   |
| Seagate ST32000542AS 2TB                          | 1         | 1.27%   |
| Seagate ST31000524AS 1TB                          | 1         | 1.27%   |
| Seagate ST3000VN000-1HJ166 3TB                    | 1         | 1.27%   |
| Seagate ST2000DM008-2FR102 2TB                    | 1         | 1.27%   |
| Seagate ST2000DL003-9VT166 2TB                    | 1         | 1.27%   |
| Seagate ST1000LM014-1EJ164 1TB                    | 1         | 1.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 9         | 20     | 40.91%  |
| Seagate             | 8         | 17     | 36.36%  |
| Toshiba             | 3         | 11     | 13.64%  |
| Samsung Electronics | 1         | 1      | 4.55%   |
| HGST                | 1         | 10     | 4.55%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 17     | 33.33%  |
| Crucial             | 5         | 16     | 20.83%  |
| WDC                 | 2         | 2      | 8.33%   |
| SanDisk             | 2         | 4      | 8.33%   |
| Kingston            | 2         | 2      | 8.33%   |
| Toshiba             | 1         | 1      | 4.17%   |
| SPCC                | 1         | 1      | 4.17%   |
| SK hynix            | 1         | 8      | 4.17%   |
| OCZ                 | 1         | 3      | 4.17%   |
| GRITRONIX           | 1         | 1      | 4.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 21        | 39     | 35.59%  |
| SSD  | 19        | 55     | 32.2%   |
| HDD  | 18        | 59     | 30.51%  |
| MMC  | 1         | 1      | 1.69%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 29        | 114    | 56.86%  |
| NVMe | 21        | 39     | 41.18%  |
| MMC  | 1         | 1      | 1.96%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 16        | 43     | 40%     |
| 0.51-1.0   | 12        | 33     | 30%     |
| 1.01-2.0   | 6         | 19     | 15%     |
| 3.01-4.0   | 3         | 14     | 7.5%    |
| 4.01-10.0  | 2         | 2      | 5%      |
| 2.01-3.0   | 1         | 3      | 2.5%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 12        | 27.91%  |
| More than 3000 | 6         | 13.95%  |
| 1001-2000      | 6         | 13.95%  |
| 101-250        | 5         | 11.63%  |
| 501-1000       | 4         | 9.3%    |
| Unknown        | 4         | 9.3%    |
| 2001-3000      | 2         | 4.65%   |
| 1-20           | 2         | 4.65%   |
| 21-50          | 1         | 2.33%   |
| 51-100         | 1         | 2.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 14        | 28%     |
| 101-250        | 7         | 14%     |
| 51-100         | 5         | 10%     |
| 251-500        | 4         | 8%      |
| 21-50          | 4         | 8%      |
| 1001-2000      | 4         | 8%      |
| 501-1000       | 4         | 8%      |
| Unknown        | 4         | 8%      |
| More than 3000 | 3         | 6%      |
| 2001-3000      | 1         | 2%      |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                   | Computers | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| WDC WD20EZRZ-00Z5HB0 2TB                | 1         | 6      | 12.5%   |
| SK hynix SC308 SATA 128GB SSD           | 1         | 8      | 12.5%   |
| SK hynix BC501 HFM256GDJTNG-8310A 256GB | 1         | 1      | 12.5%   |
| Seagate ST32000542AS 2TB                | 1         | 3      | 12.5%   |
| Samsung Electronics SSD 870 EVO 4TB     | 1         | 1      | 12.5%   |
| OCZ VERTEX3 120GB SSD                   | 1         | 3      | 12.5%   |
| HGST HTS725050A7E630 500GB              | 1         | 10     | 12.5%   |
| Crucial CT500MX500SSD1 500GB            | 1         | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| SK hynix            | 2         | 9      | 25%     |
| WDC                 | 1         | 6      | 12.5%   |
| Seagate             | 1         | 3      | 12.5%   |
| Samsung Electronics | 1         | 1      | 12.5%   |
| OCZ                 | 1         | 3      | 12.5%   |
| HGST                | 1         | 10     | 12.5%   |
| Crucial             | 1         | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 6      | 33.33%  |
| Seagate | 1         | 3      | 33.33%  |
| HGST    | 1         | 10     | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 4         | 13     | 50%     |
| HDD  | 3         | 19     | 37.5%   |
| NVMe | 1         | 1      | 12.5%   |

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
| Works    | 31        | 101    | 64.58%  |
| Detected | 11        | 20     | 22.92%  |
| Malfunc  | 6         | 33     | 12.5%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 25        | 42.37%  |
| AMD                            | 12        | 20.34%  |
| SanDisk                        | 6         | 10.17%  |
| SK hynix                       | 3         | 5.08%   |
| Toshiba America Info Systems   | 2         | 3.39%   |
| Samsung Electronics            | 2         | 3.39%   |
| Solid State Storage Technology | 1         | 1.69%   |
| Silicon Motion                 | 1         | 1.69%   |
| Phison Electronics             | 1         | 1.69%   |
| OCZ Technology Group           | 1         | 1.69%   |
| Micron/Crucial Technology      | 1         | 1.69%   |
| Micron Technology              | 1         | 1.69%   |
| Lenovo                         | 1         | 1.69%   |
| Kingston Technology Company    | 1         | 1.69%   |
| ASMedia Technology             | 1         | 1.69%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 9         | 13.85%  |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 3         | 4.62%   |
| AMD 500 Series Chipset SATA Controller                                         | 3         | 4.62%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 2         | 3.08%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 2         | 3.08%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 2         | 3.08%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 3.08%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 3.08%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 3.08%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 3.08%   |
| AMD 400 Series Chipset SATA Controller                                         | 2         | 3.08%   |
| Solid State Storage Non-Volatile memory controller                             | 1         | 1.54%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 1         | 1.54%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 1         | 1.54%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                             | 1         | 1.54%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 1.54%   |
| SanDisk NVMe Controller                                                        | 1         | 1.54%   |
| SanDisk Non-Volatile memory controller                                         | 1         | 1.54%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 1.54%   |
| Samsung Electronics Non-Volatile memory controller                             | 1         | 1.54%   |
| Phison E7 NVMe Controller                                                      | 1         | 1.54%   |
| OCZ Group RD400/400A SSD                                                       | 1         | 1.54%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                | 1         | 1.54%   |
| Micron NVMe Storage Controller                                                 | 1         | 1.54%   |
| Lenovo Non-Volatile memory controller                                          | 1         | 1.54%   |
| Kingston Company A2000 NVMe SSD                                                | 1         | 1.54%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 1.54%   |
| Intel Tiger Lake-LP SATA Controller                                            | 1         | 1.54%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 1         | 1.54%   |
| Intel SSD 665p Series                                                          | 1         | 1.54%   |
| Intel SSD 660P Series                                                          | 1         | 1.54%   |
| Intel SATA Controller [RAID mode]                                              | 1         | 1.54%   |
| Intel NVMe Controller                                                          | 1         | 1.54%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 1         | 1.54%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 1         | 1.54%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 1.54%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 1         | 1.54%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 1         | 1.54%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 1         | 1.54%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1         | 1.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 32        | 56.14%  |
| NVMe | 21        | 36.84%  |
| RAID | 3         | 5.26%   |
| IDE  | 1         | 1.75%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 26        | 66.67%  |
| AMD    | 13        | 33.33%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 5.13%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 5.13%   |
| AMD Ryzen 5 3600 6-Core Processor             | 2         | 5.13%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 5.13%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz           | 1         | 2.56%   |
| Intel Pentium Silver N6005 @ 2.00GHz          | 1         | 2.56%   |
| Intel Pentium CPU G4400T @ 2.90GHz            | 1         | 2.56%   |
| Intel Core i7-9850H CPU @ 2.60GHz             | 1         | 2.56%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 1         | 2.56%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 1         | 2.56%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 2.56%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz            | 1         | 2.56%   |
| Intel Core i7-10700K CPU @ 3.80GHz            | 1         | 2.56%   |
| Intel Core i5-7Y54 CPU @ 1.20GHz              | 1         | 2.56%   |
| Intel Core i5-7600K CPU @ 3.80GHz             | 1         | 2.56%   |
| Intel Core i5-6600K CPU @ 3.50GHz             | 1         | 2.56%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 1         | 2.56%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 2.56%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 2.56%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 2.56%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 1         | 2.56%   |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 1         | 2.56%   |
| Intel Core i5 CPU M 430 @ 2.27GHz             | 1         | 2.56%   |
| Intel Core i3-4000M CPU @ 2.40GHz             | 1         | 2.56%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 1         | 2.56%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 1         | 2.56%   |
| AMD Ryzen 9 PRO 6950HS with Radeon Graphics   | 1         | 2.56%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 1         | 2.56%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 1         | 2.56%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 1         | 2.56%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 1         | 2.56%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 1         | 2.56%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 1         | 2.56%   |
| AMD FX-7500 Radeon R7, 10 Compute Cores 4C+6G | 1         | 2.56%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G  | 1         | 2.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 12        | 30.77%  |
| Intel Core i7        | 8         | 20.51%  |
| AMD Ryzen 5          | 7         | 17.95%  |
| Other                | 2         | 5.13%   |
| Intel Core i3        | 2         | 5.13%   |
| AMD Ryzen 9          | 2         | 5.13%   |
| AMD Ryzen 7          | 2         | 5.13%   |
| Intel Xeon           | 1         | 2.56%   |
| Intel Pentium Silver | 1         | 2.56%   |
| Intel Pentium        | 1         | 2.56%   |
| AMD FX               | 1         | 2.56%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 14        | 35.9%   |
| 2      | 13        | 33.33%  |
| 6      | 7         | 17.95%  |
| 8      | 4         | 10.26%  |
| 12     | 1         | 2.56%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 39        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 33        | 84.62%  |
| 1      | 6         | 15.38%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 38        | 97.44%  |
| Unknown        | 1         | 2.56%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 15        | 32.61%  |
| 0x08701021 | 3         | 6.52%   |
| 0x806ec    | 2         | 4.35%   |
| 0x706e5    | 2         | 4.35%   |
| 0x506e3    | 2         | 4.35%   |
| 0x20655    | 2         | 4.35%   |
| 0x08108102 | 2         | 4.35%   |
| 0x0800820d | 2         | 4.35%   |
| 0xa0655    | 1         | 2.17%   |
| 0x906ea    | 1         | 2.17%   |
| 0x906e9    | 1         | 2.17%   |
| 0x806eb    | 1         | 2.17%   |
| 0x806e9    | 1         | 2.17%   |
| 0x306f2    | 1         | 2.17%   |
| 0x306d4    | 1         | 2.17%   |
| 0x306c3    | 1         | 2.17%   |
| 0x206a7    | 1         | 2.17%   |
| 0x20652    | 1         | 2.17%   |
| 0x0a404102 | 1         | 2.17%   |
| 0x08608103 | 1         | 2.17%   |
| 0x08108109 | 1         | 2.17%   |
| 0x0810100b | 1         | 2.17%   |
| 0x06006705 | 1         | 2.17%   |
| 0x06003106 | 1         | 2.17%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| KabyLake    | 8         | 20.51%  |
| Zen+        | 4         | 10.26%  |
| Skylake     | 4         | 10.26%  |
| Zen 2       | 3         | 7.69%   |
| Westmere    | 3         | 7.69%   |
| Haswell     | 3         | 7.69%   |
| Unknown     | 3         | 7.69%   |
| IceLake     | 2         | 5.13%   |
| Zen         | 1         | 2.56%   |
| Tremont     | 1         | 2.56%   |
| TigerLake   | 1         | 2.56%   |
| Steamroller | 1         | 2.56%   |
| SandyBridge | 1         | 2.56%   |
| IvyBridge   | 1         | 2.56%   |
| Excavator   | 1         | 2.56%   |
| CometLake   | 1         | 2.56%   |
| Broadwell   | 1         | 2.56%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 19        | 42.22%  |
| AMD    | 17        | 37.78%  |
| Nvidia | 9         | 20%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 3         | 6.38%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 2         | 4.26%   |
| Intel Iris Plus Graphics G7                                                 | 2         | 4.26%   |
| Intel Core Processor Integrated Graphics Controller                         | 2         | 4.26%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 2         | 4.26%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2         | 4.26%   |
| AMD Lucienne                                                                | 2         | 4.26%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                               | 1         | 2.13%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1         | 2.13%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1         | 2.13%   |
| Nvidia GM108M [GeForce MX130]                                               | 1         | 2.13%   |
| Nvidia GK208M [GeForce GT 740M]                                             | 1         | 2.13%   |
| Nvidia GK104 [GeForce GTX 770]                                              | 1         | 2.13%   |
| Nvidia GF119 [NVS 310]                                                      | 1         | 2.13%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]        | 1         | 2.13%   |
| Nvidia GA106 [Geforce RTX 3050]                                             | 1         | 2.13%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 1         | 2.13%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 1         | 2.13%   |
| Intel JasperLake [UHD Graphics]                                             | 1         | 2.13%   |
| Intel HD Graphics 620                                                       | 1         | 2.13%   |
| Intel HD Graphics 615                                                       | 1         | 2.13%   |
| Intel HD Graphics 5500                                                      | 1         | 2.13%   |
| Intel HD Graphics 530                                                       | 1         | 2.13%   |
| Intel HD Graphics 510                                                       | 1         | 2.13%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 1         | 2.13%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 1         | 2.13%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 1         | 2.13%   |
| AMD Vega 20 [Radeon VII]                                                    | 1         | 2.13%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                    | 1         | 2.13%   |
| AMD RV711/M93 [Mobility Radeon HD 4350/4550/530v/540v/545v / FirePro RG220] | 1         | 2.13%   |
| AMD Rembrandt [Radeon 680M]                                                 | 1         | 2.13%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 1         | 2.13%   |
| AMD Opal XT [Radeon R7 M265/M365X/M465]                                     | 1         | 2.13%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 1         | 2.13%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 1         | 2.13%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 1         | 2.13%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                    | 1         | 2.13%   |
| AMD Kaveri [Radeon R6/R7 Graphics]                                          | 1         | 2.13%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 1         | 2.13%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 15        | 36.59%  |
| 1 x AMD        | 15        | 36.59%  |
| 1 x Nvidia     | 6         | 14.63%  |
| Intel + Nvidia | 3         | 7.32%   |
| 2 x AMD        | 1         | 2.44%   |
| Intel + AMD    | 1         | 2.44%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 35        | 85.37%  |
| Proprietary | 6         | 14.63%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 21        | 48.84%  |
| 0.01-0.5   | 7         | 16.28%  |
| 7.01-8.0   | 4         | 9.3%    |
| 1.01-2.0   | 4         | 9.3%    |
| 8.01-16.0  | 2         | 4.65%   |
| 0.51-1.0   | 2         | 4.65%   |
| 5.01-6.0   | 1         | 2.33%   |
| 3.01-4.0   | 1         | 2.33%   |
| 2.01-3.0   | 1         | 2.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Chimei Innolux      | 8         | 15.38%  |
| Acer                | 6         | 11.54%  |
| LG Display          | 5         | 9.62%   |
| AU Optronics        | 5         | 9.62%   |
| Samsung Electronics | 4         | 7.69%   |
| Lenovo              | 3         | 5.77%   |
| Hewlett-Packard     | 3         | 5.77%   |
| Dell                | 3         | 5.77%   |
| BOE                 | 3         | 5.77%   |
| Philips             | 2         | 3.85%   |
| Goldstar            | 2         | 3.85%   |
| STD                 | 1         | 1.92%   |
| Sony                | 1         | 1.92%   |
| MSI                 | 1         | 1.92%   |
| Eizo                | 1         | 1.92%   |
| BenQ                | 1         | 1.92%   |
| ASUSTek Computer    | 1         | 1.92%   |
| Apple               | 1         | 1.92%   |
| AOC                 | 1         | 1.92%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SyncMaster SAM021E 1680x1050 433x271mm 20.1-inch  | 2         | 3.7%    |
| STD HDMI TV STD00C7 1920x1080 698x392mm 31.5-inch                     | 1         | 1.85%   |
| Sony SAMSUNG SNY5203 1920x540                                         | 1         | 1.85%   |
| Samsung Electronics S27E590 SAM0C5D 1920x1080 598x336mm 27.0-inch     | 1         | 1.85%   |
| Samsung Electronics S27E391 SAM0C15 1920x1080 598x336mm 27.0-inch     | 1         | 1.85%   |
| Samsung Electronics LCD Monitor SDC4244 2160x1440 254x169mm 12.0-inch | 1         | 1.85%   |
| Philips PHL 241P6E PHL08F7 1920x1080 530x300mm 24.0-inch              | 1         | 1.85%   |
| Philips 200V4 PHLC0BF 1600x900 432x240mm 19.5-inch                    | 1         | 1.85%   |
| MSI G241 MSI3BA4 1920x1080 527x296mm 23.8-inch                        | 1         | 1.85%   |
| LG Display LCD Monitor LGD06FF 1920x1080 344x194mm 15.5-inch          | 1         | 1.85%   |
| LG Display LCD Monitor LGD059D 1920x1080 309x174mm 14.0-inch          | 1         | 1.85%   |
| LG Display LCD Monitor LGD051D 1920x1080 309x174mm 14.0-inch          | 1         | 1.85%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch           | 1         | 1.85%   |
| LG Display LCD Monitor LGD03DE 1600x900 382x215mm 17.3-inch           | 1         | 1.85%   |
| Lenovo LEN-A-A LENF918 1920x1080 596x335mm 26.9-inch                  | 1         | 1.85%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 1         | 1.85%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x190mm 14.1-inch               | 1         | 1.85%   |
| Hewlett-Packard X27i HPN3678 2560x1440 597x336mm 27.0-inch            | 1         | 1.85%   |
| Hewlett-Packard E243i HPN3463 1920x1200 520x320mm 24.0-inch           | 1         | 1.85%   |
| Hewlett-Packard 27f HPN354B 1920x1080 598x336mm 27.0-inch             | 1         | 1.85%   |
| Hewlett-Packard 27f HPN354A 1920x1080 598x336mm 27.0-inch             | 1         | 1.85%   |
| Goldstar W1946 GSM4BCD 1360x768 406x229mm 18.4-inch                   | 1         | 1.85%   |
| Goldstar LG Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch            | 1         | 1.85%   |
| Eizo EV3285 ENC2979 3840x2160 698x393mm 31.5-inch                     | 1         | 1.85%   |
| Dell UP3216Q DEL40C2 3840x2160 700x400mm 31.7-inch                    | 1         | 1.85%   |
| Dell U2415 DELA0BC 1920x1200 518x324mm 24.1-inch                      | 1         | 1.85%   |
| Dell U2414H DELA0B2 1920x1080 527x296mm 23.8-inch                     | 1         | 1.85%   |
| Chimei Innolux LCD Monitor CMN175A 1920x1080 381x214mm 17.2-inch      | 1         | 1.85%   |
| Chimei Innolux LCD Monitor CMN1610 1920x1200 344x215mm 16.0-inch      | 1         | 1.85%   |
| Chimei Innolux LCD Monitor CMN15F6 1920x1080 340x190mm 15.3-inch      | 1         | 1.85%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 1         | 1.85%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 1         | 1.85%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch      | 1         | 1.85%   |
| Chimei Innolux LCD Monitor CMN15C0 1920x1080 344x194mm 15.5-inch      | 1         | 1.85%   |
| Chimei Innolux LCD Monitor CMN1388 1920x1080 293x165mm 13.2-inch      | 1         | 1.85%   |
| BOE LCD Monitor BOE091D 1920x1080 309x174mm 14.0-inch                 | 1         | 1.85%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 1         | 1.85%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                 | 1         | 1.85%   |
| BenQ LCD BNQ801E 3840x2160 596x335mm 26.9-inch                        | 1         | 1.85%   |
| AU Optronics LCD Monitor AUO5491 1920x1080 309x174mm 14.0-inch        | 1         | 1.85%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 26        | 54.17%  |
| 3840x2160 (4K)     | 4         | 8.33%   |
| 1366x768 (WXGA)    | 4         | 8.33%   |
| 2560x1440 (QHD)    | 2         | 4.17%   |
| 1680x1050 (WSXGA+) | 2         | 4.17%   |
| 1600x900 (HD+)     | 2         | 4.17%   |
| 3840x1080          | 1         | 2.08%   |
| 3440x1440          | 1         | 2.08%   |
| 2160x1440          | 1         | 2.08%   |
| 1920x540           | 1         | 2.08%   |
| 1920x1200 (WUXGA)  | 1         | 2.08%   |
| 1440x900 (WXGA+)   | 1         | 2.08%   |
| 1360x768           | 1         | 2.08%   |
| 1280x800 (WXGA)    | 1         | 2.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 12        | 23.53%  |
| 27      | 7         | 13.73%  |
| 14      | 6         | 11.76%  |
| 31      | 3         | 5.88%   |
| 24      | 3         | 5.88%   |
| 23      | 3         | 5.88%   |
| 20      | 2         | 3.92%   |
| 17      | 2         | 3.92%   |
| 13      | 2         | 3.92%   |
| 49      | 1         | 1.96%   |
| 40      | 1         | 1.96%   |
| 34      | 1         | 1.96%   |
| 32      | 1         | 1.96%   |
| 26      | 1         | 1.96%   |
| 21      | 1         | 1.96%   |
| 19      | 1         | 1.96%   |
| 18      | 1         | 1.96%   |
| 16      | 1         | 1.96%   |
| 12      | 1         | 1.96%   |
| Unknown | 1         | 1.96%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 19        | 39.58%  |
| 501-600     | 13        | 27.08%  |
| 601-700     | 3         | 6.25%   |
| 401-500     | 3         | 6.25%   |
| 201-300     | 3         | 6.25%   |
| 701-800     | 2         | 4.17%   |
| 351-400     | 2         | 4.17%   |
| 801-900     | 1         | 2.08%   |
| 1001-1500   | 1         | 2.08%   |
| Unknown     | 1         | 2.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 34        | 77.27%  |
| 16/10 | 6         | 13.64%  |
| 32/9  | 2         | 4.55%   |
| 3/2   | 1         | 2.27%   |
| 21/9  | 1         | 2.27%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 12        | 24.49%  |
| 301-350        | 8         | 16.33%  |
| 81-90          | 7         | 14.29%  |
| 201-250        | 5         | 10.2%   |
| 351-500        | 4         | 8.16%   |
| 151-200        | 3         | 6.12%   |
| 121-130        | 2         | 4.08%   |
| 501-1000       | 2         | 4.08%   |
| 71-80          | 1         | 2.04%   |
| 61-70          | 1         | 2.04%   |
| 251-300        | 1         | 2.04%   |
| 141-150        | 1         | 2.04%   |
| 111-120        | 1         | 2.04%   |
| Unknown        | 1         | 2.04%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 121-160 | 18        | 38.3%   |
| 51-100  | 15        | 31.91%  |
| 101-120 | 9         | 19.15%  |
| 161-240 | 4         | 8.51%   |
| Unknown | 1         | 2.13%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 31        | 73.81%  |
| 2     | 9         | 21.43%  |
| 3     | 2         | 4.76%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 22        | 39.29%  |
| Intel                 | 22        | 39.29%  |
| Qualcomm Atheros      | 5         | 8.93%   |
| Broadcom              | 4         | 7.14%   |
| Sierra Wireless       | 1         | 1.79%   |
| Qualcomm              | 1         | 1.79%   |
| NetGear               | 1         | 1.79%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 19        | 27.94%  |
| Intel Wi-Fi 6 AX200                                               | 3         | 4.41%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 4.41%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 2         | 2.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 2.94%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 2.94%   |
| Intel Wireless 8265 / 8275                                        | 2         | 2.94%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 2         | 2.94%   |
| Sierra Wireless EM7430 Qualcomm Snapdragon X7 LTE-A               | 1         | 1.47%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 1         | 1.47%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 1.47%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 1.47%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.47%   |
| Qualcomm QCNFA765 Wireless Network Adapter                        | 1         | 1.47%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 1.47%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 1.47%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 1         | 1.47%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1         | 1.47%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 1.47%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]       | 1         | 1.47%   |
| Intel Wireless-AC 9260                                            | 1         | 1.47%   |
| Intel Wireless 7260                                               | 1         | 1.47%   |
| Intel Wireless 3160                                               | 1         | 1.47%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 1.47%   |
| Intel I211 Gigabit Network Connection                             | 1         | 1.47%   |
| Intel Ethernet Controller I225-V                                  | 1         | 1.47%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.47%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 1.47%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.47%   |
| Intel Ethernet Connection (2) I218-LM                             | 1         | 1.47%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 1.47%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 1         | 1.47%   |
| Intel Centrino Ultimate-N 6300                                    | 1         | 1.47%   |
| Intel Centrino Advanced-N 6200                                    | 1         | 1.47%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1         | 1.47%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.47%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 1.47%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.47%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 1         | 1.47%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 1         | 1.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 16        | 48.48%  |
| Realtek Semiconductor | 6         | 18.18%  |
| Qualcomm Atheros      | 5         | 15.15%  |
| Broadcom              | 3         | 9.09%   |
| Sierra Wireless       | 1         | 3.03%   |
| Qualcomm              | 1         | 3.03%   |
| NetGear               | 1         | 3.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 3         | 8.82%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 2         | 5.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 5.88%   |
| Intel Wireless 8265 / 8275                                     | 2         | 5.88%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 2         | 5.88%   |
| Sierra Wireless EM7430 Qualcomm Snapdragon X7 LTE-A            | 1         | 2.94%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 1         | 2.94%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 2.94%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 2.94%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 1         | 2.94%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 2.94%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 2.94%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 2.94%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 2.94%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 2.94%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]    | 1         | 2.94%   |
| Intel Wireless-AC 9260                                         | 1         | 2.94%   |
| Intel Wireless 7260                                            | 1         | 2.94%   |
| Intel Wireless 3160                                            | 1         | 2.94%   |
| Intel Wi-Fi 6 AX201                                            | 1         | 2.94%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 2.94%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 1         | 2.94%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 2.94%   |
| Intel Centrino Advanced-N 6200                                 | 1         | 2.94%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 1         | 2.94%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 1         | 2.94%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 1         | 2.94%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 1         | 2.94%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 22        | 64.71%  |
| Intel                 | 10        | 29.41%  |
| Broadcom              | 2         | 5.88%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 19        | 55.88%  |
| Intel Ethernet Connection (2) I219-V                              | 3         | 8.82%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 5.88%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 2.94%   |
| Intel I211 Gigabit Network Connection                             | 1         | 2.94%   |
| Intel Ethernet Controller I225-V                                  | 1         | 2.94%   |
| Intel Ethernet Connection I217-V                                  | 1         | 2.94%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 2.94%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 2.94%   |
| Intel Ethernet Connection (2) I218-LM                             | 1         | 2.94%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 2.94%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 2.94%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 2.94%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 34        | 53.13%  |
| WiFi     | 30        | 46.88%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 25        | 64.1%   |
| Ethernet | 14        | 35.9%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 21        | 53.85%  |
| 1     | 17        | 43.59%  |
| 3     | 1         | 2.56%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 32        | 76.19%  |
| Yes  | 10        | 23.81%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 12        | 48%     |
| Realtek Semiconductor           | 5         | 20%     |
| Lite-On Technology              | 2         | 8%      |
| Cambridge Silicon Radio         | 2         | 8%      |
| Qualcomm Atheros Communications | 1         | 4%      |
| Foxconn / Hon Hai               | 1         | 4%      |
| Broadcom                        | 1         | 4%      |
| Apple                           | 1         | 4%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 12%     |
| Intel Bluetooth wireless interface                  | 3         | 12%     |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 12%     |
| Intel AX200 Bluetooth                               | 3         | 12%     |
| Realtek Bluetooth Radio                             | 2         | 8%      |
| Intel AX201 Bluetooth                               | 2         | 8%      |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 8%      |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 4%      |
| Lite-On Bluetooth Device                            | 1         | 4%      |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 4%      |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 4%      |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 4%      |
| Broadcom HP Portable Bumble Bee                     | 1         | 4%      |
| Apple Bluetooth USB Host Controller                 | 1         | 4%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 26        | 46.43%  |
| AMD                     | 17        | 30.36%  |
| Nvidia                  | 5         | 8.93%   |
| C-Media Electronics     | 2         | 3.57%   |
| SAVITECH                | 1         | 1.79%   |
| Realtek Semiconductor   | 1         | 1.79%   |
| Hewlett-Packard         | 1         | 1.79%   |
| GN Netcom               | 1         | 1.79%   |
| Cambridge Silicon Radio | 1         | 1.79%   |
| Astro Gaming            | 1         | 1.79%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 6         | 8.22%   |
| Intel Sunrise Point-LP HD Audio                                            | 3         | 4.11%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 4.11%   |
| Intel 200 Series PCH HD Audio                                              | 3         | 4.11%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3         | 4.11%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3         | 4.11%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 3         | 4.11%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 3         | 4.11%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 2.74%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 2.74%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 2.74%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 2.74%   |
| Intel Cannon Lake PCH cAVS                                                 | 2         | 2.74%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2         | 2.74%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 2.74%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2         | 2.74%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 2         | 2.74%   |
| SAVITECH MX3                                                               | 1         | 1.37%   |
| Realtek Semiconductor USB Audio                                            | 1         | 1.37%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 1.37%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 1.37%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 1.37%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 1.37%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 1.37%   |
| Intel Jasper Lake HD Audio                                                 | 1         | 1.37%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 1.37%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 1         | 1.37%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 1.37%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1         | 1.37%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 1.37%   |
| Hewlett-Packard USB Audio                                                  | 1         | 1.37%   |
| GN Netcom BTD-Q2                                                           | 1         | 1.37%   |
| Cambridge Silicon Radio Avantree C81                                       | 1         | 1.37%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                              | 1         | 1.37%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 1         | 1.37%   |
| Astro Gaming Astro A50                                                     | 1         | 1.37%   |
| AMD Vega 20 HDMI Audio [Radeon VII]                                        | 1         | 1.37%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 1         | 1.37%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 1         | 1.37%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 1         | 1.37%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 8         | 21.05%  |
| SK hynix            | 7         | 18.42%  |
| Crucial             | 6         | 15.79%  |
| G.Skill             | 5         | 13.16%  |
| Micron Technology   | 4         | 10.53%  |
| Kingston            | 4         | 10.53%  |
| Corsair             | 2         | 5.26%   |
| Ramsta              | 1         | 2.63%   |
| Nanya Technology    | 1         | 2.63%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 5.13%   |
| SK hynix RAM HMT451U6DFR8A-PB 4GB DIMM DDR3 1600MT/s             | 1         | 2.56%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 2.56%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s        | 1         | 2.56%   |
| SK hynix RAM HMA81GU6CJR8N-VK 8GB DIMM DDR4 2400MT/s             | 1         | 2.56%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 2.56%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 1         | 2.56%   |
| SK hynix RAM H9CCNNNCLGALAR-NUD 8GB Row Of Chips LPDDR3 1867MT/s | 1         | 2.56%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 1         | 2.56%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 1         | 2.56%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 1         | 2.56%   |
| Samsung RAM M471A2K43BB1-CRC 16GB SODIMM DDR4 2400MT/s           | 1         | 2.56%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 2.56%   |
| Samsung RAM K4UBE3D4AA-MGCL 8GB Row Of Chips LPDDR4 4267MT/s     | 1         | 2.56%   |
| Ramsta RAM 3200MHz-16G 16GB SODIMM DDR4 3200MT/s                 | 1         | 2.56%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s             | 1         | 2.56%   |
| Micron RAM Module 16GB SODIMM DDR4 3200MT/s                      | 1         | 2.56%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 1         | 2.56%   |
| Micron RAM 4ATF25664HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 1         | 2.56%   |
| Micron RAM ...d 4096MB SODIMM DDR3 1067MT/s                      | 1         | 2.56%   |
| Kingston RAM Module 8GB DIMM DDR4 3200MT/s                       | 1         | 2.56%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s             | 1         | 2.56%   |
| Kingston RAM ACR16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s           | 1         | 2.56%   |
| Kingston RAM 99U5663-007.A00G 16GB SODIMM DDR4 2667MT/s          | 1         | 2.56%   |
| G.Skill RAM F4-3600C16-8GTZR 8192MB DIMM DDR4 3600MT/s           | 1         | 2.56%   |
| G.Skill RAM F4-3200C16-16GTZN 16GB DIMM DDR4 3200MT/s            | 1         | 2.56%   |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s           | 1         | 2.56%   |
| G.Skill RAM F4-3000C15-8GRBB 8GB DIMM DDR4 3000MT/s              | 1         | 2.56%   |
| G.Skill RAM F4-2400C15-8GNT 8GB DIMM DDR4 2666MT/s               | 1         | 2.56%   |
| Crucial RAM CT8G4SFS824A.M8FE 8GB SODIMM DDR4 2667MT/s           | 1         | 2.56%   |
| Crucial RAM CT4G3S1067M.C16FKD 4GB SODIMM DDR3 1066MT/s          | 1         | 2.56%   |
| Crucial RAM CT32G48C40S5.M16A1 32GB SODIMM DDR5 4800MT/s         | 1         | 2.56%   |
| Crucial RAM CT16G4SFD824A.C16FDD 16GB SODIMM DDR4 2400MT/s       | 1         | 2.56%   |
| Crucial RAM BLS8G4D26BFSEK.8FD 8GB DIMM DDR4 3000MT/s            | 1         | 2.56%   |
| Crucial RAM BLS8G4D26BFSBK.8FBD 8GB DIMM DDR4 2667MT/s           | 1         | 2.56%   |
| Crucial RAM BL16G36C16U4R.M8FB1 16GB DIMM DDR4 3600MT/s          | 1         | 2.56%   |
| Corsair RAM CMK32GX4M2A2400C16 16GB DIMM DDR4 2400MT/s           | 1         | 2.56%   |
| Corsair RAM CMK32GX4M2A2400C14 16GB DIMM DDR4 2400MT/s           | 1         | 2.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 23        | 69.7%   |
| DDR3   | 6         | 18.18%  |
| SDRAM  | 1         | 3.03%   |
| LPDDR4 | 1         | 3.03%   |
| LPDDR3 | 1         | 3.03%   |
| DDR5   | 1         | 3.03%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 19        | 57.58%  |
| DIMM         | 11        | 33.33%  |
| Row Of Chips | 3         | 9.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 16        | 45.71%  |
| 4096  | 9         | 25.71%  |
| 16384 | 8         | 22.86%  |
| 32768 | 1         | 2.86%   |
| 2048  | 1         | 2.86%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 9         | 24.32%  |
| 2667  | 7         | 18.92%  |
| 2400  | 6         | 16.22%  |
| 1600  | 3         | 8.11%   |
| 3600  | 2         | 5.41%   |
| 3000  | 2         | 5.41%   |
| 4800  | 1         | 2.7%    |
| 4267  | 1         | 2.7%    |
| 4199  | 1         | 2.7%    |
| 2666  | 1         | 2.7%    |
| 1867  | 1         | 2.7%    |
| 1334  | 1         | 2.7%    |
| 1067  | 1         | 2.7%    |
| 1066  | 1         | 2.7%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 33.33%  |
| Hewlett-Packard     | 1         | 33.33%  |
| Canon               | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


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

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 8         | 27.59%  |
| Realtek Semiconductor                  | 3         | 10.34%  |
| IMC Networks                           | 3         | 10.34%  |
| Microdia                               | 2         | 6.9%    |
| Logitech                               | 2         | 6.9%    |
| WaveRider Communications               | 1         | 3.45%   |
| Suyin                                  | 1         | 3.45%   |
| Silicon Motion                         | 1         | 3.45%   |
| Quanta                                 | 1         | 3.45%   |
| Primax Electronics                     | 1         | 3.45%   |
| Microsoft                              | 1         | 3.45%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 3.45%   |
| Bison Electronics                      | 1         | 3.45%   |
| Apple                                  | 1         | 3.45%   |
| Acer                                   | 1         | 3.45%   |
| A4Tech                                 | 1         | 3.45%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony HD WebCam                                              | 4         | 13.79%  |
| Realtek Integrated_Webcam_HD                                   | 2         | 6.9%    |
| Microdia Integrated_Webcam_HD                                  | 2         | 6.9%    |
| WaveRider USB 2.0 Camera                                       | 1         | 3.45%   |
| Suyin 1.3M HD WebCam                                           | 1         | 3.45%   |
| Silicon Motion USB 2.0 PC Cam                                  | 1         | 3.45%   |
| Realtek FULL HD 1080P Webcam                                   | 1         | 3.45%   |
| Quanta HP Webcam                                               | 1         | 3.45%   |
| Primax Villem                                                  | 1         | 3.45%   |
| Microsoft LifeCam Cinema                                       | 1         | 3.45%   |
| Logitech Webcam C270                                           | 1         | 3.45%   |
| Logitech QuickCam Pro 9000                                     | 1         | 3.45%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 1         | 3.45%   |
| IMC Networks SunplusIT Integrated Camera                       | 1         | 3.45%   |
| IMC Networks Integrated Camera                                 | 1         | 3.45%   |
| Chicony Integrated Camera                                      | 1         | 3.45%   |
| Chicony HP Webcam                                              | 1         | 3.45%   |
| Chicony HP HD Camera                                           | 1         | 3.45%   |
| Chicony HP 5MP Camera                                          | 1         | 3.45%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 3.45%   |
| Bison Integrated Camera                                        | 1         | 3.45%   |
| Apple FaceTime HD Camera                                       | 1         | 3.45%   |
| Acer Integrated Camera                                         | 1         | 3.45%   |
| A4Tech USB Live camera                                         | 1         | 3.45%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 3         | 50%     |
| Synaptics             | 2         | 33.33%  |
| LighTuning Technology | 1         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader              | 1         | 16.67%  |
| Validity Sensors VFS451 Fingerprint Reader               | 1         | 16.67%  |
| Validity Sensors Synaptics WBDI                          | 1         | 16.67%  |
| Synaptics Metallica MOH Touch Fingerprint Reader         | 1         | 16.67%  |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 16.67%  |
| LighTuning EgisTec Touch Fingerprint Sensor              | 1         | 16.67%  |

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


| Model         | Computers | Percent |
|---------------|-----------|---------|
| Broadcom 5880 | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 29        | 72.5%   |
| 1     | 10        | 25%     |
| 2     | 1         | 2.5%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 6         | 50%     |
| Unassigned class         | 1         | 8.33%   |
| Sound                    | 1         | 8.33%   |
| Net/wireless             | 1         | 8.33%   |
| Graphics card            | 1         | 8.33%   |
| Communication controller | 1         | 8.33%   |
| Chipcard                 | 1         | 8.33%   |

