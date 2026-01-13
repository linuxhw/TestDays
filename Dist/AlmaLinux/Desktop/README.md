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

Total: 177

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASRock        | Z590 Phantom Gaming-ITX/... | [1421d2f645](https://linux-hardware.org/?probe=1421d2f645) | Dec 30, 2025 |
| ASUSTek       | PRIME Z790-V WIFI           | [305fb21e1d](https://linux-hardware.org/?probe=305fb21e1d) | Dec 18, 2025 |
| Gigabyte      | B450 AORUS ELITE V2         | [fa0623e0eb](https://linux-hardware.org/?probe=fa0623e0eb) | Nov 17, 2025 |
| Mancer        | B450M-DA V1.1               | [b5cf104129](https://linux-hardware.org/?probe=b5cf104129) | Nov 16, 2025 |
| MSI           | B550-A PRO                  | [75d74f1ae6](https://linux-hardware.org/?probe=75d74f1ae6) | Nov 16, 2025 |
| MSI           | B550-A PRO                  | [d942296416](https://linux-hardware.org/?probe=d942296416) | Nov 14, 2025 |
| MSI           | Z77A-GD80                   | [045c98d53b](https://linux-hardware.org/?probe=045c98d53b) | Nov 11, 2025 |
| Supermicro    | X10DRU-i+B                  | [8fae6555b0](https://linux-hardware.org/?probe=8fae6555b0) | Oct 30, 2025 |
| MSI           | H310M PRO-VD                | [5cef1d2379](https://linux-hardware.org/?probe=5cef1d2379) | Oct 21, 2025 |
| Gigabyte      | X570S UD                    | [6b0499293c](https://linux-hardware.org/?probe=6b0499293c) | Sep 23, 2025 |
| Unknown       | Unknown                     | [d24dccbf63](https://linux-hardware.org/?probe=d24dccbf63) | Sep 08, 2025 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [02d5b6d42b](https://linux-hardware.org/?probe=02d5b6d42b) | Sep 06, 2025 |
| ASUSTek       | Pro WS WRX90E-SAGE SE       | [744af99a4e](https://linux-hardware.org/?probe=744af99a4e) | Sep 06, 2025 |
| Gigabyte      | TRX40 AORUS MASTER          | [f5ee8ddbd9](https://linux-hardware.org/?probe=f5ee8ddbd9) | Jul 23, 2025 |
| Gigabyte      | TRX40 AORUS MASTER          | [3a2f253a7c](https://linux-hardware.org/?probe=3a2f253a7c) | Jul 18, 2025 |
| ASUSTek       | PRIME B650M-A AX II         | [49892ac27e](https://linux-hardware.org/?probe=49892ac27e) | Jun 22, 2025 |
| ASUSTek       | PRIME B650M-A AX II         | [927f8d5adc](https://linux-hardware.org/?probe=927f8d5adc) | Jun 01, 2025 |
| Optimized ... | KVM                         | [7a5e8bbb73](https://linux-hardware.org/?probe=7a5e8bbb73) | May 23, 2025 |
| Optimized ... | KVM                         | [ba0da05513](https://linux-hardware.org/?probe=ba0da05513) | May 16, 2025 |
| Gigabyte      | MFLP7IP-00                  | [95c9b5ef7e](https://linux-hardware.org/?probe=95c9b5ef7e) | May 06, 2025 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [fd0f4cc032](https://linux-hardware.org/?probe=fd0f4cc032) | Apr 15, 2025 |
| Gigabyte      | B550M DS3H AC               | [64afda3481](https://linux-hardware.org/?probe=64afda3481) | Apr 04, 2025 |
| MSI           | B450M MORTAR TITANIUM       | [3073ae0e1a](https://linux-hardware.org/?probe=3073ae0e1a) | Mar 21, 2025 |
| MSI           | B450M MORTAR TITANIUM       | [c67c792e5b](https://linux-hardware.org/?probe=c67c792e5b) | Mar 16, 2025 |
| Gigabyte      | B450M DS3H V2               | [515442999b](https://linux-hardware.org/?probe=515442999b) | Feb 22, 2025 |
| Supermicro    | X9DR3-F                     | [ad9c3075c6](https://linux-hardware.org/?probe=ad9c3075c6) | Jan 30, 2025 |
| Lenovo        | Kabini CRB NOK              | [13d31c68c4](https://linux-hardware.org/?probe=13d31c68c4) | Jan 26, 2025 |
| Gigabyte      | B85M-D3H                    | [544dbadbcb](https://linux-hardware.org/?probe=544dbadbcb) | Jan 15, 2025 |
| ASRock        | G31M-S                      | [b4354eea8e](https://linux-hardware.org/?probe=b4354eea8e) | Jan 15, 2025 |
| Supermicro    | H13SSWA                     | [b9b242c650](https://linux-hardware.org/?probe=b9b242c650) | Jan 10, 2025 |
| Pelco by S... | DS-SRV2 S584XF01            | [7ed2a57a58](https://linux-hardware.org/?probe=7ed2a57a58) | Jan 03, 2025 |
| Dell          | 0JP3NX A01                  | [8675954a59](https://linux-hardware.org/?probe=8675954a59) | Dec 20, 2024 |
| MSI           | A320M-A PRO MAX             | [f160b8eebe](https://linux-hardware.org/?probe=f160b8eebe) | Dec 16, 2024 |
| ASUSTek       | PRIME B360M-D               | [5bdb93a154](https://linux-hardware.org/?probe=5bdb93a154) | Dec 02, 2024 |
| Optimized ... | KVM                         | [672aaf8ea5](https://linux-hardware.org/?probe=672aaf8ea5) | Nov 22, 2024 |
| Medion        | MS-7616                     | [0c544180a0](https://linux-hardware.org/?probe=0c544180a0) | Oct 23, 2024 |
| MACHINIST     | X99-MR9A PRO MAX V5.1       | [d7e2cffa85](https://linux-hardware.org/?probe=d7e2cffa85) | Oct 19, 2024 |
| Dell          | 0K2NWM A00                  | [465d3bfbda](https://linux-hardware.org/?probe=465d3bfbda) | Oct 17, 2024 |
| MSI           | Boston                      | [8e086f2e70](https://linux-hardware.org/?probe=8e086f2e70) | Oct 02, 2024 |
| Dell          | 0HD5W2 A01                  | [e21b766bf5](https://linux-hardware.org/?probe=e21b766bf5) | Sep 27, 2024 |
| HP            | 0AA0h                       | [056856286b](https://linux-hardware.org/?probe=056856286b) | Sep 26, 2024 |
| Dell          | 042P49 A02                  | [9f6b43e99e](https://linux-hardware.org/?probe=9f6b43e99e) | Sep 13, 2024 |
| HP            | 1791                        | [1bd7f12e61](https://linux-hardware.org/?probe=1bd7f12e61) | Sep 05, 2024 |
| HP            | 1589                        | [a21e698c3c](https://linux-hardware.org/?probe=a21e698c3c) | Sep 05, 2024 |
| Dell          | 0JP3NX A01                  | [0353987388](https://linux-hardware.org/?probe=0353987388) | Aug 31, 2024 |
| Supermicro    | H13DSG-O-CPU                | [08fd89ae34](https://linux-hardware.org/?probe=08fd89ae34) | Aug 22, 2024 |
| Supermicro    | H13DSG-O-CPU                | [069e34f016](https://linux-hardware.org/?probe=069e34f016) | Aug 20, 2024 |
| Techvision    | TVI7309X B0                 | [5685155a60](https://linux-hardware.org/?probe=5685155a60) | Aug 16, 2024 |
| Techvision    | TVI7309X B0                 | [9285a26f03](https://linux-hardware.org/?probe=9285a26f03) | Aug 15, 2024 |
| Gigabyte      | GA-880GM-USB3L              | [a0a2b265e5](https://linux-hardware.org/?probe=a0a2b265e5) | Aug 06, 2024 |
| MSI           | H110M PRO-VD PLUS           | [3bf15e63ac](https://linux-hardware.org/?probe=3bf15e63ac) | Jun 21, 2024 |
| MSI           | Boston                      | [4b244032d0](https://linux-hardware.org/?probe=4b244032d0) | Jun 19, 2024 |
| MSI           | Boston                      | [5252f63696](https://linux-hardware.org/?probe=5252f63696) | Jun 19, 2024 |
| ASRock        | Z790 PG SONIC               | [b5098f47bc](https://linux-hardware.org/?probe=b5098f47bc) | Jun 09, 2024 |
| Gigabyte      | H97-Gaming 3                | [98633fa042](https://linux-hardware.org/?probe=98633fa042) | Jun 08, 2024 |
| Intel         | DH77EB AAG39073-304         | [78e8b0e68e](https://linux-hardware.org/?probe=78e8b0e68e) | Jun 07, 2024 |
| Lenovo        | Kabini CRB NOK              | [f1053f6b0e](https://linux-hardware.org/?probe=f1053f6b0e) | Jun 05, 2024 |
| Lenovo        | Kabini CRB NOK              | [f5c76261aa](https://linux-hardware.org/?probe=f5c76261aa) | May 12, 2024 |
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


| Name           | Desktops | Percent |
|----------------|----------|---------|
| AlmaLinux 8.10 | 12       | 13.79%  |
| AlmaLinux 9.4  | 9        | 10.34%  |
| AlmaLinux 9.6  | 8        | 9.2%    |
| AlmaLinux 9.5  | 8        | 9.2%    |
| AlmaLinux 9.1  | 8        | 9.2%    |
| AlmaLinux 9.2  | 6        | 6.9%    |
| AlmaLinux 10.0 | 6        | 6.9%    |
| AlmaLinux 9.3  | 5        | 5.75%   |
| AlmaLinux 8.9  | 5        | 5.75%   |
| AlmaLinux 8.8  | 5        | 5.75%   |
| AlmaLinux 8.7  | 5        | 5.75%   |
| AlmaLinux 9.0  | 3        | 3.45%   |
| AlmaLinux 8.6  | 2        | 2.3%    |
| AlmaLinux 8.5  | 1        | 1.15%   |
| AlmaLinux 8.4  | 1        | 1.15%   |
| AlmaLinux 8.3  | 1        | 1.15%   |
| AlmaLinux 10.1 | 1        | 1.15%   |
| AlmaLinux 10   | 1        | 1.15%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| AlmaLinux | 80       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Desktops | Percent |
|---------------------------------|----------|---------|
| 4.18.0-553.16.1.el8_10.x86_64   | 6        | 6.67%   |
| 4.18.0-425.3.1.el8.x86_64       | 5        | 5.56%   |
| 5.14.0-427.28.1.el9_4.x86_64    | 3        | 3.33%   |
| 5.14.0-362.8.1.el9_3.x86_64     | 3        | 3.33%   |
| 5.14.0-284.30.1.el9_2.x86_64    | 3        | 3.33%   |
| 5.14.0-162.12.1.el9_1.x86_64    | 3        | 3.33%   |
| 6.12.0-55.43.1.el10_0.x86_64    | 2        | 2.22%   |
| 5.14.0-70.30.1.el9_0.x86_64     | 2        | 2.22%   |
| 5.14.0-503.16.1.el9_5.x86_64    | 2        | 2.22%   |
| 5.14.0-427.33.1.el9_4.x86_64    | 2        | 2.22%   |
| 5.14.0-284.18.1.el9_2.x86_64    | 2        | 2.22%   |
| 5.14.0-162.6.1.el9_1.x86_64     | 2        | 2.22%   |
| 4.18.0-553.5.1.el8_10.x86_64    | 2        | 2.22%   |
| 4.18.0-553.22.1.el8_10.x86_64   | 2        | 2.22%   |
| 4.18.0-477.27.2.el8_8.x86_64    | 2        | 2.22%   |
| 4.18.0-477.21.1.el8_8.x86_64    | 2        | 2.22%   |
| 6.9.3-1.el9.elrepo.x86_64       | 1        | 1.11%   |
| 6.9.1-1.el8.elrepo.x86_64       | 1        | 1.11%   |
| 6.8.7-1.el8.elrepo.x86_64       | 1        | 1.11%   |
| 6.15.9-1.el9.elrepo.x86_64      | 1        | 1.11%   |
| 6.15.3-1.el9.elrepo.x86_64      | 1        | 1.11%   |
| 6.13.3-1.el9.x86_64             | 1        | 1.11%   |
| 6.12.11-1.el9.elrepo.x86_64     | 1        | 1.11%   |
| 6.12.0-55.9.1.el10_0.x86_64     | 1        | 1.11%   |
| 6.12.0-55.40.1.el10_0.x86_64_v2 | 1        | 1.11%   |
| 6.12.0-55.39.1.el10_0.x86_64    | 1        | 1.11%   |
| 6.12.0-174.el10.x86_64_v2       | 1        | 1.11%   |
| 6.12.0-124.20.1.el10_1.x86_64   | 1        | 1.11%   |
| 6.11.0-0.rc5.23.el10.x86_64     | 1        | 1.11%   |
| 6.1.24-1kx.el9.x86_64           | 1        | 1.11%   |
| 5.4.274-1.el8.elrepo.x86_64     | 1        | 1.11%   |
| 5.14.0-70.22.1.el9_0.x86_64     | 1        | 1.11%   |
| 5.14.0-570.62.1.el9_6.x86_64    | 1        | 1.11%   |
| 5.14.0-570.51.1.el9_6.x86_64    | 1        | 1.11%   |
| 5.14.0-570.37.1.el9_6.x86_64    | 1        | 1.11%   |
| 5.14.0-570.22.1.el9_6.x86_64    | 1        | 1.11%   |
| 5.14.0-570.12.1.el9_6.x86_64    | 1        | 1.11%   |
| 5.14.0-503.38.1.el9_5.x86_64    | 1        | 1.11%   |
| 5.14.0-503.35.1.el9_5.x86_64    | 1        | 1.11%   |
| 5.14.0-503.34.1.el9_5.x86_64    | 1        | 1.11%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.14.0  | 41       | 49.4%   |
| 4.18.0  | 25       | 30.12%  |
| 6.12.0  | 7        | 8.43%   |
| 6.9.3   | 1        | 1.2%    |
| 6.9.1   | 1        | 1.2%    |
| 6.8.7   | 1        | 1.2%    |
| 6.15.9  | 1        | 1.2%    |
| 6.15.3  | 1        | 1.2%    |
| 6.13.3  | 1        | 1.2%    |
| 6.12.11 | 1        | 1.2%    |
| 6.11.0  | 1        | 1.2%    |
| 6.1.24  | 1        | 1.2%    |
| 5.4.274 | 1        | 1.2%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.14    | 41       | 49.4%   |
| 4.18    | 25       | 30.12%  |
| 6.12    | 8        | 9.64%   |
| 6.9     | 2        | 2.41%   |
| 6.15    | 2        | 2.41%   |
| 6.8     | 1        | 1.2%    |
| 6.13    | 1        | 1.2%    |
| 6.11    | 1        | 1.2%    |
| 6.1     | 1        | 1.2%    |
| 5.4     | 1        | 1.2%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 80       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 51       | 62.96%  |
| Unknown       | 14       | 17.28%  |
| KDE5          | 8        | 9.88%   |
| MATE          | 3        | 3.7%    |
| GNOME Classic | 2        | 2.47%   |
| XFCE          | 1        | 1.23%   |
| X-Cinnamon    | 1        | 1.23%   |
| KDE6          | 1        | 1.23%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 39       | 47.56%  |
| X11     | 31       | 37.8%   |
| Tty     | 6        | 7.32%   |
| Unknown | 6        | 7.32%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 52       | 64.2%   |
| GDM     | 23       | 28.4%   |
| SDDM    | 5        | 6.17%   |
| LightDM | 1        | 1.23%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 37       | 45.68%  |
| C       | 7        | 8.64%   |
| de_DE   | 5        | 6.17%   |
| pt_BR   | 4        | 4.94%   |
| en_GB   | 4        | 4.94%   |
| it_IT   | 3        | 3.7%    |
| fr_FR   | 3        | 3.7%    |
| Unknown | 3        | 3.7%    |
| ru_RU   | 2        | 2.47%   |
| pl_PL   | 2        | 2.47%   |
| fr_CA   | 2        | 2.47%   |
| en_CA   | 2        | 2.47%   |
| en_AU   | 2        | 2.47%   |
| zh_CN   | 1        | 1.23%   |
| uk_UA   | 1        | 1.23%   |
| ru_UA   | 1        | 1.23%   |
| hu_HU   | 1        | 1.23%   |
| da_DK   | 1        | 1.23%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 42       | 51.85%  |
| BIOS | 39       | 48.15%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Xfs   | 65       | 81.25%  |
| Ext4  | 13       | 16.25%  |
| Ext3  | 1        | 1.25%   |
| Btrfs | 1        | 1.25%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 37       | 45.68%  |
| GPT     | 32       | 39.51%  |
| MBR     | 12       | 14.81%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 68       | 85%     |
| Yes       | 12       | 15%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 71       | 88.75%  |
| Yes       | 9        | 11.25%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Desktops | Percent |
|-----------------------------|----------|---------|
| Gigabyte Technology         | 14       | 17.5%   |
| MSI                         | 12       | 15%     |
| ASUSTek Computer            | 12       | 15%     |
| Hewlett-Packard             | 10       | 12.5%   |
| Dell                        | 6        | 7.5%    |
| Supermicro                  | 5        | 6.25%   |
| Lenovo                      | 4        | 5%      |
| ASRock                      | 4        | 5%      |
| Intel                       | 3        | 3.75%   |
| Optimized Hosting           | 2        | 2.5%    |
| Techvision                  | 1        | 1.25%   |
| Pelco by Schneider Electric | 1        | 1.25%   |
| Medion                      | 1        | 1.25%   |
| Mancer                      | 1        | 1.25%   |
| MACHINIST                   | 1        | 1.25%   |
| Haier                       | 1        | 1.25%   |
| ASRockRack                  | 1        | 1.25%   |
| Unknown                     | 1        | 1.25%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Optimized Hosting KVM                   | 2        | 2.5%    |
| Gigabyte X570S UD                       | 2        | 2.5%    |
| Techvision TVI7309X                     | 1        | 1.25%   |
| Supermicro X9DR3-F                      | 1        | 1.25%   |
| Supermicro SYS-6018U-TRT+               | 1        | 1.25%   |
| Supermicro PIO-617R-TLN4F+-ST031        | 1        | 1.25%   |
| Supermicro AS -4125GS-TNRT2             | 1        | 1.25%   |
| Supermicro AS -1115CS-TNR               | 1        | 1.25%   |
| Pelco by Schneider Electric E1-MGW-SVRP | 1        | 1.25%   |
| MSI MS-7D91                             | 1        | 1.25%   |
| MSI MS-7D07                             | 1        | 1.25%   |
| MSI MS-7C95                             | 1        | 1.25%   |
| MSI MS-7C56                             | 1        | 1.25%   |
| MSI MS-7C52                             | 1        | 1.25%   |
| MSI MS-7B89                             | 1        | 1.25%   |
| MSI MS-7B33                             | 1        | 1.25%   |
| MSI MS-7A15                             | 1        | 1.25%   |
| MSI MS-7900                             | 1        | 1.25%   |
| MSI MS-7816                             | 1        | 1.25%   |
| MSI MS-7757                             | 1        | 1.25%   |
| MSI KX624AA-ABZ SR5550IT                | 1        | 1.25%   |
| Medion MS-7616                          | 1        | 1.25%   |
| Mancer B450M-DA                         | 1        | 1.25%   |
| MACHINIST X99-MR9A PRO MAX V5.1         | 1        | 1.25%   |
| Lenovo ThinkStation P350 30E6S20S00     | 1        | 1.25%   |
| Lenovo ThinkCentre M720s 10SUS34E00     | 1        | 1.25%   |
| Lenovo H520S 10093                      | 1        | 1.25%   |
| Lenovo H515s 10126                      | 1        | 1.25%   |
| Intel X99                               | 1        | 1.25%   |
| Intel TTL TEKNOPRO                      | 1        | 1.25%   |
| Intel DH77EB AAG39073-304               | 1        | 1.25%   |
| HP Z820 Workstation                     | 1        | 1.25%   |
| HP Z620 Workstation                     | 1        | 1.25%   |
| HP Z600 Workstation                     | 1        | 1.25%   |
| HP Z420 Workstation                     | 1        | 1.25%   |
| HP Z400 Workstation                     | 1        | 1.25%   |
| HP Z4 G4 Workstation                    | 1        | 1.25%   |
| HP Z220 SFF Workstation                 | 1        | 1.25%   |
| HP Z2 Tower G4 Workstation              | 1        | 1.25%   |
| HP xw4600 Workstation                   | 1        | 1.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                    | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Dell OptiPlex                           | 5        | 6.25%   |
| ASUS PRIME                              | 4        | 5%      |
| Supermicro AS                           | 2        | 2.5%    |
| Optimized Hosting KVM                   | 2        | 2.5%    |
| Gigabyte X570S                          | 2        | 2.5%    |
| ASUS Pro                                | 2        | 2.5%    |
| Techvision TVI7309X                     | 1        | 1.25%   |
| Supermicro X9DR3-F                      | 1        | 1.25%   |
| Supermicro SYS-6018U-TRT+               | 1        | 1.25%   |
| Supermicro PIO-617R-TLN4F+-ST031        | 1        | 1.25%   |
| Pelco by Schneider Electric E1-MGW-SVRP | 1        | 1.25%   |
| MSI MS-7D91                             | 1        | 1.25%   |
| MSI MS-7D07                             | 1        | 1.25%   |
| MSI MS-7C95                             | 1        | 1.25%   |
| MSI MS-7C56                             | 1        | 1.25%   |
| MSI MS-7C52                             | 1        | 1.25%   |
| MSI MS-7B89                             | 1        | 1.25%   |
| MSI MS-7B33                             | 1        | 1.25%   |
| MSI MS-7A15                             | 1        | 1.25%   |
| MSI MS-7900                             | 1        | 1.25%   |
| MSI MS-7816                             | 1        | 1.25%   |
| MSI MS-7757                             | 1        | 1.25%   |
| MSI KX624AA-ABZ                         | 1        | 1.25%   |
| Medion MS-7616                          | 1        | 1.25%   |
| Mancer B450M-DA                         | 1        | 1.25%   |
| MACHINIST X99-MR9A                      | 1        | 1.25%   |
| Lenovo ThinkStation                     | 1        | 1.25%   |
| Lenovo ThinkCentre                      | 1        | 1.25%   |
| Lenovo H520S                            | 1        | 1.25%   |
| Lenovo H515s                            | 1        | 1.25%   |
| Intel X99                               | 1        | 1.25%   |
| Intel TTL                               | 1        | 1.25%   |
| Intel DH77EB                            | 1        | 1.25%   |
| HP Z820                                 | 1        | 1.25%   |
| HP Z620                                 | 1        | 1.25%   |
| HP Z600                                 | 1        | 1.25%   |
| HP Z420                                 | 1        | 1.25%   |
| HP Z400                                 | 1        | 1.25%   |
| HP Z4                                   | 1        | 1.25%   |
| HP Z220                                 | 1        | 1.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 12       | 15%     |
| 2012 | 10       | 12.5%   |
| 2021 | 8        | 10%     |
| 2018 | 6        | 7.5%    |
| 2013 | 6        | 7.5%    |
| 2023 | 5        | 6.25%   |
| 2024 | 4        | 5%      |
| 2019 | 4        | 5%      |
| 2017 | 4        | 5%      |
| 2014 | 4        | 5%      |
| 2009 | 3        | 3.75%   |
| 2008 | 3        | 3.75%   |
| 2022 | 2        | 2.5%    |
| 2016 | 2        | 2.5%    |
| 2015 | 2        | 2.5%    |
| 2011 | 2        | 2.5%    |
| 2010 | 2        | 2.5%    |
| 2025 | 1        | 1.25%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 80       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 76       | 93.83%  |
| Enabled  | 5        | 6.17%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 80       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 64.01-256.0     | 21       | 26.25%  |
| 8.01-16.0       | 17       | 21.25%  |
| 4.01-8.0        | 16       | 20%     |
| 32.01-64.0      | 8        | 10%     |
| 24.01-32.0      | 6        | 7.5%    |
| 3.01-4.0        | 5        | 6.25%   |
| More than 256.0 | 4        | 5%      |
| 16.01-24.0      | 3        | 3.75%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB         | Desktops | Percent |
|-----------------|----------|---------|
| 2.01-3.0        | 23       | 27.38%  |
| 4.01-8.0        | 15       | 17.86%  |
| 1.01-2.0        | 12       | 14.29%  |
| 3.01-4.0        | 10       | 11.9%   |
| 8.01-16.0       | 9        | 10.71%  |
| 0.51-1.0        | 6        | 7.14%   |
| 32.01-64.0      | 3        | 3.57%   |
| 24.01-32.0      | 2        | 2.38%   |
| 16.01-24.0      | 2        | 2.38%   |
| More than 256.0 | 1        | 1.19%   |
| 64.01-256.0     | 1        | 1.19%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 25       | 30.49%  |
| 3      | 17       | 20.73%  |
| 2      | 14       | 17.07%  |
| 4      | 11       | 13.41%  |
| 6      | 5        | 6.1%    |
| 5      | 5        | 6.1%    |
| 18     | 1        | 1.22%   |
| 13     | 1        | 1.22%   |
| 12     | 1        | 1.22%   |
| 10     | 1        | 1.22%   |
| 8      | 1        | 1.22%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 47       | 58.75%  |
| Yes       | 33       | 41.25%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 78       | 97.5%   |
| No        | 2        | 2.5%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 47       | 58.75%  |
| Yes       | 33       | 41.25%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 57       | 71.25%  |
| Yes       | 23       | 28.75%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 17       | 21.25%  |
| Russia       | 8        | 10%     |
| France       | 8        | 10%     |
| Canada       | 8        | 10%     |
| Switzerland  | 5        | 6.25%   |
| Italy        | 4        | 5%      |
| Brazil       | 4        | 5%      |
| Germany      | 3        | 3.75%   |
| China        | 3        | 3.75%   |
| Ukraine      | 2        | 2.5%    |
| UK           | 2        | 2.5%    |
| Romania      | 2        | 2.5%    |
| Hungary      | 2        | 2.5%    |
| Australia    | 2        | 2.5%    |
| Sweden       | 1        | 1.25%   |
| South Korea  | 1        | 1.25%   |
| South Africa | 1        | 1.25%   |
| Poland       | 1        | 1.25%   |
| Netherlands  | 1        | 1.25%   |
| Indonesia    | 1        | 1.25%   |
| Greenland    | 1        | 1.25%   |
| Czechia      | 1        | 1.25%   |
| Bangladesh   | 1        | 1.25%   |
| Austria      | 1        | 1.25%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Moscow           | 3        | 3.66%   |
| Tunari           | 2        | 2.44%   |
| Strasbourg       | 2        | 2.44%   |
| Sorel-Tracy      | 2        | 2.44%   |
| Montreal         | 2        | 2.44%   |
| Milan            | 2        | 2.44%   |
| Geneva           | 2        | 2.44%   |
| Beijing          | 2        | 2.44%   |
| Zurich           | 1        | 1.22%   |
| Zaporizhzhia     | 1        | 1.22%   |
| Yekaterinburg    | 1        | 1.22%   |
| Wallingford      | 1        | 1.22%   |
| Vienna           | 1        | 1.22%   |
| Varosfoeld       | 1        | 1.22%   |
| Trappes          | 1        | 1.22%   |
| Teresina         | 1        | 1.22%   |
| Stadtilm         | 1        | 1.22%   |
| St. Paul         | 1        | 1.22%   |
| St Petersburg    | 1        | 1.22%   |
| Shimanovsk       | 1        | 1.22%   |
| Shanghai         | 1        | 1.22%   |
| Santo André     | 1        | 1.22%   |
| Santa Gertrudes  | 1        | 1.22%   |
| Saint-Cloud      | 1        | 1.22%   |
| Saint-Brieuc     | 1        | 1.22%   |
| Rybnik           | 1        | 1.22%   |
| Rochester        | 1        | 1.22%   |
| Ridgeland        | 1        | 1.22%   |
| Plauen           | 1        | 1.22%   |
| Pissos           | 1        | 1.22%   |
| Phoenix          | 1        | 1.22%   |
| Pardubice        | 1        | 1.22%   |
| Odessa           | 1        | 1.22%   |
| Nizhniy Novgorod | 1        | 1.22%   |
| Newmarket        | 1        | 1.22%   |
| New York         | 1        | 1.22%   |
| Minneapolis      | 1        | 1.22%   |
| Meyrin           | 1        | 1.22%   |
| Melbourne        | 1        | 1.22%   |
| Mangunsari       | 1        | 1.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| Seagate                      | 34       | 59     | 21.38%  |
| Samsung Electronics          | 26       | 41     | 16.35%  |
| WDC                          | 25       | 63     | 15.72%  |
| Kingston                     | 7        | 11     | 4.4%    |
| SanDisk                      | 6        | 10     | 3.77%   |
| Toshiba                      | 5        | 6      | 3.14%   |
| SK hynix                     | 5        | 5      | 3.14%   |
| Micron Technology            | 4        | 6      | 2.52%   |
| Crucial                      | 4        | 6      | 2.52%   |
| Micron/Crucial Technology    | 3        | 3      | 1.89%   |
| Kingston Technology Company  | 3        | 4      | 1.89%   |
| Intel                        | 3        | 4      | 1.89%   |
| HGST                         | 3        | 4      | 1.89%   |
| Silicon Motion               | 2        | 15     | 1.26%   |
| QEMU                         | 2        | 4      | 1.26%   |
| Phison Electronics           | 2        | 2      | 1.26%   |
| Patriot                      | 2        | 2      | 1.26%   |
| LITEON                       | 2        | 2      | 1.26%   |
| KIOXIA                       | 2        | 5      | 1.26%   |
| Hitachi                      | 2        | 5      | 1.26%   |
| Team                         | 1        | 1      | 0.63%   |
| SPCC                         | 1        | 1      | 0.63%   |
| Shenzhen Longsys Electronics | 1        | 1      | 0.63%   |
| Seagate Technology           | 1        | 12     | 0.63%   |
| Realtek Semiconductor        | 1        | 1      | 0.63%   |
| ProDrive                     | 1        | 1      | 0.63%   |
| Netac                        | 1        | 1      | 0.63%   |
| MAXIO Technology (Hangzhou)  | 1        | 1      | 0.63%   |
| KUNP                         | 1        | 1      | 0.63%   |
| KingSpec                     | 1        | 2      | 0.63%   |
| Hewlett-Packard              | 1        | 1      | 0.63%   |
| Gopod                        | 1        | 1      | 0.63%   |
| Corsair                      | 1        | 1      | 0.63%   |
| AMD                          | 1        | 15     | 0.63%   |
| ADATA Technology             | 1        | 2      | 0.63%   |
| A-DATA Technology            | 1        | 1      | 0.63%   |
| Unknown                      | 1        | 1      | 0.63%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 4        | 1.98%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 4        | 1.98%   |
| WDC WD40EFRX-68N32N0 4TB                           | 3        | 1.49%   |
| Kingston SA400S37480G 480GB SSD                    | 3        | 1.49%   |
| WDC WD40EFAX-68JH4N1 4TB                           | 2        | 0.99%   |
| WDC WD20EFRX-68EUZN0 2TB                           | 2        | 0.99%   |
| WDC WD10EZEX-08WN4A0 1TB                           | 2        | 0.99%   |
| Seagate ST500DM002-1SB10A 500GB                    | 2        | 0.99%   |
| Seagate ST4000DM000-1F2168 4TB                     | 2        | 0.99%   |
| Seagate ST320LT020-9YG142 320GB                    | 2        | 0.99%   |
| Seagate ST2000DM001-1ER164 2TB                     | 2        | 0.99%   |
| Samsung SSD 980 1TB                                | 2        | 0.99%   |
| Samsung SSD 870 EVO 1TB                            | 2        | 0.99%   |
| Samsung NVMe SSD Controller SM951/PM951 128GB      | 2        | 0.99%   |
| QEMU HARDDISK                                      | 2        | 0.99%   |
| Phison E12 NVMe Controller 1TB                     | 2        | 0.99%   |
| Kingston SA400S37240G 240GB SSD                    | 2        | 0.99%   |
| Hitachi HTS543232A7A384 320GB                      | 2        | 0.99%   |
| Crucial CT240BX500SSD1 240GB                       | 2        | 0.99%   |
| WDC WUH722424ALE6L4 24TB                           | 1        | 0.5%    |
| WDC WDS500G2B0A-00SM50 500GB                       | 1        | 0.5%    |
| WDC WDS240G2G0A-00JH30 240GB SSD                   | 1        | 0.5%    |
| WDC WDS100T2B0B-00YS70 1TB SSD                     | 1        | 0.5%    |
| WDC WDS100T2B0A-00SM50 1TB SSD                     | 1        | 0.5%    |
| WDC WD60EFRX-68L0BN1 6TB                           | 1        | 0.5%    |
| WDC WD5000LPVX-75V0TT0 500GB                       | 1        | 0.5%    |
| WDC WD40PURX-64GVNY0 4TB                           | 1        | 0.5%    |
| WDC WD40EZRX-00SPEB0 4TB                           | 1        | 0.5%    |
| WDC WD40EFZX-68AWUN0 4TB                           | 1        | 0.5%    |
| WDC WD40EFPX-68C6CN0 4TB                           | 1        | 0.5%    |
| WDC WD4000FYYZ-01UL1B2 4TB                         | 1        | 0.5%    |
| WDC WD4000FYYZ-01UL1B1 4TB                         | 1        | 0.5%    |
| WDC WD4000FDYZ-27YA5B0 4TB                         | 1        | 0.5%    |
| WDC WD4000F9YZ-09N20L1 4TB                         | 1        | 0.5%    |
| WDC WD4000F9YZ-09N20L0 4TB                         | 1        | 0.5%    |
| WDC WD3600FYYZ-01UL1B3 4TB                         | 1        | 0.5%    |
| WDC WD3600FYYZ-01UL1B1 4TB                         | 1        | 0.5%    |
| WDC WD35EFRX-68WT0N0 4TB                           | 1        | 0.5%    |
| WDC WD30EZRX-00SPEB0 3TB                           | 1        | 0.5%    |
| WDC WD20NPVX-00EA4T0 2TB                           | 1        | 0.5%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 33       | 47     | 47.14%  |
| WDC                 | 24       | 58     | 34.29%  |
| Toshiba             | 5        | 6      | 7.14%   |
| HGST                | 3        | 4      | 4.29%   |
| QEMU                | 2        | 4      | 2.86%   |
| Hitachi             | 2        | 5      | 2.86%   |
| Samsung Electronics | 1        | 1      | 1.43%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 11       | 14     | 25.58%  |
| Kingston            | 6        | 7      | 13.95%  |
| WDC                 | 3        | 5      | 6.98%   |
| SK hynix            | 3        | 3      | 6.98%   |
| Micron Technology   | 3        | 4      | 6.98%   |
| Crucial             | 3        | 4      | 6.98%   |
| SanDisk             | 2        | 3      | 4.65%   |
| Patriot             | 2        | 2      | 4.65%   |
| LITEON              | 2        | 2      | 4.65%   |
| Team                | 1        | 1      | 2.33%   |
| SPCC                | 1        | 1      | 2.33%   |
| Netac               | 1        | 1      | 2.33%   |
| KingSpec            | 1        | 2      | 2.33%   |
| Intel               | 1        | 1      | 2.33%   |
| Hewlett-Packard     | 1        | 1      | 2.33%   |
| Corsair             | 1        | 1      | 2.33%   |
| A-DATA Technology   | 1        | 1      | 2.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 55       | 125    | 39.57%  |
| NVMe    | 42       | 118    | 30.22%  |
| SSD     | 38       | 53     | 27.34%  |
| Unknown | 4        | 5      | 2.88%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 71       | 177    | 60.17%  |
| NVMe | 42       | 117    | 35.59%  |
| SAS  | 5        | 7      | 4.24%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 41       | 60     | 37.61%  |
| 0.51-1.0   | 29       | 40     | 26.61%  |
| 3.01-4.0   | 15       | 46     | 13.76%  |
| 1.01-2.0   | 13       | 17     | 11.93%  |
| 4.01-10.0  | 7        | 8      | 6.42%   |
| 2.01-3.0   | 3        | 3      | 2.75%   |
| 20.01-50.0 | 1        | 4      | 0.92%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 18       | 22.22%  |
| 501-1000       | 18       | 22.22%  |
| More than 3000 | 12       | 14.81%  |
| 251-500        | 11       | 13.58%  |
| 1001-2000      | 9        | 11.11%  |
| 2001-3000      | 5        | 6.17%   |
| Unknown        | 4        | 4.94%   |
| 1-20           | 2        | 2.47%   |
| 21-50          | 1        | 1.23%   |
| 51-100         | 1        | 1.23%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 21       | 25.3%   |
| 21-50          | 19       | 22.89%  |
| 251-500        | 10       | 12.05%  |
| 101-250        | 10       | 12.05%  |
| More than 3000 | 6        | 7.23%   |
| 1001-2000      | 4        | 4.82%   |
| 501-1000       | 4        | 4.82%   |
| 51-100         | 4        | 4.82%   |
| Unknown        | 4        | 4.82%   |
| 2001-3000      | 1        | 1.2%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                         | Desktops | Drives | Percent |
|---------------------------------------------------------------|----------|--------|---------|
| WDC WD4000FDYZ-27YA5B0 4TB                                    | 1        | 1      | 9.09%   |
| WDC WD20EFRX-68EUZN0 2TB                                      | 1        | 1      | 9.09%   |
| WDC WD20EARS-00J2GB0 2TB                                      | 1        | 1      | 9.09%   |
| WDC WD1003FBYX-01Y7B0 1TB                                     | 1        | 1      | 9.09%   |
| SK hynix SH920 2.5 7MM 256GB SSD                              | 1        | 1      | 9.09%   |
| Seagate ST4000DM000-1F2168 4TB                                | 1        | 1      | 9.09%   |
| Seagate ST1000DM010-2EP102 1TB                                | 1        | 2      | 9.09%   |
| Samsung Electronics NVMe SSD Controller SM981/PM981/PM983 1TB | 1        | 1      | 9.09%   |
| Samsung Electronics HD642JJ 640GB                             | 1        | 1      | 9.09%   |
| Kingston SUV400S37240G 240GB SSD                              | 1        | 1      | 9.09%   |
| HGST HTS725050A7E630 500GB                                    | 1        | 1      | 9.09%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 4        | 4      | 36.36%  |
| Seagate             | 2        | 3      | 18.18%  |
| Samsung Electronics | 2        | 2      | 18.18%  |
| SK hynix            | 1        | 1      | 9.09%   |
| Kingston            | 1        | 1      | 9.09%   |
| HGST                | 1        | 1      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 4        | 4      | 50%     |
| Seagate             | 2        | 3      | 25%     |
| Samsung Electronics | 1        | 1      | 12.5%   |
| HGST                | 1        | 1      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 8        | 9      | 72.73%  |
| SSD  | 2        | 2      | 18.18%  |
| NVMe | 1        | 1      | 9.09%   |

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
| Detected | 44       | 130    | 46.81%  |
| Works    | 40       | 159    | 42.55%  |
| Malfunc  | 10       | 12     | 10.64%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 53       | 36.55%  |
| AMD                          | 28       | 19.31%  |
| Samsung Electronics          | 15       | 10.34%  |
| ASMedia Technology           | 9        | 6.21%   |
| Kingston Technology Company  | 6        | 4.14%   |
| SanDisk                      | 4        | 2.76%   |
| Micron/Crucial Technology    | 4        | 2.76%   |
| Broadcom / LSI               | 4        | 2.76%   |
| Seagate Technology           | 3        | 2.07%   |
| SK hynix                     | 2        | 1.38%   |
| Silicon Motion               | 2        | 1.38%   |
| Red Hat                      | 2        | 1.38%   |
| Phison Electronics           | 2        | 1.38%   |
| LSI Logic / Symbios Logic    | 2        | 1.38%   |
| KIOXIA                       | 2        | 1.38%   |
| Shenzhen Longsys Electronics | 1        | 0.69%   |
| Realtek Semiconductor        | 1        | 0.69%   |
| Micron Technology            | 1        | 0.69%   |
| MAXIO Technology (Hangzhou)  | 1        | 0.69%   |
| Marvell Technology Group     | 1        | 0.69%   |
| ADATA Technology             | 1        | 0.69%   |
| 3ware                        | 1        | 0.69%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 18       | 10.34%  |
| Intel SATA Controller [RAID mode]                                              | 10       | 5.75%   |
| AMD 400 Series Chipset SATA Controller                                         | 8        | 4.6%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5        | 2.87%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 5        | 2.87%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5        | 2.87%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 5        | 2.87%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 5        | 2.87%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                            | 4        | 2.3%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 4        | 2.3%    |
| AMD 500 Series Chipset SATA Controller                                         | 4        | 2.3%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 3        | 1.72%   |
| Intel C600/X79 series chipset IDE-r Controller                                 | 3        | 1.72%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 3        | 1.72%   |
| ASMedia ASM1166 Serial ATA Controller                                          | 3        | 1.72%   |
| Seagate E18 PCIe SSD                                                           | 2        | 1.15%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 2        | 1.15%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 2        | 1.15%   |
| Red Hat Virtio 1.0 SCSI                                                        | 2        | 1.15%   |
| Phison E12 NVMe Controller                                                     | 2        | 1.15%   |
| Intel Raptor Lake SATA AHCI Controller                                         | 2        | 1.15%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2        | 1.15%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 2        | 1.15%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 2        | 1.15%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 2        | 1.15%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]           | 2        | 1.15%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 2        | 1.15%   |
| AMD 600 Series Chipset SATA Controller                                         | 2        | 1.15%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 1        | 0.57%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 1        | 0.57%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 1        | 0.57%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 1        | 0.57%   |
| Shenzhen Longsys Lexar NM610 PRO NVME SSD (DRAM-less)                          | 1        | 0.57%   |
| Seagate FireCuda 540 SSD                                                       | 1        | 0.57%   |
| SanDisk WD SN560/SN740/SN770/SN5000 NVMe SSD                                   | 1        | 0.57%   |
| SanDisk WD Blue SN570 NVMe SSD 2TB                                             | 1        | 0.57%   |
| SanDisk WD Black NVMe SSD                                                      | 1        | 0.57%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 1        | 0.57%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1        | 0.57%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                    | 1        | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 68       | 47.89%  |
| NVMe | 41       | 28.87%  |
| RAID | 15       | 10.56%  |
| IDE  | 9        | 6.34%   |
| SAS  | 7        | 4.93%   |
| SCSI | 2        | 1.41%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 49       | 61.25%  |
| AMD    | 31       | 38.75%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Intel Core i7 CPU 870 @ 2.93GHz        | 2        | 2.5%    |
| Intel Core i5-6500 CPU @ 3.20GHz       | 2        | 2.5%    |
| AMD Ryzen 9 3900X 12-Core Processor    | 2        | 2.5%    |
| AMD Ryzen 5 5600G with Radeon Graphics | 2        | 2.5%    |
| AMD Ryzen 5 3600 6-Core Processor      | 2        | 2.5%    |
| AMD Ryzen 3 5300G with Radeon Graphics | 2        | 2.5%    |
| AMD EPYC-Rome Processor                | 2        | 2.5%    |
| Intel Xeon W-2223 CPU @ 3.60GHz        | 1        | 1.25%   |
| Intel Xeon W-1350 @ 3.30GHz            | 1        | 1.25%   |
| Intel Xeon E-2144G CPU @ 3.60GHz       | 1        | 1.25%   |
| Intel Xeon CPU X5550 @ 2.67GHz         | 1        | 1.25%   |
| Intel Xeon CPU E5540 @ 2.53GHz         | 1        | 1.25%   |
| Intel Xeon CPU E5-2697 v2 @ 2.70GHz    | 1        | 1.25%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz     | 1        | 1.25%   |
| Intel Xeon CPU E5-2683 v4 @ 2.10GHz    | 1        | 1.25%   |
| Intel Xeon CPU E5-2680 v4 @ 2.40GHz    | 1        | 1.25%   |
| Intel Xeon CPU E5-2667 v2 @ 3.30GHz    | 1        | 1.25%   |
| Intel Xeon CPU E5-2640 v4 @ 2.40GHz    | 1        | 1.25%   |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz    | 1        | 1.25%   |
| Intel Xeon CPU E5-1620 0 @ 3.60GHz     | 1        | 1.25%   |
| Intel Xeon CPU E3-1275 v3 @ 3.50GHz    | 1        | 1.25%   |
| Intel Xeon CPU E3-1245 V2 @ 3.40GHz    | 1        | 1.25%   |
| Intel N100                             | 1        | 1.25%   |
| Intel Core i7-8700K CPU @ 3.70GHz      | 1        | 1.25%   |
| Intel Core i7-8550U CPU @ 1.80GHz      | 1        | 1.25%   |
| Intel Core i7-7700 CPU @ 3.60GHz       | 1        | 1.25%   |
| Intel Core i7-3770K CPU @ 3.50GHz      | 1        | 1.25%   |
| Intel Core i7-3770 CPU @ 3.40GHz       | 1        | 1.25%   |
| Intel Core i7-14700K                   | 1        | 1.25%   |
| Intel Core i7-10700 CPU @ 2.90GHz      | 1        | 1.25%   |
| Intel Core i7 CPU X 980 @ 3.33GHz      | 1        | 1.25%   |
| Intel Core i5-8600K CPU @ 3.60GHz      | 1        | 1.25%   |
| Intel Core i5-7500T CPU @ 2.70GHz      | 1        | 1.25%   |
| Intel Core i5-4590 CPU @ 3.30GHz       | 1        | 1.25%   |
| Intel Core i5-4460 CPU @ 3.20GHz       | 1        | 1.25%   |
| Intel Core i5-4440 CPU @ 3.10GHz       | 1        | 1.25%   |
| Intel Core i5-3570 CPU @ 3.40GHz       | 1        | 1.25%   |
| Intel Core i5-10400F CPU @ 2.90GHz     | 1        | 1.25%   |
| Intel Core i3-8100 CPU @ 3.60GHz       | 1        | 1.25%   |
| Intel Core i3-7100 CPU @ 3.90GHz       | 1        | 1.25%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Xeon             | 15       | 18.75%  |
| Intel Core i7          | 10       | 12.5%   |
| AMD Ryzen 5            | 10       | 12.5%   |
| Intel Core i5          | 9        | 11.25%  |
| Other                  | 5        | 6.25%   |
| Intel Core i3          | 5        | 6.25%   |
| AMD Ryzen Threadripper | 5        | 6.25%   |
| AMD Ryzen 9            | 4        | 5%      |
| AMD EPYC               | 4        | 5%      |
| Intel Core 2 Quad      | 2        | 2.5%    |
| AMD Ryzen 3            | 2        | 2.5%    |
| AMD FX                 | 2        | 2.5%    |
| Intel Core 2 Duo       | 1        | 1.25%   |
| Intel Celeron          | 1        | 1.25%   |
| Intel Atom             | 1        | 1.25%   |
| AMD Ryzen 7            | 1        | 1.25%   |
| AMD E2                 | 1        | 1.25%   |
| AMD A8                 | 1        | 1.25%   |
| AMD A10                | 1        | 1.25%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 32       | 40%     |
| 6      | 14       | 17.5%   |
| 2      | 9        | 11.25%  |
| 16     | 6        | 7.5%    |
| 32     | 4        | 5%      |
| 12     | 4        | 5%      |
| 8      | 4        | 5%      |
| 20     | 2        | 2.5%    |
| 192    | 1        | 1.25%   |
| 64     | 1        | 1.25%   |
| 24     | 1        | 1.25%   |
| 14     | 1        | 1.25%   |
| 1      | 1        | 1.25%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 71       | 88.75%  |
| 2      | 7        | 8.75%   |
| 4      | 2        | 2.5%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 58       | 72.5%   |
| 1      | 22       | 27.5%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 80       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 49       | 59.76%  |
| 0x08701021 | 4        | 4.88%   |
| 0xa0671    | 3        | 3.66%   |
| 0x306e4    | 2        | 2.44%   |
| 0x306c3    | 2        | 2.44%   |
| 0x106a5    | 2        | 2.44%   |
| 0x0a50000d | 2        | 2.44%   |
| 0x0a101148 | 2        | 2.44%   |
| 0x06000852 | 2        | 2.44%   |
| 0xa0655    | 1        | 1.22%   |
| 0x906ea    | 1        | 1.22%   |
| 0x906e9    | 1        | 1.22%   |
| 0x506e3    | 1        | 1.22%   |
| 0x50657    | 1        | 1.22%   |
| 0x306a9    | 1        | 1.22%   |
| 0x30661    | 1        | 1.22%   |
| 0x206d7    | 1        | 1.22%   |
| 0x206a7    | 1        | 1.22%   |
| 0x0a20120a | 1        | 1.22%   |
| 0x0a201016 | 1        | 1.22%   |
| 0x0830107a | 1        | 1.22%   |
| 0x08001137 | 1        | 1.22%   |
| 0x06003106 | 1        | 1.22%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 2            | 11       | 13.75%  |
| KabyLake         | 8        | 10%     |
| IvyBridge        | 8        | 10%     |
| Zen 3            | 7        | 8.75%   |
| Unknown          | 7        | 8.75%   |
| Haswell          | 5        | 6.25%   |
| Nehalem          | 4        | 5%      |
| Skylake          | 3        | 3.75%   |
| SandyBridge      | 3        | 3.75%   |
| Icelake          | 3        | 3.75%   |
| Broadwell        | 3        | 3.75%   |
| Zen+             | 2        | 2.5%    |
| Piledriver       | 2        | 2.5%    |
| Penryn           | 2        | 2.5%    |
| CometLake        | 2        | 2.5%    |
| Zen              | 1        | 1.25%   |
| Westmere         | 1        | 1.25%   |
| Tremont          | 1        | 1.25%   |
| Steamroller      | 1        | 1.25%   |
| Jaguar           | 1        | 1.25%   |
| Gracemont        | 1        | 1.25%   |
| Excavator        | 1        | 1.25%   |
| Core             | 1        | 1.25%   |
| Bonnell          | 1        | 1.25%   |
| Alderlake Hybrid | 1        | 1.25%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 32       | 37.21%  |
| Intel                      | 23       | 26.74%  |
| AMD                        | 22       | 25.58%  |
| ASPEED Technology          | 5        | 5.81%   |
| Matrox Electronics Systems | 2        | 2.33%   |
| Technical                  | 1        | 1.16%   |
| Red Hat                    | 1        | 1.16%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| ASPEED Technology ASPEED Graphics Family                                    | 5        | 5.75%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 4        | 4.6%    |
| Nvidia GK208B [GeForce GT 710]                                              | 3        | 3.45%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3        | 3.45%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 2        | 2.3%    |
| Nvidia GP104 [GeForce GTX 1080]                                             | 2        | 2.3%    |
| Nvidia GK208B [GeForce GT 730]                                              | 2        | 2.3%    |
| Nvidia GF119 [GeForce GT 610]                                               | 2        | 2.3%    |
| Nvidia GA106 [Geforce RTX 3050]                                             | 2        | 2.3%    |
| Matrox Electronics Systems MGA G200eW WPCM450                               | 2        | 2.3%    |
| Intel Skylake-S GT2 [HD Graphics 530]                                       | 2        | 2.3%    |
| Intel Kaby Lake-S GT2 [HD Graphics 630]                                     | 2        | 2.3%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 2.3%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2        | 2.3%    |
| Technical VGA compatible controller                                         | 1        | 1.15%   |
| Red Hat QXL paravirtual graphic card                                        | 1        | 1.15%   |
| Nvidia TU117GLM [Quadro T400 Mobile]                                        | 1        | 1.15%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 1.15%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 1.15%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 1.15%   |
| Nvidia GP107GL [Quadro P620]                                                | 1        | 1.15%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 1.15%   |
| Nvidia GP106GL [Quadro P2200]                                               | 1        | 1.15%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 1.15%   |
| Nvidia GM204GL [Quadro M4000]                                               | 1        | 1.15%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1        | 1.15%   |
| Nvidia GM107GL [Quadro K2200]                                               | 1        | 1.15%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 1.15%   |
| Nvidia GK104 [GeForce GTX 770]                                              | 1        | 1.15%   |
| Nvidia GH100 [H100L 94GB]                                                   | 1        | 1.15%   |
| Nvidia GF108GL [Quadro 600]                                                 | 1        | 1.15%   |
| Nvidia GF108 [GeForce GT 730]                                               | 1        | 1.15%   |
| Nvidia GF100GL [Quadro 4000]                                                | 1        | 1.15%   |
| Nvidia AD103 [GeForce RTX 4070 Ti SUPER]                                    | 1        | 1.15%   |
| Nvidia AD102 [GeForce RTX 4090]                                             | 1        | 1.15%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 1.15%   |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller              | 1        | 1.15%   |
| Intel RocketLake-S GT1 [UHD Graphics P750]                                  | 1        | 1.15%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 1        | 1.15%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                   | 1        | 1.15%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 27       | 33.75%  |
| 1 x Intel       | 20       | 25%     |
| 1 x AMD         | 18       | 22.5%   |
| 1 x ASPEED      | 4        | 5%      |
| 1 x Matrox      | 2        | 2.5%    |
| Intel + AMD     | 2        | 2.5%    |
| 2 x Nvidia      | 1        | 1.25%   |
| 2 x AMD         | 1        | 1.25%   |
| 1 x Technical   | 1        | 1.25%   |
| 1 x Red Hat     | 1        | 1.25%   |
| Nvidia + ASPEED | 1        | 1.25%   |
| Intel + Nvidia  | 1        | 1.25%   |
| AMD + Nvidia    | 1        | 1.25%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 56       | 68.29%  |
| Proprietary | 13       | 15.85%  |
| Unknown     | 13       | 15.85%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 49       | 59.76%  |
| 1.01-2.0   | 8        | 9.76%   |
| 0.51-1.0   | 7        | 8.54%   |
| 7.01-8.0   | 5        | 6.1%    |
| 0.01-0.5   | 5        | 6.1%    |
| 3.01-4.0   | 4        | 4.88%   |
| 5.01-6.0   | 2        | 2.44%   |
| 4.01-5.0   | 1        | 1.22%   |
| 16.01-24.0 | 1        | 1.22%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 12       | 16.67%  |
| Goldstar             | 8        | 11.11%  |
| Samsung Electronics  | 6        | 8.33%   |
| Eizo                 | 5        | 6.94%   |
| Philips              | 4        | 5.56%   |
| Lenovo               | 4        | 5.56%   |
| Acer                 | 4        | 5.56%   |
| BenQ                 | 3        | 4.17%   |
| AOC                  | 3        | 4.17%   |
| Ancor Communications | 3        | 4.17%   |
| ___                  | 2        | 2.78%   |
| ViewSonic            | 2        | 2.78%   |
| Iiyama               | 2        | 2.78%   |
| Vizio                | 1        | 1.39%   |
| Unknown              | 1        | 1.39%   |
| TopView              | 1        | 1.39%   |
| STD                  | 1        | 1.39%   |
| RPL                  | 1        | 1.39%   |
| RHT                  | 1        | 1.39%   |
| Panasonic            | 1        | 1.39%   |
| NEC Computers        | 1        | 1.39%   |
| MiTAC                | 1        | 1.39%   |
| Medion               | 1        | 1.39%   |
| Hewlett-Packard      | 1        | 1.39%   |
| HannStar             | 1        | 1.39%   |
| CZZ                  | 1        | 1.39%   |
| ASUSTek Computer     | 1        | 1.39%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| ___ LCD TV ___9000 1360x768                                           | 2        | 2.67%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 2        | 2.67%   |
| Vizio E190VA VIZ0067 1920x1080 410x230mm 18.5-inch                    | 1        | 1.33%   |
| ViewSonic VX2233wm-1 VSC1D22 1920x1080 477x268mm 21.5-inch            | 1        | 1.33%   |
| ViewSonic VA2232 Series VSC8224 1680x1050 474x296mm 22.0-inch         | 1        | 1.33%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 1        | 1.33%   |
| TopView HD TV TOPC37E 1920x1080 700x390mm 31.5-inch                   | 1        | 1.33%   |
| STD HDMI TV STD00C7 1920x1080 698x392mm 31.5-inch                     | 1        | 1.33%   |
| Samsung Electronics U32H85x SAM0E3A 3840x2160 697x392mm 31.5-inch     | 1        | 1.33%   |
| Samsung Electronics SyncMaster SAM021B 1400x1050 408x300mm 19.9-inch  | 1        | 1.33%   |
| Samsung Electronics SA300/SA350 SAM078F 1920x1080 477x268mm 21.5-inch | 1        | 1.33%   |
| Samsung Electronics S27H65x SAM0E1D 1920x1080 598x336mm 27.0-inch     | 1        | 1.33%   |
| Samsung Electronics LCD Monitor SAM0D42 3840x2160 890x500mm 40.2-inch | 1        | 1.33%   |
| Samsung Electronics LCD Monitor S32B80P 5760x2160                     | 1        | 1.33%   |
| Samsung Electronics LCD Monitor S32B80P                               | 1        | 1.33%   |
| Samsung Electronics F27G3xTF SAM710D 1920x1080 600x330mm 27.0-inch    | 1        | 1.33%   |
| RPL RPI MON156 RPL0100 1920x1080 350x190mm 15.7-inch                  | 1        | 1.33%   |
| RHT QEMU Monitor RHT1234 2048x1152 325x203mm 15.1-inch                | 1        | 1.33%   |
| Philips PHL 272B7QU PHL0926 2560x1440 597x336mm 27.0-inch             | 1        | 1.33%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 1        | 1.33%   |
| Philips PHL 221V8 PHLC211 1920x1080 477x268mm 21.5-inch               | 1        | 1.33%   |
| Philips 19B PHL0879 1280x1024 376x301mm 19.0-inch                     | 1        | 1.33%   |
| Panasonic TV MEIA063 1280x720 1434x806mm 64.8-inch                    | 1        | 1.33%   |
| NEC Computers AS191WM NEC67C0 1440x900 408x255mm 18.9-inch            | 1        | 1.33%   |
| MiTAC JVC TV SZM0074 3840x2160 800x450mm 36.1-inch                    | 1        | 1.33%   |
| Medion MD7212AS MED4971 1280x1024 359x287mm 18.1-inch                 | 1        | 1.33%   |
| Lenovo LEN T2424pA LEN60C8 1920x1080 527x296mm 23.8-inch              | 1        | 1.33%   |
| Lenovo LEN L171 LEN240B 1280x1024 337x270mm 17.0-inch                 | 1        | 1.33%   |
| Lenovo L24q-10 LEN65CF 2560x1440 527x296mm 23.8-inch                  | 1        | 1.33%   |
| Lenovo D19-10 LEN61E0 1366x768 430x255mm 19.7-inch                    | 1        | 1.33%   |
| Iiyama PL3288UH IVM7610 3840x2160 698x393mm 31.5-inch                 | 1        | 1.33%   |
| Iiyama PL2409HD IVM560C 1920x1080 521x293mm 23.5-inch                 | 1        | 1.33%   |
| Hewlett-Packard 2311 HWP293A 1920x1080 509x286mm 23.0-inch            | 1        | 1.33%   |
| HannStar HT231 HSD5173 1920x1080 509x286mm 23.0-inch                  | 1        | 1.33%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch           | 1        | 1.33%   |
| Goldstar L226W GSM566B 1680x1050 474x296mm 22.0-inch                  | 1        | 1.33%   |
| Goldstar E2241 GSM5818 1920x1080 477x268mm 21.5-inch                  | 1        | 1.33%   |
| Goldstar 24GN50W GSM5BA7 1920x1080 531x298mm 24.0-inch                | 1        | 1.33%   |
| Goldstar 23MP55 GSM5A23 1920x1080 510x290mm 23.1-inch                 | 1        | 1.33%   |
| Goldstar 22EA53 GSM59A6 1920x1080 477x268mm 21.5-inch                 | 1        | 1.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 34       | 48.57%  |
| 3840x2160 (4K)     | 8        | 11.43%  |
| 1280x1024 (SXGA)   | 6        | 8.57%   |
| 2560x1440 (QHD)    | 4        | 5.71%   |
| 1920x1200 (WUXGA)  | 2        | 2.86%   |
| 1680x1050 (WSXGA+) | 2        | 2.86%   |
| 1440x900 (WXGA+)   | 2        | 2.86%   |
| 1280x720 (HD)      | 2        | 2.86%   |
| 5760x2160          | 1        | 1.43%   |
| 3440x1440          | 1        | 1.43%   |
| 2560x1600          | 1        | 1.43%   |
| 2560x1397          | 1        | 1.43%   |
| 2560x1080          | 1        | 1.43%   |
| 2288x1287          | 1        | 1.43%   |
| 1600x1200          | 1        | 1.43%   |
| 1400x1050          | 1        | 1.43%   |
| 1366x768 (WXGA)    | 1        | 1.43%   |
| Unknown            | 1        | 1.43%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 10       | 14.08%  |
| 24      | 10       | 14.08%  |
| 23      | 9        | 12.68%  |
| 31      | 8        | 11.27%  |
| 21      | 7        | 9.86%   |
| 19      | 6        | 8.45%   |
| Unknown | 5        | 7.04%   |
| 34      | 2        | 2.82%   |
| 29      | 2        | 2.82%   |
| 18      | 2        | 2.82%   |
| 17      | 2        | 2.82%   |
| 142     | 1        | 1.41%   |
| 84      | 1        | 1.41%   |
| 64      | 1        | 1.41%   |
| 36      | 1        | 1.41%   |
| 22      | 1        | 1.41%   |
| 20      | 1        | 1.41%   |
| 16      | 1        | 1.41%   |
| 15      | 1        | 1.41%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 26       | 37.68%  |
| 401-500        | 13       | 18.84%  |
| 601-700        | 10       | 14.49%  |
| 351-400        | 6        | 8.7%    |
| Unknown        | 5        | 7.25%   |
| 701-800        | 3        | 4.35%   |
| 301-350        | 3        | 4.35%   |
| More than 2000 | 1        | 1.45%   |
| 1501-2000      | 1        | 1.45%   |
| 1001-1500      | 1        | 1.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 47       | 69.12%  |
| 5/4     | 6        | 8.82%   |
| 16/10   | 5        | 7.35%   |
| Unknown | 3        | 4.41%   |
| 4/3     | 2        | 2.94%   |
| 21/9    | 2        | 2.94%   |
| 6/5     | 1        | 1.47%   |
| 3/2     | 1        | 1.47%   |
| 1.00    | 1        | 1.47%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 24       | 33.8%   |
| 351-500        | 12       | 16.9%   |
| 151-200        | 11       | 15.49%  |
| 301-350        | 10       | 14.08%  |
| Unknown        | 5        | 7.04%   |
| More than 1000 | 3        | 4.23%   |
| 141-150        | 2        | 2.82%   |
| 251-300        | 1        | 1.41%   |
| 111-120        | 1        | 1.41%   |
| 101-110        | 1        | 1.41%   |
| 501-1000       | 1        | 1.41%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 42       | 62.69%  |
| 101-120 | 11       | 16.42%  |
| 121-160 | 7        | 10.45%  |
| Unknown | 5        | 7.46%   |
| 1-50    | 2        | 2.99%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 54       | 65.85%  |
| 0     | 17       | 20.73%  |
| 2     | 10       | 12.2%   |
| 3     | 1        | 1.22%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 43       | 36.75%  |
| Realtek Semiconductor    | 40       | 34.19%  |
| TP-Link                  | 5        | 4.27%   |
| Qualcomm Atheros         | 5        | 4.27%   |
| Ralink Technology        | 4        | 3.42%   |
| Broadcom                 | 4        | 3.42%   |
| Mellanox Technologies    | 2        | 1.71%   |
| Insyde Software          | 2        | 1.71%   |
| Broadcom Limited         | 2        | 1.71%   |
| Sigma Designs            | 1        | 0.85%   |
| Ralink                   | 1        | 0.85%   |
| NetGear                  | 1        | 0.85%   |
| Marvell Technology Group | 1        | 0.85%   |
| Emulex                   | 1        | 0.85%   |
| Cypress Semiconductor    | 1        | 0.85%   |
| Chelsio Communications   | 1        | 0.85%   |
| Aquantia                 | 1        | 0.85%   |
| American Megatrends      | 1        | 0.85%   |
| 3Com                     | 1        | 0.85%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 30       | 20%     |
| Intel Ethernet Controller X550                                         | 6        | 4%      |
| Realtek RTL8125 2.5GbE Controller                                      | 5        | 3.33%   |
| Intel Wi-Fi 6 AX200                                                    | 5        | 3.33%   |
| Intel I211 Gigabit Network Connection                                  | 4        | 2.67%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 4        | 2.67%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                    | 3        | 2%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 3        | 2%      |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 3        | 2%      |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 3        | 2%      |
| Intel I350 Gigabit Network Connection                                  | 3        | 2%      |
| Intel I210 Gigabit Network Connection                                  | 3        | 2%      |
| Intel Ethernet Controller I225-V                                       | 3        | 2%      |
| Intel Ethernet Connection (2) I219-LM                                  | 3        | 2%      |
| Intel 82579V Gigabit Network Connection                                | 3        | 2%      |
| Ralink MT7601U Wireless Adapter                                        | 2        | 1.33%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 2        | 1.33%   |
| Intel Wireless 7265                                                    | 2        | 1.33%   |
| Intel Ethernet Controller X710 for 10GBASE-T                           | 2        | 1.33%   |
| Intel Ethernet Controller I226-V                                       | 2        | 1.33%   |
| Intel Ethernet Connection (14) I219-LM                                 | 2        | 1.33%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                   | 2        | 1.33%   |
| Intel 82574L Gigabit Network Connection                                | 2        | 1.33%   |
| Insyde Software RNDIS/Ethernet Gadget                                  | 2        | 1.33%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 2        | 1.33%   |
| TP-Link Archer T4U ver.3                                               | 1        | 0.67%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                 | 1        | 0.67%   |
| Sigma Designs Aeotec Z-Stick Gen5 (ZW090) - UZB                        | 1        | 0.67%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 1        | 0.67%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 1        | 0.67%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 1        | 0.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 1        | 0.67%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                    | 1        | 0.67%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 1        | 0.67%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 1        | 0.67%   |
| Ralink RT5572 Wireless Adapter                                         | 1        | 0.67%   |
| Ralink RT3572 Wireless Adapter                                         | 1        | 0.67%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                              | 1        | 0.67%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 1        | 0.67%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                       | 1        | 0.67%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 14       | 41.18%  |
| Realtek Semiconductor | 6        | 17.65%  |
| TP-Link               | 5        | 14.71%  |
| Ralink Technology     | 4        | 11.76%  |
| Qualcomm Atheros      | 3        | 8.82%   |
| Ralink                | 1        | 2.94%   |
| NetGear               | 1        | 2.94%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                            | 5        | 14.71%  |
| TP-Link Archer T2U PLUS [RTL8821AU]                                            | 3        | 8.82%   |
| Ralink MT7601U Wireless Adapter                                                | 2        | 5.88%   |
| Intel Wireless 7265                                                            | 2        | 5.88%   |
| TP-Link Archer T4U ver.3                                                       | 1        | 2.94%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                         | 1        | 2.94%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                    | 1        | 2.94%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                       | 1        | 2.94%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 1        | 2.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 1        | 2.94%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                            | 1        | 2.94%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 1        | 2.94%   |
| Ralink RT5572 Wireless Adapter                                                 | 1        | 2.94%   |
| Ralink RT3572 Wireless Adapter                                                 | 1        | 2.94%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                      | 1        | 2.94%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 1        | 2.94%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                               | 1        | 2.94%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 1        | 2.94%   |
| NetGear A6150                                                                  | 1        | 2.94%   |
| Intel Wireless 8265 / 8275                                                     | 1        | 2.94%   |
| Intel Wireless 8260                                                            | 1        | 2.94%   |
| Intel Wireless 3165                                                            | 1        | 2.94%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                      | 1        | 2.94%   |
| Intel Tiger Lake PCH CNVi WiFi                                                 | 1        | 2.94%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 1        | 2.94%   |
| Intel 700 Series Chipset CNVi WiFi                                             | 1        | 2.94%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 40       | 41.24%  |
| Intel                    | 39       | 40.21%  |
| Broadcom                 | 4        | 4.12%   |
| Qualcomm Atheros         | 2        | 2.06%   |
| Mellanox Technologies    | 2        | 2.06%   |
| Insyde Software          | 2        | 2.06%   |
| Broadcom Limited         | 2        | 2.06%   |
| Marvell Technology Group | 1        | 1.03%   |
| Emulex                   | 1        | 1.03%   |
| Chelsio Communications   | 1        | 1.03%   |
| Aquantia                 | 1        | 1.03%   |
| American Megatrends      | 1        | 1.03%   |
| 3Com                     | 1        | 1.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 30       | 26.32%  |
| Intel Ethernet Controller X550                                         | 6        | 5.26%   |
| Realtek RTL8125 2.5GbE Controller                                      | 5        | 4.39%   |
| Intel I211 Gigabit Network Connection                                  | 4        | 3.51%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 4        | 3.51%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 3        | 2.63%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 3        | 2.63%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 3        | 2.63%   |
| Intel I350 Gigabit Network Connection                                  | 3        | 2.63%   |
| Intel I210 Gigabit Network Connection                                  | 3        | 2.63%   |
| Intel Ethernet Controller I225-V                                       | 3        | 2.63%   |
| Intel Ethernet Connection (2) I219-LM                                  | 3        | 2.63%   |
| Intel 82579V Gigabit Network Connection                                | 3        | 2.63%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 2        | 1.75%   |
| Intel Ethernet Controller X710 for 10GBASE-T                           | 2        | 1.75%   |
| Intel Ethernet Controller I226-V                                       | 2        | 1.75%   |
| Intel Ethernet Connection (14) I219-LM                                 | 2        | 1.75%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                   | 2        | 1.75%   |
| Intel 82574L Gigabit Network Connection                                | 2        | 1.75%   |
| Insyde Software RNDIS/Ethernet Gadget                                  | 2        | 1.75%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 2        | 1.75%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 1        | 0.88%   |
| Mellanox MT2892 Family [ConnectX-6 Dx]                                 | 1        | 0.88%   |
| Mellanox MT28800 Family [ConnectX-5 Ex]                                | 1        | 0.88%   |
| Mellanox MT27800 Family [ConnectX-5]                                   | 1        | 0.88%   |
| Mellanox MT27710 Family [ConnectX-4 Lx]                                | 1        | 0.88%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 1        | 0.88%   |
| Intel Ethernet Controller E810-C for QSFP                              | 1        | 0.88%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                          | 1        | 0.88%   |
| Intel Ethernet Connection I219-V                                       | 1        | 0.88%   |
| Intel Ethernet Connection I219-LM                                      | 1        | 0.88%   |
| Intel Ethernet Connection I217-LM                                      | 1        | 0.88%   |
| Intel Ethernet Connection (7) I219-V                                   | 1        | 0.88%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1        | 0.88%   |
| Intel Ethernet Connection (5) I219-V                                   | 1        | 0.88%   |
| Intel 82578DM Gigabit Network Connection                               | 1        | 0.88%   |
| Intel 82576 Gigabit Network Connection                                 | 1        | 0.88%   |
| Emulex OneConnect 10Gb NIC (be3)                                       | 1        | 0.88%   |
| Chelsio T320 10GbE Dual Port Adapter                                   | 1        | 0.88%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                     | 1        | 0.88%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 79       | 69.3%   |
| WiFi     | 33       | 28.95%  |
| Modem    | 2        | 1.75%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 63       | 80.77%  |
| WiFi     | 15       | 19.23%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 2     | 31       | 38.27%  |
| 1     | 29       | 35.8%   |
| 3     | 9        | 11.11%  |
| 4     | 6        | 7.41%   |
| 6     | 2        | 2.47%   |
| 0     | 2        | 2.47%   |
| 10    | 1        | 1.23%   |
| 5     | 1        | 1.23%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 60       | 73.17%  |
| Yes  | 22       | 26.83%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 13       | 54.17%  |
| IMC Networks            | 3        | 12.5%   |
| Cambridge Silicon Radio | 2        | 8.33%   |
| Broadcom                | 2        | 8.33%   |
| ASUSTek Computer        | 2        | 8.33%   |
| TP-Link                 | 1        | 4.17%   |
| Realtek Semiconductor   | 1        | 4.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                               | 5        | 20.83%  |
| Intel Bluetooth wireless interface                  | 4        | 16.67%  |
| IMC Networks Bluetooth Radio                        | 3        | 12.5%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2        | 8.33%   |
| TP-Link TP-T@- UB500 Adapter                        | 1        | 4.17%   |
| Realtek Bluetooth Radio                             | 1        | 4.17%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 4.17%   |
| Intel Bluetooth Device                              | 1        | 4.17%   |
| Intel AX210 Bluetooth                               | 1        | 4.17%   |
| Intel AX201 Bluetooth                               | 1        | 4.17%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 4.17%   |
| Broadcom BCM2045 Bluetooth                          | 1        | 4.17%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 4.17%   |
| ASUS ASUS USB-BT500                                 | 1        | 4.17%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 45       | 35.43%  |
| AMD                      | 34       | 26.77%  |
| Nvidia                   | 31       | 24.41%  |
| Micro Star International | 2        | 1.57%   |
| Giga-Byte Technology     | 2        | 1.57%   |
| ASUSTek Computer         | 2        | 1.57%   |
| Yamaha                   | 1        | 0.79%   |
| Plantronics              | 1        | 0.79%   |
| Logitech                 | 1        | 0.79%   |
| Kingston Technology      | 1        | 0.79%   |
| JMTek                    | 1        | 0.79%   |
| Harman International     | 1        | 0.79%   |
| Generalplus Technology   | 1        | 0.79%   |
| Creative Technology      | 1        | 0.79%   |
| Conexant Systems         | 1        | 0.79%   |
| C-Media Electronics      | 1        | 0.79%   |
| Apple                    | 1        | 0.79%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 11       | 7.48%   |
| AMD Ryzen HD Audio Controller                                              | 8        | 5.44%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 6        | 4.08%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 5        | 3.4%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5        | 3.4%    |
| Intel Cannon Lake PCH cAVS                                                 | 4        | 2.72%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4        | 2.72%   |
| Nvidia GF108 High Definition Audio Controller                              | 3        | 2.04%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3        | 2.04%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3        | 2.04%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3        | 2.04%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 3        | 2.04%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 3        | 2.04%   |
| Intel 200 Series PCH HD Audio                                              | 3        | 2.04%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3        | 2.04%   |
| Nvidia TU116 High Definition Audio Controller                              | 2        | 1.36%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2        | 1.36%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 1.36%   |
| Nvidia GP106 High Definition Audio Controller                              | 2        | 1.36%   |
| Nvidia GP104 High Definition Audio Controller                              | 2        | 1.36%   |
| Nvidia GM204 High Definition Audio Controller                              | 2        | 1.36%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2        | 1.36%   |
| Nvidia GA106 High Definition Audio Controller                              | 2        | 1.36%   |
| Micro Star International USB Audio                                         | 2        | 1.36%   |
| Intel Raptor Lake High Definition Audio Controller                         | 2        | 1.36%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2        | 1.36%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2        | 1.36%   |
| Giga-Byte Technology USB Audio                                             | 2        | 1.36%   |
| ASUSTek Computer USB Audio                                                 | 2        | 1.36%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2        | 1.36%   |
| AMD Kabini HDMI/DP Audio                                                   | 2        | 1.36%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                             | 2        | 1.36%   |
| AMD FCH Azalia Controller                                                  | 2        | 1.36%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 2        | 1.36%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2        | 1.36%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2        | 1.36%   |
| Yamaha Steinberg UR44C                                                     | 1        | 0.68%   |
| Plantronics Plantronics Blackwire 320                                      | 1        | 0.68%   |
| Nvidia TU104 HD Audio Controller                                           | 1        | 0.68%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 12       | 24.49%  |
| SK hynix            | 6        | 12.24%  |
| Samsung Electronics | 6        | 12.24%  |
| Micron Technology   | 4        | 8.16%   |
| Unknown             | 3        | 6.12%   |
| G.Skill             | 3        | 6.12%   |
| Crucial             | 3        | 6.12%   |
| Corsair             | 3        | 6.12%   |
| QEMU                | 2        | 4.08%   |
| Apacer              | 2        | 4.08%   |
| Unknown             | 2        | 4.08%   |
| Patriot             | 1        | 2.04%   |
| GLOWAY              | 1        | 2.04%   |
| GeIL                | 1        | 2.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| QEMU RAM Module 8GB DIMM RAM                              | 2        | 3.85%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3733MT/s     | 2        | 3.85%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s     | 2        | 3.85%   |
| Unknown                                                   | 2        | 3.85%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                      | 1        | 1.92%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                      | 1        | 1.92%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                      | 1        | 1.92%   |
| SK hynix RAM HMT42GR7MFR4C 16GB DIMM DDR3 1600MT/s        | 1        | 1.92%   |
| SK hynix RAM HMT351U6AFR8C-H9 4GB DIMM DDR3 1333MT/s      | 1        | 1.92%   |
| SK hynix RAM HMCGM4MEBRB237N 96GB DIMM DDR5 4800MT/s      | 1        | 1.92%   |
| SK hynix RAM HMCG94MEBRA123N 64GB DIMM DDR5 4800MT/s      | 1        | 1.92%   |
| SK hynix RAM HMA82GR7AFR8N-UH 16GB DIMM DDR4 2400MT/s     | 1        | 1.92%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s      | 1        | 1.92%   |
| Samsung RAM Module 16GB DIMM DDR4 2667MT/s                | 1        | 1.92%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s    | 1        | 1.92%   |
| Samsung RAM M393B2G70QH0 16GB DIMM DDR3 1866MT/s          | 1        | 1.92%   |
| Samsung RAM M393A1K43DB1-CVF 8GB DIMM DDR4 2933MT/s       | 1        | 1.92%   |
| Samsung RAM M378A5244CB0-CRC 4GB DIMM DDR4 3066MT/s       | 1        | 1.92%   |
| Samsung RAM M378A4G43MB1-CTD 32GB DIMM DDR4 3466MT/s      | 1        | 1.92%   |
| Patriot RAM 2400C10 Series 8GB DIMM DDR3 1600MT/s         | 1        | 1.92%   |
| Patriot RAM 1600 CL10 Series 8GB DIMM DDR3 1600MT/s       | 1        | 1.92%   |
| Micron RAM 9ASF2G72AZ-3G2B1 16GB DIMM DDR4 3200MT/s       | 1        | 1.92%   |
| Micron RAM 8KTF25664HZ-1G6M 2GB SODIMM DDR3 1066MT/s      | 1        | 1.92%   |
| Micron RAM 8JSF25664HZ-1G4D 2GB SODIMM DDR3 1066MT/s      | 1        | 1.92%   |
| Micron RAM 36KSF2G72PZ-1G6E1 16GB DIMM DDR3 1600MT/s      | 1        | 1.92%   |
| Micron RAM 36ASF2G72PZ-2G1A2 16GB DIMM DDR4 2400MT/s      | 1        | 1.92%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s      | 1        | 1.92%   |
| Kingston RAM KHX2400C15D4/4G 4GB DIMM DDR4 3151MT/s       | 1        | 1.92%   |
| Kingston RAM KF560R32-32 32GB DIMM DDR5 4800MT/s          | 1        | 1.92%   |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3933MT/s     | 1        | 1.92%   |
| Kingston RAM ACR256X64D3U1333C9 2GB DIMM DDR3 1333MT/s    | 1        | 1.92%   |
| Kingston RAM 99U5458-005.A01LF 4GB DIMM DDR3 1333MT/s     | 1        | 1.92%   |
| Kingston RAM 9965754-006.C00G 16GB DIMM DDR4 3200MT/s     | 1        | 1.92%   |
| Kingston RAM 9965516-189.A 16GB DIMM DDR3 1600MT/s        | 1        | 1.92%   |
| Kingston RAM 9905702-017.A00G 8GB DIMM DDR4 2933MT/s      | 1        | 1.92%   |
| Kingston RAM 9905624-026.A00G 8GB SODIMM DDR4 2400MT/s    | 1        | 1.92%   |
| Kingston RAM 9905458-013.A00LF 4GB DIMM DDR3 1333MT/s     | 1        | 1.92%   |
| GLOWAY RAM VGM4SX32C22AG-SWARNN 16GB SODIMM DDR4 3200MT/s | 1        | 1.92%   |
| GeIL RAM CL11-11-11 D3-1600 4GB DIMM 1866MT/s             | 1        | 1.92%   |
| G.Skill RAM F4-4000C15-8GVK 8GB DIMM DDR4 2133MT/s        | 1        | 1.92%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 21       | 50%     |
| DDR3    | 12       | 28.57%  |
| DDR5    | 3        | 7.14%   |
| Unknown | 3        | 7.14%   |
| RAM     | 2        | 4.76%   |
| DRAM    | 1        | 2.38%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 38       | 90.48%  |
| SODIMM | 4        | 9.52%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 17       | 37.78%  |
| 16384 | 12       | 26.67%  |
| 4096  | 8        | 17.78%  |
| 32768 | 4        | 8.89%   |
| 2048  | 2        | 4.44%   |
| 98304 | 1        | 2.22%   |
| 65536 | 1        | 2.22%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 8        | 17.02%  |
| 1600    | 8        | 17.02%  |
| 2400    | 4        | 8.51%   |
| 1333    | 4        | 8.51%   |
| 4800    | 3        | 6.38%   |
| 3733    | 3        | 6.38%   |
| 2933    | 2        | 4.26%   |
| 2667    | 2        | 4.26%   |
| 1866    | 2        | 4.26%   |
| 1066    | 2        | 4.26%   |
| Unknown | 2        | 4.26%   |
| 3933    | 1        | 2.13%   |
| 3466    | 1        | 2.13%   |
| 3151    | 1        | 2.13%   |
| 3066    | 1        | 2.13%   |
| 2133    | 1        | 2.13%   |
| 1867    | 1        | 2.13%   |
| 800     | 1        | 2.13%   |

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


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Logitech                 | 5        | 33.33%  |
| Microsoft                | 2        | 13.33%  |
| Microdia                 | 2        | 13.33%  |
| XIFT                     | 1        | 6.67%   |
| Realtek Semiconductor    | 1        | 6.67%   |
| Novatek Microelectronics | 1        | 6.67%   |
| MacroSilicon             | 1        | 6.67%   |
| Creative Technology      | 1        | 6.67%   |
| Apple                    | 1        | 6.67%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Logitech Webcam C270                | 3        | 20%     |
| XIFT Web Camera                     | 1        | 6.67%   |
| Realtek USB Camera                  | 1        | 6.67%   |
| Novatek USB Camera                  | 1        | 6.67%   |
| Microsoft LifeCam VX-700            | 1        | 6.67%   |
| Microsoft LifeCam HD-3000           | 1        | 6.67%   |
| Microdia USB 2.0 Camera             | 1        | 6.67%   |
| Microdia Integrated Camera          | 1        | 6.67%   |
| MacroSilicon USB Video              | 1        | 6.67%   |
| Logitech Webcam B500                | 1        | 6.67%   |
| Logitech HD Pro Webcam C920         | 1        | 6.67%   |
| Creative Live! Cam Chat HD [VF0700] | 1        | 6.67%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X     | 1        | 6.67%   |

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
| 0     | 55       | 67.07%  |
| 1     | 21       | 25.61%  |
| 2     | 3        | 3.66%   |
| 5     | 2        | 2.44%   |
| 3     | 1        | 1.22%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 11       | 31.43%  |
| Net/wireless             | 6        | 17.14%  |
| Sound                    | 3        | 8.57%   |
| Unassigned class         | 2        | 5.71%   |
| Storage/raid             | 2        | 5.71%   |
| Network                  | 2        | 5.71%   |
| Net/ethernet             | 2        | 5.71%   |
| Firewire controller      | 2        | 5.71%   |
| Communication controller | 2        | 5.71%   |
| Storage/ide              | 1        | 2.86%   |
| Multimedia controller    | 1        | 2.86%   |
| Bluetooth                | 1        | 2.86%   |

