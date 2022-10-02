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

Total: 79

| Vendor     | Model                       | Form-Factor | Probe                                                      | Date         |
|------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version              | Computers | Percent |
|----------------------|-----------|---------|
| 4.19.80              | 7         | 10.61%  |
| 5.10.28-Unraid       | 6         | 9.09%   |
| 4.4.190              | 4         | 6.06%   |
| 4.4.240              | 3         | 4.55%   |
| 5.3.7                | 2         | 3.03%   |
| 5.7.0                | 1         | 1.52%   |
| 5.5.10               | 1         | 1.52%   |
| 5.4.77               | 1         | 1.52%   |
| 5.4.75               | 1         | 1.52%   |
| 5.4.62               | 1         | 1.52%   |
| 5.4.53-APRL          | 1         | 1.52%   |
| 5.4.50               | 1         | 1.52%   |
| 5.4.47               | 1         | 1.52%   |
| 5.4.43               | 1         | 1.52%   |
| 5.4.24toshiba-new    | 1         | 1.52%   |
| 5.4.2                | 1         | 1.52%   |
| 5.4.13               | 1         | 1.52%   |
| 5.4.12+              | 1         | 1.52%   |
| 5.4.0-rc2-vto        | 1         | 1.52%   |
| 5.2.2                | 1         | 1.52%   |
| 5.15.50-cwl          | 1         | 1.52%   |
| 5.13.0.a             | 1         | 1.52%   |
| 5.12.12              | 1         | 1.52%   |
| 5.10.44-slack64-host | 1         | 1.52%   |
| 5.10.40              | 1         | 1.52%   |
| 5.10.4               | 1         | 1.52%   |
| 5.10.3               | 1         | 1.52%   |
| 5.10.21              | 1         | 1.52%   |
| 5.10.19              | 1         | 1.52%   |
| 4.9.248.a            | 1         | 1.52%   |
| 4.9.118              | 1         | 1.52%   |
| 4.4.88               | 1         | 1.52%   |
| 4.4.276              | 1         | 1.52%   |
| 4.4.261              | 1         | 1.52%   |
| 4.4.227              | 1         | 1.52%   |
| 4.4.206+             | 1         | 1.52%   |
| 4.4.202              | 1         | 1.52%   |
| 4.4.190-smp          | 1         | 1.52%   |
| 4.4.189              | 1         | 1.52%   |
| 4.4.14               | 1         | 1.52%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.19.80 | 7         | 10.61%  |
| 5.10.28 | 6         | 9.09%   |
| 4.4.190 | 5         | 7.58%   |
| 4.4.240 | 3         | 4.55%   |
| 5.3.7   | 2         | 3.03%   |
| 5.7.0   | 1         | 1.52%   |
| 5.5.10  | 1         | 1.52%   |
| 5.4.77  | 1         | 1.52%   |
| 5.4.75  | 1         | 1.52%   |
| 5.4.62  | 1         | 1.52%   |
| 5.4.53  | 1         | 1.52%   |
| 5.4.50  | 1         | 1.52%   |
| 5.4.47  | 1         | 1.52%   |
| 5.4.43  | 1         | 1.52%   |
| 5.4.24  | 1         | 1.52%   |
| 5.4.2   | 1         | 1.52%   |
| 5.4.13  | 1         | 1.52%   |
| 5.4.12  | 1         | 1.52%   |
| 5.4.0   | 1         | 1.52%   |
| 5.2.2   | 1         | 1.52%   |
| 5.15.50 | 1         | 1.52%   |
| 5.13.0  | 1         | 1.52%   |
| 5.12.12 | 1         | 1.52%   |
| 5.10.44 | 1         | 1.52%   |
| 5.10.40 | 1         | 1.52%   |
| 5.10.4  | 1         | 1.52%   |
| 5.10.3  | 1         | 1.52%   |
| 5.10.21 | 1         | 1.52%   |
| 5.10.19 | 1         | 1.52%   |
| 4.9.248 | 1         | 1.52%   |
| 4.9.118 | 1         | 1.52%   |
| 4.4.88  | 1         | 1.52%   |
| 4.4.276 | 1         | 1.52%   |
| 4.4.261 | 1         | 1.52%   |
| 4.4.227 | 1         | 1.52%   |
| 4.4.206 | 1         | 1.52%   |
| 4.4.202 | 1         | 1.52%   |
| 4.4.189 | 1         | 1.52%   |
| 4.4.14  | 1         | 1.52%   |
| 4.20.11 | 1         | 1.52%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.4     | 16        | 24.24%  |
| 4.19    | 14        | 21.21%  |
| 5.4     | 12        | 18.18%  |
| 5.10    | 12        | 18.18%  |
| 5.3     | 2         | 3.03%   |
| 4.9     | 2         | 3.03%   |
| 5.7     | 1         | 1.52%   |
| 5.5     | 1         | 1.52%   |
| 5.2     | 1         | 1.52%   |
| 5.15    | 1         | 1.52%   |
| 5.13    | 1         | 1.52%   |
| 5.12    | 1         | 1.52%   |
| 4.20    | 1         | 1.52%   |
| 4.16    | 1         | 1.52%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 59        | 95.16%  |
| aarch64 | 2         | 3.23%   |
| i686    | 1         | 1.61%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Unknown       | 34        | 53.97%  |
| XFCE          | 19        | 30.16%  |
| KDE           | 4         | 6.35%   |
| KDE5          | 2         | 3.17%   |
| MATE          | 1         | 1.59%   |
| LXQt          | 1         | 1.59%   |
| fvwm          | 1         | 1.59%   |
| Enlightenment | 1         | 1.59%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 49        | 79.03%  |
| Unknown | 8         | 12.9%   |
| Tty     | 4         | 6.45%   |
| Wayland | 1         | 1.61%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 36        | 57.14%  |
| XDM     | 20        | 31.75%  |
| SDDM    | 5         | 7.94%   |
| SLiM    | 2         | 3.17%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 31        | 50%     |
| en_US   | 23        | 37.1%   |
| ru_RU   | 1         | 1.61%   |
| pt_BR   | 1         | 1.61%   |
| pl_PL   | 1         | 1.61%   |
| it_IT   | 1         | 1.61%   |
| fr_FR   | 1         | 1.61%   |
| en_GB   | 1         | 1.61%   |
| en_AU   | 1         | 1.61%   |
| C       | 1         | 1.61%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 40        | 63.49%  |
| EFI  | 23        | 36.51%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 47        | 75.81%  |
| Btrfs    | 8         | 12.9%   |
| Rootfs   | 3         | 4.84%   |
| Xfs      | 2         | 3.23%   |
| Reiserfs | 1         | 1.61%   |
| Jfs      | 1         | 1.61%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 38        | 60.32%  |
| MBR     | 22        | 34.92%  |
| Unknown | 3         | 4.76%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 36        | 57.14%  |
| Yes       | 27        | 42.86%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 43        | 69.35%  |
| Yes       | 19        | 30.65%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 14        | 22.58%  |
| Lenovo              | 7         | 11.29%  |
| Hewlett-Packard     | 7         | 11.29%  |
| Gigabyte Technology | 5         | 8.06%   |
| Dell                | 5         | 8.06%   |
| Toshiba             | 3         | 4.84%   |
| ASRock              | 3         | 4.84%   |
| MSI                 | 2         | 3.23%   |
| Acer                | 2         | 3.23%   |
| Supermicro          | 1         | 1.61%   |
| Shuttle             | 1         | 1.61%   |
| Samsung Electronics | 1         | 1.61%   |
| Radxa               | 1         | 1.61%   |
| Notebook            | 1         | 1.61%   |
| NetGear             | 1         | 1.61%   |
| Intel               | 1         | 1.61%   |
| Huanan              | 1         | 1.61%   |
| HPE                 | 1         | 1.61%   |
| Fujitsu             | 1         | 1.61%   |
| Foxconn             | 1         | 1.61%   |
| Dynabook            | 1         | 1.61%   |
| AMI                 | 1         | 1.61%   |
| Unknown             | 1         | 1.61%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| ASUS All Series                          | 3         | 4.84%   |
| Toshiba Satellite P50-A-12Z              | 1         | 1.61%   |
| Toshiba Satellite C660                   | 1         | 1.61%   |
| Toshiba PORTEGE Z30-A                    | 1         | 1.61%   |
| Supermicro X9DA7/E                       | 1         | 1.61%   |
| Shuttle NC03U                            | 1         | 1.61%   |
| Samsung 300E5M/300E5L                    | 1         | 1.61%   |
| Radxa ROCK Pi 4                          | 1         | 1.61%   |
| Notebook NL40_50CU                       | 1         | 1.61%   |
| NetGear ReadyDATA 5200                   | 1         | 1.61%   |
| MSI MS-7529                              | 1         | 1.61%   |
| MSI GL73 8RC                             | 1         | 1.61%   |
| Lenovo V330-14ARR 81B1                   | 1         | 1.61%   |
| Lenovo ThinkPad X1 Carbon 7th 20R10015US | 1         | 1.61%   |
| Lenovo ThinkPad T470 20HDCTO1WW          | 1         | 1.61%   |
| Lenovo ThinkPad T450s 20BW000EUS         | 1         | 1.61%   |
| Lenovo ThinkPad T400 6474BV7             | 1         | 1.61%   |
| Lenovo ThinkPad P70 20ERCTO1WW           | 1         | 1.61%   |
| Lenovo ThinkPad L440 20ASS05K00          | 1         | 1.61%   |
| Intel DZ77RE-75K AAG39010-302            | 1         | 1.61%   |
| Huanan X79-8D VAA31                      | 1         | 1.61%   |
| HPE ProLiant MicroServer Gen10 Plus      | 1         | 1.61%   |
| HP Z620 Workstation                      | 1         | 1.61%   |
| HP t640 Thin Client                      | 1         | 1.61%   |
| HP t620 Quad Core TC                     | 1         | 1.61%   |
| HP Pavilion Notebook                     | 1         | 1.61%   |
| HP Laptop 15-bs2xx                       | 1         | 1.61%   |
| HP 500-515na                             | 1         | 1.61%   |
| HP 15 Notebook PC                        | 1         | 1.61%   |
| Gigabyte X570 AORUS MASTER               | 1         | 1.61%   |
| Gigabyte X150M-PRO ECC                   | 1         | 1.61%   |
| Gigabyte N3160TN                         | 1         | 1.61%   |
| Gigabyte M61SME-S2                       | 1         | 1.61%   |
| Gigabyte 970A-DS3P                       | 1         | 1.61%   |
| Fujitsu LIFEBOOK A555                    | 1         | 1.61%   |
| Foxconn p6-2390                          | 1         | 1.61%   |
| Dynabook PORTEGE X50-G                   | 1         | 1.61%   |
| Dell Precision WorkStation T3400         | 1         | 1.61%   |
| Dell Precision T3600                     | 1         | 1.61%   |
| Dell Precision M4600                     | 1         | 1.61%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 6         | 9.68%   |
| Dell Precision     | 3         | 4.84%   |
| ASUS PRIME         | 3         | 4.84%   |
| ASUS All           | 3         | 4.84%   |
| Toshiba Satellite  | 2         | 3.23%   |
| Dell Latitude      | 2         | 3.23%   |
| Toshiba PORTEGE    | 1         | 1.61%   |
| Supermicro X9DA7   | 1         | 1.61%   |
| Shuttle NC03U      | 1         | 1.61%   |
| Samsung 300E5M     | 1         | 1.61%   |
| Radxa ROCK         | 1         | 1.61%   |
| Notebook NL40      | 1         | 1.61%   |
| NetGear ReadyDATA  | 1         | 1.61%   |
| MSI MS-7529        | 1         | 1.61%   |
| MSI GL73           | 1         | 1.61%   |
| Lenovo V330-14ARR  | 1         | 1.61%   |
| Intel DZ77RE-75K   | 1         | 1.61%   |
| Huanan X79-8D      | 1         | 1.61%   |
| HPE ProLiant       | 1         | 1.61%   |
| HP Z620            | 1         | 1.61%   |
| HP t640            | 1         | 1.61%   |
| HP t620            | 1         | 1.61%   |
| HP Pavilion        | 1         | 1.61%   |
| HP Laptop          | 1         | 1.61%   |
| HP 500-515na       | 1         | 1.61%   |
| HP 15              | 1         | 1.61%   |
| Gigabyte X570      | 1         | 1.61%   |
| Gigabyte X150M-PRO | 1         | 1.61%   |
| Gigabyte N3160TN   | 1         | 1.61%   |
| Gigabyte M61SME-S2 | 1         | 1.61%   |
| Gigabyte 970A-DS3P | 1         | 1.61%   |
| Fujitsu LIFEBOOK   | 1         | 1.61%   |
| Foxconn p6-2390    | 1         | 1.61%   |
| Dynabook PORTEGE   | 1         | 1.61%   |
| ASUS VivoBook      | 1         | 1.61%   |
| ASUS ROG           | 1         | 1.61%   |
| ASUS Pro           | 1         | 1.61%   |
| ASUS P5QLD         | 1         | 1.61%   |
| ASUS P53E          | 1         | 1.61%   |
| ASUS M5A97         | 1         | 1.61%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 10        | 16.13%  |
| 2017    | 7         | 11.29%  |
| 2018    | 6         | 9.68%   |
| 2015    | 6         | 9.68%   |
| 2014    | 6         | 9.68%   |
| 2016    | 5         | 8.06%   |
| 2012    | 4         | 6.45%   |
| 2008    | 4         | 6.45%   |
| 2013    | 3         | 4.84%   |
| 2011    | 3         | 4.84%   |
| 2020    | 2         | 3.23%   |
| 2009    | 2         | 3.23%   |
| Unknown | 2         | 3.23%   |
| 2010    | 1         | 1.61%   |
| 2007    | 1         | 1.61%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 32        | 51.61%  |
| Notebook       | 26        | 41.94%  |
| System on chip | 2         | 3.23%   |
| Mini pc        | 2         | 3.23%   |

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
| No   | 61        | 98.39%  |
| Yes  | 1         | 1.61%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 13        | 20.97%  |
| 4.01-8.0    | 12        | 19.35%  |
| 16.01-24.0  | 12        | 19.35%  |
| 3.01-4.0    | 11        | 17.74%  |
| 32.01-64.0  | 6         | 9.68%   |
| 64.01-256.0 | 4         | 6.45%   |
| 24.01-32.0  | 2         | 3.23%   |
| 1.01-2.0    | 1         | 1.61%   |
| 0.51-1.0    | 1         | 1.61%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 23        | 35.94%  |
| 2.01-3.0    | 12        | 18.75%  |
| 3.01-4.0    | 10        | 15.63%  |
| 4.01-8.0    | 7         | 10.94%  |
| 8.01-16.0   | 4         | 6.25%   |
| 0.01-0.5    | 3         | 4.69%   |
| 24.01-32.0  | 2         | 3.13%   |
| 64.01-256.0 | 1         | 1.56%   |
| 16.01-24.0  | 1         | 1.56%   |
| 0.51-1.0    | 1         | 1.56%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 30        | 47.62%  |
| 2      | 11        | 17.46%  |
| 3      | 7         | 11.11%  |
| 4      | 5         | 7.94%   |
| 5      | 4         | 6.35%   |
| 6      | 2         | 3.17%   |
| 13     | 1         | 1.59%   |
| 8      | 1         | 1.59%   |
| 7      | 1         | 1.59%   |
| 0      | 1         | 1.59%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 36        | 58.06%  |
| Yes       | 26        | 41.94%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 58        | 93.55%  |
| No        | 4         | 6.45%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 37        | 59.68%  |
| No        | 25        | 40.32%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 34        | 54.84%  |
| No        | 28        | 45.16%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 14        | 22.58%  |
| UK          | 8         | 12.9%   |
| Germany     | 5         | 8.06%   |
| Russia      | 4         | 6.45%   |
| Portugal    | 4         | 6.45%   |
| India       | 4         | 6.45%   |
| Canada      | 4         | 6.45%   |
| Sweden      | 3         | 4.84%   |
| France      | 3         | 4.84%   |
| Poland      | 2         | 3.23%   |
| Italy       | 2         | 3.23%   |
| Brazil      | 2         | 3.23%   |
| Spain       | 1         | 1.61%   |
| Philippines | 1         | 1.61%   |
| Hong Kong   | 1         | 1.61%   |
| Finland     | 1         | 1.61%   |
| Chile       | 1         | 1.61%   |
| Bulgaria    | 1         | 1.61%   |
| Australia   | 1         | 1.61%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Yekaterinburg          | 3         | 4.69%   |
| Paris                  | 3         | 4.69%   |
| Lisbon                 | 3         | 4.69%   |
| Warsaw                 | 2         | 3.13%   |
| New Delhi              | 2         | 3.13%   |
| Carrollton             | 2         | 3.13%   |
| Barry                  | 2         | 3.13%   |
| Barrie                 | 2         | 3.13%   |
| Wokingham              | 1         | 1.56%   |
| Winnipeg               | 1         | 1.56%   |
| Weilheim               | 1         | 1.56%   |
| Visconde do Rio Branco | 1         | 1.56%   |
| Tiffin                 | 1         | 1.56%   |
| Stockholm              | 1         | 1.56%   |
| St Louis               | 1         | 1.56%   |
| Springfield            | 1         | 1.56%   |
| Southend-on-Sea        | 1         | 1.56%   |
| Shrewsbury             | 1         | 1.56%   |
| Roknaes                | 1         | 1.56%   |
| Redding                | 1         | 1.56%   |
| Puente Alto            | 1         | 1.56%   |
| Plovdiv                | 1         | 1.56%   |
| Pinhal Novo            | 1         | 1.56%   |
| Pesaro                 | 1         | 1.56%   |
| Pasay                  | 1         | 1.56%   |
| Palma                  | 1         | 1.56%   |
| Ottawa                 | 1         | 1.56%   |
| Oldham                 | 1         | 1.56%   |
| Northport              | 1         | 1.56%   |
| Naples                 | 1         | 1.56%   |
| Milwaukee              | 1         | 1.56%   |
| Milan                  | 1         | 1.56%   |
| Mason                  | 1         | 1.56%   |
| Lins                   | 1         | 1.56%   |
| Lexington              | 1         | 1.56%   |
| Kstovo                 | 1         | 1.56%   |
| Kowloon                | 1         | 1.56%   |
| Koblenz                | 1         | 1.56%   |
| Jaipur                 | 1         | 1.56%   |
| Hornsey                | 1         | 1.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


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

