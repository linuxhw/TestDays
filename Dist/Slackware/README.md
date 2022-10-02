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

Total: 148

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | 3031h                       | Desktop     | [b6849a29a2](https://linux-hardware.org/?probe=b6849a29a2) | Sep 24, 2022 |
| Lenovo        | ThinkPad T61 765912G        | Notebook    | [bd04e564a0](https://linux-hardware.org/?probe=bd04e564a0) | Sep 24, 2022 |
| HP            | 3031h                       | Desktop     | [40160588bb](https://linux-hardware.org/?probe=40160588bb) | Sep 20, 2022 |
| MSI           | H110M PRO-VD                | Desktop     | [2299dc1786](https://linux-hardware.org/?probe=2299dc1786) | Sep 17, 2022 |
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
| Slackware 14.2  | 62        | 50.82%  |
| Slackware 15.0  | 54        | 44.26%  |
| Slackware 14.2+ | 6         | 4.92%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| Slackware | 120       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.15.19           | 12        | 9.45%   |
| 4.19.80           | 8         | 6.3%    |
| 5.10.28-Unraid    | 6         | 4.72%   |
| 5.15.27           | 4         | 3.15%   |
| 4.4.190           | 4         | 3.15%   |
| 4.4.240           | 3         | 2.36%   |
| 5.3.7             | 2         | 1.57%   |
| 5.17.2            | 2         | 1.57%   |
| 5.17.1            | 2         | 1.57%   |
| 5.16.13           | 2         | 1.57%   |
| 5.15.63           | 2         | 1.57%   |
| 5.15.38           | 2         | 1.57%   |
| 5.15.30-Unraid    | 2         | 1.57%   |
| 5.13.8            | 2         | 1.57%   |
| 5.10.3            | 2         | 1.57%   |
| 5.7.0             | 1         | 0.79%   |
| 5.5.10            | 1         | 0.79%   |
| 5.4.77            | 1         | 0.79%   |
| 5.4.75            | 1         | 0.79%   |
| 5.4.62            | 1         | 0.79%   |
| 5.4.53-APRL       | 1         | 0.79%   |
| 5.4.50            | 1         | 0.79%   |
| 5.4.47            | 1         | 0.79%   |
| 5.4.43            | 1         | 0.79%   |
| 5.4.24toshiba-new | 1         | 0.79%   |
| 5.4.2             | 1         | 0.79%   |
| 5.4.139-jw        | 1         | 0.79%   |
| 5.4.13            | 1         | 0.79%   |
| 5.4.12+           | 1         | 0.79%   |
| 5.4.0-rc2-vto     | 1         | 0.79%   |
| 5.2.2             | 1         | 0.79%   |
| 5.17.5            | 1         | 0.79%   |
| 5.17.0-custom     | 1         | 0.79%   |
| 5.16.9-joe1       | 1         | 0.79%   |
| 5.16.18           | 1         | 0.79%   |
| 5.16.12           | 1         | 0.79%   |
| 5.16.11           | 1         | 0.79%   |
| 5.15.6            | 1         | 0.79%   |
| 5.15.50-cwl       | 1         | 0.79%   |
| 5.15.37.a         | 1         | 0.79%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.19 | 12        | 9.45%   |
| 4.19.80 | 8         | 6.3%    |
| 5.10.28 | 6         | 4.72%   |
| 4.4.190 | 5         | 3.94%   |
| 5.15.27 | 4         | 3.15%   |
| 4.4.240 | 3         | 2.36%   |
| 5.3.7   | 2         | 1.57%   |
| 5.17.2  | 2         | 1.57%   |
| 5.17.1  | 2         | 1.57%   |
| 5.16.13 | 2         | 1.57%   |
| 5.15.63 | 2         | 1.57%   |
| 5.15.38 | 2         | 1.57%   |
| 5.15.30 | 2         | 1.57%   |
| 5.14.15 | 2         | 1.57%   |
| 5.13.8  | 2         | 1.57%   |
| 5.10.3  | 2         | 1.57%   |
| 5.7.0   | 1         | 0.79%   |
| 5.5.10  | 1         | 0.79%   |
| 5.4.77  | 1         | 0.79%   |
| 5.4.75  | 1         | 0.79%   |
| 5.4.62  | 1         | 0.79%   |
| 5.4.53  | 1         | 0.79%   |
| 5.4.50  | 1         | 0.79%   |
| 5.4.47  | 1         | 0.79%   |
| 5.4.43  | 1         | 0.79%   |
| 5.4.24  | 1         | 0.79%   |
| 5.4.2   | 1         | 0.79%   |
| 5.4.139 | 1         | 0.79%   |
| 5.4.13  | 1         | 0.79%   |
| 5.4.12  | 1         | 0.79%   |
| 5.4.0   | 1         | 0.79%   |
| 5.2.2   | 1         | 0.79%   |
| 5.17.5  | 1         | 0.79%   |
| 5.17.0  | 1         | 0.79%   |
| 5.16.9  | 1         | 0.79%   |
| 5.16.18 | 1         | 0.79%   |
| 5.16.12 | 1         | 0.79%   |
| 5.16.11 | 1         | 0.79%   |
| 5.15.6  | 1         | 0.79%   |
| 5.15.50 | 1         | 0.79%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 31        | 24.6%   |
| 4.4     | 16        | 12.7%   |
| 5.10    | 15        | 11.9%   |
| 4.19    | 15        | 11.9%   |
| 5.4     | 13        | 10.32%  |
| 5.14    | 7         | 5.56%   |
| 5.13    | 7         | 5.56%   |
| 5.17    | 6         | 4.76%   |
| 5.16    | 6         | 4.76%   |
| 5.3     | 2         | 1.59%   |
| 4.9     | 2         | 1.59%   |
| 5.7     | 1         | 0.79%   |
| 5.5     | 1         | 0.79%   |
| 5.2     | 1         | 0.79%   |
| 5.12    | 1         | 0.79%   |
| 4.20    | 1         | 0.79%   |
| 4.16    | 1         | 0.79%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 117       | 97.5%   |
| aarch64 | 2         | 1.67%   |
| i686    | 1         | 0.83%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Unknown       | 42        | 34.43%  |
| XFCE          | 36        | 29.51%  |
| KDE5          | 30        | 24.59%  |
| KDE           | 5         | 4.1%    |
| MATE          | 2         | 1.64%   |
| GNOME         | 2         | 1.64%   |
| FVWM          | 2         | 1.64%   |
| xwmconfig     | 1         | 0.82%   |
| LXQt          | 1         | 0.82%   |
| Enlightenment | 1         | 0.82%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 81        | 66.39%  |
| Tty     | 27        | 22.13%  |
| Unknown | 10        | 8.2%    |
| Wayland | 4         | 3.28%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 50        | 40.98%  |
| SDDM    | 41        | 33.61%  |
| XDM     | 27        | 22.13%  |
| SLiM    | 2         | 1.64%   |
| LightDM | 2         | 1.64%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 62        | 51.67%  |
| Unknown     | 38        | 31.67%  |
| it_IT       | 3         | 2.5%    |
| fr_FR       | 3         | 2.5%    |
| ru_RU       | 2         | 1.67%   |
| pt_BR       | 2         | 1.67%   |
| en_GB       | 2         | 1.67%   |
| de_DE       | 2         | 1.67%   |
| sr_RS@latin | 1         | 0.83%   |
| pl_PL       | 1         | 0.83%   |
| es_ES.UTF8  | 1         | 0.83%   |
| en_US.ASCII | 1         | 0.83%   |
| en_AU       | 1         | 0.83%   |
| C           | 1         | 0.83%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 65        | 53.72%  |
| EFI  | 56        | 46.28%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 87        | 72.5%   |
| Btrfs    | 14        | 11.67%  |
| Overlay  | 6         | 5%      |
| Xfs      | 5         | 4.17%   |
| Rootfs   | 3         | 2.5%    |
| Zfs      | 1         | 0.83%   |
| Reiserfs | 1         | 0.83%   |
| Jfs      | 1         | 0.83%   |
| F2fs     | 1         | 0.83%   |
| Ext3     | 1         | 0.83%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 84        | 68.29%  |
| MBR     | 31        | 25.2%   |
| Unknown | 8         | 6.5%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 81        | 66.39%  |
| Yes       | 41        | 33.61%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 78        | 65%     |
| Yes       | 42        | 35%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 20        | 16.67%  |
| Hewlett-Packard     | 19        | 15.83%  |
| Lenovo              | 14        | 11.67%  |
| MSI                 | 12        | 10%     |
| Dell                | 12        | 10%     |
| ASRock              | 7         | 5.83%   |
| Gigabyte Technology | 5         | 4.17%   |
| Toshiba             | 3         | 2.5%    |
| Acer                | 3         | 2.5%    |
| Notebook            | 2         | 1.67%   |
| Fujitsu             | 2         | 1.67%   |
| Dynabook            | 2         | 1.67%   |
| Apple               | 2         | 1.67%   |
| Unknown             | 2         | 1.67%   |
| TYAN Computer       | 1         | 0.83%   |
| System76            | 1         | 0.83%   |
| Supermicro          | 1         | 0.83%   |
| Sony                | 1         | 0.83%   |
| Shuttle             | 1         | 0.83%   |
| Samsung Electronics | 1         | 0.83%   |
| Radxa               | 1         | 0.83%   |
| NetGear             | 1         | 0.83%   |
| Intel               | 1         | 0.83%   |
| Huanan              | 1         | 0.83%   |
| HPE                 | 1         | 0.83%   |
| Framework           | 1         | 0.83%   |
| Foxconn             | 1         | 0.83%   |
| Biostar             | 1         | 0.83%   |
| AMI                 | 1         | 0.83%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| ASUS All Series                          | 4         | 3.33%   |
| Unknown                                  | 2         | 1.67%   |
| TYAN S7012                               | 1         | 0.83%   |
| Toshiba Satellite P50-A-12Z              | 1         | 0.83%   |
| Toshiba Satellite C660                   | 1         | 0.83%   |
| Toshiba PORTEGE Z30-A                    | 1         | 0.83%   |
| System76 Oryx Pro                        | 1         | 0.83%   |
| Supermicro X9DA7/E                       | 1         | 0.83%   |
| Sony SVE1713A1EW                         | 1         | 0.83%   |
| Shuttle NC03U                            | 1         | 0.83%   |
| Samsung 300E5M/300E5L                    | 1         | 0.83%   |
| Radxa ROCK Pi 4                          | 1         | 0.83%   |
| Notebook X170KM-G                        | 1         | 0.83%   |
| Notebook NL40_50CU                       | 1         | 0.83%   |
| NetGear ReadyDATA 5200                   | 1         | 0.83%   |
| MSI MS-7C52                              | 1         | 0.83%   |
| MSI MS-7C02                              | 1         | 0.83%   |
| MSI MS-7996                              | 1         | 0.83%   |
| MSI MS-7788                              | 1         | 0.83%   |
| MSI MS-7693                              | 1         | 0.83%   |
| MSI MS-7529                              | 1         | 0.83%   |
| MSI MS-7365                              | 1         | 0.83%   |
| MSI Modern 14 B11MO                      | 1         | 0.83%   |
| MSI Modern 14 B10MW                      | 1         | 0.83%   |
| MSI GP76 Leopard 11UG                    | 1         | 0.83%   |
| MSI GL73 8RC                             | 1         | 0.83%   |
| MSI GE76 Raider 11UE                     | 1         | 0.83%   |
| Lenovo V330-14ARR 81B1                   | 1         | 0.83%   |
| Lenovo ThinkPad X230 2325P38             | 1         | 0.83%   |
| Lenovo ThinkPad X1 Carbon 7th 20R10015US | 1         | 0.83%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS04300 | 1         | 0.83%   |
| Lenovo ThinkPad T61 765912G              | 1         | 0.83%   |
| Lenovo ThinkPad T470 20HDCTO1WW          | 1         | 0.83%   |
| Lenovo ThinkPad T450s 20BW000EUS         | 1         | 0.83%   |
| Lenovo ThinkPad T400 6474BV7             | 1         | 0.83%   |
| Lenovo ThinkPad P70 20ERCTO1WW           | 1         | 0.83%   |
| Lenovo ThinkPad L440 20ASS05K00          | 1         | 0.83%   |
| Lenovo ThinkPad Edge E530c 336669G       | 1         | 0.83%   |
| Lenovo IdeaPad P500 20210                | 1         | 0.83%   |
| Lenovo IdeaPad 310-15ISK 80SM            | 1         | 0.83%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 10        | 8.33%   |
| Dell Precision    | 4         | 3.33%   |
| ASUS PRIME        | 4         | 3.33%   |
| ASUS All          | 4         | 3.33%   |
| HP Pavilion       | 3         | 2.5%    |
| HP Laptop         | 3         | 2.5%    |
| Dell Latitude     | 3         | 2.5%    |
| ASUS ROG          | 3         | 2.5%    |
| Toshiba Satellite | 2         | 1.67%   |
| MSI Modern        | 2         | 1.67%   |
| Lenovo IdeaPad    | 2         | 1.67%   |
| HP EliteBook      | 2         | 1.67%   |
| Fujitsu LIFEBOOK  | 2         | 1.67%   |
| Dell PowerEdge    | 2         | 1.67%   |
| Acer Aspire       | 2         | 1.67%   |
| Unknown           | 2         | 1.67%   |
| TYAN S7012        | 1         | 0.83%   |
| Toshiba PORTEGE   | 1         | 0.83%   |
| System76 Oryx     | 1         | 0.83%   |
| Supermicro X9DA7  | 1         | 0.83%   |
| Sony SVE1713A1EW  | 1         | 0.83%   |
| Shuttle NC03U     | 1         | 0.83%   |
| Samsung 300E5M    | 1         | 0.83%   |
| Radxa ROCK        | 1         | 0.83%   |
| Notebook X170KM-G | 1         | 0.83%   |
| Notebook NL40     | 1         | 0.83%   |
| NetGear ReadyDATA | 1         | 0.83%   |
| MSI MS-7C52       | 1         | 0.83%   |
| MSI MS-7C02       | 1         | 0.83%   |
| MSI MS-7996       | 1         | 0.83%   |
| MSI MS-7788       | 1         | 0.83%   |
| MSI MS-7693       | 1         | 0.83%   |
| MSI MS-7529       | 1         | 0.83%   |
| MSI MS-7365       | 1         | 0.83%   |
| MSI GP76          | 1         | 0.83%   |
| MSI GL73          | 1         | 0.83%   |
| MSI GE76          | 1         | 0.83%   |
| Lenovo V330-14ARR | 1         | 0.83%   |
| Lenovo H50-05     | 1         | 0.83%   |
| Intel DZ77RE-75K  | 1         | 0.83%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 15        | 12.5%   |
| 2012    | 12        | 10%     |
| 2020    | 11        | 9.17%   |
| 2018    | 10        | 8.33%   |
| 2017    | 10        | 8.33%   |
| 2015    | 10        | 8.33%   |
| 2021    | 8         | 6.67%   |
| 2014    | 8         | 6.67%   |
| 2016    | 7         | 5.83%   |
| 2011    | 7         | 5.83%   |
| 2008    | 6         | 5%      |
| 2013    | 4         | 3.33%   |
| 2007    | 4         | 3.33%   |
| 2009    | 3         | 2.5%    |
| 2010    | 2         | 1.67%   |
| Unknown | 2         | 1.67%   |
| 2022    | 1         | 0.83%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 55        | 45.83%  |
| Notebook       | 55        | 45.83%  |
| Mini pc        | 3         | 2.5%    |
| Server         | 3         | 2.5%    |
| System on chip | 2         | 1.67%   |
| All in one     | 2         | 1.67%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 120       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 117       | 97.5%   |
| Yes  | 3         | 2.5%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 25        | 20.83%  |
| 4.01-8.0    | 24        | 20%     |
| 3.01-4.0    | 21        | 17.5%   |
| 8.01-16.0   | 21        | 17.5%   |
| 32.01-64.0  | 11        | 9.17%   |
| 64.01-256.0 | 9         | 7.5%    |
| 24.01-32.0  | 5         | 4.17%   |
| 1.01-2.0    | 3         | 2.5%    |
| 0.51-1.0    | 1         | 0.83%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 38        | 30.4%   |
| 2.01-3.0    | 28        | 22.4%   |
| 4.01-8.0    | 21        | 16.8%   |
| 3.01-4.0    | 13        | 10.4%   |
| 0.51-1.0    | 9         | 7.2%    |
| 0.01-0.5    | 5         | 4%      |
| 8.01-16.0   | 4         | 3.2%    |
| 16.01-24.0  | 3         | 2.4%    |
| 24.01-32.0  | 2         | 1.6%    |
| 32.01-64.0  | 1         | 0.8%    |
| 64.01-256.0 | 1         | 0.8%    |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 58        | 47.54%  |
| 2      | 24        | 19.67%  |
| 3      | 15        | 12.3%   |
| 4      | 10        | 8.2%    |
| 5      | 5         | 4.1%    |
| 6      | 4         | 3.28%   |
| 0      | 2         | 1.64%   |
| 13     | 1         | 0.82%   |
| 9      | 1         | 0.82%   |
| 8      | 1         | 0.82%   |
| 7      | 1         | 0.82%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 68        | 56.67%  |
| Yes       | 52        | 43.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 111       | 92.5%   |
| No        | 9         | 7.5%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 80        | 66.67%  |
| No        | 40        | 33.33%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 74        | 61.67%  |
| No        | 46        | 38.33%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 27        | 22.5%   |
| UK           | 11        | 9.17%   |
| Germany      | 7         | 5.83%   |
| Brazil       | 7         | 5.83%   |
| Kazakhstan   | 6         | 5%      |
| Italy        | 6         | 5%      |
| Canada       | 6         | 5%      |
| Portugal     | 5         | 4.17%   |
| Japan        | 5         | 4.17%   |
| France       | 5         | 4.17%   |
| Sweden       | 4         | 3.33%   |
| Russia       | 4         | 3.33%   |
| India        | 4         | 3.33%   |
| Spain        | 3         | 2.5%    |
| South Africa | 3         | 2.5%    |
| Hong Kong    | 3         | 2.5%    |
| Serbia       | 2         | 1.67%   |
| Poland       | 2         | 1.67%   |
| Greece       | 2         | 1.67%   |
| Switzerland  | 1         | 0.83%   |
| Philippines  | 1         | 0.83%   |
| Netherlands  | 1         | 0.83%   |
| Mexico       | 1         | 0.83%   |
| Finland      | 1         | 0.83%   |
| Chile        | 1         | 0.83%   |
| Bulgaria     | 1         | 0.83%   |
| Australia    | 1         | 0.83%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Ust-Kamenogorsk        | 4         | 3.25%   |
| Lisbon                 | 4         | 3.25%   |
| Yekaterinburg          | 3         | 2.44%   |
| Paris                  | 3         | 2.44%   |
| Warsaw                 | 2         | 1.63%   |
| Tsukuba                | 2         | 1.63%   |
| Tendo                  | 2         | 1.63%   |
| New Delhi              | 2         | 1.63%   |
| Milan                  | 2         | 1.63%   |
| Karaganda              | 2         | 1.63%   |
| Chania                 | 2         | 1.63%   |
| Carrollton             | 2         | 1.63%   |
| Cape Town              | 2         | 1.63%   |
| Belgrade               | 2         | 1.63%   |
| Barry                  | 2         | 1.63%   |
| Barrie                 | 2         | 1.63%   |
| Wokingham              | 1         | 0.81%   |
| Winter Springs         | 1         | 0.81%   |
| Winnipeg               | 1         | 0.81%   |
| Weilheim               | 1         | 0.81%   |
| Visconde do Rio Branco | 1         | 0.81%   |
| Toronto                | 1         | 0.81%   |
| Tiffin                 | 1         | 0.81%   |
| Stockholm              | 1         | 0.81%   |
| St Petersburg          | 1         | 0.81%   |
| St Louis               | 1         | 0.81%   |
| Springfield            | 1         | 0.81%   |
| Southend-on-Sea        | 1         | 0.81%   |
| Skövde                | 1         | 0.81%   |
| Shrewsbury             | 1         | 0.81%   |
| Sham Shui Po           | 1         | 0.81%   |
| Santa Cruz do Sul      | 1         | 0.81%   |
| San Antonio            | 1         | 0.81%   |
| Saint Paul             | 1         | 0.81%   |
| Round Rock             | 1         | 0.81%   |
| Rome                   | 1         | 0.81%   |
| Roknaes                | 1         | 0.81%   |
| Rock                   | 1         | 0.81%   |
| Reno                   | 1         | 0.81%   |
| Renazzo                | 1         | 0.81%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 36        | 66     | 19.05%  |
| Samsung Electronics | 33        | 50     | 17.46%  |
| Seagate             | 30        | 59     | 15.87%  |
| Toshiba             | 14        | 23     | 7.41%   |
| Kingston            | 9         | 11     | 4.76%   |
| Hitachi             | 8         | 11     | 4.23%   |
| Crucial             | 7         | 8      | 3.7%    |
| HGST                | 5         | 5      | 2.65%   |
| Unknown             | 4         | 4      | 2.12%   |
| SanDisk             | 4         | 4      | 2.12%   |
| Intel               | 4         | 4      | 2.12%   |
| A-DATA Technology   | 4         | 4      | 2.12%   |
| SK hynix            | 3         | 3      | 1.59%   |
| Hewlett-Packard     | 3         | 4      | 1.59%   |
| Gigabyte Technology | 3         | 3      | 1.59%   |
| Patriot             | 2         | 3      | 1.06%   |
| Micron Technology   | 2         | 2      | 1.06%   |
| China               | 2         | 3      | 1.06%   |
| Apple               | 2         | 3      | 1.06%   |
| ZHITAI              | 1         | 2      | 0.53%   |
| TO Exter            | 1         | 1      | 0.53%   |
| Team                | 1         | 1      | 0.53%   |
| Plextor             | 1         | 1      | 0.53%   |
| Netac               | 1         | 1      | 0.53%   |
| Maxtor              | 1         | 1      | 0.53%   |
| KIOXIA              | 1         | 1      | 0.53%   |
| JMicron Technology  | 1         | 1      | 0.53%   |
| Intenso             | 1         | 1      | 0.53%   |
| GOODRAM             | 1         | 1      | 0.53%   |
| Fujitsu             | 1         | 1      | 0.53%   |
| External            | 1         | 1      | 0.53%   |
| DUEX                | 1         | 1      | 0.53%   |
| Dogfish             | 1         | 1      | 0.53%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| WDC WD20EFRX-68EUZN0 2TB         | 3         | 1.29%   |
| WDC WD1003FZEX-00MK2A0 1TB       | 3         | 1.29%   |
| Samsung SSD 970 EVO 250GB        | 3         | 1.29%   |
| WDC WD10SPZX-60Z10T0 1TB         | 2         | 0.86%   |
| Toshiba MQ04ABF100 1TB           | 2         | 0.86%   |
| Toshiba MQ01ABD100 1TB           | 2         | 0.86%   |
| Seagate ST500DM002-1BD142 500GB  | 2         | 0.86%   |
| Seagate ST4000VN008-2DR166 4TB   | 2         | 0.86%   |
| Seagate ST31000524AS 1TB         | 2         | 0.86%   |
| Seagate ST2000DM008-2FR102 2TB   | 2         | 0.86%   |
| Seagate ST2000DM001-1CH164 2TB   | 2         | 0.86%   |
| Seagate ST1000DM010-2EP102 1TB   | 2         | 0.86%   |
| Seagate ST1000DM003-1SB102 1TB   | 2         | 0.86%   |
| Seagate ST1000DM003-1ER162 1TB   | 2         | 0.86%   |
| Samsung SSD 970 EVO Plus 1TB     | 2         | 0.86%   |
| Samsung SSD 860 QVO 2TB          | 2         | 0.86%   |
| Kingston SA400S37240G 240GB SSD  | 2         | 0.86%   |
| Crucial CT500MX500SSD1 500GB     | 2         | 0.86%   |
| ZHITAI SC001 Active 1TB SSD      | 1         | 0.43%   |
| ZHITAI PC005 Active 512GB        | 1         | 0.43%   |
| WDC WDS500G2B0B-00YS70 500GB SSD | 1         | 0.43%   |
| WDC WDS480G2G0A-00JH30 480GB SSD | 1         | 0.43%   |
| WDC WDS100T2B0C-00PXH0 1TB       | 1         | 0.43%   |
| WDC WDS100T2B0A-00SM50 1TB SSD   | 1         | 0.43%   |
| WDC WD7500BPVT-24HXZT3 752GB     | 1         | 0.43%   |
| WDC WD5003ABYX-18WERA0 500GB     | 1         | 0.43%   |
| WDC WD5000LPCX-60VHAT1 500GB     | 1         | 0.43%   |
| WDC WD5000BPVT-2 500GB           | 1         | 0.43%   |
| WDC WD5000BPKX-60HPJT0 500GB     | 1         | 0.43%   |
| WDC WD5000AAKX-22ERMA0 500GB     | 1         | 0.43%   |
| WDC WD5000AAKX-00ERMA0 500GB     | 1         | 0.43%   |
| WDC WD5000AAKS-00V0A0 500GB      | 1         | 0.43%   |
| WDC WD5000AAKS-00A7B2 500GB      | 1         | 0.43%   |
| WDC WD40EJRX-89T1XY0 4TB         | 1         | 0.43%   |
| WDC WD40EFRX-68WT0N0 4TB         | 1         | 0.43%   |
| WDC WD40EFRX-68N32N0 4TB         | 1         | 0.43%   |
| WDC WD400BD-60LTA0 40GB          | 1         | 0.43%   |
| WDC WD3200AAJS-65B4A0 320GB      | 1         | 0.43%   |
| WDC WD30EZRX-00SPEB0 3TB         | 1         | 0.43%   |
| WDC WD30EZRX-00M                 | 1         | 0.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 33        | 60     | 34.74%  |
| Seagate             | 30        | 55     | 31.58%  |
| Toshiba             | 13        | 21     | 13.68%  |
| Hitachi             | 8         | 11     | 8.42%   |
| HGST                | 5         | 5      | 5.26%   |
| Samsung Electronics | 3         | 3      | 3.16%   |
| Maxtor              | 1         | 1      | 1.05%   |
| Hewlett-Packard     | 1         | 1      | 1.05%   |
| Fujitsu             | 1         | 1      | 1.05%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 17        | 25     | 29.31%  |
| Kingston            | 8         | 10     | 13.79%  |
| Crucial             | 6         | 7      | 10.34%  |
| SanDisk             | 4         | 4      | 6.9%    |
| WDC                 | 2         | 3      | 3.45%   |
| Patriot             | 2         | 3      | 3.45%   |
| China               | 2         | 3      | 3.45%   |
| Apple               | 2         | 3      | 3.45%   |
| A-DATA Technology   | 2         | 2      | 3.45%   |
| ZHITAI              | 1         | 1      | 1.72%   |
| TO Exter            | 1         | 1      | 1.72%   |
| Team                | 1         | 1      | 1.72%   |
| Plextor             | 1         | 1      | 1.72%   |
| Netac               | 1         | 1      | 1.72%   |
| Micron Technology   | 1         | 1      | 1.72%   |
| Intenso             | 1         | 1      | 1.72%   |
| Intel               | 1         | 1      | 1.72%   |
| Hewlett-Packard     | 1         | 1      | 1.72%   |
| GOODRAM             | 1         | 1      | 1.72%   |
| Gigabyte Technology | 1         | 1      | 1.72%   |
| DUEX                | 1         | 1      | 1.72%   |
| Dogfish             | 1         | 1      | 1.72%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 69        | 158    | 41.57%  |
| SSD     | 54        | 73     | 32.53%  |
| NVMe    | 38        | 46     | 22.89%  |
| MMC     | 4         | 4      | 2.41%   |
| Unknown | 1         | 4      | 0.6%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 95        | 225    | 67.86%  |
| NVMe | 36        | 44     | 25.71%  |
| SAS  | 5         | 12     | 3.57%   |
| MMC  | 4         | 4      | 2.86%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 69        | 100    | 48.59%  |
| 0.51-1.0   | 39        | 67     | 27.46%  |
| 1.01-2.0   | 14        | 21     | 9.86%   |
| 3.01-4.0   | 8         | 20     | 5.63%   |
| 2.01-3.0   | 7         | 15     | 4.93%   |
| 4.01-10.0  | 3         | 3      | 2.11%   |
| 10.01-20.0 | 2         | 5      | 1.41%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 501-1000       | 28        | 23.14%  |
| 101-250        | 27        | 22.31%  |
| 251-500        | 19        | 15.7%   |
| Unknown        | 14        | 11.57%  |
| 1001-2000      | 12        | 9.92%   |
| 1-20           | 7         | 5.79%   |
| 2001-3000      | 6         | 4.96%   |
| More than 3000 | 4         | 3.31%   |
| 51-100         | 3         | 2.48%   |
| 21-50          | 1         | 0.83%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 25        | 20.33%  |
| 1-20           | 20        | 16.26%  |
| 21-50          | 17        | 13.82%  |
| 501-1000       | 16        | 13.01%  |
| Unknown        | 14        | 11.38%  |
| 251-500        | 12        | 9.76%   |
| 51-100         | 12        | 9.76%   |
| 1001-2000      | 4         | 3.25%   |
| More than 3000 | 3         | 2.44%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WDS480G2G0A-00JH30 480GB SSD    | 1         | 1      | 2.56%   |
| WDC WD5003ABYX-18WERA0 500GB        | 1         | 2      | 2.56%   |
| WDC WD5000LPCX-60VHAT1 500GB        | 1         | 1      | 2.56%   |
| WDC WD5000BPKX-60HPJT0 500GB        | 1         | 1      | 2.56%   |
| WDC WD5000AAKX-22ERMA0 500GB        | 1         | 1      | 2.56%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 1         | 1      | 2.56%   |
| WDC WD5000AAKS-00A7B2 500GB         | 1         | 1      | 2.56%   |
| WDC WD40EFRX-68WT0N0 4TB            | 1         | 2      | 2.56%   |
| WDC WD3200AAJS-65B4A0 320GB         | 1         | 1      | 2.56%   |
| WDC WD30EZRX-00M                    | 1         | 1      | 2.56%   |
| WDC WD30EFRX-68AX9N0 3TB            | 1         | 4      | 2.56%   |
| WDC WD20EFRX-68EUZN0 2TB            | 1         | 2      | 2.56%   |
| WDC WD10JPLX-00MBPT0 1TB            | 1         | 1      | 2.56%   |
| WDC WD10EZEX-00RKKA0 1TB            | 1         | 1      | 2.56%   |
| WDC WD10EALS-00Z8A0 1TB             | 1         | 2      | 2.56%   |
| WDC WD1003FZEX-00MK2A0 1TB          | 1         | 2      | 2.56%   |
| Toshiba MK2565GSXN 250GB            | 1         | 1      | 2.56%   |
| Seagate ST380011A 80GB              | 1         | 2      | 2.56%   |
| Seagate ST3500630AS 500GB           | 1         | 1      | 2.56%   |
| Seagate ST3500418AS 500GB           | 1         | 1      | 2.56%   |
| Seagate ST3500410AS 500GB           | 1         | 1      | 2.56%   |
| Seagate ST31000524AS 1TB            | 1         | 1      | 2.56%   |
| Seagate ST3000VX006-1HH166 3TB      | 1         | 1      | 2.56%   |
| Seagate ST2000DL003-9VT166 2TB      | 1         | 1      | 2.56%   |
| Seagate ST1000VM002-1SD102 1TB      | 1         | 1      | 2.56%   |
| Seagate ST1000NM0011 1TB            | 1         | 2      | 2.56%   |
| Seagate ST1000DM003-1ER162 1TB      | 1         | 2      | 2.56%   |
| SanDisk SDSA6MM-016G-1006 16GB SSD  | 1         | 1      | 2.56%   |
| Samsung Electronics SSD 870 EVO 1TB | 1         | 1      | 2.56%   |
| Plextor PX-128M6S 128GB SSD         | 1         | 1      | 2.56%   |
| Maxtor 4G120J6 128GB                | 1         | 1      | 2.56%   |
| Intel SSDSA2M080G2GC 80GB           | 1         | 1      | 2.56%   |
| Hitachi HUA723030ALA640 3TB         | 1         | 1      | 2.56%   |
| Hitachi HDS721050CLA660 500GB       | 1         | 1      | 2.56%   |
| Hitachi HDS721016CLA382 160GB       | 1         | 1      | 2.56%   |
| HGST HTS725050A7E630 500GB          | 1         | 1      | 2.56%   |
| HGST HTS545050A7E380 500GB          | 1         | 1      | 2.56%   |
| HGST HDN726040ALE614 4TB            | 1         | 1      | 2.56%   |
| DUEX DX300256A5xnEMLC 256GB SSD     | 1         | 1      | 2.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 14        | 24     | 38.89%  |
| Seagate             | 9         | 13     | 25%     |
| Hitachi             | 3         | 3      | 8.33%   |
| HGST                | 3         | 3      | 8.33%   |
| Toshiba             | 1         | 1      | 2.78%   |
| SanDisk             | 1         | 1      | 2.78%   |
| Samsung Electronics | 1         | 1      | 2.78%   |
| Plextor             | 1         | 1      | 2.78%   |
| Maxtor              | 1         | 1      | 2.78%   |
| Intel               | 1         | 1      | 2.78%   |
| DUEX                | 1         | 1      | 2.78%   |

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
| HDD  | 27        | 44     | 81.82%  |
| SSD  | 6         | 6      | 18.18%  |

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
| Works    | 98        | 205    | 66.22%  |
| Malfunc  | 33        | 50     | 22.3%   |
| Detected | 17        | 30     | 11.49%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 78        | 48.45%  |
| AMD                          | 27        | 16.77%  |
| Samsung Electronics          | 18        | 11.18%  |
| ASMedia Technology           | 5         | 3.11%   |
| Marvell Technology Group     | 4         | 2.48%   |
| SK hynix                     | 3         | 1.86%   |
| SanDisk                      | 3         | 1.86%   |
| Nvidia                       | 3         | 1.86%   |
| Broadcom / LSI               | 3         | 1.86%   |
| Realtek Semiconductor        | 2         | 1.24%   |
| Phison Electronics           | 2         | 1.24%   |
| JMicron Technology           | 2         | 1.24%   |
| Yangtze Memory Technologies  | 1         | 0.62%   |
| Toshiba America Info Systems | 1         | 0.62%   |
| Silicon Image                | 1         | 0.62%   |
| Micron/Crucial Technology    | 1         | 0.62%   |
| Micron Technology            | 1         | 0.62%   |
| LSI Logic / Symbios Logic    | 1         | 0.62%   |
| KIOXIA                       | 1         | 0.62%   |
| Kingston Technology Company  | 1         | 0.62%   |
| Biwin Storage Technology     | 1         | 0.62%   |
| Adaptec                      | 1         | 0.62%   |
| 3ware                        | 1         | 0.62%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 23        | 11.98%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 10        | 5.21%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 7         | 3.65%   |
| AMD 400 Series Chipset SATA Controller                                           | 7         | 3.65%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 6         | 3.13%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 5         | 2.6%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 5         | 2.6%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 4         | 2.08%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 4         | 2.08%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 4         | 2.08%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 1.56%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 3         | 1.56%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 3         | 1.56%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3         | 1.56%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 3         | 1.56%   |
| SK hynix Gold P31 SSD                                                            | 2         | 1.04%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 2         | 1.04%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 1.04%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 1.04%   |
| Realtek Realtek Non-Volatile memory controller                                   | 2         | 1.04%   |
| Nvidia MCP61 SATA Controller                                                     | 2         | 1.04%   |
| Nvidia MCP61 IDE                                                                 | 2         | 1.04%   |
| Intel SSD 600P Series                                                            | 2         | 1.04%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 2         | 1.04%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 2         | 1.04%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 2         | 1.04%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                              | 2         | 1.04%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 2         | 1.04%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 2         | 1.04%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                             | 2         | 1.04%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 1.04%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 1.04%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 1.04%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 2         | 1.04%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 2         | 1.04%   |
| Intel 4 Series Chipset PT IDER Controller                                        | 2         | 1.04%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 2         | 1.04%   |
| Yangtze Memory Non-Volatile memory controller                                    | 1         | 0.52%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                             | 1         | 0.52%   |
| SK hynix BC511                                                                   | 1         | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 92        | 57.5%   |
| NVMe | 36        | 22.5%   |
| IDE  | 16        | 10%     |
| RAID | 10        | 6.25%   |
| SAS  | 4         | 2.5%    |
| SCSI | 2         | 1.25%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 89        | 74.17%  |
| AMD    | 29        | 24.17%  |
| ARM    | 2         | 1.67%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 3         | 2.5%    |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz            | 2         | 1.67%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 2         | 1.67%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1.67%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 1.67%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 1.67%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 2         | 1.67%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 2         | 1.67%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 2         | 1.67%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 1.67%   |
| ARM Processor                                 | 2         | 1.67%   |
| AMD Ryzen 7 3800X 8-Core Processor            | 2         | 1.67%   |
| AMD Ryzen 5 3600 6-Core Processor             | 2         | 1.67%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 2         | 1.67%   |
| AMD FX-8350 Eight-Core Processor              | 2         | 1.67%   |
| Intel Xeon CPU X5680 @ 3.33GHz                | 1         | 0.83%   |
| Intel Xeon CPU X3450 @ 2.67GHz                | 1         | 0.83%   |
| Intel Xeon CPU E5-2697 v3 @ 2.60GHz           | 1         | 0.83%   |
| Intel Xeon CPU E5-2667 v2 @ 3.30GHz           | 1         | 0.83%   |
| Intel Xeon CPU E5-2660 v3 @ 2.60GHz           | 1         | 0.83%   |
| Intel Xeon CPU E5-2620 0 @ 2.00GHz            | 1         | 0.83%   |
| Intel Xeon CPU E5-2407 0 @ 2.20GHz            | 1         | 0.83%   |
| Intel Xeon CPU E5-1650 0 @ 3.20GHz            | 1         | 0.83%   |
| Intel Xeon CPU E3-1246 v3 @ 3.50GHz           | 1         | 0.83%   |
| Intel Xeon CPU 5160 @ 3.00GHz                 | 1         | 0.83%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz        | 1         | 0.83%   |
| Intel Pentium Dual CPU E2140 @ 1.60GHz        | 1         | 0.83%   |
| Intel Pentium CPU P6100 @ 2.00GHz             | 1         | 0.83%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.83%   |
| Intel Pentium CPU G640 @ 2.80GHz              | 1         | 0.83%   |
| Intel Pentium CPU G4560 @ 3.50GHz             | 1         | 0.83%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 1         | 0.83%   |
| Intel Core M-5Y51 CPU @ 1.10GHz               | 1         | 0.83%   |
| Intel Core i7-9700 CPU @ 3.00GHz              | 1         | 0.83%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 0.83%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 1         | 0.83%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 0.83%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 0.83%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 0.83%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 1         | 0.83%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model              | Computers | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 21        | 17.5%   |
| Intel Core i7      | 19        | 15.83%  |
| Intel Xeon         | 12        | 10%     |
| Other              | 9         | 7.5%    |
| AMD Ryzen 5        | 8         | 6.67%   |
| Intel Core i3      | 7         | 5.83%   |
| Intel Core 2 Duo   | 6         | 5%      |
| Intel Pentium      | 5         | 4.17%   |
| AMD Ryzen 9        | 5         | 4.17%   |
| Intel Celeron      | 4         | 3.33%   |
| AMD Ryzen 7        | 4         | 3.33%   |
| AMD FX             | 4         | 3.33%   |
| Intel Core 2 Quad  | 2         | 1.67%   |
| Intel Atom         | 2         | 1.67%   |
| Intel Pentium Gold | 1         | 0.83%   |
| Intel Pentium Dual | 1         | 0.83%   |
| Intel Core M       | 1         | 0.83%   |
| Intel Core 2       | 1         | 0.83%   |
| AMD Ryzen Embedded | 1         | 0.83%   |
| AMD GX             | 1         | 0.83%   |
| AMD EPYC           | 1         | 0.83%   |
| AMD Athlon 64 X2   | 1         | 0.83%   |
| AMD Athlon         | 1         | 0.83%   |
| AMD A8             | 1         | 0.83%   |
| AMD A4             | 1         | 0.83%   |
| AMD A10            | 1         | 0.83%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 43        | 35.83%  |
| 4      | 41        | 34.17%  |
| 8      | 13        | 10.83%  |
| 6      | 10        | 8.33%   |
| 16     | 4         | 3.33%   |
| 12     | 4         | 3.33%   |
| 1      | 2         | 1.67%   |
| 14     | 1         | 0.83%   |
| 10     | 1         | 0.83%   |
| 3      | 1         | 0.83%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 113       | 94.17%  |
| 2      | 7         | 5.83%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 88        | 73.33%  |
| 1      | 32        | 26.67%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 117       | 97.5%   |
| Unknown        | 2         | 1.67%   |
| 32-bit         | 1         | 0.83%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 24        | 20%     |
| 0x306a9    | 9         | 7.5%    |
| 0x306c3    | 5         | 4.17%   |
| 0x206d7    | 5         | 4.17%   |
| 0x306d4    | 4         | 3.33%   |
| 0x1067a    | 4         | 3.33%   |
| 0x806ec    | 3         | 2.5%    |
| 0x806ea    | 3         | 2.5%    |
| 0x806d1    | 3         | 2.5%    |
| 0x806c1    | 3         | 2.5%    |
| 0x406e3    | 3         | 2.5%    |
| 0x406c4    | 3         | 2.5%    |
| 0x206a7    | 3         | 2.5%    |
| 0x08701013 | 3         | 2.5%    |
| 0x08108109 | 3         | 2.5%    |
| 0x906ed    | 2         | 1.67%   |
| 0x906ea    | 2         | 1.67%   |
| 0x6fd      | 2         | 1.67%   |
| 0x506e3    | 2         | 1.67%   |
| 0x306f2    | 2         | 1.67%   |
| 0x106c2    | 2         | 1.67%   |
| 0x0a201016 | 2         | 1.67%   |
| 0x08701021 | 2         | 1.67%   |
| 0x0810100b | 2         | 1.67%   |
| 0x06001119 | 2         | 1.67%   |
| 0x06000822 | 2         | 1.67%   |
| 0xa0671    | 1         | 0.83%   |
| 0xa0660    | 1         | 0.83%   |
| 0xa0653    | 1         | 0.83%   |
| 0xa0652    | 1         | 0.83%   |
| 0x906e9    | 1         | 0.83%   |
| 0x806e9    | 1         | 0.83%   |
| 0x706a1    | 1         | 0.83%   |
| 0x6fa      | 1         | 0.83%   |
| 0x40651    | 1         | 0.83%   |
| 0x306e4    | 1         | 0.83%   |
| 0x206c2    | 1         | 0.83%   |
| 0x20655    | 1         | 0.83%   |
| 0x106e5    | 1         | 0.83%   |
| 0x08600106 | 1         | 0.83%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 17        | 14.17%  |
| Haswell       | 11        | 9.17%   |
| Zen 2         | 10        | 8.33%   |
| IvyBridge     | 10        | 8.33%   |
| SandyBridge   | 9         | 7.5%    |
| Skylake       | 6         | 5%      |
| Piledriver    | 6         | 5%      |
| Core          | 6         | 5%      |
| Penryn        | 5         | 4.17%   |
| Zen+          | 4         | 3.33%   |
| Zen           | 4         | 3.33%   |
| Silvermont    | 4         | 3.33%   |
| Icelake       | 4         | 3.33%   |
| Broadwell     | 4         | 3.33%   |
| Westmere      | 3         | 2.5%    |
| TigerLake     | 3         | 2.5%    |
| CometLake     | 3         | 2.5%    |
| Zen 3         | 2         | 1.67%   |
| Bonnell       | 2         | 1.67%   |
| Unknown       | 2         | 1.67%   |
| Puma          | 1         | 0.83%   |
| Nehalem       | 1         | 0.83%   |
| K8 Hammer     | 1         | 0.83%   |
| Jaguar        | 1         | 0.83%   |
| Goldmont plus | 1         | 0.83%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 57        | 44.53%  |
| Nvidia                     | 35        | 27.34%  |
| AMD                        | 32        | 25%     |
| Matrox Electronics Systems | 4         | 3.13%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 5         | 3.79%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 3.03%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 3.03%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 3.03%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 3.03%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 3.03%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 3         | 2.27%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 3         | 2.27%   |
| Intel UHD Graphics 620                                                                   | 3         | 2.27%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 2.27%   |
| Intel HD Graphics 620                                                                    | 3         | 2.27%   |
| Intel HD Graphics 5500                                                                   | 3         | 2.27%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 2.27%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 2.27%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 1.52%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 1.52%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 2         | 1.52%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 1.52%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.52%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 1.52%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 1.52%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2         | 1.52%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 1.52%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 2         | 1.52%   |
| AMD Renoir                                                                               | 2         | 1.52%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 2         | 1.52%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1         | 0.76%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 1         | 0.76%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 0.76%   |
| Nvidia GP107GL [Quadro P1000]                                                            | 1         | 0.76%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 0.76%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 1         | 0.76%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1         | 0.76%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1         | 0.76%   |
| Nvidia GM204GLM [Quadro M3000M]                                                          | 1         | 0.76%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1         | 0.76%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1         | 0.76%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1         | 0.76%   |
| Nvidia GK110GL [Quadro K5200]                                                            | 1         | 0.76%   |
| Nvidia GK107M [GeForce GT 745M]                                                          | 1         | 0.76%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 49        | 40.83%  |
| 1 x AMD        | 30        | 25%     |
| 1 x Nvidia     | 23        | 19.17%  |
| Intel + Nvidia | 8         | 6.67%   |
| 1 x Matrox     | 4         | 3.33%   |
| Other          | 3         | 2.5%    |
| AMD + Nvidia   | 2         | 1.67%   |
| 2 x Nvidia     | 1         | 0.83%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 91        | 75.83%  |
| Proprietary | 19        | 15.83%  |
| Unknown     | 10        | 8.33%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 66        | 54.55%  |
| 0.51-1.0   | 14        | 11.57%  |
| 1.01-2.0   | 12        | 9.92%   |
| 3.01-4.0   | 8         | 6.61%   |
| 7.01-8.0   | 7         | 5.79%   |
| 0.01-0.5   | 6         | 4.96%   |
| 5.01-6.0   | 4         | 3.31%   |
| 8.01-16.0  | 3         | 2.48%   |
| 2.01-3.0   | 1         | 0.83%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Samsung Electronics  | 13        | 10.4%   |
| LG Display           | 12        | 9.6%    |
| BOE                  | 12        | 9.6%    |
| Chimei Innolux       | 10        | 8%      |
| Hewlett-Packard      | 9         | 7.2%    |
| Dell                 | 9         | 7.2%    |
| AU Optronics         | 8         | 6.4%    |
| BenQ                 | 6         | 4.8%    |
| Goldstar             | 5         | 4%      |
| Sharp                | 4         | 3.2%    |
| Lenovo               | 4         | 3.2%    |
| Ancor Communications | 4         | 3.2%    |
| Acer                 | 4         | 3.2%    |
| ViewSonic            | 2         | 1.6%    |
| Iiyama               | 2         | 1.6%    |
| ASUSTek Computer     | 2         | 1.6%    |
| Xiaomi               | 1         | 0.8%    |
| Wacom                | 1         | 0.8%    |
| Unknown              | 1         | 0.8%    |
| UGD                  | 1         | 0.8%    |
| Toshiba              | 1         | 0.8%    |
| Sony                 | 1         | 0.8%    |
| PANDA                | 1         | 0.8%    |
| Panasonic            | 1         | 0.8%    |
| ONN                  | 1         | 0.8%    |
| NEC Computers        | 1         | 0.8%    |
| JVC                  | 1         | 0.8%    |
| IOD                  | 1         | 0.8%    |
| Gigabyte Technology  | 1         | 0.8%    |
| GDH                  | 1         | 0.8%    |
| Eizo                 | 1         | 0.8%    |
| DPC                  | 1         | 0.8%    |
| Apple                | 1         | 0.8%    |
| AOC                  | 1         | 0.8%    |
| Unknown              | 1         | 0.8%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0353 1366x768 345x194mm 15.6-inch          | 2         | 1.56%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 2         | 1.56%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch        | 2         | 1.56%   |
| Xiaomi Mi TV XMD009A 3440x1440 480x270mm 21.7-inch                   | 1         | 0.78%   |
| Wacom Cintiq 22HDT WAC1037 1920x1080 476x268mm 21.5-inch             | 1         | 0.78%   |
| ViewSonic LCD Monitor VX2276 Series 1920x1080                        | 1         | 0.78%   |
| ViewSonic LCD Monitor VA2448 SERIES 1920x1080                        | 1         | 0.78%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch            | 1         | 0.78%   |
| UGD LCD Monitor UGD1302 1920x1080 290x160mm 13.0-inch                | 1         | 0.78%   |
| Toshiba TV TSB0206 1920x1080 886x498mm 40.0-inch                     | 1         | 0.78%   |
| Sony TV SNY8102 1360x768 1600x900mm 72.3-inch                        | 1         | 0.78%   |
| Sharp LQ173M1JW05 SHP14EC 1920x1080 380x210mm 17.1-inch              | 1         | 0.78%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch              | 1         | 0.78%   |
| Sharp LQ125T1JW02 SHP142F 2560x1440 277x155mm 12.5-inch              | 1         | 0.78%   |
| Sharp LCD Monitor SHP14C4 1920x1080 344x194mm 15.5-inch              | 1         | 0.78%   |
| Samsung Electronics SyncMaster SAM0578 1920x1080 476x268mm 21.5-inch | 1         | 0.78%   |
| Samsung Electronics SyncMaster SAM04DF 1360x768 410x230mm 18.5-inch  | 1         | 0.78%   |
| Samsung Electronics SyncMaster SAM0428 1680x1050 459x296mm 21.5-inch | 1         | 0.78%   |
| Samsung Electronics SyncMaster SAM0248 1280x1024 380x300mm 19.1-inch | 1         | 0.78%   |
| Samsung Electronics SyncMaster SAM01AD 1600x1200 408x306mm 20.1-inch | 1         | 0.78%   |
| Samsung Electronics SMS27A650 SAM082D 1920x1080 598x336mm 27.0-inch  | 1         | 0.78%   |
| Samsung Electronics SMS19A100 SAM0867 1366x768 410x230mm 18.5-inch   | 1         | 0.78%   |
| Samsung Electronics SMB2430L SAM0644 1920x1080 521x293mm 23.5-inch   | 1         | 0.78%   |
| Samsung Electronics SM2333T SAM0736 1920x1080 477x268mm 21.5-inch    | 1         | 0.78%   |
| Samsung Electronics S24D390 SAM0B65 1920x1080 521x293mm 23.5-inch    | 1         | 0.78%   |
| Samsung Electronics S22D300 SAM0B3E 1920x1080 477x268mm 21.5-inch    | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 340x190mm 15.3-inch | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 353x198mm 15.9-inch | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch | 1         | 0.78%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch              | 1         | 0.78%   |
| Panasonic TDM13O56 MEI96A2 3000x2000 285x190mm 13.5-inch             | 1         | 0.78%   |
| ONN 100002480 ONN0101 1920x1080 470x290mm 21.7-inch                  | 1         | 0.78%   |
| NEC Computers LCD2490WUXi NEC66CE 1920x1200 518x324mm 24.1-inch      | 1         | 0.78%   |
| LG Display LCD Monitor LGD0625 1920x1080 344x194mm 15.5-inch         | 1         | 0.78%   |
| LG Display LCD Monitor LGD0599 1920x1080 309x174mm 14.0-inch         | 1         | 0.78%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch         | 1         | 0.78%   |
| LG Display LCD Monitor LGD0508 1366x768 309x174mm 14.0-inch          | 1         | 0.78%   |
| LG Display LCD Monitor LGD03D7 1366x768 310x174mm 14.0-inch          | 1         | 0.78%   |
| LG Display LCD Monitor LGD032C 1920x1080 344x194mm 15.5-inch         | 1         | 0.78%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch          | 1         | 0.78%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 58        | 47.54%  |
| 1366x768 (WXGA)    | 24        | 19.67%  |
| 1280x1024 (SXGA)   | 6         | 4.92%   |
| 3840x2160 (4K)     | 5         | 4.1%    |
| 2560x1440 (QHD)    | 5         | 4.1%    |
| 1680x1050 (WSXGA+) | 5         | 4.1%    |
| 1920x1200 (WUXGA)  | 4         | 3.28%   |
| 1600x900 (HD+)     | 3         | 2.46%   |
| 3440x1440          | 2         | 1.64%   |
| 1360x768           | 2         | 1.64%   |
| 1280x800 (WXGA)    | 2         | 1.64%   |
| 3200x1080          | 1         | 0.82%   |
| 2288x1287          | 1         | 0.82%   |
| 2256x1504          | 1         | 0.82%   |
| 1920x540           | 1         | 0.82%   |
| 1600x1200          | 1         | 0.82%   |
| Unknown            | 1         | 0.82%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 28        | 22.4%   |
| 21      | 13        | 10.4%   |
| 24      | 12        | 9.6%    |
| 27      | 10        | 8%      |
| 14      | 10        | 8%      |
| 17      | 9         | 7.2%    |
| 13      | 9         | 7.2%    |
| 23      | 8         | 6.4%    |
| Unknown | 5         | 4%      |
| 20      | 4         | 3.2%    |
| 18      | 3         | 2.4%    |
| 12      | 3         | 2.4%    |
| 22      | 2         | 1.6%    |
| 19      | 2         | 1.6%    |
| 142     | 1         | 0.8%    |
| 74      | 1         | 0.8%    |
| 72      | 1         | 0.8%    |
| 52      | 1         | 0.8%    |
| 34      | 1         | 0.8%    |
| 32      | 1         | 0.8%    |
| 16      | 1         | 0.8%    |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 47        | 37.9%   |
| 501-600        | 28        | 22.58%  |
| 401-500        | 22        | 17.74%  |
| 351-400        | 9         | 7.26%   |
| 201-300        | 6         | 4.84%   |
| Unknown        | 5         | 4.03%   |
| 701-800        | 2         | 1.61%   |
| 1501-2000      | 2         | 1.61%   |
| More than 2000 | 1         | 0.81%   |
| 601-700        | 1         | 0.81%   |
| 1001-1500      | 1         | 0.81%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 85        | 74.56%  |
| 16/10   | 12        | 10.53%  |
| 5/4     | 4         | 3.51%   |
| Unknown | 4         | 3.51%   |
| 3/2     | 3         | 2.63%   |
| 6/5     | 2         | 1.75%   |
| 4/3     | 1         | 0.88%   |
| 32/9    | 1         | 0.88%   |
| 21/9    | 1         | 0.88%   |
| 1.00    | 1         | 0.88%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 29        | 23.58%  |
| 201-250        | 25        | 20.33%  |
| 81-90          | 17        | 13.82%  |
| 301-350        | 10        | 8.13%   |
| 151-200        | 8         | 6.5%    |
| 141-150        | 7         | 5.69%   |
| 251-300        | 6         | 4.88%   |
| 121-130        | 5         | 4.07%   |
| Unknown        | 5         | 4.07%   |
| More than 1000 | 4         | 3.25%   |
| 61-70          | 3         | 2.44%   |
| 71-80          | 2         | 1.63%   |
| 351-500        | 2         | 1.63%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 44        | 35.48%  |
| 101-120       | 35        | 28.23%  |
| 121-160       | 30        | 24.19%  |
| Unknown       | 5         | 4.03%   |
| 1-50          | 4         | 3.23%   |
| More than 240 | 3         | 2.42%   |
| 161-240       | 3         | 2.42%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 91        | 75.83%  |
| 2     | 14        | 11.67%  |
| 0     | 11        | 9.17%   |
| 3     | 3         | 2.5%    |
| 4     | 1         | 0.83%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 73        | 41.48%  |
| Realtek Semiconductor    | 59        | 33.52%  |
| Qualcomm Atheros         | 12        | 6.82%   |
| Broadcom                 | 8         | 4.55%   |
| Ralink Technology        | 4         | 2.27%   |
| TP-Link                  | 3         | 1.7%    |
| Broadcom Limited         | 3         | 1.7%    |
| Nvidia                   | 2         | 1.14%   |
| ASIX Electronics         | 2         | 1.14%   |
| VIA Technologies         | 1         | 0.57%   |
| Sierra Wireless          | 1         | 0.57%   |
| Ralink                   | 1         | 0.57%   |
| Qualcomm                 | 1         | 0.57%   |
| Micro Star International | 1         | 0.57%   |
| Mellanox Technologies    | 1         | 0.57%   |
| Marvell Technology Group | 1         | 0.57%   |
| Hewlett-Packard          | 1         | 0.57%   |
| Dell                     | 1         | 0.57%   |
| Chelsio Communications   | 1         | 0.57%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 41        | 18.98%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 3.7%    |
| Intel I211 Gigabit Network Connection                             | 7         | 3.24%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 2.78%   |
| Intel 82574L Gigabit Network Connection                           | 5         | 2.31%   |
| Ralink MT7601U Wireless Adapter                                   | 4         | 1.85%   |
| Intel Wireless-AC 9260                                            | 4         | 1.85%   |
| Intel Wireless 8265 / 8275                                        | 4         | 1.85%   |
| Intel Wireless 7260                                               | 4         | 1.85%   |
| Intel Wi-Fi 6 AX200                                               | 4         | 1.85%   |
| Intel Ethernet Connection (2) I218-V                              | 4         | 1.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3         | 1.39%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 3         | 1.39%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 1.39%   |
| Intel Wireless 7265                                               | 3         | 1.39%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 3         | 1.39%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 1.39%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 1.39%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 0.93%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 0.93%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 0.93%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.93%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 2         | 0.93%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 0.93%   |
| Intel Wireless 8260                                               | 2         | 0.93%   |
| Intel Wireless 3160                                               | 2         | 0.93%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 0.93%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 0.93%   |
| Intel I350 Gigabit Network Connection                             | 2         | 0.93%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.93%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 0.93%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.93%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.93%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.93%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 0.93%   |
| Intel Centrino Ultimate-N 6300                                    | 2         | 0.93%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 0.93%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 0.93%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 2         | 0.93%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1         | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 48        | 57.83%  |
| Realtek Semiconductor    | 11        | 13.25%  |
| Qualcomm Atheros         | 9         | 10.84%  |
| Ralink Technology        | 4         | 4.82%   |
| TP-Link                  | 3         | 3.61%   |
| Broadcom                 | 3         | 3.61%   |
| Sierra Wireless          | 1         | 1.2%    |
| Ralink                   | 1         | 1.2%    |
| Micro Star International | 1         | 1.2%    |
| Dell                     | 1         | 1.2%    |
| Broadcom Limited         | 1         | 1.2%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Ralink MT7601U Wireless Adapter                                                       | 4         | 4.82%   |
| Intel Wireless-AC 9260                                                                | 4         | 4.82%   |
| Intel Wireless 8265 / 8275                                                            | 4         | 4.82%   |
| Intel Wireless 7260                                                                   | 4         | 4.82%   |
| Intel Wi-Fi 6 AX200                                                                   | 4         | 4.82%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 3         | 3.61%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 3         | 3.61%   |
| Intel Wireless 7265                                                                   | 3         | 3.61%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 3         | 3.61%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 3         | 3.61%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 3         | 3.61%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 2         | 2.41%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                      | 2         | 2.41%   |
| Intel Wireless 8260                                                                   | 2         | 2.41%   |
| Intel Wireless 3160                                                                   | 2         | 2.41%   |
| Intel Wi-Fi 6 AX201                                                                   | 2         | 2.41%   |
| Intel Tiger Lake PCH CNVi WiFi                                                        | 2         | 2.41%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 2         | 2.41%   |
| Intel Centrino Ultimate-N 6300                                                        | 2         | 2.41%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                           | 1         | 1.2%    |
| TP-Link RTL8812AU Archer T4U 802.11ac                                                 | 1         | 1.2%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                            | 1         | 1.2%    |
| Sierra Wireless EM7305                                                                | 1         | 1.2%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 1         | 1.2%    |
| Realtek RTL8723DE Wireless Network Adapter                                            | 1         | 1.2%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                       | 1         | 1.2%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1         | 1.2%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                               | 1         | 1.2%    |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                             | 1         | 1.2%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 1         | 1.2%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                        | 1         | 1.2%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 1         | 1.2%    |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                      | 1         | 1.2%    |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 1.2%    |
| Micro Star International MS-3871 802.11bgn Wireless Module [Ralink RT8070]            | 1         | 1.2%    |
| Intel Wireless 3165                                                                   | 1         | 1.2%    |
| Intel WiFi Link 5100                                                                  | 1         | 1.2%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                         | 1         | 1.2%    |
| Intel Gemini Lake PCH CNVi WiFi                                                       | 1         | 1.2%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 1         | 1.2%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 56        | 45.53%  |
| Intel                    | 44        | 35.77%  |
| Qualcomm Atheros         | 6         | 4.88%   |
| Broadcom                 | 6         | 4.88%   |
| Nvidia                   | 2         | 1.63%   |
| Broadcom Limited         | 2         | 1.63%   |
| ASIX Electronics         | 2         | 1.63%   |
| VIA Technologies         | 1         | 0.81%   |
| Qualcomm                 | 1         | 0.81%   |
| Mellanox Technologies    | 1         | 0.81%   |
| Marvell Technology Group | 1         | 0.81%   |
| Chelsio Communications   | 1         | 0.81%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 41        | 31.06%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 8         | 6.06%   |
| Intel I211 Gigabit Network Connection                                         | 7         | 5.3%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 6         | 4.55%   |
| Intel 82574L Gigabit Network Connection                                       | 5         | 3.79%   |
| Intel Ethernet Connection (2) I218-V                                          | 4         | 3.03%   |
| Realtek RTL8125 2.5GbE Controller                                             | 3         | 2.27%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 2         | 1.52%   |
| Realtek Killer E3000 2.5GbE Controller                                        | 2         | 1.52%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 2         | 1.52%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 2         | 1.52%   |
| Intel I350 Gigabit Network Connection                                         | 2         | 1.52%   |
| Intel Ethernet Connection I217-V                                              | 2         | 1.52%   |
| Intel Ethernet Connection (7) I219-V                                          | 2         | 1.52%   |
| Intel Ethernet Connection (4) I219-LM                                         | 2         | 1.52%   |
| Intel Ethernet Connection (3) I218-LM                                         | 2         | 1.52%   |
| Intel Ethernet Connection (2) I219-LM                                         | 2         | 1.52%   |
| Intel 82579V Gigabit Network Connection                                       | 2         | 1.52%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 2         | 1.52%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 2         | 1.52%   |
| VIA VT6105/VT6106S [Rhine-III]                                                | 1         | 0.76%   |
| Realtek USB 10/100/1G/2.5G LAN                                                | 1         | 0.76%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1         | 0.76%   |
| Qualcomm Mobile Router                                                        | 1         | 0.76%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1         | 0.76%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1         | 0.76%   |
| Nvidia MCP79 Ethernet                                                         | 1         | 0.76%   |
| Nvidia MCP61 Ethernet                                                         | 1         | 0.76%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]                         | 1         | 0.76%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                       | 1         | 0.76%   |
| Intel Ethernet Connection I219-LM                                             | 1         | 0.76%   |
| Intel Ethernet Connection I218-V                                              | 1         | 0.76%   |
| Intel Ethernet Connection (4) I219-V                                          | 1         | 0.76%   |
| Intel Ethernet Connection (2) I219-V                                          | 1         | 0.76%   |
| Intel Ethernet Connection (2) I218-LM                                         | 1         | 0.76%   |
| Intel Ethernet Connection (12) I219-V                                         | 1         | 0.76%   |
| Intel Ethernet Connection (10) I219-V                                         | 1         | 0.76%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 1         | 0.76%   |
| Intel 82576 Gigabit Network Connection                                        | 1         | 0.76%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 0.76%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 111       | 57.81%  |
| WiFi     | 80        | 41.67%  |
| Modem    | 1         | 0.52%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 67        | 56.78%  |
| WiFi     | 51        | 43.22%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 66        | 54.55%  |
| 1     | 39        | 32.23%  |
| 3     | 6         | 4.96%   |
| 4     | 5         | 4.13%   |
| 0     | 4         | 3.31%   |
| 5     | 1         | 0.83%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 109       | 90.08%  |
| Yes  | 12        | 9.92%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 41        | 55.41%  |
| Cambridge Silicon Radio         | 12        | 16.22%  |
| Realtek Semiconductor           | 6         | 8.11%   |
| Broadcom                        | 6         | 8.11%   |
| Qualcomm Atheros Communications | 3         | 4.05%   |
| Micro Star International        | 2         | 2.7%    |
| Apple                           | 2         | 2.7%    |
| Toshiba                         | 1         | 1.35%   |
| Foxconn / Hon Hai               | 1         | 1.35%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 17        | 22.97%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 12        | 16.22%  |
| Intel AX201 Bluetooth                               | 6         | 8.11%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 5.41%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 4         | 5.41%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 5.41%   |
| Intel AX200 Bluetooth                               | 4         | 5.41%   |
| Intel AX210 Bluetooth                               | 3         | 4.05%   |
| Realtek Bluetooth Radio                             | 2         | 2.7%    |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 2.7%    |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 2.7%    |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2         | 2.7%    |
| Toshiba Askey Bluetooth Module                      | 1         | 1.35%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 1.35%   |
| Micro Star International Bluetooth Dongle           | 1         | 1.35%   |
| Micro Star International Bluetooth Device           | 1         | 1.35%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.35%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 1.35%   |
| Broadcom HP Portable SoftSailing                    | 1         | 1.35%   |
| Broadcom BCM20702A0                                 | 1         | 1.35%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.35%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 1         | 1.35%   |
| Apple Bluetooth USB Host Controller                 | 1         | 1.35%   |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 1         | 1.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 80        | 49.69%  |
| AMD                    | 35        | 21.74%  |
| Nvidia                 | 29        | 18.01%  |
| Creative Labs          | 7         | 4.35%   |
| C-Media Electronics    | 4         | 2.48%   |
| VIA Technologies       | 1         | 0.62%   |
| Texas Instruments      | 1         | 0.62%   |
| M-Audio                | 1         | 0.62%   |
| Generalplus Technology | 1         | 0.62%   |
| EGO SYStems            | 1         | 0.62%   |
| ASUSTek Computer       | 1         | 0.62%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 10        | 5.13%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 9         | 4.62%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 9         | 4.62%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 8         | 4.1%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 7         | 3.59%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 6         | 3.08%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 2.56%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 2.56%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 5         | 2.56%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 4         | 2.05%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 2.05%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 4         | 2.05%   |
| Intel Broadwell-U Audio Controller                                                                | 4         | 2.05%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 2.05%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 2.05%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 2.05%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 4         | 2.05%   |
| AMD FCH Azalia Controller                                                                         | 4         | 2.05%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 1.54%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 3         | 1.54%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 1.54%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 1.54%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 3         | 1.54%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 1.54%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.54%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                                     | 3         | 1.54%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 3         | 1.54%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 1.03%   |
| Nvidia MCP61 High Definition Audio                                                                | 2         | 1.03%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 1.03%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 2         | 1.03%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 1.03%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 1.03%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 2         | 1.03%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 1.03%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 1.03%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 1.03%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 1.03%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 1.03%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 2         | 1.03%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 26        | 20.63%  |
| Kingston            | 22        | 17.46%  |
| Samsung Electronics | 18        | 14.29%  |
| Crucial             | 11        | 8.73%   |
| Corsair             | 10        | 7.94%   |
| Unknown             | 7         | 5.56%   |
| Micron Technology   | 7         | 5.56%   |
| Team                | 4         | 3.17%   |
| Transcend           | 2         | 1.59%   |
| Ramaxel Technology  | 2         | 1.59%   |
| A-DATA Technology   | 2         | 1.59%   |
| Strontium           | 1         | 0.79%   |
| Smart               | 1         | 0.79%   |
| Silicon Power       | 1         | 0.79%   |
| Neo Forza           | 1         | 0.79%   |
| Nanya Technology    | 1         | 0.79%   |
| HPE                 | 1         | 0.79%   |
| Goodram             | 1         | 0.79%   |
| GLOWAY              | 1         | 0.79%   |
| G.Skill             | 1         | 0.79%   |
| Essencore Limited   | 1         | 0.79%   |
| Elpida              | 1         | 0.79%   |
| Avant               | 1         | 0.79%   |
| AMD                 | 1         | 0.79%   |
| A Force             | 1         | 0.79%   |
| Unknown             | 1         | 0.79%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB DIMM SDRAM                        | 2         | 1.44%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3200MT/s          | 2         | 1.44%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 2         | 1.44%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s      | 2         | 1.44%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                   | 1         | 0.72%   |
| Unknown RAM Module 4096MB DIMM DDR3 65535MT/s               | 1         | 0.72%   |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s                  | 1         | 0.72%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                      | 1         | 0.72%   |
| Unknown RAM Module 1024MB SODIMM SDRAM                      | 1         | 0.72%   |
| Unknown RAM Module 1024MB DIMM DDR 800MT/s                  | 1         | 0.72%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                      | 1         | 0.72%   |
| Transcend RAM TS256MLQ72V6U 2GB DIMM DDR2 667MT/s           | 1         | 0.72%   |
| Transcend RAM JM1600KLN-8GK 4096MB DIMM DDR3 1600MT/s       | 1         | 0.72%   |
| Team RAM TEAMGROUP-UD4-3600 32GB DIMM DDR4 3600MT/s         | 1         | 0.72%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3600MT/s         | 1         | 0.72%   |
| Strontium RAM SRT4G86U1-P9H 4096MB DIMM DDR3 1333MT/s       | 1         | 0.72%   |
| Smart RAM SH5641G8FJ8NWRNSQG 8GB SODIMM DDR3 1600MT/s       | 1         | 0.72%   |
| SK hynix RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s     | 1         | 0.72%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s             | 1         | 0.72%   |
| SK hynix RAM HYMP512F72CP8N3-Y5 1024MB FB-DIMM DDR2 667MT/s | 1         | 0.72%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s       | 1         | 0.72%   |
| SK hynix RAM HMT41GV7BMR4A-H9 16GB DIMM 1333MT/s            | 1         | 0.72%   |
| SK hynix RAM HMT41GU6BFR8A-PB 8192MB DIMM DDR3 2000MT/s     | 1         | 0.72%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s      | 1         | 0.72%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s      | 1         | 0.72%   |
| SK hynix RAM HMT351U6BFR8C-H9 4096MB DIMM DDR3 1333MT/s     | 1         | 0.72%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 0.72%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1333MT/s   | 1         | 0.72%   |
| SK hynix RAM HMT351R7CFR8A-H9 4096MB DIMM DDR3 1333MT/s     | 1         | 0.72%   |
| SK hynix RAM HMT31GR7EFR4A 8192MB DIMM DDR3 1600MT/s        | 1         | 0.72%   |
| SK hynix RAM HMT31GR7BFR4A-H9 16GB DIMM 1333MT/s            | 1         | 0.72%   |
| SK hynix RAM HMT125R7BFR8C-H9 4GB DIMM 1333MT/s             | 1         | 0.72%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s      | 1         | 0.72%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s      | 1         | 0.72%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s      | 1         | 0.72%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s      | 1         | 0.72%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s      | 1         | 0.72%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s   | 1         | 0.72%   |
| SK hynix RAM HMA81GR7CJR8N-XN 8192MB DIMM DDR4 3200MT/s     | 1         | 0.72%   |
| SK hynix RAM HMA451S6AFR8N-TF 4096MB SODIMM DDR4 2133MT/s   | 1         | 0.72%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 49        | 44.55%  |
| DDR3    | 44        | 40%     |
| DDR2    | 5         | 4.55%   |
| SDRAM   | 4         | 3.64%   |
| LPDDR3  | 3         | 2.73%   |
| LPDDR4  | 2         | 1.82%   |
| Unknown | 2         | 1.82%   |
| DDR     | 1         | 0.91%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 53        | 48.62%  |
| DIMM         | 52        | 47.71%  |
| Row Of Chips | 2         | 1.83%   |
| RIMM         | 1         | 0.92%   |
| FB-DIMM      | 1         | 0.92%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 45        | 37.5%   |
| 4096  | 40        | 33.33%  |
| 16384 | 14        | 11.67%  |
| 2048  | 10        | 8.33%   |
| 32768 | 6         | 5%      |
| 1024  | 5         | 4.17%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 31        | 26.05%  |
| 3200    | 16        | 13.45%  |
| 2667    | 14        | 11.76%  |
| 2400    | 11        | 9.24%   |
| 1333    | 8         | 6.72%   |
| 3600    | 6         | 5.04%   |
| 2133    | 5         | 4.2%    |
| 667     | 5         | 4.2%    |
| 1867    | 3         | 2.52%   |
| Unknown | 3         | 2.52%   |
| 2666    | 2         | 1.68%   |
| 1866    | 2         | 1.68%   |
| 975     | 2         | 1.68%   |
| 65535   | 1         | 0.84%   |
| 4199    | 1         | 0.84%   |
| 3800    | 1         | 0.84%   |
| 2933    | 1         | 0.84%   |
| 2472    | 1         | 0.84%   |
| 2187    | 1         | 0.84%   |
| 2000    | 1         | 0.84%   |
| 1334    | 1         | 0.84%   |
| 1066    | 1         | 0.84%   |
| 800     | 1         | 0.84%   |
| 701     | 1         | 0.84%   |

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


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 3         | 4.76%   |
| Acer HD Webcam                                      | 3         | 4.76%   |
| Acer BisonCam,NB Pro                                | 3         | 4.76%   |
| Realtek USB Camera                                  | 2         | 3.17%   |
| Quanta HP Webcam                                    | 2         | 3.17%   |
| Logitech Webcam C270                                | 2         | 3.17%   |
| Chicony FJ Camera                                   | 2         | 3.17%   |
| Syntek USB2.0 Camera                                | 1         | 1.59%   |
| Sunplus Laptop_Integrated_Webcam_FHD                | 1         | 1.59%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 1.59%   |
| Silicon Motion Web Camera                           | 1         | 1.59%   |
| Samsung Galaxy A5 (MTP)                             | 1         | 1.59%   |
| Realtek Laptop Camera                               | 1         | 1.59%   |
| Realtek EasyCamera                                  | 1         | 1.59%   |
| Motorola PCS XT1033 [Moto G], PTP mode              | 1         | 1.59%   |
| Microdia Laptop_Integrated_Webcam_2M                | 1         | 1.59%   |
| Microdia Integrated_Webcam_HD                       | 1         | 1.59%   |
| Microdia Integrated Webcam                          | 1         | 1.59%   |
| Microdia Dell Integrated HD Webcam                  | 1         | 1.59%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 1.59%   |
| Logitech Webcam C310                                | 1         | 1.59%   |
| Logitech Webcam C300                                | 1         | 1.59%   |
| Logitech Webcam C170                                | 1         | 1.59%   |
| Logitech QuickCam Pro 9000                          | 1         | 1.59%   |
| Logitech HD Webcam C525                             | 1         | 1.59%   |
| Logitech HD Pro Webcam C920                         | 1         | 1.59%   |
| Logitech C922 Pro Stream Webcam                     | 1         | 1.59%   |
| Logitech C920 PRO HD Webcam                         | 1         | 1.59%   |
| Lite-On TOSHIBA Web Camera - FHD                    | 1         | 1.59%   |
| Lite-On Integrated Camera                           | 1         | 1.59%   |
| Lite-On HP TrueVision HD Camera                     | 1         | 1.59%   |
| IMC Networks UVC VGA Webcam                         | 1         | 1.59%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 1         | 1.59%   |
| IMC Networks Lenovo EasyCamera                      | 1         | 1.59%   |
| IMC Networks Integrated Camera                      | 1         | 1.59%   |
| Chicony Web Camera - FHD                            | 1         | 1.59%   |
| Chicony TOSHIBA Web Camera - HD                     | 1         | 1.59%   |
| Chicony TOSHIBA Web Camera - FHD                    | 1         | 1.59%   |
| Chicony Integrated Camera [ThinkPad]                | 1         | 1.59%   |
| Chicony Integrated Camera (1280x720@30)             | 1         | 1.59%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 6         | 46.15%  |
| Synaptics             | 3         | 23.08%  |
| STMicroelectronics    | 2         | 15.38%  |
| LighTuning Technology | 1         | 7.69%   |
| Elan Microelectronics | 1         | 7.69%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| STMicroelectronics Fingerprint Reader             | 2         | 15.38%  |
| Unknown                                           | 2         | 15.38%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor | 1         | 7.69%   |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 7.69%   |
| Validity Sensors VFS300 Fingerprint Reader        | 1         | 7.69%   |
| Validity Sensors VFS Fingerprint sensor           | 1         | 7.69%   |
| Validity Sensors VFS 5011 fingerprint sensor      | 1         | 7.69%   |
| Validity Sensors Synaptics WBDI                   | 1         | 7.69%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 7.69%   |
| LighTuning EgisTec Touch Fingerprint Sensor       | 1         | 7.69%   |
| Elan ELAN:Fingerprint                             | 1         | 7.69%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 3         | 37.5%   |
| Broadcom              | 2         | 25%     |
| O2 Micro              | 1         | 12.5%   |
| Lenovo                | 1         | 12.5%   |
| Gemalto (was Gemplus) | 1         | 12.5%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                  | Computers | Percent |
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

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 75        | 61.48%  |
| 1     | 25        | 20.49%  |
| 2     | 12        | 9.84%   |
| 3     | 6         | 4.92%   |
| 4     | 4         | 3.28%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 14        | 18.18%  |
| Fingerprint reader       | 12        | 15.58%  |
| Sound                    | 10        | 12.99%  |
| Communication controller | 8         | 10.39%  |
| Chipcard                 | 8         | 10.39%  |
| Net/wireless             | 7         | 9.09%   |
| Card reader              | 4         | 5.19%   |
| Unassigned class         | 3         | 3.9%    |
| Bluetooth                | 3         | 3.9%    |
| Net/ethernet             | 2         | 2.6%    |
| Multimedia controller    | 2         | 2.6%    |
| Storage/ata              | 1         | 1.3%    |
| Storage                  | 1         | 1.3%    |
| Firewire controller      | 1         | 1.3%    |
| Camera                   | 1         | 1.3%    |

