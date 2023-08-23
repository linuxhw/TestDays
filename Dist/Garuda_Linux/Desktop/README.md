Garuda Linux - Tested Hardware & Statistics (Desktops)
------------------------------------------------------

A project to collect tested hardware configurations for Garuda Linux.

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

Total: 282

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASRock        | B450M-HDV R4.0              | [6855901c02](https://linux-hardware.org/?probe=6855901c02) | Aug 12, 2023 |
| HP            | 8433 11                     | [de06cea570](https://linux-hardware.org/?probe=de06cea570) | Aug 10, 2023 |
| HP            | 8433 11                     | [4275d43a74](https://linux-hardware.org/?probe=4275d43a74) | Aug 10, 2023 |
| Gigabyte      | B560 DS3H AC-Y1             | [af88e64084](https://linux-hardware.org/?probe=af88e64084) | Aug 04, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [88e9cc22bf](https://linux-hardware.org/?probe=88e9cc22bf) | Aug 03, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [52319a8cef](https://linux-hardware.org/?probe=52319a8cef) | Aug 03, 2023 |
| MSI           | B450 TOMAHAWK               | [6b736ced64](https://linux-hardware.org/?probe=6b736ced64) | Aug 03, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [a5467c396a](https://linux-hardware.org/?probe=a5467c396a) | Jul 28, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [3a59ab6dd1](https://linux-hardware.org/?probe=3a59ab6dd1) | Jul 26, 2023 |
| HP            | 18E7                        | [1638b42b8b](https://linux-hardware.org/?probe=1638b42b8b) | Jul 23, 2023 |
| HP            | 18E7                        | [909788f739](https://linux-hardware.org/?probe=909788f739) | Jul 23, 2023 |
| ASRock        | B250M Pro4                  | [9ce9a989dd](https://linux-hardware.org/?probe=9ce9a989dd) | Jul 23, 2023 |
| Biostar       | B350GT3                     | [41d95e4e81](https://linux-hardware.org/?probe=41d95e4e81) | Jul 22, 2023 |
| Alienware     | 07W25T A00                  | [24dade96af](https://linux-hardware.org/?probe=24dade96af) | Jul 21, 2023 |
| Shenzhen M... | HX90G                       | [f42afac191](https://linux-hardware.org/?probe=f42afac191) | Jul 15, 2023 |
| ASUSTek       | PRIME Z690-P D4             | [b91bb21dfc](https://linux-hardware.org/?probe=b91bb21dfc) | Jul 10, 2023 |
| HP            | 8053                        | [4241a715e6](https://linux-hardware.org/?probe=4241a715e6) | Jul 09, 2023 |
| ASRock        | B450M-HDV R4.0              | [f24ba1fb9c](https://linux-hardware.org/?probe=f24ba1fb9c) | Jul 09, 2023 |
| ASUSTek       | Rampage V EDITION 10        | [54611e82ec](https://linux-hardware.org/?probe=54611e82ec) | Jul 06, 2023 |
| Gigabyte      | Z490 GAMING X               | [5e8900dde2](https://linux-hardware.org/?probe=5e8900dde2) | Jul 02, 2023 |
| Gigabyte      | Z490 GAMING X               | [b819a1fb21](https://linux-hardware.org/?probe=b819a1fb21) | Jul 02, 2023 |
| ASRock        | X470 Taichi                 | [529873f796](https://linux-hardware.org/?probe=529873f796) | Jul 02, 2023 |
| HP            | 1998                        | [cee46b5772](https://linux-hardware.org/?probe=cee46b5772) | Jul 01, 2023 |
| Shenzhen M... | HX90G                       | [d1d0bb38d0](https://linux-hardware.org/?probe=d1d0bb38d0) | Jun 20, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [2278cd4d03](https://linux-hardware.org/?probe=2278cd4d03) | Jun 17, 2023 |
| Biostar       | B350GT3                     | [13b1026096](https://linux-hardware.org/?probe=13b1026096) | Jun 13, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [933978a1ae](https://linux-hardware.org/?probe=933978a1ae) | Jun 07, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [21b7236d20](https://linux-hardware.org/?probe=21b7236d20) | Jun 03, 2023 |
| Lenovo        | ThinkCentre M58p 6137AU8    | [bd80dea70f](https://linux-hardware.org/?probe=bd80dea70f) | May 29, 2023 |
| ASUSTek       | Rampage V EDITION 10        | [a7fbdc21bc](https://linux-hardware.org/?probe=a7fbdc21bc) | May 26, 2023 |
| Win elemen... | M600                        | [4c5d685663](https://linux-hardware.org/?probe=4c5d685663) | May 21, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [262bc7c88f](https://linux-hardware.org/?probe=262bc7c88f) | May 21, 2023 |
| Win elemen... | M600                        | [84de4a3207](https://linux-hardware.org/?probe=84de4a3207) | May 20, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [194f7f96e5](https://linux-hardware.org/?probe=194f7f96e5) | May 13, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [fda523de2a](https://linux-hardware.org/?probe=fda523de2a) | May 11, 2023 |
| ASUSTek       | Z170 PRO GAMING             | [3b4eb54186](https://linux-hardware.org/?probe=3b4eb54186) | May 08, 2023 |
| Intel         | DH67CL AAG10212-210         | [3f2fa70636](https://linux-hardware.org/?probe=3f2fa70636) | May 06, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [7a5a0f75aa](https://linux-hardware.org/?probe=7a5a0f75aa) | May 01, 2023 |
| Intel         | DH67CL AAG10212-210         | [7d6b0027b3](https://linux-hardware.org/?probe=7d6b0027b3) | Apr 30, 2023 |
| ASRock        | A320M-HD                    | [43b57e5088](https://linux-hardware.org/?probe=43b57e5088) | Apr 28, 2023 |
| Intel         | DH67CL AAG10212-210         | [cb87589d9f](https://linux-hardware.org/?probe=cb87589d9f) | Apr 28, 2023 |
| Shenzhen M... | F7BFC                       | [bb189b2507](https://linux-hardware.org/?probe=bb189b2507) | Apr 22, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [d9fd347989](https://linux-hardware.org/?probe=d9fd347989) | Apr 20, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [d5adb940b4](https://linux-hardware.org/?probe=d5adb940b4) | Apr 19, 2023 |
| Intel         | DH67CL AAG10212-210         | [8519b4cda2](https://linux-hardware.org/?probe=8519b4cda2) | Apr 15, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [424d545740](https://linux-hardware.org/?probe=424d545740) | Apr 14, 2023 |
| Acer          | Veriton K8-680G V:1.0       | [9ab3fc183a](https://linux-hardware.org/?probe=9ab3fc183a) | Apr 13, 2023 |
| Win elemen... | M600                        | [7723a03558](https://linux-hardware.org/?probe=7723a03558) | Apr 10, 2023 |
| Win elemen... | M600                        | [e20927ec15](https://linux-hardware.org/?probe=e20927ec15) | Apr 10, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | [e2521c6d93](https://linux-hardware.org/?probe=e2521c6d93) | Apr 09, 2023 |
| HP            | 8053                        | [9897b3e51f](https://linux-hardware.org/?probe=9897b3e51f) | Apr 04, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | [7a2bce56b1](https://linux-hardware.org/?probe=7a2bce56b1) | Mar 26, 2023 |
| HP            | 8053                        | [82eb90837f](https://linux-hardware.org/?probe=82eb90837f) | Mar 21, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [40372e4af3](https://linux-hardware.org/?probe=40372e4af3) | Mar 19, 2023 |
| MSI           | B450-A PRO MAX              | [15f0543609](https://linux-hardware.org/?probe=15f0543609) | Mar 19, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [9d10f13efc](https://linux-hardware.org/?probe=9d10f13efc) | Mar 18, 2023 |
| HP            | 8053                        | [273a6c822b](https://linux-hardware.org/?probe=273a6c822b) | Mar 12, 2023 |
| HP            | 8053                        | [be27383efc](https://linux-hardware.org/?probe=be27383efc) | Mar 11, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [51b92fb276](https://linux-hardware.org/?probe=51b92fb276) | Mar 11, 2023 |
| Dell          | 0VYXHD A00                  | [d7618c5b6c](https://linux-hardware.org/?probe=d7618c5b6c) | Mar 08, 2023 |
| ASUSTek       | BT6130                      | [3549cfad14](https://linux-hardware.org/?probe=3549cfad14) | Feb 27, 2023 |
| MSI           | MAG B760 TOMAHAWK WIFI D... | [575a7f4897](https://linux-hardware.org/?probe=575a7f4897) | Feb 26, 2023 |
| MSI           | MAG B760 TOMAHAWK WIFI D... | [466f8533fb](https://linux-hardware.org/?probe=466f8533fb) | Feb 26, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [fad109dc98](https://linux-hardware.org/?probe=fad109dc98) | Feb 25, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [a53235325f](https://linux-hardware.org/?probe=a53235325f) | Feb 23, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [bd6a746c89](https://linux-hardware.org/?probe=bd6a746c89) | Feb 20, 2023 |
| MSI           | B450-A PRO                  | [014bf5276e](https://linux-hardware.org/?probe=014bf5276e) | Feb 17, 2023 |
| ASUSTek       | BT6130                      | [db3b191eb2](https://linux-hardware.org/?probe=db3b191eb2) | Feb 13, 2023 |
| ASRock        | A520M-ITX/ac                | [a6e401a1d3](https://linux-hardware.org/?probe=a6e401a1d3) | Feb 09, 2023 |
| Intel         | X79M-S                      | [91ab5e33ed](https://linux-hardware.org/?probe=91ab5e33ed) | Feb 03, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [d6d4c6c38c](https://linux-hardware.org/?probe=d6d4c6c38c) | Jan 31, 2023 |
| ASUSTek       | PRIME Z490-A                | [91dbb8d045](https://linux-hardware.org/?probe=91dbb8d045) | Jan 26, 2023 |
| Intel         | X79M-S                      | [ccad523936](https://linux-hardware.org/?probe=ccad523936) | Jan 22, 2023 |
| ASUSTek       | PRIME A320M-A               | [918dbdb148](https://linux-hardware.org/?probe=918dbdb148) | Jan 22, 2023 |
| ASUSTek       | Rampage IV GENE             | [64553c4fd7](https://linux-hardware.org/?probe=64553c4fd7) | Jan 17, 2023 |
| MSI           | B450M PRO-VDH MAX           | [87e7a60bfa](https://linux-hardware.org/?probe=87e7a60bfa) | Jan 15, 2023 |
| ASUSTek       | CM6850                      | [7eac1c6a7a](https://linux-hardware.org/?probe=7eac1c6a7a) | Jan 13, 2023 |
| ASUSTek       | P8H61/USB3 R2.0             | [5e29a1afb7](https://linux-hardware.org/?probe=5e29a1afb7) | Jan 10, 2023 |
| ASUSTek       | P8H61/USB3 R2.0             | [8daa546122](https://linux-hardware.org/?probe=8daa546122) | Jan 09, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [919b259ea2](https://linux-hardware.org/?probe=919b259ea2) | Jan 09, 2023 |
| ASUSTek       | PRIME X570-P                | [95c21fc90e](https://linux-hardware.org/?probe=95c21fc90e) | Jan 09, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [d759bb7551](https://linux-hardware.org/?probe=d759bb7551) | Jan 08, 2023 |
| MSI           | H61M-E22/W8                 | [92280cb6ae](https://linux-hardware.org/?probe=92280cb6ae) | Jan 06, 2023 |
| ASUSTek       | PRIME B360M-C               | [7685480bf0](https://linux-hardware.org/?probe=7685480bf0) | Jan 05, 2023 |
| Intel         | X79M-S                      | [3b38d8023e](https://linux-hardware.org/?probe=3b38d8023e) | Jan 03, 2023 |
| Dell          | 0VHWTR A02                  | [0d9d6203e1](https://linux-hardware.org/?probe=0d9d6203e1) | Jan 03, 2023 |
| Intel         | X79M-S                      | [5c97a3976d](https://linux-hardware.org/?probe=5c97a3976d) | Jan 01, 2023 |
| ASUSTek       | TUF Gaming B660M-E D4       | [a294963db9](https://linux-hardware.org/?probe=a294963db9) | Jan 01, 2023 |
| Lenovo        | Win8 Pro DPK TPG            | [9561e51689](https://linux-hardware.org/?probe=9561e51689) | Dec 31, 2022 |
| Intel         | H61                         | [39f3cddffb](https://linux-hardware.org/?probe=39f3cddffb) | Dec 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [ee98173357](https://linux-hardware.org/?probe=ee98173357) | Dec 27, 2022 |
| ASRock        | X570 Taichi                 | [e48882ad67](https://linux-hardware.org/?probe=e48882ad67) | Dec 22, 2022 |
| ASUSTek       | PRIME Z390-P                | [1a9f9ac05f](https://linux-hardware.org/?probe=1a9f9ac05f) | Dec 22, 2022 |
| Lenovo        | Win8 Pro DPK TPG            | [7ce8a10de4](https://linux-hardware.org/?probe=7ce8a10de4) | Dec 21, 2022 |
| Lenovo        | Win8 Pro DPK TPG            | [a4c1397ad3](https://linux-hardware.org/?probe=a4c1397ad3) | Dec 21, 2022 |
| BESSTAR Te... | B550                        | [d9fbac807d](https://linux-hardware.org/?probe=d9fbac807d) | Dec 10, 2022 |
| ASRock        | Z77 Pro3                    | [a2e7958d4a](https://linux-hardware.org/?probe=a2e7958d4a) | Dec 08, 2022 |
| ASRock        | Z77 Pro3                    | [3184df2bf6](https://linux-hardware.org/?probe=3184df2bf6) | Dec 07, 2022 |
| Gigabyte      | 990FXA-UD3                  | [54d896b9ed](https://linux-hardware.org/?probe=54d896b9ed) | Dec 06, 2022 |
| MSI           | H510I PRO WIFI              | [f46e59c772](https://linux-hardware.org/?probe=f46e59c772) | Nov 27, 2022 |
| Dell          | 0K3CM7 A00                  | [27109cda18](https://linux-hardware.org/?probe=27109cda18) | Nov 20, 2022 |
| Dell          | 0K3CM7 A00                  | [6dbdd86e08](https://linux-hardware.org/?probe=6dbdd86e08) | Nov 20, 2022 |
| HP            | 8767 A                      | [375e0d4525](https://linux-hardware.org/?probe=375e0d4525) | Nov 19, 2022 |
| Gigabyte      | 990FXA-UD3                  | [985fb6d758](https://linux-hardware.org/?probe=985fb6d758) | Nov 16, 2022 |
| Dell          | 0K3CM7 A00                  | [3c426cb32b](https://linux-hardware.org/?probe=3c426cb32b) | Nov 14, 2022 |
| ASRock        | X470 Taichi                 | [7cd5f4c280](https://linux-hardware.org/?probe=7cd5f4c280) | Nov 05, 2022 |
| ASRock        | X470 Taichi                 | [d808be6d90](https://linux-hardware.org/?probe=d808be6d90) | Oct 31, 2022 |
| HP            | 2B2C                        | [6f90b1e25e](https://linux-hardware.org/?probe=6f90b1e25e) | Oct 26, 2022 |
| ASUSTek       | PRIME X570-P                | [5558f9e3f7](https://linux-hardware.org/?probe=5558f9e3f7) | Oct 23, 2022 |
| Acer          | Aspire TC-780               | [fd6c66dac7](https://linux-hardware.org/?probe=fd6c66dac7) | Oct 22, 2022 |
| ASUSTek       | PRIME X570-P                | [a7d6f0bd9e](https://linux-hardware.org/?probe=a7d6f0bd9e) | Oct 15, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [541e327f0f](https://linux-hardware.org/?probe=541e327f0f) | Oct 01, 2022 |
| ASUSTek       | PRIME X570-P                | [6647dc20ac](https://linux-hardware.org/?probe=6647dc20ac) | Sep 21, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [9d0697ec96](https://linux-hardware.org/?probe=9d0697ec96) | Sep 20, 2022 |
| ASRock        | A320M-HDV R4.0              | [afbb849b02](https://linux-hardware.org/?probe=afbb849b02) | Sep 11, 2022 |
| ASRock        | A320M-HDV R4.0              | [5e98f641f1](https://linux-hardware.org/?probe=5e98f641f1) | Sep 11, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [ac65980e25](https://linux-hardware.org/?probe=ac65980e25) | Sep 02, 2022 |
| Gigabyte      | F2A88XM-HD3                 | [44e355eb93](https://linux-hardware.org/?probe=44e355eb93) | Aug 30, 2022 |
| ASRock        | X470 Taichi                 | [7bc56eb3d4](https://linux-hardware.org/?probe=7bc56eb3d4) | Aug 25, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [57f1970999](https://linux-hardware.org/?probe=57f1970999) | Aug 20, 2022 |
| ASUSTek       | PRIME X570-P                | [fc5923b017](https://linux-hardware.org/?probe=fc5923b017) | Aug 15, 2022 |
| ASUSTek       | PRIME X570-P                | [e53bbe7c1b](https://linux-hardware.org/?probe=e53bbe7c1b) | Aug 14, 2022 |
| MSI           | A68HM-E33 V2                | [762f08a697](https://linux-hardware.org/?probe=762f08a697) | Aug 13, 2022 |
| ASRock        | A520M-HDV                   | [f23bdacb56](https://linux-hardware.org/?probe=f23bdacb56) | Aug 11, 2022 |
| ASUSTek       | Maximus IX FORMULA          | [2212732244](https://linux-hardware.org/?probe=2212732244) | Aug 01, 2022 |
| MSI           | B450M PRO-VDH MAX           | [941092ee95](https://linux-hardware.org/?probe=941092ee95) | Jul 26, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [dfe6047aa7](https://linux-hardware.org/?probe=dfe6047aa7) | Jul 21, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | [f9996d6494](https://linux-hardware.org/?probe=f9996d6494) | Jul 21, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [92fe4c2ff3](https://linux-hardware.org/?probe=92fe4c2ff3) | Jul 03, 2022 |
| ASUSTek       | PRIME B550-PLUS AC-HES      | [dde2246ae8](https://linux-hardware.org/?probe=dde2246ae8) | Jul 01, 2022 |
| ASRock        | Z87M Extreme4               | [06504aecc5](https://linux-hardware.org/?probe=06504aecc5) | Jun 24, 2022 |
| Gigabyte      | Z77X-UD3H                   | [7d7828a253](https://linux-hardware.org/?probe=7d7828a253) | Jun 23, 2022 |
| MSI           | B550-A PRO                  | [a7a76f04f9](https://linux-hardware.org/?probe=a7a76f04f9) | Jun 19, 2022 |
| MSI           | B450M MORTAR MAX            | [e1f785770e](https://linux-hardware.org/?probe=e1f785770e) | Jun 11, 2022 |
| T-bao         | MINI PC V1.0                | [8108463ab7](https://linux-hardware.org/?probe=8108463ab7) | Jun 09, 2022 |
| ASRock        | Z87M Extreme4               | [5ca7bb09b0](https://linux-hardware.org/?probe=5ca7bb09b0) | Jun 05, 2022 |
| ASRock        | X470 Taichi                 | [114aa0b977](https://linux-hardware.org/?probe=114aa0b977) | May 22, 2022 |
| Lenovo        | 3716 SDK0T76463 WIN 3422... | [cd15058963](https://linux-hardware.org/?probe=cd15058963) | May 16, 2022 |
| Lenovo        | 3716 SDK0T76463 WIN 3422... | [4043d7e26a](https://linux-hardware.org/?probe=4043d7e26a) | May 11, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [8c34e423f4](https://linux-hardware.org/?probe=8c34e423f4) | May 04, 2022 |
| ASRock        | X470 Taichi                 | [bd151331c1](https://linux-hardware.org/?probe=bd151331c1) | May 04, 2022 |
| Dell          | 0WR7PY A01                  | [66c6e57421](https://linux-hardware.org/?probe=66c6e57421) | Apr 23, 2022 |
| ASRock        | B550M Pro4                  | [b82721163b](https://linux-hardware.org/?probe=b82721163b) | Apr 22, 2022 |
| ASRock        | X99X Killer                 | [c6d6bddd17](https://linux-hardware.org/?probe=c6d6bddd17) | Apr 18, 2022 |
| ASUSTek       | Z97-P                       | [bf54ec19d0](https://linux-hardware.org/?probe=bf54ec19d0) | Apr 16, 2022 |
| ASRock        | X99X Killer                 | [3be92995ff](https://linux-hardware.org/?probe=3be92995ff) | Apr 11, 2022 |
| ASRock        | X470 Taichi                 | [ba87ebf29f](https://linux-hardware.org/?probe=ba87ebf29f) | Apr 08, 2022 |
| ASUSTek       | P8B75-M                     | [808661699f](https://linux-hardware.org/?probe=808661699f) | Apr 07, 2022 |
| HP            | 8433 11                     | [30c5d1d62f](https://linux-hardware.org/?probe=30c5d1d62f) | Apr 03, 2022 |
| MSI           | B450-A PRO MAX              | [a47ab656ab](https://linux-hardware.org/?probe=a47ab656ab) | Apr 01, 2022 |
| Gigabyte      | B550 GAMING X V2            | [3d37374fae](https://linux-hardware.org/?probe=3d37374fae) | Apr 01, 2022 |
| ASUSTek       | A68HM-PLUS                  | [cd6ebcba97](https://linux-hardware.org/?probe=cd6ebcba97) | Mar 31, 2022 |
| ASRock        | X470 Taichi                 | [f339c6f710](https://linux-hardware.org/?probe=f339c6f710) | Mar 29, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [fc5cdc4595](https://linux-hardware.org/?probe=fc5cdc4595) | Mar 23, 2022 |
| MSI           | MPG B550 GAMING CARBON W... | [c1a26607fd](https://linux-hardware.org/?probe=c1a26607fd) | Mar 13, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [95b7c99a5a](https://linux-hardware.org/?probe=95b7c99a5a) | Mar 08, 2022 |
| ASRock        | B450 Gaming K4              | [504b20acce](https://linux-hardware.org/?probe=504b20acce) | Mar 04, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [336ddc137d](https://linux-hardware.org/?probe=336ddc137d) | Mar 01, 2022 |
| ASUSTek       | A68HM-PLUS                  | [edfa6eb6e3](https://linux-hardware.org/?probe=edfa6eb6e3) | Feb 28, 2022 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | [abc925b917](https://linux-hardware.org/?probe=abc925b917) | Feb 26, 2022 |
| ASUSTek       | M4A89TD PRO USB3            | [66c0fc8423](https://linux-hardware.org/?probe=66c0fc8423) | Feb 26, 2022 |
| ASRock        | X470 Taichi                 | [df78a2fff6](https://linux-hardware.org/?probe=df78a2fff6) | Feb 14, 2022 |
| HP            | 8767 A                      | [e048574911](https://linux-hardware.org/?probe=e048574911) | Feb 12, 2022 |
| ASUSTek       | ROG Maximus XII FORMULA     | [a63d909e46](https://linux-hardware.org/?probe=a63d909e46) | Feb 12, 2022 |
| HP            | 8767 A                      | [6cb1e6b72f](https://linux-hardware.org/?probe=6cb1e6b72f) | Feb 12, 2022 |
| ASUSTek       | ROG Maximus XII FORMULA     | [885617bdda](https://linux-hardware.org/?probe=885617bdda) | Feb 12, 2022 |
| ASRock        | B450M Pro4                  | [0d80dc8143](https://linux-hardware.org/?probe=0d80dc8143) | Feb 11, 2022 |
| Lenovo        | 31900058 STD                | [03540e9cb2](https://linux-hardware.org/?probe=03540e9cb2) | Feb 07, 2022 |
| ASRock        | X470 Taichi                 | [e4beeac4a1](https://linux-hardware.org/?probe=e4beeac4a1) | Feb 06, 2022 |
| Gigabyte      | MFLP3AP-00\2.x              | [b7441a0e94](https://linux-hardware.org/?probe=b7441a0e94) | Jan 31, 2022 |
| ASRock        | X470 Taichi                 | [aa0e21b159](https://linux-hardware.org/?probe=aa0e21b159) | Jan 27, 2022 |
| Gigabyte      | B85-HD3                     | [ad70601774](https://linux-hardware.org/?probe=ad70601774) | Jan 26, 2022 |
| ASRock        | 970M Pro3                   | [402a4f960e](https://linux-hardware.org/?probe=402a4f960e) | Jan 17, 2022 |
| ASUSTek       | ROG Maximus X CODE          | [8fac80f31d](https://linux-hardware.org/?probe=8fac80f31d) | Jan 16, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [9fab263b02](https://linux-hardware.org/?probe=9fab263b02) | Jan 11, 2022 |
| MSI           | Z270 GAMING M5              | [02d70182fd](https://linux-hardware.org/?probe=02d70182fd) | Jan 10, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [8a1167daea](https://linux-hardware.org/?probe=8a1167daea) | Jan 08, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [1a4570a458](https://linux-hardware.org/?probe=1a4570a458) | Jan 08, 2022 |
| Pegatron      | 2AD5                        | [91ee5ba1df](https://linux-hardware.org/?probe=91ee5ba1df) | Jan 08, 2022 |
| Gigabyte      | B460M DS3H                  | [40f4de9da7](https://linux-hardware.org/?probe=40f4de9da7) | Jan 07, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | [1b62246b10](https://linux-hardware.org/?probe=1b62246b10) | Dec 21, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [9e73346fb8](https://linux-hardware.org/?probe=9e73346fb8) | Dec 15, 2021 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [196b460373](https://linux-hardware.org/?probe=196b460373) | Dec 13, 2021 |
| ASRock        | H77M-ITX                    | [5e98a2fce2](https://linux-hardware.org/?probe=5e98a2fce2) | Dec 11, 2021 |
| ASRock        | B450M Pro4                  | [e4fb1e4fe4](https://linux-hardware.org/?probe=e4fb1e4fe4) | Dec 09, 2021 |
| Lenovo        | ThinkStation S20 4105O1U    | [731c890641](https://linux-hardware.org/?probe=731c890641) | Dec 08, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [f0df07c0e4](https://linux-hardware.org/?probe=f0df07c0e4) | Dec 06, 2021 |
| Acer          | Aspire TC-895 V:1.0         | [c743459a71](https://linux-hardware.org/?probe=c743459a71) | Dec 04, 2021 |
| ASUSTek       | H87M-E                      | [2b4abcf54f](https://linux-hardware.org/?probe=2b4abcf54f) | Dec 02, 2021 |
| ASUSTek       | H87M-E                      | [72cf0ed74d](https://linux-hardware.org/?probe=72cf0ed74d) | Dec 02, 2021 |
| Lenovo        | ThinkStation S20 4105O1U    | [f031548aac](https://linux-hardware.org/?probe=f031548aac) | Dec 01, 2021 |
| Lenovo        | ThinkStation S20 4105O1U    | [48f73af82d](https://linux-hardware.org/?probe=48f73af82d) | Nov 30, 2021 |
| ASRock        | X470 Taichi                 | [0b1d816eff](https://linux-hardware.org/?probe=0b1d816eff) | Nov 28, 2021 |
| ASUSTek       | Rampage IV EXTREME          | [50999d4796](https://linux-hardware.org/?probe=50999d4796) | Nov 14, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [cd295bb56c](https://linux-hardware.org/?probe=cd295bb56c) | Nov 04, 2021 |
| ASRock        | X470 Taichi                 | [86f08832c0](https://linux-hardware.org/?probe=86f08832c0) | Oct 31, 2021 |
| ASUSTek       | P8B75-M                     | [2130c28d33](https://linux-hardware.org/?probe=2130c28d33) | Oct 27, 2021 |
| MSI           | Z77A-G43                    | [3bd9604ae7](https://linux-hardware.org/?probe=3bd9604ae7) | Oct 20, 2021 |
| MSI           | B460M PRO-VDH WIFI          | [76071ec77b](https://linux-hardware.org/?probe=76071ec77b) | Oct 19, 2021 |
| MSI           | B450M-A PRO MAX             | [4148046f02](https://linux-hardware.org/?probe=4148046f02) | Oct 17, 2021 |
| ASRock        | X470 Taichi                 | [ff6b763448](https://linux-hardware.org/?probe=ff6b763448) | Oct 16, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | [fdd8f9dd8e](https://linux-hardware.org/?probe=fdd8f9dd8e) | Sep 17, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | [ab3ad8009e](https://linux-hardware.org/?probe=ab3ad8009e) | Sep 16, 2021 |
| ASUSTek       | PRIME B450M-K               | [b8b49f201f](https://linux-hardware.org/?probe=b8b49f201f) | Sep 14, 2021 |
| MSI           | H310M PRO-VDH PLUS          | [65fcfef06f](https://linux-hardware.org/?probe=65fcfef06f) | Aug 27, 2021 |
| Alienware     | 0TYR0X A00                  | [5ea23ebfb2](https://linux-hardware.org/?probe=5ea23ebfb2) | Aug 19, 2021 |
| ASRock        | X399 Professional Gaming    | [bb53a385c3](https://linux-hardware.org/?probe=bb53a385c3) | Aug 19, 2021 |
| Medion        | H110H4-EM2                  | [f4e01958e5](https://linux-hardware.org/?probe=f4e01958e5) | Aug 10, 2021 |
| ASRock        | X470 Taichi                 | [a919fef17f](https://linux-hardware.org/?probe=a919fef17f) | Aug 07, 2021 |
| MSI           | Z97 MPOWER                  | [dee7d3af4a](https://linux-hardware.org/?probe=dee7d3af4a) | Aug 06, 2021 |
| MSI           | Z97 MPOWER                  | [f30e5a3a86](https://linux-hardware.org/?probe=f30e5a3a86) | Aug 06, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [826edd51bc](https://linux-hardware.org/?probe=826edd51bc) | Jul 07, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [aa05cca9b7](https://linux-hardware.org/?probe=aa05cca9b7) | Jun 30, 2021 |
| Biostar       | H310MHP                     | [0d3f648f3e](https://linux-hardware.org/?probe=0d3f648f3e) | Jun 30, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [fb3d7de63c](https://linux-hardware.org/?probe=fb3d7de63c) | Jun 26, 2021 |
| MSI           | A320M-HDV R4.0              | [486775a989](https://linux-hardware.org/?probe=486775a989) | Jun 23, 2021 |
| MSI           | A320M-HDV R4.0              | [4629f86f56](https://linux-hardware.org/?probe=4629f86f56) | Jun 22, 2021 |
| MSI           | A320M-HDV R4.0              | [69dea4e3cf](https://linux-hardware.org/?probe=69dea4e3cf) | Jun 22, 2021 |
| MSI           | A320M-HDV R4.0              | [2fd89c951e](https://linux-hardware.org/?probe=2fd89c951e) | Jun 22, 2021 |
| MSI           | X370 GAMING PRO CARBON      | [9ead1e1bb5](https://linux-hardware.org/?probe=9ead1e1bb5) | Jun 22, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [8144c83b50](https://linux-hardware.org/?probe=8144c83b50) | Jun 22, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [376c0ff95d](https://linux-hardware.org/?probe=376c0ff95d) | Jun 15, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [34801a2f74](https://linux-hardware.org/?probe=34801a2f74) | Jun 12, 2021 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [51e1e33185](https://linux-hardware.org/?probe=51e1e33185) | May 20, 2021 |
| MSI           | B350M GAMING PRO            | [c04e6666e7](https://linux-hardware.org/?probe=c04e6666e7) | May 20, 2021 |
| Dell          | 0D28YY A02                  | [14edf3bd00](https://linux-hardware.org/?probe=14edf3bd00) | May 16, 2021 |
| Gigabyte      | A320M-S2H-CF                | [066f815622](https://linux-hardware.org/?probe=066f815622) | May 12, 2021 |
| HP            | 844C                        | [29f7cf64ce](https://linux-hardware.org/?probe=29f7cf64ce) | May 06, 2021 |
| HP            | 844C                        | [0534f06ec4](https://linux-hardware.org/?probe=0534f06ec4) | May 06, 2021 |
| ASUSTek       | PRIME Z590-A                | [cb3058760e](https://linux-hardware.org/?probe=cb3058760e) | May 04, 2021 |
| Gigabyte      | P67A-UD3-B3                 | [08ea956bfa](https://linux-hardware.org/?probe=08ea956bfa) | Apr 24, 2021 |
| MSI           | Z87 MPOWER                  | [ff6aa3811c](https://linux-hardware.org/?probe=ff6aa3811c) | Apr 08, 2021 |
| ASRock        | AB350M-HDV                  | [23502edac5](https://linux-hardware.org/?probe=23502edac5) | Apr 01, 2021 |
| ASRock        | AB350M-HDV                  | [13b2fdddc0](https://linux-hardware.org/?probe=13b2fdddc0) | Apr 01, 2021 |
| Dell          | 07KY25 A01                  | [8c4f2f9922](https://linux-hardware.org/?probe=8c4f2f9922) | Mar 31, 2021 |
| Dell          | 07KY25 A01                  | [1b9efb1b29](https://linux-hardware.org/?probe=1b9efb1b29) | Mar 24, 2021 |
| Gigabyte      | B450 AORUS M                | [097a0d616c](https://linux-hardware.org/?probe=097a0d616c) | Mar 18, 2021 |
| Gigabyte      | B450 AORUS M                | [22054ffd75](https://linux-hardware.org/?probe=22054ffd75) | Mar 18, 2021 |
| HP            | 2AF7                        | [e0639ea4a5](https://linux-hardware.org/?probe=e0639ea4a5) | Mar 11, 2021 |
| HP            | 2AF7                        | [fb8d76722c](https://linux-hardware.org/?probe=fb8d76722c) | Mar 11, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [c1f22a7521](https://linux-hardware.org/?probe=c1f22a7521) | Mar 05, 2021 |
| Gigabyte      | GA-MA790FXT-UD5P            | [404dab2464](https://linux-hardware.org/?probe=404dab2464) | Feb 27, 2021 |
| ASRock        | FM2A88X Extreme6+           | [13f9fc2ef3](https://linux-hardware.org/?probe=13f9fc2ef3) | Feb 18, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [2e19f3b1af](https://linux-hardware.org/?probe=2e19f3b1af) | Feb 18, 2021 |
| Dell          | 0C2KJT A00                  | [f821a0035b](https://linux-hardware.org/?probe=f821a0035b) | Feb 12, 2021 |
| ASUSTek       | PRIME B360M-K               | [b73941c431](https://linux-hardware.org/?probe=b73941c431) | Feb 08, 2021 |
| HP            | 1825                        | [3b6b80db46](https://linux-hardware.org/?probe=3b6b80db46) | Jan 31, 2021 |
| HP            | 1825                        | [1df894dea4](https://linux-hardware.org/?probe=1df894dea4) | Jan 31, 2021 |
| ASRock        | X470 Master SLI             | [36eaf717e9](https://linux-hardware.org/?probe=36eaf717e9) | Jan 26, 2021 |
| ASRock        | X470 Master SLI             | [b1be9375c0](https://linux-hardware.org/?probe=b1be9375c0) | Jan 24, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [7332b50f98](https://linux-hardware.org/?probe=7332b50f98) | Jan 24, 2021 |
| ASUSTek       | PRIME H270-PLUS             | [3f895b585b](https://linux-hardware.org/?probe=3f895b585b) | Jan 22, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [61976e9745](https://linux-hardware.org/?probe=61976e9745) | Jan 18, 2021 |
| MSI           | X399 SLI PLUS               | [e392838a54](https://linux-hardware.org/?probe=e392838a54) | Jan 10, 2021 |
| ASUSTek       | CM5671                      | [069344a54e](https://linux-hardware.org/?probe=069344a54e) | Jan 07, 2021 |
| MSI           | B85-G43 GAMING              | [8fe013f04a](https://linux-hardware.org/?probe=8fe013f04a) | Jan 04, 2021 |
| ASRock        | G41M-VS3                    | [e1217b1871](https://linux-hardware.org/?probe=e1217b1871) | Jan 02, 2021 |
| Pegatron      | 2AC2A                       | [436a2ca3ce](https://linux-hardware.org/?probe=436a2ca3ce) | Dec 25, 2020 |
| Pegatron      | 2AC2A                       | [2df3b195c6](https://linux-hardware.org/?probe=2df3b195c6) | Dec 25, 2020 |
| ASUSTek       | PRIME Z370-P                | [35365be0e8](https://linux-hardware.org/?probe=35365be0e8) | Dec 19, 2020 |
| MSI           | Z390-A PRO                  | [ea7a52fdac](https://linux-hardware.org/?probe=ea7a52fdac) | Dec 16, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [62a5c95d51](https://linux-hardware.org/?probe=62a5c95d51) | Dec 14, 2020 |
| HP            | 8643 SMVB                   | [dccfba36f1](https://linux-hardware.org/?probe=dccfba36f1) | Dec 06, 2020 |
| Gigabyte      | B450 AORUS ELITE            | [2a35d394f9](https://linux-hardware.org/?probe=2a35d394f9) | Dec 04, 2020 |
| MSI           | Z390-A PRO                  | [05e3eb32c9](https://linux-hardware.org/?probe=05e3eb32c9) | Dec 03, 2020 |
| MSI           | Z390-A PRO                  | [dc6ea9bfb8](https://linux-hardware.org/?probe=dc6ea9bfb8) | Nov 29, 2020 |
| ASUSTek       | M5A97 LE R2.0               | [d4b3f84c86](https://linux-hardware.org/?probe=d4b3f84c86) | Nov 28, 2020 |
| Gigabyte      | B450 AORUS M                | [a3d68dc126](https://linux-hardware.org/?probe=a3d68dc126) | Nov 19, 2020 |
| Gigabyte      | B450 AORUS M                | [d9faeae0d4](https://linux-hardware.org/?probe=d9faeae0d4) | Nov 19, 2020 |
| Gigabyte      | X570 AORUS PRO WIFI         | [11c79940a4](https://linux-hardware.org/?probe=11c79940a4) | Nov 19, 2020 |
| HP            | 18E7                        | [f84cbfd465](https://linux-hardware.org/?probe=f84cbfd465) | Nov 10, 2020 |
| Gigabyte      | X570 AORUS PRO WIFI         | [79608bd849](https://linux-hardware.org/?probe=79608bd849) | Nov 06, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [e80ddac12f](https://linux-hardware.org/?probe=e80ddac12f) | Nov 02, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [876b039494](https://linux-hardware.org/?probe=876b039494) | Nov 01, 2020 |
| Gigabyte      | X570 AORUS PRO WIFI         | [4e573bc6ff](https://linux-hardware.org/?probe=4e573bc6ff) | Oct 28, 2020 |
| MSI           | MPG B550 GAMING EDGE WIF... | [4b9d2b77cb](https://linux-hardware.org/?probe=4b9d2b77cb) | Oct 26, 2020 |
| ASUSTek       | PRIME X399-A                | [b7772d9ff8](https://linux-hardware.org/?probe=b7772d9ff8) | Oct 13, 2020 |
| Dell          | 0R6JMP A00                  | [c4cbec5b80](https://linux-hardware.org/?probe=c4cbec5b80) | Oct 11, 2020 |
| OEM           | Unknown                     | [2e7a212437](https://linux-hardware.org/?probe=2e7a212437) | Sep 26, 2020 |
| Lenovo        | ThinkCentre M91p 7033CG1    | [c08fed8ecb](https://linux-hardware.org/?probe=c08fed8ecb) | Sep 11, 2020 |
| ASUSTek       | Maximus VIII FORMULA        | [7b8babe846](https://linux-hardware.org/?probe=7b8babe846) | Aug 27, 2020 |
| ASUSTek       | Maximus VIII FORMULA        | [73462df387](https://linux-hardware.org/?probe=73462df387) | Aug 07, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| Garuda Linux Soaring | 101      | 54.01%  |
| Garuda Linux         | 54       | 28.88%  |
| Garuda Linux Rolling | 32       | 17.11%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Garuda Linux | 183      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version            | Desktops | Percent |
|--------------------|----------|---------|
| 5.17.1-zen1-1-zen  | 6        | 2.73%   |
| 6.2.10-zen1-1-zen  | 4        | 1.82%   |
| 6.1.12-zen1-1-zen  | 4        | 1.82%   |
| 6.1.1-zen1-1-zen   | 4        | 1.82%   |
| 5.15.7-zen1-1-zen  | 4        | 1.82%   |
| 5.10.4-107-tkg-bmq | 4        | 1.82%   |
| 6.4.6-zen1-1-zen   | 3        | 1.36%   |
| 6.3.2-zen1-1-zen   | 3        | 1.36%   |
| 6.1.8-zen1-1-zen   | 3        | 1.36%   |
| 6.0.2-zen1-1-zen   | 3        | 1.36%   |
| 6.0.12-zen1-1-zen  | 3        | 1.36%   |
| 6.0.11-zen1-1-zen  | 3        | 1.36%   |
| 5.9.1-zen2-1-zen   | 3        | 1.36%   |
| 5.18.12-zen1-1-zen | 3        | 1.36%   |
| 5.18.1-zen1-1-zen  | 3        | 1.36%   |
| 5.16.4-zen1-1-zen  | 3        | 1.36%   |
| 5.15.2-zen1-1-zen  | 3        | 1.36%   |
| 5.15.13-zen1-1-zen | 3        | 1.36%   |
| 5.11.16-zen1-1-zen | 3        | 1.36%   |
| 6.4.9-zen1-1-zen   | 2        | 0.91%   |
| 6.4.3-zen1-1-zen   | 2        | 0.91%   |
| 6.3.6-zen1-1-zen   | 2        | 0.91%   |
| 6.2.7-zen1-1-zen   | 2        | 0.91%   |
| 6.2.2-zen2-1-zen   | 2        | 0.91%   |
| 6.2.12-zen1-1-zen  | 2        | 0.91%   |
| 6.2.11-zen1-1-zen  | 2        | 0.91%   |
| 6.1.4-zen2-1-zen   | 2        | 0.91%   |
| 6.1.3-zen1-1-zen   | 2        | 0.91%   |
| 6.0.8-zen1-1-zen   | 2        | 0.91%   |
| 5.9.11-zen2-1-zen  | 2        | 0.91%   |
| 5.9.10-zen1-1-zen  | 2        | 0.91%   |
| 5.8.14-zen1-1-zen  | 2        | 0.91%   |
| 5.19.9-zen1-1-zen  | 2        | 0.91%   |
| 5.19.5-zen1-1-zen  | 2        | 0.91%   |
| 5.18.16-zen1-1-zen | 2        | 0.91%   |
| 5.16.8-zen1-1-zen  | 2        | 0.91%   |
| 5.16.11-zen1-1-zen | 2        | 0.91%   |
| 5.16.10-zen1-1-zen | 2        | 0.91%   |
| 5.16.0-zen1-1-zen  | 2        | 0.91%   |
| 5.15.12-zen1-1-zen | 2        | 0.91%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.17.1  | 7        | 3.18%   |
| 6.2.10  | 4        | 1.82%   |
| 6.1.12  | 4        | 1.82%   |
| 6.1.1   | 4        | 1.82%   |
| 5.15.7  | 4        | 1.82%   |
| 5.10.4  | 4        | 1.82%   |
| 6.4.6   | 3        | 1.36%   |
| 6.4.3   | 3        | 1.36%   |
| 6.3.2   | 3        | 1.36%   |
| 6.2.2   | 3        | 1.36%   |
| 6.1.8   | 3        | 1.36%   |
| 6.1.4   | 3        | 1.36%   |
| 6.0.2   | 3        | 1.36%   |
| 6.0.12  | 3        | 1.36%   |
| 6.0.11  | 3        | 1.36%   |
| 5.9.1   | 3        | 1.36%   |
| 5.18.12 | 3        | 1.36%   |
| 5.18.1  | 3        | 1.36%   |
| 5.17.5  | 3        | 1.36%   |
| 5.16.4  | 3        | 1.36%   |
| 5.15.2  | 3        | 1.36%   |
| 5.15.13 | 3        | 1.36%   |
| 5.12.13 | 3        | 1.36%   |
| 5.11.16 | 3        | 1.36%   |
| 6.4.9   | 2        | 0.91%   |
| 6.4.2   | 2        | 0.91%   |
| 6.3.6   | 2        | 0.91%   |
| 6.2.7   | 2        | 0.91%   |
| 6.2.12  | 2        | 0.91%   |
| 6.2.11  | 2        | 0.91%   |
| 6.1.3   | 2        | 0.91%   |
| 6.0.8   | 2        | 0.91%   |
| 5.9.11  | 2        | 0.91%   |
| 5.9.10  | 2        | 0.91%   |
| 5.8.14  | 2        | 0.91%   |
| 5.19.9  | 2        | 0.91%   |
| 5.19.5  | 2        | 0.91%   |
| 5.18.16 | 2        | 0.91%   |
| 5.17.3  | 2        | 0.91%   |
| 5.16.8  | 2        | 0.91%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.1     | 25       | 11.96%  |
| 5.15    | 20       | 9.57%   |
| 5.16    | 16       | 7.66%   |
| 5.10    | 16       | 7.66%   |
| 6.0     | 15       | 7.18%   |
| 6.4     | 14       | 6.7%    |
| 6.2     | 14       | 6.7%    |
| 5.18    | 14       | 6.7%    |
| 5.17    | 11       | 5.26%   |
| 5.12    | 10       | 4.78%   |
| 5.11    | 10       | 4.78%   |
| 6.3     | 9        | 4.31%   |
| 5.9     | 9        | 4.31%   |
| 5.19    | 8        | 3.83%   |
| 5.13    | 7        | 3.35%   |
| 5.14    | 6        | 2.87%   |
| 5.8     | 5        | 2.39%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 183      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| KDE5       | 127      | 67.91%  |
| GNOME      | 20       | 10.7%   |
| KDE        | 19       | 10.16%  |
| XFCE       | 8        | 4.28%   |
| X-Cinnamon | 3        | 1.6%    |
| sway       | 2        | 1.07%   |
| LXQt       | 2        | 1.07%   |
| Unknown    | 2        | 1.07%   |
| MATE       | 1        | 0.53%   |
| i3         | 1        | 0.53%   |
| Deepin     | 1        | 0.53%   |
| Cinnamon   | 1        | 0.53%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 164      | 87.7%   |
| Wayland | 14       | 7.49%   |
| Tty     | 6        | 3.21%   |
| Unknown | 3        | 1.6%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 80       | 43.24%  |
| SDDM    | 78       | 42.16%  |
| LightDM | 17       | 9.19%   |
| GDM     | 8        | 4.32%   |
| GREETD  | 2        | 1.08%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 94       | 51.09%  |
| de_DE | 18       | 9.78%   |
| en_GB | 16       | 8.7%    |
| en_CA | 6        | 3.26%   |
| es_ES | 5        | 2.72%   |
| pt_BR | 4        | 2.17%   |
| it_IT | 4        | 2.17%   |
| en_AU | 4        | 2.17%   |
| ru_RU | 3        | 1.63%   |
| nl_NL | 3        | 1.63%   |
| sk_SK | 2        | 1.09%   |
| pl_PL | 2        | 1.09%   |
| fr_FR | 2        | 1.09%   |
| fr_BE | 2        | 1.09%   |
| en_IN | 2        | 1.09%   |
| da_DK | 2        | 1.09%   |
| sv_SE | 1        | 0.54%   |
| nl_BE | 1        | 0.54%   |
| nb_NO | 1        | 0.54%   |
| iu_CA | 1        | 0.54%   |
| hu_HU | 1        | 0.54%   |
| es_VE | 1        | 0.54%   |
| es_MX | 1        | 0.54%   |
| es_AR | 1        | 0.54%   |
| en_ZA | 1        | 0.54%   |
| en_SG | 1        | 0.54%   |
| en_DE | 1        | 0.54%   |
| el_GR | 1        | 0.54%   |
| de_CH | 1        | 0.54%   |
| de_AT | 1        | 0.54%   |
| cs_CZ | 1        | 0.54%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 103      | 56.28%  |
| BIOS | 80       | 43.72%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Btrfs   | 178      | 97.27%  |
| Overlay | 2        | 1.09%   |
| Ext4    | 2        | 1.09%   |
| Tmpfs   | 1        | 0.55%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 99       | 53.8%   |
| Unknown | 79       | 42.93%  |
| MBR     | 6        | 3.26%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 148      | 79.57%  |
| Yes       | 38       | 20.43%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 125      | 67.57%  |
| Yes       | 60       | 32.43%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 54       | 29.51%  |
| MSI                                  | 32       | 17.49%  |
| Gigabyte Technology                  | 28       | 15.3%   |
| ASRock                               | 21       | 11.48%  |
| Hewlett-Packard                      | 12       | 6.56%   |
| Lenovo                               | 8        | 4.37%   |
| Dell                                 | 8        | 4.37%   |
| Intel                                | 3        | 1.64%   |
| Acer                                 | 3        | 1.64%   |
| Shenzhen Meigao Electronic Equipment | 2        | 1.09%   |
| Pegatron                             | 2        | 1.09%   |
| Biostar                              | 2        | 1.09%   |
| Alienware                            | 2        | 1.09%   |
| Win element                          | 1        | 0.55%   |
| T-bao                                | 1        | 0.55%   |
| OEM                                  | 1        | 0.55%   |
| Medion                               | 1        | 0.55%   |
| Fujitsu                              | 1        | 0.55%   |
| BESSTAR Tech                         | 1        | 0.55%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| ASUS TUF Gaming X570-PLUS                  | 7        | 3.83%   |
| MSI MS-7C91                                | 3        | 1.64%   |
| MSI MS-7B86                                | 3        | 1.64%   |
| ASUS All Series                            | 3        | 1.64%   |
| MSI MS-7C37                                | 2        | 1.09%   |
| MSI MS-7C02                                | 2        | 1.09%   |
| HP ProDesk 600 G1 SFF                      | 2        | 1.09%   |
| HP Pavilion Gaming Desktop 690-00xx        | 2        | 1.09%   |
| Gigabyte X570 AORUS PRO WIFI               | 2        | 1.09%   |
| Gigabyte AB350-Gaming 3                    | 2        | 1.09%   |
| Dell Inspiron 3668                         | 2        | 1.09%   |
| ASUS ROG STRIX X570-E GAMING               | 2        | 1.09%   |
| ASUS ROG STRIX B550-F GAMING               | 2        | 1.09%   |
| ASUS PRIME X570-P                          | 2        | 1.09%   |
| ASRock B450M-HDV R4.0                      | 2        | 1.09%   |
| Win element M600                           | 1        | 0.55%   |
| T-bao MINI PC                              | 1        | 0.55%   |
| Shenzhen Meigao Electronic Equipment UM690 | 1        | 0.55%   |
| Shenzhen Meigao Electronic Equipment HX90G | 1        | 0.55%   |
| Pegatron p7-1030                           | 1        | 0.55%   |
| Pegatron h9-1301es                         | 1        | 0.55%   |
| MSI MS-7D96                                | 1        | 0.55%   |
| MSI MS-7D75                                | 1        | 0.55%   |
| MSI MS-7D16                                | 1        | 0.55%   |
| MSI MS-7C90                                | 1        | 0.55%   |
| MSI MS-7C83                                | 1        | 0.55%   |
| MSI MS-7C56                                | 1        | 0.55%   |
| MSI MS-7C52                                | 1        | 0.55%   |
| MSI MS-7C09                                | 1        | 0.55%   |
| MSI MS-7B98                                | 1        | 0.55%   |
| MSI MS-7B93                                | 1        | 0.55%   |
| MSI MS-7B89                                | 1        | 0.55%   |
| MSI MS-7B09                                | 1        | 0.55%   |
| MSI MS-7A78                                | 1        | 0.55%   |
| MSI MS-7A39                                | 1        | 0.55%   |
| MSI MS-7A38                                | 1        | 0.55%   |
| MSI MS-7A32                                | 1        | 0.55%   |
| MSI MS-7818                                | 1        | 0.55%   |
| MSI MS-7816                                | 1        | 0.55%   |
| MSI MS-7788                                | 1        | 0.55%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| ASUS PRIME                                 | 13       | 7.1%    |
| ASUS ROG                                   | 12       | 6.56%   |
| ASUS TUF                                   | 11       | 6.01%   |
| Lenovo ThinkCentre                         | 5        | 2.73%   |
| Dell Inspiron                              | 5        | 2.73%   |
| HP Pavilion                                | 4        | 2.19%   |
| Gigabyte X570                              | 4        | 2.19%   |
| MSI MS-7C91                                | 3        | 1.64%   |
| MSI MS-7B86                                | 3        | 1.64%   |
| HP EliteDesk                               | 3        | 1.64%   |
| Gigabyte B550                              | 3        | 1.64%   |
| Gigabyte B450                              | 3        | 1.64%   |
| Dell OptiPlex                              | 3        | 1.64%   |
| ASUS All                                   | 3        | 1.64%   |
| MSI MS-7C37                                | 2        | 1.09%   |
| MSI MS-7C02                                | 2        | 1.09%   |
| HP ProDesk                                 | 2        | 1.09%   |
| Gigabyte AB350-Gaming                      | 2        | 1.09%   |
| ASUS Rampage                               | 2        | 1.09%   |
| ASUS Maximus                               | 2        | 1.09%   |
| ASRock X470                                | 2        | 1.09%   |
| ASRock B450M-HDV                           | 2        | 1.09%   |
| Alienware Aurora                           | 2        | 1.09%   |
| Acer Aspire                                | 2        | 1.09%   |
| Win element M600                           | 1        | 0.55%   |
| T-bao MINI                                 | 1        | 0.55%   |
| Shenzhen Meigao Electronic Equipment UM690 | 1        | 0.55%   |
| Shenzhen Meigao Electronic Equipment HX90G | 1        | 0.55%   |
| Pegatron p7-1030                           | 1        | 0.55%   |
| Pegatron h9-1301es                         | 1        | 0.55%   |
| MSI MS-7D96                                | 1        | 0.55%   |
| MSI MS-7D75                                | 1        | 0.55%   |
| MSI MS-7D16                                | 1        | 0.55%   |
| MSI MS-7C90                                | 1        | 0.55%   |
| MSI MS-7C83                                | 1        | 0.55%   |
| MSI MS-7C56                                | 1        | 0.55%   |
| MSI MS-7C52                                | 1        | 0.55%   |
| MSI MS-7C09                                | 1        | 0.55%   |
| MSI MS-7B98                                | 1        | 0.55%   |
| MSI MS-7B93                                | 1        | 0.55%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 30       | 16.39%  |
| 2018 | 25       | 13.66%  |
| 2020 | 23       | 12.57%  |
| 2017 | 16       | 8.74%   |
| 2021 | 15       | 8.2%    |
| 2022 | 13       | 7.1%    |
| 2013 | 13       | 7.1%    |
| 2014 | 11       | 6.01%   |
| 2012 | 11       | 6.01%   |
| 2016 | 7        | 3.83%   |
| 2011 | 7        | 3.83%   |
| 2015 | 5        | 2.73%   |
| 2010 | 4        | 2.19%   |
| 2009 | 2        | 1.09%   |
| 2008 | 1        | 0.55%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 183      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 183      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 183      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 32.01-64.0  | 58       | 31.18%  |
| 16.01-24.0  | 54       | 29.03%  |
| 8.01-16.0   | 27       | 14.52%  |
| 4.01-8.0    | 17       | 9.14%   |
| 64.01-256.0 | 13       | 6.99%   |
| 24.01-32.0  | 12       | 6.45%   |
| 3.01-4.0    | 5        | 2.69%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 80       | 40.82%  |
| 3.01-4.0   | 39       | 19.9%   |
| 8.01-16.0  | 31       | 15.82%  |
| 2.01-3.0   | 27       | 13.78%  |
| 1.01-2.0   | 11       | 5.61%   |
| 16.01-24.0 | 7        | 3.57%   |
| 32.01-64.0 | 1        | 0.51%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 55       | 29.1%   |
| 3      | 45       | 23.81%  |
| 1      | 31       | 16.4%   |
| 4      | 27       | 14.29%  |
| 5      | 16       | 8.47%   |
| 6      | 7        | 3.7%    |
| 9      | 4        | 2.12%   |
| 18     | 1        | 0.53%   |
| 14     | 1        | 0.53%   |
| 11     | 1        | 0.53%   |
| 7      | 1        | 0.53%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 129      | 70.11%  |
| Yes       | 55       | 29.89%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 181      | 98.91%  |
| No        | 2        | 1.09%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 103      | 54.5%   |
| No        | 86       | 45.5%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 96       | 51.34%  |
| Yes       | 91       | 48.66%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 54       | 29.51%  |
| Germany      | 24       | 13.11%  |
| Italy        | 10       | 5.46%   |
| UK           | 8        | 4.37%   |
| Canada       | 7        | 3.83%   |
| Brazil       | 7        | 3.83%   |
| Spain        | 5        | 2.73%   |
| Sweden       | 4        | 2.19%   |
| Russia       | 4        | 2.19%   |
| Netherlands  | 4        | 2.19%   |
| Belgium      | 4        | 2.19%   |
| Australia    | 4        | 2.19%   |
| Romania      | 3        | 1.64%   |
| Poland       | 3        | 1.64%   |
| Norway       | 3        | 1.64%   |
| India        | 3        | 1.64%   |
| France       | 3        | 1.64%   |
| Slovakia     | 2        | 1.09%   |
| Puerto Rico  | 2        | 1.09%   |
| Latvia       | 2        | 1.09%   |
| Greece       | 2        | 1.09%   |
| Denmark      | 2        | 1.09%   |
| Austria      | 2        | 1.09%   |
| Venezuela    | 1        | 0.55%   |
| Ukraine      | 1        | 0.55%   |
| Turkey       | 1        | 0.55%   |
| Taiwan       | 1        | 0.55%   |
| Switzerland  | 1        | 0.55%   |
| South Africa | 1        | 0.55%   |
| Singapore    | 1        | 0.55%   |
| Serbia       | 1        | 0.55%   |
| Portugal     | 1        | 0.55%   |
| Philippines  | 1        | 0.55%   |
| Mexico       | 1        | 0.55%   |
| Lithuania    | 1        | 0.55%   |
| Israel       | 1        | 0.55%   |
| Ireland      | 1        | 0.55%   |
| Iceland      | 1        | 0.55%   |
| Hungary      | 1        | 0.55%   |
| Finland      | 1        | 0.55%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Desktops | Percent |
|-------------------------|----------|---------|
| Milan                   | 3        | 1.58%   |
| Dallas                  | 3        | 1.58%   |
| Wasmes                  | 2        | 1.05%   |
| Sydney                  | 2        | 1.05%   |
| St Louis                | 2        | 1.05%   |
| Sao Paulo               | 2        | 1.05%   |
| Riga                    | 2        | 1.05%   |
| Oklahoma City           | 2        | 1.05%   |
| Melbourne               | 2        | 1.05%   |
| Mannheim                | 2        | 1.05%   |
| Kingsport               | 2        | 1.05%   |
| Gaildorf                | 2        | 1.05%   |
| Berlin                  | 2        | 1.05%   |
| Algeciras               | 2        | 1.05%   |
| Złotoryja              | 1        | 0.53%   |
| Zwickau                 | 1        | 0.53%   |
| York                    | 1        | 0.53%   |
| Wil                     | 1        | 0.53%   |
| Wichita                 | 1        | 0.53%   |
| Weiterstadt             | 1        | 0.53%   |
| Weilen unter den Rinnen | 1        | 0.53%   |
| Warsaw                  | 1        | 0.53%   |
| Voronezh                | 1        | 0.53%   |
| Volzhskiy               | 1        | 0.53%   |
| Vilnius                 | 1        | 0.53%   |
| Victoria                | 1        | 0.53%   |
| Västerås              | 1        | 0.53%   |
| Valence                 | 1        | 0.53%   |
| Urbandale               | 1        | 0.53%   |
| Ullerslev               | 1        | 0.53%   |
| Udine                   | 1        | 0.53%   |
| Trecastelli             | 1        | 0.53%   |
| Timișoara              | 1        | 0.53%   |
| Thonon-les-Bains        | 1        | 0.53%   |
| Taunusstein             | 1        | 0.53%   |
| Tampere                 | 1        | 0.53%   |
| Taipei                  | 1        | 0.53%   |
| Stockholm               | 1        | 0.53%   |
| Steyr                   | 1        | 0.53%   |
| Stavropol               | 1        | 0.53%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 81       | 137    | 17.72%  |
| Seagate                     | 75       | 122    | 16.41%  |
| Samsung Electronics         | 74       | 158    | 16.19%  |
| Toshiba                     | 31       | 42     | 6.78%   |
| Sandisk                     | 26       | 35     | 5.69%   |
| Crucial                     | 22       | 29     | 4.81%   |
| Kingston                    | 21       | 31     | 4.6%    |
| Hitachi                     | 10       | 10     | 2.19%   |
| Silicon Motion              | 8        | 8      | 1.75%   |
| Phison                      | 7        | 8      | 1.53%   |
| Intel                       | 7        | 10     | 1.53%   |
| Micron/Crucial Technology   | 6        | 10     | 1.31%   |
| A-DATA Technology           | 6        | 9      | 1.31%   |
| PNY                         | 5        | 5      | 1.09%   |
| Unknown                     | 4        | 4      | 0.88%   |
| OCZ                         | 4        | 4      | 0.88%   |
| HGST                        | 4        | 10     | 0.88%   |
| China                       | 4        | 6      | 0.88%   |
| ADATA Technology            | 4        | 5      | 0.88%   |
| XPG                         | 3        | 4      | 0.66%   |
| SPCC                        | 3        | 3      | 0.66%   |
| SK hynix                    | 3        | 5      | 0.66%   |
| Intenso                     | 3        | 4      | 0.66%   |
| Emtec                       | 3        | 5      | 0.66%   |
| Transcend                   | 2        | 2      | 0.44%   |
| TO Exter                    | 2        | 2      | 0.44%   |
| Team                        | 2        | 3      | 0.44%   |
| Realtek Semiconductor       | 2        | 3      | 0.44%   |
| LITEONIT                    | 2        | 2      | 0.44%   |
| Kingston Technology Company | 2        | 2      | 0.44%   |
| Hewlett-Packard             | 2        | 2      | 0.44%   |
| WD MediaMax                 | 1        | 1      | 0.22%   |
| USB30                       | 1        | 2      | 0.22%   |
| T-FORCE                     | 1        | 1      | 0.22%   |
| SABRENT                     | 1        | 2      | 0.22%   |
| Qumo                        | 1        | 1      | 0.22%   |
| Plextor                     | 1        | 1      | 0.22%   |
| Phison Electronics          | 1        | 2      | 0.22%   |
| Patriot                     | 1        | 1      | 0.22%   |
| Neo                         | 1        | 1      | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                              | Desktops | Percent |
|--------------------------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB                | 11       | 1.99%   |
| Samsung SSD 850 EVO 250GB                                          | 9        | 1.63%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB                 | 8        | 1.45%   |
| Seagate ST2000DM008-2FR102 2TB                                     | 7        | 1.27%   |
| Samsung SSD 860 EVO 500GB                                          | 7        | 1.27%   |
| Crucial CT1000MX500SSD1 1TB                                        | 7        | 1.27%   |
| Seagate ST1000DM010-2EP102 1TB                                     | 6        | 1.08%   |
| Samsung NVMe SSD Drive 1TB                                         | 6        | 1.08%   |
| Toshiba DT01ACA100 1TB                                             | 5        | 0.9%    |
| Samsung SSD 970 EVO Plus 500GB                                     | 5        | 0.9%    |
| WDC WD10EZEX-60WN4A0 1TB                                           | 4        | 0.72%   |
| WDC WD10EZEX-08WN4A0 1TB                                           | 4        | 0.72%   |
| Toshiba HDWD110 1TB                                                | 4        | 0.72%   |
| Toshiba DT01ACA050 500GB                                           | 4        | 0.72%   |
| Seagate ST4000DM004-2CV104 4TB                                     | 4        | 0.72%   |
| Sandisk WD Blue SN550 NVMe SSD 250GB                               | 4        | 0.72%   |
| SanDisk SSD PLUS 1000GB                                            | 4        | 0.72%   |
| Samsung NVMe SSD Drive 500GB                                       | 4        | 0.72%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive 1024GB | 4        | 0.72%   |
| WDC WD60EZAZ-00SF3B0 6TB                                           | 3        | 0.54%   |
| WDC WD20EZRZ-00Z5HB0 2TB                                           | 3        | 0.54%   |
| WDC WD10EALX-009BA0 1TB                                            | 3        | 0.54%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 500GB              | 3        | 0.54%   |
| Seagate ST3320820AS 320GB                                          | 3        | 0.54%   |
| Seagate ST3000DM001-1ER166 3TB                                     | 3        | 0.54%   |
| Seagate ST2000DL003-9VT166 2TB                                     | 3        | 0.54%   |
| Seagate ST1000DM003-1CH162 1TB                                     | 3        | 0.54%   |
| Seagate Portable 1TB                                               | 3        | 0.54%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB                  | 3        | 0.54%   |
| SanDisk NVMe SSD Drive 1TB                                         | 3        | 0.54%   |
| Samsung SSD 980 1TB                                                | 3        | 0.54%   |
| Samsung SSD 970 EVO 250GB                                          | 3        | 0.54%   |
| Samsung SSD 860 QVO 1TB                                            | 3        | 0.54%   |
| Samsung SSD 860 EVO 250GB                                          | 3        | 0.54%   |
| Samsung SSD 860 EVO 1TB                                            | 3        | 0.54%   |
| Samsung SSD 850 EVO 500GB                                          | 3        | 0.54%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB                | 3        | 0.54%   |
| PNY CS900 240GB SSD                                                | 3        | 0.54%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                                | 3        | 0.54%   |
| XPG NVMe SSD Drive 512GB                                           | 2        | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 72       | 116    | 36.92%  |
| WDC                 | 69       | 122    | 35.38%  |
| Toshiba             | 27       | 34     | 13.85%  |
| Hitachi             | 10       | 10     | 5.13%   |
| Samsung Electronics | 4        | 4      | 2.05%   |
| HGST                | 4        | 10     | 2.05%   |
| Intenso             | 3        | 4      | 1.54%   |
| Unknown             | 2        | 2      | 1.03%   |
| LaCie               | 1        | 1      | 0.51%   |
| Inateck             | 1        | 1      | 0.51%   |
| Hewlett-Packard     | 1        | 1      | 0.51%   |
| ASMedia             | 1        | 2      | 0.51%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 36       | 63     | 25.35%  |
| Crucial             | 18       | 23     | 12.68%  |
| Kingston            | 14       | 20     | 9.86%   |
| SanDisk             | 13       | 19     | 9.15%   |
| WDC                 | 9        | 9      | 6.34%   |
| A-DATA Technology   | 6        | 9      | 4.23%   |
| Toshiba             | 4        | 7      | 2.82%   |
| PNY                 | 4        | 4      | 2.82%   |
| OCZ                 | 4        | 4      | 2.82%   |
| China               | 4        | 6      | 2.82%   |
| SPCC                | 3        | 3      | 2.11%   |
| Emtec               | 3        | 5      | 2.11%   |
| Transcend           | 2        | 2      | 1.41%   |
| TO Exter            | 2        | 2      | 1.41%   |
| Team                | 2        | 3      | 1.41%   |
| SK hynix            | 2        | 4      | 1.41%   |
| LITEONIT            | 2        | 2      | 1.41%   |
| USB30               | 1        | 2      | 0.7%    |
| Unknown             | 1        | 1      | 0.7%    |
| T-FORCE             | 1        | 1      | 0.7%    |
| Qumo                | 1        | 1      | 0.7%    |
| Plextor             | 1        | 1      | 0.7%    |
| Neo                 | 1        | 1      | 0.7%    |
| Mushkin             | 1        | 1      | 0.7%    |
| Micron Technology   | 1        | 1      | 0.7%    |
| LITEON              | 1        | 1      | 0.7%    |
| HS-SSD-C100         | 1        | 1      | 0.7%    |
| GOODRAM             | 1        | 1      | 0.7%    |
| Fanxiang            | 1        | 1      | 0.7%    |
| DEXP                | 1        | 1      | 0.7%    |
| ADATA SU            | 1        | 1      | 0.7%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 140      | 307    | 38.78%  |
| SSD     | 106      | 200    | 29.36%  |
| NVMe    | 103      | 198    | 28.53%  |
| Unknown | 12       | 12     | 3.32%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 161      | 476    | 55.14%  |
| NVMe | 103      | 196    | 35.27%  |
| SAS  | 28       | 45     | 9.59%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 107      | 209    | 36.03%  |
| 0.51-1.0   | 93       | 140    | 31.31%  |
| 1.01-2.0   | 52       | 86     | 17.51%  |
| 3.01-4.0   | 16       | 30     | 5.39%   |
| 4.01-10.0  | 14       | 18     | 4.71%   |
| 2.01-3.0   | 13       | 21     | 4.38%   |
| 10.01-20.0 | 2        | 3      | 0.67%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 99       | 53.51%  |
| 1001-2000      | 32       | 17.3%   |
| 2001-3000      | 23       | 12.43%  |
| 501-1000       | 15       | 8.11%   |
| 251-500        | 9        | 4.86%   |
| Unknown        | 3        | 1.62%   |
| 101-250        | 2        | 1.08%   |
| 1-20           | 2        | 1.08%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 32       | 16.41%  |
| More than 3000 | 31       | 15.9%   |
| 1001-2000      | 29       | 14.87%  |
| 501-1000       | 29       | 14.87%  |
| 101-250        | 28       | 14.36%  |
| 2001-3000      | 22       | 11.28%  |
| 51-100         | 14       | 7.18%   |
| 21-50          | 4        | 2.05%   |
| 1-20           | 3        | 1.54%   |
| Unknown        | 3        | 1.54%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                   | Desktops | Drives | Percent |
|---------------------------------------------------------|----------|--------|---------|
| Toshiba DT01ACA050 500GB                                | 2        | 2      | 4.88%   |
| Intenso USB 3.0 device 1TB                              | 2        | 2      | 4.88%   |
| WDC WD6400AAKS-65A7B0 640GB                             | 1        | 1      | 2.44%   |
| WDC WD5000AAKX-60U6AA0 500GB                            | 1        | 1      | 2.44%   |
| WDC WD5000AAKX-003CA0 500GB                             | 1        | 2      | 2.44%   |
| WDC WD5000AAKS-00E4A0 500GB                             | 1        | 1      | 2.44%   |
| WDC WD30EZRX-00DC0B0 3TB                                | 1        | 1      | 2.44%   |
| WDC WD30EFRX-68EUZN0 3TB                                | 1        | 2      | 2.44%   |
| WDC WD20EARX-00PASB0 2TB                                | 1        | 1      | 2.44%   |
| WDC WD20EARS-00MVWB0 2TB                                | 1        | 1      | 2.44%   |
| WDC WD10EZRX-00L4HB0 1TB                                | 1        | 1      | 2.44%   |
| WDC WD10EZEX-60ZF5A0 1TB                                | 1        | 1      | 2.44%   |
| WDC WD10EARS-00Y5B1 1TB                                 | 1        | 1      | 2.44%   |
| WDC WD10EALX-009BA0 1TB                                 | 1        | 1      | 2.44%   |
| WDC WD10EADS-22M2B0 1TB                                 | 1        | 1      | 2.44%   |
| WDC WD10EADS-00M2B0 1TB                                 | 1        | 1      | 2.44%   |
| Toshiba DT01ACA100 1TB                                  | 1        | 1      | 2.44%   |
| Seagate ST9250827AS 250GB                               | 1        | 1      | 2.44%   |
| Seagate ST4000DM004-2CV104 4TB                          | 1        | 1      | 2.44%   |
| Seagate ST3000DM003-1F216N 3TB                          | 1        | 1      | 2.44%   |
| Seagate ST2000LM003 HN-M201RAD 2TB                      | 1        | 1      | 2.44%   |
| Seagate ST2000DX002-2DV164 2TB                          | 1        | 2      | 2.44%   |
| Seagate ST2000DL003-9VT166 2TB                          | 1        | 1      | 2.44%   |
| SanDisk SD6SF1M128G1022I 128GB SSD                      | 1        | 1      | 2.44%   |
| Samsung Electronics SSD 980 1TB                         | 1        | 7      | 2.44%   |
| Samsung Electronics SSD 960 EVO 250GB                   | 1        | 5      | 2.44%   |
| Samsung Electronics SSD 850 PRO 512GB                   | 1        | 2      | 2.44%   |
| Realtek Semiconductor RTS5763DL NVMe SSD Controller 1TB | 1        | 2      | 2.44%   |
| OCZ TRION100 480GB SSD                                  | 1        | 1      | 2.44%   |
| Kingston SV300S37A120G 120GB SSD                        | 1        | 1      | 2.44%   |
| Kingston SH103S3240G 240GB SSD                          | 1        | 1      | 2.44%   |
| Hitachi HTS543216L9A300 160GB                           | 1        | 1      | 2.44%   |
| Hitachi HDT721032SLA360 320GB                           | 1        | 1      | 2.44%   |
| Hitachi HDS722020ALA330 2TB                             | 1        | 1      | 2.44%   |
| HGST HTS725050A7E635 OPAL 500GB                         | 1        | 3      | 2.44%   |
| HGST HTS725050A7E630 500GB                              | 1        | 4      | 2.44%   |
| Hewlett-Packard SSD EX900 500GB                         | 1        | 1      | 2.44%   |
| Crucial CT960M500SSD1 960GB                             | 1        | 1      | 2.44%   |
| A-DATA Technology SU800 1TB SSD                         | 1        | 1      | 2.44%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| WDC                   | 12       | 16     | 32.43%  |
| Seagate               | 6        | 7      | 16.22%  |
| Toshiba               | 3        | 3      | 8.11%   |
| Hitachi               | 3        | 3      | 8.11%   |
| Samsung Electronics   | 2        | 14     | 5.41%   |
| Kingston              | 2        | 2      | 5.41%   |
| Intenso               | 2        | 2      | 5.41%   |
| SanDisk               | 1        | 1      | 2.7%    |
| Realtek Semiconductor | 1        | 2      | 2.7%    |
| OCZ                   | 1        | 1      | 2.7%    |
| HGST                  | 1        | 7      | 2.7%    |
| Hewlett-Packard       | 1        | 1      | 2.7%    |
| Crucial               | 1        | 1      | 2.7%    |
| A-DATA Technology     | 1        | 1      | 2.7%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 12       | 16     | 44.44%  |
| Seagate | 6        | 7      | 22.22%  |
| Toshiba | 3        | 3      | 11.11%  |
| Hitachi | 3        | 3      | 11.11%  |
| Intenso | 2        | 2      | 7.41%   |
| HGST    | 1        | 7      | 3.7%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 22       | 38     | 68.75%  |
| SSD  | 7        | 8      | 21.88%  |
| NVMe | 3        | 15     | 9.38%   |

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


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 107      | 351    | 46.93%  |
| Works    | 92       | 305    | 40.35%  |
| Malfunc  | 29       | 61     | 12.72%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| AMD                          | 99       | 31.43%  |
| Intel                        | 83       | 26.35%  |
| Samsung Electronics          | 46       | 14.6%   |
| SanDisk                      | 18       | 5.71%   |
| Kingston Technology Company  | 10       | 3.17%   |
| ASMedia Technology           | 10       | 3.17%   |
| Silicon Motion               | 9        | 2.86%   |
| Phison Electronics           | 9        | 2.86%   |
| Micron/Crucial Technology    | 8        | 2.54%   |
| ADATA Technology             | 6        | 1.9%    |
| Marvell Technology Group     | 5        | 1.59%   |
| Realtek Semiconductor        | 3        | 0.95%   |
| Seagate Technology           | 2        | 0.63%   |
| JMicron Technology           | 2        | 0.63%   |
| Union Memory (Shenzhen)      | 1        | 0.32%   |
| Toshiba America Info Systems | 1        | 0.32%   |
| SK hynix                     | 1        | 0.32%   |
| Shenzhen Longsys Electronics | 1        | 0.32%   |
| MAXIO Technology (Hangzhou)  | 1        | 0.32%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 63       | 16.36%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 33       | 8.57%   |
| AMD 400 Series Chipset SATA Controller                                                  | 23       | 5.97%   |
| AMD 500 Series Chipset SATA Controller                                                  | 20       | 5.19%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 15       | 3.9%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 10       | 2.6%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 10       | 2.6%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 9        | 2.34%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 7        | 1.82%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 7        | 1.82%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 7        | 1.82%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 7        | 1.82%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 6        | 1.56%   |
| Phison E12 NVMe Controller                                                              | 6        | 1.56%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 6        | 1.56%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 6        | 1.56%   |
| AMD 300 Series Chipset SATA Controller                                                  | 6        | 1.56%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 6        | 1.56%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 5        | 1.3%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5        | 1.3%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5        | 1.3%    |
| AMD FCH SATA Controller D                                                               | 5        | 1.3%    |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 4        | 1.04%   |
| Kingston Company KC3000/Renegade NVMe SSD                                               | 4        | 1.04%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 4        | 1.04%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 4        | 1.04%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 3        | 0.78%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 3        | 0.78%   |
| Samsung NVMe SSD Controller 980                                                         | 3        | 0.78%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 3        | 0.78%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 3        | 0.78%   |
| Intel SSD 660P Series                                                                   | 3        | 0.78%   |
| Intel SATA Controller [RAID mode]                                                       | 3        | 0.78%   |
| Intel PROSet/Wireless WiFi Software extension                                           | 3        | 0.78%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3        | 0.78%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3        | 0.78%   |
| AMD X399 Series Chipset SATA Controller                                                 | 3        | 0.78%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3        | 0.78%   |
| Seagate FireCuda 530 SSD                                                                | 2        | 0.52%   |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                                       | 2        | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 167      | 56.42%  |
| NVMe | 104      | 35.14%  |
| IDE  | 15       | 5.07%   |
| RAID | 10       | 3.38%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 101      | 55.19%  |
| Intel  | 82       | 44.81%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 7 3700X 8-Core Processor          | 7        | 3.8%    |
| AMD Ryzen 9 3900X 12-Core Processor         | 6        | 3.26%   |
| AMD Ryzen 5 3600 6-Core Processor           | 6        | 3.26%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 5        | 2.72%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 5        | 2.72%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 4        | 2.17%   |
| Intel 12th Gen Core i5-12600K               | 4        | 2.17%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 4        | 2.17%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 4        | 2.17%   |
| AMD Ryzen 9 7900X 12-Core Processor         | 3        | 1.63%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 3        | 1.63%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 3        | 1.63%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 3        | 1.63%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 3        | 1.63%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 3        | 1.63%   |
| AMD FX-8350 Eight-Core Processor            | 3        | 1.63%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 2        | 1.09%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 2        | 1.09%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 2        | 1.09%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 2        | 1.09%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 2        | 1.09%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 1.09%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 2        | 1.09%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 2        | 1.09%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 2        | 1.09%   |
| AMD Ryzen 9 6900HX with Radeon Graphics     | 2        | 1.09%   |
| AMD Ryzen 7 5800X3D 8-Core Processor        | 2        | 1.09%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 2        | 1.09%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 2        | 1.09%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 2        | 1.09%   |
| AMD Ryzen 5 1600X Six-Core Processor        | 2        | 1.09%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 2        | 1.09%   |
| Intel Xeon CPU W3550 @ 3.07GHz              | 1        | 0.54%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz          | 1        | 0.54%   |
| Intel Xeon CPU E5-1680 v2 @ 3.00GHz         | 1        | 0.54%   |
| Intel Xeon CPU E3-1246 v3 @ 3.50GHz         | 1        | 0.54%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 1        | 0.54%   |
| Intel Pentium CPU G4600 @ 3.60GHz           | 1        | 0.54%   |
| Intel Core i9-10900K CPU @ 3.70GHz          | 1        | 0.54%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 1        | 0.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| AMD Ryzen 7             | 31       | 16.94%  |
| AMD Ryzen 5             | 30       | 16.39%  |
| Intel Core i5           | 25       | 13.66%  |
| Intel Core i7           | 22       | 12.02%  |
| AMD Ryzen 9             | 18       | 9.84%   |
| Intel Core i3           | 15       | 8.2%    |
| Other                   | 9        | 4.92%   |
| AMD Ryzen 3             | 6        | 3.28%   |
| AMD FX                  | 5        | 2.73%   |
| Intel Xeon              | 4        | 2.19%   |
| AMD Ryzen Threadripper  | 3        | 1.64%   |
| Intel Celeron           | 2        | 1.09%   |
| AMD A10                 | 2        | 1.09%   |
| Intel Pentium Dual-Core | 1        | 0.55%   |
| Intel Pentium           | 1        | 0.55%   |
| Intel Core i9           | 1        | 0.55%   |
| Intel Core 2 Quad       | 1        | 0.55%   |
| Intel Core 2 Duo        | 1        | 0.55%   |
| AMD Phenom II X6        | 1        | 0.55%   |
| AMD Phenom II X4        | 1        | 0.55%   |
| AMD Phenom II X2        | 1        | 0.55%   |
| AMD Athlon X4           | 1        | 0.55%   |
| AMD Athlon              | 1        | 0.55%   |
| AMD A8                  | 1        | 0.55%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 55       | 30.05%  |
| 8      | 43       | 23.5%   |
| 6      | 37       | 20.22%  |
| 2      | 24       | 13.11%  |
| 12     | 12       | 6.56%   |
| 16     | 5        | 2.73%   |
| 10     | 5        | 2.73%   |
| 24     | 1        | 0.55%   |
| 3      | 1        | 0.55%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 183      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 145      | 79.23%  |
| 1      | 38       | 20.77%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 183      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 91       | 48.66%  |
| 0x08701021 | 9        | 4.81%   |
| 0x306c3    | 7        | 3.74%   |
| 0x0800820d | 7        | 3.74%   |
| 0x306a9    | 5        | 2.67%   |
| 0x206a7    | 4        | 2.14%   |
| 0x0a601203 | 4        | 2.14%   |
| 0x0a20120a | 4        | 2.14%   |
| 0x906ea    | 3        | 1.6%    |
| 0x506e3    | 3        | 1.6%    |
| 0x0a50000d | 3        | 1.6%    |
| 0x0a50000c | 3        | 1.6%    |
| 0x0a201009 | 3        | 1.6%    |
| 0x08108109 | 3        | 1.6%    |
| 0x08001137 | 3        | 1.6%    |
| 0xa0653    | 2        | 1.07%   |
| 0x906ed    | 2        | 1.07%   |
| 0x906e9    | 2        | 1.07%   |
| 0x90672    | 2        | 1.07%   |
| 0x0a404102 | 2        | 1.07%   |
| 0x0a201204 | 2        | 1.07%   |
| 0x0a201025 | 2        | 1.07%   |
| 0x0810100b | 2        | 1.07%   |
| 0x08001138 | 2        | 1.07%   |
| 0x06000852 | 2        | 1.07%   |
| 0xa0655    | 1        | 0.53%   |
| 0x906ec    | 1        | 0.53%   |
| 0x906eb    | 1        | 0.53%   |
| 0x90675    | 1        | 0.53%   |
| 0x106a5    | 1        | 0.53%   |
| 0x1067a    | 1        | 0.53%   |
| 0x0a601201 | 1        | 0.53%   |
| 0x0a50000b | 1        | 0.53%   |
| 0x0a201016 | 1        | 0.53%   |
| 0x08701030 | 1        | 0.53%   |
| 0x08701013 | 1        | 0.53%   |
| 0x08101016 | 1        | 0.53%   |
| 0x06003106 | 1        | 0.53%   |
| 0x010000dc | 1        | 0.53%   |
| 0x00000000 | 1        | 0.53%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 3            | 28       | 15.22%  |
| Zen 2            | 24       | 13.04%  |
| Zen+             | 19       | 10.33%  |
| KabyLake         | 17       | 9.24%   |
| Haswell          | 17       | 9.24%   |
| Zen              | 12       | 6.52%   |
| IvyBridge        | 11       | 5.98%   |
| Unknown          | 11       | 5.98%   |
| SandyBridge      | 10       | 5.43%   |
| CometLake        | 7        | 3.8%    |
| Piledriver       | 6        | 3.26%   |
| Skylake          | 5        | 2.72%   |
| Alderlake Hybrid | 4        | 2.17%   |
| Steamroller      | 3        | 1.63%   |
| Penryn           | 3        | 1.63%   |
| K10              | 3        | 1.63%   |
| Westmere         | 1        | 0.54%   |
| Nehalem          | 1        | 0.54%   |
| Icelake          | 1        | 0.54%   |
| Broadwell        | 1        | 0.54%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 94       | 45.85%  |
| Nvidia | 74       | 36.1%   |
| Intel  | 37       | 18.05%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 15       | 7.04%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 12       | 5.63%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 10       | 4.69%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 10       | 4.69%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 7        | 3.29%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 6        | 2.82%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 5        | 2.35%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 5        | 2.35%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 5        | 2.35%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 4        | 1.88%   |
| Nvidia GK208B [GeForce GT 710]                                              | 4        | 1.88%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 4        | 1.88%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                      | 3        | 1.41%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 3        | 1.41%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 3        | 1.41%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 3        | 1.41%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 3        | 1.41%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 3        | 1.41%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 3        | 1.41%   |
| Intel HD Graphics 630                                                       | 3        | 1.41%   |
| Intel AlderLake-S GT1                                                       | 3        | 1.41%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 1.41%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 3        | 1.41%   |
| AMD Raphael                                                                 | 3        | 1.41%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 3        | 1.41%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 2        | 0.94%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 2        | 0.94%   |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 0.94%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 2        | 0.94%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 2        | 0.94%   |
| Nvidia GM204 [GeForce GTX 980]                                              | 2        | 0.94%   |
| Nvidia GK208 [GeForce GT 635]                                               | 2        | 0.94%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 2        | 0.94%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 2        | 0.94%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 2        | 0.94%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 2        | 0.94%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 0.94%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 0.94%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 0.94%   |
| AMD Tahiti PRO [Radeon HD 7950/8950 OEM / R9 280]                           | 2        | 0.94%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 80       | 42.78%  |
| 1 x Nvidia     | 64       | 34.22%  |
| 1 x Intel      | 23       | 12.3%   |
| 2 x AMD        | 6        | 3.21%   |
| AMD + Nvidia   | 6        | 3.21%   |
| Intel + AMD    | 3        | 1.6%    |
| 2 x Nvidia     | 2        | 1.07%   |
| Intel + Nvidia | 2        | 1.07%   |
| 2 x Intel      | 1        | 0.53%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 122      | 65.59%  |
| Proprietary | 63       | 33.87%  |
| Unknown     | 1        | 0.54%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 71       | 37.77%  |
| 7.01-8.0   | 31       | 16.49%  |
| 8.01-16.0  | 23       | 12.23%  |
| 3.01-4.0   | 20       | 10.64%  |
| 1.01-2.0   | 16       | 8.51%   |
| 5.01-6.0   | 8        | 4.26%   |
| 0.51-1.0   | 7        | 3.72%   |
| 0.01-0.5   | 7        | 3.72%   |
| 16.01-24.0 | 3        | 1.6%    |
| 2.01-3.0   | 2        | 1.06%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 36       | 15.13%  |
| Goldstar             | 24       | 10.08%  |
| Acer                 | 22       | 9.24%   |
| Dell                 | 21       | 8.82%   |
| AOC                  | 18       | 7.56%   |
| Hewlett-Packard      | 14       | 5.88%   |
| BenQ                 | 11       | 4.62%   |
| Ancor Communications | 11       | 4.62%   |
| Unknown              | 7        | 2.94%   |
| Philips              | 6        | 2.52%   |
| MSI                  | 6        | 2.52%   |
| ASUSTek Computer     | 6        | 2.52%   |
| ViewSonic            | 5        | 2.1%    |
| Iiyama               | 5        | 2.1%    |
| Gigabyte Technology  | 5        | 2.1%    |
| Sony                 | 3        | 1.26%   |
| NEC Computers        | 3        | 1.26%   |
| Vizio                | 2        | 0.84%   |
| Toshiba              | 2        | 0.84%   |
| Mi                   | 2        | 0.84%   |
| LG Electronics       | 2        | 0.84%   |
| Lenovo               | 2        | 0.84%   |
| Insignia             | 2        | 0.84%   |
| Xiaomi               | 1        | 0.42%   |
| VIZ                  | 1        | 0.42%   |
| Viotek               | 1        | 0.42%   |
| Vestel               | 1        | 0.42%   |
| RTK                  | 1        | 0.42%   |
| Optoma               | 1        | 0.42%   |
| ONN                  | 1        | 0.42%   |
| MiTAC                | 1        | 0.42%   |
| Microstep            | 1        | 0.42%   |
| LTM                  | 1        | 0.42%   |
| Lenovo Group Limited | 1        | 0.42%   |
| Idek Iiyama          | 1        | 0.42%   |
| HUAWEI               | 1        | 0.42%   |
| HPN                  | 1        | 0.42%   |
| HKC                  | 1        | 0.42%   |
| Hitachi              | 1        | 0.42%   |
| HannStar Display     | 1        | 0.42%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 3        | 1.17%   |
| Goldstar LG TV SSCR2 GSMC0C8 3840x2160                                 | 3        | 1.17%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 3        | 1.17%   |
| ViewSonic VX3258 series VSCDE35 2560x1440 700x390mm 31.5-inch          | 2        | 0.78%   |
| Samsung Electronics S34J55x SAM0F72 3440x1440 797x333mm 34.0-inch      | 2        | 0.78%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch               | 2        | 0.78%   |
| MSI G273 MSI3CA7 1920x1080 590x330mm 26.6-inch                         | 2        | 0.78%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch               | 2        | 0.78%   |
| Dell U2312HM DEL4073 1920x1080 510x287mm 23.0-inch                     | 2        | 0.78%   |
| Dell 1909W DELA03C 1440x900 408x255mm 18.9-inch                        | 2        | 0.78%   |
| AOC Q32G1WG4 AOC3201 2560x1440 697x393mm 31.5-inch                     | 2        | 0.78%   |
| AOC Q27P1B AOC2701 2560x1440 597x336mm 27.0-inch                       | 2        | 0.78%   |
| AOC 2460G4 AOC0001 1920x1080 530x300mm 24.0-inch                       | 2        | 0.78%   |
| Ancor Communications ASUS PB287Q ACI28A3 3840x2160 621x341mm 27.9-inch | 2        | 0.78%   |
| Acer X223W ACR0009 1680x1050 473x296mm 22.0-inch                       | 2        | 0.78%   |
| Acer ED322Q ACR0574 1920x1080 521x293mm 23.5-inch                      | 2        | 0.78%   |
| Xiaomi Mi TV XMD009A 3440x1440 480x270mm 21.7-inch                     | 1        | 0.39%   |
| Vizio P502ui-B1E VIZ1013 3840x2160 1095x616mm 49.5-inch                | 1        | 0.39%   |
| Vizio E231-B1 VIZ0095 1360x768 534x311mm 24.3-inch                     | 1        | 0.39%   |
| VIZ LCD Monitor D40f-J09 1920x1080                                     | 1        | 0.39%   |
| Viotek VIOTEKGN27C2 VTK0027 1920x1080 598x336mm 27.0-inch              | 1        | 0.39%   |
| ViewSonic VX3276-QHD VSCE635 2560x1440 698x393mm 31.5-inch             | 1        | 0.39%   |
| ViewSonic VX2270 SERIES VSCE02C 1920x1080 476x267mm 21.5-inch          | 1        | 0.39%   |
| ViewSonic VA2415 SERIES VSCBC3C 1920x1080 521x293mm 23.5-inch          | 1        | 0.39%   |
| Vestel LCD Monitor 24W_LCD_TV 1920x1080                                | 1        | 0.39%   |
| Unknown LCD Monitor XXX AAA 1366x768                                   | 1        | 0.39%   |
| Unknown LCD Monitor SAMSUNG 3840x2160                                  | 1        | 0.39%   |
| Unknown LCD Monitor SAMSUNG                                            | 1        | 0.39%   |
| Unknown LCD Monitor RJT HDMI                                           | 1        | 0.39%   |
| Unknown LCD Monitor LHC 32-QHD-144-C 4480x1440                         | 1        | 0.39%   |
| Unknown LCD Monitor Hitachi/HINT W240D DVI                             | 1        | 0.39%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch              | 1        | 0.39%   |
| Toshiba TV TSB0206 1920x1080 1600x1000mm 74.3-inch                     | 1        | 0.39%   |
| Toshiba TV TSB0105 1920x1080 708x398mm 32.0-inch                       | 1        | 0.39%   |
| Sony TV SNY4B03 1920x1080 708x398mm 32.0-inch                          | 1        | 0.39%   |
| Sony TV SNY1802 1920x1080                                              | 1        | 0.39%   |
| Sony TV SNY0801 1360x768                                               | 1        | 0.39%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch      | 1        | 0.39%   |
| Samsung Electronics U28E850 SAM0CCB 3840x2160 607x345mm 27.5-inch      | 1        | 0.39%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch      | 1        | 0.39%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 100      | 44.05%  |
| 3840x2160 (4K)     | 32       | 14.1%   |
| 2560x1440 (QHD)    | 18       | 7.93%   |
| 3440x1440          | 11       | 4.85%   |
| Unknown            | 9        | 3.96%   |
| 1366x768 (WXGA)    | 8        | 3.52%   |
| 2560x1080          | 7        | 3.08%   |
| 1680x1050 (WSXGA+) | 7        | 3.08%   |
| 1280x1024 (SXGA)   | 6        | 2.64%   |
| 3840x1080          | 5        | 2.2%    |
| 1920x1200 (WUXGA)  | 5        | 2.2%    |
| 1440x900 (WXGA+)   | 5        | 2.2%    |
| 1600x900 (HD+)     | 3        | 1.32%   |
| 7680x2160          | 2        | 0.88%   |
| 1360x768           | 2        | 0.88%   |
| 9600x2160          | 1        | 0.44%   |
| 4480x1440          | 1        | 0.44%   |
| 3840x1200          | 1        | 0.44%   |
| 2288x1287          | 1        | 0.44%   |
| 2048x1152          | 1        | 0.44%   |
| 1920x540           | 1        | 0.44%   |
| 1280x720 (HD)      | 1        | 0.44%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 44       | 19.13%  |
| 24      | 34       | 14.78%  |
| Unknown | 31       | 13.48%  |
| 23      | 24       | 10.43%  |
| 21      | 15       | 6.52%   |
| 34      | 13       | 5.65%   |
| 31      | 13       | 5.65%   |
| 19      | 8        | 3.48%   |
| 22      | 7        | 3.04%   |
| 72      | 5        | 2.17%   |
| 20      | 4        | 1.74%   |
| 18      | 4        | 1.74%   |
| 25      | 3        | 1.3%    |
| 74      | 2        | 0.87%   |
| 49      | 2        | 0.87%   |
| 48      | 2        | 0.87%   |
| 40      | 2        | 0.87%   |
| 28      | 2        | 0.87%   |
| 26      | 2        | 0.87%   |
| 17      | 2        | 0.87%   |
| 142     | 1        | 0.43%   |
| 84      | 1        | 0.43%   |
| 58      | 1        | 0.43%   |
| 54      | 1        | 0.43%   |
| 50      | 1        | 0.43%   |
| 47      | 1        | 0.43%   |
| 46      | 1        | 0.43%   |
| 43      | 1        | 0.43%   |
| 33      | 1        | 0.43%   |
| 29      | 1        | 0.43%   |
| 16      | 1        | 0.43%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 91       | 41.55%  |
| 401-500        | 33       | 15.07%  |
| Unknown        | 31       | 14.16%  |
| 601-700        | 22       | 10.05%  |
| 701-800        | 14       | 6.39%   |
| 1001-1500      | 9        | 4.11%   |
| 1501-2000      | 8        | 3.65%   |
| 351-400        | 5        | 2.28%   |
| 801-900        | 2        | 0.91%   |
| 301-350        | 2        | 0.91%   |
| More than 2000 | 1        | 0.46%   |
| 901-1000       | 1        | 0.46%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 128      | 63.37%  |
| Unknown | 29       | 14.36%  |
| 16/10   | 21       | 10.4%   |
| 21/9    | 14       | 6.93%   |
| 5/4     | 6        | 2.97%   |
| 32/9    | 3        | 1.49%   |
| 1.00    | 1        | 0.5%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 62       | 27.93%  |
| 301-350        | 46       | 20.72%  |
| Unknown        | 31       | 13.96%  |
| 351-500        | 29       | 13.06%  |
| More than 1000 | 14       | 6.31%   |
| 151-200        | 14       | 6.31%   |
| 251-300        | 13       | 5.86%   |
| 501-1000       | 7        | 3.15%   |
| 141-150        | 5        | 2.25%   |
| 121-130        | 1        | 0.45%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 112      | 55.17%  |
| 101-120 | 35       | 17.24%  |
| Unknown | 31       | 15.27%  |
| 1-50    | 10       | 4.93%   |
| 121-160 | 10       | 4.93%   |
| 161-240 | 5        | 2.46%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 118      | 62.77%  |
| 2     | 49       | 26.06%  |
| 3     | 15       | 7.98%   |
| 0     | 4        | 2.13%   |
| 4     | 2        | 1.06%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 123      | 43.93%  |
| Intel                           | 88       | 31.43%  |
| Qualcomm Atheros                | 12       | 4.29%   |
| MediaTek                        | 11       | 3.93%   |
| Broadcom                        | 6        | 2.14%   |
| TP-Link                         | 4        | 1.43%   |
| Ralink Technology               | 4        | 1.43%   |
| NetGear                         | 4        | 1.43%   |
| Microsoft                       | 4        | 1.43%   |
| Linksys                         | 4        | 1.43%   |
| Aquantia                        | 3        | 1.07%   |
| Ralink                          | 2        | 0.71%   |
| DisplayLink                     | 2        | 0.71%   |
| AVM                             | 2        | 0.71%   |
| Xiaomi                          | 1        | 0.36%   |
| Sitecom Europe                  | 1        | 0.36%   |
| Samsung Electronics             | 1        | 0.36%   |
| Qualcomm Atheros Communications | 1        | 0.36%   |
| InterBiometrics                 | 1        | 0.36%   |
| Holtek Semiconductor            | 1        | 0.36%   |
| D-Link                          | 1        | 0.36%   |
| Belkin Components               | 1        | 0.36%   |
| ASIX Electronics                | 1        | 0.36%   |
| Alteon Networks                 | 1        | 0.36%   |
| Accton Technology               | 1        | 0.36%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 94       | 29.38%  |
| Realtek RTL8125 2.5GbE Controller                                   | 21       | 6.56%   |
| Intel I211 Gigabit Network Connection                               | 20       | 6.25%   |
| Intel Ethernet Controller I225-V                                    | 15       | 4.69%   |
| Intel Wi-Fi 6 AX200                                                 | 13       | 4.06%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 8        | 2.5%    |
| Intel Wireless-AC 9260                                              | 8        | 2.5%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 7        | 2.19%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                             | 6        | 1.88%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                              | 6        | 1.88%   |
| Intel Ethernet Connection I217-LM                                   | 6        | 1.88%   |
| Intel Ethernet Connection (2) I219-V                                | 5        | 1.56%   |
| Microsoft Xbox Wireless Adapter for Windows                         | 4        | 1.25%   |
| Ralink RT2870/RT3070 Wireless Adapter                               | 3        | 0.94%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 3        | 0.94%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter       | 3        | 0.94%   |
| Intel Wireless 7265                                                 | 3        | 0.94%   |
| Intel 82579V Gigabit Network Connection                             | 3        | 0.94%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 3        | 0.94%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                     | 2        | 0.63%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 2        | 0.63%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter          | 2        | 0.63%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                            | 2        | 0.63%   |
| NetGear A6210                                                       | 2        | 0.63%   |
| Linksys AE6000 802.11a/b/g/n/ac Wireless Adapter [MediaTek MT7610U] | 2        | 0.63%   |
| Intel Tiger Lake PCH CNVi WiFi                                      | 2        | 0.63%   |
| Intel Ethernet Connection (7) I219-V                                | 2        | 0.63%   |
| Intel Ethernet Connection (2) I218-V                                | 2        | 0.63%   |
| Intel Comet Lake PCH CNVi WiFi                                      | 2        | 0.63%   |
| AVM FRITZ!WLAN AC 860                                               | 2        | 0.63%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]   | 2        | 0.63%   |
| Xiaomi Mi/Redmi series (RNDIS)                                      | 1        | 0.31%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                         | 1        | 0.31%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                        | 1        | 0.31%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                          | 1        | 0.31%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]          | 1        | 0.31%   |
| Sitecom Europe WLA-5000 802.11abgn [Ralink RT3572]                  | 1        | 0.31%   |
| Samsung Galaxy series, misc. (tethering mode)                       | 1        | 0.31%   |
| Realtek USB 10/100/1G/2.5G LAN                                      | 1        | 0.31%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                  | 1        | 0.31%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 45       | 40.18%  |
| Realtek Semiconductor           | 21       | 18.75%  |
| MediaTek                        | 9        | 8.04%   |
| Qualcomm Atheros                | 5        | 4.46%   |
| TP-Link                         | 4        | 3.57%   |
| Ralink Technology               | 4        | 3.57%   |
| NetGear                         | 4        | 3.57%   |
| Microsoft                       | 4        | 3.57%   |
| Linksys                         | 4        | 3.57%   |
| Broadcom                        | 4        | 3.57%   |
| Ralink                          | 2        | 1.79%   |
| AVM                             | 2        | 1.79%   |
| Sitecom Europe                  | 1        | 0.89%   |
| Qualcomm Atheros Communications | 1        | 0.89%   |
| D-Link                          | 1        | 0.89%   |
| Accton Technology               | 1        | 0.89%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                           | 13       | 11.61%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 8        | 7.14%   |
| Intel Wireless-AC 9260                                                        | 8        | 7.14%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 7        | 6.25%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                       | 6        | 5.36%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 6        | 5.36%   |
| Microsoft Xbox Wireless Adapter for Windows                                   | 4        | 3.57%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 3        | 2.68%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                 | 3        | 2.68%   |
| Intel Wireless 7265                                                           | 3        | 2.68%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 2        | 1.79%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 2        | 1.79%   |
| NetGear A6210                                                                 | 2        | 1.79%   |
| Linksys AE6000 802.11a/b/g/n/ac Wireless Adapter [MediaTek MT7610U]           | 2        | 1.79%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 2        | 1.79%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 2        | 1.79%   |
| AVM FRITZ!WLAN AC 860                                                         | 2        | 1.79%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 1        | 0.89%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 1        | 0.89%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                    | 1        | 0.89%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 1        | 0.89%   |
| Sitecom Europe WLA-5000 802.11abgn [Ralink RT3572]                            | 1        | 0.89%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 1        | 0.89%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                      | 1        | 0.89%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                           | 1        | 0.89%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                       | 1        | 0.89%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                               | 1        | 0.89%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                        | 1        | 0.89%   |
| Realtek RTL8188RU 802.11n WLAN Adapter                                        | 1        | 0.89%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                         | 1        | 0.89%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 1        | 0.89%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 1        | 0.89%   |
| Realtek 802.11n WLAN Adapter                                                  | 1        | 0.89%   |
| Ralink Wireless Adapter Canyon CN-WF511                                       | 1        | 0.89%   |
| Ralink MT7601U Wireless Adapter                                               | 1        | 0.89%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                        | 1        | 0.89%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 1        | 0.89%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 1        | 0.89%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1        | 0.89%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                              | 1        | 0.89%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 118      | 59%     |
| Intel                 | 60       | 30%     |
| Qualcomm Atheros      | 8        | 4%      |
| Aquantia              | 3        | 1.5%    |
| MediaTek              | 2        | 1%      |
| DisplayLink           | 2        | 1%      |
| Broadcom              | 2        | 1%      |
| Xiaomi                | 1        | 0.5%    |
| Samsung Electronics   | 1        | 0.5%    |
| Belkin Components     | 1        | 0.5%    |
| ASIX Electronics      | 1        | 0.5%    |
| Alteon Networks       | 1        | 0.5%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 94       | 45.63%  |
| Realtek RTL8125 2.5GbE Controller                                   | 21       | 10.19%  |
| Intel I211 Gigabit Network Connection                               | 20       | 9.71%   |
| Intel Ethernet Controller I225-V                                    | 15       | 7.28%   |
| Intel Ethernet Connection I217-LM                                   | 6        | 2.91%   |
| Intel Ethernet Connection (2) I219-V                                | 5        | 2.43%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 3        | 1.46%   |
| Intel 82579V Gigabit Network Connection                             | 3        | 1.46%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 3        | 1.46%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 2        | 0.97%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                            | 2        | 0.97%   |
| Intel Ethernet Connection (7) I219-V                                | 2        | 0.97%   |
| Intel Ethernet Connection (2) I218-V                                | 2        | 0.97%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]   | 2        | 0.97%   |
| Xiaomi Mi/Redmi series (RNDIS)                                      | 1        | 0.49%   |
| Samsung Galaxy series, misc. (tethering mode)                       | 1        | 0.49%   |
| Realtek USB 10/100/1G/2.5G LAN                                      | 1        | 0.49%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 1        | 0.49%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter               | 1        | 0.49%   |
| Realtek Killer E3000 2.5GbE Controller                              | 1        | 0.49%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                    | 1        | 0.49%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller           | 1        | 0.49%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                          | 1        | 0.49%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet      | 1        | 0.49%   |
| MediaTek Titan pocket                                               | 1        | 0.49%   |
| MediaTek 100026191                                                  | 1        | 0.49%   |
| Intel Ethernet Controller I225-LM                                   | 1        | 0.49%   |
| Intel Ethernet Connection I217-V                                    | 1        | 0.49%   |
| Intel Ethernet Connection (2) I219-LM                               | 1        | 0.49%   |
| Intel Ethernet Connection (14) I219-LM                              | 1        | 0.49%   |
| Intel 82576 Gigabit Network Connection                              | 1        | 0.49%   |
| Intel 82567LM-3 Gigabit Network Connection                          | 1        | 0.49%   |
| DisplayLink USB3.0 5K Graphic Docking                               | 1        | 0.49%   |
| DisplayLink ThinkPad USB 3.0 Dock                                   | 1        | 0.49%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express             | 1        | 0.49%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                     | 1        | 0.49%   |
| Belkin Components F5D5050 100Mbps Ethernet                          | 1        | 0.49%   |
| ASIX AX88179 Gigabit Ethernet                                       | 1        | 0.49%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 0.49%   |
| Alteon Networks Ethernet controller                                 | 1        | 0.49%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 181      | 63.51%  |
| WiFi     | 102      | 35.79%  |
| Modem    | 1        | 0.35%   |
| Unknown  | 1        | 0.35%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 139      | 72.02%  |
| WiFi     | 54       | 27.98%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 101      | 54.3%   |
| 2     | 69       | 37.1%   |
| 3     | 13       | 6.99%   |
| 0     | 2        | 1.08%   |
| 4     | 1        | 0.54%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 137      | 74.46%  |
| Yes  | 47       | 25.54%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 39       | 42.39%  |
| Cambridge Silicon Radio         | 15       | 16.3%   |
| Realtek Semiconductor           | 12       | 13.04%  |
| MediaTek                        | 7        | 7.61%   |
| ASUSTek Computer                | 7        | 7.61%   |
| Qualcomm Atheros Communications | 5        | 5.43%   |
| Broadcom                        | 3        | 3.26%   |
| IMC Networks                    | 2        | 2.17%   |
| Edimax Technology               | 1        | 1.09%   |
| Dynex                           | 1        | 1.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 15       | 16.3%   |
| Intel AX200 Bluetooth                                    | 11       | 11.96%  |
| Realtek Bluetooth Radio                                  | 8        | 8.7%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 8        | 8.7%    |
| MediaTek Wireless_Device                                 | 7        | 7.61%   |
| Intel Wireless-AC 3168 Bluetooth                         | 7        | 7.61%   |
| Realtek  Bluetooth 4.2 Adapter                           | 4        | 4.35%   |
| Qualcomm Atheros  Bluetooth Device                       | 4        | 4.35%   |
| Intel AX210 Bluetooth                                    | 4        | 4.35%   |
| Intel AX201 Bluetooth                                    | 4        | 4.35%   |
| Intel Bluetooth wireless interface                       | 3        | 3.26%   |
| IMC Networks Bluetooth Radio                             | 2        | 2.17%   |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 2        | 2.17%   |
| ASUS Bluetooth Radio                                     | 2        | 2.17%   |
| ASUS ASUS USB-BT500                                      | 2        | 2.17%   |
| Qualcomm Atheros AR3011 Bluetooth                        | 1        | 1.09%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 1        | 1.09%   |
| Intel Bluetooth Device                                   | 1        | 1.09%   |
| Edimax Bluetooth Adapter                                 | 1        | 1.09%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 1        | 1.09%   |
| Broadcom BCM43142A0 Bluetooth Device                     | 1        | 1.09%   |
| ASUS Qualcomm Bluetooth 4.1                              | 1        | 1.09%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 1        | 1.09%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE    | 1        | 1.09%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| AMD                      | 118      | 33.33%  |
| Intel                    | 81       | 22.88%  |
| Nvidia                   | 75       | 21.19%  |
| C-Media Electronics      | 12       | 3.39%   |
| Logitech                 | 10       | 2.82%   |
| Kingston Technology      | 5        | 1.41%   |
| Texas Instruments        | 4        | 1.13%   |
| Sony                     | 4        | 1.13%   |
| Blue Microphones         | 4        | 1.13%   |
| Trust                    | 3        | 0.85%   |
| JMTek                    | 3        | 0.85%   |
| Yamaha                   | 2        | 0.56%   |
| Razer USA                | 2        | 0.56%   |
| Generalplus Technology   | 2        | 0.56%   |
| DSEA A/S                 | 2        | 0.56%   |
| Digidesign               | 2        | 0.56%   |
| Creative Technology      | 2        | 0.56%   |
| Creative Labs            | 2        | 0.56%   |
| XMOS                     | 1        | 0.28%   |
| Tenx Technology          | 1        | 0.28%   |
| SteelSeries ApS          | 1        | 0.28%   |
| Scarlett                 | 1        | 0.28%   |
| Samson Technologies      | 1        | 0.28%   |
| RODE Microphones         | 1        | 0.28%   |
| ROCCAT                   | 1        | 0.28%   |
| Plantronics              | 1        | 0.28%   |
| Micro Star International | 1        | 0.28%   |
| KORG                     | 1        | 0.28%   |
| Hewlett-Packard          | 1        | 0.28%   |
| Harman International     | 1        | 0.28%   |
| Focusrite-Novation       | 1        | 0.28%   |
| EVGA                     | 1        | 0.28%   |
| DigiTech                 | 1        | 0.28%   |
| Audio-Technica           | 1        | 0.28%   |
| ASUSTek Computer         | 1        | 0.28%   |
| Astro Gaming             | 1        | 0.28%   |
| Arturia                  | 1        | 0.28%   |
| Alesis                   | 1        | 0.28%   |
| Unknown                  | 1        | 0.28%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 43       | 9.56%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 26       | 5.78%   |
| AMD Family 17h/19h HD Audio Controller                                     | 25       | 5.56%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 18       | 4%      |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 16       | 3.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 13       | 2.89%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 13       | 2.89%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 12       | 2.67%   |
| Nvidia GP104 High Definition Audio Controller                              | 10       | 2.22%   |
| AMD Navi 10 HDMI Audio                                                     | 10       | 2.22%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 9        | 2%      |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 9        | 2%      |
| Intel 200 Series PCH HD Audio                                              | 8        | 1.78%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 8        | 1.78%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7        | 1.56%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 7        | 1.56%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 6        | 1.33%   |
| Nvidia GA102 High Definition Audio Controller                              | 6        | 1.33%   |
| Intel Cannon Lake PCH cAVS                                                 | 6        | 1.33%   |
| C-Media Electronics USB Audio Device                                       | 6        | 1.33%   |
| Nvidia TU116 High Definition Audio Controller                              | 5        | 1.11%   |
| Nvidia TU104 HD Audio Controller                                           | 5        | 1.11%   |
| Nvidia GM204 High Definition Audio Controller                              | 5        | 1.11%   |
| Nvidia GA104 High Definition Audio Controller                              | 5        | 1.11%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 5        | 1.11%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 5        | 1.11%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 5        | 1.11%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 5        | 1.11%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4        | 0.89%   |
| Nvidia GP106 High Definition Audio Controller                              | 4        | 0.89%   |
| Intel Alder Lake-S HD Audio Controller                                     | 4        | 0.89%   |
| Blue Microphones Yeti Stereo Microphone                                    | 4        | 0.89%   |
| Texas Instruments PCM2902 Audio Codec                                      | 3        | 0.67%   |
| Sony DualShock 4 [CUH-ZCT2x]                                               | 3        | 0.67%   |
| Nvidia High Definition Audio Controller                                    | 3        | 0.67%   |
| Nvidia GP102 HDMI Audio Controller                                         | 3        | 0.67%   |
| Nvidia GM206 High Definition Audio Controller                              | 3        | 0.67%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3        | 0.67%   |
| Nvidia GK106 HDMI Audio Controller                                         | 3        | 0.67%   |
| Kingston Technology HyperX QuadCast                                        | 3        | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| G.Skill                      | 28       | 24.35%  |
| Corsair                      | 18       | 15.65%  |
| Kingston                     | 13       | 11.3%   |
| Crucial                      | 9        | 7.83%   |
| SK hynix                     | 8        | 6.96%   |
| Samsung Electronics          | 8        | 6.96%   |
| Unknown                      | 7        | 6.09%   |
| Patriot                      | 6        | 5.22%   |
| A-DATA Technology            | 4        | 3.48%   |
| Team                         | 3        | 2.61%   |
| Patriot Memory (PDP Systems) | 3        | 2.61%   |
| Unknown                      | 3        | 2.61%   |
| Micron Technology            | 2        | 1.74%   |
| Ramaxel Technology           | 1        | 0.87%   |
| Hewlett-Packard              | 1        | 0.87%   |
| Apacer                       | 1        | 0.87%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                    | Desktops | Percent |
|--------------------------------------------------------------------------|----------|---------|
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s                     | 6        | 4.76%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s                    | 4        | 3.17%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s                      | 3        | 2.38%   |
| Unknown                                                                  | 3        | 2.38%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s                     | 2        | 1.59%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s                     | 2        | 1.59%   |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s                      | 2        | 1.59%   |
| Patriot RAM 2666 C16 Series 8GB DIMM DDR4 2800MT/s                       | 2        | 1.59%   |
| Patriot Memory (PDP Systems) RAM 3600 C18 Series 16GB DIMM DDR4 3600MT/s | 2        | 1.59%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s                    | 2        | 1.59%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s                       | 2        | 1.59%   |
| Corsair RAM CMK32GX4M4B3200C16 8GB DIMM DDR4 3600MT/s                    | 2        | 1.59%   |
| Corsair RAM CMK16GX4M2D3600C18 8GB DIMM DDR4 3600MT/s                    | 2        | 1.59%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s                    | 2        | 1.59%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                                | 1        | 0.79%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                                     | 1        | 0.79%   |
| Unknown RAM Module 8GB DIMM                                              | 1        | 0.79%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                                     | 1        | 0.79%   |
| Unknown RAM Module 4GB DIMM                                              | 1        | 0.79%   |
| Unknown RAM Module 2GB DIMM DDR2 1067MT/s                                | 1        | 0.79%   |
| Unknown RAM Module 1GB DIMM 1066MT/s                                     | 1        | 0.79%   |
| Unknown RAM 4400 C19 Series 8GB DIMM DDR4 2133MT/s                       | 1        | 0.79%   |
| Unknown RAM 3000 C16 Series 8192MB DIMM DDR4 2133MT/s                    | 1        | 0.79%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s                       | 1        | 0.79%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3733MT/s                      | 1        | 0.79%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s                       | 1        | 0.79%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1648MT/s                     | 1        | 0.79%   |
| SK hynix RAM HMT41GU6BFR8C-PB 8GB DIMM DDR3 1600MT/s                     | 1        | 0.79%   |
| SK hynix RAM HMT325U7CFR8C-PB 2GB DIMM DDR3 1600MT/s                     | 1        | 0.79%   |
| SK hynix RAM HMAA2GU6CJR8N-XN 16GB DIMM DDR4 3200MT/s                    | 1        | 0.79%   |
| SK hynix RAM HMA81GU6CJR8N-VK 8GB DIMM DDR4 2667MT/s                     | 1        | 0.79%   |
| Samsung RAM Module 8GB DIMM DDR4 2666MT/s                                | 1        | 0.79%   |
| Samsung RAM Module 16GB DIMM DDR4 3200MT/s                               | 1        | 0.79%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s                    | 1        | 0.79%   |
| Samsung RAM M379B5273DH0-YK0 4GB DIMM DDR3 1600MT/s                      | 1        | 0.79%   |
| Samsung RAM M379B5273DH0-YK 4GB DIMM DDR3 1600MT/s                       | 1        | 0.79%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s                      | 1        | 0.79%   |
| Samsung RAM M378B1G73QH0-CK0 8GB DIMM DDR3 1600MT/s                      | 1        | 0.79%   |
| Samsung RAM M378B1G73EB0-CK0 8GB DIMM DDR3 1600MT/s                      | 1        | 0.79%   |
| Ramaxel RAM RMR5030MM58E8F1600 2GB DIMM DDR3 1600MT/s                    | 1        | 0.79%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 73       | 70.19%  |
| DDR3    | 19       | 18.27%  |
| DDR5    | 7        | 6.73%   |
| Unknown | 4        | 3.85%   |
| DDR2    | 1        | 0.96%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 99       | 95.19%  |
| SODIMM | 5        | 4.81%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 56       | 48.28%  |
| 16384 | 29       | 25%     |
| 4096  | 17       | 14.66%  |
| 32768 | 10       | 8.62%   |
| 2048  | 3        | 2.59%   |
| 1024  | 1        | 0.86%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3600    | 19       | 16.38%  |
| 3200    | 17       | 14.66%  |
| 1600    | 10       | 8.62%   |
| 2400    | 7        | 6.03%   |
| 3666    | 5        | 4.31%   |
| 4800    | 4        | 3.45%   |
| 3533    | 4        | 3.45%   |
| 2667    | 4        | 3.45%   |
| 1800    | 4        | 3.45%   |
| 1333    | 4        | 3.45%   |
| 3000    | 3        | 2.59%   |
| 2800    | 3        | 2.59%   |
| 2666    | 3        | 2.59%   |
| 3866    | 2        | 1.72%   |
| 3800    | 2        | 1.72%   |
| 3733    | 2        | 1.72%   |
| 3466    | 2        | 1.72%   |
| 2933    | 2        | 1.72%   |
| 6400    | 1        | 0.86%   |
| 5600    | 1        | 0.86%   |
| 5200    | 1        | 0.86%   |
| 4266    | 1        | 0.86%   |
| 4200    | 1        | 0.86%   |
| 4000    | 1        | 0.86%   |
| 3534    | 1        | 0.86%   |
| 3400    | 1        | 0.86%   |
| 3151    | 1        | 0.86%   |
| 2200    | 1        | 0.86%   |
| 2133    | 1        | 0.86%   |
| 1867    | 1        | 0.86%   |
| 1866    | 1        | 0.86%   |
| 1648    | 1        | 0.86%   |
| 1200    | 1        | 0.86%   |
| 1067    | 1        | 0.86%   |
| 1066    | 1        | 0.86%   |
| 800     | 1        | 0.86%   |
| Unknown | 1        | 0.86%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 2        | 25%     |
| Dymo-CoStar         | 2        | 25%     |
| Brother Industries  | 2        | 25%     |
| Samsung Electronics | 1        | 12.5%   |
| Fuji Xerox          | 1        | 12.5%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Dymo-CoStar LabelWriter 450      | 2        | 25%     |
| Samsung M267x 287x Series        | 1        | 12.5%   |
| HP OfficeJet Pro 8020 series     | 1        | 12.5%   |
| HP DeskJet Plus 4100 series      | 1        | 12.5%   |
| Fuji Xerox DocuPrint CM315/318 z | 1        | 12.5%   |
| Brother MFC Composite Device     | 1        | 12.5%   |
| Brother HL-5370DW series         | 1        | 12.5%   |

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


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 20       | 46.51%  |
| Microsoft                     | 5        | 11.63%  |
| Sunplus Innovation Technology | 4        | 9.3%    |
| Jieli Technology              | 3        | 6.98%   |
| Realtek Semiconductor         | 2        | 4.65%   |
| Generalplus Technology        | 2        | 4.65%   |
| Z-Star Microelectronics       | 1        | 2.33%   |
| Trust                         | 1        | 2.33%   |
| Razer USA                     | 1        | 2.33%   |
| Microdia                      | 1        | 2.33%   |
| MacroSilicon                  | 1        | 2.33%   |
| Creative Technology           | 1        | 2.33%   |
| Unknown                       | 1        | 2.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Logitech Webcam C930e                      | 3        | 6.98%   |
| Logitech Webcam C270                       | 3        | 6.98%   |
| Logitech BRIO Ultra HD Webcam              | 3        | 6.98%   |
| Jieli USB PHY 2.0                          | 3        | 6.98%   |
| Sunplus FHD Camera                         | 2        | 4.65%   |
| Realtek FULL HD 1080P Webcam               | 2        | 4.65%   |
| Microsoft LifeCam HD-5000                  | 2        | 4.65%   |
| Logitech HD Webcam C910                    | 2        | 4.65%   |
| Logitech HD Pro Webcam C920                | 2        | 4.65%   |
| Logitech C922 Pro Stream Webcam            | 2        | 4.65%   |
| Z-Star Vega USB 2.0 Camera.                | 1        | 2.33%   |
| Trust USB Camera                           | 1        | 2.33%   |
| Sunplus USB 2.0 Camera                     | 1        | 2.33%   |
| Sunplus Aukey-PC-LM1E Camera               | 1        | 2.33%   |
| Razer USA Razer Kiyo Pro                   | 1        | 2.33%   |
| Microsoft Xbox NUI Camera                  | 1        | 2.33%   |
| Microsoft LifeCam VX-2000                  | 1        | 2.33%   |
| Microsoft LifeCam HD-3000                  | 1        | 2.33%   |
| Microdia Integrated Camera                 | 1        | 2.33%   |
| MacroSilicon USB Video                     | 1        | 2.33%   |
| Logitech Webcam C925e                      | 1        | 2.33%   |
| Logitech Webcam C310                       | 1        | 2.33%   |
| Logitech HD Webcam C510                    | 1        | 2.33%   |
| Logitech C920 PRO HD Webcam                | 1        | 2.33%   |
| Logitech Brio 500                          | 1        | 2.33%   |
| Generalplus WEB CAM                        | 1        | 2.33%   |
| Generalplus GENERAL WEBCAM                 | 1        | 2.33%   |
| Creative Live! Cam Chat HD [VF0700/VF0790] | 1        | 2.33%   |
| Unknown                                    | 1        | 2.33%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

Chipcard Vendor
---------------

Chipcard module vendors

Zero info for selected period =(

Chipcard Model
--------------

Chipcard module models

Zero info for selected period =(

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 96       | 51.61%  |
| 1     | 80       | 43.01%  |
| 2     | 9        | 4.84%   |
| 3     | 1        | 0.54%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 77       | 74.76%  |
| Net/wireless             | 11       | 10.68%  |
| Graphics card            | 9        | 8.74%   |
| Net/ethernet             | 3        | 2.91%   |
| Unassigned class         | 2        | 1.94%   |
| Multimedia controller    | 1        | 0.97%   |

