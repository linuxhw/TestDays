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

Total: 110

| Vendor  | Model                       | Form-Factor | Probe                                                      | Date         |
|---------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP      | ProBook 4540s               | Notebook    | [0646f227a6](https://linux-hardware.org/?probe=0646f227a6) | Jan 02, 2025 |
| ASUSTek | VivoBook_ASUSLaptop X150... | Notebook    | [2c4e1abbf9](https://linux-hardware.org/?probe=2c4e1abbf9) | Nov 09, 2024 |
| Lenovo  | ThinkPad L590 20Q7001HGE    | Notebook    | [ec2225a1f3](https://linux-hardware.org/?probe=ec2225a1f3) | Oct 12, 2024 |
| Lenovo  | G50-30 80G0                 | Notebook    | [53798578b1](https://linux-hardware.org/?probe=53798578b1) | Jun 19, 2024 |
| HP      | 250 G7 Notebook PC          | Notebook    | [637ffca44b](https://linux-hardware.org/?probe=637ffca44b) | Jun 16, 2024 |
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

![OS](./images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Siduction 12       | 19        | 30.65%  |
| Siduction 11       | 14        | 22.58%  |
| Siduction          | 12        | 19.35%  |
| Siduction Unstable | 11        | 17.74%  |
| Siduction 10       | 5         | 8.06%   |
| Siduction 21       | 1         | 1.61%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| Siduction | 49        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                       | Computers | Percent |
|-------------------------------|-----------|---------|
| 6.2.6-1-siduction-amd64       | 4         | 4.44%   |
| 6.2.8-1-siduction-amd64       | 3         | 3.33%   |
| 5.13.8-1-siduction-amd64      | 3         | 3.33%   |
| 6.5.3-1-siduction-amd64       | 2         | 2.22%   |
| 6.5.2-1-siduction-amd64       | 2         | 2.22%   |
| 6.2.2-6-siduction-amd64       | 2         | 2.22%   |
| 6.2.15-1-siduction-amd64      | 2         | 2.22%   |
| 6.2.13-1-siduction-amd64      | 2         | 2.22%   |
| 6.2.10-1-siduction-amd64      | 2         | 2.22%   |
| 6.1.14-1-siduction-amd64      | 2         | 2.22%   |
| 5.13.6-1-siduction-amd64      | 2         | 2.22%   |
| 5.12.12-1-siduction-amd64     | 2         | 2.22%   |
| 6.9.4-1-siduction-amd64       | 1         | 1.11%   |
| 6.8.10-1-siduction-amd64      | 1         | 1.11%   |
| 6.7.10-1-siduction-amd64      | 1         | 1.11%   |
| 6.6.8-1-siduction-amd64       | 1         | 1.11%   |
| 6.6.4-1-siduction-amd64       | 1         | 1.11%   |
| 6.6.2-1-siduction-amd64       | 1         | 1.11%   |
| 6.6.10-1-siduction-amd64      | 1         | 1.11%   |
| 6.5.6-1-siduction-amd64       | 1         | 1.11%   |
| 6.4.12-1-siduction-amd64      | 1         | 1.11%   |
| 6.3.7-1-siduction-amd64       | 1         | 1.11%   |
| 6.3.3-1-siduction-amd64       | 1         | 1.11%   |
| 6.3.10-1-siduction-amd64      | 1         | 1.11%   |
| 6.2.2-3-siduction-amd64       | 1         | 1.11%   |
| 6.2.11-1-siduction-amd64      | 1         | 1.11%   |
| 6.2.0-rc6-siduction-amd64     | 1         | 1.11%   |
| 6.12.7-1-siduction-amd64      | 1         | 1.11%   |
| 6.10.12-1-siduction-amd64     | 1         | 1.11%   |
| 6.1.10-2-siduction-amd64      | 1         | 1.11%   |
| 6.1.1-4-siduction-amd64       | 1         | 1.11%   |
| 6.0.9-1-siduction-amd64       | 1         | 1.11%   |
| 5.9.8-towo.3-siduction-amd64  | 1         | 1.11%   |
| 5.9.13-towo.1-siduction-amd64 | 1         | 1.11%   |
| 5.8.5-towo.1-siduction-amd64  | 1         | 1.11%   |
| 5.8.12-towo.1-siduction-amd64 | 1         | 1.11%   |
| 5.7.2-towo.1-siduction-amd64  | 1         | 1.11%   |
| 5.7.11-towo.2-siduction-amd64 | 1         | 1.11%   |
| 5.6.2-towo.1-siduction-amd64  | 1         | 1.11%   |
| 5.4.5-towo.2-siduction-amd64  | 1         | 1.11%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.2.6   | 4         | 4.44%   |
| 6.2.8   | 3         | 3.33%   |
| 6.2.2   | 3         | 3.33%   |
| 5.13.8  | 3         | 3.33%   |
| 6.5.3   | 2         | 2.22%   |
| 6.5.2   | 2         | 2.22%   |
| 6.2.15  | 2         | 2.22%   |
| 6.2.13  | 2         | 2.22%   |
| 6.2.10  | 2         | 2.22%   |
| 6.1.14  | 2         | 2.22%   |
| 5.14.0  | 2         | 2.22%   |
| 5.13.6  | 2         | 2.22%   |
| 5.12.12 | 2         | 2.22%   |
| 6.9.4   | 1         | 1.11%   |
| 6.8.10  | 1         | 1.11%   |
| 6.7.10  | 1         | 1.11%   |
| 6.6.8   | 1         | 1.11%   |
| 6.6.4   | 1         | 1.11%   |
| 6.6.2   | 1         | 1.11%   |
| 6.6.10  | 1         | 1.11%   |
| 6.5.6   | 1         | 1.11%   |
| 6.4.12  | 1         | 1.11%   |
| 6.3.7   | 1         | 1.11%   |
| 6.3.3   | 1         | 1.11%   |
| 6.3.10  | 1         | 1.11%   |
| 6.2.11  | 1         | 1.11%   |
| 6.2.0   | 1         | 1.11%   |
| 6.12.7  | 1         | 1.11%   |
| 6.10.12 | 1         | 1.11%   |
| 6.1.10  | 1         | 1.11%   |
| 6.1.1   | 1         | 1.11%   |
| 6.0.9   | 1         | 1.11%   |
| 5.9.8   | 1         | 1.11%   |
| 5.9.13  | 1         | 1.11%   |
| 5.8.5   | 1         | 1.11%   |
| 5.8.12  | 1         | 1.11%   |
| 5.7.2   | 1         | 1.11%   |
| 5.7.11  | 1         | 1.11%   |
| 5.6.2   | 1         | 1.11%   |
| 5.4.5   | 1         | 1.11%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.2     | 16        | 20%     |
| 5.13    | 8         | 10%     |
| 6.6     | 4         | 5%      |
| 6.5     | 4         | 5%      |
| 6.1     | 4         | 5%      |
| 5.16    | 4         | 5%      |
| 5.12    | 4         | 5%      |
| 6.3     | 3         | 3.75%   |
| 5.19    | 3         | 3.75%   |
| 5.18    | 3         | 3.75%   |
| 5.15    | 3         | 3.75%   |
| 5.14    | 3         | 3.75%   |
| 5.8     | 2         | 2.5%    |
| 5.7     | 2         | 2.5%    |
| 5.4     | 2         | 2.5%    |
| 5.3     | 2         | 2.5%    |
| 5.10    | 2         | 2.5%    |
| 6.9     | 1         | 1.25%   |
| 6.8     | 1         | 1.25%   |
| 6.7     | 1         | 1.25%   |
| 6.4     | 1         | 1.25%   |
| 6.12    | 1         | 1.25%   |
| 6.10    | 1         | 1.25%   |
| 6.0     | 1         | 1.25%   |
| 5.9     | 1         | 1.25%   |
| 5.6     | 1         | 1.25%   |
| 5.11    | 1         | 1.25%   |
| 4.20    | 1         | 1.25%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 49        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KDE5            | 33        | 60%     |
| XFCE            | 7         | 12.73%  |
| Unknown         | 5         | 9.09%   |
| X-Cinnamon      | 3         | 5.45%   |
| LXQt            | 3         | 5.45%   |
| Budgie          | 2         | 3.64%   |
| GNOME Flashback | 1         | 1.82%   |
| Cinnamon        | 1         | 1.82%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 40        | 76.92%  |
| Wayland | 10        | 19.23%  |
| Tty     | 2         | 3.85%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 36        | 67.92%  |
| Unknown | 11        | 20.75%  |
| LightDM | 3         | 5.66%   |
| TDM     | 1         | 1.89%   |
| GDM3    | 1         | 1.89%   |
| GDM     | 1         | 1.89%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| de_DE   | 21        | 40.38%  |
| en_US   | 15        | 28.85%  |
| Unknown | 4         | 7.69%   |
| en_GB   | 3         | 5.77%   |
| it_IT   | 2         | 3.85%   |
| de_AT   | 2         | 3.85%   |
| fr_FR   | 1         | 1.92%   |
| en_ZA   | 1         | 1.92%   |
| en_CA   | 1         | 1.92%   |
| de_CH   | 1         | 1.92%   |
| C       | 1         | 1.92%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 35        | 70%     |
| BIOS | 15        | 30%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 39        | 76.47%  |
| Btrfs   | 9         | 17.65%  |
| Tmpfs   | 1         | 1.96%   |
| Overlay | 1         | 1.96%   |
| Unknown | 1         | 1.96%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 34        | 68%     |
| Unknown | 9         | 18%     |
| MBR     | 7         | 14%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 46        | 92%     |
| Yes       | 4         | 8%      |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 37        | 74%     |
| Yes       | 13        | 26%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Lenovo           | 14        | 28.57%  |
| Hewlett-Packard  | 10        | 20.41%  |
| ASUSTek Computer | 8         | 16.33%  |
| Dell             | 6         | 12.24%  |
| Acer             | 4         | 8.16%   |
| ASRock           | 2         | 4.08%   |
| TUXEDO           | 1         | 2.04%   |
| NEWSMAY          | 1         | 2.04%   |
| MSI              | 1         | 2.04%   |
| Intel            | 1         | 2.04%   |
| Compal           | 1         | 2.04%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| TUXEDO Book BA1510                         | 1         | 2.04%   |
| MSI MS-7C56                                | 1         | 2.04%   |
| Lenovo ThinkPad X1 Tablet Gen 2 20JCA016JP | 1         | 2.04%   |
| Lenovo ThinkPad X1 Carbon 5th 20HRCTO1WW   | 1         | 2.04%   |
| Lenovo ThinkPad T580 20LAS1GG00            | 1         | 2.04%   |
| Lenovo ThinkPad T490 20N3SFKX00            | 1         | 2.04%   |
| Lenovo ThinkPad T410 253725G               | 1         | 2.04%   |
| Lenovo ThinkPad T14s Gen 1 20T1S15N00      | 1         | 2.04%   |
| Lenovo ThinkPad L590 20Q7001HGE            | 1         | 2.04%   |
| Lenovo ThinkPad L540 20AUS01H00            | 1         | 2.04%   |
| Lenovo ThinkPad Edge E540 20C6003AGE       | 1         | 2.04%   |
| Lenovo ThinkPad E590 20NB001AIX            | 1         | 2.04%   |
| Lenovo IdeaPad 3 15IIL05 81WE              | 1         | 2.04%   |
| Lenovo IdeaCentre AIO 3 27ALC6 F0FY0055GE  | 1         | 2.04%   |
| Lenovo IdeaCentre 310S-08ASR 90G9006DIX    | 1         | 2.04%   |
| Lenovo G50-30 80G0                         | 1         | 2.04%   |
| Intel NUC7i5DNKE                           | 1         | 2.04%   |
| HP ZBook 15 G6                             | 1         | 2.04%   |
| HP Z440 Workstation                        | 1         | 2.04%   |
| HP ProBook 640 G1                          | 1         | 2.04%   |
| HP ProBook 4540s                           | 1         | 2.04%   |
| HP ProBook 4520s                           | 1         | 2.04%   |
| HP OMEN 30L Desktop GT13-0xxx              | 1         | 2.04%   |
| HP Laptop 17-ca1xxx                        | 1         | 2.04%   |
| HP Laptop 15-db0xxx                        | 1         | 2.04%   |
| HP EliteBook 865 16 inch G9 Notebook PC    | 1         | 2.04%   |
| HP 250 G7 Notebook PC                      | 1         | 2.04%   |
| Dell Vostro 15 3510                        | 1         | 2.04%   |
| Dell OptiPlex 9020                         | 1         | 2.04%   |
| Dell OptiPlex 5040                         | 1         | 2.04%   |
| Dell OptiPlex 3050                         | 1         | 2.04%   |
| Dell Latitude 5491                         | 1         | 2.04%   |
| Dell Inspiron 7415 2-in-1                  | 1         | 2.04%   |
| Compal NBLBX                               | 1         | 2.04%   |
| ASUS ZenBook UX325JA_UX325JA               | 1         | 2.04%   |
| ASUS VivoBook_ASUSLaptop X1504ZA_X1504ZA   | 1         | 2.04%   |
| ASUS ROG STRIX Z370-F GAMING               | 1         | 2.04%   |
| ASUS ROG STRIX B550-A GAMING               | 1         | 2.04%   |
| ASUS PRIME Z270-A                          | 1         | 2.04%   |
| ASUS BU201LA                               | 1         | 2.04%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 10        | 20.41%  |
| HP ProBook        | 3         | 6.12%   |
| Dell OptiPlex     | 3         | 6.12%   |
| Acer Aspire       | 3         | 6.12%   |
| Lenovo IdeaCentre | 2         | 4.08%   |
| HP Laptop         | 2         | 4.08%   |
| ASUS ROG          | 2         | 4.08%   |
| TUXEDO Book       | 1         | 2.04%   |
| MSI MS-7C56       | 1         | 2.04%   |
| Lenovo IdeaPad    | 1         | 2.04%   |
| Lenovo G50-30     | 1         | 2.04%   |
| Intel NUC7i5DNKE  | 1         | 2.04%   |
| HP ZBook          | 1         | 2.04%   |
| HP Z440           | 1         | 2.04%   |
| HP OMEN           | 1         | 2.04%   |
| HP EliteBook      | 1         | 2.04%   |
| HP 250            | 1         | 2.04%   |
| Dell Vostro       | 1         | 2.04%   |
| Dell Latitude     | 1         | 2.04%   |
| Dell Inspiron     | 1         | 2.04%   |
| Compal NBLBX      | 1         | 2.04%   |
| ASUS ZenBook      | 1         | 2.04%   |
| ASUS VivoBook     | 1         | 2.04%   |
| ASUS PRIME        | 1         | 2.04%   |
| ASUS BU201LA      | 1         | 2.04%   |
| ASUS B150M-A      | 1         | 2.04%   |
| ASUS A0000001     | 1         | 2.04%   |
| ASRock B550       | 1         | 2.04%   |
| ASRock B450       | 1         | 2.04%   |
| Acer Swift        | 1         | 2.04%   |
| Unknown           | 1         | 2.04%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 8         | 16.33%  |
| 2019 | 7         | 14.29%  |
| 2014 | 6         | 12.24%  |
| 2018 | 5         | 10.2%   |
| 2021 | 4         | 8.16%   |
| 2017 | 4         | 8.16%   |
| 2022 | 3         | 6.12%   |
| 2016 | 3         | 6.12%   |
| 2013 | 3         | 6.12%   |
| 2010 | 2         | 4.08%   |
| 2015 | 1         | 2.04%   |
| 2012 | 1         | 2.04%   |
| 2011 | 1         | 2.04%   |
| 2009 | 1         | 2.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 30        | 61.22%  |
| Desktop     | 15        | 30.61%  |
| Tablet      | 1         | 2.04%   |
| Convertible | 1         | 2.04%   |
| Mini pc     | 1         | 2.04%   |
| All in one  | 1         | 2.04%   |

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
| No   | 49        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 13        | 26%     |
| 16.01-24.0  | 13        | 26%     |
| 32.01-64.0  | 10        | 20%     |
| 8.01-16.0   | 10        | 20%     |
| 3.01-4.0    | 2         | 4%      |
| 64.01-256.0 | 1         | 2%      |
| Unknown     | 1         | 2%      |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 17        | 26.15%  |
| 3.01-4.0   | 15        | 23.08%  |
| 2.01-3.0   | 14        | 21.54%  |
| 1.01-2.0   | 9         | 13.85%  |
| 8.01-16.0  | 4         | 6.15%   |
| 0.51-1.0   | 3         | 4.62%   |
| 16.01-24.0 | 1         | 1.54%   |
| 0.01-0.5   | 1         | 1.54%   |
| Unknown    | 1         | 1.54%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 31        | 60.78%  |
| 2      | 10        | 19.61%  |
| 4      | 5         | 9.8%    |
| 3      | 3         | 5.88%   |
| 6      | 1         | 1.96%   |
| 5      | 1         | 1.96%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 33        | 64.71%  |
| Yes       | 18        | 35.29%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 43        | 87.76%  |
| No        | 6         | 12.24%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 40        | 81.63%  |
| No        | 9         | 18.37%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 33        | 63.46%  |
| No        | 19        | 36.54%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| Germany      | 21        | 41.18%  |
| USA          | 8         | 15.69%  |
| Austria      | 4         | 7.84%   |
| UK           | 3         | 5.88%   |
| Italy        | 3         | 5.88%   |
| Canada       | 3         | 5.88%   |
| Sweden       | 2         | 3.92%   |
| Switzerland  | 1         | 1.96%   |
| South Africa | 1         | 1.96%   |
| Nigeria      | 1         | 1.96%   |
| Netherlands  | 1         | 1.96%   |
| Japan        | 1         | 1.96%   |
| Israel       | 1         | 1.96%   |
| France       | 1         | 1.96%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Computers | Percent |
|-----------------|-----------|---------|
| Munich          | 5         | 7.25%   |
| Vienna          | 3         | 4.35%   |
| Berlin          | 3         | 4.35%   |
| Suisun          | 2         | 2.9%    |
| Stuttgart       | 2         | 2.9%    |
| Stockholm       | 2         | 2.9%    |
| Schrobenhausen  | 2         | 2.9%    |
| Hamburg         | 2         | 2.9%    |
| Zurich          | 1         | 1.45%   |
| Wiener Neustadt | 1         | 1.45%   |
| Unterbergla     | 1         | 1.45%   |
| Turin           | 1         | 1.45%   |
| Trier           | 1         | 1.45%   |
| Toronto         | 1         | 1.45%   |
| Tokyo           | 1         | 1.45%   |
| Sidney          | 1         | 1.45%   |
| Savannah        | 1         | 1.45%   |
| Sanford         | 1         | 1.45%   |
| San Francisco   | 1         | 1.45%   |
| Salzburg        | 1         | 1.45%   |
| Reading         | 1         | 1.45%   |
| Portland        | 1         | 1.45%   |
| Piea            | 1         | 1.45%   |
| Paris           | 1         | 1.45%   |
| Papenburg       | 1         | 1.45%   |
| Oranienburg     | 1         | 1.45%   |
| Oberboihingen   | 1         | 1.45%   |
| Mittenwald      | 1         | 1.45%   |
| Milan           | 1         | 1.45%   |
| Merseburg       | 1         | 1.45%   |
| Marion          | 1         | 1.45%   |
| Mannheim        | 1         | 1.45%   |
| Malmo           | 1         | 1.45%   |
| Leipzig         | 1         | 1.45%   |
| Leimen          | 1         | 1.45%   |
| Langewiesen     | 1         | 1.45%   |
| Landau          | 1         | 1.45%   |
| Lagos           | 1         | 1.45%   |
| Kensington      | 1         | 1.45%   |
| Johannesburg    | 1         | 1.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 16        | 26     | 20%     |
| WDC                 | 13        | 30     | 16.25%  |
| Seagate             | 8         | 17     | 10%     |
| Toshiba             | 7         | 16     | 8.75%   |
| Sandisk             | 6         | 13     | 7.5%    |
| SK hynix            | 5         | 14     | 6.25%   |
| Kingston            | 5         | 5      | 6.25%   |
| Crucial             | 5         | 17     | 6.25%   |
| Intel               | 4         | 8      | 5%      |
| Unknown             | 1         | 1      | 1.25%   |
| SSSTC               | 1         | 1      | 1.25%   |
| Silicon Motion      | 1         | 1      | 1.25%   |
| OCZ                 | 1         | 3      | 1.25%   |
| Mushkin             | 1         | 3      | 1.25%   |
| Micron Technology   | 1         | 1      | 1.25%   |
| Lenovo              | 1         | 1      | 1.25%   |
| Hitachi             | 1         | 1      | 1.25%   |
| HGST                | 1         | 11     | 1.25%   |
| GRITRONIX           | 1         | 1      | 1.25%   |
| Corsair             | 1         | 3      | 1.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| WDC WD10JPVX-22JC3T0 1TB                          | 3         | 3.33%   |
| Toshiba MQ04ABF100 1TB                            | 2         | 2.22%   |
| SanDisk NVMe SSD Drive 1TB                        | 2         | 2.22%   |
| Samsung SSD 850 EVO 250GB                         | 2         | 2.22%   |
| Kingston SA400S37240G 240GB SSD                   | 2         | 2.22%   |
| Crucial CT500MX500SSD1 500GB                      | 2         | 2.22%   |
| Crucial CT1000MX500SSD1 1TB                       | 2         | 2.22%   |
| WDC WDS400T2B0A-00SM50 4TB SSD                    | 1         | 1.11%   |
| WDC WDS200T2B0B-00YS70 2TB SSD                    | 1         | 1.11%   |
| WDC WDS100T2B0C-00PXH0 1TB                        | 1         | 1.11%   |
| WDC WD60EZAZ-00SF3B0 6TB                          | 1         | 1.11%   |
| WDC WD40EZAZ-00SF3B0 4TB                          | 1         | 1.11%   |
| WDC WD3200BPVT-22JJ5T0 320GB                      | 1         | 1.11%   |
| WDC WD20EZRZ-00Z5HB0 2TB                          | 1         | 1.11%   |
| WDC WD20EFRX-68EUZN0 2TB                          | 1         | 1.11%   |
| WDC WD10SPZX-60Z10T0 1TB                          | 1         | 1.11%   |
| WDC WD10JPVX-60JC3T1 1TB                          | 1         | 1.11%   |
| WDC WD10EADX-00TDHB0 1TB                          | 1         | 1.11%   |
| WDC WD BLACK SDBPNTY-512G-1106 512GB              | 1         | 1.11%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB              | 1         | 1.11%   |
| Unknown MMC Card  64GB                            | 1         | 1.11%   |
| Toshiba THNSNK256GVN8 256GB SSD                   | 1         | 1.11%   |
| Toshiba THNSF5512GPUK 512GB                       | 1         | 1.11%   |
| Toshiba RD400 256GB                               | 1         | 1.11%   |
| Toshiba MQ01ACF032 320GB                          | 1         | 1.11%   |
| Toshiba KBG30ZMT256G 256GB                        | 1         | 1.11%   |
| SSSTC CL4-3D256-Q11 NVMe 256GB                    | 1         | 1.11%   |
| SK hynix SKHynix_HFS256GD9TNG-L5B0B 256GB         | 1         | 1.11%   |
| SK hynix SC308 SATA 128GB SSD                     | 1         | 1.11%   |
| SK hynix NVMe SSD Drive 512GB                     | 1         | 1.11%   |
| SK hynix BC711 NVMe 1TB                           | 1         | 1.11%   |
| SK hynix BC501 HFM256GDJTNG-8310A 256GB           | 1         | 1.11%   |
| Silicon Motion SM2262/SM2262EN SSD Controller 2TB | 1         | 1.11%   |
| Seagate ST9640320AS 640GB                         | 1         | 1.11%   |
| Seagate ST9500420AS 500GB                         | 1         | 1.11%   |
| Seagate ST6000DM003-2CY186 6TB                    | 1         | 1.11%   |
| Seagate ST500LT012-1DG142 500GB                   | 1         | 1.11%   |
| Seagate ST4000LM016-1N2170 4TB                    | 1         | 1.11%   |
| Seagate ST32000542AS 2TB                          | 1         | 1.11%   |
| Seagate ST31000524AS 1TB                          | 1         | 1.11%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 10        | 21     | 41.67%  |
| Seagate             | 8         | 17     | 33.33%  |
| Toshiba             | 3         | 11     | 12.5%   |
| Samsung Electronics | 1         | 1      | 4.17%   |
| Hitachi             | 1         | 1      | 4.17%   |
| HGST                | 1         | 11     | 4.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


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

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 28        | 52     | 40%     |
| SSD  | 21        | 58     | 30%     |
| HDD  | 20        | 62     | 28.57%  |
| MMC  | 1         | 1      | 1.43%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 33        | 120    | 53.23%  |
| NVMe | 28        | 52     | 45.16%  |
| MMC  | 1         | 1      | 1.61%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 21        | 50     | 47.73%  |
| 0.51-1.0   | 11        | 32     | 25%     |
| 1.01-2.0   | 6         | 19     | 13.64%  |
| 3.01-4.0   | 3         | 14     | 6.82%   |
| 4.01-10.0  | 2         | 2      | 4.55%   |
| 2.01-3.0   | 1         | 3      | 2.27%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 15        | 27.78%  |
| 101-250        | 7         | 12.96%  |
| 1001-2000      | 7         | 12.96%  |
| More than 3000 | 6         | 11.11%  |
| 501-1000       | 6         | 11.11%  |
| Unknown        | 5         | 9.26%   |
| 1-20           | 3         | 5.56%   |
| 21-50          | 2         | 3.7%    |
| 2001-3000      | 2         | 3.7%    |
| 51-100         | 1         | 1.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 19        | 30.16%  |
| 101-250        | 9         | 14.29%  |
| 51-100         | 8         | 12.7%   |
| 251-500        | 5         | 7.94%   |
| 21-50          | 5         | 7.94%   |
| Unknown        | 5         | 7.94%   |
| 1001-2000      | 4         | 6.35%   |
| 501-1000       | 4         | 6.35%   |
| More than 3000 | 3         | 4.76%   |
| 2001-3000      | 1         | 1.59%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                   | Computers | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| WDC WD20EZRZ-00Z5HB0 2TB                | 1         | 6      | 10%     |
| SK hynix SC308 SATA 128GB SSD           | 1         | 9      | 10%     |
| SK hynix BC501 HFM256GDJTNG-8310A 256GB | 1         | 1      | 10%     |
| Seagate ST32000542AS 2TB                | 1         | 3      | 10%     |
| Samsung Electronics SSD 870 EVO 4TB     | 1         | 1      | 10%     |
| OCZ VERTEX3 120GB SSD                   | 1         | 3      | 10%     |
| Kingston SA400S37240G 240GB SSD         | 1         | 1      | 10%     |
| Hitachi HTS725025A9A364 250GB           | 1         | 1      | 10%     |
| HGST HTS725050A7E630 500GB              | 1         | 11     | 10%     |
| Crucial CT500MX500SSD1 500GB            | 1         | 1      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| SK hynix            | 2         | 10     | 20%     |
| WDC                 | 1         | 6      | 10%     |
| Seagate             | 1         | 3      | 10%     |
| Samsung Electronics | 1         | 1      | 10%     |
| OCZ                 | 1         | 3      | 10%     |
| Kingston            | 1         | 1      | 10%     |
| Hitachi             | 1         | 1      | 10%     |
| HGST                | 1         | 11     | 10%     |
| Crucial             | 1         | 1      | 10%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 6      | 25%     |
| Seagate | 1         | 3      | 25%     |
| Hitachi | 1         | 1      | 25%     |
| HGST    | 1         | 11     | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 5         | 15     | 50%     |
| HDD  | 4         | 21     | 40%     |
| NVMe | 1         | 1      | 10%     |

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
| Works    | 40        | 111    | 67.8%   |
| Detected | 11        | 25     | 18.64%  |
| Malfunc  | 8         | 37     | 13.56%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 32        | 45.07%  |
| AMD                            | 12        | 16.9%   |
| SanDisk                        | 6         | 8.45%   |
| Samsung Electronics            | 5         | 7.04%   |
| SK hynix                       | 4         | 5.63%   |
| Toshiba America Info Systems   | 3         | 4.23%   |
| Solid State Storage Technology | 1         | 1.41%   |
| Silicon Motion                 | 1         | 1.41%   |
| Phison Electronics             | 1         | 1.41%   |
| OCZ Technology Group           | 1         | 1.41%   |
| Micron/Crucial Technology      | 1         | 1.41%   |
| Micron Technology              | 1         | 1.41%   |
| Lenovo                         | 1         | 1.41%   |
| Kingston Technology Company    | 1         | 1.41%   |
| ASMedia Technology             | 1         | 1.41%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 9         | 11.54%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 5.13%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 3         | 3.85%   |
| AMD 500 Series Chipset SATA Controller                                         | 3         | 3.85%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)            | 2         | 2.56%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 2         | 2.56%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 2         | 2.56%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 2.56%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 2.56%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 2.56%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 2.56%   |
| AMD 400 Series Chipset SATA Controller                                         | 2         | 2.56%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 1         | 1.28%   |
| Solid State Storage CL4-8D512 NVMe SSD M.2 (DRAM-less)                         | 1         | 1.28%   |
| SK hynix PC601 NVMe Solid State Drive                                          | 1         | 1.28%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 1         | 1.28%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 1         | 1.28%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                          | 1         | 1.28%   |
| SanDisk PC SN735 / WD_BLACK SN750 SE NVMe SSD (DRAM-less)                      | 1         | 1.28%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                          | 1         | 1.28%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 1         | 1.28%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1         | 1.28%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 1         | 1.28%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                    | 1         | 1.28%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                  | 1         | 1.28%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 1.28%   |
| Phison E7 NVMe Controller                                                      | 1         | 1.28%   |
| OCZ Group RD400/400A SSD                                                       | 1         | 1.28%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton]                                      | 1         | 1.28%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 1         | 1.28%   |
| Lenovo LENSE20256GMSP34MEAT2TA                                                 | 1         | 1.28%   |
| Kingston Company A2000 NVMe SSD [SM2263EN]                                     | 1         | 1.28%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 1.28%   |
| Intel Volume Management Device NVMe RAID Controller                            | 1         | 1.28%   |
| Intel Tiger Lake-LP SATA Controller                                            | 1         | 1.28%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 1         | 1.28%   |
| Intel SSD 665p Series [Neptune Harbor Refresh]                                 | 1         | 1.28%   |
| Intel SSD 660P Series                                                          | 1         | 1.28%   |
| Intel SATA Controller [RAID mode]                                              | 1         | 1.28%   |
| Intel Optane NVME SSD H10 with Solid State Storage [Teton Glacier]             | 1         | 1.28%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 36        | 52.17%  |
| NVMe | 27        | 39.13%  |
| RAID | 4         | 5.8%    |
| IDE  | 2         | 2.9%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 36        | 73.47%  |
| AMD    | 13        | 26.53%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 4.08%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 4.08%   |
| AMD Ryzen 5 3600 6-Core Processor             | 2         | 4.08%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 4.08%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz           | 1         | 2.04%   |
| Intel Pentium Silver N6005 @ 2.00GHz          | 1         | 2.04%   |
| Intel Pentium CPU G4400T @ 2.90GHz            | 1         | 2.04%   |
| Intel Core i7-9850H CPU @ 2.60GHz             | 1         | 2.04%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 1         | 2.04%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 1         | 2.04%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 2.04%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 2.04%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz            | 1         | 2.04%   |
| Intel Core i7-10700K CPU @ 3.80GHz            | 1         | 2.04%   |
| Intel Core i7-10610U CPU @ 1.80GHz            | 1         | 2.04%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 1         | 2.04%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 1         | 2.04%   |
| Intel Core i5-7Y54 CPU @ 1.20GHz              | 1         | 2.04%   |
| Intel Core i5-7600K CPU @ 3.80GHz             | 1         | 2.04%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 1         | 2.04%   |
| Intel Core i5-6600K CPU @ 3.50GHz             | 1         | 2.04%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 1         | 2.04%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 2.04%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 2.04%   |
| Intel Core i5-4590S CPU @ 3.00GHz             | 1         | 2.04%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 2.04%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 1         | 2.04%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 1         | 2.04%   |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 1         | 2.04%   |
| Intel Core i5 CPU M 430 @ 2.27GHz             | 1         | 2.04%   |
| Intel Core i3-4000M CPU @ 2.40GHz             | 1         | 2.04%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 1         | 2.04%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 1         | 2.04%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 1         | 2.04%   |
| Intel 12th Gen Core i3-1215U                  | 1         | 2.04%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 1         | 2.04%   |
| AMD Ryzen 9 PRO 6950HS with Radeon Graphics   | 1         | 2.04%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 1         | 2.04%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 1         | 2.04%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 1         | 2.04%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 17        | 34.69%  |
| Intel Core i7        | 10        | 20.41%  |
| AMD Ryzen 5          | 7         | 14.29%  |
| Other                | 3         | 6.12%   |
| Intel Core i3        | 3         | 6.12%   |
| AMD Ryzen 9          | 2         | 4.08%   |
| AMD Ryzen 7          | 2         | 4.08%   |
| Intel Xeon           | 1         | 2.04%   |
| Intel Pentium Silver | 1         | 2.04%   |
| Intel Pentium        | 1         | 2.04%   |
| Intel Celeron        | 1         | 2.04%   |
| AMD FX               | 1         | 2.04%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 19        | 38.78%  |
| 2      | 17        | 34.69%  |
| 6      | 8         | 16.33%  |
| 8      | 4         | 8.16%   |
| 12     | 1         | 2.04%   |

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
| 2      | 41        | 83.67%  |
| 1      | 8         | 16.33%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 48        | 97.96%  |
| Unknown        | 1         | 2.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 25        | 44.64%  |
| 0x08701021 | 3         | 5.36%   |
| 0x806ec    | 2         | 3.57%   |
| 0x706e5    | 2         | 3.57%   |
| 0x506e3    | 2         | 3.57%   |
| 0x20655    | 2         | 3.57%   |
| 0x08108102 | 2         | 3.57%   |
| 0x0800820d | 2         | 3.57%   |
| 0xa0655    | 1         | 1.79%   |
| 0x906ea    | 1         | 1.79%   |
| 0x906e9    | 1         | 1.79%   |
| 0x806eb    | 1         | 1.79%   |
| 0x806e9    | 1         | 1.79%   |
| 0x306f2    | 1         | 1.79%   |
| 0x306d4    | 1         | 1.79%   |
| 0x306c3    | 1         | 1.79%   |
| 0x206a7    | 1         | 1.79%   |
| 0x20652    | 1         | 1.79%   |
| 0x0a404102 | 1         | 1.79%   |
| 0x08608103 | 1         | 1.79%   |
| 0x08108109 | 1         | 1.79%   |
| 0x0810100b | 1         | 1.79%   |
| 0x06006705 | 1         | 1.79%   |
| 0x06003106 | 1         | 1.79%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 13        | 26.53%  |
| Haswell          | 6         | 12.24%  |
| Zen+             | 4         | 8.16%   |
| Skylake          | 4         | 8.16%   |
| Zen 2            | 3         | 6.12%   |
| Westmere         | 3         | 6.12%   |
| Unknown          | 3         | 6.12%   |
| IceLake          | 2         | 4.08%   |
| Zen              | 1         | 2.04%   |
| Tremont          | 1         | 2.04%   |
| TigerLake        | 1         | 2.04%   |
| Steamroller      | 1         | 2.04%   |
| Silvermont       | 1         | 2.04%   |
| SandyBridge      | 1         | 2.04%   |
| IvyBridge        | 1         | 2.04%   |
| Excavator        | 1         | 2.04%   |
| CometLake        | 1         | 2.04%   |
| Broadwell        | 1         | 2.04%   |
| Alderlake Hybrid | 1         | 2.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 29        | 52.73%  |
| AMD    | 17        | 30.91%  |
| Nvidia | 9         | 16.36%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 4         | 7.02%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 3         | 5.26%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 3         | 5.26%   |
| Intel Iris Plus Graphics G7                                                 | 2         | 3.51%   |
| Intel HD Graphics 620                                                       | 2         | 3.51%   |
| Intel Core Processor Integrated Graphics Controller                         | 2         | 3.51%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2         | 3.51%   |
| AMD Lucienne                                                                | 2         | 3.51%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                               | 1         | 1.75%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1         | 1.75%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1         | 1.75%   |
| Nvidia GM108M [GeForce MX130]                                               | 1         | 1.75%   |
| Nvidia GK208M [GeForce GT 740M]                                             | 1         | 1.75%   |
| Nvidia GK104 [GeForce GTX 770]                                              | 1         | 1.75%   |
| Nvidia GF119 [NVS 310]                                                      | 1         | 1.75%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]        | 1         | 1.75%   |
| Nvidia GA106 [Geforce RTX 3050]                                             | 1         | 1.75%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1         | 1.75%   |
| Intel UHD Graphics 620                                                      | 1         | 1.75%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 1         | 1.75%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 1         | 1.75%   |
| Intel JasperLake [UHD Graphics]                                             | 1         | 1.75%   |
| Intel HD Graphics 615                                                       | 1         | 1.75%   |
| Intel HD Graphics 5500                                                      | 1         | 1.75%   |
| Intel HD Graphics 530                                                       | 1         | 1.75%   |
| Intel HD Graphics 510                                                       | 1         | 1.75%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 1         | 1.75%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 1         | 1.75%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 1         | 1.75%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 1         | 1.75%   |
| Intel Alder Lake-UP3 GT1 [UHD Graphics]                                     | 1         | 1.75%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 1         | 1.75%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 1         | 1.75%   |
| AMD Vega 20 [Radeon VII]                                                    | 1         | 1.75%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                    | 1         | 1.75%   |
| AMD RV711/M93 [Mobility Radeon HD 4350/4550/530v/540v/545v / FirePro RG220] | 1         | 1.75%   |
| AMD Rembrandt [Radeon 680M]                                                 | 1         | 1.75%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 1         | 1.75%   |
| AMD Opal XT [Radeon R7 M265/M365X/M465]                                     | 1         | 1.75%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 1         | 1.75%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 25        | 49.02%  |
| 1 x AMD        | 15        | 29.41%  |
| 1 x Nvidia     | 6         | 11.76%  |
| Intel + Nvidia | 3         | 5.88%   |
| 2 x AMD        | 1         | 1.96%   |
| Intel + AMD    | 1         | 1.96%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 44        | 86.27%  |
| Proprietary | 6         | 11.76%  |
| Unknown     | 1         | 1.96%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 31        | 58.49%  |
| 0.01-0.5   | 7         | 13.21%  |
| 7.01-8.0   | 4         | 7.55%   |
| 1.01-2.0   | 4         | 7.55%   |
| 8.01-16.0  | 2         | 3.77%   |
| 0.51-1.0   | 2         | 3.77%   |
| 5.01-6.0   | 1         | 1.89%   |
| 3.01-4.0   | 1         | 1.89%   |
| 2.01-3.0   | 1         | 1.89%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Chimei Innolux      | 11        | 17.46%  |
| LG Display          | 8         | 12.7%   |
| AU Optronics        | 6         | 9.52%   |
| Acer                | 6         | 9.52%   |
| Samsung Electronics | 5         | 7.94%   |
| BOE                 | 5         | 7.94%   |
| Hewlett-Packard     | 4         | 6.35%   |
| Lenovo              | 3         | 4.76%   |
| Dell                | 3         | 4.76%   |
| Philips             | 2         | 3.17%   |
| Goldstar            | 2         | 3.17%   |
| AOC                 | 2         | 3.17%   |
| STD                 | 1         | 1.59%   |
| Sony                | 1         | 1.59%   |
| MSI                 | 1         | 1.59%   |
| Eizo                | 1         | 1.59%   |
| BenQ                | 1         | 1.59%   |
| ASUSTek Computer    | 1         | 1.59%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SyncMaster SAM021E 1680x1050 433x271mm 20.1-inch  | 2         | 3.03%   |
| STD HDMI TV STD00C7 1920x1080 698x392mm 31.5-inch                     | 1         | 1.52%   |
| Sony SAMSUNG SNY5203 1920x540                                         | 1         | 1.52%   |
| Samsung Electronics SMB2240W SAM0699 1680x1050 459x296mm 21.5-inch    | 1         | 1.52%   |
| Samsung Electronics S27E590 SAM0C5D 1920x1080 598x336mm 27.0-inch     | 1         | 1.52%   |
| Samsung Electronics S27E391 SAM0C15 1920x1080 598x336mm 27.0-inch     | 1         | 1.52%   |
| Samsung Electronics LCD Monitor SDC4244 2160x1440 254x169mm 12.0-inch | 1         | 1.52%   |
| Philips PHL 241P6E PHL08F7 1920x1080 530x300mm 24.0-inch              | 1         | 1.52%   |
| Philips 200V4 PHLC0BF 1600x900 432x240mm 19.5-inch                    | 1         | 1.52%   |
| MSI G241 MSI3BA4 1920x1080 527x296mm 23.8-inch                        | 1         | 1.52%   |
| LG Display LCD Monitor LGD06FF 1920x1080 344x194mm 15.5-inch          | 1         | 1.52%   |
| LG Display LCD Monitor LGD059D 1920x1080 309x174mm 14.0-inch          | 1         | 1.52%   |
| LG Display LCD Monitor LGD051D 1920x1080 309x174mm 14.0-inch          | 1         | 1.52%   |
| LG Display LCD Monitor LGD045E 1366x768 309x174mm 14.0-inch           | 1         | 1.52%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch          | 1         | 1.52%   |
| LG Display LCD Monitor LGD03DE 1600x900 382x215mm 17.3-inch           | 1         | 1.52%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch           | 1         | 1.52%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch           | 1         | 1.52%   |
| Lenovo LEN-A-A LENF918 1920x1080 596x335mm 26.9-inch                  | 1         | 1.52%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 1         | 1.52%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x189mm 14.1-inch               | 1         | 1.52%   |
| Hewlett-Packard X27i HPN3678 2560x1440 597x336mm 27.0-inch            | 1         | 1.52%   |
| Hewlett-Packard E243i HPN3463 1920x1200 518x324mm 24.1-inch           | 1         | 1.52%   |
| Hewlett-Packard 27f HPN354B 1920x1080 598x336mm 27.0-inch             | 1         | 1.52%   |
| Hewlett-Packard 27f HPN354A 1920x1080 598x336mm 27.0-inch             | 1         | 1.52%   |
| Hewlett-Packard 23xw HWP318C 1920x1080 509x286mm 23.0-inch            | 1         | 1.52%   |
| Hewlett-Packard 23cw HWP3187 1920x1080 509x286mm 23.0-inch            | 1         | 1.52%   |
| Goldstar W1946 GSM4BCD 1360x768 406x229mm 18.4-inch                   | 1         | 1.52%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch               | 1         | 1.52%   |
| Eizo EV3285 ENC2979 3840x2160 698x393mm 31.5-inch                     | 1         | 1.52%   |
| Dell UP3216Q DEL40C2 3840x2160 700x400mm 31.7-inch                    | 1         | 1.52%   |
| Dell U2415 DELA0BC 1920x1200 518x324mm 24.1-inch                      | 1         | 1.52%   |
| Dell U2414H DELA0B2 1920x1080 527x296mm 23.8-inch                     | 1         | 1.52%   |
| Chimei Innolux LCD Monitor CMN175A 1920x1080 381x214mm 17.2-inch      | 1         | 1.52%   |
| Chimei Innolux LCD Monitor CMN1610 1920x1200 344x215mm 16.0-inch      | 1         | 1.52%   |
| Chimei Innolux LCD Monitor CMN15F6 1920x1080 344x193mm 15.5-inch      | 1         | 1.52%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 1         | 1.52%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 1         | 1.52%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 1         | 1.52%   |
| Chimei Innolux LCD Monitor CMN15D3 1920x1080 344x193mm 15.5-inch      | 1         | 1.52%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 33        | 56.9%   |
| 1366x768 (WXGA)    | 7         | 12.07%  |
| 3840x2160 (4K)     | 4         | 6.9%    |
| 1680x1050 (WSXGA+) | 3         | 5.17%   |
| 2560x1440 (QHD)    | 2         | 3.45%   |
| 1600x900 (HD+)     | 2         | 3.45%   |
| 3840x1080          | 1         | 1.72%   |
| 3440x1440          | 1         | 1.72%   |
| 2160x1440          | 1         | 1.72%   |
| 1920x540           | 1         | 1.72%   |
| 1920x1200 (WUXGA)  | 1         | 1.72%   |
| 1440x900 (WXGA+)   | 1         | 1.72%   |
| 1360x768           | 1         | 1.72%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 18        | 29.03%  |
| 27      | 8         | 12.9%   |
| 14      | 7         | 11.29%  |
| 23      | 4         | 6.45%   |
| 31      | 3         | 4.84%   |
| 24      | 3         | 4.84%   |
| 20      | 2         | 3.23%   |
| 17      | 2         | 3.23%   |
| 13      | 2         | 3.23%   |
| 12      | 2         | 3.23%   |
| 49      | 1         | 1.61%   |
| 40      | 1         | 1.61%   |
| 34      | 1         | 1.61%   |
| 32      | 1         | 1.61%   |
| 26      | 1         | 1.61%   |
| 22      | 1         | 1.61%   |
| 21      | 1         | 1.61%   |
| 19      | 1         | 1.61%   |
| 18      | 1         | 1.61%   |
| 16      | 1         | 1.61%   |
| Unknown | 1         | 1.61%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 27        | 46.55%  |
| 501-600     | 14        | 24.14%  |
| 401-500     | 4         | 6.9%    |
| 601-700     | 3         | 5.17%   |
| 201-300     | 3         | 5.17%   |
| 701-800     | 2         | 3.45%   |
| 351-400     | 2         | 3.45%   |
| 801-900     | 1         | 1.72%   |
| 1001-1500   | 1         | 1.72%   |
| Unknown     | 1         | 1.72%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 44        | 81.48%  |
| 16/10 | 6         | 11.11%  |
| 32/9  | 2         | 3.7%    |
| 3/2   | 1         | 1.85%   |
| 21/9  | 1         | 1.85%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 18        | 30%     |
| 301-350        | 9         | 15%     |
| 81-90          | 8         | 13.33%  |
| 201-250        | 7         | 11.67%  |
| 351-500        | 4         | 6.67%   |
| 151-200        | 3         | 5%      |
| 61-70          | 2         | 3.33%   |
| 121-130        | 2         | 3.33%   |
| 501-1000       | 2         | 3.33%   |
| 71-80          | 1         | 1.67%   |
| 251-300        | 1         | 1.67%   |
| 141-150        | 1         | 1.67%   |
| 111-120        | 1         | 1.67%   |
| Unknown        | 1         | 1.67%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 121-160 | 23        | 40.35%  |
| 51-100  | 17        | 29.82%  |
| 101-120 | 11        | 19.3%   |
| 161-240 | 5         | 8.77%   |
| Unknown | 1         | 1.75%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 39        | 75%     |
| 2     | 10        | 19.23%  |
| 3     | 3         | 5.77%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 31        | 44.29%  |
| Realtek Semiconductor | 25        | 35.71%  |
| Qualcomm Atheros      | 5         | 7.14%   |
| Broadcom              | 3         | 4.29%   |
| Sierra Wireless       | 1         | 1.43%   |
| Ralink                | 1         | 1.43%   |
| Qualcomm              | 1         | 1.43%   |
| NetGear               | 1         | 1.43%   |
| HMD Global            | 1         | 1.43%   |
| Fibocom               | 1         | 1.43%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 20        | 22.47%  |
| Intel Wi-Fi 6 AX200                                                    | 4         | 4.49%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 3         | 3.37%   |
| Intel Wireless 8265 / 8275                                             | 3         | 3.37%   |
| Intel Ethernet Connection (2) I219-V                                   | 3         | 3.37%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 2         | 2.25%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 2         | 2.25%   |
| Intel Wireless 7260                                                    | 2         | 2.25%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 2         | 2.25%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 2         | 2.25%   |
| Intel Ethernet Connection I217-V                                       | 2         | 2.25%   |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 2.25%   |
| Sierra Wireless Sierra Wireless EM7430 Qualcomm Snapdragon X7 LTE-A    | 1         | 1.12%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 1         | 1.12%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 1         | 1.12%   |
| Realtek RTL8723DE Wireless Network Adapter                             | 1         | 1.12%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 1         | 1.12%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1         | 1.12%   |
| Realtek 802.11ac WLAN Adapter                                          | 1         | 1.12%   |
| Ralink RT5390R PCIe 802.11b/g/n Wireless Network Adapter               | 1         | 1.12%   |
| Qualcomm QCNFA765 Wireless Network Adapter                             | 1         | 1.12%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 1         | 1.12%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 1         | 1.12%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)         | 1         | 1.12%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 1         | 1.12%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 1         | 1.12%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]            | 1         | 1.12%   |
| Intel Wireless 7265                                                    | 1         | 1.12%   |
| Intel Wireless 3160                                                    | 1         | 1.12%   |
| Intel Wi-Fi 6 AX201                                                    | 1         | 1.12%   |
| Intel I211 Gigabit Network Connection                                  | 1         | 1.12%   |
| Intel Ethernet Controller I225-V                                       | 1         | 1.12%   |
| Intel Ethernet Connection I219-LM                                      | 1         | 1.12%   |
| Intel Ethernet Connection I218-V                                       | 1         | 1.12%   |
| Intel Ethernet Connection I217-LM                                      | 1         | 1.12%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1         | 1.12%   |
| Intel Ethernet Connection (6) I219-V                                   | 1         | 1.12%   |
| Intel Ethernet Connection (6) I219-LM                                  | 1         | 1.12%   |
| Intel Ethernet Connection (2) I218-LM                                  | 1         | 1.12%   |
| Intel Ethernet Connection (10) I219-LM                                 | 1         | 1.12%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 24        | 54.55%  |
| Realtek Semiconductor | 8         | 18.18%  |
| Qualcomm Atheros      | 5         | 11.36%  |
| Broadcom              | 2         | 4.55%   |
| Sierra Wireless       | 1         | 2.27%   |
| Ralink                | 1         | 2.27%   |
| Qualcomm              | 1         | 2.27%   |
| NetGear               | 1         | 2.27%   |
| Fibocom               | 1         | 2.27%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                 | 4         | 8.7%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                  | 3         | 6.52%   |
| Intel Wireless 8265 / 8275                                          | 3         | 6.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 2         | 4.35%   |
| Intel Wireless 7260                                                 | 2         | 4.35%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]             | 2         | 4.35%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                     | 2         | 4.35%   |
| Sierra Wireless Sierra Wireless EM7430 Qualcomm Snapdragon X7 LTE-A | 1         | 2.17%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller         | 1         | 2.17%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter            | 1         | 2.17%   |
| Realtek RTL8723DE Wireless Network Adapter                          | 1         | 2.17%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                 | 1         | 2.17%   |
| Realtek 802.11ac WLAN Adapter                                       | 1         | 2.17%   |
| Ralink RT5390R PCIe 802.11b/g/n Wireless Network Adapter            | 1         | 2.17%   |
| Qualcomm QCNFA765 Wireless Network Adapter                          | 1         | 2.17%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter          | 1         | 2.17%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter          | 1         | 2.17%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)      | 1         | 2.17%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)      | 1         | 2.17%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)      | 1         | 2.17%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]         | 1         | 2.17%   |
| Intel Wireless 7265                                                 | 1         | 2.17%   |
| Intel Wireless 3160                                                 | 1         | 2.17%   |
| Intel Wi-Fi 6 AX201                                                 | 1         | 2.17%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                   | 1         | 2.17%   |
| Intel Comet Lake PCH CNVi WiFi                                      | 1         | 2.17%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                        | 1         | 2.17%   |
| Intel Centrino Ultimate-N 6300                                      | 1         | 2.17%   |
| Intel Centrino Advanced-N 6235                                      | 1         | 2.17%   |
| Intel Centrino Advanced-N 6200                                      | 1         | 2.17%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                            | 1         | 2.17%   |
| Intel Cannon Lake PCH CNVi WiFi                                     | 1         | 2.17%   |
| Fibocom L830-EB-00 LTE WWAN Modem                                   | 1         | 2.17%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter        | 1         | 2.17%   |
| Broadcom BCM43228 802.11a/b/g/n                                     | 1         | 2.17%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 23        | 53.49%  |
| Intel                 | 18        | 41.86%  |
| HMD Global            | 1         | 2.33%   |
| Broadcom              | 1         | 2.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 20        | 46.51%  |
| Intel Ethernet Connection (2) I219-V                                   | 3         | 6.98%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 2         | 4.65%   |
| Intel Ethernet Connection I217-V                                       | 2         | 4.65%   |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 4.65%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1         | 2.33%   |
| Intel I211 Gigabit Network Connection                                  | 1         | 2.33%   |
| Intel Ethernet Controller I225-V                                       | 1         | 2.33%   |
| Intel Ethernet Connection I219-LM                                      | 1         | 2.33%   |
| Intel Ethernet Connection I218-V                                       | 1         | 2.33%   |
| Intel Ethernet Connection I217-LM                                      | 1         | 2.33%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1         | 2.33%   |
| Intel Ethernet Connection (6) I219-V                                   | 1         | 2.33%   |
| Intel Ethernet Connection (6) I219-LM                                  | 1         | 2.33%   |
| Intel Ethernet Connection (2) I218-LM                                  | 1         | 2.33%   |
| Intel Ethernet Connection (10) I219-LM                                 | 1         | 2.33%   |
| Intel 82577LM Gigabit Network Connection                               | 1         | 2.33%   |
| HMD Global Nokia6.2                                                    | 1         | 2.33%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 1         | 2.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 43        | 52.44%  |
| WiFi     | 39        | 47.56%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 33        | 68.75%  |
| Ethernet | 15        | 31.25%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 28        | 57.14%  |
| 1     | 18        | 36.73%  |
| 0     | 2         | 4.08%   |
| 3     | 1         | 2.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 39        | 73.58%  |
| Yes  | 14        | 26.42%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 20        | 55.56%  |
| Realtek Semiconductor           | 6         | 16.67%  |
| Lite-On Technology              | 2         | 5.56%   |
| Edimax Technology               | 2         | 5.56%   |
| Cambridge Silicon Radio         | 2         | 5.56%   |
| Qualcomm Atheros Communications | 1         | 2.78%   |
| IMC Networks                    | 1         | 2.78%   |
| Foxconn / Hon Hai               | 1         | 2.78%   |
| Broadcom                        | 1         | 2.78%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                      | 6         | 16.67%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)          | 4         | 11.11%  |
| Intel AX200 Bluetooth                                   | 4         | 11.11%  |
| Realtek  Bluetooth 4.2 Adapter                          | 3         | 8.33%   |
| Intel AX201 Bluetooth                                   | 3         | 8.33%   |
| Realtek Bluetooth Radio                                 | 2         | 5.56%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                | 2         | 5.56%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)     | 2         | 5.56%   |
| Realtek RTL8723B Bluetooth                              | 1         | 2.78%   |
| Qualcomm Atheros AR3011 Bluetooth                       | 1         | 2.78%   |
| Lite-On Bluetooth Device                                | 1         | 2.78%   |
| Lite-On Atheros AR3012 Bluetooth                        | 1         | 2.78%   |
| Intel Centrino Bluetooth Wireless Transceiver           | 1         | 2.78%   |
| IMC Networks Wireless_Device                            | 1         | 2.78%   |
| Foxconn / Hon Hai Bluetooth Device                      | 1         | 2.78%   |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter | 1         | 2.78%   |
| Edimax Bluetooth Adapter                                | 1         | 2.78%   |
| Broadcom HP Portable Bumble Bee                         | 1         | 2.78%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 36        | 52.94%  |
| AMD                     | 17        | 25%     |
| Nvidia                  | 5         | 7.35%   |
| C-Media Electronics     | 2         | 2.94%   |
| Astro Gaming            | 2         | 2.94%   |
| SAVITECH                | 1         | 1.47%   |
| Realtek Semiconductor   | 1         | 1.47%   |
| Lenovo                  | 1         | 1.47%   |
| Hewlett-Packard         | 1         | 1.47%   |
| GN Netcom               | 1         | 1.47%   |
| Cambridge Silicon Radio | 1         | 1.47%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 6         | 6.82%   |
| Intel Sunrise Point-LP HD Audio                                            | 5         | 5.68%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4         | 4.55%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 4.55%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4         | 4.55%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 3.41%   |
| Intel 200 Series PCH HD Audio                                              | 3         | 3.41%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3         | 3.41%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3         | 3.41%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 3         | 3.41%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 3         | 3.41%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 2.27%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 2.27%   |
| Intel Cannon Lake PCH cAVS                                                 | 2         | 2.27%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 2.27%   |
| Astro Gaming Astro A50                                                     | 2         | 2.27%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2         | 2.27%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 2         | 2.27%   |
| SAVITECH MX3                                                               | 1         | 1.14%   |
| Realtek Semiconductor USB Audio                                            | 1         | 1.14%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 1.14%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 1.14%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 1.14%   |
| Lenovo ThinkPad Dock USB Audio                                             | 1         | 1.14%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 1.14%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 1.14%   |
| Intel Jasper Lake HD Audio                                                 | 1         | 1.14%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 1.14%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 1.14%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 1.14%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 1         | 1.14%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 1.14%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 1.14%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 1         | 1.14%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 1.14%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1         | 1.14%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 1.14%   |
| Hewlett-Packard USB Audio                                                  | 1         | 1.14%   |
| GN Netcom Jabra Link 380                                                   | 1         | 1.14%   |
| Cambridge Silicon Radio B25                                                | 1         | 1.14%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 11        | 21.57%  |
| Samsung Electronics | 11        | 21.57%  |
| G.Skill             | 6         | 11.76%  |
| Crucial             | 6         | 11.76%  |
| Micron Technology   | 5         | 9.8%    |
| Kingston            | 5         | 9.8%    |
| Nanya Technology    | 2         | 3.92%   |
| Corsair             | 2         | 3.92%   |
| Unknown             | 1         | 1.96%   |
| Ramsta              | 1         | 1.96%   |
| Elpida              | 1         | 1.96%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 2         | 3.85%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 3.85%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                        | 1         | 1.92%   |
| SK hynix RAM HMT451U6DFR8A-PB 4GB DIMM DDR3 1600MT/s             | 1         | 1.92%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 1.92%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.92%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.92%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 1         | 1.92%   |
| SK hynix RAM HMA81GU6CJR8N-VK 8GB DIMM DDR4 2400MT/s             | 1         | 1.92%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.92%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 1.92%   |
| SK hynix RAM H9CCNNNCLGALAR-NUD 8GB Row Of Chips LPDDR3 1867MT/s | 1         | 1.92%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 1         | 1.92%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 1         | 1.92%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.92%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 1         | 1.92%   |
| Samsung RAM M471A2K43BB1-CRC 16GB SODIMM DDR4 2400MT/s           | 1         | 1.92%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.92%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.92%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.92%   |
| Samsung RAM K4UBE3D4AA-MGCL 8GB Row Of Chips LPDDR4 4267MT/s     | 1         | 1.92%   |
| Ramsta RAM 3200MHz-16G 16GB SODIMM DDR4 3200MT/s                 | 1         | 1.92%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s             | 1         | 1.92%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s             | 1         | 1.92%   |
| Micron RAM Module 16GB SODIMM DDR4 3200MT/s                      | 1         | 1.92%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 1         | 1.92%   |
| Micron RAM 4ATF25664HZ-2G3B1 2GB SODIMM DDR4 2400MT/s            | 1         | 1.92%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 1         | 1.92%   |
| Micron RAM ...d 4096MB SODIMM DDR3 1067MT/s                      | 1         | 1.92%   |
| Kingston RAM Module 8GB DIMM DDR4 3200MT/s                       | 1         | 1.92%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s             | 1         | 1.92%   |
| Kingston RAM KHX1600C9S3L/8G 8192MB SODIMM DDR3 1600MT/s         | 1         | 1.92%   |
| Kingston RAM ACR16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s           | 1         | 1.92%   |
| Kingston RAM 99U5663-007.A00G 16GB SODIMM DDR4 2667MT/s          | 1         | 1.92%   |
| G.Skill RAM F4-3600C16-8GTZR 8192MB DIMM DDR4 3600MT/s           | 1         | 1.92%   |
| G.Skill RAM F4-3200C16-16GTZN 16GB DIMM DDR4 3200MT/s            | 1         | 1.92%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s              | 1         | 1.92%   |
| G.Skill RAM F4-3000C15-8GRBB 8GB DIMM DDR4 3000MT/s              | 1         | 1.92%   |
| G.Skill RAM F4-2400C16-16GRS 16GB SODIMM DDR4 2667MT/s           | 1         | 1.92%   |
| G.Skill RAM F4-2400C15-8GNT 8GB DIMM DDR4 2666MT/s               | 1         | 1.92%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 29        | 67.44%  |
| DDR3   | 10        | 23.26%  |
| SDRAM  | 1         | 2.33%   |
| LPDDR4 | 1         | 2.33%   |
| LPDDR3 | 1         | 2.33%   |
| DDR5   | 1         | 2.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 28        | 65.12%  |
| DIMM         | 12        | 27.91%  |
| Row Of Chips | 3         | 6.98%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 22        | 46.81%  |
| 4096  | 12        | 25.53%  |
| 16384 | 11        | 23.4%   |
| 32768 | 1         | 2.13%   |
| 2048  | 1         | 2.13%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 11        | 23.4%   |
| 2667  | 11        | 23.4%   |
| 1600  | 7         | 14.89%  |
| 2400  | 6         | 12.77%  |
| 3600  | 2         | 4.26%   |
| 3000  | 2         | 4.26%   |
| 4800  | 1         | 2.13%   |
| 4267  | 1         | 2.13%   |
| 4199  | 1         | 2.13%   |
| 2666  | 1         | 2.13%   |
| 1867  | 1         | 2.13%   |
| 1334  | 1         | 2.13%   |
| 1067  | 1         | 2.13%   |
| 1066  | 1         | 2.13%   |

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

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Computers | Percent |
|----------------|-----------|---------|
| Mustek Systems | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| Mustek Systems ScanExpress 600 CU | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 12        | 31.58%  |
| IMC Networks                           | 5         | 13.16%  |
| Realtek Semiconductor                  | 3         | 7.89%   |
| Logitech                               | 3         | 7.89%   |
| Bison Electronics                      | 3         | 7.89%   |
| Microdia                               | 2         | 5.26%   |
| WaveRider Communications               | 1         | 2.63%   |
| Suyin                                  | 1         | 2.63%   |
| Silicon Motion                         | 1         | 2.63%   |
| Quanta                                 | 1         | 2.63%   |
| Primax Electronics                     | 1         | 2.63%   |
| Microsoft                              | 1         | 2.63%   |
| Lite-On Technology                     | 1         | 2.63%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.63%   |
| Acer                                   | 1         | 2.63%   |
| A4Tech                                 | 1         | 2.63%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony HD WebCam                                              | 4         | 10.53%  |
| Realtek Integrated_Webcam_HD                                   | 2         | 5.26%   |
| Microdia Integrated_Webcam_HD                                  | 2         | 5.26%   |
| Logitech Webcam C270                                           | 2         | 5.26%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 2         | 5.26%   |
| Chicony Integrated Camera                                      | 2         | 5.26%   |
| Bison Integrated Camera                                        | 2         | 5.26%   |
| WaveRider USB Live camera                                      | 1         | 2.63%   |
| Suyin 1.3M HD WebCam                                           | 1         | 2.63%   |
| Silicon Motion USB 2.0 PC Cam                                  | 1         | 2.63%   |
| Realtek FULL HD 1080P Webcam                                   | 1         | 2.63%   |
| Quanta HP Webcam                                               | 1         | 2.63%   |
| Primax Villem                                                  | 1         | 2.63%   |
| Microsoft LifeCam Cinema                                       | 1         | 2.63%   |
| Logitech QuickCam Pro 9000                                     | 1         | 2.63%   |
| Lite-On Integrated Camera                                      | 1         | 2.63%   |
| IMC Networks SunplusIT Integrated Camera                       | 1         | 2.63%   |
| IMC Networks Lenovo EasyCamera                                 | 1         | 2.63%   |
| IMC Networks Integrated Camera                                 | 1         | 2.63%   |
| Chicony USB2.0 HD UVC WebCam                                   | 1         | 2.63%   |
| Chicony ThinkPad T490 Webcam                                   | 1         | 2.63%   |
| Chicony HP Webcam                                              | 1         | 2.63%   |
| Chicony HP HD Webcam [Fixed]                                   | 1         | 2.63%   |
| Chicony HP HD Camera                                           | 1         | 2.63%   |
| Chicony HP 5MP Camera                                          | 1         | 2.63%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 2.63%   |
| Bison SunplusIT Integrated Camera                              | 1         | 2.63%   |
| Acer Integrated IR Camera                                      | 1         | 2.63%   |
| A4Tech PK-635G                                                 | 1         | 2.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 4         | 40%     |
| Synaptics                  | 4         | 40%     |
| Shenzhen Goodix Technology | 1         | 10%     |
| LighTuning Technology      | 1         | 10%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader              | 1         | 10%     |
| Validity Sensors VFS451 Fingerprint Reader               | 1         | 10%     |
| Validity Sensors VFS Fingerprint sensor                  | 1         | 10%     |
| Validity Sensors Synaptics WBDI                          | 1         | 10%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 1         | 10%     |
| Synaptics Metallica MOH Touch Fingerprint Reader         | 1         | 10%     |
| Synaptics Metallica MIS Touch Fingerprint Reader         | 1         | 10%     |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 10%     |
| Shenzhen Goodix Fingerprint Reader                       | 1         | 10%     |
| LighTuning EgisTec Touch Fingerprint Sensor              | 1         | 10%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 2         | 66.67%  |
| Broadcom    | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 2         | 66.67%  |
| Broadcom 5880                       | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 35        | 70%     |
| 1     | 12        | 24%     |
| 2     | 3         | 6%      |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 10        | 55.56%  |
| Chipcard                 | 2         | 11.11%  |
| Unassigned class         | 1         | 5.56%   |
| Sound                    | 1         | 5.56%   |
| Net/wireless             | 1         | 5.56%   |
| Graphics card            | 1         | 5.56%   |
| Communication controller | 1         | 5.56%   |
| Card reader              | 1         | 5.56%   |

