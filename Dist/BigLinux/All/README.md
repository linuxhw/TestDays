BigLinux - Tested Hardware & Statistics
---------------------------------------

A project to collect tested hardware configurations for BigLinux.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/BigLinux/Desktop/README.md) and [notebooks](/Dist/BigLinux/Notebook/README.md).

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

Total: 92

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Biostar       | G31M+                       | Desktop     | [24eb0eb2db](https://linux-hardware.org/?probe=24eb0eb2db) | Sep 06, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [73e3b8ef8a](https://linux-hardware.org/?probe=73e3b8ef8a) | Sep 04, 2023 |
| ASUSTek       | PRIME H410M-D               | Desktop     | [332e78dfba](https://linux-hardware.org/?probe=332e78dfba) | Sep 01, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [9cf292357b](https://linux-hardware.org/?probe=9cf292357b) | Aug 30, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [1986877980](https://linux-hardware.org/?probe=1986877980) | Aug 25, 2023 |
| ASUSTek       | X455LA                      | Notebook    | [8b60fb0411](https://linux-hardware.org/?probe=8b60fb0411) | Aug 08, 2023 |
| HP            | EliteBook 8760w             | Notebook    | [30ea6db008](https://linux-hardware.org/?probe=30ea6db008) | Jul 23, 2023 |
| Multilaser    | MLSH1H LINUX                | Notebook    | [e699ffe719](https://linux-hardware.org/?probe=e699ffe719) | Jul 08, 2023 |
| Daten Tecn... | DH110MXV                    | Desktop     | [a2487119a6](https://linux-hardware.org/?probe=a2487119a6) | Jul 08, 2023 |
| Daten Tecn... | DH110MXV                    | Desktop     | [f9a1d993b2](https://linux-hardware.org/?probe=f9a1d993b2) | Jul 07, 2023 |
| ASUSTek       | VX7SX                       | Notebook    | [2ef4295d22](https://linux-hardware.org/?probe=2ef4295d22) | Jul 05, 2023 |
| Positivo      | Q464B                       | Notebook    | [9dad5f0aa1](https://linux-hardware.org/?probe=9dad5f0aa1) | Jul 02, 2023 |
| Multilaser    | MLSH1H LINUX                | Notebook    | [3aa4a11068](https://linux-hardware.org/?probe=3aa4a11068) | Jun 30, 2023 |
| Multilaser    | MLSH1H LINUX                | Notebook    | [3a8a822af9](https://linux-hardware.org/?probe=3a8a822af9) | Jun 30, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [5223ed2efd](https://linux-hardware.org/?probe=5223ed2efd) | Jun 13, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [e25224b362](https://linux-hardware.org/?probe=e25224b362) | Jun 13, 2023 |
| Intel         | X79 (INTEL Xeon E5/Corei... | Desktop     | [613d703a17](https://linux-hardware.org/?probe=613d703a17) | Jun 10, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [91d11f8da1](https://linux-hardware.org/?probe=91d11f8da1) | Jun 04, 2023 |
| Toshiba       | STI 005492G                 | Desktop     | [4f161f4ed0](https://linux-hardware.org/?probe=4f161f4ed0) | May 26, 2023 |
| LG Electro... | V720                        | All in one  | [686e013b62](https://linux-hardware.org/?probe=686e013b62) | May 25, 2023 |
| Samsung       | 300E5M/300E5L               | Notebook    | [ebd65238d8](https://linux-hardware.org/?probe=ebd65238d8) | May 22, 2023 |
| Dell          | Inspiron 7460               | Notebook    | [696014fc68](https://linux-hardware.org/?probe=696014fc68) | May 01, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [620668d216](https://linux-hardware.org/?probe=620668d216) | Apr 25, 2023 |
| Dell          | G15 5520                    | Notebook    | [d2cc8527a5](https://linux-hardware.org/?probe=d2cc8527a5) | Apr 23, 2023 |
| HP            | 1495                        | Desktop     | [96283c0a09](https://linux-hardware.org/?probe=96283c0a09) | Apr 01, 2023 |
| HP            | 1495                        | Desktop     | [f25125625a](https://linux-hardware.org/?probe=f25125625a) | Apr 01, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [e3a13c69ef](https://linux-hardware.org/?probe=e3a13c69ef) | Apr 01, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [ebe6cc115e](https://linux-hardware.org/?probe=ebe6cc115e) | Mar 22, 2023 |
| Clevo         | W340EU                      | Notebook    | [fb9df7f581](https://linux-hardware.org/?probe=fb9df7f581) | Mar 18, 2023 |
| Clevo         | W340EU                      | Notebook    | [176b7d75bf](https://linux-hardware.org/?probe=176b7d75bf) | Mar 18, 2023 |
| Avell High... | STORM TWO                   | Notebook    | [e6b20084b5](https://linux-hardware.org/?probe=e6b20084b5) | Mar 16, 2023 |
| HP            | 3397                        | Desktop     | [0b74e11cdd](https://linux-hardware.org/?probe=0b74e11cdd) | Mar 12, 2023 |
| HP            | 1495                        | Desktop     | [058beaa7d1](https://linux-hardware.org/?probe=058beaa7d1) | Mar 12, 2023 |
| HP            | 1495                        | Desktop     | [517a7a6401](https://linux-hardware.org/?probe=517a7a6401) | Mar 12, 2023 |
| Lenovo        | NOK                         | Desktop     | [2e90ce2e87](https://linux-hardware.org/?probe=2e90ce2e87) | Mar 10, 2023 |
| Gigabyte      | B560M AORUS ELITE           | Desktop     | [066cc238c4](https://linux-hardware.org/?probe=066cc238c4) | Feb 26, 2023 |
| Intel         | H61                         | Desktop     | [5e26cd7b85](https://linux-hardware.org/?probe=5e26cd7b85) | Feb 23, 2023 |
| Gigabyte      | B560M AORUS ELITE           | Desktop     | [789bcfe82f](https://linux-hardware.org/?probe=789bcfe82f) | Feb 22, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [7c6973f1fa](https://linux-hardware.org/?probe=7c6973f1fa) | Feb 21, 2023 |
| Gigabyte      | X399 DESIGNARE EX-CF        | Desktop     | [4bcfe32668](https://linux-hardware.org/?probe=4bcfe32668) | Feb 12, 2023 |
| Intel         | H61                         | Desktop     | [81e14fd083](https://linux-hardware.org/?probe=81e14fd083) | Feb 08, 2023 |
| BESSTAR Te... | HM90                        | Desktop     | [3f958de9bb](https://linux-hardware.org/?probe=3f958de9bb) | Feb 01, 2023 |
| Acer          | Aspire A315-53              | Notebook    | [fd498f882b](https://linux-hardware.org/?probe=fd498f882b) | Jan 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [009adbd75c](https://linux-hardware.org/?probe=009adbd75c) | Jan 18, 2023 |
| Intel         | H55                         | Desktop     | [4fdea85eec](https://linux-hardware.org/?probe=4fdea85eec) | Jan 14, 2023 |
| Intel         | H55                         | Desktop     | [d875a18037](https://linux-hardware.org/?probe=d875a18037) | Jan 14, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [b1a7adefab](https://linux-hardware.org/?probe=b1a7adefab) | Jan 09, 2023 |
| Lenovo        | ThinkPad A485 20MVS0LG00    | Notebook    | [12b3654541](https://linux-hardware.org/?probe=12b3654541) | Dec 15, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [89e97c7099](https://linux-hardware.org/?probe=89e97c7099) | Nov 29, 2022 |
| Toshiba       | Satellite S55-A             | Notebook    | [c188e01f20](https://linux-hardware.org/?probe=c188e01f20) | Nov 20, 2022 |
| Toshiba       | Satellite S55-A             | Notebook    | [d5e9f0d98a](https://linux-hardware.org/?probe=d5e9f0d98a) | Nov 19, 2022 |
| Intel         | NUC11DBBi7 M17027-403       | Mini pc     | [d0d37dd251](https://linux-hardware.org/?probe=d0d37dd251) | Nov 17, 2022 |
| Lenovo        | IdeaPad 300-15ISK 80RS      | Notebook    | [16dc745785](https://linux-hardware.org/?probe=16dc745785) | Nov 16, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [9b43ddbe11](https://linux-hardware.org/?probe=9b43ddbe11) | Nov 09, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [8e89ed396e](https://linux-hardware.org/?probe=8e89ed396e) | Nov 05, 2022 |
| ASUSTek       | TUF Gaming B450M-PRO S      | Desktop     | [8cb2cd8c19](https://linux-hardware.org/?probe=8cb2cd8c19) | Oct 26, 2022 |
| eMachines     | EMCP61M                     | Desktop     | [711594c5b4](https://linux-hardware.org/?probe=711594c5b4) | Oct 09, 2022 |
| ASUSTek       | TUF Gaming B450M-PRO S      | Desktop     | [75502d8d96](https://linux-hardware.org/?probe=75502d8d96) | Oct 09, 2022 |
| Dell          | System XPS L502X            | Notebook    | [cd40a3f168](https://linux-hardware.org/?probe=cd40a3f168) | Oct 08, 2022 |
| ASUSTek       | TUF Gaming B450M-PRO S      | Desktop     | [94c783f944](https://linux-hardware.org/?probe=94c783f944) | Sep 11, 2022 |
| ASUSTek       | X45U                        | Notebook    | [3efe835653](https://linux-hardware.org/?probe=3efe835653) | Aug 22, 2022 |
| Positivo      | C14RV01                     | Notebook    | [818c67da93](https://linux-hardware.org/?probe=818c67da93) | Aug 21, 2022 |
| Intel         | DH61WW AAG23116-203         | Desktop     | [43a16c5e88](https://linux-hardware.org/?probe=43a16c5e88) | Aug 21, 2022 |
| Sony          | VGN-NR230AE                 | Notebook    | [ba78970975](https://linux-hardware.org/?probe=ba78970975) | Aug 15, 2022 |
| ASUSTek       | Z87M-PLUS                   | Desktop     | [0efc94e34d](https://linux-hardware.org/?probe=0efc94e34d) | Jul 24, 2022 |
| Intel         | DH61WW AAG23116-203         | Desktop     | [cfd6e87e09](https://linux-hardware.org/?probe=cfd6e87e09) | Jul 23, 2022 |
| Lenovo        | IdeaPad S400 VIUS3          | Notebook    | [2f8b49e4f8](https://linux-hardware.org/?probe=2f8b49e4f8) | Jul 23, 2022 |
| ASUSTek       | Z87M-PLUS                   | Desktop     | [c30806c628](https://linux-hardware.org/?probe=c30806c628) | Jul 23, 2022 |
| ASUSTek       | Z87M-PLUS                   | Desktop     | [b805fa0cd8](https://linux-hardware.org/?probe=b805fa0cd8) | Jul 23, 2022 |
| Positivo      | C14RV01                     | Notebook    | [fc6fa07b38](https://linux-hardware.org/?probe=fc6fa07b38) | Sep 10, 2021 |
| Acer          | Predator G9-793             | Notebook    | [6004b8b462](https://linux-hardware.org/?probe=6004b8b462) | Jun 24, 2021 |
| Dell          | System Inspiron N7110       | Notebook    | [e58da0d3ca](https://linux-hardware.org/?probe=e58da0d3ca) | Jun 23, 2021 |
| Acer          | Predator G9-793             | Notebook    | [ae4824f52e](https://linux-hardware.org/?probe=ae4824f52e) | Jun 20, 2021 |
| Dell          | System Inspiron N7110       | Notebook    | [41512cfc6a](https://linux-hardware.org/?probe=41512cfc6a) | Jun 20, 2021 |
| ECS           | H67H2-M2                    | Desktop     | [d82e4c4eb4](https://linux-hardware.org/?probe=d82e4c4eb4) | Apr 10, 2021 |
| Positivo      | C14RV01                     | Notebook    | [36efae3128](https://linux-hardware.org/?probe=36efae3128) | Feb 03, 2021 |
| Acer          | A315-41                     | Notebook    | [021dc9110e](https://linux-hardware.org/?probe=021dc9110e) | Nov 11, 2020 |
| Lenovo        | ThinkPad T410 25379N2       | Notebook    | [ed777f25b7](https://linux-hardware.org/?probe=ed777f25b7) | Nov 09, 2020 |
| Dell          | Inspiron 3480               | Notebook    | [1f0823c074](https://linux-hardware.org/?probe=1f0823c074) | Oct 13, 2020 |
| ASUSTek       | H110M-C/BR                  | Desktop     | [0c4cd978f2](https://linux-hardware.org/?probe=0c4cd978f2) | Jul 24, 2020 |
| ASUSTek       | TUF B360M-PLUS GAMING/BR    | Desktop     | [3cef63e59d](https://linux-hardware.org/?probe=3cef63e59d) | Jul 17, 2020 |
| Acer          | Aspire A515-51G             | Notebook    | [8b89f99351](https://linux-hardware.org/?probe=8b89f99351) | Jul 17, 2020 |
| Acer          | Aspire A515-51G             | Notebook    | [07fb6950a2](https://linux-hardware.org/?probe=07fb6950a2) | Jul 11, 2020 |
| PCWare        | IPX1800E2                   | Desktop     | [0990462881](https://linux-hardware.org/?probe=0990462881) | Jun 21, 2020 |
| PCWare        | IPX1800E2                   | Desktop     | [93916c17f2](https://linux-hardware.org/?probe=93916c17f2) | Jun 21, 2020 |
| ASRock        | 775Dual-VSTA                | Desktop     | [0e5ac5a0bf](https://linux-hardware.org/?probe=0e5ac5a0bf) | Jun 12, 2020 |
| ASRock        | 775Dual-VSTA                | Desktop     | [a4f3841c00](https://linux-hardware.org/?probe=a4f3841c00) | May 29, 2020 |
| ASRock        | 775Dual-VSTA                | Desktop     | [3fe70d9fdd](https://linux-hardware.org/?probe=3fe70d9fdd) | May 06, 2020 |
| ASRock        | 775Dual-VSTA                | Desktop     | [8fa9935547](https://linux-hardware.org/?probe=8fa9935547) | Apr 27, 2020 |
| Lenovo        | IdeaPad Z470                | Notebook    | [3a8f141df4](https://linux-hardware.org/?probe=3a8f141df4) | Mar 28, 2020 |
| Alienware     | 17                          | Notebook    | [14abe97f88](https://linux-hardware.org/?probe=14abe97f88) | Oct 23, 2019 |
| Lenovo        | Yoga 520-14IKB 80YM         | Convertible | [419565138f](https://linux-hardware.org/?probe=419565138f) | Aug 30, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                      | Computers | Percent |
|---------------------------|-----------|---------|
| BigLinux 20.04            | 11        | 16.18%  |
| BigLinux 23.0.0           | 7         | 10.29%  |
| BigLinux 22.0.0           | 6         | 8.82%   |
| BigLinux 19.04            | 5         | 7.35%   |
| BigLinux 22.1.0           | 4         | 5.88%   |
| BigLinux 22.0.4           | 4         | 5.88%   |
| BigLinux 21.3.7           | 3         | 4.41%   |
| BigLinux 21.3.5           | 3         | 4.41%   |
| BigLinux 23.02.20         | 2         | 2.94%   |
| BigLinux 2023-06-30_08-01 | 2         | 2.94%   |
| BigLinux 23.02.24         | 1         | 1.47%   |
| BigLinux 23.02.07         | 1         | 1.47%   |
| BigLinux 23.01.30         | 1         | 1.47%   |
| BigLinux 23.01.06         | 1         | 1.47%   |
| BigLinux 22.12.24         | 1         | 1.47%   |
| BigLinux 22.11.19         | 1         | 1.47%   |
| BigLinux 22.11.14         | 1         | 1.47%   |
| BigLinux 22.10.28         | 1         | 1.47%   |
| BigLinux 22.10.06         | 1         | 1.47%   |
| BigLinux 22.1.1           | 1         | 1.47%   |
| BigLinux 22.09.09         | 1         | 1.47%   |
| BigLinux 22.0.5           | 1         | 1.47%   |
| BigLinux 22.0.2           | 1         | 1.47%   |
| BigLinux 21.3.6           | 1         | 1.47%   |
| BigLinux 21.1.2           | 1         | 1.47%   |
| BigLinux 2023-08-04_06-17 | 1         | 1.47%   |
| BigLinux 2023-06-23_06-21 | 1         | 1.47%   |
| BigLinux 2023-06-07_06-02 | 1         | 1.47%   |
| BigLinux 2023-06-03_00-55 | 1         | 1.47%   |
| BigLinux 2023-04-11_15-10 | 1         | 1.47%   |
| BigLinux 2023-03-17_19-23 | 1         | 1.47%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| BigLinux | 64        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Computers | Percent |
|-----------------------|-----------|---------|
| 6.1.31-2-MANJARO      | 4         | 5.71%   |
| 6.1.12-1-MANJARO      | 4         | 5.71%   |
| 6.1.23-1-MANJARO      | 3         | 4.29%   |
| 5.15.94-1-MANJARO     | 3         | 4.29%   |
| 5.15.85-1-MANJARO     | 3         | 4.29%   |
| 5.15.60-1-MANJARO     | 3         | 4.29%   |
| 6.4.12-1-MANJARO      | 2         | 2.86%   |
| 6.2.12-1-MANJARO      | 2         | 2.86%   |
| 6.0.8-1-MANJARO       | 2         | 2.86%   |
| 5.8.0-43-generic      | 2         | 2.86%   |
| 5.4.0-37-generic      | 2         | 2.86%   |
| 5.2.8-xanmod8         | 2         | 2.86%   |
| 5.15.78-1-MANJARO     | 2         | 2.86%   |
| 5.15.71-1-MANJARO     | 2         | 2.86%   |
| 5.15.102-1-MANJARO    | 2         | 2.86%   |
| 6.4.6-1-MANJARO       | 1         | 1.43%   |
| 6.3.5-2-MANJARO       | 1         | 1.43%   |
| 6.3.5-1-MANJARO       | 1         | 1.43%   |
| 6.3.13-1-MANJARO      | 1         | 1.43%   |
| 6.1.9-x64v1-xanmod1-1 | 1         | 1.43%   |
| 6.1.9-1-MANJARO       | 1         | 1.43%   |
| 6.1.49-1-MANJARO      | 1         | 1.43%   |
| 6.1.26-1-MANJARO      | 1         | 1.43%   |
| 6.1.1-1-MANJARO       | 1         | 1.43%   |
| 5.9.3-xanmod1         | 1         | 1.43%   |
| 5.8.0-48-generic      | 1         | 1.43%   |
| 5.8.0-28-generic      | 1         | 1.43%   |
| 5.7.9-xanmod1         | 1         | 1.43%   |
| 5.6.6-xanmod1         | 1         | 1.43%   |
| 5.6.10-xanmod1        | 1         | 1.43%   |
| 5.4.0-48-generic      | 1         | 1.43%   |
| 5.4.0-33-generic      | 1         | 1.43%   |
| 5.4.0-31-generic      | 1         | 1.43%   |
| 5.3.6-xanmod5         | 1         | 1.43%   |
| 5.2.10-xanmod9        | 1         | 1.43%   |
| 5.19.13-1-MANJARO     | 1         | 1.43%   |
| 5.17.15-1-MANJARO     | 1         | 1.43%   |
| 5.16.11-1-BIGLINUX    | 1         | 1.43%   |
| 5.15.89-1-MANJARO     | 1         | 1.43%   |
| 5.15.76-1-MANJARO     | 1         | 1.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 6.1.31   | 4         | 5.8%    |
| 6.1.12   | 4         | 5.8%    |
| 5.8.0    | 4         | 5.8%    |
| 5.4.0    | 4         | 5.8%    |
| 6.1.23   | 3         | 4.35%   |
| 5.15.94  | 3         | 4.35%   |
| 5.15.85  | 3         | 4.35%   |
| 5.15.60  | 3         | 4.35%   |
| 6.4.12   | 2         | 2.9%    |
| 6.3.5    | 2         | 2.9%    |
| 6.2.12   | 2         | 2.9%    |
| 6.1.9    | 2         | 2.9%    |
| 6.0.8    | 2         | 2.9%    |
| 5.2.8    | 2         | 2.9%    |
| 5.15.78  | 2         | 2.9%    |
| 5.15.71  | 2         | 2.9%    |
| 5.15.102 | 2         | 2.9%    |
| 6.4.6    | 1         | 1.45%   |
| 6.3.13   | 1         | 1.45%   |
| 6.1.49   | 1         | 1.45%   |
| 6.1.26   | 1         | 1.45%   |
| 6.1.1    | 1         | 1.45%   |
| 5.9.3    | 1         | 1.45%   |
| 5.7.9    | 1         | 1.45%   |
| 5.6.6    | 1         | 1.45%   |
| 5.6.10   | 1         | 1.45%   |
| 5.3.6    | 1         | 1.45%   |
| 5.2.10   | 1         | 1.45%   |
| 5.19.13  | 1         | 1.45%   |
| 5.17.15  | 1         | 1.45%   |
| 5.16.11  | 1         | 1.45%   |
| 5.15.89  | 1         | 1.45%   |
| 5.15.76  | 1         | 1.45%   |
| 5.15.55  | 1         | 1.45%   |
| 5.15.114 | 1         | 1.45%   |
| 5.10.61  | 1         | 1.45%   |
| 5.10.136 | 1         | 1.45%   |
| 5.10.131 | 1         | 1.45%   |
| 5.10.129 | 1         | 1.45%   |
| 5.10.12  | 1         | 1.45%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 17        | 26.56%  |
| 6.1     | 16        | 25%     |
| 5.8     | 4         | 6.25%   |
| 5.4     | 4         | 6.25%   |
| 6.4     | 3         | 4.69%   |
| 6.3     | 3         | 4.69%   |
| 5.2     | 3         | 4.69%   |
| 5.10    | 3         | 4.69%   |
| 6.2     | 2         | 3.13%   |
| 6.0     | 2         | 3.13%   |
| 5.9     | 1         | 1.56%   |
| 5.7     | 1         | 1.56%   |
| 5.6     | 1         | 1.56%   |
| 5.3     | 1         | 1.56%   |
| 5.19    | 1         | 1.56%   |
| 5.17    | 1         | 1.56%   |
| 5.16    | 1         | 1.56%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 64        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| KDE5     | 55        | 85.94%  |
| KDE      | 6         | 9.38%   |
| Unknown  | 2         | 3.13%   |
| Cinnamon | 1         | 1.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 62        | 96.88%  |
| Wayland | 1         | 1.56%   |
| Unknown | 1         | 1.56%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 54        | 84.38%  |
| Unknown | 7         | 10.94%  |
| LightDM | 2         | 3.13%   |
| LXDM    | 1         | 1.56%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| pt_BR   | 39        | 60.94%  |
| en_US   | 9         | 14.06%  |
| es_MX   | 3         | 4.69%   |
| pt_PT   | 2         | 3.13%   |
| en_GB   | 2         | 3.13%   |
| Unknown | 2         | 3.13%   |
| fr_BE   | 1         | 1.56%   |
| fi_FI   | 1         | 1.56%   |
| es_ES   | 1         | 1.56%   |
| es_CR   | 1         | 1.56%   |
| es_AR   | 1         | 1.56%   |
| el_GR   | 1         | 1.56%   |
| de_AT   | 1         | 1.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 40        | 61.54%  |
| BIOS | 25        | 38.46%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 56        | 87.5%   |
| Ext4    | 5         | 7.81%   |
| Overlay | 2         | 3.13%   |
| Unknown | 1         | 1.56%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 38        | 57.58%  |
| MBR     | 19        | 28.79%  |
| Unknown | 9         | 13.64%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 61        | 93.85%  |
| Yes       | 4         | 6.15%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 34        | 53.13%  |
| Yes       | 30        | 46.88%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| ASUSTek Computer       | 10        | 15.63%  |
| Lenovo                 | 9         | 14.06%  |
| Intel                  | 6         | 9.38%   |
| Dell                   | 5         | 7.81%   |
| Acer                   | 5         | 7.81%   |
| Hewlett-Packard        | 4         | 6.25%   |
| Gigabyte Technology    | 4         | 6.25%   |
| Positivo               | 2         | 3.13%   |
| MSI                    | 2         | 3.13%   |
| ASRock                 | 2         | 3.13%   |
| Toshiba                | 1         | 1.56%   |
| Sony                   | 1         | 1.56%   |
| Semp Toshiba           | 1         | 1.56%   |
| Samsung Electronics    | 1         | 1.56%   |
| PCWare                 | 1         | 1.56%   |
| Multilaser             | 1         | 1.56%   |
| eMachines              | 1         | 1.56%   |
| ECS                    | 1         | 1.56%   |
| Daten Tecnologia       | 1         | 1.56%   |
| Clevo                  | 1         | 1.56%   |
| Biostar                | 1         | 1.56%   |
| BESSTAR Tech           | 1         | 1.56%   |
| Avell High Performance | 1         | 1.56%   |
| Apple                  | 1         | 1.56%   |
| Alienware              | 1         | 1.56%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                         | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Intel H61                                                    | 2         | 3.13%   |
| ASRock 775Dual-VSTA                                          | 2         | 3.13%   |
| Toshiba Satellite S55-A                                      | 1         | 1.56%   |
| Sony VGN-NR230AE                                             | 1         | 1.56%   |
| Semp Toshiba STI                                             | 1         | 1.56%   |
| Samsung 300E5M/300E5L                                        | 1         | 1.56%   |
| Positivo Q464B                                               | 1         | 1.56%   |
| Positivo C14RV01                                             | 1         | 1.56%   |
| PCWare IPX1800E2                                             | 1         | 1.56%   |
| Multilaser MLSH1H LINUX                                      | 1         | 1.56%   |
| MSI MS-7C95                                                  | 1         | 1.56%   |
| MSI MS-7C91                                                  | 1         | 1.56%   |
| Lenovo Yoga Slim 7 14ARE05 82A2                              | 1         | 1.56%   |
| Lenovo Yoga 520-14IKB 80YM                                   | 1         | 1.56%   |
| Lenovo ThinkPad T410 25379N2                                 | 1         | 1.56%   |
| Lenovo ThinkCentre M93p 10AB0010US                           | 1         | 1.56%   |
| Lenovo IdeaPad Z470                                          | 1         | 1.56%   |
| Lenovo IdeaPad S400 VIUS3                                    | 1         | 1.56%   |
| Lenovo IdeaPad 5 Pro 14ACN6 82L7                             | 1         | 1.56%   |
| Lenovo IdeaPad 300-15ISK 80RS                                | 1         | 1.56%   |
| Lenovo 63 90AT0002BR                                         | 1         | 1.56%   |
| Intel X79 (INTEL Xeon E5/Corei7 DMI2 - C600/C200 Cipset V307 | 1         | 1.56%   |
| Intel NUC11BTMi7                                             | 1         | 1.56%   |
| Intel H55                                                    | 1         | 1.56%   |
| Intel DH61WW AAG23116-203                                    | 1         | 1.56%   |
| HP EliteBook 8760w                                           | 1         | 1.56%   |
| HP Compaq Elite 8300 SFF                                     | 1         | 1.56%   |
| HP Compaq 8200 Elite SFF PC                                  | 1         | 1.56%   |
| HP 255 G7 Notebook PC                                        | 1         | 1.56%   |
| Gigabyte Z87-HD3                                             | 1         | 1.56%   |
| Gigabyte X399 DESIGNARE EX                                   | 1         | 1.56%   |
| Gigabyte B560M AORUS ELITE                                   | 1         | 1.56%   |
| Gigabyte B550M AORUS ELITE                                   | 1         | 1.56%   |
| eMachines EL1321                                             | 1         | 1.56%   |
| ECS H67H2-M2                                                 | 1         | 1.56%   |
| Dell System XPS L502X                                        | 1         | 1.56%   |
| Dell System Inspiron N7110                                   | 1         | 1.56%   |
| Dell Inspiron 7460                                           | 1         | 1.56%   |
| Dell Inspiron 3480                                           | 1         | 1.56%   |
| Dell G15 5520                                                | 1         | 1.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Lenovo IdeaPad               | 4         | 6.25%   |
| Lenovo Yoga                  | 2         | 3.13%   |
| Intel H61                    | 2         | 3.13%   |
| HP Compaq                    | 2         | 3.13%   |
| Dell System                  | 2         | 3.13%   |
| Dell Inspiron                | 2         | 3.13%   |
| ASUS TUF                     | 2         | 3.13%   |
| ASRock 775Dual-VSTA          | 2         | 3.13%   |
| Acer Aspire                  | 2         | 3.13%   |
| Toshiba Satellite            | 1         | 1.56%   |
| Sony VGN-NR230AE             | 1         | 1.56%   |
| Semp Toshiba STI             | 1         | 1.56%   |
| Samsung 300E5M               | 1         | 1.56%   |
| Positivo Q464B               | 1         | 1.56%   |
| Positivo C14RV01             | 1         | 1.56%   |
| PCWare IPX1800E2             | 1         | 1.56%   |
| Multilaser MLSH1H            | 1         | 1.56%   |
| MSI MS-7C95                  | 1         | 1.56%   |
| MSI MS-7C91                  | 1         | 1.56%   |
| Lenovo ThinkPad              | 1         | 1.56%   |
| Lenovo ThinkCentre           | 1         | 1.56%   |
| Lenovo 63                    | 1         | 1.56%   |
| Intel X79                    | 1         | 1.56%   |
| Intel NUC11BTMi7             | 1         | 1.56%   |
| Intel H55                    | 1         | 1.56%   |
| Intel DH61WW                 | 1         | 1.56%   |
| HP EliteBook                 | 1         | 1.56%   |
| HP 255                       | 1         | 1.56%   |
| Gigabyte Z87-HD3             | 1         | 1.56%   |
| Gigabyte X399                | 1         | 1.56%   |
| Gigabyte B560M               | 1         | 1.56%   |
| Gigabyte B550M               | 1         | 1.56%   |
| eMachines EL1321             | 1         | 1.56%   |
| ECS H67H2-M2                 | 1         | 1.56%   |
| Dell G15                     | 1         | 1.56%   |
| Daten Tecnologia DH110MXV    | 1         | 1.56%   |
| Clevo W340EU                 | 1         | 1.56%   |
| Biostar G31M+                | 1         | 1.56%   |
| BESSTAR Tech HM90            | 1         | 1.56%   |
| Avell High Performance STORM | 1         | 1.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2017 | 8         | 12.5%   |
| 2021 | 7         | 10.94%  |
| 2012 | 7         | 10.94%  |
| 2020 | 6         | 9.38%   |
| 2011 | 6         | 9.38%   |
| 2013 | 5         | 7.81%   |
| 2018 | 4         | 6.25%   |
| 2014 | 4         | 6.25%   |
| 2022 | 3         | 4.69%   |
| 2019 | 3         | 4.69%   |
| 2016 | 3         | 4.69%   |
| 2009 | 3         | 4.69%   |
| 2006 | 2         | 3.13%   |
| 2015 | 1         | 1.56%   |
| 2010 | 1         | 1.56%   |
| 2007 | 1         | 1.56%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 32        | 50%     |
| Desktop     | 30        | 46.88%  |
| Convertible | 1         | 1.56%   |
| Mini pc     | 1         | 1.56%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 63        | 98.44%  |
| Enabled  | 1         | 1.56%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 64        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 14        | 21.54%  |
| 4.01-8.0    | 13        | 20%     |
| 32.01-64.0  | 11        | 16.92%  |
| 16.01-24.0  | 11        | 16.92%  |
| 8.01-16.0   | 9         | 13.85%  |
| 2.01-3.0    | 4         | 6.15%   |
| 1.01-2.0    | 2         | 3.08%   |
| 64.01-256.0 | 1         | 1.54%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 25        | 36.76%  |
| 1.01-2.0  | 23        | 33.82%  |
| 4.01-8.0  | 8         | 11.76%  |
| 3.01-4.0  | 5         | 7.35%   |
| 0.51-1.0  | 4         | 5.88%   |
| 8.01-16.0 | 2         | 2.94%   |
| 0.01-0.5  | 1         | 1.47%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 33        | 50.77%  |
| 2      | 13        | 20%     |
| 3      | 12        | 18.46%  |
| 4      | 4         | 6.15%   |
| 6      | 2         | 3.08%   |
| 0      | 1         | 1.54%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 40        | 62.5%   |
| Yes       | 24        | 37.5%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 60        | 93.75%  |
| No        | 4         | 6.25%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 47        | 73.44%  |
| No        | 17        | 26.56%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 35        | 54.69%  |
| No        | 29        | 45.31%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Computers | Percent |
|------------|-----------|---------|
| Brazil     | 43        | 67.19%  |
| USA        | 3         | 4.69%   |
| UK         | 3         | 4.69%   |
| Mexico     | 3         | 4.69%   |
| Greece     | 3         | 4.69%   |
| Portugal   | 2         | 3.13%   |
| Spain      | 1         | 1.56%   |
| Japan      | 1         | 1.56%   |
| Finland    | 1         | 1.56%   |
| Costa Rica | 1         | 1.56%   |
| Belgium    | 1         | 1.56%   |
| Austria    | 1         | 1.56%   |
| Argentina  | 1         | 1.56%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Sao Paulo              | 5         | 7.69%   |
| Brasília              | 4         | 6.15%   |
| Rio de Janeiro         | 3         | 4.62%   |
| Belo Horizonte         | 3         | 4.62%   |
| Thessaloniki           | 2         | 3.08%   |
| Sao Domingos do Capim  | 2         | 3.08%   |
| Curitiba               | 2         | 3.08%   |
| Castanhal              | 2         | 3.08%   |
| Wiener Neustadt        | 1         | 1.54%   |
| Vila Nova de Famalicao | 1         | 1.54%   |
| Tokyo                  | 1         | 1.54%   |
| Tlajomulco de Zuniga   | 1         | 1.54%   |
| The Villages           | 1         | 1.54%   |
| Sao Jose do Rio Preto  | 1         | 1.54%   |
| Sao Joaquim da Barra   | 1         | 1.54%   |
| Santo André           | 1         | 1.54%   |
| Santa Cruz de Tenerife | 1         | 1.54%   |
| San José              | 1         | 1.54%   |
| Salvador               | 1         | 1.54%   |
| Ribeirao Grande        | 1         | 1.54%   |
| Osasco                 | 1         | 1.54%   |
| Mirassol               | 1         | 1.54%   |
| Metepec                | 1         | 1.54%   |
| Maringá               | 1         | 1.54%   |
| Marataizes             | 1         | 1.54%   |
| Maidstone              | 1         | 1.54%   |
| Macapa                 | 1         | 1.54%   |
| Londrina               | 1         | 1.54%   |
| Juazeiro do Norte      | 1         | 1.54%   |
| Joensuu                | 1         | 1.54%   |
| Ivinhema               | 1         | 1.54%   |
| Hoffman                | 1         | 1.54%   |
| Guimaraes              | 1         | 1.54%   |
| Gavere                 | 1         | 1.54%   |
| Fresno                 | 1         | 1.54%   |
| Franca                 | 1         | 1.54%   |
| Fortaleza              | 1         | 1.54%   |
| Fernandopolis          | 1         | 1.54%   |
| El Palomar             | 1         | 1.54%   |
| Dumbarton              | 1         | 1.54%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 21        | 27     | 19.81%  |
| Seagate                     | 17        | 27     | 16.04%  |
| Samsung Electronics         | 8         | 9      | 7.55%   |
| Hitachi                     | 6         | 6      | 5.66%   |
| Sandisk                     | 5         | 5      | 4.72%   |
| China                       | 5         | 7      | 4.72%   |
| KingSpec                    | 4         | 4      | 3.77%   |
| Crucial                     | 4         | 4      | 3.77%   |
| ADATA Technology            | 4         | 4      | 3.77%   |
| Toshiba                     | 3         | 4      | 2.83%   |
| PNY                         | 3         | 4      | 2.83%   |
| Kingston                    | 3         | 6      | 2.83%   |
| XrayDisk                    | 2         | 2      | 1.89%   |
| Unknown                     | 2         | 2      | 1.89%   |
| Netac                       | 2         | 3      | 1.89%   |
| Micron/Crucial Technology   | 2         | 2      | 1.89%   |
| LITEON                      | 2         | 3      | 1.89%   |
| JMicron Technology          | 2         | 2      | 1.89%   |
| HGST                        | 2         | 2      | 1.89%   |
| A-DATA Technology           | 2         | 2      | 1.89%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 0.94%   |
| Kingston Technology Company | 1         | 1      | 0.94%   |
| Intel                       | 1         | 1      | 0.94%   |
| EYOTA                       | 1         | 1      | 0.94%   |
| BHT                         | 1         | 1      | 0.94%   |
| Apacer                      | 1         | 1      | 0.94%   |
| Unknown                     | 1         | 1      | 0.94%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 4         | 3.51%   |
| WDC WD10SPZX-21Z10T0 1TB                            | 3         | 2.63%   |
| Unknown MMC Card  64GB                              | 2         | 1.75%   |
| Seagate ST500DM002-1BD142 500GB                     | 2         | 1.75%   |
| Seagate ST4000DM004-2CV104 4TB                      | 2         | 1.75%   |
| Seagate ST1000DM010-2EP102 1TB                      | 2         | 1.75%   |
| Micron/Crucial CT500P5SSD8 500GB                    | 2         | 1.75%   |
| Kingston SV300S37A240G 240GB SSD                    | 2         | 1.75%   |
| JMicron Tech 250GB                                  | 2         | 1.75%   |
| XrayDisk 512GB SSD                                  | 1         | 0.88%   |
| XrayDisk 120GB                                      | 1         | 0.88%   |
| WDC WDS480G2G0A-00JH30 480GB SSD                    | 1         | 0.88%   |
| WDC WDS100T2G0A-00JH30 1TB SSD                      | 1         | 0.88%   |
| WDC WD800BD-22MRA1 80GB                             | 1         | 0.88%   |
| WDC WD800AAJS-75M0A0 80GB                           | 1         | 0.88%   |
| WDC WD7500BPKX-75HPJT0 752GB                        | 1         | 0.88%   |
| WDC WD5000LPVX-75V0TT0 500GB                        | 1         | 0.88%   |
| WDC WD5000LPVT-08G33T1 500GB                        | 1         | 0.88%   |
| WDC WD5000LPCX-24VHAT0 500GB                        | 1         | 0.88%   |
| WDC WD5000AAKX-08U6AA0 500GB                        | 1         | 0.88%   |
| WDC WD40EZRX-00SPEB0 4TB                            | 1         | 0.88%   |
| WDC WD3200BPVT-22JJ5T0 320GB                        | 1         | 0.88%   |
| WDC WD3200BPVT-00JJ5T0 320GB                        | 1         | 0.88%   |
| WDC WD3200AAKS-75L9A0 320GB                         | 1         | 0.88%   |
| WDC WD3200AAJS-56M0A0 320GB                         | 1         | 0.88%   |
| WDC WD30EFAX-68JH4N0 3TB                            | 1         | 0.88%   |
| WDC WD1600AAJS-08L7A0 160GB                         | 1         | 0.88%   |
| WDC WD10SPZX-80Z10T2 1TB                            | 1         | 0.88%   |
| WDC WD10SPZX-75Z10T3 1TB                            | 1         | 0.88%   |
| WDC WD10EZEX-60WN4A0 1TB                            | 1         | 0.88%   |
| WDC WD10EZEX-00KUWA0 1TB                            | 1         | 0.88%   |
| WDC WD1001FALS-41Y6A1 1TB                           | 1         | 0.88%   |
| Toshiba MQ04ABF100 1TB                              | 1         | 0.88%   |
| Toshiba MQ01ABD050V -63 500GB                       | 1         | 0.88%   |
| Toshiba DT01ACA050 500GB                            | 1         | 0.88%   |
| Seagate ST9500325AS 500GB                           | 1         | 0.88%   |
| Seagate ST9100824AS 100GB                           | 1         | 0.88%   |
| Seagate ST8000VN0022-2EL112 8TB                     | 1         | 0.88%   |
| Seagate ST8000AS0002-1NA17Z 8TB                     | 1         | 0.88%   |
| Seagate ST380811AS 80GB                             | 1         | 0.88%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 19        | 25     | 39.58%  |
| Seagate             | 17        | 27     | 35.42%  |
| Hitachi             | 6         | 6      | 12.5%   |
| Toshiba             | 3         | 4      | 6.25%   |
| HGST                | 2         | 2      | 4.17%   |
| Samsung Electronics | 1         | 1      | 2.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| China               | 5         | 7      | 14.29%  |
| KingSpec            | 4         | 4      | 11.43%  |
| Crucial             | 4         | 4      | 11.43%  |
| SanDisk             | 3         | 3      | 8.57%   |
| Samsung Electronics | 3         | 4      | 8.57%   |
| PNY                 | 3         | 4      | 8.57%   |
| Kingston            | 3         | 5      | 8.57%   |
| WDC                 | 2         | 2      | 5.71%   |
| LITEON              | 2         | 3      | 5.71%   |
| A-DATA Technology   | 2         | 2      | 5.71%   |
| XrayDisk            | 1         | 1      | 2.86%   |
| BHT                 | 1         | 1      | 2.86%   |
| Apacer              | 1         | 1      | 2.86%   |
| Unknown             | 1         | 1      | 2.86%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 41        | 65     | 43.62%  |
| SSD     | 30        | 42     | 31.91%  |
| NVMe    | 17        | 19     | 18.09%  |
| Unknown | 4         | 4      | 4.26%   |
| MMC     | 2         | 2      | 2.13%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 57        | 106    | 70.37%  |
| NVMe | 17        | 19     | 20.99%  |
| SAS  | 5         | 5      | 6.17%   |
| MMC  | 2         | 2      | 2.47%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 40        | 63     | 57.14%  |
| 0.51-1.0   | 22        | 29     | 31.43%  |
| 1.01-2.0   | 3         | 5      | 4.29%   |
| 3.01-4.0   | 2         | 6      | 2.86%   |
| 4.01-10.0  | 2         | 3      | 2.86%   |
| 2.01-3.0   | 1         | 1      | 1.43%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 1001-2000      | 14        | 21.88%  |
| 251-500        | 13        | 20.31%  |
| 2001-3000      | 11        | 17.19%  |
| 101-250        | 10        | 15.63%  |
| More than 3000 | 7         | 10.94%  |
| 501-1000       | 7         | 10.94%  |
| 1-20           | 2         | 3.13%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 21-50          | 23        | 33.82%  |
| 51-100         | 14        | 20.59%  |
| 101-250        | 10        | 14.71%  |
| 251-500        | 7         | 10.29%  |
| 1-20           | 6         | 8.82%   |
| 501-1000       | 5         | 7.35%   |
| More than 3000 | 1         | 1.47%   |
| 2001-3000      | 1         | 1.47%   |
| 1001-2000      | 1         | 1.47%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                  | Computers | Drives | Percent |
|----------------------------------------|-----------|--------|---------|
| WDC WD800AAJS-75M0A0 80GB              | 1         | 1      | 6.67%   |
| WDC WD5000AAKX-08U6AA0 500GB           | 1         | 1      | 6.67%   |
| WDC WD3200BPVT-00JJ5T0 320GB           | 1         | 3      | 6.67%   |
| WDC WD1001FALS-41Y6A1 1TB              | 1         | 2      | 6.67%   |
| Seagate ST9100824AS 100GB              | 1         | 1      | 6.67%   |
| Seagate ST8000AS0002-1NA17Z 8TB        | 1         | 1      | 6.67%   |
| Seagate ST500DM002-1BD142 500GB        | 1         | 2      | 6.67%   |
| Seagate ST3320613AS 320GB              | 1         | 1      | 6.67%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 1         | 1      | 6.67%   |
| Hitachi HTS727575A9E364 752GB          | 1         | 1      | 6.67%   |
| Hitachi HTS545032A7E380 320GB          | 1         | 1      | 6.67%   |
| Hitachi HDS721050DLE630 500GB          | 1         | 1      | 6.67%   |
| Crucial CT500MX200SSD3 500GB           | 1         | 1      | 6.67%   |
| China SATA SSD 240GB                   | 1         | 1      | 6.67%   |
| ADATA Technology SM2P32A8-512GC1 512GB | 1         | 1      | 6.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor           | Computers | Drives | Percent |
|------------------|-----------|--------|---------|
| Seagate          | 5         | 6      | 33.33%  |
| WDC              | 4         | 7      | 26.67%  |
| Hitachi          | 3         | 3      | 20%     |
| Crucial          | 1         | 1      | 6.67%   |
| China            | 1         | 1      | 6.67%   |
| ADATA Technology | 1         | 1      | 6.67%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 6      | 41.67%  |
| WDC     | 4         | 7      | 33.33%  |
| Hitachi | 3         | 3      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 11        | 16     | 78.57%  |
| SSD  | 2         | 2      | 14.29%  |
| NVMe | 1         | 1      | 7.14%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 32        | 53     | 40.51%  |
| Works    | 32        | 59     | 40.51%  |
| Malfunc  | 14        | 19     | 17.72%  |
| Failed   | 1         | 1      | 1.27%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 46        | 60.53%  |
| AMD                         | 10        | 13.16%  |
| ADATA Technology            | 4         | 5.26%   |
| Samsung Electronics         | 3         | 3.95%   |
| VIA Technologies            | 2         | 2.63%   |
| SanDisk                     | 2         | 2.63%   |
| Netac Technology            | 2         | 2.63%   |
| Micron/Crucial Technology   | 2         | 2.63%   |
| Kingston Technology Company | 2         | 2.63%   |
| Phison Electronics          | 1         | 1.32%   |
| Nvidia                      | 1         | 1.32%   |
| MAXIO Technology (Hangzhou) | 1         | 1.32%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 6         | 6.98%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 5         | 5.81%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5         | 5.81%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 5         | 5.81%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 5         | 5.81%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 4         | 4.65%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4         | 4.65%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3         | 3.49%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3         | 3.49%   |
| AMD 500 Series Chipset SATA Controller                                                  | 3         | 3.49%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 2         | 2.33%   |
| VIA VT8237A SATA 2-Port Controller                                                      | 2         | 2.33%   |
| Netac Non-Volatile memory controller                                                    | 2         | 2.33%   |
| Micron/Crucial P5 NVMe PCIe SSD[SlashP5]                                                | 2         | 2.33%   |
| Intel Tiger Lake SATA AHCI Controller                                                   | 2         | 2.33%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2         | 2.33%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 2         | 2.33%   |
| ADATA A Non-Volatile memory controller                                                  | 2         | 2.33%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                                      | 1         | 1.16%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1         | 1.16%   |
| Phison E12 NVMe Controller                                                              | 1         | 1.16%   |
| Nvidia MCP61 SATA Controller                                                            | 1         | 1.16%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                            | 1         | 1.16%   |
| Kingston Company OM3PDP3 NVMe SSD                                                       | 1         | 1.16%   |
| Kingston Company NVMe Controller                                                        | 1         | 1.16%   |
| Intel SSD 660P Series                                                                   | 1         | 1.16%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 1         | 1.16%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1         | 1.16%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 1         | 1.16%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 1         | 1.16%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 1         | 1.16%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 1         | 1.16%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1         | 1.16%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1         | 1.16%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1         | 1.16%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 1         | 1.16%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1         | 1.16%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 1         | 1.16%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 1         | 1.16%   |
| AMD X399 Series Chipset SATA Controller                                                 | 1         | 1.16%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 49        | 62.82%  |
| NVMe | 16        | 20.51%  |
| IDE  | 7         | 8.97%   |
| RAID | 6         | 7.69%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 51        | 79.69%  |
| AMD    | 13        | 20.31%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Pentium D CPU 3.00GHz                 | 2         | 3.13%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 2         | 3.13%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 3.13%   |
| AMD Ryzen 5 5600 6-Core Processor           | 2         | 3.13%   |
| Intel Xeon CPU E5-2420 v2 @ 2.20GHz         | 1         | 1.56%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1         | 1.56%   |
| Intel Pentium Dual CPU T2330 @ 1.60GHz      | 1         | 1.56%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 1         | 1.56%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 1         | 1.56%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 1.56%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1         | 1.56%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 1         | 1.56%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 1         | 1.56%   |
| Intel Core i7-2860QM CPU @ 2.50GHz          | 1         | 1.56%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 1         | 1.56%   |
| Intel Core i7-2630QM CPU @ 2.00GHz          | 1         | 1.56%   |
| Intel Core i7 CPU S 860 @ 2.53GHz           | 1         | 1.56%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 1         | 1.56%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 1         | 1.56%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 1         | 1.56%   |
| Intel Core i5-4570T CPU @ 2.90GHz           | 1         | 1.56%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 1         | 1.56%   |
| Intel Core i5-3337U CPU @ 1.80GHz           | 1         | 1.56%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 1         | 1.56%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 1         | 1.56%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 1         | 1.56%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 1         | 1.56%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 1         | 1.56%   |
| Intel Core i5-2300 CPU @ 2.80GHz            | 1         | 1.56%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 1         | 1.56%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 1         | 1.56%   |
| Intel Core i3-7100U CPU @ 2.40GHz           | 1         | 1.56%   |
| Intel Core i3-7020U CPU @ 2.30GHz           | 1         | 1.56%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 1         | 1.56%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 1         | 1.56%   |
| Intel Core i3-4030U CPU @ 1.90GHz           | 1         | 1.56%   |
| Intel Core i3-3250 CPU @ 3.50GHz            | 1         | 1.56%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 1         | 1.56%   |
| Intel Core i3-2375M CPU @ 1.50GHz           | 1         | 1.56%   |
| Intel Core i3-10100F CPU @ 3.60GHz          | 1         | 1.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 16        | 25%     |
| Intel Core i7           | 11        | 17.19%  |
| Intel Core i3           | 9         | 14.06%  |
| AMD Ryzen 5             | 6         | 9.38%   |
| Other                   | 5         | 7.81%   |
| Intel Pentium D         | 2         | 3.13%   |
| Intel Celeron           | 2         | 3.13%   |
| AMD Ryzen 7             | 2         | 3.13%   |
| Intel Xeon              | 1         | 1.56%   |
| Intel Pentium Dual-Core | 1         | 1.56%   |
| Intel Pentium Dual      | 1         | 1.56%   |
| Intel Pentium           | 1         | 1.56%   |
| Intel Core 2 Quad       | 1         | 1.56%   |
| Intel Atom              | 1         | 1.56%   |
| AMD Ryzen Threadripper  | 1         | 1.56%   |
| AMD Ryzen 9             | 1         | 1.56%   |
| AMD C-70                | 1         | 1.56%   |
| AMD C-60                | 1         | 1.56%   |
| AMD Athlon              | 1         | 1.56%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 28        | 43.75%  |
| 4      | 20        | 31.25%  |
| 6      | 8         | 12.5%   |
| 8      | 4         | 6.25%   |
| 12     | 2         | 3.13%   |
| 14     | 1         | 1.56%   |
| 1      | 1         | 1.56%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 64        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 45        | 70.31%  |
| 1      | 19        | 29.69%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 63        | 98.44%  |
| Unknown        | 1         | 1.56%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 11        | 17.19%  |
| 0x206a7    | 8         | 12.5%   |
| 0x806e9    | 5         | 7.81%   |
| 0x306c3    | 4         | 6.25%   |
| 0x306a9    | 4         | 6.25%   |
| 0x506e3    | 3         | 4.69%   |
| 0xf64      | 2         | 3.13%   |
| 0x906a3    | 2         | 3.13%   |
| 0x806d1    | 2         | 3.13%   |
| 0x05000119 | 2         | 3.13%   |
| 0xa0671    | 1         | 1.56%   |
| 0x906ed    | 1         | 1.56%   |
| 0x806ec    | 1         | 1.56%   |
| 0x706e5    | 1         | 1.56%   |
| 0x6fd      | 1         | 1.56%   |
| 0x6fb      | 1         | 1.56%   |
| 0x406e3    | 1         | 1.56%   |
| 0x406c4    | 1         | 1.56%   |
| 0x306e4    | 1         | 1.56%   |
| 0x30678    | 1         | 1.56%   |
| 0x20652    | 1         | 1.56%   |
| 0x1067a    | 1         | 1.56%   |
| 0x0a50000d | 1         | 1.56%   |
| 0x0a20120a | 1         | 1.56%   |
| 0x0a201025 | 1         | 1.56%   |
| 0x08701021 | 1         | 1.56%   |
| 0x08600106 | 1         | 1.56%   |
| 0x08108109 | 1         | 1.56%   |
| 0x0810100b | 1         | 1.56%   |
| 0x0800820d | 1         | 1.56%   |
| 0x08001137 | 1         | 1.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| SandyBridge      | 10        | 15.63%  |
| KabyLake         | 8         | 12.5%   |
| IvyBridge        | 6         | 9.38%   |
| Haswell          | 6         | 9.38%   |
| Skylake          | 5         | 7.81%   |
| Zen 3            | 3         | 4.69%   |
| Zen 2            | 3         | 4.69%   |
| Icelake          | 3         | 4.69%   |
| Zen+             | 2         | 3.13%   |
| Zen              | 2         | 3.13%   |
| Silvermont       | 2         | 3.13%   |
| NetBurst         | 2         | 3.13%   |
| Core             | 2         | 3.13%   |
| Bobcat           | 2         | 3.13%   |
| Alderlake Hybrid | 2         | 3.13%   |
| Westmere         | 1         | 1.56%   |
| Penryn           | 1         | 1.56%   |
| Nehalem          | 1         | 1.56%   |
| K8 Hammer        | 1         | 1.56%   |
| CometLake        | 1         | 1.56%   |
| Unknown          | 1         | 1.56%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 35        | 46.05%  |
| Nvidia | 25        | 32.89%  |
| AMD    | 16        | 21.05%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                       | 6         | 7.79%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 6         | 7.79%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 3         | 3.9%    |
| Nvidia GP108 [GeForce GT 1030]                                              | 2         | 2.6%    |
| Nvidia GM108M [GeForce 940MX]                                               | 2         | 2.6%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2         | 2.6%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 2         | 2.6%    |
| Intel Alder Lake-P Integrated Graphics Controller                           | 2         | 2.6%    |
| AMD Renoir                                                                  | 2         | 2.6%    |
| AMD Caicos PRO [Radeon HD 7450]                                             | 2         | 2.6%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 1         | 1.3%    |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1         | 1.3%    |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1         | 1.3%    |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1         | 1.3%    |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1         | 1.3%    |
| Nvidia TU106 [GeForce GTX 1650]                                             | 1         | 1.3%    |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 1         | 1.3%    |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                    | 1         | 1.3%    |
| Nvidia GM206 [GeForce GTX 960]                                              | 1         | 1.3%    |
| Nvidia GM108M [GeForce 920MX]                                               | 1         | 1.3%    |
| Nvidia GM107 [GeForce GTX 750]                                              | 1         | 1.3%    |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1         | 1.3%    |
| Nvidia GK208B [GeForce GT 710]                                              | 1         | 1.3%    |
| Nvidia GK106M [GeForce GTX 770M]                                            | 1         | 1.3%    |
| Nvidia GF116M [GeForce GT 560M]                                             | 1         | 1.3%    |
| Nvidia GF108M [GeForce GT 540M]                                             | 1         | 1.3%    |
| Nvidia GA107BM [GeForce RTX 3050 Mobile]                                    | 1         | 1.3%    |
| Nvidia GA104 [Geforce RTX 3070 Ti Laptop GPU]                               | 1         | 1.3%    |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 1         | 1.3%    |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 1         | 1.3%    |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 1         | 1.3%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1         | 1.3%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 1         | 1.3%    |
| Intel Skylake GT2 [HD Graphics 520]                                         | 1         | 1.3%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)         | 1         | 1.3%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)           | 1         | 1.3%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                      | 1         | 1.3%    |
| Intel HD Graphics 530                                                       | 1         | 1.3%    |
| Intel HD Graphics 510                                                       | 1         | 1.3%    |
| Intel Haswell-ULT Integrated Graphics Controller                            | 1         | 1.3%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 22        | 34.38%  |
| 1 x Nvidia     | 15        | 23.44%  |
| 1 x AMD        | 15        | 23.44%  |
| Intel + Nvidia | 10        | 15.63%  |
| 2 x Intel      | 1         | 1.56%   |
| Intel + AMD    | 1         | 1.56%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 44        | 68.75%  |
| Proprietary | 18        | 28.13%  |
| Unknown     | 2         | 3.13%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 33        | 51.56%  |
| 1.01-2.0   | 12        | 18.75%  |
| 0.01-0.5   | 5         | 7.81%   |
| 3.01-4.0   | 4         | 6.25%   |
| 7.01-8.0   | 3         | 4.69%   |
| 0.51-1.0   | 3         | 4.69%   |
| 5.01-6.0   | 2         | 3.13%   |
| 2.01-3.0   | 1         | 1.56%   |
| 8.01-16.0  | 1         | 1.56%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 11        | 15.94%  |
| Goldstar                | 8         | 11.59%  |
| Chimei Innolux          | 8         | 11.59%  |
| LG Display              | 6         | 8.7%    |
| BOE                     | 6         | 8.7%    |
| AU Optronics            | 6         | 8.7%    |
| AOC                     | 3         | 4.35%   |
| Unknown (XXX)           | 2         | 2.9%    |
| Positivo                | 2         | 2.9%    |
| Philips                 | 2         | 2.9%    |
| Panasonic               | 2         | 2.9%    |
| Hewlett-Packard         | 2         | 2.9%    |
| Chi Mei Optoelectronics | 2         | 2.9%    |
| NEC Computers           | 1         | 1.45%   |
| LG Electronics          | 1         | 1.45%   |
| Lenovo                  | 1         | 1.45%   |
| ITE                     | 1         | 1.45%   |
| Dell                    | 1         | 1.45%   |
| CSO                     | 1         | 1.45%   |
| BenQ                    | 1         | 1.45%   |
| ASUSTek Computer        | 1         | 1.45%   |
| Apple                   | 1         | 1.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SyncMaster SAM037A 1680x1050 433x271mm 20.1-inch    | 2         | 2.74%   |
| Panasonic TV MEIC10C 1920x540 697x392mm 31.5-inch                       | 2         | 2.74%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                 | 2         | 2.74%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch         | 2         | 2.74%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch           | 1         | 1.37%   |
| Unknown (XXX) Beyond TV XXX2851 1920x1080 1209x680mm 54.6-inch          | 1         | 1.37%   |
| Samsung Electronics T22B300 SAM092D 1920x1080 477x268mm 21.5-inch       | 1         | 1.37%   |
| Samsung Electronics SyncMaster SAM05EB 1920x1080 597x336mm 27.0-inch    | 1         | 1.37%   |
| Samsung Electronics SyncMaster SAM0471 1360x768 344x194mm 15.5-inch     | 1         | 1.37%   |
| Samsung Electronics S24C450 SAM09CF 1920x1200 518x324mm 24.1-inch       | 1         | 1.37%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch    | 1         | 1.37%   |
| Samsung Electronics LCD Monitor SAM0FEF 3840x2160 1872x1053mm 84.6-inch | 1         | 1.37%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch    | 1         | 1.37%   |
| Samsung Electronics LCD Monitor SAM02C9 1360x768 885x498mm 40.0-inch    | 1         | 1.37%   |
| Samsung Electronics LCD Monitor C24F390 1920x1080                       | 1         | 1.37%   |
| Positivo UNION NON1500 1360x768 344x194mm 15.5-inch                     | 1         | 1.37%   |
| Positivo FIT85X NON1801 1360x768 344x194mm 15.5-inch                    | 1         | 1.37%   |
| Philips PHL 221V8 PHLC211 1920x1080 477x268mm 21.5-inch                 | 1         | 1.37%   |
| Philips 237E4 PHLC0AD 1920x1080 509x286mm 23.0-inch                     | 1         | 1.37%   |
| NEC Computers LCD1770VX NEC6697 1280x960 338x270mm 17.0-inch            | 1         | 1.37%   |
| LG Electronics LCD Monitor LG FULL HD 3200x1080                         | 1         | 1.37%   |
| LG Electronics LCD Monitor LG FULL HD                                   | 1         | 1.37%   |
| LG Display LCD Monitor LGD04BD 1366x768 344x194mm 15.5-inch             | 1         | 1.37%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch            | 1         | 1.37%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch             | 1         | 1.37%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch             | 1         | 1.37%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch             | 1         | 1.37%   |
| LG Display LCD Monitor LGD02DA 1920x1080 382x215mm 17.3-inch            | 1         | 1.37%   |
| Lenovo LCD Monitor LEN4035 1280x800 303x190mm 14.1-inch                 | 1         | 1.37%   |
| ITE DP2VGA V235 ITE6516 1920x1080 600x340mm 27.2-inch                   | 1         | 1.37%   |
| Hewlett-Packard 25mx HPN359B 1920x1080 544x303mm 24.5-inch              | 1         | 1.37%   |
| Hewlett-Packard 23tm HWP3110 1920x1080 509x286mm 23.0-inch              | 1         | 1.37%   |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                     | 1         | 1.37%   |
| Goldstar ULTRAWIDE GSM5C0C 2560x1080 601x254mm 25.7-inch                | 1         | 1.37%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                | 1         | 1.37%   |
| Goldstar L1753T GSM4476 1280x1024 338x270mm 17.0-inch                   | 1         | 1.37%   |
| Goldstar HD 16 GSM3E92 1366x768 344x194mm 15.5-inch                     | 1         | 1.37%   |
| Goldstar 25UM58G GSM5B98 2560x1080 673x284mm 28.8-inch                  | 1         | 1.37%   |
| Goldstar 23EA53 GSM59A9 1920x1080 510x290mm 23.1-inch                   | 1         | 1.37%   |
| Dell LCD Monitor E170S 3200x1080                                        | 1         | 1.37%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 21        | 30%     |
| 1366x768 (WXGA)    | 20        | 28.57%  |
| 2560x1080          | 5         | 7.14%   |
| 3840x2160 (4K)     | 4         | 5.71%   |
| 1360x768           | 4         | 5.71%   |
| 1600x900 (HD+)     | 3         | 4.29%   |
| 1920x540           | 2         | 2.86%   |
| 1680x1050 (WSXGA+) | 2         | 2.86%   |
| 1280x800 (WXGA)    | 2         | 2.86%   |
| 3200x1080          | 1         | 1.43%   |
| 2880x1800          | 1         | 1.43%   |
| 2560x1440 (QHD)    | 1         | 1.43%   |
| 1920x1200 (WUXGA)  | 1         | 1.43%   |
| 1280x960           | 1         | 1.43%   |
| 1280x1024 (SXGA)   | 1         | 1.43%   |
| Unknown            | 1         | 1.43%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 13        | 18.57%  |
| 14      | 9         | 12.86%  |
| 17      | 8         | 11.43%  |
| 13      | 6         | 8.57%   |
| 23      | 4         | 5.71%   |
| 18      | 4         | 5.71%   |
| 34      | 3         | 4.29%   |
| 31      | 3         | 4.29%   |
| 27      | 3         | 4.29%   |
| 24      | 3         | 4.29%   |
| 20      | 3         | 4.29%   |
| Unknown | 3         | 4.29%   |
| 54      | 2         | 2.86%   |
| 21      | 2         | 2.86%   |
| 84      | 1         | 1.43%   |
| 40      | 1         | 1.43%   |
| 28      | 1         | 1.43%   |
| 25      | 1         | 1.43%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 29        | 42.03%  |
| 501-600     | 9         | 13.04%  |
| 401-500     | 9         | 13.04%  |
| 351-400     | 6         | 8.7%    |
| 601-700     | 5         | 7.25%   |
| 701-800     | 3         | 4.35%   |
| Unknown     | 3         | 4.35%   |
| 1001-1500   | 2         | 2.9%    |
| 801-900     | 1         | 1.45%   |
| 201-300     | 1         | 1.45%   |
| 1501-2000   | 1         | 1.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 48        | 75%     |
| 16/10   | 6         | 9.38%   |
| 21/9    | 5         | 7.81%   |
| Unknown | 3         | 4.69%   |
| 5/4     | 2         | 3.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 15        | 21.74%  |
| 101-110        | 13        | 18.84%  |
| 201-250        | 7         | 10.14%  |
| 351-500        | 6         | 8.7%    |
| 141-150        | 6         | 8.7%    |
| 121-130        | 6         | 8.7%    |
| More than 1000 | 3         | 4.35%   |
| 301-350        | 3         | 4.35%   |
| 251-300        | 3         | 4.35%   |
| 151-200        | 3         | 4.35%   |
| Unknown        | 3         | 4.35%   |
| 501-1000       | 1         | 1.45%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 25        | 37.88%  |
| 101-120       | 23        | 34.85%  |
| 121-160       | 10        | 15.15%  |
| 1-50          | 3         | 4.55%   |
| Unknown       | 3         | 4.55%   |
| More than 240 | 1         | 1.52%   |
| 161-240       | 1         | 1.52%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 48        | 73.85%  |
| 2     | 14        | 21.54%  |
| 0     | 3         | 4.62%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 44        | 43.14%  |
| Intel                    | 21        | 20.59%  |
| Qualcomm Atheros         | 18        | 17.65%  |
| VIA Technologies         | 2         | 1.96%   |
| Ralink Technology        | 2         | 1.96%   |
| D-Link System            | 2         | 1.96%   |
| Broadcom                 | 2         | 1.96%   |
| TP-Link                  | 1         | 0.98%   |
| Samsung Electronics      | 1         | 0.98%   |
| Ralink                   | 1         | 0.98%   |
| Prolific Technology      | 1         | 0.98%   |
| MediaTek                 | 1         | 0.98%   |
| Marvell Technology Group | 1         | 0.98%   |
| JMicron Technology       | 1         | 0.98%   |
| Edimax Technology        | 1         | 0.98%   |
| D-Link                   | 1         | 0.98%   |
| Belkin Components        | 1         | 0.98%   |
| ASIX Electronics         | 1         | 0.98%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 26        | 21.31%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 10        | 8.2%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 6         | 4.92%   |
| Realtek RTL8125 2.5GbE Controller                                                     | 4         | 3.28%   |
| Realtek 802.11ac NIC                                                                  | 3         | 2.46%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 3         | 2.46%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 3         | 2.46%   |
| VIA VT6102/VT6103 [Rhine-II]                                                          | 2         | 1.64%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                       | 2         | 1.64%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                 | 2         | 1.64%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 2         | 1.64%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                              | 2         | 1.64%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 2         | 1.64%   |
| Intel Wi-Fi 6 AX200                                                                   | 2         | 1.64%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                      | 2         | 1.64%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                                       | 2         | 1.64%   |
| TP-Link Archer T4U ver.3                                                              | 1         | 0.82%   |
| Samsung Galaxy series, misc. (tethering mode)                                         | 1         | 0.82%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 1         | 0.82%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                                   | 1         | 0.82%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                       | 1         | 0.82%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                 | 1         | 0.82%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                                      | 1         | 0.82%   |
| Realtek 802.11n WLAN Adapter                                                          | 1         | 0.82%   |
| Ralink RT5370 Wireless Adapter                                                        | 1         | 0.82%   |
| Ralink MT7601U Wireless Adapter                                                       | 1         | 0.82%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                             | 1         | 0.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 1         | 0.82%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                             | 1         | 0.82%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                             | 1         | 0.82%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                             | 1         | 0.82%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                              | 1         | 0.82%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                            | 1         | 0.82%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 0.82%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 1         | 0.82%   |
| Prolific USB-Serial Controller                                                        | 1         | 0.82%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                               | 1         | 0.82%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                                  | 1         | 0.82%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                                | 1         | 0.82%   |
| Intel Wireless 8265 / 8275                                                            | 1         | 0.82%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 15        | 29.41%  |
| Qualcomm Atheros      | 14        | 27.45%  |
| Realtek Semiconductor | 12        | 23.53%  |
| Ralink Technology     | 2         | 3.92%   |
| Broadcom              | 2         | 3.92%   |
| TP-Link               | 1         | 1.96%   |
| Ralink                | 1         | 1.96%   |
| MediaTek              | 1         | 1.96%   |
| Edimax Technology     | 1         | 1.96%   |
| D-Link                | 1         | 1.96%   |
| Belkin Components     | 1         | 1.96%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                  | Computers | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                             | 6         | 11.54%  |
| Realtek 802.11ac NIC                                                                   | 3         | 5.77%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                             | 3         | 5.77%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                        | 2         | 3.85%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                  | 2         | 3.85%   |
| Realtek RTL8188EE Wireless Network Adapter                                             | 2         | 3.85%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                         | 2         | 3.85%   |
| Intel Wi-Fi 6 AX200                                                                    | 2         | 3.85%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                       | 2         | 3.85%   |
| TP-Link Archer T4U ver.3                                                               | 1         | 1.92%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                               | 1         | 1.92%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                                    | 1         | 1.92%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                        | 1         | 1.92%   |
| Realtek 802.11n WLAN Adapter                                                           | 1         | 1.92%   |
| Ralink RT5370 Wireless Adapter                                                         | 1         | 1.92%   |
| Ralink MT7601U Wireless Adapter                                                        | 1         | 1.92%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                              | 1         | 1.92%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                             | 1         | 1.92%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express)  | 1         | 1.92%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                | 1         | 1.92%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                | 1         | 1.92%   |
| Intel Wireless 8265 / 8275                                                             | 1         | 1.92%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                 | 1         | 1.92%   |
| Intel Tiger Lake PCH CNVi WiFi                                                         | 1         | 1.92%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                        | 1         | 1.92%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                       | 1         | 1.92%   |
| Intel Centrino Wireless-N 105                                                          | 1         | 1.92%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                          | 1         | 1.92%   |
| Intel Centrino Ultimate-N 6300                                                         | 1         | 1.92%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                                          | 1         | 1.92%   |
| Intel Centrino Advanced-N 6200                                                         | 1         | 1.92%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                               | 1         | 1.92%   |
| Edimax EW-7711MAC 802.11ac Wireless Adapter                                            | 1         | 1.92%   |
| D-Link DWA-171 AC600 DB Wireless Adapter(rev.A1) [Realtek RTL8811AU]                   | 1         | 1.92%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                     | 1         | 1.92%   |
| Broadcom BCM4331 802.11a/b/g/n                                                         | 1         | 1.92%   |
| Belkin Components F6D4050 N150 Enhanced Wireless Network Adapter v1000 [Ralink RT3070] | 1         | 1.92%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 40        | 61.54%  |
| Intel                    | 11        | 16.92%  |
| Qualcomm Atheros         | 5         | 7.69%   |
| VIA Technologies         | 2         | 3.08%   |
| D-Link System            | 2         | 3.08%   |
| Samsung Electronics      | 1         | 1.54%   |
| Marvell Technology Group | 1         | 1.54%   |
| JMicron Technology       | 1         | 1.54%   |
| Broadcom                 | 1         | 1.54%   |
| ASIX Electronics         | 1         | 1.54%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 26        | 37.68%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10        | 14.49%  |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 5.8%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 4.35%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 2         | 2.9%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 2.9%    |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2         | 2.9%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.45%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.45%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 1.45%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.45%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.45%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 1.45%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.45%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.45%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 1         | 1.45%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 1.45%   |
| Intel I211 Gigabit Network Connection                             | 1         | 1.45%   |
| Intel Ethernet Controller I225-V                                  | 1         | 1.45%   |
| Intel Ethernet Controller I225-LM                                 | 1         | 1.45%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.45%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.45%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 1.45%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 1.45%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.45%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 1.45%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 1.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 60        | 55.56%  |
| WiFi     | 47        | 43.52%  |
| Modem    | 1         | 0.93%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 33        | 51.56%  |
| WiFi     | 31        | 48.44%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 38        | 59.38%  |
| 1     | 23        | 35.94%  |
| 3     | 2         | 3.13%   |
| 0     | 1         | 1.56%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 39        | 60.94%  |
| Yes  | 25        | 39.06%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 12        | 34.29%  |
| Qualcomm Atheros Communications | 6         | 17.14%  |
| Lite-On Technology              | 4         | 11.43%  |
| Cambridge Silicon Radio         | 4         | 11.43%  |
| Realtek Semiconductor           | 3         | 8.57%   |
| MediaTek                        | 1         | 2.86%   |
| IMC Networks                    | 1         | 2.86%   |
| Hewlett-Packard                 | 1         | 2.86%   |
| Foxconn / Hon Hai               | 1         | 2.86%   |
| Broadcom                        | 1         | 2.86%   |
| Apple                           | 1         | 2.86%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Qualcomm Atheros  Bluetooth Device                  | 4         | 11.43%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 11.43%  |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 8.57%   |
| Intel AX201 Bluetooth                               | 3         | 8.57%   |
| Realtek Bluetooth Radio                             | 2         | 5.71%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 5.71%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 2         | 5.71%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 5.71%   |
| Intel AX200 Bluetooth                               | 2         | 5.71%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 2.86%   |
| MediaTek Wireless_Device                            | 1         | 2.86%   |
| Lite-On Bluetooth Device                            | 1         | 2.86%   |
| Intel Bluetooth wireless interface                  | 1         | 2.86%   |
| Intel Bluetooth Device                              | 1         | 2.86%   |
| Intel AX210 Bluetooth                               | 1         | 2.86%   |
| IMC Networks BCM20702A0                             | 1         | 2.86%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 2.86%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 1         | 2.86%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 2.86%   |
| Apple Bluetooth USB Host Controller                 | 1         | 2.86%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 48        | 48.98%  |
| Nvidia                 | 21        | 21.43%  |
| AMD                    | 19        | 19.39%  |
| C-Media Electronics    | 3         | 3.06%   |
| Generalplus Technology | 2         | 2.04%   |
| Creative Labs          | 2         | 2.04%   |
| Roland                 | 1         | 1.02%   |
| Realtek Semiconductor  | 1         | 1.02%   |
| Razer USA              | 1         | 1.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 10        | 9.17%   |
| Intel Sunrise Point-LP HD Audio                                                   | 7         | 6.42%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 6         | 5.5%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 5         | 4.59%   |
| AMD Family 17h/19h HD Audio Controller                                            | 5         | 4.59%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 4         | 3.67%   |
| Nvidia TU106 High Definition Audio Controller                                     | 3         | 2.75%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 3         | 2.75%   |
| AMD Starship/Matisse HD Audio Controller                                          | 3         | 2.75%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 3         | 2.75%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 3         | 2.75%   |
| Nvidia TU116 High Definition Audio Controller                                     | 2         | 1.83%   |
| Nvidia GP108 High Definition Audio Controller                                     | 2         | 1.83%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 2         | 1.83%   |
| Nvidia GA104 High Definition Audio Controller                                     | 2         | 1.83%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 2         | 1.83%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 2         | 1.83%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                           | 2         | 1.83%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 2         | 1.83%   |
| Generalplus Technology USB Audio Device                                           | 2         | 1.83%   |
| Creative Labs CA0106/CA0111 [SB Live!/Audigy/X-Fi Series]                         | 2         | 1.83%   |
| AMD Wrestler HDMI Audio                                                           | 2         | 1.83%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 2         | 1.83%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 2         | 1.83%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 2         | 1.83%   |
| Roland QUAD-CAPTURE                                                               | 1         | 0.92%   |
| Realtek Semiconductor USB Audio                                                   | 1         | 0.92%   |
| Razer USA Razer Leviathan V2                                                      | 1         | 0.92%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 1         | 0.92%   |
| Nvidia TU102 High Definition Audio Controller                                     | 1         | 0.92%   |
| Nvidia MCP61 High Definition Audio                                                | 1         | 0.92%   |
| Nvidia GP104 High Definition Audio Controller                                     | 1         | 0.92%   |
| Nvidia GM206 High Definition Audio Controller                                     | 1         | 0.92%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 1         | 0.92%   |
| Nvidia GK106 HDMI Audio Controller                                                | 1         | 0.92%   |
| Nvidia GF116 High Definition Audio Controller                                     | 1         | 0.92%   |
| Nvidia GF108 High Definition Audio Controller                                     | 1         | 0.92%   |
| Nvidia Audio device                                                               | 1         | 0.92%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                         | 1         | 0.92%   |
| Intel Haswell-ULT HD Audio Controller                                             | 1         | 0.92%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 10        | 16.39%  |
| Samsung Electronics | 10        | 16.39%  |
| Kingston            | 9         | 14.75%  |
| Smart               | 5         | 8.2%    |
| SK hynix            | 5         | 8.2%    |
| Micron Technology   | 5         | 8.2%    |
| Corsair             | 4         | 6.56%   |
| Teikon              | 2         | 3.28%   |
| Crucial             | 2         | 3.28%   |
| A-DATA Technology   | 2         | 3.28%   |
| Unknown             | 2         | 3.28%   |
| Ramaxel Technology  | 1         | 1.64%   |
| PLEXHD              | 1         | 1.64%   |
| Nanya Technology    | 1         | 1.64%   |
| Kembona             | 1         | 1.64%   |
| G.Skill             | 1         | 1.64%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB DIMM SDRAM                         | 2         | 2.99%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s     | 2         | 2.99%   |
| Unknown                                                   | 2         | 2.99%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s               | 1         | 1.49%   |
| Unknown RAM Module 8GB DIMM SDRAM                         | 1         | 1.49%   |
| Unknown RAM Module 512MB SODIMM DDR2                      | 1         | 1.49%   |
| Unknown RAM Module 4GB SODIMM DDR4 2133MT/s               | 1         | 1.49%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                 | 1         | 1.49%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s               | 1         | 1.49%   |
| Unknown RAM Module 2GB SODIMM DDR2                        | 1         | 1.49%   |
| Unknown RAM Module 2GB DIMM DDR2 266MT/s                  | 1         | 1.49%   |
| Unknown RAM Module 16GB DIMM DDR4 3200MT/s                | 1         | 1.49%   |
| Teikon RAM TMT351S6EFR8A-PBHJ 4GB SODIMM DDR3 1600MT/s    | 1         | 1.49%   |
| Teikon RAM TMA81GS6AFR8N-UHSC 8GB SODIMM DDR4 2400MT/s    | 1         | 1.49%   |
| Smart RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s     | 1         | 1.49%   |
| Smart RAM SH564568FH8NZPHSCR 2048MB SODIMM DDR3 1333MT/s  | 1         | 1.49%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s     | 1         | 1.49%   |
| Smart RAM SH564128FH8N6TNSQG 4GB DIMM DDR3 1600MT/s       | 1         | 1.49%   |
| Smart RAM SF4641G8CKHIWDFSEG 8GB SODIMM DDR4 2133MT/s     | 1         | 1.49%   |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s     | 1         | 1.49%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1066MT/s              | 1         | 1.49%   |
| SK hynix RAM MMXIV 4096MB SODIMM DDR3 1333MT/s            | 1         | 1.49%   |
| SK hynix RAM MD4512NSE-CB3M2 00 4096MB DIMM DDR4 2400MT/s | 1         | 1.49%   |
| SK hynix RAM HMT41GU6MFR8C-PB 8GB DIMM DDR3 1600MT/s      | 1         | 1.49%   |
| SK hynix RAM HMCG66MEBSA092N 8GB SODIMM DDR5 4800MT/s     | 1         | 1.49%   |
| Samsung RAM Module 2GB Row Of Chips LPDDR3 1600MT/s       | 1         | 1.49%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s     | 1         | 1.49%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s     | 1         | 1.49%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s     | 1         | 1.49%   |
| Samsung RAM M471B1G73BH0-CK0 8GB SODIMM DDR3 1600MT/s     | 1         | 1.49%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s     | 1         | 1.49%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s     | 1         | 1.49%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s       | 1         | 1.49%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s       | 1         | 1.49%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s   | 1         | 1.49%   |
| Ramaxel RAM RMT3170EB68F9W1600 4GB SODIMM DDR3 1600MT/s   | 1         | 1.49%   |
| PLEXHD RAM er 4GB DIMM DDR3 1600MT/s                      | 1         | 1.49%   |
| Nanya RAM Module 2GB DIMM DDR3 1333MT/s                   | 1         | 1.49%   |
| Micron RAM Module 4GB SODIMM DDR3 1600MT/s                | 1         | 1.49%   |
| Micron RAM Module 4GB Row Of Chips LPDDR4 4266MT/s        | 1         | 1.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR3   | 23        | 45.1%   |
| DDR4   | 18        | 35.29%  |
| SDRAM  | 4         | 7.84%   |
| DDR5   | 2         | 3.92%   |
| DDR2   | 2         | 3.92%   |
| LPDDR4 | 1         | 1.96%   |
| LPDDR3 | 1         | 1.96%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 27        | 52.94%  |
| DIMM         | 22        | 43.14%  |
| Row Of Chips | 2         | 3.92%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 21        | 36.21%  |
| 4096  | 16        | 27.59%  |
| 2048  | 11        | 18.97%  |
| 16384 | 6         | 10.34%  |
| 32768 | 2         | 3.45%   |
| 1024  | 1         | 1.72%   |
| 512   | 1         | 1.72%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 16        | 27.59%  |
| 3200    | 6         | 10.34%  |
| 1333    | 6         | 10.34%  |
| 2400    | 5         | 8.62%   |
| 2667    | 4         | 6.9%    |
| 2133    | 4         | 6.9%    |
| 1334    | 4         | 6.9%    |
| Unknown | 4         | 6.9%    |
| 4800    | 2         | 3.45%   |
| 4266    | 1         | 1.72%   |
| 3733    | 1         | 1.72%   |
| 2200    | 1         | 1.72%   |
| 1867    | 1         | 1.72%   |
| 1067    | 1         | 1.72%   |
| 1066    | 1         | 1.72%   |
| 266     | 1         | 1.72%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Seiko Epson L380 Series | 1         | 100%    |

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
| Quanta                                 | 5         | 14.71%  |
| Chicony Electronics                    | 5         | 14.71%  |
| Sunplus Innovation Technology          | 4         | 11.76%  |
| Bison Electronics                      | 3         | 8.82%   |
| Microdia                               | 2         | 5.88%   |
| Lenovo                                 | 2         | 5.88%   |
| Y Media                                | 1         | 2.94%   |
| Sonix Technology                       | 1         | 2.94%   |
| Silicon Motion                         | 1         | 2.94%   |
| Realtek Semiconductor                  | 1         | 2.94%   |
| Microsoft                              | 1         | 2.94%   |
| Lite-On Technology                     | 1         | 2.94%   |
| Jieli Technology                       | 1         | 2.94%   |
| IMC Networks                           | 1         | 2.94%   |
| GEMBIRD                                | 1         | 2.94%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.94%   |
| Apple                                  | 1         | 2.94%   |
| Alcor Micro                            | 1         | 2.94%   |
| Acer                                   | 1         | 2.94%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Quanta VGA WebCam                                | 2         | 5.88%   |
| Microdia Integrated_Webcam_HD                    | 2         | 5.88%   |
| Bison Lenovo EasyCamera                          | 2         | 5.88%   |
| Y Media USB Camera                               | 1         | 2.94%   |
| Sunplus Laptop_Integrated_Webcam_HD              | 1         | 2.94%   |
| Sunplus Laptop Integrated Webcam FHD             | 1         | 2.94%   |
| Sunplus HP HD Webcam [Fixed]                     | 1         | 2.94%   |
| Sunplus FHD Camera Microphone                    | 1         | 2.94%   |
| Sonix USB2.0 HD UVC WebCam                       | 1         | 2.94%   |
| Silicon Motion Web Camera                        | 1         | 2.94%   |
| Realtek USB Camera                               | 1         | 2.94%   |
| Quanta Laptop_Integrated_Webcam_2HDM             | 1         | 2.94%   |
| Quanta HD Webcam                                 | 1         | 2.94%   |
| Quanta HD User Facing                            | 1         | 2.94%   |
| Microsoft LifeCam VX-2000                        | 1         | 2.94%   |
| Lite-On TOSHIBA Web Camera - HD                  | 1         | 2.94%   |
| Lenovo Integrated Webcam [R5U877]                | 1         | 2.94%   |
| Lenovo FHD Webcam                                | 1         | 2.94%   |
| Jieli USB PHY 2.0                                | 1         | 2.94%   |
| IMC Networks Integrated Camera                   | 1         | 2.94%   |
| GEMBIRD USB2.0 PC CAMERA                         | 1         | 2.94%   |
| Chicony Lenovo EasyCamera                        | 1         | 2.94%   |
| Chicony Integrated Camera                        | 1         | 2.94%   |
| Chicony HD WebCam                                | 1         | 2.94%   |
| Chicony FHD Webcam                               | 1         | 2.94%   |
| Chicony 2.0M UVC WebCam                          | 1         | 2.94%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 1         | 2.94%   |
| Bison HD Webcam                                  | 1         | 2.94%   |
| Apple FaceTime HD Camera                         | 1         | 2.94%   |
| Alcor Micro USB 2.0 PC cam                       | 1         | 2.94%   |
| Acer EasyCamera                                  | 1         | 2.94%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 1         | 50%     |
| Synaptics        | 1         | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Validity Sensors VFS471 Fingerprint Reader | 1         | 50%     |
| Synaptics  WBDI                            | 1         | 50%     |

Chipcard Vendor
---------------

Chipcard module vendors

Zero info for selected period =(

Chipcard Model
--------------

Chipcard module models

Zero info for selected period =(

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 51        | 79.69%  |
| 1     | 11        | 17.19%  |
| 2     | 2         | 3.13%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Computers | Percent |
|--------------------|-----------|---------|
| Net/wireless       | 8         | 50%     |
| Graphics card      | 5         | 31.25%  |
| Fingerprint reader | 2         | 12.5%   |
| Network            | 1         | 6.25%   |

