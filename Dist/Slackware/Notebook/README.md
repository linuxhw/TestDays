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

Total: 104

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo    | V330-14ARR 81B1             | [b80592c227](https://linux-hardware.org/?probe=b80592c227) | Oct 21, 2023 |
| Toshiba   | Satellite C660              | [483998d7de](https://linux-hardware.org/?probe=483998d7de) | Oct 20, 2023 |
| HP        | OMEN by Laptop 16-b1xxx     | [aafdab7043](https://linux-hardware.org/?probe=aafdab7043) | Oct 13, 2023 |
| HP        | OMEN by Laptop 16-b1xxx     | [a1a64b6621](https://linux-hardware.org/?probe=a1a64b6621) | Oct 05, 2023 |
| Notebook  | P7xxTM                      | [e14cfa2f1f](https://linux-hardware.org/?probe=e14cfa2f1f) | Sep 22, 2023 |
| Notebook  | P7xxTM                      | [41b1348520](https://linux-hardware.org/?probe=41b1348520) | Sep 22, 2023 |
| Lenovo    | ThinkPad E16 Gen 1 21JT0... | [586c1fab43](https://linux-hardware.org/?probe=586c1fab43) | Sep 06, 2023 |
| ASUSTek   | ASUS TUF Dash F15 FX517Z... | [10db09006a](https://linux-hardware.org/?probe=10db09006a) | Aug 31, 2023 |
| Dell      | Vostro 3405                 | [2ba4151315](https://linux-hardware.org/?probe=2ba4151315) | Aug 19, 2023 |
| Lenovo    | ThinkPad X1 Carbon 4th 2... | [b8ceea98b8](https://linux-hardware.org/?probe=b8ceea98b8) | Aug 18, 2023 |
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
| Slackware 15.0  | 48        | 61.54%  |
| Slackware 14.2  | 27        | 34.62%  |
| Slackware 14.2+ | 3         | 3.85%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| Slackware | 78        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.15.19           | 12        | 14.12%  |
| 5.15.117          | 4         | 4.71%   |
| 4.19.80           | 4         | 4.71%   |
| 5.19.17           | 3         | 3.53%   |
| 6.1.44            | 2         | 2.35%   |
| 5.3.7             | 2         | 2.35%   |
| 5.17.1            | 2         | 2.35%   |
| 5.15.80           | 2         | 2.35%   |
| 5.15.38           | 2         | 2.35%   |
| 5.13.8            | 2         | 2.35%   |
| 4.4.276           | 2         | 2.35%   |
| 6.5.5             | 1         | 1.18%   |
| 6.1.51            | 1         | 1.18%   |
| 6.1.12            | 1         | 1.18%   |
| 6.1.1             | 1         | 1.18%   |
| 5.7.0             | 1         | 1.18%   |
| 5.5.10            | 1         | 1.18%   |
| 5.4.75            | 1         | 1.18%   |
| 5.4.50            | 1         | 1.18%   |
| 5.4.47            | 1         | 1.18%   |
| 5.4.24toshiba-new | 1         | 1.18%   |
| 5.4.2             | 1         | 1.18%   |
| 5.4.139-jw        | 1         | 1.18%   |
| 5.4.13            | 1         | 1.18%   |
| 5.2.2             | 1         | 1.18%   |
| 5.17.5            | 1         | 1.18%   |
| 5.17.2            | 1         | 1.18%   |
| 5.16.9-joe1       | 1         | 1.18%   |
| 5.16.12           | 1         | 1.18%   |
| 5.15.78.a         | 1         | 1.18%   |
| 5.15.63           | 1         | 1.18%   |
| 5.15.37.a         | 1         | 1.18%   |
| 5.15.33.kjh       | 1         | 1.18%   |
| 5.15.27           | 1         | 1.18%   |
| 5.15.118          | 1         | 1.18%   |
| 5.15.1            | 1         | 1.18%   |
| 5.14.9            | 1         | 1.18%   |
| 5.14.8            | 1         | 1.18%   |
| 5.14.10           | 1         | 1.18%   |
| 5.14.0            | 1         | 1.18%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.15.19  | 12        | 14.12%  |
| 5.15.117 | 4         | 4.71%   |
| 4.19.80  | 4         | 4.71%   |
| 5.19.17  | 3         | 3.53%   |
| 6.1.44   | 2         | 2.35%   |
| 5.3.7    | 2         | 2.35%   |
| 5.17.1   | 2         | 2.35%   |
| 5.15.80  | 2         | 2.35%   |
| 5.15.38  | 2         | 2.35%   |
| 5.13.8   | 2         | 2.35%   |
| 4.4.276  | 2         | 2.35%   |
| 4.4.190  | 2         | 2.35%   |
| 6.5.5    | 1         | 1.18%   |
| 6.1.51   | 1         | 1.18%   |
| 6.1.12   | 1         | 1.18%   |
| 6.1.1    | 1         | 1.18%   |
| 5.7.0    | 1         | 1.18%   |
| 5.5.10   | 1         | 1.18%   |
| 5.4.75   | 1         | 1.18%   |
| 5.4.50   | 1         | 1.18%   |
| 5.4.47   | 1         | 1.18%   |
| 5.4.24   | 1         | 1.18%   |
| 5.4.2    | 1         | 1.18%   |
| 5.4.139  | 1         | 1.18%   |
| 5.4.13   | 1         | 1.18%   |
| 5.2.2    | 1         | 1.18%   |
| 5.17.5   | 1         | 1.18%   |
| 5.17.2   | 1         | 1.18%   |
| 5.16.9   | 1         | 1.18%   |
| 5.16.12  | 1         | 1.18%   |
| 5.15.78  | 1         | 1.18%   |
| 5.15.63  | 1         | 1.18%   |
| 5.15.37  | 1         | 1.18%   |
| 5.15.33  | 1         | 1.18%   |
| 5.15.27  | 1         | 1.18%   |
| 5.15.118 | 1         | 1.18%   |
| 5.15.1   | 1         | 1.18%   |
| 5.14.9   | 1         | 1.18%   |
| 5.14.8   | 1         | 1.18%   |
| 5.14.10  | 1         | 1.18%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 27        | 32.14%  |
| 4.4     | 8         | 9.52%   |
| 5.4     | 7         | 8.33%   |
| 4.19    | 7         | 8.33%   |
| 5.10    | 6         | 7.14%   |
| 6.1     | 5         | 5.95%   |
| 5.13    | 5         | 5.95%   |
| 5.17    | 4         | 4.76%   |
| 5.19    | 3         | 3.57%   |
| 5.14    | 3         | 3.57%   |
| 5.3     | 2         | 2.38%   |
| 5.16    | 2         | 2.38%   |
| 6.5     | 1         | 1.19%   |
| 5.7     | 1         | 1.19%   |
| 5.5     | 1         | 1.19%   |
| 5.2     | 1         | 1.19%   |
| 4.16    | 1         | 1.19%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 77        | 98.72%  |
| i686   | 1         | 1.28%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| XFCE          | 26        | 32.5%   |
| KDE5          | 26        | 32.5%   |
| Unknown       | 18        | 22.5%   |
| KDE           | 3         | 3.75%   |
| xwmconfig     | 1         | 1.25%   |
| MATE          | 1         | 1.25%   |
| LXQt          | 1         | 1.25%   |
| GNOME         | 1         | 1.25%   |
| Enlightenment | 1         | 1.25%   |
| awesome       | 1         | 1.25%   |
| 2bwm          | 1         | 1.25%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 57        | 70.37%  |
| Tty     | 21        | 25.93%  |
| Wayland | 3         | 3.7%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 31        | 37.8%   |
| Unknown | 30        | 36.59%  |
| XDM     | 19        | 23.17%  |
| LightDM | 1         | 1.22%   |
| GDM     | 1         | 1.22%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 50        | 64.1%   |
| Unknown | 14        | 17.95%  |
| pt_BR   | 3         | 3.85%   |
| fr_FR   | 3         | 3.85%   |
| de_DE   | 3         | 3.85%   |
| ru_RU   | 2         | 2.56%   |
| it_IT   | 2         | 2.56%   |
| pl_PL   | 1         | 1.28%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 41        | 51.25%  |
| BIOS | 39        | 48.75%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 69        | 86.25%  |
| Btrfs   | 6         | 7.5%    |
| Overlay | 4         | 5%      |
| Xfs     | 1         | 1.25%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 50        | 62.5%   |
| MBR     | 18        | 22.5%   |
| Unknown | 12        | 15%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 68        | 85%     |
| Yes       | 12        | 15%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 50        | 63.29%  |
| Yes       | 29        | 36.71%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 21        | 26.92%  |
| Hewlett-Packard     | 16        | 20.51%  |
| Dell                | 8         | 10.26%  |
| ASUSTek Computer    | 7         | 8.97%   |
| MSI                 | 5         | 6.41%   |
| Acer                | 5         | 6.41%   |
| Toshiba             | 4         | 5.13%   |
| Notebook            | 3         | 3.85%   |
| Fujitsu             | 2         | 2.56%   |
| Dynabook            | 2         | 2.56%   |
| Valve               | 1         | 1.28%   |
| System76            | 1         | 1.28%   |
| Sony                | 1         | 1.28%   |
| Samsung Electronics | 1         | 1.28%   |
| Framework           | 1         | 1.28%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Toshiba Satellite C660                   | 2         | 2.56%   |
| Lenovo V330-14ARR 81B1                   | 2         | 2.56%   |
| ASUS VivoBook_ASUSLaptop K6500ZE_K6500ZE | 2         | 2.56%   |
| Valve Jupiter                            | 1         | 1.28%   |
| Toshiba Satellite P50-A-12Z              | 1         | 1.28%   |
| Toshiba PORTEGE Z30-A                    | 1         | 1.28%   |
| System76 Oryx Pro                        | 1         | 1.28%   |
| Sony SVE1713A1EW                         | 1         | 1.28%   |
| Samsung 300E5M/300E5L                    | 1         | 1.28%   |
| Notebook X170KM-G                        | 1         | 1.28%   |
| Notebook P7xxTM                          | 1         | 1.28%   |
| Notebook NL40_50CU                       | 1         | 1.28%   |
| MSI Modern 14 B11MO                      | 1         | 1.28%   |
| MSI Modern 14 B10MW                      | 1         | 1.28%   |
| MSI GP76 Leopard 11UG                    | 1         | 1.28%   |
| MSI GL73 8RC                             | 1         | 1.28%   |
| MSI GE76 Raider 11UE                     | 1         | 1.28%   |
| Lenovo ThinkPad X230 2325P38             | 1         | 1.28%   |
| Lenovo ThinkPad X140e 20BMS03E00         | 1         | 1.28%   |
| Lenovo ThinkPad X1 Carbon 7th 20R10015US | 1         | 1.28%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS04300 | 1         | 1.28%   |
| Lenovo ThinkPad X1 Carbon 4th 20FCS2FT00 | 1         | 1.28%   |
| Lenovo ThinkPad T61 765912G              | 1         | 1.28%   |
| Lenovo ThinkPad T470p 20J60018MS         | 1         | 1.28%   |
| Lenovo ThinkPad T470 20JNS01R01          | 1         | 1.28%   |
| Lenovo ThinkPad T470 20HDCTO1WW          | 1         | 1.28%   |
| Lenovo ThinkPad T450s 20BW000EUS         | 1         | 1.28%   |
| Lenovo ThinkPad T410 2518C3U             | 1         | 1.28%   |
| Lenovo ThinkPad T400 6474BV7             | 1         | 1.28%   |
| Lenovo ThinkPad P70 20ERCTO1WW           | 1         | 1.28%   |
| Lenovo ThinkPad L440 20ASS05K00          | 1         | 1.28%   |
| Lenovo ThinkPad Edge E530c 336669G       | 1         | 1.28%   |
| Lenovo ThinkPad E16 Gen 1 21JT000PJP     | 1         | 1.28%   |
| Lenovo IdeaPad P500 20210                | 1         | 1.28%   |
| Lenovo IdeaPad 5 15ALC05 82LN            | 1         | 1.28%   |
| Lenovo IdeaPad 310-15ISK 80SM            | 1         | 1.28%   |
| HP ProBook 6570b                         | 1         | 1.28%   |
| HP Pavilion Notebook                     | 1         | 1.28%   |
| HP Pavilion Gaming Laptop 16-a0xxx       | 1         | 1.28%   |
| HP Pavilion Gaming Laptop 15-ec1xxx      | 1         | 1.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 16        | 20.51%  |
| HP Laptop           | 4         | 5.13%   |
| Toshiba Satellite   | 3         | 3.85%   |
| Lenovo IdeaPad      | 3         | 3.85%   |
| HP Pavilion         | 3         | 3.85%   |
| HP EliteBook        | 3         | 3.85%   |
| Dell Latitude       | 3         | 3.85%   |
| ASUS VivoBook       | 3         | 3.85%   |
| MSI Modern          | 2         | 2.56%   |
| Lenovo V330-14ARR   | 2         | 2.56%   |
| HP OMEN             | 2         | 2.56%   |
| Fujitsu LIFEBOOK    | 2         | 2.56%   |
| Dell Vostro         | 2         | 2.56%   |
| Dell Precision      | 2         | 2.56%   |
| Acer Swift          | 2         | 2.56%   |
| Valve Jupiter       | 1         | 1.28%   |
| Toshiba PORTEGE     | 1         | 1.28%   |
| System76 Oryx       | 1         | 1.28%   |
| Sony SVE1713A1EW    | 1         | 1.28%   |
| Samsung 300E5M      | 1         | 1.28%   |
| Notebook X170KM-G   | 1         | 1.28%   |
| Notebook P7xxTM     | 1         | 1.28%   |
| Notebook NL40       | 1         | 1.28%   |
| MSI GP76            | 1         | 1.28%   |
| MSI GL73            | 1         | 1.28%   |
| MSI GE76            | 1         | 1.28%   |
| HP ProBook          | 1         | 1.28%   |
| HP ENVY             | 1         | 1.28%   |
| HP 245              | 1         | 1.28%   |
| HP 15               | 1         | 1.28%   |
| Framework Laptop    | 1         | 1.28%   |
| Dynabook PORTEGE    | 1         | 1.28%   |
| Dynabook P1-C7MP-BL | 1         | 1.28%   |
| Dell Inspiron       | 1         | 1.28%   |
| ASUS ROG            | 1         | 1.28%   |
| ASUS P53E           | 1         | 1.28%   |
| ASUS ASUS           | 1         | 1.28%   |
| ASUS 1000H          | 1         | 1.28%   |
| Acer Nitro          | 1         | 1.28%   |
| Acer Extensa        | 1         | 1.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 12        | 15.38%  |
| 2021 | 8         | 10.26%  |
| 2019 | 7         | 8.97%   |
| 2017 | 7         | 8.97%   |
| 2022 | 6         | 7.69%   |
| 2012 | 6         | 7.69%   |
| 2014 | 5         | 6.41%   |
| 2018 | 4         | 5.13%   |
| 2016 | 4         | 5.13%   |
| 2015 | 4         | 5.13%   |
| 2010 | 4         | 5.13%   |
| 2008 | 3         | 3.85%   |
| 2013 | 2         | 2.56%   |
| 2011 | 2         | 2.56%   |
| 2007 | 2         | 2.56%   |
| 2023 | 1         | 1.28%   |
| 2009 | 1         | 1.28%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 78        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 78        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 75        | 96.15%  |
| Yes  | 3         | 3.85%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 20        | 25.32%  |
| 8.01-16.0   | 20        | 25.32%  |
| 3.01-4.0    | 14        | 17.72%  |
| 16.01-24.0  | 13        | 16.46%  |
| 32.01-64.0  | 4         | 5.06%   |
| 64.01-256.0 | 3         | 3.8%    |
| 24.01-32.0  | 2         | 2.53%   |
| 1.01-2.0    | 2         | 2.53%   |
| 0.51-1.0    | 1         | 1.27%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 25        | 30.12%  |
| 1.01-2.0   | 25        | 30.12%  |
| 4.01-8.0   | 13        | 15.66%  |
| 3.01-4.0   | 8         | 9.64%   |
| 0.51-1.0   | 7         | 8.43%   |
| 0.01-0.5   | 3         | 3.61%   |
| 16.01-24.0 | 1         | 1.2%    |
| 8.01-16.0  | 1         | 1.2%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 56        | 70%     |
| 2      | 19        | 23.75%  |
| 4      | 2         | 2.5%    |
| 3      | 2         | 2.5%    |
| 0      | 1         | 1.25%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 59        | 75.64%  |
| Yes       | 19        | 24.36%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 68        | 87.18%  |
| No        | 10        | 12.82%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 78        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 67        | 85.9%   |
| No        | 11        | 14.1%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 16        | 20.51%  |
| Portugal     | 6         | 7.69%   |
| Brazil       | 5         | 6.41%   |
| UK           | 4         | 5.13%   |
| Japan        | 4         | 5.13%   |
| Italy        | 4         | 5.13%   |
| India        | 4         | 5.13%   |
| Germany      | 4         | 5.13%   |
| France       | 4         | 5.13%   |
| Russia       | 3         | 3.85%   |
| Kazakhstan   | 3         | 3.85%   |
| Canada       | 3         | 3.85%   |
| Sweden       | 2         | 2.56%   |
| South Africa | 2         | 2.56%   |
| Poland       | 2         | 2.56%   |
| Chile        | 2         | 2.56%   |
| Spain        | 1         | 1.28%   |
| Serbia       | 1         | 1.28%   |
| Romania      | 1         | 1.28%   |
| Philippines  | 1         | 1.28%   |
| Mexico       | 1         | 1.28%   |
| Iran         | 1         | 1.28%   |
| Greece       | 1         | 1.28%   |
| Finland      | 1         | 1.28%   |
| China        | 1         | 1.28%   |
| Argentina    | 1         | 1.28%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lisbon                 | 4         | 4.94%   |
| Warsaw                 | 2         | 2.47%   |
| Ust-Kamenogorsk        | 2         | 2.47%   |
| Tsukuba                | 2         | 2.47%   |
| Sun Prairie            | 2         | 2.47%   |
| Greater Noida          | 2         | 2.47%   |
| Frignano               | 2         | 2.47%   |
| Worpswede              | 1         | 1.23%   |
| Wokingham              | 1         | 1.23%   |
| Winnipeg               | 1         | 1.23%   |
| Voskresensk            | 1         | 1.23%   |
| Visconde do Rio Branco | 1         | 1.23%   |
| Villa Carlos Paz       | 1         | 1.23%   |
| Tendo                  | 1         | 1.23%   |
| Tehran                 | 1         | 1.23%   |
| Skövde                | 1         | 1.23%   |
| Sao Paulo              | 1         | 1.23%   |
| Santiago               | 1         | 1.23%   |
| San Antonio            | 1         | 1.23%   |
| Round Rock             | 1         | 1.23%   |
| Roknaes                | 1         | 1.23%   |
| Reno                   | 1         | 1.23%   |
| Renazzo                | 1         | 1.23%   |
| Redding                | 1         | 1.23%   |
| Puente Alto            | 1         | 1.23%   |
| Plainwell              | 1         | 1.23%   |
| Pinhal Novo            | 1         | 1.23%   |
| Pesaro                 | 1         | 1.23%   |
| Pasay                  | 1         | 1.23%   |
| Paris                  | 1         | 1.23%   |
| Ōtsu                  | 1         | 1.23%   |
| Oberstreit             | 1         | 1.23%   |
| Northport              | 1         | 1.23%   |
| Moscow                 | 1         | 1.23%   |
| Montreal               | 1         | 1.23%   |
| Milan                  | 1         | 1.23%   |
| Mexico City            | 1         | 1.23%   |
| Meuselwitz             | 1         | 1.23%   |
| McKinney               | 1         | 1.23%   |
| Luxeuil-les-Bains      | 1         | 1.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 20        | 27     | 20.41%  |
| WDC                         | 15        | 18     | 15.31%  |
| Kingston                    | 8         | 8      | 8.16%   |
| Seagate                     | 7         | 7      | 7.14%   |
| Toshiba                     | 6         | 6      | 6.12%   |
| Intel                       | 6         | 6      | 6.12%   |
| SanDisk                     | 5         | 7      | 5.1%    |
| Crucial                     | 5         | 6      | 5.1%    |
| HGST                        | 4         | 4      | 4.08%   |
| Unknown                     | 3         | 4      | 3.06%   |
| SK hynix                    | 3         | 3      | 3.06%   |
| Micron Technology           | 3         | 3      | 3.06%   |
| Gigabyte Technology         | 2         | 2      | 2.04%   |
| Transcend                   | 1         | 1      | 1.02%   |
| Silicon Motion              | 1         | 1      | 1.02%   |
| Plextor                     | 1         | 1      | 1.02%   |
| Patriot                     | 1         | 2      | 1.02%   |
| Netac                       | 1         | 1      | 1.02%   |
| Micron/Crucial Technology   | 1         | 1      | 1.02%   |
| KIOXIA                      | 1         | 1      | 1.02%   |
| Kingston Technology Company | 1         | 1      | 1.02%   |
| Hewlett-Packard             | 1         | 2      | 1.02%   |
| External                    | 1         | 1      | 1.02%   |
| Dogfish                     | 1         | 1      | 1.02%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                       | 5         | 4.76%   |
| WDC WD10SPZX-60Z10T0 1TB                              | 2         | 1.9%    |
| Toshiba MQ04ABF100 1TB                                | 2         | 1.9%    |
| Seagate ST1000LM048-2E7172 1TB                        | 2         | 1.9%    |
| Intel SSD 660P Series 1024GB                          | 2         | 1.9%    |
| HGST HTS725050A7E630 500GB                            | 2         | 1.9%    |
| WDC WDS500G2B0B-00YS70 500GB SSD                      | 1         | 0.95%   |
| WDC WDS100T2B0B-00YS70 1TB SSD                        | 1         | 0.95%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                        | 1         | 0.95%   |
| WDC WD7500BPVT-24HXZT3 752GB                          | 1         | 0.95%   |
| WDC WD5000LPCX-60VHAT1 500GB                          | 1         | 0.95%   |
| WDC WD5000BEKT-60KA9T0 500GB                          | 1         | 0.95%   |
| WDC WD10JPVX-35JC3T0 1TB                              | 1         | 0.95%   |
| WDC WD10JPVX-16JC3T3 1TB                              | 1         | 0.95%   |
| WDC WD10JPVT-08A1YT2 1TB                              | 1         | 0.95%   |
| WDC WD10JPLX-00MBPT0 1TB                              | 1         | 0.95%   |
| WDC WD Green 2.5 240GB                                | 1         | 0.95%   |
| WDC PC SN530 SDBPNPZ-1T00-1002 1TB                    | 1         | 0.95%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB                  | 1         | 0.95%   |
| WDC PC SN520 SDAPNUW-256G-1102 256GB                  | 1         | 0.95%   |
| Unknown SD32G  32GB                                   | 1         | 0.95%   |
| Unknown SC32G  32GB                                   | 1         | 0.95%   |
| Unknown MMC Card  512GB                               | 1         | 0.95%   |
| Transcend TS256GMTE352T-VLV 256GB                     | 1         | 0.95%   |
| Toshiba MQ01ACF032 320GB                              | 1         | 0.95%   |
| Toshiba MQ01ABF050 500GB                              | 1         | 0.95%   |
| Toshiba MK2565GSXN 250GB                              | 1         | 0.95%   |
| Toshiba MK1646GSX 160GB                               | 1         | 0.95%   |
| SK hynix HFM001TD3JX013N 1024GB                       | 1         | 0.95%   |
| SK hynix BC511 HFM512GDJTNI-82A0A 512GB               | 1         | 0.95%   |
| SK hynix BC511 512GB                                  | 1         | 0.95%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 1         | 0.95%   |
| Seagate ST9160827AS 160GB                             | 1         | 0.95%   |
| Seagate ST9160412AS 160GB                             | 1         | 0.95%   |
| Seagate ST500VT000-1DK142 500GB                       | 1         | 0.95%   |
| Seagate ST2000LX001-1RG174 2TB                        | 1         | 0.95%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 1         | 0.95%   |
| Sandisk WD PC SN740 SDDQNQD-1T00-1201 1024GB          | 1         | 0.95%   |
| Sandisk WD Black SN850 1TB                            | 1         | 0.95%   |
| SanDisk Ultra II 960GB SSD                            | 1         | 0.95%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| WDC      | 9         | 11     | 33.33%  |
| Seagate  | 7         | 7      | 25.93%  |
| Toshiba  | 6         | 6      | 22.22%  |
| HGST     | 4         | 4      | 14.81%  |
| External | 1         | 1      | 3.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 10     | 25.81%  |
| Kingston            | 7         | 7      | 22.58%  |
| Crucial             | 4         | 5      | 12.9%   |
| WDC                 | 3         | 4      | 9.68%   |
| SanDisk             | 3         | 3      | 9.68%   |
| Plextor             | 1         | 1      | 3.23%   |
| Patriot             | 1         | 2      | 3.23%   |
| Netac               | 1         | 1      | 3.23%   |
| Micron Technology   | 1         | 1      | 3.23%   |
| Gigabyte Technology | 1         | 1      | 3.23%   |
| Dogfish             | 1         | 1      | 3.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 36        | 45     | 37.89%  |
| SSD  | 30        | 36     | 31.58%  |
| HDD  | 26        | 29     | 27.37%  |
| MMC  | 3         | 4      | 3.16%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 47        | 62     | 52.81%  |
| NVMe | 36        | 45     | 40.45%  |
| SAS  | 3         | 3      | 3.37%   |
| MMC  | 3         | 4      | 3.37%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 35        | 41     | 62.5%   |
| 0.51-1.0   | 18        | 21     | 32.14%  |
| 1.01-2.0   | 3         | 3      | 5.36%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 24        | 30%     |
| 501-1000       | 23        | 28.75%  |
| 251-500        | 16        | 20%     |
| 1001-2000      | 8         | 10%     |
| 1-20           | 3         | 3.75%   |
| 21-50          | 2         | 2.5%    |
| More than 3000 | 1         | 1.25%   |
| 2001-3000      | 1         | 1.25%   |
| 51-100         | 1         | 1.25%   |
| Unknown        | 1         | 1.25%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 101-250   | 17        | 20.24%  |
| 21-50     | 15        | 17.86%  |
| 1-20      | 15        | 17.86%  |
| 251-500   | 12        | 14.29%  |
| 51-100    | 12        | 14.29%  |
| 501-1000  | 9         | 10.71%  |
| 1001-2000 | 3         | 3.57%   |
| Unknown   | 1         | 1.19%   |

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
| Works    | 62        | 82     | 72.09%  |
| Detected | 17        | 25     | 19.77%  |
| Malfunc  | 7         | 7      | 8.14%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 54        | 58.7%   |
| Samsung Electronics         | 12        | 13.04%  |
| AMD                         | 8         | 8.7%    |
| SanDisk                     | 5         | 5.43%   |
| SK hynix                    | 3         | 3.26%   |
| Micron/Crucial Technology   | 2         | 2.17%   |
| Micron Technology           | 2         | 2.17%   |
| Kingston Technology Company | 2         | 2.17%   |
| Silicon Motion              | 1         | 1.09%   |
| Phison Electronics          | 1         | 1.09%   |
| KIOXIA                      | 1         | 1.09%   |
| Biwin Storage Technology    | 1         | 1.09%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 7         | 7.07%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 6         | 6.06%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 5         | 5.05%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 5         | 5.05%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 5         | 5.05%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 4         | 4.04%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 4         | 4.04%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 3         | 3.03%   |
| Intel Volume Management Device NVMe RAID Controller                              | 3         | 3.03%   |
| Intel SSD 660P Series                                                            | 3         | 3.03%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3         | 3.03%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 3.03%   |
| SK hynix BC511 NVMe SSD                                                          | 2         | 2.02%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 2.02%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 2         | 2.02%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 2.02%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 2.02%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 2.02%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 2.02%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 2         | 2.02%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 2         | 2.02%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 2         | 2.02%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 1         | 1.01%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 1         | 1.01%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                       | 1         | 1.01%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                            | 1         | 1.01%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD          | 1         | 1.01%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 1         | 1.01%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                            | 1         | 1.01%   |
| Phison E8 PCIe3 NVMe Controller                                                  | 1         | 1.01%   |
| Micron 3400 NVMe SSD [Hendrix]                                                   | 1         | 1.01%   |
| Micron 2210 NVMe SSD [Cobain]                                                    | 1         | 1.01%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 1         | 1.01%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 1         | 1.01%   |
| Kingston Company A1000/U-SNS8154P3 x2 NVMe SSD                                   | 1         | 1.01%   |
| Intel Tiger Lake-LP SATA Controller                                              | 1         | 1.01%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                                 | 1         | 1.01%   |
| Intel SSD 670p Series [Keystone Harbor]                                          | 1         | 1.01%   |
| Intel SSD 600P Series                                                            | 1         | 1.01%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 1.01%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 50        | 51.55%  |
| NVMe | 35        | 36.08%  |
| RAID | 8         | 8.25%   |
| IDE  | 4         | 4.12%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 66        | 84.62%  |
| AMD    | 12        | 15.38%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 4         | 5.13%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 3         | 3.85%   |
| Intel 12th Gen Core i7-12700H                 | 3         | 3.85%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 3         | 3.85%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 2.56%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 2.56%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 2.56%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 2.56%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 1         | 1.28%   |
| Intel Pentium CPU P6100 @ 2.00GHz             | 1         | 1.28%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 1.28%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 1         | 1.28%   |
| Intel CPU Version                             | 1         | 1.28%   |
| Intel Core M-5Y51 CPU @ 1.10GHz               | 1         | 1.28%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 1.28%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 1         | 1.28%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 1.28%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 1.28%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 1.28%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 1.28%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 1.28%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 1.28%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 1.28%   |
| Intel Core i7-3840QM CPU @ 2.80GHz            | 1         | 1.28%   |
| Intel Core i7-2860QM CPU @ 2.50GHz            | 1         | 1.28%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 1         | 1.28%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 1         | 1.28%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 1.28%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 1.28%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 1         | 1.28%   |
| Intel Core i5-4310M CPU @ 2.70GHz             | 1         | 1.28%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 1.28%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 1.28%   |
| Intel Core i5-3360M CPU @ 2.80GHz             | 1         | 1.28%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 1.28%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 1.28%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 1.28%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 1         | 1.28%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 1         | 1.28%   |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 1         | 1.28%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 19        | 24.36%  |
| Other                | 15        | 19.23%  |
| Intel Core i7        | 15        | 19.23%  |
| Intel Core i3        | 7         | 8.97%   |
| AMD Ryzen 5          | 6         | 7.69%   |
| Intel Pentium        | 3         | 3.85%   |
| AMD Ryzen 7          | 3         | 3.85%   |
| Intel Core 2 Duo     | 2         | 2.56%   |
| Intel Celeron        | 2         | 2.56%   |
| Intel Pentium Silver | 1         | 1.28%   |
| Intel Core M         | 1         | 1.28%   |
| Intel Core 2         | 1         | 1.28%   |
| Intel Atom           | 1         | 1.28%   |
| AMD Ryzen 9          | 1         | 1.28%   |
| AMD E1               | 1         | 1.28%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 34        | 43.59%  |
| 4      | 23        | 29.49%  |
| 8      | 10        | 12.82%  |
| 6      | 4         | 5.13%   |
| 14     | 3         | 3.85%   |
| 10     | 2         | 2.56%   |
| 1      | 2         | 2.56%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 78        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 66        | 84.62%  |
| 1      | 12        | 15.38%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 75        | 96.15%  |
| Unknown        | 2         | 2.56%   |
| 32-bit         | 1         | 1.28%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 18        | 22.78%  |
| 0x306a9    | 6         | 7.59%   |
| 0x906a3    | 4         | 5.06%   |
| 0x806d1    | 4         | 5.06%   |
| 0x406e3    | 4         | 5.06%   |
| 0x306d4    | 4         | 5.06%   |
| 0x806ec    | 3         | 3.8%    |
| 0x806ea    | 3         | 3.8%    |
| 0x806c1    | 3         | 3.8%    |
| 0x20655    | 3         | 3.8%    |
| 0x306c3    | 2         | 2.53%   |
| 0x206a7    | 2         | 2.53%   |
| 0x08600106 | 2         | 2.53%   |
| 0x08108109 | 2         | 2.53%   |
| 0xa0671    | 1         | 1.27%   |
| 0xa0660    | 1         | 1.27%   |
| 0xa0652    | 1         | 1.27%   |
| 0x906ea    | 1         | 1.27%   |
| 0x906c0    | 1         | 1.27%   |
| 0x906a4    | 1         | 1.27%   |
| 0x806e9    | 1         | 1.27%   |
| 0x706a1    | 1         | 1.27%   |
| 0x6fd      | 1         | 1.27%   |
| 0x506e3    | 1         | 1.27%   |
| 0x406c4    | 1         | 1.27%   |
| 0x40651    | 1         | 1.27%   |
| 0x106c2    | 1         | 1.27%   |
| 0x1067a    | 1         | 1.27%   |
| 0x10661    | 1         | 1.27%   |
| 0x08900201 | 1         | 1.27%   |
| 0x08608102 | 1         | 1.27%   |
| 0x0810100b | 1         | 1.27%   |
| 0x07000106 | 1         | 1.27%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 13        | 16.46%  |
| Skylake          | 7         | 8.86%   |
| IvyBridge        | 6         | 7.59%   |
| Westmere         | 5         | 6.33%   |
| Icelake          | 5         | 6.33%   |
| Haswell          | 5         | 6.33%   |
| Alderlake Hybrid | 5         | 6.33%   |
| Broadwell        | 4         | 5.06%   |
| Zen 2            | 3         | 3.8%    |
| Zen              | 3         | 3.8%    |
| TigerLake        | 3         | 3.8%    |
| Core             | 3         | 3.8%    |
| Unknown          | 3         | 3.8%    |
| Zen+             | 2         | 2.53%   |
| Silvermont       | 2         | 2.53%   |
| SandyBridge      | 2         | 2.53%   |
| CometLake        | 2         | 2.53%   |
| Zen 3            | 1         | 1.27%   |
| Tremont          | 1         | 1.27%   |
| Penryn           | 1         | 1.27%   |
| Jaguar           | 1         | 1.27%   |
| Goldmont plus    | 1         | 1.27%   |
| Bonnell          | 1         | 1.27%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 57        | 59.38%  |
| Nvidia | 23        | 23.96%  |
| AMD    | 16        | 16.67%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Skylake GT2 [HD Graphics 520]                                                      | 6         | 6.06%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 4         | 4.04%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 4.04%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 3         | 3.03%   |
| Intel UHD Graphics 620                                                                   | 3         | 3.03%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 3.03%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 3.03%   |
| Intel HD Graphics 5500                                                                   | 3         | 3.03%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 3.03%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 3         | 3.03%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 3.03%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 3.03%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 3         | 3.03%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 3.03%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 2.02%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 2.02%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 2.02%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 2.02%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 2.02%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 2.02%   |
| Intel HD Graphics 620                                                                    | 2         | 2.02%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 2.02%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 2.02%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 2.02%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 2         | 2.02%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 2.02%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 1.01%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 1         | 1.01%   |
| Nvidia TU106BM [GeForce RTX 2070 Mobile / Max-Q]                                         | 1         | 1.01%   |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 1.01%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 1.01%   |
| Nvidia GM204GLM [Quadro M3000M]                                                          | 1         | 1.01%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 1.01%   |
| Nvidia GK107M [GeForce GT 745M]                                                          | 1         | 1.01%   |
| Nvidia GF106GLM [Quadro 2000M]                                                           | 1         | 1.01%   |
| Nvidia GA107M [GeForce RTX 2050]                                                         | 1         | 1.01%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 1         | 1.01%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 1.01%   |
| Intel JasperLake [UHD Graphics]                                                          | 1         | 1.01%   |
| Intel HD Graphics 630                                                                    | 1         | 1.01%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 42        | 53.85%  |
| Intel + Nvidia | 14        | 17.95%  |
| 1 x AMD        | 14        | 17.95%  |
| 1 x Nvidia     | 6         | 7.69%   |
| AMD + Nvidia   | 2         | 2.56%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 70        | 88.61%  |
| Proprietary | 8         | 10.13%  |
| Unknown     | 1         | 1.27%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 51        | 63.75%  |
| 1.01-2.0   | 7         | 8.75%   |
| 0.01-0.5   | 7         | 8.75%   |
| 0.51-1.0   | 6         | 7.5%    |
| 7.01-8.0   | 4         | 5%      |
| 3.01-4.0   | 3         | 3.75%   |
| 5.01-6.0   | 2         | 2.5%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| BOE                 | 16        | 18.6%   |
| Chimei Innolux      | 15        | 17.44%  |
| AU Optronics        | 14        | 16.28%  |
| LG Display          | 13        | 15.12%  |
| Samsung Electronics | 7         | 8.14%   |
| Sharp               | 4         | 4.65%   |
| Lenovo              | 3         | 3.49%   |
| Hewlett-Packard     | 3         | 3.49%   |
| Goldstar            | 3         | 3.49%   |
| Valve               | 1         | 1.16%   |
| Sony                | 1         | 1.16%   |
| PANDA               | 1         | 1.16%   |
| Panasonic           | 1         | 1.16%   |
| Hyundai ImageQuest  | 1         | 1.16%   |
| HKC                 | 1         | 1.16%   |
| Dell                | 1         | 1.16%   |
| AOC                 | 1         | 1.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 3         | 3.49%   |
| Samsung Electronics LCD Monitor SDC416E 2880x1620 344x194mm 15.5-inch | 2         | 2.33%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 2         | 2.33%   |
| LG Display LCD Monitor LGD0353 1366x768 345x194mm 15.6-inch           | 2         | 2.33%   |
| Lenovo LCD Monitor LEN4035 1280x800 303x189mm 14.1-inch               | 2         | 2.33%   |
| Goldstar ULTRAGEAR GSM7765 2560x1440 697x392mm 31.5-inch              | 2         | 2.33%   |
| Chimei Innolux LCD Monitor CMN14FF 1920x1080 309x173mm 13.9-inch      | 2         | 2.33%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch         | 2         | 2.33%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 1         | 1.16%   |
| Sony TV SNY8102 1360x768                                              | 1         | 1.16%   |
| Sharp LQ173M1JW05 SHP14EC 1920x1080 382x215mm 17.3-inch               | 1         | 1.16%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 1         | 1.16%   |
| Sharp LQ125T1JW02 SHP142F 2560x1440 277x155mm 12.5-inch               | 1         | 1.16%   |
| Sharp LCD Monitor SHP14C4 1920x1080 344x194mm 15.5-inch               | 1         | 1.16%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch     | 1         | 1.16%   |
| Samsung Electronics SyncMaster SAM0428 1680x1050 459x296mm 21.5-inch  | 1         | 1.16%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch  | 1         | 1.16%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch  | 1         | 1.16%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch  | 1         | 1.16%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch               | 1         | 1.16%   |
| Panasonic LCD Monitor MEI96A2 2880x1620 344x193mm 15.5-inch           | 1         | 1.16%   |
| LG Display LCD Monitor LGD0625 1920x1080 340x190mm 15.3-inch          | 1         | 1.16%   |
| LG Display LCD Monitor LGD0599 1920x1080 309x174mm 14.0-inch          | 1         | 1.16%   |
| LG Display LCD Monitor LGD0508 1366x768 309x174mm 14.0-inch           | 1         | 1.16%   |
| LG Display LCD Monitor LGD03D7 1366x768 310x174mm 14.0-inch           | 1         | 1.16%   |
| LG Display LCD Monitor LGD032C 1920x1080 344x194mm 15.5-inch          | 1         | 1.16%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch           | 1         | 1.16%   |
| LG Display LCD Monitor LGD02D9 1920x1080 344x194mm 15.5-inch          | 1         | 1.16%   |
| LG Display LCD Monitor LGD028A 1366x768 344x194mm 15.5-inch           | 1         | 1.16%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch           | 1         | 1.16%   |
| Lenovo LCD Monitor LEN4031 1280x800 304x190mm 14.1-inch               | 1         | 1.16%   |
| Hyundai ImageQuest B70A HIQ5004 1280x1024 337x270mm 17.0-inch         | 1         | 1.16%   |
| HKC LCD Monitor HKC36B1 1366x768 309x174mm 14.0-inch                  | 1         | 1.16%   |
| Hewlett-Packard P223 HPN3392 1920x1080 477x268mm 21.5-inch            | 1         | 1.16%   |
| Hewlett-Packard 27m HPN3579 1920x1080 598x336mm 27.0-inch             | 1         | 1.16%   |
| Hewlett-Packard 22fw HPN3541 1920x1080 476x268mm 21.5-inch            | 1         | 1.16%   |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                   | 1         | 1.16%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                      | 1         | 1.16%   |
| Chimei Innolux LCD Monitor CMN1774 1920x1080 381x214mm 17.2-inch      | 1         | 1.16%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 381x214mm 17.2-inch      | 1         | 1.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 37        | 44.05%  |
| 1366x768 (WXGA)    | 23        | 27.38%  |
| 3840x2160 (4K)     | 5         | 5.95%   |
| 1600x900 (HD+)     | 4         | 4.76%   |
| 1280x800 (WXGA)    | 4         | 4.76%   |
| 2560x1440 (QHD)    | 3         | 3.57%   |
| 2880x1620          | 2         | 2.38%   |
| 800x1280           | 1         | 1.19%   |
| 2256x1504          | 1         | 1.19%   |
| 1920x1200 (WUXGA)  | 1         | 1.19%   |
| 1680x1050 (WSXGA+) | 1         | 1.19%   |
| 1360x768           | 1         | 1.19%   |
| 1280x1024 (SXGA)   | 1         | 1.19%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 33        | 38.37%  |
| 14     | 14        | 16.28%  |
| 13     | 12        | 13.95%  |
| 17     | 8         | 9.3%    |
| 31     | 3         | 3.49%   |
| 16     | 3         | 3.49%   |
| 12     | 3         | 3.49%   |
| 27     | 2         | 2.33%   |
| 21     | 2         | 2.33%   |
| 72     | 1         | 1.16%   |
| 24     | 1         | 1.16%   |
| 23     | 1         | 1.16%   |
| 20     | 1         | 1.16%   |
| 11     | 1         | 1.16%   |
| 7      | 1         | 1.16%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 58        | 67.44%  |
| 351-400     | 10        | 11.63%  |
| 201-300     | 6         | 6.98%   |
| 401-500     | 4         | 4.65%   |
| 601-700     | 3         | 3.49%   |
| 501-600     | 3         | 3.49%   |
| 1501-2000   | 1         | 1.16%   |
| 1-100       | 1         | 1.16%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 68        | 87.18%  |
| 16/10 | 6         | 7.69%   |
| 3/2   | 2         | 2.56%   |
| 5/4   | 1         | 1.28%   |
| 0.67  | 1         | 1.28%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 35        | 40.7%   |
| 81-90          | 25        | 29.07%  |
| 121-130        | 7         | 8.14%   |
| 61-70          | 3         | 3.49%   |
| 351-500        | 3         | 3.49%   |
| 301-350        | 2         | 2.33%   |
| 201-250        | 2         | 2.33%   |
| 151-200        | 2         | 2.33%   |
| More than 1000 | 1         | 1.16%   |
| 71-80          | 1         | 1.16%   |
| 51-60          | 1         | 1.16%   |
| 1-40           | 1         | 1.16%   |
| 251-300        | 1         | 1.16%   |
| 141-150        | 1         | 1.16%   |
| 111-120        | 1         | 1.16%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 40        | 48.19%  |
| 101-120       | 22        | 26.51%  |
| 51-100        | 12        | 14.46%  |
| 161-240       | 5         | 6.02%   |
| More than 240 | 3         | 3.61%   |
| 1-50          | 1         | 1.2%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 68        | 87.18%  |
| 2     | 10        | 12.82%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 53        | 42.4%   |
| Realtek Semiconductor | 39        | 31.2%   |
| Qualcomm Atheros      | 11        | 8.8%    |
| ASIX Electronics      | 5         | 4%      |
| Broadcom Limited      | 4         | 3.2%    |
| MediaTek              | 3         | 2.4%    |
| Broadcom              | 3         | 2.4%    |
| Ralink Technology     | 2         | 1.6%    |
| Sitecom Europe        | 1         | 0.8%    |
| Sierra Wireless       | 1         | 0.8%    |
| Huawei Technologies   | 1         | 0.8%    |
| Hewlett-Packard       | 1         | 0.8%    |
| Dell                  | 1         | 0.8%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 24        | 15.48%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 4.52%   |
| Intel Wireless 8265 / 8275                                        | 6         | 3.87%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 2.58%   |
| Intel Wireless 8260                                               | 4         | 2.58%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 4         | 2.58%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 2.58%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 1.94%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 1.94%   |
| Intel Wireless 7265                                               | 3         | 1.94%   |
| Intel Wireless 7260                                               | 3         | 1.94%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 1.94%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.94%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 1.94%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 1.94%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 1.29%   |
| Ralink MT7601U Wireless Adapter                                   | 2         | 1.29%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 1.29%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 2         | 1.29%   |
| Intel Wireless-AC 9260                                            | 2         | 1.29%   |
| Intel Wireless 3160                                               | 2         | 1.29%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 1.29%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 1.29%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.29%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 1.29%   |
| Intel Centrino Ultimate-N 6300                                    | 2         | 1.29%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 1.29%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 2         | 1.29%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.29%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                           | 2         | 1.29%   |
| Sitecom Europe WL-113 rev 2 Wireless Network USB Adapter          | 1         | 0.65%   |
| Sierra Wireless EM7305                                            | 1         | 0.65%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 0.65%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1         | 0.65%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 0.65%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 0.65%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1         | 0.65%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.65%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 0.65%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.65%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 49        | 59.76%  |
| Realtek Semiconductor | 13        | 15.85%  |
| Qualcomm Atheros      | 8         | 9.76%   |
| MediaTek              | 3         | 3.66%   |
| Broadcom Limited      | 3         | 3.66%   |
| Ralink Technology     | 2         | 2.44%   |
| Sitecom Europe        | 1         | 1.22%   |
| Sierra Wireless       | 1         | 1.22%   |
| Dell                  | 1         | 1.22%   |
| Broadcom              | 1         | 1.22%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                                            | 6         | 7.23%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 4         | 4.82%   |
| Intel Wireless 8260                                                                   | 4         | 4.82%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 4         | 4.82%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 3         | 3.61%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 3         | 3.61%   |
| Intel Wireless 7265                                                                   | 3         | 3.61%   |
| Intel Wireless 7260                                                                   | 3         | 3.61%   |
| Intel Wi-Fi 6 AX200                                                                   | 3         | 3.61%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 3         | 3.61%   |
| Ralink MT7601U Wireless Adapter                                                       | 2         | 2.41%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                         | 2         | 2.41%   |
| Intel Wireless-AC 9260                                                                | 2         | 2.41%   |
| Intel Wireless 3160                                                                   | 2         | 2.41%   |
| Intel Wi-Fi 6 AX201                                                                   | 2         | 2.41%   |
| Intel Tiger Lake PCH CNVi WiFi                                                        | 2         | 2.41%   |
| Intel Centrino Ultimate-N 6300                                                        | 2         | 2.41%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 2         | 2.41%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                      | 2         | 2.41%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                                               | 2         | 2.41%   |
| Sitecom Europe WL-113 rev 2 Wireless Network USB Adapter                              | 1         | 1.2%    |
| Sierra Wireless EM7305                                                                | 1         | 1.2%    |
| Realtek RTL8723DE Wireless Network Adapter                                            | 1         | 1.2%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                       | 1         | 1.2%    |
| Realtek RTL8191SEvB Wireless LAN Controller                                           | 1         | 1.2%    |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 1.2%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                               | 1         | 1.2%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 1         | 1.2%    |
| Realtek Realtek WLAN controller                                                       | 1         | 1.2%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 1         | 1.2%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                      | 1         | 1.2%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 1         | 1.2%    |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 1.2%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 1         | 1.2%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 1         | 1.2%    |
| Intel Wireless 3165                                                                   | 1         | 1.2%    |
| Intel WiFi Link 5100                                                                  | 1         | 1.2%    |
| Intel Wi-Fi 6 AX201 160MHz                                                            | 1         | 1.2%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                         | 1         | 1.2%    |
| Intel Gemini Lake PCH CNVi WiFi                                                       | 1         | 1.2%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 34        | 48.57%  |
| Intel                 | 22        | 31.43%  |
| Qualcomm Atheros      | 5         | 7.14%   |
| ASIX Electronics      | 5         | 7.14%   |
| Broadcom              | 2         | 2.86%   |
| Huawei Technologies   | 1         | 1.43%   |
| Broadcom Limited      | 1         | 1.43%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 24        | 33.8%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 9.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 5.63%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 4.23%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 4.23%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 2.82%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 2.82%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 2.82%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 2.82%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 2.82%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.41%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.41%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.41%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.41%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 1.41%   |
| Intel Ethernet Connection I218-V                                  | 1         | 1.41%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.41%   |
| Intel Ethernet Connection (5) I219-V                              | 1         | 1.41%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.41%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.41%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 1.41%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.41%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.41%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 1.41%   |
| Huawei E353/E3131                                                 | 1         | 1.41%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.41%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 1.41%   |
| Broadcom Limited NetXtreme BCM5756ME Gigabit Ethernet PCI Express | 1         | 1.41%   |
| ASIX AX88772B                                                     | 1         | 1.41%   |
| ASIX AX88772A Fast Ethernet                                       | 1         | 1.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 78        | 53.06%  |
| Ethernet | 68        | 46.26%  |
| Modem    | 1         | 0.68%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 60        | 73.17%  |
| Ethernet | 22        | 26.83%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 61        | 78.21%  |
| 1     | 15        | 19.23%  |
| 0     | 2         | 2.56%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 69        | 88.46%  |
| Yes  | 9         | 11.54%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 43        | 64.18%  |
| Realtek Semiconductor           | 8         | 11.94%  |
| Broadcom                        | 5         | 7.46%   |
| Qualcomm Atheros Communications | 4         | 5.97%   |
| IMC Networks                    | 4         | 5.97%   |
| Toshiba                         | 1         | 1.49%   |
| Foxconn / Hon Hai               | 1         | 1.49%   |
| Cambridge Silicon Radio         | 1         | 1.49%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 20        | 29.85%  |
| Intel AX201 Bluetooth                               | 8         | 11.94%  |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 5.97%   |
| Realtek Bluetooth Radio                             | 4         | 5.97%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 5.97%   |
| Intel AX210 Bluetooth                               | 4         | 5.97%   |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 4.48%   |
| Intel AX200 Bluetooth                               | 3         | 4.48%   |
| IMC Networks Wireless_Device                        | 3         | 4.48%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 2.99%   |
| Toshiba Askey Bluetooth Module                      | 1         | 1.49%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 1.49%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.49%   |
| Intel Bluetooth Device                              | 1         | 1.49%   |
| IMC Networks Bluetooth Radio                        | 1         | 1.49%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 1.49%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 1.49%   |
| Broadcom HP Portable SoftSailing                    | 1         | 1.49%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 1.49%   |
| Broadcom BCM20702A0                                 | 1         | 1.49%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.49%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 1         | 1.49%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 66        | 64.71%  |
| Nvidia              | 18        | 17.65%  |
| AMD                 | 15        | 14.71%  |
| Texas Instruments   | 1         | 0.98%   |
| C-Media Electronics | 1         | 0.98%   |
| ASUSTek Computer    | 1         | 0.98%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 11        | 9.09%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 10        | 8.26%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6         | 4.96%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 5         | 4.13%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 4.13%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 5         | 4.13%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 4.13%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5         | 4.13%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 4         | 3.31%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 3.31%   |
| Intel Broadwell-U Audio Controller                                                                | 4         | 3.31%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 3.31%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 2.48%   |
| Nvidia Audio device                                                                               | 3         | 2.48%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 2.48%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 2.48%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 2.48%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 1.65%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 1.65%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 2         | 1.65%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 1.65%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 1.65%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.65%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 1.65%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 1.65%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 1.65%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 1.65%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 1.65%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.83%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1         | 0.83%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 0.83%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 0.83%   |
| Intel Jasper Lake HD Audio                                                                        | 1         | 0.83%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.83%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.83%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 0.83%   |
| Intel 200 Series PCH HD Audio                                                                     | 1         | 0.83%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 0.83%   |
| C-Media Electronics CM6631A Audio Processor                                                       | 1         | 0.83%   |
| ASUSTek Computer C-Media Audio                                                                    | 1         | 0.83%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 21        | 27.63%  |
| Samsung Electronics | 21        | 27.63%  |
| Kingston            | 9         | 11.84%  |
| Micron Technology   | 7         | 9.21%   |
| Crucial             | 4         | 5.26%   |
| Corsair             | 3         | 3.95%   |
| Unknown             | 2         | 2.63%   |
| Ramaxel Technology  | 2         | 2.63%   |
| Smart               | 1         | 1.32%   |
| Neo Forza           | 1         | 1.32%   |
| Nanya Technology    | 1         | 1.32%   |
| Innodisk            | 1         | 1.32%   |
| Essencore Limited   | 1         | 1.32%   |
| Elpida              | 1         | 1.32%   |
| A-DATA Technology   | 1         | 1.32%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 3.7%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 2         | 2.47%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 2.47%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 4GB Row Of Chips LPDDR5 6400MT/s | 2         | 2.47%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 2.47%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 2.47%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 2         | 2.47%   |
| Corsair RAM CMSX32GX4M2A2666C18 16GB SODIMM DDR4 2667MT/s        | 2         | 2.47%   |
| Unknown RAM Module 1024MB SODIMM SDRAM                           | 1         | 1.23%   |
| Unknown RAM Module 1024MB SODIMM DDR2 533MT/s                    | 1         | 1.23%   |
| Smart RAM SH5641G8FJ8NWRNSQG 8GB SODIMM DDR3 1600MT/s            | 1         | 1.23%   |
| SK hynix RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s          | 1         | 1.23%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                  | 1         | 1.23%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR 975MT/s          | 1         | 1.23%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.23%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.23%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 1         | 1.23%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.23%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.23%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 1.23%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.23%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 1         | 1.23%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 1         | 1.23%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s           | 1         | 1.23%   |
| SK hynix RAM H9CCNNNCLGALAR-NUD 8GB Row Of Chips LPDDR3 1867MT/s | 1         | 1.23%   |
| SK hynix RAM H9CCNNNBJTMLAR 4GB SODIMM LPDDR3 1867MT/s           | 1         | 1.23%   |
| SK hynix RAM H9CCNNNBJTMLAR 4GB Chip LPDDR3 1867MT/s             | 1         | 1.23%   |
| SK hynix RAM 746448-381 4096MB SODIMM LPDDR3 1600MT/s            | 1         | 1.23%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s            | 1         | 1.23%   |
| Samsung RAM M471B5773DH0-CH9 2048MB SODIMM DDR3 1600MT/s         | 1         | 1.23%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM 4199MT/s                 | 1         | 1.23%   |
| Samsung RAM M471B5273DH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.23%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.23%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.23%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.23%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.23%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 1         | 1.23%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 1.23%   |
| Samsung RAM M471A5244BB0-CPB 4GB SODIMM DDR4 2400MT/s            | 1         | 1.23%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 1         | 1.23%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 31        | 46.97%  |
| DDR3   | 19        | 28.79%  |
| LPDDR3 | 4         | 6.06%   |
| LPDDR5 | 3         | 4.55%   |
| LPDDR4 | 3         | 4.55%   |
| SDRAM  | 2         | 3.03%   |
| DDR5   | 2         | 3.03%   |
| DDR2   | 2         | 3.03%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 60        | 89.55%  |
| Row Of Chips | 6         | 8.96%   |
| Chip         | 1         | 1.49%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 34        | 45.95%  |
| 4096  | 24        | 32.43%  |
| 16384 | 8         | 10.81%  |
| 2048  | 4         | 5.41%   |
| 32768 | 2         | 2.7%    |
| 1024  | 2         | 2.7%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 18        | 25.35%  |
| 3200    | 15        | 21.13%  |
| 2667    | 14        | 19.72%  |
| 2400    | 4         | 5.63%   |
| 2133    | 3         | 4.23%   |
| 1334    | 3         | 4.23%   |
| 6400    | 2         | 2.82%   |
| 4800    | 2         | 2.82%   |
| 1867    | 2         | 2.82%   |
| 4267    | 1         | 1.41%   |
| 4266    | 1         | 1.41%   |
| 4199    | 1         | 1.41%   |
| 1333    | 1         | 1.41%   |
| 975     | 1         | 1.41%   |
| 701     | 1         | 1.41%   |
| 533     | 1         | 1.41%   |
| Unknown | 1         | 1.41%   |

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
| Chicony Electronics                    | 23        | 32.39%  |
| Bison Electronics                      | 8         | 11.27%  |
| Realtek Semiconductor                  | 6         | 8.45%   |
| Microdia                               | 4         | 5.63%   |
| IMC Networks                           | 4         | 5.63%   |
| Syntek                                 | 3         | 4.23%   |
| Sunplus Innovation Technology          | 3         | 4.23%   |
| Sonix Technology                       | 3         | 4.23%   |
| Quanta                                 | 3         | 4.23%   |
| Luxvisions Innotech Limited            | 3         | 4.23%   |
| Lite-On Technology                     | 3         | 4.23%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 4.23%   |
| Silicon Motion                         | 1         | 1.41%   |
| Samsung Electronics                    | 1         | 1.41%   |
| Motorola PCS                           | 1         | 1.41%   |
| Logitech                               | 1         | 1.41%   |
| Lenovo                                 | 1         | 1.41%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 5         | 7.04%   |
| Bison HD Webcam                                      | 3         | 4.23%   |
| Bison BisonCam,NB Pro                                | 3         | 4.23%   |
| Syntek Integrated Camera                             | 2         | 2.82%   |
| Sunplus Integrated_Webcam_HD                         | 2         | 2.82%   |
| Sonix USB2.0 FHD UVC WebCam                          | 2         | 2.82%   |
| Quanta HP Webcam                                     | 2         | 2.82%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 2         | 2.82%   |
| Chicony Integrated Camera (1280x720@30)              | 2         | 2.82%   |
| Chicony HD User Facing                               | 2         | 2.82%   |
| Chicony FJ Camera                                    | 2         | 2.82%   |
| Syntek USB2.0 Camera                                 | 1         | 1.41%   |
| Sunplus Laptop_Integrated_Webcam_FHD                 | 1         | 1.41%   |
| Sonix USB2.0 HD UVC WebCam                           | 1         | 1.41%   |
| Silicon Motion Web Camera                            | 1         | 1.41%   |
| Samsung Galaxy series, misc. (MTP mode)              | 1         | 1.41%   |
| Realtek USB2.0-Camera                                | 1         | 1.41%   |
| Realtek USB Camera                                   | 1         | 1.41%   |
| Realtek Laptop Camera                                | 1         | 1.41%   |
| Realtek Integrated Camera                            | 1         | 1.41%   |
| Realtek EasyCamera                                   | 1         | 1.41%   |
| Realtek Bluetooth Radio                              | 1         | 1.41%   |
| Quanta HP Wide Vision HD Camera                      | 1         | 1.41%   |
| Motorola PCS XT1033 [Moto G], PTP mode               | 1         | 1.41%   |
| Microdia Laptop_Integrated_Webcam_2M                 | 1         | 1.41%   |
| Microdia Integrated_Webcam_HD                        | 1         | 1.41%   |
| Microdia Integrated Webcam                           | 1         | 1.41%   |
| Microdia Dell Integrated HD Webcam                   | 1         | 1.41%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 1.41%   |
| Logitech C920 PRO HD Webcam                          | 1         | 1.41%   |
| Lite-On TOSHIBA Web Camera - FHD                     | 1         | 1.41%   |
| Lite-On Integrated Camera                            | 1         | 1.41%   |
| Lite-On HP TrueVision HD Camera                      | 1         | 1.41%   |
| Lenovo Integrated Webcam [R5U877]                    | 1         | 1.41%   |
| IMC Networks UVC VGA Webcam                          | 1         | 1.41%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 1         | 1.41%   |
| IMC Networks Lenovo EasyCamera                       | 1         | 1.41%   |
| IMC Networks Integrated Camera                       | 1         | 1.41%   |
| Chicony Web Camera - FHD                             | 1         | 1.41%   |
| Chicony TOSHIBA Web Camera - HD                      | 1         | 1.41%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 10        | 47.62%  |
| Synaptics                          | 4         | 19.05%  |
| Realtek USB2.0 Finger Print Bridge | 2         | 9.52%   |
| Elan Microelectronics              | 2         | 9.52%   |
| STMicroelectronics                 | 1         | 4.76%   |
| Shenzhen Goodix Technology         | 1         | 4.76%   |
| LighTuning Technology              | 1         | 4.76%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI                                 | 3         | 14.29%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor               | 2         | 9.52%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 2         | 9.52%   |
| Validity Sensors VFS495 Fingerprint Reader                      | 1         | 4.76%   |
| Validity Sensors VFS451 Fingerprint Reader                      | 1         | 4.76%   |
| Validity Sensors VFS300 Fingerprint Reader                      | 1         | 4.76%   |
| Validity Sensors VFS Fingerprint sensor                         | 1         | 4.76%   |
| Validity Sensors VFS 5011 fingerprint sensor                    | 1         | 4.76%   |
| Synaptics WBDI Device                                           | 1         | 4.76%   |
| Synaptics TouchPad                                              | 1         | 4.76%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 1         | 4.76%   |
| STMicroelectronics Fingerprint Reader                           | 1         | 4.76%   |
| Shenzhen Goodix  FingerPrint Device                             | 1         | 4.76%   |
| LighTuning EgisTec Touch Fingerprint Sensor                     | 1         | 4.76%   |
| Elan ELAN:Fingerprint                                           | 1         | 4.76%   |
| Elan ELAN:ARM-M4                                                | 1         | 4.76%   |
| Unknown                                                         | 1         | 4.76%   |

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
| 0     | 43        | 53.09%  |
| 1     | 25        | 30.86%  |
| 2     | 10        | 12.35%  |
| 3     | 3         | 3.7%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 20        | 37.04%  |
| Graphics card            | 9         | 16.67%  |
| Chipcard                 | 8         | 14.81%  |
| Net/wireless             | 4         | 7.41%   |
| Multimedia controller    | 3         | 5.56%   |
| Card reader              | 3         | 5.56%   |
| Camera                   | 2         | 3.7%    |
| Storage                  | 1         | 1.85%   |
| Net/ethernet             | 1         | 1.85%   |
| Firewire controller      | 1         | 1.85%   |
| Communication controller | 1         | 1.85%   |
| Bluetooth                | 1         | 1.85%   |

