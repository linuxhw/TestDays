RHEL - Tested Hardware & Statistics (Desktops)
----------------------------------------------

A project to collect tested hardware configurations for RHEL.

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

Total: 179

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | 01G0M6 A02                  | [9018a2ac09](https://linux-hardware.org/?probe=9018a2ac09) | Jan 06, 2025 |
| ASRock        | X570 Steel Legend           | [2b29fc224e](https://linux-hardware.org/?probe=2b29fc224e) | Jan 04, 2025 |
| Gigabyte      | B550M DS3H                  | [675c306b51](https://linux-hardware.org/?probe=675c306b51) | Jan 03, 2025 |
| MSI           | MPG B550 GAMING PLUS        | [8c9e4bdd75](https://linux-hardware.org/?probe=8c9e4bdd75) | Dec 26, 2024 |
| ASRock        | X570 Steel Legend           | [eab49b95cc](https://linux-hardware.org/?probe=eab49b95cc) | Dec 24, 2024 |
| Dell          | 0HHV7N A00                  | [36a5d324c6](https://linux-hardware.org/?probe=36a5d324c6) | Nov 20, 2024 |
| Dell          | 0HHV7N A00                  | [2724eb028f](https://linux-hardware.org/?probe=2724eb028f) | Nov 20, 2024 |
| ASRock        | X570 Steel Legend           | [5b8dc636f4](https://linux-hardware.org/?probe=5b8dc636f4) | Nov 16, 2024 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [087f372f3b](https://linux-hardware.org/?probe=087f372f3b) | Nov 16, 2024 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [28e20675ef](https://linux-hardware.org/?probe=28e20675ef) | Nov 16, 2024 |
| ASRock        | H310CM-HG4                  | [947520025d](https://linux-hardware.org/?probe=947520025d) | Nov 12, 2024 |
| ASRock        | H310CM-HG4                  | [11021e8d32](https://linux-hardware.org/?probe=11021e8d32) | Nov 12, 2024 |
| ASRock        | H310CM-HG4                  | [63b0d341db](https://linux-hardware.org/?probe=63b0d341db) | Nov 12, 2024 |
| Dell          | 0HHV7N A00                  | [dac9fa757b](https://linux-hardware.org/?probe=dac9fa757b) | Oct 09, 2024 |
| HP            | 8949 11                     | [e10c4e5057](https://linux-hardware.org/?probe=e10c4e5057) | Oct 02, 2024 |
| MSI           | H310M PRO-VD                | [7a1624219e](https://linux-hardware.org/?probe=7a1624219e) | Sep 07, 2024 |
| Supermicro    | X9DAi                       | [f84f7e7927](https://linux-hardware.org/?probe=f84f7e7927) | Sep 01, 2024 |
| ASRock        | B450 Pro4                   | [fe4942ef99](https://linux-hardware.org/?probe=fe4942ef99) | Aug 16, 2024 |
| HP            | 859C                        | [4797f69707](https://linux-hardware.org/?probe=4797f69707) | Jul 23, 2024 |
| Supermicro    | X10DRH-CT                   | [dd4b138c6e](https://linux-hardware.org/?probe=dd4b138c6e) | Jun 27, 2024 |
| Dell          | 0MWYPT A01                  | [4e18ec8df0](https://linux-hardware.org/?probe=4e18ec8df0) | May 15, 2024 |
| MSI           | MPG X570S CARBON MAX WIF... | [c5ad34b5f5](https://linux-hardware.org/?probe=c5ad34b5f5) | May 14, 2024 |
| ASUSTek       | ROG STRIX Z590-A GAMING ... | [fba3144c06](https://linux-hardware.org/?probe=fba3144c06) | May 06, 2024 |
| MSI           | MEG Z790 ACE MAX            | [b10bbe2874](https://linux-hardware.org/?probe=b10bbe2874) | Apr 22, 2024 |
| Dell          | 07WP95 A02                  | [46e0a9d4d4](https://linux-hardware.org/?probe=46e0a9d4d4) | Apr 15, 2024 |
| CX / Air C... | CX-H87-M1                   | [6ca85693a6](https://linux-hardware.org/?probe=6ca85693a6) | Apr 12, 2024 |
| ASUSTek       | G16CH                       | [04a245fffe](https://linux-hardware.org/?probe=04a245fffe) | Apr 11, 2024 |
| ASRock        | X570 Creator                | [53aae5d4cb](https://linux-hardware.org/?probe=53aae5d4cb) | Apr 07, 2024 |
| ASRock        | X399 Taichi                 | [c57b1d4302](https://linux-hardware.org/?probe=c57b1d4302) | Apr 04, 2024 |
| ASRock        | X399 Taichi                 | [0f04c10bfa](https://linux-hardware.org/?probe=0f04c10bfa) | Apr 02, 2024 |
| HP            | 212A                        | [4a6e30808e](https://linux-hardware.org/?probe=4a6e30808e) | Mar 12, 2024 |
| Dell          | 06JWJY A00                  | [f1c6a0f9dd](https://linux-hardware.org/?probe=f1c6a0f9dd) | Mar 06, 2024 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [23c12f49f6](https://linux-hardware.org/?probe=23c12f49f6) | Jan 27, 2024 |
| Intel         | DQ77MK AAG39642-400         | [6d4d5ee6c7](https://linux-hardware.org/?probe=6d4d5ee6c7) | Jan 25, 2024 |
| Gigabyte      | B550M AORUS PRO-P           | [cb116dae9c](https://linux-hardware.org/?probe=cb116dae9c) | Jan 20, 2024 |
| MSI           | PRO Z690-A DDR4             | [55f164e414](https://linux-hardware.org/?probe=55f164e414) | Dec 20, 2023 |
| MSI           | PRO Z690-A DDR4             | [b758a439b8](https://linux-hardware.org/?probe=b758a439b8) | Dec 20, 2023 |
| ASUSTek       | ROG Maximus Z790 HERO       | [c492be4899](https://linux-hardware.org/?probe=c492be4899) | Dec 04, 2023 |
| Dell          | 0X8DXD A00                  | [bc58f50ac6](https://linux-hardware.org/?probe=bc58f50ac6) | Nov 22, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [367bde5a11](https://linux-hardware.org/?probe=367bde5a11) | Nov 03, 2023 |
| ASUSTek       | PRIME Z690-A                | [e356c02979](https://linux-hardware.org/?probe=e356c02979) | Oct 30, 2023 |
| ASUSTek       | ROG Maximus XII APEX        | [2ed4b6b711](https://linux-hardware.org/?probe=2ed4b6b711) | Oct 24, 2023 |
| HP            | ProLiant ML310e Gen8        | [79f6aee2c7](https://linux-hardware.org/?probe=79f6aee2c7) | Oct 24, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [ff1efba80e](https://linux-hardware.org/?probe=ff1efba80e) | Sep 13, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [c190907cc8](https://linux-hardware.org/?probe=c190907cc8) | Aug 29, 2023 |
| ASUSTek       | STRIX Z270E GAMING          | [e5b049be3a](https://linux-hardware.org/?probe=e5b049be3a) | Aug 18, 2023 |
| ASRock        | A320M-HDV R4.0              | [f88687d2f0](https://linux-hardware.org/?probe=f88687d2f0) | Aug 15, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [f6892c6532](https://linux-hardware.org/?probe=f6892c6532) | Aug 15, 2023 |
| ASUSTek       | ROG Maximus X HERO          | [d5d888506b](https://linux-hardware.org/?probe=d5d888506b) | Aug 10, 2023 |
| ASRock        | A320M-HDV R4.0              | [eb99d95702](https://linux-hardware.org/?probe=eb99d95702) | Aug 08, 2023 |
| ASRock        | A320M-HDV R4.0              | [de07e937bb](https://linux-hardware.org/?probe=de07e937bb) | Aug 04, 2023 |
| HP            | 0AECh D                     | [b9ea790e39](https://linux-hardware.org/?probe=b9ea790e39) | Jul 24, 2023 |
| HP            | 0AECh D                     | [078f0cd045](https://linux-hardware.org/?probe=078f0cd045) | Jul 24, 2023 |
| MSI           | Z270-A PRO                  | [0d8b3d7c32](https://linux-hardware.org/?probe=0d8b3d7c32) | Jun 20, 2023 |
| Dell          | 07T4MC A02                  | [ad310dd147](https://linux-hardware.org/?probe=ad310dd147) | Jun 09, 2023 |
| Dell          | 0HHV7N A00                  | [a3a157f327](https://linux-hardware.org/?probe=a3a157f327) | May 21, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [2afc4ee693](https://linux-hardware.org/?probe=2afc4ee693) | May 18, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [b1ea93c5fa](https://linux-hardware.org/?probe=b1ea93c5fa) | May 09, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [18c5e3c7c3](https://linux-hardware.org/?probe=18c5e3c7c3) | Apr 10, 2023 |
| MSI           | B450M MORTAR MAX            | [0077b88576](https://linux-hardware.org/?probe=0077b88576) | Apr 06, 2023 |
| Gigabyte      | X670E AORUS MASTER          | [68731ac4ec](https://linux-hardware.org/?probe=68731ac4ec) | Mar 31, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | [898059efa5](https://linux-hardware.org/?probe=898059efa5) | Mar 28, 2023 |
| MSI           | B450M MORTAR MAX            | [29c85678af](https://linux-hardware.org/?probe=29c85678af) | Mar 28, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | [1821e3657a](https://linux-hardware.org/?probe=1821e3657a) | Mar 26, 2023 |
| MSI           | B450M MORTAR MAX            | [641481dd1d](https://linux-hardware.org/?probe=641481dd1d) | Mar 21, 2023 |
| MSI           | B450M MORTAR MAX            | [9d859cb8bd](https://linux-hardware.org/?probe=9d859cb8bd) | Mar 20, 2023 |
| Gigabyte      | X570 UD                     | [12d8200114](https://linux-hardware.org/?probe=12d8200114) | Mar 13, 2023 |
| Gigabyte      | H510M H                     | [861b7c5aa7](https://linux-hardware.org/?probe=861b7c5aa7) | Feb 02, 2023 |
| ASUSTek       | PRIME Z590-A                | [f328fab9f1](https://linux-hardware.org/?probe=f328fab9f1) | Jan 27, 2023 |
| Hardkernel    | ODROID-H3                   | [98f5768c61](https://linux-hardware.org/?probe=98f5768c61) | Jan 22, 2023 |
| Unknown       | Unknown                     | [9d66e8f05d](https://linux-hardware.org/?probe=9d66e8f05d) | Dec 25, 2022 |
| Gigabyte      | Z590I VISION D              | [9787630f1c](https://linux-hardware.org/?probe=9787630f1c) | Dec 12, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [af5361313b](https://linux-hardware.org/?probe=af5361313b) | Nov 17, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [2d830dc96d](https://linux-hardware.org/?probe=2d830dc96d) | Nov 11, 2022 |
| HP            | 8591                        | [98bde1bd5a](https://linux-hardware.org/?probe=98bde1bd5a) | Nov 01, 2022 |
| Gigabyte      | Z590I VISION D              | [22131a6ec5](https://linux-hardware.org/?probe=22131a6ec5) | Sep 03, 2022 |
| Acer          | Aspire XC-330               | [2012033d09](https://linux-hardware.org/?probe=2012033d09) | Aug 14, 2022 |
| Unknown       | Unknown                     | [fad6d4558f](https://linux-hardware.org/?probe=fad6d4558f) | Jul 26, 2022 |
| Intel         | H81                         | [e1a730a6e6](https://linux-hardware.org/?probe=e1a730a6e6) | Jul 08, 2022 |
| Unknown       | Unknown                     | [16c6df7b29](https://linux-hardware.org/?probe=16c6df7b29) | Jul 07, 2022 |
| Unknown       | Unknown                     | [6b25430dc1](https://linux-hardware.org/?probe=6b25430dc1) | Jul 07, 2022 |
| Dell          | 02K9CR A03                  | [5656d7a0d5](https://linux-hardware.org/?probe=5656d7a0d5) | May 27, 2022 |
| Dell          | 0N4YC8 A00                  | [74525891a0](https://linux-hardware.org/?probe=74525891a0) | May 26, 2022 |
| ASRock        | Z370 Professional Gaming... | [658347ec76](https://linux-hardware.org/?probe=658347ec76) | May 12, 2022 |
| Lenovo        | 3132 SDK0K17763 WIN 1801... | [a6e43346ba](https://linux-hardware.org/?probe=a6e43346ba) | Apr 16, 2022 |
| ASUSTek       | X99-DELUXE II               | [82939dc69f](https://linux-hardware.org/?probe=82939dc69f) | Apr 05, 2022 |
| CX / Air C... | CX-H87-M1                   | [ddfbf2df5e](https://linux-hardware.org/?probe=ddfbf2df5e) | Apr 01, 2022 |
| CX / Air C... | CX-H87-M1                   | [5a8ee938ce](https://linux-hardware.org/?probe=5a8ee938ce) | Apr 01, 2022 |
| ASRock        | X99E-ITX/ac                 | [0cf67f0201](https://linux-hardware.org/?probe=0cf67f0201) | Mar 06, 2022 |
| ASRock        | X570 Steel Legend           | [e7843ce1cf](https://linux-hardware.org/?probe=e7843ce1cf) | Mar 05, 2022 |
| ASUSTek       | Maximus VII FORMULA         | [7fd2e4885c](https://linux-hardware.org/?probe=7fd2e4885c) | Mar 05, 2022 |
| Gigabyte      | B150-HD3-CF                 | [cab21caab7](https://linux-hardware.org/?probe=cab21caab7) | Feb 10, 2022 |
| ASUSTek       | Maximus VII FORMULA         | [36c52eaf3d](https://linux-hardware.org/?probe=36c52eaf3d) | Feb 05, 2022 |
| ASUSTek       | Maximus VII FORMULA         | [07de603a4a](https://linux-hardware.org/?probe=07de603a4a) | Jan 31, 2022 |
| Gigabyte      | Z97N-WIFI                   | [5808f89618](https://linux-hardware.org/?probe=5808f89618) | Jan 07, 2022 |
| ASUSTek       | PRIME B360M-D               | [e3b3ac9f8b](https://linux-hardware.org/?probe=e3b3ac9f8b) | Jan 01, 2022 |
| Lenovo        | MAHOBAY                     | [ea1413bf9e](https://linux-hardware.org/?probe=ea1413bf9e) | Nov 19, 2021 |
| HP            | ProLiant MicroServer Gen... | [0178a25382](https://linux-hardware.org/?probe=0178a25382) | Nov 18, 2021 |
| ASUSTek       | PRIME B350M-A               | [d3d69e7587](https://linux-hardware.org/?probe=d3d69e7587) | Oct 24, 2021 |
| ASUSTek       | Pro WS X570-ACE             | [07a5b3c465](https://linux-hardware.org/?probe=07a5b3c465) | Oct 16, 2021 |
| ASUSTek       | PRIME B350M-A               | [66cd9bb2c9](https://linux-hardware.org/?probe=66cd9bb2c9) | Oct 09, 2021 |
| ASUSTek       | Z87-DELUXE                  | [63b48dfa23](https://linux-hardware.org/?probe=63b48dfa23) | Oct 07, 2021 |
| HP            | 212B                        | [322371cc6a](https://linux-hardware.org/?probe=322371cc6a) | Oct 04, 2021 |
| ASUSTek       | Z87-DELUXE                  | [2792a3ef1c](https://linux-hardware.org/?probe=2792a3ef1c) | Oct 03, 2021 |
| Gigabyte      | Z97N-WIFI                   | [539316ac91](https://linux-hardware.org/?probe=539316ac91) | Sep 30, 2021 |
| Gigabyte      | Z97N-WIFI                   | [95ae5d0e04](https://linux-hardware.org/?probe=95ae5d0e04) | Sep 29, 2021 |
| Lenovo        | MAHOBAY                     | [fc498b8cb0](https://linux-hardware.org/?probe=fc498b8cb0) | Sep 10, 2021 |
| ASUSTek       | PRIME B350M-A               | [35fa4b96f4](https://linux-hardware.org/?probe=35fa4b96f4) | Sep 09, 2021 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | [f7bcc3d753](https://linux-hardware.org/?probe=f7bcc3d753) | Aug 25, 2021 |
| Gigabyte      | 970A-D3                     | [d62c66d9bd](https://linux-hardware.org/?probe=d62c66d9bd) | Aug 12, 2021 |
| Gigabyte      | Z490 GAMING X               | [a540fa2f59](https://linux-hardware.org/?probe=a540fa2f59) | Jul 19, 2021 |
| Dell          | 0MWYPT A02                  | [ab6e7450c3](https://linux-hardware.org/?probe=ab6e7450c3) | Jul 01, 2021 |
| Intel         | DX79SR AAG57199-200         | [380f10f479](https://linux-hardware.org/?probe=380f10f479) | Jun 10, 2021 |
| HP            | 1906                        | [bf20783dee](https://linux-hardware.org/?probe=bf20783dee) | Jun 02, 2021 |
| Gigabyte      | B85M-D3V-A                  | [4405336208](https://linux-hardware.org/?probe=4405336208) | Jun 01, 2021 |
| MSI           | MPG Z390 GAMING PLUS        | [2eebd180f8](https://linux-hardware.org/?probe=2eebd180f8) | May 28, 2021 |
| HP            | 2129                        | [3991895525](https://linux-hardware.org/?probe=3991895525) | May 23, 2021 |
| MSI           | Z77A-G45                    | [9b11ff6d26](https://linux-hardware.org/?probe=9b11ff6d26) | May 22, 2021 |
| MSI           | Z77A-G45                    | [bd980d04be](https://linux-hardware.org/?probe=bd980d04be) | May 22, 2021 |
| ASUSTek       | ROG Maximus X HERO          | [4a38b848dd](https://linux-hardware.org/?probe=4a38b848dd) | May 19, 2021 |
| HP            | 8054                        | [cf6b804c19](https://linux-hardware.org/?probe=cf6b804c19) | May 13, 2021 |
| ASRock        | X99E-ITX/ac                 | [9cacd1608e](https://linux-hardware.org/?probe=9cacd1608e) | May 08, 2021 |
| ASUSTek       | PRIME B360M-D               | [3dce7dc37d](https://linux-hardware.org/?probe=3dce7dc37d) | Mar 20, 2021 |
| ASRock        | A300M-STX                   | [22c97ac8b2](https://linux-hardware.org/?probe=22c97ac8b2) | Feb 27, 2021 |
| Dell          | 0NNNCT A01                  | [3f081f03fe](https://linux-hardware.org/?probe=3f081f03fe) | Feb 22, 2021 |
| Dell          | PowerEdge FC630             | [98ea3e97e6](https://linux-hardware.org/?probe=98ea3e97e6) | Jan 25, 2021 |
| Dell          | PowerEdge FC630             | [2da05b98bf](https://linux-hardware.org/?probe=2da05b98bf) | Jan 25, 2021 |
| ASUSTek       | ROG Maximus X HERO          | [d0ac809f8a](https://linux-hardware.org/?probe=d0ac809f8a) | Jan 15, 2021 |
| Dell          | PowerEdge FC630             | [038ccd7256](https://linux-hardware.org/?probe=038ccd7256) | Jan 15, 2021 |
| Dell          | PowerEdge FC630             | [f0441f0a07](https://linux-hardware.org/?probe=f0441f0a07) | Jan 15, 2021 |
| Dell          | PowerEdge FC630             | [3c396f0b59](https://linux-hardware.org/?probe=3c396f0b59) | Jan 15, 2021 |
| Dell          | PowerEdge FC630             | [ab4ea06f29](https://linux-hardware.org/?probe=ab4ea06f29) | Jan 15, 2021 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [e10979867d](https://linux-hardware.org/?probe=e10979867d) | Jan 13, 2021 |
| ASUSTek       | H87M-PLUS                   | [95389bff49](https://linux-hardware.org/?probe=95389bff49) | Jan 13, 2021 |
| ASRock        | H270 Pro4                   | [3a3b83a6ed](https://linux-hardware.org/?probe=3a3b83a6ed) | Jan 07, 2021 |
| Unknown       | SKYBAY                      | [d99f937c68](https://linux-hardware.org/?probe=d99f937c68) | Dec 12, 2020 |
| HP            | 1905                        | [6690d08a07](https://linux-hardware.org/?probe=6690d08a07) | Dec 04, 2020 |
| Dell          | 082WXT A01                  | [8d9240a29c](https://linux-hardware.org/?probe=8d9240a29c) | Nov 19, 2020 |
| Dell          | 082WXT A01                  | [0a2176308f](https://linux-hardware.org/?probe=0a2176308f) | Nov 17, 2020 |
| HP            | 81B4                        | [12ac27dcb5](https://linux-hardware.org/?probe=12ac27dcb5) | Nov 14, 2020 |
| HP            | 81B4                        | [faf7b737fe](https://linux-hardware.org/?probe=faf7b737fe) | Nov 14, 2020 |
| MSI           | H310M PRO-VD                | [18c316813f](https://linux-hardware.org/?probe=18c316813f) | Nov 11, 2020 |
| HP            | 1905                        | [0e53545ff8](https://linux-hardware.org/?probe=0e53545ff8) | Oct 14, 2020 |
| ASUSTek       | Z10PE-D16 WS                | [7bf945cd18](https://linux-hardware.org/?probe=7bf945cd18) | Oct 13, 2020 |
| HP            | 1905                        | [48fd57f60f](https://linux-hardware.org/?probe=48fd57f60f) | Sep 24, 2020 |
| HP            | 1905                        | [0e2d6062d9](https://linux-hardware.org/?probe=0e2d6062d9) | Sep 24, 2020 |
| HP            | 843F                        | [6f9898a049](https://linux-hardware.org/?probe=6f9898a049) | Sep 24, 2020 |
| HP            | 843F                        | [91498f153e](https://linux-hardware.org/?probe=91498f153e) | Sep 18, 2020 |
| HP            | 843F                        | [e0bdf38c8a](https://linux-hardware.org/?probe=e0bdf38c8a) | Jul 16, 2020 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [b9a88cd7cf](https://linux-hardware.org/?probe=b9a88cd7cf) | Jun 13, 2020 |
| ASUSTek       | P8Z77-V PRO                 | [b97f2eb31f](https://linux-hardware.org/?probe=b97f2eb31f) | May 20, 2020 |
| HP            | 158A                        | [344194646f](https://linux-hardware.org/?probe=344194646f) | May 14, 2020 |
| Dell          | 00V62H A01                  | [220c6fdf1c](https://linux-hardware.org/?probe=220c6fdf1c) | May 13, 2020 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [6237c4cae4](https://linux-hardware.org/?probe=6237c4cae4) | May 10, 2020 |
| ASRockRack    | EP2C612 WS                  | [9657b92263](https://linux-hardware.org/?probe=9657b92263) | Apr 14, 2020 |
| Gigabyte      | B75-D3V                     | [73b3145cb4](https://linux-hardware.org/?probe=73b3145cb4) | Apr 10, 2020 |
| ASRockRack    | EP2C612 WS                  | [8dad315eb5](https://linux-hardware.org/?probe=8dad315eb5) | Apr 07, 2020 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [848a63637f](https://linux-hardware.org/?probe=848a63637f) | Apr 01, 2020 |
| Alienware     | 0VDT73 A00                  | [00cc8f89dc](https://linux-hardware.org/?probe=00cc8f89dc) | Mar 17, 2020 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [a018f0a4d4](https://linux-hardware.org/?probe=a018f0a4d4) | Feb 27, 2020 |
| Lenovo        | ThinkCentre M91p 0266RZ1    | [ce36caf100](https://linux-hardware.org/?probe=ce36caf100) | Feb 18, 2020 |
| Lenovo        | ThinkCentre M91p 0266RZ1    | [13d8453be0](https://linux-hardware.org/?probe=13d8453be0) | Feb 18, 2020 |
| MSI           | B350M MORTAR                | [9496a3ac2c](https://linux-hardware.org/?probe=9496a3ac2c) | Feb 10, 2020 |
| ASUSTek       | P8Z77-V PRO                 | [0a9570ceaf](https://linux-hardware.org/?probe=0a9570ceaf) | Jan 29, 2020 |
| Dell          | 0XR1GT A00                  | [319aa86f81](https://linux-hardware.org/?probe=319aa86f81) | Jan 25, 2020 |
| Dell          | 0XR1GT A00                  | [189883a0aa](https://linux-hardware.org/?probe=189883a0aa) | Jan 25, 2020 |
| ASUSTek       | PRIME X470-PRO              | [bfacbe4d23](https://linux-hardware.org/?probe=bfacbe4d23) | Jan 18, 2020 |
| MSI           | B350M MORTAR                | [f53a75b96e](https://linux-hardware.org/?probe=f53a75b96e) | Jan 10, 2020 |
| ASUSTek       | P8Z77-V PRO                 | [6bffc36e6a](https://linux-hardware.org/?probe=6bffc36e6a) | Jan 06, 2020 |
| ASRock        | H91M-PLUS                   | [c90d6b4c4d](https://linux-hardware.org/?probe=c90d6b4c4d) | Dec 30, 2019 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [fff26d5712](https://linux-hardware.org/?probe=fff26d5712) | Dec 21, 2019 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [199fad181e](https://linux-hardware.org/?probe=199fad181e) | Nov 29, 2019 |
| Dell          | 0G919G A00                  | [bdf53b02dc](https://linux-hardware.org/?probe=bdf53b02dc) | Nov 18, 2019 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [6a11247e37](https://linux-hardware.org/?probe=6a11247e37) | Nov 11, 2019 |
| Supermicro    | X7DWN+                      | [505e506351](https://linux-hardware.org/?probe=505e506351) | Oct 26, 2019 |
| Supermicro    | X7DWN+                      | [5ad617d6ad](https://linux-hardware.org/?probe=5ad617d6ad) | Oct 25, 2019 |
| Dell          | 0HHV7N A00                  | [9e55c4bdee](https://linux-hardware.org/?probe=9e55c4bdee) | Apr 05, 2019 |
| HP            | 158A                        | [6924d366ab](https://linux-hardware.org/?probe=6924d366ab) | Jan 09, 2019 |
| Dell          | 05DN3X A00                  | [4be9ce0f72](https://linux-hardware.org/?probe=4be9ce0f72) | Dec 20, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| RHEL 8  | 58       | 47.93%  |
| RHEL 9  | 47       | 38.84%  |
| RHEL 7  | 14       | 11.57%  |
| RHEL 6  | 1        | 0.83%   |
| RHEL 10 | 1        | 0.83%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| RHEL | 119      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Desktops | Percent |
|---------------------------------|----------|---------|
| 5.14.0-362.24.1.el9_3.x86_64    | 7        | 5.07%   |
| 4.18.0-305.el8.x86_64           | 7        | 5.07%   |
| 4.18.0-147.3.1.el8_1.x86_64     | 6        | 4.35%   |
| 5.14.0-162.6.1.el9_1.x86_64     | 5        | 3.62%   |
| 5.14.0-362.13.1.el9_3.x86_64    | 4        | 2.9%    |
| 5.14.0-284.11.1.el9_2.x86_64    | 4        | 2.9%    |
| 4.18.0-348.20.1.el8_5.x86_64    | 4        | 2.9%    |
| 4.18.0-305.19.1.el8_4.x86_64    | 4        | 2.9%    |
| 4.18.0-240.1.1.el8_3.x86_64     | 4        | 2.9%    |
| 5.14.0-70.17.1.el9_0.x86_64     | 3        | 2.17%   |
| 5.14.0-284.25.1.el9_2.x86_64    | 3        | 2.17%   |
| 5.14.0-162.22.2.el9_1.x86_64    | 3        | 2.17%   |
| 4.18.0-348.12.2.el8_5.x86_64    | 3        | 2.17%   |
| 4.18.0-240.22.1.el8_3.x86_64    | 3        | 2.17%   |
| 4.18.0-240.10.1.el8_3.x86_64    | 3        | 2.17%   |
| 4.18.0-147.5.1.el8_1.x86_64     | 3        | 2.17%   |
| 3.10.0-862.3.2.el7.x86_64       | 3        | 2.17%   |
| 5.14.0-70.22.1.el9_0.x86_64     | 2        | 1.45%   |
| 5.14.0-503.14.1.el9_5.x86_64    | 2        | 1.45%   |
| 5.14.0-284.30.1.el9_2.x86_64    | 2        | 1.45%   |
| 5.14.0-162.12.1.el9_1.x86_64    | 2        | 1.45%   |
| 4.18.0-348.2.1.el8_5.x86_64     | 2        | 1.45%   |
| 4.18.0-305.10.2.el8_4.x86_64    | 2        | 1.45%   |
| 4.18.0-240.15.1.el8_3.x86_64    | 2        | 1.45%   |
| 4.18.0-193.el8.x86_64           | 2        | 1.45%   |
| 4.18.0-193.6.3.el8_2.x86_64     | 2        | 1.45%   |
| 4.18.0-193.19.1.el8_2.x86_64    | 2        | 1.45%   |
| 4.18.0-147.el8.x86_64           | 2        | 1.45%   |
| 6.11.0-0.rc5.23.el10.x86_64     | 1        | 0.72%   |
| 5.14.0-70.5.1.el9_0.x86_64      | 1        | 0.72%   |
| 5.14.0-503.19.1.el9_5.x86_64+rt | 1        | 0.72%   |
| 5.14.0-427.42.1.el9_4.x86_64    | 1        | 0.72%   |
| 5.14.0-427.37.1.el9_4.x86_64    | 1        | 0.72%   |
| 5.14.0-427.31.1.el9_4.x86_64    | 1        | 0.72%   |
| 5.14.0-427.22.1.el9_4.x86_64    | 1        | 0.72%   |
| 5.14.0-427.16.1.el9_4.x86_64    | 1        | 0.72%   |
| 5.14.0-427.13.1.el9_4.x86_64    | 1        | 0.72%   |
| 5.14.0-362.8.1.el9_3.x86_64     | 1        | 0.72%   |
| 5.14.0-362.18.1.el9_3.x86_64    | 1        | 0.72%   |
| 5.14.0-284.18.1.el9_2.x86_64    | 1        | 0.72%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 4.18.0   | 56       | 46.28%  |
| 5.14.0   | 47       | 38.84%  |
| 3.10.0   | 14       | 11.57%  |
| 6.11.0   | 1        | 0.83%   |
| 5.10.6   | 1        | 0.83%   |
| 4.19.150 | 1        | 0.83%   |
| 2.6.32   | 1        | 0.83%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.18    | 56       | 46.28%  |
| 5.14    | 47       | 38.84%  |
| 3.10    | 14       | 11.57%  |
| 6.11    | 1        | 0.83%   |
| 5.10    | 1        | 0.83%   |
| 4.19    | 1        | 0.83%   |
| 2.6     | 1        | 0.83%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 119      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 90       | 73.17%  |
| Unknown       | 17       | 13.82%  |
| KDE5          | 5        | 4.07%   |
| GNOME Classic | 4        | 3.25%   |
| MATE          | 2        | 1.63%   |
| KDE           | 2        | 1.63%   |
| X-Cinnamon    | 1        | 0.81%   |
| KDE4          | 1        | 0.81%   |
| Cinnamon      | 1        | 0.81%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 59       | 47.97%  |
| X11     | 53       | 43.09%  |
| Unknown | 8        | 6.5%    |
| Tty     | 3        | 2.44%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 78       | 63.93%  |
| GDM     | 39       | 31.97%  |
| SDDM    | 3        | 2.46%   |
| LightDM | 2        | 1.64%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 66       | 55%     |
| Unknown | 14       | 11.67%  |
| en_GB   | 7        | 5.83%   |
| en_IN   | 5        | 4.17%   |
| ru_RU   | 3        | 2.5%    |
| pl_PL   | 3        | 2.5%    |
| en_NZ   | 3        | 2.5%    |
| pt_BR   | 2        | 1.67%   |
| es_ES   | 2        | 1.67%   |
| es_AR   | 2        | 1.67%   |
| de_DE   | 2        | 1.67%   |
| C       | 2        | 1.67%   |
| sl_SI   | 1        | 0.83%   |
| ko_KR   | 1        | 0.83%   |
| ja_JP   | 1        | 0.83%   |
| fr_CA   | 1        | 0.83%   |
| es_MX   | 1        | 0.83%   |
| en_ZA   | 1        | 0.83%   |
| en_CA   | 1        | 0.83%   |
| en_AU   | 1        | 0.83%   |
| cs_CZ   | 1        | 0.83%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 78       | 65%     |
| BIOS | 42       | 35%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Xfs     | 108      | 90%     |
| Ext4    | 9        | 7.5%    |
| Unknown | 3        | 2.5%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 63       | 51.64%  |
| GPT     | 45       | 36.89%  |
| MBR     | 14       | 11.48%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 97       | 80.83%  |
| Yes       | 23       | 19.17%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 106      | 88.33%  |
| Yes       | 14       | 11.67%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 25       | 21.01%  |
| Dell                | 24       | 20.17%  |
| Hewlett-Packard     | 15       | 12.61%  |
| Gigabyte Technology | 14       | 11.76%  |
| MSI                 | 12       | 10.08%  |
| ASRock              | 11       | 9.24%   |
| Lenovo              | 4        | 3.36%   |
| Unknown             | 4        | 3.36%   |
| Supermicro          | 3        | 2.52%   |
| Intel               | 3        | 2.52%   |
| Hardkernel          | 1        | 0.84%   |
| CX / Air Computers. | 1        | 0.84%   |
| Alienware           | 1        | 0.84%   |
| Acer                | 1        | 0.84%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| Dell PowerEdge FC630                | 6        | 5.04%   |
| ASUS All Series                     | 4        | 3.36%   |
| Unknown                             | 4        | 3.36%   |
| Dell Precision Tower 5810           | 3        | 2.52%   |
| HP Z620 Workstation                 | 2        | 1.68%   |
| Gigabyte B550M AORUS PRO-P          | 2        | 1.68%   |
| Dell Precision Tower 3620           | 2        | 1.68%   |
| Dell Precision 5820 Tower           | 2        | 1.68%   |
| Dell OptiPlex 9020                  | 2        | 1.68%   |
| Supermicro X9DAi                    | 1        | 0.84%   |
| Supermicro X7DW3                    | 1        | 0.84%   |
| Supermicro SSG-6028R-E1CR12T        | 1        | 0.84%   |
| MSI MS-7D86                         | 1        | 0.84%   |
| MSI MS-7D54                         | 1        | 0.84%   |
| MSI MS-7D52                         | 1        | 0.84%   |
| MSI MS-7D25                         | 1        | 0.84%   |
| MSI MS-7C95                         | 1        | 0.84%   |
| MSI MS-7C56                         | 1        | 0.84%   |
| MSI MS-7B89                         | 1        | 0.84%   |
| MSI MS-7B51                         | 1        | 0.84%   |
| MSI MS-7B33                         | 1        | 0.84%   |
| MSI MS-7A71                         | 1        | 0.84%   |
| MSI MS-7A37                         | 1        | 0.84%   |
| MSI MS-7752                         | 1        | 0.84%   |
| Lenovo ThinkCentre M92p 3238AZ8     | 1        | 0.84%   |
| Lenovo ThinkCentre M920t 10SFS03200 | 1        | 0.84%   |
| Lenovo ThinkCentre M91p 0266RZ1     | 1        | 0.84%   |
| Lenovo 10SFS03200                   | 1        | 0.84%   |
| Intel H81                           | 1        | 0.84%   |
| Intel DX79SR AAG57199-200           | 1        | 0.84%   |
| Intel DQ77MK AAG39642-400           | 1        | 0.84%   |
| HP Z840 Workstation                 | 1        | 0.84%   |
| HP Z800 Workstation                 | 1        | 0.84%   |
| HP Z440 Workstation                 | 1        | 0.84%   |
| HP Z230 Tower Workstation           | 1        | 0.84%   |
| HP Z230 SFF Workstation             | 1        | 0.84%   |
| HP Z1 Entry Tower G5                | 1        | 0.84%   |
| HP ProLiant ML310e Gen8             | 1        | 0.84%   |
| HP ProLiant MicroServer Gen8        | 1        | 0.84%   |
| HP ProDesk 400 G5 Desktop Mini      | 1        | 0.84%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Dell Precision               | 11       | 9.24%   |
| ASUS ROG                     | 9        | 7.56%   |
| Dell PowerEdge               | 7        | 5.88%   |
| ASUS PRIME                   | 6        | 5.04%   |
| Dell OptiPlex                | 4        | 3.36%   |
| ASUS All                     | 4        | 3.36%   |
| Unknown                      | 4        | 3.36%   |
| Lenovo ThinkCentre           | 3        | 2.52%   |
| Gigabyte B550M               | 3        | 2.52%   |
| HP Z620                      | 2        | 1.68%   |
| HP Z230                      | 2        | 1.68%   |
| HP ProLiant                  | 2        | 1.68%   |
| ASUS TUF                     | 2        | 1.68%   |
| ASRock X570                  | 2        | 1.68%   |
| Supermicro X9DAi             | 1        | 0.84%   |
| Supermicro X7DW3             | 1        | 0.84%   |
| Supermicro SSG-6028R-E1CR12T | 1        | 0.84%   |
| MSI MS-7D86                  | 1        | 0.84%   |
| MSI MS-7D54                  | 1        | 0.84%   |
| MSI MS-7D52                  | 1        | 0.84%   |
| MSI MS-7D25                  | 1        | 0.84%   |
| MSI MS-7C95                  | 1        | 0.84%   |
| MSI MS-7C56                  | 1        | 0.84%   |
| MSI MS-7B89                  | 1        | 0.84%   |
| MSI MS-7B51                  | 1        | 0.84%   |
| MSI MS-7B33                  | 1        | 0.84%   |
| MSI MS-7A71                  | 1        | 0.84%   |
| MSI MS-7A37                  | 1        | 0.84%   |
| MSI MS-7752                  | 1        | 0.84%   |
| Lenovo 10SFS03200            | 1        | 0.84%   |
| Intel H81                    | 1        | 0.84%   |
| Intel DX79SR                 | 1        | 0.84%   |
| Intel DQ77MK                 | 1        | 0.84%   |
| HP Z840                      | 1        | 0.84%   |
| HP Z800                      | 1        | 0.84%   |
| HP Z440                      | 1        | 0.84%   |
| HP Z1                        | 1        | 0.84%   |
| HP ProDesk                   | 1        | 0.84%   |
| HP OMEN                      | 1        | 0.84%   |
| HP EliteDesk                 | 1        | 0.84%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2016 | 17       | 14.29%  |
| 2018 | 14       | 11.76%  |
| 2021 | 13       | 10.92%  |
| 2019 | 13       | 10.92%  |
| 2017 | 12       | 10.08%  |
| 2012 | 10       | 8.4%    |
| 2022 | 7        | 5.88%   |
| 2020 | 7        | 5.88%   |
| 2015 | 6        | 5.04%   |
| 2013 | 6        | 5.04%   |
| 2023 | 4        | 3.36%   |
| 2014 | 4        | 3.36%   |
| 2010 | 2        | 1.68%   |
| 2009 | 2        | 1.68%   |
| 2024 | 1        | 0.84%   |
| 2011 | 1        | 0.84%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 119      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 112      | 93.33%  |
| Enabled  | 8        | 6.67%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 119      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 32.01-64.0      | 31       | 25.2%   |
| 64.01-256.0     | 30       | 24.39%  |
| 8.01-16.0       | 20       | 16.26%  |
| 4.01-8.0        | 13       | 10.57%  |
| 16.01-24.0      | 13       | 10.57%  |
| 24.01-32.0      | 9        | 7.32%   |
| More than 256.0 | 4        | 3.25%   |
| 3.01-4.0        | 2        | 1.63%   |
| 2.01-3.0        | 1        | 0.81%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 39       | 28.68%  |
| 2.01-3.0   | 36       | 26.47%  |
| 8.01-16.0  | 24       | 17.65%  |
| 3.01-4.0   | 20       | 14.71%  |
| 1.01-2.0   | 11       | 8.09%   |
| 16.01-24.0 | 3        | 2.21%   |
| 24.01-32.0 | 1        | 0.74%   |
| 0.51-1.0   | 1        | 0.74%   |
| Unknown    | 1        | 0.74%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 39       | 31.2%   |
| 1      | 28       | 22.4%   |
| 3      | 22       | 17.6%   |
| 5      | 12       | 9.6%    |
| 4      | 11       | 8.8%    |
| 12     | 3        | 2.4%    |
| 6      | 3        | 2.4%    |
| 8      | 2        | 1.6%    |
| 15     | 1        | 0.8%    |
| 14     | 1        | 0.8%    |
| 10     | 1        | 0.8%    |
| 7      | 1        | 0.8%    |
| 0      | 1        | 0.8%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 74       | 61.67%  |
| Yes       | 46       | 38.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 119      | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 61       | 50%     |
| No        | 61       | 50%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 69       | 57.02%  |
| Yes       | 52       | 42.98%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 33       | 27.73%  |
| Germany      | 10       | 8.4%    |
| UK           | 9        | 7.56%   |
| India        | 8        | 6.72%   |
| Canada       | 7        | 5.88%   |
| Czechia      | 5        | 4.2%    |
| Brazil       | 5        | 4.2%    |
| Spain        | 3        | 2.52%   |
| Russia       | 3        | 2.52%   |
| Poland       | 3        | 2.52%   |
| New Zealand  | 3        | 2.52%   |
| Italy        | 3        | 2.52%   |
| Ukraine      | 2        | 1.68%   |
| Switzerland  | 2        | 1.68%   |
| Sweden       | 2        | 1.68%   |
| South Korea  | 2        | 1.68%   |
| Netherlands  | 2        | 1.68%   |
| Argentina    | 2        | 1.68%   |
| Turkmenistan | 1        | 0.84%   |
| South Africa | 1        | 0.84%   |
| Slovenia     | 1        | 0.84%   |
| Mexico       | 1        | 0.84%   |
| Lithuania    | 1        | 0.84%   |
| Japan        | 1        | 0.84%   |
| Indonesia    | 1        | 0.84%   |
| France       | 1        | 0.84%   |
| Finland      | 1        | 0.84%   |
| Egypt        | 1        | 0.84%   |
| China        | 1        | 0.84%   |
| Belgium      | 1        | 0.84%   |
| Belarus      | 1        | 0.84%   |
| Austria      | 1        | 0.84%   |
| Australia    | 1        | 0.84%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Petersberg       | 6        | 4.84%   |
| Prague           | 4        | 3.23%   |
| Wellington       | 2        | 1.61%   |
| Kyiv             | 2        | 1.61%   |
| Chicago          | 2        | 1.61%   |
| Bengaluru        | 2        | 1.61%   |
| Yorktown Heights | 1        | 0.81%   |
| Yongin-si        | 1        | 0.81%   |
| Wildomar         | 1        | 0.81%   |
| Wiesbaden        | 1        | 0.81%   |
| Vienna           | 1        | 0.81%   |
| Valencia         | 1        | 0.81%   |
| Vaglio           | 1        | 0.81%   |
| Turku            | 1        | 0.81%   |
| Toronto          | 1        | 0.81%   |
| Tokyo            | 1        | 0.81%   |
| Tiruchi          | 1        | 0.81%   |
| Tauranga         | 1        | 0.81%   |
| Sutton           | 1        | 0.81%   |
| Sterling Heights | 1        | 0.81%   |
| Stavropol        | 1        | 0.81%   |
| Spokane          | 1        | 0.81%   |
| Spalding         | 1        | 0.81%   |
| Sorel-Tracy      | 1        | 0.81%   |
| Sierra Vista     | 1        | 0.81%   |
| Šiauliai        | 1        | 0.81%   |
| Saratov          | 1        | 0.81%   |
| San Jose         | 1        | 0.81%   |
| San Fernando     | 1        | 0.81%   |
| Salvador         | 1        | 0.81%   |
| Saltillo         | 1        | 0.81%   |
| Sainte-Marie     | 1        | 0.81%   |
| Roseville        | 1        | 0.81%   |
| Rosario          | 1        | 0.81%   |
| Rio de Janeiro   | 1        | 0.81%   |
| Ribeirao Preto   | 1        | 0.81%   |
| Rensselaer       | 1        | 0.81%   |
| Reading          | 1        | 0.81%   |
| Poznan           | 1        | 0.81%   |
| Porto Empedocle  | 1        | 0.81%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| Seagate                      | 41       | 97     | 16.47%  |
| WDC                          | 39       | 78     | 15.66%  |
| Samsung Electronics          | 34       | 70     | 13.65%  |
| Toshiba                      | 14       | 21     | 5.62%   |
| SanDisk                      | 14       | 28     | 5.62%   |
| Kingston                     | 11       | 16     | 4.42%   |
| Intel                        | 8        | 15     | 3.21%   |
| Crucial                      | 8        | 13     | 3.21%   |
| Micron/Crucial Technology    | 6        | 8      | 2.41%   |
| SK hynix                     | 5        | 7      | 2.01%   |
| Phison                       | 5        | 9      | 2.01%   |
| Phison Electronics           | 4        | 5      | 1.61%   |
| Micron Technology            | 4        | 4      | 1.61%   |
| Hitachi                      | 4        | 4      | 1.61%   |
| HGST                         | 4        | 4      | 1.61%   |
| Dell                         | 4        | 8      | 1.61%   |
| A-DATA Technology            | 4        | 4      | 1.61%   |
| Unknown                      | 3        | 6      | 1.2%    |
| PNY                          | 3        | 3      | 1.2%    |
| Gigabyte Technology          | 3        | 4      | 1.2%    |
| China                        | 3        | 3      | 1.2%    |
| Silicon Motion               | 2        | 2      | 0.8%    |
| Corsair                      | 2        | 5      | 0.8%    |
| XUM                          | 1        | 1      | 0.4%    |
| XPG                          | 1        | 1      | 0.4%    |
| Western Digital              | 1        | 1      | 0.4%    |
| Toshiba America Info Systems | 1        | 1      | 0.4%    |
| T-FORCE                      | 1        | 2      | 0.4%    |
| SSK Port                     | 1        | 1      | 0.4%    |
| SPCC                         | 1        | 1      | 0.4%    |
| SCST_FIO                     | 1        | 9      | 0.4%    |
| SABRENT                      | 1        | 1      | 0.4%    |
| Realtek                      | 1        | 1      | 0.4%    |
| OCZ                          | 1        | 2      | 0.4%    |
| Lexar                        | 1        | 1      | 0.4%    |
| KingSpec                     | 1        | 1      | 0.4%    |
| KingFast                     | 1        | 2      | 0.4%    |
| KINGBANK                     | 1        | 1      | 0.4%    |
| Kimtigo                      | 1        | 1      | 0.4%    |
| Inland                       | 1        | 1      | 0.4%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| Samsung SSD 860 EVO 1TB                              | 4        | 1.29%   |
| Dell MD34xx 26TB                                     | 4        | 1.29%   |
| Toshiba DT01ACA200 2TB                               | 3        | 0.97%   |
| Seagate ST2000DM001-1ER164 2TB                       | 3        | 0.97%   |
| Samsung SSD 980 1TB                                  | 3        | 0.97%   |
| Samsung SSD 860 EVO 500GB                            | 3        | 0.97%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 3        | 0.97%   |
| Phison E16 PCIe4 NVMe Controller 1TB                 | 3        | 0.97%   |
| Micron/Crucial P2 NVMe PCIe SSD 500GB                | 3        | 0.97%   |
| HGST HTS721010A9E630 1TB                             | 3        | 0.97%   |
| WDC WD5000AAKX-75U6AA0 500GB                         | 2        | 0.65%   |
| WDC WD40EFRX-68N32N0 4TB                             | 2        | 0.65%   |
| WDC WD4005FZBX-00K5WB0 4TB                           | 2        | 0.65%   |
| WDC WD1003FZEX-00MK2A0 1TB                           | 2        | 0.65%   |
| WDC WD1002FAEX-00Z3A0 1TB                            | 2        | 0.65%   |
| Unknown SD/MMC/MS PRO 128GB                          | 2        | 0.65%   |
| Toshiba NVMe SSD Drive 256GB                         | 2        | 0.65%   |
| Toshiba DT01ACA100 1TB                               | 2        | 0.65%   |
| Toshiba AL14SEB18EQ 1.8TB                            | 2        | 0.65%   |
| Seagate ST91000640NS 1TB                             | 2        | 0.65%   |
| Seagate ST500DM002-1BD142 500GB                      | 2        | 0.65%   |
| Seagate ST2000NX0433 2TB                             | 2        | 0.65%   |
| Seagate ST2000NX0273 2TB                             | 2        | 0.65%   |
| Seagate ST1000DM010-2EP102 1TB                       | 2        | 0.65%   |
| Seagate ST1000DM003-9YN162 1TB                       | 2        | 0.65%   |
| Sandisk WD Black SN850 2TB                           | 2        | 0.65%   |
| Samsung SSD 990 PRO 2TB                              | 2        | 0.65%   |
| Samsung SSD 870 QVO 1TB                              | 2        | 0.65%   |
| Samsung SSD 850 EVO 250GB                            | 2        | 0.65%   |
| Samsung NVMe SSD Drive 512GB                         | 2        | 0.65%   |
| Samsung NVMe SSD Drive 500GB                         | 2        | 0.65%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB  | 2        | 0.65%   |
| Micron/Crucial CT1000P1SSD8 1TB                      | 2        | 0.65%   |
| Kingston SUV500120G 120GB SSD                        | 2        | 0.65%   |
| Kingston SA400S37480G 480GB SSD                      | 2        | 0.65%   |
| Kingston SA400S37240G 240GB SSD                      | 2        | 0.65%   |
| Intel SSD 660P Series 1024GB                         | 2        | 0.65%   |
| Crucial CT480BX500SSD1 480GB                         | 2        | 0.65%   |
| Crucial CT240BX500SSD1 240GB                         | 2        | 0.65%   |
| Corsair Force LE SSD 240GB                           | 2        | 0.65%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 41       | 97     | 37.61%  |
| WDC                 | 36       | 71     | 33.03%  |
| Toshiba             | 12       | 18     | 11.01%  |
| Hitachi             | 4        | 4      | 3.67%   |
| HGST                | 4        | 4      | 3.67%   |
| Dell                | 4        | 8      | 3.67%   |
| Unknown             | 2        | 2      | 1.83%   |
| Samsung Electronics | 2        | 3      | 1.83%   |
| SCST_FIO            | 1        | 9      | 0.92%   |
| SABRENT             | 1        | 1      | 0.92%   |
| Hewlett-Packard     | 1        | 1      | 0.92%   |
| Fantom              | 1        | 1      | 0.92%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 18       | 37     | 22.5%   |
| Kingston            | 11       | 16     | 13.75%  |
| Crucial             | 8        | 12     | 10%     |
| WDC                 | 5        | 6      | 6.25%   |
| SanDisk             | 4        | 9      | 5%      |
| Intel               | 4        | 7      | 5%      |
| SK hynix            | 3        | 5      | 3.75%   |
| PNY                 | 3        | 3      | 3.75%   |
| Micron Technology   | 3        | 3      | 3.75%   |
| China               | 3        | 3      | 3.75%   |
| A-DATA Technology   | 3        | 3      | 3.75%   |
| Corsair             | 2        | 5      | 2.5%    |
| XUM                 | 1        | 1      | 1.25%   |
| SSK Port            | 1        | 1      | 1.25%   |
| SPCC                | 1        | 1      | 1.25%   |
| OCZ                 | 1        | 2      | 1.25%   |
| Lexar               | 1        | 1      | 1.25%   |
| KingSpec            | 1        | 1      | 1.25%   |
| KINGBANK            | 1        | 1      | 1.25%   |
| Kimtigo             | 1        | 1      | 1.25%   |
| Inland              | 1        | 1      | 1.25%   |
| HUSKY               | 1        | 1      | 1.25%   |
| Hoodisk             | 1        | 1      | 1.25%   |
| Gigabyte Technology | 1        | 1      | 1.25%   |
| Anobit              | 1        | 1      | 1.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 80       | 219    | 38.1%   |
| SSD     | 71       | 123    | 33.81%  |
| NVMe    | 55       | 98     | 26.19%  |
| Unknown | 4        | 9      | 1.9%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 102      | 320    | 58.62%  |
| NVMe | 55       | 97     | 31.61%  |
| SAS  | 17       | 32     | 9.77%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 68       | 128    | 38.42%  |
| 0.51-1.0   | 46       | 77     | 25.99%  |
| 1.01-2.0   | 30       | 62     | 16.95%  |
| 3.01-4.0   | 12       | 27     | 6.78%   |
| 4.01-10.0  | 9        | 29     | 5.08%   |
| 20.01-50.0 | 4        | 8      | 2.26%   |
| 2.01-3.0   | 4        | 5      | 2.26%   |
| 10.01-20.0 | 4        | 6      | 2.26%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 27       | 21.26%  |
| 251-500        | 22       | 17.32%  |
| More than 3000 | 20       | 15.75%  |
| 501-1000       | 20       | 15.75%  |
| 1001-2000      | 16       | 12.6%   |
| Unknown        | 10       | 7.87%   |
| 2001-3000      | 7        | 5.51%   |
| 51-100         | 3        | 2.36%   |
| 21-50          | 1        | 0.79%   |
| 1-20           | 1        | 0.79%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 21-50          | 28       | 21.05%  |
| 1-20           | 28       | 21.05%  |
| 101-250        | 19       | 14.29%  |
| 51-100         | 16       | 12.03%  |
| 251-500        | 10       | 7.52%   |
| Unknown        | 10       | 7.52%   |
| 501-1000       | 7        | 5.26%   |
| More than 3000 | 6        | 4.51%   |
| 1001-2000      | 5        | 3.76%   |
| 2001-3000      | 4        | 3.01%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                             | Desktops | Drives | Percent |
|---------------------------------------------------|----------|--------|---------|
| WDC WD50 00LPVX-22V0TT0 500GB                     | 1        | 1      | 8.33%   |
| WDC WD10EALX-759BA1 1TB                           | 1        | 2      | 8.33%   |
| Silicon Motion SM2262/SM2262EN SSD Controller 2TB | 1        | 1      | 8.33%   |
| Seagate ST91000640NS 1TB                          | 1        | 2      | 8.33%   |
| Seagate ST14000NM0018-2H4101 14TB                 | 1        | 1      | 8.33%   |
| Seagate ST1000DM010-2EP102 1TB                    | 1        | 1      | 8.33%   |
| Seagate ST1000DM003-9YN162 1TB                    | 1        | 1      | 8.33%   |
| Micron Technology M510_2.5 7MM 256GB SSD          | 1        | 1      | 8.33%   |
| Intel SSDSC2BB480G7 480GB                         | 1        | 2      | 8.33%   |
| Hitachi HDS722020ALA330 2TB                       | 1        | 1      | 8.33%   |
| Crucial CT1000BX500SSD1 1TB                       | 1        | 1      | 8.33%   |
| A-DATA Technology SU800NS38 256GB SSD             | 1        | 1      | 8.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Desktops | Drives | Percent |
|-------------------|----------|--------|---------|
| Seagate           | 4        | 5      | 33.33%  |
| WDC               | 2        | 3      | 16.67%  |
| Silicon Motion    | 1        | 1      | 8.33%   |
| Micron Technology | 1        | 1      | 8.33%   |
| Intel             | 1        | 2      | 8.33%   |
| Hitachi           | 1        | 1      | 8.33%   |
| Crucial           | 1        | 1      | 8.33%   |
| A-DATA Technology | 1        | 1      | 8.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 4        | 5      | 57.14%  |
| WDC     | 2        | 3      | 28.57%  |
| Hitachi | 1        | 1      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 6        | 9      | 54.55%  |
| SSD  | 4        | 5      | 36.36%  |
| NVMe | 1        | 1      | 9.09%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| Samsung Electronics SSD 980 1TB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 68       | 259    | 50.75%  |
| Works    | 54       | 174    | 40.3%   |
| Malfunc  | 11       | 15     | 8.21%   |
| Failed   | 1        | 1      | 0.75%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 93       | 44.71%  |
| AMD                          | 28       | 13.46%  |
| Samsung Electronics          | 21       | 10.1%   |
| SanDisk                      | 10       | 4.81%   |
| Phison Electronics           | 10       | 4.81%   |
| Broadcom / LSI               | 10       | 4.81%   |
| ASMedia Technology           | 10       | 4.81%   |
| Micron/Crucial Technology    | 6        | 2.88%   |
| Toshiba America Info Systems | 3        | 1.44%   |
| Marvell Technology Group     | 3        | 1.44%   |
| LSI Logic / Symbios Logic    | 3        | 1.44%   |
| ADATA Technology             | 3        | 1.44%   |
| SK hynix                     | 2        | 0.96%   |
| Silicon Motion               | 2        | 0.96%   |
| Western Digital              | 1        | 0.48%   |
| Micron Technology            | 1        | 0.48%   |
| JMicron Technology           | 1        | 0.48%   |
| HighPoint Technologies       | 1        | 0.48%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 17       | 6.75%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 14       | 5.56%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 12       | 4.76%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 11       | 4.37%   |
| Intel SATA Controller [RAID mode]                                              | 11       | 4.37%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 11       | 4.37%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 10       | 3.97%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 7        | 2.78%   |
| AMD 500 Series Chipset SATA Controller                                         | 7        | 2.78%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 6        | 2.38%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 6        | 2.38%   |
| Broadcom / LSI MegaRAID SAS-3 3108 [Invader]                                   | 6        | 2.38%   |
| Phison E16 PCIe4 NVMe Controller                                               | 5        | 1.98%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 5        | 1.98%   |
| Broadcom / LSI SAS3008 PCI-Express Fusion-MPT SAS-3                            | 5        | 1.98%   |
| Phison E12 NVMe Controller                                                     | 4        | 1.59%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 4        | 1.59%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 4        | 1.59%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 3        | 1.19%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 3        | 1.19%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                    | 3        | 1.19%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3        | 1.19%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 3        | 1.19%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 3        | 1.19%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 3        | 1.19%   |
| Intel SSD 660P Series                                                          | 3        | 1.19%   |
| Intel Raptor Lake SATA AHCI Controller                                         | 3        | 1.19%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                            | 3        | 1.19%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 3        | 1.19%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 3        | 1.19%   |
| AMD 400 Series Chipset SATA Controller                                         | 3        | 1.19%   |
| AMD 300 Series Chipset SATA Controller                                         | 3        | 1.19%   |
| SK hynix PC601 NVMe Solid State Drive                                          | 2        | 0.79%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 2        | 0.79%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 2        | 0.79%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                          | 2        | 0.79%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 2        | 0.79%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton2]                                     | 2        | 0.79%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2        | 0.79%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 2        | 0.79%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 104      | 50.98%  |
| NVMe | 55       | 26.96%  |
| RAID | 27       | 13.24%  |
| SAS  | 12       | 5.88%   |
| IDE  | 5        | 2.45%   |
| SCSI | 1        | 0.49%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 91       | 76.47%  |
| AMD    | 28       | 23.53%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| AMD Ryzen 9 3900X 12-Core Processor     | 5        | 4.2%    |
| Intel Core i7-8700 CPU @ 3.20GHz        | 4        | 3.36%   |
| AMD Ryzen 9 5900X 12-Core Processor     | 4        | 3.36%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz     | 3        | 2.52%   |
| Intel 11th Gen Core i7-11700K @ 3.60GHz | 3        | 2.52%   |
| AMD Ryzen 5 5600G with Radeon Graphics  | 3        | 2.52%   |
| Intel Xeon CPU E5-2680 v3 @ 2.50GHz     | 2        | 1.68%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz     | 2        | 1.68%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz     | 2        | 1.68%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz  | 2        | 1.68%   |
| Intel Core i7-8700K CPU @ 3.70GHz       | 2        | 1.68%   |
| Intel Core i7-7700K CPU @ 4.20GHz       | 2        | 1.68%   |
| Intel Core i7-7700 CPU @ 3.60GHz        | 2        | 1.68%   |
| Intel Core i3-4130 CPU @ 3.40GHz        | 2        | 1.68%   |
| AMD Ryzen 5 3600 6-Core Processor       | 2        | 1.68%   |
| Intel Xeon w9-3495X                     | 1        | 0.84%   |
| Intel Xeon W-2145 CPU @ 3.70GHz         | 1        | 0.84%   |
| Intel Xeon W-2102 CPU @ 2.90GHz         | 1        | 0.84%   |
| Intel Xeon CPU X5570 @ 2.93GHz          | 1        | 0.84%   |
| Intel Xeon CPU E5472 @ 3.00GHz          | 1        | 0.84%   |
| Intel Xeon CPU E5-2696 v3 @ 2.30GHz     | 1        | 0.84%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz      | 1        | 0.84%   |
| Intel Xeon CPU E5-2680 v2 @ 2.80GHz     | 1        | 0.84%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz     | 1        | 0.84%   |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz      | 1        | 0.84%   |
| Intel Xeon CPU E5-2620 0 @ 2.00GHz      | 1        | 0.84%   |
| Intel Xeon CPU E5-1650 v4 @ 3.60GHz     | 1        | 0.84%   |
| Intel Xeon CPU E5-1620 v4 @ 3.50GHz     | 1        | 0.84%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz     | 1        | 0.84%   |
| Intel Xeon CPU E5-1607 v4 @ 3.10GHz     | 1        | 0.84%   |
| Intel Xeon CPU E3-1280 V2 @ 3.60GHz     | 1        | 0.84%   |
| Intel Xeon CPU E3-1270 v5 @ 3.60GHz     | 1        | 0.84%   |
| Intel Xeon CPU E3-1240 v5 @ 3.50GHz     | 1        | 0.84%   |
| Intel Xeon CPU E3-1240 v3 @ 3.40GHz     | 1        | 0.84%   |
| Intel Xeon CPU E3-1225 v5 @ 3.30GHz     | 1        | 0.84%   |
| Intel Pentium Silver N6005 @ 2.00GHz    | 1        | 0.84%   |
| Intel Core i9-9900 CPU @ 3.10GHz        | 1        | 0.84%   |
| Intel Core i9-14900KS                   | 1        | 0.84%   |
| Intel Core i9-10850K CPU @ 3.60GHz      | 1        | 0.84%   |
| Intel Core i7-9700F CPU @ 3.00GHz       | 1        | 0.84%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Xeon             | 29       | 24.37%  |
| Intel Core i7          | 20       | 16.81%  |
| Intel Core i5          | 15       | 12.61%  |
| AMD Ryzen 9            | 11       | 9.24%   |
| Other                  | 10       | 8.4%    |
| Intel Core i3          | 9        | 7.56%   |
| AMD Ryzen 5            | 7        | 5.88%   |
| AMD Ryzen 7            | 5        | 4.2%    |
| Intel Core i9          | 3        | 2.52%   |
| Intel Pentium Gold     | 2        | 1.68%   |
| Intel Pentium Silver   | 1        | 0.84%   |
| Intel Core 2 Duo       | 1        | 0.84%   |
| Intel Celeron          | 1        | 0.84%   |
| AMD Ryzen Threadripper | 1        | 0.84%   |
| AMD Ryzen 3            | 1        | 0.84%   |
| AMD FX                 | 1        | 0.84%   |
| AMD Athlon X4          | 1        | 0.84%   |
| AMD A4                 | 1        | 0.84%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 36       | 30.25%  |
| 8      | 18       | 15.13%  |
| 6      | 17       | 14.29%  |
| 12     | 15       | 12.61%  |
| 2      | 13       | 10.92%  |
| 16     | 9        | 7.56%   |
| 24     | 3        | 2.52%   |
| 10     | 2        | 1.68%   |
| 1      | 2        | 1.68%   |
| 56     | 1        | 0.84%   |
| 36     | 1        | 0.84%   |
| 20     | 1        | 0.84%   |
| 14     | 1        | 0.84%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 106      | 89.08%  |
| 2      | 13       | 10.92%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 87       | 72.5%   |
| 1      | 33       | 27.5%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 117      | 98.32%  |
| Unknown        | 2        | 1.68%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 23       | 19.01%  |
| 0x306c3    | 12       | 9.92%   |
| 0x906ea    | 8        | 6.61%   |
| 0x306f2    | 8        | 6.61%   |
| 0x306a9    | 8        | 6.61%   |
| 0x08701021 | 5        | 4.13%   |
| 0xa0671    | 4        | 3.31%   |
| 0x906e9    | 4        | 3.31%   |
| 0x506e3    | 4        | 3.31%   |
| 0x406f1    | 4        | 3.31%   |
| 0x906ed    | 3        | 2.48%   |
| 0x206d7    | 3        | 2.48%   |
| 0x906eb    | 2        | 1.65%   |
| 0x906c0    | 2        | 1.65%   |
| 0x0a50000f | 2        | 1.65%   |
| 0x0a20120a | 2        | 1.65%   |
| 0x08701013 | 2        | 1.65%   |
| 0x08001138 | 2        | 1.65%   |
| 0xb0671    | 1        | 0.83%   |
| 0xa0655    | 1        | 0.83%   |
| 0x90672    | 1        | 0.83%   |
| 0x806e9    | 1        | 0.83%   |
| 0x306e4    | 1        | 0.83%   |
| 0x206c2    | 1        | 0.83%   |
| 0x206a7    | 1        | 0.83%   |
| 0x106a5    | 1        | 0.83%   |
| 0x1067a    | 1        | 0.83%   |
| 0x10676    | 1        | 0.83%   |
| 0x0a601206 | 1        | 0.83%   |
| 0x0a601203 | 1        | 0.83%   |
| 0x0a50000c | 1        | 0.83%   |
| 0x0a201204 | 1        | 0.83%   |
| 0x0a20102b | 1        | 0.83%   |
| 0x08701030 | 1        | 0.83%   |
| 0x08108102 | 1        | 0.83%   |
| 0x0810100b | 1        | 0.83%   |
| 0x0800820d | 1        | 0.83%   |
| 0x08001137 | 1        | 0.83%   |
| 0x06006705 | 1        | 0.83%   |
| 0x0600611a | 1        | 0.83%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| KabyLake         | 21       | 17.65%  |
| Haswell          | 21       | 17.65%  |
| IvyBridge        | 11       | 9.24%   |
| Zen 3            | 9        | 7.56%   |
| Zen 2            | 8        | 6.72%   |
| Skylake          | 7        | 5.88%   |
| Broadwell        | 6        | 5.04%   |
| Alderlake Hybrid | 6        | 5.04%   |
| SandyBridge      | 5        | 4.2%    |
| Icelake          | 5        | 4.2%    |
| Zen              | 4        | 3.36%   |
| Unknown          | 3        | 2.52%   |
| Zen+             | 2        | 1.68%   |
| Tremont          | 2        | 1.68%   |
| Penryn           | 2        | 1.68%   |
| Excavator        | 2        | 1.68%   |
| CometLake        | 2        | 1.68%   |
| Westmere         | 1        | 0.84%   |
| Piledriver       | 1        | 0.84%   |
| Nehalem          | 1        | 0.84%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 65       | 46.76%  |
| Intel                      | 39       | 28.06%  |
| AMD                        | 27       | 19.42%  |
| Matrox Electronics Systems | 7        | 5.04%   |
| ASPEED Technology          | 1        | 0.72%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 8        | 5.52%   |
| Matrox Electronics Systems G200eR2                                          | 6        | 4.14%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 5        | 3.45%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 4        | 2.76%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 4        | 2.76%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 2.07%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 3        | 2.07%   |
| Nvidia GK208B [GeForce GT 730]                                              | 3        | 2.07%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3        | 2.07%   |
| Intel HD Graphics 630                                                       | 3        | 2.07%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3        | 2.07%   |
| Nvidia TU117GL [T400 4GB / T400E]                                           | 2        | 1.38%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 2        | 1.38%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 2        | 1.38%   |
| Nvidia GP107GL [Quadro P400]                                                | 2        | 1.38%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 1.38%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 2        | 1.38%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 2        | 1.38%   |
| Nvidia GM107GL [Quadro K620]                                                | 2        | 1.38%   |
| Nvidia GF119 [NVS 315]                                                      | 2        | 1.38%   |
| Nvidia GF108GL [Quadro 600]                                                 | 2        | 1.38%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 2        | 1.38%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 2        | 1.38%   |
| Nvidia AD102 [GeForce RTX 4090]                                             | 2        | 1.38%   |
| Intel JasperLake [UHD Graphics]                                             | 2        | 1.38%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2        | 1.38%   |
| Intel AlderLake-S GT1                                                       | 2        | 1.38%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 2        | 1.38%   |
| AMD Raphael                                                                 | 2        | 1.38%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]       | 2        | 1.38%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 2        | 1.38%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 2        | 1.38%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 2        | 1.38%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2        | 1.38%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 0.69%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 0.69%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 0.69%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 1        | 0.69%   |
| Nvidia GT218 [GeForce G210]                                                 | 1        | 0.69%   |
| Nvidia GP107GL [Quadro P600]                                                | 1        | 0.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 55       | 45.08%  |
| 1 x Intel       | 24       | 19.67%  |
| 1 x AMD         | 20       | 16.39%  |
| 1 x Matrox      | 7        | 5.74%   |
| Intel + Nvidia  | 5        | 4.1%    |
| 2 x Nvidia      | 3        | 2.46%   |
| 2 x AMD         | 3        | 2.46%   |
| Intel + AMD     | 3        | 2.46%   |
| Nvidia + ASPEED | 1        | 0.82%   |
| AMD + Nvidia    | 1        | 0.82%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 81       | 66.94%  |
| Proprietary | 30       | 24.79%  |
| Unknown     | 10       | 8.26%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 45       | 35.71%  |
| 7.01-8.0   | 20       | 15.87%  |
| 1.01-2.0   | 17       | 13.49%  |
| 3.01-4.0   | 11       | 8.73%   |
| 0.51-1.0   | 9        | 7.14%   |
| 8.01-16.0  | 7        | 5.56%   |
| 0.01-0.5   | 6        | 4.76%   |
| 5.01-6.0   | 4        | 3.17%   |
| 2.01-3.0   | 3        | 2.38%   |
| 16.01-24.0 | 3        | 2.38%   |
| 32.01-64.0 | 1        | 0.79%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 27       | 21.43%  |
| Samsung Electronics  | 24       | 19.05%  |
| Goldstar             | 13       | 10.32%  |
| Acer                 | 9        | 7.14%   |
| Hewlett-Packard      | 8        | 6.35%   |
| Lenovo               | 6        | 4.76%   |
| BenQ                 | 4        | 3.17%   |
| Unknown              | 4        | 3.17%   |
| ViewSonic            | 3        | 2.38%   |
| Philips              | 3        | 2.38%   |
| Iiyama               | 3        | 2.38%   |
| Gigabyte Technology  | 3        | 2.38%   |
| Ancor Communications | 3        | 2.38%   |
| Lenovo Group Limited | 2        | 1.59%   |
| Eizo                 | 2        | 1.59%   |
| Vizio                | 1        | 0.79%   |
| STD                  | 1        | 0.79%   |
| Sony                 | 1        | 0.79%   |
| Panasonic            | 1        | 0.79%   |
| OUT                  | 1        | 0.79%   |
| Microstep            | 1        | 0.79%   |
| LG Electronics       | 1        | 0.79%   |
| Insignia             | 1        | 0.79%   |
| Haier                | 1        | 0.79%   |
| Fujitsu Siemens      | 1        | 0.79%   |
| Deco Gear            | 1        | 0.79%   |
| AOC                  | 1        | 0.79%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Dell LCD Monitor DEL0001 1280x1024                                     | 6        | 4.29%   |
| Unknown                                                                | 4        | 2.86%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 677x290mm 29.0-inch               | 3        | 2.14%   |
| Lenovo TIO24Gen3 LEN10B4 1920x1080 527x296mm 23.8-inch                 | 2        | 1.43%   |
| Lenovo LEN T2324pA LEN60C7 1920x1080 509x286mm 23.0-inch               | 2        | 1.43%   |
| Lenovo LEN P27u-10 LEN61B0 3840x2160 597x336mm 27.0-inch               | 2        | 1.43%   |
| Iiyama PL4840 IVM1065 1920x1080 1054x593mm 47.6-inch                   | 2        | 1.43%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 2        | 1.43%   |
| Acer ED322QR ACR06DD 1920x1080 700x390mm 31.5-inch                     | 2        | 1.43%   |
| Vizio D48-D0 VIZ1004 1920x1080 1070x610mm 48.5-inch                    | 1        | 0.71%   |
| ViewSonic VX2776 Series VSC3E32 1920x1080 598x336mm 27.0-inch          | 1        | 0.71%   |
| ViewSonic VA2419 Series VSC7B32 1920x1080 527x296mm 23.8-inch          | 1        | 0.71%   |
| ViewSonic VA2259 Series VSC5E32 1920x1080 476x268mm 21.5-inch          | 1        | 0.71%   |
| STD VGA STD0110 1600x900 440x230mm 19.5-inch                           | 1        | 0.71%   |
| Sony TV SNYD703 1360x768                                               | 1        | 0.71%   |
| Samsung Electronics SyncMaster SAM05FC 1920x1080                       | 1        | 0.71%   |
| Samsung Electronics SyncMaster SAM0566 1440x900 408x255mm 18.9-inch    | 1        | 0.71%   |
| Samsung Electronics SyncMaster SAM0526 1920x1080 510x287mm 23.0-inch   | 1        | 0.71%   |
| Samsung Electronics SyncMaster SAM0380 1680x1050 459x296mm 21.5-inch   | 1        | 0.71%   |
| Samsung Electronics SyncMaster SAM0370 1680x1050 459x296mm 21.5-inch   | 1        | 0.71%   |
| Samsung Electronics SyncMaster SAM020D 1280x1024 338x270mm 17.0-inch   | 1        | 0.71%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch   | 1        | 0.71%   |
| Samsung Electronics SMS23A550H SAM07CA 1920x1080 509x286mm 23.0-inch   | 1        | 0.71%   |
| Samsung Electronics S27C500 SAM0AF2 1920x1080 598x336mm 27.0-inch      | 1        | 0.71%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 521x293mm 23.5-inch      | 1        | 0.71%   |
| Samsung Electronics S22E390 SAM0C18 1920x1080 477x268mm 21.5-inch      | 1        | 0.71%   |
| Samsung Electronics S22B300 SAM08A9 1600x900 443x249mm 20.0-inch       | 1        | 0.71%   |
| Samsung Electronics LU28R55 SAM1017 3840x2160 632x360mm 28.6-inch      | 1        | 0.71%   |
| Samsung Electronics LU28R55 SAM1015 3840x2160 632x360mm 28.6-inch      | 1        | 0.71%   |
| Samsung Electronics LCD Monitor SAM723F 3840x2160 700x390mm 31.5-inch  | 1        | 0.71%   |
| Samsung Electronics LCD Monitor SAM7106 1920x1080 1210x680mm 54.6-inch | 1        | 0.71%   |
| Samsung Electronics LCD Monitor SAM7103 3840x2160 700x390mm 31.5-inch  | 1        | 0.71%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 1110x620mm 50.1-inch | 1        | 0.71%   |
| Samsung Electronics LCD Monitor SAM0D42 3840x2160 1020x570mm 46.0-inch | 1        | 0.71%   |
| Samsung Electronics LCD Monitor SAM0C04 3840x2160 1050x590mm 47.4-inch | 1        | 0.71%   |
| Samsung Electronics LCD Monitor SAM0B30 1920x1080 480x270mm 21.7-inch  | 1        | 0.71%   |
| Samsung Electronics LCD Monitor SAM0200 1280x720                       | 1        | 0.71%   |
| Samsung Electronics LCD Monitor S22B150                                | 1        | 0.71%   |
| Samsung Electronics LCD Monitor C49HG9x 3840x1080                      | 1        | 0.71%   |
| Samsung Electronics C32R50x SAM7000 1920x1080 698x393mm 31.5-inch      | 1        | 0.71%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 51       | 41.46%  |
| 3840x2160 (4K)     | 14       | 11.38%  |
| 2560x1440 (QHD)    | 11       | 8.94%   |
| 1280x1024 (SXGA)   | 9        | 7.32%   |
| 3440x1440          | 5        | 4.07%   |
| 2560x1080          | 5        | 4.07%   |
| Unknown            | 5        | 4.07%   |
| 1600x900 (HD+)     | 4        | 3.25%   |
| 3840x1080          | 3        | 2.44%   |
| 1680x1050 (WSXGA+) | 3        | 2.44%   |
| 7680x2160          | 2        | 1.63%   |
| 3840x1200          | 2        | 1.63%   |
| 1920x1200 (WUXGA)  | 2        | 1.63%   |
| 9600x2160          | 1        | 0.81%   |
| 3840x1600          | 1        | 0.81%   |
| 2560x1600          | 1        | 0.81%   |
| 1440x900 (WXGA+)   | 1        | 0.81%   |
| 1360x768           | 1        | 0.81%   |
| 1280x768           | 1        | 0.81%   |
| 1280x720 (HD)      | 1        | 0.81%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 23       | 18.4%   |
| 24      | 16       | 12.8%   |
| 27      | 15       | 12%     |
| 23      | 14       | 11.2%   |
| 21      | 9        | 7.2%    |
| 31      | 8        | 6.4%    |
| 34      | 6        | 4.8%    |
| 54      | 4        | 3.2%    |
| 20      | 4        | 3.2%    |
| 84      | 3        | 2.4%    |
| 28      | 3        | 2.4%    |
| 47      | 2        | 1.6%    |
| 43      | 2        | 1.6%    |
| 17      | 2        | 1.6%    |
| 72      | 1        | 0.8%    |
| 64      | 1        | 0.8%    |
| 52      | 1        | 0.8%    |
| 40      | 1        | 0.8%    |
| 39      | 1        | 0.8%    |
| 37      | 1        | 0.8%    |
| 35      | 1        | 0.8%    |
| 33      | 1        | 0.8%    |
| 29      | 1        | 0.8%    |
| 26      | 1        | 0.8%    |
| 25      | 1        | 0.8%    |
| 19      | 1        | 0.8%    |
| 18      | 1        | 0.8%    |
| 16      | 1        | 0.8%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 43       | 35.54%  |
| Unknown     | 23       | 19.01%  |
| 601-700     | 13       | 10.74%  |
| 401-500     | 13       | 10.74%  |
| 1001-1500   | 8        | 6.61%   |
| 701-800     | 7        | 5.79%   |
| 801-900     | 4        | 3.31%   |
| 1501-2000   | 4        | 3.31%   |
| 301-350     | 3        | 2.48%   |
| 901-1000    | 2        | 1.65%   |
| 351-400     | 1        | 0.83%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 70       | 63.06%  |
| Unknown | 14       | 12.61%  |
| 5/4     | 9        | 8.11%   |
| 21/9    | 9        | 8.11%   |
| 16/10   | 8        | 7.21%   |
| 4/3     | 1        | 0.9%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 32       | 26.02%  |
| Unknown        | 23       | 18.7%   |
| 351-500        | 19       | 15.45%  |
| 301-350        | 16       | 13.01%  |
| More than 1000 | 10       | 8.13%   |
| 151-200        | 7        | 5.69%   |
| 501-1000       | 7        | 5.69%   |
| 251-300        | 6        | 4.88%   |
| 141-150        | 2        | 1.63%   |
| 131-140        | 1        | 0.81%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 62       | 51.67%  |
| Unknown | 23       | 19.17%  |
| 101-120 | 21       | 17.5%   |
| 1-50    | 8        | 6.67%   |
| 161-240 | 3        | 2.5%    |
| 121-160 | 3        | 2.5%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 89       | 71.77%  |
| 2     | 19       | 15.32%  |
| 0     | 11       | 8.87%   |
| 3     | 5        | 4.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 78       | 43.82%  |
| Realtek Semiconductor    | 54       | 30.34%  |
| Broadcom                 | 12       | 6.74%   |
| Qualcomm Atheros         | 8        | 4.49%   |
| ASIX Electronics         | 3        | 1.69%   |
| Aquantia                 | 3        | 1.69%   |
| Ralink Technology        | 2        | 1.12%   |
| MediaTek                 | 2        | 1.12%   |
| Edimax Technology        | 2        | 1.12%   |
| Dell                     | 2        | 1.12%   |
| TP-Link                  | 1        | 0.56%   |
| Ralink                   | 1        | 0.56%   |
| Qualcomm                 | 1        | 0.56%   |
| Microchip Technology     | 1        | 0.56%   |
| Micro Star International | 1        | 0.56%   |
| Mellanox Technologies    | 1        | 0.56%   |
| Huawei Technologies      | 1        | 0.56%   |
| D-Link                   | 1        | 0.56%   |
| Broadcom Limited         | 1        | 0.56%   |
| ASUSTek Computer         | 1        | 0.56%   |
| Arduino SA               | 1        | 0.56%   |
| AMD                      | 1        | 0.56%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 36       | 15.52%  |
| Realtek RTL8125 2.5GbE Controller                                              | 10       | 4.31%   |
| Intel I211 Gigabit Network Connection                                          | 10       | 4.31%   |
| Intel Ethernet Controller I225-V                                               | 10       | 4.31%   |
| Intel Wi-Fi 6 AX200                                                            | 8        | 3.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 7        | 3.02%   |
| Intel 82574L Gigabit Network Connection                                        | 7        | 3.02%   |
| Intel Ethernet Connection I217-LM                                              | 6        | 2.59%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                      | 5        | 2.16%   |
| Intel Ethernet Connection (2) I219-V                                           | 5        | 2.16%   |
| Intel Ethernet Connection (2) I219-LM                                          | 5        | 2.16%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 5        | 2.16%   |
| Intel I350 Gigabit Network Connection                                          | 4        | 1.72%   |
| Intel Ethernet Connection (7) I219-LM                                          | 4        | 1.72%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                             | 4        | 1.72%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                               | 4        | 1.72%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 3        | 1.29%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 3        | 1.29%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 3        | 1.29%   |
| Intel I210 Gigabit Network Connection                                          | 3        | 1.29%   |
| Intel Ethernet Connection (2) I218-V                                           | 3        | 1.29%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 3        | 1.29%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter                   | 3        | 1.29%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 2        | 0.86%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 2        | 0.86%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                        | 2        | 0.86%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                              | 2        | 0.86%   |
| Intel Ethernet Controller I226-V                                               | 2        | 0.86%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                  | 2        | 0.86%   |
| Intel Ethernet Connection I217-V                                               | 2        | 0.86%   |
| Intel Ethernet Connection (7) I219-V                                           | 2        | 0.86%   |
| Intel Ethernet Connection (5) I219-LM                                          | 2        | 0.86%   |
| Intel Ethernet Connection (2) I218-LM                                          | 2        | 0.86%   |
| Intel 82599 10 Gigabit Dual Port Backplane Connection                          | 2        | 0.86%   |
| Dell iDRAC Virtual NIC                                                         | 2        | 0.86%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                   | 2        | 0.86%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 2        | 0.86%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 2        | 0.86%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                            | 1        | 0.43%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller                    | 1        | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 30       | 46.88%  |
| Realtek Semiconductor    | 10       | 15.63%  |
| Qualcomm Atheros         | 7        | 10.94%  |
| Broadcom                 | 6        | 9.38%   |
| Ralink Technology        | 2        | 3.13%   |
| MediaTek                 | 2        | 3.13%   |
| Edimax Technology        | 2        | 3.13%   |
| TP-Link                  | 1        | 1.56%   |
| Ralink                   | 1        | 1.56%   |
| Micro Star International | 1        | 1.56%   |
| D-Link                   | 1        | 1.56%   |
| ASUSTek Computer         | 1        | 1.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                        | 8        | 12.5%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                  | 5        | 7.81%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                           | 5        | 7.81%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 3        | 4.69%   |
| Intel Cannon Lake PCH CNVi WiFi                                            | 3        | 4.69%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter               | 3        | 4.69%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                 | 2        | 3.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                           | 2        | 3.13%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                    | 2        | 3.13%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                          | 2        | 3.13%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter               | 2        | 3.13%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                        | 1        | 1.56%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller                | 1        | 1.56%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                | 1        | 1.56%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                            | 1        | 1.56%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                 | 1        | 1.56%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                            | 1        | 1.56%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                            | 1        | 1.56%   |
| Realtek 802.11n WLAN Adapter                                               | 1        | 1.56%   |
| Ralink RT5572 Wireless Adapter                                             | 1        | 1.56%   |
| Ralink RT5372 Wireless Adapter                                             | 1        | 1.56%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                  | 1        | 1.56%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                           | 1        | 1.56%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)             | 1        | 1.56%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                           | 1        | 1.56%   |
| Micro Star International MS-3871 802.11bgn Wireless Module [Ralink RT8070] | 1        | 1.56%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                    | 1        | 1.56%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                         | 1        | 1.56%   |
| Intel Wireless 8265 / 8275                                                 | 1        | 1.56%   |
| Intel Wireless 7260                                                        | 1        | 1.56%   |
| Intel Wi-Fi 6 AX201 160MHz                                                 | 1        | 1.56%   |
| Intel Comet Lake PCH CNVi WiFi                                             | 1        | 1.56%   |
| Intel Alder Lake-S PCH CNVi WiFi                                           | 1        | 1.56%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]             | 1        | 1.56%   |
| Edimax AC1200 MU-MIMO USB3.0 Adapter                                       | 1        | 1.56%   |
| D-Link DWA-171 AC600 DB Wireless Adapter(rev.A1) [Realtek RTL8811AU]       | 1        | 1.56%   |
| Broadcom BCM4321 802.11b/g/n                                               | 1        | 1.56%   |
| ASUS WL-167G v3 802.11n Adapter [Realtek RTL8188SU]                        | 1        | 1.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 71       | 50%     |
| Realtek Semiconductor | 51       | 35.92%  |
| Broadcom              | 7        | 4.93%   |
| ASIX Electronics      | 3        | 2.11%   |
| Aquantia              | 3        | 2.11%   |
| Qualcomm Atheros      | 2        | 1.41%   |
| Dell                  | 2        | 1.41%   |
| Qualcomm              | 1        | 0.7%    |
| Mellanox Technologies | 1        | 0.7%    |
| Broadcom Limited      | 1        | 0.7%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 36       | 21.95%  |
| Realtek RTL8125 2.5GbE Controller                                              | 10       | 6.1%    |
| Intel I211 Gigabit Network Connection                                          | 10       | 6.1%    |
| Intel Ethernet Controller I225-V                                               | 10       | 6.1%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 7        | 4.27%   |
| Intel 82574L Gigabit Network Connection                                        | 7        | 4.27%   |
| Intel Ethernet Connection I217-LM                                              | 6        | 3.66%   |
| Intel Ethernet Connection (2) I219-V                                           | 5        | 3.05%   |
| Intel Ethernet Connection (2) I219-LM                                          | 5        | 3.05%   |
| Intel I350 Gigabit Network Connection                                          | 4        | 2.44%   |
| Intel Ethernet Connection (7) I219-LM                                          | 4        | 2.44%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                             | 4        | 2.44%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                               | 4        | 2.44%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 3        | 1.83%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 3        | 1.83%   |
| Intel I210 Gigabit Network Connection                                          | 3        | 1.83%   |
| Intel Ethernet Connection (2) I218-V                                           | 3        | 1.83%   |
| Intel Ethernet Controller I226-V                                               | 2        | 1.22%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                  | 2        | 1.22%   |
| Intel Ethernet Connection I217-V                                               | 2        | 1.22%   |
| Intel Ethernet Connection (7) I219-V                                           | 2        | 1.22%   |
| Intel Ethernet Connection (5) I219-LM                                          | 2        | 1.22%   |
| Intel Ethernet Connection (2) I218-LM                                          | 2        | 1.22%   |
| Intel 82599 10 Gigabit Dual Port Backplane Connection                          | 2        | 1.22%   |
| Dell iDRAC Virtual NIC                                                         | 2        | 1.22%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 2        | 1.22%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 2        | 1.22%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1        | 0.61%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1        | 0.61%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1        | 0.61%   |
| Qualcomm Airtel 4G                                                             | 1        | 0.61%   |
| Mellanox MT27500 Family [ConnectX-3]                                           | 1        | 0.61%   |
| Intel Wi-Fi 7(802.11be) AX1775*/AX1790*/BE20*/BE401/BE1750* 2x2                | 1        | 0.61%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                  | 1        | 0.61%   |
| Intel Ethernet Connection (17) I219-LM                                         | 1        | 0.61%   |
| Intel Ethernet Connection (11) I219-V                                          | 1        | 0.61%   |
| Intel 82579V Gigabit Network Connection                                        | 1        | 0.61%   |
| Intel 82575EB Gigabit Network Connection                                       | 1        | 0.61%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications)  | 1        | 0.61%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                     | 1        | 0.61%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 119      | 64.67%  |
| WiFi     | 61       | 33.15%  |
| Modem    | 3        | 1.63%   |
| Unknown  | 1        | 0.54%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 103      | 83.74%  |
| WiFi     | 20       | 16.26%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 2     | 46       | 37.7%   |
| 1     | 46       | 37.7%   |
| 3     | 16       | 13.11%  |
| 4     | 7        | 5.74%   |
| 6     | 5        | 4.1%    |
| 5     | 2        | 1.64%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 93       | 75.61%  |
| Yes  | 30       | 24.39%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 29       | 54.72%  |
| Cambridge Silicon Radio         | 8        | 15.09%  |
| Realtek Semiconductor           | 4        | 7.55%   |
| ASUSTek Computer                | 4        | 7.55%   |
| Qualcomm Atheros Communications | 2        | 3.77%   |
| Micro Star International        | 1        | 1.89%   |
| MediaTek                        | 1        | 1.89%   |
| Integrated System Solution      | 1        | 1.89%   |
| IMC Networks                    | 1        | 1.89%   |
| Foxconn / Hon Hai               | 1        | 1.89%   |
| Broadcom                        | 1        | 1.89%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 8        | 15.09%  |
| Intel AX200 Bluetooth                                 | 7        | 13.21%  |
| Intel Wireless-AC 3168 Bluetooth                      | 5        | 9.43%   |
| Intel AX210 Bluetooth                                 | 5        | 9.43%   |
| Realtek Bluetooth Radio                               | 4        | 7.55%   |
| Intel AX201 Bluetooth                                 | 4        | 7.55%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 3        | 5.66%   |
| Qualcomm Atheros  Bluetooth Device                    | 2        | 3.77%   |
| Intel Bluetooth wireless interface                    | 2        | 3.77%   |
| ASUS BCM20702A0                                       | 2        | 3.77%   |
| Micro Star International Bluetooth Device             | 1        | 1.89%   |
| MediaTek Wireless_Device                              | 1        | 1.89%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 1        | 1.89%   |
| Intel Bluetooth Device                                | 1        | 1.89%   |
| Intel AX211 Bluetooth                                 | 1        | 1.89%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1        | 1.89%   |
| IMC Networks BCM20702A0                               | 1        | 1.89%   |
| Foxconn / Hon Hai Bluetooth Device                    | 1        | 1.89%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 1        | 1.89%   |
| ASUS Qualcomm Bluetooth 4.1                           | 1        | 1.89%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 1.89%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 79       | 36.74%  |
| Nvidia                                       | 61       | 28.37%  |
| AMD                                          | 36       | 16.74%  |
| Creative Labs                                | 4        | 1.86%   |
| ASUSTek Computer                             | 4        | 1.86%   |
| Texas Instruments                            | 3        | 1.4%    |
| Logitech                                     | 3        | 1.4%    |
| Lenovo                                       | 3        | 1.4%    |
| Plantronics                                  | 2        | 0.93%   |
| Micro Star International                     | 2        | 0.93%   |
| Creative Technology                          | 2        | 0.93%   |
| C-Media Electronics                          | 2        | 0.93%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 0.47%   |
| Valve Software                               | 1        | 0.47%   |
| Unknown                                      | 1        | 0.47%   |
| Tenx Technology                              | 1        | 0.47%   |
| SteelSeries ApS                              | 1        | 0.47%   |
| Sennheiser Communications                    | 1        | 0.47%   |
| RODE Microphones                             | 1        | 0.47%   |
| JMTek                                        | 1        | 0.47%   |
| GN Netcom                                    | 1        | 0.47%   |
| Giga-Byte Technology                         | 1        | 0.47%   |
| Elgato Systems                               | 1        | 0.47%   |
| Dynex                                        | 1        | 0.47%   |
| Blue Microphones                             | 1        | 0.47%   |
| Astro Gaming                                 | 1        | 0.47%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 12       | 4.92%   |
| Intel Cannon Lake PCH cAVS                                                 | 11       | 4.51%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 10       | 4.1%    |
| Nvidia GP107GL High Definition Audio Controller                            | 8        | 3.28%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 8        | 3.28%   |
| Intel 200 Series PCH HD Audio                                              | 8        | 3.28%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 8        | 3.28%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 7        | 2.87%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 6        | 2.46%   |
| Nvidia GP104 High Definition Audio Controller                              | 5        | 2.05%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 5        | 2.05%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 5        | 2.05%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5        | 2.05%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 5        | 2.05%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 4        | 1.64%   |
| Nvidia GF108 High Definition Audio Controller                              | 4        | 1.64%   |
| Intel Alder Lake-S HD Audio Controller                                     | 4        | 1.64%   |
| AMD Navi 10 HDMI Audio                                                     | 4        | 1.64%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 4        | 1.64%   |
| Texas Instruments PCM2902 Audio Codec                                      | 3        | 1.23%   |
| Nvidia TU116 High Definition Audio Controller                              | 3        | 1.23%   |
| Nvidia TU106 High Definition Audio Controller                              | 3        | 1.23%   |
| Nvidia GP106 High Definition Audio Controller                              | 3        | 1.23%   |
| Nvidia GM206 High Definition Audio Controller                              | 3        | 1.23%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3        | 1.23%   |
| Nvidia GF119 HDMI Audio Controller                                         | 3        | 1.23%   |
| Nvidia GA104 High Definition Audio Controller                              | 3        | 1.23%   |
| Nvidia GA102 High Definition Audio Controller                              | 3        | 1.23%   |
| Lenovo Thinkcentre TIO24Gen3 for USB-audio                                 | 3        | 1.23%   |
| Intel Raptor Lake High Definition Audio Controller                         | 3        | 1.23%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3        | 1.23%   |
| ASUSTek Computer USB Audio                                                 | 3        | 1.23%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3        | 1.23%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3        | 1.23%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 3        | 1.23%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2        | 0.82%   |
| Nvidia TU104 HD Audio Controller                                           | 2        | 0.82%   |
| Nvidia GP102 HDMI Audio Controller                                         | 2        | 0.82%   |
| Nvidia GM204 High Definition Audio Controller                              | 2        | 0.82%   |
| Nvidia GK106 HDMI Audio Controller                                         | 2        | 0.82%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| SK hynix            | 11       | 15.94%  |
| Samsung Electronics | 10       | 14.49%  |
| Corsair             | 10       | 14.49%  |
| Micron Technology   | 9        | 13.04%  |
| Crucial             | 8        | 11.59%  |
| G.Skill             | 7        | 10.14%  |
| Kingston            | 5        | 7.25%   |
| Unknown             | 3        | 4.35%   |
| Unknown (0x0205)    | 1        | 1.45%   |
| Transcend           | 1        | 1.45%   |
| Team                | 1        | 1.45%   |
| Patriot             | 1        | 1.45%   |
| Hewlett-Packard     | 1        | 1.45%   |
| GOODRAM             | 1        | 1.45%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| SK hynix RAM HMA82GR7MFR8N-UH 16GB DIMM DDR4 2400MT/s   | 2        | 2.67%   |
| SK hynix RAM HMA42GR7MFR4N-TF 16GB DIMM DDR4 2133MT/s   | 2        | 2.67%   |
| Samsung RAM M378A2K43CB1-CTD 16GB DIMM DDR4 3200MT/s    | 2        | 2.67%   |
| Micron RAM 36ASF2G72PZ-2G1A2 16GB DIMM DDR4 2400MT/s    | 2        | 2.67%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3866MT/s  | 2        | 2.67%   |
| Corsair RAM CMK64GX4M2D3600C18 32GB DIMM DDR4 3600MT/s  | 2        | 2.67%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s   | 2        | 2.67%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s               | 1        | 1.33%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s            | 1        | 1.33%   |
| Unknown RAM Module 2GB DIMM DDR3 1600MT/s               | 1        | 1.33%   |
| Unknown (0x0205) RAM Module 8GB DIMM DDR3 1600MT/s      | 1        | 1.33%   |
| Transcend RAM TS1GLK72V3H 8GB DIMM DDR3 1333MT/s        | 1        | 1.33%   |
| Team RAM TEAMGROUP-ED4-2400 16GB DIMM DDR4 2400MT/s     | 1        | 1.33%   |
| SK hynix RAM Module 16GB Row Of Chips LPDDR4 2933MT/s   | 1        | 1.33%   |
| SK hynix RAM HMT351S6EFR8C-PB 4096MB DIMM DDR3 1333MT/s | 1        | 1.33%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB DIMM DDR3 1333MT/s | 1        | 1.33%   |
| SK hynix RAM HMA851U6CJR6N-VK 4GB DIMM DDR4 2667MT/s    | 1        | 1.33%   |
| SK hynix RAM HMA84GR7MFR4N-UH 32GB RIMM DDR4 2400MT/s   | 1        | 1.33%   |
| SK hynix RAM HMA82GU7AFR8N-UH 16GB DIMM DDR4 2400MT/s   | 1        | 1.33%   |
| SK hynix RAM HMA82GU6CJR8N-VK 16GB DIMM DDR4 2667MT/s   | 1        | 1.33%   |
| SK hynix RAM HMA81GU7AFR8N-UH 8GB DIMM DDR4 2400MT/s    | 1        | 1.33%   |
| Samsung RAM Module 8GB DIMM DDR4 2666MT/s               | 1        | 1.33%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2667MT/s          | 1        | 1.33%   |
| Samsung RAM Module 4GB DIMM DDR4 2133MT/s               | 1        | 1.33%   |
| Samsung RAM Module 16GB DIMM DDR4 2666MT/s              | 1        | 1.33%   |
| Samsung RAM M393A2G40DB0-CPB 16GB DIMM DDR4 2133MT/s    | 1        | 1.33%   |
| Samsung RAM M393A1G43EB1-CRC 8GB DIMM DDR4 2400MT/s     | 1        | 1.33%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s     | 1        | 1.33%   |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR3 1867MT/s     | 1        | 1.33%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3266MT/s     | 1        | 1.33%   |
| Samsung RAM M3 78T5663EH3-CF7 2GB DIMM DDR2 800MT/s     | 1        | 1.33%   |
| Samsung RAM M3 78T2863EHS-CF7 1GB DIMM DDR2 800MT/s     | 1        | 1.33%   |
| Patriot RAM PSD416G26662 16GB DIMM DDR4 2667MT/s        | 1        | 1.33%   |
| Micron RAM Module 4GB DIMM DDR4 2133MT/s                | 1        | 1.33%   |
| Micron RAM 9ASF51272PZ-2G3B1 4GB RIMM DDR4 2400MT/s     | 1        | 1.33%   |
| Micron RAM 36ASF4G72PZ-2G3B1 32GB DIMM DDR4 2400MT/s    | 1        | 1.33%   |
| Micron RAM 18ASF2G72PDZ-2G6E1 16GB DIMM DDR4 2667MT/s   | 1        | 1.33%   |
| Micron RAM 18ASF2G72AZ-2G6D1 16GB DIMM DDR4 2667MT/s    | 1        | 1.33%   |
| Micron RAM 16JTF1G64AZ-1G6E1 8GB DIMM DDR3 1600MT/s     | 1        | 1.33%   |
| Micron RAM 16ATF1G64AZ-2G1B1 8GB DIMM DDR4 2133MT/s     | 1        | 1.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Desktops | Percent |
|--------|----------|---------|
| DDR4   | 40       | 63.49%  |
| DDR3   | 12       | 19.05%  |
| DRAM   | 4        | 6.35%   |
| SDRAM  | 3        | 4.76%   |
| DDR5   | 2        | 3.17%   |
| LPDDR4 | 1        | 1.59%   |
| DDR2   | 1        | 1.59%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 55       | 90.16%  |
| SODIMM       | 3        | 4.92%   |
| RIMM         | 2        | 3.28%   |
| Row Of Chips | 1        | 1.64%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 16384 | 24       | 35.82%  |
| 8192  | 23       | 34.33%  |
| 4096  | 10       | 14.93%  |
| 32768 | 5        | 7.46%   |
| 2048  | 3        | 4.48%   |
| 49152 | 1        | 1.49%   |
| 1024  | 1        | 1.49%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 2400  | 15       | 22.73%  |
| 1600  | 10       | 15.15%  |
| 3600  | 8        | 12.12%  |
| 2667  | 7        | 10.61%  |
| 2133  | 5        | 7.58%   |
| 3200  | 3        | 4.55%   |
| 1333  | 3        | 4.55%   |
| 6400  | 2        | 3.03%   |
| 3866  | 2        | 3.03%   |
| 2933  | 2        | 3.03%   |
| 2666  | 2        | 3.03%   |
| 4000  | 1        | 1.52%   |
| 3933  | 1        | 1.52%   |
| 3534  | 1        | 1.52%   |
| 3266  | 1        | 1.52%   |
| 2048  | 1        | 1.52%   |
| 1867  | 1        | 1.52%   |
| 800   | 1        | 1.52%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Hewlett-Packard    | 3        | 30%     |
| Canon              | 3        | 30%     |
| Seiko Epson        | 2        | 20%     |
| Kyocera            | 1        | 10%     |
| Brother Industries | 1        | 10%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seiko Epson XP-4100 Series       | 1        | 10%     |
| Seiko Epson WF-3520 Series       | 1        | 10%     |
| Kyocera FS-1030D printer         | 1        | 10%     |
| HP LaserJet Professional P 1102w | 1        | 10%     |
| HP LaserJet Pro M118-M119        | 1        | 10%     |
| HP DeskJet 3700 series           | 1        | 10%     |
| Canon PIXMA MG2500 Series        | 1        | 10%     |
| Canon E560 series                | 1        | 10%     |
| Canon CanoScan LiDE 300          | 1        | 10%     |
| Brother DCP-1610W                | 1        | 10%     |

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


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Logitech                    | 4        | 15.38%  |
| Samsung Electronics         | 3        | 11.54%  |
| Hopewin Electronic Material | 3        | 11.54%  |
| Generalplus Technology      | 3        | 11.54%  |
| Apple                       | 2        | 7.69%   |
| vivo                        | 1        | 3.85%   |
| Valve Software              | 1        | 3.85%   |
| Ruision                     | 1        | 3.85%   |
| Realtek Semiconductor       | 1        | 3.85%   |
| Owon                        | 1        | 3.85%   |
| Microsoft                   | 1        | 3.85%   |
| Microdia                    | 1        | 3.85%   |
| Jieli Technology            | 1        | 3.85%   |
| IMC Networks                | 1        | 3.85%   |
| Hewlett-Packard             | 1        | 3.85%   |
| ARC International           | 1        | 3.85%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Desktops | Percent |
|--------------------------------------------------|----------|---------|
| Samsung Galaxy series, misc. (MTP mode)          | 3        | 11.54%  |
| Hopewin Electronic Material FULL HD 1080P Webcam | 3        | 11.54%  |
| Generalplus GENERAL WEBCAM                       | 3        | 11.54%  |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR               | 2        | 7.69%   |
| vivo 1906                                        | 1        | 3.85%   |
| Valve Software 3D Camera                         | 1        | 3.85%   |
| Ruision UVC Camera                               | 1        | 3.85%   |
| Realtek FULL HD 1080P Webcam                     | 1        | 3.85%   |
| Owon USB CAMERA                                  | 1        | 3.85%   |
| Microsoft LifeCam HD-3000                        | 1        | 3.85%   |
| Microdia USB 2.0 Camera                          | 1        | 3.85%   |
| Logitech Webcam C310                             | 1        | 3.85%   |
| Logitech Webcam C270                             | 1        | 3.85%   |
| Logitech Webcam C250                             | 1        | 3.85%   |
| Logitech HD Webcam C910                          | 1        | 3.85%   |
| Jieli USB PHY 2.0                                | 1        | 3.85%   |
| IMC Networks HD Camera                           | 1        | 3.85%   |
| HP Webcam HD 4310                                | 1        | 3.85%   |
| ARC International Camera                         | 1        | 3.85%   |

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


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| SCM Microsystems      | 1        | 33.33%  |
| Giesecke & Devrient   | 1        | 33.33%  |
| Gemalto (was Gemplus) | 1        | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader | 1        | 33.33%  |
| Giesecke & Devrient StarSign CUT S                     | 1        | 33.33%  |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader      | 1        | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 86       | 70.49%  |
| 1     | 17       | 13.93%  |
| 2     | 15       | 12.3%   |
| 3     | 3        | 2.46%   |
| 5     | 1        | 0.82%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Unassigned class         | 16       | 28.57%  |
| Net/wireless             | 12       | 21.43%  |
| Graphics card            | 12       | 21.43%  |
| Communication controller | 10       | 17.86%  |
| Bluetooth                | 2        | 3.57%   |
| Storage/ide              | 1        | 1.79%   |
| Sound                    | 1        | 1.79%   |
| Net/ethernet             | 1        | 1.79%   |
| Firewire controller      | 1        | 1.79%   |

