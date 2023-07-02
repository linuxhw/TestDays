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

Total: 80

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| BigLinux 20.04            | 11        | 18.64%  |
| BigLinux 22.0.0           | 6         | 10.17%  |
| BigLinux 19.04            | 5         | 8.47%   |
| BigLinux 22.1.0           | 4         | 6.78%   |
| BigLinux 22.0.4           | 4         | 6.78%   |
| BigLinux 21.3.7           | 3         | 5.08%   |
| BigLinux 21.3.5           | 3         | 5.08%   |
| BigLinux 23.02.20         | 2         | 3.39%   |
| BigLinux 23.02.24         | 1         | 1.69%   |
| BigLinux 23.02.07         | 1         | 1.69%   |
| BigLinux 23.01.30         | 1         | 1.69%   |
| BigLinux 23.01.06         | 1         | 1.69%   |
| BigLinux 23.0.0           | 1         | 1.69%   |
| BigLinux 22.12.24         | 1         | 1.69%   |
| BigLinux 22.11.19         | 1         | 1.69%   |
| BigLinux 22.11.14         | 1         | 1.69%   |
| BigLinux 22.10.28         | 1         | 1.69%   |
| BigLinux 22.10.06         | 1         | 1.69%   |
| BigLinux 22.1.1           | 1         | 1.69%   |
| BigLinux 22.09.09         | 1         | 1.69%   |
| BigLinux 22.0.5           | 1         | 1.69%   |
| BigLinux 22.0.2           | 1         | 1.69%   |
| BigLinux 21.3.6           | 1         | 1.69%   |
| BigLinux 21.1.2           | 1         | 1.69%   |
| BigLinux 2023-06-23_06-21 | 1         | 1.69%   |
| BigLinux 2023-06-07_06-02 | 1         | 1.69%   |
| BigLinux 2023-06-03_00-55 | 1         | 1.69%   |
| BigLinux 2023-04-11_15-10 | 1         | 1.69%   |
| BigLinux 2023-03-17_19-23 | 1         | 1.69%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| BigLinux | 55        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Computers | Percent |
|-----------------------|-----------|---------|
| 6.1.12-1-MANJARO      | 4         | 6.56%   |
| 5.15.94-1-MANJARO     | 3         | 4.92%   |
| 5.15.85-1-MANJARO     | 3         | 4.92%   |
| 5.15.60-1-MANJARO     | 3         | 4.92%   |
| 6.2.12-1-MANJARO      | 2         | 3.28%   |
| 6.1.31-2-MANJARO      | 2         | 3.28%   |
| 6.1.23-1-MANJARO      | 2         | 3.28%   |
| 6.0.8-1-MANJARO       | 2         | 3.28%   |
| 5.8.0-43-generic      | 2         | 3.28%   |
| 5.4.0-37-generic      | 2         | 3.28%   |
| 5.2.8-xanmod8         | 2         | 3.28%   |
| 5.15.78-1-MANJARO     | 2         | 3.28%   |
| 5.15.71-1-MANJARO     | 2         | 3.28%   |
| 5.15.102-1-MANJARO    | 2         | 3.28%   |
| 6.3.5-1-MANJARO       | 1         | 1.64%   |
| 6.1.9-x64v1-xanmod1-1 | 1         | 1.64%   |
| 6.1.9-1-MANJARO       | 1         | 1.64%   |
| 6.1.26-1-MANJARO      | 1         | 1.64%   |
| 6.1.1-1-MANJARO       | 1         | 1.64%   |
| 5.9.3-xanmod1         | 1         | 1.64%   |
| 5.8.0-48-generic      | 1         | 1.64%   |
| 5.8.0-28-generic      | 1         | 1.64%   |
| 5.7.9-xanmod1         | 1         | 1.64%   |
| 5.6.6-xanmod1         | 1         | 1.64%   |
| 5.6.10-xanmod1        | 1         | 1.64%   |
| 5.4.0-48-generic      | 1         | 1.64%   |
| 5.4.0-33-generic      | 1         | 1.64%   |
| 5.4.0-31-generic      | 1         | 1.64%   |
| 5.3.6-xanmod5         | 1         | 1.64%   |
| 5.2.10-xanmod9        | 1         | 1.64%   |
| 5.19.13-1-MANJARO     | 1         | 1.64%   |
| 5.17.15-1-MANJARO     | 1         | 1.64%   |
| 5.16.11-1-BIGLINUX    | 1         | 1.64%   |
| 5.15.89-1-MANJARO     | 1         | 1.64%   |
| 5.15.76-1-MANJARO     | 1         | 1.64%   |
| 5.15.55-1-MANJARO     | 1         | 1.64%   |
| 5.15.114-2-MANJARO    | 1         | 1.64%   |
| 5.10.61-1-MANJARO     | 1         | 1.64%   |
| 5.10.136-1-MANJARO    | 1         | 1.64%   |
| 5.10.131-1-MANJARO    | 1         | 1.64%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 6.1.12   | 4         | 6.67%   |
| 5.8.0    | 4         | 6.67%   |
| 5.4.0    | 4         | 6.67%   |
| 5.15.94  | 3         | 5%      |
| 5.15.85  | 3         | 5%      |
| 5.15.60  | 3         | 5%      |
| 6.2.12   | 2         | 3.33%   |
| 6.1.9    | 2         | 3.33%   |
| 6.1.31   | 2         | 3.33%   |
| 6.1.23   | 2         | 3.33%   |
| 6.0.8    | 2         | 3.33%   |
| 5.2.8    | 2         | 3.33%   |
| 5.15.78  | 2         | 3.33%   |
| 5.15.71  | 2         | 3.33%   |
| 5.15.102 | 2         | 3.33%   |
| 6.3.5    | 1         | 1.67%   |
| 6.1.26   | 1         | 1.67%   |
| 6.1.1    | 1         | 1.67%   |
| 5.9.3    | 1         | 1.67%   |
| 5.7.9    | 1         | 1.67%   |
| 5.6.6    | 1         | 1.67%   |
| 5.6.10   | 1         | 1.67%   |
| 5.3.6    | 1         | 1.67%   |
| 5.2.10   | 1         | 1.67%   |
| 5.19.13  | 1         | 1.67%   |
| 5.17.15  | 1         | 1.67%   |
| 5.16.11  | 1         | 1.67%   |
| 5.15.89  | 1         | 1.67%   |
| 5.15.76  | 1         | 1.67%   |
| 5.15.55  | 1         | 1.67%   |
| 5.15.114 | 1         | 1.67%   |
| 5.10.61  | 1         | 1.67%   |
| 5.10.136 | 1         | 1.67%   |
| 5.10.131 | 1         | 1.67%   |
| 5.10.129 | 1         | 1.67%   |
| 5.10.12  | 1         | 1.67%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 17        | 30.91%  |
| 6.1     | 12        | 21.82%  |
| 5.8     | 4         | 7.27%   |
| 5.4     | 4         | 7.27%   |
| 5.2     | 3         | 5.45%   |
| 5.10    | 3         | 5.45%   |
| 6.2     | 2         | 3.64%   |
| 6.0     | 2         | 3.64%   |
| 6.3     | 1         | 1.82%   |
| 5.9     | 1         | 1.82%   |
| 5.7     | 1         | 1.82%   |
| 5.6     | 1         | 1.82%   |
| 5.3     | 1         | 1.82%   |
| 5.19    | 1         | 1.82%   |
| 5.17    | 1         | 1.82%   |
| 5.16    | 1         | 1.82%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 55        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| KDE5     | 46        | 83.64%  |
| KDE      | 6         | 10.91%  |
| Unknown  | 2         | 3.64%   |
| Cinnamon | 1         | 1.82%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 54        | 98.18%  |
| Unknown | 1         | 1.82%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 46        | 83.64%  |
| Unknown | 7         | 12.73%  |
| LXDM    | 1         | 1.82%   |
| LightDM | 1         | 1.82%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| pt_BR   | 34        | 61.82%  |
| en_US   | 7         | 12.73%  |
| pt_PT   | 2         | 3.64%   |
| es_MX   | 2         | 3.64%   |
| en_GB   | 2         | 3.64%   |
| Unknown | 2         | 3.64%   |
| fr_BE   | 1         | 1.82%   |
| fi_FI   | 1         | 1.82%   |
| es_ES   | 1         | 1.82%   |
| es_CR   | 1         | 1.82%   |
| es_AR   | 1         | 1.82%   |
| el_GR   | 1         | 1.82%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 36        | 64.29%  |
| BIOS | 20        | 35.71%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 48        | 87.27%  |
| Ext4    | 4         | 7.27%   |
| Overlay | 2         | 3.64%   |
| Unknown | 1         | 1.82%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 33        | 57.89%  |
| MBR     | 15        | 26.32%  |
| Unknown | 9         | 15.79%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 52        | 92.86%  |
| Yes       | 4         | 7.14%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 30        | 54.55%  |
| Yes       | 25        | 45.45%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 9         | 16.36%  |
| Intel                  | 6         | 10.91%  |
| ASUSTek Computer       | 6         | 10.91%  |
| Dell                   | 5         | 9.09%   |
| Acer                   | 5         | 9.09%   |
| Hewlett-Packard        | 3         | 5.45%   |
| Gigabyte Technology    | 3         | 5.45%   |
| MSI                    | 2         | 3.64%   |
| ASRock                 | 2         | 3.64%   |
| Toshiba                | 1         | 1.82%   |
| Sony                   | 1         | 1.82%   |
| Semp Toshiba           | 1         | 1.82%   |
| Samsung Electronics    | 1         | 1.82%   |
| Positivo               | 1         | 1.82%   |
| PCWare                 | 1         | 1.82%   |
| Multilaser             | 1         | 1.82%   |
| eMachines              | 1         | 1.82%   |
| ECS                    | 1         | 1.82%   |
| Clevo                  | 1         | 1.82%   |
| BESSTAR Tech           | 1         | 1.82%   |
| Avell High Performance | 1         | 1.82%   |
| Apple                  | 1         | 1.82%   |
| Alienware              | 1         | 1.82%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                         | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Intel H61                                                    | 2         | 3.64%   |
| ASRock 775Dual-VSTA                                          | 2         | 3.64%   |
| Toshiba Satellite S55-A                                      | 1         | 1.82%   |
| Sony VGN-NR230AE                                             | 1         | 1.82%   |
| Semp Toshiba STI                                             | 1         | 1.82%   |
| Samsung 300E5M/300E5L                                        | 1         | 1.82%   |
| Positivo C14RV01                                             | 1         | 1.82%   |
| PCWare IPX1800E2                                             | 1         | 1.82%   |
| Multilaser MLSH1H LINUX                                      | 1         | 1.82%   |
| MSI MS-7C95                                                  | 1         | 1.82%   |
| MSI MS-7C91                                                  | 1         | 1.82%   |
| Lenovo Yoga Slim 7 14ARE05 82A2                              | 1         | 1.82%   |
| Lenovo Yoga 520-14IKB 80YM                                   | 1         | 1.82%   |
| Lenovo ThinkPad T410 25379N2                                 | 1         | 1.82%   |
| Lenovo ThinkCentre M93p 10AB0010US                           | 1         | 1.82%   |
| Lenovo IdeaPad Z470                                          | 1         | 1.82%   |
| Lenovo IdeaPad S400 VIUS3                                    | 1         | 1.82%   |
| Lenovo IdeaPad 5 Pro 14ACN6 82L7                             | 1         | 1.82%   |
| Lenovo IdeaPad 300-15ISK 80RS                                | 1         | 1.82%   |
| Lenovo 63 90AT0002BR                                         | 1         | 1.82%   |
| Intel X79 (INTEL Xeon E5/Corei7 DMI2 - C600/C200 Cipset V307 | 1         | 1.82%   |
| Intel NUC11BTMi7                                             | 1         | 1.82%   |
| Intel H55                                                    | 1         | 1.82%   |
| Intel DH61WW AAG23116-203                                    | 1         | 1.82%   |
| HP Compaq Elite 8300 SFF                                     | 1         | 1.82%   |
| HP Compaq 8200 Elite SFF PC                                  | 1         | 1.82%   |
| HP 255 G7 Notebook PC                                        | 1         | 1.82%   |
| Gigabyte Z87-HD3                                             | 1         | 1.82%   |
| Gigabyte X399 DESIGNARE EX                                   | 1         | 1.82%   |
| Gigabyte B560M AORUS ELITE                                   | 1         | 1.82%   |
| eMachines EL1321                                             | 1         | 1.82%   |
| ECS H67H2-M2                                                 | 1         | 1.82%   |
| Dell System XPS L502X                                        | 1         | 1.82%   |
| Dell System Inspiron N7110                                   | 1         | 1.82%   |
| Dell Inspiron 7460                                           | 1         | 1.82%   |
| Dell Inspiron 3480                                           | 1         | 1.82%   |
| Dell G15 5520                                                | 1         | 1.82%   |
| Clevo W340EU                                                 | 1         | 1.82%   |
| BESSTAR Tech HM90                                            | 1         | 1.82%   |
| Avell High Performance STORM TWO                             | 1         | 1.82%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Lenovo IdeaPad               | 4         | 7.27%   |
| Lenovo Yoga                  | 2         | 3.64%   |
| Intel H61                    | 2         | 3.64%   |
| HP Compaq                    | 2         | 3.64%   |
| Dell System                  | 2         | 3.64%   |
| Dell Inspiron                | 2         | 3.64%   |
| ASUS TUF                     | 2         | 3.64%   |
| ASRock 775Dual-VSTA          | 2         | 3.64%   |
| Acer Aspire                  | 2         | 3.64%   |
| Toshiba Satellite            | 1         | 1.82%   |
| Sony VGN-NR230AE             | 1         | 1.82%   |
| Semp Toshiba STI             | 1         | 1.82%   |
| Samsung 300E5M               | 1         | 1.82%   |
| Positivo C14RV01             | 1         | 1.82%   |
| PCWare IPX1800E2             | 1         | 1.82%   |
| Multilaser MLSH1H            | 1         | 1.82%   |
| MSI MS-7C95                  | 1         | 1.82%   |
| MSI MS-7C91                  | 1         | 1.82%   |
| Lenovo ThinkPad              | 1         | 1.82%   |
| Lenovo ThinkCentre           | 1         | 1.82%   |
| Lenovo 63                    | 1         | 1.82%   |
| Intel X79                    | 1         | 1.82%   |
| Intel NUC11BTMi7             | 1         | 1.82%   |
| Intel H55                    | 1         | 1.82%   |
| Intel DH61WW                 | 1         | 1.82%   |
| HP 255                       | 1         | 1.82%   |
| Gigabyte Z87-HD3             | 1         | 1.82%   |
| Gigabyte X399                | 1         | 1.82%   |
| Gigabyte B560M               | 1         | 1.82%   |
| eMachines EL1321             | 1         | 1.82%   |
| ECS H67H2-M2                 | 1         | 1.82%   |
| Dell G15                     | 1         | 1.82%   |
| Clevo W340EU                 | 1         | 1.82%   |
| BESSTAR Tech HM90            | 1         | 1.82%   |
| Avell High Performance STORM | 1         | 1.82%   |
| ASUS X45U                    | 1         | 1.82%   |
| ASUS VivoBook                | 1         | 1.82%   |
| ASUS H110M-C                 | 1         | 1.82%   |
| ASUS All                     | 1         | 1.82%   |
| Apple MacBookPro9            | 1         | 1.82%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2017 | 8         | 14.55%  |
| 2021 | 7         | 12.73%  |
| 2013 | 6         | 10.91%  |
| 2012 | 5         | 9.09%   |
| 2011 | 5         | 9.09%   |
| 2020 | 4         | 7.27%   |
| 2018 | 4         | 7.27%   |
| 2022 | 3         | 5.45%   |
| 2014 | 3         | 5.45%   |
| 2009 | 3         | 5.45%   |
| 2019 | 2         | 3.64%   |
| 2016 | 2         | 3.64%   |
| 2006 | 2         | 3.64%   |
| 2007 | 1         | 1.82%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 28        | 50.91%  |
| Desktop     | 25        | 45.45%  |
| Convertible | 1         | 1.82%   |
| Mini pc     | 1         | 1.82%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 54        | 98.18%  |
| Enabled  | 1         | 1.82%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 55        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 12        | 21.43%  |
| 3.01-4.0    | 12        | 21.43%  |
| 16.01-24.0  | 9         | 16.07%  |
| 32.01-64.0  | 8         | 14.29%  |
| 8.01-16.0   | 8         | 14.29%  |
| 2.01-3.0    | 4         | 7.14%   |
| 1.01-2.0    | 2         | 3.57%   |
| 64.01-256.0 | 1         | 1.79%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 21        | 36.21%  |
| 2.01-3.0  | 18        | 31.03%  |
| 4.01-8.0  | 8         | 13.79%  |
| 3.01-4.0  | 4         | 6.9%    |
| 0.51-1.0  | 4         | 6.9%    |
| 8.01-16.0 | 2         | 3.45%   |
| 0.01-0.5  | 1         | 1.72%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 29        | 51.79%  |
| 2      | 13        | 23.21%  |
| 3      | 9         | 16.07%  |
| 6      | 2         | 3.57%   |
| 4      | 2         | 3.57%   |
| 0      | 1         | 1.79%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 35        | 63.64%  |
| Yes       | 20        | 36.36%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 52        | 94.55%  |
| No        | 3         | 5.45%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 42        | 76.36%  |
| No        | 13        | 23.64%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 32        | 58.18%  |
| No        | 23        | 41.82%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Computers | Percent |
|------------|-----------|---------|
| Brazil     | 37        | 67.27%  |
| UK         | 3         | 5.45%   |
| Greece     | 3         | 5.45%   |
| USA        | 2         | 3.64%   |
| Portugal   | 2         | 3.64%   |
| Mexico     | 2         | 3.64%   |
| Spain      | 1         | 1.82%   |
| Japan      | 1         | 1.82%   |
| Finland    | 1         | 1.82%   |
| Costa Rica | 1         | 1.82%   |
| Belgium    | 1         | 1.82%   |
| Argentina  | 1         | 1.82%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Sao Paulo              | 3         | 5.36%   |
| Rio de Janeiro         | 3         | 5.36%   |
| Brasília              | 3         | 5.36%   |
| Belo Horizonte         | 3         | 5.36%   |
| Thessaloniki           | 2         | 3.57%   |
| Sao Domingos do Capim  | 2         | 3.57%   |
| Curitiba               | 2         | 3.57%   |
| Castanhal              | 2         | 3.57%   |
| Vila Nova de Famalicao | 1         | 1.79%   |
| Tokyo                  | 1         | 1.79%   |
| Tlajomulco de Zuniga   | 1         | 1.79%   |
| The Villages           | 1         | 1.79%   |
| Sao Jose do Rio Preto  | 1         | 1.79%   |
| Sao Joaquim da Barra   | 1         | 1.79%   |
| Santo André           | 1         | 1.79%   |
| Santa Cruz de Tenerife | 1         | 1.79%   |
| San José              | 1         | 1.79%   |
| Salvador               | 1         | 1.79%   |
| Ribeirao Grande        | 1         | 1.79%   |
| Osasco                 | 1         | 1.79%   |
| Mirassol               | 1         | 1.79%   |
| Metepec                | 1         | 1.79%   |
| Maringá               | 1         | 1.79%   |
| Marataizes             | 1         | 1.79%   |
| Maidstone              | 1         | 1.79%   |
| Macapa                 | 1         | 1.79%   |
| Londrina               | 1         | 1.79%   |
| Joensuu                | 1         | 1.79%   |
| Guimaraes              | 1         | 1.79%   |
| Gavere                 | 1         | 1.79%   |
| Fresno                 | 1         | 1.79%   |
| Franca                 | 1         | 1.79%   |
| Fortaleza              | 1         | 1.79%   |
| Fernandopolis          | 1         | 1.79%   |
| El Palomar             | 1         | 1.79%   |
| Dumbarton              | 1         | 1.79%   |
| Domingos Martins       | 1         | 1.79%   |
| Cruz Alta              | 1         | 1.79%   |
| Colombo                | 1         | 1.79%   |
| Caruaru                | 1         | 1.79%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 16        | 22     | 18.6%   |
| Seagate                     | 14        | 23     | 16.28%  |
| Samsung Electronics         | 8         | 9      | 9.3%    |
| Hitachi                     | 5         | 5      | 5.81%   |
| China                       | 5         | 7      | 5.81%   |
| SanDisk                     | 4         | 4      | 4.65%   |
| KingSpec                    | 4         | 4      | 4.65%   |
| ADATA Technology            | 4         | 4      | 4.65%   |
| Toshiba                     | 3         | 3      | 3.49%   |
| Kingston                    | 3         | 6      | 3.49%   |
| XrayDisk                    | 2         | 2      | 2.33%   |
| PNY                         | 2         | 2      | 2.33%   |
| Micron/Crucial Technology   | 2         | 2      | 2.33%   |
| LITEON                      | 2         | 3      | 2.33%   |
| JMicron Technology          | 2         | 2      | 2.33%   |
| HGST                        | 2         | 2      | 2.33%   |
| Crucial                     | 2         | 2      | 2.33%   |
| Netac                       | 1         | 2      | 1.16%   |
| Kingston Technology Company | 1         | 1      | 1.16%   |
| Intel                       | 1         | 1      | 1.16%   |
| BHT                         | 1         | 1      | 1.16%   |
| Apacer                      | 1         | 1      | 1.16%   |
| A-DATA Technology           | 1         | 1      | 1.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 4         | 4.3%    |
| WDC WD10SPZX-21Z10T0 1TB                            | 3         | 3.23%   |
| Seagate ST500DM002-1BD142 500GB                     | 2         | 2.15%   |
| Seagate ST4000DM004-2CV104 4TB                      | 2         | 2.15%   |
| Micron/Crucial CT500P5SSD8 500GB                    | 2         | 2.15%   |
| Kingston SV300S37A240G 240GB SSD                    | 2         | 2.15%   |
| JMicron Tech 250GB                                  | 2         | 2.15%   |
| XrayDisk 512GB SSD                                  | 1         | 1.08%   |
| XrayDisk 120GB                                      | 1         | 1.08%   |
| WDC WD800AAJS-75M0A0 80GB                           | 1         | 1.08%   |
| WDC WD7500BPKX-75HPJT0 752GB                        | 1         | 1.08%   |
| WDC WD5000LPVX-75V0TT0 500GB                        | 1         | 1.08%   |
| WDC WD5000LPVT-08G33T1 500GB                        | 1         | 1.08%   |
| WDC WD5000LPCX-24VHAT0 500GB                        | 1         | 1.08%   |
| WDC WD5000AAKX-08U6AA0 500GB                        | 1         | 1.08%   |
| WDC WD40EZRX-00SPEB0 4TB                            | 1         | 1.08%   |
| WDC WD3200BPVT-00JJ5T0 320GB                        | 1         | 1.08%   |
| WDC WD3200AAKS-75L9A0 320GB                         | 1         | 1.08%   |
| WDC WD3200AAJS-56M0A0 320GB                         | 1         | 1.08%   |
| WDC WD1600AAJS-08L7A0 160GB                         | 1         | 1.08%   |
| WDC WD10SPZX-80Z10T2 1TB                            | 1         | 1.08%   |
| WDC WD10SPZX-75Z10T3 1TB                            | 1         | 1.08%   |
| WDC WD10EZEX-60WN4A0 1TB                            | 1         | 1.08%   |
| WDC WD10EZEX-00KUWA0 1TB                            | 1         | 1.08%   |
| WDC WD1001FALS-41Y6A1 1TB                           | 1         | 1.08%   |
| Toshiba MQ04ABF100 1TB                              | 1         | 1.08%   |
| Toshiba MQ01ABD050V -63 500GB                       | 1         | 1.08%   |
| Toshiba DT01ACA050 500GB                            | 1         | 1.08%   |
| Seagate ST9500325AS 500GB                           | 1         | 1.08%   |
| Seagate ST9100824AS 100GB                           | 1         | 1.08%   |
| Seagate ST8000VN0022-2EL112 8TB                     | 1         | 1.08%   |
| Seagate ST8000AS0002-1NA17Z 8TB                     | 1         | 1.08%   |
| Seagate ST3320613AS 320GB                           | 1         | 1.08%   |
| Seagate ST320LM001 HN-M320MBB 320GB                 | 1         | 1.08%   |
| Seagate ST32000542AS 2TB                            | 1         | 1.08%   |
| Seagate ST3160212SCE 160GB                          | 1         | 1.08%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 1.08%   |
| Seagate ST1000LM014-1EJ164 1TB                      | 1         | 1.08%   |
| Seagate ST1000DM010-2EP102 1TB                      | 1         | 1.08%   |
| Seagate Expansion HDD 8TB                           | 1         | 1.08%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 16        | 22     | 39.02%  |
| Seagate             | 14        | 23     | 34.15%  |
| Hitachi             | 5         | 5      | 12.2%   |
| Toshiba             | 3         | 3      | 7.32%   |
| HGST                | 2         | 2      | 4.88%   |
| Samsung Electronics | 1         | 1      | 2.44%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| China               | 5         | 7      | 18.52%  |
| KingSpec            | 4         | 4      | 14.81%  |
| Samsung Electronics | 3         | 4      | 11.11%  |
| Kingston            | 3         | 5      | 11.11%  |
| SanDisk             | 2         | 2      | 7.41%   |
| PNY                 | 2         | 2      | 7.41%   |
| LITEON              | 2         | 3      | 7.41%   |
| Crucial             | 2         | 2      | 7.41%   |
| XrayDisk            | 1         | 1      | 3.7%    |
| BHT                 | 1         | 1      | 3.7%    |
| Apacer              | 1         | 1      | 3.7%    |
| A-DATA Technology   | 1         | 1      | 3.7%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 36        | 56     | 45.57%  |
| SSD     | 25        | 33     | 31.65%  |
| NVMe    | 15        | 17     | 18.99%  |
| Unknown | 3         | 3      | 3.8%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 48        | 88     | 71.64%  |
| NVMe | 15        | 17     | 22.39%  |
| SAS  | 4         | 4      | 5.97%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 33        | 52     | 56.9%   |
| 0.51-1.0   | 18        | 24     | 31.03%  |
| 1.01-2.0   | 3         | 4      | 5.17%   |
| 3.01-4.0   | 2         | 6      | 3.45%   |
| 4.01-10.0  | 2         | 3      | 3.45%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 12        | 21.82%  |
| 1001-2000      | 12        | 21.82%  |
| 2001-3000      | 9         | 16.36%  |
| 101-250        | 9         | 16.36%  |
| 501-1000       | 6         | 10.91%  |
| More than 3000 | 5         | 9.09%   |
| 1-20           | 2         | 3.64%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 21-50          | 17        | 28.81%  |
| 51-100         | 13        | 22.03%  |
| 101-250        | 9         | 15.25%  |
| 251-500        | 6         | 10.17%  |
| 1-20           | 6         | 10.17%  |
| 501-1000       | 5         | 8.47%   |
| More than 3000 | 1         | 1.69%   |
| 2001-3000      | 1         | 1.69%   |
| 1001-2000      | 1         | 1.69%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                  | Computers | Drives | Percent |
|----------------------------------------|-----------|--------|---------|
| WDC WD800AAJS-75M0A0 80GB              | 1         | 1      | 7.14%   |
| WDC WD5000AAKX-08U6AA0 500GB           | 1         | 1      | 7.14%   |
| WDC WD3200BPVT-00JJ5T0 320GB           | 1         | 3      | 7.14%   |
| WDC WD1001FALS-41Y6A1 1TB              | 1         | 2      | 7.14%   |
| Seagate ST9100824AS 100GB              | 1         | 1      | 7.14%   |
| Seagate ST8000AS0002-1NA17Z 8TB        | 1         | 1      | 7.14%   |
| Seagate ST500DM002-1BD142 500GB        | 1         | 2      | 7.14%   |
| Seagate ST3320613AS 320GB              | 1         | 1      | 7.14%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 1         | 1      | 7.14%   |
| Hitachi HTS727575A9E364 752GB          | 1         | 1      | 7.14%   |
| Hitachi HTS545032A7E380 320GB          | 1         | 1      | 7.14%   |
| Hitachi HDS721050DLE630 500GB          | 1         | 1      | 7.14%   |
| China SATA SSD 240GB                   | 1         | 1      | 7.14%   |
| ADATA Technology SM2P32A8-512GC1 512GB | 1         | 1      | 7.14%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor           | Computers | Drives | Percent |
|------------------|-----------|--------|---------|
| Seagate          | 5         | 6      | 35.71%  |
| WDC              | 4         | 7      | 28.57%  |
| Hitachi          | 3         | 3      | 21.43%  |
| China            | 1         | 1      | 7.14%   |
| ADATA Technology | 1         | 1      | 7.14%   |

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
| HDD  | 11        | 16     | 84.62%  |
| NVMe | 1         | 1      | 7.69%   |
| SSD  | 1         | 1      | 7.69%   |

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
| Works    | 30        | 55     | 45.45%  |
| Detected | 22        | 35     | 33.33%  |
| Malfunc  | 13        | 18     | 19.7%   |
| Failed   | 1         | 1      | 1.52%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 39        | 59.09%  |
| AMD                         | 9         | 13.64%  |
| ADATA Technology            | 4         | 6.06%   |
| Samsung Electronics         | 3         | 4.55%   |
| VIA Technologies            | 2         | 3.03%   |
| SanDisk                     | 2         | 3.03%   |
| Micron/Crucial Technology   | 2         | 3.03%   |
| Kingston Technology Company | 2         | 3.03%   |
| Phison Electronics          | 1         | 1.52%   |
| Nvidia                      | 1         | 1.52%   |
| Netac Technology            | 1         | 1.52%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 6         | 8%      |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 5         | 6.67%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5         | 6.67%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 5         | 6.67%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 4         | 5.33%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4         | 5.33%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3         | 4%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 3         | 4%      |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 2         | 2.67%   |
| VIA VT8237A SATA 2-Port Controller                                                      | 2         | 2.67%   |
| Micron/Crucial NVMe Storage Controller                                                  | 2         | 2.67%   |
| Intel Tiger Lake SATA AHCI Controller                                                   | 2         | 2.67%   |
| AMD 500 Series Chipset SATA Controller                                                  | 2         | 2.67%   |
| ADATA A Non-Volatile memory controller                                                  | 2         | 2.67%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                                      | 1         | 1.33%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1         | 1.33%   |
| Phison E12 NVMe Controller                                                              | 1         | 1.33%   |
| Nvidia MCP61 SATA Controller                                                            | 1         | 1.33%   |
| Netac Non-Volatile memory controller                                                    | 1         | 1.33%   |
| Kingston Company OM3PDP3 NVMe SSD                                                       | 1         | 1.33%   |
| Kingston Company NVMe Controller                                                        | 1         | 1.33%   |
| Intel SSD 660P Series                                                                   | 1         | 1.33%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1         | 1.33%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1         | 1.33%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 1         | 1.33%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1         | 1.33%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 1         | 1.33%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 1         | 1.33%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 1         | 1.33%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1         | 1.33%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1         | 1.33%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1         | 1.33%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1         | 1.33%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 1         | 1.33%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1         | 1.33%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 1         | 1.33%   |
| AMD X399 Series Chipset SATA Controller                                                 | 1         | 1.33%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 1         | 1.33%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1         | 1.33%   |
| AMD 400 Series Chipset SATA Controller                                                  | 1         | 1.33%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 42        | 61.76%  |
| NVMe | 14        | 20.59%  |
| RAID | 6         | 8.82%   |
| IDE  | 6         | 8.82%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 43        | 78.18%  |
| AMD    | 12        | 21.82%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Pentium D CPU 3.00GHz                 | 2         | 3.64%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 2         | 3.64%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 3.64%   |
| Intel Xeon CPU E5-2420 v2 @ 2.20GHz         | 1         | 1.82%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1         | 1.82%   |
| Intel Pentium Dual CPU T2330 @ 1.60GHz      | 1         | 1.82%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 1         | 1.82%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 1         | 1.82%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 1.82%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1         | 1.82%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 1         | 1.82%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 1         | 1.82%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 1         | 1.82%   |
| Intel Core i7 CPU S 860 @ 2.53GHz           | 1         | 1.82%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 1         | 1.82%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 1         | 1.82%   |
| Intel Core i5-4570T CPU @ 2.90GHz           | 1         | 1.82%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 1         | 1.82%   |
| Intel Core i5-3337U CPU @ 1.80GHz           | 1         | 1.82%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 1         | 1.82%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 1         | 1.82%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 1         | 1.82%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 1         | 1.82%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 1         | 1.82%   |
| Intel Core i5-2300 CPU @ 2.80GHz            | 1         | 1.82%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 1         | 1.82%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 1         | 1.82%   |
| Intel Core i3-7100U CPU @ 2.40GHz           | 1         | 1.82%   |
| Intel Core i3-7020U CPU @ 2.30GHz           | 1         | 1.82%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 1         | 1.82%   |
| Intel Core i3-3250 CPU @ 3.50GHz            | 1         | 1.82%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 1         | 1.82%   |
| Intel Core i3-2375M CPU @ 1.50GHz           | 1         | 1.82%   |
| Intel Celeron CPU J1800 @ 2.41GHz           | 1         | 1.82%   |
| Intel Celeron CPU G530 @ 2.40GHz            | 1         | 1.82%   |
| Intel 12th Gen Core i7-12700H               | 1         | 1.82%   |
| Intel 12th Gen Core i5-12500H               | 1         | 1.82%   |
| Intel 11th Gen Core i7-11700B @ 3.20GHz     | 1         | 1.82%   |
| Intel 11th Gen Core i5-11400H @ 2.70GHz     | 1         | 1.82%   |
| Intel 11th Gen Core i5-11400F @ 2.60GHz     | 1         | 1.82%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 15        | 27.27%  |
| Intel Core i7           | 9         | 16.36%  |
| Intel Core i3           | 6         | 10.91%  |
| Other                   | 5         | 9.09%   |
| AMD Ryzen 5             | 5         | 9.09%   |
| Intel Pentium D         | 2         | 3.64%   |
| Intel Celeron           | 2         | 3.64%   |
| AMD Ryzen 7             | 2         | 3.64%   |
| Intel Xeon              | 1         | 1.82%   |
| Intel Pentium Dual-Core | 1         | 1.82%   |
| Intel Pentium Dual      | 1         | 1.82%   |
| Intel Pentium           | 1         | 1.82%   |
| AMD Ryzen Threadripper  | 1         | 1.82%   |
| AMD Ryzen 9             | 1         | 1.82%   |
| AMD C-70                | 1         | 1.82%   |
| AMD C-60                | 1         | 1.82%   |
| AMD Athlon              | 1         | 1.82%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 26        | 47.27%  |
| 4      | 14        | 25.45%  |
| 6      | 7         | 12.73%  |
| 8      | 4         | 7.27%   |
| 12     | 2         | 3.64%   |
| 14     | 1         | 1.82%   |
| 1      | 1         | 1.82%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 55        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 39        | 70.91%  |
| 1      | 16        | 29.09%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 54        | 98.18%  |
| Unknown        | 1         | 1.82%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x206a7    | 8         | 14.55%  |
| Unknown    | 6         | 10.91%  |
| 0x806e9    | 5         | 9.09%   |
| 0x306c3    | 4         | 7.27%   |
| 0x306a9    | 4         | 7.27%   |
| 0xf64      | 2         | 3.64%   |
| 0x906a3    | 2         | 3.64%   |
| 0x806d1    | 2         | 3.64%   |
| 0x506e3    | 2         | 3.64%   |
| 0x05000119 | 2         | 3.64%   |
| 0xa0671    | 1         | 1.82%   |
| 0x906ed    | 1         | 1.82%   |
| 0x806ec    | 1         | 1.82%   |
| 0x706e5    | 1         | 1.82%   |
| 0x6fd      | 1         | 1.82%   |
| 0x406e3    | 1         | 1.82%   |
| 0x306e4    | 1         | 1.82%   |
| 0x30678    | 1         | 1.82%   |
| 0x20652    | 1         | 1.82%   |
| 0x1067a    | 1         | 1.82%   |
| 0x0a50000d | 1         | 1.82%   |
| 0x0a201025 | 1         | 1.82%   |
| 0x08701021 | 1         | 1.82%   |
| 0x08600106 | 1         | 1.82%   |
| 0x08108109 | 1         | 1.82%   |
| 0x0810100b | 1         | 1.82%   |
| 0x0800820d | 1         | 1.82%   |
| 0x08001137 | 1         | 1.82%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| SandyBridge      | 8         | 14.55%  |
| KabyLake         | 8         | 14.55%  |
| IvyBridge        | 6         | 10.91%  |
| Haswell          | 5         | 9.09%   |
| Zen 2            | 3         | 5.45%   |
| Skylake          | 3         | 5.45%   |
| IceLake          | 3         | 5.45%   |
| Zen+             | 2         | 3.64%   |
| Zen 3            | 2         | 3.64%   |
| Zen              | 2         | 3.64%   |
| NetBurst         | 2         | 3.64%   |
| Bobcat           | 2         | 3.64%   |
| Alderlake Hybrid | 2         | 3.64%   |
| Westmere         | 1         | 1.82%   |
| Silvermont       | 1         | 1.82%   |
| Penryn           | 1         | 1.82%   |
| Nehalem          | 1         | 1.82%   |
| K8 Hammer        | 1         | 1.82%   |
| Core             | 1         | 1.82%   |
| Unknown          | 1         | 1.82%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 31        | 46.27%  |
| Nvidia | 22        | 32.84%  |
| AMD    | 14        | 20.9%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                       | 6         | 8.82%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 6         | 8.82%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 3         | 4.41%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2         | 2.94%   |
| Nvidia GM108M [GeForce 940MX]                                               | 2         | 2.94%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2         | 2.94%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 2         | 2.94%   |
| Intel Alder Lake-P Integrated Graphics Controller                           | 2         | 2.94%   |
| AMD Renoir                                                                  | 2         | 2.94%   |
| AMD Caicos PRO [Radeon HD 7450]                                             | 2         | 2.94%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 1         | 1.47%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1         | 1.47%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1         | 1.47%   |
| Nvidia TU106 [GeForce GTX 1650]                                             | 1         | 1.47%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 1         | 1.47%   |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                    | 1         | 1.47%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1         | 1.47%   |
| Nvidia GM108M [GeForce 920MX]                                               | 1         | 1.47%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 1         | 1.47%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1         | 1.47%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1         | 1.47%   |
| Nvidia GK106M [GeForce GTX 770M]                                            | 1         | 1.47%   |
| Nvidia GF108M [GeForce GT 540M]                                             | 1         | 1.47%   |
| Nvidia GA107BM [GeForce RTX 3050 Mobile]                                    | 1         | 1.47%   |
| Nvidia GA104 [Geforce RTX 3070 Ti Laptop GPU]                               | 1         | 1.47%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 1         | 1.47%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 1         | 1.47%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 1         | 1.47%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1         | 1.47%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 1         | 1.47%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 1         | 1.47%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)         | 1         | 1.47%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)           | 1         | 1.47%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                      | 1         | 1.47%   |
| Intel HD Graphics 510                                                       | 1         | 1.47%   |
| Intel Core Processor Integrated Graphics Controller                         | 1         | 1.47%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1         | 1.47%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 1         | 1.47%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 1         | 1.47%   |
| AMD Wrestler [Radeon HD 7290]                                               | 1         | 1.47%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 18        | 32.73%  |
| 1 x AMD        | 13        | 23.64%  |
| 1 x Nvidia     | 12        | 21.82%  |
| Intel + Nvidia | 10        | 18.18%  |
| 2 x Intel      | 1         | 1.82%   |
| Intel + AMD    | 1         | 1.82%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 38        | 69.09%  |
| Proprietary | 16        | 29.09%  |
| Unknown     | 1         | 1.82%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 28        | 50.91%  |
| 1.01-2.0   | 12        | 21.82%  |
| 0.01-0.5   | 5         | 9.09%   |
| 3.01-4.0   | 3         | 5.45%   |
| 7.01-8.0   | 2         | 3.64%   |
| 5.01-6.0   | 2         | 3.64%   |
| 0.51-1.0   | 2         | 3.64%   |
| 8.01-16.0  | 1         | 1.82%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 11        | 18.64%  |
| Goldstar                | 7         | 11.86%  |
| LG Display              | 6         | 10.17%  |
| Chimei Innolux          | 6         | 10.17%  |
| BOE                     | 6         | 10.17%  |
| AU Optronics            | 5         | 8.47%   |
| Unknown (XXX)           | 2         | 3.39%   |
| Philips                 | 2         | 3.39%   |
| Panasonic               | 2         | 3.39%   |
| AOC                     | 2         | 3.39%   |
| Positivo                | 1         | 1.69%   |
| NEC Computers           | 1         | 1.69%   |
| LG Electronics          | 1         | 1.69%   |
| Lenovo                  | 1         | 1.69%   |
| Dell                    | 1         | 1.69%   |
| CSO                     | 1         | 1.69%   |
| Chi Mei Optoelectronics | 1         | 1.69%   |
| BenQ                    | 1         | 1.69%   |
| ASUSTek Computer        | 1         | 1.69%   |
| Apple                   | 1         | 1.69%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SyncMaster SAM037A 1680x1050 433x271mm 20.1-inch    | 2         | 3.23%   |
| Panasonic TV MEIC10C 1920x540 697x392mm 31.5-inch                       | 2         | 3.23%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                 | 2         | 3.23%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch           | 1         | 1.61%   |
| Unknown (XXX) Beyond TV XXX2851 3840x2160 1209x680mm 54.6-inch          | 1         | 1.61%   |
| Samsung Electronics T22B300 SAM092D 1920x1080 477x268mm 21.5-inch       | 1         | 1.61%   |
| Samsung Electronics SyncMaster SAM05EB 1920x1080 597x336mm 27.0-inch    | 1         | 1.61%   |
| Samsung Electronics SyncMaster SAM0471 1360x768 344x194mm 15.5-inch     | 1         | 1.61%   |
| Samsung Electronics S24C450 SAM09CF 1920x1200 518x324mm 24.1-inch       | 1         | 1.61%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch    | 1         | 1.61%   |
| Samsung Electronics LCD Monitor SAM0FEF 3840x2160 1872x1053mm 84.6-inch | 1         | 1.61%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch    | 1         | 1.61%   |
| Samsung Electronics LCD Monitor SAM02C9 1360x768 885x498mm 40.0-inch    | 1         | 1.61%   |
| Samsung Electronics LCD Monitor C24F390 1920x1080                       | 1         | 1.61%   |
| Positivo FIT85X NON1801 1360x768 344x194mm 15.5-inch                    | 1         | 1.61%   |
| Philips PHL 221V8 PHLC211 1920x1080 477x268mm 21.5-inch                 | 1         | 1.61%   |
| Philips 237E4 PHLC0AD 1920x1080 509x286mm 23.0-inch                     | 1         | 1.61%   |
| NEC Computers LCD1770VX NEC6697 1280x960 338x270mm 17.0-inch            | 1         | 1.61%   |
| LG Electronics LCD Monitor LG FULL HD 3200x1080                         | 1         | 1.61%   |
| LG Electronics LCD Monitor LG FULL HD                                   | 1         | 1.61%   |
| LG Display LCD Monitor LGD04BD 1366x768 344x194mm 15.5-inch             | 1         | 1.61%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch            | 1         | 1.61%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch             | 1         | 1.61%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch             | 1         | 1.61%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch             | 1         | 1.61%   |
| LG Display LCD Monitor LGD02DA 1920x1080 382x215mm 17.3-inch            | 1         | 1.61%   |
| Lenovo LCD Monitor LEN4035 1280x800 303x190mm 14.1-inch                 | 1         | 1.61%   |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                     | 1         | 1.61%   |
| Goldstar ULTRAWIDE GSM5C0C 2560x1080 601x254mm 25.7-inch                | 1         | 1.61%   |
| Goldstar L1753T GSM4476 1280x1024 338x270mm 17.0-inch                   | 1         | 1.61%   |
| Goldstar HD 16 GSM3E92 1366x768 344x194mm 15.5-inch                     | 1         | 1.61%   |
| Goldstar 25UM58G GSM5B98 2560x1080 673x284mm 28.8-inch                  | 1         | 1.61%   |
| Goldstar 23EA53 GSM59A9 1920x1080 510x290mm 23.1-inch                   | 1         | 1.61%   |
| Dell LCD Monitor E170S 3200x1080                                        | 1         | 1.61%   |
| Dell LCD Monitor E170S                                                  | 1         | 1.61%   |
| CSO LCD Monitor CSO140C 2880x1800 302x188mm 14.0-inch                   | 1         | 1.61%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch        | 1         | 1.61%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch         | 1         | 1.61%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch         | 1         | 1.61%   |
| Chimei Innolux LCD Monitor CMN14C8 1920x1080 309x173mm 13.9-inch        | 1         | 1.61%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 17        | 28.81%  |
| 1366x768 (WXGA)    | 17        | 28.81%  |
| 2560x1080          | 4         | 6.78%   |
| 3840x2160 (4K)     | 3         | 5.08%   |
| 1360x768           | 3         | 5.08%   |
| 1920x540           | 2         | 3.39%   |
| 1680x1050 (WSXGA+) | 2         | 3.39%   |
| 1600x900 (HD+)     | 2         | 3.39%   |
| 1280x800 (WXGA)    | 2         | 3.39%   |
| 3200x1080          | 1         | 1.69%   |
| 2880x1800          | 1         | 1.69%   |
| 2560x1440 (QHD)    | 1         | 1.69%   |
| 1920x1200 (WUXGA)  | 1         | 1.69%   |
| 1280x960           | 1         | 1.69%   |
| 1280x1024 (SXGA)   | 1         | 1.69%   |
| Unknown            | 1         | 1.69%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 11        | 18.64%  |
| 14      | 8         | 13.56%  |
| 17      | 7         | 11.86%  |
| 13      | 5         | 8.47%   |
| 31      | 3         | 5.08%   |
| 23      | 3         | 5.08%   |
| 20      | 3         | 5.08%   |
| 18      | 3         | 5.08%   |
| Unknown | 3         | 5.08%   |
| 54      | 2         | 3.39%   |
| 34      | 2         | 3.39%   |
| 24      | 2         | 3.39%   |
| 21      | 2         | 3.39%   |
| 84      | 1         | 1.69%   |
| 40      | 1         | 1.69%   |
| 28      | 1         | 1.69%   |
| 27      | 1         | 1.69%   |
| 25      | 1         | 1.69%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 25        | 43.1%   |
| 401-500     | 8         | 13.79%  |
| 601-700     | 5         | 8.62%   |
| 501-600     | 5         | 8.62%   |
| 351-400     | 5         | 8.62%   |
| Unknown     | 3         | 5.17%   |
| 701-800     | 2         | 3.45%   |
| 1001-1500   | 2         | 3.45%   |
| 801-900     | 1         | 1.72%   |
| 201-300     | 1         | 1.72%   |
| 1501-2000   | 1         | 1.72%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 40        | 72.73%  |
| 16/10   | 6         | 10.91%  |
| 21/9    | 4         | 7.27%   |
| Unknown | 3         | 5.45%   |
| 5/4     | 2         | 3.64%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 13        | 22.41%  |
| 101-110        | 11        | 18.97%  |
| 201-250        | 6         | 10.34%  |
| 351-500        | 5         | 8.62%   |
| 141-150        | 5         | 8.62%   |
| 121-130        | 5         | 8.62%   |
| More than 1000 | 3         | 5.17%   |
| 151-200        | 3         | 5.17%   |
| Unknown        | 3         | 5.17%   |
| 251-300        | 2         | 3.45%   |
| 301-350        | 1         | 1.72%   |
| 501-1000       | 1         | 1.72%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 20        | 35.71%  |
| 101-120       | 19        | 33.93%  |
| 121-160       | 9         | 16.07%  |
| 1-50          | 3         | 5.36%   |
| Unknown       | 3         | 5.36%   |
| More than 240 | 1         | 1.79%   |
| 161-240       | 1         | 1.79%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 43        | 76.79%  |
| 2     | 11        | 19.64%  |
| 0     | 2         | 3.57%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 37        | 40.66%  |
| Intel                    | 19        | 20.88%  |
| Qualcomm Atheros         | 17        | 18.68%  |
| VIA Technologies         | 2         | 2.2%    |
| Ralink Technology        | 2         | 2.2%    |
| D-Link System            | 2         | 2.2%    |
| Broadcom                 | 2         | 2.2%    |
| TP-Link                  | 1         | 1.1%    |
| Samsung Electronics      | 1         | 1.1%    |
| Ralink                   | 1         | 1.1%    |
| Prolific Technology      | 1         | 1.1%    |
| MediaTek                 | 1         | 1.1%    |
| Marvell Technology Group | 1         | 1.1%    |
| JMicron Technology       | 1         | 1.1%    |
| D-Link                   | 1         | 1.1%    |
| Belkin Components        | 1         | 1.1%    |
| ASIX Electronics         | 1         | 1.1%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 21        | 19.81%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 9         | 8.49%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 6         | 5.66%   |
| Realtek RTL8125 2.5GbE Controller                                                     | 4         | 3.77%   |
| Realtek 802.11ac NIC                                                                  | 3         | 2.83%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 3         | 2.83%   |
| VIA VT6102/VT6103 [Rhine-II]                                                          | 2         | 1.89%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                 | 2         | 1.89%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 2         | 1.89%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 2         | 1.89%   |
| Intel Wi-Fi 6 AX200                                                                   | 2         | 1.89%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                      | 2         | 1.89%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 2         | 1.89%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                                       | 2         | 1.89%   |
| TP-Link Archer T4U ver.3                                                              | 1         | 0.94%   |
| Samsung Galaxy series, misc. (tethering mode)                                         | 1         | 0.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 1         | 0.94%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                       | 1         | 0.94%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                              | 1         | 0.94%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                                      | 1         | 0.94%   |
| Realtek 802.11n WLAN Adapter                                                          | 1         | 0.94%   |
| Ralink RT5370 Wireless Adapter                                                        | 1         | 0.94%   |
| Ralink MT7601U Wireless Adapter                                                       | 1         | 0.94%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                             | 1         | 0.94%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                             | 1         | 0.94%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                             | 1         | 0.94%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                             | 1         | 0.94%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                              | 1         | 0.94%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                            | 1         | 0.94%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 0.94%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 1         | 0.94%   |
| Prolific USB-Serial Controller                                                        | 1         | 0.94%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                               | 1         | 0.94%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                                  | 1         | 0.94%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                                | 1         | 0.94%   |
| Intel Wireless 8265 / 8275                                                            | 1         | 0.94%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 1         | 0.94%   |
| Intel Tiger Lake PCH CNVi WiFi                                                        | 1         | 0.94%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                       | 1         | 0.94%   |
| Intel I211 Gigabit Network Connection                                                 | 1         | 0.94%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 14        | 31.11%  |
| Qualcomm Atheros      | 13        | 28.89%  |
| Realtek Semiconductor | 9         | 20%     |
| Ralink Technology     | 2         | 4.44%   |
| Broadcom              | 2         | 4.44%   |
| TP-Link               | 1         | 2.22%   |
| Ralink                | 1         | 2.22%   |
| MediaTek              | 1         | 2.22%   |
| D-Link                | 1         | 2.22%   |
| Belkin Components     | 1         | 2.22%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                  | Computers | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                             | 6         | 13.04%  |
| Realtek 802.11ac NIC                                                                   | 3         | 6.52%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                             | 3         | 6.52%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                  | 2         | 4.35%   |
| Realtek RTL8188EE Wireless Network Adapter                                             | 2         | 4.35%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                         | 2         | 4.35%   |
| Intel Wi-Fi 6 AX200                                                                    | 2         | 4.35%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                       | 2         | 4.35%   |
| TP-Link Archer T4U ver.3                                                               | 1         | 2.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                               | 1         | 2.17%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                        | 1         | 2.17%   |
| Realtek 802.11n WLAN Adapter                                                           | 1         | 2.17%   |
| Ralink RT5370 Wireless Adapter                                                         | 1         | 2.17%   |
| Ralink MT7601U Wireless Adapter                                                        | 1         | 2.17%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                              | 1         | 2.17%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express)  | 1         | 2.17%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                | 1         | 2.17%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                | 1         | 2.17%   |
| Intel Wireless 8265 / 8275                                                             | 1         | 2.17%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                 | 1         | 2.17%   |
| Intel Tiger Lake PCH CNVi WiFi                                                         | 1         | 2.17%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                        | 1         | 2.17%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                       | 1         | 2.17%   |
| Intel Centrino Wireless-N 105                                                          | 1         | 2.17%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                          | 1         | 2.17%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                                          | 1         | 2.17%   |
| Intel Centrino Advanced-N 6200                                                         | 1         | 2.17%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                               | 1         | 2.17%   |
| D-Link DWA-171 AC600 DB Wireless Adapter(rev.A1) [Realtek RTL8811AU]                   | 1         | 2.17%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                     | 1         | 2.17%   |
| Broadcom BCM4331 802.11a/b/g/n                                                         | 1         | 2.17%   |
| Belkin Components F6D4050 N150 Enhanced Wireless Network Adapter v1000 [Ralink RT3070] | 1         | 2.17%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 34        | 59.65%  |
| Intel                    | 9         | 15.79%  |
| Qualcomm Atheros         | 5         | 8.77%   |
| VIA Technologies         | 2         | 3.51%   |
| D-Link System            | 2         | 3.51%   |
| Samsung Electronics      | 1         | 1.75%   |
| Marvell Technology Group | 1         | 1.75%   |
| JMicron Technology       | 1         | 1.75%   |
| Broadcom                 | 1         | 1.75%   |
| ASIX Electronics         | 1         | 1.75%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 21        | 35.59%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 15.25%  |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 6.78%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 2         | 3.39%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 3.39%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2         | 3.39%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.69%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.69%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 1.69%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.69%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.69%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 1.69%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.69%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.69%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 1         | 1.69%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 1.69%   |
| Intel I211 Gigabit Network Connection                             | 1         | 1.69%   |
| Intel Ethernet Controller I225-V                                  | 1         | 1.69%   |
| Intel Ethernet Controller I225-LM                                 | 1         | 1.69%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.69%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.69%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 1.69%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.69%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 1.69%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 1.69%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 52        | 54.74%  |
| WiFi     | 42        | 44.21%  |
| Modem    | 1         | 1.05%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 29        | 51.79%  |
| Ethernet | 27        | 48.21%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 33        | 60%     |
| 1     | 20        | 36.36%  |
| 3     | 2         | 3.64%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 35        | 63.64%  |
| Yes  | 20        | 36.36%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 12        | 37.5%   |
| Qualcomm Atheros Communications | 6         | 18.75%  |
| Cambridge Silicon Radio         | 4         | 12.5%   |
| Lite-On Technology              | 3         | 9.38%   |
| Realtek Semiconductor           | 2         | 6.25%   |
| MediaTek                        | 1         | 3.13%   |
| IMC Networks                    | 1         | 3.13%   |
| Foxconn / Hon Hai               | 1         | 3.13%   |
| Broadcom                        | 1         | 3.13%   |
| Apple                           | 1         | 3.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Qualcomm Atheros  Bluetooth Device                  | 4         | 12.5%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 12.5%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 9.38%   |
| Intel AX201 Bluetooth                               | 3         | 9.38%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 6.25%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 2         | 6.25%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 6.25%   |
| Intel AX200 Bluetooth                               | 2         | 6.25%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 3.13%   |
| Realtek Bluetooth Radio                             | 1         | 3.13%   |
| MediaTek Wireless_Device                            | 1         | 3.13%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 3.13%   |
| Intel Bluetooth wireless interface                  | 1         | 3.13%   |
| Intel AX210 Bluetooth                               | 1         | 3.13%   |
| IMC Networks BCM20702A0                             | 1         | 3.13%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 1         | 3.13%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 3.13%   |
| Apple Bluetooth USB Host Controller                 | 1         | 3.13%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 41        | 48.81%  |
| Nvidia                 | 18        | 21.43%  |
| AMD                    | 16        | 19.05%  |
| C-Media Electronics    | 3         | 3.57%   |
| Generalplus Technology | 2         | 2.38%   |
| Creative Labs          | 2         | 2.38%   |
| Roland                 | 1         | 1.19%   |
| Realtek Semiconductor  | 1         | 1.19%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 8         | 8.51%   |
| Intel Sunrise Point-LP HD Audio                                                   | 7         | 7.45%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 6         | 6.38%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 5         | 5.32%   |
| AMD Family 17h/19h HD Audio Controller                                            | 5         | 5.32%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 3         | 3.19%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 3         | 3.19%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 3         | 3.19%   |
| Nvidia TU106 High Definition Audio Controller                                     | 2         | 2.13%   |
| Nvidia GP108 High Definition Audio Controller                                     | 2         | 2.13%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 2         | 2.13%   |
| Nvidia GA104 High Definition Audio Controller                                     | 2         | 2.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 2         | 2.13%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                           | 2         | 2.13%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 2         | 2.13%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 2         | 2.13%   |
| Generalplus Technology USB Audio Device                                           | 2         | 2.13%   |
| Creative Labs CA0106/CA0111 [SB Live!/Audigy/X-Fi Series]                         | 2         | 2.13%   |
| AMD Wrestler HDMI Audio                                                           | 2         | 2.13%   |
| AMD Starship/Matisse HD Audio Controller                                          | 2         | 2.13%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 2         | 2.13%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 2         | 2.13%   |
| Roland QUAD-CAPTURE                                                               | 1         | 1.06%   |
| Realtek Semiconductor USB Audio                                                   | 1         | 1.06%   |
| Nvidia TU116 High Definition Audio Controller                                     | 1         | 1.06%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 1         | 1.06%   |
| Nvidia TU102 High Definition Audio Controller                                     | 1         | 1.06%   |
| Nvidia MCP61 High Definition Audio                                                | 1         | 1.06%   |
| Nvidia GP104 High Definition Audio Controller                                     | 1         | 1.06%   |
| Nvidia GM206 High Definition Audio Controller                                     | 1         | 1.06%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 1         | 1.06%   |
| Nvidia GK106 HDMI Audio Controller                                                | 1         | 1.06%   |
| Nvidia GF108 High Definition Audio Controller                                     | 1         | 1.06%   |
| Nvidia Audio device                                                               | 1         | 1.06%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 1         | 1.06%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                         | 1         | 1.06%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 1         | 1.06%   |
| Intel Cannon Lake PCH cAVS                                                        | 1         | 1.06%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 1         | 1.06%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 1         | 1.06%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 9         | 17.31%  |
| Unknown             | 8         | 15.38%  |
| Kingston            | 7         | 13.46%  |
| Smart               | 5         | 9.62%   |
| SK hynix            | 4         | 7.69%   |
| Micron Technology   | 4         | 7.69%   |
| Corsair             | 3         | 5.77%   |
| Teikon              | 2         | 3.85%   |
| Crucial             | 2         | 3.85%   |
| A-DATA Technology   | 2         | 3.85%   |
| Unknown             | 2         | 3.85%   |
| Ramaxel Technology  | 1         | 1.92%   |
| PLEXHD              | 1         | 1.92%   |
| Nanya Technology    | 1         | 1.92%   |
| G.Skill             | 1         | 1.92%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Unknown                                                   | 2         | 3.57%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s               | 1         | 1.79%   |
| Unknown RAM Module 8GB DIMM SDRAM                         | 1         | 1.79%   |
| Unknown RAM Module 512MB SODIMM DDR2                      | 1         | 1.79%   |
| Unknown RAM Module 4GB SODIMM DDR4 2133MT/s               | 1         | 1.79%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                 | 1         | 1.79%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s               | 1         | 1.79%   |
| Unknown RAM Module 2GB SODIMM DDR2                        | 1         | 1.79%   |
| Unknown RAM Module 2GB DIMM SDRAM                         | 1         | 1.79%   |
| Unknown RAM Module 2GB DIMM DDR2 266MT/s                  | 1         | 1.79%   |
| Teikon RAM TMT351S6EFR8A-PBHJ 4GB SODIMM DDR3 1600MT/s    | 1         | 1.79%   |
| Teikon RAM TMA81GS6AFR8N-UHSC 8GB SODIMM DDR4 2400MT/s    | 1         | 1.79%   |
| Smart RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s     | 1         | 1.79%   |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1333MT/s     | 1         | 1.79%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s     | 1         | 1.79%   |
| Smart RAM SH564128FH8N6TNSQG 4GB DIMM DDR3 1600MT/s       | 1         | 1.79%   |
| Smart RAM SF4641G8CKHIWDFSEG 8GB SODIMM DDR4 2133MT/s     | 1         | 1.79%   |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s     | 1         | 1.79%   |
| SK hynix RAM MMXIV 4096MB SODIMM DDR3 1333MT/s            | 1         | 1.79%   |
| SK hynix RAM MD4512NSE-CB3M2 00 4096MB DIMM DDR4 2400MT/s | 1         | 1.79%   |
| SK hynix RAM HMT41GU6MFR8C-PB 8GB DIMM DDR3 1600MT/s      | 1         | 1.79%   |
| SK hynix RAM HMCG66MEBSA092N 8GB SODIMM DDR5 4800MT/s     | 1         | 1.79%   |
| Samsung RAM Module 2GB Row Of Chips LPDDR3 1600MT/s       | 1         | 1.79%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s     | 1         | 1.79%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s     | 1         | 1.79%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s     | 1         | 1.79%   |
| Samsung RAM M471B5173EB0-YK0 4096MB SODIMM DDR3 1600MT/s  | 1         | 1.79%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s     | 1         | 1.79%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s     | 1         | 1.79%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s       | 1         | 1.79%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM 2200MT/s            | 1         | 1.79%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s   | 1         | 1.79%   |
| Ramaxel RAM RMT3170EB68F9W1600 4GB SODIMM DDR3 1600MT/s   | 1         | 1.79%   |
| PLEXHD RAM er 4GB DIMM DDR3 1600MT/s                      | 1         | 1.79%   |
| Nanya RAM Module 2GB DIMM DDR3 1333MT/s                   | 1         | 1.79%   |
| Micron RAM Module 4GB Row Of Chips LPDDR4 4266MT/s        | 1         | 1.79%   |
| Micron RAM Module 2GB SODIMM DDR3 1600MT/s                | 1         | 1.79%   |
| Micron RAM 36JSZF51272PZ 4GB DIMM DDR3 1600MT/s           | 1         | 1.79%   |
| Micron RAM 16ATF2G64HZ-2G1B1 16GB SODIMM DDR4 2133MT/s    | 1         | 1.79%   |
| Kingston RAM Module 4GB DIMM DDR3 1333MT/s                | 1         | 1.79%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR3   | 18        | 42.86%  |
| DDR4   | 15        | 35.71%  |
| SDRAM  | 3         | 7.14%   |
| DDR5   | 2         | 4.76%   |
| DDR2   | 2         | 4.76%   |
| LPDDR4 | 1         | 2.38%   |
| LPDDR3 | 1         | 2.38%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 23        | 54.76%  |
| DIMM         | 17        | 40.48%  |
| Row Of Chips | 2         | 4.76%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 16        | 32.65%  |
| 4096  | 15        | 30.61%  |
| 2048  | 10        | 20.41%  |
| 16384 | 4         | 8.16%   |
| 32768 | 2         | 4.08%   |
| 1024  | 1         | 2.04%   |
| 512   | 1         | 2.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 13        | 27.08%  |
| 3200    | 5         | 10.42%  |
| 2400    | 5         | 10.42%  |
| 1333    | 5         | 10.42%  |
| 2133    | 4         | 8.33%   |
| 2667    | 3         | 6.25%   |
| 1334    | 3         | 6.25%   |
| Unknown | 3         | 6.25%   |
| 4800    | 2         | 4.17%   |
| 4266    | 1         | 2.08%   |
| 2200    | 1         | 2.08%   |
| 1867    | 1         | 2.08%   |
| 1067    | 1         | 2.08%   |
| 266     | 1         | 2.08%   |

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
| Quanta                                 | 5         | 17.86%  |
| Chicony Electronics                    | 4         | 14.29%  |
| Sunplus Innovation Technology          | 3         | 10.71%  |
| Acer                                   | 3         | 10.71%  |
| Microdia                               | 2         | 7.14%   |
| Lenovo                                 | 2         | 7.14%   |
| Y Media                                | 1         | 3.57%   |
| Sonix Technology                       | 1         | 3.57%   |
| Silicon Motion                         | 1         | 3.57%   |
| Lite-On Technology                     | 1         | 3.57%   |
| Jieli Technology                       | 1         | 3.57%   |
| IMC Networks                           | 1         | 3.57%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 3.57%   |
| Bison Electronics                      | 1         | 3.57%   |
| Apple                                  | 1         | 3.57%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Quanta VGA WebCam                                | 2         | 7.14%   |
| Microdia Integrated_Webcam_HD                    | 2         | 7.14%   |
| Acer Lenovo EasyCamera                           | 2         | 7.14%   |
| Y Media USB Camera                               | 1         | 3.57%   |
| Sunplus Laptop_Integrated_Webcam_HD              | 1         | 3.57%   |
| Sunplus Laptop Integrated Webcam FHD             | 1         | 3.57%   |
| Sunplus FHD Camera Microphone                    | 1         | 3.57%   |
| Sonix USB2.0 HD UVC WebCam                       | 1         | 3.57%   |
| Silicon Motion Web Camera                        | 1         | 3.57%   |
| Quanta Laptop_Integrated_Webcam_2HDM             | 1         | 3.57%   |
| Quanta HD Webcam                                 | 1         | 3.57%   |
| Quanta HD User Facing                            | 1         | 3.57%   |
| Lite-On TOSHIBA Web Camera - HD                  | 1         | 3.57%   |
| Lenovo Integrated Webcam [R5U877]                | 1         | 3.57%   |
| Lenovo FHD Webcam Audio                          | 1         | 3.57%   |
| Jieli USB PHY 2.0                                | 1         | 3.57%   |
| IMC Networks Integrated Camera                   | 1         | 3.57%   |
| Chicony Lenovo EasyCamera                        | 1         | 3.57%   |
| Chicony Integrated Camera                        | 1         | 3.57%   |
| Chicony HD WebCam                                | 1         | 3.57%   |
| Chicony FHD Webcam                               | 1         | 3.57%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 1         | 3.57%   |
| Bison BisonCam, NB Pro                           | 1         | 3.57%   |
| Apple FaceTime HD Camera                         | 1         | 3.57%   |
| Acer EasyCamera                                  | 1         | 3.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor    | Computers | Percent |
|-----------|-----------|---------|
| Synaptics | 1         | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model           | Computers | Percent |
|-----------------|-----------|---------|
| Synaptics  WBDI | 1         | 100%    |

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
| 0     | 44        | 80%     |
| 1     | 9         | 16.36%  |
| 2     | 2         | 3.64%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Computers | Percent |
|--------------------|-----------|---------|
| Net/wireless       | 7         | 53.85%  |
| Graphics card      | 4         | 30.77%  |
| Network            | 1         | 7.69%   |
| Fingerprint reader | 1         | 7.69%   |

