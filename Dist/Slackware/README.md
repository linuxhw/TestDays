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

Total: 186

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Acer          | Swift SF114-34              | Notebook    | [ec48f7a207](https://linux-hardware.org/?probe=ec48f7a207) | May 28, 2023 |
| MSI           | X99A GAMING 7               | Desktop     | [ec94d173a7](https://linux-hardware.org/?probe=ec94d173a7) | May 23, 2023 |
| Microsoft     | Surface Go 3                | Tablet      | [90b4889055](https://linux-hardware.org/?probe=90b4889055) | May 21, 2023 |
| ASRock        | N68-S3 FX                   | Desktop     | [0ed94fe810](https://linux-hardware.org/?probe=0ed94fe810) | May 10, 2023 |
| HEDYCOMPUT... | IH81MF-Q3                   | Desktop     | [3444236ed4](https://linux-hardware.org/?probe=3444236ed4) | Apr 30, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [941aa94750](https://linux-hardware.org/?probe=941aa94750) | Apr 13, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [7f052050d9](https://linux-hardware.org/?probe=7f052050d9) | Apr 10, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [70314c0c37](https://linux-hardware.org/?probe=70314c0c37) | Mar 23, 2023 |
| Dell          | 0MY171 A00                  | Desktop     | [47fd974afd](https://linux-hardware.org/?probe=47fd974afd) | Mar 20, 2023 |
| Valve         | Jupiter                     | Notebook    | [e9844f7162](https://linux-hardware.org/?probe=e9844f7162) | Mar 13, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [053498458e](https://linux-hardware.org/?probe=053498458e) | Mar 03, 2023 |
| Dell          | 0MY171 A00                  | Desktop     | [795f707b1a](https://linux-hardware.org/?probe=795f707b1a) | Feb 25, 2023 |
| Dell          | 04YP6J A03                  | Desktop     | [696cc9b57a](https://linux-hardware.org/?probe=696cc9b57a) | Feb 19, 2023 |
| HP            | ENVY Laptop 17-cr0xxx       | Notebook    | [fde666c0ea](https://linux-hardware.org/?probe=fde666c0ea) | Feb 17, 2023 |
| HP            | ENVY Laptop 17-cr0xxx       | Notebook    | [5ce5272a93](https://linux-hardware.org/?probe=5ce5272a93) | Feb 17, 2023 |
| ASRock        | 990FX Extreme4              | Desktop     | [7ce91f2b1e](https://linux-hardware.org/?probe=7ce91f2b1e) | Feb 16, 2023 |
| Lenovo        | ThinkPad X140e 20BMS03E0... | Notebook    | [fb4c4aebf9](https://linux-hardware.org/?probe=fb4c4aebf9) | Jan 31, 2023 |
| Lenovo        | ThinkPad T470p 20J60018M... | Notebook    | [9324b897c3](https://linux-hardware.org/?probe=9324b897c3) | Jan 19, 2023 |
| ASRock        | N68-S UCC                   | Desktop     | [cb4c89a390](https://linux-hardware.org/?probe=cb4c89a390) | Jan 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | Notebook    | [1b50127412](https://linux-hardware.org/?probe=1b50127412) | Jan 14, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [9edc837033](https://linux-hardware.org/?probe=9edc837033) | Jan 13, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [1c9dc6792e](https://linux-hardware.org/?probe=1c9dc6792e) | Jan 13, 2023 |
| HP            | OMEN by Laptop 17-ck0xxx    | Notebook    | [9655429e71](https://linux-hardware.org/?probe=9655429e71) | Jan 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | Notebook    | [4900ec9966](https://linux-hardware.org/?probe=4900ec9966) | Jan 05, 2023 |
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

![OS](./All/images/pie_chart/os_name.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| Slackware 15.0  | 81        | 54%     |
| Slackware 14.2  | 63        | 42%     |
| Slackware 14.2+ | 6         | 4%      |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| Slackware | 148       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.15.19           | 19        | 11.95%  |
| 4.19.80           | 8         | 5.03%   |
| 5.19.17           | 6         | 3.77%   |
| 5.10.28-Unraid    | 6         | 3.77%   |
| 5.15.63           | 5         | 3.14%   |
| 5.15.27           | 4         | 2.52%   |
| 4.4.190           | 4         | 2.52%   |
| 5.15.38           | 3         | 1.89%   |
| 4.4.240           | 3         | 1.89%   |
| 5.3.7             | 2         | 1.26%   |
| 5.19.17-Unraid    | 2         | 1.26%   |
| 5.17.2            | 2         | 1.26%   |
| 5.17.1            | 2         | 1.26%   |
| 5.16.13           | 2         | 1.26%   |
| 5.15.94           | 2         | 1.26%   |
| 5.15.80           | 2         | 1.26%   |
| 5.15.30-Unraid    | 2         | 1.26%   |
| 5.13.8            | 2         | 1.26%   |
| 5.10.3            | 2         | 1.26%   |
| 4.4.276           | 2         | 1.26%   |
| 6.1.27            | 1         | 0.63%   |
| 6.1.20            | 1         | 0.63%   |
| 6.1.13            | 1         | 0.63%   |
| 6.1.12            | 1         | 0.63%   |
| 6.1.1             | 1         | 0.63%   |
| 5.7.0             | 1         | 0.63%   |
| 5.5.10            | 1         | 0.63%   |
| 5.4.77            | 1         | 0.63%   |
| 5.4.75            | 1         | 0.63%   |
| 5.4.62            | 1         | 0.63%   |
| 5.4.53-APRL       | 1         | 0.63%   |
| 5.4.50            | 1         | 0.63%   |
| 5.4.47            | 1         | 0.63%   |
| 5.4.43            | 1         | 0.63%   |
| 5.4.24toshiba-new | 1         | 0.63%   |
| 5.4.2             | 1         | 0.63%   |
| 5.4.139-jw        | 1         | 0.63%   |
| 5.4.13            | 1         | 0.63%   |
| 5.4.12+           | 1         | 0.63%   |
| 5.4.0-rc2-vto     | 1         | 0.63%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.19 | 19        | 11.95%  |
| 5.19.17 | 8         | 5.03%   |
| 4.19.80 | 8         | 5.03%   |
| 5.10.28 | 6         | 3.77%   |
| 5.15.63 | 5         | 3.14%   |
| 4.4.190 | 5         | 3.14%   |
| 5.15.27 | 4         | 2.52%   |
| 5.15.38 | 3         | 1.89%   |
| 4.4.240 | 3         | 1.89%   |
| 5.3.7   | 2         | 1.26%   |
| 5.17.2  | 2         | 1.26%   |
| 5.17.1  | 2         | 1.26%   |
| 5.16.13 | 2         | 1.26%   |
| 5.15.94 | 2         | 1.26%   |
| 5.15.80 | 2         | 1.26%   |
| 5.15.30 | 2         | 1.26%   |
| 5.14.15 | 2         | 1.26%   |
| 5.13.8  | 2         | 1.26%   |
| 5.10.3  | 2         | 1.26%   |
| 4.4.276 | 2         | 1.26%   |
| 6.1.27  | 1         | 0.63%   |
| 6.1.20  | 1         | 0.63%   |
| 6.1.13  | 1         | 0.63%   |
| 6.1.12  | 1         | 0.63%   |
| 6.1.1   | 1         | 0.63%   |
| 5.7.0   | 1         | 0.63%   |
| 5.5.10  | 1         | 0.63%   |
| 5.4.77  | 1         | 0.63%   |
| 5.4.75  | 1         | 0.63%   |
| 5.4.62  | 1         | 0.63%   |
| 5.4.53  | 1         | 0.63%   |
| 5.4.50  | 1         | 0.63%   |
| 5.4.47  | 1         | 0.63%   |
| 5.4.43  | 1         | 0.63%   |
| 5.4.24  | 1         | 0.63%   |
| 5.4.2   | 1         | 0.63%   |
| 5.4.139 | 1         | 0.63%   |
| 5.4.13  | 1         | 0.63%   |
| 5.4.12  | 1         | 0.63%   |
| 5.4.0   | 1         | 0.63%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 48        | 30.57%  |
| 4.4     | 17        | 10.83%  |
| 5.10    | 15        | 9.55%   |
| 4.19    | 15        | 9.55%   |
| 5.4     | 13        | 8.28%   |
| 5.19    | 9         | 5.73%   |
| 5.14    | 7         | 4.46%   |
| 5.13    | 7         | 4.46%   |
| 5.17    | 6         | 3.82%   |
| 5.16    | 6         | 3.82%   |
| 6.1     | 4         | 2.55%   |
| 5.3     | 2         | 1.27%   |
| 4.9     | 2         | 1.27%   |
| 5.7     | 1         | 0.64%   |
| 5.5     | 1         | 0.64%   |
| 5.2     | 1         | 0.64%   |
| 5.12    | 1         | 0.64%   |
| 4.20    | 1         | 0.64%   |
| 4.16    | 1         | 0.64%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 145       | 97.97%  |
| aarch64 | 2         | 1.35%   |
| i686    | 1         | 0.68%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Unknown       | 47        | 31.13%  |
| XFCE          | 44        | 29.14%  |
| KDE5          | 40        | 26.49%  |
| KDE           | 5         | 3.31%   |
| GNOME         | 3         | 1.99%   |
| xwmconfig     | 2         | 1.32%   |
| MATE          | 2         | 1.32%   |
| FVWM          | 2         | 1.32%   |
| X-Generic     | 1         | 0.66%   |
| X-Cinnamon    | 1         | 0.66%   |
| LXQt          | 1         | 0.66%   |
| Enlightenment | 1         | 0.66%   |
| awesome       | 1         | 0.66%   |
| 2bwm          | 1         | 0.66%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 99        | 65.13%  |
| Tty     | 34        | 22.37%  |
| Unknown | 12        | 7.89%   |
| Wayland | 7         | 4.61%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 62        | 40.79%  |
| SDDM    | 51        | 33.55%  |
| XDM     | 32        | 21.05%  |
| LightDM | 4         | 2.63%   |
| SLiM    | 2         | 1.32%   |
| GDM     | 1         | 0.66%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 76        | 51.35%  |
| Unknown     | 43        | 29.05%  |
| ru_RU       | 4         | 2.7%    |
| pt_BR       | 4         | 2.7%    |
| it_IT       | 4         | 2.7%    |
| fr_FR       | 3         | 2.03%   |
| en_GB       | 3         | 2.03%   |
| de_DE       | 3         | 2.03%   |
| sr_RS@latin | 1         | 0.68%   |
| pt_PT       | 1         | 0.68%   |
| pl_PL       | 1         | 0.68%   |
| es_ES.UTF8  | 1         | 0.68%   |
| es_ES       | 1         | 0.68%   |
| en_US.ASCII | 1         | 0.68%   |
| en_AU       | 1         | 0.68%   |
| C           | 1         | 0.68%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 79        | 53.02%  |
| EFI  | 70        | 46.98%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 108       | 72.97%  |
| Btrfs    | 16        | 10.81%  |
| Xfs      | 7         | 4.73%   |
| Overlay  | 7         | 4.73%   |
| Rootfs   | 3         | 2.03%   |
| Zfs      | 1         | 0.68%   |
| Tmpfs    | 1         | 0.68%   |
| Reiserfs | 1         | 0.68%   |
| Jfs      | 1         | 0.68%   |
| F2fs     | 1         | 0.68%   |
| Ext3     | 1         | 0.68%   |
| Ext2     | 1         | 0.68%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 100       | 66.23%  |
| MBR     | 36        | 23.84%  |
| Unknown | 15        | 9.93%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 100       | 66.23%  |
| Yes       | 51        | 33.77%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 100       | 67.57%  |
| Yes       | 48        | 32.43%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 25        | 16.89%  |
| Hewlett-Packard     | 24        | 16.22%  |
| Lenovo              | 18        | 12.16%  |
| Dell                | 14        | 9.46%   |
| MSI                 | 13        | 8.78%   |
| ASRock              | 11        | 7.43%   |
| Gigabyte Technology | 6         | 4.05%   |
| Acer                | 6         | 4.05%   |
| Toshiba             | 3         | 2.03%   |
| Notebook            | 2         | 1.35%   |
| Fujitsu             | 2         | 1.35%   |
| Dynabook            | 2         | 1.35%   |
| Apple               | 2         | 1.35%   |
| Unknown             | 2         | 1.35%   |
| Valve               | 1         | 0.68%   |
| TYAN Computer       | 1         | 0.68%   |
| System76            | 1         | 0.68%   |
| Supermicro          | 1         | 0.68%   |
| Sony                | 1         | 0.68%   |
| Shuttle             | 1         | 0.68%   |
| Samsung Electronics | 1         | 0.68%   |
| Radxa               | 1         | 0.68%   |
| NetGear             | 1         | 0.68%   |
| Microsoft           | 1         | 0.68%   |
| Intel               | 1         | 0.68%   |
| Huanan              | 1         | 0.68%   |
| HPE                 | 1         | 0.68%   |
| HEDYCOMPUTER        | 1         | 0.68%   |
| Framework           | 1         | 0.68%   |
| Foxconn             | 1         | 0.68%   |
| Biostar             | 1         | 0.68%   |
| AMI                 | 1         | 0.68%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| ASUS All Series                          | 4         | 2.7%    |
| ASUS VivoBook_ASUSLaptop K6500ZE_K6500ZE | 2         | 1.35%   |
| ASRock N68-S3 FX                         | 2         | 1.35%   |
| Unknown                                  | 2         | 1.35%   |
| Valve Jupiter                            | 1         | 0.68%   |
| TYAN S7012                               | 1         | 0.68%   |
| Toshiba Satellite P50-A-12Z              | 1         | 0.68%   |
| Toshiba Satellite C660                   | 1         | 0.68%   |
| Toshiba PORTEGE Z30-A                    | 1         | 0.68%   |
| System76 Oryx Pro                        | 1         | 0.68%   |
| Supermicro X9DA7/E                       | 1         | 0.68%   |
| Sony SVE1713A1EW                         | 1         | 0.68%   |
| Shuttle NC03U                            | 1         | 0.68%   |
| Samsung 300E5M/300E5L                    | 1         | 0.68%   |
| Radxa ROCK Pi 4                          | 1         | 0.68%   |
| Notebook X170KM-G                        | 1         | 0.68%   |
| Notebook NL40_50CU                       | 1         | 0.68%   |
| NetGear ReadyDATA 5200                   | 1         | 0.68%   |
| MSI MS-7C52                              | 1         | 0.68%   |
| MSI MS-7C02                              | 1         | 0.68%   |
| MSI MS-7996                              | 1         | 0.68%   |
| MSI MS-7885                              | 1         | 0.68%   |
| MSI MS-7788                              | 1         | 0.68%   |
| MSI MS-7693                              | 1         | 0.68%   |
| MSI MS-7529                              | 1         | 0.68%   |
| MSI MS-7365                              | 1         | 0.68%   |
| MSI Modern 14 B11MO                      | 1         | 0.68%   |
| MSI Modern 14 B10MW                      | 1         | 0.68%   |
| MSI GP76 Leopard 11UG                    | 1         | 0.68%   |
| MSI GL73 8RC                             | 1         | 0.68%   |
| MSI GE76 Raider 11UE                     | 1         | 0.68%   |
| Microsoft Surface Go 3                   | 1         | 0.68%   |
| Lenovo V330-14ARR 81B1                   | 1         | 0.68%   |
| Lenovo ThinkPad X230 2325P38             | 1         | 0.68%   |
| Lenovo ThinkPad X140e 20BMS03E00         | 1         | 0.68%   |
| Lenovo ThinkPad X1 Carbon 7th 20R10015US | 1         | 0.68%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS04300 | 1         | 0.68%   |
| Lenovo ThinkPad T61 765912G              | 1         | 0.68%   |
| Lenovo ThinkPad T470p 20J60018MS         | 1         | 0.68%   |
| Lenovo ThinkPad T470 20JNS01R01          | 1         | 0.68%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 14        | 9.46%   |
| Dell Precision    | 5         | 3.38%   |
| ASUS PRIME        | 5         | 3.38%   |
| HP Pavilion       | 4         | 2.7%    |
| ASUS ROG          | 4         | 2.7%    |
| ASUS All          | 4         | 2.7%    |
| HP Laptop         | 3         | 2.03%   |
| HP EliteBook      | 3         | 2.03%   |
| Dell Latitude     | 3         | 2.03%   |
| ASUS VivoBook     | 3         | 2.03%   |
| Toshiba Satellite | 2         | 1.35%   |
| MSI Modern        | 2         | 1.35%   |
| Lenovo IdeaPad    | 2         | 1.35%   |
| HP OMEN           | 2         | 1.35%   |
| Fujitsu LIFEBOOK  | 2         | 1.35%   |
| Dell PowerEdge    | 2         | 1.35%   |
| Dell OptiPlex     | 2         | 1.35%   |
| ASUS TUF          | 2         | 1.35%   |
| ASRock N68-S3     | 2         | 1.35%   |
| Acer Swift        | 2         | 1.35%   |
| Acer Aspire       | 2         | 1.35%   |
| Unknown           | 2         | 1.35%   |
| Valve Jupiter     | 1         | 0.68%   |
| TYAN S7012        | 1         | 0.68%   |
| Toshiba PORTEGE   | 1         | 0.68%   |
| System76 Oryx     | 1         | 0.68%   |
| Supermicro X9DA7  | 1         | 0.68%   |
| Sony SVE1713A1EW  | 1         | 0.68%   |
| Shuttle NC03U     | 1         | 0.68%   |
| Samsung 300E5M    | 1         | 0.68%   |
| Radxa ROCK        | 1         | 0.68%   |
| Notebook X170KM-G | 1         | 0.68%   |
| Notebook NL40     | 1         | 0.68%   |
| NetGear ReadyDATA | 1         | 0.68%   |
| MSI MS-7C52       | 1         | 0.68%   |
| MSI MS-7C02       | 1         | 0.68%   |
| MSI MS-7996       | 1         | 0.68%   |
| MSI MS-7885       | 1         | 0.68%   |
| MSI MS-7788       | 1         | 0.68%   |
| MSI MS-7693       | 1         | 0.68%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 17        | 11.49%  |
| 2020    | 14        | 9.46%   |
| 2017    | 13        | 8.78%   |
| 2015    | 12        | 8.11%   |
| 2012    | 12        | 8.11%   |
| 2021    | 11        | 7.43%   |
| 2018    | 11        | 7.43%   |
| 2014    | 9         | 6.08%   |
| 2011    | 9         | 6.08%   |
| 2022    | 7         | 4.73%   |
| 2016    | 7         | 4.73%   |
| 2008    | 7         | 4.73%   |
| 2007    | 5         | 3.38%   |
| 2013    | 4         | 2.7%    |
| 2010    | 4         | 2.7%    |
| 2009    | 4         | 2.7%    |
| Unknown | 2         | 1.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 69        | 46.62%  |
| Desktop        | 68        | 45.95%  |
| Mini pc        | 3         | 2.03%   |
| Server         | 3         | 2.03%   |
| System on chip | 2         | 1.35%   |
| All in one     | 2         | 1.35%   |
| Tablet         | 1         | 0.68%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 148       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 145       | 97.97%  |
| Yes  | 3         | 2.03%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 33        | 22.15%  |
| 8.01-16.0   | 27        | 18.12%  |
| 4.01-8.0    | 26        | 17.45%  |
| 3.01-4.0    | 24        | 16.11%  |
| 32.01-64.0  | 16        | 10.74%  |
| 64.01-256.0 | 10        | 6.71%   |
| 24.01-32.0  | 7         | 4.7%    |
| 1.01-2.0    | 5         | 3.36%   |
| 0.51-1.0    | 1         | 0.67%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 43        | 27.74%  |
| 2.01-3.0    | 36        | 23.23%  |
| 4.01-8.0    | 27        | 17.42%  |
| 3.01-4.0    | 16        | 10.32%  |
| 0.51-1.0    | 13        | 8.39%   |
| 8.01-16.0   | 6         | 3.87%   |
| 0.01-0.5    | 6         | 3.87%   |
| 16.01-24.0  | 4         | 2.58%   |
| 24.01-32.0  | 2         | 1.29%   |
| 32.01-64.0  | 1         | 0.65%   |
| 64.01-256.0 | 1         | 0.65%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 73        | 48.03%  |
| 2      | 33        | 21.71%  |
| 3      | 17        | 11.18%  |
| 4      | 10        | 6.58%   |
| 6      | 6         | 3.95%   |
| 5      | 5         | 3.29%   |
| 0      | 3         | 1.97%   |
| 13     | 1         | 0.66%   |
| 11     | 1         | 0.66%   |
| 9      | 1         | 0.66%   |
| 8      | 1         | 0.66%   |
| 7      | 1         | 0.66%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 89        | 59.73%  |
| Yes       | 60        | 40.27%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 136       | 91.89%  |
| No        | 12        | 8.11%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 100       | 67.11%  |
| No        | 49        | 32.89%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 90        | 60.81%  |
| No        | 58        | 39.19%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 33        | 22.3%   |
| UK           | 12        | 8.11%   |
| Germany      | 10        | 6.76%   |
| Brazil       | 10        | 6.76%   |
| Italy        | 8         | 5.41%   |
| Russia       | 7         | 4.73%   |
| Portugal     | 7         | 4.73%   |
| Kazakhstan   | 6         | 4.05%   |
| Japan        | 6         | 4.05%   |
| Canada       | 6         | 4.05%   |
| India        | 5         | 3.38%   |
| France       | 5         | 3.38%   |
| Sweden       | 4         | 2.7%    |
| Spain        | 4         | 2.7%    |
| South Africa | 3         | 2.03%   |
| Hong Kong    | 3         | 2.03%   |
| Greece       | 3         | 2.03%   |
| Serbia       | 2         | 1.35%   |
| Poland       | 2         | 1.35%   |
| Chile        | 2         | 1.35%   |
| Australia    | 2         | 1.35%   |
| Switzerland  | 1         | 0.68%   |
| Philippines  | 1         | 0.68%   |
| Netherlands  | 1         | 0.68%   |
| Mexico       | 1         | 0.68%   |
| Finland      | 1         | 0.68%   |
| China        | 1         | 0.68%   |
| Bulgaria     | 1         | 0.68%   |
| Argentina    | 1         | 0.68%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Lisbon                 | 6         | 3.92%   |
| Ust-Kamenogorsk        | 4         | 2.61%   |
| Yekaterinburg          | 3         | 1.96%   |
| Tsukuba                | 3         | 1.96%   |
| Paris                  | 3         | 1.96%   |
| Chania                 | 3         | 1.96%   |
| Warsaw                 | 2         | 1.31%   |
| Tendo                  | 2         | 1.31%   |
| Sun Prairie            | 2         | 1.31%   |
| New Delhi              | 2         | 1.31%   |
| Moscow                 | 2         | 1.31%   |
| Milan                  | 2         | 1.31%   |
| McKinney               | 2         | 1.31%   |
| Karaganda              | 2         | 1.31%   |
| Frignano               | 2         | 1.31%   |
| Fayetteville           | 2         | 1.31%   |
| Carrollton             | 2         | 1.31%   |
| Cape Town              | 2         | 1.31%   |
| Belgrade               | 2         | 1.31%   |
| Barry                  | 2         | 1.31%   |
| Barrie                 | 2         | 1.31%   |
| Worpswede              | 1         | 0.65%   |
| Wokingham              | 1         | 0.65%   |
| Winter Springs         | 1         | 0.65%   |
| Winnipeg               | 1         | 0.65%   |
| Weilheim               | 1         | 0.65%   |
| Voskresensk            | 1         | 0.65%   |
| Visconde do Rio Branco | 1         | 0.65%   |
| Toronto                | 1         | 0.65%   |
| Tiffin                 | 1         | 0.65%   |
| Tatuí                 | 1         | 0.65%   |
| Stockholm              | 1         | 0.65%   |
| St Petersburg          | 1         | 0.65%   |
| St Louis               | 1         | 0.65%   |
| Springfield            | 1         | 0.65%   |
| Southend-on-Sea        | 1         | 0.65%   |
| Skövde                | 1         | 0.65%   |
| Shrewsbury             | 1         | 0.65%   |
| Sham Shui Po           | 1         | 0.65%   |
| Seville                | 1         | 0.65%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 44        | 88     | 18.64%  |
| Samsung Electronics | 39        | 58     | 16.53%  |
| Seagate             | 36        | 66     | 15.25%  |
| Toshiba             | 18        | 35     | 7.63%   |
| Kingston            | 11        | 14     | 4.66%   |
| Crucial             | 10        | 12     | 4.24%   |
| Hitachi             | 8         | 11     | 3.39%   |
| Intel               | 7         | 8      | 2.97%   |
| HGST                | 6         | 6      | 2.54%   |
| Unknown             | 5         | 5      | 2.12%   |
| SK hynix            | 5         | 5      | 2.12%   |
| SanDisk             | 5         | 6      | 2.12%   |
| A-DATA Technology   | 4         | 4      | 1.69%   |
| Micron Technology   | 3         | 3      | 1.27%   |
| KIOXIA              | 3         | 3      | 1.27%   |
| Hewlett-Packard     | 3         | 4      | 1.27%   |
| Gigabyte Technology | 3         | 3      | 1.27%   |
| Transcend           | 2         | 2      | 0.85%   |
| Patriot             | 2         | 3      | 0.85%   |
| Maxtor              | 2         | 2      | 0.85%   |
| China               | 2         | 3      | 0.85%   |
| Apple               | 2         | 3      | 0.85%   |
| ZHITAI              | 1         | 2      | 0.42%   |
| TO Exter            | 1         | 1      | 0.42%   |
| Team                | 1         | 1      | 0.42%   |
| Silicon Motion      | 1         | 1      | 0.42%   |
| PNY                 | 1         | 1      | 0.42%   |
| Plextor             | 1         | 1      | 0.42%   |
| Phison Electronics  | 1         | 1      | 0.42%   |
| Netac               | 1         | 1      | 0.42%   |
| Lexar               | 1         | 1      | 0.42%   |
| JMicron Technology  | 1         | 1      | 0.42%   |
| Intenso             | 1         | 1      | 0.42%   |
| GOODRAM             | 1         | 1      | 0.42%   |
| Fujitsu             | 1         | 1      | 0.42%   |
| External            | 1         | 1      | 0.42%   |
| DUEX                | 1         | 1      | 0.42%   |
| Dogfish             | 1         | 1      | 0.42%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD  | 4         | 1.39%   |
| WDC WD20EFRX-68EUZN0 2TB         | 3         | 1.04%   |
| WDC WD1003FZEX-00MK2A0 1TB       | 3         | 1.04%   |
| Seagate ST2000DM008-2FR102 2TB   | 3         | 1.04%   |
| Samsung SSD 970 EVO 250GB        | 3         | 1.04%   |
| WDC WDS100T2B0A-00SM50 1TB SSD   | 2         | 0.69%   |
| WDC WD30EZRX-00SPEB0 3TB         | 2         | 0.69%   |
| WDC WD10SPZX-60Z10T0 1TB         | 2         | 0.69%   |
| WDC WD10EZEX-08WN4A0 1TB         | 2         | 0.69%   |
| WDC WD10EZEX-00RKKA0 1TB         | 2         | 0.69%   |
| Toshiba MQ04ABF100 1TB           | 2         | 0.69%   |
| Toshiba MQ01ABD100 1TB           | 2         | 0.69%   |
| Seagate ST500DM002-1BD142 500GB  | 2         | 0.69%   |
| Seagate ST4000VN008-2DR166 4TB   | 2         | 0.69%   |
| Seagate ST4000DM004-2CV104 4TB   | 2         | 0.69%   |
| Seagate ST31000524AS 1TB         | 2         | 0.69%   |
| Seagate ST2000DM001-1CH164 2TB   | 2         | 0.69%   |
| Seagate ST2000DL003-9VT166 2TB   | 2         | 0.69%   |
| Seagate ST1000DM010-2EP102 1TB   | 2         | 0.69%   |
| Seagate ST1000DM003-1SB102 1TB   | 2         | 0.69%   |
| Seagate ST1000DM003-1ER162 1TB   | 2         | 0.69%   |
| Seagate Expansion Desk 4TB       | 2         | 0.69%   |
| Samsung SSD 970 EVO Plus 1TB     | 2         | 0.69%   |
| Samsung SSD 860 QVO 2TB          | 2         | 0.69%   |
| Intel SSD 660P Series 512GB      | 2         | 0.69%   |
| HGST HTS725050A7E630 500GB       | 2         | 0.69%   |
| Crucial CT500MX500SSD1 500GB     | 2         | 0.69%   |
| ZHITAI SC001 Active 1TB SSD      | 1         | 0.35%   |
| ZHITAI PC005 Active 512GB        | 1         | 0.35%   |
| WDC WDS500G2B0B-00YS70 500GB SSD | 1         | 0.35%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 1         | 0.35%   |
| WDC WDS480G2G0A-00JH30 480GB SSD | 1         | 0.35%   |
| WDC WDS100T2B0C-00PXH0 1TB       | 1         | 0.35%   |
| WDC WDS100T2B0B-00YS70 1TB SSD   | 1         | 0.35%   |
| WDC WD7500BPVT-24HXZT3 752GB     | 1         | 0.35%   |
| WDC WD5003ABYX-18WERA0 500GB     | 1         | 0.35%   |
| WDC WD5000LPCX-60VHAT1 500GB     | 1         | 0.35%   |
| WDC WD5000BPVT-2 500GB           | 1         | 0.35%   |
| WDC WD5000BPKX-60HPJT0 500GB     | 1         | 0.35%   |
| WDC WD5000AAKX-22ERMA0 500GB     | 1         | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 38        | 78     | 33.33%  |
| Seagate             | 36        | 62     | 31.58%  |
| Toshiba             | 17        | 30     | 14.91%  |
| Hitachi             | 8         | 11     | 7.02%   |
| HGST                | 6         | 6      | 5.26%   |
| Samsung Electronics | 4         | 4      | 3.51%   |
| Maxtor              | 2         | 2      | 1.75%   |
| Hewlett-Packard     | 1         | 1      | 0.88%   |
| Fujitsu             | 1         | 1      | 0.88%   |
| External            | 1         | 1      | 0.88%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 18        | 28     | 24.32%  |
| Kingston            | 10        | 13     | 13.51%  |
| Crucial             | 8         | 10     | 10.81%  |
| WDC                 | 5         | 7      | 6.76%   |
| SanDisk             | 4         | 4      | 5.41%   |
| Transcend           | 2         | 2      | 2.7%    |
| Patriot             | 2         | 3      | 2.7%    |
| Intel               | 2         | 3      | 2.7%    |
| China               | 2         | 3      | 2.7%    |
| Apple               | 2         | 3      | 2.7%    |
| A-DATA Technology   | 2         | 2      | 2.7%    |
| ZHITAI              | 1         | 1      | 1.35%   |
| Toshiba             | 1         | 3      | 1.35%   |
| TO Exter            | 1         | 1      | 1.35%   |
| Team                | 1         | 1      | 1.35%   |
| SK hynix            | 1         | 1      | 1.35%   |
| PNY                 | 1         | 1      | 1.35%   |
| Plextor             | 1         | 1      | 1.35%   |
| Netac               | 1         | 1      | 1.35%   |
| Micron Technology   | 1         | 1      | 1.35%   |
| Lexar               | 1         | 1      | 1.35%   |
| JMicron Technology  | 1         | 1      | 1.35%   |
| Intenso             | 1         | 1      | 1.35%   |
| Hewlett-Packard     | 1         | 1      | 1.35%   |
| GOODRAM             | 1         | 1      | 1.35%   |
| Gigabyte Technology | 1         | 1      | 1.35%   |
| DUEX                | 1         | 1      | 1.35%   |
| Dogfish             | 1         | 1      | 1.35%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 82        | 196    | 40.2%   |
| SSD     | 67        | 97     | 32.84%  |
| NVMe    | 49        | 59     | 24.02%  |
| MMC     | 5         | 5      | 2.45%   |
| Unknown | 1         | 4      | 0.49%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 113       | 284    | 65.32%  |
| NVMe | 49        | 59     | 28.32%  |
| SAS  | 6         | 13     | 3.47%   |
| MMC  | 5         | 5      | 2.89%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 82        | 122    | 47.13%  |
| 0.51-1.0   | 45        | 87     | 25.86%  |
| 1.01-2.0   | 19        | 26     | 10.92%  |
| 3.01-4.0   | 14        | 28     | 8.05%   |
| 2.01-3.0   | 8         | 19     | 4.6%    |
| 4.01-10.0  | 4         | 6      | 2.3%    |
| 10.01-20.0 | 2         | 5      | 1.15%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 34        | 22.52%  |
| 501-1000       | 32        | 21.19%  |
| 251-500        | 24        | 15.89%  |
| Unknown        | 18        | 11.92%  |
| 1001-2000      | 15        | 9.93%   |
| 2001-3000      | 8         | 5.3%    |
| 1-20           | 8         | 5.3%    |
| More than 3000 | 5         | 3.31%   |
| 51-100         | 4         | 2.65%   |
| 21-50          | 3         | 1.99%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 28        | 18.18%  |
| 1-20           | 25        | 16.23%  |
| 21-50          | 22        | 14.29%  |
| 501-1000       | 19        | 12.34%  |
| Unknown        | 18        | 11.69%  |
| 251-500        | 16        | 10.39%  |
| 51-100         | 16        | 10.39%  |
| 1001-2000      | 7         | 4.55%   |
| More than 3000 | 3         | 1.95%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WDS480G2G0A-00JH30 480GB SSD      | 1         | 1      | 2.38%   |
| WDC WD5003ABYX-18WERA0 500GB          | 1         | 2      | 2.38%   |
| WDC WD5000LPCX-60VHAT1 500GB          | 1         | 1      | 2.38%   |
| WDC WD5000BPKX-60HPJT0 500GB          | 1         | 1      | 2.38%   |
| WDC WD5000AAKX-22ERMA0 500GB          | 1         | 1      | 2.38%   |
| WDC WD5000AAKX-00ERMA0 500GB          | 1         | 1      | 2.38%   |
| WDC WD5000AAKS-00A7B2 500GB           | 1         | 1      | 2.38%   |
| WDC WD40EFRX-68WT0N0 4TB              | 1         | 2      | 2.38%   |
| WDC WD3200AAJS-65B4A0 320GB           | 1         | 1      | 2.38%   |
| WDC WD30EZRX-00MMMB0 3TB              | 1         | 1      | 2.38%   |
| WDC WD30EZRX-00M                      | 1         | 1      | 2.38%   |
| WDC WD30EFRX-68AX9N0 3TB              | 1         | 4      | 2.38%   |
| WDC WD20EFRX-68EUZN0 2TB              | 1         | 2      | 2.38%   |
| WDC WD20EARX-00PASB0 2TB              | 1         | 1      | 2.38%   |
| WDC WD10JPLX-00MBPT0 1TB              | 1         | 1      | 2.38%   |
| WDC WD10EZEX-00RKKA0 1TB              | 1         | 1      | 2.38%   |
| WDC WD10EALS-00Z8A0 1TB               | 1         | 2      | 2.38%   |
| WDC WD1003FZEX-00MK2A0 1TB            | 1         | 2      | 2.38%   |
| Toshiba MK2565GSXN 250GB              | 1         | 1      | 2.38%   |
| Seagate ST380011A 80GB                | 1         | 2      | 2.38%   |
| Seagate ST3500630AS 500GB             | 1         | 1      | 2.38%   |
| Seagate ST3500418AS 500GB             | 1         | 1      | 2.38%   |
| Seagate ST3500410AS 500GB             | 1         | 1      | 2.38%   |
| Seagate ST31000524AS 1TB              | 1         | 1      | 2.38%   |
| Seagate ST3000VX006-1HH166 3TB        | 1         | 1      | 2.38%   |
| Seagate ST2000DL003-9VT166 2TB        | 1         | 1      | 2.38%   |
| Seagate ST1000VM002-1SD102 1TB        | 1         | 1      | 2.38%   |
| Seagate ST1000NM0011 1TB              | 1         | 2      | 2.38%   |
| Seagate ST1000DM003-1ER162 1TB        | 1         | 2      | 2.38%   |
| SanDisk SDSA6MM-016G-1006 16GB SSD    | 1         | 1      | 2.38%   |
| Samsung Electronics SSD 970 EVO 500GB | 1         | 1      | 2.38%   |
| Samsung Electronics SSD 870 EVO 1TB   | 1         | 1      | 2.38%   |
| Plextor PX-128M6S 128GB SSD           | 1         | 1      | 2.38%   |
| Maxtor 4G120J6 128GB                  | 1         | 1      | 2.38%   |
| Intel SSDSA2M080G2GC 80GB             | 1         | 1      | 2.38%   |
| Hitachi HUA723030ALA640 3TB           | 1         | 1      | 2.38%   |
| Hitachi HDS721050CLA660 500GB         | 1         | 1      | 2.38%   |
| Hitachi HDS721016CLA382 160GB         | 1         | 1      | 2.38%   |
| HGST HTS725050A7E630 500GB            | 1         | 1      | 2.38%   |
| HGST HTS545050A7E380 500GB            | 1         | 1      | 2.38%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 15        | 26     | 39.47%  |
| Seagate             | 9         | 13     | 23.68%  |
| Hitachi             | 3         | 3      | 7.89%   |
| HGST                | 3         | 3      | 7.89%   |
| Samsung Electronics | 2         | 2      | 5.26%   |
| Toshiba             | 1         | 1      | 2.63%   |
| SanDisk             | 1         | 1      | 2.63%   |
| Plextor             | 1         | 1      | 2.63%   |
| Maxtor              | 1         | 1      | 2.63%   |
| Intel               | 1         | 1      | 2.63%   |
| DUEX                | 1         | 1      | 2.63%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 14        | 25     | 45.16%  |
| Seagate | 9         | 13     | 29.03%  |
| Hitachi | 3         | 3      | 9.68%   |
| HGST    | 3         | 3      | 9.68%   |
| Toshiba | 1         | 1      | 3.23%   |
| Maxtor  | 1         | 1      | 3.23%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 28        | 46     | 80%     |
| SSD  | 6         | 6      | 17.14%  |
| NVMe | 1         | 1      | 2.86%   |

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
| Works    | 116       | 246    | 64.8%   |
| Malfunc  | 35        | 53     | 19.55%  |
| Detected | 28        | 62     | 15.64%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 90        | 45.23%  |
| AMD                          | 35        | 17.59%  |
| Samsung Electronics          | 22        | 11.06%  |
| Marvell Technology Group     | 6         | 3.02%   |
| ASMedia Technology           | 6         | 3.02%   |
| Nvidia                       | 5         | 2.51%   |
| SK hynix                     | 4         | 2.01%   |
| SanDisk                      | 4         | 2.01%   |
| KIOXIA                       | 3         | 1.51%   |
| JMicron Technology           | 3         | 1.51%   |
| Broadcom / LSI               | 3         | 1.51%   |
| Realtek Semiconductor        | 2         | 1.01%   |
| Phison Electronics           | 2         | 1.01%   |
| Micron/Crucial Technology    | 2         | 1.01%   |
| Micron Technology            | 2         | 1.01%   |
| LSI Logic / Symbios Logic    | 2         | 1.01%   |
| Yangtze Memory Technologies  | 1         | 0.5%    |
| Toshiba America Info Systems | 1         | 0.5%    |
| Silicon Motion               | 1         | 0.5%    |
| Silicon Image                | 1         | 0.5%    |
| Kingston Technology Company  | 1         | 0.5%    |
| Biwin Storage Technology     | 1         | 0.5%    |
| Adaptec                      | 1         | 0.5%    |
| 3ware                        | 1         | 0.5%    |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 25        | 10.37%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 12        | 4.98%   |
| AMD 400 Series Chipset SATA Controller                                           | 10        | 4.15%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 7         | 2.9%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 6         | 2.49%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 6         | 2.49%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 5         | 2.07%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 5         | 2.07%   |
| Nvidia MCP61 SATA Controller                                                     | 4         | 1.66%   |
| Nvidia MCP61 IDE                                                                 | 4         | 1.66%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 4         | 1.66%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 4         | 1.66%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 1.66%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 4         | 1.66%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 3         | 1.24%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 1.24%   |
| Samsung NVMe SSD Controller 980                                                  | 3         | 1.24%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 3         | 1.24%   |
| Intel Volume Management Device NVMe RAID Controller                              | 3         | 1.24%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 3         | 1.24%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 3         | 1.24%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 3         | 1.24%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 3         | 1.24%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 3         | 1.24%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 3         | 1.24%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 1.24%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 2         | 0.83%   |
| SK hynix BC511                                                                   | 2         | 0.83%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 2         | 0.83%   |
| Realtek NVMe Controller                                                          | 2         | 0.83%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 2         | 0.83%   |
| Micron NVMe Storage Controller                                                   | 2         | 0.83%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                 | 2         | 0.83%   |
| JMicron JMB58x AHCI SATA controller                                              | 2         | 0.83%   |
| Intel SSD 660P Series                                                            | 2         | 0.83%   |
| Intel SSD 600P Series                                                            | 2         | 0.83%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 2         | 0.83%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                              | 2         | 0.83%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 2         | 0.83%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 2         | 0.83%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 107       | 53.77%  |
| NVMe | 49        | 24.62%  |
| IDE  | 22        | 11.06%  |
| RAID | 14        | 7.04%   |
| SAS  | 4         | 2.01%   |
| SCSI | 3         | 1.51%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 106       | 71.62%  |
| AMD    | 40        | 27.03%  |
| ARM    | 2         | 1.35%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 4         | 2.68%   |
| AMD Ryzen 5 3600 6-Core Processor             | 4         | 2.68%   |
| Intel 12th Gen Core i7-12700H                 | 3         | 2.01%   |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz            | 2         | 1.34%   |
| Intel Core i7-5820K CPU @ 3.30GHz             | 2         | 1.34%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 2         | 1.34%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1.34%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 1.34%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 1.34%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 1.34%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 2         | 1.34%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 2         | 1.34%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 2         | 1.34%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 1.34%   |
| ARM Processor                                 | 2         | 1.34%   |
| AMD Ryzen 7 3800X 8-Core Processor            | 2         | 1.34%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 2         | 1.34%   |
| AMD FX-8350 Eight-Core Processor              | 2         | 1.34%   |
| AMD Athlon II X2 250 Processor                | 2         | 1.34%   |
| Intel Xeon CPU X5680 @ 3.33GHz                | 1         | 0.67%   |
| Intel Xeon CPU X5355 @ 2.66GHz                | 1         | 0.67%   |
| Intel Xeon CPU X3450 @ 2.67GHz                | 1         | 0.67%   |
| Intel Xeon CPU E5-2697 v3 @ 2.60GHz           | 1         | 0.67%   |
| Intel Xeon CPU E5-2667 v2 @ 3.30GHz           | 1         | 0.67%   |
| Intel Xeon CPU E5-2660 v3 @ 2.60GHz           | 1         | 0.67%   |
| Intel Xeon CPU E5-2620 0 @ 2.00GHz            | 1         | 0.67%   |
| Intel Xeon CPU E5-2407 0 @ 2.20GHz            | 1         | 0.67%   |
| Intel Xeon CPU E5-1650 0 @ 3.20GHz            | 1         | 0.67%   |
| Intel Xeon CPU E3-1246 v3 @ 3.50GHz           | 1         | 0.67%   |
| Intel Xeon CPU 5160 @ 3.00GHz                 | 1         | 0.67%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 1         | 0.67%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz        | 1         | 0.67%   |
| Intel Pentium Dual CPU E2140 @ 1.60GHz        | 1         | 0.67%   |
| Intel Pentium CPU P6100 @ 2.00GHz             | 1         | 0.67%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.67%   |
| Intel Pentium CPU GOLD 6500Y @ 1.10GHz        | 1         | 0.67%   |
| Intel Pentium CPU G640 @ 2.80GHz              | 1         | 0.67%   |
| Intel Pentium CPU G4560 @ 3.50GHz             | 1         | 0.67%   |
| Intel Pentium CPU G3250 @ 3.20GHz             | 1         | 0.67%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 1         | 0.67%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 25        | 16.78%  |
| Intel Core i7        | 23        | 15.44%  |
| Other                | 16        | 10.74%  |
| Intel Xeon           | 13        | 8.72%   |
| AMD Ryzen 5          | 12        | 8.05%   |
| Intel Pentium        | 7         | 4.7%    |
| Intel Core i3        | 7         | 4.7%    |
| Intel Core 2 Duo     | 6         | 4.03%   |
| AMD Ryzen 9          | 5         | 3.36%   |
| AMD FX               | 5         | 3.36%   |
| Intel Celeron        | 4         | 2.68%   |
| AMD Ryzen 7          | 4         | 2.68%   |
| Intel Core 2 Quad    | 2         | 1.34%   |
| Intel Atom           | 2         | 1.34%   |
| AMD Athlon II X2     | 2         | 1.34%   |
| Intel Pentium Silver | 1         | 0.67%   |
| Intel Pentium Gold   | 1         | 0.67%   |
| Intel Pentium Dual   | 1         | 0.67%   |
| Intel Core M         | 1         | 0.67%   |
| Intel Core 2         | 1         | 0.67%   |
| AMD Ryzen Embedded   | 1         | 0.67%   |
| AMD Ryzen 7 PRO      | 1         | 0.67%   |
| AMD Ryzen 3          | 1         | 0.67%   |
| AMD GX               | 1         | 0.67%   |
| AMD EPYC             | 1         | 0.67%   |
| AMD E1               | 1         | 0.67%   |
| AMD Athlon 64 X2     | 1         | 0.67%   |
| AMD Athlon           | 1         | 0.67%   |
| AMD A8               | 1         | 0.67%   |
| AMD A4               | 1         | 0.67%   |
| AMD A10              | 1         | 0.67%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 51        | 34.23%  |
| 4      | 48        | 32.21%  |
| 8      | 16        | 10.74%  |
| 6      | 16        | 10.74%  |
| 16     | 4         | 2.68%   |
| 14     | 4         | 2.68%   |
| 12     | 4         | 2.68%   |
| 1      | 3         | 2.01%   |
| 10     | 2         | 1.34%   |
| 3      | 1         | 0.67%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 140       | 94.59%  |
| 2      | 8         | 5.41%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 107       | 72.3%   |
| 1      | 41        | 27.7%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 145       | 97.97%  |
| Unknown        | 2         | 1.35%   |
| 32-bit         | 1         | 0.68%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 33        | 22.3%   |
| 0x306a9    | 9         | 6.08%   |
| 0x306c3    | 6         | 4.05%   |
| 0x206d7    | 5         | 3.38%   |
| 0x806d1    | 4         | 2.7%    |
| 0x306d4    | 4         | 2.7%    |
| 0x1067a    | 4         | 2.7%    |
| 0x08701021 | 4         | 2.7%    |
| 0x906a3    | 3         | 2.03%   |
| 0x806ec    | 3         | 2.03%   |
| 0x806ea    | 3         | 2.03%   |
| 0x806c1    | 3         | 2.03%   |
| 0x406e3    | 3         | 2.03%   |
| 0x406c4    | 3         | 2.03%   |
| 0x306f2    | 3         | 2.03%   |
| 0x206a7    | 3         | 2.03%   |
| 0x08701013 | 3         | 2.03%   |
| 0x08108109 | 3         | 2.03%   |
| 0x906ed    | 2         | 1.35%   |
| 0x906ea    | 2         | 1.35%   |
| 0x6fd      | 2         | 1.35%   |
| 0x506e3    | 2         | 1.35%   |
| 0x20655    | 2         | 1.35%   |
| 0x106c2    | 2         | 1.35%   |
| 0x0a50000c | 2         | 1.35%   |
| 0x0a201016 | 2         | 1.35%   |
| 0x0810100b | 2         | 1.35%   |
| 0x06001119 | 2         | 1.35%   |
| 0x06000822 | 2         | 1.35%   |
| 0xa0671    | 1         | 0.68%   |
| 0xa0660    | 1         | 0.68%   |
| 0xa0653    | 1         | 0.68%   |
| 0xa0652    | 1         | 0.68%   |
| 0x906e9    | 1         | 0.68%   |
| 0x906c0    | 1         | 0.68%   |
| 0x906a4    | 1         | 0.68%   |
| 0x806e9    | 1         | 0.68%   |
| 0x706a1    | 1         | 0.68%   |
| 0x6fb      | 1         | 0.68%   |
| 0x6fa      | 1         | 0.68%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 20        | 13.51%  |
| Haswell          | 14        | 9.46%   |
| Zen 2            | 12        | 8.11%   |
| IvyBridge        | 10        | 6.76%   |
| SandyBridge      | 9         | 6.08%   |
| Core             | 8         | 5.41%   |
| Skylake          | 7         | 4.73%   |
| Piledriver       | 6         | 4.05%   |
| Zen+             | 5         | 3.38%   |
| Zen              | 5         | 3.38%   |
| Westmere         | 5         | 3.38%   |
| Penryn           | 5         | 3.38%   |
| Icelake          | 5         | 3.38%   |
| Zen 3            | 4         | 2.7%    |
| Silvermont       | 4         | 2.7%    |
| Broadwell        | 4         | 2.7%    |
| Alderlake Hybrid | 4         | 2.7%    |
| TigerLake        | 3         | 2.03%   |
| CometLake        | 3         | 2.03%   |
| Unknown          | 3         | 2.03%   |
| K10              | 2         | 1.35%   |
| Jaguar           | 2         | 1.35%   |
| Bonnell          | 2         | 1.35%   |
| Tremont          | 1         | 0.68%   |
| Puma             | 1         | 0.68%   |
| Nehalem          | 1         | 0.68%   |
| K8 Hammer        | 1         | 0.68%   |
| Goldmont plus    | 1         | 0.68%   |
| Bulldozer        | 1         | 0.68%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 71        | 43.56%  |
| Nvidia                     | 50        | 30.67%  |
| AMD                        | 38        | 23.31%  |
| Matrox Electronics Systems | 4         | 2.45%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 6         | 3.55%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 2.96%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 2.96%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 4         | 2.37%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 2.37%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 2.37%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 2.37%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 3         | 1.78%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 3         | 1.78%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3         | 1.78%   |
| Intel UHD Graphics 620                                                                   | 3         | 1.78%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 1.78%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 1.78%   |
| Intel HD Graphics 620                                                                    | 3         | 1.78%   |
| Intel HD Graphics 5500                                                                   | 3         | 1.78%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 1.78%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 3         | 1.78%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 1.78%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 1.78%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 1.18%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 1.18%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 1.18%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 2         | 1.18%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 2         | 1.18%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 2         | 1.18%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 2         | 1.18%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 1.18%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 1.18%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.18%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 1.18%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2         | 1.18%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.18%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 1.18%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 2         | 1.18%   |
| AMD Renoir                                                                               | 2         | 1.18%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 2         | 1.18%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 2         | 1.18%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2         | 1.18%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.59%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1         | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 56        | 37.84%  |
| 1 x AMD        | 35        | 23.65%  |
| 1 x Nvidia     | 31        | 20.95%  |
| Intel + Nvidia | 15        | 10.14%  |
| 1 x Matrox     | 4         | 2.7%    |
| Other          | 3         | 2.03%   |
| AMD + Nvidia   | 2         | 1.35%   |
| 2 x Nvidia     | 1         | 0.68%   |
| 2 x AMD        | 1         | 0.68%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 111       | 75%     |
| Proprietary | 25        | 16.89%  |
| Unknown     | 12        | 8.11%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 81        | 54.36%  |
| 0.51-1.0   | 15        | 10.07%  |
| 1.01-2.0   | 13        | 8.72%   |
| 3.01-4.0   | 11        | 7.38%   |
| 0.01-0.5   | 11        | 7.38%   |
| 7.01-8.0   | 9         | 6.04%   |
| 5.01-6.0   | 4         | 2.68%   |
| 8.01-16.0  | 3         | 2.01%   |
| 2.01-3.0   | 1         | 0.67%   |
| 16.01-24.0 | 1         | 0.67%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 17        | 11.33%  |
| BOE                     | 15        | 10%     |
| LG Display              | 13        | 8.67%   |
| Dell                    | 12        | 8%      |
| Chimei Innolux          | 12        | 8%      |
| AU Optronics            | 12        | 8%      |
| Hewlett-Packard         | 10        | 6.67%   |
| BenQ                    | 7         | 4.67%   |
| Goldstar                | 6         | 4%      |
| Lenovo                  | 5         | 3.33%   |
| Sharp                   | 4         | 2.67%   |
| Ancor Communications    | 4         | 2.67%   |
| Acer                    | 4         | 2.67%   |
| ASUSTek Computer        | 3         | 2%      |
| ViewSonic               | 2         | 1.33%   |
| Iiyama                  | 2         | 1.33%   |
| AOC                     | 2         | 1.33%   |
| Xiaomi                  | 1         | 0.67%   |
| Wacom                   | 1         | 0.67%   |
| Valve                   | 1         | 0.67%   |
| Unknown                 | 1         | 0.67%   |
| UGD                     | 1         | 0.67%   |
| Toshiba                 | 1         | 0.67%   |
| Sony                    | 1         | 0.67%   |
| PANDA                   | 1         | 0.67%   |
| Panasonic               | 1         | 0.67%   |
| ONN                     | 1         | 0.67%   |
| NEC Computers           | 1         | 0.67%   |
| JVC                     | 1         | 0.67%   |
| IOD                     | 1         | 0.67%   |
| Gigabyte Technology     | 1         | 0.67%   |
| GDH                     | 1         | 0.67%   |
| Eizo                    | 1         | 0.67%   |
| DPC                     | 1         | 0.67%   |
| Chi Mei Optoelectronics | 1         | 0.67%   |
| Apple                   | 1         | 0.67%   |
| Unknown                 | 1         | 0.67%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 3         | 1.95%   |
| Samsung Electronics LCD Monitor SDC416E 2880x1620 344x194mm 15.5-inch | 2         | 1.3%    |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 2         | 1.3%    |
| LG Display LCD Monitor LGD0353 1366x768 345x194mm 15.6-inch           | 2         | 1.3%    |
| Lenovo LCD Monitor LEN4035 1280x800 303x190mm 14.1-inch               | 2         | 1.3%    |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch         | 2         | 1.3%    |
| Xiaomi Mi TV XMD009A 2880x1800 480x270mm 21.7-inch                    | 1         | 0.65%   |
| Wacom Cintiq 22HDT WAC1037 1920x1080 476x268mm 21.5-inch              | 1         | 0.65%   |
| ViewSonic LCD Monitor VX2276 Series 1920x1080                         | 1         | 0.65%   |
| ViewSonic LCD Monitor VA2448 SERIES 1920x1080                         | 1         | 0.65%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 1         | 0.65%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 1         | 0.65%   |
| UGD LCD Monitor UGD1302 1920x1080 290x160mm 13.0-inch                 | 1         | 0.65%   |
| Toshiba TV TSB0206 1920x1080 1600x1000mm 74.3-inch                    | 1         | 0.65%   |
| Sony TV SNY8102 1360x768                                              | 1         | 0.65%   |
| Sharp LQ173M1JW05 SHP14EC 1920x1080 382x215mm 17.3-inch               | 1         | 0.65%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 1         | 0.65%   |
| Sharp LQ125T1JW02 SHP142F 2560x1440 277x155mm 12.5-inch               | 1         | 0.65%   |
| Sharp LCD Monitor SHP14C4 1920x1080 344x194mm 15.5-inch               | 1         | 0.65%   |
| Samsung Electronics SyncMaster SAM0578 1920x1080 476x268mm 21.5-inch  | 1         | 0.65%   |
| Samsung Electronics SyncMaster SAM04DF 1360x768 410x230mm 18.5-inch   | 1         | 0.65%   |
| Samsung Electronics SyncMaster SAM0428 1680x1050 459x296mm 21.5-inch  | 1         | 0.65%   |
| Samsung Electronics SyncMaster SAM03F2 1680x1050                      | 1         | 0.65%   |
| Samsung Electronics SyncMaster SAM03F0 1680x1050 433x271mm 20.1-inch  | 1         | 0.65%   |
| Samsung Electronics SyncMaster SAM0248 1280x1024 376x301mm 19.0-inch  | 1         | 0.65%   |
| Samsung Electronics SyncMaster SAM01AD 1600x1200 408x306mm 20.1-inch  | 1         | 0.65%   |
| Samsung Electronics SMS27A650 SAM082D 1920x1080 598x336mm 27.0-inch   | 1         | 0.65%   |
| Samsung Electronics SMS19A100 SAM0867 1366x768 410x230mm 18.5-inch    | 1         | 0.65%   |
| Samsung Electronics SM2333T SAM0736 1920x1080 477x268mm 21.5-inch     | 1         | 0.65%   |
| Samsung Electronics S24D390 SAM0B65 1920x1080 521x293mm 23.5-inch     | 1         | 0.65%   |
| Samsung Electronics S22D300 SAM0B3E 1920x1080 477x268mm 21.5-inch     | 1         | 0.65%   |
| Samsung Electronics LCD Monitor U28D590 3840x2160                     | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch  | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch  | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch  | 1         | 0.65%   |
| Samsung Electronics B2430L SAM0644 1920x1080 521x293mm 23.5-inch      | 1         | 0.65%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch               | 1         | 0.65%   |
| Panasonic VVX14T092N00 MEI96A2 2256x1504 285x190mm 13.5-inch          | 1         | 0.65%   |
| ONN 100002480 ONN0101 1920x1080 470x290mm 21.7-inch                   | 1         | 0.65%   |
| NEC Computers LCD2490WUXi NEC66CE 1920x1200 518x324mm 24.1-inch       | 1         | 0.65%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 66        | 44.9%   |
| 1366x768 (WXGA)    | 26        | 17.69%  |
| 2560x1440 (QHD)    | 7         | 4.76%   |
| 1680x1050 (WSXGA+) | 7         | 4.76%   |
| 1280x1024 (SXGA)   | 7         | 4.76%   |
| 3840x2160 (4K)     | 6         | 4.08%   |
| 1920x1200 (WUXGA)  | 4         | 2.72%   |
| 1600x900 (HD+)     | 4         | 2.72%   |
| 1280x800 (WXGA)    | 4         | 2.72%   |
| 3440x1440          | 2         | 1.36%   |
| 2880x1620          | 2         | 1.36%   |
| 1440x900 (WXGA+)   | 2         | 1.36%   |
| 1360x768           | 2         | 1.36%   |
| 800x1280           | 1         | 0.68%   |
| 3200x1080          | 1         | 0.68%   |
| 2288x1287          | 1         | 0.68%   |
| 2256x1504          | 1         | 0.68%   |
| 1920x540           | 1         | 0.68%   |
| 1920x1280          | 1         | 0.68%   |
| 1600x1200          | 1         | 0.68%   |
| Unknown            | 1         | 0.68%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 32        | 21.19%  |
| 24      | 13        | 8.61%   |
| 21      | 13        | 8.61%   |
| 14      | 13        | 8.61%   |
| 27      | 12        | 7.95%   |
| 17      | 11        | 7.28%   |
| 13      | 11        | 7.28%   |
| 23      | 9         | 5.96%   |
| Unknown | 7         | 4.64%   |
| 22      | 4         | 2.65%   |
| 20      | 4         | 2.65%   |
| 19      | 4         | 2.65%   |
| 18      | 4         | 2.65%   |
| 12      | 3         | 1.99%   |
| 16      | 2         | 1.32%   |
| 142     | 1         | 0.66%   |
| 74      | 1         | 0.66%   |
| 72      | 1         | 0.66%   |
| 52      | 1         | 0.66%   |
| 34      | 1         | 0.66%   |
| 32      | 1         | 0.66%   |
| 11      | 1         | 0.66%   |
| 10      | 1         | 0.66%   |
| 7       | 1         | 0.66%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 56        | 37.33%  |
| 501-600        | 31        | 20.67%  |
| 401-500        | 27        | 18%     |
| 351-400        | 13        | 8.67%   |
| 201-300        | 8         | 5.33%   |
| Unknown        | 7         | 4.67%   |
| 701-800        | 2         | 1.33%   |
| 1501-2000      | 2         | 1.33%   |
| More than 2000 | 1         | 0.67%   |
| 601-700        | 1         | 0.67%   |
| 1001-1500      | 1         | 0.67%   |
| 1-100          | 1         | 0.67%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 100       | 71.94%  |
| 16/10   | 18        | 12.95%  |
| 5/4     | 5         | 3.6%    |
| Unknown | 5         | 3.6%    |
| 3/2     | 4         | 2.88%   |
| 6/5     | 2         | 1.44%   |
| 4/3     | 1         | 0.72%   |
| 32/9    | 1         | 0.72%   |
| 21/9    | 1         | 0.72%   |
| 1.00    | 1         | 0.72%   |
| 0.67    | 1         | 0.72%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 34        | 22.82%  |
| 201-250        | 29        | 19.46%  |
| 81-90          | 22        | 14.77%  |
| 301-350        | 12        | 8.05%   |
| 151-200        | 11        | 7.38%   |
| 141-150        | 7         | 4.7%    |
| 121-130        | 7         | 4.7%    |
| Unknown        | 7         | 4.7%    |
| 251-300        | 6         | 4.03%   |
| More than 1000 | 4         | 2.68%   |
| 61-70          | 3         | 2.01%   |
| 71-80          | 2         | 1.34%   |
| 51-60          | 2         | 1.34%   |
| 351-500        | 2         | 1.34%   |
| 1-40           | 1         | 0.67%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 52        | 34.67%  |
| 101-120       | 40        | 26.67%  |
| 121-160       | 37        | 24.67%  |
| 161-240       | 7         | 4.67%   |
| Unknown       | 7         | 4.67%   |
| 1-50          | 4         | 2.67%   |
| More than 240 | 3         | 2%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 115       | 77.7%   |
| 2     | 16        | 10.81%  |
| 0     | 13        | 8.78%   |
| 3     | 3         | 2.03%   |
| 4     | 1         | 0.68%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 86        | 39.09%  |
| Realtek Semiconductor    | 73        | 33.18%  |
| Qualcomm Atheros         | 14        | 6.36%   |
| Broadcom                 | 11        | 5%      |
| Ralink Technology        | 5         | 2.27%   |
| Broadcom Limited         | 5         | 2.27%   |
| Nvidia                   | 4         | 1.82%   |
| ASIX Electronics         | 4         | 1.82%   |
| TP-Link                  | 3         | 1.36%   |
| MediaTek                 | 3         | 1.36%   |
| VIA Technologies         | 1         | 0.45%   |
| Sitecom Europe           | 1         | 0.45%   |
| Sierra Wireless          | 1         | 0.45%   |
| Ralink                   | 1         | 0.45%   |
| Qualcomm                 | 1         | 0.45%   |
| Micro Star International | 1         | 0.45%   |
| Mellanox Technologies    | 1         | 0.45%   |
| Marvell Technology Group | 1         | 0.45%   |
| Huawei Technologies      | 1         | 0.45%   |
| Hewlett-Packard          | 1         | 0.45%   |
| Dell                     | 1         | 0.45%   |
| Chelsio Communications   | 1         | 0.45%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 51        | 19.25%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 3.4%    |
| Intel Wi-Fi 6 AX200                                               | 7         | 2.64%   |
| Intel I211 Gigabit Network Connection                             | 7         | 2.64%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 2.26%   |
| Ralink MT7601U Wireless Adapter                                   | 5         | 1.89%   |
| Intel Wireless 8265 / 8275                                        | 5         | 1.89%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 5         | 1.89%   |
| Intel 82574L Gigabit Network Connection                           | 5         | 1.89%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.51%   |
| Intel Wireless-AC 9260                                            | 4         | 1.51%   |
| Intel Wireless 7260                                               | 4         | 1.51%   |
| Intel Ethernet Connection (2) I218-V                              | 4         | 1.51%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 3         | 1.13%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 1.13%   |
| Nvidia MCP61 Ethernet                                             | 3         | 1.13%   |
| Intel Wireless 8260                                               | 3         | 1.13%   |
| Intel Wireless 7265                                               | 3         | 1.13%   |
| Intel I350 Gigabit Network Connection                             | 3         | 1.13%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 1.13%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 1.13%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.75%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 2         | 0.75%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 0.75%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 0.75%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 0.75%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.75%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.75%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 2         | 0.75%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 0.75%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 2         | 0.75%   |
| Intel Wireless 3160                                               | 2         | 0.75%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 0.75%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 0.75%   |
| Intel Ethernet Controller I225-V                                  | 2         | 0.75%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 0.75%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.75%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 0.75%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.75%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.75%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 57        | 54.81%  |
| Realtek Semiconductor    | 15        | 14.42%  |
| Qualcomm Atheros         | 10        | 9.62%   |
| Ralink Technology        | 5         | 4.81%   |
| TP-Link                  | 3         | 2.88%   |
| MediaTek                 | 3         | 2.88%   |
| Broadcom Limited         | 3         | 2.88%   |
| Broadcom                 | 3         | 2.88%   |
| Sitecom Europe           | 1         | 0.96%   |
| Sierra Wireless          | 1         | 0.96%   |
| Ralink                   | 1         | 0.96%   |
| Micro Star International | 1         | 0.96%   |
| Dell                     | 1         | 0.96%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                                   | 7         | 6.67%   |
| Ralink MT7601U Wireless Adapter                                                       | 5         | 4.76%   |
| Intel Wireless 8265 / 8275                                                            | 5         | 4.76%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 5         | 4.76%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 4         | 3.81%   |
| Intel Wireless-AC 9260                                                                | 4         | 3.81%   |
| Intel Wireless 7260                                                                   | 4         | 3.81%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 3         | 2.86%   |
| Intel Wireless 8260                                                                   | 3         | 2.86%   |
| Intel Wireless 7265                                                                   | 3         | 2.86%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 3         | 2.86%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 3         | 2.86%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 2         | 1.9%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                               | 2         | 1.9%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 2         | 1.9%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                      | 2         | 1.9%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                         | 2         | 1.9%    |
| Intel Wireless 3160                                                                   | 2         | 1.9%    |
| Intel Wi-Fi 6 AX201                                                                   | 2         | 1.9%    |
| Intel Tiger Lake PCH CNVi WiFi                                                        | 2         | 1.9%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 2         | 1.9%    |
| Intel Centrino Ultimate-N 6300                                                        | 2         | 1.9%    |
| Broadcom Limited BCM43228 802.11a/b/g/n                                               | 2         | 1.9%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                           | 1         | 0.95%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                                                 | 1         | 0.95%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                            | 1         | 0.95%   |
| Sitecom Europe WL-113 rev 2 Wireless Network USB Adapter                              | 1         | 0.95%   |
| Sierra Wireless EM7305                                                                | 1         | 0.95%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                    | 1         | 0.95%   |
| Realtek RTL8723DE Wireless Network Adapter                                            | 1         | 0.95%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                       | 1         | 0.95%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                           | 1         | 0.95%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1         | 0.95%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                             | 1         | 0.95%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 1         | 0.95%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                        | 1         | 0.95%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 1         | 0.95%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                      | 1         | 0.95%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 0.95%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 1         | 0.95%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 67        | 44.67%  |
| Intel                    | 51        | 34%     |
| Broadcom                 | 9         | 6%      |
| Qualcomm Atheros         | 7         | 4.67%   |
| Nvidia                   | 4         | 2.67%   |
| ASIX Electronics         | 4         | 2.67%   |
| Broadcom Limited         | 2         | 1.33%   |
| VIA Technologies         | 1         | 0.67%   |
| Qualcomm                 | 1         | 0.67%   |
| Mellanox Technologies    | 1         | 0.67%   |
| Marvell Technology Group | 1         | 0.67%   |
| Huawei Technologies      | 1         | 0.67%   |
| Chelsio Communications   | 1         | 0.67%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 51        | 32.08%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 5.66%   |
| Intel I211 Gigabit Network Connection                             | 7         | 4.4%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 3.77%   |
| Intel 82574L Gigabit Network Connection                           | 5         | 3.14%   |
| Intel Ethernet Connection (2) I218-V                              | 4         | 2.52%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 1.89%   |
| Nvidia MCP61 Ethernet                                             | 3         | 1.89%   |
| Intel I350 Gigabit Network Connection                             | 3         | 1.89%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1.26%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 1.26%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 1.26%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 1.26%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 1.26%   |
| Intel Ethernet Controller I225-V                                  | 2         | 1.26%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.26%   |
| Intel Ethernet Connection I217-V                                  | 2         | 1.26%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 1.26%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.26%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 1.26%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 1.26%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 1.26%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.26%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 1.26%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 2         | 1.26%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 2         | 1.26%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 1.26%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1         | 0.63%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1         | 0.63%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.63%   |
| Qualcomm Fairphone 4 5G                                           | 1         | 0.63%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.63%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.63%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]             | 1         | 0.63%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.63%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.63%   |
| Intel Ethernet Connection (5) I219-V                              | 1         | 0.63%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.63%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 0.63%   |
| Intel Ethernet Connection (2) I218-LM                             | 1         | 0.63%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 136       | 57.38%  |
| WiFi     | 100       | 42.19%  |
| Modem    | 1         | 0.42%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 80        | 54.42%  |
| WiFi     | 67        | 45.58%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 78        | 52%     |
| 1     | 54        | 36%     |
| 3     | 6         | 4%      |
| 4     | 5         | 3.33%   |
| 0     | 5         | 3.33%   |
| 5     | 2         | 1.33%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 131       | 87.33%  |
| Yes  | 19        | 12.67%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 50        | 54.95%  |
| Cambridge Silicon Radio         | 13        | 14.29%  |
| Realtek Semiconductor           | 7         | 7.69%   |
| Broadcom                        | 6         | 6.59%   |
| IMC Networks                    | 4         | 4.4%    |
| Qualcomm Atheros Communications | 3         | 3.3%    |
| Micro Star International        | 2         | 2.2%    |
| Apple                           | 2         | 2.2%    |
| TP-Link                         | 1         | 1.1%    |
| Toshiba                         | 1         | 1.1%    |
| MediaTek                        | 1         | 1.1%    |
| Foxconn / Hon Hai               | 1         | 1.1%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 19        | 20.88%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 13        | 14.29%  |
| Intel AX201 Bluetooth                               | 7         | 7.69%   |
| Intel AX200 Bluetooth                               | 7         | 7.69%   |
| Intel AX210 Bluetooth                               | 5         | 5.49%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 4.4%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 4         | 4.4%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 4.4%    |
| Realtek Bluetooth Radio                             | 3         | 3.3%    |
| IMC Networks Wireless_Device                        | 3         | 3.3%    |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 2.2%    |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 2.2%    |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2         | 2.2%    |
| TP-Link UB500 Adapter                               | 1         | 1.1%    |
| Toshiba Askey Bluetooth Module                      | 1         | 1.1%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 1.1%    |
| Micro Star International Bluetooth Dongle           | 1         | 1.1%    |
| Micro Star International Bluetooth Device           | 1         | 1.1%    |
| MediaTek Wireless_Device                            | 1         | 1.1%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.1%    |
| Intel Bluetooth Device                              | 1         | 1.1%    |
| IMC Networks Bluetooth Radio                        | 1         | 1.1%    |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 1.1%    |
| Broadcom HP Portable SoftSailing                    | 1         | 1.1%    |
| Broadcom BCM20702A0                                 | 1         | 1.1%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.1%    |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 1         | 1.1%    |
| Apple Bluetooth USB Host Controller                 | 1         | 1.1%    |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 1         | 1.1%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 97        | 47.78%  |
| AMD                    | 44        | 21.67%  |
| Nvidia                 | 41        | 20.2%   |
| Creative Labs          | 7         | 3.45%   |
| C-Media Electronics    | 4         | 1.97%   |
| Texas Instruments      | 2         | 0.99%   |
| VIA Technologies       | 1         | 0.49%   |
| RME                    | 1         | 0.49%   |
| M-Audio                | 1         | 0.49%   |
| Kingston Technology    | 1         | 0.49%   |
| Holtek Semiconductor   | 1         | 0.49%   |
| Generalplus Technology | 1         | 0.49%   |
| EGO SYStems            | 1         | 0.49%   |
| ASUSTek Computer       | 1         | 0.49%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 12        | 4.92%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 11        | 4.51%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 11        | 4.51%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 8         | 3.28%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 8         | 3.28%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 7         | 2.87%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 6         | 2.46%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 6         | 2.46%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 5         | 2.05%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 5         | 2.05%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 2.05%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 2.05%   |
| AMD FCH Azalia Controller                                                                         | 5         | 2.05%   |
| Nvidia MCP61 High Definition Audio                                                                | 4         | 1.64%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 4         | 1.64%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 1.64%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 1.64%   |
| Intel Broadwell-U Audio Controller                                                                | 4         | 1.64%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 1.64%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 4         | 1.64%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 1.64%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 1.64%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 1.64%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 4         | 1.64%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1.23%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 1.23%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 1.23%   |
| Nvidia Audio device                                                                               | 3         | 1.23%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 1.23%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 3         | 1.23%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 1.23%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.23%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus]   | 3         | 1.23%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 1.23%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 1.23%   |
| AMD Navi 10 HDMI Audio                                                                            | 3         | 1.23%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 3         | 1.23%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 2         | 0.82%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 0.82%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 2         | 0.82%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 29        | 19.21%  |
| Kingston            | 25        | 16.56%  |
| Samsung Electronics | 24        | 15.89%  |
| Corsair             | 14        | 9.27%   |
| Crucial             | 12        | 7.95%   |
| Unknown             | 9         | 5.96%   |
| Micron Technology   | 8         | 5.3%    |
| Team                | 4         | 2.65%   |
| G.Skill             | 3         | 1.99%   |
| Transcend           | 2         | 1.32%   |
| Smart               | 2         | 1.32%   |
| Ramaxel Technology  | 2         | 1.32%   |
| A-DATA Technology   | 2         | 1.32%   |
| Unknown             | 2         | 1.32%   |
| Strontium           | 1         | 0.66%   |
| Silicon Power       | 1         | 0.66%   |
| Patriot             | 1         | 0.66%   |
| Neo Forza           | 1         | 0.66%   |
| Nanya Technology    | 1         | 0.66%   |
| HPE                 | 1         | 0.66%   |
| Goodram             | 1         | 0.66%   |
| GLOWAY              | 1         | 0.66%   |
| Essencore Limited   | 1         | 0.66%   |
| Elpida              | 1         | 0.66%   |
| Avant               | 1         | 0.66%   |
| AMD                 | 1         | 0.66%   |
| A Force             | 1         | 0.66%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB DIMM SDRAM                             | 2         | 1.22%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s              | 2         | 1.22%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.22%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 2         | 1.22%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 1.22%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 4GB Row Of Chips LPDDR5 6400MT/s | 2         | 1.22%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 1.22%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.22%   |
| Corsair RAM CMZ32GX3M4X1600C10 8GB DIMM DDR3 1600MT/s            | 2         | 1.22%   |
| Unknown                                                          | 2         | 1.22%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                        | 1         | 0.61%   |
| Unknown RAM Module 4096MB DIMM DDR3 65535MT/s                    | 1         | 0.61%   |
| Unknown RAM Module 2GB DIMM DDR2 533MT/s                         | 1         | 0.61%   |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s                       | 1         | 0.61%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                           | 1         | 0.61%   |
| Unknown RAM Module 1024MB SODIMM SDRAM                           | 1         | 0.61%   |
| Unknown RAM Module 1024MB SODIMM DDR2 533MT/s                    | 1         | 0.61%   |
| Unknown RAM Module 1024MB DIMM DDR 800MT/s                       | 1         | 0.61%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                           | 1         | 0.61%   |
| Transcend RAM TS256MLQ72V6U 2GB DIMM DDR2 667MT/s                | 1         | 0.61%   |
| Transcend RAM JM1600KLN-8GK 4096MB DIMM DDR3 1600MT/s            | 1         | 0.61%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3600MT/s               | 1         | 0.61%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3733MT/s              | 1         | 0.61%   |
| Strontium RAM SRT4G86U1-P9H 4096MB DIMM DDR3 1333MT/s            | 1         | 0.61%   |
| Smart RAM SH5641G8FJ8NWRNSQG 8GB SODIMM DDR3 1600MT/s            | 1         | 0.61%   |
| Smart RAM SH564128FH8N6TNSQG 4GB DIMM DDR3 1600MT/s              | 1         | 0.61%   |
| SK hynix RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s          | 1         | 0.61%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                  | 1         | 0.61%   |
| SK hynix RAM HYMP512F72CP8N3-Y5 1024MB FB-DIMM DDR2 667MT/s      | 1         | 0.61%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s            | 1         | 0.61%   |
| SK hynix RAM HMT41GV7BMR4A-H9 16GB DIMM 1333MT/s                 | 1         | 0.61%   |
| SK hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 2000MT/s             | 1         | 0.61%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.61%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.61%   |
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1333MT/s             | 1         | 0.61%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.61%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1333MT/s        | 1         | 0.61%   |
| SK hynix RAM HMT351R7CFR8A-H9 4GB DIMM DDR3 1333MT/s             | 1         | 0.61%   |
| SK hynix RAM HMT31GR7EFR4A 8192MB DIMM DDR3 1600MT/s             | 1         | 0.61%   |
| SK hynix RAM HMT31GR7BFR4A-H9 8192MB DIMM 1333MT/s               | 1         | 0.61%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 59        | 45.04%  |
| DDR3    | 48        | 36.64%  |
| DDR2    | 7         | 5.34%   |
| SDRAM   | 4         | 3.05%   |
| LPDDR5  | 3         | 2.29%   |
| LPDDR4  | 3         | 2.29%   |
| LPDDR3  | 3         | 2.29%   |
| Unknown | 2         | 1.53%   |
| DDR5    | 1         | 0.76%   |
| DDR     | 1         | 0.76%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 63        | 48.09%  |
| SODIMM       | 61        | 46.56%  |
| Row Of Chips | 5         | 3.82%   |
| RIMM         | 1         | 0.76%   |
| FB-DIMM      | 1         | 0.76%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 56        | 38.89%  |
| 4096  | 45        | 31.25%  |
| 16384 | 18        | 12.5%   |
| 2048  | 12        | 8.33%   |
| 32768 | 7         | 4.86%   |
| 1024  | 6         | 4.17%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 34        | 23.94%  |
| 3200    | 18        | 12.68%  |
| 2667    | 15        | 10.56%  |
| 2400    | 12        | 8.45%   |
| 3600    | 8         | 5.63%   |
| 1333    | 8         | 5.63%   |
| 2133    | 5         | 3.52%   |
| 667     | 5         | 3.52%   |
| 3800    | 3         | 2.11%   |
| 1867    | 3         | 2.11%   |
| Unknown | 3         | 2.11%   |
| 6400    | 2         | 1.41%   |
| 2800    | 2         | 1.41%   |
| 2666    | 2         | 1.41%   |
| 1866    | 2         | 1.41%   |
| 1334    | 2         | 1.41%   |
| 975     | 2         | 1.41%   |
| 533     | 2         | 1.41%   |
| 65535   | 1         | 0.7%    |
| 4800    | 1         | 0.7%    |
| 4267    | 1         | 0.7%    |
| 4266    | 1         | 0.7%    |
| 4199    | 1         | 0.7%    |
| 3733    | 1         | 0.7%    |
| 3400    | 1         | 0.7%    |
| 2933    | 1         | 0.7%    |
| 2472    | 1         | 0.7%    |
| 2187    | 1         | 0.7%    |
| 2000    | 1         | 0.7%    |
| 1066    | 1         | 0.7%    |
| 800     | 1         | 0.7%    |
| 701     | 1         | 0.7%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 3         | 33.33%  |
| Brother Industries  | 3         | 33.33%  |
| QinHeng Electronics | 1         | 11.11%  |
| Dell                | 1         | 11.11%  |
| Canon               | 1         | 11.11%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                        | Computers | Percent |
|------------------------------|-----------|---------|
| QinHeng CH340S               | 1         | 11.11%  |
| HP OfficeJet Pro 9010 series | 1         | 11.11%  |
| HP ENVY 4520 series          | 1         | 11.11%  |
| HP ENVY 4500 series          | 1         | 11.11%  |
| Dell 2330d Laser Printer     | 1         | 11.11%  |
| Canon LiDE 300               | 1         | 11.11%  |
| Brother Printer              | 1         | 11.11%  |
| Brother HL-L5102DW           | 1         | 11.11%  |
| Brother HL-L2320D series     | 1         | 11.11%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Seiko Epson     | 1         | 33.33%  |
| Hewlett-Packard | 1         | 33.33%  |
| Canon           | 1         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO] | 1         | 33.33%  |
| HP ScanJet 5590                               | 1         | 33.33%  |
| Canon CanoScan LIDE 25                        | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 20        | 25.32%  |
| Logitech                               | 13        | 16.46%  |
| Acer                                   | 6         | 7.59%   |
| Realtek Semiconductor                  | 5         | 6.33%   |
| Microdia                               | 5         | 6.33%   |
| IMC Networks                           | 4         | 5.06%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 5.06%   |
| Quanta                                 | 3         | 3.8%    |
| Lite-On Technology                     | 3         | 3.8%    |
| Sunplus Innovation Technology          | 2         | 2.53%   |
| Sonix Technology                       | 2         | 2.53%   |
| Samsung Electronics                    | 2         | 2.53%   |
| Luxvisions Innotech Limited            | 2         | 2.53%   |
| Bison Electronics                      | 2         | 2.53%   |
| Syntek                                 | 1         | 1.27%   |
| Silicon Motion                         | 1         | 1.27%   |
| Motorola PCS                           | 1         | 1.27%   |
| Microsoft                              | 1         | 1.27%   |
| Lenovo                                 | 1         | 1.27%   |
| Apple                                  | 1         | 1.27%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 4         | 5.06%   |
| Logitech Webcam C270                                 | 3         | 3.8%    |
| Acer HD Webcam                                       | 3         | 3.8%    |
| Acer BisonCam,NB Pro                                 | 3         | 3.8%    |
| Sonix USB2.0 FHD UVC WebCam                          | 2         | 2.53%   |
| Samsung Galaxy series, misc. (MTP mode)              | 2         | 2.53%   |
| Quanta HP Webcam                                     | 2         | 2.53%   |
| Logitech HD Pro Webcam C920                          | 2         | 2.53%   |
| Chicony HD User Facing                               | 2         | 2.53%   |
| Chicony FJ Camera                                    | 2         | 2.53%   |
| Syntek USB2.0 Camera                                 | 1         | 1.27%   |
| Sunplus Laptop_Integrated_Webcam_FHD                 | 1         | 1.27%   |
| Sunplus Integrated_Webcam_HD                         | 1         | 1.27%   |
| Silicon Motion Web Camera                            | 1         | 1.27%   |
| Realtek USB Camera                                   | 1         | 1.27%   |
| Realtek Laptop Camera                                | 1         | 1.27%   |
| Realtek Integrated Camera                            | 1         | 1.27%   |
| Realtek EasyCamera                                   | 1         | 1.27%   |
| Realtek 2SF022                                       | 1         | 1.27%   |
| Quanta HP Wide Vision HD Camera                      | 1         | 1.27%   |
| Motorola PCS XT1033 [Moto G], PTP mode               | 1         | 1.27%   |
| Microsoft LifeCam HD-3000                            | 1         | 1.27%   |
| Microdia Laptop_Integrated_Webcam_2M                 | 1         | 1.27%   |
| Microdia Integrated_Webcam_HD                        | 1         | 1.27%   |
| Microdia Integrated Webcam                           | 1         | 1.27%   |
| Microdia Dell Integrated HD Webcam                   | 1         | 1.27%   |
| Microdia Camera                                      | 1         | 1.27%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 1.27%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 1         | 1.27%   |
| Logitech Webcam C310                                 | 1         | 1.27%   |
| Logitech Webcam C300                                 | 1         | 1.27%   |
| Logitech Webcam C170                                 | 1         | 1.27%   |
| Logitech QuickCam Pro 9000                           | 1         | 1.27%   |
| Logitech Logitech Webcam C160                        | 1         | 1.27%   |
| Logitech HD Webcam C910                              | 1         | 1.27%   |
| Logitech HD Webcam C525                              | 1         | 1.27%   |
| Logitech C922 Pro Stream Webcam                      | 1         | 1.27%   |
| Lite-On TOSHIBA Web Camera - FHD                     | 1         | 1.27%   |
| Lite-On Integrated Camera                            | 1         | 1.27%   |
| Lite-On HP TrueVision HD Camera                      | 1         | 1.27%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 9         | 50%     |
| Synaptics                          | 3         | 16.67%  |
| STMicroelectronics                 | 2         | 11.11%  |
| Realtek USB2.0 Finger Print Bridge | 2         | 11.11%  |
| LighTuning Technology              | 1         | 5.56%   |
| Elan Microelectronics              | 1         | 5.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI                                 | 3         | 16.67%  |
| STMicroelectronics Fingerprint Reader                           | 2         | 11.11%  |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 2         | 11.11%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor               | 1         | 5.56%   |
| Validity Sensors VFS495 Fingerprint Reader                      | 1         | 5.56%   |
| Validity Sensors VFS451 Fingerprint Reader                      | 1         | 5.56%   |
| Validity Sensors VFS300 Fingerprint Reader                      | 1         | 5.56%   |
| Validity Sensors VFS Fingerprint sensor                         | 1         | 5.56%   |
| Validity Sensors VFS 5011 fingerprint sensor                    | 1         | 5.56%   |
| Synaptics UWP WBDI                                              | 1         | 5.56%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 1         | 5.56%   |
| LighTuning EgisTec Touch Fingerprint Sensor                     | 1         | 5.56%   |
| Elan ELAN:Fingerprint                                           | 1         | 5.56%   |
| Unknown                                                         | 1         | 5.56%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 4         | 44.44%  |
| Broadcom              | 2         | 22.22%  |
| O2 Micro              | 1         | 11.11%  |
| Lenovo                | 1         | 11.11%  |
| Gemalto (was Gemplus) | 1         | 11.11%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                    | 4         | 44.44%  |
| O2 Micro OZ776 CCID Smartcard Reader                   | 1         | 11.11%  |
| Lenovo Integrated Smart Card Reader                    | 1         | 11.11%  |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer | 1         | 11.11%  |
| Broadcom BCM5880 Secure Applications Processor         | 1         | 11.11%  |
| Broadcom 5880                                          | 1         | 11.11%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 91        | 60.26%  |
| 1     | 35        | 23.18%  |
| 2     | 13        | 8.61%   |
| 3     | 7         | 4.64%   |
| 4     | 5         | 3.31%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 19        | 19.79%  |
| Fingerprint reader       | 17        | 17.71%  |
| Sound                    | 13        | 13.54%  |
| Chipcard                 | 9         | 9.38%   |
| Net/wireless             | 8         | 8.33%   |
| Communication controller | 8         | 8.33%   |
| Unassigned class         | 4         | 4.17%   |
| Multimedia controller    | 4         | 4.17%   |
| Card reader              | 4         | 4.17%   |
| Bluetooth                | 3         | 3.13%   |
| Net/ethernet             | 2         | 2.08%   |
| Camera                   | 2         | 2.08%   |
| Storage/ata              | 1         | 1.04%   |
| Storage                  | 1         | 1.04%   |
| Firewire controller      | 1         | 1.04%   |

