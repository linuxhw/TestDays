Slackware - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for Slackware.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 71

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| HP        | Pavilion Gaming Laptop 1... | [bd2dda1d8a](https://linux-hardware.org/?probe=bd2dda1d8a) | Apr 29, 2022 |
| HP        | Pavilion Gaming Laptop 1... | [cfc9c5dbf7](https://linux-hardware.org/?probe=cfc9c5dbf7) | Apr 29, 2022 |
| MSI       | GP76 Leopard 11UG           | [aebd373a66](https://linux-hardware.org/?probe=aebd373a66) | Apr 12, 2022 |
| MSI       | GE76 Raider 11UE            | [3072e065a3](https://linux-hardware.org/?probe=3072e065a3) | Apr 12, 2022 |
| Notebook  | X170KM-G                    | [4ecba03d19](https://linux-hardware.org/?probe=4ecba03d19) | Apr 11, 2022 |
| Dell      | Latitude 3520               | [4398aa2a03](https://linux-hardware.org/?probe=4398aa2a03) | Apr 06, 2022 |
| HP        | ProBook 6570b               | [cf1305eacc](https://linux-hardware.org/?probe=cf1305eacc) | Apr 06, 2022 |
| Lenovo    | IdeaPad 310-15ISK 80SM      | [d406cb4819](https://linux-hardware.org/?probe=d406cb4819) | Apr 05, 2022 |
| Dell      | Precision M4700             | [ab99532bd5](https://linux-hardware.org/?probe=ab99532bd5) | Apr 04, 2022 |
| Lenovo    | ThinkPad X230 2325P38       | [1a0cab737b](https://linux-hardware.org/?probe=1a0cab737b) | Mar 10, 2022 |
| ASUSTek   | ROG Zephyrus G14 GA401IV... | [0b0c1aca1b](https://linux-hardware.org/?probe=0b0c1aca1b) | Mar 10, 2022 |
| HP        | Pavilion Gaming Laptop 1... | [c7825c54fc](https://linux-hardware.org/?probe=c7825c54fc) | Mar 10, 2022 |
| Framework | Laptop                      | [ae37705198](https://linux-hardware.org/?probe=ae37705198) | Mar 10, 2022 |
| Lenovo    | ThinkPad Edge E530c 3366... | [8ce0419468](https://linux-hardware.org/?probe=8ce0419468) | Feb 13, 2022 |
| Dynabook  | P1-C7MP-BL                  | [268f94787e](https://linux-hardware.org/?probe=268f94787e) | Jan 14, 2022 |
| HP        | Laptop 15-bs2xx             | [bf53c3c878](https://linux-hardware.org/?probe=bf53c3c878) | Jan 02, 2022 |
| HP        | Laptop 15-bs1xx             | [b6c9f34c4c](https://linux-hardware.org/?probe=b6c9f34c4c) | Dec 07, 2021 |
| HP        | Laptop 15-da0xxx            | [2e3e23fb54](https://linux-hardware.org/?probe=2e3e23fb54) | Nov 01, 2021 |
| System76  | Oryx Pro                    | [3cd05d02a8](https://linux-hardware.org/?probe=3cd05d02a8) | Oct 27, 2021 |
| MSI       | Modern 14 B11MO             | [e8f13facfd](https://linux-hardware.org/?probe=e8f13facfd) | Oct 03, 2021 |
| MSI       | Modern 14 B11MO             | [9f5c2e0fde](https://linux-hardware.org/?probe=9f5c2e0fde) | Sep 27, 2021 |
| Toshiba   | PORTEGE Z30-A               | [13b9ce0773](https://linux-hardware.org/?probe=13b9ce0773) | Sep 22, 2021 |
| Dynabook  | dynabook PORTEGE X50-G      | [da8279a7a9](https://linux-hardware.org/?probe=da8279a7a9) | Sep 22, 2021 |
| Dell      | Inspiron 15-3552            | [f76339b0af](https://linux-hardware.org/?probe=f76339b0af) | Aug 31, 2021 |
| HP        | 245 G7 Notebook PC          | [c0806e4955](https://linux-hardware.org/?probe=c0806e4955) | Aug 23, 2021 |
| HP        | 245 G7 Notebook PC          | [c409287d23](https://linux-hardware.org/?probe=c409287d23) | Aug 23, 2021 |
| HP        | EliteBook 840 G5            | [4c196e1abd](https://linux-hardware.org/?probe=4c196e1abd) | Aug 18, 2021 |
| Dell      | Vostro 3500                 | [53a1179121](https://linux-hardware.org/?probe=53a1179121) | Aug 12, 2021 |
| HP        | EliteBook Folio 1020 G1 ... | [32e6ec699f](https://linux-hardware.org/?probe=32e6ec699f) | Aug 09, 2021 |
| HP        | EliteBook Folio 1020 G1 ... | [7facd0568b](https://linux-hardware.org/?probe=7facd0568b) | Aug 09, 2021 |
| HP        | 15 Notebook PC              | [bec2fe2e78](https://linux-hardware.org/?probe=bec2fe2e78) | Mar 21, 2021 |
| Toshiba   | Satellite C660              | [5189fbc4c9](https://linux-hardware.org/?probe=5189fbc4c9) | Mar 10, 2021 |
| Samsung   | 300E5M/300E5L               | [bda4ee984f](https://linux-hardware.org/?probe=bda4ee984f) | Mar 05, 2021 |
| Dell      | Latitude E5500              | [a8e17b79ce](https://linux-hardware.org/?probe=a8e17b79ce) | Feb 26, 2021 |
| HP        | Pavilion Notebook           | [45dfe3c2b1](https://linux-hardware.org/?probe=45dfe3c2b1) | Feb 24, 2021 |
| Lenovo    | ThinkPad L440 20ASS05K00    | [aecef5c789](https://linux-hardware.org/?probe=aecef5c789) | Jan 22, 2021 |
| Lenovo    | ThinkPad L440 20ASS05K00    | [7a6a06bb55](https://linux-hardware.org/?probe=7a6a06bb55) | Jan 04, 2021 |
| Dell      | Precision M4600             | [71bb8e2e9a](https://linux-hardware.org/?probe=71bb8e2e9a) | Dec 28, 2020 |
| Lenovo    | ThinkPad L440 20ASS05K00    | [b330b2d38a](https://linux-hardware.org/?probe=b330b2d38a) | Nov 19, 2020 |
| Lenovo    | ThinkPad L440 20ASS05K00    | [416d54b307](https://linux-hardware.org/?probe=416d54b307) | Nov 17, 2020 |
| MSI       | GL73 8RC                    | [44f82bfc01](https://linux-hardware.org/?probe=44f82bfc01) | Nov 09, 2020 |
| Lenovo    | ThinkPad L440 20ASS05K00    | [9c79f4e7b9](https://linux-hardware.org/?probe=9c79f4e7b9) | Nov 08, 2020 |
| Lenovo    | ThinkPad L440 20ASS05K00    | [a4cb1ecf16](https://linux-hardware.org/?probe=a4cb1ecf16) | Nov 08, 2020 |
| Samsung   | 300E5M/300E5L               | [270b65ced8](https://linux-hardware.org/?probe=270b65ced8) | Jul 24, 2020 |
| Notebook  | NL40_50CU                   | [941073da73](https://linux-hardware.org/?probe=941073da73) | Jun 27, 2020 |
| Lenovo    | V330-14ARR 81B1             | [5089cbcf84](https://linux-hardware.org/?probe=5089cbcf84) | Jun 24, 2020 |
| Lenovo    | V330-14ARR 81B1             | [cb63994f94](https://linux-hardware.org/?probe=cb63994f94) | Jun 22, 2020 |
| Notebook  | NL40_50CU                   | [9a1c09c6e1](https://linux-hardware.org/?probe=9a1c09c6e1) | Mar 28, 2020 |
| Notebook  | NL40_50CU                   | [bc5ed8dea4](https://linux-hardware.org/?probe=bc5ed8dea4) | Mar 24, 2020 |
| Notebook  | NL40_50CU                   | [ae7070b067](https://linux-hardware.org/?probe=ae7070b067) | Mar 21, 2020 |
| Notebook  | NL40_50CU                   | [320dada481](https://linux-hardware.org/?probe=320dada481) | Mar 20, 2020 |
| Toshiba   | Satellite P50-A-12Z         | [96927db16b](https://linux-hardware.org/?probe=96927db16b) | Mar 17, 2020 |
| Lenovo    | ThinkPad X1 Carbon 7th 2... | [afe3135216](https://linux-hardware.org/?probe=afe3135216) | Dec 10, 2019 |
| ASUSTek   | P53E                        | [e9dcced0f7](https://linux-hardware.org/?probe=e9dcced0f7) | Oct 28, 2019 |
| Lenovo    | ThinkPad T400 6474BV7       | [825bdb9fd0](https://linux-hardware.org/?probe=825bdb9fd0) | Oct 28, 2019 |
| ASUSTek   | 1000H                       | [50da35c0d0](https://linux-hardware.org/?probe=50da35c0d0) | Oct 28, 2019 |
| Acer      | Aspire E1-572               | [0fe80f5758](https://linux-hardware.org/?probe=0fe80f5758) | Oct 23, 2019 |
| ASUSTek   | VivoBook_ASUSLaptop X570... | [ecca7bced0](https://linux-hardware.org/?probe=ecca7bced0) | Oct 22, 2019 |
| ASUSTek   | VivoBook_ASUSLaptop X570... | [e1cfaedc22](https://linux-hardware.org/?probe=e1cfaedc22) | Oct 22, 2019 |
| ASUSTek   | VivoBook_ASUSLaptop X570... | [c7637c27a6](https://linux-hardware.org/?probe=c7637c27a6) | Oct 22, 2019 |
| Lenovo    | IdeaPad P500 20210          | [3d09c5e38d](https://linux-hardware.org/?probe=3d09c5e38d) | Oct 22, 2019 |
| Acer      | Swift SF314-52              | [05f880ecec](https://linux-hardware.org/?probe=05f880ecec) | Oct 21, 2019 |
| Lenovo    | ThinkPad P70 20ERCTO1WW     | [0ceeb50e5e](https://linux-hardware.org/?probe=0ceeb50e5e) | Oct 21, 2019 |
| Lenovo    | ThinkPad T450s 20BW000EU... | [41ca8d1a20](https://linux-hardware.org/?probe=41ca8d1a20) | Oct 21, 2019 |
| ASUSTek   | VivoBook_ASUSLaptop X570... | [c2fd6acb71](https://linux-hardware.org/?probe=c2fd6acb71) | Oct 21, 2019 |
| Dell      | Latitude E7270              | [859e021e2f](https://linux-hardware.org/?probe=859e021e2f) | Oct 20, 2019 |
| Fujitsu   | LIFEBOOK A555               | [e0c6729d5b](https://linux-hardware.org/?probe=e0c6729d5b) | Oct 20, 2019 |
| Lenovo    | ThinkPad T470 20HDCTO1WW    | [0f9287651d](https://linux-hardware.org/?probe=0f9287651d) | Jul 24, 2019 |
| Lenovo    | ThinkPad T470 20HDCTO1WW    | [6986d35989](https://linux-hardware.org/?probe=6986d35989) | Jul 23, 2019 |
| Lenovo    | ThinkPad T470 20HDCTO1WW    | [67672ef038](https://linux-hardware.org/?probe=67672ef038) | Jul 23, 2019 |
| Fujitsu   | LIFEBOOK A555               | [63c120aa28](https://linux-hardware.org/?probe=63c120aa28) | Aug 19, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| Slackware 14.2  | 26        | 52%     |
| Slackware 15.0  | 21        | 42%     |
| Slackware 14.2+ | 3         | 6%      |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| Slackware | 50        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.15.19           | 5         | 9.09%   |
| 4.19.80           | 4         | 7.27%   |
| 5.3.7             | 2         | 3.64%   |
| 5.17.1            | 2         | 3.64%   |
| 5.13.8            | 2         | 3.64%   |
| 5.7.0             | 1         | 1.82%   |
| 5.5.10            | 1         | 1.82%   |
| 5.4.75            | 1         | 1.82%   |
| 5.4.50            | 1         | 1.82%   |
| 5.4.47            | 1         | 1.82%   |
| 5.4.24toshiba-new | 1         | 1.82%   |
| 5.4.2             | 1         | 1.82%   |
| 5.4.139-jw        | 1         | 1.82%   |
| 5.4.13            | 1         | 1.82%   |
| 5.2.2             | 1         | 1.82%   |
| 5.17.2            | 1         | 1.82%   |
| 5.16.9-joe1       | 1         | 1.82%   |
| 5.16.12           | 1         | 1.82%   |
| 5.15.33.kjh       | 1         | 1.82%   |
| 5.15.27           | 1         | 1.82%   |
| 5.15.1            | 1         | 1.82%   |
| 5.14.9            | 1         | 1.82%   |
| 5.14.8            | 1         | 1.82%   |
| 5.14.10           | 1         | 1.82%   |
| 5.14.0            | 1         | 1.82%   |
| 5.13.5            | 1         | 1.82%   |
| 5.13.11           | 1         | 1.82%   |
| 5.13.0.a          | 1         | 1.82%   |
| 5.10.91           | 1         | 1.82%   |
| 5.10.4            | 1         | 1.82%   |
| 5.10.3            | 1         | 1.82%   |
| 5.10.21           | 1         | 1.82%   |
| 5.10.19           | 1         | 1.82%   |
| 5.10.1-pmagic     | 1         | 1.82%   |
| 4.4.88            | 1         | 1.82%   |
| 4.4.276           | 1         | 1.82%   |
| 4.4.240           | 1         | 1.82%   |
| 4.4.227           | 1         | 1.82%   |
| 4.4.202           | 1         | 1.82%   |
| 4.4.190-smp       | 1         | 1.82%   |
| 4.4.190           | 1         | 1.82%   |
| 4.19.79           | 1         | 1.82%   |
| 4.19.76           | 1         | 1.82%   |
| 4.19.206.a        | 1         | 1.82%   |
| 4.16.18           | 1         | 1.82%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.15.19  | 5         | 9.09%   |
| 4.19.80  | 4         | 7.27%   |
| 5.3.7    | 2         | 3.64%   |
| 5.17.1   | 2         | 3.64%   |
| 5.13.8   | 2         | 3.64%   |
| 4.4.190  | 2         | 3.64%   |
| 5.7.0    | 1         | 1.82%   |
| 5.5.10   | 1         | 1.82%   |
| 5.4.75   | 1         | 1.82%   |
| 5.4.50   | 1         | 1.82%   |
| 5.4.47   | 1         | 1.82%   |
| 5.4.24   | 1         | 1.82%   |
| 5.4.2    | 1         | 1.82%   |
| 5.4.139  | 1         | 1.82%   |
| 5.4.13   | 1         | 1.82%   |
| 5.2.2    | 1         | 1.82%   |
| 5.17.2   | 1         | 1.82%   |
| 5.16.9   | 1         | 1.82%   |
| 5.16.12  | 1         | 1.82%   |
| 5.15.33  | 1         | 1.82%   |
| 5.15.27  | 1         | 1.82%   |
| 5.15.1   | 1         | 1.82%   |
| 5.14.9   | 1         | 1.82%   |
| 5.14.8   | 1         | 1.82%   |
| 5.14.10  | 1         | 1.82%   |
| 5.14.0   | 1         | 1.82%   |
| 5.13.5   | 1         | 1.82%   |
| 5.13.11  | 1         | 1.82%   |
| 5.13.0   | 1         | 1.82%   |
| 5.10.91  | 1         | 1.82%   |
| 5.10.4   | 1         | 1.82%   |
| 5.10.3   | 1         | 1.82%   |
| 5.10.21  | 1         | 1.82%   |
| 5.10.19  | 1         | 1.82%   |
| 5.10.1   | 1         | 1.82%   |
| 4.4.88   | 1         | 1.82%   |
| 4.4.276  | 1         | 1.82%   |
| 4.4.240  | 1         | 1.82%   |
| 4.4.227  | 1         | 1.82%   |
| 4.4.202  | 1         | 1.82%   |
| 4.19.79  | 1         | 1.82%   |
| 4.19.76  | 1         | 1.82%   |
| 4.19.206 | 1         | 1.82%   |
| 4.16.18  | 1         | 1.82%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 8         | 14.81%  |
| 5.4     | 7         | 12.96%  |
| 4.4     | 7         | 12.96%  |
| 4.19    | 7         | 12.96%  |
| 5.10    | 6         | 11.11%  |
| 5.13    | 5         | 9.26%   |
| 5.17    | 3         | 5.56%   |
| 5.14    | 3         | 5.56%   |
| 5.3     | 2         | 3.7%    |
| 5.16    | 2         | 3.7%    |
| 5.7     | 1         | 1.85%   |
| 5.5     | 1         | 1.85%   |
| 5.2     | 1         | 1.85%   |
| 4.16    | 1         | 1.85%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 49        | 98%     |
| i686   | 1         | 2%      |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Unknown       | 16        | 31.37%  |
| XFCE          | 15        | 29.41%  |
| KDE5          | 13        | 25.49%  |
| KDE           | 3         | 5.88%   |
| xwmconfig     | 1         | 1.96%   |
| MATE          | 1         | 1.96%   |
| LXQt          | 1         | 1.96%   |
| Enlightenment | 1         | 1.96%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 41        | 80.39%  |
| Tty     | 8         | 15.69%  |
| Wayland | 2         | 3.92%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 23        | 45.1%   |
| SDDM    | 17        | 33.33%  |
| XDM     | 11        | 21.57%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 30        | 60%     |
| Unknown | 14        | 28%     |
| pt_BR   | 2         | 4%      |
| fr_FR   | 2         | 4%      |
| ru_RU   | 1         | 2%      |
| pl_PL   | 1         | 2%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 27        | 52.94%  |
| EFI  | 24        | 47.06%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 42        | 84%     |
| Btrfs   | 5         | 10%     |
| Overlay | 3         | 6%      |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 33        | 64.71%  |
| MBR     | 13        | 25.49%  |
| Unknown | 5         | 9.8%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 44        | 84.62%  |
| Yes       | 8         | 15.38%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 31        | 62%     |
| Yes       | 19        | 38%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 11        | 22%     |
| Hewlett-Packard     | 11        | 22%     |
| Dell                | 7         | 14%     |
| MSI                 | 4         | 8%      |
| ASUSTek Computer    | 4         | 8%      |
| Toshiba             | 3         | 6%      |
| Notebook            | 2         | 4%      |
| Dynabook            | 2         | 4%      |
| Acer                | 2         | 4%      |
| System76            | 1         | 2%      |
| Samsung Electronics | 1         | 2%      |
| Fujitsu             | 1         | 2%      |
| Framework           | 1         | 2%      |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Toshiba Satellite P50-A-12Z              | 1         | 2%      |
| Toshiba Satellite C660                   | 1         | 2%      |
| Toshiba PORTEGE Z30-A                    | 1         | 2%      |
| System76 Oryx Pro                        | 1         | 2%      |
| Samsung 300E5M/300E5L                    | 1         | 2%      |
| Notebook X170KM-G                        | 1         | 2%      |
| Notebook NL40_50CU                       | 1         | 2%      |
| MSI Modern 14 B11MO                      | 1         | 2%      |
| MSI GP76 Leopard 11UG                    | 1         | 2%      |
| MSI GL73 8RC                             | 1         | 2%      |
| MSI GE76 Raider 11UE                     | 1         | 2%      |
| Lenovo V330-14ARR 81B1                   | 1         | 2%      |
| Lenovo ThinkPad X230 2325P38             | 1         | 2%      |
| Lenovo ThinkPad X1 Carbon 7th 20R10015US | 1         | 2%      |
| Lenovo ThinkPad T470 20HDCTO1WW          | 1         | 2%      |
| Lenovo ThinkPad T450s 20BW000EUS         | 1         | 2%      |
| Lenovo ThinkPad T400 6474BV7             | 1         | 2%      |
| Lenovo ThinkPad P70 20ERCTO1WW           | 1         | 2%      |
| Lenovo ThinkPad L440 20ASS05K00          | 1         | 2%      |
| Lenovo ThinkPad Edge E530c 336669G       | 1         | 2%      |
| Lenovo IdeaPad P500 20210                | 1         | 2%      |
| Lenovo IdeaPad 310-15ISK 80SM            | 1         | 2%      |
| HP ProBook 6570b                         | 1         | 2%      |
| HP Pavilion Notebook                     | 1         | 2%      |
| HP Pavilion Gaming Laptop 16-a0xxx       | 1         | 2%      |
| HP Pavilion Gaming Laptop 15-ec1xxx      | 1         | 2%      |
| HP Laptop 15-da0xxx                      | 1         | 2%      |
| HP Laptop 15-bs2xx                       | 1         | 2%      |
| HP Laptop 15-bs1xx                       | 1         | 2%      |
| HP EliteBook Folio 1020 G1 SE            | 1         | 2%      |
| HP EliteBook 840 G5                      | 1         | 2%      |
| HP 245 G7 Notebook PC                    | 1         | 2%      |
| HP 15 Notebook PC                        | 1         | 2%      |
| Fujitsu LIFEBOOK A555                    | 1         | 2%      |
| Framework Laptop                         | 1         | 2%      |
| Dynabook P1-C7MP-BL                      | 1         | 2%      |
| Dynabook dynabook PORTEGE X50-G          | 1         | 2%      |
| Dell Vostro 3500                         | 1         | 2%      |
| Dell Precision M4700                     | 1         | 2%      |
| Dell Precision M4600                     | 1         | 2%      |
| Dell Latitude E7270                      | 1         | 2%      |
| Dell Latitude E5500                      | 1         | 2%      |
| Dell Latitude 3520                       | 1         | 2%      |
| Dell Inspiron 15-3552                    | 1         | 2%      |
| ASUS VivoBook_ASUSLaptop X570ZD_K570ZD   | 1         | 2%      |
| ASUS ROG Zephyrus G14 GA401IV_GA401IV    | 1         | 2%      |
| ASUS P53E                                | 1         | 2%      |
| ASUS 1000H                               | 1         | 2%      |
| Acer Swift SF314-52                      | 1         | 2%      |
| Acer Aspire E1-572                       | 1         | 2%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 8         | 16%     |
| HP Pavilion         | 3         | 6%      |
| HP Laptop           | 3         | 6%      |
| Dell Latitude       | 3         | 6%      |
| Toshiba Satellite   | 2         | 4%      |
| Lenovo IdeaPad      | 2         | 4%      |
| HP EliteBook        | 2         | 4%      |
| Dell Precision      | 2         | 4%      |
| Toshiba PORTEGE     | 1         | 2%      |
| System76 Oryx       | 1         | 2%      |
| Samsung 300E5M      | 1         | 2%      |
| Notebook X170KM-G   | 1         | 2%      |
| Notebook NL40       | 1         | 2%      |
| MSI Modern          | 1         | 2%      |
| MSI GP76            | 1         | 2%      |
| MSI GL73            | 1         | 2%      |
| MSI GE76            | 1         | 2%      |
| Lenovo V330-14ARR   | 1         | 2%      |
| HP ProBook          | 1         | 2%      |
| HP 245              | 1         | 2%      |
| HP 15               | 1         | 2%      |
| Fujitsu LIFEBOOK    | 1         | 2%      |
| Framework Laptop    | 1         | 2%      |
| Dynabook P1-C7MP-BL | 1         | 2%      |
| Dynabook dynabook   | 1         | 2%      |
| Dell Vostro         | 1         | 2%      |
| Dell Inspiron       | 1         | 2%      |
| ASUS VivoBook       | 1         | 2%      |
| ASUS ROG            | 1         | 2%      |
| ASUS P53E           | 1         | 2%      |
| ASUS 1000H          | 1         | 2%      |
| Acer Swift          | 1         | 2%      |
| Acer Aspire         | 1         | 2%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 7         | 14%     |
| 2021 | 6         | 12%     |
| 2019 | 5         | 10%     |
| 2015 | 5         | 10%     |
| 2012 | 5         | 10%     |
| 2018 | 4         | 8%      |
| 2017 | 4         | 8%      |
| 2016 | 3         | 6%      |
| 2014 | 3         | 6%      |
| 2008 | 3         | 6%      |
| 2011 | 2         | 4%      |
| 2010 | 2         | 4%      |
| 2013 | 1         | 2%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 50        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 50        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 47        | 94%     |
| Yes  | 3         | 6%      |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 15        | 30%     |
| 3.01-4.0    | 10        | 20%     |
| 8.01-16.0   | 10        | 20%     |
| 16.01-24.0  | 8         | 16%     |
| 32.01-64.0  | 3         | 6%      |
| 24.01-32.0  | 1         | 2%      |
| 64.01-256.0 | 1         | 2%      |
| 1.01-2.0    | 1         | 2%      |
| 0.51-1.0    | 1         | 2%      |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 18        | 34.62%  |
| 2.01-3.0   | 15        | 28.85%  |
| 4.01-8.0   | 8         | 15.38%  |
| 3.01-4.0   | 4         | 7.69%   |
| 0.51-1.0   | 3         | 5.77%   |
| 0.01-0.5   | 2         | 3.85%   |
| 16.01-24.0 | 1         | 1.92%   |
| 8.01-16.0  | 1         | 1.92%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 36        | 70.59%  |
| 2      | 13        | 25.49%  |
| 4      | 1         | 1.96%   |
| 3      | 1         | 1.96%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 35        | 70%     |
| Yes       | 15        | 30%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 44        | 88%     |
| No        | 6         | 12%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 50        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 45        | 90%     |
| No        | 5         | 10%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 12        | 24%     |
| Brazil       | 4         | 8%      |
| UK           | 3         | 6%      |
| Portugal     | 3         | 6%      |
| Kazakhstan   | 3         | 6%      |
| Japan        | 3         | 6%      |
| Canada       | 3         | 6%      |
| Sweden       | 2         | 4%      |
| South Africa | 2         | 4%      |
| Poland       | 2         | 4%      |
| India        | 2         | 4%      |
| France       | 2         | 4%      |
| Spain        | 1         | 2%      |
| Serbia       | 1         | 2%      |
| Russia       | 1         | 2%      |
| Philippines  | 1         | 2%      |
| Mexico       | 1         | 2%      |
| Italy        | 1         | 2%      |
| Germany      | 1         | 2%      |
| Finland      | 1         | 2%      |
| Chile        | 1         | 2%      |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Warsaw                 | 2         | 3.85%   |
| Ust-Kamenogorsk        | 2         | 3.85%   |
| Lisbon                 | 2         | 3.85%   |
| Winnipeg               | 1         | 1.92%   |
| Visconde do Rio Branco | 1         | 1.92%   |
| Tsuruoka               | 1         | 1.92%   |
| SkÃ¶vde              | 1         | 1.92%   |
| SetГєbal             | 1         | 1.92%   |
| Savonlinna             | 1         | 1.92%   |
| Santiago               | 1         | 1.92%   |
| San Antonio            | 1         | 1.92%   |
| Round Rock             | 1         | 1.92%   |
| Reno                   | 1         | 1.92%   |
| Redding                | 1         | 1.92%   |
| Reading                | 1         | 1.92%   |
| Prato                  | 1         | 1.92%   |
| Plainwell              | 1         | 1.92%   |
| PiteГҐ               | 1         | 1.92%   |
| Pasig                  | 1         | 1.92%   |
| Paris                  | 1         | 1.92%   |
| Ottawa                 | 1         | 1.92%   |
| Ōtsu                  | 1         | 1.92%   |
| Northport              | 1         | 1.92%   |
| Nizhniy Novgorod       | 1         | 1.92%   |
| Musashino              | 1         | 1.92%   |
| Montreal               | 1         | 1.92%   |
| Milan                  | 1         | 1.92%   |
| Mexico City            | 1         | 1.92%   |
| McKinney               | 1         | 1.92%   |
| Lins                   | 1         | 1.92%   |
| League City            | 1         | 1.92%   |
| Karaganda              | 1         | 1.92%   |
| Johannesburg           | 1         | 1.92%   |
| Hornsey                | 1         | 1.92%   |
| Heinsberg              | 1         | 1.92%   |
| Hayward                | 1         | 1.92%   |
| Guntur                 | 1         | 1.92%   |
| Fortaleza              | 1         | 1.92%   |
| Delhi                  | 1         | 1.92%   |
| Chessy                 | 1         | 1.92%   |
| Carrollton             | 1         | 1.92%   |
| Cape Town              | 1         | 1.92%   |
| Canandaigua            | 1         | 1.92%   |
| Campinas               | 1         | 1.92%   |
| Bengaluru              | 1         | 1.92%   |
| Belgrade               | 1         | 1.92%   |
| Barry                  | 1         | 1.92%   |
| Algeciras              | 1         | 1.92%   |
| Abingdon               | 1         | 1.92%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 15        | 20     | 24.19%  |
| WDC                 | 11        | 13     | 17.74%  |
| Toshiba             | 5         | 5      | 8.06%   |
| Seagate             | 5         | 5      | 8.06%   |
| Crucial             | 4         | 5      | 6.45%   |
| SanDisk             | 3         | 3      | 4.84%   |
| Kingston            | 3         | 3      | 4.84%   |
| Unknown             | 2         | 2      | 3.23%   |
| SK Hynix            | 2         | 2      | 3.23%   |
| HGST                | 2         | 2      | 3.23%   |
| Gigabyte Technology | 2         | 2      | 3.23%   |
| PLEXTOR             | 1         | 1      | 1.61%   |
| Patriot             | 1         | 2      | 1.61%   |
| Netac               | 1         | 1      | 1.61%   |
| Micron Technology   | 1         | 1      | 1.61%   |
| KIOXIA              | 1         | 1      | 1.61%   |
| Intel               | 1         | 1      | 1.61%   |
| Hewlett-Packard     | 1         | 2      | 1.61%   |
| DOGFISH             | 1         | 1      | 1.61%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| WDC WD10SPZX-60Z10T0 1TB                | 2         | 3.03%   |
| Toshiba MQ04ABF100 1TB                  | 2         | 3.03%   |
| WDC WDS500G2B0B-00YS70 500GB SSD        | 1         | 1.52%   |
| WDC WD7500BPVT-24HXZT3 752GB            | 1         | 1.52%   |
| WDC WD5000LPCX-60VHAT1 500GB            | 1         | 1.52%   |
| WDC WD10JPVX-35JC3T0 1TB                | 1         | 1.52%   |
| WDC WD10JPVX-16JC3T3 1TB                | 1         | 1.52%   |
| WDC WD10JPVT-08A1YT2 1TB                | 1         | 1.52%   |
| WDC WD10JPLX-00MBPT0 1TB                | 1         | 1.52%   |
| WDC PC SN530 SDBPNPZ-1T00-1002 1TB      | 1         | 1.52%   |
| WDC PC SN520 SDAPNUW-256G-1102 256GB    | 1         | 1.52%   |
| Unknown SD32G  32GB                     | 1         | 1.52%   |
| Unknown SC32G  32GB                     | 1         | 1.52%   |
| Toshiba MQ01ABF050 500GB                | 1         | 1.52%   |
| Toshiba MK2565GSXN 250GB                | 1         | 1.52%   |
| Toshiba MK1646GSX 160GB                 | 1         | 1.52%   |
| SK Hynix HFM001TD3JX013N 1TB            | 1         | 1.52%   |
| SK Hynix BC511 HFM512GDJTNI-82A0A 512GB | 1         | 1.52%   |
| Seagate ST9160827AS 160GB               | 1         | 1.52%   |
| Seagate ST9160412AS 160GB               | 1         | 1.52%   |
| Seagate ST500VT000-1DK142 500GB         | 1         | 1.52%   |
| Seagate ST1000LM048-2E7172 1TB          | 1         | 1.52%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 1         | 1.52%   |
| SanDisk Ultra II 960GB SSD              | 1         | 1.52%   |
| SanDisk SDSSDA240G 240GB                | 1         | 1.52%   |
| SanDisk SD8TN8U256G1001 256GB SSD       | 1         | 1.52%   |
| Samsung SSD 980 PRO 500GB               | 1         | 1.52%   |
| Samsung SSD 980 PRO 2TB                 | 1         | 1.52%   |
| Samsung SSD 970 EVO Plus 2TB            | 1         | 1.52%   |
| Samsung SSD 970 EVO Plus 250GB          | 1         | 1.52%   |
| Samsung SSD 970 EVO 2TB                 | 1         | 1.52%   |
| Samsung SSD 870 EVO 1TB                 | 1         | 1.52%   |
| Samsung SSD 860 QVO 2TB                 | 1         | 1.52%   |
| Samsung SSD 860 EVO mSATA 500GB         | 1         | 1.52%   |
| Samsung SSD 840 EVO 250GB               | 1         | 1.52%   |
| Samsung NVMe SSD Drive 256GB            | 1         | 1.52%   |
| Samsung MZVLQ512HALU-000H1 512GB        | 1         | 1.52%   |
| Samsung MZVLB512HAJQ-000L7 512GB        | 1         | 1.52%   |
| Samsung MZVLB1T0HBLR-00007 1TB          | 1         | 1.52%   |
| Samsung MZVL21T0HCLR-00B00 1TB          | 1         | 1.52%   |
| Samsung MZVKW512HMJP-000H1 512GB        | 1         | 1.52%   |
| Samsung MZMTE256HMHP-00000 256GB SSD    | 1         | 1.52%   |
| Samsung MZ7LN256HCHP-000L7 256GB SSD    | 1         | 1.52%   |
| Samsung MZ7LN256HAJQ-000L2 256GB SSD    | 1         | 1.52%   |
| PLEXTOR PX-128M6S 128GB SSD             | 1         | 1.52%   |
| Patriot Burst 960GB SSD                 | 1         | 1.52%   |
| Patriot Burst 120GB SSD                 | 1         | 1.52%   |
| Netac SSD 720GB                         | 1         | 1.52%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD     | 1         | 1.52%   |
| KIOXIA KBG40ZNS256G NVMe 256GB          | 1         | 1.52%   |
| Kingston SUV400S37240G 240GB SSD        | 1         | 1.52%   |
| Kingston SA400S37240G 240GB SSD         | 1         | 1.52%   |
| Kingston RBUSNS8154P3128GJ 128GB        | 1         | 1.52%   |
| Intel SSDPEKKF010T8L 1TB                | 1         | 1.52%   |
| HGST HTS725050A7E630 500GB              | 1         | 1.52%   |
| HGST HTS541010A9E680 1TB                | 1         | 1.52%   |
| HP SSD EX950 2TB                        | 1         | 1.52%   |
| Gigabyte GP-GSTFS31240GNTD 240GB        | 1         | 1.52%   |
| Gigabyte GP-GSM2NE8128GNTD 128GB        | 1         | 1.52%   |
| DOGFISH SSD 256G                        | 1         | 1.52%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 8         | 10     | 40%     |
| Toshiba | 5         | 5      | 25%     |
| Seagate | 5         | 5      | 25%     |
| HGST    | 2         | 2      | 10%     |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 7      | 28.57%  |
| SanDisk             | 3         | 3      | 14.29%  |
| Crucial             | 3         | 4      | 14.29%  |
| Kingston            | 2         | 2      | 9.52%   |
| WDC                 | 1         | 1      | 4.76%   |
| PLEXTOR             | 1         | 1      | 4.76%   |
| Patriot             | 1         | 2      | 4.76%   |
| Netac               | 1         | 1      | 4.76%   |
| Micron Technology   | 1         | 1      | 4.76%   |
| Gigabyte Technology | 1         | 1      | 4.76%   |
| DOGFISH             | 1         | 1      | 4.76%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 20        | 24     | 32.79%  |
| HDD  | 20        | 22     | 32.79%  |
| NVMe | 19        | 24     | 31.15%  |
| MMC  | 2         | 2      | 3.28%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 35        | 46     | 62.5%   |
| NVMe | 19        | 24     | 33.93%  |
| MMC  | 2         | 2      | 3.57%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 23        | 27     | 57.5%   |
| 0.51-1.0   | 16        | 18     | 40%     |
| 1.01-2.0   | 1         | 1      | 2.5%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 501-1000       | 16        | 32%     |
| 101-250        | 12        | 24%     |
| 251-500        | 11        | 22%     |
| 1001-2000      | 5         | 10%     |
| 1-20           | 3         | 6%      |
| More than 3000 | 1         | 2%      |
| 51-100         | 1         | 2%      |
| Unknown        | 1         | 2%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 11        | 20.75%  |
| 21-50     | 10        | 18.87%  |
| 101-250   | 8         | 15.09%  |
| 51-100    | 8         | 15.09%  |
| 251-500   | 7         | 13.21%  |
| 501-1000  | 7         | 13.21%  |
| 1001-2000 | 1         | 1.89%   |
| Unknown   | 1         | 1.89%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD5000LPCX-60VHAT1 500GB        | 1         | 1      | 16.67%  |
| WDC WD10JPLX-00MBPT0 1TB            | 1         | 1      | 16.67%  |
| Toshiba MK2565GSXN 250GB            | 1         | 1      | 16.67%  |
| Samsung Electronics SSD 870 EVO 1TB | 1         | 1      | 16.67%  |
| PLEXTOR PX-128M6S 128GB SSD         | 1         | 1      | 16.67%  |
| HGST HTS725050A7E630 500GB          | 1         | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 2         | 2      | 33.33%  |
| Toshiba             | 1         | 1      | 16.67%  |
| Samsung Electronics | 1         | 1      | 16.67%  |
| PLEXTOR             | 1         | 1      | 16.67%  |
| HGST                | 1         | 1      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 2         | 2      | 50%     |
| Toshiba | 1         | 1      | 25%     |
| HGST    | 1         | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 4         | 4      | 66.67%  |
| SSD  | 2         | 2      | 33.33%  |

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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 42        | 57     | 75%     |
| Detected | 8         | 9      | 14.29%  |
| Malfunc  | 6         | 6      | 10.71%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 37        | 61.67%  |
| Samsung Electronics         | 9         | 15%     |
| AMD                         | 5         | 8.33%   |
| SK Hynix                    | 2         | 3.33%   |
| Sandisk                     | 2         | 3.33%   |
| Phison Electronics          | 1         | 1.67%   |
| Micron/Crucial Technology   | 1         | 1.67%   |
| KIOXIA                      | 1         | 1.67%   |
| Kingston Technology Company | 1         | 1.67%   |
| Biwin Storage Technology    | 1         | 1.67%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 5         | 8.06%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 5         | 8.06%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 4         | 6.45%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 4         | 6.45%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 4         | 6.45%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 4         | 6.45%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 4.84%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 3.23%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 3.23%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 3.23%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2         | 3.23%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 2         | 3.23%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 2         | 3.23%   |
| SK Hynix Gold P31 SSD                                                            | 1         | 1.61%   |
| SK Hynix BC511                                                                   | 1         | 1.61%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 1         | 1.61%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 1.61%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 1.61%   |
| Phison NVMe Storage Controller                                                   | 1         | 1.61%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1         | 1.61%   |
| KIOXIA Non-Volatile memory controller                                            | 1         | 1.61%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 1.61%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 1         | 1.61%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 1         | 1.61%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 1.61%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 1.61%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 1.61%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 1.61%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 1         | 1.61%   |
| Intel 6 Series/C200 Series Chipset Family IDE-r Controller                       | 1         | 1.61%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 1         | 1.61%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 1         | 1.61%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 1         | 1.61%   |
| Biwin Storage Non-Volatile memory controller                                     | 1         | 1.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 35        | 57.38%  |
| NVMe | 19        | 31.15%  |
| RAID | 5         | 8.2%    |
| IDE  | 2         | 3.28%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 45        | 90%     |
| AMD    | 5         | 10%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 3         | 6%      |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 4%      |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 4%      |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 4%      |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 2         | 4%      |
| Intel Pentium CPU P6100 @ 2.00GHz             | 1         | 2%      |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 2%      |
| Intel Core M-5Y51 CPU @ 1.10GHz               | 1         | 2%      |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 2%      |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 2%      |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 2%      |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 2%      |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 2%      |
| Intel Core i7-3840QM CPU @ 2.80GHz            | 1         | 2%      |
| Intel Core i7-2860QM CPU @ 2.50GHz            | 1         | 2%      |
| Intel Core i7-10870H CPU @ 2.20GHz            | 1         | 2%      |
| Intel Core i7-10710U CPU @ 1.10GHz            | 1         | 2%      |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 2%      |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 2%      |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 2%      |
| Intel Core i5-5300U CPU @ 2.30GHz             | 1         | 2%      |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 2%      |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 2%      |
| Intel Core i5-3360M CPU @ 2.80GHz             | 1         | 2%      |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 2%      |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 2%      |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 2%      |
| Intel Core i5-2430M CPU @ 2.40GHz             | 1         | 2%      |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 2%      |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 1         | 2%      |
| Intel Core i3-8130U CPU @ 2.20GHz             | 1         | 2%      |
| Intel Core i3-6100U CPU @ 2.30GHz             | 1         | 2%      |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 2%      |
| Intel Core i3-4000M CPU @ 2.40GHz             | 1         | 2%      |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz          | 1         | 2%      |
| Intel Core 2 CPU P8400 @ 2.26GHz              | 1         | 2%      |
| Intel Celeron N4000 CPU @ 1.10GHz             | 1         | 2%      |
| Intel Celeron CPU N3060 @ 1.60GHz             | 1         | 2%      |
| Intel Atom CPU N270 @ 1.60GHz                 | 1         | 2%      |
| Intel 11th Gen Core i9-11900K @ 3.50GHz       | 1         | 2%      |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1         | 2%      |
| AMD Ryzen 9 4900HS with Radeon Graphics       | 1         | 2%      |
| AMD Ryzen 5 4600H with Radeon Graphics        | 1         | 2%      |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 2%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 13        | 26%     |
| Intel Core i7    | 11        | 22%     |
| Other            | 7         | 14%     |
| Intel Core i3    | 6         | 12%     |
| AMD Ryzen 5      | 4         | 8%      |
| Intel Pentium    | 2         | 4%      |
| Intel Celeron    | 2         | 4%      |
| Intel Core M     | 1         | 2%      |
| Intel Core 2 Duo | 1         | 2%      |
| Intel Core 2     | 1         | 2%      |
| Intel Atom       | 1         | 2%      |
| AMD Ryzen 9      | 1         | 2%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 24        | 48%     |
| 4      | 17        | 34%     |
| 8      | 6         | 12%     |
| 6      | 2         | 4%      |
| 1      | 1         | 2%      |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 50        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 44        | 88%     |
| 1      | 6         | 12%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 47        | 94%     |
| Unknown        | 2         | 4%      |
| 32-bit         | 1         | 2%      |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 9         | 18%     |
| 0x306a9    | 5         | 10%     |
| 0x306d4    | 4         | 8%      |
| 0x806ea    | 3         | 6%      |
| 0x806d1    | 3         | 6%      |
| 0x806c1    | 3         | 6%      |
| 0x406e3    | 3         | 6%      |
| 0x806ec    | 2         | 4%      |
| 0x206a7    | 2         | 4%      |
| 0xa0671    | 1         | 2%      |
| 0xa0660    | 1         | 2%      |
| 0xa0652    | 1         | 2%      |
| 0x806e9    | 1         | 2%      |
| 0x706a1    | 1         | 2%      |
| 0x6fd      | 1         | 2%      |
| 0x506e3    | 1         | 2%      |
| 0x406c4    | 1         | 2%      |
| 0x40651    | 1         | 2%      |
| 0x306c3    | 1         | 2%      |
| 0x20655    | 1         | 2%      |
| 0x106c2    | 1         | 2%      |
| 0x1067a    | 1         | 2%      |
| 0x08600106 | 1         | 2%      |
| 0x08108109 | 1         | 2%      |
| 0x0810100b | 1         | 2%      |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 8         | 16%     |
| Skylake       | 5         | 10%     |
| IvyBridge     | 5         | 10%     |
| Icelake       | 4         | 8%      |
| Haswell       | 4         | 8%      |
| Broadwell     | 4         | 8%      |
| TigerLake     | 3         | 6%      |
| Zen 2         | 2         | 4%      |
| Zen           | 2         | 4%      |
| Westmere      | 2         | 4%      |
| Silvermont    | 2         | 4%      |
| SandyBridge   | 2         | 4%      |
| CometLake     | 2         | 4%      |
| Zen+          | 1         | 2%      |
| Penryn        | 1         | 2%      |
| Goldmont plus | 1         | 2%      |
| Core          | 1         | 2%      |
| Bonnell       | 1         | 2%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 40        | 66.67%  |
| Nvidia | 13        | 21.67%  |
| AMD    | 7         | 11.67%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 6.56%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 3         | 4.92%   |
| Intel UHD Graphics 620                                                                   | 3         | 4.92%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 4.92%   |
| Intel HD Graphics 5500                                                                   | 3         | 4.92%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 4.92%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 4.92%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 3.28%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 3.28%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 3.28%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 3.28%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 3.28%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 3.28%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 3.28%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 3.28%   |
| AMD Renoir                                                                               | 2         | 3.28%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 3.28%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 1         | 1.64%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 1.64%   |
| Nvidia GM204GLM [Quadro M3000M]                                                          | 1         | 1.64%   |
| Nvidia GK107M [GeForce GT 745M]                                                          | 1         | 1.64%   |
| Nvidia GF106GLM [Quadro 2000M]                                                           | 1         | 1.64%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 1.64%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 1         | 1.64%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 1.64%   |
| Intel HD Graphics 620                                                                    | 1         | 1.64%   |
| Intel HD Graphics 5300                                                                   | 1         | 1.64%   |
| Intel HD Graphics 530                                                                    | 1         | 1.64%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 1.64%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 1.64%   |
| Intel Comet Lake UHD Graphics                                                            | 1         | 1.64%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.64%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1         | 1.64%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 1         | 1.64%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1         | 1.64%   |
| AMD Chelsea XT GL [FirePro M4000]                                                        | 1         | 1.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 33        | 66%     |
| Intel + Nvidia | 7         | 14%     |
| 1 x AMD        | 5         | 10%     |
| 1 x Nvidia     | 3         | 6%      |
| AMD + Nvidia   | 2         | 4%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 46        | 92%     |
| Proprietary | 3         | 6%      |
| Unknown     | 1         | 2%      |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 35        | 68.63%  |
| 1.01-2.0   | 5         | 9.8%    |
| 0.51-1.0   | 3         | 5.88%   |
| 0.01-0.5   | 3         | 5.88%   |
| 7.01-8.0   | 2         | 3.92%   |
| 3.01-4.0   | 2         | 3.92%   |
| 5.01-6.0   | 1         | 1.96%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| LG Display          | 11        | 20%     |
| BOE                 | 11        | 20%     |
| Chimei Innolux      | 9         | 16.36%  |
| AU Optronics        | 8         | 14.55%  |
| Sharp               | 4         | 7.27%   |
| Samsung Electronics | 4         | 7.27%   |
| Hewlett-Packard     | 2         | 3.64%   |
| Sony                | 1         | 1.82%   |
| PANDA               | 1         | 1.82%   |
| Panasonic           | 1         | 1.82%   |
| Lenovo              | 1         | 1.82%   |
| Goldstar            | 1         | 1.82%   |
| Dell                | 1         | 1.82%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 2         | 3.64%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch        | 2         | 3.64%   |
| Sony TV SNY8102 1360x768 1600x900mm 72.3-inch                        | 1         | 1.82%   |
| Sharp LQ173M1JW05 SHP14EC 1920x1080 382x215mm 17.3-inch              | 1         | 1.82%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch              | 1         | 1.82%   |
| Sharp LQ125T1JW02 SHP142F 2560x1440 277x155mm 12.5-inch              | 1         | 1.82%   |
| Sharp LCD Monitor SHP14C4 1920x1080 344x194mm 15.5-inch              | 1         | 1.82%   |
| Samsung Electronics SyncMaster SAM0428 1680x1050 459x296mm 21.5-inch | 1         | 1.82%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch | 1         | 1.82%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch | 1         | 1.82%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch | 1         | 1.82%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch              | 1         | 1.82%   |
| Panasonic LCD Monitor MEI96A2 2560x1440 309x173mm 13.9-inch          | 1         | 1.82%   |
| LG Display LCD Monitor LGD0625 1920x1080 344x194mm 15.5-inch         | 1         | 1.82%   |
| LG Display LCD Monitor LGD0599 1920x1080 309x174mm 14.0-inch         | 1         | 1.82%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch         | 1         | 1.82%   |
| LG Display LCD Monitor LGD0508 1366x768 309x174mm 14.0-inch          | 1         | 1.82%   |
| LG Display LCD Monitor LGD03D7 1366x768 310x174mm 14.0-inch          | 1         | 1.82%   |
| LG Display LCD Monitor LGD0353 1366x768 345x194mm 15.6-inch          | 1         | 1.82%   |
| LG Display LCD Monitor LGD032C 1920x1080 344x194mm 15.5-inch         | 1         | 1.82%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch          | 1         | 1.82%   |
| LG Display LCD Monitor LGD02D9 1920x1080 344x194mm 15.5-inch         | 1         | 1.82%   |
| LG Display LCD Monitor LGD028A 1366x768 344x194mm 15.5-inch          | 1         | 1.82%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch          | 1         | 1.82%   |
| Lenovo LCD Monitor LEN4035 1280x800 303x190mm 14.1-inch              | 1         | 1.82%   |
| Hewlett-Packard P223 HPN3392 1920x1080 477x268mm 21.5-inch           | 1         | 1.82%   |
| Hewlett-Packard 27m HPN3579 1920x1080 598x336mm 27.0-inch            | 1         | 1.82%   |
| Goldstar W2043 GSM4E9D 1600x900 450x250mm 20.3-inch                  | 1         | 1.82%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                     | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch     | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN15CC 1366x768 344x193mm 15.5-inch      | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN15B6 1366x768 340x190mm 15.3-inch      | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch     | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch      | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch      | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN1355 1366x768 293x165mm 13.2-inch      | 1         | 1.82%   |
| BOE LCD Monitor BOE0A85 1920x1080 344x194mm 15.5-inch                | 1         | 1.82%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                | 1         | 1.82%   |
| BOE LCD Monitor BOE08F6 1920x1080 355x200mm 16.0-inch                | 1         | 1.82%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                | 1         | 1.82%   |
| BOE LCD Monitor BOE07C8 3840x2160 309x174mm 14.0-inch                | 1         | 1.82%   |
| BOE LCD Monitor BOE0703 1920x1080 344x194mm 15.5-inch                | 1         | 1.82%   |
| BOE LCD Monitor BOE06F0 1366x768 344x194mm 15.5-inch                 | 1         | 1.82%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                 | 1         | 1.82%   |
| BOE LCD Monitor BOE0690 1920x1080 344x193mm 15.5-inch                | 1         | 1.82%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                 | 1         | 1.82%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                 | 1         | 1.82%   |
| AU Optronics LCD Monitor AUO978F 1920x1080 382x215mm 17.3-inch       | 1         | 1.82%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch        | 1         | 1.82%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch       | 1         | 1.82%   |
| AU Optronics LCD Monitor AUO48EC 1366x768 344x193mm 15.5-inch        | 1         | 1.82%   |
| AU Optronics LCD Monitor AUO30ED 1920x1080 344x193mm 15.5-inch       | 1         | 1.82%   |
| AU Optronics LCD Monitor AUO309B 3840x2160 381x214mm 17.2-inch       | 1         | 1.82%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 22        | 41.51%  |
| 1366x768 (WXGA)    | 20        | 37.74%  |
| 3840x2160 (4K)     | 3         | 5.66%   |
| 1600x900 (HD+)     | 3         | 5.66%   |
| 2560x1440 (QHD)    | 1         | 1.89%   |
| 2256x1504          | 1         | 1.89%   |
| 1680x1050 (WSXGA+) | 1         | 1.89%   |
| 1360x768           | 1         | 1.89%   |
| 1280x800 (WXGA)    | 1         | 1.89%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 25        | 45.45%  |
| 14     | 9         | 16.36%  |
| 13     | 6         | 10.91%  |
| 17     | 5         | 9.09%   |
| 12     | 3         | 5.45%   |
| 21     | 2         | 3.64%   |
| 72     | 1         | 1.82%   |
| 27     | 1         | 1.82%   |
| 24     | 1         | 1.82%   |
| 20     | 1         | 1.82%   |
| 16     | 1         | 1.82%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 37        | 67.27%  |
| 351-400     | 7         | 12.73%  |
| 201-300     | 5         | 9.09%   |
| 401-500     | 3         | 5.45%   |
| 501-600     | 2         | 3.64%   |
| 1501-2000   | 1         | 1.82%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 47        | 92.16%  |
| 3/2   | 2         | 3.92%   |
| 16/10 | 2         | 3.92%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 26        | 47.27%  |
| 81-90          | 14        | 25.45%  |
| 121-130        | 5         | 9.09%   |
| 61-70          | 3         | 5.45%   |
| 151-200        | 2         | 3.64%   |
| More than 1000 | 1         | 1.82%   |
| 71-80          | 1         | 1.82%   |
| 301-350        | 1         | 1.82%   |
| 251-300        | 1         | 1.82%   |
| 201-250        | 1         | 1.82%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 24        | 44.44%  |
| 101-120       | 18        | 33.33%  |
| 51-100        | 6         | 11.11%  |
| More than 240 | 3         | 5.56%   |
| 161-240       | 2         | 3.7%    |
| 1-50          | 1         | 1.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 44        | 88%     |
| 2     | 6         | 12%     |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 38        | 46.91%  |
| Realtek Semiconductor | 25        | 30.86%  |
| Qualcomm Atheros      | 7         | 8.64%   |
| Ralink Technology     | 2         | 2.47%   |
| Broadcom Limited      | 2         | 2.47%   |
| Broadcom              | 2         | 2.47%   |
| ASIX Electronics      | 2         | 2.47%   |
| Sierra Wireless       | 1         | 1.23%   |
| Hewlett-Packard       | 1         | 1.23%   |
| Dell                  | 1         | 1.23%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 16        | 15.84%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 5         | 4.95%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 4         | 3.96%   |
| Intel Wireless 8265 / 8275                                                            | 3         | 2.97%   |
| Intel Wireless 7265                                                                   | 3         | 2.97%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 3         | 2.97%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 2         | 1.98%   |
| Realtek Killer E3000 2.5GbE Controller                                                | 2         | 1.98%   |
| Ralink MT7601U Wireless Adapter                                                       | 2         | 1.98%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 2         | 1.98%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                             | 2         | 1.98%   |
| Intel Wireless-AC 9260                                                                | 2         | 1.98%   |
| Intel Wireless 8260                                                                   | 2         | 1.98%   |
| Intel Wireless 7260                                                                   | 2         | 1.98%   |
| Intel Wireless 3160                                                                   | 2         | 1.98%   |
| Intel Wi-Fi 6 AX201                                                                   | 2         | 1.98%   |
| Intel Wi-Fi 6 AX200                                                                   | 2         | 1.98%   |
| Intel Tiger Lake PCH CNVi WiFi                                                        | 2         | 1.98%   |
| Intel Ethernet Connection (3) I218-LM                                                 | 2         | 1.98%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 2         | 1.98%   |
| Intel Centrino Ultimate-N 6300                                                        | 2         | 1.98%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 2         | 1.98%   |
| Sierra Wireless EM7305                                                                | 1         | 0.99%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 1         | 0.99%   |
| Realtek RTL8723DE Wireless Network Adapter                                            | 1         | 0.99%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                       | 1         | 0.99%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 0.99%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                              | 1         | 0.99%   |
| Realtek RTL8125 2.5GbE Controller                                                     | 1         | 0.99%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                      | 1         | 0.99%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 1         | 0.99%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                         | 1         | 0.99%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                        | 1         | 0.99%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 0.99%   |
| Intel Wireless 3165                                                                   | 1         | 0.99%   |
| Intel WiFi Link 5100                                                                  | 1         | 0.99%   |
| Intel Gemini Lake PCH CNVi WiFi                                                       | 1         | 0.99%   |
| Intel Ethernet Connection I219-LM                                                     | 1         | 0.99%   |
| Intel Ethernet Connection I218-V                                                      | 1         | 0.99%   |
| Intel Ethernet Connection I217-V                                                      | 1         | 0.99%   |
| Intel Ethernet Connection (4) I219-V                                                  | 1         | 0.99%   |
| Intel Ethernet Connection (4) I219-LM                                                 | 1         | 0.99%   |
| Intel Ethernet Connection (2) I219-LM                                                 | 1         | 0.99%   |
| Intel Ethernet Connection (10) I219-V                                                 | 1         | 0.99%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 1         | 0.99%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 1         | 0.99%   |
| Intel Centrino Wireless-N 2230                                                        | 1         | 0.99%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 1         | 0.99%   |
| Intel 82567LM Gigabit Network Connection                                              | 1         | 0.99%   |
| HP hs2350 HSPA+ MobileBroadband                                                       | 1         | 0.99%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                                                  | 1         | 0.99%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                                     | 1         | 0.99%   |
| Broadcom Limited NetXtreme BCM5756ME Gigabit Ethernet PCI Express                     | 1         | 0.99%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                                               | 1         | 0.99%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 1         | 0.99%   |
| ASIX AX88772B                                                                         | 1         | 0.99%   |
| ASIX AX88179 Gigabit Ethernet                                                         | 1         | 0.99%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 36        | 67.92%  |
| Realtek Semiconductor | 6         | 11.32%  |
| Qualcomm Atheros      | 5         | 9.43%   |
| Ralink Technology     | 2         | 3.77%   |
| Sierra Wireless       | 1         | 1.89%   |
| Dell                  | 1         | 1.89%   |
| Broadcom Limited      | 1         | 1.89%   |
| Broadcom              | 1         | 1.89%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                                            | 3         | 5.66%   |
| Intel Wireless 7265                                                                   | 3         | 5.66%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 3         | 5.66%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 2         | 3.77%   |
| Ralink MT7601U Wireless Adapter                                                       | 2         | 3.77%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 2         | 3.77%   |
| Intel Wireless-AC 9260                                                                | 2         | 3.77%   |
| Intel Wireless 8260                                                                   | 2         | 3.77%   |
| Intel Wireless 7260                                                                   | 2         | 3.77%   |
| Intel Wireless 3160                                                                   | 2         | 3.77%   |
| Intel Wi-Fi 6 AX201                                                                   | 2         | 3.77%   |
| Intel Wi-Fi 6 AX200                                                                   | 2         | 3.77%   |
| Intel Tiger Lake PCH CNVi WiFi                                                        | 2         | 3.77%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 2         | 3.77%   |
| Intel Centrino Ultimate-N 6300                                                        | 2         | 3.77%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 2         | 3.77%   |
| Sierra Wireless EM7305                                                                | 1         | 1.89%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 1         | 1.89%   |
| Realtek RTL8723DE Wireless Network Adapter                                            | 1         | 1.89%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                       | 1         | 1.89%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 1.89%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                      | 1         | 1.89%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 1         | 1.89%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 1.89%   |
| Intel Wireless 3165                                                                   | 1         | 1.89%   |
| Intel WiFi Link 5100                                                                  | 1         | 1.89%   |
| Intel Gemini Lake PCH CNVi WiFi                                                       | 1         | 1.89%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 1         | 1.89%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 1         | 1.89%   |
| Intel Centrino Wireless-N 2230                                                        | 1         | 1.89%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 1         | 1.89%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                                                  | 1         | 1.89%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                                               | 1         | 1.89%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 1         | 1.89%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 24        | 52.17%  |
| Intel                 | 14        | 30.43%  |
| Qualcomm Atheros      | 4         | 8.7%    |
| ASIX Electronics      | 2         | 4.35%   |
| Broadcom Limited      | 1         | 2.17%   |
| Broadcom              | 1         | 2.17%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 16        | 34.04%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 10.64%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 8.51%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 4.26%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 4.26%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 4.26%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 2.13%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 2.13%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 2.13%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 2.13%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 2.13%   |
| Intel Ethernet Connection I218-V                                  | 1         | 2.13%   |
| Intel Ethernet Connection I217-V                                  | 1         | 2.13%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 2.13%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 2.13%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 2.13%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 2.13%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 2.13%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 2.13%   |
| Broadcom Limited NetXtreme BCM5756ME Gigabit Ethernet PCI Express | 1         | 2.13%   |
| ASIX AX88772B                                                     | 1         | 2.13%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 2.13%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 50        | 52.63%  |
| Ethernet | 44        | 46.32%  |
| Modem    | 1         | 1.05%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 40        | 66.67%  |
| Ethernet | 20        | 33.33%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 42        | 84%     |
| 1     | 7         | 14%     |
| 0     | 1         | 2%      |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 48        | 96%     |
| Yes  | 2         | 4%      |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 31        | 68.89%  |
| Realtek Semiconductor           | 5         | 11.11%  |
| Broadcom                        | 4         | 8.89%   |
| Qualcomm Atheros Communications | 3         | 6.67%   |
| Toshiba                         | 1         | 2.22%   |
| Cambridge Silicon Radio         | 1         | 2.22%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 14        | 31.11%  |
| Intel Bluetooth Device                              | 6         | 13.33%  |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 6.67%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 6.67%   |
| Intel AX210 Bluetooth                               | 3         | 6.67%   |
| Realtek Bluetooth Radio                             | 2         | 4.44%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 4.44%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 4.44%   |
| Intel AX200 Bluetooth                               | 2         | 4.44%   |
| Toshiba Askey Bluetooth Module                      | 1         | 2.22%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 2.22%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 2.22%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 2.22%   |
| Broadcom HP Portable SoftSailing                    | 1         | 2.22%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 2.22%   |
| Broadcom BCM20702A0                                 | 1         | 2.22%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 2.22%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 45        | 70.31%  |
| Nvidia              | 10        | 15.63%  |
| AMD                 | 7         | 10.94%  |
| Texas Instruments   | 1         | 1.56%   |
| C-Media Electronics | 1         | 1.56%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 8         | 10.53%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 5         | 6.58%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 5         | 6.58%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 5.26%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 4         | 5.26%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 5.26%   |
| Intel Broadwell-U Audio Controller                                                                | 4         | 5.26%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 3         | 3.95%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 3.95%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 3.95%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 2.63%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 2.63%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 2.63%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 2.63%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 2.63%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 2.63%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 2.63%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 2.63%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 2.63%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 1.32%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 1.32%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 1.32%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1         | 1.32%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 1.32%   |
| Nvidia Audio device                                                                               | 1         | 1.32%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 1.32%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 1.32%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 1.32%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 1.32%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 1.32%   |
| C-Media Electronics CM6631A Audio Processor                                                       | 1         | 1.32%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 1         | 1.32%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 1.32%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 1         | 1.32%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 15        | 28.85%  |
| Samsung Electronics | 10        | 19.23%  |
| Kingston            | 7         | 13.46%  |
| Micron Technology   | 5         | 9.62%   |
| Crucial             | 4         | 7.69%   |
| Ramaxel Technology  | 2         | 3.85%   |
| Corsair             | 2         | 3.85%   |
| Unknown             | 1         | 1.92%   |
| Smart               | 1         | 1.92%   |
| Neo Forza           | 1         | 1.92%   |
| Nanya Technology    | 1         | 1.92%   |
| Essencore Limited   | 1         | 1.92%   |
| Elpida              | 1         | 1.92%   |
| A-DATA Technology   | 1         | 1.92%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s            | 2         | 3.64%   |
| Unknown RAM Module 1024MB SODIMM SDRAM                               | 1         | 1.82%   |
| Smart RAM SH5641G8FJ8NWRNSQG 8GB SODIMM DDR3 1600MT/s                | 1         | 1.82%   |
| SK Hynix RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s              | 1         | 1.82%   |
| SK Hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                      | 1         | 1.82%   |
| SK Hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 975MT/s                 | 1         | 1.82%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s               | 1         | 1.82%   |
| SK Hynix RAM HMT41GS6MFR8C-PB 8192MB SODIMM DDR3 1600MT/s            | 1         | 1.82%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s            | 1         | 1.82%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s               | 1         | 1.82%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s               | 1         | 1.82%   |
| SK Hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s               | 1         | 1.82%   |
| SK Hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s               | 1         | 1.82%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s               | 1         | 1.82%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s               | 1         | 1.82%   |
| SK Hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s               | 1         | 1.82%   |
| SK Hynix RAM 746448-381 4096MB SODIMM LPDDR3 1600MT/s                | 1         | 1.82%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s                | 1         | 1.82%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s             | 1         | 1.82%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s                | 1         | 1.82%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s             | 1         | 1.82%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s                | 1         | 1.82%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s                | 1         | 1.82%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s                | 1         | 1.82%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s                | 1         | 1.82%   |
| Samsung RAM M471A5244BB0-CPB 4GB SODIMM DDR4 2400MT/s                | 1         | 1.82%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s               | 1         | 1.82%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s              | 1         | 1.82%   |
| Ramaxel RAM RMT3150ED58E8W1600 2GB SODIMM DDR3 1600MT/s              | 1         | 1.82%   |
| Ramaxel RAM RMSA3260MH78HAF-2666 8GB SODIMM DDR4 2667MT/s            | 1         | 1.82%   |
| Neo Forza RAM NMSO480E82-3200E 8GB SODIMM DDR4 3200MT/s              | 1         | 1.82%   |
| Nanya RAM NT4GC64C88B1NS-DI 4096MB SODIMM DDR3 1600MT/s              | 1         | 1.82%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s                 | 1         | 1.82%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8192MB SODIMM DDR4 3200MT/s              | 1         | 1.82%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s                | 1         | 1.82%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s                | 1         | 1.82%   |
| Micron RAM 16KTF51264HZ-1G4 4096MB SODIMM DDR3 701MT/s               | 1         | 1.82%   |
| Kingston RAM KNWMX1-ETB 4GB SODIMM DDR3 1600MT/s                     | 1         | 1.82%   |
| Kingston RAM KKRVFX-MIE 8GB SODIMM DDR4 3200MT/s                     | 1         | 1.82%   |
| Kingston RAM KHX2666C15S4/8G 8192MB SODIMM DDR4 2667MT/s             | 1         | 1.82%   |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s              | 1         | 1.82%   |
| Kingston RAM CL15-15-15 D4-2133 4096MB SODIMM DDR4 2133MT/s          | 1         | 1.82%   |
| Kingston RAM 9905712-007.A00G 16384MB SODIMM DDR4 2400MT/s           | 1         | 1.82%   |
| Kingston RAM 9905711-032.A00G 8GB SODIMM DDR4 2667MT/s               | 1         | 1.82%   |
| Kingston RAM 9905703-011.A00G 16GB SODIMM DDR4 2400MT/s              | 1         | 1.82%   |
| Essencore Limited RAM KD4AGSA8M-26N1900 16384MB SODIMM DDR4 2667MT/s | 1         | 1.82%   |
| Elpida RAM EBJ81UG8BBU0-GN-F 8192MB SODIMM DDR3 1600MT/s             | 1         | 1.82%   |
| Crucial RAM CT4G4SFS824A.C8FE 4GB SODIMM DDR4 2400MT/s               | 1         | 1.82%   |
| Crucial RAM CT32G4SFD832A.C16FE 32GB SODIMM DDR4 3200MT/s            | 1         | 1.82%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s              | 1         | 1.82%   |
| Crucial RAM BL8G32C16S4B.8FE 8GB SODIMM DDR4 2667MT/s                | 1         | 1.82%   |
| Corsair RAM CMSX32GX4M2A2666C18 16GB SODIMM DDR4 2667MT/s            | 1         | 1.82%   |
| Corsair RAM CMSO4GX3M1C1600C11 4GB SODIMM DDR3 1600MT/s              | 1         | 1.82%   |
| A-DATA RAM AO1L16BC4R1-BX7S 4096MB SODIMM DDR3 1600MT/s              | 1         | 1.82%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 23        | 52.27%  |
| DDR3   | 14        | 31.82%  |
| SDRAM  | 2         | 4.55%   |
| LPDDR4 | 2         | 4.55%   |
| LPDDR3 | 2         | 4.55%   |
| DDR2   | 1         | 2.27%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 43        | 97.73%  |
| Row Of Chips | 1         | 2.27%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 22        | 44%     |
| 8192  | 18        | 36%     |
| 16384 | 5         | 10%     |
| 2048  | 3         | 6%      |
| 32768 | 1         | 2%      |
| 1024  | 1         | 2%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 14        | 29.17%  |
| 2667    | 13        | 27.08%  |
| 3200    | 7         | 14.58%  |
| 2400    | 5         | 10.42%  |
| 2133    | 3         | 6.25%   |
| 4199    | 1         | 2.08%   |
| 1334    | 1         | 2.08%   |
| 1333    | 1         | 2.08%   |
| 975     | 1         | 2.08%   |
| 701     | 1         | 2.08%   |
| Unknown | 1         | 2.08%   |

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


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 14        | 29.17%  |
| Acer                                   | 7         | 14.58%  |
| Realtek Semiconductor                  | 4         | 8.33%   |
| Microdia                               | 4         | 8.33%   |
| IMC Networks                           | 4         | 8.33%   |
| Lite-On Technology                     | 3         | 6.25%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 6.25%   |
| Sunplus Innovation Technology          | 2         | 4.17%   |
| Quanta                                 | 2         | 4.17%   |
| Silicon Motion                         | 1         | 2.08%   |
| Samsung Electronics                    | 1         | 2.08%   |
| Motorola PCS                           | 1         | 2.08%   |
| Luxvisions Innotech Limited            | 1         | 2.08%   |
| Logitech                               | 1         | 2.08%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Acer BisonCam,NB Pro                                                       | 3         | 6.25%   |
| Realtek USB Camera                                                         | 2         | 4.17%   |
| Quanta HP Webcam                                                           | 2         | 4.17%   |
| Chicony Integrated Camera                                                  | 2         | 4.17%   |
| Acer HD Webcam                                                             | 2         | 4.17%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                       | 1         | 2.08%   |
| Sunplus Integrated_Webcam_HD                                               | 1         | 2.08%   |
| Silicon Motion Web Camera                                                  | 1         | 2.08%   |
| Samsung Galaxy A5 (MTP)                                                    | 1         | 2.08%   |
| Realtek Laptop Camera                                                      | 1         | 2.08%   |
| Realtek EasyCamera                                                         | 1         | 2.08%   |
| Motorola PCS XT1033 [Moto G], PTP mode                                     | 1         | 2.08%   |
| Microdia Laptop_Integrated_Webcam_2M                                       | 1         | 2.08%   |
| Microdia Integrated_Webcam_HD                                              | 1         | 2.08%   |
| Microdia Integrated Webcam                                                 | 1         | 2.08%   |
| Microdia Dell Integrated HD Webcam                                         | 1         | 2.08%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 1         | 2.08%   |
| Logitech C920 PRO HD Webcam                                                | 1         | 2.08%   |
| Lite-On TOSHIBA Web Camera - FHD                                           | 1         | 2.08%   |
| Lite-On Integrated Camera                                                  | 1         | 2.08%   |
| Lite-On HP TrueVision HD Camera                                            | 1         | 2.08%   |
| IMC Networks UVC VGA Webcam                                                | 1         | 2.08%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 1         | 2.08%   |
| IMC Networks Lenovo EasyCamera                                             | 1         | 2.08%   |
| IMC Networks Integrated Camera                                             | 1         | 2.08%   |
| Chicony Web Camera - FHD                                                   | 1         | 2.08%   |
| Chicony TOSHIBA Web Camera - HD                                            | 1         | 2.08%   |
| Chicony TOSHIBA Web Camera - FHD                                           | 1         | 2.08%   |
| Chicony Integrated Camera [ThinkPad]                                       | 1         | 2.08%   |
| Chicony Integrated Camera (1280x720@30)                                    | 1         | 2.08%   |
| Chicony HP TrueVision HD Camera                                            | 1         | 2.08%   |
| Chicony HP HD Webcam [Fixed]                                               | 1         | 2.08%   |
| Chicony HP HD Camera                                                       | 1         | 2.08%   |
| Chicony HD WebCam (Acer)                                                   | 1         | 2.08%   |
| Chicony HD WebCam                                                          | 1         | 2.08%   |
| Chicony FJ Camera                                                          | 1         | 2.08%   |
| Chicony 2.0M UVC Webcam / CNF7129                                          | 1         | 2.08%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD integrated webcam | 1         | 2.08%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera             | 1         | 2.08%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam                        | 1         | 2.08%   |
| Acer ThinkPad Integrated Camera                                            | 1         | 2.08%   |
| Acer Integrated Camera                                                     | 1         | 2.08%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 5         | 50%     |
| Synaptics             | 3         | 30%     |
| LighTuning Technology | 1         | 10%     |
| Elan Microelectronics | 1         | 10%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Unknown                                           | 2         | 20%     |
| Validity Sensors VFS7500 Touch Fingerprint Sensor | 1         | 10%     |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 10%     |
| Validity Sensors VFS300 Fingerprint Reader        | 1         | 10%     |
| Validity Sensors VFS Fingerprint sensor           | 1         | 10%     |
| Validity Sensors VFS 5011 fingerprint sensor      | 1         | 10%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 10%     |
| LighTuning EgisTec Touch Fingerprint Sensor       | 1         | 10%     |
| Elan ELAN:Fingerprint                             | 1         | 10%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 2         | 33.33%  |
| Alcor Micro           | 2         | 33.33%  |
| O2 Micro              | 1         | 16.67%  |
| Gemalto (was Gemplus) | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Notebooks | Percent |
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


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 29        | 55.77%  |
| 1     | 14        | 26.92%  |
| 2     | 6         | 11.54%  |
| 3     | 3         | 5.77%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 9         | 26.47%  |
| Chipcard                 | 6         | 17.65%  |
| Graphics card            | 5         | 14.71%  |
| Net/wireless             | 3         | 8.82%   |
| Card reader              | 3         | 8.82%   |
| Multimedia controller    | 2         | 5.88%   |
| Storage                  | 1         | 2.94%   |
| Net/ethernet             | 1         | 2.94%   |
| Firewire controller      | 1         | 2.94%   |
| Communication controller | 1         | 2.94%   |
| Camera                   | 1         | 2.94%   |
| Bluetooth                | 1         | 2.94%   |

