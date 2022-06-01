Slackware - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Slackware.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Slackware/Desktop/README.md) and [notebooks](/Dist/Slackware/Notebook/README.md).

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

Total: 138

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Gigabyte      | N3160TN                     | Desktop     | [e2f44a8274](https://linux-hardware.org/?probe=e2f44a8274) | May 31, 2022 |
| Sony          | SVE1713A1EW                 | Notebook    | [c3a65d695d](https://linux-hardware.org/?probe=c3a65d695d) | May 10, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [f837aaeb12](https://linux-hardware.org/?probe=f837aaeb12) | May 08, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [bd2dda1d8a](https://linux-hardware.org/?probe=bd2dda1d8a) | Apr 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [cfc9c5dbf7](https://linux-hardware.org/?probe=cfc9c5dbf7) | Apr 29, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [533b8a9f83](https://linux-hardware.org/?probe=533b8a9f83) | Apr 13, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [25d8968f19](https://linux-hardware.org/?probe=25d8968f19) | Apr 13, 2022 |
| MSI           | GP76 Leopard 11UG           | Notebook    | [aebd373a66](https://linux-hardware.org/?probe=aebd373a66) | Apr 12, 2022 |
| MSI           | GE76 Raider 11UE            | Notebook    | [3072e065a3](https://linux-hardware.org/?probe=3072e065a3) | Apr 12, 2022 |
| Notebook      | X170KM-G                    | Notebook    | [4ecba03d19](https://linux-hardware.org/?probe=4ecba03d19) | Apr 11, 2022 |
| ASRock        | N68-S3 FX                   | Desktop     | [ca818bd06d](https://linux-hardware.org/?probe=ca818bd06d) | Apr 08, 2022 |
| MSI           | MS-7365                     | Desktop     | [8948dea4de](https://linux-hardware.org/?probe=8948dea4de) | Apr 07, 2022 |
| Unknown       | X79-P3                      | Desktop     | [40e38e9a8d](https://linux-hardware.org/?probe=40e38e9a8d) | Apr 07, 2022 |
| Dell          | Latitude 3520               | Notebook    | [4398aa2a03](https://linux-hardware.org/?probe=4398aa2a03) | Apr 06, 2022 |
| HP            | ProBook 6570b               | Notebook    | [cf1305eacc](https://linux-hardware.org/?probe=cf1305eacc) | Apr 06, 2022 |
| HP            | 0A08h                       | Desktop     | [4df5b0832f](https://linux-hardware.org/?probe=4df5b0832f) | Apr 06, 2022 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [d406cb4819](https://linux-hardware.org/?probe=d406cb4819) | Apr 05, 2022 |
| Dell          | Precision M4700             | Notebook    | [ab99532bd5](https://linux-hardware.org/?probe=ab99532bd5) | Apr 04, 2022 |
| ASRock        | H410M-ITX/ac                | Desktop     | [ae936790c9](https://linux-hardware.org/?probe=ae936790c9) | Apr 03, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [5307aba2c3](https://linux-hardware.org/?probe=5307aba2c3) | Mar 30, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [c8289cd264](https://linux-hardware.org/?probe=c8289cd264) | Mar 26, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [5c6b1616fa](https://linux-hardware.org/?probe=5c6b1616fa) | Mar 21, 2022 |
| Acer          | FMCP7A-ION-LE               | Desktop     | [bbce73c6d6](https://linux-hardware.org/?probe=bbce73c6d6) | Mar 14, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [5f36bc3969](https://linux-hardware.org/?probe=5f36bc3969) | Mar 12, 2022 |
| ASRock        | H270 Pro4                   | Desktop     | [ae79ca8557](https://linux-hardware.org/?probe=ae79ca8557) | Mar 12, 2022 |
| HP            | 86F3 00100                  | All in one  | [7de0381db8](https://linux-hardware.org/?probe=7de0381db8) | Mar 11, 2022 |
| Lenovo        | ThinkPad X230 2325P38       | Notebook    | [1a0cab737b](https://linux-hardware.org/?probe=1a0cab737b) | Mar 10, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [0b0c1aca1b](https://linux-hardware.org/?probe=0b0c1aca1b) | Mar 10, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c7825c54fc](https://linux-hardware.org/?probe=c7825c54fc) | Mar 10, 2022 |
| Framework     | Laptop                      | Notebook    | [ae37705198](https://linux-hardware.org/?probe=ae37705198) | Mar 10, 2022 |
| Dell          | 068NXX A00                  | Server      | [85004f427a](https://linux-hardware.org/?probe=85004f427a) | Mar 09, 2022 |
| Lenovo        | 31900058 STD                | Desktop     | [bc59b862f4](https://linux-hardware.org/?probe=bc59b862f4) | Mar 02, 2022 |
| TYAN Compu... | S7012                       | Server      | [fec98b51da](https://linux-hardware.org/?probe=fec98b51da) | Feb 27, 2022 |
| TYAN Compu... | S7012                       | Server      | [81a490184b](https://linux-hardware.org/?probe=81a490184b) | Feb 26, 2022 |
| Biostar       | X470GTA                     | Desktop     | [8d400b49f8](https://linux-hardware.org/?probe=8d400b49f8) | Feb 13, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | Notebook    | [8ce0419468](https://linux-hardware.org/?probe=8ce0419468) | Feb 13, 2022 |
| MSI           | G31TM-P21                   | Desktop     | [dda6a57223](https://linux-hardware.org/?probe=dda6a57223) | Feb 07, 2022 |
| HP            | 212B                        | Desktop     | [353b0dde99](https://linux-hardware.org/?probe=353b0dde99) | Jan 29, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [85543358d3](https://linux-hardware.org/?probe=85543358d3) | Jan 14, 2022 |
| Dynabook      | P1-C7MP-BL                  | Notebook    | [268f94787e](https://linux-hardware.org/?probe=268f94787e) | Jan 14, 2022 |
| MSI           | G31TM-P21                   | Desktop     | [25d668ee95](https://linux-hardware.org/?probe=25d668ee95) | Jan 10, 2022 |
| HP            | Laptop 15-bs2xx             | Notebook    | [bf53c3c878](https://linux-hardware.org/?probe=bf53c3c878) | Jan 02, 2022 |
| MSI           | H61M-P31                    | Desktop     | [58651bba67](https://linux-hardware.org/?probe=58651bba67) | Dec 07, 2021 |
| HP            | Laptop 15-bs1xx             | Notebook    | [b6c9f34c4c](https://linux-hardware.org/?probe=b6c9f34c4c) | Dec 07, 2021 |
| HP            | 21B4 A01                    | Desktop     | [871b196cc2](https://linux-hardware.org/?probe=871b196cc2) | Nov 21, 2021 |
| HP            | 21B4 A01                    | Desktop     | [259232d98b](https://linux-hardware.org/?probe=259232d98b) | Nov 21, 2021 |
| Supermicro    | X9DA7/E                     | Desktop     | [3fc1ef2b58](https://linux-hardware.org/?probe=3fc1ef2b58) | Nov 09, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [2e3e23fb54](https://linux-hardware.org/?probe=2e3e23fb54) | Nov 01, 2021 |
| System76      | Oryx Pro                    | Notebook    | [3cd05d02a8](https://linux-hardware.org/?probe=3cd05d02a8) | Oct 27, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [b7df25ba5d](https://linux-hardware.org/?probe=b7df25ba5d) | Oct 25, 2021 |
| ASUSTek       | SABERTOOTH X99              | Desktop     | [64e5ee1691](https://linux-hardware.org/?probe=64e5ee1691) | Oct 13, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [17d37c5316](https://linux-hardware.org/?probe=17d37c5316) | Oct 12, 2021 |
| MSI           | Modern 14 B11MO             | Notebook    | [e8f13facfd](https://linux-hardware.org/?probe=e8f13facfd) | Oct 03, 2021 |
| MSI           | Modern 14 B11MO             | Notebook    | [9f5c2e0fde](https://linux-hardware.org/?probe=9f5c2e0fde) | Sep 27, 2021 |
| Intel         | DZ77RE-75K AAG39010-302     | Desktop     | [069c508e80](https://linux-hardware.org/?probe=069c508e80) | Sep 25, 2021 |
| Shuttle       | NC03U                       | Desktop     | [c5f76c4400](https://linux-hardware.org/?probe=c5f76c4400) | Sep 22, 2021 |
| Toshiba       | PORTEGE Z30-A               | Notebook    | [13b9ce0773](https://linux-hardware.org/?probe=13b9ce0773) | Sep 22, 2021 |
| Dynabook      | PORTEGE X50-G               | Notebook    | [da8279a7a9](https://linux-hardware.org/?probe=da8279a7a9) | Sep 22, 2021 |
| Dell          | Inspiron 15-3552            | Notebook    | [f76339b0af](https://linux-hardware.org/?probe=f76339b0af) | Aug 31, 2021 |
| HP            | 245 G7 Notebook PC          | Notebook    | [c0806e4955](https://linux-hardware.org/?probe=c0806e4955) | Aug 23, 2021 |
| HP            | 245 G7 Notebook PC          | Notebook    | [c409287d23](https://linux-hardware.org/?probe=c409287d23) | Aug 23, 2021 |
| HP            | EliteBook 840 G5            | Notebook    | [4c196e1abd](https://linux-hardware.org/?probe=4c196e1abd) | Aug 18, 2021 |
| Dell          | Vostro 3500                 | Notebook    | [53a1179121](https://linux-hardware.org/?probe=53a1179121) | Aug 12, 2021 |
| HP            | EliteBook Folio 1020 G1 ... | Notebook    | [32e6ec699f](https://linux-hardware.org/?probe=32e6ec699f) | Aug 09, 2021 |
| HP            | EliteBook Folio 1020 G1 ... | Notebook    | [7facd0568b](https://linux-hardware.org/?probe=7facd0568b) | Aug 09, 2021 |
| ASUSTek       | SABERTOOTH X79              | Desktop     | [5d6732e14c](https://linux-hardware.org/?probe=5d6732e14c) | Aug 09, 2021 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [9ac798b737](https://linux-hardware.org/?probe=9ac798b737) | Aug 05, 2021 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [095745e5fb](https://linux-hardware.org/?probe=095745e5fb) | Jul 06, 2021 |
| HP            | 158A                        | Desktop     | [d612124939](https://linux-hardware.org/?probe=d612124939) | Jun 21, 2021 |
| ASRock        | H310CM-HDV                  | Desktop     | [3291e5d2de](https://linux-hardware.org/?probe=3291e5d2de) | Jun 19, 2021 |
| ASRock        | H87M Pro4                   | Desktop     | [8d4b7f121d](https://linux-hardware.org/?probe=8d4b7f121d) | Jun 02, 2021 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [6e60025ac5](https://linux-hardware.org/?probe=6e60025ac5) | May 25, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [3e5f76719a](https://linux-hardware.org/?probe=3e5f76719a) | May 24, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [c75f9d5c0d](https://linux-hardware.org/?probe=c75f9d5c0d) | May 23, 2021 |
| Dell          | 0PTTT9 A00                  | Desktop     | [e5b81a0da1](https://linux-hardware.org/?probe=e5b81a0da1) | May 20, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [cabba2c402](https://linux-hardware.org/?probe=cabba2c402) | May 19, 2021 |
| Gigabyte      | N3160TN                     | Desktop     | [2fd537312f](https://linux-hardware.org/?probe=2fd537312f) | May 14, 2021 |
| MSI           | G31TM-P21                   | Desktop     | [91c11ae82e](https://linux-hardware.org/?probe=91c11ae82e) | May 07, 2021 |
| HP            | 15 Notebook PC              | Notebook    | [bec2fe2e78](https://linux-hardware.org/?probe=bec2fe2e78) | Mar 21, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [5189fbc4c9](https://linux-hardware.org/?probe=5189fbc4c9) | Mar 10, 2021 |
| Foxconn       | 2ADA                        | Desktop     | [425d15a5ce](https://linux-hardware.org/?probe=425d15a5ce) | Mar 09, 2021 |
| Samsung       | 300E5M/300E5L               | Notebook    | [bda4ee984f](https://linux-hardware.org/?probe=bda4ee984f) | Mar 05, 2021 |
| Dell          | Latitude E5500              | Notebook    | [a8e17b79ce](https://linux-hardware.org/?probe=a8e17b79ce) | Feb 26, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [45dfe3c2b1](https://linux-hardware.org/?probe=45dfe3c2b1) | Feb 24, 2021 |
| Lenovo        | ThinkPad L440 20ASS05K00    | Notebook    | [aecef5c789](https://linux-hardware.org/?probe=aecef5c789) | Jan 22, 2021 |
| Dell          | 0TP412                      | Desktop     | [f0e56aacff](https://linux-hardware.org/?probe=f0e56aacff) | Jan 05, 2021 |
| Lenovo        | ThinkPad L440 20ASS05K00    | Notebook    | [7a6a06bb55](https://linux-hardware.org/?probe=7a6a06bb55) | Jan 04, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [e1424f6de3](https://linux-hardware.org/?probe=e1424f6de3) | Dec 31, 2020 |
| Dell          | Precision M4600             | Notebook    | [71bb8e2e9a](https://linux-hardware.org/?probe=71bb8e2e9a) | Dec 28, 2020 |
| Lenovo        | ThinkPad L440 20ASS05K00    | Notebook    | [b330b2d38a](https://linux-hardware.org/?probe=b330b2d38a) | Nov 19, 2020 |
| NETGEAR       | ReadyDATA 5200              | Desktop     | [96607f4270](https://linux-hardware.org/?probe=96607f4270) | Nov 12, 2020 |
| MSI           | GL73 8RC                    | Notebook    | [44f82bfc01](https://linux-hardware.org/?probe=44f82bfc01) | Nov 09, 2020 |
| Lenovo        | ThinkPad L440 20ASS05K00    | Notebook    | [a4cb1ecf16](https://linux-hardware.org/?probe=a4cb1ecf16) | Nov 08, 2020 |
| HP            | 8523 A01                    | Mini pc     | [bab721d52e](https://linux-hardware.org/?probe=bab721d52e) | Oct 30, 2020 |
| ASRock        | Z390M-ITX/ac                | Desktop     | [06eb8afdbc](https://linux-hardware.org/?probe=06eb8afdbc) | Oct 19, 2020 |
| Samsung       | 300E5M/300E5L               | Notebook    | [270b65ced8](https://linux-hardware.org/?probe=270b65ced8) | Jul 24, 2020 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [d42d44dd82](https://linux-hardware.org/?probe=d42d44dd82) | Jul 23, 2020 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [888f105221](https://linux-hardware.org/?probe=888f105221) | Jul 23, 2020 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [2eb600bb96](https://linux-hardware.org/?probe=2eb600bb96) | Jul 10, 2020 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [232221bf45](https://linux-hardware.org/?probe=232221bf45) | Jul 10, 2020 |
| Notebook      | NL40_50CU                   | Notebook    | [941073da73](https://linux-hardware.org/?probe=941073da73) | Jun 27, 2020 |
| Lenovo        | V330-14ARR 81B1             | Notebook    | [5089cbcf84](https://linux-hardware.org/?probe=5089cbcf84) | Jun 24, 2020 |
| Lenovo        | V330-14ARR 81B1             | Notebook    | [cb63994f94](https://linux-hardware.org/?probe=cb63994f94) | Jun 22, 2020 |
| Notebook      | NL40_50CU                   | Notebook    | [9a1c09c6e1](https://linux-hardware.org/?probe=9a1c09c6e1) | Mar 28, 2020 |
| Notebook      | NL40_50CU                   | Notebook    | [bc5ed8dea4](https://linux-hardware.org/?probe=bc5ed8dea4) | Mar 24, 2020 |
| Notebook      | NL40_50CU                   | Notebook    | [ae7070b067](https://linux-hardware.org/?probe=ae7070b067) | Mar 21, 2020 |
| Notebook      | NL40_50CU                   | Notebook    | [320dada481](https://linux-hardware.org/?probe=320dada481) | Mar 20, 2020 |
| Toshiba       | Satellite P50-A-12Z         | Notebook    | [96927db16b](https://linux-hardware.org/?probe=96927db16b) | Mar 17, 2020 |
| Radxa         | ROCK Pi 4                   | Soc         | [abf599e14a](https://linux-hardware.org/?probe=abf599e14a) | Jan 27, 2020 |
| Huanan        | X79-8D VAA31                | Desktop     | [bbfc99d048](https://linux-hardware.org/?probe=bbfc99d048) | Jan 22, 2020 |
| Unknown       | Unknown                     | Soc         | [62347dfd8d](https://linux-hardware.org/?probe=62347dfd8d) | Jan 01, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [afe3135216](https://linux-hardware.org/?probe=afe3135216) | Dec 10, 2019 |
| ASUSTek       | P53E                        | Notebook    | [e9dcced0f7](https://linux-hardware.org/?probe=e9dcced0f7) | Oct 28, 2019 |
| Lenovo        | ThinkPad T400 6474BV7       | Notebook    | [825bdb9fd0](https://linux-hardware.org/?probe=825bdb9fd0) | Oct 28, 2019 |
| ASUSTek       | 1000H                       | Notebook    | [50da35c0d0](https://linux-hardware.org/?probe=50da35c0d0) | Oct 28, 2019 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [505df04abc](https://linux-hardware.org/?probe=505df04abc) | Oct 27, 2019 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [0b246f9623](https://linux-hardware.org/?probe=0b246f9623) | Oct 27, 2019 |
| Acer          | Aspire E1-572               | Notebook    | [0fe80f5758](https://linux-hardware.org/?probe=0fe80f5758) | Oct 23, 2019 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [21d76cde28](https://linux-hardware.org/?probe=21d76cde28) | Oct 22, 2019 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [ecca7bced0](https://linux-hardware.org/?probe=ecca7bced0) | Oct 22, 2019 |
| Lenovo        | IdeaPad P500 20210          | Notebook    | [3d09c5e38d](https://linux-hardware.org/?probe=3d09c5e38d) | Oct 22, 2019 |
| ASUSTek       | Z97-A                       | Desktop     | [482c60ec21](https://linux-hardware.org/?probe=482c60ec21) | Oct 21, 2019 |
| Acer          | Swift SF314-52              | Notebook    | [05f880ecec](https://linux-hardware.org/?probe=05f880ecec) | Oct 21, 2019 |
| Lenovo        | ThinkPad P70 20ERCTO1WW     | Notebook    | [0ceeb50e5e](https://linux-hardware.org/?probe=0ceeb50e5e) | Oct 21, 2019 |
| Gigabyte      | M61SME-S2                   | Desktop     | [10469f1659](https://linux-hardware.org/?probe=10469f1659) | Oct 21, 2019 |
| Lenovo        | ThinkPad T450s 20BW000EU... | Notebook    | [41ca8d1a20](https://linux-hardware.org/?probe=41ca8d1a20) | Oct 21, 2019 |
| HP            | 2B35                        | Desktop     | [45c5e4afbe](https://linux-hardware.org/?probe=45c5e4afbe) | Oct 21, 2019 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [c2fd6acb71](https://linux-hardware.org/?probe=c2fd6acb71) | Oct 21, 2019 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [70ea4f97bf](https://linux-hardware.org/?probe=70ea4f97bf) | Oct 21, 2019 |
| Dell          | Latitude E7270              | Notebook    | [859e021e2f](https://linux-hardware.org/?probe=859e021e2f) | Oct 20, 2019 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [4751f76aa2](https://linux-hardware.org/?probe=4751f76aa2) | Oct 20, 2019 |
| ASUSTek       | Maximus VII RANGER          | Desktop     | [71121ccd6f](https://linux-hardware.org/?probe=71121ccd6f) | Oct 20, 2019 |
| Fujitsu       | LIFEBOOK A555               | Notebook    | [e0c6729d5b](https://linux-hardware.org/?probe=e0c6729d5b) | Oct 20, 2019 |
| ASUSTek       | P5QLD PRO                   | Desktop     | [dabc1ee203](https://linux-hardware.org/?probe=dabc1ee203) | Oct 20, 2019 |
| Lenovo        | ThinkPad T470 20HDCTO1WW    | Notebook    | [0f9287651d](https://linux-hardware.org/?probe=0f9287651d) | Jul 24, 2019 |
| Lenovo        | ThinkPad T470 20HDCTO1WW    | Notebook    | [67672ef038](https://linux-hardware.org/?probe=67672ef038) | Jul 23, 2019 |
| Gigabyte      | X150M-PRO ECC-CF            | Desktop     | [39987c5d8e](https://linux-hardware.org/?probe=39987c5d8e) | Oct 10, 2018 |
| Fujitsu       | LIFEBOOK A555               | Notebook    | [63c120aa28](https://linux-hardware.org/?probe=63c120aa28) | Aug 19, 2018 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| Slackware 14.2  | 61        | 53.98%  |
| Slackware 15.0  | 47        | 41.59%  |
| Slackware 14.2+ | 5         | 4.42%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| Slackware | 111       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version              | Computers | Percent |
|----------------------|-----------|---------|
| 5.15.19              | 10        | 8.47%   |
| 4.19.80              | 8         | 6.78%   |
| 5.10.28-Unraid       | 6         | 5.08%   |
| 5.15.27              | 4         | 3.39%   |
| 4.4.190              | 4         | 3.39%   |
| 4.4.240              | 3         | 2.54%   |
| 5.3.7                | 2         | 1.69%   |
| 5.17.2               | 2         | 1.69%   |
| 5.17.1               | 2         | 1.69%   |
| 5.16.13              | 2         | 1.69%   |
| 5.15.30-Unraid       | 2         | 1.69%   |
| 5.13.8               | 2         | 1.69%   |
| 5.10.3               | 2         | 1.69%   |
| 5.7.0                | 1         | 0.85%   |
| 5.5.10               | 1         | 0.85%   |
| 5.4.77               | 1         | 0.85%   |
| 5.4.75               | 1         | 0.85%   |
| 5.4.62               | 1         | 0.85%   |
| 5.4.53-APRL          | 1         | 0.85%   |
| 5.4.50               | 1         | 0.85%   |
| 5.4.47               | 1         | 0.85%   |
| 5.4.43               | 1         | 0.85%   |
| 5.4.24toshiba-new    | 1         | 0.85%   |
| 5.4.2                | 1         | 0.85%   |
| 5.4.139-jw           | 1         | 0.85%   |
| 5.4.13               | 1         | 0.85%   |
| 5.4.12+              | 1         | 0.85%   |
| 5.4.0-rc2-vto        | 1         | 0.85%   |
| 5.2.2                | 1         | 0.85%   |
| 5.17.5               | 1         | 0.85%   |
| 5.17.0-custom        | 1         | 0.85%   |
| 5.16.9-joe1          | 1         | 0.85%   |
| 5.16.18              | 1         | 0.85%   |
| 5.16.12              | 1         | 0.85%   |
| 5.16.11              | 1         | 0.85%   |
| 5.15.6               | 1         | 0.85%   |
| 5.15.37.a            | 1         | 0.85%   |
| 5.15.33.kjh          | 1         | 0.85%   |
| 5.15.21-hardened1    | 1         | 0.85%   |
| 5.15.14              | 1         | 0.85%   |
| 5.15.13              | 1         | 0.85%   |
| 5.15.1               | 1         | 0.85%   |
| 5.14.9               | 1         | 0.85%   |
| 5.14.8               | 1         | 0.85%   |
| 5.14.15-Unraid       | 1         | 0.85%   |
| 5.14.15              | 1         | 0.85%   |
| 5.14.11              | 1         | 0.85%   |
| 5.14.10              | 1         | 0.85%   |
| 5.14.0               | 1         | 0.85%   |
| 5.13.9-jw            | 1         | 0.85%   |
| 5.13.5               | 1         | 0.85%   |
| 5.13.12              | 1         | 0.85%   |
| 5.13.11              | 1         | 0.85%   |
| 5.13.0.a             | 1         | 0.85%   |
| 5.12.12              | 1         | 0.85%   |
| 5.10.91              | 1         | 0.85%   |
| 5.10.44-slack64-host | 1         | 0.85%   |
| 5.10.40              | 1         | 0.85%   |
| 5.10.4               | 1         | 0.85%   |
| 5.10.21              | 1         | 0.85%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.19 | 10        | 8.47%   |
| 4.19.80 | 8         | 6.78%   |
| 5.10.28 | 6         | 5.08%   |
| 4.4.190 | 5         | 4.24%   |
| 5.15.27 | 4         | 3.39%   |
| 4.4.240 | 3         | 2.54%   |
| 5.3.7   | 2         | 1.69%   |
| 5.17.2  | 2         | 1.69%   |
| 5.17.1  | 2         | 1.69%   |
| 5.16.13 | 2         | 1.69%   |
| 5.15.30 | 2         | 1.69%   |
| 5.14.15 | 2         | 1.69%   |
| 5.13.8  | 2         | 1.69%   |
| 5.10.3  | 2         | 1.69%   |
| 5.7.0   | 1         | 0.85%   |
| 5.5.10  | 1         | 0.85%   |
| 5.4.77  | 1         | 0.85%   |
| 5.4.75  | 1         | 0.85%   |
| 5.4.62  | 1         | 0.85%   |
| 5.4.53  | 1         | 0.85%   |
| 5.4.50  | 1         | 0.85%   |
| 5.4.47  | 1         | 0.85%   |
| 5.4.43  | 1         | 0.85%   |
| 5.4.24  | 1         | 0.85%   |
| 5.4.2   | 1         | 0.85%   |
| 5.4.139 | 1         | 0.85%   |
| 5.4.13  | 1         | 0.85%   |
| 5.4.12  | 1         | 0.85%   |
| 5.4.0   | 1         | 0.85%   |
| 5.2.2   | 1         | 0.85%   |
| 5.17.5  | 1         | 0.85%   |
| 5.17.0  | 1         | 0.85%   |
| 5.16.9  | 1         | 0.85%   |
| 5.16.18 | 1         | 0.85%   |
| 5.16.12 | 1         | 0.85%   |
| 5.16.11 | 1         | 0.85%   |
| 5.15.6  | 1         | 0.85%   |
| 5.15.37 | 1         | 0.85%   |
| 5.15.33 | 1         | 0.85%   |
| 5.15.21 | 1         | 0.85%   |
| 5.15.14 | 1         | 0.85%   |
| 5.15.13 | 1         | 0.85%   |
| 5.15.1  | 1         | 0.85%   |
| 5.14.9  | 1         | 0.85%   |
| 5.14.8  | 1         | 0.85%   |
| 5.14.11 | 1         | 0.85%   |
| 5.14.10 | 1         | 0.85%   |
| 5.14.0  | 1         | 0.85%   |
| 5.13.9  | 1         | 0.85%   |
| 5.13.5  | 1         | 0.85%   |
| 5.13.12 | 1         | 0.85%   |
| 5.13.11 | 1         | 0.85%   |
| 5.13.0  | 1         | 0.85%   |
| 5.12.12 | 1         | 0.85%   |
| 5.10.91 | 1         | 0.85%   |
| 5.10.44 | 1         | 0.85%   |
| 5.10.40 | 1         | 0.85%   |
| 5.10.4  | 1         | 0.85%   |
| 5.10.21 | 1         | 0.85%   |
| 5.10.19 | 1         | 0.85%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 23        | 19.66%  |
| 4.4     | 16        | 13.68%  |
| 5.10    | 15        | 12.82%  |
| 4.19    | 15        | 12.82%  |
| 5.4     | 13        | 11.11%  |
| 5.13    | 7         | 5.98%   |
| 5.17    | 6         | 5.13%   |
| 5.16    | 6         | 5.13%   |
| 5.14    | 6         | 5.13%   |
| 5.3     | 2         | 1.71%   |
| 4.9     | 2         | 1.71%   |
| 5.7     | 1         | 0.85%   |
| 5.5     | 1         | 0.85%   |
| 5.2     | 1         | 0.85%   |
| 5.12    | 1         | 0.85%   |
| 4.20    | 1         | 0.85%   |
| 4.16    | 1         | 0.85%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 108       | 97.3%   |
| aarch64 | 2         | 1.8%    |
| i686    | 1         | 0.9%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Unknown       | 41        | 36.28%  |
| XFCE          | 31        | 27.43%  |
| KDE5          | 28        | 24.78%  |
| KDE           | 5         | 4.42%   |
| GNOME         | 2         | 1.77%   |
| FVWM          | 2         | 1.77%   |
| xwmconfig     | 1         | 0.88%   |
| MATE          | 1         | 0.88%   |
| LXQt          | 1         | 0.88%   |
| Enlightenment | 1         | 0.88%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 78        | 69.03%  |
| Tty     | 21        | 18.58%  |
| Unknown | 10        | 8.85%   |
| Wayland | 4         | 3.54%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 46        | 40.71%  |
| SDDM    | 37        | 32.74%  |
| XDM     | 26        | 23.01%  |
| SLiM    | 2         | 1.77%   |
| LightDM | 2         | 1.77%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 59        | 53.15%  |
| Unknown     | 37        | 33.33%  |
| ru_RU       | 2         | 1.8%    |
| pt_BR       | 2         | 1.8%    |
| it_IT       | 2         | 1.8%    |
| fr_FR       | 2         | 1.8%    |
| sr_RS@latin | 1         | 0.9%    |
| pl_PL       | 1         | 0.9%    |
| es_ES.UTF8  | 1         | 0.9%    |
| en_US.ASCII | 1         | 0.9%    |
| en_GB       | 1         | 0.9%    |
| de_DE       | 1         | 0.9%    |
| C           | 1         | 0.9%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 61        | 54.46%  |
| EFI  | 51        | 45.54%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 80        | 72.07%  |
| Btrfs    | 14        | 12.61%  |
| Overlay  | 5         | 4.5%    |
| Xfs      | 4         | 3.6%    |
| Rootfs   | 3         | 2.7%    |
| Zfs      | 1         | 0.9%    |
| Reiserfs | 1         | 0.9%    |
| Jfs      | 1         | 0.9%    |
| F2fs     | 1         | 0.9%    |
| Ext3     | 1         | 0.9%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 77        | 67.54%  |
| MBR     | 31        | 27.19%  |
| Unknown | 6         | 5.26%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 73        | 64.6%   |
| Yes       | 40        | 35.4%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 73        | 65.77%  |
| Yes       | 38        | 34.23%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 19        | 17.12%  |
| Hewlett-Packard     | 18        | 16.22%  |
| Lenovo              | 13        | 11.71%  |
| MSI                 | 10        | 9.01%   |
| Dell                | 10        | 9.01%   |
| ASRock              | 7         | 6.31%   |
| Gigabyte Technology | 4         | 3.6%    |
| Toshiba             | 3         | 2.7%    |
| Acer                | 3         | 2.7%    |
| Notebook            | 2         | 1.8%    |
| Dynabook            | 2         | 1.8%    |
| Apple               | 2         | 1.8%    |
| Unknown             | 2         | 1.8%    |
| TYAN Computer       | 1         | 0.9%    |
| System76            | 1         | 0.9%    |
| Supermicro          | 1         | 0.9%    |
| Sony                | 1         | 0.9%    |
| Shuttle             | 1         | 0.9%    |
| Samsung Electronics | 1         | 0.9%    |
| Radxa               | 1         | 0.9%    |
| NETGEAR             | 1         | 0.9%    |
| Intel               | 1         | 0.9%    |
| Huanan              | 1         | 0.9%    |
| HPE                 | 1         | 0.9%    |
| Fujitsu             | 1         | 0.9%    |
| Framework           | 1         | 0.9%    |
| Foxconn             | 1         | 0.9%    |
| Biostar             | 1         | 0.9%    |
| AMI                 | 1         | 0.9%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| ASUS All Series                          | 4         | 3.6%    |
| Unknown                                  | 2         | 1.8%    |
| TYAN S7012                               | 1         | 0.9%    |
| Toshiba Satellite P50-A-12Z              | 1         | 0.9%    |
| Toshiba Satellite C660                   | 1         | 0.9%    |
| Toshiba PORTEGE Z30-A                    | 1         | 0.9%    |
| System76 Oryx Pro                        | 1         | 0.9%    |
| Supermicro X9DA7/E                       | 1         | 0.9%    |
| Sony SVE1713A1EW                         | 1         | 0.9%    |
| Shuttle NC03U                            | 1         | 0.9%    |
| Samsung 300E5M/300E5L                    | 1         | 0.9%    |
| Radxa ROCK Pi 4                          | 1         | 0.9%    |
| Notebook X170KM-G                        | 1         | 0.9%    |
| Notebook NL40_50CU                       | 1         | 0.9%    |
| NETGEAR ReadyDATA 5200                   | 1         | 0.9%    |
| MSI MS-7C52                              | 1         | 0.9%    |
| MSI MS-7C02                              | 1         | 0.9%    |
| MSI MS-7788                              | 1         | 0.9%    |
| MSI MS-7693                              | 1         | 0.9%    |
| MSI MS-7529                              | 1         | 0.9%    |
| MSI MS-7365                              | 1         | 0.9%    |
| MSI Modern 14 B11MO                      | 1         | 0.9%    |
| MSI GP76 Leopard 11UG                    | 1         | 0.9%    |
| MSI GL73 8RC                             | 1         | 0.9%    |
| MSI GE76 Raider 11UE                     | 1         | 0.9%    |
| Lenovo V330-14ARR 81B1                   | 1         | 0.9%    |
| Lenovo ThinkPad X230 2325P38             | 1         | 0.9%    |
| Lenovo ThinkPad X1 Carbon 7th 20R10015US | 1         | 0.9%    |
| Lenovo ThinkPad X1 Carbon 5th 20HQS04300 | 1         | 0.9%    |
| Lenovo ThinkPad T470 20HDCTO1WW          | 1         | 0.9%    |
| Lenovo ThinkPad T450s 20BW000EUS         | 1         | 0.9%    |
| Lenovo ThinkPad T400 6474BV7             | 1         | 0.9%    |
| Lenovo ThinkPad P70 20ERCTO1WW           | 1         | 0.9%    |
| Lenovo ThinkPad L440 20ASS05K00          | 1         | 0.9%    |
| Lenovo ThinkPad Edge E530c 336669G       | 1         | 0.9%    |
| Lenovo IdeaPad P500 20210                | 1         | 0.9%    |
| Lenovo IdeaPad 310-15ISK 80SM            | 1         | 0.9%    |
| Lenovo H50-05 90BH001WIX                 | 1         | 0.9%    |
| Intel DZ77RE-75K AAG39010-302            | 1         | 0.9%    |
| Huanan X79-8D VAA31                      | 1         | 0.9%    |
| HPE ProLiant MicroServer Gen10 Plus      | 1         | 0.9%    |
| HP Z620 Workstation                      | 1         | 0.9%    |
| HP Z440 Workstation                      | 1         | 0.9%    |
| HP xw8400 Workstation                    | 1         | 0.9%    |
| HP t640 Thin Client                      | 1         | 0.9%    |
| HP t620 Quad Core TC                     | 1         | 0.9%    |
| HP ProBook 6570b                         | 1         | 0.9%    |
| HP Pavilion Notebook                     | 1         | 0.9%    |
| HP Pavilion Gaming Laptop 16-a0xxx       | 1         | 0.9%    |
| HP Pavilion Gaming Laptop 15-ec1xxx      | 1         | 0.9%    |
| HP Laptop 15-da0xxx                      | 1         | 0.9%    |
| HP Laptop 15-bs2xx                       | 1         | 0.9%    |
| HP Laptop 15-bs1xx                       | 1         | 0.9%    |
| HP EliteBook Folio 1020 G1 SE            | 1         | 0.9%    |
| HP EliteBook 840 G5                      | 1         | 0.9%    |
| HP 500-515na                             | 1         | 0.9%    |
| HP 245 G7 Notebook PC                    | 1         | 0.9%    |
| HP 205 G4 22 All-in-One PC               | 1         | 0.9%    |
| HP 15 Notebook PC                        | 1         | 0.9%    |
| Gigabyte X150M-PRO ECC                   | 1         | 0.9%    |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 9         | 8.11%   |
| Dell Precision      | 4         | 3.6%    |
| ASUS PRIME          | 4         | 3.6%    |
| ASUS All            | 4         | 3.6%    |
| HP Pavilion         | 3         | 2.7%    |
| HP Laptop           | 3         | 2.7%    |
| Dell Latitude       | 3         | 2.7%    |
| Toshiba Satellite   | 2         | 1.8%    |
| Lenovo IdeaPad      | 2         | 1.8%    |
| HP EliteBook        | 2         | 1.8%    |
| ASUS ROG            | 2         | 1.8%    |
| Acer Aspire         | 2         | 1.8%    |
| Unknown             | 2         | 1.8%    |
| TYAN S7012          | 1         | 0.9%    |
| Toshiba PORTEGE     | 1         | 0.9%    |
| System76 Oryx       | 1         | 0.9%    |
| Supermicro X9DA7    | 1         | 0.9%    |
| Sony SVE1713A1EW    | 1         | 0.9%    |
| Shuttle NC03U       | 1         | 0.9%    |
| Samsung 300E5M      | 1         | 0.9%    |
| Radxa ROCK          | 1         | 0.9%    |
| Notebook X170KM-G   | 1         | 0.9%    |
| Notebook NL40       | 1         | 0.9%    |
| NETGEAR ReadyDATA   | 1         | 0.9%    |
| MSI MS-7C52         | 1         | 0.9%    |
| MSI MS-7C02         | 1         | 0.9%    |
| MSI MS-7788         | 1         | 0.9%    |
| MSI MS-7693         | 1         | 0.9%    |
| MSI MS-7529         | 1         | 0.9%    |
| MSI MS-7365         | 1         | 0.9%    |
| MSI Modern          | 1         | 0.9%    |
| MSI GP76            | 1         | 0.9%    |
| MSI GL73            | 1         | 0.9%    |
| MSI GE76            | 1         | 0.9%    |
| Lenovo V330-14ARR   | 1         | 0.9%    |
| Lenovo H50-05       | 1         | 0.9%    |
| Intel DZ77RE-75K    | 1         | 0.9%    |
| Huanan X79-8D       | 1         | 0.9%    |
| HPE ProLiant        | 1         | 0.9%    |
| HP Z620             | 1         | 0.9%    |
| HP Z440             | 1         | 0.9%    |
| HP xw8400           | 1         | 0.9%    |
| HP t640             | 1         | 0.9%    |
| HP t620             | 1         | 0.9%    |
| HP ProBook          | 1         | 0.9%    |
| HP 500-515na        | 1         | 0.9%    |
| HP 245              | 1         | 0.9%    |
| HP 205              | 1         | 0.9%    |
| HP 15               | 1         | 0.9%    |
| Gigabyte X150M-PRO  | 1         | 0.9%    |
| Gigabyte N3160TN    | 1         | 0.9%    |
| Gigabyte M61SME-S2  | 1         | 0.9%    |
| Gigabyte 970A-DS3P  | 1         | 0.9%    |
| Fujitsu LIFEBOOK    | 1         | 0.9%    |
| Framework Laptop    | 1         | 0.9%    |
| Foxconn p6-2390     | 1         | 0.9%    |
| Dynabook PORTEGE    | 1         | 0.9%    |
| Dynabook P1-C7MP-BL | 1         | 0.9%    |
| Dell Vostro         | 1         | 0.9%    |
| Dell PowerEdge      | 1         | 0.9%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 14        | 12.61%  |
| 2012    | 11        | 9.91%   |
| 2020    | 10        | 9.01%   |
| 2018    | 10        | 9.01%   |
| 2017    | 10        | 9.01%   |
| 2015    | 9         | 8.11%   |
| 2021    | 8         | 7.21%   |
| 2014    | 8         | 7.21%   |
| 2016    | 7         | 6.31%   |
| 2011    | 6         | 5.41%   |
| 2008    | 5         | 4.5%    |
| 2013    | 3         | 2.7%    |
| 2009    | 3         | 2.7%    |
| 2007    | 3         | 2.7%    |
| 2010    | 2         | 1.8%    |
| Unknown | 2         | 1.8%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 52        | 46.85%  |
| Desktop        | 50        | 45.05%  |
| Mini pc        | 3         | 2.7%    |
| System on chip | 2         | 1.8%    |
| All in one     | 2         | 1.8%    |
| Server         | 2         | 1.8%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 111       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 108       | 97.3%   |
| Yes  | 3         | 2.7%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 23        | 20.72%  |
| 4.01-8.0    | 22        | 19.82%  |
| 8.01-16.0   | 20        | 18.02%  |
| 3.01-4.0    | 19        | 17.12%  |
| 32.01-64.0  | 10        | 9.01%   |
| 64.01-256.0 | 8         | 7.21%   |
| 24.01-32.0  | 5         | 4.5%    |
| 1.01-2.0    | 3         | 2.7%    |
| 0.51-1.0    | 1         | 0.9%    |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 35        | 30.17%  |
| 2.01-3.0    | 25        | 21.55%  |
| 4.01-8.0    | 20        | 17.24%  |
| 3.01-4.0    | 12        | 10.34%  |
| 0.51-1.0    | 8         | 6.9%    |
| 0.01-0.5    | 5         | 4.31%   |
| 8.01-16.0   | 4         | 3.45%   |
| 16.01-24.0  | 3         | 2.59%   |
| 24.01-32.0  | 2         | 1.72%   |
| 32.01-64.0  | 1         | 0.86%   |
| 64.01-256.0 | 1         | 0.86%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 53        | 46.9%   |
| 2      | 24        | 21.24%  |
| 3      | 12        | 10.62%  |
| 4      | 10        | 8.85%   |
| 6      | 4         | 3.54%   |
| 5      | 4         | 3.54%   |
| 0      | 2         | 1.77%   |
| 13     | 1         | 0.88%   |
| 9      | 1         | 0.88%   |
| 8      | 1         | 0.88%   |
| 7      | 1         | 0.88%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 66        | 59.46%  |
| Yes       | 45        | 40.54%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 103       | 92.79%  |
| No        | 8         | 7.21%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 74        | 66.67%  |
| No        | 37        | 33.33%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 68        | 61.26%  |
| No        | 43        | 38.74%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 25        | 22.52%  |
| UK           | 10        | 9.01%   |
| Kazakhstan   | 6         | 5.41%   |
| Germany      | 6         | 5.41%   |
| Canada       | 6         | 5.41%   |
| Brazil       | 6         | 5.41%   |
| Portugal     | 5         | 4.5%    |
| Japan        | 5         | 4.5%    |
| Italy        | 5         | 4.5%    |
| Sweden       | 4         | 3.6%    |
| Russia       | 4         | 3.6%    |
| India        | 4         | 3.6%    |
| France       | 4         | 3.6%    |
| Spain        | 3         | 2.7%    |
| South Africa | 3         | 2.7%    |
| Serbia       | 2         | 1.8%    |
| Poland       | 2         | 1.8%    |
| Hong Kong    | 2         | 1.8%    |
| Greece       | 2         | 1.8%    |
| Switzerland  | 1         | 0.9%    |
| Philippines  | 1         | 0.9%    |
| Netherlands  | 1         | 0.9%    |
| Mexico       | 1         | 0.9%    |
| Finland      | 1         | 0.9%    |
| Chile        | 1         | 0.9%    |
| Bulgaria     | 1         | 0.9%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Ust-Kamenogorsk        | 4         | 3.51%   |
| Lisbon                 | 4         | 3.51%   |
| Yekaterinburg          | 3         | 2.63%   |
| Paris                  | 3         | 2.63%   |
| Warsaw                 | 2         | 1.75%   |
| Tsukuba                | 2         | 1.75%   |
| Tendo                  | 2         | 1.75%   |
| New Delhi              | 2         | 1.75%   |
| Milan                  | 2         | 1.75%   |
| Karaganda              | 2         | 1.75%   |
| Chania                 | 2         | 1.75%   |
| Carrollton             | 2         | 1.75%   |
| Cape Town              | 2         | 1.75%   |
| Belgrade               | 2         | 1.75%   |
| Barry                  | 2         | 1.75%   |
| Barrie                 | 2         | 1.75%   |
| Wokingham              | 1         | 0.88%   |
| Winnipeg               | 1         | 0.88%   |
| Weilheim               | 1         | 0.88%   |
| Visconde do Rio Branco | 1         | 0.88%   |
| Toronto                | 1         | 0.88%   |
| Tiffin                 | 1         | 0.88%   |
| Stockholm              | 1         | 0.88%   |
| St Petersburg          | 1         | 0.88%   |
| St Louis               | 1         | 0.88%   |
| Springfield            | 1         | 0.88%   |
| Southend-on-Sea        | 1         | 0.88%   |
| Skövde                | 1         | 0.88%   |
| Shrewsbury             | 1         | 0.88%   |
| Sham Shui Po           | 1         | 0.88%   |
| Santa Cruz do Sul      | 1         | 0.88%   |
| San Antonio            | 1         | 0.88%   |
| Saint Paul             | 1         | 0.88%   |
| Round Rock             | 1         | 0.88%   |
| Rome                   | 1         | 0.88%   |
| Roknaes                | 1         | 0.88%   |
| Reno                   | 1         | 0.88%   |
| Redding                | 1         | 0.88%   |
| Puente Alto            | 1         | 0.88%   |
| Porto Alegre           | 1         | 0.88%   |
| Plovdiv                | 1         | 0.88%   |
| Plainwell              | 1         | 0.88%   |
| Pinhal Novo            | 1         | 0.88%   |
| Pesaro                 | 1         | 0.88%   |
| Pasay                  | 1         | 0.88%   |
| Palma                  | 1         | 0.88%   |
| Ottawa                 | 1         | 0.88%   |
| Ōtsu                  | 1         | 0.88%   |
| Oldham                 | 1         | 0.88%   |
| Oberstreit             | 1         | 0.88%   |
| Northport              | 1         | 0.88%   |
| Naples                 | 1         | 0.88%   |
| Naaldwijk              | 1         | 0.88%   |
| Montreal               | 1         | 0.88%   |
| Milwaukee              | 1         | 0.88%   |
| Mexico City            | 1         | 0.88%   |
| Mead                   | 1         | 0.88%   |
| McKinney               | 1         | 0.88%   |
| Mason                  | 1         | 0.88%   |
| London                 | 1         | 0.88%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 33        | 59     | 18.54%  |
| Samsung Electronics | 31        | 46     | 17.42%  |
| Seagate             | 29        | 58     | 16.29%  |
| Toshiba             | 13        | 21     | 7.3%    |
| Kingston            | 8         | 10     | 4.49%   |
| Hitachi             | 7         | 10     | 3.93%   |
| Crucial             | 7         | 8      | 3.93%   |
| HGST                | 5         | 5      | 2.81%   |
| Unknown             | 4         | 4      | 2.25%   |
| SanDisk             | 4         | 4      | 2.25%   |
| Intel               | 4         | 4      | 2.25%   |
| A-DATA Technology   | 4         | 4      | 2.25%   |
| SK Hynix            | 3         | 3      | 1.69%   |
| Hewlett-Packard     | 3         | 4      | 1.69%   |
| Gigabyte Technology | 3         | 3      | 1.69%   |
| Patriot             | 2         | 3      | 1.12%   |
| China               | 2         | 3      | 1.12%   |
| Apple               | 2         | 3      | 1.12%   |
| ZHITAI              | 1         | 2      | 0.56%   |
| TO Exter            | 1         | 1      | 0.56%   |
| Team                | 1         | 1      | 0.56%   |
| PLEXTOR             | 1         | 1      | 0.56%   |
| Netac               | 1         | 1      | 0.56%   |
| Micron Technology   | 1         | 1      | 0.56%   |
| MAXTOR              | 1         | 1      | 0.56%   |
| KIOXIA              | 1         | 1      | 0.56%   |
| JMicron             | 1         | 1      | 0.56%   |
| Intenso             | 1         | 1      | 0.56%   |
| GOODRAM             | 1         | 1      | 0.56%   |
| Fujitsu             | 1         | 1      | 0.56%   |
| External            | 1         | 1      | 0.56%   |
| DOGFISH             | 1         | 1      | 0.56%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| WDC WD20EFRX-68EUZN0 2TB             | 3         | 1.38%   |
| WDC WD1003FZEX-00MK2A0 1TB           | 3         | 1.38%   |
| Samsung SSD 970 EVO 250GB            | 3         | 1.38%   |
| WDC WD10SPZX-60Z10T0 1TB             | 2         | 0.92%   |
| Toshiba MQ04ABF100 1TB               | 2         | 0.92%   |
| Toshiba MQ01ABD100 1TB               | 2         | 0.92%   |
| Seagate ST500DM002-1BD142 500GB      | 2         | 0.92%   |
| Seagate ST4000VN008-2DR166 4TB       | 2         | 0.92%   |
| Seagate ST31000524AS 1TB             | 2         | 0.92%   |
| Seagate ST2000DM008-2FR102 2TB       | 2         | 0.92%   |
| Seagate ST2000DM001-1CH164 2TB       | 2         | 0.92%   |
| Seagate ST1000DM010-2EP102 1TB       | 2         | 0.92%   |
| Seagate ST1000DM003-1ER162 1TB       | 2         | 0.92%   |
| Samsung SSD 970 EVO Plus 1TB         | 2         | 0.92%   |
| Samsung SSD 860 QVO 2TB              | 2         | 0.92%   |
| Kingston SA400S37240G 240GB SSD      | 2         | 0.92%   |
| Crucial CT500MX500SSD1 500GB         | 2         | 0.92%   |
| ZHITAI SC001 Active 1TB SSD          | 1         | 0.46%   |
| ZHITAI PC005 Active 512GB            | 1         | 0.46%   |
| WDC WDS500G2B0B-00YS70 500GB SSD     | 1         | 0.46%   |
| WDC WDS100T2B0C-00PXH0 1TB           | 1         | 0.46%   |
| WDC WD7500BPVT-24HXZT3 752GB         | 1         | 0.46%   |
| WDC WD5000LPCX-60VHAT1 500GB         | 1         | 0.46%   |
| WDC WD5000BPVT-2 500GB               | 1         | 0.46%   |
| WDC WD5000BPKX-60HPJT0 500GB         | 1         | 0.46%   |
| WDC WD5000AAKX-22ERMA0 500GB         | 1         | 0.46%   |
| WDC WD5000AAKX-00ERMA0 500GB         | 1         | 0.46%   |
| WDC WD5000AAKS-00V0A0 500GB          | 1         | 0.46%   |
| WDC WD5000AAKS-00A7B2 500GB          | 1         | 0.46%   |
| WDC WD40EJRX-89T1XY0 4TB             | 1         | 0.46%   |
| WDC WD40EFRX-68WT0N0 4TB             | 1         | 0.46%   |
| WDC WD40EFRX-68N32N0 4TB             | 1         | 0.46%   |
| WDC WD400BD-60LTA0 40GB              | 1         | 0.46%   |
| WDC WD3200AAJS-65B4A0 320GB          | 1         | 0.46%   |
| WDC WD30EZRX-00SPEB0 3TB             | 1         | 0.46%   |
| WDC WD30EZRX-00M                     | 1         | 0.46%   |
| WDC WD30EFRX-68EUZN0 3TB             | 1         | 0.46%   |
| WDC WD30EFRX-68AX9N0 3TB             | 1         | 0.46%   |
| WDC WD20EZRZ-00Z5HB0 2TB             | 1         | 0.46%   |
| WDC WD20EZRX-00D8PB0 2TB             | 1         | 0.46%   |
| WDC WD2003FZEX-0 2TB                 | 1         | 0.46%   |
| WDC WD1600AAJS-00PSA0 160GB          | 1         | 0.46%   |
| WDC WD120EDAZ-11F3RA0 12TB           | 1         | 0.46%   |
| WDC WD10JPVX-35JC3T0 1TB             | 1         | 0.46%   |
| WDC WD10JPVX-16JC3T3 1TB             | 1         | 0.46%   |
| WDC WD10JPVT-08A1YT2 1TB             | 1         | 0.46%   |
| WDC WD10JPLX-00MBPT0 1TB             | 1         | 0.46%   |
| WDC WD10EZRZ-00HTKB0 1TB             | 1         | 0.46%   |
| WDC WD10EZEX-22BN5A0 1TB             | 1         | 0.46%   |
| WDC WD10EZEX-00RKKA0 1TB             | 1         | 0.46%   |
| WDC WD10EZEX-00BN5A0 1TB             | 1         | 0.46%   |
| WDC WD10EURX-61C57Y0 1TB             | 1         | 0.46%   |
| WDC WD10EALS-00Z8A0 1TB              | 1         | 0.46%   |
| WDC WD100EMAZ-00WJTA0 10TB           | 1         | 0.46%   |
| WDC WD1003FZEX-00K3CA0 1TB           | 1         | 0.46%   |
| WDC PC SN530 SDBPNPZ-1T00-1002 1TB   | 1         | 0.46%   |
| WDC PC SN520 SDAPNUW-256G-1102 256GB | 1         | 0.46%   |
| Unknown SLD32G  32GB                 | 1         | 0.46%   |
| Unknown SD32G  32GB                  | 1         | 0.46%   |
| Unknown SC32G  32GB                  | 1         | 0.46%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 30        | 55     | 33.71%  |
| Seagate             | 29        | 54     | 32.58%  |
| Toshiba             | 13        | 21     | 14.61%  |
| Hitachi             | 7         | 10     | 7.87%   |
| HGST                | 5         | 5      | 5.62%   |
| Samsung Electronics | 2         | 2      | 2.25%   |
| MAXTOR              | 1         | 1      | 1.12%   |
| Hewlett-Packard     | 1         | 1      | 1.12%   |
| Fujitsu             | 1         | 1      | 1.12%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 15        | 23     | 27.27%  |
| Kingston            | 7         | 9      | 12.73%  |
| Crucial             | 6         | 7      | 10.91%  |
| SanDisk             | 4         | 4      | 7.27%   |
| Patriot             | 2         | 3      | 3.64%   |
| China               | 2         | 3      | 3.64%   |
| Apple               | 2         | 3      | 3.64%   |
| A-DATA Technology   | 2         | 2      | 3.64%   |
| ZHITAI              | 1         | 1      | 1.82%   |
| WDC                 | 1         | 1      | 1.82%   |
| TO Exter            | 1         | 1      | 1.82%   |
| Team                | 1         | 1      | 1.82%   |
| PLEXTOR             | 1         | 1      | 1.82%   |
| Netac               | 1         | 1      | 1.82%   |
| Micron Technology   | 1         | 1      | 1.82%   |
| JMicron             | 1         | 1      | 1.82%   |
| Intenso             | 1         | 1      | 1.82%   |
| Intel               | 1         | 1      | 1.82%   |
| Hewlett-Packard     | 1         | 1      | 1.82%   |
| GOODRAM             | 1         | 1      | 1.82%   |
| Gigabyte Technology | 1         | 1      | 1.82%   |
| External            | 1         | 1      | 1.82%   |
| DOGFISH             | 1         | 1      | 1.82%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 64        | 150    | 42.38%  |
| SSD     | 49        | 69     | 32.45%  |
| NVMe    | 33        | 40     | 21.85%  |
| MMC     | 4         | 4      | 2.65%   |
| Unknown | 1         | 4      | 0.66%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 87        | 211    | 67.44%  |
| NVMe | 33        | 40     | 25.58%  |
| SAS  | 5         | 12     | 3.88%   |
| MMC  | 4         | 4      | 3.1%    |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 63        | 94     | 47.01%  |
| 0.51-1.0   | 37        | 64     | 27.61%  |
| 1.01-2.0   | 13        | 17     | 9.7%    |
| 3.01-4.0   | 8         | 20     | 5.97%   |
| 2.01-3.0   | 7         | 15     | 5.22%   |
| 4.01-10.0  | 4         | 4      | 2.99%   |
| 10.01-20.0 | 2         | 5      | 1.49%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 25        | 22.32%  |
| 501-1000       | 25        | 22.32%  |
| 251-500        | 18        | 16.07%  |
| Unknown        | 13        | 11.61%  |
| 1001-2000      | 12        | 10.71%  |
| 1-20           | 7         | 6.25%   |
| 2001-3000      | 5         | 4.46%   |
| More than 3000 | 3         | 2.68%   |
| 51-100         | 3         | 2.68%   |
| 21-50          | 1         | 0.89%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 22        | 19.3%   |
| 1-20           | 19        | 16.67%  |
| 501-1000       | 16        | 14.04%  |
| 21-50          | 15        | 13.16%  |
| Unknown        | 13        | 11.4%   |
| 251-500        | 12        | 10.53%  |
| 51-100         | 12        | 10.53%  |
| 1001-2000      | 3         | 2.63%   |
| More than 3000 | 2         | 1.75%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD5000LPCX-60VHAT1 500GB        | 1         | 1      | 2.78%   |
| WDC WD5000BPKX-60HPJT0 500GB        | 1         | 1      | 2.78%   |
| WDC WD5000AAKX-22ERMA0 500GB        | 1         | 1      | 2.78%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 1         | 1      | 2.78%   |
| WDC WD5000AAKS-00A7B2 500GB         | 1         | 1      | 2.78%   |
| WDC WD40EFRX-68WT0N0 4TB            | 1         | 2      | 2.78%   |
| WDC WD3200AAJS-65B4A0 320GB         | 1         | 1      | 2.78%   |
| WDC WD30EZRX-00M                    | 1         | 1      | 2.78%   |
| WDC WD30EFRX-68AX9N0 3TB            | 1         | 4      | 2.78%   |
| WDC WD20EFRX-68EUZN0 2TB            | 1         | 2      | 2.78%   |
| WDC WD10JPLX-00MBPT0 1TB            | 1         | 1      | 2.78%   |
| WDC WD10EZEX-00RKKA0 1TB            | 1         | 1      | 2.78%   |
| WDC WD10EALS-00Z8A0 1TB             | 1         | 2      | 2.78%   |
| WDC WD1003FZEX-00MK2A0 1TB          | 1         | 2      | 2.78%   |
| Toshiba MK2565GSXN 250GB            | 1         | 1      | 2.78%   |
| Seagate ST380011A 80GB              | 1         | 2      | 2.78%   |
| Seagate ST3500630AS 500GB           | 1         | 1      | 2.78%   |
| Seagate ST3500418AS 500GB           | 1         | 1      | 2.78%   |
| Seagate ST3500410AS 500GB           | 1         | 1      | 2.78%   |
| Seagate ST31000524AS 1TB            | 1         | 1      | 2.78%   |
| Seagate ST3000VX006-1HH166 3TB      | 1         | 1      | 2.78%   |
| Seagate ST2000DL003-9VT166 2TB      | 1         | 1      | 2.78%   |
| Seagate ST1000VM002-1SD102 1TB      | 1         | 1      | 2.78%   |
| Seagate ST1000NM0011 1TB            | 1         | 2      | 2.78%   |
| Seagate ST1000DM003-1ER162 1TB      | 1         | 2      | 2.78%   |
| SanDisk SDSA6MM-016G-1006 16GB SSD  | 1         | 1      | 2.78%   |
| Samsung Electronics SSD 870 EVO 1TB | 1         | 1      | 2.78%   |
| PLEXTOR PX-128M6S 128GB SSD         | 1         | 1      | 2.78%   |
| MAXTOR 4G120J6 128GB                | 1         | 1      | 2.78%   |
| Intel SSDSA2M080G2GC 80GB           | 1         | 1      | 2.78%   |
| Hitachi HUA723030ALA640 3TB         | 1         | 1      | 2.78%   |
| Hitachi HDS721050CLA660 500GB       | 1         | 1      | 2.78%   |
| Hitachi HDS721016CLA382 160GB       | 1         | 1      | 2.78%   |
| HGST HTS725050A7E630 500GB          | 1         | 1      | 2.78%   |
| HGST HTS545050A7E380 500GB          | 1         | 1      | 2.78%   |
| HGST HDN726040ALE614 4TB            | 1         | 1      | 2.78%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 12        | 21     | 36.36%  |
| Seagate             | 9         | 13     | 27.27%  |
| Hitachi             | 3         | 3      | 9.09%   |
| HGST                | 3         | 3      | 9.09%   |
| Toshiba             | 1         | 1      | 3.03%   |
| SanDisk             | 1         | 1      | 3.03%   |
| Samsung Electronics | 1         | 1      | 3.03%   |
| PLEXTOR             | 1         | 1      | 3.03%   |
| MAXTOR              | 1         | 1      | 3.03%   |
| Intel               | 1         | 1      | 3.03%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 12        | 21     | 41.38%  |
| Seagate | 9         | 13     | 31.03%  |
| Hitachi | 3         | 3      | 10.34%  |
| HGST    | 3         | 3      | 10.34%  |
| Toshiba | 1         | 1      | 3.45%   |
| MAXTOR  | 1         | 1      | 3.45%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 26        | 42     | 86.67%  |
| SSD  | 4         | 4      | 13.33%  |

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
| Works    | 92        | 193    | 67.15%  |
| Malfunc  | 30        | 46     | 21.9%   |
| Detected | 15        | 28     | 10.95%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 72        | 48.32%  |
| AMD                         | 25        | 16.78%  |
| Samsung Electronics         | 17        | 11.41%  |
| ASMedia Technology          | 5         | 3.36%   |
| Marvell Technology Group    | 4         | 2.68%   |
| SK Hynix                    | 3         | 2.01%   |
| Sandisk                     | 3         | 2.01%   |
| Nvidia                      | 3         | 2.01%   |
| Broadcom / LSI              | 3         | 2.01%   |
| Realtek Semiconductor       | 2         | 1.34%   |
| Phison Electronics          | 2         | 1.34%   |
| JMicron Technology          | 2         | 1.34%   |
| Yangtze Memory Technologies | 1         | 0.67%   |
| Silicon Image               | 1         | 0.67%   |
| Micron/Crucial Technology   | 1         | 0.67%   |
| KIOXIA                      | 1         | 0.67%   |
| Kingston Technology Company | 1         | 0.67%   |
| Biwin Storage Technology    | 1         | 0.67%   |
| Adaptec                     | 1         | 0.67%   |
| 3ware                       | 1         | 0.67%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 21        | 11.86%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 10        | 5.65%   |
| AMD 400 Series Chipset SATA Controller                                           | 7         | 3.95%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 6         | 3.39%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 6         | 3.39%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 5         | 2.82%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 5         | 2.82%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 4         | 2.26%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 4         | 2.26%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 4         | 2.26%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 1.69%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 3         | 1.69%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 3         | 1.69%   |
| SK Hynix Gold P31 SSD                                                            | 2         | 1.13%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 2         | 1.13%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 1.13%   |
| Realtek Realtek Non-Volatile memory controller                                   | 2         | 1.13%   |
| Nvidia MCP61 SATA Controller                                                     | 2         | 1.13%   |
| Nvidia MCP61 IDE                                                                 | 2         | 1.13%   |
| Intel SSD 600P Series                                                            | 2         | 1.13%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 1.13%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 2         | 1.13%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 2         | 1.13%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 2         | 1.13%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                              | 2         | 1.13%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 2         | 1.13%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 2         | 1.13%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 1.13%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2         | 1.13%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 2         | 1.13%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 2         | 1.13%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 2         | 1.13%   |
| Yangtze Memory Non-Volatile memory controller                                    | 1         | 0.56%   |
| SK Hynix BC511                                                                   | 1         | 0.56%   |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller                 | 1         | 0.56%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 0.56%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 0.56%   |
| Samsung Electronics SATA controller                                              | 1         | 0.56%   |
| Samsung Apple PCIe SSD                                                           | 1         | 0.56%   |
| Phison NVMe Storage Controller                                                   | 1         | 0.56%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 1         | 0.56%   |
| Nvidia MCP79 AHCI Controller                                                     | 1         | 0.56%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1         | 0.56%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                     | 1         | 0.56%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller with HyperDuo            | 1         | 0.56%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller                          | 1         | 0.56%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                            | 1         | 0.56%   |
| KIOXIA Non-Volatile memory controller                                            | 1         | 0.56%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 0.56%   |
| JMicron JMB58x AHCI SATA controller                                              | 1         | 0.56%   |
| JMicron JMB368 IDE controller                                                    | 1         | 0.56%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 1         | 0.56%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 1         | 0.56%   |
| Intel SATA Controller [RAID mode]                                                | 1         | 0.56%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 1         | 0.56%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 0.56%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 0.56%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 0.56%   |
| Intel C608 chipset Dual 4-Port SATA/SAS Storage Control Unit                     | 1         | 0.56%   |
| Intel C600/X79 series chipset IDE-r Controller                                   | 1         | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 84        | 57.93%  |
| NVMe | 33        | 22.76%  |
| IDE  | 13        | 8.97%   |
| RAID | 9         | 6.21%   |
| SAS  | 4         | 2.76%   |
| SCSI | 2         | 1.38%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 82        | 73.87%  |
| AMD    | 27        | 24.32%  |
| ARM    | 2         | 1.8%    |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 3         | 2.7%    |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz            | 2         | 1.8%    |
| Intel Core i7-4790K CPU @ 4.00GHz             | 2         | 1.8%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1.8%    |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 1.8%    |
| Intel Celeron CPU N3060 @ 1.60GHz             | 2         | 1.8%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 1.8%    |
| ARM Processor                                 | 2         | 1.8%    |
| AMD Ryzen 7 3800X 8-Core Processor            | 2         | 1.8%    |
| AMD Ryzen 5 3600 6-Core Processor             | 2         | 1.8%    |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 2         | 1.8%    |
| AMD FX-8350 Eight-Core Processor              | 2         | 1.8%    |
| Intel Xeon CPU X5680 @ 3.33GHz                | 1         | 0.9%    |
| Intel Xeon CPU X3450 @ 2.67GHz                | 1         | 0.9%    |
| Intel Xeon CPU E5-2697 v3 @ 2.60GHz           | 1         | 0.9%    |
| Intel Xeon CPU E5-2667 v2 @ 3.30GHz           | 1         | 0.9%    |
| Intel Xeon CPU E5-2660 v3 @ 2.60GHz           | 1         | 0.9%    |
| Intel Xeon CPU E5-2620 0 @ 2.00GHz            | 1         | 0.9%    |
| Intel Xeon CPU E5-1650 0 @ 3.20GHz            | 1         | 0.9%    |
| Intel Xeon CPU E3-1246 v3 @ 3.50GHz           | 1         | 0.9%    |
| Intel Xeon CPU 5160 @ 3.00GHz                 | 1         | 0.9%    |
| Intel Pentium Gold G5420 CPU @ 3.80GHz        | 1         | 0.9%    |
| Intel Pentium Dual CPU E2140 @ 1.60GHz        | 1         | 0.9%    |
| Intel Pentium CPU P6100 @ 2.00GHz             | 1         | 0.9%    |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.9%    |
| Intel Pentium CPU G640 @ 2.80GHz              | 1         | 0.9%    |
| Intel Pentium CPU G4560 @ 3.50GHz             | 1         | 0.9%    |
| Intel Pentium CPU 2020M @ 2.40GHz             | 1         | 0.9%    |
| Intel Core M-5Y51 CPU @ 1.10GHz               | 1         | 0.9%    |
| Intel Core i7-9700 CPU @ 3.00GHz              | 1         | 0.9%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 0.9%    |
| Intel Core i7-7700 CPU @ 3.60GHz              | 1         | 0.9%    |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 0.9%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 0.9%    |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 0.9%    |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 0.9%    |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 0.9%    |
| Intel Core i7-3930K CPU @ 3.20GHz             | 1         | 0.9%    |
| Intel Core i7-3840QM CPU @ 2.80GHz            | 1         | 0.9%    |
| Intel Core i7-3720QM CPU @ 2.60GHz            | 1         | 0.9%    |
| Intel Core i7-2860QM CPU @ 2.50GHz            | 1         | 0.9%    |
| Intel Core i7-10870H CPU @ 2.20GHz            | 1         | 0.9%    |
| Intel Core i7-10710U CPU @ 1.10GHz            | 1         | 0.9%    |
| Intel Core i5-9400 CPU @ 2.90GHz              | 1         | 0.9%    |
| Intel Core i5-8600K CPU @ 3.60GHz             | 1         | 0.9%    |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 0.9%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 0.9%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 0.9%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 0.9%    |
| Intel Core i5-5300U CPU @ 2.30GHz             | 1         | 0.9%    |
| Intel Core i5-4690 CPU @ 3.50GHz              | 1         | 0.9%    |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 0.9%    |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 0.9%    |
| Intel Core i5-3470 CPU @ 3.20GHz              | 1         | 0.9%    |
| Intel Core i5-3360M CPU @ 2.80GHz             | 1         | 0.9%    |
| Intel Core i5-3330 CPU @ 3.00GHz              | 1         | 0.9%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 0.9%    |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 0.9%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 0.9%    |
| Intel Core i5-2430M CPU @ 2.40GHz             | 1         | 0.9%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model              | Computers | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 19        | 17.12%  |
| Intel Core i7      | 18        | 16.22%  |
| Intel Xeon         | 11        | 9.91%   |
| Other              | 9         | 8.11%   |
| AMD Ryzen 5        | 8         | 7.21%   |
| Intel Core i3      | 7         | 6.31%   |
| Intel Pentium      | 5         | 4.5%    |
| Intel Celeron      | 4         | 3.6%    |
| AMD Ryzen 7        | 4         | 3.6%    |
| AMD FX             | 4         | 3.6%    |
| Intel Core 2 Duo   | 3         | 2.7%    |
| AMD Ryzen 9        | 3         | 2.7%    |
| Intel Core 2 Quad  | 2         | 1.8%    |
| Intel Atom         | 2         | 1.8%    |
| Intel Pentium Gold | 1         | 0.9%    |
| Intel Pentium Dual | 1         | 0.9%    |
| Intel Core M       | 1         | 0.9%    |
| Intel Core 2       | 1         | 0.9%    |
| AMD Ryzen Embedded | 1         | 0.9%    |
| AMD GX             | 1         | 0.9%    |
| AMD EPYC           | 1         | 0.9%    |
| AMD Athlon 64 X2   | 1         | 0.9%    |
| AMD Athlon         | 1         | 0.9%    |
| AMD A8             | 1         | 0.9%    |
| AMD A4             | 1         | 0.9%    |
| AMD A10            | 1         | 0.9%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 39        | 35.14%  |
| 4      | 38        | 34.23%  |
| 8      | 13        | 11.71%  |
| 6      | 10        | 9.01%   |
| 16     | 4         | 3.6%    |
| 12     | 2         | 1.8%    |
| 1      | 2         | 1.8%    |
| 14     | 1         | 0.9%    |
| 10     | 1         | 0.9%    |
| 3      | 1         | 0.9%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 104       | 93.69%  |
| 2      | 7         | 6.31%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 83        | 74.77%  |
| 1      | 28        | 25.23%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 108       | 97.3%   |
| Unknown        | 2         | 1.8%    |
| 32-bit         | 1         | 0.9%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 22        | 19.82%  |
| 0x306a9    | 9         | 8.11%   |
| 0x306d4    | 4         | 3.6%    |
| 0x306c3    | 4         | 3.6%    |
| 0x206d7    | 4         | 3.6%    |
| 0x806ea    | 3         | 2.7%    |
| 0x806d1    | 3         | 2.7%    |
| 0x806c1    | 3         | 2.7%    |
| 0x406e3    | 3         | 2.7%    |
| 0x406c4    | 3         | 2.7%    |
| 0x206a7    | 3         | 2.7%    |
| 0x1067a    | 3         | 2.7%    |
| 0x08108109 | 3         | 2.7%    |
| 0x906ed    | 2         | 1.8%    |
| 0x906ea    | 2         | 1.8%    |
| 0x806ec    | 2         | 1.8%    |
| 0x6fd      | 2         | 1.8%    |
| 0x306f2    | 2         | 1.8%    |
| 0x106c2    | 2         | 1.8%    |
| 0x08701021 | 2         | 1.8%    |
| 0x08701013 | 2         | 1.8%    |
| 0x0810100b | 2         | 1.8%    |
| 0x06001119 | 2         | 1.8%    |
| 0x06000822 | 2         | 1.8%    |
| 0xa0671    | 1         | 0.9%    |
| 0xa0660    | 1         | 0.9%    |
| 0xa0653    | 1         | 0.9%    |
| 0xa0652    | 1         | 0.9%    |
| 0x906e9    | 1         | 0.9%    |
| 0x806e9    | 1         | 0.9%    |
| 0x706a1    | 1         | 0.9%    |
| 0x6fa      | 1         | 0.9%    |
| 0x506e3    | 1         | 0.9%    |
| 0x40651    | 1         | 0.9%    |
| 0x306e4    | 1         | 0.9%    |
| 0x206c2    | 1         | 0.9%    |
| 0x20655    | 1         | 0.9%    |
| 0x106e5    | 1         | 0.9%    |
| 0x0a201016 | 1         | 0.9%    |
| 0x08600106 | 1         | 0.9%    |
| 0x0830104d | 1         | 0.9%    |
| 0x08001138 | 1         | 0.9%    |
| 0x07030105 | 1         | 0.9%    |
| 0x07000110 | 1         | 0.9%    |
| 0x06000852 | 1         | 0.9%    |
| 0x00000000 | 1         | 0.9%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 16        | 14.41%  |
| IvyBridge     | 10        | 9.01%   |
| Haswell       | 10        | 9.01%   |
| Zen 2         | 9         | 8.11%   |
| SandyBridge   | 8         | 7.21%   |
| Piledriver    | 6         | 5.41%   |
| Skylake       | 5         | 4.5%    |
| Core          | 5         | 4.5%    |
| Zen+          | 4         | 3.6%    |
| Zen           | 4         | 3.6%    |
| Silvermont    | 4         | 3.6%    |
| Icelake       | 4         | 3.6%    |
| Broadwell     | 4         | 3.6%    |
| Westmere      | 3         | 2.7%    |
| TigerLake     | 3         | 2.7%    |
| Penryn        | 3         | 2.7%    |
| CometLake     | 3         | 2.7%    |
| Bonnell       | 2         | 1.8%    |
| Unknown       | 2         | 1.8%    |
| Zen 3         | 1         | 0.9%    |
| Puma          | 1         | 0.9%    |
| Nehalem       | 1         | 0.9%    |
| K8 Hammer     | 1         | 0.9%    |
| Jaguar        | 1         | 0.9%    |
| Goldmont plus | 1         | 0.9%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 53        | 44.54%  |
| Nvidia                     | 32        | 26.89%  |
| AMD                        | 31        | 26.05%  |
| Matrox Electronics Systems | 3         | 2.52%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 5         | 4.1%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 3.28%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 3.28%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 3.28%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 3.28%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 3         | 2.46%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 3         | 2.46%   |
| Intel UHD Graphics 620                                                                   | 3         | 2.46%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 2.46%   |
| Intel HD Graphics 620                                                                    | 3         | 2.46%   |
| Intel HD Graphics 5500                                                                   | 3         | 2.46%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 2.46%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 2.46%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 1.64%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 1.64%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 2         | 1.64%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 1.64%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.64%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 1.64%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 1.64%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2         | 1.64%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 1.64%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 1.64%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 2         | 1.64%   |
| AMD Renoir                                                                               | 2         | 1.64%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 2         | 1.64%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1         | 0.82%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 1         | 0.82%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 0.82%   |
| Nvidia GP107GL [Quadro P1000]                                                            | 1         | 0.82%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 0.82%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 1         | 0.82%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1         | 0.82%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1         | 0.82%   |
| Nvidia GM204GLM [Quadro M3000M]                                                          | 1         | 0.82%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1         | 0.82%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1         | 0.82%   |
| Nvidia GK110GL [Quadro K5200]                                                            | 1         | 0.82%   |
| Nvidia GK107M [GeForce GT 745M]                                                          | 1         | 0.82%   |
| Nvidia GK107 [GeForce GT 640]                                                            | 1         | 0.82%   |
| Nvidia GK104GL [Quadro K5000]                                                            | 1         | 0.82%   |
| Nvidia GF106GLM [Quadro 2000M]                                                           | 1         | 0.82%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 0.82%   |
| Nvidia G84 [GeForce 8600 GT]                                                             | 1         | 0.82%   |
| Nvidia G80GL [Quadro FX 4600]                                                            | 1         | 0.82%   |
| Nvidia G71GL [Quadro FX 1500]                                                            | 1         | 0.82%   |
| Nvidia C79 [ION]                                                                         | 1         | 0.82%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 1         | 0.82%   |
| Matrox Electronics Systems MGA G200eH3                                                   | 1         | 0.82%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller                 | 1         | 0.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1         | 0.82%   |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller                           | 1         | 0.82%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1         | 0.82%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 1         | 0.82%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 0.82%   |
| Intel HD Graphics 5300                                                                   | 1         | 0.82%   |
| Intel HD Graphics 530                                                                    | 1         | 0.82%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 0.82%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1         | 0.82%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 0.82%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 45        | 40.54%  |
| 1 x AMD        | 29        | 26.13%  |
| 1 x Nvidia     | 20        | 18.02%  |
| Intel + Nvidia | 8         | 7.21%   |
| Other          | 3         | 2.7%    |
| 1 x Matrox     | 3         | 2.7%    |
| AMD + Nvidia   | 2         | 1.8%    |
| 2 x Nvidia     | 1         | 0.9%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 85        | 76.58%  |
| Proprietary | 16        | 14.41%  |
| Unknown     | 10        | 9.01%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 61        | 54.46%  |
| 0.51-1.0   | 13        | 11.61%  |
| 1.01-2.0   | 11        | 9.82%   |
| 7.01-8.0   | 7         | 6.25%   |
| 3.01-4.0   | 7         | 6.25%   |
| 0.01-0.5   | 6         | 5.36%   |
| 5.01-6.0   | 4         | 3.57%   |
| 8.01-16.0  | 2         | 1.79%   |
| 2.01-3.0   | 1         | 0.89%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Samsung Electronics  | 13        | 11.3%   |
| BOE                  | 12        | 10.43%  |
| LG Display           | 11        | 9.57%   |
| Chimei Innolux       | 9         | 7.83%   |
| AU Optronics         | 8         | 6.96%   |
| Hewlett-Packard      | 7         | 6.09%   |
| Dell                 | 6         | 5.22%   |
| Goldstar             | 5         | 4.35%   |
| BenQ                 | 5         | 4.35%   |
| Sharp                | 4         | 3.48%   |
| Ancor Communications | 4         | 3.48%   |
| Acer                 | 4         | 3.48%   |
| Lenovo               | 3         | 2.61%   |
| ViewSonic            | 2         | 1.74%   |
| Iiyama               | 2         | 1.74%   |
| ASUSTek Computer     | 2         | 1.74%   |
| Xiaomi               | 1         | 0.87%   |
| Wacom                | 1         | 0.87%   |
| Unknown              | 1         | 0.87%   |
| UGD                  | 1         | 0.87%   |
| Toshiba              | 1         | 0.87%   |
| Sony                 | 1         | 0.87%   |
| PANDA                | 1         | 0.87%   |
| Panasonic            | 1         | 0.87%   |
| ONN                  | 1         | 0.87%   |
| NEC Computers        | 1         | 0.87%   |
| JVC                  | 1         | 0.87%   |
| IOD                  | 1         | 0.87%   |
| Gigabyte Technology  | 1         | 0.87%   |
| GDH                  | 1         | 0.87%   |
| Eizo                 | 1         | 0.87%   |
| DPC                  | 1         | 0.87%   |
| Apple                | 1         | 0.87%   |
| AOC                  | 1         | 0.87%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 2         | 1.69%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch        | 2         | 1.69%   |
| Xiaomi Mi TV XMD009A 3440x1440 480x270mm 21.7-inch                   | 1         | 0.85%   |
| Wacom Cintiq 22HDT WAC1037 1920x1080 476x268mm 21.5-inch             | 1         | 0.85%   |
| ViewSonic LCD Monitor VX2276 Series 1920x1080                        | 1         | 0.85%   |
| ViewSonic LCD Monitor VA2448 SERIES 1920x1080                        | 1         | 0.85%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch            | 1         | 0.85%   |
| UGD LCD Monitor UGD1302 1920x1080 290x160mm 13.0-inch                | 1         | 0.85%   |
| Toshiba TV TSB0206 1920x1080 886x498mm 40.0-inch                     | 1         | 0.85%   |
| Sony TV SNY8102 1360x768 1600x900mm 72.3-inch                        | 1         | 0.85%   |
| Sharp LQ173M1JW05 SHP14EC 1920x1080 380x210mm 17.1-inch              | 1         | 0.85%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch              | 1         | 0.85%   |
| Sharp LQ125T1JW02 SHP142F 2560x1440 277x155mm 12.5-inch              | 1         | 0.85%   |
| Sharp LCD Monitor SHP14C4 1920x1080 344x194mm 15.5-inch              | 1         | 0.85%   |
| Samsung Electronics SyncMaster SAM0578 1920x1080 476x268mm 21.5-inch | 1         | 0.85%   |
| Samsung Electronics SyncMaster SAM04DF 1360x768 410x230mm 18.5-inch  | 1         | 0.85%   |
| Samsung Electronics SyncMaster SAM0428 1680x1050 459x296mm 21.5-inch | 1         | 0.85%   |
| Samsung Electronics SyncMaster SAM0248 1280x1024 376x301mm 19.0-inch | 1         | 0.85%   |
| Samsung Electronics SyncMaster SAM01AD 1600x1200 408x306mm 20.1-inch | 1         | 0.85%   |
| Samsung Electronics SMS27A650 SAM082D 1920x1080 600x340mm 27.2-inch  | 1         | 0.85%   |
| Samsung Electronics SMS19A100 SAM0867 1366x768 410x230mm 18.5-inch   | 1         | 0.85%   |
| Samsung Electronics SMB2430L SAM0644 1920x1080 521x293mm 23.5-inch   | 1         | 0.85%   |
| Samsung Electronics SM2333T SAM0736 1920x1080 477x268mm 21.5-inch    | 1         | 0.85%   |
| Samsung Electronics S24D390 SAM0B65 1920x1080 521x293mm 23.5-inch    | 1         | 0.85%   |
| Samsung Electronics S22D300 SAM0B3E 1920x1080 477x268mm 21.5-inch    | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch | 1         | 0.85%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch              | 1         | 0.85%   |
| Panasonic VVX16T029D00 MEI96A2 2880x1620 344x193mm 15.5-inch         | 1         | 0.85%   |
| ONN 100002480 ONN0101 1920x1080 470x290mm 21.7-inch                  | 1         | 0.85%   |
| NEC Computers LCD2490WUXi NEC66CE 1920x1200 518x324mm 24.1-inch      | 1         | 0.85%   |
| LG Display LCD Monitor LGD0625 1920x1080 344x194mm 15.5-inch         | 1         | 0.85%   |
| LG Display LCD Monitor LGD0599 1920x1080 309x174mm 14.0-inch         | 1         | 0.85%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch         | 1         | 0.85%   |
| LG Display LCD Monitor LGD0508 1366x768 309x174mm 14.0-inch          | 1         | 0.85%   |
| LG Display LCD Monitor LGD03D7 1366x768 310x174mm 14.0-inch          | 1         | 0.85%   |
| LG Display LCD Monitor LGD0353 1366x768 345x194mm 15.6-inch          | 1         | 0.85%   |
| LG Display LCD Monitor LGD032C 1920x1080 344x194mm 15.5-inch         | 1         | 0.85%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch          | 1         | 0.85%   |
| LG Display LCD Monitor LGD02D9 1920x1080 344x194mm 15.5-inch         | 1         | 0.85%   |
| LG Display LCD Monitor LGD028A 1366x768 344x194mm 15.5-inch          | 1         | 0.85%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch          | 1         | 0.85%   |
| Lenovo LEN L171 LEN24C9 1280x1024 337x270mm 17.0-inch                | 1         | 0.85%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch             | 1         | 0.85%   |
| Lenovo LCD Monitor LEN4035 1280x800 303x190mm 14.1-inch              | 1         | 0.85%   |
| JVC FPDEUFT3 JVC21BE 1920x540                                        | 1         | 0.85%   |
| IOD LCD-GL211X IOD151D 1920x1080 458x258mm 20.7-inch                 | 1         | 0.85%   |
| Iiyama PLE2207WS IVM5609 1680x1050 474x296mm 22.0-inch               | 1         | 0.85%   |
| Iiyama PL2783Q IVM661F 2560x1440 597x336mm 27.0-inch                 | 1         | 0.85%   |
| Hewlett-Packard ZR2740w HWP2957 2560x1440 597x336mm 27.0-inch        | 1         | 0.85%   |
| Hewlett-Packard P223 HPN3392 1920x1080 477x268mm 21.5-inch           | 1         | 0.85%   |
| Hewlett-Packard LE1851w HWP2840 1366x768 413x234mm 18.7-inch         | 1         | 0.85%   |
| Hewlett-Packard ALL-in-One HPN4021 1920x1080 476x268mm 21.5-inch     | 1         | 0.85%   |
| Hewlett-Packard 27w HPN3494 1920x1080 598x336mm 27.0-inch            | 1         | 0.85%   |
| Hewlett-Packard 27m HPN3579 1920x1080 598x336mm 27.0-inch            | 1         | 0.85%   |
| Hewlett-Packard 2309 HWP2823 1920x1080 510x287mm 23.0-inch           | 1         | 0.85%   |
| Goldstar W2242 GSM5678 1680x1050 474x296mm 22.0-inch                 | 1         | 0.85%   |
| Goldstar W2242 GSM5677 1680x1050 474x296mm 22.0-inch                 | 1         | 0.85%   |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                  | 1         | 0.85%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 54        | 48.21%  |
| 1366x768 (WXGA)    | 23        | 20.54%  |
| 1280x1024 (SXGA)   | 6         | 5.36%   |
| 3840x2160 (4K)     | 5         | 4.46%   |
| 2560x1440 (QHD)    | 5         | 4.46%   |
| 1680x1050 (WSXGA+) | 4         | 3.57%   |
| 1920x1200 (WUXGA)  | 3         | 2.68%   |
| 1600x900 (HD+)     | 3         | 2.68%   |
| 3440x1440          | 2         | 1.79%   |
| 1360x768           | 2         | 1.79%   |
| 2288x1287          | 1         | 0.89%   |
| 2256x1504          | 1         | 0.89%   |
| 1920x540           | 1         | 0.89%   |
| 1600x1200          | 1         | 0.89%   |
| 1280x800 (WXGA)    | 1         | 0.89%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 27        | 23.28%  |
| 21      | 13        | 11.21%  |
| 27      | 10        | 8.62%   |
| 24      | 10        | 8.62%   |
| 17      | 9         | 7.76%   |
| 14      | 9         | 7.76%   |
| 13      | 8         | 6.9%    |
| 23      | 6         | 5.17%   |
| 20      | 4         | 3.45%   |
| Unknown | 4         | 3.45%   |
| 18      | 3         | 2.59%   |
| 12      | 3         | 2.59%   |
| 19      | 2         | 1.72%   |
| 142     | 1         | 0.86%   |
| 74      | 1         | 0.86%   |
| 72      | 1         | 0.86%   |
| 52      | 1         | 0.86%   |
| 34      | 1         | 0.86%   |
| 32      | 1         | 0.86%   |
| 22      | 1         | 0.86%   |
| 16      | 1         | 0.86%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 44        | 38.26%  |
| 501-600        | 24        | 20.87%  |
| 401-500        | 21        | 18.26%  |
| 351-400        | 9         | 7.83%   |
| 201-300        | 6         | 5.22%   |
| Unknown        | 4         | 3.48%   |
| 701-800        | 2         | 1.74%   |
| 1501-2000      | 2         | 1.74%   |
| More than 2000 | 1         | 0.87%   |
| 601-700        | 1         | 0.87%   |
| 1001-1500      | 1         | 0.87%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 80        | 76.19%  |
| 16/10   | 9         | 8.57%   |
| 5/4     | 4         | 3.81%   |
| 3/2     | 3         | 2.86%   |
| Unknown | 3         | 2.86%   |
| 6/5     | 2         | 1.9%    |
| 4/3     | 1         | 0.95%   |
| 32/9    | 1         | 0.95%   |
| 21/9    | 1         | 0.95%   |
| 1.00    | 1         | 0.95%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 28        | 24.56%  |
| 201-250        | 21        | 18.42%  |
| 81-90          | 15        | 13.16%  |
| 301-350        | 10        | 8.77%   |
| 151-200        | 8         | 7.02%   |
| 141-150        | 7         | 6.14%   |
| 251-300        | 5         | 4.39%   |
| 121-130        | 5         | 4.39%   |
| More than 1000 | 4         | 3.51%   |
| Unknown        | 4         | 3.51%   |
| 61-70          | 3         | 2.63%   |
| 71-80          | 2         | 1.75%   |
| 351-500        | 2         | 1.75%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 38        | 33.04%  |
| 101-120       | 34        | 29.57%  |
| 121-160       | 29        | 25.22%  |
| 1-50          | 4         | 3.48%   |
| Unknown       | 4         | 3.48%   |
| More than 240 | 3         | 2.61%   |
| 161-240       | 3         | 2.61%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 83        | 74.77%  |
| 2     | 13        | 11.71%  |
| 0     | 11        | 9.91%   |
| 3     | 3         | 2.7%    |
| 4     | 1         | 0.9%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 65        | 40.37%  |
| Realtek Semiconductor    | 55        | 34.16%  |
| Qualcomm Atheros         | 12        | 7.45%   |
| Broadcom                 | 7         | 4.35%   |
| Ralink Technology        | 4         | 2.48%   |
| Broadcom Limited         | 3         | 1.86%   |
| TP-Link                  | 2         | 1.24%   |
| Nvidia                   | 2         | 1.24%   |
| ASIX Electronics         | 2         | 1.24%   |
| VIA Technologies         | 1         | 0.62%   |
| Sierra Wireless          | 1         | 0.62%   |
| Ralink                   | 1         | 0.62%   |
| Micro Star International | 1         | 0.62%   |
| Mellanox Technologies    | 1         | 0.62%   |
| Marvell Technology Group | 1         | 0.62%   |
| Hewlett-Packard          | 1         | 0.62%   |
| Dell                     | 1         | 0.62%   |
| Chelsio Communications   | 1         | 0.62%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 39        | 19.7%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 8         | 4.04%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 6         | 3.03%   |
| Intel I211 Gigabit Network Connection                                                 | 5         | 2.53%   |
| Intel 82574L Gigabit Network Connection                                               | 5         | 2.53%   |
| Ralink MT7601U Wireless Adapter                                                       | 4         | 2.02%   |
| Intel Wireless-AC 9260                                                                | 4         | 2.02%   |
| Intel Wireless 8265 / 8275                                                            | 4         | 2.02%   |
| Intel Ethernet Connection (2) I218-V                                                  | 4         | 2.02%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 3         | 1.52%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 3         | 1.52%   |
| Intel Wireless 7265                                                                   | 3         | 1.52%   |
| Intel Wireless 7260                                                                   | 3         | 1.52%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 3         | 1.52%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 3         | 1.52%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                              | 2         | 1.01%   |
| Realtek Killer E3000 2.5GbE Controller                                                | 2         | 1.01%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 2         | 1.01%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                             | 2         | 1.01%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                      | 2         | 1.01%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                        | 2         | 1.01%   |
| Intel Wireless 8260                                                                   | 2         | 1.01%   |
| Intel Wireless 3160                                                                   | 2         | 1.01%   |
| Intel Wi-Fi 6 AX201                                                                   | 2         | 1.01%   |
| Intel Wi-Fi 6 AX200                                                                   | 2         | 1.01%   |
| Intel Tiger Lake PCH CNVi WiFi                                                        | 2         | 1.01%   |
| Intel Ethernet Connection I217-V                                                      | 2         | 1.01%   |
| Intel Ethernet Connection (7) I219-V                                                  | 2         | 1.01%   |
| Intel Ethernet Connection (4) I219-LM                                                 | 2         | 1.01%   |
| Intel Ethernet Connection (3) I218-LM                                                 | 2         | 1.01%   |
| Intel Ethernet Connection (2) I219-LM                                                 | 2         | 1.01%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 2         | 1.01%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 2         | 1.01%   |
| Intel Centrino Ultimate-N 6300                                                        | 2         | 1.01%   |
| Intel 82579V Gigabit Network Connection                                               | 2         | 1.01%   |
| VIA VT6105/VT6106S [Rhine-III]                                                        | 1         | 0.51%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                                                 | 1         | 0.51%   |
| TP-Link 802.11ac WLAN Adapter                                                         | 1         | 0.51%   |
| Sierra Wireless EM7305                                                                | 1         | 0.51%   |
| Realtek USB 10/100/1G/2.5G LAN                                                        | 1         | 0.51%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 1         | 0.51%   |
| Realtek RTL8723DE Wireless Network Adapter                                            | 1         | 0.51%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                       | 1         | 0.51%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1         | 0.51%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                               | 1         | 0.51%   |
| Realtek RTL8125 2.5GbE Controller                                                     | 1         | 0.51%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                 | 1         | 0.51%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                             | 1         | 0.51%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                             | 1         | 0.51%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 1         | 0.51%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                        | 1         | 0.51%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 1         | 0.51%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                      | 1         | 0.51%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                         | 1         | 0.51%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 0.51%   |
| Nvidia MCP79 Ethernet                                                                 | 1         | 0.51%   |
| Nvidia MCP61 Ethernet                                                                 | 1         | 0.51%   |
| Micro Star International MS-3871 802.11bgn Wireless Module [Ralink RT8070]            | 1         | 0.51%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]                                 | 1         | 0.51%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                               | 1         | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 43        | 55.84%  |
| Realtek Semiconductor    | 11        | 14.29%  |
| Qualcomm Atheros         | 9         | 11.69%  |
| Ralink Technology        | 4         | 5.19%   |
| Broadcom                 | 3         | 3.9%    |
| TP-Link                  | 2         | 2.6%    |
| Sierra Wireless          | 1         | 1.3%    |
| Ralink                   | 1         | 1.3%    |
| Micro Star International | 1         | 1.3%    |
| Dell                     | 1         | 1.3%    |
| Broadcom Limited         | 1         | 1.3%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Ralink MT7601U Wireless Adapter                                                       | 4         | 5.19%   |
| Intel Wireless-AC 9260                                                                | 4         | 5.19%   |
| Intel Wireless 8265 / 8275                                                            | 4         | 5.19%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 3         | 3.9%    |
| Realtek RTL8188EE Wireless Network Adapter                                            | 3         | 3.9%    |
| Intel Wireless 7265                                                                   | 3         | 3.9%    |
| Intel Wireless 7260                                                                   | 3         | 3.9%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 3         | 3.9%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 3         | 3.9%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 2         | 2.6%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                      | 2         | 2.6%    |
| Intel Wireless 8260                                                                   | 2         | 2.6%    |
| Intel Wireless 3160                                                                   | 2         | 2.6%    |
| Intel Wi-Fi 6 AX201                                                                   | 2         | 2.6%    |
| Intel Wi-Fi 6 AX200                                                                   | 2         | 2.6%    |
| Intel Tiger Lake PCH CNVi WiFi                                                        | 2         | 2.6%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 2         | 2.6%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 2         | 2.6%    |
| Intel Centrino Ultimate-N 6300                                                        | 2         | 2.6%    |
| TP-Link RTL8812AU Archer T4U 802.11ac                                                 | 1         | 1.3%    |
| TP-Link 802.11ac WLAN Adapter                                                         | 1         | 1.3%    |
| Sierra Wireless EM7305                                                                | 1         | 1.3%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 1         | 1.3%    |
| Realtek RTL8723DE Wireless Network Adapter                                            | 1         | 1.3%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                       | 1         | 1.3%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1         | 1.3%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                               | 1         | 1.3%    |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                             | 1         | 1.3%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 1         | 1.3%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                        | 1         | 1.3%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 1         | 1.3%    |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                      | 1         | 1.3%    |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 1.3%    |
| Micro Star International MS-3871 802.11bgn Wireless Module [Ralink RT8070]            | 1         | 1.3%    |
| Intel Wireless 3165                                                                   | 1         | 1.3%    |
| Intel WiFi Link 5100                                                                  | 1         | 1.3%    |
| Intel Gemini Lake PCH CNVi WiFi                                                       | 1         | 1.3%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 1         | 1.3%    |
| Intel Comet Lake PCH CNVi WiFi                                                        | 1         | 1.3%    |
| Intel Centrino Wireless-N 2230                                                        | 1         | 1.3%    |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 1         | 1.3%    |
| Dell DW5811e Snapdragonâ¢ X7 LTE                                                  | 1         | 1.3%    |
| Broadcom Limited BCM43228 802.11a/b/g/n                                               | 1         | 1.3%    |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 1         | 1.3%    |
| Broadcom BCM4321 802.11a/b/g/n                                                        | 1         | 1.3%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 1         | 1.3%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 52        | 46.85%  |
| Intel                    | 38        | 34.23%  |
| Qualcomm Atheros         | 6         | 5.41%   |
| Broadcom                 | 5         | 4.5%    |
| Nvidia                   | 2         | 1.8%    |
| Broadcom Limited         | 2         | 1.8%    |
| ASIX Electronics         | 2         | 1.8%    |
| VIA Technologies         | 1         | 0.9%    |
| Mellanox Technologies    | 1         | 0.9%    |
| Marvell Technology Group | 1         | 0.9%    |
| Chelsio Communications   | 1         | 0.9%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 39        | 32.5%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 8         | 6.67%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 6         | 5%      |
| Intel I211 Gigabit Network Connection                                         | 5         | 4.17%   |
| Intel 82574L Gigabit Network Connection                                       | 5         | 4.17%   |
| Intel Ethernet Connection (2) I218-V                                          | 4         | 3.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 2         | 1.67%   |
| Realtek Killer E3000 2.5GbE Controller                                        | 2         | 1.67%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 2         | 1.67%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 2         | 1.67%   |
| Intel Ethernet Connection I217-V                                              | 2         | 1.67%   |
| Intel Ethernet Connection (7) I219-V                                          | 2         | 1.67%   |
| Intel Ethernet Connection (4) I219-LM                                         | 2         | 1.67%   |
| Intel Ethernet Connection (3) I218-LM                                         | 2         | 1.67%   |
| Intel Ethernet Connection (2) I219-LM                                         | 2         | 1.67%   |
| Intel 82579V Gigabit Network Connection                                       | 2         | 1.67%   |
| VIA VT6105/VT6106S [Rhine-III]                                                | 1         | 0.83%   |
| Realtek USB 10/100/1G/2.5G LAN                                                | 1         | 0.83%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1         | 0.83%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1         | 0.83%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1         | 0.83%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1         | 0.83%   |
| Nvidia MCP79 Ethernet                                                         | 1         | 0.83%   |
| Nvidia MCP61 Ethernet                                                         | 1         | 0.83%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]                         | 1         | 0.83%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                       | 1         | 0.83%   |
| Intel I350 Gigabit Network Connection                                         | 1         | 0.83%   |
| Intel Ethernet Connection I219-LM                                             | 1         | 0.83%   |
| Intel Ethernet Connection I218-V                                              | 1         | 0.83%   |
| Intel Ethernet Connection (4) I219-V                                          | 1         | 0.83%   |
| Intel Ethernet Connection (2) I219-V                                          | 1         | 0.83%   |
| Intel Ethernet Connection (2) I218-LM                                         | 1         | 0.83%   |
| Intel Ethernet Connection (12) I219-V                                         | 1         | 0.83%   |
| Intel Ethernet Connection (10) I219-V                                         | 1         | 0.83%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 1         | 0.83%   |
| Intel 82576 Gigabit Network Connection                                        | 1         | 0.83%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 0.83%   |
| Intel 82567LM Gigabit Network Connection                                      | 1         | 0.83%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                          | 1         | 0.83%   |
| Chelsio T320 10GbE Dual Port Adapter                                          | 1         | 0.83%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                             | 1         | 0.83%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                             | 1         | 0.83%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                       | 1         | 0.83%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                       | 1         | 0.83%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 1         | 0.83%   |
| Broadcom Limited NetXtreme BCM5756ME Gigabit Ethernet PCI Express             | 1         | 0.83%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express               | 1         | 0.83%   |
| ASIX AX88772B                                                                 | 1         | 0.83%   |
| ASIX AX88179 Gigabit Ethernet                                                 | 1         | 0.83%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 103       | 57.87%  |
| WiFi     | 74        | 41.57%  |
| Modem    | 1         | 0.56%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 62        | 56.36%  |
| WiFi     | 48        | 43.64%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 64        | 57.14%  |
| 1     | 35        | 31.25%  |
| 4     | 4         | 3.57%   |
| 3     | 4         | 3.57%   |
| 0     | 4         | 3.57%   |
| 5     | 1         | 0.89%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 103       | 91.96%  |
| Yes  | 9         | 8.04%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 37        | 54.41%  |
| Cambridge Silicon Radio         | 12        | 17.65%  |
| Realtek Semiconductor           | 6         | 8.82%   |
| Broadcom                        | 5         | 7.35%   |
| Qualcomm Atheros Communications | 3         | 4.41%   |
| Apple                           | 2         | 2.94%   |
| Toshiba                         | 1         | 1.47%   |
| Micro Star International        | 1         | 1.47%   |
| Foxconn / Hon Hai               | 1         | 1.47%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 16        | 23.53%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 12        | 17.65%  |
| Intel AX201 Bluetooth                               | 6         | 8.82%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 5.88%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 4         | 5.88%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 4.41%   |
| Intel AX210 Bluetooth                               | 3         | 4.41%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 2.94%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 2.94%   |
| Intel AX200 Bluetooth                               | 2         | 2.94%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2         | 2.94%   |
| Toshiba Askey Bluetooth Module                      | 1         | 1.47%   |
| Realtek Bluetooth Radio                             | 1         | 1.47%   |
| Realtek 802.11ac WLAN Adapter                       | 1         | 1.47%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 1.47%   |
| Micro Star International Bluetooth Device           | 1         | 1.47%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.47%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 1.47%   |
| Broadcom HP Portable SoftSailing                    | 1         | 1.47%   |
| Broadcom BCM20702A0                                 | 1         | 1.47%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.47%   |
| Apple Bluetooth USB Host Controller                 | 1         | 1.47%   |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 1         | 1.47%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 74        | 49.33%  |
| AMD                    | 33        | 22%     |
| Nvidia                 | 26        | 17.33%  |
| Creative Labs          | 7         | 4.67%   |
| C-Media Electronics    | 4         | 2.67%   |
| VIA Technologies       | 1         | 0.67%   |
| Texas Instruments      | 1         | 0.67%   |
| M-Audio                | 1         | 0.67%   |
| Generalplus Technology | 1         | 0.67%   |
| EGO SYStems            | 1         | 0.67%   |
| ASUSTek Computer       | 1         | 0.67%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 10        | 5.49%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 9         | 4.95%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 8         | 4.4%    |
| AMD Starship/Matisse HD Audio Controller                                                          | 7         | 3.85%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 7         | 3.85%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 6         | 3.3%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 5         | 2.75%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 4         | 2.2%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 2.2%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 2.2%    |
| Intel Tiger Lake-H HD Audio Controller                                                            | 4         | 2.2%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 2.2%    |
| Intel Broadwell-U Audio Controller                                                                | 4         | 2.2%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 2.2%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 2.2%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 2.2%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 4         | 2.2%    |
| AMD FCH Azalia Controller                                                                         | 4         | 2.2%    |
| Nvidia GA104 High Definition Audio Controller                                                     | 3         | 1.65%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 1.65%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 1.65%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 3         | 1.65%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                                     | 3         | 1.65%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 1.1%    |
| Nvidia MCP61 High Definition Audio                                                                | 2         | 1.1%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 1.1%    |
| Nvidia GM204 High Definition Audio Controller                                                     | 2         | 1.1%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 1.1%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 1.1%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 1.1%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 1.1%    |
| Intel 8 Series HD Audio Controller                                                                | 2         | 1.1%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 1.1%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 1.1%    |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 1.1%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 1.1%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 2         | 1.1%    |
| AMD Navi 10 HDMI Audio                                                                            | 2         | 1.1%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 2         | 1.1%    |
| VIA Technologies VT1720/24 [Envy24PT/HT] PCI Multi-Channel Audio Controller                       | 1         | 0.55%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.55%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.55%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.55%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.55%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.55%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1         | 0.55%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1         | 0.55%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.55%   |
| Nvidia GK110 High Definition Audio Controller                                                     | 1         | 0.55%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.55%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 0.55%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 0.55%   |
| Nvidia Audio device                                                                               | 1         | 0.55%   |
| M-Audio M-Audio MobilePre                                                                         | 1         | 0.55%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 1         | 0.55%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.55%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 0.55%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 1         | 0.55%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 0.55%   |
| Intel 200 Series PCH HD Audio                                                                     | 1         | 0.55%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 24        | 20.34%  |
| Kingston            | 20        | 16.95%  |
| Samsung Electronics | 17        | 14.41%  |
| Crucial             | 11        | 9.32%   |
| Corsair             | 9         | 7.63%   |
| Unknown             | 7         | 5.93%   |
| Micron Technology   | 7         | 5.93%   |
| Transcend           | 2         | 1.69%   |
| Team                | 2         | 1.69%   |
| Ramaxel Technology  | 2         | 1.69%   |
| A-DATA Technology   | 2         | 1.69%   |
| Strontium           | 1         | 0.85%   |
| Smart               | 1         | 0.85%   |
| Silicon Power       | 1         | 0.85%   |
| Neo Forza           | 1         | 0.85%   |
| Nanya Technology    | 1         | 0.85%   |
| HPE                 | 1         | 0.85%   |
| GOODRAM             | 1         | 0.85%   |
| Gloway              | 1         | 0.85%   |
| G.Skill             | 1         | 0.85%   |
| Essencore Limited   | 1         | 0.85%   |
| Elpida              | 1         | 0.85%   |
| Avant               | 1         | 0.85%   |
| AMD                 | 1         | 0.85%   |
| A Force             | 1         | 0.85%   |
| Unknown             | 1         | 0.85%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB DIMM SDRAM                                | 2         | 1.53%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3200MT/s                  | 2         | 1.53%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 1.53%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 2         | 1.53%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                           | 1         | 0.76%   |
| Unknown RAM Module 4096MB DIMM DDR3 65535MT/s                       | 1         | 0.76%   |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s                          | 1         | 0.76%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                              | 1         | 0.76%   |
| Unknown RAM Module 1024MB SODIMM SDRAM                              | 1         | 0.76%   |
| Unknown RAM Module 1024MB DIMM DDR 800MT/s                          | 1         | 0.76%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                              | 1         | 0.76%   |
| Transcend RAM TS256MLQ72V6U 2048MB DIMM DDR2 667MT/s                | 1         | 0.76%   |
| Transcend RAM JM1600KLN-8GK 4096MB DIMM DDR3 1600MT/s               | 1         | 0.76%   |
| Strontium RAM SRT4G86U1-P9H 4096MB DIMM DDR3 1333MT/s               | 1         | 0.76%   |
| Smart RAM SH5641G8FJ8NWRNSQG 8192MB SODIMM DDR3 1600MT/s            | 1         | 0.76%   |
| SK Hynix RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s             | 1         | 0.76%   |
| SK Hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                     | 1         | 0.76%   |
| SK Hynix RAM HYMP512F72CP8N3-Y5 1024MB FB-DIMM DDR2 667MT/s         | 1         | 0.76%   |
| SK Hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 975MT/s                | 1         | 0.76%   |
| SK Hynix RAM HMT41GV7BMR4A-H9 16GB DIMM 1333MT/s                    | 1         | 0.76%   |
| SK Hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 2000MT/s                | 1         | 0.76%   |
| SK Hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s              | 1         | 0.76%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 1         | 0.76%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.76%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1333MT/s           | 1         | 0.76%   |
| SK Hynix RAM HMT351R7CFR8A-H9 4096MB DIMM DDR3 1333MT/s             | 1         | 0.76%   |
| SK Hynix RAM HMT31GR7EFR4A 8192MB DIMM DDR3 1600MT/s                | 1         | 0.76%   |
| SK Hynix RAM HMT31GR7BFR4A-H9 16GB DIMM 1333MT/s                    | 1         | 0.76%   |
| SK Hynix RAM HMT125R7BFR8C-H9 4GB DIMM 1333MT/s                     | 1         | 0.76%   |
| SK Hynix RAM HMA851S6JJR6N-VK 4096MB SODIMM DDR4 2667MT/s           | 1         | 0.76%   |
| SK Hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s              | 1         | 0.76%   |
| SK Hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 0.76%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 1         | 0.76%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s              | 1         | 0.76%   |
| SK Hynix RAM HMA81GR7CJR8N-XN 8192MB DIMM DDR4 3200MT/s             | 1         | 0.76%   |
| SK Hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s              | 1         | 0.76%   |
| SK Hynix RAM H9CCNNNCLGALAR-NUD 8192MB Row Of Chips LPDDR3 1867MT/s | 1         | 0.76%   |
| SK Hynix RAM 746448-381 4096MB SODIMM LPDDR3 1600MT/s               | 1         | 0.76%   |
| Silicon Power RAM DCLT4GN568S V 4096MB DIMM DDR3 1600MT/s           | 1         | 0.76%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s               | 1         | 0.76%   |
| Samsung RAM M471B5273DH0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.76%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 1         | 0.76%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.76%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.76%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.76%   |
| Samsung RAM M471B5173BH0-CK0 4096MB SODIMM DDR3 1600MT/s            | 1         | 0.76%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s            | 1         | 0.76%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 1         | 0.76%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 1         | 0.76%   |
| Samsung RAM M471A5244BB0-CPB 4GB SODIMM DDR4 2400MT/s               | 1         | 0.76%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s              | 1         | 0.76%   |
| Samsung RAM M395T5663QZ4-CE66 2048MB FB-DIMM DDR2 667MT/s           | 1         | 0.76%   |
| Samsung RAM M393B5273DH0-CK0 4GB DIMM DDR3 1600MT/s                 | 1         | 0.76%   |
| Samsung RAM M393A2G40DB0-CPB 16GB RIMM DDR4 2133MT/s                | 1         | 0.76%   |
| Samsung RAM M393A1K43BB0-CRC 8GB DIMM DDR4 2400MT/s                 | 1         | 0.76%   |
| Samsung RAM M393A1G43EB1-CRC 8GB DIMM DDR4 2400MT/s                 | 1         | 0.76%   |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s                 | 1         | 0.76%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s             | 1         | 0.76%   |
| Ramaxel RAM RMT3150ED58E8W1600 2GB SODIMM DDR3 1600MT/s             | 1         | 0.76%   |
| Ramaxel RAM RMSA3260MH78HAF-2666 8192MB SODIMM DDR4 2667MT/s        | 1         | 0.76%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 45        | 43.69%  |
| DDR3    | 41        | 39.81%  |
| DDR2    | 5         | 4.85%   |
| SDRAM   | 4         | 3.88%   |
| LPDDR3  | 3         | 2.91%   |
| LPDDR4  | 2         | 1.94%   |
| Unknown | 2         | 1.94%   |
| DDR     | 1         | 0.97%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 51        | 50%     |
| DIMM         | 47        | 46.08%  |
| Row Of Chips | 2         | 1.96%   |
| RIMM         | 1         | 0.98%   |
| FB-DIMM      | 1         | 0.98%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 40        | 35.4%   |
| 4096  | 40        | 35.4%   |
| 16384 | 14        | 12.39%  |
| 2048  | 10        | 8.85%   |
| 1024  | 5         | 4.42%   |
| 32768 | 4         | 3.54%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 30        | 27.27%  |
| 2667    | 15        | 13.64%  |
| 3200    | 14        | 12.73%  |
| 2400    | 11        | 10%     |
| 1333    | 6         | 5.45%   |
| 2133    | 5         | 4.55%   |
| 667     | 5         | 4.55%   |
| 3600    | 3         | 2.73%   |
| 1867    | 3         | 2.73%   |
| Unknown | 3         | 2.73%   |
| 2666    | 2         | 1.82%   |
| 1866    | 2         | 1.82%   |
| 800     | 2         | 1.82%   |
| 65535   | 1         | 0.91%   |
| 4199    | 1         | 0.91%   |
| 3800    | 1         | 0.91%   |
| 3533    | 1         | 0.91%   |
| 2000    | 1         | 0.91%   |
| 1334    | 1         | 0.91%   |
| 1066    | 1         | 0.91%   |
| 975     | 1         | 0.91%   |
| 701     | 1         | 0.91%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 3         | 37.5%   |
| Brother Industries  | 2         | 25%     |
| QinHeng Electronics | 1         | 12.5%   |
| Dell                | 1         | 12.5%   |
| Canon               | 1         | 12.5%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                        | Computers | Percent |
|------------------------------|-----------|---------|
| QinHeng CH340S               | 1         | 12.5%   |
| HP OfficeJet Pro 9010 series | 1         | 12.5%   |
| HP ENVY 4520 series          | 1         | 12.5%   |
| HP ENVY 4500 series          | 1         | 12.5%   |
| Dell 2330d Laser Printer     | 1         | 12.5%   |
| Canon LiDE 300               | 1         | 12.5%   |
| Brother Printer              | 1         | 12.5%   |
| Brother HL-L2320D series     | 1         | 12.5%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Seiko Epson     | 1         | 50%     |
| Hewlett-Packard | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO] | 1         | 50%     |
| HP ScanJet 5590                               | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 15        | 25%     |
| Logitech                               | 9         | 15%     |
| Acer                                   | 7         | 11.67%  |
| Realtek Semiconductor                  | 4         | 6.67%   |
| Microdia                               | 4         | 6.67%   |
| IMC Networks                           | 4         | 6.67%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 6.67%   |
| Lite-On Technology                     | 3         | 5%      |
| Sunplus Innovation Technology          | 2         | 3.33%   |
| Quanta                                 | 2         | 3.33%   |
| Syntek                                 | 1         | 1.67%   |
| Silicon Motion                         | 1         | 1.67%   |
| Samsung Electronics                    | 1         | 1.67%   |
| Motorola PCS                           | 1         | 1.67%   |
| Luxvisions Innotech Limited            | 1         | 1.67%   |
| Apple                                  | 1         | 1.67%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 3         | 5%      |
| Acer BisonCam,NB Pro                                                       | 3         | 5%      |
| Quanta HP Webcam                                                           | 2         | 3.33%   |
| Acer HD Webcam                                                             | 2         | 3.33%   |
| Syntek USB2.0 Camera                                                       | 1         | 1.67%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                       | 1         | 1.67%   |
| Sunplus Integrated_Webcam_HD                                               | 1         | 1.67%   |
| Silicon Motion Web Camera                                                  | 1         | 1.67%   |
| Samsung Galaxy A5 (MTP)                                                    | 1         | 1.67%   |
| Realtek USB2.0-Camera                                                      | 1         | 1.67%   |
| Realtek USB Camera                                                         | 1         | 1.67%   |
| Realtek Laptop Camera                                                      | 1         | 1.67%   |
| Realtek EasyCamera                                                         | 1         | 1.67%   |
| Motorola PCS XT1033 [Moto G], PTP mode                                     | 1         | 1.67%   |
| Microdia Laptop_Integrated_Webcam_2M                                       | 1         | 1.67%   |
| Microdia Integrated_Webcam_HD                                              | 1         | 1.67%   |
| Microdia Integrated Webcam                                                 | 1         | 1.67%   |
| Microdia Dell Integrated HD Webcam                                         | 1         | 1.67%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 1         | 1.67%   |
| Logitech Webcam C310                                                       | 1         | 1.67%   |
| Logitech Webcam C300                                                       | 1         | 1.67%   |
| Logitech Webcam C270                                                       | 1         | 1.67%   |
| Logitech Webcam C170                                                       | 1         | 1.67%   |
| Logitech QuickCam Pro 9000                                                 | 1         | 1.67%   |
| Logitech HD Webcam C525                                                    | 1         | 1.67%   |
| Logitech HD Pro Webcam C920                                                | 1         | 1.67%   |
| Logitech C922 Pro Stream Webcam                                            | 1         | 1.67%   |
| Logitech C920 PRO HD Webcam                                                | 1         | 1.67%   |
| Lite-On TOSHIBA Web Camera - FHD                                           | 1         | 1.67%   |
| Lite-On Integrated Camera                                                  | 1         | 1.67%   |
| Lite-On HP TrueVision HD Camera                                            | 1         | 1.67%   |
| IMC Networks UVC VGA Webcam                                                | 1         | 1.67%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 1         | 1.67%   |
| IMC Networks Lenovo EasyCamera                                             | 1         | 1.67%   |
| IMC Networks Integrated Camera                                             | 1         | 1.67%   |
| Chicony Web Camera - FHD                                                   | 1         | 1.67%   |
| Chicony TOSHIBA Web Camera - HD                                            | 1         | 1.67%   |
| Chicony TOSHIBA Web Camera - FHD                                           | 1         | 1.67%   |
| Chicony Integrated Camera [ThinkPad]                                       | 1         | 1.67%   |
| Chicony Integrated Camera (1280x720@30)                                    | 1         | 1.67%   |
| Chicony HP TrueVision HD Camera                                            | 1         | 1.67%   |
| Chicony HP HD Webcam [Fixed]                                               | 1         | 1.67%   |
| Chicony HP HD Camera                                                       | 1         | 1.67%   |
| Chicony HD WebCam (Acer)                                                   | 1         | 1.67%   |
| Chicony HD WebCam                                                          | 1         | 1.67%   |
| Chicony FJ Camera                                                          | 1         | 1.67%   |
| Chicony 2.0M UVC Webcam / CNF7129                                          | 1         | 1.67%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD integrated webcam | 1         | 1.67%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera             | 1         | 1.67%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam                        | 1         | 1.67%   |
| Cheng Uei Precision Industry (Foxlink) HP 5M Camera                        | 1         | 1.67%   |
| Apple Built-in iSight                                                      | 1         | 1.67%   |
| Acer ThinkPad Integrated Camera                                            | 1         | 1.67%   |
| Acer Integrated Camera                                                     | 1         | 1.67%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 6         | 50%     |
| Synaptics             | 3         | 25%     |
| STMicroelectronics    | 1         | 8.33%   |
| LighTuning Technology | 1         | 8.33%   |
| Elan Microelectronics | 1         | 8.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Unknown                                           | 2         | 16.67%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor | 1         | 8.33%   |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 8.33%   |
| Validity Sensors VFS300 Fingerprint Reader        | 1         | 8.33%   |
| Validity Sensors VFS Fingerprint sensor           | 1         | 8.33%   |
| Validity Sensors VFS 5011 fingerprint sensor      | 1         | 8.33%   |
| Validity Sensors Synaptics WBDI                   | 1         | 8.33%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 8.33%   |
| STMicroelectronics Fingerprint Reader             | 1         | 8.33%   |
| LighTuning EgisTec Touch Fingerprint Sensor       | 1         | 8.33%   |
| Elan ELAN:Fingerprint                             | 1         | 8.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 3         | 42.86%  |
| Broadcom              | 2         | 28.57%  |
| O2 Micro              | 1         | 14.29%  |
| Gemalto (was Gemplus) | 1         | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                    | 3         | 42.86%  |
| O2 Micro OZ776 CCID Smartcard Reader                   | 1         | 14.29%  |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer | 1         | 14.29%  |
| Broadcom BCM5880 Secure Applications Processor         | 1         | 14.29%  |
| Broadcom 5880                                          | 1         | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 69        | 61.06%  |
| 1     | 23        | 20.35%  |
| 2     | 11        | 9.73%   |
| 3     | 6         | 5.31%   |
| 4     | 4         | 3.54%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 14        | 19.18%  |
| Fingerprint reader       | 11        | 15.07%  |
| Sound                    | 10        | 13.7%   |
| Net/wireless             | 7         | 9.59%   |
| Communication controller | 7         | 9.59%   |
| Chipcard                 | 7         | 9.59%   |
| Card reader              | 4         | 5.48%   |
| Unassigned class         | 3         | 4.11%   |
| Net/ethernet             | 2         | 2.74%   |
| Multimedia controller    | 2         | 2.74%   |
| Bluetooth                | 2         | 2.74%   |
| Storage/ata              | 1         | 1.37%   |
| Storage                  | 1         | 1.37%   |
| Firewire controller      | 1         | 1.37%   |
| Camera                   | 1         | 1.37%   |

