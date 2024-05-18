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

Total: 119

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | Kabini CRB NOK              | [dfa3d8f2cd](https://linux-hardware.org/?probe=dfa3d8f2cd) | Apr 29, 2024 |
| Haier         | TIGD2-CI                    | [dc4f526a80](https://linux-hardware.org/?probe=dc4f526a80) | Apr 23, 2024 |
| Dell          | 0D441T A01                  | [98b14bc73d](https://linux-hardware.org/?probe=98b14bc73d) | Apr 10, 2024 |
| Gigabyte      | X570 AORUS ULTRA            | [7db787716d](https://linux-hardware.org/?probe=7db787716d) | Mar 12, 2024 |
| ASUSTek       | P6X58D PREMIUM              | [ffc080a6f0](https://linux-hardware.org/?probe=ffc080a6f0) | Mar 09, 2024 |
| ASUSTek       | P6X58D PREMIUM              | [3a33a36874](https://linux-hardware.org/?probe=3a33a36874) | Mar 09, 2024 |
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
| AlmaLinux 9.1 | 8        | 19.05%  |
| AlmaLinux 9.2 | 6        | 14.29%  |
| AlmaLinux 9.3 | 5        | 11.9%   |
| AlmaLinux 8.9 | 5        | 11.9%   |
| AlmaLinux 8.8 | 5        | 11.9%   |
| AlmaLinux 8.7 | 5        | 11.9%   |
| AlmaLinux 9.0 | 3        | 7.14%   |
| AlmaLinux 8.6 | 2        | 4.76%   |
| AlmaLinux 8.5 | 1        | 2.38%   |
| AlmaLinux 8.4 | 1        | 2.38%   |
| AlmaLinux 8.3 | 1        | 2.38%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| AlmaLinux | 37       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Desktops | Percent |
|------------------------------|----------|---------|
| 4.18.0-425.3.1.el8.x86_64    | 5        | 11.63%  |
| 5.14.0-362.8.1.el9_3.x86_64  | 3        | 6.98%   |
| 5.14.0-284.30.1.el9_2.x86_64 | 3        | 6.98%   |
| 5.14.0-162.12.1.el9_1.x86_64 | 3        | 6.98%   |
| 5.14.0-70.30.1.el9_0.x86_64  | 2        | 4.65%   |
| 5.14.0-284.18.1.el9_2.x86_64 | 2        | 4.65%   |
| 5.14.0-162.6.1.el9_1.x86_64  | 2        | 4.65%   |
| 4.18.0-477.27.2.el8_8.x86_64 | 2        | 4.65%   |
| 4.18.0-477.21.1.el8_8.x86_64 | 2        | 4.65%   |
| 6.8.7-1.el8.elrepo.x86_64    | 1        | 2.33%   |
| 6.1.24-1kx.el9.x86_64        | 1        | 2.33%   |
| 5.4.274-1.el8.elrepo.x86_64  | 1        | 2.33%   |
| 5.14.0-70.22.1.el9_0.x86_64  | 1        | 2.33%   |
| 5.14.0-362.24.2.el9_3.x86_64 | 1        | 2.33%   |
| 5.14.0-362.13.1.el9_3.x86_64 | 1        | 2.33%   |
| 5.14.0-284.11.1.el9_2.x86_64 | 1        | 2.33%   |
| 5.14.0-162.22.2.el9_1.x86_64 | 1        | 2.33%   |
| 5.14.0-162.18.1.el9_1.x86_64 | 1        | 2.33%   |
| 4.18.0-513.9.1.el8_9.x86_64  | 1        | 2.33%   |
| 4.18.0-513.5.1.el8_9.x86_64  | 1        | 2.33%   |
| 4.18.0-477.13.1.el8_8.x86_64 | 1        | 2.33%   |
| 4.18.0-477.10.1.el8_8.x86_64 | 1        | 2.33%   |
| 4.18.0-425.19.2.el8_7.x86_64 | 1        | 2.33%   |
| 4.18.0-425.13.1.el8_7.x86_64 | 1        | 2.33%   |
| 4.18.0-372.9.1.el8.x86_64    | 1        | 2.33%   |
| 4.18.0-348.12.2.el8_5.x86_64 | 1        | 2.33%   |
| 4.18.0-305.el8.x86_64        | 1        | 2.33%   |
| 4.18.0-240.15.1.el8_3.x86_64 | 1        | 2.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.14.0  | 21       | 55.26%  |
| 4.18.0  | 14       | 36.84%  |
| 6.8.7   | 1        | 2.63%   |
| 6.1.24  | 1        | 2.63%   |
| 5.4.274 | 1        | 2.63%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.14    | 21       | 55.26%  |
| 4.18    | 14       | 36.84%  |
| 6.8     | 1        | 2.63%   |
| 6.1     | 1        | 2.63%   |
| 5.4     | 1        | 2.63%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 37       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 25       | 65.79%  |
| Unknown    | 8        | 21.05%  |
| KDE5       | 3        | 7.89%   |
| XFCE       | 1        | 2.63%   |
| X-Cinnamon | 1        | 2.63%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 19       | 48.72%  |
| Wayland | 15       | 38.46%  |
| Unknown | 3        | 7.69%   |
| Tty     | 2        | 5.13%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 21       | 55.26%  |
| GDM     | 15       | 39.47%  |
| SDDM    | 1        | 2.63%   |
| LightDM | 1        | 2.63%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 18       | 47.37%  |
| en_GB   | 3        | 7.89%   |
| ru_RU   | 2        | 5.26%   |
| en_CA   | 2        | 5.26%   |
| en_AU   | 2        | 5.26%   |
| de_DE   | 2        | 5.26%   |
| Unknown | 2        | 5.26%   |
| zh_CN   | 1        | 2.63%   |
| uk_UA   | 1        | 2.63%   |
| ru_UA   | 1        | 2.63%   |
| pl_PL   | 1        | 2.63%   |
| hu_HU   | 1        | 2.63%   |
| fr_FR   | 1        | 2.63%   |
| da_DK   | 1        | 2.63%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 21       | 56.76%  |
| BIOS | 16       | 43.24%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Xfs   | 29       | 78.38%  |
| Ext4  | 7        | 18.92%  |
| Btrfs | 1        | 2.7%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 16       | 43.24%  |
| Unknown | 13       | 35.14%  |
| MBR     | 8        | 21.62%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 30       | 81.08%  |
| Yes       | 7        | 18.92%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 30       | 81.08%  |
| Yes       | 7        | 18.92%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 7        | 18.92%  |
| ASUSTek Computer    | 7        | 18.92%  |
| MSI                 | 5        | 13.51%  |
| Gigabyte Technology | 5        | 13.51%  |
| Lenovo              | 3        | 8.11%   |
| Intel               | 2        | 5.41%   |
| Dell                | 2        | 5.41%   |
| ASRock              | 2        | 5.41%   |
| Supermicro          | 1        | 2.7%    |
| Optimized Hosting   | 1        | 2.7%    |
| Haier               | 1        | 2.7%    |
| ASRockRack          | 1        | 2.7%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Desktops | Percent |
|-------------------------------------------|----------|---------|
| Supermicro PIO-617R-TLN4F+-ST031          | 1        | 2.7%    |
| Optimized Hosting KVM                     | 1        | 2.7%    |
| MSI MS-7D91                               | 1        | 2.7%    |
| MSI MS-7D07                               | 1        | 2.7%    |
| MSI MS-7C95                               | 1        | 2.7%    |
| MSI MS-7900                               | 1        | 2.7%    |
| MSI MS-7816                               | 1        | 2.7%    |
| Lenovo ThinkStation P350 30E6S20S00       | 1        | 2.7%    |
| Lenovo H520S 10093                        | 1        | 2.7%    |
| Lenovo H515s 10126                        | 1        | 2.7%    |
| Intel X99                                 | 1        | 2.7%    |
| Intel TTL TEKNOPRO                        | 1        | 2.7%    |
| HP Z820 Workstation                       | 1        | 2.7%    |
| HP Z620 Workstation                       | 1        | 2.7%    |
| HP Z600 Workstation                       | 1        | 2.7%    |
| HP Z400 Workstation                       | 1        | 2.7%    |
| HP Z4 G4 Workstation                      | 1        | 2.7%    |
| HP Z2 Tower G4 Workstation                | 1        | 2.7%    |
| HP Victus by 15L Gaming Desktop TG02-0xxx | 1        | 2.7%    |
| Haier HaierComputer                       | 1        | 2.7%    |
| Gigabyte Z590 AORUS PRO AX                | 1        | 2.7%    |
| Gigabyte X570S UD                         | 1        | 2.7%    |
| Gigabyte X570 AORUS ULTRA                 | 1        | 2.7%    |
| Gigabyte X399 DESIGNARE EX                | 1        | 2.7%    |
| Gigabyte H81M-D2V                         | 1        | 2.7%    |
| Dell OptiPlex 980                         | 1        | 2.7%    |
| Dell OptiPlex 5050                        | 1        | 2.7%    |
| ASUS TUF Gaming B450-PLUS II              | 1        | 2.7%    |
| ASUS Q170M2                               | 1        | 2.7%    |
| ASUS Pro WS WRX80E-SAGE SE WIFI           | 1        | 2.7%    |
| ASUS PRIME B550-PLUS                      | 1        | 2.7%    |
| ASUS P6X58D PREMIUM                       | 1        | 2.7%    |
| ASUS M5A78L-M/USB3                        | 1        | 2.7%    |
| ASUS CROSSHAIR VI HERO                    | 1        | 2.7%    |
| ASRockRack X470D4U2-2T                    | 1        | 2.7%    |
| ASRock B460 Phantom Gaming 4              | 1        | 2.7%    |
| ASRock B450M Pro4 R2.0                    | 1        | 2.7%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| Dell OptiPlex                    | 2        | 5.41%   |
| Supermicro PIO-617R-TLN4F+-ST031 | 1        | 2.7%    |
| Optimized Hosting KVM            | 1        | 2.7%    |
| MSI MS-7D91                      | 1        | 2.7%    |
| MSI MS-7D07                      | 1        | 2.7%    |
| MSI MS-7C95                      | 1        | 2.7%    |
| MSI MS-7900                      | 1        | 2.7%    |
| MSI MS-7816                      | 1        | 2.7%    |
| Lenovo ThinkStation              | 1        | 2.7%    |
| Lenovo H520S                     | 1        | 2.7%    |
| Lenovo H515s                     | 1        | 2.7%    |
| Intel X99                        | 1        | 2.7%    |
| Intel TTL                        | 1        | 2.7%    |
| HP Z820                          | 1        | 2.7%    |
| HP Z620                          | 1        | 2.7%    |
| HP Z600                          | 1        | 2.7%    |
| HP Z400                          | 1        | 2.7%    |
| HP Z4                            | 1        | 2.7%    |
| HP Z2                            | 1        | 2.7%    |
| HP Victus                        | 1        | 2.7%    |
| Haier HaierComputer              | 1        | 2.7%    |
| Gigabyte Z590                    | 1        | 2.7%    |
| Gigabyte X570S                   | 1        | 2.7%    |
| Gigabyte X570                    | 1        | 2.7%    |
| Gigabyte X399                    | 1        | 2.7%    |
| Gigabyte H81M-D2V                | 1        | 2.7%    |
| ASUS TUF                         | 1        | 2.7%    |
| ASUS Q170M2                      | 1        | 2.7%    |
| ASUS Pro                         | 1        | 2.7%    |
| ASUS PRIME                       | 1        | 2.7%    |
| ASUS P6X58D                      | 1        | 2.7%    |
| ASUS M5A78L-M                    | 1        | 2.7%    |
| ASUS CROSSHAIR                   | 1        | 2.7%    |
| ASRockRack X470D4U2-2T           | 1        | 2.7%    |
| ASRock B460                      | 1        | 2.7%    |
| ASRock B450M                     | 1        | 2.7%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 7        | 18.92%  |
| 2013 | 5        | 13.51%  |
| 2021 | 4        | 10.81%  |
| 2012 | 4        | 10.81%  |
| 2019 | 3        | 8.11%   |
| 2018 | 3        | 8.11%   |
| 2010 | 3        | 8.11%   |
| 2022 | 2        | 5.41%   |
| 2015 | 2        | 5.41%   |
| 2017 | 1        | 2.7%    |
| 2014 | 1        | 2.7%    |
| 2011 | 1        | 2.7%    |
| 2009 | 1        | 2.7%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 37       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 34       | 89.47%  |
| Enabled  | 4        | 10.53%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 37       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 64.01-256.0     | 12       | 32.43%  |
| 4.01-8.0        | 8        | 21.62%  |
| 8.01-16.0       | 6        | 16.22%  |
| 24.01-32.0      | 5        | 13.51%  |
| 32.01-64.0      | 2        | 5.41%   |
| 16.01-24.0      | 2        | 5.41%   |
| More than 256.0 | 1        | 2.7%    |
| 3.01-4.0        | 1        | 2.7%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 8        | 21.05%  |
| 2.01-3.0   | 8        | 21.05%  |
| 3.01-4.0   | 7        | 18.42%  |
| 1.01-2.0   | 6        | 15.79%  |
| 0.51-1.0   | 3        | 7.89%   |
| 32.01-64.0 | 2        | 5.26%   |
| 8.01-16.0  | 2        | 5.26%   |
| 24.01-32.0 | 1        | 2.63%   |
| 16.01-24.0 | 1        | 2.63%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 3      | 11       | 28.95%  |
| 1      | 9        | 23.68%  |
| 4      | 7        | 18.42%  |
| 2      | 6        | 15.79%  |
| 6      | 2        | 5.26%   |
| 5      | 2        | 5.26%   |
| 10     | 1        | 2.63%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 24       | 64.86%  |
| Yes       | 13       | 35.14%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 36       | 97.3%   |
| No        | 1        | 2.7%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 24       | 64.86%  |
| Yes       | 13       | 35.14%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 26       | 70.27%  |
| Yes       | 11       | 29.73%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 5        | 13.51%  |
| Russia      | 5        | 13.51%  |
| Canada      | 4        | 10.81%  |
| France      | 3        | 8.11%   |
| China       | 3        | 8.11%   |
| Ukraine     | 2        | 5.41%   |
| Switzerland | 2        | 5.41%   |
| Romania     | 2        | 5.41%   |
| Hungary     | 2        | 5.41%   |
| Australia   | 2        | 5.41%   |
| UK          | 1        | 2.7%    |
| Netherlands | 1        | 2.7%    |
| Italy       | 1        | 2.7%    |
| Greenland   | 1        | 2.7%    |
| Germany     | 1        | 2.7%    |
| Czechia     | 1        | 2.7%    |
| Austria     | 1        | 2.7%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Tunari           | 2        | 5.41%   |
| Moscow           | 2        | 5.41%   |
| Zaporizhzhia     | 1        | 2.7%    |
| Vienna           | 1        | 2.7%    |
| Varosfoeld       | 1        | 2.7%    |
| Strasbourg       | 1        | 2.7%    |
| Stadtilm         | 1        | 2.7%    |
| St. Paul         | 1        | 2.7%    |
| Shimanovsk       | 1        | 2.7%    |
| Shanghai         | 1        | 2.7%    |
| Saint-Cloud      | 1        | 2.7%    |
| Saint-Brieuc     | 1        | 2.7%    |
| Rochester        | 1        | 2.7%    |
| Pardubice        | 1        | 2.7%    |
| Nizhniy Novgorod | 1        | 2.7%    |
| Montreal         | 1        | 2.7%    |
| Milan            | 1        | 2.7%    |
| Melbourne        | 1        | 2.7%    |
| Kyiv             | 1        | 2.7%    |
| Kitimat          | 1        | 2.7%    |
| Jilin City       | 1        | 2.7%    |
| Ilulissat        | 1        | 2.7%    |
| Groningen        | 1        | 2.7%    |
| Geneva           | 1        | 2.7%    |
| DeLand           | 1        | 2.7%    |
| Concord          | 1        | 2.7%    |
| Cincinnati       | 1        | 2.7%    |
| Budapest         | 1        | 2.7%    |
| Brisbane         | 1        | 2.7%    |
| Bloomington      | 1        | 2.7%    |
| Bellevue         | 1        | 2.7%    |
| Beijing          | 1        | 2.7%    |
| Beauharnois      | 1        | 2.7%    |
| Basel            | 1        | 2.7%    |
| Arzamas          | 1        | 2.7%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 17       | 24     | 23.61%  |
| Samsung Electronics         | 14       | 20     | 19.44%  |
| WDC                         | 12       | 29     | 16.67%  |
| Kingston                    | 5        | 8      | 6.94%   |
| SanDisk                     | 4        | 8      | 5.56%   |
| Toshiba                     | 2        | 3      | 2.78%   |
| SK hynix                    | 2        | 2      | 2.78%   |
| Micron Technology           | 2        | 3      | 2.78%   |
| Hitachi                     | 2        | 2      | 2.78%   |
| Crucial                     | 2        | 4      | 2.78%   |
| Team                        | 1        | 1      | 1.39%   |
| Silicon Motion              | 1        | 14     | 1.39%   |
| QEMU                        | 1        | 2      | 1.39%   |
| Netac                       | 1        | 1      | 1.39%   |
| LITEON                      | 1        | 1      | 1.39%   |
| Kingston Technology Company | 1        | 1      | 1.39%   |
| Intel                       | 1        | 1      | 1.39%   |
| HGST                        | 1        | 1      | 1.39%   |
| Hewlett-Packard             | 1        | 1      | 1.39%   |
| AMD                         | 1        | 15     | 1.39%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 3        | 3.03%   |
| WDC WD10EZEX-08WN4A0 1TB                          | 2        | 2.02%   |
| Seagate ST4000DM000-1F2168 4TB                    | 2        | 2.02%   |
| Seagate ST320LT020-9YG142 320GB                   | 2        | 2.02%   |
| Samsung NVMe SSD Controller SM951/PM951 256GB     | 2        | 2.02%   |
| Kingston SA400S37480G 480GB SSD                   | 2        | 2.02%   |
| Hitachi HTS543232A7A384 320GB                     | 2        | 2.02%   |
| WDC WDS100T2B0B-00YS70 1TB SSD                    | 1        | 1.01%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                    | 1        | 1.01%   |
| WDC WD60EFRX-68L0BN1 6TB                          | 1        | 1.01%   |
| WDC WD40EZRX-00SPEB0 4TB                          | 1        | 1.01%   |
| WDC WD40EFZX-68AWUN0 4TB                          | 1        | 1.01%   |
| WDC WD40EFRX-68N32N0 4TB                          | 1        | 1.01%   |
| WDC WD40EFAX-68JH4N1 4TB                          | 1        | 1.01%   |
| WDC WD4000FYYZ-01UL1B2 4TB                        | 1        | 1.01%   |
| WDC WD4000FYYZ-01UL1B1 4TB                        | 1        | 1.01%   |
| WDC WD4000FDYZ-27YA5B0 4TB                        | 1        | 1.01%   |
| WDC WD4000F9YZ-09N20L1 4TB                        | 1        | 1.01%   |
| WDC WD3600FYYZ-01UL1B3 4TB                        | 1        | 1.01%   |
| WDC WD3600FYYZ-01UL1B1 4TB                        | 1        | 1.01%   |
| WDC WD35EFRX-68WT0N0 4TB                          | 1        | 1.01%   |
| WDC WD20EZBX-60AYRA0 2TB                          | 1        | 1.01%   |
| WDC WD20EARS-00J2GB0 2TB                          | 1        | 1.01%   |
| WDC WD10EZEX-75M2NA0 1TB                          | 1        | 1.01%   |
| WDC WD10EZEX-08M2NA0 1TB                          | 1        | 1.01%   |
| WDC WD10EZEX-00KUWA0 1TB                          | 1        | 1.01%   |
| WDC RAT035VWHG-GTK4D7 4TB                         | 1        | 1.01%   |
| WDC RAT035VQHR-GTK4D7 4TB                         | 1        | 1.01%   |
| Toshiba MG06ACA800E 8TB                           | 1        | 1.01%   |
| Toshiba DT01ACA100 1TB                            | 1        | 1.01%   |
| Team T253X1480G 480GB SSD                         | 1        | 1.01%   |
| SK hynix SH920 2.5 7MM 256GB SSD                  | 1        | 1.01%   |
| SK hynix BC711 HFM512GD3JX013N 512GB              | 1        | 1.01%   |
| Silicon Motion SM2262/SM2262EN SSD Controller 2TB | 1        | 1.01%   |
| Seagate ST4000NM000A 00MX141 00MX141LEN 4TB       | 1        | 1.01%   |
| Seagate ST4000NC001-1FS168 4TB                    | 1        | 1.01%   |
| Seagate ST4000DM005-2DP166 4TB                    | 1        | 1.01%   |
| Seagate ST3500418AS 500GB                         | 1        | 1.01%   |
| Seagate ST3160815AS 160GB                         | 1        | 1.01%   |
| Seagate ST31000528AS 1TB                          | 1        | 1.01%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 17       | 24     | 48.57%  |
| WDC                 | 11       | 26     | 31.43%  |
| Toshiba             | 2        | 3      | 5.71%   |
| Hitachi             | 2        | 2      | 5.71%   |
| Samsung Electronics | 1        | 1      | 2.86%   |
| QEMU                | 1        | 2      | 2.86%   |
| HGST                | 1        | 1      | 2.86%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 6        | 7      | 28.57%  |
| Kingston            | 4        | 4      | 19.05%  |
| Micron Technology   | 2        | 3      | 9.52%   |
| WDC                 | 1        | 3      | 4.76%   |
| Team                | 1        | 1      | 4.76%   |
| SK hynix            | 1        | 1      | 4.76%   |
| SanDisk             | 1        | 2      | 4.76%   |
| Netac               | 1        | 1      | 4.76%   |
| LITEON              | 1        | 1      | 4.76%   |
| Intel               | 1        | 1      | 4.76%   |
| Hewlett-Packard     | 1        | 1      | 4.76%   |
| Crucial             | 1        | 2      | 4.76%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 26       | 59     | 39.39%  |
| NVMe | 20       | 55     | 30.3%   |
| SSD  | 20       | 27     | 30.3%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 33       | 83     | 58.93%  |
| NVMe | 20       | 55     | 35.71%  |
| SAS  | 3        | 3      | 5.36%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 19       | 24     | 35.19%  |
| 0.51-1.0   | 18       | 27     | 33.33%  |
| 3.01-4.0   | 8        | 23     | 14.81%  |
| 1.01-2.0   | 5        | 7      | 9.26%   |
| 4.01-10.0  | 3        | 4      | 5.56%   |
| 2.01-3.0   | 1        | 1      | 1.85%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 9        | 24.32%  |
| More than 3000 | 6        | 16.22%  |
| 101-250        | 6        | 16.22%  |
| 251-500        | 4        | 10.81%  |
| 2001-3000      | 4        | 10.81%  |
| 1001-2000      | 3        | 8.11%   |
| Unknown        | 3        | 8.11%   |
| 1-20           | 1        | 2.7%    |
| 51-100         | 1        | 2.7%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 10       | 25.64%  |
| 21-50          | 7        | 17.95%  |
| 101-250        | 7        | 17.95%  |
| 251-500        | 3        | 7.69%   |
| 1001-2000      | 3        | 7.69%   |
| Unknown        | 3        | 7.69%   |
| More than 3000 | 2        | 5.13%   |
| 51-100         | 2        | 5.13%   |
| 2001-3000      | 1        | 2.56%   |
| 501-1000       | 1        | 2.56%   |

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
| Works    | 22       | 70     | 45.83%  |
| Detected | 19       | 62     | 39.58%  |
| Malfunc  | 7        | 9      | 14.58%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 24       | 37.5%   |
| AMD                         | 14       | 21.88%  |
| Samsung Electronics         | 8        | 12.5%   |
| Kingston Technology Company | 4        | 6.25%   |
| SanDisk                     | 3        | 4.69%   |
| ASMedia Technology          | 3        | 4.69%   |
| LSI Logic / Symbios Logic   | 2        | 3.13%   |
| SK hynix                    | 1        | 1.56%   |
| Silicon Motion              | 1        | 1.56%   |
| Red Hat                     | 1        | 1.56%   |
| Micron/Crucial Technology   | 1        | 1.56%   |
| Marvell Technology Group    | 1        | 1.56%   |
| Broadcom / LSI              | 1        | 1.56%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 9        | 11.39%  |
| Intel SATA Controller [RAID mode]                                                       | 7        | 8.86%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4        | 5.06%   |
| AMD 400 Series Chipset SATA Controller                                                  | 4        | 5.06%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 3        | 3.8%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 3        | 3.8%    |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 2        | 2.53%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2        | 2.53%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 2        | 2.53%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 2        | 2.53%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 2        | 2.53%   |
| AMD 500 Series Chipset SATA Controller                                                  | 2        | 2.53%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 1        | 1.27%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 1        | 1.27%   |
| SanDisk WD Blue SN570 NVMe SSD 2TB                                                      | 1        | 1.27%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD                 | 1        | 1.27%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 1        | 1.27%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 1        | 1.27%   |
| Red Hat Virtio 1.0 SCSI                                                                 | 1        | 1.27%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                                    | 1        | 1.27%   |
| Marvell Group 88SE9123 PCIe SATA 6.0 Gb/s controller                                    | 1        | 1.27%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                 | 1        | 1.27%   |
| LSI Logic / Symbios Logic MegaRAID SAS 2108 [Liberator]                                 | 1        | 1.27%   |
| Kingston Company NV1 NVMe SSD SM2263XT (DRAM-less)                                      | 1        | 1.27%   |
| Kingston Company NV1 NVMe SSD E13T (DRAM-less)                                          | 1        | 1.27%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD E18                                      | 1        | 1.27%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                                | 1        | 1.27%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation                   | 1        | 1.27%   |
| Intel Raptor Lake SATA AHCI Controller                                                  | 1        | 1.27%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1        | 1.27%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 1        | 1.27%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 1        | 1.27%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 1        | 1.27%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1        | 1.27%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 1        | 1.27%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 1        | 1.27%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 1        | 1.27%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1        | 1.27%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 1.27%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 1.27%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 30       | 44.78%  |
| NVMe | 19       | 28.36%  |
| RAID | 9        | 13.43%  |
| SAS  | 4        | 5.97%   |
| IDE  | 4        | 5.97%   |
| SCSI | 1        | 1.49%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 22       | 59.46%  |
| AMD    | 15       | 40.54%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| AMD Ryzen 9 3900X 12-Core Processor             | 2        | 5.41%   |
| Intel Xeon W-2223 CPU @ 3.60GHz                 | 1        | 2.7%    |
| Intel Xeon W-1350 @ 3.30GHz                     | 1        | 2.7%    |
| Intel Xeon E-2144G CPU @ 3.60GHz                | 1        | 2.7%    |
| Intel Xeon CPU X5550 @ 2.67GHz                  | 1        | 2.7%    |
| Intel Xeon CPU E5540 @ 2.53GHz                  | 1        | 2.7%    |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz              | 1        | 2.7%    |
| Intel Xeon CPU E5-2683 v4 @ 2.10GHz             | 1        | 2.7%    |
| Intel Xeon CPU E5-2667 v2 @ 3.30GHz             | 1        | 2.7%    |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz             | 1        | 2.7%    |
| Intel Core i7-7700 CPU @ 3.60GHz                | 1        | 2.7%    |
| Intel Core i7-3770 CPU @ 3.40GHz                | 1        | 2.7%    |
| Intel Core i7-14700K                            | 1        | 2.7%    |
| Intel Core i7 CPU X 980 @ 3.33GHz               | 1        | 2.7%    |
| Intel Core i7 CPU 870 @ 2.93GHz                 | 1        | 2.7%    |
| Intel Core i5-6500 CPU @ 3.20GHz                | 1        | 2.7%    |
| Intel Core i5-4440 CPU @ 3.10GHz                | 1        | 2.7%    |
| Intel Core i5-10400F CPU @ 2.90GHz              | 1        | 2.7%    |
| Intel Core i3-4130 CPU @ 3.40GHz                | 1        | 2.7%    |
| Intel Core i3-2130 CPU @ 3.40GHz                | 1        | 2.7%    |
| Intel Atom CPU D2550 @ 1.86GHz                  | 1        | 2.7%    |
| Intel 11th Gen Core i7-11700K @ 3.60GHz         | 1        | 2.7%    |
| Intel 11th Gen Core i5-11400 @ 2.60GHz          | 1        | 2.7%    |
| AMD Ryzen Threadripper PRO 3975WX 32-Cores      | 1        | 2.7%    |
| AMD Ryzen Threadripper 1920X 12-Core Processor  | 1        | 2.7%    |
| AMD Ryzen 9 5950X 16-Core Processor             | 1        | 2.7%    |
| AMD Ryzen 9 3950X 16-Core Processor             | 1        | 2.7%    |
| AMD Ryzen 7 5800X3D 8-Core Processor            | 1        | 2.7%    |
| AMD Ryzen 5 5600G with Radeon Graphics          | 1        | 2.7%    |
| AMD Ryzen 5 3600 6-Core Processor               | 1        | 2.7%    |
| AMD Ryzen 5 3500X 6-Core Processor              | 1        | 2.7%    |
| AMD Ryzen 3 5300G with Radeon Graphics          | 1        | 2.7%    |
| AMD FX-8350 Eight-Core Processor                | 1        | 2.7%    |
| AMD EPYC-Rome Processor                         | 1        | 2.7%    |
| AMD E2-3800 APU with Radeon HD Graphics         | 1        | 2.7%    |
| AMD A10-7850K Radeon R7, 12 Compute Cores 4C+8G | 1        | 2.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Xeon             | 9        | 24.32%  |
| Intel Core i7          | 5        | 13.51%  |
| AMD Ryzen 9            | 4        | 10.81%  |
| Intel Core i5          | 3        | 8.11%   |
| AMD Ryzen 5            | 3        | 8.11%   |
| Other                  | 2        | 5.41%   |
| Intel Core i3          | 2        | 5.41%   |
| AMD Ryzen Threadripper | 2        | 5.41%   |
| Intel Atom             | 1        | 2.7%    |
| AMD Ryzen 7            | 1        | 2.7%    |
| AMD Ryzen 3            | 1        | 2.7%    |
| AMD FX                 | 1        | 2.7%    |
| AMD EPYC               | 1        | 2.7%    |
| AMD E2                 | 1        | 2.7%    |
| AMD A10                | 1        | 2.7%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 13       | 35.14%  |
| 6      | 6        | 16.22%  |
| 16     | 4        | 10.81%  |
| 12     | 4        | 10.81%  |
| 2      | 4        | 10.81%  |
| 32     | 2        | 5.41%   |
| 8      | 2        | 5.41%   |
| 20     | 1        | 2.7%    |
| 1      | 1        | 2.7%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 32       | 86.49%  |
| 2      | 4        | 10.81%  |
| 4      | 1        | 2.7%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 30       | 81.08%  |
| 1      | 7        | 18.92%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 37       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 9        | 23.08%  |
| 0x08701021 | 4        | 10.26%  |
| 0xa0671    | 3        | 7.69%   |
| 0x306e4    | 2        | 5.13%   |
| 0x306c3    | 2        | 5.13%   |
| 0x106a5    | 2        | 5.13%   |
| 0x0a50000d | 2        | 5.13%   |
| 0xa0655    | 1        | 2.56%   |
| 0x906ea    | 1        | 2.56%   |
| 0x906e9    | 1        | 2.56%   |
| 0x506e3    | 1        | 2.56%   |
| 0x50657    | 1        | 2.56%   |
| 0x306a9    | 1        | 2.56%   |
| 0x30661    | 1        | 2.56%   |
| 0x206d7    | 1        | 2.56%   |
| 0x206a7    | 1        | 2.56%   |
| 0x0a20120a | 1        | 2.56%   |
| 0x0a201016 | 1        | 2.56%   |
| 0x0830107a | 1        | 2.56%   |
| 0x08001137 | 1        | 2.56%   |
| 0x06003106 | 1        | 2.56%   |
| 0x06000852 | 1        | 2.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 2            | 7        | 18.92%  |
| Zen 3            | 4        | 10.81%  |
| Nehalem          | 3        | 8.11%   |
| IvyBridge        | 3        | 8.11%   |
| Icelake          | 3        | 8.11%   |
| Skylake          | 2        | 5.41%   |
| SandyBridge      | 2        | 5.41%   |
| KabyLake         | 2        | 5.41%   |
| Haswell          | 2        | 5.41%   |
| Zen              | 1        | 2.7%    |
| Westmere         | 1        | 2.7%    |
| Steamroller      | 1        | 2.7%    |
| Piledriver       | 1        | 2.7%    |
| Jaguar           | 1        | 2.7%    |
| CometLake        | 1        | 2.7%    |
| Broadwell        | 1        | 2.7%    |
| Bonnell          | 1        | 2.7%    |
| Alderlake Hybrid | 1        | 2.7%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 17       | 43.59%  |
| AMD                        | 11       | 28.21%  |
| Intel                      | 8        | 20.51%  |
| Red Hat                    | 1        | 2.56%   |
| Matrox Electronics Systems | 1        | 2.56%   |
| ASPEED Technology          | 1        | 2.56%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Nvidia GA106 [Geforce RTX 3050]                                           | 2        | 5.13%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 2        | 5.13%   |
| Red Hat QXL paravirtual graphic card                                      | 1        | 2.56%   |
| Nvidia TU117GLM [Quadro T400 Mobile]                                      | 1        | 2.56%   |
| Nvidia TU117 [GeForce GTX 1650]                                           | 1        | 2.56%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                     | 1        | 2.56%   |
| Nvidia GP107GL [Quadro P620]                                              | 1        | 2.56%   |
| Nvidia GP106GL [Quadro P2200]                                             | 1        | 2.56%   |
| Nvidia GP104 [GeForce GTX 1080]                                           | 1        | 2.56%   |
| Nvidia GM204GL [Quadro M4000]                                             | 1        | 2.56%   |
| Nvidia GM204 [GeForce GTX 970]                                            | 1        | 2.56%   |
| Nvidia GM107GL [Quadro K2200]                                             | 1        | 2.56%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                         | 1        | 2.56%   |
| Nvidia GK208B [GeForce GT 730]                                            | 1        | 2.56%   |
| Nvidia GK104 [GeForce GTX 770]                                            | 1        | 2.56%   |
| Nvidia GF119 [GeForce GT 610]                                             | 1        | 2.56%   |
| Nvidia GF108GL [Quadro 600]                                               | 1        | 2.56%   |
| Nvidia AD102 [GeForce RTX 4090]                                           | 1        | 2.56%   |
| Matrox Electronics Systems MGA G200eW WPCM450                             | 1        | 2.56%   |
| Intel RocketLake-S GT1 [UHD Graphics P750]                                | 1        | 2.56%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                 | 1        | 2.56%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                | 1        | 2.56%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                    | 1        | 2.56%   |
| Intel HD Graphics 530                                                     | 1        | 2.56%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller           | 1        | 2.56%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller | 1        | 2.56%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 1        | 2.56%   |
| ASPEED Technology ASPEED Graphics Family                                  | 1        | 2.56%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                  | 1        | 2.56%   |
| AMD RS780L [Radeon 3000]                                                  | 1        | 2.56%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                            | 1        | 2.56%   |
| AMD Kaveri [Radeon R7 Graphics]                                           | 1        | 2.56%   |
| AMD Kabini [Radeon HD 8280 / R3 Series]                                   | 1        | 2.56%   |
| AMD Juniper XT [Radeon HD 5770]                                           | 1        | 2.56%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                   | 1        | 2.56%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                          | 1        | 2.56%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]       | 1        | 2.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x Nvidia   | 14       | 37.84%  |
| 1 x AMD      | 10       | 27.03%  |
| 1 x Intel    | 8        | 21.62%  |
| 2 x Nvidia   | 1        | 2.7%    |
| 1 x Red Hat  | 1        | 2.7%    |
| 1 x Matrox   | 1        | 2.7%    |
| 1 x ASPEED   | 1        | 2.7%    |
| AMD + Nvidia | 1        | 2.7%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 22       | 57.89%  |
| Proprietary | 9        | 23.68%  |
| Unknown     | 7        | 18.42%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 16       | 42.11%  |
| 7.01-8.0   | 4        | 10.53%  |
| 1.01-2.0   | 4        | 10.53%  |
| 0.51-1.0   | 4        | 10.53%  |
| 0.01-0.5   | 4        | 10.53%  |
| 3.01-4.0   | 3        | 7.89%   |
| 5.01-6.0   | 1        | 2.63%   |
| 4.01-5.0   | 1        | 2.63%   |
| 16.01-24.0 | 1        | 2.63%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Dell                | 7        | 21.21%  |
| Eizo                | 4        | 12.12%  |
| Samsung Electronics | 3        | 9.09%   |
| Philips             | 3        | 9.09%   |
| BenQ                | 3        | 9.09%   |
| ViewSonic           | 2        | 6.06%   |
| Lenovo              | 2        | 6.06%   |
| Goldstar            | 2        | 6.06%   |
| Acer                | 2        | 6.06%   |
| TopView             | 1        | 3.03%   |
| STD                 | 1        | 3.03%   |
| Medion              | 1        | 3.03%   |
| ASUSTek Computer    | 1        | 3.03%   |
| AOC                 | 1        | 3.03%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| ViewSonic VX2233wm-1 VSC1D22 1920x1080 477x268mm 21.5-inch           | 1        | 2.78%   |
| ViewSonic VA2232 Series VSC8224 1680x1050 474x296mm 22.0-inch        | 1        | 2.78%   |
| TopView HD TV TOPC37E 1920x1080 700x390mm 31.5-inch                  | 1        | 2.78%   |
| STD HDMI TV STD00C7 1680x1050 698x392mm 31.5-inch                    | 1        | 2.78%   |
| Samsung Electronics SyncMaster SAM021B 1400x1050 408x300mm 19.9-inch | 1        | 2.78%   |
| Samsung Electronics S27H65x SAM0E1D 1920x1080 598x336mm 27.0-inch    | 1        | 2.78%   |
| Samsung Electronics LCD Monitor S32B80P 5760x2160                    | 1        | 2.78%   |
| Samsung Electronics LCD Monitor S32B80P                              | 1        | 2.78%   |
| Samsung Electronics F27G3xTF SAM710D 1920x1080 600x330mm 27.0-inch   | 1        | 2.78%   |
| Philips PHL 272B7QU PHL0926 2560x1440 597x336mm 27.0-inch            | 1        | 2.78%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch              | 1        | 2.78%   |
| Philips 19B PHL0879 1280x1024 376x301mm 19.0-inch                    | 1        | 2.78%   |
| Medion MD7212AS MED4971 1280x1024 359x287mm 18.1-inch                | 1        | 2.78%   |
| Lenovo LEN L171 LEN240B 1280x1024 340x270mm 17.1-inch                | 1        | 2.78%   |
| Lenovo L24q-10 LEN65CF 2560x1440 527x296mm 23.8-inch                 | 1        | 2.78%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch             | 1        | 2.78%   |
| Goldstar 22EA53 GSM59A6 1920x1080 477x268mm 21.5-inch                | 1        | 2.78%   |
| Eizo RX220 ENC2146 1600x1200 440x330mm 21.7-inch                     | 1        | 2.78%   |
| Eizo RP3225-004 ENC3225 3840x2160 700x390mm 31.5-inch                | 1        | 2.78%   |
| Eizo LCD Monitor CG247 5760x2160                                     | 1        | 2.78%   |
| Eizo LCD Monitor CG247 1920x1200                                     | 1        | 2.78%   |
| Eizo EV2336W ENC2390 1920x1080 510x287mm 23.0-inch                   | 1        | 2.78%   |
| Dell UP3017 DEL40FA 2560x1600 640x400mm 29.7-inch                    | 1        | 2.78%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 1        | 2.78%   |
| Dell P2417H DELA0DB 1920x1080 530x300mm 24.0-inch                    | 1        | 2.78%   |
| Dell LCD Monitor U2515H 2560x1440                                    | 1        | 2.78%   |
| Dell G2722HS DEL427D 1920x1080 597x336mm 27.0-inch                   | 1        | 2.78%   |
| Dell E190S DELA04B 1280x1024 376x301mm 19.0-inch                     | 1        | 2.78%   |
| Dell 1905FP DEL400C 1280x1024 376x301mm 19.0-inch                    | 1        | 2.78%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                    | 1        | 2.78%   |
| BenQ G700 BNQ7802 1280x1024 338x270mm 17.0-inch                      | 1        | 2.78%   |
| BenQ BL2405 BNQ8016 1920x1080 531x298mm 24.0-inch                    | 1        | 2.78%   |
| ASUSTek Computer VL278 AUS27C2 1920x1080 600x340mm 27.2-inch         | 1        | 2.78%   |
| AOC 2330V AOC2330 1920x1080 476x268mm 21.5-inch                      | 1        | 2.78%   |
| Acer K222HQL ACR03E1 1920x1080 480x270mm 21.7-inch                   | 1        | 2.78%   |
| Acer EK271 E ACR0B62 1920x1080 597x336mm 27.0-inch                   | 1        | 2.78%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 16       | 45.71%  |
| 1280x1024 (SXGA)   | 6        | 17.14%  |
| 2560x1440 (QHD)    | 3        | 8.57%   |
| 1920x1200 (WUXGA)  | 2        | 5.71%   |
| 5760x2160          | 1        | 2.86%   |
| 3840x2160 (4K)     | 1        | 2.86%   |
| 2560x1600          | 1        | 2.86%   |
| 2560x1080          | 1        | 2.86%   |
| 1680x1050 (WSXGA+) | 1        | 2.86%   |
| 1600x1200          | 1        | 2.86%   |
| 1400x1050          | 1        | 2.86%   |
| Unknown            | 1        | 2.86%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 6        | 17.65%  |
| 24      | 5        | 14.71%  |
| 21      | 5        | 14.71%  |
| 31      | 3        | 8.82%   |
| 19      | 3        | 8.82%   |
| Unknown | 3        | 8.82%   |
| 23      | 2        | 5.88%   |
| 17      | 2        | 5.88%   |
| 34      | 1        | 2.94%   |
| 29      | 1        | 2.94%   |
| 22      | 1        | 2.94%   |
| 20      | 1        | 2.94%   |
| 18      | 1        | 2.94%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 13       | 38.24%  |
| 401-500     | 7        | 20.59%  |
| 601-700     | 4        | 11.76%  |
| 351-400     | 4        | 11.76%  |
| Unknown     | 3        | 8.82%   |
| 301-350     | 2        | 5.88%   |
| 701-800     | 1        | 2.94%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 19       | 55.88%  |
| 5/4     | 5        | 14.71%  |
| 16/10   | 3        | 8.82%   |
| Unknown | 3        | 8.82%   |
| 4/3     | 2        | 5.88%   |
| 6/5     | 1        | 2.94%   |
| 21/9    | 1        | 2.94%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 11       | 32.35%  |
| 301-350        | 6        | 17.65%  |
| 151-200        | 6        | 17.65%  |
| 351-500        | 5        | 14.71%  |
| Unknown        | 3        | 8.82%   |
| 141-150        | 2        | 5.88%   |
| 251-300        | 1        | 2.94%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 21       | 65.63%  |
| 101-120 | 6        | 18.75%  |
| Unknown | 3        | 9.38%   |
| 121-160 | 2        | 6.25%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 25       | 65.79%  |
| 2     | 7        | 18.42%  |
| 0     | 6        | 15.79%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 20       | 41.67%  |
| Realtek Semiconductor    | 16       | 33.33%  |
| TP-Link                  | 2        | 4.17%   |
| Qualcomm Atheros         | 2        | 4.17%   |
| Broadcom                 | 2        | 4.17%   |
| Ralink Technology        | 1        | 2.08%   |
| Ralink                   | 1        | 2.08%   |
| Marvell Technology Group | 1        | 2.08%   |
| Emulex                   | 1        | 2.08%   |
| Broadcom Limited         | 1        | 2.08%   |
| 3Com                     | 1        | 2.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 13       | 20%     |
| Intel Wi-Fi 6 AX200                                                    | 3        | 4.62%   |
| Intel I211 Gigabit Network Connection                                  | 3        | 4.62%   |
| Intel Ethernet Controller X550                                         | 3        | 4.62%   |
| Intel Ethernet Controller I225-V                                       | 3        | 4.62%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 2        | 3.08%   |
| Realtek RTL8125 2.5GbE Controller                                      | 2        | 3.08%   |
| Intel I350 Gigabit Network Connection                                  | 2        | 3.08%   |
| Intel I210 Gigabit Network Connection                                  | 2        | 3.08%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2        | 3.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2        | 3.08%   |
| Intel 82574L Gigabit Network Connection                                | 2        | 3.08%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 2        | 3.08%   |
| TP-Link Archer T4U ver.3                                               | 1        | 1.54%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                 | 1        | 1.54%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 1        | 1.54%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                    | 1        | 1.54%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 1        | 1.54%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1        | 1.54%   |
| Ralink MT7601U Wireless Adapter                                        | 1        | 1.54%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                              | 1        | 1.54%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1        | 1.54%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                       | 1        | 1.54%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 1        | 1.54%   |
| Intel Wireless 8265 / 8275                                             | 1        | 1.54%   |
| Intel Wireless 8260                                                    | 1        | 1.54%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                      | 1        | 1.54%   |
| Intel Ethernet Connection I219-LM                                      | 1        | 1.54%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1        | 1.54%   |
| Intel Ethernet Connection (5) I219-V                                   | 1        | 1.54%   |
| Intel Ethernet Connection (14) I219-LM                                 | 1        | 1.54%   |
| Intel 82579V Gigabit Network Connection                                | 1        | 1.54%   |
| Intel 82578DM Gigabit Network Connection                               | 1        | 1.54%   |
| Intel 82576 Gigabit Network Connection                                 | 1        | 1.54%   |
| Emulex OneConnect 10Gb NIC (be3)                                       | 1        | 1.54%   |
| Broadcom Limited NetXtreme II BCM5709 Gigabit Ethernet                 | 1        | 1.54%   |
| 3Com 3c905C-TX/TX-M [Tornado]                                          | 1        | 1.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 6        | 46.15%  |
| TP-Link               | 2        | 15.38%  |
| Realtek Semiconductor | 2        | 15.38%  |
| Ralink Technology     | 1        | 7.69%   |
| Ralink                | 1        | 7.69%   |
| Qualcomm Atheros      | 1        | 7.69%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                      | 3        | 23.08%  |
| TP-Link Archer T4U ver.3                                 | 1        | 7.69%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                   | 1        | 7.69%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter | 1        | 7.69%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter      | 1        | 7.69%   |
| Ralink MT7601U Wireless Adapter                          | 1        | 7.69%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                | 1        | 7.69%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter         | 1        | 7.69%   |
| Intel Wireless 8265 / 8275                               | 1        | 7.69%   |
| Intel Wireless 8260                                      | 1        | 7.69%   |
| Intel Raptor Lake-S PCH CNVi WiFi                        | 1        | 7.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 20       | 46.51%  |
| Realtek Semiconductor    | 16       | 37.21%  |
| Broadcom                 | 2        | 4.65%   |
| Qualcomm Atheros         | 1        | 2.33%   |
| Marvell Technology Group | 1        | 2.33%   |
| Emulex                   | 1        | 2.33%   |
| Broadcom Limited         | 1        | 2.33%   |
| 3Com                     | 1        | 2.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 13       | 25%     |
| Intel I211 Gigabit Network Connection                                  | 3        | 5.77%   |
| Intel Ethernet Controller X550                                         | 3        | 5.77%   |
| Intel Ethernet Controller I225-V                                       | 3        | 5.77%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 2        | 3.85%   |
| Realtek RTL8125 2.5GbE Controller                                      | 2        | 3.85%   |
| Intel I350 Gigabit Network Connection                                  | 2        | 3.85%   |
| Intel I210 Gigabit Network Connection                                  | 2        | 3.85%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2        | 3.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2        | 3.85%   |
| Intel 82574L Gigabit Network Connection                                | 2        | 3.85%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 2        | 3.85%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 1        | 1.92%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1        | 1.92%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1        | 1.92%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 1        | 1.92%   |
| Intel Ethernet Connection I219-LM                                      | 1        | 1.92%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1        | 1.92%   |
| Intel Ethernet Connection (5) I219-V                                   | 1        | 1.92%   |
| Intel Ethernet Connection (14) I219-LM                                 | 1        | 1.92%   |
| Intel 82579V Gigabit Network Connection                                | 1        | 1.92%   |
| Intel 82578DM Gigabit Network Connection                               | 1        | 1.92%   |
| Intel 82576 Gigabit Network Connection                                 | 1        | 1.92%   |
| Emulex OneConnect 10Gb NIC (be3)                                       | 1        | 1.92%   |
| Broadcom Limited NetXtreme II BCM5709 Gigabit Ethernet                 | 1        | 1.92%   |
| 3Com 3c905C-TX/TX-M [Tornado]                                          | 1        | 1.92%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 37       | 74%     |
| WiFi     | 13       | 26%     |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 29       | 82.86%  |
| WiFi     | 6        | 17.14%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 2     | 16       | 43.24%  |
| 1     | 12       | 32.43%  |
| 3     | 4        | 10.81%  |
| 4     | 3        | 8.11%   |
| 5     | 1        | 2.7%    |
| 0     | 1        | 2.7%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 28       | 73.68%  |
| Yes  | 10       | 26.32%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 6        | 54.55%  |
| Broadcom                | 2        | 18.18%  |
| Realtek Semiconductor   | 1        | 9.09%   |
| Cambridge Silicon Radio | 1        | 9.09%   |
| ASUSTek Computer        | 1        | 9.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                               | 3        | 27.27%  |
| Intel Bluetooth Device                              | 2        | 18.18%  |
| Realtek Bluetooth Radio                             | 1        | 9.09%   |
| Intel AX211 Bluetooth                               | 1        | 9.09%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1        | 9.09%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 9.09%   |
| Broadcom BCM2045 Bluetooth                          | 1        | 9.09%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 9.09%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 21       | 32.81%  |
| Nvidia                   | 17       | 26.56%  |
| AMD                      | 17       | 26.56%  |
| Micro Star International | 2        | 3.13%   |
| Plantronics              | 1        | 1.56%   |
| JMTek                    | 1        | 1.56%   |
| Giga-Byte Technology     | 1        | 1.56%   |
| Creative Technology      | 1        | 1.56%   |
| Conexant Systems         | 1        | 1.56%   |
| ASUSTek Computer         | 1        | 1.56%   |
| Apple                    | 1        | 1.56%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 8        | 11.11%  |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 3        | 4.17%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2        | 2.78%   |
| Nvidia GM204 High Definition Audio Controller                              | 2        | 2.78%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2        | 2.78%   |
| Nvidia GF108 High Definition Audio Controller                              | 2        | 2.78%   |
| Nvidia GA106 High Definition Audio Controller                              | 2        | 2.78%   |
| Micro Star International USB Audio                                         | 2        | 2.78%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2        | 2.78%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 2        | 2.78%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2        | 2.78%   |
| Intel 200 Series PCH HD Audio                                              | 2        | 2.78%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2        | 2.78%   |
| AMD FCH Azalia Controller                                                  | 2        | 2.78%   |
| AMD Family 17h/19h HD Audio Controller                                     | 2        | 2.78%   |
| Plantronics Blackwire 320                                                  | 1        | 1.39%   |
| Nvidia TU116 High Definition Audio Controller                              | 1        | 1.39%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 1.39%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 1.39%   |
| Nvidia GP104 High Definition Audio Controller                              | 1        | 1.39%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 1.39%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1        | 1.39%   |
| Nvidia AD102 High Definition Audio Controller                              | 1        | 1.39%   |
| JMTek USB PnP Audio Device                                                 | 1        | 1.39%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1        | 1.39%   |
| Intel Raptor Lake High Definition Audio Controller                         | 1        | 1.39%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1        | 1.39%   |
| Intel Comet Lake PCH-V cAVS                                                | 1        | 1.39%   |
| Intel Cannon Lake PCH cAVS                                                 | 1        | 1.39%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 1        | 1.39%   |
| Intel Alder Lake-S HD Audio Controller                                     | 1        | 1.39%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1        | 1.39%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1        | 1.39%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1        | 1.39%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1        | 1.39%   |
| Giga-Byte Technology USB Audio                                             | 1        | 1.39%   |
| Creative Technology Stage Air V2                                           | 1        | 1.39%   |
| Conexant Systems G941                                                      | 1        | 1.39%   |
| ASUSTek Computer USB Audio                                                 | 1        | 1.39%   |
| Apple USB-C to 3.5mm Headphone Jack Adapter                                | 1        | 1.39%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 5        | 18.52%  |
| Samsung Electronics | 4        | 14.81%  |
| Micron Technology   | 3        | 11.11%  |
| G.Skill             | 3        | 11.11%  |
| Unknown             | 2        | 7.41%   |
| SK hynix            | 2        | 7.41%   |
| Crucial             | 2        | 7.41%   |
| Corsair             | 2        | 7.41%   |
| Unknown             | 2        | 7.41%   |
| QEMU                | 1        | 3.7%    |
| GeIL                | 1        | 3.7%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s   | 2        | 6.9%    |
| Unknown                                                 | 2        | 6.9%    |
| Unknown RAM Module 8GB DIMM 1600MT/s                    | 1        | 3.45%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                    | 1        | 3.45%   |
| SK hynix RAM HMT351U6AFR8C-H9 4GB DIMM DDR3 1333MT/s    | 1        | 3.45%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s    | 1        | 3.45%   |
| Samsung RAM Module 16GB DIMM DDR4 2667MT/s              | 1        | 3.45%   |
| Samsung RAM M393A1K43DB1-CVF 8GB DIMM DDR4 2933MT/s     | 1        | 3.45%   |
| Samsung RAM M378A5244CB0-CRC 4GB DIMM DDR4 3066MT/s     | 1        | 3.45%   |
| Samsung RAM M378A4G43MB1-CTD 32GB DIMM DDR4 3466MT/s    | 1        | 3.45%   |
| QEMU RAM Module 8GB DIMM RAM                            | 1        | 3.45%   |
| Micron RAM 9ASF2G72AZ-3G2B1 16GB DIMM DDR4 3200MT/s     | 1        | 3.45%   |
| Micron RAM 8KTF25664HZ-1G6M 2GB SODIMM DDR3 1066MT/s    | 1        | 3.45%   |
| Micron RAM 8JSF25664HZ-1G4D 2GB SODIMM DDR3 1066MT/s    | 1        | 3.45%   |
| Micron RAM 36KSF2G72PZ-1G6E1 16GB DIMM DDR3 1600MT/s    | 1        | 3.45%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s    | 1        | 3.45%   |
| Kingston RAM ACR256X64D3U1333C9 2GB DIMM DDR3 1333MT/s  | 1        | 3.45%   |
| Kingston RAM 99U5458-005.A01LF 4GB DIMM DDR3 1333MT/s   | 1        | 3.45%   |
| Kingston RAM 9905458-013.A00LF 4GB DIMM DDR3 1333MT/s   | 1        | 3.45%   |
| GeIL RAM CL11-11-11 D3-1600 4GB DIMM 1600MT/s           | 1        | 3.45%   |
| G.Skill RAM F4-4000C15-8GVK 8GB DIMM DDR4 2133MT/s      | 1        | 3.45%   |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s  | 1        | 3.45%   |
| G.Skill RAM F3-12800CL9-4GBXL 4GB DIMM DDR3 1867MT/s    | 1        | 3.45%   |
| Crucial RAM CT8G4DFRA32A.C4FE 8GB DIMM DDR4 3200MT/s    | 1        | 3.45%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s   | 1        | 3.45%   |
| Corsair RAM CMK64GX4M4E3200C16 16GB DIMM DDR4 3200MT/s  | 1        | 3.45%   |
| Corsair RAM CMK128GX4M4E3200C16 32GB DIMM DDR4 3200MT/s | 1        | 3.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 13       | 54.17%  |
| DDR3    | 8        | 33.33%  |
| Unknown | 2        | 8.33%   |
| RAM     | 1        | 4.17%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 23       | 95.83%  |
| SODIMM | 1        | 4.17%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 10       | 38.46%  |
| 16384 | 6        | 23.08%  |
| 4096  | 6        | 23.08%  |
| 32768 | 2        | 7.69%   |
| 2048  | 2        | 7.69%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 7        | 26.92%  |
| 1600    | 5        | 19.23%  |
| 1333    | 2        | 7.69%   |
| 1066    | 2        | 7.69%   |
| 3733    | 1        | 3.85%   |
| 3466    | 1        | 3.85%   |
| 3066    | 1        | 3.85%   |
| 2933    | 1        | 3.85%   |
| 2667    | 1        | 3.85%   |
| 2400    | 1        | 3.85%   |
| 2133    | 1        | 3.85%   |
| 1867    | 1        | 3.85%   |
| 800     | 1        | 3.85%   |
| Unknown | 1        | 3.85%   |

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
| Apple iPhone 5/5C/5S/6/SE/7/8/X     | 1        | 12.5%   |

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
| 0     | 24       | 63.16%  |
| 1     | 10       | 26.32%  |
| 5     | 2        | 5.26%   |
| 3     | 1        | 2.63%   |
| 2     | 1        | 2.63%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 5        | 25%     |
| Sound                    | 3        | 15%     |
| Net/wireless             | 3        | 15%     |
| Net/ethernet             | 2        | 10%     |
| Unassigned class         | 1        | 5%      |
| Storage/raid             | 1        | 5%      |
| Storage/ide              | 1        | 5%      |
| Network                  | 1        | 5%      |
| Firewire controller      | 1        | 5%      |
| Communication controller | 1        | 5%      |
| Bluetooth                | 1        | 5%      |

