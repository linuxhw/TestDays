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

Total: 94

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| Valve     | Jupiter                     | [eee501d93c](https://linux-hardware.org/?probe=eee501d93c) | Aug 09, 2023 |
| Lenovo    | IdeaPad 5 15ALC05 82LN      | [eec04bec1d](https://linux-hardware.org/?probe=eec04bec1d) | Aug 08, 2023 |
| HP        | Laptop 14s-fq0xxx           | [0a7b2a3fcc](https://linux-hardware.org/?probe=0a7b2a3fcc) | Aug 03, 2023 |
| Acer      | Swift SF114-34              | [ec48f7a207](https://linux-hardware.org/?probe=ec48f7a207) | May 28, 2023 |
| Apple     | MacBookAir7,2               | [941aa94750](https://linux-hardware.org/?probe=941aa94750) | Apr 13, 2023 |
| Valve     | Jupiter                     | [e9844f7162](https://linux-hardware.org/?probe=e9844f7162) | Mar 13, 2023 |
| HP        | ENVY Laptop 17-cr0xxx       | [fde666c0ea](https://linux-hardware.org/?probe=fde666c0ea) | Feb 17, 2023 |
| HP        | ENVY Laptop 17-cr0xxx       | [5ce5272a93](https://linux-hardware.org/?probe=5ce5272a93) | Feb 17, 2023 |
| Lenovo    | ThinkPad X140e 20BMS03E0... | [fb4c4aebf9](https://linux-hardware.org/?probe=fb4c4aebf9) | Jan 31, 2023 |
| Lenovo    | ThinkPad T470p 20J60018M... | [9324b897c3](https://linux-hardware.org/?probe=9324b897c3) | Jan 19, 2023 |
| ASUSTek   | VivoBook_ASUSLaptop K650... | [1b50127412](https://linux-hardware.org/?probe=1b50127412) | Jan 14, 2023 |
| HP        | EliteBook 8440p             | [9edc837033](https://linux-hardware.org/?probe=9edc837033) | Jan 13, 2023 |
| HP        | OMEN by Laptop 17-ck0xxx    | [9655429e71](https://linux-hardware.org/?probe=9655429e71) | Jan 06, 2023 |
| ASUSTek   | VivoBook_ASUSLaptop K650... | [4900ec9966](https://linux-hardware.org/?probe=4900ec9966) | Jan 05, 2023 |
| Acer      | Nitro AN515-54              | [5205b7c248](https://linux-hardware.org/?probe=5205b7c248) | Dec 27, 2022 |
| ASUSTek   | VivoBook_ASUSLaptop K650... | [1cf2ac2b8b](https://linux-hardware.org/?probe=1cf2ac2b8b) | Dec 27, 2022 |
| Acer      | Extensa 5220                | [30ca0c3efa](https://linux-hardware.org/?probe=30ca0c3efa) | Dec 06, 2022 |
| HP        | OMEN by Laptop 16-b1xxx     | [799470f1aa](https://linux-hardware.org/?probe=799470f1aa) | Dec 05, 2022 |
| HP        | OMEN by Laptop 16-b1xxx     | [0cd3005f69](https://linux-hardware.org/?probe=0cd3005f69) | Dec 01, 2022 |
| HP        | OMEN by Laptop 16-b1xxx     | [32b68762df](https://linux-hardware.org/?probe=32b68762df) | Nov 30, 2022 |
| Lenovo    | ThinkPad T470 20JNS01R01    | [abb8194196](https://linux-hardware.org/?probe=abb8194196) | Oct 21, 2022 |
| Lenovo    | ThinkPad T61 765912G        | [e7f2dc737e](https://linux-hardware.org/?probe=e7f2dc737e) | Oct 09, 2022 |
| Lenovo    | ThinkPad T410 2518C3U       | [4d250adf3b](https://linux-hardware.org/?probe=4d250adf3b) | Oct 04, 2022 |
| Lenovo    | ThinkPad T61 765912G        | [bd04e564a0](https://linux-hardware.org/?probe=bd04e564a0) | Sep 24, 2022 |
| Fujitsu   | LIFEBOOK A544               | [e5785106f1](https://linux-hardware.org/?probe=e5785106f1) | Aug 09, 2022 |
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
| Slackware 15.0  | 41        | 57.75%  |
| Slackware 14.2  | 27        | 38.03%  |
| Slackware 14.2+ | 3         | 4.23%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| Slackware | 71        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.15.19           | 11        | 14.29%  |
| 4.19.80           | 4         | 5.19%   |
| 5.3.7             | 2         | 2.6%    |
| 5.19.17           | 2         | 2.6%    |
| 5.17.1            | 2         | 2.6%    |
| 5.15.80           | 2         | 2.6%    |
| 5.15.38           | 2         | 2.6%    |
| 5.15.117          | 2         | 2.6%    |
| 5.13.8            | 2         | 2.6%    |
| 4.4.276           | 2         | 2.6%    |
| 6.1.44            | 1         | 1.3%    |
| 6.1.12            | 1         | 1.3%    |
| 6.1.1             | 1         | 1.3%    |
| 5.7.0             | 1         | 1.3%    |
| 5.5.10            | 1         | 1.3%    |
| 5.4.75            | 1         | 1.3%    |
| 5.4.50            | 1         | 1.3%    |
| 5.4.47            | 1         | 1.3%    |
| 5.4.24toshiba-new | 1         | 1.3%    |
| 5.4.2             | 1         | 1.3%    |
| 5.4.139-jw        | 1         | 1.3%    |
| 5.4.13            | 1         | 1.3%    |
| 5.2.2             | 1         | 1.3%    |
| 5.17.5            | 1         | 1.3%    |
| 5.17.2            | 1         | 1.3%    |
| 5.16.9-joe1       | 1         | 1.3%    |
| 5.16.12           | 1         | 1.3%    |
| 5.15.78.a         | 1         | 1.3%    |
| 5.15.63           | 1         | 1.3%    |
| 5.15.37.a         | 1         | 1.3%    |
| 5.15.33.kjh       | 1         | 1.3%    |
| 5.15.27           | 1         | 1.3%    |
| 5.15.1            | 1         | 1.3%    |
| 5.14.9            | 1         | 1.3%    |
| 5.14.8            | 1         | 1.3%    |
| 5.14.10           | 1         | 1.3%    |
| 5.14.0            | 1         | 1.3%    |
| 5.13.5            | 1         | 1.3%    |
| 5.13.11           | 1         | 1.3%    |
| 5.13.0.a          | 1         | 1.3%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.15.19  | 11        | 14.29%  |
| 4.19.80  | 4         | 5.19%   |
| 5.3.7    | 2         | 2.6%    |
| 5.19.17  | 2         | 2.6%    |
| 5.17.1   | 2         | 2.6%    |
| 5.15.80  | 2         | 2.6%    |
| 5.15.38  | 2         | 2.6%    |
| 5.15.117 | 2         | 2.6%    |
| 5.13.8   | 2         | 2.6%    |
| 4.4.276  | 2         | 2.6%    |
| 4.4.190  | 2         | 2.6%    |
| 6.1.44   | 1         | 1.3%    |
| 6.1.12   | 1         | 1.3%    |
| 6.1.1    | 1         | 1.3%    |
| 5.7.0    | 1         | 1.3%    |
| 5.5.10   | 1         | 1.3%    |
| 5.4.75   | 1         | 1.3%    |
| 5.4.50   | 1         | 1.3%    |
| 5.4.47   | 1         | 1.3%    |
| 5.4.24   | 1         | 1.3%    |
| 5.4.2    | 1         | 1.3%    |
| 5.4.139  | 1         | 1.3%    |
| 5.4.13   | 1         | 1.3%    |
| 5.2.2    | 1         | 1.3%    |
| 5.17.5   | 1         | 1.3%    |
| 5.17.2   | 1         | 1.3%    |
| 5.16.9   | 1         | 1.3%    |
| 5.16.12  | 1         | 1.3%    |
| 5.15.78  | 1         | 1.3%    |
| 5.15.63  | 1         | 1.3%    |
| 5.15.37  | 1         | 1.3%    |
| 5.15.33  | 1         | 1.3%    |
| 5.15.27  | 1         | 1.3%    |
| 5.15.1   | 1         | 1.3%    |
| 5.14.9   | 1         | 1.3%    |
| 5.14.8   | 1         | 1.3%    |
| 5.14.10  | 1         | 1.3%    |
| 5.14.0   | 1         | 1.3%    |
| 5.13.5   | 1         | 1.3%    |
| 5.13.11  | 1         | 1.3%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 23        | 30.26%  |
| 4.4     | 8         | 10.53%  |
| 5.4     | 7         | 9.21%   |
| 4.19    | 7         | 9.21%   |
| 5.10    | 6         | 7.89%   |
| 5.13    | 5         | 6.58%   |
| 5.17    | 4         | 5.26%   |
| 6.1     | 3         | 3.95%   |
| 5.14    | 3         | 3.95%   |
| 5.3     | 2         | 2.63%   |
| 5.19    | 2         | 2.63%   |
| 5.16    | 2         | 2.63%   |
| 5.7     | 1         | 1.32%   |
| 5.5     | 1         | 1.32%   |
| 5.2     | 1         | 1.32%   |
| 4.16    | 1         | 1.32%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 70        | 98.59%  |
| i686   | 1         | 1.41%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| XFCE          | 23        | 31.51%  |
| KDE5          | 23        | 31.51%  |
| Unknown       | 17        | 23.29%  |
| KDE           | 3         | 4.11%   |
| xwmconfig     | 1         | 1.37%   |
| MATE          | 1         | 1.37%   |
| LXQt          | 1         | 1.37%   |
| GNOME         | 1         | 1.37%   |
| Enlightenment | 1         | 1.37%   |
| awesome       | 1         | 1.37%   |
| 2bwm          | 1         | 1.37%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 54        | 72.97%  |
| Tty     | 17        | 22.97%  |
| Wayland | 3         | 4.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 29        | 39.19%  |
| Unknown | 27        | 36.49%  |
| XDM     | 16        | 21.62%  |
| LightDM | 1         | 1.35%   |
| GDM     | 1         | 1.35%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 43        | 60.56%  |
| Unknown | 14        | 19.72%  |
| pt_BR   | 3         | 4.23%   |
| fr_FR   | 3         | 4.23%   |
| de_DE   | 3         | 4.23%   |
| ru_RU   | 2         | 2.82%   |
| it_IT   | 2         | 2.82%   |
| pl_PL   | 1         | 1.41%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 37        | 51.39%  |
| BIOS | 35        | 48.61%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 62        | 86.11%  |
| Btrfs   | 5         | 6.94%   |
| Overlay | 4         | 5.56%   |
| Xfs     | 1         | 1.39%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 46        | 63.89%  |
| MBR     | 17        | 23.61%  |
| Unknown | 9         | 12.5%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 61        | 83.56%  |
| Yes       | 12        | 16.44%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 45        | 63.38%  |
| Yes       | 26        | 36.62%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 18        | 25.35%  |
| Hewlett-Packard     | 16        | 22.54%  |
| Dell                | 7         | 9.86%   |
| ASUSTek Computer    | 6         | 8.45%   |
| MSI                 | 5         | 7.04%   |
| Acer                | 5         | 7.04%   |
| Toshiba             | 3         | 4.23%   |
| Notebook            | 2         | 2.82%   |
| Fujitsu             | 2         | 2.82%   |
| Dynabook            | 2         | 2.82%   |
| Valve               | 1         | 1.41%   |
| System76            | 1         | 1.41%   |
| Sony                | 1         | 1.41%   |
| Samsung Electronics | 1         | 1.41%   |
| Framework           | 1         | 1.41%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| ASUS VivoBook_ASUSLaptop K6500ZE_K6500ZE | 2         | 2.82%   |
| Valve Jupiter                            | 1         | 1.41%   |
| Toshiba Satellite P50-A-12Z              | 1         | 1.41%   |
| Toshiba Satellite C660                   | 1         | 1.41%   |
| Toshiba PORTEGE Z30-A                    | 1         | 1.41%   |
| System76 Oryx Pro                        | 1         | 1.41%   |
| Sony SVE1713A1EW                         | 1         | 1.41%   |
| Samsung 300E5M/300E5L                    | 1         | 1.41%   |
| Notebook X170KM-G                        | 1         | 1.41%   |
| Notebook NL40_50CU                       | 1         | 1.41%   |
| MSI Modern 14 B11MO                      | 1         | 1.41%   |
| MSI Modern 14 B10MW                      | 1         | 1.41%   |
| MSI GP76 Leopard 11UG                    | 1         | 1.41%   |
| MSI GL73 8RC                             | 1         | 1.41%   |
| MSI GE76 Raider 11UE                     | 1         | 1.41%   |
| Lenovo V330-14ARR 81B1                   | 1         | 1.41%   |
| Lenovo ThinkPad X230 2325P38             | 1         | 1.41%   |
| Lenovo ThinkPad X140e 20BMS03E00         | 1         | 1.41%   |
| Lenovo ThinkPad X1 Carbon 7th 20R10015US | 1         | 1.41%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS04300 | 1         | 1.41%   |
| Lenovo ThinkPad T61 765912G              | 1         | 1.41%   |
| Lenovo ThinkPad T470p 20J60018MS         | 1         | 1.41%   |
| Lenovo ThinkPad T470 20JNS01R01          | 1         | 1.41%   |
| Lenovo ThinkPad T470 20HDCTO1WW          | 1         | 1.41%   |
| Lenovo ThinkPad T450s 20BW000EUS         | 1         | 1.41%   |
| Lenovo ThinkPad T410 2518C3U             | 1         | 1.41%   |
| Lenovo ThinkPad T400 6474BV7             | 1         | 1.41%   |
| Lenovo ThinkPad P70 20ERCTO1WW           | 1         | 1.41%   |
| Lenovo ThinkPad L440 20ASS05K00          | 1         | 1.41%   |
| Lenovo ThinkPad Edge E530c 336669G       | 1         | 1.41%   |
| Lenovo IdeaPad P500 20210                | 1         | 1.41%   |
| Lenovo IdeaPad 5 15ALC05 82LN            | 1         | 1.41%   |
| Lenovo IdeaPad 310-15ISK 80SM            | 1         | 1.41%   |
| HP ProBook 6570b                         | 1         | 1.41%   |
| HP Pavilion Notebook                     | 1         | 1.41%   |
| HP Pavilion Gaming Laptop 16-a0xxx       | 1         | 1.41%   |
| HP Pavilion Gaming Laptop 15-ec1xxx      | 1         | 1.41%   |
| HP OMEN by Laptop 17-ck0xxx              | 1         | 1.41%   |
| HP OMEN by Laptop 16-b1xxx               | 1         | 1.41%   |
| HP Laptop 15-da0xxx                      | 1         | 1.41%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 14        | 19.72%  |
| HP Laptop           | 4         | 5.63%   |
| Lenovo IdeaPad      | 3         | 4.23%   |
| HP Pavilion         | 3         | 4.23%   |
| HP EliteBook        | 3         | 4.23%   |
| Dell Latitude       | 3         | 4.23%   |
| ASUS VivoBook       | 3         | 4.23%   |
| Toshiba Satellite   | 2         | 2.82%   |
| MSI Modern          | 2         | 2.82%   |
| HP OMEN             | 2         | 2.82%   |
| Fujitsu LIFEBOOK    | 2         | 2.82%   |
| Dell Precision      | 2         | 2.82%   |
| Acer Swift          | 2         | 2.82%   |
| Valve Jupiter       | 1         | 1.41%   |
| Toshiba PORTEGE     | 1         | 1.41%   |
| System76 Oryx       | 1         | 1.41%   |
| Sony SVE1713A1EW    | 1         | 1.41%   |
| Samsung 300E5M      | 1         | 1.41%   |
| Notebook X170KM-G   | 1         | 1.41%   |
| Notebook NL40       | 1         | 1.41%   |
| MSI GP76            | 1         | 1.41%   |
| MSI GL73            | 1         | 1.41%   |
| MSI GE76            | 1         | 1.41%   |
| Lenovo V330-14ARR   | 1         | 1.41%   |
| HP ProBook          | 1         | 1.41%   |
| HP ENVY             | 1         | 1.41%   |
| HP 245              | 1         | 1.41%   |
| HP 15               | 1         | 1.41%   |
| Framework Laptop    | 1         | 1.41%   |
| Dynabook PORTEGE    | 1         | 1.41%   |
| Dynabook P1-C7MP-BL | 1         | 1.41%   |
| Dell Vostro         | 1         | 1.41%   |
| Dell Inspiron       | 1         | 1.41%   |
| ASUS ROG            | 1         | 1.41%   |
| ASUS P53E           | 1         | 1.41%   |
| ASUS 1000H          | 1         | 1.41%   |
| Acer Nitro          | 1         | 1.41%   |
| Acer Extensa        | 1         | 1.41%   |
| Acer Aspire         | 1         | 1.41%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 10        | 14.08%  |
| 2021 | 8         | 11.27%  |
| 2017 | 7         | 9.86%   |
| 2019 | 6         | 8.45%   |
| 2012 | 6         | 8.45%   |
| 2022 | 5         | 7.04%   |
| 2015 | 5         | 7.04%   |
| 2018 | 4         | 5.63%   |
| 2014 | 4         | 5.63%   |
| 2016 | 3         | 4.23%   |
| 2010 | 3         | 4.23%   |
| 2008 | 3         | 4.23%   |
| 2013 | 2         | 2.82%   |
| 2011 | 2         | 2.82%   |
| 2007 | 2         | 2.82%   |
| 2009 | 1         | 1.41%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 71        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 71        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 68        | 95.77%  |
| Yes  | 3         | 4.23%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 18        | 25.35%  |
| 8.01-16.0   | 16        | 22.54%  |
| 3.01-4.0    | 14        | 19.72%  |
| 16.01-24.0  | 13        | 18.31%  |
| 32.01-64.0  | 4         | 5.63%   |
| 24.01-32.0  | 2         | 2.82%   |
| 1.01-2.0    | 2         | 2.82%   |
| 64.01-256.0 | 1         | 1.41%   |
| 0.51-1.0    | 1         | 1.41%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 23        | 30.26%  |
| 1.01-2.0   | 22        | 28.95%  |
| 4.01-8.0   | 12        | 15.79%  |
| 3.01-4.0   | 7         | 9.21%   |
| 0.51-1.0   | 7         | 9.21%   |
| 0.01-0.5   | 3         | 3.95%   |
| 16.01-24.0 | 1         | 1.32%   |
| 8.01-16.0  | 1         | 1.32%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 52        | 71.23%  |
| 2      | 17        | 23.29%  |
| 3      | 2         | 2.74%   |
| 4      | 1         | 1.37%   |
| 0      | 1         | 1.37%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 53        | 74.65%  |
| Yes       | 18        | 25.35%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 61        | 85.92%  |
| No        | 10        | 14.08%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 71        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 62        | 87.32%  |
| No        | 9         | 12.68%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 16        | 22.54%  |
| Portugal     | 5         | 7.04%   |
| Brazil       | 5         | 7.04%   |
| Italy        | 4         | 5.63%   |
| India        | 4         | 5.63%   |
| Germany      | 4         | 5.63%   |
| UK           | 3         | 4.23%   |
| Russia       | 3         | 4.23%   |
| Kazakhstan   | 3         | 4.23%   |
| Japan        | 3         | 4.23%   |
| France       | 3         | 4.23%   |
| Canada       | 3         | 4.23%   |
| Sweden       | 2         | 2.82%   |
| South Africa | 2         | 2.82%   |
| Poland       | 2         | 2.82%   |
| Chile        | 2         | 2.82%   |
| Spain        | 1         | 1.41%   |
| Serbia       | 1         | 1.41%   |
| Romania      | 1         | 1.41%   |
| Philippines  | 1         | 1.41%   |
| Mexico       | 1         | 1.41%   |
| Greece       | 1         | 1.41%   |
| Finland      | 1         | 1.41%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lisbon                 | 4         | 5.41%   |
| Warsaw                 | 2         | 2.7%    |
| Ust-Kamenogorsk        | 2         | 2.7%    |
| Sun Prairie            | 2         | 2.7%    |
| Greater Noida          | 2         | 2.7%    |
| Frignano               | 2         | 2.7%    |
| Worpswede              | 1         | 1.35%   |
| Wokingham              | 1         | 1.35%   |
| Winnipeg               | 1         | 1.35%   |
| Voskresensk            | 1         | 1.35%   |
| Visconde do Rio Branco | 1         | 1.35%   |
| Tsukuba                | 1         | 1.35%   |
| Tendo                  | 1         | 1.35%   |
| Skövde                | 1         | 1.35%   |
| Sao Paulo              | 1         | 1.35%   |
| Santiago               | 1         | 1.35%   |
| San Antonio            | 1         | 1.35%   |
| Round Rock             | 1         | 1.35%   |
| Roknaes                | 1         | 1.35%   |
| Reno                   | 1         | 1.35%   |
| Renazzo                | 1         | 1.35%   |
| Redding                | 1         | 1.35%   |
| Puente Alto            | 1         | 1.35%   |
| Plainwell              | 1         | 1.35%   |
| Pinhal Novo            | 1         | 1.35%   |
| Pesaro                 | 1         | 1.35%   |
| Pasay                  | 1         | 1.35%   |
| Paris                  | 1         | 1.35%   |
| Ōtsu                  | 1         | 1.35%   |
| Oberstreit             | 1         | 1.35%   |
| Northport              | 1         | 1.35%   |
| Moscow                 | 1         | 1.35%   |
| Montreal               | 1         | 1.35%   |
| Milan                  | 1         | 1.35%   |
| Mexico City            | 1         | 1.35%   |
| Meuselwitz             | 1         | 1.35%   |
| McKinney               | 1         | 1.35%   |
| Luxeuil-les-Bains      | 1         | 1.35%   |
| Lins                   | 1         | 1.35%   |
| League City            | 1         | 1.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 18        | 24     | 20.69%  |
| WDC                 | 14        | 17     | 16.09%  |
| Kingston            | 7         | 7      | 8.05%   |
| Toshiba             | 6         | 6      | 6.9%    |
| Seagate             | 5         | 5      | 5.75%   |
| Intel               | 5         | 5      | 5.75%   |
| Crucial             | 5         | 6      | 5.75%   |
| SanDisk             | 4         | 5      | 4.6%    |
| HGST                | 4         | 4      | 4.6%    |
| Unknown             | 3         | 4      | 3.45%   |
| SK hynix            | 3         | 3      | 3.45%   |
| Micron Technology   | 3         | 3      | 3.45%   |
| Gigabyte Technology | 2         | 2      | 2.3%    |
| Transcend           | 1         | 1      | 1.15%   |
| Silicon Motion      | 1         | 1      | 1.15%   |
| Plextor             | 1         | 1      | 1.15%   |
| Patriot             | 1         | 2      | 1.15%   |
| Netac               | 1         | 1      | 1.15%   |
| KIOXIA              | 1         | 1      | 1.15%   |
| Hewlett-Packard     | 1         | 2      | 1.15%   |
| Dogfish             | 1         | 1      | 1.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                       | 4         | 4.35%   |
| WDC WD10SPZX-60Z10T0 1TB                              | 2         | 2.17%   |
| Toshiba MQ04ABF100 1TB                                | 2         | 2.17%   |
| Intel SSD 660P Series 1024GB                          | 2         | 2.17%   |
| HGST HTS725050A7E630 500GB                            | 2         | 2.17%   |
| WDC WDS500G2B0B-00YS70 500GB SSD                      | 1         | 1.09%   |
| WDC WDS100T2B0B-00YS70 1TB SSD                        | 1         | 1.09%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                        | 1         | 1.09%   |
| WDC WD7500BPVT-24HXZT3 752GB                          | 1         | 1.09%   |
| WDC WD5000LPCX-60VHAT1 500GB                          | 1         | 1.09%   |
| WDC WD10JPVX-35JC3T0 1TB                              | 1         | 1.09%   |
| WDC WD10JPVX-16JC3T3 1TB                              | 1         | 1.09%   |
| WDC WD10JPVT-08A1YT2 1TB                              | 1         | 1.09%   |
| WDC WD10JPLX-00MBPT0 1TB                              | 1         | 1.09%   |
| WDC WD Green 2.5 240GB SSD                            | 1         | 1.09%   |
| WDC PC SN530 SDBPNPZ-1T00-1002 1TB                    | 1         | 1.09%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB                  | 1         | 1.09%   |
| WDC PC SN520 SDAPNUW-256G-1102 256GB                  | 1         | 1.09%   |
| Unknown SD32G  32GB                                   | 1         | 1.09%   |
| Unknown SC32G  32GB                                   | 1         | 1.09%   |
| Unknown MMC Card  512GB                               | 1         | 1.09%   |
| Transcend TS256GMTE352T-VLV 256GB                     | 1         | 1.09%   |
| Toshiba MQ01ACF032 320GB                              | 1         | 1.09%   |
| Toshiba MQ01ABF050 500GB                              | 1         | 1.09%   |
| Toshiba MK2565GSXN 250GB                              | 1         | 1.09%   |
| Toshiba MK1646GSX 160GB                               | 1         | 1.09%   |
| SK hynix HFM001TD3JX013N 1TB                          | 1         | 1.09%   |
| SK hynix BC511 HFM512GDJTNI-82A0A 512GB               | 1         | 1.09%   |
| SK hynix BC511 512GB                                  | 1         | 1.09%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 500GB | 1         | 1.09%   |
| Seagate ST9160827AS 160GB                             | 1         | 1.09%   |
| Seagate ST9160412AS 160GB                             | 1         | 1.09%   |
| Seagate ST500VT000-1DK142 500GB                       | 1         | 1.09%   |
| Seagate ST1000LM048-2E7172 1TB                        | 1         | 1.09%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 1         | 1.09%   |
| SanDisk Ultra II 960GB SSD                            | 1         | 1.09%   |
| SanDisk SDSSDA240G 240GB                              | 1         | 1.09%   |
| SanDisk SD8TN8U256G1001 256GB SSD                     | 1         | 1.09%   |
| SanDisk NVMe SSD Drive 1TB                            | 1         | 1.09%   |
| Samsung SSD PM830 2.5 7mm 128GB                       | 1         | 1.09%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 8         | 10     | 34.78%  |
| Toshiba | 6         | 6      | 26.09%  |
| Seagate | 5         | 5      | 21.74%  |
| HGST    | 4         | 4      | 17.39%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 9      | 24.14%  |
| Kingston            | 6         | 6      | 20.69%  |
| Crucial             | 4         | 5      | 13.79%  |
| WDC                 | 3         | 4      | 10.34%  |
| SanDisk             | 3         | 3      | 10.34%  |
| Plextor             | 1         | 1      | 3.45%   |
| Patriot             | 1         | 2      | 3.45%   |
| Netac               | 1         | 1      | 3.45%   |
| Micron Technology   | 1         | 1      | 3.45%   |
| Gigabyte Technology | 1         | 1      | 3.45%   |
| Dogfish             | 1         | 1      | 3.45%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 31        | 38     | 36.47%  |
| SSD  | 28        | 34     | 32.94%  |
| HDD  | 23        | 25     | 27.06%  |
| MMC  | 3         | 4      | 3.53%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 43        | 57     | 54.43%  |
| NVMe | 31        | 38     | 39.24%  |
| MMC  | 3         | 4      | 3.8%    |
| SAS  | 2         | 2      | 2.53%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 32        | 38     | 64%     |
| 0.51-1.0   | 17        | 20     | 34%     |
| 1.01-2.0   | 1         | 1      | 2%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 22        | 30.56%  |
| 501-1000       | 20        | 27.78%  |
| 251-500        | 16        | 22.22%  |
| 1001-2000      | 6         | 8.33%   |
| 1-20           | 3         | 4.17%   |
| 21-50          | 2         | 2.78%   |
| More than 3000 | 1         | 1.39%   |
| 51-100         | 1         | 1.39%   |
| Unknown        | 1         | 1.39%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 101-250   | 16        | 21.05%  |
| 1-20      | 15        | 19.74%  |
| 21-50     | 14        | 18.42%  |
| 51-100    | 11        | 14.47%  |
| 251-500   | 10        | 13.16%  |
| 501-1000  | 7         | 9.21%   |
| 1001-2000 | 2         | 2.63%   |
| Unknown   | 1         | 1.32%   |

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
| Works    | 56        | 72     | 71.79%  |
| Detected | 15        | 22     | 19.23%  |
| Malfunc  | 7         | 7      | 8.97%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 50        | 60.24%  |
| Samsung Electronics         | 11        | 13.25%  |
| AMD                         | 7         | 8.43%   |
| SanDisk                     | 4         | 4.82%   |
| SK hynix                    | 3         | 3.61%   |
| Micron Technology           | 2         | 2.41%   |
| Silicon Motion              | 1         | 1.2%    |
| Phison Electronics          | 1         | 1.2%    |
| Micron/Crucial Technology   | 1         | 1.2%    |
| KIOXIA                      | 1         | 1.2%    |
| Kingston Technology Company | 1         | 1.2%    |
| Biwin Storage Technology    | 1         | 1.2%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 6         | 6.74%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 6         | 6.74%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 5         | 5.62%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 4         | 4.49%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 4         | 4.49%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 4         | 4.49%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 3.37%   |
| Samsung NVMe SSD Controller 980                                                  | 3         | 3.37%   |
| Intel Volume Management Device NVMe RAID Controller                              | 3         | 3.37%   |
| Intel SSD 660P Series                                                            | 3         | 3.37%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3         | 3.37%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 3.37%   |
| SK hynix BC511 NVMe SSD                                                          | 2         | 2.25%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 2.25%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 2.25%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 2.25%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 2.25%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 2.25%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 2         | 2.25%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 2         | 2.25%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 1         | 1.12%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 1         | 1.12%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                       | 1         | 1.12%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 1.12%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 1.12%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                            | 1         | 1.12%   |
| Phison E8 PCIe3 NVMe Controller                                                  | 1         | 1.12%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 1         | 1.12%   |
| Micron 3400 NVMe SSD [Hendrix]                                                   | 1         | 1.12%   |
| Micron 2210 NVMe SSD [Cobain]                                                    | 1         | 1.12%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 1         | 1.12%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 1.12%   |
| Intel Tiger Lake-LP SATA Controller                                              | 1         | 1.12%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                                 | 1         | 1.12%   |
| Intel SSD 600P Series                                                            | 1         | 1.12%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 1.12%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 1.12%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 1.12%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 1.12%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 1.12%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 44        | 50%     |
| NVMe | 31        | 35.23%  |
| RAID | 9         | 10.23%  |
| IDE  | 4         | 4.55%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 62        | 87.32%  |
| AMD    | 9         | 12.68%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 4         | 5.63%   |
| Intel 12th Gen Core i7-12700H                 | 3         | 4.23%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 2.82%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 2.82%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 2.82%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 2.82%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 2.82%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 2         | 2.82%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 1         | 1.41%   |
| Intel Pentium CPU P6100 @ 2.00GHz             | 1         | 1.41%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 1.41%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 1         | 1.41%   |
| Intel CPU Version                             | 1         | 1.41%   |
| Intel Core M-5Y51 CPU @ 1.10GHz               | 1         | 1.41%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 1.41%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 1.41%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 1.41%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 1.41%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 1.41%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 1.41%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 1.41%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 1.41%   |
| Intel Core i7-3840QM CPU @ 2.80GHz            | 1         | 1.41%   |
| Intel Core i7-2860QM CPU @ 2.50GHz            | 1         | 1.41%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 1         | 1.41%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 1         | 1.41%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 1.41%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 1.41%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 1         | 1.41%   |
| Intel Core i5-4310M CPU @ 2.70GHz             | 1         | 1.41%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 1.41%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 1.41%   |
| Intel Core i5-3360M CPU @ 2.80GHz             | 1         | 1.41%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 1.41%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 1.41%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 1.41%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 1         | 1.41%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 1         | 1.41%   |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 1         | 1.41%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 1         | 1.41%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 18        | 25.35%  |
| Other                | 14        | 19.72%  |
| Intel Core i7        | 14        | 19.72%  |
| Intel Core i3        | 6         | 8.45%   |
| AMD Ryzen 5          | 4         | 5.63%   |
| Intel Pentium        | 3         | 4.23%   |
| Intel Core 2 Duo     | 2         | 2.82%   |
| Intel Celeron        | 2         | 2.82%   |
| AMD Ryzen 7          | 2         | 2.82%   |
| Intel Pentium Silver | 1         | 1.41%   |
| Intel Core M         | 1         | 1.41%   |
| Intel Core 2         | 1         | 1.41%   |
| Intel Atom           | 1         | 1.41%   |
| AMD Ryzen 9          | 1         | 1.41%   |
| AMD E1               | 1         | 1.41%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 32        | 45.07%  |
| 4      | 21        | 29.58%  |
| 8      | 9         | 12.68%  |
| 14     | 3         | 4.23%   |
| 6      | 3         | 4.23%   |
| 1      | 2         | 2.82%   |
| 10     | 1         | 1.41%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 71        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 59        | 83.1%   |
| 1      | 12        | 16.9%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 68        | 95.77%  |
| Unknown        | 2         | 2.82%   |
| 32-bit         | 1         | 1.41%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 15        | 21.13%  |
| 0x306a9    | 6         | 8.45%   |
| 0x806d1    | 4         | 5.63%   |
| 0x306d4    | 4         | 5.63%   |
| 0x906a3    | 3         | 4.23%   |
| 0x806ec    | 3         | 4.23%   |
| 0x806ea    | 3         | 4.23%   |
| 0x806c1    | 3         | 4.23%   |
| 0x406e3    | 3         | 4.23%   |
| 0x306c3    | 2         | 2.82%   |
| 0x206a7    | 2         | 2.82%   |
| 0x20655    | 2         | 2.82%   |
| 0x08600106 | 2         | 2.82%   |
| 0xa0671    | 1         | 1.41%   |
| 0xa0660    | 1         | 1.41%   |
| 0xa0652    | 1         | 1.41%   |
| 0x906c0    | 1         | 1.41%   |
| 0x906a4    | 1         | 1.41%   |
| 0x806e9    | 1         | 1.41%   |
| 0x706a1    | 1         | 1.41%   |
| 0x6fd      | 1         | 1.41%   |
| 0x506e3    | 1         | 1.41%   |
| 0x406c4    | 1         | 1.41%   |
| 0x40651    | 1         | 1.41%   |
| 0x106c2    | 1         | 1.41%   |
| 0x1067a    | 1         | 1.41%   |
| 0x10661    | 1         | 1.41%   |
| 0x08900201 | 1         | 1.41%   |
| 0x08608102 | 1         | 1.41%   |
| 0x08108109 | 1         | 1.41%   |
| 0x0810100b | 1         | 1.41%   |
| 0x07000106 | 1         | 1.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 12        | 16.9%   |
| Skylake          | 6         | 8.45%   |
| IvyBridge        | 6         | 8.45%   |
| Icelake          | 5         | 7.04%   |
| Haswell          | 5         | 7.04%   |
| Westmere         | 4         | 5.63%   |
| Broadwell        | 4         | 5.63%   |
| Alderlake Hybrid | 4         | 5.63%   |
| Zen 2            | 3         | 4.23%   |
| TigerLake        | 3         | 4.23%   |
| Core             | 3         | 4.23%   |
| Zen              | 2         | 2.82%   |
| Silvermont       | 2         | 2.82%   |
| SandyBridge      | 2         | 2.82%   |
| CometLake        | 2         | 2.82%   |
| Unknown          | 2         | 2.82%   |
| Zen+             | 1         | 1.41%   |
| Tremont          | 1         | 1.41%   |
| Penryn           | 1         | 1.41%   |
| Jaguar           | 1         | 1.41%   |
| Goldmont plus    | 1         | 1.41%   |
| Bonnell          | 1         | 1.41%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 55        | 62.5%   |
| Nvidia | 21        | 23.86%  |
| AMD    | 12        | 13.64%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 5.49%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 4         | 4.4%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 4.4%    |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 3         | 3.3%    |
| Intel UHD Graphics 620                                                                   | 3         | 3.3%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 3.3%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 3.3%    |
| Intel HD Graphics 5500                                                                   | 3         | 3.3%    |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 3.3%    |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 3         | 3.3%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 3.3%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 3.3%    |
| AMD Renoir                                                                               | 3         | 3.3%    |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 2.2%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 2.2%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 2.2%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 2.2%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 2.2%    |
| Intel HD Graphics 620                                                                    | 2         | 2.2%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 2.2%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 2.2%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 2.2%    |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 2         | 2.2%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 2.2%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 1.1%    |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 1         | 1.1%    |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 1.1%    |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 1.1%    |
| Nvidia GM204GLM [Quadro M3000M]                                                          | 1         | 1.1%    |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 1.1%    |
| Nvidia GK107M [GeForce GT 745M]                                                          | 1         | 1.1%    |
| Nvidia GF106GLM [Quadro 2000M]                                                           | 1         | 1.1%    |
| Nvidia GA107M [GeForce RTX 2050]                                                         | 1         | 1.1%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 1.1%    |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 1         | 1.1%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 1.1%    |
| Intel JasperLake [UHD Graphics]                                                          | 1         | 1.1%    |
| Intel HD Graphics 630                                                                    | 1         | 1.1%    |
| Intel HD Graphics 5300                                                                   | 1         | 1.1%    |
| Intel HD Graphics 530                                                                    | 1         | 1.1%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 41        | 57.75%  |
| Intel + Nvidia | 14        | 19.72%  |
| 1 x AMD        | 10        | 14.08%  |
| 1 x Nvidia     | 4         | 5.63%   |
| AMD + Nvidia   | 2         | 2.82%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 64        | 90.14%  |
| Proprietary | 6         | 8.45%   |
| Unknown     | 1         | 1.41%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 47        | 65.28%  |
| 0.01-0.5   | 7         | 9.72%   |
| 1.01-2.0   | 6         | 8.33%   |
| 0.51-1.0   | 5         | 6.94%   |
| 7.01-8.0   | 3         | 4.17%   |
| 3.01-4.0   | 3         | 4.17%   |
| 5.01-6.0   | 1         | 1.39%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Chimei Innolux      | 14        | 18.18%  |
| BOE                 | 14        | 18.18%  |
| LG Display          | 13        | 16.88%  |
| AU Optronics        | 12        | 15.58%  |
| Samsung Electronics | 6         | 7.79%   |
| Sharp               | 4         | 5.19%   |
| Lenovo              | 3         | 3.9%    |
| Hewlett-Packard     | 3         | 3.9%    |
| Goldstar            | 3         | 3.9%    |
| Valve               | 1         | 1.3%    |
| Sony                | 1         | 1.3%    |
| PANDA               | 1         | 1.3%    |
| Panasonic           | 1         | 1.3%    |
| Dell                | 1         | 1.3%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 3         | 3.9%    |
| Samsung Electronics LCD Monitor SDC416E 2880x1620 344x194mm 15.5-inch | 2         | 2.6%    |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 2         | 2.6%    |
| LG Display LCD Monitor LGD0353 1366x768 345x194mm 15.6-inch           | 2         | 2.6%    |
| Lenovo LCD Monitor LEN4035 1280x800 303x189mm 14.1-inch               | 2         | 2.6%    |
| Goldstar ULTRAGEAR GSM7765 2560x1440 697x392mm 31.5-inch              | 2         | 2.6%    |
| Chimei Innolux LCD Monitor CMN14FF 1920x1080 309x173mm 13.9-inch      | 2         | 2.6%    |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 2         | 2.6%    |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 1         | 1.3%    |
| Sony TV SNY8102 1360x768                                              | 1         | 1.3%    |
| Sharp LQ173M1JW05 SHP14EC 1920x1080 382x215mm 17.3-inch               | 1         | 1.3%    |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 1         | 1.3%    |
| Sharp LQ125T1JW02 SHP142F 2560x1440 277x155mm 12.5-inch               | 1         | 1.3%    |
| Sharp LCD Monitor SHP14C4 1920x1080 344x194mm 15.5-inch               | 1         | 1.3%    |
| Samsung Electronics SyncMaster SAM0428 1680x1050 459x296mm 21.5-inch  | 1         | 1.3%    |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch  | 1         | 1.3%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 1.3%    |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch  | 1         | 1.3%    |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch               | 1         | 1.3%    |
| Panasonic LCD Monitor MEI96A2 2560x1440 309x173mm 13.9-inch           | 1         | 1.3%    |
| LG Display LCD Monitor LGD0625 1920x1080 344x194mm 15.5-inch          | 1         | 1.3%    |
| LG Display LCD Monitor LGD0599 1920x1080 309x174mm 14.0-inch          | 1         | 1.3%    |
| LG Display LCD Monitor LGD0508 1366x768 309x174mm 14.0-inch           | 1         | 1.3%    |
| LG Display LCD Monitor LGD03D7 1366x768 310x174mm 14.0-inch           | 1         | 1.3%    |
| LG Display LCD Monitor LGD032C 1920x1080 344x194mm 15.5-inch          | 1         | 1.3%    |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch           | 1         | 1.3%    |
| LG Display LCD Monitor LGD02D9 1920x1080 344x194mm 15.5-inch          | 1         | 1.3%    |
| LG Display LCD Monitor LGD028A 1366x768 344x194mm 15.5-inch           | 1         | 1.3%    |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch           | 1         | 1.3%    |
| Lenovo LCD Monitor LEN4031 1280x800 303x190mm 14.1-inch               | 1         | 1.3%    |
| Hewlett-Packard P223 HPN3392 1920x1080 477x268mm 21.5-inch            | 1         | 1.3%    |
| Hewlett-Packard 27m HPN3579 1920x1080 598x336mm 27.0-inch             | 1         | 1.3%    |
| Hewlett-Packard 22fw HPN3541 1920x1080 476x268mm 21.5-inch            | 1         | 1.3%    |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                   | 1         | 1.3%    |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                      | 1         | 1.3%    |
| Chimei Innolux LCD Monitor CMN1774 1920x1080 381x214mm 17.2-inch      | 1         | 1.3%    |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch      | 1         | 1.3%    |
| Chimei Innolux LCD Monitor CMN15CC 1366x768 344x193mm 15.5-inch       | 1         | 1.3%    |
| Chimei Innolux LCD Monitor CMN15B6 1366x768 344x194mm 15.5-inch       | 1         | 1.3%    |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch      | 1         | 1.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 33        | 44%     |
| 1366x768 (WXGA)    | 22        | 29.33%  |
| 1600x900 (HD+)     | 4         | 5.33%   |
| 1280x800 (WXGA)    | 4         | 5.33%   |
| 3840x2160 (4K)     | 3         | 4%      |
| 2560x1440 (QHD)    | 3         | 4%      |
| 2880x1620          | 2         | 2.67%   |
| 800x1280           | 1         | 1.33%   |
| 2256x1504          | 1         | 1.33%   |
| 1680x1050 (WSXGA+) | 1         | 1.33%   |
| 1360x768           | 1         | 1.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 30        | 38.96%  |
| 14     | 13        | 16.88%  |
| 13     | 11        | 14.29%  |
| 17     | 7         | 9.09%   |
| 12     | 3         | 3.9%    |
| 31     | 2         | 2.6%    |
| 21     | 2         | 2.6%    |
| 16     | 2         | 2.6%    |
| 72     | 1         | 1.3%    |
| 27     | 1         | 1.3%    |
| 24     | 1         | 1.3%    |
| 23     | 1         | 1.3%    |
| 20     | 1         | 1.3%    |
| 11     | 1         | 1.3%    |
| 7      | 1         | 1.3%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 51        | 66.23%  |
| 351-400     | 10        | 12.99%  |
| 201-300     | 6         | 7.79%   |
| 401-500     | 4         | 5.19%   |
| 601-700     | 2         | 2.6%    |
| 501-600     | 2         | 2.6%    |
| 1501-2000   | 1         | 1.3%    |
| 1-100       | 1         | 1.3%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 63        | 88.73%  |
| 16/10 | 5         | 7.04%   |
| 3/2   | 2         | 2.82%   |
| 0.67  | 1         | 1.41%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 32        | 41.56%  |
| 81-90          | 23        | 29.87%  |
| 121-130        | 7         | 9.09%   |
| 61-70          | 3         | 3.9%    |
| 351-500        | 2         | 2.6%    |
| 201-250        | 2         | 2.6%    |
| 151-200        | 2         | 2.6%    |
| More than 1000 | 1         | 1.3%    |
| 71-80          | 1         | 1.3%    |
| 51-60          | 1         | 1.3%    |
| 1-40           | 1         | 1.3%    |
| 301-350        | 1         | 1.3%    |
| 251-300        | 1         | 1.3%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 35        | 46.67%  |
| 101-120       | 21        | 28%     |
| 51-100        | 10        | 13.33%  |
| 161-240       | 5         | 6.67%   |
| More than 240 | 3         | 4%      |
| 1-50          | 1         | 1.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 63        | 88.73%  |
| 2     | 8         | 11.27%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 50        | 43.1%   |
| Realtek Semiconductor | 35        | 30.17%  |
| Qualcomm Atheros      | 9         | 7.76%   |
| ASIX Electronics      | 5         | 4.31%   |
| Broadcom Limited      | 4         | 3.45%   |
| MediaTek              | 3         | 2.59%   |
| Broadcom              | 3         | 2.59%   |
| Ralink Technology     | 2         | 1.72%   |
| Sitecom Europe        | 1         | 0.86%   |
| Sierra Wireless       | 1         | 0.86%   |
| Huawei Technologies   | 1         | 0.86%   |
| Hewlett-Packard       | 1         | 0.86%   |
| Dell                  | 1         | 0.86%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 22        | 15.6%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 3.55%   |
| Intel Wireless 8265 / 8275                                        | 5         | 3.55%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 4         | 2.84%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 2.84%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 2.13%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3         | 2.13%   |
| Intel Wireless 8260                                               | 3         | 2.13%   |
| Intel Wireless 7265                                               | 3         | 2.13%   |
| Intel Wireless 7260                                               | 3         | 2.13%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 2.13%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 2.13%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 2.13%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 1.42%   |
| Ralink MT7601U Wireless Adapter                                   | 2         | 1.42%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 1.42%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 1.42%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 2         | 1.42%   |
| Intel Wireless-AC 9260                                            | 2         | 1.42%   |
| Intel Wireless 3160                                               | 2         | 1.42%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 1.42%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 1.42%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.42%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.42%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 1.42%   |
| Intel Centrino Ultimate-N 6300                                    | 2         | 1.42%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 1.42%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.42%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                           | 2         | 1.42%   |
| Sitecom Europe WL-113 rev 2 Wireless Network USB Adapter          | 1         | 0.71%   |
| Sierra Wireless EM7305                                            | 1         | 0.71%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 0.71%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1         | 0.71%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 0.71%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 0.71%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1         | 0.71%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 0.71%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.71%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 0.71%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 1         | 0.71%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 46        | 61.33%  |
| Realtek Semiconductor | 10        | 13.33%  |
| Qualcomm Atheros      | 7         | 9.33%   |
| MediaTek              | 3         | 4%      |
| Broadcom Limited      | 3         | 4%      |
| Ralink Technology     | 2         | 2.67%   |
| Sitecom Europe        | 1         | 1.33%   |
| Sierra Wireless       | 1         | 1.33%   |
| Dell                  | 1         | 1.33%   |
| Broadcom              | 1         | 1.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                                            | 5         | 6.58%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 4         | 5.26%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 3         | 3.95%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 3         | 3.95%   |
| Intel Wireless 8260                                                                   | 3         | 3.95%   |
| Intel Wireless 7265                                                                   | 3         | 3.95%   |
| Intel Wireless 7260                                                                   | 3         | 3.95%   |
| Intel Wi-Fi 6 AX200                                                                   | 3         | 3.95%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 3         | 3.95%   |
| Ralink MT7601U Wireless Adapter                                                       | 2         | 2.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 2         | 2.63%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                         | 2         | 2.63%   |
| Intel Wireless-AC 9260                                                                | 2         | 2.63%   |
| Intel Wireless 3160                                                                   | 2         | 2.63%   |
| Intel Wi-Fi 6 AX201                                                                   | 2         | 2.63%   |
| Intel Tiger Lake PCH CNVi WiFi                                                        | 2         | 2.63%   |
| Intel Centrino Ultimate-N 6300                                                        | 2         | 2.63%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 2         | 2.63%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                                               | 2         | 2.63%   |
| Sitecom Europe WL-113 rev 2 Wireless Network USB Adapter                              | 1         | 1.32%   |
| Sierra Wireless EM7305                                                                | 1         | 1.32%   |
| Realtek RTL8723DE Wireless Network Adapter                                            | 1         | 1.32%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                       | 1         | 1.32%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                           | 1         | 1.32%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 1.32%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                               | 1         | 1.32%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 1         | 1.32%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                      | 1         | 1.32%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 1         | 1.32%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 1.32%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 1         | 1.32%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 1         | 1.32%   |
| Intel Wireless 3165                                                                   | 1         | 1.32%   |
| Intel WiFi Link 5100                                                                  | 1         | 1.32%   |
| Intel Wi-Fi 6 AX201 160MHz                                                            | 1         | 1.32%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                         | 1         | 1.32%   |
| Intel Gemini Lake PCH CNVi WiFi                                                       | 1         | 1.32%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 1         | 1.32%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 1         | 1.32%   |
| Intel Centrino Wireless-N 2230                                                        | 1         | 1.32%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 30        | 47.62%  |
| Intel                 | 20        | 31.75%  |
| ASIX Electronics      | 5         | 7.94%   |
| Qualcomm Atheros      | 4         | 6.35%   |
| Broadcom              | 2         | 3.17%   |
| Huawei Technologies   | 1         | 1.59%   |
| Broadcom Limited      | 1         | 1.59%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 22        | 34.38%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 7.81%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 6.25%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 4.69%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 3.13%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 3.13%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 3.13%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 3.13%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 3.13%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 3.13%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.56%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.56%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 1.56%   |
| Intel Ethernet Connection I218-V                                  | 1         | 1.56%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.56%   |
| Intel Ethernet Connection (5) I219-V                              | 1         | 1.56%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.56%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.56%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.56%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.56%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 1.56%   |
| Huawei E353/E3131                                                 | 1         | 1.56%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.56%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 1.56%   |
| Broadcom Limited NetXtreme BCM5756ME Gigabit Ethernet PCI Express | 1         | 1.56%   |
| ASIX AX88772B                                                     | 1         | 1.56%   |
| ASIX AX88772A Fast Ethernet                                       | 1         | 1.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 71        | 53.38%  |
| Ethernet | 61        | 45.86%  |
| Modem    | 1         | 0.75%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 55        | 74.32%  |
| Ethernet | 19        | 25.68%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 54        | 76.06%  |
| 1     | 15        | 21.13%  |
| 0     | 2         | 2.82%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 64        | 90.14%  |
| Yes  | 7         | 9.86%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 40        | 64.52%  |
| Realtek Semiconductor           | 7         | 11.29%  |
| Broadcom                        | 5         | 8.06%   |
| IMC Networks                    | 4         | 6.45%   |
| Qualcomm Atheros Communications | 3         | 4.84%   |
| Toshiba                         | 1         | 1.61%   |
| Foxconn / Hon Hai               | 1         | 1.61%   |
| Cambridge Silicon Radio         | 1         | 1.61%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 18        | 29.03%  |
| Intel AX201 Bluetooth                               | 7         | 11.29%  |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 6.45%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 6.45%   |
| Intel AX210 Bluetooth                               | 4         | 6.45%   |
| Realtek Bluetooth Radio                             | 3         | 4.84%   |
| Intel AX200 Bluetooth                               | 3         | 4.84%   |
| IMC Networks Wireless_Device                        | 3         | 4.84%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 3.23%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 3.23%   |
| Toshiba Askey Bluetooth Module                      | 1         | 1.61%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 1.61%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.61%   |
| Intel Bluetooth Device                              | 1         | 1.61%   |
| IMC Networks Bluetooth Radio                        | 1         | 1.61%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 1.61%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 1.61%   |
| Broadcom HP Portable SoftSailing                    | 1         | 1.61%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 1.61%   |
| Broadcom BCM20702A0                                 | 1         | 1.61%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.61%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 1         | 1.61%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 62        | 67.39%  |
| Nvidia              | 16        | 17.39%  |
| AMD                 | 12        | 13.04%  |
| Texas Instruments   | 1         | 1.09%   |
| C-Media Electronics | 1         | 1.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 10        | 9.26%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 7         | 6.48%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6         | 5.56%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 5         | 4.63%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 4.63%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 4         | 3.7%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 3.7%    |
| Intel Broadwell-U Audio Controller                                                                | 4         | 3.7%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 4         | 3.7%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 3.7%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 2.78%   |
| Nvidia Audio device                                                                               | 3         | 2.78%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 2.78%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 2.78%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 2.78%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 2.78%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 2.78%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 1.85%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 1.85%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 1.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.85%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 1.85%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 1.85%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 1.85%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 1.85%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 1.85%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.93%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.93%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1         | 0.93%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 0.93%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.93%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 0.93%   |
| Intel Jasper Lake HD Audio                                                                        | 1         | 0.93%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.93%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.93%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 0.93%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 0.93%   |
| C-Media Electronics CM6631A Audio Processor                                                       | 1         | 0.93%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 1         | 0.93%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 1         | 0.93%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 20        | 28.57%  |
| Samsung Electronics | 18        | 25.71%  |
| Kingston            | 9         | 12.86%  |
| Micron Technology   | 7         | 10%     |
| Crucial             | 4         | 5.71%   |
| Unknown             | 2         | 2.86%   |
| Ramaxel Technology  | 2         | 2.86%   |
| Corsair             | 2         | 2.86%   |
| Smart               | 1         | 1.43%   |
| Neo Forza           | 1         | 1.43%   |
| Nanya Technology    | 1         | 1.43%   |
| Essencore Limited   | 1         | 1.43%   |
| Elpida              | 1         | 1.43%   |
| A-DATA Technology   | 1         | 1.43%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s        | 2         | 2.74%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 2.74%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips 6400MT/s        | 2         | 2.74%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 2.74%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 2.74%   |
| Unknown RAM Module 1024MB SODIMM SDRAM                           | 1         | 1.37%   |
| Unknown RAM Module 1024MB SODIMM DDR2 533MT/s                    | 1         | 1.37%   |
| Smart RAM SH5641G8FJ8NWRNSQG 8GB SODIMM DDR3 1600MT/s            | 1         | 1.37%   |
| SK hynix RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s          | 1         | 1.37%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                  | 1         | 1.37%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 975MT/s             | 1         | 1.37%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.37%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.37%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.37%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.37%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.37%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 1.37%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.37%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.37%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 1         | 1.37%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s           | 1         | 1.37%   |
| SK hynix RAM H9CCNNNCLGALAR-NUD 8GB Row Of Chips LPDDR3 1867MT/s | 1         | 1.37%   |
| SK hynix RAM 746448-381 4096MB SODIMM LPDDR3 1600MT/s            | 1         | 1.37%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s            | 1         | 1.37%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s         | 1         | 1.37%   |
| Samsung RAM M471B5273DH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.37%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.37%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.37%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.37%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.37%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 1         | 1.37%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 1.37%   |
| Samsung RAM M471A5244BB0-CPB 4GB SODIMM DDR4 2400MT/s            | 1         | 1.37%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 1         | 1.37%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.37%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 1         | 1.37%   |
| Samsung RAM K3LK7K70BM-BGCP000 4096MB SODIMM 4266MT/s            | 1         | 1.37%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s          | 1         | 1.37%   |
| Ramaxel RAM RMT3150ED58E8W1600 2GB SODIMM DDR3 1600MT/s          | 1         | 1.37%   |
| Ramaxel RAM RMSA3260MH78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 1         | 1.37%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 29        | 47.54%  |
| DDR3   | 18        | 29.51%  |
| LPDDR5 | 3         | 4.92%   |
| LPDDR4 | 3         | 4.92%   |
| LPDDR3 | 3         | 4.92%   |
| SDRAM  | 2         | 3.28%   |
| DDR2   | 2         | 3.28%   |
| DDR5   | 1         | 1.64%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 55        | 90.16%  |
| Row Of Chips | 6         | 9.84%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 31        | 45.59%  |
| 4096  | 23        | 33.82%  |
| 16384 | 7         | 10.29%  |
| 2048  | 4         | 5.88%   |
| 1024  | 2         | 2.94%   |
| 32768 | 1         | 1.47%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 17        | 26.15%  |
| 3200    | 13        | 20%     |
| 2667    | 13        | 20%     |
| 2400    | 5         | 7.69%   |
| 2133    | 3         | 4.62%   |
| 6400    | 2         | 3.08%   |
| 1334    | 2         | 3.08%   |
| 4800    | 1         | 1.54%   |
| 4267    | 1         | 1.54%   |
| 4266    | 1         | 1.54%   |
| 4199    | 1         | 1.54%   |
| 1867    | 1         | 1.54%   |
| 1333    | 1         | 1.54%   |
| 975     | 1         | 1.54%   |
| 701     | 1         | 1.54%   |
| 533     | 1         | 1.54%   |
| Unknown | 1         | 1.54%   |

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
| Chicony Electronics                    | 20        | 31.25%  |
| Realtek Semiconductor                  | 5         | 7.81%   |
| Bison Electronics                      | 5         | 7.81%   |
| Microdia                               | 4         | 6.25%   |
| IMC Networks                           | 4         | 6.25%   |
| Quanta                                 | 3         | 4.69%   |
| Luxvisions Innotech Limited            | 3         | 4.69%   |
| Lite-On Technology                     | 3         | 4.69%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 4.69%   |
| Acer                                   | 3         | 4.69%   |
| Syntek                                 | 2         | 3.13%   |
| Sunplus Innovation Technology          | 2         | 3.13%   |
| Sonix Technology                       | 2         | 3.13%   |
| Silicon Motion                         | 1         | 1.56%   |
| Samsung Electronics                    | 1         | 1.56%   |
| Motorola PCS                           | 1         | 1.56%   |
| Logitech                               | 1         | 1.56%   |
| Lenovo                                 | 1         | 1.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 4         | 6.25%   |
| Bison HD Webcam                                      | 3         | 4.69%   |
| Acer BisonCam,NB Pro                                 | 3         | 4.69%   |
| Sonix USB2.0 FHD UVC WebCam                          | 2         | 3.13%   |
| Quanta HP Webcam                                     | 2         | 3.13%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 2         | 3.13%   |
| Chicony HD User Facing                               | 2         | 3.13%   |
| Chicony FJ Camera                                    | 2         | 3.13%   |
| Syntek USB2.0 Camera                                 | 1         | 1.56%   |
| Syntek Integrated Camera                             | 1         | 1.56%   |
| Sunplus Laptop_Integrated_Webcam_FHD                 | 1         | 1.56%   |
| Sunplus Integrated_Webcam_HD                         | 1         | 1.56%   |
| Silicon Motion Web Camera                            | 1         | 1.56%   |
| Samsung Galaxy series, misc. (MTP mode)              | 1         | 1.56%   |
| Realtek USB Camera                                   | 1         | 1.56%   |
| Realtek Laptop Camera                                | 1         | 1.56%   |
| Realtek Integrated Camera                            | 1         | 1.56%   |
| Realtek EasyCamera                                   | 1         | 1.56%   |
| Realtek 2SF022                                       | 1         | 1.56%   |
| Quanta HP Wide Vision HD Camera                      | 1         | 1.56%   |
| Motorola PCS XT1033 [Moto G], PTP mode               | 1         | 1.56%   |
| Microdia Laptop_Integrated_Webcam_2M                 | 1         | 1.56%   |
| Microdia Integrated_Webcam_HD                        | 1         | 1.56%   |
| Microdia Integrated Webcam                           | 1         | 1.56%   |
| Microdia Dell Integrated HD Webcam                   | 1         | 1.56%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 1.56%   |
| Logitech C920 PRO HD Webcam                          | 1         | 1.56%   |
| Lite-On TOSHIBA Web Camera - FHD                     | 1         | 1.56%   |
| Lite-On Integrated Camera                            | 1         | 1.56%   |
| Lite-On HP TrueVision HD Camera                      | 1         | 1.56%   |
| Lenovo Integrated Webcam [R5U877]                    | 1         | 1.56%   |
| IMC Networks UVC VGA Webcam                          | 1         | 1.56%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 1         | 1.56%   |
| IMC Networks Lenovo EasyCamera                       | 1         | 1.56%   |
| IMC Networks Integrated Camera                       | 1         | 1.56%   |
| Chicony Web Camera - FHD                             | 1         | 1.56%   |
| Chicony TOSHIBA Web Camera - HD                      | 1         | 1.56%   |
| Chicony TOSHIBA Web Camera - FHD                     | 1         | 1.56%   |
| Chicony Integrated Camera [ThinkPad]                 | 1         | 1.56%   |
| Chicony Integrated Camera (1280x720@30)              | 1         | 1.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 9         | 47.37%  |
| Synaptics                          | 3         | 15.79%  |
| Realtek USB2.0 Finger Print Bridge | 2         | 10.53%  |
| Elan Microelectronics              | 2         | 10.53%  |
| STMicroelectronics                 | 1         | 5.26%   |
| Shenzhen Goodix Technology         | 1         | 5.26%   |
| LighTuning Technology              | 1         | 5.26%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI                                 | 3         | 15.79%  |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 2         | 10.53%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor               | 1         | 5.26%   |
| Validity Sensors VFS495 Fingerprint Reader                      | 1         | 5.26%   |
| Validity Sensors VFS451 Fingerprint Reader                      | 1         | 5.26%   |
| Validity Sensors VFS300 Fingerprint Reader                      | 1         | 5.26%   |
| Validity Sensors VFS Fingerprint sensor                         | 1         | 5.26%   |
| Validity Sensors VFS 5011 fingerprint sensor                    | 1         | 5.26%   |
| Synaptics UWP WBDI                                              | 1         | 5.26%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 1         | 5.26%   |
| STMicroelectronics Fingerprint Reader                           | 1         | 5.26%   |
| Shenzhen Goodix  FingerPrint Device                             | 1         | 5.26%   |
| LighTuning EgisTec Touch Fingerprint Sensor                     | 1         | 5.26%   |
| Elan ELAN:Fingerprint                                           | 1         | 5.26%   |
| Elan ELAN:ARM-M4                                                | 1         | 5.26%   |
| Unknown                                                         | 1         | 5.26%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 3         | 37.5%   |
| Broadcom              | 2         | 25%     |
| O2 Micro              | 1         | 12.5%   |
| Lenovo                | 1         | 12.5%   |
| Gemalto (was Gemplus) | 1         | 12.5%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                    | 3         | 37.5%   |
| O2 Micro OZ776 CCID Smartcard Reader                   | 1         | 12.5%   |
| Lenovo Integrated Smart Card Reader                    | 1         | 12.5%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer | 1         | 12.5%   |
| Broadcom BCM5880 Secure Applications Processor         | 1         | 12.5%   |
| Broadcom 5880                                          | 1         | 12.5%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 39        | 52.7%   |
| 1     | 22        | 29.73%  |
| 2     | 10        | 13.51%  |
| 3     | 3         | 4.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 18        | 35.29%  |
| Graphics card            | 8         | 15.69%  |
| Chipcard                 | 8         | 15.69%  |
| Net/wireless             | 4         | 7.84%   |
| Multimedia controller    | 3         | 5.88%   |
| Card reader              | 3         | 5.88%   |
| Camera                   | 2         | 3.92%   |
| Storage                  | 1         | 1.96%   |
| Net/ethernet             | 1         | 1.96%   |
| Firewire controller      | 1         | 1.96%   |
| Communication controller | 1         | 1.96%   |
| Bluetooth                | 1         | 1.96%   |

