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

Total: 162

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASRock        | B550 Taichi                 | Desktop     | [469f9d71e2](https://linux-hardware.org/?probe=469f9d71e2) | Dec 29, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [5205b7c248](https://linux-hardware.org/?probe=5205b7c248) | Dec 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | Notebook    | [1cf2ac2b8b](https://linux-hardware.org/?probe=1cf2ac2b8b) | Dec 27, 2022 |
| Dell          | 0MY171 A00                  | Desktop     | [055bc4ea78](https://linux-hardware.org/?probe=055bc4ea78) | Dec 13, 2022 |
| ASUSTek       | SABERTOOTH X99              | Desktop     | [c0bf1336d5](https://linux-hardware.org/?probe=c0bf1336d5) | Dec 12, 2022 |
| Acer          | Extensa 5220                | Notebook    | [30ca0c3efa](https://linux-hardware.org/?probe=30ca0c3efa) | Dec 06, 2022 |
| HP            | OMEN by Laptop 16-b1xxx     | Notebook    | [799470f1aa](https://linux-hardware.org/?probe=799470f1aa) | Dec 05, 2022 |
| HP            | 8906 SMVB                   | Desktop     | [d000e4e926](https://linux-hardware.org/?probe=d000e4e926) | Dec 02, 2022 |
| HP            | OMEN by Laptop 16-b1xxx     | Notebook    | [0cd3005f69](https://linux-hardware.org/?probe=0cd3005f69) | Dec 01, 2022 |
| HP            | OMEN by Laptop 16-b1xxx     | Notebook    | [32b68762df](https://linux-hardware.org/?probe=32b68762df) | Nov 30, 2022 |
| Lenovo        | 31900058 STD                | Desktop     | [1408b2dc5f](https://linux-hardware.org/?probe=1408b2dc5f) | Nov 18, 2022 |
| Lenovo        | ThinkPad T470 20JNS01R01    | Notebook    | [abb8194196](https://linux-hardware.org/?probe=abb8194196) | Oct 21, 2022 |
| Lenovo        | ThinkPad T61 765912G        | Notebook    | [e7f2dc737e](https://linux-hardware.org/?probe=e7f2dc737e) | Oct 09, 2022 |
| Lenovo        | ThinkPad T410 2518C3U       | Notebook    | [4d250adf3b](https://linux-hardware.org/?probe=4d250adf3b) | Oct 04, 2022 |
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

![OS](./images/pie_chart/os_name.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| Slackware 14.2  | 63        | 48.09%  |
| Slackware 15.0  | 62        | 47.33%  |
| Slackware 14.2+ | 6         | 4.58%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| Slackware | 129       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.15.19           | 15        | 10.87%  |
| 4.19.80           | 8         | 5.8%    |
| 5.10.28-Unraid    | 6         | 4.35%   |
| 5.19.17           | 4         | 2.9%    |
| 5.15.27           | 4         | 2.9%    |
| 4.4.190           | 4         | 2.9%    |
| 5.15.63           | 3         | 2.17%   |
| 4.4.240           | 3         | 2.17%   |
| 5.3.7             | 2         | 1.45%   |
| 5.17.2            | 2         | 1.45%   |
| 5.17.1            | 2         | 1.45%   |
| 5.16.13           | 2         | 1.45%   |
| 5.15.38           | 2         | 1.45%   |
| 5.15.30-Unraid    | 2         | 1.45%   |
| 5.13.8            | 2         | 1.45%   |
| 5.10.3            | 2         | 1.45%   |
| 4.4.276           | 2         | 1.45%   |
| 6.1.1             | 1         | 0.72%   |
| 5.7.0             | 1         | 0.72%   |
| 5.5.10            | 1         | 0.72%   |
| 5.4.77            | 1         | 0.72%   |
| 5.4.75            | 1         | 0.72%   |
| 5.4.62            | 1         | 0.72%   |
| 5.4.53-APRL       | 1         | 0.72%   |
| 5.4.50            | 1         | 0.72%   |
| 5.4.47            | 1         | 0.72%   |
| 5.4.43            | 1         | 0.72%   |
| 5.4.24toshiba-new | 1         | 0.72%   |
| 5.4.2             | 1         | 0.72%   |
| 5.4.139-jw        | 1         | 0.72%   |
| 5.4.13            | 1         | 0.72%   |
| 5.4.12+           | 1         | 0.72%   |
| 5.4.0-rc2-vto     | 1         | 0.72%   |
| 5.2.2             | 1         | 0.72%   |
| 5.19.16           | 1         | 0.72%   |
| 5.17.5            | 1         | 0.72%   |
| 5.17.0-custom     | 1         | 0.72%   |
| 5.16.9-joe1       | 1         | 0.72%   |
| 5.16.18           | 1         | 0.72%   |
| 5.16.12           | 1         | 0.72%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.19 | 15        | 10.87%  |
| 4.19.80 | 8         | 5.8%    |
| 5.10.28 | 6         | 4.35%   |
| 4.4.190 | 5         | 3.62%   |
| 5.19.17 | 4         | 2.9%    |
| 5.15.27 | 4         | 2.9%    |
| 5.15.63 | 3         | 2.17%   |
| 4.4.240 | 3         | 2.17%   |
| 5.3.7   | 2         | 1.45%   |
| 5.17.2  | 2         | 1.45%   |
| 5.17.1  | 2         | 1.45%   |
| 5.16.13 | 2         | 1.45%   |
| 5.15.38 | 2         | 1.45%   |
| 5.15.30 | 2         | 1.45%   |
| 5.14.15 | 2         | 1.45%   |
| 5.13.8  | 2         | 1.45%   |
| 5.10.3  | 2         | 1.45%   |
| 4.4.276 | 2         | 1.45%   |
| 6.1.1   | 1         | 0.72%   |
| 5.7.0   | 1         | 0.72%   |
| 5.5.10  | 1         | 0.72%   |
| 5.4.77  | 1         | 0.72%   |
| 5.4.75  | 1         | 0.72%   |
| 5.4.62  | 1         | 0.72%   |
| 5.4.53  | 1         | 0.72%   |
| 5.4.50  | 1         | 0.72%   |
| 5.4.47  | 1         | 0.72%   |
| 5.4.43  | 1         | 0.72%   |
| 5.4.24  | 1         | 0.72%   |
| 5.4.2   | 1         | 0.72%   |
| 5.4.139 | 1         | 0.72%   |
| 5.4.13  | 1         | 0.72%   |
| 5.4.12  | 1         | 0.72%   |
| 5.4.0   | 1         | 0.72%   |
| 5.2.2   | 1         | 0.72%   |
| 5.19.16 | 1         | 0.72%   |
| 5.17.5  | 1         | 0.72%   |
| 5.17.0  | 1         | 0.72%   |
| 5.16.9  | 1         | 0.72%   |
| 5.16.18 | 1         | 0.72%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 35        | 25.55%  |
| 4.4     | 17        | 12.41%  |
| 5.10    | 15        | 10.95%  |
| 4.19    | 15        | 10.95%  |
| 5.4     | 13        | 9.49%   |
| 5.14    | 7         | 5.11%   |
| 5.13    | 7         | 5.11%   |
| 5.17    | 6         | 4.38%   |
| 5.16    | 6         | 4.38%   |
| 5.19    | 5         | 3.65%   |
| 5.3     | 2         | 1.46%   |
| 4.9     | 2         | 1.46%   |
| 6.1     | 1         | 0.73%   |
| 5.7     | 1         | 0.73%   |
| 5.5     | 1         | 0.73%   |
| 5.2     | 1         | 0.73%   |
| 5.12    | 1         | 0.73%   |
| 4.20    | 1         | 0.73%   |
| 4.16    | 1         | 0.73%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 126       | 97.67%  |
| aarch64 | 2         | 1.55%   |
| i686    | 1         | 0.78%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Unknown       | 43        | 32.58%  |
| XFCE          | 37        | 28.03%  |
| KDE5          | 35        | 26.52%  |
| KDE           | 5         | 3.79%   |
| GNOME         | 3         | 2.27%   |
| MATE          | 2         | 1.52%   |
| FVWM          | 2         | 1.52%   |
| xwmconfig     | 1         | 0.76%   |
| X-Generic     | 1         | 0.76%   |
| LXQt          | 1         | 0.76%   |
| Enlightenment | 1         | 0.76%   |
| awesome       | 1         | 0.76%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 88        | 66.17%  |
| Tty     | 29        | 21.8%   |
| Unknown | 10        | 7.52%   |
| Wayland | 6         | 4.51%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 55        | 41.35%  |
| SDDM    | 43        | 32.33%  |
| XDM     | 30        | 22.56%  |
| SLiM    | 2         | 1.5%    |
| LightDM | 2         | 1.5%    |
| GDM     | 1         | 0.75%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 67        | 51.94%  |
| Unknown     | 38        | 29.46%  |
| ru_RU       | 4         | 3.1%    |
| pt_BR       | 3         | 2.33%   |
| it_IT       | 3         | 2.33%   |
| fr_FR       | 3         | 2.33%   |
| en_GB       | 2         | 1.55%   |
| de_DE       | 2         | 1.55%   |
| sr_RS@latin | 1         | 0.78%   |
| pt_PT       | 1         | 0.78%   |
| pl_PL       | 1         | 0.78%   |
| es_ES.UTF8  | 1         | 0.78%   |
| en_US.ASCII | 1         | 0.78%   |
| en_AU       | 1         | 0.78%   |
| C           | 1         | 0.78%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 70        | 53.85%  |
| EFI  | 60        | 46.15%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 94        | 72.87%  |
| Btrfs    | 14        | 10.85%  |
| Xfs      | 7         | 5.43%   |
| Overlay  | 6         | 4.65%   |
| Rootfs   | 3         | 2.33%   |
| Zfs      | 1         | 0.78%   |
| Reiserfs | 1         | 0.78%   |
| Jfs      | 1         | 0.78%   |
| F2fs     | 1         | 0.78%   |
| Ext3     | 1         | 0.78%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 88        | 66.67%  |
| MBR     | 32        | 24.24%  |
| Unknown | 12        | 9.09%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 90        | 68.18%  |
| Yes       | 42        | 31.82%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 85        | 65.89%  |
| Yes       | 44        | 34.11%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 21        | 16.28%  |
| ASUSTek Computer    | 21        | 16.28%  |
| Lenovo              | 16        | 12.4%   |
| Dell                | 13        | 10.08%  |
| MSI                 | 12        | 9.3%    |
| ASRock              | 8         | 6.2%    |
| Gigabyte Technology | 5         | 3.88%   |
| Acer                | 5         | 3.88%   |
| Toshiba             | 3         | 2.33%   |
| Notebook            | 2         | 1.55%   |
| Fujitsu             | 2         | 1.55%   |
| Dynabook            | 2         | 1.55%   |
| Apple               | 2         | 1.55%   |
| Unknown             | 2         | 1.55%   |
| TYAN Computer       | 1         | 0.78%   |
| System76            | 1         | 0.78%   |
| Supermicro          | 1         | 0.78%   |
| Sony                | 1         | 0.78%   |
| Shuttle             | 1         | 0.78%   |
| Samsung Electronics | 1         | 0.78%   |
| Radxa               | 1         | 0.78%   |
| NetGear             | 1         | 0.78%   |
| Intel               | 1         | 0.78%   |
| Huanan              | 1         | 0.78%   |
| HPE                 | 1         | 0.78%   |
| Framework           | 1         | 0.78%   |
| Foxconn             | 1         | 0.78%   |
| Biostar             | 1         | 0.78%   |
| AMI                 | 1         | 0.78%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| ASUS All Series                          | 4         | 3.1%    |
| Unknown                                  | 2         | 1.55%   |
| TYAN S7012                               | 1         | 0.78%   |
| Toshiba Satellite P50-A-12Z              | 1         | 0.78%   |
| Toshiba Satellite C660                   | 1         | 0.78%   |
| Toshiba PORTEGE Z30-A                    | 1         | 0.78%   |
| System76 Oryx Pro                        | 1         | 0.78%   |
| Supermicro X9DA7/E                       | 1         | 0.78%   |
| Sony SVE1713A1EW                         | 1         | 0.78%   |
| Shuttle NC03U                            | 1         | 0.78%   |
| Samsung 300E5M/300E5L                    | 1         | 0.78%   |
| Radxa ROCK Pi 4                          | 1         | 0.78%   |
| Notebook X170KM-G                        | 1         | 0.78%   |
| Notebook NL40_50CU                       | 1         | 0.78%   |
| NetGear ReadyDATA 5200                   | 1         | 0.78%   |
| MSI MS-7C52                              | 1         | 0.78%   |
| MSI MS-7C02                              | 1         | 0.78%   |
| MSI MS-7996                              | 1         | 0.78%   |
| MSI MS-7788                              | 1         | 0.78%   |
| MSI MS-7693                              | 1         | 0.78%   |
| MSI MS-7529                              | 1         | 0.78%   |
| MSI MS-7365                              | 1         | 0.78%   |
| MSI Modern 14 B11MO                      | 1         | 0.78%   |
| MSI Modern 14 B10MW                      | 1         | 0.78%   |
| MSI GP76 Leopard 11UG                    | 1         | 0.78%   |
| MSI GL73 8RC                             | 1         | 0.78%   |
| MSI GE76 Raider 11UE                     | 1         | 0.78%   |
| Lenovo V330-14ARR 81B1                   | 1         | 0.78%   |
| Lenovo ThinkPad X230 2325P38             | 1         | 0.78%   |
| Lenovo ThinkPad X1 Carbon 7th 20R10015US | 1         | 0.78%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS04300 | 1         | 0.78%   |
| Lenovo ThinkPad T61 765912G              | 1         | 0.78%   |
| Lenovo ThinkPad T470 20JNS01R01          | 1         | 0.78%   |
| Lenovo ThinkPad T470 20HDCTO1WW          | 1         | 0.78%   |
| Lenovo ThinkPad T450s 20BW000EUS         | 1         | 0.78%   |
| Lenovo ThinkPad T410 2518C3U             | 1         | 0.78%   |
| Lenovo ThinkPad T400 6474BV7             | 1         | 0.78%   |
| Lenovo ThinkPad P70 20ERCTO1WW           | 1         | 0.78%   |
| Lenovo ThinkPad L440 20ASS05K00          | 1         | 0.78%   |
| Lenovo ThinkPad Edge E530c 336669G       | 1         | 0.78%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 12        | 9.3%    |
| Dell Precision    | 5         | 3.88%   |
| HP Pavilion       | 4         | 3.1%    |
| ASUS PRIME        | 4         | 3.1%    |
| ASUS All          | 4         | 3.1%    |
| HP Laptop         | 3         | 2.33%   |
| Dell Latitude     | 3         | 2.33%   |
| ASUS ROG          | 3         | 2.33%   |
| Toshiba Satellite | 2         | 1.55%   |
| MSI Modern        | 2         | 1.55%   |
| Lenovo IdeaPad    | 2         | 1.55%   |
| HP EliteBook      | 2         | 1.55%   |
| Fujitsu LIFEBOOK  | 2         | 1.55%   |
| Dell PowerEdge    | 2         | 1.55%   |
| ASUS VivoBook     | 2         | 1.55%   |
| Acer Aspire       | 2         | 1.55%   |
| Unknown           | 2         | 1.55%   |
| TYAN S7012        | 1         | 0.78%   |
| Toshiba PORTEGE   | 1         | 0.78%   |
| System76 Oryx     | 1         | 0.78%   |
| Supermicro X9DA7  | 1         | 0.78%   |
| Sony SVE1713A1EW  | 1         | 0.78%   |
| Shuttle NC03U     | 1         | 0.78%   |
| Samsung 300E5M    | 1         | 0.78%   |
| Radxa ROCK        | 1         | 0.78%   |
| Notebook X170KM-G | 1         | 0.78%   |
| Notebook NL40     | 1         | 0.78%   |
| NetGear ReadyDATA | 1         | 0.78%   |
| MSI MS-7C52       | 1         | 0.78%   |
| MSI MS-7C02       | 1         | 0.78%   |
| MSI MS-7996       | 1         | 0.78%   |
| MSI MS-7788       | 1         | 0.78%   |
| MSI MS-7693       | 1         | 0.78%   |
| MSI MS-7529       | 1         | 0.78%   |
| MSI MS-7365       | 1         | 0.78%   |
| MSI GP76          | 1         | 0.78%   |
| MSI GL73          | 1         | 0.78%   |
| MSI GE76          | 1         | 0.78%   |
| Lenovo V330-14ARR | 1         | 0.78%   |
| Lenovo H50-05     | 1         | 0.78%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 16        | 12.4%   |
| 2012    | 12        | 9.3%    |
| 2020    | 11        | 8.53%   |
| 2017    | 11        | 8.53%   |
| 2018    | 10        | 7.75%   |
| 2015    | 10        | 7.75%   |
| 2021    | 9         | 6.98%   |
| 2014    | 8         | 6.2%    |
| 2016    | 7         | 5.43%   |
| 2011    | 7         | 5.43%   |
| 2008    | 7         | 5.43%   |
| 2007    | 5         | 3.88%   |
| 2022    | 4         | 3.1%    |
| 2013    | 4         | 3.1%    |
| 2009    | 4         | 3.1%    |
| 2010    | 2         | 1.55%   |
| Unknown | 2         | 1.55%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 61        | 47.29%  |
| Desktop        | 58        | 44.96%  |
| Mini pc        | 3         | 2.33%   |
| Server         | 3         | 2.33%   |
| System on chip | 2         | 1.55%   |
| All in one     | 2         | 1.55%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 129       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 126       | 97.67%  |
| Yes  | 3         | 2.33%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 28        | 21.54%  |
| 4.01-8.0    | 25        | 19.23%  |
| 8.01-16.0   | 22        | 16.92%  |
| 3.01-4.0    | 21        | 16.15%  |
| 32.01-64.0  | 14        | 10.77%  |
| 64.01-256.0 | 10        | 7.69%   |
| 24.01-32.0  | 5         | 3.85%   |
| 1.01-2.0    | 4         | 3.08%   |
| 0.51-1.0    | 1         | 0.77%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 38        | 27.94%  |
| 2.01-3.0    | 32        | 23.53%  |
| 4.01-8.0    | 23        | 16.91%  |
| 3.01-4.0    | 14        | 10.29%  |
| 0.51-1.0    | 12        | 8.82%   |
| 8.01-16.0   | 5         | 3.68%   |
| 0.01-0.5    | 5         | 3.68%   |
| 16.01-24.0  | 3         | 2.21%   |
| 24.01-32.0  | 2         | 1.47%   |
| 32.01-64.0  | 1         | 0.74%   |
| 64.01-256.0 | 1         | 0.74%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 62        | 46.62%  |
| 2      | 28        | 21.05%  |
| 3      | 16        | 12.03%  |
| 4      | 10        | 7.52%   |
| 6      | 5         | 3.76%   |
| 5      | 5         | 3.76%   |
| 0      | 3         | 2.26%   |
| 13     | 1         | 0.75%   |
| 9      | 1         | 0.75%   |
| 8      | 1         | 0.75%   |
| 7      | 1         | 0.75%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 76        | 58.46%  |
| Yes       | 54        | 41.54%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 119       | 92.25%  |
| No        | 10        | 7.75%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 88        | 68.22%  |
| No        | 41        | 31.78%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 80        | 62.02%  |
| No        | 49        | 37.98%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 29        | 22.48%  |
| UK           | 11        | 8.53%   |
| Brazil       | 8         | 6.2%    |
| Italy        | 7         | 5.43%   |
| Germany      | 7         | 5.43%   |
| Russia       | 6         | 4.65%   |
| Portugal     | 6         | 4.65%   |
| Kazakhstan   | 6         | 4.65%   |
| Canada       | 6         | 4.65%   |
| Japan        | 5         | 3.88%   |
| France       | 5         | 3.88%   |
| Sweden       | 4         | 3.1%    |
| India        | 4         | 3.1%    |
| Spain        | 3         | 2.33%   |
| South Africa | 3         | 2.33%   |
| Hong Kong    | 3         | 2.33%   |
| Greece       | 3         | 2.33%   |
| Serbia       | 2         | 1.55%   |
| Poland       | 2         | 1.55%   |
| Chile        | 2         | 1.55%   |
| Switzerland  | 1         | 0.78%   |
| Philippines  | 1         | 0.78%   |
| Netherlands  | 1         | 0.78%   |
| Mexico       | 1         | 0.78%   |
| Finland      | 1         | 0.78%   |
| Bulgaria     | 1         | 0.78%   |
| Australia    | 1         | 0.78%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Ust-Kamenogorsk        | 4         | 3.01%   |
| Lisbon                 | 4         | 3.01%   |
| Yekaterinburg          | 3         | 2.26%   |
| Paris                  | 3         | 2.26%   |
| Chania                 | 3         | 2.26%   |
| Warsaw                 | 2         | 1.5%    |
| Tsukuba                | 2         | 1.5%    |
| Tendo                  | 2         | 1.5%    |
| New Delhi              | 2         | 1.5%    |
| Milan                  | 2         | 1.5%    |
| McKinney               | 2         | 1.5%    |
| Karaganda              | 2         | 1.5%    |
| Carrollton             | 2         | 1.5%    |
| Cape Town              | 2         | 1.5%    |
| Belgrade               | 2         | 1.5%    |
| Barry                  | 2         | 1.5%    |
| Barrie                 | 2         | 1.5%    |
| Worpswede              | 1         | 0.75%   |
| Wokingham              | 1         | 0.75%   |
| Winter Springs         | 1         | 0.75%   |
| Winnipeg               | 1         | 0.75%   |
| Weilheim               | 1         | 0.75%   |
| Voskresensk            | 1         | 0.75%   |
| Visconde do Rio Branco | 1         | 0.75%   |
| Toronto                | 1         | 0.75%   |
| Tiffin                 | 1         | 0.75%   |
| Sun Prairie            | 1         | 0.75%   |
| Stockholm              | 1         | 0.75%   |
| St Petersburg          | 1         | 0.75%   |
| St Louis               | 1         | 0.75%   |
| Springfield            | 1         | 0.75%   |
| Southend-on-Sea        | 1         | 0.75%   |
| Skövde                | 1         | 0.75%   |
| Shrewsbury             | 1         | 0.75%   |
| Sham Shui Po           | 1         | 0.75%   |
| Senhora da Hora        | 1         | 0.75%   |
| Sao Paulo              | 1         | 0.75%   |
| Santiago               | 1         | 0.75%   |
| Santa Cruz do Sul      | 1         | 0.75%   |
| San Antonio            | 1         | 0.75%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 39        | 73     | 19.31%  |
| Samsung Electronics | 34        | 53     | 16.83%  |
| Seagate             | 31        | 60     | 15.35%  |
| Toshiba             | 16        | 26     | 7.92%   |
| Kingston            | 9         | 12     | 4.46%   |
| Hitachi             | 8         | 11     | 3.96%   |
| Crucial             | 7         | 8      | 3.47%   |
| Intel               | 6         | 7      | 2.97%   |
| SanDisk             | 5         | 6      | 2.48%   |
| HGST                | 5         | 5      | 2.48%   |
| Unknown             | 4         | 4      | 1.98%   |
| A-DATA Technology   | 4         | 4      | 1.98%   |
| SK hynix            | 3         | 3      | 1.49%   |
| Hewlett-Packard     | 3         | 4      | 1.49%   |
| Gigabyte Technology | 3         | 3      | 1.49%   |
| Patriot             | 2         | 3      | 0.99%   |
| Micron Technology   | 2         | 2      | 0.99%   |
| KIOXIA              | 2         | 2      | 0.99%   |
| China               | 2         | 3      | 0.99%   |
| Apple               | 2         | 3      | 0.99%   |
| ZHITAI              | 1         | 2      | 0.5%    |
| TO Exter            | 1         | 1      | 0.5%    |
| Team                | 1         | 1      | 0.5%    |
| PNY                 | 1         | 1      | 0.5%    |
| Plextor             | 1         | 1      | 0.5%    |
| Phison Electronics  | 1         | 1      | 0.5%    |
| Netac               | 1         | 1      | 0.5%    |
| Maxtor              | 1         | 1      | 0.5%    |
| JMicron Technology  | 1         | 1      | 0.5%    |
| Intenso             | 1         | 1      | 0.5%    |
| GOODRAM             | 1         | 1      | 0.5%    |
| Fujitsu             | 1         | 1      | 0.5%    |
| External            | 1         | 1      | 0.5%    |
| DUEX                | 1         | 1      | 0.5%    |
| Dogfish             | 1         | 1      | 0.5%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| WDC WD20EFRX-68EUZN0 2TB         | 3         | 1.2%    |
| WDC WD1003FZEX-00MK2A0 1TB       | 3         | 1.2%    |
| Samsung SSD 970 EVO 250GB        | 3         | 1.2%    |
| WDC WDS100T2B0A-00SM50 1TB SSD   | 2         | 0.8%    |
| WDC WD10SPZX-60Z10T0 1TB         | 2         | 0.8%    |
| WDC WD10EZEX-08WN4A0 1TB         | 2         | 0.8%    |
| WDC WD10EZEX-00RKKA0 1TB         | 2         | 0.8%    |
| Toshiba MQ04ABF100 1TB           | 2         | 0.8%    |
| Toshiba MQ01ABD100 1TB           | 2         | 0.8%    |
| Seagate ST500DM002-1BD142 500GB  | 2         | 0.8%    |
| Seagate ST4000VN008-2DR166 4TB   | 2         | 0.8%    |
| Seagate ST4000DM004-2CV104 4TB   | 2         | 0.8%    |
| Seagate ST31000524AS 1TB         | 2         | 0.8%    |
| Seagate ST2000DM008-2FR102 2TB   | 2         | 0.8%    |
| Seagate ST2000DM001-1CH164 2TB   | 2         | 0.8%    |
| Seagate ST1000DM010-2EP102 1TB   | 2         | 0.8%    |
| Seagate ST1000DM003-1SB102 1TB   | 2         | 0.8%    |
| Seagate ST1000DM003-1ER162 1TB   | 2         | 0.8%    |
| Samsung SSD 970 EVO Plus 1TB     | 2         | 0.8%    |
| Samsung SSD 860 QVO 2TB          | 2         | 0.8%    |
| Kingston SA400S37240G 240GB SSD  | 2         | 0.8%    |
| Crucial CT500MX500SSD1 500GB     | 2         | 0.8%    |
| ZHITAI SC001 Active 1TB SSD      | 1         | 0.4%    |
| ZHITAI PC005 Active 512GB        | 1         | 0.4%    |
| WDC WDS500G2B0B-00YS70 500GB SSD | 1         | 0.4%    |
| WDC WDS480G2G0A-00JH30 480GB SSD | 1         | 0.4%    |
| WDC WDS100T2B0C-00PXH0 1TB       | 1         | 0.4%    |
| WDC WDS100T2B0B-00YS70 1TB SSD   | 1         | 0.4%    |
| WDC WD7500BPVT-24HXZT3 752GB     | 1         | 0.4%    |
| WDC WD5003ABYX-18WERA0 500GB     | 1         | 0.4%    |
| WDC WD5000LPCX-60VHAT1 500GB     | 1         | 0.4%    |
| WDC WD5000BPVT-2 500GB           | 1         | 0.4%    |
| WDC WD5000BPKX-60HPJT0 500GB     | 1         | 0.4%    |
| WDC WD5000AAKX-22ERMA0 500GB     | 1         | 0.4%    |
| WDC WD5000AAKX-00ERMA0 500GB     | 1         | 0.4%    |
| WDC WD5000AAKS-00V0A0 500GB      | 1         | 0.4%    |
| WDC WD5000AAKS-00A7B2 500GB      | 1         | 0.4%    |
| WDC WD40EJRX-89T1XY0 4TB         | 1         | 0.4%    |
| WDC WD40EFRX-68WT0N0 4TB         | 1         | 0.4%    |
| WDC WD40EFRX-68N32N0 4TB         | 1         | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 34        | 64     | 34.34%  |
| Seagate             | 31        | 56     | 31.31%  |
| Toshiba             | 15        | 23     | 15.15%  |
| Hitachi             | 8         | 11     | 8.08%   |
| HGST                | 5         | 5      | 5.05%   |
| Samsung Electronics | 3         | 3      | 3.03%   |
| Maxtor              | 1         | 1      | 1.01%   |
| Hewlett-Packard     | 1         | 1      | 1.01%   |
| Fujitsu             | 1         | 1      | 1.01%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 17        | 27     | 26.56%  |
| Kingston            | 8         | 11     | 12.5%   |
| Crucial             | 6         | 7      | 9.38%   |
| WDC                 | 4         | 6      | 6.25%   |
| SanDisk             | 4         | 4      | 6.25%   |
| Patriot             | 2         | 3      | 3.13%   |
| Intel               | 2         | 3      | 3.13%   |
| China               | 2         | 3      | 3.13%   |
| Apple               | 2         | 3      | 3.13%   |
| A-DATA Technology   | 2         | 2      | 3.13%   |
| ZHITAI              | 1         | 1      | 1.56%   |
| Toshiba             | 1         | 1      | 1.56%   |
| TO Exter            | 1         | 1      | 1.56%   |
| Team                | 1         | 1      | 1.56%   |
| PNY                 | 1         | 1      | 1.56%   |
| Plextor             | 1         | 1      | 1.56%   |
| Netac               | 1         | 1      | 1.56%   |
| Micron Technology   | 1         | 1      | 1.56%   |
| JMicron Technology  | 1         | 1      | 1.56%   |
| Intenso             | 1         | 1      | 1.56%   |
| Hewlett-Packard     | 1         | 1      | 1.56%   |
| GOODRAM             | 1         | 1      | 1.56%   |
| Gigabyte Technology | 1         | 1      | 1.56%   |
| DUEX                | 1         | 1      | 1.56%   |
| Dogfish             | 1         | 1      | 1.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 72        | 165    | 40.68%  |
| SSD     | 59        | 84     | 33.33%  |
| NVMe    | 41        | 51     | 23.16%  |
| MMC     | 4         | 4      | 2.26%   |
| Unknown | 1         | 4      | 0.56%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 100       | 242    | 67.11%  |
| NVMe | 40        | 50     | 26.85%  |
| SAS  | 5         | 12     | 3.36%   |
| MMC  | 4         | 4      | 2.68%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 71        | 107    | 47.33%  |
| 0.51-1.0   | 42        | 75     | 28%     |
| 1.01-2.0   | 14        | 20     | 9.33%   |
| 3.01-4.0   | 10        | 23     | 6.67%   |
| 2.01-3.0   | 7         | 15     | 4.67%   |
| 4.01-10.0  | 4         | 4      | 2.67%   |
| 10.01-20.0 | 2         | 5      | 1.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 501-1000       | 30        | 22.73%  |
| 101-250        | 29        | 21.97%  |
| 251-500        | 21        | 15.91%  |
| Unknown        | 15        | 11.36%  |
| 1001-2000      | 14        | 10.61%  |
| 2001-3000      | 7         | 5.3%    |
| 1-20           | 7         | 5.3%    |
| More than 3000 | 5         | 3.79%   |
| 51-100         | 3         | 2.27%   |
| 21-50          | 1         | 0.76%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 25        | 18.52%  |
| 1-20           | 21        | 15.56%  |
| 21-50          | 20        | 14.81%  |
| 501-1000       | 17        | 12.59%  |
| Unknown        | 15        | 11.11%  |
| 251-500        | 14        | 10.37%  |
| 51-100         | 13        | 9.63%   |
| 1001-2000      | 7         | 5.19%   |
| More than 3000 | 3         | 2.22%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


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

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


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

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


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

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


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

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 101       | 214    | 64.74%  |
| Malfunc  | 33        | 50     | 21.15%  |
| Detected | 22        | 44     | 14.1%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 83        | 47.7%   |
| AMD                          | 29        | 16.67%  |
| Samsung Electronics          | 19        | 10.92%  |
| ASMedia Technology           | 6         | 3.45%   |
| Marvell Technology Group     | 5         | 2.87%   |
| SanDisk                      | 4         | 2.3%    |
| SK hynix                     | 3         | 1.72%   |
| Nvidia                       | 3         | 1.72%   |
| Broadcom / LSI               | 3         | 1.72%   |
| Realtek Semiconductor        | 2         | 1.15%   |
| Phison Electronics           | 2         | 1.15%   |
| LSI Logic / Symbios Logic    | 2         | 1.15%   |
| KIOXIA                       | 2         | 1.15%   |
| JMicron Technology           | 2         | 1.15%   |
| Yangtze Memory Technologies  | 1         | 0.57%   |
| Toshiba America Info Systems | 1         | 0.57%   |
| Silicon Image                | 1         | 0.57%   |
| Micron/Crucial Technology    | 1         | 0.57%   |
| Micron Technology            | 1         | 0.57%   |
| Kingston Technology Company  | 1         | 0.57%   |
| Biwin Storage Technology     | 1         | 0.57%   |
| Adaptec                      | 1         | 0.57%   |
| 3ware                        | 1         | 0.57%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 24        | 11.48%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 10        | 4.78%   |
| AMD 400 Series Chipset SATA Controller                                           | 8         | 3.83%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 7         | 3.35%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 6         | 2.87%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 6         | 2.87%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 5         | 2.39%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 5         | 2.39%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 4         | 1.91%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 4         | 1.91%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 3         | 1.44%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 1.44%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 3         | 1.44%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 3         | 1.44%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 3         | 1.44%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 3         | 1.44%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3         | 1.44%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 3         | 1.44%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 2         | 0.96%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 2         | 0.96%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 0.96%   |
| Realtek Realtek Non-Volatile memory controller                                   | 2         | 0.96%   |
| Nvidia MCP61 SATA Controller                                                     | 2         | 0.96%   |
| Nvidia MCP61 IDE                                                                 | 2         | 0.96%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 2         | 0.96%   |
| Intel SSD 600P Series                                                            | 2         | 0.96%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 2         | 0.96%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 2         | 0.96%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 2         | 0.96%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                              | 2         | 0.96%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 2         | 0.96%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 2         | 0.96%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                             | 2         | 0.96%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 0.96%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 2         | 0.96%   |
| Intel 631xESB/632xESB IDE Controller                                             | 2         | 0.96%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 2         | 0.96%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 0.96%   |
| Intel 4 Series Chipset PT IDER Controller                                        | 2         | 0.96%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 2         | 0.96%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 97        | 55.75%  |
| NVMe | 40        | 22.99%  |
| IDE  | 18        | 10.34%  |
| RAID | 12        | 6.9%    |
| SAS  | 4         | 2.3%    |
| SCSI | 3         | 1.72%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 96        | 74.42%  |
| AMD    | 31        | 24.03%  |
| ARM    | 2         | 1.55%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 3         | 2.31%   |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz            | 2         | 1.54%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 2         | 1.54%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1.54%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 1.54%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 1.54%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 1.54%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 2         | 1.54%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 2         | 1.54%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 2         | 1.54%   |
| Intel 12th Gen Core i7-12700H                 | 2         | 1.54%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 1.54%   |
| ARM Processor                                 | 2         | 1.54%   |
| AMD Ryzen 7 3800X 8-Core Processor            | 2         | 1.54%   |
| AMD Ryzen 5 3600 6-Core Processor             | 2         | 1.54%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 2         | 1.54%   |
| AMD FX-8350 Eight-Core Processor              | 2         | 1.54%   |
| Intel Xeon CPU X5680 @ 3.33GHz                | 1         | 0.77%   |
| Intel Xeon CPU X5355 @ 2.66GHz                | 1         | 0.77%   |
| Intel Xeon CPU X3450 @ 2.67GHz                | 1         | 0.77%   |
| Intel Xeon CPU E5-2697 v3 @ 2.60GHz           | 1         | 0.77%   |
| Intel Xeon CPU E5-2667 v2 @ 3.30GHz           | 1         | 0.77%   |
| Intel Xeon CPU E5-2660 v3 @ 2.60GHz           | 1         | 0.77%   |
| Intel Xeon CPU E5-2620 0 @ 2.00GHz            | 1         | 0.77%   |
| Intel Xeon CPU E5-2407 0 @ 2.20GHz            | 1         | 0.77%   |
| Intel Xeon CPU E5-1650 0 @ 3.20GHz            | 1         | 0.77%   |
| Intel Xeon CPU E3-1246 v3 @ 3.50GHz           | 1         | 0.77%   |
| Intel Xeon CPU 5160 @ 3.00GHz                 | 1         | 0.77%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz        | 1         | 0.77%   |
| Intel Pentium Dual CPU E2140 @ 1.60GHz        | 1         | 0.77%   |
| Intel Pentium CPU P6100 @ 2.00GHz             | 1         | 0.77%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.77%   |
| Intel Pentium CPU G640 @ 2.80GHz              | 1         | 0.77%   |
| Intel Pentium CPU G4560 @ 3.50GHz             | 1         | 0.77%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 1         | 0.77%   |
| Intel CPU Version                             | 1         | 0.77%   |
| Intel Core M-5Y51 CPU @ 1.10GHz               | 1         | 0.77%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 0.77%   |
| Intel Core i7-9700 CPU @ 3.00GHz              | 1         | 0.77%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 0.77%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Computers | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 23        | 17.69%  |
| Intel Core i7      | 21        | 16.15%  |
| Intel Xeon         | 13        | 10%     |
| Other              | 12        | 9.23%   |
| AMD Ryzen 5        | 9         | 6.92%   |
| Intel Core i3      | 7         | 5.38%   |
| Intel Core 2 Duo   | 6         | 4.62%   |
| Intel Pentium      | 5         | 3.85%   |
| AMD Ryzen 9        | 5         | 3.85%   |
| Intel Celeron      | 4         | 3.08%   |
| AMD Ryzen 7        | 4         | 3.08%   |
| AMD FX             | 4         | 3.08%   |
| Intel Core 2 Quad  | 2         | 1.54%   |
| Intel Atom         | 2         | 1.54%   |
| Intel Pentium Gold | 1         | 0.77%   |
| Intel Pentium Dual | 1         | 0.77%   |
| Intel Core M       | 1         | 0.77%   |
| Intel Core 2       | 1         | 0.77%   |
| AMD Ryzen Embedded | 1         | 0.77%   |
| AMD Ryzen 7 PRO    | 1         | 0.77%   |
| AMD GX             | 1         | 0.77%   |
| AMD EPYC           | 1         | 0.77%   |
| AMD Athlon 64 X2   | 1         | 0.77%   |
| AMD Athlon         | 1         | 0.77%   |
| AMD A8             | 1         | 0.77%   |
| AMD A4             | 1         | 0.77%   |
| AMD A10            | 1         | 0.77%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 45        | 34.62%  |
| 4      | 41        | 31.54%  |
| 8      | 15        | 11.54%  |
| 6      | 13        | 10%     |
| 16     | 4         | 3.08%   |
| 12     | 4         | 3.08%   |
| 14     | 3         | 2.31%   |
| 1      | 3         | 2.31%   |
| 10     | 1         | 0.77%   |
| 3      | 1         | 0.77%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 121       | 93.8%   |
| 2      | 8         | 6.2%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 95        | 73.64%  |
| 1      | 34        | 26.36%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 126       | 97.67%  |
| Unknown        | 2         | 1.55%   |
| 32-bit         | 1         | 0.78%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 27        | 20.93%  |
| 0x306a9    | 9         | 6.98%   |
| 0x306c3    | 5         | 3.88%   |
| 0x206d7    | 5         | 3.88%   |
| 0x306d4    | 4         | 3.1%    |
| 0x1067a    | 4         | 3.1%    |
| 0x806ec    | 3         | 2.33%   |
| 0x806ea    | 3         | 2.33%   |
| 0x806d1    | 3         | 2.33%   |
| 0x806c1    | 3         | 2.33%   |
| 0x406e3    | 3         | 2.33%   |
| 0x406c4    | 3         | 2.33%   |
| 0x206a7    | 3         | 2.33%   |
| 0x08701013 | 3         | 2.33%   |
| 0x08108109 | 3         | 2.33%   |
| 0x906ed    | 2         | 1.55%   |
| 0x906ea    | 2         | 1.55%   |
| 0x906a3    | 2         | 1.55%   |
| 0x6fd      | 2         | 1.55%   |
| 0x506e3    | 2         | 1.55%   |
| 0x306f2    | 2         | 1.55%   |
| 0x106c2    | 2         | 1.55%   |
| 0x0a50000c | 2         | 1.55%   |
| 0x0a201016 | 2         | 1.55%   |
| 0x08701021 | 2         | 1.55%   |
| 0x0810100b | 2         | 1.55%   |
| 0x06001119 | 2         | 1.55%   |
| 0x06000822 | 2         | 1.55%   |
| 0xa0671    | 1         | 0.78%   |
| 0xa0660    | 1         | 0.78%   |
| 0xa0653    | 1         | 0.78%   |
| 0xa0652    | 1         | 0.78%   |
| 0x906e9    | 1         | 0.78%   |
| 0x806e9    | 1         | 0.78%   |
| 0x706a1    | 1         | 0.78%   |
| 0x6fb      | 1         | 0.78%   |
| 0x6fa      | 1         | 0.78%   |
| 0x40651    | 1         | 0.78%   |
| 0x306e4    | 1         | 0.78%   |
| 0x206c2    | 1         | 0.78%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 18        | 13.95%  |
| Haswell          | 11        | 8.53%   |
| Zen 2            | 10        | 7.75%   |
| IvyBridge        | 10        | 7.75%   |
| SandyBridge      | 9         | 6.98%   |
| Core             | 8         | 6.2%    |
| Skylake          | 7         | 5.43%   |
| Piledriver       | 6         | 4.65%   |
| Penryn           | 5         | 3.88%   |
| Zen+             | 4         | 3.1%    |
| Zen 3            | 4         | 3.1%    |
| Zen              | 4         | 3.1%    |
| Westmere         | 4         | 3.1%    |
| Silvermont       | 4         | 3.1%    |
| Icelake          | 4         | 3.1%    |
| Broadwell        | 4         | 3.1%    |
| TigerLake        | 3         | 2.33%   |
| CometLake        | 3         | 2.33%   |
| Bonnell          | 2         | 1.55%   |
| Alderlake Hybrid | 2         | 1.55%   |
| Unknown          | 2         | 1.55%   |
| Puma             | 1         | 0.78%   |
| Nehalem          | 1         | 0.78%   |
| K8 Hammer        | 1         | 0.78%   |
| Jaguar           | 1         | 0.78%   |
| Goldmont plus    | 1         | 0.78%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 63        | 45%     |
| Nvidia                     | 39        | 27.86%  |
| AMD                        | 34        | 24.29%  |
| Matrox Electronics Systems | 4         | 2.86%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 3.42%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 5         | 3.42%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 2.74%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 2.74%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 2.74%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 2.74%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 3         | 2.05%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 3         | 2.05%   |
| Intel UHD Graphics 620                                                                   | 3         | 2.05%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 2.05%   |
| Intel HD Graphics 620                                                                    | 3         | 2.05%   |
| Intel HD Graphics 5500                                                                   | 3         | 2.05%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 2.05%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 2.05%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 2.05%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 1.37%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 1.37%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 1.37%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 2         | 1.37%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 2         | 1.37%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 1.37%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 1.37%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 1.37%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.37%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 1.37%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2         | 1.37%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.37%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 2         | 1.37%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 1.37%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 2         | 1.37%   |
| AMD Renoir                                                                               | 2         | 1.37%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 2         | 1.37%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 2         | 1.37%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2         | 1.37%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.68%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1         | 0.68%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 1         | 0.68%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 0.68%   |
| Nvidia GP107GL [Quadro P1000]                                                            | 1         | 0.68%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 1         | 0.68%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 52        | 40.31%  |
| 1 x AMD        | 31        | 24.03%  |
| 1 x Nvidia     | 24        | 18.6%   |
| Intel + Nvidia | 11        | 8.53%   |
| 1 x Matrox     | 4         | 3.1%    |
| Other          | 3         | 2.33%   |
| AMD + Nvidia   | 2         | 1.55%   |
| 2 x Nvidia     | 1         | 0.78%   |
| 2 x AMD        | 1         | 0.78%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 97        | 75.19%  |
| Proprietary | 22        | 17.05%  |
| Unknown     | 10        | 7.75%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 70        | 53.85%  |
| 0.51-1.0   | 14        | 10.77%  |
| 1.01-2.0   | 12        | 9.23%   |
| 3.01-4.0   | 11        | 8.46%   |
| 0.01-0.5   | 8         | 6.15%   |
| 7.01-8.0   | 7         | 5.38%   |
| 5.01-6.0   | 4         | 3.08%   |
| 8.01-16.0  | 3         | 2.31%   |
| 2.01-3.0   | 1         | 0.77%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Samsung Electronics  | 15        | 11.19%  |
| LG Display           | 13        | 9.7%    |
| BOE                  | 13        | 9.7%    |
| Dell                 | 11        | 8.21%   |
| Chimei Innolux       | 10        | 7.46%   |
| AU Optronics         | 10        | 7.46%   |
| Hewlett-Packard      | 9         | 6.72%   |
| BenQ                 | 6         | 4.48%   |
| Lenovo               | 5         | 3.73%   |
| Goldstar             | 5         | 3.73%   |
| Sharp                | 4         | 2.99%   |
| Ancor Communications | 4         | 2.99%   |
| Acer                 | 4         | 2.99%   |
| ViewSonic            | 2         | 1.49%   |
| Iiyama               | 2         | 1.49%   |
| ASUSTek Computer     | 2         | 1.49%   |
| Xiaomi               | 1         | 0.75%   |
| Wacom                | 1         | 0.75%   |
| Unknown              | 1         | 0.75%   |
| UGD                  | 1         | 0.75%   |
| Toshiba              | 1         | 0.75%   |
| Sony                 | 1         | 0.75%   |
| PANDA                | 1         | 0.75%   |
| Panasonic            | 1         | 0.75%   |
| ONN                  | 1         | 0.75%   |
| NEC Computers        | 1         | 0.75%   |
| JVC                  | 1         | 0.75%   |
| IOD                  | 1         | 0.75%   |
| Gigabyte Technology  | 1         | 0.75%   |
| GDH                  | 1         | 0.75%   |
| Eizo                 | 1         | 0.75%   |
| DPC                  | 1         | 0.75%   |
| Apple                | 1         | 0.75%   |
| AOC                  | 1         | 0.75%   |
| Unknown              | 1         | 0.75%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 2         | 1.46%   |
| LG Display LCD Monitor LGD0353 1366x768 345x194mm 15.6-inch           | 2         | 1.46%   |
| Lenovo LCD Monitor LEN4035 1280x800 303x190mm 14.1-inch               | 2         | 1.46%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 1.46%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch         | 2         | 1.46%   |
| Xiaomi Mi TV XMD009A 2880x1800 480x270mm 21.7-inch                    | 1         | 0.73%   |
| Wacom Cintiq 22HDT WAC1037 1920x1080 476x268mm 21.5-inch              | 1         | 0.73%   |
| ViewSonic LCD Monitor VX2276 Series 1920x1080                         | 1         | 0.73%   |
| ViewSonic LCD Monitor VA2448 SERIES 1920x1080                         | 1         | 0.73%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 1         | 0.73%   |
| UGD LCD Monitor UGD1302 1920x1080 290x160mm 13.0-inch                 | 1         | 0.73%   |
| Toshiba TV TSB0206 1920x1080 886x498mm 40.0-inch                      | 1         | 0.73%   |
| Sony TV SNY8102 1360x768                                              | 1         | 0.73%   |
| Sharp LQ173M1JW05 SHP14EC 1920x1080 382x215mm 17.3-inch               | 1         | 0.73%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 1         | 0.73%   |
| Sharp LQ125T1JW02 SHP142F 2560x1440 277x155mm 12.5-inch               | 1         | 0.73%   |
| Sharp LCD Monitor SHP14C4 1920x1080 344x194mm 15.5-inch               | 1         | 0.73%   |
| Samsung Electronics SyncMaster SAM0578 1920x1080 476x268mm 21.5-inch  | 1         | 0.73%   |
| Samsung Electronics SyncMaster SAM04DF 1360x768 410x230mm 18.5-inch   | 1         | 0.73%   |
| Samsung Electronics SyncMaster SAM0428 1680x1050 459x296mm 21.5-inch  | 1         | 0.73%   |
| Samsung Electronics SyncMaster SAM03F0 1680x1050 433x271mm 20.1-inch  | 1         | 0.73%   |
| Samsung Electronics SyncMaster SAM0248 1280x1024 380x300mm 19.1-inch  | 1         | 0.73%   |
| Samsung Electronics SyncMaster SAM01AD 1600x1200 408x306mm 20.1-inch  | 1         | 0.73%   |
| Samsung Electronics SMS27A650 SAM082D 1920x1080 598x336mm 27.0-inch   | 1         | 0.73%   |
| Samsung Electronics SMS19A100 SAM0867 1366x768 410x230mm 18.5-inch    | 1         | 0.73%   |
| Samsung Electronics SMB2430L SAM0644 1920x1080 521x293mm 23.5-inch    | 1         | 0.73%   |
| Samsung Electronics SM2333T SAM0736 1920x1080 477x268mm 21.5-inch     | 1         | 0.73%   |
| Samsung Electronics S24D390 SAM0B65 1920x1080 521x293mm 23.5-inch     | 1         | 0.73%   |
| Samsung Electronics S22D300 SAM0B3E 1920x1080 477x268mm 21.5-inch     | 1         | 0.73%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch  | 1         | 0.73%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 0.73%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch  | 1         | 0.73%   |
| Samsung Electronics LCD Monitor SDC416E 2880x1620 344x194mm 15.5-inch | 1         | 0.73%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch               | 1         | 0.73%   |
| Panasonic LCD Monitor MEI96A2 2880x1620 344x193mm 15.5-inch           | 1         | 0.73%   |
| ONN ONA18HO015 ONN0101 1920x1080 470x290mm 21.7-inch                  | 1         | 0.73%   |
| NEC Computers LCD2490WUXi NEC66CE 1920x1200 518x324mm 24.1-inch       | 1         | 0.73%   |
| LG Display LCD Monitor LGD0625 1920x1080 344x194mm 15.5-inch          | 1         | 0.73%   |
| LG Display LCD Monitor LGD0599 1920x1080 309x174mm 14.0-inch          | 1         | 0.73%   |
| LG Display LCD Monitor LGD0508 1366x768 309x174mm 14.0-inch           | 1         | 0.73%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 61        | 46.56%  |
| 1366x768 (WXGA)    | 24        | 18.32%  |
| 1280x1024 (SXGA)   | 7         | 5.34%   |
| 2560x1440 (QHD)    | 6         | 4.58%   |
| 1680x1050 (WSXGA+) | 6         | 4.58%   |
| 3840x2160 (4K)     | 5         | 3.82%   |
| 1920x1200 (WUXGA)  | 4         | 3.05%   |
| 1280x800 (WXGA)    | 4         | 3.05%   |
| 1600x900 (HD+)     | 3         | 2.29%   |
| 3440x1440          | 2         | 1.53%   |
| 1360x768           | 2         | 1.53%   |
| 3200x1080          | 1         | 0.76%   |
| 2880x1620          | 1         | 0.76%   |
| 2288x1287          | 1         | 0.76%   |
| 2256x1504          | 1         | 0.76%   |
| 1920x540           | 1         | 0.76%   |
| 1600x1200          | 1         | 0.76%   |
| Unknown            | 1         | 0.76%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 31        | 23.13%  |
| 21      | 13        | 9.7%    |
| 24      | 12        | 8.96%   |
| 14      | 12        | 8.96%   |
| 27      | 11        | 8.21%   |
| 17      | 9         | 6.72%   |
| 13      | 9         | 6.72%   |
| 23      | 8         | 5.97%   |
| Unknown | 5         | 3.73%   |
| 20      | 4         | 2.99%   |
| 22      | 3         | 2.24%   |
| 19      | 3         | 2.24%   |
| 18      | 3         | 2.24%   |
| 12      | 3         | 2.24%   |
| 16      | 2         | 1.49%   |
| 142     | 1         | 0.75%   |
| 74      | 1         | 0.75%   |
| 72      | 1         | 0.75%   |
| 52      | 1         | 0.75%   |
| 34      | 1         | 0.75%   |
| 32      | 1         | 0.75%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 52        | 39.1%   |
| 501-600        | 29        | 21.8%   |
| 401-500        | 23        | 17.29%  |
| 351-400        | 11        | 8.27%   |
| 201-300        | 6         | 4.51%   |
| Unknown        | 5         | 3.76%   |
| 701-800        | 2         | 1.5%    |
| 1501-2000      | 2         | 1.5%    |
| More than 2000 | 1         | 0.75%   |
| 601-700        | 1         | 0.75%   |
| 1001-1500      | 1         | 0.75%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 90        | 73.17%  |
| 16/10   | 15        | 12.2%   |
| 5/4     | 5         | 4.07%   |
| Unknown | 4         | 3.25%   |
| 3/2     | 3         | 2.44%   |
| 6/5     | 2         | 1.63%   |
| 4/3     | 1         | 0.81%   |
| 32/9    | 1         | 0.81%   |
| 21/9    | 1         | 0.81%   |
| 1.00    | 1         | 0.81%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 33        | 25%     |
| 201-250        | 26        | 19.7%   |
| 81-90          | 19        | 14.39%  |
| 301-350        | 11        | 8.33%   |
| 151-200        | 9         | 6.82%   |
| 141-150        | 7         | 5.3%    |
| 251-300        | 6         | 4.55%   |
| 121-130        | 5         | 3.79%   |
| Unknown        | 5         | 3.79%   |
| More than 1000 | 4         | 3.03%   |
| 61-70          | 3         | 2.27%   |
| 71-80          | 2         | 1.52%   |
| 351-500        | 2         | 1.52%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 47        | 35.34%  |
| 101-120       | 37        | 27.82%  |
| 121-160       | 33        | 24.81%  |
| Unknown       | 5         | 3.76%   |
| 1-50          | 4         | 3.01%   |
| 161-240       | 4         | 3.01%   |
| More than 240 | 3         | 2.26%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 99        | 76.74%  |
| 2     | 15        | 11.63%  |
| 0     | 11        | 8.53%   |
| 3     | 3         | 2.33%   |
| 4     | 1         | 0.78%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 77        | 40.1%   |
| Realtek Semiconductor    | 65        | 33.85%  |
| Qualcomm Atheros         | 13        | 6.77%   |
| Broadcom                 | 10        | 5.21%   |
| Ralink Technology        | 4         | 2.08%   |
| TP-Link                  | 3         | 1.56%   |
| Broadcom Limited         | 3         | 1.56%   |
| Nvidia                   | 2         | 1.04%   |
| MediaTek                 | 2         | 1.04%   |
| ASIX Electronics         | 2         | 1.04%   |
| VIA Technologies         | 1         | 0.52%   |
| Sitecom Europe           | 1         | 0.52%   |
| Sierra Wireless          | 1         | 0.52%   |
| Ralink                   | 1         | 0.52%   |
| Qualcomm                 | 1         | 0.52%   |
| Micro Star International | 1         | 0.52%   |
| Mellanox Technologies    | 1         | 0.52%   |
| Marvell Technology Group | 1         | 0.52%   |
| Hewlett-Packard          | 1         | 0.52%   |
| Dell                     | 1         | 0.52%   |
| Chelsio Communications   | 1         | 0.52%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 45        | 19.15%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 3.4%    |
| Intel I211 Gigabit Network Connection                             | 7         | 2.98%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 2.55%   |
| Intel Wi-Fi 6 AX200                                               | 5         | 2.13%   |
| Intel 82574L Gigabit Network Connection                           | 5         | 2.13%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.7%    |
| Ralink MT7601U Wireless Adapter                                   | 4         | 1.7%    |
| Intel Wireless-AC 9260                                            | 4         | 1.7%    |
| Intel Wireless 8265 / 8275                                        | 4         | 1.7%    |
| Intel Wireless 7260                                               | 4         | 1.7%    |
| Intel Ethernet Connection (2) I218-V                              | 4         | 1.7%    |
| Realtek RTL8188EE Wireless Network Adapter                        | 3         | 1.28%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 1.28%   |
| Intel Wireless 8260                                               | 3         | 1.28%   |
| Intel Wireless 7265                                               | 3         | 1.28%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 3         | 1.28%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 1.28%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 1.28%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 2         | 0.85%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 0.85%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 0.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 0.85%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.85%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 2         | 0.85%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 0.85%   |
| Intel Wireless 3160                                               | 2         | 0.85%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 0.85%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 0.85%   |
| Intel I350 Gigabit Network Connection                             | 2         | 0.85%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 0.85%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.85%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 0.85%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.85%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.85%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 0.85%   |
| Intel Centrino Ultimate-N 6300                                    | 2         | 0.85%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 0.85%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 0.85%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 50        | 54.35%  |
| Realtek Semiconductor    | 14        | 15.22%  |
| Qualcomm Atheros         | 10        | 10.87%  |
| Ralink Technology        | 4         | 4.35%   |
| TP-Link                  | 3         | 3.26%   |
| Broadcom                 | 3         | 3.26%   |
| MediaTek                 | 2         | 2.17%   |
| Sitecom Europe           | 1         | 1.09%   |
| Sierra Wireless          | 1         | 1.09%   |
| Ralink                   | 1         | 1.09%   |
| Micro Star International | 1         | 1.09%   |
| Dell                     | 1         | 1.09%   |
| Broadcom Limited         | 1         | 1.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                                   | 5         | 5.38%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 4         | 4.3%    |
| Ralink MT7601U Wireless Adapter                                                       | 4         | 4.3%    |
| Intel Wireless-AC 9260                                                                | 4         | 4.3%    |
| Intel Wireless 8265 / 8275                                                            | 4         | 4.3%    |
| Intel Wireless 7260                                                                   | 4         | 4.3%    |
| Realtek RTL8188EE Wireless Network Adapter                                            | 3         | 3.23%   |
| Intel Wireless 8260                                                                   | 3         | 3.23%   |
| Intel Wireless 7265                                                                   | 3         | 3.23%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 3         | 3.23%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 3         | 3.23%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 3         | 3.23%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                               | 2         | 2.15%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 2         | 2.15%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                      | 2         | 2.15%   |
| Intel Wireless 3160                                                                   | 2         | 2.15%   |
| Intel Wi-Fi 6 AX201                                                                   | 2         | 2.15%   |
| Intel Tiger Lake PCH CNVi WiFi                                                        | 2         | 2.15%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 2         | 2.15%   |
| Intel Centrino Ultimate-N 6300                                                        | 2         | 2.15%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                           | 1         | 1.08%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                                                 | 1         | 1.08%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                            | 1         | 1.08%   |
| Sitecom Europe WL-113 rev 2 Wireless Network USB Adapter                              | 1         | 1.08%   |
| Sierra Wireless EM7305                                                                | 1         | 1.08%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                    | 1         | 1.08%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 1         | 1.08%   |
| Realtek RTL8723DE Wireless Network Adapter                                            | 1         | 1.08%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                       | 1         | 1.08%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                           | 1         | 1.08%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1         | 1.08%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                             | 1         | 1.08%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 1         | 1.08%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                        | 1         | 1.08%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 1         | 1.08%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                      | 1         | 1.08%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 1.08%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 1         | 1.08%   |
| Micro Star International MS-3871 802.11bgn Wireless Module [Ralink RT8070]            | 1         | 1.08%   |
| MediaTek WLAN controller                                                              | 1         | 1.08%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 60        | 45.45%  |
| Intel                    | 47        | 35.61%  |
| Broadcom                 | 8         | 6.06%   |
| Qualcomm Atheros         | 6         | 4.55%   |
| Nvidia                   | 2         | 1.52%   |
| Broadcom Limited         | 2         | 1.52%   |
| ASIX Electronics         | 2         | 1.52%   |
| VIA Technologies         | 1         | 0.76%   |
| Qualcomm                 | 1         | 0.76%   |
| Mellanox Technologies    | 1         | 0.76%   |
| Marvell Technology Group | 1         | 0.76%   |
| Chelsio Communications   | 1         | 0.76%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 45        | 31.91%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 5.67%   |
| Intel I211 Gigabit Network Connection                             | 7         | 4.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 4.26%   |
| Intel 82574L Gigabit Network Connection                           | 5         | 3.55%   |
| Intel Ethernet Connection (2) I218-V                              | 4         | 2.84%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 2.13%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1.42%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 1.42%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 1.42%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 1.42%   |
| Intel I350 Gigabit Network Connection                             | 2         | 1.42%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.42%   |
| Intel Ethernet Connection I217-V                                  | 2         | 1.42%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 1.42%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.42%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 1.42%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 1.42%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 1.42%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 1.42%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 2         | 1.42%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 2         | 1.42%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1         | 0.71%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1         | 0.71%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.71%   |
| Qualcomm MegaFon M150-4                                           | 1         | 0.71%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.71%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.71%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.71%   |
| Nvidia MCP61 Ethernet                                             | 1         | 0.71%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]             | 1         | 0.71%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.71%   |
| Intel Ethernet Controller I225-V                                  | 1         | 0.71%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.71%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.71%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 0.71%   |
| Intel Ethernet Connection (2) I218-LM                             | 1         | 0.71%   |
| Intel Ethernet Connection (12) I219-V                             | 1         | 0.71%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.71%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 1         | 0.71%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 119       | 57.21%  |
| WiFi     | 88        | 42.31%  |
| Modem    | 1         | 0.48%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 68        | 53.97%  |
| WiFi     | 58        | 46.03%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 72        | 54.96%  |
| 1     | 42        | 32.06%  |
| 3     | 6         | 4.58%   |
| 4     | 5         | 3.82%   |
| 0     | 5         | 3.82%   |
| 5     | 1         | 0.76%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 116       | 89.23%  |
| Yes  | 14        | 10.77%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 43        | 53.75%  |
| Cambridge Silicon Radio         | 12        | 15%     |
| Realtek Semiconductor           | 7         | 8.75%   |
| Broadcom                        | 6         | 7.5%    |
| Qualcomm Atheros Communications | 3         | 3.75%   |
| Micro Star International        | 2         | 2.5%    |
| IMC Networks                    | 2         | 2.5%    |
| Apple                           | 2         | 2.5%    |
| TP-Link                         | 1         | 1.25%   |
| Toshiba                         | 1         | 1.25%   |
| Foxconn / Hon Hai               | 1         | 1.25%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 18        | 22.5%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 12        | 15%     |
| Intel AX201 Bluetooth                               | 6         | 7.5%    |
| Intel AX200 Bluetooth                               | 5         | 6.25%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 5%      |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 4         | 5%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 5%      |
| Realtek Bluetooth Radio                             | 3         | 3.75%   |
| Intel AX210 Bluetooth                               | 3         | 3.75%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 2.5%    |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 2.5%    |
| IMC Networks Wireless_Device                        | 2         | 2.5%    |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2         | 2.5%    |
| TP-Link UB500 Adapter                               | 1         | 1.25%   |
| Toshiba Askey Bluetooth Module                      | 1         | 1.25%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 1.25%   |
| Micro Star International Bluetooth Dongle           | 1         | 1.25%   |
| Micro Star International Bluetooth Device           | 1         | 1.25%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.25%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 1.25%   |
| Broadcom HP Portable SoftSailing                    | 1         | 1.25%   |
| Broadcom BCM20702A0                                 | 1         | 1.25%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.25%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 1         | 1.25%   |
| Apple Bluetooth USB Host Controller                 | 1         | 1.25%   |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 1         | 1.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 87        | 49.43%  |
| AMD                    | 37        | 21.02%  |
| Nvidia                 | 33        | 18.75%  |
| Creative Labs          | 7         | 3.98%   |
| C-Media Electronics    | 4         | 2.27%   |
| Texas Instruments      | 2         | 1.14%   |
| VIA Technologies       | 1         | 0.57%   |
| RME                    | 1         | 0.57%   |
| M-Audio                | 1         | 0.57%   |
| Generalplus Technology | 1         | 0.57%   |
| EGO SYStems            | 1         | 0.57%   |
| ASUSTek Computer       | 1         | 0.57%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 11        | 5.19%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 10        | 4.72%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 9         | 4.25%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 8         | 3.77%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 7         | 3.3%    |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 6         | 2.83%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 2.36%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 2.36%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 5         | 2.36%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 4         | 1.89%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 1.89%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 4         | 1.89%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 1.89%   |
| Intel Broadwell-U Audio Controller                                                                | 4         | 1.89%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 1.89%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 1.89%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 1.89%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 4         | 1.89%   |
| AMD FCH Azalia Controller                                                                         | 4         | 1.89%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1.42%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 1.42%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 1.42%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 3         | 1.42%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 1.42%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 3         | 1.42%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 1.42%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 1.42%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 1.42%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.42%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus]   | 3         | 1.42%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 1.42%   |
| AMD Navi 10 HDMI Audio                                                                            | 3         | 1.42%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 3         | 1.42%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 2         | 0.94%   |
| Nvidia MCP61 High Definition Audio                                                                | 2         | 0.94%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 2         | 0.94%   |
| Nvidia Audio device                                                                               | 2         | 0.94%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 0.94%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 0.94%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 0.94%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 27        | 20.3%   |
| Kingston            | 24        | 18.05%  |
| Samsung Electronics | 19        | 14.29%  |
| Crucial             | 11        | 8.27%   |
| Corsair             | 11        | 8.27%   |
| Unknown             | 8         | 6.02%   |
| Micron Technology   | 7         | 5.26%   |
| Team                | 4         | 3.01%   |
| Transcend           | 2         | 1.5%    |
| Ramaxel Technology  | 2         | 1.5%    |
| A-DATA Technology   | 2         | 1.5%    |
| Unknown             | 2         | 1.5%    |
| Strontium           | 1         | 0.75%   |
| Smart               | 1         | 0.75%   |
| Silicon Power       | 1         | 0.75%   |
| Neo Forza           | 1         | 0.75%   |
| Nanya Technology    | 1         | 0.75%   |
| HPE                 | 1         | 0.75%   |
| Goodram             | 1         | 0.75%   |
| GLOWAY              | 1         | 0.75%   |
| G.Skill             | 1         | 0.75%   |
| Essencore Limited   | 1         | 0.75%   |
| Elpida              | 1         | 0.75%   |
| Avant               | 1         | 0.75%   |
| AMD                 | 1         | 0.75%   |
| A Force             | 1         | 0.75%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB DIMM SDRAM                        | 2         | 1.37%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s         | 2         | 1.37%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 2         | 1.37%   |
| SK hynix RAM HMA851S6AFR6N-UH 2GB SODIMM LPDDR4 2667MT/s    | 2         | 1.37%   |
| Unknown                                                     | 2         | 1.37%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                   | 1         | 0.68%   |
| Unknown RAM Module 4096MB DIMM DDR3 65535MT/s               | 1         | 0.68%   |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s                  | 1         | 0.68%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                      | 1         | 0.68%   |
| Unknown RAM Module 1024MB SODIMM SDRAM                      | 1         | 0.68%   |
| Unknown RAM Module 1024MB SODIMM DDR2 533MT/s               | 1         | 0.68%   |
| Unknown RAM Module 1024MB DIMM DDR 800MT/s                  | 1         | 0.68%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                      | 1         | 0.68%   |
| Transcend RAM TS256MLQ72V6U 2GB DIMM DDR2 667MT/s           | 1         | 0.68%   |
| Transcend RAM JM1600KLN-8GK 4096MB DIMM DDR3 1600MT/s       | 1         | 0.68%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3733MT/s          | 1         | 0.68%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3600MT/s         | 1         | 0.68%   |
| Strontium RAM SRT4G86U1-P9H 4096MB DIMM DDR3 1333MT/s       | 1         | 0.68%   |
| Smart RAM SH5641G8FJ8NWRNSQG 8GB SODIMM DDR3 1600MT/s       | 1         | 0.68%   |
| SK hynix RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s     | 1         | 0.68%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s             | 1         | 0.68%   |
| SK hynix RAM HYMP512F72CP8N3-Y5 1024MB FB-DIMM DDR2 667MT/s | 1         | 0.68%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s       | 1         | 0.68%   |
| SK hynix RAM HMT41GV7BMR4A-H9 16GB DIMM 1333MT/s            | 1         | 0.68%   |
| SK hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 2000MT/s        | 1         | 0.68%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s      | 1         | 0.68%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s      | 1         | 0.68%   |
| SK hynix RAM HMT351U6BFR8C-H9 4096MB DIMM DDR3 1333MT/s     | 1         | 0.68%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 0.68%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s      | 1         | 0.68%   |
| SK hynix RAM HMT351R7CFR8A-H9 4GB DIMM DDR3 1333MT/s        | 1         | 0.68%   |
| SK hynix RAM HMT31GR7EFR4A 8192MB DIMM DDR3 1600MT/s        | 1         | 0.68%   |
| SK hynix RAM HMT31GR7BFR4A-H9 16GB DIMM 1333MT/s            | 1         | 0.68%   |
| SK hynix RAM HMT125R7BFR8C-H9 2GB DIMM 1333MT/s             | 1         | 0.68%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s      | 1         | 0.68%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s      | 1         | 0.68%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s      | 1         | 0.68%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8192MB SODIMM DDR4 3200MT/s   | 1         | 0.68%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s      | 1         | 0.68%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s      | 1         | 0.68%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 51        | 44.35%  |
| DDR3    | 44        | 38.26%  |
| DDR2    | 6         | 5.22%   |
| SDRAM   | 4         | 3.48%   |
| LPDDR3  | 3         | 2.61%   |
| LPDDR4  | 2         | 1.74%   |
| Unknown | 2         | 1.74%   |
| LPDDR5  | 1         | 0.87%   |
| DDR5    | 1         | 0.87%   |
| DDR     | 1         | 0.87%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 55        | 47.83%  |
| DIMM         | 55        | 47.83%  |
| Row Of Chips | 3         | 2.61%   |
| RIMM         | 1         | 0.87%   |
| FB-DIMM      | 1         | 0.87%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 48        | 37.8%   |
| 4096  | 40        | 31.5%   |
| 16384 | 15        | 11.81%  |
| 2048  | 11        | 8.66%   |
| 32768 | 7         | 5.51%   |
| 1024  | 6         | 4.72%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 31        | 24.8%   |
| 3200    | 15        | 12%     |
| 2667    | 14        | 11.2%   |
| 2400    | 11        | 8.8%    |
| 1333    | 8         | 6.4%    |
| 3600    | 6         | 4.8%    |
| 2133    | 5         | 4%      |
| 667     | 5         | 4%      |
| 3800    | 3         | 2.4%    |
| 1867    | 3         | 2.4%    |
| Unknown | 3         | 2.4%    |
| 2666    | 2         | 1.6%    |
| 1866    | 2         | 1.6%    |
| 975     | 2         | 1.6%    |
| 65535   | 1         | 0.8%    |
| 6400    | 1         | 0.8%    |
| 4800    | 1         | 0.8%    |
| 4199    | 1         | 0.8%    |
| 3733    | 1         | 0.8%    |
| 2933    | 1         | 0.8%    |
| 2800    | 1         | 0.8%    |
| 2472    | 1         | 0.8%    |
| 2187    | 1         | 0.8%    |
| 2000    | 1         | 0.8%    |
| 1334    | 1         | 0.8%    |
| 1066    | 1         | 0.8%    |
| 800     | 1         | 0.8%    |
| 701     | 1         | 0.8%    |
| 533     | 1         | 0.8%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


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

![Printer Model](./images/pie_chart/printer_model.svg)


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

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Seiko Epson     | 1         | 50%     |
| Hewlett-Packard | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO] | 1         | 50%     |
| HP ScanJet 5590                               | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 18        | 25.71%  |
| Logitech                               | 10        | 14.29%  |
| Acer                                   | 8         | 11.43%  |
| Microdia                               | 5         | 7.14%   |
| Realtek Semiconductor                  | 4         | 5.71%   |
| IMC Networks                           | 4         | 5.71%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 5.71%   |
| Lite-On Technology                     | 3         | 4.29%   |
| Sunplus Innovation Technology          | 2         | 2.86%   |
| Quanta                                 | 2         | 2.86%   |
| Luxvisions Innotech Limited            | 2         | 2.86%   |
| Syntek                                 | 1         | 1.43%   |
| Sonix Technology                       | 1         | 1.43%   |
| Silicon Motion                         | 1         | 1.43%   |
| Samsung Electronics                    | 1         | 1.43%   |
| Motorola PCS                           | 1         | 1.43%   |
| Microsoft                              | 1         | 1.43%   |
| Lenovo                                 | 1         | 1.43%   |
| Apple                                  | 1         | 1.43%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 4         | 5.71%   |
| Acer HD Webcam                                       | 3         | 4.29%   |
| Acer BisonCam,NB Pro                                 | 3         | 4.29%   |
| Realtek USB Camera                                   | 2         | 2.86%   |
| Quanta HP Webcam                                     | 2         | 2.86%   |
| Logitech Webcam C270                                 | 2         | 2.86%   |
| Chicony FJ Camera                                    | 2         | 2.86%   |
| Acer Integrated Camera                               | 2         | 2.86%   |
| Syntek USB2.0 Camera                                 | 1         | 1.43%   |
| Sunplus Laptop_Integrated_Webcam_FHD                 | 1         | 1.43%   |
| Sunplus Integrated_Webcam_HD                         | 1         | 1.43%   |
| Sonix USB2.0 FHD UVC WebCam                          | 1         | 1.43%   |
| Silicon Motion Web Camera                            | 1         | 1.43%   |
| Samsung Galaxy A5 (MTP)                              | 1         | 1.43%   |
| Realtek Laptop Camera                                | 1         | 1.43%   |
| Realtek EasyCamera                                   | 1         | 1.43%   |
| Motorola PCS XT1033 [Moto G], PTP mode               | 1         | 1.43%   |
| Microsoft LifeCam HD-3000                            | 1         | 1.43%   |
| Microdia Laptop_Integrated_Webcam_2M                 | 1         | 1.43%   |
| Microdia Integrated_Webcam_HD                        | 1         | 1.43%   |
| Microdia Integrated Webcam                           | 1         | 1.43%   |
| Microdia Dell Integrated HD Webcam                   | 1         | 1.43%   |
| Microdia Camera                                      | 1         | 1.43%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 1.43%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 1         | 1.43%   |
| Logitech Webcam C310                                 | 1         | 1.43%   |
| Logitech Webcam C300                                 | 1         | 1.43%   |
| Logitech Webcam C170                                 | 1         | 1.43%   |
| Logitech QuickCam Pro 9000                           | 1         | 1.43%   |
| Logitech HD Webcam C525                              | 1         | 1.43%   |
| Logitech HD Pro Webcam C920                          | 1         | 1.43%   |
| Logitech C922 Pro Stream Webcam                      | 1         | 1.43%   |
| Logitech C920 PRO HD Webcam                          | 1         | 1.43%   |
| Lite-On TOSHIBA Web Camera - FHD                     | 1         | 1.43%   |
| Lite-On Integrated Camera                            | 1         | 1.43%   |
| Lite-On HP TrueVision HD Camera                      | 1         | 1.43%   |
| Lenovo Integrated Webcam [R5U877]                    | 1         | 1.43%   |
| IMC Networks UVC VGA Webcam                          | 1         | 1.43%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 1         | 1.43%   |
| IMC Networks Lenovo EasyCamera                       | 1         | 1.43%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 7         | 46.67%  |
| Synaptics                          | 3         | 20%     |
| STMicroelectronics                 | 2         | 13.33%  |
| Realtek USB2.0 Finger Print Bridge | 1         | 6.67%   |
| LighTuning Technology              | 1         | 6.67%   |
| Elan Microelectronics              | 1         | 6.67%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI                                 | 2         | 13.33%  |
| STMicroelectronics Fingerprint Reader                           | 2         | 13.33%  |
| Unknown                                                         | 2         | 13.33%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor               | 1         | 6.67%   |
| Validity Sensors VFS495 Fingerprint Reader                      | 1         | 6.67%   |
| Validity Sensors VFS300 Fingerprint Reader                      | 1         | 6.67%   |
| Validity Sensors VFS Fingerprint sensor                         | 1         | 6.67%   |
| Validity Sensors VFS 5011 fingerprint sensor                    | 1         | 6.67%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 1         | 6.67%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 1         | 6.67%   |
| LighTuning EgisTec Touch Fingerprint Sensor                     | 1         | 6.67%   |
| Elan ELAN:Fingerprint                                           | 1         | 6.67%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


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

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


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

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 81        | 61.36%  |
| 1     | 28        | 21.21%  |
| 2     | 13        | 9.85%   |
| 3     | 6         | 4.55%   |
| 4     | 4         | 3.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 15        | 18.29%  |
| Fingerprint reader       | 14        | 17.07%  |
| Sound                    | 11        | 13.41%  |
| Net/wireless             | 8         | 9.76%   |
| Communication controller | 8         | 9.76%   |
| Chipcard                 | 8         | 9.76%   |
| Card reader              | 4         | 4.88%   |
| Unassigned class         | 3         | 3.66%   |
| Bluetooth                | 3         | 3.66%   |
| Net/ethernet             | 2         | 2.44%   |
| Multimedia controller    | 2         | 2.44%   |
| Storage/ata              | 1         | 1.22%   |
| Storage                  | 1         | 1.22%   |
| Firewire controller      | 1         | 1.22%   |
| Camera                   | 1         | 1.22%   |