![Drive Model](./All/images/pie_chart/drive_model.svg)


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

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


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

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


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

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


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

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 51        | 129    | 70.83%  |
| NVMe | 15        | 17     | 20.83%  |
| MMC  | 4         | 4      | 5.56%   |
| SAS  | 2         | 9      | 2.78%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 38        | 58     | 51.35%  |
| 0.51-1.0   | 19        | 42     | 25.68%  |
| 1.01-2.0   | 6         | 9      | 8.11%   |
| 3.01-4.0   | 4         | 11     | 5.41%   |
| 2.01-3.0   | 4         | 8      | 5.41%   |
| 10.01-20.0 | 2         | 5      | 2.7%    |
| 4.01-10.0  | 1         | 1      | 1.35%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 13        | 20.97%  |
| 501-1000       | 13        | 20.97%  |
| 251-500        | 9         | 14.52%  |
| Unknown        | 9         | 14.52%  |
| 1001-2000      | 8         | 12.9%   |
| 2001-3000      | 3         | 4.84%   |
| 51-100         | 3         | 4.84%   |
| 1-20           | 2         | 3.23%   |
| More than 3000 | 1         | 1.61%   |
| 21-50          | 1         | 1.61%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 501-1000       | 11        | 16.92%  |
| 21-50          | 10        | 15.38%  |
| 1-20           | 10        | 15.38%  |
| 51-100         | 10        | 15.38%  |
| Unknown        | 9         | 13.85%  |
| 101-250        | 7         | 10.77%  |
| 251-500        | 5         | 7.69%   |
| 1001-2000      | 2         | 3.08%   |
| More than 3000 | 1         | 1.54%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


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

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


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

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


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

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


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

