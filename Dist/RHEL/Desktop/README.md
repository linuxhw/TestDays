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

Total: 140

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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


| Name   | Desktops | Percent |
|--------|----------|---------|
| RHEL 8 | 55       | 59.14%  |
| RHEL 9 | 25       | 26.88%  |
| RHEL 7 | 13       | 13.98%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| RHEL | 93       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Desktops | Percent |
|------------------------------|----------|---------|
| 4.18.0-305.el8.x86_64        | 7        | 6.36%   |
| 4.18.0-147.3.1.el8_1.x86_64  | 6        | 5.45%   |
| 5.14.0-162.6.1.el9_1.x86_64  | 5        | 4.55%   |
| 5.14.0-284.11.1.el9_2.x86_64 | 4        | 3.64%   |
| 4.18.0-348.20.1.el8_5.x86_64 | 4        | 3.64%   |
| 4.18.0-305.19.1.el8_4.x86_64 | 4        | 3.64%   |
| 4.18.0-240.1.1.el8_3.x86_64  | 4        | 3.64%   |
| 5.14.0-70.17.1.el9_0.x86_64  | 3        | 2.73%   |
| 5.14.0-284.25.1.el9_2.x86_64 | 3        | 2.73%   |
| 5.14.0-162.22.2.el9_1.x86_64 | 3        | 2.73%   |
| 4.18.0-348.12.2.el8_5.x86_64 | 3        | 2.73%   |
| 4.18.0-240.22.1.el8_3.x86_64 | 3        | 2.73%   |
| 4.18.0-240.10.1.el8_3.x86_64 | 3        | 2.73%   |
| 4.18.0-147.5.1.el8_1.x86_64  | 3        | 2.73%   |
| 3.10.0-862.3.2.el7.x86_64    | 3        | 2.73%   |
| 5.14.0-70.22.1.el9_0.x86_64  | 2        | 1.82%   |
| 5.14.0-284.30.1.el9_2.x86_64 | 2        | 1.82%   |
| 5.14.0-162.12.1.el9_1.x86_64 | 2        | 1.82%   |
| 4.18.0-348.2.1.el8_5.x86_64  | 2        | 1.82%   |
| 4.18.0-305.10.2.el8_4.x86_64 | 2        | 1.82%   |
| 4.18.0-240.15.1.el8_3.x86_64 | 2        | 1.82%   |
| 4.18.0-193.el8.x86_64        | 2        | 1.82%   |
| 4.18.0-193.6.3.el8_2.x86_64  | 2        | 1.82%   |
| 4.18.0-193.19.1.el8_2.x86_64 | 2        | 1.82%   |
| 4.18.0-147.el8.x86_64        | 2        | 1.82%   |
| 5.14.0-70.5.1.el9_0.x86_64   | 1        | 0.91%   |
| 5.14.0-284.18.1.el9_2.x86_64 | 1        | 0.91%   |
| 5.14.0-162.23.1.el9_1.x86_64 | 1        | 0.91%   |
| 5.10.6-1.el8.elrepo.x86_64   | 1        | 0.91%   |
| 4.19.150                     | 1        | 0.91%   |
| 4.18.0-80.11.2.el8_0.x86_64  | 1        | 0.91%   |
| 4.18.0-513.1.1.el8_9.x86_64  | 1        | 0.91%   |
| 4.18.0-477.15.1.el8_8.x86_64 | 1        | 0.91%   |
| 4.18.0-425.3.1.el8.x86_64    | 1        | 0.91%   |
| 4.18.0-425.10.1.el8_7.x86_64 | 1        | 0.91%   |
| 4.18.0-372.9.1.el8.x86_64    | 1        | 0.91%   |
| 4.18.0-372.32.1.el8_6.x86_64 | 1        | 0.91%   |
| 4.18.0-372.19.1.el8_6.x86_64 | 1        | 0.91%   |
| 4.18.0-348.7.1.el8_5.x86_64  | 1        | 0.91%   |
| 4.18.0-305.7.1.el8_4.x86_64  | 1        | 0.91%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 4.18.0   | 53       | 56.99%  |
| 5.14.0   | 25       | 26.88%  |
| 3.10.0   | 13       | 13.98%  |
| 5.10.6   | 1        | 1.08%   |
| 4.19.150 | 1        | 1.08%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.18    | 53       | 56.99%  |
| 5.14    | 25       | 26.88%  |
| 3.10    | 13       | 13.98%  |
| 5.10    | 1        | 1.08%   |
| 4.19    | 1        | 1.08%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 93       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 70       | 72.92%  |
| Unknown       | 16       | 16.67%  |
| GNOME Classic | 4        | 4.17%   |
| KDE5          | 2        | 2.08%   |
| KDE           | 2        | 2.08%   |
| MATE          | 1        | 1.04%   |
| KDE4          | 1        | 1.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 47       | 48.96%  |
| Wayland | 41       | 42.71%  |
| Unknown | 7        | 7.29%   |
| Tty     | 1        | 1.04%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 65       | 67.71%  |
| GDM     | 28       | 29.17%  |
| LightDM | 2        | 2.08%   |
| SDDM    | 1        | 1.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 47       | 50%     |
| Unknown | 13       | 13.83%  |
| en_GB   | 7        | 7.45%   |
| en_IN   | 4        | 4.26%   |
| ru_RU   | 3        | 3.19%   |
| en_NZ   | 3        | 3.19%   |
| pt_BR   | 2        | 2.13%   |
| pl_PL   | 2        | 2.13%   |
| es_ES   | 2        | 2.13%   |
| es_AR   | 2        | 2.13%   |
| de_DE   | 2        | 2.13%   |
| sl_SI   | 1        | 1.06%   |
| ko_KR   | 1        | 1.06%   |
| ja_JP   | 1        | 1.06%   |
| es_MX   | 1        | 1.06%   |
| en_ZA   | 1        | 1.06%   |
| en_CA   | 1        | 1.06%   |
| cs_CZ   | 1        | 1.06%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 59       | 62.77%  |
| BIOS | 35       | 37.23%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Xfs     | 85       | 90.43%  |
| Ext4    | 6        | 6.38%   |
| Unknown | 3        | 3.19%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 50       | 52.08%  |
| GPT     | 32       | 33.33%  |
| MBR     | 14       | 14.58%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 74       | 78.72%  |
| Yes       | 20       | 21.28%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 83       | 88.3%   |
| Yes       | 11       | 11.7%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 20       | 21.51%  |
| Dell                | 18       | 19.35%  |
| Hewlett-Packard     | 13       | 13.98%  |
| Gigabyte Technology | 12       | 12.9%   |
| MSI                 | 8        | 8.6%    |
| ASRock              | 7        | 7.53%   |
| Lenovo              | 4        | 4.3%    |
| Unknown             | 4        | 4.3%    |
| Intel               | 2        | 2.15%   |
| Supermicro          | 1        | 1.08%   |
| Hardkernel          | 1        | 1.08%   |
| CX / Air Computers. | 1        | 1.08%   |
| Alienware           | 1        | 1.08%   |
| Acer                | 1        | 1.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| Dell PowerEdge FC630                | 6        | 6.45%   |
| ASUS All Series                     | 4        | 4.3%    |
| Unknown                             | 4        | 4.3%    |
| HP Z620 Workstation                 | 2        | 2.15%   |
| Dell Precision Tower 5810           | 2        | 2.15%   |
| Dell OptiPlex 9020                  | 2        | 2.15%   |
| Supermicro X7DW3                    | 1        | 1.08%   |
| MSI MS-7D54                         | 1        | 1.08%   |
| MSI MS-7C95                         | 1        | 1.08%   |
| MSI MS-7B89                         | 1        | 1.08%   |
| MSI MS-7B51                         | 1        | 1.08%   |
| MSI MS-7B33                         | 1        | 1.08%   |
| MSI MS-7A71                         | 1        | 1.08%   |
| MSI MS-7A37                         | 1        | 1.08%   |
| MSI MS-7752                         | 1        | 1.08%   |
| Lenovo ThinkCentre M92p 3238AZ8     | 1        | 1.08%   |
| Lenovo ThinkCentre M920t 10SFS03200 | 1        | 1.08%   |
| Lenovo ThinkCentre M91p 0266RZ1     | 1        | 1.08%   |
| Lenovo 10SFS03200                   | 1        | 1.08%   |
| Intel H81                           | 1        | 1.08%   |
| Intel DX79SR AAG57199-200           | 1        | 1.08%   |
| HP Z840 Workstation                 | 1        | 1.08%   |
| HP Z800 Workstation                 | 1        | 1.08%   |
| HP Z440 Workstation                 | 1        | 1.08%   |
| HP Z230 Tower Workstation           | 1        | 1.08%   |
| HP Z230 SFF Workstation             | 1        | 1.08%   |
| HP Z1 Entry Tower G5                | 1        | 1.08%   |
| HP ProLiant ML310e Gen8             | 1        | 1.08%   |
| HP ProLiant MicroServer Gen8        | 1        | 1.08%   |
| HP EliteDesk 800 G2 SFF             | 1        | 1.08%   |
| HP 290 G1 SFF Business PC           | 1        | 1.08%   |
| HP 260-P020il                       | 1        | 1.08%   |
| Hardkernel ODROID-H3                | 1        | 1.08%   |
| Gigabyte Z97N-WIFI                  | 1        | 1.08%   |
| Gigabyte Z590I VISION D             | 1        | 1.08%   |
| Gigabyte Z490 GAMING X              | 1        | 1.08%   |
| Gigabyte Z390 AORUS ULTRA           | 1        | 1.08%   |
| Gigabyte X670E AORUS MASTER         | 1        | 1.08%   |
| Gigabyte X570 UD                    | 1        | 1.08%   |
| Gigabyte H510M H                    | 1        | 1.08%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| Dell PowerEdge       | 7        | 7.53%   |
| Dell Precision       | 6        | 6.45%   |
| ASUS PRIME           | 6        | 6.45%   |
| ASUS ROG             | 5        | 5.38%   |
| ASUS All             | 4        | 4.3%    |
| Unknown              | 4        | 4.3%    |
| Lenovo ThinkCentre   | 3        | 3.23%   |
| Dell OptiPlex        | 3        | 3.23%   |
| HP Z620              | 2        | 2.15%   |
| HP Z230              | 2        | 2.15%   |
| HP ProLiant          | 2        | 2.15%   |
| Supermicro X7DW3     | 1        | 1.08%   |
| MSI MS-7D54          | 1        | 1.08%   |
| MSI MS-7C95          | 1        | 1.08%   |
| MSI MS-7B89          | 1        | 1.08%   |
| MSI MS-7B51          | 1        | 1.08%   |
| MSI MS-7B33          | 1        | 1.08%   |
| MSI MS-7A71          | 1        | 1.08%   |
| MSI MS-7A37          | 1        | 1.08%   |
| MSI MS-7752          | 1        | 1.08%   |
| Lenovo 10SFS03200    | 1        | 1.08%   |
| Intel H81            | 1        | 1.08%   |
| Intel DX79SR         | 1        | 1.08%   |
| HP Z840              | 1        | 1.08%   |
| HP Z800              | 1        | 1.08%   |
| HP Z440              | 1        | 1.08%   |
| HP Z1                | 1        | 1.08%   |
| HP EliteDesk         | 1        | 1.08%   |
| HP 290               | 1        | 1.08%   |
| HP 260-P020il        | 1        | 1.08%   |
| Hardkernel ODROID-H3 | 1        | 1.08%   |
| Gigabyte Z97N-WIFI   | 1        | 1.08%   |
| Gigabyte Z590I       | 1        | 1.08%   |
| Gigabyte Z490        | 1        | 1.08%   |
| Gigabyte Z390        | 1        | 1.08%   |
| Gigabyte X670E       | 1        | 1.08%   |
| Gigabyte X570        | 1        | 1.08%   |
| Gigabyte H510M       | 1        | 1.08%   |
| Gigabyte B85M-D3V-A  | 1        | 1.08%   |
| Gigabyte B75-D3V     | 1        | 1.08%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2016 | 15       | 16.13%  |
| 2018 | 12       | 12.9%   |
| 2019 | 9        | 9.68%   |
| 2017 | 9        | 9.68%   |
| 2012 | 9        | 9.68%   |
| 2021 | 8        | 8.6%    |
| 2015 | 6        | 6.45%   |
| 2013 | 6        | 6.45%   |
| 2020 | 5        | 5.38%   |
| 2022 | 4        | 4.3%    |
| 2014 | 3        | 3.23%   |
| 2023 | 2        | 2.15%   |
| 2010 | 2        | 2.15%   |
| 2009 | 2        | 2.15%   |
| 2011 | 1        | 1.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 93       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 88       | 93.62%  |
| Enabled  | 6        | 6.38%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 93       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 64.01-256.0     | 23       | 23.96%  |
| 32.01-64.0      | 20       | 20.83%  |
| 8.01-16.0       | 16       | 16.67%  |
| 4.01-8.0        | 12       | 12.5%   |
| 16.01-24.0      | 12       | 12.5%   |
| 24.01-32.0      | 8        | 8.33%   |
| More than 256.0 | 2        | 2.08%   |
| 3.01-4.0        | 2        | 2.08%   |
| 2.01-3.0        | 1        | 1.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 30       | 28.04%  |
| 4.01-8.0   | 29       | 27.1%   |
| 3.01-4.0   | 17       | 15.89%  |
| 8.01-16.0  | 16       | 14.95%  |
| 1.01-2.0   | 10       | 9.35%   |
| 16.01-24.0 | 3        | 2.8%    |
| 24.01-32.0 | 1        | 0.93%   |
| 0.51-1.0   | 1        | 0.93%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 30       | 30.3%   |
| 1      | 23       | 23.23%  |
| 3      | 17       | 17.17%  |
| 5      | 10       | 10.1%   |
| 4      | 9        | 9.09%   |
| 12     | 3        | 3.03%   |
| 8      | 2        | 2.02%   |
| 6      | 2        | 2.02%   |
| 14     | 1        | 1.01%   |
| 10     | 1        | 1.01%   |
| 0      | 1        | 1.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 56       | 59.57%  |
| Yes       | 38       | 40.43%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 93       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 48       | 51.06%  |
| Yes       | 46       | 48.94%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 56       | 59.57%  |
| Yes       | 38       | 40.43%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 20       | 21.51%  |
| Germany      | 10       | 10.75%  |
| UK           | 8        | 8.6%    |
| India        | 6        | 6.45%   |
| Canada       | 6        | 6.45%   |
| Czechia      | 5        | 5.38%   |
| Russia       | 3        | 3.23%   |
| New Zealand  | 3        | 3.23%   |
| Brazil       | 3        | 3.23%   |
| Ukraine      | 2        | 2.15%   |
| Spain        | 2        | 2.15%   |
| South Korea  | 2        | 2.15%   |
| Poland       | 2        | 2.15%   |
| Italy        | 2        | 2.15%   |
| Argentina    | 2        | 2.15%   |
| Turkmenistan | 1        | 1.08%   |
| Switzerland  | 1        | 1.08%   |
| Sweden       | 1        | 1.08%   |
| South Africa | 1        | 1.08%   |
| Slovenia     | 1        | 1.08%   |
| Netherlands  | 1        | 1.08%   |
| Mexico       | 1        | 1.08%   |
| Lithuania    | 1        | 1.08%   |
| Japan        | 1        | 1.08%   |
| Indonesia    | 1        | 1.08%   |
| France       | 1        | 1.08%   |
| Finland      | 1        | 1.08%   |
| Egypt        | 1        | 1.08%   |
| China        | 1        | 1.08%   |
| Belgium      | 1        | 1.08%   |
| Belarus      | 1        | 1.08%   |
| Austria      | 1        | 1.08%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Petersberg            | 6        | 6.19%   |
| Prague                | 4        | 4.12%   |
| Wellington            | 2        | 2.06%   |
| Kyiv                  | 2        | 2.06%   |
| Chicago               | 2        | 2.06%   |
| Bengaluru             | 2        | 2.06%   |
| Yorktown Heights      | 1        | 1.03%   |
| Yongin-si             | 1        | 1.03%   |
| Wildomar              | 1        | 1.03%   |
| Wiesbaden             | 1        | 1.03%   |
| Vienna                | 1        | 1.03%   |
| Valencia              | 1        | 1.03%   |
| Vaglio                | 1        | 1.03%   |
| Turku                 | 1        | 1.03%   |
| Toronto               | 1        | 1.03%   |
| Tokyo                 | 1        | 1.03%   |
| Tiruchi               | 1        | 1.03%   |
| Tauranga              | 1        | 1.03%   |
| Sutton                | 1        | 1.03%   |
| Stavropol             | 1        | 1.03%   |
| Spokane               | 1        | 1.03%   |
| Šiauliai             | 1        | 1.03%   |
| Saratov               | 1        | 1.03%   |
| San Jose              | 1        | 1.03%   |
| San Fernando          | 1        | 1.03%   |
| Salvador              | 1        | 1.03%   |
| Saltillo              | 1        | 1.03%   |
| Sainte-Marie          | 1        | 1.03%   |
| Rosario               | 1        | 1.03%   |
| Rio de Janeiro        | 1        | 1.03%   |
| Ribeirao Preto        | 1        | 1.03%   |
| Rensselaer            | 1        | 1.03%   |
| Reading               | 1        | 1.03%   |
| Pforzheim             | 1        | 1.03%   |
| Pernis                | 1        | 1.03%   |
| Paracuellos de Jarama | 1        | 1.03%   |
| Oldham                | 1        | 1.03%   |
| Newham                | 1        | 1.03%   |
| Musselburgh           | 1        | 1.03%   |
| Montreal              | 1        | 1.03%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 35       | 71     | 17.95%  |
| WDC                       | 34       | 64     | 17.44%  |
| Samsung Electronics       | 23       | 51     | 11.79%  |
| Toshiba                   | 11       | 16     | 5.64%   |
| Kingston                  | 10       | 14     | 5.13%   |
| SanDisk                   | 8        | 17     | 4.1%    |
| Crucial                   | 7        | 12     | 3.59%   |
| Intel                     | 6        | 12     | 3.08%   |
| Phison                    | 5        | 9      | 2.56%   |
| SK hynix                  | 4        | 6      | 2.05%   |
| Hitachi                   | 4        | 4      | 2.05%   |
| Dell                      | 4        | 8      | 2.05%   |
| A-DATA Technology         | 4        | 4      | 2.05%   |
| Unknown                   | 3        | 5      | 1.54%   |
| PNY                       | 3        | 3      | 1.54%   |
| Micron/Crucial Technology | 3        | 4      | 1.54%   |
| Micron Technology         | 3        | 3      | 1.54%   |
| Gigabyte Technology       | 3        | 4      | 1.54%   |
| China                     | 3        | 3      | 1.54%   |
| HGST                      | 2        | 2      | 1.03%   |
| Corsair                   | 2        | 5      | 1.03%   |
| XUM                       | 1        | 1      | 0.51%   |
| XPG                       | 1        | 1      | 0.51%   |
| Western Digital           | 1        | 1      | 0.51%   |
| T-FORCE                   | 1        | 2      | 0.51%   |
| Silicon Motion            | 1        | 1      | 0.51%   |
| SCST_FIO                  | 1        | 9      | 0.51%   |
| SABRENT                   | 1        | 1      | 0.51%   |
| Phison Electronics        | 1        | 2      | 0.51%   |
| OCZ                       | 1        | 2      | 0.51%   |
| KingSpec                  | 1        | 1      | 0.51%   |
| KingFast                  | 1        | 1      | 0.51%   |
| KINGBANK                  | 1        | 1      | 0.51%   |
| HPT                       | 1        | 1      | 0.51%   |
| Hoodisk                   | 1        | 1      | 0.51%   |
| Hewlett-Packard           | 1        | 1      | 0.51%   |
| Fantom                    | 1        | 1      | 0.51%   |
| Anobit                    | 1        | 1      | 0.51%   |
| ADATA Technology          | 1        | 1      | 0.51%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Samsung SSD 860 EVO 1TB               | 4        | 1.62%   |
| Dell MD34xx 26TB                      | 4        | 1.62%   |
| Seagate ST2000DM001-1ER164 2TB        | 3        | 1.21%   |
| Samsung SSD 860 EVO 500GB             | 3        | 1.21%   |
| WDC WD40EFRX-68N32N0 4TB              | 2        | 0.81%   |
| WDC WD1003FZEX-00MK2A0 1TB            | 2        | 0.81%   |
| WDC WD1002FAEX-00Z3A0 1TB             | 2        | 0.81%   |
| Unknown SD/MMC/MS PRO 16GB            | 2        | 0.81%   |
| Toshiba NVMe SSD Drive 256GB          | 2        | 0.81%   |
| Toshiba DT01ACA200 2TB                | 2        | 0.81%   |
| Toshiba AL14SEB18EQ 1.8TB             | 2        | 0.81%   |
| Seagate ST91000640NS 1TB              | 2        | 0.81%   |
| Seagate ST500DM002-1BD142 500GB       | 2        | 0.81%   |
| Seagate ST2000NX0433 2TB              | 2        | 0.81%   |
| Seagate ST2000NX0273 2TB              | 2        | 0.81%   |
| Seagate ST1000DM010-2EP102 1TB        | 2        | 0.81%   |
| Seagate ST1000DM003-9YN162 1TB        | 2        | 0.81%   |
| Samsung SSD 850 EVO 250GB             | 2        | 0.81%   |
| Samsung NVMe SSD Drive 512GB          | 2        | 0.81%   |
| Samsung NVMe SSD Drive 500GB          | 2        | 0.81%   |
| Micron/Crucial P2 NVMe PCIe SSD 500GB | 2        | 0.81%   |
| Kingston SUV500120G 120GB SSD         | 2        | 0.81%   |
| Kingston SA400S37240G 240GB SSD       | 2        | 0.81%   |
| Intel SSD 660P Series 1024GB          | 2        | 0.81%   |
| Crucial CT240BX500SSD1 240GB          | 2        | 0.81%   |
| Corsair Force LE SSD 240GB            | 2        | 0.81%   |
| XUM HX256GSSDSATA3 256GB              | 1        | 0.4%    |
| XPG NVMe SSD Drive 1024GB             | 1        | 0.4%    |
| Western Digital NVMe SSD Drive 960GB  | 1        | 0.4%    |
| WDC WDS500G2B0A-00SM50 500GB SSD      | 1        | 0.4%    |
| WDC WDS250G2B0B-00YS70 250GB SSD      | 1        | 0.4%    |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 1        | 0.4%    |
| WDC WDS240G1G0A-00SS50 240GB SSD      | 1        | 0.4%    |
| WDC WDS100T2B0A-00SM50 1TB SSD        | 1        | 0.4%    |
| WDC WDBA3V5000ANC-WRSN 500GB          | 1        | 0.4%    |
| WDC WD80EFAX-68KNBN0 8TB              | 1        | 0.4%    |
| WDC WD7500BPKT-00PK4T0 752GB          | 1        | 0.4%    |
| WDC WD60 EFAX-68JH4N1 6TB             | 1        | 0.4%    |
| WDC WD60 EFAX-68JH4N0 6TB             | 1        | 0.4%    |
| WDC WD5003ABYZ-011FA0 500GB           | 1        | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 35       | 71     | 38.46%  |
| WDC                 | 31       | 58     | 34.07%  |
| Toshiba             | 9        | 13     | 9.89%   |
| Hitachi             | 4        | 4      | 4.4%    |
| Dell                | 4        | 8      | 4.4%    |
| Unknown             | 2        | 2      | 2.2%    |
| HGST                | 2        | 2      | 2.2%    |
| SCST_FIO            | 1        | 9      | 1.1%    |
| Samsung Electronics | 1        | 2      | 1.1%    |
| Hewlett-Packard     | 1        | 1      | 1.1%    |
| Fantom              | 1        | 1      | 1.1%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 16       | 33     | 23.53%  |
| Kingston            | 10       | 14     | 14.71%  |
| Crucial             | 7        | 11     | 10.29%  |
| WDC                 | 4        | 5      | 5.88%   |
| SanDisk             | 4        | 9      | 5.88%   |
| PNY                 | 3        | 3      | 4.41%   |
| Micron Technology   | 3        | 3      | 4.41%   |
| Intel               | 3        | 5      | 4.41%   |
| China               | 3        | 3      | 4.41%   |
| A-DATA Technology   | 3        | 3      | 4.41%   |
| SK hynix            | 2        | 4      | 2.94%   |
| Corsair             | 2        | 5      | 2.94%   |
| XUM                 | 1        | 1      | 1.47%   |
| SABRENT             | 1        | 1      | 1.47%   |
| OCZ                 | 1        | 2      | 1.47%   |
| KingSpec            | 1        | 1      | 1.47%   |
| KINGBANK            | 1        | 1      | 1.47%   |
| Hoodisk             | 1        | 1      | 1.47%   |
| Gigabyte Technology | 1        | 1      | 1.47%   |
| Anobit              | 1        | 1      | 1.47%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 66       | 171    | 40.74%  |
| SSD     | 59       | 107    | 36.42%  |
| NVMe    | 33       | 61     | 20.37%  |
| Unknown | 4        | 7      | 2.47%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 85       | 258    | 64.39%  |
| NVMe | 33       | 61     | 25%     |
| SAS  | 14       | 27     | 10.61%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 58       | 111    | 39.73%  |
| 0.51-1.0   | 39       | 66     | 26.71%  |
| 1.01-2.0   | 24       | 49     | 16.44%  |
| 3.01-4.0   | 10       | 20     | 6.85%   |
| 4.01-10.0  | 6        | 16     | 4.11%   |
| 20.01-50.0 | 4        | 8      | 2.74%   |
| 2.01-3.0   | 3        | 4      | 2.05%   |
| 10.01-20.0 | 2        | 4      | 1.37%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 22       | 22%     |
| 251-500        | 19       | 19%     |
| 501-1000       | 17       | 17%     |
| More than 3000 | 14       | 14%     |
| 1001-2000      | 10       | 10%     |
| Unknown        | 9        | 9%      |
| 2001-3000      | 5        | 5%      |
| 51-100         | 3        | 3%      |
| 21-50          | 1        | 1%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 21-50          | 24       | 22.64%  |
| 1-20           | 22       | 20.75%  |
| 101-250        | 14       | 13.21%  |
| 51-100         | 12       | 11.32%  |
| Unknown        | 9        | 8.49%   |
| 251-500        | 8        | 7.55%   |
| 1001-2000      | 5        | 4.72%   |
| More than 3000 | 4        | 3.77%   |
| 2001-3000      | 4        | 3.77%   |
| 501-1000       | 4        | 3.77%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Desktops | Drives | Percent |
|------------------------------------------|----------|--------|---------|
| WDC WD50 00LPVX-22V0TT0 500GB            | 1        | 1      | 11.11%  |
| WDC WD10EALX-759BA1 1TB                  | 1        | 2      | 11.11%  |
| Seagate ST91000640NS 1TB                 | 1        | 2      | 11.11%  |
| Seagate ST1000DM010-2EP102 1TB           | 1        | 1      | 11.11%  |
| Seagate ST1000DM003-9YN162 1TB           | 1        | 1      | 11.11%  |
| Micron Technology M510_2.5 7MM 256GB SSD | 1        | 1      | 11.11%  |
| Hitachi HDS722020ALA330 2TB              | 1        | 1      | 11.11%  |
| Crucial CT1000BX500SSD1 1TB              | 1        | 1      | 11.11%  |
| A-DATA Technology SU800NS38 256GB SSD    | 1        | 1      | 11.11%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Desktops | Drives | Percent |
|-------------------|----------|--------|---------|
| Seagate           | 3        | 4      | 33.33%  |
| WDC               | 2        | 3      | 22.22%  |
| Micron Technology | 1        | 1      | 11.11%  |
| Hitachi           | 1        | 1      | 11.11%  |
| Crucial           | 1        | 1      | 11.11%  |
| A-DATA Technology | 1        | 1      | 11.11%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 3        | 4      | 50%     |
| WDC     | 2        | 3      | 33.33%  |
| Hitachi | 1        | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 5        | 8      | 62.5%   |
| SSD  | 3        | 3      | 37.5%   |

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
| Detected | 54       | 204    | 52.43%  |
| Works    | 41       | 131    | 39.81%  |
| Malfunc  | 8        | 11     | 7.77%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 76       | 50.67%  |
| AMD                          | 18       | 12%     |
| Samsung Electronics          | 12       | 8%      |
| Broadcom / LSI               | 9        | 6%      |
| Phison Electronics           | 7        | 4.67%   |
| ASMedia Technology           | 5        | 3.33%   |
| SanDisk                      | 4        | 2.67%   |
| Micron/Crucial Technology    | 4        | 2.67%   |
| Marvell Technology Group     | 3        | 2%      |
| ADATA Technology             | 3        | 2%      |
| Toshiba America Info Systems | 2        | 1.33%   |
| SK hynix                     | 2        | 1.33%   |
| LSI Logic / Symbios Logic    | 2        | 1.33%   |
| Western Digital              | 1        | 0.67%   |
| Silicon Motion               | 1        | 0.67%   |
| HighPoint Technologies       | 1        | 0.67%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 14       | 7.53%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 12       | 6.45%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 11       | 5.91%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 10       | 5.38%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 9        | 4.84%   |
| Intel SATA Controller [RAID mode]                                              | 6        | 3.23%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 6        | 3.23%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 6        | 3.23%   |
| Broadcom / LSI MegaRAID SAS-3 3108 [Invader]                                   | 6        | 3.23%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 5        | 2.69%   |
| Broadcom / LSI SAS3008 PCI-Express Fusion-MPT SAS-3                            | 5        | 2.69%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 5        | 2.69%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 4        | 2.15%   |
| Phison E16 PCIe4 NVMe Controller                                               | 3        | 1.61%   |
| Phison E12 NVMe Controller                                                     | 3        | 1.61%   |
| Intel SSD 660P Series                                                          | 3        | 1.61%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 3        | 1.61%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 3        | 1.61%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 3        | 1.61%   |
| AMD 300 Series Chipset SATA Controller                                         | 3        | 1.61%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 2        | 1.08%   |
| SK hynix PC601 NVMe Solid State Drive                                          | 2        | 1.08%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 2        | 1.08%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 2        | 1.08%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 2        | 1.08%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 2        | 1.08%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                            | 2        | 1.08%   |
| Intel C600/X79 series chipset SATA RAID Controller                             | 2        | 1.08%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 2        | 1.08%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 2        | 1.08%   |
| AMD 500 Series Chipset SATA Controller                                         | 2        | 1.08%   |
| AMD 400 Series Chipset SATA Controller                                         | 2        | 1.08%   |
| ADATA ADATA XPG GAMMIXS1 1L Media (256 GB SSD)                                 | 2        | 1.08%   |
| Western Digital Ultrastar DC SN640 NVMe SSD                                    | 1        | 0.54%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 1        | 0.54%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1        | 0.54%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 1        | 0.54%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                          | 1        | 0.54%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 1        | 0.54%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1        | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 81       | 53.64%  |
| NVMe | 34       | 22.52%  |
| RAID | 21       | 13.91%  |
| SAS  | 10       | 6.62%   |
| IDE  | 5        | 3.31%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 75       | 80.65%  |
| AMD    | 18       | 19.35%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| AMD Ryzen 9 3900X 12-Core Processor     | 5        | 5.38%   |
| Intel Core i7-8700 CPU @ 3.20GHz        | 4        | 4.3%    |
| Intel 11th Gen Core i7-11700K @ 3.60GHz | 3        | 3.23%   |
| Intel Xeon CPU E5-2680 v3 @ 2.50GHz     | 2        | 2.15%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz     | 2        | 2.15%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz     | 2        | 2.15%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz     | 2        | 2.15%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz  | 2        | 2.15%   |
| Intel Core i7-8700K CPU @ 3.70GHz       | 2        | 2.15%   |
| Intel Core i7-7700K CPU @ 4.20GHz       | 2        | 2.15%   |
| Intel Core i7-7700 CPU @ 3.60GHz        | 2        | 2.15%   |
| Intel Core i3-4130 CPU @ 3.40GHz        | 2        | 2.15%   |
| AMD Ryzen 5 3600 6-Core Processor       | 2        | 2.15%   |
| Intel Xeon CPU X5570 @ 2.93GHz          | 1        | 1.08%   |
| Intel Xeon CPU E5472 @ 3.00GHz          | 1        | 1.08%   |
| Intel Xeon CPU E5-2696 v3 @ 2.30GHz     | 1        | 1.08%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz      | 1        | 1.08%   |
| Intel Xeon CPU E5-2680 v2 @ 2.80GHz     | 1        | 1.08%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz     | 1        | 1.08%   |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz      | 1        | 1.08%   |
| Intel Xeon CPU E5-1650 v4 @ 3.60GHz     | 1        | 1.08%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz     | 1        | 1.08%   |
| Intel Xeon CPU E5-1607 v4 @ 3.10GHz     | 1        | 1.08%   |
| Intel Xeon CPU E3-1280 V2 @ 3.60GHz     | 1        | 1.08%   |
| Intel Xeon CPU E3-1270 v5 @ 3.60GHz     | 1        | 1.08%   |
| Intel Xeon CPU E3-1240 v3 @ 3.40GHz     | 1        | 1.08%   |
| Intel Xeon CPU E3-1225 v5 @ 3.30GHz     | 1        | 1.08%   |
| Intel Pentium Silver N6005 @ 2.00GHz    | 1        | 1.08%   |
| Intel Core i9-9900 CPU @ 3.10GHz        | 1        | 1.08%   |
| Intel Core i9-10850K CPU @ 3.60GHz      | 1        | 1.08%   |
| Intel Core i7-9700F CPU @ 3.00GHz       | 1        | 1.08%   |
| Intel Core i7-7560U CPU @ 2.40GHz       | 1        | 1.08%   |
| Intel Core i7-4790K CPU @ 4.00GHz       | 1        | 1.08%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 1        | 1.08%   |
| Intel Core i7-4770K CPU @ 3.50GHz       | 1        | 1.08%   |
| Intel Core i7-3820 CPU @ 3.60GHz        | 1        | 1.08%   |
| Intel Core i7-3770K CPU @ 3.50GHz       | 1        | 1.08%   |
| Intel Core i7 CPU X 990 @ 3.47GHz       | 1        | 1.08%   |
| Intel Core i5-9600K CPU @ 3.70GHz       | 1        | 1.08%   |
| Intel Core i5-7500 CPU @ 3.40GHz        | 1        | 1.08%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Desktops | Percent |
|----------------------|----------|---------|
| Intel Xeon           | 22       | 23.66%  |
| Intel Core i7        | 18       | 19.35%  |
| Intel Core i5        | 14       | 15.05%  |
| Intel Core i3        | 8        | 8.6%    |
| AMD Ryzen 9          | 8        | 8.6%    |
| Other                | 6        | 6.45%   |
| AMD Ryzen 5          | 4        | 4.3%    |
| Intel Pentium Gold   | 2        | 2.15%   |
| Intel Core i9        | 2        | 2.15%   |
| AMD Ryzen 7          | 2        | 2.15%   |
| Intel Pentium Silver | 1        | 1.08%   |
| Intel Core 2 Duo     | 1        | 1.08%   |
| Intel Celeron        | 1        | 1.08%   |
| AMD Ryzen 3          | 1        | 1.08%   |
| AMD FX               | 1        | 1.08%   |
| AMD Athlon X4        | 1        | 1.08%   |
| AMD A4               | 1        | 1.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 32       | 34.41%  |
| 6      | 13       | 13.98%  |
| 2      | 13       | 13.98%  |
| 8      | 12       | 12.9%   |
| 12     | 11       | 11.83%  |
| 16     | 6        | 6.45%   |
| 36     | 1        | 1.08%   |
| 24     | 1        | 1.08%   |
| 20     | 1        | 1.08%   |
| 14     | 1        | 1.08%   |
| 10     | 1        | 1.08%   |
| 1      | 1        | 1.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 82       | 88.17%  |
| 2      | 11       | 11.83%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 68       | 72.34%  |
| 1      | 26       | 27.66%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 91       | 97.85%  |
| Unknown        | 2        | 2.15%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 12       | 12.9%   |
| 0x906ea    | 8        | 8.6%    |
| 0x306f2    | 8        | 8.6%    |
| 0x306a9    | 8        | 8.6%    |
| 0x08701021 | 5        | 5.38%   |
| 0xa0671    | 4        | 4.3%    |
| 0x906e9    | 4        | 4.3%    |
| 0x506e3    | 4        | 4.3%    |
| 0x406f1    | 4        | 4.3%    |
| Unknown    | 4        | 4.3%    |
| 0x906ed    | 3        | 3.23%   |
| 0x206d7    | 3        | 3.23%   |
| 0x906c0    | 2        | 2.15%   |
| 0x0a20120a | 2        | 2.15%   |
| 0x08701013 | 2        | 2.15%   |
| 0xb0671    | 1        | 1.08%   |
| 0xa0655    | 1        | 1.08%   |
| 0x906eb    | 1        | 1.08%   |
| 0x90672    | 1        | 1.08%   |
| 0x806e9    | 1        | 1.08%   |
| 0x306e4    | 1        | 1.08%   |
| 0x206c2    | 1        | 1.08%   |
| 0x206a7    | 1        | 1.08%   |
| 0x106a5    | 1        | 1.08%   |
| 0x1067a    | 1        | 1.08%   |
| 0x10676    | 1        | 1.08%   |
| 0x0a601203 | 1        | 1.08%   |
| 0x0a50000c | 1        | 1.08%   |
| 0x08108102 | 1        | 1.08%   |
| 0x0810100b | 1        | 1.08%   |
| 0x08001138 | 1        | 1.08%   |
| 0x08001137 | 1        | 1.08%   |
| 0x06006705 | 1        | 1.08%   |
| 0x0600611a | 1        | 1.08%   |
| 0x06000852 | 1        | 1.08%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 21       | 22.58%  |
| KabyLake         | 18       | 19.35%  |
| IvyBridge        | 10       | 10.75%  |
| Zen 2            | 7        | 7.53%   |
| Skylake          | 4        | 4.3%    |
| SandyBridge      | 4        | 4.3%    |
| Icelake          | 4        | 4.3%    |
| Broadwell        | 4        | 4.3%    |
| Zen 3            | 3        | 3.23%   |
| Zen              | 3        | 3.23%   |
| Tremont          | 2        | 2.15%   |
| Penryn           | 2        | 2.15%   |
| Excavator        | 2        | 2.15%   |
| CometLake        | 2        | 2.15%   |
| Alderlake Hybrid | 2        | 2.15%   |
| Zen+             | 1        | 1.08%   |
| Westmere         | 1        | 1.08%   |
| Piledriver       | 1        | 1.08%   |
| Nehalem          | 1        | 1.08%   |
| Unknown          | 1        | 1.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 49       | 45.37%  |
| Intel                      | 34       | 31.48%  |
| AMD                        | 18       | 16.67%  |
| Matrox Electronics Systems | 7        | 6.48%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Matrox Electronics Systems G200eR2                                          | 6        | 5.36%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 6        | 5.36%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 4        | 3.57%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 2.68%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 3        | 2.68%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3        | 2.68%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 3        | 2.68%   |
| Intel HD Graphics 630                                                       | 3        | 2.68%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3        | 2.68%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 3        | 2.68%   |
| Nvidia TU117GL [T400 4GB]                                                   | 2        | 1.79%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 2        | 1.79%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 2        | 1.79%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 1.79%   |
| Nvidia GK208B [GeForce GT 730]                                              | 2        | 1.79%   |
| Nvidia GF108GL [Quadro 600]                                                 | 2        | 1.79%   |
| Intel JasperLake [UHD Graphics]                                             | 2        | 1.79%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2        | 1.79%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]       | 2        | 1.79%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 2        | 1.79%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 0.89%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 0.89%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 1        | 0.89%   |
| Nvidia GT218 [GeForce G210]                                                 | 1        | 0.89%   |
| Nvidia GP107GL [Quadro P600]                                                | 1        | 0.89%   |
| Nvidia GP107GL [Quadro P400]                                                | 1        | 0.89%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 0.89%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 0.89%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 0.89%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1        | 0.89%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 0.89%   |
| Nvidia GM206GL [Quadro M2000]                                               | 1        | 0.89%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 0.89%   |
| Nvidia GM204GL [Quadro M4000]                                               | 1        | 0.89%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1        | 0.89%   |
| Nvidia GM107GL [Quadro K620]                                                | 1        | 0.89%   |
| Nvidia GM107GL [NVS 810]                                                    | 1        | 0.89%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 0.89%   |
| Nvidia GK106GL [Quadro K4000]                                               | 1        | 0.89%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 1        | 0.89%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 42       | 44.21%  |
| 1 x Intel      | 21       | 22.11%  |
| 1 x AMD        | 13       | 13.68%  |
| 1 x Matrox     | 7        | 7.37%   |
| Intel + Nvidia | 5        | 5.26%   |
| Intel + AMD    | 3        | 3.16%   |
| 2 x Nvidia     | 2        | 2.11%   |
| 2 x AMD        | 2        | 2.11%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 64       | 68.09%  |
| Proprietary | 23       | 24.47%  |
| Unknown     | 7        | 7.45%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 37       | 37.76%  |
| 1.01-2.0   | 16       | 16.33%  |
| 7.01-8.0   | 15       | 15.31%  |
| 3.01-4.0   | 8        | 8.16%   |
| 0.51-1.0   | 7        | 7.14%   |
| 0.01-0.5   | 5        | 5.1%    |
| 5.01-6.0   | 3        | 3.06%   |
| 2.01-3.0   | 3        | 3.06%   |
| 8.01-16.0  | 3        | 3.06%   |
| 16.01-24.0 | 1        | 1.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 19       | 19.39%  |
| Samsung Electronics  | 17       | 17.35%  |
| Goldstar             | 10       | 10.2%   |
| Hewlett-Packard      | 7        | 7.14%   |
| Lenovo               | 6        | 6.12%   |
| BenQ                 | 4        | 4.08%   |
| Acer                 | 4        | 4.08%   |
| ViewSonic            | 3        | 3.06%   |
| Philips              | 3        | 3.06%   |
| Ancor Communications | 3        | 3.06%   |
| Unknown              | 3        | 3.06%   |
| Lenovo Group Limited | 2        | 2.04%   |
| Iiyama               | 2        | 2.04%   |
| Gigabyte Technology  | 2        | 2.04%   |
| Eizo                 | 2        | 2.04%   |
| Vizio                | 1        | 1.02%   |
| STD                  | 1        | 1.02%   |
| Sony                 | 1        | 1.02%   |
| Panasonic            | 1        | 1.02%   |
| OUT                  | 1        | 1.02%   |
| Microstep            | 1        | 1.02%   |
| LG Electronics       | 1        | 1.02%   |
| Insignia             | 1        | 1.02%   |
| Haier                | 1        | 1.02%   |
| Deco Gear            | 1        | 1.02%   |
| AOC                  | 1        | 1.02%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Dell LCD Monitor DEL0001 1280x1024                                     | 6        | 5.5%    |
| Unknown                                                                | 3        | 2.75%   |
| Lenovo TIO24Gen3 LEN10B4 1920x1080 527x296mm 23.8-inch                 | 2        | 1.83%   |
| Lenovo LEN T2324pA LEN60C7 1920x1080 509x286mm 23.0-inch               | 2        | 1.83%   |
| Lenovo LEN P27u-10 LEN61B0 3840x2160 597x336mm 27.0-inch               | 2        | 1.83%   |
| Iiyama PL4840 IVM1065 1920x1080 1054x593mm 47.6-inch                   | 2        | 1.83%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 2        | 1.83%   |
| Acer ED322QR ACR06DD 1920x1080 700x390mm 31.5-inch                     | 2        | 1.83%   |
| Vizio E550i-B2 VIZ1004 1920x1080 477x268mm 21.5-inch                   | 1        | 0.92%   |
| ViewSonic VX2776 Series VSC3E32 1920x1080 598x336mm 27.0-inch          | 1        | 0.92%   |
| ViewSonic VA2419 Series VSC7B32 1920x1080 527x296mm 23.8-inch          | 1        | 0.92%   |
| ViewSonic VA2259 Series VSC5E32 1920x1080 476x268mm 21.5-inch          | 1        | 0.92%   |
| STD LED STD0110 1920x1080 480x260mm 21.5-inch                          | 1        | 0.92%   |
| Sony TV SNYD703 1360x768                                               | 1        | 0.92%   |
| Samsung Electronics SyncMaster SAM05FC 1920x1080                       | 1        | 0.92%   |
| Samsung Electronics SyncMaster SAM0566 1440x900 408x255mm 18.9-inch    | 1        | 0.92%   |
| Samsung Electronics SyncMaster SAM0526 1920x1080 510x287mm 23.0-inch   | 1        | 0.92%   |
| Samsung Electronics SyncMaster SAM0370 1680x1050 459x296mm 21.5-inch   | 1        | 0.92%   |
| Samsung Electronics SyncMaster SAM020D 1280x1024 338x270mm 17.0-inch   | 1        | 0.92%   |
| Samsung Electronics SMS23A550H SAM07CA 1920x1080 509x286mm 23.0-inch   | 1        | 0.92%   |
| Samsung Electronics S27C500 SAM0AF2 1920x1080 598x336mm 27.0-inch      | 1        | 0.92%   |
| Samsung Electronics S22E390 SAM0C18 1920x1080 477x268mm 21.5-inch      | 1        | 0.92%   |
| Samsung Electronics S22B300 SAM08A9 1600x900 443x249mm 20.0-inch       | 1        | 0.92%   |
| Samsung Electronics LCD Monitor SAM7106 1920x1080 530x300mm 24.0-inch  | 1        | 0.92%   |
| Samsung Electronics LCD Monitor SAM7103 3840x2160 700x390mm 31.5-inch  | 1        | 0.92%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 950x540mm 43.0-inch  | 1        | 0.92%   |
| Samsung Electronics LCD Monitor SAM0C04 3840x2160 1420x800mm 64.2-inch | 1        | 0.92%   |
| Samsung Electronics LCD Monitor SAM0B30 1920x1080 885x498mm 40.0-inch  | 1        | 0.92%   |
| Samsung Electronics LCD Monitor SAM0200 1280x720                       | 1        | 0.92%   |
| Samsung Electronics LCD Monitor S22B150                                | 1        | 0.92%   |
| Samsung Electronics LCD Monitor C49HG9x 3840x1080                      | 1        | 0.92%   |
| Samsung Electronics C32R50x SAM7000 1920x1080 698x393mm 31.5-inch      | 1        | 0.92%   |
| Samsung Electronics C32HG7x SAM0E14 2560x1440 697x392mm 31.5-inch      | 1        | 0.92%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 1        | 0.92%   |
| Philips PHL 322E1 PHLC20F 1920x1080 698x393mm 31.5-inch                | 1        | 0.92%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch                | 1        | 0.92%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 1        | 0.92%   |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                     | 1        | 0.92%   |
| OUT Analog OUT0096 1280x800 341x256mm 16.8-inch                        | 1        | 0.92%   |
| Microstep LCD Monitor MSI AG32CV 1920x1080                             | 1        | 0.92%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 44       | 46.32%  |
| 3840x2160 (4K)     | 9        | 9.47%   |
| 1280x1024 (SXGA)   | 8        | 8.42%   |
| 2560x1440 (QHD)    | 7        | 7.37%   |
| 3440x1440          | 4        | 4.21%   |
| 1600x900 (HD+)     | 4        | 4.21%   |
| 3840x1080          | 3        | 3.16%   |
| 2560x1080          | 3        | 3.16%   |
| Unknown            | 3        | 3.16%   |
| 1680x1050 (WSXGA+) | 2        | 2.11%   |
| 9600x2160          | 1        | 1.05%   |
| 7680x2160          | 1        | 1.05%   |
| 3840x1600          | 1        | 1.05%   |
| 3840x1200          | 1        | 1.05%   |
| 1920x1200 (WUXGA)  | 1        | 1.05%   |
| 1440x900 (WXGA+)   | 1        | 1.05%   |
| 1280x768           | 1        | 1.05%   |
| 1280x720 (HD)      | 1        | 1.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 19       | 19.39%  |
| 23      | 12       | 12.24%  |
| 21      | 11       | 11.22%  |
| 27      | 10       | 10.2%   |
| 24      | 10       | 10.2%   |
| 31      | 6        | 6.12%   |
| 54      | 4        | 4.08%   |
| 20      | 4        | 4.08%   |
| 34      | 3        | 3.06%   |
| 84      | 2        | 2.04%   |
| 47      | 2        | 2.04%   |
| 72      | 1        | 1.02%   |
| 64      | 1        | 1.02%   |
| 52      | 1        | 1.02%   |
| 43      | 1        | 1.02%   |
| 40      | 1        | 1.02%   |
| 39      | 1        | 1.02%   |
| 37      | 1        | 1.02%   |
| 35      | 1        | 1.02%   |
| 33      | 1        | 1.02%   |
| 28      | 1        | 1.02%   |
| 25      | 1        | 1.02%   |
| 19      | 1        | 1.02%   |
| 18      | 1        | 1.02%   |
| 17      | 1        | 1.02%   |
| 16      | 1        | 1.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 30       | 31.58%  |
| Unknown     | 19       | 20%     |
| 401-500     | 15       | 15.79%  |
| 601-700     | 8        | 8.42%   |
| 1001-1500   | 8        | 8.42%   |
| 801-900     | 4        | 4.21%   |
| 701-800     | 4        | 4.21%   |
| 1501-2000   | 3        | 3.16%   |
| 301-350     | 2        | 2.11%   |
| 351-400     | 1        | 1.05%   |
| 901-1000    | 1        | 1.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 56       | 65.12%  |
| Unknown | 11       | 12.79%  |
| 5/4     | 8        | 9.3%    |
| 21/9    | 6        | 6.98%   |
| 16/10   | 4        | 4.65%   |
| 4/3     | 1        | 1.16%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 28       | 29.17%  |
| Unknown        | 19       | 19.79%  |
| 351-500        | 11       | 11.46%  |
| 301-350        | 10       | 10.42%  |
| More than 1000 | 9        | 9.38%   |
| 151-200        | 7        | 7.29%   |
| 501-1000       | 6        | 6.25%   |
| 251-300        | 4        | 4.17%   |
| 141-150        | 1        | 1.04%   |
| 131-140        | 1        | 1.04%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 46       | 48.94%  |
| Unknown | 19       | 20.21%  |
| 101-120 | 17       | 18.09%  |
| 1-50    | 8        | 8.51%   |
| 161-240 | 3        | 3.19%   |
| 121-160 | 1        | 1.06%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 71       | 73.2%   |
| 2     | 12       | 12.37%  |
| 0     | 9        | 9.28%   |
| 3     | 5        | 5.15%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 60       | 43.8%   |
| Realtek Semiconductor    | 41       | 29.93%  |
| Broadcom                 | 11       | 8.03%   |
| Qualcomm Atheros         | 8        | 5.84%   |
| ASIX Electronics         | 3        | 2.19%   |
| Ralink Technology        | 2        | 1.46%   |
| Dell                     | 2        | 1.46%   |
| Ralink                   | 1        | 0.73%   |
| Microchip Technology     | 1        | 0.73%   |
| Micro Star International | 1        | 0.73%   |
| MediaTek                 | 1        | 0.73%   |
| Huawei Technologies      | 1        | 0.73%   |
| D-Link                   | 1        | 0.73%   |
| Broadcom Limited         | 1        | 0.73%   |
| ASUSTek Computer         | 1        | 0.73%   |
| Arduino SA               | 1        | 0.73%   |
| Aquantia                 | 1        | 0.73%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 29       | 16.11%  |
| Intel I211 Gigabit Network Connection                             | 8        | 4.44%   |
| Intel Ethernet Controller I225-V                                  | 7        | 3.89%   |
| Realtek RTL8125 2.5GbE Controller                                 | 6        | 3.33%   |
| Intel Ethernet Connection I217-LM                                 | 6        | 3.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6        | 3.33%   |
| Intel 82574L Gigabit Network Connection                           | 6        | 3.33%   |
| Intel Wi-Fi 6 AX200                                               | 5        | 2.78%   |
| Intel Ethernet Connection (2) I219-V                              | 5        | 2.78%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 4        | 2.22%   |
| Intel Ethernet Connection (7) I219-LM                             | 4        | 2.22%   |
| Intel Ethernet Connection (2) I219-LM                             | 4        | 2.22%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                | 4        | 2.22%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                  | 4        | 2.22%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 1.67%   |
| Intel I350 Gigabit Network Connection                             | 3        | 1.67%   |
| Intel Ethernet Connection (2) I218-V                              | 3        | 1.67%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3        | 1.67%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3        | 1.67%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter      | 3        | 1.67%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2        | 1.11%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 1.11%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2        | 1.11%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2        | 1.11%   |
| Intel Wireless-AC 9260                                            | 2        | 1.11%   |
| Intel I210 Gigabit Network Connection                             | 2        | 1.11%   |
| Intel Ethernet Connection I217-V                                  | 2        | 1.11%   |
| Intel Ethernet Connection (7) I219-V                              | 2        | 1.11%   |
| Intel Ethernet Connection (2) I218-LM                             | 2        | 1.11%   |
| Intel 82599 10 Gigabit Dual Port Backplane Connection             | 2        | 1.11%   |
| Dell iDRAC Virtual NIC                                            | 2        | 1.11%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2        | 1.11%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1        | 0.56%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 1        | 0.56%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1        | 0.56%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 1        | 0.56%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.56%   |
| Realtek 802.11n WLAN Adapter                                      | 1        | 0.56%   |
| Ralink RT5572 Wireless Adapter                                    | 1        | 0.56%   |
| Ralink RT5372 Wireless Adapter                                    | 1        | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 21       | 44.68%  |
| Realtek Semiconductor    | 7        | 14.89%  |
| Qualcomm Atheros         | 7        | 14.89%  |
| Broadcom                 | 5        | 10.64%  |
| Ralink Technology        | 2        | 4.26%   |
| Ralink                   | 1        | 2.13%   |
| Micro Star International | 1        | 2.13%   |
| MediaTek                 | 1        | 2.13%   |
| D-Link                   | 1        | 2.13%   |
| ASUSTek Computer         | 1        | 2.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                        | 5        | 10.64%  |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                     | 4        | 8.51%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                           | 3        | 6.38%   |
| Intel Cannon Lake PCH CNVi WiFi                                            | 3        | 6.38%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter               | 3        | 6.38%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 2        | 4.26%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                 | 2        | 4.26%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                           | 2        | 4.26%   |
| Intel Wireless-AC 9260                                                     | 2        | 4.26%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                            | 1        | 2.13%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                 | 1        | 2.13%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                            | 1        | 2.13%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                            | 1        | 2.13%   |
| Realtek 802.11n WLAN Adapter                                               | 1        | 2.13%   |
| Ralink RT5572 Wireless Adapter                                             | 1        | 2.13%   |
| Ralink RT5372 Wireless Adapter                                             | 1        | 2.13%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                  | 1        | 2.13%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                           | 1        | 2.13%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)             | 1        | 2.13%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                           | 1        | 2.13%   |
| Micro Star International MS-3871 802.11bgn Wireless Module [Ralink RT8070] | 1        | 2.13%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                         | 1        | 2.13%   |
| Intel Wireless 7260                                                        | 1        | 2.13%   |
| Intel Wi-Fi 6 AX201 160MHz                                                 | 1        | 2.13%   |
| Intel Comet Lake PCH CNVi WiFi                                             | 1        | 2.13%   |
| Intel Alder Lake-S PCH CNVi WiFi                                           | 1        | 2.13%   |
| D-Link DWA-171 AC600 DB Wireless Adapter(rev.A1) [Realtek RTL8811AU]       | 1        | 2.13%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter               | 1        | 2.13%   |
| Broadcom BCM4321 802.11b/g/n                                               | 1        | 2.13%   |
| ASUS WL-167G v3 802.11n Adapter [Realtek RTL8188SU]                        | 1        | 2.13%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 56       | 50.45%  |
| Realtek Semiconductor | 39       | 35.14%  |
| Broadcom              | 7        | 6.31%   |
| ASIX Electronics      | 3        | 2.7%    |
| Qualcomm Atheros      | 2        | 1.8%    |
| Dell                  | 2        | 1.8%    |
| Broadcom Limited      | 1        | 0.9%    |
| Aquantia              | 1        | 0.9%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 29       | 22.31%  |
| Intel I211 Gigabit Network Connection                                         | 8        | 6.15%   |
| Intel Ethernet Controller I225-V                                              | 7        | 5.38%   |
| Realtek RTL8125 2.5GbE Controller                                             | 6        | 4.62%   |
| Intel Ethernet Connection I217-LM                                             | 6        | 4.62%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 6        | 4.62%   |
| Intel 82574L Gigabit Network Connection                                       | 6        | 4.62%   |
| Intel Ethernet Connection (2) I219-V                                          | 5        | 3.85%   |
| Intel Ethernet Connection (7) I219-LM                                         | 4        | 3.08%   |
| Intel Ethernet Connection (2) I219-LM                                         | 4        | 3.08%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 4        | 3.08%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 4        | 3.08%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 3        | 2.31%   |
| Intel I350 Gigabit Network Connection                                         | 3        | 2.31%   |
| Intel Ethernet Connection (2) I218-V                                          | 3        | 2.31%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 2        | 1.54%   |
| Intel I210 Gigabit Network Connection                                         | 2        | 1.54%   |
| Intel Ethernet Connection I217-V                                              | 2        | 1.54%   |
| Intel Ethernet Connection (7) I219-V                                          | 2        | 1.54%   |
| Intel Ethernet Connection (2) I218-LM                                         | 2        | 1.54%   |
| Intel 82599 10 Gigabit Dual Port Backplane Connection                         | 2        | 1.54%   |
| Dell iDRAC Virtual NIC                                                        | 2        | 1.54%   |
| ASIX AX88179 Gigabit Ethernet                                                 | 2        | 1.54%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 0.77%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 1        | 0.77%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1        | 0.77%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 1        | 0.77%   |
| Intel Ethernet Connection (11) I219-V                                         | 1        | 0.77%   |
| Intel 82579V Gigabit Network Connection                                       | 1        | 0.77%   |
| Intel 82575EB Gigabit Network Connection                                      | 1        | 0.77%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 0.77%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 1        | 0.77%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1        | 0.77%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 1        | 0.77%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 1        | 0.77%   |
| Broadcom NetXtreme BCM5717 Gigabit Ethernet PCIe                              | 1        | 0.77%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express               | 1        | 0.77%   |
| ASIX AX88772A Fast Ethernet                                                   | 1        | 0.77%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 1        | 0.77%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 93       | 65.49%  |
| WiFi     | 46       | 32.39%  |
| Modem    | 3        | 2.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 79       | 84.04%  |
| WiFi     | 15       | 15.96%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 39       | 41.05%  |
| 2     | 29       | 30.53%  |
| 3     | 15       | 15.79%  |
| 4     | 6        | 6.32%   |
| 6     | 5        | 5.26%   |
| 5     | 1        | 1.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 77       | 81.05%  |
| Yes  | 18       | 18.95%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 19       | 48.72%  |
| Cambridge Silicon Radio         | 8        | 20.51%  |
| ASUSTek Computer                | 4        | 10.26%  |
| Realtek Semiconductor           | 2        | 5.13%   |
| Qualcomm Atheros Communications | 2        | 5.13%   |
| Micro Star International        | 1        | 2.56%   |
| Integrated System Solution      | 1        | 2.56%   |
| IMC Networks                    | 1        | 2.56%   |
| Broadcom                        | 1        | 2.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 8        | 20.51%  |
| Intel AX210 Bluetooth                                 | 4        | 10.26%  |
| Intel AX200 Bluetooth                                 | 4        | 10.26%  |
| Intel Wireless-AC 3168 Bluetooth                      | 3        | 7.69%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 3        | 7.69%   |
| Intel AX201 Bluetooth                                 | 3        | 7.69%   |
| Realtek Bluetooth Radio                               | 2        | 5.13%   |
| Qualcomm Atheros  Bluetooth Device                    | 2        | 5.13%   |
| ASUS BCM20702A0                                       | 2        | 5.13%   |
| Micro Star International Bluetooth Device             | 1        | 2.56%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 1        | 2.56%   |
| Intel Bluetooth wireless interface                    | 1        | 2.56%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1        | 2.56%   |
| IMC Networks BCM20702A0                               | 1        | 2.56%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 1        | 2.56%   |
| ASUS Qualcomm Bluetooth 4.1                           | 1        | 2.56%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 2.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 64       | 39.51%  |
| Nvidia                                       | 46       | 28.4%   |
| AMD                                          | 24       | 14.81%  |
| Texas Instruments                            | 3        | 1.85%   |
| Lenovo                                       | 3        | 1.85%   |
| Creative Labs                                | 3        | 1.85%   |
| Plantronics                                  | 2        | 1.23%   |
| Logitech                                     | 2        | 1.23%   |
| ASUSTek Computer                             | 2        | 1.23%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 0.62%   |
| Tenx Technology                              | 1        | 0.62%   |
| SteelSeries ApS                              | 1        | 0.62%   |
| Sennheiser Communications                    | 1        | 0.62%   |
| RODE Microphones                             | 1        | 0.62%   |
| Micro Star International                     | 1        | 0.62%   |
| JMTek                                        | 1        | 0.62%   |
| Giga-Byte Technology                         | 1        | 0.62%   |
| Dynex                                        | 1        | 0.62%   |
| Creative Technology                          | 1        | 0.62%   |
| C-Media Electronics                          | 1        | 0.62%   |
| Blue Microphones                             | 1        | 0.62%   |
| Astro Gaming                                 | 1        | 0.62%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 10       | 5.52%   |
| Intel Cannon Lake PCH cAVS                                                 | 9        | 4.97%   |
| AMD Starship/Matisse HD Audio Controller                                   | 8        | 4.42%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 7        | 3.87%   |
| Nvidia GP107GL High Definition Audio Controller                            | 6        | 3.31%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 6        | 3.31%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 6        | 3.31%   |
| Nvidia GP104 High Definition Audio Controller                              | 5        | 2.76%   |
| Intel 200 Series PCH HD Audio                                              | 5        | 2.76%   |
| Nvidia GF108 High Definition Audio Controller                              | 4        | 2.21%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4        | 2.21%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 4        | 2.21%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4        | 2.21%   |
| AMD Family 17h/19h HD Audio Controller                                     | 4        | 2.21%   |
| Texas Instruments PCM2902 Audio Codec                                      | 3        | 1.66%   |
| Nvidia TU106 High Definition Audio Controller                              | 3        | 1.66%   |
| Nvidia GP106 High Definition Audio Controller                              | 3        | 1.66%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3        | 1.66%   |
| Lenovo Thinkcentre TIO24Gen3 for USB-audio                                 | 3        | 1.66%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3        | 1.66%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3        | 1.66%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 3        | 1.66%   |
| Nvidia TU116 High Definition Audio Controller                              | 2        | 1.1%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2        | 1.1%    |
| Nvidia TU104 HD Audio Controller                                           | 2        | 1.1%    |
| Nvidia GM206 High Definition Audio Controller                              | 2        | 1.1%    |
| Nvidia GM204 High Definition Audio Controller                              | 2        | 1.1%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2        | 1.1%    |
| Nvidia GK106 HDMI Audio Controller                                         | 2        | 1.1%    |
| Nvidia GA102 High Definition Audio Controller                              | 2        | 1.1%    |
| Intel Jasper Lake HD Audio                                                 | 2        | 1.1%    |
| Intel Comet Lake PCH cAVS                                                  | 2        | 1.1%    |
| Intel Alder Lake-S HD Audio Controller                                     | 2        | 1.1%    |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2        | 1.1%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 1.1%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2        | 1.1%    |
| AMD Navi 10 HDMI Audio                                                     | 2        | 1.1%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 2        | 1.1%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2        | 1.1%    |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID             | 1        | 0.55%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| SK hynix            | 8        | 14.81%  |
| Samsung Electronics | 8        | 14.81%  |
| Micron Technology   | 7        | 12.96%  |
| Crucial             | 7        | 12.96%  |
| Corsair             | 6        | 11.11%  |
| Kingston            | 5        | 9.26%   |
| G.Skill             | 4        | 7.41%   |
| Unknown             | 3        | 5.56%   |
| Unknown (0x0205)    | 1        | 1.85%   |
| Transcend           | 1        | 1.85%   |
| Team                | 1        | 1.85%   |
| Patriot             | 1        | 1.85%   |
| Hewlett-Packard     | 1        | 1.85%   |
| GOODRAM             | 1        | 1.85%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| SK hynix RAM HMA82GR7MFR8N-UH 16GB DIMM DDR4 2400MT/s   | 2        | 3.39%   |
| SK hynix RAM HMA42GR7MFR4N-TF 16GB DIMM DDR4 2133MT/s   | 2        | 3.39%   |
| Samsung RAM M378A2K43CB1-CTD 16384MB DIMM DDR4 3200MT/s | 2        | 3.39%   |
| Micron RAM 36ASF2G72PZ-2G1A2 16GB DIMM DDR4 2133MT/s    | 2        | 3.39%   |
| Corsair RAM CMK64GX4M2D3600C18 32GB DIMM DDR4 3600MT/s  | 2        | 3.39%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s   | 2        | 3.39%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s               | 1        | 1.69%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s            | 1        | 1.69%   |
| Unknown RAM Module 2GB DIMM DDR3 1600MT/s               | 1        | 1.69%   |
| Unknown (0x0205) RAM Module 8GB DIMM DDR3 1600MT/s      | 1        | 1.69%   |
| Transcend RAM TS1GLK72V3H 8GB DIMM DDR3 1333MT/s        | 1        | 1.69%   |
| Team RAM TEAMGROUP-ED4-2400 16GB DIMM DDR4 2400MT/s     | 1        | 1.69%   |
| SK hynix RAM Module 16GB Row Of Chips LPDDR4 2933MT/s   | 1        | 1.69%   |
| SK hynix RAM HMT351S6EFR8C-PB 4096MB DIMM DDR3 1333MT/s | 1        | 1.69%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB DIMM DDR3 1333MT/s | 1        | 1.69%   |
| SK hynix RAM HMA851U6CJR6N-VK 4GB DIMM DDR4 2667MT/s    | 1        | 1.69%   |
| SK hynix RAM HMA81GU7AFR8N-UH 8GB DIMM DDR4 2400MT/s    | 1        | 1.69%   |
| Samsung RAM Module 8GB DIMM DDR4 2666MT/s               | 1        | 1.69%   |
| Samsung RAM Module 4GB DIMM DDR4 2133MT/s               | 1        | 1.69%   |
| Samsung RAM Module 16GB DIMM DDR4 2666MT/s              | 1        | 1.69%   |
| Samsung RAM M393A2G40DB0-CPB 16GB DIMM DDR4 2133MT/s    | 1        | 1.69%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM 1600MT/s          | 1        | 1.69%   |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR3 1867MT/s     | 1        | 1.69%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3266MT/s     | 1        | 1.69%   |
| Samsung RAM M3 78T5663EH3-CF7 2GB DIMM DDR2 800MT/s     | 1        | 1.69%   |
| Samsung RAM M3 78T2863EHS-CF7 1GB DIMM DDR2 800MT/s     | 1        | 1.69%   |
| Patriot RAM PSD416G26662 16GB DIMM DDR4 2667MT/s        | 1        | 1.69%   |
| Micron RAM Module 4GB DIMM DDR4 2133MT/s                | 1        | 1.69%   |
| Micron RAM 9ASF51272PZ-2G3B1 4GB RIMM DDR4 2400MT/s     | 1        | 1.69%   |
| Micron RAM 36ASF4G72PZ-2G3B1 32GB DIMM DDR4 2400MT/s    | 1        | 1.69%   |
| Micron RAM 16JTF1G64AZ-1G6E1 8GB DIMM DDR3 1600MT/s     | 1        | 1.69%   |
| Micron RAM 16ATF1G64AZ-2G1B1 8GB DIMM DDR4 2133MT/s     | 1        | 1.69%   |
| Kingston RAM KHX2666C13/16GX 16GB DIMM DDR4 3200MT/s    | 1        | 1.69%   |
| Kingston RAM KHX2400C12D4/8GX 8GB DIMM DDR4 2400MT/s    | 1        | 1.69%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s     | 1        | 1.69%   |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3933MT/s   | 1        | 1.69%   |
| Kingston RAM 9905712-034.A00G 16GB SODIMM DDR4 2400MT/s | 1        | 1.69%   |
| HP RAM 669237-071 2GB DIMM DDR3 1600MT/s                | 1        | 1.69%   |
| GOODRAM RAM GR1600D364L11S/4G 4GB DIMM DDR3 1600MT/s    | 1        | 1.69%   |
| G.Skill RAM F5-6000J3636F16G 16GB DIMM DDR5 6400MT/s    | 1        | 1.69%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Desktops | Percent |
|--------|----------|---------|
| DDR4   | 28       | 58.33%  |
| DDR3   | 11       | 22.92%  |
| SDRAM  | 3        | 6.25%   |
| DRAM   | 3        | 6.25%   |
| LPDDR4 | 1        | 2.08%   |
| DDR5   | 1        | 2.08%   |
| DDR2   | 1        | 2.08%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 42       | 91.3%   |
| SODIMM       | 2        | 4.35%   |
| Row Of Chips | 1        | 2.17%   |
| RIMM         | 1        | 2.17%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 16384 | 17       | 32.69%  |
| 8192  | 17       | 32.69%  |
| 4096  | 10       | 19.23%  |
| 32768 | 4        | 7.69%   |
| 2048  | 3        | 5.77%   |
| 1024  | 1        | 1.92%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 2400  | 10       | 19.61%  |
| 3600  | 9        | 17.65%  |
| 1600  | 9        | 17.65%  |
| 2133  | 6        | 11.76%  |
| 1333  | 3        | 5.88%   |
| 3200  | 2        | 3.92%   |
| 2933  | 2        | 3.92%   |
| 2667  | 2        | 3.92%   |
| 6400  | 1        | 1.96%   |
| 3933  | 1        | 1.96%   |
| 3266  | 1        | 1.96%   |
| 2666  | 1        | 1.96%   |
| 2472  | 1        | 1.96%   |
| 2048  | 1        | 1.96%   |
| 1867  | 1        | 1.96%   |
| 800   | 1        | 1.96%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Canon              | 3        | 42.86%  |
| Seiko Epson        | 2        | 28.57%  |
| Hewlett-Packard    | 1        | 14.29%  |
| Brother Industries | 1        | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seiko Epson XP-4100 Series       | 1        | 14.29%  |
| Seiko Epson WF-3520 Series       | 1        | 14.29%  |
| HP LaserJet Professional P 1102w | 1        | 14.29%  |
| Canon PIXMA MG2500 Series        | 1        | 14.29%  |
| Canon LiDE 300                   | 1        | 14.29%  |
| Canon E560 series                | 1        | 14.29%  |
| Brother DCP-1610W                | 1        | 14.29%  |

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
| Logitech                    | 3        | 15%     |
| Hopewin Electronic Material | 3        | 15%     |
| Generalplus Technology      | 2        | 10%     |
| Apple                       | 2        | 10%     |
| vivo                        | 1        | 5%      |
| Samsung Electronics         | 1        | 5%      |
| Ruision                     | 1        | 5%      |
| Realtek Semiconductor       | 1        | 5%      |
| Owon                        | 1        | 5%      |
| Microsoft                   | 1        | 5%      |
| Microdia                    | 1        | 5%      |
| Jieli Technology            | 1        | 5%      |
| IMC Networks                | 1        | 5%      |
| ARC International           | 1        | 5%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Desktops | Percent |
|--------------------------------------------------|----------|---------|
| Hopewin Electronic Material FULL HD 1080P Webcam | 3        | 15%     |
| Generalplus GENERAL WEBCAM                       | 2        | 10%     |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                  | 2        | 10%     |
| vivo V2023                                       | 1        | 5%      |
| Samsung Galaxy series, misc. (MTP mode)          | 1        | 5%      |
| Ruision UVC Camera                               | 1        | 5%      |
| Realtek Full HD webcam                           | 1        | 5%      |
| Owon USB CAMERA                                  | 1        | 5%      |
| Microsoft LifeCam HD-3000                        | 1        | 5%      |
| Microdia USB 2.0 Camera                          | 1        | 5%      |
| Logitech Webcam C270                             | 1        | 5%      |
| Logitech Webcam C250                             | 1        | 5%      |
| Logitech HD Webcam C910                          | 1        | 5%      |
| Jieli USB PHY 2.0                                | 1        | 5%      |
| IMC Networks XHC Camera                          | 1        | 5%      |
| ARC International Camera                         | 1        | 5%      |

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
| SCM Microsystems      | 1        | 50%     |
| Gemalto (was Gemplus) | 1        | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader | 1        | 50%     |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader      | 1        | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 70       | 73.68%  |
| 1     | 13       | 13.68%  |
| 2     | 10       | 10.53%  |
| 5     | 1        | 1.05%   |
| 3     | 1        | 1.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Unassigned class         | 14       | 36.84%  |
| Net/wireless             | 7        | 18.42%  |
| Graphics card            | 7        | 18.42%  |
| Communication controller | 7        | 18.42%  |
| Storage/ide              | 1        | 2.63%   |
| Sound                    | 1        | 2.63%   |
| Bluetooth                | 1        | 2.63%   |

