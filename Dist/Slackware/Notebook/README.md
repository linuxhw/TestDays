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

Total: 69

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| MSI       | Modern 14 B10MW             | [b9cde08864](https://linux-hardware.org/?probe=b9cde08864) | Jul 25, 2022 |
| Sony      | SVE1713A1EW                 | [c3a65d695d](https://linux-hardware.org/?probe=c3a65d695d) | May 10, 2022 |
| Lenovo    | ThinkPad X1 Carbon 5th 2... | [f837aaeb12](https://linux-hardware.org/?probe=f837aaeb12) | May 08, 2022 |
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
| Dynabook  | PORTEGE X50-G               | [da8279a7a9](https://linux-hardware.org/?probe=da8279a7a9) | Sep 22, 2021 |
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
| MSI       | GL73 8RC                    | [44f82bfc01](https://linux-hardware.org/?probe=44f82bfc01) | Nov 09, 2020 |
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
| Lenovo    | IdeaPad P500 20210          | [3d09c5e38d](https://linux-hardware.org/?probe=3d09c5e38d) | Oct 22, 2019 |
| Acer      | Swift SF314-52              | [05f880ecec](https://linux-hardware.org/?probe=05f880ecec) | Oct 21, 2019 |
| Lenovo    | ThinkPad P70 20ERCTO1WW     | [0ceeb50e5e](https://linux-hardware.org/?probe=0ceeb50e5e) | Oct 21, 2019 |
| Lenovo    | ThinkPad T450s 20BW000EU... | [41ca8d1a20](https://linux-hardware.org/?probe=41ca8d1a20) | Oct 21, 2019 |
| ASUSTek   | VivoBook_ASUSLaptop X570... | [c2fd6acb71](https://linux-hardware.org/?probe=c2fd6acb71) | Oct 21, 2019 |
| Dell      | Latitude E7270              | [859e021e2f](https://linux-hardware.org/?probe=859e021e2f) | Oct 20, 2019 |
| Fujitsu   | LIFEBOOK A555               | [e0c6729d5b](https://linux-hardware.org/?probe=e0c6729d5b) | Oct 20, 2019 |
| Lenovo    | ThinkPad T470 20HDCTO1WW    | [0f9287651d](https://linux-hardware.org/?probe=0f9287651d) | Jul 24, 2019 |
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
| Slackware 14.2  | 26        | 49.06%  |
| Slackware 15.0  | 24        | 45.28%  |
| Slackware 14.2+ | 3         | 5.66%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| Slackware | 53        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.15.19           | 6         | 10.34%  |
| 4.19.80           | 4         | 6.9%    |
| 5.3.7             | 2         | 3.45%   |
| 5.17.1            | 2         | 3.45%   |
| 5.13.8            | 2         | 3.45%   |
| 5.7.0             | 1         | 1.72%   |
| 5.5.10            | 1         | 1.72%   |
| 5.4.75            | 1         | 1.72%   |
| 5.4.50            | 1         | 1.72%   |
| 5.4.47            | 1         | 1.72%   |
| 5.4.24toshiba-new | 1         | 1.72%   |
| 5.4.2             | 1         | 1.72%   |
| 5.4.139-jw        | 1         | 1.72%   |
| 5.4.13            | 1         | 1.72%   |
| 5.2.2             | 1         | 1.72%   |
| 5.17.5            | 1         | 1.72%   |
| 5.17.2            | 1         | 1.72%   |
| 5.16.9-joe1       | 1         | 1.72%   |
| 5.16.12           | 1         | 1.72%   |
| 5.15.37.a         | 1         | 1.72%   |
| 5.15.33.kjh       | 1         | 1.72%   |
| 5.15.27           | 1         | 1.72%   |
| 5.15.1            | 1         | 1.72%   |
| 5.14.9            | 1         | 1.72%   |
| 5.14.8            | 1         | 1.72%   |
| 5.14.10           | 1         | 1.72%   |
| 5.14.0            | 1         | 1.72%   |
| 5.13.5            | 1         | 1.72%   |
| 5.13.11           | 1         | 1.72%   |
| 5.13.0.a          | 1         | 1.72%   |
| 5.10.91           | 1         | 1.72%   |
| 5.10.4            | 1         | 1.72%   |
| 5.10.3            | 1         | 1.72%   |
| 5.10.21           | 1         | 1.72%   |
| 5.10.19           | 1         | 1.72%   |
| 5.10.1-pmagic     | 1         | 1.72%   |
| 4.4.88            | 1         | 1.72%   |
| 4.4.276           | 1         | 1.72%   |
| 4.4.240           | 1         | 1.72%   |
| 4.4.227           | 1         | 1.72%   |
| 4.4.202           | 1         | 1.72%   |
| 4.4.190-smp       | 1         | 1.72%   |
| 4.4.190           | 1         | 1.72%   |
| 4.19.79           | 1         | 1.72%   |
| 4.19.76           | 1         | 1.72%   |
| 4.19.206.a        | 1         | 1.72%   |
| 4.16.18           | 1         | 1.72%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.15.19  | 6         | 10.34%  |
| 4.19.80  | 4         | 6.9%    |
| 5.3.7    | 2         | 3.45%   |
| 5.17.1   | 2         | 3.45%   |
| 5.13.8   | 2         | 3.45%   |
| 4.4.190  | 2         | 3.45%   |
| 5.7.0    | 1         | 1.72%   |
| 5.5.10   | 1         | 1.72%   |
| 5.4.75   | 1         | 1.72%   |
| 5.4.50   | 1         | 1.72%   |
| 5.4.47   | 1         | 1.72%   |
| 5.4.24   | 1         | 1.72%   |
| 5.4.2    | 1         | 1.72%   |
| 5.4.139  | 1         | 1.72%   |
| 5.4.13   | 1         | 1.72%   |
| 5.2.2    | 1         | 1.72%   |
| 5.17.5   | 1         | 1.72%   |
| 5.17.2   | 1         | 1.72%   |
| 5.16.9   | 1         | 1.72%   |
| 5.16.12  | 1         | 1.72%   |
| 5.15.37  | 1         | 1.72%   |
| 5.15.33  | 1         | 1.72%   |
| 5.15.27  | 1         | 1.72%   |
| 5.15.1   | 1         | 1.72%   |
| 5.14.9   | 1         | 1.72%   |
| 5.14.8   | 1         | 1.72%   |
| 5.14.10  | 1         | 1.72%   |
| 5.14.0   | 1         | 1.72%   |
| 5.13.5   | 1         | 1.72%   |
| 5.13.11  | 1         | 1.72%   |
| 5.13.0   | 1         | 1.72%   |
| 5.10.91  | 1         | 1.72%   |
| 5.10.4   | 1         | 1.72%   |
| 5.10.3   | 1         | 1.72%   |
| 5.10.21  | 1         | 1.72%   |
| 5.10.19  | 1         | 1.72%   |
| 5.10.1   | 1         | 1.72%   |
| 4.4.88   | 1         | 1.72%   |
| 4.4.276  | 1         | 1.72%   |
| 4.4.240  | 1         | 1.72%   |
| 4.4.227  | 1         | 1.72%   |
| 4.4.202  | 1         | 1.72%   |
| 4.19.79  | 1         | 1.72%   |
| 4.19.76  | 1         | 1.72%   |
| 4.19.206 | 1         | 1.72%   |
| 4.16.18  | 1         | 1.72%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 10        | 17.54%  |
| 5.4     | 7         | 12.28%  |
| 4.4     | 7         | 12.28%  |
| 4.19    | 7         | 12.28%  |
| 5.10    | 6         | 10.53%  |
| 5.13    | 5         | 8.77%   |
| 5.17    | 4         | 7.02%   |
| 5.14    | 3         | 5.26%   |
| 5.3     | 2         | 3.51%   |
| 5.16    | 2         | 3.51%   |
| 5.7     | 1         | 1.75%   |
| 5.5     | 1         | 1.75%   |
| 5.2     | 1         | 1.75%   |
| 4.16    | 1         | 1.75%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 52        | 98.11%  |
| i686   | 1         | 1.89%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| XFCE          | 16        | 29.63%  |
| Unknown       | 16        | 29.63%  |
| KDE5          | 15        | 27.78%  |
| KDE           | 3         | 5.56%   |
| xwmconfig     | 1         | 1.85%   |
| MATE          | 1         | 1.85%   |
| LXQt          | 1         | 1.85%   |
| Enlightenment | 1         | 1.85%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 43        | 79.63%  |
| Tty     | 9         | 16.67%  |
| Wayland | 2         | 3.7%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 23        | 42.59%  |
| SDDM    | 20        | 37.04%  |
| XDM     | 11        | 20.37%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 31        | 58.49%  |
| Unknown | 14        | 26.42%  |
| fr_FR   | 3         | 5.66%   |
| pt_BR   | 2         | 3.77%   |
| ru_RU   | 1         | 1.89%   |
| pl_PL   | 1         | 1.89%   |
| de_DE   | 1         | 1.89%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 28        | 51.85%  |
| EFI  | 26        | 48.15%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 45        | 84.91%  |
| Btrfs   | 5         | 9.43%   |
| Overlay | 3         | 5.66%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 35        | 64.81%  |
| MBR     | 14        | 25.93%  |
| Unknown | 5         | 9.26%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 46        | 83.64%  |
| Yes       | 9         | 16.36%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 31        | 58.49%  |
| Yes       | 22        | 41.51%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 12        | 22.64%  |
| Hewlett-Packard     | 11        | 20.75%  |
| Dell                | 7         | 13.21%  |
| MSI                 | 5         | 9.43%   |
| ASUSTek Computer    | 4         | 7.55%   |
| Toshiba             | 3         | 5.66%   |
| Notebook            | 2         | 3.77%   |
| Dynabook            | 2         | 3.77%   |
| Acer                | 2         | 3.77%   |
| System76            | 1         | 1.89%   |
| Sony                | 1         | 1.89%   |
| Samsung Electronics | 1         | 1.89%   |
| Fujitsu             | 1         | 1.89%   |
| Framework           | 1         | 1.89%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Toshiba Satellite P50-A-12Z              | 1         | 1.89%   |
| Toshiba Satellite C660                   | 1         | 1.89%   |
| Toshiba PORTEGE Z30-A                    | 1         | 1.89%   |
| System76 Oryx Pro                        | 1         | 1.89%   |
| Sony SVE1713A1EW                         | 1         | 1.89%   |
| Samsung 300E5M/300E5L                    | 1         | 1.89%   |
| Notebook X170KM-G                        | 1         | 1.89%   |
| Notebook NL40_50CU                       | 1         | 1.89%   |
| MSI Modern 14 B11MO                      | 1         | 1.89%   |
| MSI Modern 14 B10MW                      | 1         | 1.89%   |
| MSI GP76 Leopard 11UG                    | 1         | 1.89%   |
| MSI GL73 8RC                             | 1         | 1.89%   |
| MSI GE76 Raider 11UE                     | 1         | 1.89%   |
| Lenovo V330-14ARR 81B1                   | 1         | 1.89%   |
| Lenovo ThinkPad X230 2325P38             | 1         | 1.89%   |
| Lenovo ThinkPad X1 Carbon 7th 20R10015US | 1         | 1.89%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS04300 | 1         | 1.89%   |
| Lenovo ThinkPad T470 20HDCTO1WW          | 1         | 1.89%   |
| Lenovo ThinkPad T450s 20BW000EUS         | 1         | 1.89%   |
| Lenovo ThinkPad T400 6474BV7             | 1         | 1.89%   |
| Lenovo ThinkPad P70 20ERCTO1WW           | 1         | 1.89%   |
| Lenovo ThinkPad L440 20ASS05K00          | 1         | 1.89%   |
| Lenovo ThinkPad Edge E530c 336669G       | 1         | 1.89%   |
| Lenovo IdeaPad P500 20210                | 1         | 1.89%   |
| Lenovo IdeaPad 310-15ISK 80SM            | 1         | 1.89%   |
| HP ProBook 6570b                         | 1         | 1.89%   |
| HP Pavilion Notebook                     | 1         | 1.89%   |
| HP Pavilion Gaming Laptop 16-a0xxx       | 1         | 1.89%   |
| HP Pavilion Gaming Laptop 15-ec1xxx      | 1         | 1.89%   |
| HP Laptop 15-da0xxx                      | 1         | 1.89%   |
| HP Laptop 15-bs2xx                       | 1         | 1.89%   |
| HP Laptop 15-bs1xx                       | 1         | 1.89%   |
| HP EliteBook Folio 1020 G1 SE            | 1         | 1.89%   |
| HP EliteBook 840 G5                      | 1         | 1.89%   |
| HP 245 G7 Notebook PC                    | 1         | 1.89%   |
| HP 15 Notebook PC                        | 1         | 1.89%   |
| Fujitsu LIFEBOOK A555                    | 1         | 1.89%   |
| Framework Laptop                         | 1         | 1.89%   |
| Dynabook PORTEGE X50-G                   | 1         | 1.89%   |
| Dynabook P1-C7MP-BL                      | 1         | 1.89%   |
| Dell Vostro 3500                         | 1         | 1.89%   |
| Dell Precision M4700                     | 1         | 1.89%   |
| Dell Precision M4600                     | 1         | 1.89%   |
| Dell Latitude E7270                      | 1         | 1.89%   |
| Dell Latitude E5500                      | 1         | 1.89%   |
| Dell Latitude 3520                       | 1         | 1.89%   |
| Dell Inspiron 15-3552                    | 1         | 1.89%   |
| ASUS VivoBook_ASUSLaptop X570ZD_K570ZD   | 1         | 1.89%   |
| ASUS ROG Zephyrus G14 GA401IV_GA401IV    | 1         | 1.89%   |
| ASUS P53E                                | 1         | 1.89%   |
| ASUS 1000H                               | 1         | 1.89%   |
| Acer Swift SF314-52                      | 1         | 1.89%   |
| Acer Aspire E1-572                       | 1         | 1.89%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 9         | 16.98%  |
| HP Pavilion         | 3         | 5.66%   |
| HP Laptop           | 3         | 5.66%   |
| Dell Latitude       | 3         | 5.66%   |
| Toshiba Satellite   | 2         | 3.77%   |
| MSI Modern          | 2         | 3.77%   |
| Lenovo IdeaPad      | 2         | 3.77%   |
| HP EliteBook        | 2         | 3.77%   |
| Dell Precision      | 2         | 3.77%   |
| Toshiba PORTEGE     | 1         | 1.89%   |
| System76 Oryx       | 1         | 1.89%   |
| Sony SVE1713A1EW    | 1         | 1.89%   |
| Samsung 300E5M      | 1         | 1.89%   |
| Notebook X170KM-G   | 1         | 1.89%   |
| Notebook NL40       | 1         | 1.89%   |
| MSI GP76            | 1         | 1.89%   |
| MSI GL73            | 1         | 1.89%   |
| MSI GE76            | 1         | 1.89%   |
| Lenovo V330-14ARR   | 1         | 1.89%   |
| HP ProBook          | 1         | 1.89%   |
| HP 245              | 1         | 1.89%   |
| HP 15               | 1         | 1.89%   |
| Fujitsu LIFEBOOK    | 1         | 1.89%   |
| Framework Laptop    | 1         | 1.89%   |
| Dynabook PORTEGE    | 1         | 1.89%   |
| Dynabook P1-C7MP-BL | 1         | 1.89%   |
| Dell Vostro         | 1         | 1.89%   |
| Dell Inspiron       | 1         | 1.89%   |
| ASUS VivoBook       | 1         | 1.89%   |
| ASUS ROG            | 1         | 1.89%   |
| ASUS P53E           | 1         | 1.89%   |
| ASUS 1000H          | 1         | 1.89%   |
| Acer Swift          | 1         | 1.89%   |
| Acer Aspire         | 1         | 1.89%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 8         | 15.09%  |
| 2021 | 6         | 11.32%  |
| 2012 | 6         | 11.32%  |
| 2019 | 5         | 9.43%   |
| 2017 | 5         | 9.43%   |
| 2015 | 5         | 9.43%   |
| 2018 | 4         | 7.55%   |
| 2016 | 3         | 5.66%   |
| 2014 | 3         | 5.66%   |
| 2008 | 3         | 5.66%   |
| 2011 | 2         | 3.77%   |
| 2010 | 2         | 3.77%   |
| 2013 | 1         | 1.89%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 53        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 53        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 50        | 94.34%  |
| Yes  | 3         | 5.66%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 16        | 30.19%  |
| 3.01-4.0    | 11        | 20.75%  |
| 8.01-16.0   | 11        | 20.75%  |
| 16.01-24.0  | 8         | 15.09%  |
| 32.01-64.0  | 3         | 5.66%   |
| 24.01-32.0  | 1         | 1.89%   |
| 64.01-256.0 | 1         | 1.89%   |
| 1.01-2.0    | 1         | 1.89%   |
| 0.51-1.0    | 1         | 1.89%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 20        | 36.36%  |
| 2.01-3.0   | 16        | 29.09%  |
| 4.01-8.0   | 8         | 14.55%  |
| 3.01-4.0   | 4         | 7.27%   |
| 0.51-1.0   | 3         | 5.45%   |
| 0.01-0.5   | 2         | 3.64%   |
| 16.01-24.0 | 1         | 1.82%   |
| 8.01-16.0  | 1         | 1.82%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 39        | 72.22%  |
| 2      | 13        | 24.07%  |
| 4      | 1         | 1.85%   |
| 3      | 1         | 1.85%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 37        | 69.81%  |
| Yes       | 16        | 30.19%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 46        | 86.79%  |
| No        | 7         | 13.21%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 53        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 48        | 90.57%  |
| No        | 5         | 9.43%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 12        | 22.64%  |
| Portugal     | 4         | 7.55%   |
| Brazil       | 4         | 7.55%   |
| UK           | 3         | 5.66%   |
| Kazakhstan   | 3         | 5.66%   |
| Japan        | 3         | 5.66%   |
| France       | 3         | 5.66%   |
| Canada       | 3         | 5.66%   |
| Sweden       | 2         | 3.77%   |
| South Africa | 2         | 3.77%   |
| Poland       | 2         | 3.77%   |
| India        | 2         | 3.77%   |
| Germany      | 2         | 3.77%   |
| Spain        | 1         | 1.89%   |
| Serbia       | 1         | 1.89%   |
| Russia       | 1         | 1.89%   |
| Philippines  | 1         | 1.89%   |
| Mexico       | 1         | 1.89%   |
| Italy        | 1         | 1.89%   |
| Finland      | 1         | 1.89%   |
| Chile        | 1         | 1.89%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lisbon                 | 3         | 5.45%   |
| Warsaw                 | 2         | 3.64%   |
| Ust-Kamenogorsk        | 2         | 3.64%   |
| Wokingham              | 1         | 1.82%   |
| Winnipeg               | 1         | 1.82%   |
| Visconde do Rio Branco | 1         | 1.82%   |
| Tsukuba                | 1         | 1.82%   |
| Tendo                  | 1         | 1.82%   |
| Skövde                | 1         | 1.82%   |
| San Antonio            | 1         | 1.82%   |
| Round Rock             | 1         | 1.82%   |
| Roknaes                | 1         | 1.82%   |
| Reno                   | 1         | 1.82%   |
| Redding                | 1         | 1.82%   |
| Puente Alto            | 1         | 1.82%   |
| Plainwell              | 1         | 1.82%   |
| Pinhal Novo            | 1         | 1.82%   |
| Pesaro                 | 1         | 1.82%   |
| Pasay                  | 1         | 1.82%   |
| Paris                  | 1         | 1.82%   |
| Ōtsu                  | 1         | 1.82%   |
| Oberstreit             | 1         | 1.82%   |
| Northport              | 1         | 1.82%   |
| Montreal               | 1         | 1.82%   |
| Milan                  | 1         | 1.82%   |
| Mexico City            | 1         | 1.82%   |
| McKinney               | 1         | 1.82%   |
| Luxeuil-les-Bains      | 1         | 1.82%   |
| Lins                   | 1         | 1.82%   |
| League City            | 1         | 1.82%   |
| Kstovo                 | 1         | 1.82%   |
| Karaganda              | 1         | 1.82%   |
| Johannesburg           | 1         | 1.82%   |
| Jaipur                 | 1         | 1.82%   |
| Hornsey                | 1         | 1.82%   |
| Helsinki               | 1         | 1.82%   |
| Hayward                | 1         | 1.82%   |
| Fortaleza              | 1         | 1.82%   |
| Faridabad              | 1         | 1.82%   |
| Chessy                 | 1         | 1.82%   |
| Carrollton             | 1         | 1.82%   |
| Cape Town              | 1         | 1.82%   |
| Canandaigua            | 1         | 1.82%   |
| Campinas               | 1         | 1.82%   |
| Borken                 | 1         | 1.82%   |
| Bengaluru              | 1         | 1.82%   |
| Belgrade               | 1         | 1.82%   |
| Barry                  | 1         | 1.82%   |
| Barrie                 | 1         | 1.82%   |
| Algeciras              | 1         | 1.82%   |
| Abingdon               | 1         | 1.82%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 15        | 20     | 23.08%  |
| WDC                 | 11        | 13     | 16.92%  |
| Toshiba             | 5         | 5      | 7.69%   |
| Seagate             | 5         | 5      | 7.69%   |
| Crucial             | 4         | 5      | 6.15%   |
| SanDisk             | 3         | 3      | 4.62%   |
| Kingston            | 3         | 3      | 4.62%   |
| HGST                | 3         | 3      | 4.62%   |
| Unknown             | 2         | 2      | 3.08%   |
| SK hynix            | 2         | 2      | 3.08%   |
| Micron Technology   | 2         | 2      | 3.08%   |
| Intel               | 2         | 2      | 3.08%   |
| Gigabyte Technology | 2         | 2      | 3.08%   |
| Plextor             | 1         | 1      | 1.54%   |
| Patriot             | 1         | 2      | 1.54%   |
| Netac               | 1         | 1      | 1.54%   |
| KIOXIA              | 1         | 1      | 1.54%   |
| Hewlett-Packard     | 1         | 2      | 1.54%   |
| Dogfish             | 1         | 1      | 1.54%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| WDC WD10SPZX-60Z10T0 1TB                | 2         | 2.9%    |
| Toshiba MQ04ABF100 1TB                  | 2         | 2.9%    |
| WDC WDS500G2B0B-00YS70 500GB SSD        | 1         | 1.45%   |
| WDC WD7500BPVT-24HXZT3 752GB            | 1         | 1.45%   |
| WDC WD5000LPCX-60VHAT1 500GB            | 1         | 1.45%   |
| WDC WD10JPVX-35JC3T0 1TB                | 1         | 1.45%   |
| WDC WD10JPVX-16JC3T3 1TB                | 1         | 1.45%   |
| WDC WD10JPVT-08A1YT2 1TB                | 1         | 1.45%   |
| WDC WD10JPLX-00MBPT0 1TB                | 1         | 1.45%   |
| WDC PC SN530 SDBPNPZ-1T00-1002 1TB      | 1         | 1.45%   |
| WDC PC SN520 SDAPNUW-256G-1102 256GB    | 1         | 1.45%   |
| Unknown SD32G  32GB                     | 1         | 1.45%   |
| Unknown SC32G  32GB                     | 1         | 1.45%   |
| Toshiba MQ01ABF050 500GB                | 1         | 1.45%   |
| Toshiba MK2565GSXN 250GB                | 1         | 1.45%   |
| Toshiba MK1646GSX 160GB                 | 1         | 1.45%   |
| SK hynix HFM001TD3JX013N 1TB            | 1         | 1.45%   |
| SK hynix BC511 HFM512GDJTNI-82A0A 512GB | 1         | 1.45%   |
| Seagate ST9160827AS 160GB               | 1         | 1.45%   |
| Seagate ST9160412AS 160GB               | 1         | 1.45%   |
| Seagate ST500VT000-1DK142 500GB         | 1         | 1.45%   |
| Seagate ST1000LM048-2E7172 1TB          | 1         | 1.45%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 1         | 1.45%   |
| SanDisk Ultra II 960GB SSD              | 1         | 1.45%   |
| SanDisk SDSSDA240G 240GB                | 1         | 1.45%   |
| SanDisk SD8TN8U256G1001 256GB SSD       | 1         | 1.45%   |
| Samsung SSD 980 PRO 500GB               | 1         | 1.45%   |
| Samsung SSD 980 PRO 2TB                 | 1         | 1.45%   |
| Samsung SSD 970 EVO Plus 2TB            | 1         | 1.45%   |
| Samsung SSD 970 EVO Plus 250GB          | 1         | 1.45%   |
| Samsung SSD 970 EVO 2TB                 | 1         | 1.45%   |
| Samsung SSD 870 EVO 1TB                 | 1         | 1.45%   |
| Samsung SSD 860 QVO 2TB                 | 1         | 1.45%   |
| Samsung SSD 860 EVO mSATA 500GB         | 1         | 1.45%   |
| Samsung SSD 840 EVO 250GB               | 1         | 1.45%   |
| Samsung NVMe SSD Drive 256GB            | 1         | 1.45%   |
| Samsung MZVLQ512HALU-000H1 512GB        | 1         | 1.45%   |
| Samsung MZVLB512HAJQ-000L7 512GB        | 1         | 1.45%   |
| Samsung MZVLB1T0HBLR-00007 1TB          | 1         | 1.45%   |
| Samsung MZVL21T0HCLR-00B00 1TB          | 1         | 1.45%   |
| Samsung MZVKW512HMJP-000H1 512GB        | 1         | 1.45%   |
| Samsung MZMTE256HMHP-00000 256GB SSD    | 1         | 1.45%   |
| Samsung MZ7LN256HCHP-000L7 256GB SSD    | 1         | 1.45%   |
| Samsung MZ7LN256HAJQ-000L2 256GB SSD    | 1         | 1.45%   |
| Plextor PX-128M6S 128GB SSD             | 1         | 1.45%   |
| Patriot Burst 960GB SSD                 | 1         | 1.45%   |
| Patriot Burst 120GB SSD                 | 1         | 1.45%   |
| Netac SSD 720GB                         | 1         | 1.45%   |
| Micron 2210_MTFDHBA512QFD 512GB         | 1         | 1.45%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD     | 1         | 1.45%   |
| KIOXIA KBG40ZNS256G NVMe 256GB          | 1         | 1.45%   |
| Kingston SUV400S37240G 240GB SSD        | 1         | 1.45%   |
| Kingston SA400S37240G 240GB SSD         | 1         | 1.45%   |
| Kingston RBUSNS8154P3128GJ 128GB        | 1         | 1.45%   |
| Intel SSDPEKKF256G7L 256GB              | 1         | 1.45%   |
| Intel SSDPEKKF010T8L 1TB                | 1         | 1.45%   |
| HGST HTS725050A7E630 500GB              | 1         | 1.45%   |
| HGST HTS545050A7E380 500GB              | 1         | 1.45%   |
| HGST HTS541010A9E680 1TB                | 1         | 1.45%   |
| HP SSD EX950 2TB                        | 1         | 1.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 8         | 10     | 38.1%   |
| Toshiba | 5         | 5      | 23.81%  |
| Seagate | 5         | 5      | 23.81%  |
| HGST    | 3         | 3      | 14.29%  |

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
| Plextor             | 1         | 1      | 4.76%   |
| Patriot             | 1         | 2      | 4.76%   |
| Netac               | 1         | 1      | 4.76%   |
| Micron Technology   | 1         | 1      | 4.76%   |
| Gigabyte Technology | 1         | 1      | 4.76%   |
| Dogfish             | 1         | 1      | 4.76%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 21        | 26     | 32.81%  |
| HDD  | 21        | 23     | 32.81%  |
| SSD  | 20        | 24     | 31.25%  |
| MMC  | 2         | 2      | 3.13%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 36        | 47     | 61.02%  |
| NVMe | 21        | 26     | 35.59%  |
| MMC  | 2         | 2      | 3.39%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 24        | 28     | 58.54%  |
| 0.51-1.0   | 16        | 18     | 39.02%  |
| 1.01-2.0   | 1         | 1      | 2.44%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 501-1000       | 16        | 30.19%  |
| 101-250        | 15        | 28.3%   |
| 251-500        | 11        | 20.75%  |
| 1001-2000      | 5         | 9.43%   |
| 1-20           | 3         | 5.66%   |
| More than 3000 | 1         | 1.89%   |
| 51-100         | 1         | 1.89%   |
| Unknown        | 1         | 1.89%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 101-250   | 11        | 19.64%  |
| 1-20      | 11        | 19.64%  |
| 21-50     | 10        | 17.86%  |
| 51-100    | 8         | 14.29%  |
| 251-500   | 7         | 12.5%   |
| 501-1000  | 7         | 12.5%   |
| 1001-2000 | 1         | 1.79%   |
| Unknown   | 1         | 1.79%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD5000LPCX-60VHAT1 500GB        | 1         | 1      | 14.29%  |
| WDC WD10JPLX-00MBPT0 1TB            | 1         | 1      | 14.29%  |
| Toshiba MK2565GSXN 250GB            | 1         | 1      | 14.29%  |
| Samsung Electronics SSD 870 EVO 1TB | 1         | 1      | 14.29%  |
| Plextor PX-128M6S 128GB SSD         | 1         | 1      | 14.29%  |
| HGST HTS725050A7E630 500GB          | 1         | 1      | 14.29%  |
| HGST HTS545050A7E380 500GB          | 1         | 1      | 14.29%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 2         | 2      | 28.57%  |
| HGST                | 2         | 2      | 28.57%  |
| Toshiba             | 1         | 1      | 14.29%  |
| Samsung Electronics | 1         | 1      | 14.29%  |
| Plextor             | 1         | 1      | 14.29%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 2         | 2      | 40%     |
| HGST    | 2         | 2      | 40%     |
| Toshiba | 1         | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 5         | 5      | 71.43%  |
| SSD  | 2         | 2      | 28.57%  |

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
| Works    | 44        | 59     | 74.58%  |
| Detected | 8         | 9      | 13.56%  |
| Malfunc  | 7         | 7      | 11.86%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 39        | 61.9%   |
| Samsung Electronics         | 9         | 14.29%  |
| AMD                         | 5         | 7.94%   |
| SK hynix                    | 2         | 3.17%   |
| SanDisk                     | 2         | 3.17%   |
| Phison Electronics          | 1         | 1.59%   |
| Micron/Crucial Technology   | 1         | 1.59%   |
| Micron Technology           | 1         | 1.59%   |
| KIOXIA                      | 1         | 1.59%   |
| Kingston Technology Company | 1         | 1.59%   |
| Biwin Storage Technology    | 1         | 1.59%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 5         | 7.69%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 5         | 7.69%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 5         | 7.69%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 4         | 6.15%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 4         | 6.15%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 4         | 6.15%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 4.62%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 3.08%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 3.08%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 3.08%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2         | 3.08%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 2         | 3.08%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 2         | 3.08%   |
| SK hynix Gold P31 SSD                                                            | 1         | 1.54%   |
| SK hynix BC511                                                                   | 1         | 1.54%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 1.54%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 1.54%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 1.54%   |
| Phison NVMe Storage Controller                                                   | 1         | 1.54%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1         | 1.54%   |
| Micron Non-Volatile memory controller                                            | 1         | 1.54%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 1         | 1.54%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 1.54%   |
| Intel Tiger Lake-LP SATA Controller                                              | 1         | 1.54%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 1         | 1.54%   |
| Intel SSD 600P Series                                                            | 1         | 1.54%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 1.54%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 1.54%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 1.54%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 1.54%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 1         | 1.54%   |
| Intel 6 Series/C200 Series Chipset Family IDE-r Controller                       | 1         | 1.54%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 1         | 1.54%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 1         | 1.54%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 1         | 1.54%   |
| Biwin Storage Non-Volatile memory controller                                     | 1         | 1.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 36        | 56.25%  |
| NVMe | 21        | 32.81%  |
| RAID | 5         | 7.81%   |
| IDE  | 2         | 3.13%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 48        | 90.57%  |
| AMD    | 5         | 9.43%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 3         | 5.66%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 3.77%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 3.77%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 3.77%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 3.77%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 2         | 3.77%   |
| Intel Pentium CPU P6100 @ 2.00GHz             | 1         | 1.89%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 1.89%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 1         | 1.89%   |
| Intel Core M-5Y51 CPU @ 1.10GHz               | 1         | 1.89%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 1.89%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 1.89%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 1.89%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 1.89%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 1.89%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 1.89%   |
| Intel Core i7-3840QM CPU @ 2.80GHz            | 1         | 1.89%   |
| Intel Core i7-2860QM CPU @ 2.50GHz            | 1         | 1.89%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 1         | 1.89%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 1         | 1.89%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 1.89%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 1.89%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 1.89%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 1         | 1.89%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 1.89%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 1.89%   |
| Intel Core i5-3360M CPU @ 2.80GHz             | 1         | 1.89%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 1.89%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 1.89%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 1.89%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 1         | 1.89%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 1         | 1.89%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 1         | 1.89%   |
| Intel Core i3-6100U CPU @ 2.30GHz             | 1         | 1.89%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 1.89%   |
| Intel Core i3-4000M CPU @ 2.40GHz             | 1         | 1.89%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz          | 1         | 1.89%   |
| Intel Core 2 CPU P8400 @ 2.26GHz              | 1         | 1.89%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 1         | 1.89%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 1         | 1.89%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 1         | 1.89%   |
| Intel 11th Gen Core i9-11900K @ 3.50GHz       | 1         | 1.89%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1         | 1.89%   |
| AMD Ryzen 9 4900HS with Radeon Graphics       | 1         | 1.89%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 1         | 1.89%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 1.89%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 14        | 26.42%  |
| Intel Core i7    | 12        | 22.64%  |
| Other            | 7         | 13.21%  |
| Intel Core i3    | 6         | 11.32%  |
| AMD Ryzen 5      | 4         | 7.55%   |
| Intel Pentium    | 3         | 5.66%   |
| Intel Celeron    | 2         | 3.77%   |
| Intel Core M     | 1         | 1.89%   |
| Intel Core 2 Duo | 1         | 1.89%   |
| Intel Core 2     | 1         | 1.89%   |
| Intel Atom       | 1         | 1.89%   |
| AMD Ryzen 9      | 1         | 1.89%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 26        | 49.06%  |
| 4      | 18        | 33.96%  |
| 8      | 6         | 11.32%  |
| 6      | 2         | 3.77%   |
| 1      | 1         | 1.89%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 53        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 46        | 86.79%  |
| 1      | 7         | 13.21%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 50        | 94.34%  |
| Unknown        | 2         | 3.77%   |
| 32-bit         | 1         | 1.89%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 10        | 18.87%  |
| 0x306a9    | 6         | 11.32%  |
| 0x306d4    | 4         | 7.55%   |
| 0x806ec    | 3         | 5.66%   |
| 0x806ea    | 3         | 5.66%   |
| 0x806d1    | 3         | 5.66%   |
| 0x806c1    | 3         | 5.66%   |
| 0x406e3    | 3         | 5.66%   |
| 0x206a7    | 2         | 3.77%   |
| 0xa0671    | 1         | 1.89%   |
| 0xa0660    | 1         | 1.89%   |
| 0xa0652    | 1         | 1.89%   |
| 0x806e9    | 1         | 1.89%   |
| 0x706a1    | 1         | 1.89%   |
| 0x6fd      | 1         | 1.89%   |
| 0x506e3    | 1         | 1.89%   |
| 0x406c4    | 1         | 1.89%   |
| 0x40651    | 1         | 1.89%   |
| 0x306c3    | 1         | 1.89%   |
| 0x20655    | 1         | 1.89%   |
| 0x106c2    | 1         | 1.89%   |
| 0x1067a    | 1         | 1.89%   |
| 0x08600106 | 1         | 1.89%   |
| 0x08108109 | 1         | 1.89%   |
| 0x0810100b | 1         | 1.89%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 10        | 18.87%  |
| IvyBridge     | 6         | 11.32%  |
| Skylake       | 5         | 9.43%   |
| Icelake       | 4         | 7.55%   |
| Haswell       | 4         | 7.55%   |
| Broadwell     | 4         | 7.55%   |
| TigerLake     | 3         | 5.66%   |
| Zen 2         | 2         | 3.77%   |
| Zen           | 2         | 3.77%   |
| Westmere      | 2         | 3.77%   |
| Silvermont    | 2         | 3.77%   |
| SandyBridge   | 2         | 3.77%   |
| CometLake     | 2         | 3.77%   |
| Zen+          | 1         | 1.89%   |
| Penryn        | 1         | 1.89%   |
| Goldmont plus | 1         | 1.89%   |
| Core          | 1         | 1.89%   |
| Bonnell       | 1         | 1.89%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 42        | 66.67%  |
| Nvidia | 13        | 20.63%  |
| AMD    | 8         | 12.7%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 6.25%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 6.25%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 3         | 4.69%   |
| Intel UHD Graphics 620                                                                   | 3         | 4.69%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 4.69%   |
| Intel HD Graphics 5500                                                                   | 3         | 4.69%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 4.69%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 3.13%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 3.13%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 3.13%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 3.13%   |
| Intel HD Graphics 620                                                                    | 2         | 3.13%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 3.13%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 3.13%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 3.13%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 3.13%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 2         | 3.13%   |
| AMD Renoir                                                                               | 2         | 3.13%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 3.13%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 1         | 1.56%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 1.56%   |
| Nvidia GM204GLM [Quadro M3000M]                                                          | 1         | 1.56%   |
| Nvidia GK107M [GeForce GT 745M]                                                          | 1         | 1.56%   |
| Nvidia GF106GLM [Quadro 2000M]                                                           | 1         | 1.56%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 1.56%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 1         | 1.56%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 1.56%   |
| Intel HD Graphics 5300                                                                   | 1         | 1.56%   |
| Intel HD Graphics 530                                                                    | 1         | 1.56%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 1.56%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 1.56%   |
| Intel Comet Lake UHD Graphics                                                            | 1         | 1.56%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.56%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1         | 1.56%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1         | 1.56%   |
| AMD Chelsea XT GL [FirePro M4000]                                                        | 1         | 1.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 35        | 66.04%  |
| Intel + Nvidia | 7         | 13.21%  |
| 1 x AMD        | 6         | 11.32%  |
| 1 x Nvidia     | 3         | 5.66%   |
| AMD + Nvidia   | 2         | 3.77%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 49        | 92.45%  |
| Proprietary | 3         | 5.66%   |
| Unknown     | 1         | 1.89%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 37        | 68.52%  |
| 1.01-2.0   | 5         | 9.26%   |
| 0.51-1.0   | 4         | 7.41%   |
| 0.01-0.5   | 3         | 5.56%   |
| 7.01-8.0   | 2         | 3.7%    |
| 3.01-4.0   | 2         | 3.7%    |
| 5.01-6.0   | 1         | 1.85%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| BOE                 | 12        | 21.05%  |
| LG Display          | 11        | 19.3%   |
| Chimei Innolux      | 10        | 17.54%  |
| AU Optronics        | 8         | 14.04%  |
| Sharp               | 4         | 7.02%   |
| Samsung Electronics | 4         | 7.02%   |
| Hewlett-Packard     | 2         | 3.51%   |
| Sony                | 1         | 1.75%   |
| PANDA               | 1         | 1.75%   |
| Panasonic           | 1         | 1.75%   |
| Lenovo              | 1         | 1.75%   |
| Goldstar            | 1         | 1.75%   |
| Dell                | 1         | 1.75%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 2         | 3.51%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch        | 2         | 3.51%   |
| Sony TV SNY8102 1360x768 1600x900mm 72.3-inch                        | 1         | 1.75%   |
| Sharp LQ173M1JW05 SHP14EC 1920x1080 380x210mm 17.1-inch              | 1         | 1.75%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch              | 1         | 1.75%   |
| Sharp LQ125T1JW02 SHP142F 2560x1440 277x155mm 12.5-inch              | 1         | 1.75%   |
| Sharp LCD Monitor SHP14C4 1920x1080 344x194mm 15.5-inch              | 1         | 1.75%   |
| Samsung Electronics SyncMaster SAM0428 1680x1050 459x296mm 21.5-inch | 1         | 1.75%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch | 1         | 1.75%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 1         | 1.75%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch | 1         | 1.75%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch              | 1         | 1.75%   |
| Panasonic TDM13O56 MEI96A2 3000x2000 285x190mm 13.5-inch             | 1         | 1.75%   |
| LG Display LCD Monitor LGD0625 1920x1080 344x194mm 15.5-inch         | 1         | 1.75%   |
| LG Display LCD Monitor LGD0599 1920x1080 309x174mm 14.0-inch         | 1         | 1.75%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch         | 1         | 1.75%   |
| LG Display LCD Monitor LGD0508 1366x768 309x174mm 14.0-inch          | 1         | 1.75%   |
| LG Display LCD Monitor LGD03D7 1366x768 310x174mm 14.0-inch          | 1         | 1.75%   |
| LG Display LCD Monitor LGD0353 1366x768 345x194mm 15.6-inch          | 1         | 1.75%   |
| LG Display LCD Monitor LGD032C 1920x1080 344x194mm 15.5-inch         | 1         | 1.75%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch          | 1         | 1.75%   |
| LG Display LCD Monitor LGD02D9 1920x1080 344x194mm 15.5-inch         | 1         | 1.75%   |
| LG Display LCD Monitor LGD028A 1366x768 344x194mm 15.5-inch          | 1         | 1.75%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch          | 1         | 1.75%   |
| Lenovo LCD Monitor LEN4035 1280x800 303x190mm 14.1-inch              | 1         | 1.75%   |
| Hewlett-Packard P223 HPN3392 1920x1080 477x268mm 21.5-inch           | 1         | 1.75%   |
| Hewlett-Packard 27m HPN3579 1920x1080 598x336mm 27.0-inch            | 1         | 1.75%   |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                  | 1         | 1.75%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                     | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 381x214mm 17.2-inch     | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN15CC 1366x768 344x193mm 15.5-inch      | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN15B6 1366x768 340x190mm 15.3-inch      | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN14FF 1920x1080 309x173mm 13.9-inch     | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch     | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch      | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch      | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN1355 1366x768 293x165mm 13.2-inch      | 1         | 1.75%   |
| BOE LCD Monitor BOE0A85 1920x1080 344x194mm 15.5-inch                | 1         | 1.75%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                | 1         | 1.75%   |
| BOE LCD Monitor BOE08F6 1920x1080 355x200mm 16.0-inch                | 1         | 1.75%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                | 1         | 1.75%   |
| BOE LCD Monitor BOE07C8 3840x2160 309x174mm 14.0-inch                | 1         | 1.75%   |
| BOE LCD Monitor BOE0703 1920x1080 344x194mm 15.5-inch                | 1         | 1.75%   |
| BOE LCD Monitor BOE06F0 1366x768 344x194mm 15.5-inch                 | 1         | 1.75%   |
| BOE LCD Monitor BOE06DF 1920x1080 309x173mm 13.9-inch                | 1         | 1.75%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                 | 1         | 1.75%   |
| BOE LCD Monitor BOE0690 1920x1080 344x193mm 15.5-inch                | 1         | 1.75%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                 | 1         | 1.75%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                 | 1         | 1.75%   |
| AU Optronics LCD Monitor AUO978F 1920x1080 382x215mm 17.3-inch       | 1         | 1.75%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch        | 1         | 1.75%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch       | 1         | 1.75%   |
| AU Optronics LCD Monitor AUO48EC 1366x768 344x193mm 15.5-inch        | 1         | 1.75%   |
| AU Optronics LCD Monitor AUO30ED 1920x1080 344x193mm 15.5-inch       | 1         | 1.75%   |
| AU Optronics LCD Monitor AUO309B 3840x2160 381x214mm 17.2-inch       | 1         | 1.75%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 24        | 43.64%  |
| 1366x768 (WXGA)    | 20        | 36.36%  |
| 3840x2160 (4K)     | 3         | 5.45%   |
| 1600x900 (HD+)     | 3         | 5.45%   |
| 2560x1440 (QHD)    | 1         | 1.82%   |
| 2256x1504          | 1         | 1.82%   |
| 1680x1050 (WSXGA+) | 1         | 1.82%   |
| 1360x768           | 1         | 1.82%   |
| 1280x800 (WXGA)    | 1         | 1.82%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 25        | 43.86%  |
| 14     | 9         | 15.79%  |
| 13     | 8         | 14.04%  |
| 17     | 5         | 8.77%   |
| 12     | 3         | 5.26%   |
| 21     | 2         | 3.51%   |
| 72     | 1         | 1.75%   |
| 27     | 1         | 1.75%   |
| 24     | 1         | 1.75%   |
| 20     | 1         | 1.75%   |
| 16     | 1         | 1.75%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 39        | 68.42%  |
| 351-400     | 7         | 12.28%  |
| 201-300     | 5         | 8.77%   |
| 401-500     | 3         | 5.26%   |
| 501-600     | 2         | 3.51%   |
| 1501-2000   | 1         | 1.75%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 49        | 92.45%  |
| 3/2   | 2         | 3.77%   |
| 16/10 | 2         | 3.77%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 26        | 45.61%  |
| 81-90          | 16        | 28.07%  |
| 121-130        | 5         | 8.77%   |
| 61-70          | 3         | 5.26%   |
| 151-200        | 2         | 3.51%   |
| More than 1000 | 1         | 1.75%   |
| 71-80          | 1         | 1.75%   |
| 301-350        | 1         | 1.75%   |
| 251-300        | 1         | 1.75%   |
| 201-250        | 1         | 1.75%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 26        | 46.43%  |
| 101-120       | 18        | 32.14%  |
| 51-100        | 6         | 10.71%  |
| More than 240 | 3         | 5.36%   |
| 161-240       | 2         | 3.57%   |
| 1-50          | 1         | 1.79%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 47        | 88.68%  |
| 2     | 6         | 11.32%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 40        | 47.06%  |
| Realtek Semiconductor | 26        | 30.59%  |
| Qualcomm Atheros      | 8         | 9.41%   |
| Ralink Technology     | 2         | 2.35%   |
| Broadcom Limited      | 2         | 2.35%   |
| Broadcom              | 2         | 2.35%   |
| ASIX Electronics      | 2         | 2.35%   |
| Sierra Wireless       | 1         | 1.18%   |
| Hewlett-Packard       | 1         | 1.18%   |
| Dell                  | 1         | 1.18%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 17        | 16.04%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 5         | 4.72%   |
| Intel Wireless 8265 / 8275                                                            | 4         | 3.77%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 4         | 3.77%   |
| Intel Wireless 7265                                                                   | 3         | 2.83%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 3         | 2.83%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 3         | 2.83%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 2         | 1.89%   |
| Realtek Killer E3000 2.5GbE Controller                                                | 2         | 1.89%   |
| Ralink MT7601U Wireless Adapter                                                       | 2         | 1.89%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 2         | 1.89%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                             | 2         | 1.89%   |
| Intel Wireless-AC 9260                                                                | 2         | 1.89%   |
| Intel Wireless 8260                                                                   | 2         | 1.89%   |
| Intel Wireless 7260                                                                   | 2         | 1.89%   |
| Intel Wireless 3160                                                                   | 2         | 1.89%   |
| Intel Wi-Fi 6 AX201                                                                   | 2         | 1.89%   |
| Intel Wi-Fi 6 AX200                                                                   | 2         | 1.89%   |
| Intel Tiger Lake PCH CNVi WiFi                                                        | 2         | 1.89%   |
| Intel Ethernet Connection (4) I219-LM                                                 | 2         | 1.89%   |
| Intel Ethernet Connection (3) I218-LM                                                 | 2         | 1.89%   |
| Intel Centrino Ultimate-N 6300                                                        | 2         | 1.89%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 2         | 1.89%   |
| Sierra Wireless EM7305                                                                | 1         | 0.94%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 1         | 0.94%   |
| Realtek RTL8723DE Wireless Network Adapter                                            | 1         | 0.94%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                       | 1         | 0.94%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 0.94%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                              | 1         | 0.94%   |
| Realtek RTL8125 2.5GbE Controller                                                     | 1         | 0.94%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 1         | 0.94%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                      | 1         | 0.94%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 1         | 0.94%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                         | 1         | 0.94%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                        | 1         | 0.94%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 0.94%   |
| Intel Wireless 3165                                                                   | 1         | 0.94%   |
| Intel WiFi Link 5100                                                                  | 1         | 0.94%   |
| Intel Gemini Lake PCH CNVi WiFi                                                       | 1         | 0.94%   |
| Intel Ethernet Connection I219-LM                                                     | 1         | 0.94%   |
| Intel Ethernet Connection I218-V                                                      | 1         | 0.94%   |
| Intel Ethernet Connection I217-V                                                      | 1         | 0.94%   |
| Intel Ethernet Connection (4) I219-V                                                  | 1         | 0.94%   |
| Intel Ethernet Connection (2) I219-LM                                                 | 1         | 0.94%   |
| Intel Ethernet Connection (10) I219-V                                                 | 1         | 0.94%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 1         | 0.94%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 1         | 0.94%   |
| Intel Centrino Wireless-N 2230                                                        | 1         | 0.94%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 1         | 0.94%   |
| Intel 82567LM Gigabit Network Connection                                              | 1         | 0.94%   |
| HP hs2350 HSPA+ MobileBroadband                                                       | 1         | 0.94%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                                                  | 1         | 0.94%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                                     | 1         | 0.94%   |
| Broadcom Limited NetXtreme BCM5756ME Gigabit Ethernet PCI Express                     | 1         | 0.94%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                                               | 1         | 0.94%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 1         | 0.94%   |
| ASIX AX88772B                                                                         | 1         | 0.94%   |
| ASIX AX88179 Gigabit Ethernet                                                         | 1         | 0.94%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 38        | 67.86%  |
| Realtek Semiconductor | 6         | 10.71%  |
| Qualcomm Atheros      | 6         | 10.71%  |
| Ralink Technology     | 2         | 3.57%   |
| Sierra Wireless       | 1         | 1.79%   |
| Dell                  | 1         | 1.79%   |
| Broadcom Limited      | 1         | 1.79%   |
| Broadcom              | 1         | 1.79%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                                            | 4         | 7.14%   |
| Intel Wireless 7265                                                                   | 3         | 5.36%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 3         | 5.36%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 3         | 5.36%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 2         | 3.57%   |
| Ralink MT7601U Wireless Adapter                                                       | 2         | 3.57%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 2         | 3.57%   |
| Intel Wireless-AC 9260                                                                | 2         | 3.57%   |
| Intel Wireless 8260                                                                   | 2         | 3.57%   |
| Intel Wireless 7260                                                                   | 2         | 3.57%   |
| Intel Wireless 3160                                                                   | 2         | 3.57%   |
| Intel Wi-Fi 6 AX201                                                                   | 2         | 3.57%   |
| Intel Wi-Fi 6 AX200                                                                   | 2         | 3.57%   |
| Intel Tiger Lake PCH CNVi WiFi                                                        | 2         | 3.57%   |
| Intel Centrino Ultimate-N 6300                                                        | 2         | 3.57%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 2         | 3.57%   |
| Sierra Wireless EM7305                                                                | 1         | 1.79%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 1         | 1.79%   |
| Realtek RTL8723DE Wireless Network Adapter                                            | 1         | 1.79%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                       | 1         | 1.79%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 1.79%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 1         | 1.79%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                      | 1         | 1.79%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 1         | 1.79%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 1.79%   |
| Intel Wireless 3165                                                                   | 1         | 1.79%   |
| Intel WiFi Link 5100                                                                  | 1         | 1.79%   |
| Intel Gemini Lake PCH CNVi WiFi                                                       | 1         | 1.79%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 1         | 1.79%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 1         | 1.79%   |
| Intel Centrino Wireless-N 2230                                                        | 1         | 1.79%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 1         | 1.79%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                                                  | 1         | 1.79%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                                               | 1         | 1.79%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 1         | 1.79%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 25        | 52.08%  |
| Intel                 | 15        | 31.25%  |
| Qualcomm Atheros      | 4         | 8.33%   |
| ASIX Electronics      | 2         | 4.17%   |
| Broadcom Limited      | 1         | 2.08%   |
| Broadcom              | 1         | 2.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 17        | 34.69%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 10.2%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 8.16%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 4.08%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 4.08%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 4.08%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 4.08%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 2.04%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 2.04%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 2.04%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 2.04%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 2.04%   |
| Intel Ethernet Connection I218-V                                  | 1         | 2.04%   |
| Intel Ethernet Connection I217-V                                  | 1         | 2.04%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 2.04%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 2.04%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 2.04%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 2.04%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 2.04%   |
| Broadcom Limited NetXtreme BCM5756ME Gigabit Ethernet PCI Express | 1         | 2.04%   |
| ASIX AX88772B                                                     | 1         | 2.04%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 2.04%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 53        | 53%     |
| Ethernet | 46        | 46%     |
| Modem    | 1         | 1%      |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 40        | 72.73%  |
| Ethernet | 15        | 27.27%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 44        | 83.02%  |
| 1     | 8         | 15.09%  |
| 0     | 1         | 1.89%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 50        | 94.34%  |
| Yes  | 3         | 5.66%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 33        | 68.75%  |
| Realtek Semiconductor           | 5         | 10.42%  |
| Broadcom                        | 4         | 8.33%   |
| Qualcomm Atheros Communications | 3         | 6.25%   |
| Toshiba                         | 1         | 2.08%   |
| Foxconn / Hon Hai               | 1         | 2.08%   |
| Cambridge Silicon Radio         | 1         | 2.08%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 15        | 31.25%  |
| Intel AX201 Bluetooth                               | 6         | 12.5%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 8.33%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 6.25%   |
| Intel AX210 Bluetooth                               | 3         | 6.25%   |
| Realtek Bluetooth Radio                             | 2         | 4.17%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 4.17%   |
| Intel Bluetooth Device                              | 2         | 4.17%   |
| Intel AX200 Bluetooth                               | 2         | 4.17%   |
| Toshiba Askey Bluetooth Module                      | 1         | 2.08%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 2.08%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 2.08%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 2.08%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 2.08%   |
| Broadcom HP Portable SoftSailing                    | 1         | 2.08%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 2.08%   |
| Broadcom BCM20702A0                                 | 1         | 2.08%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 2.08%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 48        | 70.59%  |
| Nvidia              | 10        | 14.71%  |
| AMD                 | 8         | 11.76%  |
| Texas Instruments   | 1         | 1.47%   |
| C-Media Electronics | 1         | 1.47%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 9         | 11.25%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6         | 7.5%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 6.25%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 5         | 6.25%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 5%      |
| Intel Tiger Lake-H HD Audio Controller                                                            | 4         | 5%      |
| Intel Broadwell-U Audio Controller                                                                | 4         | 5%      |
| Nvidia GA104 High Definition Audio Controller                                                     | 3         | 3.75%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 3.75%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 3.75%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 2.5%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 2.5%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 2.5%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 2.5%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 2.5%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 2.5%    |
| Intel 8 Series HD Audio Controller                                                                | 2         | 2.5%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 2.5%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 2.5%    |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 2.5%    |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 1.25%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 1.25%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 1.25%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1         | 1.25%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 1.25%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 1.25%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 1.25%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 1.25%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 1.25%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 1.25%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 1.25%   |
| C-Media Electronics CM6631A Audio Processor                                                       | 1         | 1.25%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 1.25%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 1         | 1.25%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 17        | 30.91%  |
| Samsung Electronics | 11        | 20%     |
| Kingston            | 7         | 12.73%  |
| Micron Technology   | 5         | 9.09%   |
| Crucial             | 4         | 7.27%   |
| Ramaxel Technology  | 2         | 3.64%   |
| Corsair             | 2         | 3.64%   |
| Unknown             | 1         | 1.82%   |
| Smart               | 1         | 1.82%   |
| Neo Forza           | 1         | 1.82%   |
| Nanya Technology    | 1         | 1.82%   |
| Essencore Limited   | 1         | 1.82%   |
| Elpida              | 1         | 1.82%   |
| A-DATA Technology   | 1         | 1.82%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s               | 2         | 3.45%   |
| Unknown RAM Module 1024MB SODIMM SDRAM                               | 1         | 1.72%   |
| Smart RAM SH5641G8FJ8NWRNSQG 8GB SODIMM DDR3 1600MT/s                | 1         | 1.72%   |
| SK hynix RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s              | 1         | 1.72%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                      | 1         | 1.72%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 800MT/s                 | 1         | 1.72%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s               | 1         | 1.72%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8192MB SODIMM DDR3 1600MT/s            | 1         | 1.72%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s               | 1         | 1.72%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s               | 1         | 1.72%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s               | 1         | 1.72%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s               | 1         | 1.72%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s               | 1         | 1.72%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s               | 1         | 1.72%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s               | 1         | 1.72%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2400MT/s            | 1         | 1.72%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s               | 1         | 1.72%   |
| SK hynix RAM H9CCNNNCLGALAR-NUD 8192MB Row Of Chips LPDDR3 1867MT/s  | 1         | 1.72%   |
| SK hynix RAM 746448-381 4096MB SODIMM LPDDR3 1600MT/s                | 1         | 1.72%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s                | 1         | 1.72%   |
| Samsung RAM M471B5273DH0-YK0 4GB SODIMM DDR3 1600MT/s                | 1         | 1.72%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                | 1         | 1.72%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s                | 1         | 1.72%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                | 1         | 1.72%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s                | 1         | 1.72%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s                | 1         | 1.72%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s                | 1         | 1.72%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s                | 1         | 1.72%   |
| Samsung RAM M471A5244BB0-CPB 4GB SODIMM DDR4 2400MT/s                | 1         | 1.72%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s               | 1         | 1.72%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s              | 1         | 1.72%   |
| Ramaxel RAM RMT3150ED58E8W1600 2GB SODIMM DDR3 1600MT/s              | 1         | 1.72%   |
| Ramaxel RAM RMSA3260MH78HAF-2666 8192MB SODIMM DDR4 2667MT/s         | 1         | 1.72%   |
| Neo Forza RAM NMSO480E82-3200E 8GB SODIMM DDR4 3200MT/s              | 1         | 1.72%   |
| Nanya RAM NT4GC64C88B1NS-DI 4096MB SODIMM DDR3 1600MT/s              | 1         | 1.72%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s                 | 1         | 1.72%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                 | 1         | 1.72%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s                | 1         | 1.72%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s                | 1         | 1.72%   |
| Micron RAM 16KTF51264HZ-1G4 4096MB SODIMM DDR3 701MT/s               | 1         | 1.72%   |
| Kingston RAM KNWMX1-ETB 4GB SODIMM DDR3 1600MT/s                     | 1         | 1.72%   |
| Kingston RAM KKRVFX-MIE 8192MB SODIMM DDR4 3200MT/s                  | 1         | 1.72%   |
| Kingston RAM KHX2666C15S4/8G 8GB SODIMM DDR4 2667MT/s                | 1         | 1.72%   |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s              | 1         | 1.72%   |
| Kingston RAM CL15-15-15 D4-2133 4096MB SODIMM DDR4 2133MT/s          | 1         | 1.72%   |
| Kingston RAM 9905712-007.A00G 16384MB SODIMM DDR4 2400MT/s           | 1         | 1.72%   |
| Kingston RAM 9905711-032.A00G 8192MB SODIMM DDR4 2667MT/s            | 1         | 1.72%   |
| Kingston RAM 9905703-011.A00G 16GB SODIMM DDR4 2400MT/s              | 1         | 1.72%   |
| Essencore Limited RAM KD4AGSA8M-26N1900 16384MB SODIMM DDR4 2667MT/s | 1         | 1.72%   |
| Elpida RAM EBJ81UG8BBU0-GN-F 8GB SODIMM DDR3 1600MT/s                | 1         | 1.72%   |
| Crucial RAM CT4G4SFS824A.C8FE 4GB SODIMM DDR4 2400MT/s               | 1         | 1.72%   |
| Crucial RAM CT32G4SFD832A.C16FE 32GB SODIMM DDR4 3200MT/s            | 1         | 1.72%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s              | 1         | 1.72%   |
| Crucial RAM BL8G32C16S4B.8FE 8GB SODIMM DDR4 2667MT/s                | 1         | 1.72%   |
| Corsair RAM CMSX32GX4M2A2666C18 16GB SODIMM DDR4 2667MT/s            | 1         | 1.72%   |
| Corsair RAM CMSO4GX3M1C1600C11 4096MB SODIMM DDR3 1600MT/s           | 1         | 1.72%   |
| A-DATA RAM AO1L16BC4R1-BX7S 4096MB SODIMM DDR3 1600MT/s              | 1         | 1.72%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 24        | 51.06%  |
| DDR3   | 15        | 31.91%  |
| LPDDR3 | 3         | 6.38%   |
| SDRAM  | 2         | 4.26%   |
| LPDDR4 | 2         | 4.26%   |
| DDR2   | 1         | 2.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 45        | 95.74%  |
| Row Of Chips | 2         | 4.26%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 23        | 43.4%   |
| 8192  | 20        | 37.74%  |
| 16384 | 5         | 9.43%   |
| 2048  | 3         | 5.66%   |
| 32768 | 1         | 1.89%   |
| 1024  | 1         | 1.89%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 15        | 29.41%  |
| 2667    | 13        | 25.49%  |
| 3200    | 8         | 15.69%  |
| 2400    | 5         | 9.8%    |
| 2133    | 3         | 5.88%   |
| 4199    | 1         | 1.96%   |
| 1867    | 1         | 1.96%   |
| 1334    | 1         | 1.96%   |
| 1333    | 1         | 1.96%   |
| 975     | 1         | 1.96%   |
| 701     | 1         | 1.96%   |
| Unknown | 1         | 1.96%   |

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
| Chicony Electronics                    | 15        | 29.41%  |
| Acer                                   | 8         | 15.69%  |
| Realtek Semiconductor                  | 4         | 7.84%   |
| Microdia                               | 4         | 7.84%   |
| IMC Networks                           | 4         | 7.84%   |
| Lite-On Technology                     | 3         | 5.88%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 5.88%   |
| Sunplus Innovation Technology          | 2         | 3.92%   |
| Quanta                                 | 2         | 3.92%   |
| Syntek                                 | 1         | 1.96%   |
| Silicon Motion                         | 1         | 1.96%   |
| Samsung Electronics                    | 1         | 1.96%   |
| Motorola PCS                           | 1         | 1.96%   |
| Luxvisions Innotech Limited            | 1         | 1.96%   |
| Logitech                               | 1         | 1.96%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 3         | 5.88%   |
| Acer HD Webcam                                                             | 3         | 5.88%   |
| Acer BisonCam,NB Pro                                                       | 3         | 5.88%   |
| Quanta HP Webcam                                                           | 2         | 3.92%   |
| Syntek USB2.0 Camera                                                       | 1         | 1.96%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                       | 1         | 1.96%   |
| Sunplus Integrated_Webcam_HD                                               | 1         | 1.96%   |
| Silicon Motion Web Camera                                                  | 1         | 1.96%   |
| Samsung Galaxy A5 (MTP)                                                    | 1         | 1.96%   |
| Realtek USB Camera                                                         | 1         | 1.96%   |
| Realtek Laptop Camera                                                      | 1         | 1.96%   |
| Realtek HP Webcam-101                                                      | 1         | 1.96%   |
| Realtek EasyCamera                                                         | 1         | 1.96%   |
| Motorola PCS XT1033 [Moto G], PTP mode                                     | 1         | 1.96%   |
| Microdia Laptop_Integrated_Webcam_2M                                       | 1         | 1.96%   |
| Microdia Integrated_Webcam_HD                                              | 1         | 1.96%   |
| Microdia Integrated Webcam                                                 | 1         | 1.96%   |
| Microdia Dell Integrated HD Webcam                                         | 1         | 1.96%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 1         | 1.96%   |
| Logitech C920 PRO HD Webcam                                                | 1         | 1.96%   |
| Lite-On TOSHIBA Web Camera - FHD                                           | 1         | 1.96%   |
| Lite-On Integrated Camera                                                  | 1         | 1.96%   |
| Lite-On HP TrueVision HD Camera                                            | 1         | 1.96%   |
| IMC Networks UVC VGA Webcam                                                | 1         | 1.96%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 1         | 1.96%   |
| IMC Networks Lenovo EasyCamera                                             | 1         | 1.96%   |
| IMC Networks Integrated Camera                                             | 1         | 1.96%   |
| Chicony Web Camera - FHD                                                   | 1         | 1.96%   |
| Chicony TOSHIBA Web Camera - HD                                            | 1         | 1.96%   |
| Chicony TOSHIBA Web Camera - FHD                                           | 1         | 1.96%   |
| Chicony Integrated Camera [ThinkPad]                                       | 1         | 1.96%   |
| Chicony Integrated Camera (1280x720@30)                                    | 1         | 1.96%   |
| Chicony HP TrueVision HD Camera                                            | 1         | 1.96%   |
| Chicony HP HD Webcam [Fixed]                                               | 1         | 1.96%   |
| Chicony HP HD Camera                                                       | 1         | 1.96%   |
| Chicony HD WebCam (Acer)                                                   | 1         | 1.96%   |
| Chicony HD WebCam                                                          | 1         | 1.96%   |
| Chicony FJ Camera                                                          | 1         | 1.96%   |
| Chicony 2.0M UVC Webcam / CNF7129                                          | 1         | 1.96%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD integrated webcam | 1         | 1.96%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera             | 1         | 1.96%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam                        | 1         | 1.96%   |
| Acer ThinkPad Integrated Camera                                            | 1         | 1.96%   |
| Acer Integrated Camera                                                     | 1         | 1.96%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 6         | 54.55%  |
| Synaptics             | 3         | 27.27%  |
| LighTuning Technology | 1         | 9.09%   |
| Elan Microelectronics | 1         | 9.09%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Unknown                                           | 2         | 18.18%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor | 1         | 9.09%   |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 9.09%   |
| Validity Sensors VFS300 Fingerprint Reader        | 1         | 9.09%   |
| Validity Sensors VFS Fingerprint sensor           | 1         | 9.09%   |
| Validity Sensors VFS 5011 fingerprint sensor      | 1         | 9.09%   |
| Validity Sensors Synaptics WBDI                   | 1         | 9.09%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 9.09%   |
| LighTuning EgisTec Touch Fingerprint Sensor       | 1         | 9.09%   |
| Elan ELAN:Fingerprint                             | 1         | 9.09%   |

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
| 0     | 31        | 56.36%  |
| 1     | 15        | 27.27%  |
| 2     | 6         | 10.91%  |
| 3     | 3         | 5.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 10        | 28.57%  |
| Chipcard                 | 6         | 17.14%  |
| Graphics card            | 5         | 14.29%  |
| Net/wireless             | 3         | 8.57%   |
| Card reader              | 3         | 8.57%   |
| Multimedia controller    | 2         | 5.71%   |
| Storage                  | 1         | 2.86%   |
| Net/ethernet             | 1         | 2.86%   |
| Firewire controller      | 1         | 2.86%   |
| Communication controller | 1         | 2.86%   |
| Camera                   | 1         | 2.86%   |
| Bluetooth                | 1         | 2.86%   |

