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

Total: 179

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| Slackware 15.0  | 75        | 52.08%  |
| Slackware 14.2  | 63        | 43.75%  |
| Slackware 14.2+ | 6         | 4.17%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| Slackware | 142       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.15.19           | 18        | 11.76%  |
| 4.19.80           | 8         | 5.23%   |
| 5.19.17           | 6         | 3.92%   |
| 5.10.28-Unraid    | 6         | 3.92%   |
| 5.15.63           | 4         | 2.61%   |
| 5.15.27           | 4         | 2.61%   |
| 4.4.190           | 4         | 2.61%   |
| 4.4.240           | 3         | 1.96%   |
| 5.3.7             | 2         | 1.31%   |
| 5.17.2            | 2         | 1.31%   |
| 5.17.1            | 2         | 1.31%   |
| 5.16.13           | 2         | 1.31%   |
| 5.15.80           | 2         | 1.31%   |
| 5.15.38           | 2         | 1.31%   |
| 5.15.30-Unraid    | 2         | 1.31%   |
| 5.13.8            | 2         | 1.31%   |
| 5.10.3            | 2         | 1.31%   |
| 4.4.276           | 2         | 1.31%   |
| 6.1.20            | 1         | 0.65%   |
| 6.1.13            | 1         | 0.65%   |
| 6.1.12            | 1         | 0.65%   |
| 6.1.1             | 1         | 0.65%   |
| 5.7.0             | 1         | 0.65%   |
| 5.5.10            | 1         | 0.65%   |
| 5.4.77            | 1         | 0.65%   |
| 5.4.75            | 1         | 0.65%   |
| 5.4.62            | 1         | 0.65%   |
| 5.4.53-APRL       | 1         | 0.65%   |
| 5.4.50            | 1         | 0.65%   |
| 5.4.47            | 1         | 0.65%   |
| 5.4.43            | 1         | 0.65%   |
| 5.4.24toshiba-new | 1         | 0.65%   |
| 5.4.2             | 1         | 0.65%   |
| 5.4.139-jw        | 1         | 0.65%   |
| 5.4.13            | 1         | 0.65%   |
| 5.4.12+           | 1         | 0.65%   |
| 5.4.0-rc2-vto     | 1         | 0.65%   |
| 5.2.2             | 1         | 0.65%   |
| 5.19.17-Unraid    | 1         | 0.65%   |
| 5.19.16           | 1         | 0.65%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.19 | 18        | 11.76%  |
| 4.19.80 | 8         | 5.23%   |
| 5.19.17 | 7         | 4.58%   |
| 5.10.28 | 6         | 3.92%   |
| 4.4.190 | 5         | 3.27%   |
| 5.15.63 | 4         | 2.61%   |
| 5.15.27 | 4         | 2.61%   |
| 4.4.240 | 3         | 1.96%   |
| 5.3.7   | 2         | 1.31%   |
| 5.17.2  | 2         | 1.31%   |
| 5.17.1  | 2         | 1.31%   |
| 5.16.13 | 2         | 1.31%   |
| 5.15.80 | 2         | 1.31%   |
| 5.15.38 | 2         | 1.31%   |
| 5.15.30 | 2         | 1.31%   |
| 5.14.15 | 2         | 1.31%   |
| 5.13.8  | 2         | 1.31%   |
| 5.10.3  | 2         | 1.31%   |
| 4.4.276 | 2         | 1.31%   |
| 6.1.20  | 1         | 0.65%   |
| 6.1.13  | 1         | 0.65%   |
| 6.1.12  | 1         | 0.65%   |
| 6.1.1   | 1         | 0.65%   |
| 5.7.0   | 1         | 0.65%   |
| 5.5.10  | 1         | 0.65%   |
| 5.4.77  | 1         | 0.65%   |
| 5.4.75  | 1         | 0.65%   |
| 5.4.62  | 1         | 0.65%   |
| 5.4.53  | 1         | 0.65%   |
| 5.4.50  | 1         | 0.65%   |
| 5.4.47  | 1         | 0.65%   |
| 5.4.43  | 1         | 0.65%   |
| 5.4.24  | 1         | 0.65%   |
| 5.4.2   | 1         | 0.65%   |
| 5.4.139 | 1         | 0.65%   |
| 5.4.13  | 1         | 0.65%   |
| 5.4.12  | 1         | 0.65%   |
| 5.4.0   | 1         | 0.65%   |
| 5.2.2   | 1         | 0.65%   |
| 5.19.16 | 1         | 0.65%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 44        | 29.14%  |
| 4.4     | 17        | 11.26%  |
| 5.10    | 15        | 9.93%   |
| 4.19    | 15        | 9.93%   |
| 5.4     | 13        | 8.61%   |
| 5.19    | 8         | 5.3%    |
| 5.14    | 7         | 4.64%   |
| 5.13    | 7         | 4.64%   |
| 5.17    | 6         | 3.97%   |
| 5.16    | 6         | 3.97%   |
| 6.1     | 3         | 1.99%   |
| 5.3     | 2         | 1.32%   |
| 4.9     | 2         | 1.32%   |
| 5.7     | 1         | 0.66%   |
| 5.5     | 1         | 0.66%   |
| 5.2     | 1         | 0.66%   |
| 5.12    | 1         | 0.66%   |
| 4.20    | 1         | 0.66%   |
| 4.16    | 1         | 0.66%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 139       | 97.89%  |
| aarch64 | 2         | 1.41%   |
| i686    | 1         | 0.7%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Unknown       | 46        | 31.72%  |
| XFCE          | 41        | 28.28%  |
| KDE5          | 39        | 26.9%   |
| KDE           | 5         | 3.45%   |
| GNOME         | 3         | 2.07%   |
| MATE          | 2         | 1.38%   |
| fvwm          | 2         | 1.38%   |
| xwmconfig     | 1         | 0.69%   |
| X-Generic     | 1         | 0.69%   |
| X-Cinnamon    | 1         | 0.69%   |
| LXQt          | 1         | 0.69%   |
| Enlightenment | 1         | 0.69%   |
| awesome       | 1         | 0.69%   |
| 2bwm          | 1         | 0.69%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 95        | 65.07%  |
| Tty     | 33        | 22.6%   |
| Unknown | 11        | 7.53%   |
| Wayland | 7         | 4.79%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 58        | 39.73%  |
| SDDM    | 50        | 34.25%  |
| XDM     | 32        | 21.92%  |
| LightDM | 3         | 2.05%   |
| SLiM    | 2         | 1.37%   |
| GDM     | 1         | 0.68%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 73        | 51.41%  |
| Unknown     | 42        | 29.58%  |
| ru_RU       | 4         | 2.82%   |
| it_IT       | 4         | 2.82%   |
| pt_BR       | 3         | 2.11%   |
| fr_FR       | 3         | 2.11%   |
| en_GB       | 3         | 2.11%   |
| de_DE       | 2         | 1.41%   |
| sr_RS@latin | 1         | 0.7%    |
| pt_PT       | 1         | 0.7%    |
| pl_PL       | 1         | 0.7%    |
| es_ES.UTF8  | 1         | 0.7%    |
| es_ES       | 1         | 0.7%    |
| en_US.ASCII | 1         | 0.7%    |
| en_AU       | 1         | 0.7%    |
| C           | 1         | 0.7%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 76        | 53.15%  |
| EFI  | 67        | 46.85%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 103       | 72.54%  |
| Btrfs    | 15        | 10.56%  |
| Xfs      | 7         | 4.93%   |
| Overlay  | 7         | 4.93%   |
| Rootfs   | 3         | 2.11%   |
| Zfs      | 1         | 0.7%    |
| Tmpfs    | 1         | 0.7%    |
| Reiserfs | 1         | 0.7%    |
| Jfs      | 1         | 0.7%    |
| F2fs     | 1         | 0.7%    |
| Ext3     | 1         | 0.7%    |
| Ext2     | 1         | 0.7%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 98        | 67.59%  |
| MBR     | 35        | 24.14%  |
| Unknown | 12        | 8.28%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 96        | 66.21%  |
| Yes       | 49        | 33.79%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 94        | 66.2%   |
| Yes       | 48        | 33.8%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 25        | 17.61%  |
| Hewlett-Packard     | 24        | 16.9%   |
| Lenovo              | 18        | 12.68%  |
| Dell                | 14        | 9.86%   |
| MSI                 | 12        | 8.45%   |
| ASRock              | 10        | 7.04%   |
| Gigabyte Technology | 5         | 3.52%   |
| Acer                | 5         | 3.52%   |
| Toshiba             | 3         | 2.11%   |
| Notebook            | 2         | 1.41%   |
| Fujitsu             | 2         | 1.41%   |
| Dynabook            | 2         | 1.41%   |
| Apple               | 2         | 1.41%   |
| Unknown             | 2         | 1.41%   |
| Valve               | 1         | 0.7%    |
| TYAN Computer       | 1         | 0.7%    |
| System76            | 1         | 0.7%    |
| Supermicro          | 1         | 0.7%    |
| Sony                | 1         | 0.7%    |
| Shuttle             | 1         | 0.7%    |
| Samsung Electronics | 1         | 0.7%    |
| Radxa               | 1         | 0.7%    |
| NetGear             | 1         | 0.7%    |
| Intel               | 1         | 0.7%    |
| Huanan              | 1         | 0.7%    |
| HPE                 | 1         | 0.7%    |
| Framework           | 1         | 0.7%    |
| Foxconn             | 1         | 0.7%    |
| Biostar             | 1         | 0.7%    |
| AMI                 | 1         | 0.7%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| ASUS All Series                          | 4         | 2.82%   |
| ASUS VivoBook_ASUSLaptop K6500ZE_K6500ZE | 2         | 1.41%   |
| Unknown                                  | 2         | 1.41%   |
| Valve Jupiter                            | 1         | 0.7%    |
| TYAN S7012                               | 1         | 0.7%    |
| Toshiba Satellite P50-A-12Z              | 1         | 0.7%    |
| Toshiba Satellite C660                   | 1         | 0.7%    |
| Toshiba PORTEGE Z30-A                    | 1         | 0.7%    |
| System76 Oryx Pro                        | 1         | 0.7%    |
| Supermicro X9DA7/E                       | 1         | 0.7%    |
| Sony SVE1713A1EW                         | 1         | 0.7%    |
| Shuttle NC03U                            | 1         | 0.7%    |
| Samsung 300E5M/300E5L                    | 1         | 0.7%    |
| Radxa ROCK Pi 4                          | 1         | 0.7%    |
| Notebook X170KM-G                        | 1         | 0.7%    |
| Notebook NL40_50CU                       | 1         | 0.7%    |
| NetGear ReadyDATA 5200                   | 1         | 0.7%    |
| MSI MS-7C52                              | 1         | 0.7%    |
| MSI MS-7C02                              | 1         | 0.7%    |
| MSI MS-7996                              | 1         | 0.7%    |
| MSI MS-7788                              | 1         | 0.7%    |
| MSI MS-7693                              | 1         | 0.7%    |
| MSI MS-7529                              | 1         | 0.7%    |
| MSI MS-7365                              | 1         | 0.7%    |
| MSI Modern 14 B11MO                      | 1         | 0.7%    |
| MSI Modern 14 B10MW                      | 1         | 0.7%    |
| MSI GP76 Leopard 11UG                    | 1         | 0.7%    |
| MSI GL73 8RC                             | 1         | 0.7%    |
| MSI GE76 Raider 11UE                     | 1         | 0.7%    |
| Lenovo V330-14ARR 81B1                   | 1         | 0.7%    |
| Lenovo ThinkPad X230 2325P38             | 1         | 0.7%    |
| Lenovo ThinkPad X140e 20BMS03E00         | 1         | 0.7%    |
| Lenovo ThinkPad X1 Carbon 7th 20R10015US | 1         | 0.7%    |
| Lenovo ThinkPad X1 Carbon 5th 20HQS04300 | 1         | 0.7%    |
| Lenovo ThinkPad T61 765912G              | 1         | 0.7%    |
| Lenovo ThinkPad T470p 20J60018MS         | 1         | 0.7%    |
| Lenovo ThinkPad T470 20JNS01R01          | 1         | 0.7%    |
| Lenovo ThinkPad T470 20HDCTO1WW          | 1         | 0.7%    |
| Lenovo ThinkPad T450s 20BW000EUS         | 1         | 0.7%    |
| Lenovo ThinkPad T410 2518C3U             | 1         | 0.7%    |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 14        | 9.86%   |
| Dell Precision    | 5         | 3.52%   |
| ASUS PRIME        | 5         | 3.52%   |
| HP Pavilion       | 4         | 2.82%   |
| ASUS ROG          | 4         | 2.82%   |
| ASUS All          | 4         | 2.82%   |
| HP Laptop         | 3         | 2.11%   |
| HP EliteBook      | 3         | 2.11%   |
| Dell Latitude     | 3         | 2.11%   |
| ASUS VivoBook     | 3         | 2.11%   |
| Toshiba Satellite | 2         | 1.41%   |
| MSI Modern        | 2         | 1.41%   |
| Lenovo IdeaPad    | 2         | 1.41%   |
| HP OMEN           | 2         | 1.41%   |
| Fujitsu LIFEBOOK  | 2         | 1.41%   |
| Dell PowerEdge    | 2         | 1.41%   |
| Dell OptiPlex     | 2         | 1.41%   |
| ASUS TUF          | 2         | 1.41%   |
| Acer Aspire       | 2         | 1.41%   |
| Unknown           | 2         | 1.41%   |
| Valve Jupiter     | 1         | 0.7%    |
| TYAN S7012        | 1         | 0.7%    |
| Toshiba PORTEGE   | 1         | 0.7%    |
| System76 Oryx     | 1         | 0.7%    |
| Supermicro X9DA7  | 1         | 0.7%    |
| Sony SVE1713A1EW  | 1         | 0.7%    |
| Shuttle NC03U     | 1         | 0.7%    |
| Samsung 300E5M    | 1         | 0.7%    |
| Radxa ROCK        | 1         | 0.7%    |
| Notebook X170KM-G | 1         | 0.7%    |
| Notebook NL40     | 1         | 0.7%    |
| NetGear ReadyDATA | 1         | 0.7%    |
| MSI MS-7C52       | 1         | 0.7%    |
| MSI MS-7C02       | 1         | 0.7%    |
| MSI MS-7996       | 1         | 0.7%    |
| MSI MS-7788       | 1         | 0.7%    |
| MSI MS-7693       | 1         | 0.7%    |
| MSI MS-7529       | 1         | 0.7%    |
| MSI MS-7365       | 1         | 0.7%    |
| MSI GP76          | 1         | 0.7%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 17        | 11.97%  |
| 2020    | 13        | 9.15%   |
| 2017    | 12        | 8.45%   |
| 2012    | 12        | 8.45%   |
| 2018    | 11        | 7.75%   |
| 2021    | 10        | 7.04%   |
| 2015    | 10        | 7.04%   |
| 2014    | 9         | 6.34%   |
| 2011    | 8         | 5.63%   |
| 2022    | 7         | 4.93%   |
| 2016    | 7         | 4.93%   |
| 2008    | 7         | 4.93%   |
| 2007    | 5         | 3.52%   |
| 2013    | 4         | 2.82%   |
| 2010    | 4         | 2.82%   |
| 2009    | 4         | 2.82%   |
| Unknown | 2         | 1.41%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 68        | 47.89%  |
| Desktop        | 64        | 45.07%  |
| Mini pc        | 3         | 2.11%   |
| Server         | 3         | 2.11%   |
| System on chip | 2         | 1.41%   |
| All in one     | 2         | 1.41%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 142       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 139       | 97.89%  |
| Yes  | 3         | 2.11%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 32        | 22.38%  |
| 4.01-8.0    | 26        | 18.18%  |
| 8.01-16.0   | 25        | 17.48%  |
| 3.01-4.0    | 22        | 15.38%  |
| 32.01-64.0  | 15        | 10.49%  |
| 64.01-256.0 | 10        | 6.99%   |
| 24.01-32.0  | 7         | 4.9%    |
| 1.01-2.0    | 5         | 3.5%    |
| 0.51-1.0    | 1         | 0.7%    |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 39        | 26.17%  |
| 2.01-3.0    | 35        | 23.49%  |
| 4.01-8.0    | 27        | 18.12%  |
| 3.01-4.0    | 15        | 10.07%  |
| 0.51-1.0    | 13        | 8.72%   |
| 8.01-16.0   | 6         | 4.03%   |
| 0.01-0.5    | 6         | 4.03%   |
| 16.01-24.0  | 4         | 2.68%   |
| 24.01-32.0  | 2         | 1.34%   |
| 32.01-64.0  | 1         | 0.67%   |
| 64.01-256.0 | 1         | 0.67%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 69        | 47.26%  |
| 2      | 31        | 21.23%  |
| 3      | 17        | 11.64%  |
| 4      | 10        | 6.85%   |
| 6      | 6         | 4.11%   |
| 5      | 5         | 3.42%   |
| 0      | 3         | 2.05%   |
| 13     | 1         | 0.68%   |
| 11     | 1         | 0.68%   |
| 9      | 1         | 0.68%   |
| 8      | 1         | 0.68%   |
| 7      | 1         | 0.68%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 85        | 59.44%  |
| Yes       | 58        | 40.56%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 131       | 92.25%  |
| No        | 11        | 7.75%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 96        | 67.13%  |
| No        | 47        | 32.87%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 87        | 61.27%  |
| No        | 55        | 38.73%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 33        | 23.24%  |
| UK           | 12        | 8.45%   |
| Germany      | 9         | 6.34%   |
| Brazil       | 9         | 6.34%   |
| Italy        | 8         | 5.63%   |
| Russia       | 7         | 4.93%   |
| Portugal     | 7         | 4.93%   |
| Kazakhstan   | 6         | 4.23%   |
| Canada       | 6         | 4.23%   |
| Japan        | 5         | 3.52%   |
| India        | 5         | 3.52%   |
| France       | 5         | 3.52%   |
| Sweden       | 4         | 2.82%   |
| Spain        | 3         | 2.11%   |
| South Africa | 3         | 2.11%   |
| Hong Kong    | 3         | 2.11%   |
| Greece       | 3         | 2.11%   |
| Serbia       | 2         | 1.41%   |
| Poland       | 2         | 1.41%   |
| Chile        | 2         | 1.41%   |
| Switzerland  | 1         | 0.7%    |
| Philippines  | 1         | 0.7%    |
| Netherlands  | 1         | 0.7%    |
| Mexico       | 1         | 0.7%    |
| Finland      | 1         | 0.7%    |
| Bulgaria     | 1         | 0.7%    |
| Australia    | 1         | 0.7%    |
| Argentina    | 1         | 0.7%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Lisbon                 | 6         | 4.08%   |
| Ust-Kamenogorsk        | 4         | 2.72%   |
| Yekaterinburg          | 3         | 2.04%   |
| Paris                  | 3         | 2.04%   |
| Chania                 | 3         | 2.04%   |
| Warsaw                 | 2         | 1.36%   |
| Tsukuba                | 2         | 1.36%   |
| Tendo                  | 2         | 1.36%   |
| Sun Prairie            | 2         | 1.36%   |
| New Delhi              | 2         | 1.36%   |
| Moscow                 | 2         | 1.36%   |
| Milan                  | 2         | 1.36%   |
| McKinney               | 2         | 1.36%   |
| Karaganda              | 2         | 1.36%   |
| Frignano               | 2         | 1.36%   |
| Fayetteville           | 2         | 1.36%   |
| Carrollton             | 2         | 1.36%   |
| Cape Town              | 2         | 1.36%   |
| Belgrade               | 2         | 1.36%   |
| Barry                  | 2         | 1.36%   |
| Barrie                 | 2         | 1.36%   |
| Worpswede              | 1         | 0.68%   |
| Wokingham              | 1         | 0.68%   |
| Winter Springs         | 1         | 0.68%   |
| Winnipeg               | 1         | 0.68%   |
| Weilheim               | 1         | 0.68%   |
| Warwick                | 1         | 0.68%   |
| Voskresensk            | 1         | 0.68%   |
| Visconde do Rio Branco | 1         | 0.68%   |
| Toronto                | 1         | 0.68%   |
| Tiffin                 | 1         | 0.68%   |
| Tatuí                 | 1         | 0.68%   |
| Stockholm              | 1         | 0.68%   |
| St Petersburg          | 1         | 0.68%   |
| St Louis               | 1         | 0.68%   |
| Springfield            | 1         | 0.68%   |
| Southend-on-Sea        | 1         | 0.68%   |
| Skövde                | 1         | 0.68%   |
| Shrewsbury             | 1         | 0.68%   |
| Sham Shui Po           | 1         | 0.68%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 43        | 87     | 18.86%  |
| Samsung Electronics | 38        | 57     | 16.67%  |
| Seagate             | 35        | 65     | 15.35%  |
| Toshiba             | 18        | 35     | 7.89%   |
| Kingston            | 10        | 13     | 4.39%   |
| Crucial             | 10        | 12     | 4.39%   |
| Hitachi             | 8         | 11     | 3.51%   |
| Intel               | 7         | 8      | 3.07%   |
| HGST                | 6         | 6      | 2.63%   |
| Unknown             | 5         | 5      | 2.19%   |
| SanDisk             | 5         | 6      | 2.19%   |
| SK hynix            | 4         | 4      | 1.75%   |
| A-DATA Technology   | 4         | 4      | 1.75%   |
| Micron Technology   | 3         | 3      | 1.32%   |
| Hewlett-Packard     | 3         | 4      | 1.32%   |
| Gigabyte Technology | 3         | 3      | 1.32%   |
| Transcend           | 2         | 2      | 0.88%   |
| Patriot             | 2         | 3      | 0.88%   |
| KIOXIA              | 2         | 2      | 0.88%   |
| China               | 2         | 3      | 0.88%   |
| Apple               | 2         | 3      | 0.88%   |
| ZHITAI              | 1         | 2      | 0.44%   |
| TO Exter            | 1         | 1      | 0.44%   |
| Team                | 1         | 1      | 0.44%   |
| Silicon Motion      | 1         | 1      | 0.44%   |
| PNY                 | 1         | 1      | 0.44%   |
| Plextor             | 1         | 1      | 0.44%   |
| Phison Electronics  | 1         | 1      | 0.44%   |
| Netac               | 1         | 1      | 0.44%   |
| Maxtor              | 1         | 1      | 0.44%   |
| JMicron Technology  | 1         | 1      | 0.44%   |
| Intenso             | 1         | 1      | 0.44%   |
| GOODRAM             | 1         | 1      | 0.44%   |
| Fujitsu             | 1         | 1      | 0.44%   |
| External            | 1         | 1      | 0.44%   |
| DUEX                | 1         | 1      | 0.44%   |
| Dogfish             | 1         | 1      | 0.44%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| WDC WD20EFRX-68EUZN0 2TB         | 3         | 1.07%   |
| WDC WD1003FZEX-00MK2A0 1TB       | 3         | 1.07%   |
| Samsung SSD 970 EVO 250GB        | 3         | 1.07%   |
| Kingston SA400S37240G 240GB SSD  | 3         | 1.07%   |
| WDC WDS100T2B0A-00SM50 1TB SSD   | 2         | 0.71%   |
| WDC WD30EZRX-00SPEB0 3TB         | 2         | 0.71%   |
| WDC WD10SPZX-60Z10T0 1TB         | 2         | 0.71%   |
| WDC WD10EZEX-08WN4A0 1TB         | 2         | 0.71%   |
| WDC WD10EZEX-00RKKA0 1TB         | 2         | 0.71%   |
| Toshiba MQ04ABF100 1TB           | 2         | 0.71%   |
| Toshiba MQ01ABD100 1TB           | 2         | 0.71%   |
| Seagate ST500DM002-1BD142 500GB  | 2         | 0.71%   |
| Seagate ST4000VN008-2DR166 4TB   | 2         | 0.71%   |
| Seagate ST4000DM004-2CV104 4TB   | 2         | 0.71%   |
| Seagate ST31000524AS 1TB         | 2         | 0.71%   |
| Seagate ST2000DM008-2FR102 2TB   | 2         | 0.71%   |
| Seagate ST2000DM001-1CH164 2TB   | 2         | 0.71%   |
| Seagate ST2000DL003-9VT166 2TB   | 2         | 0.71%   |
| Seagate ST1000DM010-2EP102 1TB   | 2         | 0.71%   |
| Seagate ST1000DM003-1SB102 1TB   | 2         | 0.71%   |
| Seagate ST1000DM003-1ER162 1TB   | 2         | 0.71%   |
| Seagate Expansion Desk 8TB       | 2         | 0.71%   |
| Samsung SSD 970 EVO Plus 1TB     | 2         | 0.71%   |
| Samsung SSD 860 QVO 2TB          | 2         | 0.71%   |
| Intel SSD 660P Series 512GB      | 2         | 0.71%   |
| HGST HTS725050A7E630 500GB       | 2         | 0.71%   |
| Crucial CT500MX500SSD1 500GB     | 2         | 0.71%   |
| ZHITAI SC001 Active 1TB SSD      | 1         | 0.36%   |
| ZHITAI PC005 Active 512GB        | 1         | 0.36%   |
| WDC WDS500G2B0B-00YS70 500GB SSD | 1         | 0.36%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 1         | 0.36%   |
| WDC WDS480G2G0A-00JH30 480GB SSD | 1         | 0.36%   |
| WDC WDS100T2B0C-00PXH0 1TB       | 1         | 0.36%   |
| WDC WDS100T2B0B-00YS70 1TB SSD   | 1         | 0.36%   |
| WDC WD7500BPVT-24HXZT3 752GB     | 1         | 0.36%   |
| WDC WD5003ABYX-18WERA0 500GB     | 1         | 0.36%   |
| WDC WD5000LPCX-60VHAT1 500GB     | 1         | 0.36%   |
| WDC WD5000BPVT-2 500GB           | 1         | 0.36%   |
| WDC WD5000BPKX-60HPJT0 500GB     | 1         | 0.36%   |
| WDC WD5000AAKX-22ERMA0 500GB     | 1         | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 37        | 77     | 33.64%  |
| Seagate             | 35        | 61     | 31.82%  |
| Toshiba             | 17        | 30     | 15.45%  |
| Hitachi             | 8         | 11     | 7.27%   |
| HGST                | 6         | 6      | 5.45%   |
| Samsung Electronics | 4         | 4      | 3.64%   |
| Maxtor              | 1         | 1      | 0.91%   |
| Hewlett-Packard     | 1         | 1      | 0.91%   |
| Fujitsu             | 1         | 1      | 0.91%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 18        | 28     | 25%     |
| Kingston            | 9         | 12     | 12.5%   |
| Crucial             | 8         | 10     | 11.11%  |
| WDC                 | 5         | 7      | 6.94%   |
| SanDisk             | 4         | 4      | 5.56%   |
| Transcend           | 2         | 2      | 2.78%   |
| Patriot             | 2         | 3      | 2.78%   |
| Intel               | 2         | 3      | 2.78%   |
| China               | 2         | 3      | 2.78%   |
| Apple               | 2         | 3      | 2.78%   |
| A-DATA Technology   | 2         | 2      | 2.78%   |
| ZHITAI              | 1         | 1      | 1.39%   |
| Toshiba             | 1         | 3      | 1.39%   |
| TO Exter            | 1         | 1      | 1.39%   |
| Team                | 1         | 1      | 1.39%   |
| SK hynix            | 1         | 1      | 1.39%   |
| PNY                 | 1         | 1      | 1.39%   |
| Plextor             | 1         | 1      | 1.39%   |
| Netac               | 1         | 1      | 1.39%   |
| Micron Technology   | 1         | 1      | 1.39%   |
| JMicron Technology  | 1         | 1      | 1.39%   |
| Intenso             | 1         | 1      | 1.39%   |
| Hewlett-Packard     | 1         | 1      | 1.39%   |
| GOODRAM             | 1         | 1      | 1.39%   |
| Gigabyte Technology | 1         | 1      | 1.39%   |
| DUEX                | 1         | 1      | 1.39%   |
| Dogfish             | 1         | 1      | 1.39%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 78        | 192    | 39.8%   |
| SSD     | 65        | 95     | 33.16%  |
| NVMe    | 47        | 57     | 23.98%  |
| MMC     | 5         | 5      | 2.55%   |
| Unknown | 1         | 4      | 0.51%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 109       | 279    | 65.66%  |
| NVMe | 46        | 56     | 27.71%  |
| SAS  | 6         | 13     | 3.61%   |
| MMC  | 5         | 5      | 3.01%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 78        | 118    | 46.43%  |
| 0.51-1.0   | 45        | 87     | 26.79%  |
| 1.01-2.0   | 17        | 24     | 10.12%  |
| 3.01-4.0   | 12        | 26     | 7.14%   |
| 2.01-3.0   | 8         | 19     | 4.76%   |
| 4.01-10.0  | 6         | 8      | 3.57%   |
| 10.01-20.0 | 2         | 5      | 1.19%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 32        | 22.07%  |
| 501-1000       | 32        | 22.07%  |
| 251-500        | 23        | 15.86%  |
| Unknown        | 17        | 11.72%  |
| 1001-2000      | 15        | 10.34%  |
| 1-20           | 8         | 5.52%   |
| 2001-3000      | 7         | 4.83%   |
| More than 3000 | 5         | 3.45%   |
| 21-50          | 3         | 2.07%   |
| 51-100         | 3         | 2.07%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 26        | 17.57%  |
| 1-20           | 24        | 16.22%  |
| 21-50          | 21        | 14.19%  |
| 501-1000       | 18        | 12.16%  |
| Unknown        | 17        | 11.49%  |
| 251-500        | 16        | 10.81%  |
| 51-100         | 16        | 10.81%  |
| 1001-2000      | 7         | 4.73%   |
| More than 3000 | 3         | 2.03%   |

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
| Works    | 113       | 241    | 65.32%  |
| Malfunc  | 35        | 53     | 20.23%  |
| Detected | 25        | 59     | 14.45%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 88        | 45.83%  |
| AMD                          | 34        | 17.71%  |
| Samsung Electronics          | 21        | 10.94%  |
| Marvell Technology Group     | 6         | 3.13%   |
| ASMedia Technology           | 6         | 3.13%   |
| SanDisk                      | 4         | 2.08%   |
| Nvidia                       | 4         | 2.08%   |
| SK hynix                     | 3         | 1.56%   |
| JMicron Technology           | 3         | 1.56%   |
| Broadcom / LSI               | 3         | 1.56%   |
| Realtek Semiconductor        | 2         | 1.04%   |
| Phison Electronics           | 2         | 1.04%   |
| Micron/Crucial Technology    | 2         | 1.04%   |
| Micron Technology            | 2         | 1.04%   |
| LSI Logic / Symbios Logic    | 2         | 1.04%   |
| KIOXIA                       | 2         | 1.04%   |
| Yangtze Memory Technologies  | 1         | 0.52%   |
| Toshiba America Info Systems | 1         | 0.52%   |
| Silicon Motion               | 1         | 0.52%   |
| Silicon Image                | 1         | 0.52%   |
| Kingston Technology Company  | 1         | 0.52%   |
| Biwin Storage Technology     | 1         | 0.52%   |
| Adaptec                      | 1         | 0.52%   |
| 3ware                        | 1         | 0.52%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 24        | 10.43%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 11        | 4.78%   |
| AMD 400 Series Chipset SATA Controller                                           | 10        | 4.35%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 7         | 3.04%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 6         | 2.61%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 6         | 2.61%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 5         | 2.17%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 5         | 2.17%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 4         | 1.74%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 4         | 1.74%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 1.74%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 4         | 1.74%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 3         | 1.3%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 1.3%    |
| Samsung NVMe SSD Controller 980                                                  | 3         | 1.3%    |
| Nvidia MCP61 SATA Controller                                                     | 3         | 1.3%    |
| Nvidia MCP61 IDE                                                                 | 3         | 1.3%    |
| Intel Volume Management Device NVMe RAID Controller                              | 3         | 1.3%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 3         | 1.3%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 3         | 1.3%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 3         | 1.3%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 3         | 1.3%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 1.3%    |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 2         | 0.87%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 2         | 0.87%   |
| Realtek NVMe Controller                                                          | 2         | 0.87%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 2         | 0.87%   |
| Micron NVMe Storage Controller                                                   | 2         | 0.87%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                 | 2         | 0.87%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 2         | 0.87%   |
| JMicron JMB58x AHCI SATA controller                                              | 2         | 0.87%   |
| Intel SSD 660P Series                                                            | 2         | 0.87%   |
| Intel SSD 600P Series                                                            | 2         | 0.87%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 2         | 0.87%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 2         | 0.87%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 2         | 0.87%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                              | 2         | 0.87%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 2         | 0.87%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 2         | 0.87%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                             | 2         | 0.87%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 105       | 54.69%  |
| NVMe | 46        | 23.96%  |
| IDE  | 20        | 10.42%  |
| RAID | 14        | 7.29%   |
| SAS  | 4         | 2.08%   |
| SCSI | 3         | 1.56%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 102       | 71.83%  |
| AMD    | 38        | 26.76%  |
| ARM    | 2         | 1.41%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 4         | 2.8%    |
| AMD Ryzen 5 3600 6-Core Processor             | 4         | 2.8%    |
| Intel 12th Gen Core i7-12700H                 | 3         | 2.1%    |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz            | 2         | 1.4%    |
| Intel Core i7-4790K CPU @ 4.00GHz             | 2         | 1.4%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1.4%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 1.4%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 1.4%    |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 1.4%    |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 2         | 1.4%    |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 2         | 1.4%    |
| Intel Celeron CPU N3060 @ 1.60GHz             | 2         | 1.4%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 1.4%    |
| ARM Processor                                 | 2         | 1.4%    |
| AMD Ryzen 7 3800X 8-Core Processor            | 2         | 1.4%    |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 2         | 1.4%    |
| AMD FX-8350 Eight-Core Processor              | 2         | 1.4%    |
| Intel Xeon CPU X5680 @ 3.33GHz                | 1         | 0.7%    |
| Intel Xeon CPU X5355 @ 2.66GHz                | 1         | 0.7%    |
| Intel Xeon CPU X3450 @ 2.67GHz                | 1         | 0.7%    |
| Intel Xeon CPU E5-2697 v3 @ 2.60GHz           | 1         | 0.7%    |
| Intel Xeon CPU E5-2667 v2 @ 3.30GHz           | 1         | 0.7%    |
| Intel Xeon CPU E5-2660 v3 @ 2.60GHz           | 1         | 0.7%    |
| Intel Xeon CPU E5-2620 0 @ 2.00GHz            | 1         | 0.7%    |
| Intel Xeon CPU E5-2407 0 @ 2.20GHz            | 1         | 0.7%    |
| Intel Xeon CPU E5-1650 0 @ 3.20GHz            | 1         | 0.7%    |
| Intel Xeon CPU E3-1246 v3 @ 3.50GHz           | 1         | 0.7%    |
| Intel Xeon CPU 5160 @ 3.00GHz                 | 1         | 0.7%    |
| Intel Pentium Gold G5420 CPU @ 3.80GHz        | 1         | 0.7%    |
| Intel Pentium Dual CPU E2140 @ 1.60GHz        | 1         | 0.7%    |
| Intel Pentium CPU P6100 @ 2.00GHz             | 1         | 0.7%    |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.7%    |
| Intel Pentium CPU G640 @ 2.80GHz              | 1         | 0.7%    |
| Intel Pentium CPU G4560 @ 3.50GHz             | 1         | 0.7%    |
| Intel Pentium CPU 2020M @ 2.40GHz             | 1         | 0.7%    |
| Intel CPU Version                             | 1         | 0.7%    |
| Intel Core M-5Y51 CPU @ 1.10GHz               | 1         | 0.7%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 0.7%    |
| Intel Core i7-9700 CPU @ 3.00GHz              | 1         | 0.7%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 0.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model              | Computers | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 25        | 17.48%  |
| Intel Core i7      | 22        | 15.38%  |
| Other              | 16        | 11.19%  |
| Intel Xeon         | 13        | 9.09%   |
| AMD Ryzen 5        | 11        | 7.69%   |
| Intel Core i3      | 7         | 4.9%    |
| Intel Core 2 Duo   | 6         | 4.2%    |
| Intel Pentium      | 5         | 3.5%    |
| AMD Ryzen 9        | 5         | 3.5%    |
| AMD FX             | 5         | 3.5%    |
| Intel Celeron      | 4         | 2.8%    |
| AMD Ryzen 7        | 4         | 2.8%    |
| Intel Core 2 Quad  | 2         | 1.4%    |
| Intel Atom         | 2         | 1.4%    |
| Intel Pentium Gold | 1         | 0.7%    |
| Intel Pentium Dual | 1         | 0.7%    |
| Intel Core M       | 1         | 0.7%    |
| Intel Core 2       | 1         | 0.7%    |
| AMD Ryzen Embedded | 1         | 0.7%    |
| AMD Ryzen 7 PRO    | 1         | 0.7%    |
| AMD Ryzen 3        | 1         | 0.7%    |
| AMD GX             | 1         | 0.7%    |
| AMD EPYC           | 1         | 0.7%    |
| AMD E1             | 1         | 0.7%    |
| AMD Athlon II X2   | 1         | 0.7%    |
| AMD Athlon 64 X2   | 1         | 0.7%    |
| AMD Athlon         | 1         | 0.7%    |
| AMD A8             | 1         | 0.7%    |
| AMD A4             | 1         | 0.7%    |
| AMD A10            | 1         | 0.7%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 48        | 33.57%  |
| 4      | 46        | 32.17%  |
| 8      | 16        | 11.19%  |
| 6      | 15        | 10.49%  |
| 16     | 4         | 2.8%    |
| 14     | 4         | 2.8%    |
| 12     | 4         | 2.8%    |
| 1      | 3         | 2.1%    |
| 10     | 2         | 1.4%    |
| 3      | 1         | 0.7%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 134       | 94.37%  |
| 2      | 8         | 5.63%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 104       | 73.24%  |
| 1      | 38        | 26.76%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 139       | 97.89%  |
| Unknown        | 2         | 1.41%   |
| 32-bit         | 1         | 0.7%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 30        | 21.13%  |
| 0x306a9    | 9         | 6.34%   |
| 0x306c3    | 6         | 4.23%   |
| 0x206d7    | 5         | 3.52%   |
| 0x806d1    | 4         | 2.82%   |
| 0x306d4    | 4         | 2.82%   |
| 0x1067a    | 4         | 2.82%   |
| 0x08701021 | 4         | 2.82%   |
| 0x906a3    | 3         | 2.11%   |
| 0x806ec    | 3         | 2.11%   |
| 0x806ea    | 3         | 2.11%   |
| 0x806c1    | 3         | 2.11%   |
| 0x406e3    | 3         | 2.11%   |
| 0x406c4    | 3         | 2.11%   |
| 0x206a7    | 3         | 2.11%   |
| 0x08701013 | 3         | 2.11%   |
| 0x08108109 | 3         | 2.11%   |
| 0x906ed    | 2         | 1.41%   |
| 0x906ea    | 2         | 1.41%   |
| 0x6fd      | 2         | 1.41%   |
| 0x506e3    | 2         | 1.41%   |
| 0x306f2    | 2         | 1.41%   |
| 0x20655    | 2         | 1.41%   |
| 0x106c2    | 2         | 1.41%   |
| 0x0a50000c | 2         | 1.41%   |
| 0x0a201016 | 2         | 1.41%   |
| 0x0810100b | 2         | 1.41%   |
| 0x06001119 | 2         | 1.41%   |
| 0x06000822 | 2         | 1.41%   |
| 0xa0671    | 1         | 0.7%    |
| 0xa0660    | 1         | 0.7%    |
| 0xa0653    | 1         | 0.7%    |
| 0xa0652    | 1         | 0.7%    |
| 0x906e9    | 1         | 0.7%    |
| 0x906a4    | 1         | 0.7%    |
| 0x806e9    | 1         | 0.7%    |
| 0x706a1    | 1         | 0.7%    |
| 0x6fb      | 1         | 0.7%    |
| 0x6fa      | 1         | 0.7%    |
| 0x40651    | 1         | 0.7%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 19        | 13.38%  |
| Zen 2            | 12        | 8.45%   |
| Haswell          | 12        | 8.45%   |
| IvyBridge        | 10        | 7.04%   |
| SandyBridge      | 9         | 6.34%   |
| Core             | 8         | 5.63%   |
| Skylake          | 7         | 4.93%   |
| Piledriver       | 6         | 4.23%   |
| Zen+             | 5         | 3.52%   |
| Westmere         | 5         | 3.52%   |
| Penryn           | 5         | 3.52%   |
| Icelake          | 5         | 3.52%   |
| Zen 3            | 4         | 2.82%   |
| Zen              | 4         | 2.82%   |
| Silvermont       | 4         | 2.82%   |
| Broadwell        | 4         | 2.82%   |
| Alderlake Hybrid | 4         | 2.82%   |
| TigerLake        | 3         | 2.11%   |
| CometLake        | 3         | 2.11%   |
| Unknown          | 3         | 2.11%   |
| Jaguar           | 2         | 1.41%   |
| Bonnell          | 2         | 1.41%   |
| Puma             | 1         | 0.7%    |
| Nehalem          | 1         | 0.7%    |
| K8 Hammer        | 1         | 0.7%    |
| K10              | 1         | 0.7%    |
| Goldmont plus    | 1         | 0.7%    |
| Bulldozer        | 1         | 0.7%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 68        | 43.31%  |
| Nvidia                     | 47        | 29.94%  |
| AMD                        | 38        | 24.2%   |
| Matrox Electronics Systems | 4         | 2.55%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 6         | 3.68%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 3.07%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 3.07%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 4         | 2.45%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 2.45%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 2.45%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 2.45%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 3         | 1.84%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 3         | 1.84%   |
| Intel UHD Graphics 620                                                                   | 3         | 1.84%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 1.84%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 1.84%   |
| Intel HD Graphics 620                                                                    | 3         | 1.84%   |
| Intel HD Graphics 5500                                                                   | 3         | 1.84%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 1.84%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 3         | 1.84%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 1.84%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 1.84%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 1.23%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 1.23%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 1.23%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 2         | 1.23%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 2         | 1.23%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 1.23%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 1.23%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 1.23%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.23%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 1.23%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2         | 1.23%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.23%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 1.23%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 2         | 1.23%   |
| AMD Renoir                                                                               | 2         | 1.23%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 2         | 1.23%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 2         | 1.23%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2         | 1.23%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.61%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1         | 0.61%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 1         | 0.61%   |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 53        | 37.32%  |
| 1 x AMD        | 35        | 24.65%  |
| 1 x Nvidia     | 28        | 19.72%  |
| Intel + Nvidia | 15        | 10.56%  |
| 1 x Matrox     | 4         | 2.82%   |
| Other          | 3         | 2.11%   |
| AMD + Nvidia   | 2         | 1.41%   |
| 2 x Nvidia     | 1         | 0.7%    |
| 2 x AMD        | 1         | 0.7%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 106       | 74.65%  |
| Proprietary | 24        | 16.9%   |
| Unknown     | 12        | 8.45%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 76        | 53.15%  |
| 0.51-1.0   | 15        | 10.49%  |
| 1.01-2.0   | 13        | 9.09%   |
| 3.01-4.0   | 11        | 7.69%   |
| 0.01-0.5   | 11        | 7.69%   |
| 7.01-8.0   | 9         | 6.29%   |
| 5.01-6.0   | 4         | 2.8%    |
| 8.01-16.0  | 3         | 2.1%    |
| 2.01-3.0   | 1         | 0.7%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 17        | 11.64%  |
| BOE                     | 14        | 9.59%   |
| LG Display              | 13        | 8.9%    |
| Dell                    | 12        | 8.22%   |
| AU Optronics            | 12        | 8.22%   |
| Chimei Innolux          | 11        | 7.53%   |
| Hewlett-Packard         | 10        | 6.85%   |
| BenQ                    | 7         | 4.79%   |
| Lenovo                  | 5         | 3.42%   |
| Goldstar                | 5         | 3.42%   |
| Sharp                   | 4         | 2.74%   |
| Ancor Communications    | 4         | 2.74%   |
| Acer                    | 4         | 2.74%   |
| ASUSTek Computer        | 3         | 2.05%   |
| ViewSonic               | 2         | 1.37%   |
| Iiyama                  | 2         | 1.37%   |
| Xiaomi                  | 1         | 0.68%   |
| Wacom                   | 1         | 0.68%   |
| Valve                   | 1         | 0.68%   |
| Unknown                 | 1         | 0.68%   |
| UGD                     | 1         | 0.68%   |
| Toshiba                 | 1         | 0.68%   |
| Sony                    | 1         | 0.68%   |
| PANDA                   | 1         | 0.68%   |
| Panasonic               | 1         | 0.68%   |
| ONN                     | 1         | 0.68%   |
| NEC Computers           | 1         | 0.68%   |
| JVC                     | 1         | 0.68%   |
| IOD                     | 1         | 0.68%   |
| Gigabyte Technology     | 1         | 0.68%   |
| GDH                     | 1         | 0.68%   |
| Eizo                    | 1         | 0.68%   |
| DPC                     | 1         | 0.68%   |
| Chi Mei Optoelectronics | 1         | 0.68%   |
| Apple                   | 1         | 0.68%   |
| AOC                     | 1         | 0.68%   |
| Unknown                 | 1         | 0.68%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC416E 2880x1620 344x194mm 15.5-inch | 2         | 1.33%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 2         | 1.33%   |
| LG Display LCD Monitor LGD0353 1366x768 345x194mm 15.6-inch           | 2         | 1.33%   |
| Lenovo LCD Monitor LEN4035 1280x800 303x190mm 14.1-inch               | 2         | 1.33%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 1.33%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch         | 2         | 1.33%   |
| Xiaomi Mi TV XMD009A 2224x1668 341x192mm 15.4-inch                    | 1         | 0.67%   |
| Wacom Cintiq 22HDT WAC1037 1920x1080 476x268mm 21.5-inch              | 1         | 0.67%   |
| ViewSonic LCD Monitor VX2276 Series 1920x1080                         | 1         | 0.67%   |
| ViewSonic LCD Monitor VA2448 SERIES 1920x1080                         | 1         | 0.67%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 1         | 0.67%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 1         | 0.67%   |
| UGD LCD Monitor UGD1302 1920x1080 290x160mm 13.0-inch                 | 1         | 0.67%   |
| Toshiba TV TSB0206 1920x1080                                          | 1         | 0.67%   |
| Sony TV SNY8102 1360x768                                              | 1         | 0.67%   |
| Sharp LQ173M1JW05 SHP14EC 1920x1080 382x215mm 17.3-inch               | 1         | 0.67%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 1         | 0.67%   |
| Sharp LQ125T1JW02 SHP142F 2560x1440 277x155mm 12.5-inch               | 1         | 0.67%   |
| Sharp LCD Monitor SHP14C4 1920x1080 344x194mm 15.5-inch               | 1         | 0.67%   |
| Samsung Electronics SyncMaster SAM0578 1920x1080 476x268mm 21.5-inch  | 1         | 0.67%   |
| Samsung Electronics SyncMaster SAM04DF 1360x768 410x230mm 18.5-inch   | 1         | 0.67%   |
| Samsung Electronics SyncMaster SAM0428 1680x1050 459x296mm 21.5-inch  | 1         | 0.67%   |
| Samsung Electronics SyncMaster SAM03F2 1680x1050                      | 1         | 0.67%   |
| Samsung Electronics SyncMaster SAM03F0 1680x1050 433x271mm 20.1-inch  | 1         | 0.67%   |
| Samsung Electronics SyncMaster SAM0248 1280x1024 376x301mm 19.0-inch  | 1         | 0.67%   |
| Samsung Electronics SyncMaster SAM01AD 1600x1200 408x306mm 20.1-inch  | 1         | 0.67%   |
| Samsung Electronics SMS27A650 SAM082D 1920x1080 598x336mm 27.0-inch   | 1         | 0.67%   |
| Samsung Electronics SMS19A100 SAM0867 1366x768 410x230mm 18.5-inch    | 1         | 0.67%   |
| Samsung Electronics SM2333T SAM0736 1920x1080 477x268mm 21.5-inch     | 1         | 0.67%   |
| Samsung Electronics S24D390 SAM0B65 1920x1080 521x293mm 23.5-inch     | 1         | 0.67%   |
| Samsung Electronics S22D300 SAM0B3E 1920x1080 477x268mm 21.5-inch     | 1         | 0.67%   |
| Samsung Electronics LCD Monitor U28D590 3840x2160                     | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch  | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch  | 1         | 0.67%   |
| Samsung Electronics B2430L SAM0644 1920x1080 521x293mm 23.5-inch      | 1         | 0.67%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch               | 1         | 0.67%   |
| Panasonic VVX16T029D00 MEI96A2 2880x1620 344x193mm 15.5-inch          | 1         | 0.67%   |
| ONN 100002480 ONN0101 1920x1080 470x290mm 21.7-inch                   | 1         | 0.67%   |
| NEC Computers LCD2490WUXi NEC66CE 1920x1200 518x324mm 24.1-inch       | 1         | 0.67%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 65        | 45.45%  |
| 1366x768 (WXGA)    | 26        | 18.18%  |
| 1680x1050 (WSXGA+) | 7         | 4.9%    |
| 1280x1024 (SXGA)   | 7         | 4.9%    |
| 3840x2160 (4K)     | 6         | 4.2%    |
| 2560x1440 (QHD)    | 6         | 4.2%    |
| 1920x1200 (WUXGA)  | 4         | 2.8%    |
| 1600x900 (HD+)     | 4         | 2.8%    |
| 1280x800 (WXGA)    | 4         | 2.8%    |
| 3440x1440          | 2         | 1.4%    |
| 2880x1620          | 2         | 1.4%    |
| 1360x768           | 2         | 1.4%    |
| 800x1280           | 1         | 0.7%    |
| 3200x1080          | 1         | 0.7%    |
| 2288x1287          | 1         | 0.7%    |
| 2256x1504          | 1         | 0.7%    |
| 1920x540           | 1         | 0.7%    |
| 1600x1200          | 1         | 0.7%    |
| 1440x900 (WXGA+)   | 1         | 0.7%    |
| Unknown            | 1         | 0.7%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 32        | 21.77%  |
| 24      | 13        | 8.84%   |
| 21      | 13        | 8.84%   |
| 14      | 13        | 8.84%   |
| 27      | 11        | 7.48%   |
| 17      | 11        | 7.48%   |
| 13      | 10        | 6.8%    |
| 23      | 9         | 6.12%   |
| Unknown | 7         | 4.76%   |
| 22      | 4         | 2.72%   |
| 20      | 4         | 2.72%   |
| 18      | 4         | 2.72%   |
| 19      | 3         | 2.04%   |
| 12      | 3         | 2.04%   |
| 16      | 2         | 1.36%   |
| 142     | 1         | 0.68%   |
| 74      | 1         | 0.68%   |
| 72      | 1         | 0.68%   |
| 52      | 1         | 0.68%   |
| 34      | 1         | 0.68%   |
| 32      | 1         | 0.68%   |
| 11      | 1         | 0.68%   |
| 7       | 1         | 0.68%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 55        | 37.67%  |
| 501-600        | 30        | 20.55%  |
| 401-500        | 26        | 17.81%  |
| 351-400        | 13        | 8.9%    |
| 201-300        | 7         | 4.79%   |
| Unknown        | 7         | 4.79%   |
| 701-800        | 2         | 1.37%   |
| 1501-2000      | 2         | 1.37%   |
| More than 2000 | 1         | 0.68%   |
| 601-700        | 1         | 0.68%   |
| 1001-1500      | 1         | 0.68%   |
| 1-100          | 1         | 0.68%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 98        | 72.59%  |
| 16/10   | 17        | 12.59%  |
| 5/4     | 5         | 3.7%    |
| Unknown | 5         | 3.7%    |
| 3/2     | 3         | 2.22%   |
| 6/5     | 2         | 1.48%   |
| 4/3     | 1         | 0.74%   |
| 32/9    | 1         | 0.74%   |
| 21/9    | 1         | 0.74%   |
| 1.00    | 1         | 0.74%   |
| 0.67    | 1         | 0.74%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 34        | 23.45%  |
| 201-250        | 29        | 20%     |
| 81-90          | 21        | 14.48%  |
| 301-350        | 11        | 7.59%   |
| 151-200        | 10        | 6.9%    |
| 141-150        | 7         | 4.83%   |
| 121-130        | 7         | 4.83%   |
| Unknown        | 7         | 4.83%   |
| 251-300        | 6         | 4.14%   |
| More than 1000 | 4         | 2.76%   |
| 61-70          | 3         | 2.07%   |
| 71-80          | 2         | 1.38%   |
| 351-500        | 2         | 1.38%   |
| 51-60          | 1         | 0.69%   |
| 1-40           | 1         | 0.69%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 51        | 34.93%  |
| 101-120       | 39        | 26.71%  |
| 121-160       | 36        | 24.66%  |
| Unknown       | 7         | 4.79%   |
| 161-240       | 6         | 4.11%   |
| 1-50          | 4         | 2.74%   |
| More than 240 | 3         | 2.05%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 110       | 77.46%  |
| 2     | 16        | 11.27%  |
| 0     | 12        | 8.45%   |
| 3     | 3         | 2.11%   |
| 4     | 1         | 0.7%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 83        | 39.34%  |
| Realtek Semiconductor    | 71        | 33.65%  |
| Qualcomm Atheros         | 13        | 6.16%   |
| Broadcom                 | 11        | 5.21%   |
| Broadcom Limited         | 5         | 2.37%   |
| Ralink Technology        | 4         | 1.9%    |
| ASIX Electronics         | 4         | 1.9%    |
| TP-Link                  | 3         | 1.42%   |
| Nvidia                   | 3         | 1.42%   |
| MediaTek                 | 3         | 1.42%   |
| VIA Technologies         | 1         | 0.47%   |
| Sitecom Europe           | 1         | 0.47%   |
| Sierra Wireless          | 1         | 0.47%   |
| Ralink                   | 1         | 0.47%   |
| Qualcomm                 | 1         | 0.47%   |
| Micro Star International | 1         | 0.47%   |
| Mellanox Technologies    | 1         | 0.47%   |
| Marvell Technology Group | 1         | 0.47%   |
| Hewlett-Packard          | 1         | 0.47%   |
| Dell                     | 1         | 0.47%   |
| Chelsio Communications   | 1         | 0.47%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 50        | 19.53%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 3.13%   |
| Intel I211 Gigabit Network Connection                             | 7         | 2.73%   |
| Intel Wi-Fi 6 AX200                                               | 6         | 2.34%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 2.34%   |
| Intel Wireless 8265 / 8275                                        | 5         | 1.95%   |
| Intel 82574L Gigabit Network Connection                           | 5         | 1.95%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.56%   |
| Ralink MT7601U Wireless Adapter                                   | 4         | 1.56%   |
| Intel Wireless-AC 9260                                            | 4         | 1.56%   |
| Intel Wireless 7260                                               | 4         | 1.56%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 4         | 1.56%   |
| Intel Ethernet Connection (2) I218-V                              | 4         | 1.56%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 3         | 1.17%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 1.17%   |
| Intel Wireless 8260                                               | 3         | 1.17%   |
| Intel Wireless 7265                                               | 3         | 1.17%   |
| Intel I350 Gigabit Network Connection                             | 3         | 1.17%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 1.17%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 1.17%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.78%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 2         | 0.78%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 0.78%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 0.78%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 0.78%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.78%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 2         | 0.78%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 0.78%   |
| Nvidia MCP61 Ethernet                                             | 2         | 0.78%   |
| MediaTek Wi-Fi 6E MT7922 160MHz Wireless Network Adapter          | 2         | 0.78%   |
| Intel Wireless 3160                                               | 2         | 0.78%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 0.78%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 0.78%   |
| Intel Ethernet Controller I225-V                                  | 2         | 0.78%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 0.78%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.78%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 0.78%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.78%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.78%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.78%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 54        | 54%     |
| Realtek Semiconductor    | 15        | 15%     |
| Qualcomm Atheros         | 10        | 10%     |
| Ralink Technology        | 4         | 4%      |
| TP-Link                  | 3         | 3%      |
| MediaTek                 | 3         | 3%      |
| Broadcom Limited         | 3         | 3%      |
| Broadcom                 | 3         | 3%      |
| Sitecom Europe           | 1         | 1%      |
| Sierra Wireless          | 1         | 1%      |
| Ralink                   | 1         | 1%      |
| Micro Star International | 1         | 1%      |
| Dell                     | 1         | 1%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                                   | 6         | 5.94%   |
| Intel Wireless 8265 / 8275                                                            | 5         | 4.95%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 4         | 3.96%   |
| Ralink MT7601U Wireless Adapter                                                       | 4         | 3.96%   |
| Intel Wireless-AC 9260                                                                | 4         | 3.96%   |
| Intel Wireless 7260                                                                   | 4         | 3.96%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 4         | 3.96%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 3         | 2.97%   |
| Intel Wireless 8260                                                                   | 3         | 2.97%   |
| Intel Wireless 7265                                                                   | 3         | 2.97%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 3         | 2.97%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 3         | 2.97%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 2         | 1.98%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                               | 2         | 1.98%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 2         | 1.98%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                      | 2         | 1.98%   |
| MediaTek Wi-Fi 6E MT7922 160MHz Wireless Network Adapter                              | 2         | 1.98%   |
| Intel Wireless 3160                                                                   | 2         | 1.98%   |
| Intel Wi-Fi 6 AX201                                                                   | 2         | 1.98%   |
| Intel Tiger Lake PCH CNVi WiFi                                                        | 2         | 1.98%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 2         | 1.98%   |
| Intel Centrino Ultimate-N 6300                                                        | 2         | 1.98%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                                               | 2         | 1.98%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                           | 1         | 0.99%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                                                 | 1         | 0.99%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                            | 1         | 0.99%   |
| Sitecom Europe WL-113 rev 2 Wireless Network USB Adapter                              | 1         | 0.99%   |
| Sierra Wireless EM7305                                                                | 1         | 0.99%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                    | 1         | 0.99%   |
| Realtek RTL8723DE Wireless Network Adapter                                            | 1         | 0.99%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                       | 1         | 0.99%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                           | 1         | 0.99%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1         | 0.99%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                             | 1         | 0.99%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 1         | 0.99%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                        | 1         | 0.99%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 1         | 0.99%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                      | 1         | 0.99%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 0.99%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 1         | 0.99%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 65        | 44.83%  |
| Intel                    | 51        | 35.17%  |
| Broadcom                 | 9         | 6.21%   |
| Qualcomm Atheros         | 6         | 4.14%   |
| ASIX Electronics         | 4         | 2.76%   |
| Nvidia                   | 3         | 2.07%   |
| Broadcom Limited         | 2         | 1.38%   |
| VIA Technologies         | 1         | 0.69%   |
| Qualcomm                 | 1         | 0.69%   |
| Mellanox Technologies    | 1         | 0.69%   |
| Marvell Technology Group | 1         | 0.69%   |
| Chelsio Communications   | 1         | 0.69%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 50        | 32.47%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 5.19%   |
| Intel I211 Gigabit Network Connection                             | 7         | 4.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 3.9%    |
| Intel 82574L Gigabit Network Connection                           | 5         | 3.25%   |
| Intel Ethernet Connection (2) I218-V                              | 4         | 2.6%    |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 1.95%   |
| Intel I350 Gigabit Network Connection                             | 3         | 1.95%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1.3%    |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 1.3%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 1.3%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 1.3%    |
| Nvidia MCP61 Ethernet                                             | 2         | 1.3%    |
| Intel Ethernet Controller I225-V                                  | 2         | 1.3%    |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.3%    |
| Intel Ethernet Connection I217-V                                  | 2         | 1.3%    |
| Intel Ethernet Connection (7) I219-V                              | 2         | 1.3%    |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.3%    |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 1.3%    |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 1.3%    |
| Intel 82579V Gigabit Network Connection                           | 2         | 1.3%    |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.3%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 1.3%    |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 2         | 1.3%    |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 2         | 1.3%    |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 1.3%    |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1         | 0.65%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1         | 0.65%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.65%   |
| Qualcomm Fairphone 4 5G                                           | 1         | 0.65%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.65%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.65%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.65%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]             | 1         | 0.65%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.65%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.65%   |
| Intel Ethernet Connection (5) I219-V                              | 1         | 0.65%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.65%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 0.65%   |
| Intel Ethernet Connection (2) I218-LM                             | 1         | 0.65%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 131       | 57.46%  |
| WiFi     | 96        | 42.11%  |
| Modem    | 1         | 0.44%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 77        | 54.61%  |
| WiFi     | 64        | 45.39%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 77        | 53.47%  |
| 1     | 49        | 34.03%  |
| 3     | 6         | 4.17%   |
| 4     | 5         | 3.47%   |
| 0     | 5         | 3.47%   |
| 5     | 2         | 1.39%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 127       | 88.19%  |
| Yes  | 17        | 11.81%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 47        | 53.41%  |
| Cambridge Silicon Radio         | 13        | 14.77%  |
| Realtek Semiconductor           | 7         | 7.95%   |
| Broadcom                        | 6         | 6.82%   |
| IMC Networks                    | 4         | 4.55%   |
| Qualcomm Atheros Communications | 3         | 3.41%   |
| Micro Star International        | 2         | 2.27%   |
| Apple                           | 2         | 2.27%   |
| TP-Link                         | 1         | 1.14%   |
| Toshiba                         | 1         | 1.14%   |
| MediaTek                        | 1         | 1.14%   |
| Foxconn / Hon Hai               | 1         | 1.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 19        | 21.59%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 13        | 14.77%  |
| Intel AX201 Bluetooth                               | 6         | 6.82%   |
| Intel AX200 Bluetooth                               | 6         | 6.82%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 4.55%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 4         | 4.55%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 4.55%   |
| Intel AX210 Bluetooth                               | 4         | 4.55%   |
| Realtek Bluetooth Radio                             | 3         | 3.41%   |
| IMC Networks Wireless_Device                        | 3         | 3.41%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 2.27%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 2.27%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2         | 2.27%   |
| TP-Link UB500 Adapter                               | 1         | 1.14%   |
| Toshiba Askey Bluetooth Module                      | 1         | 1.14%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 1.14%   |
| Micro Star International Bluetooth Dongle           | 1         | 1.14%   |
| Micro Star International Bluetooth Device           | 1         | 1.14%   |
| MediaTek Wireless_Device                            | 1         | 1.14%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.14%   |
| Intel Bluetooth Device                              | 1         | 1.14%   |
| IMC Networks Bluetooth Radio                        | 1         | 1.14%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 1.14%   |
| Broadcom HP Portable SoftSailing                    | 1         | 1.14%   |
| Broadcom BCM20702A0                                 | 1         | 1.14%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.14%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 1         | 1.14%   |
| Apple Bluetooth USB Host Controller                 | 1         | 1.14%   |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 1         | 1.14%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 93        | 47.94%  |
| AMD                    | 43        | 22.16%  |
| Nvidia                 | 38        | 19.59%  |
| Creative Labs          | 7         | 3.61%   |
| C-Media Electronics    | 4         | 2.06%   |
| Texas Instruments      | 2         | 1.03%   |
| VIA Technologies       | 1         | 0.52%   |
| RME                    | 1         | 0.52%   |
| M-Audio                | 1         | 0.52%   |
| Kingston Technology    | 1         | 0.52%   |
| Generalplus Technology | 1         | 0.52%   |
| EGO SYStems            | 1         | 0.52%   |
| ASUSTek Computer       | 1         | 0.52%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 11        | 4.7%    |
| AMD Starship/Matisse HD Audio Controller                                                          | 11        | 4.7%    |
| AMD Family 17h/19h HD Audio Controller                                                            | 11        | 4.7%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 8         | 3.42%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 8         | 3.42%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 6         | 2.56%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 6         | 2.56%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 6         | 2.56%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 5         | 2.14%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 2.14%   |
| AMD FCH Azalia Controller                                                                         | 5         | 2.14%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 4         | 1.71%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 4         | 1.71%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 1.71%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 1.71%   |
| Intel Broadwell-U Audio Controller                                                                | 4         | 1.71%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 1.71%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 4         | 1.71%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 1.71%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 1.71%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 1.71%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 1.71%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 4         | 1.71%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1.28%   |
| Nvidia MCP61 High Definition Audio                                                                | 3         | 1.28%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 1.28%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 1.28%   |
| Nvidia Audio device                                                                               | 3         | 1.28%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 1.28%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 3         | 1.28%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 1.28%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.28%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus]   | 3         | 1.28%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 1.28%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 1.28%   |
| AMD Navi 10 HDMI Audio                                                                            | 3         | 1.28%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 3         | 1.28%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 2         | 0.85%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 0.85%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 2         | 0.85%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 29        | 19.59%  |
| Kingston            | 25        | 16.89%  |
| Samsung Electronics | 24        | 16.22%  |
| Corsair             | 13        | 8.78%   |
| Crucial             | 12        | 8.11%   |
| Unknown             | 9         | 6.08%   |
| Micron Technology   | 7         | 4.73%   |
| Team                | 4         | 2.7%    |
| Transcend           | 2         | 1.35%   |
| Smart               | 2         | 1.35%   |
| Ramaxel Technology  | 2         | 1.35%   |
| G.Skill             | 2         | 1.35%   |
| A-DATA Technology   | 2         | 1.35%   |
| Unknown             | 2         | 1.35%   |
| Strontium           | 1         | 0.68%   |
| Silicon Power       | 1         | 0.68%   |
| Patriot             | 1         | 0.68%   |
| Neo Forza           | 1         | 0.68%   |
| Nanya Technology    | 1         | 0.68%   |
| HPE                 | 1         | 0.68%   |
| Goodram             | 1         | 0.68%   |
| GLOWAY              | 1         | 0.68%   |
| Essencore Limited   | 1         | 0.68%   |
| Elpida              | 1         | 0.68%   |
| Avant               | 1         | 0.68%   |
| AMD                 | 1         | 0.68%   |
| A Force             | 1         | 0.68%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB DIMM SDRAM                             | 2         | 1.24%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s               | 2         | 1.24%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.24%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 2         | 1.24%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 1.24%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips LPDDR5 6400MT/s | 2         | 1.24%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 1.24%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.24%   |
| Corsair RAM CMZ32GX3M4X1600C10 8GB DIMM DDR3 1600MT/s            | 2         | 1.24%   |
| Unknown                                                          | 2         | 1.24%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                        | 1         | 0.62%   |
| Unknown RAM Module 4096MB DIMM DDR3 65535MT/s                    | 1         | 0.62%   |
| Unknown RAM Module 2GB DIMM DDR2 533MT/s                         | 1         | 0.62%   |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s                       | 1         | 0.62%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                           | 1         | 0.62%   |
| Unknown RAM Module 1024MB SODIMM SDRAM                           | 1         | 0.62%   |
| Unknown RAM Module 1024MB SODIMM DDR2 533MT/s                    | 1         | 0.62%   |
| Unknown RAM Module 1024MB DIMM DDR 800MT/s                       | 1         | 0.62%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                           | 1         | 0.62%   |
| Transcend RAM TS256MLQ72V6U 2GB DIMM DDR2 667MT/s                | 1         | 0.62%   |
| Transcend RAM JM1600KLN-8GK 4096MB DIMM DDR3 1600MT/s            | 1         | 0.62%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3733MT/s              | 1         | 0.62%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3600MT/s              | 1         | 0.62%   |
| Strontium RAM SRT4G86U1-P9H 4096MB DIMM DDR3 1333MT/s            | 1         | 0.62%   |
| Smart RAM SH5641G8FJ8NWRNSQG 8GB SODIMM DDR3 1600MT/s            | 1         | 0.62%   |
| Smart RAM SH564128FH8N6TNSQG 4GB DIMM DDR3 1600MT/s              | 1         | 0.62%   |
| SK hynix RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s          | 1         | 0.62%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                  | 1         | 0.62%   |
| SK hynix RAM HYMP512F72CP8N3-Y5 1024MB FB-DIMM DDR2 667MT/s      | 1         | 0.62%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 800MT/s             | 1         | 0.62%   |
| SK hynix RAM HMT41GV7BMR4A-H9 16GB DIMM 1333MT/s                 | 1         | 0.62%   |
| SK hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 2000MT/s             | 1         | 0.62%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.62%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.62%   |
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1333MT/s             | 1         | 0.62%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.62%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1333MT/s        | 1         | 0.62%   |
| SK hynix RAM HMT351R7CFR8A-H9 4GB DIMM DDR3 1333MT/s             | 1         | 0.62%   |
| SK hynix RAM HMT31GR7EFR4A 8192MB DIMM DDR3 1600MT/s             | 1         | 0.62%   |
| SK hynix RAM HMT31GR7BFR4A-H9 16GB DIMM 1333MT/s                 | 1         | 0.62%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 57        | 44.53%  |
| DDR3    | 48        | 37.5%   |
| DDR2    | 7         | 5.47%   |
| SDRAM   | 4         | 3.13%   |
| LPDDR5  | 3         | 2.34%   |
| LPDDR3  | 3         | 2.34%   |
| LPDDR4  | 2         | 1.56%   |
| Unknown | 2         | 1.56%   |
| DDR5    | 1         | 0.78%   |
| DDR     | 1         | 0.78%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 61        | 47.66%  |
| DIMM         | 61        | 47.66%  |
| Row Of Chips | 4         | 3.13%   |
| RIMM         | 1         | 0.78%   |
| FB-DIMM      | 1         | 0.78%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 54        | 38.3%   |
| 4096  | 43        | 30.5%   |
| 16384 | 17        | 12.06%  |
| 2048  | 14        | 9.93%   |
| 32768 | 7         | 4.96%   |
| 1024  | 6         | 4.26%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 34        | 24.46%  |
| 3200    | 17        | 12.23%  |
| 2667    | 15        | 10.79%  |
| 2400    | 12        | 8.63%   |
| 3600    | 8         | 5.76%   |
| 1333    | 8         | 5.76%   |
| 2133    | 5         | 3.6%    |
| 667     | 5         | 3.6%    |
| 3800    | 3         | 2.16%   |
| 1867    | 3         | 2.16%   |
| Unknown | 3         | 2.16%   |
| 6400    | 2         | 1.44%   |
| 2800    | 2         | 1.44%   |
| 2666    | 2         | 1.44%   |
| 1866    | 2         | 1.44%   |
| 1334    | 2         | 1.44%   |
| 975     | 2         | 1.44%   |
| 533     | 2         | 1.44%   |
| 65535   | 1         | 0.72%   |
| 4800    | 1         | 0.72%   |
| 4266    | 1         | 0.72%   |
| 4199    | 1         | 0.72%   |
| 3733    | 1         | 0.72%   |
| 2933    | 1         | 0.72%   |
| 2472    | 1         | 0.72%   |
| 2187    | 1         | 0.72%   |
| 2000    | 1         | 0.72%   |
| 1066    | 1         | 0.72%   |
| 800     | 1         | 0.72%   |
| 701     | 1         | 0.72%   |

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
| Canon CanoScan LiDE 300      | 1         | 11.11%  |
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
| Chicony Electronics                    | 19        | 25%     |
| Logitech                               | 12        | 15.79%  |
| Acer                                   | 7         | 9.21%   |
| Realtek Semiconductor                  | 5         | 6.58%   |
| Microdia                               | 5         | 6.58%   |
| IMC Networks                           | 4         | 5.26%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 5.26%   |
| Quanta                                 | 3         | 3.95%   |
| Lite-On Technology                     | 3         | 3.95%   |
| Sunplus Innovation Technology          | 2         | 2.63%   |
| Sonix Technology                       | 2         | 2.63%   |
| Luxvisions Innotech Limited            | 2         | 2.63%   |
| Syntek                                 | 1         | 1.32%   |
| Silicon Motion                         | 1         | 1.32%   |
| Samsung Electronics                    | 1         | 1.32%   |
| Motorola PCS                           | 1         | 1.32%   |
| Microsoft                              | 1         | 1.32%   |
| Lenovo                                 | 1         | 1.32%   |
| Bison Electronics                      | 1         | 1.32%   |
| Apple                                  | 1         | 1.32%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 4         | 5.26%   |
| Logitech Webcam C270                                 | 3         | 3.95%   |
| Acer HD Webcam                                       | 3         | 3.95%   |
| Acer BisonCam,NB Pro                                 | 3         | 3.95%   |
| Sonix USB2.0 FHD UVC WebCam                          | 2         | 2.63%   |
| Quanta HP Webcam                                     | 2         | 2.63%   |
| Chicony FJ Camera                                    | 2         | 2.63%   |
| Syntek USB2.0 Camera                                 | 1         | 1.32%   |
| Sunplus Laptop_Integrated_Webcam_FHD                 | 1         | 1.32%   |
| Sunplus Integrated_Webcam_HD                         | 1         | 1.32%   |
| Silicon Motion Web Camera                            | 1         | 1.32%   |
| Samsung Galaxy A5 (MTP)                              | 1         | 1.32%   |
| Realtek USB2.0-Camera                                | 1         | 1.32%   |
| Realtek USB Camera                                   | 1         | 1.32%   |
| Realtek Laptop Camera                                | 1         | 1.32%   |
| Realtek Integrated Camera                            | 1         | 1.32%   |
| Realtek EasyCamera                                   | 1         | 1.32%   |
| Quanta HP Wide Vision HD Camera                      | 1         | 1.32%   |
| Motorola PCS XT1033 [Moto G], PTP mode               | 1         | 1.32%   |
| Microsoft LifeCam HD-3000                            | 1         | 1.32%   |
| Microdia Laptop_Integrated_Webcam_2M                 | 1         | 1.32%   |
| Microdia Integrated_Webcam_HD                        | 1         | 1.32%   |
| Microdia Integrated Webcam                           | 1         | 1.32%   |
| Microdia Dell Integrated HD Webcam                   | 1         | 1.32%   |
| Microdia Camera                                      | 1         | 1.32%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 1.32%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 1         | 1.32%   |
| Logitech Webcam C310                                 | 1         | 1.32%   |
| Logitech Webcam C300                                 | 1         | 1.32%   |
| Logitech Webcam C170                                 | 1         | 1.32%   |
| Logitech QuickCam Pro 9000                           | 1         | 1.32%   |
| Logitech Logitech Webcam C160                        | 1         | 1.32%   |
| Logitech HD Webcam C525                              | 1         | 1.32%   |
| Logitech HD Pro Webcam C920                          | 1         | 1.32%   |
| Logitech C922 Pro Stream Webcam                      | 1         | 1.32%   |
| Logitech C920 PRO HD Webcam                          | 1         | 1.32%   |
| Lite-On TOSHIBA Web Camera - FHD                     | 1         | 1.32%   |
| Lite-On Integrated Camera                            | 1         | 1.32%   |
| Lite-On HP TrueVision HD Camera                      | 1         | 1.32%   |
| Lenovo Integrated Webcam [R5U877]                    | 1         | 1.32%   |

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
| 0     | 86        | 59.31%  |
| 1     | 33        | 22.76%  |
| 2     | 15        | 10.34%  |
| 3     | 6         | 4.14%   |
| 4     | 5         | 3.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 21        | 22.34%  |
| Fingerprint reader       | 17        | 18.09%  |
| Sound                    | 12        | 12.77%  |
| Chipcard                 | 9         | 9.57%   |
| Net/wireless             | 8         | 8.51%   |
| Communication controller | 8         | 8.51%   |
| Card reader              | 4         | 4.26%   |
| Unassigned class         | 3         | 3.19%   |
| Bluetooth                | 3         | 3.19%   |
| Net/ethernet             | 2         | 2.13%   |
| Multimedia controller    | 2         | 2.13%   |
| Camera                   | 2         | 2.13%   |
| Storage/ata              | 1         | 1.06%   |
| Storage                  | 1         | 1.06%   |
| Firewire controller      | 1         | 1.06%   |

