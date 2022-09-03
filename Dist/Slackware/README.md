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

Total: 144

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [a954ba4e86](https://linux-hardware.org/?probe=a954ba4e86) | Aug 26, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [9bfc03d98e](https://linux-hardware.org/?probe=9bfc03d98e) | Aug 20, 2022 |
| Dell          | 0200DY A03                  | Desktop     | [e0e14cd1f2](https://linux-hardware.org/?probe=e0e14cd1f2) | Aug 19, 2022 |
| Fujitsu       | LIFEBOOK A544               | Notebook    | [e5785106f1](https://linux-hardware.org/?probe=e5785106f1) | Aug 09, 2022 |
| MSI           | Modern 14 B10MW             | Notebook    | [b9cde08864](https://linux-hardware.org/?probe=b9cde08864) | Jul 25, 2022 |
| Dell          | 072XWF A03                  | Server      | [d083ad669a](https://linux-hardware.org/?probe=d083ad669a) | Jun 29, 2022 |
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
| NetGear       | ReadyDATA 5200              | Desktop     | [96607f4270](https://linux-hardware.org/?probe=96607f4270) | Nov 12, 2020 |
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
| Slackware 14.2  | 62        | 52.1%   |
| Slackware 15.0  | 51        | 42.86%  |
| Slackware 14.2+ | 6         | 5.04%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| Slackware | 117       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version              | Computers | Percent |
|----------------------|-----------|---------|
| 5.15.19              | 12        | 9.68%   |
| 4.19.80              | 8         | 6.45%   |
| 5.10.28-Unraid       | 6         | 4.84%   |
| 5.15.27              | 4         | 3.23%   |
| 4.4.190              | 4         | 3.23%   |
| 4.4.240              | 3         | 2.42%   |
| 5.3.7                | 2         | 1.61%   |
| 5.17.2               | 2         | 1.61%   |
| 5.17.1               | 2         | 1.61%   |
| 5.16.13              | 2         | 1.61%   |
| 5.15.38              | 2         | 1.61%   |
| 5.15.30-Unraid       | 2         | 1.61%   |
| 5.13.8               | 2         | 1.61%   |
| 5.10.3               | 2         | 1.61%   |
| 5.7.0                | 1         | 0.81%   |
| 5.5.10               | 1         | 0.81%   |
| 5.4.77               | 1         | 0.81%   |
| 5.4.75               | 1         | 0.81%   |
| 5.4.62               | 1         | 0.81%   |
| 5.4.53-APRL          | 1         | 0.81%   |
| 5.4.50               | 1         | 0.81%   |
| 5.4.47               | 1         | 0.81%   |
| 5.4.43               | 1         | 0.81%   |
| 5.4.24toshiba-new    | 1         | 0.81%   |
| 5.4.2                | 1         | 0.81%   |
| 5.4.139-jw           | 1         | 0.81%   |
| 5.4.13               | 1         | 0.81%   |
| 5.4.12+              | 1         | 0.81%   |
| 5.4.0-rc2-vto        | 1         | 0.81%   |
| 5.2.2                | 1         | 0.81%   |
| 5.17.5               | 1         | 0.81%   |
| 5.17.0-custom        | 1         | 0.81%   |
| 5.16.9-joe1          | 1         | 0.81%   |
| 5.16.18              | 1         | 0.81%   |
| 5.16.12              | 1         | 0.81%   |
| 5.16.11              | 1         | 0.81%   |
| 5.15.6               | 1         | 0.81%   |
| 5.15.50-cwl          | 1         | 0.81%   |
| 5.15.37.a            | 1         | 0.81%   |
| 5.15.33.kjh          | 1         | 0.81%   |
| 5.15.21-hardened1    | 1         | 0.81%   |
| 5.15.2-pmagic        | 1         | 0.81%   |
| 5.15.14              | 1         | 0.81%   |
| 5.15.13              | 1         | 0.81%   |
| 5.15.1               | 1         | 0.81%   |
| 5.14.9               | 1         | 0.81%   |
| 5.14.8               | 1         | 0.81%   |
| 5.14.15-Unraid       | 1         | 0.81%   |
| 5.14.15              | 1         | 0.81%   |
| 5.14.11              | 1         | 0.81%   |
| 5.14.10              | 1         | 0.81%   |
| 5.14.0               | 1         | 0.81%   |
| 5.13.9-jw            | 1         | 0.81%   |
| 5.13.5               | 1         | 0.81%   |
| 5.13.12              | 1         | 0.81%   |
| 5.13.11              | 1         | 0.81%   |
| 5.13.0.a             | 1         | 0.81%   |
| 5.12.12              | 1         | 0.81%   |
| 5.10.91              | 1         | 0.81%   |
| 5.10.44-slack64-host | 1         | 0.81%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.19 | 12        | 9.68%   |
| 4.19.80 | 8         | 6.45%   |
| 5.10.28 | 6         | 4.84%   |
| 4.4.190 | 5         | 4.03%   |
| 5.15.27 | 4         | 3.23%   |
| 4.4.240 | 3         | 2.42%   |
| 5.3.7   | 2         | 1.61%   |
| 5.17.2  | 2         | 1.61%   |
| 5.17.1  | 2         | 1.61%   |
| 5.16.13 | 2         | 1.61%   |
| 5.15.38 | 2         | 1.61%   |
| 5.15.30 | 2         | 1.61%   |
| 5.14.15 | 2         | 1.61%   |
| 5.13.8  | 2         | 1.61%   |
| 5.10.3  | 2         | 1.61%   |
| 5.7.0   | 1         | 0.81%   |
| 5.5.10  | 1         | 0.81%   |
| 5.4.77  | 1         | 0.81%   |
| 5.4.75  | 1         | 0.81%   |
| 5.4.62  | 1         | 0.81%   |
| 5.4.53  | 1         | 0.81%   |
| 5.4.50  | 1         | 0.81%   |
| 5.4.47  | 1         | 0.81%   |
| 5.4.43  | 1         | 0.81%   |
| 5.4.24  | 1         | 0.81%   |
| 5.4.2   | 1         | 0.81%   |
| 5.4.139 | 1         | 0.81%   |
| 5.4.13  | 1         | 0.81%   |
| 5.4.12  | 1         | 0.81%   |
| 5.4.0   | 1         | 0.81%   |
| 5.2.2   | 1         | 0.81%   |
| 5.17.5  | 1         | 0.81%   |
| 5.17.0  | 1         | 0.81%   |
| 5.16.9  | 1         | 0.81%   |
| 5.16.18 | 1         | 0.81%   |
| 5.16.12 | 1         | 0.81%   |
| 5.16.11 | 1         | 0.81%   |
| 5.15.6  | 1         | 0.81%   |
| 5.15.50 | 1         | 0.81%   |
| 5.15.37 | 1         | 0.81%   |
| 5.15.33 | 1         | 0.81%   |
| 5.15.21 | 1         | 0.81%   |
| 5.15.2  | 1         | 0.81%   |
| 5.15.14 | 1         | 0.81%   |
| 5.15.13 | 1         | 0.81%   |
| 5.15.1  | 1         | 0.81%   |
| 5.14.9  | 1         | 0.81%   |
| 5.14.8  | 1         | 0.81%   |
| 5.14.11 | 1         | 0.81%   |
| 5.14.10 | 1         | 0.81%   |
| 5.14.0  | 1         | 0.81%   |
| 5.13.9  | 1         | 0.81%   |
| 5.13.5  | 1         | 0.81%   |
| 5.13.12 | 1         | 0.81%   |
| 5.13.11 | 1         | 0.81%   |
| 5.13.0  | 1         | 0.81%   |
| 5.12.12 | 1         | 0.81%   |
| 5.10.91 | 1         | 0.81%   |
| 5.10.44 | 1         | 0.81%   |
| 5.10.40 | 1         | 0.81%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 29        | 23.58%  |
| 4.4     | 16        | 13.01%  |
| 5.10    | 15        | 12.2%   |
| 4.19    | 15        | 12.2%   |
| 5.4     | 13        | 10.57%  |
| 5.13    | 7         | 5.69%   |
| 5.17    | 6         | 4.88%   |
| 5.16    | 6         | 4.88%   |
| 5.14    | 6         | 4.88%   |
| 5.3     | 2         | 1.63%   |
| 4.9     | 2         | 1.63%   |
| 5.7     | 1         | 0.81%   |
| 5.5     | 1         | 0.81%   |
| 5.2     | 1         | 0.81%   |
| 5.12    | 1         | 0.81%   |
| 4.20    | 1         | 0.81%   |
| 4.16    | 1         | 0.81%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 114       | 97.44%  |
| aarch64 | 2         | 1.71%   |
| i686    | 1         | 0.85%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Unknown       | 42        | 35.29%  |
| XFCE          | 33        | 27.73%  |
| KDE5          | 30        | 25.21%  |
| KDE           | 5         | 4.2%    |
| MATE          | 2         | 1.68%   |
| GNOME         | 2         | 1.68%   |
| fvwm          | 2         | 1.68%   |
| xwmconfig     | 1         | 0.84%   |
| LXQt          | 1         | 0.84%   |
| Enlightenment | 1         | 0.84%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 79        | 66.39%  |
| Tty     | 26        | 21.85%  |
| Unknown | 10        | 8.4%    |
| Wayland | 4         | 3.36%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 48        | 40.34%  |
| SDDM    | 40        | 33.61%  |
| XDM     | 27        | 22.69%  |
| SLiM    | 2         | 1.68%   |
| LightDM | 2         | 1.68%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 61        | 52.14%  |
| Unknown     | 38        | 32.48%  |
| it_IT       | 3         | 2.56%   |
| fr_FR       | 3         | 2.56%   |
| ru_RU       | 2         | 1.71%   |
| pt_BR       | 2         | 1.71%   |
| sr_RS@latin | 1         | 0.85%   |
| pl_PL       | 1         | 0.85%   |
| es_ES.UTF8  | 1         | 0.85%   |
| en_US.ASCII | 1         | 0.85%   |
| en_GB       | 1         | 0.85%   |
| en_AU       | 1         | 0.85%   |
| de_DE       | 1         | 0.85%   |
| C           | 1         | 0.85%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 62        | 52.54%  |
| EFI  | 56        | 47.46%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 85        | 72.65%  |
| Btrfs    | 14        | 11.97%  |
| Overlay  | 6         | 5.13%   |
| Xfs      | 4         | 3.42%   |
| Rootfs   | 3         | 2.56%   |
| Zfs      | 1         | 0.85%   |
| Reiserfs | 1         | 0.85%   |
| Jfs      | 1         | 0.85%   |
| F2fs     | 1         | 0.85%   |
| Ext3     | 1         | 0.85%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 83        | 69.17%  |
| MBR     | 31        | 25.83%  |
| Unknown | 6         | 5%      |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 78        | 65.55%  |
| Yes       | 41        | 34.45%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 76        | 64.96%  |
| Yes       | 41        | 35.04%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 20        | 17.09%  |
| Hewlett-Packard     | 18        | 15.38%  |
| Lenovo              | 13        | 11.11%  |
| Dell                | 12        | 10.26%  |
| MSI                 | 11        | 9.4%    |
| ASRock              | 7         | 5.98%   |
| Gigabyte Technology | 5         | 4.27%   |
| Toshiba             | 3         | 2.56%   |
| Acer                | 3         | 2.56%   |
| Notebook            | 2         | 1.71%   |
| Fujitsu             | 2         | 1.71%   |
| Dynabook            | 2         | 1.71%   |
| Apple               | 2         | 1.71%   |
| Unknown             | 2         | 1.71%   |
| TYAN Computer       | 1         | 0.85%   |
| System76            | 1         | 0.85%   |
| Supermicro          | 1         | 0.85%   |
| Sony                | 1         | 0.85%   |
| Shuttle             | 1         | 0.85%   |
| Samsung Electronics | 1         | 0.85%   |
| Radxa               | 1         | 0.85%   |
| NetGear             | 1         | 0.85%   |
| Intel               | 1         | 0.85%   |
| Huanan              | 1         | 0.85%   |
| HPE                 | 1         | 0.85%   |
| Framework           | 1         | 0.85%   |
| Foxconn             | 1         | 0.85%   |
| Biostar             | 1         | 0.85%   |
| AMI                 | 1         | 0.85%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| ASUS All Series                          | 4         | 3.42%   |
| Unknown                                  | 2         | 1.71%   |
| TYAN S7012                               | 1         | 0.85%   |
| Toshiba Satellite P50-A-12Z              | 1         | 0.85%   |
| Toshiba Satellite C660                   | 1         | 0.85%   |
| Toshiba PORTEGE Z30-A                    | 1         | 0.85%   |
| System76 Oryx Pro                        | 1         | 0.85%   |
| Supermicro X9DA7/E                       | 1         | 0.85%   |
| Sony SVE1713A1EW                         | 1         | 0.85%   |
| Shuttle NC03U                            | 1         | 0.85%   |
| Samsung 300E5M/300E5L                    | 1         | 0.85%   |
| Radxa ROCK Pi 4                          | 1         | 0.85%   |
| Notebook X170KM-G                        | 1         | 0.85%   |
| Notebook NL40_50CU                       | 1         | 0.85%   |
| NetGear ReadyDATA 5200                   | 1         | 0.85%   |
| MSI MS-7C52                              | 1         | 0.85%   |
| MSI MS-7C02                              | 1         | 0.85%   |
| MSI MS-7788                              | 1         | 0.85%   |
| MSI MS-7693                              | 1         | 0.85%   |
| MSI MS-7529                              | 1         | 0.85%   |
| MSI MS-7365                              | 1         | 0.85%   |
| MSI Modern 14 B11MO                      | 1         | 0.85%   |
| MSI Modern 14 B10MW                      | 1         | 0.85%   |
| MSI GP76 Leopard 11UG                    | 1         | 0.85%   |
| MSI GL73 8RC                             | 1         | 0.85%   |
| MSI GE76 Raider 11UE                     | 1         | 0.85%   |
| Lenovo V330-14ARR 81B1                   | 1         | 0.85%   |
| Lenovo ThinkPad X230 2325P38             | 1         | 0.85%   |
| Lenovo ThinkPad X1 Carbon 7th 20R10015US | 1         | 0.85%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS04300 | 1         | 0.85%   |
| Lenovo ThinkPad T470 20HDCTO1WW          | 1         | 0.85%   |
| Lenovo ThinkPad T450s 20BW000EUS         | 1         | 0.85%   |
| Lenovo ThinkPad T400 6474BV7             | 1         | 0.85%   |
| Lenovo ThinkPad P70 20ERCTO1WW           | 1         | 0.85%   |
| Lenovo ThinkPad L440 20ASS05K00          | 1         | 0.85%   |
| Lenovo ThinkPad Edge E530c 336669G       | 1         | 0.85%   |
| Lenovo IdeaPad P500 20210                | 1         | 0.85%   |
| Lenovo IdeaPad 310-15ISK 80SM            | 1         | 0.85%   |
| Lenovo H50-05 90BH001WIX                 | 1         | 0.85%   |
| Intel DZ77RE-75K AAG39010-302            | 1         | 0.85%   |
| Huanan X79-8D VAA31                      | 1         | 0.85%   |
| HPE ProLiant MicroServer Gen10 Plus      | 1         | 0.85%   |
| HP Z620 Workstation                      | 1         | 0.85%   |
| HP Z440 Workstation                      | 1         | 0.85%   |
| HP xw8400 Workstation                    | 1         | 0.85%   |
| HP t640 Thin Client                      | 1         | 0.85%   |
| HP t620 Quad Core TC                     | 1         | 0.85%   |
| HP ProBook 6570b                         | 1         | 0.85%   |
| HP Pavilion Notebook                     | 1         | 0.85%   |
| HP Pavilion Gaming Laptop 16-a0xxx       | 1         | 0.85%   |
| HP Pavilion Gaming Laptop 15-ec1xxx      | 1         | 0.85%   |
| HP Laptop 15-da0xxx                      | 1         | 0.85%   |
| HP Laptop 15-bs2xx                       | 1         | 0.85%   |
| HP Laptop 15-bs1xx                       | 1         | 0.85%   |
| HP EliteBook Folio 1020 G1 SE            | 1         | 0.85%   |
| HP EliteBook 840 G5                      | 1         | 0.85%   |
| HP 500-515na                             | 1         | 0.85%   |
| HP 245 G7 Notebook PC                    | 1         | 0.85%   |
| HP 205 G4 22 All-in-One PC               | 1         | 0.85%   |
| HP 15 Notebook PC                        | 1         | 0.85%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 9         | 7.69%   |
| Dell Precision      | 4         | 3.42%   |
| ASUS PRIME          | 4         | 3.42%   |
| ASUS All            | 4         | 3.42%   |
| HP Pavilion         | 3         | 2.56%   |
| HP Laptop           | 3         | 2.56%   |
| Dell Latitude       | 3         | 2.56%   |
| ASUS ROG            | 3         | 2.56%   |
| Toshiba Satellite   | 2         | 1.71%   |
| MSI Modern          | 2         | 1.71%   |
| Lenovo IdeaPad      | 2         | 1.71%   |
| HP EliteBook        | 2         | 1.71%   |
| Fujitsu LIFEBOOK    | 2         | 1.71%   |
| Dell PowerEdge      | 2         | 1.71%   |
| Acer Aspire         | 2         | 1.71%   |
| Unknown             | 2         | 1.71%   |
| TYAN S7012          | 1         | 0.85%   |
| Toshiba PORTEGE     | 1         | 0.85%   |
| System76 Oryx       | 1         | 0.85%   |
| Supermicro X9DA7    | 1         | 0.85%   |
| Sony SVE1713A1EW    | 1         | 0.85%   |
| Shuttle NC03U       | 1         | 0.85%   |
| Samsung 300E5M      | 1         | 0.85%   |
| Radxa ROCK          | 1         | 0.85%   |
| Notebook X170KM-G   | 1         | 0.85%   |
| Notebook NL40       | 1         | 0.85%   |
| NetGear ReadyDATA   | 1         | 0.85%   |
| MSI MS-7C52         | 1         | 0.85%   |
| MSI MS-7C02         | 1         | 0.85%   |
| MSI MS-7788         | 1         | 0.85%   |
| MSI MS-7693         | 1         | 0.85%   |
| MSI MS-7529         | 1         | 0.85%   |
| MSI MS-7365         | 1         | 0.85%   |
| MSI GP76            | 1         | 0.85%   |
| MSI GL73            | 1         | 0.85%   |
| MSI GE76            | 1         | 0.85%   |
| Lenovo V330-14ARR   | 1         | 0.85%   |
| Lenovo H50-05       | 1         | 0.85%   |
| Intel DZ77RE-75K    | 1         | 0.85%   |
| Huanan X79-8D       | 1         | 0.85%   |
| HPE ProLiant        | 1         | 0.85%   |
| HP Z620             | 1         | 0.85%   |
| HP Z440             | 1         | 0.85%   |
| HP xw8400           | 1         | 0.85%   |
| HP t640             | 1         | 0.85%   |
| HP t620             | 1         | 0.85%   |
| HP ProBook          | 1         | 0.85%   |
| HP 500-515na        | 1         | 0.85%   |
| HP 245              | 1         | 0.85%   |
| HP 205              | 1         | 0.85%   |
| HP 15               | 1         | 0.85%   |
| Gigabyte X570       | 1         | 0.85%   |
| Gigabyte X150M-PRO  | 1         | 0.85%   |
| Gigabyte N3160TN    | 1         | 0.85%   |
| Gigabyte M61SME-S2  | 1         | 0.85%   |
| Gigabyte 970A-DS3P  | 1         | 0.85%   |
| Framework Laptop    | 1         | 0.85%   |
| Foxconn p6-2390     | 1         | 0.85%   |
| Dynabook PORTEGE    | 1         | 0.85%   |
| Dynabook P1-C7MP-BL | 1         | 0.85%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 15        | 12.82%  |
| 2012    | 12        | 10.26%  |
| 2020    | 11        | 9.4%    |
| 2018    | 10        | 8.55%   |
| 2017    | 10        | 8.55%   |
| 2015    | 9         | 7.69%   |
| 2021    | 8         | 6.84%   |
| 2014    | 8         | 6.84%   |
| 2016    | 7         | 5.98%   |
| 2011    | 7         | 5.98%   |
| 2008    | 5         | 4.27%   |
| 2013    | 4         | 3.42%   |
| 2009    | 3         | 2.56%   |
| 2007    | 3         | 2.56%   |
| 2010    | 2         | 1.71%   |
| Unknown | 2         | 1.71%   |
| 2022    | 1         | 0.85%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 54        | 46.15%  |
| Desktop        | 53        | 45.3%   |
| Mini pc        | 3         | 2.56%   |
| Server         | 3         | 2.56%   |
| System on chip | 2         | 1.71%   |
| All in one     | 2         | 1.71%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 117       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 114       | 97.44%  |
| Yes  | 3         | 2.56%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 24        | 20.51%  |
| 16.01-24.0  | 24        | 20.51%  |
| 8.01-16.0   | 21        | 17.95%  |
| 3.01-4.0    | 19        | 16.24%  |
| 32.01-64.0  | 11        | 9.4%    |
| 64.01-256.0 | 9         | 7.69%   |
| 24.01-32.0  | 5         | 4.27%   |
| 1.01-2.0    | 3         | 2.56%   |
| 0.51-1.0    | 1         | 0.85%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 36        | 29.51%  |
| 2.01-3.0    | 27        | 22.13%  |
| 4.01-8.0    | 21        | 17.21%  |
| 3.01-4.0    | 13        | 10.66%  |
| 0.51-1.0    | 9         | 7.38%   |
| 0.01-0.5    | 5         | 4.1%    |
| 8.01-16.0   | 4         | 3.28%   |
| 16.01-24.0  | 3         | 2.46%   |
| 24.01-32.0  | 2         | 1.64%   |
| 32.01-64.0  | 1         | 0.82%   |
| 64.01-256.0 | 1         | 0.82%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 56        | 47.06%  |
| 2      | 24        | 20.17%  |
| 3      | 14        | 11.76%  |
| 4      | 10        | 8.4%    |
| 5      | 5         | 4.2%    |
| 6      | 4         | 3.36%   |
| 0      | 2         | 1.68%   |
| 13     | 1         | 0.84%   |
| 9      | 1         | 0.84%   |
| 8      | 1         | 0.84%   |
| 7      | 1         | 0.84%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 67        | 57.26%  |
| Yes       | 50        | 42.74%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 108       | 92.31%  |
| No        | 9         | 7.69%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 78        | 66.67%  |
| No        | 39        | 33.33%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 73        | 62.39%  |
| No        | 44        | 37.61%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 26        | 22.22%  |
| UK           | 10        | 8.55%   |
| Brazil       | 7         | 5.98%   |
| Kazakhstan   | 6         | 5.13%   |
| Italy        | 6         | 5.13%   |
| Germany      | 6         | 5.13%   |
| Canada       | 6         | 5.13%   |
| Portugal     | 5         | 4.27%   |
| Japan        | 5         | 4.27%   |
| France       | 5         | 4.27%   |
| Sweden       | 4         | 3.42%   |
| Russia       | 4         | 3.42%   |
| India        | 4         | 3.42%   |
| Spain        | 3         | 2.56%   |
| South Africa | 3         | 2.56%   |
| Hong Kong    | 3         | 2.56%   |
| Serbia       | 2         | 1.71%   |
| Poland       | 2         | 1.71%   |
| Greece       | 2         | 1.71%   |
| Switzerland  | 1         | 0.85%   |
| Philippines  | 1         | 0.85%   |
| Netherlands  | 1         | 0.85%   |
| Mexico       | 1         | 0.85%   |
| Finland      | 1         | 0.85%   |
| Chile        | 1         | 0.85%   |
| Bulgaria     | 1         | 0.85%   |
| Australia    | 1         | 0.85%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Ust-Kamenogorsk        | 4         | 3.33%   |
| Lisbon                 | 4         | 3.33%   |
| Yekaterinburg          | 3         | 2.5%    |
| Paris                  | 3         | 2.5%    |
| Warsaw                 | 2         | 1.67%   |
| Tsukuba                | 2         | 1.67%   |
| Tendo                  | 2         | 1.67%   |
| New Delhi              | 2         | 1.67%   |
| Milan                  | 2         | 1.67%   |
| Karaganda              | 2         | 1.67%   |
| Chania                 | 2         | 1.67%   |
| Carrollton             | 2         | 1.67%   |
| Cape Town              | 2         | 1.67%   |
| Belgrade               | 2         | 1.67%   |
| Barry                  | 2         | 1.67%   |
| Barrie                 | 2         | 1.67%   |
| Wokingham              | 1         | 0.83%   |
| Winnipeg               | 1         | 0.83%   |
| Weilheim               | 1         | 0.83%   |
| Visconde do Rio Branco | 1         | 0.83%   |
| Toronto                | 1         | 0.83%   |
| Tiffin                 | 1         | 0.83%   |
| Stockholm              | 1         | 0.83%   |
| St Petersburg          | 1         | 0.83%   |
| St Louis               | 1         | 0.83%   |
| Springfield            | 1         | 0.83%   |
| Southend-on-Sea        | 1         | 0.83%   |
| Skövde                | 1         | 0.83%   |
| Shrewsbury             | 1         | 0.83%   |
| Sham Shui Po           | 1         | 0.83%   |
| Santa Cruz do Sul      | 1         | 0.83%   |
| San Antonio            | 1         | 0.83%   |
| Saint Paul             | 1         | 0.83%   |
| Round Rock             | 1         | 0.83%   |
| Rome                   | 1         | 0.83%   |
| Roknaes                | 1         | 0.83%   |
| Reno                   | 1         | 0.83%   |
| Renazzo                | 1         | 0.83%   |
| Redding                | 1         | 0.83%   |
| Puente Alto            | 1         | 0.83%   |
| Porto Alegre           | 1         | 0.83%   |
| Plovdiv                | 1         | 0.83%   |
| Plainwell              | 1         | 0.83%   |
| Pinhal Novo            | 1         | 0.83%   |
| Pesaro                 | 1         | 0.83%   |
| Pasay                  | 1         | 0.83%   |
| Palma                  | 1         | 0.83%   |
| Ottawa                 | 1         | 0.83%   |
| Ōtsu                  | 1         | 0.83%   |
| Oldham                 | 1         | 0.83%   |
| Oberstreit             | 1         | 0.83%   |
| Northport              | 1         | 0.83%   |
| Naples                 | 1         | 0.83%   |
| Naaldwijk              | 1         | 0.83%   |
| Montreal               | 1         | 0.83%   |
| Milwaukee              | 1         | 0.83%   |
| Mexico City            | 1         | 0.83%   |
| Mead                   | 1         | 0.83%   |
| McKinney               | 1         | 0.83%   |
| Mason                  | 1         | 0.83%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 35        | 63     | 18.82%  |
| Samsung Electronics | 32        | 49     | 17.2%   |
| Seagate             | 30        | 59     | 16.13%  |
| Toshiba             | 14        | 23     | 7.53%   |
| Kingston            | 9         | 11     | 4.84%   |
| Hitachi             | 7         | 10     | 3.76%   |
| Crucial             | 7         | 8      | 3.76%   |
| HGST                | 5         | 5      | 2.69%   |
| Unknown             | 4         | 4      | 2.15%   |
| SanDisk             | 4         | 4      | 2.15%   |
| Intel               | 4         | 4      | 2.15%   |
| A-DATA Technology   | 4         | 4      | 2.15%   |
| SK hynix            | 3         | 3      | 1.61%   |
| Hewlett-Packard     | 3         | 4      | 1.61%   |
| Gigabyte Technology | 3         | 3      | 1.61%   |
| Patriot             | 2         | 3      | 1.08%   |
| Micron Technology   | 2         | 2      | 1.08%   |
| China               | 2         | 3      | 1.08%   |
| Apple               | 2         | 3      | 1.08%   |
| ZHITAI              | 1         | 2      | 0.54%   |
| TO Exter            | 1         | 1      | 0.54%   |
| Team                | 1         | 1      | 0.54%   |
| Plextor             | 1         | 1      | 0.54%   |
| Netac               | 1         | 1      | 0.54%   |
| Maxtor              | 1         | 1      | 0.54%   |
| KIOXIA              | 1         | 1      | 0.54%   |
| JMicron Technology  | 1         | 1      | 0.54%   |
| Intenso             | 1         | 1      | 0.54%   |
| GOODRAM             | 1         | 1      | 0.54%   |
| Fujitsu             | 1         | 1      | 0.54%   |
| External            | 1         | 1      | 0.54%   |
| DUEX                | 1         | 1      | 0.54%   |
| Dogfish             | 1         | 1      | 0.54%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| WDC WD20EFRX-68EUZN0 2TB             | 3         | 1.32%   |
| WDC WD1003FZEX-00MK2A0 1TB           | 3         | 1.32%   |
| Samsung SSD 970 EVO 250GB            | 3         | 1.32%   |
| WDC WD10SPZX-60Z10T0 1TB             | 2         | 0.88%   |
| Toshiba MQ04ABF100 1TB               | 2         | 0.88%   |
| Toshiba MQ01ABD100 1TB               | 2         | 0.88%   |
| Seagate ST500DM002-1BD142 500GB      | 2         | 0.88%   |
| Seagate ST4000VN008-2DR166 4TB       | 2         | 0.88%   |
| Seagate ST31000524AS 1TB             | 2         | 0.88%   |
| Seagate ST2000DM008-2FR102 2TB       | 2         | 0.88%   |
| Seagate ST2000DM001-1CH164 2TB       | 2         | 0.88%   |
| Seagate ST1000DM010-2EP102 1TB       | 2         | 0.88%   |
| Seagate ST1000DM003-1SB102 1TB       | 2         | 0.88%   |
| Seagate ST1000DM003-1ER162 1TB       | 2         | 0.88%   |
| Samsung SSD 970 EVO Plus 1TB         | 2         | 0.88%   |
| Samsung SSD 860 QVO 2TB              | 2         | 0.88%   |
| Kingston SA400S37240G 240GB SSD      | 2         | 0.88%   |
| Crucial CT500MX500SSD1 500GB         | 2         | 0.88%   |
| ZHITAI SC001 Active 1TB SSD          | 1         | 0.44%   |
| ZHITAI PC005 Active 512GB            | 1         | 0.44%   |
| WDC WDS500G2B0B-00YS70 500GB SSD     | 1         | 0.44%   |
| WDC WDS100T2B0C-00PXH0 1TB           | 1         | 0.44%   |
| WDC WD7500BPVT-24HXZT3 752GB         | 1         | 0.44%   |
| WDC WD5003ABYX-18WERA0 500GB         | 1         | 0.44%   |
| WDC WD5000LPCX-60VHAT1 500GB         | 1         | 0.44%   |
| WDC WD5000BPVT-2 500GB               | 1         | 0.44%   |
| WDC WD5000BPKX-60HPJT0 500GB         | 1         | 0.44%   |
| WDC WD5000AAKX-22ERMA0 500GB         | 1         | 0.44%   |
| WDC WD5000AAKX-00ERMA0 500GB         | 1         | 0.44%   |
| WDC WD5000AAKS-00V0A0 500GB          | 1         | 0.44%   |
| WDC WD5000AAKS-00A7B2 500GB          | 1         | 0.44%   |
| WDC WD40EJRX-89T1XY0 4TB             | 1         | 0.44%   |
| WDC WD40EFRX-68WT0N0 4TB             | 1         | 0.44%   |
| WDC WD40EFRX-68N32N0 4TB             | 1         | 0.44%   |
| WDC WD400BD-60LTA0 40GB              | 1         | 0.44%   |
| WDC WD3200AAJS-65B4A0 320GB          | 1         | 0.44%   |
| WDC WD30EZRX-00SPEB0 3TB             | 1         | 0.44%   |
| WDC WD30EZRX-00M                     | 1         | 0.44%   |
| WDC WD30EFRX-68EUZN0 3TB             | 1         | 0.44%   |
| WDC WD30EFRX-68AX9N0 3TB             | 1         | 0.44%   |
| WDC WD20EZRZ-00Z5HB0 2TB             | 1         | 0.44%   |
| WDC WD20EZRX-00D8PB0 2TB             | 1         | 0.44%   |
| WDC WD2003FZEX-00Z4SA0 2TB           | 1         | 0.44%   |
| WDC WD2003FZEX-0 2TB                 | 1         | 0.44%   |
| WDC WD1600AAJS-00PSA0 160GB          | 1         | 0.44%   |
| WDC WD120EDAZ-11F3RA0 12TB           | 1         | 0.44%   |
| WDC WD10JPVX-35JC3T0 1TB             | 1         | 0.44%   |
| WDC WD10JPVX-16JC3T3 1TB             | 1         | 0.44%   |
| WDC WD10JPVT-08A1YT2 1TB             | 1         | 0.44%   |
| WDC WD10JPLX-00MBPT0 1TB             | 1         | 0.44%   |
| WDC WD10EZRZ-00HTKB0 1TB             | 1         | 0.44%   |
| WDC WD10EZEX-22BN5A0 1TB             | 1         | 0.44%   |
| WDC WD10EZEX-00RKKA0 1TB             | 1         | 0.44%   |
| WDC WD10EZEX-00BN5A0 1TB             | 1         | 0.44%   |
| WDC WD10EURX-61C57Y0 1TB             | 1         | 0.44%   |
| WDC WD10EALS-00Z8A0 1TB              | 1         | 0.44%   |
| WDC WD100EMAZ-00WJTA0 10TB           | 1         | 0.44%   |
| WDC WD1003FZEX-00K3CA0 1TB           | 1         | 0.44%   |
| WDC PC SN530 SDBPNPZ-1T00-1002 1TB   | 1         | 0.44%   |
| WDC PC SN520 SDAPNUW-256G-1102 256GB | 1         | 0.44%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 32        | 59     | 34.41%  |
| Seagate             | 30        | 55     | 32.26%  |
| Toshiba             | 13        | 21     | 13.98%  |
| Hitachi             | 7         | 10     | 7.53%   |
| HGST                | 5         | 5      | 5.38%   |
| Samsung Electronics | 3         | 3      | 3.23%   |
| Maxtor              | 1         | 1      | 1.08%   |
| Hewlett-Packard     | 1         | 1      | 1.08%   |
| Fujitsu             | 1         | 1      | 1.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 16        | 24     | 28.07%  |
| Kingston            | 8         | 10     | 14.04%  |
| Crucial             | 6         | 7      | 10.53%  |
| SanDisk             | 4         | 4      | 7.02%   |
| Patriot             | 2         | 3      | 3.51%   |
| China               | 2         | 3      | 3.51%   |
| Apple               | 2         | 3      | 3.51%   |
| A-DATA Technology   | 2         | 2      | 3.51%   |
| ZHITAI              | 1         | 1      | 1.75%   |
| WDC                 | 1         | 1      | 1.75%   |
| TO Exter            | 1         | 1      | 1.75%   |
| Team                | 1         | 1      | 1.75%   |
| Plextor             | 1         | 1      | 1.75%   |
| Netac               | 1         | 1      | 1.75%   |
| Micron Technology   | 1         | 1      | 1.75%   |
| JMicron Technology  | 1         | 1      | 1.75%   |
| Intenso             | 1         | 1      | 1.75%   |
| Intel               | 1         | 1      | 1.75%   |
| Hewlett-Packard     | 1         | 1      | 1.75%   |
| GOODRAM             | 1         | 1      | 1.75%   |
| Gigabyte Technology | 1         | 1      | 1.75%   |
| DUEX                | 1         | 1      | 1.75%   |
| Dogfish             | 1         | 1      | 1.75%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 67        | 156    | 41.61%  |
| SSD     | 52        | 71     | 32.3%   |
| NVMe    | 37        | 45     | 22.98%  |
| MMC     | 4         | 4      | 2.48%   |
| Unknown | 1         | 4      | 0.62%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 92        | 220    | 67.15%  |
| NVMe | 36        | 44     | 26.28%  |
| SAS  | 5         | 12     | 3.65%   |
| MMC  | 4         | 4      | 2.92%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 67        | 99     | 48.2%   |
| 0.51-1.0   | 37        | 64     | 26.62%  |
| 1.01-2.0   | 14        | 20     | 10.07%  |
| 3.01-4.0   | 9         | 21     | 6.47%   |
| 2.01-3.0   | 7         | 15     | 5.04%   |
| 4.01-10.0  | 3         | 3      | 2.16%   |
| 10.01-20.0 | 2         | 5      | 1.44%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 501-1000       | 27        | 22.88%  |
| 101-250        | 26        | 22.03%  |
| 251-500        | 19        | 16.1%   |
| Unknown        | 14        | 11.86%  |
| 1001-2000      | 12        | 10.17%  |
| 1-20           | 7         | 5.93%   |
| 2001-3000      | 5         | 4.24%   |
| More than 3000 | 4         | 3.39%   |
| 51-100         | 3         | 2.54%   |
| 21-50          | 1         | 0.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 25        | 20.83%  |
| 1-20           | 19        | 15.83%  |
| 21-50          | 16        | 13.33%  |
| 501-1000       | 16        | 13.33%  |
| Unknown        | 14        | 11.67%  |
| 251-500        | 12        | 10%     |
| 51-100         | 12        | 10%     |
| More than 3000 | 3         | 2.5%    |
| 1001-2000      | 3         | 2.5%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD5003ABYX-18WERA0 500GB        | 1         | 2      | 2.63%   |
| WDC WD5000LPCX-60VHAT1 500GB        | 1         | 1      | 2.63%   |
| WDC WD5000BPKX-60HPJT0 500GB        | 1         | 1      | 2.63%   |
| WDC WD5000AAKX-22ERMA0 500GB        | 1         | 1      | 2.63%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 1         | 1      | 2.63%   |
| WDC WD5000AAKS-00A7B2 500GB         | 1         | 1      | 2.63%   |
| WDC WD40EFRX-68WT0N0 4TB            | 1         | 2      | 2.63%   |
| WDC WD3200AAJS-65B4A0 320GB         | 1         | 1      | 2.63%   |
| WDC WD30EZRX-00M                    | 1         | 1      | 2.63%   |
| WDC WD30EFRX-68AX9N0 3TB            | 1         | 4      | 2.63%   |
| WDC WD20EFRX-68EUZN0 2TB            | 1         | 2      | 2.63%   |
| WDC WD10JPLX-00MBPT0 1TB            | 1         | 1      | 2.63%   |
| WDC WD10EZEX-00RKKA0 1TB            | 1         | 1      | 2.63%   |
| WDC WD10EALS-00Z8A0 1TB             | 1         | 2      | 2.63%   |
| WDC WD1003FZEX-00MK2A0 1TB          | 1         | 2      | 2.63%   |
| Toshiba MK2565GSXN 250GB            | 1         | 1      | 2.63%   |
| Seagate ST380011A 80GB              | 1         | 2      | 2.63%   |
| Seagate ST3500630AS 500GB           | 1         | 1      | 2.63%   |
| Seagate ST3500418AS 500GB           | 1         | 1      | 2.63%   |
| Seagate ST3500410AS 500GB           | 1         | 1      | 2.63%   |
| Seagate ST31000524AS 1TB            | 1         | 1      | 2.63%   |
| Seagate ST3000VX006-1HH166 3TB      | 1         | 1      | 2.63%   |
| Seagate ST2000DL003-9VT166 2TB      | 1         | 1      | 2.63%   |
| Seagate ST1000VM002-1SD102 1TB      | 1         | 1      | 2.63%   |
| Seagate ST1000NM0011 1TB            | 1         | 2      | 2.63%   |
| Seagate ST1000DM003-1ER162 1TB      | 1         | 2      | 2.63%   |
| SanDisk SDSA6MM-016G-1006 16GB SSD  | 1         | 1      | 2.63%   |
| Samsung Electronics SSD 870 EVO 1TB | 1         | 1      | 2.63%   |
| Plextor PX-128M6S 128GB SSD         | 1         | 1      | 2.63%   |
| Maxtor 4G120J6 128GB                | 1         | 1      | 2.63%   |
| Intel SSDSA2M080G2GC 80GB           | 1         | 1      | 2.63%   |
| Hitachi HUA723030ALA640 3TB         | 1         | 1      | 2.63%   |
| Hitachi HDS721050CLA660 500GB       | 1         | 1      | 2.63%   |
| Hitachi HDS721016CLA382 160GB       | 1         | 1      | 2.63%   |
| HGST HTS725050A7E630 500GB          | 1         | 1      | 2.63%   |
| HGST HTS545050A7E380 500GB          | 1         | 1      | 2.63%   |
| HGST HDN726040ALE614 4TB            | 1         | 1      | 2.63%   |
| DUEX DX300256A5xnEMLC 256GB SSD     | 1         | 1      | 2.63%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 13        | 23     | 37.14%  |
| Seagate             | 9         | 13     | 25.71%  |
| Hitachi             | 3         | 3      | 8.57%   |
| HGST                | 3         | 3      | 8.57%   |
| Toshiba             | 1         | 1      | 2.86%   |
| SanDisk             | 1         | 1      | 2.86%   |
| Samsung Electronics | 1         | 1      | 2.86%   |
| Plextor             | 1         | 1      | 2.86%   |
| Maxtor              | 1         | 1      | 2.86%   |
| Intel               | 1         | 1      | 2.86%   |
| DUEX                | 1         | 1      | 2.86%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 13        | 23     | 43.33%  |
| Seagate | 9         | 13     | 30%     |
| Hitachi | 3         | 3      | 10%     |
| HGST    | 3         | 3      | 10%     |
| Toshiba | 1         | 1      | 3.33%   |
| Maxtor  | 1         | 1      | 3.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 27        | 44     | 84.38%  |
| SSD  | 5         | 5      | 15.63%  |

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
| Works    | 97        | 203    | 67.36%  |
| Malfunc  | 32        | 49     | 22.22%  |
| Detected | 15        | 28     | 10.42%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 75        | 47.47%  |
| AMD                          | 27        | 17.09%  |
| Samsung Electronics          | 18        | 11.39%  |
| ASMedia Technology           | 5         | 3.16%   |
| Marvell Technology Group     | 4         | 2.53%   |
| SK hynix                     | 3         | 1.9%    |
| SanDisk                      | 3         | 1.9%    |
| Nvidia                       | 3         | 1.9%    |
| Broadcom / LSI               | 3         | 1.9%    |
| Realtek Semiconductor        | 2         | 1.27%   |
| Phison Electronics           | 2         | 1.27%   |
| JMicron Technology           | 2         | 1.27%   |
| Yangtze Memory Technologies  | 1         | 0.63%   |
| Toshiba America Info Systems | 1         | 0.63%   |
| Silicon Image                | 1         | 0.63%   |
| Micron/Crucial Technology    | 1         | 0.63%   |
| Micron Technology            | 1         | 0.63%   |
| LSI Logic / Symbios Logic    | 1         | 0.63%   |
| KIOXIA                       | 1         | 0.63%   |
| Kingston Technology Company  | 1         | 0.63%   |
| Biwin Storage Technology     | 1         | 0.63%   |
| Adaptec                      | 1         | 0.63%   |
| 3ware                        | 1         | 0.63%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 23        | 12.3%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 10        | 5.35%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 7         | 3.74%   |
| AMD 400 Series Chipset SATA Controller                                           | 7         | 3.74%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 6         | 3.21%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 5         | 2.67%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 5         | 2.67%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 4         | 2.14%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 4         | 2.14%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 4         | 2.14%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 1.6%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 3         | 1.6%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3         | 1.6%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 3         | 1.6%    |
| SK hynix Gold P31 SSD                                                            | 2         | 1.07%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 2         | 1.07%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 1.07%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 1.07%   |
| Realtek Realtek Non-Volatile memory controller                                   | 2         | 1.07%   |
| Nvidia MCP61 SATA Controller                                                     | 2         | 1.07%   |
| Nvidia MCP61 IDE                                                                 | 2         | 1.07%   |
| Intel SSD 600P Series                                                            | 2         | 1.07%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 1.07%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 2         | 1.07%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 2         | 1.07%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 2         | 1.07%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                              | 2         | 1.07%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 2         | 1.07%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 2         | 1.07%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 1.07%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 2         | 1.07%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 2         | 1.07%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 2         | 1.07%   |
| Yangtze Memory Non-Volatile memory controller                                    | 1         | 0.53%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                             | 1         | 0.53%   |
| SK hynix BC511                                                                   | 1         | 0.53%   |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller                 | 1         | 0.53%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 0.53%   |
| Samsung Electronics SATA controller                                              | 1         | 0.53%   |
| Samsung Apple PCIe SSD                                                           | 1         | 0.53%   |
| Phison NVMe Storage Controller                                                   | 1         | 0.53%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 1         | 0.53%   |
| Nvidia MCP79 AHCI Controller                                                     | 1         | 0.53%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1         | 0.53%   |
| Micron Non-Volatile memory controller                                            | 1         | 0.53%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                     | 1         | 0.53%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller with HyperDuo            | 1         | 0.53%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller                          | 1         | 0.53%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                            | 1         | 0.53%   |
| LSI Logic / Symbios Logic MegaRAID SAS 2008 [Falcon]                             | 1         | 0.53%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 1         | 0.53%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 0.53%   |
| JMicron JMB58x AHCI SATA controller                                              | 1         | 0.53%   |
| JMicron JMB368 IDE controller                                                    | 1         | 0.53%   |
| Intel Tiger Lake-LP SATA Controller                                              | 1         | 0.53%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 1         | 0.53%   |
| Intel SATA Controller [RAID mode]                                                | 1         | 0.53%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 1         | 0.53%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 0.53%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 0.53%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 89        | 57.42%  |
| NVMe | 36        | 23.23%  |
| IDE  | 14        | 9.03%   |
| RAID | 10        | 6.45%   |
| SAS  | 4         | 2.58%   |
| SCSI | 2         | 1.29%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 86        | 73.5%   |
| AMD    | 29        | 24.79%  |
| ARM    | 2         | 1.71%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 3         | 2.56%   |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz            | 2         | 1.71%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 2         | 1.71%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1.71%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 1.71%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 1.71%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 2         | 1.71%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 1.71%   |
| ARM Processor                                 | 2         | 1.71%   |
| AMD Ryzen 7 3800X 8-Core Processor            | 2         | 1.71%   |
| AMD Ryzen 5 3600 6-Core Processor             | 2         | 1.71%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 2         | 1.71%   |
| AMD FX-8350 Eight-Core Processor              | 2         | 1.71%   |
| Intel Xeon CPU X5680 @ 3.33GHz                | 1         | 0.85%   |
| Intel Xeon CPU X3450 @ 2.67GHz                | 1         | 0.85%   |
| Intel Xeon CPU E5-2697 v3 @ 2.60GHz           | 1         | 0.85%   |
| Intel Xeon CPU E5-2667 v2 @ 3.30GHz           | 1         | 0.85%   |
| Intel Xeon CPU E5-2660 v3 @ 2.60GHz           | 1         | 0.85%   |
| Intel Xeon CPU E5-2620 0 @ 2.00GHz            | 1         | 0.85%   |
| Intel Xeon CPU E5-2407 0 @ 2.20GHz            | 1         | 0.85%   |
| Intel Xeon CPU E5-1650 0 @ 3.20GHz            | 1         | 0.85%   |
| Intel Xeon CPU E3-1246 v3 @ 3.50GHz           | 1         | 0.85%   |
| Intel Xeon CPU 5160 @ 3.00GHz                 | 1         | 0.85%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz        | 1         | 0.85%   |
| Intel Pentium Dual CPU E2140 @ 1.60GHz        | 1         | 0.85%   |
| Intel Pentium CPU P6100 @ 2.00GHz             | 1         | 0.85%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.85%   |
| Intel Pentium CPU G640 @ 2.80GHz              | 1         | 0.85%   |
| Intel Pentium CPU G4560 @ 3.50GHz             | 1         | 0.85%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 1         | 0.85%   |
| Intel Core M-5Y51 CPU @ 1.10GHz               | 1         | 0.85%   |
| Intel Core i7-9700 CPU @ 3.00GHz              | 1         | 0.85%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 0.85%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 1         | 0.85%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 0.85%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 0.85%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 0.85%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 0.85%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 0.85%   |
| Intel Core i7-3930K CPU @ 3.20GHz             | 1         | 0.85%   |
| Intel Core i7-3840QM CPU @ 2.80GHz            | 1         | 0.85%   |
| Intel Core i7-3720QM CPU @ 2.60GHz            | 1         | 0.85%   |
| Intel Core i7-2860QM CPU @ 2.50GHz            | 1         | 0.85%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 1         | 0.85%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 1         | 0.85%   |
| Intel Core i5-9400 CPU @ 2.90GHz              | 1         | 0.85%   |
| Intel Core i5-8600K CPU @ 3.60GHz             | 1         | 0.85%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 0.85%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 0.85%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 0.85%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 0.85%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 1         | 0.85%   |
| Intel Core i5-4690 CPU @ 3.50GHz              | 1         | 0.85%   |
| Intel Core i5-4310M CPU @ 2.70GHz             | 1         | 0.85%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 0.85%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 0.85%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 1         | 0.85%   |
| Intel Core i5-3360M CPU @ 2.80GHz             | 1         | 0.85%   |
| Intel Core i5-3330 CPU @ 3.00GHz              | 1         | 0.85%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 0.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model              | Computers | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 21        | 17.95%  |
| Intel Core i7      | 18        | 15.38%  |
| Intel Xeon         | 12        | 10.26%  |
| Other              | 9         | 7.69%   |
| AMD Ryzen 5        | 8         | 6.84%   |
| Intel Core i3      | 7         | 5.98%   |
| Intel Pentium      | 5         | 4.27%   |
| AMD Ryzen 9        | 5         | 4.27%   |
| Intel Core 2 Duo   | 4         | 3.42%   |
| Intel Celeron      | 4         | 3.42%   |
| AMD Ryzen 7        | 4         | 3.42%   |
| AMD FX             | 4         | 3.42%   |
| Intel Core 2 Quad  | 2         | 1.71%   |
| Intel Atom         | 2         | 1.71%   |
| Intel Pentium Gold | 1         | 0.85%   |
| Intel Pentium Dual | 1         | 0.85%   |
| Intel Core M       | 1         | 0.85%   |
| Intel Core 2       | 1         | 0.85%   |
| AMD Ryzen Embedded | 1         | 0.85%   |
| AMD GX             | 1         | 0.85%   |
| AMD EPYC           | 1         | 0.85%   |
| AMD Athlon 64 X2   | 1         | 0.85%   |
| AMD Athlon         | 1         | 0.85%   |
| AMD A8             | 1         | 0.85%   |
| AMD A4             | 1         | 0.85%   |
| AMD A10            | 1         | 0.85%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 41        | 35.04%  |
| 4      | 40        | 34.19%  |
| 8      | 13        | 11.11%  |
| 6      | 10        | 8.55%   |
| 16     | 4         | 3.42%   |
| 12     | 4         | 3.42%   |
| 1      | 2         | 1.71%   |
| 14     | 1         | 0.85%   |
| 10     | 1         | 0.85%   |
| 3      | 1         | 0.85%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 110       | 94.02%  |
| 2      | 7         | 5.98%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 87        | 74.36%  |
| 1      | 30        | 25.64%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 114       | 97.44%  |
| Unknown        | 2         | 1.71%   |
| 32-bit         | 1         | 0.85%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 22        | 18.8%   |
| 0x306a9    | 9         | 7.69%   |
| 0x306c3    | 5         | 4.27%   |
| 0x206d7    | 5         | 4.27%   |
| 0x306d4    | 4         | 3.42%   |
| 0x1067a    | 4         | 3.42%   |
| 0x806ec    | 3         | 2.56%   |
| 0x806ea    | 3         | 2.56%   |
| 0x806d1    | 3         | 2.56%   |
| 0x806c1    | 3         | 2.56%   |
| 0x406e3    | 3         | 2.56%   |
| 0x406c4    | 3         | 2.56%   |
| 0x206a7    | 3         | 2.56%   |
| 0x08701013 | 3         | 2.56%   |
| 0x08108109 | 3         | 2.56%   |
| 0x906ed    | 2         | 1.71%   |
| 0x906ea    | 2         | 1.71%   |
| 0x6fd      | 2         | 1.71%   |
| 0x306f2    | 2         | 1.71%   |
| 0x106c2    | 2         | 1.71%   |
| 0x0a201016 | 2         | 1.71%   |
| 0x08701021 | 2         | 1.71%   |
| 0x0810100b | 2         | 1.71%   |
| 0x06001119 | 2         | 1.71%   |
| 0x06000822 | 2         | 1.71%   |
| 0xa0671    | 1         | 0.85%   |
| 0xa0660    | 1         | 0.85%   |
| 0xa0653    | 1         | 0.85%   |
| 0xa0652    | 1         | 0.85%   |
| 0x906e9    | 1         | 0.85%   |
| 0x806e9    | 1         | 0.85%   |
| 0x706a1    | 1         | 0.85%   |
| 0x6fa      | 1         | 0.85%   |
| 0x506e3    | 1         | 0.85%   |
| 0x40651    | 1         | 0.85%   |
| 0x306e4    | 1         | 0.85%   |
| 0x206c2    | 1         | 0.85%   |
| 0x20655    | 1         | 0.85%   |
| 0x106e5    | 1         | 0.85%   |
| 0x08600106 | 1         | 0.85%   |
| 0x0830104d | 1         | 0.85%   |
| 0x08001138 | 1         | 0.85%   |
| 0x07030105 | 1         | 0.85%   |
| 0x07000110 | 1         | 0.85%   |
| 0x06000852 | 1         | 0.85%   |
| 0x00000000 | 1         | 0.85%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 17        | 14.53%  |
| Haswell       | 11        | 9.4%    |
| Zen 2         | 10        | 8.55%   |
| IvyBridge     | 10        | 8.55%   |
| SandyBridge   | 9         | 7.69%   |
| Piledriver    | 6         | 5.13%   |
| Skylake       | 5         | 4.27%   |
| Core          | 5         | 4.27%   |
| Zen+          | 4         | 3.42%   |
| Zen           | 4         | 3.42%   |
| Silvermont    | 4         | 3.42%   |
| Penryn        | 4         | 3.42%   |
| Icelake       | 4         | 3.42%   |
| Broadwell     | 4         | 3.42%   |
| Westmere      | 3         | 2.56%   |
| TigerLake     | 3         | 2.56%   |
| CometLake     | 3         | 2.56%   |
| Zen 3         | 2         | 1.71%   |
| Bonnell       | 2         | 1.71%   |
| Unknown       | 2         | 1.71%   |
| Puma          | 1         | 0.85%   |
| Nehalem       | 1         | 0.85%   |
| K8 Hammer     | 1         | 0.85%   |
| Jaguar        | 1         | 0.85%   |
| Goldmont plus | 1         | 0.85%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 55        | 44%     |
| Nvidia                     | 34        | 27.2%   |
| AMD                        | 32        | 25.6%   |
| Matrox Electronics Systems | 4         | 3.2%    |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 5         | 3.91%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 3.13%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 3.13%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 3.13%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 3.13%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 3.13%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 3         | 2.34%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 3         | 2.34%   |
| Intel UHD Graphics 620                                                                   | 3         | 2.34%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 2.34%   |
| Intel HD Graphics 620                                                                    | 3         | 2.34%   |
| Intel HD Graphics 5500                                                                   | 3         | 2.34%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 2.34%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 2.34%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 1.56%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 1.56%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 2         | 1.56%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 1.56%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.56%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 1.56%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 1.56%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2         | 1.56%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 1.56%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 2         | 1.56%   |
| AMD Renoir                                                                               | 2         | 1.56%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 2         | 1.56%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1         | 0.78%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 1         | 0.78%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 0.78%   |
| Nvidia GP107GL [Quadro P1000]                                                            | 1         | 0.78%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 0.78%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 1         | 0.78%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1         | 0.78%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1         | 0.78%   |
| Nvidia GM204GLM [Quadro M3000M]                                                          | 1         | 0.78%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1         | 0.78%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1         | 0.78%   |
| Nvidia GK110GL [Quadro K5200]                                                            | 1         | 0.78%   |
| Nvidia GK107M [GeForce GT 745M]                                                          | 1         | 0.78%   |
| Nvidia GK107 [GeForce GT 640]                                                            | 1         | 0.78%   |
| Nvidia GK104GL [Quadro K5000]                                                            | 1         | 0.78%   |
| Nvidia GF108GL [Quadro 600]                                                              | 1         | 0.78%   |
| Nvidia GF106GLM [Quadro 2000M]                                                           | 1         | 0.78%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 0.78%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                                       | 1         | 0.78%   |
| Nvidia G84 [GeForce 8600 GT]                                                             | 1         | 0.78%   |
| Nvidia G80GL [Quadro FX 4600]                                                            | 1         | 0.78%   |
| Nvidia G71GL [Quadro FX 1500]                                                            | 1         | 0.78%   |
| Nvidia C79 [ION]                                                                         | 1         | 0.78%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 1         | 0.78%   |
| Matrox Electronics Systems MGA G200eH3                                                   | 1         | 0.78%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller                 | 1         | 0.78%   |
| Matrox Electronics Systems G200eR2                                                       | 1         | 0.78%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1         | 0.78%   |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller                           | 1         | 0.78%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1         | 0.78%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 1         | 0.78%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 0.78%   |
| Intel HD Graphics 5300                                                                   | 1         | 0.78%   |
| Intel HD Graphics 530                                                                    | 1         | 0.78%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 47        | 40.17%  |
| 1 x AMD        | 30        | 25.64%  |
| 1 x Nvidia     | 22        | 18.8%   |
| Intel + Nvidia | 8         | 6.84%   |
| 1 x Matrox     | 4         | 3.42%   |
| Other          | 3         | 2.56%   |
| AMD + Nvidia   | 2         | 1.71%   |
| 2 x Nvidia     | 1         | 0.85%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 89        | 76.07%  |
| Proprietary | 18        | 15.38%  |
| Unknown     | 10        | 8.55%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 64        | 54.24%  |
| 0.51-1.0   | 14        | 11.86%  |
| 1.01-2.0   | 11        | 9.32%   |
| 3.01-4.0   | 8         | 6.78%   |
| 7.01-8.0   | 7         | 5.93%   |
| 0.01-0.5   | 6         | 5.08%   |
| 5.01-6.0   | 4         | 3.39%   |
| 8.01-16.0  | 3         | 2.54%   |
| 2.01-3.0   | 1         | 0.85%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Samsung Electronics  | 13        | 10.66%  |
| LG Display           | 12        | 9.84%   |
| BOE                  | 12        | 9.84%   |
| Chimei Innolux       | 10        | 8.2%    |
| Hewlett-Packard      | 8         | 6.56%   |
| Dell                 | 8         | 6.56%   |
| AU Optronics         | 8         | 6.56%   |
| BenQ                 | 6         | 4.92%   |
| Goldstar             | 5         | 4.1%    |
| Sharp                | 4         | 3.28%   |
| Ancor Communications | 4         | 3.28%   |
| Acer                 | 4         | 3.28%   |
| Lenovo               | 3         | 2.46%   |
| ViewSonic            | 2         | 1.64%   |
| Iiyama               | 2         | 1.64%   |
| ASUSTek Computer     | 2         | 1.64%   |
| Xiaomi               | 1         | 0.82%   |
| Wacom                | 1         | 0.82%   |
| Unknown              | 1         | 0.82%   |
| UGD                  | 1         | 0.82%   |
| Toshiba              | 1         | 0.82%   |
| Sony                 | 1         | 0.82%   |
| PANDA                | 1         | 0.82%   |
| Panasonic            | 1         | 0.82%   |
| ONN                  | 1         | 0.82%   |
| NEC Computers        | 1         | 0.82%   |
| JVC                  | 1         | 0.82%   |
| IOD                  | 1         | 0.82%   |
| Gigabyte Technology  | 1         | 0.82%   |
| GDH                  | 1         | 0.82%   |
| Eizo                 | 1         | 0.82%   |
| DPC                  | 1         | 0.82%   |
| Apple                | 1         | 0.82%   |
| AOC                  | 1         | 0.82%   |
| Unknown              | 1         | 0.82%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0353 1366x768 345x194mm 15.6-inch          | 2         | 1.6%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 2         | 1.6%    |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch        | 2         | 1.6%    |
| Xiaomi DPF90435 XMD009A 2224x1668 341x192mm 15.4-inch                | 1         | 0.8%    |
| Wacom Cintiq 22HDT WAC1037 1920x1080 476x268mm 21.5-inch             | 1         | 0.8%    |
| ViewSonic LCD Monitor VX2276 Series 1920x1080                        | 1         | 0.8%    |
| ViewSonic LCD Monitor VA2448 SERIES 1920x1080                        | 1         | 0.8%    |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch            | 1         | 0.8%    |
| UGD LCD Monitor UGD1302 1920x1080 290x160mm 13.0-inch                | 1         | 0.8%    |
| Toshiba TV TSB0206 1920x1080 886x498mm 40.0-inch                     | 1         | 0.8%    |
| Sony TV SNY8102 1360x768 1600x900mm 72.3-inch                        | 1         | 0.8%    |
| Sharp LQ173M1JW05 SHP14EC 1920x1080 380x210mm 17.1-inch              | 1         | 0.8%    |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch              | 1         | 0.8%    |
| Sharp LQ125T1JW02 SHP142F 2560x1440 277x155mm 12.5-inch              | 1         | 0.8%    |
| Sharp LCD Monitor SHP14C4 1920x1080 344x194mm 15.5-inch              | 1         | 0.8%    |
| Samsung Electronics SyncMaster SAM0578 1920x1080 476x268mm 21.5-inch | 1         | 0.8%    |
| Samsung Electronics SyncMaster SAM04DF 1360x768 410x230mm 18.5-inch  | 1         | 0.8%    |
| Samsung Electronics SyncMaster SAM0428 1680x1050 459x296mm 21.5-inch | 1         | 0.8%    |
| Samsung Electronics SyncMaster SAM0248 1280x1024 380x300mm 19.1-inch | 1         | 0.8%    |
| Samsung Electronics SyncMaster SAM01AD 1600x1200 408x306mm 20.1-inch | 1         | 0.8%    |
| Samsung Electronics SMS27A650 SAM082D 1920x1080 598x336mm 27.0-inch  | 1         | 0.8%    |
| Samsung Electronics SMS19A100 SAM0867 1366x768 410x230mm 18.5-inch   | 1         | 0.8%    |
| Samsung Electronics SMB2430L SAM0644 1920x1080 521x293mm 23.5-inch   | 1         | 0.8%    |
| Samsung Electronics SM2333T SAM0736 1920x1080 477x268mm 21.5-inch    | 1         | 0.8%    |
| Samsung Electronics S24D390 SAM0B65 1920x1080 520x290mm 23.4-inch    | 1         | 0.8%    |
| Samsung Electronics S22D300 SAM0B3E 1920x1080 477x268mm 21.5-inch    | 1         | 0.8%    |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch | 1         | 0.8%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 1         | 0.8%    |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch | 1         | 0.8%    |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch              | 1         | 0.8%    |
| Panasonic LCD Monitor MEI96A2 3840x2160 382x215mm 17.3-inch          | 1         | 0.8%    |
| ONN 100002480 ONN0101 1920x1080 470x290mm 21.7-inch                  | 1         | 0.8%    |
| NEC Computers LCD2490WUXi NEC66CE 1920x1200 518x324mm 24.1-inch      | 1         | 0.8%    |
| LG Display LCD Monitor LGD0625 1920x1080 344x194mm 15.5-inch         | 1         | 0.8%    |
| LG Display LCD Monitor LGD0599 1920x1080 309x174mm 14.0-inch         | 1         | 0.8%    |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch         | 1         | 0.8%    |
| LG Display LCD Monitor LGD0508 1366x768 309x174mm 14.0-inch          | 1         | 0.8%    |
| LG Display LCD Monitor LGD03D7 1366x768 310x174mm 14.0-inch          | 1         | 0.8%    |
| LG Display LCD Monitor LGD032C 1920x1080 344x194mm 15.5-inch         | 1         | 0.8%    |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch          | 1         | 0.8%    |
| LG Display LCD Monitor LGD02D9 1920x1080 344x194mm 15.5-inch         | 1         | 0.8%    |
| LG Display LCD Monitor LGD028A 1366x768 344x194mm 15.5-inch          | 1         | 0.8%    |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch          | 1         | 0.8%    |
| Lenovo LEN L171 LEN24C9 1280x1024 337x270mm 17.0-inch                | 1         | 0.8%    |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch             | 1         | 0.8%    |
| Lenovo LCD Monitor LEN4035 1280x800 303x190mm 14.1-inch              | 1         | 0.8%    |
| JVC FPDEUFT3 JVC21BE 1920x540                                        | 1         | 0.8%    |
| IOD LCD-GL211X IOD151D 1920x1080 458x258mm 20.7-inch                 | 1         | 0.8%    |
| Iiyama PLE2207WS IVM5609 1680x1050 465x291mm 21.6-inch               | 1         | 0.8%    |
| Iiyama PL2783Q IVM661F 2560x1440 597x336mm 27.0-inch                 | 1         | 0.8%    |
| Hewlett-Packard ZR2740w HWP2957 2560x1440 597x336mm 27.0-inch        | 1         | 0.8%    |
| Hewlett-Packard Z24i HWP309E 1920x1200 520x320mm 24.0-inch           | 1         | 0.8%    |
| Hewlett-Packard P223 HPN3392 1920x1080 477x268mm 21.5-inch           | 1         | 0.8%    |
| Hewlett-Packard LE1851w HWP2840 1366x768 413x234mm 18.7-inch         | 1         | 0.8%    |
| Hewlett-Packard ALL-in-One HPN4021 1920x1080 476x268mm 21.5-inch     | 1         | 0.8%    |
| Hewlett-Packard 27w HPN3494 1920x1080 598x336mm 27.0-inch            | 1         | 0.8%    |
| Hewlett-Packard 27m HPN3579 1920x1080 598x336mm 27.0-inch            | 1         | 0.8%    |
| Hewlett-Packard 2309 HWP2823 1920x1080 510x287mm 23.0-inch           | 1         | 0.8%    |
| Goldstar W2242 GSM5678 1680x1050 474x296mm 22.0-inch                 | 1         | 0.8%    |
| Goldstar W2242 GSM5677 1680x1050 474x296mm 22.0-inch                 | 1         | 0.8%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 57        | 47.9%   |
| 1366x768 (WXGA)    | 24        | 20.17%  |
| 1280x1024 (SXGA)   | 6         | 5.04%   |
| 3840x2160 (4K)     | 5         | 4.2%    |
| 2560x1440 (QHD)    | 5         | 4.2%    |
| 1920x1200 (WUXGA)  | 4         | 3.36%   |
| 1680x1050 (WSXGA+) | 4         | 3.36%   |
| 1600x900 (HD+)     | 3         | 2.52%   |
| 3440x1440          | 2         | 1.68%   |
| 1360x768           | 2         | 1.68%   |
| 3200x1080          | 1         | 0.84%   |
| 2288x1287          | 1         | 0.84%   |
| 2256x1504          | 1         | 0.84%   |
| 1920x540           | 1         | 0.84%   |
| 1600x1200          | 1         | 0.84%   |
| 1280x800 (WXGA)    | 1         | 0.84%   |
| Unknown            | 1         | 0.84%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 28        | 22.95%  |
| 21      | 13        | 10.66%  |
| 24      | 12        | 9.84%   |
| 27      | 10        | 8.2%    |
| 17      | 9         | 7.38%   |
| 14      | 9         | 7.38%   |
| 13      | 9         | 7.38%   |
| 23      | 7         | 5.74%   |
| Unknown | 5         | 4.1%    |
| 20      | 4         | 3.28%   |
| 18      | 3         | 2.46%   |
| 12      | 3         | 2.46%   |
| 19      | 2         | 1.64%   |
| 142     | 1         | 0.82%   |
| 74      | 1         | 0.82%   |
| 72      | 1         | 0.82%   |
| 52      | 1         | 0.82%   |
| 34      | 1         | 0.82%   |
| 32      | 1         | 0.82%   |
| 22      | 1         | 0.82%   |
| 16      | 1         | 0.82%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 46        | 38.02%  |
| 501-600        | 27        | 22.31%  |
| 401-500        | 21        | 17.36%  |
| 351-400        | 9         | 7.44%   |
| 201-300        | 6         | 4.96%   |
| Unknown        | 5         | 4.13%   |
| 701-800        | 2         | 1.65%   |
| 1501-2000      | 2         | 1.65%   |
| More than 2000 | 1         | 0.83%   |
| 601-700        | 1         | 0.83%   |
| 1001-1500      | 1         | 0.83%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 84        | 75.68%  |
| 16/10   | 10        | 9.01%   |
| 5/4     | 4         | 3.6%    |
| Unknown | 4         | 3.6%    |
| 3/2     | 3         | 2.7%    |
| 6/5     | 2         | 1.8%    |
| 4/3     | 1         | 0.9%    |
| 32/9    | 1         | 0.9%    |
| 21/9    | 1         | 0.9%    |
| 1.00    | 1         | 0.9%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 29        | 24.17%  |
| 201-250        | 23        | 19.17%  |
| 81-90          | 16        | 13.33%  |
| 301-350        | 10        | 8.33%   |
| 151-200        | 8         | 6.67%   |
| 141-150        | 7         | 5.83%   |
| 251-300        | 6         | 5%      |
| 121-130        | 5         | 4.17%   |
| Unknown        | 5         | 4.17%   |
| More than 1000 | 4         | 3.33%   |
| 61-70          | 3         | 2.5%    |
| 71-80          | 2         | 1.67%   |
| 351-500        | 2         | 1.67%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 42        | 34.71%  |
| 101-120       | 34        | 28.1%   |
| 121-160       | 30        | 24.79%  |
| Unknown       | 5         | 4.13%   |
| 1-50          | 4         | 3.31%   |
| More than 240 | 3         | 2.48%   |
| 161-240       | 3         | 2.48%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 88        | 75.21%  |
| 2     | 14        | 11.97%  |
| 0     | 11        | 9.4%    |
| 3     | 3         | 2.56%   |
| 4     | 1         | 0.85%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 71        | 41.52%  |
| Realtek Semiconductor    | 58        | 33.92%  |
| Qualcomm Atheros         | 12        | 7.02%   |
| Broadcom                 | 8         | 4.68%   |
| Ralink Technology        | 4         | 2.34%   |
| Broadcom Limited         | 3         | 1.75%   |
| TP-Link                  | 2         | 1.17%   |
| Nvidia                   | 2         | 1.17%   |
| ASIX Electronics         | 2         | 1.17%   |
| VIA Technologies         | 1         | 0.58%   |
| Sierra Wireless          | 1         | 0.58%   |
| Ralink                   | 1         | 0.58%   |
| Micro Star International | 1         | 0.58%   |
| Mellanox Technologies    | 1         | 0.58%   |
| Marvell Technology Group | 1         | 0.58%   |
| Hewlett-Packard          | 1         | 0.58%   |
| Dell                     | 1         | 0.58%   |
| Chelsio Communications   | 1         | 0.58%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 40        | 19.05%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 8         | 3.81%   |
| Intel I211 Gigabit Network Connection                                                 | 7         | 3.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 6         | 2.86%   |
| Intel 82574L Gigabit Network Connection                                               | 5         | 2.38%   |
| Ralink MT7601U Wireless Adapter                                                       | 4         | 1.9%    |
| Intel Wireless-AC 9260                                                                | 4         | 1.9%    |
| Intel Wireless 8265 / 8275                                                            | 4         | 1.9%    |
| Intel Wireless 7260                                                                   | 4         | 1.9%    |
| Intel Wi-Fi 6 AX200                                                                   | 4         | 1.9%    |
| Intel Ethernet Connection (2) I218-V                                                  | 4         | 1.9%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 3         | 1.43%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 3         | 1.43%   |
| Realtek RTL8125 2.5GbE Controller                                                     | 3         | 1.43%   |
| Intel Wireless 7265                                                                   | 3         | 1.43%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 3         | 1.43%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 3         | 1.43%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 3         | 1.43%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                              | 2         | 0.95%   |
| Realtek Killer E3000 2.5GbE Controller                                                | 2         | 0.95%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 2         | 0.95%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                             | 2         | 0.95%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                      | 2         | 0.95%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                        | 2         | 0.95%   |
| Intel Wireless 8260                                                                   | 2         | 0.95%   |
| Intel Wireless 3160                                                                   | 2         | 0.95%   |
| Intel Wi-Fi 6 AX201                                                                   | 2         | 0.95%   |
| Intel Tiger Lake PCH CNVi WiFi                                                        | 2         | 0.95%   |
| Intel I350 Gigabit Network Connection                                                 | 2         | 0.95%   |
| Intel Ethernet Connection I217-V                                                      | 2         | 0.95%   |
| Intel Ethernet Connection (7) I219-V                                                  | 2         | 0.95%   |
| Intel Ethernet Connection (4) I219-LM                                                 | 2         | 0.95%   |
| Intel Ethernet Connection (3) I218-LM                                                 | 2         | 0.95%   |
| Intel Ethernet Connection (2) I219-LM                                                 | 2         | 0.95%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 2         | 0.95%   |
| Intel Centrino Ultimate-N 6300                                                        | 2         | 0.95%   |
| Intel 82579V Gigabit Network Connection                                               | 2         | 0.95%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                                      | 2         | 0.95%   |
| VIA VT6105/VT6106S [Rhine-III]                                                        | 1         | 0.48%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                                                 | 1         | 0.48%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                            | 1         | 0.48%   |
| Sierra Wireless EM7305                                                                | 1         | 0.48%   |
| Realtek USB 10/100/1G/2.5G LAN                                                        | 1         | 0.48%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 1         | 0.48%   |
| Realtek RTL8723DE Wireless Network Adapter                                            | 1         | 0.48%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                       | 1         | 0.48%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1         | 0.48%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                               | 1         | 0.48%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                 | 1         | 0.48%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                             | 1         | 0.48%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                             | 1         | 0.48%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 1         | 0.48%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                        | 1         | 0.48%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 1         | 0.48%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                      | 1         | 0.48%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                         | 1         | 0.48%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 0.48%   |
| Nvidia MCP79 Ethernet                                                                 | 1         | 0.48%   |
| Nvidia MCP61 Ethernet                                                                 | 1         | 0.48%   |
| Micro Star International MS-3871 802.11bgn Wireless Module [Ralink RT8070]            | 1         | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 47        | 58.02%  |
| Realtek Semiconductor    | 11        | 13.58%  |
| Qualcomm Atheros         | 9         | 11.11%  |
| Ralink Technology        | 4         | 4.94%   |
| Broadcom                 | 3         | 3.7%    |
| TP-Link                  | 2         | 2.47%   |
| Sierra Wireless          | 1         | 1.23%   |
| Ralink                   | 1         | 1.23%   |
| Micro Star International | 1         | 1.23%   |
| Dell                     | 1         | 1.23%   |
| Broadcom Limited         | 1         | 1.23%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Ralink MT7601U Wireless Adapter                                                       | 4         | 4.94%   |
| Intel Wireless-AC 9260                                                                | 4         | 4.94%   |
| Intel Wireless 8265 / 8275                                                            | 4         | 4.94%   |
| Intel Wireless 7260                                                                   | 4         | 4.94%   |
| Intel Wi-Fi 6 AX200                                                                   | 4         | 4.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 3         | 3.7%    |
| Realtek RTL8188EE Wireless Network Adapter                                            | 3         | 3.7%    |
| Intel Wireless 7265                                                                   | 3         | 3.7%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 3         | 3.7%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 3         | 3.7%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 3         | 3.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 2         | 2.47%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                      | 2         | 2.47%   |
| Intel Wireless 8260                                                                   | 2         | 2.47%   |
| Intel Wireless 3160                                                                   | 2         | 2.47%   |
| Intel Wi-Fi 6 AX201                                                                   | 2         | 2.47%   |
| Intel Tiger Lake PCH CNVi WiFi                                                        | 2         | 2.47%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 2         | 2.47%   |
| Intel Centrino Ultimate-N 6300                                                        | 2         | 2.47%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                                                 | 1         | 1.23%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                            | 1         | 1.23%   |
| Sierra Wireless EM7305                                                                | 1         | 1.23%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 1         | 1.23%   |
| Realtek RTL8723DE Wireless Network Adapter                                            | 1         | 1.23%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                       | 1         | 1.23%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1         | 1.23%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                               | 1         | 1.23%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                             | 1         | 1.23%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 1         | 1.23%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                        | 1         | 1.23%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 1         | 1.23%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                      | 1         | 1.23%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 1.23%   |
| Micro Star International MS-3871 802.11bgn Wireless Module [Ralink RT8070]            | 1         | 1.23%   |
| Intel Wireless 3165                                                                   | 1         | 1.23%   |
| Intel WiFi Link 5100                                                                  | 1         | 1.23%   |
| Intel Gemini Lake PCH CNVi WiFi                                                       | 1         | 1.23%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 1         | 1.23%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 1         | 1.23%   |
| Intel Centrino Wireless-N 2230                                                        | 1         | 1.23%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 1         | 1.23%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                                                  | 1         | 1.23%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                                               | 1         | 1.23%   |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 1         | 1.23%   |
| Broadcom BCM4321 802.11a/b/g/n                                                        | 1         | 1.23%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 1         | 1.23%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 55        | 46.22%  |
| Intel                    | 42        | 35.29%  |
| Qualcomm Atheros         | 6         | 5.04%   |
| Broadcom                 | 6         | 5.04%   |
| Nvidia                   | 2         | 1.68%   |
| Broadcom Limited         | 2         | 1.68%   |
| ASIX Electronics         | 2         | 1.68%   |
| VIA Technologies         | 1         | 0.84%   |
| Mellanox Technologies    | 1         | 0.84%   |
| Marvell Technology Group | 1         | 0.84%   |
| Chelsio Communications   | 1         | 0.84%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 40        | 31.25%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 8         | 6.25%   |
| Intel I211 Gigabit Network Connection                                         | 7         | 5.47%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 6         | 4.69%   |
| Intel 82574L Gigabit Network Connection                                       | 5         | 3.91%   |
| Intel Ethernet Connection (2) I218-V                                          | 4         | 3.13%   |
| Realtek RTL8125 2.5GbE Controller                                             | 3         | 2.34%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 2         | 1.56%   |
| Realtek Killer E3000 2.5GbE Controller                                        | 2         | 1.56%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 2         | 1.56%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 2         | 1.56%   |
| Intel I350 Gigabit Network Connection                                         | 2         | 1.56%   |
| Intel Ethernet Connection I217-V                                              | 2         | 1.56%   |
| Intel Ethernet Connection (7) I219-V                                          | 2         | 1.56%   |
| Intel Ethernet Connection (4) I219-LM                                         | 2         | 1.56%   |
| Intel Ethernet Connection (3) I218-LM                                         | 2         | 1.56%   |
| Intel Ethernet Connection (2) I219-LM                                         | 2         | 1.56%   |
| Intel 82579V Gigabit Network Connection                                       | 2         | 1.56%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 2         | 1.56%   |
| VIA VT6105/VT6106S [Rhine-III]                                                | 1         | 0.78%   |
| Realtek USB 10/100/1G/2.5G LAN                                                | 1         | 0.78%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1         | 0.78%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1         | 0.78%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1         | 0.78%   |
| Nvidia MCP79 Ethernet                                                         | 1         | 0.78%   |
| Nvidia MCP61 Ethernet                                                         | 1         | 0.78%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]                         | 1         | 0.78%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                       | 1         | 0.78%   |
| Intel Ethernet Connection I219-LM                                             | 1         | 0.78%   |
| Intel Ethernet Connection I218-V                                              | 1         | 0.78%   |
| Intel Ethernet Connection (4) I219-V                                          | 1         | 0.78%   |
| Intel Ethernet Connection (2) I219-V                                          | 1         | 0.78%   |
| Intel Ethernet Connection (2) I218-LM                                         | 1         | 0.78%   |
| Intel Ethernet Connection (12) I219-V                                         | 1         | 0.78%   |
| Intel Ethernet Connection (10) I219-V                                         | 1         | 0.78%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 1         | 0.78%   |
| Intel 82576 Gigabit Network Connection                                        | 1         | 0.78%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 0.78%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1         | 0.78%   |
| Intel 82567LM Gigabit Network Connection                                      | 1         | 0.78%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                          | 1         | 0.78%   |
| Chelsio T320 10GbE Dual Port Adapter                                          | 1         | 0.78%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                             | 1         | 0.78%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                             | 1         | 0.78%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                       | 1         | 0.78%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                       | 1         | 0.78%   |
| Broadcom Limited NetXtreme BCM5756ME Gigabit Ethernet PCI Express             | 1         | 0.78%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express               | 1         | 0.78%   |
| ASIX AX88772B                                                                 | 1         | 0.78%   |
| ASIX AX88179 Gigabit Ethernet                                                 | 1         | 0.78%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 108       | 57.75%  |
| WiFi     | 78        | 41.71%  |
| Modem    | 1         | 0.53%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 66        | 56.9%   |
| WiFi     | 50        | 43.1%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 65        | 55.08%  |
| 1     | 37        | 31.36%  |
| 3     | 6         | 5.08%   |
| 4     | 5         | 4.24%   |
| 0     | 4         | 3.39%   |
| 5     | 1         | 0.85%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 107       | 90.68%  |
| Yes  | 11        | 9.32%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 41        | 56.16%  |
| Cambridge Silicon Radio         | 12        | 16.44%  |
| Realtek Semiconductor           | 6         | 8.22%   |
| Broadcom                        | 5         | 6.85%   |
| Qualcomm Atheros Communications | 3         | 4.11%   |
| Micro Star International        | 2         | 2.74%   |
| Apple                           | 2         | 2.74%   |
| Toshiba                         | 1         | 1.37%   |
| Foxconn / Hon Hai               | 1         | 1.37%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 17        | 23.29%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 12        | 16.44%  |
| Intel AX201 Bluetooth                               | 6         | 8.22%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 5.48%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 4         | 5.48%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 5.48%   |
| Intel AX200 Bluetooth                               | 4         | 5.48%   |
| Intel AX210 Bluetooth                               | 3         | 4.11%   |
| Realtek Bluetooth Radio                             | 2         | 2.74%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 2.74%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 2.74%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2         | 2.74%   |
| Toshiba Askey Bluetooth Module                      | 1         | 1.37%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 1.37%   |
| Micro Star International Bluetooth Dongle           | 1         | 1.37%   |
| Micro Star International Bluetooth Device           | 1         | 1.37%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.37%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 1.37%   |
| Broadcom HP Portable SoftSailing                    | 1         | 1.37%   |
| Broadcom BCM20702A0                                 | 1         | 1.37%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.37%   |
| Apple Bluetooth USB Host Controller                 | 1         | 1.37%   |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 1         | 1.37%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 77        | 49.04%  |
| AMD                    | 35        | 22.29%  |
| Nvidia                 | 28        | 17.83%  |
| Creative Labs          | 7         | 4.46%   |
| C-Media Electronics    | 4         | 2.55%   |
| VIA Technologies       | 1         | 0.64%   |
| Texas Instruments      | 1         | 0.64%   |
| M-Audio                | 1         | 0.64%   |
| Generalplus Technology | 1         | 0.64%   |
| EGO SYStems            | 1         | 0.64%   |
| ASUSTek Computer       | 1         | 0.64%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 10        | 5.24%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 9         | 4.71%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 9         | 4.71%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 8         | 4.19%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 7         | 3.66%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 6         | 3.14%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 2.62%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 2.62%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 5         | 2.62%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 4         | 2.09%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 2.09%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 4         | 2.09%   |
| Intel Broadwell-U Audio Controller                                                                | 4         | 2.09%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 2.09%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 2.09%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 2.09%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 4         | 2.09%   |
| AMD FCH Azalia Controller                                                                         | 4         | 2.09%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 1.57%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 3         | 1.57%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 1.57%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 1.57%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 3         | 1.57%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 1.57%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                                     | 3         | 1.57%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 3         | 1.57%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 1.05%   |
| Nvidia MCP61 High Definition Audio                                                                | 2         | 1.05%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 1.05%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 2         | 1.05%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 1.05%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 1.05%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 1.05%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 1.05%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 1.05%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 1.05%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 1.05%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 2         | 1.05%   |
| AMD Navi 10 HDMI Audio                                                                            | 2         | 1.05%   |
| VIA Technologies VT1720/24 [Envy24PT/HT] PCI Multi-Channel Audio Controller                       | 1         | 0.52%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.52%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.52%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.52%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.52%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.52%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1         | 0.52%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1         | 0.52%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.52%   |
| Nvidia GK110 High Definition Audio Controller                                                     | 1         | 0.52%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.52%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 0.52%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 0.52%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.52%   |
| Nvidia GA102 High Definition Audio Controller                                                     | 1         | 0.52%   |
| M-Audio M-Audio MobilePre                                                                         | 1         | 0.52%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 1         | 0.52%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.52%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 0.52%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 1         | 0.52%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 1         | 0.52%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 26        | 20.97%  |
| Kingston            | 21        | 16.94%  |
| Samsung Electronics | 18        | 14.52%  |
| Crucial             | 11        | 8.87%   |
| Corsair             | 9         | 7.26%   |
| Unknown             | 7         | 5.65%   |
| Micron Technology   | 7         | 5.65%   |
| Team                | 4         | 3.23%   |
| Transcend           | 2         | 1.61%   |
| Ramaxel Technology  | 2         | 1.61%   |
| A-DATA Technology   | 2         | 1.61%   |
| Strontium           | 1         | 0.81%   |
| Smart               | 1         | 0.81%   |
| Silicon Power       | 1         | 0.81%   |
| Neo Forza           | 1         | 0.81%   |
| Nanya Technology    | 1         | 0.81%   |
| HPE                 | 1         | 0.81%   |
| Goodram             | 1         | 0.81%   |
| GLOWAY              | 1         | 0.81%   |
| G.Skill             | 1         | 0.81%   |
| Essencore Limited   | 1         | 0.81%   |
| Elpida              | 1         | 0.81%   |
| Avant               | 1         | 0.81%   |
| AMD                 | 1         | 0.81%   |
| A Force             | 1         | 0.81%   |
| Unknown             | 1         | 0.81%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB DIMM SDRAM                                | 2         | 1.46%   |
| Team RAM TEAMGROUP-UD4-3200 32GB DIMM DDR4 3200MT/s                 | 2         | 1.46%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 2         | 1.46%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 2         | 1.46%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                           | 1         | 0.73%   |
| Unknown RAM Module 4096MB DIMM DDR3 65535MT/s                       | 1         | 0.73%   |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s                          | 1         | 0.73%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                              | 1         | 0.73%   |
| Unknown RAM Module 1024MB SODIMM SDRAM                              | 1         | 0.73%   |
| Unknown RAM Module 1024MB DIMM DDR 800MT/s                          | 1         | 0.73%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                              | 1         | 0.73%   |
| Transcend RAM TS256MLQ72V6U 2GB DIMM DDR2 667MT/s                   | 1         | 0.73%   |
| Transcend RAM JM1600KLN-8GK 4096MB DIMM DDR3 1600MT/s               | 1         | 0.73%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3600MT/s                  | 1         | 0.73%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3600MT/s                 | 1         | 0.73%   |
| Strontium RAM SRT4G86U1-P9H 4096MB DIMM DDR3 1333MT/s               | 1         | 0.73%   |
| Smart RAM SH5641G8FJ8NWRNSQG 8GB SODIMM DDR3 1600MT/s               | 1         | 0.73%   |
| SK hynix RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s             | 1         | 0.73%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                     | 1         | 0.73%   |
| SK hynix RAM HYMP512F72CP8N3-Y5 1024MB FB-DIMM DDR2 667MT/s         | 1         | 0.73%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s               | 1         | 0.73%   |
| SK hynix RAM HMT41GV7BMR4A-H9 16GB DIMM 1333MT/s                    | 1         | 0.73%   |
| SK hynix RAM HMT41GU6BFR8A-PB 8192MB DIMM DDR3 2000MT/s             | 1         | 0.73%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s              | 1         | 0.73%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 1         | 0.73%   |
| SK hynix RAM HMT351U6BFR8C-H9 4096MB DIMM DDR3 1333MT/s             | 1         | 0.73%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.73%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s              | 1         | 0.73%   |
| SK hynix RAM HMT351R7CFR8A-H9 4096MB DIMM DDR3 1333MT/s             | 1         | 0.73%   |
| SK hynix RAM HMT31GR7EFR4A 8192MB DIMM DDR3 1600MT/s                | 1         | 0.73%   |
| SK hynix RAM HMT31GR7BFR4A-H9 16GB DIMM 1333MT/s                    | 1         | 0.73%   |
| SK hynix RAM HMT125R7BFR8C-H9 4GB DIMM 1333MT/s                     | 1         | 0.73%   |
| SK hynix RAM HMA851S6JJR6N-VK 4096MB SODIMM DDR4 2667MT/s           | 1         | 0.73%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s              | 1         | 0.73%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 0.73%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 0.73%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 1         | 0.73%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s              | 1         | 0.73%   |
| SK hynix RAM HMA81GR7CJR8N-XN 8192MB DIMM DDR4 3200MT/s             | 1         | 0.73%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s              | 1         | 0.73%   |
| SK hynix RAM H9CCNNNCLGALAR-NUD 8192MB Row Of Chips LPDDR3 1867MT/s | 1         | 0.73%   |
| SK hynix RAM 746448-381 4096MB SODIMM LPDDR3 1600MT/s               | 1         | 0.73%   |
| Silicon Power RAM DCLT4GN568S V 4096MB DIMM DDR3 1600MT/s           | 1         | 0.73%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s               | 1         | 0.73%   |
| Samsung RAM M471B5273DH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 1         | 0.73%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s            | 1         | 0.73%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.73%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.73%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s            | 1         | 0.73%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.73%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 0.73%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 1         | 0.73%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 1         | 0.73%   |
| Samsung RAM M471A5244BB0-CPB 4096MB SODIMM DDR4 2400MT/s            | 1         | 0.73%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s              | 1         | 0.73%   |
| Samsung RAM M395T5663QZ4-CE66 2048MB FB-DIMM DDR2 667MT/s           | 1         | 0.73%   |
| Samsung RAM M393B5273DH0-CK0 4GB DIMM DDR3 1600MT/s                 | 1         | 0.73%   |
| Samsung RAM M393A2G40DB0-CPB 16GB RIMM DDR4 2133MT/s                | 1         | 0.73%   |
| Samsung RAM M393A1K43BB0-CRC 8GB DIMM DDR4 2400MT/s                 | 1         | 0.73%   |
| Samsung RAM M393A1G43EB1-CRC 8GB DIMM DDR4 2400MT/s                 | 1         | 0.73%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 48        | 44.04%  |
| DDR3    | 44        | 40.37%  |
| DDR2    | 5         | 4.59%   |
| SDRAM   | 4         | 3.67%   |
| LPDDR3  | 3         | 2.75%   |
| LPDDR4  | 2         | 1.83%   |
| Unknown | 2         | 1.83%   |
| DDR     | 1         | 0.92%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 53        | 49.07%  |
| DIMM         | 51        | 47.22%  |
| Row Of Chips | 2         | 1.85%   |
| RIMM         | 1         | 0.93%   |
| FB-DIMM      | 1         | 0.93%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 42        | 35.29%  |
| 4096  | 42        | 35.29%  |
| 16384 | 15        | 12.61%  |
| 2048  | 10        | 8.4%    |
| 32768 | 5         | 4.2%    |
| 1024  | 5         | 4.2%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 31        | 26.72%  |
| 3200    | 15        | 12.93%  |
| 2667    | 15        | 12.93%  |
| 2400    | 11        | 9.48%   |
| 1333    | 8         | 6.9%    |
| 3600    | 6         | 5.17%   |
| 2133    | 5         | 4.31%   |
| 667     | 5         | 4.31%   |
| 1867    | 3         | 2.59%   |
| Unknown | 3         | 2.59%   |
| 2666    | 2         | 1.72%   |
| 1866    | 2         | 1.72%   |
| 975     | 2         | 1.72%   |
| 65535   | 1         | 0.86%   |
| 4199    | 1         | 0.86%   |
| 3800    | 1         | 0.86%   |
| 2000    | 1         | 0.86%   |
| 1334    | 1         | 0.86%   |
| 1066    | 1         | 0.86%   |
| 800     | 1         | 0.86%   |
| 701     | 1         | 0.86%   |

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
| Canon CanoScan LiDE 300      | 1         | 12.5%   |
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
| Chicony Electronics                    | 16        | 25.4%   |
| Logitech                               | 10        | 15.87%  |
| Acer                                   | 8         | 12.7%   |
| Realtek Semiconductor                  | 4         | 6.35%   |
| Microdia                               | 4         | 6.35%   |
| IMC Networks                           | 4         | 6.35%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 6.35%   |
| Lite-On Technology                     | 3         | 4.76%   |
| Sunplus Innovation Technology          | 2         | 3.17%   |
| Quanta                                 | 2         | 3.17%   |
| Syntek                                 | 1         | 1.59%   |
| Silicon Motion                         | 1         | 1.59%   |
| Samsung Electronics                    | 1         | 1.59%   |
| Motorola PCS                           | 1         | 1.59%   |
| Luxvisions Innotech Limited            | 1         | 1.59%   |
| Apple                                  | 1         | 1.59%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 3         | 4.76%   |
| Acer HD Webcam                                                             | 3         | 4.76%   |
| Acer BisonCam,NB Pro                                                       | 3         | 4.76%   |
| Realtek USB Camera                                                         | 2         | 3.17%   |
| Quanta HP Webcam                                                           | 2         | 3.17%   |
| Logitech Webcam C270                                                       | 2         | 3.17%   |
| Chicony FJ Camera                                                          | 2         | 3.17%   |
| Syntek USB2.0 Camera                                                       | 1         | 1.59%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                       | 1         | 1.59%   |
| Sunplus Integrated_Webcam_HD                                               | 1         | 1.59%   |
| Silicon Motion Web Camera                                                  | 1         | 1.59%   |
| Samsung Galaxy series, misc. (MTP mode)                                    | 1         | 1.59%   |
| Realtek Laptop Camera                                                      | 1         | 1.59%   |
| Realtek EasyCamera                                                         | 1         | 1.59%   |
| Motorola PCS XT1033 [Moto G], PTP mode                                     | 1         | 1.59%   |
| Microdia Laptop_Integrated_Webcam_2M                                       | 1         | 1.59%   |
| Microdia Integrated_Webcam_HD                                              | 1         | 1.59%   |
| Microdia Integrated Webcam                                                 | 1         | 1.59%   |
| Microdia Dell Integrated HD Webcam                                         | 1         | 1.59%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 1         | 1.59%   |
| Logitech Webcam C310                                                       | 1         | 1.59%   |
| Logitech Webcam C300                                                       | 1         | 1.59%   |
| Logitech Webcam C170                                                       | 1         | 1.59%   |
| Logitech QuickCam Pro 9000                                                 | 1         | 1.59%   |
| Logitech HD Webcam C525                                                    | 1         | 1.59%   |
| Logitech HD Pro Webcam C920                                                | 1         | 1.59%   |
| Logitech C922 Pro Stream Webcam                                            | 1         | 1.59%   |
| Logitech C920 PRO HD Webcam                                                | 1         | 1.59%   |
| Lite-On TOSHIBA Web Camera - FHD                                           | 1         | 1.59%   |
| Lite-On Integrated Camera                                                  | 1         | 1.59%   |
| Lite-On HP TrueVision HD Camera                                            | 1         | 1.59%   |
| IMC Networks UVC VGA Webcam                                                | 1         | 1.59%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 1         | 1.59%   |
| IMC Networks Lenovo EasyCamera                                             | 1         | 1.59%   |
| IMC Networks Integrated Camera                                             | 1         | 1.59%   |
| Chicony Web Camera - FHD                                                   | 1         | 1.59%   |
| Chicony TOSHIBA Web Camera - HD                                            | 1         | 1.59%   |
| Chicony TOSHIBA Web Camera - FHD                                           | 1         | 1.59%   |
| Chicony Integrated Camera [ThinkPad]                                       | 1         | 1.59%   |
| Chicony Integrated Camera (1280x720@30)                                    | 1         | 1.59%   |
| Chicony HP TrueVision HD Camera                                            | 1         | 1.59%   |
| Chicony HP HD Webcam [Fixed]                                               | 1         | 1.59%   |
| Chicony HP HD Camera                                                       | 1         | 1.59%   |
| Chicony HD WebCam (Acer)                                                   | 1         | 1.59%   |
| Chicony HD WebCam                                                          | 1         | 1.59%   |
| Chicony 2.0M UVC Webcam / CNF7129                                          | 1         | 1.59%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD integrated webcam | 1         | 1.59%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera             | 1         | 1.59%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam                        | 1         | 1.59%   |
| Cheng Uei Precision Industry (Foxlink) HP 5M Camera                        | 1         | 1.59%   |
| Apple Built-in iSight                                                      | 1         | 1.59%   |
| Acer ThinkPad Integrated Camera                                            | 1         | 1.59%   |
| Acer Integrated Camera                                                     | 1         | 1.59%   |

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
| 0     | 74        | 62.18%  |
| 1     | 24        | 20.17%  |
| 2     | 11        | 9.24%   |
| 3     | 6         | 5.04%   |
| 4     | 4         | 3.36%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 13        | 17.57%  |
| Fingerprint reader       | 11        | 14.86%  |
| Sound                    | 10        | 13.51%  |
| Communication controller | 8         | 10.81%  |
| Net/wireless             | 7         | 9.46%   |
| Chipcard                 | 7         | 9.46%   |
| Card reader              | 4         | 5.41%   |
| Unassigned class         | 3         | 4.05%   |
| Bluetooth                | 3         | 4.05%   |
| Net/ethernet             | 2         | 2.7%    |
| Multimedia controller    | 2         | 2.7%    |
| Storage/ata              | 1         | 1.35%   |
| Storage                  | 1         | 1.35%   |
| Firewire controller      | 1         | 1.35%   |
| Camera                   | 1         | 1.35%   |

