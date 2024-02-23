AlmaLinux - Tested Hardware & Statistics (Desktops)
---------------------------------------------------

A project to collect tested hardware configurations for AlmaLinux.

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

Total: 113

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | 89D8 SMVB                   | [61f8c8c9e0](https://linux-hardware.org/?probe=61f8c8c9e0) | Jan 22, 2024 |
| HP            | 89D8 SMVB                   | [3c8308af97](https://linux-hardware.org/?probe=3c8308af97) | Jan 22, 2024 |
| Optimized ... | KVM                         | [4fe928d059](https://linux-hardware.org/?probe=4fe928d059) | Jan 11, 2024 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [aa11af3235](https://linux-hardware.org/?probe=aa11af3235) | Dec 20, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [230f41f6b5](https://linux-hardware.org/?probe=230f41f6b5) | Dec 12, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [93675534e1](https://linux-hardware.org/?probe=93675534e1) | Dec 05, 2023 |
| HP            | 0B4Ch D                     | [85c03e03e8](https://linux-hardware.org/?probe=85c03e03e8) | Dec 04, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | [746c6adb3f](https://linux-hardware.org/?probe=746c6adb3f) | Dec 04, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | [7eaae92099](https://linux-hardware.org/?probe=7eaae92099) | Dec 04, 2023 |
| MSI           | MPG Z590 GAMING PLUS        | [d231a15a8f](https://linux-hardware.org/?probe=d231a15a8f) | Nov 22, 2023 |
| Intel         | X99                         | [c07799299c](https://linux-hardware.org/?probe=c07799299c) | Nov 19, 2023 |
| MSI           | MPG Z590 GAMING PLUS        | [e3760a331a](https://linux-hardware.org/?probe=e3760a331a) | Oct 31, 2023 |
| MSI           | MAG B550M BAZOOKA           | [492563a83c](https://linux-hardware.org/?probe=492563a83c) | Oct 24, 2023 |
| MSI           | MAG B550M BAZOOKA           | [3e4b32b047](https://linux-hardware.org/?probe=3e4b32b047) | Oct 24, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [de8a8232ba](https://linux-hardware.org/?probe=de8a8232ba) | Oct 19, 2023 |
| Gigabyte      | X399 DESIGNARE EX-CF        | [d9bbe8269c](https://linux-hardware.org/?probe=d9bbe8269c) | Oct 10, 2023 |
| Intel         | DH77EB AAG39073-304         | [27ce5f6a61](https://linux-hardware.org/?probe=27ce5f6a61) | Oct 06, 2023 |
| HP            | 81C5 MVB                    | [ccdf9d0cfa](https://linux-hardware.org/?probe=ccdf9d0cfa) | Oct 02, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [7ab6fc6901](https://linux-hardware.org/?probe=7ab6fc6901) | Sep 27, 2023 |
| HP            | 158B                        | [f8385c7d22](https://linux-hardware.org/?probe=f8385c7d22) | Sep 18, 2023 |
| HP            | 158B                        | [986f0c6ba1](https://linux-hardware.org/?probe=986f0c6ba1) | Sep 15, 2023 |
| ASUSTek       | Rampage V EDITION 10        | [727e431acb](https://linux-hardware.org/?probe=727e431acb) | Sep 03, 2023 |
| ASRockRack    | X470D4U2-2T                 | [058672ddad](https://linux-hardware.org/?probe=058672ddad) | Jul 18, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [2330d7d072](https://linux-hardware.org/?probe=2330d7d072) | Jul 15, 2023 |
| ASRockRack    | X470D4U2-2T                 | [59f9ee3ee8](https://linux-hardware.org/?probe=59f9ee3ee8) | Jul 09, 2023 |
| ASRockRack    | X470D4U2-2T                 | [a686a6eed6](https://linux-hardware.org/?probe=a686a6eed6) | Jul 08, 2023 |
| Gigabyte      | X570S UD                    | [cd368fbd36](https://linux-hardware.org/?probe=cd368fbd36) | Jul 07, 2023 |
| ASRockRack    | X470D4U2-2T                 | [da271abdd3](https://linux-hardware.org/?probe=da271abdd3) | Jul 03, 2023 |
| ASRockRack    | X470D4U2-2T                 | [92bf7e658e](https://linux-hardware.org/?probe=92bf7e658e) | Jul 02, 2023 |
| ASRockRack    | X470D4U2-2T                 | [57424619e8](https://linux-hardware.org/?probe=57424619e8) | Jul 01, 2023 |
| ASRockRack    | X470D4U2-2T                 | [70ed50862c](https://linux-hardware.org/?probe=70ed50862c) | Jun 30, 2023 |
| ASRockRack    | X470D4U2-2T                 | [f36489e090](https://linux-hardware.org/?probe=f36489e090) | Jun 26, 2023 |
| ASRockRack    | X470D4U2-2T                 | [cf3b44c0b6](https://linux-hardware.org/?probe=cf3b44c0b6) | Jun 25, 2023 |
| ASRockRack    | X470D4U2-2T                 | [8738063b30](https://linux-hardware.org/?probe=8738063b30) | Jun 11, 2023 |
| ASRockRack    | X470D4U2-2T                 | [8e10de95af](https://linux-hardware.org/?probe=8e10de95af) | Jun 10, 2023 |
| ASRockRack    | X470D4U2-2T                 | [9c282e76a6](https://linux-hardware.org/?probe=9c282e76a6) | Jun 06, 2023 |
| ASRockRack    | X470D4U2-2T                 | [4592ff63f3](https://linux-hardware.org/?probe=4592ff63f3) | Jun 05, 2023 |
| ASRockRack    | X470D4U2-2T                 | [9a28272d6e](https://linux-hardware.org/?probe=9a28272d6e) | Jun 01, 2023 |
| ASRockRack    | X470D4U2-2T                 | [cffbd92b9f](https://linux-hardware.org/?probe=cffbd92b9f) | May 31, 2023 |
| ASRockRack    | X470D4U2-2T                 | [399cce0d30](https://linux-hardware.org/?probe=399cce0d30) | May 30, 2023 |
| ASRockRack    | X470D4U2-2T                 | [531455206b](https://linux-hardware.org/?probe=531455206b) | May 29, 2023 |
| ASRockRack    | X470D4U2-2T                 | [12a444a75a](https://linux-hardware.org/?probe=12a444a75a) | May 23, 2023 |
| ASRockRack    | X470D4U2-2T                 | [0f9deafb62](https://linux-hardware.org/?probe=0f9deafb62) | May 22, 2023 |
| Dell          | 0FDY5C A00                  | [3d9b02954b](https://linux-hardware.org/?probe=3d9b02954b) | May 16, 2023 |
| ASRockRack    | X470D4U2-2T                 | [465488c540](https://linux-hardware.org/?probe=465488c540) | May 15, 2023 |
| ASRockRack    | X470D4U2-2T                 | [413d3b7b92](https://linux-hardware.org/?probe=413d3b7b92) | May 14, 2023 |
| ASRockRack    | X470D4U2-2T                 | [2a69d13961](https://linux-hardware.org/?probe=2a69d13961) | May 13, 2023 |
| ASRockRack    | X470D4U2-2T                 | [208afe074a](https://linux-hardware.org/?probe=208afe074a) | May 12, 2023 |
| ASRockRack    | X470D4U2-2T                 | [64bd100bb5](https://linux-hardware.org/?probe=64bd100bb5) | May 09, 2023 |
| ASRockRack    | X470D4U2-2T                 | [28a1f44a1e](https://linux-hardware.org/?probe=28a1f44a1e) | May 08, 2023 |
| ASRockRack    | X470D4U2-2T                 | [2849b9a200](https://linux-hardware.org/?probe=2849b9a200) | May 02, 2023 |
| ASRockRack    | X470D4U2-2T                 | [34e7df2c84](https://linux-hardware.org/?probe=34e7df2c84) | May 01, 2023 |
| ASRockRack    | X470D4U2-2T                 | [f46e9f6ba7](https://linux-hardware.org/?probe=f46e9f6ba7) | Apr 30, 2023 |
| ASRockRack    | X470D4U2-2T                 | [9fdfb825c7](https://linux-hardware.org/?probe=9fdfb825c7) | Apr 27, 2023 |
| ASRockRack    | X470D4U2-2T                 | [b24f39801d](https://linux-hardware.org/?probe=b24f39801d) | Apr 26, 2023 |
| Dell          | 0FDY5C A00                  | [ddf678b11a](https://linux-hardware.org/?probe=ddf678b11a) | Apr 20, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [6e9640e9c2](https://linux-hardware.org/?probe=6e9640e9c2) | Apr 15, 2023 |
| ASRockRack    | X470D4U2-2T                 | [9dd9a74143](https://linux-hardware.org/?probe=9dd9a74143) | Apr 12, 2023 |
| MSI           | B85-G43                     | [49c7de9ea6](https://linux-hardware.org/?probe=49c7de9ea6) | Apr 08, 2023 |
| ASRockRack    | X470D4U2-2T                 | [d699519c30](https://linux-hardware.org/?probe=d699519c30) | Apr 06, 2023 |
| ASRockRack    | X470D4U2-2T                 | [fbd686e3e2](https://linux-hardware.org/?probe=fbd686e3e2) | Apr 02, 2023 |
| ASRockRack    | X470D4U2-2T                 | [acb0f81194](https://linux-hardware.org/?probe=acb0f81194) | Apr 01, 2023 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | [3c3474d69b](https://linux-hardware.org/?probe=3c3474d69b) | Mar 28, 2023 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | [21f6af6f50](https://linux-hardware.org/?probe=21f6af6f50) | Mar 28, 2023 |
| ASRockRack    | X470D4U2-2T                 | [d96c0cfcd9](https://linux-hardware.org/?probe=d96c0cfcd9) | Mar 27, 2023 |
| ASRockRack    | X470D4U2-2T                 | [da489de02c](https://linux-hardware.org/?probe=da489de02c) | Mar 26, 2023 |
| ASRockRack    | X470D4U2-2T                 | [d21d79ee06](https://linux-hardware.org/?probe=d21d79ee06) | Mar 19, 2023 |
| ASRockRack    | X470D4U2-2T                 | [17e455c4df](https://linux-hardware.org/?probe=17e455c4df) | Mar 18, 2023 |
| ASRockRack    | X470D4U2-2T                 | [7d42741fac](https://linux-hardware.org/?probe=7d42741fac) | Mar 12, 2023 |
| ASRockRack    | X470D4U2-2T                 | [c5419b8b27](https://linux-hardware.org/?probe=c5419b8b27) | Mar 11, 2023 |
| ASRockRack    | X470D4U2-2T                 | [70b5b39ce8](https://linux-hardware.org/?probe=70b5b39ce8) | Mar 07, 2023 |
| ASRockRack    | X470D4U2-2T                 | [77ca3b430b](https://linux-hardware.org/?probe=77ca3b430b) | Mar 06, 2023 |
| ASRockRack    | X470D4U2-2T                 | [a750fc7c24](https://linux-hardware.org/?probe=a750fc7c24) | Mar 04, 2023 |
| ASRockRack    | X470D4U2-2T                 | [0a8ce98d46](https://linux-hardware.org/?probe=0a8ce98d46) | Mar 03, 2023 |
| ASRockRack    | X470D4U2-2T                 | [92300b45fe](https://linux-hardware.org/?probe=92300b45fe) | Mar 01, 2023 |
| ASRockRack    | X470D4U2-2T                 | [6ccb40f64d](https://linux-hardware.org/?probe=6ccb40f64d) | Feb 28, 2023 |
| ASRockRack    | X470D4U2-2T                 | [fb42cba088](https://linux-hardware.org/?probe=fb42cba088) | Feb 25, 2023 |
| ASRockRack    | X470D4U2-2T                 | [59ec61666a](https://linux-hardware.org/?probe=59ec61666a) | Feb 24, 2023 |
| ASRockRack    | X470D4U2-2T                 | [2a2dfe19fc](https://linux-hardware.org/?probe=2a2dfe19fc) | Feb 18, 2023 |
| ASRockRack    | X470D4U2-2T                 | [c913edda07](https://linux-hardware.org/?probe=c913edda07) | Feb 17, 2023 |
| ASRockRack    | X470D4U2-2T                 | [3e048e046a](https://linux-hardware.org/?probe=3e048e046a) | Feb 12, 2023 |
| ASRockRack    | X470D4U2-2T                 | [9a81107301](https://linux-hardware.org/?probe=9a81107301) | Feb 11, 2023 |
| HP            | 8455                        | [ffc8587d29](https://linux-hardware.org/?probe=ffc8587d29) | Feb 08, 2023 |
| ASRockRack    | X470D4U2-2T                 | [0593b2bac6](https://linux-hardware.org/?probe=0593b2bac6) | Feb 08, 2023 |
| ASRockRack    | X470D4U2-2T                 | [a019143fe9](https://linux-hardware.org/?probe=a019143fe9) | Feb 07, 2023 |
| ASRockRack    | X470D4U2-2T                 | [768696d7b8](https://linux-hardware.org/?probe=768696d7b8) | Feb 04, 2023 |
| ASRockRack    | X470D4U2-2T                 | [6bb0e68672](https://linux-hardware.org/?probe=6bb0e68672) | Feb 03, 2023 |
| ASRockRack    | X470D4U2-2T                 | [f6ad918c7e](https://linux-hardware.org/?probe=f6ad918c7e) | Feb 02, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | [21ce876854](https://linux-hardware.org/?probe=21ce876854) | Feb 01, 2023 |
| ASRockRack    | X470D4U2-2T                 | [602482d070](https://linux-hardware.org/?probe=602482d070) | Feb 01, 2023 |
| ASRockRack    | X470D4U2-2T                 | [af3cf25119](https://linux-hardware.org/?probe=af3cf25119) | Jan 31, 2023 |
| ASRockRack    | X470D4U2-2T                 | [ec76a40223](https://linux-hardware.org/?probe=ec76a40223) | Jan 30, 2023 |
| ASRock        | B450M Pro4 R2.0             | [e4289105c5](https://linux-hardware.org/?probe=e4289105c5) | Jan 30, 2023 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | [ee36c9d395](https://linux-hardware.org/?probe=ee36c9d395) | Jan 30, 2023 |
| ASRockRack    | X470D4U2-2T                 | [6b99585bc0](https://linux-hardware.org/?probe=6b99585bc0) | Jan 29, 2023 |
| ASRockRack    | X470D4U2-2T                 | [b9f3d19faa](https://linux-hardware.org/?probe=b9f3d19faa) | Jan 26, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [df1811bf5d](https://linux-hardware.org/?probe=df1811bf5d) | Jan 26, 2023 |
| ASRockRack    | X470D4U2-2T                 | [71a9255bc8](https://linux-hardware.org/?probe=71a9255bc8) | Jan 24, 2023 |
| ASRockRack    | X470D4U2-2T                 | [e327d1dea4](https://linux-hardware.org/?probe=e327d1dea4) | Jan 24, 2023 |
| ASRockRack    | X470D4U2-2T                 | [f62d0d9183](https://linux-hardware.org/?probe=f62d0d9183) | Jan 24, 2023 |
| ASRock        | B450M Pro4 R2.0             | [ed6204876e](https://linux-hardware.org/?probe=ed6204876e) | Jan 22, 2023 |
| HP            | 158A                        | [c0e1c9b6e6](https://linux-hardware.org/?probe=c0e1c9b6e6) | Jan 09, 2023 |
| MSI           | A88X-G45 GAMING             | [891e0757ed](https://linux-hardware.org/?probe=891e0757ed) | Dec 31, 2022 |
| MSI           | A88X-G45 GAMING             | [bdb45edaad](https://linux-hardware.org/?probe=bdb45edaad) | Dec 31, 2022 |
| Optimized ... | KVM                         | [d62625a751](https://linux-hardware.org/?probe=d62625a751) | Dec 13, 2022 |
| Gigabyte      | H81M-D2V                    | [6035f1ee45](https://linux-hardware.org/?probe=6035f1ee45) | Nov 11, 2022 |
| ASUSTek       | Q170M2                      | [c62954095d](https://linux-hardware.org/?probe=c62954095d) | Nov 11, 2022 |
| Lenovo        | 1052 NOK                    | [28cd1416fe](https://linux-hardware.org/?probe=28cd1416fe) | Sep 22, 2022 |
| ASRock        | B460 Phantom Gaming 4       | [0dc125da55](https://linux-hardware.org/?probe=0dc125da55) | Jul 05, 2022 |
| Gigabyte      | Z590 AORUS PRO AX           | [a517886d4d](https://linux-hardware.org/?probe=a517886d4d) | Feb 10, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [e5a30a171e](https://linux-hardware.org/?probe=e5a30a171e) | Jun 08, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [043878564d](https://linux-hardware.org/?probe=043878564d) | Jun 08, 2021 |
| HP            | 0AE8h C                     | [b7fd559b13](https://linux-hardware.org/?probe=b7fd559b13) | Mar 24, 2021 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| AlmaLinux 9.1 | 9        | 23.68%  |
| AlmaLinux 9.2 | 6        | 15.79%  |
| AlmaLinux 8.8 | 5        | 13.16%  |
| AlmaLinux 8.7 | 5        | 13.16%  |
| AlmaLinux 9.3 | 3        | 7.89%   |
| AlmaLinux 9.0 | 3        | 7.89%   |
| AlmaLinux 8.9 | 3        | 7.89%   |
| AlmaLinux 8.6 | 1        | 2.63%   |
| AlmaLinux 8.5 | 1        | 2.63%   |
| AlmaLinux 8.4 | 1        | 2.63%   |
| AlmaLinux 8.3 | 1        | 2.63%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| AlmaLinux | 33       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Desktops | Percent |
|------------------------------|----------|---------|
| 4.18.0-425.3.1.el8.x86_64    | 4        | 10.26%  |
| 5.14.0-284.30.1.el9_2.x86_64 | 3        | 7.69%   |
| 5.14.0-162.6.1.el9_1.x86_64  | 3        | 7.69%   |
| 5.14.0-162.12.1.el9_1.x86_64 | 3        | 7.69%   |
| 5.14.0-70.30.1.el9_0.x86_64  | 2        | 5.13%   |
| 5.14.0-362.8.1.el9_3.x86_64  | 2        | 5.13%   |
| 5.14.0-284.18.1.el9_2.x86_64 | 2        | 5.13%   |
| 4.18.0-477.27.2.el8_8.x86_64 | 2        | 5.13%   |
| 4.18.0-477.21.1.el8_8.x86_64 | 2        | 5.13%   |
| 6.1.24-1kx.el9.x86_64        | 1        | 2.56%   |
| 5.14.0-70.22.1.el9_0.x86_64  | 1        | 2.56%   |
| 5.14.0-362.13.1.el9_3.x86_64 | 1        | 2.56%   |
| 5.14.0-284.11.1.el9_2.x86_64 | 1        | 2.56%   |
| 5.14.0-162.22.2.el9_1.x86_64 | 1        | 2.56%   |
| 5.14.0-162.18.1.el9_1.x86_64 | 1        | 2.56%   |
| 4.18.0-513.9.1.el8_9.x86_64  | 1        | 2.56%   |
| 4.18.0-513.5.1.el8_9.x86_64  | 1        | 2.56%   |
| 4.18.0-477.13.1.el8_8.x86_64 | 1        | 2.56%   |
| 4.18.0-477.10.1.el8_8.x86_64 | 1        | 2.56%   |
| 4.18.0-425.19.2.el8_7.x86_64 | 1        | 2.56%   |
| 4.18.0-425.13.1.el8_7.x86_64 | 1        | 2.56%   |
| 4.18.0-372.9.1.el8.x86_64    | 1        | 2.56%   |
| 4.18.0-348.12.2.el8_5.x86_64 | 1        | 2.56%   |
| 4.18.0-305.el8.x86_64        | 1        | 2.56%   |
| 4.18.0-240.15.1.el8_3.x86_64 | 1        | 2.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.14.0  | 20       | 58.82%  |
| 4.18.0  | 13       | 38.24%  |
| 6.1.24  | 1        | 2.94%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.14    | 20       | 58.82%  |
| 4.18    | 13       | 38.24%  |
| 6.1     | 1        | 2.94%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 33       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 22       | 64.71%  |
| Unknown    | 7        | 20.59%  |
| KDE5       | 3        | 8.82%   |
| XFCE       | 1        | 2.94%   |
| X-Cinnamon | 1        | 2.94%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 18       | 51.43%  |
| Wayland | 13       | 37.14%  |
| Tty     | 2        | 5.71%   |
| Unknown | 2        | 5.71%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 21       | 61.76%  |
| GDM     | 12       | 35.29%  |
| SDDM    | 1        | 2.94%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 16       | 47.06%  |
| en_GB   | 3        | 8.82%   |
| ru_RU   | 2        | 5.88%   |
| en_CA   | 2        | 5.88%   |
| de_DE   | 2        | 5.88%   |
| Unknown | 2        | 5.88%   |
| uk_UA   | 1        | 2.94%   |
| ru_UA   | 1        | 2.94%   |
| pl_PL   | 1        | 2.94%   |
| hu_HU   | 1        | 2.94%   |
| fr_FR   | 1        | 2.94%   |
| en_AU   | 1        | 2.94%   |
| da_DK   | 1        | 2.94%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 22       | 66.67%  |
| BIOS | 11       | 33.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Xfs  | 26       | 78.79%  |
| Ext4 | 7        | 21.21%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 16       | 48.48%  |
| Unknown | 13       | 39.39%  |
| MBR     | 4        | 12.12%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 27       | 81.82%  |
| Yes       | 6        | 18.18%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 25       | 75.76%  |
| Yes       | 8        | 24.24%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 7        | 21.21%  |
| ASUSTek Computer    | 6        | 18.18%  |
| MSI                 | 5        | 15.15%  |
| Gigabyte Technology | 5        | 15.15%  |
| Lenovo              | 2        | 6.06%   |
| Intel               | 2        | 6.06%   |
| ASRock              | 2        | 6.06%   |
| Supermicro          | 1        | 3.03%   |
| Optimized Hosting   | 1        | 3.03%   |
| Dell                | 1        | 3.03%   |
| ASRockRack          | 1        | 3.03%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Desktops | Percent |
|-------------------------------------------|----------|---------|
| Supermicro PIO-617R-TLN4F+-ST031          | 1        | 3.03%   |
| Optimized Hosting KVM                     | 1        | 3.03%   |
| MSI MS-7D91                               | 1        | 3.03%   |
| MSI MS-7D07                               | 1        | 3.03%   |
| MSI MS-7C95                               | 1        | 3.03%   |
| MSI MS-7900                               | 1        | 3.03%   |
| MSI MS-7816                               | 1        | 3.03%   |
| Lenovo ThinkStation P350 30E6S20S00       | 1        | 3.03%   |
| Lenovo H520S 10093                        | 1        | 3.03%   |
| Intel X99                                 | 1        | 3.03%   |
| Intel TTL TEKNOPRO                        | 1        | 3.03%   |
| HP Z820 Workstation                       | 1        | 3.03%   |
| HP Z620 Workstation                       | 1        | 3.03%   |
| HP Z600 Workstation                       | 1        | 3.03%   |
| HP Z400 Workstation                       | 1        | 3.03%   |
| HP Z4 G4 Workstation                      | 1        | 3.03%   |
| HP Z2 Tower G4 Workstation                | 1        | 3.03%   |
| HP Victus by 15L Gaming Desktop TG02-0xxx | 1        | 3.03%   |
| Gigabyte Z690 GAMING X DDR4               | 1        | 3.03%   |
| Gigabyte Z590 AORUS PRO AX                | 1        | 3.03%   |
| Gigabyte X570S UD                         | 1        | 3.03%   |
| Gigabyte X399 DESIGNARE EX                | 1        | 3.03%   |
| Gigabyte H81M-D2V                         | 1        | 3.03%   |
| Dell OptiPlex 5050                        | 1        | 3.03%   |
| ASUS TUF Gaming B450-PLUS II              | 1        | 3.03%   |
| ASUS Q170M2                               | 1        | 3.03%   |
| ASUS Pro WS WRX80E-SAGE SE WIFI           | 1        | 3.03%   |
| ASUS PRIME B550-PLUS                      | 1        | 3.03%   |
| ASUS M5A78L-M/USB3                        | 1        | 3.03%   |
| ASUS CROSSHAIR VI HERO                    | 1        | 3.03%   |
| ASRockRack X470D4U2-2T                    | 1        | 3.03%   |
| ASRock B460 Phantom Gaming 4              | 1        | 3.03%   |
| ASRock B450M Pro4 R2.0                    | 1        | 3.03%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| Supermicro PIO-617R-TLN4F+-ST031 | 1        | 3.03%   |
| Optimized Hosting KVM            | 1        | 3.03%   |
| MSI MS-7D91                      | 1        | 3.03%   |
| MSI MS-7D07                      | 1        | 3.03%   |
| MSI MS-7C95                      | 1        | 3.03%   |
| MSI MS-7900                      | 1        | 3.03%   |
| MSI MS-7816                      | 1        | 3.03%   |
| Lenovo ThinkStation              | 1        | 3.03%   |
| Lenovo H520S                     | 1        | 3.03%   |
| Intel X99                        | 1        | 3.03%   |
| Intel TTL                        | 1        | 3.03%   |
| HP Z820                          | 1        | 3.03%   |
| HP Z620                          | 1        | 3.03%   |
| HP Z600                          | 1        | 3.03%   |
| HP Z400                          | 1        | 3.03%   |
| HP Z4                            | 1        | 3.03%   |
| HP Z2                            | 1        | 3.03%   |
| HP Victus                        | 1        | 3.03%   |
| Gigabyte Z690                    | 1        | 3.03%   |
| Gigabyte Z590                    | 1        | 3.03%   |
| Gigabyte X570S                   | 1        | 3.03%   |
| Gigabyte X399                    | 1        | 3.03%   |
| Gigabyte H81M-D2V                | 1        | 3.03%   |
| Dell OptiPlex                    | 1        | 3.03%   |
| ASUS TUF                         | 1        | 3.03%   |
| ASUS Q170M2                      | 1        | 3.03%   |
| ASUS Pro                         | 1        | 3.03%   |
| ASUS PRIME                       | 1        | 3.03%   |
| ASUS M5A78L-M                    | 1        | 3.03%   |
| ASUS CROSSHAIR                   | 1        | 3.03%   |
| ASRockRack X470D4U2-2T           | 1        | 3.03%   |
| ASRock B460                      | 1        | 3.03%   |
| ASRock B450M                     | 1        | 3.03%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 7        | 21.21%  |
| 2012 | 5        | 15.15%  |
| 2022 | 3        | 9.09%   |
| 2021 | 3        | 9.09%   |
| 2018 | 3        | 9.09%   |
| 2013 | 3        | 9.09%   |
| 2019 | 2        | 6.06%   |
| 2015 | 2        | 6.06%   |
| 2017 | 1        | 3.03%   |
| 2014 | 1        | 3.03%   |
| 2011 | 1        | 3.03%   |
| 2010 | 1        | 3.03%   |
| 2009 | 1        | 3.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 33       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 30       | 88.24%  |
| Enabled  | 4        | 11.76%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 33       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 64.01-256.0     | 11       | 33.33%  |
| 4.01-8.0        | 6        | 18.18%  |
| 8.01-16.0       | 6        | 18.18%  |
| 24.01-32.0      | 4        | 12.12%  |
| 32.01-64.0      | 3        | 9.09%   |
| 16.01-24.0      | 2        | 6.06%   |
| More than 256.0 | 1        | 3.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 9        | 26.47%  |
| 2.01-3.0   | 8        | 23.53%  |
| 3.01-4.0   | 6        | 17.65%  |
| 1.01-2.0   | 5        | 14.71%  |
| 32.01-64.0 | 2        | 5.88%   |
| 24.01-32.0 | 1        | 2.94%   |
| 16.01-24.0 | 1        | 2.94%   |
| 8.01-16.0  | 1        | 2.94%   |
| 0.51-1.0   | 1        | 2.94%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 3      | 8        | 23.53%  |
| 4      | 7        | 20.59%  |
| 2      | 7        | 20.59%  |
| 1      | 7        | 20.59%  |
| 6      | 2        | 5.88%   |
| 5      | 2        | 5.88%   |
| 10     | 1        | 2.94%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 21       | 63.64%  |
| Yes       | 12       | 36.36%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 32       | 96.97%  |
| No        | 1        | 3.03%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 21       | 63.64%  |
| Yes       | 12       | 36.36%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 23       | 69.7%   |
| Yes       | 10       | 30.3%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| Russia      | 5        | 15.15%  |
| USA         | 4        | 12.12%  |
| Canada      | 4        | 12.12%  |
| France      | 3        | 9.09%   |
| Ukraine     | 2        | 6.06%   |
| Switzerland | 2        | 6.06%   |
| Romania     | 2        | 6.06%   |
| Hungary     | 2        | 6.06%   |
| UK          | 1        | 3.03%   |
| Netherlands | 1        | 3.03%   |
| Kazakhstan  | 1        | 3.03%   |
| Greenland   | 1        | 3.03%   |
| Germany     | 1        | 3.03%   |
| Czechia     | 1        | 3.03%   |
| China       | 1        | 3.03%   |
| Austria     | 1        | 3.03%   |
| Australia   | 1        | 3.03%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Tunari           | 2        | 6.06%   |
| Moscow           | 2        | 6.06%   |
| Zaporizhzhia     | 1        | 3.03%   |
| Vienna           | 1        | 3.03%   |
| Varosfoeld       | 1        | 3.03%   |
| Strasbourg       | 1        | 3.03%   |
| Stadtilm         | 1        | 3.03%   |
| St. Paul         | 1        | 3.03%   |
| Shimanovsk       | 1        | 3.03%   |
| Shanghai         | 1        | 3.03%   |
| Saint-Cloud      | 1        | 3.03%   |
| Saint-Brieuc     | 1        | 3.03%   |
| Rochester        | 1        | 3.03%   |
| Pardubice        | 1        | 3.03%   |
| Nizhniy Novgorod | 1        | 3.03%   |
| Montreal         | 1        | 3.03%   |
| Kyiv             | 1        | 3.03%   |
| Kitimat          | 1        | 3.03%   |
| Ilulissat        | 1        | 3.03%   |
| Groningen        | 1        | 3.03%   |
| Geneva           | 1        | 3.03%   |
| DeLand           | 1        | 3.03%   |
| Cincinnati       | 1        | 3.03%   |
| Budapest         | 1        | 3.03%   |
| Brisbane         | 1        | 3.03%   |
| Bloomington      | 1        | 3.03%   |
| Bellevue         | 1        | 3.03%   |
| Beauharnois      | 1        | 3.03%   |
| Basel            | 1        | 3.03%   |
| Arzamas          | 1        | 3.03%   |
| Almaty           | 1        | 3.03%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 13       | 19     | 20.97%  |
| WDC                         | 12       | 29     | 19.35%  |
| Samsung Electronics         | 10       | 16     | 16.13%  |
| Kingston                    | 5        | 8      | 8.06%   |
| SanDisk                     | 4        | 8      | 6.45%   |
| Toshiba                     | 2        | 3      | 3.23%   |
| SK hynix                    | 2        | 2      | 3.23%   |
| Micron Technology           | 2        | 3      | 3.23%   |
| Crucial                     | 2        | 4      | 3.23%   |
| Team                        | 1        | 1      | 1.61%   |
| Silicon Motion              | 1        | 14     | 1.61%   |
| QEMU                        | 1        | 2      | 1.61%   |
| Netac                       | 1        | 1      | 1.61%   |
| LITEON                      | 1        | 1      | 1.61%   |
| Kingston Technology Company | 1        | 1      | 1.61%   |
| Intel                       | 1        | 1      | 1.61%   |
| HGST                        | 1        | 1      | 1.61%   |
| Hewlett-Packard             | 1        | 1      | 1.61%   |
| AMD                         | 1        | 15     | 1.61%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| WDC WD10EZEX-08WN4A0 1TB                            | 2        | 2.27%   |
| Seagate ST4000DM000-1F2168 4TB                      | 2        | 2.27%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB   | 2        | 2.27%   |
| Kingston SA400S37480G 480GB SSD                     | 2        | 2.27%   |
| WDC WDS100T2B0B-00YS70 1TB SSD                      | 1        | 1.14%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                      | 1        | 1.14%   |
| WDC WD60EFRX-68L0BN1 6TB                            | 1        | 1.14%   |
| WDC WD40EZRX-00SPEB0 4TB                            | 1        | 1.14%   |
| WDC WD40EFZX-68AWUN0 4TB                            | 1        | 1.14%   |
| WDC WD40EFRX-68N32N0 4TB                            | 1        | 1.14%   |
| WDC WD40EFAX-68JH4N1 4TB                            | 1        | 1.14%   |
| WDC WD4000FYYZ-01UL1B2 4TB                          | 1        | 1.14%   |
| WDC WD4000FYYZ-01UL1B1 4TB                          | 1        | 1.14%   |
| WDC WD4000FDYZ-27YA5B0 4TB                          | 1        | 1.14%   |
| WDC WD4000F9YZ-09N20L1 4TB                          | 1        | 1.14%   |
| WDC WD3600FYYZ-01UL1B3 4TB                          | 1        | 1.14%   |
| WDC WD3600FYYZ-01UL1B1 4TB                          | 1        | 1.14%   |
| WDC WD35EFRX-68WT0N0 4TB                            | 1        | 1.14%   |
| WDC WD20EZBX-60AYRA0 2TB                            | 1        | 1.14%   |
| WDC WD20EARS-00J2GB0 2TB                            | 1        | 1.14%   |
| WDC WD10EZEX-75M2NA0 1TB                            | 1        | 1.14%   |
| WDC WD10EZEX-08M2NA0 1TB                            | 1        | 1.14%   |
| WDC WD10EZEX-00KUWA0 1TB                            | 1        | 1.14%   |
| WDC RAT035VWHG-GTK4D7 4TB                           | 1        | 1.14%   |
| WDC RAT035VQHR-GTK4D7 4TB                           | 1        | 1.14%   |
| Toshiba MG06ACA800E 8TB                             | 1        | 1.14%   |
| Toshiba DT01ACA100 1TB                              | 1        | 1.14%   |
| Team T253X1480G 480GB SSD                           | 1        | 1.14%   |
| SK hynix SH920 2.5 7MM 256GB SSD                    | 1        | 1.14%   |
| SK hynix BC711 HFM512GD3JX013N 512GB                | 1        | 1.14%   |
| Silicon Motion SM2262/SM2262EN SSD Controller 480GB | 1        | 1.14%   |
| Seagate ST4000NM000A 00MX141 00MX141LEN 4TB         | 1        | 1.14%   |
| Seagate ST4000NC001-1FS168 4TB                      | 1        | 1.14%   |
| Seagate ST4000DM005-2DP166 4TB                      | 1        | 1.14%   |
| Seagate ST31000528AS 1TB                            | 1        | 1.14%   |
| Seagate ST3000DM001-1CH166 3TB                      | 1        | 1.14%   |
| Seagate ST2000VN000-1H3164 2TB                      | 1        | 1.14%   |
| Seagate ST2000DM001-1ER164 2TB                      | 1        | 1.14%   |
| Seagate ST2000DL003-9VT166 2TB                      | 1        | 1.14%   |
| Seagate ST1000NM0033-9ZM173 1TB                     | 1        | 1.14%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 13       | 19     | 44.83%  |
| WDC                 | 11       | 26     | 37.93%  |
| Toshiba             | 2        | 3      | 6.9%    |
| Samsung Electronics | 1        | 1      | 3.45%   |
| QEMU                | 1        | 2      | 3.45%   |
| HGST                | 1        | 1      | 3.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 5        | 6      | 25%     |
| Kingston            | 4        | 4      | 20%     |
| Micron Technology   | 2        | 3      | 10%     |
| WDC                 | 1        | 3      | 5%      |
| Team                | 1        | 1      | 5%      |
| SK hynix            | 1        | 1      | 5%      |
| SanDisk             | 1        | 2      | 5%      |
| Netac               | 1        | 1      | 5%      |
| LITEON              | 1        | 1      | 5%      |
| Intel               | 1        | 1      | 5%      |
| Hewlett-Packard     | 1        | 1      | 5%      |
| Crucial             | 1        | 2      | 5%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 22       | 52     | 37.93%  |
| SSD  | 19       | 26     | 32.76%  |
| NVMe | 17       | 52     | 29.31%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 29       | 75     | 59.18%  |
| NVMe | 17       | 52     | 34.69%  |
| SAS  | 3        | 3      | 6.12%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.51-1.0   | 18       | 26     | 36%     |
| 0.01-0.5   | 15       | 18     | 30%     |
| 3.01-4.0   | 8        | 23     | 16%     |
| 1.01-2.0   | 5        | 6      | 10%     |
| 4.01-10.0  | 3        | 4      | 6%      |
| 2.01-3.0   | 1        | 1      | 2%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 7        | 21.21%  |
| More than 3000 | 6        | 18.18%  |
| 101-250        | 5        | 15.15%  |
| 2001-3000      | 4        | 12.12%  |
| 251-500        | 3        | 9.09%   |
| 1001-2000      | 3        | 9.09%   |
| Unknown        | 3        | 9.09%   |
| 1-20           | 1        | 3.03%   |
| 51-100         | 1        | 3.03%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 8        | 22.86%  |
| 21-50          | 6        | 17.14%  |
| 101-250        | 5        | 14.29%  |
| 251-500        | 3        | 8.57%   |
| 1001-2000      | 3        | 8.57%   |
| 51-100         | 3        | 8.57%   |
| Unknown        | 3        | 8.57%   |
| More than 3000 | 2        | 5.71%   |
| 2001-3000      | 1        | 2.86%   |
| 501-1000       | 1        | 2.86%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD4000FDYZ-27YA5B0 4TB        | 1        | 1      | 12.5%   |
| WDC WD20EARS-00J2GB0 2TB          | 1        | 1      | 12.5%   |
| SK hynix SH920 2.5 7MM 256GB SSD  | 1        | 1      | 12.5%   |
| Seagate ST4000DM000-1F2168 4TB    | 1        | 1      | 12.5%   |
| Seagate ST1000DM010-2EP102 1TB    | 1        | 2      | 12.5%   |
| Samsung Electronics HD642JJ 640GB | 1        | 1      | 12.5%   |
| Kingston SUV400S37240G 240GB SSD  | 1        | 1      | 12.5%   |
| HGST HTS725050A7E630 500GB        | 1        | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 2        | 2      | 25%     |
| Seagate             | 2        | 3      | 25%     |
| SK hynix            | 1        | 1      | 12.5%   |
| Samsung Electronics | 1        | 1      | 12.5%   |
| Kingston            | 1        | 1      | 12.5%   |
| HGST                | 1        | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 2        | 2      | 33.33%  |
| Seagate             | 2        | 3      | 33.33%  |
| Samsung Electronics | 1        | 1      | 16.67%  |
| HGST                | 1        | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 6        | 7      | 75%     |
| SSD  | 2        | 2      | 25%     |

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
| Detected | 18       | 61     | 41.86%  |
| Works    | 18       | 60     | 41.86%  |
| Malfunc  | 7        | 9      | 16.28%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 21       | 38.18%  |
| AMD                         | 12       | 21.82%  |
| Samsung Electronics         | 5        | 9.09%   |
| Kingston Technology Company | 4        | 7.27%   |
| SanDisk                     | 3        | 5.45%   |
| ASMedia Technology          | 3        | 5.45%   |
| LSI Logic / Symbios Logic   | 2        | 3.64%   |
| SK hynix                    | 1        | 1.82%   |
| Silicon Motion              | 1        | 1.82%   |
| Red Hat                     | 1        | 1.82%   |
| Micron/Crucial Technology   | 1        | 1.82%   |
| Broadcom / LSI              | 1        | 1.82%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 7        | 10%     |
| Intel SATA Controller [RAID Mode]                                                       | 6        | 8.57%   |
| AMD 400 Series Chipset SATA Controller                                                  | 4        | 5.71%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3        | 4.29%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 3        | 4.29%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 3        | 4.29%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2        | 2.86%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 2        | 2.86%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 2        | 2.86%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 2        | 2.86%   |
| AMD 500 Series Chipset SATA Controller                                                  | 2        | 2.86%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 1        | 1.43%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 1        | 1.43%   |
| SanDisk WD Blue SN570 NVMe SSD 2TB                                                      | 1        | 1.43%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD                 | 1        | 1.43%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 1        | 1.43%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 1        | 1.43%   |
| Red Hat Virtio 1.0 SCSI                                                                 | 1        | 1.43%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                                    | 1        | 1.43%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                 | 1        | 1.43%   |
| LSI Logic / Symbios Logic MegaRAID SAS 2108 [Liberator]                                 | 1        | 1.43%   |
| Kingston Company NV1 NVMe SSD SM2263XT (DRAM-less)                                      | 1        | 1.43%   |
| Kingston Company NV1 NVMe SSD E13T (DRAM-less)                                          | 1        | 1.43%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD E18                                      | 1        | 1.43%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                                | 1        | 1.43%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation                   | 1        | 1.43%   |
| Intel Raptor Lake SATA AHCI Controller                                                  | 1        | 1.43%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1        | 1.43%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 1        | 1.43%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 1        | 1.43%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1        | 1.43%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 1        | 1.43%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 1        | 1.43%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1        | 1.43%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 1.43%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 1.43%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 1        | 1.43%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1        | 1.43%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                                     | 1        | 1.43%   |
| ASMedia ASM1166 Serial ATA Controller                                                   | 1        | 1.43%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 26       | 44.07%  |
| NVMe | 16       | 27.12%  |
| RAID | 8        | 13.56%  |
| SAS  | 4        | 6.78%   |
| IDE  | 4        | 6.78%   |
| SCSI | 1        | 1.69%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 20       | 60.61%  |
| AMD    | 13       | 39.39%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel Xeon W-2223 CPU @ 3.60GHz                 | 1        | 3.03%   |
| Intel Xeon W-1350 @ 3.30GHz                     | 1        | 3.03%   |
| Intel Xeon E-2144G CPU @ 3.60GHz                | 1        | 3.03%   |
| Intel Xeon CPU X5550 @ 2.67GHz                  | 1        | 3.03%   |
| Intel Xeon CPU E5540 @ 2.53GHz                  | 1        | 3.03%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz              | 1        | 3.03%   |
| Intel Xeon CPU E5-2683 v4 @ 2.10GHz             | 1        | 3.03%   |
| Intel Xeon CPU E5-2667 v2 @ 3.30GHz             | 1        | 3.03%   |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz             | 1        | 3.03%   |
| Intel Core i7-7700 CPU @ 3.60GHz                | 1        | 3.03%   |
| Intel Core i7-3770 CPU @ 3.40GHz                | 1        | 3.03%   |
| Intel Core i7-14700K                            | 1        | 3.03%   |
| Intel Core i5-6500 CPU @ 3.20GHz                | 1        | 3.03%   |
| Intel Core i5-4440 CPU @ 3.10GHz                | 1        | 3.03%   |
| Intel Core i5-10400F CPU @ 2.90GHz              | 1        | 3.03%   |
| Intel Core i3-4130 CPU @ 3.40GHz                | 1        | 3.03%   |
| Intel Core i3-2130 CPU @ 3.40GHz                | 1        | 3.03%   |
| Intel 12th Gen Core i7-12700KF                  | 1        | 3.03%   |
| Intel 11th Gen Core i7-11700K @ 3.60GHz         | 1        | 3.03%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz          | 1        | 3.03%   |
| AMD Ryzen Threadripper PRO 3975WX 32-Cores      | 1        | 3.03%   |
| AMD Ryzen Threadripper 1920X 12-Core Processor  | 1        | 3.03%   |
| AMD Ryzen 9 5950X 16-Core Processor             | 1        | 3.03%   |
| AMD Ryzen 9 3950X 16-Core Processor             | 1        | 3.03%   |
| AMD Ryzen 9 3900X 12-Core Processor             | 1        | 3.03%   |
| AMD Ryzen 7 5800X3D 8-Core Processor            | 1        | 3.03%   |
| AMD Ryzen 5 5600G with Radeon Graphics          | 1        | 3.03%   |
| AMD Ryzen 5 3600 6-Core Processor               | 1        | 3.03%   |
| AMD Ryzen 5 3500X 6-Core Processor              | 1        | 3.03%   |
| AMD Ryzen 3 5300G with Radeon Graphics          | 1        | 3.03%   |
| AMD FX-8350 Eight-Core Processor                | 1        | 3.03%   |
| AMD EPYC-Rome Processor                         | 1        | 3.03%   |
| AMD A10-7850K Radeon R7, 12 Compute Cores 4C+8G | 1        | 3.03%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Xeon             | 9        | 27.27%  |
| Other                  | 3        | 9.09%   |
| Intel Core i7          | 3        | 9.09%   |
| Intel Core i5          | 3        | 9.09%   |
| AMD Ryzen 9            | 3        | 9.09%   |
| AMD Ryzen 5            | 3        | 9.09%   |
| Intel Core i3          | 2        | 6.06%   |
| AMD Ryzen Threadripper | 2        | 6.06%   |
| AMD Ryzen 7            | 1        | 3.03%   |
| AMD Ryzen 3            | 1        | 3.03%   |
| AMD FX                 | 1        | 3.03%   |
| AMD EPYC               | 1        | 3.03%   |
| AMD A10                | 1        | 3.03%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 11       | 33.33%  |
| 6      | 6        | 18.18%  |
| 16     | 4        | 12.12%  |
| 12     | 4        | 12.12%  |
| 2      | 3        | 9.09%   |
| 32     | 2        | 6.06%   |
| 8      | 2        | 6.06%   |
| 20     | 1        | 3.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 28       | 84.85%  |
| 2      | 4        | 12.12%  |
| 4      | 1        | 3.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 28       | 84.85%  |
| 1      | 5        | 15.15%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 33       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 6        | 17.14%  |
| 0xa0671    | 3        | 8.57%   |
| 0x08701021 | 3        | 8.57%   |
| 0x306e4    | 2        | 5.71%   |
| 0x306c3    | 2        | 5.71%   |
| 0x106a5    | 2        | 5.71%   |
| 0x0a50000d | 2        | 5.71%   |
| 0xa0655    | 1        | 2.86%   |
| 0x906ea    | 1        | 2.86%   |
| 0x906e9    | 1        | 2.86%   |
| 0x90672    | 1        | 2.86%   |
| 0x506e3    | 1        | 2.86%   |
| 0x50657    | 1        | 2.86%   |
| 0x306a9    | 1        | 2.86%   |
| 0x206d7    | 1        | 2.86%   |
| 0x206a7    | 1        | 2.86%   |
| 0x0a20120a | 1        | 2.86%   |
| 0x0a201016 | 1        | 2.86%   |
| 0x0830107a | 1        | 2.86%   |
| 0x08001137 | 1        | 2.86%   |
| 0x06003106 | 1        | 2.86%   |
| 0x06000852 | 1        | 2.86%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 2            | 6        | 18.18%  |
| Zen 3            | 4        | 12.12%  |
| IvyBridge        | 3        | 9.09%   |
| Icelake          | 3        | 9.09%   |
| Skylake          | 2        | 6.06%   |
| SandyBridge      | 2        | 6.06%   |
| Nehalem          | 2        | 6.06%   |
| KabyLake         | 2        | 6.06%   |
| Haswell          | 2        | 6.06%   |
| Alderlake Hybrid | 2        | 6.06%   |
| Zen              | 1        | 3.03%   |
| Steamroller      | 1        | 3.03%   |
| Piledriver       | 1        | 3.03%   |
| CometLake        | 1        | 3.03%   |
| Broadwell        | 1        | 3.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 16       | 47.06%  |
| AMD                        | 8        | 23.53%  |
| Intel                      | 7        | 20.59%  |
| Red Hat                    | 1        | 2.94%   |
| Matrox Electronics Systems | 1        | 2.94%   |
| ASPEED Technology          | 1        | 2.94%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Nvidia GA106 [Geforce RTX 3050]                                           | 2        | 5.88%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 2        | 5.88%   |
| Red Hat QXL paravirtual graphic card                                      | 1        | 2.94%   |
| Nvidia TU117GLM [Quadro T400 Mobile]                                      | 1        | 2.94%   |
| Nvidia TU117 [GeForce GTX 1650]                                           | 1        | 2.94%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                     | 1        | 2.94%   |
| Nvidia GP107GL [Quadro P620]                                              | 1        | 2.94%   |
| Nvidia GP104 [GeForce GTX 1080]                                           | 1        | 2.94%   |
| Nvidia GM204GL [Quadro M4000]                                             | 1        | 2.94%   |
| Nvidia GM204 [GeForce GTX 970]                                            | 1        | 2.94%   |
| Nvidia GM107GL [Quadro K2200]                                             | 1        | 2.94%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                         | 1        | 2.94%   |
| Nvidia GK208B [GeForce GT 730]                                            | 1        | 2.94%   |
| Nvidia GK104 [GeForce GTX 770]                                            | 1        | 2.94%   |
| Nvidia GF119 [GeForce GT 610]                                             | 1        | 2.94%   |
| Nvidia GF108GL [Quadro 600]                                               | 1        | 2.94%   |
| Nvidia AD102 [GeForce RTX 4090]                                           | 1        | 2.94%   |
| Matrox Electronics Systems MGA G200eW WPCM450                             | 1        | 2.94%   |
| Intel RocketLake-S GT1 [UHD Graphics P750]                                | 1        | 2.94%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                 | 1        | 2.94%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                | 1        | 2.94%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                    | 1        | 2.94%   |
| Intel HD Graphics 530                                                     | 1        | 2.94%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller | 1        | 2.94%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 1        | 2.94%   |
| ASPEED Technology ASPEED Graphics Family                                  | 1        | 2.94%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                  | 1        | 2.94%   |
| AMD RS780L [Radeon 3000]                                                  | 1        | 2.94%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                            | 1        | 2.94%   |
| AMD Kaveri [Radeon R7 Graphics]                                           | 1        | 2.94%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                   | 1        | 2.94%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]       | 1        | 2.94%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x Nvidia   | 15       | 45.45%  |
| 1 x Intel    | 7        | 21.21%  |
| 1 x AMD      | 7        | 21.21%  |
| 1 x Red Hat  | 1        | 3.03%   |
| 1 x Matrox   | 1        | 3.03%   |
| 1 x ASPEED   | 1        | 3.03%   |
| AMD + Nvidia | 1        | 3.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 20       | 58.82%  |
| Proprietary | 8        | 23.53%  |
| Unknown     | 6        | 17.65%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 15       | 44.12%  |
| 7.01-8.0   | 5        | 14.71%  |
| 1.01-2.0   | 4        | 11.76%  |
| 3.01-4.0   | 3        | 8.82%   |
| 0.51-1.0   | 3        | 8.82%   |
| 0.01-0.5   | 2        | 5.88%   |
| 5.01-6.0   | 1        | 2.94%   |
| 16.01-24.0 | 1        | 2.94%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Dell                | 5        | 17.24%  |
| Eizo                | 4        | 13.79%  |
| Samsung Electronics | 3        | 10.34%  |
| Philips             | 3        | 10.34%  |
| ViewSonic           | 2        | 6.9%    |
| Goldstar            | 2        | 6.9%    |
| BenQ                | 2        | 6.9%    |
| Acer                | 2        | 6.9%    |
| TopView             | 1        | 3.45%   |
| STD                 | 1        | 3.45%   |
| Medion              | 1        | 3.45%   |
| Lenovo              | 1        | 3.45%   |
| ASUSTek Computer    | 1        | 3.45%   |
| AOC                 | 1        | 3.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| ViewSonic VX2233wm-1 VSC1D22 1920x1080 477x268mm 21.5-inch           | 1        | 3.13%   |
| ViewSonic VA2232 Series VSC8224 1680x1050 474x296mm 22.0-inch        | 1        | 3.13%   |
| TopView HD TV TOPC37E 1920x1080 700x390mm 31.5-inch                  | 1        | 3.13%   |
| STD HDMI TV STD00C7 1440x900 698x392mm 31.5-inch                     | 1        | 3.13%   |
| Samsung Electronics SyncMaster SAM021B 1400x1050 408x300mm 19.9-inch | 1        | 3.13%   |
| Samsung Electronics S27H65x SAM0E1D 1920x1080 598x336mm 27.0-inch    | 1        | 3.13%   |
| Samsung Electronics LCD Monitor S32B80P 5760x2160                    | 1        | 3.13%   |
| Samsung Electronics LCD Monitor S32B80P                              | 1        | 3.13%   |
| Samsung Electronics F27G3xTF SAM710D 1920x1080 600x330mm 27.0-inch   | 1        | 3.13%   |
| Philips PHL 272B7QU PHL0926 2560x1440 597x336mm 27.0-inch            | 1        | 3.13%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch              | 1        | 3.13%   |
| Philips 19B PHL0879 1280x1024 376x301mm 19.0-inch                    | 1        | 3.13%   |
| Medion MD7212AS MED4971 1280x1024 359x287mm 18.1-inch                | 1        | 3.13%   |
| Lenovo L24q-10 LEN65CF 2560x1440 527x296mm 23.8-inch                 | 1        | 3.13%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch             | 1        | 3.13%   |
| Goldstar 22EA53 GSM59A6 1920x1080 477x268mm 21.5-inch                | 1        | 3.13%   |
| Eizo RX220 ENC2146 1600x1200 440x330mm 21.7-inch                     | 1        | 3.13%   |
| Eizo RP3225-004 ENC3225 3840x2160 700x390mm 31.5-inch                | 1        | 3.13%   |
| Eizo LCD Monitor CG247 5760x2160                                     | 1        | 3.13%   |
| Eizo LCD Monitor CG247 1920x1200                                     | 1        | 3.13%   |
| Eizo EV2336W ENC2390 1920x1080 510x287mm 23.0-inch                   | 1        | 3.13%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 1        | 3.13%   |
| Dell P2417H DELA0DB 1920x1080 527x296mm 23.8-inch                    | 1        | 3.13%   |
| Dell LCD Monitor U2515H 2560x1440                                    | 1        | 3.13%   |
| Dell G2722HS DEL427D 1920x1080 597x336mm 27.0-inch                   | 1        | 3.13%   |
| Dell 1905FP DEL400C 1280x1024 376x301mm 19.0-inch                    | 1        | 3.13%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                    | 1        | 3.13%   |
| BenQ G700 BNQ7802 1280x1024 338x270mm 17.0-inch                      | 1        | 3.13%   |
| ASUSTek Computer VL278 AUS27C2 1920x1080 598x336mm 27.0-inch         | 1        | 3.13%   |
| AOC 2330V AOC2330 1920x1080 476x268mm 21.5-inch                      | 1        | 3.13%   |
| Acer K222HQL ACR03E1 1920x1080 477x268mm 21.5-inch                   | 1        | 3.13%   |
| Acer EK271 E ACR0B62 1920x1080 597x336mm 27.0-inch                   | 1        | 3.13%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 15       | 48.39%  |
| 1280x1024 (SXGA)   | 4        | 12.9%   |
| 2560x1440 (QHD)    | 3        | 9.68%   |
| 1920x1200 (WUXGA)  | 2        | 6.45%   |
| 5760x2160          | 1        | 3.23%   |
| 3840x2160 (4K)     | 1        | 3.23%   |
| 2560x1080          | 1        | 3.23%   |
| 1680x1050 (WSXGA+) | 1        | 3.23%   |
| 1600x1200          | 1        | 3.23%   |
| 1400x1050          | 1        | 3.23%   |
| Unknown            | 1        | 3.23%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 6        | 20%     |
| 21      | 5        | 16.67%  |
| 24      | 4        | 13.33%  |
| 31      | 3        | 10%     |
| Unknown | 3        | 10%     |
| 23      | 2        | 6.67%   |
| 19      | 2        | 6.67%   |
| 34      | 1        | 3.33%   |
| 22      | 1        | 3.33%   |
| 20      | 1        | 3.33%   |
| 18      | 1        | 3.33%   |
| 17      | 1        | 3.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 12       | 40%     |
| 401-500     | 7        | 23.33%  |
| 601-700     | 3        | 10%     |
| 351-400     | 3        | 10%     |
| Unknown     | 3        | 10%     |
| 701-800     | 1        | 3.33%   |
| 301-350     | 1        | 3.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 18       | 60%     |
| 5/4     | 3        | 10%     |
| Unknown | 3        | 10%     |
| 4/3     | 2        | 6.67%   |
| 16/10   | 2        | 6.67%   |
| 6/5     | 1        | 3.33%   |
| 21/9    | 1        | 3.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 10       | 33.33%  |
| 301-350        | 6        | 20%     |
| 151-200        | 5        | 16.67%  |
| 351-500        | 4        | 13.33%  |
| Unknown        | 3        | 10%     |
| 251-300        | 1        | 3.33%   |
| 141-150        | 1        | 3.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 18       | 64.29%  |
| 101-120 | 5        | 17.86%  |
| Unknown | 3        | 10.71%  |
| 121-160 | 2        | 7.14%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 22       | 64.71%  |
| 2     | 7        | 20.59%  |
| 0     | 5        | 14.71%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 18       | 42.86%  |
| Realtek Semiconductor | 14       | 33.33%  |
| TP-Link               | 2        | 4.76%   |
| Qualcomm Atheros      | 2        | 4.76%   |
| Broadcom              | 2        | 4.76%   |
| Ralink Technology     | 1        | 2.38%   |
| Ralink                | 1        | 2.38%   |
| Emulex                | 1        | 2.38%   |
| Broadcom Limited      | 1        | 2.38%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 12       | 21.05%  |
| Intel Ethernet Controller X550                                         | 3        | 5.26%   |
| Intel Ethernet Controller I225-V                                       | 3        | 5.26%   |
| Realtek RTL8125 2.5GbE Controller                                      | 2        | 3.51%   |
| Intel Wi-Fi 6 AX200                                                    | 2        | 3.51%   |
| Intel I350 Gigabit Network Connection                                  | 2        | 3.51%   |
| Intel I211 Gigabit Network Connection                                  | 2        | 3.51%   |
| Intel I210 Gigabit Network Connection                                  | 2        | 3.51%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2        | 3.51%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2        | 3.51%   |
| Intel 82574L Gigabit Network Connection                                | 2        | 3.51%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 2        | 3.51%   |
| TP-Link Archer T4U ver.3                                               | 1        | 1.75%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                 | 1        | 1.75%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 1        | 1.75%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                    | 1        | 1.75%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1        | 1.75%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1        | 1.75%   |
| Ralink MT7601U Wireless Adapter                                        | 1        | 1.75%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                              | 1        | 1.75%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1        | 1.75%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                       | 1        | 1.75%   |
| Intel Wireless 8265 / 8275                                             | 1        | 1.75%   |
| Intel Wireless 8260                                                    | 1        | 1.75%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                      | 1        | 1.75%   |
| Intel Ethernet Connection I219-LM                                      | 1        | 1.75%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1        | 1.75%   |
| Intel Ethernet Connection (5) I219-V                                   | 1        | 1.75%   |
| Intel Ethernet Connection (14) I219-LM                                 | 1        | 1.75%   |
| Intel 82579V Gigabit Network Connection                                | 1        | 1.75%   |
| Intel 82576 Gigabit Network Connection                                 | 1        | 1.75%   |
| Emulex OneConnect 10Gb NIC (be3)                                       | 1        | 1.75%   |
| Broadcom Limited NetXtreme II BCM5709 Gigabit Ethernet                 | 1        | 1.75%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 5        | 41.67%  |
| TP-Link               | 2        | 16.67%  |
| Realtek Semiconductor | 2        | 16.67%  |
| Ralink Technology     | 1        | 8.33%   |
| Ralink                | 1        | 8.33%   |
| Qualcomm Atheros      | 1        | 8.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                      | 2        | 16.67%  |
| TP-Link Archer T4U ver.3                                 | 1        | 8.33%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                   | 1        | 8.33%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter | 1        | 8.33%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter      | 1        | 8.33%   |
| Ralink MT7601U Wireless Adapter                          | 1        | 8.33%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                | 1        | 8.33%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter         | 1        | 8.33%   |
| Intel Wireless 8265 / 8275                               | 1        | 8.33%   |
| Intel Wireless 8260                                      | 1        | 8.33%   |
| Intel Raptor Lake-S PCH CNVi WiFi                        | 1        | 8.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 18       | 48.65%  |
| Realtek Semiconductor | 14       | 37.84%  |
| Broadcom              | 2        | 5.41%   |
| Qualcomm Atheros      | 1        | 2.7%    |
| Emulex                | 1        | 2.7%    |
| Broadcom Limited      | 1        | 2.7%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 12       | 26.67%  |
| Intel Ethernet Controller X550                                         | 3        | 6.67%   |
| Intel Ethernet Controller I225-V                                       | 3        | 6.67%   |
| Realtek RTL8125 2.5GbE Controller                                      | 2        | 4.44%   |
| Intel I350 Gigabit Network Connection                                  | 2        | 4.44%   |
| Intel I211 Gigabit Network Connection                                  | 2        | 4.44%   |
| Intel I210 Gigabit Network Connection                                  | 2        | 4.44%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2        | 4.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2        | 4.44%   |
| Intel 82574L Gigabit Network Connection                                | 2        | 4.44%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 2        | 4.44%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1        | 2.22%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1        | 2.22%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1        | 2.22%   |
| Intel Ethernet Connection I219-LM                                      | 1        | 2.22%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1        | 2.22%   |
| Intel Ethernet Connection (5) I219-V                                   | 1        | 2.22%   |
| Intel Ethernet Connection (14) I219-LM                                 | 1        | 2.22%   |
| Intel 82579V Gigabit Network Connection                                | 1        | 2.22%   |
| Intel 82576 Gigabit Network Connection                                 | 1        | 2.22%   |
| Emulex OneConnect 10Gb NIC (be3)                                       | 1        | 2.22%   |
| Broadcom Limited NetXtreme II BCM5709 Gigabit Ethernet                 | 1        | 2.22%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 32       | 72.73%  |
| WiFi     | 12       | 27.27%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 24       | 80%     |
| WiFi     | 6        | 20%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 2     | 13       | 39.39%  |
| 1     | 11       | 33.33%  |
| 3     | 4        | 12.12%  |
| 4     | 3        | 9.09%   |
| 5     | 1        | 3.03%   |
| 0     | 1        | 3.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 26       | 76.47%  |
| Yes  | 8        | 23.53%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 5        | 50%     |
| Broadcom                | 2        | 20%     |
| Realtek Semiconductor   | 1        | 10%     |
| Cambridge Silicon Radio | 1        | 10%     |
| ASUSTek Computer        | 1        | 10%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface                  | 2        | 20%     |
| Intel AX200 Bluetooth                               | 2        | 20%     |
| Realtek Bluetooth Radio                             | 1        | 10%     |
| Intel Bluetooth Device                              | 1        | 10%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1        | 10%     |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 10%     |
| Broadcom BCM2045 Bluetooth                          | 1        | 10%     |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 10%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 18       | 31.58%  |
| Nvidia                   | 16       | 28.07%  |
| AMD                      | 14       | 24.56%  |
| Micro Star International | 2        | 3.51%   |
| Plantronics              | 1        | 1.75%   |
| JMTek                    | 1        | 1.75%   |
| Giga-Byte Technology     | 1        | 1.75%   |
| Creative Technology      | 1        | 1.75%   |
| Conexant Systems         | 1        | 1.75%   |
| ASUSTek Computer         | 1        | 1.75%   |
| Apple                    | 1        | 1.75%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 7        | 10.94%  |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2        | 3.13%   |
| Nvidia GM204 High Definition Audio Controller                              | 2        | 3.13%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2        | 3.13%   |
| Nvidia GF108 High Definition Audio Controller                              | 2        | 3.13%   |
| Nvidia GA106 High Definition Audio Controller                              | 2        | 3.13%   |
| Micro Star International USB Audio                                         | 2        | 3.13%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2        | 3.13%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 2        | 3.13%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 3.13%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2        | 3.13%   |
| Intel 200 Series PCH HD Audio                                              | 2        | 3.13%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2        | 3.13%   |
| AMD Family 17h/19h HD Audio Controller                                     | 2        | 3.13%   |
| Plantronics Blackwire 320                                                  | 1        | 1.56%   |
| Nvidia TU116 High Definition Audio Controller                              | 1        | 1.56%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 1.56%   |
| Nvidia GP104 High Definition Audio Controller                              | 1        | 1.56%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 1.56%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1        | 1.56%   |
| Nvidia AD102 High Definition Audio Controller                              | 1        | 1.56%   |
| JMTek USB PnP Audio Device                                                 | 1        | 1.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1        | 1.56%   |
| Intel Raptor Lake High Definition Audio Controller                         | 1        | 1.56%   |
| Intel Comet Lake PCH-V cAVS                                                | 1        | 1.56%   |
| Intel Cannon Lake PCH cAVS                                                 | 1        | 1.56%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 1        | 1.56%   |
| Intel Alder Lake-S HD Audio Controller                                     | 1        | 1.56%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1        | 1.56%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1        | 1.56%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1        | 1.56%   |
| Giga-Byte Technology USB Audio                                             | 1        | 1.56%   |
| Creative Technology Stage Air V2                                           | 1        | 1.56%   |
| Conexant Systems G941                                                      | 1        | 1.56%   |
| ASUSTek Computer USB Audio                                                 | 1        | 1.56%   |
| Apple USB-C to 3.5mm Headphone Jack Adapter                                | 1        | 1.56%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 1        | 1.56%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1        | 1.56%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                     | 1        | 1.56%   |
| AMD Navi 10 HDMI Audio                                                     | 1        | 1.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 5        | 22.73%  |
| Samsung Electronics | 4        | 18.18%  |
| G.Skill             | 3        | 13.64%  |
| SK hynix            | 2        | 9.09%   |
| Micron Technology   | 2        | 9.09%   |
| Crucial             | 2        | 9.09%   |
| Unknown             | 1        | 4.55%   |
| QEMU                | 1        | 4.55%   |
| Corsair             | 1        | 4.55%   |
| Unknown             | 1        | 4.55%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s  | 2        | 8.7%    |
| Unknown RAM Module 8GB DIMM 1600MT/s                   | 1        | 4.35%   |
| SK hynix RAM HMT351U6AFR8C-H9 4GB DIMM DDR3 1333MT/s   | 1        | 4.35%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s   | 1        | 4.35%   |
| Samsung RAM Module 16GB DIMM DDR4 2667MT/s             | 1        | 4.35%   |
| Samsung RAM M393A1K43DB1-CVF 8GB DIMM DDR4 2933MT/s    | 1        | 4.35%   |
| Samsung RAM M378A5244CB0-CRC 4GB DIMM DDR4 3066MT/s    | 1        | 4.35%   |
| Samsung RAM M378A4G43MB1-CTD 32GB DIMM DDR4 3466MT/s   | 1        | 4.35%   |
| QEMU RAM Module 8GB DIMM RAM                           | 1        | 4.35%   |
| Micron RAM 9ASF2G72AZ-3G2B1 16GB DIMM DDR4 3200MT/s    | 1        | 4.35%   |
| Micron RAM 36KSF2G72PZ-1G6E1 16GB DIMM DDR3 1600MT/s   | 1        | 4.35%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s   | 1        | 4.35%   |
| Kingston RAM ACR256X64D3U1333C9 2GB DIMM DDR3 1333MT/s | 1        | 4.35%   |
| Kingston RAM 99U5458-005.A01LF 4GB DIMM DDR3 1333MT/s  | 1        | 4.35%   |
| Kingston RAM 9905458-013.A00LF 4GB DIMM DDR3 1333MT/s  | 1        | 4.35%   |
| G.Skill RAM F4-4000C15-8GVK 8GB DIMM DDR4 2133MT/s     | 1        | 4.35%   |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s | 1        | 4.35%   |
| G.Skill RAM F3-12800CL9-4GBXL 4GB DIMM DDR3 1867MT/s   | 1        | 4.35%   |
| Crucial RAM CT8G4DFRA32A.C4FE 8GB DIMM DDR4 3200MT/s   | 1        | 4.35%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s  | 1        | 4.35%   |
| Corsair RAM CMK64GX4M4E3200C16 16GB DIMM DDR4 3200MT/s | 1        | 4.35%   |
| Unknown                                                | 1        | 4.35%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 12       | 60%     |
| DDR3    | 6        | 30%     |
| RAM     | 1        | 5%      |
| Unknown | 1        | 5%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 20       | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 9        | 42.86%  |
| 16384 | 6        | 28.57%  |
| 4096  | 4        | 19.05%  |
| 32768 | 1        | 4.76%   |
| 2048  | 1        | 4.76%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 6        | 28.57%  |
| 1600    | 4        | 19.05%  |
| 1333    | 2        | 9.52%   |
| 3733    | 1        | 4.76%   |
| 3466    | 1        | 4.76%   |
| 3066    | 1        | 4.76%   |
| 2933    | 1        | 4.76%   |
| 2667    | 1        | 4.76%   |
| 2400    | 1        | 4.76%   |
| 2133    | 1        | 4.76%   |
| 1867    | 1        | 4.76%   |
| Unknown | 1        | 4.76%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 1        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| HP LaserJet P1102 | 1        | 100%    |

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


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Microsoft           | 2        | 25%     |
| Microdia            | 2        | 25%     |
| Logitech            | 2        | 25%     |
| Creative Technology | 1        | 12.5%   |
| Apple               | 1        | 12.5%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Microsoft LifeCam VX-700            | 1        | 12.5%   |
| Microsoft LifeCam HD-3000           | 1        | 12.5%   |
| Microdia USB 2.0 Camera             | 1        | 12.5%   |
| Microdia Integrated Camera          | 1        | 12.5%   |
| Logitech Webcam C270                | 1        | 12.5%   |
| Logitech Webcam B500                | 1        | 12.5%   |
| Creative Live! Cam Chat HD [VF0700] | 1        | 12.5%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR  | 1        | 12.5%   |

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

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| OmniKey | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                       | Desktops | Percent |
|-----------------------------|----------|---------|
| OmniKey CardMan 3021 / 3121 | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 23       | 67.65%  |
| 1     | 8        | 23.53%  |
| 5     | 1        | 2.94%   |
| 3     | 1        | 2.94%   |
| 2     | 1        | 2.94%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 5        | 33.33%  |
| Sound                    | 2        | 13.33%  |
| Net/wireless             | 2        | 13.33%  |
| Net/ethernet             | 2        | 13.33%  |
| Unassigned class         | 1        | 6.67%   |
| Storage/raid             | 1        | 6.67%   |
| Storage/ide              | 1        | 6.67%   |
| Communication controller | 1        | 6.67%   |