![Drive Status](./All/images/pie_chart/drive_status.svg)


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

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 43        | 52.44%  |
| AMD                         | 14        | 17.07%  |
| Samsung Electronics         | 8         | 9.76%   |
| ASMedia Technology          | 3         | 3.66%   |
| SanDisk                     | 2         | 2.44%   |
| Marvell Technology Group    | 2         | 2.44%   |
| Broadcom / LSI              | 2         | 2.44%   |
| SK hynix                    | 1         | 1.22%   |
| Silicon Image               | 1         | 1.22%   |
| Realtek Semiconductor       | 1         | 1.22%   |
| Phison Electronics          | 1         | 1.22%   |
| Nvidia                      | 1         | 1.22%   |
| Kingston Technology Company | 1         | 1.22%   |
| JMicron Technology          | 1         | 1.22%   |
| 3ware                       | 1         | 1.22%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 12        | 12.37%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 6         | 6.19%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 4         | 4.12%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 4         | 4.12%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 3.09%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 3         | 3.09%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 2.06%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 2.06%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 2         | 2.06%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                              | 2         | 2.06%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 2.06%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2         | 2.06%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 2         | 2.06%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 2         | 2.06%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 2         | 2.06%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 2.06%   |
| AMD 400 Series Chipset SATA Controller                                           | 2         | 2.06%   |
| SK hynix Gold P31 SSD                                                            | 1         | 1.03%   |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller                 | 1         | 1.03%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 1.03%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 1.03%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 1.03%   |
| Samsung Apple PCIe SSD                                                           | 1         | 1.03%   |
| Realtek Realtek Non-Volatile memory controller                                   | 1         | 1.03%   |
| Phison NVMe Storage Controller                                                   | 1         | 1.03%   |
| Nvidia MCP61 SATA Controller                                                     | 1         | 1.03%   |
| Nvidia MCP61 IDE                                                                 | 1         | 1.03%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                     | 1         | 1.03%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller                          | 1         | 1.03%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 1.03%   |
| JMicron JMB368 IDE controller                                                    | 1         | 1.03%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 1         | 1.03%   |
| Intel SSD 600P Series                                                            | 1         | 1.03%   |
| Intel SATA Controller [RAID mode]                                                | 1         | 1.03%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 1         | 1.03%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 1.03%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 1.03%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 1.03%   |
| Intel C608 chipset Dual 4-Port SATA/SAS Storage Control Unit                     | 1         | 1.03%   |
| Intel C600/X79 series chipset IDE-r Controller                                   | 1         | 1.03%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 51        | 62.96%  |
| NVMe | 15        | 18.52%  |
| IDE  | 7         | 8.64%   |
| RAID | 4         | 4.94%   |
| SAS  | 4         | 4.94%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 45        | 72.58%  |
| AMD    | 15        | 24.19%  |
| ARM    | 2         | 3.23%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Xeon CPU E5-2670 0 @ 2.60GHz            | 2         | 3.23%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 2         | 3.23%   |
| ARM Processor                                 | 2         | 3.23%   |
| AMD Ryzen 5 3600 6-Core Processor             | 2         | 3.23%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 2         | 3.23%   |
| AMD FX-8350 Eight-Core Processor              | 2         | 3.23%   |
| Intel Xeon CPU X3450 @ 2.67GHz                | 1         | 1.61%   |
| Intel Xeon CPU E5-2620 0 @ 2.00GHz            | 1         | 1.61%   |
| Intel Xeon CPU E5-1650 0 @ 3.20GHz            | 1         | 1.61%   |
| Intel Xeon CPU E3-1246 v3 @ 3.50GHz           | 1         | 1.61%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz        | 1         | 1.61%   |
| Intel Pentium CPU P6100 @ 2.00GHz             | 1         | 1.61%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 1.61%   |
| Intel Pentium CPU G640 @ 2.80GHz              | 1         | 1.61%   |
| Intel Pentium CPU G4560 @ 3.50GHz             | 1         | 1.61%   |
| Intel Core i7-9700 CPU @ 3.00GHz              | 1         | 1.61%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 1.61%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 1.61%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 1.61%   |
| Intel Core i7-2860QM CPU @ 2.50GHz            | 1         | 1.61%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 1         | 1.61%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 1.61%   |
| Intel Core i5-9400 CPU @ 2.90GHz              | 1         | 1.61%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 1.61%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 1.61%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 1.61%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 1.61%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 1         | 1.61%   |
| Intel Core i5-4690 CPU @ 3.50GHz              | 1         | 1.61%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 1.61%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 1.61%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 1         | 1.61%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 1         | 1.61%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 1.61%   |
| Intel Core i3-6100U CPU @ 2.30GHz             | 1         | 1.61%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 1.61%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 1         | 1.61%   |
| Intel Core i3-4000M CPU @ 2.40GHz             | 1         | 1.61%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz         | 1         | 1.61%   |
| Intel Core 2 Quad CPU Q6700 @ 2.66GHz         | 1         | 1.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model              | Computers | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 12        | 19.35%  |
| Intel Core i7      | 9         | 14.52%  |
| Intel Xeon         | 6         | 9.68%   |
| Intel Pentium      | 4         | 6.45%   |
| Intel Core i3      | 4         | 6.45%   |
| AMD Ryzen 5        | 4         | 6.45%   |
| Intel Celeron      | 3         | 4.84%   |
| Other              | 2         | 3.23%   |
| Intel Core 2 Quad  | 2         | 3.23%   |
| Intel Core 2 Duo   | 2         | 3.23%   |
| AMD Ryzen 9        | 2         | 3.23%   |
| AMD Ryzen 7        | 2         | 3.23%   |
| AMD FX             | 2         | 3.23%   |
| Intel Pentium Gold | 1         | 1.61%   |
| Intel Core 2       | 1         | 1.61%   |
| Intel Atom         | 1         | 1.61%   |
| AMD Ryzen Embedded | 1         | 1.61%   |
| AMD GX             | 1         | 1.61%   |
| AMD Athlon 64 X2   | 1         | 1.61%   |
| AMD A4             | 1         | 1.61%   |
| AMD A10            | 1         | 1.61%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 23        | 37.1%   |
| 4      | 22        | 35.48%  |
| 6      | 7         | 11.29%  |
| 16     | 3         | 4.84%   |
| 8      | 3         | 4.84%   |
| 12     | 2         | 3.23%   |
| 1      | 2         | 3.23%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 57        | 91.94%  |
| 2      | 5         | 8.06%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 43        | 69.35%  |
| 1      | 19        | 30.65%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 59        | 95.16%  |
| Unknown        | 2         | 3.23%   |
| 32-bit         | 1         | 1.61%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 16        | 25.81%  |
| 0x306c3    | 4         | 6.45%   |
| 0x206d7    | 3         | 4.84%   |
| 0x206a7    | 3         | 4.84%   |
| 0x1067a    | 3         | 4.84%   |
| 0x08701013 | 3         | 4.84%   |
| 0x906ed    | 2         | 3.23%   |
| 0x806ec    | 2         | 3.23%   |
| 0x406e3    | 2         | 3.23%   |
| 0x406c4    | 2         | 3.23%   |
| 0x306d4    | 2         | 3.23%   |
| 0x06001119 | 2         | 3.23%   |
| 0xa0660    | 1         | 1.61%   |
| 0x906ea    | 1         | 1.61%   |
| 0x806ea    | 1         | 1.61%   |
| 0x806e9    | 1         | 1.61%   |
| 0x706a1    | 1         | 1.61%   |
| 0x6fd      | 1         | 1.61%   |
| 0x506e3    | 1         | 1.61%   |
| 0x40651    | 1         | 1.61%   |
| 0x306a9    | 1         | 1.61%   |
| 0x20655    | 1         | 1.61%   |
| 0x106e5    | 1         | 1.61%   |
| 0x106c2    | 1         | 1.61%   |
| 0x08701021 | 1         | 1.61%   |
| 0x0810100b | 1         | 1.61%   |
| 0x08001138 | 1         | 1.61%   |
| 0x07000110 | 1         | 1.61%   |
| 0x06000852 | 1         | 1.61%   |
| 0x06000822 | 1         | 1.61%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 10        | 16.13%  |
| Haswell       | 8         | 12.9%   |
| SandyBridge   | 7         | 11.29%  |
| Zen 2         | 5         | 8.06%   |
| Skylake       | 4         | 6.45%   |
| Piledriver    | 4         | 6.45%   |
| Zen           | 3         | 4.84%   |
| Silvermont    | 3         | 4.84%   |
| Penryn        | 3         | 4.84%   |
| Core          | 2         | 3.23%   |
| Broadwell     | 2         | 3.23%   |
| Unknown       | 2         | 3.23%   |
| Zen+          | 1         | 1.61%   |
| Westmere      | 1         | 1.61%   |
| Nehalem       | 1         | 1.61%   |
| K8 Hammer     | 1         | 1.61%   |
| Jaguar        | 1         | 1.61%   |
| IvyBridge     | 1         | 1.61%   |
| Goldmont plus | 1         | 1.61%   |
| CometLake     | 1         | 1.61%   |
| Bonnell       | 1         | 1.61%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 32        | 50.79%  |
| AMD                        | 15        | 23.81%  |
| Nvidia                     | 14        | 22.22%  |
| Matrox Electronics Systems | 2         | 3.17%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 4.55%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 4.55%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 3         | 4.55%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 3.03%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 3.03%   |
| Intel HD Graphics 620                                                                    | 2         | 3.03%   |
| Intel HD Graphics 5500                                                                   | 2         | 3.03%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 3.03%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 3.03%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2         | 3.03%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 3.03%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 3.03%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 3.03%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1         | 1.52%   |
| Nvidia GP107GL [Quadro P1000]                                                            | 1         | 1.52%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 1.52%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1         | 1.52%   |
| Nvidia GM204GLM [Quadro M3000M]                                                          | 1         | 1.52%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1         | 1.52%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1         | 1.52%   |
| Nvidia GK110GL [Quadro K5200]                                                            | 1         | 1.52%   |
| Nvidia GK107M [GeForce GT 745M]                                                          | 1         | 1.52%   |
| Nvidia GK107 [GeForce GT 640]                                                            | 1         | 1.52%   |
| Nvidia GK104GL [Quadro K5000]                                                            | 1         | 1.52%   |
| Nvidia GF106GLM [Quadro 2000M]                                                           | 1         | 1.52%   |
| Nvidia G80GL [Quadro FX 4600]                                                            | 1         | 1.52%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 1         | 1.52%   |
| Matrox Electronics Systems MGA G200eH3                                                   | 1         | 1.52%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1         | 1.52%   |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller                           | 1         | 1.52%   |
| Intel UHD Graphics 620                                                                   | 1         | 1.52%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 1         | 1.52%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 1.52%   |
| Intel HD Graphics 530                                                                    | 1         | 1.52%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 1.52%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.52%   |
| Intel Comet Lake UHD Graphics                                                            | 1         | 1.52%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.52%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1         | 1.52%   |
| AMD Richland [Radeon HD 8470D]                                                           | 1         | 1.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 29        | 46.77%  |
| 1 x AMD        | 14        | 22.58%  |
| 1 x Nvidia     | 9         | 14.52%  |
| Other          | 3         | 4.84%   |
| Intel + Nvidia | 3         | 4.84%   |
| 1 x Matrox     | 2         | 3.23%   |
| 2 x Nvidia     | 1         | 1.61%   |
| AMD + Nvidia   | 1         | 1.61%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 43        | 69.35%  |
| Unknown     | 10        | 16.13%  |
| Proprietary | 9         | 14.52%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 38        | 60.32%  |
| 3.01-4.0   | 8         | 12.7%   |
| 1.01-2.0   | 8         | 12.7%   |
| 0.51-1.0   | 6         | 9.52%   |
| 7.01-8.0   | 2         | 3.17%   |
| 0.01-0.5   | 1         | 1.59%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Chimei Innolux       | 7         | 11.48%  |
| LG Display           | 6         | 9.84%   |
| Samsung Electronics  | 5         | 8.2%    |
| Goldstar             | 4         | 6.56%   |
| Dell                 | 4         | 6.56%   |
| BenQ                 | 4         | 6.56%   |
| AU Optronics         | 4         | 6.56%   |
| Hewlett-Packard      | 3         | 4.92%   |
| BOE                  | 3         | 4.92%   |
| ViewSonic            | 2         | 3.28%   |
| Lenovo               | 2         | 3.28%   |
| ASUSTek Computer     | 2         | 3.28%   |
| Acer                 | 2         | 3.28%   |
| Xiaomi               | 1         | 1.64%   |
| Unknown              | 1         | 1.64%   |
| Toshiba              | 1         | 1.64%   |
| Sharp                | 1         | 1.64%   |
| Panasonic            | 1         | 1.64%   |
| ONN                  | 1         | 1.64%   |
| NEC Computers        | 1         | 1.64%   |
| JVC                  | 1         | 1.64%   |
| Iiyama               | 1         | 1.64%   |
| Gigabyte Technology  | 1         | 1.64%   |
| Eizo                 | 1         | 1.64%   |
| DPC                  | 1         | 1.64%   |
| Ancor Communications | 1         | 1.64%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 2         | 3.17%   |
| Xiaomi Mi TV XMD009A 3440x1440 480x270mm 21.7-inch                   | 1         | 1.59%   |
| ViewSonic LCD Monitor VX2276 Series 1920x1080                        | 1         | 1.59%   |
| ViewSonic LCD Monitor VA2448 SERIES 1920x1080                        | 1         | 1.59%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch            | 1         | 1.59%   |
| Toshiba TV TSB0206 1920x1080 886x498mm 40.0-inch                     | 1         | 1.59%   |
| Sharp LCD Monitor SHP14C4 1920x1080 344x194mm 15.5-inch              | 1         | 1.59%   |
| Samsung Electronics SyncMaster SAM0578 1920x1080 476x268mm 21.5-inch | 1         | 1.59%   |
| Samsung Electronics SyncMaster SAM0428 1680x1050 459x296mm 21.5-inch | 1         | 1.59%   |
| Samsung Electronics SMB2430L SAM0644 1920x1080 521x293mm 23.5-inch   | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 340x190mm 15.3-inch | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 353x198mm 15.9-inch | 1         | 1.59%   |
| Panasonic TDM13O56 MEI96A2 3000x2000 285x190mm 13.5-inch             | 1         | 1.59%   |
| ONN 100002480 ONN0101 1920x1080 470x290mm 21.7-inch                  | 1         | 1.59%   |
| NEC Computers LCD2490WUXi NEC66CE 1920x1200 518x324mm 24.1-inch      | 1         | 1.59%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch         | 1         | 1.59%   |
| LG Display LCD Monitor LGD0508 1366x768 309x174mm 14.0-inch          | 1         | 1.59%   |
| LG Display LCD Monitor LGD03D7 1366x768 310x174mm 14.0-inch          | 1         | 1.59%   |
| LG Display LCD Monitor LGD0353 1366x768 345x194mm 15.6-inch          | 1         | 1.59%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch          | 1         | 1.59%   |
| LG Display LCD Monitor LGD02D9 1920x1080 344x194mm 15.5-inch         | 1         | 1.59%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch             | 1         | 1.59%   |
| Lenovo LCD Monitor LEN4035 1280x800 303x189mm 14.1-inch              | 1         | 1.59%   |
| JVC FPDEUFT3 JVC21BE 1920x540                                        | 1         | 1.59%   |
| Iiyama PLE2207WS IVM5609 1680x1050 465x291mm 21.6-inch               | 1         | 1.59%   |
| Hewlett-Packard ZR2740w HWP2957 2560x1440 597x336mm 27.0-inch        | 1         | 1.59%   |
| Hewlett-Packard LE1851w HWP2840 1366x768 413x234mm 18.7-inch         | 1         | 1.59%   |
| Hewlett-Packard 2309 HWP2823 1920x1080 510x287mm 23.0-inch           | 1         | 1.59%   |
| Goldstar W2242 GSM5678 1680x1050 474x296mm 22.0-inch                 | 1         | 1.59%   |
| Goldstar W2242 GSM5677 1680x1050 474x296mm 22.0-inch                 | 1         | 1.59%   |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                  | 1         | 1.59%   |
| Goldstar FULL HD GSM5ABA 1920x1080 480x270mm 21.7-inch               | 1         | 1.59%   |
| Goldstar BK750Y GSM5B3E 1920x1080 600x340mm 27.2-inch                | 1         | 1.59%   |
| Goldstar BK750Y GSM5B3D 1920x1080 480x270mm 21.7-inch                | 1         | 1.59%   |
| Gigabyte Technology G27Q GBT2709 2560x1440 600x330mm 27.0-inch       | 1         | 1.59%   |
| Eizo M1700 ENC1788 1280x1024 338x271mm 17.1-inch                     | 1         | 1.59%   |
| DPC Qumi Q38 DPC81F2 1920x1200 708x398mm 32.0-inch                   | 1         | 1.59%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 1         | 1.59%   |
| Dell LCD Monitor U2312HM 1920x1080                                   | 1         | 1.59%   |
| Dell E176FP DELA014 1280x1024 338x270mm 17.0-inch                    | 1         | 1.59%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 29        | 48.33%  |
| 1366x768 (WXGA)    | 12        | 20%     |
| 1280x1024 (SXGA)   | 4         | 6.67%   |
| 1680x1050 (WSXGA+) | 3         | 5%      |
| 3840x2160 (4K)     | 2         | 3.33%   |
| 2560x1440 (QHD)    | 2         | 3.33%   |
| 1920x1200 (WUXGA)  | 2         | 3.33%   |
| 1600x900 (HD+)     | 2         | 3.33%   |
| 3440x1440          | 1         | 1.67%   |
| 2288x1287          | 1         | 1.67%   |
| 1920x540           | 1         | 1.67%   |
| 1280x800 (WXGA)    | 1         | 1.67%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 13        | 20.97%  |
| 21      | 8         | 12.9%   |
| 24      | 6         | 9.68%   |
| 14      | 6         | 9.68%   |
| 17      | 5         | 8.06%   |
| 27      | 4         | 6.45%   |
| 23      | 4         | 6.45%   |
| 13      | 4         | 6.45%   |
| Unknown | 4         | 6.45%   |
| 142     | 1         | 1.61%   |
| 74      | 1         | 1.61%   |
| 32      | 1         | 1.61%   |
| 22      | 1         | 1.61%   |
| 20      | 1         | 1.61%   |
| 19      | 1         | 1.61%   |
| 18      | 1         | 1.61%   |
| 12      | 1         | 1.61%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 24        | 38.71%  |
| 501-600        | 13        | 20.97%  |
| 401-500        | 12        | 19.35%  |
| 351-400        | 4         | 6.45%   |
| Unknown        | 4         | 6.45%   |
| 201-300        | 2         | 3.23%   |
| More than 2000 | 1         | 1.61%   |
| 701-800        | 1         | 1.61%   |
| 1501-2000      | 1         | 1.61%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 41        | 70.69%  |
| 16/10   | 6         | 10.34%  |
| Unknown | 3         | 5.17%   |
| 6/5     | 2         | 3.45%   |
| 5/4     | 2         | 3.45%   |
| 3/2     | 2         | 3.45%   |
| 32/9    | 1         | 1.72%   |
| 1.00    | 1         | 1.72%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 15        | 24.59%  |
| 101-110        | 13        | 21.31%  |
| 81-90          | 9         | 14.75%  |
| 301-350        | 4         | 6.56%   |
| 141-150        | 4         | 6.56%   |
| Unknown        | 4         | 6.56%   |
| 251-300        | 3         | 4.92%   |
| More than 1000 | 2         | 3.28%   |
| 151-200        | 2         | 3.28%   |
| 121-130        | 2         | 3.28%   |
| 71-80          | 1         | 1.64%   |
| 61-70          | 1         | 1.64%   |
| 351-500        | 1         | 1.64%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 22        | 35.48%  |
| 101-120       | 18        | 29.03%  |
| 121-160       | 14        | 22.58%  |
| Unknown       | 4         | 6.45%   |
| More than 240 | 2         | 3.23%   |
| 1-50          | 2         | 3.23%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 44        | 70.97%  |
| 2     | 8         | 12.9%   |
| 0     | 8         | 12.9%   |
| 3     | 2         | 3.23%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 38        | 42.22%  |
| Realtek Semiconductor    | 28        | 31.11%  |
| Qualcomm Atheros         | 8         | 8.89%   |
| Broadcom                 | 3         | 3.33%   |
| Ralink Technology        | 2         | 2.22%   |
| VIA Technologies         | 1         | 1.11%   |
| TP-Link                  | 1         | 1.11%   |
| Sierra Wireless          | 1         | 1.11%   |
| Ralink                   | 1         | 1.11%   |
| Nvidia                   | 1         | 1.11%   |
| Micro Star International | 1         | 1.11%   |
| Mellanox Technologies    | 1         | 1.11%   |
| Dell                     | 1         | 1.11%   |
| Chelsio Communications   | 1         | 1.11%   |
| Broadcom Limited         | 1         | 1.11%   |
| ASIX Electronics         | 1         | 1.11%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 19        | 17.27%  |
| Intel I211 Gigabit Network Connection                                                 | 6         | 5.45%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 5         | 4.55%   |
| Intel 82574L Gigabit Network Connection                                               | 4         | 3.64%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 3         | 2.73%   |
| Intel Wireless-AC 9260                                                                | 3         | 2.73%   |
| Intel Wireless 7260                                                                   | 3         | 2.73%   |
| Intel Ethernet Connection (2) I218-V                                                  | 3         | 2.73%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 3         | 2.73%   |
| Ralink MT7601U Wireless Adapter                                                       | 2         | 1.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 2         | 1.82%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                             | 2         | 1.82%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                        | 2         | 1.82%   |
| Intel Wireless 8265 / 8275                                                            | 2         | 1.82%   |
| Intel Wireless 8260                                                                   | 2         | 1.82%   |
| Intel Wireless 7265                                                                   | 2         | 1.82%   |
| Intel Wireless 3160                                                                   | 2         | 1.82%   |
| Intel Ethernet Connection I217-V                                                      | 2         | 1.82%   |
| Intel Ethernet Connection (2) I219-LM                                                 | 2         | 1.82%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 2         | 1.82%   |
| VIA VT6105/VT6106S [Rhine-III]                                                        | 1         | 0.91%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                                                 | 1         | 0.91%   |
| Sierra Wireless EM7305                                                                | 1         | 0.91%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                       | 1         | 0.91%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1         | 0.91%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                              | 1         | 0.91%   |
| Realtek RTL8125 2.5GbE Controller                                                     | 1         | 0.91%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                             | 1         | 0.91%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                      | 1         | 0.91%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 1         | 0.91%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                         | 1         | 0.91%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 0.91%   |
| Nvidia MCP61 Ethernet                                                                 | 1         | 0.91%   |
| Micro Star International MS-3871 802.11bgn Wireless Module [Ralink RT8070]            | 1         | 0.91%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]                                 | 1         | 0.91%   |
| Intel WiFi Link 5100                                                                  | 1         | 0.91%   |
| Intel Wi-Fi 6 AX200                                                                   | 1         | 0.91%   |
| Intel I350 Gigabit Network Connection                                                 | 1         | 0.91%   |
| Intel Gemini Lake PCH CNVi WiFi                                                       | 1         | 0.91%   |
| Intel Ethernet Connection I219-LM                                                     | 1         | 0.91%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 22        | 55%     |
| Realtek Semiconductor    | 5         | 12.5%   |
| Qualcomm Atheros         | 5         | 12.5%   |
| Ralink Technology        | 2         | 5%      |
| TP-Link                  | 1         | 2.5%    |
| Sierra Wireless          | 1         | 2.5%    |
| Ralink                   | 1         | 2.5%    |
| Micro Star International | 1         | 2.5%    |
| Dell                     | 1         | 2.5%    |
| Broadcom                 | 1         | 2.5%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8188EE Wireless Network Adapter                                            | 3         | 7.5%    |
| Intel Wireless-AC 9260                                                                | 3         | 7.5%    |
| Intel Wireless 7260                                                                   | 3         | 7.5%    |
| Ralink MT7601U Wireless Adapter                                                       | 2         | 5%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 2         | 5%      |
| Intel Wireless 8265 / 8275                                                            | 2         | 5%      |
| Intel Wireless 8260                                                                   | 2         | 5%      |
| Intel Wireless 7265                                                                   | 2         | 5%      |
| Intel Wireless 3160                                                                   | 2         | 5%      |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 2         | 5%      |
| TP-Link RTL8812AU Archer T4U 802.11ac                                                 | 1         | 2.5%    |
| Sierra Wireless EM7305                                                                | 1         | 2.5%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                       | 1         | 2.5%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1         | 2.5%    |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                             | 1         | 2.5%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                      | 1         | 2.5%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 1         | 2.5%    |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 2.5%    |
| Micro Star International MS-3871 802.11bgn Wireless Module [Ralink RT8070]            | 1         | 2.5%    |
| Intel WiFi Link 5100                                                                  | 1         | 2.5%    |
| Intel Wi-Fi 6 AX200                                                                   | 1         | 2.5%    |
| Intel Gemini Lake PCH CNVi WiFi                                                       | 1         | 2.5%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1         | 2.5%    |
| Intel Centrino Ultimate-N 6300                                                        | 1         | 2.5%    |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 1         | 2.5%    |
| Dell DW5811e Snapdragonâ¢ X7 LTE                                                  | 1         | 2.5%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 1         | 2.5%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Realtek Semiconductor  | 25        | 39.68%  |
| Intel                  | 25        | 39.68%  |
| Qualcomm Atheros       | 5         | 7.94%   |
| Broadcom               | 2         | 3.17%   |
| VIA Technologies       | 1         | 1.59%   |
| Nvidia                 | 1         | 1.59%   |
| Mellanox Technologies  | 1         | 1.59%   |
| Chelsio Communications | 1         | 1.59%   |
| Broadcom Limited       | 1         | 1.59%   |
| ASIX Electronics       | 1         | 1.59%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 19        | 27.14%  |
| Intel I211 Gigabit Network Connection                                         | 6         | 8.57%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 5         | 7.14%   |
| Intel 82574L Gigabit Network Connection                                       | 4         | 5.71%   |
| Intel Ethernet Connection (2) I218-V                                          | 3         | 4.29%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 3         | 4.29%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 2         | 2.86%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 2         | 2.86%   |
| Intel Ethernet Connection I217-V                                              | 2         | 2.86%   |
| Intel Ethernet Connection (2) I219-LM                                         | 2         | 2.86%   |
| VIA VT6105/VT6106S [Rhine-III]                                                | 1         | 1.43%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 1         | 1.43%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1         | 1.43%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1         | 1.43%   |
| Nvidia MCP61 Ethernet                                                         | 1         | 1.43%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]                         | 1         | 1.43%   |
| Intel I350 Gigabit Network Connection                                         | 1         | 1.43%   |
| Intel Ethernet Connection I219-LM                                             | 1         | 1.43%   |
| Intel Ethernet Connection I218-V                                              | 1         | 1.43%   |
| Intel Ethernet Connection (7) I219-V                                          | 1         | 1.43%   |
| Intel Ethernet Connection (4) I219-V                                          | 1         | 1.43%   |
| Intel Ethernet Connection (3) I218-LM                                         | 1         | 1.43%   |
| Intel Ethernet Connection (10) I219-V                                         | 1         | 1.43%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 1         | 1.43%   |
| Intel 82579V Gigabit Network Connection                                       | 1         | 1.43%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 1.43%   |
| Intel 82567LM Gigabit Network Connection                                      | 1         | 1.43%   |
| Chelsio T320 10GbE Dual Port Adapter                                          | 1         | 1.43%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                             | 1         | 1.43%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                       | 1         | 1.43%   |
| Broadcom Limited NetXtreme BCM5756ME Gigabit Ethernet PCI Express             | 1         | 1.43%   |
| ASIX AX88772B                                                                 | 1         | 1.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 58        | 61.05%  |
| WiFi     | 37        | 38.95%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 36        | 65.45%  |
| WiFi     | 19        | 34.55%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 34        | 54.84%  |
| 1     | 17        | 27.42%  |
| 3     | 4         | 6.45%   |
| 0     | 4         | 6.45%   |
| 4     | 2         | 3.23%   |
| 5     | 1         | 1.61%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 58        | 93.55%  |
| Yes  | 4         | 6.45%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


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

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


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

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 43        | 55.84%  |
| AMD                 | 17        | 22.08%  |
| Nvidia              | 10        | 12.99%  |
| Creative Labs       | 3         | 3.9%    |
| C-Media Electronics | 2         | 2.6%    |
| Texas Instruments   | 1         | 1.3%    |
| EGO SYStems         | 1         | 1.3%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 6         | 6.12%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 5         | 5.1%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 4.08%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 4         | 4.08%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 3.06%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 3.06%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 3         | 3.06%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 3.06%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 3         | 3.06%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 3.06%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 3         | 3.06%   |
| AMD FCH Azalia Controller                                                                         | 3         | 3.06%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 3         | 3.06%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 3         | 3.06%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 3         | 3.06%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 2.04%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 2         | 2.04%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 2.04%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 2.04%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 2.04%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 2.04%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 2.04%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 2.04%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 2.04%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 2.04%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 1.02%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 1.02%   |
| Nvidia MCP61 High Definition Audio                                                                | 1         | 1.02%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1         | 1.02%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 1.02%   |
| Nvidia GK110 High Definition Audio Controller                                                     | 1         | 1.02%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 1.02%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 1.02%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 1.02%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 1.02%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 1         | 1.02%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1         | 1.02%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 1.02%   |
| Intel 200 Series PCH HD Audio                                                                     | 1         | 1.02%   |
| EGO SYStems U24XL                                                                                 | 1         | 1.02%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 13        | 20.97%  |
| Samsung Electronics | 9         | 14.52%  |
| Kingston            | 8         | 12.9%   |
| Corsair             | 7         | 11.29%  |
| Crucial             | 6         | 9.68%   |
| Unknown             | 5         | 8.06%   |
| Micron Technology   | 4         | 6.45%   |
| Team                | 2         | 3.23%   |
| Transcend           | 1         | 1.61%   |
| Smart               | 1         | 1.61%   |
| Ramaxel Technology  | 1         | 1.61%   |
| HPE                 | 1         | 1.61%   |
| Elpida              | 1         | 1.61%   |
| Avant               | 1         | 1.61%   |
| AMD                 | 1         | 1.61%   |
| A Force             | 1         | 1.61%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 2.94%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s       | 2         | 2.94%   |
| Unknown RAM Module 4096MB DIMM DDR3 65535MT/s                | 1         | 1.47%   |
| Unknown RAM Module 2048MB DIMM SDRAM                         | 1         | 1.47%   |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s                   | 1         | 1.47%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                       | 1         | 1.47%   |
| Unknown RAM Module 1024MB SODIMM SDRAM                       | 1         | 1.47%   |
| Unknown RAM Module 1024MB DIMM DDR 800MT/s                   | 1         | 1.47%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                       | 1         | 1.47%   |
| Transcend RAM TS256MLQ72V6U 2GB DIMM DDR2 667MT/s            | 1         | 1.47%   |
| Team RAM TEAMGROUP-UD4-3600 32GB DIMM DDR4 3600MT/s          | 1         | 1.47%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3200MT/s           | 1         | 1.47%   |
| Smart RAM SH5641G8FJ8NWRNSQG 8GB SODIMM DDR3 1600MT/s        | 1         | 1.47%   |
| SK hynix RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s      | 1         | 1.47%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s              | 1         | 1.47%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s        | 1         | 1.47%   |
| SK hynix RAM HMT41GU6BFR8A-PB 8192MB DIMM DDR3 2000MT/s      | 1         | 1.47%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 1.47%   |
| SK hynix RAM HMT351R7CFR8A-H9 4096MB DIMM DDR3 1333MT/s      | 1         | 1.47%   |
| SK hynix RAM HMT31GR7EFR4A 8192MB DIMM DDR3 1600MT/s         | 1         | 1.47%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s       | 1         | 1.47%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s    | 1         | 1.47%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s        | 1         | 1.47%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 1         | 1.47%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s        | 1         | 1.47%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 1.47%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 1.47%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 1         | 1.47%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s        | 1         | 1.47%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s       | 1         | 1.47%   |
| Samsung RAM M393B5273DH0-CK0 4GB DIMM DDR3 1600MT/s          | 1         | 1.47%   |
| Ramaxel RAM RMSA3260MH78HAF-2666 8192MB SODIMM DDR4 2667MT/s | 1         | 1.47%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s        | 1         | 1.47%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s        | 1         | 1.47%   |
| Micron RAM 36KSF1G72PZ-1G4K1 8192MB DIMM DDR3 1333MT/s       | 1         | 1.47%   |
| Micron RAM 18JSF1G72PZ-1G9E1 8GB DIMM DDR3 1866MT/s          | 1         | 1.47%   |
| Micron RAM 16JTF51264AZ-1G6M1 4GB DIMM DDR3 1600MT/s         | 1         | 1.47%   |
| Kingston RAM KHX3600C17D4/8GX 8GB DIMM DDR4 3600MT/s         | 1         | 1.47%   |
| Kingston RAM KHX2666C15S4/8G 8GB SODIMM DDR4 2667MT/s        | 1         | 1.47%   |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s      | 1         | 1.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 25        | 44.64%  |
| DDR4    | 21        | 37.5%   |
| SDRAM   | 3         | 5.36%   |
| LPDDR4  | 2         | 3.57%   |
| DDR2    | 2         | 3.57%   |
| LPDDR3  | 1         | 1.79%   |
| DDR     | 1         | 1.79%   |
| Unknown | 1         | 1.79%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 31        | 55.36%  |
| SODIMM       | 24        | 42.86%  |
| Row Of Chips | 1         | 1.79%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 25        | 41.67%  |
| 4096  | 17        | 28.33%  |
| 16384 | 6         | 10%     |
| 2048  | 6         | 10%     |
| 32768 | 3         | 5%      |
| 1024  | 3         | 5%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 17        | 28.33%  |
| 2667    | 10        | 16.67%  |
| 2400    | 6         | 10%     |
| 3600    | 3         | 5%      |
| 3200    | 3         | 5%      |
| 1333    | 3         | 5%      |
| 667     | 3         | 5%      |
| 2666    | 2         | 3.33%   |
| 2133    | 2         | 3.33%   |
| 1867    | 2         | 3.33%   |
| Unknown | 2         | 3.33%   |
| 65535   | 1         | 1.67%   |
| 4199    | 1         | 1.67%   |
| 2000    | 1         | 1.67%   |
| 1866    | 1         | 1.67%   |
| 1334    | 1         | 1.67%   |
| 975     | 1         | 1.67%   |
| 800     | 1         | 1.67%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 2         | 40%     |
| Brother Industries | 2         | 40%     |
| Dell               | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


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

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model           | Computers | Percent |
|-----------------|-----------|---------|
| HP ScanJet 5590 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


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

![Camera Model](./All/images/pie_chart/camera_model.svg)


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

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 3         | 50%     |
| Synaptics             | 1         | 16.67%  |
| LighTuning Technology | 1         | 16.67%  |
| Elan Microelectronics | 1         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


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

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 2         | 33.33%  |
| Alcor Micro           | 2         | 33.33%  |
| O2 Micro              | 1         | 16.67%  |
| Gemalto (was Gemplus) | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


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

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 34        | 53.13%  |
| 1     | 13        | 20.31%  |
| 2     | 9         | 14.06%  |
| 3     | 5         | 7.81%   |
| 4     | 3         | 4.69%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


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

