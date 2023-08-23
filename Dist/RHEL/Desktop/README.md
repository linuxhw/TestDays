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

Total: 131

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| RHEL 8 | 54       | 62.07%  |
| RHEL 9 | 21       | 24.14%  |
| RHEL 7 | 12       | 13.79%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| RHEL | 87       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Desktops | Percent |
|------------------------------|----------|---------|
| 4.18.0-305.el8.x86_64        | 7        | 6.8%    |
| 4.18.0-147.3.1.el8_1.x86_64  | 6        | 5.83%   |
| 5.14.0-162.6.1.el9_1.x86_64  | 5        | 4.85%   |
| 4.18.0-348.20.1.el8_5.x86_64 | 4        | 3.88%   |
| 4.18.0-305.19.1.el8_4.x86_64 | 4        | 3.88%   |
| 4.18.0-240.1.1.el8_3.x86_64  | 4        | 3.88%   |
| 5.14.0-70.17.1.el9_0.x86_64  | 3        | 2.91%   |
| 5.14.0-284.11.1.el9_2.x86_64 | 3        | 2.91%   |
| 5.14.0-162.22.2.el9_1.x86_64 | 3        | 2.91%   |
| 4.18.0-348.12.2.el8_5.x86_64 | 3        | 2.91%   |
| 4.18.0-240.22.1.el8_3.x86_64 | 3        | 2.91%   |
| 4.18.0-240.10.1.el8_3.x86_64 | 3        | 2.91%   |
| 4.18.0-147.5.1.el8_1.x86_64  | 3        | 2.91%   |
| 3.10.0-862.3.2.el7.x86_64    | 3        | 2.91%   |
| 5.14.0-70.22.1.el9_0.x86_64  | 2        | 1.94%   |
| 5.14.0-162.12.1.el9_1.x86_64 | 2        | 1.94%   |
| 4.18.0-348.2.1.el8_5.x86_64  | 2        | 1.94%   |
| 4.18.0-305.10.2.el8_4.x86_64 | 2        | 1.94%   |
| 4.18.0-240.15.1.el8_3.x86_64 | 2        | 1.94%   |
| 4.18.0-193.el8.x86_64        | 2        | 1.94%   |
| 4.18.0-193.6.3.el8_2.x86_64  | 2        | 1.94%   |
| 4.18.0-193.19.1.el8_2.x86_64 | 2        | 1.94%   |
| 4.18.0-147.el8.x86_64        | 2        | 1.94%   |
| 5.14.0-70.5.1.el9_0.x86_64   | 1        | 0.97%   |
| 5.14.0-284.25.1.el9_2.x86_64 | 1        | 0.97%   |
| 5.14.0-284.18.1.el9_2.x86_64 | 1        | 0.97%   |
| 5.14.0-162.23.1.el9_1.x86_64 | 1        | 0.97%   |
| 5.10.6-1.el8.elrepo.x86_64   | 1        | 0.97%   |
| 4.19.150                     | 1        | 0.97%   |
| 4.18.0-80.11.2.el8_0.x86_64  | 1        | 0.97%   |
| 4.18.0-477.15.1.el8_8.x86_64 | 1        | 0.97%   |
| 4.18.0-425.3.1.el8.x86_64    | 1        | 0.97%   |
| 4.18.0-425.10.1.el8_7.x86_64 | 1        | 0.97%   |
| 4.18.0-372.9.1.el8.x86_64    | 1        | 0.97%   |
| 4.18.0-372.32.1.el8_6.x86_64 | 1        | 0.97%   |
| 4.18.0-372.19.1.el8_6.x86_64 | 1        | 0.97%   |
| 4.18.0-348.7.1.el8_5.x86_64  | 1        | 0.97%   |
| 4.18.0-305.7.1.el8_4.x86_64  | 1        | 0.97%   |
| 4.18.0-305.3.1.el8_4.x86_64  | 1        | 0.97%   |
| 4.18.0-305.17.1.el8_4.x86_64 | 1        | 0.97%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 4.18.0   | 52       | 59.77%  |
| 5.14.0   | 21       | 24.14%  |
| 3.10.0   | 12       | 13.79%  |
| 5.10.6   | 1        | 1.15%   |
| 4.19.150 | 1        | 1.15%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.18    | 52       | 59.77%  |
| 5.14    | 21       | 24.14%  |
| 3.10    | 12       | 13.79%  |
| 5.10    | 1        | 1.15%   |
| 4.19    | 1        | 1.15%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 87       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 65       | 72.22%  |
| Unknown       | 16       | 17.78%  |
| GNOME Classic | 4        | 4.44%   |
| KDE5          | 2        | 2.22%   |
| KDE           | 2        | 2.22%   |
| MATE          | 1        | 1.11%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 44       | 48.89%  |
| Wayland | 38       | 42.22%  |
| Unknown | 7        | 7.78%   |
| Tty     | 1        | 1.11%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 62       | 68.89%  |
| GDM     | 26       | 28.89%  |
| SDDM    | 1        | 1.11%   |
| LightDM | 1        | 1.11%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 45       | 51.14%  |
| Unknown | 13       | 14.77%  |
| en_GB   | 6        | 6.82%   |
| en_IN   | 4        | 4.55%   |
| ru_RU   | 3        | 3.41%   |
| pl_PL   | 2        | 2.27%   |
| es_ES   | 2        | 2.27%   |
| es_AR   | 2        | 2.27%   |
| en_NZ   | 2        | 2.27%   |
| de_DE   | 2        | 2.27%   |
| sl_SI   | 1        | 1.14%   |
| pt_BR   | 1        | 1.14%   |
| ko_KR   | 1        | 1.14%   |
| ja_JP   | 1        | 1.14%   |
| es_MX   | 1        | 1.14%   |
| en_CA   | 1        | 1.14%   |
| cs_CZ   | 1        | 1.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 54       | 61.36%  |
| BIOS | 34       | 38.64%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Xfs     | 80       | 90.91%  |
| Ext4    | 5        | 5.68%   |
| Unknown | 3        | 3.41%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 47       | 52.22%  |
| GPT     | 30       | 33.33%  |
| MBR     | 13       | 14.44%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 68       | 77.27%  |
| Yes       | 20       | 22.73%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 77       | 87.5%   |
| Yes       | 11       | 12.5%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Dell                | 18       | 20.69%  |
| ASUSTek Computer    | 15       | 17.24%  |
| Hewlett-Packard     | 12       | 13.79%  |
| Gigabyte Technology | 12       | 13.79%  |
| MSI                 | 8        | 9.2%    |
| ASRock              | 7        | 8.05%   |
| Lenovo              | 4        | 4.6%    |
| Unknown             | 4        | 4.6%    |
| Intel               | 2        | 2.3%    |
| Supermicro          | 1        | 1.15%   |
| Hardkernel          | 1        | 1.15%   |
| CX / Air Computers. | 1        | 1.15%   |
| Alienware           | 1        | 1.15%   |
| Acer                | 1        | 1.15%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| Dell PowerEdge FC630                | 6        | 6.9%    |
| ASUS All Series                     | 4        | 4.6%    |
| Unknown                             | 4        | 4.6%    |
| HP Z620 Workstation                 | 2        | 2.3%    |
| Dell Precision Tower 5810           | 2        | 2.3%    |
| Dell OptiPlex 9020                  | 2        | 2.3%    |
| Supermicro X7DW3                    | 1        | 1.15%   |
| MSI MS-7D54                         | 1        | 1.15%   |
| MSI MS-7C95                         | 1        | 1.15%   |
| MSI MS-7B89                         | 1        | 1.15%   |
| MSI MS-7B51                         | 1        | 1.15%   |
| MSI MS-7B33                         | 1        | 1.15%   |
| MSI MS-7A71                         | 1        | 1.15%   |
| MSI MS-7A37                         | 1        | 1.15%   |
| MSI MS-7752                         | 1        | 1.15%   |
| Lenovo ThinkCentre M92p 3238AZ8     | 1        | 1.15%   |
| Lenovo ThinkCentre M920t 10SFS03200 | 1        | 1.15%   |
| Lenovo ThinkCentre M91p 0266RZ1     | 1        | 1.15%   |
| Lenovo 10SFS03200                   | 1        | 1.15%   |
| Intel H81                           | 1        | 1.15%   |
| Intel DX79SR AAG57199-200           | 1        | 1.15%   |
| HP Z840 Workstation                 | 1        | 1.15%   |
| HP Z800 Workstation                 | 1        | 1.15%   |
| HP Z440 Workstation                 | 1        | 1.15%   |
| HP Z230 Tower Workstation           | 1        | 1.15%   |
| HP Z230 SFF Workstation             | 1        | 1.15%   |
| HP Z1 Entry Tower G5                | 1        | 1.15%   |
| HP ProLiant MicroServer Gen8        | 1        | 1.15%   |
| HP EliteDesk 800 G2 SFF             | 1        | 1.15%   |
| HP 290 G1 SFF Business PC           | 1        | 1.15%   |
| HP 260-P020il                       | 1        | 1.15%   |
| Hardkernel ODROID-H3                | 1        | 1.15%   |
| Gigabyte Z97N-WIFI                  | 1        | 1.15%   |
| Gigabyte Z590I VISION D             | 1        | 1.15%   |
| Gigabyte Z490 GAMING X              | 1        | 1.15%   |
| Gigabyte Z390 AORUS ULTRA           | 1        | 1.15%   |
| Gigabyte X670E AORUS MASTER         | 1        | 1.15%   |
| Gigabyte X570 UD                    | 1        | 1.15%   |
| Gigabyte H510M H                    | 1        | 1.15%   |
| Gigabyte B85M-D3V-A                 | 1        | 1.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| Dell PowerEdge       | 7        | 8.05%   |
| Dell Precision       | 6        | 6.9%    |
| ASUS PRIME           | 5        | 5.75%   |
| ASUS All             | 4        | 4.6%    |
| Unknown              | 4        | 4.6%    |
| Lenovo ThinkCentre   | 3        | 3.45%   |
| Dell OptiPlex        | 3        | 3.45%   |
| HP Z620              | 2        | 2.3%    |
| HP Z230              | 2        | 2.3%    |
| ASUS ROG             | 2        | 2.3%    |
| Supermicro X7DW3     | 1        | 1.15%   |
| MSI MS-7D54          | 1        | 1.15%   |
| MSI MS-7C95          | 1        | 1.15%   |
| MSI MS-7B89          | 1        | 1.15%   |
| MSI MS-7B51          | 1        | 1.15%   |
| MSI MS-7B33          | 1        | 1.15%   |
| MSI MS-7A71          | 1        | 1.15%   |
| MSI MS-7A37          | 1        | 1.15%   |
| MSI MS-7752          | 1        | 1.15%   |
| Lenovo 10SFS03200    | 1        | 1.15%   |
| Intel H81            | 1        | 1.15%   |
| Intel DX79SR         | 1        | 1.15%   |
| HP Z840              | 1        | 1.15%   |
| HP Z800              | 1        | 1.15%   |
| HP Z440              | 1        | 1.15%   |
| HP Z1                | 1        | 1.15%   |
| HP ProLiant          | 1        | 1.15%   |
| HP EliteDesk         | 1        | 1.15%   |
| HP 290               | 1        | 1.15%   |
| HP 260-P020il        | 1        | 1.15%   |
| Hardkernel ODROID-H3 | 1        | 1.15%   |
| Gigabyte Z97N-WIFI   | 1        | 1.15%   |
| Gigabyte Z590I       | 1        | 1.15%   |
| Gigabyte Z490        | 1        | 1.15%   |
| Gigabyte Z390        | 1        | 1.15%   |
| Gigabyte X670E       | 1        | 1.15%   |
| Gigabyte X570        | 1        | 1.15%   |
| Gigabyte H510M       | 1        | 1.15%   |
| Gigabyte B85M-D3V-A  | 1        | 1.15%   |
| Gigabyte B75-D3V     | 1        | 1.15%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2016 | 14       | 16.09%  |
| 2018 | 12       | 13.79%  |
| 2019 | 10       | 11.49%  |
| 2017 | 9        | 10.34%  |
| 2012 | 8        | 9.2%    |
| 2021 | 6        | 6.9%    |
| 2015 | 6        | 6.9%    |
| 2013 | 6        | 6.9%    |
| 2020 | 5        | 5.75%   |
| 2022 | 3        | 3.45%   |
| 2014 | 2        | 2.3%    |
| 2010 | 2        | 2.3%    |
| 2009 | 2        | 2.3%    |
| 2023 | 1        | 1.15%   |
| 2011 | 1        | 1.15%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 87       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 82       | 93.18%  |
| Enabled  | 6        | 6.82%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 87       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 64.01-256.0     | 21       | 23.33%  |
| 32.01-64.0      | 18       | 20%     |
| 8.01-16.0       | 15       | 16.67%  |
| 4.01-8.0        | 12       | 13.33%  |
| 16.01-24.0      | 12       | 13.33%  |
| 24.01-32.0      | 8        | 8.89%   |
| More than 256.0 | 2        | 2.22%   |
| 3.01-4.0        | 1        | 1.11%   |
| 2.01-3.0        | 1        | 1.11%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 28       | 28.28%  |
| 4.01-8.0   | 27       | 27.27%  |
| 3.01-4.0   | 16       | 16.16%  |
| 8.01-16.0  | 14       | 14.14%  |
| 1.01-2.0   | 9        | 9.09%   |
| 16.01-24.0 | 3        | 3.03%   |
| 24.01-32.0 | 1        | 1.01%   |
| 0.51-1.0   | 1        | 1.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 30       | 32.26%  |
| 1      | 22       | 23.66%  |
| 3      | 14       | 15.05%  |
| 5      | 10       | 10.75%  |
| 4      | 8        | 8.6%    |
| 12     | 3        | 3.23%   |
| 8      | 2        | 2.15%   |
| 6      | 2        | 2.15%   |
| 14     | 1        | 1.08%   |
| 10     | 1        | 1.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 51       | 57.95%  |
| Yes       | 37       | 42.05%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 87       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 46       | 52.87%  |
| Yes       | 41       | 47.13%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 54       | 62.07%  |
| Yes       | 33       | 37.93%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 19       | 21.84%  |
| Germany      | 10       | 11.49%  |
| UK           | 7        | 8.05%   |
| India        | 6        | 6.9%    |
| Canada       | 6        | 6.9%    |
| Czechia      | 5        | 5.75%   |
| Russia       | 3        | 3.45%   |
| Ukraine      | 2        | 2.3%    |
| Spain        | 2        | 2.3%    |
| South Korea  | 2        | 2.3%    |
| Poland       | 2        | 2.3%    |
| New Zealand  | 2        | 2.3%    |
| Italy        | 2        | 2.3%    |
| Brazil       | 2        | 2.3%    |
| Argentina    | 2        | 2.3%    |
| Turkmenistan | 1        | 1.15%   |
| Switzerland  | 1        | 1.15%   |
| Sweden       | 1        | 1.15%   |
| Slovenia     | 1        | 1.15%   |
| Netherlands  | 1        | 1.15%   |
| Mexico       | 1        | 1.15%   |
| Lithuania    | 1        | 1.15%   |
| Japan        | 1        | 1.15%   |
| Indonesia    | 1        | 1.15%   |
| Finland      | 1        | 1.15%   |
| Egypt        | 1        | 1.15%   |
| China        | 1        | 1.15%   |
| Belgium      | 1        | 1.15%   |
| Belarus      | 1        | 1.15%   |
| Austria      | 1        | 1.15%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Petersberg            | 6        | 6.67%   |
| Prague                | 4        | 4.44%   |
| Kyiv                  | 2        | 2.22%   |
| Chicago               | 2        | 2.22%   |
| Bengaluru             | 2        | 2.22%   |
| Yorktown Heights      | 1        | 1.11%   |
| Yongin-si             | 1        | 1.11%   |
| Wildomar              | 1        | 1.11%   |
| Wiesbaden             | 1        | 1.11%   |
| Wellington            | 1        | 1.11%   |
| Vienna                | 1        | 1.11%   |
| Valencia              | 1        | 1.11%   |
| Vaglio                | 1        | 1.11%   |
| Turku                 | 1        | 1.11%   |
| Toronto               | 1        | 1.11%   |
| Tokyo                 | 1        | 1.11%   |
| Tiruchi               | 1        | 1.11%   |
| Tauranga              | 1        | 1.11%   |
| Sutton                | 1        | 1.11%   |
| Stavropol             | 1        | 1.11%   |
| Spokane               | 1        | 1.11%   |
| Šiauliai             | 1        | 1.11%   |
| Saratov               | 1        | 1.11%   |
| San Jose              | 1        | 1.11%   |
| San Fernando          | 1        | 1.11%   |
| Salvador              | 1        | 1.11%   |
| Saltillo              | 1        | 1.11%   |
| Sainte-Marie          | 1        | 1.11%   |
| Rosario               | 1        | 1.11%   |
| Ribeirao Preto        | 1        | 1.11%   |
| Rensselaer            | 1        | 1.11%   |
| Reading               | 1        | 1.11%   |
| Pforzheim             | 1        | 1.11%   |
| Pernis                | 1        | 1.11%   |
| Paracuellos de Jarama | 1        | 1.11%   |
| Oldham                | 1        | 1.11%   |
| Musselburgh           | 1        | 1.11%   |
| Montreal              | 1        | 1.11%   |
| Mississauga           | 1        | 1.11%   |
| Minsk                 | 1        | 1.11%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 32       | 62     | 17.39%  |
| Seagate                   | 32       | 65     | 17.39%  |
| Samsung Electronics       | 22       | 49     | 11.96%  |
| Toshiba                   | 11       | 16     | 5.98%   |
| Kingston                  | 10       | 14     | 5.43%   |
| SanDisk                   | 7        | 13     | 3.8%    |
| Crucial                   | 7        | 12     | 3.8%    |
| Phison                    | 5        | 9      | 2.72%   |
| SK hynix                  | 4        | 6      | 2.17%   |
| Intel                     | 4        | 6      | 2.17%   |
| Hitachi                   | 4        | 4      | 2.17%   |
| Dell                      | 4        | 8      | 2.17%   |
| A-DATA Technology         | 4        | 4      | 2.17%   |
| Unknown                   | 3        | 5      | 1.63%   |
| PNY                       | 3        | 3      | 1.63%   |
| Micron Technology         | 3        | 3      | 1.63%   |
| Gigabyte Technology       | 3        | 4      | 1.63%   |
| China                     | 3        | 3      | 1.63%   |
| Micron/Crucial Technology | 2        | 3      | 1.09%   |
| HGST                      | 2        | 2      | 1.09%   |
| Corsair                   | 2        | 5      | 1.09%   |
| XUM                       | 1        | 1      | 0.54%   |
| XPG                       | 1        | 1      | 0.54%   |
| Western Digital           | 1        | 1      | 0.54%   |
| T-FORCE                   | 1        | 2      | 0.54%   |
| Silicon Motion            | 1        | 1      | 0.54%   |
| SCST_FIO                  | 1        | 9      | 0.54%   |
| SABRENT                   | 1        | 1      | 0.54%   |
| OCZ                       | 1        | 2      | 0.54%   |
| KingSpec                  | 1        | 1      | 0.54%   |
| KingFast                  | 1        | 1      | 0.54%   |
| KINGBANK                  | 1        | 1      | 0.54%   |
| HPT                       | 1        | 1      | 0.54%   |
| Hoodisk                   | 1        | 1      | 0.54%   |
| Hewlett-Packard           | 1        | 1      | 0.54%   |
| Fantom                    | 1        | 1      | 0.54%   |
| Anobit                    | 1        | 1      | 0.54%   |
| ADATA Technology          | 1        | 1      | 0.54%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Samsung SSD 860 EVO 1TB              | 4        | 1.73%   |
| Dell MD34xx 26TB                     | 4        | 1.73%   |
| WDC WD40EFRX-68N32N0 4TB             | 2        | 0.87%   |
| WDC WD1003FZEX-00MK2A0 1TB           | 2        | 0.87%   |
| WDC WD1002FAEX-00Z3A0 1TB            | 2        | 0.87%   |
| Unknown SD/MMC/MS PRO 128GB          | 2        | 0.87%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD  | 2        | 0.87%   |
| Toshiba DT01ACA200 2TB               | 2        | 0.87%   |
| Toshiba AL14SEB18EQ 1.8TB            | 2        | 0.87%   |
| Seagate ST91000640NS 1TB             | 2        | 0.87%   |
| Seagate ST500DM002-1BD142 500GB      | 2        | 0.87%   |
| Seagate ST2000NX0433 2TB             | 2        | 0.87%   |
| Seagate ST2000NX0273 2TB             | 2        | 0.87%   |
| Seagate ST2000DM001-1ER164 2TB       | 2        | 0.87%   |
| Seagate ST1000DM010-2EP102 1TB       | 2        | 0.87%   |
| Seagate ST1000DM003-9YN162 1TB       | 2        | 0.87%   |
| Samsung SSD 860 EVO 500GB            | 2        | 0.87%   |
| Samsung SSD 850 EVO 250GB            | 2        | 0.87%   |
| Samsung NVMe SSD Drive 512GB         | 2        | 0.87%   |
| Samsung NVMe SSD Drive 500GB         | 2        | 0.87%   |
| Kingston SUV500120G 120GB SSD        | 2        | 0.87%   |
| Kingston SA400S37240G 240GB SSD      | 2        | 0.87%   |
| Crucial CT240BX500SSD1 240GB         | 2        | 0.87%   |
| Corsair Force LE SSD 240GB           | 2        | 0.87%   |
| XUM HX256GSSDSATA3 256GB             | 1        | 0.43%   |
| XPG NVMe SSD Drive 1024GB            | 1        | 0.43%   |
| Western Digital NVMe SSD Drive 960GB | 1        | 0.43%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 1        | 0.43%   |
| WDC WDS250G2B0B-00YS70 250GB SSD     | 1        | 0.43%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1        | 0.43%   |
| WDC WDS240G1G0A-00SS50 240GB SSD     | 1        | 0.43%   |
| WDC WDS100T2B0A-00SM50 1TB SSD       | 1        | 0.43%   |
| WDC WDBA3V5000ANC-WRSN 500GB         | 1        | 0.43%   |
| WDC WD80EFAX-68KNBN0 8TB             | 1        | 0.43%   |
| WDC WD7500BPKT-00PK4T0 752GB         | 1        | 0.43%   |
| WDC WD60 EFAX-68JH4N1 6TB            | 1        | 0.43%   |
| WDC WD60 EFAX-68JH4N0 6TB            | 1        | 0.43%   |
| WDC WD5003ABYZ-011FA0 500GB          | 1        | 0.43%   |
| WDC WD5000HHTZ-04N21V0 500GB         | 1        | 0.43%   |
| WDC WD5000AVDS-63U7B0 500GB          | 1        | 0.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 32       | 65     | 37.21%  |
| WDC                 | 29       | 56     | 33.72%  |
| Toshiba             | 9        | 13     | 10.47%  |
| Hitachi             | 4        | 4      | 4.65%   |
| Dell                | 4        | 8      | 4.65%   |
| Unknown             | 2        | 2      | 2.33%   |
| HGST                | 2        | 2      | 2.33%   |
| SCST_FIO            | 1        | 9      | 1.16%   |
| Samsung Electronics | 1        | 2      | 1.16%   |
| Hewlett-Packard     | 1        | 1      | 1.16%   |
| Fantom              | 1        | 1      | 1.16%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 15       | 31     | 23.08%  |
| Kingston            | 10       | 14     | 15.38%  |
| Crucial             | 7        | 11     | 10.77%  |
| WDC                 | 4        | 5      | 6.15%   |
| SanDisk             | 4        | 9      | 6.15%   |
| PNY                 | 3        | 3      | 4.62%   |
| Micron Technology   | 3        | 3      | 4.62%   |
| China               | 3        | 3      | 4.62%   |
| A-DATA Technology   | 3        | 3      | 4.62%   |
| SK hynix            | 2        | 4      | 3.08%   |
| Intel               | 2        | 3      | 3.08%   |
| Corsair             | 2        | 5      | 3.08%   |
| XUM                 | 1        | 1      | 1.54%   |
| OCZ                 | 1        | 2      | 1.54%   |
| KingSpec            | 1        | 1      | 1.54%   |
| KINGBANK            | 1        | 1      | 1.54%   |
| Hoodisk             | 1        | 1      | 1.54%   |
| Gigabyte Technology | 1        | 1      | 1.54%   |
| Anobit              | 1        | 1      | 1.54%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 61       | 163    | 40.4%   |
| SSD     | 57       | 102    | 37.75%  |
| NVMe    | 29       | 51     | 19.21%  |
| Unknown | 4        | 7      | 2.65%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 81       | 247    | 65.85%  |
| NVMe | 29       | 50     | 23.58%  |
| SAS  | 13       | 26     | 10.57%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 56       | 107    | 40.88%  |
| 0.51-1.0   | 38       | 65     | 27.74%  |
| 1.01-2.0   | 21       | 46     | 15.33%  |
| 3.01-4.0   | 9        | 17     | 6.57%   |
| 4.01-10.0  | 5        | 15     | 3.65%   |
| 20.01-50.0 | 4        | 8      | 2.92%   |
| 2.01-3.0   | 2        | 3      | 1.46%   |
| 10.01-20.0 | 2        | 4      | 1.46%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 20       | 21.51%  |
| 251-500        | 17       | 18.28%  |
| 501-1000       | 17       | 18.28%  |
| More than 3000 | 12       | 12.9%   |
| 1001-2000      | 10       | 10.75%  |
| Unknown        | 9        | 9.68%   |
| 2001-3000      | 5        | 5.38%   |
| 51-100         | 3        | 3.23%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 21-50          | 21       | 21.21%  |
| 1-20           | 21       | 21.21%  |
| 101-250        | 14       | 14.14%  |
| 51-100         | 11       | 11.11%  |
| Unknown        | 9        | 9.09%   |
| 251-500        | 8        | 8.08%   |
| 1001-2000      | 5        | 5.05%   |
| More than 3000 | 4        | 4.04%   |
| 501-1000       | 4        | 4.04%   |
| 2001-3000      | 2        | 2.02%   |

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
| Detected | 50       | 187    | 51.55%  |
| Works    | 39       | 125    | 40.21%  |
| Malfunc  | 8        | 11     | 8.25%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 70       | 50.36%  |
| AMD                          | 17       | 12.23%  |
| Samsung Electronics          | 12       | 8.63%   |
| Broadcom / LSI               | 9        | 6.47%   |
| Phison Electronics           | 6        | 4.32%   |
| ASMedia Technology           | 4        | 2.88%   |
| SanDisk                      | 3        | 2.16%   |
| Micron/Crucial Technology    | 3        | 2.16%   |
| Marvell Technology Group     | 3        | 2.16%   |
| ADATA Technology             | 3        | 2.16%   |
| Toshiba America Info Systems | 2        | 1.44%   |
| SK hynix                     | 2        | 1.44%   |
| LSI Logic / Symbios Logic    | 2        | 1.44%   |
| Western Digital              | 1        | 0.72%   |
| Silicon Motion               | 1        | 0.72%   |
| HighPoint Technologies       | 1        | 0.72%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 13       | 7.56%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 12       | 6.98%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 11       | 6.4%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 10       | 5.81%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 9        | 5.23%   |
| Intel SATA Controller [RAID mode]                                              | 6        | 3.49%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 6        | 3.49%   |
| Broadcom / LSI MegaRAID SAS-3 3108 [Invader]                                   | 6        | 3.49%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 5        | 2.91%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 5        | 2.91%   |
| Broadcom / LSI SAS3008 PCI-Express Fusion-MPT SAS-3                            | 5        | 2.91%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 4        | 2.33%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 4        | 2.33%   |
| Phison E12 NVMe Controller                                                     | 3        | 1.74%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 3        | 1.74%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 3        | 1.74%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 3        | 1.74%   |
| AMD 300 Series Chipset SATA Controller                                         | 3        | 1.74%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 2        | 1.16%   |
| SK hynix PC601 NVMe Solid State Drive                                          | 2        | 1.16%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 2        | 1.16%   |
| Phison PS5013 E13 NVMe Controller                                              | 2        | 1.16%   |
| Phison E16 PCIe4 NVMe Controller                                               | 2        | 1.16%   |
| Intel SSD 660P Series                                                          | 2        | 1.16%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 2        | 1.16%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                            | 2        | 1.16%   |
| Intel C600/X79 series chipset SATA RAID Controller                             | 2        | 1.16%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 2        | 1.16%   |
| AMD 500 Series Chipset SATA Controller                                         | 2        | 1.16%   |
| AMD 400 Series Chipset SATA Controller                                         | 2        | 1.16%   |
| ADATA ADATA XPG GAMMIXS1 1L Media (256 GB SSD)                                 | 2        | 1.16%   |
| Western Digital Ultrastar DC SN640 NVMe SSD                                    | 1        | 0.58%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 1        | 0.58%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                             | 1        | 0.58%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1        | 0.58%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1        | 0.58%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1        | 0.58%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                           | 1        | 0.58%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 1        | 0.58%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton2]                                     | 1        | 0.58%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 77       | 55%     |
| NVMe | 30       | 21.43%  |
| RAID | 18       | 12.86%  |
| SAS  | 10       | 7.14%   |
| IDE  | 5        | 3.57%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 70       | 80.46%  |
| AMD    | 17       | 19.54%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| AMD Ryzen 9 3900X 12-Core Processor     | 5        | 5.75%   |
| Intel Core i7-8700 CPU @ 3.20GHz        | 4        | 4.6%    |
| Intel Xeon CPU E5-2680 v3 @ 2.50GHz     | 2        | 2.3%    |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz     | 2        | 2.3%    |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz     | 2        | 2.3%    |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz     | 2        | 2.3%    |
| Intel Pentium Gold G5400 CPU @ 3.70GHz  | 2        | 2.3%    |
| Intel Core i7-8700K CPU @ 3.70GHz       | 2        | 2.3%    |
| Intel Core i7-7700 CPU @ 3.60GHz        | 2        | 2.3%    |
| Intel Core i3-4130 CPU @ 3.40GHz        | 2        | 2.3%    |
| Intel 11th Gen Core i7-11700K @ 3.60GHz | 2        | 2.3%    |
| AMD Ryzen 5 3600 6-Core Processor       | 2        | 2.3%    |
| Intel Xeon CPU X5570 @ 2.93GHz          | 1        | 1.15%   |
| Intel Xeon CPU E5472 @ 3.00GHz          | 1        | 1.15%   |
| Intel Xeon CPU E5-2696 v3 @ 2.30GHz     | 1        | 1.15%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz      | 1        | 1.15%   |
| Intel Xeon CPU E5-2680 v2 @ 2.80GHz     | 1        | 1.15%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz     | 1        | 1.15%   |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz      | 1        | 1.15%   |
| Intel Xeon CPU E5-1650 v4 @ 3.60GHz     | 1        | 1.15%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz     | 1        | 1.15%   |
| Intel Xeon CPU E5-1607 v4 @ 3.10GHz     | 1        | 1.15%   |
| Intel Xeon CPU E3-1280 V2 @ 3.60GHz     | 1        | 1.15%   |
| Intel Xeon CPU E3-1270 v5 @ 3.60GHz     | 1        | 1.15%   |
| Intel Xeon CPU E3-1240 v3 @ 3.40GHz     | 1        | 1.15%   |
| Intel Xeon CPU E3-1225 v5 @ 3.30GHz     | 1        | 1.15%   |
| Intel Pentium Silver N6005 @ 2.00GHz    | 1        | 1.15%   |
| Intel Core i9-9900 CPU @ 3.10GHz        | 1        | 1.15%   |
| Intel Core i7-9700F CPU @ 3.00GHz       | 1        | 1.15%   |
| Intel Core i7-7700K CPU @ 4.20GHz       | 1        | 1.15%   |
| Intel Core i7-7560U CPU @ 2.40GHz       | 1        | 1.15%   |
| Intel Core i7-4790K CPU @ 4.00GHz       | 1        | 1.15%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 1        | 1.15%   |
| Intel Core i7-4770K CPU @ 3.50GHz       | 1        | 1.15%   |
| Intel Core i7-3820 CPU @ 3.60GHz        | 1        | 1.15%   |
| Intel Core i7-3770K CPU @ 3.50GHz       | 1        | 1.15%   |
| Intel Core i7 CPU X 990 @ 3.47GHz       | 1        | 1.15%   |
| Intel Core i5-9600K CPU @ 3.70GHz       | 1        | 1.15%   |
| Intel Core i5-7500 CPU @ 3.40GHz        | 1        | 1.15%   |
| Intel Core i5-6500 CPU @ 3.20GHz        | 1        | 1.15%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Desktops | Percent |
|----------------------|----------|---------|
| Intel Xeon           | 22       | 25.29%  |
| Intel Core i7        | 17       | 19.54%  |
| Intel Core i5        | 14       | 16.09%  |
| Intel Core i3        | 7        | 8.05%   |
| AMD Ryzen 9          | 7        | 8.05%   |
| Other                | 4        | 4.6%    |
| AMD Ryzen 5          | 4        | 4.6%    |
| Intel Pentium Gold   | 2        | 2.3%    |
| AMD Ryzen 7          | 2        | 2.3%    |
| Intel Pentium Silver | 1        | 1.15%   |
| Intel Core i9        | 1        | 1.15%   |
| Intel Core 2 Duo     | 1        | 1.15%   |
| Intel Celeron        | 1        | 1.15%   |
| AMD Ryzen 3          | 1        | 1.15%   |
| AMD FX               | 1        | 1.15%   |
| AMD Athlon X4        | 1        | 1.15%   |
| AMD A4               | 1        | 1.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 31       | 35.63%  |
| 6      | 13       | 14.94%  |
| 2      | 13       | 14.94%  |
| 12     | 11       | 12.64%  |
| 8      | 11       | 12.64%  |
| 16     | 4        | 4.6%    |
| 36     | 1        | 1.15%   |
| 24     | 1        | 1.15%   |
| 20     | 1        | 1.15%   |
| 14     | 1        | 1.15%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 76       | 87.36%  |
| 2      | 11       | 12.64%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 63       | 71.59%  |
| 1      | 25       | 28.41%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 85       | 97.7%   |
| Unknown        | 2        | 2.3%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 12       | 13.79%  |
| 0x906ea    | 8        | 9.2%    |
| 0x306f2    | 8        | 9.2%    |
| 0x306a9    | 7        | 8.05%   |
| 0x08701021 | 5        | 5.75%   |
| 0x906e9    | 4        | 4.6%    |
| 0x506e3    | 4        | 4.6%    |
| 0x406f1    | 4        | 4.6%    |
| 0xa0671    | 3        | 3.45%   |
| 0x906ed    | 3        | 3.45%   |
| 0x206d7    | 3        | 3.45%   |
| 0x906c0    | 2        | 2.3%    |
| 0x08701013 | 2        | 2.3%    |
| Unknown    | 2        | 2.3%    |
| 0xb0671    | 1        | 1.15%   |
| 0xa0655    | 1        | 1.15%   |
| 0x906eb    | 1        | 1.15%   |
| 0x806e9    | 1        | 1.15%   |
| 0x306e4    | 1        | 1.15%   |
| 0x206c2    | 1        | 1.15%   |
| 0x206a7    | 1        | 1.15%   |
| 0x106a5    | 1        | 1.15%   |
| 0x1067a    | 1        | 1.15%   |
| 0x10676    | 1        | 1.15%   |
| 0x0a601203 | 1        | 1.15%   |
| 0x0a50000c | 1        | 1.15%   |
| 0x0a20120a | 1        | 1.15%   |
| 0x08108102 | 1        | 1.15%   |
| 0x0810100b | 1        | 1.15%   |
| 0x08001138 | 1        | 1.15%   |
| 0x08001137 | 1        | 1.15%   |
| 0x06006705 | 1        | 1.15%   |
| 0x0600611a | 1        | 1.15%   |
| 0x06000852 | 1        | 1.15%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 21       | 24.14%  |
| KabyLake         | 17       | 19.54%  |
| IvyBridge        | 9        | 10.34%  |
| Zen 2            | 7        | 8.05%   |
| Skylake          | 4        | 4.6%    |
| SandyBridge      | 4        | 4.6%    |
| Broadwell        | 4        | 4.6%    |
| Zen              | 3        | 3.45%   |
| Icelake          | 3        | 3.45%   |
| Zen 3            | 2        | 2.3%    |
| Tremont          | 2        | 2.3%    |
| Penryn           | 2        | 2.3%    |
| Excavator        | 2        | 2.3%    |
| Zen+             | 1        | 1.15%   |
| Westmere         | 1        | 1.15%   |
| Piledriver       | 1        | 1.15%   |
| Nehalem          | 1        | 1.15%   |
| CometLake        | 1        | 1.15%   |
| Alderlake Hybrid | 1        | 1.15%   |
| Unknown          | 1        | 1.15%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 45       | 44.55%  |
| Intel                      | 32       | 31.68%  |
| AMD                        | 18       | 17.82%  |
| Matrox Electronics Systems | 6        | 5.94%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Matrox Electronics Systems G200eR2                                          | 6        | 5.71%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 6        | 5.71%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 4        | 3.81%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 2.86%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 3        | 2.86%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3        | 2.86%   |
| Intel HD Graphics 630                                                       | 3        | 2.86%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3        | 2.86%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 3        | 2.86%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 2        | 1.9%    |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 2        | 1.9%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 1.9%    |
| Nvidia GK208B [GeForce GT 730]                                              | 2        | 1.9%    |
| Nvidia GF108GL [Quadro 600]                                                 | 2        | 1.9%    |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 2        | 1.9%    |
| Intel JasperLake [UHD Graphics]                                             | 2        | 1.9%    |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2        | 1.9%    |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]       | 2        | 1.9%    |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 2        | 1.9%    |
| Nvidia TU117GL [T400 4GB]                                                   | 1        | 0.95%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 0.95%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 0.95%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 1        | 0.95%   |
| Nvidia GT218 [GeForce G210]                                                 | 1        | 0.95%   |
| Nvidia GP107GL [Quadro P600]                                                | 1        | 0.95%   |
| Nvidia GP107GL [Quadro P400]                                                | 1        | 0.95%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 0.95%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 0.95%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1        | 0.95%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 0.95%   |
| Nvidia GM206GL [Quadro M2000]                                               | 1        | 0.95%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 0.95%   |
| Nvidia GM204GL [Quadro M4000]                                               | 1        | 0.95%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1        | 0.95%   |
| Nvidia GM107GL [Quadro K620]                                                | 1        | 0.95%   |
| Nvidia GM107GL [NVS 810]                                                    | 1        | 0.95%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 0.95%   |
| Nvidia GK106GL [Quadro K4000]                                               | 1        | 0.95%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 1        | 0.95%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 1        | 0.95%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 39       | 43.82%  |
| 1 x Intel      | 20       | 22.47%  |
| 1 x AMD        | 13       | 14.61%  |
| 1 x Matrox     | 6        | 6.74%   |
| Intel + Nvidia | 4        | 4.49%   |
| Intel + AMD    | 3        | 3.37%   |
| 2 x Nvidia     | 2        | 2.25%   |
| 2 x AMD        | 2        | 2.25%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 61       | 69.32%  |
| Proprietary | 20       | 22.73%  |
| Unknown     | 7        | 7.95%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 35       | 38.04%  |
| 7.01-8.0   | 15       | 16.3%   |
| 1.01-2.0   | 15       | 16.3%   |
| 3.01-4.0   | 7        | 7.61%   |
| 0.51-1.0   | 7        | 7.61%   |
| 0.01-0.5   | 5        | 5.43%   |
| 5.01-6.0   | 3        | 3.26%   |
| 2.01-3.0   | 3        | 3.26%   |
| 8.01-16.0  | 2        | 2.17%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 18       | 19.78%  |
| Samsung Electronics  | 15       | 16.48%  |
| Goldstar             | 10       | 10.99%  |
| Lenovo               | 6        | 6.59%   |
| Hewlett-Packard      | 6        | 6.59%   |
| BenQ                 | 4        | 4.4%    |
| Acer                 | 4        | 4.4%    |
| Philips              | 3        | 3.3%    |
| Ancor Communications | 3        | 3.3%    |
| ViewSonic            | 2        | 2.2%    |
| Lenovo Group Limited | 2        | 2.2%    |
| Iiyama               | 2        | 2.2%    |
| Gigabyte Technology  | 2        | 2.2%    |
| Eizo                 | 2        | 2.2%    |
| Vizio                | 1        | 1.1%    |
| STD                  | 1        | 1.1%    |
| Sony                 | 1        | 1.1%    |
| Panasonic            | 1        | 1.1%    |
| OUT                  | 1        | 1.1%    |
| Microstep            | 1        | 1.1%    |
| LG Electronics       | 1        | 1.1%    |
| Insignia             | 1        | 1.1%    |
| Haier                | 1        | 1.1%    |
| Deco Gear            | 1        | 1.1%    |
| AOC                  | 1        | 1.1%    |
| Unknown              | 1        | 1.1%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Dell LCD Monitor DEL0001 1280x1024                                     | 6        | 5.88%   |
| Lenovo TIO24Gen3 LEN10B4 1920x1080 527x296mm 23.8-inch                 | 2        | 1.96%   |
| Lenovo LEN T2324pA LEN60C7 1920x1080 509x286mm 23.0-inch               | 2        | 1.96%   |
| Lenovo LEN P27u-10 LEN61B0 3840x2160 597x336mm 27.0-inch               | 2        | 1.96%   |
| Iiyama PL4840 IVM1065 1920x1080 1054x593mm 47.6-inch                   | 2        | 1.96%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 2        | 1.96%   |
| Acer ED322QR ACR06DD 1920x1080 700x390mm 31.5-inch                     | 2        | 1.96%   |
| Vizio E500i-A1 VIZ1004 1920x1080 1095x616mm 49.5-inch                  | 1        | 0.98%   |
| ViewSonic VX2776 Series VSC3E32 1920x1080 598x336mm 27.0-inch          | 1        | 0.98%   |
| ViewSonic VA2259 Series VSC5E32 1920x1080 476x268mm 21.5-inch          | 1        | 0.98%   |
| STD LED STD0110 1920x1080 480x260mm 21.5-inch                          | 1        | 0.98%   |
| Sony TV SNYD703 1360x768                                               | 1        | 0.98%   |
| Samsung Electronics SyncMaster SAM05FC 1920x1080                       | 1        | 0.98%   |
| Samsung Electronics SyncMaster SAM0566 1440x900 408x255mm 18.9-inch    | 1        | 0.98%   |
| Samsung Electronics SyncMaster SAM0526 1920x1080 510x287mm 23.0-inch   | 1        | 0.98%   |
| Samsung Electronics SyncMaster SAM0370 1680x1050 459x296mm 21.5-inch   | 1        | 0.98%   |
| Samsung Electronics SyncMaster SAM020D 1280x1024 338x270mm 17.0-inch   | 1        | 0.98%   |
| Samsung Electronics SMS23A550H SAM07CA 1920x1080 509x286mm 23.0-inch   | 1        | 0.98%   |
| Samsung Electronics S27C500 SAM0AF2 1920x1080 598x336mm 27.0-inch      | 1        | 0.98%   |
| Samsung Electronics S22E390 SAM0C18 1920x1080 477x268mm 21.5-inch      | 1        | 0.98%   |
| Samsung Electronics S22B300 SAM08A9 1600x900 443x249mm 20.0-inch       | 1        | 0.98%   |
| Samsung Electronics LCD Monitor SAM7106 1920x1080 1210x680mm 54.6-inch | 1        | 0.98%   |
| Samsung Electronics LCD Monitor SAM0C04 3840x2160 1420x800mm 64.2-inch | 1        | 0.98%   |
| Samsung Electronics LCD Monitor SAM0B30 1920x1080 885x498mm 40.0-inch  | 1        | 0.98%   |
| Samsung Electronics LCD Monitor SAM0200 1280x720                       | 1        | 0.98%   |
| Samsung Electronics LCD Monitor S22B150                                | 1        | 0.98%   |
| Samsung Electronics LCD Monitor C49HG9x 3840x1080                      | 1        | 0.98%   |
| Samsung Electronics C32R50x SAM7000 1920x1080 698x393mm 31.5-inch      | 1        | 0.98%   |
| Samsung Electronics C32HG7x SAM0E14 2560x1440 697x392mm 31.5-inch      | 1        | 0.98%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 1        | 0.98%   |
| Philips PHL 322E1 PHLC20F 1920x1080 698x393mm 31.5-inch                | 1        | 0.98%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch                | 1        | 0.98%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 1        | 0.98%   |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                     | 1        | 0.98%   |
| OUT Analog OUT0096 1280x800 341x256mm 16.8-inch                        | 1        | 0.98%   |
| Microstep LCD Monitor MSI AG32CV 1920x1080                             | 1        | 0.98%   |
| LG Electronics LCD Monitor W2486 1920x1080                             | 1        | 0.98%   |
| Lenovo P27h-20 LEN61E9 2560x1440 600x340mm 27.2-inch                   | 1        | 0.98%   |
| Lenovo LEN L24q-30 LEN65FB 2560x1440 527x296mm 23.8-inch               | 1        | 0.98%   |
| Lenovo L24q-10 LEN65CF 2560x1440 527x296mm 23.8-inch                   | 1        | 0.98%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 41       | 45.56%  |
| 1280x1024 (SXGA)   | 8        | 8.89%   |
| 3840x2160 (4K)     | 7        | 7.78%   |
| 2560x1440 (QHD)    | 7        | 7.78%   |
| 3440x1440          | 4        | 4.44%   |
| 1600x900 (HD+)     | 4        | 4.44%   |
| 3840x1080          | 3        | 3.33%   |
| 2560x1080          | 3        | 3.33%   |
| Unknown            | 3        | 3.33%   |
| 1680x1050 (WSXGA+) | 2        | 2.22%   |
| 9600x2160          | 1        | 1.11%   |
| 7680x2160          | 1        | 1.11%   |
| 3840x1600          | 1        | 1.11%   |
| 3840x1200          | 1        | 1.11%   |
| 1920x1200 (WUXGA)  | 1        | 1.11%   |
| 1440x900 (WXGA+)   | 1        | 1.11%   |
| 1280x768           | 1        | 1.11%   |
| 1280x720 (HD)      | 1        | 1.11%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 17       | 18.48%  |
| 23      | 12       | 13.04%  |
| 21      | 11       | 11.96%  |
| 27      | 10       | 10.87%  |
| 24      | 8        | 8.7%    |
| 31      | 6        | 6.52%   |
| 20      | 4        | 4.35%   |
| 54      | 3        | 3.26%   |
| 34      | 3        | 3.26%   |
| 47      | 2        | 2.17%   |
| 84      | 1        | 1.09%   |
| 72      | 1        | 1.09%   |
| 64      | 1        | 1.09%   |
| 52      | 1        | 1.09%   |
| 49      | 1        | 1.09%   |
| 40      | 1        | 1.09%   |
| 39      | 1        | 1.09%   |
| 37      | 1        | 1.09%   |
| 35      | 1        | 1.09%   |
| 33      | 1        | 1.09%   |
| 28      | 1        | 1.09%   |
| 25      | 1        | 1.09%   |
| 19      | 1        | 1.09%   |
| 18      | 1        | 1.09%   |
| 17      | 1        | 1.09%   |
| 16      | 1        | 1.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 28       | 31.46%  |
| Unknown     | 17       | 19.1%   |
| 401-500     | 15       | 16.85%  |
| 601-700     | 8        | 8.99%   |
| 1001-1500   | 8        | 8.99%   |
| 801-900     | 4        | 4.49%   |
| 701-800     | 4        | 4.49%   |
| 301-350     | 2        | 2.25%   |
| 1501-2000   | 2        | 2.25%   |
| 351-400     | 1        | 1.12%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 53       | 65.43%  |
| Unknown | 9        | 11.11%  |
| 5/4     | 8        | 9.88%   |
| 21/9    | 6        | 7.41%   |
| 16/10   | 4        | 4.94%   |
| 4/3     | 1        | 1.23%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 26       | 28.89%  |
| Unknown        | 17       | 18.89%  |
| 351-500        | 11       | 12.22%  |
| 301-350        | 10       | 11.11%  |
| More than 1000 | 8        | 8.89%   |
| 151-200        | 7        | 7.78%   |
| 501-1000       | 5        | 5.56%   |
| 251-300        | 4        | 4.44%   |
| 141-150        | 1        | 1.11%   |
| 131-140        | 1        | 1.11%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 44       | 50%     |
| Unknown | 17       | 19.32%  |
| 101-120 | 16       | 18.18%  |
| 1-50    | 8        | 9.09%   |
| 161-240 | 2        | 2.27%   |
| 121-160 | 1        | 1.14%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 68       | 74.73%  |
| 2     | 10       | 10.99%  |
| 0     | 8        | 8.79%   |
| 3     | 5        | 5.49%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 54       | 42.52%  |
| Realtek Semiconductor    | 40       | 31.5%   |
| Broadcom                 | 10       | 7.87%   |
| Qualcomm Atheros         | 7        | 5.51%   |
| Ralink Technology        | 2        | 1.57%   |
| Dell                     | 2        | 1.57%   |
| ASIX Electronics         | 2        | 1.57%   |
| Ralink                   | 1        | 0.79%   |
| Microchip Technology     | 1        | 0.79%   |
| Micro Star International | 1        | 0.79%   |
| MediaTek                 | 1        | 0.79%   |
| Huawei Technologies      | 1        | 0.79%   |
| D-Link                   | 1        | 0.79%   |
| Broadcom Limited         | 1        | 0.79%   |
| ASUSTek Computer         | 1        | 0.79%   |
| Arduino SA               | 1        | 0.79%   |
| Aquantia                 | 1        | 0.79%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 29       | 17.47%  |
| Intel I211 Gigabit Network Connection                             | 7        | 4.22%   |
| Intel Ethernet Connection I217-LM                                 | 6        | 3.61%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6        | 3.61%   |
| Intel 82574L Gigabit Network Connection                           | 6        | 3.61%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5        | 3.01%   |
| Intel Ethernet Controller I225-V                                  | 4        | 2.41%   |
| Intel Ethernet Connection (7) I219-LM                             | 4        | 2.41%   |
| Intel Ethernet Connection (2) I219-V                              | 4        | 2.41%   |
| Intel Ethernet Connection (2) I219-LM                             | 4        | 2.41%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                | 4        | 2.41%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                  | 4        | 2.41%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 1.81%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 3        | 1.81%   |
| Intel Wi-Fi 6 AX200                                               | 3        | 1.81%   |
| Intel I350 Gigabit Network Connection                             | 3        | 1.81%   |
| Intel Ethernet Connection (2) I218-V                              | 3        | 1.81%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3        | 1.81%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3        | 1.81%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                | 3        | 1.81%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2        | 1.2%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 1.2%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2        | 1.2%    |
| Intel Wireless-AC 9260                                            | 2        | 1.2%    |
| Intel I210 Gigabit Network Connection                             | 2        | 1.2%    |
| Intel Ethernet Connection I217-V                                  | 2        | 1.2%    |
| Intel Ethernet Connection (7) I219-V                              | 2        | 1.2%    |
| Intel Ethernet Connection (2) I218-LM                             | 2        | 1.2%    |
| Intel 82599 10 Gigabit Dual Port Backplane Connection             | 2        | 1.2%    |
| Dell iDRAC Virtual NIC                                            | 2        | 1.2%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1        | 0.6%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 1        | 0.6%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1        | 0.6%    |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 1        | 0.6%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.6%    |
| Realtek 802.11n WLAN Adapter                                      | 1        | 0.6%    |
| Ralink RT5572 Wireless Adapter                                    | 1        | 0.6%    |
| Ralink RT5372 Wireless Adapter                                    | 1        | 0.6%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 1        | 0.6%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1        | 0.6%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 17       | 40.48%  |
| Realtek Semiconductor    | 7        | 16.67%  |
| Qualcomm Atheros         | 6        | 14.29%  |
| Broadcom                 | 5        | 11.9%   |
| Ralink Technology        | 2        | 4.76%   |
| Ralink                   | 1        | 2.38%   |
| Micro Star International | 1        | 2.38%   |
| MediaTek                 | 1        | 2.38%   |
| D-Link                   | 1        | 2.38%   |
| ASUSTek Computer         | 1        | 2.38%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 3        | 7.14%   |
| Intel Wi-Fi 6 AX200                                                  | 3        | 7.14%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 3        | 7.14%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 3        | 7.14%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                   | 3        | 7.14%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 2        | 4.76%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 2        | 4.76%   |
| Intel Wireless-AC 9260                                               | 2        | 4.76%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 1        | 2.38%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                           | 1        | 2.38%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                      | 1        | 2.38%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                      | 1        | 2.38%   |
| Realtek 802.11n WLAN Adapter                                         | 1        | 2.38%   |
| Ralink RT5572 Wireless Adapter                                       | 1        | 2.38%   |
| Ralink RT5372 Wireless Adapter                                       | 1        | 2.38%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                            | 1        | 2.38%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 1        | 2.38%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 1        | 2.38%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 1        | 2.38%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                     | 1        | 2.38%   |
| Micro Star International 802.11 n WLAN                               | 1        | 2.38%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                   | 1        | 2.38%   |
| Intel Wireless 7260                                                  | 1        | 2.38%   |
| Intel Wi-Fi 6 AX201 160MHz                                           | 1        | 2.38%   |
| Intel Alder Lake-S PCH CNVi WiFi                                     | 1        | 2.38%   |
| D-Link DWA-171 AC600 DB Wireless Adapter(rev.A1) [Realtek RTL8811AU] | 1        | 2.38%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                   | 1        | 2.38%   |
| Broadcom BCM4321 802.11b/g/n                                         | 1        | 2.38%   |
| ASUS WL-167G v3 802.11n Adapter [Realtek RTL8188SU]                  | 1        | 2.38%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 50       | 49.02%  |
| Realtek Semiconductor | 38       | 37.25%  |
| Broadcom              | 6        | 5.88%   |
| Qualcomm Atheros      | 2        | 1.96%   |
| Dell                  | 2        | 1.96%   |
| ASIX Electronics      | 2        | 1.96%   |
| Broadcom Limited      | 1        | 0.98%   |
| Aquantia              | 1        | 0.98%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 29       | 23.97%  |
| Intel I211 Gigabit Network Connection                                         | 7        | 5.79%   |
| Intel Ethernet Connection I217-LM                                             | 6        | 4.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 6        | 4.96%   |
| Intel 82574L Gigabit Network Connection                                       | 6        | 4.96%   |
| Realtek RTL8125 2.5GbE Controller                                             | 5        | 4.13%   |
| Intel Ethernet Controller I225-V                                              | 4        | 3.31%   |
| Intel Ethernet Connection (7) I219-LM                                         | 4        | 3.31%   |
| Intel Ethernet Connection (2) I219-V                                          | 4        | 3.31%   |
| Intel Ethernet Connection (2) I219-LM                                         | 4        | 3.31%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 4        | 3.31%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 4        | 3.31%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 3        | 2.48%   |
| Intel I350 Gigabit Network Connection                                         | 3        | 2.48%   |
| Intel Ethernet Connection (2) I218-V                                          | 3        | 2.48%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 2        | 1.65%   |
| Intel I210 Gigabit Network Connection                                         | 2        | 1.65%   |
| Intel Ethernet Connection I217-V                                              | 2        | 1.65%   |
| Intel Ethernet Connection (7) I219-V                                          | 2        | 1.65%   |
| Intel Ethernet Connection (2) I218-LM                                         | 2        | 1.65%   |
| Intel 82599 10 Gigabit Dual Port Backplane Connection                         | 2        | 1.65%   |
| Dell iDRAC Virtual NIC                                                        | 2        | 1.65%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 0.83%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 1        | 0.83%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1        | 0.83%   |
| Intel Ethernet Connection (11) I219-V                                         | 1        | 0.83%   |
| Intel 82579V Gigabit Network Connection                                       | 1        | 0.83%   |
| Intel 82575EB Gigabit Network Connection                                      | 1        | 0.83%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 0.83%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 1        | 0.83%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1        | 0.83%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 1        | 0.83%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 1        | 0.83%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express               | 1        | 0.83%   |
| ASIX AX88772A Fast Ethernet                                                   | 1        | 0.83%   |
| ASIX AX88179 Gigabit Ethernet                                                 | 1        | 0.83%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 1        | 0.83%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 87       | 66.41%  |
| WiFi     | 41       | 31.3%   |
| Modem    | 3        | 2.29%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 74       | 83.15%  |
| WiFi     | 15       | 16.85%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 38       | 43.18%  |
| 2     | 26       | 29.55%  |
| 3     | 13       | 14.77%  |
| 6     | 5        | 5.68%   |
| 4     | 5        | 5.68%   |
| 5     | 1        | 1.14%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 72       | 81.82%  |
| Yes  | 16       | 18.18%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 15       | 44.12%  |
| Cambridge Silicon Radio         | 8        | 23.53%  |
| ASUSTek Computer                | 3        | 8.82%   |
| Realtek Semiconductor           | 2        | 5.88%   |
| Qualcomm Atheros Communications | 2        | 5.88%   |
| Micro Star International        | 1        | 2.94%   |
| Integrated System Solution      | 1        | 2.94%   |
| IMC Networks                    | 1        | 2.94%   |
| Broadcom                        | 1        | 2.94%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 8        | 23.53%  |
| Intel Wireless-AC 3168 Bluetooth                      | 3        | 8.82%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 3        | 8.82%   |
| Intel AX210 Bluetooth                                 | 3        | 8.82%   |
| Realtek Bluetooth Radio                               | 2        | 5.88%   |
| Qualcomm Atheros  Bluetooth Device                    | 2        | 5.88%   |
| Intel AX201 Bluetooth                                 | 2        | 5.88%   |
| Intel AX200 Bluetooth                                 | 2        | 5.88%   |
| ASUS BCM20702A0                                       | 2        | 5.88%   |
| Micro Star International Bluetooth Device             | 1        | 2.94%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 1        | 2.94%   |
| Intel Bluetooth wireless interface                    | 1        | 2.94%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1        | 2.94%   |
| IMC Networks BCM20702A0                               | 1        | 2.94%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 1        | 2.94%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 2.94%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 60       | 40%     |
| Nvidia                                       | 42       | 28%     |
| AMD                                          | 23       | 15.33%  |
| Texas Instruments                            | 3        | 2%      |
| Lenovo                                       | 3        | 2%      |
| Creative Labs                                | 3        | 2%      |
| Plantronics                                  | 2        | 1.33%   |
| Logitech                                     | 2        | 1.33%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 0.67%   |
| Tenx Technology                              | 1        | 0.67%   |
| SteelSeries ApS                              | 1        | 0.67%   |
| Sennheiser Communications                    | 1        | 0.67%   |
| RODE Microphones                             | 1        | 0.67%   |
| Micro Star International                     | 1        | 0.67%   |
| JMTek                                        | 1        | 0.67%   |
| Giga-Byte Technology                         | 1        | 0.67%   |
| Dynex                                        | 1        | 0.67%   |
| Creative Technology                          | 1        | 0.67%   |
| Blue Microphones                             | 1        | 0.67%   |
| ASUSTek Computer                             | 1        | 0.67%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 10       | 5.92%   |
| Intel Cannon Lake PCH cAVS                                                 | 9        | 5.33%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 7        | 4.14%   |
| AMD Starship/Matisse HD Audio Controller                                   | 7        | 4.14%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 6        | 3.55%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 6        | 3.55%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5        | 2.96%   |
| Nvidia GP104 High Definition Audio Controller                              | 5        | 2.96%   |
| Nvidia GF108 High Definition Audio Controller                              | 4        | 2.37%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 4        | 2.37%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4        | 2.37%   |
| Intel 200 Series PCH HD Audio                                              | 4        | 2.37%   |
| AMD Family 17h/19h HD Audio Controller                                     | 4        | 2.37%   |
| Texas Instruments PCM2902 Audio Codec                                      | 3        | 1.78%   |
| Nvidia TU106 High Definition Audio Controller                              | 3        | 1.78%   |
| Nvidia GP106 High Definition Audio Controller                              | 3        | 1.78%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3        | 1.78%   |
| Lenovo Thinkcentre TIO24Gen3 for USB-audio                                 | 3        | 1.78%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3        | 1.78%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3        | 1.78%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3        | 1.78%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 3        | 1.78%   |
| Nvidia TU116 High Definition Audio Controller                              | 2        | 1.18%   |
| Nvidia TU104 HD Audio Controller                                           | 2        | 1.18%   |
| Nvidia GM206 High Definition Audio Controller                              | 2        | 1.18%   |
| Nvidia GM204 High Definition Audio Controller                              | 2        | 1.18%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2        | 1.18%   |
| Nvidia GK106 HDMI Audio Controller                                         | 2        | 1.18%   |
| Intel Jasper Lake HD Audio                                                 | 2        | 1.18%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2        | 1.18%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 1.18%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2        | 1.18%   |
| AMD Navi 10 HDMI Audio                                                     | 2        | 1.18%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 2        | 1.18%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2        | 1.18%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID             | 1        | 0.59%   |
| Tenx Technology USB AUDIO                                                  | 1        | 0.59%   |
| SteelSeries ApS SteelSeries Arctis 7                                       | 1        | 0.59%   |
| Sennheiser Communications EPOS ADAPT 1x5T                                  | 1        | 0.59%   |
| RODE Microphones RODE NT-USB                                               | 1        | 0.59%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| SK hynix            | 8        | 16%     |
| Samsung Electronics | 8        | 16%     |
| Micron Technology   | 7        | 14%     |
| Crucial             | 7        | 14%     |
| Kingston            | 5        | 10%     |
| Corsair             | 5        | 10%     |
| G.Skill             | 3        | 6%      |
| Unknown             | 2        | 4%      |
| Unknown (0x0205)    | 1        | 2%      |
| Transcend           | 1        | 2%      |
| Team                | 1        | 2%      |
| Patriot             | 1        | 2%      |
| GOODRAM             | 1        | 2%      |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| SK hynix RAM HMA82GR7MFR8N-UH 16GB DIMM DDR4 2400MT/s   | 2        | 3.64%   |
| SK hynix RAM HMA42GR7MFR4N-TF 16GB DIMM DDR4 2133MT/s   | 2        | 3.64%   |
| Samsung RAM M378A2K43CB1-CTD 16384MB DIMM DDR4 3200MT/s | 2        | 3.64%   |
| Micron RAM 36ASF2G72PZ-2G1A2 16GB DIMM DDR4 2133MT/s    | 2        | 3.64%   |
| Corsair RAM CMK64GX4M2D3600C18 32GB DIMM DDR4 3600MT/s  | 2        | 3.64%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s               | 1        | 1.82%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s            | 1        | 1.82%   |
| Unknown (0x0205) RAM Module 8GB DIMM DDR3 1600MT/s      | 1        | 1.82%   |
| Transcend RAM TS1GLK72V3H 8GB DIMM DDR3 1333MT/s        | 1        | 1.82%   |
| Team RAM TEAMGROUP-ED4-2400 16GB DIMM DDR4 2400MT/s     | 1        | 1.82%   |
| SK hynix RAM Module 16GB Row Of Chips LPDDR4 2933MT/s   | 1        | 1.82%   |
| SK hynix RAM HMT351S6EFR8C-PB 4096MB DIMM DDR3 1333MT/s | 1        | 1.82%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB DIMM DDR3 1333MT/s | 1        | 1.82%   |
| SK hynix RAM HMA851U6CJR6N-VK 4GB DIMM DDR4 2667MT/s    | 1        | 1.82%   |
| SK hynix RAM HMA81GU7AFR8N-UH 8GB DIMM DDR4 2400MT/s    | 1        | 1.82%   |
| Samsung RAM Module 8GB DIMM DDR4 2666MT/s               | 1        | 1.82%   |
| Samsung RAM Module 4GB DIMM DDR4 2133MT/s               | 1        | 1.82%   |
| Samsung RAM Module 16GB DIMM DDR4 2666MT/s              | 1        | 1.82%   |
| Samsung RAM M393A2G40DB0-CPB 16GB DIMM DDR4 2133MT/s    | 1        | 1.82%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s     | 1        | 1.82%   |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR3 1867MT/s     | 1        | 1.82%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3266MT/s     | 1        | 1.82%   |
| Samsung RAM M3 78T5663EH3-CF7 2GB DIMM DDR2 800MT/s     | 1        | 1.82%   |
| Samsung RAM M3 78T2863EHS-CF7 1GB DIMM DDR2 800MT/s     | 1        | 1.82%   |
| Patriot RAM PSD416G26662 16GB DIMM DDR4 2667MT/s        | 1        | 1.82%   |
| Micron RAM Module 4GB DIMM DDR4 2133MT/s                | 1        | 1.82%   |
| Micron RAM 9ASF51272PZ-2G3B1 4GB RIMM DDR4 2400MT/s     | 1        | 1.82%   |
| Micron RAM 36ASF4G72PZ-2G3B1 32GB DIMM DDR4 2400MT/s    | 1        | 1.82%   |
| Micron RAM 16JTF1G64AZ-1G6E1 8192MB DIMM DDR3 1600MT/s  | 1        | 1.82%   |
| Micron RAM 16ATF1G64AZ-2G1B1 8GB DIMM DDR4 2133MT/s     | 1        | 1.82%   |
| Kingston RAM KHX2666C13/16GX 16GB DIMM DDR4 3200MT/s    | 1        | 1.82%   |
| Kingston RAM KHX2400C12D4/8GX 8GB DIMM DDR4 2400MT/s    | 1        | 1.82%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s     | 1        | 1.82%   |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3933MT/s   | 1        | 1.82%   |
| Kingston RAM 9905712-034.A00G 16GB SODIMM DDR4 2400MT/s | 1        | 1.82%   |
| GOODRAM RAM GR1600D364L11S/4G 4GB DIMM DDR3 1600MT/s    | 1        | 1.82%   |
| G.Skill RAM F5-6000J3636F16G 16GB DIMM DDR5 6400MT/s    | 1        | 1.82%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s  | 1        | 1.82%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s    | 1        | 1.82%   |
| Crucial RAM CT8G4S24AM.M8FJ 8GB SODIMM DDR4 2400MT/s    | 1        | 1.82%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Desktops | Percent |
|--------|----------|---------|
| DDR4   | 26       | 59.09%  |
| DDR3   | 10       | 22.73%  |
| SDRAM  | 3        | 6.82%   |
| DRAM   | 2        | 4.55%   |
| LPDDR4 | 1        | 2.27%   |
| DDR5   | 1        | 2.27%   |
| DDR2   | 1        | 2.27%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 39       | 90.7%   |
| SODIMM       | 2        | 4.65%   |
| Row Of Chips | 1        | 2.33%   |
| RIMM         | 1        | 2.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 16384 | 16       | 32.65%  |
| 8192  | 16       | 32.65%  |
| 4096  | 10       | 20.41%  |
| 32768 | 4        | 8.16%   |
| 2048  | 2        | 4.08%   |
| 1024  | 1        | 2.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 2400  | 10       | 20.83%  |
| 1600  | 8        | 16.67%  |
| 3600  | 7        | 14.58%  |
| 2133  | 6        | 12.5%   |
| 1333  | 3        | 6.25%   |
| 3200  | 2        | 4.17%   |
| 2933  | 2        | 4.17%   |
| 2667  | 2        | 4.17%   |
| 6400  | 1        | 2.08%   |
| 3933  | 1        | 2.08%   |
| 3266  | 1        | 2.08%   |
| 2666  | 1        | 2.08%   |
| 2472  | 1        | 2.08%   |
| 2048  | 1        | 2.08%   |
| 1867  | 1        | 2.08%   |
| 800   | 1        | 2.08%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Seiko Epson        | 2        | 33.33%  |
| Canon              | 2        | 33.33%  |
| Hewlett-Packard    | 1        | 16.67%  |
| Brother Industries | 1        | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seiko Epson XP-4100 Series       | 1        | 16.67%  |
| Seiko Epson WF-3520 Series       | 1        | 16.67%  |
| HP LaserJet Professional P 1102w | 1        | 16.67%  |
| Canon E560 series                | 1        | 16.67%  |
| Canon CanoScan LiDE 300          | 1        | 16.67%  |
| Brother DCP-1610W                | 1        | 16.67%  |

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
| Logitech                    | 3        | 17.65%  |
| Hopewin Electronic Material | 3        | 17.65%  |
| Generalplus Technology      | 2        | 11.76%  |
| vivo                        | 1        | 5.88%   |
| Samsung Electronics         | 1        | 5.88%   |
| Ruision                     | 1        | 5.88%   |
| Realtek Semiconductor       | 1        | 5.88%   |
| Microsoft                   | 1        | 5.88%   |
| Microdia                    | 1        | 5.88%   |
| Jieli Technology            | 1        | 5.88%   |
| IMC Networks                | 1        | 5.88%   |
| ARC International           | 1        | 5.88%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Desktops | Percent |
|--------------------------------------------------|----------|---------|
| Hopewin Electronic Material FULL HD 1080P Webcam | 3        | 17.65%  |
| Generalplus GENERAL WEBCAM                       | 2        | 11.76%  |
| vivo V2023                                       | 1        | 5.88%   |
| Samsung Galaxy series, misc. (MTP mode)          | 1        | 5.88%   |
| Ruision UVC Camera                               | 1        | 5.88%   |
| Realtek FULL HD 1080P Webcam                     | 1        | 5.88%   |
| Microsoft LifeCam HD-3000                        | 1        | 5.88%   |
| Microdia USB 2.0 Camera                          | 1        | 5.88%   |
| Logitech Webcam C270                             | 1        | 5.88%   |
| Logitech Webcam C250                             | 1        | 5.88%   |
| Logitech HD Webcam C910                          | 1        | 5.88%   |
| Jieli USB PHY 2.0                                | 1        | 5.88%   |
| IMC Networks XHC Camera                          | 1        | 5.88%   |
| ARC International Camera                         | 1        | 5.88%   |

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
| 0     | 64       | 72.73%  |
| 1     | 12       | 13.64%  |
| 2     | 10       | 11.36%  |
| 5     | 1        | 1.14%   |
| 3     | 1        | 1.14%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Unassigned class         | 14       | 37.84%  |
| Graphics card            | 7        | 18.92%  |
| Communication controller | 7        | 18.92%  |
| Net/wireless             | 6        | 16.22%  |
| Storage/ide              | 1        | 2.7%    |
| Sound                    | 1        | 2.7%    |
| Bluetooth                | 1        | 2.7%    |

