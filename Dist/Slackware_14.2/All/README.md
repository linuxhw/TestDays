Slackware 14.2 - Tested Hardware & Statistics
---------------------------------------------

A project to collect tested hardware configurations for Slackware 14.2.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Slackware_14.2/Desktop/README.md) and [notebooks](/Dist/Slackware_14.2/Notebook/README.md).

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

| Vendor     | Model                       | Form-Factor | Probe                                                      | Date         |
|------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Acer       | Extensa 5220                | Notebook    | [30ca0c3efa](https://linux-hardware.org/?probe=30ca0c3efa) | Dec 06, 2022 |
| Gigabyte   | X570 AORUS MASTER           | Desktop     | [9bfc03d98e](https://linux-hardware.org/?probe=9bfc03d98e) | Aug 20, 2022 |
| HP         | Laptop 15-bs2xx             | Notebook    | [bf53c3c878](https://linux-hardware.org/?probe=bf53c3c878) | Jan 02, 2022 |
| HP         | 21B4 A01                    | Desktop     | [871b196cc2](https://linux-hardware.org/?probe=871b196cc2) | Nov 21, 2021 |
| HP         | 21B4 A01                    | Desktop     | [259232d98b](https://linux-hardware.org/?probe=259232d98b) | Nov 21, 2021 |
| Supermicro | X9DA7/E                     | Desktop     | [3fc1ef2b58](https://linux-hardware.org/?probe=3fc1ef2b58) | Nov 09, 2021 |
| Intel      | DZ77RE-75K AAG39010-302     | Desktop     | [069c508e80](https://linux-hardware.org/?probe=069c508e80) | Sep 25, 2021 |
| Shuttle    | NC03U                       | Desktop     | [c5f76c4400](https://linux-hardware.org/?probe=c5f76c4400) | Sep 22, 2021 |
| Toshiba    | PORTEGE Z30-A               | Notebook    | [13b9ce0773](https://linux-hardware.org/?probe=13b9ce0773) | Sep 22, 2021 |
| Dynabook   | PORTEGE X50-G               | Notebook    | [da8279a7a9](https://linux-hardware.org/?probe=da8279a7a9) | Sep 22, 2021 |
| HPE        | ProLiant MicroServer Gen... | Desktop     | [9ac798b737](https://linux-hardware.org/?probe=9ac798b737) | Aug 05, 2021 |
| HPE        | ProLiant MicroServer Gen... | Desktop     | [095745e5fb](https://linux-hardware.org/?probe=095745e5fb) | Jul 06, 2021 |
| HP         | 158A                        | Desktop     | [d612124939](https://linux-hardware.org/?probe=d612124939) | Jun 21, 2021 |
| ASRock     | H310CM-HDV                  | Desktop     | [3291e5d2de](https://linux-hardware.org/?probe=3291e5d2de) | Jun 19, 2021 |
| ASRock     | H87M Pro4                   | Desktop     | [8d4b7f121d](https://linux-hardware.org/?probe=8d4b7f121d) | Jun 02, 2021 |
| ASUSTek    | Pro WS X570-ACE             | Desktop     | [6e60025ac5](https://linux-hardware.org/?probe=6e60025ac5) | May 25, 2021 |
| ASUSTek    | PRIME X370-PRO              | Desktop     | [3e5f76719a](https://linux-hardware.org/?probe=3e5f76719a) | May 24, 2021 |
| ASUSTek    | PRIME X370-PRO              | Desktop     | [c75f9d5c0d](https://linux-hardware.org/?probe=c75f9d5c0d) | May 23, 2021 |
| Dell       | 0PTTT9 A00                  | Desktop     | [e5b81a0da1](https://linux-hardware.org/?probe=e5b81a0da1) | May 20, 2021 |
| AMI        | Aptio CRB                   | Mini pc     | [cabba2c402](https://linux-hardware.org/?probe=cabba2c402) | May 19, 2021 |
| Gigabyte   | N3160TN                     | Desktop     | [2fd537312f](https://linux-hardware.org/?probe=2fd537312f) | May 14, 2021 |
| MSI        | G31TM-P21                   | Desktop     | [91c11ae82e](https://linux-hardware.org/?probe=91c11ae82e) | May 07, 2021 |
| HP         | 15 Notebook PC              | Notebook    | [bec2fe2e78](https://linux-hardware.org/?probe=bec2fe2e78) | Mar 21, 2021 |
| Toshiba    | Satellite C660              | Notebook    | [5189fbc4c9](https://linux-hardware.org/?probe=5189fbc4c9) | Mar 10, 2021 |
| Foxconn    | 2ADA                        | Desktop     | [425d15a5ce](https://linux-hardware.org/?probe=425d15a5ce) | Mar 09, 2021 |
| Samsung    | 300E5M/300E5L               | Notebook    | [bda4ee984f](https://linux-hardware.org/?probe=bda4ee984f) | Mar 05, 2021 |
| Dell       | Latitude E5500              | Notebook    | [a8e17b79ce](https://linux-hardware.org/?probe=a8e17b79ce) | Feb 26, 2021 |
| HP         | Pavilion Notebook           | Notebook    | [45dfe3c2b1](https://linux-hardware.org/?probe=45dfe3c2b1) | Feb 24, 2021 |
| Lenovo     | ThinkPad L440 20ASS05K00    | Notebook    | [aecef5c789](https://linux-hardware.org/?probe=aecef5c789) | Jan 22, 2021 |
| Dell       | 0TP412                      | Desktop     | [f0e56aacff](https://linux-hardware.org/?probe=f0e56aacff) | Jan 05, 2021 |
| Lenovo     | ThinkPad L440 20ASS05K00    | Notebook    | [7a6a06bb55](https://linux-hardware.org/?probe=7a6a06bb55) | Jan 04, 2021 |
| Dell       | Precision M4600             | Notebook    | [71bb8e2e9a](https://linux-hardware.org/?probe=71bb8e2e9a) | Dec 28, 2020 |
| Lenovo     | ThinkPad L440 20ASS05K00    | Notebook    | [b330b2d38a](https://linux-hardware.org/?probe=b330b2d38a) | Nov 19, 2020 |
| NetGear    | ReadyDATA 5200              | Desktop     | [96607f4270](https://linux-hardware.org/?probe=96607f4270) | Nov 12, 2020 |
| MSI        | GL73 8RC                    | Notebook    | [44f82bfc01](https://linux-hardware.org/?probe=44f82bfc01) | Nov 09, 2020 |
| Lenovo     | ThinkPad L440 20ASS05K00    | Notebook    | [a4cb1ecf16](https://linux-hardware.org/?probe=a4cb1ecf16) | Nov 08, 2020 |
| HP         | 8523 A01                    | Mini pc     | [bab721d52e](https://linux-hardware.org/?probe=bab721d52e) | Oct 30, 2020 |
| ASRock     | Z390M-ITX/ac                | Desktop     | [06eb8afdbc](https://linux-hardware.org/?probe=06eb8afdbc) | Oct 19, 2020 |
| Samsung    | 300E5M/300E5L               | Notebook    | [270b65ced8](https://linux-hardware.org/?probe=270b65ced8) | Jul 24, 2020 |
| ASUSTek    | PRIME B450-PLUS             | Desktop     | [d42d44dd82](https://linux-hardware.org/?probe=d42d44dd82) | Jul 23, 2020 |
| ASUSTek    | PRIME B450-PLUS             | Desktop     | [888f105221](https://linux-hardware.org/?probe=888f105221) | Jul 23, 2020 |
| ASUSTek    | M5A97 R2.0                  | Desktop     | [2eb600bb96](https://linux-hardware.org/?probe=2eb600bb96) | Jul 10, 2020 |
| ASUSTek    | M5A97 R2.0                  | Desktop     | [232221bf45](https://linux-hardware.org/?probe=232221bf45) | Jul 10, 2020 |
| Notebook   | NL40_50CU                   | Notebook    | [941073da73](https://linux-hardware.org/?probe=941073da73) | Jun 27, 2020 |
| Lenovo     | V330-14ARR 81B1             | Notebook    | [5089cbcf84](https://linux-hardware.org/?probe=5089cbcf84) | Jun 24, 2020 |
| Lenovo     | V330-14ARR 81B1             | Notebook    | [cb63994f94](https://linux-hardware.org/?probe=cb63994f94) | Jun 22, 2020 |
| Notebook   | NL40_50CU                   | Notebook    | [9a1c09c6e1](https://linux-hardware.org/?probe=9a1c09c6e1) | Mar 28, 2020 |
| Notebook   | NL40_50CU                   | Notebook    | [bc5ed8dea4](https://linux-hardware.org/?probe=bc5ed8dea4) | Mar 24, 2020 |
| Notebook   | NL40_50CU                   | Notebook    | [ae7070b067](https://linux-hardware.org/?probe=ae7070b067) | Mar 21, 2020 |
| Notebook   | NL40_50CU                   | Notebook    | [320dada481](https://linux-hardware.org/?probe=320dada481) | Mar 20, 2020 |
| Toshiba    | Satellite P50-A-12Z         | Notebook    | [96927db16b](https://linux-hardware.org/?probe=96927db16b) | Mar 17, 2020 |
| Radxa      | ROCK Pi 4                   | Soc         | [abf599e14a](https://linux-hardware.org/?probe=abf599e14a) | Jan 27, 2020 |
| Huanan     | X79-8D VAA31                | Desktop     | [bbfc99d048](https://linux-hardware.org/?probe=bbfc99d048) | Jan 22, 2020 |
| Unknown    | Unknown                     | Soc         | [62347dfd8d](https://linux-hardware.org/?probe=62347dfd8d) | Jan 01, 2020 |
| Lenovo     | ThinkPad X1 Carbon 7th 2... | Notebook    | [afe3135216](https://linux-hardware.org/?probe=afe3135216) | Dec 10, 2019 |
| ASUSTek    | P53E                        | Notebook    | [e9dcced0f7](https://linux-hardware.org/?probe=e9dcced0f7) | Oct 28, 2019 |
| Lenovo     | ThinkPad T400 6474BV7       | Notebook    | [825bdb9fd0](https://linux-hardware.org/?probe=825bdb9fd0) | Oct 28, 2019 |
| ASUSTek    | 1000H                       | Notebook    | [50da35c0d0](https://linux-hardware.org/?probe=50da35c0d0) | Oct 28, 2019 |
| ASUSTek    | A68HM-PLUS                  | Desktop     | [505df04abc](https://linux-hardware.org/?probe=505df04abc) | Oct 27, 2019 |
| ASUSTek    | PRIME B350M-A               | Desktop     | [0b246f9623](https://linux-hardware.org/?probe=0b246f9623) | Oct 27, 2019 |
| Acer       | Aspire E1-572               | Notebook    | [0fe80f5758](https://linux-hardware.org/?probe=0fe80f5758) | Oct 23, 2019 |
| ASUSTek    | ROG STRIX X470-F GAMING     | Desktop     | [21d76cde28](https://linux-hardware.org/?probe=21d76cde28) | Oct 22, 2019 |
| ASUSTek    | VivoBook_ASUSLaptop X570... | Notebook    | [ecca7bced0](https://linux-hardware.org/?probe=ecca7bced0) | Oct 22, 2019 |
| ASUSTek    | Z97-A                       | Desktop     | [482c60ec21](https://linux-hardware.org/?probe=482c60ec21) | Oct 21, 2019 |
| Acer       | Swift SF314-52              | Notebook    | [05f880ecec](https://linux-hardware.org/?probe=05f880ecec) | Oct 21, 2019 |
| Lenovo     | ThinkPad P70 20ERCTO1WW     | Notebook    | [0ceeb50e5e](https://linux-hardware.org/?probe=0ceeb50e5e) | Oct 21, 2019 |
| Gigabyte   | M61SME-S2                   | Desktop     | [10469f1659](https://linux-hardware.org/?probe=10469f1659) | Oct 21, 2019 |
| Lenovo     | ThinkPad T450s 20BW000EU... | Notebook    | [41ca8d1a20](https://linux-hardware.org/?probe=41ca8d1a20) | Oct 21, 2019 |
| HP         | 2B35                        | Desktop     | [45c5e4afbe](https://linux-hardware.org/?probe=45c5e4afbe) | Oct 21, 2019 |
| ASUSTek    | VivoBook_ASUSLaptop X570... | Notebook    | [c2fd6acb71](https://linux-hardware.org/?probe=c2fd6acb71) | Oct 21, 2019 |
| Gigabyte   | 970A-DS3P                   | Desktop     | [70ea4f97bf](https://linux-hardware.org/?probe=70ea4f97bf) | Oct 21, 2019 |
| Dell       | Latitude E7270              | Notebook    | [859e021e2f](https://linux-hardware.org/?probe=859e021e2f) | Oct 20, 2019 |
| ASUSTek    | Maximus VII HERO            | Desktop     | [4751f76aa2](https://linux-hardware.org/?probe=4751f76aa2) | Oct 20, 2019 |
| ASUSTek    | Maximus VII RANGER          | Desktop     | [71121ccd6f](https://linux-hardware.org/?probe=71121ccd6f) | Oct 20, 2019 |
| Fujitsu    | LIFEBOOK A555               | Notebook    | [e0c6729d5b](https://linux-hardware.org/?probe=e0c6729d5b) | Oct 20, 2019 |
| ASUSTek    | P5QLD PRO                   | Desktop     | [dabc1ee203](https://linux-hardware.org/?probe=dabc1ee203) | Oct 20, 2019 |
| Lenovo     | ThinkPad T470 20HDCTO1WW    | Notebook    | [0f9287651d](https://linux-hardware.org/?probe=0f9287651d) | Jul 24, 2019 |
| Lenovo     | ThinkPad T470 20HDCTO1WW    | Notebook    | [67672ef038](https://linux-hardware.org/?probe=67672ef038) | Jul 23, 2019 |
| Gigabyte   | X150M-PRO ECC-CF            | Desktop     | [39987c5d8e](https://linux-hardware.org/?probe=39987c5d8e) | Oct 10, 2018 |
| Fujitsu    | LIFEBOOK A555               | Notebook    | [63c120aa28](https://linux-hardware.org/?probe=63c120aa28) | Aug 19, 2018 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Computers | Percent |
|----------------------|-----------|---------|
| 4.19.80              | 7         | 10.45%  |
| 5.10.28-Unraid       | 6         | 8.96%   |
| 4.4.190              | 4         | 5.97%   |
| 4.4.240              | 3         | 4.48%   |
| 5.3.7                | 2         | 2.99%   |
| 4.4.276              | 2         | 2.99%   |
| 5.7.0                | 1         | 1.49%   |
| 5.5.10               | 1         | 1.49%   |
| 5.4.77               | 1         | 1.49%   |
| 5.4.75               | 1         | 1.49%   |
| 5.4.62               | 1         | 1.49%   |
| 5.4.53-APRL          | 1         | 1.49%   |
| 5.4.50               | 1         | 1.49%   |
| 5.4.47               | 1         | 1.49%   |
| 5.4.43               | 1         | 1.49%   |
| 5.4.24toshiba-new    | 1         | 1.49%   |
| 5.4.2                | 1         | 1.49%   |
| 5.4.13               | 1         | 1.49%   |
| 5.4.12+              | 1         | 1.49%   |
| 5.4.0-rc2-vto        | 1         | 1.49%   |
| 5.2.2                | 1         | 1.49%   |
| 5.15.50-cwl          | 1         | 1.49%   |
| 5.13.0.a             | 1         | 1.49%   |
| 5.12.12              | 1         | 1.49%   |
| 5.10.44-slack64-host | 1         | 1.49%   |
| 5.10.40              | 1         | 1.49%   |
| 5.10.4               | 1         | 1.49%   |
| 5.10.3               | 1         | 1.49%   |
| 5.10.21              | 1         | 1.49%   |
| 5.10.19              | 1         | 1.49%   |
| 4.9.248.a            | 1         | 1.49%   |
| 4.9.118              | 1         | 1.49%   |
| 4.4.88               | 1         | 1.49%   |
| 4.4.261              | 1         | 1.49%   |
| 4.4.227              | 1         | 1.49%   |
| 4.4.206+             | 1         | 1.49%   |
| 4.4.202              | 1         | 1.49%   |
| 4.4.190-smp          | 1         | 1.49%   |
| 4.4.189              | 1         | 1.49%   |
| 4.4.14               | 1         | 1.49%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.19.80 | 7         | 10.45%  |
| 5.10.28 | 6         | 8.96%   |
| 4.4.190 | 5         | 7.46%   |
| 4.4.240 | 3         | 4.48%   |
| 5.3.7   | 2         | 2.99%   |
| 4.4.276 | 2         | 2.99%   |
| 5.7.0   | 1         | 1.49%   |
| 5.5.10  | 1         | 1.49%   |
| 5.4.77  | 1         | 1.49%   |
| 5.4.75  | 1         | 1.49%   |
| 5.4.62  | 1         | 1.49%   |
| 5.4.53  | 1         | 1.49%   |
| 5.4.50  | 1         | 1.49%   |
| 5.4.47  | 1         | 1.49%   |
| 5.4.43  | 1         | 1.49%   |
| 5.4.24  | 1         | 1.49%   |
| 5.4.2   | 1         | 1.49%   |
| 5.4.13  | 1         | 1.49%   |
| 5.4.12  | 1         | 1.49%   |
| 5.4.0   | 1         | 1.49%   |
| 5.2.2   | 1         | 1.49%   |
| 5.15.50 | 1         | 1.49%   |
| 5.13.0  | 1         | 1.49%   |
| 5.12.12 | 1         | 1.49%   |
| 5.10.44 | 1         | 1.49%   |
| 5.10.40 | 1         | 1.49%   |
| 5.10.4  | 1         | 1.49%   |
| 5.10.3  | 1         | 1.49%   |
| 5.10.21 | 1         | 1.49%   |
| 5.10.19 | 1         | 1.49%   |
| 4.9.248 | 1         | 1.49%   |
| 4.9.118 | 1         | 1.49%   |
| 4.4.88  | 1         | 1.49%   |
| 4.4.261 | 1         | 1.49%   |
| 4.4.227 | 1         | 1.49%   |
| 4.4.206 | 1         | 1.49%   |
| 4.4.202 | 1         | 1.49%   |
| 4.4.189 | 1         | 1.49%   |
| 4.4.14  | 1         | 1.49%   |
| 4.20.11 | 1         | 1.49%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.4     | 17        | 25.37%  |
| 4.19    | 14        | 20.9%   |
| 5.4     | 12        | 17.91%  |
| 5.10    | 12        | 17.91%  |
| 5.3     | 2         | 2.99%   |
| 4.9     | 2         | 2.99%   |
| 5.7     | 1         | 1.49%   |
| 5.5     | 1         | 1.49%   |
| 5.2     | 1         | 1.49%   |
| 5.15    | 1         | 1.49%   |
| 5.13    | 1         | 1.49%   |
| 5.12    | 1         | 1.49%   |
| 4.20    | 1         | 1.49%   |
| 4.16    | 1         | 1.49%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 60        | 95.24%  |
| aarch64 | 2         | 3.17%   |
| i686    | 1         | 1.59%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Unknown       | 34        | 53.13%  |
| XFCE          | 20        | 31.25%  |
| KDE           | 4         | 6.25%   |
| KDE5          | 2         | 3.13%   |
| MATE          | 1         | 1.56%   |
| LXQt          | 1         | 1.56%   |
| fvwm          | 1         | 1.56%   |
| Enlightenment | 1         | 1.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 50        | 79.37%  |
| Unknown | 8         | 12.7%   |
| Tty     | 4         | 6.35%   |
| Wayland | 1         | 1.59%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 36        | 56.25%  |
| XDM     | 21        | 32.81%  |
| SDDM    | 5         | 7.81%   |
| SLiM    | 2         | 3.13%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 31        | 49.21%  |
| en_US   | 23        | 36.51%  |
| ru_RU   | 2         | 3.17%   |
| pt_BR   | 1         | 1.59%   |
| pl_PL   | 1         | 1.59%   |
| it_IT   | 1         | 1.59%   |
| fr_FR   | 1         | 1.59%   |
| en_GB   | 1         | 1.59%   |
| en_AU   | 1         | 1.59%   |
| C       | 1         | 1.59%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 41        | 64.06%  |
| EFI  | 23        | 35.94%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 48        | 76.19%  |
| Btrfs    | 8         | 12.7%   |
| Rootfs   | 3         | 4.76%   |
| Xfs      | 2         | 3.17%   |
| Reiserfs | 1         | 1.59%   |
| Jfs      | 1         | 1.59%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 38        | 59.38%  |
| MBR     | 23        | 35.94%  |
| Unknown | 3         | 4.69%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 37        | 57.81%  |
| Yes       | 27        | 42.19%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 44        | 69.84%  |
| Yes       | 19        | 30.16%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 14        | 22.22%  |
| Lenovo              | 7         | 11.11%  |
| Hewlett-Packard     | 7         | 11.11%  |
| Gigabyte Technology | 5         | 7.94%   |
| Dell                | 5         | 7.94%   |
| Toshiba             | 3         | 4.76%   |
| ASRock              | 3         | 4.76%   |
| Acer                | 3         | 4.76%   |
| MSI                 | 2         | 3.17%   |
| Supermicro          | 1         | 1.59%   |
| Shuttle             | 1         | 1.59%   |
| Samsung Electronics | 1         | 1.59%   |
| Radxa               | 1         | 1.59%   |
| Notebook            | 1         | 1.59%   |
| NetGear             | 1         | 1.59%   |
| Intel               | 1         | 1.59%   |
| Huanan              | 1         | 1.59%   |
| HPE                 | 1         | 1.59%   |
| Fujitsu             | 1         | 1.59%   |
| Foxconn             | 1         | 1.59%   |
| Dynabook            | 1         | 1.59%   |
| AMI                 | 1         | 1.59%   |
| Unknown             | 1         | 1.59%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| ASUS All Series                          | 3         | 4.76%   |
| Toshiba Satellite P50-A-12Z              | 1         | 1.59%   |
| Toshiba Satellite C660                   | 1         | 1.59%   |
| Toshiba PORTEGE Z30-A                    | 1         | 1.59%   |
| Supermicro X9DA7/E                       | 1         | 1.59%   |
| Shuttle NC03U                            | 1         | 1.59%   |
| Samsung 300E5M/300E5L                    | 1         | 1.59%   |
| Radxa ROCK Pi 4                          | 1         | 1.59%   |
| Notebook NL40_50CU                       | 1         | 1.59%   |
| NetGear ReadyDATA 5200                   | 1         | 1.59%   |
| MSI MS-7529                              | 1         | 1.59%   |
| MSI GL73 8RC                             | 1         | 1.59%   |
| Lenovo V330-14ARR 81B1                   | 1         | 1.59%   |
| Lenovo ThinkPad X1 Carbon 7th 20R10015US | 1         | 1.59%   |
| Lenovo ThinkPad T470 20HDCTO1WW          | 1         | 1.59%   |
| Lenovo ThinkPad T450s 20BW000EUS         | 1         | 1.59%   |
| Lenovo ThinkPad T400 6474BV7             | 1         | 1.59%   |
| Lenovo ThinkPad P70 20ERCTO1WW           | 1         | 1.59%   |
| Lenovo ThinkPad L440 20ASS05K00          | 1         | 1.59%   |
| Intel DZ77RE-75K AAG39010-302            | 1         | 1.59%   |
| Huanan X79-8D VAA31                      | 1         | 1.59%   |
| HPE ProLiant MicroServer Gen10 Plus      | 1         | 1.59%   |
| HP Z620 Workstation                      | 1         | 1.59%   |
| HP t640 Thin Client                      | 1         | 1.59%   |
| HP t620 Quad Core TC                     | 1         | 1.59%   |
| HP Pavilion Notebook                     | 1         | 1.59%   |
| HP Laptop 15-bs2xx                       | 1         | 1.59%   |
| HP 500-515na                             | 1         | 1.59%   |
| HP 15 Notebook PC                        | 1         | 1.59%   |
| Gigabyte X570 AORUS MASTER               | 1         | 1.59%   |
| Gigabyte X150M-PRO ECC                   | 1         | 1.59%   |
| Gigabyte N3160TN                         | 1         | 1.59%   |
| Gigabyte M61SME-S2                       | 1         | 1.59%   |
| Gigabyte 970A-DS3P                       | 1         | 1.59%   |
| Fujitsu LIFEBOOK A555                    | 1         | 1.59%   |
| Foxconn p6-2390                          | 1         | 1.59%   |
| Dynabook PORTEGE X50-G                   | 1         | 1.59%   |
| Dell Precision WorkStation T3400         | 1         | 1.59%   |
| Dell Precision T3600                     | 1         | 1.59%   |
| Dell Precision M4600                     | 1         | 1.59%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 6         | 9.52%   |
| Dell Precision     | 3         | 4.76%   |
| ASUS PRIME         | 3         | 4.76%   |
| ASUS All           | 3         | 4.76%   |
| Toshiba Satellite  | 2         | 3.17%   |
| Dell Latitude      | 2         | 3.17%   |
| Toshiba PORTEGE    | 1         | 1.59%   |
| Supermicro X9DA7   | 1         | 1.59%   |
| Shuttle NC03U      | 1         | 1.59%   |
| Samsung 300E5M     | 1         | 1.59%   |
| Radxa ROCK         | 1         | 1.59%   |
| Notebook NL40      | 1         | 1.59%   |
| NetGear ReadyDATA  | 1         | 1.59%   |
| MSI MS-7529        | 1         | 1.59%   |
| MSI GL73           | 1         | 1.59%   |
| Lenovo V330-14ARR  | 1         | 1.59%   |
| Intel DZ77RE-75K   | 1         | 1.59%   |
| Huanan X79-8D      | 1         | 1.59%   |
| HPE ProLiant       | 1         | 1.59%   |
| HP Z620            | 1         | 1.59%   |
| HP t640            | 1         | 1.59%   |
| HP t620            | 1         | 1.59%   |
| HP Pavilion        | 1         | 1.59%   |
| HP Laptop          | 1         | 1.59%   |
| HP 500-515na       | 1         | 1.59%   |
| HP 15              | 1         | 1.59%   |
| Gigabyte X570      | 1         | 1.59%   |
| Gigabyte X150M-PRO | 1         | 1.59%   |
| Gigabyte N3160TN   | 1         | 1.59%   |
| Gigabyte M61SME-S2 | 1         | 1.59%   |
| Gigabyte 970A-DS3P | 1         | 1.59%   |
| Fujitsu LIFEBOOK   | 1         | 1.59%   |
| Foxconn p6-2390    | 1         | 1.59%   |
| Dynabook PORTEGE   | 1         | 1.59%   |
| ASUS VivoBook      | 1         | 1.59%   |
| ASUS ROG           | 1         | 1.59%   |
| ASUS Pro           | 1         | 1.59%   |
| ASUS P5QLD         | 1         | 1.59%   |
| ASUS P53E          | 1         | 1.59%   |
| ASUS M5A97         | 1         | 1.59%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 10        | 15.87%  |
| 2017    | 7         | 11.11%  |
| 2018    | 6         | 9.52%   |
| 2015    | 6         | 9.52%   |
| 2014    | 6         | 9.52%   |
| 2016    | 5         | 7.94%   |
| 2012    | 4         | 6.35%   |
| 2008    | 4         | 6.35%   |
| 2013    | 3         | 4.76%   |
| 2011    | 3         | 4.76%   |
| 2020    | 2         | 3.17%   |
| 2009    | 2         | 3.17%   |
| 2007    | 2         | 3.17%   |
| Unknown | 2         | 3.17%   |
| 2010    | 1         | 1.59%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 32        | 50.79%  |
| Notebook       | 27        | 42.86%  |
| System on chip | 2         | 3.17%   |
| Mini pc        | 2         | 3.17%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 63        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 62        | 98.41%  |
| Yes  | 1         | 1.59%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 13        | 20.63%  |
| 4.01-8.0    | 12        | 19.05%  |
| 16.01-24.0  | 12        | 19.05%  |
| 3.01-4.0    | 11        | 17.46%  |
| 32.01-64.0  | 6         | 9.52%   |
| 64.01-256.0 | 4         | 6.35%   |
| 24.01-32.0  | 2         | 3.17%   |
| 1.01-2.0    | 2         | 3.17%   |
| 0.51-1.0    | 1         | 1.59%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 23        | 35.38%  |
| 2.01-3.0    | 12        | 18.46%  |
| 3.01-4.0    | 10        | 15.38%  |
| 4.01-8.0    | 7         | 10.77%  |
| 8.01-16.0   | 4         | 6.15%   |
| 0.01-0.5    | 3         | 4.62%   |
| 24.01-32.0  | 2         | 3.08%   |
| 0.51-1.0    | 2         | 3.08%   |
| 64.01-256.0 | 1         | 1.54%   |
| 16.01-24.0  | 1         | 1.54%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 30        | 46.88%  |
| 2      | 11        | 17.19%  |
| 3      | 7         | 10.94%  |
| 4      | 5         | 7.81%   |
| 5      | 4         | 6.25%   |
| 6      | 2         | 3.13%   |
| 0      | 2         | 3.13%   |
| 13     | 1         | 1.56%   |
| 8      | 1         | 1.56%   |
| 7      | 1         | 1.56%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 37        | 58.73%  |
| Yes       | 26        | 41.27%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 59        | 93.65%  |
| No        | 4         | 6.35%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 38        | 60.32%  |
| No        | 25        | 39.68%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 34        | 53.97%  |
| No        | 29        | 46.03%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 14        | 22.22%  |
| UK          | 8         | 12.7%   |
| Russia      | 5         | 7.94%   |
| Germany     | 5         | 7.94%   |
| Portugal    | 4         | 6.35%   |
| India       | 4         | 6.35%   |
| Canada      | 4         | 6.35%   |
| Sweden      | 3         | 4.76%   |
| France      | 3         | 4.76%   |
| Poland      | 2         | 3.17%   |
| Italy       | 2         | 3.17%   |
| Brazil      | 2         | 3.17%   |
| Spain       | 1         | 1.59%   |
| Philippines | 1         | 1.59%   |
| Hong Kong   | 1         | 1.59%   |
| Finland     | 1         | 1.59%   |
| Chile       | 1         | 1.59%   |
| Bulgaria    | 1         | 1.59%   |
| Australia   | 1         | 1.59%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Yekaterinburg          | 3         | 4.62%   |
| Paris                  | 3         | 4.62%   |
| Lisbon                 | 3         | 4.62%   |
| Warsaw                 | 2         | 3.08%   |
| New Delhi              | 2         | 3.08%   |
| Carrollton             | 2         | 3.08%   |
| Barry                  | 2         | 3.08%   |
| Barrie                 | 2         | 3.08%   |
| Wokingham              | 1         | 1.54%   |
| Winnipeg               | 1         | 1.54%   |
| Weilheim               | 1         | 1.54%   |
| Voskresensk            | 1         | 1.54%   |
| Visconde do Rio Branco | 1         | 1.54%   |
| Tiffin                 | 1         | 1.54%   |
| Stockholm              | 1         | 1.54%   |
| St Louis               | 1         | 1.54%   |
| Springfield            | 1         | 1.54%   |
| Southend-on-Sea        | 1         | 1.54%   |
| Shrewsbury             | 1         | 1.54%   |
| Roknaes                | 1         | 1.54%   |
| Redding                | 1         | 1.54%   |
| Puente Alto            | 1         | 1.54%   |
| Plovdiv                | 1         | 1.54%   |
| Pinhal Novo            | 1         | 1.54%   |
| Pesaro                 | 1         | 1.54%   |
| Pasay                  | 1         | 1.54%   |
| Palma                  | 1         | 1.54%   |
| Ottawa                 | 1         | 1.54%   |
| Oldham                 | 1         | 1.54%   |
| Northport              | 1         | 1.54%   |
| Naples                 | 1         | 1.54%   |
| Milwaukee              | 1         | 1.54%   |
| Milan                  | 1         | 1.54%   |
| Mason                  | 1         | 1.54%   |
| Lins                   | 1         | 1.54%   |
| Lexington              | 1         | 1.54%   |
| Kstovo                 | 1         | 1.54%   |
| Kowloon                | 1         | 1.54%   |
| Koblenz                | 1         | 1.54%   |
| Jaipur                 | 1         | 1.54%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 20        | 44     | 20.62%  |
| Samsung Electronics | 17        | 28     | 17.53%  |
| Seagate             | 15        | 32     | 15.46%  |
| Toshiba             | 7         | 13     | 7.22%   |
| Kingston            | 5         | 5      | 5.15%   |
| Unknown             | 4         | 4      | 4.12%   |
| Crucial             | 4         | 5      | 4.12%   |
| Intel               | 3         | 3      | 3.09%   |
| Hitachi             | 3         | 3      | 3.09%   |
| A-DATA Technology   | 3         | 3      | 3.09%   |
| SanDisk             | 2         | 2      | 2.06%   |
| HGST                | 2         | 2      | 2.06%   |
| TO Exter            | 1         | 1      | 1.03%   |
| Team                | 1         | 1      | 1.03%   |
| SK hynix            | 1         | 1      | 1.03%   |
| Patriot             | 1         | 2      | 1.03%   |
| Netac               | 1         | 1      | 1.03%   |
| Micron Technology   | 1         | 1      | 1.03%   |
| Maxtor              | 1         | 1      | 1.03%   |
| Gigabyte Technology | 1         | 1      | 1.03%   |
| Fujitsu             | 1         | 1      | 1.03%   |
| Dogfish             | 1         | 1      | 1.03%   |
| China               | 1         | 2      | 1.03%   |
| Apple               | 1         | 2      | 1.03%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| WDC WD1003FZEX-00MK2A0 1TB           | 2         | 1.61%   |
| Toshiba MQ01ABD100 1TB               | 2         | 1.61%   |
| Seagate ST500DM002-1BD142 500GB      | 2         | 1.61%   |
| Seagate ST4000VN008-2DR166 4TB       | 2         | 1.61%   |
| Seagate ST31000524AS 1TB             | 2         | 1.61%   |
| Kingston SA400S37240G 240GB SSD      | 2         | 1.61%   |
| WDC WDS100T2B0C-00PXH0 1TB           | 1         | 0.81%   |
| WDC WD5000LPCX-60VHAT1 500GB         | 1         | 0.81%   |
| WDC WD5000BPVT-2 500GB               | 1         | 0.81%   |
| WDC WD5000BPKX-60HPJT0 500GB         | 1         | 0.81%   |
| WDC WD5000AAKX-00ERMA0 500GB         | 1         | 0.81%   |
| WDC WD5000AAKS-00V0A0 500GB          | 1         | 0.81%   |
| WDC WD5000AAKS-00A7B2 500GB          | 1         | 0.81%   |
| WDC WD40EFRX-68WT0N0 4TB             | 1         | 0.81%   |
| WDC WD40EFRX-68N32N0 4TB             | 1         | 0.81%   |
| WDC WD30EZRX-00SPEB0 3TB             | 1         | 0.81%   |
| WDC WD30EZRX-00M                     | 1         | 0.81%   |
| WDC WD30EFRX-68EUZN0 3TB             | 1         | 0.81%   |
| WDC WD30EFRX-68AX9N0 3TB             | 1         | 0.81%   |
| WDC WD2003FZEX-00Z4SA0 2TB           | 1         | 0.81%   |
| WDC WD2003FZEX-0 2TB                 | 1         | 0.81%   |
| WDC WD1600AAJS-00PSA0 160GB          | 1         | 0.81%   |
| WDC WD120EDAZ-11F3RA0 12TB           | 1         | 0.81%   |
| WDC WD10JPVX-35JC3T0 1TB             | 1         | 0.81%   |
| WDC WD10JPVX-16JC3T3 1TB             | 1         | 0.81%   |
| WDC WD10JPLX-00MBPT0 1TB             | 1         | 0.81%   |
| WDC WD10EZRZ-00HTKB0 1TB             | 1         | 0.81%   |
| WDC WD10EZEX-22BN5A0 1TB             | 1         | 0.81%   |
| WDC WD10EZEX-00RKKA0 1TB             | 1         | 0.81%   |
| WDC WD10EZEX-00BN5A0 1TB             | 1         | 0.81%   |
| WDC WD10EURX-61C57Y0 1TB             | 1         | 0.81%   |
| WDC WD10EALS-00Z8A0 1TB              | 1         | 0.81%   |
| WDC WD100EMAZ-00WJTA0 10TB           | 1         | 0.81%   |
| WDC WD1003FZEX-00K3CA0 1TB           | 1         | 0.81%   |
| WDC PC SN520 SDAPNUW-256G-1102 256GB | 1         | 0.81%   |
| Unknown SLD32G  32GB                 | 1         | 0.81%   |
| Unknown SD32G  32GB                  | 1         | 0.81%   |
| Unknown SC32G  32GB                  | 1         | 0.81%   |
| Unknown 00000  32GB                  | 1         | 0.81%   |
| Toshiba MK2565GSXN 250GB             | 1         | 0.81%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 19        | 42     | 37.25%  |
| Seagate             | 15        | 28     | 29.41%  |
| Toshiba             | 7         | 13     | 13.73%  |
| Samsung Electronics | 3         | 3      | 5.88%   |
| Hitachi             | 3         | 3      | 5.88%   |
| HGST                | 2         | 2      | 3.92%   |
| Maxtor              | 1         | 1      | 1.96%   |
| Fujitsu             | 1         | 1      | 1.96%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 10        | 16     | 32.26%  |
| Kingston            | 4         | 4      | 12.9%   |
| Crucial             | 4         | 5      | 12.9%   |
| SanDisk             | 2         | 2      | 6.45%   |
| A-DATA Technology   | 2         | 2      | 6.45%   |
| TO Exter            | 1         | 1      | 3.23%   |
| Team                | 1         | 1      | 3.23%   |
| Patriot             | 1         | 2      | 3.23%   |
| Netac               | 1         | 1      | 3.23%   |
| Micron Technology   | 1         | 1      | 3.23%   |
| Intel               | 1         | 1      | 3.23%   |
| Dogfish             | 1         | 1      | 3.23%   |
| China               | 1         | 2      | 3.23%   |
| Apple               | 1         | 2      | 3.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 37        | 93     | 43.02%  |
| SSD     | 29        | 41     | 33.72%  |
| NVMe    | 15        | 17     | 17.44%  |
| MMC     | 4         | 4      | 4.65%   |
| Unknown | 1         | 4      | 1.16%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 51        | 129    | 70.83%  |
| NVMe | 15        | 17     | 20.83%  |
| MMC  | 4         | 4      | 5.56%   |
| SAS  | 2         | 9      | 2.78%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 37        | 57     | 50%     |
| 0.51-1.0   | 20        | 43     | 27.03%  |
| 1.01-2.0   | 6         | 9      | 8.11%   |
| 3.01-4.0   | 4         | 11     | 5.41%   |
| 2.01-3.0   | 4         | 8      | 5.41%   |
| 10.01-20.0 | 2         | 5      | 2.7%    |
| 4.01-10.0  | 1         | 1      | 1.35%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 13        | 20.63%  |
| 501-1000       | 13        | 20.63%  |
| 251-500        | 10        | 15.87%  |
| Unknown        | 9         | 14.29%  |
| 1001-2000      | 8         | 12.7%   |
| 2001-3000      | 3         | 4.76%   |
| 51-100         | 3         | 4.76%   |
| 1-20           | 2         | 3.17%   |
| More than 3000 | 1         | 1.59%   |
| 21-50          | 1         | 1.59%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 501-1000       | 11        | 16.67%  |
| 21-50          | 10        | 15.15%  |
| 1-20           | 10        | 15.15%  |
| 51-100         | 10        | 15.15%  |
| Unknown        | 9         | 13.64%  |
| 101-250        | 7         | 10.61%  |
| 251-500        | 6         | 9.09%   |
| 1001-2000      | 2         | 3.03%   |
| More than 3000 | 1         | 1.52%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WD5000LPCX-60VHAT1 500GB       | 1         | 1      | 4.35%   |
| WDC WD5000BPKX-60HPJT0 500GB       | 1         | 1      | 4.35%   |
| WDC WD5000AAKX-00ERMA0 500GB       | 1         | 1      | 4.35%   |
| WDC WD5000AAKS-00A7B2 500GB        | 1         | 1      | 4.35%   |
| WDC WD40EFRX-68WT0N0 4TB           | 1         | 2      | 4.35%   |
| WDC WD30EZRX-00M                   | 1         | 1      | 4.35%   |
| WDC WD30EFRX-68AX9N0 3TB           | 1         | 4      | 4.35%   |
| WDC WD10JPLX-00MBPT0 1TB           | 1         | 1      | 4.35%   |
| WDC WD10EZEX-00RKKA0 1TB           | 1         | 1      | 4.35%   |
| WDC WD10EALS-00Z8A0 1TB            | 1         | 2      | 4.35%   |
| WDC WD1003FZEX-00MK2A0 1TB         | 1         | 2      | 4.35%   |
| Toshiba MK2565GSXN 250GB           | 1         | 1      | 4.35%   |
| Seagate ST380011A 80GB             | 1         | 1      | 4.35%   |
| Seagate ST3500418AS 500GB          | 1         | 1      | 4.35%   |
| Seagate ST3500410AS 500GB          | 1         | 1      | 4.35%   |
| Seagate ST31000524AS 1TB           | 1         | 1      | 4.35%   |
| Seagate ST1000VM002-1SD102 1TB     | 1         | 1      | 4.35%   |
| Seagate ST1000NM0011 1TB           | 1         | 2      | 4.35%   |
| SanDisk SDSA6MM-016G-1006 16GB SSD | 1         | 1      | 4.35%   |
| Maxtor 4G120J6 128GB               | 1         | 1      | 4.35%   |
| Intel SSDSA2M080G2GC 80GB          | 1         | 1      | 4.35%   |
| Hitachi HDS721050CLA660 500GB      | 1         | 1      | 4.35%   |
| HGST HDN726040ALE614 4TB           | 1         | 1      | 4.35%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 9         | 17     | 42.86%  |
| Seagate | 6         | 7      | 28.57%  |
| Toshiba | 1         | 1      | 4.76%   |
| SanDisk | 1         | 1      | 4.76%   |
| Maxtor  | 1         | 1      | 4.76%   |
| Intel   | 1         | 1      | 4.76%   |
| Hitachi | 1         | 1      | 4.76%   |
| HGST    | 1         | 1      | 4.76%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 9         | 17     | 47.37%  |
| Seagate | 6         | 7      | 31.58%  |
| Toshiba | 1         | 1      | 5.26%   |
| Maxtor  | 1         | 1      | 5.26%   |
| Hitachi | 1         | 1      | 5.26%   |
| HGST    | 1         | 1      | 5.26%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 18        | 28     | 90%     |
| SSD  | 2         | 2      | 10%     |

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
| Works    | 49        | 112    | 62.82%  |
| Malfunc  | 20        | 30     | 25.64%  |
| Detected | 9         | 17     | 11.54%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 44        | 53.01%  |
| AMD                         | 14        | 16.87%  |
| Samsung Electronics         | 8         | 9.64%   |
| ASMedia Technology          | 3         | 3.61%   |
| SanDisk                     | 2         | 2.41%   |
| Marvell Technology Group    | 2         | 2.41%   |
| Broadcom / LSI              | 2         | 2.41%   |
| SK hynix                    | 1         | 1.2%    |
| Silicon Image               | 1         | 1.2%    |
| Realtek Semiconductor       | 1         | 1.2%    |
| Phison Electronics          | 1         | 1.2%    |
| Nvidia                      | 1         | 1.2%    |
| Kingston Technology Company | 1         | 1.2%    |
| JMicron Technology          | 1         | 1.2%    |
| 3ware                       | 1         | 1.2%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 12        | 12.12%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 6         | 6.06%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 4         | 4.04%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 4         | 4.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 3.03%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 3         | 3.03%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 2.02%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 2.02%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 2         | 2.02%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                              | 2         | 2.02%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 2.02%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2         | 2.02%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 2         | 2.02%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 2         | 2.02%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 2         | 2.02%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 2.02%   |
| AMD 400 Series Chipset SATA Controller                                           | 2         | 2.02%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 1         | 1.01%   |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller                 | 1         | 1.01%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 1.01%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 1.01%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 1.01%   |
| Samsung Apple PCIe SSD                                                           | 1         | 1.01%   |
| Realtek Realtek Non-Volatile memory controller                                   | 1         | 1.01%   |
| Phison NVMe Storage Controller                                                   | 1         | 1.01%   |
| Nvidia MCP61 SATA Controller                                                     | 1         | 1.01%   |
| Nvidia MCP61 IDE                                                                 | 1         | 1.01%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                     | 1         | 1.01%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller                          | 1         | 1.01%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 1.01%   |
| JMicron JMB368 IDE controller                                                    | 1         | 1.01%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 1         | 1.01%   |
| Intel SSD 600P Series                                                            | 1         | 1.01%   |
| Intel SATA Controller [RAID mode]                                                | 1         | 1.01%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 1         | 1.01%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 1.01%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 1.01%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 1.01%   |
| Intel C608 chipset Dual 4-Port SATA/SAS Storage Control Unit                     | 1         | 1.01%   |
| Intel C600/X79 series chipset IDE-r Controller                                   | 1         | 1.01%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 52        | 62.65%  |
| NVMe | 15        | 18.07%  |
| IDE  | 8         | 9.64%   |
| RAID | 4         | 4.82%   |
| SAS  | 4         | 4.82%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 46        | 73.02%  |
| AMD    | 15        | 23.81%  |
| ARM    | 2         | 3.17%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Xeon CPU E5-2670 0 @ 2.60GHz            | 2         | 3.17%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 2         | 3.17%   |
| ARM Processor                                 | 2         | 3.17%   |
| AMD Ryzen 5 3600 6-Core Processor             | 2         | 3.17%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 2         | 3.17%   |
| AMD FX-8350 Eight-Core Processor              | 2         | 3.17%   |
| Intel Xeon CPU X3450 @ 2.67GHz                | 1         | 1.59%   |
| Intel Xeon CPU E5-2620 0 @ 2.00GHz            | 1         | 1.59%   |
| Intel Xeon CPU E5-1650 0 @ 3.20GHz            | 1         | 1.59%   |
| Intel Xeon CPU E3-1246 v3 @ 3.50GHz           | 1         | 1.59%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz        | 1         | 1.59%   |
| Intel Pentium CPU P6100 @ 2.00GHz             | 1         | 1.59%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 1.59%   |
| Intel Pentium CPU G640 @ 2.80GHz              | 1         | 1.59%   |
| Intel Pentium CPU G4560 @ 3.50GHz             | 1         | 1.59%   |
| Intel CPU Version                             | 1         | 1.59%   |
| Intel Core i7-9700 CPU @ 3.00GHz              | 1         | 1.59%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 1.59%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 1.59%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 1.59%   |
| Intel Core i7-2860QM CPU @ 2.50GHz            | 1         | 1.59%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 1         | 1.59%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 1.59%   |
| Intel Core i5-9400 CPU @ 2.90GHz              | 1         | 1.59%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 1.59%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 1.59%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 1.59%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 1.59%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 1         | 1.59%   |
| Intel Core i5-4690 CPU @ 3.50GHz              | 1         | 1.59%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 1.59%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 1.59%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 1         | 1.59%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 1         | 1.59%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 1.59%   |
| Intel Core i3-6100U CPU @ 2.30GHz             | 1         | 1.59%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 1.59%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 1         | 1.59%   |
| Intel Core i3-4000M CPU @ 2.40GHz             | 1         | 1.59%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz         | 1         | 1.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Computers | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 12        | 19.05%  |
| Intel Core i7      | 9         | 14.29%  |
| Intel Xeon         | 6         | 9.52%   |
| Intel Pentium      | 4         | 6.35%   |
| Intel Core i3      | 4         | 6.35%   |
| AMD Ryzen 5        | 4         | 6.35%   |
| Other              | 3         | 4.76%   |
| Intel Celeron      | 3         | 4.76%   |
| Intel Core 2 Quad  | 2         | 3.17%   |
| Intel Core 2 Duo   | 2         | 3.17%   |
| AMD Ryzen 9        | 2         | 3.17%   |
| AMD Ryzen 7        | 2         | 3.17%   |
| AMD FX             | 2         | 3.17%   |
| Intel Pentium Gold | 1         | 1.59%   |
| Intel Core 2       | 1         | 1.59%   |
| Intel Atom         | 1         | 1.59%   |
| AMD Ryzen Embedded | 1         | 1.59%   |
| AMD GX             | 1         | 1.59%   |
| AMD Athlon 64 X2   | 1         | 1.59%   |
| AMD A4             | 1         | 1.59%   |
| AMD A10            | 1         | 1.59%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 23        | 36.51%  |
| 4      | 22        | 34.92%  |
| 6      | 7         | 11.11%  |
| 16     | 3         | 4.76%   |
| 8      | 3         | 4.76%   |
| 1      | 3         | 4.76%   |
| 12     | 2         | 3.17%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 58        | 92.06%  |
| 2      | 5         | 7.94%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 43        | 68.25%  |
| 1      | 20        | 31.75%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 60        | 95.24%  |
| Unknown        | 2         | 3.17%   |
| 32-bit         | 1         | 1.59%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 16        | 25.4%   |
| 0x306c3    | 4         | 6.35%   |
| 0x206d7    | 3         | 4.76%   |
| 0x206a7    | 3         | 4.76%   |
| 0x1067a    | 3         | 4.76%   |
| 0x08701013 | 3         | 4.76%   |
| 0x906ed    | 2         | 3.17%   |
| 0x806ec    | 2         | 3.17%   |
| 0x406e3    | 2         | 3.17%   |
| 0x406c4    | 2         | 3.17%   |
| 0x306d4    | 2         | 3.17%   |
| 0x06001119 | 2         | 3.17%   |
| 0xa0660    | 1         | 1.59%   |
| 0x906ea    | 1         | 1.59%   |
| 0x806ea    | 1         | 1.59%   |
| 0x806e9    | 1         | 1.59%   |
| 0x706a1    | 1         | 1.59%   |
| 0x6fd      | 1         | 1.59%   |
| 0x506e3    | 1         | 1.59%   |
| 0x40651    | 1         | 1.59%   |
| 0x306a9    | 1         | 1.59%   |
| 0x20655    | 1         | 1.59%   |
| 0x106e5    | 1         | 1.59%   |
| 0x106c2    | 1         | 1.59%   |
| 0x10661    | 1         | 1.59%   |
| 0x08701021 | 1         | 1.59%   |
| 0x0810100b | 1         | 1.59%   |
| 0x08001138 | 1         | 1.59%   |
| 0x07000110 | 1         | 1.59%   |
| 0x06000852 | 1         | 1.59%   |
| 0x06000822 | 1         | 1.59%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 10        | 15.87%  |
| Haswell       | 8         | 12.7%   |
| SandyBridge   | 7         | 11.11%  |
| Zen 2         | 5         | 7.94%   |
| Skylake       | 4         | 6.35%   |
| Piledriver    | 4         | 6.35%   |
| Zen           | 3         | 4.76%   |
| Silvermont    | 3         | 4.76%   |
| Penryn        | 3         | 4.76%   |
| Core          | 3         | 4.76%   |
| Broadwell     | 2         | 3.17%   |
| Unknown       | 2         | 3.17%   |
| Zen+          | 1         | 1.59%   |
| Westmere      | 1         | 1.59%   |
| Nehalem       | 1         | 1.59%   |
| K8 Hammer     | 1         | 1.59%   |
| Jaguar        | 1         | 1.59%   |
| IvyBridge     | 1         | 1.59%   |
| Goldmont plus | 1         | 1.59%   |
| CometLake     | 1         | 1.59%   |
| Bonnell       | 1         | 1.59%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 33        | 51.56%  |
| AMD                        | 15        | 23.44%  |
| Nvidia                     | 14        | 21.88%  |
| Matrox Electronics Systems | 2         | 3.13%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 4.41%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 4.41%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 3         | 4.41%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 2.94%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 2.94%   |
| Intel HD Graphics 620                                                                    | 2         | 2.94%   |
| Intel HD Graphics 5500                                                                   | 2         | 2.94%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 2.94%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 2.94%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2         | 2.94%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 2.94%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 2.94%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 2.94%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1         | 1.47%   |
| Nvidia GP107GL [Quadro P1000]                                                            | 1         | 1.47%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 1.47%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1         | 1.47%   |
| Nvidia GM204GLM [Quadro M3000M]                                                          | 1         | 1.47%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1         | 1.47%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1         | 1.47%   |
| Nvidia GK110GL [Quadro K5200]                                                            | 1         | 1.47%   |
| Nvidia GK107M [GeForce GT 745M]                                                          | 1         | 1.47%   |
| Nvidia GK107 [GeForce GT 640]                                                            | 1         | 1.47%   |
| Nvidia GK104GL [Quadro K5000]                                                            | 1         | 1.47%   |
| Nvidia GF106GLM [Quadro 2000M]                                                           | 1         | 1.47%   |
| Nvidia G80GL [Quadro FX 4600]                                                            | 1         | 1.47%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 1         | 1.47%   |
| Matrox Electronics Systems MGA G200eH3                                                   | 1         | 1.47%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1         | 1.47%   |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller                           | 1         | 1.47%   |
| Intel UHD Graphics 620                                                                   | 1         | 1.47%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.47%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.47%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 1         | 1.47%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 1.47%   |
| Intel HD Graphics 530                                                                    | 1         | 1.47%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 1.47%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.47%   |
| Intel Comet Lake UHD Graphics                                                            | 1         | 1.47%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.47%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 30        | 47.62%  |
| 1 x AMD        | 14        | 22.22%  |
| 1 x Nvidia     | 9         | 14.29%  |
| Other          | 3         | 4.76%   |
| Intel + Nvidia | 3         | 4.76%   |
| 1 x Matrox     | 2         | 3.17%   |
| 2 x Nvidia     | 1         | 1.59%   |
| AMD + Nvidia   | 1         | 1.59%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 44        | 69.84%  |
| Unknown     | 10        | 15.87%  |
| Proprietary | 9         | 14.29%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 38        | 59.38%  |
| 3.01-4.0   | 8         | 12.5%   |
| 1.01-2.0   | 8         | 12.5%   |
| 0.51-1.0   | 6         | 9.38%   |
| 7.01-8.0   | 2         | 3.13%   |
| 0.01-0.5   | 2         | 3.13%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Chimei Innolux       | 7         | 11.29%  |
| LG Display           | 6         | 9.68%   |
| Samsung Electronics  | 5         | 8.06%   |
| AU Optronics         | 5         | 8.06%   |
| Goldstar             | 4         | 6.45%   |
| Dell                 | 4         | 6.45%   |
| BenQ                 | 4         | 6.45%   |
| Hewlett-Packard      | 3         | 4.84%   |
| BOE                  | 3         | 4.84%   |
| ViewSonic            | 2         | 3.23%   |
| Lenovo               | 2         | 3.23%   |
| ASUSTek Computer     | 2         | 3.23%   |
| Acer                 | 2         | 3.23%   |
| Xiaomi               | 1         | 1.61%   |
| Unknown              | 1         | 1.61%   |
| Toshiba              | 1         | 1.61%   |
| Sharp                | 1         | 1.61%   |
| Panasonic            | 1         | 1.61%   |
| ONN                  | 1         | 1.61%   |
| NEC Computers        | 1         | 1.61%   |
| JVC                  | 1         | 1.61%   |
| Iiyama               | 1         | 1.61%   |
| Gigabyte Technology  | 1         | 1.61%   |
| Eizo                 | 1         | 1.61%   |
| DPC                  | 1         | 1.61%   |
| Ancor Communications | 1         | 1.61%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 2         | 3.13%   |
| Xiaomi Mi TV XMD009A 2880x1800 480x270mm 21.7-inch                   | 1         | 1.56%   |
| ViewSonic LCD Monitor VX2276 Series 1920x1080                        | 1         | 1.56%   |
| ViewSonic LCD Monitor VA2448 SERIES 1920x1080                        | 1         | 1.56%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch            | 1         | 1.56%   |
| Toshiba TV TSB0206 1920x1080 886x498mm 40.0-inch                     | 1         | 1.56%   |
| Sharp LCD Monitor SHP14C4 1920x1080 344x194mm 15.5-inch              | 1         | 1.56%   |
| Samsung Electronics SyncMaster SAM0578 1920x1080 476x268mm 21.5-inch | 1         | 1.56%   |
| Samsung Electronics SyncMaster SAM0428 1680x1050 459x296mm 21.5-inch | 1         | 1.56%   |
| Samsung Electronics SMB2430L SAM0644 1920x1080 521x293mm 23.5-inch   | 1         | 1.56%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch | 1         | 1.56%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 1         | 1.56%   |
| Panasonic LCD Monitor MEI96A2 2880x1620 344x193mm 15.5-inch          | 1         | 1.56%   |
| ONN ONA18HO015 ONN0101 1920x1080 470x290mm 21.7-inch                 | 1         | 1.56%   |
| NEC Computers LCD2490WUXi NEC66CE 1920x1200 518x324mm 24.1-inch      | 1         | 1.56%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch         | 1         | 1.56%   |
| LG Display LCD Monitor LGD0508 1366x768 309x174mm 14.0-inch          | 1         | 1.56%   |
| LG Display LCD Monitor LGD03D7 1366x768 309x174mm 14.0-inch          | 1         | 1.56%   |
| LG Display LCD Monitor LGD0353 1366x768 345x194mm 15.6-inch          | 1         | 1.56%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch          | 1         | 1.56%   |
| LG Display LCD Monitor LGD02D9 1920x1080 344x194mm 15.5-inch         | 1         | 1.56%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch             | 1         | 1.56%   |
| Lenovo LCD Monitor LEN4035 1280x800 303x190mm 14.1-inch              | 1         | 1.56%   |
| JVC FPDEUFT3 JVC21BE 1920x540                                        | 1         | 1.56%   |
| Iiyama PLE2207WS IVM5609 1680x1050 474x296mm 22.0-inch               | 1         | 1.56%   |
| Hewlett-Packard ZR2740w HWP2957 2560x1440 597x336mm 27.0-inch        | 1         | 1.56%   |
| Hewlett-Packard LE1851w HWP2840 1366x768 413x234mm 18.7-inch         | 1         | 1.56%   |
| Hewlett-Packard 2309 HWP2823 1920x1080 510x287mm 23.0-inch           | 1         | 1.56%   |
| Goldstar W2242 GSM5678 1680x1050 474x296mm 22.0-inch                 | 1         | 1.56%   |
| Goldstar W2242 GSM5677 1680x1050 474x296mm 22.0-inch                 | 1         | 1.56%   |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                  | 1         | 1.56%   |
| Goldstar FULL HD GSM5ABA 1920x1080 480x270mm 21.7-inch               | 1         | 1.56%   |
| Goldstar BK750Y GSM5B3E 1920x1080 600x340mm 27.2-inch                | 1         | 1.56%   |
| Goldstar BK750Y GSM5B3D 1920x1080 480x270mm 21.7-inch                | 1         | 1.56%   |
| Gigabyte Technology G27Q GBT2709 2560x1440 598x336mm 27.0-inch       | 1         | 1.56%   |
| Eizo M1700 ENC1788 1280x1024 338x271mm 17.1-inch                     | 1         | 1.56%   |
| DPC Qumi Q38 DPC81F2 1920x1200 708x398mm 32.0-inch                   | 1         | 1.56%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 1         | 1.56%   |
| Dell LCD Monitor U2312HM 1920x1080                                   | 1         | 1.56%   |
| Dell E176FP DELA014 1280x1024 338x270mm 17.0-inch                    | 1         | 1.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 29        | 47.54%  |
| 1366x768 (WXGA)    | 12        | 19.67%  |
| 1280x1024 (SXGA)   | 4         | 6.56%   |
| 1680x1050 (WSXGA+) | 3         | 4.92%   |
| 3840x2160 (4K)     | 2         | 3.28%   |
| 2560x1440 (QHD)    | 2         | 3.28%   |
| 1920x1200 (WUXGA)  | 2         | 3.28%   |
| 1600x900 (HD+)     | 2         | 3.28%   |
| 1280x800 (WXGA)    | 2         | 3.28%   |
| 3440x1440          | 1         | 1.64%   |
| 2288x1287          | 1         | 1.64%   |
| 1920x540           | 1         | 1.64%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 14        | 22.22%  |
| 21      | 8         | 12.7%   |
| 24      | 6         | 9.52%   |
| 14      | 6         | 9.52%   |
| 17      | 5         | 7.94%   |
| 27      | 4         | 6.35%   |
| 23      | 4         | 6.35%   |
| 13      | 4         | 6.35%   |
| Unknown | 4         | 6.35%   |
| 142     | 1         | 1.59%   |
| 74      | 1         | 1.59%   |
| 32      | 1         | 1.59%   |
| 22      | 1         | 1.59%   |
| 20      | 1         | 1.59%   |
| 19      | 1         | 1.59%   |
| 18      | 1         | 1.59%   |
| 12      | 1         | 1.59%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 25        | 39.68%  |
| 501-600        | 13        | 20.63%  |
| 401-500        | 12        | 19.05%  |
| 351-400        | 4         | 6.35%   |
| Unknown        | 4         | 6.35%   |
| 201-300        | 2         | 3.17%   |
| More than 2000 | 1         | 1.59%   |
| 701-800        | 1         | 1.59%   |
| 1501-2000      | 1         | 1.59%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 41        | 69.49%  |
| 16/10   | 7         | 11.86%  |
| Unknown | 3         | 5.08%   |
| 6/5     | 2         | 3.39%   |
| 5/4     | 2         | 3.39%   |
| 3/2     | 2         | 3.39%   |
| 32/9    | 1         | 1.69%   |
| 1.00    | 1         | 1.69%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 15        | 24.19%  |
| 101-110        | 14        | 22.58%  |
| 81-90          | 9         | 14.52%  |
| 301-350        | 4         | 6.45%   |
| 141-150        | 4         | 6.45%   |
| Unknown        | 4         | 6.45%   |
| 251-300        | 3         | 4.84%   |
| More than 1000 | 2         | 3.23%   |
| 151-200        | 2         | 3.23%   |
| 121-130        | 2         | 3.23%   |
| 71-80          | 1         | 1.61%   |
| 61-70          | 1         | 1.61%   |
| 351-500        | 1         | 1.61%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 23        | 36.51%  |
| 101-120       | 18        | 28.57%  |
| 121-160       | 14        | 22.22%  |
| Unknown       | 4         | 6.35%   |
| More than 240 | 2         | 3.17%   |
| 1-50          | 2         | 3.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 45        | 71.43%  |
| 2     | 8         | 12.7%   |
| 0     | 8         | 12.7%   |
| 3     | 2         | 3.17%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 38        | 41.3%   |
| Realtek Semiconductor    | 28        | 30.43%  |
| Qualcomm Atheros         | 9         | 9.78%   |
| Broadcom                 | 4         | 4.35%   |
| Ralink Technology        | 2         | 2.17%   |
| VIA Technologies         | 1         | 1.09%   |
| TP-Link                  | 1         | 1.09%   |
| Sierra Wireless          | 1         | 1.09%   |
| Ralink                   | 1         | 1.09%   |
| Nvidia                   | 1         | 1.09%   |
| Micro Star International | 1         | 1.09%   |
| Mellanox Technologies    | 1         | 1.09%   |
| Dell                     | 1         | 1.09%   |
| Chelsio Communications   | 1         | 1.09%   |
| Broadcom Limited         | 1         | 1.09%   |
| ASIX Electronics         | 1         | 1.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 19        | 16.96%  |
| Intel I211 Gigabit Network Connection                                                 | 6         | 5.36%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 5         | 4.46%   |
| Intel 82574L Gigabit Network Connection                                               | 4         | 3.57%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 3         | 2.68%   |
| Intel Wireless-AC 9260                                                                | 3         | 2.68%   |
| Intel Wireless 7260                                                                   | 3         | 2.68%   |
| Intel Ethernet Connection (2) I218-V                                                  | 3         | 2.68%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 3         | 2.68%   |
| Ralink MT7601U Wireless Adapter                                                       | 2         | 1.79%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 2         | 1.79%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                             | 2         | 1.79%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                        | 2         | 1.79%   |
| Intel Wireless 8265 / 8275                                                            | 2         | 1.79%   |
| Intel Wireless 8260                                                                   | 2         | 1.79%   |
| Intel Wireless 7265                                                                   | 2         | 1.79%   |
| Intel Wireless 3160                                                                   | 2         | 1.79%   |
| Intel Ethernet Connection I217-V                                                      | 2         | 1.79%   |
| Intel Ethernet Connection (2) I219-LM                                                 | 2         | 1.79%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 2         | 1.79%   |
| VIA VT6105/VT6106S [Rhine-III]                                                        | 1         | 0.89%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                                                 | 1         | 0.89%   |
| Sierra Wireless EM7305                                                                | 1         | 0.89%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                       | 1         | 0.89%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1         | 0.89%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                              | 1         | 0.89%   |
| Realtek RTL8125 2.5GbE Controller                                                     | 1         | 0.89%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                             | 1         | 0.89%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                      | 1         | 0.89%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 1         | 0.89%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                         | 1         | 0.89%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 0.89%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 1         | 0.89%   |
| Nvidia MCP61 Ethernet                                                                 | 1         | 0.89%   |
| Micro Star International MS-3871 802.11bgn Wireless Module [Ralink RT8070]            | 1         | 0.89%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]                                 | 1         | 0.89%   |
| Intel WiFi Link 5100                                                                  | 1         | 0.89%   |
| Intel Wi-Fi 6 AX200                                                                   | 1         | 0.89%   |
| Intel I350 Gigabit Network Connection                                                 | 1         | 0.89%   |
| Intel Gemini Lake PCH CNVi WiFi                                                       | 1         | 0.89%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 22        | 53.66%  |
| Qualcomm Atheros         | 6         | 14.63%  |
| Realtek Semiconductor    | 5         | 12.2%   |
| Ralink Technology        | 2         | 4.88%   |
| TP-Link                  | 1         | 2.44%   |
| Sierra Wireless          | 1         | 2.44%   |
| Ralink                   | 1         | 2.44%   |
| Micro Star International | 1         | 2.44%   |
| Dell                     | 1         | 2.44%   |
| Broadcom                 | 1         | 2.44%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8188EE Wireless Network Adapter                                            | 3         | 7.32%   |
| Intel Wireless-AC 9260                                                                | 3         | 7.32%   |
| Intel Wireless 7260                                                                   | 3         | 7.32%   |
| Ralink MT7601U Wireless Adapter                                                       | 2         | 4.88%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 2         | 4.88%   |
| Intel Wireless 8265 / 8275                                                            | 2         | 4.88%   |
| Intel Wireless 8260                                                                   | 2         | 4.88%   |
| Intel Wireless 7265                                                                   | 2         | 4.88%   |
| Intel Wireless 3160                                                                   | 2         | 4.88%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 2         | 4.88%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                                                 | 1         | 2.44%   |
| Sierra Wireless EM7305                                                                | 1         | 2.44%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                       | 1         | 2.44%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1         | 2.44%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                             | 1         | 2.44%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                      | 1         | 2.44%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 1         | 2.44%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 2.44%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 1         | 2.44%   |
| Micro Star International MS-3871 802.11bgn Wireless Module [Ralink RT8070]            | 1         | 2.44%   |
| Intel WiFi Link 5100                                                                  | 1         | 2.44%   |
| Intel Wi-Fi 6 AX200                                                                   | 1         | 2.44%   |
| Intel Gemini Lake PCH CNVi WiFi                                                       | 1         | 2.44%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1         | 2.44%   |
| Intel Centrino Ultimate-N 6300                                                        | 1         | 2.44%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 1         | 2.44%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                                                  | 1         | 2.44%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 1         | 2.44%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Realtek Semiconductor  | 25        | 39.06%  |
| Intel                  | 25        | 39.06%  |
| Qualcomm Atheros       | 5         | 7.81%   |
| Broadcom               | 3         | 4.69%   |
| VIA Technologies       | 1         | 1.56%   |
| Nvidia                 | 1         | 1.56%   |
| Mellanox Technologies  | 1         | 1.56%   |
| Chelsio Communications | 1         | 1.56%   |
| Broadcom Limited       | 1         | 1.56%   |
| ASIX Electronics       | 1         | 1.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 19        | 26.76%  |
| Intel I211 Gigabit Network Connection                                         | 6         | 8.45%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 5         | 7.04%   |
| Intel 82574L Gigabit Network Connection                                       | 4         | 5.63%   |
| Intel Ethernet Connection (2) I218-V                                          | 3         | 4.23%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 3         | 4.23%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 2         | 2.82%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 2         | 2.82%   |
| Intel Ethernet Connection I217-V                                              | 2         | 2.82%   |
| Intel Ethernet Connection (2) I219-LM                                         | 2         | 2.82%   |
| VIA VT6105/VT6106S [Rhine-III]                                                | 1         | 1.41%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 1         | 1.41%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1         | 1.41%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1         | 1.41%   |
| Nvidia MCP61 Ethernet                                                         | 1         | 1.41%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]                         | 1         | 1.41%   |
| Intel I350 Gigabit Network Connection                                         | 1         | 1.41%   |
| Intel Ethernet Connection I219-LM                                             | 1         | 1.41%   |
| Intel Ethernet Connection I218-V                                              | 1         | 1.41%   |
| Intel Ethernet Connection (7) I219-V                                          | 1         | 1.41%   |
| Intel Ethernet Connection (4) I219-V                                          | 1         | 1.41%   |
| Intel Ethernet Connection (3) I218-LM                                         | 1         | 1.41%   |
| Intel Ethernet Connection (10) I219-V                                         | 1         | 1.41%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 1         | 1.41%   |
| Intel 82579V Gigabit Network Connection                                       | 1         | 1.41%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 1.41%   |
| Intel 82567LM Gigabit Network Connection                                      | 1         | 1.41%   |
| Chelsio T320 10GbE Dual Port Adapter                                          | 1         | 1.41%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                             | 1         | 1.41%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                       | 1         | 1.41%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                        | 1         | 1.41%   |
| Broadcom Limited NetXtreme BCM5756ME Gigabit Ethernet PCI Express             | 1         | 1.41%   |
| ASIX AX88772B                                                                 | 1         | 1.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 59        | 60.82%  |
| WiFi     | 38        | 39.18%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 36        | 65.45%  |
| WiFi     | 19        | 34.55%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 34        | 53.97%  |
| 1     | 17        | 26.98%  |
| 0     | 5         | 7.94%   |
| 3     | 4         | 6.35%   |
| 4     | 2         | 3.17%   |
| 5     | 1         | 1.59%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 59        | 93.65%  |
| Yes  | 4         | 6.35%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 20        | 58.82%  |
| Cambridge Silicon Radio         | 7         | 20.59%  |
| Qualcomm Atheros Communications | 3         | 8.82%   |
| Toshiba                         | 1         | 2.94%   |
| Realtek Semiconductor           | 1         | 2.94%   |
| Micro Star International        | 1         | 2.94%   |
| Broadcom                        | 1         | 2.94%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 11        | 32.35%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 7         | 20.59%  |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 8.82%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 8.82%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 5.88%   |
| Toshiba Askey Bluetooth Module                      | 1         | 2.94%   |
| Realtek Bluetooth Radio                             | 1         | 2.94%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 2.94%   |
| Micro Star International Bluetooth Device           | 1         | 2.94%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 2.94%   |
| Intel AX201 Bluetooth                               | 1         | 2.94%   |
| Intel AX200 Bluetooth                               | 1         | 2.94%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 2.94%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 44        | 56.41%  |
| AMD                 | 17        | 21.79%  |
| Nvidia              | 10        | 12.82%  |
| Creative Labs       | 3         | 3.85%   |
| C-Media Electronics | 2         | 2.56%   |
| Texas Instruments   | 1         | 1.28%   |
| EGO SYStems         | 1         | 1.28%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 6         | 6.06%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 5         | 5.05%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 4.04%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 4         | 4.04%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 3.03%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 3.03%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 3         | 3.03%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 3.03%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 3         | 3.03%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 3.03%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 3         | 3.03%   |
| AMD FCH Azalia Controller                                                                         | 3         | 3.03%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 3         | 3.03%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 3         | 3.03%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 3         | 3.03%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 2.02%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 2         | 2.02%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 2.02%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 2.02%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 2.02%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 2.02%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 2.02%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 2.02%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 2.02%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 2.02%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 1.01%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 1.01%   |
| Nvidia MCP61 High Definition Audio                                                                | 1         | 1.01%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1         | 1.01%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 1.01%   |
| Nvidia GK110 High Definition Audio Controller                                                     | 1         | 1.01%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 1.01%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 1.01%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 1.01%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 1.01%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 1         | 1.01%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 1.01%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1         | 1.01%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 1.01%   |
| Intel 200 Series PCH HD Audio                                                                     | 1         | 1.01%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 13        | 20.63%  |
| Samsung Electronics | 9         | 14.29%  |
| Kingston            | 8         | 12.7%   |
| Corsair             | 7         | 11.11%  |
| Unknown             | 6         | 9.52%   |
| Crucial             | 6         | 9.52%   |
| Micron Technology   | 4         | 6.35%   |
| Team                | 2         | 3.17%   |
| Transcend           | 1         | 1.59%   |
| Smart               | 1         | 1.59%   |
| Ramaxel Technology  | 1         | 1.59%   |
| HPE                 | 1         | 1.59%   |
| Elpida              | 1         | 1.59%   |
| Avant               | 1         | 1.59%   |
| AMD                 | 1         | 1.59%   |
| A Force             | 1         | 1.59%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 2         | 2.9%    |
| SK hynix RAM HMA851S6AFR6N-UH 2GB SODIMM LPDDR4 2667MT/s  | 2         | 2.9%    |
| Unknown RAM Module 4096MB DIMM DDR3 65535MT/s             | 1         | 1.45%   |
| Unknown RAM Module 2048MB DIMM SDRAM                      | 1         | 1.45%   |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s                | 1         | 1.45%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                    | 1         | 1.45%   |
| Unknown RAM Module 1024MB SODIMM SDRAM                    | 1         | 1.45%   |
| Unknown RAM Module 1024MB SODIMM DDR2 533MT/s             | 1         | 1.45%   |
| Unknown RAM Module 1024MB DIMM DDR 800MT/s                | 1         | 1.45%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                    | 1         | 1.45%   |
| Transcend RAM TS256MLQ72V6U 2GB DIMM DDR2 667MT/s         | 1         | 1.45%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3600MT/s       | 1         | 1.45%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s       | 1         | 1.45%   |
| Smart RAM SH5641G8FJ8NWRNSQG 8GB SODIMM DDR3 1600MT/s     | 1         | 1.45%   |
| SK hynix RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s   | 1         | 1.45%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s           | 1         | 1.45%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s     | 1         | 1.45%   |
| SK hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 2000MT/s      | 1         | 1.45%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s    | 1         | 1.45%   |
| SK hynix RAM HMT351R7CFR8A-H9 4GB DIMM DDR3 1333MT/s      | 1         | 1.45%   |
| SK hynix RAM HMT31GR7EFR4A 8192MB DIMM DDR3 1600MT/s      | 1         | 1.45%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s    | 1         | 1.45%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s    | 1         | 1.45%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s     | 1         | 1.45%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s  | 1         | 1.45%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s     | 1         | 1.45%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s     | 1         | 1.45%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s     | 1         | 1.45%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s     | 1         | 1.45%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s     | 1         | 1.45%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s    | 1         | 1.45%   |
| Samsung RAM M393B5273DH0-CK0 4GB DIMM DDR3 1600MT/s       | 1         | 1.45%   |
| Ramaxel RAM RMSA3260MH78HAF-2666 8GB SODIMM DDR4 2667MT/s | 1         | 1.45%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s     | 1         | 1.45%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s     | 1         | 1.45%   |
| Micron RAM 36KSF1G72PZ-1G4K1 8192MB DIMM DDR3 1333MT/s    | 1         | 1.45%   |
| Micron RAM 18JSF1G72PZ-1G9E1 8GB DIMM DDR3 1866MT/s       | 1         | 1.45%   |
| Micron RAM 16JTF51264AZ-1G6M1 4GB DIMM DDR3 1600MT/s      | 1         | 1.45%   |
| Kingston RAM KHX3600C17D4/8GX 8GB DIMM DDR4 3600MT/s      | 1         | 1.45%   |
| Kingston RAM KHX2666C15S4/8G 8GB SODIMM DDR4 2667MT/s     | 1         | 1.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 25        | 43.86%  |
| DDR4    | 21        | 36.84%  |
| SDRAM   | 3         | 5.26%   |
| DDR2    | 3         | 5.26%   |
| LPDDR4  | 2         | 3.51%   |
| LPDDR3  | 1         | 1.75%   |
| DDR     | 1         | 1.75%   |
| Unknown | 1         | 1.75%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 31        | 54.39%  |
| SODIMM       | 25        | 43.86%  |
| Row Of Chips | 1         | 1.75%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 25        | 40.98%  |
| 4096  | 17        | 27.87%  |
| 16384 | 6         | 9.84%   |
| 2048  | 6         | 9.84%   |
| 1024  | 4         | 6.56%   |
| 32768 | 3         | 4.92%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 17        | 27.87%  |
| 2667    | 9         | 14.75%  |
| 2400    | 6         | 9.84%   |
| 3600    | 3         | 4.92%   |
| 1333    | 3         | 4.92%   |
| 667     | 3         | 4.92%   |
| 3200    | 2         | 3.28%   |
| 2666    | 2         | 3.28%   |
| 2133    | 2         | 3.28%   |
| 1867    | 2         | 3.28%   |
| Unknown | 2         | 3.28%   |
| 65535   | 1         | 1.64%   |
| 4199    | 1         | 1.64%   |
| 3800    | 1         | 1.64%   |
| 2800    | 1         | 1.64%   |
| 2000    | 1         | 1.64%   |
| 1866    | 1         | 1.64%   |
| 1334    | 1         | 1.64%   |
| 975     | 1         | 1.64%   |
| 800     | 1         | 1.64%   |
| 533     | 1         | 1.64%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 2         | 40%     |
| Brother Industries | 2         | 40%     |
| Dell               | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Computers | Percent |
|--------------------------|-----------|---------|
| HP ENVY 4520 series      | 1         | 20%     |
| HP ENVY 4500 series      | 1         | 20%     |
| Dell 2330d Laser Printer | 1         | 20%     |
| Brother Printer          | 1         | 20%     |
| Brother HL-L2320D series | 1         | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model           | Computers | Percent |
|-----------------|-----------|---------|
| HP ScanJet 5590 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 9         | 33.33%  |
| Logitech                               | 4         | 14.81%  |
| IMC Networks                           | 3         | 11.11%  |
| Sunplus Innovation Technology          | 2         | 7.41%   |
| Realtek Semiconductor                  | 2         | 7.41%   |
| Lite-On Technology                     | 2         | 7.41%   |
| Silicon Motion                         | 1         | 3.7%    |
| Quanta                                 | 1         | 3.7%    |
| Motorola PCS                           | 1         | 3.7%    |
| Cheng Uei Precision Industry (Foxlink) | 1         | 3.7%    |
| Acer                                   | 1         | 3.7%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Realtek USB Camera                                                         | 2         | 7.41%   |
| Chicony Integrated Camera                                                  | 2         | 7.41%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                       | 1         | 3.7%    |
| Sunplus Integrated_Webcam_HD                                               | 1         | 3.7%    |
| Silicon Motion Web Camera                                                  | 1         | 3.7%    |
| Quanta HP Webcam                                                           | 1         | 3.7%    |
| Motorola PCS XT1033 [Moto G], PTP mode                                     | 1         | 3.7%    |
| Logitech Webcam C300                                                       | 1         | 3.7%    |
| Logitech Webcam C170                                                       | 1         | 3.7%    |
| Logitech HD Webcam C525                                                    | 1         | 3.7%    |
| Logitech HD Pro Webcam C920                                                | 1         | 3.7%    |
| Lite-On TOSHIBA Web Camera - FHD                                           | 1         | 3.7%    |
| Lite-On Integrated Camera                                                  | 1         | 3.7%    |
| IMC Networks UVC VGA Webcam                                                | 1         | 3.7%    |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 1         | 3.7%    |
| IMC Networks Integrated Camera                                             | 1         | 3.7%    |
| Chicony TOSHIBA Web Camera - HD                                            | 1         | 3.7%    |
| Chicony TOSHIBA Web Camera - FHD                                           | 1         | 3.7%    |
| Chicony Integrated Camera (1280x720@30)                                    | 1         | 3.7%    |
| Chicony HD WebCam (Acer)                                                   | 1         | 3.7%    |
| Chicony HD WebCam                                                          | 1         | 3.7%    |
| Chicony FJ Camera                                                          | 1         | 3.7%    |
| Chicony 2.0M UVC Webcam / CNF7129                                          | 1         | 3.7%    |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD integrated webcam | 1         | 3.7%    |
| Acer BisonCam,NB Pro                                                       | 1         | 3.7%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 3         | 50%     |
| Synaptics             | 1         | 16.67%  |
| LighTuning Technology | 1         | 16.67%  |
| Elan Microelectronics | 1         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS7500 Touch Fingerprint Sensor | 1         | 16.67%  |
| Validity Sensors VFS Fingerprint sensor           | 1         | 16.67%  |
| Validity Sensors VFS 5011 fingerprint sensor      | 1         | 16.67%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 16.67%  |
| LighTuning EgisTec Touch Fingerprint Sensor       | 1         | 16.67%  |
| Elan ELAN:Fingerprint                             | 1         | 16.67%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 2         | 33.33%  |
| Alcor Micro           | 2         | 33.33%  |
| O2 Micro              | 1         | 16.67%  |
| Gemalto (was Gemplus) | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                    | 2         | 33.33%  |
| O2 Micro OZ776 CCID Smartcard Reader                   | 1         | 16.67%  |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer | 1         | 16.67%  |
| Broadcom BCM5880 Secure Applications Processor         | 1         | 16.67%  |
| Broadcom 5880                                          | 1         | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 35        | 53.85%  |
| 1     | 13        | 20%     |
| 2     | 9         | 13.85%  |
| 3     | 5         | 7.69%   |
| 4     | 3         | 4.62%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 12        | 23.08%  |
| Sound                    | 7         | 13.46%  |
| Fingerprint reader       | 6         | 11.54%  |
| Chipcard                 | 6         | 11.54%  |
| Communication controller | 5         | 9.62%   |
| Net/wireless             | 4         | 7.69%   |
| Card reader              | 4         | 7.69%   |
| Bluetooth                | 2         | 3.85%   |
| Unassigned class         | 1         | 1.92%   |
| Storage/ata              | 1         | 1.92%   |
| Storage                  | 1         | 1.92%   |
| Net/ethernet             | 1         | 1.92%   |
| Firewire controller      | 1         | 1.92%   |
| Camera                   | 1         | 1.92%   |

